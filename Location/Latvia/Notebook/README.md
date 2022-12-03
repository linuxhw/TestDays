Linux in Latvia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

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

Total: 263

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GV72 7RE                    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| ASUSTek       | G751JL                      | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| ASUSTek       | X453MA                      | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| MSI           | Modern 14 B4MW              | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Wortmann      | CR700                       | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| ASUSTek       | X553MA                      | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Toshiba       | Satellite L350              | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Acer          | Aspire 5250                 | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| Acer          | Aspire 5742                 | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| HP            | EliteBook 8440p             | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Acer          | Aspire A315-42              | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Dell          | Precision 3561              | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| HP            | ProBook 450 G0              | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Dell          | Inspiron 3543               | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Valve         | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| Dell          | Latitude E7440              | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| Dell          | Latitude 5590               | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| Dell          | Latitude 5520               | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| Acer          | AO725                       | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| Dell          | Inspiron 3583               | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| Dell          | Inspiron 5720               | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| Dell          | Latitude E5400              | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| ASUSTek       | N56VM                       | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Lenovo        | G70-80 80FF                 | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Lenovo        | V110-15IAP 80TG             | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Fujitsu       | STYLISTIC Q704              | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Acer          | Aspire E5-774G              | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| ASUSTek       | F9S                         | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Acer          | Aspire E1-570               | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Packard Be... | EasyNote LE69KB             | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| HP            | Pavilion dv6700             | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| HP            | Pavilion dv6700             | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| Acer          | Aspire ES1-512              | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASUSTek       | N56VZ                       | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| Dell          | Latitude E6230              | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASUSTek       | BU401LAV                    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Dell          | Inspiron 1720               | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| HP            | Laptop 15-db0xxx            | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| Dell          | Latitude D630               | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| HP            | EliteBook 8440p             | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | Laptop 15-bw0xx             | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| Dell          | Inspiron N5010              | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| Dell          | Inspiron 1720               | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Lenovo        | G70-80 80FF                 | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Acer          | Aspire V5-552G              | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Dell          | XPS MXC062                  | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | K73BE                       | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| ASUSTek       | X553MA                      | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| eMachines     | Unknown                     | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | K53SD                       | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 22        | 11.34%  |
| ROSA R11           | 14        | 7.22%   |
| Ubuntu 18.04       | 9         | 4.64%   |
| ROSA R9            | 7         | 3.61%   |
| ROSA R10           | 6         | 3.09%   |
| Arch               | 6         | 3.09%   |
| ROSA R8.1          | 5         | 2.58%   |
| ROSA R11.1         | 5         | 2.58%   |
| Debian 11          | 5         | 2.58%   |
| ROSA R8            | 4         | 2.06%   |
| Pop!_OS 21.04      | 4         | 2.06%   |
| Pop!_OS 20.10      | 4         | 2.06%   |
| Manjaro            | 4         | 2.06%   |
| Linux Mint 21      | 4         | 2.06%   |
| Ubuntu 19.10       | 3         | 1.55%   |
| ROSA 12.1          | 3         | 1.55%   |
| OpenMandriva 4.3   | 3         | 1.55%   |
| Linux Mint 20.3    | 3         | 1.55%   |
| Linux Mint 19      | 3         | 1.55%   |
| Linux Mint 18.3    | 3         | 1.55%   |
| KDE neon 20.04     | 3         | 1.55%   |
| ArcoLinux Rolling  | 3         | 1.55%   |
| Arch Rolling       | 3         | 1.55%   |
| Ubuntu 22.04       | 2         | 1.03%   |
| Ubuntu 21.10       | 2         | 1.03%   |
| Ubuntu 21.04       | 2         | 1.03%   |
| Ubuntu 20.10       | 2         | 1.03%   |
| ROSA 12.2          | 2         | 1.03%   |
| Pop!_OS 22.04      | 2         | 1.03%   |
| Pop!_OS 21.10      | 2         | 1.03%   |
| Linux Mint 20.1    | 2         | 1.03%   |
| Linux Mint 20      | 2         | 1.03%   |
| Fedora 34          | 2         | 1.03%   |
| Debian Testing     | 2         | 1.03%   |
| Debian 10          | 2         | 1.03%   |
| Xubuntu 21.04      | 1         | 0.52%   |
| Xubuntu 20.04      | 1         | 0.52%   |
| Void Linux Rolling | 1         | 0.52%   |
| Ubuntu Unity 21.04 | 1         | 0.52%   |
| Ubuntu Unity 16.04 | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 45        | 26.16%  |
| ROSA          | 32        | 18.6%   |
| Linux Mint    | 18        | 10.47%  |
| Pop!_OS       | 11        | 6.4%    |
| Debian        | 9         | 5.23%   |
| Arch          | 9         | 5.23%   |
| Manjaro       | 8         | 4.65%   |
| Fedora        | 6         | 3.49%   |
| OpenMandriva  | 5         | 2.91%   |
| ArcoLinux     | 4         | 2.33%   |
| KDE neon      | 3         | 1.74%   |
| Elementary    | 3         | 1.74%   |
| Xubuntu       | 2         | 1.16%   |
| Ubuntu Unity  | 2         | 1.16%   |
| Kali          | 2         | 1.16%   |
| Endless       | 2         | 1.16%   |
| Void Linux    | 1         | 0.58%   |
| Ubuntu Budgie | 1         | 0.58%   |
| SteamOS       | 1         | 0.58%   |
| Solus         | 1         | 0.58%   |
| Peppermint    | 1         | 0.58%   |
| Parrot        | 1         | 0.58%   |
| openSUSE      | 1         | 0.58%   |
| MX            | 1         | 0.58%   |
| GNOME OS      | 1         | 0.58%   |
| Garuda Linux  | 1         | 0.58%   |
| EndeavourOS   | 1         | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.83%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.83%   |
| 5.4.0-42-generic                   | 4         | 1.89%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.89%   |
| 5.8.0-7630-generic                 | 3         | 1.42%   |
| 5.16.7-desktop-1omv4003            | 3         | 1.42%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.42%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.42%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.42%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.42%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.42%   |
| 5.8.0-48-generic                   | 2         | 0.94%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.94%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.94%   |
| 5.4.0-80-generic                   | 2         | 0.94%   |
| 5.4.0-26-generic                   | 2         | 0.94%   |
| 5.15.0-46-generic                  | 2         | 0.94%   |
| 5.13.6-arch1-1                     | 2         | 0.94%   |
| 5.13.0-25-generic                  | 2         | 0.94%   |
| 5.11.0-43-generic                  | 2         | 0.94%   |
| 5.10.0-8-amd64                     | 2         | 0.94%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.94%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.94%   |
| 4.18.0-18-generic                  | 2         | 0.94%   |
| 4.15.0-54-generic                  | 2         | 0.94%   |
| 4.10.0-38-generic                  | 2         | 0.94%   |
| 6.0.9_1                            | 1         | 0.47%   |
| 6.0.8-AMD-znver2                   | 1         | 0.47%   |
| 6.0.2-xm1.0.fc37.x86_64            | 1         | 0.47%   |
| 5.9.8-2-MANJARO                    | 1         | 0.47%   |
| 5.9.0-5-amd64                      | 1         | 0.47%   |
| 5.8.16-2-MANJARO                   | 1         | 0.47%   |
| 5.8.13-050813-generic              | 1         | 0.47%   |
| 5.8.0-53-generic                   | 1         | 0.47%   |
| 5.8.0-45-generic                   | 1         | 0.47%   |
| 5.8.0-33-generic                   | 1         | 0.47%   |
| 5.8.0-29-generic                   | 1         | 0.47%   |
| 5.8.0-25-generic                   | 1         | 0.47%   |
| 5.8.0-1parrot1-amd64               | 1         | 0.47%   |
| 5.7.5-arch1-1                      | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 13.66%  |
| 4.15.0  | 22        | 10.73%  |
| 5.11.0  | 11        | 5.37%   |
| 5.8.0   | 10        | 4.88%   |
| 5.13.0  | 10        | 4.88%   |
| 5.3.0   | 6         | 2.93%   |
| 5.15.0  | 6         | 2.93%   |
| 5.10.0  | 6         | 2.93%   |
| 4.9.20  | 6         | 2.93%   |
| 5.10.74 | 4         | 1.95%   |
| 5.0.0   | 4         | 1.95%   |
| 4.18.0  | 4         | 1.95%   |
| 5.17.1  | 3         | 1.46%   |
| 5.16.7  | 3         | 1.46%   |
| 4.9.60  | 3         | 1.46%   |
| 4.9.41  | 3         | 1.46%   |
| 4.9.155 | 3         | 1.46%   |
| 4.1.34  | 3         | 1.46%   |
| 5.4.83  | 2         | 0.98%   |
| 5.4.72  | 2         | 0.98%   |
| 5.4.32  | 2         | 0.98%   |
| 5.14.0  | 2         | 0.98%   |
| 5.13.6  | 2         | 0.98%   |
| 5.13.12 | 2         | 0.98%   |
| 5.12.14 | 2         | 0.98%   |
| 4.9.9   | 2         | 0.98%   |
| 4.9.124 | 2         | 0.98%   |
| 4.4.0   | 2         | 0.98%   |
| 4.10.0  | 2         | 0.98%   |
| 4.1.38  | 2         | 0.98%   |
| 6.0.9   | 1         | 0.49%   |
| 6.0.8   | 1         | 0.49%   |
| 6.0.2   | 1         | 0.49%   |
| 5.9.8   | 1         | 0.49%   |
| 5.9.0   | 1         | 0.49%   |
| 5.8.16  | 1         | 0.49%   |
| 5.8.13  | 1         | 0.49%   |
| 5.7.5   | 1         | 0.49%   |
| 5.6.18  | 1         | 0.49%   |
| 5.5.5   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 16.84%  |
| 4.15    | 22        | 11.22%  |
| 4.9     | 16        | 8.16%   |
| 5.13    | 13        | 6.63%   |
| 5.10    | 13        | 6.63%   |
| 5.8     | 12        | 6.12%   |
| 5.15    | 12        | 6.12%   |
| 5.11    | 11        | 5.61%   |
| 5.3     | 6         | 3.06%   |
| 5.16    | 6         | 3.06%   |
| 5.12    | 6         | 3.06%   |
| 5.18    | 4         | 2.04%   |
| 5.17    | 4         | 2.04%   |
| 5.14    | 4         | 2.04%   |
| 5.0     | 4         | 2.04%   |
| 4.18    | 4         | 2.04%   |
| 4.1     | 4         | 2.04%   |
| 6.0     | 3         | 1.53%   |
| 5.5     | 3         | 1.53%   |
| 5.19    | 3         | 1.53%   |
| 5.9     | 2         | 1.02%   |
| 4.4     | 2         | 1.02%   |
| 4.19    | 2         | 1.02%   |
| 4.10    | 2         | 1.02%   |
| 5.7     | 1         | 0.51%   |
| 5.6     | 1         | 0.51%   |
| 5.2     | 1         | 0.51%   |
| 4.20    | 1         | 0.51%   |
| 4.13    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 94.64%  |
| i686   | 9         | 5.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 68        | 37.57%  |
| KDE5       | 29        | 16.02%  |
| KDE4       | 24        | 13.26%  |
| Unknown    | 17        | 9.39%   |
| XFCE       | 13        | 7.18%   |
| MATE       | 8         | 4.42%   |
| X-Cinnamon | 5         | 2.76%   |
| Budgie     | 4         | 2.21%   |
| Pantheon   | 3         | 1.66%   |
| KDE        | 3         | 1.66%   |
| Unity      | 2         | 1.1%    |
| LXQt       | 2         | 1.1%    |
| Cinnamon   | 2         | 1.1%    |
| LXDE       | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 139       | 79.89%  |
| Wayland | 24        | 13.79%  |
| Unknown | 8         | 4.6%    |
| Tty     | 3         | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 67        | 38.29%  |
| GDM     | 30        | 17.14%  |
| KDM     | 24        | 13.71%  |
| SDDM    | 23        | 13.14%  |
| LightDM | 13        | 7.43%   |
| TDM     | 11        | 6.29%   |
| GDM3    | 4         | 2.29%   |
| SLiM    | 1         | 0.57%   |
| MDM     | 1         | 0.57%   |
| LDM     | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 82        | 46.86%  |
| Unknown     | 43        | 24.57%  |
| lv_LV       | 18        | 10.29%  |
| ru_RU       | 17        | 9.71%   |
| en_GB       | 9         | 5.14%   |
| C           | 3         | 1.71%   |
| ru_RU.UTF_8 | 1         | 0.57%   |
| POSIX       | 1         | 0.57%   |
| de_DE       | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 90        | 52.94%  |
| EFI  | 80        | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 77.33%  |
| Unknown | 16        | 9.3%    |
| Btrfs   | 15        | 8.72%   |
| Overlay | 7         | 4.07%   |
| Zfs     | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 44.51%  |
| GPT     | 60        | 34.68%  |
| MBR     | 36        | 20.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 159       | 90.34%  |
| Yes       | 17        | 9.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 73.26%  |
| Yes       | 46        | 26.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 38        | 22.62%  |
| ASUSTek Computer    | 29        | 17.26%  |
| Hewlett-Packard     | 28        | 16.67%  |
| Dell                | 24        | 14.29%  |
| Acer                | 21        | 12.5%   |
| Toshiba             | 6         | 3.57%   |
| Samsung Electronics | 4         | 2.38%   |
| MSI                 | 4         | 2.38%   |
| HUAWEI              | 2         | 1.19%   |
| Wortmann AG         | 1         | 0.6%    |
| Valve               | 1         | 0.6%    |
| Timi                | 1         | 0.6%    |
| Sony                | 1         | 0.6%    |
| Razer               | 1         | 0.6%    |
| Quanta              | 1         | 0.6%    |
| Packard Bell        | 1         | 0.6%    |
| Fujitsu Siemens     | 1         | 0.6%    |
| Fujitsu             | 1         | 0.6%    |
| eMachines           | 1         | 0.6%    |
| Apple               | 1         | 0.6%    |
| Advent              | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.79%   |
| Toshiba Satellite C660                                | 2         | 1.19%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.19%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 1.19%   |
| HP EliteBook 8440p                                    | 2         | 1.19%   |
| HP 250 G6 Notebook PC                                 | 2         | 1.19%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 1.19%   |
| ASUS X553MA                                           | 2         | 1.19%   |
| ASUS X551MA                                           | 2         | 1.19%   |
| Wortmann AG CR700                                     | 1         | 0.6%    |
| Valve Jupiter                                         | 1         | 0.6%    |
| Toshiba Satellite L850-1LK                            | 1         | 0.6%    |
| Toshiba Satellite L750                                | 1         | 0.6%    |
| Toshiba Satellite L350                                | 1         | 0.6%    |
| Toshiba Satellite C50D-B                              | 1         | 0.6%    |
| Timi A35S                                             | 1         | 0.6%    |
| Sony VPCCW2S8E                                        | 1         | 0.6%    |
| Samsung R528/R728                                     | 1         | 0.6%    |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.6%    |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.6%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.6%    |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.6%    |
| Quanta TW8/SW8/DW8                                    | 1         | 0.6%    |
| Packard Bell EasyNote LE69KB                          | 1         | 0.6%    |
| MSI Modern 14 B4MW                                    | 1         | 0.6%    |
| MSI GV72 7RE                                          | 1         | 0.6%    |
| MSI GT62VR 6RE                                        | 1         | 0.6%    |
| MSI GP75 Leopard 9SD                                  | 1         | 0.6%    |
| Lenovo Y50-70 20378                                   | 1         | 0.6%    |
| Lenovo V110-15IAP 80TG                                | 1         | 0.6%    |
| Lenovo ThinkPad X260 20F5S5Q200                       | 1         | 0.6%    |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.6%    |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.6%    |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.6%    |
| Lenovo ThinkPad X220 4291Q50                          | 1         | 0.6%    |
| Lenovo ThinkPad X201 Tablet 311396U                   | 1         | 0.6%    |
| Lenovo ThinkPad T60 8741W3M                           | 1         | 0.6%    |
| Lenovo ThinkPad T495 20NK000HMH                       | 1         | 0.6%    |
| Lenovo ThinkPad T460s 20FAS4KH04                      | 1         | 0.6%    |
| Lenovo ThinkPad T430 2347HM4                          | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 22        | 13.1%   |
| Acer Aspire           | 13        | 7.74%   |
| HP EliteBook          | 11        | 6.55%   |
| Dell Inspiron         | 10        | 5.95%   |
| Dell Latitude         | 9         | 5.36%   |
| Lenovo IdeaPad        | 8         | 4.76%   |
| Toshiba Satellite     | 6         | 3.57%   |
| HP ProBook            | 5         | 2.98%   |
| HP Pavilion           | 4         | 2.38%   |
| ASUS VivoBook         | 4         | 2.38%   |
| HP 250                | 3         | 1.79%   |
| HP Laptop             | 2         | 1.19%   |
| Dell XPS              | 2         | 1.19%   |
| ASUS ZenBook          | 2         | 1.19%   |
| ASUS X553MA           | 2         | 1.19%   |
| ASUS X551MA           | 2         | 1.19%   |
| ASUS TUF              | 2         | 1.19%   |
| Acer Nitro            | 2         | 1.19%   |
| Wortmann AG CR700     | 1         | 0.6%    |
| Valve Jupiter         | 1         | 0.6%    |
| Timi A35S             | 1         | 0.6%    |
| Sony VPCCW2S8E        | 1         | 0.6%    |
| Samsung R528          | 1         | 0.6%    |
| Samsung 355V4C        | 1         | 0.6%    |
| Samsung 350V5C        | 1         | 0.6%    |
| Samsung 300V3A        | 1         | 0.6%    |
| Razer Blade           | 1         | 0.6%    |
| Quanta TW8            | 1         | 0.6%    |
| Packard Bell EasyNote | 1         | 0.6%    |
| MSI Modern            | 1         | 0.6%    |
| MSI GV72              | 1         | 0.6%    |
| MSI GT62VR            | 1         | 0.6%    |
| MSI GP75              | 1         | 0.6%    |
| Lenovo Y50-70         | 1         | 0.6%    |
| Lenovo V110-15IAP     | 1         | 0.6%    |
| Lenovo ThinkBook      | 1         | 0.6%    |
| Lenovo Legion         | 1         | 0.6%    |
| Lenovo G70-80         | 1         | 0.6%    |
| Lenovo G550           | 1         | 0.6%    |
| Lenovo G50-80         | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 17        | 10.12%  |
| 2013 | 17        | 10.12%  |
| 2014 | 14        | 8.33%   |
| 2020 | 13        | 7.74%   |
| 2018 | 13        | 7.74%   |
| 2015 | 12        | 7.14%   |
| 2010 | 12        | 7.14%   |
| 2011 | 11        | 6.55%   |
| 2017 | 9         | 5.36%   |
| 2016 | 9         | 5.36%   |
| 2012 | 9         | 5.36%   |
| 2008 | 9         | 5.36%   |
| 2007 | 7         | 4.17%   |
| 2021 | 6         | 3.57%   |
| 2009 | 6         | 3.57%   |
| 2022 | 2         | 1.19%   |
| 2006 | 2         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 168       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 90%     |
| Enabled  | 17        | 10%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 99.4%   |
| Yes  | 1         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 50        | 29.59%  |
| 4.01-8.0   | 48        | 28.4%   |
| 8.01-16.0  | 25        | 14.79%  |
| 16.01-24.0 | 23        | 13.61%  |
| 32.01-64.0 | 7         | 4.14%   |
| 1.01-2.0   | 7         | 4.14%   |
| 2.01-3.0   | 5         | 2.96%   |
| 24.01-32.0 | 2         | 1.18%   |
| 0.51-1.0   | 2         | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 31.72%  |
| 2.01-3.0   | 48        | 25.81%  |
| 0.51-1.0   | 25        | 13.44%  |
| 4.01-8.0   | 24        | 12.9%   |
| 3.01-4.0   | 20        | 10.75%  |
| 8.01-16.0  | 7         | 3.76%   |
| 16.01-24.0 | 2         | 1.08%   |
| 0.01-0.5   | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 122       | 71.76%  |
| 2      | 41        | 24.12%  |
| 3      | 4         | 2.35%   |
| 0      | 2         | 1.18%   |
| 4      | 1         | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 57.89%  |
| Yes       | 72        | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 90.59%  |
| No        | 16        | 9.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 98.81%  |
| No        | 2         | 1.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 74.85%  |
| No        | 43        | 25.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 168       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 130       | 73.03%  |
| Jelgava                 | 6         | 3.37%   |
| Daugavpils              | 6         | 3.37%   |
| Liepāja                | 5         | 2.81%   |
| Jūrmala                | 3         | 1.69%   |
| Adazi                   | 3         | 1.69%   |
| Valmiera                | 2         | 1.12%   |
| Saulkrasti              | 2         | 1.12%   |
| Malpils                 | 2         | 1.12%   |
| Jaunmarupe              | 2         | 1.12%   |
| Cēsis                  | 2         | 1.12%   |
| Zvejniekciems           | 1         | 0.56%   |
| Ulbroka                 | 1         | 0.56%   |
| Tukums                  | 1         | 0.56%   |
| Tiraine                 | 1         | 0.56%   |
| Saldus                  | 1         | 0.56%   |
| Pļaviņas              | 1         | 0.56%   |
| Limbaži                | 1         | 0.56%   |
| Kuldīga                | 1         | 0.56%   |
| Jēkabpils Municipality | 1         | 0.56%   |
| Jēkabpils              | 1         | 0.56%   |
| Iecava                  | 1         | 0.56%   |
| Garciems                | 1         | 0.56%   |
| Dobele                  | 1         | 0.56%   |
| Aizpute                 | 1         | 0.56%   |
| Aizkraukle              | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 32        | 40     | 15.53%  |
| Seagate                 | 28        | 34     | 13.59%  |
| Kingston                | 24        | 29     | 11.65%  |
| Toshiba                 | 23        | 26     | 11.17%  |
| WDC                     | 19        | 28     | 9.22%   |
| Hitachi                 | 10        | 13     | 4.85%   |
| SK hynix                | 7         | 7      | 3.4%    |
| SanDisk                 | 7         | 14     | 3.4%    |
| HGST                    | 7         | 15     | 3.4%    |
| Unknown                 | 6         | 7      | 2.91%   |
| Micron Technology       | 6         | 6      | 2.91%   |
| Patriot                 | 4         | 8      | 1.94%   |
| A-DATA Technology       | 4         | 5      | 1.94%   |
| KIOXIA                  | 3         | 4      | 1.46%   |
| Intel                   | 3         | 5      | 1.46%   |
| Crucial                 | 3         | 3      | 1.46%   |
| LITEON                  | 2         | 2      | 0.97%   |
| Verbatim                | 1         | 1      | 0.49%   |
| USB                     | 1         | 1      | 0.49%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.49%   |
| Realtek                 | 1         | 1      | 0.49%   |
| PNY                     | 1         | 1      | 0.49%   |
| Plextor                 | 1         | 1      | 0.49%   |
| Phison                  | 1         | 1      | 0.49%   |
| OCZ                     | 1         | 1      | 0.49%   |
| Netac                   | 1         | 1      | 0.49%   |
| LITEONIT                | 1         | 1      | 0.49%   |
| Lexar                   | 1         | 1      | 0.49%   |
| KingSpec                | 1         | 1      | 0.49%   |
| Kingchuxing             | 1         | 2      | 0.49%   |
| Intenso                 | 1         | 1      | 0.49%   |
| Integral                | 1         | 1      | 0.49%   |
| Hrdtac                  | 1         | 2      | 0.49%   |
| Fujitsu                 | 1         | 1      | 0.49%   |
| China                   | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 6         | 2.83%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 2.36%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.89%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 1.89%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.89%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.89%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.42%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 1.42%   |
| Hitachi HTS545050B9A300 500GB       | 3         | 1.42%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.94%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.94%   |
| Toshiba MK8034GSX 80GB              | 2         | 0.94%   |
| Toshiba MK6465GSX 640GB             | 2         | 0.94%   |
| SK hynix HFM512GDJTNG-8310A 512GB   | 2         | 0.94%   |
| SK hynix BC511 NVMe 256GB           | 2         | 0.94%   |
| Seagate ST9160821AS 160GB           | 2         | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.94%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 2         | 0.94%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.94%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.94%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.94%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.94%   |
| Samsung HM321HI 320GB               | 2         | 0.94%   |
| Patriot Burst 240GB SSD             | 2         | 0.94%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 2         | 0.94%   |
| Kingston SV300S37A60G 64GB SSD      | 2         | 0.94%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.94%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.94%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.94%   |
| HGST HTS545050A7E680 500GB          | 2         | 0.94%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.47%   |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.47%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.47%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.47%   |
| WDC WD3200BEVT-75ZCT0 320GB         | 1         | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.47%   |
| WDC WD3200BEVS-26VAT0 320GB         | 1         | 0.47%   |
| WDC WD2500BEKT-60PVMT0 250GB        | 1         | 0.47%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 32.94%  |
| Toshiba             | 18        | 21     | 21.18%  |
| WDC                 | 16        | 24     | 18.82%  |
| Hitachi             | 10        | 13     | 11.76%  |
| HGST                | 7         | 15     | 8.24%   |
| Samsung Electronics | 4         | 4      | 4.71%   |
| USB                 | 1         | 1      | 1.18%   |
| Fujitsu             | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 21        | 25     | 30%     |
| Samsung Electronics | 19        | 23     | 27.14%  |
| Patriot             | 4         | 8      | 5.71%   |
| A-DATA Technology   | 4         | 5      | 5.71%   |
| SanDisk             | 3         | 4      | 4.29%   |
| Micron Technology   | 3         | 3      | 4.29%   |
| Crucial             | 3         | 3      | 4.29%   |
| LITEON              | 2         | 2      | 2.86%   |
| Verbatim            | 1         | 1      | 1.43%   |
| Toshiba             | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Plextor             | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| Lexar               | 1         | 1      | 1.43%   |
| KingSpec            | 1         | 1      | 1.43%   |
| Intenso             | 1         | 1      | 1.43%   |
| Integral            | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 83        | 113    | 42.35%  |
| SSD     | 65        | 84     | 33.16%  |
| NVMe    | 42        | 59     | 21.43%  |
| MMC     | 4         | 5      | 2.04%   |
| Unknown | 2         | 5      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 197    | 71.98%  |
| NVMe | 42        | 58     | 23.08%  |
| SAS  | 5         | 6      | 2.75%   |
| MMC  | 4         | 5      | 2.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 136    | 68.28%  |
| 0.51-1.0   | 44        | 59     | 30.34%  |
| 1.01-2.0   | 2         | 2      | 1.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 31.72%  |
| 251-500        | 46        | 24.73%  |
| 501-1000       | 26        | 13.98%  |
| 51-100         | 14        | 7.53%   |
| 1001-2000      | 13        | 6.99%   |
| 1-20           | 13        | 6.99%   |
| 21-50          | 6         | 3.23%   |
| Unknown        | 5         | 2.69%   |
| 2001-3000      | 3         | 1.61%   |
| More than 3000 | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 79        | 42.93%  |
| 21-50     | 27        | 14.67%  |
| 101-250   | 21        | 11.41%  |
| 51-100    | 21        | 11.41%  |
| 251-500   | 15        | 8.15%   |
| 501-1000  | 10        | 5.43%   |
| 1001-2000 | 5         | 2.72%   |
| Unknown   | 5         | 2.72%   |
| 2001-3000 | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 4.76%   |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 4.76%   |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4.76%   |
| Toshiba MK8034GSX 80GB               | 1         | 1      | 4.76%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 4.76%   |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 4.76%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB            | 1         | 3      | 4.76%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 4.76%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 4.76%   |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 4.76%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 4.76%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 4.76%   |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 4.76%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 4.76%   |
| HGST HTS721010A9E630 1TB             | 1         | 2      | 4.76%   |
| HGST HTS545050A7E680 500GB           | 1         | 1      | 4.76%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 7      | 23.81%  |
| Toshiba             | 4         | 4      | 19.05%  |
| Seagate             | 4         | 6      | 19.05%  |
| WDC                 | 3         | 6      | 14.29%  |
| Kingston            | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 7      | 26.32%  |
| Toshiba             | 4         | 4      | 21.05%  |
| Seagate             | 4         | 6      | 21.05%  |
| WDC                 | 3         | 6      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 26     | 90%     |
| SSD  | 2         | 2      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 82        | 127    | 46.33%  |
| Detected | 73        | 109    | 41.24%  |
| Malfunc  | 20        | 28     | 11.3%   |
| Failed   | 2         | 2      | 1.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 67.34%  |
| AMD                          | 20        | 10.05%  |
| Samsung Electronics          | 12        | 6.03%   |
| SK hynix                     | 7         | 3.52%   |
| SanDisk                      | 7         | 3.52%   |
| KIOXIA                       | 4         | 2.01%   |
| Toshiba America Info Systems | 3         | 1.51%   |
| Micron Technology            | 3         | 1.51%   |
| Kingston Technology Company  | 3         | 1.51%   |
| Union Memory (Shenzhen)      | 2         | 1.01%   |
| Silicon Motion               | 1         | 0.5%    |
| Phison Electronics           | 1         | 0.5%    |
| Nvidia                       | 1         | 0.5%    |
| ADATA Technology             | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 8.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 8.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 6.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 4.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 3.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 3.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 3.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 3.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.79%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.33%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.4%    |
| Micron Non-Volatile memory controller                                            | 3         | 1.4%    |
| Intel SSD 660P Series                                                            | 3         | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.93%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.93%   |
| SK hynix BC511                                                                   | 2         | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.93%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.93%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 137       | 65.55%  |
| NVMe | 45        | 21.53%  |
| IDE  | 16        | 7.66%   |
| RAID | 11        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 139       | 82.74%  |
| AMD    | 29        | 17.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.98%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.98%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 2.38%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.79%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.79%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.79%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.19%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.19%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.19%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.19%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.19%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 1.19%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.19%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.19%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.6%    |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.6%    |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 0.6%    |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.6%    |
| Intel Genuine CPU T2060 @ 1.60GHz             | 1         | 0.6%    |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.6%    |
| Intel Genuine CPU 575 @ 2.00GHz               | 1         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 25.6%   |
| Intel Core i7           | 29        | 17.26%  |
| Intel Core i3           | 18        | 10.71%  |
| Intel Core 2 Duo        | 12        | 7.14%   |
| Intel Celeron           | 12        | 7.14%   |
| Other                   | 10        | 5.95%   |
| AMD Ryzen 5             | 7         | 4.17%   |
| Intel Pentium           | 5         | 2.98%   |
| AMD Ryzen 7             | 5         | 2.98%   |
| Intel Pentium Dual-Core | 3         | 1.79%   |
| Intel Pentium Dual      | 3         | 1.79%   |
| Intel Genuine           | 3         | 1.79%   |
| Intel Core 2            | 2         | 1.19%   |
| AMD Ryzen 3             | 2         | 1.19%   |
| AMD E1                  | 2         | 1.19%   |
| AMD A8                  | 2         | 1.19%   |
| AMD A10                 | 2         | 1.19%   |
| Intel Xeon              | 1         | 0.6%    |
| Intel Atom              | 1         | 0.6%    |
| AMD Turion 64 X2 Mobile | 1         | 0.6%    |
| AMD Ryzen 7 PRO         | 1         | 0.6%    |
| AMD Ryzen 5 PRO         | 1         | 0.6%    |
| AMD E2                  | 1         | 0.6%    |
| AMD E                   | 1         | 0.6%    |
| AMD C-70                | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 103       | 60.95%  |
| 4      | 49        | 28.99%  |
| 6      | 7         | 4.14%   |
| 8      | 5         | 2.96%   |
| 1      | 4         | 2.37%   |
| 14     | 1         | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 68.05%  |
| 1      | 54        | 31.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 166       | 98.81%  |
| 32-bit         | 1         | 0.6%    |
| Unknown        | 1         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 17.54%  |
| 0x406e3    | 11        | 6.43%   |
| 0x306a9    | 11        | 6.43%   |
| 0x206a7    | 9         | 5.26%   |
| 0x6fd      | 7         | 4.09%   |
| 0x30678    | 7         | 4.09%   |
| 0x20655    | 7         | 4.09%   |
| 0x306d4    | 6         | 3.51%   |
| 0x1067a    | 6         | 3.51%   |
| 0x906ea    | 5         | 2.92%   |
| 0x806c1    | 5         | 2.92%   |
| 0x806ec    | 4         | 2.34%   |
| 0x40651    | 4         | 2.34%   |
| 0x306c3    | 4         | 2.34%   |
| 0x08108102 | 4         | 2.34%   |
| 0x906e9    | 3         | 1.75%   |
| 0x806ea    | 3         | 1.75%   |
| 0x806e9    | 3         | 1.75%   |
| 0x10676    | 3         | 1.75%   |
| 0x06001119 | 3         | 1.75%   |
| 0x05000119 | 3         | 1.75%   |
| 0xa0652    | 2         | 1.17%   |
| 0x6f6      | 2         | 1.17%   |
| 0x506e3    | 2         | 1.17%   |
| 0x406c3    | 2         | 1.17%   |
| 0x20652    | 2         | 1.17%   |
| 0x08600103 | 2         | 1.17%   |
| 0x08108109 | 2         | 1.17%   |
| 0x906ed    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x806d1    | 1         | 0.58%   |
| 0x706a8    | 1         | 0.58%   |
| 0x706a1    | 1         | 0.58%   |
| 0x6fb      | 1         | 0.58%   |
| 0x6fa      | 1         | 0.58%   |
| 0x6ec      | 1         | 0.58%   |
| 0x506c9    | 1         | 0.58%   |
| 0x30673    | 1         | 0.58%   |
| 0x106e5    | 1         | 0.58%   |
| 0x10661    | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 14.88%  |
| Skylake       | 16        | 9.52%   |
| Core          | 14        | 8.33%   |
| IvyBridge     | 13        | 7.74%   |
| Silvermont    | 11        | 6.55%   |
| Haswell       | 11        | 6.55%   |
| Westmere      | 10        | 5.95%   |
| SandyBridge   | 10        | 5.95%   |
| Penryn        | 9         | 5.36%   |
| Zen+          | 8         | 4.76%   |
| Zen 2         | 7         | 4.17%   |
| Broadwell     | 6         | 3.57%   |
| TigerLake     | 5         | 2.98%   |
| Piledriver    | 3         | 1.79%   |
| Bobcat        | 3         | 1.79%   |
| Puma          | 2         | 1.19%   |
| Goldmont plus | 2         | 1.19%   |
| Excavator     | 2         | 1.19%   |
| CometLake     | 2         | 1.19%   |
| Unknown       | 2         | 1.19%   |
| Zen 3         | 1         | 0.6%    |
| P6            | 1         | 0.6%    |
| Nehalem       | 1         | 0.6%    |
| K8 Hammer     | 1         | 0.6%    |
| Jaguar        | 1         | 0.6%    |
| Icelake       | 1         | 0.6%    |
| Goldmont      | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 119       | 57.49%  |
| Nvidia | 50        | 24.15%  |
| AMD    | 38        | 18.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 6.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 5.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 4.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.26%   |
| AMD Renoir                                                                               | 7         | 3.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.4%    |
| Intel UHD Graphics 620                                                                   | 3         | 1.4%    |
| Intel HD Graphics 620                                                                    | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.93%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.93%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.93%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.47%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.47%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.47%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 81        | 48.21%  |
| Intel + Nvidia | 31        | 18.45%  |
| 1 x AMD        | 26        | 15.48%  |
| 1 x Nvidia     | 17        | 10.12%  |
| Intel + AMD    | 6         | 3.57%   |
| 2 x AMD        | 4         | 2.38%   |
| AMD + Nvidia   | 2         | 1.19%   |
| 2 x Intel      | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 140       | 80%     |
| Proprietary | 29        | 16.57%  |
| Unknown     | 6         | 3.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 51.14%  |
| 1.01-2.0   | 37        | 21.02%  |
| 0.01-0.5   | 24        | 13.64%  |
| 0.51-1.0   | 11        | 6.25%   |
| 3.01-4.0   | 9         | 5.11%   |
| 7.01-8.0   | 3         | 1.7%    |
| 5.01-6.0   | 2         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 23.28%  |
| LG Display              | 31        | 16.4%   |
| Samsung Electronics     | 26        | 13.76%  |
| BOE                     | 22        | 11.64%  |
| Chimei Innolux          | 19        | 10.05%  |
| Dell                    | 12        | 6.35%   |
| Lenovo                  | 4         | 2.12%   |
| Goldstar                | 4         | 2.12%   |
| PANDA                   | 3         | 1.59%   |
| Chi Mei Optoelectronics | 3         | 1.59%   |
| BenQ                    | 3         | 1.59%   |
| Sony                    | 2         | 1.06%   |
| Seiko/Epson             | 2         | 1.06%   |
| InfoVision              | 2         | 1.06%   |
| Hitachi                 | 2         | 1.06%   |
| Tianma XM               | 1         | 0.53%   |
| Sharp                   | 1         | 0.53%   |
| Quanta Display          | 1         | 0.53%   |
| Philips                 | 1         | 0.53%   |
| Panasonic               | 1         | 0.53%   |
| LGD                     | 1         | 0.53%   |
| LG Philips              | 1         | 0.53%   |
| Apple                   | 1         | 0.53%   |
| ANX                     | 1         | 0.53%   |
| Acer                    | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 1.54%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 1.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.54%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 1.54%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 2         | 1.03%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 2         | 1.03%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 1.03%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.03%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 2         | 1.03%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 2         | 1.03%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.51%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                 | 1         | 0.51%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.51%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.51%   |
| Seiko/Epson LCD Monitor 1366x768                                      | 1         | 0.51%   |
| Seiko/Epson LCD Monitor 1280x800                                      | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch  | 1         | 0.51%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.51%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 35.43%  |
| 1366x768 (WXGA)    | 61        | 34.86%  |
| 1600x900 (HD+)     | 13        | 7.43%   |
| 1280x800 (WXGA)    | 10        | 5.71%   |
| 3840x2160 (4K)     | 5         | 2.86%   |
| 2560x1440 (QHD)    | 5         | 2.86%   |
| 1440x900 (WXGA+)   | 4         | 2.29%   |
| 3440x1440          | 3         | 1.71%   |
| 1920x1200 (WUXGA)  | 2         | 1.14%   |
| 1280x1024 (SXGA)   | 2         | 1.14%   |
| 800x1280           | 1         | 0.57%   |
| 7680x2160          | 1         | 0.57%   |
| 3456x2160          | 1         | 0.57%   |
| 3000x2000          | 1         | 0.57%   |
| 2160x1440          | 1         | 0.57%   |
| 1680x1050 (WSXGA+) | 1         | 0.57%   |
| 1280x720 (HD)      | 1         | 0.57%   |
| Unknown            | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 92        | 48.17%  |
| 14      | 19        | 9.95%   |
| 17      | 17        | 8.9%    |
| 13      | 16        | 8.38%   |
| 12      | 11        | 5.76%   |
| 24      | 9         | 4.71%   |
| 27      | 5         | 2.62%   |
| Unknown | 5         | 2.62%   |
| 11      | 3         | 1.57%   |
| 40      | 2         | 1.05%   |
| 35      | 2         | 1.05%   |
| 21      | 2         | 1.05%   |
| 84      | 1         | 0.52%   |
| 43      | 1         | 0.52%   |
| 34      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 23      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 18      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 61.9%   |
| 351-400     | 21        | 11.11%  |
| 201-300     | 20        | 10.58%  |
| 501-600     | 15        | 7.94%   |
| Unknown     | 5         | 2.65%   |
| 801-900     | 4         | 2.12%   |
| 401-500     | 3         | 1.59%   |
| 701-800     | 1         | 0.53%   |
| 601-700     | 1         | 0.53%   |
| 1501-2000   | 1         | 0.53%   |
| 901-1000    | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 82.35%  |
| 16/10   | 17        | 10%     |
| Unknown | 4         | 2.35%   |
| 3/2     | 3         | 1.76%   |
| 21/9    | 3         | 1.76%   |
| 5/4     | 2         | 1.18%   |
| 0.62    | 1         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 47.37%  |
| 81-90          | 32        | 16.84%  |
| 121-130        | 14        | 7.37%   |
| 61-70          | 11        | 5.79%   |
| 201-250        | 11        | 5.79%   |
| 301-350        | 5         | 2.63%   |
| Unknown        | 5         | 2.63%   |
| 351-500        | 4         | 2.11%   |
| 71-80          | 3         | 1.58%   |
| 51-60          | 3         | 1.58%   |
| 501-1000       | 3         | 1.58%   |
| 151-200        | 2         | 1.05%   |
| 131-140        | 2         | 1.05%   |
| 91-100         | 2         | 1.05%   |
| More than 1000 | 1         | 0.53%   |
| 251-300        | 1         | 0.53%   |
| 141-150        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 75        | 39.68%  |
| 101-120       | 66        | 34.92%  |
| 51-100        | 31        | 16.4%   |
| 161-240       | 7         | 3.7%    |
| Unknown       | 5         | 2.65%   |
| More than 240 | 3         | 1.59%   |
| 1-50          | 2         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 138       | 80.7%   |
| 2     | 26        | 15.2%   |
| 0     | 4         | 2.34%   |
| 3     | 3         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 93        | 34.44%  |
| Intel                    | 88        | 32.59%  |
| Qualcomm Atheros         | 43        | 15.93%  |
| Broadcom                 | 17        | 6.3%    |
| Broadcom Limited         | 7         | 2.59%   |
| Marvell Technology Group | 4         | 1.48%   |
| Ralink                   | 3         | 1.11%   |
| TP-Link                  | 2         | 0.74%   |
| Ralink Technology        | 2         | 0.74%   |
| MediaTek                 | 2         | 0.74%   |
| Hewlett-Packard          | 2         | 0.74%   |
| Xiaomi                   | 1         | 0.37%   |
| vivo                     | 1         | 0.37%   |
| U-Blox                   | 1         | 0.37%   |
| Samsung Electronics      | 1         | 0.37%   |
| Nvidia                   | 1         | 0.37%   |
| Lenovo                   | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 17.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 7.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.4%    |
| Intel Wireless 8260                                               | 7         | 2.1%    |
| Intel Wireless 3160                                               | 7         | 2.1%    |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 5         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.2%    |
| Intel Wireless 7260                                               | 4         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 1.2%    |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.2%    |
| Intel Wireless 7265                                               | 3         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 3         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 50.58%  |
| Qualcomm Atheros      | 37        | 21.51%  |
| Realtek Semiconductor | 23        | 13.37%  |
| Broadcom              | 13        | 7.56%   |
| Ralink                | 3         | 1.74%   |
| Broadcom Limited      | 3         | 1.74%   |
| TP-Link               | 2         | 1.16%   |
| Ralink Technology     | 2         | 1.16%   |
| MediaTek              | 1         | 0.58%   |
| Hewlett-Packard       | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 5.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.65%   |
| Intel Wireless 8260                                                     | 7         | 4.07%   |
| Intel Wireless 3160                                                     | 7         | 4.07%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.91%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.33%   |
| Intel Wireless 7260                                                     | 4         | 2.33%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.33%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.33%   |
| Intel Wireless 7265                                                     | 3         | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.16%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.16%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.16%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.16%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 55.35%  |
| Intel                    | 35        | 22.01%  |
| Qualcomm Atheros         | 13        | 8.18%   |
| Broadcom                 | 8         | 5.03%   |
| Marvell Technology Group | 4         | 2.52%   |
| Broadcom Limited         | 4         | 2.52%   |
| Xiaomi                   | 1         | 0.63%   |
| vivo                     | 1         | 0.63%   |
| Samsung Electronics      | 1         | 0.63%   |
| Nvidia                   | 1         | 0.63%   |
| MediaTek                 | 1         | 0.63%   |
| Lenovo                   | 1         | 0.63%   |
| Huawei Technologies      | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 36.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 15.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.52%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.52%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.26%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.63%   |
| vivo 1806                                                         | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.63%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.63%   |
| MediaTek TECNO F1                                                 | 1         | 0.63%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.63%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.63%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 51.55%  |
| Ethernet | 154       | 47.83%  |
| Modem    | 2         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 82.76%  |
| Ethernet | 30        | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 144       | 85.71%  |
| 1     | 21        | 12.5%   |
| 3     | 2         | 1.19%   |
| 0     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 160       | 95.24%  |
| Yes  | 8         | 4.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 40.63%  |
| Realtek Semiconductor           | 14        | 10.94%  |
| IMC Networks                    | 12        | 9.38%   |
| Lite-On Technology              | 11        | 8.59%   |
| Qualcomm Atheros Communications | 10        | 7.81%   |
| Broadcom                        | 9         | 7.03%   |
| Dell                            | 5         | 3.91%   |
| Hewlett-Packard                 | 4         | 3.13%   |
| Toshiba                         | 3         | 2.34%   |
| Ralink                          | 2         | 1.56%   |
| Cambridge Silicon Radio         | 2         | 1.56%   |
| Qcom                            | 1         | 0.78%   |
| Foxconn / Hon Hai               | 1         | 0.78%   |
| ASUSTek Computer                | 1         | 0.78%   |
| Apple                           | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 23        | 17.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 7.03%   |
| Realtek Bluetooth Radio                             | 7         | 5.47%   |
| Intel AX200 Bluetooth                               | 6         | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.91%   |
| Intel AX201 Bluetooth                               | 5         | 3.91%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.34%   |
| Lite-On Bluetooth Device                            | 3         | 2.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.34%   |
| IMC Networks Bluetooth Device                       | 3         | 2.34%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.56%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.56%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.56%   |
| Intel AX210 Bluetooth                               | 2         | 1.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.56%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.56%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.56%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.56%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.78%   |
| Toshiba Bluetooth Device                            | 1         | 0.78%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.78%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.78%   |
| Lite-On BCM43142A0                                  | 1         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.78%   |
| Intel Bluetooth Device                              | 1         | 0.78%   |
| IMC Networks Wireless_Device                        | 1         | 0.78%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 138       | 67.32%  |
| AMD                   | 31        | 15.12%  |
| Nvidia                | 24        | 11.71%  |
| C-Media Electronics   | 3         | 1.46%   |
| Logitech              | 2         | 0.98%   |
| Realtek Semiconductor | 1         | 0.49%   |
| Microsoft             | 1         | 0.49%   |
| Lenovo                | 1         | 0.49%   |
| GYROCOM C&C           | 1         | 0.49%   |
| GN Netcom             | 1         | 0.49%   |
| Creative Technology   | 1         | 0.49%   |
| Apple                 | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 8.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 6.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 5.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.27%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.45%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.45%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.22%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.22%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.22%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.82%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 27.07%  |
| SK hynix            | 31        | 23.31%  |
| Kingston            | 20        | 15.04%  |
| Unknown             | 19        | 14.29%  |
| Micron Technology   | 12        | 9.02%   |
| G.Skill             | 3         | 2.26%   |
| Elpida              | 3         | 2.26%   |
| Ramaxel Technology  | 2         | 1.5%    |
| Crucial             | 2         | 1.5%    |
| Corsair             | 2         | 1.5%    |
| Toshiba             | 1         | 0.75%   |
| Goodram             | 1         | 0.75%   |
| A-DATA Technology   | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 3         | 2.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 2.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 2.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 2.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                       | 3         | 2.16%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                              | 2         | 1.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                               | 2         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.44%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                    | 2         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.44%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s                    | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                    | 2         | 1.44%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.44%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.44%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                               | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                               | 1         | 0.72%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                                | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DRAM                                          | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                  | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR                                        | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                    | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                              | 1         | 0.72%   |
| Unknown RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 1024MB SODIMM DDR2 667MT/s | 1         | 0.72%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                          | 1         | 0.72%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                           | 1         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                             | 1         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                             | 1         | 0.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                               | 1         | 0.72%   |
| SK hynix RAM HYMP564S64CP6-Y5 512MB SODIMM DDR 667MT/s                      | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 45.28%  |
| DDR4    | 40        | 37.74%  |
| DDR2    | 11        | 10.38%  |
| LPDDR4  | 3         | 2.83%   |
| SDRAM   | 1         | 0.94%   |
| DRAM    | 1         | 0.94%   |
| DDR     | 1         | 0.94%   |
| Unknown | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 96.23%  |
| Row Of Chips | 3         | 2.83%   |
| Chip         | 1         | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 45        | 38.79%  |
| 8192  | 37        | 31.9%   |
| 2048  | 22        | 18.97%  |
| 16384 | 7         | 6.03%   |
| 1024  | 3         | 2.59%   |
| 32768 | 1         | 0.86%   |
| 512   | 1         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 25.64%  |
| 2667    | 22        | 18.8%   |
| 1334    | 11        | 9.4%    |
| 1333    | 9         | 7.69%   |
| 3200    | 8         | 6.84%   |
| 2133    | 7         | 5.98%   |
| 667     | 7         | 5.98%   |
| 2400    | 6         | 5.13%   |
| 1066    | 3         | 2.56%   |
| Unknown | 3         | 2.56%   |
| 4267    | 2         | 1.71%   |
| 1067    | 2         | 1.71%   |
| 800     | 2         | 1.71%   |
| 4199    | 1         | 0.85%   |
| 3266    | 1         | 0.85%   |
| 1867    | 1         | 0.85%   |
| 975     | 1         | 0.85%   |
| 200     | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 66.67%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung SCX-4100 Scanner | 1         | 33.33%  |
| Samsung SCX-3200 Series  | 1         | 33.33%  |
| HP LaserJet 1018         | 1         | 33.33%  |

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
| Chicony Electronics                    | 38        | 26.57%  |
| IMC Networks                           | 18        | 12.59%  |
| Realtek Semiconductor                  | 15        | 10.49%  |
| Acer                                   | 10        | 6.99%   |
| Microdia                               | 9         | 6.29%   |
| Suyin                                  | 8         | 5.59%   |
| Sunplus Innovation Technology          | 7         | 4.9%    |
| Quanta                                 | 7         | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.2%    |
| Syntek                                 | 5         | 3.5%    |
| Lite-On Technology                     | 5         | 3.5%    |
| Silicon Motion                         | 3         | 2.1%    |
| Luxvisions Innotech Limited            | 3         | 2.1%    |
| Ricoh                                  | 2         | 1.4%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| OmniVision Technologies                | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Genesys Logic                          | 1         | 0.7%    |
| DigiTech                               | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 4.14%   |
| Realtek Integrated_Webcam_HD                                | 5         | 3.45%   |
| Chicony Integrated Camera                                   | 5         | 3.45%   |
| Chicony HD WebCam                                           | 4         | 2.76%   |
| Sunplus Asus Webcam                                         | 3         | 2.07%   |
| Realtek USB Camera                                          | 3         | 2.07%   |
| Lite-On Integrated Camera                                   | 3         | 2.07%   |
| IMC Networks Integrated Camera                              | 3         | 2.07%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 2.07%   |
| Chicony HP HD Camera                                        | 3         | 2.07%   |
| Chicony HD User Facing                                      | 3         | 2.07%   |
| Acer Lenovo EasyCamera                                      | 3         | 2.07%   |
| Acer Integrated Camera                                      | 3         | 2.07%   |
| Suyin HD WebCam                                             | 2         | 1.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1.38%   |
| Realtek Integrated Webcam                                   | 2         | 1.38%   |
| Realtek HP Webcam                                           | 2         | 1.38%   |
| Quanta HD Webcam                                            | 2         | 1.38%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.38%   |
| Microdia Integrated Webcam                                  | 2         | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.38%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.38%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.38%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.38%   |
| Chicony HP HD Webcam                                        | 2         | 1.38%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.38%   |
| Acer BisonCam, NB Pro                                       | 2         | 1.38%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.69%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.69%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.69%   |
| Syntek Integrated Camera                                    | 1         | 0.69%   |
| Syntek EasyCamera                                           | 1         | 0.69%   |
| Suyin WebCam                                                | 1         | 0.69%   |
| Suyin HD Video WebCam                                       | 1         | 0.69%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.69%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.69%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 48.48%  |
| Synaptics                  | 6         | 18.18%  |
| AuthenTec                  | 3         | 9.09%   |
| Upek                       | 2         | 6.06%   |
| STMicroelectronics         | 2         | 6.06%   |
| Elan Microelectronics      | 2         | 6.06%   |
| Shenzhen Goodix Technology | 1         | 3.03%   |
| LighTuning Technology      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 12.12%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 9.09%   |
| Validity Sensors VFS491                                                    | 2         | 6.06%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.06%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 6.06%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 6.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.03%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.03%   |
| AuthenTec AES1600                                                          | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 52.63%  |
| Broadcom    | 5         | 26.32%  |
| Lenovo      | 2         | 10.53%  |
| Upek        | 1         | 5.26%   |
| O2 Micro    | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 52.63%  |
| Broadcom 58200                                             | 4         | 21.05%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 10.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 5.26%   |
| Broadcom 5880                                              | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 108       | 62.07%  |
| 1     | 49        | 28.16%  |
| 2     | 16        | 9.2%    |
| 3     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 41.25%  |
| Graphics card            | 16        | 20%     |
| Chipcard                 | 15        | 18.75%  |
| Net/wireless             | 5         | 6.25%   |
| Multimedia controller    | 4         | 5%      |
| Communication controller | 2         | 2.5%    |
| Camera                   | 2         | 2.5%    |
| Bluetooth                | 2         | 2.5%    |
| Card reader              | 1         | 1.25%   |

