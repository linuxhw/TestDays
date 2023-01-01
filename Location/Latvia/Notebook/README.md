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

Total: 272

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | G62                         | [4d80c95e73](https://linux-hardware.org/?probe=4d80c95e73) | Dec 18, 2022 |
| Dell          | Inspiron N5050              | [cc139ec3a3](https://linux-hardware.org/?probe=cc139ec3a3) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [b3c750c720](https://linux-hardware.org/?probe=b3c750c720) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| ASUSTek       | X550MD                      | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| ASUSTek       | F3Sg                        | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
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
| Ubuntu 20.04       | 22        | 10.89%  |
| ROSA R11           | 14        | 6.93%   |
| Ubuntu 18.04       | 9         | 4.46%   |
| ROSA R9            | 7         | 3.47%   |
| ROSA R10           | 6         | 2.97%   |
| Arch               | 6         | 2.97%   |
| ROSA R8.1          | 5         | 2.48%   |
| ROSA R11.1         | 5         | 2.48%   |
| Debian 11          | 5         | 2.48%   |
| ROSA R8            | 4         | 1.98%   |
| Pop!_OS 21.04      | 4         | 1.98%   |
| Pop!_OS 20.10      | 4         | 1.98%   |
| OpenMandriva 4.3   | 4         | 1.98%   |
| Manjaro            | 4         | 1.98%   |
| Linux Mint 21      | 4         | 1.98%   |
| ArcoLinux Rolling  | 4         | 1.98%   |
| Ubuntu 19.10       | 3         | 1.49%   |
| ROSA 12.1          | 3         | 1.49%   |
| Pop!_OS 22.04      | 3         | 1.49%   |
| Linux Mint 20.3    | 3         | 1.49%   |
| Linux Mint 19      | 3         | 1.49%   |
| Linux Mint 18.3    | 3         | 1.49%   |
| KDE neon 20.04     | 3         | 1.49%   |
| Arch Rolling       | 3         | 1.49%   |
| Ubuntu 22.04       | 2         | 0.99%   |
| Ubuntu 21.10       | 2         | 0.99%   |
| Ubuntu 21.04       | 2         | 0.99%   |
| Ubuntu 20.10       | 2         | 0.99%   |
| ROSA 12.2          | 2         | 0.99%   |
| Pop!_OS 21.10      | 2         | 0.99%   |
| OpenMandriva 4.50  | 2         | 0.99%   |
| Linux Mint 20.1    | 2         | 0.99%   |
| Linux Mint 20      | 2         | 0.99%   |
| KDE neon 22.04     | 2         | 0.99%   |
| Fedora 34          | 2         | 0.99%   |
| Debian Testing     | 2         | 0.99%   |
| Debian 10          | 2         | 0.99%   |
| Xubuntu 21.04      | 1         | 0.5%    |
| Xubuntu 20.04      | 1         | 0.5%    |
| Void Linux Rolling | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 45        | 25.14%  |
| ROSA          | 32        | 17.88%  |
| Linux Mint    | 18        | 10.06%  |
| Pop!_OS       | 12        | 6.7%    |
| Debian        | 9         | 5.03%   |
| Arch          | 9         | 5.03%   |
| Manjaro       | 8         | 4.47%   |
| OpenMandriva  | 7         | 3.91%   |
| Fedora        | 6         | 3.35%   |
| KDE neon      | 5         | 2.79%   |
| ArcoLinux     | 5         | 2.79%   |
| Elementary    | 3         | 1.68%   |
| Xubuntu       | 2         | 1.12%   |
| Ubuntu Unity  | 2         | 1.12%   |
| openSUSE      | 2         | 1.12%   |
| Kali          | 2         | 1.12%   |
| Endless       | 2         | 1.12%   |
| Void Linux    | 1         | 0.56%   |
| Ubuntu Budgie | 1         | 0.56%   |
| SteamOS       | 1         | 0.56%   |
| Solus         | 1         | 0.56%   |
| Peppermint    | 1         | 0.56%   |
| Parrot        | 1         | 0.56%   |
| MX            | 1         | 0.56%   |
| GNOME OS      | 1         | 0.56%   |
| Garuda Linux  | 1         | 0.56%   |
| EndeavourOS   | 1         | 0.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.73%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.73%   |
| 5.4.0-42-generic                   | 4         | 1.82%   |
| 5.16.7-desktop-1omv4003            | 4         | 1.82%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.82%   |
| 5.8.0-7630-generic                 | 3         | 1.36%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.36%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.36%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.36%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.36%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.36%   |
| 5.8.0-48-generic                   | 2         | 0.91%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.91%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.91%   |
| 5.4.0-80-generic                   | 2         | 0.91%   |
| 5.4.0-26-generic                   | 2         | 0.91%   |
| 5.15.0-56-generic                  | 2         | 0.91%   |
| 5.15.0-46-generic                  | 2         | 0.91%   |
| 5.13.6-arch1-1                     | 2         | 0.91%   |
| 5.13.0-25-generic                  | 2         | 0.91%   |
| 5.11.0-43-generic                  | 2         | 0.91%   |
| 5.10.0-8-amd64                     | 2         | 0.91%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.91%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.91%   |
| 4.18.0-18-generic                  | 2         | 0.91%   |
| 4.15.0-54-generic                  | 2         | 0.91%   |
| 4.10.0-38-generic                  | 2         | 0.91%   |
| 6.0.9_1                            | 1         | 0.45%   |
| 6.0.8-AMD-znver2                   | 1         | 0.45%   |
| 6.0.6-76060006-generic             | 1         | 0.45%   |
| 6.0.2-xm1.0.fc37.x86_64            | 1         | 0.45%   |
| 6.0.10-1-default                   | 1         | 0.45%   |
| 5.9.8-2-MANJARO                    | 1         | 0.45%   |
| 5.9.0-5-amd64                      | 1         | 0.45%   |
| 5.8.16-2-MANJARO                   | 1         | 0.45%   |
| 5.8.13-050813-generic              | 1         | 0.45%   |
| 5.8.0-53-generic                   | 1         | 0.45%   |
| 5.8.0-45-generic                   | 1         | 0.45%   |
| 5.8.0-33-generic                   | 1         | 0.45%   |
| 5.8.0-29-generic                   | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 13.15%  |
| 4.15.0  | 22        | 10.33%  |
| 5.11.0  | 11        | 5.16%   |
| 5.8.0   | 10        | 4.69%   |
| 5.13.0  | 10        | 4.69%   |
| 5.15.0  | 8         | 3.76%   |
| 5.3.0   | 6         | 2.82%   |
| 5.10.0  | 6         | 2.82%   |
| 4.9.20  | 6         | 2.82%   |
| 5.16.7  | 4         | 1.88%   |
| 5.10.74 | 4         | 1.88%   |
| 5.0.0   | 4         | 1.88%   |
| 4.18.0  | 4         | 1.88%   |
| 5.17.1  | 3         | 1.41%   |
| 4.9.60  | 3         | 1.41%   |
| 4.9.41  | 3         | 1.41%   |
| 4.9.155 | 3         | 1.41%   |
| 4.1.34  | 3         | 1.41%   |
| 5.4.83  | 2         | 0.94%   |
| 5.4.72  | 2         | 0.94%   |
| 5.4.32  | 2         | 0.94%   |
| 5.14.0  | 2         | 0.94%   |
| 5.13.6  | 2         | 0.94%   |
| 5.13.12 | 2         | 0.94%   |
| 5.12.14 | 2         | 0.94%   |
| 4.9.9   | 2         | 0.94%   |
| 4.9.124 | 2         | 0.94%   |
| 4.4.0   | 2         | 0.94%   |
| 4.10.0  | 2         | 0.94%   |
| 4.1.38  | 2         | 0.94%   |
| 6.0.9   | 1         | 0.47%   |
| 6.0.8   | 1         | 0.47%   |
| 6.0.6   | 1         | 0.47%   |
| 6.0.2   | 1         | 0.47%   |
| 6.0.10  | 1         | 0.47%   |
| 5.9.8   | 1         | 0.47%   |
| 5.9.0   | 1         | 0.47%   |
| 5.8.16  | 1         | 0.47%   |
| 5.8.13  | 1         | 0.47%   |
| 5.7.5   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 16.18%  |
| 4.15    | 22        | 10.78%  |
| 4.9     | 16        | 7.84%   |
| 5.15    | 15        | 7.35%   |
| 5.13    | 14        | 6.86%   |
| 5.10    | 13        | 6.37%   |
| 5.8     | 12        | 5.88%   |
| 5.11    | 11        | 5.39%   |
| 5.16    | 7         | 3.43%   |
| 5.3     | 6         | 2.94%   |
| 5.12    | 6         | 2.94%   |
| 6.0     | 5         | 2.45%   |
| 5.19    | 4         | 1.96%   |
| 5.18    | 4         | 1.96%   |
| 5.17    | 4         | 1.96%   |
| 5.14    | 4         | 1.96%   |
| 5.0     | 4         | 1.96%   |
| 4.18    | 4         | 1.96%   |
| 4.1     | 4         | 1.96%   |
| 5.5     | 3         | 1.47%   |
| 5.9     | 2         | 0.98%   |
| 4.4     | 2         | 0.98%   |
| 4.19    | 2         | 0.98%   |
| 4.10    | 2         | 0.98%   |
| 5.7     | 1         | 0.49%   |
| 5.6     | 1         | 0.49%   |
| 5.2     | 1         | 0.49%   |
| 4.20    | 1         | 0.49%   |
| 4.13    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 166       | 94.86%  |
| i686   | 9         | 5.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 69        | 36.7%   |
| KDE5       | 34        | 18.09%  |
| KDE4       | 24        | 12.77%  |
| Unknown    | 17        | 9.04%   |
| XFCE       | 14        | 7.45%   |
| MATE       | 8         | 4.26%   |
| X-Cinnamon | 5         | 2.66%   |
| Budgie     | 4         | 2.13%   |
| Pantheon   | 3         | 1.6%    |
| KDE        | 3         | 1.6%    |
| Unity      | 2         | 1.06%   |
| LXQt       | 2         | 1.06%   |
| Cinnamon   | 2         | 1.06%   |
| LXDE       | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 146       | 80.66%  |
| Wayland | 24        | 13.26%  |
| Unknown | 8         | 4.42%   |
| Tty     | 3         | 1.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 38.46%  |
| GDM     | 30        | 16.48%  |
| SDDM    | 26        | 14.29%  |
| KDM     | 24        | 13.19%  |
| LightDM | 13        | 7.14%   |
| TDM     | 11        | 6.04%   |
| GDM3    | 5         | 2.75%   |
| SLiM    | 1         | 0.55%   |
| MDM     | 1         | 0.55%   |
| LDM     | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 89        | 48.9%   |
| Unknown     | 43        | 23.63%  |
| lv_LV       | 18        | 9.89%   |
| ru_RU       | 17        | 9.34%   |
| en_GB       | 9         | 4.95%   |
| C           | 3         | 1.65%   |
| ru_RU.UTF_8 | 1         | 0.55%   |
| POSIX       | 1         | 0.55%   |
| de_DE       | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 93        | 52.54%  |
| EFI  | 84        | 47.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 136       | 75.98%  |
| Btrfs   | 16        | 8.94%   |
| Unknown | 16        | 8.94%   |
| Overlay | 10        | 5.59%   |
| Zfs     | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 44.44%  |
| GPT     | 64        | 35.56%  |
| MBR     | 36        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 89.07%  |
| Yes       | 20        | 10.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 73.74%  |
| Yes       | 47        | 26.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 22.86%  |
| ASUSTek Computer    | 30        | 17.14%  |
| Hewlett-Packard     | 29        | 16.57%  |
| Dell                | 25        | 14.29%  |
| Acer                | 21        | 12%     |
| Toshiba             | 6         | 3.43%   |
| MSI                 | 5         | 2.86%   |
| Samsung Electronics | 4         | 2.29%   |
| HUAWEI              | 2         | 1.14%   |
| Fujitsu Siemens     | 2         | 1.14%   |
| Wortmann AG         | 1         | 0.57%   |
| Valve               | 1         | 0.57%   |
| Timi                | 1         | 0.57%   |
| Sony                | 1         | 0.57%   |
| Razer               | 1         | 0.57%   |
| Quanta              | 1         | 0.57%   |
| Packard Bell        | 1         | 0.57%   |
| Fujitsu             | 1         | 0.57%   |
| eMachines           | 1         | 0.57%   |
| Apple               | 1         | 0.57%   |
| Advent              | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.71%   |
| Toshiba Satellite C660                                | 2         | 1.14%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.14%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 1.14%   |
| HP G62                                                | 2         | 1.14%   |
| HP EliteBook 8440p                                    | 2         | 1.14%   |
| HP 250 G6 Notebook PC                                 | 2         | 1.14%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 1.14%   |
| ASUS X553MA                                           | 2         | 1.14%   |
| ASUS X551MA                                           | 2         | 1.14%   |
| Wortmann AG CR700                                     | 1         | 0.57%   |
| Valve Jupiter                                         | 1         | 0.57%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.57%   |
| Toshiba Satellite L750                                | 1         | 0.57%   |
| Toshiba Satellite L350                                | 1         | 0.57%   |
| Toshiba Satellite C50D-B                              | 1         | 0.57%   |
| Timi A35S                                             | 1         | 0.57%   |
| Sony VPCCW2S8E                                        | 1         | 0.57%   |
| Samsung R528/R728                                     | 1         | 0.57%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.57%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.57%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.57%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.57%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.57%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.57%   |
| MSI Modern 14 B4MW                                    | 1         | 0.57%   |
| MSI GV72 7RE                                          | 1         | 0.57%   |
| MSI GT62VR 6RE                                        | 1         | 0.57%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.57%   |
| MSI GF63 Thin 9RCX                                    | 1         | 0.57%   |
| Lenovo Y50-70 20378                                   | 1         | 0.57%   |
| Lenovo V110-15IAP 80TG                                | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S5Q200                       | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.57%   |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.57%   |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291Q50                          | 1         | 0.57%   |
| Lenovo ThinkPad X201 Tablet 311396U                   | 1         | 0.57%   |
| Lenovo ThinkPad T60 8741W3M                           | 1         | 0.57%   |
| Lenovo ThinkPad T495 20NK000HMH                       | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 22        | 12.57%  |
| Acer Aspire           | 13        | 7.43%   |
| HP EliteBook          | 11        | 6.29%   |
| Dell Inspiron         | 11        | 6.29%   |
| Lenovo IdeaPad        | 9         | 5.14%   |
| Dell Latitude         | 9         | 5.14%   |
| Toshiba Satellite     | 6         | 3.43%   |
| HP ProBook            | 5         | 2.86%   |
| HP Pavilion           | 4         | 2.29%   |
| ASUS VivoBook         | 4         | 2.29%   |
| HP 250                | 3         | 1.71%   |
| Lenovo Legion         | 2         | 1.14%   |
| HP Laptop             | 2         | 1.14%   |
| HP G62                | 2         | 1.14%   |
| Dell XPS              | 2         | 1.14%   |
| ASUS ZenBook          | 2         | 1.14%   |
| ASUS X553MA           | 2         | 1.14%   |
| ASUS X551MA           | 2         | 1.14%   |
| ASUS TUF              | 2         | 1.14%   |
| Acer Nitro            | 2         | 1.14%   |
| Wortmann AG CR700     | 1         | 0.57%   |
| Valve Jupiter         | 1         | 0.57%   |
| Timi A35S             | 1         | 0.57%   |
| Sony VPCCW2S8E        | 1         | 0.57%   |
| Samsung R528          | 1         | 0.57%   |
| Samsung 355V4C        | 1         | 0.57%   |
| Samsung 350V5C        | 1         | 0.57%   |
| Samsung 300V3A        | 1         | 0.57%   |
| Razer Blade           | 1         | 0.57%   |
| Quanta TW8            | 1         | 0.57%   |
| Packard Bell EasyNote | 1         | 0.57%   |
| MSI Modern            | 1         | 0.57%   |
| MSI GV72              | 1         | 0.57%   |
| MSI GT62VR            | 1         | 0.57%   |
| MSI GP75              | 1         | 0.57%   |
| MSI GF63              | 1         | 0.57%   |
| Lenovo Y50-70         | 1         | 0.57%   |
| Lenovo V110-15IAP     | 1         | 0.57%   |
| Lenovo ThinkBook      | 1         | 0.57%   |
| Lenovo G70-80         | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 18        | 10.29%  |
| 2013 | 17        | 9.71%   |
| 2014 | 15        | 8.57%   |
| 2020 | 14        | 8%      |
| 2010 | 13        | 7.43%   |
| 2018 | 12        | 6.86%   |
| 2015 | 12        | 6.86%   |
| 2011 | 12        | 6.86%   |
| 2017 | 10        | 5.71%   |
| 2008 | 10        | 5.71%   |
| 2016 | 9         | 5.14%   |
| 2012 | 9         | 5.14%   |
| 2021 | 7         | 4%      |
| 2007 | 7         | 4%      |
| 2009 | 6         | 3.43%   |
| 2022 | 2         | 1.14%   |
| 2006 | 2         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 175       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 160       | 90.4%   |
| Enabled  | 17        | 9.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 174       | 99.43%  |
| Yes  | 1         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 53        | 30.11%  |
| 4.01-8.0   | 48        | 27.27%  |
| 8.01-16.0  | 26        | 14.77%  |
| 16.01-24.0 | 24        | 13.64%  |
| 32.01-64.0 | 8         | 4.55%   |
| 1.01-2.0   | 7         | 3.98%   |
| 2.01-3.0   | 6         | 3.41%   |
| 24.01-32.0 | 2         | 1.14%   |
| 0.51-1.0   | 2         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 64        | 32.99%  |
| 2.01-3.0   | 50        | 25.77%  |
| 0.51-1.0   | 25        | 12.89%  |
| 4.01-8.0   | 24        | 12.37%  |
| 3.01-4.0   | 20        | 10.31%  |
| 8.01-16.0  | 8         | 4.12%   |
| 16.01-24.0 | 2         | 1.03%   |
| 0.01-0.5   | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 71.75%  |
| 2      | 43        | 24.29%  |
| 3      | 4         | 2.26%   |
| 0      | 2         | 1.13%   |
| 4      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 57.87%  |
| Yes       | 75        | 42.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 90.96%  |
| No        | 16        | 9.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 98.86%  |
| No        | 2         | 1.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 75.28%  |
| No        | 44        | 24.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 175       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 134       | 72.04%  |
| Liepāja                | 6         | 3.23%   |
| Jelgava                 | 6         | 3.23%   |
| Daugavpils              | 6         | 3.23%   |
| Jūrmala                | 3         | 1.61%   |
| Adazi                   | 3         | 1.61%   |
| Valmiera                | 2         | 1.08%   |
| Saulkrasti              | 2         | 1.08%   |
| Malpils                 | 2         | 1.08%   |
| Jaunmarupe              | 2         | 1.08%   |
| Cēsis                  | 2         | 1.08%   |
| Zvejniekciems           | 1         | 0.54%   |
| Ventspils               | 1         | 0.54%   |
| Ulbroka                 | 1         | 0.54%   |
| Tukums                  | 1         | 0.54%   |
| Tiraine                 | 1         | 0.54%   |
| Saldus                  | 1         | 0.54%   |
| Pļaviņas              | 1         | 0.54%   |
| Lizums                  | 1         | 0.54%   |
| Limbaži                | 1         | 0.54%   |
| Kuldīga                | 1         | 0.54%   |
| Jēkabpils Municipality | 1         | 0.54%   |
| Jēkabpils              | 1         | 0.54%   |
| Iecava                  | 1         | 0.54%   |
| Garkalne                | 1         | 0.54%   |
| Garciems                | 1         | 0.54%   |
| Dobele                  | 1         | 0.54%   |
| Aizpute                 | 1         | 0.54%   |
| Aizkraukle              | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 35        | 45     | 16.43%  |
| Seagate                 | 29        | 35     | 13.62%  |
| Kingston                | 24        | 29     | 11.27%  |
| Toshiba                 | 23        | 26     | 10.8%   |
| WDC                     | 20        | 29     | 9.39%   |
| Hitachi                 | 10        | 13     | 4.69%   |
| SK hynix                | 7         | 7      | 3.29%   |
| SanDisk                 | 7         | 14     | 3.29%   |
| HGST                    | 7         | 15     | 3.29%   |
| Unknown                 | 6         | 7      | 2.82%   |
| Micron Technology       | 6         | 6      | 2.82%   |
| A-DATA Technology       | 5         | 6      | 2.35%   |
| Patriot                 | 4         | 8      | 1.88%   |
| KIOXIA                  | 3         | 4      | 1.41%   |
| Intel                   | 3         | 5      | 1.41%   |
| Crucial                 | 3         | 3      | 1.41%   |
| LITEON                  | 2         | 2      | 0.94%   |
| Verbatim                | 1         | 1      | 0.47%   |
| USB                     | 1         | 1      | 0.47%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.47%   |
| SPCC                    | 1         | 1      | 0.47%   |
| Realtek                 | 1         | 1      | 0.47%   |
| PNY                     | 1         | 1      | 0.47%   |
| Plextor                 | 1         | 1      | 0.47%   |
| Phison                  | 1         | 1      | 0.47%   |
| OCZ                     | 1         | 1      | 0.47%   |
| Netac                   | 1         | 1      | 0.47%   |
| LITEONIT                | 1         | 1      | 0.47%   |
| Lexar                   | 1         | 1      | 0.47%   |
| KingSpec                | 1         | 1      | 0.47%   |
| Kingchuxing             | 1         | 2      | 0.47%   |
| Intenso                 | 1         | 1      | 0.47%   |
| Integral                | 1         | 1      | 0.47%   |
| Hrdtac                  | 1         | 2      | 0.47%   |
| Fujitsu                 | 1         | 1      | 0.47%   |
| China                   | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 6         | 2.73%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 2.27%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.82%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 1.82%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.82%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.82%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.36%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.36%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 1.36%   |
| Hitachi HTS545050B9A300 500GB       | 3         | 1.36%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.91%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.91%   |
| Toshiba MK8034GSX 80GB              | 2         | 0.91%   |
| Toshiba MK6465GSX 640GB             | 2         | 0.91%   |
| SK hynix HFM512GDJTNG-8310A 512GB   | 2         | 0.91%   |
| SK hynix BC511 NVMe 256GB           | 2         | 0.91%   |
| Seagate ST9160821AS 160GB           | 2         | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.91%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 2         | 0.91%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.91%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.91%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.91%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.91%   |
| Samsung HM321HI 320GB               | 2         | 0.91%   |
| Patriot Burst 240GB SSD             | 2         | 0.91%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 2         | 0.91%   |
| Kingston SV300S37A60G 64GB SSD      | 2         | 0.91%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.91%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.91%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.91%   |
| HGST HTS545050A7E680 500GB          | 2         | 0.91%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.45%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.45%   |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.45%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.45%   |
| WDC WD3200BEVT-75ZCT0 320GB         | 1         | 0.45%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.45%   |
| WDC WD3200BEVS-26VAT0 320GB         | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 33.33%  |
| Toshiba             | 18        | 21     | 20.69%  |
| WDC                 | 17        | 25     | 19.54%  |
| Hitachi             | 10        | 13     | 11.49%  |
| HGST                | 7         | 15     | 8.05%   |
| Samsung Electronics | 4         | 4      | 4.6%    |
| USB                 | 1         | 1      | 1.15%   |
| Fujitsu             | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 21        | 25     | 28.77%  |
| Samsung Electronics | 20        | 25     | 27.4%   |
| A-DATA Technology   | 5         | 6      | 6.85%   |
| Patriot             | 4         | 8      | 5.48%   |
| SanDisk             | 3         | 4      | 4.11%   |
| Micron Technology   | 3         | 3      | 4.11%   |
| Crucial             | 3         | 3      | 4.11%   |
| LITEON              | 2         | 2      | 2.74%   |
| Verbatim            | 1         | 1      | 1.37%   |
| Toshiba             | 1         | 1      | 1.37%   |
| SPCC                | 1         | 1      | 1.37%   |
| PNY                 | 1         | 1      | 1.37%   |
| Plextor             | 1         | 1      | 1.37%   |
| OCZ                 | 1         | 1      | 1.37%   |
| LITEONIT            | 1         | 1      | 1.37%   |
| Lexar               | 1         | 1      | 1.37%   |
| KingSpec            | 1         | 1      | 1.37%   |
| Intenso             | 1         | 1      | 1.37%   |
| Integral            | 1         | 1      | 1.37%   |
| China               | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 85        | 115    | 41.67%  |
| SSD     | 68        | 88     | 33.33%  |
| NVMe    | 45        | 62     | 22.06%  |
| MMC     | 4         | 5      | 1.96%   |
| Unknown | 2         | 5      | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 136       | 203    | 71.58%  |
| NVMe | 45        | 61     | 23.68%  |
| SAS  | 5         | 6      | 2.63%   |
| MMC  | 4         | 5      | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 142    | 68.87%  |
| 0.51-1.0   | 43        | 57     | 28.48%  |
| 1.01-2.0   | 4         | 4      | 2.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 31.09%  |
| 251-500        | 48        | 24.87%  |
| 501-1000       | 27        | 13.99%  |
| 1-20           | 16        | 8.29%   |
| 51-100         | 14        | 7.25%   |
| 1001-2000      | 13        | 6.74%   |
| 21-50          | 6         | 3.11%   |
| Unknown        | 5         | 2.59%   |
| 2001-3000      | 3         | 1.55%   |
| More than 3000 | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 83        | 43.46%  |
| 21-50     | 28        | 14.66%  |
| 101-250   | 22        | 11.52%  |
| 51-100    | 22        | 11.52%  |
| 251-500   | 15        | 7.85%   |
| 501-1000  | 10        | 5.24%   |
| 1001-2000 | 5         | 2.62%   |
| Unknown   | 5         | 2.62%   |
| 2001-3000 | 1         | 0.52%   |

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
| Works    | 86        | 133    | 46.74%  |
| Detected | 76        | 112    | 41.3%   |
| Malfunc  | 20        | 28     | 10.87%  |
| Failed   | 2         | 2      | 1.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 140       | 66.99%  |
| AMD                          | 21        | 10.05%  |
| Samsung Electronics          | 15        | 7.18%   |
| SK hynix                     | 7         | 3.35%   |
| SanDisk                      | 7         | 3.35%   |
| KIOXIA                       | 4         | 1.91%   |
| Toshiba America Info Systems | 3         | 1.44%   |
| Micron Technology            | 3         | 1.44%   |
| Kingston Technology Company  | 3         | 1.44%   |
| Union Memory (Shenzhen)      | 2         | 0.96%   |
| Silicon Motion               | 1         | 0.48%   |
| Phison Electronics           | 1         | 0.48%   |
| Nvidia                       | 1         | 0.48%   |
| ADATA Technology             | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 8.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 7.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 5.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 4.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 3.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 3.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 3.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 3.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.65%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.21%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 1.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.33%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.33%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.33%   |
| Intel SSD 660P Series                                                            | 3         | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.33%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.88%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.88%   |
| SK hynix BC511                                                                   | 2         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.88%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 65.45%  |
| NVMe | 48        | 21.82%  |
| IDE  | 17        | 7.73%   |
| RAID | 11        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 82.86%  |
| AMD    | 30        | 17.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.86%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.86%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 2.29%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.71%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.14%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.14%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.14%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.14%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.14%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 1.14%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1.14%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.14%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.57%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.57%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.57%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.57%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 0.57%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 45        | 25.71%  |
| Intel Core i7           | 29        | 16.57%  |
| Intel Core i3           | 18        | 10.29%  |
| Intel Core 2 Duo        | 13        | 7.43%   |
| Intel Celeron           | 12        | 6.86%   |
| Other                   | 10        | 5.71%   |
| Intel Pentium           | 8         | 4.57%   |
| AMD Ryzen 5             | 7         | 4%      |
| AMD Ryzen 7             | 6         | 3.43%   |
| Intel Pentium Dual-Core | 3         | 1.71%   |
| Intel Pentium Dual      | 3         | 1.71%   |
| Intel Genuine           | 3         | 1.71%   |
| Intel Core 2            | 2         | 1.14%   |
| AMD Ryzen 3             | 2         | 1.14%   |
| AMD E1                  | 2         | 1.14%   |
| AMD A8                  | 2         | 1.14%   |
| AMD A10                 | 2         | 1.14%   |
| Intel Xeon              | 1         | 0.57%   |
| Intel Atom              | 1         | 0.57%   |
| AMD Turion 64 X2 Mobile | 1         | 0.57%   |
| AMD Ryzen 7 PRO         | 1         | 0.57%   |
| AMD Ryzen 5 PRO         | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E                   | 1         | 0.57%   |
| AMD C-70                | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 60.23%  |
| 4      | 52        | 29.55%  |
| 6      | 7         | 3.98%   |
| 8      | 6         | 3.41%   |
| 1      | 4         | 2.27%   |
| 14     | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 175       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 118       | 67.05%  |
| 1      | 58        | 32.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 98.86%  |
| 32-bit         | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 17.98%  |
| 0x406e3    | 11        | 6.18%   |
| 0x306a9    | 11        | 6.18%   |
| 0x206a7    | 9         | 5.06%   |
| 0x30678    | 8         | 4.49%   |
| 0x6fd      | 7         | 3.93%   |
| 0x20655    | 7         | 3.93%   |
| 0x906ea    | 6         | 3.37%   |
| 0x306d4    | 6         | 3.37%   |
| 0x1067a    | 6         | 3.37%   |
| 0x806c1    | 5         | 2.81%   |
| 0x806ec    | 4         | 2.25%   |
| 0x40651    | 4         | 2.25%   |
| 0x306c3    | 4         | 2.25%   |
| 0x08108102 | 4         | 2.25%   |
| 0xa0652    | 3         | 1.69%   |
| 0x906e9    | 3         | 1.69%   |
| 0x806ea    | 3         | 1.69%   |
| 0x806e9    | 3         | 1.69%   |
| 0x10676    | 3         | 1.69%   |
| 0x06001119 | 3         | 1.69%   |
| 0x05000119 | 3         | 1.69%   |
| 0x6fa      | 2         | 1.12%   |
| 0x6f6      | 2         | 1.12%   |
| 0x506e3    | 2         | 1.12%   |
| 0x406c3    | 2         | 1.12%   |
| 0x20652    | 2         | 1.12%   |
| 0x0a50000c | 2         | 1.12%   |
| 0x08600103 | 2         | 1.12%   |
| 0x08108109 | 2         | 1.12%   |
| 0x906ed    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806d1    | 1         | 0.56%   |
| 0x706a8    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x6fb      | 1         | 0.56%   |
| 0x6ec      | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x30673    | 1         | 0.56%   |
| 0x106e5    | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 14.86%  |
| Skylake       | 16        | 9.14%   |
| Core          | 15        | 8.57%   |
| IvyBridge     | 13        | 7.43%   |
| Silvermont    | 12        | 6.86%   |
| Westmere      | 11        | 6.29%   |
| SandyBridge   | 11        | 6.29%   |
| Haswell       | 11        | 6.29%   |
| Penryn        | 9         | 5.14%   |
| Zen+          | 8         | 4.57%   |
| Zen 2         | 7         | 4%      |
| Broadwell     | 6         | 3.43%   |
| TigerLake     | 5         | 2.86%   |
| Piledriver    | 3         | 1.71%   |
| CometLake     | 3         | 1.71%   |
| Bobcat        | 3         | 1.71%   |
| Zen 3         | 2         | 1.14%   |
| Puma          | 2         | 1.14%   |
| Goldmont plus | 2         | 1.14%   |
| Excavator     | 2         | 1.14%   |
| Unknown       | 2         | 1.14%   |
| P6            | 1         | 0.57%   |
| Nehalem       | 1         | 0.57%   |
| K8 Hammer     | 1         | 0.57%   |
| Jaguar        | 1         | 0.57%   |
| Icelake       | 1         | 0.57%   |
| Goldmont      | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 57.08%  |
| Nvidia | 54        | 24.66%  |
| AMD    | 40        | 18.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 5.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 4.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.51%   |
| AMD Renoir                                                                               | 7         | 3.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.19%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.32%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.32%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.32%   |
| Intel HD Graphics 620                                                                    | 3         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.88%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.88%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.88%   |
| Intel HD Graphics 630                                                                    | 2         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.88%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.88%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.88%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 47.43%  |
| Intel + Nvidia | 34        | 19.43%  |
| 1 x AMD        | 26        | 14.86%  |
| 1 x Nvidia     | 17        | 9.71%   |
| Intel + AMD    | 7         | 4%      |
| 2 x AMD        | 4         | 2.29%   |
| AMD + Nvidia   | 3         | 1.71%   |
| 2 x Intel      | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 146       | 80.22%  |
| Proprietary | 30        | 16.48%  |
| Unknown     | 6         | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 51.37%  |
| 1.01-2.0   | 38        | 20.77%  |
| 0.01-0.5   | 24        | 13.11%  |
| 3.01-4.0   | 11        | 6.01%   |
| 0.51-1.0   | 11        | 6.01%   |
| 7.01-8.0   | 3         | 1.64%   |
| 5.01-6.0   | 2         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 23.59%  |
| LG Display              | 33        | 16.92%  |
| Samsung Electronics     | 26        | 13.33%  |
| BOE                     | 22        | 11.28%  |
| Chimei Innolux          | 19        | 9.74%   |
| Dell                    | 12        | 6.15%   |
| Chi Mei Optoelectronics | 5         | 2.56%   |
| Lenovo                  | 4         | 2.05%   |
| Goldstar                | 4         | 2.05%   |
| PANDA                   | 3         | 1.54%   |
| BenQ                    | 3         | 1.54%   |
| Sony                    | 2         | 1.03%   |
| Seiko/Epson             | 2         | 1.03%   |
| InfoVision              | 2         | 1.03%   |
| Hitachi                 | 2         | 1.03%   |
| Tianma XM               | 1         | 0.51%   |
| Sharp                   | 1         | 0.51%   |
| Quanta Display          | 1         | 0.51%   |
| Philips                 | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| LGD                     | 1         | 0.51%   |
| LG Philips              | 1         | 0.51%   |
| Apple                   | 1         | 0.51%   |
| ANX                     | 1         | 0.51%   |
| Acer                    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.99%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 3         | 1.49%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.49%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1%      |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 1%      |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 1%      |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 1%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1%      |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 1%      |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 1%      |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 1%      |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1%      |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 1%      |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 1%      |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.5%    |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.5%    |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.5%    |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.5%    |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.5%    |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch     | 1         | 0.5%    |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 1         | 0.5%    |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch        | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 35.91%  |
| 1366x768 (WXGA)    | 64        | 35.36%  |
| 1600x900 (HD+)     | 13        | 7.18%   |
| 1280x800 (WXGA)    | 10        | 5.52%   |
| 3840x2160 (4K)     | 5         | 2.76%   |
| 2560x1440 (QHD)    | 5         | 2.76%   |
| 1440x900 (WXGA+)   | 4         | 2.21%   |
| 3440x1440          | 3         | 1.66%   |
| 1920x1200 (WUXGA)  | 2         | 1.1%    |
| 1280x1024 (SXGA)   | 2         | 1.1%    |
| 800x1280           | 1         | 0.55%   |
| 7680x2160          | 1         | 0.55%   |
| 3456x2160          | 1         | 0.55%   |
| 3000x2000          | 1         | 0.55%   |
| 2160x1440          | 1         | 0.55%   |
| 1680x1050 (WSXGA+) | 1         | 0.55%   |
| 1280x720 (HD)      | 1         | 0.55%   |
| Unknown            | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 98        | 49.75%  |
| 14      | 19        | 9.64%   |
| 17      | 17        | 8.63%   |
| 13      | 16        | 8.12%   |
| 12      | 11        | 5.58%   |
| 24      | 9         | 4.57%   |
| 27      | 5         | 2.54%   |
| Unknown | 5         | 2.54%   |
| 11      | 3         | 1.52%   |
| 40      | 2         | 1.02%   |
| 35      | 2         | 1.02%   |
| 21      | 2         | 1.02%   |
| 84      | 1         | 0.51%   |
| 43      | 1         | 0.51%   |
| 34      | 1         | 0.51%   |
| 31      | 1         | 0.51%   |
| 26      | 1         | 0.51%   |
| 23      | 1         | 0.51%   |
| 19      | 1         | 0.51%   |
| 18      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 123       | 63.08%  |
| 351-400     | 21        | 10.77%  |
| 201-300     | 20        | 10.26%  |
| 501-600     | 15        | 7.69%   |
| Unknown     | 5         | 2.56%   |
| 801-900     | 4         | 2.05%   |
| 401-500     | 3         | 1.54%   |
| 701-800     | 1         | 0.51%   |
| 601-700     | 1         | 0.51%   |
| 1501-2000   | 1         | 0.51%   |
| 901-1000    | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 146       | 82.95%  |
| 16/10   | 17        | 9.66%   |
| Unknown | 4         | 2.27%   |
| 3/2     | 3         | 1.7%    |
| 21/9    | 3         | 1.7%    |
| 5/4     | 2         | 1.14%   |
| 0.62    | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 96        | 48.98%  |
| 81-90          | 32        | 16.33%  |
| 121-130        | 14        | 7.14%   |
| 61-70          | 11        | 5.61%   |
| 201-250        | 11        | 5.61%   |
| 301-350        | 5         | 2.55%   |
| Unknown        | 5         | 2.55%   |
| 351-500        | 4         | 2.04%   |
| 71-80          | 3         | 1.53%   |
| 51-60          | 3         | 1.53%   |
| 501-1000       | 3         | 1.53%   |
| 151-200        | 2         | 1.02%   |
| 131-140        | 2         | 1.02%   |
| 91-100         | 2         | 1.02%   |
| More than 1000 | 1         | 0.51%   |
| 251-300        | 1         | 0.51%   |
| 141-150        | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 40%     |
| 101-120       | 68        | 34.87%  |
| 51-100        | 32        | 16.41%  |
| 161-240       | 7         | 3.59%   |
| Unknown       | 5         | 2.56%   |
| More than 240 | 3         | 1.54%   |
| 1-50          | 2         | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 145       | 81.46%  |
| 2     | 26        | 14.61%  |
| 0     | 4         | 2.25%   |
| 3     | 3         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 99        | 34.98%  |
| Intel                    | 91        | 32.16%  |
| Qualcomm Atheros         | 44        | 15.55%  |
| Broadcom                 | 18        | 6.36%   |
| Broadcom Limited         | 7         | 2.47%   |
| Marvell Technology Group | 5         | 1.77%   |
| Ralink                   | 4         | 1.41%   |
| TP-Link                  | 2         | 0.71%   |
| Ralink Technology        | 2         | 0.71%   |
| MediaTek                 | 2         | 0.71%   |
| Hewlett-Packard          | 2         | 0.71%   |
| Xiaomi                   | 1         | 0.35%   |
| vivo                     | 1         | 0.35%   |
| U-Blox                   | 1         | 0.35%   |
| Samsung Electronics      | 1         | 0.35%   |
| Nvidia                   | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 17.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 8.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.31%   |
| Intel Wireless 8260                                               | 7         | 2.02%   |
| Intel Wireless 3160                                               | 7         | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.73%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.44%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 5         | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.15%   |
| Intel Wireless 7260                                               | 4         | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.15%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.15%   |
| Intel Wireless 7265                                               | 3         | 0.86%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 50.56%  |
| Qualcomm Atheros      | 38        | 21.35%  |
| Realtek Semiconductor | 24        | 13.48%  |
| Broadcom              | 14        | 7.87%   |
| Ralink                | 4         | 2.25%   |
| Broadcom Limited      | 3         | 1.69%   |
| TP-Link               | 2         | 1.12%   |
| Ralink Technology     | 2         | 1.12%   |
| MediaTek              | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 5.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.49%   |
| Intel Wireless 8260                                                     | 7         | 3.93%   |
| Intel Wireless 3160                                                     | 7         | 3.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.37%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.81%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 2.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.25%   |
| Intel Wireless 7260                                                     | 4         | 2.25%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.25%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.25%   |
| Intel Wireless 7265                                                     | 3         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.12%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.12%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 94        | 56.29%  |
| Intel                    | 35        | 20.96%  |
| Qualcomm Atheros         | 13        | 7.78%   |
| Broadcom                 | 8         | 4.79%   |
| Marvell Technology Group | 5         | 2.99%   |
| Broadcom Limited         | 4         | 2.4%    |
| Xiaomi                   | 1         | 0.6%    |
| vivo                     | 1         | 0.6%    |
| Samsung Electronics      | 1         | 0.6%    |
| Nvidia                   | 1         | 0.6%    |
| MediaTek                 | 1         | 0.6%    |
| Lenovo                   | 1         | 0.6%    |
| Huawei Technologies      | 1         | 0.6%    |
| Hewlett-Packard          | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 36.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 16.77%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.4%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.4%    |
| Intel Ethernet Connection I219-V                                  | 3         | 1.8%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.2%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.2%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.2%    |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.6%    |
| vivo 1806                                                         | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.6%    |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.6%    |
| MediaTek TECNO CAMON 18P                                          | 1         | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Lenovo Thinkpad LAN                                               | 1         | 0.6%    |
| Intel PRO/100 VE Network Connection                               | 1         | 0.6%    |
| Intel Ethernet Connection I218-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.6%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 51.49%  |
| Ethernet | 161       | 47.92%  |
| Modem    | 2         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 149       | 82.32%  |
| Ethernet | 32        | 17.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 151       | 86.29%  |
| 1     | 21        | 12%     |
| 3     | 2         | 1.14%   |
| 0     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 95.43%  |
| Yes  | 8         | 4.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 40.3%   |
| Realtek Semiconductor           | 15        | 11.19%  |
| Lite-On Technology              | 12        | 8.96%   |
| IMC Networks                    | 12        | 8.96%   |
| Qualcomm Atheros Communications | 10        | 7.46%   |
| Broadcom                        | 9         | 6.72%   |
| Dell                            | 5         | 3.73%   |
| Hewlett-Packard                 | 4         | 2.99%   |
| Toshiba                         | 3         | 2.24%   |
| Ralink                          | 2         | 1.49%   |
| Cambridge Silicon Radio         | 2         | 1.49%   |
| Taiyo Yuden                     | 1         | 0.75%   |
| Ralink Technology               | 1         | 0.75%   |
| Qcom                            | 1         | 0.75%   |
| Foxconn / Hon Hai               | 1         | 0.75%   |
| ASUSTek Computer                | 1         | 0.75%   |
| Apple                           | 1         | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 23        | 17.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 7.46%   |
| Realtek Bluetooth Radio                             | 8         | 5.97%   |
| Intel AX201 Bluetooth                               | 6         | 4.48%   |
| Intel AX200 Bluetooth                               | 6         | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.73%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.24%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 2.24%   |
| Lite-On Bluetooth Device                            | 3         | 2.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.24%   |
| IMC Networks Bluetooth Device                       | 3         | 2.24%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.49%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.49%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.49%   |
| Intel AX210 Bluetooth                               | 2         | 1.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.49%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.49%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.49%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.49%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.75%   |
| Toshiba Bluetooth Device                            | 1         | 0.75%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.75%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.75%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.75%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.75%   |
| Lite-On BCM43142A0                                  | 1         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.75%   |
| Intel Bluetooth Device                              | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 66.98%  |
| AMD                   | 33        | 15.35%  |
| Nvidia                | 26        | 12.09%  |
| C-Media Electronics   | 3         | 1.4%    |
| Logitech              | 2         | 0.93%   |
| Realtek Semiconductor | 1         | 0.47%   |
| Microsoft             | 1         | 0.47%   |
| Lenovo                | 1         | 0.47%   |
| GYROCOM C&C           | 1         | 0.47%   |
| GN Netcom             | 1         | 0.47%   |
| Creative Technology   | 1         | 0.47%   |
| Apple                 | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 8.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 6.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 5.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.14%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.35%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.18%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.18%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.78%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 26.28%  |
| SK hynix            | 33        | 24.09%  |
| Kingston            | 21        | 15.33%  |
| Unknown             | 19        | 13.87%  |
| Micron Technology   | 12        | 8.76%   |
| G.Skill             | 3         | 2.19%   |
| Elpida              | 3         | 2.19%   |
| Ramaxel Technology  | 2         | 1.46%   |
| Crucial             | 2         | 1.46%   |
| Corsair             | 2         | 1.46%   |
| Toshiba             | 1         | 0.73%   |
| PNY                 | 1         | 0.73%   |
| Goodram             | 1         | 0.73%   |
| A-DATA Technology   | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 4         | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.78%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                    | 3         | 2.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 2.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                       | 3         | 2.08%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                              | 2         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                               | 2         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.39%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.39%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.39%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.39%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.39%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                 | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                                | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DRAM                                          | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                  | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR                                        | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                    | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                              | 1         | 0.69%   |
| Unknown RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 1024MB SODIMM DDR2 667MT/s | 1         | 0.69%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s                          | 1         | 0.69%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s                      | 1         | 0.69%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                             | 1         | 0.69%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                             | 1         | 0.69%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                               | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 44.55%  |
| DDR4    | 43        | 39.09%  |
| DDR2    | 11        | 10%     |
| LPDDR4  | 3         | 2.73%   |
| SDRAM   | 1         | 0.91%   |
| DRAM    | 1         | 0.91%   |
| DDR     | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 96.36%  |
| Row Of Chips | 3         | 2.73%   |
| Chip         | 1         | 0.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 46        | 38.33%  |
| 8192  | 39        | 32.5%   |
| 2048  | 22        | 18.33%  |
| 16384 | 8         | 6.67%   |
| 1024  | 3         | 2.5%    |
| 32768 | 1         | 0.83%   |
| 512   | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 25.62%  |
| 2667    | 23        | 19.01%  |
| 1334    | 11        | 9.09%   |
| 3200    | 10        | 8.26%   |
| 1333    | 9         | 7.44%   |
| 2133    | 7         | 5.79%   |
| 667     | 7         | 5.79%   |
| 2400    | 6         | 4.96%   |
| 1066    | 3         | 2.48%   |
| Unknown | 3         | 2.48%   |
| 4267    | 2         | 1.65%   |
| 1067    | 2         | 1.65%   |
| 800     | 2         | 1.65%   |
| 4199    | 1         | 0.83%   |
| 3266    | 1         | 0.83%   |
| 1867    | 1         | 0.83%   |
| 975     | 1         | 0.83%   |
| 200     | 1         | 0.83%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 26.53%  |
| IMC Networks                           | 19        | 12.93%  |
| Realtek Semiconductor                  | 17        | 11.56%  |
| Acer                                   | 10        | 6.8%    |
| Microdia                               | 9         | 6.12%   |
| Suyin                                  | 8         | 5.44%   |
| Sunplus Innovation Technology          | 7         | 4.76%   |
| Quanta                                 | 7         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.08%   |
| Syntek                                 | 5         | 3.4%    |
| Lite-On Technology                     | 5         | 3.4%    |
| Silicon Motion                         | 3         | 2.04%   |
| Luxvisions Innotech Limited            | 3         | 2.04%   |
| Ricoh                                  | 2         | 1.36%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Primax Electronics                     | 1         | 0.68%   |
| OmniVision Technologies                | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Genesys Logic                          | 1         | 0.68%   |
| DigiTech                               | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 4.03%   |
| Realtek Integrated_Webcam_HD                                | 5         | 3.36%   |
| Chicony Integrated Camera                                   | 5         | 3.36%   |
| Realtek USB Camera                                          | 4         | 2.68%   |
| IMC Networks Integrated Camera                              | 4         | 2.68%   |
| Chicony HD WebCam                                           | 4         | 2.68%   |
| Acer Lenovo EasyCamera                                      | 4         | 2.68%   |
| Sunplus Asus Webcam                                         | 3         | 2.01%   |
| Realtek Integrated Webcam                                   | 3         | 2.01%   |
| Lite-On Integrated Camera                                   | 3         | 2.01%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 2.01%   |
| Chicony HP HD Camera                                        | 3         | 2.01%   |
| Chicony HD User Facing                                      | 3         | 2.01%   |
| Acer Integrated Camera                                      | 3         | 2.01%   |
| Suyin HD WebCam                                             | 2         | 1.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1.34%   |
| Realtek HP Webcam                                           | 2         | 1.34%   |
| Quanta HD Webcam                                            | 2         | 1.34%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.34%   |
| Microdia Integrated Webcam                                  | 2         | 1.34%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.34%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.34%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.34%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.34%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.34%   |
| Chicony HP HD Webcam                                        | 2         | 1.34%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.34%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.67%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.67%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.67%   |
| Syntek Integrated Camera                                    | 1         | 0.67%   |
| Syntek EasyCamera                                           | 1         | 0.67%   |
| Suyin WebCam                                                | 1         | 0.67%   |
| Suyin HD Video WebCam                                       | 1         | 0.67%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.67%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.67%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.67%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.67%   |
| Sunplus HD WebCam                                           | 1         | 0.67%   |

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
| 0     | 114       | 62.98%  |
| 1     | 50        | 27.62%  |
| 2     | 15        | 8.29%   |
| 3     | 2         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 40.24%  |
| Graphics card            | 17        | 20.73%  |
| Chipcard                 | 15        | 18.29%  |
| Net/wireless             | 5         | 6.1%    |
| Multimedia controller    | 4         | 4.88%   |
| Communication controller | 2         | 2.44%   |
| Camera                   | 2         | 2.44%   |
| Bluetooth                | 2         | 2.44%   |
| Storage                  | 1         | 1.22%   |
| Card reader              | 1         | 1.22%   |

