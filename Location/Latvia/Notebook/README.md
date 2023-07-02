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

Total: 321

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 23        | 10%     |
| ROSA R11           | 14        | 6.09%   |
| Ubuntu 18.04       | 9         | 3.91%   |
| ROSA R9            | 7         | 3.04%   |
| ROSA R10           | 6         | 2.61%   |
| OpenMandriva 4.3   | 6         | 2.61%   |
| Debian 11          | 6         | 2.61%   |
| Arch               | 6         | 2.61%   |
| ROSA R8.1          | 5         | 2.17%   |
| ROSA R11.1         | 5         | 2.17%   |
| Pop!_OS 22.04      | 5         | 2.17%   |
| Ubuntu 22.04       | 4         | 1.74%   |
| ROSA R8            | 4         | 1.74%   |
| ROSA 12.3          | 4         | 1.74%   |
| Pop!_OS 21.04      | 4         | 1.74%   |
| Pop!_OS 20.10      | 4         | 1.74%   |
| Manjaro            | 4         | 1.74%   |
| Linux Mint 21      | 4         | 1.74%   |
| Linux Mint 20.3    | 4         | 1.74%   |
| KDE neon 20.04     | 4         | 1.74%   |
| ArcoLinux Rolling  | 4         | 1.74%   |
| Arch Rolling       | 4         | 1.74%   |
| Ubuntu 19.10       | 3         | 1.3%    |
| ROSA 12.1          | 3         | 1.3%    |
| Linux Mint 19      | 3         | 1.3%    |
| Linux Mint 18.3    | 3         | 1.3%    |
| KDE neon 22.04     | 3         | 1.3%    |
| Fedora 37          | 3         | 1.3%    |
| Xubuntu 20.04      | 2         | 0.87%   |
| Ubuntu 21.10       | 2         | 0.87%   |
| Ubuntu 21.04       | 2         | 0.87%   |
| Ubuntu 20.10       | 2         | 0.87%   |
| ROSA 12.2          | 2         | 0.87%   |
| Pop!_OS 21.10      | 2         | 0.87%   |
| OpenMandriva 4.50  | 2         | 0.87%   |
| OpenMandriva 23.01 | 2         | 0.87%   |
| Linux Mint 20.1    | 2         | 0.87%   |
| Linux Mint 20      | 2         | 0.87%   |
| Fedora 34          | 2         | 0.87%   |
| Debian Testing     | 2         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 23.41%  |
| ROSA          | 35        | 17.07%  |
| Linux Mint    | 19        | 9.27%   |
| Pop!_OS       | 14        | 6.83%   |
| OpenMandriva  | 11        | 5.37%   |
| Debian        | 11        | 5.37%   |
| Arch          | 10        | 4.88%   |
| Manjaro       | 8         | 3.9%    |
| Fedora        | 8         | 3.9%    |
| KDE neon      | 7         | 3.41%   |
| ArcoLinux     | 5         | 2.44%   |
| Xubuntu       | 4         | 1.95%   |
| Elementary    | 3         | 1.46%   |
| Ubuntu Unity  | 2         | 0.98%   |
| openSUSE      | 2         | 0.98%   |
| Kali          | 2         | 0.98%   |
| Endless       | 2         | 0.98%   |
| Zorin         | 1         | 0.49%   |
| Void Linux    | 1         | 0.49%   |
| Ubuntu Budgie | 1         | 0.49%   |
| SteamOS       | 1         | 0.49%   |
| Solus         | 1         | 0.49%   |
| Peppermint    | 1         | 0.49%   |
| Parrot        | 1         | 0.49%   |
| NixOS         | 1         | 0.49%   |
| MX            | 1         | 0.49%   |
| Lubuntu       | 1         | 0.49%   |
| Kubuntu       | 1         | 0.49%   |
| GNOME OS      | 1         | 0.49%   |
| Garuda Linux  | 1         | 0.49%   |
| EndeavourOS   | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 6         | 2.33%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.33%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.33%   |
| 5.4.0-42-generic                   | 4         | 1.56%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.56%   |
| 5.8.0-7630-generic                 | 3         | 1.17%   |
| 5.15.0-58-generic                  | 3         | 1.17%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.17%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.17%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.17%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.17%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.17%   |
| 6.2.0-20-generic                   | 2         | 0.78%   |
| 6.1.1-desktop-1omv2290             | 2         | 0.78%   |
| 5.8.0-48-generic                   | 2         | 0.78%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.78%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.78%   |
| 5.4.0-80-generic                   | 2         | 0.78%   |
| 5.4.0-47-generic                   | 2         | 0.78%   |
| 5.4.0-26-generic                   | 2         | 0.78%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.78%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.78%   |
| 5.15.0-67-generic                  | 2         | 0.78%   |
| 5.15.0-56-generic                  | 2         | 0.78%   |
| 5.15.0-52-generic                  | 2         | 0.78%   |
| 5.15.0-46-generic                  | 2         | 0.78%   |
| 5.13.6-arch1-1                     | 2         | 0.78%   |
| 5.13.0-25-generic                  | 2         | 0.78%   |
| 5.11.0-43-generic                  | 2         | 0.78%   |
| 5.10.0-8-amd64                     | 2         | 0.78%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.78%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.78%   |
| 4.18.0-18-generic                  | 2         | 0.78%   |
| 4.15.0-54-generic                  | 2         | 0.78%   |
| 4.10.0-38-generic                  | 2         | 0.78%   |
| 6.3.2-arch1-1                      | 1         | 0.39%   |
| 6.3.1                              | 1         | 0.39%   |
| 6.2.6-76060206-generic             | 1         | 0.39%   |
| 6.1.9-x64v1-xanmod1                | 1         | 0.39%   |
| 6.1.8-200.fc37.x86_64              | 1         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 12.7%   |
| 4.15.0  | 22        | 9.02%   |
| 5.15.0  | 13        | 5.33%   |
| 5.11.0  | 11        | 4.51%   |
| 5.8.0   | 10        | 4.1%    |
| 5.13.0  | 10        | 4.1%    |
| 5.10.0  | 7         | 2.87%   |
| 5.3.0   | 6         | 2.46%   |
| 5.16.7  | 6         | 2.46%   |
| 4.9.20  | 6         | 2.46%   |
| 5.10.74 | 4         | 1.64%   |
| 5.0.0   | 4         | 1.64%   |
| 4.18.0  | 4         | 1.64%   |
| 5.17.1  | 3         | 1.23%   |
| 4.9.60  | 3         | 1.23%   |
| 4.9.41  | 3         | 1.23%   |
| 4.9.155 | 3         | 1.23%   |
| 4.1.34  | 3         | 1.23%   |
| 6.2.0   | 2         | 0.82%   |
| 6.1.1   | 2         | 0.82%   |
| 6.0.9   | 2         | 0.82%   |
| 5.4.83  | 2         | 0.82%   |
| 5.4.72  | 2         | 0.82%   |
| 5.4.32  | 2         | 0.82%   |
| 5.19.0  | 2         | 0.82%   |
| 5.15.79 | 2         | 0.82%   |
| 5.15.75 | 2         | 0.82%   |
| 5.14.0  | 2         | 0.82%   |
| 5.13.6  | 2         | 0.82%   |
| 5.13.12 | 2         | 0.82%   |
| 5.12.14 | 2         | 0.82%   |
| 4.9.9   | 2         | 0.82%   |
| 4.9.124 | 2         | 0.82%   |
| 4.4.0   | 2         | 0.82%   |
| 4.10.0  | 2         | 0.82%   |
| 4.1.38  | 2         | 0.82%   |
| 6.3.2   | 1         | 0.41%   |
| 6.3.1   | 1         | 0.41%   |
| 6.2.6   | 1         | 0.41%   |
| 6.1.9   | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 15.32%  |
| 5.15    | 24        | 10.21%  |
| 4.15    | 22        | 9.36%   |
| 4.9     | 16        | 6.81%   |
| 5.13    | 14        | 5.96%   |
| 5.10    | 14        | 5.96%   |
| 5.8     | 12        | 5.11%   |
| 5.11    | 11        | 4.68%   |
| 5.16    | 9         | 3.83%   |
| 6.1     | 8         | 3.4%    |
| 6.0     | 7         | 2.98%   |
| 5.3     | 6         | 2.55%   |
| 5.12    | 6         | 2.55%   |
| 5.19    | 5         | 2.13%   |
| 5.18    | 4         | 1.7%    |
| 5.17    | 4         | 1.7%    |
| 5.14    | 4         | 1.7%    |
| 5.0     | 4         | 1.7%    |
| 4.18    | 4         | 1.7%    |
| 4.1     | 4         | 1.7%    |
| 6.2     | 3         | 1.28%   |
| 5.5     | 3         | 1.28%   |
| 6.3     | 2         | 0.85%   |
| 5.9     | 2         | 0.85%   |
| 4.4     | 2         | 0.85%   |
| 4.19    | 2         | 0.85%   |
| 4.10    | 2         | 0.85%   |
| 5.7     | 1         | 0.43%   |
| 5.6     | 1         | 0.43%   |
| 5.2     | 1         | 0.43%   |
| 4.20    | 1         | 0.43%   |
| 4.13    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 191       | 95.5%   |
| i686   | 9         | 4.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 78        | 36.45%  |
| KDE5       | 44        | 20.56%  |
| KDE4       | 24        | 11.21%  |
| Unknown    | 18        | 8.41%   |
| XFCE       | 17        | 7.94%   |
| MATE       | 8         | 3.74%   |
| X-Cinnamon | 6         | 2.8%    |
| Budgie     | 4         | 1.87%   |
| Pantheon   | 3         | 1.4%    |
| LXQt       | 3         | 1.4%    |
| KDE        | 3         | 1.4%    |
| Unity      | 2         | 0.93%   |
| Cinnamon   | 2         | 0.93%   |
| sway       | 1         | 0.47%   |
| LXDE       | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 164       | 79.23%  |
| Wayland | 31        | 14.98%  |
| Unknown | 9         | 4.35%   |
| Tty     | 3         | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 36.67%  |
| SDDM    | 35        | 16.67%  |
| GDM     | 32        | 15.24%  |
| KDM     | 24        | 11.43%  |
| LightDM | 19        | 9.05%   |
| TDM     | 11        | 5.24%   |
| GDM3    | 9         | 4.29%   |
| SLiM    | 1         | 0.48%   |
| MDM     | 1         | 0.48%   |
| LDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 103       | 49.28%  |
| Unknown     | 43        | 20.57%  |
| lv_LV       | 23        | 11%     |
| ru_RU       | 22        | 10.53%  |
| en_GB       | 9         | 4.31%   |
| C           | 4         | 1.91%   |
| ru_RU.UTF_8 | 1         | 0.48%   |
| POSIX       | 1         | 0.48%   |
| fr_FR       | 1         | 0.48%   |
| en_AG       | 1         | 0.48%   |
| de_DE       | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 108       | 53.2%   |
| EFI  | 95        | 46.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 156       | 76.1%   |
| Btrfs   | 18        | 8.78%   |
| Unknown | 16        | 7.8%    |
| Overlay | 12        | 5.85%   |
| Tmpfs   | 2         | 0.98%   |
| Zfs     | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 41.35%  |
| GPT     | 79        | 37.98%  |
| MBR     | 43        | 20.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 88.52%  |
| Yes       | 24        | 11.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 149       | 73.04%  |
| Yes       | 55        | 26.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 24.5%   |
| ASUSTek Computer    | 33        | 16.5%   |
| Hewlett-Packard     | 30        | 15%     |
| Dell                | 26        | 13%     |
| Acer                | 23        | 11.5%   |
| Toshiba             | 6         | 3%      |
| MSI                 | 6         | 3%      |
| Fujitsu Siemens     | 5         | 2.5%    |
| Samsung Electronics | 4         | 2%      |
| HUAWEI              | 3         | 1.5%    |
| Packard Bell        | 2         | 1%      |
| Apple               | 2         | 1%      |
| Wortmann AG         | 1         | 0.5%    |
| Valve               | 1         | 0.5%    |
| Timi                | 1         | 0.5%    |
| Sony                | 1         | 0.5%    |
| Razer               | 1         | 0.5%    |
| Quanta              | 1         | 0.5%    |
| Gigabyte Technology | 1         | 0.5%    |
| Fujitsu             | 1         | 0.5%    |
| eMachines           | 1         | 0.5%    |
| Chuwi               | 1         | 0.5%    |
| Advent              | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.5%    |
| ASUS X553MA                                           | 3         | 1.5%    |
| Toshiba Satellite C660                                | 2         | 1%      |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1%      |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 1%      |
| HP G62                                                | 2         | 1%      |
| HP EliteBook 8440p                                    | 2         | 1%      |
| HP 250 G6 Notebook PC                                 | 2         | 1%      |
| Fujitsu Siemens LIFEBOOK S6420                        | 2         | 1%      |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 1%      |
| ASUS X551MA                                           | 2         | 1%      |
| Wortmann AG CR700                                     | 1         | 0.5%    |
| Valve Jupiter                                         | 1         | 0.5%    |
| Toshiba Satellite L850-1LK                            | 1         | 0.5%    |
| Toshiba Satellite L750                                | 1         | 0.5%    |
| Toshiba Satellite L350                                | 1         | 0.5%    |
| Toshiba Satellite C50D-B                              | 1         | 0.5%    |
| Timi A35S                                             | 1         | 0.5%    |
| Sony VPCCW2S8E                                        | 1         | 0.5%    |
| Samsung R528/R728                                     | 1         | 0.5%    |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.5%    |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.5%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.5%    |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.5%    |
| Quanta TW8/SW8/DW8                                    | 1         | 0.5%    |
| Packard Bell EasyNote LM85                            | 1         | 0.5%    |
| Packard Bell EasyNote LE69KB                          | 1         | 0.5%    |
| MSI Modern 14 B4MW                                    | 1         | 0.5%    |
| MSI GV72 7RE                                          | 1         | 0.5%    |
| MSI GT62VR 6RE                                        | 1         | 0.5%    |
| MSI GP75 Leopard 9SD                                  | 1         | 0.5%    |
| MSI GF63 Thin 9RCX                                    | 1         | 0.5%    |
| MSI CR500                                             | 1         | 0.5%    |
| Lenovo ZIWB2                                          | 1         | 0.5%    |
| Lenovo Y50-70 20378                                   | 1         | 0.5%    |
| Lenovo V110-15IAP 80TG                                | 1         | 0.5%    |
| Lenovo ThinkPad X260 20F5S5Q200                       | 1         | 0.5%    |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.5%    |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.5%    |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 28        | 14%     |
| Acer Aspire              | 14        | 7%      |
| HP EliteBook             | 11        | 5.5%    |
| Dell Inspiron            | 11        | 5.5%    |
| Lenovo IdeaPad           | 10        | 5%      |
| Dell Latitude            | 10        | 5%      |
| Toshiba Satellite        | 6         | 3%      |
| HP ProBook               | 5         | 2.5%    |
| HP Pavilion              | 5         | 2.5%    |
| ASUS VivoBook            | 4         | 2%      |
| Lenovo Legion            | 3         | 1.5%    |
| HP 250                   | 3         | 1.5%    |
| Fujitsu Siemens LIFEBOOK | 3         | 1.5%    |
| ASUS X553MA              | 3         | 1.5%    |
| Packard Bell EasyNote    | 2         | 1%      |
| HP Laptop                | 2         | 1%      |
| HP G62                   | 2         | 1%      |
| Fujitsu Siemens AMILO    | 2         | 1%      |
| Dell XPS                 | 2         | 1%      |
| ASUS ZenBook             | 2         | 1%      |
| ASUS X551MA              | 2         | 1%      |
| ASUS TUF                 | 2         | 1%      |
| ASUS ASUS                | 2         | 1%      |
| Acer Nitro               | 2         | 1%      |
| Acer Extensa             | 2         | 1%      |
| Wortmann AG CR700        | 1         | 0.5%    |
| Valve Jupiter            | 1         | 0.5%    |
| Timi A35S                | 1         | 0.5%    |
| Sony VPCCW2S8E           | 1         | 0.5%    |
| Samsung R528             | 1         | 0.5%    |
| Samsung 355V4C           | 1         | 0.5%    |
| Samsung 350V5C           | 1         | 0.5%    |
| Samsung 300V3A           | 1         | 0.5%    |
| Razer Blade              | 1         | 0.5%    |
| Quanta TW8               | 1         | 0.5%    |
| MSI Modern               | 1         | 0.5%    |
| MSI GV72                 | 1         | 0.5%    |
| MSI GT62VR               | 1         | 0.5%    |
| MSI GP75                 | 1         | 0.5%    |
| MSI GF63                 | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 10%     |
| 2013 | 18        | 9%      |
| 2014 | 17        | 8.5%    |
| 2020 | 15        | 7.5%    |
| 2018 | 14        | 7%      |
| 2010 | 14        | 7%      |
| 2011 | 13        | 6.5%    |
| 2008 | 13        | 6.5%    |
| 2015 | 12        | 6%      |
| 2012 | 12        | 6%      |
| 2017 | 11        | 5.5%    |
| 2021 | 10        | 5%      |
| 2016 | 9         | 4.5%    |
| 2009 | 9         | 4.5%    |
| 2007 | 7         | 3.5%    |
| 2022 | 4         | 2%      |
| 2006 | 2         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 200       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 183       | 90.59%  |
| Enabled  | 19        | 9.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 199       | 99.5%   |
| Yes  | 1         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 59        | 29.06%  |
| 4.01-8.0   | 56        | 27.59%  |
| 8.01-16.0  | 30        | 14.78%  |
| 16.01-24.0 | 28        | 13.79%  |
| 32.01-64.0 | 10        | 4.93%   |
| 2.01-3.0   | 8         | 3.94%   |
| 1.01-2.0   | 8         | 3.94%   |
| 24.01-32.0 | 2         | 0.99%   |
| 0.51-1.0   | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 77        | 33.77%  |
| 2.01-3.0   | 58        | 25.44%  |
| 4.01-8.0   | 29        | 12.72%  |
| 0.51-1.0   | 28        | 12.28%  |
| 3.01-4.0   | 23        | 10.09%  |
| 8.01-16.0  | 10        | 4.39%   |
| 16.01-24.0 | 2         | 0.88%   |
| 0.01-0.5   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 147       | 72.41%  |
| 2      | 47        | 23.15%  |
| 3      | 6         | 2.96%   |
| 0      | 2         | 0.99%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 57.84%  |
| Yes       | 86        | 42.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 88.61%  |
| No        | 23        | 11.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 99%     |
| No        | 2         | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 74.88%  |
| No        | 51        | 25.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 200       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 154       | 71.96%  |
| Liepāja                | 6         | 2.8%    |
| Jelgava                 | 6         | 2.8%    |
| Daugavpils              | 6         | 2.8%    |
| Jūrmala                | 3         | 1.4%    |
| Adazi                   | 3         | 1.4%    |
| Valmiera                | 2         | 0.93%   |
| Saulkrasti              | 2         | 0.93%   |
| Rēzekne                | 2         | 0.93%   |
| Malpils                 | 2         | 0.93%   |
| Jaunmarupe              | 2         | 0.93%   |
| Iecava                  | 2         | 0.93%   |
| Cēsis                  | 2         | 0.93%   |
| Zvejniekciems           | 1         | 0.47%   |
| Ventspils               | 1         | 0.47%   |
| Ulbroka                 | 1         | 0.47%   |
| Tukums                  | 1         | 0.47%   |
| Tiraine                 | 1         | 0.47%   |
| Smiltene                | 1         | 0.47%   |
| Saldus                  | 1         | 0.47%   |
| Pļaviņas              | 1         | 0.47%   |
| Nereta                  | 1         | 0.47%   |
| Lizums                  | 1         | 0.47%   |
| Limbaži                | 1         | 0.47%   |
| Kuldīga                | 1         | 0.47%   |
| Ķekava                 | 1         | 0.47%   |
| Jēkabpils Municipality | 1         | 0.47%   |
| Jēkabpils              | 1         | 0.47%   |
| Inčukalns              | 1         | 0.47%   |
| Garkalne                | 1         | 0.47%   |
| Garciems                | 1         | 0.47%   |
| Dobele                  | 1         | 0.47%   |
| Bukulti                 | 1         | 0.47%   |
| Aizpute                 | 1         | 0.47%   |
| Aizkraukle              | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 38        | 50     | 15.51%  |
| Seagate                     | 34        | 40     | 13.88%  |
| Kingston                    | 28        | 39     | 11.43%  |
| WDC                         | 24        | 33     | 9.8%    |
| Toshiba                     | 24        | 27     | 9.8%    |
| Hitachi                     | 10        | 13     | 4.08%   |
| Unknown                     | 8         | 9      | 3.27%   |
| Micron Technology           | 8         | 9      | 3.27%   |
| HGST                        | 8         | 16     | 3.27%   |
| SK hynix                    | 7         | 7      | 2.86%   |
| SanDisk                     | 7         | 16     | 2.86%   |
| Intel                       | 5         | 7      | 2.04%   |
| A-DATA Technology           | 5         | 6      | 2.04%   |
| Patriot                     | 4         | 10     | 1.63%   |
| KIOXIA                      | 4         | 6      | 1.63%   |
| Crucial                     | 4         | 4      | 1.63%   |
| LITEON                      | 2         | 2      | 0.82%   |
| Integral                    | 2         | 2      | 0.82%   |
| Verbatim                    | 1         | 1      | 0.41%   |
| USB                         | 1         | 1      | 0.41%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.41%   |
| SPCC                        | 1         | 1      | 0.41%   |
| Realtek                     | 1         | 1      | 0.41%   |
| PNY                         | 1         | 1      | 0.41%   |
| Plextor                     | 1         | 1      | 0.41%   |
| Platinet                    | 1         | 1      | 0.41%   |
| Phison Electronics          | 1         | 1      | 0.41%   |
| Phison                      | 1         | 1      | 0.41%   |
| OCZ                         | 1         | 1      | 0.41%   |
| Netac                       | 1         | 1      | 0.41%   |
| LITEONIT                    | 1         | 1      | 0.41%   |
| LITEON C                    | 1         | 1      | 0.41%   |
| Lexar                       | 1         | 1      | 0.41%   |
| Kingston Technology Company | 1         | 1      | 0.41%   |
| KingSpec                    | 1         | 1      | 0.41%   |
| Kingchuxing                 | 1         | 6      | 0.41%   |
| Intenso                     | 1         | 1      | 0.41%   |
| Hrdtac                      | 1         | 5      | 0.41%   |
| Fujitsu                     | 1         | 1      | 0.41%   |
| China                       | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 7         | 2.78%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 2.38%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 2.38%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.59%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 1.59%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.59%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.19%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.19%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.19%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 1.19%   |
| Hitachi HTS545050B9A300 500GB       | 3         | 1.19%   |
| HGST HTS545050A7E680 500GB          | 3         | 1.19%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.79%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.79%   |
| Toshiba MK8034GSX 80GB              | 2         | 0.79%   |
| Toshiba MK6465GSX 640GB             | 2         | 0.79%   |
| SK hynix HFM512GDJTNG-8310A 512GB   | 2         | 0.79%   |
| SK hynix BC511 NVMe 256GB           | 2         | 0.79%   |
| Seagate ST9160821AS 160GB           | 2         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.79%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 2         | 0.79%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.79%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.79%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.79%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.79%   |
| Samsung MZALQ256HAJD-000L2 256GB    | 2         | 0.79%   |
| Samsung HM321HI 320GB               | 2         | 0.79%   |
| Patriot Burst 240GB SSD             | 2         | 0.79%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 2         | 0.79%   |
| Kingston SV300S37A60G 64GB SSD      | 2         | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.79%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.79%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.79%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.79%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.4%    |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.4%    |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.4%    |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 40     | 35.42%  |
| WDC                 | 20        | 28     | 20.83%  |
| Toshiba             | 19        | 22     | 19.79%  |
| Hitachi             | 10        | 13     | 10.42%  |
| HGST                | 8         | 16     | 8.33%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| Fujitsu             | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 25        | 35     | 30.12%  |
| Samsung Electronics | 20        | 27     | 24.1%   |
| A-DATA Technology   | 5         | 6      | 6.02%   |
| Patriot             | 4         | 10     | 4.82%   |
| Crucial             | 4         | 4      | 4.82%   |
| SanDisk             | 3         | 5      | 3.61%   |
| Micron Technology   | 3         | 3      | 3.61%   |
| LITEON              | 2         | 2      | 2.41%   |
| Integral            | 2         | 2      | 2.41%   |
| Verbatim            | 1         | 1      | 1.2%    |
| USB                 | 1         | 1      | 1.2%    |
| Toshiba             | 1         | 1      | 1.2%    |
| SPCC                | 1         | 1      | 1.2%    |
| PNY                 | 1         | 1      | 1.2%    |
| Plextor             | 1         | 1      | 1.2%    |
| Platinet            | 1         | 1      | 1.2%    |
| OCZ                 | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| LITEON C            | 1         | 1      | 1.2%    |
| Lexar               | 1         | 1      | 1.2%    |
| KingSpec            | 1         | 1      | 1.2%    |
| Intenso             | 1         | 1      | 1.2%    |
| China               | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 93        | 124    | 39.74%  |
| SSD     | 78        | 109    | 33.33%  |
| NVMe    | 55        | 76     | 23.5%   |
| MMC     | 6         | 7      | 2.56%   |
| Unknown | 2         | 12     | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 151       | 235    | 68.95%  |
| NVMe | 55        | 75     | 25.11%  |
| SAS  | 7         | 11     | 3.2%    |
| MMC  | 6         | 7      | 2.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 170    | 71.86%  |
| 0.51-1.0   | 43        | 59     | 25.75%  |
| 1.01-2.0   | 4         | 4      | 2.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 33.94%  |
| 251-500        | 54        | 24.43%  |
| 501-1000       | 28        | 12.67%  |
| 1-20           | 18        | 8.14%   |
| 51-100         | 16        | 7.24%   |
| 1001-2000      | 15        | 6.79%   |
| 21-50          | 6         | 2.71%   |
| Unknown        | 5         | 2.26%   |
| 2001-3000      | 3         | 1.36%   |
| More than 3000 | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 97        | 43.5%   |
| 21-50     | 32        | 14.35%  |
| 51-100    | 28        | 12.56%  |
| 101-250   | 26        | 11.66%  |
| 251-500   | 17        | 7.62%   |
| 501-1000  | 11        | 4.93%   |
| 1001-2000 | 6         | 2.69%   |
| Unknown   | 5         | 2.24%   |
| 2001-3000 | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 11.54%  |
| HGST HTS545050A7E680 500GB           | 2         | 2      | 7.69%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 3.85%   |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.85%   |
| Toshiba MK8034GSX 80GB               | 1         | 1      | 3.85%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 3.85%   |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 3.85%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB            | 1         | 3      | 3.85%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.85%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 3.85%   |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 3.85%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 3.85%   |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 3.85%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 3.85%   |
| HGST HTS721010A9E630 1TB             | 1         | 2      | 3.85%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 3.85%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 30.77%  |
| HGST                | 6         | 8      | 23.08%  |
| Toshiba             | 4         | 4      | 15.38%  |
| WDC                 | 3         | 6      | 11.54%  |
| Kingston            | 2         | 2      | 7.69%   |
| Hitachi             | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 33.33%  |
| HGST                | 6         | 8      | 25%     |
| Toshiba             | 4         | 4      | 16.67%  |
| WDC                 | 3         | 6      | 12.5%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 31     | 92%     |
| SSD  | 2         | 2      | 8%      |

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
| Works    | 97        | 152    | 45.97%  |
| Detected | 87        | 141    | 41.23%  |
| Malfunc  | 25        | 33     | 11.85%  |
| Failed   | 2         | 2      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 156       | 65.55%  |
| AMD                          | 23        | 9.66%   |
| Samsung Electronics          | 18        | 7.56%   |
| SanDisk                      | 8         | 3.36%   |
| SK hynix                     | 7         | 2.94%   |
| Micron Technology            | 5         | 2.1%    |
| KIOXIA                       | 5         | 2.1%    |
| Kingston Technology Company  | 4         | 1.68%   |
| Toshiba America Info Systems | 3         | 1.26%   |
| Union Memory (Shenzhen)      | 2         | 0.84%   |
| Phison Electronics           | 2         | 0.84%   |
| Nvidia                       | 2         | 0.84%   |
| Silicon Motion               | 1         | 0.42%   |
| Silicon Image                | 1         | 0.42%   |
| ADATA Technology             | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 6.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 15        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 4.26%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 3.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.71%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.33%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.94%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 1.94%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.16%   |
| Intel SSD 660P Series                                                            | 3         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.16%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.78%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.78%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.78%   |
| Micron 2200S NVMe SSD                                                            | 2         | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 161       | 64.14%  |
| NVMe | 58        | 23.11%  |
| IDE  | 19        | 7.57%   |
| RAID | 13        | 5.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 167       | 83.5%   |
| AMD    | 33        | 16.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.5%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 2.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 2%      |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.5%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.5%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.5%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1%      |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1%      |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1%      |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1%      |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1%      |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1%      |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 1%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1%      |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1%      |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1%      |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.5%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 26%     |
| Intel Core i7           | 32        | 16%     |
| Intel Core i3           | 19        | 9.5%    |
| Intel Core 2 Duo        | 18        | 9%      |
| Other                   | 14        | 7%      |
| Intel Celeron           | 14        | 7%      |
| Intel Pentium           | 8         | 4%      |
| AMD Ryzen 5             | 7         | 3.5%    |
| AMD Ryzen 7             | 6         | 3%      |
| Intel Pentium Dual-Core | 3         | 1.5%    |
| Intel Pentium Dual      | 3         | 1.5%    |
| Intel Genuine           | 3         | 1.5%    |
| AMD A10                 | 3         | 1.5%    |
| Intel Core 2            | 2         | 1%      |
| AMD Turion 64 X2 Mobile | 2         | 1%      |
| AMD Ryzen 7 PRO         | 2         | 1%      |
| AMD Ryzen 3             | 2         | 1%      |
| AMD E1                  | 2         | 1%      |
| AMD A8                  | 2         | 1%      |
| Intel Xeon              | 1         | 0.5%    |
| Intel Atom              | 1         | 0.5%    |
| AMD Ryzen 5 PRO         | 1         | 0.5%    |
| AMD E2                  | 1         | 0.5%    |
| AMD E                   | 1         | 0.5%    |
| AMD C-70                | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 121       | 60.2%   |
| 4      | 59        | 29.35%  |
| 6      | 8         | 3.98%   |
| 8      | 7         | 3.48%   |
| 1      | 4         | 1.99%   |
| 14     | 1         | 0.5%    |
| 10     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 200       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 134       | 66.67%  |
| 1      | 67        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 198       | 99%     |
| 32-bit         | 1         | 0.5%    |
| Unknown        | 1         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 20.49%  |
| 0x306a9    | 13        | 6.34%   |
| 0x406e3    | 11        | 5.37%   |
| 0x206a7    | 10        | 4.88%   |
| 0x6fd      | 9         | 4.39%   |
| 0x30678    | 9         | 4.39%   |
| 0x1067a    | 9         | 4.39%   |
| 0x906ea    | 7         | 3.41%   |
| 0x20655    | 7         | 3.41%   |
| 0x806c1    | 6         | 2.93%   |
| 0x306d4    | 6         | 2.93%   |
| 0x40651    | 5         | 2.44%   |
| 0x806ec    | 4         | 1.95%   |
| 0x806ea    | 4         | 1.95%   |
| 0x806e9    | 4         | 1.95%   |
| 0x306c3    | 4         | 1.95%   |
| 0x08108102 | 4         | 1.95%   |
| 0x06001119 | 4         | 1.95%   |
| 0xa0652    | 3         | 1.46%   |
| 0x906e9    | 3         | 1.46%   |
| 0x506e3    | 3         | 1.46%   |
| 0x10676    | 3         | 1.46%   |
| 0x05000119 | 3         | 1.46%   |
| 0x6fa      | 2         | 0.98%   |
| 0x6f6      | 2         | 0.98%   |
| 0x406c3    | 2         | 0.98%   |
| 0x20652    | 2         | 0.98%   |
| 0x0a50000c | 2         | 0.98%   |
| 0x08600103 | 2         | 0.98%   |
| 0x08108109 | 2         | 0.98%   |
| 0x906ed    | 1         | 0.49%   |
| 0x806eb    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706a8    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x6ec      | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x30673    | 1         | 0.49%   |
| 0x106e5    | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 14.5%   |
| Skylake       | 17        | 8.5%    |
| Core          | 17        | 8.5%    |
| IvyBridge     | 16        | 8%      |
| Silvermont    | 13        | 6.5%    |
| Westmere      | 12        | 6%      |
| SandyBridge   | 12        | 6%      |
| Penryn        | 12        | 6%      |
| Haswell       | 12        | 6%      |
| Zen+          | 8         | 4%      |
| TigerLake     | 8         | 4%      |
| Zen 2         | 7         | 3.5%    |
| Broadwell     | 6         | 3%      |
| Unknown       | 5         | 2.5%    |
| Piledriver    | 4         | 2%      |
| CometLake     | 4         | 2%      |
| Bobcat        | 3         | 1.5%    |
| Zen 3         | 2         | 1%      |
| Puma          | 2         | 1%      |
| K8 Hammer     | 2         | 1%      |
| Goldmont plus | 2         | 1%      |
| Excavator     | 2         | 1%      |
| P6            | 1         | 0.5%    |
| Nehalem       | 1         | 0.5%    |
| Jaguar        | 1         | 0.5%    |
| Icelake       | 1         | 0.5%    |
| Goldmont      | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 58.47%  |
| Nvidia | 59        | 23.79%  |
| AMD    | 44        | 17.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 5.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 4.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.7%    |
| AMD Renoir                                                                               | 7         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.93%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.54%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.54%   |
| Intel HD Graphics 620                                                                    | 4         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.54%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.77%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.77%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.77%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.77%   |
| Intel HD Graphics 630                                                                    | 2         | 0.77%   |
| Intel HD Graphics 530                                                                    | 2         | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.77%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 49.5%   |
| Intel + Nvidia | 38        | 19%     |
| 1 x AMD        | 29        | 14.5%   |
| 1 x Nvidia     | 18        | 9%      |
| Intel + AMD    | 7         | 3.5%    |
| 2 x AMD        | 5         | 2.5%    |
| AMD + Nvidia   | 3         | 1.5%    |
| 2 x Intel      | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 167       | 80.68%  |
| Proprietary | 33        | 15.94%  |
| Unknown     | 7         | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 54.81%  |
| 1.01-2.0   | 38        | 18.27%  |
| 0.01-0.5   | 26        | 12.5%   |
| 0.51-1.0   | 13        | 6.25%   |
| 3.01-4.0   | 12        | 5.77%   |
| 7.01-8.0   | 3         | 1.44%   |
| 5.01-6.0   | 2         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 24.42%  |
| LG Display              | 35        | 16.13%  |
| Samsung Electronics     | 29        | 13.36%  |
| BOE                     | 25        | 11.52%  |
| Chimei Innolux          | 21        | 9.68%   |
| Dell                    | 13        | 5.99%   |
| Chi Mei Optoelectronics | 7         | 3.23%   |
| Lenovo                  | 5         | 2.3%    |
| PANDA                   | 4         | 1.84%   |
| Goldstar                | 4         | 1.84%   |
| BenQ                    | 3         | 1.38%   |
| Sony                    | 2         | 0.92%   |
| Seiko/Epson             | 2         | 0.92%   |
| InfoVision              | 2         | 0.92%   |
| Hitachi                 | 2         | 0.92%   |
| Apple                   | 2         | 0.92%   |
| Tianma XM               | 1         | 0.46%   |
| Sharp                   | 1         | 0.46%   |
| Quanta Display          | 1         | 0.46%   |
| Philips                 | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| LGD                     | 1         | 0.46%   |
| LG Philips              | 1         | 0.46%   |
| Acer                    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 1.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 1.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.34%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.89%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 2         | 0.89%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.89%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.89%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.89%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.89%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.89%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.45%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.45%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 0.45%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.45%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.45%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch     | 1         | 0.45%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 1         | 0.45%   |
| Samsung Electronics S24E650 SAM0CC2 1920x1200 518x324mm 24.1-inch        | 1         | 0.45%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch        | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 36.63%  |
| 1366x768 (WXGA)    | 69        | 34.16%  |
| 1600x900 (HD+)     | 15        | 7.43%   |
| 1280x800 (WXGA)    | 12        | 5.94%   |
| 3840x2160 (4K)     | 5         | 2.48%   |
| 2560x1440 (QHD)    | 5         | 2.48%   |
| 1440x900 (WXGA+)   | 5         | 2.48%   |
| 1920x1200 (WUXGA)  | 4         | 1.98%   |
| 3440x1440          | 3         | 1.49%   |
| 1280x1024 (SXGA)   | 2         | 0.99%   |
| 7680x2160          | 1         | 0.5%    |
| 3456x2160          | 1         | 0.5%    |
| 3000x2000          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1360x768           | 1         | 0.5%    |
| 1280x720 (HD)      | 1         | 0.5%    |
| Unknown            | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 106       | 48.62%  |
| 14      | 24        | 11.01%  |
| 13      | 20        | 9.17%   |
| 17      | 19        | 8.72%   |
| 12      | 11        | 5.05%   |
| 24      | 10        | 4.59%   |
| 27      | 4         | 1.83%   |
| Unknown | 4         | 1.83%   |
| 40      | 3         | 1.38%   |
| 21      | 3         | 1.38%   |
| 11      | 3         | 1.38%   |
| 35      | 2         | 0.92%   |
| 23      | 2         | 0.92%   |
| 19      | 2         | 0.92%   |
| 84      | 1         | 0.46%   |
| 43      | 1         | 0.46%   |
| 34      | 1         | 0.46%   |
| 31      | 1         | 0.46%   |
| 18      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 138       | 63.59%  |
| 351-400     | 23        | 10.6%   |
| 201-300     | 22        | 10.14%  |
| 501-600     | 16        | 7.37%   |
| 801-900     | 5         | 2.3%    |
| 401-500     | 5         | 2.3%    |
| Unknown     | 4         | 1.84%   |
| 701-800     | 1         | 0.46%   |
| 601-700     | 1         | 0.46%   |
| 1501-2000   | 1         | 0.46%   |
| 901-1000    | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 82.23%  |
| 16/10   | 23        | 11.68%  |
| Unknown | 4         | 2.03%   |
| 3/2     | 3         | 1.52%   |
| 21/9    | 3         | 1.52%   |
| 5/4     | 2         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 104       | 47.71%  |
| 81-90          | 39        | 17.89%  |
| 121-130        | 16        | 7.34%   |
| 201-250        | 12        | 5.5%    |
| 61-70          | 11        | 5.05%   |
| 71-80          | 5         | 2.29%   |
| 351-500        | 4         | 1.83%   |
| 301-350        | 4         | 1.83%   |
| 151-200        | 4         | 1.83%   |
| 501-1000       | 4         | 1.83%   |
| Unknown        | 4         | 1.83%   |
| 51-60          | 3         | 1.38%   |
| 251-300        | 2         | 0.92%   |
| 131-140        | 2         | 0.92%   |
| 91-100         | 2         | 0.92%   |
| More than 1000 | 1         | 0.46%   |
| 141-150        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 39.63%  |
| 101-120       | 76        | 35.02%  |
| 51-100        | 37        | 17.05%  |
| 161-240       | 9         | 4.15%   |
| Unknown       | 4         | 1.84%   |
| More than 240 | 3         | 1.38%   |
| 1-50          | 2         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 81.37%  |
| 2     | 29        | 14.22%  |
| 0     | 5         | 2.45%   |
| 3     | 4         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 109       | 33.44%  |
| Intel                    | 107       | 32.82%  |
| Qualcomm Atheros         | 49        | 15.03%  |
| Broadcom                 | 21        | 6.44%   |
| Broadcom Limited         | 9         | 2.76%   |
| Marvell Technology Group | 6         | 1.84%   |
| Ralink                   | 4         | 1.23%   |
| Xiaomi                   | 2         | 0.61%   |
| vivo                     | 2         | 0.61%   |
| TP-Link                  | 2         | 0.61%   |
| Samsung Electronics      | 2         | 0.61%   |
| Ralink Technology        | 2         | 0.61%   |
| Nvidia                   | 2         | 0.61%   |
| MediaTek                 | 2         | 0.61%   |
| Hewlett-Packard          | 2         | 0.61%   |
| U-Blox                   | 1         | 0.31%   |
| Qualcomm                 | 1         | 0.31%   |
| Lenovo                   | 1         | 0.31%   |
| Huawei Technologies      | 1         | 0.31%   |
| Google                   | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 16.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 7.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.03%   |
| Intel Wireless 8260                                               | 8         | 2.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.77%   |
| Intel Wireless 3160                                               | 7         | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.77%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.01%   |
| Intel Wireless 7260                                               | 4         | 1.01%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.01%   |
| Intel Wireless 7265                                               | 3         | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.51%   |
| vivo 1820                                                         | 2         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 106       | 51.96%  |
| Qualcomm Atheros      | 43        | 21.08%  |
| Realtek Semiconductor | 25        | 12.25%  |
| Broadcom              | 15        | 7.35%   |
| Broadcom Limited      | 5         | 2.45%   |
| Ralink                | 4         | 1.96%   |
| TP-Link               | 2         | 0.98%   |
| Ralink Technology     | 2         | 0.98%   |
| Qualcomm              | 1         | 0.49%   |
| MediaTek              | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 4.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.92%   |
| Intel Wireless 8260                                                     | 8         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.43%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.43%   |
| Intel Wireless 3160                                                     | 7         | 3.43%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.43%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.96%   |
| Intel Wireless 7260                                                     | 4         | 1.96%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.96%   |
| Intel Wireless 7265                                                     | 3         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.98%   |
| Intel WiFi Link 5100                                                    | 2         | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 55.61%  |
| Intel                    | 39        | 20.86%  |
| Qualcomm Atheros         | 13        | 6.95%   |
| Broadcom                 | 10        | 5.35%   |
| Marvell Technology Group | 6         | 3.21%   |
| Broadcom Limited         | 4         | 2.14%   |
| Xiaomi                   | 2         | 1.07%   |
| vivo                     | 2         | 1.07%   |
| Nvidia                   | 2         | 1.07%   |
| MediaTek                 | 1         | 0.53%   |
| Lenovo                   | 1         | 0.53%   |
| Huawei Technologies      | 1         | 0.53%   |
| Hewlett-Packard          | 1         | 0.53%   |
| Google                   | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 35.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 16.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.67%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.14%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.6%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.07%   |
| vivo 1820                                                         | 2         | 1.07%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.07%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.07%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.07%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.07%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.07%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.07%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.07%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.53%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.53%   |
| MediaTek WP15                                                     | 1         | 0.53%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.53%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.53%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 51.97%  |
| Ethernet | 179       | 46.98%  |
| Modem    | 4         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 80.77%  |
| Ethernet | 40        | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 84%     |
| 1     | 29        | 14.5%   |
| 3     | 2         | 1%      |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 189       | 94.5%   |
| Yes  | 11        | 5.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 42.11%  |
| Realtek Semiconductor           | 16        | 10.53%  |
| Lite-On Technology              | 13        | 8.55%   |
| Qualcomm Atheros Communications | 12        | 7.89%   |
| IMC Networks                    | 12        | 7.89%   |
| Broadcom                        | 11        | 7.24%   |
| Dell                            | 5         | 3.29%   |
| Hewlett-Packard                 | 4         | 2.63%   |
| Toshiba                         | 3         | 1.97%   |
| Ralink                          | 2         | 1.32%   |
| Cambridge Silicon Radio         | 2         | 1.32%   |
| Apple                           | 2         | 1.32%   |
| USI                             | 1         | 0.66%   |
| Taiyo Yuden                     | 1         | 0.66%   |
| Ralink Technology               | 1         | 0.66%   |
| Qcom                            | 1         | 0.66%   |
| Foxconn / Hon Hai               | 1         | 0.66%   |
| ASUSTek Computer                | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 17.76%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.89%   |
| Intel AX201 Bluetooth                               | 9         | 5.92%   |
| Realtek Bluetooth Radio                             | 8         | 5.26%   |
| Intel AX200 Bluetooth                               | 6         | 3.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.29%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.29%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.97%   |
| Lite-On Bluetooth Device                            | 3         | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.97%   |
| IMC Networks Bluetooth Device                       | 3         | 1.97%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.32%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.32%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.32%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.32%   |
| Intel Bluetooth Device                              | 2         | 1.32%   |
| Intel AX210 Bluetooth                               | 2         | 1.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.32%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.32%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.32%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.32%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.32%   |
| USI Bluetooth Device                                | 1         | 0.66%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.66%   |
| Toshiba Bluetooth Device                            | 1         | 0.66%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.66%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.66%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.66%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.66%   |
| Lite-On BCM43142A0                                  | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 165       | 67.35%  |
| AMD                   | 37        | 15.1%   |
| Nvidia                | 30        | 12.24%  |
| C-Media Electronics   | 3         | 1.22%   |
| Realtek Semiconductor | 2         | 0.82%   |
| Logitech              | 2         | 0.82%   |
| Microsoft             | 1         | 0.41%   |
| Lenovo                | 1         | 0.41%   |
| GYROCOM C&C           | 1         | 0.41%   |
| GN Netcom             | 1         | 0.41%   |
| Creative Technology   | 1         | 0.41%   |
| Apple                 | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 6.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 5.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.13%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.39%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.04%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.04%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 25.79%  |
| SK hynix            | 38        | 23.9%   |
| Unknown             | 24        | 15.09%  |
| Kingston            | 23        | 14.47%  |
| Micron Technology   | 13        | 8.18%   |
| G.Skill             | 3         | 1.89%   |
| Elpida              | 3         | 1.89%   |
| Crucial             | 3         | 1.89%   |
| Ramaxel Technology  | 2         | 1.26%   |
| Corsair             | 2         | 1.26%   |
| A-DATA Technology   | 2         | 1.26%   |
| Toshiba             | 1         | 0.63%   |
| PNY                 | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Nanya Technology    | 1         | 0.63%   |
| GOODRAM             | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 4         | 2.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 3         | 1.81%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.81%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.81%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s                    | 3         | 1.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                       | 3         | 1.81%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 2         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                              | 2         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 2         | 1.2%    |
| Unknown RAM Module 2GB SODIMM 533MT/s                                       | 2         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                               | 2         | 1.2%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.2%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.2%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.2%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.2%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.2%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.2%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                 | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                               | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                               | 1         | 0.6%    |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                                | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DRAM                                          | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                  | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR                                        | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                    | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 1         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                              | 1         | 0.6%    |
| Unknown RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 1024MB SODIMM DDR2 667MT/s | 1         | 0.6%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                          | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 41.73%  |
| DDR4    | 47        | 37.01%  |
| DDR2    | 14        | 11.02%  |
| SDRAM   | 3         | 2.36%   |
| LPDDR4  | 3         | 2.36%   |
| Unknown | 3         | 2.36%   |
| LPDDR5  | 1         | 0.79%   |
| LPDDR3  | 1         | 0.79%   |
| DRAM    | 1         | 0.79%   |
| DDR     | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 96.03%  |
| Row Of Chips | 4         | 3.17%   |
| Chip         | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 35.97%  |
| 8192  | 43        | 30.94%  |
| 2048  | 27        | 19.42%  |
| 16384 | 11        | 7.91%   |
| 1024  | 5         | 3.6%    |
| 32768 | 2         | 1.44%   |
| 512   | 1         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 23.94%  |
| 2667    | 26        | 18.31%  |
| 3200    | 12        | 8.45%   |
| 1334    | 11        | 7.75%   |
| 1333    | 10        | 7.04%   |
| 667     | 10        | 7.04%   |
| 2400    | 8         | 5.63%   |
| 2133    | 8         | 5.63%   |
| 1066    | 3         | 2.11%   |
| Unknown | 3         | 2.11%   |
| 4267    | 2         | 1.41%   |
| 1067    | 2         | 1.41%   |
| 800     | 2         | 1.41%   |
| 533     | 2         | 1.41%   |
| 6400    | 1         | 0.7%    |
| 4199    | 1         | 0.7%    |
| 3266    | 1         | 0.7%    |
| 2933    | 1         | 0.7%    |
| 2048    | 1         | 0.7%    |
| 1867    | 1         | 0.7%    |
| 1639    | 1         | 0.7%    |
| 975     | 1         | 0.7%    |
| 200     | 1         | 0.7%    |

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
| Chicony Electronics                    | 46        | 27.71%  |
| IMC Networks                           | 20        | 12.05%  |
| Realtek Semiconductor                  | 18        | 10.84%  |
| Microdia                               | 12        | 7.23%   |
| Suyin                                  | 9         | 5.42%   |
| Bison Electronics                      | 9         | 5.42%   |
| Quanta                                 | 8         | 4.82%   |
| Sunplus Innovation Technology          | 7         | 4.22%   |
| Lite-On Technology                     | 6         | 3.61%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.61%   |
| Syntek                                 | 5         | 3.01%   |
| Silicon Motion                         | 3         | 1.81%   |
| Luxvisions Innotech Limited            | 3         | 1.81%   |
| Ricoh                                  | 2         | 1.2%    |
| Acer                                   | 2         | 1.2%    |
| Z-Star Microelectronics                | 1         | 0.6%    |
| Samsung Electronics                    | 1         | 0.6%    |
| Primax Electronics                     | 1         | 0.6%    |
| OmniVision Technologies                | 1         | 0.6%    |
| Microsoft                              | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Genesys Logic                          | 1         | 0.6%    |
| DigiTech                               | 1         | 0.6%    |
| Apple                                  | 1         | 0.6%    |
| ALi                                    | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 4.14%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 3.55%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.96%   |
| IMC Networks Integrated Camera                              | 5         | 2.96%   |
| Realtek USB Camera                                          | 4         | 2.37%   |
| Lite-On Integrated Camera                                   | 4         | 2.37%   |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 2.37%   |
| Chicony HD WebCam                                           | 4         | 2.37%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.78%   |
| Sunplus Asus Webcam                                         | 3         | 1.78%   |
| Realtek Integrated Webcam                                   | 3         | 1.78%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.78%   |
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 1.78%   |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 1.78%   |
| Chicony HP HD Camera                                        | 3         | 1.78%   |
| Chicony HD User Facing                                      | 3         | 1.78%   |
| Bison Lenovo EasyCamera                                     | 3         | 1.78%   |
| Suyin HD WebCam                                             | 2         | 1.18%   |
| Realtek HP Webcam                                           | 2         | 1.18%   |
| Quanta HD Webcam                                            | 2         | 1.18%   |
| Microdia Lenovo EasyCamera                                  | 2         | 1.18%   |
| Microdia Integrated Webcam                                  | 2         | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.18%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.18%   |
| Chicony HP Truevision HD camera                             | 2         | 1.18%   |
| Chicony HP HD Webcam                                        | 2         | 1.18%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.18%   |
| Bison Integrated Camera                                     | 2         | 1.18%   |
| Bison BisonCam, NB Pro                                      | 2         | 1.18%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.59%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.59%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.59%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.59%   |
| Syntek Integrated Camera                                    | 1         | 0.59%   |
| Syntek EasyCamera                                           | 1         | 0.59%   |
| Suyin WebCam                                                | 1         | 0.59%   |
| Suyin Acer HD Crystal Eye webcam                            | 1         | 0.59%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.59%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 42.86%  |
| Synaptics                  | 9         | 21.43%  |
| AuthenTec                  | 5         | 11.9%   |
| Upek                       | 3         | 7.14%   |
| STMicroelectronics         | 2         | 4.76%   |
| Shenzhen Goodix Technology | 2         | 4.76%   |
| Elan Microelectronics      | 2         | 4.76%   |
| LighTuning Technology      | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 9.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 7.14%   |
| Validity Sensors VFS491                                                    | 2         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.76%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.76%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.38%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.38%   |
| AuthenTec AES1600                                                          | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 13        | 56.52%  |
| Broadcom    | 6         | 26.09%  |
| Lenovo      | 2         | 8.7%    |
| Upek        | 1         | 4.35%   |
| O2 Micro    | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 13        | 56.52%  |
| Broadcom 58200                                             | 5         | 21.74%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 8.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.35%   |
| Broadcom 5880                                              | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 59.9%   |
| 1     | 59        | 28.5%   |
| 2     | 21        | 10.14%  |
| 3     | 2         | 0.97%   |
| 4     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 42        | 40.38%  |
| Graphics card            | 20        | 19.23%  |
| Chipcard                 | 18        | 17.31%  |
| Net/wireless             | 9         | 8.65%   |
| Multimedia controller    | 5         | 4.81%   |
| Camera                   | 3         | 2.88%   |
| Storage                  | 2         | 1.92%   |
| Communication controller | 2         | 1.92%   |
| Bluetooth                | 2         | 1.92%   |
| Card reader              | 1         | 0.96%   |

