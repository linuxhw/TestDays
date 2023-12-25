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

Total: 352

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 250 G6 Notebook PC          | [552bc11608](https://linux-hardware.org/?probe=552bc11608) | Dec 19, 2023 |
| MSI           | Katana GF76 12UC            | [6667f9e88d](https://linux-hardware.org/?probe=6667f9e88d) | Dec 08, 2023 |
| HP            | ProBook 450 G0              | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| TUXEDO        | Gemini Gen2                 | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| Wortmann      | CR700                       | [0c5f9ff4c6](https://linux-hardware.org/?probe=0c5f9ff4c6) | Nov 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [dc40a2bbb1](https://linux-hardware.org/?probe=dc40a2bbb1) | Nov 10, 2023 |
| Wortmann      | CR700                       | [45ed4d1320](https://linux-hardware.org/?probe=45ed4d1320) | Nov 07, 2023 |
| TUXEDO        | Unknown                     | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Wortmann      | CR700                       | [916c9bceda](https://linux-hardware.org/?probe=916c9bceda) | Oct 15, 2023 |
| Packard Be... | EasyNote TE11HC             | [75cbcab213](https://linux-hardware.org/?probe=75cbcab213) | Oct 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| MSI           | Katana GF76 11UE            | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| Packard Be... | EasyNote TE11HC             | [0d897e53cf](https://linux-hardware.org/?probe=0d897e53cf) | Sep 21, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [432c1d0b94](https://linux-hardware.org/?probe=432c1d0b94) | Sep 18, 2023 |
| Packard Be... | EasyNote TE11HC             | [7f55f1b615](https://linux-hardware.org/?probe=7f55f1b615) | Sep 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| Acer          | Aspire A515-56              | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| Acer          | Aspire A515-56              | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
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
| Ubuntu 20.04       | 23        | 9.24%   |
| ROSA R11           | 14        | 5.62%   |
| Ubuntu 18.04       | 9         | 3.61%   |
| ROSA R9            | 7         | 2.81%   |
| Ubuntu 22.04       | 6         | 2.41%   |
| ROSA R10           | 6         | 2.41%   |
| Pop!_OS 22.04      | 6         | 2.41%   |
| OpenMandriva 4.3   | 6         | 2.41%   |
| Debian 11          | 6         | 2.41%   |
| Arch Rolling       | 6         | 2.41%   |
| Arch               | 6         | 2.41%   |
| ROSA R8.1          | 5         | 2.01%   |
| ROSA R11.1         | 5         | 2.01%   |
| ROSA R8            | 4         | 1.61%   |
| ROSA 12.3          | 4         | 1.61%   |
| Pop!_OS 21.04      | 4         | 1.61%   |
| Pop!_OS 20.10      | 4         | 1.61%   |
| Manjaro            | 4         | 1.61%   |
| Linux Mint 21      | 4         | 1.61%   |
| Linux Mint 20.3    | 4         | 1.61%   |
| KDE neon 20.04     | 4         | 1.61%   |
| ArcoLinux Rolling  | 4         | 1.61%   |
| Ubuntu 19.10       | 3         | 1.2%    |
| ROSA 12.1          | 3         | 1.2%    |
| Linux Mint 19      | 3         | 1.2%    |
| Linux Mint 18.3    | 3         | 1.2%    |
| KDE neon 22.04     | 3         | 1.2%    |
| Fedora 37          | 3         | 1.2%    |
| Xubuntu 20.04      | 2         | 0.8%    |
| Ubuntu 23.04       | 2         | 0.8%    |
| Ubuntu 21.10       | 2         | 0.8%    |
| Ubuntu 21.04       | 2         | 0.8%    |
| Ubuntu 20.10       | 2         | 0.8%    |
| ROSA 12.2          | 2         | 0.8%    |
| Pop!_OS 21.10      | 2         | 0.8%    |
| OpenMandriva 4.50  | 2         | 0.8%    |
| OpenMandriva 23.08 | 2         | 0.8%    |
| OpenMandriva 23.01 | 2         | 0.8%    |
| Linux Mint 21.2    | 2         | 0.8%    |
| Linux Mint 21.1    | 2         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51        | 23.08%  |
| ROSA          | 36        | 16.29%  |
| Linux Mint    | 20        | 9.05%   |
| Pop!_OS       | 15        | 6.79%   |
| OpenMandriva  | 13        | 5.88%   |
| Debian        | 12        | 5.43%   |
| Arch          | 12        | 5.43%   |
| Manjaro       | 9         | 4.07%   |
| Fedora        | 9         | 4.07%   |
| KDE neon      | 7         | 3.17%   |
| ArcoLinux     | 5         | 2.26%   |
| Xubuntu       | 4         | 1.81%   |
| Kubuntu       | 3         | 1.36%   |
| Elementary    | 3         | 1.36%   |
| Ubuntu Unity  | 2         | 0.9%    |
| openSUSE      | 2         | 0.9%    |
| Kali          | 2         | 0.9%    |
| Endless       | 2         | 0.9%    |
| EndeavourOS   | 2         | 0.9%    |
| Zorin         | 1         | 0.45%   |
| Void Linux    | 1         | 0.45%   |
| Ubuntu Budgie | 1         | 0.45%   |
| SteamOS       | 1         | 0.45%   |
| Solus         | 1         | 0.45%   |
| Peppermint    | 1         | 0.45%   |
| Parrot        | 1         | 0.45%   |
| NixOS         | 1         | 0.45%   |
| MX            | 1         | 0.45%   |
| Lubuntu       | 1         | 0.45%   |
| GNOME OS      | 1         | 0.45%   |
| Garuda Linux  | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 6         | 2.12%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.12%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.12%   |
| 5.4.0-42-generic                   | 4         | 1.41%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.41%   |
| 5.8.0-7630-generic                 | 3         | 1.06%   |
| 5.15.0-58-generic                  | 3         | 1.06%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 1.06%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.06%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.06%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.06%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.06%   |
| 6.2.6-76060206-generic             | 2         | 0.71%   |
| 6.2.0-20-generic                   | 2         | 0.71%   |
| 6.1.1-desktop-1omv2290             | 2         | 0.71%   |
| 5.8.0-48-generic                   | 2         | 0.71%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.71%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.71%   |
| 5.4.0-80-generic                   | 2         | 0.71%   |
| 5.4.0-47-generic                   | 2         | 0.71%   |
| 5.4.0-26-generic                   | 2         | 0.71%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.71%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.71%   |
| 5.15.0-86-generic                  | 2         | 0.71%   |
| 5.15.0-67-generic                  | 2         | 0.71%   |
| 5.15.0-56-generic                  | 2         | 0.71%   |
| 5.15.0-52-generic                  | 2         | 0.71%   |
| 5.15.0-46-generic                  | 2         | 0.71%   |
| 5.13.6-arch1-1                     | 2         | 0.71%   |
| 5.13.0-25-generic                  | 2         | 0.71%   |
| 5.11.0-43-generic                  | 2         | 0.71%   |
| 5.10.0-8-amd64                     | 2         | 0.71%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.71%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.71%   |
| 4.18.0-18-generic                  | 2         | 0.71%   |
| 4.15.0-54-generic                  | 2         | 0.71%   |
| 4.10.0-38-generic                  | 2         | 0.71%   |
| 6.6.4-arch1-1                      | 1         | 0.35%   |
| 6.6.1-zen1-1-zen                   | 1         | 0.35%   |
| 6.6.1-arch1-1                      | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 11.7%   |
| 4.15.0  | 22        | 8.3%    |
| 5.15.0  | 14        | 5.28%   |
| 5.11.0  | 11        | 4.15%   |
| 5.8.0   | 10        | 3.77%   |
| 5.13.0  | 10        | 3.77%   |
| 6.2.0   | 7         | 2.64%   |
| 5.10.0  | 7         | 2.64%   |
| 5.3.0   | 6         | 2.26%   |
| 5.16.7  | 6         | 2.26%   |
| 4.9.20  | 6         | 2.26%   |
| 5.10.74 | 4         | 1.51%   |
| 5.0.0   | 4         | 1.51%   |
| 4.18.0  | 4         | 1.51%   |
| 6.2.6   | 3         | 1.13%   |
| 5.19.0  | 3         | 1.13%   |
| 5.17.1  | 3         | 1.13%   |
| 4.9.60  | 3         | 1.13%   |
| 4.9.41  | 3         | 1.13%   |
| 4.9.155 | 3         | 1.13%   |
| 4.1.34  | 3         | 1.13%   |
| 6.6.1   | 2         | 0.75%   |
| 6.1.1   | 2         | 0.75%   |
| 6.1.0   | 2         | 0.75%   |
| 6.0.9   | 2         | 0.75%   |
| 5.4.83  | 2         | 0.75%   |
| 5.4.72  | 2         | 0.75%   |
| 5.4.32  | 2         | 0.75%   |
| 5.15.79 | 2         | 0.75%   |
| 5.15.75 | 2         | 0.75%   |
| 5.14.0  | 2         | 0.75%   |
| 5.13.6  | 2         | 0.75%   |
| 5.13.12 | 2         | 0.75%   |
| 5.12.14 | 2         | 0.75%   |
| 4.9.9   | 2         | 0.75%   |
| 4.9.124 | 2         | 0.75%   |
| 4.4.0   | 2         | 0.75%   |
| 4.10.0  | 2         | 0.75%   |
| 4.1.38  | 2         | 0.75%   |
| 6.6.4   | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 14.06%  |
| 5.15    | 25        | 9.77%   |
| 4.15    | 22        | 8.59%   |
| 4.9     | 16        | 6.25%   |
| 5.13    | 14        | 5.47%   |
| 5.10    | 14        | 5.47%   |
| 5.8     | 12        | 4.69%   |
| 5.11    | 12        | 4.69%   |
| 6.1     | 11        | 4.3%    |
| 6.2     | 10        | 3.91%   |
| 5.16    | 9         | 3.52%   |
| 6.0     | 7         | 2.73%   |
| 5.3     | 6         | 2.34%   |
| 5.19    | 6         | 2.34%   |
| 5.12    | 6         | 2.34%   |
| 5.18    | 4         | 1.56%   |
| 5.17    | 4         | 1.56%   |
| 5.14    | 4         | 1.56%   |
| 5.0     | 4         | 1.56%   |
| 4.18    | 4         | 1.56%   |
| 4.1     | 4         | 1.56%   |
| 6.6     | 3         | 1.17%   |
| 6.5     | 3         | 1.17%   |
| 5.5     | 3         | 1.17%   |
| 6.4     | 2         | 0.78%   |
| 6.3     | 2         | 0.78%   |
| 5.9     | 2         | 0.78%   |
| 4.4     | 2         | 0.78%   |
| 4.19    | 2         | 0.78%   |
| 4.10    | 2         | 0.78%   |
| 5.7     | 1         | 0.39%   |
| 5.6     | 1         | 0.39%   |
| 5.2     | 1         | 0.39%   |
| 4.20    | 1         | 0.39%   |
| 4.13    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 206       | 95.81%  |
| i686   | 9         | 4.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 83        | 35.78%  |
| KDE5       | 53        | 22.84%  |
| KDE4       | 24        | 10.34%  |
| Unknown    | 20        | 8.62%   |
| XFCE       | 17        | 7.33%   |
| MATE       | 9         | 3.88%   |
| X-Cinnamon | 6         | 2.59%   |
| Budgie     | 4         | 1.72%   |
| Pantheon   | 3         | 1.29%   |
| LXQt       | 3         | 1.29%   |
| KDE        | 3         | 1.29%   |
| Unity      | 2         | 0.86%   |
| Cinnamon   | 2         | 0.86%   |
| sway       | 1         | 0.43%   |
| LXDE       | 1         | 0.43%   |
| i3         | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 173       | 77.23%  |
| Wayland | 37        | 16.52%  |
| Unknown | 10        | 4.46%   |
| Tty     | 4         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 35.68%  |
| SDDM    | 42        | 18.5%   |
| GDM     | 33        | 14.54%  |
| KDM     | 24        | 10.57%  |
| LightDM | 20        | 8.81%   |
| GDM3    | 13        | 5.73%   |
| TDM     | 11        | 4.85%   |
| SLiM    | 1         | 0.44%   |
| MDM     | 1         | 0.44%   |
| LDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 114       | 50.89%  |
| Unknown     | 43        | 19.2%   |
| lv_LV       | 25        | 11.16%  |
| ru_RU       | 24        | 10.71%  |
| en_GB       | 9         | 4.02%   |
| C           | 4         | 1.79%   |
| ru_RU.UTF_8 | 1         | 0.45%   |
| POSIX       | 1         | 0.45%   |
| fr_FR       | 1         | 0.45%   |
| en_AG       | 1         | 0.45%   |
| de_DE       | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 112       | 51.14%  |
| EFI  | 107       | 48.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 166       | 74.77%  |
| Btrfs   | 21        | 9.46%   |
| Unknown | 16        | 7.21%   |
| Overlay | 12        | 5.41%   |
| Tmpfs   | 5         | 2.25%   |
| Zfs     | 2         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 94        | 41.59%  |
| Unknown | 89        | 39.38%  |
| MBR     | 43        | 19.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 88.84%  |
| Yes       | 25        | 11.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 73.97%  |
| Yes       | 57        | 26.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 52        | 24.19%  |
| ASUSTek Computer    | 36        | 16.74%  |
| Hewlett-Packard     | 31        | 14.42%  |
| Dell                | 26        | 12.09%  |
| Acer                | 24        | 11.16%  |
| MSI                 | 8         | 3.72%   |
| Toshiba             | 6         | 2.79%   |
| Fujitsu Siemens     | 5         | 2.33%   |
| Samsung Electronics | 4         | 1.86%   |
| Packard Bell        | 3         | 1.4%    |
| HUAWEI              | 3         | 1.4%    |
| Apple               | 3         | 1.4%    |
| TUXEDO              | 2         | 0.93%   |
| Wortmann AG         | 1         | 0.47%   |
| Valve               | 1         | 0.47%   |
| Timi                | 1         | 0.47%   |
| Sony                | 1         | 0.47%   |
| Razer               | 1         | 0.47%   |
| Quanta              | 1         | 0.47%   |
| Gigabyte Technology | 1         | 0.47%   |
| Fujitsu             | 1         | 0.47%   |
| eMachines           | 1         | 0.47%   |
| Chuwi               | 1         | 0.47%   |
| Advent              | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 1.4%    |
| ASUS X553MA                                           | 3         | 1.4%    |
| Unknown                                               | 3         | 1.4%    |
| Toshiba Satellite C660                                | 2         | 0.93%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.93%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.93%   |
| HP G62                                                | 2         | 0.93%   |
| HP EliteBook 8440p                                    | 2         | 0.93%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.93%   |
| Fujitsu Siemens LIFEBOOK S6420                        | 2         | 0.93%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.93%   |
| ASUS X551MA                                           | 2         | 0.93%   |
| Apple MacBookPro8,1                                   | 2         | 0.93%   |
| Wortmann AG CR700                                     | 1         | 0.47%   |
| Valve Jupiter                                         | 1         | 0.47%   |
| TUXEDO Gemini Gen2                                    | 1         | 0.47%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.47%   |
| Toshiba Satellite L750                                | 1         | 0.47%   |
| Toshiba Satellite L350                                | 1         | 0.47%   |
| Toshiba Satellite C50D-B                              | 1         | 0.47%   |
| Timi A35S                                             | 1         | 0.47%   |
| Sony VPCCW2S8E                                        | 1         | 0.47%   |
| Samsung R528/R728                                     | 1         | 0.47%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.47%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.47%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.47%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.47%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.47%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.47%   |
| Packard Bell EasyNote LM85                            | 1         | 0.47%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.47%   |
| MSI Modern 14 B4MW                                    | 1         | 0.47%   |
| MSI Katana GF76 12UC                                  | 1         | 0.47%   |
| MSI Katana GF76 11UE                                  | 1         | 0.47%   |
| MSI GV72 7RE                                          | 1         | 0.47%   |
| MSI GT62VR 6RE                                        | 1         | 0.47%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.47%   |
| MSI GF63 Thin 9RCX                                    | 1         | 0.47%   |
| MSI CR500                                             | 1         | 0.47%   |
| Lenovo ZIWB2                                          | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 30        | 13.95%  |
| Acer Aspire              | 15        | 6.98%   |
| HP EliteBook             | 12        | 5.58%   |
| Dell Inspiron            | 11        | 5.12%   |
| Lenovo IdeaPad           | 10        | 4.65%   |
| Dell Latitude            | 10        | 4.65%   |
| Toshiba Satellite        | 6         | 2.79%   |
| HP ProBook               | 5         | 2.33%   |
| HP Pavilion              | 5         | 2.33%   |
| ASUS VivoBook            | 5         | 2.33%   |
| Packard Bell EasyNote    | 3         | 1.4%    |
| Lenovo Legion            | 3         | 1.4%    |
| HP 250                   | 3         | 1.4%    |
| Fujitsu Siemens LIFEBOOK | 3         | 1.4%    |
| ASUS Zenbook             | 3         | 1.4%    |
| ASUS X553MA              | 3         | 1.4%    |
| Unknown                  | 3         | 1.4%    |
| MSI Katana               | 2         | 0.93%   |
| Lenovo ThinkBook         | 2         | 0.93%   |
| HP Laptop                | 2         | 0.93%   |
| HP G62                   | 2         | 0.93%   |
| Fujitsu Siemens AMILO    | 2         | 0.93%   |
| Dell XPS                 | 2         | 0.93%   |
| ASUS X551MA              | 2         | 0.93%   |
| ASUS TUF                 | 2         | 0.93%   |
| ASUS ASUS                | 2         | 0.93%   |
| Apple MacBookPro8        | 2         | 0.93%   |
| Acer Nitro               | 2         | 0.93%   |
| Acer Extensa             | 2         | 0.93%   |
| Wortmann AG CR700        | 1         | 0.47%   |
| Valve Jupiter            | 1         | 0.47%   |
| TUXEDO Gemini            | 1         | 0.47%   |
| Timi A35S                | 1         | 0.47%   |
| Sony VPCCW2S8E           | 1         | 0.47%   |
| Samsung R528             | 1         | 0.47%   |
| Samsung 355V4C           | 1         | 0.47%   |
| Samsung 350V5C           | 1         | 0.47%   |
| Samsung 300V3A           | 1         | 0.47%   |
| Razer Blade              | 1         | 0.47%   |
| Quanta TW8               | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 21        | 9.77%   |
| 2013 | 18        | 8.37%   |
| 2020 | 17        | 7.91%   |
| 2014 | 17        | 7.91%   |
| 2010 | 15        | 6.98%   |
| 2018 | 14        | 6.51%   |
| 2012 | 14        | 6.51%   |
| 2015 | 13        | 6.05%   |
| 2011 | 13        | 6.05%   |
| 2008 | 13        | 6.05%   |
| 2021 | 12        | 5.58%   |
| 2017 | 11        | 5.12%   |
| 2016 | 9         | 4.19%   |
| 2009 | 9         | 4.19%   |
| 2022 | 7         | 3.26%   |
| 2007 | 7         | 3.26%   |
| 2023 | 3         | 1.4%    |
| 2006 | 2         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 215       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 197       | 90.78%  |
| Enabled  | 20        | 9.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 214       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 60        | 27.52%  |
| 4.01-8.0   | 59        | 27.06%  |
| 16.01-24.0 | 33        | 15.14%  |
| 8.01-16.0  | 32        | 14.68%  |
| 32.01-64.0 | 13        | 5.96%   |
| 2.01-3.0   | 8         | 3.67%   |
| 1.01-2.0   | 8         | 3.67%   |
| 24.01-32.0 | 3         | 1.38%   |
| 0.51-1.0   | 2         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 81        | 33.06%  |
| 2.01-3.0   | 60        | 24.49%  |
| 4.01-8.0   | 34        | 13.88%  |
| 0.51-1.0   | 29        | 11.84%  |
| 3.01-4.0   | 26        | 10.61%  |
| 8.01-16.0  | 12        | 4.9%    |
| 16.01-24.0 | 2         | 0.82%   |
| 0.01-0.5   | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 73.85%  |
| 2      | 48        | 22.02%  |
| 3      | 6         | 2.75%   |
| 0      | 2         | 0.92%   |
| 4      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 59.55%  |
| Yes       | 89        | 40.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 88.48%  |
| No        | 25        | 11.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 98.14%  |
| No        | 4         | 1.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 75.8%   |
| No        | 53        | 24.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 215       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 168       | 72.1%   |
| Liepāja                | 7         | 3%      |
| Jelgava                 | 6         | 2.58%   |
| Daugavpils              | 6         | 2.58%   |
| Jūrmala                | 3         | 1.29%   |
| Jaunmarupe              | 3         | 1.29%   |
| Iecava                  | 3         | 1.29%   |
| Adazi                   | 3         | 1.29%   |
| Valmiera                | 2         | 0.86%   |
| Saulkrasti              | 2         | 0.86%   |
| Rēzekne                | 2         | 0.86%   |
| Malpils                 | 2         | 0.86%   |
| Cēsis                  | 2         | 0.86%   |
| Zvejniekciems           | 1         | 0.43%   |
| Ventspils               | 1         | 0.43%   |
| Ulbroka                 | 1         | 0.43%   |
| Tukums                  | 1         | 0.43%   |
| Tiraine                 | 1         | 0.43%   |
| Smiltene                | 1         | 0.43%   |
| Saulkalne               | 1         | 0.43%   |
| Saldus                  | 1         | 0.43%   |
| Salaspils               | 1         | 0.43%   |
| Pļaviņas              | 1         | 0.43%   |
| Nereta                  | 1         | 0.43%   |
| Lizums                  | 1         | 0.43%   |
| Limbaži                | 1         | 0.43%   |
| Kuldīga                | 1         | 0.43%   |
| Ķekava                 | 1         | 0.43%   |
| Jēkabpils Municipality | 1         | 0.43%   |
| Jēkabpils              | 1         | 0.43%   |
| Inčukalns              | 1         | 0.43%   |
| Garkalne                | 1         | 0.43%   |
| Garciems                | 1         | 0.43%   |
| Dobele                  | 1         | 0.43%   |
| Bukulti                 | 1         | 0.43%   |
| Aizpute                 | 1         | 0.43%   |
| Aizkraukle              | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 44        | 60     | 16.79%  |
| Seagate                     | 34        | 40     | 12.98%  |
| Kingston                    | 30        | 44     | 11.45%  |
| WDC                         | 24        | 34     | 9.16%   |
| Toshiba                     | 24        | 27     | 9.16%   |
| Micron Technology           | 10        | 11     | 3.82%   |
| Hitachi                     | 10        | 13     | 3.82%   |
| Unknown                     | 8         | 9      | 3.05%   |
| SK hynix                    | 8         | 8      | 3.05%   |
| HGST                        | 8         | 17     | 3.05%   |
| SanDisk                     | 7         | 17     | 2.67%   |
| Intel                       | 6         | 8      | 2.29%   |
| Crucial                     | 5         | 5      | 1.91%   |
| A-DATA Technology           | 5         | 6      | 1.91%   |
| Patriot                     | 4         | 10     | 1.53%   |
| KIOXIA                      | 4         | 6      | 1.53%   |
| SPCC                        | 2         | 2      | 0.76%   |
| LITEON                      | 2         | 2      | 0.76%   |
| Lexar                       | 2         | 2      | 0.76%   |
| Kingston Technology Company | 2         | 3      | 0.76%   |
| Integral                    | 2         | 2      | 0.76%   |
| Verbatim                    | 1         | 1      | 0.38%   |
| USB                         | 1         | 1      | 0.38%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.38%   |
| Realtek                     | 1         | 1      | 0.38%   |
| PNY                         | 1         | 1      | 0.38%   |
| Plextor                     | 1         | 1      | 0.38%   |
| Platinet                    | 1         | 1      | 0.38%   |
| Phison Electronics          | 1         | 1      | 0.38%   |
| Phison                      | 1         | 1      | 0.38%   |
| OCZ                         | 1         | 1      | 0.38%   |
| Netac                       | 1         | 1      | 0.38%   |
| LITEONIT                    | 1         | 1      | 0.38%   |
| LITEON C                    | 1         | 1      | 0.38%   |
| KingSpec                    | 1         | 1      | 0.38%   |
| Kingchuxing                 | 1         | 9      | 0.38%   |
| Intenso                     | 1         | 1      | 0.38%   |
| Hrdtac                      | 1         | 7      | 0.38%   |
| Fujitsu                     | 1         | 1      | 0.38%   |
| China                       | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 7         | 2.6%    |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 2.23%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 2.23%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 1.49%   |
| Seagate ST1000LM048-2E7172 1TB                      | 4         | 1.49%   |
| Samsung SSD 850 EVO 500GB                           | 4         | 1.49%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.12%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.12%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 1.12%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 1.12%   |
| Hitachi HTS545050B9A300 500GB                       | 3         | 1.12%   |
| HGST HTS545050A7E680 500GB                          | 3         | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.74%   |
| Toshiba MK8034GSX 80GB                              | 2         | 0.74%   |
| Toshiba MK6465GSX 640GB                             | 2         | 0.74%   |
| SK hynix HFM512GDJTNG-8310A 512GB                   | 2         | 0.74%   |
| SK hynix BC511 NVMe 256GB                           | 2         | 0.74%   |
| Seagate ST9160821AS 160GB                           | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.74%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD                 | 2         | 0.74%   |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 0.74%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.74%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.74%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.74%   |
| Samsung MZALQ256HAJD-000L2 256GB                    | 2         | 0.74%   |
| Samsung HM321HI 320GB                               | 2         | 0.74%   |
| Patriot Burst 240GB SSD                             | 2         | 0.74%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 2         | 0.74%   |
| Kingston SV300S37A60G 64GB SSD                      | 2         | 0.74%   |
| Kingston SUV500MS480G 480GB SSD                     | 2         | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.74%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.74%   |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 0.74%   |
| Hitachi HTS545050A7E380 500GB                       | 2         | 0.74%   |
| HGST HTS725032A7E630 320GB                          | 2         | 0.74%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 40     | 35.05%  |
| WDC                 | 20        | 29     | 20.62%  |
| Toshiba             | 19        | 22     | 19.59%  |
| Hitachi             | 10        | 13     | 10.31%  |
| HGST                | 8         | 17     | 8.25%   |
| Samsung Electronics | 4         | 5      | 4.12%   |
| USB                 | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 26        | 39     | 29.21%  |
| Samsung Electronics | 23        | 33     | 25.84%  |
| Crucial             | 5         | 5      | 5.62%   |
| A-DATA Technology   | 5         | 6      | 5.62%   |
| Patriot             | 4         | 10     | 4.49%   |
| SanDisk             | 3         | 6      | 3.37%   |
| Micron Technology   | 3         | 3      | 3.37%   |
| SPCC                | 2         | 2      | 2.25%   |
| LITEON              | 2         | 2      | 2.25%   |
| Integral            | 2         | 2      | 2.25%   |
| Verbatim            | 1         | 1      | 1.12%   |
| Toshiba             | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Plextor             | 1         | 1      | 1.12%   |
| Platinet            | 1         | 1      | 1.12%   |
| OCZ                 | 1         | 1      | 1.12%   |
| LITEONIT            | 1         | 1      | 1.12%   |
| LITEON C            | 1         | 1      | 1.12%   |
| Lexar               | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| Intenso             | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| Apple               | 1         | 1      | 1.12%   |
| Unknown             | 1         | 3      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 94        | 128    | 37.6%   |
| SSD     | 83        | 124    | 33.2%   |
| NVMe    | 65        | 87     | 26%     |
| MMC     | 6         | 7      | 2.4%    |
| Unknown | 2         | 17     | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 157       | 257    | 66.81%  |
| NVMe | 65        | 86     | 27.66%  |
| SAS  | 7         | 13     | 2.98%   |
| MMC  | 6         | 7      | 2.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 123       | 183    | 70.29%  |
| 0.51-1.0   | 47        | 64     | 26.86%  |
| 1.01-2.0   | 5         | 5      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 32.07%  |
| 251-500        | 59        | 24.89%  |
| 501-1000       | 32        | 13.5%   |
| 1-20           | 20        | 8.44%   |
| 51-100         | 18        | 7.59%   |
| 1001-2000      | 16        | 6.75%   |
| 21-50          | 6         | 2.53%   |
| Unknown        | 6         | 2.53%   |
| 2001-3000      | 3         | 1.27%   |
| More than 3000 | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 103       | 43.1%   |
| 21-50     | 36        | 15.06%  |
| 101-250   | 29        | 12.13%  |
| 51-100    | 28        | 11.72%  |
| 251-500   | 18        | 7.53%   |
| 501-1000  | 12        | 5.02%   |
| 1001-2000 | 6         | 2.51%   |
| Unknown   | 6         | 2.51%   |
| 2001-3000 | 1         | 0.42%   |

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
| HGST HTS541075A9E680 752GB           | 1         | 2      | 3.7%    |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 29.63%  |
| HGST                | 6         | 9      | 22.22%  |
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
| HGST                | 6         | 9      | 24%     |
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
| HDD  | 24        | 33     | 92.31%  |
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
| Works    | 105       | 164    | 46.26%  |
| Detected | 94        | 162    | 41.41%  |
| Malfunc  | 26        | 35     | 11.45%  |
| Failed   | 2         | 2      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 166       | 64.59%  |
| AMD                          | 23        | 8.95%   |
| Samsung Electronics          | 21        | 8.17%   |
| SK hynix                     | 8         | 3.11%   |
| SanDisk                      | 8         | 3.11%   |
| Micron Technology            | 7         | 2.72%   |
| Kingston Technology Company  | 6         | 2.33%   |
| KIOXIA                       | 5         | 1.95%   |
| Toshiba America Info Systems | 3         | 1.17%   |
| Union Memory (Shenzhen)      | 2         | 0.78%   |
| Phison Electronics           | 2         | 0.78%   |
| Nvidia                       | 2         | 0.78%   |
| Silicon Motion               | 1         | 0.39%   |
| Silicon Image                | 1         | 0.39%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.39%   |
| ADATA Technology             | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 7.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 6.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 6.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 15        | 5.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 4.29%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6         | 2.14%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 5         | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.43%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.07%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 3         | 1.07%   |
| Intel SSD 660P Series                                                            | 3         | 1.07%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.71%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.71%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.71%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.71%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.71%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 0.71%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 62.27%  |
| NVMe | 68        | 24.91%  |
| IDE  | 19        | 6.96%   |
| RAID | 16        | 5.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 179       | 83.26%  |
| AMD    | 36        | 16.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.33%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2.33%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.86%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.4%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.4%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.4%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.4%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.93%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.93%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.93%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.93%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.93%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.93%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.93%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 53        | 24.65%  |
| Intel Core i7           | 34        | 15.81%  |
| Other                   | 20        | 9.3%    |
| Intel Core i3           | 19        | 8.84%   |
| Intel Core 2 Duo        | 18        | 8.37%   |
| Intel Celeron           | 16        | 7.44%   |
| Intel Pentium           | 8         | 3.72%   |
| AMD Ryzen 7             | 7         | 3.26%   |
| AMD Ryzen 5             | 7         | 3.26%   |
| AMD Ryzen 7 PRO         | 4         | 1.86%   |
| Intel Pentium Dual-Core | 3         | 1.4%    |
| Intel Pentium Dual      | 3         | 1.4%    |
| Intel Genuine           | 3         | 1.4%    |
| AMD A10                 | 3         | 1.4%    |
| Intel Core 2            | 2         | 0.93%   |
| AMD Turion 64 X2 Mobile | 2         | 0.93%   |
| AMD Ryzen 3             | 2         | 0.93%   |
| AMD E1                  | 2         | 0.93%   |
| AMD A8                  | 2         | 0.93%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Pentium Gold      | 1         | 0.47%   |
| Intel Atom              | 1         | 0.47%   |
| AMD Ryzen 5 PRO         | 1         | 0.47%   |
| AMD E2                  | 1         | 0.47%   |
| AMD E                   | 1         | 0.47%   |
| AMD C-70                | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 125       | 57.87%  |
| 4      | 62        | 28.7%   |
| 8      | 12        | 5.56%   |
| 6      | 8         | 3.7%    |
| 1      | 4         | 1.85%   |
| 14     | 2         | 0.93%   |
| 10     | 2         | 0.93%   |
| 24     | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 215       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 146       | 67.59%  |
| 1      | 70        | 32.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 213       | 99.07%  |
| 32-bit         | 1         | 0.47%   |
| Unknown        | 1         | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 23.87%  |
| 0x306a9    | 14        | 6.31%   |
| 0x406e3    | 11        | 4.95%   |
| 0x206a7    | 10        | 4.5%    |
| 0x6fd      | 9         | 4.05%   |
| 0x30678    | 9         | 4.05%   |
| 0x1067a    | 9         | 4.05%   |
| 0x906ea    | 7         | 3.15%   |
| 0x20655    | 7         | 3.15%   |
| 0x806c1    | 6         | 2.7%    |
| 0x306d4    | 6         | 2.7%    |
| 0x40651    | 5         | 2.25%   |
| 0x806ec    | 4         | 1.8%    |
| 0x806ea    | 4         | 1.8%    |
| 0x806e9    | 4         | 1.8%    |
| 0x306c3    | 4         | 1.8%    |
| 0x08108102 | 4         | 1.8%    |
| 0x06001119 | 4         | 1.8%    |
| 0xa0652    | 3         | 1.35%   |
| 0x906e9    | 3         | 1.35%   |
| 0x506e3    | 3         | 1.35%   |
| 0x10676    | 3         | 1.35%   |
| 0x05000119 | 3         | 1.35%   |
| 0x6fa      | 2         | 0.9%    |
| 0x6f6      | 2         | 0.9%    |
| 0x406c3    | 2         | 0.9%    |
| 0x20652    | 2         | 0.9%    |
| 0x0a50000c | 2         | 0.9%    |
| 0x0a404102 | 2         | 0.9%    |
| 0x08600106 | 2         | 0.9%    |
| 0x08600103 | 2         | 0.9%    |
| 0x08108109 | 2         | 0.9%    |
| 0xb06a2    | 1         | 0.45%   |
| 0x906ed    | 1         | 0.45%   |
| 0x906a3    | 1         | 0.45%   |
| 0x806eb    | 1         | 0.45%   |
| 0x806d1    | 1         | 0.45%   |
| 0x706a8    | 1         | 0.45%   |
| 0x706a1    | 1         | 0.45%   |
| 0x6fb      | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 13.95%  |
| IvyBridge        | 18        | 8.37%   |
| Skylake          | 17        | 7.91%   |
| Core             | 17        | 7.91%   |
| Silvermont       | 13        | 6.05%   |
| SandyBridge      | 13        | 6.05%   |
| Westmere         | 12        | 5.58%   |
| Penryn           | 12        | 5.58%   |
| Haswell          | 12        | 5.58%   |
| TigerLake        | 10        | 4.65%   |
| Zen+             | 8         | 3.72%   |
| Zen 2            | 8         | 3.72%   |
| Broadwell        | 7         | 3.26%   |
| Unknown          | 6         | 2.79%   |
| Piledriver       | 4         | 1.86%   |
| CometLake        | 4         | 1.86%   |
| Alderlake Hybrid | 4         | 1.86%   |
| Zen 3            | 3         | 1.4%    |
| Bobcat           | 3         | 1.4%    |
| Puma             | 2         | 0.93%   |
| K8 Hammer        | 2         | 0.93%   |
| Icelake          | 2         | 0.93%   |
| Goldmont plus    | 2         | 0.93%   |
| Excavator        | 2         | 0.93%   |
| P6               | 1         | 0.47%   |
| Nehalem          | 1         | 0.47%   |
| Jaguar           | 1         | 0.47%   |
| Goldmont         | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 157       | 58.8%   |
| Nvidia | 63        | 23.6%   |
| AMD    | 47        | 17.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 5.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 5.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 4.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 3.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 3.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 2.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.8%    |
| Intel HD Graphics 5500                                                                   | 5         | 1.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.44%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.44%   |
| Intel HD Graphics 620                                                                    | 4         | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.44%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.72%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.72%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.72%   |
| Intel HD Graphics 630                                                                    | 2         | 0.72%   |
| Intel HD Graphics 530                                                                    | 2         | 0.72%   |
| Intel HD Graphics                                                                        | 2         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 49.77%  |
| Intel + Nvidia | 42        | 19.53%  |
| 1 x AMD        | 32        | 14.88%  |
| 1 x Nvidia     | 18        | 8.37%   |
| Intel + AMD    | 7         | 3.26%   |
| 2 x AMD        | 5         | 2.33%   |
| AMD + Nvidia   | 3         | 1.4%    |
| 2 x Intel      | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 180       | 80.72%  |
| Proprietary | 36        | 16.14%  |
| Unknown     | 7         | 3.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 55.36%  |
| 1.01-2.0   | 40        | 17.86%  |
| 0.01-0.5   | 28        | 12.5%   |
| 0.51-1.0   | 14        | 6.25%   |
| 3.01-4.0   | 13        | 5.8%    |
| 7.01-8.0   | 3         | 1.34%   |
| 5.01-6.0   | 2         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 23.33%  |
| LG Display              | 36        | 15%     |
| Samsung Electronics     | 32        | 13.33%  |
| BOE                     | 28        | 11.67%  |
| Chimei Innolux          | 24        | 10%     |
| Dell                    | 15        | 6.25%   |
| Chi Mei Optoelectronics | 7         | 2.92%   |
| PANDA                   | 5         | 2.08%   |
| Lenovo                  | 5         | 2.08%   |
| BenQ                    | 5         | 2.08%   |
| Goldstar                | 4         | 1.67%   |
| Apple                   | 3         | 1.25%   |
| Sony                    | 2         | 0.83%   |
| Seiko/Epson             | 2         | 0.83%   |
| Philips                 | 2         | 0.83%   |
| LG Philips              | 2         | 0.83%   |
| InfoVision              | 2         | 0.83%   |
| Hitachi                 | 2         | 0.83%   |
| Xiaomi                  | 1         | 0.42%   |
| Tianma XM               | 1         | 0.42%   |
| Sharp                   | 1         | 0.42%   |
| Quanta Display          | 1         | 0.42%   |
| Panasonic               | 1         | 0.42%   |
| LGD                     | 1         | 0.42%   |
| Hewlett-Packard         | 1         | 0.42%   |
| Acer                    | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.62%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 1.21%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 1.21%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 1.21%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.21%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.81%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.81%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.81%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 2         | 0.81%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                        | 2         | 0.81%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.81%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.81%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.81%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.81%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                       | 1         | 0.4%    |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch              | 1         | 0.4%    |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                    | 1         | 0.4%    |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.4%    |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                  | 1         | 0.4%    |
| Seiko/Epson LCD Monitor 1366x768                                         | 1         | 0.4%    |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch     | 1         | 0.4%    |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 1         | 0.4%    |
| Samsung Electronics S24E650 SAM0CC2 1920x1200 518x324mm 24.1-inch        | 1         | 0.4%    |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch        | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 37.67%  |
| 1366x768 (WXGA)    | 70        | 31.39%  |
| 1600x900 (HD+)     | 15        | 6.73%   |
| 1280x800 (WXGA)    | 14        | 6.28%   |
| 3840x2160 (4K)     | 7         | 3.14%   |
| 2560x1440 (QHD)    | 7         | 3.14%   |
| 1920x1200 (WUXGA)  | 5         | 2.24%   |
| 1440x900 (WXGA+)   | 5         | 2.24%   |
| 3440x1440          | 3         | 1.35%   |
| 1280x1024 (SXGA)   | 3         | 1.35%   |
| 7680x2160          | 1         | 0.45%   |
| 3456x2160          | 1         | 0.45%   |
| 3000x2000          | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2560x1600          | 1         | 0.45%   |
| 2160x1440          | 1         | 0.45%   |
| 1680x1050 (WSXGA+) | 1         | 0.45%   |
| 1360x768           | 1         | 0.45%   |
| 1280x720 (HD)      | 1         | 0.45%   |
| Unknown            | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 112       | 46.47%  |
| 14      | 25        | 10.37%  |
| 13      | 23        | 9.54%   |
| 17      | 21        | 8.71%   |
| 12      | 11        | 4.56%   |
| 24      | 10        | 4.15%   |
| 27      | 5         | 2.07%   |
| 21      | 4         | 1.66%   |
| Unknown | 4         | 1.66%   |
| 40      | 3         | 1.24%   |
| 23      | 3         | 1.24%   |
| 19      | 3         | 1.24%   |
| 16      | 3         | 1.24%   |
| 11      | 3         | 1.24%   |
| 65      | 2         | 0.83%   |
| 35      | 2         | 0.83%   |
| 31      | 2         | 0.83%   |
| 84      | 1         | 0.41%   |
| 43      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 148       | 61.67%  |
| 351-400     | 27        | 11.25%  |
| 201-300     | 24        | 10%     |
| 501-600     | 19        | 7.92%   |
| 401-500     | 6         | 2.5%    |
| 801-900     | 5         | 2.08%   |
| Unknown     | 4         | 1.67%   |
| 601-700     | 2         | 0.83%   |
| 1001-1500   | 2         | 0.83%   |
| 701-800     | 1         | 0.42%   |
| 1501-2000   | 1         | 0.42%   |
| 901-1000    | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 80.93%  |
| 16/10   | 28        | 13.02%  |
| Unknown | 4         | 1.86%   |
| 5/4     | 3         | 1.4%    |
| 3/2     | 3         | 1.4%    |
| 21/9    | 3         | 1.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 45.83%  |
| 81-90          | 41        | 17.08%  |
| 121-130        | 20        | 8.33%   |
| 201-250        | 14        | 5.83%   |
| 61-70          | 11        | 4.58%   |
| 71-80          | 6         | 2.5%    |
| 351-500        | 5         | 2.08%   |
| 301-350        | 5         | 2.08%   |
| 151-200        | 5         | 2.08%   |
| 501-1000       | 4         | 1.67%   |
| Unknown        | 4         | 1.67%   |
| 51-60          | 3         | 1.25%   |
| 251-300        | 3         | 1.25%   |
| 91-100         | 3         | 1.25%   |
| More than 1000 | 2         | 0.83%   |
| 131-140        | 2         | 0.83%   |
| 141-150        | 1         | 0.42%   |
| 111-120        | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 94        | 39.33%  |
| 101-120       | 81        | 33.89%  |
| 51-100        | 42        | 17.57%  |
| 161-240       | 12        | 5.02%   |
| Unknown       | 4         | 1.67%   |
| More than 240 | 3         | 1.26%   |
| 1-50          | 3         | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 177       | 80.45%  |
| 2     | 34        | 15.45%  |
| 0     | 5         | 2.27%   |
| 3     | 4         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 117       | 33.33%  |
| Intel                    | 116       | 33.05%  |
| Qualcomm Atheros         | 51        | 14.53%  |
| Broadcom                 | 23        | 6.55%   |
| Broadcom Limited         | 9         | 2.56%   |
| Marvell Technology Group | 6         | 1.71%   |
| Ralink                   | 4         | 1.14%   |
| Samsung Electronics      | 3         | 0.85%   |
| MediaTek                 | 3         | 0.85%   |
| Lenovo                   | 3         | 0.85%   |
| Xiaomi                   | 2         | 0.57%   |
| vivo                     | 2         | 0.57%   |
| TP-Link                  | 2         | 0.57%   |
| Ralink Technology        | 2         | 0.57%   |
| Nvidia                   | 2         | 0.57%   |
| Hewlett-Packard          | 2         | 0.57%   |
| U-Blox                   | 1         | 0.28%   |
| Qualcomm                 | 1         | 0.28%   |
| Huawei Technologies      | 1         | 0.28%   |
| Google                   | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 17.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 7.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.88%   |
| Intel Wireless 8260                                               | 8         | 1.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.65%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.65%   |
| Intel Wireless 3160                                               | 7         | 1.65%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 6         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.94%   |
| Intel Wireless 7260                                               | 4         | 0.94%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.71%   |
| Intel Wireless-AC 9260                                            | 3         | 0.71%   |
| Intel Wireless 7265                                               | 3         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.71%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 115       | 53%     |
| Qualcomm Atheros      | 44        | 20.28%  |
| Realtek Semiconductor | 27        | 12.44%  |
| Broadcom              | 16        | 7.37%   |
| Broadcom Limited      | 5         | 2.3%    |
| Ralink                | 4         | 1.84%   |
| TP-Link               | 2         | 0.92%   |
| Ralink Technology     | 2         | 0.92%   |
| Qualcomm              | 1         | 0.46%   |
| MediaTek              | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 4.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.67%   |
| Intel Wireless 8260                                                     | 8         | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.21%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.21%   |
| Intel Wireless 3160                                                     | 7         | 3.21%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.21%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 1.83%   |
| Intel Wireless 7260                                                     | 4         | 1.83%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.38%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.38%   |
| Intel Wireless 7265                                                     | 3         | 1.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.38%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.92%   |
| Intel WiFi Link 5100                                                    | 2         | 0.92%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.92%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 54.68%  |
| Intel                    | 41        | 20.2%   |
| Qualcomm Atheros         | 14        | 6.9%    |
| Broadcom                 | 12        | 5.91%   |
| Marvell Technology Group | 6         | 2.96%   |
| Broadcom Limited         | 4         | 1.97%   |
| Lenovo                   | 3         | 1.48%   |
| Xiaomi                   | 2         | 0.99%   |
| vivo                     | 2         | 0.99%   |
| Nvidia                   | 2         | 0.99%   |
| MediaTek                 | 2         | 0.99%   |
| Samsung Electronics      | 1         | 0.49%   |
| Huawei Technologies      | 1         | 0.49%   |
| Hewlett-Packard          | 1         | 0.49%   |
| Google                   | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 35.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 14.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.96%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.48%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.48%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.99%   |
| vivo 1820                                                         | 2         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.99%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.99%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.99%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.99%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.49%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.49%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.49%   |
| MediaTek P8                                                       | 1         | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.49%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| Lenovo Powered Hub                                                | 1         | 0.49%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.49%   |
| Intel Ethernet Controller I219-V                                  | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 51.84%  |
| Ethernet | 192       | 47.17%  |
| Modem    | 4         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 181       | 80.44%  |
| Ethernet | 44        | 19.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 179       | 83.26%  |
| 1     | 33        | 15.35%  |
| 3     | 2         | 0.93%   |
| 0     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 93.98%  |
| Yes  | 13        | 6.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 43.98%  |
| Realtek Semiconductor           | 17        | 10.24%  |
| Lite-On Technology              | 13        | 7.83%   |
| IMC Networks                    | 13        | 7.83%   |
| Qualcomm Atheros Communications | 12        | 7.23%   |
| Broadcom                        | 11        | 6.63%   |
| Dell                            | 5         | 3.01%   |
| Hewlett-Packard                 | 4         | 2.41%   |
| Toshiba                         | 3         | 1.81%   |
| Apple                           | 3         | 1.81%   |
| Ralink                          | 2         | 1.2%    |
| Foxconn / Hon Hai               | 2         | 1.2%    |
| Cambridge Silicon Radio         | 2         | 1.2%    |
| USI                             | 1         | 0.6%    |
| Taiyo Yuden                     | 1         | 0.6%    |
| Ralink Technology               | 1         | 0.6%    |
| Qcom                            | 1         | 0.6%    |
| Fujitsu                         | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 16.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.23%   |
| Intel AX201 Bluetooth                               | 12        | 7.23%   |
| Realtek Bluetooth Radio                             | 10        | 6.02%   |
| Intel AX200 Bluetooth                               | 7         | 4.22%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.01%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 2.41%   |
| Intel Bluetooth Device                              | 4         | 2.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.81%   |
| Lite-On Bluetooth Device                            | 3         | 1.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.81%   |
| Intel AX210 Bluetooth                               | 3         | 1.81%   |
| IMC Networks Bluetooth Device                       | 3         | 1.81%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.2%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.2%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.2%    |
| Dell Wireless 355 Bluetooth                         | 2         | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.2%    |
| Broadcom HP Portable SoftSailing                    | 2         | 1.2%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.2%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.2%    |
| Apple Bluetooth Host Controller                     | 2         | 1.2%    |
| USI Bluetooth Device                                | 1         | 0.6%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.6%    |
| Toshiba Bluetooth Device                            | 1         | 0.6%    |
| Toshiba Askey Bluetooth Module                      | 1         | 0.6%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.6%    |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 177       | 66.79%  |
| AMD                   | 40        | 15.09%  |
| Nvidia                | 33        | 12.45%  |
| Logitech              | 3         | 1.13%   |
| C-Media Electronics   | 3         | 1.13%   |
| Realtek Semiconductor | 2         | 0.75%   |
| Razer USA             | 1         | 0.38%   |
| Microsoft             | 1         | 0.38%   |
| Lenovo                | 1         | 0.38%   |
| GYROCOM C&C           | 1         | 0.38%   |
| GN Netcom             | 1         | 0.38%   |
| Creative Technology   | 1         | 0.38%   |
| Apple                 | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 23        | 7.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 6.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 5.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 3.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 2.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 2.88%   |
| AMD FCH Azalia Controller                                                  | 9         | 2.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.24%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.24%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                          | 4         | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.64%   |
| Nvidia Audio device                                                        | 2         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.64%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 26.01%  |
| SK hynix            | 41        | 23.7%   |
| Unknown             | 25        | 14.45%  |
| Kingston            | 24        | 13.87%  |
| Micron Technology   | 15        | 8.67%   |
| Crucial             | 5         | 2.89%   |
| G.Skill             | 3         | 1.73%   |
| Elpida              | 3         | 1.73%   |
| Ramaxel Technology  | 2         | 1.16%   |
| Corsair             | 2         | 1.16%   |
| A-DATA Technology   | 2         | 1.16%   |
| Toshiba             | 1         | 0.58%   |
| PNY                 | 1         | 0.58%   |
| Patriot             | 1         | 0.58%   |
| Nanya Technology    | 1         | 0.58%   |
| GOODRAM             | 1         | 0.58%   |
| ASint Technology    | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 4         | 2.21%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 1.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 3         | 1.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 1.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 2         | 1.1%    |
| Unknown RAM Module 2GB SODIMM 533MT/s                    | 2         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 2         | 1.1%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.1%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 1.1%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s    | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s | 2         | 1.1%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 1.1%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 1.1%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 2         | 1.1%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 2         | 1.1%    |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s     | 2         | 1.1%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s  | 2         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s              | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s            | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s            | 1         | 0.55%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s             | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s            | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3                       | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s               | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR                     | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s               | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s           | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 54        | 38.85%  |
| DDR3    | 54        | 38.85%  |
| DDR2    | 15        | 10.79%  |
| SDRAM   | 3         | 2.16%   |
| LPDDR5  | 3         | 2.16%   |
| LPDDR4  | 3         | 2.16%   |
| Unknown | 3         | 2.16%   |
| LPDDR3  | 1         | 0.72%   |
| DRAM    | 1         | 0.72%   |
| DDR5    | 1         | 0.72%   |
| DDR     | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 131       | 94.93%  |
| Row Of Chips | 6         | 4.35%   |
| Chip         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 33.55%  |
| 8192  | 48        | 30.97%  |
| 2048  | 29        | 18.71%  |
| 16384 | 17        | 10.97%  |
| 1024  | 5         | 3.23%   |
| 32768 | 3         | 1.94%   |
| 512   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 35        | 22.73%  |
| 2667    | 26        | 16.88%  |
| 3200    | 18        | 11.69%  |
| 1334    | 11        | 7.14%   |
| 667     | 11        | 7.14%   |
| 1333    | 10        | 6.49%   |
| 2400    | 8         | 5.19%   |
| 2133    | 8         | 5.19%   |
| 6400    | 3         | 1.95%   |
| 1066    | 3         | 1.95%   |
| Unknown | 3         | 1.95%   |
| 4267    | 2         | 1.3%    |
| 1067    | 2         | 1.3%    |
| 800     | 2         | 1.3%    |
| 533     | 2         | 1.3%    |
| 8400    | 1         | 0.65%   |
| 5600    | 1         | 0.65%   |
| 4199    | 1         | 0.65%   |
| 3266    | 1         | 0.65%   |
| 2933    | 1         | 0.65%   |
| 2048    | 1         | 0.65%   |
| 1867    | 1         | 0.65%   |
| 1639    | 1         | 0.65%   |
| 975     | 1         | 0.65%   |
| 200     | 1         | 0.65%   |

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
| Chicony Electronics                    | 52        | 28.73%  |
| IMC Networks                           | 20        | 11.05%  |
| Realtek Semiconductor                  | 18        | 9.94%   |
| Microdia                               | 12        | 6.63%   |
| Bison Electronics                      | 10        | 5.52%   |
| Suyin                                  | 9         | 4.97%   |
| Sunplus Innovation Technology          | 8         | 4.42%   |
| Quanta                                 | 8         | 4.42%   |
| Lite-On Technology                     | 6         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.31%   |
| Syntek                                 | 5         | 2.76%   |
| Acer                                   | 4         | 2.21%   |
| Silicon Motion                         | 3         | 1.66%   |
| Luxvisions Innotech Limited            | 3         | 1.66%   |
| Ricoh                                  | 2         | 1.1%    |
| Apple                                  | 2         | 1.1%    |
| Z-Star Microelectronics                | 1         | 0.55%   |
| Sonix Technology                       | 1         | 0.55%   |
| Shinetech                              | 1         | 0.55%   |
| Samsung Electronics                    | 1         | 0.55%   |
| Primax Electronics                     | 1         | 0.55%   |
| OmniVision Technologies                | 1         | 0.55%   |
| Microsoft                              | 1         | 0.55%   |
| Lenovo                                 | 1         | 0.55%   |
| Genesys Logic                          | 1         | 0.55%   |
| DigiTech                               | 1         | 0.55%   |
| Arkmicro Technologies                  | 1         | 0.55%   |
| ALi                                    | 1         | 0.55%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 4.89%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 3.26%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.72%   |
| IMC Networks Integrated Camera                              | 5         | 2.72%   |
| Sunplus Asus Webcam                                         | 4         | 2.17%   |
| Realtek USB Camera                                          | 4         | 2.17%   |
| Lite-On Integrated Camera                                   | 4         | 2.17%   |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 2.17%   |
| Chicony HP HD Camera                                        | 4         | 2.17%   |
| Chicony HD WebCam                                           | 4         | 2.17%   |
| Chicony HD User Facing                                      | 4         | 2.17%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.63%   |
| Realtek Integrated Webcam                                   | 3         | 1.63%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.63%   |
| Chicony USB2.0 VGA UVC WebCam                               | 3         | 1.63%   |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 1.63%   |
| Suyin HD WebCam                                             | 2         | 1.09%   |
| Realtek HP Webcam                                           | 2         | 1.09%   |
| Quanta HD Webcam                                            | 2         | 1.09%   |
| Microdia Lenovo EasyCamera                                  | 2         | 1.09%   |
| Microdia Integrated Webcam                                  | 2         | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.09%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.09%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.09%   |
| Chicony HP Truevision HD camera                             | 2         | 1.09%   |
| Chicony HP HD Webcam                                        | 2         | 1.09%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 1.09%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.09%   |
| Bison Integrated Camera                                     | 2         | 1.09%   |
| Bison HD Webcam                                             | 2         | 1.09%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.54%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                        | 1         | 0.54%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.54%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.54%   |
| Syntek Integrated Camera                                    | 1         | 0.54%   |
| Syntek EasyCamera                                           | 1         | 0.54%   |
| Suyin WebCam                                                | 1         | 0.54%   |
| Suyin HD Video WebCam                                       | 1         | 0.54%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.54%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 40%     |
| Synaptics                  | 12        | 26.67%  |
| AuthenTec                  | 5         | 11.11%  |
| Upek                       | 3         | 6.67%   |
| STMicroelectronics         | 2         | 4.44%   |
| Shenzhen Goodix Technology | 2         | 4.44%   |
| Elan Microelectronics      | 2         | 4.44%   |
| LighTuning Technology      | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 8.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 8.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6.67%   |
| Validity Sensors VFS491                                                    | 2         | 4.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.44%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.44%   |
| Synaptics UWP WBDI Device                                                  | 2         | 4.44%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 4.44%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.44%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.22%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.22%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.22%   |
| AuthenTec AES1600                                                          | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 15        | 60%     |
| Broadcom    | 6         | 24%     |
| Lenovo      | 2         | 8%      |
| Upek        | 1         | 4%      |
| O2 Micro    | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 15        | 60%     |
| Broadcom 58200                                             | 5         | 20%     |
| Lenovo Integrated Smart Card Reader                        | 2         | 8%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4%      |
| Broadcom 5880                                              | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 134       | 60.09%  |
| 1     | 60        | 26.91%  |
| 2     | 24        | 10.76%  |
| 3     | 4         | 1.79%   |
| 4     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 45        | 38.79%  |
| Graphics card            | 25        | 21.55%  |
| Chipcard                 | 20        | 17.24%  |
| Net/wireless             | 9         | 7.76%   |
| Multimedia controller    | 5         | 4.31%   |
| Camera                   | 5         | 4.31%   |
| Storage                  | 2         | 1.72%   |
| Communication controller | 2         | 1.72%   |
| Bluetooth                | 2         | 1.72%   |
| Card reader              | 1         | 0.86%   |

