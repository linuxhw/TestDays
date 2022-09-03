Gentoo 2.8 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 148

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [21392e76a8](https://linux-hardware.org/?probe=21392e76a8) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| win elemen... | MoreFine S500+              | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [a1b7c5d6ab](https://linux-hardware.org/?probe=a1b7c5d6ab) | Aug 27, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [8a23dbfd36](https://linux-hardware.org/?probe=8a23dbfd36) | Aug 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [6d0a3e71d7](https://linux-hardware.org/?probe=6d0a3e71d7) | Aug 24, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Purism        | Librem 15 v4                | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Razer         | Blade 15 Studio Edition ... | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | GS63VR 6RF                  | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| HP            | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Dell          | Latitude D420               | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
| Timi          | RedmiBook 13                | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Dell          | Precision 7550              | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| Dell          | XPS 17 9710                 | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | 1005HA                      | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| MSI           | GE66 Raider 11UE            | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| Dell          | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| MSI           | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Framework     | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Framework     | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| MSI           | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi          | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Dell          | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Framework     | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Dell          | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Acer          | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell          | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                         | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| 5.15.52-gentoo                                  | 5         | 4.5%    |
| 5.19.0-gentoo-x86_64                            | 4         | 3.6%    |
| 5.15.59-gentoo-x86_64                           | 3         | 2.7%    |
| 5.15.41-gentoo-x86_64                           | 3         | 2.7%    |
| 5.14.9-gentoo-x86_64                            | 3         | 2.7%    |
| 5.18.7-gentoo                                   | 2         | 1.8%    |
| 5.18.4-gentoo                                   | 2         | 1.8%    |
| 5.18.1-gentoo-r2                                | 2         | 1.8%    |
| 5.17.1-gentoo-r1                                | 2         | 1.8%    |
| 5.16.0-gentoo-x86_64                            | 2         | 1.8%    |
| 5.15.59-gentoo                                  | 2         | 1.8%    |
| 5.15.52-gentoo-x86_64                           | 2         | 1.8%    |
| 5.15.41-gentoo-dist                             | 2         | 1.8%    |
| 5.15.10-gentoo-x86_64                           | 2         | 1.8%    |
| 5.19.3-gentoo-x86_64                            | 1         | 0.9%    |
| 5.19.0-xanmod1-elitebook                        | 1         | 0.9%    |
| 5.19.0-rc2-p+                                   | 1         | 0.9%    |
| 5.19.0-gentoo                                   | 1         | 0.9%    |
| 5.18.9-gentoo                                   | 1         | 0.9%    |
| 5.18.8-gentoo-dist                              | 1         | 0.9%    |
| 5.18.8-gentoo                                   | 1         | 0.9%    |
| 5.18.6-gentoo-venus                             | 1         | 0.9%    |
| 5.18.5-gentoo                                   | 1         | 0.9%    |
| 5.18.19-gentoo-r1                               | 1         | 0.9%    |
| 5.18.15-gentoo-dist                             | 1         | 0.9%    |
| 5.18.10-k08                                     | 1         | 0.9%    |
| 5.18.1-gentoo-r1-x86_64                         | 1         | 0.9%    |
| 5.18.1-gentoo-r1                                | 1         | 0.9%    |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 0.9%    |
| 5.18.0-gbfc780ef1ca0                            | 1         | 0.9%    |
| 5.18.0-g95ff72a6c129                            | 1         | 0.9%    |
| 5.17.9-gentoo-x86_64                            | 1         | 0.9%    |
| 5.17.9-gentoo-x86                               | 1         | 0.9%    |
| 5.17.9-gentoo                                   | 1         | 0.9%    |
| 5.17.8-gentoo-x86_64                            | 1         | 0.9%    |
| 5.17.8-gentoo                                   | 1         | 0.9%    |
| 5.17.7-gentoo-groovin                           | 1         | 0.9%    |
| 5.17.6-zen1                                     | 1         | 0.9%    |
| 5.17.5-gentoo-dist                              | 1         | 0.9%    |
| 5.17.3-gentoo                                   | 1         | 0.9%    |
| 5.17.2-gentoo-groovin                           | 1         | 0.9%    |
| 5.17.13-gentoo                                  | 1         | 0.9%    |
| 5.17.12-gentoo-dist                             | 1         | 0.9%    |
| 5.17.0-gentoo-x86_64                            | 1         | 0.9%    |
| 5.16.9-gentoo-dist                              | 1         | 0.9%    |
| 5.16.8-gentoo-gentoo-dist                       | 1         | 0.9%    |
| 5.16.5-gentoo-x86_64                            | 1         | 0.9%    |
| 5.16.2-gentoo-x86_64                            | 1         | 0.9%    |
| 5.16.2-gentoo                                   | 1         | 0.9%    |
| 5.16.14-gentoo-x86_64-lto                       | 1         | 0.9%    |
| 5.16.14-gentoo                                  | 1         | 0.9%    |
| 5.16.11-gentoo-dist                             | 1         | 0.9%    |
| 5.16.10-gentoo--20-feb-2022                     | 1         | 0.9%    |
| 5.16.10-gentoo                                  | 1         | 0.9%    |
| 5.16.1-gentoo-x86_64                            | 1         | 0.9%    |
| 5.16.1-gentoo                                   | 1         | 0.9%    |
| 5.16.0-xanmod1                                  | 1         | 0.9%    |
| 5.16.0-pf5                                      | 1         | 0.9%    |
| 5.16.0-kali7-amd64                              | 1         | 0.9%    |
| 5.16.0-gentoo-gentoo-dist                       | 1         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.52 | 9         | 8.18%   |
| 5.19.0  | 7         | 6.36%   |
| 5.16.0  | 7         | 6.36%   |
| 5.15.59 | 7         | 6.36%   |
| 5.15.41 | 6         | 5.45%   |
| 5.18.1  | 4         | 3.64%   |
| 5.14.9  | 4         | 3.64%   |
| 5.17.9  | 3         | 2.73%   |
| 5.15.5  | 3         | 2.73%   |
| 5.18.8  | 2         | 1.82%   |
| 5.18.7  | 2         | 1.82%   |
| 5.18.4  | 2         | 1.82%   |
| 5.18.0  | 2         | 1.82%   |
| 5.17.8  | 2         | 1.82%   |
| 5.17.1  | 2         | 1.82%   |
| 5.16.2  | 2         | 1.82%   |
| 5.16.14 | 2         | 1.82%   |
| 5.16.10 | 2         | 1.82%   |
| 5.16.1  | 2         | 1.82%   |
| 5.15.33 | 2         | 1.82%   |
| 5.15.13 | 2         | 1.82%   |
| 5.15.10 | 2         | 1.82%   |
| 5.14.14 | 2         | 1.82%   |
| 5.19.3  | 1         | 0.91%   |
| 5.18.9  | 1         | 0.91%   |
| 5.18.6  | 1         | 0.91%   |
| 5.18.5  | 1         | 0.91%   |
| 5.18.19 | 1         | 0.91%   |
| 5.18.15 | 1         | 0.91%   |
| 5.18.10 | 1         | 0.91%   |
| 5.17.7  | 1         | 0.91%   |
| 5.17.6  | 1         | 0.91%   |
| 5.17.5  | 1         | 0.91%   |
| 5.17.3  | 1         | 0.91%   |
| 5.17.2  | 1         | 0.91%   |
| 5.17.13 | 1         | 0.91%   |
| 5.17.12 | 1         | 0.91%   |
| 5.17.0  | 1         | 0.91%   |
| 5.16.9  | 1         | 0.91%   |
| 5.16.8  | 1         | 0.91%   |
| 5.16.5  | 1         | 0.91%   |
| 5.16.11 | 1         | 0.91%   |
| 5.15.7  | 1         | 0.91%   |
| 5.15.61 | 1         | 0.91%   |
| 5.15.6  | 1         | 0.91%   |
| 5.15.55 | 1         | 0.91%   |
| 5.15.35 | 1         | 0.91%   |
| 5.15.19 | 1         | 0.91%   |
| 5.15.12 | 1         | 0.91%   |
| 5.15.1  | 1         | 0.91%   |
| 5.14.7  | 1         | 0.91%   |
| 5.10.83 | 1         | 0.91%   |
| 5.10.76 | 1         | 0.91%   |
| 5.10.70 | 1         | 0.91%   |
| 5.10.27 | 1         | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 38        | 35.85%  |
| 5.16    | 18        | 16.98%  |
| 5.18    | 17        | 16.04%  |
| 5.17    | 14        | 13.21%  |
| 5.19    | 8         | 7.55%   |
| 5.14    | 7         | 6.6%    |
| 5.10    | 4         | 3.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 95.96%  |
| i686   | 4         | 4.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 38        | 38%     |
| KDE5     | 33        | 33%     |
| GNOME    | 11        | 11%     |
| XFCE     | 7         | 7%      |
| sway     | 2         | 2%      |
| LXQt     | 2         | 2%      |
| dwm      | 2         | 2%      |
| xmonad   | 1         | 1%      |
| MATE     | 1         | 1%      |
| LeftWM   | 1         | 1%      |
| fvwm     | 1         | 1%      |
| Cinnamon | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 49        | 48.04%  |
| Wayland | 20        | 19.61%  |
| Unknown | 17        | 16.67%  |
| Tty     | 16        | 15.69%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 38        | 38%     |
| Unknown | 37        | 37%     |
| LightDM | 14        | 14%     |
| GDM     | 6         | 6%      |
| SLiM    | 2         | 2%      |
| XDM     | 1         | 1%      |
| LXDM    | 1         | 1%      |
| GREETD  | 1         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 49        | 49.49%  |
| C.UTF8     | 12        | 12.12%  |
| en_GB      | 7         | 7.07%   |
| Unknown    | 7         | 7.07%   |
| C          | 4         | 4.04%   |
| de_DE      | 3         | 3.03%   |
| ru_RU      | 2         | 2.02%   |
| it_IT      | 2         | 2.02%   |
| es_AR      | 2         | 2.02%   |
| en_AU      | 2         | 2.02%   |
| zh_CN      | 1         | 1.01%   |
| tr_TR      | 1         | 1.01%   |
| fr_FR      | 1         | 1.01%   |
| fr_CA      | 1         | 1.01%   |
| es_MX      | 1         | 1.01%   |
| en_US.UTF8 | 1         | 1.01%   |
| en_NZ      | 1         | 1.01%   |
| el_GR      | 1         | 1.01%   |
| de_CH      | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 89        | 89%     |
| BIOS | 11        | 11%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 55        | 55.56%  |
| Btrfs    | 32        | 32.32%  |
| Zfs      | 5         | 5.05%   |
| XXXXXXX  | 4         | 4.04%   |
| Overlay  | 1         | 1.01%   |
| F2fs     | 1         | 1.01%   |
| Bcachefs | 1         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 91        | 91.92%  |
| MBR  | 8         | 8.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 76.47%  |
| Yes       | 24        | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 77%     |
| Yes       | 23        | 23%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 31        | 31.31%  |
| Hewlett-Packard     | 13        | 13.13%  |
| Dell                | 13        | 13.13%  |
| ASUSTek Computer    | 11        | 11.11%  |
| MSI                 | 5         | 5.05%   |
| Timi                | 4         | 4.04%   |
| Acer                | 4         | 4.04%   |
| Toshiba             | 3         | 3.03%   |
| HUAWEI              | 2         | 2.02%   |
| Framework           | 2         | 2.02%   |
| win element         | 1         | 1.01%   |
| TUXEDO              | 1         | 1.01%   |
| System76            | 1         | 1.01%   |
| Samsung Electronics | 1         | 1.01%   |
| Razer               | 1         | 1.01%   |
| Purism              | 1         | 1.01%   |
| Notebook            | 1         | 1.01%   |
| IBM                 | 1         | 1.01%   |
| Eluktronics         | 1         | 1.01%   |
| BANGHO              | 1         | 1.01%   |
| AVITA               | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba Satellite C850D-118               | 2         | 2.02%   |
| MSI GS63VR 6RF                            | 2         | 2.02%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 2         | 2.02%   |
| HP Laptop 15s-eq0xxx                      | 2         | 2.02%   |
| Framework Laptop                          | 2         | 2.02%   |
| Dell XPS 15 9570                          | 2         | 2.02%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 2.02%   |
| win element MoreFine S500+                | 1         | 1.01%   |
| TUXEDO InfinityBook Pro 14 Gen6           | 1         | 1.01%   |
| Toshiba NB100                             | 1         | 1.01%   |
| Timi RedmiBook 13                         | 1         | 1.01%   |
| Timi Mi Laptop Pro 15 2020                | 1         | 1.01%   |
| Timi Mi Laptop Pro 15                     | 1         | 1.01%   |
| Timi A35                                  | 1         | 1.01%   |
| System76 Gazelle                          | 1         | 1.01%   |
| Samsung 700G7C                            | 1         | 1.01%   |
| Razer Blade 15 Studio Edition - Late 2019 | 1         | 1.01%   |
| Purism Librem 15 v4                       | 1         | 1.01%   |
| Notebook N141CU                           | 1         | 1.01%   |
| MSI MS-7A34                               | 1         | 1.01%   |
| MSI GE73 Raider RGB 8RF                   | 1         | 1.01%   |
| MSI GE66 Raider 11UE                      | 1         | 1.01%   |
| Lenovo Yoga Slim 7 14IIL05 82A1           | 1         | 1.01%   |
| Lenovo Yoga S940-14IWL 81Q7               | 1         | 1.01%   |
| Lenovo Yoga S740-14IIL 81RS               | 1         | 1.01%   |
| Lenovo ThinkPad Z16 Gen 1 21D4002GGE      | 1         | 1.01%   |
| Lenovo ThinkPad X220 4291QT1              | 1         | 1.01%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI  | 1         | 1.01%   |
| Lenovo ThinkPad T470p 20J7S06Q00          | 1         | 1.01%   |
| Lenovo ThinkPad T460 20FMS421US           | 1         | 1.01%   |
| Lenovo ThinkPad T14 Gen 2a 20XK002SCK     | 1         | 1.01%   |
| Lenovo ThinkPad T14 Gen 2a 20XK000YRI     | 1         | 1.01%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00      | 1         | 1.01%   |
| Lenovo ThinkPad P73 20QSS09S00            | 1         | 1.01%   |
| Lenovo ThinkPad P50 20EQS33R0J            | 1         | 1.01%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F437       | 1         | 1.01%   |
| Lenovo ThinkPad L15 Gen 2a 20X7006PAU     | 1         | 1.01%   |
| Lenovo ThinkPad E495 20NE000BGE           | 1         | 1.01%   |
| Lenovo ThinkPad E15 Gen 2 20T8001STX      | 1         | 1.01%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB      | 1         | 1.01%   |
| Lenovo ThinkPad 20FMCT01WW                | 1         | 1.01%   |
| Lenovo ThinkBook 14 G3 ACL 21A2           | 1         | 1.01%   |
| Lenovo ThinkBook 13s G2 ITL 20V9          | 1         | 1.01%   |
| Lenovo Legion Y7000 2019 PG0 81T0         | 1         | 1.01%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 1.01%   |
| Lenovo Legion R7000 2020 82B6             | 1         | 1.01%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 1.01%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 1         | 1.01%   |
| Lenovo IdeaPad 3 15ALC6 82KU              | 1         | 1.01%   |
| Lenovo IdeaPad 100-15IBD 80QQ             | 1         | 1.01%   |
| Lenovo G510 20238                         | 1         | 1.01%   |
| IBM 2722BDG                               | 1         | 1.01%   |
| HUAWEI HVY-WXX9                           | 1         | 1.01%   |
| HUAWEI BOHB-WAX9                          | 1         | 1.01%   |
| HP Victus by Laptop 16-e0xxx              | 1         | 1.01%   |
| HP ProBook 6570b                          | 1         | 1.01%   |
| HP Pavilion Notebook                      | 1         | 1.01%   |
| HP Pavilion Gaming Laptop 15-cx0xxx       | 1         | 1.01%   |
| HP OMEN by Laptop 16-c0xxx                | 1         | 1.01%   |
| HP OMEN by Laptop 15-dc0xxx               | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 16        | 16.16%  |
| Lenovo Legion        | 5         | 5.05%   |
| ASUS ROG             | 5         | 5.05%   |
| Lenovo IdeaPad       | 4         | 4.04%   |
| Dell XPS             | 4         | 4.04%   |
| Lenovo Yoga          | 3         | 3.03%   |
| HP OMEN              | 3         | 3.03%   |
| HP Laptop            | 3         | 3.03%   |
| HP EliteBook         | 3         | 3.03%   |
| Dell Precision       | 3         | 3.03%   |
| Toshiba Satellite    | 2         | 2.02%   |
| Timi Mi              | 2         | 2.02%   |
| MSI GS63VR           | 2         | 2.02%   |
| Lenovo ThinkBook     | 2         | 2.02%   |
| HP Pavilion          | 2         | 2.02%   |
| Framework Laptop     | 2         | 2.02%   |
| Dell Latitude        | 2         | 2.02%   |
| Dell Inspiron        | 2         | 2.02%   |
| ASUS VivoBook        | 2         | 2.02%   |
| Acer Aspire          | 2         | 2.02%   |
| win element MoreFine | 1         | 1.01%   |
| TUXEDO InfinityBook  | 1         | 1.01%   |
| Toshiba NB100        | 1         | 1.01%   |
| Timi RedmiBook       | 1         | 1.01%   |
| Timi A35             | 1         | 1.01%   |
| System76 Gazelle     | 1         | 1.01%   |
| Samsung 700G7C       | 1         | 1.01%   |
| Razer Blade          | 1         | 1.01%   |
| Purism Librem        | 1         | 1.01%   |
| Notebook N141CU      | 1         | 1.01%   |
| MSI MS-7A34          | 1         | 1.01%   |
| MSI GE73             | 1         | 1.01%   |
| MSI GE66             | 1         | 1.01%   |
| Lenovo G510          | 1         | 1.01%   |
| IBM 2722BDG          | 1         | 1.01%   |
| HUAWEI HVY-WXX9      | 1         | 1.01%   |
| HUAWEI BOHB-WAX9     | 1         | 1.01%   |
| HP Victus            | 1         | 1.01%   |
| HP ProBook           | 1         | 1.01%   |
| Eluktronics MAX-17   | 1         | 1.01%   |
| Dell G5              | 1         | 1.01%   |
| Dell G3              | 1         | 1.01%   |
| BANGHO MAX           | 1         | 1.01%   |
| AVITA NS14A6         | 1         | 1.01%   |
| ASUS X555LJ          | 1         | 1.01%   |
| ASUS UX430UAR        | 1         | 1.01%   |
| ASUS ASUS            | 1         | 1.01%   |
| ASUS 1005HA          | 1         | 1.01%   |
| Acer Swift           | 1         | 1.01%   |
| Acer Nitro           | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 31        | 31.31%  |
| 2020 | 19        | 19.19%  |
| 2019 | 17        | 17.17%  |
| 2018 | 6         | 6.06%   |
| 2022 | 5         | 5.05%   |
| 2012 | 4         | 4.04%   |
| 2017 | 3         | 3.03%   |
| 2016 | 3         | 3.03%   |
| 2015 | 3         | 3.03%   |
| 2011 | 2         | 2.02%   |
| 2006 | 2         | 2.02%   |
| 2014 | 1         | 1.01%   |
| 2013 | 1         | 1.01%   |
| 2009 | 1         | 1.01%   |
| 2008 | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 99        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 97        | 97%     |
| Enabled  | 3         | 3%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 97.98%  |
| Yes  | 2         | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 25        | 25.25%  |
| 8.01-16.0   | 25        | 25.25%  |
| 32.01-64.0  | 18        | 18.18%  |
| 4.01-8.0    | 15        | 15.15%  |
| 64.01-256.0 | 6         | 6.06%   |
| 3.01-4.0    | 4         | 4.04%   |
| 2.01-3.0    | 3         | 3.03%   |
| 24.01-32.0  | 1         | 1.01%   |
| 1.01-2.0    | 1         | 1.01%   |
| 0.51-1.0    | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 26        | 24.76%  |
| 1.01-2.0  | 23        | 21.9%   |
| 3.01-4.0  | 19        | 18.1%   |
| 2.01-3.0  | 12        | 11.43%  |
| 8.01-16.0 | 12        | 11.43%  |
| 0.51-1.0  | 9         | 8.57%   |
| 0.01-0.5  | 4         | 3.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 71%     |
| 2      | 24        | 24%     |
| 3      | 4         | 4%      |
| 4      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 88.89%  |
| Yes       | 11        | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 67.68%  |
| No        | 32        | 32.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 98.99%  |
| No        | 1         | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 88.12%  |
| No        | 12        | 11.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 17%     |
| Germany     | 10        | 10%     |
| China       | 7         | 7%      |
| UK          | 6         | 6%      |
| Russia      | 6         | 6%      |
| France      | 6         | 6%      |
| Greece      | 4         | 4%      |
| Sweden      | 3         | 3%      |
| Poland      | 3         | 3%      |
| Belarus     | 3         | 3%      |
| Australia   | 3         | 3%      |
| Turkey      | 2         | 2%      |
| Switzerland | 2         | 2%      |
| Spain       | 2         | 2%      |
| Romania     | 2         | 2%      |
| Mexico      | 2         | 2%      |
| Italy       | 2         | 2%      |
| India       | 2         | 2%      |
| Hong Kong   | 2         | 2%      |
| Czechia     | 2         | 2%      |
| Argentina   | 2         | 2%      |
| Uruguay     | 1         | 1%      |
| Ukraine     | 1         | 1%      |
| Tunisia     | 1         | 1%      |
| Slovakia    | 1         | 1%      |
| Philippines | 1         | 1%      |
| Norway      | 1         | 1%      |
| New Zealand | 1         | 1%      |
| Netherlands | 1         | 1%      |
| Finland     | 1         | 1%      |
| Canada      | 1         | 1%      |
| Belgium     | 1         | 1%      |
| Austria     | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Minsk            | 3         | 2.91%   |
| Athens           | 3         | 2.91%   |
| Sydney           | 2         | 1.94%   |
| Sterling         | 2         | 1.94%   |
| Milan            | 2         | 1.94%   |
| Guangzhou        | 2         | 1.94%   |
| Foshan           | 2         | 1.94%   |
| Cieszyn          | 2         | 1.94%   |
| Cherry Hill      | 2         | 1.94%   |
| Central          | 2         | 1.94%   |
| Zacapu           | 1         | 0.97%   |
| Winston-Salem    | 1         | 0.97%   |
| West Orange      | 1         | 0.97%   |
| Vienna           | 1         | 0.97%   |
| Vantaa           | 1         | 0.97%   |
| Tunis            | 1         | 0.97%   |
| Trnava           | 1         | 0.97%   |
| Taby             | 1         | 0.97%   |
| Sundsvall        | 1         | 0.97%   |
| Storsteinnes     | 1         | 0.97%   |
| Shenzhen         | 1         | 0.97%   |
| Santa Rosa       | 1         | 0.97%   |
| Sacramento       | 1         | 0.97%   |
| Rostock          | 1         | 0.97%   |
| Ratingen         | 1         | 0.97%   |
| Québec          | 1         | 0.97%   |
| Punta Gorda      | 1         | 0.97%   |
| Pujaut           | 1         | 0.97%   |
| Prague           | 1         | 0.97%   |
| Postbauer-Heng   | 1         | 0.97%   |
| Perm             | 1         | 0.97%   |
| Paris            | 1         | 0.97%   |
| Orlando          | 1         | 0.97%   |
| Ocala            | 1         | 0.97%   |
| Nuremberg        | 1         | 0.97%   |
| Novosibirsk      | 1         | 0.97%   |
| Noisy-le-Sec     | 1         | 0.97%   |
| Nizhny Tagil     | 1         | 0.97%   |
| Nizhniy Novgorod | 1         | 0.97%   |
| New York         | 1         | 0.97%   |
| Neath            | 1         | 0.97%   |
| Munich           | 1         | 0.97%   |
| Motala           | 1         | 0.97%   |
| Moscow           | 1         | 0.97%   |
| Minden           | 1         | 0.97%   |
| Milton Keynes    | 1         | 0.97%   |
| Mexico City      | 1         | 0.97%   |
| Marseille        | 1         | 0.97%   |
| Marcoussis       | 1         | 0.97%   |
| London           | 1         | 0.97%   |
| Lochristi        | 1         | 0.97%   |
| Lincoln          | 1         | 0.97%   |
| Leidschendam     | 1         | 0.97%   |
| Kyiv             | 1         | 0.97%   |
| Kulmbach         | 1         | 0.97%   |
| Kallithea        | 1         | 0.97%   |
| Kailua-Kona      | 1         | 0.97%   |
| Hyderabad        | 1         | 0.97%   |
| Huangpu          | 1         | 0.97%   |
| Houston          | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 30     | 21.43%  |
| Samsung Electronics | 25        | 31     | 19.84%  |
| SK hynix            | 13        | 13     | 10.32%  |
| Intel               | 12        | 15     | 9.52%   |
| Seagate             | 8         | 9      | 6.35%   |
| SanDisk             | 8         | 9      | 6.35%   |
| Micron Technology   | 6         | 6      | 4.76%   |
| Toshiba             | 4         | 7      | 3.17%   |
| Crucial             | 4         | 5      | 3.17%   |
| KIOXIA-EXCERIA      | 2         | 4      | 1.59%   |
| Kingston            | 2         | 2      | 1.59%   |
| HGST                | 2         | 2      | 1.59%   |
| XrayDisk            | 1         | 1      | 0.79%   |
| Unknown             | 1         | 3      | 0.79%   |
| T-FORCE             | 1         | 1      | 0.79%   |
| Plextor             | 1         | 1      | 0.79%   |
| Phison              | 1         | 1      | 0.79%   |
| LITEON              | 1         | 1      | 0.79%   |
| KIOXIA              | 1         | 2      | 0.79%   |
| Hoodisk             | 1         | 1      | 0.79%   |
| Hitachi             | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |
| AMD                 | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel SSDPEKNW010T8 1TB                 | 4         | 3.1%    |
| Intel SSDPEKNU512GZ 512GB               | 3         | 2.33%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 1.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 1.55%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 1.55%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 1.55%   |
| Toshiba KXG6AZNV512G 512GB              | 2         | 1.55%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB  | 2         | 1.55%   |
| SK hynix PC711 NVMe 512GB               | 2         | 1.55%   |
| Samsung SSD 970 PRO 1TB                 | 2         | 1.55%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.55%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 1.55%   |
| Intel SSDPEKNW020T8 2TB                 | 2         | 1.55%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.55%   |
| XrayDisk SSD 128GB                      | 1         | 0.78%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.78%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.78%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.78%   |
| WDC WD3200LPVX-22V0TT0 320GB            | 1         | 0.78%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.78%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.78%   |
| WDC WD10SPSX-08A6W 1TB                  | 1         | 0.78%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1         | 0.78%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.78%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 0.78%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.78%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 0.78%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.78%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB    | 1         | 0.78%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.78%   |
| Toshiba MK6008GAH 64GB                  | 1         | 0.78%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD | 1         | 0.78%   |
| T-FORCE TM8FP5001T 1TB                  | 1         | 0.78%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 0.78%   |
| SK hynix PC711 NVMe 1TB                 | 1         | 0.78%   |
| SK hynix PC611 NVMe 512GB               | 1         | 0.78%   |
| SK hynix HFS128G39MNC-3510A 128GB SSD   | 1         | 0.78%   |
| SK hynix HFM512GDHTNG-8710B 512GB       | 1         | 0.78%   |
| SK hynix HFM512GD3JX016N 512GB          | 1         | 0.78%   |
| SK hynix HFM512GD3JX013N 512GB          | 1         | 0.78%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 0.78%   |
| SK hynix BC711 NVMe 512GB               | 1         | 0.78%   |
| Seagate ST2000LX001-1RG174 2TB          | 1         | 0.78%   |
| Seagate ST2000LM015-2E8174 2TB          | 1         | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.78%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.78%   |
| Seagate ST1000LM035-1RK1 1TB            | 1         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.78%   |
| Seagate FireCuda 530 ZP4000GM30013 4TB  | 1         | 0.78%   |
| Sandisk WD Black SN850 500GB            | 1         | 0.78%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 0.78%   |
| SanDisk SD9SN8W256G1002 256GB SSD       | 1         | 0.78%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 1         | 0.78%   |
| SanDisk SD8TN8U512G1001 512GB SSD       | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 8      | 36.84%  |
| Seagate | 7         | 8      | 36.84%  |
| HGST    | 2         | 2      | 10.53%  |
| Toshiba | 1         | 2      | 5.26%   |
| Hitachi | 1         | 1      | 5.26%   |
| Fujitsu | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 26.92%  |
| SanDisk             | 6         | 7      | 23.08%  |
| WDC                 | 3         | 4      | 11.54%  |
| Crucial             | 3         | 4      | 11.54%  |
| XrayDisk            | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Hoodisk             | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 72        | 92     | 62.07%  |
| SSD     | 24        | 32     | 20.69%  |
| HDD     | 19        | 22     | 16.38%  |
| Unknown | 1         | 3      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 72        | 92     | 64.29%  |
| SATA | 38        | 52     | 33.93%  |
| SAS  | 2         | 5      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 21        | 24     | 46.67%  |
| 0.01-0.5   | 21        | 27     | 46.67%  |
| 1.01-2.0   | 3         | 3      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 30        | 30%     |
| 501-1000       | 19        | 19%     |
| 101-250        | 18        | 18%     |
| 1001-2000      | 10        | 10%     |
| 1-20           | 6         | 6%      |
| Unknown        | 6         | 6%      |
| 2001-3000      | 5         | 5%      |
| 21-50          | 3         | 3%      |
| More than 3000 | 2         | 2%      |
| 51-100         | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 28        | 26.92%  |
| 21-50     | 18        | 17.31%  |
| 101-250   | 17        | 16.35%  |
| 251-500   | 12        | 11.54%  |
| 51-100    | 10        | 9.62%   |
| 1001-2000 | 7         | 6.73%   |
| 501-1000  | 6         | 5.77%   |
| Unknown   | 6         | 5.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVS-22RST0 160GB        | 1         | 1      | 9.09%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1         | 2      | 9.09%   |
| Toshiba MK6008GAH 64GB             | 1         | 2      | 9.09%   |
| Seagate ST1000LM049-2GH172 1TB     | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 2      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 9.09%   |
| Intel SSDPEKKF256G8L 256GB         | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB           | 1         | 1      | 9.09%   |
| Fujitsu MHW2040AT 40GB             | 1         | 1      | 9.09%   |
| Crucial CT1000P1SSD8 1TB           | 1         | 1      | 9.09%   |
| A-DATA Technology SP550 240GB SSD  | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 27.27%  |
| WDC               | 2         | 3      | 18.18%  |
| Toshiba           | 1         | 2      | 9.09%   |
| Intel             | 1         | 1      | 9.09%   |
| HGST              | 1         | 1      | 9.09%   |
| Fujitsu           | 1         | 1      | 9.09%   |
| Crucial           | 1         | 1      | 9.09%   |
| A-DATA Technology | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 37.5%   |
| WDC     | 2         | 3      | 25%     |
| Toshiba | 1         | 2      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 11     | 72.73%  |
| NVMe | 2         | 2      | 18.18%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Works    | 90        | 129    | 86.54%  |
| Malfunc  | 11        | 14     | 10.58%  |
| Detected | 3         | 6      | 2.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 52        | 37.41%  |
| SanDisk                      | 19        | 13.67%  |
| Samsung Electronics          | 19        | 13.67%  |
| AMD                          | 18        | 12.95%  |
| SK hynix                     | 12        | 8.63%   |
| Micron Technology            | 6         | 4.32%   |
| Toshiba America Info Systems | 3         | 2.16%   |
| Phison Electronics           | 3         | 2.16%   |
| KIOXIA                       | 2         | 1.44%   |
| Kingston Technology Company  | 2         | 1.44%   |
| Seagate Technology           | 1         | 0.72%   |
| Micron/Crucial Technology    | 1         | 0.72%   |
| Lite-On Technology           | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 11.89%  |
| SK hynix Gold P31 SSD                                                          | 10        | 6.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 6.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 4.9%    |
| Micron Non-Volatile memory controller                                          | 6         | 4.2%    |
| Intel SSD 660P Series                                                          | 6         | 4.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 4.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 3.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 2.8%    |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.1%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.1%    |
| Intel Non-Volatile memory controller                                           | 3         | 2.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.4%    |
| KIOXIA NVMe SSD                                                                | 2         | 1.4%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.4%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.7%    |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.7%    |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.7%    |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.7%    |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.7%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.7%    |
| Phison E7 NVMe Controller                                                      | 1         | 0.7%    |
| Phison E12 NVMe Controller                                                     | 1         | 0.7%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.7%    |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.7%    |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.7%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 0.7%    |
| AMD RAID Bottom Device                                                         | 1         | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 72        | 54.14%  |
| SATA | 51        | 38.35%  |
| RAID | 7         | 5.26%   |
| IDE  | 3         | 2.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 63.64%  |
| AMD    | 36        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 4.04%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 4.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 4.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 4.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 3.03%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 3         | 3.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 3.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 2.02%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 2.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 2.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.02%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.02%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.02%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.02%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 2.02%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 2         | 2.02%   |
| Intel Pentium M processor 1400MHz             | 1         | 1.01%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 1.01%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.01%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.01%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.01%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.01%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.01%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.01%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.01%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.01%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.01%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.01%   |
| Intel Core Duo CPU U2500 @ 1.20GHz            | 1         | 1.01%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 1.01%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 1.01%   |
| Intel 12th Gen Core i7-1280P                  | 1         | 1.01%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 1.01%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 1.01%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 1.01%   |
| AMD Ryzen 9 PRO 6950H with Radeon Graphics    | 1         | 1.01%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 1         | 1.01%   |
| AMD Ryzen 7 PRO 6850HS with Radeon Graphics   | 1         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.01%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 24        | 24.24%  |
| Intel Core i5   | 16        | 16.16%  |
| Other           | 15        | 15.15%  |
| AMD Ryzen 7     | 15        | 15.15%  |
| AMD Ryzen 5     | 7         | 7.07%   |
| AMD Ryzen 9     | 5         | 5.05%   |
| AMD Ryzen 7 PRO | 5         | 5.05%   |
| Intel Core i9   | 2         | 2.02%   |
| Intel Core i3   | 2         | 2.02%   |
| Intel Atom      | 2         | 2.02%   |
| AMD Ryzen 3     | 2         | 2.02%   |
| AMD E1          | 2         | 2.02%   |
| Intel Pentium M | 1         | 1.01%   |
| Intel Core Duo  | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 35        | 35.35%  |
| 8      | 29        | 29.29%  |
| 6      | 15        | 15.15%  |
| 2      | 15        | 15.15%  |
| 1      | 3         | 3.03%   |
| 14     | 1         | 1.01%   |
| 12     | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 92%     |
| 1      | 8         | 8%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 95.96%  |
| 32-bit         | 4         | 4.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 13        | 13%     |
| 0x906ea    | 11        | 11%     |
| Unknown    | 8         | 8%      |
| 0x806ec    | 7         | 7%      |
| 0x806d1    | 6         | 6%      |
| 0x806c1    | 5         | 5%      |
| 0x08608103 | 4         | 4%      |
| 0x08108109 | 4         | 4%      |
| 0xa0652    | 3         | 3%      |
| 0x506e3    | 3         | 3%      |
| 0x306d4    | 3         | 3%      |
| 0x08600106 | 3         | 3%      |
| 0x08600103 | 3         | 3%      |
| 0x906a3    | 2         | 2%      |
| 0x706e5    | 2         | 2%      |
| 0x306c3    | 2         | 2%      |
| 0x306a9    | 2         | 2%      |
| 0x206a7    | 2         | 2%      |
| 0x0a404102 | 2         | 2%      |
| 0x05000119 | 2         | 2%      |
| 0x906ed    | 1         | 1%      |
| 0x906e9    | 1         | 1%      |
| 0x806eb    | 1         | 1%      |
| 0x806ea    | 1         | 1%      |
| 0x806e9    | 1         | 1%      |
| 0x806c2    | 1         | 1%      |
| 0x6ec      | 1         | 1%      |
| 0x406e3    | 1         | 1%      |
| 0x0a404101 | 1         | 1%      |
| 0x08608102 | 1         | 1%      |
| 0x08600102 | 1         | 1%      |
| 0x08108102 | 1         | 1%      |
| 0x08001105 | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 25%     |
| Zen 3            | 13        | 13%     |
| IceLake          | 9         | 9%      |
| Unknown          | 9         | 9%      |
| Zen 2            | 7         | 7%      |
| TigerLake        | 7         | 7%      |
| Zen+             | 5         | 5%      |
| Skylake          | 4         | 4%      |
| CometLake        | 3         | 3%      |
| Broadwell        | 3         | 3%      |
| SandyBridge      | 2         | 2%      |
| P6               | 2         | 2%      |
| IvyBridge        | 2         | 2%      |
| Haswell          | 2         | 2%      |
| Bonnell          | 2         | 2%      |
| Bobcat           | 2         | 2%      |
| Alderlake Hybrid | 2         | 2%      |
| Zen              | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 42.11%  |
| Nvidia | 41        | 30.83%  |
| AMD    | 36        | 27.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                                   | 12        | 8.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 6.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 4.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 6         | 4.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 6         | 4.2%    |
| AMD Renoir                                                                    | 6         | 4.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 5         | 3.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 3.5%    |
| AMD Lucienne                                                                  | 5         | 3.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 2.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 2.1%    |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 2.1%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 2.1%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 3         | 2.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 2.1%    |
| Intel HD Graphics 5500                                                        | 3         | 2.1%    |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 2.1%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.4%    |
| Intel UHD Graphics 620                                                        | 2         | 1.4%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 1.4%    |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.4%    |
| Intel HD Graphics 630                                                         | 2         | 1.4%    |
| Intel HD Graphics 530                                                         | 2         | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.4%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 1.4%    |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 1.4%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.7%    |
| Nvidia TU117M                                                                 | 1         | 0.7%    |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.7%    |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                              | 1         | 0.7%    |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.7%    |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1         | 0.7%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.7%    |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M2000M]                                               | 1         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.7%    |
| Nvidia GF114M [GeForce GTX 675M]                                              | 1         | 0.7%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 0.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 0.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.7%    |
| Intel HD Graphics 620                                                         | 1         | 0.7%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 1         | 0.7%    |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 0.7%    |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                        | 1         | 0.7%    |
| AMD Navi 23 [Radeon RX 6650 XT]                                               | 1         | 0.7%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 1         | 0.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 0.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 1         | 0.7%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 28        | 28.28%  |
| 1 x Intel      | 24        | 24.24%  |
| 1 x AMD        | 23        | 23.23%  |
| 1 x Nvidia     | 8         | 8.08%   |
| 2 x AMD        | 7         | 7.07%   |
| AMD + Nvidia   | 5         | 5.05%   |
| 2 x Intel      | 3         | 3.03%   |
| Intel + AMD    | 1         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 71.72%  |
| Proprietary | 26        | 26.26%  |
| Unknown     | 2         | 2.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 48.51%  |
| 0.01-0.5   | 12        | 11.88%  |
| 3.01-4.0   | 11        | 10.89%  |
| 1.01-2.0   | 10        | 9.9%    |
| 0.51-1.0   | 6         | 5.94%   |
| 7.01-8.0   | 4         | 3.96%   |
| 5.01-6.0   | 4         | 3.96%   |
| 8.01-16.0  | 3         | 2.97%   |
| 2.01-3.0   | 2         | 1.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 23        | 20%     |
| AU Optronics            | 20        | 17.39%  |
| Samsung Electronics     | 15        | 13.04%  |
| Chimei Innolux          | 13        | 11.3%   |
| Sharp                   | 8         | 6.96%   |
| LG Display              | 8         | 6.96%   |
| Lenovo                  | 4         | 3.48%   |
| Goldstar                | 3         | 2.61%   |
| CSO                     | 3         | 2.61%   |
| PANDA                   | 2         | 1.74%   |
| Hewlett-Packard         | 2         | 1.74%   |
| Dell                    | 2         | 1.74%   |
| BenQ                    | 2         | 1.74%   |
| ASUSTek Computer        | 2         | 1.74%   |
| Xiaomi                  | 1         | 0.87%   |
| ViewSonic               | 1         | 0.87%   |
| MSI                     | 1         | 0.87%   |
| IOC                     | 1         | 0.87%   |
| InfoVision              | 1         | 0.87%   |
| HannStar                | 1         | 0.87%   |
| Chi Mei Optoelectronics | 1         | 0.87%   |
| AOC                     | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 2         | 1.74%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 2         | 1.74%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 2         | 1.74%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch        | 2         | 1.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.74%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 1.74%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.74%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                  | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.74%   |
| Xiaomi Mi TV XMD0002 1920x1080 708x398mm 32.0-inch                     | 1         | 0.87%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch            | 1         | 0.87%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.87%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.87%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.87%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.87%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.87%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch   | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4165 3840x2400 344x215mm 16.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 0.87%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.87%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 0.87%   |
| Samsung Electronics 173HT02-C01 SECD033 1920x1080 382x215mm 17.3-inch  | 1         | 0.87%   |
| PANDA LCD Monitor NCP0067 1920x1080 309x174mm 14.0-inch                | 1         | 0.87%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.87%   |
| MSI MAG272QP MSI3CA8 2560x1440 597x336mm 27.0-inch                     | 1         | 0.87%   |
| LG Display LCD Monitor LGD06DA 1920x1080 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD05BE 1920x1080 382x215mm 17.3-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 0.87%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                   | 1         | 0.87%   |
| Lenovo LEN T34w-20 LEN61F3 3440x1440 800x330mm 34.1-inch               | 1         | 0.87%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch               | 1         | 0.87%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| IOC 15A1F IOC1560 1920x1080 344x193mm 15.5-inch                        | 1         | 0.87%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch           | 1         | 0.87%   |
| Hewlett-Packard E273q HPN3473 2560x1440 597x336mm 27.0-inch            | 1         | 0.87%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch             | 1         | 0.87%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 1         | 0.87%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1         | 0.87%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                    | 1         | 0.87%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                  | 1         | 0.87%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 1         | 0.87%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                       | 1         | 0.87%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                  | 1         | 0.87%   |
| CSO LCD Monitor CSO1600 2560x1600 345x215mm 16.0-inch                  | 1         | 0.87%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                  | 1         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch       | 1         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch       | 1         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 52.34%  |
| 2560x1440 (QHD)    | 10        | 9.35%   |
| 3840x2160 (4K)     | 9         | 8.41%   |
| 1366x768 (WXGA)    | 9         | 8.41%   |
| 2560x1600          | 4         | 3.74%   |
| 1920x1200 (WUXGA)  | 4         | 3.74%   |
| 3840x2400          | 3         | 2.8%    |
| 3440x1440          | 2         | 1.87%   |
| 2256x1504          | 2         | 1.87%   |
| 1024x600           | 2         | 1.87%   |
| 3456x2160          | 1         | 0.93%   |
| 2880x1800          | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1600x900 (HD+)     | 1         | 0.93%   |
| 1440x900 (WXGA+)   | 1         | 0.93%   |
| 1280x1024 (SXGA)   | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 48        | 42.48%  |
| 14     | 15        | 13.27%  |
| 13     | 14        | 12.39%  |
| 17     | 9         | 7.96%   |
| 16     | 7         | 6.19%   |
| 27     | 6         | 5.31%   |
| 34     | 2         | 1.77%   |
| 24     | 2         | 1.77%   |
| 23     | 2         | 1.77%   |
| 65     | 1         | 0.88%   |
| 54     | 1         | 0.88%   |
| 25     | 1         | 0.88%   |
| 22     | 1         | 0.88%   |
| 18     | 1         | 0.88%   |
| 12     | 1         | 0.88%   |
| 10     | 1         | 0.88%   |
| 8      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 69.09%  |
| 501-600     | 10        | 9.09%   |
| 351-400     | 10        | 9.09%   |
| 201-300     | 7         | 6.36%   |
| 701-800     | 2         | 1.82%   |
| 401-500     | 2         | 1.82%   |
| 1001-1500   | 2         | 1.82%   |
| 101-200     | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 81        | 80.2%   |
| 16/10 | 15        | 14.85%  |
| 3/2   | 2         | 1.98%   |
| 21/9  | 2         | 1.98%   |
| 5/4   | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 43.36%  |
| 81-90          | 26        | 23.01%  |
| 121-130        | 8         | 7.08%   |
| 301-350        | 6         | 5.31%   |
| 111-120        | 6         | 5.31%   |
| 201-250        | 4         | 3.54%   |
| 71-80          | 3         | 2.65%   |
| More than 1000 | 2         | 1.77%   |
| 351-500        | 2         | 1.77%   |
| 251-300        | 2         | 1.77%   |
| 141-150        | 2         | 1.77%   |
| 61-70          | 1         | 0.88%   |
| 41-50          | 1         | 0.88%   |
| 1-40           | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 50.45%  |
| 161-240       | 15        | 13.51%  |
| 101-120       | 15        | 13.51%  |
| More than 240 | 13        | 11.71%  |
| 51-100        | 10        | 9.01%   |
| 1-50          | 2         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 80        | 80%     |
| 2     | 14        | 14%     |
| 3     | 3         | 3%      |
| 0     | 3         | 3%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 68        | 45.64%  |
| Realtek Semiconductor             | 47        | 31.54%  |
| Qualcomm Atheros                  | 9         | 6.04%   |
| MediaTek                          | 6         | 4.03%   |
| Broadcom                          | 3         | 2.01%   |
| Samsung Electronics               | 2         | 1.34%   |
| Qualcomm                          | 2         | 1.34%   |
| ASIX Electronics                  | 2         | 1.34%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.67%   |
| Sierra Wireless                   | 1         | 0.67%   |
| Shenzhen Goodix Technology        | 1         | 0.67%   |
| Lenovo                            | 1         | 0.67%   |
| ICS Advent                        | 1         | 0.67%   |
| Ericsson Business Mobile Networks | 1         | 0.67%   |
| Dell                              | 1         | 0.67%   |
| D-Link                            | 1         | 0.67%   |
| Broadcom Limited                  | 1         | 0.67%   |
| Aquantia                          | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 33        | 18.75%  |
| Intel Wi-Fi 6 AX200                                                     | 15        | 8.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 3.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.84%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 2.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 2.27%   |
| Intel Wireless 8260                                                     | 4         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 2.27%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.14%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.14%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                           | 2         | 1.14%   |
| ZTE WCDMA MSM ZTE Mobile Broadband Station                              | 1         | 0.57%   |
| Sierra Wireless EM7455                                                  | 1         | 0.57%   |
| Shenzhen Goodix Unknow device                                           | 1         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.57%   |
| MediaTek WLAN controller                                                | 1         | 0.57%   |
| Lenovo ThinkPad TBT 3 Dock                                              | 1         | 0.57%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.57%   |
| Intel Wireless 7265                                                     | 1         | 0.57%   |
| Intel Wireless 3160                                                     | 1         | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 0.57%   |
| Intel Ethernet Connection (5) I219-V                                    | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.57%   |
| Intel Ethernet Connection (16) I219-LM                                  | 1         | 0.57%   |
| Intel Ethernet Connection (14) I219-V                                   | 1         | 0.57%   |
| Intel Ethernet Connection (14) I219-LM                                  | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 65.35%  |
| Realtek Semiconductor | 16        | 15.84%  |
| MediaTek              | 6         | 5.94%   |
| Qualcomm Atheros      | 5         | 4.95%   |
| Qualcomm              | 2         | 1.98%   |
| Broadcom              | 2         | 1.98%   |
| Sierra Wireless       | 1         | 0.99%   |
| Dell                  | 1         | 0.99%   |
| D-Link                | 1         | 0.99%   |
| Broadcom Limited      | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 14.85%  |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 6.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 5.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 4.95%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 4.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 4.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 3.96%   |
| Intel Wireless 8260                                                     | 4         | 3.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.96%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.98%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.98%   |
| Sierra Wireless EM7455                                                  | 1         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| MediaTek WLAN controller                                                | 1         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.99%   |
| Intel Wireless 7265                                                     | 1         | 0.99%   |
| Intel Wireless 3160                                                     | 1         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.99%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 1         | 0.99%   |
| D-Link 802.11 n WLAN                                                    | 1         | 0.99%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.99%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 41        | 58.57%  |
| Intel                 | 16        | 22.86%  |
| Qualcomm Atheros      | 5         | 7.14%   |
| Samsung Electronics   | 2         | 2.86%   |
| ASIX Electronics      | 2         | 2.86%   |
| Lenovo                | 1         | 1.43%   |
| ICS Advent            | 1         | 1.43%   |
| Broadcom              | 1         | 1.43%   |
| Aquantia              | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 46.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.41%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.41%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.41%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.41%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.41%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.41%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 57.99%  |
| Ethernet | 67        | 39.64%  |
| Modem    | 3         | 1.78%   |
| Unknown  | 1         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 78.43%  |
| Ethernet | 22        | 21.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 58.59%  |
| 1     | 39        | 39.39%  |
| 3     | 2         | 2.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 76.7%   |
| Yes  | 24        | 23.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 67.42%  |
| Realtek Semiconductor | 11        | 12.36%  |
| IMC Networks          | 6         | 6.74%   |
| Foxconn / Hon Hai     | 3         | 3.37%   |
| Toshiba               | 2         | 2.25%   |
| USI                   | 1         | 1.12%   |
| Lite-On Technology    | 1         | 1.12%   |
| Hewlett-Packard       | 1         | 1.12%   |
| Foxconn International | 1         | 1.12%   |
| Broadcom              | 1         | 1.12%   |
| ASUSTek Computer      | 1         | 1.12%   |
| Apple                 | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 17        | 19.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 13        | 14.61%  |
| Intel AX200 Bluetooth                             | 13        | 14.61%  |
| Intel Bluetooth wireless interface                | 9         | 10.11%  |
| Realtek Bluetooth Radio                           | 7         | 7.87%   |
| Intel AX210 Bluetooth                             | 4         | 4.49%   |
| IMC Networks Wireless_Device                      | 4         | 4.49%   |
| Toshiba RT Bluetooth Radio                        | 2         | 2.25%   |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 2.25%   |
| Intel Bluetooth Device                            | 2         | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                 | 2         | 2.25%   |
| USI Bluetooth Device                              | 1         | 1.12%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 1.12%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 1.12%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.12%   |
| IMC Networks Bluetooth Device                     | 1         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.12%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 1.12%   |
| Broadcom HP Portable SoftSailing                  | 1         | 1.12%   |
| ASUS Broadcom Bluetooth 2.1                       | 1         | 1.12%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 63        | 47.73%  |
| AMD                                  | 37        | 28.03%  |
| Nvidia                               | 26        | 19.7%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.76%   |
| Razer USA                            | 1         | 0.76%   |
| Lenovo                               | 1         | 0.76%   |
| Kingston Technology                  | 1         | 0.76%   |
| Hewlett-Packard                      | 1         | 0.76%   |
| ACTIONS                              | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 18.86%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 12%     |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 6.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 3.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 3.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 2.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 2.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 2.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.71%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.71%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.71%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia Audio device                                                        | 2         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.14%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.14%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.14%   |
| Thesycon Systemsoftware & Consulting U90                                   | 1         | 0.57%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.57%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.57%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.57%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.57%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.57%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 0.57%   |
| Hewlett-Packard USB Audio                                                  | 1         | 0.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.57%   |
| ACTIONS EDIFIER M380                                                       | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 43.12%  |
| SK hynix            | 24        | 22.02%  |
| Micron Technology   | 12        | 11.01%  |
| Kingston            | 8         | 7.34%   |
| Crucial             | 5         | 4.59%   |
| Unknown             | 2         | 1.83%   |
| A-DATA Technology   | 2         | 1.83%   |
| Transcend           | 1         | 0.92%   |
| Timetec             | 1         | 0.92%   |
| Team                | 1         | 0.92%   |
| Ramaxel Technology  | 1         | 0.92%   |
| Patriot             | 1         | 0.92%   |
| Magnum Tech         | 1         | 0.92%   |
| G.Skill             | 1         | 0.92%   |
| Corsair             | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 4.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 3.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 2.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 2.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 2.68%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.79%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 1.79%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.79%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.79%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.79%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.89%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.89%   |
| Transcend RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.89%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.89%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM 4800MT/s                | 1         | 0.89%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.89%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.89%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.89%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.89%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM 6400MT/s              | 1         | 0.89%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.89%   |
| Samsung RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.89%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.89%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 0.89%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.89%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.89%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 0.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.89%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM 4800MT/s               | 1         | 0.89%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 1         | 0.89%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.89%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 0.89%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.89%   |
| Patriot RAM PSD416G24002S 16GB SODIMM DDR4 2667MT/s              | 1         | 0.89%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 0.89%   |
| Micron RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.89%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 0.89%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 71.72%  |
| DDR3    | 12        | 12.12%  |
| LPDDR4  | 4         | 4.04%   |
| LPDDR3  | 3         | 3.03%   |
| Unknown | 3         | 3.03%   |
| DDR5    | 2         | 2.02%   |
| DDR     | 2         | 2.02%   |
| SDRAM   | 1         | 1.01%   |
| DDR2    | 1         | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 87%     |
| Row Of Chips | 12        | 12%     |
| Chip         | 1         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 51.49%  |
| 16384 | 24        | 23.76%  |
| 4096  | 10        | 9.9%    |
| 32768 | 8         | 7.92%   |
| 2048  | 4         | 3.96%   |
| 1024  | 2         | 1.98%   |
| 512   | 1         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 41        | 40.2%   |
| 2667    | 27        | 26.47%  |
| 1600    | 10        | 9.8%    |
| 4800    | 5         | 4.9%    |
| 8400    | 3         | 2.94%   |
| 2133    | 3         | 2.94%   |
| 4267    | 2         | 1.96%   |
| 2400    | 2         | 1.96%   |
| 533     | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 6400    | 1         | 0.98%   |
| 2933    | 1         | 0.98%   |
| 1333    | 1         | 0.98%   |
| 1067    | 1         | 0.98%   |
| 667     | 1         | 0.98%   |

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
| IMC Networks                           | 18        | 23.08%  |
| Chicony Electronics                    | 18        | 23.08%  |
| Acer                                   | 8         | 10.26%  |
| Lite-On Technology                     | 6         | 7.69%   |
| Realtek Semiconductor                  | 5         | 6.41%   |
| Microdia                               | 5         | 6.41%   |
| Syntek                                 | 3         | 3.85%   |
| Sunplus Innovation Technology          | 3         | 3.85%   |
| Quanta                                 | 3         | 3.85%   |
| Luxvisions Innotech Limited            | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.56%   |
| Sonix Technology                       | 1         | 1.28%   |
| Samsung Electronics                    | 1         | 1.28%   |
| DigiTech                               | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                               | 10        | 12.66%  |
| Chicony Integrated Camera                                    | 6         | 7.59%   |
| Microdia Integrated_Webcam_HD                                | 5         | 6.33%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 5         | 6.33%   |
| Acer Integrated Camera                                       | 5         | 6.33%   |
| Syntek Integrated Camera                                     | 2         | 2.53%   |
| Sunplus Integrated_Webcam_HD                                 | 2         | 2.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 2         | 2.53%   |
| Lite-On TOSHIBA Web Camera - HD                              | 2         | 2.53%   |
| Lite-On HP Wide Vision HD Camera                             | 2         | 2.53%   |
| Chicony USB2.0 Camera                                        | 2         | 2.53%   |
| Chicony HD User Facing                                       | 2         | 2.53%   |
| Acer NEC HD WebCam                                           | 2         | 2.53%   |
| Syntek Lenovo EasyCamera                                     | 1         | 1.27%   |
| Sunplus HP Wide Vision HD                                    | 1         | 1.27%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 1.27%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 1.27%   |
| Realtek USB Camera                                           | 1         | 1.27%   |
| Realtek Laptop Camera                                        | 1         | 1.27%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 1.27%   |
| Realtek Integrated Webcam HD                                 | 1         | 1.27%   |
| Realtek Integrated Camera                                    | 1         | 1.27%   |
| Quanta HP Wide Vision HD Camera                              | 1         | 1.27%   |
| Quanta HD Webcam                                             | 1         | 1.27%   |
| Quanta HD Camera                                             | 1         | 1.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 1         | 1.27%   |
| Lite-On Integrated Camera                                    | 1         | 1.27%   |
| Lite-On HP Webcam                                            | 1         | 1.27%   |
| IMC Networks XiaoMi Webcam                                   | 1         | 1.27%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                          | 1         | 1.27%   |
| IMC Networks Lenovo EasyCamera                               | 1         | 1.27%   |
| IMC Networks Integrated IR Camera                            | 1         | 1.27%   |
| DigiTech SC-20FHL11146M                                      | 1         | 1.27%   |
| Chicony XiaoMi USB 2.0 Webcam                                | 1         | 1.27%   |
| Chicony USB 2.0 Camera                                       | 1         | 1.27%   |
| Chicony Integrated HP HD Webcam                              | 1         | 1.27%   |
| Chicony HP Truevision HD                                     | 1         | 1.27%   |
| Chicony HP HD Camera                                         | 1         | 1.27%   |
| Chicony HP 5MP Camera                                        | 1         | 1.27%   |
| Chicony HD Webcam                                            | 1         | 1.27%   |
| Chicony CNF8029                                              | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 1         | 1.27%   |
| Alcor Micro 720P USB Webcam                                  | 1         | 1.27%   |
| Acer HD Webcam                                               | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Validity Sensors           | 4         | 28.57%  |
| Elan Microelectronics      | 4         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 21.43%  |
| Elan ELAN:Fingerprint                             | 3         | 21.43%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                   | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                  | 1         | 7.14%   |
| Unknown                                           | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 50%     |
| Alcor Micro | 3         | 37.5%   |
| O2 Micro    | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 58200                      | 3         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader | 3         | 37.5%   |
| O2 Micro Oz776 SmartCard Reader     | 1         | 12.5%   |
| Broadcom 5880                       | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 44        | 43.56%  |
| 1     | 26        | 25.74%  |
| 2     | 14        | 13.86%  |
| 3     | 8         | 7.92%   |
| 4     | 6         | 5.94%   |
| 7     | 1         | 0.99%   |
| 6     | 1         | 0.99%   |
| 5     | 1         | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Bluetooth                | 15        | 13.16%  |
| Fingerprint reader       | 14        | 12.28%  |
| Camera                   | 14        | 12.28%  |
| Graphics card            | 13        | 11.4%   |
| Communication controller | 12        | 10.53%  |
| Net/wireless             | 11        | 9.65%   |
| Multimedia controller    | 9         | 7.89%   |
| Chipcard                 | 7         | 6.14%   |
| Card reader              | 5         | 4.39%   |
| Sound                    | 4         | 3.51%   |
| Network                  | 4         | 3.51%   |
| Modem                    | 2         | 1.75%   |
| Firewire controller      | 2         | 1.75%   |
| Storage/ata              | 1         | 0.88%   |
| Net/ethernet             | 1         | 0.88%   |

