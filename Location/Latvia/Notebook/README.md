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

Total: 330

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | N56VJ                       | [d552e1a450](https://linux-hardware.org/?probe=d552e1a450) | Aug 08, 2023 |
| Wortmann      | CR700                       | [2f3379e14e](https://linux-hardware.org/?probe=2f3379e14e) | Jul 31, 2023 |
| HP            | ProBook 4530s               | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| HP            | Pavilion dv6500             | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Packard Be... | EasyNote TE11HC             | [9b40832f50](https://linux-hardware.org/?probe=9b40832f50) | Jul 09, 2023 |
| Unknown       | Unknown                     | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| Sony          | VPCCW2S8E                   | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| Wortmann      | CR700                       | [b198dccb29](https://linux-hardware.org/?probe=b198dccb29) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Gigabyte      | P55V6                       | [63d0cd064b](https://linux-hardware.org/?probe=63d0cd064b) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Wortmann      | CR700                       | [189f1ae92b](https://linux-hardware.org/?probe=189f1ae92b) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Dell          | Latitude 5330               | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [66b49186cb](https://linux-hardware.org/?probe=66b49186cb) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| HUAWEI        | BOD-WXX9                    | [1909a7f824](https://linux-hardware.org/?probe=1909a7f824) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [6e0d5c7f28](https://linux-hardware.org/?probe=6e0d5c7f28) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [136fd4098d](https://linux-hardware.org/?probe=136fd4098d) | May 01, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| Dell          | Latitude 5400               | [70899bc374](https://linux-hardware.org/?probe=70899bc374) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| Acer          | Aspire 5250                 | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| Apple         | MacBookAir5,2               | [5a1cd8556c](https://linux-hardware.org/?probe=5a1cd8556c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| Acer          | Extensa 5630                | [e78d4a3c28](https://linux-hardware.org/?probe=e78d4a3c28) | Mar 14, 2023 |
| Wortmann      | CR700                       | [a48e22ffc5](https://linux-hardware.org/?probe=a48e22ffc5) | Mar 07, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| HP            | Pavilion 17                 | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| Fujitsu       | STYLISTIC Q704              | [9d36ad089c](https://linux-hardware.org/?probe=9d36ad089c) | Feb 18, 2023 |
| Dell          | Latitude 5330               | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| Acer          | Aspire 5532                 | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | X550CL                      | [e98a955b1a](https://linux-hardware.org/?probe=e98a955b1a) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Extensa 5630                | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Wortmann      | CR700                       | [0d40cf0690](https://linux-hardware.org/?probe=0d40cf0690) | Jan 22, 2023 |
| MSI           | CR500                       | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9cb7b18b35](https://linux-hardware.org/?probe=9cb7b18b35) | Jan 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [95e7b7d833](https://linux-hardware.org/?probe=95e7b7d833) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [8026c0d5b2](https://linux-hardware.org/?probe=8026c0d5b2) | Jan 17, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [68bd2484a1](https://linux-hardware.org/?probe=68bd2484a1) | Jan 04, 2023 |
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
| Ubuntu 20.04       | 23        | 9.75%   |
| ROSA R11           | 14        | 5.93%   |
| Ubuntu 18.04       | 9         | 3.81%   |
| ROSA R9            | 7         | 2.97%   |
| ROSA R10           | 6         | 2.54%   |
| OpenMandriva 4.3   | 6         | 2.54%   |
| Debian 11          | 6         | 2.54%   |
| Arch               | 6         | 2.54%   |
| Ubuntu 22.04       | 5         | 2.12%   |
| ROSA R8.1          | 5         | 2.12%   |
| ROSA R11.1         | 5         | 2.12%   |
| Pop!_OS 22.04      | 5         | 2.12%   |
| ROSA R8            | 4         | 1.69%   |
| ROSA 12.3          | 4         | 1.69%   |
| Pop!_OS 21.04      | 4         | 1.69%   |
| Pop!_OS 20.10      | 4         | 1.69%   |
| Manjaro            | 4         | 1.69%   |
| Linux Mint 21      | 4         | 1.69%   |
| Linux Mint 20.3    | 4         | 1.69%   |
| KDE neon 20.04     | 4         | 1.69%   |
| ArcoLinux Rolling  | 4         | 1.69%   |
| Arch Rolling       | 4         | 1.69%   |
| Ubuntu 19.10       | 3         | 1.27%   |
| ROSA 12.1          | 3         | 1.27%   |
| Linux Mint 19      | 3         | 1.27%   |
| Linux Mint 18.3    | 3         | 1.27%   |
| KDE neon 22.04     | 3         | 1.27%   |
| Fedora 37          | 3         | 1.27%   |
| Xubuntu 20.04      | 2         | 0.85%   |
| Ubuntu 23.04       | 2         | 0.85%   |
| Ubuntu 21.10       | 2         | 0.85%   |
| Ubuntu 21.04       | 2         | 0.85%   |
| Ubuntu 20.10       | 2         | 0.85%   |
| ROSA 12.2          | 2         | 0.85%   |
| Pop!_OS 21.10      | 2         | 0.85%   |
| OpenMandriva 4.50  | 2         | 0.85%   |
| OpenMandriva 23.01 | 2         | 0.85%   |
| Linux Mint 21.1    | 2         | 0.85%   |
| Linux Mint 20.1    | 2         | 0.85%   |
| Linux Mint 20      | 2         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 50        | 23.81%  |
| ROSA          | 35        | 16.67%  |
| Linux Mint    | 20        | 9.52%   |
| Pop!_OS       | 14        | 6.67%   |
| OpenMandriva  | 12        | 5.71%   |
| Debian        | 11        | 5.24%   |
| Arch          | 10        | 4.76%   |
| Manjaro       | 8         | 3.81%   |
| Fedora        | 8         | 3.81%   |
| KDE neon      | 7         | 3.33%   |
| ArcoLinux     | 5         | 2.38%   |
| Xubuntu       | 4         | 1.9%    |
| Elementary    | 3         | 1.43%   |
| Ubuntu Unity  | 2         | 0.95%   |
| openSUSE      | 2         | 0.95%   |
| Kubuntu       | 2         | 0.95%   |
| Kali          | 2         | 0.95%   |
| Endless       | 2         | 0.95%   |
| Zorin         | 1         | 0.48%   |
| Void Linux    | 1         | 0.48%   |
| Ubuntu Budgie | 1         | 0.48%   |
| SteamOS       | 1         | 0.48%   |
| Solus         | 1         | 0.48%   |
| Peppermint    | 1         | 0.48%   |
| Parrot        | 1         | 0.48%   |
| NixOS         | 1         | 0.48%   |
| MX            | 1         | 0.48%   |
| Lubuntu       | 1         | 0.48%   |
| GNOME OS      | 1         | 0.48%   |
| Garuda Linux  | 1         | 0.48%   |
| EndeavourOS   | 1         | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 6         | 2.27%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.27%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.27%   |
| 5.4.0-42-generic                   | 4         | 1.52%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.52%   |
| 5.8.0-7630-generic                 | 3         | 1.14%   |
| 5.15.0-58-generic                  | 3         | 1.14%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.14%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.14%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.14%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.14%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.14%   |
| 6.2.0-20-generic                   | 2         | 0.76%   |
| 6.1.1-desktop-1omv2290             | 2         | 0.76%   |
| 5.8.0-48-generic                   | 2         | 0.76%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.76%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.76%   |
| 5.4.0-80-generic                   | 2         | 0.76%   |
| 5.4.0-47-generic                   | 2         | 0.76%   |
| 5.4.0-26-generic                   | 2         | 0.76%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.76%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.76%   |
| 5.15.0-67-generic                  | 2         | 0.76%   |
| 5.15.0-56-generic                  | 2         | 0.76%   |
| 5.15.0-52-generic                  | 2         | 0.76%   |
| 5.15.0-46-generic                  | 2         | 0.76%   |
| 5.13.6-arch1-1                     | 2         | 0.76%   |
| 5.13.0-25-generic                  | 2         | 0.76%   |
| 5.11.0-43-generic                  | 2         | 0.76%   |
| 5.10.0-8-amd64                     | 2         | 0.76%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.76%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.76%   |
| 4.18.0-18-generic                  | 2         | 0.76%   |
| 4.15.0-54-generic                  | 2         | 0.76%   |
| 4.10.0-38-generic                  | 2         | 0.76%   |
| 6.3.2-arch1-1                      | 1         | 0.38%   |
| 6.3.1                              | 1         | 0.38%   |
| 6.2.6-desktop-1omv2390             | 1         | 0.38%   |
| 6.2.6-76060206-generic             | 1         | 0.38%   |
| 6.2.0-26-generic                   | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 12.4%   |
| 4.15.0  | 22        | 8.8%    |
| 5.15.0  | 14        | 5.6%    |
| 5.11.0  | 11        | 4.4%    |
| 5.8.0   | 10        | 4%      |
| 5.13.0  | 10        | 4%      |
| 5.10.0  | 7         | 2.8%    |
| 5.3.0   | 6         | 2.4%    |
| 5.16.7  | 6         | 2.4%    |
| 4.9.20  | 6         | 2.4%    |
| 6.2.0   | 5         | 2%      |
| 5.10.74 | 4         | 1.6%    |
| 5.0.0   | 4         | 1.6%    |
| 4.18.0  | 4         | 1.6%    |
| 5.17.1  | 3         | 1.2%    |
| 4.9.60  | 3         | 1.2%    |
| 4.9.41  | 3         | 1.2%    |
| 4.9.155 | 3         | 1.2%    |
| 4.1.34  | 3         | 1.2%    |
| 6.2.6   | 2         | 0.8%    |
| 6.1.1   | 2         | 0.8%    |
| 6.0.9   | 2         | 0.8%    |
| 5.4.83  | 2         | 0.8%    |
| 5.4.72  | 2         | 0.8%    |
| 5.4.32  | 2         | 0.8%    |
| 5.19.0  | 2         | 0.8%    |
| 5.15.79 | 2         | 0.8%    |
| 5.15.75 | 2         | 0.8%    |
| 5.14.0  | 2         | 0.8%    |
| 5.13.6  | 2         | 0.8%    |
| 5.13.12 | 2         | 0.8%    |
| 5.12.14 | 2         | 0.8%    |
| 4.9.9   | 2         | 0.8%    |
| 4.9.124 | 2         | 0.8%    |
| 4.4.0   | 2         | 0.8%    |
| 4.10.0  | 2         | 0.8%    |
| 4.1.38  | 2         | 0.8%    |
| 6.3.2   | 1         | 0.4%    |
| 6.3.1   | 1         | 0.4%    |
| 6.1.9   | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 14.94%  |
| 5.15    | 25        | 10.37%  |
| 4.15    | 22        | 9.13%   |
| 4.9     | 16        | 6.64%   |
| 5.13    | 14        | 5.81%   |
| 5.10    | 14        | 5.81%   |
| 5.8     | 12        | 4.98%   |
| 5.11    | 12        | 4.98%   |
| 5.16    | 9         | 3.73%   |
| 6.1     | 8         | 3.32%   |
| 6.2     | 7         | 2.9%    |
| 6.0     | 7         | 2.9%    |
| 5.3     | 6         | 2.49%   |
| 5.12    | 6         | 2.49%   |
| 5.19    | 5         | 2.07%   |
| 5.18    | 4         | 1.66%   |
| 5.17    | 4         | 1.66%   |
| 5.14    | 4         | 1.66%   |
| 5.0     | 4         | 1.66%   |
| 4.18    | 4         | 1.66%   |
| 4.1     | 4         | 1.66%   |
| 5.5     | 3         | 1.24%   |
| 6.3     | 2         | 0.83%   |
| 5.9     | 2         | 0.83%   |
| 4.4     | 2         | 0.83%   |
| 4.19    | 2         | 0.83%   |
| 4.10    | 2         | 0.83%   |
| 5.7     | 1         | 0.41%   |
| 5.6     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 4.20    | 1         | 0.41%   |
| 4.13    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 95.59%  |
| i686   | 9         | 4.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 80        | 36.53%  |
| KDE5       | 46        | 21%     |
| KDE4       | 24        | 10.96%  |
| Unknown    | 18        | 8.22%   |
| XFCE       | 17        | 7.76%   |
| MATE       | 9         | 4.11%   |
| X-Cinnamon | 6         | 2.74%   |
| Budgie     | 4         | 1.83%   |
| Pantheon   | 3         | 1.37%   |
| LXQt       | 3         | 1.37%   |
| KDE        | 3         | 1.37%   |
| Unity      | 2         | 0.91%   |
| Cinnamon   | 2         | 0.91%   |
| sway       | 1         | 0.46%   |
| LXDE       | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 167       | 79.15%  |
| Wayland | 32        | 15.17%  |
| Unknown | 9         | 4.27%   |
| Tty     | 3         | 1.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 36.28%  |
| SDDM    | 37        | 17.21%  |
| GDM     | 32        | 14.88%  |
| KDM     | 24        | 11.16%  |
| LightDM | 19        | 8.84%   |
| TDM     | 11        | 5.12%   |
| GDM3    | 11        | 5.12%   |
| SLiM    | 1         | 0.47%   |
| MDM     | 1         | 0.47%   |
| LDM     | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 106       | 49.77%  |
| Unknown     | 43        | 20.19%  |
| ru_RU       | 23        | 10.8%   |
| lv_LV       | 23        | 10.8%   |
| en_GB       | 9         | 4.23%   |
| C           | 4         | 1.88%   |
| ru_RU.UTF_8 | 1         | 0.47%   |
| POSIX       | 1         | 0.47%   |
| fr_FR       | 1         | 0.47%   |
| en_AG       | 1         | 0.47%   |
| de_DE       | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 110       | 53.14%  |
| EFI  | 97        | 46.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 159       | 75.71%  |
| Btrfs   | 18        | 8.57%   |
| Unknown | 16        | 7.62%   |
| Overlay | 12        | 5.71%   |
| Tmpfs   | 4         | 1.9%    |
| Zfs     | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 40.85%  |
| GPT     | 83        | 38.97%  |
| MBR     | 43        | 20.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 189       | 88.73%  |
| Yes       | 24        | 11.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 73.08%  |
| Yes       | 56        | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 24.51%  |
| ASUSTek Computer    | 34        | 16.67%  |
| Hewlett-Packard     | 30        | 14.71%  |
| Dell                | 26        | 12.75%  |
| Acer                | 23        | 11.27%  |
| Toshiba             | 6         | 2.94%   |
| MSI                 | 6         | 2.94%   |
| Fujitsu Siemens     | 5         | 2.45%   |
| Samsung Electronics | 4         | 1.96%   |
| Packard Bell        | 3         | 1.47%   |
| HUAWEI              | 3         | 1.47%   |
| Apple               | 2         | 0.98%   |
| Wortmann AG         | 1         | 0.49%   |
| Valve               | 1         | 0.49%   |
| Timi                | 1         | 0.49%   |
| Sony                | 1         | 0.49%   |
| Razer               | 1         | 0.49%   |
| Quanta              | 1         | 0.49%   |
| Gigabyte Technology | 1         | 0.49%   |
| Fujitsu             | 1         | 0.49%   |
| eMachines           | 1         | 0.49%   |
| Chuwi               | 1         | 0.49%   |
| Advent              | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.47%   |
| ASUS X553MA                                           | 3         | 1.47%   |
| Toshiba Satellite C660                                | 2         | 0.98%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.98%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.98%   |
| HP G62                                                | 2         | 0.98%   |
| HP EliteBook 8440p                                    | 2         | 0.98%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.98%   |
| Fujitsu Siemens LIFEBOOK S6420                        | 2         | 0.98%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.98%   |
| ASUS X551MA                                           | 2         | 0.98%   |
| Unknown                                               | 2         | 0.98%   |
| Wortmann AG CR700                                     | 1         | 0.49%   |
| Valve Jupiter                                         | 1         | 0.49%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.49%   |
| Toshiba Satellite L750                                | 1         | 0.49%   |
| Toshiba Satellite L350                                | 1         | 0.49%   |
| Toshiba Satellite C50D-B                              | 1         | 0.49%   |
| Timi A35S                                             | 1         | 0.49%   |
| Sony VPCCW2S8E                                        | 1         | 0.49%   |
| Samsung R528/R728                                     | 1         | 0.49%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.49%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.49%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.49%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.49%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.49%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.49%   |
| Packard Bell EasyNote LM85                            | 1         | 0.49%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.49%   |
| MSI Modern 14 B4MW                                    | 1         | 0.49%   |
| MSI GV72 7RE                                          | 1         | 0.49%   |
| MSI GT62VR 6RE                                        | 1         | 0.49%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.49%   |
| MSI GF63 Thin 9RCX                                    | 1         | 0.49%   |
| MSI CR500                                             | 1         | 0.49%   |
| Lenovo ZIWB2                                          | 1         | 0.49%   |
| Lenovo Y50-70 20378                                   | 1         | 0.49%   |
| Lenovo V110-15IAP 80TG                                | 1         | 0.49%   |
| Lenovo ThinkPad X260 20F5S5Q200                       | 1         | 0.49%   |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 29        | 14.22%  |
| Acer Aspire              | 14        | 6.86%   |
| HP EliteBook             | 11        | 5.39%   |
| Dell Inspiron            | 11        | 5.39%   |
| Lenovo IdeaPad           | 10        | 4.9%    |
| Dell Latitude            | 10        | 4.9%    |
| Toshiba Satellite        | 6         | 2.94%   |
| HP ProBook               | 5         | 2.45%   |
| HP Pavilion              | 5         | 2.45%   |
| ASUS VivoBook            | 4         | 1.96%   |
| Packard Bell EasyNote    | 3         | 1.47%   |
| Lenovo Legion            | 3         | 1.47%   |
| HP 250                   | 3         | 1.47%   |
| Fujitsu Siemens LIFEBOOK | 3         | 1.47%   |
| ASUS X553MA              | 3         | 1.47%   |
| HP Laptop                | 2         | 0.98%   |
| HP G62                   | 2         | 0.98%   |
| Fujitsu Siemens AMILO    | 2         | 0.98%   |
| Dell XPS                 | 2         | 0.98%   |
| ASUS ZenBook             | 2         | 0.98%   |
| ASUS X551MA              | 2         | 0.98%   |
| ASUS TUF                 | 2         | 0.98%   |
| ASUS ASUS                | 2         | 0.98%   |
| Acer Nitro               | 2         | 0.98%   |
| Acer Extensa             | 2         | 0.98%   |
| Unknown                  | 2         | 0.98%   |
| Wortmann AG CR700        | 1         | 0.49%   |
| Valve Jupiter            | 1         | 0.49%   |
| Timi A35S                | 1         | 0.49%   |
| Sony VPCCW2S8E           | 1         | 0.49%   |
| Samsung R528             | 1         | 0.49%   |
| Samsung 355V4C           | 1         | 0.49%   |
| Samsung 350V5C           | 1         | 0.49%   |
| Samsung 300V3A           | 1         | 0.49%   |
| Razer Blade              | 1         | 0.49%   |
| Quanta TW8               | 1         | 0.49%   |
| MSI Modern               | 1         | 0.49%   |
| MSI GV72                 | 1         | 0.49%   |
| MSI GT62VR               | 1         | 0.49%   |
| MSI GP75                 | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 9.8%    |
| 2013 | 18        | 8.82%   |
| 2014 | 17        | 8.33%   |
| 2020 | 15        | 7.35%   |
| 2010 | 15        | 7.35%   |
| 2018 | 14        | 6.86%   |
| 2012 | 14        | 6.86%   |
| 2015 | 13        | 6.37%   |
| 2008 | 13        | 6.37%   |
| 2011 | 12        | 5.88%   |
| 2017 | 11        | 5.39%   |
| 2021 | 10        | 4.9%    |
| 2016 | 9         | 4.41%   |
| 2009 | 9         | 4.41%   |
| 2007 | 7         | 3.43%   |
| 2022 | 4         | 1.96%   |
| 2006 | 2         | 0.98%   |
| 2023 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 204       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 187       | 90.78%  |
| Enabled  | 19        | 9.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 60        | 28.99%  |
| 4.01-8.0   | 57        | 27.54%  |
| 8.01-16.0  | 31        | 14.98%  |
| 16.01-24.0 | 29        | 14.01%  |
| 32.01-64.0 | 10        | 4.83%   |
| 2.01-3.0   | 8         | 3.86%   |
| 1.01-2.0   | 8         | 3.86%   |
| 24.01-32.0 | 2         | 0.97%   |
| 0.51-1.0   | 2         | 0.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 79        | 33.91%  |
| 2.01-3.0   | 59        | 25.32%  |
| 4.01-8.0   | 30        | 12.88%  |
| 0.51-1.0   | 29        | 12.45%  |
| 3.01-4.0   | 23        | 9.87%   |
| 8.01-16.0  | 10        | 4.29%   |
| 16.01-24.0 | 2         | 0.86%   |
| 0.01-0.5   | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 151       | 72.95%  |
| 2      | 47        | 22.71%  |
| 3      | 6         | 2.9%    |
| 0      | 2         | 0.97%   |
| 4      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 58.17%  |
| Yes       | 87        | 41.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 88.83%  |
| No        | 23        | 11.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 98.53%  |
| No        | 3         | 1.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 74.4%   |
| No        | 53        | 25.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 204       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 157       | 71.36%  |
| Liepāja                | 6         | 2.73%   |
| Jelgava                 | 6         | 2.73%   |
| Daugavpils              | 6         | 2.73%   |
| Jūrmala                | 3         | 1.36%   |
| Jaunmarupe              | 3         | 1.36%   |
| Iecava                  | 3         | 1.36%   |
| Adazi                   | 3         | 1.36%   |
| Valmiera                | 2         | 0.91%   |
| Saulkrasti              | 2         | 0.91%   |
| Rēzekne                | 2         | 0.91%   |
| Malpils                 | 2         | 0.91%   |
| Cēsis                  | 2         | 0.91%   |
| Zvejniekciems           | 1         | 0.45%   |
| Ventspils               | 1         | 0.45%   |
| Ulbroka                 | 1         | 0.45%   |
| Tukums                  | 1         | 0.45%   |
| Tiraine                 | 1         | 0.45%   |
| Smiltene                | 1         | 0.45%   |
| Saulkalne               | 1         | 0.45%   |
| Saldus                  | 1         | 0.45%   |
| Pļaviņas              | 1         | 0.45%   |
| Nereta                  | 1         | 0.45%   |
| Lizums                  | 1         | 0.45%   |
| Limbaži                | 1         | 0.45%   |
| Kuldīga                | 1         | 0.45%   |
| Ķekava                 | 1         | 0.45%   |
| Jēkabpils Municipality | 1         | 0.45%   |
| Jēkabpils              | 1         | 0.45%   |
| Inčukalns              | 1         | 0.45%   |
| Garkalne                | 1         | 0.45%   |
| Garciems                | 1         | 0.45%   |
| Dobele                  | 1         | 0.45%   |
| Bukulti                 | 1         | 0.45%   |
| Aizpute                 | 1         | 0.45%   |
| Aizkraukle              | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 39        | 52     | 15.66%  |
| Seagate                     | 34        | 40     | 13.65%  |
| Kingston                    | 29        | 41     | 11.65%  |
| WDC                         | 24        | 34     | 9.64%   |
| Toshiba                     | 24        | 27     | 9.64%   |
| Hitachi                     | 10        | 13     | 4.02%   |
| Unknown                     | 8         | 9      | 3.21%   |
| SK hynix                    | 8         | 8      | 3.21%   |
| Micron Technology           | 8         | 9      | 3.21%   |
| HGST                        | 8         | 16     | 3.21%   |
| SanDisk                     | 7         | 16     | 2.81%   |
| Intel                       | 5         | 7      | 2.01%   |
| A-DATA Technology           | 5         | 6      | 2.01%   |
| Patriot                     | 4         | 10     | 1.61%   |
| KIOXIA                      | 4         | 6      | 1.61%   |
| Crucial                     | 4         | 4      | 1.61%   |
| LITEON                      | 2         | 2      | 0.8%    |
| Integral                    | 2         | 2      | 0.8%    |
| Verbatim                    | 1         | 1      | 0.4%    |
| USB                         | 1         | 1      | 0.4%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.4%    |
| SPCC                        | 1         | 1      | 0.4%    |
| Realtek                     | 1         | 1      | 0.4%    |
| PNY                         | 1         | 1      | 0.4%    |
| Plextor                     | 1         | 1      | 0.4%    |
| Platinet                    | 1         | 1      | 0.4%    |
| Phison Electronics          | 1         | 1      | 0.4%    |
| Phison                      | 1         | 1      | 0.4%    |
| OCZ                         | 1         | 1      | 0.4%    |
| Netac                       | 1         | 1      | 0.4%    |
| LITEONIT                    | 1         | 1      | 0.4%    |
| LITEON C                    | 1         | 1      | 0.4%    |
| Lexar                       | 1         | 1      | 0.4%    |
| Kingston Technology Company | 1         | 1      | 0.4%    |
| KingSpec                    | 1         | 1      | 0.4%    |
| Kingchuxing                 | 1         | 7      | 0.4%    |
| Intenso                     | 1         | 1      | 0.4%    |
| Hrdtac                      | 1         | 6      | 0.4%    |
| Fujitsu                     | 1         | 1      | 0.4%    |
| China                       | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 7         | 2.73%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 2.34%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 2.34%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.56%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 1.56%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.56%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.17%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.17%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.17%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 1.17%   |
| Hitachi HTS545050B9A300 500GB       | 3         | 1.17%   |
| HGST HTS545050A7E680 500GB          | 3         | 1.17%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.78%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.78%   |
| Toshiba MK8034GSX 80GB              | 2         | 0.78%   |
| Toshiba MK6465GSX 640GB             | 2         | 0.78%   |
| SK hynix HFM512GDJTNG-8310A 512GB   | 2         | 0.78%   |
| SK hynix BC511 NVMe 256GB           | 2         | 0.78%   |
| Seagate ST9160821AS 160GB           | 2         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.78%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.78%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.78%   |
| Samsung MZALQ256HAJD-000L2 256GB    | 2         | 0.78%   |
| Samsung HM321HI 320GB               | 2         | 0.78%   |
| Patriot Burst 240GB SSD             | 2         | 0.78%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 2         | 0.78%   |
| Kingston SV300S37A60G 64GB SSD      | 2         | 0.78%   |
| Kingston SUV500MS480G 480GB SSD     | 2         | 0.78%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.78%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.78%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.78%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.78%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.39%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.39%   |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 40     | 35.42%  |
| WDC                 | 20        | 29     | 20.83%  |
| Toshiba             | 19        | 22     | 19.79%  |
| Hitachi             | 10        | 13     | 10.42%  |
| HGST                | 8         | 16     | 8.33%   |
| Samsung Electronics | 4         | 5      | 4.17%   |
| Fujitsu             | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 26        | 37     | 30.23%  |
| Samsung Electronics | 21        | 28     | 24.42%  |
| A-DATA Technology   | 5         | 6      | 5.81%   |
| Patriot             | 4         | 10     | 4.65%   |
| Crucial             | 4         | 4      | 4.65%   |
| SanDisk             | 3         | 5      | 3.49%   |
| Micron Technology   | 3         | 3      | 3.49%   |
| LITEON              | 2         | 2      | 2.33%   |
| Integral            | 2         | 2      | 2.33%   |
| Verbatim            | 1         | 1      | 1.16%   |
| USB                 | 1         | 1      | 1.16%   |
| Toshiba             | 1         | 1      | 1.16%   |
| SPCC                | 1         | 1      | 1.16%   |
| PNY                 | 1         | 1      | 1.16%   |
| Plextor             | 1         | 1      | 1.16%   |
| Platinet            | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| LITEONIT            | 1         | 1      | 1.16%   |
| LITEON C            | 1         | 1      | 1.16%   |
| Lexar               | 1         | 1      | 1.16%   |
| KingSpec            | 1         | 1      | 1.16%   |
| Intenso             | 1         | 1      | 1.16%   |
| China               | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |
| Unknown             | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 93        | 126    | 39.08%  |
| SSD     | 81        | 113    | 34.03%  |
| NVMe    | 56        | 77     | 23.53%  |
| MMC     | 6         | 7      | 2.52%   |
| Unknown | 2         | 14     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 242    | 69.06%  |
| NVMe | 56        | 76     | 25.11%  |
| SAS  | 7         | 12     | 3.14%   |
| MMC  | 6         | 7      | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 173    | 70.59%  |
| 0.51-1.0   | 47        | 63     | 27.65%  |
| 1.01-2.0   | 3         | 3      | 1.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 33.78%  |
| 251-500        | 56        | 24.89%  |
| 501-1000       | 29        | 12.89%  |
| 1-20           | 18        | 8%      |
| 51-100         | 16        | 7.11%   |
| 1001-2000      | 15        | 6.67%   |
| 21-50          | 6         | 2.67%   |
| Unknown        | 5         | 2.22%   |
| 2001-3000      | 3         | 1.33%   |
| More than 3000 | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 98        | 43.17%  |
| 21-50     | 34        | 14.98%  |
| 51-100    | 28        | 12.33%  |
| 101-250   | 27        | 11.89%  |
| 251-500   | 17        | 7.49%   |
| 501-1000  | 11        | 4.85%   |
| 1001-2000 | 6         | 2.64%   |
| Unknown   | 5         | 2.2%    |
| 2001-3000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 11.11%  |
| HGST HTS545050A7E680 500GB           | 2         | 2      | 7.41%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 3.7%    |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 3.7%    |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.7%    |
| Toshiba MK8034GSX 80GB               | 1         | 1      | 3.7%    |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 3.7%    |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 3.7%    |
| Seagate ST9500420AS 500GB            | 1         | 1      | 3.7%    |
| Seagate ST9500325AS 500GB            | 1         | 3      | 3.7%    |
| Seagate ST9250827AS 250GB            | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.7%    |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 3.7%    |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 3.7%    |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 3.7%    |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 3.7%    |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 3.7%    |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 3.7%    |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 3.7%    |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 3.7%    |
| HGST HTS721010A9E630 1TB             | 1         | 2      | 3.7%    |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 3.7%    |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 29.63%  |
| HGST                | 6         | 8      | 22.22%  |
| Toshiba             | 4         | 4      | 14.81%  |
| WDC                 | 3         | 6      | 11.11%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Kingston            | 2         | 2      | 7.41%   |
| Hitachi             | 2         | 2      | 7.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 32%     |
| HGST                | 6         | 8      | 24%     |
| Toshiba             | 4         | 4      | 16%     |
| WDC                 | 3         | 6      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 32     | 92.31%  |
| SSD  | 2         | 2      | 7.69%   |

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
| Works    | 98        | 154    | 45.37%  |
| Detected | 90        | 147    | 41.67%  |
| Malfunc  | 26        | 34     | 12.04%  |
| Failed   | 2         | 2      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 159       | 65.7%   |
| AMD                          | 23        | 9.5%    |
| Samsung Electronics          | 18        | 7.44%   |
| SK hynix                     | 8         | 3.31%   |
| SanDisk                      | 8         | 3.31%   |
| Micron Technology            | 5         | 2.07%   |
| KIOXIA                       | 5         | 2.07%   |
| Kingston Technology Company  | 4         | 1.65%   |
| Toshiba America Info Systems | 3         | 1.24%   |
| Union Memory (Shenzhen)      | 2         | 0.83%   |
| Phison Electronics           | 2         | 0.83%   |
| Nvidia                       | 2         | 0.83%   |
| Silicon Motion               | 1         | 0.41%   |
| Silicon Image                | 1         | 0.41%   |
| ADATA Technology             | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 6.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 6.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 15        | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 4.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 3.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 3.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.67%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 2.29%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.91%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 5         | 1.91%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.15%   |
| Intel SSD 660P Series                                                            | 3         | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.15%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.76%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.76%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 164       | 64.31%  |
| NVMe | 59        | 23.14%  |
| IDE  | 19        | 7.45%   |
| RAID | 13        | 5.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 83.82%  |
| AMD    | 33        | 16.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 2.45%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.96%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.47%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.47%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.47%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.47%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.98%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.98%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.98%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.98%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.98%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.98%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.98%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.98%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.98%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.98%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.98%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 0.98%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 25.49%  |
| Intel Core i7           | 33        | 16.18%  |
| Intel Core i3           | 19        | 9.31%   |
| Intel Core 2 Duo        | 18        | 8.82%   |
| Intel Celeron           | 16        | 7.84%   |
| Other                   | 15        | 7.35%   |
| Intel Pentium           | 8         | 3.92%   |
| AMD Ryzen 5             | 7         | 3.43%   |
| AMD Ryzen 7             | 6         | 2.94%   |
| Intel Pentium Dual-Core | 3         | 1.47%   |
| Intel Pentium Dual      | 3         | 1.47%   |
| Intel Genuine           | 3         | 1.47%   |
| AMD A10                 | 3         | 1.47%   |
| Intel Core 2            | 2         | 0.98%   |
| AMD Turion 64 X2 Mobile | 2         | 0.98%   |
| AMD Ryzen 7 PRO         | 2         | 0.98%   |
| AMD Ryzen 3             | 2         | 0.98%   |
| AMD E1                  | 2         | 0.98%   |
| AMD A8                  | 2         | 0.98%   |
| Intel Xeon              | 1         | 0.49%   |
| Intel Atom              | 1         | 0.49%   |
| AMD Ryzen 5 PRO         | 1         | 0.49%   |
| AMD E2                  | 1         | 0.49%   |
| AMD E                   | 1         | 0.49%   |
| AMD C-70                | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 123       | 60%     |
| 4      | 60        | 29.27%  |
| 6      | 8         | 3.9%    |
| 8      | 7         | 3.41%   |
| 1      | 4         | 1.95%   |
| 10     | 2         | 0.98%   |
| 14     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 204       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 135       | 65.85%  |
| 1      | 70        | 34.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 99.02%  |
| 32-bit         | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 21.53%  |
| 0x306a9    | 14        | 6.7%    |
| 0x406e3    | 11        | 5.26%   |
| 0x206a7    | 10        | 4.78%   |
| 0x6fd      | 9         | 4.31%   |
| 0x30678    | 9         | 4.31%   |
| 0x1067a    | 9         | 4.31%   |
| 0x906ea    | 7         | 3.35%   |
| 0x20655    | 7         | 3.35%   |
| 0x806c1    | 6         | 2.87%   |
| 0x306d4    | 6         | 2.87%   |
| 0x40651    | 5         | 2.39%   |
| 0x806ec    | 4         | 1.91%   |
| 0x806ea    | 4         | 1.91%   |
| 0x806e9    | 4         | 1.91%   |
| 0x306c3    | 4         | 1.91%   |
| 0x08108102 | 4         | 1.91%   |
| 0x06001119 | 4         | 1.91%   |
| 0xa0652    | 3         | 1.44%   |
| 0x906e9    | 3         | 1.44%   |
| 0x506e3    | 3         | 1.44%   |
| 0x10676    | 3         | 1.44%   |
| 0x05000119 | 3         | 1.44%   |
| 0x6fa      | 2         | 0.96%   |
| 0x6f6      | 2         | 0.96%   |
| 0x406c3    | 2         | 0.96%   |
| 0x20652    | 2         | 0.96%   |
| 0x0a50000c | 2         | 0.96%   |
| 0x08600103 | 2         | 0.96%   |
| 0x08108109 | 2         | 0.96%   |
| 0x906ed    | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x806d1    | 1         | 0.48%   |
| 0x706a8    | 1         | 0.48%   |
| 0x706a1    | 1         | 0.48%   |
| 0x6fb      | 1         | 0.48%   |
| 0x6ec      | 1         | 0.48%   |
| 0x506c9    | 1         | 0.48%   |
| 0x30673    | 1         | 0.48%   |
| 0x106e5    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 14.22%  |
| IvyBridge        | 18        | 8.82%   |
| Skylake          | 17        | 8.33%   |
| Core             | 17        | 8.33%   |
| Silvermont       | 13        | 6.37%   |
| Westmere         | 12        | 5.88%   |
| SandyBridge      | 12        | 5.88%   |
| Penryn           | 12        | 5.88%   |
| Haswell          | 12        | 5.88%   |
| Zen+             | 8         | 3.92%   |
| TigerLake        | 8         | 3.92%   |
| Zen 2            | 7         | 3.43%   |
| Broadwell        | 7         | 3.43%   |
| Unknown          | 5         | 2.45%   |
| Piledriver       | 4         | 1.96%   |
| CometLake        | 4         | 1.96%   |
| Bobcat           | 3         | 1.47%   |
| Zen 3            | 2         | 0.98%   |
| Puma             | 2         | 0.98%   |
| K8 Hammer        | 2         | 0.98%   |
| Goldmont plus    | 2         | 0.98%   |
| Excavator        | 2         | 0.98%   |
| P6               | 1         | 0.49%   |
| Nehalem          | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| Icelake          | 1         | 0.49%   |
| Goldmont         | 1         | 0.49%   |
| Alderlake Hybrid | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 58.89%  |
| Nvidia | 60        | 23.72%  |
| AMD    | 44        | 17.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 6.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 5.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 4.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.65%   |
| AMD Renoir                                                                               | 7         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.52%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.52%   |
| Intel HD Graphics 620                                                                    | 4         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.76%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.76%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.76%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.76%   |
| Intel HD Graphics 630                                                                    | 2         | 0.76%   |
| Intel HD Graphics 530                                                                    | 2         | 0.76%   |
| Intel HD Graphics                                                                        | 2         | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 102       | 50%     |
| Intel + Nvidia | 39        | 19.12%  |
| 1 x AMD        | 29        | 14.22%  |
| 1 x Nvidia     | 18        | 8.82%   |
| Intel + AMD    | 7         | 3.43%   |
| 2 x AMD        | 5         | 2.45%   |
| AMD + Nvidia   | 3         | 1.47%   |
| 2 x Intel      | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 80.66%  |
| Proprietary | 34        | 16.04%  |
| Unknown     | 7         | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 54.93%  |
| 1.01-2.0   | 39        | 18.31%  |
| 0.01-0.5   | 27        | 12.68%  |
| 0.51-1.0   | 13        | 6.1%    |
| 3.01-4.0   | 12        | 5.63%   |
| 7.01-8.0   | 3         | 1.41%   |
| 5.01-6.0   | 2         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 23.56%  |
| LG Display              | 36        | 16%     |
| Samsung Electronics     | 31        | 13.78%  |
| BOE                     | 26        | 11.56%  |
| Chimei Innolux          | 21        | 9.33%   |
| Dell                    | 14        | 6.22%   |
| Chi Mei Optoelectronics | 7         | 3.11%   |
| Lenovo                  | 5         | 2.22%   |
| PANDA                   | 4         | 1.78%   |
| Goldstar                | 4         | 1.78%   |
| BenQ                    | 4         | 1.78%   |
| Sony                    | 2         | 0.89%   |
| Seiko/Epson             | 2         | 0.89%   |
| Philips                 | 2         | 0.89%   |
| LG Philips              | 2         | 0.89%   |
| InfoVision              | 2         | 0.89%   |
| Hitachi                 | 2         | 0.89%   |
| Apple                   | 2         | 0.89%   |
| Tianma XM               | 1         | 0.44%   |
| Sharp                   | 1         | 0.44%   |
| Quanta Display          | 1         | 0.44%   |
| Panasonic               | 1         | 0.44%   |
| LGD                     | 1         | 0.44%   |
| Acer                    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 1.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 1.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.29%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.86%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.86%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.86%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.86%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch                  | 2         | 0.86%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.86%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.86%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.86%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.86%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.86%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.43%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.43%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 1         | 0.43%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.43%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.43%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch     | 1         | 0.43%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 1         | 0.43%   |
| Samsung Electronics S24E650 SAM0CC2 1920x1200 518x324mm 24.1-inch        | 1         | 0.43%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch        | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 36.36%  |
| 1366x768 (WXGA)    | 70        | 33.49%  |
| 1600x900 (HD+)     | 15        | 7.18%   |
| 1280x800 (WXGA)    | 13        | 6.22%   |
| 3840x2160 (4K)     | 7         | 3.35%   |
| 2560x1440 (QHD)    | 5         | 2.39%   |
| 1440x900 (WXGA+)   | 5         | 2.39%   |
| 1920x1200 (WUXGA)  | 4         | 1.91%   |
| 3440x1440          | 3         | 1.44%   |
| 1280x1024 (SXGA)   | 3         | 1.44%   |
| 7680x2160          | 1         | 0.48%   |
| 3456x2160          | 1         | 0.48%   |
| 3000x2000          | 1         | 0.48%   |
| 2160x1440          | 1         | 0.48%   |
| 1680x1050 (WSXGA+) | 1         | 0.48%   |
| 1360x768           | 1         | 0.48%   |
| 1280x720 (HD)      | 1         | 0.48%   |
| Unknown            | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 110       | 48.67%  |
| 14      | 24        | 10.62%  |
| 13      | 20        | 8.85%   |
| 17      | 19        | 8.41%   |
| 12      | 11        | 4.87%   |
| 24      | 10        | 4.42%   |
| 27      | 4         | 1.77%   |
| 21      | 4         | 1.77%   |
| Unknown | 4         | 1.77%   |
| 40      | 3         | 1.33%   |
| 19      | 3         | 1.33%   |
| 11      | 3         | 1.33%   |
| 35      | 2         | 0.88%   |
| 31      | 2         | 0.88%   |
| 23      | 2         | 0.88%   |
| 84      | 1         | 0.44%   |
| 65      | 1         | 0.44%   |
| 43      | 1         | 0.44%   |
| 34      | 1         | 0.44%   |
| 18      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 62.67%  |
| 351-400     | 25        | 11.11%  |
| 201-300     | 22        | 9.78%   |
| 501-600     | 16        | 7.11%   |
| 401-500     | 6         | 2.67%   |
| 801-900     | 5         | 2.22%   |
| Unknown     | 4         | 1.78%   |
| 601-700     | 2         | 0.89%   |
| 701-800     | 1         | 0.44%   |
| 1501-2000   | 1         | 0.44%   |
| 1001-1500   | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 166       | 81.77%  |
| 16/10   | 24        | 11.82%  |
| Unknown | 4         | 1.97%   |
| 5/4     | 3         | 1.48%   |
| 3/2     | 3         | 1.48%   |
| 21/9    | 3         | 1.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 47.79%  |
| 81-90          | 39        | 17.26%  |
| 121-130        | 16        | 7.08%   |
| 201-250        | 13        | 5.75%   |
| 61-70          | 11        | 4.87%   |
| 71-80          | 5         | 2.21%   |
| 351-500        | 5         | 2.21%   |
| 151-200        | 5         | 2.21%   |
| 301-350        | 4         | 1.77%   |
| 501-1000       | 4         | 1.77%   |
| Unknown        | 4         | 1.77%   |
| 51-60          | 3         | 1.33%   |
| More than 1000 | 2         | 0.88%   |
| 251-300        | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |
| 91-100         | 2         | 0.88%   |
| 141-150        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 87        | 38.67%  |
| 101-120       | 78        | 34.67%  |
| 51-100        | 41        | 18.22%  |
| 161-240       | 9         | 4%      |
| Unknown       | 4         | 1.78%   |
| More than 240 | 3         | 1.33%   |
| 1-50          | 3         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 169       | 80.86%  |
| 2     | 31        | 14.83%  |
| 0     | 5         | 2.39%   |
| 3     | 4         | 1.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 33.23%  |
| Intel                    | 109       | 32.63%  |
| Qualcomm Atheros         | 51        | 15.27%  |
| Broadcom                 | 22        | 6.59%   |
| Broadcom Limited         | 9         | 2.69%   |
| Marvell Technology Group | 6         | 1.8%    |
| Ralink                   | 4         | 1.2%    |
| Xiaomi                   | 2         | 0.6%    |
| vivo                     | 2         | 0.6%    |
| TP-Link                  | 2         | 0.6%    |
| Samsung Electronics      | 2         | 0.6%    |
| Ralink Technology        | 2         | 0.6%    |
| Nvidia                   | 2         | 0.6%    |
| MediaTek                 | 2         | 0.6%    |
| Lenovo                   | 2         | 0.6%    |
| Hewlett-Packard          | 2         | 0.6%    |
| U-Blox                   | 1         | 0.3%    |
| Qualcomm                 | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |
| Google                   | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 16.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 7.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.98%   |
| Intel Wireless 8260                                               | 8         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.73%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.73%   |
| Intel Wireless 3160                                               | 7         | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.49%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.99%   |
| Intel Wireless 7260                                               | 4         | 0.99%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.74%   |
| Intel Wireless 7265                                               | 3         | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.74%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.5%    |
| vivo 1820                                                         | 2         | 0.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 108       | 52.17%  |
| Qualcomm Atheros      | 44        | 21.26%  |
| Realtek Semiconductor | 25        | 12.08%  |
| Broadcom              | 15        | 7.25%   |
| Broadcom Limited      | 5         | 2.42%   |
| Ralink                | 4         | 1.93%   |
| TP-Link               | 2         | 0.97%   |
| Ralink Technology     | 2         | 0.97%   |
| Qualcomm              | 1         | 0.48%   |
| MediaTek              | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 4.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.86%   |
| Intel Wireless 8260                                                     | 8         | 3.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.38%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.38%   |
| Intel Wireless 3160                                                     | 7         | 3.38%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.38%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.42%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.93%   |
| Intel Wireless 7260                                                     | 4         | 1.93%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.93%   |
| Intel Wireless 7265                                                     | 3         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.45%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.97%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.97%   |
| Intel WiFi Link 5100                                                    | 2         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.97%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 54.92%  |
| Intel                    | 40        | 20.73%  |
| Qualcomm Atheros         | 14        | 7.25%   |
| Broadcom                 | 11        | 5.7%    |
| Marvell Technology Group | 6         | 3.11%   |
| Broadcom Limited         | 4         | 2.07%   |
| Xiaomi                   | 2         | 1.04%   |
| vivo                     | 2         | 1.04%   |
| Nvidia                   | 2         | 1.04%   |
| Lenovo                   | 2         | 1.04%   |
| MediaTek                 | 1         | 0.52%   |
| Huawei Technologies      | 1         | 0.52%   |
| Hewlett-Packard          | 1         | 0.52%   |
| Google                   | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 35.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 15.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.11%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.55%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.55%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.04%   |
| vivo 1820                                                         | 2         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.04%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.04%   |
| Lenovo ThinkPad Lan                                               | 2         | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.04%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.52%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.52%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.52%   |
| MediaTek 100026191                                                | 1         | 0.52%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 201       | 51.8%   |
| Ethernet | 183       | 47.16%  |
| Modem    | 4         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 80.28%  |
| Ethernet | 42        | 19.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 172       | 84.31%  |
| 1     | 29        | 14.22%  |
| 3     | 2         | 0.98%   |
| 0     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 193       | 94.61%  |
| Yes  | 11        | 5.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 42.86%  |
| Realtek Semiconductor           | 16        | 10.39%  |
| Lite-On Technology              | 13        | 8.44%   |
| Qualcomm Atheros Communications | 12        | 7.79%   |
| IMC Networks                    | 12        | 7.79%   |
| Broadcom                        | 11        | 7.14%   |
| Dell                            | 5         | 3.25%   |
| Hewlett-Packard                 | 4         | 2.6%    |
| Toshiba                         | 3         | 1.95%   |
| Ralink                          | 2         | 1.3%    |
| Cambridge Silicon Radio         | 2         | 1.3%    |
| Apple                           | 2         | 1.3%    |
| USI                             | 1         | 0.65%   |
| Taiyo Yuden                     | 1         | 0.65%   |
| Ralink Technology               | 1         | 0.65%   |
| Qcom                            | 1         | 0.65%   |
| Foxconn / Hon Hai               | 1         | 0.65%   |
| ASUSTek Computer                | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 17.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.79%   |
| Intel AX201 Bluetooth                               | 10        | 6.49%   |
| Realtek Bluetooth Radio                             | 8         | 5.19%   |
| Intel AX200 Bluetooth                               | 6         | 3.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.25%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.95%   |
| Lite-On Bluetooth Device                            | 3         | 1.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.95%   |
| IMC Networks Bluetooth Device                       | 3         | 1.95%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.3%    |
| Realtek RTL8723B Bluetooth                          | 2         | 1.3%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.3%    |
| Intel Bluetooth Device                              | 2         | 1.3%    |
| Intel AX210 Bluetooth                               | 2         | 1.3%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.3%    |
| Dell Wireless 355 Bluetooth                         | 2         | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.3%    |
| Broadcom HP Portable SoftSailing                    | 2         | 1.3%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.3%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.3%    |
| USI Bluetooth Device                                | 1         | 0.65%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.65%   |
| Toshiba Bluetooth Device                            | 1         | 0.65%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.65%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.65%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 169       | 67.6%   |
| AMD                   | 37        | 14.8%   |
| Nvidia                | 31        | 12.4%   |
| C-Media Electronics   | 3         | 1.2%    |
| Realtek Semiconductor | 2         | 0.8%    |
| Logitech              | 2         | 0.8%    |
| Microsoft             | 1         | 0.4%    |
| Lenovo                | 1         | 0.4%    |
| GYROCOM C&C           | 1         | 0.4%    |
| GN Netcom             | 1         | 0.4%    |
| Creative Technology   | 1         | 0.4%    |
| Apple                 | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 6.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 6.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 5.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 3.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.06%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.36%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.02%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.02%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 25.77%  |
| SK hynix            | 39        | 23.93%  |
| Unknown             | 25        | 15.34%  |
| Kingston            | 23        | 14.11%  |
| Micron Technology   | 13        | 7.98%   |
| G.Skill             | 3         | 1.84%   |
| Elpida              | 3         | 1.84%   |
| Crucial             | 3         | 1.84%   |
| Ramaxel Technology  | 2         | 1.23%   |
| Corsair             | 2         | 1.23%   |
| A-DATA Technology   | 2         | 1.23%   |
| Toshiba             | 1         | 0.61%   |
| PNY                 | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| GOODRAM             | 1         | 0.61%   |
| ASint Technology    | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 4         | 2.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 3         | 1.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 3         | 1.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 3         | 1.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                       | 3         | 1.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 2         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                              | 2         | 1.18%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                                       | 2         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                               | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.18%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.18%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.18%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                    | 2         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.18%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                 | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 0.59%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                                | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DRAM                                          | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                  | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR                                        | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                    | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 1         | 0.59%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                              | 1         | 0.59%   |
| Unknown RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 1024MB SODIMM DDR2 667MT/s | 1         | 0.59%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s                       | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 54        | 41.54%  |
| DDR4    | 48        | 36.92%  |
| DDR2    | 15        | 11.54%  |
| SDRAM   | 3         | 2.31%   |
| LPDDR4  | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |
| LPDDR5  | 1         | 0.77%   |
| LPDDR3  | 1         | 0.77%   |
| DRAM    | 1         | 0.77%   |
| DDR     | 1         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 124       | 96.12%  |
| Row Of Chips | 4         | 3.1%    |
| Chip         | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 34.48%  |
| 8192  | 46        | 31.72%  |
| 2048  | 29        | 20%     |
| 16384 | 12        | 8.28%   |
| 1024  | 5         | 3.45%   |
| 32768 | 2         | 1.38%   |
| 512   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 35        | 24.14%  |
| 2667    | 26        | 17.93%  |
| 3200    | 13        | 8.97%   |
| 1334    | 11        | 7.59%   |
| 667     | 11        | 7.59%   |
| 1333    | 10        | 6.9%    |
| 2400    | 8         | 5.52%   |
| 2133    | 8         | 5.52%   |
| 1066    | 3         | 2.07%   |
| Unknown | 3         | 2.07%   |
| 4267    | 2         | 1.38%   |
| 1067    | 2         | 1.38%   |
| 800     | 2         | 1.38%   |
| 533     | 2         | 1.38%   |
| 6400    | 1         | 0.69%   |
| 4199    | 1         | 0.69%   |
| 3266    | 1         | 0.69%   |
| 2933    | 1         | 0.69%   |
| 2048    | 1         | 0.69%   |
| 1867    | 1         | 0.69%   |
| 1639    | 1         | 0.69%   |
| 975     | 1         | 0.69%   |
| 200     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 60%     |
| Samsung Electronics | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet 1018         | 2         | 40%     |
| Samsung SCX-4100 Scanner | 1         | 20%     |
| Samsung SCX-3200 Series  | 1         | 20%     |
| HP LaserJet P1102        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 47        | 27.81%  |
| IMC Networks                           | 20        | 11.83%  |
| Realtek Semiconductor                  | 18        | 10.65%  |
| Microdia                               | 12        | 7.1%    |
| Suyin                                  | 9         | 5.33%   |
| Sunplus Innovation Technology          | 8         | 4.73%   |
| Quanta                                 | 8         | 4.73%   |
| Bison Electronics                      | 7         | 4.14%   |
| Lite-On Technology                     | 6         | 3.55%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.55%   |
| Syntek                                 | 5         | 2.96%   |
| Luxvisions Innotech Limited            | 4         | 2.37%   |
| Acer                                   | 4         | 2.37%   |
| Silicon Motion                         | 3         | 1.78%   |
| Ricoh                                  | 2         | 1.18%   |
| Z-Star Microelectronics                | 1         | 0.59%   |
| Samsung Electronics                    | 1         | 0.59%   |
| Primax Electronics                     | 1         | 0.59%   |
| OmniVision Technologies                | 1         | 0.59%   |
| Microsoft                              | 1         | 0.59%   |
| Lenovo                                 | 1         | 0.59%   |
| Genesys Logic                          | 1         | 0.59%   |
| DigiTech                               | 1         | 0.59%   |
| Apple                                  | 1         | 0.59%   |
| ALi                                    | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 4.07%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 3.49%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.91%   |
| IMC Networks Integrated Camera                              | 5         | 2.91%   |
| Chicony HD WebCam                                           | 5         | 2.91%   |
| Sunplus Asus Webcam                                         | 4         | 2.33%   |
| Realtek USB Camera                                          | 4         | 2.33%   |
| Lite-On Integrated Camera                                   | 4         | 2.33%   |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 2.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.74%   |
| Realtek Integrated Webcam                                   | 3         | 1.74%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.74%   |
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 1.74%   |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 1.74%   |
| Chicony HP HD Camera                                        | 3         | 1.74%   |
| Chicony HD User Facing                                      | 3         | 1.74%   |
| Bison Lenovo EasyCamera                                     | 3         | 1.74%   |
| Suyin HD WebCam                                             | 2         | 1.16%   |
| Realtek HP Webcam                                           | 2         | 1.16%   |
| Quanta HD Webcam                                            | 2         | 1.16%   |
| Microdia Lenovo EasyCamera                                  | 2         | 1.16%   |
| Microdia Integrated Webcam                                  | 2         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.16%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.16%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.16%   |
| Chicony HP Truevision HD camera                             | 2         | 1.16%   |
| Chicony HP HD Webcam                                        | 2         | 1.16%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.16%   |
| Bison BisonCam, NB Pro                                      | 2         | 1.16%   |
| Acer Integrated Camera                                      | 2         | 1.16%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.58%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.58%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.58%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.58%   |
| Syntek Integrated Camera                                    | 1         | 0.58%   |
| Syntek EasyCamera                                           | 1         | 0.58%   |
| Suyin WebCam                                                | 1         | 0.58%   |
| Suyin Acer HD Crystal Eye webcam                            | 1         | 0.58%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.58%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 41.86%  |
| Synaptics                  | 10        | 23.26%  |
| AuthenTec                  | 5         | 11.63%  |
| Upek                       | 3         | 6.98%   |
| STMicroelectronics         | 2         | 4.65%   |
| Shenzhen Goodix Technology | 2         | 4.65%   |
| Elan Microelectronics      | 2         | 4.65%   |
| LighTuning Technology      | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 9.3%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 9.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6.98%   |
| Validity Sensors VFS491                                                    | 2         | 4.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.65%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.65%   |
| Synaptics UWP WBDI Device                                                  | 2         | 4.65%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 4.65%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.33%   |
| AuthenTec AES1600                                                          | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 14        | 58.33%  |
| Broadcom    | 6         | 25%     |
| Lenovo      | 2         | 8.33%   |
| Upek        | 1         | 4.17%   |
| O2 Micro    | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 14        | 58.33%  |
| Broadcom 58200                                             | 5         | 20.83%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.17%   |
| Broadcom 5880                                              | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 127       | 59.91%  |
| 1     | 60        | 28.3%   |
| 2     | 22        | 10.38%  |
| 3     | 2         | 0.94%   |
| 4     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 40.19%  |
| Graphics card            | 20        | 18.69%  |
| Chipcard                 | 19        | 17.76%  |
| Net/wireless             | 9         | 8.41%   |
| Multimedia controller    | 5         | 4.67%   |
| Camera                   | 4         | 3.74%   |
| Storage                  | 2         | 1.87%   |
| Communication controller | 2         | 1.87%   |
| Bluetooth                | 2         | 1.87%   |
| Card reader              | 1         | 0.93%   |

