Linux in Switzerland - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

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

Total: 1507

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| Star Labs     | LabTop                      | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Lenovo        | G50-30 80G0                 | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| Acer          | Aspire V3-772G              | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| Dell          | Latitude E6420              | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| Dell          | Latitude 7490               | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| GPD           | P2 MAX                      | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Swift SF514-52T             | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Latitude E6530              | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Valve         | Jupiter                     | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| Dell          | Latitude 5520               | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Acer          | Aspire 5332                 | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| HP            | Compaq 6910p                | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| Acer          | Predator PH18-71            | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Dell          | Vostro 3558                 | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Dell          | Latitude 5520               | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| HP            | EliteBook 820 G1            | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| Dell          | XPS 17 9720                 | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| Dell          | Latitude 7530               | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Valve         | Jupiter                     | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| Fujitsu       | LIFEBOOK E736               | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| HP            | ProBook 430 G4              | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude E6440              | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| Fujitsu       | CELSIUS H780                | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| Lenovo        | Z51-70 80K6                 | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Acer          | Aspire V3-371               | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | GL702VM                     | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| HP            | ProBook 4720s               | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| HP            | EliteBook 865 16 inch G9... | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| HP            | Pavilion dv7                | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| HP            | Pavilion dv7                | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Dell          | XPS 13 9360                 | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | B50-10 80QR                 | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | ProBook 650 G4              | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Acer          | Aspire E5-511               | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Acer          | Predator G9-591             | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| Valve         | Jupiter                     | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | X556UAK                     | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| HP            | ENVY dv7                    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Notebook      | L140PU                      | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Dell          | Latitude E6420              | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| Dell          | XPS 9320                    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Apple         | MacBookPro4,1               | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| Dell          | Precision 5520              | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| Samsung       | RC530/RC730                 | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| HP            | ProBook 640 G2              | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| ASUSTek       | K55VJ                       | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| Gigabyte      | RC14UD                      | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| HP            | EliteBook Folio 1040 G2     | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| Acer          | Aspire S5-371               | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Acer          | Aspire 5942                 | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| Acer          | V3-771                      | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Shuttle       | DS437                       | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| Acer          | Predator G9-791             | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| Dell          | Inspiron 5570               | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| HP            | Unknown                     | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Acer          | Aspire V3-772G              | [283eb3c040](https://linux-hardware.org/?probe=283eb3c040) | Aug 06, 2022 |
| MSI           | GT72S 6QE                   | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| Lenovo        | ThinkPad T470s 20HGS36K0... | [caf10d48a0](https://linux-hardware.org/?probe=caf10d48a0) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| Lenovo        | ThinkPad P51 20HH001RMZ     | [3fee9267ba](https://linux-hardware.org/?probe=3fee9267ba) | Jul 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [44a5e2107e](https://linux-hardware.org/?probe=44a5e2107e) | Jul 27, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| Acer          | Aspire 5738                 | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Sony          | SVE1513R1EB                 | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Alienware     | 17 R5                       | [29b538f1c0](https://linux-hardware.org/?probe=29b538f1c0) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| Acer          | V3-771                      | [809bd80b9a](https://linux-hardware.org/?probe=809bd80b9a) | Jul 17, 2022 |
| Lenovo        | ThinkPad T410 25379UG       | [00478c63ba](https://linux-hardware.org/?probe=00478c63ba) | Jul 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [41c6118825](https://linux-hardware.org/?probe=41c6118825) | Jul 15, 2022 |
| HP            | Pavilion dv7                | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| HP            | ProBook 440 G6              | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| HUAWEI        | KLVL-WXXW                   | [0e5d573899](https://linux-hardware.org/?probe=0e5d573899) | Jul 09, 2022 |
| HP            | EliteBook Folio 1040 G2     | [c58559e78c](https://linux-hardware.org/?probe=c58559e78c) | Jul 09, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| HP            | Pavilion dv7                | [ee1a040981](https://linux-hardware.org/?probe=ee1a040981) | Jul 06, 2022 |
| MSI           | GE62 2QF                    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Dell          | Latitude 7530               | [0d40af60b2](https://linux-hardware.org/?probe=0d40af60b2) | Jul 01, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Acer          | Aspire V3-772G              | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Aspire V3-772G              | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| Clevo         | W150ER                      | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| Dell          | XPS 13 9380                 | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| HUAWEI        | MACH-WX9                    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SF515-51T             | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Timi          | TM1613                      | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Acer          | V3-771                      | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Dell          | XPS 15 7590                 | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| TUXEDO        | N2x0WU                      | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Sony          | VPCF23S1E                   | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Toshiba       | TECRA R840                  | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Apple         | MacBookPro9,2               | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| Apple         | MacBookPro11,3              | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| Acer          | Aspire A515-56              | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| HP            | ENVY 17                     | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| System76      | Galago Pro                  | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| Acer          | Swift SF514-51              | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Latitude D400               | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| Apple         | MacBookPro10,1              | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| HP            | ProBook 450 G5              | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Acer          | Aspire E5-773G              | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| HP            | Pavilion g7                 | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| ASUSTek       | K73E                        | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| Dell          | Latitude 5400               | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| Acer          | Aspire V3-772G              | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| Acer          | Swift SF314-42              | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| Medion        | P6624                       | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| Dell          | XPS 15 9560                 | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| Dell          | Latitude 7490               | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| Acer          | Aspire 3820                 | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| HP            | Compaq 15                   | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| Packard Be... | EasyNote TV44HC             | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Acer          | Aspire V3-772G              | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| Clevo         | W76x/M77xCUH                | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| AMI           | Cherry Trail Tablet         | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| Apple         | MacBookPro5,3               | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| HP            | Pavilion g7                 | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| Acer          | Aspire V3-772G              | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| Dell          | XPS 15 9510                 | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| Acer          | Aspire V3-772G              | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| Acer          | Aspire R7-572G              | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| Apple         | MacBookPro14,3              | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| HP            | Pavilion dv7                | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| HP            | ProBook 4740s               | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| Acer          | Aspire A315-31              | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| HP            | Pavilion dv7                | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Apple         | MacBookAir3,1               | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| HP            | ENVY dv7                    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| Lenovo        | G50-70 20351                | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| MSI           | MS-17G                      | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2067df0e1e](https://linux-hardware.org/?probe=2067df0e1e) | Nov 16, 2021 |
| Acer          | Aspire V3-772G              | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| HP            | ZBook 15 G2                 | [f40c4458aa](https://linux-hardware.org/?probe=f40c4458aa) | Nov 16, 2021 |
| Dell          | Latitude E7240              | [aaf6395a70](https://linux-hardware.org/?probe=aaf6395a70) | Nov 14, 2021 |
| Dell          | Latitude E7270              | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| HP            | EliteBook 735 G5            | [79600db29f](https://linux-hardware.org/?probe=79600db29f) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3876a60641](https://linux-hardware.org/?probe=3876a60641) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [92b50813ac](https://linux-hardware.org/?probe=92b50813ac) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| ASUSTek       | UX430UNR                    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| Acer          | V3-771                      | [bf99ad481c](https://linux-hardware.org/?probe=bf99ad481c) | Nov 04, 2021 |
| ASUSTek       | U36SD                       | [84e47bb477](https://linux-hardware.org/?probe=84e47bb477) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Acer          | TravelMate P459-G2-MG       | [05087f89c1](https://linux-hardware.org/?probe=05087f89c1) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| Acer          | TravelMate P459-G2-MG       | [4a80b949aa](https://linux-hardware.org/?probe=4a80b949aa) | Oct 30, 2021 |
| HP            | EliteBook 840 G6            | [d0307fd66e](https://linux-hardware.org/?probe=d0307fd66e) | Oct 29, 2021 |
| HP            | EliteBook 840 G6            | [a5abf5d5ee](https://linux-hardware.org/?probe=a5abf5d5ee) | Oct 29, 2021 |
| Medion        | S3409 MD60234               | [4bb4415dae](https://linux-hardware.org/?probe=4bb4415dae) | Oct 27, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | [a567978a3c](https://linux-hardware.org/?probe=a567978a3c) | Oct 26, 2021 |
| Acer          | V3-771                      | [b953b67d06](https://linux-hardware.org/?probe=b953b67d06) | Oct 25, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Packard Be... | EasyNote TV44HC             | [5ebedd4a1c](https://linux-hardware.org/?probe=5ebedd4a1c) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [3517455df5](https://linux-hardware.org/?probe=3517455df5) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Medion        | E6226                       | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4f400bb9ab](https://linux-hardware.org/?probe=4f400bb9ab) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4d7535970d](https://linux-hardware.org/?probe=4d7535970d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [d8302cc197](https://linux-hardware.org/?probe=d8302cc197) | Oct 19, 2021 |
| Acer          | Aspire 1410                 | [dc42de3c30](https://linux-hardware.org/?probe=dc42de3c30) | Oct 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [dda062734d](https://linux-hardware.org/?probe=dda062734d) | Oct 17, 2021 |
| Dell          | XPS 15 7590                 | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Dell          | Latitude 5410               | [bdd46a0cd7](https://linux-hardware.org/?probe=bdd46a0cd7) | Oct 14, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [62872f38de](https://linux-hardware.org/?probe=62872f38de) | Oct 14, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [b72f6d9f64](https://linux-hardware.org/?probe=b72f6d9f64) | Oct 08, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [770a47642f](https://linux-hardware.org/?probe=770a47642f) | Oct 03, 2021 |
| Acer          | Aspire A515-52              | [1f5c815672](https://linux-hardware.org/?probe=1f5c815672) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Acer          | Aspire 1410                 | [8db88d13ec](https://linux-hardware.org/?probe=8db88d13ec) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | [cc4ac84959](https://linux-hardware.org/?probe=cc4ac84959) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [2c7e4f944f](https://linux-hardware.org/?probe=2c7e4f944f) | Sep 18, 2021 |
| Acer          | Swift SF515-51T             | [a0a6460520](https://linux-hardware.org/?probe=a0a6460520) | Sep 17, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ab2e5dcff2](https://linux-hardware.org/?probe=ab2e5dcff2) | Sep 14, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f01a6435b7](https://linux-hardware.org/?probe=f01a6435b7) | Sep 14, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [60ee8c9731](https://linux-hardware.org/?probe=60ee8c9731) | Sep 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | [c11d22f126](https://linux-hardware.org/?probe=c11d22f126) | Sep 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3333d2aabd](https://linux-hardware.org/?probe=3333d2aabd) | Sep 09, 2021 |
| Lenovo        | ThinkPad L460 20FVS01500    | [065324adcb](https://linux-hardware.org/?probe=065324adcb) | Sep 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Medion        | S3409 MD60234               | [30a93543cd](https://linux-hardware.org/?probe=30a93543cd) | Sep 07, 2021 |
| Medion        | S3409 MD60234               | [274fe63960](https://linux-hardware.org/?probe=274fe63960) | Sep 06, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| Packard Be... | EasyNote TV44HC             | [87353376d7](https://linux-hardware.org/?probe=87353376d7) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [4fc1ff5f76](https://linux-hardware.org/?probe=4fc1ff5f76) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2087b72fe1](https://linux-hardware.org/?probe=2087b72fe1) | Aug 31, 2021 |
| Packard Be... | EasyNote TV44HC             | [4d4510dbfb](https://linux-hardware.org/?probe=4d4510dbfb) | Aug 30, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [6f82a1cdeb](https://linux-hardware.org/?probe=6f82a1cdeb) | Aug 30, 2021 |
| Samsung       | 700G7C                      | [9bdbd478e5](https://linux-hardware.org/?probe=9bdbd478e5) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| Acer          | Aspire ES1-512              | [666660f555](https://linux-hardware.org/?probe=666660f555) | Aug 29, 2021 |
| Dell          | Precision M6700             | [c1e66e1633](https://linux-hardware.org/?probe=c1e66e1633) | Aug 28, 2021 |
| TrekStor      | Surfbook E11B               | [9014dfda1f](https://linux-hardware.org/?probe=9014dfda1f) | Aug 26, 2021 |
| Dell          | Precision 5520              | [12782a8da6](https://linux-hardware.org/?probe=12782a8da6) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [76b34b8383](https://linux-hardware.org/?probe=76b34b8383) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | [35b4ea3ba9](https://linux-hardware.org/?probe=35b4ea3ba9) | Aug 24, 2021 |
| Dell          | Precision 5520              | [43f1c9c69c](https://linux-hardware.org/?probe=43f1c9c69c) | Aug 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [3598b4e555](https://linux-hardware.org/?probe=3598b4e555) | Aug 23, 2021 |
| Dell          | Latitude E5550              | [186ab38330](https://linux-hardware.org/?probe=186ab38330) | Aug 23, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| HP            | EliteBook Folio 9470m       | [ddd4cdd7ca](https://linux-hardware.org/?probe=ddd4cdd7ca) | Aug 22, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [47cea1b5c7](https://linux-hardware.org/?probe=47cea1b5c7) | Aug 20, 2021 |
| Dell          | Precision 5520              | [bb6728e105](https://linux-hardware.org/?probe=bb6728e105) | Aug 19, 2021 |
| Dell          | Precision 5520              | [87389dc90a](https://linux-hardware.org/?probe=87389dc90a) | Aug 19, 2021 |
| Acer          | V3-771                      | [5235c8cb39](https://linux-hardware.org/?probe=5235c8cb39) | Aug 18, 2021 |
| Acer          | Aspire 5253                 | [8d12d69ada](https://linux-hardware.org/?probe=8d12d69ada) | Aug 18, 2021 |
| Toshiba       | Satellite C660D             | [eb50acee36](https://linux-hardware.org/?probe=eb50acee36) | Aug 16, 2021 |
| Toshiba       | Satellite C660D             | [2afd21c6f7](https://linux-hardware.org/?probe=2afd21c6f7) | Aug 16, 2021 |
| Acer          | Aspire 5253                 | [06a6ece9cb](https://linux-hardware.org/?probe=06a6ece9cb) | Aug 16, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [d628c6c320](https://linux-hardware.org/?probe=d628c6c320) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| HP            | ProBook 650 G2              | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | [4b51090679](https://linux-hardware.org/?probe=4b51090679) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [f78358fed7](https://linux-hardware.org/?probe=f78358fed7) | Aug 13, 2021 |
| Dell          | Latitude 7490               | [3c3c535058](https://linux-hardware.org/?probe=3c3c535058) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [33a205253e](https://linux-hardware.org/?probe=33a205253e) | Aug 10, 2021 |
| HP            | ENVY dv7                    | [888257031e](https://linux-hardware.org/?probe=888257031e) | Aug 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [92fb2e26c0](https://linux-hardware.org/?probe=92fb2e26c0) | Aug 10, 2021 |
| Dell          | Latitude E7440              | [89a521499a](https://linux-hardware.org/?probe=89a521499a) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [05628cae80](https://linux-hardware.org/?probe=05628cae80) | Aug 09, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| TUXEDO        | Unknown                     | [15b26f4936](https://linux-hardware.org/?probe=15b26f4936) | Aug 07, 2021 |
| Acer          | Aspire E5-571G              | [ed862d4cb6](https://linux-hardware.org/?probe=ed862d4cb6) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | [80fafef64f](https://linux-hardware.org/?probe=80fafef64f) | Aug 05, 2021 |
| Dell          | Inspiron 15-5578            | [1169a22f51](https://linux-hardware.org/?probe=1169a22f51) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b70933531](https://linux-hardware.org/?probe=5b70933531) | Aug 01, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| HP            | Pavilion dv7                | [e9254ad52f](https://linux-hardware.org/?probe=e9254ad52f) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [3963220295](https://linux-hardware.org/?probe=3963220295) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | [f8eb40a0a3](https://linux-hardware.org/?probe=f8eb40a0a3) | Jul 30, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [9cf9065745](https://linux-hardware.org/?probe=9cf9065745) | Jul 30, 2021 |
| Dell          | Latitude E5550              | [84d60c9f30](https://linux-hardware.org/?probe=84d60c9f30) | Jul 30, 2021 |
| Dell          | XPS 13 9310                 | [4ad09b336f](https://linux-hardware.org/?probe=4ad09b336f) | Jul 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [cde8deea7e](https://linux-hardware.org/?probe=cde8deea7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| Lenovo        | G580 20150                  | [a52bc56d5e](https://linux-hardware.org/?probe=a52bc56d5e) | Jul 23, 2021 |
| Medion        | E6226                       | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| HP            | Pavilion g7                 | [59f46869ee](https://linux-hardware.org/?probe=59f46869ee) | Jul 21, 2021 |
| HP            | Pavilion g7                 | [b71a21e87a](https://linux-hardware.org/?probe=b71a21e87a) | Jul 21, 2021 |
| HP            | ProBook 450 G3              | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Medion        | P6618                       | [d8b3d2db11](https://linux-hardware.org/?probe=d8b3d2db11) | Jul 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [5c3f0aef89](https://linux-hardware.org/?probe=5c3f0aef89) | Jul 17, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [c61db52d00](https://linux-hardware.org/?probe=c61db52d00) | Jul 16, 2021 |
| Dell          | XPS 13 9360                 | [90fcb82f7e](https://linux-hardware.org/?probe=90fcb82f7e) | Jul 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [427828621f](https://linux-hardware.org/?probe=427828621f) | Jul 12, 2021 |
| Acer          | Swift SF114-33              | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| Toshiba       | NB550D                      | [6e4b998cc0](https://linux-hardware.org/?probe=6e4b998cc0) | Jul 12, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [04163e3fa8](https://linux-hardware.org/?probe=04163e3fa8) | Jul 12, 2021 |
| Notebook      | NS50MU                      | [6841e398e3](https://linux-hardware.org/?probe=6841e398e3) | Jul 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | [6c9599ccf7](https://linux-hardware.org/?probe=6c9599ccf7) | Jul 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [8887f14351](https://linux-hardware.org/?probe=8887f14351) | Jul 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [7bbd48efde](https://linux-hardware.org/?probe=7bbd48efde) | Jul 03, 2021 |
| Lenovo        | ThinkPad T450s 20BX004KM... | [dbd8629d3c](https://linux-hardware.org/?probe=dbd8629d3c) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | [78ad5dbea0](https://linux-hardware.org/?probe=78ad5dbea0) | Jul 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [6fde0ddd03](https://linux-hardware.org/?probe=6fde0ddd03) | Jul 01, 2021 |
| HP            | Laptop 15-bs0xx             | [934190169c](https://linux-hardware.org/?probe=934190169c) | Jun 30, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | [05a46ada33](https://linux-hardware.org/?probe=05a46ada33) | Jun 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [ea4ab7e535](https://linux-hardware.org/?probe=ea4ab7e535) | Jun 22, 2021 |
| HP            | ProBook 470 G5              | [94fbab0837](https://linux-hardware.org/?probe=94fbab0837) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32c83da9dd](https://linux-hardware.org/?probe=32c83da9dd) | Jun 19, 2021 |
| Apple         | MacBookPro14,1              | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [96ee62e1dc](https://linux-hardware.org/?probe=96ee62e1dc) | Jun 15, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire E5-571G              | [455a20d0a7](https://linux-hardware.org/?probe=455a20d0a7) | Jun 10, 2021 |
| Acer          | Aspire E5-571G              | [467c46c227](https://linux-hardware.org/?probe=467c46c227) | Jun 08, 2021 |
| Dell          | XPS 13 9310                 | [5456739d8f](https://linux-hardware.org/?probe=5456739d8f) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| HP            | ProBook 4510s (NX684EA)     | [55591c1e24](https://linux-hardware.org/?probe=55591c1e24) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Dell          | Inspiron 5577               | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Dell          | XPS 15 7590                 | [08b1e4c99f](https://linux-hardware.org/?probe=08b1e4c99f) | Jun 05, 2021 |
| Acer          | Aspire 1410                 | [c0022674fa](https://linux-hardware.org/?probe=c0022674fa) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell          | Latitude E7440              | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [c1ec69ad60](https://linux-hardware.org/?probe=c1ec69ad60) | Jun 02, 2021 |
| HP            | 355 G2                      | [c80a118e90](https://linux-hardware.org/?probe=c80a118e90) | May 29, 2021 |
| Acer          | Aspire 7736                 | [f8cf9b2aa2](https://linux-hardware.org/?probe=f8cf9b2aa2) | May 29, 2021 |
| HP            | ENVY 17                     | [bdaee2e27b](https://linux-hardware.org/?probe=bdaee2e27b) | May 28, 2021 |
| Acer          | Aspire F5-573G              | [d0c45f9b31](https://linux-hardware.org/?probe=d0c45f9b31) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| HP            | Unknown                     | [42eeaf84d9](https://linux-hardware.org/?probe=42eeaf84d9) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| Notebook      | NH5x_7xDPx                  | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [901f37d11b](https://linux-hardware.org/?probe=901f37d11b) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [39f2002b6b](https://linux-hardware.org/?probe=39f2002b6b) | May 19, 2021 |
| Acer          | Aspire 1410                 | [877462fbca](https://linux-hardware.org/?probe=877462fbca) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| HP            | Compaq CQ58                 | [710fdca60a](https://linux-hardware.org/?probe=710fdca60a) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| HP            | ProBook 455 G4              | [aca836bae8](https://linux-hardware.org/?probe=aca836bae8) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [42a1bf7901](https://linux-hardware.org/?probe=42a1bf7901) | May 14, 2021 |
| HP            | Pavilion 15                 | [7e38915bdc](https://linux-hardware.org/?probe=7e38915bdc) | May 13, 2021 |
| HP            | OMEN by Laptop              | [43907153c2](https://linux-hardware.org/?probe=43907153c2) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [36ade7dd15](https://linux-hardware.org/?probe=36ade7dd15) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [06c1bbc65e](https://linux-hardware.org/?probe=06c1bbc65e) | May 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [b313183fd5](https://linux-hardware.org/?probe=b313183fd5) | May 11, 2021 |
| Acer          | Swift SF114-33              | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [e126e1aa0c](https://linux-hardware.org/?probe=e126e1aa0c) | May 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| Acer          | Swift SF114-33              | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Google        | Lars                        | [2cba94fe45](https://linux-hardware.org/?probe=2cba94fe45) | May 08, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [eedf4bb0ca](https://linux-hardware.org/?probe=eedf4bb0ca) | May 08, 2021 |
| Acer          | Swift SF314-42              | [f28c9e243e](https://linux-hardware.org/?probe=f28c9e243e) | May 07, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | [d6154d7955](https://linux-hardware.org/?probe=d6154d7955) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LM... | [0b155bcbcd](https://linux-hardware.org/?probe=0b155bcbcd) | May 04, 2021 |
| HP            | Notebook                    | [4e09e8ff3b](https://linux-hardware.org/?probe=4e09e8ff3b) | May 03, 2021 |
| HP            | 2133                        | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| Alienware     | m15 R2                      | [4884d06d2e](https://linux-hardware.org/?probe=4884d06d2e) | May 02, 2021 |
| HP            | EliteBook Folio 1040 G1     | [226f359e79](https://linux-hardware.org/?probe=226f359e79) | May 01, 2021 |
| HP            | 250 G7 Notebook PC          | [e69f0b2a6e](https://linux-hardware.org/?probe=e69f0b2a6e) | May 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ08    | [7efd61973c](https://linux-hardware.org/?probe=7efd61973c) | Apr 30, 2021 |
| Lenovo        | Z50-70 20354                | [93033f85c6](https://linux-hardware.org/?probe=93033f85c6) | Apr 29, 2021 |
| HP            | 2133                        | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Alienware     | m15 R2                      | [77d90d2a91](https://linux-hardware.org/?probe=77d90d2a91) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | [909c049308](https://linux-hardware.org/?probe=909c049308) | Apr 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6fd9f38406](https://linux-hardware.org/?probe=6fd9f38406) | Apr 26, 2021 |
| Dell          | Latitude E7440              | [b8c6136bd0](https://linux-hardware.org/?probe=b8c6136bd0) | Apr 26, 2021 |
| HP            | EliteBook 2170p             | [98a664ebcc](https://linux-hardware.org/?probe=98a664ebcc) | Apr 26, 2021 |
| ASUSTek       | K72Jr                       | [ff3ba69d3e](https://linux-hardware.org/?probe=ff3ba69d3e) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| OriginPC      | ND-17                       | [8ff850fe97](https://linux-hardware.org/?probe=8ff850fe97) | Apr 25, 2021 |
| ASUSTek       | K72Jr                       | [bcc4e8b350](https://linux-hardware.org/?probe=bcc4e8b350) | Apr 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [41ade399b3](https://linux-hardware.org/?probe=41ade399b3) | Apr 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | [38221d2991](https://linux-hardware.org/?probe=38221d2991) | Apr 21, 2021 |
| Acer          | Aspire 1410                 | [7288f31e3c](https://linux-hardware.org/?probe=7288f31e3c) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5b66c48c4a](https://linux-hardware.org/?probe=5b66c48c4a) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Dell          | Latitude E7240              | [45870a7f89](https://linux-hardware.org/?probe=45870a7f89) | Apr 14, 2021 |
| whyopencom... | Unknown                     | [aad3ad526f](https://linux-hardware.org/?probe=aad3ad526f) | Apr 13, 2021 |
| HP            | 250 G6 Notebook PC          | [bc738ac65f](https://linux-hardware.org/?probe=bc738ac65f) | Apr 11, 2021 |
| Dell          | XPS 13 9343                 | [4d759a05db](https://linux-hardware.org/?probe=4d759a05db) | Apr 09, 2021 |
| Dell          | Latitude E6500              | [3bdee6855c](https://linux-hardware.org/?probe=3bdee6855c) | Apr 07, 2021 |
| Lenovo        | IdeaPad Yoga 13 2191        | [44aa3ba48f](https://linux-hardware.org/?probe=44aa3ba48f) | Apr 05, 2021 |
| Dell          | XPS 15 9570                 | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| TrekStor      | Surfbook E11B               | [464dce7796](https://linux-hardware.org/?probe=464dce7796) | Apr 01, 2021 |
| Dell          | Latitude E5450              | [5ce2bad1c1](https://linux-hardware.org/?probe=5ce2bad1c1) | Mar 29, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [449ee0c3ef](https://linux-hardware.org/?probe=449ee0c3ef) | Mar 28, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | [44e41b06e8](https://linux-hardware.org/?probe=44e41b06e8) | Mar 28, 2021 |
| Medion        | S3409 MD60234               | [eee4e7256b](https://linux-hardware.org/?probe=eee4e7256b) | Mar 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [7e10f0b649](https://linux-hardware.org/?probe=7e10f0b649) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [27a3733dc4](https://linux-hardware.org/?probe=27a3733dc4) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [f00d8623c8](https://linux-hardware.org/?probe=f00d8623c8) | Mar 24, 2021 |
| Lenovo        | ThinkPad T460s 20F9005CS... | [c03bed695b](https://linux-hardware.org/?probe=c03bed695b) | Mar 24, 2021 |
| HP            | 250 G8 Notebook PC          | [8889dc5ad5](https://linux-hardware.org/?probe=8889dc5ad5) | Mar 22, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [045f977209](https://linux-hardware.org/?probe=045f977209) | Mar 22, 2021 |
| Acer          | V3-771                      | [a602c93819](https://linux-hardware.org/?probe=a602c93819) | Mar 21, 2021 |
| Apple         | MacBookAir5,2               | [23d38894c7](https://linux-hardware.org/?probe=23d38894c7) | Mar 20, 2021 |
| Dell          | Inspiron 7577               | [25f556cacf](https://linux-hardware.org/?probe=25f556cacf) | Mar 18, 2021 |
| HP            | EliteBook 2760p             | [49ee1765af](https://linux-hardware.org/?probe=49ee1765af) | Mar 16, 2021 |
| HP            | EliteBook 2760p             | [20bf0cfe70](https://linux-hardware.org/?probe=20bf0cfe70) | Mar 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| ASUSTek       | GL702ZC                     | [1d220bf375](https://linux-hardware.org/?probe=1d220bf375) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Acer          | Aspire E1-731               | [23ea26d43f](https://linux-hardware.org/?probe=23ea26d43f) | Mar 12, 2021 |
| Acer          | Aspire 7736                 | [f3777d97b2](https://linux-hardware.org/?probe=f3777d97b2) | Mar 11, 2021 |
| Medion        | E6226                       | [fd72b6bbc9](https://linux-hardware.org/?probe=fd72b6bbc9) | Mar 11, 2021 |
| Dell          | Latitude E7440              | [4521f4c1a3](https://linux-hardware.org/?probe=4521f4c1a3) | Mar 10, 2021 |
| HP            | ProBook 4720s               | [1dbaa2aa4b](https://linux-hardware.org/?probe=1dbaa2aa4b) | Mar 10, 2021 |
| GPD           | P2 MAX                      | [931b98f992](https://linux-hardware.org/?probe=931b98f992) | Mar 09, 2021 |
| Acer          | Nitro AN515-52              | [332460236a](https://linux-hardware.org/?probe=332460236a) | Mar 09, 2021 |
| Lenovo        | G50-80 80E5                 | [7d142fb2ab](https://linux-hardware.org/?probe=7d142fb2ab) | Mar 09, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Fujitsu       | LIFEBOOK E782               | [b926f7249f](https://linux-hardware.org/?probe=b926f7249f) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [6aea799f3a](https://linux-hardware.org/?probe=6aea799f3a) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | [f87b2a351a](https://linux-hardware.org/?probe=f87b2a351a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [025319ae47](https://linux-hardware.org/?probe=025319ae47) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| Acer          | Aspire A315-42              | [44974397a8](https://linux-hardware.org/?probe=44974397a8) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E782               | [0c2c32289a](https://linux-hardware.org/?probe=0c2c32289a) | Feb 28, 2021 |
| HP            | Pavilion Notebook g6        | [e8fb0d80d6](https://linux-hardware.org/?probe=e8fb0d80d6) | Feb 27, 2021 |
| Medion        | P6624                       | [29fba6cccc](https://linux-hardware.org/?probe=29fba6cccc) | Feb 24, 2021 |
| HP            | Pavilion Notebook g6        | [786a3e39df](https://linux-hardware.org/?probe=786a3e39df) | Feb 21, 2021 |
| Toshiba       | QOSMIO X770                 | [1d2a7b2b7a](https://linux-hardware.org/?probe=1d2a7b2b7a) | Feb 20, 2021 |
| Acer          | V3-771                      | [b6e90947b8](https://linux-hardware.org/?probe=b6e90947b8) | Feb 20, 2021 |
| HP            | Pavilion g7                 | [35f315adb8](https://linux-hardware.org/?probe=35f315adb8) | Feb 19, 2021 |
| HP            | Pavilion g7                 | [93b1476aa8](https://linux-hardware.org/?probe=93b1476aa8) | Feb 19, 2021 |
| HP            | Laptop 15-bs0xx             | [f80d7003a7](https://linux-hardware.org/?probe=f80d7003a7) | Feb 18, 2021 |
| TUXEDO        | N13xWU                      | [905dae2b25](https://linux-hardware.org/?probe=905dae2b25) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [fd4dd43574](https://linux-hardware.org/?probe=fd4dd43574) | Feb 16, 2021 |
| ASUSTek       | GL702ZC                     | [8730756c6f](https://linux-hardware.org/?probe=8730756c6f) | Feb 16, 2021 |
| Samsung       | 730U3E/740U3E               | [094783ff7a](https://linux-hardware.org/?probe=094783ff7a) | Feb 15, 2021 |
| ASUSTek       | X550ZE                      | [d8957c1789](https://linux-hardware.org/?probe=d8957c1789) | Feb 14, 2021 |
| Acer          | Aspire E5-774G              | [f002df90ed](https://linux-hardware.org/?probe=f002df90ed) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6e7025de29](https://linux-hardware.org/?probe=6e7025de29) | Feb 14, 2021 |
| Medion        | S621xT                      | [3b77cd1079](https://linux-hardware.org/?probe=3b77cd1079) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [d955eb3433](https://linux-hardware.org/?probe=d955eb3433) | Feb 14, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| Samsung       | 730U3E/740U3E               | [df4eb897c9](https://linux-hardware.org/?probe=df4eb897c9) | Feb 12, 2021 |
| Apple         | MacBookPro10,1              | [0fdb263ea1](https://linux-hardware.org/?probe=0fdb263ea1) | Feb 11, 2021 |
| Acer          | V3-771                      | [525217a48b](https://linux-hardware.org/?probe=525217a48b) | Feb 07, 2021 |
| Dell          | Latitude E5440              | [421629b6e9](https://linux-hardware.org/?probe=421629b6e9) | Feb 07, 2021 |
| Medion        | X782X                       | [384e3543dd](https://linux-hardware.org/?probe=384e3543dd) | Feb 05, 2021 |
| Apple         | MacBookPro9,2               | [c3062ebba4](https://linux-hardware.org/?probe=c3062ebba4) | Feb 04, 2021 |
| Apple         | MacBookPro9,2               | [2203826b83](https://linux-hardware.org/?probe=2203826b83) | Feb 04, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Sony          | SVE1511F4E                  | [6e713387ef](https://linux-hardware.org/?probe=6e713387ef) | Feb 01, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [669829c000](https://linux-hardware.org/?probe=669829c000) | Jan 31, 2021 |
| HP            | ZBook 17 G2                 | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Hampoo        | Cherry Trail CR             | [ecaf6db2cc](https://linux-hardware.org/?probe=ecaf6db2cc) | Jan 31, 2021 |
| Schenker      | VIA 15 Pro                  | [4f091c50f8](https://linux-hardware.org/?probe=4f091c50f8) | Jan 30, 2021 |
| Acer          | V3-771                      | [84fb01f37b](https://linux-hardware.org/?probe=84fb01f37b) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Acer          | Aspire 7736                 | [361d552fde](https://linux-hardware.org/?probe=361d552fde) | Jan 28, 2021 |
| Sony          | VGN-AR61ZU                  | [32858b781b](https://linux-hardware.org/?probe=32858b781b) | Jan 25, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Lenovo        | ThinkPad X260 20F6CT01WW    | [6f921d73e3](https://linux-hardware.org/?probe=6f921d73e3) | Jan 20, 2021 |
| Lenovo        | ThinkPad Edge E530 32597... | [bb6fc12e56](https://linux-hardware.org/?probe=bb6fc12e56) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | [d2bc47e82b](https://linux-hardware.org/?probe=d2bc47e82b) | Jan 20, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Lenovo        | ThinkPad T430 2349G5G       | [f552a37632](https://linux-hardware.org/?probe=f552a37632) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| ASUSTek       | GL702ZC                     | [ba6a149cba](https://linux-hardware.org/?probe=ba6a149cba) | Jan 17, 2021 |
| Acer          | Nitro AN515-52              | [f5873c65c2](https://linux-hardware.org/?probe=f5873c65c2) | Jan 17, 2021 |
| GPD           | P2 MAX                      | [cdc2c0ab67](https://linux-hardware.org/?probe=cdc2c0ab67) | Jan 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [951df975ad](https://linux-hardware.org/?probe=951df975ad) | Jan 17, 2021 |
| whyopencom... | Unknown                     | [c120bc7ad7](https://linux-hardware.org/?probe=c120bc7ad7) | Jan 17, 2021 |
| ASUSTek       | F5RL                        | [79907a946b](https://linux-hardware.org/?probe=79907a946b) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e07ae256e7](https://linux-hardware.org/?probe=e07ae256e7) | Jan 16, 2021 |
| Notebook      | W65_67SZ                    | [1992f23f11](https://linux-hardware.org/?probe=1992f23f11) | Jan 15, 2021 |
| whyopencom... | Unknown                     | [05e1dc54c4](https://linux-hardware.org/?probe=05e1dc54c4) | Jan 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [680db2a270](https://linux-hardware.org/?probe=680db2a270) | Jan 14, 2021 |
| HP            | Laptop 15s-eq1xxx           | [51f542581b](https://linux-hardware.org/?probe=51f542581b) | Jan 13, 2021 |
| Sony          | SVE1511F4E                  | [18f6b7a23f](https://linux-hardware.org/?probe=18f6b7a23f) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Dell          | Latitude XT2                | [958e277130](https://linux-hardware.org/?probe=958e277130) | Jan 12, 2021 |
| Acer          | V3-771                      | [816da2c056](https://linux-hardware.org/?probe=816da2c056) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1209b7ddaa](https://linux-hardware.org/?probe=1209b7ddaa) | Jan 10, 2021 |
| Dell          | XPS 13 7390                 | [ee990dcfb4](https://linux-hardware.org/?probe=ee990dcfb4) | Jan 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S4AF00    | [88d0c92974](https://linux-hardware.org/?probe=88d0c92974) | Jan 05, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [6226d61b8d](https://linux-hardware.org/?probe=6226d61b8d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | [0280683b9f](https://linux-hardware.org/?probe=0280683b9f) | Jan 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0f6cbbdc40](https://linux-hardware.org/?probe=0f6cbbdc40) | Jan 03, 2021 |
| Dell          | XPS 13 7390                 | [7fcac0b28e](https://linux-hardware.org/?probe=7fcac0b28e) | Jan 01, 2021 |
| HP            | ProBook 650 G2              | [4e4dfa1185](https://linux-hardware.org/?probe=4e4dfa1185) | Jan 01, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Sony          | SVE1511F4E                  | [2482a9cf42](https://linux-hardware.org/?probe=2482a9cf42) | Dec 29, 2020 |
| Sony          | SVE1511F4E                  | [9ddcb0cab8](https://linux-hardware.org/?probe=9ddcb0cab8) | Dec 29, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 135       | 12.65%  |
| Ubuntu 18.04                 | 90        | 8.43%   |
| Ubuntu 22.04                 | 52        | 4.87%   |
| Debian 11                    | 36        | 3.37%   |
| Linux Mint 20.3              | 32        | 3%      |
| Debian 10                    | 24        | 2.25%   |
| OpenMandriva 4.3             | 22        | 2.06%   |
| Zorin 16                     | 21        | 1.97%   |
| Linux Mint 20.2              | 20        | 1.87%   |
| Linux Mint 20.1              | 20        | 1.87%   |
| Ubuntu 21.10                 | 17        | 1.59%   |
| KDE neon 20.04               | 17        | 1.59%   |
| OpenMandriva 4.2             | 16        | 1.5%    |
| Arch Rolling                 | 16        | 1.5%    |
| Pop!_OS 22.04                | 15        | 1.41%   |
| Linux Mint 21.1              | 15        | 1.41%   |
| Ubuntu 20.10                 | 14        | 1.31%   |
| Manjaro                      | 14        | 1.31%   |
| Fedora 37                    | 14        | 1.31%   |
| Ubuntu 19.10                 | 13        | 1.22%   |
| Fedora 34                    | 13        | 1.22%   |
| Ubuntu 22.10                 | 12        | 1.12%   |
| Pop!_OS 21.04                | 12        | 1.12%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.12%   |
| ArcoLinux Rolling            | 12        | 1.12%   |
| Arch                         | 12        | 1.12%   |
| Pop!_OS 20.10                | 11        | 1.03%   |
| Linux Mint 19.3              | 11        | 1.03%   |
| Fedora 32                    | 11        | 1.03%   |
| Pop!_OS 20.04                | 10        | 0.94%   |
| Kubuntu 20.04                | 10        | 0.94%   |
| Fedora 35                    | 10        | 0.94%   |
| Linux Mint 21                | 9         | 0.84%   |
| Fedora 33                    | 9         | 0.84%   |
| Zorin 15                     | 8         | 0.75%   |
| Fedora 36                    | 8         | 0.75%   |
| Ubuntu MATE 20.04            | 7         | 0.66%   |
| OpenMandriva 23.03           | 7         | 0.66%   |
| OpenMandriva 23.01           | 7         | 0.66%   |
| LMDE 4                       | 7         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 329       | 33.2%   |
| Linux Mint    | 105       | 10.6%   |
| Fedora        | 74        | 7.47%   |
| Debian        | 69        | 6.96%   |
| OpenMandriva  | 62        | 6.26%   |
| Pop!_OS       | 49        | 4.94%   |
| Manjaro       | 33        | 3.33%   |
| Zorin         | 29        | 2.93%   |
| Arch          | 27        | 2.72%   |
| Kubuntu       | 23        | 2.32%   |
| KDE neon      | 19        | 1.92%   |
| openSUSE      | 16        | 1.61%   |
| ROSA          | 15        | 1.51%   |
| ArcoLinux     | 15        | 1.51%   |
| Kali          | 11        | 1.11%   |
| Xubuntu       | 10        | 1.01%   |
| Ubuntu MATE   | 10        | 1.01%   |
| Lubuntu       | 8         | 0.81%   |
| LMDE          | 7         | 0.71%   |
| Gentoo        | 7         | 0.71%   |
| Endless       | 6         | 0.61%   |
| Elementary    | 6         | 0.61%   |
| BlackPanther  | 5         | 0.5%    |
| Ubuntu Budgie | 4         | 0.4%    |
| SteamOS       | 4         | 0.4%    |
| Feren OS      | 4         | 0.4%    |
| Clear Linux   | 4         | 0.4%    |
| Void Linux    | 3         | 0.3%    |
| Ubuntu Unity  | 3         | 0.3%    |
| RHEL          | 3         | 0.3%    |
| Parrot        | 3         | 0.3%    |
| MX            | 3         | 0.3%    |
| Garuda Linux  | 3         | 0.3%    |
| TUXEDO OS     | 2         | 0.2%    |
| NixOS         | 2         | 0.2%    |
| EndeavourOS   | 2         | 0.2%    |
| CentOS        | 2         | 0.2%    |
| Artix         | 2         | 0.2%    |
| Ubuntu Studio | 1         | 0.1%    |
| Solus         | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 20        | 1.69%   |
| 5.15.0-56-generic        | 18        | 1.52%   |
| 5.10.14-desktop-1omv4002 | 16        | 1.35%   |
| 5.4.0-42-generic         | 14        | 1.18%   |
| 5.4.0-52-generic         | 12        | 1.01%   |
| 5.19.0-35-generic        | 11        | 0.93%   |
| 5.4.0-58-generic         | 10        | 0.84%   |
| 5.4.0-47-generic         | 10        | 0.84%   |
| 5.15.0-58-generic        | 10        | 0.84%   |
| 5.10.0-21-amd64          | 10        | 0.84%   |
| 5.15.0-52-generic        | 9         | 0.76%   |
| 5.8.0-55-generic         | 8         | 0.67%   |
| 5.4.0-91-generic         | 8         | 0.67%   |
| 5.4.0-80-generic         | 8         | 0.67%   |
| 5.3.0-28-generic         | 8         | 0.67%   |
| 5.15.0-60-generic        | 8         | 0.67%   |
| 6.2.6-desktop-1omv2390   | 7         | 0.59%   |
| 6.1.1-desktop-1omv2290   | 7         | 0.59%   |
| 5.8.0-59-generic         | 7         | 0.59%   |
| 5.4.0-72-generic         | 7         | 0.59%   |
| 5.4.0-65-generic         | 7         | 0.59%   |
| 5.4.0-62-generic         | 7         | 0.59%   |
| 5.4.0-48-generic         | 7         | 0.59%   |
| 5.15.0-48-generic        | 7         | 0.59%   |
| 5.13.0-30-generic        | 7         | 0.59%   |
| 5.11.0-43-generic        | 7         | 0.59%   |
| 5.10.0-8-amd64           | 7         | 0.59%   |
| 5.0.0-37-generic         | 7         | 0.59%   |
| 5.4.0-81-generic         | 6         | 0.51%   |
| 5.4.0-51-generic         | 6         | 0.51%   |
| 5.4.0-37-generic         | 6         | 0.51%   |
| 5.3.0-51-generic         | 6         | 0.51%   |
| 5.3.0-40-generic         | 6         | 0.51%   |
| 5.13.0-39-generic        | 6         | 0.51%   |
| 5.13.0-35-generic        | 6         | 0.51%   |
| 5.11.0-7620-generic      | 6         | 0.51%   |
| 5.11.0-40-generic        | 6         | 0.51%   |
| 5.11.0-38-generic        | 6         | 0.51%   |
| 4.15.0-96-generic        | 6         | 0.51%   |
| 5.8.0-53-generic         | 5         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 182       | 16.53%  |
| 5.15.0  | 97        | 8.81%   |
| 5.8.0   | 60        | 5.45%   |
| 4.15.0  | 57        | 5.18%   |
| 5.11.0  | 55        | 5%      |
| 5.13.0  | 54        | 4.9%    |
| 5.10.0  | 43        | 3.91%   |
| 5.3.0   | 40        | 3.63%   |
| 5.19.0  | 40        | 3.63%   |
| 4.19.0  | 27        | 2.45%   |
| 5.0.0   | 26        | 2.36%   |
| 5.16.7  | 20        | 1.82%   |
| 4.18.0  | 18        | 1.63%   |
| 5.10.14 | 17        | 1.54%   |
| 5.14.0  | 11        | 1%      |
| 6.2.0   | 10        | 0.91%   |
| 6.1.1   | 9         | 0.82%   |
| 6.2.6   | 8         | 0.73%   |
| 6.0.0   | 8         | 0.73%   |
| 5.6.0   | 7         | 0.64%   |
| 5.17.5  | 7         | 0.64%   |
| 6.0.15  | 5         | 0.45%   |
| 6.0.12  | 5         | 0.45%   |
| 5.6.14  | 5         | 0.45%   |
| 6.1.0   | 4         | 0.36%   |
| 6.0.8   | 4         | 0.36%   |
| 6.0.7   | 4         | 0.36%   |
| 5.9.16  | 4         | 0.36%   |
| 5.5.8   | 4         | 0.36%   |
| 5.18.0  | 4         | 0.36%   |
| 4.18.16 | 4         | 0.36%   |
| 6.3.5   | 3         | 0.27%   |
| 6.2.2   | 3         | 0.27%   |
| 6.0.10  | 3         | 0.27%   |
| 5.9.8   | 3         | 0.27%   |
| 5.9.11  | 3         | 0.27%   |
| 5.7.0   | 3         | 0.27%   |
| 5.6.4   | 3         | 0.27%   |
| 5.3.18  | 3         | 0.27%   |
| 5.17.6  | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 190       | 17.45%  |
| 5.15    | 120       | 11.02%  |
| 5.10    | 73        | 6.7%    |
| 5.8     | 71        | 6.52%   |
| 5.11    | 71        | 6.52%   |
| 5.13    | 65        | 5.97%   |
| 4.15    | 57        | 5.23%   |
| 5.19    | 47        | 4.32%   |
| 5.3     | 46        | 4.22%   |
| 5.16    | 35        | 3.21%   |
| 4.19    | 32        | 2.94%   |
| 6.0     | 31        | 2.85%   |
| 6.2     | 28        | 2.57%   |
| 5.0     | 28        | 2.57%   |
| 4.18    | 24        | 2.2%    |
| 5.17    | 23        | 2.11%   |
| 6.1     | 22        | 2.02%   |
| 5.6     | 18        | 1.65%   |
| 5.9     | 17        | 1.56%   |
| 5.14    | 17        | 1.56%   |
| 5.18    | 14        | 1.29%   |
| 5.12    | 12        | 1.1%    |
| 5.7     | 11        | 1.01%   |
| 4.9     | 11        | 1.01%   |
| 6.3     | 10        | 0.92%   |
| 5.5     | 6         | 0.55%   |
| 5.2     | 2         | 0.18%   |
| 4.4     | 2         | 0.18%   |
| 4.14    | 2         | 0.18%   |
| 4.1     | 2         | 0.18%   |
| 4.20    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 936       | 97.91%  |
| i686   | 20        | 2.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 441       | 43.75%  |
| KDE5            | 165       | 16.37%  |
| Unknown         | 119       | 11.81%  |
| X-Cinnamon      | 89        | 8.83%   |
| XFCE            | 58        | 5.75%   |
| MATE            | 29        | 2.88%   |
| KDE             | 16        | 1.59%   |
| Cinnamon        | 16        | 1.59%   |
| LXDE            | 14        | 1.39%   |
| LXQt            | 11        | 1.09%   |
| i3              | 9         | 0.89%   |
| KDE4            | 8         | 0.79%   |
| GNOME Flashback | 8         | 0.79%   |
| Pantheon        | 6         | 0.6%    |
| Budgie          | 6         | 0.6%    |
| bspwm           | 4         | 0.4%    |
| Unity           | 2         | 0.2%    |
| qtile           | 2         | 0.2%    |
| sway            | 1         | 0.1%    |
| openbox         | 1         | 0.1%    |
| herbstluftwm    | 1         | 0.1%    |
| GNUstep         | 1         | 0.1%    |
| GNOME Classic   | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 716       | 71.74%  |
| Wayland | 186       | 18.64%  |
| Unknown | 77        | 7.72%   |
| Tty     | 19        | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 446       | 44.56%  |
| GDM     | 138       | 13.79%  |
| SDDM    | 137       | 13.69%  |
| LightDM | 117       | 11.69%  |
| GDM3    | 110       | 10.99%  |
| TDM     | 40        | 4%      |
| KDM     | 8         | 0.8%    |
| XDM     | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |
| GREETD  | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 345       | 34.88%  |
| de_CH   | 244       | 24.67%  |
| Unknown | 123       | 12.44%  |
| fr_CH   | 72        | 7.28%   |
| de_DE   | 55        | 5.56%   |
| en_GB   | 51        | 5.16%   |
| fr_FR   | 21        | 2.12%   |
| C       | 20        | 2.02%   |
| pt_PT   | 10        | 1.01%   |
| it_IT   | 9         | 0.91%   |
| it_CH   | 7         | 0.71%   |
| pl_PL   | 5         | 0.51%   |
| es_ES   | 4         | 0.4%    |
| de_AT   | 4         | 0.4%    |
| en_CH   | 3         | 0.3%    |
| ru_RU   | 2         | 0.2%    |
| en_IE   | 2         | 0.2%    |
| en_CA   | 2         | 0.2%    |
| en_AU   | 2         | 0.2%    |
| tr_TR   | 1         | 0.1%    |
| ru_UA   | 1         | 0.1%    |
| POSIX   | 1         | 0.1%    |
| nl_BE   | 1         | 0.1%    |
| hsb_DE  | 1         | 0.1%    |
| de_LI   | 1         | 0.1%    |
| de_IT   | 1         | 0.1%    |
| ca_ES   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 569       | 58.48%  |
| BIOS | 404       | 41.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 751       | 76.24%  |
| Btrfs   | 93        | 9.44%   |
| Overlay | 69        | 7.01%   |
| Unknown | 37        | 3.76%   |
| Xfs     | 11        | 1.12%   |
| Zfs     | 8         | 0.81%   |
| Tmpfs   | 8         | 0.81%   |
| Ext2    | 4         | 0.41%   |
| Ext3    | 3         | 0.3%    |
| F2fs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 462       | 47.05%  |
| GPT     | 426       | 43.38%  |
| MBR     | 94        | 9.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 867       | 89.11%  |
| Yes       | 106       | 10.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 744       | 76.7%   |
| Yes       | 226       | 23.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 263       | 27.54%  |
| Hewlett-Packard     | 215       | 22.51%  |
| Dell                | 108       | 11.31%  |
| Acer                | 96        | 10.05%  |
| ASUSTek Computer    | 78        | 8.17%   |
| Apple               | 39        | 4.08%   |
| Toshiba             | 16        | 1.68%   |
| Sony                | 13        | 1.36%   |
| TUXEDO              | 12        | 1.26%   |
| Notebook            | 12        | 1.26%   |
| Medion              | 11        | 1.15%   |
| HUAWEI              | 9         | 0.94%   |
| Samsung Electronics | 8         | 0.84%   |
| Fujitsu             | 7         | 0.73%   |
| Razer               | 6         | 0.63%   |
| MSI                 | 6         | 0.63%   |
| Valve               | 4         | 0.42%   |
| Schenker            | 4         | 0.42%   |
| Alienware           | 4         | 0.42%   |
| Timi                | 3         | 0.31%   |
| Packard Bell        | 3         | 0.31%   |
| GPD                 | 3         | 0.31%   |
| Clevo               | 3         | 0.31%   |
| whyopencomputing    | 2         | 0.21%   |
| TrekStor            | 2         | 0.21%   |
| System76            | 2         | 0.21%   |
| Purism              | 2         | 0.21%   |
| PC Specialist       | 2         | 0.21%   |
| MPMAN               | 2         | 0.21%   |
| Google              | 2         | 0.21%   |
| Fujitsu Siemens     | 2         | 0.21%   |
| Star Labs           | 1         | 0.1%    |
| SLIMBOOK            | 1         | 0.1%    |
| Shuttle             | 1         | 0.1%    |
| Quanta              | 1         | 0.1%    |
| Quanmax             | 1         | 0.1%    |
| Polaroid            | 1         | 0.1%    |
| Panasonic           | 1         | 0.1%    |
| OriginPC            | 1         | 0.1%    |
| LG Electronics      | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion dv7                            | 8         | 0.84%   |
| Dell Latitude 7490                         | 7         | 0.73%   |
| Unknown                                    | 7         | 0.73%   |
| HP Pavilion dv6                            | 5         | 0.52%   |
| HP Notebook                                | 5         | 0.52%   |
| HP ENVY 15                                 | 5         | 0.52%   |
| Dell XPS 15 9570                           | 5         | 0.52%   |
| Dell Latitude E7240                        | 5         | 0.52%   |
| Apple MacBookPro9,2                        | 5         | 0.52%   |
| Apple MacBookPro8,1                        | 5         | 0.52%   |
| Valve Jupiter                              | 4         | 0.42%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.42%   |
| HP ProBook 440 G8 Notebook PC              | 4         | 0.42%   |
| HP Pavilion g7                             | 4         | 0.42%   |
| HP Laptop 15-bs1xx                         | 4         | 0.42%   |
| HP EliteBook Folio 1040 G1                 | 4         | 0.42%   |
| HP EliteBook 840 G5                        | 4         | 0.42%   |
| Dell XPS 15 9560                           | 4         | 0.42%   |
| Dell XPS 15 7590                           | 4         | 0.42%   |
| Dell XPS 13 9370                           | 4         | 0.42%   |
| TUXEDO Pulse 15 Gen1                       | 3         | 0.31%   |
| Razer Blade                                | 3         | 0.31%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 3         | 0.31%   |
| Lenovo ThinkPad T530 24296HG               | 3         | 0.31%   |
| HUAWEI MACH-WX9                            | 3         | 0.31%   |
| HP ProBook 440 G6                          | 3         | 0.31%   |
| HP Pavilion g6                             | 3         | 0.31%   |
| HP Pavilion dv6700                         | 3         | 0.31%   |
| HP Pavilion 15                             | 3         | 0.31%   |
| HP Laptop 15-bs0xx                         | 3         | 0.31%   |
| HP ENVY dv7                                | 3         | 0.31%   |
| HP EliteBook 850 G8 Notebook PC            | 3         | 0.31%   |
| HP EliteBook 840 G6                        | 3         | 0.31%   |
| Dell XPS 13 9360                           | 3         | 0.31%   |
| Dell XPS 13 7390                           | 3         | 0.31%   |
| Dell Latitude E7470                        | 3         | 0.31%   |
| Apple MacBookPro6,2                        | 3         | 0.31%   |
| Apple MacBookPro11,1                       | 3         | 0.31%   |
| Apple MacBookPro10,1                       | 3         | 0.31%   |
| Acer Aspire V3-772G                        | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 198       | 20.73%  |
| Acer Aspire           | 62        | 6.49%   |
| HP EliteBook          | 58        | 6.07%   |
| Dell Latitude         | 47        | 4.92%   |
| HP Pavilion           | 42        | 4.4%    |
| Dell XPS              | 40        | 4.19%   |
| HP ProBook            | 34        | 3.56%   |
| Lenovo IdeaPad        | 20        | 2.09%   |
| HP Laptop             | 18        | 1.88%   |
| HP ENVY               | 17        | 1.78%   |
| Lenovo Yoga           | 15        | 1.57%   |
| HP ZBook              | 14        | 1.47%   |
| Acer Swift            | 14        | 1.47%   |
| Dell Inspiron         | 12        | 1.26%   |
| ASUS VivoBook         | 12        | 1.26%   |
| Toshiba Satellite     | 11        | 1.15%   |
| ASUS ZenBook          | 10        | 1.05%   |
| HP Compaq             | 8         | 0.84%   |
| Unknown               | 7         | 0.73%   |
| Razer Blade           | 6         | 0.63%   |
| Dell Precision        | 6         | 0.63%   |
| ASUS ROG              | 6         | 0.63%   |
| HP Notebook           | 5         | 0.52%   |
| Fujitsu LIFEBOOK      | 5         | 0.52%   |
| Apple MacBookPro9     | 5         | 0.52%   |
| Apple MacBookPro8     | 5         | 0.52%   |
| Apple MacBookPro11    | 5         | 0.52%   |
| Acer Predator         | 5         | 0.52%   |
| Valve Jupiter         | 4         | 0.42%   |
| Lenovo ThinkBook      | 4         | 0.42%   |
| HP OMEN               | 4         | 0.42%   |
| HP 250                | 4         | 0.42%   |
| Acer TravelMate       | 4         | 0.42%   |
| Acer Nitro            | 4         | 0.42%   |
| TUXEDO Pulse          | 3         | 0.31%   |
| Packard Bell EasyNote | 3         | 0.31%   |
| Lenovo Legion         | 3         | 0.31%   |
| HUAWEI MACH-WX9       | 3         | 0.31%   |
| ASUS ASUS             | 3         | 0.31%   |
| Apple MacBookPro6     | 3         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 98        | 10.26%  |
| 2020 | 94        | 9.84%   |
| 2019 | 90        | 9.42%   |
| 2012 | 79        | 8.27%   |
| 2017 | 70        | 7.33%   |
| 2011 | 67        | 7.02%   |
| 2013 | 61        | 6.39%   |
| 2021 | 59        | 6.18%   |
| 2015 | 55        | 5.76%   |
| 2014 | 55        | 5.76%   |
| 2016 | 52        | 5.45%   |
| 2010 | 49        | 5.13%   |
| 2022 | 38        | 3.98%   |
| 2008 | 29        | 3.04%   |
| 2007 | 21        | 2.2%    |
| 2009 | 20        | 2.09%   |
| 2023 | 8         | 0.84%   |
| 2005 | 5         | 0.52%   |
| 2006 | 4         | 0.42%   |
| 2004 | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 955       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 841       | 87.06%  |
| Enabled  | 125       | 12.94%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 947       | 99.16%  |
| Yes  | 8         | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 246       | 25.18%  |
| 4.01-8.0    | 220       | 22.52%  |
| 8.01-16.0   | 172       | 17.6%   |
| 3.01-4.0    | 145       | 14.84%  |
| 32.01-64.0  | 113       | 11.57%  |
| 1.01-2.0    | 26        | 2.66%   |
| 24.01-32.0  | 21        | 2.15%   |
| 64.01-256.0 | 15        | 1.54%   |
| 2.01-3.0    | 11        | 1.13%   |
| 0.51-1.0    | 8         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 353       | 32.99%  |
| 2.01-3.0   | 270       | 25.23%  |
| 4.01-8.0   | 184       | 17.2%   |
| 3.01-4.0   | 129       | 12.06%  |
| 0.51-1.0   | 60        | 5.61%   |
| 8.01-16.0  | 56        | 5.23%   |
| 16.01-24.0 | 10        | 0.93%   |
| 0.01-0.5   | 5         | 0.47%   |
| 24.01-32.0 | 3         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 747       | 76.38%  |
| 2      | 187       | 19.12%  |
| 3      | 30        | 3.07%   |
| 0      | 8         | 0.82%   |
| 5      | 3         | 0.31%   |
| 4      | 3         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 649       | 67.75%  |
| Yes       | 309       | 32.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 778       | 80.79%  |
| No        | 185       | 19.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 940       | 98.43%  |
| No        | 15        | 1.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 770       | 79.3%   |
| No        | 201       | 20.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 955       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Zurich        | 237       | 22.79%  |
| Bern          | 52        | 5%      |
| Geneva        | 45        | 4.33%   |
| Lucerne       | 24        | 2.31%   |
| Winterthur    | 23        | 2.21%   |
| Lausanne      | 19        | 1.83%   |
| Basel         | 19        | 1.83%   |
| Neuchatel     | 16        | 1.54%   |
| Lugano        | 13        | 1.25%   |
| St. Gallen    | 9         | 0.87%   |
| Herrliberg    | 9         | 0.87%   |
| Thun          | 8         | 0.77%   |
| Wil           | 7         | 0.67%   |
| Widnau        | 7         | 0.67%   |
| Wettingen     | 6         | 0.58%   |
| Sion          | 6         | 0.58%   |
| Munchenstein  | 6         | 0.58%   |
| Lyss          | 6         | 0.58%   |
| Gerlafingen   | 6         | 0.58%   |
| Dietikon      | 6         | 0.58%   |
| Biel/Bienne   | 6         | 0.58%   |
| Aarau         | 6         | 0.58%   |
| Wohlen        | 5         | 0.48%   |
| Willisau      | 5         | 0.48%   |
| St. Moritz    | 5         | 0.48%   |
| Solothurn     | 5         | 0.48%   |
| Onex          | 5         | 0.48%   |
| Grancy        | 5         | 0.48%   |
| Grabs         | 5         | 0.48%   |
| Effretikon    | 5         | 0.48%   |
| Dubendorf     | 5         | 0.48%   |
| Chur          | 5         | 0.48%   |
| Bussigny      | 5         | 0.48%   |
| Baar          | 5         | 0.48%   |
| Zweidlen-Dorf | 4         | 0.38%   |
| Vernier       | 4         | 0.38%   |
| Suhr          | 4         | 0.38%   |
| Schwarzenbach | 4         | 0.38%   |
| Oftringen     | 4         | 0.38%   |
| Munsingen     | 4         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 318       | 453    | 27.04%  |
| WDC                            | 115       | 151    | 9.78%   |
| Seagate                        | 103       | 124    | 8.76%   |
| Toshiba                        | 84        | 112    | 7.14%   |
| SanDisk                        | 75        | 92     | 6.38%   |
| Intel                          | 65        | 81     | 5.53%   |
| SK hynix                       | 61        | 74     | 5.19%   |
| Unknown                        | 52        | 72     | 4.42%   |
| Hitachi                        | 35        | 45     | 2.98%   |
| Crucial                        | 32        | 48     | 2.72%   |
| Micron Technology              | 27        | 33     | 2.3%    |
| Kingston                       | 27        | 41     | 2.3%    |
| Apple                          | 23        | 27     | 1.96%   |
| HGST                           | 20        | 25     | 1.7%    |
| LITEON                         | 15        | 20     | 1.28%   |
| LITEONIT                       | 10        | 11     | 0.85%   |
| Intenso                        | 9         | 10     | 0.77%   |
| OCZ                            | 8         | 8      | 0.68%   |
| Phison Electronics             | 7         | 15     | 0.6%    |
| A-DATA Technology              | 7         | 12     | 0.6%    |
| Transcend                      | 6         | 9      | 0.51%   |
| KIOXIA                         | 6         | 7      | 0.51%   |
| Fujitsu                        | 6         | 9      | 0.51%   |
| ASMT                           | 5         | 6      | 0.43%   |
| Phison                         | 4         | 6      | 0.34%   |
| Corsair                        | 4         | 5      | 0.34%   |
| Silicon Motion                 | 3         | 4      | 0.26%   |
| Lenovo                         | 3         | 3      | 0.26%   |
| JMicron Technology             | 3         | 3      | 0.26%   |
| China                          | 3         | 3      | 0.26%   |
| Unknown                        | 3         | 3      | 0.26%   |
| SPCC                           | 2         | 2      | 0.17%   |
| Solid State Storage Technology | 2         | 3      | 0.17%   |
| Lite-On                        | 2         | 2      | 0.17%   |
| LaCie                          | 2         | 2      | 0.17%   |
| KingSpec                       | 2         | 2      | 0.17%   |
| External                       | 2         | 2      | 0.17%   |
| USB3.0                         | 1         | 2      | 0.09%   |
| Unknown (CF)                   | 1         | 1      | 0.09%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                            | 13        | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 12        | 0.97%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.89%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.89%   |
| Samsung SSD 860 EVO 1TB                             | 10        | 0.81%   |
| Unknown MMC Card  32GB                              | 9         | 0.73%   |
| Unknown MMC Card  128GB                             | 9         | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9         | 0.73%   |
| Samsung SSD 860 EVO 250GB                           | 9         | 0.73%   |
| Samsung NVMe SSD Drive 256GB                        | 9         | 0.73%   |
| Samsung NVMe SSD Drive 1024GB                       | 9         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 9         | 0.73%   |
| Seagate ST1000LM048-2E7172 1TB                      | 8         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                        | 8         | 0.65%   |
| Samsung SSD 860 EVO 500GB                           | 8         | 0.65%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.57%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                        | 7         | 0.57%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 0.57%   |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.57%   |
| Intel NVMe SSD Drive 512GB                          | 7         | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 7         | 0.57%   |
| Unknown MMC Card  64GB                              | 6         | 0.49%   |
| Seagate ST2000LM015-2E8174 2TB                      | 6         | 0.49%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.49%   |
| Samsung SSD 970 EVO 1TB                             | 6         | 0.49%   |
| Samsung NVMe SSD Drive 2TB                          | 6         | 0.49%   |
| Hitachi HTS547575A9E384 752GB                       | 6         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB                        | 5         | 0.4%    |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.4%    |
| Seagate Expansion 1TB                               | 5         | 0.4%    |
| Samsung SSD 870 EVO 500GB                           | 5         | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 5         | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 5         | 0.4%    |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 5         | 0.4%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 5         | 0.4%    |
| Intel NVMe SSD Drive 1024GB                         | 5         | 0.4%    |
| WDC WDS120G2G0A-00JH30 128GB SSD                    | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 121    | 37.04%  |
| WDC                 | 55        | 77     | 20.37%  |
| Toshiba             | 40        | 45     | 14.81%  |
| Hitachi             | 35        | 45     | 12.96%  |
| HGST                | 20        | 25     | 7.41%   |
| Fujitsu             | 6         | 9      | 2.22%   |
| Unknown             | 3         | 3      | 1.11%   |
| Samsung Electronics | 3         | 3      | 1.11%   |
| USB3.0              | 1         | 2      | 0.37%   |
| Unknown (CF)        | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| HGST HTS            | 1         | 1      | 0.37%   |
| External            | 1         | 1      | 0.37%   |
| ASMT                | 1         | 1      | 0.37%   |
| ASMedia             | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 153       | 195    | 35.17%  |
| SanDisk             | 45        | 54     | 10.34%  |
| Intel               | 29        | 33     | 6.67%   |
| Crucial             | 29        | 45     | 6.67%   |
| WDC                 | 23        | 28     | 5.29%   |
| Kingston            | 18        | 32     | 4.14%   |
| Apple               | 18        | 20     | 4.14%   |
| Toshiba             | 16        | 25     | 3.68%   |
| LITEON              | 15        | 20     | 3.45%   |
| SK hynix            | 14        | 16     | 3.22%   |
| Micron Technology   | 14        | 19     | 3.22%   |
| LITEONIT            | 10        | 11     | 2.3%    |
| OCZ                 | 8         | 8      | 1.84%   |
| Intenso             | 7         | 8      | 1.61%   |
| Transcend           | 6         | 9      | 1.38%   |
| A-DATA Technology   | 5         | 8      | 1.15%   |
| Corsair             | 4         | 5      | 0.92%   |
| China               | 3         | 3      | 0.69%   |
| ASMT                | 3         | 4      | 0.69%   |
| KingSpec            | 2         | 2      | 0.46%   |
| SPCC                | 1         | 1      | 0.23%   |
| Seagate             | 1         | 1      | 0.23%   |
| PNY                 | 1         | 1      | 0.23%   |
| Plextor             | 1         | 1      | 0.23%   |
| Phison              | 1         | 3      | 0.23%   |
| ORICO               | 1         | 1      | 0.23%   |
| Mushkin             | 1         | 1      | 0.23%   |
| Kolink              | 1         | 1      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| GOODRAM             | 1         | 3      | 0.23%   |
| External            | 1         | 1      | 0.23%   |
| Dogfish             | 1         | 1      | 0.23%   |
| BIWIN               | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 400       | 562    | 35.71%  |
| NVMe    | 394       | 567    | 35.18%  |
| HDD     | 262       | 337    | 23.39%  |
| MMC     | 56        | 77     | 5%      |
| Unknown | 8         | 9      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 577       | 862    | 54.13%  |
| NVMe | 391       | 563    | 36.68%  |
| MMC  | 56        | 77     | 5.25%   |
| SAS  | 42        | 50     | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 429       | 598    | 65%     |
| 0.51-1.0   | 208       | 273    | 31.52%  |
| 1.01-2.0   | 17        | 22     | 2.58%   |
| 3.01-4.0   | 3         | 3      | 0.45%   |
| 4.01-10.0  | 3         | 3      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 259       | 25.42%  |
| 251-500        | 251       | 24.63%  |
| 501-1000       | 181       | 17.76%  |
| 1-20           | 81        | 7.95%   |
| 1001-2000      | 78        | 7.65%   |
| 51-100         | 56        | 5.5%    |
| Unknown        | 46        | 4.51%   |
| 21-50          | 36        | 3.53%   |
| More than 3000 | 16        | 1.57%   |
| 2001-3000      | 15        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 419       | 39.6%   |
| 21-50     | 161       | 15.22%  |
| 101-250   | 152       | 14.37%  |
| 51-100    | 114       | 10.78%  |
| 251-500   | 89        | 8.41%   |
| 501-1000  | 52        | 4.91%   |
| Unknown   | 46        | 4.35%   |
| 1001-2000 | 21        | 1.98%   |
| 2001-3000 | 4         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 4.26%   |
| Hitachi HTS545050B9A300 500GB                  | 2         | 2      | 4.26%   |
| WDC WD1600BEKT-60A25T1 160GB                   | 1         | 1      | 2.13%   |
| Toshiba MQ01ACF050 500GB                       | 1         | 1      | 2.13%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.13%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 2.13%   |
| Toshiba MK1255GSX H 120GB                      | 1         | 1      | 2.13%   |
| SK hynix SC401 SATA 512GB SSD                  | 1         | 2      | 2.13%   |
| SK hynix SC210 mSATA 256GB SSD                 | 1         | 1      | 2.13%   |
| SK hynix HFS256GD9TNG-62A0A 256GB              | 1         | 1      | 2.13%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 2.13%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 2.13%   |
| SK hynix HFS128G39MNC-2300A 128GB SSD          | 1         | 1      | 2.13%   |
| Seagate ST9500420AS 500GB                      | 1         | 2      | 2.13%   |
| Seagate ST9250827AS 250GB                      | 1         | 1      | 2.13%   |
| Seagate ST9160412AS 160GB                      | 1         | 1      | 2.13%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.13%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 2.13%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB            | 1         | 1      | 2.13%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD            | 1         | 1      | 2.13%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.13%   |
| SanDisk SD7SB3Q256G1002 256GB SSD              | 1         | 2      | 2.13%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 860 EVO M.2 1TB        | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 840 Series 120GB       | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 3      | 2.13%   |
| Samsung Electronics HM500JI 500GB              | 1         | 1      | 2.13%   |
| Micron Technology C300-MTFDDAC064MAG 64GB SSD  | 1         | 1      | 2.13%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.13%   |
| LITEONIT LAT-256M3S 256GB SSD                  | 1         | 1      | 2.13%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 2.13%   |
| Intenso SSD Sata III 256GB                     | 1         | 1      | 2.13%   |
| Intel SSDSCKKF256G8H 256GB                     | 1         | 1      | 2.13%   |
| Intel SSDSC2BF180A4L 180GB                     | 1         | 1      | 2.13%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 2.13%   |
| Intel SSDPEKKW256G7 256GB                      | 1         | 1      | 2.13%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 19.15%  |
| Toshiba             | 6         | 6      | 12.77%  |
| SK hynix            | 6         | 7      | 12.77%  |
| Samsung Electronics | 5         | 7      | 10.64%  |
| Intel               | 4         | 4      | 8.51%   |
| Hitachi             | 4         | 4      | 8.51%   |
| SanDisk             | 3         | 4      | 6.38%   |
| Micron Technology   | 2         | 2      | 4.26%   |
| HGST                | 2         | 2      | 4.26%   |
| WDC                 | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| Kingston            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Crucial             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 37.5%   |
| Toshiba             | 6         | 6      | 25%     |
| Hitachi             | 4         | 4      | 16.67%  |
| HGST                | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 25     | 51.06%  |
| SSD  | 21        | 25     | 44.68%  |
| NVMe | 2         | 2      | 4.26%   |

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
| Detected | 545       | 883    | 53.17%  |
| Works    | 434       | 617    | 42.34%  |
| Malfunc  | 46        | 52     | 4.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 662       | 59.53%  |
| Samsung Electronics            | 177       | 15.92%  |
| SanDisk                        | 65        | 5.85%   |
| AMD                            | 59        | 5.31%   |
| SK hynix                       | 42        | 3.78%   |
| Toshiba America Info Systems   | 31        | 2.79%   |
| Micron Technology              | 14        | 1.26%   |
| Phison Electronics             | 12        | 1.08%   |
| Kingston Technology Company    | 10        | 0.9%    |
| Nvidia                         | 7         | 0.63%   |
| Marvell Technology Group       | 5         | 0.45%   |
| KIOXIA                         | 4         | 0.36%   |
| Solid State Storage Technology | 3         | 0.27%   |
| Silicon Motion                 | 3         | 0.27%   |
| Lite-On Technology             | 3         | 0.27%   |
| Lenovo                         | 3         | 0.27%   |
| Apple                          | 3         | 0.27%   |
| VIA Technologies               | 2         | 0.18%   |
| Union Memory (Shenzhen)        | 2         | 0.18%   |
| Micron/Crucial Technology      | 2         | 0.18%   |
| Realtek Semiconductor          | 1         | 0.09%   |
| Biwin Storage Technology       | 1         | 0.09%   |
| ADATA Technology               | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 94        | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 88        | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 83        | 6.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 56        | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 52        | 4.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 3.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 45        | 3.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 41        | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 30        | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 26        | 2.19%   |
| Samsung NVMe SSD Controller 980                                                | 25        | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 1.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 20        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 20        | 1.68%   |
| Intel SSD 660P Series                                                          | 17        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 17        | 1.43%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 16        | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 16        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 1.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 1.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 14        | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 14        | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 1.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 12        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 12        | 1.01%   |
| Micron NVMe Storage Controller                                                 | 11        | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 11        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.93%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 9         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 8         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.67%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 7         | 0.59%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 0.51%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 609       | 52.96%  |
| NVMe | 393       | 34.17%  |
| RAID | 95        | 8.26%   |
| IDE  | 53        | 4.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 842       | 88.17%  |
| AMD          | 111       | 11.62%  |
| CentaurHauls | 2         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 36        | 3.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 32        | 3.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 30        | 3.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 18        | 1.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 17        | 1.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 15        | 1.57%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 14        | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 14        | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 1.26%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 12        | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 12        | 1.26%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 11        | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 11        | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 11        | 1.15%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 11        | 1.15%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 10        | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 10        | 1.05%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 10        | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 10        | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 9         | 0.94%   |
| Intel 12th Gen Core i7-1260P               | 9         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 8         | 0.84%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 8         | 0.84%   |
| Intel Core i7-2630QM CPU @ 2.00GHz         | 8         | 0.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 8         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 8         | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 8         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 8         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 8         | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 8         | 0.84%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 7         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz          | 7         | 0.73%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 7         | 0.73%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 7         | 0.73%   |
| Intel Core i7 CPU M 620 @ 2.67GHz          | 7         | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 7         | 0.73%   |
| Intel 12th Gen Core i7-12700H              | 7         | 0.73%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 7         | 0.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 6         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 362       | 37.91%  |
| Intel Core i5           | 232       | 24.29%  |
| Other                   | 92        | 9.63%   |
| Intel Core 2 Duo        | 39        | 4.08%   |
| AMD Ryzen 7             | 33        | 3.46%   |
| Intel Celeron           | 27        | 2.83%   |
| Intel Core i3           | 22        | 2.3%    |
| Intel Pentium           | 21        | 2.2%    |
| AMD Ryzen 7 PRO         | 19        | 1.99%   |
| AMD Ryzen 5             | 16        | 1.68%   |
| Intel Atom              | 15        | 1.57%   |
| Intel Core 2            | 8         | 0.84%   |
| Intel Core i9           | 7         | 0.73%   |
| AMD Ryzen 9             | 6         | 0.63%   |
| AMD E                   | 6         | 0.63%   |
| Intel Pentium Dual-Core | 5         | 0.52%   |
| AMD A8                  | 4         | 0.42%   |
| Intel Xeon              | 3         | 0.31%   |
| Intel Pentium M         | 3         | 0.31%   |
| Intel Core M            | 3         | 0.31%   |
| AMD E1                  | 3         | 0.31%   |
| Intel Pentium Silver    | 2         | 0.21%   |
| Intel Celeron Dual-Core | 2         | 0.21%   |
| AMD Turion 64 X2 Mobile | 2         | 0.21%   |
| AMD Ryzen 3             | 2         | 0.21%   |
| AMD Phenom II           | 2         | 0.21%   |
| AMD E2                  | 2         | 0.21%   |
| AMD C-50                | 2         | 0.21%   |
| AMD A4                  | 2         | 0.21%   |
| Intel Pentium Gold      | 1         | 0.1%    |
| Intel Pentium Dual      | 1         | 0.1%    |
| Intel Pentium 4         | 1         | 0.1%    |
| Intel Genuine           | 1         | 0.1%    |
| Intel Core m3           | 1         | 0.1%    |
| CentaurHauls VIA Eden   | 1         | 0.1%    |
| CentaurHauls VIA C7     | 1         | 0.1%    |
| AMD Turion 64 Mobile    | 1         | 0.1%    |
| AMD Ryzen 5 PRO         | 1         | 0.1%    |
| AMD FX                  | 1         | 0.1%    |
| AMD C-60                | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 420       | 43.93%  |
| 4       | 358       | 37.45%  |
| 8       | 76        | 7.95%   |
| 6       | 60        | 6.28%   |
| 1       | 13        | 1.36%   |
| 14      | 9         | 0.94%   |
| 12      | 9         | 0.94%   |
| 10      | 8         | 0.84%   |
| 24      | 1         | 0.1%    |
| 16      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 955       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 791       | 82.65%  |
| 1       | 165       | 17.24%  |
| Unknown | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 936       | 97.6%   |
| Unknown        | 17        | 1.77%   |
| 32-bit         | 6         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 228       | 23.12%  |
| 0x306a9    | 70        | 7.1%    |
| 0x806ea    | 56        | 5.68%   |
| 0x206a7    | 56        | 5.68%   |
| 0x40651    | 50        | 5.07%   |
| 0x806c1    | 42        | 4.26%   |
| 0x806ec    | 41        | 4.16%   |
| 0x806e9    | 32        | 3.25%   |
| 0x906ea    | 29        | 2.94%   |
| 0x306d4    | 29        | 2.94%   |
| 0x1067a    | 25        | 2.54%   |
| 0x306c3    | 24        | 2.43%   |
| 0x20655    | 20        | 2.03%   |
| 0x406e3    | 19        | 1.93%   |
| 0x30678    | 15        | 1.52%   |
| 0x806eb    | 14        | 1.42%   |
| 0xa0652    | 13        | 1.32%   |
| 0x506e3    | 13        | 1.32%   |
| 0x0a50000c | 12        | 1.22%   |
| 0x20652    | 11        | 1.12%   |
| 0x906a3    | 10        | 1.01%   |
| 0x10676    | 10        | 1.01%   |
| 0x906e9    | 9         | 0.91%   |
| 0x706e5    | 9         | 0.91%   |
| 0x0a404102 | 9         | 0.91%   |
| 0x08600106 | 9         | 0.91%   |
| 0x08600103 | 9         | 0.91%   |
| 0x406c4    | 8         | 0.81%   |
| 0x6fd      | 7         | 0.71%   |
| 0x706a1    | 6         | 0.61%   |
| 0x6f6      | 6         | 0.61%   |
| 0x806d1    | 5         | 0.51%   |
| 0x08108102 | 5         | 0.51%   |
| 0x05000119 | 5         | 0.51%   |
| 0x906ed    | 4         | 0.41%   |
| 0x906a4    | 4         | 0.41%   |
| 0x08608103 | 4         | 0.41%   |
| 0x05000029 | 4         | 0.41%   |
| 0xa0660    | 3         | 0.3%    |
| 0x406c3    | 3         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 241       | 25.18%  |
| Haswell          | 90        | 9.4%    |
| IvyBridge        | 86        | 8.99%   |
| SandyBridge      | 69        | 7.21%   |
| Skylake          | 54        | 5.64%   |
| TigerLake        | 51        | 5.33%   |
| Unknown          | 41        | 4.28%   |
| Penryn           | 40        | 4.18%   |
| Broadwell        | 37        | 3.87%   |
| Westmere         | 34        | 3.55%   |
| Silvermont       | 31        | 3.24%   |
| Zen 2            | 28        | 2.93%   |
| CometLake        | 23        | 2.4%    |
| Alderlake Hybrid | 19        | 1.99%   |
| Core             | 18        | 1.88%   |
| Zen 3            | 17        | 1.78%   |
| IceLake          | 16        | 1.67%   |
| Bobcat           | 11        | 1.15%   |
| Zen+             | 9         | 0.94%   |
| Goldmont plus    | 8         | 0.84%   |
| K8 Hammer        | 4         | 0.42%   |
| Bonnell          | 4         | 0.42%   |
| P6               | 3         | 0.31%   |
| Nehalem          | 3         | 0.31%   |
| Jaguar           | 3         | 0.31%   |
| Excavator        | 3         | 0.31%   |
| Zen              | 2         | 0.21%   |
| Puma             | 2         | 0.21%   |
| Piledriver       | 2         | 0.21%   |
| K10 Llano        | 2         | 0.21%   |
| K10              | 2         | 0.21%   |
| Goldmont         | 2         | 0.21%   |
| Steamroller      | 1         | 0.1%    |
| NetBurst         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 759       | 62.06%  |
| Nvidia           | 289       | 23.63%  |
| AMD              | 173       | 14.15%  |
| VIA Technologies | 2         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 79        | 6.36%   |
| Intel UHD Graphics 620                                                                   | 66        | 5.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 4.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 55        | 4.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 52        | 4.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 49        | 3.94%   |
| Intel HD Graphics 620                                                                    | 37        | 2.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 2.82%   |
| Intel HD Graphics 5500                                                                   | 30        | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 2.41%   |
| AMD Renoir                                                                               | 28        | 2.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 1.45%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 17        | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.97%   |
| AMD Rembrandt [Radeon 680M]                                                              | 12        | 0.97%   |
| Intel HD Graphics 630                                                                    | 11        | 0.88%   |
| Intel HD Graphics 530                                                                    | 11        | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 8         | 0.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 0.64%   |
| AMD Lucienne                                                                             | 8         | 0.64%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.48%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 6         | 0.48%   |
| Nvidia GF108M [NVS 5400M]                                                                | 6         | 0.48%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 507       | 52.87%  |
| Intel + Nvidia | 219       | 22.84%  |
| 1 x AMD        | 120       | 12.51%  |
| 1 x Nvidia     | 55        | 5.74%   |
| Intel + AMD    | 33        | 3.44%   |
| AMD + Nvidia   | 14        | 1.46%   |
| 2 x AMD        | 5         | 0.52%   |
| 2 x Nvidia     | 2         | 0.21%   |
| 1 x VIA        | 2         | 0.21%   |
| Other          | 1         | 0.1%    |
| 2 x Intel      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 804       | 83.75%  |
| Proprietary | 131       | 13.65%  |
| Unknown     | 25        | 2.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 615       | 63.08%  |
| 1.01-2.0   | 113       | 11.59%  |
| 0.01-0.5   | 93        | 9.54%   |
| 3.01-4.0   | 71        | 7.28%   |
| 0.51-1.0   | 51        | 5.23%   |
| 7.01-8.0   | 16        | 1.64%   |
| 5.01-6.0   | 11        | 1.13%   |
| 2.01-3.0   | 4         | 0.41%   |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 224       | 20.36%  |
| LG Display              | 187       | 17%     |
| Chimei Innolux          | 116       | 10.55%  |
| BOE                     | 94        | 8.55%   |
| Samsung Electronics     | 93        | 8.45%   |
| Sharp                   | 49        | 4.45%   |
| Apple                   | 41        | 3.73%   |
| Lenovo                  | 39        | 3.55%   |
| Dell                    | 33        | 3%      |
| Hewlett-Packard         | 27        | 2.45%   |
| Chi Mei Optoelectronics | 23        | 2.09%   |
| Acer                    | 20        | 1.82%   |
| Philips                 | 16        | 1.45%   |
| CSO                     | 14        | 1.27%   |
| BenQ                    | 13        | 1.18%   |
| InfoVision              | 12        | 1.09%   |
| Goldstar                | 12        | 1.09%   |
| PANDA                   | 8         | 0.73%   |
| Sony                    | 6         | 0.55%   |
| Eizo                    | 6         | 0.55%   |
| AOC                     | 6         | 0.55%   |
| Ancor Communications    | 6         | 0.55%   |
| LG Philips              | 5         | 0.45%   |
| Vestel Elektronik       | 4         | 0.36%   |
| Valve                   | 4         | 0.36%   |
| Toshiba                 | 4         | 0.36%   |
| LGD                     | 4         | 0.36%   |
| JDI                     | 4         | 0.36%   |
| Iiyama                  | 4         | 0.36%   |
| Panasonic               | 3         | 0.27%   |
| HannStar                | 3         | 0.27%   |
| IBM                     | 2         | 0.18%   |
| Denver                  | 2         | 0.18%   |
| CPT                     | 2         | 0.18%   |
| ASUSTek Computer        | 2         | 0.18%   |
| ViewSonic               | 1         | 0.09%   |
| Unknown                 | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |
| Tianma XM               | 1         | 0.09%   |
| Nvidia                  | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 9         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 9         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 8         | 0.72%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 7         | 0.63%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 7         | 0.63%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.54%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 6         | 0.54%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 6         | 0.54%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 5         | 0.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch              | 5         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 5         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 5         | 0.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 5         | 0.45%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch      | 4         | 0.36%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 4         | 0.36%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 4         | 0.36%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 4         | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 4         | 0.36%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 4         | 0.36%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 4         | 0.36%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 4         | 0.36%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 4         | 0.36%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch              | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch           | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 4         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 4         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.36%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 4         | 0.36%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                     | 4         | 0.36%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 4         | 0.36%   |
| AU Optronics LCD Monitor AUO109B 3840x2160 380x210mm 17.1-inch            | 4         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 479       | 46.06%  |
| 1366x768 (WXGA)    | 155       | 14.9%   |
| 1600x900 (HD+)     | 83        | 7.98%   |
| 3840x2160 (4K)     | 66        | 6.35%   |
| 2560x1440 (QHD)    | 45        | 4.33%   |
| 1280x800 (WXGA)    | 37        | 3.56%   |
| 1920x1200 (WUXGA)  | 33        | 3.17%   |
| 1440x900 (WXGA+)   | 24        | 2.31%   |
| 2560x1600          | 15        | 1.44%   |
| 1680x1050 (WSXGA+) | 15        | 1.44%   |
| 2880x1800          | 11        | 1.06%   |
| 3440x1440          | 10        | 0.96%   |
| 3840x2400          | 8         | 0.77%   |
| 3200x1800 (QHD+)   | 7         | 0.67%   |
| 1280x1024 (SXGA)   | 7         | 0.67%   |
| 3840x1600          | 5         | 0.48%   |
| 1024x600           | 5         | 0.48%   |
| 800x1280           | 4         | 0.38%   |
| 2560x1080          | 4         | 0.38%   |
| 1600x1200          | 4         | 0.38%   |
| 3000x2000          | 3         | 0.29%   |
| 2160x1440          | 3         | 0.29%   |
| 3840x1100          | 2         | 0.19%   |
| 3456x2160          | 2         | 0.19%   |
| 3072x1920          | 2         | 0.19%   |
| 1360x768           | 2         | 0.19%   |
| 1024x768 (XGA)     | 2         | 0.19%   |
| 3840x1080          | 1         | 0.1%    |
| 3286x1080          | 1         | 0.1%    |
| 2560x1024          | 1         | 0.1%    |
| 2288x1287          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1920x515           | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 378       | 34.21%  |
| 13      | 157       | 14.21%  |
| 14      | 147       | 13.3%   |
| 17      | 117       | 10.59%  |
| 27      | 64        | 5.79%   |
| 12      | 46        | 4.16%   |
| 24      | 35        | 3.17%   |
| 23      | 19        | 1.72%   |
| Unknown | 16        | 1.45%   |
| 21      | 15        | 1.36%   |
| 34      | 13        | 1.18%   |
| 11      | 12        | 1.09%   |
| 31      | 11        | 1%      |
| 16      | 10        | 0.9%    |
| 22      | 6         | 0.54%   |
| 84      | 5         | 0.45%   |
| 37      | 5         | 0.45%   |
| 20      | 5         | 0.45%   |
| 10      | 5         | 0.45%   |
| 40      | 4         | 0.36%   |
| 32      | 4         | 0.36%   |
| 19      | 4         | 0.36%   |
| 7       | 4         | 0.36%   |
| 72      | 3         | 0.27%   |
| 25      | 3         | 0.27%   |
| 18      | 3         | 0.27%   |
| 65      | 2         | 0.18%   |
| 54      | 2         | 0.18%   |
| 46      | 2         | 0.18%   |
| 142     | 1         | 0.09%   |
| 55      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 9       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 585       | 53.42%  |
| 201-300        | 156       | 14.25%  |
| 351-400        | 131       | 11.96%  |
| 501-600        | 113       | 10.32%  |
| 401-500        | 28        | 2.56%   |
| 701-800        | 17        | 1.55%   |
| 601-700        | 16        | 1.46%   |
| Unknown        | 16        | 1.46%   |
| 801-900        | 10        | 0.91%   |
| 1001-1500      | 9         | 0.82%   |
| 1501-2000      | 8         | 0.73%   |
| 1-100          | 4         | 0.37%   |
| More than 2000 | 1         | 0.09%   |
| 101-200        | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 767       | 78.83%  |
| 16/10   | 142       | 14.59%  |
| 21/9    | 18        | 1.85%   |
| Unknown | 12        | 1.23%   |
| 3/2     | 10        | 1.03%   |
| 4/3     | 8         | 0.82%   |
| 5/4     | 6         | 0.62%   |
| 0.67    | 4         | 0.41%   |
| 3.40    | 2         | 0.21%   |
| 32/9    | 1         | 0.1%    |
| 3.73    | 1         | 0.1%    |
| 2.50    | 1         | 0.1%    |
| 1.00    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 375       | 33.97%  |
| 81-90          | 223       | 20.2%   |
| 121-130        | 100       | 9.06%   |
| 71-80          | 77        | 6.97%   |
| 301-350        | 65        | 5.89%   |
| 201-250        | 58        | 5.25%   |
| 61-70          | 46        | 4.17%   |
| 351-500        | 30        | 2.72%   |
| 251-300        | 18        | 1.63%   |
| Unknown        | 16        | 1.45%   |
| More than 1000 | 15        | 1.36%   |
| 131-140        | 15        | 1.36%   |
| 51-60          | 14        | 1.27%   |
| 501-1000       | 12        | 1.09%   |
| 151-200        | 11        | 1%      |
| 111-120        | 11        | 1%      |
| 41-50          | 5         | 0.45%   |
| 1-40           | 5         | 0.45%   |
| 141-150        | 4         | 0.36%   |
| 91-100         | 4         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 469       | 43.67%  |
| 101-120       | 242       | 22.53%  |
| 51-100        | 155       | 14.43%  |
| 161-240       | 114       | 10.61%  |
| More than 240 | 65        | 6.05%   |
| Unknown       | 16        | 1.49%   |
| 1-50          | 13        | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 758       | 77.03%  |
| 2     | 178       | 18.09%  |
| 0     | 26        | 2.64%   |
| 3     | 22        | 2.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 618       | 40.95%  |
| Realtek Semiconductor             | 389       | 25.78%  |
| Qualcomm Atheros                  | 157       | 10.4%   |
| Broadcom                          | 94        | 6.23%   |
| Broadcom Limited                  | 28        | 1.86%   |
| Ralink                            | 21        | 1.39%   |
| Lenovo                            | 18        | 1.19%   |
| MediaTek                          | 17        | 1.13%   |
| ASIX Electronics                  | 16        | 1.06%   |
| Dell                              | 15        | 0.99%   |
| Sierra Wireless                   | 14        | 0.93%   |
| Hewlett-Packard                   | 14        | 0.93%   |
| Marvell Technology Group          | 13        | 0.86%   |
| Ericsson Business Mobile Networks | 13        | 0.86%   |
| Qualcomm                          | 11        | 0.73%   |
| DisplayLink                       | 11        | 0.73%   |
| Huawei Technologies               | 8         | 0.53%   |
| Nvidia                            | 6         | 0.4%    |
| Samsung Electronics               | 5         | 0.33%   |
| ASUSTek Computer                  | 5         | 0.33%   |
| Xiaomi                            | 4         | 0.27%   |
| Ralink Technology                 | 4         | 0.27%   |
| Fibocom                           | 4         | 0.27%   |
| Edimax Technology                 | 4         | 0.27%   |
| TP-Link                           | 3         | 0.2%    |
| NetGear                           | 2         | 0.13%   |
| Linksys                           | 2         | 0.13%   |
| D-Link                            | 2         | 0.13%   |
| Wilocity                          | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| Novatek Microelectronics          | 1         | 0.07%   |
| MosChip Semiconductor             | 1         | 0.07%   |
| JMicron Technology                | 1         | 0.07%   |
| Intersil                          | 1         | 0.07%   |
| HMD Global                        | 1         | 0.07%   |
| AVM                               | 1         | 0.07%   |
| Arduino SA                        | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |
| AMD                               | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 268       | 14.34%  |
| Intel Wireless 8265 / 8275                                        | 69        | 3.69%   |
| Intel Wi-Fi 6 AX200                                               | 69        | 3.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 2.57%   |
| Intel Wireless 7260                                               | 43        | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 2.14%   |
| Intel Wi-Fi 6 AX201                                               | 40        | 2.14%   |
| Intel Wireless 7265                                               | 37        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 1.44%   |
| Intel Wireless 8260                                               | 25        | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 1.23%   |
| Intel Centrino Ultimate-N 6300                                    | 23        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 21        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 21        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 0.91%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 14        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 0.7%    |
| Intel Wireless-AC 9260                                            | 13        | 0.7%    |
| Intel Wireless 3160                                               | 13        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 0.7%    |
| Intel Centrino Advanced-N 6235                                    | 13        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 12        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 604       | 60.58%  |
| Qualcomm Atheros      | 134       | 13.44%  |
| Realtek Semiconductor | 72        | 7.22%   |
| Broadcom              | 70        | 7.02%   |
| Ralink                | 21        | 2.11%   |
| Broadcom Limited      | 18        | 1.81%   |
| MediaTek              | 15        | 1.5%    |
| Sierra Wireless       | 14        | 1.4%    |
| Qualcomm              | 9         | 0.9%    |
| Dell                  | 8         | 0.8%    |
| Hewlett-Packard       | 7         | 0.7%    |
| ASUSTek Computer      | 5         | 0.5%    |
| Ralink Technology     | 4         | 0.4%    |
| Fibocom               | 4         | 0.4%    |
| Edimax Technology     | 4         | 0.4%    |
| TP-Link               | 2         | 0.2%    |
| NetGear               | 2         | 0.2%    |
| Wilocity              | 1         | 0.1%    |
| Linksys               | 1         | 0.1%    |
| D-Link                | 1         | 0.1%    |
| AVM                   | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 69        | 6.88%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 6.88%   |
| Intel Wireless 7260                                                     | 43        | 4.29%   |
| Intel Wi-Fi 6 AX201                                                     | 40        | 3.99%   |
| Intel Wireless 7265                                                     | 37        | 3.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 37        | 3.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 2.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 27        | 2.69%   |
| Intel Wireless 8260                                                     | 25        | 2.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.29%   |
| Intel Centrino Ultimate-N 6300                                          | 23        | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 21        | 2.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 21        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 15        | 1.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 14        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.3%    |
| Intel Wireless-AC 9260                                                  | 13        | 1.3%    |
| Intel Wireless 3160                                                     | 13        | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 1.3%    |
| Intel Centrino Advanced-N 6235                                          | 13        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.2%    |
| Intel Wireless 3165                                                     | 11        | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 10        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 0.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.8%    |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 7         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 362       | 44.42%  |
| Intel                         | 266       | 32.64%  |
| Qualcomm Atheros              | 48        | 5.89%   |
| Broadcom                      | 43        | 5.28%   |
| Lenovo                        | 18        | 2.21%   |
| ASIX Electronics              | 16        | 1.96%   |
| Marvell Technology Group      | 13        | 1.6%    |
| DisplayLink                   | 11        | 1.35%   |
| Broadcom Limited              | 10        | 1.23%   |
| Nvidia                        | 6         | 0.74%   |
| Xiaomi                        | 4         | 0.49%   |
| Huawei Technologies           | 3         | 0.37%   |
| Samsung Electronics           | 2         | 0.25%   |
| Qualcomm                      | 2         | 0.25%   |
| MediaTek                      | 2         | 0.25%   |
| TP-Link                       | 1         | 0.12%   |
| OnePlus Technology (Shenzhen) | 1         | 0.12%   |
| MosChip Semiconductor         | 1         | 0.12%   |
| Linksys                       | 1         | 0.12%   |
| JMicron Technology            | 1         | 0.12%   |
| HMD Global                    | 1         | 0.12%   |
| Hewlett-Packard               | 1         | 0.12%   |
| D-Link                        | 1         | 0.12%   |
| Apple                         | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 268       | 32.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 7.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 5.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 4.86%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 2.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 2.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 2.19%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 2.07%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 2.07%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 2.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 1.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 1.7%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 9         | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 1.09%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 7         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.85%   |
| Lenovo ThinkPad Lan                                               | 6         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.73%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 0.73%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.61%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 5         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.49%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 940       | 53.47%  |
| Ethernet | 776       | 44.14%  |
| Modem    | 41        | 2.33%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 763       | 75.84%  |
| Ethernet | 242       | 24.06%  |
| Modem    | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 681       | 71.31%  |
| 1     | 247       | 25.86%  |
| 3     | 16        | 1.68%   |
| 0     | 11        | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 776       | 79.1%   |
| Yes  | 205       | 20.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 446       | 57.62%  |
| Broadcom                        | 60        | 7.75%   |
| Qualcomm Atheros Communications | 39        | 5.04%   |
| Foxconn / Hon Hai               | 38        | 4.91%   |
| Realtek Semiconductor           | 36        | 4.65%   |
| Apple                           | 33        | 4.26%   |
| Lite-On Technology              | 31        | 4.01%   |
| IMC Networks                    | 23        | 2.97%   |
| Hewlett-Packard                 | 14        | 1.81%   |
| Dell                            | 12        | 1.55%   |
| Cambridge Silicon Radio         | 10        | 1.29%   |
| Ralink                          | 9         | 1.16%   |
| USI                             | 5         | 0.65%   |
| Toshiba                         | 3         | 0.39%   |
| Alps Electric                   | 3         | 0.39%   |
| Realtek                         | 2         | 0.26%   |
| Ralink Technology               | 2         | 0.26%   |
| Chicony Electronics             | 2         | 0.26%   |
| ASUSTek Computer                | 2         | 0.26%   |
| Taiyo Yuden                     | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 192       | 24.74%  |
| Intel AX201 Bluetooth                               | 79        | 10.18%  |
| Intel AX200 Bluetooth                               | 66        | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 5.54%   |
| Realtek Bluetooth Radio                             | 24        | 3.09%   |
| Intel Bluetooth Device                              | 24        | 3.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 2.58%   |
| Apple Bluetooth Host Controller                     | 19        | 2.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 2.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 1.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.29%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.29%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.29%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.77%   |
| USI Bluetooth Device                                | 5         | 0.64%   |
| Lite-On Bluetooth Device                            | 5         | 0.64%   |
| Intel AX210 Bluetooth                               | 5         | 0.64%   |
| IMC Networks Wireless_Device                        | 5         | 0.64%   |
| IMC Networks Bluetooth Device                       | 5         | 0.64%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.64%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.52%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.52%   |
| Lite-On Wireless_Device                             | 3         | 0.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.39%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 825       | 68.52%  |
| Nvidia                   | 152       | 12.62%  |
| AMD                      | 134       | 11.13%  |
| Lenovo                   | 14        | 1.16%   |
| GN Netcom                | 14        | 1.16%   |
| Hewlett-Packard          | 9         | 0.75%   |
| Logitech                 | 8         | 0.66%   |
| Realtek Semiconductor    | 7         | 0.58%   |
| C-Media Electronics      | 7         | 0.58%   |
| Plantronics              | 5         | 0.42%   |
| Kingston Technology      | 3         | 0.25%   |
| VIA Technologies         | 2         | 0.17%   |
| SteelSeries ApS          | 2         | 0.17%   |
| RODE Microphones         | 2         | 0.17%   |
| Conexant Systems         | 2         | 0.17%   |
| BEHRINGER International  | 2         | 0.17%   |
| Tenx Technology          | 1         | 0.08%   |
| ROCCAT                   | 1         | 0.08%   |
| Other World Computing    | 1         | 0.08%   |
| Nordic Semiconductor ASA | 1         | 0.08%   |
| miniDSP                  | 1         | 0.08%   |
| Magic Control Technology | 1         | 0.08%   |
| JMTek                    | 1         | 0.08%   |
| Griffin Technology       | 1         | 0.08%   |
| freeVoice                | 1         | 0.08%   |
| Elite Silicon            | 1         | 0.08%   |
| Cambridge Silicon Radio  | 1         | 0.08%   |
| AudioQuest               | 1         | 0.08%   |
| ASUSTek Computer         | 1         | 0.08%   |
| Astro Gaming             | 1         | 0.08%   |
| Apple                    | 1         | 0.08%   |
| Afatech                  | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 147       | 10.37%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 93        | 6.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 73        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 62        | 4.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 56        | 3.95%   |
| Intel 8 Series HD Audio Controller                                                                | 56        | 3.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 53        | 3.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 51        | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 47        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 41        | 2.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 37        | 2.61%   |
| Intel Broadwell-U Audio Controller                                                                | 37        | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 34        | 2.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28        | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 23        | 1.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 18        | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 1.06%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 15        | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 14        | 0.99%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.85%   |
| AMD FCH Azalia Controller                                                                         | 12        | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 9         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 8         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 211       | 32.76%  |
| SK hynix            | 167       | 25.93%  |
| Micron Technology   | 82        | 12.73%  |
| Kingston            | 62        | 9.63%   |
| Unknown             | 37        | 5.75%   |
| Crucial             | 21        | 3.26%   |
| Elpida              | 15        | 2.33%   |
| Corsair             | 15        | 2.33%   |
| A-DATA Technology   | 10        | 1.55%   |
| Ramaxel Technology  | 9         | 1.4%    |
| Nanya Technology    | 4         | 0.62%   |
| Unknown             | 4         | 0.62%   |
| G.Skill             | 2         | 0.31%   |
| ASint Technology    | 2         | 0.31%   |
| Unknown (08AE)      | 1         | 0.16%   |
| OnBoard             | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 2.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 1.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.01%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 1.01%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 1.01%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.87%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 6         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.87%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.87%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.72%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 5         | 0.72%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.58%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.58%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.58%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.58%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 4         | 0.58%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.58%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 4         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 254       | 45.28%  |
| DDR3    | 198       | 35.29%  |
| LPDDR3  | 40        | 7.13%   |
| LPDDR4  | 24        | 4.28%   |
| DDR2    | 16        | 2.85%   |
| DDR5    | 9         | 1.6%    |
| LPDDR5  | 8         | 1.43%   |
| SDRAM   | 7         | 1.25%   |
| DDR     | 3         | 0.53%   |
| Unknown | 2         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 486       | 86.79%  |
| Row Of Chips | 63        | 11.25%  |
| Chip         | 8         | 1.43%   |
| Unknown      | 2         | 0.36%   |
| DIMM         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 247       | 40.29%  |
| 4096  | 154       | 25.12%  |
| 16384 | 122       | 19.9%   |
| 2048  | 56        | 9.14%   |
| 32768 | 17        | 2.77%   |
| 1024  | 16        | 2.61%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 131       | 21.72%  |
| 2667    | 122       | 20.23%  |
| 3200    | 100       | 16.58%  |
| 2133    | 54        | 8.96%   |
| 1334    | 40        | 6.63%   |
| 2400    | 37        | 6.14%   |
| 1333    | 21        | 3.48%   |
| 4267    | 11        | 1.82%   |
| 1067    | 10        | 1.66%   |
| 4800    | 9         | 1.49%   |
| 667     | 9         | 1.49%   |
| Unknown | 9         | 1.49%   |
| 6400    | 8         | 1.33%   |
| 3266    | 6         | 1%      |
| 1867    | 5         | 0.83%   |
| 800     | 5         | 0.83%   |
| 8400    | 4         | 0.66%   |
| 4266    | 3         | 0.5%    |
| 4199    | 3         | 0.5%    |
| 3733    | 3         | 0.5%    |
| 2048    | 3         | 0.5%    |
| 1066    | 3         | 0.5%    |
| 975     | 2         | 0.33%   |
| 5600    | 1         | 0.17%   |
| 3000    | 1         | 0.17%   |
| 1639    | 1         | 0.17%   |
| 333     | 1         | 0.17%   |
| 266     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 44.44%  |
| Samsung Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Konica Minolta      | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series | 1         | 11.11%  |
| Prolific PL2305 Parallel Port  | 1         | 11.11%  |
| Konica Minolta Printer         | 1         | 11.11%  |
| HP Laserjet P1505              | 1         | 11.11%  |
| Canon PIXMA TS6250             | 1         | 11.11%  |
| Brother MFC Composite Device   | 1         | 11.11%  |
| Brother HL-3040CN series       | 1         | 11.11%  |
| Brother HL-2030 Laser Printer  | 1         | 11.11%  |
| Brother DCP-7055W              | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Seiko Epson       | 1         | 50%     |
| Canon Electronics | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon P-150 Scanner                                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 279       | 31.63%  |
| IMC Networks                           | 73        | 8.28%   |
| Microdia                               | 61        | 6.92%   |
| Realtek Semiconductor                  | 52        | 5.9%    |
| Bison Electronics                      | 50        | 5.67%   |
| Quanta                                 | 45        | 5.1%    |
| Sunplus Innovation Technology          | 41        | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 4.31%   |
| Apple                                  | 32        | 3.63%   |
| Suyin                                  | 29        | 3.29%   |
| Lite-On Technology                     | 29        | 3.29%   |
| Acer                                   | 28        | 3.17%   |
| Lenovo                                 | 17        | 1.93%   |
| Syntek                                 | 15        | 1.7%    |
| Ricoh                                  | 13        | 1.47%   |
| Logitech                               | 12        | 1.36%   |
| Luxvisions Innotech Limited            | 11        | 1.25%   |
| Alcor Micro                            | 9         | 1.02%   |
| Silicon Motion                         | 6         | 0.68%   |
| Samsung Electronics                    | 5         | 0.57%   |
| Primax Electronics                     | 5         | 0.57%   |
| ALi                                    | 4         | 0.45%   |
| Z-Star Microelectronics                | 3         | 0.34%   |
| Sonix Technology                       | 3         | 0.34%   |
| Tripath Technology                     | 2         | 0.23%   |
| OmniVision Technologies                | 2         | 0.23%   |
| Generalplus Technology                 | 2         | 0.23%   |
| DigiTech                               | 2         | 0.23%   |
| Xiaomi                                 | 1         | 0.11%   |
| WCM_USB                                | 1         | 0.11%   |
| Tobii Technology AB                    | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |
| Nikon                                  | 1         | 0.11%   |
| Mimaki Engineering                     | 1         | 0.11%   |
| Leap Motion                            | 1         | 0.11%   |
| Jieli Technology                       | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Importek                               | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 73        | 8.19%   |
| Microdia Integrated_Webcam_HD           | 34        | 3.82%   |
| Chicony HD WebCam                       | 33        | 3.7%    |
| IMC Networks Integrated Camera          | 30        | 3.37%   |
| Chicony HP HD Camera                    | 23        | 2.58%   |
| Realtek Integrated_Webcam_HD            | 18        | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam       | 18        | 2.02%   |
| Lite-On Integrated Camera               | 14        | 1.57%   |
| Bison Integrated Camera                 | 14        | 1.57%   |
| Quanta HP HD Camera                     | 13        | 1.46%   |
| Chicony USB2.0 Camera                   | 13        | 1.46%   |
| Sunplus HD WebCam                       | 12        | 1.35%   |
| Chicony HP Truevision HD                | 11        | 1.23%   |
| Microdia Integrated Webcam              | 10        | 1.12%   |
| Apple FaceTime HD Camera                | 10        | 1.12%   |
| Sunplus Integrated_Webcam_HD            | 9         | 1.01%   |
| Lite-On HP HD Camera                    | 9         | 1.01%   |
| Chicony Integrated Camera (1280x720@30) | 9         | 1.01%   |
| Chicony HD User Facing                  | 8         | 0.9%    |
| Apple Built-in iSight                   | 8         | 0.9%    |
| Syntek Integrated Camera                | 7         | 0.79%   |
| Suyin HP Truevision HD                  | 7         | 0.79%   |
| Lenovo Integrated Webcam                | 7         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 7         | 0.79%   |
| Chicony HP HD Webcam                    | 7         | 0.79%   |
| Bison SunplusIT Integrated Camera       | 7         | 0.79%   |
| Syntek Lenovo EasyCamera                | 6         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam            | 6         | 0.67%   |
| Quanta HD User Facing                   | 6         | 0.67%   |
| Lenovo Integrated Webcam [R5U877]       | 6         | 0.67%   |
| Chicony HP Wide Vision HD Camera        | 6         | 0.67%   |
| Chicony CNF9055 Toshiba Webcam          | 6         | 0.67%   |
| Bison BisonCam,NB Pro                   | 6         | 0.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 6         | 0.67%   |
| Acer Integrated Camera                  | 6         | 0.67%   |
| Samsung Galaxy A5 (MTP)                 | 5         | 0.56%   |
| Ricoh USB2.0 Camera                     | 5         | 0.56%   |
| Quanta HP TrueVision HD Camera          | 5         | 0.56%   |
| Quanta HD Webcam                        | 5         | 0.56%   |
| Chicony TOSHIBA Web Camera - HD         | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 114       | 39.04%  |
| Synaptics                  | 95        | 32.53%  |
| Shenzhen Goodix Technology | 22        | 7.53%   |
| Upek                       | 19        | 6.51%   |
| Elan Microelectronics      | 16        | 5.48%   |
| AuthenTec                  | 14        | 4.79%   |
| LighTuning Technology      | 10        | 3.42%   |
| STMicroelectronics         | 2         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 12.67%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 6.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 5.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 4.45%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 3.77%   |
| Elan ELAN:ARM-M4                                                           | 11        | 3.77%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 3.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 3.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 3.08%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 3.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 3.08%   |
| Validity Sensors VFS491                                                    | 8         | 2.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.4%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.4%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.71%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.71%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.71%   |
| AuthenTec AES2810                                                          | 5         | 1.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.37%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.37%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.03%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.03%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.03%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.03%   |
| Synaptics  WBDI                                                            | 3         | 1.03%   |
| Unknown                                                                    | 3         | 1.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.68%   |
| Synaptics UWP WBDI                                                         | 2         | 0.68%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.34%   |
| Synaptics WBDI Device                                                      | 1         | 0.34%   |
| Synaptics WBDI                                                             | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 45        | 41.28%  |
| Broadcom                  | 37        | 33.94%  |
| Upek                      | 12        | 11.01%  |
| O2 Micro                  | 5         | 4.59%   |
| Yubico.com                | 3         | 2.75%   |
| Lenovo                    | 3         | 2.75%   |
| OmniKey                   | 1         | 0.92%   |
| Gemalto (was Gemplus)     | 1         | 0.92%   |
| Clay Logic                | 1         | 0.92%   |
| Aladdin Knowledge Systems | 1         | 0.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 41.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 11.93%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 11.01%  |
| Broadcom 5880                                                                | 11        | 10.09%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.42%   |
| Broadcom 58200                                                               | 6         | 5.5%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.59%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.75%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.83%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.92%   |
| OmniKey CardMan 4321                                                         | 1         | 0.92%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.92%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.92%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.92%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 500       | 50.81%  |
| 1     | 368       | 37.4%   |
| 2     | 96        | 9.76%   |
| 3     | 14        | 1.42%   |
| 4     | 3         | 0.3%    |
| 7     | 2         | 0.2%    |
| 5     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 288       | 46.83%  |
| Chipcard                 | 94        | 15.28%  |
| Graphics card            | 83        | 13.5%   |
| Net/wireless             | 41        | 6.67%   |
| Multimedia controller    | 23        | 3.74%   |
| Camera                   | 18        | 2.93%   |
| Bluetooth                | 17        | 2.76%   |
| Communication controller | 12        | 1.95%   |
| Card reader              | 10        | 1.63%   |
| Storage                  | 7         | 1.14%   |
| Net/ethernet             | 7         | 1.14%   |
| Sound                    | 5         | 0.81%   |
| Modem                    | 4         | 0.65%   |
| Network                  | 2         | 0.33%   |
| Unassigned class         | 1         | 0.16%   |
| Storage/nvme             | 1         | 0.16%   |
| Flash memory             | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

