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

Total: 169

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| Sony          | PCG-GRT230(UC)              | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| System76      | Gazelle Professional        | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Timi          | TM1604                      | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
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
| 5.15.59-gentoo-x86_64                           | 6         | 4.65%   |
| 5.15.52-gentoo                                  | 5         | 3.88%   |
| 5.19.0-gentoo-x86_64                            | 4         | 3.1%    |
| 5.15.59-gentoo                                  | 3         | 2.33%   |
| 5.15.41-gentoo-x86_64                           | 3         | 2.33%   |
| 5.14.9-gentoo-x86_64                            | 3         | 2.33%   |
| 5.18.7-gentoo                                   | 2         | 1.55%   |
| 5.18.4-gentoo                                   | 2         | 1.55%   |
| 5.18.1-gentoo-r2                                | 2         | 1.55%   |
| 5.17.1-gentoo-r1                                | 2         | 1.55%   |
| 5.16.0-gentoo-x86_64                            | 2         | 1.55%   |
| 5.15.68-gentoo-x86_64                           | 2         | 1.55%   |
| 5.15.52-gentoo-x86_64                           | 2         | 1.55%   |
| 5.15.41-gentoo-dist                             | 2         | 1.55%   |
| 5.15.10-gentoo-x86_64                           | 2         | 1.55%   |
| 5.19.8-gentoo-x86_64                            | 1         | 0.78%   |
| 5.19.6-gentoo-dell-gentoid                      | 1         | 0.78%   |
| 5.19.4-gentoo-dist                              | 1         | 0.78%   |
| 5.19.3-gentoo-x86_64                            | 1         | 0.78%   |
| 5.19.11-gentoo-x86_64                           | 1         | 0.78%   |
| 5.19.10-gentoo                                  | 1         | 0.78%   |
| 5.19.0-xanmod1-elitebook                        | 1         | 0.78%   |
| 5.19.0-rc2-p+                                   | 1         | 0.78%   |
| 5.19.0-gentoo                                   | 1         | 0.78%   |
| 5.18.9-gentoo                                   | 1         | 0.78%   |
| 5.18.8-gentoo-dist                              | 1         | 0.78%   |
| 5.18.8-gentoo                                   | 1         | 0.78%   |
| 5.18.6-gentoo-venus                             | 1         | 0.78%   |
| 5.18.5-gentoo                                   | 1         | 0.78%   |
| 5.18.19-gentoo-r1                               | 1         | 0.78%   |
| 5.18.16-arch1-1                                 | 1         | 0.78%   |
| 5.18.15-gentoo-dist                             | 1         | 0.78%   |
| 5.18.10-k08                                     | 1         | 0.78%   |
| 5.18.1-gentoo-r1-x86_64                         | 1         | 0.78%   |
| 5.18.1-gentoo-r1                                | 1         | 0.78%   |
| 5.18.0-rc7-x86_64-git-00119-gb015dcd62b86-dirty | 1         | 0.78%   |
| 5.18.0-gbfc780ef1ca0                            | 1         | 0.78%   |
| 5.18.0-g95ff72a6c129                            | 1         | 0.78%   |
| 5.17.9-gentoo-x86_64                            | 1         | 0.78%   |
| 5.17.9-gentoo-x86                               | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.59 | 12        | 9.38%   |
| 5.15.52 | 10        | 7.81%   |
| 5.19.0  | 7         | 5.47%   |
| 5.16.0  | 7         | 5.47%   |
| 5.15.41 | 6         | 4.69%   |
| 5.18.1  | 4         | 3.13%   |
| 5.14.9  | 4         | 3.13%   |
| 5.17.9  | 3         | 2.34%   |
| 5.15.5  | 3         | 2.34%   |
| 5.18.8  | 2         | 1.56%   |
| 5.18.7  | 2         | 1.56%   |
| 5.18.4  | 2         | 1.56%   |
| 5.18.0  | 2         | 1.56%   |
| 5.17.8  | 2         | 1.56%   |
| 5.17.1  | 2         | 1.56%   |
| 5.16.2  | 2         | 1.56%   |
| 5.16.14 | 2         | 1.56%   |
| 5.16.10 | 2         | 1.56%   |
| 5.16.1  | 2         | 1.56%   |
| 5.15.69 | 2         | 1.56%   |
| 5.15.68 | 2         | 1.56%   |
| 5.15.33 | 2         | 1.56%   |
| 5.15.13 | 2         | 1.56%   |
| 5.15.10 | 2         | 1.56%   |
| 5.14.14 | 2         | 1.56%   |
| 5.19.8  | 1         | 0.78%   |
| 5.19.6  | 1         | 0.78%   |
| 5.19.4  | 1         | 0.78%   |
| 5.19.3  | 1         | 0.78%   |
| 5.19.11 | 1         | 0.78%   |
| 5.19.10 | 1         | 0.78%   |
| 5.18.9  | 1         | 0.78%   |
| 5.18.6  | 1         | 0.78%   |
| 5.18.5  | 1         | 0.78%   |
| 5.18.19 | 1         | 0.78%   |
| 5.18.16 | 1         | 0.78%   |
| 5.18.15 | 1         | 0.78%   |
| 5.18.10 | 1         | 0.78%   |
| 5.17.7  | 1         | 0.78%   |
| 5.17.6  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 50        | 40.32%  |
| 5.18    | 18        | 14.52%  |
| 5.16    | 18        | 14.52%  |
| 5.17    | 14        | 11.29%  |
| 5.19    | 13        | 10.48%  |
| 5.14    | 7         | 5.65%   |
| 5.10    | 4         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 110       | 94.02%  |
| i686   | 7         | 5.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 44        | 37.29%  |
| KDE5     | 36        | 30.51%  |
| GNOME    | 16        | 13.56%  |
| XFCE     | 10        | 8.47%   |
| LXQt     | 3         | 2.54%   |
| sway     | 2         | 1.69%   |
| DWM      | 2         | 1.69%   |
| xmonad   | 1         | 0.85%   |
| MATE     | 1         | 0.85%   |
| LeftWM   | 1         | 0.85%   |
| fvwm     | 1         | 0.85%   |
| Cinnamon | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 45%     |
| Wayland | 25        | 20.83%  |
| Tty     | 21        | 17.5%   |
| Unknown | 20        | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 46        | 38.98%  |
| SDDM    | 41        | 34.75%  |
| LightDM | 14        | 11.86%  |
| GDM     | 9         | 7.63%   |
| LXDM    | 3         | 2.54%   |
| XDM     | 2         | 1.69%   |
| SLiM    | 2         | 1.69%   |
| GREETD  | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 54        | 46.15%  |
| C.UTF8     | 15        | 12.82%  |
| en_GB      | 9         | 7.69%   |
| Unknown    | 9         | 7.69%   |
| C          | 6         | 5.13%   |
| de_DE      | 5         | 4.27%   |
| ru_RU      | 3         | 2.56%   |
| it_IT      | 2         | 1.71%   |
| es_AR      | 2         | 1.71%   |
| en_AU      | 2         | 1.71%   |
| zh_CN      | 1         | 0.85%   |
| tr_TR      | 1         | 0.85%   |
| pt_BR      | 1         | 0.85%   |
| fr_FR      | 1         | 0.85%   |
| fr_CA      | 1         | 0.85%   |
| es_MX      | 1         | 0.85%   |
| en_US.UTF8 | 1         | 0.85%   |
| en_NZ      | 1         | 0.85%   |
| el_GR      | 1         | 0.85%   |
| de_CH      | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 103       | 87.29%  |
| BIOS | 15        | 12.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 68        | 58.12%  |
| Btrfs    | 35        | 29.91%  |
| Zfs      | 6         | 5.13%   |
| XXXXXXX  | 5         | 4.27%   |
| Overlay  | 1         | 0.85%   |
| F2fs     | 1         | 0.85%   |
| Bcachefs | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 105       | 89.74%  |
| MBR  | 12        | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 77.5%   |
| Yes       | 27        | 22.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 78.81%  |
| Yes       | 25        | 21.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 35        | 29.91%  |
| Hewlett-Packard                | 17        | 14.53%  |
| Dell                           | 15        | 12.82%  |
| ASUSTek Computer               | 12        | 10.26%  |
| Timi                           | 5         | 4.27%   |
| MSI                            | 5         | 4.27%   |
| Acer                           | 5         | 4.27%   |
| Toshiba                        | 3         | 2.56%   |
| HUAWEI                         | 3         | 2.56%   |
| win element                    | 2         | 1.71%   |
| System76                       | 2         | 1.71%   |
| Framework                      | 2         | 1.71%   |
| TUXEDO                         | 1         | 0.85%   |
| Sony                           | 1         | 0.85%   |
| Samsung Electronics            | 1         | 0.85%   |
| Razer                          | 1         | 0.85%   |
| Purism                         | 1         | 0.85%   |
| Notebook                       | 1         | 0.85%   |
| Matsushita Electric Industrial | 1         | 0.85%   |
| IBM                            | 1         | 0.85%   |
| Eluktronics                    | 1         | 0.85%   |
| BANGHO                         | 1         | 0.85%   |
| AVITA                          | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| win element MoreFine S500+                  | 2         | 1.71%   |
| Toshiba Satellite C850D-118                 | 2         | 1.71%   |
| MSI GS63VR 6RF                              | 2         | 1.71%   |
| Lenovo ThinkPad E15 Gen 2 20T8000MPB        | 2         | 1.71%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ            | 2         | 1.71%   |
| HP Laptop 15s-eq0xxx                        | 2         | 1.71%   |
| HP Laptop 14-dk1xxx                         | 2         | 1.71%   |
| Framework Laptop                            | 2         | 1.71%   |
| Dell XPS 15 9570                            | 2         | 1.71%   |
| ASUS ROG Strix G513QY_G513QY                | 2         | 1.71%   |
| TUXEDO InfinityBook Pro 14 Gen6             | 1         | 0.85%   |
| Toshiba NB100                               | 1         | 0.85%   |
| Timi TM1604                                 | 1         | 0.85%   |
| Timi RedmiBook 13                           | 1         | 0.85%   |
| Timi Mi Laptop Pro 15 2020                  | 1         | 0.85%   |
| Timi Mi Laptop Pro 15                       | 1         | 0.85%   |
| Timi A35                                    | 1         | 0.85%   |
| System76 Gazelle Professional               | 1         | 0.85%   |
| System76 Gazelle                            | 1         | 0.85%   |
| Sony PCG-GRT230(UC)                         | 1         | 0.85%   |
| Samsung 700G7C                              | 1         | 0.85%   |
| Razer Blade 15 Studio Edition - Late 2019   | 1         | 0.85%   |
| Purism Librem 15 v4                         | 1         | 0.85%   |
| Notebook N141CU                             | 1         | 0.85%   |
| MSI MS-7A34                                 | 1         | 0.85%   |
| MSI GE73 Raider RGB 8RF                     | 1         | 0.85%   |
| MSI GE66 Raider 11UE                        | 1         | 0.85%   |
| Matsushita Electric Industrial CF-29LTQGZBM | 1         | 0.85%   |
| Lenovo Yoga Slim 7 14IIL05 82A1             | 1         | 0.85%   |
| Lenovo Yoga S940-14IWL 81Q7                 | 1         | 0.85%   |
| Lenovo Yoga S740-14IIL 81RS                 | 1         | 0.85%   |
| Lenovo ThinkPad Z16 Gen 1 21D4002GGE        | 1         | 0.85%   |
| Lenovo ThinkPad X220 4291QT1                | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD0039RI    | 1         | 0.85%   |
| Lenovo ThinkPad T470p 20J7S06Q00            | 1         | 0.85%   |
| Lenovo ThinkPad T460 20FMS421US             | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 3 21AH0093CK        | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 2a 20XK002SCK       | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 2a 20XK000YRI       | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 1 20S1S35Y00        | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 20        | 17.09%  |
| HP Laptop                                   | 6         | 5.13%   |
| Lenovo Legion                               | 5         | 4.27%   |
| ASUS ROG                                    | 5         | 4.27%   |
| Lenovo IdeaPad                              | 4         | 3.42%   |
| HP EliteBook                                | 4         | 3.42%   |
| Dell XPS                                    | 4         | 3.42%   |
| Lenovo Yoga                                 | 3         | 2.56%   |
| HP OMEN                                     | 3         | 2.56%   |
| Dell Precision                              | 3         | 2.56%   |
| Dell Latitude                               | 3         | 2.56%   |
| win element MoreFine                        | 2         | 1.71%   |
| Toshiba Satellite                           | 2         | 1.71%   |
| Timi Mi                                     | 2         | 1.71%   |
| System76 Gazelle                            | 2         | 1.71%   |
| MSI GS63VR                                  | 2         | 1.71%   |
| Lenovo ThinkBook                            | 2         | 1.71%   |
| HP Pavilion                                 | 2         | 1.71%   |
| Framework Laptop                            | 2         | 1.71%   |
| Dell Inspiron                               | 2         | 1.71%   |
| ASUS VivoBook                               | 2         | 1.71%   |
| Acer Swift                                  | 2         | 1.71%   |
| Acer Aspire                                 | 2         | 1.71%   |
| TUXEDO InfinityBook                         | 1         | 0.85%   |
| Toshiba NB100                               | 1         | 0.85%   |
| Timi TM1604                                 | 1         | 0.85%   |
| Timi RedmiBook                              | 1         | 0.85%   |
| Timi A35                                    | 1         | 0.85%   |
| Sony PCG-GRT230(UC)                         | 1         | 0.85%   |
| Samsung 700G7C                              | 1         | 0.85%   |
| Razer Blade                                 | 1         | 0.85%   |
| Purism Librem                               | 1         | 0.85%   |
| Notebook N141CU                             | 1         | 0.85%   |
| MSI MS-7A34                                 | 1         | 0.85%   |
| MSI GE73                                    | 1         | 0.85%   |
| MSI GE66                                    | 1         | 0.85%   |
| Matsushita Electric Industrial CF-29LTQGZBM | 1         | 0.85%   |
| Lenovo G510                                 | 1         | 0.85%   |
| IBM 2722BDG                                 | 1         | 0.85%   |
| HUAWEI KLVL-WXX9                            | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 33        | 28.21%  |
| 2020 | 22        | 18.8%   |
| 2019 | 21        | 17.95%  |
| 2018 | 8         | 6.84%   |
| 2022 | 7         | 5.98%   |
| 2012 | 5         | 4.27%   |
| 2017 | 4         | 3.42%   |
| 2016 | 3         | 2.56%   |
| 2015 | 3         | 2.56%   |
| 2006 | 3         | 2.56%   |
| 2011 | 2         | 1.71%   |
| 2014 | 1         | 0.85%   |
| 2013 | 1         | 0.85%   |
| 2009 | 1         | 0.85%   |
| 2008 | 1         | 0.85%   |
| 2005 | 1         | 0.85%   |
| 2003 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 117       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 115       | 97.46%  |
| Enabled  | 3         | 2.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 98.29%  |
| Yes  | 2         | 1.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 24.79%  |
| 16.01-24.0  | 27        | 23.08%  |
| 32.01-64.0  | 20        | 17.09%  |
| 4.01-8.0    | 19        | 16.24%  |
| 64.01-256.0 | 7         | 5.98%   |
| 3.01-4.0    | 4         | 3.42%   |
| 24.01-32.0  | 3         | 2.56%   |
| 2.01-3.0    | 3         | 2.56%   |
| 1.01-2.0    | 2         | 1.71%   |
| 0.51-1.0    | 2         | 1.71%   |
| 0.01-0.5    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 27        | 21.95%  |
| 4.01-8.0   | 26        | 21.14%  |
| 3.01-4.0   | 21        | 17.07%  |
| 2.01-3.0   | 15        | 12.2%   |
| 8.01-16.0  | 13        | 10.57%  |
| 0.51-1.0   | 11        | 8.94%   |
| 0.01-0.5   | 9         | 7.32%   |
| 32.01-64.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 72.03%  |
| 2      | 27        | 22.88%  |
| 3      | 5         | 4.24%   |
| 4      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 88.89%  |
| Yes       | 13        | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 69.23%  |
| No        | 36        | 30.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 98.29%  |
| No        | 2         | 1.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 84.03%  |
| No        | 19        | 15.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 22        | 18.64%  |
| Germany     | 13        | 11.02%  |
| China       | 9         | 7.63%   |
| Russia      | 7         | 5.93%   |
| France      | 7         | 5.93%   |
| UK          | 6         | 5.08%   |
| Poland      | 4         | 3.39%   |
| Greece      | 4         | 3.39%   |
| Sweden      | 3         | 2.54%   |
| Mexico      | 3         | 2.54%   |
| Czechia     | 3         | 2.54%   |
| Belarus     | 3         | 2.54%   |
| Australia   | 3         | 2.54%   |
| Turkey      | 2         | 1.69%   |
| Switzerland | 2         | 1.69%   |
| Spain       | 2         | 1.69%   |
| Romania     | 2         | 1.69%   |
| Norway      | 2         | 1.69%   |
| Italy       | 2         | 1.69%   |
| India       | 2         | 1.69%   |
| Hong Kong   | 2         | 1.69%   |
| Canada      | 2         | 1.69%   |
| Argentina   | 2         | 1.69%   |
| Uruguay     | 1         | 0.85%   |
| Ukraine     | 1         | 0.85%   |
| Tunisia     | 1         | 0.85%   |
| Slovakia    | 1         | 0.85%   |
| Philippines | 1         | 0.85%   |
| New Zealand | 1         | 0.85%   |
| Netherlands | 1         | 0.85%   |
| Finland     | 1         | 0.85%   |
| Brazil      | 1         | 0.85%   |
| Belgium     | 1         | 0.85%   |
| Austria     | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Minsk                | 3         | 2.48%   |
| Cieszyn              | 3         | 2.48%   |
| Berlin               | 3         | 2.48%   |
| Athens               | 3         | 2.48%   |
| Weatherford          | 2         | 1.65%   |
| Sydney               | 2         | 1.65%   |
| Sterling             | 2         | 1.65%   |
| Prague               | 2         | 1.65%   |
| Moscow               | 2         | 1.65%   |
| Milan                | 2         | 1.65%   |
| Mexico City          | 2         | 1.65%   |
| Lincoln              | 2         | 1.65%   |
| Hangzhou             | 2         | 1.65%   |
| Guangzhou            | 2         | 1.65%   |
| Grasse               | 2         | 1.65%   |
| Foshan               | 2         | 1.65%   |
| Cherry Hill          | 2         | 1.65%   |
| Central              | 2         | 1.65%   |
| Zacapu               | 1         | 0.83%   |
| Winston-Salem        | 1         | 0.83%   |
| West Orange          | 1         | 0.83%   |
| Vienna               | 1         | 0.83%   |
| Vantaa               | 1         | 0.83%   |
| Tunis                | 1         | 0.83%   |
| Trnava               | 1         | 0.83%   |
| Taby                 | 1         | 0.83%   |
| Sundsvall            | 1         | 0.83%   |
| Storsteinnes         | 1         | 0.83%   |
| Shenzhen             | 1         | 0.83%   |
| Santa Rosa           | 1         | 0.83%   |
| Sacramento           | 1         | 0.83%   |
| Røyken Municipality | 1         | 0.83%   |
| Rostock              | 1         | 0.83%   |
| Ratingen             | 1         | 0.83%   |
| Québec              | 1         | 0.83%   |
| Punta Gorda          | 1         | 0.83%   |
| Pujaut               | 1         | 0.83%   |
| Postbauer-Heng       | 1         | 0.83%   |
| Perm                 | 1         | 0.83%   |
| Paris                | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 33     | 20.41%  |
| Samsung Electronics | 28        | 36     | 19.05%  |
| SK hynix            | 13        | 13     | 8.84%   |
| Intel               | 13        | 16     | 8.84%   |
| SanDisk             | 10        | 11     | 6.8%    |
| Seagate             | 8         | 9      | 5.44%   |
| Micron Technology   | 6         | 6      | 4.08%   |
| Crucial             | 5         | 6      | 3.4%    |
| Toshiba             | 4         | 7      | 2.72%   |
| Kingston            | 4         | 4      | 2.72%   |
| A-DATA Technology   | 3         | 3      | 2.04%   |
| Unknown             | 2         | 4      | 1.36%   |
| KIOXIA-EXCERIA      | 2         | 4      | 1.36%   |
| KIOXIA              | 2         | 3      | 1.36%   |
| Hitachi             | 2         | 2      | 1.36%   |
| HGST                | 2         | 2      | 1.36%   |
| Zheino              | 1         | 1      | 0.68%   |
| XrayDisk            | 1         | 1      | 0.68%   |
| UMIS                | 1         | 1      | 0.68%   |
| T-FORCE             | 1         | 1      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| Phison Electronics  | 1         | 1      | 0.68%   |
| Phison              | 1         | 1      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| IBM/Hitachi         | 1         | 1      | 0.68%   |
| Hoodisk             | 1         | 1      | 0.68%   |
| Fujitsu             | 1         | 1      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |
| AMD                 | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel SSDPEKNW010T8 1TB                 | 4         | 2.65%   |
| Intel SSDPEKNU512GZ 512GB               | 3         | 1.99%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 1.32%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 2         | 1.32%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 1.32%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB    | 2         | 1.32%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 1.32%   |
| Toshiba KXG6AZNV512G 512GB              | 2         | 1.32%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB  | 2         | 1.32%   |
| SK hynix PC711 NVMe 512GB               | 2         | 1.32%   |
| SanDisk NVMe SSD Drive 500GB            | 2         | 1.32%   |
| Samsung SSD 970 PRO 1TB                 | 2         | 1.32%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.32%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 1.32%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 1.32%   |
| Intel SSDPEKNW020T8 2TB                 | 2         | 1.32%   |
| HGST HTS721010A9E630 1TB                | 2         | 1.32%   |
| Zheino CHN-mSATAQ3-120 120GB SSD        | 1         | 0.66%   |
| XrayDisk SSD 128GB                      | 1         | 0.66%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.66%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.66%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.66%   |
| WDC WD3200LPVX-22V0TT0 320GB            | 1         | 0.66%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 0.66%   |
| WDC WD10SPZX-75Z10T2 1TB                | 1         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.66%   |
| WDC WD10SPSX-08A6W 1TB                  | 1         | 0.66%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1         | 0.66%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.66%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 0.66%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.66%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 0.66%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.66%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB    | 1         | 0.66%   |
| Unknown USB DISK 3.2 250GB              | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 8         | 9      | 36.36%  |
| Seagate     | 7         | 8      | 31.82%  |
| Hitachi     | 2         | 2      | 9.09%   |
| HGST        | 2         | 2      | 9.09%   |
| Toshiba     | 1         | 2      | 4.55%   |
| IBM/Hitachi | 1         | 1      | 4.55%   |
| Fujitsu     | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 24.24%  |
| SanDisk             | 6         | 7      | 18.18%  |
| Crucial             | 4         | 5      | 12.12%  |
| WDC                 | 3         | 4      | 9.09%   |
| A-DATA Technology   | 3         | 3      | 9.09%   |
| Kingston            | 2         | 2      | 6.06%   |
| Zheino              | 1         | 1      | 3.03%   |
| XrayDisk            | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Plextor             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Hoodisk             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 82        | 104    | 59.85%  |
| SSD     | 31        | 39     | 22.63%  |
| HDD     | 22        | 25     | 16.06%  |
| MMC     | 1         | 1      | 0.73%   |
| Unknown | 1         | 3      | 0.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 82        | 104    | 62.12%  |
| SATA | 47        | 62     | 35.61%  |
| SAS  | 2         | 5      | 1.52%   |
| MMC  | 1         | 1      | 0.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 35     | 52.73%  |
| 0.51-1.0   | 22        | 25     | 40%     |
| 1.01-2.0   | 4         | 4      | 7.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 36        | 30.51%  |
| 101-250        | 22        | 18.64%  |
| 501-1000       | 20        | 16.95%  |
| 1001-2000      | 11        | 9.32%   |
| 1-20           | 7         | 5.93%   |
| Unknown        | 7         | 5.93%   |
| 2001-3000      | 6         | 5.08%   |
| 21-50          | 5         | 4.24%   |
| More than 3000 | 2         | 1.69%   |
| 51-100         | 2         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 35        | 28.69%  |
| 21-50     | 21        | 17.21%  |
| 101-250   | 17        | 13.93%  |
| 251-500   | 15        | 12.3%   |
| 51-100    | 13        | 10.66%  |
| 1001-2000 | 7         | 5.74%   |
| 501-1000  | 7         | 5.74%   |
| Unknown   | 7         | 5.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 2         | 2      | 14.29%  |
| WDC WD1600BEVS-22RST0 160GB                  | 1         | 1      | 7.14%   |
| WDC WD10EZEX-08M2NA0 1TB                     | 1         | 2      | 7.14%   |
| Toshiba MK6008GAH 64GB                       | 1         | 2      | 7.14%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 2      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 7.14%   |
| Intel SSDPEKKF256G8L 256GB                   | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 7.14%   |
| Fujitsu MHW2040AT 40GB                       | 1         | 1      | 7.14%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 7.14%   |
| A-DATA Technology SP550 240GB SSD            | 1         | 1      | 7.14%   |
| A-DATA Technology AXNS381E-256GM-B 256GB SSD | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 21.43%  |
| WDC               | 2         | 3      | 14.29%  |
| Kingston          | 2         | 2      | 14.29%  |
| A-DATA Technology | 2         | 2      | 14.29%  |
| Toshiba           | 1         | 2      | 7.14%   |
| Intel             | 1         | 1      | 7.14%   |
| HGST              | 1         | 1      | 7.14%   |
| Fujitsu           | 1         | 1      | 7.14%   |
| Crucial           | 1         | 1      | 7.14%   |

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
| HDD  | 8         | 11     | 57.14%  |
| SSD  | 4         | 4      | 28.57%  |
| NVMe | 2         | 2      | 14.29%  |

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
| Works    | 103       | 146    | 83.74%  |
| Malfunc  | 14        | 17     | 11.38%  |
| Detected | 6         | 9      | 4.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 59        | 36.65%  |
| SanDisk                          | 23        | 14.29%  |
| Samsung Electronics              | 22        | 13.66%  |
| AMD                              | 22        | 13.66%  |
| SK hynix                         | 12        | 7.45%   |
| Micron Technology                | 6         | 3.73%   |
| Phison Electronics               | 4         | 2.48%   |
| Toshiba America Info Systems     | 3         | 1.86%   |
| KIOXIA                           | 3         | 1.86%   |
| Kingston Technology Company      | 2         | 1.24%   |
| Union Memory (Shenzhen)          | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] | 1         | 0.62%   |
| Seagate Technology               | 1         | 0.62%   |
| Micron/Crucial Technology        | 1         | 0.62%   |
| Lite-On Technology               | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 12.73%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 7.27%   |
| SK hynix Gold P31 SSD                                                          | 10        | 6.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 4.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 4.24%   |
| Intel SSD 660P Series                                                          | 7         | 4.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 3.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 3.64%   |
| Micron Non-Volatile memory controller                                          | 6         | 3.64%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 3.03%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 2.42%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.82%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.21%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2         | 1.21%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.21%   |
| KIOXIA NVMe SSD                                                                | 2         | 1.21%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.21%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.61%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.61%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.61%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.61%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.61%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.61%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 82        | 53.25%  |
| SATA | 59        | 38.31%  |
| RAID | 7         | 4.55%   |
| IDE  | 6         | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 62.39%  |
| AMD    | 44        | 37.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 4.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 4.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 3.42%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 3.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 3.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.56%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 2.56%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 3         | 2.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.71%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.71%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 1.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.71%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 1.71%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 2         | 1.71%   |
| Intel Xeon E-2276M CPU @ 2.80GHz              | 1         | 0.85%   |
| Intel Pentium M processor 2.00GHz             | 1         | 0.85%   |
| Intel Pentium M processor 1400MHz             | 1         | 0.85%   |
| Intel Pentium M processor 1.60GHz             | 1         | 0.85%   |
| Intel Pentium 4 CPU 2.40GHz                   | 1         | 0.85%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.85%   |
| Intel Core i7-7820HK CPU @ 2.90GHz            | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 27        | 23.08%  |
| AMD Ryzen 7     | 19        | 16.24%  |
| Intel Core i5   | 18        | 15.38%  |
| Other           | 16        | 13.68%  |
| AMD Ryzen 5     | 9         | 7.69%   |
| AMD Ryzen 9     | 5         | 4.27%   |
| AMD Ryzen 7 PRO | 5         | 4.27%   |
| AMD Ryzen 3     | 4         | 3.42%   |
| Intel Pentium M | 3         | 2.56%   |
| Intel Core i9   | 2         | 1.71%   |
| Intel Core i3   | 2         | 1.71%   |
| Intel Atom      | 2         | 1.71%   |
| AMD E1          | 2         | 1.71%   |
| Intel Xeon      | 1         | 0.85%   |
| Intel Pentium 4 | 1         | 0.85%   |
| Intel Core Duo  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 38        | 32.48%  |
| 8      | 33        | 28.21%  |
| 6      | 19        | 16.24%  |
| 2      | 18        | 15.38%  |
| 1      | 6         | 5.13%   |
| 12     | 2         | 1.71%   |
| 14     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 88.14%  |
| 1      | 14        | 11.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 94.02%  |
| 32-bit         | 7         | 5.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 14        | 11.86%  |
| 0x906ea    | 12        | 10.17%  |
| Unknown    | 10        | 8.47%   |
| 0x806ec    | 8         | 6.78%   |
| 0x806d1    | 6         | 5.08%   |
| 0x08108109 | 6         | 5.08%   |
| 0x806c1    | 5         | 4.24%   |
| 0x08608103 | 5         | 4.24%   |
| 0x08600106 | 4         | 3.39%   |
| 0x08600103 | 4         | 3.39%   |
| 0xa0652    | 3         | 2.54%   |
| 0x906a3    | 3         | 2.54%   |
| 0x506e3    | 3         | 2.54%   |
| 0x306d4    | 3         | 2.54%   |
| 0x306a9    | 3         | 2.54%   |
| 0x906ed    | 2         | 1.69%   |
| 0x806e9    | 2         | 1.69%   |
| 0x706e5    | 2         | 1.69%   |
| 0x306c3    | 2         | 1.69%   |
| 0x206a7    | 2         | 1.69%   |
| 0x0a404102 | 2         | 1.69%   |
| 0x0a404101 | 2         | 1.69%   |
| 0x08600102 | 2         | 1.69%   |
| 0x05000119 | 2         | 1.69%   |
| 0xf29      | 1         | 0.85%   |
| 0x906e9    | 1         | 0.85%   |
| 0x806eb    | 1         | 0.85%   |
| 0x806ea    | 1         | 0.85%   |
| 0x806c2    | 1         | 0.85%   |
| 0x6ec      | 1         | 0.85%   |
| 0x6d8      | 1         | 0.85%   |
| 0x406e3    | 1         | 0.85%   |
| 0x08608102 | 1         | 0.85%   |
| 0x08108102 | 1         | 0.85%   |
| 0x08001105 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 25.42%  |
| Zen 3            | 14        | 11.86%  |
| Unknown          | 11        | 9.32%   |
| Zen 2            | 10        | 8.47%   |
| IceLake          | 9         | 7.63%   |
| Zen+             | 7         | 5.93%   |
| TigerLake        | 7         | 5.93%   |
| Skylake          | 4         | 3.39%   |
| P6               | 4         | 3.39%   |
| IvyBridge        | 3         | 2.54%   |
| CometLake        | 3         | 2.54%   |
| Broadwell        | 3         | 2.54%   |
| Alderlake Hybrid | 3         | 2.54%   |
| SandyBridge      | 2         | 1.69%   |
| Haswell          | 2         | 1.69%   |
| Bonnell          | 2         | 1.69%   |
| Bobcat           | 2         | 1.69%   |
| Zen              | 1         | 0.85%   |
| NetBurst         | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 42.21%  |
| Nvidia | 45        | 29.22%  |
| AMD    | 44        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                                   | 13        | 7.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 12        | 7.32%   |
| AMD Renoir                                                                    | 9         | 5.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 4.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 7         | 4.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 6         | 3.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 6         | 3.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 6         | 3.66%   |
| AMD Lucienne                                                                  | 6         | 3.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 2.44%   |
| AMD Rembrandt [Radeon 680M]                                                   | 4         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.83%   |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 1.83%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 1.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 3         | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.83%   |
| Intel UHD Graphics 620                                                        | 3         | 1.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 1.83%   |
| Intel HD Graphics 5500                                                        | 3         | 1.83%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 3         | 1.83%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                              | 2         | 1.22%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 1.22%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 1.22%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 1.22%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.22%   |
| Intel HD Graphics 630                                                         | 2         | 1.22%   |
| Intel HD Graphics 620                                                         | 2         | 1.22%   |
| Intel HD Graphics 530                                                         | 2         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 1.22%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.61%   |
| Nvidia TU117M                                                                 | 1         | 0.61%   |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.61%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.61%   |
| Nvidia NV17M [GeForce4 420 Go]                                                | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 31        | 26.5%   |
| 1 x AMD        | 31        | 26.5%   |
| 1 x Intel      | 28        | 23.93%  |
| 1 x Nvidia     | 9         | 7.69%   |
| 2 x AMD        | 7         | 5.98%   |
| 2 x Intel      | 5         | 4.27%   |
| AMD + Nvidia   | 5         | 4.27%   |
| Intel + AMD    | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 86        | 73.5%   |
| Proprietary | 27        | 23.08%  |
| Unknown     | 4         | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 48.74%  |
| 0.01-0.5   | 17        | 14.29%  |
| 1.01-2.0   | 13        | 10.92%  |
| 3.01-4.0   | 12        | 10.08%  |
| 0.51-1.0   | 6         | 5.04%   |
| 7.01-8.0   | 4         | 3.36%   |
| 5.01-6.0   | 4         | 3.36%   |
| 8.01-16.0  | 3         | 2.52%   |
| 2.01-3.0   | 2         | 1.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 26        | 19.4%   |
| AU Optronics            | 23        | 17.16%  |
| Samsung Electronics     | 17        | 12.69%  |
| Chimei Innolux          | 16        | 11.94%  |
| LG Display              | 10        | 7.46%   |
| Sharp                   | 9         | 6.72%   |
| Lenovo                  | 6         | 4.48%   |
| Hewlett-Packard         | 3         | 2.24%   |
| Goldstar                | 3         | 2.24%   |
| CSO                     | 3         | 2.24%   |
| PANDA                   | 2         | 1.49%   |
| Dell                    | 2         | 1.49%   |
| BenQ                    | 2         | 1.49%   |
| ASUSTek Computer        | 2         | 1.49%   |
| Xiaomi                  | 1         | 0.75%   |
| ViewSonic               | 1         | 0.75%   |
| MSI                     | 1         | 0.75%   |
| IOC                     | 1         | 0.75%   |
| InfoVision              | 1         | 0.75%   |
| Iiyama                  | 1         | 0.75%   |
| HannStar                | 1         | 0.75%   |
| Chi Mei Optoelectronics | 1         | 0.75%   |
| AOC                     | 1         | 0.75%   |
| Acer                    | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 2.24%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 2         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 2         | 1.49%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 2         | 1.49%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch        | 2         | 1.49%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 2         | 1.49%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.49%   |
| BOE LCD Monitor BOE082B 1920x1080 309x174mm 14.0-inch                  | 2         | 1.49%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                  | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.49%   |
| Xiaomi Mi TV XMD0002 1920x1080 708x398mm 32.0-inch                     | 1         | 0.75%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch            | 1         | 0.75%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4A58 1024x768 246x184mm 12.1-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4165 3840x2400 344x215mm 16.0-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 0.75%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 0.75%   |
| Samsung Electronics 173HT02-C01 SECD033 1920x1080 382x215mm 17.3-inch  | 1         | 0.75%   |
| PANDA LCD Monitor NCP0067 1920x1080 309x174mm 14.0-inch                | 1         | 0.75%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                | 1         | 0.75%   |
| MSI MAG272QR MSI3CA8 2560x1440 597x336mm 27.0-inch                     | 1         | 0.75%   |
| LG Display LCD Monitor LGD06DA 1920x1080 344x194mm 15.5-inch           | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 53.66%  |
| 3840x2160 (4K)     | 11        | 8.94%   |
| 2560x1440 (QHD)    | 10        | 8.13%   |
| 1366x768 (WXGA)    | 9         | 7.32%   |
| 3840x2400          | 4         | 3.25%   |
| 2560x1600          | 4         | 3.25%   |
| 1920x1200 (WUXGA)  | 4         | 3.25%   |
| 3440x1440          | 2         | 1.63%   |
| 2880x1800          | 2         | 1.63%   |
| 2256x1504          | 2         | 1.63%   |
| 1024x600           | 2         | 1.63%   |
| 3456x2160          | 1         | 0.81%   |
| 2160x1440          | 1         | 0.81%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |
| 1600x900 (HD+)     | 1         | 0.81%   |
| 1440x900 (WXGA+)   | 1         | 0.81%   |
| 1280x1024 (SXGA)   | 1         | 0.81%   |
| 1024x768 (XGA)     | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 52        | 39.39%  |
| 14     | 19        | 14.39%  |
| 13     | 18        | 13.64%  |
| 17     | 10        | 7.58%   |
| 27     | 7         | 5.3%    |
| 16     | 7         | 5.3%    |
| 24     | 3         | 2.27%   |
| 23     | 3         | 2.27%   |
| 34     | 2         | 1.52%   |
| 21     | 2         | 1.52%   |
| 12     | 2         | 1.52%   |
| 65     | 1         | 0.76%   |
| 54     | 1         | 0.76%   |
| 25     | 1         | 0.76%   |
| 22     | 1         | 0.76%   |
| 18     | 1         | 0.76%   |
| 10     | 1         | 0.76%   |
| 8      | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 65.12%  |
| 501-600     | 13        | 10.08%  |
| 201-300     | 12        | 9.3%    |
| 351-400     | 11        | 8.53%   |
| 401-500     | 4         | 3.1%    |
| 701-800     | 2         | 1.55%   |
| 1001-1500   | 2         | 1.55%   |
| 101-200     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 92        | 79.31%  |
| 16/10 | 17        | 14.66%  |
| 3/2   | 3         | 2.59%   |
| 21/9  | 2         | 1.72%   |
| 5/4   | 1         | 0.86%   |
| 4/3   | 1         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 40.46%  |
| 81-90          | 32        | 24.43%  |
| 121-130        | 9         | 6.87%   |
| 301-350        | 7         | 5.34%   |
| 201-250        | 6         | 4.58%   |
| 111-120        | 6         | 4.58%   |
| 71-80          | 5         | 3.82%   |
| More than 1000 | 2         | 1.53%   |
| 61-70          | 2         | 1.53%   |
| 351-500        | 2         | 1.53%   |
| 251-300        | 2         | 1.53%   |
| 141-150        | 2         | 1.53%   |
| 41-50          | 1         | 0.76%   |
| 1-40           | 1         | 0.76%   |
| 151-200        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 48.46%  |
| 161-240       | 18        | 13.85%  |
| 101-120       | 18        | 13.85%  |
| More than 240 | 16        | 12.31%  |
| 51-100        | 13        | 10%     |
| 1-50          | 2         | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 91        | 77.12%  |
| 2     | 19        | 16.1%   |
| 0     | 5         | 4.24%   |
| 3     | 3         | 2.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 78        | 44.57%  |
| Realtek Semiconductor             | 58        | 33.14%  |
| Qualcomm Atheros                  | 10        | 5.71%   |
| MediaTek                          | 7         | 4%      |
| Broadcom                          | 4         | 2.29%   |
| Samsung Electronics               | 2         | 1.14%   |
| Qualcomm                          | 2         | 1.14%   |
| ASIX Electronics                  | 2         | 1.14%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.57%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.57%   |
| Sierra Wireless                   | 1         | 0.57%   |
| Shenzhen Goodix Technology        | 1         | 0.57%   |
| Marvell Technology Group          | 1         | 0.57%   |
| Lenovo                            | 1         | 0.57%   |
| ICS Advent                        | 1         | 0.57%   |
| Ericsson Business Mobile Networks | 1         | 0.57%   |
| Dell                              | 1         | 0.57%   |
| D-Link                            | 1         | 0.57%   |
| Broadcom Limited                  | 1         | 0.57%   |
| Aquantia                          | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 17.84%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 8.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 3.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 2.35%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 2.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 1.88%   |
| Intel Wireless 8260                                               | 4         | 1.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.94%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 0.94%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection         | 2         | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller  | 2         | 0.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.94%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller           | 1         | 0.47%   |
| Sierra Wireless EM7455                                            | 1         | 0.47%   |
| Shenzhen Goodix Unknow device                                     | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 76        | 63.87%  |
| Realtek Semiconductor | 22        | 18.49%  |
| MediaTek              | 7         | 5.88%   |
| Qualcomm Atheros      | 6         | 5.04%   |
| Qualcomm              | 2         | 1.68%   |
| Broadcom              | 2         | 1.68%   |
| Sierra Wireless       | 1         | 0.84%   |
| Dell                  | 1         | 0.84%   |
| D-Link                | 1         | 0.84%   |
| Broadcom Limited      | 1         | 0.84%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 19        | 15.97%  |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 5.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 5.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 4.2%    |
| Intel Wireless 8265 / 8275                                              | 5         | 4.2%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 4.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 4.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.36%   |
| Intel Wireless 8260                                                     | 4         | 3.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.68%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.68%   |
| Sierra Wireless EM7455                                                  | 1         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.84%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 1         | 0.84%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 0.84%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| MediaTek WLAN controller                                                | 1         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.84%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.84%   |
| Intel Wireless 7265                                                     | 1         | 0.84%   |
| Intel Wireless 3160                                                     | 1         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.84%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 48        | 55.81%  |
| Intel                            | 20        | 23.26%  |
| Qualcomm Atheros                 | 6         | 6.98%   |
| Samsung Electronics              | 2         | 2.33%   |
| Broadcom                         | 2         | 2.33%   |
| ASIX Electronics                 | 2         | 2.33%   |
| ZTE WCDMA Technologies MSM       | 1         | 1.16%   |
| Silicon Integrated Systems [SiS] | 1         | 1.16%   |
| Marvell Technology Group         | 1         | 1.16%   |
| Lenovo                           | 1         | 1.16%   |
| ICS Advent                       | 1         | 1.16%   |
| Aquantia                         | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 43.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 3.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.27%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.27%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 1.14%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.14%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.14%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.14%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.14%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.14%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.14%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.14%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 1.14%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.14%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.14%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 56.93%  |
| Ethernet | 81        | 40.1%   |
| Modem    | 5         | 2.48%   |
| Unknown  | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 75.21%  |
| Ethernet | 30        | 24.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 71        | 60.68%  |
| 1     | 44        | 37.61%  |
| 3     | 2         | 1.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 91        | 75.21%  |
| Yes  | 30        | 24.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 66%     |
| Realtek Semiconductor | 14        | 14%     |
| IMC Networks          | 6         | 6%      |
| Foxconn / Hon Hai     | 4         | 4%      |
| Toshiba               | 2         | 2%      |
| USI                   | 1         | 1%      |
| Realtek               | 1         | 1%      |
| Lite-On Technology    | 1         | 1%      |
| Hewlett-Packard       | 1         | 1%      |
| Foxconn International | 1         | 1%      |
| Broadcom              | 1         | 1%      |
| ASUSTek Computer      | 1         | 1%      |
| Apple                 | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 17        | 17%     |
| Intel AX200 Bluetooth                             | 16        | 16%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 13        | 13%     |
| Intel Bluetooth wireless interface                | 11        | 11%     |
| Realtek Bluetooth Radio                           | 8         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 4%      |
| Intel AX210 Bluetooth                             | 4         | 4%      |
| IMC Networks Wireless_Device                      | 4         | 4%      |
| Intel Bluetooth Device                            | 3         | 3%      |
| Foxconn / Hon Hai Wireless_Device                 | 3         | 3%      |
| Toshiba RT Bluetooth Radio                        | 2         | 2%      |
| USI Bluetooth Device                              | 1         | 1%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 1%      |
| Realtek RTL8723B Bluetooth                        | 1         | 1%      |
| Realtek Bluetooth Radio                           | 1         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 1%      |
| IMC Networks Bluetooth Radio                      | 1         | 1%      |
| IMC Networks Bluetooth Device                     | 1         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1%      |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 1%      |
| Broadcom HP Portable SoftSailing                  | 1         | 1%      |
| ASUS Broadcom Bluetooth 2.1                       | 1         | 1%      |
| Apple Bluetooth USB Host Controller               | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 72        | 46.75%  |
| AMD                                  | 45        | 29.22%  |
| Nvidia                               | 28        | 18.18%  |
| Hewlett-Packard                      | 2         | 1.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.65%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.65%   |
| Razer USA                            | 1         | 0.65%   |
| Lenovo                               | 1         | 0.65%   |
| Kingston Technology                  | 1         | 0.65%   |
| DSEA A/S                             | 1         | 0.65%   |
| ACTIONS                              | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 40        | 19.61%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 26        | 12.75%  |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 6.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.96%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.96%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.98%   |
| Nvidia Audio device                                                        | 2         | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.98%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.98%   |
| Hewlett-Packard USB Audio                                                  | 2         | 0.98%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.98%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.98%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.98%   |
| Thesycon Systemsoftware & Consulting D50s                                  | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.49%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 43.85%  |
| SK hynix            | 26        | 20%     |
| Micron Technology   | 15        | 11.54%  |
| Kingston            | 9         | 6.92%   |
| Unknown             | 5         | 3.85%   |
| Crucial             | 5         | 3.85%   |
| Patriot             | 2         | 1.54%   |
| A-DATA Technology   | 2         | 1.54%   |
| Unknown             | 2         | 1.54%   |
| Transcend           | 1         | 0.77%   |
| Timetec             | 1         | 0.77%   |
| Team                | 1         | 0.77%   |
| Ramaxel Technology  | 1         | 0.77%   |
| Magnum Tech         | 1         | 0.77%   |
| G.Skill             | 1         | 0.77%   |
| Corsair             | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 4.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 2.99%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 2.24%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 2.24%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.24%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.24%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.24%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.49%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 2         | 1.49%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.49%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.49%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.49%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 1.49%   |
| Kingston RAM KF3200C20S4/16GX 16384MB SODIMM DDR4 3200MT/s       | 2         | 1.49%   |
| Unknown                                                          | 2         | 1.49%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.75%   |
| Unknown RAM Module 256MB SODIMM DDR 133MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.75%   |
| Transcend RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.75%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.75%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.75%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM 4800MT/s                | 1         | 0.75%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.75%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 71.55%  |
| DDR3    | 13        | 11.21%  |
| LPDDR4  | 5         | 4.31%   |
| DDR     | 4         | 3.45%   |
| LPDDR3  | 3         | 2.59%   |
| LPDDR5  | 2         | 1.72%   |
| DDR5    | 2         | 1.72%   |
| DDR2    | 2         | 1.72%   |
| SDRAM   | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 88.14%  |
| Row Of Chips | 13        | 11.02%  |
| Chip         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 47.06%  |
| 16384 | 31        | 26.05%  |
| 4096  | 13        | 10.92%  |
| 32768 | 9         | 7.56%   |
| 2048  | 4         | 3.36%   |
| 1024  | 3         | 2.52%   |
| 512   | 2         | 1.68%   |
| 256   | 1         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 50        | 40.98%  |
| 2667    | 29        | 23.77%  |
| 1600    | 11        | 9.02%   |
| 4800    | 5         | 4.1%    |
| 2133    | 5         | 4.1%    |
| Unknown | 4         | 3.28%   |
| 8400    | 3         | 2.46%   |
| 6400    | 2         | 1.64%   |
| 4267    | 2         | 1.64%   |
| 2400    | 2         | 1.64%   |
| 667     | 2         | 1.64%   |
| 533     | 2         | 1.64%   |
| 3733    | 1         | 0.82%   |
| 2933    | 1         | 0.82%   |
| 1333    | 1         | 0.82%   |
| 1067    | 1         | 0.82%   |
| 133     | 1         | 0.82%   |

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
| Chicony Electronics                    | 24        | 26.37%  |
| IMC Networks                           | 19        | 20.88%  |
| Acer                                   | 8         | 8.79%   |
| Lite-On Technology                     | 7         | 7.69%   |
| Microdia                               | 6         | 6.59%   |
| Realtek Semiconductor                  | 5         | 5.49%   |
| Quanta                                 | 4         | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.4%    |
| Syntek                                 | 3         | 3.3%    |
| Sunplus Innovation Technology          | 3         | 3.3%    |
| Luxvisions Innotech Limited            | 3         | 3.3%    |
| Sonix Technology                       | 1         | 1.1%    |
| Samsung Electronics                    | 1         | 1.1%    |
| DigiTech                               | 1         | 1.1%    |
| Cubeternet                             | 1         | 1.1%    |
| Alcor Micro                            | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 10        | 10.87%  |
| Chicony Integrated Camera                                      | 7         | 7.61%   |
| Microdia Integrated_Webcam_HD                                  | 6         | 6.52%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 6.52%   |
| Acer Integrated Camera                                         | 5         | 5.43%   |
| Chicony HD User Facing                                         | 3         | 3.26%   |
| Syntek Integrated Camera                                       | 2         | 2.17%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 2.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 2.17%   |
| Lite-On TOSHIBA Web Camera - HD                                | 2         | 2.17%   |
| Lite-On Integrated Camera                                      | 2         | 2.17%   |
| Lite-On HP Wide Vision HD Camera                               | 2         | 2.17%   |
| Chicony XiaoMi USB 2.0 Webcam                                  | 2         | 2.17%   |
| Chicony USB2.0 Camera                                          | 2         | 2.17%   |
| Chicony HP HD Camera                                           | 2         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.17%   |
| Acer NEC HD WebCam                                             | 2         | 2.17%   |
| Syntek Lenovo EasyCamera                                       | 1         | 1.09%   |
| Sunplus HP Wide Vision HD                                      | 1         | 1.09%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 1.09%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 1.09%   |
| Realtek USB Camera                                             | 1         | 1.09%   |
| Realtek Laptop Camera                                          | 1         | 1.09%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.09%   |
| Realtek Integrated Webcam HD                                   | 1         | 1.09%   |
| Realtek Integrated Camera                                      | 1         | 1.09%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.09%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.09%   |
| Quanta HD Webcam                                               | 1         | 1.09%   |
| Quanta HD Camera                                               | 1         | 1.09%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.09%   |
| Lite-On HP Webcam                                              | 1         | 1.09%   |
| IMC Networks XiaoMi Webcam                                     | 1         | 1.09%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                            | 1         | 1.09%   |
| IMC Networks Lenovo EasyCamera                                 | 1         | 1.09%   |
| IMC Networks Integrated IR Camera                              | 1         | 1.09%   |
| DigiTech SC-20FHL11146M                                        | 1         | 1.09%   |
| Cubeternet HDMI to U3 capture                                  | 1         | 1.09%   |
| Chicony USB 2.0 Camera                                         | 1         | 1.09%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 44.44%  |
| Elan Microelectronics      | 5         | 27.78%  |
| Validity Sensors           | 4         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                      | 4         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                            | 1         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                           | 1         | 5.56%   |
| Unknown                                                    | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 4         | 40%     |
| Alcor Micro               | 4         | 40%     |
| O2 Micro                  | 1         | 10%     |
| Aladdin Knowledge Systems | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 4         | 40%     |
| Broadcom 58200                      | 3         | 30%     |
| O2 Micro Oz776 SmartCard Reader     | 1         | 10%     |
| Broadcom 5880                       | 1         | 10%     |
| Aladdin Knowledge Systems Token JC  | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 42.02%  |
| 1     | 30        | 25.21%  |
| 2     | 19        | 15.97%  |
| 3     | 11        | 9.24%   |
| 4     | 5         | 4.2%    |
| 5     | 2         | 1.68%   |
| 7     | 1         | 0.84%   |
| 6     | 1         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 13.87%  |
| Fingerprint reader       | 18        | 13.14%  |
| Camera                   | 16        | 11.68%  |
| Bluetooth                | 16        | 11.68%  |
| Net/wireless             | 14        | 10.22%  |
| Communication controller | 14        | 10.22%  |
| Multimedia controller    | 11        | 8.03%   |
| Chipcard                 | 8         | 5.84%   |
| Sound                    | 5         | 3.65%   |
| Network                  | 5         | 3.65%   |
| Card reader              | 5         | 3.65%   |
| Modem                    | 2         | 1.46%   |
| Firewire controller      | 2         | 1.46%   |
| Storage/ata              | 1         | 0.73%   |
| Net/ethernet             | 1         | 0.73%   |

