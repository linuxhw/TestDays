Xubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

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

Total: 139

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.15.0-47-generic            | 19        | 16.24%  |
| 5.15.0-48-generic            | 16        | 13.68%  |
| 5.15.0-25-generic            | 11        | 9.4%    |
| 5.15.0-52-generic            | 8         | 6.84%   |
| 5.15.0-46-generic            | 8         | 6.84%   |
| 5.15.0-27-generic            | 7         | 5.98%   |
| 5.15.0-50-generic            | 5         | 4.27%   |
| 5.15.0-40-generic            | 5         | 4.27%   |
| 5.15.0-39-generic            | 5         | 4.27%   |
| 5.15.0-35-generic            | 5         | 4.27%   |
| 5.15.0-41-generic            | 4         | 3.42%   |
| 5.15.0-43-generic            | 3         | 2.56%   |
| 5.15.0-37-generic            | 3         | 2.56%   |
| 5.17.0-1013-oem              | 2         | 1.71%   |
| 5.15.0-33-generic            | 2         | 1.71%   |
| 5.4.0-126-generic            | 1         | 0.85%   |
| 5.19.5-051905-generic        | 1         | 0.85%   |
| 5.19.0-051900-generic        | 1         | 0.85%   |
| 5.18.0-10.1-liquorix-amd64   | 1         | 0.85%   |
| 5.17.3-051703-generic        | 1         | 0.85%   |
| 5.17.0-ashpy3-lyesdef        | 1         | 0.85%   |
| 5.17.0-1015-oem              | 1         | 0.85%   |
| 5.15.0-50-lowlatency         | 1         | 0.85%   |
| 5.15.0-48-lowlatency         | 1         | 0.85%   |
| 5.15.0-46-lowlatency         | 1         | 0.85%   |
| 5.15.0-30-generic            | 1         | 0.85%   |
| 5.15.0-27-lowlatency         | 1         | 0.85%   |
| 5.15.0-1011-intel-iotg       | 1         | 0.85%   |
| 4.19.241-13212-ge9b0bab46475 | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 105       | 91.3%   |
| 5.17.0   | 4         | 3.48%   |
| 5.4.0    | 1         | 0.87%   |
| 5.19.5   | 1         | 0.87%   |
| 5.19.0   | 1         | 0.87%   |
| 5.18.0   | 1         | 0.87%   |
| 5.17.3   | 1         | 0.87%   |
| 4.19.241 | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 105       | 91.3%   |
| 5.17    | 5         | 4.35%   |
| 5.19    | 2         | 1.74%   |
| 5.4     | 1         | 0.87%   |
| 5.18    | 1         | 0.87%   |
| 4.19    | 1         | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 115       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 112       | 97.39%  |
| GNOME | 3         | 2.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 111       | 96.52%  |
| Wayland | 3         | 2.61%   |
| Tty     | 1         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 103       | 89.57%  |
| GDM3    | 5         | 4.35%   |
| Unknown | 5         | 4.35%   |
| SLiM    | 1         | 0.87%   |
| SDDM    | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 56        | 48.7%   |
| de_DE | 11        | 9.57%   |
| fr_FR | 10        | 8.7%    |
| it_IT | 9         | 7.83%   |
| en_GB | 5         | 4.35%   |
| es_ES | 3         | 2.61%   |
| ru_RU | 2         | 1.74%   |
| pt_BR | 2         | 1.74%   |
| hu_HU | 2         | 1.74%   |
| en_CA | 2         | 1.74%   |
| en_AU | 2         | 1.74%   |
| tr_TR | 1         | 0.87%   |
| nl_NL | 1         | 0.87%   |
| nl_BE | 1         | 0.87%   |
| ja_JP | 1         | 0.87%   |
| fr_BE | 1         | 0.87%   |
| es_MX | 1         | 0.87%   |
| es_CL | 1         | 0.87%   |
| en_IL | 1         | 0.87%   |
| cs_CZ | 1         | 0.87%   |
| C     | 1         | 0.87%   |
| bg_BG | 1         | 0.87%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 67        | 58.26%  |
| BIOS | 48        | 41.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 105       | 91.3%   |
| Overlay | 5         | 4.35%   |
| Zfs     | 3         | 2.61%   |
| Btrfs   | 2         | 1.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 79        | 68.1%   |
| Unknown | 30        | 25.86%  |
| MBR     | 7         | 6.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 91.45%  |
| Yes       | 10        | 8.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 70.43%  |
| Yes       | 34        | 29.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 22.61%  |
| Hewlett-Packard     | 21        | 18.26%  |
| ASUSTek Computer    | 17        | 14.78%  |
| Dell                | 15        | 13.04%  |
| Acer                | 9         | 7.83%   |
| Google              | 5         | 4.35%   |
| Toshiba             | 3         | 2.61%   |
| GPU Company         | 3         | 2.61%   |
| Unknown             | 2         | 1.74%   |
| Tactus              | 1         | 0.87%   |
| Standard            | 1         | 0.87%   |
| Sony                | 1         | 0.87%   |
| Schenker            | 1         | 0.87%   |
| Samsung Electronics | 1         | 0.87%   |
| Panasonic           | 1         | 0.87%   |
| Packard Bell        | 1         | 0.87%   |
| MSI                 | 1         | 0.87%   |
| Mediacom            | 1         | 0.87%   |
| HUAWEI              | 1         | 0.87%   |
| Digma               | 1         | 0.87%   |
| Chuwi               | 1         | 0.87%   |
| Apple               | 1         | 0.87%   |
| AMI                 | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 840 G3                    | 3         | 2.61%   |
| Unknown                                | 3         | 2.61%   |
| HP Pavilion Notebook                   | 2         | 1.74%   |
| GPU Company GWTN116-3                  | 2         | 1.74%   |
| Toshiba Satellite Pro R50-C            | 1         | 0.87%   |
| Toshiba Satellite C650                 | 1         | 0.87%   |
| Toshiba PT10F                          | 1         | 0.87%   |
| Tactus GeoBook 140                     | 1         | 0.87%   |
| Sony SVE1512C6EB                       | 1         | 0.87%   |
| Schenker WORK (Early 2021)             | 1         | 0.87%   |
| Samsung 370E4K                         | 1         | 0.87%   |
| Panasonic CF-D1DVA06F3                 | 1         | 0.87%   |
| Packard Bell EasyNote MH45             | 1         | 0.87%   |
| MSI GF63 Thin 9RCX                     | 1         | 0.87%   |
| Mediacom SmartBook 14 FullHD - SB14UC  | 1         | 0.87%   |
| Lenovo V340-17IWL 81RG                 | 1         | 0.87%   |
| Lenovo V330-15IKB 81AX                 | 1         | 0.87%   |
| Lenovo ThinkPad X220 42918F6           | 1         | 0.87%   |
| Lenovo ThinkPad T61p 6457A24           | 1         | 0.87%   |
| Lenovo ThinkPad T61 7659AB7            | 1         | 0.87%   |
| Lenovo ThinkPad T470s 20HF004MMX       | 1         | 0.87%   |
| Lenovo ThinkPad T460s 20FAS6JY00       | 1         | 0.87%   |
| Lenovo ThinkPad T460s 20FAS30L01       | 1         | 0.87%   |
| Lenovo ThinkPad T460s 20FAS0Q900       | 1         | 0.87%   |
| Lenovo ThinkPad T430 23501K1           | 1         | 0.87%   |
| Lenovo ThinkPad T420 42361L0           | 1         | 0.87%   |
| Lenovo ThinkPad T410 2537AF8           | 1         | 0.87%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00B9MX | 1         | 0.87%   |
| Lenovo ThinkPad T14s Gen 2a 20XF004RUS | 1         | 0.87%   |
| Lenovo ThinkPad P70 20ERCTO1WW         | 1         | 0.87%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002LUS  | 1         | 0.87%   |
| Lenovo ThinkPad L520 5017AL3           | 1         | 0.87%   |
| Lenovo ThinkPad E580 20KS001JGE        | 1         | 0.87%   |
| Lenovo ThinkPad E14 Gen 2 20TA00JLAU   | 1         | 0.87%   |
| Lenovo IdeaPad N585 20179              | 1         | 0.87%   |
| Lenovo IdeaPad 3 14IML05 81WA          | 1         | 0.87%   |
| Lenovo IdeaPad 120S-14IAP 81A5         | 1         | 0.87%   |
| Lenovo IdeaPad 100-15IBY 80MJ          | 1         | 0.87%   |
| Lenovo G50-30 80G0                     | 1         | 0.87%   |
| Lenovo B70-80 80MR                     | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 14.78%  |
| Acer Aspire            | 7         | 6.09%   |
| HP Pavilion            | 6         | 5.22%   |
| HP EliteBook           | 6         | 5.22%   |
| Dell Latitude          | 6         | 5.22%   |
| Dell Inspiron          | 5         | 4.35%   |
| Lenovo IdeaPad         | 4         | 3.48%   |
| ASUS VivoBook          | 4         | 3.48%   |
| Unknown                | 3         | 2.61%   |
| Toshiba Satellite      | 2         | 1.74%   |
| HP Laptop              | 2         | 1.74%   |
| HP 255                 | 2         | 1.74%   |
| GPU Company GWTN116-3  | 2         | 1.74%   |
| Dell XPS               | 2         | 1.74%   |
| Dell Precision         | 2         | 1.74%   |
| ASUS ASUS              | 2         | 1.74%   |
| Toshiba PT10F          | 1         | 0.87%   |
| Tactus GeoBook         | 1         | 0.87%   |
| Sony SVE1512C6EB       | 1         | 0.87%   |
| Schenker WORK          | 1         | 0.87%   |
| Samsung 370E4K         | 1         | 0.87%   |
| Panasonic CF-D1DVA06F3 | 1         | 0.87%   |
| Packard Bell EasyNote  | 1         | 0.87%   |
| MSI GF63               | 1         | 0.87%   |
| Mediacom SmartBook     | 1         | 0.87%   |
| Lenovo V340-17IWL      | 1         | 0.87%   |
| Lenovo V330-15IKB      | 1         | 0.87%   |
| Lenovo G50-30          | 1         | 0.87%   |
| Lenovo B70-80          | 1         | 0.87%   |
| Lenovo 14w             | 1         | 0.87%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.87%   |
| HP Stream              | 1         | 0.87%   |
| HP ProBook             | 1         | 0.87%   |
| HP Notebook            | 1         | 0.87%   |
| HP Mini                | 1         | 0.87%   |
| HP 15                  | 1         | 0.87%   |
| GPU Company GWTN141-4  | 1         | 0.87%   |
| Google Snappy          | 1         | 0.87%   |
| Google Reks            | 1         | 0.87%   |
| Google Kip             | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 15.65%  |
| 2020 | 13        | 11.3%   |
| 2016 | 10        | 8.7%    |
| 2015 | 10        | 8.7%    |
| 2019 | 8         | 6.96%   |
| 2012 | 8         | 6.96%   |
| 2018 | 6         | 5.22%   |
| 2017 | 6         | 5.22%   |
| 2014 | 6         | 5.22%   |
| 2011 | 6         | 5.22%   |
| 2022 | 5         | 4.35%   |
| 2013 | 4         | 3.48%   |
| 2010 | 4         | 3.48%   |
| 2008 | 4         | 3.48%   |
| 2009 | 3         | 2.61%   |
| 2007 | 3         | 2.61%   |
| 2006 | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 105       | 91.3%   |
| Enabled  | 10        | 8.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 95.65%  |
| Yes  | 5         | 4.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 33.04%  |
| 3.01-4.0    | 34        | 29.57%  |
| 16.01-24.0  | 16        | 13.91%  |
| 8.01-16.0   | 11        | 9.57%   |
| 1.01-2.0    | 7         | 6.09%   |
| 32.01-64.0  | 5         | 4.35%   |
| 64.01-256.0 | 2         | 1.74%   |
| 2.01-3.0    | 1         | 0.87%   |
| 0.51-1.0    | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 57        | 48.31%  |
| 2.01-3.0  | 34        | 28.81%  |
| 0.51-1.0  | 11        | 9.32%   |
| 3.01-4.0  | 8         | 6.78%   |
| 4.01-8.0  | 5         | 4.24%   |
| 8.01-16.0 | 3         | 2.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 80%     |
| 2      | 21        | 18.26%  |
| 4      | 1         | 0.87%   |
| 3      | 1         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 63.48%  |
| Yes       | 42        | 36.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 74.78%  |
| No        | 29        | 25.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 98.26%  |
| No        | 2         | 1.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 75.65%  |
| No        | 28        | 24.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 23        | 20%     |
| Germany      | 15        | 13.04%  |
| Italy        | 11        | 9.57%   |
| France       | 10        | 8.7%    |
| UK           | 5         | 4.35%   |
| Russia       | 4         | 3.48%   |
| Netherlands  | 4         | 3.48%   |
| Sweden       | 3         | 2.61%   |
| Mexico       | 3         | 2.61%   |
| Malaysia     | 3         | 2.61%   |
| Belgium      | 3         | 2.61%   |
| Spain        | 2         | 1.74%   |
| Israel       | 2         | 1.74%   |
| Iran         | 2         | 1.74%   |
| Indonesia    | 2         | 1.74%   |
| Hungary      | 2         | 1.74%   |
| Czechia      | 2         | 1.74%   |
| Brazil       | 2         | 1.74%   |
| Australia    | 2         | 1.74%   |
| Argentina    | 2         | 1.74%   |
| Vietnam      | 1         | 0.87%   |
| Turkey       | 1         | 0.87%   |
| Sint Maarten | 1         | 0.87%   |
| Madagascar   | 1         | 0.87%   |
| Japan        | 1         | 0.87%   |
| India        | 1         | 0.87%   |
| Finland      | 1         | 0.87%   |
| Egypt        | 1         | 0.87%   |
| Colombia     | 1         | 0.87%   |
| Chile        | 1         | 0.87%   |
| Canada       | 1         | 0.87%   |
| Bulgaria     | 1         | 0.87%   |
| Austria      | 1         | 0.87%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 3         | 2.56%   |
| Uppsala                | 2         | 1.71%   |
| St Petersburg          | 2         | 1.71%   |
| Oklahoma City          | 2         | 1.71%   |
| Munich                 | 2         | 1.71%   |
| Milan                  | 2         | 1.71%   |
| Melbourne              | 2         | 1.71%   |
| Leipzig                | 2         | 1.71%   |
| Indianapolis           | 2         | 1.71%   |
| Hamburg                | 2         | 1.71%   |
| Farmington             | 2         | 1.71%   |
| Auxerre                | 2         | 1.71%   |
| Yokohama               | 1         | 0.85%   |
| Wierden                | 1         | 0.85%   |
| Washington             | 1         | 0.85%   |
| Vidin                  | 1         | 0.85%   |
| Västerås             | 1         | 0.85%   |
| Tustin                 | 1         | 0.85%   |
| Treviso                | 1         | 0.85%   |
| Toamasina              | 1         | 0.85%   |
| Tehran                 | 1         | 0.85%   |
| Surabaya               | 1         | 0.85%   |
| Stuttgart              | 1         | 0.85%   |
| Sombrio                | 1         | 0.85%   |
| Smiths Falls           | 1         | 0.85%   |
| Seattle                | 1         | 0.85%   |
| Schwarzenberg          | 1         | 0.85%   |
| Schmalkalden           | 1         | 0.85%   |
| Schaarbeek             | 1         | 0.85%   |
| Santiago               | 1         | 0.85%   |
| San Miguel de Tucumán | 1         | 0.85%   |
| San Luis Potosí City  | 1         | 0.85%   |
| San Diego              | 1         | 0.85%   |
| Saint-Gilles           | 1         | 0.85%   |
| Rome                   | 1         | 0.85%   |
| Rochester              | 1         | 0.85%   |
| Puebla City            | 1         | 0.85%   |
| Pontault-Combault      | 1         | 0.85%   |
| Poggibonsi             | 1         | 0.85%   |
| Pilsen                 | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 25     | 17.42%  |
| Unknown             | 17        | 20     | 12.88%  |
| WDC                 | 15        | 16     | 11.36%  |
| Seagate             | 12        | 14     | 9.09%   |
| SK hynix            | 10        | 11     | 7.58%   |
| Kingston            | 7         | 8      | 5.3%    |
| Intel               | 6         | 6      | 4.55%   |
| SanDisk             | 4         | 4      | 3.03%   |
| Hitachi             | 4         | 4      | 3.03%   |
| Micron Technology   | 3         | 3      | 2.27%   |
| HGST                | 3         | 3      | 2.27%   |
| China               | 3         | 4      | 2.27%   |
| Transcend           | 2         | 3      | 1.52%   |
| TO Exter            | 2         | 2      | 1.52%   |
| PNY                 | 2         | 2      | 1.52%   |
| Crucial             | 2         | 2      | 1.52%   |
| A-DATA Technology   | 2         | 4      | 1.52%   |
| USB3.0              | 1         | 2      | 0.76%   |
| Toshiba             | 1         | 1      | 0.76%   |
| SSSTC               | 1         | 1      | 0.76%   |
| SSD0240S            | 1         | 1      | 0.76%   |
| Silicon Motion      | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Lenovo              | 1         | 1      | 0.76%   |
| INNOVATION IT       | 1         | 1      | 0.76%   |
| FORESEE             | 1         | 1      | 0.76%   |
| Apple               | 1         | 2      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |
| Unknown             | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 3         | 2.16%   |
| Samsung SSD 850 EVO 500GB              | 3         | 2.16%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 2.16%   |
| Unknown SA08G  8GB                     | 2         | 1.44%   |
| Unknown MMC64G  64GB                   | 2         | 1.44%   |
| Unknown MMC Card  32GB                 | 2         | 1.44%   |
| TO Exter nal USB 3.0 1TB               | 2         | 1.44%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 1.44%   |
| SanDisk DF4032  32GB                   | 2         | 1.44%   |
| PNY CS900 120GB SSD                    | 2         | 1.44%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 1.44%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 1.44%   |
| HGST HTS541010A9E680 1TB               | 2         | 1.44%   |
| WDC WDS960G2G0C-00AJM0 960GB           | 1         | 0.72%   |
| WDC WDS500G2B0C 500GB                  | 1         | 0.72%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.72%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 1         | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.72%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 0.72%   |
| WDC WD7500BPVT-60HXZT3 752GB           | 1         | 0.72%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.72%   |
| WDC WD3200LPVX-75V0TT0 320GB           | 1         | 0.72%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 1         | 0.72%   |
| WDC WD10SPZX-80Z10T2 1TB               | 1         | 0.72%   |
| WDC WD10SPZX-22Z10T1 1TB               | 1         | 0.72%   |
| WDC WD10SPZX-00Z10T0 1TB               | 1         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.72%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 1         | 0.72%   |
| USB3.0 Super Speed 1TB                 | 1         | 0.72%   |
| Unknown SD64G  64GB                    | 1         | 0.72%   |
| Unknown SD32G  32GB                    | 1         | 0.72%   |
| Unknown SD16G  16GB                    | 1         | 0.72%   |
| Unknown SD08G  8GB                     | 1         | 0.72%   |
| Unknown SD/MMC/MS PRO 1TB              | 1         | 0.72%   |
| Unknown NCard  32GB                    | 1         | 0.72%   |
| Unknown GE8QT  256GB                   | 1         | 0.72%   |
| Unknown DA4064  64GB                   | 1         | 0.72%   |
| Unknown DA4032  32GB                   | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 14     | 38.71%  |
| WDC     | 9         | 9      | 29.03%  |
| Hitachi | 4         | 4      | 12.9%   |
| HGST    | 3         | 3      | 9.68%   |
| USB3.0  | 1         | 2      | 3.23%   |
| Unknown | 1         | 1      | 3.23%   |
| Toshiba | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 25.58%  |
| Kingston            | 6         | 6      | 13.95%  |
| WDC                 | 3         | 3      | 6.98%   |
| China               | 3         | 4      | 6.98%   |
| Transcend           | 2         | 2      | 4.65%   |
| TO Exter            | 2         | 2      | 4.65%   |
| SK hynix            | 2         | 2      | 4.65%   |
| PNY                 | 2         | 2      | 4.65%   |
| A-DATA Technology   | 2         | 4      | 4.65%   |
| SSSTC               | 1         | 1      | 2.33%   |
| Patriot             | 1         | 1      | 2.33%   |
| Netac               | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| LITEON              | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| INNOVATION IT       | 1         | 1      | 2.33%   |
| FORESEE             | 1         | 1      | 2.33%   |
| Crucial             | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 41        | 44     | 31.3%   |
| SSD     | 41        | 47     | 31.3%   |
| HDD     | 29        | 34     | 22.14%  |
| MMC     | 19        | 22     | 14.5%   |
| Unknown | 1         | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 76     | 50.38%  |
| NVMe | 41        | 44     | 31.3%   |
| MMC  | 19        | 22     | 14.5%   |
| SAS  | 5         | 6      | 3.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 60     | 73.97%  |
| 0.51-1.0   | 18        | 20     | 24.66%  |
| 1.01-2.0   | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 27.35%  |
| 101-250        | 32        | 27.35%  |
| 501-1000       | 16        | 13.68%  |
| 51-100         | 16        | 13.68%  |
| 1-20           | 9         | 7.69%   |
| 21-50          | 8         | 6.84%   |
| 1001-2000      | 2         | 1.71%   |
| More than 3000 | 1         | 0.85%   |
| Unknown        | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 44.44%  |
| 21-50     | 30        | 25.64%  |
| 101-250   | 13        | 11.11%  |
| 51-100    | 11        | 9.4%    |
| 251-500   | 6         | 5.13%   |
| 501-1000  | 3         | 2.56%   |
| 1001-2000 | 1         | 0.85%   |
| Unknown   | 1         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 9.09%   |
| SSSTC CVB-8D128-HP 128GB           | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 9.09%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 9.09%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 9.09%   |
| Intel SSDSCKKF240H6L 240GB         | 1         | 1      | 9.09%   |
| Hitachi HTS543212L9A300 120GB      | 1         | 1      | 9.09%   |
| Hitachi HTS541080G9SA00 80GB       | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 9.09%   |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 27.27%  |
| Hitachi  | 2         | 2      | 18.18%  |
| HGST     | 2         | 2      | 18.18%  |
| WDC      | 1         | 1      | 9.09%   |
| SSSTC    | 1         | 1      | 9.09%   |
| Kingston | 1         | 1      | 9.09%   |
| Intel    | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| HGST    | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 63.64%  |
| SSD  | 4         | 4      | 36.36%  |

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
| Works    | 56        | 65     | 46.28%  |
| Detected | 54        | 72     | 44.63%  |
| Malfunc  | 11        | 11     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 72        | 57.6%   |
| AMD                         | 18        | 14.4%   |
| Samsung Electronics         | 12        | 9.6%    |
| SK hynix                    | 8         | 6.4%    |
| SanDisk                     | 6         | 4.8%    |
| Silicon Motion              | 2         | 1.6%    |
| Kingston Technology Company | 2         | 1.6%    |
| Phison Electronics          | 1         | 0.8%    |
| Micron/Crucial Technology   | 1         | 0.8%    |
| Micron Technology           | 1         | 0.8%    |
| Lenovo                      | 1         | 0.8%    |
| Apple                       | 1         | 0.8%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 17        | 12.59%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 8         | 5.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 8         | 5.93%   |
| Samsung NVMe SSD Controller 980                                              | 6         | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 5         | 3.7%    |
| SK hynix Gold P31 SSD                                                        | 4         | 2.96%   |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 2.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 4         | 2.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 4         | 2.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 4         | 2.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 3         | 2.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 3         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 3         | 2.22%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                  | 2         | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.48%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 2         | 1.48%   |
| Intel SSD 660P Series                                                        | 2         | 1.48%   |
| Intel Non-Volatile memory controller                                         | 2         | 1.48%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.48%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.48%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.48%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 0.74%   |
| SK hynix BC511                                                               | 1         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 0.74%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 1         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.74%   |
| SanDisk Non-Volatile memory controller                                       | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                      | 1         | 0.74%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD                                              | 1         | 0.74%   |
| Micron Non-Volatile memory controller                                        | 1         | 0.74%   |
| Lenovo Non-Volatile memory controller                                        | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 58.65%  |
| NVMe | 41        | 30.83%  |
| IDE  | 8         | 6.02%   |
| RAID | 6         | 4.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 80%     |
| AMD    | 23        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 3.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 3.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 2.61%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 3         | 2.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 2.61%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 2.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 3         | 2.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 1.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.74%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.74%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 1.74%   |
| Intel Celeron 3205U @ 1.50GHz               | 2         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.74%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 2         | 1.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.74%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 2         | 1.74%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.74%   |
| AMD A6-7310 APU with AMD Radeon R4 Graphics | 2         | 1.74%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.87%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.87%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.87%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.87%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.87%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.87%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.87%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.87%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 0.87%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 24        | 20.87%  |
| Intel Core i5           | 21        | 18.26%  |
| Intel Core i7           | 13        | 11.3%   |
| Other                   | 11        | 9.57%   |
| Intel Core i3           | 6         | 5.22%   |
| Intel Core 2 Duo        | 5         | 4.35%   |
| AMD Ryzen 7             | 5         | 4.35%   |
| AMD A6                  | 5         | 4.35%   |
| Intel Atom              | 4         | 3.48%   |
| Intel Pentium           | 3         | 2.61%   |
| AMD Ryzen 5             | 3         | 2.61%   |
| AMD Ryzen 5 PRO         | 2         | 1.74%   |
| AMD A8                  | 2         | 1.74%   |
| Intel Xeon              | 1         | 0.87%   |
| Intel Pentium Silver    | 1         | 0.87%   |
| Intel Pentium Dual-Core | 1         | 0.87%   |
| Intel Genuine           | 1         | 0.87%   |
| Intel Core 2            | 1         | 0.87%   |
| AMD Ryzen 9             | 1         | 0.87%   |
| AMD FX                  | 1         | 0.87%   |
| AMD E2                  | 1         | 0.87%   |
| AMD E1                  | 1         | 0.87%   |
| AMD A4                  | 1         | 0.87%   |
| AMD A10                 | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 65        | 56.52%  |
| 4      | 32        | 27.83%  |
| 8      | 8         | 6.96%   |
| 6      | 8         | 6.96%   |
| 1      | 2         | 1.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 68        | 59.13%  |
| 1      | 47        | 40.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 115       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 32.17%  |
| 0x806c1    | 8         | 6.96%   |
| 0x406e3    | 6         | 5.22%   |
| 0x30678    | 5         | 4.35%   |
| 0xa0652    | 3         | 2.61%   |
| 0x806ec    | 3         | 2.61%   |
| 0x706a8    | 3         | 2.61%   |
| 0x406c3    | 3         | 2.61%   |
| 0x306d4    | 3         | 2.61%   |
| 0x306a9    | 3         | 2.61%   |
| 0x206a7    | 3         | 2.61%   |
| 0x08608103 | 3         | 2.61%   |
| 0x906ea    | 2         | 1.74%   |
| 0x806e9    | 2         | 1.74%   |
| 0x806d1    | 2         | 1.74%   |
| 0x6fb      | 2         | 1.74%   |
| 0x506ca    | 2         | 1.74%   |
| 0x506c9    | 2         | 1.74%   |
| 0x1067a    | 2         | 1.74%   |
| 0x0a50000c | 2         | 1.74%   |
| 0x906c0    | 1         | 0.87%   |
| 0x806ea    | 1         | 0.87%   |
| 0x6fd      | 1         | 0.87%   |
| 0x6f6      | 1         | 0.87%   |
| 0x506e3    | 1         | 0.87%   |
| 0x406c4    | 1         | 0.87%   |
| 0x40651    | 1         | 0.87%   |
| 0x30661    | 1         | 0.87%   |
| 0x20655    | 1         | 0.87%   |
| 0x20652    | 1         | 0.87%   |
| 0x0a404101 | 1         | 0.87%   |
| 0x08600104 | 1         | 0.87%   |
| 0x08108109 | 1         | 0.87%   |
| 0x08008206 | 1         | 0.87%   |
| 0x07030105 | 1         | 0.87%   |
| 0x06006705 | 1         | 0.87%   |
| 0x06006110 | 1         | 0.87%   |
| 0x06003106 | 1         | 0.87%   |
| 0x03000027 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 12.17%  |
| Silvermont    | 11        | 9.57%   |
| Skylake       | 10        | 8.7%    |
| TigerLake     | 9         | 7.83%   |
| IvyBridge     | 7         | 6.09%   |
| SandyBridge   | 6         | 5.22%   |
| Westmere      | 5         | 4.35%   |
| Goldmont      | 5         | 4.35%   |
| Puma          | 4         | 3.48%   |
| Penryn        | 4         | 3.48%   |
| Goldmont plus | 4         | 3.48%   |
| Core          | 4         | 3.48%   |
| Unknown       | 4         | 3.48%   |
| Zen 3         | 3         | 2.61%   |
| Icelake       | 3         | 2.61%   |
| Excavator     | 3         | 2.61%   |
| CometLake     | 3         | 2.61%   |
| Broadwell     | 3         | 2.61%   |
| Zen+          | 2         | 1.74%   |
| Zen 2         | 2         | 1.74%   |
| K10 Llano     | 2         | 1.74%   |
| Bonnell       | 2         | 1.74%   |
| Tremont       | 1         | 0.87%   |
| Steamroller   | 1         | 0.87%   |
| Piledriver    | 1         | 0.87%   |
| Haswell       | 1         | 0.87%   |
| Bobcat        | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 66.41%  |
| AMD    | 26        | 19.85%  |
| Nvidia | 18        | 13.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 6.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 5.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 5.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.35%   |
| Intel HD Graphics 500                                                                    | 5         | 3.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 2.9%    |
| Intel HD Graphics 620                                                                    | 3         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.17%   |
| AMD Lucienne                                                                             | 3         | 2.17%   |
| AMD Cezanne                                                                              | 3         | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.45%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.45%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.45%   |
| Intel HD Graphics                                                                        | 2         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.45%   |
| AMD Renoir                                                                               | 2         | 1.45%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 1.45%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.72%   |
| Nvidia TU117M                                                                            | 1         | 0.72%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.72%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 63.48%  |
| 1 x AMD        | 17        | 14.78%  |
| Intel + Nvidia | 11        | 9.57%   |
| 2 x AMD        | 4         | 3.48%   |
| 1 x Nvidia     | 4         | 3.48%   |
| AMD + Nvidia   | 3         | 2.61%   |
| Intel + AMD    | 2         | 1.74%   |
| Other          | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 88.7%   |
| Proprietary | 11        | 9.57%   |
| Unknown     | 2         | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 80%     |
| 0.01-0.5   | 11        | 9.57%   |
| 0.51-1.0   | 5         | 4.35%   |
| 1.01-2.0   | 4         | 3.48%   |
| 3.01-4.0   | 2         | 1.74%   |
| 7.01-8.0   | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 20.16%  |
| LG Display              | 21        | 16.94%  |
| BOE                     | 16        | 12.9%   |
| Chimei Innolux          | 15        | 12.1%   |
| Samsung Electronics     | 12        | 9.68%   |
| Chi Mei Optoelectronics | 5         | 4.03%   |
| PANDA                   | 4         | 3.23%   |
| Lenovo                  | 4         | 3.23%   |
| Dell                    | 4         | 3.23%   |
| KDC                     | 2         | 1.61%   |
| InfoVision              | 2         | 1.61%   |
| Goldstar                | 2         | 1.61%   |
| ViewSonic               | 1         | 0.81%   |
| Toshiba                 | 1         | 0.81%   |
| Sharp                   | 1         | 0.81%   |
| Sceptre Tech            | 1         | 0.81%   |
| Philips                 | 1         | 0.81%   |
| Panasonic               | 1         | 0.81%   |
| LG Philips              | 1         | 0.81%   |
| HannStar                | 1         | 0.81%   |
| CSO                     | 1         | 0.81%   |
| BenQ                    | 1         | 0.81%   |
| Apple                   | 1         | 0.81%   |
| Acer                    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 1.61%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 1.61%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.61%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.81%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.81%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4A52 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM7048 1360x768 522x293mm 23.6-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                         | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                        | 1         | 0.81%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 0.81%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 0.81%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 1         | 0.81%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD06C3 1920x1080 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD05BE 1920x1080 380x210mm 17.1-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0551 1920x1080 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD04D1 1366x768 344x194mm 15.5-inch              | 1         | 0.81%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 42.02%  |
| 1366x768 (WXGA)    | 40        | 33.61%  |
| 1600x900 (HD+)     | 8         | 6.72%   |
| 3840x2160 (4K)     | 4         | 3.36%   |
| 1280x800 (WXGA)    | 4         | 3.36%   |
| 1440x900 (WXGA+)   | 3         | 2.52%   |
| 1024x600           | 2         | 1.68%   |
| 2880x1800          | 1         | 0.84%   |
| 2560x1440 (QHD)    | 1         | 0.84%   |
| 2160x1440          | 1         | 0.84%   |
| 1920x1200 (WUXGA)  | 1         | 0.84%   |
| 1680x1050 (WSXGA+) | 1         | 0.84%   |
| 1366x912           | 1         | 0.84%   |
| 1360x768           | 1         | 0.84%   |
| 1280x1024 (SXGA)   | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 38.71%  |
| 14      | 25        | 20.16%  |
| 13      | 18        | 14.52%  |
| 17      | 8         | 6.45%   |
| 27      | 4         | 3.23%   |
| 11      | 4         | 3.23%   |
| 23      | 3         | 2.42%   |
| 12      | 3         | 2.42%   |
| 26      | 2         | 1.61%   |
| 21      | 2         | 1.61%   |
| 10      | 2         | 1.61%   |
| Unknown | 2         | 1.61%   |
| 24      | 1         | 0.81%   |
| 20      | 1         | 0.81%   |
| 18      | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 67.74%  |
| 201-300     | 16        | 12.9%   |
| 501-600     | 10        | 8.06%   |
| 351-400     | 8         | 6.45%   |
| 401-500     | 4         | 3.23%   |
| Unknown     | 2         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 100       | 88.5%   |
| 16/10 | 10        | 8.85%   |
| 3/2   | 2         | 1.77%   |
| 4/3   | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 38.71%  |
| 81-90          | 37        | 29.84%  |
| 71-80          | 7         | 5.65%   |
| 121-130        | 7         | 5.65%   |
| 201-250        | 6         | 4.84%   |
| 301-350        | 5         | 4.03%   |
| 51-60          | 4         | 3.23%   |
| 61-70          | 2         | 1.61%   |
| 41-50          | 2         | 1.61%   |
| 151-200        | 2         | 1.61%   |
| Unknown        | 2         | 1.61%   |
| 251-300        | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 55        | 44.72%  |
| 101-120       | 41        | 33.33%  |
| 51-100        | 19        | 15.45%  |
| More than 240 | 3         | 2.44%   |
| 161-240       | 3         | 2.44%   |
| Unknown       | 2         | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 98        | 85.22%  |
| 2     | 15        | 13.04%  |
| 0     | 2         | 1.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 61        | 36.31%  |
| Realtek Semiconductor             | 55        | 32.74%  |
| Qualcomm Atheros                  | 19        | 11.31%  |
| Broadcom                          | 12        | 7.14%   |
| MediaTek                          | 3         | 1.79%   |
| Sierra Wireless                   | 2         | 1.19%   |
| Samsung Electronics               | 2         | 1.19%   |
| Marvell Technology Group          | 2         | 1.19%   |
| Huawei Technologies               | 2         | 1.19%   |
| TP-Link                           | 1         | 0.6%    |
| Ralink Technology                 | 1         | 0.6%    |
| Qualcomm                          | 1         | 0.6%    |
| LG Electronics                    | 1         | 0.6%    |
| Hewlett-Packard                   | 1         | 0.6%    |
| Ericsson Business Mobile Networks | 1         | 0.6%    |
| Dell                              | 1         | 0.6%    |
| BUFFALO                           | 1         | 0.6%    |
| Attansic Technology               | 1         | 0.6%    |
| Apple                             | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 13.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 3.72%   |
| Intel Wireless 8260                                               | 7         | 3.26%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.79%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.86%   |
| Intel Wireless 3165                                               | 4         | 1.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.86%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.4%    |
| Realtek 802.11n WLAN Adapter                                      | 3         | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.4%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 2         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.93%   |
| Intel Wireless 7265                                               | 2         | 0.93%   |
| Intel Wireless 7260                                               | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.93%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.93%   |
| Huawei LYA-L09                                                    | 2         | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 49.18%  |
| Realtek Semiconductor | 28        | 22.95%  |
| Qualcomm Atheros      | 17        | 13.93%  |
| Broadcom              | 8         | 6.56%   |
| MediaTek              | 3         | 2.46%   |
| Sierra Wireless       | 2         | 1.64%   |
| Ralink Technology     | 1         | 0.82%   |
| Qualcomm              | 1         | 0.82%   |
| Dell                  | 1         | 0.82%   |
| BUFFALO               | 1         | 0.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 6.4%    |
| Intel Wireless 8260                                            | 7         | 5.6%    |
| Intel Wi-Fi 6 AX201                                            | 7         | 5.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 4.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.2%    |
| Intel Wireless 8265 / 8275                                     | 4         | 3.2%    |
| Intel Wireless 3165                                            | 4         | 3.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 3.2%    |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 2.4%    |
| Realtek 802.11n WLAN Adapter                                   | 3         | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.4%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 2.4%    |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.4%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 2         | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.6%    |
| Intel Wireless 7265                                            | 2         | 1.6%    |
| Intel Wireless 7260                                            | 2         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 1.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.8%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.8%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.8%    |
| Realtek 802.11ac NIC                                           | 1         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.8%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.8%    |
| MediaTek WiFi                                                  | 1         | 0.8%    |
| Intel Wireless 3160                                            | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 49.44%  |
| Intel                    | 25        | 28.09%  |
| Qualcomm Atheros         | 5         | 5.62%   |
| Broadcom                 | 4         | 4.49%   |
| Samsung Electronics      | 2         | 2.25%   |
| Marvell Technology Group | 2         | 2.25%   |
| Huawei Technologies      | 2         | 2.25%   |
| TP-Link                  | 1         | 1.12%   |
| LG Electronics           | 1         | 1.12%   |
| Hewlett-Packard          | 1         | 1.12%   |
| Attansic Technology      | 1         | 1.12%   |
| Apple                    | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 33.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 13        | 14.61%  |
| Intel Ethernet Connection I219-LM                                              | 6         | 6.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 5.62%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.25%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 2.25%   |
| Huawei LYA-L09                                                                 | 2         | 2.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.12%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.12%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                            | 1         | 1.12%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.12%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.12%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 1.12%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.12%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 1         | 1.12%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.12%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 1.12%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.12%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 1.12%   |
| Apple Ethernet Adapter [A1277]                                                 | 1         | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 56.5%   |
| Ethernet | 86        | 43%     |
| Modem    | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 82.35%  |
| Ethernet | 21        | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 78        | 67.83%  |
| 1     | 31        | 26.96%  |
| 0     | 6         | 5.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 66.38%  |
| Yes  | 39        | 33.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 50.57%  |
| Realtek Semiconductor           | 12        | 13.79%  |
| Broadcom                        | 7         | 8.05%   |
| Lite-On Technology              | 6         | 6.9%    |
| Foxconn / Hon Hai               | 5         | 5.75%   |
| Qualcomm Atheros Communications | 3         | 3.45%   |
| IMC Networks                    | 3         | 3.45%   |
| Toshiba                         | 1         | 1.15%   |
| Realtek                         | 1         | 1.15%   |
| Hewlett-Packard                 | 1         | 1.15%   |
| Dell                            | 1         | 1.15%   |
| Chicony Electronics             | 1         | 1.15%   |
| Cambridge Silicon Radio         | 1         | 1.15%   |
| Alps Electric                   | 1         | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 22.99%  |
| Realtek Bluetooth Radio                             | 9         | 10.34%  |
| Intel AX201 Bluetooth                               | 9         | 10.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.9%    |
| Intel AX210 Bluetooth                               | 4         | 4.6%    |
| Intel AX200 Bluetooth                               | 4         | 4.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 4.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.3%    |
| IMC Networks Wireless_Device                        | 2         | 2.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 2.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 2.3%    |
| Toshiba Bluetooth Device                            | 1         | 1.15%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.15%   |
| Realtek Bluetooth Radio                             | 1         | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.15%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 1.15%   |
| Lite-On Bluetooth Radio                             | 1         | 1.15%   |
| Lite-On Bluetooth Device                            | 1         | 1.15%   |
| Lite-On BCM43142A0                                  | 1         | 1.15%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.15%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.15%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.15%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.15%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.15%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.15%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 90        | 70.87%  |
| AMD                    | 23        | 18.11%  |
| Nvidia                 | 8         | 6.3%    |
| JMTek                  | 2         | 1.57%   |
| Texas Instruments      | 1         | 0.79%   |
| Tenx Technology        | 1         | 0.79%   |
| Generalplus Technology | 1         | 0.79%   |
| ASUSTek Computer       | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 9.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 5.88%   |
| AMD FCH Azalia Controller                                                                         | 9         | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.96%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.96%   |
| Nvidia Audio device                                                                               | 2         | 1.31%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.31%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.31%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.31%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.65%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.65%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.65%   |
| JMTek USB Audio Device                                                                            | 1         | 0.65%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 27        | 29.67%  |
| SK hynix                   | 18        | 19.78%  |
| Unknown                    | 15        | 16.48%  |
| Micron Technology          | 11        | 12.09%  |
| Unknown (ABCD)             | 5         | 5.49%   |
| Kingston                   | 5         | 5.49%   |
| Crucial                    | 5         | 5.49%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 1.1%    |
| Smart                      | 1         | 1.1%    |
| Foxline                    | 1         | 1.1%    |
| fef5                       | 1         | 1.1%    |
| Essencore                  | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s            | 5         | 5.38%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                                   | 3         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                       | 3         | 3.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 2.15%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 2.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 2         | 2.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 2.15%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                                 | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                       | 1         | 1.08%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                            | 1         | 1.08%   |
| Unknown RAM 202020202020202020202020202020202020 4096MB SODIMM DDR2 800MT/s | 1         | 1.08%   |
| Unknown (7F7F7F7F7F7F6B00) RAM 8D7T3MN8-NATP 2GB SODIMM DDR 667MT/s         | 1         | 1.08%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.08%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                | 1         | 1.08%   |
| SK hynix RAM Module 2GB Row Of Chips DDR3 1600MT/s                          | 1         | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                             | 1         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s                | 1         | 1.08%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s                     | 1         | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.08%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.08%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s            | 1         | 1.08%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s                  | 1         | 1.08%   |
| Samsung RAM U6E3S4AA-MGCR 4GB Row Of Chips LPDDR4 4267MT/s                  | 1         | 1.08%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                                 | 1         | 1.08%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                                | 1         | 1.08%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                       | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 40%     |
| DDR3    | 22        | 27.5%   |
| LPDDR4  | 14        | 17.5%   |
| DDR2    | 4         | 5%      |
| LPDDR3  | 3         | 3.75%   |
| Unknown | 2         | 2.5%    |
| SDRAM   | 1         | 1.25%   |
| DDR5    | 1         | 1.25%   |
| DDR     | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 81.71%  |
| Row Of Chips | 10        | 12.2%   |
| Chip         | 3         | 3.66%   |
| Unknown      | 2         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 37.35%  |
| 8192  | 27        | 32.53%  |
| 2048  | 11        | 13.25%  |
| 16384 | 8         | 9.64%   |
| 1024  | 3         | 3.61%   |
| 32768 | 2         | 2.41%   |
| 1536  | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 17        | 20.48%  |
| 1600  | 16        | 19.28%  |
| 2667  | 10        | 12.05%  |
| 2400  | 9         | 10.84%  |
| 2133  | 8         | 9.64%   |
| 667   | 5         | 6.02%   |
| 4267  | 4         | 4.82%   |
| 1334  | 3         | 3.61%   |
| 1333  | 2         | 2.41%   |
| 4800  | 1         | 1.2%    |
| 4266  | 1         | 1.2%    |
| 4199  | 1         | 1.2%    |
| 3733  | 1         | 1.2%    |
| 3266  | 1         | 1.2%    |
| 2134  | 1         | 1.2%    |
| 1776  | 1         | 1.2%    |
| 1066  | 1         | 1.2%    |
| 800   | 1         | 1.2%    |

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
| Chicony Electronics                    | 31        | 29.81%  |
| Realtek Semiconductor                  | 10        | 9.62%   |
| Quanta                                 | 9         | 8.65%   |
| IMC Networks                           | 7         | 6.73%   |
| Microdia                               | 6         | 5.77%   |
| Suyin                                  | 5         | 4.81%   |
| Sunplus Innovation Technology          | 5         | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.81%   |
| Acer                                   | 4         | 3.85%   |
| Luxvisions Innotech Limited            | 3         | 2.88%   |
| Lite-On Technology                     | 3         | 2.88%   |
| Silicon Motion                         | 2         | 1.92%   |
| icSpring                               | 2         | 1.92%   |
| Alcor Micro                            | 2         | 1.92%   |
| Z-Star Microelectronics                | 1         | 0.96%   |
| USB Camera CS                          | 1         | 0.96%   |
| Syntek                                 | 1         | 0.96%   |
| SunplusIT                              | 1         | 0.96%   |
| Sonix Technology                       | 1         | 0.96%   |
| Primax Electronics                     | 1         | 0.96%   |
| OmniVision Technologies                | 1         | 0.96%   |
| Logitech                               | 1         | 0.96%   |
| Lenovo                                 | 1         | 0.96%   |
| Importek                               | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 9.62%   |
| Microdia Integrated_Webcam_HD                       | 3         | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 2.88%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.92%   |
| Sunplus Integrated_Webcam_FHD                       | 2         | 1.92%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.92%   |
| Realtek HP Truevision HD                            | 2         | 1.92%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.92%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.92%   |
| Quanta HD User Facing                               | 2         | 1.92%   |
| icSpring camera                                     | 2         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.92%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.92%   |
| Chicony HP Truevision HD                            | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.92%   |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 0.96%   |
| USB Camera CS USB Camera CS                         | 1         | 0.96%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.96%   |
| Suyin VGA Webcam                                    | 1         | 0.96%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.96%   |
| Suyin HD WebCam                                     | 1         | 0.96%   |
| Suyin Asus Integrated Webcam [CN031B]               | 1         | 0.96%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.96%   |
| SunplusIT USB camera                                | 1         | 0.96%   |
| Sunplus Asus Webcam                                 | 1         | 0.96%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.96%   |
| Silicon Motion ATIV VGA Camera                      | 1         | 0.96%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.96%   |
| Realtek USB Camera                                  | 1         | 0.96%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.96%   |
| Realtek Integrated Webcam_HD                        | 1         | 0.96%   |
| Realtek Integrated Webcam HD                        | 1         | 0.96%   |
| Quanta Lenovo EasyCamera                            | 1         | 0.96%   |
| Quanta HP Webcam                                    | 1         | 0.96%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.96%   |
| Quanta HP HD Camera                                 | 1         | 0.96%   |
| Quanta HD Webcam                                    | 1         | 0.96%   |
| Primax Villem                                       | 1         | 0.96%   |
| OmniVision OV2640 Webcam                            | 1         | 0.96%   |
| Microdia Webcam Vitade AF                           | 1         | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 43.75%  |
| Synaptics                  | 3         | 18.75%  |
| Upek                       | 2         | 12.5%   |
| STMicroelectronics         | 2         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 12.5%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.25%   |
| Synaptics  WBDI                                        | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 36.36%  |
| Alcor Micro | 4         | 36.36%  |
| Lenovo      | 2         | 18.18%  |
| O2 Micro    | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 4         | 36.36%  |
| Lenovo Integrated Smart Card Reader | 2         | 18.18%  |
| Broadcom 5880                       | 2         | 18.18%  |
| Broadcom 58200                      | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader     | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 63.79%  |
| 1     | 35        | 30.17%  |
| 2     | 7         | 6.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 32.61%  |
| Chipcard              | 11        | 23.91%  |
| Net/wireless          | 5         | 10.87%  |
| Graphics card         | 4         | 8.7%    |
| Camera                | 4         | 8.7%    |
| Network               | 3         | 6.52%   |
| Card reader           | 2         | 4.35%   |
| Multimedia controller | 1         | 2.17%   |
| Bluetooth             | 1         | 2.17%   |

