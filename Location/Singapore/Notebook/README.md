Linux in Singapore - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [d94ad2e231](https://linux-hardware.org/?probe=d94ad2e231) | Jun 28, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| Dell          | Precision 5520              | [8d5ec720c1](https://linux-hardware.org/?probe=8d5ec720c1) | Jun 19, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Aspire 4750                 | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Unknown       | AG958                       | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| Dell          | Latitude 7400               | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [c518902ba7](https://linux-hardware.org/?probe=c518902ba7) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| ASUSTek       | X45A                        | [a0401520d5](https://linux-hardware.org/?probe=a0401520d5) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [dbe8e77436](https://linux-hardware.org/?probe=dbe8e77436) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [675de376da](https://linux-hardware.org/?probe=675de376da) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HUAWEI        | MACHC-WAX9                  | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Acer          | Aspire V5-132               | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| ASUSTek       | K45VM                       | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Acer          | Aspire ES1-432              | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| Dell          | Latitude 7390               | [cc5d8632f5](https://linux-hardware.org/?probe=cc5d8632f5) | Jan 13, 2023 |
| Dell          | Latitude 7390               | [a8ee39edc5](https://linux-hardware.org/?probe=a8ee39edc5) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ae506ac561](https://linux-hardware.org/?probe=ae506ac561) | Jan 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| ASUSTek       | X555LAB                     | [3af1bc02b8](https://linux-hardware.org/?probe=3af1bc02b8) | Jan 05, 2023 |
| ASUSTek       | X555LAB                     | [0a1360a7dc](https://linux-hardware.org/?probe=0a1360a7dc) | Jan 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | Inspiron 1420               | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [51f520d152](https://linux-hardware.org/?probe=51f520d152) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [d5171f9491](https://linux-hardware.org/?probe=d5171f9491) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Dell          | Precision 3571              | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| Google        | Atlas                       | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Dell          | Precision 3571              | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| Dell          | Precision 3571              | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| Dell          | Precision 3571              | [9da55445b0](https://linux-hardware.org/?probe=9da55445b0) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0a0922ed82](https://linux-hardware.org/?probe=0a0922ed82) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [18893915f3](https://linux-hardware.org/?probe=18893915f3) | Oct 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Dell          | Latitude 3320               | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| MSI           | Pulse GL66 11UGK            | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Acer          | Aspire V5-471PG             | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| Dell          | Latitude 3320               | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Acer          | Aspire A315-41              | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Acer          | Aspire A315-41              | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Latitude 3120               | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Sony          | VPCCA15FG                   | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Lenovo        | 14w 81MQS02H00              | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| Dell          | XPS 13 7390                 | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | Latitude 3120               | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Dell          | Inspiron 3501               | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| ASUSTek       | K45VM                       | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASUSTek       | N501JW                      | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Apple         | MacBookPro7,1               | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| Apple         | MacBookPro7,1               | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | Inspiron 5580               | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Acer          | Aspire 6935                 | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Toshiba       | PORTEGE R930                | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | K45VM                       | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| Sony          | VPCSB36FG                   | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| Aftershock    | N15_N17RF1                  | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | Inspiron 5379               | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| Fujitsu       | LIFEBOOK SH561              | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| HP            | Compaq 6510b                | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| HP            | Compaq 6510b                | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| Aftershock    | N8xxEP6                     | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Dell          | Precision 7530              | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Toshiba       | PORTEGE R930                | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Lenovo        | Yoga 3 14 80JH              | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | XPS 13 9370                 | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| Lenovo        | IdeaPad U460 20056          | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| Dell          | Latitude E7440              | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| Acer          | Predator PH315-52           | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| ASUSTek       | T300LA                      | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | B50-30 20382                | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| Acer          | ConceptD CN715-71           | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| ASUSTek       | U24E                        | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| HP            | ZBook Studio G5             | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Acer          | AO751h                      | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | GE63VR 7RE                  | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 19.41%  |
| Ubuntu 18.04                 | 19        | 8.02%   |
| Ubuntu 22.04                 | 15        | 6.33%   |
| Fedora 33                    | 10        | 4.22%   |
| Arch Rolling                 | 8         | 3.38%   |
| Pop!_OS 22.04                | 5         | 2.11%   |
| Pop!_OS 20.04                | 5         | 2.11%   |
| Arch                         | 5         | 2.11%   |
| Zorin 16                     | 4         | 1.69%   |
| OpenMandriva 23.01           | 4         | 1.69%   |
| Linux Mint 21                | 4         | 1.69%   |
| Fedora 38                    | 4         | 1.69%   |
| Debian Testing               | 4         | 1.69%   |
| Debian 11                    | 4         | 1.69%   |
| Xubuntu 20.04                | 3         | 1.27%   |
| Linux Mint 20                | 3         | 1.27%   |
| Kubuntu 22.04                | 3         | 1.27%   |
| Fedora 37                    | 3         | 1.27%   |
| Fedora 36                    | 3         | 1.27%   |
| Fedora 32                    | 3         | 1.27%   |
| EndeavourOS Rolling          | 3         | 1.27%   |
| Elementary 6.1               | 3         | 1.27%   |
| ArcoLinux Rolling            | 3         | 1.27%   |
| Zorin 15                     | 2         | 0.84%   |
| Ubuntu 21.10                 | 2         | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.84%   |
| OpenMandriva 4.3             | 2         | 0.84%   |
| Manjaro 20.1                 | 2         | 0.84%   |
| Manjaro                      | 2         | 0.84%   |
| Linux Mint 21.1              | 2         | 0.84%   |
| Kubuntu 20.10                | 2         | 0.84%   |
| KDE neon 22.04               | 2         | 0.84%   |
| Gentoo 2.6                   | 2         | 0.84%   |
| Garuda Linux Soaring         | 2         | 0.84%   |
| Fedora 35                    | 2         | 0.84%   |
| Fedora 34                    | 2         | 0.84%   |
| Fedora 31                    | 2         | 0.84%   |
| Debian 12                    | 2         | 0.84%   |
| Debian                       | 2         | 0.84%   |
| Xubuntu 21.04                | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 87        | 38.33%  |
| Fedora        | 23        | 10.13%  |
| Debian        | 14        | 6.17%   |
| Pop!_OS       | 13        | 5.73%   |
| Arch          | 12        | 5.29%   |
| Linux Mint    | 10        | 4.41%   |
| OpenMandriva  | 9         | 3.96%   |
| Zorin         | 6         | 2.64%   |
| Manjaro       | 6         | 2.64%   |
| Kubuntu       | 6         | 2.64%   |
| Xubuntu       | 4         | 1.76%   |
| KDE neon      | 3         | 1.32%   |
| EndeavourOS   | 3         | 1.32%   |
| Elementary    | 3         | 1.32%   |
| ArcoLinux     | 3         | 1.32%   |
| Ubuntu Unity  | 2         | 0.88%   |
| ROSA          | 2         | 0.88%   |
| RHEL          | 2         | 0.88%   |
| openSUSE      | 2         | 0.88%   |
| Lubuntu       | 2         | 0.88%   |
| Kali          | 2         | 0.88%   |
| Gentoo        | 2         | 0.88%   |
| Garuda Linux  | 2         | 0.88%   |
| Endless       | 2         | 0.88%   |
| Clear Linux   | 2         | 0.88%   |
| Ubuntu Budgie | 1         | 0.44%   |
| Q4OS          | 1         | 0.44%   |
| NixOS         | 1         | 0.44%   |
| LMDE          | 1         | 0.44%   |
| Deepin        | 1         | 0.44%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.0-56-generic       | 6         | 2.25%   |
| 5.4.0-48-generic        | 5         | 1.87%   |
| 5.15.0-46-generic       | 5         | 1.87%   |
| 6.1.1-desktop-1omv2290  | 4         | 1.5%    |
| 5.9.8-200.fc33.x86_64   | 4         | 1.5%    |
| 5.4.0-42-generic        | 4         | 1.5%    |
| 5.4.0-40-generic        | 4         | 1.5%    |
| 5.3.0-62-generic        | 4         | 1.5%    |
| 5.11.0-43-generic       | 4         | 1.5%    |
| 6.2.15-300.fc38.x86_64  | 3         | 1.12%   |
| 5.4.0-65-generic        | 3         | 1.12%   |
| 5.4.0-52-generic        | 3         | 1.12%   |
| 5.4.0-47-generic        | 3         | 1.12%   |
| 5.4.0-37-generic        | 3         | 1.12%   |
| 5.4.0-29-generic        | 3         | 1.12%   |
| 5.15.0-41-generic       | 3         | 1.12%   |
| 5.13.0-28-generic       | 3         | 1.12%   |
| 5.11.0-38-generic       | 3         | 1.12%   |
| 6.2.10-300.fc38.x86_64  | 2         | 0.75%   |
| 6.2.0-20-generic        | 2         | 0.75%   |
| 6.1.14-200.fc37.x86_64  | 2         | 0.75%   |
| 6.0.6-76060006-generic  | 2         | 0.75%   |
| 5.4.5-050405-generic    | 2         | 0.75%   |
| 5.4.0-7634-generic      | 2         | 0.75%   |
| 5.4.0-31-generic        | 2         | 0.75%   |
| 5.4.0-26-generic        | 2         | 0.75%   |
| 5.19.0-40-generic       | 2         | 0.75%   |
| 5.18.0-3-amd64          | 2         | 0.75%   |
| 5.18.0-2-amd64          | 2         | 0.75%   |
| 5.17.5-76051705-generic | 2         | 0.75%   |
| 5.16.7-desktop-1omv4003 | 2         | 0.75%   |
| 5.15.0-67-generic       | 2         | 0.75%   |
| 5.15.0-58-generic       | 2         | 0.75%   |
| 5.15.0-48-generic       | 2         | 0.75%   |
| 5.15.0-47-generic       | 2         | 0.75%   |
| 5.15.0-43-generic       | 2         | 0.75%   |
| 5.13.0-40-generic       | 2         | 0.75%   |
| 5.13.0-37-generic       | 2         | 0.75%   |
| 5.11.0-37-generic       | 2         | 0.75%   |
| 5.11.0-25-generic       | 2         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 15.42%  |
| 5.15.0  | 29        | 11.46%  |
| 5.11.0  | 13        | 5.14%   |
| 5.8.0   | 11        | 4.35%   |
| 5.13.0  | 10        | 3.95%   |
| 5.3.0   | 7         | 2.77%   |
| 4.18.0  | 7         | 2.77%   |
| 4.15.0  | 7         | 2.77%   |
| 5.19.0  | 6         | 2.37%   |
| 5.18.0  | 6         | 2.37%   |
| 5.10.0  | 5         | 1.98%   |
| 6.1.1   | 4         | 1.58%   |
| 5.9.8   | 4         | 1.58%   |
| 5.0.0   | 4         | 1.58%   |
| 6.2.15  | 3         | 1.19%   |
| 6.1.0   | 3         | 1.19%   |
| 6.2.10  | 2         | 0.79%   |
| 6.2.0   | 2         | 0.79%   |
| 6.1.14  | 2         | 0.79%   |
| 6.0.7   | 2         | 0.79%   |
| 6.0.6   | 2         | 0.79%   |
| 6.0.0   | 2         | 0.79%   |
| 5.4.5   | 2         | 0.79%   |
| 5.19.13 | 2         | 0.79%   |
| 5.17.5  | 2         | 0.79%   |
| 5.16.7  | 2         | 0.79%   |
| 5.13.13 | 2         | 0.79%   |
| 4.19.0  | 2         | 0.79%   |
| 6.3.8   | 1         | 0.4%    |
| 6.3.5   | 1         | 0.4%    |
| 6.3.3   | 1         | 0.4%    |
| 6.2.9   | 1         | 0.4%    |
| 6.2.6   | 1         | 0.4%    |
| 6.2.14  | 1         | 0.4%    |
| 6.2.12  | 1         | 0.4%    |
| 6.1.3   | 1         | 0.4%    |
| 6.1.20  | 1         | 0.4%    |
| 6.0.2   | 1         | 0.4%    |
| 5.9.9   | 1         | 0.4%    |
| 5.9.16  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 46        | 18.93%  |
| 5.15    | 34        | 13.99%  |
| 5.8     | 17        | 7%      |
| 5.13    | 16        | 6.58%   |
| 5.11    | 14        | 5.76%   |
| 5.10    | 11        | 4.53%   |
| 6.1     | 10        | 4.12%   |
| 5.18    | 10        | 4.12%   |
| 5.19    | 9         | 3.7%    |
| 6.0     | 7         | 2.88%   |
| 5.9     | 7         | 2.88%   |
| 5.3     | 7         | 2.88%   |
| 4.18    | 7         | 2.88%   |
| 4.15    | 7         | 2.88%   |
| 6.2     | 6         | 2.47%   |
| 5.16    | 6         | 2.47%   |
| 5.0     | 5         | 2.06%   |
| 5.6     | 4         | 1.65%   |
| 5.17    | 4         | 1.65%   |
| 6.3     | 3         | 1.23%   |
| 5.12    | 3         | 1.23%   |
| 4.19    | 3         | 1.23%   |
| 5.5     | 2         | 0.82%   |
| 5.7     | 1         | 0.41%   |
| 5.14    | 1         | 0.41%   |
| 4.4     | 1         | 0.41%   |
| 4.16    | 1         | 0.41%   |
| 3.10    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 216       | 99.08%  |
| i686   | 2         | 0.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 127       | 55.7%   |
| KDE5            | 35        | 15.35%  |
| Unknown         | 22        | 9.65%   |
| X-Cinnamon      | 11        | 4.82%   |
| XFCE            | 9         | 3.95%   |
| KDE             | 5         | 2.19%   |
| Cinnamon        | 4         | 1.75%   |
| Pantheon        | 3         | 1.32%   |
| LXQt            | 3         | 1.32%   |
| Unity           | 2         | 0.88%   |
| MATE            | 1         | 0.44%   |
| KDE4            | 1         | 0.44%   |
| i3              | 1         | 0.44%   |
| Hyprland        | 1         | 0.44%   |
| GNOME Flashback | 1         | 0.44%   |
| GNOME Classic   | 1         | 0.44%   |
| Budgie          | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 167       | 73.25%  |
| Wayland | 40        | 17.54%  |
| Unknown | 13        | 5.7%    |
| Tty     | 8         | 3.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 101       | 44.3%   |
| GDM     | 43        | 18.86%  |
| GDM3    | 33        | 14.47%  |
| SDDM    | 32        | 14.04%  |
| LightDM | 14        | 6.14%   |
| TDM     | 4         | 1.75%   |
| KDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_SG   | 90        | 40.36%  |
| en_US   | 86        | 38.57%  |
| Unknown | 17        | 7.62%   |
| zh_CN   | 6         | 2.69%   |
| en_IN   | 6         | 2.69%   |
| C       | 6         | 2.69%   |
| en_GB   | 3         | 1.35%   |
| de_DE   | 3         | 1.35%   |
| en_PH   | 2         | 0.9%    |
| en_AU   | 2         | 0.9%    |
| ru_UA   | 1         | 0.45%   |
| en_IE   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 154       | 70%     |
| BIOS | 66        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 177       | 79.73%  |
| Btrfs   | 22        | 9.91%   |
| Overlay | 10        | 4.5%    |
| Unknown | 7         | 3.15%   |
| Xfs     | 3         | 1.35%   |
| Zfs     | 2         | 0.9%    |
| Tmpfs   | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 48.42%  |
| GPT     | 106       | 47.96%  |
| MBR     | 8         | 3.62%   |

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
| No        | 136       | 61.82%  |
| Yes       | 84        | 38.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 58        | 26.61%  |
| Dell                   | 46        | 21.1%   |
| ASUSTek Computer       | 34        | 15.6%   |
| Acer                   | 27        | 12.39%  |
| Hewlett-Packard        | 13        | 5.96%   |
| Apple                  | 8         | 3.67%   |
| Sony                   | 5         | 2.29%   |
| MSI                    | 4         | 1.83%   |
| Toshiba                | 2         | 0.92%   |
| Timi                   | 2         | 0.92%   |
| Samsung Electronics    | 2         | 0.92%   |
| HUAWEI                 | 2         | 0.92%   |
| Fujitsu                | 2         | 0.92%   |
| Foxconn                | 2         | 0.92%   |
| Aftershock             | 2         | 0.92%   |
| Unknown                | 2         | 0.92%   |
| Razer                  | 1         | 0.46%   |
| Notebook               | 1         | 0.46%   |
| MECHREVO               | 1         | 0.46%   |
| Google                 | 1         | 0.46%   |
| COPELION INTERNATIONAL | 1         | 0.46%   |
| AZW                    | 1         | 0.46%   |
| AMI                    | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron 15 5510                                 | 3         | 1.38%   |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.92%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.92%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.92%   |
| HP Compaq 6510b                                       | 2         | 0.92%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.92%   |
| Dell XPS 13 9310                                      | 2         | 0.92%   |
| Dell XPS 13 7390                                      | 2         | 0.92%   |
| Dell Latitude 3320                                    | 2         | 0.92%   |
| Dell Latitude 3120                                    | 2         | 0.92%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 0.92%   |
| ASUS T300LA                                           | 2         | 0.92%   |
| ASUS K45VM                                            | 2         | 0.92%   |
| Apple MacBookPro8,1                                   | 2         | 0.92%   |
| Acer Swift SF314-57G                                  | 2         | 0.92%   |
| Acer ConceptD CN715-71                                | 2         | 0.92%   |
| Unknown                                               | 2         | 0.92%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.46%   |
| Toshiba PORTEGE R930                                  | 1         | 0.46%   |
| Timi TM1701                                           | 1         | 0.46%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.46%   |
| Sony VPCSB36FG                                        | 1         | 0.46%   |
| Sony VPCCA15FG                                        | 1         | 0.46%   |
| Sony VGN-CR32G_W                                      | 1         | 0.46%   |
| Sony SVF1531V8CW                                      | 1         | 0.46%   |
| Sony SVE11116FGW                                      | 1         | 0.46%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.46%   |
| Samsung 305U1A                                        | 1         | 0.46%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.46%   |
| Notebook P65_P67SE                                    | 1         | 0.46%   |
| MSI Pulse GL66 11UGK                                  | 1         | 0.46%   |
| MSI Modern 14 B5M                                     | 1         | 0.46%   |
| MSI GE63VR 7RE                                        | 1         | 0.46%   |
| MSI GE62VR 6RF                                        | 1         | 0.46%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.46%   |
| Lenovo Yoga Slim 7 proX 14ARH7 82TL                   | 1         | 0.46%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.46%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.46%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.46%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 32        | 14.68%  |
| Dell Inspiron      | 17        | 7.8%    |
| Acer Aspire        | 13        | 5.96%   |
| Dell Latitude      | 12        | 5.5%    |
| ASUS VivoBook      | 11        | 5.05%   |
| Dell XPS           | 10        | 4.59%   |
| Lenovo IdeaPad     | 9         | 4.13%   |
| Lenovo Legion      | 8         | 3.67%   |
| Acer Swift         | 8         | 3.67%   |
| Dell Precision     | 5         | 2.29%   |
| ASUS ZenBook       | 5         | 2.29%   |
| Lenovo Yoga        | 4         | 1.83%   |
| HP Pavilion        | 4         | 1.83%   |
| HP ZBook           | 3         | 1.38%   |
| HP EliteBook       | 3         | 1.38%   |
| Apple MacBookPro11 | 3         | 1.38%   |
| Toshiba PORTEGE    | 2         | 0.92%   |
| HP Compaq          | 2         | 0.92%   |
| Fujitsu LIFEBOOK   | 2         | 0.92%   |
| Foxconn Kangaroo   | 2         | 0.92%   |
| ASUS TUF           | 2         | 0.92%   |
| ASUS T300LA        | 2         | 0.92%   |
| ASUS K45VM         | 2         | 0.92%   |
| ASUS ASUS          | 2         | 0.92%   |
| Apple MacBookPro8  | 2         | 0.92%   |
| Acer Predator      | 2         | 0.92%   |
| Acer ConceptD      | 2         | 0.92%   |
| Unknown            | 2         | 0.92%   |
| Timi TM1701        | 1         | 0.46%   |
| Timi Redmi         | 1         | 0.46%   |
| Sony VPCSB36FG     | 1         | 0.46%   |
| Sony VPCCA15FG     | 1         | 0.46%   |
| Sony VGN-CR32G     | 1         | 0.46%   |
| Sony SVF1531V8CW   | 1         | 0.46%   |
| Sony SVE11116FGW   | 1         | 0.46%   |
| Samsung RF510      | 1         | 0.46%   |
| Samsung 305U1A     | 1         | 0.46%   |
| Razer Blade        | 1         | 0.46%   |
| Notebook P65       | 1         | 0.46%   |
| MSI Pulse          | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 31        | 14.22%  |
| 2019 | 29        | 13.3%   |
| 2020 | 24        | 11.01%  |
| 2018 | 21        | 9.63%   |
| 2011 | 16        | 7.34%   |
| 2022 | 15        | 6.88%   |
| 2017 | 13        | 5.96%   |
| 2012 | 13        | 5.96%   |
| 2016 | 11        | 5.05%   |
| 2014 | 11        | 5.05%   |
| 2015 | 9         | 4.13%   |
| 2013 | 7         | 3.21%   |
| 2010 | 5         | 2.29%   |
| 2008 | 5         | 2.29%   |
| 2007 | 5         | 2.29%   |
| 2009 | 3         | 1.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 218       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 182       | 82.73%  |
| Enabled  | 38        | 17.27%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 99.54%  |
| Yes  | 1         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 63        | 28.25%  |
| 4.01-8.0    | 53        | 23.77%  |
| 8.01-16.0   | 36        | 16.14%  |
| 3.01-4.0    | 32        | 14.35%  |
| 32.01-64.0  | 22        | 9.87%   |
| 1.01-2.0    | 7         | 3.14%   |
| 24.01-32.0  | 5         | 2.24%   |
| 64.01-256.0 | 3         | 1.35%   |
| 2.01-3.0    | 2         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 68        | 27.09%  |
| 2.01-3.0   | 56        | 22.31%  |
| 4.01-8.0   | 54        | 21.51%  |
| 3.01-4.0   | 40        | 15.94%  |
| 8.01-16.0  | 18        | 7.17%   |
| 0.51-1.0   | 10        | 3.98%   |
| 16.01-24.0 | 2         | 0.8%    |
| 0.01-0.5   | 2         | 0.8%    |
| 24.01-32.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 160       | 71.43%  |
| 2      | 52        | 23.21%  |
| 3      | 9         | 4.02%   |
| 0      | 2         | 0.89%   |
| 4      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 81.82%  |
| Yes       | 40        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 65.3%   |
| No        | 76        | 34.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 97.71%  |
| No        | 5         | 2.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 84.16%  |
| No        | 35        | 15.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 218       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 209       | 95.87%  |
| Jurong West          | 4         | 1.83%   |
| Yio Chu Kang         | 1         | 0.46%   |
| Sembawang Estate     | 1         | 0.46%   |
| Queenstown Estate    | 1         | 0.46%   |
| Kampong Ulu Jurong   | 1         | 0.46%   |
| Bukit Batok New Town | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 52        | 81     | 18.71%  |
| WDC                         | 25        | 47     | 8.99%   |
| Seagate                     | 23        | 28     | 8.27%   |
| SK hynix                    | 21        | 23     | 7.55%   |
| SanDisk                     | 21        | 29     | 7.55%   |
| Toshiba                     | 18        | 26     | 6.47%   |
| Unknown                     | 14        | 19     | 5.04%   |
| Intel                       | 13        | 15     | 4.68%   |
| Micron Technology           | 11        | 12     | 3.96%   |
| HGST                        | 9         | 13     | 3.24%   |
| KIOXIA                      | 7         | 7      | 2.52%   |
| Hitachi                     | 7         | 7      | 2.52%   |
| Kingston                    | 5         | 6      | 1.8%    |
| Apple                       | 5         | 5      | 1.8%    |
| Phison                      | 4         | 6      | 1.44%   |
| Crucial                     | 4         | 4      | 1.44%   |
| China                       | 3         | 3      | 1.08%   |
| Transcend                   | 2         | 3      | 0.72%   |
| SPCC                        | 2         | 2      | 0.72%   |
| Phison Electronics          | 2         | 2      | 0.72%   |
| Patriot                     | 2         | 2      | 0.72%   |
| LITEON                      | 2         | 3      | 0.72%   |
| Lexar                       | 2         | 2      | 0.72%   |
| Lenovo                      | 2         | 2      | 0.72%   |
| JMicron Technology          | 2         | 5      | 0.72%   |
| Hewlett-Packard             | 2         | 3      | 0.72%   |
| External                    | 2         | 2      | 0.72%   |
| A-DATA Technology           | 2         | 2      | 0.72%   |
| Yangtze Memory Technologies | 1         | 1      | 0.36%   |
| UMIS                        | 1         | 1      | 0.36%   |
| TO Exter                    | 1         | 1      | 0.36%   |
| Team                        | 1         | 1      | 0.36%   |
| Silicon Motion              | 1         | 1      | 0.36%   |
| OCZ                         | 1         | 1      | 0.36%   |
| INTEL SS                    | 1         | 2      | 0.36%   |
| Haizhide                    | 1         | 1      | 0.36%   |
| GALAX                       | 1         | 1      | 0.36%   |
| Fujitsu                     | 1         | 1      | 0.36%   |
| CT1000MX                    | 1         | 2      | 0.36%   |
| Corsair                     | 1         | 2      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 2.09%   |
| Unknown MMC Card  64GB                              | 4         | 1.39%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 1.39%   |
| Samsung NVMe SSD Drive 1024GB                       | 4         | 1.39%   |
| HGST HTS721010A9E630 1TB                            | 4         | 1.39%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 1.05%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 3         | 1.05%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 1.05%   |
| WDC WDS500G2X0C-00L350 500GB                        | 2         | 0.7%    |
| WDC WDS100T2X0C-00L350 1TB                          | 2         | 0.7%    |
| WDC WD7500BPVT-80HXZT3 752GB                        | 2         | 0.7%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.7%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 2         | 0.7%    |
| WDC PC SN720 SED SDAQNTW-1T00 1TB                   | 2         | 0.7%    |
| Unknown MMC Card  32GB                              | 2         | 0.7%    |
| Toshiba MK5055GSX 500GB                             | 2         | 0.7%    |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 2         | 0.7%    |
| SK hynix HFM512GDJTNG-8310A 512GB                   | 2         | 0.7%    |
| SK hynix HFM001TD3JX013N 1TB                        | 2         | 0.7%    |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 0.7%    |
| Seagate Expansion 1TB                               | 2         | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 2         | 0.7%    |
| SanDisk SSD PLUS 240GB                              | 2         | 0.7%    |
| SanDisk SD6SN1M128G1002 128GB SSD                   | 2         | 0.7%    |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.7%    |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.7%    |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.7%    |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.7%    |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.7%    |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.7%    |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 2         | 0.7%    |
| Samsung MZALQ512HALU-000L2 512GB                    | 2         | 0.7%    |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 0.7%    |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 0.7%    |
| KIOXIA KBG40ZNS128G NVMe 128GB                      | 2         | 0.7%    |
| JMicron Generic 240GB                               | 2         | 0.7%    |
| Intel SSDPEKNU512GZ 512GB                           | 2         | 0.7%    |
| Intel SSD 660P Series 512GB                         | 2         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 25     | 32.31%  |
| Toshiba             | 14        | 22     | 21.54%  |
| WDC                 | 11        | 15     | 16.92%  |
| HGST                | 9         | 13     | 13.85%  |
| Hitachi             | 7         | 7      | 10.77%  |
| Samsung Electronics | 1         | 3      | 1.54%   |
| Fujitsu             | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 46     | 32.89%  |
| SanDisk             | 12        | 19     | 15.79%  |
| Micron Technology   | 4         | 5      | 5.26%   |
| Apple               | 4         | 4      | 5.26%   |
| Crucial             | 3         | 3      | 3.95%   |
| China               | 3         | 3      | 3.95%   |
| WDC                 | 2         | 3      | 2.63%   |
| Transcend           | 2         | 3      | 2.63%   |
| SPCC                | 2         | 2      | 2.63%   |
| SK hynix            | 2         | 2      | 2.63%   |
| Patriot             | 2         | 2      | 2.63%   |
| LITEON              | 2         | 3      | 2.63%   |
| Kingston            | 2         | 3      | 2.63%   |
| External            | 2         | 2      | 2.63%   |
| Toshiba             | 1         | 1      | 1.32%   |
| TO Exter            | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 1      | 1.32%   |
| Lexar               | 1         | 1      | 1.32%   |
| Hewlett-Packard     | 1         | 2      | 1.32%   |
| Haizhide            | 1         | 1      | 1.32%   |
| GALAX               | 1         | 1      | 1.32%   |
| CT1000MX            | 1         | 2      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 113       | 161    | 43.8%   |
| SSD     | 71        | 111    | 27.52%  |
| HDD     | 62        | 87     | 24.03%  |
| MMC     | 11        | 16     | 4.26%   |
| Unknown | 1         | 1      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 113       | 154    | 45.38%  |
| SATA | 112       | 187    | 44.98%  |
| SAS  | 13        | 19     | 5.22%   |
| MMC  | 11        | 16     | 4.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 129    | 63.57%  |
| 0.51-1.0   | 44        | 65     | 34.11%  |
| 1.01-2.0   | 3         | 4      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 27.47%  |
| 251-500        | 56        | 24.03%  |
| 501-1000       | 42        | 18.03%  |
| 51-100         | 16        | 6.87%   |
| 1001-2000      | 15        | 6.44%   |
| 1-20           | 15        | 6.44%   |
| More than 3000 | 8         | 3.43%   |
| 21-50          | 8         | 3.43%   |
| Unknown        | 7         | 3%      |
| 2001-3000      | 2         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 92        | 38.66%  |
| 21-50          | 39        | 16.39%  |
| 101-250        | 36        | 15.13%  |
| 251-500        | 24        | 10.08%  |
| 51-100         | 22        | 9.24%   |
| 501-1000       | 11        | 4.62%   |
| Unknown        | 7         | 2.94%   |
| 1001-2000      | 4         | 1.68%   |
| 2001-3000      | 2         | 0.84%   |
| More than 3000 | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 12.5%   |
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 12.5%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 12.5%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 12.5%   |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 12.5%   |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 12.5%   |
| China SSD 128GB                    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Seagate | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| China   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Detected | 126       | 199    | 54.08%  |
| Works    | 99        | 168    | 42.49%  |
| Malfunc  | 8         | 9      | 3.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 49.26%  |
| Samsung Electronics          | 30        | 11.03%  |
| AMD                          | 23        | 8.46%   |
| SanDisk                      | 20        | 7.35%   |
| SK hynix                     | 19        | 6.99%   |
| Micron Technology            | 7         | 2.57%   |
| Phison Electronics           | 6         | 2.21%   |
| KIOXIA                       | 6         | 2.21%   |
| Toshiba America Info Systems | 5         | 1.84%   |
| ADATA Technology             | 4         | 1.47%   |
| Nvidia                       | 3         | 1.1%    |
| Kingston Technology Company  | 3         | 1.1%    |
| Silicon Motion               | 2         | 0.74%   |
| Shenzhen Longsys Electronics | 2         | 0.74%   |
| Seagate Technology           | 2         | 0.74%   |
| Lenovo                       | 2         | 0.74%   |
| Yangtze Memory Technologies  | 1         | 0.37%   |
| Union Memory (Shenzhen)      | 1         | 0.37%   |
| Micron/Crucial Technology    | 1         | 0.37%   |
| ASMedia Technology           | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 7.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 6.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 4.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 4.24%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 3.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 3.18%   |
| Intel SSD 660P Series                                                          | 7         | 2.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 2.12%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 2.12%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 2.12%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.77%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.77%   |
| Micron NVMe Storage Controller                                                 | 4         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.41%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.06%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.06%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.06%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.71%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.71%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.71%   |
| Samsung Electronics SATA controller                                            | 2         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.71%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 129       | 47.25%  |
| NVMe | 114       | 41.76%  |
| RAID | 21        | 7.69%   |
| IDE  | 9         | 3.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 80.73%  |
| AMD    | 42        | 19.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 4.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 4.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 3.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 3.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.29%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 2.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.29%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 2.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.38%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 3         | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.38%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.92%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.92%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.92%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.92%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.92%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.92%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 0.92%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.92%   |
| Intel 12th Gen Core i7-12650H                 | 2         | 0.92%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.92%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 0.92%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 64        | 29.36%  |
| Intel Core i5           | 45        | 20.64%  |
| Other                   | 25        | 11.47%  |
| AMD Ryzen 7             | 17        | 7.8%    |
| AMD Ryzen 5             | 11        | 5.05%   |
| Intel Core 2 Duo        | 10        | 4.59%   |
| Intel Celeron           | 9         | 4.13%   |
| Intel Core i3           | 5         | 2.29%   |
| Intel Xeon              | 4         | 1.83%   |
| Intel Pentium Silver    | 4         | 1.83%   |
| Intel Atom              | 4         | 1.83%   |
| AMD Ryzen 7 PRO         | 3         | 1.38%   |
| Intel Core m3           | 2         | 0.92%   |
| Intel Core i9           | 2         | 0.92%   |
| AMD Ryzen 9             | 2         | 0.92%   |
| AMD Ryzen 3             | 2         | 0.92%   |
| Intel Pentium Dual      | 1         | 0.46%   |
| Intel Core 2            | 1         | 0.46%   |
| AMD Turion 64 X2 Mobile | 1         | 0.46%   |
| AMD Ryzen 5 PRO         | 1         | 0.46%   |
| AMD PRO A10             | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD E1                  | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |
| AMD A6                  | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 89        | 40.83%  |
| 2      | 76        | 34.86%  |
| 8      | 28        | 12.84%  |
| 6      | 18        | 8.26%   |
| 10     | 3         | 1.38%   |
| 14     | 2         | 0.92%   |
| 1      | 2         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 218       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 81.82%  |
| 1      | 40        | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 215       | 98.62%  |
| 32-bit         | 2         | 0.92%   |
| Unknown        | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 19.82%  |
| 0x806ea    | 14        | 6.17%   |
| 0x806ec    | 13        | 5.73%   |
| 0x306a9    | 12        | 5.29%   |
| 0x206a7    | 12        | 5.29%   |
| 0x906ea    | 10        | 4.41%   |
| 0x0a50000c | 10        | 4.41%   |
| 0x806c1    | 9         | 3.96%   |
| 0x40651    | 7         | 3.08%   |
| 0x806e9    | 6         | 2.64%   |
| 0x806eb    | 5         | 2.2%    |
| 0x6fd      | 5         | 2.2%    |
| 0x306d4    | 5         | 2.2%    |
| 0x806d1    | 4         | 1.76%   |
| 0x506e3    | 4         | 1.76%   |
| 0x406e3    | 4         | 1.76%   |
| 0x1067a    | 4         | 1.76%   |
| 0x08108109 | 4         | 1.76%   |
| 0xa0652    | 3         | 1.32%   |
| 0x806c2    | 3         | 1.32%   |
| 0x40661    | 3         | 1.32%   |
| 0x306c3    | 3         | 1.32%   |
| 0x20655    | 3         | 1.32%   |
| 0x08600106 | 3         | 1.32%   |
| 0x906e9    | 2         | 0.88%   |
| 0x906c0    | 2         | 0.88%   |
| 0x906a3    | 2         | 0.88%   |
| 0x706e5    | 2         | 0.88%   |
| 0x706a8    | 2         | 0.88%   |
| 0x706a1    | 2         | 0.88%   |
| 0x406c3    | 2         | 0.88%   |
| 0x30678    | 2         | 0.88%   |
| 0x106c2    | 2         | 0.88%   |
| 0x0a404102 | 2         | 0.88%   |
| 0x0a404101 | 2         | 0.88%   |
| 0x08600103 | 2         | 0.88%   |
| 0x08108102 | 2         | 0.88%   |
| 0x906ed    | 1         | 0.44%   |
| 0x6f6      | 1         | 0.44%   |
| 0x506c9    | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 27.52%  |
| TigerLake        | 16        | 7.34%   |
| SandyBridge      | 15        | 6.88%   |
| Haswell          | 14        | 6.42%   |
| Zen 3            | 13        | 5.96%   |
| IvyBridge        | 12        | 5.5%    |
| Unknown          | 11        | 5.05%   |
| Zen+             | 9         | 4.13%   |
| Skylake          | 9         | 4.13%   |
| Zen 2            | 7         | 3.21%   |
| Icelake          | 7         | 3.21%   |
| Penryn           | 6         | 2.75%   |
| Core             | 6         | 2.75%   |
| Silvermont       | 5         | 2.29%   |
| Broadwell        | 5         | 2.29%   |
| Goldmont plus    | 4         | 1.83%   |
| CometLake        | 4         | 1.83%   |
| Westmere         | 3         | 1.38%   |
| Tremont          | 2         | 0.92%   |
| Excavator        | 2         | 0.92%   |
| Bonnell          | 2         | 0.92%   |
| Bobcat           | 2         | 0.92%   |
| K8 Hammer        | 1         | 0.46%   |
| Jaguar           | 1         | 0.46%   |
| Goldmont         | 1         | 0.46%   |
| Alderlake Hybrid | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 165       | 55.74%  |
| Nvidia | 85        | 28.72%  |
| AMD    | 46        | 15.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 17        | 5.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 15        | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 14        | 4.58%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 12        | 3.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 11        | 3.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 3.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 9         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 9         | 2.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 9         | 2.94%   |
| Intel HD Graphics 620                                                     | 7         | 2.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 7         | 2.29%   |
| AMD Renoir                                                                | 7         | 2.29%   |
| Nvidia GP108M [GeForce MX150]                                             | 5         | 1.63%   |
| Nvidia GP108BM [GeForce MX250]                                            | 5         | 1.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 5         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1.63%   |
| AMD Rembrandt [Radeon 680M]                                               | 5         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 1.31%   |
| Intel HD Graphics 5500                                                    | 4         | 1.31%   |
| Intel HD Graphics 530                                                     | 4         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 0.98%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 3         | 0.98%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 3         | 0.98%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 3         | 0.98%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 0.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 0.65%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                   | 2         | 0.65%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                              | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 44.29%  |
| Intel + Nvidia | 60        | 27.4%   |
| 1 x AMD        | 25        | 11.42%  |
| 1 x Nvidia     | 16        | 7.31%   |
| AMD + Nvidia   | 10        | 4.57%   |
| Intel + AMD    | 8         | 3.65%   |
| 2 x AMD        | 3         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 169       | 75.78%  |
| Proprietary | 48        | 21.52%  |
| Unknown     | 6         | 2.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 66.38%  |
| 1.01-2.0   | 30        | 13.1%   |
| 0.01-0.5   | 18        | 7.86%   |
| 3.01-4.0   | 15        | 6.55%   |
| 7.01-8.0   | 5         | 2.18%   |
| 0.51-1.0   | 4         | 1.75%   |
| 5.01-6.0   | 3         | 1.31%   |
| 2.01-3.0   | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 27.94%  |
| BOE                     | 31        | 12.55%  |
| LG Display              | 28        | 11.34%  |
| Samsung Electronics     | 24        | 9.72%   |
| Chimei Innolux          | 19        | 7.69%   |
| Dell                    | 15        | 6.07%   |
| Sharp                   | 9         | 3.64%   |
| Apple                   | 8         | 3.24%   |
| Philips                 | 6         | 2.43%   |
| Acer                    | 5         | 2.02%   |
| InfoVision              | 4         | 1.62%   |
| CSO                     | 4         | 1.62%   |
| Lenovo                  | 3         | 1.21%   |
| Goldstar                | 3         | 1.21%   |
| PANDA                   | 2         | 0.81%   |
| Mi                      | 2         | 0.81%   |
| LG Philips              | 2         | 0.81%   |
| Hewlett-Packard         | 2         | 0.81%   |
| Toshiba                 | 1         | 0.4%    |
| Tianma XM               | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| JDI                     | 1         | 0.4%    |
| EXP                     | 1         | 0.4%    |
| DENON                   | 1         | 0.4%    |
| CVT                     | 1         | 0.4%    |
| CPT                     | 1         | 0.4%    |
| Chi Mei Optoelectronics | 1         | 0.4%    |
| ASUSTek Computer        | 1         | 0.4%    |
| Ancor Communications    | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 4         | 1.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 1.61%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.2%    |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch        | 3         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.8%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.8%    |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.8%    |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.8%    |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch            | 2         | 0.8%    |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.8%    |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.8%    |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.8%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.8%    |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.4%    |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.4%    |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.4%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.4%    |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch  | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 119       | 52.19%  |
| 1366x768 (WXGA)   | 43        | 18.86%  |
| 3840x2160 (4K)    | 12        | 5.26%   |
| 1280x800 (WXGA)   | 10        | 4.39%   |
| 2560x1440 (QHD)   | 9         | 3.95%   |
| 2560x1600         | 6         | 2.63%   |
| 1920x1200 (WUXGA) | 6         | 2.63%   |
| 2880x1800         | 5         | 2.19%   |
| 3440x1440         | 3         | 1.32%   |
| 3840x2400         | 2         | 0.88%   |
| 3000x2000         | 2         | 0.88%   |
| 2240x1400         | 2         | 0.88%   |
| 1440x900 (WXGA+)  | 2         | 0.88%   |
| 1360x768          | 2         | 0.88%   |
| 3200x1800 (QHD+)  | 1         | 0.44%   |
| 3072x1920         | 1         | 0.44%   |
| 1600x900 (HD+)    | 1         | 0.44%   |
| 1280x1024 (SXGA)  | 1         | 0.44%   |
| 1024x600          | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 70        | 28.46%  |
| 13      | 57        | 23.17%  |
| 14      | 46        | 18.7%   |
| 27      | 10        | 4.07%   |
| 23      | 10        | 4.07%   |
| 12      | 10        | 4.07%   |
| 11      | 8         | 3.25%   |
| 24      | 7         | 2.85%   |
| 21      | 6         | 2.44%   |
| 16      | 5         | 2.03%   |
| 34      | 2         | 0.81%   |
| 32      | 2         | 0.81%   |
| 19      | 2         | 0.81%   |
| 18      | 2         | 0.81%   |
| 65      | 1         | 0.41%   |
| 52      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 35      | 1         | 0.41%   |
| 31      | 1         | 0.41%   |
| 17      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |
| 8       | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 58.2%   |
| 201-300     | 51        | 20.9%   |
| 501-600     | 25        | 10.25%  |
| 401-500     | 9         | 3.69%   |
| 351-400     | 6         | 2.46%   |
| 701-800     | 4         | 1.64%   |
| 801-900     | 2         | 0.82%   |
| 1001-1500   | 2         | 0.82%   |
| 601-700     | 1         | 0.41%   |
| 101-200     | 1         | 0.41%   |
| Unknown     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 171       | 80.66%  |
| 16/10 | 33        | 15.57%  |
| 3/2   | 3         | 1.42%   |
| 21/9  | 3         | 1.42%   |
| 5/4   | 1         | 0.47%   |
| 0.62  | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 75        | 30.61%  |
| 101-110        | 70        | 28.57%  |
| 71-80          | 26        | 10.61%  |
| 201-250        | 20        | 8.16%   |
| 61-70          | 10        | 4.08%   |
| 301-350        | 10        | 4.08%   |
| 51-60          | 8         | 3.27%   |
| 351-500        | 6         | 2.45%   |
| 111-120        | 5         | 2.04%   |
| 151-200        | 4         | 1.63%   |
| More than 1000 | 2         | 0.82%   |
| 141-150        | 2         | 0.82%   |
| 91-100         | 2         | 0.82%   |
| 41-50          | 1         | 0.41%   |
| 1-40           | 1         | 0.41%   |
| 121-130        | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 106       | 44.73%  |
| 101-120       | 42        | 17.72%  |
| 161-240       | 40        | 16.88%  |
| 51-100        | 30        | 12.66%  |
| More than 240 | 15        | 6.33%   |
| 1-50          | 3         | 1.27%   |
| Unknown       | 1         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 177       | 77.29%  |
| 2     | 41        | 17.9%   |
| 0     | 8         | 3.49%   |
| 3     | 3         | 1.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 133       | 42.22%  |
| Realtek Semiconductor    | 84        | 26.67%  |
| Qualcomm Atheros         | 42        | 13.33%  |
| Broadcom                 | 19        | 6.03%   |
| MediaTek                 | 9         | 2.86%   |
| ASIX Electronics         | 7         | 2.22%   |
| Marvell Technology Group | 3         | 0.95%   |
| Broadcom Limited         | 3         | 0.95%   |
| Qualcomm                 | 2         | 0.63%   |
| Sierra Wireless          | 1         | 0.32%   |
| Samsung Electronics      | 1         | 0.32%   |
| Ralink Technology        | 1         | 0.32%   |
| Ralink                   | 1         | 0.32%   |
| Nvidia                   | 1         | 0.32%   |
| MosChip Semiconductor    | 1         | 0.32%   |
| Linksys                  | 1         | 0.32%   |
| Lenovo                   | 1         | 0.32%   |
| Hewlett-Packard          | 1         | 0.32%   |
| Google                   | 1         | 0.32%   |
| Dell                     | 1         | 0.32%   |
| D-Link                   | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 13.67%  |
| Intel Wi-Fi 6 AX200                                               | 17        | 4.56%   |
| Intel Wi-Fi 6 AX201                                               | 15        | 4.02%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.22%   |
| Intel Wireless 7265                                               | 12        | 3.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.14%   |
| Intel Wireless 7260                                               | 8         | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.34%   |
| Intel Wireless 3165                                               | 5         | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.8%    |
| Intel Wireless-AC 9260                                            | 3         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.54%   |
| Realtek 802.11ac NIC                                              | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 131       | 59.55%  |
| Qualcomm Atheros      | 37        | 16.82%  |
| Realtek Semiconductor | 20        | 9.09%   |
| Broadcom              | 13        | 5.91%   |
| MediaTek              | 9         | 4.09%   |
| Qualcomm              | 2         | 0.91%   |
| Broadcom Limited      | 2         | 0.91%   |
| Sierra Wireless       | 1         | 0.45%   |
| Ralink Technology     | 1         | 0.45%   |
| Ralink                | 1         | 0.45%   |
| Hewlett-Packard       | 1         | 0.45%   |
| Dell                  | 1         | 0.45%   |
| D-Link                | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17        | 7.66%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 6.76%   |
| Intel Wireless 8265 / 8275                                              | 12        | 5.41%   |
| Intel Wireless 7265                                                     | 12        | 5.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 4.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 4.05%   |
| Intel Wireless 7260                                                     | 8         | 3.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 3.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 3.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.25%   |
| Intel Wireless 3165                                                     | 5         | 2.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.35%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.9%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.9%    |
| Intel Wireless 8260                                                     | 2         | 0.9%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.9%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.9%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 48.32%  |
| Intel                    | 39        | 26.17%  |
| Qualcomm Atheros         | 10        | 6.71%   |
| Broadcom                 | 10        | 6.71%   |
| ASIX Electronics         | 7         | 4.7%    |
| Marvell Technology Group | 3         | 2.01%   |
| Samsung Electronics      | 1         | 0.67%   |
| Nvidia                   | 1         | 0.67%   |
| MosChip Semiconductor    | 1         | 0.67%   |
| Linksys                  | 1         | 0.67%   |
| Lenovo                   | 1         | 0.67%   |
| Google                   | 1         | 0.67%   |
| Broadcom Limited         | 1         | 0.67%   |
| Apple                    | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 51        | 33.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 6.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 5.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.64%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 4.64%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 3.31%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.99%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.99%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.32%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.32%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.32%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.32%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.32%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.66%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.66%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.66%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.66%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.66%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.66%   |
| Linksys Gigabit Ethernet Adapter                                               | 1         | 0.66%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 59.83%  |
| Ethernet | 143       | 40.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 81.28%  |
| Ethernet | 44        | 18.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 121       | 55.25%  |
| 1     | 95        | 43.38%  |
| 3     | 2         | 0.91%   |
| 0     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 200       | 91.74%  |
| Yes  | 18        | 8.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 108       | 57.75%  |
| IMC Networks                    | 13        | 6.95%   |
| Qualcomm Atheros Communications | 12        | 6.42%   |
| Foxconn / Hon Hai               | 12        | 6.42%   |
| Broadcom                        | 9         | 4.81%   |
| Lite-On Technology              | 8         | 4.28%   |
| Apple                           | 7         | 3.74%   |
| Realtek Semiconductor           | 6         | 3.21%   |
| MediaTek                        | 2         | 1.07%   |
| Cambridge Silicon Radio         | 2         | 1.07%   |
| USI                             | 1         | 0.53%   |
| Toshiba                         | 1         | 0.53%   |
| Ralink Technology               | 1         | 0.53%   |
| Foxconn International           | 1         | 0.53%   |
| Dell                            | 1         | 0.53%   |
| Chicony Electronics             | 1         | 0.53%   |
| Askey Computer                  | 1         | 0.53%   |
| Alps Electric                   | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 18.72%  |
| Intel AX201 Bluetooth                               | 31        | 16.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 10.7%   |
| Intel AX200 Bluetooth                               | 15        | 8.02%   |
| Realtek Bluetooth Radio                             | 5         | 2.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.67%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.67%   |
| Apple Bluetooth Host Controller                     | 5         | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.14%   |
| IMC Networks Bluetooth Device                       | 4         | 2.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.14%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 2.14%   |
| IMC Networks Wireless_Device                        | 3         | 1.6%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.6%    |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.6%    |
| MediaTek Wireless_Device                            | 2         | 1.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.07%   |
| Lite-On Bluetooth Radio                             | 2         | 1.07%   |
| Lite-On Bluetooth Device                            | 2         | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.07%   |
| Intel Bluetooth Device                              | 2         | 1.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.07%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.07%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.07%   |
| USI Bluetooth Device                                | 1         | 0.53%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.53%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.53%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.53%   |
| Intel AX210 Bluetooth                               | 1         | 0.53%   |
| IMC Networks Bluetooth module                       | 1         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.53%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 171       | 63.81%  |
| AMD                 | 42        | 15.67%  |
| Nvidia              | 40        | 14.93%  |
| Plantronics         | 2         | 0.75%   |
| Lenovo              | 2         | 0.75%   |
| Kingston Technology | 2         | 0.75%   |
| Apple               | 2         | 0.75%   |
| Razer USA           | 1         | 0.37%   |
| Logitech            | 1         | 0.37%   |
| JBL                 | 1         | 0.37%   |
| GN Netcom           | 1         | 0.37%   |
| Cooler Master       | 1         | 0.37%   |
| Conexant Systems    | 1         | 0.37%   |
| ASUSTek Computer    | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 36        | 11.18%  |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 9.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 4.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 4.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 4.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 2.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.17%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.55%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.24%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.24%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.93%   |
| Nvidia Audio device                                                        | 3         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.93%   |
| Plantronics Blackwire 3225 Series                                          | 2         | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.62%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.62%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 44        | 27.67%  |
| Samsung Electronics | 40        | 25.16%  |
| Micron Technology   | 23        | 14.47%  |
| Kingston            | 12        | 7.55%   |
| Unknown             | 10        | 6.29%   |
| Crucial             | 9         | 5.66%   |
| Ramaxel Technology  | 4         | 2.52%   |
| Transcend           | 3         | 1.89%   |
| A-DATA Technology   | 3         | 1.89%   |
| Nanya Technology    | 2         | 1.26%   |
| Elpida              | 2         | 1.26%   |
| V-GeN               | 1         | 0.63%   |
| Unknown (ABCD)      | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Lexar               | 1         | 0.63%   |
| Corsair             | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.4%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 1.8%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.8%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.8%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.2%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.2%    |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 1.2%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.2%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.2%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.2%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.2%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.2%    |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 1.2%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.2%    |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 2         | 1.2%    |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.6%    |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.6%    |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s            | 1         | 0.6%    |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1333MT/s              | 1         | 0.6%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.6%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 65        | 50.39%  |
| DDR3   | 35        | 27.13%  |
| LPDDR3 | 12        | 9.3%    |
| LPDDR4 | 11        | 8.53%   |
| DDR5   | 3         | 2.33%   |
| LPDDR5 | 2         | 1.55%   |
| SDRAM  | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 101       | 78.29%  |
| Row Of Chips | 25        | 19.38%  |
| Chip         | 2         | 1.55%   |
| Unknown      | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 40%     |
| 4096  | 43        | 28.67%  |
| 16384 | 29        | 19.33%  |
| 2048  | 9         | 6%      |
| 32768 | 7         | 4.67%   |
| 1024  | 2         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 31        | 21.99%  |
| 1600    | 27        | 19.15%  |
| 2667    | 25        | 17.73%  |
| 2400    | 10        | 7.09%   |
| 4267    | 9         | 6.38%   |
| 2133    | 9         | 6.38%   |
| 1334    | 6         | 4.26%   |
| 1333    | 5         | 3.55%   |
| 4800    | 4         | 2.84%   |
| 1867    | 3         | 2.13%   |
| 6400    | 2         | 1.42%   |
| 3266    | 2         | 1.42%   |
| 1067    | 2         | 1.42%   |
| Unknown | 2         | 1.42%   |
| 8400    | 1         | 0.71%   |
| 4199    | 1         | 0.71%   |
| 1200    | 1         | 0.71%   |
| 800     | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 50        | 25.64%  |
| IMC Networks                           | 31        | 15.9%   |
| Microdia                               | 27        | 13.85%  |
| Realtek Semiconductor                  | 16        | 8.21%   |
| Sunplus Innovation Technology          | 13        | 6.67%   |
| Suyin                                  | 7         | 3.59%   |
| Bison Electronics                      | 6         | 3.08%   |
| Acer                                   | 6         | 3.08%   |
| Samsung Electronics                    | 5         | 2.56%   |
| Syntek                                 | 4         | 2.05%   |
| Lite-On Technology                     | 4         | 2.05%   |
| Apple                                  | 4         | 2.05%   |
| Logitech                               | 3         | 1.54%   |
| Silicon Motion                         | 2         | 1.03%   |
| Ricoh                                  | 2         | 1.03%   |
| OmniVision Technologies                | 2         | 1.03%   |
| Luxvisions Innotech Limited            | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.03%   |
| SunplusIT                              | 1         | 0.51%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.51%   |
| Sonix Technology                       | 1         | 0.51%   |
| Quanta                                 | 1         | 0.51%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.51%   |
| Magic Control Technology               | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Intel                                  | 1         | 0.51%   |
| Alcor Micro                            | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 18        | 9.18%   |
| Chicony Integrated Camera                        | 10        | 5.1%    |
| Chicony HD WebCam                                | 10        | 5.1%    |
| IMC Networks USB2.0 HD UVC WebCam                | 9         | 4.59%   |
| IMC Networks Integrated Camera                   | 9         | 4.59%   |
| Realtek Integrated_Webcam_HD                     | 7         | 3.57%   |
| Sunplus Integrated_Webcam_HD                     | 6         | 3.06%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 3.06%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 2.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 4         | 2.04%   |
| Chicony HP HD Camera                             | 4         | 2.04%   |
| Acer Integrated Camera                           | 4         | 2.04%   |
| Syntek Integrated Camera                         | 3         | 1.53%   |
| Lite-On Integrated Camera                        | 3         | 1.53%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 1.53%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.53%   |
| Apple FaceTime HD Camera                         | 3         | 1.53%   |
| Realtek Integrated Webcam_HD                     | 2         | 1.02%   |
| Realtek Asus 2.0 USB Webcam                      | 2         | 1.02%   |
| OmniVision OV2640 Webcam                         | 2         | 1.02%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 1.02%   |
| Microdia Integrated Camera                       | 2         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera    | 2         | 1.02%   |
| IMC Networks Lenovo EasyCamera                   | 2         | 1.02%   |
| Chicony VGA Webcam                               | 2         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 1.02%   |
| Chicony USB2.0 Camera                            | 2         | 1.02%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 1.02%   |
| Chicony HD User Facing                           | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 1.02%   |
| Bison Integrated Camera                          | 2         | 1.02%   |
| Bison BisonCam, NB Pro                           | 2         | 1.02%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.51%   |
| Suyin UVC HD Webcam                              | 1         | 0.51%   |
| Suyin Laptop_Integrated_Webcam_HD                | 1         | 0.51%   |
| Suyin HD WebCam                                  | 1         | 0.51%   |
| Suyin Asus Integrated Webcam                     | 1         | 0.51%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 0.51%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.51%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 14        | 23.73%  |
| Validity Sensors                   | 11        | 18.64%  |
| Shenzhen Goodix Technology         | 8         | 13.56%  |
| LighTuning Technology              | 7         | 11.86%  |
| Upek                               | 6         | 10.17%  |
| Elan Microelectronics              | 6         | 10.17%  |
| AuthenTec                          | 6         | 10.17%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 13.56%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 11.86%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 10.17%  |
| Elan ELAN:Fingerprint                                                      | 4         | 6.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.08%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 5.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.08%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.39%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.39%   |
| AuthenTec AES2810                                                          | 2         | 3.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.69%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.69%   |
| Unknown                                                                    | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 87.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 25%     |
| Broadcom 5880                                  | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 129       | 55.84%  |
| 1     | 75        | 32.47%  |
| 2     | 22        | 9.52%   |
| 3     | 3         | 1.3%    |
| 5     | 1         | 0.43%   |
| 4     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 41.35%  |
| Graphics card            | 33        | 24.81%  |
| Net/wireless             | 13        | 9.77%   |
| Multimedia controller    | 9         | 6.77%   |
| Chipcard                 | 7         | 5.26%   |
| Camera                   | 6         | 4.51%   |
| Communication controller | 3         | 2.26%   |
| Net/ethernet             | 2         | 1.5%    |
| Wireless                 | 1         | 0.75%   |
| Storage/raid             | 1         | 0.75%   |
| Sound                    | 1         | 0.75%   |
| Firewire controller      | 1         | 0.75%   |
| Bluetooth                | 1         | 0.75%   |

