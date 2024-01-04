Linux in Sweden - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

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

Total: 1770

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-db0xxx            | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Dell          | Latitude 7490               | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| ASUSTek       | G75VW                       | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| Dell          | Latitude 5420               | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [18ef14b687](https://linux-hardware.org/?probe=18ef14b687) | Dec 23, 2023 |
| HP            | ProBook 445 14 inch G10 ... | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3324746751](https://linux-hardware.org/?probe=3324746751) | Dec 16, 2023 |
| PC Special... | N150CU                      | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| PC Special... | N150CU                      | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| HP            | Unknown                     | [6a46b87d41](https://linux-hardware.org/?probe=6a46b87d41) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| Acer          | Extensa 2509                | [ee00581b3a](https://linux-hardware.org/?probe=ee00581b3a) | Dec 11, 2023 |
| Dell          | XPS 9320                    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Acer          | Swift SFE16-43              | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| Acer          | Aspire V3-571               | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| HUAWEI        | KLVC-WXX9                   | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [24e86fc568](https://linux-hardware.org/?probe=24e86fc568) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [288151e67d](https://linux-hardware.org/?probe=288151e67d) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Acer          | Predator PH315-53           | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94927ee986](https://linux-hardware.org/?probe=94927ee986) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8cb9c3b0a7](https://linux-hardware.org/?probe=8cb9c3b0a7) | Nov 24, 2023 |
| HP            | Presario CQ61               | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| HP            | EliteBook 6930p             | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Acer          | Aspire V3-571G              | [63c8984ac3](https://linux-hardware.org/?probe=63c8984ac3) | Nov 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e42bab7bfa](https://linux-hardware.org/?probe=e42bab7bfa) | Nov 15, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| Valve         | Jupiter                     | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Apple         | MacBookPro11,1              | [224a0992ae](https://linux-hardware.org/?probe=224a0992ae) | Nov 08, 2023 |
| Apple         | MacBookPro11,1              | [9a3d616dad](https://linux-hardware.org/?probe=9a3d616dad) | Nov 08, 2023 |
| HP            | EliteBook 2570p             | [de38771bec](https://linux-hardware.org/?probe=de38771bec) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5191c2b469](https://linux-hardware.org/?probe=5191c2b469) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Dell          | Latitude 3190               | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| Chuwi         | HeroBook Pro                | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Acer          | Swift SF113-31              | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| HP            | Unknown                     | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| Dell          | XPS 13 9310                 | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A532               | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| Dell          | Precision 5570              | [fb83199260](https://linux-hardware.org/?probe=fb83199260) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| Dell          | Latitude 7370               | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| HP            | Unknown                     | [3aadbc5c33](https://linux-hardware.org/?probe=3aadbc5c33) | Oct 30, 2023 |
| HP            | Laptop 15-bw0xx             | [b61ad8059a](https://linux-hardware.org/?probe=b61ad8059a) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| HP            | G62                         | [bd714e9671](https://linux-hardware.org/?probe=bd714e9671) | Oct 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| ASUSTek       | G75VW                       | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK E752               | [c1078c11fb](https://linux-hardware.org/?probe=c1078c11fb) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | [b05283573c](https://linux-hardware.org/?probe=b05283573c) | Oct 26, 2023 |
| HP            | EliteBook 8560p             | [101037a3e1](https://linux-hardware.org/?probe=101037a3e1) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [c505d21099](https://linux-hardware.org/?probe=c505d21099) | Oct 25, 2023 |
| Notebook      | NS5x_NS7xAU                 | [ad7033d138](https://linux-hardware.org/?probe=ad7033d138) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | Latitude 3190               | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 13 9310                 | [cceff4e3b1](https://linux-hardware.org/?probe=cceff4e3b1) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0feec3b3ab](https://linux-hardware.org/?probe=0feec3b3ab) | Oct 19, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| HP            | EliteBook 8760w             | [d5febd2212](https://linux-hardware.org/?probe=d5febd2212) | Oct 17, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Notebook      | NS5x_NS7xAU                 | [1568dbcf9b](https://linux-hardware.org/?probe=1568dbcf9b) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Dell          | Latitude 7420               | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c360c7552a](https://linux-hardware.org/?probe=c360c7552a) | Oct 08, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| HP            | ZBook 14u G4                | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [071eee1057](https://linux-hardware.org/?probe=071eee1057) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| HP            | ZBook Studio G5             | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Dell          | Inspiron 3541               | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Valve         | Jupiter                     | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| ASUSTek       | K55DR                       | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Samsung       | R530/R730/P590              | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| Dell          | Latitude 7440               | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Acer          | Aspire 5755G                | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Acer          | Aspire ES1-311              | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| HP            | Unknown                     | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| ASUSTek       | G75VW                       | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| MSI           | GF65 Thin 10SER             | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | GX60 1AC                    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| MSI           | Katana GF76 12UD            | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| Acer          | Aspire ES1-311              | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | G75VW                       | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| Acer          | Aspire E1-571               | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| HP            | Compaq 6730s                | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| HP            | EliteBook 850 G6            | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | Latitude 5430               | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Dell          | Latitude 7490               | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| Unknown       | Unknown                     | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| HP            | ProBook 4530s               | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Dell          | Precision 5530              | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | ENVY TS Sleekbook 4         | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| GPD           | P2 MAX                      | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| HP            | Presario CQ57               | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| ASUSTek       | G75VW                       | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| GPD           | P2 MAX                      | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | EliteBook 820 G3            | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| HP            | Laptop 15-dw1xxx            | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Valve         | Jupiter                     | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Acer          | Aspire V3-571               | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Dell          | Studio 1749                 | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Acer          | Aspire V3-571G              | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Valve         | Jupiter                     | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| Dell          | Latitude 3380               | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | Latitude 3380               | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | Latitude E7240              | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| Insyde        | G0975                       | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Dell          | Latitude 5430               | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| Dell          | XPS 9320                    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| HP            | ZBook 15u G6                | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| HP            | EliteBook 830 G5            | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| Valve         | Jupiter                     | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Apple         | MacBookAir6,1               | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| Dell          | XPS 15 9560                 | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Latitude E6320              | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | XPS 13 9310                 | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Valve         | Jupiter                     | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| HP            | Pavilion g7                 | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| Dell          | Latitude E6320              | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Dell          | Latitude 7300               | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| Acer          | Aspire V3-571G              | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | Pavilion 15                 | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| Samsung       | 935XDB                      | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Pavilion g6                 | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Apple         | MacBookPro11,3              | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Valve         | Jupiter                     | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Apple         | MacBookPro11,3              | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| MSI           | Raider GE76 12UGS           | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| Dell          | Precision 5570              | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Valve         | Jupiter                     | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| Dell          | XPS 15 9520                 | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| Apple         | MacBookAir6,2               | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | ProBook 6450b               | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| HP            | ProBook 6450b               | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| HP            | ProBook 650 G1              | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Apple         | MacBook6,1                  | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Apple         | MacBookAir7,2               | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| Apple         | MacBook6,1                  | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| MSI           | GS73VR 7RG                  | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| Notebook      | NS50_70MU                   | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Acer          | Aspire A315-41              | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| HP            | Pavilion Notebook           | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| Toshiba       | BLB                         | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| HP            | ProBook 430 G1              | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASUSTek       | N56DY                       | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Dell          | Precision 5540              | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Apple         | MacBookPro11,3              | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| HP            | ProBook 430 G1              | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Sony          | VPCEB36FG                   | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| Dell          | Precision 3510              | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dell          | Latitude E6430              | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| Dell          | Latitude D620               | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| ASUSTek       | GR8                         | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Apple         | MacBook3,1                  | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| Notebook      | N13xWU                      | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Dell          | Inspiron 5721               | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Dell          | Latitude 5290               | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Sony          | VPCEB3S1E                   | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| Samsung       | 935XDB                      | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| Dell          | XPS 13 9350                 | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| Samsung       | 905S3G/906S3G/915S3G        | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Dell          | Latitude E7450              | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Dell          | Precision 5560              | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| HP            | Compaq CQ58                 | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Acer          | Predator PT315-51           | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASUSTek       | N550JK                      | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| HP            | ZBook 14 G2                 | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| HP            | ProBook 430 G1              | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | T100HAN                     | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Acer          | Aspire V3-772G              | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Dell          | Latitude E5250              | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| Google        | Treeya                      | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| HP            | EliteBook 830 G6            | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | GL553VE                     | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Presario CQ62               | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| Apple         | MacBookAir7,2               | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Acer          | Swift SF314-511             | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| HP            | ZBook 17 G3                 | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| HP            | ProBook 4540s               | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| PC Special... | N150CU                      | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| ASUSTek       | X510UAR                     | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Dell          | Inspiron 7520               | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 146       | 11.45%  |
| Ubuntu 22.04                 | 91        | 7.14%   |
| Ubuntu 18.04                 | 74        | 5.8%    |
| Debian 12                    | 34        | 2.67%   |
| Pop!_OS 22.04                | 33        | 2.59%   |
| Debian 11                    | 32        | 2.51%   |
| Zorin 16                     | 28        | 2.2%    |
| Arch Rolling                 | 27        | 2.12%   |
| Manjaro                      | 24        | 1.88%   |
| Pop!_OS 21.04                | 22        | 1.73%   |
| OpenMandriva 4.3             | 21        | 1.65%   |
| OpenMandriva 4.2             | 21        | 1.65%   |
| Arch                         | 21        | 1.65%   |
| Fedora 35                    | 20        | 1.57%   |
| ArcoLinux Rolling            | 20        | 1.57%   |
| Ubuntu 19.04                 | 19        | 1.49%   |
| Linux Mint 21.1              | 18        | 1.41%   |
| Zorin 15                     | 16        | 1.25%   |
| Ubuntu 21.10                 | 16        | 1.25%   |
| Pop!_OS 20.10                | 16        | 1.25%   |
| Pop!_OS 20.04                | 16        | 1.25%   |
| openSUSE Tumbleweed-XXXXXXXX | 16        | 1.25%   |
| Linux Mint 20.3              | 15        | 1.18%   |
| KDE neon 20.04               | 15        | 1.18%   |
| Linux Mint 20.2              | 14        | 1.1%    |
| Fedora 38                    | 14        | 1.1%    |
| Fedora 37                    | 14        | 1.1%    |
| Ubuntu 19.10                 | 13        | 1.02%   |
| Linux Mint 20.1              | 12        | 0.94%   |
| Fedora 34                    | 12        | 0.94%   |
| Ubuntu 21.04                 | 11        | 0.86%   |
| Linux Mint 21.2              | 11        | 0.86%   |
| Ubuntu 20.10                 | 10        | 0.78%   |
| Fedora 36                    | 10        | 0.78%   |
| Ubuntu 23.04                 | 9         | 0.71%   |
| Pop!_OS 21.10                | 9         | 0.71%   |
| Fedora 33                    | 9         | 0.71%   |
| Xubuntu 20.04                | 8         | 0.63%   |
| Ubuntu 22.10                 | 8         | 0.63%   |
| Linux Mint 20                | 8         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 391       | 32.08%  |
| Linux Mint    | 99        | 8.12%   |
| Fedora        | 98        | 8.04%   |
| Pop!_OS       | 92        | 7.55%   |
| Debian        | 78        | 6.4%    |
| OpenMandriva  | 64        | 5.25%   |
| Manjaro       | 47        | 3.86%   |
| Arch          | 47        | 3.86%   |
| Zorin         | 44        | 3.61%   |
| KDE neon      | 23        | 1.89%   |
| ArcoLinux     | 23        | 1.89%   |
| Xubuntu       | 21        | 1.72%   |
| openSUSE      | 18        | 1.48%   |
| Kubuntu       | 17        | 1.39%   |
| Kali          | 15        | 1.23%   |
| Gentoo        | 12        | 0.98%   |
| EndeavourOS   | 10        | 0.82%   |
| Ubuntu MATE   | 9         | 0.74%   |
| SteamOS       | 9         | 0.74%   |
| Endless       | 9         | 0.74%   |
| Elementary    | 8         | 0.66%   |
| ROSA          | 7         | 0.57%   |
| CentOS        | 6         | 0.49%   |
| Parrot        | 5         | 0.41%   |
| BunsenLabs    | 5         | 0.41%   |
| Peppermint    | 4         | 0.33%   |
| Lubuntu       | 4         | 0.33%   |
| LMDE          | 4         | 0.33%   |
| Clear Linux   | 4         | 0.33%   |
| BlackPanther  | 4         | 0.33%   |
| Ubuntu Unity  | 3         | 0.25%   |
| Ubuntu Budgie | 3         | 0.25%   |
| Nobara        | 3         | 0.25%   |
| NixOS         | 3         | 0.25%   |
| MX            | 3         | 0.25%   |
| Garuda Linux  | 3         | 0.25%   |
| Slackware     | 2         | 0.16%   |
| GNOME OS      | 2         | 0.16%   |
| Deepin        | 2         | 0.16%   |
| Chrome OS     | 2         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 1.51%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.43%   |
| 5.15.0-56-generic        | 19        | 1.36%   |
| 5.4.0-42-generic         | 18        | 1.29%   |
| 5.4.0-58-generic         | 12        | 0.86%   |
| 5.4.0-48-generic         | 12        | 0.86%   |
| 5.15.0-52-generic        | 12        | 0.86%   |
| 6.1.0-7-amd64            | 10        | 0.72%   |
| 5.3.0-40-generic         | 10        | 0.72%   |
| 5.13.0-30-generic        | 10        | 0.72%   |
| 6.1.0-9-amd64            | 9         | 0.65%   |
| 5.4.0-52-generic         | 9         | 0.65%   |
| 5.4.0-40-generic         | 9         | 0.65%   |
| 5.15.0-78-generic        | 9         | 0.65%   |
| 5.15.0-60-generic        | 9         | 0.65%   |
| 5.11.0-37-generic        | 9         | 0.65%   |
| 5.8.0-48-generic         | 8         | 0.57%   |
| 5.15.0-48-generic        | 8         | 0.57%   |
| 5.13.0-7614-generic      | 8         | 0.57%   |
| 6.4.11-desktop-1omv2390  | 7         | 0.5%    |
| 5.4.0-70-generic         | 7         | 0.5%    |
| 5.4.0-65-generic         | 7         | 0.5%    |
| 5.19.0-35-generic        | 7         | 0.5%    |
| 5.15.0-76-generic        | 7         | 0.5%    |
| 5.13.0-39-generic        | 7         | 0.5%    |
| 5.10.0-8-amd64           | 7         | 0.5%    |
| 5.10.0-21-amd64          | 7         | 0.5%    |
| 4.15.0-47-generic        | 7         | 0.5%    |
| 5.8.0-7630-generic       | 6         | 0.43%   |
| 5.4.0-7634-generic       | 6         | 0.43%   |
| 5.4.0-66-generic         | 6         | 0.43%   |
| 5.4.0-54-generic         | 6         | 0.43%   |
| 5.4.0-33-generic         | 6         | 0.43%   |
| 5.3.0-51-generic         | 6         | 0.43%   |
| 5.3.0-28-generic         | 6         | 0.43%   |
| 5.19.0-46-generic        | 6         | 0.43%   |
| 5.15.0-50-generic        | 6         | 0.43%   |
| 5.11.0-41-generic        | 6         | 0.43%   |
| 6.2.6-76060206-generic   | 5         | 0.36%   |
| 6.1.0-13-amd64           | 5         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 178       | 13.47%  |
| 5.15.0  | 128       | 9.69%   |
| 5.13.0  | 66        | 5%      |
| 5.11.0  | 66        | 5%      |
| 5.8.0   | 51        | 3.86%   |
| 6.1.0   | 47        | 3.56%   |
| 5.3.0   | 46        | 3.48%   |
| 4.15.0  | 46        | 3.48%   |
| 5.10.0  | 45        | 3.41%   |
| 5.19.0  | 40        | 3.03%   |
| 6.2.0   | 35        | 2.65%   |
| 5.0.0   | 34        | 2.57%   |
| 4.18.0  | 23        | 1.74%   |
| 5.16.7  | 21        | 1.59%   |
| 5.10.14 | 21        | 1.59%   |
| 6.2.6   | 9         | 0.68%   |
| 5.14.0  | 9         | 0.68%   |
| 6.4.11  | 8         | 0.61%   |
| 6.5.0   | 7         | 0.53%   |
| 6.0.12  | 7         | 0.53%   |
| 5.17.5  | 7         | 0.53%   |
| 6.5.6   | 6         | 0.45%   |
| 6.1.1   | 6         | 0.45%   |
| 5.16.0  | 6         | 0.45%   |
| 6.5.7   | 5         | 0.38%   |
| 5.7.0   | 5         | 0.38%   |
| 5.18.0  | 5         | 0.38%   |
| 6.6.7   | 4         | 0.3%    |
| 6.5.5   | 4         | 0.3%    |
| 6.4.0   | 4         | 0.3%    |
| 6.3.0   | 4         | 0.3%    |
| 6.2.9   | 4         | 0.3%    |
| 6.2.8   | 4         | 0.3%    |
| 6.2.7   | 4         | 0.3%    |
| 6.1.9   | 4         | 0.3%    |
| 6.0.8   | 4         | 0.3%    |
| 5.17.1  | 4         | 0.3%    |
| 5.16.2  | 4         | 0.3%    |
| 5.16.15 | 4         | 0.3%    |
| 5.15.5  | 4         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 185       | 14.25%  |
| 5.15    | 160       | 12.33%  |
| 5.10    | 83        | 6.39%   |
| 6.1     | 78        | 6.01%   |
| 5.11    | 78        | 6.01%   |
| 5.13    | 76        | 5.86%   |
| 6.2     | 63        | 4.85%   |
| 5.8     | 63        | 4.85%   |
| 5.3     | 52        | 4.01%   |
| 5.19    | 47        | 3.62%   |
| 5.16    | 47        | 3.62%   |
| 4.15    | 46        | 3.54%   |
| 5.0     | 36        | 2.77%   |
| 6.4     | 29        | 2.23%   |
| 4.18    | 29        | 2.23%   |
| 6.0     | 26        | 2%      |
| 6.5     | 25        | 1.93%   |
| 5.14    | 21        | 1.62%   |
| 5.18    | 20        | 1.54%   |
| 5.17    | 20        | 1.54%   |
| 6.3     | 16        | 1.23%   |
| 5.9     | 14        | 1.08%   |
| 5.12    | 14        | 1.08%   |
| 6.6     | 12        | 0.92%   |
| 5.7     | 11        | 0.85%   |
| 5.6     | 11        | 0.85%   |
| 4.19    | 8         | 0.62%   |
| 5.5     | 7         | 0.54%   |
| 5.2     | 6         | 0.46%   |
| 4.9     | 5         | 0.39%   |
| 5.1     | 4         | 0.31%   |
| 4.1     | 2         | 0.15%   |
| 6.7     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 3.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1154      | 98.63%  |
| i686   | 16        | 1.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 609       | 49.71%  |
| KDE5            | 163       | 13.31%  |
| Unknown         | 137       | 11.18%  |
| XFCE            | 93        | 7.59%   |
| X-Cinnamon      | 85        | 6.94%   |
| KDE             | 29        | 2.37%   |
| MATE            | 28        | 2.29%   |
| i3              | 13        | 1.06%   |
| Cinnamon        | 12        | 0.98%   |
| Pantheon        | 8         | 0.65%   |
| LXQt            | 8         | 0.65%   |
| sway            | 5         | 0.41%   |
| LXDE            | 5         | 0.41%   |
| Unity           | 3         | 0.24%   |
| KDE4            | 3         | 0.24%   |
| BunsenLabs      | 3         | 0.24%   |
| Budgie          | 3         | 0.24%   |
| awesome         | 3         | 0.24%   |
| qtile           | 2         | 0.16%   |
| GNOME Flashback | 2         | 0.16%   |
| DWM             | 2         | 0.16%   |
| Deepin          | 2         | 0.16%   |
| Trinity         | 1         | 0.08%   |
| spectrwm        | 1         | 0.08%   |
| none+awesome    | 1         | 0.08%   |
| LeftWM          | 1         | 0.08%   |
| Hyprland        | 1         | 0.08%   |
| DDE             | 1         | 0.08%   |
| bspwm           | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 848       | 70.2%   |
| Wayland | 264       | 21.85%  |
| Unknown | 76        | 6.29%   |
| Tty     | 20        | 1.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 592       | 48.45%  |
| GDM3    | 179       | 14.65%  |
| SDDM    | 151       | 12.36%  |
| GDM     | 143       | 11.7%   |
| LightDM | 117       | 9.57%   |
| TDM     | 28        | 2.29%   |
| LXDM    | 4         | 0.33%   |
| XDM     | 3         | 0.25%   |
| KDM     | 3         | 0.25%   |
| Ly      | 2         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 593       | 49.25%  |
| sv_SE      | 331       | 27.49%  |
| Unknown    | 124       | 10.3%   |
| en_GB      | 73        | 6.06%   |
| C          | 17        | 1.41%   |
| ru_RU      | 10        | 0.83%   |
| de_DE      | 8         | 0.66%   |
| pl_PL      | 6         | 0.5%    |
| en_SE      | 5         | 0.42%   |
| fr_FR      | 3         | 0.25%   |
| en_DK      | 3         | 0.25%   |
| en_CA      | 3         | 0.25%   |
| el_GR      | 3         | 0.25%   |
| zh_CN      | 2         | 0.17%   |
| uk_UA      | 2         | 0.17%   |
| lt_LT      | 2         | 0.17%   |
| it_IT      | 2         | 0.17%   |
| fi_FI      | 2         | 0.17%   |
| en_AG      | 2         | 0.17%   |
| tr_TR      | 1         | 0.08%   |
| sv_SE.UTF8 | 1         | 0.08%   |
| sv_FI      | 1         | 0.08%   |
| POSIX      | 1         | 0.08%   |
| nn_NO      | 1         | 0.08%   |
| nb_NO      | 1         | 0.08%   |
| hu_HU      | 1         | 0.08%   |
| gl_ES      | 1         | 0.08%   |
| es_ES      | 1         | 0.08%   |
| en_IE      | 1         | 0.08%   |
| en_AU      | 1         | 0.08%   |
| C.UTF8     | 1         | 0.08%   |
| bg_BG      | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 648       | 54%     |
| BIOS | 552       | 46%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 888       | 73.69%  |
| Btrfs   | 131       | 10.87%  |
| Overlay | 68        | 5.64%   |
| Tmpfs   | 47        | 3.9%    |
| Unknown | 31        | 2.57%   |
| Zfs     | 14        | 1.16%   |
| Xfs     | 14        | 1.16%   |
| Ext2    | 6         | 0.5%    |
| F2fs    | 4         | 0.33%   |
| XXXXXXX | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 601       | 50.04%  |
| GPT     | 494       | 41.13%  |
| MBR     | 106       | 8.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1083      | 91.39%  |
| Yes       | 102       | 8.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 957       | 80.9%   |
| Yes       | 226       | 19.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 284       | 24.27%  |
| Hewlett-Packard      | 245       | 20.94%  |
| Dell                 | 176       | 15.04%  |
| ASUSTek Computer     | 148       | 12.65%  |
| Acer                 | 84        | 7.18%   |
| Apple                | 51        | 4.36%   |
| MSI                  | 25        | 2.14%   |
| Toshiba              | 16        | 1.37%   |
| Sony                 | 15        | 1.28%   |
| Samsung Electronics  | 11        | 0.94%   |
| Packard Bell         | 10        | 0.85%   |
| Notebook             | 10        | 0.85%   |
| Fujitsu              | 10        | 0.85%   |
| Google               | 9         | 0.77%   |
| Valve                | 8         | 0.68%   |
| Fujitsu Siemens      | 6         | 0.51%   |
| Unknown              | 6         | 0.51%   |
| HUAWEI               | 5         | 0.43%   |
| TUXEDO               | 3         | 0.26%   |
| Star Labs            | 3         | 0.26%   |
| Clevo                | 3         | 0.26%   |
| Alienware            | 3         | 0.26%   |
| Timi                 | 2         | 0.17%   |
| System76             | 2         | 0.17%   |
| Schenker             | 2         | 0.17%   |
| Razer                | 2         | 0.17%   |
| PC Specialist        | 2         | 0.17%   |
| LG Electronics       | 2         | 0.17%   |
| Gigabyte Technology  | 2         | 0.17%   |
| eMachines            | 2         | 0.17%   |
| Dynabook             | 2         | 0.17%   |
| ZEPTO                | 1         | 0.09%   |
| YJKC                 | 1         | 0.09%   |
| win element          | 1         | 0.09%   |
| SLIMBOOK             | 1         | 0.09%   |
| Purism               | 1         | 0.09%   |
| Panasonic            | 1         | 0.09%   |
| On by NetOnNet       | 1         | 0.09%   |
| Medion               | 1         | 0.09%   |
| Intel Client Systems | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 0.85%   |
| Valve Jupiter                              | 8         | 0.68%   |
| Dell XPS 13 9370                           | 7         | 0.6%    |
| Dell XPS 13 9310                           | 7         | 0.6%    |
| HP EliteBook Folio 9470m                   | 6         | 0.51%   |
| Dell Precision 5540                        | 6         | 0.51%   |
| Apple MacBookPro9,2                        | 6         | 0.51%   |
| Apple MacBookAir7,2                        | 6         | 0.51%   |
| Acer Aspire V3-571                         | 6         | 0.51%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 5         | 0.43%   |
| HP ProBook 640 G1                          | 5         | 0.43%   |
| HP Pavilion dv7                            | 5         | 0.43%   |
| HP Pavilion 15                             | 5         | 0.43%   |
| HP EliteBook 840 G3                        | 5         | 0.43%   |
| HP EliteBook 840 G2                        | 5         | 0.43%   |
| Dell XPS 15 9570                           | 5         | 0.43%   |
| Apple MacBookPro8,1                        | 5         | 0.43%   |
| Apple MacBookPro11,3                       | 5         | 0.43%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX       | 4         | 0.34%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00       | 4         | 0.34%   |
| HP Laptop 15-db0xxx                        | 4         | 0.34%   |
| HP EliteBook 8440p                         | 4         | 0.34%   |
| HP EliteBook 840 G6                        | 4         | 0.34%   |
| HP EliteBook 830 G6                        | 4         | 0.34%   |
| Dell XPS 15 9500                           | 4         | 0.34%   |
| Dell Latitude E7240                        | 4         | 0.34%   |
| Dell Latitude 7490                         | 4         | 0.34%   |
| Apple MacBookPro12,1                       | 4         | 0.34%   |
| Lenovo Z50-70 20354                        | 3         | 0.26%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 3         | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005NMX | 3         | 0.26%   |
| Lenovo G50-30 80G0                         | 3         | 0.26%   |
| Lenovo B50-30 80ES                         | 3         | 0.26%   |
| HUAWEI KLVL-WXX9                           | 3         | 0.26%   |
| HP ZBook Studio G5                         | 3         | 0.26%   |
| HP ZBook 15 G2                             | 3         | 0.26%   |
| HP ProBook 650 G1                          | 3         | 0.26%   |
| HP ProBook 430 G1                          | 3         | 0.26%   |
| HP Pavilion Notebook                       | 3         | 0.26%   |
| HP Pavilion g6                             | 3         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 184       | 15.73%  |
| HP EliteBook          | 89        | 7.61%   |
| Dell Latitude         | 70        | 5.98%   |
| Acer Aspire           | 55        | 4.7%    |
| Dell XPS              | 47        | 4.02%   |
| Lenovo IdeaPad        | 43        | 3.68%   |
| HP ProBook            | 41        | 3.5%    |
| Dell Precision        | 40        | 3.42%   |
| HP Pavilion           | 38        | 3.25%   |
| ASUS VivoBook         | 23        | 1.97%   |
| HP ZBook              | 21        | 1.79%   |
| HP Laptop             | 19        | 1.62%   |
| ASUS ROG              | 19        | 1.62%   |
| Toshiba Satellite     | 14        | 1.2%    |
| Lenovo Yoga           | 13        | 1.11%   |
| HP Compaq             | 13        | 1.11%   |
| Acer Swift            | 13        | 1.11%   |
| ASUS ZenBook          | 12        | 1.03%   |
| Dell Inspiron         | 10        | 0.85%   |
| Unknown               | 10        | 0.85%   |
| Packard Bell EasyNote | 9         | 0.77%   |
| Lenovo Legion         | 9         | 0.77%   |
| Fujitsu LIFEBOOK      | 9         | 0.77%   |
| Valve Jupiter         | 8         | 0.68%   |
| Dell Vostro           | 8         | 0.68%   |
| ASUS ASUS             | 8         | 0.68%   |
| HP ENVY               | 7         | 0.6%    |
| Apple MacBookPro11    | 7         | 0.6%    |
| Apple MacBookPro9     | 6         | 0.51%   |
| Apple MacBookAir7     | 6         | 0.51%   |
| Acer Predator         | 6         | 0.51%   |
| Acer Nitro            | 6         | 0.51%   |
| Apple MacBookPro8     | 5         | 0.43%   |
| Apple MacBookAir6     | 5         | 0.43%   |
| MSI Katana            | 4         | 0.34%   |
| HP Presario           | 4         | 0.34%   |
| ASUS TUF              | 4         | 0.34%   |
| Apple MacBookPro12    | 4         | 0.34%   |
| MSI GF63              | 3         | 0.26%   |
| Lenovo Z50-70         | 3         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 113       | 9.66%   |
| 2019 | 100       | 8.55%   |
| 2013 | 100       | 8.55%   |
| 2018 | 95        | 8.12%   |
| 2020 | 91        | 7.78%   |
| 2012 | 91        | 7.78%   |
| 2011 | 79        | 6.75%   |
| 2017 | 78        | 6.67%   |
| 2014 | 72        | 6.15%   |
| 2015 | 67        | 5.73%   |
| 2016 | 59        | 5.04%   |
| 2010 | 55        | 4.7%    |
| 2022 | 54        | 4.62%   |
| 2008 | 34        | 2.91%   |
| 2007 | 27        | 2.31%   |
| 2009 | 21        | 1.79%   |
| 2023 | 19        | 1.62%   |
| 2006 | 8         | 0.68%   |
| 2005 | 6         | 0.51%   |
| 2004 | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1170      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1026      | 87.02%  |
| Enabled  | 153       | 12.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1157      | 98.89%  |
| Yes  | 13        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 339       | 28.68%  |
| 16.01-24.0  | 232       | 19.63%  |
| 8.01-16.0   | 209       | 17.68%  |
| 3.01-4.0    | 193       | 16.33%  |
| 32.01-64.0  | 135       | 11.42%  |
| 1.01-2.0    | 37        | 3.13%   |
| 24.01-32.0  | 15        | 1.27%   |
| 64.01-256.0 | 9         | 0.76%   |
| 2.01-3.0    | 8         | 0.68%   |
| 0.51-1.0    | 5         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 426       | 33.13%  |
| 2.01-3.0   | 339       | 26.36%  |
| 4.01-8.0   | 205       | 15.94%  |
| 3.01-4.0   | 190       | 14.77%  |
| 0.51-1.0   | 55        | 4.28%   |
| 8.01-16.0  | 47        | 3.65%   |
| 16.01-24.0 | 11        | 0.86%   |
| 0.01-0.5   | 11        | 0.86%   |
| 24.01-32.0 | 2         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 956       | 80.47%  |
| 2      | 204       | 17.17%  |
| 3      | 18        | 1.52%   |
| 0      | 5         | 0.42%   |
| 4      | 4         | 0.34%   |
| 5      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 840       | 71.61%  |
| Yes       | 333       | 28.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 934       | 79.49%  |
| No        | 241       | 20.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1159      | 99.06%  |
| No        | 11        | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 979       | 82.62%  |
| No        | 206       | 17.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 1170      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Stockholm         | 240       | 18.94%  |
| Gothenburg        | 125       | 9.87%   |
| Malmo             | 59        | 4.66%   |
| Uppsala           | 31        | 2.45%   |
| Linköping        | 19        | 1.5%    |
| Solna             | 17        | 1.34%   |
| Saltsjoe-Boo      | 17        | 1.34%   |
| Lund              | 17        | 1.34%   |
| Bromma            | 17        | 1.34%   |
| Sollentuna        | 15        | 1.18%   |
| Örebro           | 15        | 1.18%   |
| Västerås        | 14        | 1.1%    |
| Umeå             | 13        | 1.03%   |
| Norrköping       | 13        | 1.03%   |
| Huddinge          | 13        | 1.03%   |
| Vaxjo             | 12        | 0.95%   |
| Vaestra Froelunda | 11        | 0.87%   |
| Sundbyberg        | 11        | 0.87%   |
| Karlskrona        | 11        | 0.87%   |
| Bandhagen         | 11        | 0.87%   |
| Taby              | 9         | 0.71%   |
| Sundsvall         | 9         | 0.71%   |
| Norsborg          | 9         | 0.71%   |
| Kista             | 9         | 0.71%   |
| Karlstad          | 9         | 0.71%   |
| Halmstad          | 9         | 0.71%   |
| Haegersten        | 9         | 0.71%   |
| Spanga            | 8         | 0.63%   |
| Södertälje      | 8         | 0.63%   |
| Landskrona        | 8         | 0.63%   |
| Jönköping       | 8         | 0.63%   |
| Helsingborg       | 8         | 0.63%   |
| Staffanstorp      | 7         | 0.55%   |
| Moelndal          | 7         | 0.55%   |
| Mjoelby           | 7         | 0.55%   |
| Katrineholm       | 7         | 0.55%   |
| Gävle            | 7         | 0.55%   |
| Sigtuna           | 6         | 0.47%   |
| Luleå            | 6         | 0.47%   |
| Kalmar            | 6         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 303       | 405    | 21.8%   |
| WDC                            | 123       | 151    | 8.85%   |
| Seagate                        | 99        | 116    | 7.12%   |
| Toshiba                        | 96        | 121    | 6.91%   |
| Kingston                       | 94        | 123    | 6.76%   |
| SanDisk                        | 93        | 116    | 6.69%   |
| Intel                          | 89        | 100    | 6.4%    |
| SK hynix                       | 78        | 86     | 5.61%   |
| Unknown                        | 71        | 87     | 5.11%   |
| Micron Technology              | 55        | 61     | 3.96%   |
| Hitachi                        | 38        | 44     | 2.73%   |
| Apple                          | 31        | 38     | 2.23%   |
| HGST                           | 30        | 36     | 2.16%   |
| Crucial                        | 25        | 34     | 1.8%    |
| LITEON                         | 17        | 22     | 1.22%   |
| KIOXIA                         | 15        | 15     | 1.08%   |
| Kingston Technology Company    | 11        | 11     | 0.79%   |
| OCZ                            | 9         | 9      | 0.65%   |
| LITEONIT                       | 7         | 12     | 0.5%    |
| A-DATA Technology              | 7         | 7      | 0.5%    |
| Intenso                        | 6         | 6      | 0.43%   |
| Phison Electronics             | 5         | 5      | 0.36%   |
| Phison                         | 5         | 5      | 0.36%   |
| Fujitsu                        | 5         | 7      | 0.36%   |
| Lenovo                         | 4         | 4      | 0.29%   |
| China                          | 4         | 4      | 0.29%   |
| Union Memory                   | 3         | 3      | 0.22%   |
| Transcend                      | 3         | 3      | 0.22%   |
| Silicon Motion                 | 3         | 15     | 0.22%   |
| JMicron Technology             | 3         | 3      | 0.22%   |
| Unknown                        | 3         | 3      | 0.22%   |
| Star Drive                     | 2         | 2      | 0.14%   |
| SSSTC                          | 2         | 3      | 0.14%   |
| Solid State Storage Technology | 2         | 2      | 0.14%   |
| ROG                            | 2         | 2      | 0.14%   |
| PNY                            | 2         | 2      | 0.14%   |
| Micron/Crucial Technology      | 2         | 2      | 0.14%   |
| M4-CT128                       | 2         | 2      | 0.14%   |
| Lite-On                        | 2         | 2      | 0.14%   |
| KingSpec                       | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 16        | 1.12%   |
| Kingston SA400S37480G 480GB SSD                     | 13        | 0.91%   |
| Kingston SA400S37120G 120GB SSD                     | 13        | 0.91%   |
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.84%   |
| SanDisk NVMe SSD Drive 512GB                        | 12        | 0.84%   |
| Unknown MMC Card  32GB                              | 11        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.77%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 10        | 0.7%    |
| Seagate ST9500325AS 500GB                           | 9         | 0.63%   |
| Samsung SSD 850 EVO 500GB                           | 9         | 0.63%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.63%   |
| Samsung NVMe SSD Drive 1024GB                       | 9         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 9         | 0.63%   |
| Unknown MMC Card  64GB                              | 8         | 0.56%   |
| Unknown MMC Card  16GB                              | 8         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 8         | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 8         | 0.56%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 8         | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 0.56%   |
| HGST HTS721010A9E630 1TB                            | 8         | 0.56%   |
| Unknown MMC Card  128GB                             | 7         | 0.49%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.49%   |
| Intel NVMe SSD Drive 256GB                          | 7         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 0.42%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 0.42%   |
| Seagate ST320LT007-9ZV142 320GB                     | 6         | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.42%   |
| Kingston SUV400S37120G 120GB SSD                    | 6         | 0.42%   |
| Intel SSDPEKNW010T8 1TB                             | 6         | 0.42%   |
| Intel SSDPEKNU512GZ 512GB                           | 6         | 0.42%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 5         | 0.35%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 5         | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                          | 5         | 0.35%   |
| Micron NVMe SSD Drive 512GB                         | 5         | 0.35%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.35%   |
| Apple SSD SM0256G 256GB                             | 5         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 112    | 32.99%  |
| WDC                 | 66        | 83     | 22.68%  |
| Toshiba             | 38        | 46     | 13.06%  |
| Hitachi             | 38        | 44     | 13.06%  |
| HGST                | 30        | 36     | 10.31%  |
| Samsung Electronics | 7         | 7      | 2.41%   |
| Fujitsu             | 5         | 7      | 1.72%   |
| Apple               | 4         | 4      | 1.37%   |
| Unknown             | 2         | 2      | 0.69%   |
| TO Exter            | 1         | 1      | 0.34%   |
| Intenso             | 1         | 1      | 0.34%   |
| HGST HTS            | 1         | 1      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 145       | 208    | 27.94%  |
| Kingston            | 74        | 100    | 14.26%  |
| SanDisk             | 48        | 60     | 9.25%   |
| Intel               | 46        | 51     | 8.86%   |
| Micron Technology   | 26        | 30     | 5.01%   |
| WDC                 | 25        | 30     | 4.82%   |
| Crucial             | 24        | 33     | 4.62%   |
| Apple               | 24        | 30     | 4.62%   |
| SK hynix            | 18        | 20     | 3.47%   |
| LITEON              | 16        | 21     | 3.08%   |
| Toshiba             | 14        | 22     | 2.7%    |
| OCZ                 | 9         | 9      | 1.73%   |
| LITEONIT            | 7         | 12     | 1.35%   |
| Intenso             | 4         | 4      | 0.77%   |
| China               | 4         | 4      | 0.77%   |
| Transcend           | 3         | 3      | 0.58%   |
| A-DATA Technology   | 3         | 3      | 0.58%   |
| PNY                 | 2         | 2      | 0.39%   |
| M4-CT128            | 2         | 2      | 0.39%   |
| KingSpec            | 2         | 2      | 0.39%   |
| JMicron Technology  | 2         | 2      | 0.39%   |
| Corsair             | 2         | 2      | 0.39%   |
| Verbatim            | 1         | 2      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| Star                | 1         | 1      | 0.19%   |
| SSSTC               | 1         | 2      | 0.19%   |
| Seagate             | 1         | 1      | 0.19%   |
| Radeon              | 1         | 2      | 0.19%   |
| OCZ-VERTEX3         | 1         | 1      | 0.19%   |
| Neo                 | 1         | 1      | 0.19%   |
| MyDigitalSSD        | 1         | 1      | 0.19%   |
| Maxtor              | 1         | 1      | 0.19%   |
| Lexar               | 1         | 1      | 0.19%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.19%   |
| KingFast            | 1         | 1      | 0.19%   |
| JD                  | 1         | 1      | 0.19%   |
| GOODRAM             | 1         | 1      | 0.19%   |
| FORESEE             | 1         | 1      | 0.19%   |
| Colorful            | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 477       | 672    | 36.33%  |
| NVMe    | 472       | 600    | 35.95%  |
| HDD     | 283       | 346    | 21.55%  |
| MMC     | 70        | 85     | 5.33%   |
| Unknown | 11        | 10     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 696       | 996    | 54.76%  |
| NVMe | 471       | 597    | 37.06%  |
| MMC  | 70        | 85     | 5.51%   |
| SAS  | 34        | 35     | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 583       | 807    | 77.22%  |
| 0.51-1.0   | 150       | 186    | 19.87%  |
| 1.01-2.0   | 18        | 21     | 2.38%   |
| 3.01-4.0   | 2         | 2      | 0.26%   |
| 4.01-10.0  | 2         | 2      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 396       | 32.3%   |
| 251-500        | 323       | 26.35%  |
| 501-1000       | 163       | 13.3%   |
| 1-20           | 90        | 7.34%   |
| 1001-2000      | 70        | 5.71%   |
| 51-100         | 69        | 5.63%   |
| Unknown        | 55        | 4.49%   |
| 21-50          | 39        | 3.18%   |
| More than 3000 | 11        | 0.9%    |
| 2001-3000      | 10        | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 521       | 41.06%  |
| 21-50          | 218       | 17.18%  |
| 101-250        | 189       | 14.89%  |
| 51-100         | 148       | 11.66%  |
| 251-500        | 74        | 5.83%   |
| Unknown        | 55        | 4.33%   |
| 501-1000       | 47        | 3.7%    |
| 1001-2000      | 14        | 1.1%    |
| More than 3000 | 1         | 0.08%   |
| 2001-3000      | 1         | 0.08%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 6.9%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 3         | 4      | 5.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 2      | 3.45%   |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 3.45%   |
| HGST HTS725032A7E630 320GB                          | 2         | 2      | 3.45%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 3.45%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 1.72%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 1.72%   |
| Toshiba MK4026GAX RoHS 40GB                         | 1         | 1      | 1.72%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 1.72%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 1.72%   |
| Team L5 LITE SSD 240GB                              | 1         | 1      | 1.72%   |
| SK hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 1.72%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD               | 1         | 1      | 1.72%   |
| Silicon Motion 1TB PCS PCIe M.2 SSD                 | 1         | 1      | 1.72%   |
| Seagate ST980817AS 80GB                             | 1         | 1      | 1.72%   |
| Seagate ST96812A 64GB                               | 1         | 1      | 1.72%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 1.72%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.72%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 1.72%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 1.72%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 1.72%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 1.72%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 1.72%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 1.72%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD      | 1         | 1      | 1.72%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 1.72%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 1.72%   |
| Intel SSDSC2BW480A4 480GB                           | 1         | 1      | 1.72%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 1.72%   |
| Intel SSDSA2BW160G3H 160GB                          | 1         | 1      | 1.72%   |
| Hitachi HTS727550A9E364 500GB                       | 1         | 1      | 1.72%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 1.72%   |
| Hitachi HTS545050B9SA02 500GB                       | 1         | 2      | 1.72%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 1.72%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 1.72%   |
| Hitachi HTS543216L9A300 160GB                       | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 24.14%  |
| Hitachi             | 8         | 9      | 13.79%  |
| HGST                | 7         | 8      | 12.07%  |
| Micron Technology   | 5         | 6      | 8.62%   |
| Intel               | 4         | 5      | 6.9%    |
| Toshiba             | 3         | 3      | 5.17%   |
| WDC                 | 2         | 2      | 3.45%   |
| SK hynix            | 2         | 2      | 3.45%   |
| Samsung Electronics | 2         | 2      | 3.45%   |
| Union Memory        | 1         | 1      | 1.72%   |
| Transcend           | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| Silicon Motion      | 1         | 1      | 1.72%   |
| SanDisk             | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| LITEONIT            | 1         | 1      | 1.72%   |
| Crucial             | 1         | 2      | 1.72%   |
| Corsair             | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |
| Apple               | 1         | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 40%     |
| Hitachi | 8         | 9      | 22.86%  |
| HGST    | 7         | 8      | 20%     |
| Toshiba | 3         | 3      | 8.57%   |
| WDC     | 2         | 2      | 5.71%   |
| Apple   | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 38     | 60.34%  |
| SSD  | 21        | 24     | 36.21%  |
| NVMe | 2         | 2      | 3.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 716       | 1063   | 58.12%  |
| Works    | 458       | 585    | 37.18%  |
| Malfunc  | 57        | 64     | 4.63%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 735       | 54.69%  |
| Samsung Electronics              | 170       | 12.65%  |
| AMD                              | 120       | 8.93%   |
| SanDisk                          | 75        | 5.58%   |
| SK hynix                         | 59        | 4.39%   |
| Toshiba America Info Systems     | 47        | 3.5%    |
| Micron Technology                | 29        | 2.16%   |
| Kingston Technology Company      | 29        | 2.16%   |
| KIOXIA                           | 13        | 0.97%   |
| Phison Electronics               | 12        | 0.89%   |
| Nvidia                           | 10        | 0.74%   |
| Marvell Technology Group         | 6         | 0.45%   |
| Silicon Motion                   | 5         | 0.37%   |
| ADATA Technology                 | 5         | 0.37%   |
| Union Memory (Shenzhen)          | 4         | 0.3%    |
| Solid State Storage Technology   | 4         | 0.3%    |
| Lite-On Technology               | 4         | 0.3%    |
| Lenovo                           | 4         | 0.3%    |
| Apple                            | 4         | 0.3%    |
| Silicon Integrated Systems [SiS] | 3         | 0.22%   |
| Realtek Semiconductor            | 2         | 0.15%   |
| Micron/Crucial Technology        | 2         | 0.15%   |
| Seagate Technology               | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 101       | 7.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 85        | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 82        | 5.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 77        | 5.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 61        | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 59        | 4.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 51        | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 43        | 3.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 37        | 2.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 2.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 32        | 2.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 32        | 2.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 32        | 2.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 23        | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 1.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 21        | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 20        | 1.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 18        | 1.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 1.19%   |
| Intel SSD 660P Series                                                          | 16        | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 16        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 0.84%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 11        | 0.77%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 11        | 0.77%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 11        | 0.77%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 11        | 0.77%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 11        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 0.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 9         | 0.63%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 9         | 0.63%   |
| Intel SSD 600P Series                                                          | 9         | 0.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 9         | 0.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 0.56%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 7         | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 723       | 52.54%  |
| NVMe | 474       | 34.45%  |
| RAID | 98        | 7.12%   |
| IDE  | 81        | 5.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 957       | 81.79%  |
| AMD    | 213       | 18.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 26        | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 25        | 2.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 21        | 1.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 17        | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 15        | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 14        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 13        | 1.11%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 12        | 1.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 11        | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 10        | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 10        | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 9         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 9         | 0.77%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 8         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 8         | 0.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 8         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 8         | 0.68%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.68%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 8         | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 8         | 0.68%   |
| AMD Custom APU 0405                     | 8         | 0.68%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 7         | 0.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 7         | 0.6%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 7         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 0.6%    |
| Intel 12th Gen Core i7-12700H           | 7         | 0.6%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 7         | 0.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 316       | 27.01%  |
| Intel Core i5                  | 300       | 25.64%  |
| Other                          | 128       | 10.94%  |
| Intel Core i3                  | 60        | 5.13%   |
| AMD Ryzen 7                    | 53        | 4.53%   |
| Intel Core 2 Duo               | 45        | 3.85%   |
| Intel Celeron                  | 45        | 3.85%   |
| AMD Ryzen 5                    | 36        | 3.08%   |
| Intel Pentium                  | 15        | 1.28%   |
| Intel Atom                     | 13        | 1.11%   |
| AMD Ryzen 9                    | 13        | 1.11%   |
| AMD Ryzen 3                    | 11        | 0.94%   |
| AMD A8                         | 11        | 0.94%   |
| AMD A6                         | 11        | 0.94%   |
| Intel Genuine                  | 10        | 0.85%   |
| AMD Ryzen 7 PRO                | 9         | 0.77%   |
| Intel Core 2                   | 8         | 0.68%   |
| AMD E1                         | 8         | 0.68%   |
| AMD A4                         | 7         | 0.6%    |
| Intel Xeon                     | 6         | 0.51%   |
| Intel Core i9                  | 6         | 0.51%   |
| AMD Ryzen 5 PRO                | 6         | 0.51%   |
| AMD A10                        | 6         | 0.51%   |
| AMD E                          | 5         | 0.43%   |
| Intel Pentium Silver           | 4         | 0.34%   |
| Intel Pentium M                | 4         | 0.34%   |
| Intel Pentium Dual             | 4         | 0.34%   |
| Intel Core m3                  | 3         | 0.26%   |
| Intel Celeron Dual-Core        | 3         | 0.26%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.26%   |
| AMD Sempron                    | 2         | 0.17%   |
| AMD Athlon II Dual-Core        | 2         | 0.17%   |
| AMD Athlon 64 X2               | 2         | 0.17%   |
| Intel Pentium Dual-Core        | 1         | 0.09%   |
| Intel Core m7                  | 1         | 0.09%   |
| Intel Core m5                  | 1         | 0.09%   |
| Intel Celeron M                | 1         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.09%   |
| AMD Turion II Dual-Core        | 1         | 0.09%   |
| AMD Turion 64 Mobile           | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 565       | 48.29%  |
| 4      | 380       | 32.48%  |
| 8      | 89        | 7.61%   |
| 6      | 85        | 7.26%   |
| 1      | 17        | 1.45%   |
| 14     | 15        | 1.28%   |
| 12     | 9         | 0.77%   |
| 10     | 9         | 0.77%   |
| 24     | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1170      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 934       | 79.76%  |
| 1      | 237       | 20.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1148      | 97.87%  |
| Unknown        | 16        | 1.36%   |
| 32-bit         | 9         | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 350       | 28.81%  |
| 0x306a9    | 61        | 5.02%   |
| 0x206a7    | 50        | 4.12%   |
| 0x40651    | 48        | 3.95%   |
| 0x806c1    | 47        | 3.87%   |
| 0x306d4    | 44        | 3.62%   |
| 0x306c3    | 42        | 3.46%   |
| 0x406e3    | 41        | 3.37%   |
| 0x806ea    | 37        | 3.05%   |
| 0x806ec    | 36        | 2.96%   |
| 0x806e9    | 34        | 2.8%    |
| 0x906ea    | 26        | 2.14%   |
| 0x20655    | 25        | 2.06%   |
| 0x906e9    | 23        | 1.89%   |
| 0x1067a    | 23        | 1.89%   |
| 0x0a50000c | 19        | 1.56%   |
| 0xa0652    | 13        | 1.07%   |
| 0x08600106 | 13        | 1.07%   |
| 0x806eb    | 12        | 0.99%   |
| 0x6fd      | 11        | 0.91%   |
| 0x0700010f | 11        | 0.91%   |
| 0x906a3    | 10        | 0.82%   |
| 0x406c4    | 10        | 0.82%   |
| 0x08608103 | 10        | 0.82%   |
| 0x08108109 | 10        | 0.82%   |
| 0x806d1    | 9         | 0.74%   |
| 0x506e3    | 9         | 0.74%   |
| 0x30678    | 9         | 0.74%   |
| 0x20652    | 8         | 0.66%   |
| 0x0810100b | 8         | 0.66%   |
| 0x706e5    | 7         | 0.58%   |
| 0x6fb      | 7         | 0.58%   |
| 0x6f6      | 7         | 0.58%   |
| 0x08108102 | 7         | 0.58%   |
| 0x06001119 | 7         | 0.58%   |
| 0x05000119 | 7         | 0.58%   |
| 0x906ed    | 6         | 0.49%   |
| 0x10676    | 6         | 0.49%   |
| 0x0a404102 | 6         | 0.49%   |
| 0x40661    | 5         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 238       | 20.34%  |
| Haswell          | 117       | 10%     |
| IvyBridge        | 85        | 7.26%   |
| SandyBridge      | 76        | 6.5%    |
| Skylake          | 65        | 5.56%   |
| Unknown          | 64        | 5.47%   |
| TigerLake        | 61        | 5.21%   |
| Broadwell        | 50        | 4.27%   |
| Zen 3            | 41        | 3.5%    |
| Westmere         | 40        | 3.42%   |
| Silvermont       | 38        | 3.25%   |
| Penryn           | 38        | 3.25%   |
| Core             | 34        | 2.91%   |
| Zen 2            | 24        | 2.05%   |
| CometLake        | 23        | 1.97%   |
| IceLake          | 20        | 1.71%   |
| Alderlake Hybrid | 20        | 1.71%   |
| Zen+             | 19        | 1.62%   |
| Excavator        | 15        | 1.28%   |
| Zen              | 12        | 1.03%   |
| Piledriver       | 11        | 0.94%   |
| Jaguar           | 11        | 0.94%   |
| Goldmont plus    | 10        | 0.85%   |
| Puma             | 9         | 0.77%   |
| K8 Hammer        | 7         | 0.6%    |
| Bobcat           | 7         | 0.6%    |
| P6               | 6         | 0.51%   |
| K10 Llano        | 6         | 0.51%   |
| K10              | 5         | 0.43%   |
| Goldmont         | 5         | 0.43%   |
| Bonnell          | 5         | 0.43%   |
| Nehalem          | 4         | 0.34%   |
| K8 & K10 hybrid  | 3         | 0.26%   |
| Tremont          | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 863       | 59.15%  |
| Nvidia                           | 334       | 22.89%  |
| AMD                              | 259       | 17.75%  |
| Silicon Integrated Systems [SiS] | 3         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 75        | 4.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68        | 4.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 63        | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 53        | 3.51%   |
| Intel UHD Graphics 620                                                                   | 51        | 3.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 49        | 3.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 2.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 2.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 2.58%   |
| Intel HD Graphics 620                                                                    | 38        | 2.52%   |
| Intel HD Graphics 5500                                                                   | 37        | 2.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.79%   |
| Intel HD Graphics 630                                                                    | 26        | 1.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 24        | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.26%   |
| AMD Lucienne                                                                             | 18        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1.13%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 17        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 13        | 0.86%   |
| AMD Rembrandt [Radeon 680M]                                                              | 12        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.53%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 8         | 0.53%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.53%   |
| Intel HD Graphics 530                                                                    | 8         | 0.53%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 8         | 0.53%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 604       | 51.49%  |
| Intel + Nvidia | 226       | 19.27%  |
| 1 x AMD        | 174       | 14.83%  |
| 1 x Nvidia     | 77        | 6.56%   |
| Intel + AMD    | 31        | 2.64%   |
| AMD + Nvidia   | 31        | 2.64%   |
| 2 x AMD        | 24        | 2.05%   |
| 1 x SiS        | 3         | 0.26%   |
| 2 x Intel      | 2         | 0.17%   |
| Other          | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 973       | 82.18%  |
| Proprietary | 186       | 15.71%  |
| Unknown     | 25        | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 797       | 66.75%  |
| 0.01-0.5   | 137       | 11.47%  |
| 1.01-2.0   | 121       | 10.13%  |
| 3.01-4.0   | 55        | 4.61%   |
| 0.51-1.0   | 55        | 4.61%   |
| 5.01-6.0   | 13        | 1.09%   |
| 7.01-8.0   | 12        | 1.01%   |
| 2.01-3.0   | 4         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 298       | 21.93%  |
| LG Display              | 177       | 13.02%  |
| Chimei Innolux          | 165       | 12.14%  |
| Samsung Electronics     | 142       | 10.45%  |
| BOE                     | 106       | 7.8%    |
| Sharp                   | 65        | 4.78%   |
| Apple                   | 51        | 3.75%   |
| Dell                    | 41        | 3.02%   |
| Lenovo                  | 33        | 2.43%   |
| Chi Mei Optoelectronics | 25        | 1.84%   |
| Philips                 | 23        | 1.69%   |
| InfoVision              | 22        | 1.62%   |
| Hewlett-Packard         | 22        | 1.62%   |
| CSO                     | 18        | 1.32%   |
| LG Philips              | 17        | 1.25%   |
| BenQ                    | 13        | 0.96%   |
| AOC                     | 12        | 0.88%   |
| Ancor Communications    | 12        | 0.88%   |
| PANDA                   | 11        | 0.81%   |
| Goldstar                | 11        | 0.81%   |
| ASUSTek Computer        | 10        | 0.74%   |
| Acer                    | 10        | 0.74%   |
| Panasonic               | 6         | 0.44%   |
| Sony                    | 5         | 0.37%   |
| LGD                     | 5         | 0.37%   |
| BOE Technology Group    | 5         | 0.37%   |
| Vestel Elektronik       | 4         | 0.29%   |
| Valve                   | 4         | 0.29%   |
| Quanta Display          | 4         | 0.29%   |
| Unknown                 | 3         | 0.22%   |
| Toshiba                 | 3         | 0.22%   |
| Eizo                    | 3         | 0.22%   |
| Analogix                | 3         | 0.22%   |
| Nvidia                  | 2         | 0.15%   |
| Fujitsu Siemens         | 2         | 0.15%   |
| CPT                     | 2         | 0.15%   |
| VOXICON                 | 1         | 0.07%   |
| ViewSonic               | 1         | 0.07%   |
| TMX                     | 1         | 0.07%   |
| TCL                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 16        | 1.16%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 13        | 0.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 11        | 0.8%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 10        | 0.73%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 9         | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 8         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 7         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.51%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 6         | 0.44%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 6         | 0.44%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 5         | 0.36%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 5         | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 5         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 5         | 0.36%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 5         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch         | 5         | 0.36%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                   | 5         | 0.36%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 4         | 0.29%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 4         | 0.29%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 4         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 4         | 0.29%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch               | 4         | 0.29%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch           | 4         | 0.29%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch           | 4         | 0.29%   |
| InfoVision LCD Monitor IVO857F 1920x1080 294x165mm 13.3-inch           | 4         | 0.29%   |
| Hewlett-Packard E243i HPN3462 1920x1200 518x324mm 24.1-inch            | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch        | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 4         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 558       | 43.06%  |
| 1366x768 (WXGA)    | 279       | 21.53%  |
| 3840x2160 (4K)     | 80        | 6.17%   |
| 2560x1440 (QHD)    | 55        | 4.24%   |
| 1280x800 (WXGA)    | 49        | 3.78%   |
| 1600x900 (HD+)     | 48        | 3.7%    |
| 1920x1200 (WUXGA)  | 46        | 3.55%   |
| 2560x1600          | 30        | 2.31%   |
| 1440x900 (WXGA+)   | 24        | 1.85%   |
| 2880x1800          | 20        | 1.54%   |
| 3840x2400          | 17        | 1.31%   |
| 1680x1050 (WSXGA+) | 16        | 1.23%   |
| 3440x1440          | 13        | 1%      |
| 3200x1800 (QHD+)   | 8         | 0.62%   |
| 800x1280           | 7         | 0.54%   |
| 1024x768 (XGA)     | 6         | 0.46%   |
| 1280x1024 (SXGA)   | 5         | 0.39%   |
| 1024x600           | 5         | 0.39%   |
| 2160x1440          | 4         | 0.31%   |
| 1920x540           | 4         | 0.31%   |
| Unknown            | 4         | 0.31%   |
| 2288x1287          | 3         | 0.23%   |
| 1360x768           | 3         | 0.23%   |
| 3840x1080          | 2         | 0.15%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3456x2160          | 1         | 0.08%   |
| 3200x2000          | 1         | 0.08%   |
| 2880x1920          | 1         | 0.08%   |
| 2560x1700          | 1         | 0.08%   |
| 2560x1080          | 1         | 0.08%   |
| 2240x1400          | 1         | 0.08%   |
| 1920x1280          | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 433       | 31.84%  |
| 13      | 264       | 19.41%  |
| 14      | 185       | 13.6%   |
| 17      | 80        | 5.88%   |
| 27      | 65        | 4.78%   |
| 12      | 63        | 4.63%   |
| 24      | 52        | 3.82%   |
| 23      | 27        | 1.99%   |
| 11      | 24        | 1.76%   |
| Unknown | 24        | 1.76%   |
| 16      | 23        | 1.69%   |
| 31      | 16        | 1.18%   |
| 34      | 11        | 0.81%   |
| 84      | 8         | 0.59%   |
| 22      | 8         | 0.59%   |
| 21      | 8         | 0.59%   |
| 18      | 7         | 0.51%   |
| 32      | 5         | 0.37%   |
| 19      | 5         | 0.37%   |
| 10      | 5         | 0.37%   |
| 65      | 4         | 0.29%   |
| 54      | 4         | 0.29%   |
| 7       | 4         | 0.29%   |
| 39      | 3         | 0.22%   |
| 29      | 3         | 0.22%   |
| 3       | 3         | 0.22%   |
| 142     | 2         | 0.15%   |
| 72      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 40      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 35      | 2         | 0.15%   |
| 33      | 2         | 0.15%   |
| 25      | 2         | 0.15%   |
| 20      | 2         | 0.15%   |
| 86      | 1         | 0.07%   |
| 75      | 1         | 0.07%   |
| 74      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 744       | 55.19%  |
| 201-300        | 242       | 17.95%  |
| 501-600        | 133       | 9.87%   |
| 351-400        | 90        | 6.68%   |
| 601-700        | 26        | 1.93%   |
| 401-500        | 26        | 1.93%   |
| Unknown        | 24        | 1.78%   |
| 701-800        | 17        | 1.26%   |
| 1501-2000      | 12        | 0.89%   |
| 1001-1500      | 12        | 0.89%   |
| 801-900        | 8         | 0.59%   |
| 1-100          | 7         | 0.52%   |
| 901-1000       | 4         | 0.3%    |
| More than 2000 | 2         | 0.15%   |
| 101-200        | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 929       | 76.78%  |
| 16/10   | 207       | 17.11%  |
| Unknown | 22        | 1.82%   |
| 21/9    | 16        | 1.32%   |
| 3/2     | 10        | 0.83%   |
| 4/3     | 7         | 0.58%   |
| 5/4     | 6         | 0.5%    |
| 6/5     | 4         | 0.33%   |
| 0.67    | 4         | 0.33%   |
| 1.00    | 2         | 0.17%   |
| 32/9    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 427       | 31.47%  |
| 81-90          | 328       | 24.17%  |
| 71-80          | 119       | 8.77%   |
| 121-130        | 69        | 5.08%   |
| 201-250        | 67        | 4.94%   |
| 301-350        | 66        | 4.86%   |
| 61-70          | 60        | 4.42%   |
| 351-500        | 37        | 2.73%   |
| 251-300        | 28        | 2.06%   |
| More than 1000 | 25        | 1.84%   |
| 51-60          | 25        | 1.84%   |
| 111-120        | 24        | 1.77%   |
| Unknown        | 24        | 1.77%   |
| 131-140        | 14        | 1.03%   |
| 501-1000       | 10        | 0.74%   |
| 151-200        | 9         | 0.66%   |
| 1-40           | 7         | 0.52%   |
| 141-150        | 7         | 0.52%   |
| 41-50          | 6         | 0.44%   |
| 91-100         | 5         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 561       | 42.12%  |
| 101-120       | 310       | 23.27%  |
| 51-100        | 186       | 13.96%  |
| 161-240       | 153       | 11.49%  |
| More than 240 | 76        | 5.71%   |
| Unknown       | 24        | 1.8%    |
| 1-50          | 22        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 940       | 78.73%  |
| 2     | 205       | 17.17%  |
| 3     | 24        | 2.01%   |
| 0     | 24        | 2.01%   |
| 5     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 705       | 39.17%  |
| Realtek Semiconductor                  | 469       | 26.06%  |
| Qualcomm Atheros                       | 204       | 11.33%  |
| Broadcom                               | 123       | 6.83%   |
| MediaTek                               | 42        | 2.33%   |
| Broadcom Limited                       | 41        | 2.28%   |
| Hewlett-Packard                        | 19        | 1.06%   |
| ASIX Electronics                       | 18        | 1%      |
| Sierra Wireless                        | 17        | 0.94%   |
| Marvell Technology Group               | 16        | 0.89%   |
| Dell                                   | 14        | 0.78%   |
| Ralink                                 | 13        | 0.72%   |
| Lenovo                                 | 12        | 0.67%   |
| Ericsson Business Mobile Networks      | 9         | 0.5%    |
| Qualcomm                               | 8         | 0.44%   |
| Nvidia                                 | 8         | 0.44%   |
| TP-Link                                | 7         | 0.39%   |
| DisplayLink                            | 7         | 0.39%   |
| Huawei Technologies                    | 6         | 0.33%   |
| ASUSTek Computer                       | 6         | 0.33%   |
| Fibocom                                | 5         | 0.28%   |
| Samsung Electronics                    | 4         | 0.22%   |
| Ralink Technology                      | 4         | 0.22%   |
| NetGear                                | 4         | 0.22%   |
| Xiaomi                                 | 3         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.17%   |
| D-Link                                 | 3         | 0.17%   |
| Texas Instruments                      | 2         | 0.11%   |
| STMicroelectronics                     | 2         | 0.11%   |
| Qualcomm Atheros Communications        | 2         | 0.11%   |
| Microsoft                              | 2         | 0.11%   |
| JMicron Technology                     | 2         | 0.11%   |
| ZyXEL Communications                   | 1         | 0.06%   |
| Wacom                                  | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| SEGGER                                 | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Novatek Microelectronics               | 1         | 0.06%   |
| Micro Star International               | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 284       | 12.57%  |
| Intel Wireless 8265 / 8275                                        | 82        | 3.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 2.79%   |
| Intel Wireless 7260                                               | 61        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 2.35%   |
| Intel Wi-Fi 6 AX200                                               | 53        | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 2.26%   |
| Intel Wi-Fi 6 AX201                                               | 47        | 2.08%   |
| Intel Wireless 7265                                               | 46        | 2.04%   |
| Intel Wireless 8260                                               | 44        | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 32        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 30        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 1.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 26        | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.8%    |
| Intel Wireless 3160                                               | 17        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 17        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 17        | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 17        | 0.75%   |
| Intel Wireless-AC 9260                                            | 16        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.66%   |
| Intel Centrino Advanced-N 6200                                    | 15        | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 673       | 54.41%  |
| Qualcomm Atheros                  | 173       | 13.99%  |
| Realtek Semiconductor             | 137       | 11.08%  |
| Broadcom                          | 94        | 7.6%    |
| MediaTek                          | 42        | 3.4%    |
| Broadcom Limited                  | 27        | 2.18%   |
| Sierra Wireless                   | 17        | 1.37%   |
| Ralink                            | 13        | 1.05%   |
| Dell                              | 9         | 0.73%   |
| Qualcomm                          | 7         | 0.57%   |
| ASUSTek Computer                  | 6         | 0.49%   |
| TP-Link                           | 5         | 0.4%    |
| Fibocom                           | 5         | 0.4%    |
| Ralink Technology                 | 4         | 0.32%   |
| NetGear                           | 4         | 0.32%   |
| Hewlett-Packard                   | 4         | 0.32%   |
| Qualcomm Atheros Communications   | 2         | 0.16%   |
| Ericsson Business Mobile Networks | 2         | 0.16%   |
| D-Link                            | 2         | 0.16%   |
| ZyXEL Communications              | 1         | 0.08%   |
| Wacom                             | 1         | 0.08%   |
| Microsoft                         | 1         | 0.08%   |
| Micro Star International          | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| IMC Networks                      | 1         | 0.08%   |
| Fujitsu Siemens Computers         | 1         | 0.08%   |
| Edimax Technology                 | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| Chu Yuen Enterprise               | 1         | 0.08%   |
| Belkin Components                 | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 82        | 6.59%   |
| Intel Wireless 7260                                                  | 61        | 4.9%    |
| Intel Wi-Fi 6 AX200                                                  | 53        | 4.26%   |
| Intel Wi-Fi 6 AX201                                                  | 47        | 3.78%   |
| Intel Wireless 7265                                                  | 46        | 3.7%    |
| Intel Wireless 8260                                                  | 44        | 3.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 36        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 32        | 2.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 32        | 2.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 30        | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 27        | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 26        | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 24        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 23        | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 23        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 23        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 22        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 18        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 18        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 18        | 1.45%   |
| Intel Wireless 3160                                                  | 17        | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 17        | 1.37%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 17        | 1.37%   |
| Intel Wireless-AC 9260                                               | 16        | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 16        | 1.29%   |
| Intel Centrino Advanced-N 6200                                       | 15        | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 14        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 14        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 13        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 13        | 1.05%   |
| Intel Centrino Advanced-N 6235                                       | 12        | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 12        | 0.96%   |
| Intel Centrino Ultimate-N 6300                                       | 11        | 0.88%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                  | 10        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 10        | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 10        | 0.8%    |
| Intel Centrino Wireless-N 2230                                       | 10        | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 10        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 9         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 8         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 411       | 42.41%  |
| Intel                                  | 335       | 34.57%  |
| Qualcomm Atheros                       | 63        | 6.5%    |
| Broadcom                               | 54        | 5.57%   |
| ASIX Electronics                       | 18        | 1.86%   |
| Marvell Technology Group               | 16        | 1.65%   |
| Broadcom Limited                       | 15        | 1.55%   |
| Lenovo                                 | 12        | 1.24%   |
| Nvidia                                 | 8         | 0.83%   |
| DisplayLink                            | 7         | 0.72%   |
| Hewlett-Packard                        | 6         | 0.62%   |
| Huawei Technologies                    | 5         | 0.52%   |
| Xiaomi                                 | 3         | 0.31%   |
| Samsung Electronics                    | 3         | 0.31%   |
| TP-Link                                | 2         | 0.21%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.21%   |
| JMicron Technology                     | 2         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Qualcomm                               | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| ICS Advent                             | 1         | 0.1%    |
| Gemtek                                 | 1         | 0.1%    |
| D-Link                                 | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 284       | 29.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 63        | 6.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 5.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 5.21%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 2.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 2.25%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 2.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 17        | 1.74%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 1.53%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 1.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 1.53%   |
| Intel Ethernet Connection (13) I219-V                             | 14        | 1.43%   |
| Intel Ethernet Connection I219-V                                  | 13        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 10        | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.82%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                            | 6         | 0.61%   |
| DisplayLink Dell Universal Dock D6000                             | 6         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.51%   |
| Huawei MAR-LX1M                                                   | 5         | 0.51%   |
| HP lt4120 Snapdragon X5 LTE                                       | 5         | 0.51%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.51%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 5         | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 5         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1159      | 54.49%  |
| Ethernet | 930       | 43.72%  |
| Modem    | 35        | 1.65%   |
| Unknown  | 3         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 951       | 76.39%  |
| Ethernet | 293       | 23.53%  |
| Unknown  | 1         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 820       | 70.03%  |
| 1     | 332       | 28.35%  |
| 3     | 11        | 0.94%   |
| 0     | 8         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1100      | 93.38%  |
| Yes  | 78        | 6.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 521       | 53.11%  |
| Realtek Semiconductor           | 78        | 7.95%   |
| Qualcomm Atheros Communications | 62        | 6.32%   |
| IMC Networks                    | 54        | 5.5%    |
| Broadcom                        | 54        | 5.5%    |
| Foxconn / Hon Hai               | 52        | 5.3%    |
| Apple                           | 45        | 4.59%   |
| Lite-On Technology              | 33        | 3.36%   |
| Hewlett-Packard                 | 20        | 2.04%   |
| Dell                            | 16        | 1.63%   |
| ASUSTek Computer                | 10        | 1.02%   |
| Ralink                          | 7         | 0.71%   |
| Cambridge Silicon Radio         | 7         | 0.71%   |
| Toshiba                         | 5         | 0.51%   |
| USI                             | 3         | 0.31%   |
| Realtek                         | 3         | 0.31%   |
| MediaTek                        | 3         | 0.31%   |
| Ralink Technology               | 2         | 0.2%    |
| Chicony Electronics             | 2         | 0.2%    |
| Taiyo Yuden                     | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Creative Technology             | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 237       | 24.06%  |
| Intel Bluetooth Device                              | 115       | 11.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 58        | 5.89%   |
| Realtek Bluetooth Radio                             | 54        | 5.48%   |
| Intel AX200 Bluetooth                               | 52        | 5.28%   |
| Apple Bluetooth Host Controller                     | 27        | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 2.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 2.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 1.62%   |
| Apple Bluetooth USB Host Controller                 | 16        | 1.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.52%   |
| IMC Networks Wireless_Device                        | 15        | 1.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 1.42%   |
| Intel AX210 Bluetooth                               | 13        | 1.32%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 1.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 1.02%   |
| Lite-On Bluetooth Device                            | 9         | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.91%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.91%   |
| IMC Networks Bluetooth Device                       | 8         | 0.81%   |
| IMC Networks 802.11ac WLAN Adapter                  | 8         | 0.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.61%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.51%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 938       | 64.16%  |
| AMD                              | 230       | 15.73%  |
| Nvidia                           | 179       | 12.24%  |
| C-Media Electronics              | 17        | 1.16%   |
| Realtek Semiconductor            | 12        | 0.82%   |
| GN Netcom                        | 10        | 0.68%   |
| Logitech                         | 9         | 0.62%   |
| Lenovo                           | 8         | 0.55%   |
| Plantronics                      | 6         | 0.41%   |
| Kingston Technology              | 5         | 0.34%   |
| Hewlett-Packard                  | 5         | 0.34%   |
| ASUSTek Computer                 | 4         | 0.27%   |
| Silicon Integrated Systems [SiS] | 3         | 0.21%   |
| SAVITECH                         | 3         | 0.21%   |
| RODE Microphones                 | 3         | 0.21%   |
| Apple                            | 3         | 0.21%   |
| Texas Instruments                | 2         | 0.14%   |
| SteelSeries ApS                  | 2         | 0.14%   |
| DSEA A/S                         | 2         | 0.14%   |
| Creative Technology              | 2         | 0.14%   |
| XMOS                             | 1         | 0.07%   |
| Unknown                          | 1         | 0.07%   |
| SlrTek                           | 1         | 0.07%   |
| Samson Technologies              | 1         | 0.07%   |
| QinHeng Electronics              | 1         | 0.07%   |
| PreSonus Audio Electronics       | 1         | 0.07%   |
| No brand                         | 1         | 0.07%   |
| Line6                            | 1         | 0.07%   |
| LG Electronics                   | 1         | 0.07%   |
| JMTek                            | 1         | 0.07%   |
| JBL                              | 1         | 0.07%   |
| GYROCOM C&C                      | 1         | 0.07%   |
| Generalplus Technology           | 1         | 0.07%   |
| Focusrite-Novation               | 1         | 0.07%   |
| Elite Silicon                    | 1         | 0.07%   |
| Digidesign                       | 1         | 0.07%   |
| Corsair                          | 1         | 0.07%   |
| Conexant Systems                 | 1         | 0.07%   |
| Asahi Kasei Microsystems         | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 147       | 8.22%   |
| AMD Family 17h/19h HD Audio Controller                                     | 124       | 6.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 92        | 5.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 72        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 68        | 3.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 63        | 3.52%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 3.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 61        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 2.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 50        | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 50        | 2.8%    |
| Intel Broadwell-U Audio Controller                                         | 50        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 44        | 2.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 42        | 2.35%   |
| AMD FCH Azalia Controller                                                  | 39        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36        | 2.01%   |
| Intel CM238 HD Audio Controller                                            | 30        | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 30        | 1.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 29        | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 27        | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 1.4%    |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 21        | 1.17%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 17        | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 14        | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 13        | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 13        | 0.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 13        | 0.73%   |
| Realtek Semiconductor USB Audio                                            | 12        | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 0.67%   |
| AMD Trinity HDMI Audio Controller                                          | 11        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 225       | 31.25%  |
| SK hynix            | 166       | 23.06%  |
| Micron Technology   | 118       | 16.39%  |
| Unknown             | 50        | 6.94%   |
| Kingston            | 50        | 6.94%   |
| Corsair             | 22        | 3.06%   |
| Crucial             | 19        | 2.64%   |
| Ramaxel Technology  | 15        | 2.08%   |
| Elpida              | 14        | 1.94%   |
| A-DATA Technology   | 11        | 1.53%   |
| Unknown             | 6         | 0.83%   |
| Nanya Technology    | 5         | 0.69%   |
| Unknown (ABCD)      | 2         | 0.28%   |
| Team                | 2         | 0.28%   |
| Patriot             | 2         | 0.28%   |
| GSkill              | 2         | 0.28%   |
| G.Skill             | 2         | 0.28%   |
| TEXTORM             | 1         | 0.14%   |
| Qimonda             | 1         | 0.14%   |
| Netlist             | 1         | 0.14%   |
| Neo Forza           | 1         | 0.14%   |
| GOODRAM             | 1         | 0.14%   |
| fef5                | 1         | 0.14%   |
| Avant               | 1         | 0.14%   |
| ASint Technology    | 1         | 0.14%   |
| Apacer              | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 13        | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 1.17%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.04%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 1.04%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 7         | 0.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.91%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.78%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.78%   |
| Unknown                                                          | 6         | 0.78%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 5         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 5         | 0.65%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.65%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.65%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 0.65%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 5         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.65%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.52%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 4         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 0.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.52%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 4         | 0.52%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.52%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.52%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 4         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 275       | 43.17%  |
| DDR3    | 213       | 33.44%  |
| LPDDR4  | 47        | 7.38%   |
| LPDDR3  | 33        | 5.18%   |
| DDR2    | 22        | 3.45%   |
| LPDDR5  | 16        | 2.51%   |
| DDR5    | 12        | 1.88%   |
| SDRAM   | 10        | 1.57%   |
| DRAM    | 3         | 0.47%   |
| DDR     | 3         | 0.47%   |
| Unknown | 3         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 541       | 84.01%  |
| Row Of Chips | 88        | 13.66%  |
| Chip         | 10        | 1.55%   |
| Unknown      | 3         | 0.47%   |
| DIMM         | 2         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 276       | 39.88%  |
| 4096  | 168       | 24.28%  |
| 16384 | 138       | 19.94%  |
| 2048  | 82        | 11.85%  |
| 1024  | 13        | 1.88%   |
| 32768 | 12        | 1.73%   |
| 512   | 3         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 157       | 23.05%  |
| 3200    | 119       | 17.47%  |
| 2667    | 111       | 16.3%   |
| 2133    | 47        | 6.9%    |
| 2400    | 44        | 6.46%   |
| 1334    | 32        | 4.7%    |
| 4267    | 29        | 4.26%   |
| 1333    | 20        | 2.94%   |
| 6400    | 15        | 2.2%    |
| Unknown | 15        | 2.2%    |
| 667     | 13        | 1.91%   |
| 1867    | 12        | 1.76%   |
| 4800    | 10        | 1.47%   |
| 4266    | 10        | 1.47%   |
| 1067    | 9         | 1.32%   |
| 3266    | 7         | 1.03%   |
| 4199    | 5         | 0.73%   |
| 800     | 5         | 0.73%   |
| 8400    | 3         | 0.44%   |
| 5600    | 2         | 0.29%   |
| 3733    | 2         | 0.29%   |
| 2048    | 2         | 0.29%   |
| 1066    | 2         | 0.29%   |
| 975     | 2         | 0.29%   |
| 533     | 2         | 0.29%   |
| 333     | 2         | 0.29%   |
| 7467    | 1         | 0.15%   |
| 5500    | 1         | 0.15%   |
| 1639    | 1         | 0.15%   |
| 266     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| Samsung Electronics | 2         | 25%     |
| Oki Data            | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung SCX-3200 Series      | 1         | 12.5%   |
| Samsung M2070 Series         | 1         | 12.5%   |
| Oki Data USB Device          | 1         | 12.5%   |
| HP LaserJet P2035            | 1         | 12.5%   |
| HP ENVY 4520 series          | 1         | 12.5%   |
| HP DeskJet 5650c             | 1         | 12.5%   |
| HP DeskJet 2700 series       | 1         | 12.5%   |
| Brother QL-500 label printer | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 25%     |
| HP ScanJet 2200c                            | 1         | 25%     |
| Canon CanoScan LiDE 100                     | 1         | 25%     |
| Canon CanoScan 4400F                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 275       | 26.93%  |
| IMC Networks                           | 100       | 9.79%   |
| Microdia                               | 98        | 9.6%    |
| Realtek Semiconductor                  | 77        | 7.54%   |
| Bison Electronics                      | 73        | 7.15%   |
| Sunplus Innovation Technology          | 52        | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 4.41%   |
| Quanta                                 | 41        | 4.02%   |
| Lite-On Technology                     | 39        | 3.82%   |
| Apple                                  | 34        | 3.33%   |
| Suyin                                  | 29        | 2.84%   |
| Syntek                                 | 24        | 2.35%   |
| Acer                                   | 21        | 2.06%   |
| Luxvisions Innotech Limited            | 17        | 1.67%   |
| Logitech                               | 17        | 1.67%   |
| Ricoh                                  | 10        | 0.98%   |
| Lenovo                                 | 10        | 0.98%   |
| Alcor Micro                            | 8         | 0.78%   |
| Silicon Motion                         | 6         | 0.59%   |
| Samsung Electronics                    | 6         | 0.59%   |
| ALi                                    | 6         | 0.59%   |
| Sonix Technology                       | 5         | 0.49%   |
| DigiTech                               | 4         | 0.39%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.29%   |
| Primax Electronics                     | 3         | 0.29%   |
| SunplusIT                              | 2         | 0.2%    |
| Sunplus Technology                     | 2         | 0.2%    |
| Microsoft                              | 2         | 0.2%    |
| Importek                               | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |
| Z-Star Microelectronics                | 1         | 0.1%    |
| ShineTech                              | 1         | 0.1%    |
| Polycom                                | 1         | 0.1%    |
| LG Electronics                         | 1         | 0.1%    |
| Intel                                  | 1         | 0.1%    |
| Generalplus Technology                 | 1         | 0.1%    |
| Etron Technology                       | 1         | 0.1%    |
| BRS 2Mp Camera                         | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 69        | 6.71%   |
| Microdia Integrated_Webcam_HD                                            | 48        | 4.67%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 40        | 3.89%   |
| IMC Networks Integrated Camera                                           | 31        | 3.02%   |
| Realtek Integrated_Webcam_HD                                             | 28        | 2.72%   |
| Chicony HD WebCam                                                        | 23        | 2.24%   |
| Chicony HP HD Camera                                                     | 21        | 2.04%   |
| Bison Integrated Camera                                                  | 21        | 2.04%   |
| Lite-On HP HD Camera                                                     | 18        | 1.75%   |
| Syntek Integrated Camera                                                 | 16        | 1.56%   |
| Sunplus Integrated_Webcam_HD                                             | 13        | 1.26%   |
| Sunplus HD WebCam                                                        | 13        | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 1.17%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 1.17%   |
| Quanta HP HD Camera                                                      | 11        | 1.07%   |
| Lite-On Integrated Camera                                                | 11        | 1.07%   |
| Bison Lenovo EasyCamera                                                  | 11        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 11        | 1.07%   |
| Realtek USB Camera                                                       | 10        | 0.97%   |
| Chicony HP HD Webcam [Fixed]                                             | 10        | 0.97%   |
| Apple FaceTime HD Camera                                                 | 10        | 0.97%   |
| Quanta HD User Facing                                                    | 9         | 0.88%   |
| Chicony USB2.0 Camera                                                    | 9         | 0.88%   |
| Chicony HP HD Webcam                                                     | 9         | 0.88%   |
| Quanta HP TrueVision HD Camera                                           | 8         | 0.78%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 8         | 0.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 8         | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 0.78%   |
| Chicony Integrated HP HD Webcam                                          | 8         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 8         | 0.78%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                                             | 7         | 0.68%   |
| Chicony HP Truevision HD                                                 | 7         | 0.68%   |
| Apple Built-in iSight                                                    | 7         | 0.68%   |
| Suyin HP TrueVision HD                                                   | 6         | 0.58%   |
| Sunplus HP HD Webcam [Fixed]                                             | 6         | 0.58%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 6         | 0.58%   |
| Quanta HD Webcam                                                         | 6         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 6         | 0.58%   |
| Microdia Integrated Webcam                                               | 6         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 127       | 46.18%  |
| Synaptics                  | 75        | 27.27%  |
| Shenzhen Goodix Technology | 22        | 8%      |
| Elan Microelectronics      | 14        | 5.09%   |
| Upek                       | 13        | 4.73%   |
| AuthenTec                  | 11        | 4%      |
| LighTuning Technology      | 7         | 2.55%   |
| STMicroelectronics         | 6         | 2.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 16.36%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 6.91%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 6.18%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 5.82%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 5.09%   |
| Validity Sensors VFS491                                                    | 12        | 4.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.36%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.64%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 2.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.18%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.18%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.18%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 2.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.82%   |
| AuthenTec AES2810                                                          | 5         | 1.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.82%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.09%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.09%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.73%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.73%   |
| Synaptics WBDI                                                             | 2         | 0.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.73%   |
| Unknown                                                                    | 2         | 0.73%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.36%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.36%   |
| Synaptics WBDI Device                                                      | 1         | 0.36%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.36%   |
| Synaptics  WBDI                                                            | 1         | 0.36%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 70        | 44.03%  |
| Broadcom    | 64        | 40.25%  |
| O2 Micro    | 12        | 7.55%   |
| Lenovo      | 7         | 4.4%    |
| Upek        | 5         | 3.14%   |
| Yubico.com  | 1         | 0.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 44.03%  |
| Broadcom 58200                                                               | 19        | 11.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 11.32%  |
| Broadcom 5880                                                                | 14        | 8.81%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 6.29%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.4%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.26%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 631       | 52.54%  |
| 1     | 432       | 35.97%  |
| 2     | 123       | 10.24%  |
| 3     | 12        | 1%      |
| 4     | 2         | 0.17%   |
| 7     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 275       | 38.84%  |
| Chipcard                 | 147       | 20.76%  |
| Graphics card            | 95        | 13.42%  |
| Net/wireless             | 57        | 8.05%   |
| Multimedia controller    | 48        | 6.78%   |
| Camera                   | 24        | 3.39%   |
| Bluetooth                | 20        | 2.82%   |
| Communication controller | 15        | 2.12%   |
| Sound                    | 6         | 0.85%   |
| Storage                  | 5         | 0.71%   |
| Card reader              | 5         | 0.71%   |
| Net/ethernet             | 4         | 0.56%   |
| Modem                    | 2         | 0.28%   |
| Flash memory             | 2         | 0.28%   |
| Storage/nvme             | 1         | 0.14%   |
| Storage/ide              | 1         | 0.14%   |
| Storage/ata              | 1         | 0.14%   |

