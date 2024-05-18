Linux in Thailand - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 426

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A315-44P             | [88d63b7ebb](https://linux-hardware.org/?probe=88d63b7ebb) | Apr 29, 2024 |
| Apple         | MacBookAir6,2               | [37c91e715a](https://linux-hardware.org/?probe=37c91e715a) | Apr 22, 2024 |
| Acer          | Aspire A315-44P             | [6636df5576](https://linux-hardware.org/?probe=6636df5576) | Apr 20, 2024 |
| Apple         | MacBookPro10,1              | [c468075794](https://linux-hardware.org/?probe=c468075794) | Apr 11, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1b09cf1322](https://linux-hardware.org/?probe=1b09cf1322) | Apr 10, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [46ec5edae0](https://linux-hardware.org/?probe=46ec5edae0) | Apr 10, 2024 |
| Acer          | Swift SF314-71              | [071a57efd2](https://linux-hardware.org/?probe=071a57efd2) | Apr 07, 2024 |
| MSI           | GF65 Thin 10UE              | [8d0c1e98f2](https://linux-hardware.org/?probe=8d0c1e98f2) | Apr 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [21ef6a026f](https://linux-hardware.org/?probe=21ef6a026f) | Mar 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [d55fe0350b](https://linux-hardware.org/?probe=d55fe0350b) | Mar 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a9cd8ee448](https://linux-hardware.org/?probe=a9cd8ee448) | Mar 22, 2024 |
| Apple         | MacBookPro4,1               | [6570fe8279](https://linux-hardware.org/?probe=6570fe8279) | Mar 07, 2024 |
| ASUSTek       | F80Q                        | [613ffc9f22](https://linux-hardware.org/?probe=613ffc9f22) | Mar 05, 2024 |
| Fujitsu       | FMVC05005                   | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Apple         | MacBookPro4,1               | [a0684dfb38](https://linux-hardware.org/?probe=a0684dfb38) | Feb 25, 2024 |
| HP            | ProBook 430 G3              | [e718712840](https://linux-hardware.org/?probe=e718712840) | Feb 24, 2024 |
| Acer          | SF314-71-50E8               | [109256318a](https://linux-hardware.org/?probe=109256318a) | Feb 20, 2024 |
| Acer          | SF314-71-50E8               | [b05150cb04](https://linux-hardware.org/?probe=b05150cb04) | Feb 19, 2024 |
| Acer          | SF314-71-50E8               | [8c9f92e873](https://linux-hardware.org/?probe=8c9f92e873) | Feb 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [edb077d9e9](https://linux-hardware.org/?probe=edb077d9e9) | Feb 15, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [de7b828cc8](https://linux-hardware.org/?probe=de7b828cc8) | Feb 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d72d765d84](https://linux-hardware.org/?probe=d72d765d84) | Feb 06, 2024 |
| Acer          | SF314-71-50E8               | [0d44d5cc60](https://linux-hardware.org/?probe=0d44d5cc60) | Feb 06, 2024 |
| Lenovo        | Z50-70 20354                | [d6023b78a2](https://linux-hardware.org/?probe=d6023b78a2) | Feb 02, 2024 |
| Fujitsu       | FARQ10003                   | [6084280fc9](https://linux-hardware.org/?probe=6084280fc9) | Jan 27, 2024 |
| Acer          | Aspire E5-575G              | [326dd5b81f](https://linux-hardware.org/?probe=326dd5b81f) | Jan 23, 2024 |
| Toshiba       | Satellite L640              | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | OMEN by Transcend Gaming... | [6690260fd8](https://linux-hardware.org/?probe=6690260fd8) | Jan 18, 2024 |
| Lenovo        | ThinkPad X240 20AMS00100    | [4b39b1cbe0](https://linux-hardware.org/?probe=4b39b1cbe0) | Jan 17, 2024 |
| Dell          | Vostro 5471                 | [d3ef161a9e](https://linux-hardware.org/?probe=d3ef161a9e) | Jan 14, 2024 |
| Apple         | MacBookPro3,1               | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Samsung       | 900X3L                      | [d77974be8d](https://linux-hardware.org/?probe=d77974be8d) | Jan 07, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | [b811bdcbfd](https://linux-hardware.org/?probe=b811bdcbfd) | Jan 07, 2024 |
| HP            | ENVY m6                     | [d63a06fb89](https://linux-hardware.org/?probe=d63a06fb89) | Jan 04, 2024 |
| Acer          | SF314-71-50E8               | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1b62649586](https://linux-hardware.org/?probe=1b62649586) | Jan 02, 2024 |
| Acer          | SF314-71-50E8               | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| MicroByte     | ezbook                      | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | ENVY m6                     | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| Dell          | Vostro 3558                 | [83b004a254](https://linux-hardware.org/?probe=83b004a254) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [9227c29b16](https://linux-hardware.org/?probe=9227c29b16) | Dec 14, 2023 |
| HP            | ENVY m6                     | [f561fb6a85](https://linux-hardware.org/?probe=f561fb6a85) | Dec 12, 2023 |
| Apple         | MacBookAir7,1               | [b6d0160123](https://linux-hardware.org/?probe=b6d0160123) | Dec 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ac764bedcc](https://linux-hardware.org/?probe=ac764bedcc) | Dec 06, 2023 |
| Acer          | Swift SF515-51T             | [3cd6a2e9dc](https://linux-hardware.org/?probe=3cd6a2e9dc) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | [a0306c58e5](https://linux-hardware.org/?probe=a0306c58e5) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | [a03bc4e394](https://linux-hardware.org/?probe=a03bc4e394) | Dec 03, 2023 |
| HP            | Laptop 14-ck0xxx            | [40a0a394cc](https://linux-hardware.org/?probe=40a0a394cc) | Dec 01, 2023 |
| HP            | EliteBook 2170p             | [fe332ae4ef](https://linux-hardware.org/?probe=fe332ae4ef) | Nov 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c1777b379](https://linux-hardware.org/?probe=8c1777b379) | Nov 28, 2023 |
| Lenovo        | IdeaPad Y470 20090          | [ae2a0fceac](https://linux-hardware.org/?probe=ae2a0fceac) | Nov 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [e551d74658](https://linux-hardware.org/?probe=e551d74658) | Nov 17, 2023 |
| Acer          | Aspire 4350                 | [32da8a19ac](https://linux-hardware.org/?probe=32da8a19ac) | Nov 13, 2023 |
| HP            | Pavilion 14                 | [344b8f4865](https://linux-hardware.org/?probe=344b8f4865) | Nov 13, 2023 |
| HP            | Pavilion 14                 | [e34aa57010](https://linux-hardware.org/?probe=e34aa57010) | Nov 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [661492882b](https://linux-hardware.org/?probe=661492882b) | Nov 13, 2023 |
| Acer          | Aspire F5-573G              | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [048559335e](https://linux-hardware.org/?probe=048559335e) | Nov 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d17a8bc08a](https://linux-hardware.org/?probe=d17a8bc08a) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [313770aff1](https://linux-hardware.org/?probe=313770aff1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| Lenovo        | ThinkPad T580 20L90024GE    | [5853b175c4](https://linux-hardware.org/?probe=5853b175c4) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d561271316](https://linux-hardware.org/?probe=d561271316) | Oct 19, 2023 |
| HP            | Compaq Presario CQ40        | [45639896bd](https://linux-hardware.org/?probe=45639896bd) | Oct 15, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| MSI           | GF63 Thin 10SCXR            | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| Infinix       | INBOOK X2                   | [5d39adb330](https://linux-hardware.org/?probe=5d39adb330) | Oct 05, 2023 |
| Acer          | Swift SF314-52              | [54c8de587a](https://linux-hardware.org/?probe=54c8de587a) | Oct 05, 2023 |
| Lenovo        | ThinkPad X200 745536T       | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| HP            | EliteBook 840 G6            | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| Lenovo        | ThinkPad X200 745536T       | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a7d0f8e075](https://linux-hardware.org/?probe=a7d0f8e075) | Sep 26, 2023 |
| Acer          | Aspire E5-575G              | [48fb2a7ee3](https://linux-hardware.org/?probe=48fb2a7ee3) | Sep 25, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2310ddb9a7](https://linux-hardware.org/?probe=2310ddb9a7) | Sep 21, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| Acer          | Aspire E5-471G              | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| HP            | 1000                        | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [dda651a1c4](https://linux-hardware.org/?probe=dda651a1c4) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf8f795045](https://linux-hardware.org/?probe=bf8f795045) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [df9818b791](https://linux-hardware.org/?probe=df9818b791) | Aug 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [5247fcf1af](https://linux-hardware.org/?probe=5247fcf1af) | Aug 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1f1ce97787](https://linux-hardware.org/?probe=1f1ce97787) | Aug 19, 2023 |
| Acer          | Aspire E5-575G              | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0b3bf57b84](https://linux-hardware.org/?probe=0b3bf57b84) | Aug 07, 2023 |
| Acer          | Predator PHN16-71           | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [ffb1e25ac0](https://linux-hardware.org/?probe=ffb1e25ac0) | Jul 24, 2023 |
| ASUSTek       | X45U                        | [53a411cd41](https://linux-hardware.org/?probe=53a411cd41) | Jul 23, 2023 |
| Fujitsu       | FMVNA9K3C                   | [64c67e920e](https://linux-hardware.org/?probe=64c67e920e) | Jul 20, 2023 |
| Fujitsu       | FMVNA9K3C                   | [0b0d110403](https://linux-hardware.org/?probe=0b0d110403) | Jul 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [be44ef471d](https://linux-hardware.org/?probe=be44ef471d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Acer          | Aspire E5-471G              | [c958efdb37](https://linux-hardware.org/?probe=c958efdb37) | Jul 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| NEC Comput... | PC-VK27MBZCG                | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| MSI           | Raider GE77HX 12UHS         | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| ASUSTek       | GL552VW                     | [592b7aa556](https://linux-hardware.org/?probe=592b7aa556) | Jun 21, 2023 |
| Acer          | Aspire E5-471               | [48154f868d](https://linux-hardware.org/?probe=48154f868d) | Jun 17, 2023 |
| Dell          | XPS 13 9310                 | [9cba8f7730](https://linux-hardware.org/?probe=9cba8f7730) | Jun 15, 2023 |
| Acer          | Nitro AN515-52              | [4a0de9eca8](https://linux-hardware.org/?probe=4a0de9eca8) | Jun 14, 2023 |
| Valve         | Jupiter                     | [628ee9ac88](https://linux-hardware.org/?probe=628ee9ac88) | Jun 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Acer          | Nitro AN515-52              | [1bdfa737bc](https://linux-hardware.org/?probe=1bdfa737bc) | Jun 08, 2023 |
| MECHREVO      | Code01 Ver2.0               | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | IdeaPad Z410 20292          | [3e68e53c33](https://linux-hardware.org/?probe=3e68e53c33) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [aaf53ecd65](https://linux-hardware.org/?probe=aaf53ecd65) | May 05, 2023 |
| Valve         | Jupiter                     | [206f95ee6f](https://linux-hardware.org/?probe=206f95ee6f) | May 02, 2023 |
| Dell          | XPS 15 9500                 | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| Acer          | Aspire E5-575G              | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z410 20292          | [422a85d62b](https://linux-hardware.org/?probe=422a85d62b) | Apr 03, 2023 |
| HP            | Pavilion 15                 | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Acer          | Aspire F5-573G              | [2c68190118](https://linux-hardware.org/?probe=2c68190118) | Apr 03, 2023 |
| Toshiba       | QOSMIO X70-B                | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Acer          | Aspire F5-573G              | [daf7b5a6cc](https://linux-hardware.org/?probe=daf7b5a6cc) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [06c1b9f781](https://linux-hardware.org/?probe=06c1b9f781) | Feb 20, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Acer          | Aspire A515-55G             | [7a4e781669](https://linux-hardware.org/?probe=7a4e781669) | Jan 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [40560e6bcd](https://linux-hardware.org/?probe=40560e6bcd) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [22b5c66553](https://linux-hardware.org/?probe=22b5c66553) | Jan 12, 2023 |
| Lenovo        | IdeaPad 300S-11IBR 80KU     | [6335e974a1](https://linux-hardware.org/?probe=6335e974a1) | Jan 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | [9c9e1b06f9](https://linux-hardware.org/?probe=9c9e1b06f9) | Jan 07, 2023 |
| Acer          | Aspire V3-571G              | [67103caf92](https://linux-hardware.org/?probe=67103caf92) | Jan 07, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Dell          | G3 3579                     | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ac449d25f](https://linux-hardware.org/?probe=2ac449d25f) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [af31550cae](https://linux-hardware.org/?probe=af31550cae) | Nov 27, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7c284b1dfd](https://linux-hardware.org/?probe=7c284b1dfd) | Oct 20, 2022 |
| Acer          | Swift SFX14-41G             | [7c689396eb](https://linux-hardware.org/?probe=7c689396eb) | Oct 19, 2022 |
| Acer          | Swift SFX14-41G             | [357ad9257d](https://linux-hardware.org/?probe=357ad9257d) | Oct 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| Acer          | Aspire E5-575G              | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop                      | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| Timi          | TM1701                      | [59153cc5fe](https://linux-hardware.org/?probe=59153cc5fe) | Sep 27, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Acer          | TravelMate P653-M           | [c0fcc47188](https://linux-hardware.org/?probe=c0fcc47188) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [65f638768e](https://linux-hardware.org/?probe=65f638768e) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [0008869bb6](https://linux-hardware.org/?probe=0008869bb6) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [c0e9a2e062](https://linux-hardware.org/?probe=c0e9a2e062) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [51a98d93a6](https://linux-hardware.org/?probe=51a98d93a6) | Aug 20, 2022 |
| Acer          | Aspire V3-771               | [dc65bd0f38](https://linux-hardware.org/?probe=dc65bd0f38) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Unknown       | Unknown                     | [5cdd2332d5](https://linux-hardware.org/?probe=5cdd2332d5) | Aug 14, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [1b9f19b21e](https://linux-hardware.org/?probe=1b9f19b21e) | Aug 13, 2022 |
| Acer          | Aspire E5-575G              | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Acer          | TravelMate P643-M           | [33254cfb1e](https://linux-hardware.org/?probe=33254cfb1e) | Aug 03, 2022 |
| HP            | Stream Notebook PC 13       | [d736692861](https://linux-hardware.org/?probe=d736692861) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| Acer          | TravelMate P643-M           | [0357bf32d7](https://linux-hardware.org/?probe=0357bf32d7) | Jul 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [cfa0dde1d0](https://linux-hardware.org/?probe=cfa0dde1d0) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| MSI           | GE76 Raider 10UH            | [77ef5acb4c](https://linux-hardware.org/?probe=77ef5acb4c) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| Unknown       | Unknown                     | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| Dell          | Latitude 3120               | [c5c6eed0d9](https://linux-hardware.org/?probe=c5c6eed0d9) | Jun 14, 2022 |
| Acer          | Aspire F5-573G              | [fd7d146eb1](https://linux-hardware.org/?probe=fd7d146eb1) | Jun 08, 2022 |
| Apple         | MacBookPro11,1              | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| Acer          | One Z1402                   | [4278b806cf](https://linux-hardware.org/?probe=4278b806cf) | May 31, 2022 |
| ASUSTek       | S400CA                      | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| Dell          | Latitude 3120               | [e97cf58459](https://linux-hardware.org/?probe=e97cf58459) | May 23, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8949bc2cf8](https://linux-hardware.org/?probe=8949bc2cf8) | May 22, 2022 |
| Acer          | One Z1402                   | [ae69c0fdbd](https://linux-hardware.org/?probe=ae69c0fdbd) | May 21, 2022 |
| Dell          | Inspiron 7559               | [90bfbc9f6b](https://linux-hardware.org/?probe=90bfbc9f6b) | May 16, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJS... | [fb11780c46](https://linux-hardware.org/?probe=fb11780c46) | May 07, 2022 |
| ASUSTek       | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP            | Pro Tablet 608 G1           | [a8b97ee7cf](https://linux-hardware.org/?probe=a8b97ee7cf) | Apr 25, 2022 |
| Acer          | Aspire A515-45              | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| ASUSTek       | FX503VD                     | [218e8b7d2a](https://linux-hardware.org/?probe=218e8b7d2a) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| Acer          | Aspire E5-471G              | [a7179e1ba3](https://linux-hardware.org/?probe=a7179e1ba3) | Apr 16, 2022 |
| Framework     | Laptop                      | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Dell          | Latitude 3120               | [c0df9a1ac0](https://linux-hardware.org/?probe=c0df9a1ac0) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell          | Latitude 3120               | [69b7d6b1a3](https://linux-hardware.org/?probe=69b7d6b1a3) | Mar 26, 2022 |
| Dell          | Latitude 3120               | [78ae48c482](https://linux-hardware.org/?probe=78ae48c482) | Mar 26, 2022 |
| Acer          | Aspire E5-571               | [c2f6faf193](https://linux-hardware.org/?probe=c2f6faf193) | Mar 06, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| Acer          | AOA150                      | [aeb35f9f12](https://linux-hardware.org/?probe=aeb35f9f12) | Feb 13, 2022 |
| Acer          | AOA150                      | [7d493dd5d5](https://linux-hardware.org/?probe=7d493dd5d5) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1488d5e773](https://linux-hardware.org/?probe=1488d5e773) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| Dell          | Vostro 5471                 | [c90234250e](https://linux-hardware.org/?probe=c90234250e) | Jan 31, 2022 |
| Lenovo        | ThinkPad P50 20EQS2AB00     | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [31f48cd25e](https://linux-hardware.org/?probe=31f48cd25e) | Jan 19, 2022 |
| ASUSTek       | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2e71480673](https://linux-hardware.org/?probe=2e71480673) | Dec 24, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Toshiba       | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| Dell          | Vostro 5471                 | [4083699145](https://linux-hardware.org/?probe=4083699145) | Nov 14, 2021 |
| MSI           | Prestige 15 A10SC           | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| Dell          | Inspiron N5010              | [d1b6520785](https://linux-hardware.org/?probe=d1b6520785) | Nov 13, 2021 |
| HP            | EliteBook 6930p (FL488AW... | [af8e63842a](https://linux-hardware.org/?probe=af8e63842a) | Oct 28, 2021 |
| Acer          | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1193264475](https://linux-hardware.org/?probe=1193264475) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [514642d183](https://linux-hardware.org/?probe=514642d183) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [e4fb99f5b8](https://linux-hardware.org/?probe=e4fb99f5b8) | Sep 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| Dell          | Latitude D630               | [3af0cdbc54](https://linux-hardware.org/?probe=3af0cdbc54) | Sep 09, 2021 |
| Acer          | Aspire V3-575G              | [28e06e0c2b](https://linux-hardware.org/?probe=28e06e0c2b) | Aug 28, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8e060f6c6c](https://linux-hardware.org/?probe=8e060f6c6c) | Aug 23, 2021 |
| Acer          | Aspire E5-471G              | [7f7c5133ad](https://linux-hardware.org/?probe=7f7c5133ad) | Aug 18, 2021 |
| Fujitsu       | LIFEBOOK A357               | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Acer          | Aspire E5-475G              | [65ad8ece4a](https://linux-hardware.org/?probe=65ad8ece4a) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| Acer          | Aspire E5-471G              | [bde4a22e40](https://linux-hardware.org/?probe=bde4a22e40) | Jul 19, 2021 |
| Acer          | Nitro AN515-55              | [5c7365be9d](https://linux-hardware.org/?probe=5c7365be9d) | Jul 16, 2021 |
| Dell          | Vostro 3578                 | [f5bfb0ada6](https://linux-hardware.org/?probe=f5bfb0ada6) | Jul 09, 2021 |
| Dell          | Vostro 3578                 | [e69ebc683f](https://linux-hardware.org/?probe=e69ebc683f) | Jul 09, 2021 |
| Acer          | Aspire ES1-111M             | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| HP            | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| ASUSTek       | X450LN                      | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| Lenovo        | B50-80 80LT                 | [ef615e10ea](https://linux-hardware.org/?probe=ef615e10ea) | May 27, 2021 |
| ASUSTek       | X450LN                      | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| Toshiba       | Satellite L645              | [a3c061e392](https://linux-hardware.org/?probe=a3c061e392) | May 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0d99884dcd](https://linux-hardware.org/?probe=0d99884dcd) | May 17, 2021 |
| Dell          | Inspiron 7501               | [e8e3c50f4b](https://linux-hardware.org/?probe=e8e3c50f4b) | May 16, 2021 |
| Dell          | Latitude 3410               | [b29d7ddfe8](https://linux-hardware.org/?probe=b29d7ddfe8) | May 09, 2021 |
| Dell          | Latitude E6430              | [1a7d88c72a](https://linux-hardware.org/?probe=1a7d88c72a) | May 04, 2021 |
| Dell          | Latitude E6430              | [7b00c56952](https://linux-hardware.org/?probe=7b00c56952) | May 02, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Acer          | Aspire ES1-111M             | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell          | Latitude 3410               | [b6748a9a7e](https://linux-hardware.org/?probe=b6748a9a7e) | Apr 25, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Dell          | G7 7590                     | [be5780df0a](https://linux-hardware.org/?probe=be5780df0a) | Mar 09, 2021 |
| Samsung       | R780/R778                   | [0c57a7241e](https://linux-hardware.org/?probe=0c57a7241e) | Feb 26, 2021 |
| ASUSTek       | E200HA                      | [1faf0b360f](https://linux-hardware.org/?probe=1faf0b360f) | Feb 19, 2021 |
| ASUSTek       | K45VM                       | [26690f314d](https://linux-hardware.org/?probe=26690f314d) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | [1b2994e7f3](https://linux-hardware.org/?probe=1b2994e7f3) | Feb 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [40bcb4aaf2](https://linux-hardware.org/?probe=40bcb4aaf2) | Feb 15, 2021 |
| Apple         | MacBookAir3,2               | [0392f08b03](https://linux-hardware.org/?probe=0392f08b03) | Feb 15, 2021 |
| Acer          | Aspire E5-471G              | [401fa9d58e](https://linux-hardware.org/?probe=401fa9d58e) | Feb 13, 2021 |
| HP            | 1000                        | [16b305a6f5](https://linux-hardware.org/?probe=16b305a6f5) | Feb 13, 2021 |
| HUAWEI        | KLVL-WXX9                   | [20b10721e2](https://linux-hardware.org/?probe=20b10721e2) | Feb 09, 2021 |
| Acer          | Aspire E5-475G              | [360e7155d7](https://linux-hardware.org/?probe=360e7155d7) | Feb 06, 2021 |
| Sony          | SVF14N25CXB                 | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [731a44edca](https://linux-hardware.org/?probe=731a44edca) | Jan 16, 2021 |
| Lenovo        | IdeaPad Y450                | [1285c5deb9](https://linux-hardware.org/?probe=1285c5deb9) | Jan 11, 2021 |
| Lenovo        | G460 20041                  | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [e28d350fac](https://linux-hardware.org/?probe=e28d350fac) | Dec 24, 2020 |
| ASUSTek       | X450CC                      | [750f666a09](https://linux-hardware.org/?probe=750f666a09) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RES51Y00     | [66b1afc07c](https://linux-hardware.org/?probe=66b1afc07c) | Dec 15, 2020 |
| Dell          | Inspiron 5468               | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| MSI           | PE70 6QE                    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Acer          | Aspire E5-475G              | [53a62697ed](https://linux-hardware.org/?probe=53a62697ed) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | [719a24bc0f](https://linux-hardware.org/?probe=719a24bc0f) | Nov 30, 2020 |
| MSI           | PE70 6QE                    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| Acer          | Aspire VN7-793G             | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| Dell          | G5 5590                     | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| MSI           | GE75 Raider 10SGS           | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell          | G5 5590                     | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| HP            | Laptop 14-bs0xx             | [f90473f671](https://linux-hardware.org/?probe=f90473f671) | Nov 16, 2020 |
| HP            | Laptop 14-bs0xx             | [bf8d99074a](https://linux-hardware.org/?probe=bf8d99074a) | Nov 15, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Hampoo        | Unknown                     | [b713cd21d1](https://linux-hardware.org/?probe=b713cd21d1) | Oct 24, 2020 |
| Hampoo        | Unknown                     | [03640b9aac](https://linux-hardware.org/?probe=03640b9aac) | Oct 24, 2020 |
| MSI           | PE70 6QE                    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| Dell          | Precision 7740              | [814a0ec705](https://linux-hardware.org/?probe=814a0ec705) | Oct 15, 2020 |
| MSI           | PE70 6QE                    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| HP            | Pavilion dv7                | [058179daf5](https://linux-hardware.org/?probe=058179daf5) | Sep 24, 2020 |
| HP            | Pavilion dv6                | [acce68d947](https://linux-hardware.org/?probe=acce68d947) | Sep 09, 2020 |
| Dell          | Inspiron 5447               | [9fc26445da](https://linux-hardware.org/?probe=9fc26445da) | Sep 03, 2020 |
| Dell          | Inspiron 5447               | [fd56e29478](https://linux-hardware.org/?probe=fd56e29478) | Sep 03, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [e55f750fc2](https://linux-hardware.org/?probe=e55f750fc2) | Sep 02, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [cc7e35217e](https://linux-hardware.org/?probe=cc7e35217e) | Sep 02, 2020 |
| Acer          | Aspire VN7-792G             | [706847f6cd](https://linux-hardware.org/?probe=706847f6cd) | Aug 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| ASUSTek       | X411UN                      | [212932d80d](https://linux-hardware.org/?probe=212932d80d) | Jul 27, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Acer          | Swift SF314-57G             | [c74653b694](https://linux-hardware.org/?probe=c74653b694) | Jul 15, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Acer          | Aspire VN7-792G             | [405d399549](https://linux-hardware.org/?probe=405d399549) | Jul 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Acer          | Aspire A315-42              | [7c061a0688](https://linux-hardware.org/?probe=7c061a0688) | Jul 06, 2020 |
| Acer          | Aspire VN7-792G             | [1457f6e3b5](https://linux-hardware.org/?probe=1457f6e3b5) | Jul 04, 2020 |
| Fujitsu       | LIFEBOOK BH531              | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [adc28756a8](https://linux-hardware.org/?probe=adc28756a8) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [6e947dfc9d](https://linux-hardware.org/?probe=6e947dfc9d) | Jun 27, 2020 |
| ASUSTek       | K42JB                       | [5f87f39c75](https://linux-hardware.org/?probe=5f87f39c75) | Jun 27, 2020 |
| MSI           | MS-14Y1                     | [c585b33393](https://linux-hardware.org/?probe=c585b33393) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | [8d0c93ef24](https://linux-hardware.org/?probe=8d0c93ef24) | Jun 17, 2020 |
| MSI           | MS-14Y1                     | [657c6d539f](https://linux-hardware.org/?probe=657c6d539f) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| ASUSTek       | K53SV                       | [0bb72c8f71](https://linux-hardware.org/?probe=0bb72c8f71) | Jun 01, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [645ef14cb4](https://linux-hardware.org/?probe=645ef14cb4) | May 21, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4827cdc9b5](https://linux-hardware.org/?probe=4827cdc9b5) | May 21, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [338493712f](https://linux-hardware.org/?probe=338493712f) | May 19, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [17f5a0932c](https://linux-hardware.org/?probe=17f5a0932c) | May 19, 2020 |
| Samsung       | RV418/RV518/RV718           | [ff8f525d6b](https://linux-hardware.org/?probe=ff8f525d6b) | May 18, 2020 |
| Lenovo        | G480 20156                  | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo        | G480 20156                  | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Acer          | Nitro AN515-42              | [5c659d6268](https://linux-hardware.org/?probe=5c659d6268) | May 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [f286a38265](https://linux-hardware.org/?probe=f286a38265) | Apr 30, 2020 |
| Lenovo        | Y50-70 20378                | [bbd3e36751](https://linux-hardware.org/?probe=bbd3e36751) | Apr 16, 2020 |
| Lenovo        | Y50-70 20378                | [8bca0c818d](https://linux-hardware.org/?probe=8bca0c818d) | Apr 16, 2020 |
| Lenovo        | ThinkPad T420 4180JH1       | [4d0e9109bb](https://linux-hardware.org/?probe=4d0e9109bb) | Mar 21, 2020 |
| Samsung       | NC208/NC108                 | [d577b178a1](https://linux-hardware.org/?probe=d577b178a1) | Mar 06, 2020 |
| Samsung       | NC208/NC108                 | [cc28243d3d](https://linux-hardware.org/?probe=cc28243d3d) | Mar 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [626f7fb341](https://linux-hardware.org/?probe=626f7fb341) | Feb 29, 2020 |
| Acer          | Predator PH315-51           | [b3edf8c190](https://linux-hardware.org/?probe=b3edf8c190) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | [8d16cc2992](https://linux-hardware.org/?probe=8d16cc2992) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | [ffbfac004c](https://linux-hardware.org/?probe=ffbfac004c) | Feb 23, 2020 |
| Dell          | Precision 5510              | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [ac7b752d68](https://linux-hardware.org/?probe=ac7b752d68) | Feb 13, 2020 |
| HP            | Compaq 15                   | [e8597ab3e4](https://linux-hardware.org/?probe=e8597ab3e4) | Feb 06, 2020 |
| MSI           | X460/X460DX                 | [faf3829102](https://linux-hardware.org/?probe=faf3829102) | Feb 04, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [670b5a0247](https://linux-hardware.org/?probe=670b5a0247) | Dec 27, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [fc21e1c322](https://linux-hardware.org/?probe=fc21e1c322) | Dec 18, 2019 |
| Lenovo        | ThinkPad P50 20EQS5XE00     | [65dc93e325](https://linux-hardware.org/?probe=65dc93e325) | Dec 18, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Fujitsu       | LIFEBOOK BH531              | [c00057fc87](https://linux-hardware.org/?probe=c00057fc87) | Dec 01, 2019 |
| Clevo         | M540SR VT6363A              | [97181c941c](https://linux-hardware.org/?probe=97181c941c) | Nov 23, 2019 |
| Fujitsu       | LIFEBOOK BH531              | [0223eca896](https://linux-hardware.org/?probe=0223eca896) | Nov 22, 2019 |
| Lenovo        | G710 20252                  | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo        | G710 20252                  | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [b65742b189](https://linux-hardware.org/?probe=b65742b189) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [6ccf378246](https://linux-hardware.org/?probe=6ccf378246) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [29d4434f82](https://linux-hardware.org/?probe=29d4434f82) | Oct 26, 2019 |
| HP            | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| Acer          | Swift SF113-31              | [a37935b2e0](https://linux-hardware.org/?probe=a37935b2e0) | Sep 27, 2019 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [ccf2eacdd1](https://linux-hardware.org/?probe=ccf2eacdd1) | Sep 14, 2019 |
| Acer          | Aspire E5-552G              | [5c4bd87bc9](https://linux-hardware.org/?probe=5c4bd87bc9) | Sep 04, 2019 |
| Dell          | Vostro 3458                 | [a62197181c](https://linux-hardware.org/?probe=a62197181c) | Sep 04, 2019 |
| Lenovo        | G460 20041                  | [7b5945bfc2](https://linux-hardware.org/?probe=7b5945bfc2) | Aug 31, 2019 |
| HP            | Laptop 15-db0xxx            | [2d5f51cdd8](https://linux-hardware.org/?probe=2d5f51cdd8) | Aug 23, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [fe49019be0](https://linux-hardware.org/?probe=fe49019be0) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [7551b403e2](https://linux-hardware.org/?probe=7551b403e2) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [ef69a20f15](https://linux-hardware.org/?probe=ef69a20f15) | Aug 07, 2019 |
| HP            | ENVY Laptop ah0xxx          | [defe18c4c3](https://linux-hardware.org/?probe=defe18c4c3) | Jul 09, 2019 |
| Dell          | Latitude E6430              | [c8334c6a31](https://linux-hardware.org/?probe=c8334c6a31) | Jun 22, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [26db49d8f2](https://linux-hardware.org/?probe=26db49d8f2) | Jun 19, 2019 |
| Lenovo        | G460 20041                  | [62697bf35b](https://linux-hardware.org/?probe=62697bf35b) | Jun 16, 2019 |
| Acer          | Aspire A315-21              | [6d4aebc3ef](https://linux-hardware.org/?probe=6d4aebc3ef) | May 22, 2019 |
| Acer          | Aspire A315-21              | [f878e784e2](https://linux-hardware.org/?probe=f878e784e2) | May 04, 2019 |
| ASUSTek       | X556UQK                     | [d906d6357c](https://linux-hardware.org/?probe=d906d6357c) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [63a8e04d9e](https://linux-hardware.org/?probe=63a8e04d9e) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [7d55bd0096](https://linux-hardware.org/?probe=7d55bd0096) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [6648050a69](https://linux-hardware.org/?probe=6648050a69) | May 01, 2019 |
| Dell          | Inspiron 14-3467            | [9b390a3c82](https://linux-hardware.org/?probe=9b390a3c82) | Apr 11, 2019 |
| Dell          | Inspiron 14-3467            | [7f1e85018c](https://linux-hardware.org/?probe=7f1e85018c) | Apr 11, 2019 |
| Acer          | Aspire 4750                 | [94d50c8e16](https://linux-hardware.org/?probe=94d50c8e16) | Mar 26, 2019 |
| Apple         | MacBookAir3,2               | [ee6b3b0da4](https://linux-hardware.org/?probe=ee6b3b0da4) | Jan 29, 2019 |
| HP            | Compaq nx6325 (EQ422AV)     | [410fe4b520](https://linux-hardware.org/?probe=410fe4b520) | Dec 21, 2018 |
| HP            | Compaq nx6325 (EQ422AV)     | [1697d0f3f4](https://linux-hardware.org/?probe=1697d0f3f4) | Dec 21, 2018 |
| Acer          | Aspire 4741                 | [0875804f8d](https://linux-hardware.org/?probe=0875804f8d) | Nov 22, 2018 |
| Acer          | Aspire 4741                 | [d2f2af2cb2](https://linux-hardware.org/?probe=d2f2af2cb2) | Nov 13, 2018 |
| Lenovo        | G40-45 80E1                 | [ebf69568bf](https://linux-hardware.org/?probe=ebf69568bf) | Oct 29, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 29        | 9.45%   |
| Ubuntu 22.04                 | 20        | 6.51%   |
| Pop!_OS 22.04                | 14        | 4.56%   |
| Arch Rolling                 | 12        | 3.91%   |
| Debian 11                    | 11        | 3.58%   |
| OpenMandriva 4.2             | 9         | 2.93%   |
| Ubuntu 18.04                 | 8         | 2.61%   |
| KDE neon 20.04               | 8         | 2.61%   |
| Fedora 38                    | 7         | 2.28%   |
| OpenMandriva 23.08           | 6         | 1.95%   |
| Fedora 37                    | 6         | 1.95%   |
| Linux Mint 21                | 5         | 1.63%   |
| KDE neon 22.04               | 5         | 1.63%   |
| Fedora 39                    | 5         | 1.63%   |
| Debian 10                    | 5         | 1.63%   |
| Arch                         | 5         | 1.63%   |
| Zorin 16                     | 4         | 1.3%    |
| Ubuntu 19.10                 | 4         | 1.3%    |
| Ubuntu 19.04                 | 4         | 1.3%    |
| OpenMandriva 23.01           | 4         | 1.3%    |
| Linux Mint 20.2              | 4         | 1.3%    |
| Zorin 15                     | 3         | 0.98%   |
| Xero Rolling                 | 3         | 0.98%   |
| Ubuntu 18.10                 | 3         | 0.98%   |
| Ubuntu 16.04                 | 3         | 0.98%   |
| Pop!_OS 21.04                | 3         | 0.98%   |
| OpenMandriva 4.3             | 3         | 0.98%   |
| Linux Mint 19.2              | 3         | 0.98%   |
| Kubuntu 22.04                | 3         | 0.98%   |
| Kubuntu 20.04                | 3         | 0.98%   |
| Fedora 36                    | 3         | 0.98%   |
| Debian Testing               | 3         | 0.98%   |
| ArcoLinux Rolling            | 3         | 0.98%   |
| Xubuntu 20.04                | 2         | 0.65%   |
| Xubuntu 18.04                | 2         | 0.65%   |
| Ubuntu MATE 22.04            | 2         | 0.65%   |
| Ubuntu MATE 20.10            | 2         | 0.65%   |
| Ubuntu MATE 20.04            | 2         | 0.65%   |
| Pop!_OS 20.04                | 2         | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 72        | 24.66%  |
| Fedora       | 25        | 8.56%   |
| OpenMandriva | 23        | 7.88%   |
| Linux Mint   | 23        | 7.88%   |
| Debian       | 21        | 7.19%   |
| Pop!_OS      | 20        | 6.85%   |
| Arch         | 17        | 5.82%   |
| KDE neon     | 13        | 4.45%   |
| Zorin        | 7         | 2.4%    |
| Ubuntu MATE  | 6         | 2.05%   |
| Kubuntu      | 6         | 2.05%   |
| Endless      | 6         | 2.05%   |
| Xubuntu      | 5         | 1.71%   |
| MX           | 4         | 1.37%   |
| Elementary   | 4         | 1.37%   |
| Xero         | 3         | 1.03%   |
| openSUSE     | 3         | 1.03%   |
| Manjaro      | 3         | 1.03%   |
| Lubuntu      | 3         | 1.03%   |
| Kali         | 3         | 1.03%   |
| Clear Linux  | 3         | 1.03%   |
| ArcoLinux    | 3         | 1.03%   |
| SteamOS      | 2         | 0.68%   |
| NixOS        | 2         | 0.68%   |
| EndeavourOS  | 2         | 0.68%   |
| Void Linux   | 1         | 0.34%   |
| Ultramarine  | 1         | 0.34%   |
| UbuntuDDE    | 1         | 0.34%   |
| Ubuntu Unity | 1         | 0.34%   |
| ROSA         | 1         | 0.34%   |
| Nobara       | 1         | 0.34%   |
| Neptune OS   | 1         | 0.34%   |
| Micebuntu    | 1         | 0.34%   |
| Linux Lite   | 1         | 0.34%   |
| Lilidog      | 1         | 0.34%   |
| Garuda Linux | 1         | 0.34%   |
| BlackPanther | 1         | 0.34%   |
| Archcraft    | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 9         | 2.59%   |
| 6.4.11-desktop-1omv2390  | 6         | 1.73%   |
| 5.15.0-46-generic        | 5         | 1.44%   |
| 6.1.1-desktop-1omv2290   | 4         | 1.15%   |
| 5.15.0-58-generic        | 4         | 1.15%   |
| 6.0.6-76060006-generic   | 3         | 0.86%   |
| 6.0.12-76060006-generic  | 3         | 0.86%   |
| 5.8.0-50-generic         | 3         | 0.86%   |
| 5.4.0-42-generic         | 3         | 0.86%   |
| 5.3.0-28-generic         | 3         | 0.86%   |
| 5.19.0-43-generic        | 3         | 0.86%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.86%   |
| 5.11.0-40-generic        | 3         | 0.86%   |
| 5.10.0-21-amd64          | 3         | 0.86%   |
| 5.0.0-32-generic         | 3         | 0.86%   |
| 5.0.0-27-generic         | 3         | 0.86%   |
| 4.18.0-15-generic        | 3         | 0.86%   |
| 6.6.6-76060606-generic   | 2         | 0.58%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.58%   |
| 6.5.9-arch2-1            | 2         | 0.58%   |
| 6.5.6-300.fc39.x86_64    | 2         | 0.58%   |
| 6.5.5-arch1-1            | 2         | 0.58%   |
| 6.5.4-arch2-1            | 2         | 0.58%   |
| 6.5.0-21-generic         | 2         | 0.58%   |
| 6.2.0-34-generic         | 2         | 0.58%   |
| 6.1.11-200.fc37.x86_64   | 2         | 0.58%   |
| 5.8.14-arch1-1           | 2         | 0.58%   |
| 5.8.0-59-generic         | 2         | 0.58%   |
| 5.8.0-29-generic         | 2         | 0.58%   |
| 5.4.0-81-generic         | 2         | 0.58%   |
| 5.4.0-73-generic         | 2         | 0.58%   |
| 5.4.0-58-generic         | 2         | 0.58%   |
| 5.4.0-40-generic         | 2         | 0.58%   |
| 5.4.0-39-generic         | 2         | 0.58%   |
| 5.4.0-31-generic         | 2         | 0.58%   |
| 5.3.0-20-generic         | 2         | 0.58%   |
| 5.19.0-46-generic        | 2         | 0.58%   |
| 5.19.0-38-generic        | 2         | 0.58%   |
| 5.19.0-32-generic        | 2         | 0.58%   |
| 5.15.0-91-generic        | 2         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 9.79%   |
| 5.15.0  | 32        | 9.5%    |
| 5.13.0  | 14        | 4.15%   |
| 5.8.0   | 13        | 3.86%   |
| 4.15.0  | 13        | 3.86%   |
| 5.19.0  | 11        | 3.26%   |
| 5.11.0  | 11        | 3.26%   |
| 5.3.0   | 10        | 2.97%   |
| 6.2.0   | 9         | 2.67%   |
| 5.10.14 | 9         | 2.67%   |
| 5.0.0   | 9         | 2.67%   |
| 6.4.11  | 8         | 2.37%   |
| 5.10.0  | 8         | 2.37%   |
| 4.19.0  | 7         | 2.08%   |
| 4.18.0  | 7         | 2.08%   |
| 6.5.0   | 5         | 1.48%   |
| 6.1.1   | 5         | 1.48%   |
| 6.1.0   | 4         | 1.19%   |
| 6.0.12  | 4         | 1.19%   |
| 6.5.9   | 3         | 0.89%   |
| 6.5.5   | 3         | 0.89%   |
| 6.0.6   | 3         | 0.89%   |
| 5.16.7  | 3         | 0.89%   |
| 6.6.6   | 2         | 0.59%   |
| 6.6.2   | 2         | 0.59%   |
| 6.5.6   | 2         | 0.59%   |
| 6.5.4   | 2         | 0.59%   |
| 6.4.7   | 2         | 0.59%   |
| 6.2.9   | 2         | 0.59%   |
| 6.2.15  | 2         | 0.59%   |
| 6.1.12  | 2         | 0.59%   |
| 6.1.11  | 2         | 0.59%   |
| 6.0.0   | 2         | 0.59%   |
| 5.8.14  | 2         | 0.59%   |
| 5.18.0  | 2         | 0.59%   |
| 5.17.5  | 2         | 0.59%   |
| 5.17.0  | 2         | 0.59%   |
| 5.16.0  | 2         | 0.59%   |
| 5.12.0  | 2         | 0.59%   |
| 6.8.7   | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 36        | 10.94%  |
| 5.4     | 35        | 10.64%  |
| 5.10    | 20        | 6.08%   |
| 6.2     | 19        | 5.78%   |
| 6.5     | 17        | 5.17%   |
| 5.8     | 16        | 4.86%   |
| 5.19    | 16        | 4.86%   |
| 5.13    | 16        | 4.86%   |
| 6.1     | 15        | 4.56%   |
| 6.4     | 13        | 3.95%   |
| 4.15    | 13        | 3.95%   |
| 6.0     | 12        | 3.65%   |
| 5.3     | 11        | 3.34%   |
| 5.11    | 11        | 3.34%   |
| 6.6     | 10        | 3.04%   |
| 5.16    | 10        | 3.04%   |
| 5.0     | 9         | 2.74%   |
| 4.18    | 8         | 2.43%   |
| 4.19    | 7         | 2.13%   |
| 6.8     | 5         | 1.52%   |
| 6.3     | 5         | 1.52%   |
| 5.18    | 5         | 1.52%   |
| 5.17    | 4         | 1.22%   |
| 5.12    | 4         | 1.22%   |
| 6.7     | 3         | 0.91%   |
| 5.9     | 3         | 0.91%   |
| 5.6     | 3         | 0.91%   |
| 5.5     | 2         | 0.61%   |
| 5.7     | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 280       | 98.94%  |
| i686   | 3         | 1.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 130       | 43.19%  |
| KDE5             | 58        | 19.27%  |
| Unknown          | 31        | 10.3%   |
| X-Cinnamon       | 21        | 6.98%   |
| XFCE             | 18        | 5.98%   |
| KDE              | 8         | 2.66%   |
| MATE             | 7         | 2.33%   |
| Pantheon         | 4         | 1.33%   |
| LXQt             | 4         | 1.33%   |
| Unity            | 2         | 0.66%   |
| sway             | 2         | 0.66%   |
| KDE6             | 2         | 0.66%   |
| i3               | 2         | 0.66%   |
| Budgie           | 2         | 0.66%   |
| XFCE:GNOME:      | 1         | 0.33%   |
| TOS:GNOME        | 1         | 0.33%   |
| openbox          | 1         | 0.33%   |
| LXDE             | 1         | 0.33%   |
| lightdm-xsession | 1         | 0.33%   |
| Hyprland         | 1         | 0.33%   |
| GNOME Classic    | 1         | 0.33%   |
| Deepin           | 1         | 0.33%   |
| Cinnamon         | 1         | 0.33%   |
| awesome          | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 203       | 68.81%  |
| Wayland | 73        | 24.75%  |
| Unknown | 16        | 5.42%   |
| Tty     | 3         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 139       | 46.8%   |
| SDDM    | 50        | 16.84%  |
| GDM     | 35        | 11.78%  |
| GDM3    | 34        | 11.45%  |
| LightDM | 31        | 10.44%  |
| TDM     | 6         | 2.02%   |
| XDM     | 1         | 0.34%   |
| Ly      | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 205       | 71.68%  |
| Unknown | 30        | 10.49%  |
| th_TH   | 10        | 3.5%    |
| en_GB   | 10        | 3.5%    |
| de_DE   | 8         | 2.8%    |
| fr_FR   | 5         | 1.75%   |
| en_SG   | 5         | 1.75%   |
| C       | 5         | 1.75%   |
| ru_RU   | 3         | 1.05%   |
| en_AU   | 2         | 0.7%    |
| zh_CN   | 1         | 0.35%   |
| es_MX   | 1         | 0.35%   |
| en_DK   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 174       | 60.84%  |
| BIOS | 112       | 39.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 210       | 72.16%  |
| Btrfs   | 38        | 13.06%  |
| Overlay | 23        | 7.9%    |
| Tmpfs   | 10        | 3.44%   |
| Unknown | 6         | 2.06%   |
| Zfs     | 3         | 1.03%   |
| Xfs     | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 138       | 47.42%  |
| GPT     | 137       | 47.08%  |
| MBR     | 16        | 5.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 251       | 86.85%  |
| Yes       | 38        | 13.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 68.73%  |
| Yes       | 91        | 31.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 63        | 22.26%  |
| ASUSTek Computer               | 52        | 18.37%  |
| Acer                           | 45        | 15.9%   |
| Hewlett-Packard                | 33        | 11.66%  |
| Dell                           | 26        | 9.19%   |
| MSI                            | 13        | 4.59%   |
| Apple                          | 10        | 3.53%   |
| HUAWEI                         | 8         | 2.83%   |
| Samsung Electronics            | 6         | 2.12%   |
| Fujitsu                        | 5         | 1.77%   |
| Toshiba                        | 4         | 1.41%   |
| Valve                          | 2         | 0.71%   |
| Infinix                        | 2         | 0.71%   |
| Timi                           | 1         | 0.35%   |
| Sony                           | 1         | 0.35%   |
| SmbiosType1_SystemManufacturer | 1         | 0.35%   |
| Razer                          | 1         | 0.35%   |
| Notebook                       | 1         | 0.35%   |
| NEC Computers                  | 1         | 0.35%   |
| MicroByte                      | 1         | 0.35%   |
| MECHREVO                       | 1         | 0.35%   |
| Hampoo                         | 1         | 0.35%   |
| Gigabyte Technology            | 1         | 0.35%   |
| Framework                      | 1         | 0.35%   |
| Foxconn                        | 1         | 0.35%   |
| Clevo                          | 1         | 0.35%   |
| Unknown                        | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HUAWEI BOHB-WAX9                                             | 3         | 1.06%   |
| Acer Aspire E5-471G                                          | 3         | 1.06%   |
| Valve Jupiter                                                | 2         | 0.71%   |
| Samsung NC208/NC108                                          | 2         | 0.71%   |
| MSI GF65 Thin 10UE                                           | 2         | 0.71%   |
| Lenovo Z50-70 20354                                          | 2         | 0.71%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000                       | 2         | 0.71%   |
| Lenovo G460 20041                                            | 2         | 0.71%   |
| Infinix INBOOK X2                                            | 2         | 0.71%   |
| HUAWEI KLVL-WXX9                                             | 2         | 0.71%   |
| HP Laptop 14-ck0xxx                                          | 2         | 0.71%   |
| Dell Latitude E6430                                          | 2         | 0.71%   |
| Dell Latitude 3120                                           | 2         | 0.71%   |
| ASUS X556UQK                                                 | 2         | 0.71%   |
| ASUS X450LN                                                  | 2         | 0.71%   |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA                     | 2         | 0.71%   |
| ASUS VivoBook_ASUSLaptop M1605XA_M1605XA                     | 2         | 0.71%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA                      | 2         | 0.71%   |
| ASUS TUF Gaming FX505DT_FX505DT                              | 2         | 0.71%   |
| Apple MacBookAir3,2                                          | 2         | 0.71%   |
| Acer Aspire F5-573G                                          | 2         | 0.71%   |
| Acer Aspire A315-21                                          | 2         | 0.71%   |
| Unknown                                                      | 2         | 0.71%   |
| Toshiba Satellite L840                                       | 1         | 0.35%   |
| Toshiba Satellite L645                                       | 1         | 0.35%   |
| Toshiba Satellite L640                                       | 1         | 0.35%   |
| Toshiba QOSMIO X70-B                                         | 1         | 0.35%   |
| Timi TM1701                                                  | 1         | 0.35%   |
| Sony SVF14N25CXB                                             | 1         | 0.35%   |
| SmbiosType1_SystemManufacturer SmbiosType1_SystemProductName | 1         | 0.35%   |
| Samsung RV418/RV518/RV718                                    | 1         | 0.35%   |
| Samsung R780/R778                                            | 1         | 0.35%   |
| Samsung 900X3L                                               | 1         | 0.35%   |
| Samsung 300E4Z/300E5Z/300E7Z                                 | 1         | 0.35%   |
| Razer Blade 15 (2022) - RZ09-0421                            | 1         | 0.35%   |
| Notebook NV4XMB,ME,MZ                                        | 1         | 0.35%   |
| NEC Computers PC-VK27MBZCG                                   | 1         | 0.35%   |
| MSI X460/X460DX                                              | 1         | 0.35%   |
| MSI Raider GE77HX 12UHS                                      | 1         | 0.35%   |
| MSI Prestige 15 A10SC                                        | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 33        | 11.66%  |
| Acer Aspire        | 28        | 9.89%   |
| ASUS VivoBook      | 15        | 5.3%    |
| Lenovo IdeaPad     | 13        | 4.59%   |
| HP Pavilion        | 9         | 3.18%   |
| HP Laptop          | 8         | 2.83%   |
| Dell Latitude      | 8         | 2.83%   |
| Dell Inspiron      | 6         | 2.12%   |
| ASUS ZenBook       | 6         | 2.12%   |
| Acer Swift         | 6         | 2.12%   |
| ASUS TUF           | 5         | 1.77%   |
| HP EliteBook       | 4         | 1.41%   |
| Dell Vostro        | 4         | 1.41%   |
| ASUS ROG           | 4         | 1.41%   |
| Toshiba Satellite  | 3         | 1.06%   |
| Lenovo ThinkBook   | 3         | 1.06%   |
| HUAWEI BOHB-WAX9   | 3         | 1.06%   |
| HP Compaq          | 3         | 1.06%   |
| Dell Precision     | 3         | 1.06%   |
| ASUS ASUS          | 3         | 1.06%   |
| Acer TravelMate    | 3         | 1.06%   |
| Acer Nitro         | 3         | 1.06%   |
| Valve Jupiter      | 2         | 0.71%   |
| Samsung NC208      | 2         | 0.71%   |
| MSI GF65           | 2         | 0.71%   |
| MSI GF63           | 2         | 0.71%   |
| Lenovo Z50-70      | 2         | 0.71%   |
| Lenovo Legion      | 2         | 0.71%   |
| Lenovo G460        | 2         | 0.71%   |
| Infinix INBOOK     | 2         | 0.71%   |
| HUAWEI KLVL-WXX9   | 2         | 0.71%   |
| HP Stream          | 2         | 0.71%   |
| HP OMEN            | 2         | 0.71%   |
| HP ENVY            | 2         | 0.71%   |
| Fujitsu LIFEBOOK   | 2         | 0.71%   |
| Dell XPS           | 2         | 0.71%   |
| ASUS X556UQK       | 2         | 0.71%   |
| ASUS X450LN        | 2         | 0.71%   |
| Apple MacBookPro11 | 2         | 0.71%   |
| Apple MacBookAir3  | 2         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 30        | 10.6%   |
| 2020 | 30        | 10.6%   |
| 2018 | 29        | 10.25%  |
| 2019 | 22        | 7.77%   |
| 2012 | 22        | 7.77%   |
| 2015 | 20        | 7.07%   |
| 2014 | 20        | 7.07%   |
| 2022 | 16        | 5.65%   |
| 2017 | 16        | 5.65%   |
| 2016 | 16        | 5.65%   |
| 2011 | 15        | 5.3%    |
| 2013 | 11        | 3.89%   |
| 2010 | 10        | 3.53%   |
| 2023 | 9         | 3.18%   |
| 2008 | 9         | 3.18%   |
| 2009 | 4         | 1.41%   |
| 2007 | 3         | 1.06%   |
| 2006 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 283       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 249       | 87.37%  |
| Enabled  | 36        | 12.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 283       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 74        | 25.78%  |
| 3.01-4.0    | 61        | 21.25%  |
| 16.01-24.0  | 52        | 18.12%  |
| 8.01-16.0   | 51        | 17.77%  |
| 32.01-64.0  | 24        | 8.36%   |
| 24.01-32.0  | 9         | 3.14%   |
| 1.01-2.0    | 9         | 3.14%   |
| 2.01-3.0    | 3         | 1.05%   |
| 64.01-256.0 | 3         | 1.05%   |
| 0.51-1.0    | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 101       | 31.96%  |
| 2.01-3.0   | 84        | 26.58%  |
| 4.01-8.0   | 57        | 18.04%  |
| 3.01-4.0   | 45        | 14.24%  |
| 8.01-16.0  | 18        | 5.7%    |
| 0.51-1.0   | 9         | 2.85%   |
| 16.01-24.0 | 1         | 0.32%   |
| 0.01-0.5   | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 204       | 69.62%  |
| 2      | 70        | 23.89%  |
| 3      | 12        | 4.1%    |
| 0      | 4         | 1.37%   |
| 5      | 2         | 0.68%   |
| 4      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 77.11%  |
| Yes       | 65        | 22.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 74.74%  |
| No        | 72        | 25.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 279       | 97.89%  |
| No        | 6         | 2.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 238       | 82.93%  |
| No        | 49        | 17.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Thailand | 283       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Bangkok             | 135       | 43.55%  |
| Chiang Mai          | 22        | 7.1%    |
| Phuket              | 12        | 3.87%   |
| Nonthaburi          | 12        | 3.87%   |
| Khon Kaen           | 9         | 2.9%    |
| Bang Lamung         | 8         | 2.58%   |
| Nakhon Ratchasima   | 7         | 2.26%   |
| Surat Thani         | 4         | 1.29%   |
| Nakhon Pathom       | 4         | 1.29%   |
| Chon Buri           | 4         | 1.29%   |
| Ban Nong Sala       | 4         | 1.29%   |
| Surin               | 3         | 0.97%   |
| Rayong              | 3         | 0.97%   |
| Pattaya             | 3         | 0.97%   |
| Chiang Rai          | 3         | 0.97%   |
| Songkhla            | 2         | 0.65%   |
| Phayao              | 2         | 0.65%   |
| Pattani             | 2         | 0.65%   |
| Pak Kret            | 2         | 0.65%   |
| Mueang Samut Prakan | 2         | 0.65%   |
| Maha Sarakham       | 2         | 0.65%   |
| Khlong Luang        | 2         | 0.65%   |
| Hua Hin             | 2         | 0.65%   |
| Don Mot Daeng       | 2         | 0.65%   |
| Bang Bua Thong      | 2         | 0.65%   |
| Bang Bon            | 2         | 0.65%   |
| Ban Yang Sam Ton    | 2         | 0.65%   |
| Ban Sang            | 2         | 0.65%   |
| Ban Du              | 2         | 0.65%   |
| Ban Bueng           | 2         | 0.65%   |
| Yala                | 1         | 0.32%   |
| Udon Thani          | 1         | 0.32%   |
| Suan Luang          | 1         | 0.32%   |
| Si Sa Ket           | 1         | 0.32%   |
| Si Racha            | 1         | 0.32%   |
| Sattahip            | 1         | 0.32%   |
| Samut Prakan        | 1         | 0.32%   |
| Salaya              | 1         | 0.32%   |
| Ratchathewi         | 1         | 0.32%   |
| Rasi Salai          | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 59        | 70     | 16.12%  |
| Samsung Electronics         | 48        | 64     | 13.11%  |
| Seagate                     | 39        | 52     | 10.66%  |
| Toshiba                     | 28        | 35     | 7.65%   |
| SanDisk                     | 27        | 37     | 7.38%   |
| Unknown                     | 19        | 24     | 5.19%   |
| Kingston                    | 18        | 22     | 4.92%   |
| Intel                       | 18        | 20     | 4.92%   |
| SK hynix                    | 13        | 28     | 3.55%   |
| Micron Technology           | 12        | 15     | 3.28%   |
| HGST                        | 11        | 12     | 3.01%   |
| Apple                       | 7         | 7      | 1.91%   |
| Hitachi                     | 6         | 6      | 1.64%   |
| Transcend                   | 5         | 6      | 1.37%   |
| Crucial                     | 5         | 5      | 1.37%   |
| China                       | 4         | 4      | 1.09%   |
| SPCC                        | 3         | 3      | 0.82%   |
| Silicon Motion              | 3         | 6      | 0.82%   |
| Phison Electronics          | 3         | 7      | 0.82%   |
| KIOXIA                      | 3         | 5      | 0.82%   |
| Apacer                      | 3         | 3      | 0.82%   |
| Pioneer                     | 2         | 2      | 0.55%   |
| Kingston Technology Company | 2         | 2      | 0.55%   |
| Kingmax                     | 2         | 8      | 0.55%   |
| Fujitsu                     | 2         | 3      | 0.55%   |
| YMTC                        | 1         | 1      | 0.27%   |
| Yangtze Memory Technologies | 1         | 1      | 0.27%   |
| XPG                         | 1         | 1      | 0.27%   |
| USB3.0                      | 1         | 2      | 0.27%   |
| Teelkoou                    | 1         | 1      | 0.27%   |
| Team                        | 1         | 1      | 0.27%   |
| TARGET                      | 1         | 1      | 0.27%   |
| StoreJet                    | 1         | 1      | 0.27%   |
| ShiJi                       | 1         | 1      | 0.27%   |
| Realtek                     | 1         | 1      | 0.27%   |
| PNY                         | 1         | 2      | 0.27%   |
| Plextor                     | 1         | 1      | 0.27%   |
| O2 Micro                    | 1         | 1      | 0.27%   |
| LITEON                      | 1         | 2      | 0.27%   |
| Lite-On                     | 1         | 2      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                             | 7         | 1.86%   |
| Toshiba MQ04ABF100 1TB                             | 6         | 1.59%   |
| Seagate ST500LT012-1DG142 500GB                    | 6         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB                     | 6         | 1.59%   |
| Unknown MMC Card  64GB                             | 5         | 1.33%   |
| Unknown MMC Card  32GB                             | 5         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 4         | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 4         | 1.06%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 4         | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 1.06%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 1.06%   |
| HGST HTS721010A9E630 1TB                           | 4         | 1.06%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 3         | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                   | 3         | 0.8%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 3         | 0.8%    |
| WDC WD10SPZX-21Z10T0 1TB                           | 3         | 0.8%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 3         | 0.8%    |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                 | 3         | 0.8%    |
| Toshiba MQ01ABF032 320GB                           | 3         | 0.8%    |
| SK hynix HFM512GD3JX013N 512GB                     | 3         | 0.8%    |
| Seagate ST9500325AS 500GB                          | 3         | 0.8%    |
| Seagate ST1000LM049-2GH172 1TB                     | 3         | 0.8%    |
| SanDisk NVMe SSD Drive 1TB                         | 3         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 3         | 0.8%    |
| Micron 2450_MTFDKBA512TFK 512GB                    | 3         | 0.8%    |
| Kingston NVMe SSD Drive 512GB                      | 3         | 0.8%    |
| Intel SSDPEKNU512GZ 512GB                          | 3         | 0.8%    |
| HGST HTS725050A7E630 500GB                         | 3         | 0.8%    |
| Crucial CT500MX500SSD1 500GB                       | 3         | 0.8%    |
| WDC WD5000BPVT-22HXZT3 500GB                       | 2         | 0.53%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 2         | 0.53%   |
| Unknown SD/MMC/MS PRO 128GB                        | 2         | 0.53%   |
| Unknown DA4064  64GB                               | 2         | 0.53%   |
| Toshiba MK6475GSX 640GB                            | 2         | 0.53%   |
| Toshiba KBG30ZMT128G 128GB                         | 2         | 0.53%   |
| SK hynix HFS128G39TND-N210A 128GB SSD              | 2         | 0.53%   |
| Seagate ST500LM021-1KJ152 500GB                    | 2         | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.53%   |
| SanDisk Ultra II 240GB SSD                         | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 51     | 33.04%  |
| WDC                 | 29        | 32     | 25.22%  |
| Toshiba             | 23        | 28     | 20%     |
| HGST                | 11        | 12     | 9.57%   |
| Hitachi             | 6         | 6      | 5.22%   |
| Unknown             | 2         | 2      | 1.74%   |
| Samsung Electronics | 2         | 3      | 1.74%   |
| Fujitsu             | 2         | 3      | 1.74%   |
| JMicron Technology  | 1         | 1      | 0.87%   |
| Initio              | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 27     | 19.61%  |
| Samsung Electronics | 16        | 23     | 15.69%  |
| SanDisk             | 10        | 15     | 9.8%    |
| Kingston            | 9         | 12     | 8.82%   |
| Apple               | 6         | 6      | 5.88%   |
| Crucial             | 5         | 5      | 4.9%    |
| China               | 4         | 4      | 3.92%   |
| Transcend           | 3         | 4      | 2.94%   |
| SPCC                | 3         | 3      | 2.94%   |
| Intel               | 3         | 3      | 2.94%   |
| Apacer              | 3         | 3      | 2.94%   |
| SK hynix            | 2         | 2      | 1.96%   |
| Pioneer             | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 3      | 1.96%   |
| Kingmax             | 2         | 8      | 1.96%   |
| USB3.0              | 1         | 2      | 0.98%   |
| Teelkoou            | 1         | 1      | 0.98%   |
| Team                | 1         | 1      | 0.98%   |
| TARGET              | 1         | 1      | 0.98%   |
| StoreJet            | 1         | 1      | 0.98%   |
| Seagate             | 1         | 1      | 0.98%   |
| PNY                 | 1         | 2      | 0.98%   |
| Plextor             | 1         | 1      | 0.98%   |
| LITEON              | 1         | 2      | 0.98%   |
| Hikvision           | 1         | 1      | 0.98%   |
| Colorful            | 1         | 3      | 0.98%   |
| BR                  | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 122       | 175    | 35.67%  |
| HDD     | 108       | 139    | 31.58%  |
| SSD     | 92        | 137    | 26.9%   |
| MMC     | 17        | 22     | 4.97%   |
| Unknown | 3         | 3      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 264    | 53.44%  |
| NVMe | 122       | 174    | 38.13%  |
| MMC  | 17        | 22     | 5.31%   |
| SAS  | 10        | 16     | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 116       | 174    | 59.79%  |
| 0.51-1.0   | 73        | 96     | 37.63%  |
| 1.01-2.0   | 5         | 6      | 2.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 71        | 23.2%   |
| 101-250        | 67        | 21.9%   |
| 501-1000       | 46        | 15.03%  |
| 51-100         | 29        | 9.48%   |
| 1-20           | 28        | 9.15%   |
| 1001-2000      | 22        | 7.19%   |
| 21-50          | 20        | 6.54%   |
| Unknown        | 12        | 3.92%   |
| More than 3000 | 6         | 1.96%   |
| 2001-3000      | 5         | 1.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 126       | 40.65%  |
| 21-50     | 52        | 16.77%  |
| 101-250   | 40        | 12.9%   |
| 251-500   | 30        | 9.68%   |
| 51-100    | 29        | 9.35%   |
| 501-1000  | 13        | 4.19%   |
| Unknown   | 12        | 3.87%   |
| 1001-2000 | 8         | 2.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 9.09%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 2      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 3      | 4.55%   |
| USB3.0 Super Speed 240GB             | 1         | 2      | 4.55%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 4.55%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 4.55%   |
| TARGET SSD 128G                      | 1         | 1      | 4.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.55%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 4.55%   |
| SanDisk SDSSDX240GG25 240GB          | 1         | 1      | 4.55%   |
| Samsung Electronics HM160HI 160GB    | 1         | 2      | 4.55%   |
| Intel SSDSC2KF256H6 SATA 256GB       | 1         | 1      | 4.55%   |
| HGST HTS725050A7E630 500GB           | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 4.55%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 4.55%   |
| Colorful SL500 240GB SSD             | 1         | 3      | 4.55%   |
| Apple SSD SD0256F 256GB              | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 27.27%  |
| Toshiba             | 4         | 4      | 18.18%  |
| HGST                | 3         | 3      | 13.64%  |
| WDC                 | 1         | 3      | 4.55%   |
| USB3.0              | 1         | 2      | 4.55%   |
| TARGET              | 1         | 1      | 4.55%   |
| SK hynix            | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 2      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Colorful            | 1         | 3      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| Toshiba             | 4         | 4      | 26.67%  |
| HGST                | 3         | 3      | 20%     |
| WDC                 | 1         | 3      | 6.67%   |
| Samsung Electronics | 1         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 18     | 70%     |
| SSD  | 5         | 9      | 25%     |
| NVMe | 1         | 1      | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 166       | 277    | 55.33%  |
| Works    | 113       | 170    | 37.67%  |
| Malfunc  | 20        | 28     | 6.67%   |
| Failed   | 1         | 1      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 179       | 52.65%  |
| Samsung Electronics          | 37        | 10.88%  |
| AMD                          | 34        | 10%     |
| SanDisk                      | 28        | 8.24%   |
| SK hynix                     | 11        | 3.24%   |
| Kingston Technology Company  | 11        | 3.24%   |
| Micron Technology            | 10        | 2.94%   |
| Toshiba America Info Systems | 5         | 1.47%   |
| Silicon Motion               | 4         | 1.18%   |
| Nvidia                       | 4         | 1.18%   |
| Phison Electronics           | 3         | 0.88%   |
| KIOXIA                       | 3         | 0.88%   |
| Yangtze Memory Technologies  | 2         | 0.59%   |
| ADATA Technology             | 2         | 0.59%   |
| VIA Technologies             | 1         | 0.29%   |
| Transcend                    | 1         | 0.29%   |
| Shenzhen Longsys Electronics | 1         | 0.29%   |
| O2 Micro                     | 1         | 0.29%   |
| Marvell Technology Group     | 1         | 0.29%   |
| Lite-On Technology           | 1         | 0.29%   |
| Apple                        | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 33        | 9.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 6.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 5.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 5.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 4.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 2.79%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 2.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 9         | 2.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 8         | 2.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 2.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 7         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 1.96%   |
| Intel SSD 660P Series                                                            | 7         | 1.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6         | 1.68%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 1.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.12%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 4         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.12%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                            | 3         | 0.84%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 3         | 0.84%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 3         | 0.84%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 3         | 0.84%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 3         | 0.84%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                   | 3         | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.84%   |
| Intel SSD 600P Series                                                            | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.84%   |
| Yangtze Memory PC005 NVMe SSD                                                    | 2         | 0.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.56%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.56%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 2         | 0.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 190       | 55.39%  |
| NVMe | 125       | 36.44%  |
| RAID | 19        | 5.54%   |
| IDE  | 9         | 2.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 221       | 78.09%  |
| AMD    | 62        | 21.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 2.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 2.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 2.12%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.77%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.41%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 1.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.41%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.06%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.06%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 1.06%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 1.06%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 1.06%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.06%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.06%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 1.06%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.71%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.71%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.71%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 69        | 24.38%  |
| Intel Core i5           | 62        | 21.91%  |
| Other                   | 24        | 8.48%   |
| AMD Ryzen 5             | 21        | 7.42%   |
| Intel Core i3           | 17        | 6.01%   |
| Intel Core 2 Duo        | 15        | 5.3%    |
| AMD Ryzen 7             | 14        | 4.95%   |
| Intel Celeron           | 13        | 4.59%   |
| Intel Pentium           | 10        | 3.53%   |
| Intel Atom              | 7         | 2.47%   |
| AMD Ryzen 9             | 5         | 1.77%   |
| AMD Ryzen 7 PRO         | 4         | 1.41%   |
| AMD Ryzen 3             | 3         | 1.06%   |
| AMD A4                  | 3         | 1.06%   |
| Intel Pentium Silver    | 2         | 0.71%   |
| AMD E2                  | 2         | 0.71%   |
| AMD Athlon              | 2         | 0.71%   |
| AMD A10                 | 2         | 0.71%   |
| Intel Xeon              | 1         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Core m3           | 1         | 0.35%   |
| Intel Core i9           | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Ryzen 5 PRO         | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD A8                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 118       | 41.55%  |
| 4      | 103       | 36.27%  |
| 6      | 28        | 9.86%   |
| 8      | 23        | 8.1%    |
| 14     | 5         | 1.76%   |
| 16     | 3         | 1.06%   |
| 1      | 2         | 0.7%    |
| 24     | 1         | 0.35%   |
| 12     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 283       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 226       | 79.3%   |
| 1      | 59        | 20.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 278       | 98.23%  |
| Unknown        | 4         | 1.41%   |
| 32-bit         | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 37.04%  |
| 0x306a9    | 14        | 4.71%   |
| 0x40651    | 11        | 3.7%    |
| 0x206a7    | 10        | 3.37%   |
| 0x806ec    | 9         | 3.03%   |
| 0x806e9    | 9         | 3.03%   |
| 0x806c1    | 9         | 3.03%   |
| 0x806ea    | 8         | 2.69%   |
| 0x1067a    | 6         | 2.02%   |
| 0x08108102 | 6         | 2.02%   |
| 0x906ea    | 5         | 1.68%   |
| 0x506e3    | 5         | 1.68%   |
| 0x306c3    | 5         | 1.68%   |
| 0x20655    | 5         | 1.68%   |
| 0x0a50000c | 5         | 1.68%   |
| 0xa0652    | 4         | 1.35%   |
| 0x706a1    | 4         | 1.35%   |
| 0x406e3    | 4         | 1.35%   |
| 0x406c4    | 4         | 1.35%   |
| 0x406c3    | 4         | 1.35%   |
| 0x20652    | 4         | 1.35%   |
| 0x08608103 | 4         | 1.35%   |
| 0x08600106 | 4         | 1.35%   |
| 0x906e9    | 3         | 1.01%   |
| 0x906c0    | 3         | 1.01%   |
| 0x0a704103 | 3         | 1.01%   |
| 0x0a404102 | 3         | 1.01%   |
| 0x08600104 | 3         | 1.01%   |
| 0x0810100b | 3         | 1.01%   |
| 0xb06a2    | 2         | 0.67%   |
| 0x706a8    | 2         | 0.67%   |
| 0x6fd      | 2         | 0.67%   |
| 0x30678    | 2         | 0.67%   |
| 0x106ca    | 2         | 0.67%   |
| 0x08108109 | 2         | 0.67%   |
| 0x08101007 | 2         | 0.67%   |
| 0x06006704 | 2         | 0.67%   |
| 0xa0660    | 1         | 0.34%   |
| 0x90672    | 1         | 0.34%   |
| 0x706e5    | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 18.37%  |
| Haswell          | 25        | 8.83%   |
| Unknown          | 21        | 7.42%   |
| Skylake          | 19        | 6.71%   |
| IvyBridge        | 18        | 6.36%   |
| SandyBridge      | 13        | 4.59%   |
| Zen+             | 12        | 4.24%   |
| TigerLake        | 12        | 4.24%   |
| Silvermont       | 12        | 4.24%   |
| CometLake        | 12        | 4.24%   |
| Penryn           | 11        | 3.89%   |
| Zen 2            | 10        | 3.53%   |
| Zen 3            | 9         | 3.18%   |
| Westmere         | 9         | 3.18%   |
| Goldmont plus    | 7         | 2.47%   |
| Zen              | 5         | 1.77%   |
| Core             | 5         | 1.77%   |
| Alderlake Hybrid | 5         | 1.77%   |
| IceLake          | 4         | 1.41%   |
| Broadwell        | 4         | 1.41%   |
| Tremont          | 3         | 1.06%   |
| Excavator        | 3         | 1.06%   |
| Bonnell          | 3         | 1.06%   |
| Puma             | 2         | 0.71%   |
| Goldmont         | 2         | 0.71%   |
| Bobcat           | 2         | 0.71%   |
| Piledriver       | 1         | 0.35%   |
| K8 Hammer        | 1         | 0.35%   |
| Jaguar           | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 200       | 50.38%  |
| Nvidia           | 118       | 29.72%  |
| AMD              | 77        | 19.4%   |
| VIA Technologies | 1         | 0.25%   |
| ATI Technologies | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 3.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.94%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.7%    |
| Intel HD Graphics 620                                                                    | 11        | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 2.45%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 10        | 2.45%   |
| Intel HD Graphics 530                                                                    | 9         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.72%   |
| AMD Lucienne                                                                             | 7         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.47%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.23%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.23%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.98%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.98%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.98%   |
| Intel HD Graphics 630                                                                    | 4         | 0.98%   |
| AMD Rembrandt [Radeon 680M]                                                              | 4         | 0.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.74%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.74%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 97        | 34.28%  |
| Intel + Nvidia     | 88        | 31.1%   |
| 1 x AMD            | 49        | 17.31%  |
| 1 x Nvidia         | 16        | 5.65%   |
| AMD + Nvidia       | 12        | 4.24%   |
| Intel + AMD        | 10        | 3.53%   |
| 2 x AMD            | 7         | 2.47%   |
| Intel + 2 x Nvidia | 2         | 0.71%   |
| 2 x Intel          | 1         | 0.35%   |
| 1 x VIA            | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 228       | 77.55%  |
| Proprietary | 59        | 20.07%  |
| Unknown     | 7         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 58.08%  |
| 1.01-2.0   | 36        | 12.37%  |
| 0.01-0.5   | 34        | 11.68%  |
| 3.01-4.0   | 32        | 11%     |
| 0.51-1.0   | 13        | 4.47%   |
| 5.01-6.0   | 4         | 1.37%   |
| 8.01-16.0  | 2         | 0.69%   |
| 7.01-8.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 20.85%  |
| Chimei Innolux          | 51        | 15.41%  |
| BOE                     | 40        | 12.08%  |
| Samsung Electronics     | 36        | 10.88%  |
| LG Display              | 36        | 10.88%  |
| Dell                    | 14        | 4.23%   |
| PANDA                   | 11        | 3.32%   |
| Apple                   | 10        | 3.02%   |
| Goldstar                | 8         | 2.42%   |
| Sharp                   | 7         | 2.11%   |
| Acer                    | 6         | 1.81%   |
| Lenovo                  | 4         | 1.21%   |
| Hewlett-Packard         | 3         | 0.91%   |
| Chi Mei Optoelectronics | 3         | 0.91%   |
| ViewSonic               | 2         | 0.6%    |
| Valve                   | 2         | 0.6%    |
| Philips                 | 2         | 0.6%    |
| HJC                     | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| ASUSTek Computer        | 2         | 0.6%    |
| AOC                     | 2         | 0.6%    |
| Toshiba                 | 1         | 0.3%    |
| TCL                     | 1         | 0.3%    |
| SKY                     | 1         | 0.3%    |
| SGT                     | 1         | 0.3%    |
| Seiko/Epson             | 1         | 0.3%    |
| RTD                     | 1         | 0.3%    |
| Quanta Display          | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| NEC Computers           | 1         | 0.3%    |
| MSI                     | 1         | 0.3%    |
| Mi                      | 1         | 0.3%    |
| LPL                     | 1         | 0.3%    |
| Lenovo Group Limited    | 1         | 0.3%    |
| KTC                     | 1         | 0.3%    |
| InfoVision              | 1         | 0.3%    |
| Hitachi                 | 1         | 0.3%    |
| CS_                     | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| BenQ                    | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 5         | 1.5%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 4         | 1.2%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.9%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 3         | 0.9%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.9%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 2         | 0.6%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 0.6%    |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.6%    |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.6%    |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.6%    |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                 | 2         | 0.6%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.6%    |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                    | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.6%    |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.6%    |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.6%    |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.6%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO363C 1366x768 309x173mm 13.9-inch         | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO353D 1920x1080 309x173mm 13.9-inch        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 134       | 43.09%  |
| 1366x768 (WXGA)   | 95        | 30.55%  |
| 3840x2160 (4K)    | 16        | 5.14%   |
| 2560x1440 (QHD)   | 8         | 2.57%   |
| 1600x900 (HD+)    | 8         | 2.57%   |
| 2880x1800         | 7         | 2.25%   |
| 1920x1200 (WUXGA) | 7         | 2.25%   |
| 1440x900 (WXGA+)  | 7         | 2.25%   |
| 1280x800 (WXGA)   | 6         | 1.93%   |
| 2560x1600         | 5         | 1.61%   |
| 1280x1024 (SXGA)  | 4         | 1.29%   |
| 3840x2400         | 3         | 0.96%   |
| 800x1280          | 2         | 0.64%   |
| 2160x1440         | 2         | 0.64%   |
| 3520x1080         | 1         | 0.32%   |
| 2256x1504         | 1         | 0.32%   |
| 1920x515          | 1         | 0.32%   |
| 1360x768          | 1         | 0.32%   |
| 1024x768 (XGA)    | 1         | 0.32%   |
| 1024x600          | 1         | 0.32%   |
| Unknown           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 110       | 33.54%  |
| 14      | 60        | 18.29%  |
| 13      | 50        | 15.24%  |
| 17      | 16        | 4.88%   |
| 11      | 14        | 4.27%   |
| 24      | 13        | 3.96%   |
| 16      | 9         | 2.74%   |
| 27      | 8         | 2.44%   |
| 23      | 7         | 2.13%   |
| 21      | 7         | 2.13%   |
| 12      | 6         | 1.83%   |
| 19      | 5         | 1.52%   |
| Unknown | 5         | 1.52%   |
| 31      | 3         | 0.91%   |
| 18      | 3         | 0.91%   |
| 84      | 2         | 0.61%   |
| 40      | 2         | 0.61%   |
| 7       | 2         | 0.61%   |
| 86      | 1         | 0.3%    |
| 54      | 1         | 0.3%    |
| 46      | 1         | 0.3%    |
| 26      | 1         | 0.3%    |
| 20      | 1         | 0.3%    |
| 8       | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 206       | 63.38%  |
| 201-300     | 42        | 12.92%  |
| 501-600     | 29        | 8.92%   |
| 401-500     | 15        | 4.62%   |
| 351-400     | 15        | 4.62%   |
| Unknown     | 5         | 1.54%   |
| 601-700     | 3         | 0.92%   |
| 1001-1500   | 3         | 0.92%   |
| 801-900     | 2         | 0.62%   |
| 1501-2000   | 2         | 0.62%   |
| 1-100       | 2         | 0.62%   |
| 101-200     | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 80.7%   |
| 16/10   | 37        | 12.98%  |
| 3/2     | 5         | 1.75%   |
| 5/4     | 4         | 1.4%    |
| Unknown | 3         | 1.05%   |
| 0.67    | 2         | 0.7%    |
| 4/3     | 1         | 0.35%   |
| 3.73    | 1         | 0.35%   |
| 2.00    | 1         | 0.35%   |
| 0.56    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 33.43%  |
| 81-90          | 94        | 28.57%  |
| 201-250        | 23        | 6.99%   |
| 71-80          | 16        | 4.86%   |
| 51-60          | 14        | 4.26%   |
| 121-130        | 11        | 3.34%   |
| 111-120        | 9         | 2.74%   |
| 301-350        | 8         | 2.43%   |
| 151-200        | 7         | 2.13%   |
| 61-70          | 6         | 1.82%   |
| 141-150        | 6         | 1.82%   |
| Unknown        | 5         | 1.52%   |
| More than 1000 | 4         | 1.22%   |
| 251-300        | 4         | 1.22%   |
| 351-500        | 3         | 0.91%   |
| 1-40           | 3         | 0.91%   |
| 501-1000       | 3         | 0.91%   |
| 131-140        | 2         | 0.61%   |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 139       | 42.9%   |
| 101-120       | 87        | 26.85%  |
| 51-100        | 48        | 14.81%  |
| 161-240       | 29        | 8.95%   |
| More than 240 | 13        | 4.01%   |
| Unknown       | 5         | 1.54%   |
| 1-50          | 3         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 228       | 77.82%  |
| 2     | 54        | 18.43%  |
| 0     | 7         | 2.39%   |
| 3     | 4         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 160       | 34.19%  |
| Intel                             | 143       | 30.56%  |
| Qualcomm Atheros                  | 65        | 13.89%  |
| Broadcom                          | 32        | 6.84%   |
| MediaTek                          | 15        | 3.21%   |
| ASIX Electronics                  | 10        | 2.14%   |
| Broadcom Limited                  | 7         | 1.5%    |
| Qualcomm                          | 4         | 0.85%   |
| Marvell Technology Group          | 4         | 0.85%   |
| Xiaomi                            | 3         | 0.64%   |
| Ralink                            | 3         | 0.64%   |
| TP-Link                           | 2         | 0.43%   |
| Sierra Wireless                   | 2         | 0.43%   |
| Ralink Technology                 | 2         | 0.43%   |
| Ericsson Business Mobile Networks | 2         | 0.43%   |
| vivo                              | 1         | 0.21%   |
| VIA Technologies                  | 1         | 0.21%   |
| Samsung Electronics               | 1         | 0.21%   |
| OPPO Electronics                  | 1         | 0.21%   |
| Nvidia                            | 1         | 0.21%   |
| Motorola PCS                      | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| Huawei Technologies               | 1         | 0.21%   |
| FIBOCOM                           | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| D-Link                            | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |
| Apple                             | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 115       | 21.74%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 16        | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.89%   |
| Intel Wireless 8265 / 8275                                             | 10        | 1.89%   |
| Intel Wireless 7265                                                    | 10        | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 10        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 1.89%   |
| Intel Wireless 8260                                                    | 9         | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 1.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.51%   |
| Intel Wireless 3160                                                    | 8         | 1.51%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 6         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 4         | 0.76%   |
| Intel Wireless 3165                                                    | 4         | 0.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 4         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 4         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.57%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 3         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.57%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 3         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 141       | 47.16%  |
| Qualcomm Atheros      | 55        | 18.39%  |
| Realtek Semiconductor | 41        | 13.71%  |
| Broadcom              | 24        | 8.03%   |
| MediaTek              | 15        | 5.02%   |
| Broadcom Limited      | 6         | 2.01%   |
| Qualcomm              | 4         | 1.34%   |
| Ralink                | 3         | 1%      |
| TP-Link               | 2         | 0.67%   |
| Sierra Wireless       | 2         | 0.67%   |
| Ralink Technology     | 2         | 0.67%   |
| FIBOCOM               | 1         | 0.33%   |
| D-Link System         | 1         | 0.33%   |
| D-Link                | 1         | 0.33%   |
| ASUSTek Computer      | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 16        | 5.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 14        | 4.65%   |
| Intel Wi-Fi 6 AX200                                                                   | 13        | 4.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 11        | 3.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 10        | 3.32%   |
| Intel Wireless 8265 / 8275                                                            | 10        | 3.32%   |
| Intel Wireless 7265                                                                   | 10        | 3.32%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 10        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 10        | 3.32%   |
| Intel Wireless 8260                                                                   | 9         | 2.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 8         | 2.66%   |
| Intel Wireless 3160                                                                   | 8         | 2.66%   |
| Intel Wi-Fi 6 AX201                                                                   | 8         | 2.66%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 8         | 2.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 7         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 6         | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 6         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 1.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 6         | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 1.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 5         | 1.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 4         | 1.33%   |
| Intel Wireless 3165                                                                   | 4         | 1.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 4         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 4         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 4         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 4         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 3         | 1%      |
| Qualcomm QCNFA765 Wireless Network Adapter                                            | 3         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3         | 1%      |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                                     | 3         | 1%      |
| Intel Centrino Ultimate-N 6300                                                        | 3         | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 1%      |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 2         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.66%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 139       | 62.61%  |
| Intel                    | 29        | 13.06%  |
| Qualcomm Atheros         | 14        | 6.31%   |
| Broadcom                 | 12        | 5.41%   |
| ASIX Electronics         | 10        | 4.5%    |
| Marvell Technology Group | 4         | 1.8%    |
| Xiaomi                   | 3         | 1.35%   |
| vivo                     | 1         | 0.45%   |
| VIA Technologies         | 1         | 0.45%   |
| Samsung Electronics      | 1         | 0.45%   |
| OPPO Electronics         | 1         | 0.45%   |
| Nvidia                   | 1         | 0.45%   |
| Motorola PCS             | 1         | 0.45%   |
| Lenovo                   | 1         | 0.45%   |
| JMicron Technology       | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |
| Broadcom Limited         | 1         | 0.45%   |
| Apple                    | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 115       | 50.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 6.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 3.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 3.1%    |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.88%   |
| Realtek Killer E2600 GbE Controller                                            | 2         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.88%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                              | 2         | 0.88%   |
| ASIX AX88772A Fast Ethernet                                                    | 2         | 0.88%   |
| vivo V2027                                                                     | 1         | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.44%   |
| OPPO SM8350-MTP _SN:9338D66C                                                   | 1         | 0.44%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.44%   |
| Motorola PCS moto g(7) power                                                   | 1         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.44%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.44%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.44%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 280       | 56.57%  |
| Ethernet | 213       | 43.03%  |
| Modem    | 2         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 243       | 80.46%  |
| Ethernet | 59        | 19.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 67.72%  |
| 1     | 92        | 32.28%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 214       | 72.05%  |
| Yes  | 83        | 27.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 46.31%  |
| IMC Networks                    | 24        | 9.84%   |
| Lite-On Technology              | 19        | 7.79%   |
| Realtek Semiconductor           | 17        | 6.97%   |
| Qualcomm Atheros Communications | 11        | 4.51%   |
| Broadcom                        | 11        | 4.51%   |
| Foxconn / Hon Hai               | 10        | 4.1%    |
| Apple                           | 10        | 4.1%    |
| Dell                            | 4         | 1.64%   |
| USI                             | 3         | 1.23%   |
| Toshiba                         | 3         | 1.23%   |
| Realtek                         | 3         | 1.23%   |
| Foxconn International           | 3         | 1.23%   |
| SINO WEALTH                     | 2         | 0.82%   |
| Ralink                          | 2         | 0.82%   |
| MediaTek                        | 2         | 0.82%   |
| Hewlett-Packard                 | 2         | 0.82%   |
| Cambridge Silicon Radio         | 2         | 0.82%   |
| ASUSTek Computer                | 2         | 0.82%   |
| Askey Computer                  | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 9.8%    |
| Intel AX201 Bluetooth                               | 23        | 9.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 8.16%   |
| Intel Bluetooth Device                              | 18        | 7.35%   |
| Intel AX200 Bluetooth                               | 10        | 4.08%   |
| Realtek Bluetooth Radio                             | 9         | 3.67%   |
| IMC Networks Bluetooth Radio                        | 9         | 3.67%   |
| Intel AX211 Bluetooth                               | 8         | 3.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 2.86%   |
| IMC Networks Bluetooth Device                       | 7         | 2.86%   |
| IMC Networks Wireless_Device                        | 6         | 2.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 2.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.04%   |
| Lite-On Bluetooth Device                            | 4         | 1.63%   |
| Intel AX210 Bluetooth                               | 4         | 1.63%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.63%   |
| Apple Bluetooth Host Controller                     | 4         | 1.63%   |
| USI Bluetooth Device                                | 3         | 1.22%   |
| Realtek Bluetooth Radio                             | 3         | 1.22%   |
| Lite-On Wireless_Device                             | 3         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.22%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.82%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.82%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.82%   |
| MediaTek Wireless_Device                            | 2         | 0.82%   |
| Lite-On Bluetooth Radio                             | 2         | 0.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.82%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.82%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 2         | 0.82%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.82%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.82%   |
| Apple Bluetooth HCI                                 | 2         | 0.82%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 213       | 58.52%  |
| AMD                                          | 69        | 18.96%  |
| Nvidia                                       | 60        | 16.48%  |
| JMTek                                        | 3         | 0.82%   |
| Samson Technologies                          | 2         | 0.55%   |
| Razer USA                                    | 2         | 0.55%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.27%   |
| VIA Technologies                             | 1         | 0.27%   |
| TX                                           | 1         | 0.27%   |
| Samsung Electronics                          | 1         | 0.27%   |
| Logitech                                     | 1         | 0.27%   |
| Lenovo                                       | 1         | 0.27%   |
| Huawei Technologies                          | 1         | 0.27%   |
| Focusrite-Novation                           | 1         | 0.27%   |
| DSEA A/S                                     | 1         | 0.27%   |
| Digidesign                                   | 1         | 0.27%   |
| Dell                                         | 1         | 0.27%   |
| DCMT Technology                              | 1         | 0.27%   |
| Cayin                                        | 1         | 0.27%   |
| C-Media Electronics                          | 1         | 0.27%   |
| BlueTrm                                      | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 50        | 11.14%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 7.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 5.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 4.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 4.01%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 4.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 3.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 1.78%   |
| Nvidia Audio device                                                                               | 7         | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.11%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.89%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.89%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.67%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 28.13%  |
| SK hynix            | 39        | 20.31%  |
| Micron Technology   | 30        | 15.63%  |
| Kingston            | 24        | 12.5%   |
| Unknown             | 12        | 6.25%   |
| Crucial             | 6         | 3.13%   |
| Transcend           | 5         | 2.6%    |
| Ramaxel Technology  | 4         | 2.08%   |
| Elpida              | 3         | 1.56%   |
| A-DATA Technology   | 3         | 1.56%   |
| Team                | 2         | 1.04%   |
| Nanya Technology    | 2         | 1.04%   |
| Unknown (ABCD)      | 1         | 0.52%   |
| Unknown (08B5)      | 1         | 0.52%   |
| Lexar               | 1         | 0.52%   |
| G.Skill             | 1         | 0.52%   |
| Corsair             | 1         | 0.52%   |
| Avant               | 1         | 0.52%   |
| ASint Technology    | 1         | 0.52%   |
| Apacer              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 3.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1%      |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1%      |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1%      |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1%      |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1%      |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 2         | 1%      |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 2         | 1%      |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1%      |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s             | 2         | 1%      |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s       | 2         | 1%      |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.5%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                   | 1         | 0.5%    |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 76        | 49.03%  |
| DDR3   | 49        | 31.61%  |
| LPDDR4 | 14        | 9.03%   |
| DDR5   | 6         | 3.87%   |
| LPDDR3 | 4         | 2.58%   |
| LPDDR5 | 3         | 1.94%   |
| DDR2   | 2         | 1.29%   |
| SDRAM  | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 135       | 86.54%  |
| Row Of Chips | 21        | 13.46%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 71        | 42.77%  |
| 4096  | 51        | 30.72%  |
| 16384 | 24        | 14.46%  |
| 2048  | 15        | 9.04%   |
| 32768 | 4         | 2.41%   |
| 1024  | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 24.85%  |
| 3200    | 33        | 19.53%  |
| 2667    | 28        | 16.57%  |
| 2400    | 15        | 8.88%   |
| 2133    | 7         | 4.14%   |
| 1334    | 7         | 4.14%   |
| 4267    | 6         | 3.55%   |
| 4800    | 5         | 2.96%   |
| 3266    | 4         | 2.37%   |
| 1333    | 4         | 2.37%   |
| 4266    | 3         | 1.78%   |
| 1067    | 3         | 1.78%   |
| 6400    | 2         | 1.18%   |
| 3733    | 2         | 1.18%   |
| 8400    | 1         | 0.59%   |
| 7500    | 1         | 0.59%   |
| 5600    | 1         | 0.59%   |
| 4199    | 1         | 0.59%   |
| 1867    | 1         | 0.59%   |
| 975     | 1         | 0.59%   |
| 667     | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson ME-100 Series | 1         | 20%     |
| Seiko Epson L360 Series   | 1         | 20%     |
| Samsung SCX-4300 Series   | 1         | 20%     |
| HP DeskJet 2130 series    | 1         | 20%     |
| Canon PIXMA MP280         | 1         | 20%     |

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
| Chicony Electronics                    | 67        | 26.48%  |
| IMC Networks                           | 37        | 14.62%  |
| Bison Electronics                      | 28        | 11.07%  |
| Realtek Semiconductor                  | 21        | 8.3%    |
| Quanta                                 | 18        | 7.11%   |
| Microdia                               | 15        | 5.93%   |
| Sunplus Innovation Technology          | 7         | 2.77%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.77%   |
| Apple                                  | 6         | 2.37%   |
| Acer                                   | 6         | 2.37%   |
| Silicon Motion                         | 5         | 1.98%   |
| Lite-On Technology                     | 5         | 1.98%   |
| Suyin                                  | 4         | 1.58%   |
| Luxvisions Innotech Limited            | 4         | 1.58%   |
| Sonix Technology                       | 3         | 1.19%   |
| ShineTech                              | 3         | 1.19%   |
| Logitech                               | 3         | 1.19%   |
| Samsung Electronics                    | 2         | 0.79%   |
| OPPO Electronics                       | 2         | 0.79%   |
| Generalplus Technology                 | 2         | 0.79%   |
| Z-Star Microelectronics                | 1         | 0.4%    |
| Syntek                                 | 1         | 0.4%    |
| Razer USA                              | 1         | 0.4%    |
| Microsoft                              | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| icSpring                               | 1         | 0.4%    |
| Aveo Technology                        | 1         | 0.4%    |
| Alcor Micro                            | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam       | 16        | 6.32%   |
| Chicony HD WebCam                       | 14        | 5.53%   |
| Chicony Integrated Camera               | 11        | 4.35%   |
| Microdia Integrated_Webcam_HD           | 7         | 2.77%   |
| IMC Networks Integrated Camera          | 6         | 2.37%   |
| Chicony HP Truevision HD camera         | 6         | 2.37%   |
| Realtek Integrated_Webcam_HD            | 5         | 1.98%   |
| Bison SunplusIT Integrated Camera       | 5         | 1.98%   |
| Bison Lenovo EasyCamera                 | 5         | 1.98%   |
| Bison Integrated Camera                 | 5         | 1.98%   |
| Realtek HD WebCam                       | 4         | 1.58%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 4         | 1.58%   |
| Chicony Lenovo EasyCamera               | 4         | 1.58%   |
| Chicony HD User Facing                  | 4         | 1.58%   |
| Sunplus Integrated_Webcam_HD            | 3         | 1.19%   |
| Silicon Motion WebCam SCB-0385N         | 3         | 1.19%   |
| ShineTech USB2.0 HD UVC WebCam          | 3         | 1.19%   |
| Quanta USB2.0 HD UVC WebCam             | 3         | 1.19%   |
| Microdia USB 2.0 Camera                 | 3         | 1.19%   |
| Lite-On Integrated Camera               | 3         | 1.19%   |
| IMC Networks HD Camera                  | 3         | 1.19%   |
| Bison ThinkPad Integrated Camera        | 3         | 1.19%   |
| Bison HD Webcam                         | 3         | 1.19%   |
| Apple Built-in iSight                   | 3         | 1.19%   |
| Sunplus Asus Webcam                     | 2         | 0.79%   |
| Sonix USB2.0 HD UVC WebCam              | 2         | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode) | 2         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam            | 2         | 0.79%   |
| Realtek USB Camera                      | 2         | 0.79%   |
| Realtek Integrated Webcam               | 2         | 0.79%   |
| Quanta VGA WebCam                       | 2         | 0.79%   |
| Quanta ov9734_techfront_camera          | 2         | 0.79%   |
| Quanta HD Webcam                        | 2         | 0.79%   |
| Quanta HD User Facing                   | 2         | 0.79%   |
| Quanta HD Camera                        | 2         | 0.79%   |
| Quanta ACER HD User Facing              | 2         | 0.79%   |
| OPPO Oppo N1                            | 2         | 0.79%   |
| Microdia Integrated Webcam              | 2         | 0.79%   |
| IMC Networks VGA UVC WebCam             | 2         | 0.79%   |
| Chicony VGA Webcam                      | 2         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 13        | 27.66%  |
| Synaptics                  | 11        | 23.4%   |
| Validity Sensors           | 6         | 12.77%  |
| LighTuning Technology      | 6         | 12.77%  |
| Elan Microelectronics      | 6         | 12.77%  |
| AuthenTec                  | 3         | 6.38%   |
| Upek                       | 2         | 4.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                       | 6         | 12.77%  |
| Shenzhen Goodix  Fingerprint Device                      | 5         | 10.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 4         | 8.51%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 4         | 8.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 6.38%   |
| Elan ELAN:Fingerprint                                    | 3         | 6.38%   |
| Elan ELAN:ARM-M4                                         | 3         | 6.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 4.26%   |
| Synaptics UWP WBDI Device                                | 2         | 4.26%   |
| Shenzhen Goodix FingerPrint                              | 2         | 4.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 4.26%   |
| AuthenTec AES2810                                        | 2         | 4.26%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.13%   |
| Validity Sensors Synaptics WBDI                          | 1         | 2.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 2.13%   |
| Synaptics WBDI                                           | 1         | 2.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 2.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.13%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 45.45%  |
| O2 Micro              | 3         | 27.27%  |
| Broadcom              | 2         | 18.18%  |
| Gemalto (was Gemplus) | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 45.45%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 27.27%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 181       | 60.74%  |
| 1     | 94        | 31.54%  |
| 2     | 20        | 6.71%   |
| 3     | 3         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 33.33%  |
| Graphics card            | 32        | 23.19%  |
| Multimedia controller    | 17        | 12.32%  |
| Net/wireless             | 15        | 10.87%  |
| Chipcard                 | 11        | 7.97%   |
| Camera                   | 6         | 4.35%   |
| Bluetooth                | 4         | 2.9%    |
| Card reader              | 2         | 1.45%   |
| Wireless                 | 1         | 0.72%   |
| Storage/ide              | 1         | 0.72%   |
| Net/ethernet             | 1         | 0.72%   |
| Flash memory             | 1         | 0.72%   |
| Communication controller | 1         | 0.72%   |

