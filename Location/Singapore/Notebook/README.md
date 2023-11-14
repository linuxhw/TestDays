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

Total: 384

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | K401UB                      | [3bc894aa34](https://linux-hardware.org/?probe=3bc894aa34) | Nov 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [d690fa8f27](https://linux-hardware.org/?probe=d690fa8f27) | Oct 29, 2023 |
| ASUSTek       | PRIME X570-P                | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| ASUSTek       | UX310UQK                    | [9c8029cd07](https://linux-hardware.org/?probe=9c8029cd07) | Oct 17, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire 5750                 | [89dc9a349f](https://linux-hardware.org/?probe=89dc9a349f) | Sep 26, 2023 |
| HP            | EliteBook 725 G4            | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| EUROCOM       | RAPTOR X17                  | [bbd769440e](https://linux-hardware.org/?probe=bbd769440e) | Sep 21, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [fb5af8d0d8](https://linux-hardware.org/?probe=fb5af8d0d8) | Sep 19, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [c75315410e](https://linux-hardware.org/?probe=c75315410e) | Sep 19, 2023 |
| EUROCOM       | RAPTOR X17                  | [15e2ca1220](https://linux-hardware.org/?probe=15e2ca1220) | Sep 19, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [032cd70e81](https://linux-hardware.org/?probe=032cd70e81) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [235e80247e](https://linux-hardware.org/?probe=235e80247e) | Sep 05, 2023 |
| ASUSTek       | K401UB                      | [14a7bf0f59](https://linux-hardware.org/?probe=14a7bf0f59) | Aug 28, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | GP66 Leopard 10UE           | [54eaec1cae](https://linux-hardware.org/?probe=54eaec1cae) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [70062471e2](https://linux-hardware.org/?probe=70062471e2) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| MSI           | GP66 Leopard 10UE           | [9f6cf770d1](https://linux-hardware.org/?probe=9f6cf770d1) | Aug 18, 2023 |
| Beelink       | Gemini X                    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| Lenovo        | ThinkPad X250 20CL0007SG    | [f30d61c851](https://linux-hardware.org/?probe=f30d61c851) | Aug 01, 2023 |
| ASUSTek       | PRIME X570-P                | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | [5bc4bf8334](https://linux-hardware.org/?probe=5bc4bf8334) | Jul 28, 2023 |
| Apple         | MacBookPro11,5              | [57e295e5cf](https://linux-hardware.org/?probe=57e295e5cf) | Jul 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| ASUSTek       | K46CB                       | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [dfe9381867](https://linux-hardware.org/?probe=dfe9381867) | Jul 14, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop X415... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
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
| Ubuntu 20.04                 | 48        | 18.18%  |
| Ubuntu 22.04                 | 20        | 7.58%   |
| Ubuntu 18.04                 | 19        | 7.2%    |
| Fedora 33                    | 10        | 3.79%   |
| Arch Rolling                 | 10        | 3.79%   |
| Pop!_OS 22.04                | 7         | 2.65%   |
| Fedora 38                    | 7         | 2.65%   |
| Pop!_OS 20.04                | 5         | 1.89%   |
| Fedora 37                    | 5         | 1.89%   |
| Arch                         | 5         | 1.89%   |
| Zorin 16                     | 4         | 1.52%   |
| OpenMandriva 23.01           | 4         | 1.52%   |
| Linux Mint 21                | 4         | 1.52%   |
| Debian Testing               | 4         | 1.52%   |
| Debian 11                    | 4         | 1.52%   |
| ArcoLinux Rolling            | 4         | 1.52%   |
| Xubuntu 20.04                | 3         | 1.14%   |
| Linux Mint 21.1              | 3         | 1.14%   |
| Linux Mint 20                | 3         | 1.14%   |
| Kubuntu 22.04                | 3         | 1.14%   |
| KDE neon 22.04               | 3         | 1.14%   |
| Fedora 36                    | 3         | 1.14%   |
| Fedora 32                    | 3         | 1.14%   |
| EndeavourOS Rolling          | 3         | 1.14%   |
| Elementary 6.1               | 3         | 1.14%   |
| Debian 12                    | 3         | 1.14%   |
| Zorin 15                     | 2         | 0.76%   |
| Ubuntu 21.10                 | 2         | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.76%   |
| OpenMandriva 4.3             | 2         | 0.76%   |
| OpenMandriva 23.03           | 2         | 0.76%   |
| Manjaro 20.1                 | 2         | 0.76%   |
| Manjaro                      | 2         | 0.76%   |
| Linux Mint 21.2              | 2         | 0.76%   |
| Kubuntu 20.10                | 2         | 0.76%   |
| Gentoo 2.6                   | 2         | 0.76%   |
| Garuda Linux Soaring         | 2         | 0.76%   |
| Fedora 35                    | 2         | 0.76%   |
| Fedora 34                    | 2         | 0.76%   |
| Fedora 31                    | 2         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 94        | 37.3%   |
| Fedora        | 27        | 10.71%  |
| Pop!_OS       | 15        | 5.95%   |
| Debian        | 15        | 5.95%   |
| Arch          | 14        | 5.56%   |
| Linux Mint    | 13        | 5.16%   |
| OpenMandriva  | 11        | 4.37%   |
| Zorin         | 6         | 2.38%   |
| Manjaro       | 6         | 2.38%   |
| Kubuntu       | 6         | 2.38%   |
| Xubuntu       | 4         | 1.59%   |
| KDE neon      | 4         | 1.59%   |
| ArcoLinux     | 4         | 1.59%   |
| EndeavourOS   | 3         | 1.19%   |
| Elementary    | 3         | 1.19%   |
| Ubuntu Unity  | 2         | 0.79%   |
| Ubuntu Budgie | 2         | 0.79%   |
| ROSA          | 2         | 0.79%   |
| RHEL          | 2         | 0.79%   |
| openSUSE      | 2         | 0.79%   |
| Lubuntu       | 2         | 0.79%   |
| Kali          | 2         | 0.79%   |
| Gentoo        | 2         | 0.79%   |
| Garuda Linux  | 2         | 0.79%   |
| Endless       | 2         | 0.79%   |
| Clear Linux   | 2         | 0.79%   |
| Q4OS          | 1         | 0.4%    |
| NixOS         | 1         | 0.4%    |
| MX            | 1         | 0.4%    |
| LMDE          | 1         | 0.4%    |
| Deepin        | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.0-56-generic       | 6         | 2.01%   |
| 5.4.0-48-generic        | 5         | 1.68%   |
| 5.15.0-46-generic       | 5         | 1.68%   |
| 6.1.1-desktop-1omv2290  | 4         | 1.34%   |
| 5.9.8-200.fc33.x86_64   | 4         | 1.34%   |
| 5.4.0-42-generic        | 4         | 1.34%   |
| 5.4.0-40-generic        | 4         | 1.34%   |
| 5.3.0-62-generic        | 4         | 1.34%   |
| 5.11.0-43-generic       | 4         | 1.34%   |
| 6.2.15-300.fc38.x86_64  | 3         | 1.01%   |
| 6.2.0-26-generic        | 3         | 1.01%   |
| 5.4.0-65-generic        | 3         | 1.01%   |
| 5.4.0-52-generic        | 3         | 1.01%   |
| 5.4.0-47-generic        | 3         | 1.01%   |
| 5.4.0-37-generic        | 3         | 1.01%   |
| 5.4.0-29-generic        | 3         | 1.01%   |
| 5.15.0-41-generic       | 3         | 1.01%   |
| 5.13.0-28-generic       | 3         | 1.01%   |
| 5.11.0-38-generic       | 3         | 1.01%   |
| 6.4.6-76060406-generic  | 2         | 0.67%   |
| 6.3.8-200.fc38.x86_64   | 2         | 0.67%   |
| 6.2.6-desktop-1omv2390  | 2         | 0.67%   |
| 6.2.10-300.fc38.x86_64  | 2         | 0.67%   |
| 6.2.0-32-generic        | 2         | 0.67%   |
| 6.2.0-20-generic        | 2         | 0.67%   |
| 6.1.14-200.fc37.x86_64  | 2         | 0.67%   |
| 6.0.6-76060006-generic  | 2         | 0.67%   |
| 5.4.5-050405-generic    | 2         | 0.67%   |
| 5.4.0-7634-generic      | 2         | 0.67%   |
| 5.4.0-31-generic        | 2         | 0.67%   |
| 5.4.0-26-generic        | 2         | 0.67%   |
| 5.19.0-40-generic       | 2         | 0.67%   |
| 5.18.0-3-amd64          | 2         | 0.67%   |
| 5.18.0-2-amd64          | 2         | 0.67%   |
| 5.17.5-76051705-generic | 2         | 0.67%   |
| 5.16.7-desktop-1omv4003 | 2         | 0.67%   |
| 5.15.0-67-generic       | 2         | 0.67%   |
| 5.15.0-58-generic       | 2         | 0.67%   |
| 5.15.0-48-generic       | 2         | 0.67%   |
| 5.15.0-47-generic       | 2         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 13.78%  |
| 5.15.0  | 34        | 12.01%  |
| 5.11.0  | 13        | 4.59%   |
| 5.8.0   | 11        | 3.89%   |
| 5.13.0  | 10        | 3.53%   |
| 5.19.0  | 9         | 3.18%   |
| 6.2.0   | 7         | 2.47%   |
| 5.3.0   | 7         | 2.47%   |
| 4.18.0  | 7         | 2.47%   |
| 4.15.0  | 7         | 2.47%   |
| 5.18.0  | 6         | 2.12%   |
| 6.1.0   | 5         | 1.77%   |
| 5.10.0  | 5         | 1.77%   |
| 6.1.1   | 4         | 1.41%   |
| 5.9.8   | 4         | 1.41%   |
| 5.0.0   | 4         | 1.41%   |
| 6.3.8   | 3         | 1.06%   |
| 6.2.15  | 3         | 1.06%   |
| 6.2.10  | 3         | 1.06%   |
| 6.4.6   | 2         | 0.71%   |
| 6.3.5   | 2         | 0.71%   |
| 6.2.6   | 2         | 0.71%   |
| 6.1.14  | 2         | 0.71%   |
| 6.0.7   | 2         | 0.71%   |
| 6.0.6   | 2         | 0.71%   |
| 6.0.0   | 2         | 0.71%   |
| 5.4.5   | 2         | 0.71%   |
| 5.19.13 | 2         | 0.71%   |
| 5.17.5  | 2         | 0.71%   |
| 5.16.7  | 2         | 0.71%   |
| 5.13.13 | 2         | 0.71%   |
| 4.19.0  | 2         | 0.71%   |
| 6.5.9   | 1         | 0.35%   |
| 6.5.3   | 1         | 0.35%   |
| 6.4.8   | 1         | 0.35%   |
| 6.4.7   | 1         | 0.35%   |
| 6.4.15  | 1         | 0.35%   |
| 6.4.10  | 1         | 0.35%   |
| 6.3.3   | 1         | 0.35%   |
| 6.3.12  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 46        | 16.85%  |
| 5.15    | 39        | 14.29%  |
| 5.8     | 17        | 6.23%   |
| 5.13    | 16        | 5.86%   |
| 5.11    | 14        | 5.13%   |
| 6.2     | 13        | 4.76%   |
| 6.1     | 12        | 4.4%    |
| 5.19    | 12        | 4.4%    |
| 5.10    | 11        | 4.03%   |
| 5.18    | 10        | 3.66%   |
| 6.0     | 8         | 2.93%   |
| 6.3     | 7         | 2.56%   |
| 5.9     | 7         | 2.56%   |
| 5.3     | 7         | 2.56%   |
| 4.18    | 7         | 2.56%   |
| 4.15    | 7         | 2.56%   |
| 6.4     | 6         | 2.2%    |
| 5.16    | 6         | 2.2%    |
| 5.0     | 5         | 1.83%   |
| 5.6     | 4         | 1.47%   |
| 5.17    | 4         | 1.47%   |
| 5.12    | 3         | 1.1%    |
| 4.19    | 3         | 1.1%    |
| 6.5     | 2         | 0.73%   |
| 5.5     | 2         | 0.73%   |
| 5.7     | 1         | 0.37%   |
| 5.14    | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |
| 4.16    | 1         | 0.37%   |
| 3.10    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 240       | 99.17%  |
| i686   | 2         | 0.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 143       | 56.52%  |
| KDE5            | 39        | 15.42%  |
| Unknown         | 22        | 8.7%    |
| X-Cinnamon      | 14        | 5.53%   |
| XFCE            | 10        | 3.95%   |
| KDE             | 5         | 1.98%   |
| Cinnamon        | 4         | 1.58%   |
| Pantheon        | 3         | 1.19%   |
| LXQt            | 3         | 1.19%   |
| Unity           | 2         | 0.79%   |
| Budgie          | 2         | 0.79%   |
| MATE            | 1         | 0.4%    |
| KDE4            | 1         | 0.4%    |
| i3              | 1         | 0.4%    |
| Hyprland        | 1         | 0.4%    |
| GNOME Flashback | 1         | 0.4%    |
| GNOME Classic   | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 180       | 71.15%  |
| Wayland | 52        | 20.55%  |
| Unknown | 13        | 5.14%   |
| Tty     | 8         | 3.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 42.69%  |
| GDM     | 44        | 17.39%  |
| GDM3    | 43        | 17%     |
| SDDM    | 35        | 13.83%  |
| LightDM | 18        | 7.11%   |
| TDM     | 4         | 1.58%   |
| KDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_SG   | 101       | 40.73%  |
| en_US   | 94        | 37.9%   |
| Unknown | 17        | 6.85%   |
| zh_CN   | 9         | 3.63%   |
| en_IN   | 6         | 2.42%   |
| C       | 6         | 2.42%   |
| en_GB   | 4         | 1.61%   |
| en_PH   | 3         | 1.21%   |
| de_DE   | 3         | 1.21%   |
| en_AU   | 2         | 0.81%   |
| zh_SG   | 1         | 0.4%    |
| ru_UA   | 1         | 0.4%    |
| en_IE   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 173       | 70.33%  |
| BIOS | 73        | 29.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 191       | 77.64%  |
| Btrfs   | 27        | 10.98%  |
| Overlay | 11        | 4.47%   |
| Unknown | 7         | 2.85%   |
| Xfs     | 4         | 1.63%   |
| Tmpfs   | 4         | 1.63%   |
| Zfs     | 2         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 123       | 50.2%   |
| Unknown | 114       | 46.53%  |
| MBR     | 8         | 3.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 88.71%  |
| Yes       | 28        | 11.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 62.04%  |
| Yes       | 93        | 37.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 66        | 27.27%  |
| Dell                   | 48        | 19.83%  |
| ASUSTek Computer       | 40        | 16.53%  |
| Acer                   | 29        | 11.98%  |
| Hewlett-Packard        | 13        | 5.37%   |
| Apple                  | 10        | 4.13%   |
| Sony                   | 5         | 2.07%   |
| MSI                    | 5         | 2.07%   |
| Toshiba                | 2         | 0.83%   |
| Timi                   | 2         | 0.83%   |
| Samsung Electronics    | 2         | 0.83%   |
| HUAWEI                 | 2         | 0.83%   |
| Fujitsu                | 2         | 0.83%   |
| Foxconn                | 2         | 0.83%   |
| Aftershock             | 2         | 0.83%   |
| Unknown                | 2         | 0.83%   |
| TUXEDO                 | 1         | 0.41%   |
| Razer                  | 1         | 0.41%   |
| Notebook               | 1         | 0.41%   |
| MECHREVO               | 1         | 0.41%   |
| Google                 | 1         | 0.41%   |
| EUROCOM                | 1         | 0.41%   |
| COPELION INTERNATIONAL | 1         | 0.41%   |
| Beelink                | 1         | 0.41%   |
| AZW                    | 1         | 0.41%   |
| AMI                    | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron 15 5510                                 | 3         | 1.24%   |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.83%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.83%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.83%   |
| HP Compaq 6510b                                       | 2         | 0.83%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.83%   |
| Dell XPS 13 9310                                      | 2         | 0.83%   |
| Dell XPS 13 7390                                      | 2         | 0.83%   |
| Dell Latitude 3320                                    | 2         | 0.83%   |
| Dell Latitude 3120                                    | 2         | 0.83%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 0.83%   |
| ASUS T300LA                                           | 2         | 0.83%   |
| ASUS K45VM                                            | 2         | 0.83%   |
| Apple MacBookPro8,1                                   | 2         | 0.83%   |
| Apple MacBookPro11,5                                  | 2         | 0.83%   |
| Acer Swift SF314-57G                                  | 2         | 0.83%   |
| Acer ConceptD CN715-71                                | 2         | 0.83%   |
| Unknown                                               | 2         | 0.83%   |
| TUXEDO Stellaris Intel Gen5                           | 1         | 0.41%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.41%   |
| Toshiba PORTEGE R930                                  | 1         | 0.41%   |
| Timi TM1701                                           | 1         | 0.41%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.41%   |
| Sony VPCSB36FG                                        | 1         | 0.41%   |
| Sony VPCCA15FG                                        | 1         | 0.41%   |
| Sony VGN-CR32G_W                                      | 1         | 0.41%   |
| Sony SVF1531V8CW                                      | 1         | 0.41%   |
| Sony SVE11116FGW                                      | 1         | 0.41%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.41%   |
| Samsung 305U1A                                        | 1         | 0.41%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.41%   |
| Notebook P65_P67SE                                    | 1         | 0.41%   |
| MSI Pulse GL66 11UGK                                  | 1         | 0.41%   |
| MSI Modern 14 B5M                                     | 1         | 0.41%   |
| MSI GP66 Leopard 10UE                                 | 1         | 0.41%   |
| MSI GE63VR 7RE                                        | 1         | 0.41%   |
| MSI GE62VR 6RF                                        | 1         | 0.41%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.41%   |
| Lenovo Yoga Slim 7 proX 14ARH7 82TL                   | 1         | 0.41%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 35        | 14.46%  |
| Dell Inspiron      | 18        | 7.44%   |
| Acer Aspire        | 15        | 6.2%    |
| Dell Latitude      | 13        | 5.37%   |
| Lenovo IdeaPad     | 12        | 4.96%   |
| ASUS VivoBook      | 12        | 4.96%   |
| Dell XPS           | 10        | 4.13%   |
| Lenovo Legion      | 9         | 3.72%   |
| Acer Swift         | 8         | 3.31%   |
| Lenovo Yoga        | 5         | 2.07%   |
| Dell Precision     | 5         | 2.07%   |
| ASUS ZenBook       | 5         | 2.07%   |
| HP Pavilion        | 4         | 1.65%   |
| Apple MacBookPro11 | 4         | 1.65%   |
| HP ZBook           | 3         | 1.24%   |
| HP EliteBook       | 3         | 1.24%   |
| Toshiba PORTEGE    | 2         | 0.83%   |
| HP Compaq          | 2         | 0.83%   |
| Fujitsu LIFEBOOK   | 2         | 0.83%   |
| Foxconn Kangaroo   | 2         | 0.83%   |
| ASUS TUF           | 2         | 0.83%   |
| ASUS T300LA        | 2         | 0.83%   |
| ASUS ROG           | 2         | 0.83%   |
| ASUS K45VM         | 2         | 0.83%   |
| ASUS ASUS          | 2         | 0.83%   |
| Apple MacBookPro8  | 2         | 0.83%   |
| Acer Predator      | 2         | 0.83%   |
| Acer ConceptD      | 2         | 0.83%   |
| Unknown            | 2         | 0.83%   |
| TUXEDO Stellaris   | 1         | 0.41%   |
| Timi TM1701        | 1         | 0.41%   |
| Timi Redmi         | 1         | 0.41%   |
| Sony VPCSB36FG     | 1         | 0.41%   |
| Sony VPCCA15FG     | 1         | 0.41%   |
| Sony VGN-CR32G     | 1         | 0.41%   |
| Sony SVF1531V8CW   | 1         | 0.41%   |
| Sony SVE11116FGW   | 1         | 0.41%   |
| Samsung RF510      | 1         | 0.41%   |
| Samsung 305U1A     | 1         | 0.41%   |
| Razer Blade        | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 33        | 13.64%  |
| 2019 | 33        | 13.64%  |
| 2020 | 24        | 9.92%   |
| 2018 | 23        | 9.5%    |
| 2022 | 18        | 7.44%   |
| 2011 | 17        | 7.02%   |
| 2017 | 14        | 5.79%   |
| 2016 | 13        | 5.37%   |
| 2012 | 13        | 5.37%   |
| 2015 | 12        | 4.96%   |
| 2014 | 11        | 4.55%   |
| 2013 | 9         | 3.72%   |
| 2010 | 5         | 2.07%   |
| 2008 | 5         | 2.07%   |
| 2007 | 5         | 2.07%   |
| 2023 | 4         | 1.65%   |
| 2009 | 3         | 1.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 242       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 204       | 83.61%  |
| Enabled  | 40        | 16.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 241       | 99.59%  |
| Yes  | 1         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 66        | 26.72%  |
| 4.01-8.0    | 63        | 25.51%  |
| 8.01-16.0   | 38        | 15.38%  |
| 3.01-4.0    | 33        | 13.36%  |
| 32.01-64.0  | 28        | 11.34%  |
| 1.01-2.0    | 8         | 3.24%   |
| 24.01-32.0  | 5         | 2.02%   |
| 64.01-256.0 | 4         | 1.62%   |
| 2.01-3.0    | 2         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 74        | 26.43%  |
| 2.01-3.0   | 66        | 23.57%  |
| 4.01-8.0   | 61        | 21.79%  |
| 3.01-4.0   | 44        | 15.71%  |
| 8.01-16.0  | 20        | 7.14%   |
| 0.51-1.0   | 10        | 3.57%   |
| 16.01-24.0 | 2         | 0.71%   |
| 0.01-0.5   | 2         | 0.71%   |
| 24.01-32.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 173       | 69.2%   |
| 2      | 62        | 24.8%   |
| 3      | 12        | 4.8%    |
| 0      | 2         | 0.8%    |
| 4      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 201       | 82.72%  |
| Yes       | 42        | 17.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 65.02%  |
| No        | 85        | 34.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 97.52%  |
| No        | 6         | 2.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 84.49%  |
| No        | 38        | 15.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 242       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 234       | 96.3%   |
| Jurong West          | 4         | 1.65%   |
| Yio Chu Kang         | 1         | 0.41%   |
| Sembawang Estate     | 1         | 0.41%   |
| Queenstown Estate    | 1         | 0.41%   |
| Kampong Ulu Jurong   | 1         | 0.41%   |
| Bukit Batok New Town | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 55        | 89     | 17.3%   |
| SanDisk                     | 28        | 39     | 8.81%   |
| WDC                         | 27        | 49     | 8.49%   |
| SK hynix                    | 23        | 25     | 7.23%   |
| Seagate                     | 23        | 30     | 7.23%   |
| Toshiba                     | 20        | 28     | 6.29%   |
| Unknown                     | 16        | 23     | 5.03%   |
| Micron Technology           | 14        | 15     | 4.4%    |
| Intel                       | 14        | 16     | 4.4%    |
| HGST                        | 10        | 15     | 3.14%   |
| Hitachi                     | 8         | 8      | 2.52%   |
| KIOXIA                      | 7         | 7      | 2.2%    |
| Kingston                    | 6         | 7      | 1.89%   |
| Crucial                     | 6         | 6      | 1.89%   |
| Apple                       | 5         | 5      | 1.57%   |
| Phison                      | 4         | 6      | 1.26%   |
| China                       | 4         | 4      | 1.26%   |
| Phison Electronics          | 3         | 4      | 0.94%   |
| JMicron Technology          | 3         | 6      | 0.94%   |
| External                    | 3         | 3      | 0.94%   |
| UMIS                        | 2         | 3      | 0.63%   |
| Transcend                   | 2         | 3      | 0.63%   |
| SPCC                        | 2         | 2      | 0.63%   |
| Silicon Motion              | 2         | 2      | 0.63%   |
| Patriot                     | 2         | 2      | 0.63%   |
| LITEON                      | 2         | 3      | 0.63%   |
| Lexar                       | 2         | 2      | 0.63%   |
| Lenovo                      | 2         | 2      | 0.63%   |
| Hewlett-Packard             | 2         | 3      | 0.63%   |
| A-DATA Technology           | 2         | 2      | 0.63%   |
| YMTC                        | 1         | 1      | 0.31%   |
| Yangtze Memory Technologies | 1         | 1      | 0.31%   |
| TO Exter                    | 1         | 1      | 0.31%   |
| Team                        | 1         | 1      | 0.31%   |
| SAGE                        | 1         | 1      | 0.31%   |
| OCZ                         | 1         | 1      | 0.31%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.31%   |
| LT                          | 1         | 1      | 0.31%   |
| LALAK                       | 1         | 1      | 0.31%   |
| INTEL SS                    | 1         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 7         | 2.11%   |
| Toshiba MQ04ABF100 1TB                                | 5         | 1.51%   |
| Unknown MMC Card  64GB                                | 4         | 1.21%   |
| Samsung NVMe SSD Drive 1024GB                         | 4         | 1.21%   |
| HGST HTS721010A9E630 1TB                              | 4         | 1.21%   |
| Toshiba MQ01ABD100 1TB                                | 3         | 0.91%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 3         | 0.91%   |
| SanDisk NVMe SSD Drive 512GB                          | 3         | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 3         | 0.91%   |
| JMicron Generic 256GB                                 | 3         | 0.91%   |
| External USB3.0 2TB                                   | 3         | 0.91%   |
| WDC WDS500G2X0C-00L350 500GB                          | 2         | 0.6%    |
| WDC WDS100T2X0C-00L350 1TB                            | 2         | 0.6%    |
| WDC WD7500BPVT-80HXZT3 752GB                          | 2         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB                          | 2         | 0.6%    |
| WDC WD10SPZX-21Z10T0 1TB                              | 2         | 0.6%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 2         | 0.6%    |
| WDC PC SN720 SED SDAQNTW-1T00 1TB                     | 2         | 0.6%    |
| Unknown MMC Card  32GB                                | 2         | 0.6%    |
| Toshiba MQ01ABF050 500GB                              | 2         | 0.6%    |
| Toshiba MK5055GSX 500GB                               | 2         | 0.6%    |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 2         | 0.6%    |
| SK hynix SKHynix_HFS001TEJ9X115N 1024GB               | 2         | 0.6%    |
| SK hynix HFM512GDJTNG-8310A 512GB                     | 2         | 0.6%    |
| SK hynix HFM001TD3JX013N 1024GB                       | 2         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.6%    |
| Seagate ST1000LM049-2GH172 1TB                        | 2         | 0.6%    |
| Seagate Expansion 1TB                                 | 2         | 0.6%    |
| Sandisk WD_BLACK SN850X 1000GB                        | 2         | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 2         | 0.6%    |
| SanDisk SSD PLUS 480GB                                | 2         | 0.6%    |
| SanDisk SSD PLUS 240GB                                | 2         | 0.6%    |
| SanDisk SD6SN1M128G1002 128GB SSD                     | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.6%    |
| Samsung SSD 860 EVO 500GB                             | 2         | 0.6%    |
| Samsung SSD 860 EVO 250GB                             | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB                             | 2         | 0.6%    |
| Samsung SSD 850 EVO 1TB                               | 2         | 0.6%    |
| Samsung SSD 840 EVO 250GB                             | 2         | 0.6%    |
| Samsung NVMe SSD Drive 512GB                          | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 27.63%  |
| Toshiba             | 16        | 24     | 21.05%  |
| WDC                 | 13        | 17     | 17.11%  |
| HGST                | 10        | 15     | 13.16%  |
| Hitachi             | 8         | 8      | 10.53%  |
| External            | 3         | 3      | 3.95%   |
| Unknown             | 1         | 2      | 1.32%   |
| Samsung Electronics | 1         | 3      | 1.32%   |
| SAGE                | 1         | 1      | 1.32%   |
| Fujitsu             | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 50     | 30.59%  |
| SanDisk             | 15        | 24     | 17.65%  |
| Micron Technology   | 5         | 6      | 5.88%   |
| Crucial             | 4         | 4      | 4.71%   |
| China               | 4         | 4      | 4.71%   |
| Apple               | 4         | 4      | 4.71%   |
| SK hynix            | 3         | 3      | 3.53%   |
| WDC                 | 2         | 3      | 2.35%   |
| Transcend           | 2         | 3      | 2.35%   |
| SPCC                | 2         | 2      | 2.35%   |
| Patriot             | 2         | 2      | 2.35%   |
| LITEON              | 2         | 3      | 2.35%   |
| Kingston            | 2         | 3      | 2.35%   |
| Toshiba             | 1         | 1      | 1.18%   |
| TO Exter            | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 1      | 1.18%   |
| LT                  | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| LALAK               | 1         | 1      | 1.18%   |
| Hewlett-Packard     | 1         | 2      | 1.18%   |
| Haizhide            | 1         | 1      | 1.18%   |
| GALAX               | 1         | 1      | 1.18%   |
| FORESEE             | 1         | 1      | 1.18%   |
| CT1000MX            | 1         | 2      | 1.18%   |
| Unknown             | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 184    | 43.79%  |
| SSD     | 78        | 125    | 26.9%   |
| HDD     | 71        | 102    | 24.48%  |
| MMC     | 12        | 18     | 4.14%   |
| Unknown | 2         | 2      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 126       | 176    | 45.16%  |
| SATA | 125       | 214    | 44.8%   |
| SAS  | 16        | 23     | 5.73%   |
| MMC  | 12        | 18     | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 147    | 63.27%  |
| 0.51-1.0   | 46        | 71     | 31.29%  |
| 1.01-2.0   | 8         | 9      | 5.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 69        | 26.74%  |
| 251-500        | 63        | 24.42%  |
| 501-1000       | 45        | 17.44%  |
| 1001-2000      | 19        | 7.36%   |
| 51-100         | 19        | 7.36%   |
| 1-20           | 16        | 6.2%    |
| More than 3000 | 8         | 3.1%    |
| 21-50          | 8         | 3.1%    |
| Unknown        | 7         | 2.71%   |
| 2001-3000      | 4         | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 96        | 36.09%  |
| 21-50          | 50        | 18.8%   |
| 101-250        | 40        | 15.04%  |
| 51-100         | 27        | 10.15%  |
| 251-500        | 26        | 9.77%   |
| 501-1000       | 12        | 4.51%   |
| Unknown        | 7         | 2.63%   |
| 1001-2000      | 5         | 1.88%   |
| 2001-3000      | 2         | 0.75%   |
| More than 3000 | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 11.11%  |
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 11.11%  |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 11.11%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 11.11%  |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 11.11%  |
| SanDisk SSD U100 24GB              | 1         | 1      | 11.11%  |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 11.11%  |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 11.11%  |
| China SSD 128GB                    | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 33.33%  |
| Seagate | 2         | 2      | 22.22%  |
| Hitachi | 2         | 2      | 22.22%  |
| SanDisk | 1         | 1      | 11.11%  |
| China   | 1         | 1      | 11.11%  |

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
| HDD  | 7         | 8      | 77.78%  |
| SSD  | 2         | 2      | 22.22%  |

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
| Detected | 138       | 224    | 53.08%  |
| Works    | 113       | 197    | 43.46%  |
| Malfunc  | 9         | 10     | 3.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 148       | 48.84%  |
| Samsung Electronics                     | 32        | 10.56%  |
| AMD                                     | 25        | 8.25%   |
| SanDisk                                 | 24        | 7.92%   |
| SK hynix                                | 20        | 6.6%    |
| Micron Technology                       | 9         | 2.97%   |
| Phison Electronics                      | 7         | 2.31%   |
| KIOXIA                                  | 6         | 1.98%   |
| Toshiba America Info Systems            | 5         | 1.65%   |
| Kingston Technology Company             | 4         | 1.32%   |
| ADATA Technology                        | 4         | 1.32%   |
| Silicon Motion                          | 3         | 0.99%   |
| Nvidia                                  | 3         | 0.99%   |
| Shenzhen Longsys Electronics            | 2         | 0.66%   |
| Seagate Technology                      | 2         | 0.66%   |
| Micron/Crucial Technology               | 2         | 0.66%   |
| Lenovo                                  | 2         | 0.66%   |
| Yangtze Memory Technologies             | 1         | 0.33%   |
| Union Memory (Shenzhen)                 | 1         | 0.33%   |
| Shenzhen Unionmemory Information System | 1         | 0.33%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.33%   |
| ASMedia Technology                      | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 7.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 21        | 6.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 4.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 4.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 3.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.14%   |
| Intel SSD 660P Series                                                          | 7         | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 1.89%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 6         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 1.57%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.26%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 0.94%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.94%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 3         | 0.94%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.94%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.94%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.94%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 0.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.94%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.63%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 47.52%  |
| NVMe | 126       | 41.58%  |
| RAID | 24        | 7.92%   |
| IDE  | 9         | 2.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 197       | 81.4%   |
| AMD    | 45        | 18.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 4.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 3.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 3.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 3.31%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.07%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 2.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.24%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.24%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.24%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 3         | 1.24%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.24%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.83%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.83%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.83%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.83%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.83%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.83%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.83%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 0.83%   |
| Intel 13th Gen Core i9-13900HX                | 2         | 0.83%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 71        | 29.34%  |
| Intel Core i5           | 50        | 20.66%  |
| Other                   | 33        | 13.64%  |
| AMD Ryzen 7             | 19        | 7.85%   |
| Intel Celeron           | 11        | 4.55%   |
| AMD Ryzen 5             | 11        | 4.55%   |
| Intel Core 2 Duo        | 10        | 4.13%   |
| Intel Core i3           | 5         | 2.07%   |
| Intel Xeon              | 4         | 1.65%   |
| Intel Pentium Silver    | 4         | 1.65%   |
| Intel Atom              | 4         | 1.65%   |
| AMD Ryzen 7 PRO         | 3         | 1.24%   |
| Intel Core m3           | 2         | 0.83%   |
| Intel Core i9           | 2         | 0.83%   |
| AMD Ryzen 9             | 2         | 0.83%   |
| AMD Ryzen 3             | 2         | 0.83%   |
| Intel Pentium Dual      | 1         | 0.41%   |
| Intel Core 2            | 1         | 0.41%   |
| AMD Turion 64 X2 Mobile | 1         | 0.41%   |
| AMD Ryzen 5 PRO         | 1         | 0.41%   |
| AMD PRO A10             | 1         | 0.41%   |
| AMD E2                  | 1         | 0.41%   |
| AMD E1                  | 1         | 0.41%   |
| AMD E                   | 1         | 0.41%   |
| AMD A6                  | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 93        | 38.43%  |
| 2      | 86        | 35.54%  |
| 8      | 31        | 12.81%  |
| 6      | 19        | 7.85%   |
| 14     | 5         | 2.07%   |
| 10     | 4         | 1.65%   |
| 24     | 2         | 0.83%   |
| 1      | 2         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 242       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 199       | 81.56%  |
| 1      | 45        | 18.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 239       | 98.76%  |
| 32-bit         | 2         | 0.83%   |
| Unknown        | 1         | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 25.3%   |
| 0x806ea    | 14        | 5.53%   |
| 0x806ec    | 13        | 5.14%   |
| 0x206a7    | 13        | 5.14%   |
| 0x306a9    | 12        | 4.74%   |
| 0x906ea    | 10        | 3.95%   |
| 0x0a50000c | 10        | 3.95%   |
| 0x806c1    | 9         | 3.56%   |
| 0x40651    | 7         | 2.77%   |
| 0x806e9    | 6         | 2.37%   |
| 0x306d4    | 6         | 2.37%   |
| 0x806eb    | 5         | 1.98%   |
| 0x6fd      | 5         | 1.98%   |
| 0x806d1    | 4         | 1.58%   |
| 0x506e3    | 4         | 1.58%   |
| 0x406e3    | 4         | 1.58%   |
| 0x1067a    | 4         | 1.58%   |
| 0x08108109 | 4         | 1.58%   |
| 0xa0652    | 3         | 1.19%   |
| 0x806c2    | 3         | 1.19%   |
| 0x706a1    | 3         | 1.19%   |
| 0x40661    | 3         | 1.19%   |
| 0x306c3    | 3         | 1.19%   |
| 0x20655    | 3         | 1.19%   |
| 0x08600106 | 3         | 1.19%   |
| 0x906e9    | 2         | 0.79%   |
| 0x906c0    | 2         | 0.79%   |
| 0x906a3    | 2         | 0.79%   |
| 0x706e5    | 2         | 0.79%   |
| 0x706a8    | 2         | 0.79%   |
| 0x406c3    | 2         | 0.79%   |
| 0x30678    | 2         | 0.79%   |
| 0x106c2    | 2         | 0.79%   |
| 0x0a404102 | 2         | 0.79%   |
| 0x0a404101 | 2         | 0.79%   |
| 0x08600103 | 2         | 0.79%   |
| 0x08108102 | 2         | 0.79%   |
| 0x06006705 | 2         | 0.79%   |
| 0xb06a2    | 1         | 0.4%    |
| 0xb0671    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 63        | 25.93%  |
| TigerLake        | 17        | 7%      |
| SandyBridge      | 16        | 6.58%   |
| Haswell          | 15        | 6.17%   |
| Zen 3            | 14        | 5.76%   |
| Unknown          | 14        | 5.76%   |
| IvyBridge        | 13        | 5.35%   |
| Skylake          | 12        | 4.94%   |
| Zen+             | 9         | 3.7%    |
| Zen 2            | 7         | 2.88%   |
| Icelake          | 7         | 2.88%   |
| Broadwell        | 7         | 2.88%   |
| Penryn           | 6         | 2.47%   |
| Core             | 6         | 2.47%   |
| Alderlake Hybrid | 6         | 2.47%   |
| Silvermont       | 5         | 2.06%   |
| Goldmont plus    | 5         | 2.06%   |
| CometLake        | 5         | 2.06%   |
| Westmere         | 3         | 1.23%   |
| Excavator        | 3         | 1.23%   |
| Tremont          | 2         | 0.82%   |
| Goldmont         | 2         | 0.82%   |
| Bonnell          | 2         | 0.82%   |
| Bobcat           | 2         | 0.82%   |
| K8 Hammer        | 1         | 0.41%   |
| Jaguar           | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 55.56%  |
| Nvidia | 98        | 29.43%  |
| AMD    | 50        | 15.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 18        | 5.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 16        | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 15        | 4.36%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 13        | 3.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 12        | 3.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 2.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 9         | 2.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 9         | 2.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 9         | 2.62%   |
| Intel HD Graphics 620                                                     | 8         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 7         | 2.03%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 1.74%   |
| AMD Rembrandt [Radeon 680M]                                               | 6         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                             | 5         | 1.45%   |
| Nvidia GP108BM [GeForce MX250]                                            | 5         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 5         | 1.45%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 5         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 5         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 5         | 1.45%   |
| Intel HD Graphics 5500                                                    | 5         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 5         | 1.45%   |
| Intel HD Graphics 530                                                     | 4         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 0.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 3         | 0.87%   |
| Nvidia GM108M [GeForce 940M]                                              | 3         | 0.87%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 3         | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 3         | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 0.58%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                   | 2         | 0.58%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.58%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 43.21%  |
| Intel + Nvidia | 72        | 29.63%  |
| 1 x AMD        | 27        | 11.11%  |
| 1 x Nvidia     | 16        | 6.58%   |
| AMD + Nvidia   | 11        | 4.53%   |
| Intel + AMD    | 8         | 3.29%   |
| 2 x AMD        | 4         | 1.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 183       | 74.09%  |
| Proprietary | 58        | 23.48%  |
| Unknown     | 6         | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 67.72%  |
| 1.01-2.0   | 31        | 12.2%   |
| 0.01-0.5   | 18        | 7.09%   |
| 3.01-4.0   | 16        | 6.3%    |
| 7.01-8.0   | 5         | 1.97%   |
| 0.51-1.0   | 5         | 1.97%   |
| 5.01-6.0   | 4         | 1.57%   |
| 8.01-16.0  | 2         | 0.79%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 71        | 25.36%  |
| BOE                     | 36        | 12.86%  |
| LG Display              | 31        | 11.07%  |
| Samsung Electronics     | 27        | 9.64%   |
| Chimei Innolux          | 25        | 8.93%   |
| Dell                    | 17        | 6.07%   |
| Sharp                   | 10        | 3.57%   |
| Apple                   | 10        | 3.57%   |
| Philips                 | 7         | 2.5%    |
| Acer                    | 7         | 2.5%    |
| CSO                     | 6         | 2.14%   |
| InfoVision              | 4         | 1.43%   |
| Lenovo                  | 3         | 1.07%   |
| Goldstar                | 3         | 1.07%   |
| PANDA                   | 2         | 0.71%   |
| Mi                      | 2         | 0.71%   |
| LG Philips              | 2         | 0.71%   |
| Hewlett-Packard         | 2         | 0.71%   |
| ASUSTek Computer        | 2         | 0.71%   |
| Toshiba                 | 1         | 0.36%   |
| TMX                     | 1         | 0.36%   |
| Tianma XM               | 1         | 0.36%   |
| Sony                    | 1         | 0.36%   |
| JDI                     | 1         | 0.36%   |
| EXP                     | 1         | 0.36%   |
| DENON                   | 1         | 0.36%   |
| CVT                     | 1         | 0.36%   |
| CPT                     | 1         | 0.36%   |
| Chi Mei Optoelectronics | 1         | 0.36%   |
| BenQ                    | 1         | 0.36%   |
| AOC                     | 1         | 0.36%   |
| Ancor Communications    | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 4         | 1.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 1.41%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3         | 1.06%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 3         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.71%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                 | 2         | 0.71%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.71%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.71%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch            | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.71%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.71%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.71%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 2         | 0.71%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.71%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.35%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch               | 1         | 0.35%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.35%   |
| Sony BW8 MS_9001 1200x1920                                            | 1         | 0.35%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 130       | 50.39%  |
| 1366x768 (WXGA)    | 49        | 18.99%  |
| 3840x2160 (4K)     | 12        | 4.65%   |
| 2560x1440 (QHD)    | 12        | 4.65%   |
| 2560x1600          | 10        | 3.88%   |
| 1280x800 (WXGA)    | 10        | 3.88%   |
| 2880x1800          | 6         | 2.33%   |
| 1920x1200 (WUXGA)  | 6         | 2.33%   |
| 3440x1440          | 4         | 1.55%   |
| 3840x2400          | 2         | 0.78%   |
| 3200x1800 (QHD+)   | 2         | 0.78%   |
| 3072x1920          | 2         | 0.78%   |
| 3000x2000          | 2         | 0.78%   |
| 2240x1400          | 2         | 0.78%   |
| 1600x900 (HD+)     | 2         | 0.78%   |
| 1440x900 (WXGA+)   | 2         | 0.78%   |
| 1360x768           | 2         | 0.78%   |
| 1680x1050 (WSXGA+) | 1         | 0.39%   |
| 1280x1024 (SXGA)   | 1         | 0.39%   |
| 1024x600           | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 27.6%   |
| 13      | 62        | 22.22%  |
| 14      | 51        | 18.28%  |
| 24      | 12        | 4.3%    |
| 12      | 12        | 4.3%    |
| 27      | 11        | 3.94%   |
| 23      | 10        | 3.58%   |
| 21      | 8         | 2.87%   |
| 16      | 8         | 2.87%   |
| 11      | 8         | 2.87%   |
| 34      | 3         | 1.08%   |
| 19      | 3         | 1.08%   |
| 32      | 2         | 0.72%   |
| 18      | 2         | 0.72%   |
| 17      | 2         | 0.72%   |
| 65      | 1         | 0.36%   |
| 52      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 35      | 1         | 0.36%   |
| 31      | 1         | 0.36%   |
| 10      | 1         | 0.36%   |
| 8       | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 57.97%  |
| 201-300     | 54        | 19.57%  |
| 501-600     | 31        | 11.23%  |
| 401-500     | 12        | 4.35%   |
| 351-400     | 7         | 2.54%   |
| 701-800     | 5         | 1.81%   |
| 801-900     | 2         | 0.72%   |
| 1001-1500   | 2         | 0.72%   |
| 601-700     | 1         | 0.36%   |
| 101-200     | 1         | 0.36%   |
| Unknown     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 191       | 79.25%  |
| 16/10 | 40        | 16.6%   |
| 3/2   | 4         | 1.66%   |
| 21/9  | 4         | 1.66%   |
| 5/4   | 1         | 0.41%   |
| 0.62  | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 84        | 30.43%  |
| 101-110        | 76        | 27.54%  |
| 71-80          | 26        | 9.42%   |
| 201-250        | 24        | 8.7%    |
| 61-70          | 12        | 4.35%   |
| 301-350        | 11        | 3.99%   |
| 51-60          | 8         | 2.9%    |
| 111-120        | 8         | 2.9%    |
| 351-500        | 7         | 2.54%   |
| 151-200        | 5         | 1.81%   |
| 91-100         | 3         | 1.09%   |
| More than 1000 | 2         | 0.72%   |
| 251-300        | 2         | 0.72%   |
| 141-150        | 2         | 0.72%   |
| 121-130        | 2         | 0.72%   |
| 41-50          | 1         | 0.36%   |
| 1-40           | 1         | 0.36%   |
| 501-1000       | 1         | 0.36%   |
| Unknown        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 116       | 43.12%  |
| 101-120       | 49        | 18.22%  |
| 161-240       | 47        | 17.47%  |
| 51-100        | 37        | 13.75%  |
| More than 240 | 16        | 5.95%   |
| 1-50          | 3         | 1.12%   |
| Unknown       | 1         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 195       | 77.08%  |
| 2     | 47        | 18.58%  |
| 0     | 8         | 3.16%   |
| 3     | 3         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 147       | 42.12%  |
| Realtek Semiconductor    | 93        | 26.65%  |
| Qualcomm Atheros         | 47        | 13.47%  |
| Broadcom                 | 22        | 6.3%    |
| MediaTek                 | 10        | 2.87%   |
| ASIX Electronics         | 7         | 2.01%   |
| Marvell Technology Group | 3         | 0.86%   |
| Broadcom Limited         | 3         | 0.86%   |
| Sierra Wireless          | 2         | 0.57%   |
| Qualcomm                 | 2         | 0.57%   |
| TP-Link                  | 1         | 0.29%   |
| Samsung Electronics      | 1         | 0.29%   |
| Ralink Technology        | 1         | 0.29%   |
| Ralink                   | 1         | 0.29%   |
| Nvidia                   | 1         | 0.29%   |
| MosChip Semiconductor    | 1         | 0.29%   |
| Linksys                  | 1         | 0.29%   |
| Lenovo                   | 1         | 0.29%   |
| Hewlett-Packard          | 1         | 0.29%   |
| Google                   | 1         | 0.29%   |
| Dell                     | 1         | 0.29%   |
| D-Link                   | 1         | 0.29%   |
| Apple                    | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 13.77%  |
| Intel Wi-Fi 6 AX200                                               | 17        | 4.11%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 3.86%   |
| Intel Wireless 7265                                               | 14        | 3.38%   |
| Intel Wireless 8265 / 8275                                        | 13        | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.93%   |
| Intel Wireless 7260                                               | 8         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.45%   |
| Intel Wireless 3165                                               | 6         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.97%   |
| Intel Wireless 8260                                               | 4         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.97%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.72%   |
| Realtek 802.11ac NIC                                              | 3         | 0.72%   |
| Intel Wireless-AC 9260                                            | 3         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.72%   |
| Sierra Wireless EM7455                                            | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 58.78%  |
| Qualcomm Atheros      | 42        | 17.14%  |
| Realtek Semiconductor | 22        | 8.98%   |
| Broadcom              | 15        | 6.12%   |
| MediaTek              | 10        | 4.08%   |
| Sierra Wireless       | 2         | 0.82%   |
| Qualcomm              | 2         | 0.82%   |
| Broadcom Limited      | 2         | 0.82%   |
| TP-Link               | 1         | 0.41%   |
| Ralink Technology     | 1         | 0.41%   |
| Ralink                | 1         | 0.41%   |
| Hewlett-Packard       | 1         | 0.41%   |
| Dell                  | 1         | 0.41%   |
| D-Link                | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17        | 6.88%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 6.48%   |
| Intel Wireless 7265                                                     | 14        | 5.67%   |
| Intel Wireless 8265 / 8275                                              | 13        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 4.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 4.05%   |
| Intel Wireless 7260                                                     | 8         | 3.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 3.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 3.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.43%   |
| Intel Wireless 3165                                                     | 6         | 2.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.62%   |
| Intel Wireless 8260                                                     | 4         | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.62%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 1.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.21%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.21%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.21%   |
| Sierra Wireless EM7455                                                  | 2         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.81%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 80        | 48.48%  |
| Intel                    | 46        | 27.88%  |
| Broadcom                 | 11        | 6.67%   |
| Qualcomm Atheros         | 10        | 6.06%   |
| ASIX Electronics         | 7         | 4.24%   |
| Marvell Technology Group | 3         | 1.82%   |
| Samsung Electronics      | 1         | 0.61%   |
| Nvidia                   | 1         | 0.61%   |
| MosChip Semiconductor    | 1         | 0.61%   |
| Linksys                  | 1         | 0.61%   |
| Lenovo                   | 1         | 0.61%   |
| Google                   | 1         | 0.61%   |
| Broadcom Limited         | 1         | 0.61%   |
| Apple                    | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 57        | 34.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 5.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 4.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.19%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 4.19%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 3.59%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.2%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.2%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.2%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.2%    |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.2%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.6%    |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.6%    |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.6%    |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.6%    |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.6%    |
| Linksys Gigabit Ethernet Adapter                                               | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 236       | 59.9%   |
| Ethernet | 158       | 40.1%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 81.92%  |
| Ethernet | 47        | 18.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 134       | 55.14%  |
| 1     | 106       | 43.62%  |
| 3     | 2         | 0.82%   |
| 0     | 1         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 224       | 92.56%  |
| Yes  | 18        | 7.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 58.37%  |
| Qualcomm Atheros Communications | 14        | 6.7%    |
| IMC Networks                    | 14        | 6.7%    |
| Foxconn / Hon Hai               | 12        | 5.74%   |
| Lite-On Technology              | 10        | 4.78%   |
| Broadcom                        | 9         | 4.31%   |
| Apple                           | 9         | 4.31%   |
| Realtek Semiconductor           | 7         | 3.35%   |
| MediaTek                        | 2         | 0.96%   |
| Cambridge Silicon Radio         | 2         | 0.96%   |
| USI                             | 1         | 0.48%   |
| Toshiba                         | 1         | 0.48%   |
| Ralink Technology               | 1         | 0.48%   |
| Foxconn International           | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |
| Chicony Electronics             | 1         | 0.48%   |
| Askey Computer                  | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 41        | 19.62%  |
| Intel AX201 Bluetooth                               | 32        | 15.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 10.53%  |
| Intel AX200 Bluetooth                               | 15        | 7.18%   |
| Intel Bluetooth Device                              | 7         | 3.35%   |
| Apple Bluetooth Host Controller                     | 7         | 3.35%   |
| Realtek Bluetooth Radio                             | 6         | 2.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.39%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.39%   |
| IMC Networks Bluetooth Device                       | 5         | 2.39%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.91%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.91%   |
| IMC Networks Wireless_Device                        | 3         | 1.44%   |
| MediaTek Wireless_Device                            | 2         | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.96%   |
| Lite-On Bluetooth Radio                             | 2         | 0.96%   |
| Lite-On Bluetooth Device                            | 2         | 0.96%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.96%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.96%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.96%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.96%   |
| USI Bluetooth Device                                | 1         | 0.48%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.48%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.48%   |
| Lite-On Wireless_Device                             | 1         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.48%   |
| Intel AX210 Bluetooth                               | 1         | 0.48%   |
| IMC Networks Bluetooth module                       | 1         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.48%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 192       | 62.95%  |
| Nvidia                | 48        | 15.74%  |
| AMD                   | 46        | 15.08%  |
| Plantronics           | 2         | 0.66%   |
| Lenovo                | 2         | 0.66%   |
| Kingston Technology   | 2         | 0.66%   |
| Apple                 | 2         | 0.66%   |
| Sony                  | 1         | 0.33%   |
| Sennheiser electronic | 1         | 0.33%   |
| SAVITECH              | 1         | 0.33%   |
| Razer USA             | 1         | 0.33%   |
| Logitech              | 1         | 0.33%   |
| Jieli Technology      | 1         | 0.33%   |
| JBL                   | 1         | 0.33%   |
| GN Netcom             | 1         | 0.33%   |
| Cooler Master         | 1         | 0.33%   |
| Conexant Systems      | 1         | 0.33%   |
| ASUSTek Computer      | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37        | 10.16%  |
| Intel Sunrise Point-LP HD Audio                                            | 34        | 9.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 4.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 2.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.2%    |
| Nvidia Audio device                                                        | 7         | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.92%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.92%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 4         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.82%   |
| Plantronics Blackwire 3225 Series                                          | 2         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.55%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 50        | 28.41%  |
| Samsung Electronics | 43        | 24.43%  |
| Micron Technology   | 25        | 14.2%   |
| Kingston            | 14        | 7.95%   |
| Crucial             | 11        | 6.25%   |
| Unknown             | 10        | 5.68%   |
| Ramaxel Technology  | 4         | 2.27%   |
| Transcend           | 3         | 1.7%    |
| A-DATA Technology   | 3         | 1.7%    |
| Unknown (ABCD)      | 2         | 1.14%   |
| Nanya Technology    | 2         | 1.14%   |
| Elpida              | 2         | 1.14%   |
| V-GeN               | 1         | 0.57%   |
| Team                | 1         | 0.57%   |
| Patriot             | 1         | 0.57%   |
| Lexar               | 1         | 0.57%   |
| Corsair             | 1         | 0.57%   |
| Carry               | 1         | 0.57%   |
| ASint Technology    | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 2.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.62%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 1.62%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.08%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.08%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 1.08%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.08%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.08%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.08%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 1.08%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 1.08%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.08%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 2         | 1.08%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.54%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.54%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.54%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s            | 1         | 0.54%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.54%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1333MT/s              | 1         | 0.54%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 71        | 49.65%  |
| DDR3   | 38        | 26.57%  |
| LPDDR4 | 12        | 8.39%   |
| LPDDR3 | 12        | 8.39%   |
| DDR5   | 6         | 4.2%    |
| LPDDR5 | 3         | 2.1%    |
| SDRAM  | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 79.17%  |
| Row Of Chips | 27        | 18.75%  |
| Chip         | 2         | 1.39%   |
| Unknown      | 1         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 67        | 41.61%  |
| 4096  | 41        | 25.47%  |
| 16384 | 33        | 20.5%   |
| 32768 | 9         | 5.59%   |
| 2048  | 9         | 5.59%   |
| 1024  | 2         | 1.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 34        | 21.38%  |
| 2667    | 31        | 19.5%   |
| 1600    | 30        | 18.87%  |
| 2133    | 10        | 6.29%   |
| 4267    | 9         | 5.66%   |
| 2400    | 9         | 5.66%   |
| 1334    | 6         | 3.77%   |
| 1333    | 6         | 3.77%   |
| 4800    | 4         | 2.52%   |
| 6400    | 3         | 1.89%   |
| 5600    | 3         | 1.89%   |
| 1867    | 3         | 1.89%   |
| 8400    | 2         | 1.26%   |
| 3266    | 2         | 1.26%   |
| 1067    | 2         | 1.26%   |
| Unknown | 2         | 1.26%   |
| 4199    | 1         | 0.63%   |
| 1200    | 1         | 0.63%   |
| 800     | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Brother DCP-L2535DW series | 1         | 100%    |

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
| Chicony Electronics                    | 57        | 26.64%  |
| IMC Networks                           | 33        | 15.42%  |
| Microdia                               | 28        | 13.08%  |
| Realtek Semiconductor                  | 17        | 7.94%   |
| Sunplus Innovation Technology          | 14        | 6.54%   |
| Bison Electronics                      | 11        | 5.14%   |
| Suyin                                  | 7         | 3.27%   |
| Syntek                                 | 5         | 2.34%   |
| Samsung Electronics                    | 5         | 2.34%   |
| Lite-On Technology                     | 5         | 2.34%   |
| Apple                                  | 4         | 1.87%   |
| Acer                                   | 4         | 1.87%   |
| Logitech                               | 3         | 1.4%    |
| Silicon Motion                         | 2         | 0.93%   |
| Ricoh                                  | 2         | 0.93%   |
| Quanta                                 | 2         | 0.93%   |
| OmniVision Technologies                | 2         | 0.93%   |
| Luxvisions Innotech Limited            | 2         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 0.93%   |
| Alcor Micro                            | 2         | 0.93%   |
| SunplusIT                              | 1         | 0.47%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.47%   |
| Sonix Technology                       | 1         | 0.47%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.47%   |
| Magic Control Technology               | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| Intel                                  | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 19        | 8.84%   |
| Chicony Integrated Camera                        | 13        | 6.05%   |
| Chicony HD WebCam                                | 10        | 4.65%   |
| IMC Networks USB2.0 HD UVC WebCam                | 9         | 4.19%   |
| IMC Networks Integrated Camera                   | 9         | 4.19%   |
| Sunplus Integrated_Webcam_HD                     | 7         | 3.26%   |
| Realtek Integrated_Webcam_HD                     | 7         | 3.26%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 2.79%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 2.33%   |
| Syntek Integrated Camera                         | 4         | 1.86%   |
| Microdia USB 2.0 Camera                          | 4         | 1.86%   |
| Lite-On Integrated Camera                        | 4         | 1.86%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 4         | 1.86%   |
| Chicony HP HD Camera                             | 4         | 1.86%   |
| Bison Integrated Camera                          | 4         | 1.86%   |
| Acer Integrated Camera                           | 4         | 1.86%   |
| Chicony USB2.0 Camera                            | 3         | 1.4%    |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 1.4%    |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.4%    |
| Apple FaceTime HD Camera                         | 3         | 1.4%    |
| Realtek Integrated Webcam_HD                     | 2         | 0.93%   |
| Realtek Asus 2.0 USB Webcam                      | 2         | 0.93%   |
| OmniVision OV2640 Webcam                         | 2         | 0.93%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera    | 2         | 0.93%   |
| IMC Networks Lenovo EasyCamera                   | 2         | 0.93%   |
| Chicony VGA Webcam                               | 2         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                    | 2         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 0.93%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 0.93%   |
| Chicony HD User Facing                           | 2         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 0.93%   |
| Bison HD Webcam                                  | 2         | 0.93%   |
| Bison BisonCam, NB Pro                           | 2         | 0.93%   |
| Alcor Micro Acer Integrated Webcam               | 2         | 0.93%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.47%   |
| Suyin UVC HD Webcam                              | 1         | 0.47%   |
| Suyin Laptop_Integrated_Webcam_HD                | 1         | 0.47%   |
| Suyin HD WebCam                                  | 1         | 0.47%   |
| Suyin Asus Integrated Webcam                     | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 15        | 24.19%  |
| Validity Sensors                   | 13        | 20.97%  |
| Shenzhen Goodix Technology         | 8         | 12.9%   |
| LighTuning Technology              | 7         | 11.29%  |
| Upek                               | 6         | 9.68%   |
| Elan Microelectronics              | 6         | 9.68%   |
| AuthenTec                          | 6         | 9.68%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 12.9%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 11.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 9.68%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 6.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 4         | 6.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.84%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 4.84%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.23%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.23%   |
| AuthenTec AES2810                                                          | 2         | 3.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.61%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.61%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.61%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.61%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.61%   |
| Unknown                                                                    | 1         | 1.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 77.78%  |
| Alcor Micro | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 44.44%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 22.22%  |
| Broadcom 5880                                  | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 141       | 54.86%  |
| 1     | 82        | 31.91%  |
| 2     | 29        | 11.28%  |
| 3     | 3         | 1.17%   |
| 5     | 1         | 0.39%   |
| 4     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 37.75%  |
| Graphics card            | 41        | 27.15%  |
| Net/wireless             | 14        | 9.27%   |
| Multimedia controller    | 11        | 7.28%   |
| Chipcard                 | 8         | 5.3%    |
| Camera                   | 8         | 5.3%    |
| Communication controller | 4         | 2.65%   |
| Net/ethernet             | 2         | 1.32%   |
| Bluetooth                | 2         | 1.32%   |
| Wireless                 | 1         | 0.66%   |
| Storage/raid             | 1         | 0.66%   |
| Sound                    | 1         | 0.66%   |
| Firewire controller      | 1         | 0.66%   |

