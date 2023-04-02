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

Total: 300

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 22        | 10.09%  |
| ROSA R11           | 14        | 6.42%   |
| Ubuntu 18.04       | 9         | 4.13%   |
| ROSA R9            | 7         | 3.21%   |
| ROSA R10           | 6         | 2.75%   |
| Arch               | 6         | 2.75%   |
| ROSA R8.1          | 5         | 2.29%   |
| ROSA R11.1         | 5         | 2.29%   |
| Debian 11          | 5         | 2.29%   |
| Ubuntu 22.04       | 4         | 1.83%   |
| ROSA R8            | 4         | 1.83%   |
| ROSA 12.3          | 4         | 1.83%   |
| Pop!_OS 22.04      | 4         | 1.83%   |
| Pop!_OS 21.04      | 4         | 1.83%   |
| Pop!_OS 20.10      | 4         | 1.83%   |
| OpenMandriva 4.3   | 4         | 1.83%   |
| Manjaro            | 4         | 1.83%   |
| Linux Mint 21      | 4         | 1.83%   |
| ArcoLinux Rolling  | 4         | 1.83%   |
| Arch Rolling       | 4         | 1.83%   |
| Ubuntu 19.10       | 3         | 1.38%   |
| ROSA 12.1          | 3         | 1.38%   |
| Linux Mint 20.3    | 3         | 1.38%   |
| Linux Mint 19      | 3         | 1.38%   |
| Linux Mint 18.3    | 3         | 1.38%   |
| KDE neon 20.04     | 3         | 1.38%   |
| Xubuntu 20.04      | 2         | 0.92%   |
| Ubuntu 21.10       | 2         | 0.92%   |
| Ubuntu 21.04       | 2         | 0.92%   |
| Ubuntu 20.10       | 2         | 0.92%   |
| ROSA 12.2          | 2         | 0.92%   |
| Pop!_OS 21.10      | 2         | 0.92%   |
| OpenMandriva 4.50  | 2         | 0.92%   |
| OpenMandriva 23.01 | 2         | 0.92%   |
| Linux Mint 20.1    | 2         | 0.92%   |
| Linux Mint 20      | 2         | 0.92%   |
| KDE neon 22.04     | 2         | 0.92%   |
| Fedora 37          | 2         | 0.92%   |
| Fedora 34          | 2         | 0.92%   |
| Debian Testing     | 2         | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 46        | 23.83%  |
| ROSA          | 35        | 18.13%  |
| Linux Mint    | 18        | 9.33%   |
| Pop!_OS       | 13        | 6.74%   |
| Arch          | 10        | 5.18%   |
| OpenMandriva  | 9         | 4.66%   |
| Debian        | 9         | 4.66%   |
| Manjaro       | 8         | 4.15%   |
| Fedora        | 7         | 3.63%   |
| KDE neon      | 5         | 2.59%   |
| ArcoLinux     | 5         | 2.59%   |
| Xubuntu       | 3         | 1.55%   |
| Elementary    | 3         | 1.55%   |
| Ubuntu Unity  | 2         | 1.04%   |
| openSUSE      | 2         | 1.04%   |
| Kali          | 2         | 1.04%   |
| Endless       | 2         | 1.04%   |
| Zorin         | 1         | 0.52%   |
| Void Linux    | 1         | 0.52%   |
| Ubuntu Budgie | 1         | 0.52%   |
| SteamOS       | 1         | 0.52%   |
| Solus         | 1         | 0.52%   |
| Peppermint    | 1         | 0.52%   |
| Parrot        | 1         | 0.52%   |
| NixOS         | 1         | 0.52%   |
| MX            | 1         | 0.52%   |
| Lubuntu       | 1         | 0.52%   |
| Kubuntu       | 1         | 0.52%   |
| GNOME OS      | 1         | 0.52%   |
| Garuda Linux  | 1         | 0.52%   |
| EndeavourOS   | 1         | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.5%    |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.5%    |
| 5.4.0-42-generic                   | 4         | 1.67%   |
| 5.16.7-desktop-1omv4003            | 4         | 1.67%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.67%   |
| 5.8.0-7630-generic                 | 3         | 1.25%   |
| 5.15.0-58-generic                  | 3         | 1.25%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.25%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.25%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.25%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.25%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.25%   |
| 6.1.1-desktop-1omv2290             | 2         | 0.83%   |
| 5.8.0-48-generic                   | 2         | 0.83%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.83%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.83%   |
| 5.4.0-80-generic                   | 2         | 0.83%   |
| 5.4.0-26-generic                   | 2         | 0.83%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.83%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.83%   |
| 5.15.0-67-generic                  | 2         | 0.83%   |
| 5.15.0-56-generic                  | 2         | 0.83%   |
| 5.15.0-46-generic                  | 2         | 0.83%   |
| 5.13.6-arch1-1                     | 2         | 0.83%   |
| 5.13.0-25-generic                  | 2         | 0.83%   |
| 5.11.0-43-generic                  | 2         | 0.83%   |
| 5.10.0-8-amd64                     | 2         | 0.83%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.83%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.83%   |
| 4.18.0-18-generic                  | 2         | 0.83%   |
| 4.15.0-54-generic                  | 2         | 0.83%   |
| 4.10.0-38-generic                  | 2         | 0.83%   |
| 6.1.9-x64v1-xanmod1                | 1         | 0.42%   |
| 6.1.8-200.fc37.x86_64              | 1         | 0.42%   |
| 6.1.7-arch1-1.1                    | 1         | 0.42%   |
| 6.1.12-arch1-1                     | 1         | 0.42%   |
| 6.1.11-76060111-generic            | 1         | 0.42%   |
| 6.0.9_1                            | 1         | 0.42%   |
| 6.0.9-060009-generic               | 1         | 0.42%   |
| 6.0.8-AMD-znver2                   | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 29        | 12.61%  |
| 4.15.0  | 22        | 9.57%   |
| 5.15.0  | 12        | 5.22%   |
| 5.11.0  | 11        | 4.78%   |
| 5.8.0   | 10        | 4.35%   |
| 5.13.0  | 10        | 4.35%   |
| 5.3.0   | 6         | 2.61%   |
| 5.10.0  | 6         | 2.61%   |
| 4.9.20  | 6         | 2.61%   |
| 5.16.7  | 4         | 1.74%   |
| 5.10.74 | 4         | 1.74%   |
| 5.0.0   | 4         | 1.74%   |
| 4.18.0  | 4         | 1.74%   |
| 5.17.1  | 3         | 1.3%    |
| 4.9.60  | 3         | 1.3%    |
| 4.9.41  | 3         | 1.3%    |
| 4.9.155 | 3         | 1.3%    |
| 4.1.34  | 3         | 1.3%    |
| 6.1.1   | 2         | 0.87%   |
| 6.0.9   | 2         | 0.87%   |
| 5.4.83  | 2         | 0.87%   |
| 5.4.72  | 2         | 0.87%   |
| 5.4.32  | 2         | 0.87%   |
| 5.15.79 | 2         | 0.87%   |
| 5.15.75 | 2         | 0.87%   |
| 5.14.0  | 2         | 0.87%   |
| 5.13.6  | 2         | 0.87%   |
| 5.13.12 | 2         | 0.87%   |
| 5.12.14 | 2         | 0.87%   |
| 4.9.9   | 2         | 0.87%   |
| 4.9.124 | 2         | 0.87%   |
| 4.4.0   | 2         | 0.87%   |
| 4.10.0  | 2         | 0.87%   |
| 4.1.38  | 2         | 0.87%   |
| 6.1.9   | 1         | 0.43%   |
| 6.1.8   | 1         | 0.43%   |
| 6.1.7   | 1         | 0.43%   |
| 6.1.12  | 1         | 0.43%   |
| 6.1.11  | 1         | 0.43%   |
| 6.0.8   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 15.38%  |
| 5.15    | 23        | 10.41%  |
| 4.15    | 22        | 9.95%   |
| 4.9     | 16        | 7.24%   |
| 5.13    | 14        | 6.33%   |
| 5.10    | 13        | 5.88%   |
| 5.8     | 12        | 5.43%   |
| 5.11    | 11        | 4.98%   |
| 6.1     | 7         | 3.17%   |
| 5.16    | 7         | 3.17%   |
| 6.0     | 6         | 2.71%   |
| 5.3     | 6         | 2.71%   |
| 5.12    | 6         | 2.71%   |
| 5.19    | 4         | 1.81%   |
| 5.18    | 4         | 1.81%   |
| 5.17    | 4         | 1.81%   |
| 5.14    | 4         | 1.81%   |
| 5.0     | 4         | 1.81%   |
| 4.18    | 4         | 1.81%   |
| 4.1     | 4         | 1.81%   |
| 5.5     | 3         | 1.36%   |
| 5.9     | 2         | 0.9%    |
| 4.4     | 2         | 0.9%    |
| 4.19    | 2         | 0.9%    |
| 4.10    | 2         | 0.9%    |
| 5.7     | 1         | 0.45%   |
| 5.6     | 1         | 0.45%   |
| 5.2     | 1         | 0.45%   |
| 4.20    | 1         | 0.45%   |
| 4.13    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 180       | 95.24%  |
| i686   | 9         | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 73        | 36.14%  |
| KDE5       | 40        | 19.8%   |
| KDE4       | 24        | 11.88%  |
| Unknown    | 18        | 8.91%   |
| XFCE       | 15        | 7.43%   |
| MATE       | 8         | 3.96%   |
| X-Cinnamon | 5         | 2.48%   |
| Budgie     | 4         | 1.98%   |
| Pantheon   | 3         | 1.49%   |
| LXQt       | 3         | 1.49%   |
| KDE        | 3         | 1.49%   |
| Unity      | 2         | 0.99%   |
| Cinnamon   | 2         | 0.99%   |
| sway       | 1         | 0.5%    |
| LXDE       | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 79.08%  |
| Wayland | 29        | 14.8%   |
| Unknown | 9         | 4.59%   |
| Tty     | 3         | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 37.06%  |
| SDDM    | 33        | 16.75%  |
| GDM     | 31        | 15.74%  |
| KDM     | 24        | 12.18%  |
| LightDM | 16        | 8.12%   |
| TDM     | 11        | 5.58%   |
| GDM3    | 6         | 3.05%   |
| SLiM    | 1         | 0.51%   |
| MDM     | 1         | 0.51%   |
| LDM     | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 93        | 47.21%  |
| Unknown     | 43        | 21.83%  |
| lv_LV       | 23        | 11.68%  |
| ru_RU       | 21        | 10.66%  |
| en_GB       | 9         | 4.57%   |
| C           | 3         | 1.52%   |
| ru_RU.UTF_8 | 1         | 0.51%   |
| POSIX       | 1         | 0.51%   |
| fr_FR       | 1         | 0.51%   |
| en_AG       | 1         | 0.51%   |
| de_DE       | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 104       | 54.45%  |
| EFI  | 87        | 45.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 147       | 76.17%  |
| Btrfs   | 17        | 8.81%   |
| Unknown | 16        | 8.29%   |
| Overlay | 12        | 6.22%   |
| Zfs     | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 42.35%  |
| GPT     | 72        | 36.73%  |
| MBR     | 41        | 20.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 88.89%  |
| Yes       | 22        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 74.61%  |
| Yes       | 49        | 25.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 46        | 24.34%  |
| ASUSTek Computer    | 31        | 16.4%   |
| Hewlett-Packard     | 30        | 15.87%  |
| Dell                | 26        | 13.76%  |
| Acer                | 23        | 12.17%  |
| Toshiba             | 6         | 3.17%   |
| MSI                 | 6         | 3.17%   |
| Samsung Electronics | 4         | 2.12%   |
| Fujitsu Siemens     | 3         | 1.59%   |
| HUAWEI              | 2         | 1.06%   |
| Wortmann AG         | 1         | 0.53%   |
| Valve               | 1         | 0.53%   |
| Timi                | 1         | 0.53%   |
| Sony                | 1         | 0.53%   |
| Razer               | 1         | 0.53%   |
| Quanta              | 1         | 0.53%   |
| Packard Bell        | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| eMachines           | 1         | 0.53%   |
| Chuwi               | 1         | 0.53%   |
| Apple               | 1         | 0.53%   |
| Advent              | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.59%   |
| Toshiba Satellite C660                                | 2         | 1.06%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.06%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 1.06%   |
| HP G62                                                | 2         | 1.06%   |
| HP EliteBook 8440p                                    | 2         | 1.06%   |
| HP 250 G6 Notebook PC                                 | 2         | 1.06%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 1.06%   |
| ASUS X553MA                                           | 2         | 1.06%   |
| ASUS X551MA                                           | 2         | 1.06%   |
| Wortmann AG CR700                                     | 1         | 0.53%   |
| Valve Jupiter                                         | 1         | 0.53%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.53%   |
| Toshiba Satellite L750                                | 1         | 0.53%   |
| Toshiba Satellite L350                                | 1         | 0.53%   |
| Toshiba Satellite C50D-B                              | 1         | 0.53%   |
| Timi A35S                                             | 1         | 0.53%   |
| Sony VPCCW2S8E                                        | 1         | 0.53%   |
| Samsung R528/R728                                     | 1         | 0.53%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.53%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.53%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.53%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.53%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.53%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.53%   |
| MSI Modern 14 B4MW                                    | 1         | 0.53%   |
| MSI GV72 7RE                                          | 1         | 0.53%   |
| MSI GT62VR 6RE                                        | 1         | 0.53%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.53%   |
| MSI GF63 Thin 9RCX                                    | 1         | 0.53%   |
| MSI CR500                                             | 1         | 0.53%   |
| Lenovo ZIWB2                                          | 1         | 0.53%   |
| Lenovo Y50-70 20378                                   | 1         | 0.53%   |
| Lenovo V110-15IAP 80TG                                | 1         | 0.53%   |
| Lenovo ThinkPad X260 20F5S5Q200                       | 1         | 0.53%   |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.53%   |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.53%   |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.53%   |
| Lenovo ThinkPad X220 4291Q50                          | 1         | 0.53%   |
| Lenovo ThinkPad X201 Tablet 311396U                   | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 25        | 13.23%  |
| Acer Aspire           | 14        | 7.41%   |
| HP EliteBook          | 11        | 5.82%   |
| Dell Inspiron         | 11        | 5.82%   |
| Lenovo IdeaPad        | 10        | 5.29%   |
| Dell Latitude         | 10        | 5.29%   |
| Toshiba Satellite     | 6         | 3.17%   |
| HP ProBook            | 5         | 2.65%   |
| HP Pavilion           | 5         | 2.65%   |
| ASUS VivoBook         | 4         | 2.12%   |
| Lenovo Legion         | 3         | 1.59%   |
| HP 250                | 3         | 1.59%   |
| HP Laptop             | 2         | 1.06%   |
| HP G62                | 2         | 1.06%   |
| Fujitsu Siemens AMILO | 2         | 1.06%   |
| Dell XPS              | 2         | 1.06%   |
| ASUS ZenBook          | 2         | 1.06%   |
| ASUS X553MA           | 2         | 1.06%   |
| ASUS X551MA           | 2         | 1.06%   |
| ASUS TUF              | 2         | 1.06%   |
| Acer Nitro            | 2         | 1.06%   |
| Acer Extensa          | 2         | 1.06%   |
| Wortmann AG CR700     | 1         | 0.53%   |
| Valve Jupiter         | 1         | 0.53%   |
| Timi A35S             | 1         | 0.53%   |
| Sony VPCCW2S8E        | 1         | 0.53%   |
| Samsung R528          | 1         | 0.53%   |
| Samsung 355V4C        | 1         | 0.53%   |
| Samsung 350V5C        | 1         | 0.53%   |
| Samsung 300V3A        | 1         | 0.53%   |
| Razer Blade           | 1         | 0.53%   |
| Quanta TW8            | 1         | 0.53%   |
| Packard Bell EasyNote | 1         | 0.53%   |
| MSI Modern            | 1         | 0.53%   |
| MSI GV72              | 1         | 0.53%   |
| MSI GT62VR            | 1         | 0.53%   |
| MSI GP75              | 1         | 0.53%   |
| MSI GF63              | 1         | 0.53%   |
| MSI CR500             | 1         | 0.53%   |
| Lenovo ZIWB2          | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 19        | 10.05%  |
| 2013 | 19        | 10.05%  |
| 2014 | 16        | 8.47%   |
| 2020 | 15        | 7.94%   |
| 2011 | 13        | 6.88%   |
| 2010 | 13        | 6.88%   |
| 2018 | 12        | 6.35%   |
| 2015 | 12        | 6.35%   |
| 2008 | 11        | 5.82%   |
| 2017 | 10        | 5.29%   |
| 2012 | 10        | 5.29%   |
| 2016 | 9         | 4.76%   |
| 2009 | 9         | 4.76%   |
| 2021 | 8         | 4.23%   |
| 2007 | 7         | 3.7%    |
| 2022 | 4         | 2.12%   |
| 2006 | 2         | 1.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 189       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 173       | 90.58%  |
| Enabled  | 18        | 9.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 188       | 99.47%  |
| Yes  | 1         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 55        | 28.95%  |
| 4.01-8.0   | 54        | 28.42%  |
| 8.01-16.0  | 27        | 14.21%  |
| 16.01-24.0 | 26        | 13.68%  |
| 32.01-64.0 | 8         | 4.21%   |
| 2.01-3.0   | 8         | 4.21%   |
| 1.01-2.0   | 8         | 4.21%   |
| 24.01-32.0 | 2         | 1.05%   |
| 0.51-1.0   | 2         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 72        | 34.12%  |
| 2.01-3.0   | 53        | 25.12%  |
| 0.51-1.0   | 28        | 13.27%  |
| 4.01-8.0   | 26        | 12.32%  |
| 3.01-4.0   | 21        | 9.95%   |
| 8.01-16.0  | 8         | 3.79%   |
| 16.01-24.0 | 2         | 0.95%   |
| 0.01-0.5   | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 138       | 72.25%  |
| 2      | 46        | 24.08%  |
| 3      | 4         | 2.09%   |
| 0      | 2         | 1.05%   |
| 4      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 57.51%  |
| Yes       | 82        | 42.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 89.53%  |
| No        | 20        | 10.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 98.94%  |
| No        | 2         | 1.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 75%     |
| No        | 48        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 189       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 144       | 70.94%  |
| Liepāja                | 6         | 2.96%   |
| Jelgava                 | 6         | 2.96%   |
| Daugavpils              | 6         | 2.96%   |
| Jūrmala                | 3         | 1.48%   |
| Jaunmarupe              | 3         | 1.48%   |
| Adazi                   | 3         | 1.48%   |
| Valmiera                | 2         | 0.99%   |
| Saulkrasti              | 2         | 0.99%   |
| Rēzekne                | 2         | 0.99%   |
| Malpils                 | 2         | 0.99%   |
| Jēkabpils              | 2         | 0.99%   |
| Cēsis                  | 2         | 0.99%   |
| Zvejniekciems           | 1         | 0.49%   |
| Ventspils               | 1         | 0.49%   |
| Ulbroka                 | 1         | 0.49%   |
| Tukums                  | 1         | 0.49%   |
| Tiraine                 | 1         | 0.49%   |
| Saldus                  | 1         | 0.49%   |
| Pļaviņas              | 1         | 0.49%   |
| Ogre                    | 1         | 0.49%   |
| Lizums                  | 1         | 0.49%   |
| Limbaži                | 1         | 0.49%   |
| Kuldīga                | 1         | 0.49%   |
| Ķekava                 | 1         | 0.49%   |
| Jēkabpils Municipality | 1         | 0.49%   |
| Iecava                  | 1         | 0.49%   |
| Garkalne                | 1         | 0.49%   |
| Garciems                | 1         | 0.49%   |
| Dobele                  | 1         | 0.49%   |
| Bukulti                 | 1         | 0.49%   |
| Aizpute                 | 1         | 0.49%   |
| Aizkraukle              | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 36        | 48     | 15.72%  |
| Seagate                 | 33        | 39     | 14.41%  |
| Kingston                | 25        | 34     | 10.92%  |
| Toshiba                 | 23        | 26     | 10.04%  |
| WDC                     | 22        | 31     | 9.61%   |
| Hitachi                 | 10        | 13     | 4.37%   |
| Unknown                 | 8         | 9      | 3.49%   |
| Micron Technology       | 8         | 8      | 3.49%   |
| HGST                    | 8         | 16     | 3.49%   |
| SK hynix                | 7         | 7      | 3.06%   |
| SanDisk                 | 7         | 15     | 3.06%   |
| A-DATA Technology       | 5         | 6      | 2.18%   |
| Patriot                 | 4         | 10     | 1.75%   |
| KIOXIA                  | 4         | 5      | 1.75%   |
| Crucial                 | 4         | 4      | 1.75%   |
| Intel                   | 3         | 5      | 1.31%   |
| LITEON                  | 2         | 2      | 0.87%   |
| Integral                | 2         | 2      | 0.87%   |
| Verbatim                | 1         | 1      | 0.44%   |
| USB                     | 1         | 1      | 0.44%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.44%   |
| SPCC                    | 1         | 1      | 0.44%   |
| Realtek                 | 1         | 1      | 0.44%   |
| PNY                     | 1         | 1      | 0.44%   |
| Plextor                 | 1         | 1      | 0.44%   |
| Phison                  | 1         | 1      | 0.44%   |
| OCZ                     | 1         | 1      | 0.44%   |
| Netac                   | 1         | 1      | 0.44%   |
| LITEONIT                | 1         | 1      | 0.44%   |
| Lexar                   | 1         | 1      | 0.44%   |
| KingSpec                | 1         | 1      | 0.44%   |
| Kingchuxing             | 1         | 4      | 0.44%   |
| Intenso                 | 1         | 1      | 0.44%   |
| Hrdtac                  | 1         | 4      | 0.44%   |
| Fujitsu                 | 1         | 1      | 0.44%   |
| China                   | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 6         | 2.54%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 2.12%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.69%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 1.69%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.69%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 1.69%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 1.27%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.27%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 1.27%   |
| Hitachi HTS545050B9A300 500GB       | 3         | 1.27%   |
| HGST HTS545050A7E680 500GB          | 3         | 1.27%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.85%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.85%   |
| Toshiba MK8034GSX 80GB              | 2         | 0.85%   |
| Toshiba MK6465GSX 640GB             | 2         | 0.85%   |
| SK hynix HFM512GDJTNG-8310A 512GB   | 2         | 0.85%   |
| SK hynix BC511 NVMe 256GB           | 2         | 0.85%   |
| Seagate ST9160821AS 160GB           | 2         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.85%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 2         | 0.85%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.85%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.85%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.85%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.85%   |
| Samsung MZALQ256HAJD-000L2 256GB    | 2         | 0.85%   |
| Samsung HM321HI 320GB               | 2         | 0.85%   |
| Patriot Burst 240GB SSD             | 2         | 0.85%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 2         | 0.85%   |
| Kingston SV300S37A60G 64GB SSD      | 2         | 0.85%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.85%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 0.85%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.85%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.42%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.42%   |
| WDC WD5000LPVT-75G33T0 500GB        | 1         | 0.42%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.42%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 39     | 35.11%  |
| WDC                 | 19        | 27     | 20.21%  |
| Toshiba             | 18        | 21     | 19.15%  |
| Hitachi             | 10        | 13     | 10.64%  |
| HGST                | 8         | 16     | 8.51%   |
| Samsung Electronics | 4         | 4      | 4.26%   |
| USB                 | 1         | 1      | 1.06%   |
| Fujitsu             | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 22        | 30     | 28.95%  |
| Samsung Electronics | 20        | 27     | 26.32%  |
| A-DATA Technology   | 5         | 6      | 6.58%   |
| Patriot             | 4         | 10     | 5.26%   |
| Crucial             | 4         | 4      | 5.26%   |
| SanDisk             | 3         | 4      | 3.95%   |
| Micron Technology   | 3         | 3      | 3.95%   |
| LITEON              | 2         | 2      | 2.63%   |
| Integral            | 2         | 2      | 2.63%   |
| Verbatim            | 1         | 1      | 1.32%   |
| Toshiba             | 1         | 1      | 1.32%   |
| SPCC                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Plextor             | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Lexar               | 1         | 1      | 1.32%   |
| KingSpec            | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| China               | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 122    | 41.55%  |
| SSD     | 71        | 99     | 32.42%  |
| NVMe    | 49        | 67     | 22.37%  |
| MMC     | 6         | 7      | 2.74%   |
| Unknown | 2         | 9      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 145       | 223    | 70.73%  |
| NVMe | 49        | 66     | 23.9%   |
| MMC  | 6         | 7      | 2.93%   |
| SAS  | 5         | 8      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 159    | 71.07%  |
| 0.51-1.0   | 44        | 60     | 27.67%  |
| 1.01-2.0   | 2         | 2      | 1.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 32.69%  |
| 251-500        | 51        | 24.52%  |
| 501-1000       | 28        | 13.46%  |
| 1-20           | 18        | 8.65%   |
| 1001-2000      | 14        | 6.73%   |
| 51-100         | 14        | 6.73%   |
| 21-50          | 6         | 2.88%   |
| Unknown        | 5         | 2.4%    |
| 2001-3000      | 3         | 1.44%   |
| More than 3000 | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 93        | 44.71%  |
| 21-50     | 30        | 14.42%  |
| 51-100    | 25        | 12.02%  |
| 101-250   | 22        | 10.58%  |
| 251-500   | 16        | 7.69%   |
| 501-1000  | 10        | 4.81%   |
| 1001-2000 | 6         | 2.88%   |
| Unknown   | 5         | 2.4%    |
| 2001-3000 | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 12%     |
| HGST HTS545050A7E680 500GB           | 2         | 2      | 8%      |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 4%      |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 4%      |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4%      |
| Toshiba MK8034GSX 80GB               | 1         | 1      | 4%      |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 4%      |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 4%      |
| Seagate ST9500420AS 500GB            | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB            | 1         | 3      | 4%      |
| Seagate ST9250827AS 250GB            | 1         | 1      | 4%      |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 4%      |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 4%      |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 4%      |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 4%      |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 4%      |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 4%      |
| HGST HTS721010A9E630 1TB             | 1         | 2      | 4%      |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 28%     |
| HGST                | 6         | 8      | 24%     |
| Toshiba             | 4         | 4      | 16%     |
| WDC                 | 3         | 6      | 12%     |
| Kingston            | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |
| Samsung Electronics | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 30.43%  |
| HGST                | 6         | 8      | 26.09%  |
| Toshiba             | 4         | 4      | 17.39%  |
| WDC                 | 3         | 6      | 13.04%  |
| Hitachi             | 2         | 2      | 8.7%    |
| Samsung Electronics | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 30     | 91.67%  |
| SSD  | 2         | 2      | 8.33%   |

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
| Works    | 90        | 142    | 45.23%  |
| Detected | 83        | 128    | 41.71%  |
| Malfunc  | 24        | 32     | 12.06%  |
| Failed   | 2         | 2      | 1.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 148       | 65.78%  |
| AMD                          | 23        | 10.22%  |
| Samsung Electronics          | 16        | 7.11%   |
| SK hynix                     | 7         | 3.11%   |
| SanDisk                      | 7         | 3.11%   |
| Micron Technology            | 5         | 2.22%   |
| KIOXIA                       | 5         | 2.22%   |
| Toshiba America Info Systems | 3         | 1.33%   |
| Kingston Technology Company  | 3         | 1.33%   |
| Union Memory (Shenzhen)      | 2         | 0.89%   |
| Nvidia                       | 2         | 0.89%   |
| Silicon Motion               | 1         | 0.44%   |
| Silicon Image                | 1         | 0.44%   |
| Phison Electronics           | 1         | 0.44%   |
| ADATA Technology             | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 7.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 6.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 4.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 3.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 3.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.46%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 2.05%   |
| Micron NVMe Storage Controller                                                   | 5         | 2.05%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 2.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.05%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.23%   |
| Intel SSD 660P Series                                                            | 3         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.23%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.82%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.82%   |
| SK hynix BC511                                                                   | 2         | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.82%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.82%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 155       | 65.13%  |
| NVMe | 52        | 21.85%  |
| IDE  | 19        | 7.98%   |
| RAID | 12        | 5.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 156       | 82.54%  |
| AMD    | 33        | 17.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 2.12%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.59%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.59%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.59%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.06%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.06%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 1.06%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.06%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.06%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.06%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.06%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 1.06%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1.06%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.06%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.06%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.06%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.53%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.53%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.53%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 25.93%  |
| Intel Core i7           | 29        | 15.34%  |
| Intel Core i3           | 19        | 10.05%  |
| Intel Core 2 Duo        | 16        | 8.47%   |
| Intel Celeron           | 13        | 6.88%   |
| Other                   | 12        | 6.35%   |
| Intel Pentium           | 8         | 4.23%   |
| AMD Ryzen 5             | 7         | 3.7%    |
| AMD Ryzen 7             | 6         | 3.17%   |
| Intel Pentium Dual-Core | 3         | 1.59%   |
| Intel Pentium Dual      | 3         | 1.59%   |
| Intel Genuine           | 3         | 1.59%   |
| AMD A10                 | 3         | 1.59%   |
| Intel Core 2            | 2         | 1.06%   |
| AMD Turion 64 X2 Mobile | 2         | 1.06%   |
| AMD Ryzen 7 PRO         | 2         | 1.06%   |
| AMD Ryzen 3             | 2         | 1.06%   |
| AMD E1                  | 2         | 1.06%   |
| AMD A8                  | 2         | 1.06%   |
| Intel Xeon              | 1         | 0.53%   |
| Intel Atom              | 1         | 0.53%   |
| AMD Ryzen 5 PRO         | 1         | 0.53%   |
| AMD E2                  | 1         | 0.53%   |
| AMD E                   | 1         | 0.53%   |
| AMD C-70                | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 60.53%  |
| 4      | 55        | 28.95%  |
| 8      | 7         | 3.68%   |
| 6      | 7         | 3.68%   |
| 1      | 4         | 2.11%   |
| 14     | 1         | 0.53%   |
| 10     | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 66.32%  |
| 1      | 64        | 33.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 98.94%  |
| 32-bit         | 1         | 0.53%   |
| Unknown        | 1         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 19.69%  |
| 0x306a9    | 12        | 6.22%   |
| 0x406e3    | 11        | 5.7%    |
| 0x206a7    | 10        | 5.18%   |
| 0x6fd      | 9         | 4.66%   |
| 0x30678    | 8         | 4.15%   |
| 0x906ea    | 7         | 3.63%   |
| 0x20655    | 7         | 3.63%   |
| 0x1067a    | 7         | 3.63%   |
| 0x306d4    | 6         | 3.11%   |
| 0x806c1    | 5         | 2.59%   |
| 0x40651    | 5         | 2.59%   |
| 0x806ec    | 4         | 2.07%   |
| 0x306c3    | 4         | 2.07%   |
| 0x08108102 | 4         | 2.07%   |
| 0x06001119 | 4         | 2.07%   |
| 0xa0652    | 3         | 1.55%   |
| 0x906e9    | 3         | 1.55%   |
| 0x806ea    | 3         | 1.55%   |
| 0x806e9    | 3         | 1.55%   |
| 0x10676    | 3         | 1.55%   |
| 0x05000119 | 3         | 1.55%   |
| 0x6fa      | 2         | 1.04%   |
| 0x6f6      | 2         | 1.04%   |
| 0x506e3    | 2         | 1.04%   |
| 0x406c3    | 2         | 1.04%   |
| 0x20652    | 2         | 1.04%   |
| 0x0a50000c | 2         | 1.04%   |
| 0x08600103 | 2         | 1.04%   |
| 0x08108109 | 2         | 1.04%   |
| 0x906ed    | 1         | 0.52%   |
| 0x806eb    | 1         | 0.52%   |
| 0x806d1    | 1         | 0.52%   |
| 0x706a8    | 1         | 0.52%   |
| 0x706a1    | 1         | 0.52%   |
| 0x6fb      | 1         | 0.52%   |
| 0x6ec      | 1         | 0.52%   |
| 0x506c9    | 1         | 0.52%   |
| 0x30673    | 1         | 0.52%   |
| 0x106e5    | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 14.29%  |
| Core          | 17        | 8.99%   |
| Skylake       | 16        | 8.47%   |
| IvyBridge     | 15        | 7.94%   |
| Silvermont    | 12        | 6.35%   |
| SandyBridge   | 12        | 6.35%   |
| Haswell       | 12        | 6.35%   |
| Westmere      | 11        | 5.82%   |
| Penryn        | 10        | 5.29%   |
| Zen+          | 8         | 4.23%   |
| Zen 2         | 7         | 3.7%    |
| TigerLake     | 6         | 3.17%   |
| Broadwell     | 6         | 3.17%   |
| Unknown       | 5         | 2.65%   |
| Piledriver    | 4         | 2.12%   |
| CometLake     | 3         | 1.59%   |
| Bobcat        | 3         | 1.59%   |
| Zen 3         | 2         | 1.06%   |
| Puma          | 2         | 1.06%   |
| K8 Hammer     | 2         | 1.06%   |
| Goldmont plus | 2         | 1.06%   |
| Excavator     | 2         | 1.06%   |
| P6            | 1         | 0.53%   |
| Nehalem       | 1         | 0.53%   |
| Jaguar        | 1         | 0.53%   |
| Icelake       | 1         | 0.53%   |
| Goldmont      | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 57.45%  |
| Nvidia | 57        | 24.26%  |
| AMD    | 43        | 18.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 5.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 5.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 4.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.85%   |
| AMD Renoir                                                                               | 7         | 2.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.03%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.22%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.22%   |
| Intel HD Graphics 620                                                                    | 3         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.81%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.81%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.81%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.81%   |
| Intel HD Graphics 630                                                                    | 2         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.81%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.81%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.81%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 48.15%  |
| Intel + Nvidia | 36        | 19.05%  |
| 1 x AMD        | 28        | 14.81%  |
| 1 x Nvidia     | 18        | 9.52%   |
| Intel + AMD    | 7         | 3.7%    |
| 2 x AMD        | 5         | 2.65%   |
| AMD + Nvidia   | 3         | 1.59%   |
| 2 x Intel      | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 159       | 81.12%  |
| Proprietary | 31        | 15.82%  |
| Unknown     | 6         | 3.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 52.28%  |
| 1.01-2.0   | 38        | 19.29%  |
| 0.01-0.5   | 26        | 13.2%   |
| 0.51-1.0   | 13        | 6.6%    |
| 3.01-4.0   | 12        | 6.09%   |
| 7.01-8.0   | 3         | 1.52%   |
| 5.01-6.0   | 2         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 50        | 24.15%  |
| LG Display              | 33        | 15.94%  |
| Samsung Electronics     | 28        | 13.53%  |
| BOE                     | 24        | 11.59%  |
| Chimei Innolux          | 21        | 10.14%  |
| Dell                    | 12        | 5.8%    |
| Chi Mei Optoelectronics | 7         | 3.38%   |
| Lenovo                  | 5         | 2.42%   |
| Goldstar                | 4         | 1.93%   |
| PANDA                   | 3         | 1.45%   |
| BenQ                    | 3         | 1.45%   |
| Sony                    | 2         | 0.97%   |
| Seiko/Epson             | 2         | 0.97%   |
| InfoVision              | 2         | 0.97%   |
| Hitachi                 | 2         | 0.97%   |
| Tianma XM               | 1         | 0.48%   |
| Sharp                   | 1         | 0.48%   |
| Quanta Display          | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| Panasonic               | 1         | 0.48%   |
| LGD                     | 1         | 0.48%   |
| LG Philips              | 1         | 0.48%   |
| Apple                   | 1         | 0.48%   |
| Acer                    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.88%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch    | 3         | 1.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 1.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.94%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.94%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.94%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.94%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.94%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.94%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.94%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.94%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.47%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.47%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 1         | 0.47%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.47%   |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.47%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch     | 1         | 0.47%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 1         | 0.47%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 69        | 35.94%  |
| 1920x1080 (FHD)    | 68        | 35.42%  |
| 1600x900 (HD+)     | 14        | 7.29%   |
| 1280x800 (WXGA)    | 12        | 6.25%   |
| 3840x2160 (4K)     | 5         | 2.6%    |
| 2560x1440 (QHD)    | 5         | 2.6%    |
| 1440x900 (WXGA+)   | 4         | 2.08%   |
| 3440x1440          | 3         | 1.56%   |
| 1920x1200 (WUXGA)  | 2         | 1.04%   |
| 1280x1024 (SXGA)   | 2         | 1.04%   |
| 7680x2160          | 1         | 0.52%   |
| 3456x2160          | 1         | 0.52%   |
| 3000x2000          | 1         | 0.52%   |
| 2160x1440          | 1         | 0.52%   |
| 1680x1050 (WSXGA+) | 1         | 0.52%   |
| 1360x768           | 1         | 0.52%   |
| 1280x720 (HD)      | 1         | 0.52%   |
| Unknown            | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 103       | 49.52%  |
| 14      | 22        | 10.58%  |
| 13      | 19        | 9.13%   |
| 17      | 18        | 8.65%   |
| 12      | 11        | 5.29%   |
| 24      | 8         | 3.85%   |
| 27      | 4         | 1.92%   |
| Unknown | 4         | 1.92%   |
| 40      | 3         | 1.44%   |
| 11      | 3         | 1.44%   |
| 35      | 2         | 0.96%   |
| 23      | 2         | 0.96%   |
| 21      | 2         | 0.96%   |
| 19      | 2         | 0.96%   |
| 84      | 1         | 0.48%   |
| 43      | 1         | 0.48%   |
| 34      | 1         | 0.48%   |
| 31      | 1         | 0.48%   |
| 18      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 64.25%  |
| 351-400     | 22        | 10.63%  |
| 201-300     | 21        | 10.14%  |
| 501-600     | 14        | 6.76%   |
| 801-900     | 5         | 2.42%   |
| 401-500     | 4         | 1.93%   |
| Unknown     | 4         | 1.93%   |
| 701-800     | 1         | 0.48%   |
| 601-700     | 1         | 0.48%   |
| 1501-2000   | 1         | 0.48%   |
| 901-1000    | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 155       | 82.89%  |
| 16/10   | 20        | 10.7%   |
| Unknown | 4         | 2.14%   |
| 3/2     | 3         | 1.6%    |
| 21/9    | 3         | 1.6%    |
| 5/4     | 2         | 1.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 48.56%  |
| 81-90          | 37        | 17.79%  |
| 121-130        | 15        | 7.21%   |
| 201-250        | 12        | 5.77%   |
| 61-70          | 11        | 5.29%   |
| 71-80          | 4         | 1.92%   |
| 351-500        | 4         | 1.92%   |
| 301-350        | 4         | 1.92%   |
| 501-1000       | 4         | 1.92%   |
| Unknown        | 4         | 1.92%   |
| 51-60          | 3         | 1.44%   |
| 151-200        | 3         | 1.44%   |
| 131-140        | 2         | 0.96%   |
| 91-100         | 2         | 0.96%   |
| More than 1000 | 1         | 0.48%   |
| 141-150        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 80        | 38.65%  |
| 101-120       | 74        | 35.75%  |
| 51-100        | 35        | 16.91%  |
| 161-240       | 9         | 4.35%   |
| Unknown       | 4         | 1.93%   |
| More than 240 | 3         | 1.45%   |
| 1-50          | 2         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 158       | 82.29%  |
| 2     | 27        | 14.06%  |
| 0     | 4         | 2.08%   |
| 3     | 3         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 34.31%  |
| Intel                    | 99        | 32.35%  |
| Qualcomm Atheros         | 48        | 15.69%  |
| Broadcom                 | 19        | 6.21%   |
| Broadcom Limited         | 8         | 2.61%   |
| Marvell Technology Group | 6         | 1.96%   |
| Ralink                   | 4         | 1.31%   |
| TP-Link                  | 2         | 0.65%   |
| Ralink Technology        | 2         | 0.65%   |
| Nvidia                   | 2         | 0.65%   |
| MediaTek                 | 2         | 0.65%   |
| Hewlett-Packard          | 2         | 0.65%   |
| Xiaomi                   | 1         | 0.33%   |
| vivo                     | 1         | 0.33%   |
| U-Blox                   | 1         | 0.33%   |
| Samsung Electronics      | 1         | 0.33%   |
| Qualcomm                 | 1         | 0.33%   |
| Lenovo                   | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 17.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 7.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.88%   |
| Intel Wireless 8260                                               | 7         | 1.88%   |
| Intel Wireless 3160                                               | 7         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.08%   |
| Intel Wireless 7260                                               | 4         | 1.08%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 0.81%   |
| Intel Wireless 7265                                               | 3         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 98        | 50.78%  |
| Qualcomm Atheros      | 42        | 21.76%  |
| Realtek Semiconductor | 25        | 12.95%  |
| Broadcom              | 14        | 7.25%   |
| Ralink                | 4         | 2.07%   |
| Broadcom Limited      | 4         | 2.07%   |
| TP-Link               | 2         | 1.04%   |
| Ralink Technology     | 2         | 1.04%   |
| Qualcomm              | 1         | 0.52%   |
| MediaTek              | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 4.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.63%   |
| Intel Wireless 8260                                                     | 7         | 3.63%   |
| Intel Wireless 3160                                                     | 7         | 3.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.63%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 3.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 3.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 3.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.59%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.59%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.07%   |
| Intel Wireless 7260                                                     | 4         | 2.07%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 2.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.55%   |
| Intel Wireless 7265                                                     | 3         | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.04%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.04%   |
| Intel WiFi Link 5100                                                    | 2         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.04%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 100       | 56.5%   |
| Intel                    | 36        | 20.34%  |
| Qualcomm Atheros         | 13        | 7.34%   |
| Broadcom                 | 9         | 5.08%   |
| Marvell Technology Group | 6         | 3.39%   |
| Broadcom Limited         | 4         | 2.26%   |
| Nvidia                   | 2         | 1.13%   |
| Xiaomi                   | 1         | 0.56%   |
| vivo                     | 1         | 0.56%   |
| Samsung Electronics      | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Lenovo                   | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Hewlett-Packard          | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 37.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 16.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.26%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.26%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.13%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.13%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.13%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.13%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.13%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| vivo 1806                                                         | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.56%   |
| MediaTek KINGKONG_MINI                                            | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.56%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 187       | 51.94%  |
| Ethernet | 171       | 47.5%   |
| Modem    | 2         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 81.12%  |
| Ethernet | 37        | 18.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 161       | 85.19%  |
| 1     | 25        | 13.23%  |
| 3     | 2         | 1.06%   |
| 0     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 180       | 95.24%  |
| Yes  | 9         | 4.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 40.28%  |
| Realtek Semiconductor           | 16        | 11.11%  |
| Qualcomm Atheros Communications | 12        | 8.33%   |
| Lite-On Technology              | 12        | 8.33%   |
| IMC Networks                    | 12        | 8.33%   |
| Broadcom                        | 11        | 7.64%   |
| Dell                            | 5         | 3.47%   |
| Hewlett-Packard                 | 4         | 2.78%   |
| Toshiba                         | 3         | 2.08%   |
| Ralink                          | 2         | 1.39%   |
| Cambridge Silicon Radio         | 2         | 1.39%   |
| USI                             | 1         | 0.69%   |
| Taiyo Yuden                     | 1         | 0.69%   |
| Ralink Technology               | 1         | 0.69%   |
| Qcom                            | 1         | 0.69%   |
| Foxconn / Hon Hai               | 1         | 0.69%   |
| ASUSTek Computer                | 1         | 0.69%   |
| Apple                           | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.64%   |
| Realtek Bluetooth Radio                             | 8         | 5.56%   |
| Intel AX201 Bluetooth                               | 7         | 4.86%   |
| Intel AX200 Bluetooth                               | 6         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.47%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.08%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 2.08%   |
| Lite-On Bluetooth Device                            | 3         | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.08%   |
| IMC Networks Bluetooth Device                       | 3         | 2.08%   |
| Realtek RTL8821A Bluetooth                          | 2         | 1.39%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.39%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.39%   |
| Intel Bluetooth Device                              | 2         | 1.39%   |
| Intel AX210 Bluetooth                               | 2         | 1.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.39%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.39%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.39%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.39%   |
| USI Bluetooth Device                                | 1         | 0.69%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.69%   |
| Toshiba Bluetooth Device                            | 1         | 0.69%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.69%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.69%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.69%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.69%   |
| Lite-On BCM43142A0                                  | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 154       | 66.96%  |
| AMD                   | 36        | 15.65%  |
| Nvidia                | 28        | 12.17%  |
| C-Media Electronics   | 3         | 1.3%    |
| Logitech              | 2         | 0.87%   |
| Realtek Semiconductor | 1         | 0.43%   |
| Microsoft             | 1         | 0.43%   |
| Lenovo                | 1         | 0.43%   |
| GYROCOM C&C           | 1         | 0.43%   |
| GN Netcom             | 1         | 0.43%   |
| Creative Technology   | 1         | 0.43%   |
| Apple                 | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 5.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 3.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 9         | 3.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.1%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.1%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 25.85%  |
| SK hynix            | 35        | 23.81%  |
| Unknown             | 21        | 14.29%  |
| Kingston            | 21        | 14.29%  |
| Micron Technology   | 13        | 8.84%   |
| G.Skill             | 3         | 2.04%   |
| Elpida              | 3         | 2.04%   |
| Ramaxel Technology  | 2         | 1.36%   |
| Crucial             | 2         | 1.36%   |
| Corsair             | 2         | 1.36%   |
| A-DATA Technology   | 2         | 1.36%   |
| Toshiba             | 1         | 0.68%   |
| PNY                 | 1         | 0.68%   |
| Patriot             | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| GOODRAM             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 4         | 2.6%    |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                   | 4         | 2.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 3         | 1.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                       | 3         | 1.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                       | 3         | 1.95%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                              | 2         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 2         | 1.3%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                               | 2         | 1.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.3%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                       | 2         | 1.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.3%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                       | 2         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.3%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.3%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.3%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.3%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                 | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                 | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                  | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                               | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                               | 1         | 0.65%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                                | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                               | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DRAM                                          | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3                                          | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                  | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR                                        | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                    | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                              | 1         | 0.65%   |
| Unknown RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 1024MB SODIMM DDR2 667MT/s | 1         | 0.65%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                          | 1         | 0.65%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 51        | 42.86%  |
| DDR4    | 44        | 36.97%  |
| DDR2    | 14        | 11.76%  |
| SDRAM   | 3         | 2.52%   |
| LPDDR4  | 3         | 2.52%   |
| LPDDR5  | 1         | 0.84%   |
| DRAM    | 1         | 0.84%   |
| DDR     | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 96.61%  |
| Row Of Chips | 3         | 2.54%   |
| Chip         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 48        | 37.21%  |
| 8192  | 41        | 31.78%  |
| 2048  | 25        | 19.38%  |
| 16384 | 8         | 6.2%    |
| 1024  | 5         | 3.88%   |
| 32768 | 1         | 0.78%   |
| 512   | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 33        | 25.38%  |
| 2667    | 24        | 18.46%  |
| 1334    | 11        | 8.46%   |
| 3200    | 10        | 7.69%   |
| 667     | 10        | 7.69%   |
| 1333    | 9         | 6.92%   |
| 2133    | 7         | 5.38%   |
| 2400    | 6         | 4.62%   |
| 1066    | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |
| 4267    | 2         | 1.54%   |
| 1067    | 2         | 1.54%   |
| 800     | 2         | 1.54%   |
| 6400    | 1         | 0.77%   |
| 4199    | 1         | 0.77%   |
| 3266    | 1         | 0.77%   |
| 2048    | 1         | 0.77%   |
| 1867    | 1         | 0.77%   |
| 1639    | 1         | 0.77%   |
| 975     | 1         | 0.77%   |
| 200     | 1         | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung SCX-4100 Scanner | 1         | 25%     |
| Samsung SCX-3200 Series  | 1         | 25%     |
| HP LaserJet P1102        | 1         | 25%     |
| HP LaserJet 1018         | 1         | 25%     |

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
| Chicony Electronics                    | 43        | 27.39%  |
| IMC Networks                           | 19        | 12.1%   |
| Realtek Semiconductor                  | 18        | 11.46%  |
| Microdia                               | 11        | 7.01%   |
| Suyin                                  | 9         | 5.73%   |
| Sunplus Innovation Technology          | 7         | 4.46%   |
| Quanta                                 | 7         | 4.46%   |
| Lite-On Technology                     | 6         | 3.82%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.82%   |
| Bison Electronics                      | 6         | 3.82%   |
| Syntek                                 | 5         | 3.18%   |
| Acer                                   | 5         | 3.18%   |
| Silicon Motion                         | 3         | 1.91%   |
| Luxvisions Innotech Limited            | 3         | 1.91%   |
| Ricoh                                  | 2         | 1.27%   |
| Samsung Electronics                    | 1         | 0.64%   |
| Primax Electronics                     | 1         | 0.64%   |
| OmniVision Technologies                | 1         | 0.64%   |
| Microsoft                              | 1         | 0.64%   |
| Lenovo                                 | 1         | 0.64%   |
| Genesys Logic                          | 1         | 0.64%   |
| DigiTech                               | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 3.75%   |
| Realtek Integrated_Webcam_HD                                | 5         | 3.13%   |
| Realtek USB Camera                                          | 4         | 2.5%    |
| Lite-On Integrated Camera                                   | 4         | 2.5%    |
| IMC Networks Integrated Camera                              | 4         | 2.5%    |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 2.5%    |
| Chicony HD WebCam                                           | 4         | 2.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.88%   |
| Sunplus Asus Webcam                                         | 3         | 1.88%   |
| Realtek Integrated Webcam                                   | 3         | 1.88%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.88%   |
| Chicony HP HD Camera                                        | 3         | 1.88%   |
| Chicony HD User Facing                                      | 3         | 1.88%   |
| Bison Integrated Camera                                     | 3         | 1.88%   |
| Acer Lenovo EasyCamera                                      | 3         | 1.88%   |
| Suyin HD WebCam                                             | 2         | 1.25%   |
| Realtek HP Webcam                                           | 2         | 1.25%   |
| Quanta HD Webcam                                            | 2         | 1.25%   |
| Microdia Lenovo EasyCamera                                  | 2         | 1.25%   |
| Microdia Integrated Webcam                                  | 2         | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.25%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.25%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.25%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.25%   |
| Chicony HP Truevision HD camera                             | 2         | 1.25%   |
| Chicony HP HD Webcam                                        | 2         | 1.25%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.25%   |
| Bison BisonCam, NB Pro                                      | 2         | 1.25%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.63%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.63%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.63%   |
| Syntek Integrated Camera                                    | 1         | 0.63%   |
| Syntek EasyCamera                                           | 1         | 0.63%   |
| Suyin WebCam                                                | 1         | 0.63%   |
| Suyin Acer HD Crystal Eye webcam                            | 1         | 0.63%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 47.22%  |
| Synaptics                  | 7         | 19.44%  |
| Upek                       | 3         | 8.33%   |
| AuthenTec                  | 3         | 8.33%   |
| STMicroelectronics         | 2         | 5.56%   |
| Elan Microelectronics      | 2         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 2.78%   |
| LighTuning Technology      | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 8.33%   |
| Validity Sensors VFS491                                                    | 2         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.56%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.78%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.78%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.78%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.78%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.78%   |
| AuthenTec AES1600                                                          | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 11        | 52.38%  |
| Broadcom    | 6         | 28.57%  |
| Lenovo      | 2         | 9.52%   |
| Upek        | 1         | 4.76%   |
| O2 Micro    | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 11        | 52.38%  |
| Broadcom 58200                                             | 5         | 23.81%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.76%   |
| Broadcom 5880                                              | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 60%     |
| 1     | 59        | 30.26%  |
| 2     | 15        | 7.69%   |
| 3     | 3         | 1.54%   |
| 4     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 37.11%  |
| Graphics card            | 23        | 23.71%  |
| Chipcard                 | 17        | 17.53%  |
| Net/wireless             | 7         | 7.22%   |
| Multimedia controller    | 5         | 5.15%   |
| Storage                  | 2         | 2.06%   |
| Communication controller | 2         | 2.06%   |
| Camera                   | 2         | 2.06%   |
| Bluetooth                | 2         | 2.06%   |
| Card reader              | 1         | 1.03%   |

