Linux in Argentina - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

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

Total: 1049

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Dell          | Latitude 3410               | [050678128c](https://linux-hardware.org/?probe=050678128c) | Jun 29, 2022 |
| Dell          | Latitude 3590               | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| HP            | ProBook 455 G4              | [f54297787f](https://linux-hardware.org/?probe=f54297787f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| HP            | 255 G3                      | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | Latitude 3590               | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| ASUSTek       | UX410UAK                    | [0d2e384ebf](https://linux-hardware.org/?probe=0d2e384ebf) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a56ff0b014](https://linux-hardware.org/?probe=a56ff0b014) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9481bad179](https://linux-hardware.org/?probe=9481bad179) | Jun 17, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | [91d92999db](https://linux-hardware.org/?probe=91d92999db) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | [41495c085a](https://linux-hardware.org/?probe=41495c085a) | Jun 16, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [a3f29fd594](https://linux-hardware.org/?probe=a3f29fd594) | Jun 14, 2022 |
| HP            | Laptop 15-dw2xxx            | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| HP            | ProBook 440 G4              | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [cae8181e7d](https://linux-hardware.org/?probe=cae8181e7d) | Jun 11, 2022 |
| Gadnic        | NOT00A1                     | [d63fbf4c2e](https://linux-hardware.org/?probe=d63fbf4c2e) | Jun 10, 2022 |
| Dell          | Inspiron 3505               | [9ae6cc8594](https://linux-hardware.org/?probe=9ae6cc8594) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [09d190612b](https://linux-hardware.org/?probe=09d190612b) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [6f33d222cc](https://linux-hardware.org/?probe=6f33d222cc) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [873d9df408](https://linux-hardware.org/?probe=873d9df408) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [474a9da762](https://linux-hardware.org/?probe=474a9da762) | May 31, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [ec364402d8](https://linux-hardware.org/?probe=ec364402d8) | May 31, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| Juana Mans... | SF20GM7                     | [2078b0ab3f](https://linux-hardware.org/?probe=2078b0ab3f) | May 26, 2022 |
| Positivo      | AT510                       | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| Dell          | Inspiron M5030              | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Toshiba       | Unknown                     | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Dell          | Inspiron 3502               | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| ASUSTek       | X555LD                      | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | X555LD                      | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| HP            | Pavilion Notebook           | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Acer          | Swift SF515-51T             | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [40d9831b29](https://linux-hardware.org/?probe=40d9831b29) | May 12, 2022 |
| Positivo      | AT300b                      | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| Dell          | Latitude E6430              | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| HP            | Laptop 15-bs0xx             | [ed1e3083d6](https://linux-hardware.org/?probe=ed1e3083d6) | May 09, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [f3791f34b1](https://linux-hardware.org/?probe=f3791f34b1) | May 02, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [dc1b877e42](https://linux-hardware.org/?probe=dc1b877e42) | May 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| NSX           | SB1402                      | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| Dell          | Latitude 5411               | [34c470e595](https://linux-hardware.org/?probe=34c470e595) | Apr 28, 2022 |
| NOBLEX        | N14WD21                     | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad E470 20H1A01YAC    | [cd8726de3c](https://linux-hardware.org/?probe=cd8726de3c) | Apr 26, 2022 |
| Dell          | Studio 1558                 | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | Notebook                    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| ASUSTek       | X556UB                      | [a9d2922649](https://linux-hardware.org/?probe=a9d2922649) | Apr 23, 2022 |
| ASUSTek       | K53E                        | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [2d0ac286da](https://linux-hardware.org/?probe=2d0ac286da) | Apr 14, 2022 |
| Dell          | Latitude 3520               | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| Advantec      | CX23500W                    | [a3152e0a0f](https://linux-hardware.org/?probe=a3152e0a0f) | Apr 02, 2022 |
| Advantec      | CX23500W                    | [feb5c20169](https://linux-hardware.org/?probe=feb5c20169) | Apr 02, 2022 |
| Exo           | Smart XQ5c                  | [5653a02bd3](https://linux-hardware.org/?probe=5653a02bd3) | Mar 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [14bd2cc137](https://linux-hardware.org/?probe=14bd2cc137) | Mar 31, 2022 |
| Dell          | Latitude 3410               | [fd37f4137d](https://linux-hardware.org/?probe=fd37f4137d) | Mar 30, 2022 |
| HP            | Pavilion 17                 | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | [38700103d3](https://linux-hardware.org/?probe=38700103d3) | Mar 29, 2022 |
| Toshiba       | PORTEGE R935                | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| Positivo      | Z100                        | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| ASUSTek       | G75VW                       | [2e006b534b](https://linux-hardware.org/?probe=2e006b534b) | Mar 25, 2022 |
| HP            | Pavilion g6                 | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| BGH e-Nova    | Unknown                     | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Packard Be... | EasyNote_MX45               | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| HUAWEI        | KPL-W0X                     | [bd7accdfd5](https://linux-hardware.org/?probe=bd7accdfd5) | Mar 20, 2022 |
| NSX           | SB142G                      | [0a13591ca3](https://linux-hardware.org/?probe=0a13591ca3) | Mar 18, 2022 |
| ASUSTek       | X505BP                      | [3dc5b19d13](https://linux-hardware.org/?probe=3dc5b19d13) | Mar 17, 2022 |
| Positivo      | VJF155F11UAR                | [39b60a2ef4](https://linux-hardware.org/?probe=39b60a2ef4) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| Lenovo        | Edge 15 80H1                | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| Dell          | Inspiron 5520               | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Dell          | Inspiron 15-5578            | [c31b5d363f](https://linux-hardware.org/?probe=c31b5d363f) | Mar 10, 2022 |
| NOBLEX        | N14WD21                     | [c166ec8175](https://linux-hardware.org/?probe=c166ec8175) | Mar 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| Dell          | Latitude E5540              | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| Dell          | Inspiron 5593               | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| HP            | Pavilion 17                 | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [bf565614ca](https://linux-hardware.org/?probe=bf565614ca) | Feb 24, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | [6d10cb57e1](https://linux-hardware.org/?probe=6d10cb57e1) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASUSTek       | X55C                        | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |
| Samsung       | SQ35S                       | [7f4f9ad483](https://linux-hardware.org/?probe=7f4f9ad483) | Feb 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | X540UA                      | [681b4aca6f](https://linux-hardware.org/?probe=681b4aca6f) | Feb 16, 2022 |
| Radio Vict... | B34 SLIM                    | [8a100feae7](https://linux-hardware.org/?probe=8a100feae7) | Feb 16, 2022 |
| MSI           | Delta 15 A5EFK              | [0937e1da6a](https://linux-hardware.org/?probe=0937e1da6a) | Feb 14, 2022 |
| MSI           | Delta 15 A5EFK              | [581ebd9976](https://linux-hardware.org/?probe=581ebd9976) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| MSI           | GP72 6QE                    | [d4a2d3bb85](https://linux-hardware.org/?probe=d4a2d3bb85) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | [9409e22a95](https://linux-hardware.org/?probe=9409e22a95) | Feb 12, 2022 |
| Dell          | Inspiron N4010              | [b04de36c04](https://linux-hardware.org/?probe=b04de36c04) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| Sony          | VJFE52A0711H                | [0a29c49c46](https://linux-hardware.org/?probe=0a29c49c46) | Feb 09, 2022 |
| Dell          | Latitude E6410              | [c71db9d118](https://linux-hardware.org/?probe=c71db9d118) | Feb 08, 2022 |
| Dell          | Latitude E6410              | [61aae88463](https://linux-hardware.org/?probe=61aae88463) | Feb 08, 2022 |
| HP            | Pavilion dv6                | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| HP            | Laptop 14-bw0xx             | [fa4a95f3a5](https://linux-hardware.org/?probe=fa4a95f3a5) | Feb 03, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Dell          | Inspiron 3505               | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| Lenovo        | G40-80 80E4                 | [4c27ace709](https://linux-hardware.org/?probe=4c27ace709) | Jan 26, 2022 |
| Samsung       | N150P/N210P/N220P           | [72a04dc661](https://linux-hardware.org/?probe=72a04dc661) | Jan 22, 2022 |
| Standard      | MB50II                      | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [0f956f27ad](https://linux-hardware.org/?probe=0f956f27ad) | Jan 20, 2022 |
| Gadnic        | NOT00A1                     | [f1c6b56aa2](https://linux-hardware.org/?probe=f1c6b56aa2) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| BANGHO        | MAX G0101                   | [0e5d4dfabf](https://linux-hardware.org/?probe=0e5d4dfabf) | Jan 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [b5437027b1](https://linux-hardware.org/?probe=b5437027b1) | Jan 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2b44f3e733](https://linux-hardware.org/?probe=2b44f3e733) | Jan 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [137736d936](https://linux-hardware.org/?probe=137736d936) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Samsung       | N150P/N210P/N220P           | [7d5ceb70bb](https://linux-hardware.org/?probe=7d5ceb70bb) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| Apple         | MacBookPro13,3              | [6b1eb1745e](https://linux-hardware.org/?probe=6b1eb1745e) | Jan 10, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b6b0572310](https://linux-hardware.org/?probe=b6b0572310) | Jan 02, 2022 |
| HUAWEI        | MACH-WX9                    | [dfa1412d12](https://linux-hardware.org/?probe=dfa1412d12) | Jan 01, 2022 |
| Dell          | Latitude E5540              | [1a112d75bc](https://linux-hardware.org/?probe=1a112d75bc) | Jan 01, 2022 |
| Exo           | HR14                        | [3a16049e36](https://linux-hardware.org/?probe=3a16049e36) | Dec 31, 2021 |
| Exo           | HR14                        | [8c3bf46eb1](https://linux-hardware.org/?probe=8c3bf46eb1) | Dec 31, 2021 |
| Dell          | Inspiron 3505               | [c05333a0bc](https://linux-hardware.org/?probe=c05333a0bc) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | G40-80 80E4                 | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| HP            | 15                          | [e0d79905e2](https://linux-hardware.org/?probe=e0d79905e2) | Dec 29, 2021 |
| Lenovo        | G470 20078                  | [d860437585](https://linux-hardware.org/?probe=d860437585) | Dec 28, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [8c9f72d757](https://linux-hardware.org/?probe=8c9f72d757) | Dec 27, 2021 |
| System76      | Lemur Pro                   | [6dbfd95ccb](https://linux-hardware.org/?probe=6dbfd95ccb) | Dec 27, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [64492ac63b](https://linux-hardware.org/?probe=64492ac63b) | Dec 22, 2021 |
| Dell          | Inspiron 3583               | [aaab97a820](https://linux-hardware.org/?probe=aaab97a820) | Dec 19, 2021 |
| System76      | Lemur Pro                   | [aebe0acb39](https://linux-hardware.org/?probe=aebe0acb39) | Dec 18, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [915303d28d](https://linux-hardware.org/?probe=915303d28d) | Dec 16, 2021 |
| HP            | Compaq Presario CQ40        | [15d1b4bba5](https://linux-hardware.org/?probe=15d1b4bba5) | Dec 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23254UY       | [99dbb19723](https://linux-hardware.org/?probe=99dbb19723) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23252CG       | [e2ed9e27c3](https://linux-hardware.org/?probe=e2ed9e27c3) | Dec 14, 2021 |
| ASUSTek       | X541UAK                     | [9c83d97134](https://linux-hardware.org/?probe=9c83d97134) | Dec 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [6df961216e](https://linux-hardware.org/?probe=6df961216e) | Dec 12, 2021 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [481e8486ea](https://linux-hardware.org/?probe=481e8486ea) | Dec 10, 2021 |
| Toshiba       | TE5                         | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [44fb1a2d77](https://linux-hardware.org/?probe=44fb1a2d77) | Dec 09, 2021 |
| System76      | Lemur Pro                   | [6e54a15cf2](https://linux-hardware.org/?probe=6e54a15cf2) | Dec 08, 2021 |
| Exo           | C14C                        | [2e0765b245](https://linux-hardware.org/?probe=2e0765b245) | Dec 08, 2021 |
| Exo           | C14C                        | [1d4221ab9e](https://linux-hardware.org/?probe=1d4221ab9e) | Dec 06, 2021 |
| Positivo      | AT300b                      | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| Acer          | Aspire 5251                 | [30ef0eefda](https://linux-hardware.org/?probe=30ef0eefda) | Dec 04, 2021 |
| HP            | 250 G7 Notebook PC          | [3f21e28b42](https://linux-hardware.org/?probe=3f21e28b42) | Dec 03, 2021 |
| BANGHO        | CLOUD                       | [214c91e455](https://linux-hardware.org/?probe=214c91e455) | Dec 01, 2021 |
| BANGHO        | MOV                         | [3e5867cd6a](https://linux-hardware.org/?probe=3e5867cd6a) | Dec 01, 2021 |
| Exo           | Smart Serie M               | [cbf705cf51](https://linux-hardware.org/?probe=cbf705cf51) | Nov 22, 2021 |
| ASUSTek       | G551JW                      | [5f018a92ee](https://linux-hardware.org/?probe=5f018a92ee) | Nov 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| Acer          | Aspire ES1-572              | [871bd7121a](https://linux-hardware.org/?probe=871bd7121a) | Nov 11, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [c282ff2172](https://linux-hardware.org/?probe=c282ff2172) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [eb66540889](https://linux-hardware.org/?probe=eb66540889) | Nov 10, 2021 |
| Lenovo        | 14w 81MQ00AHAR              | [17785cda04](https://linux-hardware.org/?probe=17785cda04) | Nov 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [fbc9822ad6](https://linux-hardware.org/?probe=fbc9822ad6) | Nov 09, 2021 |
| Quanta        | TW9/SW9                     | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| BANGHO        | MOV                         | [9c2b56129e](https://linux-hardware.org/?probe=9c2b56129e) | Nov 06, 2021 |
| Lenovo        | G40-80 80E4                 | [57b9418a9c](https://linux-hardware.org/?probe=57b9418a9c) | Nov 05, 2021 |
| ASUSTek       | K52JT                       | [1f65cc3bef](https://linux-hardware.org/?probe=1f65cc3bef) | Nov 05, 2021 |
| HP            | 15                          | [0719e191d4](https://linux-hardware.org/?probe=0719e191d4) | Nov 04, 2021 |
| HP            | 630                         | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| Lenovo        | G40-80 80E4                 | [f89ddc0ebd](https://linux-hardware.org/?probe=f89ddc0ebd) | Nov 02, 2021 |
| Intel         | HURONRIVER                  | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| HP            | Pavilion dv4                | [f0ae431e2c](https://linux-hardware.org/?probe=f0ae431e2c) | Oct 26, 2021 |
| Apple         | MacBookPro9,2               | [c739ed76e3](https://linux-hardware.org/?probe=c739ed76e3) | Oct 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [7877fc09ba](https://linux-hardware.org/?probe=7877fc09ba) | Oct 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [3115478a9b](https://linux-hardware.org/?probe=3115478a9b) | Oct 20, 2021 |
| Apple         | MacBookAir4,2               | [f092832b93](https://linux-hardware.org/?probe=f092832b93) | Oct 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Toshiba       | Satellite A505              | [a955d2e293](https://linux-hardware.org/?probe=a955d2e293) | Oct 18, 2021 |
| Dell          | Inspiron 5423               | [f31078afd8](https://linux-hardware.org/?probe=f31078afd8) | Oct 18, 2021 |
| Apple         | MacBook3,1                  | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| HP            | Mini 110-3000               | [ee2ce4e3b9](https://linux-hardware.org/?probe=ee2ce4e3b9) | Oct 14, 2021 |
| NOBLEX        | E11IS2                      | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| Dell          | Latitude 5480               | [3ed90a1781](https://linux-hardware.org/?probe=3ed90a1781) | Oct 07, 2021 |
| Apple         | MacBookAir4,2               | [8163e064d3](https://linux-hardware.org/?probe=8163e064d3) | Oct 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [c111f21064](https://linux-hardware.org/?probe=c111f21064) | Oct 05, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| Dell          | G3 3779                     | [0257eadb71](https://linux-hardware.org/?probe=0257eadb71) | Oct 04, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bea39ba8be](https://linux-hardware.org/?probe=bea39ba8be) | Oct 03, 2021 |
| Dell          | Inspiron 15-3552            | [f1b660b91c](https://linux-hardware.org/?probe=f1b660b91c) | Oct 02, 2021 |
| Acer          | Aspire E5-432               | [2d6ea0cb46](https://linux-hardware.org/?probe=2d6ea0cb46) | Oct 02, 2021 |
| Lenovo        | ThinkPad E495 20NES0RR00    | [016f532a15](https://linux-hardware.org/?probe=016f532a15) | Oct 02, 2021 |
| HP            | EliteBook 840 G6            | [cd2412d37e](https://linux-hardware.org/?probe=cd2412d37e) | Oct 01, 2021 |
| ASUSTek       | K53E                        | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| Exo           | SmartPro Q6                 | [5986a21d65](https://linux-hardware.org/?probe=5986a21d65) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo        | V15-IIL 82C5                | [781b63209d](https://linux-hardware.org/?probe=781b63209d) | Sep 28, 2021 |
| Acer          | Aspire 2930Z                | [95cf81718f](https://linux-hardware.org/?probe=95cf81718f) | Sep 28, 2021 |
| Dell          | Inspiron 3583               | [f936e50be4](https://linux-hardware.org/?probe=f936e50be4) | Sep 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [445b864b6e](https://linux-hardware.org/?probe=445b864b6e) | Sep 25, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Acer          | Aspire 2930Z                | [837506804e](https://linux-hardware.org/?probe=837506804e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | [720324554e](https://linux-hardware.org/?probe=720324554e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | [85e19ff9ba](https://linux-hardware.org/?probe=85e19ff9ba) | Sep 20, 2021 |
| Lenovo        | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| Lenovo        | V330-15IKB 81AX             | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| Positivo      | SW6H                        | [2653f4ff4b](https://linux-hardware.org/?probe=2653f4ff4b) | Sep 12, 2021 |
| Dell          | Inspiron 1525               | [c9a8c369e7](https://linux-hardware.org/?probe=c9a8c369e7) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | [361beeda3d](https://linux-hardware.org/?probe=361beeda3d) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Intel         | Pine Trail - M Revision ... | [147f6959ad](https://linux-hardware.org/?probe=147f6959ad) | Sep 08, 2021 |
| Sony          | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [409ed1f8a4](https://linux-hardware.org/?probe=409ed1f8a4) | Sep 06, 2021 |
| Lenovo        | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [2140460960](https://linux-hardware.org/?probe=2140460960) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e9da9320c](https://linux-hardware.org/?probe=0e9da9320c) | Sep 03, 2021 |
| Lenovo        | G470 20078                  | [b480871bf8](https://linux-hardware.org/?probe=b480871bf8) | Sep 02, 2021 |
| BANGHO        | MAX G0101                   | [88ac236a11](https://linux-hardware.org/?probe=88ac236a11) | Aug 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6545        | [f597bdfe1a](https://linux-hardware.org/?probe=f597bdfe1a) | Aug 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [97afdfd346](https://linux-hardware.org/?probe=97afdfd346) | Aug 29, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| BANGHO        | MOV                         | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| Positivo      | Unknown                     | [28bac734c5](https://linux-hardware.org/?probe=28bac734c5) | Aug 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [be114a1393](https://linux-hardware.org/?probe=be114a1393) | Aug 23, 2021 |
| Dell          | Latitude 7400               | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| Dell          | Inspiron 5559               | [768bf35df4](https://linux-hardware.org/?probe=768bf35df4) | Aug 20, 2021 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [6d7fb6d592](https://linux-hardware.org/?probe=6d7fb6d592) | Aug 19, 2021 |
| Dell          | Inspiron N4010              | [c83e0428a8](https://linux-hardware.org/?probe=c83e0428a8) | Aug 17, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [6e32aa4ffd](https://linux-hardware.org/?probe=6e32aa4ffd) | Aug 17, 2021 |
| Lenovo        | B50-80 80EW                 | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [668328ae19](https://linux-hardware.org/?probe=668328ae19) | Aug 12, 2021 |
| Lenovo        | G40-80 80E4                 | [acd155c49f](https://linux-hardware.org/?probe=acd155c49f) | Aug 11, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [76ee9bfbac](https://linux-hardware.org/?probe=76ee9bfbac) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f1124f1fd](https://linux-hardware.org/?probe=8f1124f1fd) | Aug 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a4ba68cc4e](https://linux-hardware.org/?probe=a4ba68cc4e) | Aug 06, 2021 |
| Lenovo        | IdeaPad U310                | [f57c372664](https://linux-hardware.org/?probe=f57c372664) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d09a20ffb6](https://linux-hardware.org/?probe=d09a20ffb6) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d1450d6167](https://linux-hardware.org/?probe=d1450d6167) | Jul 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c5adb7024d](https://linux-hardware.org/?probe=c5adb7024d) | Jul 30, 2021 |
| Lenovo        | G485                        | [1b8322cbee](https://linux-hardware.org/?probe=1b8322cbee) | Jul 29, 2021 |
| Lenovo        | G485                        | [19fb967e90](https://linux-hardware.org/?probe=19fb967e90) | Jul 29, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| Positivo      | Unknown                     | [f64cbc61eb](https://linux-hardware.org/?probe=f64cbc61eb) | Jul 26, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [bd29e505b9](https://linux-hardware.org/?probe=bd29e505b9) | Jul 24, 2021 |
| Lenovo        | G485                        | [0810c75be3](https://linux-hardware.org/?probe=0810c75be3) | Jul 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [87370c4ac2](https://linux-hardware.org/?probe=87370c4ac2) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b5194fe4e7](https://linux-hardware.org/?probe=b5194fe4e7) | Jul 20, 2021 |
| Lenovo        | G485                        | [aa805dfe8d](https://linux-hardware.org/?probe=aa805dfe8d) | Jul 20, 2021 |
| HP            | ENVY Spectre XT Ultraboo... | [bf877db72a](https://linux-hardware.org/?probe=bf877db72a) | Jul 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [03ffd337ec](https://linux-hardware.org/?probe=03ffd337ec) | Jul 16, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2d432c99d0](https://linux-hardware.org/?probe=2d432c99d0) | Jul 13, 2021 |
| HP            | 250 G5 Notebook PC          | [f7013f52d0](https://linux-hardware.org/?probe=f7013f52d0) | Jul 12, 2021 |
| ASUSTek       | N53SV                       | [8044015dd8](https://linux-hardware.org/?probe=8044015dd8) | Jul 12, 2021 |
| HP            | ProBook 445 G7              | [4f0ee9421b](https://linux-hardware.org/?probe=4f0ee9421b) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f5ed33e46](https://linux-hardware.org/?probe=8f5ed33e46) | Jul 12, 2021 |
| Dell          | G3 3779                     | [2b3dc1130d](https://linux-hardware.org/?probe=2b3dc1130d) | Jul 09, 2021 |
| Dell          | G3 3779                     | [a7bcade120](https://linux-hardware.org/?probe=a7bcade120) | Jul 09, 2021 |
| Dell          | Latitude 3510               | [c98fdfc9bc](https://linux-hardware.org/?probe=c98fdfc9bc) | Jul 06, 2021 |
| Toshiba       | Unknown                     | [fd862ec37e](https://linux-hardware.org/?probe=fd862ec37e) | Jul 05, 2021 |
| Dell          | Latitude 3510               | [0b97d64290](https://linux-hardware.org/?probe=0b97d64290) | Jul 03, 2021 |
| Dell          | Latitude 7490               | [a57352ca65](https://linux-hardware.org/?probe=a57352ca65) | Jul 02, 2021 |
| System76      | Oryx Pro                    | [7ccf59ae28](https://linux-hardware.org/?probe=7ccf59ae28) | Jun 28, 2021 |
| Dell          | Latitude E6400              | [d638a1b2b6](https://linux-hardware.org/?probe=d638a1b2b6) | Jun 28, 2021 |
| Dell          | Inspiron 7773               | [fb0644646a](https://linux-hardware.org/?probe=fb0644646a) | Jun 28, 2021 |
| ASUSTek       | X455LJ                      | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [795eda0f4c](https://linux-hardware.org/?probe=795eda0f4c) | Jun 27, 2021 |
| HP            | Pavilion dv6                | [13f36adbb0](https://linux-hardware.org/?probe=13f36adbb0) | Jun 27, 2021 |
| Lenovo        | ThinkPad E14 20RBS1RA00     | [d555c56ade](https://linux-hardware.org/?probe=d555c56ade) | Jun 27, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Acer          | Aspire E5-573               | [22e59e4d90](https://linux-hardware.org/?probe=22e59e4d90) | Jun 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3489fe1584](https://linux-hardware.org/?probe=3489fe1584) | Jun 18, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| HP            | 250 G5 Notebook PC          | [4699d3c195](https://linux-hardware.org/?probe=4699d3c195) | Jun 10, 2021 |
| Pegatron      | A15                         | [9156525a1e](https://linux-hardware.org/?probe=9156525a1e) | Jun 06, 2021 |
| Acer          | Aspire V3-551               | [ba274d73f0](https://linux-hardware.org/?probe=ba274d73f0) | Jun 04, 2021 |
| HP            | Pavilion Notebook           | [a4feb93464](https://linux-hardware.org/?probe=a4feb93464) | Jun 02, 2021 |
| ASUSTek       | X541NA                      | [daad255c87](https://linux-hardware.org/?probe=daad255c87) | Jun 01, 2021 |
| Sony          | VGN-NR230FE                 | [b97d7a8c66](https://linux-hardware.org/?probe=b97d7a8c66) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| ADMIRAL       | ADC14                       | [1cd2066013](https://linux-hardware.org/?probe=1cd2066013) | May 29, 2021 |
| ADMIRAL       | ADC14                       | [d3955b8ca9](https://linux-hardware.org/?probe=d3955b8ca9) | May 29, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [eee4dbbb99](https://linux-hardware.org/?probe=eee4dbbb99) | May 28, 2021 |
| Acer          | Aspire ES1-572              | [2dd5a68280](https://linux-hardware.org/?probe=2dd5a68280) | May 27, 2021 |
| Sony          | VPCEH35FM                   | [f88d733f75](https://linux-hardware.org/?probe=f88d733f75) | May 27, 2021 |
| Sony          | VPCEH35FM                   | [309cc53bcf](https://linux-hardware.org/?probe=309cc53bcf) | May 27, 2021 |
| Lenovo        | G40-30 80FY                 | [a890a2c019](https://linux-hardware.org/?probe=a890a2c019) | May 26, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [e4c4563465](https://linux-hardware.org/?probe=e4c4563465) | May 24, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f8b9508953](https://linux-hardware.org/?probe=f8b9508953) | May 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [170b220f5b](https://linux-hardware.org/?probe=170b220f5b) | May 23, 2021 |
| Samsung       | N150P/N210P/N220P           | [d4548d357f](https://linux-hardware.org/?probe=d4548d357f) | May 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [5756ecab4b](https://linux-hardware.org/?probe=5756ecab4b) | May 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [0f8deb2aeb](https://linux-hardware.org/?probe=0f8deb2aeb) | May 21, 2021 |
| Lenovo        | V15-ADA 82C7                | [a36a726bba](https://linux-hardware.org/?probe=a36a726bba) | May 18, 2021 |
| Dell          | Latitude 7490               | [b3010001a3](https://linux-hardware.org/?probe=b3010001a3) | May 18, 2021 |
| Dell          | Inspiron 1440               | [d0f761fa17](https://linux-hardware.org/?probe=d0f761fa17) | May 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e32d9effa0](https://linux-hardware.org/?probe=e32d9effa0) | May 17, 2021 |
| Coradir       | Coradir/ES10IS5             | [60844ab595](https://linux-hardware.org/?probe=60844ab595) | May 17, 2021 |
| Coradir       | Coradir/ES10IS5             | [acae784622](https://linux-hardware.org/?probe=acae784622) | May 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [df1bd5c40d](https://linux-hardware.org/?probe=df1bd5c40d) | May 16, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [86de26c862](https://linux-hardware.org/?probe=86de26c862) | May 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1ce350fb27](https://linux-hardware.org/?probe=1ce350fb27) | May 16, 2021 |
| Sony          | VPCEG11FX                   | [b17f63c46c](https://linux-hardware.org/?probe=b17f63c46c) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d311e9743d](https://linux-hardware.org/?probe=d311e9743d) | May 15, 2021 |
| Dell          | Inspiron 14-3467            | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| HP            | ENVY Spectre XT Ultraboo... | [b59cb43ed6](https://linux-hardware.org/?probe=b59cb43ed6) | May 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS04V0... | [18da93a841](https://linux-hardware.org/?probe=18da93a841) | May 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942ece6e49](https://linux-hardware.org/?probe=942ece6e49) | May 12, 2021 |
| HP            | Pavilion Notebook           | [435e18816a](https://linux-hardware.org/?probe=435e18816a) | May 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c9b4ee21fd](https://linux-hardware.org/?probe=c9b4ee21fd) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| Toshiba       | Satellite P55t-B            | [e7f87f2061](https://linux-hardware.org/?probe=e7f87f2061) | May 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e313b9e956](https://linux-hardware.org/?probe=e313b9e956) | May 06, 2021 |
| Acer          | AOD255E                     | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3401ccaf08](https://linux-hardware.org/?probe=3401ccaf08) | Apr 30, 2021 |
| Acer          | Aspire A315-56              | [ab06ace460](https://linux-hardware.org/?probe=ab06ace460) | Apr 29, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [b4ec0e1cfe](https://linux-hardware.org/?probe=b4ec0e1cfe) | Apr 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [c5ed725f00](https://linux-hardware.org/?probe=c5ed725f00) | Apr 29, 2021 |
| HP            | EliteBook 820 G3            | [26c2c579ee](https://linux-hardware.org/?probe=26c2c579ee) | Apr 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [90bc32f31e](https://linux-hardware.org/?probe=90bc32f31e) | Apr 27, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [323f443cc2](https://linux-hardware.org/?probe=323f443cc2) | Apr 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [5e53a72f7f](https://linux-hardware.org/?probe=5e53a72f7f) | Apr 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [32062fd103](https://linux-hardware.org/?probe=32062fd103) | Apr 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fab2c07bc0](https://linux-hardware.org/?probe=fab2c07bc0) | Apr 24, 2021 |
| Dell          | Inspiron 7375               | [94102dff26](https://linux-hardware.org/?probe=94102dff26) | Apr 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d6081e3a7f](https://linux-hardware.org/?probe=d6081e3a7f) | Apr 24, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [c76e692770](https://linux-hardware.org/?probe=c76e692770) | Apr 23, 2021 |
| HP            | G42                         | [3f45a4f9fb](https://linux-hardware.org/?probe=3f45a4f9fb) | Apr 21, 2021 |
| HP            | G42                         | [053f83f355](https://linux-hardware.org/?probe=053f83f355) | Apr 20, 2021 |
| Coradir       | Coradir/ES10IS5             | [74f5215b3f](https://linux-hardware.org/?probe=74f5215b3f) | Apr 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [81567e2bff](https://linux-hardware.org/?probe=81567e2bff) | Apr 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e813571c48](https://linux-hardware.org/?probe=e813571c48) | Apr 20, 2021 |
| NOBLEX        | SF20BA                      | [565b65be26](https://linux-hardware.org/?probe=565b65be26) | Apr 18, 2021 |
| Lenovo        | V330-14ARR 81B1             | [d79109ba72](https://linux-hardware.org/?probe=d79109ba72) | Apr 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [530547c053](https://linux-hardware.org/?probe=530547c053) | Apr 14, 2021 |
| ASHI          | Unknown                     | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| HP            | Pavilion 17                 | [d2e2723620](https://linux-hardware.org/?probe=d2e2723620) | Apr 09, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [c3c1aa5184](https://linux-hardware.org/?probe=c3c1aa5184) | Apr 05, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [8d8f1e3c82](https://linux-hardware.org/?probe=8d8f1e3c82) | Apr 05, 2021 |
| PCBOX         | Kant                        | [b7f72a7573](https://linux-hardware.org/?probe=b7f72a7573) | Apr 02, 2021 |
| Dell          | Latitude 5510               | [a7de662ab0](https://linux-hardware.org/?probe=a7de662ab0) | Mar 29, 2021 |
| Dell          | Latitude 5510               | [90267d4625](https://linux-hardware.org/?probe=90267d4625) | Mar 29, 2021 |
| Compal        | NBLBX                       | [37080a9fbd](https://linux-hardware.org/?probe=37080a9fbd) | Mar 29, 2021 |
| Lenovo        | V330-15IKB 81AX             | [efff6e4c8c](https://linux-hardware.org/?probe=efff6e4c8c) | Mar 28, 2021 |
| Compal        | NBLBX                       | [3dcb5c4719](https://linux-hardware.org/?probe=3dcb5c4719) | Mar 27, 2021 |
| Coradir       | Coradir/ES10IS5             | [da31536305](https://linux-hardware.org/?probe=da31536305) | Mar 26, 2021 |
| Dell          | Inspiron 5558               | [49c7a18f18](https://linux-hardware.org/?probe=49c7a18f18) | Mar 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [78d08afb9f](https://linux-hardware.org/?probe=78d08afb9f) | Mar 23, 2021 |
| Lenovo        | ThinkPad X390 20Q1S01J00    | [a67fd9412a](https://linux-hardware.org/?probe=a67fd9412a) | Mar 21, 2021 |
| Lenovo        | V330-15IKB 81AX             | [dde152f842](https://linux-hardware.org/?probe=dde152f842) | Mar 19, 2021 |
| Exo           | Smart Serie C               | [ac4e591b39](https://linux-hardware.org/?probe=ac4e591b39) | Mar 18, 2021 |
| HP            | Compaq Presario CQ50        | [d548875719](https://linux-hardware.org/?probe=d548875719) | Mar 18, 2021 |
| Compal        | QAT10                       | [e0096fed67](https://linux-hardware.org/?probe=e0096fed67) | Mar 17, 2021 |
| Compal        | QAT10                       | [9886710c4a](https://linux-hardware.org/?probe=9886710c4a) | Mar 17, 2021 |
| Sony          | SVF14214CLW                 | [10c62e635e](https://linux-hardware.org/?probe=10c62e635e) | Mar 17, 2021 |
| ASUSTek       | K53E                        | [9f263fff1b](https://linux-hardware.org/?probe=9f263fff1b) | Mar 16, 2021 |
| Clevo         | M7x0S                       | [3a372bea27](https://linux-hardware.org/?probe=3a372bea27) | Mar 15, 2021 |
| Clevo         | M7x0S                       | [7d9fca62d2](https://linux-hardware.org/?probe=7d9fca62d2) | Mar 15, 2021 |
| ASUSTek       | K53E                        | [00b42a225f](https://linux-hardware.org/?probe=00b42a225f) | Mar 14, 2021 |
| Lenovo        | G560 0679                   | [e3e4d139c9](https://linux-hardware.org/?probe=e3e4d139c9) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1c68dc36aa](https://linux-hardware.org/?probe=1c68dc36aa) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e3489945bc](https://linux-hardware.org/?probe=e3489945bc) | Mar 13, 2021 |
| Exo           | C14C                        | [21f9a60600](https://linux-hardware.org/?probe=21f9a60600) | Mar 12, 2021 |
| HP            | Pavilion dv7                | [c358c5da72](https://linux-hardware.org/?probe=c358c5da72) | Mar 12, 2021 |
| Lenovo        | V330-15IKB 81AX             | [cd79de8b59](https://linux-hardware.org/?probe=cd79de8b59) | Mar 06, 2021 |
| HP            | 15                          | [5a6c144963](https://linux-hardware.org/?probe=5a6c144963) | Mar 03, 2021 |
| Compal        | PCW20                       | [687204c549](https://linux-hardware.org/?probe=687204c549) | Feb 28, 2021 |
| Dell          | Inspiron 3442               | [93cdabaff0](https://linux-hardware.org/?probe=93cdabaff0) | Feb 27, 2021 |
| Lenovo        | G480 20150                  | [fd423f422e](https://linux-hardware.org/?probe=fd423f422e) | Feb 27, 2021 |
| ASUSTek       | UX303UA                     | [4f9e891679](https://linux-hardware.org/?probe=4f9e891679) | Feb 27, 2021 |
| Acer          | Aspire 7560                 | [4a4a042dd5](https://linux-hardware.org/?probe=4a4a042dd5) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| HP            | 15                          | [2bccfa19ed](https://linux-hardware.org/?probe=2bccfa19ed) | Feb 25, 2021 |
| HP            | 15                          | [26e1784265](https://linux-hardware.org/?probe=26e1784265) | Feb 24, 2021 |
| Acer          | Aspire V3-471G              | [9679f4b721](https://linux-hardware.org/?probe=9679f4b721) | Feb 23, 2021 |
| Dell          | Latitude 7490               | [54e871ca5d](https://linux-hardware.org/?probe=54e871ca5d) | Feb 23, 2021 |
| Dell          | Latitude 7490               | [c8060ae48c](https://linux-hardware.org/?probe=c8060ae48c) | Feb 23, 2021 |
| Lenovo        | G50-80 Touch 80KR           | [857e2d24ec](https://linux-hardware.org/?probe=857e2d24ec) | Feb 22, 2021 |
| Lenovo        | 3000 N100 0689A31           | [2e87cb3413](https://linux-hardware.org/?probe=2e87cb3413) | Feb 21, 2021 |
| HP            | Pavilion 17                 | [690ee9606a](https://linux-hardware.org/?probe=690ee9606a) | Feb 19, 2021 |
| Compal        | PCW20                       | [59e7060e52](https://linux-hardware.org/?probe=59e7060e52) | Feb 17, 2021 |
| Lenovo        | ThinkPad P52 20MAS2NV00     | [fd1c22df8f](https://linux-hardware.org/?probe=fd1c22df8f) | Feb 16, 2021 |
| Dell          | Inspiron 1525               | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell          | Inspiron 1525               | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Sony          | SVF14214CLW                 | [939765811b](https://linux-hardware.org/?probe=939765811b) | Feb 15, 2021 |
| Dell          | Precision M4500             | [4afe123de3](https://linux-hardware.org/?probe=4afe123de3) | Feb 14, 2021 |
| Sony          | SVF14214CLW                 | [ff19a2061a](https://linux-hardware.org/?probe=ff19a2061a) | Feb 14, 2021 |
| HP            | Pavilion dm1                | [89fba540d9](https://linux-hardware.org/?probe=89fba540d9) | Feb 14, 2021 |
| Intel         | powered classmate PC        | [dd8b22c3e5](https://linux-hardware.org/?probe=dd8b22c3e5) | Feb 13, 2021 |
| ASUSTek       | K53E                        | [87f7d00f4b](https://linux-hardware.org/?probe=87f7d00f4b) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ee1be31aa](https://linux-hardware.org/?probe=4ee1be31aa) | Feb 12, 2021 |
| Lenovo        | ThinkPad T430 2349DS5       | [11bb3b276a](https://linux-hardware.org/?probe=11bb3b276a) | Feb 11, 2021 |
| Lenovo        | ThinkPad T430 2349DS5       | [9b5e541bad](https://linux-hardware.org/?probe=9b5e541bad) | Feb 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [e0e0f96ce4](https://linux-hardware.org/?probe=e0e0f96ce4) | Feb 11, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8f7b8ab812](https://linux-hardware.org/?probe=8f7b8ab812) | Feb 11, 2021 |
| ASUSTek       | X541NA                      | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Dell          | Inspiron 3442               | [219cd8abba](https://linux-hardware.org/?probe=219cd8abba) | Feb 04, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5d33c20e50](https://linux-hardware.org/?probe=5d33c20e50) | Feb 03, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [a6879fb982](https://linux-hardware.org/?probe=a6879fb982) | Feb 02, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71d08f3561](https://linux-hardware.org/?probe=71d08f3561) | Feb 01, 2021 |
| Acer          | Aspire ES1-572              | [09f8b1e97b](https://linux-hardware.org/?probe=09f8b1e97b) | Jan 31, 2021 |
| HP            | 250 G7 Notebook PC          | [0aeff90461](https://linux-hardware.org/?probe=0aeff90461) | Jan 31, 2021 |
| Lenovo        | G550 2958                   | [bef495cadc](https://linux-hardware.org/?probe=bef495cadc) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| Olidata       | U40SI1                      | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| Dell          | Latitude E6510              | [08ac5e5f3c](https://linux-hardware.org/?probe=08ac5e5f3c) | Jan 27, 2021 |
| Dell          | Latitude E6510              | [b65c6893f4](https://linux-hardware.org/?probe=b65c6893f4) | Jan 27, 2021 |
| BANGHO        | W240HU/W250HUQ              | [d962a9f838](https://linux-hardware.org/?probe=d962a9f838) | Jan 26, 2021 |
| ASUSTek       | N53SM                       | [197a025cca](https://linux-hardware.org/?probe=197a025cca) | Jan 24, 2021 |
| HP            | EliteBook 840 G1            | [e3a3b60c09](https://linux-hardware.org/?probe=e3a3b60c09) | Jan 23, 2021 |
| Dell          | Latitude 7400               | [36a1fc3e55](https://linux-hardware.org/?probe=36a1fc3e55) | Jan 18, 2021 |
| HP            | Pavilion 17                 | [1eaf2b8cd5](https://linux-hardware.org/?probe=1eaf2b8cd5) | Jan 17, 2021 |
| BANGHO        | CLOUD                       | [0c28cb5279](https://linux-hardware.org/?probe=0c28cb5279) | Jan 17, 2021 |
| BANGHO        | CLOUD                       | [be4e793cc7](https://linux-hardware.org/?probe=be4e793cc7) | Jan 15, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [8b6ac084cb](https://linux-hardware.org/?probe=8b6ac084cb) | Jan 12, 2021 |
| Dell          | Inspiron 3421               | [e8894b6d12](https://linux-hardware.org/?probe=e8894b6d12) | Jan 11, 2021 |
| HP            | Pavilion dv6700             | [a0dd739d75](https://linux-hardware.org/?probe=a0dd739d75) | Jan 09, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2f225d37e0](https://linux-hardware.org/?probe=2f225d37e0) | Jan 04, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Sony          | VPCYB35AL                   | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Dell          | Inspiron 5559               | [d5fb3b86bb](https://linux-hardware.org/?probe=d5fb3b86bb) | Jan 02, 2021 |
| Insyde        | CherryTrail                 | [5e23a44a4b](https://linux-hardware.org/?probe=5e23a44a4b) | Jan 02, 2021 |
| Insyde        | CherryTrail                 | [d672afb37f](https://linux-hardware.org/?probe=d672afb37f) | Jan 02, 2021 |
| BGH           | C46G                        | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| ASUSTek       | X541UAK                     | [87ed604a48](https://linux-hardware.org/?probe=87ed604a48) | Dec 29, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [ca0a06995e](https://linux-hardware.org/?probe=ca0a06995e) | Dec 28, 2020 |
| ASUSTek       | X541UAK                     | [e77cde62a0](https://linux-hardware.org/?probe=e77cde62a0) | Dec 27, 2020 |
| BGH           | C46G                        | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| HP            | 250 G7 Notebook PC          | [d0c7e162ef](https://linux-hardware.org/?probe=d0c7e162ef) | Dec 24, 2020 |
| HP            | 250 G7 Notebook PC          | [d20e564de9](https://linux-hardware.org/?probe=d20e564de9) | Dec 24, 2020 |
| Sony          | VPCYB35AL                   | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| HP            | 250 G7 Notebook PC          | [c282c0612b](https://linux-hardware.org/?probe=c282c0612b) | Dec 22, 2020 |
| HP            | 250 G7 Notebook PC          | [b69724eac9](https://linux-hardware.org/?probe=b69724eac9) | Dec 22, 2020 |
| Apple         | MacBookAir6,1               | [19e45fe217](https://linux-hardware.org/?probe=19e45fe217) | Dec 20, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad E470 20H1S0C500    | [84b6435606](https://linux-hardware.org/?probe=84b6435606) | Dec 16, 2020 |
| Lenovo        | ThinkPad E470 20H1S0C500    | [5b00f8ad25](https://linux-hardware.org/?probe=5b00f8ad25) | Dec 16, 2020 |
| Lenovo        | ThinkPad T430 2349DS5       | [806ce0429e](https://linux-hardware.org/?probe=806ce0429e) | Dec 16, 2020 |
| ASUSTek       | X455LJ                      | [54683be664](https://linux-hardware.org/?probe=54683be664) | Dec 15, 2020 |
| ASUSTek       | N56JN                       | [9ef963fbfe](https://linux-hardware.org/?probe=9ef963fbfe) | Dec 14, 2020 |
| Apple         | MacBook3,1                  | [12c6cc3bbb](https://linux-hardware.org/?probe=12c6cc3bbb) | Dec 13, 2020 |
| Apple         | MacBook3,1                  | [7a4425e392](https://linux-hardware.org/?probe=7a4425e392) | Dec 13, 2020 |
| ASUSTek       | X455LJ                      | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Dell          | Latitude 5510               | [0911fc0b09](https://linux-hardware.org/?probe=0911fc0b09) | Dec 10, 2020 |
| Dell          | Inspiron 5567               | [ea61f719d6](https://linux-hardware.org/?probe=ea61f719d6) | Dec 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9114238a33](https://linux-hardware.org/?probe=9114238a33) | Dec 08, 2020 |
| Lenovo        | G70-35 80Q5                 | [4f81abcc73](https://linux-hardware.org/?probe=4f81abcc73) | Dec 07, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [dc0106061d](https://linux-hardware.org/?probe=dc0106061d) | Dec 07, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0c33131abc](https://linux-hardware.org/?probe=0c33131abc) | Dec 07, 2020 |
| Lenovo        | IdeaPad Z470                | [f09e882b17](https://linux-hardware.org/?probe=f09e882b17) | Dec 07, 2020 |
| Toshiba       | Unknown                     | [dff44dc3ed](https://linux-hardware.org/?probe=dff44dc3ed) | Dec 05, 2020 |
| Samsung       | 550P5C/550P7C               | [452ab979b9](https://linux-hardware.org/?probe=452ab979b9) | Dec 05, 2020 |
| Dell          | Latitude 3410               | [c7c26cc9e6](https://linux-hardware.org/?probe=c7c26cc9e6) | Dec 03, 2020 |
| BANGHO        | MOV                         | [237e3b0449](https://linux-hardware.org/?probe=237e3b0449) | Dec 03, 2020 |
| Lenovo        | G580 20150                  | [c5a6c5f7b8](https://linux-hardware.org/?probe=c5a6c5f7b8) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [29f2114ef7](https://linux-hardware.org/?probe=29f2114ef7) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [16c932a6df](https://linux-hardware.org/?probe=16c932a6df) | Nov 29, 2020 |
| Acer          | Aspire A315-54              | [c50041e542](https://linux-hardware.org/?probe=c50041e542) | Nov 28, 2020 |
| System76      | Galago Pro                  | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | Inspiron 5575               | [269f2e1ac1](https://linux-hardware.org/?probe=269f2e1ac1) | Nov 27, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63976540](https://linux-hardware.org/?probe=7d63976540) | Nov 27, 2020 |
| ASUSTek       | GL553VD                     | [46d4c1f45d](https://linux-hardware.org/?probe=46d4c1f45d) | Nov 26, 2020 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [05988a9297](https://linux-hardware.org/?probe=05988a9297) | Nov 26, 2020 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [4516048552](https://linux-hardware.org/?probe=4516048552) | Nov 26, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3c69cde3bb](https://linux-hardware.org/?probe=3c69cde3bb) | Nov 24, 2020 |
| BANGHO        | MOV                         | [466365322d](https://linux-hardware.org/?probe=466365322d) | Nov 20, 2020 |
| HP            | Pavilion x2 Detachable      | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Sony          | SVF14N11CXB                 | [9f41b6e7c9](https://linux-hardware.org/?probe=9f41b6e7c9) | Nov 19, 2020 |
| HP            | Laptop 15-bs0xx             | [1119089279](https://linux-hardware.org/?probe=1119089279) | Nov 19, 2020 |
| Intel         | H81U                        | [1ce903f88c](https://linux-hardware.org/?probe=1ce903f88c) | Nov 18, 2020 |
| Intel         | H81U                        | [b36636a1c9](https://linux-hardware.org/?probe=b36636a1c9) | Nov 18, 2020 |
| HP            | EliteBook 840 G6            | [790941d1cf](https://linux-hardware.org/?probe=790941d1cf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Apple         | MacBookPro9,2               | [b2fdafbfe7](https://linux-hardware.org/?probe=b2fdafbfe7) | Nov 15, 2020 |
| Dell          | Latitude 3410               | [f5b5e90105](https://linux-hardware.org/?probe=f5b5e90105) | Nov 14, 2020 |
| Dell          | Latitude 3410               | [a3c8f5e5e7](https://linux-hardware.org/?probe=a3c8f5e5e7) | Nov 14, 2020 |
| Dell          | Inspiron 1545               | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83134c6b81](https://linux-hardware.org/?probe=83134c6b81) | Nov 09, 2020 |
| ASUSTek       | X455LJ                      | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [d7328f9c49](https://linux-hardware.org/?probe=d7328f9c49) | Nov 09, 2020 |
| Acer          | Aspire E5-575G              | [a80c58afbd](https://linux-hardware.org/?probe=a80c58afbd) | Nov 08, 2020 |
| HP            | 650                         | [b1b8a15b0c](https://linux-hardware.org/?probe=b1b8a15b0c) | Nov 08, 2020 |
| ASUSTek       | X455LJ                      | [992a71f58b](https://linux-hardware.org/?probe=992a71f58b) | Nov 07, 2020 |
| HP            | Pavilion 17                 | [71e4c06fe1](https://linux-hardware.org/?probe=71e4c06fe1) | Nov 07, 2020 |
| Lenovo        | ThinkPad T470 20HES07C14    | [2892878624](https://linux-hardware.org/?probe=2892878624) | Nov 06, 2020 |
| HP            | Notebook                    | [f62f2870d6](https://linux-hardware.org/?probe=f62f2870d6) | Nov 05, 2020 |
| HP            | Pavilion 17                 | [4749f187d8](https://linux-hardware.org/?probe=4749f187d8) | Nov 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [84d7d9f750](https://linux-hardware.org/?probe=84d7d9f750) | Nov 05, 2020 |
| Sony          | SVS15125PLB                 | [04e1f4654a](https://linux-hardware.org/?probe=04e1f4654a) | Nov 05, 2020 |
| BANGHO        | MAX G0101                   | [59451b99e9](https://linux-hardware.org/?probe=59451b99e9) | Nov 05, 2020 |
| BANGHO        | MAX G0101                   | [0a30aa6677](https://linux-hardware.org/?probe=0a30aa6677) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | ENVY Notebook               | [19e6729b93](https://linux-hardware.org/?probe=19e6729b93) | Nov 04, 2020 |
| Apple         | MacBookPro8,1               | [c41ddc2f73](https://linux-hardware.org/?probe=c41ddc2f73) | Nov 03, 2020 |
| Apple         | MacBookPro8,1               | [321bdb49c4](https://linux-hardware.org/?probe=321bdb49c4) | Nov 02, 2020 |
| Apple         | MacBookPro9,2               | [7ac11599ba](https://linux-hardware.org/?probe=7ac11599ba) | Nov 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [c45660f01d](https://linux-hardware.org/?probe=c45660f01d) | Oct 31, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6ddb0983ac](https://linux-hardware.org/?probe=6ddb0983ac) | Oct 31, 2020 |
| Lenovo        | B50-10 80QR                 | [bd5fbf5911](https://linux-hardware.org/?probe=bd5fbf5911) | Oct 31, 2020 |
| Lenovo        | B50-10 80QR                 | [d40e3d6a1d](https://linux-hardware.org/?probe=d40e3d6a1d) | Oct 31, 2020 |
| ASUSTek       | GL553VD                     | [1ce30fc6e2](https://linux-hardware.org/?probe=1ce30fc6e2) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | [b447f4c345](https://linux-hardware.org/?probe=b447f4c345) | Oct 30, 2020 |
| Lenovo        | V330-15ISK 81AW             | [a309a84d85](https://linux-hardware.org/?probe=a309a84d85) | Oct 30, 2020 |
| Dell          | Inspiron 5770               | [6898d75d28](https://linux-hardware.org/?probe=6898d75d28) | Oct 30, 2020 |
| Dell          | Inspiron 5567               | [37ec3d6eb4](https://linux-hardware.org/?probe=37ec3d6eb4) | Oct 27, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [cb74da5aa1](https://linux-hardware.org/?probe=cb74da5aa1) | Oct 26, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [289e1e78b3](https://linux-hardware.org/?probe=289e1e78b3) | Oct 26, 2020 |
| Toshiba       | Satellite.L845              | [735ee23f18](https://linux-hardware.org/?probe=735ee23f18) | Oct 24, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [3fa26de528](https://linux-hardware.org/?probe=3fa26de528) | Oct 24, 2020 |
| Toshiba       | Satellite.L845              | [8d9c29acf6](https://linux-hardware.org/?probe=8d9c29acf6) | Oct 24, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [877e27f004](https://linux-hardware.org/?probe=877e27f004) | Oct 24, 2020 |
| BANGHO        | MOV                         | [00a6b02371](https://linux-hardware.org/?probe=00a6b02371) | Oct 23, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b753b95909](https://linux-hardware.org/?probe=b753b95909) | Oct 23, 2020 |
| Toshiba       | Satellite P100              | [60e53b8e68](https://linux-hardware.org/?probe=60e53b8e68) | Oct 22, 2020 |
| BANGHO        | W240HU/W250HUQ              | [ee93aac7ac](https://linux-hardware.org/?probe=ee93aac7ac) | Oct 21, 2020 |
| BANGHO        | W240HU/W250HUQ              | [7e3e5a7eb4](https://linux-hardware.org/?probe=7e3e5a7eb4) | Oct 21, 2020 |
| Dell          | Latitude E6410              | [6b72fe3bc1](https://linux-hardware.org/?probe=6b72fe3bc1) | Oct 21, 2020 |
| Dell          | Latitude E6410              | [1344691841](https://linux-hardware.org/?probe=1344691841) | Oct 21, 2020 |
| HP            | ProBook 440 G6              | [7ea4a003d0](https://linux-hardware.org/?probe=7ea4a003d0) | Oct 21, 2020 |
| HP            | ProBook 440 G6              | [a12e6640f7](https://linux-hardware.org/?probe=a12e6640f7) | Oct 21, 2020 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [dfe846c6a5](https://linux-hardware.org/?probe=dfe846c6a5) | Oct 21, 2020 |
| Dell          | Inspiron 3459               | [95ddf449e4](https://linux-hardware.org/?probe=95ddf449e4) | Oct 21, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [af184296d5](https://linux-hardware.org/?probe=af184296d5) | Oct 19, 2020 |
| Dell          | Inspiron 3493               | [3e4c80a383](https://linux-hardware.org/?probe=3e4c80a383) | Oct 18, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [b91f16a7ad](https://linux-hardware.org/?probe=b91f16a7ad) | Oct 13, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [825ec694fe](https://linux-hardware.org/?probe=825ec694fe) | Oct 13, 2020 |
| ASUSTek       | X510UQ                      | [f1b1ce2864](https://linux-hardware.org/?probe=f1b1ce2864) | Oct 12, 2020 |
| PEAQ          | PNB series                  | [93deb5d8fd](https://linux-hardware.org/?probe=93deb5d8fd) | Oct 11, 2020 |
| BANGHO        | MOV                         | [f57c9ece74](https://linux-hardware.org/?probe=f57c9ece74) | Oct 11, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [f9d1e0f571](https://linux-hardware.org/?probe=f9d1e0f571) | Oct 11, 2020 |
| Apple         | MacBookAir7,1               | [fc081194c7](https://linux-hardware.org/?probe=fc081194c7) | Oct 09, 2020 |
| Apple         | MacBookPro9,2               | [dcf000f443](https://linux-hardware.org/?probe=dcf000f443) | Oct 08, 2020 |
| Apple         | MacBookPro9,2               | [4ab1bbf92b](https://linux-hardware.org/?probe=4ab1bbf92b) | Oct 08, 2020 |
| Lenovo        | V330-14ARR 81B1             | [62310522c0](https://linux-hardware.org/?probe=62310522c0) | Oct 07, 2020 |
| BANGHO        | MOV                         | [7d46d0bdaf](https://linux-hardware.org/?probe=7d46d0bdaf) | Oct 07, 2020 |
| BANGHO        | MAX G5 i1                   | [886582976a](https://linux-hardware.org/?probe=886582976a) | Oct 06, 2020 |
| BANGHO        | MAX G5 i1                   | [86fb9e836c](https://linux-hardware.org/?probe=86fb9e836c) | Oct 06, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ba00de031e](https://linux-hardware.org/?probe=ba00de031e) | Oct 05, 2020 |
| BANGHO        | MOV                         | [ac64037d70](https://linux-hardware.org/?probe=ac64037d70) | Oct 05, 2020 |
| BANGHO        | MOV                         | [33d4f04681](https://linux-hardware.org/?probe=33d4f04681) | Oct 05, 2020 |
| Acer          | AOD260                      | [df3f6056c4](https://linux-hardware.org/?probe=df3f6056c4) | Oct 05, 2020 |
| HP            | Laptop 15-bs0xx             | [a322f76191](https://linux-hardware.org/?probe=a322f76191) | Oct 02, 2020 |
| HP            | Pavilion dv7                | [98225b6277](https://linux-hardware.org/?probe=98225b6277) | Oct 02, 2020 |
| Dell          | Latitude E7470              | [8482305505](https://linux-hardware.org/?probe=8482305505) | Sep 29, 2020 |
| LG Electro... | 14Z90N-V.AA78B              | [e8a9c24350](https://linux-hardware.org/?probe=e8a9c24350) | Sep 29, 2020 |
| Dell          | Latitude 7400               | [80087e258d](https://linux-hardware.org/?probe=80087e258d) | Sep 29, 2020 |
| Dell          | Inspiron 15-7579            | [7ec4fff3d3](https://linux-hardware.org/?probe=7ec4fff3d3) | Sep 29, 2020 |
| Acer          | Aspire A715-71G             | [36df837973](https://linux-hardware.org/?probe=36df837973) | Sep 29, 2020 |
| Lenovo        | ThinkPad T430 23492D1       | [8129a72ff2](https://linux-hardware.org/?probe=8129a72ff2) | Sep 29, 2020 |
| Dell          | Inspiron 1525               | [618220e59f](https://linux-hardware.org/?probe=618220e59f) | Sep 28, 2020 |
| ASUSTek       | X555LA                      | [f8e9b10222](https://linux-hardware.org/?probe=f8e9b10222) | Sep 28, 2020 |
| Acer          | Aspire A715-71G             | [110b8c7001](https://linux-hardware.org/?probe=110b8c7001) | Sep 28, 2020 |
| BANGHO        | MAX G5                      | [2eddb3aae7](https://linux-hardware.org/?probe=2eddb3aae7) | Sep 23, 2020 |
| LG Electro... | 14Z90N-V.AA78B              | [dbd61d5061](https://linux-hardware.org/?probe=dbd61d5061) | Sep 21, 2020 |
| HP            | Pavilion dv6                | [049f1ad3ee](https://linux-hardware.org/?probe=049f1ad3ee) | Sep 21, 2020 |
| Dell          | Latitude 3340               | [07019fc3f6](https://linux-hardware.org/?probe=07019fc3f6) | Sep 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7e1e02aabc](https://linux-hardware.org/?probe=7e1e02aabc) | Sep 19, 2020 |
| HP            | Laptop 14-dq1xxx            | [ce99ff79c5](https://linux-hardware.org/?probe=ce99ff79c5) | Sep 18, 2020 |
| Lenovo        | G470 20078                  | [2a2e9cbf77](https://linux-hardware.org/?probe=2a2e9cbf77) | Sep 17, 2020 |
| Lenovo        | ThinkPad T430 2349SP5       | [8851e71134](https://linux-hardware.org/?probe=8851e71134) | Sep 16, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Dell          | Inspiron 7352               | [64e9531caa](https://linux-hardware.org/?probe=64e9531caa) | Sep 14, 2020 |
| Clevo         | M540SR                      | [00ebcac258](https://linux-hardware.org/?probe=00ebcac258) | Sep 10, 2020 |
| Clevo         | M540SR                      | [de2ce81eef](https://linux-hardware.org/?probe=de2ce81eef) | Sep 10, 2020 |
| ASUSTek       | X541NA                      | [f353530b1f](https://linux-hardware.org/?probe=f353530b1f) | Sep 09, 2020 |
| Dell          | Inspiron 5423               | [d8dc0213bf](https://linux-hardware.org/?probe=d8dc0213bf) | Sep 09, 2020 |
| HP            | Pavilion 11 x360 PC         | [3a3608a6e7](https://linux-hardware.org/?probe=3a3608a6e7) | Sep 08, 2020 |
| Lenovo        | G470 20078                  | [b8114428e2](https://linux-hardware.org/?probe=b8114428e2) | Sep 08, 2020 |
| BANGHO        | MAX G5                      | [698ed67733](https://linux-hardware.org/?probe=698ed67733) | Sep 08, 2020 |
| Lenovo        | G470 20078                  | [519a7da2bb](https://linux-hardware.org/?probe=519a7da2bb) | Sep 08, 2020 |
| Toshiba       | Satellite Pro C650          | [61966b1615](https://linux-hardware.org/?probe=61966b1615) | Sep 07, 2020 |
| ASUSTek       | X541UAK                     | [5324459574](https://linux-hardware.org/?probe=5324459574) | Sep 06, 2020 |
| BANGHO        | MAX G0101                   | [636674d438](https://linux-hardware.org/?probe=636674d438) | Sep 06, 2020 |
| Samsung       | R430/P430                   | [700a16cd90](https://linux-hardware.org/?probe=700a16cd90) | Sep 06, 2020 |
| Samsung       | R430/P430                   | [2bf6a98bc9](https://linux-hardware.org/?probe=2bf6a98bc9) | Sep 06, 2020 |
| Toshiba       | Satellite P55t-A            | [00b5e3e6dc](https://linux-hardware.org/?probe=00b5e3e6dc) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | [043d555fa5](https://linux-hardware.org/?probe=043d555fa5) | Sep 05, 2020 |
| CEVEN         | GFAST                       | [4b465becc6](https://linux-hardware.org/?probe=4b465becc6) | Sep 04, 2020 |
| Lenovo        | V330-15IKB 81AX             | [bdc65f00fe](https://linux-hardware.org/?probe=bdc65f00fe) | Sep 02, 2020 |
| HP            | Mini 110-3000               | [455ed6a1b9](https://linux-hardware.org/?probe=455ed6a1b9) | Sep 01, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [50e3a11fd5](https://linux-hardware.org/?probe=50e3a11fd5) | Aug 31, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [af42b37cfa](https://linux-hardware.org/?probe=af42b37cfa) | Aug 29, 2020 |
| HP            | 250 G5 Notebook PC          | [ee01f69731](https://linux-hardware.org/?probe=ee01f69731) | Aug 29, 2020 |
| HP            | Compaq Presario C700        | [05348acb06](https://linux-hardware.org/?probe=05348acb06) | Aug 28, 2020 |
| HP            | Laptop 17-bs0xx             | [8eb9cd8888](https://linux-hardware.org/?probe=8eb9cd8888) | Aug 27, 2020 |
| Advantec      | CX23200W                    | [b63469e77b](https://linux-hardware.org/?probe=b63469e77b) | Aug 27, 2020 |
| BANGHO        | MOV                         | [1d0422ca92](https://linux-hardware.org/?probe=1d0422ca92) | Aug 26, 2020 |
| BANGHO        | MOV                         | [f1890b9096](https://linux-hardware.org/?probe=f1890b9096) | Aug 26, 2020 |
| HP            | 15 Notebook PC              | [f1588185ac](https://linux-hardware.org/?probe=f1588185ac) | Aug 26, 2020 |
| Sony          | VGN-FE880E                  | [246d89f828](https://linux-hardware.org/?probe=246d89f828) | Aug 26, 2020 |
| ASUSTek       | X541SA                      | [8ff1a33470](https://linux-hardware.org/?probe=8ff1a33470) | Aug 22, 2020 |
| ASUSTek       | X541NA                      | [25c9061efe](https://linux-hardware.org/?probe=25c9061efe) | Aug 21, 2020 |
| Acer          | Aspire ES1-572              | [859a6dbda0](https://linux-hardware.org/?probe=859a6dbda0) | Aug 20, 2020 |
| Sony          | VGN-FE880E                  | [5785026d11](https://linux-hardware.org/?probe=5785026d11) | Aug 20, 2020 |
| Lenovo        | ThinkPad L430 24654A1       | [1f3055baa5](https://linux-hardware.org/?probe=1f3055baa5) | Aug 19, 2020 |
| Acer          | Aspire 4560                 | [1a272e0f1b](https://linux-hardware.org/?probe=1a272e0f1b) | Aug 19, 2020 |
| Acer          | Aspire 4560                 | [f4171207f6](https://linux-hardware.org/?probe=f4171207f6) | Aug 19, 2020 |
| CEVEN         | GFAST                       | [d7feb269d0](https://linux-hardware.org/?probe=d7feb269d0) | Aug 18, 2020 |
| Positivo      | C500                        | [71530651bb](https://linux-hardware.org/?probe=71530651bb) | Aug 18, 2020 |
| CEVEN         | GFAST                       | [bd67618634](https://linux-hardware.org/?probe=bd67618634) | Aug 17, 2020 |
| CEVEN         | GFAST                       | [7a24a74da7](https://linux-hardware.org/?probe=7a24a74da7) | Aug 15, 2020 |
| CEVEN         | GFAST                       | [703bfe50ff](https://linux-hardware.org/?probe=703bfe50ff) | Aug 14, 2020 |
| ASUSTek       | X541SA                      | [2d6beed0c6](https://linux-hardware.org/?probe=2d6beed0c6) | Aug 13, 2020 |
| Lenovo        | G480 20150                  | [4531dd50a5](https://linux-hardware.org/?probe=4531dd50a5) | Aug 11, 2020 |
| Lenovo        | G480 20150                  | [8e51b2cb2d](https://linux-hardware.org/?probe=8e51b2cb2d) | Aug 11, 2020 |
| Lenovo        | ThinkPad E420 1141A25       | [ebc542a80b](https://linux-hardware.org/?probe=ebc542a80b) | Aug 11, 2020 |
| Lenovo        | ThinkPad E420 1141A25       | [b00e33454f](https://linux-hardware.org/?probe=b00e33454f) | Aug 10, 2020 |
| Acer          | Aspire A315-53              | [bd6cda0140](https://linux-hardware.org/?probe=bd6cda0140) | Aug 09, 2020 |
| BANGHO        | MAX G5                      | [f38efc30b3](https://linux-hardware.org/?probe=f38efc30b3) | Aug 07, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Acer          | Aspire A315-53              | [c8b94ab639](https://linux-hardware.org/?probe=c8b94ab639) | Aug 05, 2020 |
| Acer          | Aspire A515-54G             | [ae74e61be9](https://linux-hardware.org/?probe=ae74e61be9) | Aug 04, 2020 |
| Lenovo        | QIWG5                       | [a9c15a2880](https://linux-hardware.org/?probe=a9c15a2880) | Aug 04, 2020 |
| Lenovo        | V330-14ARR 81B1             | [e89440dd5a](https://linux-hardware.org/?probe=e89440dd5a) | Aug 01, 2020 |
| Lenovo        | ThinkPad Helix 36986DG      | [393a444d6d](https://linux-hardware.org/?probe=393a444d6d) | Jul 31, 2020 |
| HP            | OMEN by Laptop 15-ce0xx     | [a16817e30b](https://linux-hardware.org/?probe=a16817e30b) | Jul 31, 2020 |
| HP            | OMEN by Laptop 15-ce0xx     | [5e32bd533e](https://linux-hardware.org/?probe=5e32bd533e) | Jul 29, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [e890487f0f](https://linux-hardware.org/?probe=e890487f0f) | Jul 28, 2020 |
| BANGHO        | H34                         | [81bf7f9011](https://linux-hardware.org/?probe=81bf7f9011) | Jul 25, 2020 |
| ASUSTek       | X541UA                      | [819a4ae9aa](https://linux-hardware.org/?probe=819a4ae9aa) | Jul 25, 2020 |
| HP            | Pavilion dv7                | [148de9bc85](https://linux-hardware.org/?probe=148de9bc85) | Jul 24, 2020 |
| Dell          | Inspiron 3421               | [f2dbd4b97a](https://linux-hardware.org/?probe=f2dbd4b97a) | Jul 23, 2020 |
| Compal        | QAL50                       | [d3f3124196](https://linux-hardware.org/?probe=d3f3124196) | Jul 21, 2020 |
| ASUSTek       | UX530UX                     | [2a05da203c](https://linux-hardware.org/?probe=2a05da203c) | Jul 21, 2020 |
| ASUSTek       | UX530UX                     | [62332faf6a](https://linux-hardware.org/?probe=62332faf6a) | Jul 21, 2020 |
| Lenovo        | ThinkPad Edge 13 01962BY    | [adc3fbd841](https://linux-hardware.org/?probe=adc3fbd841) | Jul 21, 2020 |
| Lenovo        | ThinkPad Edge 13 01962BY    | [bee144dbad](https://linux-hardware.org/?probe=bee144dbad) | Jul 21, 2020 |
| Lenovo        | ThinkPad Edge 13 01962BY    | [101d94a8b1](https://linux-hardware.org/?probe=101d94a8b1) | Jul 21, 2020 |
| Dell          | XPS M1330                   | [196c29d4f6](https://linux-hardware.org/?probe=196c29d4f6) | Jul 20, 2020 |
| ASUSTek       | N61Jq                       | [9376b50561](https://linux-hardware.org/?probe=9376b50561) | Jul 19, 2020 |
| ASUSTek       | N61Jq                       | [92ac14c653](https://linux-hardware.org/?probe=92ac14c653) | Jul 19, 2020 |
| Dell          | Inspiron 5423               | [13dad3f5c6](https://linux-hardware.org/?probe=13dad3f5c6) | Jul 18, 2020 |
| Toshiba       | Satellite A665              | [de004aea9e](https://linux-hardware.org/?probe=de004aea9e) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c975f7ce3e](https://linux-hardware.org/?probe=c975f7ce3e) | Jul 17, 2020 |
| Lenovo        | G580 20150                  | [93c3eac8c9](https://linux-hardware.org/?probe=93c3eac8c9) | Jul 16, 2020 |
| Intel         | Crestline & ICH8M Chipse... | [acc1fde47a](https://linux-hardware.org/?probe=acc1fde47a) | Jul 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dafe61ecd8](https://linux-hardware.org/?probe=dafe61ecd8) | Jul 13, 2020 |
| Lenovo        | QIWG5                       | [cc2853be76](https://linux-hardware.org/?probe=cc2853be76) | Jul 13, 2020 |
| Acer          | Aspire E5-772               | [e653bf36fb](https://linux-hardware.org/?probe=e653bf36fb) | Jul 12, 2020 |
| Dell          | Studio 1537                 | [f31c6c9d6d](https://linux-hardware.org/?probe=f31c6c9d6d) | Jul 12, 2020 |
| Lenovo        | V330-15IKB 81AX             | [89e5c0cca0](https://linux-hardware.org/?probe=89e5c0cca0) | Jul 12, 2020 |
| Lenovo        | BP PV CLASSMATE+            | [0e381612fb](https://linux-hardware.org/?probe=0e381612fb) | Jul 11, 2020 |
| Positivo      | H14BT58                     | [28675e913c](https://linux-hardware.org/?probe=28675e913c) | Jul 11, 2020 |
| HP            | Laptop 14-bp0xx             | [6eb93f1293](https://linux-hardware.org/?probe=6eb93f1293) | Jul 10, 2020 |
| ASUSTek       | N61Jq                       | [60c0d6aa00](https://linux-hardware.org/?probe=60c0d6aa00) | Jul 10, 2020 |
| Lenovo        | QIWG5                       | [15d734feb7](https://linux-hardware.org/?probe=15d734feb7) | Jul 09, 2020 |
| HP            | Pavilion Notebook           | [fdd8fdf7b1](https://linux-hardware.org/?probe=fdd8fdf7b1) | Jul 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a4e10489a6](https://linux-hardware.org/?probe=a4e10489a6) | Jul 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f5e8a43171](https://linux-hardware.org/?probe=f5e8a43171) | Jul 08, 2020 |
| ASUSTek       | N61Jq                       | [07228a2170](https://linux-hardware.org/?probe=07228a2170) | Jul 07, 2020 |
| BANGHO        | H34                         | [1795304033](https://linux-hardware.org/?probe=1795304033) | Jul 07, 2020 |
| ECS           | G410                        | [38bad5d8cb](https://linux-hardware.org/?probe=38bad5d8cb) | Jul 05, 2020 |
| HP            | 250 G6 Notebook PC          | [bc9d23a74c](https://linux-hardware.org/?probe=bc9d23a74c) | Jul 02, 2020 |
| HP            | 250 G6 Notebook PC          | [b1757b232f](https://linux-hardware.org/?probe=b1757b232f) | Jul 02, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71bc483322](https://linux-hardware.org/?probe=71bc483322) | Jun 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [16807543db](https://linux-hardware.org/?probe=16807543db) | Jun 29, 2020 |
| Intel         | HURONRIVER                  | [e748e1f03d](https://linux-hardware.org/?probe=e748e1f03d) | Jun 28, 2020 |
| Intel         | HURONRIVER                  | [319de108aa](https://linux-hardware.org/?probe=319de108aa) | Jun 28, 2020 |
| Dell          | Inspiron 1720               | [54da7f6e61](https://linux-hardware.org/?probe=54da7f6e61) | Jun 28, 2020 |
| Dell          | Inspiron N4010              | [e6887adc1c](https://linux-hardware.org/?probe=e6887adc1c) | Jun 27, 2020 |
| Lenovo        | VIUS3                       | [eef5e0b25e](https://linux-hardware.org/?probe=eef5e0b25e) | Jun 26, 2020 |
| Toshiba       | Satellite A665              | [07bd67039c](https://linux-hardware.org/?probe=07bd67039c) | Jun 25, 2020 |
| BANGHO        | SUMA                        | [ad6079072f](https://linux-hardware.org/?probe=ad6079072f) | Jun 25, 2020 |
| Lenovo        | G50-45 80E3                 | [6d9836bb74](https://linux-hardware.org/?probe=6d9836bb74) | Jun 24, 2020 |
| HP            | Pavilion dv7                | [7c9a0b5de6](https://linux-hardware.org/?probe=7c9a0b5de6) | Jun 24, 2020 |
| Toshiba       | Satellite A665              | [dbdc234d15](https://linux-hardware.org/?probe=dbdc234d15) | Jun 21, 2020 |
| HP            | Laptop 15-bs0xx             | [c26bbc4ee6](https://linux-hardware.org/?probe=c26bbc4ee6) | Jun 21, 2020 |
| MSI           | MS-N0E1 Ver                 | [ee8124530e](https://linux-hardware.org/?probe=ee8124530e) | Jun 18, 2020 |
| HP            | 245 G6                      | [e3ec1c79c7](https://linux-hardware.org/?probe=e3ec1c79c7) | Jun 17, 2020 |
| ASUSTek       | N56VB                       | [8175e92d80](https://linux-hardware.org/?probe=8175e92d80) | Jun 16, 2020 |
| BANGHO        | SUMA                        | [79985cbe20](https://linux-hardware.org/?probe=79985cbe20) | Jun 15, 2020 |
| HP            | 245 G6                      | [e51a9fc0e0](https://linux-hardware.org/?probe=e51a9fc0e0) | Jun 14, 2020 |
| Standard      | BW Series                   | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| Acer          | Aspire 4741                 | [dc3159a77a](https://linux-hardware.org/?probe=dc3159a77a) | Jun 12, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e61ac60eb7](https://linux-hardware.org/?probe=e61ac60eb7) | Jun 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2f9e1d63ca](https://linux-hardware.org/?probe=2f9e1d63ca) | Jun 10, 2020 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [51f3caaace](https://linux-hardware.org/?probe=51f3caaace) | Jun 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [11a9544569](https://linux-hardware.org/?probe=11a9544569) | Jun 09, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [c0ebbbd818](https://linux-hardware.org/?probe=c0ebbbd818) | Jun 08, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [90f8dc3206](https://linux-hardware.org/?probe=90f8dc3206) | Jun 08, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad Y460                | [232c09b56d](https://linux-hardware.org/?probe=232c09b56d) | Jun 01, 2020 |
| Dell          | Inspiron N5050              | [c1b643a296](https://linux-hardware.org/?probe=c1b643a296) | May 31, 2020 |
| Lenovo        | ThinkPad T430 2349DS5       | [77d17289e7](https://linux-hardware.org/?probe=77d17289e7) | May 31, 2020 |
| HDC High D... | CB14T332                    | [1d7a164cca](https://linux-hardware.org/?probe=1d7a164cca) | May 30, 2020 |
| HP            | Pavilion dv4                | [acc4edabeb](https://linux-hardware.org/?probe=acc4edabeb) | May 29, 2020 |
| HP            | Pavilion dv4                | [9efd9117d9](https://linux-hardware.org/?probe=9efd9117d9) | May 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [85a6296e82](https://linux-hardware.org/?probe=85a6296e82) | May 27, 2020 |
| Dell          | Inspiron 1440               | [51cbf53227](https://linux-hardware.org/?probe=51cbf53227) | May 26, 2020 |
| Toshiba       | Satellite S55-B             | [35990b670d](https://linux-hardware.org/?probe=35990b670d) | May 25, 2020 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [609fce4ba1](https://linux-hardware.org/?probe=609fce4ba1) | May 23, 2020 |
| Acer          | Aspire one                  | [610bb91d45](https://linux-hardware.org/?probe=610bb91d45) | May 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7d85f0707](https://linux-hardware.org/?probe=e7d85f0707) | May 23, 2020 |
| Dell          | Inspiron 3458               | [47147cf457](https://linux-hardware.org/?probe=47147cf457) | May 22, 2020 |
| Toshiba       | Satellite_C50-A             | [c009a1b23e](https://linux-hardware.org/?probe=c009a1b23e) | May 21, 2020 |
| Toshiba       | Satellite_C50-A             | [7194a8f44f](https://linux-hardware.org/?probe=7194a8f44f) | May 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eeb0ec95b4](https://linux-hardware.org/?probe=eeb0ec95b4) | May 21, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Inspiron 3583               | [f664e8baa0](https://linux-hardware.org/?probe=f664e8baa0) | May 19, 2020 |
| HP            | Notebook                    | [035439ee14](https://linux-hardware.org/?probe=035439ee14) | May 18, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5ae642ebcc](https://linux-hardware.org/?probe=5ae642ebcc) | May 18, 2020 |
| Advantec      | CX23200W                    | [3c46531687](https://linux-hardware.org/?probe=3c46531687) | May 18, 2020 |
| ASUSTek       | X201E                       | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| HP            | 250 G6 Notebook PC          | [2e8b8d3bf5](https://linux-hardware.org/?probe=2e8b8d3bf5) | May 17, 2020 |
| ASUSTek       | X541SA                      | [a5abf5029c](https://linux-hardware.org/?probe=a5abf5029c) | May 16, 2020 |
| HP            | Notebook                    | [17b0d4b1b2](https://linux-hardware.org/?probe=17b0d4b1b2) | May 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fdde6fdb59](https://linux-hardware.org/?probe=fdde6fdb59) | May 16, 2020 |
| NOBLEX        | SF20BA                      | [0169804f91](https://linux-hardware.org/?probe=0169804f91) | May 16, 2020 |
| ASUSTek       | X541SA                      | [ba79d13056](https://linux-hardware.org/?probe=ba79d13056) | May 15, 2020 |
| MSI           | Prestige 15 A10SC           | [b46fb9ee96](https://linux-hardware.org/?probe=b46fb9ee96) | May 15, 2020 |
| Dell          | Inspiron 5558               | [ad0097b9e5](https://linux-hardware.org/?probe=ad0097b9e5) | May 14, 2020 |
| BANGHO        | MOV                         | [b952e965fb](https://linux-hardware.org/?probe=b952e965fb) | May 14, 2020 |
| HP            | Pavilion dv6                | [a6e3c25211](https://linux-hardware.org/?probe=a6e3c25211) | May 14, 2020 |
| MSI           | GT72 2QD                    | [3e5535aff1](https://linux-hardware.org/?probe=3e5535aff1) | May 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [36026e8ba9](https://linux-hardware.org/?probe=36026e8ba9) | May 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e34df8aa1b](https://linux-hardware.org/?probe=e34df8aa1b) | May 13, 2020 |
| ASUSTek       | 1005HA                      | [208b634e5e](https://linux-hardware.org/?probe=208b634e5e) | May 12, 2020 |
| ASUSTek       | 1005HA                      | [0157e9e58a](https://linux-hardware.org/?probe=0157e9e58a) | May 11, 2020 |
| Dell          | Inspiron MP061              | [0d62b4970c](https://linux-hardware.org/?probe=0d62b4970c) | May 10, 2020 |
| Dell          | Inspiron 7375               | [9b4bfa1e62](https://linux-hardware.org/?probe=9b4bfa1e62) | May 10, 2020 |
| Acer          | Aspire A315-51              | [226717c68e](https://linux-hardware.org/?probe=226717c68e) | May 09, 2020 |
| Dell          | Inspiron 5559               | [bdeeaa6623](https://linux-hardware.org/?probe=bdeeaa6623) | May 09, 2020 |
| Acer          | Aspire A315-51              | [9f734e2f81](https://linux-hardware.org/?probe=9f734e2f81) | May 08, 2020 |
| Exo           | CloudbookE15                | [b9b02e2bec](https://linux-hardware.org/?probe=b9b02e2bec) | May 06, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [450ec80c78](https://linux-hardware.org/?probe=450ec80c78) | May 06, 2020 |
| Lenovo        | V330-15IKB 81AX             | [0612c46691](https://linux-hardware.org/?probe=0612c46691) | May 05, 2020 |
| Exo           | CloudbookE15                | [651f6e4a76](https://linux-hardware.org/?probe=651f6e4a76) | May 05, 2020 |
| Exo           | CloudbookE15                | [101bb597a7](https://linux-hardware.org/?probe=101bb597a7) | May 05, 2020 |
| Samsung       | R430/R480/R440              | [9543c80004](https://linux-hardware.org/?probe=9543c80004) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| ASUSTek       | X55A                        | [4b731fa568](https://linux-hardware.org/?probe=4b731fa568) | May 04, 2020 |
| Exo           | Smart E21                   | [21e1611f08](https://linux-hardware.org/?probe=21e1611f08) | May 03, 2020 |
| Lenovo        | V330-15IKB 81AX             | [80a7558d05](https://linux-hardware.org/?probe=80a7558d05) | May 02, 2020 |
| HP            | Compaq Presario C700        | [efeb3f4f36](https://linux-hardware.org/?probe=efeb3f4f36) | May 02, 2020 |
| Dell          | Inspiron 7375               | [8ee3d49f46](https://linux-hardware.org/?probe=8ee3d49f46) | May 02, 2020 |
| Acer          | Aspire E5-575               | [d3ad9967d5](https://linux-hardware.org/?probe=d3ad9967d5) | May 02, 2020 |
| ASUSTek       | UX430UA                     | [a092e370bd](https://linux-hardware.org/?probe=a092e370bd) | May 01, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [17855fa480](https://linux-hardware.org/?probe=17855fa480) | May 01, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [7ef5c45df9](https://linux-hardware.org/?probe=7ef5c45df9) | May 01, 2020 |
| Radio Vict... | A4                          | [5b6ac9e159](https://linux-hardware.org/?probe=5b6ac9e159) | Apr 30, 2020 |
| Acer          | Aspire A315-53              | [e1589876b4](https://linux-hardware.org/?probe=e1589876b4) | Apr 29, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [090e9b3487](https://linux-hardware.org/?probe=090e9b3487) | Apr 29, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Acer          | Aspire 4750                 | [0f2642016b](https://linux-hardware.org/?probe=0f2642016b) | Apr 27, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [0d3ef443aa](https://linux-hardware.org/?probe=0d3ef443aa) | Apr 27, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| Sony          | VPCSA3AFX                   | [61533f80b7](https://linux-hardware.org/?probe=61533f80b7) | Apr 27, 2020 |
| Toshiba       | PORTEGE Z930                | [ab20d5dde2](https://linux-hardware.org/?probe=ab20d5dde2) | Apr 27, 2020 |
| Acer          | Aspire 4750                 | [3af3d71653](https://linux-hardware.org/?probe=3af3d71653) | Apr 27, 2020 |
| Lenovo        | V130-15IGM 81HL             | [642b4cc187](https://linux-hardware.org/?probe=642b4cc187) | Apr 26, 2020 |
| Dell          | Inspiron 5559               | [9a741e6500](https://linux-hardware.org/?probe=9a741e6500) | Apr 26, 2020 |
| Dell          | Inspiron 3421               | [c740071cd2](https://linux-hardware.org/?probe=c740071cd2) | Apr 26, 2020 |
| HUAWEI        | KPL-W0X                     | [5400b2482d](https://linux-hardware.org/?probe=5400b2482d) | Apr 26, 2020 |
| HP            | 250 G6 Notebook PC          | [ab3f99280e](https://linux-hardware.org/?probe=ab3f99280e) | Apr 25, 2020 |
| Compal        | ZAW70                       | [3bcf558940](https://linux-hardware.org/?probe=3bcf558940) | Apr 24, 2020 |
| Dell          | Inspiron 3421               | [c034a695fc](https://linux-hardware.org/?probe=c034a695fc) | Apr 21, 2020 |
| Sony          | VGN-FJ270                   | [88715b924d](https://linux-hardware.org/?probe=88715b924d) | Apr 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e9c4719040](https://linux-hardware.org/?probe=e9c4719040) | Apr 20, 2020 |
| Apple         | MacBookPro9,2               | [f5ba9964b4](https://linux-hardware.org/?probe=f5ba9964b4) | Apr 20, 2020 |
| Clevo         | M7x0S                       | [2dc8a215f6](https://linux-hardware.org/?probe=2dc8a215f6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | [562739a94b](https://linux-hardware.org/?probe=562739a94b) | Apr 17, 2020 |
| Dell          | Inspiron 3421               | [0195354549](https://linux-hardware.org/?probe=0195354549) | Apr 15, 2020 |
| Acer          | Aspire V3-551               | [f76effd4e1](https://linux-hardware.org/?probe=f76effd4e1) | Apr 15, 2020 |
| Acer          | Aspire V3-551               | [9a1d303595](https://linux-hardware.org/?probe=9a1d303595) | Apr 15, 2020 |
| HP            | Laptop 15-bs0xx             | [d0236dec02](https://linux-hardware.org/?probe=d0236dec02) | Apr 13, 2020 |
| HP            | Laptop 15-bs0xx             | [bdba19d5f6](https://linux-hardware.org/?probe=bdba19d5f6) | Apr 13, 2020 |
| Dell          | Inspiron 7375               | [52fe42d7b8](https://linux-hardware.org/?probe=52fe42d7b8) | Apr 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ef5318c61](https://linux-hardware.org/?probe=0ef5318c61) | Apr 10, 2020 |
| Dell          | Latitude E5470              | [5fff3b8e03](https://linux-hardware.org/?probe=5fff3b8e03) | Apr 09, 2020 |
| ASUSTek       | X555LAB                     | [703f6be9f9](https://linux-hardware.org/?probe=703f6be9f9) | Apr 09, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0d49279899](https://linux-hardware.org/?probe=0d49279899) | Apr 09, 2020 |
| Clevo         | M540SS                      | [874f7c9501](https://linux-hardware.org/?probe=874f7c9501) | Apr 08, 2020 |
| Advantec      | CX Infinito                 | [725e058276](https://linux-hardware.org/?probe=725e058276) | Apr 07, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [e954275a3f](https://linux-hardware.org/?probe=e954275a3f) | Apr 07, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [6f436a6beb](https://linux-hardware.org/?probe=6f436a6beb) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | [a9135d6bb0](https://linux-hardware.org/?probe=a9135d6bb0) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | [a207a4c9bc](https://linux-hardware.org/?probe=a207a4c9bc) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | [e400ea0d44](https://linux-hardware.org/?probe=e400ea0d44) | Apr 07, 2020 |
| Clevo         | M540SS                      | [e240e618e6](https://linux-hardware.org/?probe=e240e618e6) | Apr 06, 2020 |
| Acer          | Aspire M5-481T              | [d84e57fd45](https://linux-hardware.org/?probe=d84e57fd45) | Apr 05, 2020 |
| Garbarino ... | A24                         | [d511923402](https://linux-hardware.org/?probe=d511923402) | Apr 04, 2020 |
| HP            | Laptop 17-bs0xx             | [4d3ea4ac7f](https://linux-hardware.org/?probe=4d3ea4ac7f) | Apr 02, 2020 |
| Lenovo        | G550 2958                   | [aaaecc38c5](https://linux-hardware.org/?probe=aaaecc38c5) | Apr 02, 2020 |
| HP            | ENVY TS 15                  | [5849da2ef2](https://linux-hardware.org/?probe=5849da2ef2) | Mar 30, 2020 |
| HP            | ENVY TS 15                  | [029ee166c9](https://linux-hardware.org/?probe=029ee166c9) | Mar 30, 2020 |
| ASUSTek       | K55A                        | [256e0346d2](https://linux-hardware.org/?probe=256e0346d2) | Mar 28, 2020 |
| HP            | Pavilion dv6                | [8ed8042b01](https://linux-hardware.org/?probe=8ed8042b01) | Mar 28, 2020 |
| HP            | Pavilion dv6                | [3f0e2ec177](https://linux-hardware.org/?probe=3f0e2ec177) | Mar 28, 2020 |
| Dell          | Inspiron M5030              | [337c1cd178](https://linux-hardware.org/?probe=337c1cd178) | Mar 28, 2020 |
| Dell          | Inspiron M5030              | [1f90f010ba](https://linux-hardware.org/?probe=1f90f010ba) | Mar 28, 2020 |
| Dell          | Inspiron 7347               | [5d99eda08d](https://linux-hardware.org/?probe=5d99eda08d) | Mar 26, 2020 |
| BANGHO        | W7x0S Bottom                | [6c5df6e4f9](https://linux-hardware.org/?probe=6c5df6e4f9) | Mar 25, 2020 |
| Acer          | Aspire 5742                 | [fbdbfba4b5](https://linux-hardware.org/?probe=fbdbfba4b5) | Mar 23, 2020 |
| ASUSTek       | UX303UB                     | [34a2568628](https://linux-hardware.org/?probe=34a2568628) | Mar 23, 2020 |
| Lenovo        | IdeaPad U310                | [a9174b0de6](https://linux-hardware.org/?probe=a9174b0de6) | Mar 22, 2020 |
| Acer          | Aspire 5536                 | [0ccba96214](https://linux-hardware.org/?probe=0ccba96214) | Mar 22, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [a351ec49d6](https://linux-hardware.org/?probe=a351ec49d6) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [824e8de596](https://linux-hardware.org/?probe=824e8de596) | Mar 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6c3da9907e](https://linux-hardware.org/?probe=6c3da9907e) | Mar 17, 2020 |
| Sony          | VGN-FJ270                   | [0bca381eba](https://linux-hardware.org/?probe=0bca381eba) | Mar 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [435bc7ba91](https://linux-hardware.org/?probe=435bc7ba91) | Mar 14, 2020 |
| Standard      | MT40II                      | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Lenovo        | Edge 15 80K9                | [55c056e413](https://linux-hardware.org/?probe=55c056e413) | Mar 11, 2020 |
| Lenovo        | Edge 15 80K9                | [34ccd49d42](https://linux-hardware.org/?probe=34ccd49d42) | Mar 11, 2020 |
| MSI           | PL62 7RC                    | [863a014929](https://linux-hardware.org/?probe=863a014929) | Mar 07, 2020 |
| MSI           | PL62 7RC                    | [ed7f7c1df9](https://linux-hardware.org/?probe=ed7f7c1df9) | Mar 05, 2020 |
| Samsung       | R430/P430/R480              | [c45f564189](https://linux-hardware.org/?probe=c45f564189) | Mar 05, 2020 |
| MSI           | MS-7A38                     | [330e00de7a](https://linux-hardware.org/?probe=330e00de7a) | Mar 05, 2020 |
| HP            | 245 G7                      | [2c764c1e8e](https://linux-hardware.org/?probe=2c764c1e8e) | Mar 04, 2020 |
| Acer          | Aspire E5-575               | [42c1d97976](https://linux-hardware.org/?probe=42c1d97976) | Mar 04, 2020 |
| Gateway       | M-6823                      | [4dcbbf243d](https://linux-hardware.org/?probe=4dcbbf243d) | Mar 04, 2020 |
| Compal        | PBL2021                     | [7309857357](https://linux-hardware.org/?probe=7309857357) | Mar 02, 2020 |
| Compal        | PBL2021                     | [1845fca59b](https://linux-hardware.org/?probe=1845fca59b) | Mar 02, 2020 |
| Acer          | Prespa M                    | [31b62dbc70](https://linux-hardware.org/?probe=31b62dbc70) | Feb 29, 2020 |
| Exo           | CloudbookE15                | [49fe457d36](https://linux-hardware.org/?probe=49fe457d36) | Feb 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3c11fbee3d](https://linux-hardware.org/?probe=3c11fbee3d) | Feb 20, 2020 |
| Dell          | XPS 15 9560                 | [b6593ee087](https://linux-hardware.org/?probe=b6593ee087) | Feb 17, 2020 |
| BANGHO        | M7x0S                       | [f056d0963d](https://linux-hardware.org/?probe=f056d0963d) | Feb 13, 2020 |
| BANGHO        | M7x0S                       | [b44de4d481](https://linux-hardware.org/?probe=b44de4d481) | Feb 13, 2020 |
| Dell          | Studio 1558                 | [32393e7045](https://linux-hardware.org/?probe=32393e7045) | Feb 11, 2020 |
| Dell          | Studio 1558                 | [a044ba6101](https://linux-hardware.org/?probe=a044ba6101) | Feb 11, 2020 |
| Toshiba       | Satellite C805              | [fb0363f3da](https://linux-hardware.org/?probe=fb0363f3da) | Feb 11, 2020 |
| Dell          | Inspiron 1545               | [d558a45887](https://linux-hardware.org/?probe=d558a45887) | Feb 09, 2020 |
| Dell          | Inspiron 1545               | [b2a0d6b4ee](https://linux-hardware.org/?probe=b2a0d6b4ee) | Feb 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4a1bfddf30](https://linux-hardware.org/?probe=4a1bfddf30) | Feb 06, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [ce93e09397](https://linux-hardware.org/?probe=ce93e09397) | Feb 03, 2020 |
| HP            | 240 G5 Notebook PC          | [bfcf32e6bd](https://linux-hardware.org/?probe=bfcf32e6bd) | Feb 02, 2020 |
| Gigabyte      | GB-BSi7A-6500               | [c7e43fe03a](https://linux-hardware.org/?probe=c7e43fe03a) | Feb 02, 2020 |
| Lenovo        | Z40-75 80DW                 | [9c75318b3d](https://linux-hardware.org/?probe=9c75318b3d) | Jan 30, 2020 |
| HP            | Pavilion Laptop 15-cd0xx    | [5c150495e4](https://linux-hardware.org/?probe=5c150495e4) | Jan 28, 2020 |
| HP            | Pavilion Laptop 15-cd0xx    | [74289cde89](https://linux-hardware.org/?probe=74289cde89) | Jan 28, 2020 |
| HP            | 240 G5 Notebook PC          | [051e7f12fa](https://linux-hardware.org/?probe=051e7f12fa) | Jan 27, 2020 |
| Dell          | Inspiron 7375               | [458ef2c975](https://linux-hardware.org/?probe=458ef2c975) | Jan 17, 2020 |
| Lenovo        | G580 20150                  | [b0d26093fb](https://linux-hardware.org/?probe=b0d26093fb) | Jan 17, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| Sony          | VPCF22KFX                   | [e471a3b2fa](https://linux-hardware.org/?probe=e471a3b2fa) | Jan 12, 2020 |
| HP            | Laptop 14-bp0xx             | [479611003b](https://linux-hardware.org/?probe=479611003b) | Jan 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32dc7aef50](https://linux-hardware.org/?probe=32dc7aef50) | Jan 03, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [1a2b9c2648](https://linux-hardware.org/?probe=1a2b9c2648) | Jan 03, 2020 |
| HP            | Laptop 17-bs0xx             | [ccd20e9767](https://linux-hardware.org/?probe=ccd20e9767) | Dec 23, 2019 |
| Exo           | CloudbookE15                | [0e39d67535](https://linux-hardware.org/?probe=0e39d67535) | Dec 20, 2019 |
| HP            | Laptop 17-bs0xx             | [7aedd09762](https://linux-hardware.org/?probe=7aedd09762) | Dec 09, 2019 |
| Positivo      | Unknown                     | [f668caa5b9](https://linux-hardware.org/?probe=f668caa5b9) | Dec 07, 2019 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [67f2124d45](https://linux-hardware.org/?probe=67f2124d45) | Dec 02, 2019 |
| HP            | Laptop 17-bs0xx             | [cc9d4c9e1d](https://linux-hardware.org/?probe=cc9d4c9e1d) | Nov 29, 2019 |
| HP            | 14                          | [1f86f4415b](https://linux-hardware.org/?probe=1f86f4415b) | Nov 29, 2019 |
| HP            | Laptop 17-bs0xx             | [4cf777cd16](https://linux-hardware.org/?probe=4cf777cd16) | Nov 29, 2019 |
| HP            | 14                          | [5b1d780d67](https://linux-hardware.org/?probe=5b1d780d67) | Nov 27, 2019 |
| Lenovo        | ThinkPad T530 2429B51       | [ec672467e4](https://linux-hardware.org/?probe=ec672467e4) | Nov 12, 2019 |
| Lenovo        | ThinkPad T530 2429B51       | [cb054fe768](https://linux-hardware.org/?probe=cb054fe768) | Nov 12, 2019 |
| ASUSTek       | X556UB                      | [61005631b6](https://linux-hardware.org/?probe=61005631b6) | Nov 08, 2019 |
| Toshiba       | Satellite_C50-A             | [de6c2e6b3a](https://linux-hardware.org/?probe=de6c2e6b3a) | Oct 31, 2019 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [f4f82d41f4](https://linux-hardware.org/?probe=f4f82d41f4) | Oct 29, 2019 |
| Gigabyte      | GB-BSi7A-6500               | [017f404601](https://linux-hardware.org/?probe=017f404601) | Oct 26, 2019 |
| Exo           | Intel powered classmate ... | [cc6b4b6840](https://linux-hardware.org/?probe=cc6b4b6840) | Oct 26, 2019 |
| HP            | Notebook                    | [cec70bf357](https://linux-hardware.org/?probe=cec70bf357) | Oct 18, 2019 |
| Lenovo        | ThinkPad E550 20DF0040US    | [02fdbe29e6](https://linux-hardware.org/?probe=02fdbe29e6) | Sep 27, 2019 |
| Lenovo        | ThinkPad E550 20DF0040US    | [0bd7b7a604](https://linux-hardware.org/?probe=0bd7b7a604) | Sep 26, 2019 |
| Samsung       | 530U3C/530U4C               | [f182396d91](https://linux-hardware.org/?probe=f182396d91) | Sep 20, 2019 |
| HP            | 250 G6 Notebook PC          | [bd2b6bff49](https://linux-hardware.org/?probe=bd2b6bff49) | Sep 17, 2019 |
| NOBLEX        | SF20BA                      | [cc059cb56c](https://linux-hardware.org/?probe=cc059cb56c) | Sep 16, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4e7e4f497c](https://linux-hardware.org/?probe=4e7e4f497c) | Sep 07, 2019 |
| ASUSTek       | G60JX                       | [a89e10b5b7](https://linux-hardware.org/?probe=a89e10b5b7) | Sep 05, 2019 |
| HP            | Laptop 15-bs0xx             | [72b30ba9f6](https://linux-hardware.org/?probe=72b30ba9f6) | Aug 31, 2019 |
| HP            | 250 G6 Notebook PC          | [fcb487dd8a](https://linux-hardware.org/?probe=fcb487dd8a) | Aug 27, 2019 |
| Clevo         | W7x0S Bottom                | [78ff985cb8](https://linux-hardware.org/?probe=78ff985cb8) | Aug 26, 2019 |
| Exo           | CloudbookE15                | [9a16d4a087](https://linux-hardware.org/?probe=9a16d4a087) | Aug 19, 2019 |
| Lenovo        | G50-70 20351                | [441b3f2fa7](https://linux-hardware.org/?probe=441b3f2fa7) | Aug 16, 2019 |
| HP            | 240 G7 Notebook PC          | [f542251613](https://linux-hardware.org/?probe=f542251613) | Aug 14, 2019 |
| HP            | 240 G7 Notebook PC          | [fdf4c7f5ea](https://linux-hardware.org/?probe=fdf4c7f5ea) | Aug 14, 2019 |
| BANGHO        | ZERO M4                     | [dff4987122](https://linux-hardware.org/?probe=dff4987122) | Aug 12, 2019 |
| BANGHO        | ZERO M4                     | [0b69fdc59f](https://linux-hardware.org/?probe=0b69fdc59f) | Aug 12, 2019 |
| Exo           | CloudbookE15                | [0b99f366be](https://linux-hardware.org/?probe=0b99f366be) | Aug 10, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [f64db4ea90](https://linux-hardware.org/?probe=f64db4ea90) | Aug 06, 2019 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c0397bcd43](https://linux-hardware.org/?probe=c0397bcd43) | Aug 05, 2019 |
| Positivo      | Unknown                     | [5599794994](https://linux-hardware.org/?probe=5599794994) | Jul 28, 2019 |
| Positivo      | Unknown                     | [dfe80e0a47](https://linux-hardware.org/?probe=dfe80e0a47) | Jul 28, 2019 |
| Positivo      | Unknown                     | [4422093eae](https://linux-hardware.org/?probe=4422093eae) | Jul 28, 2019 |
| ASUSTek       | X556UB                      | [949fd12104](https://linux-hardware.org/?probe=949fd12104) | Jul 25, 2019 |
| Positivo      | Unknown                     | [5f509f5f86](https://linux-hardware.org/?probe=5f509f5f86) | Jul 20, 2019 |
| Acer          | Aspire ES1-572              | [ae1ce65d11](https://linux-hardware.org/?probe=ae1ce65d11) | Jul 20, 2019 |
| HP            | Compaq Presario C700        | [77770402e0](https://linux-hardware.org/?probe=77770402e0) | Jul 17, 2019 |
| ASUSTek       | N56VJ                       | [566f024b92](https://linux-hardware.org/?probe=566f024b92) | Jul 12, 2019 |
| Unknown       | Unknown                     | [b49cc3bcfb](https://linux-hardware.org/?probe=b49cc3bcfb) | Jul 12, 2019 |
| Unknown       | Unknown                     | [90826ac0e7](https://linux-hardware.org/?probe=90826ac0e7) | Jul 11, 2019 |
| HP            | ProBook 450 G4              | [4fb036ba95](https://linux-hardware.org/?probe=4fb036ba95) | Jul 03, 2019 |
| Compal        | PCW20                       | [558fcaea9e](https://linux-hardware.org/?probe=558fcaea9e) | Jun 30, 2019 |
| Compal        | PCW20                       | [a17a9cddf2](https://linux-hardware.org/?probe=a17a9cddf2) | Jun 30, 2019 |
| ASUSTek       | N56VJ                       | [d83ca64ffa](https://linux-hardware.org/?probe=d83ca64ffa) | Jun 24, 2019 |
| Lenovo        | G470 20078                  | [da5525113b](https://linux-hardware.org/?probe=da5525113b) | Jun 23, 2019 |
| Lenovo        | G470 20078                  | [c07533b379](https://linux-hardware.org/?probe=c07533b379) | Jun 23, 2019 |
| Compal        | VAW70                       | [8533a07584](https://linux-hardware.org/?probe=8533a07584) | Jun 23, 2019 |
| Garbarino ... | A24                         | [6a59b71281](https://linux-hardware.org/?probe=6a59b71281) | Jun 22, 2019 |
| Dell          | Inspiron N4020              | [2d519bfadf](https://linux-hardware.org/?probe=2d519bfadf) | Jun 19, 2019 |
| Positivo      | SW6H                        | [8368dd78dd](https://linux-hardware.org/?probe=8368dd78dd) | Jun 18, 2019 |
| HP            | Laptop 15-bs1xx             | [ae39dc6976](https://linux-hardware.org/?probe=ae39dc6976) | Jun 11, 2019 |
| Positivo      | Z100                        | [0806f6416c](https://linux-hardware.org/?probe=0806f6416c) | Jun 09, 2019 |
| Toshiba       | PORTEGE R830                | [27abe342b6](https://linux-hardware.org/?probe=27abe342b6) | Jun 09, 2019 |
| Toshiba       | Satellite P755              | [1fc56d39f8](https://linux-hardware.org/?probe=1fc56d39f8) | Jun 01, 2019 |
| Acer          | Aspire A314-31              | [a7ef3d5e94](https://linux-hardware.org/?probe=a7ef3d5e94) | May 23, 2019 |
| Positivo      | Unknown                     | [281e70961f](https://linux-hardware.org/?probe=281e70961f) | May 12, 2019 |
| Positivo      | Unknown                     | [4f010c0c3f](https://linux-hardware.org/?probe=4f010c0c3f) | May 07, 2019 |
| Gigabyte      | GB-BNi5HG4-950              | [f972d2d1f1](https://linux-hardware.org/?probe=f972d2d1f1) | May 03, 2019 |
| Gigabyte      | GB-BNi5HG4-950              | [f53e1b8618](https://linux-hardware.org/?probe=f53e1b8618) | May 03, 2019 |
| Gigabyte      | GB-BNi5HG4-950              | [66428abcd8](https://linux-hardware.org/?probe=66428abcd8) | May 03, 2019 |
| Samsung       | R430/P430/R480              | [f22564b136](https://linux-hardware.org/?probe=f22564b136) | Apr 28, 2019 |
| HP            | Laptop 15-bs1xx             | [50bffeef87](https://linux-hardware.org/?probe=50bffeef87) | Apr 23, 2019 |
| Exo           | C14CR - SN: 0857932A0001... | [477a136419](https://linux-hardware.org/?probe=477a136419) | Apr 17, 2019 |
| HP            | Pavilion dv6000 (RP285UA... | [92cd40afad](https://linux-hardware.org/?probe=92cd40afad) | Apr 16, 2019 |
| Samsung       | R430/P430/R480              | [078d57f599](https://linux-hardware.org/?probe=078d57f599) | Apr 16, 2019 |
| Dell          | Inspiron 1525               | [e227839676](https://linux-hardware.org/?probe=e227839676) | Apr 16, 2019 |
| HP            | Laptop 15-bs0xx             | [009a60c959](https://linux-hardware.org/?probe=009a60c959) | Apr 14, 2019 |
| HP            | Laptop 15-bs0xx             | [6e239fa433](https://linux-hardware.org/?probe=6e239fa433) | Apr 14, 2019 |
| Dell          | Latitude E6410              | [683ab8bd94](https://linux-hardware.org/?probe=683ab8bd94) | Apr 13, 2019 |
| ASUSTek       | UX303UB                     | [500913705e](https://linux-hardware.org/?probe=500913705e) | Apr 12, 2019 |
| Sony          | VGN-CR260FE                 | [3bee1ddf68](https://linux-hardware.org/?probe=3bee1ddf68) | Apr 11, 2019 |
| Exo           | Intel powered classmate ... | [94d95acab7](https://linux-hardware.org/?probe=94d95acab7) | Apr 09, 2019 |
| HP            | Pavilion 15                 | [9a3053250c](https://linux-hardware.org/?probe=9a3053250c) | Apr 08, 2019 |
| Samsung       | 300E4A/300E5A/300E7A        | [63f767c5a3](https://linux-hardware.org/?probe=63f767c5a3) | Apr 07, 2019 |
| HP            | Pavilion 15                 | [065ded27e2](https://linux-hardware.org/?probe=065ded27e2) | Apr 06, 2019 |
| HP            | Pavilion 15                 | [ec93defa5a](https://linux-hardware.org/?probe=ec93defa5a) | Apr 06, 2019 |
| Dell          | Inspiron 1525               | [0fd8be530d](https://linux-hardware.org/?probe=0fd8be530d) | Apr 05, 2019 |
| Dell          | Inspiron 1525               | [97f5b3daae](https://linux-hardware.org/?probe=97f5b3daae) | Apr 05, 2019 |
| ASUSTek       | X555LAB                     | [06df03de64](https://linux-hardware.org/?probe=06df03de64) | Apr 04, 2019 |
| Exo           | Smart E13                   | [c6253fe399](https://linux-hardware.org/?probe=c6253fe399) | Apr 04, 2019 |
| Exo           | CloudbookE15                | [abc8f8a1bc](https://linux-hardware.org/?probe=abc8f8a1bc) | Apr 03, 2019 |
| Exo           | CloudbookE15                | [6a94242efa](https://linux-hardware.org/?probe=6a94242efa) | Apr 03, 2019 |
| Dell          | Inspiron 3459               | [0b4b479837](https://linux-hardware.org/?probe=0b4b479837) | Mar 30, 2019 |
| Dell          | Latitude E5510              | [3b87996f54](https://linux-hardware.org/?probe=3b87996f54) | Mar 30, 2019 |
| Olivetti      | U40SI                       | [b92d6e75ba](https://linux-hardware.org/?probe=b92d6e75ba) | Mar 30, 2019 |
| Olivetti      | U40SI                       | [b009ca39da](https://linux-hardware.org/?probe=b009ca39da) | Mar 30, 2019 |
| Intel         | powered classmate PC MP ... | [82cc703cb0](https://linux-hardware.org/?probe=82cc703cb0) | Mar 30, 2019 |
| HP            | Notebook                    | [70e4e79726](https://linux-hardware.org/?probe=70e4e79726) | Mar 30, 2019 |
| HP            | Laptop 14-bs0xx             | [2ef4aa6566](https://linux-hardware.org/?probe=2ef4aa6566) | Mar 27, 2019 |
| Exo           | CloudbookE15                | [9afd6329e7](https://linux-hardware.org/?probe=9afd6329e7) | Mar 27, 2019 |
| Exo           | CloudbookE15                | [e997a6e1ba](https://linux-hardware.org/?probe=e997a6e1ba) | Mar 27, 2019 |
| Clevo         | M540SS Bottom               | [135b9afcb3](https://linux-hardware.org/?probe=135b9afcb3) | Mar 26, 2019 |
| Clevo         | M540SS Bottom               | [5c84c82b4c](https://linux-hardware.org/?probe=5c84c82b4c) | Mar 26, 2019 |
| Quanta        | TW8/SW8/DW8                 | [b2feccb6a9](https://linux-hardware.org/?probe=b2feccb6a9) | Mar 25, 2019 |
| Quanta        | TW8/SW8/DW8                 | [a26971bb87](https://linux-hardware.org/?probe=a26971bb87) | Mar 25, 2019 |
| Samsung       | 530U3C/530U4C               | [71764cdef4](https://linux-hardware.org/?probe=71764cdef4) | Mar 24, 2019 |
| Kelyx Arge... | KL156X5                     | [c961c27b11](https://linux-hardware.org/?probe=c961c27b11) | Mar 17, 2019 |
| HP            | Laptop 15-bs0xx             | [e63875dac9](https://linux-hardware.org/?probe=e63875dac9) | Feb 21, 2019 |
| Toshiba       | Satellite L755D             | [e601efe09a](https://linux-hardware.org/?probe=e601efe09a) | Feb 21, 2019 |
| Dell          | Inspiron 5535               | [4fc984366c](https://linux-hardware.org/?probe=4fc984366c) | Feb 17, 2019 |
| ASUSTek       | UX303UB                     | [7e11d39010](https://linux-hardware.org/?probe=7e11d39010) | Jan 21, 2019 |
| Lenovo        | 3000 C200 8922A57           | [b8e129f8e2](https://linux-hardware.org/?probe=b8e129f8e2) | Jan 16, 2019 |
| Lenovo        | 3000 C200 8922A57           | [bb97b9f94d](https://linux-hardware.org/?probe=bb97b9f94d) | Jan 16, 2019 |
| Sony          | VPCM120AL                   | [20c032ae5b](https://linux-hardware.org/?probe=20c032ae5b) | Jan 13, 2019 |
| Sony          | VPCM120AL                   | [0df90972c9](https://linux-hardware.org/?probe=0df90972c9) | Jan 13, 2019 |
| Lenovo        | ThinkPad T440p 20AW0049A... | [c345304bc6](https://linux-hardware.org/?probe=c345304bc6) | Jan 03, 2019 |
| Dell          | Inspiron 3576               | [5c729e4690](https://linux-hardware.org/?probe=5c729e4690) | Dec 29, 2018 |
| Toshiba       | Satellite L845              | [dc2198b459](https://linux-hardware.org/?probe=dc2198b459) | Dec 27, 2018 |
| Toshiba       | Satellite L845              | [538096e332](https://linux-hardware.org/?probe=538096e332) | Dec 27, 2018 |
| Dell          | Inspiron 3576               | [9a69c53fac](https://linux-hardware.org/?probe=9a69c53fac) | Dec 20, 2018 |
| Lenovo        | G50-80 80E5                 | [0aa56a430a](https://linux-hardware.org/?probe=0aa56a430a) | Dec 16, 2018 |
| Lenovo        | G50-80 80E5                 | [b863959c49](https://linux-hardware.org/?probe=b863959c49) | Dec 16, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b218951cf6](https://linux-hardware.org/?probe=b218951cf6) | Nov 18, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [07223fc3e5](https://linux-hardware.org/?probe=07223fc3e5) | Nov 18, 2018 |
| Toshiba       | Satellite-L845              | [73e593cc58](https://linux-hardware.org/?probe=73e593cc58) | Nov 16, 2018 |
| Toshiba       | Satellite-L845              | [5bd2c5bdb7](https://linux-hardware.org/?probe=5bd2c5bdb7) | Nov 16, 2018 |
| Intel         | powered classmate PC        | [d30aac7727](https://linux-hardware.org/?probe=d30aac7727) | Nov 06, 2018 |
| Intel         | powered classmate PC        | [605cd41e53](https://linux-hardware.org/?probe=605cd41e53) | Nov 06, 2018 |
| Lenovo        | ThinkPad T530 2429B51       | [b1cddcac7d](https://linux-hardware.org/?probe=b1cddcac7d) | Nov 01, 2018 |
| Lenovo        | BP PV CLASSMATE+            | [6fbea36f98](https://linux-hardware.org/?probe=6fbea36f98) | Oct 22, 2018 |
| Lenovo        | BP PV CLASSMATE+            | [cafb057c19](https://linux-hardware.org/?probe=cafb057c19) | Oct 22, 2018 |
| Positivo      | Unknown                     | [d826611187](https://linux-hardware.org/?probe=d826611187) | Sep 24, 2018 |
| Lenovo        | Flex 3-1480 80R3            | [39115f2454](https://linux-hardware.org/?probe=39115f2454) | Aug 20, 2018 |
| Lenovo        | Flex 3-1480 80R3            | [4f70ec7614](https://linux-hardware.org/?probe=4f70ec7614) | Aug 20, 2018 |
| HP            | Pavilion dv1000 (EE633LA... | [0572e8425c](https://linux-hardware.org/?probe=0572e8425c) | May 28, 2018 |
| Toshiba       | Satellite L645              | [f1d57ca174](https://linux-hardware.org/?probe=f1d57ca174) | Jan 23, 2018 |
| Acer          | Aspire E5-575               | [1da1de1f82](https://linux-hardware.org/?probe=1da1de1f82) | Sep 02, 2017 |
| BANGHO        | W240HU/W250HUQ              | [3c75190e68](https://linux-hardware.org/?probe=3c75190e68) | Jul 26, 2017 |
| Exo           | Exomate X352                | [8aec997442](https://linux-hardware.org/?probe=8aec997442) | Jun 13, 2017 |
| Exo           | Exomate X352                | [f9af6bbe98](https://linux-hardware.org/?probe=f9af6bbe98) | Jun 10, 2017 |
| Positivo      | QL400                       | [9562fcae31](https://linux-hardware.org/?probe=9562fcae31) | May 28, 2017 |
| HP            | Compaq 6530b (FG210EC#AC... | [3c6119daa5](https://linux-hardware.org/?probe=3c6119daa5) | May 11, 2017 |
| Dell          | Inspiron M5030              | [27522e22b3](https://linux-hardware.org/?probe=27522e22b3) | May 01, 2017 |
| Acer          | Aspire E5-575               | [5974a74bfd](https://linux-hardware.org/?probe=5974a74bfd) | Mar 31, 2017 |
| HP            | Compaq 6530b (FG210EC#AC... | [8c3712689f](https://linux-hardware.org/?probe=8c3712689f) | Mar 08, 2017 |
| ASUSTek       | K52Dr                       | [a1bd0d7349](https://linux-hardware.org/?probe=a1bd0d7349) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 118       | 15.97%  |
| Ubuntu 18.04                 | 97        | 13.13%  |
| OpenMandriva 4.2             | 23        | 3.11%   |
| Zorin 15                     | 19        | 2.57%   |
| BlackPanther 18.1            | 16        | 2.17%   |
| Linux Mint 20.2              | 15        | 2.03%   |
| Debian 11                    | 15        | 2.03%   |
| Linux Mint 20.1              | 14        | 1.89%   |
| Linux Mint 20                | 13        | 1.76%   |
| Fedora 33                    | 13        | 1.76%   |
| Xubuntu 20.04                | 12        | 1.62%   |
| Ubuntu 22.04                 | 12        | 1.62%   |
| OpenMandriva 4.3             | 12        | 1.62%   |
| Linux Mint 19.3              | 12        | 1.62%   |
| Arch                         | 12        | 1.62%   |
| Ubuntu 19.04                 | 11        | 1.49%   |
| Ubuntu 18.10                 | 10        | 1.35%   |
| Fedora 34                    | 10        | 1.35%   |
| Fedora 32                    | 9         | 1.22%   |
| Debian 10                    | 9         | 1.22%   |
| Ubuntu 19.10                 | 8         | 1.08%   |
| KDE neon 20.04               | 8         | 1.08%   |
| Xubuntu 18.04                | 7         | 0.95%   |
| Ubuntu 21.10                 | 7         | 0.95%   |
| Ubuntu 16.04                 | 7         | 0.95%   |
| Pop!_OS 20.04                | 7         | 0.95%   |
| Linux Mint 20.3              | 7         | 0.95%   |
| Fedora 35                    | 7         | 0.95%   |
| ArcoLinux Rolling            | 7         | 0.95%   |
| Arch Rolling                 | 7         | 0.95%   |
| Ubuntu 20.10                 | 6         | 0.81%   |
| Pop!_OS 21.04                | 6         | 0.81%   |
| Pop!_OS 20.10                | 6         | 0.81%   |
| LMDE 4                       | 6         | 0.81%   |
| Zorin 16                     | 5         | 0.68%   |
| Ubuntu MATE 20.04            | 5         | 0.68%   |
| Manjaro                      | 5         | 0.68%   |
| Kubuntu 20.04                | 5         | 0.68%   |
| Fedora 36                    | 5         | 0.68%   |
| Endless 3.8.0                | 5         | 0.68%   |
| Debian 9                     | 5         | 0.68%   |
| Ubuntu 21.04                 | 4         | 0.54%   |
| ROSA R9                      | 4         | 0.54%   |
| Pop!_OS 21.10                | 4         | 0.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.54%   |
| Endless 3.8.4                | 4         | 0.54%   |
| Elementary 6.1               | 4         | 0.54%   |
| Elementary 6                 | 4         | 0.54%   |
| Ubuntu Budgie 21.04          | 3         | 0.41%   |
| ROSA R8.1                    | 3         | 0.41%   |
| Pop!_OS 22.04                | 3         | 0.41%   |
| Peppermint 10                | 3         | 0.41%   |
| Lubuntu 20.04                | 3         | 0.41%   |
| Linux Mint 19.2              | 3         | 0.41%   |
| Fedora 31                    | 3         | 0.41%   |
| Endless 3.9.4                | 3         | 0.41%   |
| Endless 3.8.3                | 3         | 0.41%   |
| EndeavourOS Rolling          | 3         | 0.41%   |
| Xubuntu 20.10                | 2         | 0.27%   |
| Xubuntu 19.10                | 2         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 273       | 38.61%  |
| Linux Mint    | 64        | 9.05%   |
| Fedora        | 42        | 5.94%   |
| OpenMandriva  | 36        | 5.09%   |
| Endless       | 31        | 4.38%   |
| Debian        | 30        | 4.24%   |
| Pop!_OS       | 26        | 3.68%   |
| Zorin         | 25        | 3.54%   |
| Xubuntu       | 23        | 3.25%   |
| Arch          | 18        | 2.55%   |
| BlackPanther  | 16        | 2.26%   |
| Manjaro       | 14        | 1.98%   |
| Elementary    | 12        | 1.7%    |
| Ubuntu Budgie | 9         | 1.27%   |
| Kubuntu       | 9         | 1.27%   |
| KDE neon      | 9         | 1.27%   |
| ROSA          | 8         | 1.13%   |
| ArcoLinux     | 8         | 1.13%   |
| Lubuntu       | 7         | 0.99%   |
| LMDE          | 6         | 0.85%   |
| Ubuntu MATE   | 5         | 0.71%   |
| EndeavourOS   | 5         | 0.71%   |
| openSUSE      | 4         | 0.57%   |
| Peppermint    | 3         | 0.42%   |
| LinuxFX       | 3         | 0.42%   |
| Gentoo        | 3         | 0.42%   |
| Clear Linux   | 3         | 0.42%   |
| UbuntuDDE     | 2         | 0.28%   |
| Huayra        | 2         | 0.28%   |
| CentOS        | 2         | 0.28%   |
| RHEL          | 1         | 0.14%   |
| Parrot        | 1         | 0.14%   |
| Oracle Linux  | 1         | 0.14%   |
| Kali          | 1         | 0.14%   |
| Hefftor       | 1         | 0.14%   |
| Feren OS      | 1         | 0.14%   |
| Deepin        | 1         | 0.14%   |
| Chrome OS     | 1         | 0.14%   |
| Artix         | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 22        | 2.74%   |
| 5.4.0-42-generic         | 21        | 2.62%   |
| 4.18.16-desktop-1bP      | 16        | 1.99%   |
| 5.4.0-26-generic         | 15        | 1.87%   |
| 5.3.0-40-generic         | 12        | 1.49%   |
| 5.16.7-desktop-1omv4003  | 12        | 1.49%   |
| 5.4.0-52-generic         | 11        | 1.37%   |
| 5.4.0-19-generic         | 10        | 1.25%   |
| 5.4.0-29-generic         | 9         | 1.12%   |
| 5.8.0-14-generic         | 8         | 1%      |
| 5.4.0-48-generic         | 8         | 1%      |
| 5.4.0-40-generic         | 8         | 1%      |
| 5.11.0-37-generic        | 8         | 1%      |
| 4.18.0-15-generic        | 8         | 1%      |
| 5.8.0-43-generic         | 7         | 0.87%   |
| 5.4.0-91-generic         | 7         | 0.87%   |
| 5.4.0-72-generic         | 7         | 0.87%   |
| 5.4.0-58-generic         | 7         | 0.87%   |
| 5.3.0-46-generic         | 7         | 0.87%   |
| 5.3.0-28-generic         | 7         | 0.87%   |
| 5.11.0-27-generic        | 7         | 0.87%   |
| 5.8.0-7630-generic       | 6         | 0.75%   |
| 5.4.0-73-generic         | 6         | 0.75%   |
| 5.4.0-47-generic         | 6         | 0.75%   |
| 5.4.0-45-generic         | 6         | 0.75%   |
| 5.4.0-37-generic         | 6         | 0.75%   |
| 5.3.0-42-generic         | 6         | 0.75%   |
| 5.13.0-40-generic        | 6         | 0.75%   |
| 5.13.0-35-generic        | 6         | 0.75%   |
| 4.18.0-17-generic        | 6         | 0.75%   |
| 5.8.0-59-generic         | 5         | 0.62%   |
| 5.4.0-74-generic         | 5         | 0.62%   |
| 5.3.0-53-generic         | 5         | 0.62%   |
| 5.11.0-38-generic        | 5         | 0.62%   |
| 5.10.0-9-amd64           | 5         | 0.62%   |
| 5.0.0-32-generic         | 5         | 0.62%   |
| 5.0.0-23-generic         | 5         | 0.62%   |
| 4.18.0-16-generic        | 5         | 0.62%   |
| 5.8.0-50-generic         | 4         | 0.5%    |
| 5.4.0-80-generic         | 4         | 0.5%    |
| 5.4.0-66-generic         | 4         | 0.5%    |
| 5.4.0-65-generic         | 4         | 0.5%    |
| 5.4.0-33-generic         | 4         | 0.5%    |
| 5.4.0-31-generic         | 4         | 0.5%    |
| 5.3.0-62-generic         | 4         | 0.5%    |
| 5.0.0-13-generic         | 4         | 0.5%    |
| 4.15.0-96-generic        | 4         | 0.5%    |
| 4.15.0-91-generic        | 4         | 0.5%    |
| 4.15.0-47-generic        | 4         | 0.5%    |
| 4.15.0-43-generic        | 4         | 0.5%    |
| 4.15.0-29-generic        | 4         | 0.5%    |
| 5.8.0-53-generic         | 3         | 0.37%   |
| 5.8.0-44-generic         | 3         | 0.37%   |
| 5.8.0-36-generic         | 3         | 0.37%   |
| 5.4.0-89-generic         | 3         | 0.37%   |
| 5.4.0-7642-generic       | 3         | 0.37%   |
| 5.4.0-56-generic         | 3         | 0.37%   |
| 5.4.0-54-generic         | 3         | 0.37%   |
| 5.4.0-39-generic         | 3         | 0.37%   |
| 5.4.0-28-generic         | 3         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 185       | 24.34%  |
| 4.15.0  | 59        | 7.76%   |
| 5.3.0   | 58        | 7.63%   |
| 5.8.0   | 54        | 7.11%   |
| 5.11.0  | 37        | 4.87%   |
| 5.13.0  | 32        | 4.21%   |
| 5.0.0   | 30        | 3.95%   |
| 4.18.0  | 28        | 3.68%   |
| 5.10.14 | 22        | 2.89%   |
| 5.10.0  | 17        | 2.24%   |
| 4.19.0  | 16        | 2.11%   |
| 4.18.16 | 16        | 2.11%   |
| 5.16.7  | 12        | 1.58%   |
| 5.15.0  | 12        | 1.58%   |
| 5.15.5  | 5         | 0.66%   |
| 5.9.10  | 4         | 0.53%   |
| 5.18.5  | 4         | 0.53%   |
| 5.17.5  | 4         | 0.53%   |
| 5.15.8  | 4         | 0.53%   |
| 5.14.0  | 4         | 0.53%   |
| 5.11.12 | 4         | 0.53%   |
| 4.9.20  | 4         | 0.53%   |
| 5.8.6   | 3         | 0.39%   |
| 5.8.16  | 3         | 0.39%   |
| 5.16.19 | 3         | 0.39%   |
| 5.9.16  | 2         | 0.26%   |
| 5.9.14  | 2         | 0.26%   |
| 5.9.11  | 2         | 0.26%   |
| 5.8.4   | 2         | 0.26%   |
| 5.8.15  | 2         | 0.26%   |
| 5.7.9   | 2         | 0.26%   |
| 5.7.11  | 2         | 0.26%   |
| 5.5.15  | 2         | 0.26%   |
| 5.18.6  | 2         | 0.26%   |
| 5.18.3  | 2         | 0.26%   |
| 5.17.6  | 2         | 0.26%   |
| 5.16.16 | 2         | 0.26%   |
| 5.16.11 | 2         | 0.26%   |
| 5.16.0  | 2         | 0.26%   |
| 5.15.19 | 2         | 0.26%   |
| 5.15.13 | 2         | 0.26%   |
| 5.15.11 | 2         | 0.26%   |
| 5.14.9  | 2         | 0.26%   |
| 5.14.7  | 2         | 0.26%   |
| 5.13.19 | 2         | 0.26%   |
| 5.13.13 | 2         | 0.26%   |
| 5.11.18 | 2         | 0.26%   |
| 5.11.16 | 2         | 0.26%   |
| 5.11.14 | 2         | 0.26%   |
| 4.9.9   | 2         | 0.26%   |
| 4.9.0   | 2         | 0.26%   |
| 4.13.0  | 2         | 0.26%   |
| 3.10.0  | 2         | 0.26%   |
| 5.9.8   | 1         | 0.13%   |
| 5.9.15  | 1         | 0.13%   |
| 5.9.0   | 1         | 0.13%   |
| 5.8.7   | 1         | 0.13%   |
| 5.8.17  | 1         | 0.13%   |
| 5.8.13  | 1         | 0.13%   |
| 5.8.12  | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 191       | 25.53%  |
| 5.8     | 67        | 8.96%   |
| 4.15    | 59        | 7.89%   |
| 5.3     | 58        | 7.75%   |
| 5.11    | 50        | 6.68%   |
| 5.10    | 47        | 6.28%   |
| 4.18    | 46        | 6.15%   |
| 5.13    | 42        | 5.61%   |
| 5.0     | 32        | 4.28%   |
| 5.15    | 31        | 4.14%   |
| 5.16    | 25        | 3.34%   |
| 4.19    | 18        | 2.41%   |
| 5.9     | 12        | 1.6%    |
| 5.14    | 11        | 1.47%   |
| 5.6     | 9         | 1.2%    |
| 5.18    | 9         | 1.2%    |
| 4.9     | 8         | 1.07%   |
| 5.7     | 7         | 0.94%   |
| 5.17    | 7         | 0.94%   |
| 5.12    | 6         | 0.8%    |
| 5.5     | 3         | 0.4%    |
| 4.13    | 2         | 0.27%   |
| 4.1     | 2         | 0.27%   |
| 3.10    | 2         | 0.27%   |
| 4.4     | 1         | 0.13%   |
| 4.17    | 1         | 0.13%   |
| 4.10    | 1         | 0.13%   |
| 3.16    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 645       | 93.21%  |
| i686   | 47        | 6.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 311       | 43.44%  |
| Unknown          | 102       | 14.25%  |
| KDE5             | 91        | 12.71%  |
| XFCE             | 58        | 8.1%    |
| X-Cinnamon       | 43        | 6.01%   |
| MATE             | 25        | 3.49%   |
| KDE              | 16        | 2.23%   |
| Pantheon         | 11        | 1.54%   |
| Budgie           | 10        | 1.4%    |
| LXQt             | 8         | 1.12%   |
| LXDE             | 7         | 0.98%   |
| Cinnamon         | 7         | 0.98%   |
| Unity            | 5         | 0.7%    |
| KDE4             | 5         | 0.7%    |
| i3               | 5         | 0.7%    |
| Deepin           | 4         | 0.56%   |
| xmonad           | 1         | 0.14%   |
| sway             | 1         | 0.14%   |
| openbox          | 1         | 0.14%   |
| lightdm-xsession | 1         | 0.14%   |
| i3-with-shmlog   | 1         | 0.14%   |
| GNOME Flashback  | 1         | 0.14%   |
| bspwm            | 1         | 0.14%   |
| awesome          | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 570       | 80.74%  |
| Wayland | 69        | 9.77%   |
| Unknown | 63        | 8.92%   |
| Tty     | 4         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 428       | 60.2%   |
| SDDM    | 87        | 12.24%  |
| GDM     | 83        | 11.67%  |
| LightDM | 39        | 5.49%   |
| TDM     | 33        | 4.64%   |
| GDM3    | 33        | 4.64%   |
| KDM     | 5         | 0.7%    |
| XDM     | 1         | 0.14%   |
| LXDM    | 1         | 0.14%   |
| GREETD  | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| es_AR       | 359       | 50.92%  |
| en_US       | 157       | 22.27%  |
| Unknown     | 114       | 16.17%  |
| es_ES       | 41        | 5.82%   |
| es_MX       | 10        | 1.42%   |
| C           | 9         | 1.28%   |
| en_GB       | 6         | 0.85%   |
| pt_BR       | 3         | 0.43%   |
| POSIX       | 1         | 0.14%   |
| fr_FR       | 1         | 0.14%   |
| es_US       | 1         | 0.14%   |
| es_CL       | 1         | 0.14%   |
| es_AR.UtF-8 | 1         | 0.14%   |
| en_CA       | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 370       | 52.63%  |
| EFI  | 333       | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 561       | 79.57%  |
| Overlay | 66        | 9.36%   |
| Btrfs   | 37        | 5.25%   |
| Unknown | 31        | 4.4%    |
| Xfs     | 5         | 0.71%   |
| Ext2    | 3         | 0.43%   |
| Zfs     | 1         | 0.14%   |
| Aufs    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 458       | 65.24%  |
| GPT     | 170       | 24.22%  |
| MBR     | 74        | 10.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 624       | 89.27%  |
| Yes       | 75        | 10.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 502       | 72.13%  |
| Yes       | 194       | 27.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 141       | 20.38%  |
| Hewlett-Packard            | 105       | 15.17%  |
| Dell                       | 94        | 13.58%  |
| ASUSTek Computer           | 83        | 11.99%  |
| Acer                       | 36        | 5.2%    |
| Toshiba                    | 26        | 3.76%   |
| BANGHO                     | 26        | 3.76%   |
| Samsung Electronics        | 23        | 3.32%   |
| Exo                        | 19        | 2.75%   |
| Positivo                   | 18        | 2.6%    |
| Sony                       | 15        | 2.17%   |
| Apple                      | 11        | 1.59%   |
| MSI                        | 10        | 1.45%   |
| Intel                      | 8         | 1.16%   |
| Compal                     | 8         | 1.16%   |
| Clevo                      | 6         | 0.87%   |
| NOBLEX                     | 5         | 0.72%   |
| Standard                   | 4         | 0.58%   |
| HUAWEI                     | 4         | 0.58%   |
| Coradir                    | 4         | 0.58%   |
| Advantec                   | 4         | 0.58%   |
| System76                   | 3         | 0.43%   |
| Radio Victoria Fueguina    | 2         | 0.29%   |
| Quanta                     | 2         | 0.29%   |
| Packard Bell               | 2         | 0.29%   |
| NSX                        | 2         | 0.29%   |
| Gigabyte Technology        | 2         | 0.29%   |
| Garbarino SAIC             | 2         | 0.29%   |
| Unknown                    | 2         | 0.29%   |
| Pegatron                   | 1         | 0.14%   |
| PEAQ                       | 1         | 0.14%   |
| PCBOX                      | 1         | 0.14%   |
| Olivetti                   | 1         | 0.14%   |
| Olidata                    | 1         | 0.14%   |
| Notebook                   | 1         | 0.14%   |
| LG Electronics             | 1         | 0.14%   |
| Kelyx Argentina            | 1         | 0.14%   |
| Kanji                      | 1         | 0.14%   |
| Juana Manso                | 1         | 0.14%   |
| Insyde                     | 1         | 0.14%   |
| IBM                        | 1         | 0.14%   |
| HONOR                      | 1         | 0.14%   |
| HDC High Designed Computer | 1         | 0.14%   |
| Gateway                    | 1         | 0.14%   |
| Gadnic                     | 1         | 0.14%   |
| Fujitsu Siemens            | 1         | 0.14%   |
| ECS                        | 1         | 0.14%   |
| Compaq                     | 1         | 0.14%   |
| CEVEN                      | 1         | 0.14%   |
| BGH e-Nova                 | 1         | 0.14%   |
| BGH                        | 1         | 0.14%   |
| ASHI                       | 1         | 0.14%   |
| ADMIRAL                    | 1         | 0.14%   |
| A-DATA Technology          | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 14        | 2.02%   |
| BANGHO MOV                                        | 8         | 1.16%   |
| Lenovo V330-15IKB 81AX                            | 7         | 1.01%   |
| Lenovo ThinkPad L15 Gen 2 20X4S27200              | 6         | 0.87%   |
| HP Laptop 15-bs0xx                                | 6         | 0.87%   |
| HP Pavilion dv6                                   | 5         | 0.72%   |
| HP Notebook                                       | 5         | 0.72%   |
| Exo CloudbookE15                                  | 5         | 0.72%   |
| Dell Inspiron 1525                                | 5         | 0.72%   |
| BANGHO MAX G0101                                  | 5         | 0.72%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA            | 5         | 0.72%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR              | 5         | 0.72%   |
| Lenovo IdeaPad 320-15ABR 80XS                     | 4         | 0.58%   |
| HP Pavilion Notebook                              | 4         | 0.58%   |
| HP 250 G6 Notebook PC                             | 4         | 0.58%   |
| Dell Latitude 7490                                | 4         | 0.58%   |
| Dell Inspiron 3421                                | 4         | 0.58%   |
| Coradir Coradir/ES10IS5                           | 4         | 0.58%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA        | 4         | 0.58%   |
| ASUS K53E                                         | 4         | 0.58%   |
| Apple MacBookPro9,2                               | 4         | 0.58%   |
| Samsung 300E4C/300E5C/300E7C                      | 3         | 0.43%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 3         | 0.43%   |
| Samsung 300E4A/300E5A/300E7A                      | 3         | 0.43%   |
| Positivo VJF155F11UAR                             | 3         | 0.43%   |
| NOBLEX SF20BA                                     | 3         | 0.43%   |
| Lenovo ThinkPad T430 2349DS5                      | 3         | 0.43%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 3         | 0.43%   |
| Lenovo G480 20150                                 | 3         | 0.43%   |
| Lenovo G470 20078                                 | 3         | 0.43%   |
| HP G42                                            | 3         | 0.43%   |
| HP Compaq Presario C700                           | 3         | 0.43%   |
| HP 250 G7 Notebook PC                             | 3         | 0.43%   |
| Dell Latitude E6410                               | 3         | 0.43%   |
| Dell Latitude 7400                                | 3         | 0.43%   |
| Dell Latitude 5510                                | 3         | 0.43%   |
| Dell Inspiron M5030                               | 3         | 0.43%   |
| Dell Inspiron 5559                                | 3         | 0.43%   |
| Dell Inspiron 3505                                | 3         | 0.43%   |
| BANGHO W240HU/W250HUQ                             | 3         | 0.43%   |
| ASUS X541UAK                                      | 3         | 0.43%   |
| ASUS X541NA                                       | 3         | 0.43%   |
| ASUS UX303UB                                      | 3         | 0.43%   |
| Acer Aspire 2930Z                                 | 3         | 0.43%   |
| Toshiba Satellite_C50-A                           | 2         | 0.29%   |
| Toshiba Satellite-L845                            | 2         | 0.29%   |
| Standard MT40II                                   | 2         | 0.29%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 2         | 0.29%   |
| Samsung R430/P430/R480                            | 2         | 0.29%   |
| Positivo Z100                                     | 2         | 0.29%   |
| Positivo SW6H                                     | 2         | 0.29%   |
| Lenovo V330-14ARR 81B1                            | 2         | 0.29%   |
| Lenovo ThinkPad E15 Gen 2 20T9S0B500              | 2         | 0.29%   |
| Lenovo IdeaPad S145-15AST 81N3                    | 2         | 0.29%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 2         | 0.29%   |
| Lenovo IdeaPad 3 14ADA05 81W0                     | 2         | 0.29%   |
| Lenovo G580 20150                                 | 2         | 0.29%   |
| Lenovo G550 2958                                  | 2         | 0.29%   |
| Lenovo G40-80 80E4                                | 2         | 0.29%   |
| Lenovo G40-30 80FY                                | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 56        | 8.09%   |
| Lenovo ThinkPad        | 53        | 7.66%   |
| Acer Aspire            | 33        | 4.77%   |
| HP Pavilion            | 32        | 4.62%   |
| Dell Latitude          | 30        | 4.34%   |
| Lenovo IdeaPad         | 29        | 4.19%   |
| ASUS VivoBook          | 26        | 3.76%   |
| HP Laptop              | 18        | 2.6%    |
| Toshiba Satellite      | 15        | 2.17%   |
| Unknown                | 14        | 2.02%   |
| HP 250                 | 9         | 1.3%    |
| BANGHO MAX             | 9         | 1.3%    |
| HP Compaq              | 8         | 1.16%   |
| BANGHO MOV             | 8         | 1.16%   |
| Lenovo V330-15IKB      | 7         | 1.01%   |
| Samsung 300E4A         | 6         | 0.87%   |
| HP ProBook             | 6         | 0.87%   |
| Lenovo ThinkBook       | 5         | 0.72%   |
| HP Notebook            | 5         | 0.72%   |
| HP EliteBook           | 5         | 0.72%   |
| Exo Smart              | 5         | 0.72%   |
| Exo CloudbookE15       | 5         | 0.72%   |
| Samsung R430           | 4         | 0.58%   |
| HP ENVY                | 4         | 0.58%   |
| Coradir Coradir        | 4         | 0.58%   |
| ASUS K53E              | 4         | 0.58%   |
| ASUS ASUS              | 4         | 0.58%   |
| Apple MacBookPro9      | 4         | 0.58%   |
| Toshiba PORTEGE        | 3         | 0.43%   |
| Samsung 300E4C         | 3         | 0.43%   |
| Positivo VJF155F11UAR  | 3         | 0.43%   |
| NOBLEX SF20BA          | 3         | 0.43%   |
| Lenovo G480            | 3         | 0.43%   |
| Lenovo G470            | 3         | 0.43%   |
| HP G42                 | 3         | 0.43%   |
| HP 15                  | 3         | 0.43%   |
| Dell XPS               | 3         | 0.43%   |
| Dell Studio            | 3         | 0.43%   |
| BANGHO W240HU          | 3         | 0.43%   |
| ASUS X541UAK           | 3         | 0.43%   |
| ASUS X541NA            | 3         | 0.43%   |
| ASUS UX303UB           | 3         | 0.43%   |
| Toshiba Satellite-L845 | 2         | 0.29%   |
| Standard MT40II        | 2         | 0.29%   |
| Samsung RV420          | 2         | 0.29%   |
| Positivo Z100          | 2         | 0.29%   |
| Positivo SW6H          | 2         | 0.29%   |
| Packard Bell EasyNote  | 2         | 0.29%   |
| Lenovo Yoga            | 2         | 0.29%   |
| Lenovo V330-14ARR      | 2         | 0.29%   |
| Lenovo G580            | 2         | 0.29%   |
| Lenovo G550            | 2         | 0.29%   |
| Lenovo G50-80          | 2         | 0.29%   |
| Lenovo G40-80          | 2         | 0.29%   |
| Lenovo G40-30          | 2         | 0.29%   |
| Lenovo Edge            | 2         | 0.29%   |
| Lenovo BP              | 2         | 0.29%   |
| Lenovo 3000            | 2         | 0.29%   |
| Intel powered          | 2         | 0.29%   |
| Intel HR14             | 2         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2017    | 81        | 11.71%  |
| 2012    | 76        | 10.98%  |
| 2011    | 59        | 8.53%   |
| 2019    | 58        | 8.38%   |
| 2010    | 47        | 6.79%   |
| 2020    | 46        | 6.65%   |
| 2014    | 46        | 6.65%   |
| 2018    | 45        | 6.5%    |
| 2016    | 42        | 6.07%   |
| 2015    | 39        | 5.64%   |
| 2013    | 39        | 5.64%   |
| 2008    | 34        | 4.91%   |
| 2021    | 29        | 4.19%   |
| 2009    | 20        | 2.89%   |
| 2007    | 15        | 2.17%   |
| 2006    | 8         | 1.16%   |
| Unknown | 6         | 0.87%   |
| 2005    | 1         | 0.14%   |
| 2004    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 692       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 628       | 90.49%  |
| Enabled  | 66        | 9.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 691       | 99.86%  |
| Yes  | 1         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 192       | 27.59%  |
| 4.01-8.0    | 188       | 27.01%  |
| 8.01-16.0   | 125       | 17.96%  |
| 1.01-2.0    | 74        | 10.63%  |
| 16.01-24.0  | 59        | 8.48%   |
| 2.01-3.0    | 19        | 2.73%   |
| 32.01-64.0  | 18        | 2.59%   |
| 0.51-1.0    | 14        | 2.01%   |
| 24.01-32.0  | 5         | 0.72%   |
| 64.01-256.0 | 2         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 293       | 39.17%  |
| 2.01-3.0   | 173       | 23.13%  |
| 3.01-4.0   | 86        | 11.5%   |
| 4.01-8.0   | 83        | 11.1%   |
| 0.51-1.0   | 77        | 10.29%  |
| 8.01-16.0  | 24        | 3.21%   |
| 0.01-0.5   | 10        | 1.34%   |
| 16.01-24.0 | 2         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 531       | 75.75%  |
| 2      | 147       | 20.97%  |
| 3      | 15        | 2.14%   |
| 0      | 8         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 406       | 58.33%  |
| Yes       | 290       | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 590       | 85.14%  |
| No        | 103       | 14.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 677       | 97.83%  |
| No        | 15        | 2.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 468       | 67.44%  |
| No        | 226       | 32.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Argentina | 692       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 171       | 23.59%  |
| Córdoba                    | 51        | 7.03%   |
| Rosario                     | 22        | 3.03%   |
| Mar del Plata               | 22        | 3.03%   |
| La Plata                    | 21        | 2.9%    |
| Mendoza                     | 11        | 1.52%   |
| San Martín de los Andes    | 9         | 1.24%   |
| Lanus                       | 9         | 1.24%   |
| Tandil                      | 7         | 0.97%   |
| Santa Fe                    | 7         | 0.97%   |
| Salta                       | 7         | 0.97%   |
| Resistencia                 | 7         | 0.97%   |
| Ramos Mejia                 | 7         | 0.97%   |
| Olivos                      | 7         | 0.97%   |
| Bariloche                   | 7         | 0.97%   |
| San Miguel de Tucumán      | 6         | 0.83%   |
| Posadas                     | 6         | 0.83%   |
| Lomas de Zamora             | 6         | 0.83%   |
| Ituzaingo                   | 6         | 0.83%   |
| Florencio Varela            | 6         | 0.83%   |
| Corrientes                  | 6         | 0.83%   |
| Avellaneda                  | 6         | 0.83%   |
| Villa Ballester             | 5         | 0.69%   |
| Vicente Lopez               | 5         | 0.69%   |
| San Nicolás de los Arroyos | 5         | 0.69%   |
| San Juan                    | 5         | 0.69%   |
| San Francisco               | 5         | 0.69%   |
| Rio Tercero                 | 5         | 0.69%   |
| Río Gallegos               | 5         | 0.69%   |
| Quilmes                     | 5         | 0.69%   |
| Mariano Moreno              | 5         | 0.69%   |
| Bahía Blanca               | 5         | 0.69%   |
| Villa Carlos Paz            | 4         | 0.55%   |
| Villa Allende               | 4         | 0.55%   |
| San Telmo                   | 4         | 0.55%   |
| San Isidro                  | 4         | 0.55%   |
| Rafaela                     | 4         | 0.55%   |
| Paraná                     | 4         | 0.55%   |
| Necochea                    | 4         | 0.55%   |
| Longchamps                  | 4         | 0.55%   |
| Haedo                       | 4         | 0.55%   |
| Godoy Cruz                  | 4         | 0.55%   |
| Yerba Buena                 | 3         | 0.41%   |
| Villa María                | 3         | 0.41%   |
| Viedma                      | 3         | 0.41%   |
| Santa Rosa                  | 3         | 0.41%   |
| San Luis                    | 3         | 0.41%   |
| Saenz Pena                  | 3         | 0.41%   |
| Neuquén                    | 3         | 0.41%   |
| La Rioja                    | 3         | 0.41%   |
| General San Martin          | 3         | 0.41%   |
| Comodoro Rivadavia          | 3         | 0.41%   |
| Caseros                     | 3         | 0.41%   |
| Burzaco                     | 3         | 0.41%   |
| Berisso                     | 3         | 0.41%   |
| Beccar                      | 3         | 0.41%   |
| Villa Regina                | 2         | 0.28%   |
| Villa Nueva                 | 2         | 0.28%   |
| Villa Adelina               | 2         | 0.28%   |
| Tunuyan                     | 2         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 164       | 196    | 20.27%  |
| Seagate                     | 122       | 141    | 15.08%  |
| Kingston                    | 106       | 128    | 13.1%   |
| Toshiba                     | 105       | 135    | 12.98%  |
| Samsung Electronics         | 65        | 83     | 8.03%   |
| Unknown                     | 38        | 49     | 4.7%    |
| HGST                        | 33        | 35     | 4.08%   |
| Hitachi                     | 28        | 30     | 3.46%   |
| SK hynix                    | 26        | 28     | 3.21%   |
| SanDisk                     | 20        | 27     | 2.47%   |
| A-DATA Technology           | 13        | 14     | 1.61%   |
| Crucial                     | 11        | 14     | 1.36%   |
| Micron Technology           | 8         | 10     | 0.99%   |
| Intel                       | 7         | 21     | 0.87%   |
| Gigabyte Technology         | 7         | 10     | 0.87%   |
| KIOXIA                      | 6         | 6      | 0.74%   |
| Hewlett-Packard             | 4         | 4      | 0.49%   |
| Patriot                     | 3         | 4      | 0.37%   |
| Apple                       | 3         | 3      | 0.37%   |
| XPG                         | 2         | 2      | 0.25%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.25%   |
| Union Memory                | 2         | 2      | 0.25%   |
| SPCC                        | 2         | 2      | 0.25%   |
| Realtek Semiconductor       | 2         | 2      | 0.25%   |
| PNY                         | 2         | 4      | 0.25%   |
| Neo                         | 2         | 2      | 0.25%   |
| Corsair                     | 2         | 2      | 0.25%   |
| Colorful                    | 2         | 2      | 0.25%   |
| China                       | 2         | 2      | 0.25%   |
| ZTE                         | 1         | 1      | 0.12%   |
| XrayDisk                    | 1         | 1      | 0.12%   |
| WDC WDS2                    | 1         | 1      | 0.12%   |
| USB3.0                      | 1         | 1      | 0.12%   |
| Transcend                   | 1         | 1      | 0.12%   |
| Team                        | 1         | 1      | 0.12%   |
| SMI                         | 1         | 1      | 0.12%   |
| Silicon Motion              | 1         | 1      | 0.12%   |
| OCZ                         | 1         | 1      | 0.12%   |
| NGFF                        | 1         | 2      | 0.12%   |
| Micron/Crucial Technology   | 1         | 1      | 0.12%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.12%   |
| LITEONIT                    | 1         | 1      | 0.12%   |
| LITEON                      | 1         | 1      | 0.12%   |
| Lexar                       | 1         | 1      | 0.12%   |
| HS-SSD-C100                 | 1         | 1      | 0.12%   |
| Hikvision                   | 1         | 1      | 0.12%   |
| FORESEE                     | 1         | 1      | 0.12%   |
| BIWIN                       | 1         | 2      | 0.12%   |
| Unknown                     | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD       | 40        | 4.82%   |
| Seagate ST1000LM035-1RK172 1TB        | 32        | 3.86%   |
| Toshiba MQ01ABD100 1TB                | 23        | 2.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 21        | 2.53%   |
| Toshiba MQ01ABF050 500GB              | 19        | 2.29%   |
| Kingston SA400S37480G 480GB SSD       | 18        | 2.17%   |
| Unknown MMC Card  32GB                | 15        | 1.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 13        | 1.57%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 9         | 1.08%   |
| WDC WD10JPVX-60JC3T1 1TB              | 9         | 1.08%   |
| Toshiba MQ04ABF100 1TB                | 9         | 1.08%   |
| Seagate ST500LT012-1DG142 500GB       | 9         | 1.08%   |
| Kingston SA400S37120G 120GB SSD       | 8         | 0.96%   |
| Seagate ST9500325AS 500GB             | 7         | 0.84%   |
| HGST HTS721010A9E630 1TB              | 7         | 0.84%   |
| Toshiba MQ01ABD032 320GB              | 6         | 0.72%   |
| Samsung NVMe SSD Drive 512GB          | 6         | 0.72%   |
| Kingston SV300S37A240G 240GB SSD      | 6         | 0.72%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 5         | 0.6%    |
| Toshiba MK6475GSX 640GB               | 5         | 0.6%    |
| Seagate ST500LT012-9WS142 500GB       | 5         | 0.6%    |
| Seagate ST500LM030-2E717D 500GB       | 5         | 0.6%    |
| Seagate ST320LM001 HN-M320MBB 320GB   | 5         | 0.6%    |
| Seagate ST1000LM048-2E7172 1TB        | 5         | 0.6%    |
| Kingston SUV400S37240G 240GB SSD      | 5         | 0.6%    |
| HGST HTS725050A7E630 500GB            | 5         | 0.6%    |
| HGST HTS545050A7E680 500GB            | 5         | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 4         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 4         | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 4         | 0.48%   |
| WDC WD1600BEVT-22A23T0 160GB          | 4         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB              | 4         | 0.48%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 4         | 0.48%   |
| SK hynix NVMe SSD Drive 512GB         | 4         | 0.48%   |
| SK hynix NVMe SSD Drive 256GB         | 4         | 0.48%   |
| Samsung HM250HI 250GB                 | 4         | 0.48%   |
| Hitachi HTS545050B9A300 500GB         | 4         | 0.48%   |
| HGST HTS545050A7E380 500GB            | 4         | 0.48%   |
| HGST HTS541010A9E680 1TB              | 4         | 0.48%   |
| A-DATA SU630 240GB SSD                | 4         | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 3         | 0.36%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 3         | 0.36%   |
| WDC WD5000LPCX-22VHAT0 500GB          | 3         | 0.36%   |
| WDC WD2500BEVT-22A23T0 250GB          | 3         | 0.36%   |
| WDC WD10SPZX-60Z10T1 1TB              | 3         | 0.36%   |
| WDC WD10JPVX-60JC3T0 1TB              | 3         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB              | 3         | 0.36%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 0.36%   |
| Unknown SD/MMC/MS PRO 128GB           | 3         | 0.36%   |
| Unknown MMC Card  64GB                | 3         | 0.36%   |
| Unknown MMC Card  1GB                 | 3         | 0.36%   |
| Toshiba MQ01ABD050 500GB              | 3         | 0.36%   |
| Toshiba MK3275GSX 320GB               | 3         | 0.36%   |
| Toshiba MK1665GSX 160GB               | 3         | 0.36%   |
| SK hynix HFS512G32MND-3210A 512GB SSD | 3         | 0.36%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 0.36%   |
| KIOXIA KBG40ZNS256G NVMe 256GB        | 3         | 0.36%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 0.36%   |
| Kingston SA400S37960G 960GB SSD       | 3         | 0.36%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 120       | 135    | 28.85%  |
| Seagate             | 120       | 138    | 28.85%  |
| Toshiba             | 92        | 120    | 22.12%  |
| HGST                | 33        | 35     | 7.93%   |
| Hitachi             | 28        | 30     | 6.73%   |
| Samsung Electronics | 20        | 23     | 4.81%   |
| Unknown             | 3         | 3      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 97        | 117    | 39.27%  |
| WDC                 | 38        | 46     | 15.38%  |
| Samsung Electronics | 20        | 33     | 8.1%    |
| SanDisk             | 12        | 17     | 4.86%   |
| Crucial             | 11        | 14     | 4.45%   |
| A-DATA Technology   | 11        | 11     | 4.45%   |
| SK hynix            | 7         | 8      | 2.83%   |
| Gigabyte Technology | 7         | 10     | 2.83%   |
| Toshiba             | 5         | 5      | 2.02%   |
| Micron Technology   | 4         | 5      | 1.62%   |
| Patriot             | 3         | 4      | 1.21%   |
| Intel               | 3         | 3      | 1.21%   |
| SPCC                | 2         | 2      | 0.81%   |
| Seagate             | 2         | 3      | 0.81%   |
| PNY                 | 2         | 4      | 0.81%   |
| Hewlett-Packard     | 2         | 3      | 0.81%   |
| Corsair             | 2         | 2      | 0.81%   |
| Colorful            | 2         | 2      | 0.81%   |
| Apple               | 2         | 2      | 0.81%   |
| XrayDisk            | 1         | 1      | 0.4%    |
| WDC WDS2            | 1         | 1      | 0.4%    |
| USB3.0              | 1         | 1      | 0.4%    |
| Transcend           | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| SMI                 | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| NGFF                | 1         | 2      | 0.4%    |
| Neo                 | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| Lexar               | 1         | 1      | 0.4%    |
| HS-SSD-C100         | 1         | 1      | 0.4%    |
| FORESEE             | 1         | 1      | 0.4%    |
| China               | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 408       | 484    | 51.84%  |
| SSD     | 236       | 307    | 29.99%  |
| NVMe    | 103       | 140    | 13.09%  |
| MMC     | 35        | 47     | 4.45%   |
| Unknown | 5         | 4      | 0.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 582       | 787    | 79.95%  |
| NVMe | 103       | 140    | 14.15%  |
| MMC  | 35        | 47     | 4.81%   |
| SAS  | 8         | 8      | 1.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 423       | 530    | 67.79%  |
| 0.51-1.0   | 195       | 253    | 31.25%  |
| 1.01-2.0   | 6         | 8      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 227       | 31.48%  |
| 251-500        | 186       | 25.8%   |
| 501-1000       | 119       | 16.5%   |
| 1-20           | 42        | 5.83%   |
| 51-100         | 42        | 5.83%   |
| 21-50          | 39        | 5.41%   |
| 1001-2000      | 39        | 5.41%   |
| Unknown        | 20        | 2.77%   |
| More than 3000 | 4         | 0.55%   |
| 2001-3000      | 3         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 301       | 40.35%  |
| 21-50     | 144       | 19.3%   |
| 101-250   | 104       | 13.94%  |
| 51-100    | 92        | 12.33%  |
| 251-500   | 51        | 6.84%   |
| 501-1000  | 25        | 3.35%   |
| Unknown   | 20        | 2.68%   |
| 1001-2000 | 7         | 0.94%   |
| 2001-3000 | 2         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-22HXZT3 500GB                     | 3         | 3      | 5.88%   |
| Toshiba MQ01ABD100 1TB                           | 3         | 5      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                   | 3         | 3      | 5.88%   |
| HGST HTS541010A9E680 1TB                         | 3         | 3      | 5.88%   |
| Toshiba MK1665GSX 160GB                          | 2         | 2      | 3.92%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 3.92%   |
| Kingston SA400S37240G 240GB SSD                  | 2         | 2      | 3.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                 | 1         | 1      | 1.96%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                 | 1         | 1      | 1.96%   |
| WDC WD3200BPVT-00JJ5T0 320GB                     | 1         | 1      | 1.96%   |
| WDC WD2500BEVT-75A23T0 250GB                     | 1         | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 1.96%   |
| Toshiba MK7559GSXP 752GB                         | 1         | 1      | 1.96%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 1.96%   |
| Toshiba MK2576GSX 250GB                          | 1         | 1      | 1.96%   |
| SMI SSD DISK 512GB                               | 1         | 1      | 1.96%   |
| Seagate ST960813AS 64GB                          | 1         | 1      | 1.96%   |
| Seagate ST960812A 64GB                           | 1         | 1      | 1.96%   |
| Seagate ST9160314AS 160GB                        | 1         | 1      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 3      | 1.96%   |
| Seagate ST250LM004 HN-M250MBB 250GB              | 1         | 1      | 1.96%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 840 EVO 250GB            | 1         | 1      | 1.96%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD | 1         | 1      | 1.96%   |
| Samsung Electronics HN-M101MBB 1TB               | 1         | 1      | 1.96%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.96%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 1.96%   |
| Hitachi HTS727575A9E364 752GB                    | 1         | 1      | 1.96%   |
| Hitachi HTS547564A9E384 640GB                    | 1         | 1      | 1.96%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 1.96%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 1.96%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 1.96%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 1.96%   |
| HGST HTS721010A9E630 1TB                         | 1         | 2      | 1.96%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 1.96%   |
| A-DATA Technology XM12 32GB SSD                  | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 25.49%  |
| Toshiba             | 11        | 13     | 21.57%  |
| WDC                 | 7         | 7      | 13.73%  |
| HGST                | 6         | 7      | 11.76%  |
| Hitachi             | 5         | 5      | 9.8%    |
| Samsung Electronics | 4         | 4      | 7.84%   |
| Kingston            | 3         | 3      | 5.88%   |
| SMI                 | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 30.95%  |
| Toshiba             | 11        | 13     | 26.19%  |
| HGST                | 6         | 7      | 14.29%  |
| WDC                 | 5         | 5      | 11.9%   |
| Hitachi             | 5         | 5      | 11.9%   |
| Samsung Electronics | 2         | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 47     | 82%     |
| SSD  | 9         | 9      | 18%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB | 2         | 2      | 50%     |
| Toshiba MK6475GSX 640GB     | 1         | 1      | 25%     |
| Toshiba MK1665GSX 160GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Toshiba | 2         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 456       | 625    | 63.6%   |
| Works    | 208       | 297    | 29.01%  |
| Malfunc  | 49        | 56     | 6.83%   |
| Failed   | 4         | 4      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 538       | 73.6%   |
| AMD                              | 74        | 10.12%  |
| Samsung Electronics              | 26        | 3.56%   |
| SK hynix                         | 19        | 2.6%    |
| SanDisk                          | 17        | 2.33%   |
| Silicon Integrated Systems [SiS] | 10        | 1.37%   |
| Toshiba America Info Systems     | 9         | 1.23%   |
| Kingston Technology Company      | 9         | 1.23%   |
| KIOXIA                           | 7         | 0.96%   |
| Realtek Semiconductor            | 4         | 0.55%   |
| Micron Technology                | 4         | 0.55%   |
| Union Memory (Shenzhen)          | 3         | 0.41%   |
| VIA Technologies                 | 2         | 0.27%   |
| Silicon Motion                   | 2         | 0.27%   |
| Nvidia                           | 1         | 0.14%   |
| Micron/Crucial Technology        | 1         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.14%   |
| Marvell Technology Group         | 1         | 0.14%   |
| Biwin Storage Technology         | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |
| ADATA Technology                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 94        | 11.91%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 78        | 9.89%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 59        | 7.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 42        | 5.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 41        | 5.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 26        | 3.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 21        | 2.66%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 21        | 2.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 21        | 2.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 21        | 2.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 15        | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 15        | 1.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 14        | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 14        | 1.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 1.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 13        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 13        | 1.65%   |
| Samsung NVMe SSD Controller 980                                                        | 12        | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 11        | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 1.39%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 10        | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 9         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 9         | 1.14%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 8         | 1.01%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 8         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 7         | 0.89%   |
| KIOXIA Non-Volatile memory controller                                                  | 7         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 7         | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 7         | 0.89%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 7         | 0.89%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 7         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 6         | 0.76%   |
| SanDisk Non-Volatile memory controller                                                 | 6         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 6         | 0.76%   |
| SK hynix Gold P31 SSD                                                                  | 5         | 0.63%   |
| SK hynix BC511                                                                         | 5         | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                        | 5         | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 0.63%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 5         | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 4         | 0.51%   |
| Micron Non-Volatile memory controller                                                  | 4         | 0.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 4         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 4         | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.51%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.51%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 3         | 0.38%   |
| SK hynix Non-Volatile memory controller                                                | 3         | 0.38%   |
| Intel Non-Volatile memory controller                                                   | 3         | 0.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 0.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 0.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 3         | 0.38%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 3         | 0.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 0.38%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 2         | 0.25%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 2         | 0.25%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 2         | 0.25%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                            | 2         | 0.25%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 531       | 70.33%  |
| NVMe | 104       | 13.77%  |
| IDE  | 72        | 9.54%   |
| RAID | 48        | 6.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 602       | 86.99%  |
| AMD    | 90        | 13.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz               | 21        | 3.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 14        | 2.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 14        | 2.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 14        | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 13        | 1.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 13        | 1.88%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 12        | 1.73%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 12        | 1.73%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 12        | 1.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 11        | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 10        | 1.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 10        | 1.45%   |
| Intel Atom CPU N2600 @ 1.60GHz                  | 10        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 8         | 1.16%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 8         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 8         | 1.16%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 8         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 7         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 7         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 7         | 1.01%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 7         | 1.01%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 7         | 1.01%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 7         | 1.01%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 7         | 1.01%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 6         | 0.87%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 6         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 6         | 0.87%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 6         | 0.87%   |
| Intel Core i3-2370M CPU @ 2.40GHz               | 6         | 0.87%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 0.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 6         | 0.87%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 6         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 0.87%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 5         | 0.72%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 5         | 0.72%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 5         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 5         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 5         | 0.72%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 5         | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 5         | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 0.72%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 5         | 0.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 5         | 0.72%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 5         | 0.72%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 5         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 5         | 0.72%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 5         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 4         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 4         | 0.58%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 4         | 0.58%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz            | 4         | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 4         | 0.58%   |
| AMD A6-4400M APU with Radeon HD Graphics        | 4         | 0.58%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz          | 3         | 0.43%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 3         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 0.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 3         | 0.43%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 3         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 174       | 25.14%  |
| Intel Core i7           | 120       | 17.34%  |
| Intel Core i3           | 91        | 13.15%  |
| Intel Celeron           | 60        | 8.67%   |
| Intel Atom              | 42        | 6.07%   |
| Other                   | 24        | 3.47%   |
| Intel Pentium           | 24        | 3.47%   |
| Intel Core 2 Duo        | 22        | 3.18%   |
| AMD Ryzen 5             | 22        | 3.18%   |
| Intel Pentium Dual-Core | 16        | 2.31%   |
| Intel Pentium Dual      | 13        | 1.88%   |
| AMD Ryzen 7             | 11        | 1.59%   |
| Intel Genuine           | 9         | 1.3%    |
| AMD A6                  | 9         | 1.3%    |
| AMD A10                 | 6         | 0.87%   |
| Intel Core 2            | 5         | 0.72%   |
| AMD Athlon II           | 5         | 0.72%   |
| AMD A8                  | 5         | 0.72%   |
| AMD A12                 | 5         | 0.72%   |
| AMD Ryzen 3             | 3         | 0.43%   |
| AMD A4                  | 3         | 0.43%   |
| Intel Pentium M         | 2         | 0.29%   |
| Intel Celeron M         | 2         | 0.29%   |
| AMD Ryzen 7 PRO         | 2         | 0.29%   |
| AMD E                   | 2         | 0.29%   |
| AMD C-70                | 2         | 0.29%   |
| AMD Athlon              | 2         | 0.29%   |
| Intel Core Duo          | 1         | 0.14%   |
| Intel Celeron Dual-Core | 1         | 0.14%   |
| AMD Z                   | 1         | 0.14%   |
| AMD V120                | 1         | 0.14%   |
| AMD Turion 64 Mobile    | 1         | 0.14%   |
| AMD Ryzen 9             | 1         | 0.14%   |
| AMD Phenom II           | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |
| AMD E1                  | 1         | 0.14%   |
| AMD C-60                | 1         | 0.14%   |
| AMD Athlon X2           | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 449       | 64.88%  |
| 4       | 180       | 26.01%  |
| 1       | 36        | 5.2%    |
| 8       | 13        | 1.88%   |
| 6       | 11        | 1.59%   |
| Unknown | 2         | 0.29%   |
| 3       | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 691       | 99.86%  |
| Unknown | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 472       | 68.21%  |
| 1       | 218       | 31.5%   |
| Unknown | 2         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 662       | 95.25%  |
| Unknown        | 15        | 2.16%   |
| 32-bit         | 14        | 2.01%   |
| 64-bit         | 4         | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 14.75%  |
| 0x306a9    | 61        | 8.57%   |
| 0x206a7    | 61        | 8.57%   |
| 0x806e9    | 38        | 5.34%   |
| 0x406e3    | 29        | 4.07%   |
| 0x806ec    | 27        | 3.79%   |
| 0x1067a    | 26        | 3.65%   |
| 0x306d4    | 23        | 3.23%   |
| 0x6fd      | 21        | 2.95%   |
| 0x20655    | 20        | 2.81%   |
| 0x806ea    | 19        | 2.67%   |
| 0x40651    | 19        | 2.67%   |
| 0x406c4    | 18        | 2.53%   |
| 0x706e5    | 15        | 2.11%   |
| 0x806c1    | 13        | 1.83%   |
| 0x106ca    | 13        | 1.83%   |
| 0x706a1    | 12        | 1.69%   |
| 0x506c9    | 12        | 1.69%   |
| 0x30678    | 12        | 1.69%   |
| 0x306c3    | 11        | 1.54%   |
| 0x30661    | 10        | 1.4%    |
| 0x08108109 | 7         | 0.98%   |
| 0x06006705 | 7         | 0.98%   |
| 0x6e8      | 6         | 0.84%   |
| 0x20652    | 6         | 0.84%   |
| 0x0810100b | 6         | 0.84%   |
| 0x906ea    | 5         | 0.7%    |
| 0x906e9    | 5         | 0.7%    |
| 0x10661    | 5         | 0.7%    |
| 0x08600104 | 5         | 0.7%    |
| 0x08108102 | 5         | 0.7%    |
| 0x06006118 | 5         | 0.7%    |
| 0x06001119 | 5         | 0.7%    |
| 0xa0652    | 4         | 0.56%   |
| 0x506e3    | 4         | 0.56%   |
| 0x406c3    | 4         | 0.56%   |
| 0x08608103 | 4         | 0.56%   |
| 0x05000119 | 4         | 0.56%   |
| 0x010000c8 | 4         | 0.56%   |
| 0x806eb    | 3         | 0.42%   |
| 0x706a8    | 3         | 0.42%   |
| 0x6f6      | 3         | 0.42%   |
| 0x106e5    | 3         | 0.42%   |
| 0x106c2    | 3         | 0.42%   |
| 0x08101007 | 3         | 0.42%   |
| 0x07030105 | 3         | 0.42%   |
| 0x6ec      | 2         | 0.28%   |
| 0x6d8      | 2         | 0.28%   |
| 0x10676    | 2         | 0.28%   |
| 0x0a50000c | 2         | 0.28%   |
| 0x08600106 | 2         | 0.28%   |
| 0x08600103 | 2         | 0.28%   |
| 0x03000027 | 2         | 0.28%   |
| 0xa0660    | 1         | 0.14%   |
| 0x6fb      | 1         | 0.14%   |
| 0x6fa      | 1         | 0.14%   |
| 0x6f2      | 1         | 0.14%   |
| 0x695      | 1         | 0.14%   |
| 0x306a8    | 1         | 0.14%   |
| 0x0a50000b | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 118       | 17.05%  |
| IvyBridge       | 68        | 9.83%   |
| SandyBridge     | 67        | 9.68%   |
| Skylake         | 44        | 6.36%   |
| Silvermont      | 39        | 5.64%   |
| Haswell         | 35        | 5.06%   |
| Core            | 35        | 5.06%   |
| Penryn          | 30        | 4.34%   |
| Westmere        | 27        | 3.9%    |
| Bonnell         | 26        | 3.76%   |
| Broadwell       | 23        | 3.32%   |
| TigerLake       | 19        | 2.75%   |
| IceLake         | 19        | 2.75%   |
| Goldmont plus   | 17        | 2.46%   |
| Excavator       | 15        | 2.17%   |
| Zen+            | 13        | 1.88%   |
| Goldmont        | 13        | 1.88%   |
| P6              | 11        | 1.59%   |
| Zen 2           | 10        | 1.45%   |
| Zen             | 10        | 1.45%   |
| K10             | 7         | 1.01%   |
| Bobcat          | 7         | 1.01%   |
| Piledriver      | 6         | 0.87%   |
| Unknown         | 6         | 0.87%   |
| CometLake       | 5         | 0.72%   |
| Puma            | 4         | 0.58%   |
| Nehalem         | 4         | 0.58%   |
| K10 Llano       | 4         | 0.58%   |
| Zen 3           | 3         | 0.43%   |
| Steamroller     | 2         | 0.29%   |
| K8 & K10 hybrid | 2         | 0.29%   |
| Jaguar          | 2         | 0.29%   |
| K8 Hammer       | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 572       | 72.59%  |
| AMD                              | 120       | 15.23%  |
| Nvidia                           | 84        | 10.66%  |
| Silicon Integrated Systems [SiS] | 10        | 1.27%   |
| VIA Technologies                 | 2         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 66        | 7.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 65        | 7.87%   |
| Intel HD Graphics 620                                                                    | 44        | 5.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 37        | 4.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 3.15%   |
| Intel UHD Graphics 620                                                                   | 25        | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2.66%   |
| Intel HD Graphics 5500                                                                   | 22        | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 2.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 1.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 1.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 16        | 1.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 14        | 1.69%   |
| Intel HD Graphics 500                                                                    | 13        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 1.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 1.33%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 10        | 1.21%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 10        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.09%   |
| AMD Renoir                                                                               | 9         | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.85%   |
| Nvidia GM108M [GeForce 940M]                                                             | 7         | 0.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.73%   |
| Intel HD Graphics 630                                                                    | 6         | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.73%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.48%   |
| Intel HD Graphics 530                                                                    | 4         | 0.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.48%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 4         | 0.48%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.48%   |
| AMD Lucienne                                                                             | 4         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.36%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.36%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.36%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.36%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.36%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.36%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 0.36%   |
| AMD Cezanne                                                                              | 3         | 0.36%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 2         | 0.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.24%   |
| Nvidia TU117M                                                                            | 2         | 0.24%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.24%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.24%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.24%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.24%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 2         | 0.24%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 482       | 69.65%  |
| 1 x AMD        | 82        | 11.85%  |
| Intel + Nvidia | 66        | 9.54%   |
| Intel + AMD    | 24        | 3.47%   |
| 1 x Nvidia     | 12        | 1.73%   |
| 1 x SiS        | 10        | 1.45%   |
| 2 x AMD        | 8         | 1.16%   |
| AMD + Nvidia   | 6         | 0.87%   |
| 1 x VIA        | 2         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 630       | 90.78%  |
| Proprietary | 36        | 5.19%   |
| Unknown     | 28        | 4.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 500       | 70.92%  |
| 1.01-2.0   | 74        | 10.5%   |
| 0.01-0.5   | 71        | 10.07%  |
| 3.01-4.0   | 27        | 3.83%   |
| 0.51-1.0   | 27        | 3.83%   |
| 5.01-6.0   | 4         | 0.57%   |
| 2.01-3.0   | 2         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 135       | 17.86%  |
| Samsung Electronics     | 128       | 16.93%  |
| Chimei Innolux          | 105       | 13.89%  |
| BOE                     | 103       | 13.62%  |
| LG Display              | 94        | 12.43%  |
| InfoVision              | 29        | 3.84%   |
| Goldstar                | 27        | 3.57%   |
| Chi Mei Optoelectronics | 13        | 1.72%   |
| Apple                   | 12        | 1.59%   |
| LG Philips              | 10        | 1.32%   |
| InnoLux Display         | 9         | 1.19%   |
| Lenovo                  | 8         | 1.06%   |
| ViewSonic               | 7         | 0.93%   |
| Philips                 | 7         | 0.93%   |
| HannStar                | 7         | 0.93%   |
| Dell                    | 7         | 0.93%   |
| CPT                     | 7         | 0.93%   |
| PANDA                   | 5         | 0.66%   |
| STA                     | 4         | 0.53%   |
| SKY                     | 4         | 0.53%   |
| Sharp                   | 4         | 0.53%   |
| Hitachi                 | 4         | 0.53%   |
| Hewlett-Packard         | 4         | 0.53%   |
| BenQ                    | 4         | 0.53%   |
| Unknown                 | 2         | 0.26%   |
| MTD                     | 2         | 0.26%   |
| KDC                     | 2         | 0.26%   |
| ASUSTek Computer        | 2         | 0.26%   |
| SNT                     | 1         | 0.13%   |
| SLD                     | 1         | 0.13%   |
| Quanta Display          | 1         | 0.13%   |
| MStar                   | 1         | 0.13%   |
| LPL                     | 1         | 0.13%   |
| JDI                     | 1         | 0.13%   |
| iQual                   | 1         | 0.13%   |
| HKN                     | 1         | 0.13%   |
| GDH                     | 1         | 0.13%   |
| Daewoo                  | 1         | 0.13%   |
| AOC                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 19        | 2.46%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 16        | 2.07%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 13        | 1.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 9         | 1.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 9         | 1.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 8         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 7         | 0.91%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 7         | 0.91%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 6         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.78%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 6         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 5         | 0.65%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.65%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch           | 5         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 5         | 0.65%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.65%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 5         | 0.65%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 5         | 0.65%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 5         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 4         | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.52%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 0.52%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 4         | 0.52%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 4         | 0.52%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 4         | 0.52%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.52%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                  | 3         | 0.39%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3         | 0.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch  | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SDC364A 3200x1800 293x165mm 13.2-inch | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch | 3         | 0.39%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.39%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 3         | 0.39%   |
| CPT LCD Monitor CPT14C7 1366x768 344x194mm 15.5-inch                  | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 3         | 0.39%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                  | 3         | 0.39%   |
| AU Optronics LCD Monitor AUOD98A 1366x768 344x194mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO5B94 1366x768 344x194mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO42EC 1366x768 344x193mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO3714 1280x800 261x163mm 12.1-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO24EC 1366x768 344x193mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 3         | 0.39%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 3         | 0.39%   |
| ViewSonic VG2021wm-2 VSCD91E 1680x1050 433x270mm 20.1-inch            | 2         | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.26%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 2         | 0.26%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch               | 2         | 0.26%   |
| Samsung Electronics SyncMaster SAM02D9 1680x1050 433x271mm 20.1-inch  | 2         | 0.26%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 402       | 54.69%  |
| 1920x1080 (FHD)    | 189       | 25.71%  |
| 1280x800 (WXGA)    | 43        | 5.85%   |
| 1920x1200 (WUXGA)  | 16        | 2.18%   |
| 1600x900 (HD+)     | 15        | 2.04%   |
| 1440x900 (WXGA+)   | 12        | 1.63%   |
| 3840x2160 (4K)     | 10        | 1.36%   |
| 1024x600           | 9         | 1.22%   |
| 1680x1050 (WSXGA+) | 8         | 1.09%   |
| 1280x1024 (SXGA)   | 6         | 0.82%   |
| 3200x1800 (QHD+)   | 5         | 0.68%   |
| 2560x1080          | 4         | 0.54%   |
| 1360x768           | 4         | 0.54%   |
| 2288x1287          | 2         | 0.27%   |
| 3840x2400          | 1         | 0.14%   |
| 3840x1080          | 1         | 0.14%   |
| 3456x2160          | 1         | 0.14%   |
| 3000x2000          | 1         | 0.14%   |
| 2880x1800          | 1         | 0.14%   |
| 2560x1440 (QHD)    | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |
| 1280x768           | 1         | 0.14%   |
| 1024x768 (XGA)     | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 335       | 43.68%  |
| 14      | 135       | 17.6%   |
| 13      | 112       | 14.6%   |
| 23      | 21        | 2.74%   |
| 17      | 21        | 2.74%   |
| 21      | 19        | 2.48%   |
| 18      | 15        | 1.96%   |
| 27      | 13        | 1.69%   |
| 10      | 12        | 1.56%   |
| 24      | 10        | 1.3%    |
| 12      | 10        | 1.3%    |
| 11      | 10        | 1.3%    |
| 19      | 9         | 1.17%   |
| 40      | 8         | 1.04%   |
| 20      | 8         | 1.04%   |
| 46      | 5         | 0.65%   |
| 52      | 4         | 0.52%   |
| 34      | 4         | 0.52%   |
| 16      | 3         | 0.39%   |
| 142     | 2         | 0.26%   |
| 84      | 2         | 0.26%   |
| 48      | 2         | 0.26%   |
| 31      | 2         | 0.26%   |
| 22      | 2         | 0.26%   |
| Unknown | 2         | 0.26%   |
| 32      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 545       | 71.43%  |
| 201-300        | 57        | 7.47%   |
| 401-500        | 53        | 6.95%   |
| 501-600        | 41        | 5.37%   |
| 351-400        | 34        | 4.46%   |
| 1001-1500      | 11        | 1.44%   |
| 801-900        | 8         | 1.05%   |
| 701-800        | 5         | 0.66%   |
| 601-700        | 3         | 0.39%   |
| More than 2000 | 2         | 0.26%   |
| 1501-2000      | 2         | 0.26%   |
| Unknown        | 2         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 590       | 86.38%  |
| 16/10   | 73        | 10.69%  |
| 5/4     | 4         | 0.59%   |
| 4/3     | 4         | 0.59%   |
| 21/9    | 4         | 0.59%   |
| 3/2     | 3         | 0.44%   |
| 1.00    | 2         | 0.29%   |
| 32/9    | 1         | 0.15%   |
| 1.96    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 334       | 43.38%  |
| 81-90          | 228       | 29.61%  |
| 201-250        | 50        | 6.49%   |
| 151-200        | 20        | 2.6%    |
| 71-80          | 18        | 2.34%   |
| 121-130        | 18        | 2.34%   |
| 141-150        | 17        | 2.21%   |
| 501-1000       | 15        | 1.95%   |
| 301-350        | 13        | 1.69%   |
| 41-50          | 12        | 1.56%   |
| 61-70          | 10        | 1.3%    |
| 51-60          | 10        | 1.3%    |
| More than 1000 | 8         | 1.04%   |
| 351-500        | 7         | 0.91%   |
| 111-120        | 5         | 0.65%   |
| 91-100         | 2         | 0.26%   |
| Unknown        | 2         | 0.26%   |
| 131-140        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 431       | 57.16%  |
| 121-160       | 157       | 20.82%  |
| 51-100        | 130       | 17.24%  |
| 1-50          | 17        | 2.25%   |
| More than 240 | 9         | 1.19%   |
| 161-240       | 8         | 1.06%   |
| Unknown       | 2         | 0.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 565       | 79.92%  |
| 2     | 113       | 15.98%  |
| 0     | 24        | 3.39%   |
| 3     | 5         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 437       | 40.39%  |
| Intel                                 | 261       | 24.12%  |
| Qualcomm Atheros                      | 177       | 16.36%  |
| Broadcom                              | 61        | 5.64%   |
| Broadcom Limited                      | 23        | 2.13%   |
| JMicron Technology                    | 17        | 1.57%   |
| Marvell Technology Group              | 16        | 1.48%   |
| TP-Link                               | 15        | 1.39%   |
| Ralink                                | 12        | 1.11%   |
| Silicon Integrated Systems [SiS]      | 10        | 0.92%   |
| Ralink Technology                     | 9         | 0.83%   |
| Samsung Electronics                   | 6         | 0.55%   |
| Motorola PCS                          | 6         | 0.55%   |
| Qualcomm Atheros Communications       | 5         | 0.46%   |
| MediaTek                              | 4         | 0.37%   |
| ASIX Electronics                      | 4         | 0.37%   |
| Ericsson Business Mobile Networks     | 3         | 0.28%   |
| DisplayLink                           | 3         | 0.28%   |
| VIA Technologies                      | 2         | 0.18%   |
| Encore Electronics                    | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.09%   |
| Xiaomi                                | 1         | 0.09%   |
| Ovislink                              | 1         | 0.09%   |
| Nvidia                                | 1         | 0.09%   |
| ICS Advent                            | 1         | 0.09%   |
| Digitech Systems                      | 1         | 0.09%   |
| Dell                                  | 1         | 0.09%   |
| Cisco Aironet Wireless Communications | 1         | 0.09%   |
| Arduino SA                            | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 240       | 18.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 108       | 8.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 2.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.81%   |
| Intel Wireless 3160                                                     | 23        | 1.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 19        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.28%   |
| Intel Wireless 3165                                                     | 16        | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 15        | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 1.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 15        | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 1.13%   |
| Intel Wireless 7260                                                     | 14        | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 13        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 12        | 0.9%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.83%   |
| Intel Wireless 7265                                                     | 11        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 11        | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 0.83%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 10        | 0.75%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 10        | 0.75%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 0.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.68%   |
| Intel Wireless 8260                                                     | 9         | 0.68%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 7         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                   | 7         | 0.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.45%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 0.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 0.45%   |
| Intel Centrino Wireless-N 130                                           | 6         | 0.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.38%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 5         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 247       | 34.99%  |
| Realtek Semiconductor                 | 191       | 27.05%  |
| Qualcomm Atheros                      | 154       | 21.81%  |
| Broadcom                              | 53        | 7.51%   |
| Broadcom Limited                      | 14        | 1.98%   |
| TP-Link                               | 12        | 1.7%    |
| Ralink                                | 12        | 1.7%    |
| Ralink Technology                     | 9         | 1.27%   |
| Qualcomm Atheros Communications       | 5         | 0.71%   |
| MediaTek                              | 4         | 0.57%   |
| Encore Electronics                    | 2         | 0.28%   |
| Ovislink                              | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| Cisco Aironet Wireless Communications | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 4.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 4.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 4.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 3.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 3.37%   |
| Intel Wireless 3160                                                     | 23        | 3.23%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 19        | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.38%   |
| Intel Wireless 3165                                                     | 16        | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 2.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.1%    |
| Intel Wireless 7260                                                     | 14        | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 13        | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 1.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 1.54%   |
| Intel Wireless 7265                                                     | 11        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 11        | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 1.4%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 1.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 1.4%    |
| Intel Wireless 8260                                                     | 9         | 1.26%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.84%   |
| Intel Centrino Wireless-N 130                                           | 6         | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.7%    |
| Intel Centrino Wireless-N 6150                                          | 5         | 0.7%    |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 5         | 0.7%    |
| Intel Centrino Advanced-N 6235                                          | 5         | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                            | 4         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.56%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.42%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 3         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 368       | 60.63%  |
| Intel                            | 76        | 12.52%  |
| Qualcomm Atheros                 | 68        | 11.2%   |
| JMicron Technology               | 17        | 2.8%    |
| Marvell Technology Group         | 16        | 2.64%   |
| Broadcom                         | 16        | 2.64%   |
| Silicon Integrated Systems [SiS] | 10        | 1.65%   |
| Broadcom Limited                 | 9         | 1.48%   |
| Samsung Electronics              | 6         | 0.99%   |
| Motorola PCS                     | 5         | 0.82%   |
| ASIX Electronics                 | 4         | 0.66%   |
| TP-Link                          | 3         | 0.49%   |
| DisplayLink                      | 3         | 0.49%   |
| VIA Technologies                 | 2         | 0.33%   |
| Xiaomi                           | 1         | 0.16%   |
| Nvidia                           | 1         | 0.16%   |
| ICS Advent                       | 1         | 0.16%   |
| Digitech Systems                 | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 240       | 39.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 108       | 17.76%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 15        | 2.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 2.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 2.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 1.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 1.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 1.15%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 5         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.82%   |
| Motorola PCS moto g stylus                                        | 5         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.66%   |
| Intel PRO/100 VE Network Connection                               | 4         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.49%   |
| Intel WiMAX Connection 2400m                                      | 3         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.49%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.49%   |
| ASIX AX88772B Fast Ethernet Controller                            | 3         | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.33%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 0.33%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.33%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.33%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.33%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.33%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 0.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.33%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.33%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.33%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.16%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.16%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.16%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.16%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.16%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.16%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.16%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.16%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 677       | 53.14%  |
| Ethernet | 589       | 46.23%  |
| Modem    | 8         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 574       | 81.53%  |
| Ethernet | 130       | 18.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 544       | 78.61%  |
| 1     | 120       | 17.34%  |
| 0     | 24        | 3.47%   |
| 3     | 3         | 0.43%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 636       | 90.99%  |
| Yes  | 63        | 9.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 180       | 38.46%  |
| Realtek Semiconductor           | 90        | 19.23%  |
| Qualcomm Atheros Communications | 47        | 10.04%  |
| IMC Networks                    | 31        | 6.62%   |
| Broadcom                        | 31        | 6.62%   |
| Lite-On Technology              | 23        | 4.91%   |
| Foxconn / Hon Hai               | 14        | 2.99%   |
| Dell                            | 12        | 2.56%   |
| Apple                           | 10        | 2.14%   |
| Toshiba                         | 8         | 1.71%   |
| Ralink                          | 6         | 1.28%   |
| Cambridge Silicon Radio         | 6         | 1.28%   |
| ASUSTek Computer                | 2         | 0.43%   |
| USI                             | 1         | 0.21%   |
| Syntek                          | 1         | 0.21%   |
| Realtek                         | 1         | 0.21%   |
| Qcom                            | 1         | 0.21%   |
| Integrated System Solution      | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| Foxconn International           | 1         | 0.21%   |
| Alps Electric                   | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 91        | 19.44%  |
| Realtek Bluetooth Radio                                                             | 50        | 10.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 34        | 7.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 30        | 6.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 25        | 5.34%   |
| Intel Bluetooth Device                                                              | 17        | 3.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 2.35%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 11        | 2.35%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 2.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 1.92%   |
| Intel AX200 Bluetooth                                                               | 9         | 1.92%   |
| IMC Networks Bluetooth Device                                                       | 9         | 1.92%   |
| Lite-On Bluetooth Device                                                            | 8         | 1.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.5%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 7         | 1.5%    |
| Toshiba Bluetooth USB Host Controller                                               | 6         | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.28%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 6         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 1.28%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 1.28%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 1.28%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.07%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 1.07%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.85%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.64%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 3         | 0.64%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.64%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.43%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.43%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.43%   |
| Broadcom Bluetooth 2.1 Device                                                       | 2         | 0.43%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.43%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.43%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.43%   |
| USI Bluetooth Module BCM92070                                                       | 1         | 0.21%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.21%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.21%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.21%   |
| Qualcomm Atheros Bluetooth (AR3011)                                                 | 1         | 0.21%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.21%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.21%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.21%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.21%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.21%   |
| IMC Networks Bluetooth                                                              | 1         | 0.21%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 1         | 0.21%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.21%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.21%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.21%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.21%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 575       | 76.56%  |
| AMD                              | 97        | 12.92%  |
| Nvidia                           | 34        | 4.53%   |
| Silicon Integrated Systems [SiS] | 10        | 1.33%   |
| Logitech                         | 10        | 1.33%   |
| GN Netcom                        | 4         | 0.53%   |
| C-Media Electronics              | 4         | 0.53%   |
| Kingston Technology              | 3         | 0.4%    |
| VIA Technologies                 | 2         | 0.27%   |
| Plantronics                      | 2         | 0.27%   |
| Focusrite-Novation               | 2         | 0.27%   |
| Texas Instruments                | 1         | 0.13%   |
| Samson Technologies              | 1         | 0.13%   |
| Realtek Semiconductor            | 1         | 0.13%   |
| Microsoft                        | 1         | 0.13%   |
| Generalplus Technology           | 1         | 0.13%   |
| ESI Audiotechnik                 | 1         | 0.13%   |
| Creative Technology              | 1         | 0.13%   |
| BEHRINGER International          | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 108       | 12.13%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 9.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 47        | 5.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 40        | 4.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 39        | 4.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 31        | 3.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 31        | 3.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.58%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 2.58%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.47%   |
| AMD FCH Azalia Controller                                                                         | 20        | 2.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 19        | 2.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 1.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.24%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 10        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.12%   |
| AMD High Definition Audio Controller                                                              | 8         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 0.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.56%   |
| Logitech USB Headset                                                                              | 5         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.45%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.34%   |
| Logitech Headset H390                                                                             | 3         | 0.34%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.22%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.22%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.22%   |
| Nvidia Audio device                                                                               | 2         | 0.22%   |
| Kingston Technology HyperX Quadcast                                                               | 2         | 0.22%   |
| Intel USB PnP Sound Device                                                                        | 2         | 0.22%   |
| GN Netcom Jabra EVOLVE 20                                                                         | 2         | 0.22%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.22%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.22%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.22%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.22%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.22%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.11%   |
| Samson Technologies Q2U handheld mic with XLR                                                     | 1         | 0.11%   |
| Realtek Semiconductor UACDemoV1.0                                                                 | 1         | 0.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 107       | 24.88%  |
| SK hynix            | 91        | 21.16%  |
| Kingston            | 65        | 15.12%  |
| Micron Technology   | 31        | 7.21%   |
| Unknown             | 28        | 6.51%   |
| A-DATA Technology   | 16        | 3.72%   |
| Crucial             | 11        | 2.56%   |
| Nanya Technology    | 10        | 2.33%   |
| Magnum Tech         | 10        | 2.33%   |
| Elpida              | 7         | 1.63%   |
| Novatech            | 5         | 1.16%   |
| Corsair             | 5         | 1.16%   |
| Unknown (ABCD)      | 4         | 0.93%   |
| Saikano             | 4         | 0.93%   |
| Ramaxel Technology  | 4         | 0.93%   |
| Memox               | 4         | 0.93%   |
| Goldkey             | 4         | 0.93%   |
| Transcend           | 2         | 0.47%   |
| Teikon              | 2         | 0.47%   |
| Super Talent        | 2         | 0.47%   |
| CSX                 | 2         | 0.47%   |
| Avant               | 2         | 0.47%   |
| Apacer              | 2         | 0.47%   |
| 48spaces            | 2         | 0.47%   |
| Unknown             | 2         | 0.47%   |
| Unknown (07D5)      | 1         | 0.23%   |
| Team                | 1         | 0.23%   |
| Qimonda             | 1         | 0.23%   |
| Neo Forza           | 1         | 0.23%   |
| Innodisk            | 1         | 0.23%   |
| High Bridge         | 1         | 0.23%   |
| G.Skill             | 1         | 0.23%   |
| Cors                | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                        | 13        | 2.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 10        | 2.15%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s                          | 10        | 2.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 9         | 1.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 6         | 1.29%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s                     | 6         | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s                     | 6         | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 5         | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 5         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 5         | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 5         | 1.08%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 5         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s          | 4         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 4         | 0.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                       | 4         | 0.86%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 4         | 0.86%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                                  | 4         | 0.86%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 3         | 0.65%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.65%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                       | 3         | 0.65%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s                      | 3         | 0.65%   |
| SK hynix RAM 212121212121212121212121212121212121 2048MB SODIMM DDR2 667MT/s | 3         | 0.65%   |
| SK hynix RAM 202020202020202020202020202020202020 2048MB SODIMM DDR2 667MT/s | 3         | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 3         | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 3         | 0.65%   |
| Samsung RAM M471B2873FHS-CF8 1024MB SODIMM DDR3 1067MT/s                     | 3         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                        | 3         | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 3         | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 3         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s                     | 3         | 0.65%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s                       | 3         | 0.65%   |
| Kingston RAM 99U5428-040.A01LF 4096MB SODIMM DDR3 1334MT/s                   | 3         | 0.65%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                      | 3         | 0.65%   |
| Kingston RAM 9905700-013.A00G 8GB SODIMM DDR4 2667MT/s                       | 3         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                  | 2         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                               | 2         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                  | 2         | 0.43%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.43%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s                     | 2         | 0.43%   |
| SK hynix RAM HYMP112S64CP6-S6 1024MB SODIMM DDR 975MT/s                      | 2         | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 2         | 0.43%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s                       | 2         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                       | 2         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 2         | 0.43%   |
| SK hynix RAM HMA81GS6MFR8N-TF 8192MB SODIMM DDR4 2133MT/s                    | 2         | 0.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                       | 2         | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                       | 2         | 0.43%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 2         | 0.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 2         | 0.43%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                        | 2         | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s                  | 2         | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s                       | 2         | 0.43%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s                    | 2         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 2         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 2         | 0.43%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                         | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 155       | 46.13%  |
| DDR4    | 135       | 40.18%  |
| DDR2    | 18        | 5.36%   |
| LPDDR4  | 10        | 2.98%   |
| SDRAM   | 7         | 2.08%   |
| LPDDR3  | 4         | 1.19%   |
| DRAM    | 3         | 0.89%   |
| DDR     | 3         | 0.89%   |
| Unknown | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 320       | 94.67%  |
| Row Of Chips | 13        | 3.85%   |
| DIMM         | 2         | 0.59%   |
| Chip         | 2         | 0.59%   |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 152       | 38.58%  |
| 8192  | 128       | 32.49%  |
| 2048  | 64        | 16.24%  |
| 16384 | 32        | 8.12%   |
| 1024  | 13        | 3.3%    |
| 32768 | 3         | 0.76%   |
| 6144  | 1         | 0.25%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 97        | 24.37%  |
| 2667    | 88        | 22.11%  |
| 3200    | 43        | 10.8%   |
| 1333    | 33        | 8.29%   |
| 2400    | 27        | 6.78%   |
| 1334    | 27        | 6.78%   |
| 2133    | 20        | 5.03%   |
| Unknown | 12        | 3.02%   |
| 3266    | 10        | 2.51%   |
| 667     | 10        | 2.51%   |
| 1067    | 7         | 1.76%   |
| 4199    | 4         | 1.01%   |
| 975     | 4         | 1.01%   |
| 2048    | 3         | 0.75%   |
| 1066    | 3         | 0.75%   |
| 800     | 3         | 0.75%   |
| 533     | 2         | 0.5%    |
| 8400    | 1         | 0.25%   |
| 4267    | 1         | 0.25%   |
| 2933    | 1         | 0.25%   |
| 1867    | 1         | 0.25%   |
| 400     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 50%     |
| Hewlett-Packard     | 2         | 33.33%  |
| QinHeng Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| QinHeng CH340S         | 1         | 16.67%  |
| HP LaserJet 1020       | 1         | 16.67%  |
| HP DeskJet F300 series | 1         | 16.67%  |
| Brother HL-1200 series | 1         | 16.67%  |
| Brother HL-1110 series | 1         | 16.67%  |
| Brother DCP-1600       | 1         | 16.67%  |

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
| Chicony Electronics                    | 150       | 24.35%  |
| IMC Networks                           | 64        | 10.39%  |
| Acer                                   | 62        | 10.06%  |
| Realtek Semiconductor                  | 56        | 9.09%   |
| Microdia                               | 44        | 7.14%   |
| Sunplus Innovation Technology          | 34        | 5.52%   |
| Suyin                                  | 24        | 3.9%    |
| Syntek                                 | 23        | 3.73%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.73%   |
| Silicon Motion                         | 20        | 3.25%   |
| Alcor Micro                            | 18        | 2.92%   |
| Quanta                                 | 17        | 2.76%   |
| Apple                                  | 12        | 1.95%   |
| Lite-On Technology                     | 10        | 1.62%   |
| Ricoh                                  | 9         | 1.46%   |
| Logitech                               | 6         | 0.97%   |
| Z-Star Microelectronics                | 5         | 0.81%   |
| OmniVision Technologies                | 5         | 0.81%   |
| Luxvisions Innotech Limited            | 5         | 0.81%   |
| Samsung Electronics                    | 4         | 0.65%   |
| GEMBIRD                                | 4         | 0.65%   |
| ALi                                    | 4         | 0.65%   |
| SunplusIT                              | 2         | 0.32%   |
| Sonix Technology                       | 2         | 0.32%   |
| Intel                                  | 2         | 0.32%   |
| icSpring                               | 2         | 0.32%   |
| Sunplus Technology                     | 1         | 0.16%   |
| Microsoft                              | 1         | 0.16%   |
| Lenovo                                 | 1         | 0.16%   |
| KYE Systems (Mouse Systems)            | 1         | 0.16%   |
| Importek                               | 1         | 0.16%   |
| Google                                 | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| Allwinner Technology                   | 1         | 0.16%   |
| 8SSC20F27145V1SR1BX02P8                | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 25        | 4.05%   |
| Chicony USB 2.0 Camera                                         | 20        | 3.24%   |
| Acer Integrated Camera                                         | 20        | 3.24%   |
| Realtek Integrated_Webcam_HD                                   | 18        | 2.91%   |
| Chicony Integrated Camera                                      | 14        | 2.27%   |
| Alcor Micro USB 2.0 Camera                                     | 14        | 2.27%   |
| Microdia Integrated_Webcam_HD                                  | 12        | 1.94%   |
| IMC Networks Integrated Camera                                 | 12        | 1.94%   |
| Chicony Lenovo EasyCamera                                      | 11        | 1.78%   |
| Sunplus Integrated_Webcam_HD                                   | 10        | 1.62%   |
| Chicony USB2.0 Camera                                          | 10        | 1.62%   |
| Chicony HD WebCam                                              | 9         | 1.46%   |
| Realtek USB Camera                                             | 8         | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                                | 8         | 1.29%   |
| Acer USB Camera                                                | 8         | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 1.13%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 7         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 7         | 1.13%   |
| Acer Lenovo EasyCamera                                         | 7         | 1.13%   |
| Sunplus Asus Webcam                                            | 6         | 0.97%   |
| Silicon Motion WebCam SC-0311139N                              | 6         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)                        | 6         | 0.97%   |
| Chicony HP Wide Vision HD Camera                               | 6         | 0.97%   |
| Acer SunplusIT Integrated Camera                               | 6         | 0.97%   |
| Z-Star Webcam                                                  | 5         | 0.81%   |
| Syntek Integrated Camera                                       | 5         | 0.81%   |
| OmniVision OV2640 Webcam                                       | 5         | 0.81%   |
| IMC Networks UVC VGA Webcam                                    | 5         | 0.81%   |
| Chicony HP Webcam                                              | 5         | 0.81%   |
| Chicony HP TrueVision HD Camera                                | 5         | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 5         | 0.81%   |
| Apple FaceTime HD Camera                                       | 5         | 0.81%   |
| Acer BisonCam, NB Pro                                          | 5         | 0.81%   |
| Syntek USB Video Device                                        | 4         | 0.65%   |
| Syntek Lenovo EasyCamera                                       | 4         | 0.65%   |
| Syntek EasyCamera                                              | 4         | 0.65%   |
| Sunplus HP TrueVision HD Camera                                | 4         | 0.65%   |
| Sunplus HD WebCam                                              | 4         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 4         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                                   | 4         | 0.65%   |
| Realtek Integrated Webcam HD                                   | 4         | 0.65%   |
| Quanta VGA WebCam                                              | 4         | 0.65%   |
| Lite-On Integrated Camera                                      | 4         | 0.65%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]              | 4         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 0.65%   |
| Chicony Integrated Camera [ThinkPad]                           | 4         | 0.65%   |
| Chicony HP TrueVision HD                                       | 4         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 0.65%   |
| Acer Lenovo Integrated Webcam                                  | 4         | 0.65%   |
| Syntek USB Camera Device                                       | 3         | 0.49%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 3         | 0.49%   |
| Suyin Acer HD Crystal Eye webcam                               | 3         | 0.49%   |
| Sunplus TOSHIBA Web Camera - HD                                | 3         | 0.49%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.49%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.49%   |
| Realtek Integrated Webcam                                      | 3         | 0.49%   |
| Quanta HP Webcam                                               | 3         | 0.49%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.49%   |
| Microdia Sonix USB 2.0 Camera                                  | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 34.21%  |
| Validity Sensors           | 24        | 31.58%  |
| Shenzhen Goodix Technology | 10        | 13.16%  |
| AuthenTec                  | 6         | 7.89%   |
| Upek                       | 4         | 5.26%   |
| Elan Microelectronics      | 4         | 5.26%   |
| STMicroelectronics         | 1         | 1.32%   |
| LighTuning Technology      | 1         | 1.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 15.79%  |
| Synaptics  WBDI                                                            | 10        | 13.16%  |
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 11.84%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 6.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.95%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.95%   |
| Elan ELAN:Fingerprint                                                      | 3         | 3.95%   |
| Unknown                                                                    | 3         | 3.95%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.63%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.32%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.32%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.32%   |
| AuthenTec AES2810                                                          | 1         | 1.32%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 16        | 61.54%  |
| Upek     | 8         | 30.77%  |
| O2 Micro | 1         | 3.85%   |
| Lenovo   | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 19.23%  |
| Broadcom 58200                                                               | 5         | 19.23%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 11.54%  |
| Broadcom 5880                                                                | 3         | 11.54%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.85%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 501       | 70.96%  |
| 1     | 182       | 25.78%  |
| 2     | 19        | 2.69%   |
| 3     | 3         | 0.42%   |
| 8     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 76        | 32.76%  |
| Graphics card            | 49        | 21.12%  |
| Net/wireless             | 37        | 15.95%  |
| Chipcard                 | 25        | 10.78%  |
| Camera                   | 10        | 4.31%   |
| Bluetooth                | 10        | 4.31%   |
| Multimedia controller    | 7         | 3.02%   |
| Net/ethernet             | 4         | 1.72%   |
| Communication controller | 4         | 1.72%   |
| Sound                    | 3         | 1.29%   |
| Modem                    | 2         | 0.86%   |
| Flash memory             | 2         | 0.86%   |
| Card reader              | 2         | 0.86%   |
| Network                  | 1         | 0.43%   |

