Linux in Croatia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 353

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [2dcace1084](https://linux-hardware.org/?probe=2dcace1084) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| HP            | ProBook 4530s               | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Acer          | Aspire A515-51G             | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f7cce89284](https://linux-hardware.org/?probe=f7cce89284) | Feb 17, 2022 |
| Dell          | XPS 13 9310                 | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| Apple         | MacBookPro11,4              | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| Acer          | Aspire F5-573G              | [ffb245749e](https://linux-hardware.org/?probe=ffb245749e) | Jan 12, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | B590 20208                  | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Dell          | XPS 13 9310                 | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| Dell          | Inspiron N5110              | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| SHENZHEN X... | ST106                       | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| Toshiba       | Satellite P200              | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Acer          | Aspire F5-573G              | [a62e03df32](https://linux-hardware.org/?probe=a62e03df32) | Sep 25, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| HUAWEI        | WRTB-WXX9                   | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Dell          | Inspiron N5110              | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| Acer          | Aspire 6930G                | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | [0f1f02371d](https://linux-hardware.org/?probe=0f1f02371d) | Jul 19, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire F5-573G              | [40424da04c](https://linux-hardware.org/?probe=40424da04c) | Jul 08, 2021 |
| Dell          | Latitude 3190               | [6ca8a34d23](https://linux-hardware.org/?probe=6ca8a34d23) | Jul 05, 2021 |
| Acer          | Aspire E5-571G              | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| Dell          | Latitude 3190               | [ec46d1beb2](https://linux-hardware.org/?probe=ec46d1beb2) | Jun 28, 2021 |
| HP            | EliteBook 850 G6            | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| HP            | 255 G7 Notebook PC          | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Acer          | Aspire F5-571G              | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Acer          | Aspire A315-34              | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| Acer          | Aspire F5-573G              | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| Dell          | XPS 13 9380                 | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Acer          | Aspire A315-41              | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| HP            | 250 G5 Notebook PC          | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| Dell          | Latitude E6430              | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| Dell          | Vostro 3578                 | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| Acer          | Aspire A315-21              | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| Dell          | Vostro 3578                 | [f5bf5ee5fb](https://linux-hardware.org/?probe=f5bf5ee5fb) | Dec 14, 2020 |
| Acer          | Aspire 7739G                | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Dell          | Vostro 3578                 | [72e2891df0](https://linux-hardware.org/?probe=72e2891df0) | Dec 11, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [9dd7d150b8](https://linux-hardware.org/?probe=9dd7d150b8) | Dec 08, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | [ae2f02866d](https://linux-hardware.org/?probe=ae2f02866d) | Nov 22, 2020 |
| Acer          | Aspire ES1-732              | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| Dell          | XPS 15 7590                 | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Toshiba       | Satellite C55-A-1M7         | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| Dell          | XPS 15 9570                 | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| HP            | ProBook 450 G7              | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| HP            | EliteBook 850 G6            | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| HP            | ProBook 430 G3              | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| HP            | EliteBook 850 G6            | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| HP            | ProBook 430 G3              | [fdc95a9b5e](https://linux-hardware.org/?probe=fdc95a9b5e) | Aug 15, 2020 |
| HP            | ProBook 430 G3              | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Dell          | Precision 5530              | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| HP            | 255 G7 Notebook PC          | [6a29cd065c](https://linux-hardware.org/?probe=6a29cd065c) | Jul 15, 2020 |
| ASUSTek       | X751NV                      | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| HP            | 255 G7 Notebook PC          | [949f6cb34c](https://linux-hardware.org/?probe=949f6cb34c) | Jul 13, 2020 |
| Notebook      | MAM2080                     | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Acer          | Swift SF314-52              | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Lenovo        | G500 20236                  | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Toshiba       | Satellite L50-B             | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| eMachines     | G725                        | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| Acer          | Aspire A315-51              | [33be21bf03](https://linux-hardware.org/?probe=33be21bf03) | May 02, 2020 |
| Acer          | Aspire A315-51              | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| Medion        | P6618                       | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| HP            | Pavilion g6                 | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | Laptop 17-ca0xxx            | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| HP            | OMEN by HP Laptop 17-cb0... | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| Toshiba       | Satellite A300              | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [76af33f6a0](https://linux-hardware.org/?probe=76af33f6a0) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [83f979f993](https://linux-hardware.org/?probe=83f979f993) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [662f5b1284](https://linux-hardware.org/?probe=662f5b1284) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [b90ab9f1ac](https://linux-hardware.org/?probe=b90ab9f1ac) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASUSTek       | G750JZ                      | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Acer          | Aspire A515-51G             | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| HP            | Laptop 17-ca0xxx            | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | Laptop 17-ca0xxx            | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | [ca189683d0](https://linux-hardware.org/?probe=ca189683d0) | May 03, 2019 |
| HP            | Notebook                    | [3fcf0f0723](https://linux-hardware.org/?probe=3fcf0f0723) | May 03, 2019 |
| HP            | Notebook                    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | [31d91d2705](https://linux-hardware.org/?probe=31d91d2705) | Apr 30, 2019 |
| Toshiba       | Satellite A300              | [784a5d3cb1](https://linux-hardware.org/?probe=784a5d3cb1) | Apr 30, 2019 |
| Toshiba       | Satellite A300              | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| HP            | Unknown                     | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | X540UA                      | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | [ae1021afdc](https://linux-hardware.org/?probe=ae1021afdc) | Dec 16, 2018 |
| ASUSTek       | X540UA                      | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Acer          | Aspire 5715Z                | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| HP            | ProBook 450 G4              | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| HP            | EliteBook 2540p             | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Dell          | Vostro 1700                 | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 48        | 19.59%  |
| Ubuntu 18.04        | 18        | 7.35%   |
| Pop!_OS 21.04       | 7         | 2.86%   |
| Debian 11           | 7         | 2.86%   |
| Pop!_OS 20.04       | 6         | 2.45%   |
| Ubuntu 19.04        | 5         | 2.04%   |
| Fedora 35           | 5         | 2.04%   |
| Ubuntu 21.04        | 4         | 1.63%   |
| Pop!_OS 20.10       | 4         | 1.63%   |
| OpenMandriva 4.3    | 4         | 1.63%   |
| Linux Mint 20.2     | 4         | 1.63%   |
| Endless 3.7.8       | 4         | 1.63%   |
| Zorin 16            | 3         | 1.22%   |
| Zorin 15            | 3         | 1.22%   |
| Ubuntu 20.10        | 3         | 1.22%   |
| Ubuntu 19.10        | 3         | 1.22%   |
| Ubuntu 18.10        | 3         | 1.22%   |
| ROSA R10            | 3         | 1.22%   |
| Pop!_OS 21.10       | 3         | 1.22%   |
| OpenMandriva 4.2    | 3         | 1.22%   |
| KDE neon 20.04      | 3         | 1.22%   |
| Endless 3.9.5       | 3         | 1.22%   |
| Endless 3.9.4       | 3         | 1.22%   |
| Arch Rolling        | 3         | 1.22%   |
| Arch                | 3         | 1.22%   |
| Ubuntu 22.04        | 2         | 0.82%   |
| Manjaro 21.0.7      | 2         | 0.82%   |
| Manjaro 21.0        | 2         | 0.82%   |
| Manjaro 20.2.1      | 2         | 0.82%   |
| Manjaro 20.2        | 2         | 0.82%   |
| Manjaro 20.1.2      | 2         | 0.82%   |
| Manjaro 18.1.5      | 2         | 0.82%   |
| Linux Mint 20       | 2         | 0.82%   |
| Linux Mint 19.3     | 2         | 0.82%   |
| Kubuntu 21.04       | 2         | 0.82%   |
| Kubuntu 20.04       | 2         | 0.82%   |
| Fedora 34           | 2         | 0.82%   |
| Fedora 33           | 2         | 0.82%   |
| Endless 3.9.3       | 2         | 0.82%   |
| Endless 3.8.3       | 2         | 0.82%   |
| Debian 10           | 2         | 0.82%   |
| ArcoLinux Rolling   | 2         | 0.82%   |
| Xubuntu 18.04       | 1         | 0.41%   |
| Ubuntu MATE 20.04   | 1         | 0.41%   |
| Ubuntu MATE 18.04   | 1         | 0.41%   |
| Ubuntu Budgie 20.04 | 1         | 0.41%   |
| Ubuntu 21.10        | 1         | 0.41%   |
| ROSA R8.1           | 1         | 0.41%   |
| ROSA R8             | 1         | 0.41%   |
| Parrot 4.9          | 1         | 0.41%   |
| Parrot 4.8          | 1         | 0.41%   |
| openSUSE Leap-15.1  | 1         | 0.41%   |
| openSUSE 20210106   | 1         | 0.41%   |
| OpenMandriva 4.50   | 1         | 0.41%   |
| MX 19               | 1         | 0.41%   |
| Manjaro 21.2.5      | 1         | 0.41%   |
| Manjaro 21.0.1      | 1         | 0.41%   |
| Manjaro 20.0.3      | 1         | 0.41%   |
| Manjaro 18.1.2      | 1         | 0.41%   |
| Manjaro             | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 78        | 35.78%  |
| Endless       | 21        | 9.63%   |
| Pop!_OS       | 19        | 8.72%   |
| Linux Mint    | 13        | 5.96%   |
| Manjaro       | 12        | 5.5%    |
| Fedora        | 11        | 5.05%   |
| Debian        | 9         | 4.13%   |
| OpenMandriva  | 8         | 3.67%   |
| Kubuntu       | 7         | 3.21%   |
| Zorin         | 6         | 2.75%   |
| Arch          | 6         | 2.75%   |
| ROSA          | 5         | 2.29%   |
| KDE neon      | 3         | 1.38%   |
| Ubuntu MATE   | 2         | 0.92%   |
| openSUSE      | 2         | 0.92%   |
| Kali          | 2         | 0.92%   |
| EndeavourOS   | 2         | 0.92%   |
| Elementary    | 2         | 0.92%   |
| ArcoLinux     | 2         | 0.92%   |
| Xubuntu       | 1         | 0.46%   |
| Ubuntu Budgie | 1         | 0.46%   |
| Parrot        | 1         | 0.46%   |
| MX            | 1         | 0.46%   |
| LMDE          | 1         | 0.46%   |
| LinuxFX       | 1         | 0.46%   |
| Gentoo        | 1         | 0.46%   |
| CentOS        | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 6         | 2.24%   |
| 5.11.0-38-generic               | 6         | 2.24%   |
| 5.4.0-42-generic                | 5         | 1.87%   |
| 5.11.0-7620-generic             | 5         | 1.87%   |
| 5.3.0-28-generic                | 4         | 1.49%   |
| 5.16.7-desktop-1omv4003         | 4         | 1.49%   |
| 5.13.0-30-generic               | 4         | 1.49%   |
| 5.8.16-2-MANJARO                | 3         | 1.12%   |
| 5.8.0-7630-generic              | 3         | 1.12%   |
| 5.8.0-59-generic                | 3         | 1.12%   |
| 5.8.0-43-generic                | 3         | 1.12%   |
| 5.4.0-52-generic                | 3         | 1.12%   |
| 5.4.0-48-generic                | 3         | 1.12%   |
| 5.4.0-47-generic                | 3         | 1.12%   |
| 5.4.0-40-generic                | 3         | 1.12%   |
| 5.4.0-37-generic                | 3         | 1.12%   |
| 5.4.0-29-generic                | 3         | 1.12%   |
| 5.4.0-19-generic                | 3         | 1.12%   |
| 5.13.0-7620-generic             | 3         | 1.12%   |
| 5.11.0-41-generic               | 3         | 1.12%   |
| 5.11.0-40-generic               | 3         | 1.12%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.12%   |
| 4.18.0-18-generic               | 3         | 1.12%   |
| 5.9.16-1-MANJARO                | 2         | 0.75%   |
| 5.8.0-49-generic                | 2         | 0.75%   |
| 5.8.0-48-generic                | 2         | 0.75%   |
| 5.4.0-91-generic                | 2         | 0.75%   |
| 5.4.0-84-generic                | 2         | 0.75%   |
| 5.4.0-7642-generic              | 2         | 0.75%   |
| 5.4.0-56-generic                | 2         | 0.75%   |
| 5.4.0-54-generic                | 2         | 0.75%   |
| 5.3.0-23-generic                | 2         | 0.75%   |
| 5.16.11-76051611-generic        | 2         | 0.75%   |
| 5.15.0-27-generic               | 2         | 0.75%   |
| 5.11.0-35-generic               | 2         | 0.75%   |
| 5.11.0-34-generic               | 2         | 0.75%   |
| 5.11.0-27-generic               | 2         | 0.75%   |
| 5.11.0-25-generic               | 2         | 0.75%   |
| 5.10.0-9-amd64                  | 2         | 0.75%   |
| 5.0.0-20-generic                | 2         | 0.75%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.75%   |
| 4.18.0-15-generic               | 2         | 0.75%   |
| 4.15.0-23-generic               | 2         | 0.75%   |
| 5.9.9-arch1-1                   | 1         | 0.37%   |
| 5.9.16-200.fc33.x86_64          | 1         | 0.37%   |
| 5.9.16-050916-generic           | 1         | 0.37%   |
| 5.9.11-arch2-1                  | 1         | 0.37%   |
| 5.9.11-3-MANJARO                | 1         | 0.37%   |
| 5.9.1-gentoo                    | 1         | 0.37%   |
| 5.8.6-1-MANJARO                 | 1         | 0.37%   |
| 5.8.0-7625-generic              | 1         | 0.37%   |
| 5.8.0-63-lowlatency             | 1         | 0.37%   |
| 5.8.0-63-generic                | 1         | 0.37%   |
| 5.8.0-51-generic                | 1         | 0.37%   |
| 5.8.0-31-generic                | 1         | 0.37%   |
| 5.7.11-arch1-1                  | 1         | 0.37%   |
| 5.6.6-300.fc32.x86_64           | 1         | 0.37%   |
| 5.6.2-050602-generic            | 1         | 0.37%   |
| 5.6.19-2-MANJARO                | 1         | 0.37%   |
| 5.6.0-050600-generic            | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 49        | 19.52%  |
| 5.11.0  | 31        | 12.35%  |
| 5.8.0   | 20        | 7.97%   |
| 4.15.0  | 15        | 5.98%   |
| 5.13.0  | 12        | 4.78%   |
| 5.3.0   | 11        | 4.38%   |
| 5.0.0   | 10        | 3.98%   |
| 4.18.0  | 10        | 3.98%   |
| 5.10.0  | 8         | 3.19%   |
| 5.16.7  | 5         | 1.99%   |
| 5.15.0  | 5         | 1.99%   |
| 5.9.16  | 4         | 1.59%   |
| 5.8.16  | 3         | 1.2%    |
| 5.10.14 | 3         | 1.2%    |
| 4.9.60  | 3         | 1.2%    |
| 4.19.0  | 3         | 1.2%    |
| 5.9.11  | 2         | 0.8%    |
| 5.5.0   | 2         | 0.8%    |
| 5.16.11 | 2         | 0.8%    |
| 5.15.8  | 2         | 0.8%    |
| 5.9.9   | 1         | 0.4%    |
| 5.9.1   | 1         | 0.4%    |
| 5.8.6   | 1         | 0.4%    |
| 5.7.11  | 1         | 0.4%    |
| 5.6.6   | 1         | 0.4%    |
| 5.6.2   | 1         | 0.4%    |
| 5.6.19  | 1         | 0.4%    |
| 5.6.0   | 1         | 0.4%    |
| 5.4.74  | 1         | 0.4%    |
| 5.4.17  | 1         | 0.4%    |
| 5.4.13  | 1         | 0.4%    |
| 5.3.8   | 1         | 0.4%    |
| 5.3.18  | 1         | 0.4%    |
| 5.2.10  | 1         | 0.4%    |
| 5.17.4  | 1         | 0.4%    |
| 5.17.1  | 1         | 0.4%    |
| 5.16.9  | 1         | 0.4%    |
| 5.16.8  | 1         | 0.4%    |
| 5.16.14 | 1         | 0.4%    |
| 5.16.12 | 1         | 0.4%    |
| 5.15.7  | 1         | 0.4%    |
| 5.15.3  | 1         | 0.4%    |
| 5.15.16 | 1         | 0.4%    |
| 5.15.15 | 1         | 0.4%    |
| 5.14.9  | 1         | 0.4%    |
| 5.14.0  | 1         | 0.4%    |
| 5.13.19 | 1         | 0.4%    |
| 5.13.13 | 1         | 0.4%    |
| 5.13.12 | 1         | 0.4%    |
| 5.12.4  | 1         | 0.4%    |
| 5.12.12 | 1         | 0.4%    |
| 5.11.6  | 1         | 0.4%    |
| 5.11.22 | 1         | 0.4%    |
| 5.11.16 | 1         | 0.4%    |
| 5.11.14 | 1         | 0.4%    |
| 5.11.12 | 1         | 0.4%    |
| 5.11.10 | 1         | 0.4%    |
| 5.10.88 | 1         | 0.4%    |
| 5.10.79 | 1         | 0.4%    |
| 5.10.43 | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 21.14%  |
| 5.11    | 36        | 14.63%  |
| 5.8     | 24        | 9.76%   |
| 5.10    | 16        | 6.5%    |
| 5.13    | 15        | 6.1%    |
| 4.15    | 15        | 6.1%    |
| 5.3     | 12        | 4.88%   |
| 5.0     | 11        | 4.47%   |
| 5.16    | 10        | 4.07%   |
| 5.15    | 10        | 4.07%   |
| 4.18    | 10        | 4.07%   |
| 5.9     | 8         | 3.25%   |
| 5.6     | 4         | 1.63%   |
| 4.9     | 4         | 1.63%   |
| 4.19    | 3         | 1.22%   |
| 5.5     | 2         | 0.81%   |
| 5.17    | 2         | 0.81%   |
| 5.14    | 2         | 0.81%   |
| 5.12    | 2         | 0.81%   |
| 5.7     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 5.1     | 1         | 0.41%   |
| 4.17    | 1         | 0.41%   |
| 4.16    | 1         | 0.41%   |
| 4.12    | 1         | 0.41%   |
| 4.1     | 1         | 0.41%   |
| 3.10    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 207       | 98.1%   |
| i686   | 4         | 1.9%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 110       | 48.67%  |
| Unknown         | 35        | 15.49%  |
| KDE5            | 30        | 13.27%  |
| X-Cinnamon      | 8         | 3.54%   |
| XFCE            | 7         | 3.1%    |
| KDE             | 6         | 2.65%   |
| Cinnamon        | 6         | 2.65%   |
| MATE            | 5         | 2.21%   |
| GNOME Flashback | 4         | 1.77%   |
| KDE4            | 3         | 1.33%   |
| DWM             | 3         | 1.33%   |
| Unity           | 2         | 0.88%   |
| Pantheon        | 2         | 0.88%   |
| Budgie          | 2         | 0.88%   |
| LXQt            | 1         | 0.44%   |
| i3              | 1         | 0.44%   |
| bspwm           | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 176       | 77.19%  |
| Unknown | 27        | 11.84%  |
| Wayland | 23        | 10.09%  |
| Tty     | 2         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 109       | 50.23%  |
| GDM     | 45        | 20.74%  |
| SDDM    | 28        | 12.9%   |
| LightDM | 12        | 5.53%   |
| TDM     | 10        | 4.61%   |
| GDM3    | 10        | 4.61%   |
| KDM     | 2         | 0.92%   |
| Ly      | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 109       | 49.77%  |
| hr_HR   | 52        | 23.74%  |
| Unknown | 38        | 17.35%  |
| en_GB   | 8         | 3.65%   |
| de_DE   | 5         | 2.28%   |
| C       | 4         | 1.83%   |
| hr_BA   | 1         | 0.46%   |
| fr_FR   | 1         | 0.46%   |
| en_DE   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 134       | 61.19%  |
| BIOS | 85        | 38.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 174       | 79.45%  |
| Unknown | 15        | 6.85%   |
| Overlay | 13        | 5.94%   |
| Btrfs   | 7         | 3.2%    |
| Xfs     | 4         | 1.83%   |
| Zfs     | 2         | 0.91%   |
| Ext2    | 2         | 0.91%   |
| Jfs     | 1         | 0.46%   |
| F2fs    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 53.74%  |
| GPT     | 77        | 35.98%  |
| MBR     | 22        | 10.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 93.02%  |
| Yes       | 15        | 6.98%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 164       | 76.28%  |
| Yes       | 51        | 23.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 54        | 25.59%  |
| Hewlett-Packard                              | 46        | 21.8%   |
| Acer                                         | 37        | 17.54%  |
| ASUSTek Computer                             | 26        | 12.32%  |
| Dell                                         | 23        | 10.9%   |
| Toshiba                                      | 6         | 2.84%   |
| Apple                                        | 4         | 1.9%    |
| Samsung Electronics                          | 2         | 0.95%   |
| HUAWEI                                       | 2         | 0.95%   |
| Fujitsu Siemens                              | 2         | 0.95%   |
| eMachines                                    | 2         | 0.95%   |
| TUXEDO                                       | 1         | 0.47%   |
| System76                                     | 1         | 0.47%   |
| SHENZHEN X&F TECHNOLOGY                      | 1         | 0.47%   |
| Razer                                        | 1         | 0.47%   |
| Notebook                                     | 1         | 0.47%   |
| Medion                                       | 1         | 0.47%   |
| CHUWI Innovation And Technology(ShenZhen)c0. | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-21                        | 4         | 1.9%    |
| Lenovo G710 20252                          | 3         | 1.42%   |
| Acer Aspire A515-51G                       | 3         | 1.42%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.95%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.95%   |
| HP ProBook 450 G7                          | 2         | 0.95%   |
| HP EliteBook 850 G6                        | 2         | 0.95%   |
| HP 2000                                    | 2         | 0.95%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.95%   |
| Dell XPS 13 9310                           | 2         | 0.95%   |
| ASUS X751NV                                | 2         | 0.95%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.95%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.95%   |
| Acer Aspire A715-72G                       | 2         | 0.95%   |
| Acer Aspire 7739G                          | 2         | 0.95%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.47%   |
| Toshiba Satellite P200                     | 1         | 0.47%   |
| Toshiba Satellite L750                     | 1         | 0.47%   |
| Toshiba Satellite L50-B                    | 1         | 0.47%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.47%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.47%   |
| Toshiba Satellite A300                     | 1         | 0.47%   |
| System76 Oryx Pro                          | 1         | 0.47%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.47%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.47%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.47%   |
| Razer Blade                                | 1         | 0.47%   |
| Notebook MAM2080                           | 1         | 0.47%   |
| Medion P6618                               | 1         | 0.47%   |
| Lenovo Z50-70 20354                        | 1         | 0.47%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.47%   |
| Lenovo Y50-70 20378                        | 1         | 0.47%   |
| Lenovo V340-17IWL 81RG                     | 1         | 0.47%   |
| Lenovo ThinkPad X260 20F5S0JF00            | 1         | 0.47%   |
| Lenovo ThinkPad X240 20AMS30A01            | 1         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JSC   | 1         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00   | 1         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS7SE00   | 1         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR005YSC   | 1         | 0.47%   |
| Lenovo ThinkPad W540 20BHS04K00            | 1         | 0.47%   |
| Lenovo ThinkPad T61 6458AU9                | 1         | 0.47%   |
| Lenovo ThinkPad T490s 20NXCTO1WW           | 1         | 0.47%   |
| Lenovo ThinkPad T460 20FMS0X022            | 1         | 0.47%   |
| Lenovo ThinkPad T450s 20BWS2US00           | 1         | 0.47%   |
| Lenovo ThinkPad T440p 20AWS1HK0P           | 1         | 0.47%   |
| Lenovo ThinkPad T440 20B7S14N0U            | 1         | 0.47%   |
| Lenovo ThinkPad T430 2349AK2               | 1         | 0.47%   |
| Lenovo ThinkPad T410 2522DK2               | 1         | 0.47%   |
| Lenovo ThinkPad T15 Gen 1 20S6000USC       | 1         | 0.47%   |
| Lenovo ThinkPad P53 20QNZ4RBUS             | 1         | 0.47%   |
| Lenovo ThinkPad P1 20MES1T700              | 1         | 0.47%   |
| Lenovo ThinkPad L15 Gen 1 20U70001SC       | 1         | 0.47%   |
| Lenovo ThinkPad E590 20NB006MSC            | 1         | 0.47%   |
| Lenovo ThinkPad E580 20KS005ASC            | 1         | 0.47%   |
| Lenovo ThinkPad E15 Gen 3 20YG007KSC       | 1         | 0.47%   |
| Lenovo ThinkPad E15 Gen 3 20YG006CSC       | 1         | 0.47%   |
| Lenovo ThinkPad E14 Gen 2 20T6000RSC       | 1         | 0.47%   |
| Lenovo ThinkBook 15p 20V3                  | 1         | 0.47%   |
| Lenovo ThinkBook 15-IIL 20SM               | 1         | 0.47%   |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Acer Aspire                                        | 32        | 15.17%  |
| Lenovo ThinkPad                                    | 24        | 11.37%  |
| HP ProBook                                         | 10        | 4.74%   |
| HP EliteBook                                       | 10        | 4.74%   |
| ASUS VivoBook                                      | 8         | 3.79%   |
| Toshiba Satellite                                  | 6         | 2.84%   |
| Lenovo IdeaPad                                     | 6         | 2.84%   |
| HP Pavilion                                        | 6         | 2.84%   |
| Dell XPS                                           | 6         | 2.84%   |
| Dell Vostro                                        | 6         | 2.84%   |
| Lenovo ThinkBook                                   | 5         | 2.37%   |
| Lenovo Legion                                      | 5         | 2.37%   |
| Dell Latitude                                      | 5         | 2.37%   |
| HP Laptop                                          | 4         | 1.9%    |
| Dell Inspiron                                      | 4         | 1.9%    |
| Lenovo G710                                        | 3         | 1.42%   |
| HP Compaq                                          | 3         | 1.42%   |
| HP 250                                             | 3         | 1.42%   |
| Acer Swift                                         | 3         | 1.42%   |
| Lenovo B590                                        | 2         | 0.95%   |
| HP OMEN                                            | 2         | 0.95%   |
| HP 2000                                            | 2         | 0.95%   |
| Fujitsu Siemens ESPRIMO                            | 2         | 0.95%   |
| ASUS ZenBook                                       | 2         | 0.95%   |
| ASUS X751NV                                        | 2         | 0.95%   |
| ASUS ROG                                           | 2         | 0.95%   |
| TUXEDO Pulse                                       | 1         | 0.47%   |
| System76 Oryx                                      | 1         | 0.47%   |
| SHENZHEN X&F TECHNOLOGY ST106                      | 1         | 0.47%   |
| Samsung 300E4C                                     | 1         | 0.47%   |
| Samsung 300E4A                                     | 1         | 0.47%   |
| Razer Blade                                        | 1         | 0.47%   |
| Notebook MAM2080                                   | 1         | 0.47%   |
| Medion P6618                                       | 1         | 0.47%   |
| Lenovo Z50-70                                      | 1         | 0.47%   |
| Lenovo Y520-15IKBN                                 | 1         | 0.47%   |
| Lenovo Y50-70                                      | 1         | 0.47%   |
| Lenovo V340-17IWL                                  | 1         | 0.47%   |
| Lenovo G500                                        | 1         | 0.47%   |
| Lenovo G50-45                                      | 1         | 0.47%   |
| Lenovo G50-30                                      | 1         | 0.47%   |
| Lenovo G40-30                                      | 1         | 0.47%   |
| Lenovo B50-70                                      | 1         | 0.47%   |
| HUAWEI WRTB-WXX9                                   | 1         | 0.47%   |
| HUAWEI KLVL-WXX9                                   | 1         | 0.47%   |
| HP ZBook                                           | 1         | 0.47%   |
| HP Presario                                        | 1         | 0.47%   |
| HP Notebook                                        | 1         | 0.47%   |
| HP 255                                             | 1         | 0.47%   |
| HP 2140                                            | 1         | 0.47%   |
| eMachines G725                                     | 1         | 0.47%   |
| eMachines E725                                     | 1         | 0.47%   |
| Dell Precision                                     | 1         | 0.47%   |
| Dell G3                                            | 1         | 0.47%   |
| CHUWI Innovation And Technology(ShenZhen)c0. GemiB | 1         | 0.47%   |
| ASUS X71Sr                                         | 1         | 0.47%   |
| ASUS X705UDR                                       | 1         | 0.47%   |
| ASUS X550JX                                        | 1         | 0.47%   |
| ASUS X540UA                                        | 1         | 0.47%   |
| ASUS X540SAA                                       | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 31        | 14.69%  |
| 2019 | 24        | 11.37%  |
| 2017 | 23        | 10.9%   |
| 2016 | 18        | 8.53%   |
| 2013 | 17        | 8.06%   |
| 2021 | 15        | 7.11%   |
| 2020 | 15        | 7.11%   |
| 2011 | 15        | 7.11%   |
| 2014 | 13        | 6.16%   |
| 2007 | 9         | 4.27%   |
| 2012 | 8         | 3.79%   |
| 2015 | 7         | 3.32%   |
| 2008 | 6         | 2.84%   |
| 2009 | 5         | 2.37%   |
| 2010 | 3         | 1.42%   |
| 2006 | 2         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 211       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 187       | 88.21%  |
| Enabled  | 25        | 11.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 211       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 73        | 33.8%   |
| 8.01-16.0   | 40        | 18.52%  |
| 3.01-4.0    | 38        | 17.59%  |
| 16.01-24.0  | 31        | 14.35%  |
| 32.01-64.0  | 16        | 7.41%   |
| 1.01-2.0    | 10        | 4.63%   |
| 24.01-32.0  | 4         | 1.85%   |
| 2.01-3.0    | 3         | 1.39%   |
| 64.01-256.0 | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 89        | 36.03%  |
| 2.01-3.0   | 61        | 24.7%   |
| 4.01-8.0   | 40        | 16.19%  |
| 3.01-4.0   | 29        | 11.74%  |
| 0.51-1.0   | 13        | 5.26%   |
| 8.01-16.0  | 10        | 4.05%   |
| 0.01-0.5   | 3         | 1.21%   |
| 16.01-24.0 | 2         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 73.97%  |
| 2      | 47        | 21.46%  |
| 3      | 4         | 1.83%   |
| 0      | 3         | 1.37%   |
| 6      | 1         | 0.46%   |
| 5      | 1         | 0.46%   |
| 4      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 66.2%   |
| Yes       | 72        | 33.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 84.91%  |
| No        | 32        | 15.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 99.05%  |
| No        | 2         | 0.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 82.87%  |
| No        | 37        | 17.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 211       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 140       | 58.09%  |
| Split               | 13        | 5.39%   |
| Rijeka              | 12        | 4.98%   |
| Velika Gorica       | 4         | 1.66%   |
| Samobor             | 4         | 1.66%   |
| Pula                | 4         | 1.66%   |
| Zadar               | 3         | 1.24%   |
| Sesvete             | 3         | 1.24%   |
| Osijek              | 3         | 1.24%   |
| ДЊakovec          | 2         | 0.83%   |
| Zabok               | 2         | 0.83%   |
| Krk                 | 2         | 0.83%   |
| Koprivnica          | 2         | 0.83%   |
| Karlovac            | 2         | 0.83%   |
| ZapreÅ¡iÄ‡     | 1         | 0.41%   |
| Vrbovec             | 1         | 0.41%   |
| Vodnjan             | 1         | 0.41%   |
| Vinkovci            | 1         | 0.41%   |
| Vele Mune           | 1         | 0.41%   |
| VaraЕѕdin         | 1         | 0.41%   |
| Varazdinske Toplice | 1         | 0.41%   |
| VaraÅ¾din         | 1         | 0.41%   |
| Trenkovo            | 1         | 0.41%   |
| Suhopolje           | 1         | 0.41%   |
| Slavonski Brod      | 1         | 0.41%   |
| Sinj                | 1         | 0.41%   |
| Prelog              | 1         | 0.41%   |
| Pregrada            | 1         | 0.41%   |
| Postira             | 1         | 0.41%   |
| PoÅ¾ega           | 1         | 0.41%   |
| Opuzen              | 1         | 0.41%   |
| Opatija             | 1         | 0.41%   |
| Novska              | 1         | 0.41%   |
| Nova Raca           | 1         | 0.41%   |
| Nova Gradiska       | 1         | 0.41%   |
| NaÅ¡ice           | 1         | 0.41%   |
| Motovun             | 1         | 0.41%   |
| Mirca               | 1         | 0.41%   |
| Marusevec           | 1         | 0.41%   |
| Krizevci            | 1         | 0.41%   |
| Krapina             | 1         | 0.41%   |
| KorДЌula          | 1         | 0.41%   |
| Klostar Ivanic      | 1         | 0.41%   |
| Kastav              | 1         | 0.41%   |
| Imotski             | 1         | 0.41%   |
| Donje Pazariste     | 1         | 0.41%   |
| Donja Pusca         | 1         | 0.41%   |
| Dekanovec           | 1         | 0.41%   |
| Daruvar             | 1         | 0.41%   |
| Cista Provo         | 1         | 0.41%   |
| Ceminac             | 1         | 0.41%   |
| Budinscina          | 1         | 0.41%   |
| Bogdanovci          | 1         | 0.41%   |
| Bjelovar            | 1         | 0.41%   |
| Bilice              | 1         | 0.41%   |
| Belišće           | 1         | 0.41%   |
| Belica              | 1         | 0.41%   |
| Bapca               | 1         | 0.41%   |
| Å½upanja          | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 42        | 57     | 16.41%  |
| WDC                   | 33        | 40     | 12.89%  |
| Kingston              | 24        | 31     | 9.38%   |
| Seagate               | 22        | 47     | 8.59%   |
| SK Hynix              | 20        | 30     | 7.81%   |
| Toshiba               | 19        | 20     | 7.42%   |
| Sandisk               | 13        | 18     | 5.08%   |
| Micron Technology     | 12        | 13     | 4.69%   |
| Hitachi               | 8         | 8      | 3.13%   |
| HGST                  | 8         | 8      | 3.13%   |
| Crucial               | 8         | 13     | 3.13%   |
| Unknown               | 6         | 6      | 2.34%   |
| Intel                 | 6         | 12     | 2.34%   |
| A-DATA Technology     | 5         | 5      | 1.95%   |
| Fujitsu               | 4         | 4      | 1.56%   |
| Apple                 | 4         | 4      | 1.56%   |
| Transcend             | 2         | 3      | 0.78%   |
| Silicon Motion        | 2         | 5      | 0.78%   |
| LITEON                | 2         | 3      | 0.78%   |
| KingFast              | 2         | 4      | 0.78%   |
| Intenso               | 2         | 3      | 0.78%   |
| Verbatim              | 1         | 1      | 0.39%   |
| UMIS                  | 1         | 1      | 0.39%   |
| StoreJet              | 1         | 1      | 0.39%   |
| Realtek Semiconductor | 1         | 3      | 0.39%   |
| Patriot               | 1         | 1      | 0.39%   |
| Netac                 | 1         | 1      | 0.39%   |
| Mass                  | 1         | 1      | 0.39%   |
| Lite-On               | 1         | 1      | 0.39%   |
| Lenovo                | 1         | 2      | 0.39%   |
| LaCie                 | 1         | 1      | 0.39%   |
| Corsair               | 1         | 1      | 0.39%   |
| AMD                   | 1         | 3      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 2.31%   |
| Sandisk NVMe SSD Drive 512GB            | 5         | 1.92%   |
| Samsung NVMe SSD Drive 512GB            | 5         | 1.92%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.54%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.54%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 1.15%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.15%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.15%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 1.15%   |
| HGST HTS721010A9E630 1TB                | 3         | 1.15%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.77%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.77%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 2         | 0.77%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.77%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.77%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.77%   |
| SK Hynix NVMe SSD Drive 512GB           | 2         | 0.77%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.77%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.77%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.77%   |
| Samsung PM9A1 NVMe 2048GB               | 2         | 0.77%   |
| Samsung PM981 NVMe 512GB                | 2         | 0.77%   |
| Samsung NVMe SSD Drive 256GB            | 2         | 0.77%   |
| Samsung MZNLN256HAJQ-000H1 256GB SSD    | 2         | 0.77%   |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 0.77%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.77%   |
| Micron 1100 SATA 256GB SSD              | 2         | 0.77%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.77%   |
| KingFast 256GB                          | 2         | 0.77%   |
| Intel SSDPEKNW512G8H 512GB              | 2         | 0.77%   |
| Intel SSDPEKKW256G7 256GB               | 2         | 0.77%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 0.77%   |
| HGST HTS541010A9E680 1TB                | 2         | 0.77%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.77%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.77%   |
| A-DATA SU650 240GB SSD                  | 2         | 0.77%   |
| A-DATA SU650 120GB SSD                  | 2         | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.38%   |
| WDC WDS250G2B0B-00YS70 250GB SSD        | 1         | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.38%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.38%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.38%   |
| WDC WD800BEVS-08RST2 80GB               | 1         | 0.38%   |
| WDC WD7500BPVT-80HXZT1 752GB            | 1         | 0.38%   |
| WDC WD7500BPVT-08A1YT1 752GB            | 1         | 0.38%   |
| WDC WD600VE-75HDT0 64GB                 | 1         | 0.38%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 1         | 0.38%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.38%   |
| WDC WD2500BEKT-60PVMT0 250GB            | 1         | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 0.38%   |
| WDC WD10SPZX-75Z10T2 1TB                | 1         | 0.38%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.38%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.38%   |
| WDC WD10S21X-24R 1TB                    | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 27     | 28.05%  |
| Seagate             | 22        | 35     | 26.83%  |
| Toshiba             | 13        | 14     | 15.85%  |
| Hitachi             | 8         | 8      | 9.76%   |
| HGST                | 8         | 8      | 9.76%   |
| Fujitsu             | 4         | 4      | 4.88%   |
| Unknown             | 2         | 2      | 2.44%   |
| Samsung Electronics | 1         | 2      | 1.22%   |
| Intenso             | 1         | 2      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 21        | 25     | 23.33%  |
| Samsung Electronics | 16        | 25     | 17.78%  |
| Micron Technology   | 10        | 11     | 11.11%  |
| Crucial             | 8         | 13     | 8.89%   |
| SK Hynix            | 6         | 11     | 6.67%   |
| SanDisk             | 6         | 10     | 6.67%   |
| WDC                 | 5         | 5      | 5.56%   |
| A-DATA Technology   | 5         | 5      | 5.56%   |
| Apple               | 4         | 4      | 4.44%   |
| Transcend           | 1         | 2      | 1.11%   |
| Toshiba             | 1         | 1      | 1.11%   |
| StoreJet            | 1         | 1      | 1.11%   |
| Patriot             | 1         | 1      | 1.11%   |
| Netac               | 1         | 1      | 1.11%   |
| LITEON              | 1         | 2      | 1.11%   |
| Intenso             | 1         | 1      | 1.11%   |
| Intel               | 1         | 2      | 1.11%   |
| AMD                 | 1         | 3      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 84        | 123    | 34.15%  |
| HDD     | 80        | 102    | 32.52%  |
| NVMe    | 73        | 104    | 29.67%  |
| Unknown | 6         | 19     | 2.44%   |
| MMC     | 3         | 3      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 146       | 217    | 63.2%   |
| NVMe | 73        | 104    | 31.6%   |
| SAS  | 9         | 27     | 3.9%    |
| MMC  | 3         | 3      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 149    | 66.67%  |
| 0.51-1.0   | 48        | 62     | 28.57%  |
| 1.01-2.0   | 7         | 12     | 4.17%   |
| 3.01-4.0   | 1         | 2      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 31.39%  |
| 251-500        | 52        | 23.32%  |
| 501-1000       | 35        | 15.7%   |
| 1001-2000      | 23        | 10.31%  |
| 51-100         | 15        | 6.73%   |
| 1-20           | 11        | 4.93%   |
| 21-50          | 7         | 3.14%   |
| Unknown        | 6         | 2.69%   |
| More than 3000 | 2         | 0.9%    |
| 2001-3000      | 2         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 78        | 32.23%  |
| 21-50          | 57        | 23.55%  |
| 51-100         | 31        | 12.81%  |
| 101-250        | 26        | 10.74%  |
| 501-1000       | 21        | 8.68%   |
| 251-500        | 18        | 7.44%   |
| Unknown        | 6         | 2.48%   |
| 1001-2000      | 4         | 1.65%   |
| More than 3000 | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 7.14%   |
| WDC WD600VE-75HDT0 64GB             | 1         | 1      | 7.14%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 7.14%   |
| Toshiba MK6459GSXP 640GB            | 1         | 1      | 7.14%   |
| Seagate ST9250827AS 250GB           | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 7.14%   |
| SanDisk SDSSDXPS960G 960GB          | 1         | 1      | 7.14%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD | 1         | 1      | 7.14%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 7.14%   |
| Crucial CT1024M550SSD1 1024GB       | 1         | 1      | 7.14%   |
| A-DATA Technology SU630 240GB SSD   | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 23.08%  |
| HGST              | 3         | 3      | 23.08%  |
| Seagate           | 2         | 2      | 15.38%  |
| Toshiba           | 1         | 1      | 7.69%   |
| SanDisk           | 1         | 2      | 7.69%   |
| Hitachi           | 1         | 1      | 7.69%   |
| Crucial           | 1         | 1      | 7.69%   |
| A-DATA Technology | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Seagate | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 75%     |
| SSD  | 3         | 5      | 25%     |

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
| Detected | 130       | 216    | 58.04%  |
| Works    | 82        | 121    | 36.61%  |
| Malfunc  | 12        | 14     | 5.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 58.24%  |
| AMD                              | 29        | 11.11%  |
| Samsung Electronics              | 27        | 10.34%  |
| SK Hynix                         | 14        | 5.36%   |
| Sandisk                          | 12        | 4.6%    |
| Toshiba America Info Systems     | 6         | 2.3%    |
| Kingston Technology Company      | 3         | 1.15%   |
| Silicon Motion                   | 2         | 0.77%   |
| Silicon Integrated Systems [SiS] | 2         | 0.77%   |
| Nvidia                           | 2         | 0.77%   |
| Micron Technology                | 2         | 0.77%   |
| Lite-On Technology               | 2         | 0.77%   |
| VIA Technologies                 | 1         | 0.38%   |
| Union Memory (Shenzhen)          | 1         | 0.38%   |
| Realtek Semiconductor            | 1         | 0.38%   |
| Phison Electronics               | 1         | 0.38%   |
| Marvell Technology Group         | 1         | 0.38%   |
| Lenovo                           | 1         | 0.38%   |
| KIOXIA                           | 1         | 0.38%   |
| JMicron Technology               | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 10.07%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 9.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 5.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 4.68%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 3.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 3.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.52%   |
| SK Hynix Gold P31 SSD                                                            | 6         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.16%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 5         | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.8%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.44%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 1.08%   |
| SK Hynix BC511                                                                   | 3         | 1.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.72%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.72%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.72%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.72%   |
| Samsung Electronics SATA controller                                              | 2         | 0.72%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.72%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.72%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.72%   |
| Intel SSD 660P Series                                                            | 2         | 0.72%   |
| Intel SSD 600P Series                                                            | 2         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.36%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.36%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.36%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.36%   |
| Sandisk WD Black NVMe SSD                                                        | 1         | 0.36%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.36%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.36%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.36%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.36%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.36%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.36%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 163       | 61.05%  |
| NVMe | 74        | 27.72%  |
| IDE  | 20        | 7.49%   |
| RAID | 10        | 3.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 81.04%  |
| AMD    | 40        | 18.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 4.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 4.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 3.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 2.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 4         | 1.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.9%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.9%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.42%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.42%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.42%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.95%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.95%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.95%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.95%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.95%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.95%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.95%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.95%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.95%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.95%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 2         | 0.95%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 2         | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.95%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.95%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.95%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.95%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 0.95%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.95%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.95%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.47%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.47%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 1         | 0.47%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.47%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.47%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.47%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.47%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.47%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 0.47%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 61        | 28.91%  |
| Intel Core i7           | 38        | 18.01%  |
| Intel Core i3           | 17        | 8.06%   |
| Intel Pentium           | 14        | 6.64%   |
| AMD Ryzen 5             | 14        | 6.64%   |
| Intel Core 2 Duo        | 12        | 5.69%   |
| Other                   | 8         | 3.79%   |
| AMD Ryzen 7             | 8         | 3.79%   |
| Intel Celeron           | 5         | 2.37%   |
| Intel Pentium Silver    | 4         | 1.9%    |
| Intel Pentium Dual      | 4         | 1.9%    |
| AMD Ryzen 3             | 4         | 1.9%    |
| AMD A6                  | 4         | 1.9%    |
| Intel Core i9           | 3         | 1.42%   |
| Intel Pentium M         | 2         | 0.95%   |
| Intel Pentium Dual-Core | 2         | 0.95%   |
| Intel Atom              | 2         | 0.95%   |
| AMD Ryzen 9             | 2         | 0.95%   |
| AMD E1                  | 2         | 0.95%   |
| AMD E                   | 2         | 0.95%   |
| Intel Celeron M         | 1         | 0.47%   |
| AMD Turion 64 X2 Mobile | 1         | 0.47%   |
| AMD A4                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 50.24%  |
| 4      | 74        | 35.07%  |
| 6      | 15        | 7.11%   |
| 8      | 12        | 5.69%   |
| 1      | 4         | 1.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 149       | 70.62%  |
| 1      | 62        | 29.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 200       | 93.9%   |
| Unknown        | 9         | 4.23%   |
| 32-bit         | 4         | 1.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 18.47%  |
| 0x806ea    | 14        | 6.31%   |
| 0x306c3    | 13        | 5.86%   |
| 0x806e9    | 12        | 5.41%   |
| 0x306a9    | 11        | 4.95%   |
| 0x906ea    | 10        | 4.5%    |
| 0x806ec    | 10        | 4.5%    |
| 0x6fd      | 8         | 3.6%    |
| 0x40651    | 7         | 3.15%   |
| 0x206a7    | 6         | 2.7%    |
| 0x0a50000c | 6         | 2.7%    |
| 0x306d4    | 5         | 2.25%   |
| 0x06006705 | 5         | 2.25%   |
| 0x806c1    | 4         | 1.8%    |
| 0x406e3    | 4         | 1.8%    |
| 0x30678    | 4         | 1.8%    |
| 0x1067a    | 4         | 1.8%    |
| 0x08600106 | 4         | 1.8%    |
| 0x08108109 | 4         | 1.8%    |
| 0x0810100b | 4         | 1.8%    |
| 0x706e5    | 3         | 1.35%   |
| 0x706a1    | 3         | 1.35%   |
| 0x506c9    | 3         | 1.35%   |
| 0x20655    | 3         | 1.35%   |
| 0x08608103 | 3         | 1.35%   |
| 0x05000119 | 3         | 1.35%   |
| 0x906ed    | 2         | 0.9%    |
| 0x906e9    | 2         | 0.9%    |
| 0x806eb    | 2         | 0.9%    |
| 0x6fb      | 2         | 0.9%    |
| 0x6d8      | 2         | 0.9%    |
| 0x406c4    | 2         | 0.9%    |
| 0x10676    | 2         | 0.9%    |
| 0x08600103 | 2         | 0.9%    |
| 0xa0652    | 1         | 0.45%   |
| 0x906c0    | 1         | 0.45%   |
| 0x6fa      | 1         | 0.45%   |
| 0x6e8      | 1         | 0.45%   |
| 0x506e3    | 1         | 0.45%   |
| 0x40661    | 1         | 0.45%   |
| 0x106c2    | 1         | 0.45%   |
| 0x08608102 | 1         | 0.45%   |
| 0x08600104 | 1         | 0.45%   |
| 0x08108102 | 1         | 0.45%   |
| 0x07030105 | 1         | 0.45%   |
| 0x06006704 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 61        | 28.91%  |
| Haswell       | 23        | 10.9%   |
| IvyBridge     | 15        | 7.11%   |
| Core          | 11        | 5.21%   |
| Zen 2         | 8         | 3.79%   |
| Silvermont    | 8         | 3.79%   |
| Zen 3         | 7         | 3.32%   |
| Skylake       | 7         | 3.32%   |
| SandyBridge   | 7         | 3.32%   |
| Penryn        | 7         | 3.32%   |
| TigerLake     | 6         | 2.84%   |
| Excavator     | 6         | 2.84%   |
| Broadwell     | 6         | 2.84%   |
| Zen+          | 5         | 2.37%   |
| Zen           | 4         | 1.9%    |
| Westmere      | 4         | 1.9%    |
| Goldmont plus | 4         | 1.9%    |
| Unknown       | 4         | 1.9%    |
| P6            | 3         | 1.42%   |
| IceLake       | 3         | 1.42%   |
| Goldmont      | 3         | 1.42%   |
| Bobcat        | 3         | 1.42%   |
| Tremont       | 1         | 0.47%   |
| Puma          | 1         | 0.47%   |
| K8 Hammer     | 1         | 0.47%   |
| Jaguar        | 1         | 0.47%   |
| CometLake     | 1         | 0.47%   |
| Bonnell       | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 53.52%  |
| Nvidia                           | 72        | 25.35%  |
| AMD                              | 57        | 20.07%  |
| Silicon Integrated Systems [SiS] | 2         | 0.7%    |
| VIA Technologies                 | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 17        | 5.84%   |
| Intel HD Graphics 620                                                                    | 13        | 4.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 4.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 2.75%   |
| AMD Renoir                                                                               | 7         | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 2.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.72%   |
| AMD Cezanne                                                                              | 5         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.37%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.37%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.37%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.37%   |
| AMD Lucienne                                                                             | 4         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.03%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.03%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.03%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 1.03%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 1.03%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 1.03%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.69%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.69%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.69%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.69%   |
| Intel HD Graphics 630                                                                    | 2         | 0.69%   |
| Intel HD Graphics 530                                                                    | 2         | 0.69%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.69%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.34%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.34%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.34%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.34%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.34%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.34%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.34%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 40.76%  |
| Intel + Nvidia | 51        | 24.17%  |
| 1 x AMD        | 31        | 14.69%  |
| Intel + AMD    | 15        | 7.11%   |
| 1 x Nvidia     | 14        | 6.64%   |
| AMD + Nvidia   | 7         | 3.32%   |
| 2 x AMD        | 4         | 1.9%    |
| 1 x SiS        | 2         | 0.95%   |
| 1 x VIA        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 167       | 78.77%  |
| Proprietary | 37        | 17.45%  |
| Unknown     | 8         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 54.55%  |
| 1.01-2.0   | 32        | 14.55%  |
| 3.01-4.0   | 26        | 11.82%  |
| 0.01-0.5   | 26        | 11.82%  |
| 0.51-1.0   | 11        | 5%      |
| 7.01-8.0   | 3         | 1.36%   |
| 5.01-6.0   | 1         | 0.45%   |
| 2.01-3.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 40        | 16.33%  |
| AU Optronics            | 38        | 15.51%  |
| BOE                     | 35        | 14.29%  |
| Chimei Innolux          | 34        | 13.88%  |
| Samsung Electronics     | 26        | 10.61%  |
| Dell                    | 19        | 7.76%   |
| Sharp                   | 7         | 2.86%   |
| Goldstar                | 5         | 2.04%   |
| Lenovo                  | 4         | 1.63%   |
| Chi Mei Optoelectronics | 4         | 1.63%   |
| Apple                   | 4         | 1.63%   |
| PANDA                   | 3         | 1.22%   |
| LG Philips              | 3         | 1.22%   |
| CSO                     | 3         | 1.22%   |
| Quanta Display          | 2         | 0.82%   |
| Hewlett-Packard         | 2         | 0.82%   |
| BenQ                    | 2         | 0.82%   |
| AOC                     | 2         | 0.82%   |
| Philips                 | 1         | 0.41%   |
| Panasonic               | 1         | 0.41%   |
| NCS                     | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| Iiyama                  | 1         | 0.41%   |
| IBM                     | 1         | 0.41%   |
| Grundig                 | 1         | 0.41%   |
| Fujitsu Siemens         | 1         | 0.41%   |
| BOE Technology Group    | 1         | 0.41%   |
| Achieva Shimian         | 1         | 0.41%   |
| Acer                    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 2.01%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.61%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 1.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.61%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 1.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 1.2%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.8%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch      | 2         | 0.8%    |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.8%    |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.8%    |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.8%    |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.8%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.8%    |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 2         | 0.8%    |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.8%    |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                     | 2         | 0.8%    |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 2         | 0.8%    |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                         | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.8%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 2         | 0.8%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.4%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.4%    |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch         | 1         | 0.4%    |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch         | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0626 1920x1080                          | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0486 1600x900                           | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM021D 1680x1050 433x271mm 20.1-inch      | 1         | 0.4%    |
| Samsung Electronics S23B300 SAM08CA 1920x1080 510x287mm 23.0-inch         | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch     | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 113       | 49.78%  |
| 1366x768 (WXGA)    | 43        | 18.94%  |
| 1600x900 (HD+)     | 21        | 9.25%   |
| 3840x2160 (4K)     | 9         | 3.96%   |
| 2560x1440 (QHD)    | 9         | 3.96%   |
| 1440x900 (WXGA+)   | 7         | 3.08%   |
| 1280x800 (WXGA)    | 6         | 2.64%   |
| 1680x1050 (WSXGA+) | 4         | 1.76%   |
| 2160x1440          | 3         | 1.32%   |
| 3840x2400          | 2         | 0.88%   |
| 2560x1600          | 2         | 0.88%   |
| 1920x1200 (WUXGA)  | 2         | 0.88%   |
| 1400x1050          | 2         | 0.88%   |
| 2880x1800          | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |
| 1280x1024 (SXGA)   | 1         | 0.44%   |
| 1024x576           | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 113       | 45.93%  |
| 17      | 35        | 14.23%  |
| 13      | 22        | 8.94%   |
| 14      | 19        | 7.72%   |
| 27      | 13        | 5.28%   |
| 24      | 10        | 4.07%   |
| 23      | 7         | 2.85%   |
| 12      | 5         | 2.03%   |
| 31      | 4         | 1.63%   |
| 21      | 4         | 1.63%   |
| 16      | 3         | 1.22%   |
| Unknown | 3         | 1.22%   |
| 54      | 2         | 0.81%   |
| 20      | 2         | 0.81%   |
| 11      | 2         | 0.81%   |
| 18      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 137       | 56.38%  |
| 351-400     | 38        | 15.64%  |
| 501-600     | 24        | 9.88%   |
| 201-300     | 24        | 9.88%   |
| 401-500     | 8         | 3.29%   |
| 601-700     | 7         | 2.88%   |
| Unknown     | 3         | 1.23%   |
| 1001-1500   | 2         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 175       | 84.13%  |
| 16/10   | 24        | 11.54%  |
| 3/2     | 4         | 1.92%   |
| 4/3     | 3         | 1.44%   |
| 5/4     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 114       | 46.34%  |
| 121-130        | 30        | 12.2%   |
| 81-90          | 29        | 11.79%  |
| 201-250        | 15        | 6.1%    |
| 301-350        | 13        | 5.28%   |
| 71-80          | 11        | 4.47%   |
| 151-200        | 6         | 2.44%   |
| 61-70          | 4         | 1.63%   |
| 351-500        | 4         | 1.63%   |
| 131-140        | 4         | 1.63%   |
| Unknown        | 3         | 1.22%   |
| More than 1000 | 2         | 0.81%   |
| 51-60          | 2         | 0.81%   |
| 251-300        | 2         | 0.81%   |
| 141-150        | 2         | 0.81%   |
| 111-120        | 2         | 0.81%   |
| 91-100         | 2         | 0.81%   |
| 41-50          | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 113       | 47.08%  |
| 101-120       | 65        | 27.08%  |
| 51-100        | 40        | 16.67%  |
| 161-240       | 13        | 5.42%   |
| More than 240 | 4         | 1.67%   |
| Unknown       | 3         | 1.25%   |
| 1-50          | 2         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 167       | 75.23%  |
| 2     | 41        | 18.47%  |
| 0     | 9         | 4.05%   |
| 3     | 4         | 1.8%    |
| 4     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 35.55%  |
| Intel                             | 107       | 30.92%  |
| Qualcomm Atheros                  | 60        | 17.34%  |
| Broadcom                          | 19        | 5.49%   |
| MEDIATEK                          | 7         | 2.02%   |
| Broadcom Limited                  | 4         | 1.16%   |
| Samsung Electronics               | 3         | 0.87%   |
| Xiaomi                            | 2         | 0.58%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.58%   |
| Qualcomm Atheros Communications   | 2         | 0.58%   |
| Qualcomm                          | 2         | 0.58%   |
| Marvell Technology Group          | 2         | 0.58%   |
| Lenovo                            | 2         | 0.58%   |
| D-Link                            | 2         | 0.58%   |
| VIA Technologies                  | 1         | 0.29%   |
| TP-Link                           | 1         | 0.29%   |
| Ralink                            | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| HTC (High Tech Computer)          | 1         | 0.29%   |
| Hewlett-Packard                   | 1         | 0.29%   |
| Fibocom                           | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 94        | 23.15%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.93%   |
| Intel Wireless 8265 / 8275                                              | 16        | 3.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 3.2%    |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.48%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.48%   |
| Intel Wireless 7260                                                     | 6         | 1.48%   |
| Intel Wireless 3165                                                     | 6         | 1.48%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 1.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.23%   |
| Intel Wireless 7265                                                     | 5         | 1.23%   |
| Intel Wireless 3160                                                     | 5         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.99%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.74%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.74%   |
| Intel WiFi Link 5100                                                    | 3         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.74%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.74%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.49%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.49%   |
| Lenovo USB-C Dock Ethernet                                              | 2         | 0.49%   |
| Intel Wireless 8260                                                     | 2         | 0.49%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.49%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.49%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.49%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.49%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 2         | 0.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.49%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.25%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 49.53%  |
| Qualcomm Atheros                | 53        | 24.77%  |
| Realtek Semiconductor           | 24        | 11.21%  |
| Broadcom                        | 13        | 6.07%   |
| MEDIATEK                        | 7         | 3.27%   |
| Qualcomm Atheros Communications | 2         | 0.93%   |
| Qualcomm                        | 2         | 0.93%   |
| D-Link                          | 2         | 0.93%   |
| Broadcom Limited                | 2         | 0.93%   |
| TP-Link                         | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Fibocom                         | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 9.35%   |
| Intel Wireless 8265 / 8275                                              | 16        | 7.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 6.07%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 5.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.8%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.8%    |
| Intel Wireless 7260                                                     | 6         | 2.8%    |
| Intel Wireless 3165                                                     | 6         | 2.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 2.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.34%   |
| Intel Wireless 7265                                                     | 5         | 2.34%   |
| Intel Wireless 3160                                                     | 5         | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.4%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.4%    |
| Intel WiFi Link 5100                                                    | 3         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.4%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.93%   |
| Intel Wireless 8260                                                     | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.93%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.93%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.93%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.47%   |
| Realtek Realtek Network controller                                      | 1         | 0.47%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.47%   |
| Qualcomm Atheros AR5523                                                 | 1         | 0.47%   |
| MediaTek WiFi                                                           | 1         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.47%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 0.47%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.47%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.47%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.47%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.47%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.47%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 0.47%   |
| D-Link WLAN controller                                                  | 1         | 0.47%   |
| D-Link 802.11 n WLAN                                                    | 1         | 0.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 116       | 61.38%  |
| Intel                            | 34        | 17.99%  |
| Qualcomm Atheros                 | 16        | 8.47%   |
| Broadcom                         | 6         | 3.17%   |
| Samsung Electronics              | 3         | 1.59%   |
| Xiaomi                           | 2         | 1.06%   |
| Silicon Integrated Systems [SiS] | 2         | 1.06%   |
| Marvell Technology Group         | 2         | 1.06%   |
| Lenovo                           | 2         | 1.06%   |
| Broadcom Limited                 | 2         | 1.06%   |
| VIA Technologies                 | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| HTC (High Tech Computer)         | 1         | 0.53%   |
| ASIX Electronics                 | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 49.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.7%    |
| Intel Ethernet Connection (4) I219-V                              | 6         | 3.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 2.12%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.12%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.06%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.06%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.53%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.53%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.53%   |
| HTC (High Tech Computer) MT65xx Android Phone                     | 1         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.53%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.53%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 53.32%  |
| Ethernet | 180       | 45.92%  |
| Modem    | 3         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 65.71%  |
| Ethernet | 95        | 33.93%  |
| Modem    | 1         | 0.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 79.62%  |
| 1     | 42        | 19.91%  |
| 0     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 205       | 96.7%   |
| Yes  | 7         | 3.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 46.93%  |
| Qualcomm Atheros Communications | 19        | 10.61%  |
| Lite-On Technology              | 19        | 10.61%  |
| Realtek Semiconductor           | 13        | 7.26%   |
| IMC Networks                    | 13        | 7.26%   |
| Foxconn / Hon Hai               | 7         | 3.91%   |
| Broadcom                        | 6         | 3.35%   |
| Hewlett-Packard                 | 5         | 2.79%   |
| Apple                           | 4         | 2.23%   |
| Toshiba                         | 3         | 1.68%   |
| Foxconn International           | 2         | 1.12%   |
| Cambridge Silicon Radio         | 2         | 1.12%   |
| Realtek                         | 1         | 0.56%   |
| Dell                            | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 41        | 22.91%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 7.82%   |
| Intel AX200 Bluetooth                               | 12        | 6.7%    |
| Realtek Bluetooth Radio                             | 10        | 5.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 5.03%   |
| Intel AX201 Bluetooth                               | 9         | 5.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.91%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 3.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.68%   |
| IMC Networks Wireless_Device                        | 3         | 1.68%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.12%   |
| Lite-On Bluetooth Device                            | 2         | 1.12%   |
| IMC Networks Bluetooth Device                       | 2         | 1.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.12%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.12%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.12%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.56%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.56%   |
| Toshiba Bluetooth Device                            | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.56%   |
| Realtek Bluetooth Radio                             | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.56%   |
| Lite-On Wireless_Device                             | 1         | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.56%   |
| Intel Bluetooth Device                              | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.56%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.56%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter          | 1         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.56%   |
| Apple Bluetooth Host Controller                     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 166       | 63.6%   |
| AMD                              | 44        | 16.86%  |
| Nvidia                           | 28        | 10.73%  |
| Logitech                         | 3         | 1.15%   |
| Lenovo                           | 3         | 1.15%   |
| JMTek                            | 3         | 1.15%   |
| C-Media Electronics              | 3         | 1.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.77%   |
| ZOOM                             | 1         | 0.38%   |
| VIA Technologies                 | 1         | 0.38%   |
| Trust                            | 1         | 0.38%   |
| Texas Instruments                | 1         | 0.38%   |
| SteelSeries ApS                  | 1         | 0.38%   |
| Realtek Semiconductor            | 1         | 0.38%   |
| Plantronics                      | 1         | 0.38%   |
| Pioneer DJ                       | 1         | 0.38%   |
| GN Netcom                        | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 11.29%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 8.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 3.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.19%   |
| Nvidia Audio device                                                                               | 6         | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.88%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 1.88%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.25%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 3         | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.94%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.94%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.63%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.63%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.63%   |
| C-Media Electronics Audio Adapter                                                                 | 2         | 0.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.63%   |
| ZOOM U-22                                                                                         | 1         | 0.31%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.31%   |
| Trust GXT 232 Microphone                                                                          | 1         | 0.31%   |
| Texas Instruments PCM2900B Audio CODEC                                                            | 1         | 0.31%   |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 1         | 0.31%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.31%   |
| Plantronics BT600                                                                                 | 1         | 0.31%   |
| Pioneer DJ DDJ-SB2                                                                                | 1         | 0.31%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.31%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.31%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.31%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.31%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.31%   |
| Logitech 960 Headset                                                                              | 1         | 0.31%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 0.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.31%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.31%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 31.16%  |
| SK Hynix            | 28        | 20.29%  |
| Kingston            | 23        | 16.67%  |
| Micron Technology   | 20        | 14.49%  |
| Crucial             | 7         | 5.07%   |
| Unknown             | 5         | 3.62%   |
| Ramaxel Technology  | 3         | 2.17%   |
| Patriot             | 2         | 1.45%   |
| A-DATA Technology   | 2         | 1.45%   |
| Transcend           | 1         | 0.72%   |
| Qimonda             | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| Corsair             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 3.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 2.65%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 3         | 1.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.99%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 3         | 1.99%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 1.32%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.32%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.32%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.32%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 2         | 1.32%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.32%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 2         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s            | 2         | 1.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.32%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 1.32%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s             | 2         | 1.32%   |
| Kingston RAM 9905700-047.A00G 16384MB SODIMM DDR4 2667MT/s          | 2         | 1.32%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.66%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.66%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.66%   |
| Transcend RAM TS128MSQ64V6J 1024MB SODIMM DDR2 667MT/s              | 1         | 0.66%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.66%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.66%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.66%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1066MT/s                          | 1         | 0.66%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 1         | 0.66%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                    | 1         | 0.66%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s             | 1         | 0.66%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM 1600MT/s                | 1         | 0.66%   |
| SK Hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.66%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.66%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s       | 1         | 0.66%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.66%   |
| SK Hynix RAM GKE160SO102408-3000 16384MB SODIMM DDR4 3000MT/s       | 1         | 0.66%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s              | 1         | 0.66%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.66%   |
| Samsung RAM Module 1024MB SODIMM DDR2 533MT/s                       | 1         | 0.66%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| Samsung RAM M471B1G73BH0-CK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 59        | 51.3%   |
| DDR3   | 36        | 31.3%   |
| LPDDR3 | 7         | 6.09%   |
| DDR2   | 7         | 6.09%   |
| LPDDR4 | 5         | 4.35%   |
| SDRAM  | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 86.09%  |
| Row Of Chips | 14        | 12.17%  |
| DIMM         | 1         | 0.87%   |
| Chip         | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 50        | 39.68%  |
| 4096  | 40        | 31.75%  |
| 16384 | 19        | 15.08%  |
| 2048  | 9         | 7.14%   |
| 1024  | 5         | 3.97%   |
| 32768 | 3         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 33        | 26.61%  |
| 1600  | 29        | 23.39%  |
| 3200  | 21        | 16.94%  |
| 2133  | 9         | 7.26%   |
| 2400  | 8         | 6.45%   |
| 667   | 5         | 4.03%   |
| 1334  | 4         | 3.23%   |
| 1333  | 4         | 3.23%   |
| 4267  | 2         | 1.61%   |
| 4266  | 1         | 0.81%   |
| 3266  | 1         | 0.81%   |
| 3000  | 1         | 0.81%   |
| 2048  | 1         | 0.81%   |
| 1867  | 1         | 0.81%   |
| 1067  | 1         | 0.81%   |
| 1066  | 1         | 0.81%   |
| 975   | 1         | 0.81%   |
| 533   | 1         | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Canon               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Composite Device        | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| HP Deskjet 1050 J410            | 1         | 20%     |
| Canon PIXMA iP4300 Printer      | 1         | 20%     |
| Canon LBP6670 UFR II            | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Ultima Artec Ultima 2000 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 57        | 28.93%  |
| IMC Networks                           | 24        | 12.18%  |
| Realtek Semiconductor                  | 19        | 9.64%   |
| Quanta                                 | 18        | 9.14%   |
| Microdia                               | 13        | 6.6%    |
| Acer                                   | 11        | 5.58%   |
| Suyin                                  | 9         | 4.57%   |
| Lite-On Technology                     | 8         | 4.06%   |
| Syntek                                 | 7         | 3.55%   |
| Sunplus Innovation Technology          | 6         | 3.05%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.05%   |
| Luxvisions Innotech Limited            | 3         | 1.52%   |
| Apple                                  | 3         | 1.52%   |
| Silicon Motion                         | 2         | 1.02%   |
| Primax Electronics                     | 2         | 1.02%   |
| Logitech                               | 2         | 1.02%   |
| Anker                                  | 2         | 1.02%   |
| Jieli Technology                       | 1         | 0.51%   |
| Goertek Electronics                    | 1         | 0.51%   |
| Genesys Logic                          | 1         | 0.51%   |
| Cubeternet                             | 1         | 0.51%   |
| AVerMedia Technologies                 | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 6.09%   |
| Chicony HD WebCam                                   | 11        | 5.58%   |
| IMC Networks Integrated Camera                      | 8         | 4.06%   |
| Quanta VGA WebCam                                   | 7         | 3.55%   |
| Microdia Integrated_Webcam_HD                       | 7         | 3.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 3.55%   |
| Lite-On HP HD Camera                                | 5         | 2.54%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.03%   |
| Quanta HD Webcam                                    | 4         | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.03%   |
| Acer Lenovo EasyCamera                              | 4         | 2.03%   |
| Syntek Integrated Camera                            | 3         | 1.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.52%   |
| Realtek Integrated Webcam                           | 3         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.52%   |
| Chicony Integrated HP HD Webcam                     | 3         | 1.52%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.52%   |
| Chicony HP Webcam                                   | 3         | 1.52%   |
| Suyin WebCam                                        | 2         | 1.02%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.02%   |
| Sunplus HD WebCam                                   | 2         | 1.02%   |
| Realtek USB Camera                                  | 2         | 1.02%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.02%   |
| Realtek EasyCamera                                  | 2         | 1.02%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.02%   |
| Quanta HP HD Camera                                 | 2         | 1.02%   |
| Quanta HD User Facing                               | 2         | 1.02%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.02%   |
| Lite-On Integrated Camera                           | 2         | 1.02%   |
| IMC Networks HD Camera                              | 2         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.02%   |
| Chicony USB 2.0 Camera                              | 2         | 1.02%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 1.02%   |
| Chicony EasyCamera                                  | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.02%   |
| Anker PowerConf C300                                | 2         | 1.02%   |
| Acer Lenovo Integrated Webcam                       | 2         | 1.02%   |
| Acer Integrated Camera                              | 2         | 1.02%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.51%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.51%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.51%   |
| Syntek EasyCamera                                   | 1         | 0.51%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.51%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.51%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.51%   |
| Sunplus Integrated Camera                           | 1         | 0.51%   |
| Sunplus ASUS Webcam                                 | 1         | 0.51%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.51%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.51%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.51%   |
| Realtek VGA WebCam                                  | 1         | 0.51%   |
| Realtek Integrated Webcam_HD                        | 1         | 0.51%   |
| Realtek HP Truevision HD                            | 1         | 0.51%   |
| Realtek HD WebCam                                   | 1         | 0.51%   |
| Quanta HP Webcam                                    | 1         | 0.51%   |
| Microdia Webcam Vitade AF                           | 1         | 0.51%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 33.33%  |
| Validity Sensors           | 13        | 27.08%  |
| Shenzhen Goodix Technology | 9         | 18.75%  |
| Upek                       | 3         | 6.25%   |
| Elan Microelectronics      | 3         | 6.25%   |
| LighTuning Technology      | 2         | 4.17%   |
| STMicroelectronics         | 1         | 2.08%   |
| AuthenTec                  | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 14.58%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 3         | 6.25%   |
| Unknown                                                                    | 3         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 4.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 4.17%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 4.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.08%   |
| Validity Sensors VFS491                                                    | 1         | 2.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.08%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.08%   |
| Synaptics  WBDI                                                            | 1         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.08%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 66.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 4         | 66.67%  |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 16.67%  |
| Lenovo Integrated Smart Card Reader               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 135       | 61.64%  |
| 1     | 67        | 30.59%  |
| 2     | 15        | 6.85%   |
| 3     | 2         | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 46.53%  |
| Graphics card            | 22        | 21.78%  |
| Net/wireless             | 10        | 9.9%    |
| Multimedia controller    | 6         | 5.94%   |
| Chipcard                 | 5         | 4.95%   |
| Card reader              | 3         | 2.97%   |
| Communication controller | 2         | 1.98%   |
| Camera                   | 2         | 1.98%   |
| Storage/ide              | 1         | 0.99%   |
| Storage                  | 1         | 0.99%   |
| Sound                    | 1         | 0.99%   |
| Modem                    | 1         | 0.99%   |

