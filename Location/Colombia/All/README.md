Linux in Colombia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Colombia/Desktop/README.md) and [notebooks](/Location/Colombia/Notebook/README.md).

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

Total: 1165

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | V241DA                      | All in one  | [8a9451cb9c](https://linux-hardware.org/?probe=8a9451cb9c) | Oct 31, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [150c8ac0ac](https://linux-hardware.org/?probe=150c8ac0ac) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7daabab955](https://linux-hardware.org/?probe=7daabab955) | Oct 27, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [947259d1f6](https://linux-hardware.org/?probe=947259d1f6) | Oct 26, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [1ca42d6148](https://linux-hardware.org/?probe=1ca42d6148) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| HP            | 245 G7                      | Notebook    | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d8372069b0](https://linux-hardware.org/?probe=d8372069b0) | Oct 16, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [742bc1f2eb](https://linux-hardware.org/?probe=742bc1f2eb) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a318dbfcc9](https://linux-hardware.org/?probe=a318dbfcc9) | Oct 15, 2022 |
| HP            | Pavilion dv6000 (RG266UA... | Notebook    | [1601ca9a83](https://linux-hardware.org/?probe=1601ca9a83) | Oct 14, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [f785339c71](https://linux-hardware.org/?probe=f785339c71) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4ca8fc6d34](https://linux-hardware.org/?probe=4ca8fc6d34) | Oct 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Lanix         | Neuron V                    | Notebook    | [6bd3c14cc9](https://linux-hardware.org/?probe=6bd3c14cc9) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [45557ec6e6](https://linux-hardware.org/?probe=45557ec6e6) | Oct 03, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [7b92fcd976](https://linux-hardware.org/?probe=7b92fcd976) | Oct 02, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [de8eb62c07](https://linux-hardware.org/?probe=de8eb62c07) | Oct 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [28003748e6](https://linux-hardware.org/?probe=28003748e6) | Sep 27, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [1186e5b5d8](https://linux-hardware.org/?probe=1186e5b5d8) | Sep 23, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [4a71131e80](https://linux-hardware.org/?probe=4a71131e80) | Sep 19, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [f7c5412964](https://linux-hardware.org/?probe=f7c5412964) | Sep 19, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| HP            | 18E7                        | Desktop     | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| Dell          | Latitude E5420              | Notebook    | [7416dc3fb1](https://linux-hardware.org/?probe=7416dc3fb1) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [09f7be676c](https://linux-hardware.org/?probe=09f7be676c) | Sep 15, 2022 |
| ASUSTek       | X405UA                      | Notebook    | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| HP            | 1494                        | Desktop     | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| Acer          | Aspire V3-472P              | Notebook    | [632117c524](https://linux-hardware.org/?probe=632117c524) | Sep 10, 2022 |
| Toshiba       | Satellite L635              | Notebook    | [6d0bbfb576](https://linux-hardware.org/?probe=6d0bbfb576) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [b635e1c2ba](https://linux-hardware.org/?probe=b635e1c2ba) | Sep 01, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| HP            | ENVY 15                     | Notebook    | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | Desktop     | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [24849a5c23](https://linux-hardware.org/?probe=24849a5c23) | Aug 15, 2022 |
| ASUSTek       | X550DP                      | Notebook    | [ce42b65252](https://linux-hardware.org/?probe=ce42b65252) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [298cf4b527](https://linux-hardware.org/?probe=298cf4b527) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [e71b330285](https://linux-hardware.org/?probe=e71b330285) | Aug 13, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fcc8ebfb00](https://linux-hardware.org/?probe=fcc8ebfb00) | Aug 04, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6d65ac3351](https://linux-hardware.org/?probe=6d65ac3351) | Aug 02, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| HP            | 245 G6                      | Notebook    | [ae4b0ce17e](https://linux-hardware.org/?probe=ae4b0ce17e) | Jul 28, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| Lenovo        | G410 20237                  | Notebook    | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| Sony          | VPCEG33FL                   | Notebook    | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [635f096b70](https://linux-hardware.org/?probe=635f096b70) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [12ef7e83a2](https://linux-hardware.org/?probe=12ef7e83a2) | Jul 20, 2022 |
| Sony          | VPCEH37FJ                   | Notebook    | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| ASUSTek       | V241DA                      | All in one  | [51c040abed](https://linux-hardware.org/?probe=51c040abed) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [2af75f4744](https://linux-hardware.org/?probe=2af75f4744) | Jul 12, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [c7c8a9031c](https://linux-hardware.org/?probe=c7c8a9031c) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| Sony          | VPCEH37FJ                   | Notebook    | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | Notebook    | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | Desktop     | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | Desktop     | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Acer          | AO722                       | Notebook    | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| Gigabyte      | H61M-HD2                    | Desktop     | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [269af04437](https://linux-hardware.org/?probe=269af04437) | Jun 13, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [170031499c](https://linux-hardware.org/?probe=170031499c) | Jun 12, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [5e7659e141](https://linux-hardware.org/?probe=5e7659e141) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [77e3d238c1](https://linux-hardware.org/?probe=77e3d238c1) | Jun 10, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [0664b57ae1](https://linux-hardware.org/?probe=0664b57ae1) | Jun 09, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [47ef7a04b9](https://linux-hardware.org/?probe=47ef7a04b9) | Jun 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e5998cb70e](https://linux-hardware.org/?probe=e5998cb70e) | Jun 05, 2022 |
| Sony          | VGN-CS240T                  | Notebook    | [b25cbd1a6b](https://linux-hardware.org/?probe=b25cbd1a6b) | Jun 03, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Acer          | AOD260                      | Notebook    | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| HP            | 8054                        | Desktop     | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [159819d677](https://linux-hardware.org/?probe=159819d677) | May 26, 2022 |
| Dell          | Latitude E5410              | Notebook    | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [7dd1f5b528](https://linux-hardware.org/?probe=7dd1f5b528) | May 23, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [46f7672c43](https://linux-hardware.org/?probe=46f7672c43) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [6f6a96c1cb](https://linux-hardware.org/?probe=6f6a96c1cb) | May 22, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Dell          | Inspiron 3459               | Notebook    | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [915b4b3bf1](https://linux-hardware.org/?probe=915b4b3bf1) | May 16, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | Notebook    | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [0d68cb4fdd](https://linux-hardware.org/?probe=0d68cb4fdd) | May 04, 2022 |
| Toshiba       | Satellite L735              | Notebook    | [cb523c0933](https://linux-hardware.org/?probe=cb523c0933) | May 02, 2022 |
| Lenovo        | G450 2949                   | Notebook    | [8a97581747](https://linux-hardware.org/?probe=8a97581747) | May 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Dell          | Vostro 1510                 | Notebook    | [3b071a4b76](https://linux-hardware.org/?probe=3b071a4b76) | Apr 29, 2022 |
| Dell          | Vostro 1510                 | Notebook    | [483727ec47](https://linux-hardware.org/?probe=483727ec47) | Apr 29, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [8a8d7b120a](https://linux-hardware.org/?probe=8a8d7b120a) | Apr 24, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [9f8f3a2eb5](https://linux-hardware.org/?probe=9f8f3a2eb5) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [738850499d](https://linux-hardware.org/?probe=738850499d) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [fd8cacef33](https://linux-hardware.org/?probe=fd8cacef33) | Apr 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| MSI           | Creator 15 A10SFS           | Notebook    | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Acer          | Aspire 4740                 | Notebook    | [d401412daa](https://linux-hardware.org/?probe=d401412daa) | Apr 13, 2022 |
| Dell          | 0C1GJ7 A00                  | All in one  | [8dd3b0dfb9](https://linux-hardware.org/?probe=8dd3b0dfb9) | Apr 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [7349c76e13](https://linux-hardware.org/?probe=7349c76e13) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 4291AN3       | Notebook    | [848b7902d8](https://linux-hardware.org/?probe=848b7902d8) | Apr 10, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Toshiba       | Satellite L735              | Notebook    | [b7873249a4](https://linux-hardware.org/?probe=b7873249a4) | Apr 07, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f68ed48f1b](https://linux-hardware.org/?probe=f68ed48f1b) | Apr 06, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [b3601d9299](https://linux-hardware.org/?probe=b3601d9299) | Apr 05, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [38036fe92b](https://linux-hardware.org/?probe=38036fe92b) | Apr 05, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | Desktop     | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [a7fbdd0858](https://linux-hardware.org/?probe=a7fbdd0858) | Mar 26, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [dc0e34cb10](https://linux-hardware.org/?probe=dc0e34cb10) | Mar 26, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [18bc4eb505](https://linux-hardware.org/?probe=18bc4eb505) | Mar 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | Notebook    | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [e149d7ed93](https://linux-hardware.org/?probe=e149d7ed93) | Mar 23, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b15d85a6e9](https://linux-hardware.org/?probe=b15d85a6e9) | Mar 22, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [f8d12d8ab9](https://linux-hardware.org/?probe=f8d12d8ab9) | Mar 22, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [6d6865b081](https://linux-hardware.org/?probe=6d6865b081) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7810210cf5](https://linux-hardware.org/?probe=7810210cf5) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| HP            | 550                         | Notebook    | [91f443bb06](https://linux-hardware.org/?probe=91f443bb06) | Mar 18, 2022 |
| HP            | 550                         | Notebook    | [8acaec9ff1](https://linux-hardware.org/?probe=8acaec9ff1) | Mar 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8c94df31c1](https://linux-hardware.org/?probe=8c94df31c1) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | Notebook    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T430 2347AF3       | Notebook    | [8fa4355200](https://linux-hardware.org/?probe=8fa4355200) | Mar 08, 2022 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [3298d34369](https://linux-hardware.org/?probe=3298d34369) | Mar 07, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | Notebook    | [b1a7b4593a](https://linux-hardware.org/?probe=b1a7b4593a) | Mar 07, 2022 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [1e54d4f165](https://linux-hardware.org/?probe=1e54d4f165) | Mar 06, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | Notebook    | [f10cf42ebf](https://linux-hardware.org/?probe=f10cf42ebf) | Mar 06, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [b887ed3aa2](https://linux-hardware.org/?probe=b887ed3aa2) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [07cade8a02](https://linux-hardware.org/?probe=07cade8a02) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| HP            | 245 G3                      | Notebook    | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| ASUSTek       | K43E                        | Notebook    | [484fd9a41a](https://linux-hardware.org/?probe=484fd9a41a) | Feb 27, 2022 |
| Supermicro    | X7DA8                       | Desktop     | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| Dell          | Latitude 5179               | Notebook    | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | Notebook    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2505367a60](https://linux-hardware.org/?probe=2505367a60) | Feb 16, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | Notebook    | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Framework     | Laptop                      | Notebook    | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| HP            | 240 G7                      | Notebook    | [48bc3b139b](https://linux-hardware.org/?probe=48bc3b139b) | Feb 03, 2022 |
| HP            | 1587h                       | Desktop     | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e9752ad35d](https://linux-hardware.org/?probe=e9752ad35d) | Jan 24, 2022 |
| MSI           | GF75 Thin 10SER             | Notebook    | [2e94cc2b4c](https://linux-hardware.org/?probe=2e94cc2b4c) | Jan 22, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | Notebook    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [fb3b510c66](https://linux-hardware.org/?probe=fb3b510c66) | Jan 06, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [be57155d1f](https://linux-hardware.org/?probe=be57155d1f) | Jan 06, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [c9cffe7310](https://linux-hardware.org/?probe=c9cffe7310) | Dec 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| MSI           | B150A GAMING PRO            | Desktop     | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | Desktop     | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| HP            | ProBook 6450b               | Notebook    | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| HP            | 14                          | Notebook    | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | Notebook    | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| ASUSTek       | X441NA                      | Notebook    | [da21de67fb](https://linux-hardware.org/?probe=da21de67fb) | Nov 18, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [b98c646c47](https://linux-hardware.org/?probe=b98c646c47) | Nov 16, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [18152a84af](https://linux-hardware.org/?probe=18152a84af) | Nov 13, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6514199d0c](https://linux-hardware.org/?probe=6514199d0c) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| Lenovo        | ThinkPad T495 20NKS0QN0V    | Notebook    | [ceab02dda1](https://linux-hardware.org/?probe=ceab02dda1) | Nov 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [dcd63f8987](https://linux-hardware.org/?probe=dcd63f8987) | Oct 31, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [809fe8da11](https://linux-hardware.org/?probe=809fe8da11) | Oct 30, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7f70de1771](https://linux-hardware.org/?probe=7f70de1771) | Oct 26, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [6777af6e6a](https://linux-hardware.org/?probe=6777af6e6a) | Oct 26, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [46a74b74fc](https://linux-hardware.org/?probe=46a74b74fc) | Oct 22, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [dc7a02c862](https://linux-hardware.org/?probe=dc7a02c862) | Oct 15, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| HP            | 240 G3                      | Notebook    | [a083502110](https://linux-hardware.org/?probe=a083502110) | Oct 11, 2021 |
| HP            | 240 G3                      | Notebook    | [1772f88ed6](https://linux-hardware.org/?probe=1772f88ed6) | Oct 11, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [ee28fa6dfb](https://linux-hardware.org/?probe=ee28fa6dfb) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | Desktop     | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [b411cfd959](https://linux-hardware.org/?probe=b411cfd959) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | Desktop     | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| ECS           | G31T-M7                     | Desktop     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [e6fbfad3de](https://linux-hardware.org/?probe=e6fbfad3de) | Sep 16, 2021 |
| Gateway       | NV47H                       | Notebook    | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | Notebook    | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Dell          | Latitude E7270              | Notebook    | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| HP            | 18E9                        | Desktop     | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2300be2f19](https://linux-hardware.org/?probe=2300be2f19) | Sep 13, 2021 |
| HP            | 2000                        | Notebook    | [7d8cd719a2](https://linux-hardware.org/?probe=7d8cd719a2) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Dell          | Inspiron 1110               | Notebook    | [890d9d9d24](https://linux-hardware.org/?probe=890d9d9d24) | Sep 08, 2021 |
| Dell          | Inspiron 1110               | Notebook    | [e299761316](https://linux-hardware.org/?probe=e299761316) | Sep 08, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | Desktop     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | X555QA                      | Notebook    | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [badf1b0736](https://linux-hardware.org/?probe=badf1b0736) | Aug 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [33a8107059](https://linux-hardware.org/?probe=33a8107059) | Aug 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [fe2ba9da7c](https://linux-hardware.org/?probe=fe2ba9da7c) | Aug 28, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08c766b957](https://linux-hardware.org/?probe=08c766b957) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8aa8372f3c](https://linux-hardware.org/?probe=8aa8372f3c) | Aug 23, 2021 |
| HP            | 14                          | Notebook    | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Pegatron      | 2AEE                        | Desktop     | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | Desktop     | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | Desktop     | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | Desktop     | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| HP            | 304Ah                       | Desktop     | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| HP            | 304Ah                       | Desktop     | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| HP            | 8430 1000                   | All in one  | [38088141ff](https://linux-hardware.org/?probe=38088141ff) | Aug 17, 2021 |
| Timi          | A35S                        | Notebook    | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3bf42ebeb8](https://linux-hardware.org/?probe=3bf42ebeb8) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| Dell          | Precision 3551              | Notebook    | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Dell          | Precision 3551              | Notebook    | [aeeeb63990](https://linux-hardware.org/?probe=aeeeb63990) | Aug 10, 2021 |
| Dell          | 0CXTWJ A00                  | All in one  | [55b0b947be](https://linux-hardware.org/?probe=55b0b947be) | Aug 09, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Dell          | Latitude D630               | Notebook    | [ceb9ca591f](https://linux-hardware.org/?probe=ceb9ca591f) | Aug 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| MSI           | MS-16GF                     | Notebook    | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 4293B43       | Notebook    | [7accb85da9](https://linux-hardware.org/?probe=7accb85da9) | Jul 30, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| HP            | Presario CQ42               | Notebook    | [fa65f13c3b](https://linux-hardware.org/?probe=fa65f13c3b) | Jul 23, 2021 |
| Dell          | Inspiron 3493               | Notebook    | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9182648939](https://linux-hardware.org/?probe=9182648939) | Jul 19, 2021 |
| Acer          | TravelMate P2410-G2-M       | Notebook    | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| MSI           | MS-7309                     | Desktop     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| Dell          | 0CXTWJ A00                  | All in one  | [c8d344a37f](https://linux-hardware.org/?probe=c8d344a37f) | Jul 07, 2021 |
| ASUSTek       | K401UQ                      | Notebook    | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | G73Jw                       | Notebook    | [b1d6609434](https://linux-hardware.org/?probe=b1d6609434) | Jul 03, 2021 |
| Lenovo        | ThinkPad W510 4391BY8       | Notebook    | [12d0ff5c27](https://linux-hardware.org/?probe=12d0ff5c27) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [bc19b4b3bf](https://linux-hardware.org/?probe=bc19b4b3bf) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c1442501a0](https://linux-hardware.org/?probe=c1442501a0) | Jul 03, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude 7414               | Notebook    | [5557aada9a](https://linux-hardware.org/?probe=5557aada9a) | Jun 28, 2021 |
| ASUSTek       | X441UA                      | Notebook    | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [1759d8d1f8](https://linux-hardware.org/?probe=1759d8d1f8) | Jun 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| ASUSTek       | T101HA                      | Tablet      | [ae0e0904db](https://linux-hardware.org/?probe=ae0e0904db) | Jun 20, 2021 |
| ASUSTek       | T101HA                      | Tablet      | [5482959345](https://linux-hardware.org/?probe=5482959345) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Acer          | A315-41G                    | Notebook    | [c3b9603724](https://linux-hardware.org/?probe=c3b9603724) | Jun 15, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Acer          | Aspire E5-471               | Notebook    | [f15409e7cc](https://linux-hardware.org/?probe=f15409e7cc) | Jun 10, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [2e841a4dc4](https://linux-hardware.org/?probe=2e841a4dc4) | Jun 09, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [a5547e4146](https://linux-hardware.org/?probe=a5547e4146) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d15f22008c](https://linux-hardware.org/?probe=d15f22008c) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [82dff2688d](https://linux-hardware.org/?probe=82dff2688d) | Jun 07, 2021 |
| Intel         | H61                         | Desktop     | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [ad461cbf3e](https://linux-hardware.org/?probe=ad461cbf3e) | Jun 07, 2021 |
| HP            | 245 G6                      | Notebook    | [a3594ab925](https://linux-hardware.org/?probe=a3594ab925) | Jun 03, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| ONDA          | V919 AIR CH                 | Tablet      | [3317ba664d](https://linux-hardware.org/?probe=3317ba664d) | May 28, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [499479904d](https://linux-hardware.org/?probe=499479904d) | May 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| HP            | Notebook                    | Notebook    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | Notebook    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [834d15c08c](https://linux-hardware.org/?probe=834d15c08c) | May 16, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [0ece4b9e9e](https://linux-hardware.org/?probe=0ece4b9e9e) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| Toshiba       | Satellite C850-B797         | Notebook    | [1355c6e459](https://linux-hardware.org/?probe=1355c6e459) | May 13, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | Notebook    | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [5ad427cffb](https://linux-hardware.org/?probe=5ad427cffb) | May 04, 2021 |
| ASRock        | G965M-S                     | Desktop     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [bed13d11ad](https://linux-hardware.org/?probe=bed13d11ad) | May 02, 2021 |
| Dell          | 00NH4P A09                  | Server      | [d03d113d9f](https://linux-hardware.org/?probe=d03d113d9f) | May 02, 2021 |
| Intel         | H61                         | Desktop     | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | Desktop     | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | Desktop     | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | Desktop     | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Notebook      | N150CU                      | Notebook    | [e62762a731](https://linux-hardware.org/?probe=e62762a731) | Apr 14, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| Lenovo        | ThinkPad X260 20F5A0HB00    | Notebook    | [9163ce31dc](https://linux-hardware.org/?probe=9163ce31dc) | Apr 14, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1263e938c8](https://linux-hardware.org/?probe=1263e938c8) | Apr 13, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [5fada7c64a](https://linux-hardware.org/?probe=5fada7c64a) | Apr 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95df5a7ac5](https://linux-hardware.org/?probe=95df5a7ac5) | Apr 06, 2021 |
| HP            | x2 210 G2                   | Tablet      | [1c188b150f](https://linux-hardware.org/?probe=1c188b150f) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 2325BG3       | Notebook    | [90f6078b02](https://linux-hardware.org/?probe=90f6078b02) | Apr 04, 2021 |
| ASUSTek       | X555DG                      | Notebook    | [334a8d4184](https://linux-hardware.org/?probe=334a8d4184) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2c67d604ff](https://linux-hardware.org/?probe=2c67d604ff) | Mar 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [87e7b3b248](https://linux-hardware.org/?probe=87e7b3b248) | Mar 22, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [1d422767e1](https://linux-hardware.org/?probe=1d422767e1) | Mar 20, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [ccb5c756ee](https://linux-hardware.org/?probe=ccb5c756ee) | Mar 20, 2021 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Acer          | AOD255                      | Notebook    | [2e5b228a04](https://linux-hardware.org/?probe=2e5b228a04) | Mar 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [843d061b78](https://linux-hardware.org/?probe=843d061b78) | Mar 15, 2021 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [87cabd058e](https://linux-hardware.org/?probe=87cabd058e) | Mar 13, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [8cb18a4f6c](https://linux-hardware.org/?probe=8cb18a4f6c) | Mar 11, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [a6e9e8ea5e](https://linux-hardware.org/?probe=a6e9e8ea5e) | Mar 11, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Acer          | AOD255                      | Notebook    | [f3a5b4b0e4](https://linux-hardware.org/?probe=f3a5b4b0e4) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | Desktop     | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d9708c63f5](https://linux-hardware.org/?probe=d9708c63f5) | Mar 04, 2021 |
| Dell          | Precision 3551              | Notebook    | [d75a598209](https://linux-hardware.org/?probe=d75a598209) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [bc879be58b](https://linux-hardware.org/?probe=bc879be58b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [27b7f94851](https://linux-hardware.org/?probe=27b7f94851) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [935f9c5571](https://linux-hardware.org/?probe=935f9c5571) | Mar 03, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a758fdf9af](https://linux-hardware.org/?probe=a758fdf9af) | Mar 01, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a8bd4eacfc](https://linux-hardware.org/?probe=a8bd4eacfc) | Feb 28, 2021 |
| HP            | Pavilion 10 TS              | Notebook    | [5998c38555](https://linux-hardware.org/?probe=5998c38555) | Feb 26, 2021 |
| Intel         | DP67DE AAG10217-205         | Desktop     | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | Desktop     | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| Dell          | Latitude E6220              | Notebook    | [1c0ab9fab1](https://linux-hardware.org/?probe=1c0ab9fab1) | Feb 23, 2021 |
| Dell          | Latitude E6220              | Notebook    | [19e1a4a1d6](https://linux-hardware.org/?probe=19e1a4a1d6) | Feb 23, 2021 |
| Dell          | Inspiron 3493               | Notebook    | [684245175e](https://linux-hardware.org/?probe=684245175e) | Feb 20, 2021 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [7581904d41](https://linux-hardware.org/?probe=7581904d41) | Feb 20, 2021 |
| Apple         | MacBookPro15,1              | Notebook    | [a148b9034a](https://linux-hardware.org/?probe=a148b9034a) | Feb 19, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [f6830c6ac2](https://linux-hardware.org/?probe=f6830c6ac2) | Feb 18, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [ecddf05f3e](https://linux-hardware.org/?probe=ecddf05f3e) | Feb 16, 2021 |
| BAKED         | P7xxDM2(-G)                 | Notebook    | [824169b9f7](https://linux-hardware.org/?probe=824169b9f7) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [8be5048c51](https://linux-hardware.org/?probe=8be5048c51) | Feb 15, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [8da12e7518](https://linux-hardware.org/?probe=8da12e7518) | Feb 14, 2021 |
| Nvidia        | Tegra                       | Soc         | [b49723230a](https://linux-hardware.org/?probe=b49723230a) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [5e5731f2b0](https://linux-hardware.org/?probe=5e5731f2b0) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [90847dec81](https://linux-hardware.org/?probe=90847dec81) | Feb 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e97c86bc3](https://linux-hardware.org/?probe=6e97c86bc3) | Feb 10, 2021 |
| HP            | Notebook                    | Notebook    | [5224b13971](https://linux-hardware.org/?probe=5224b13971) | Feb 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [93004b8e8f](https://linux-hardware.org/?probe=93004b8e8f) | Feb 07, 2021 |
| Nvidia        | Tegra                       | Soc         | [ed22dcb6c2](https://linux-hardware.org/?probe=ed22dcb6c2) | Feb 07, 2021 |
| Dell          | Inspiron 7586               | Notebook    | [7e6463f517](https://linux-hardware.org/?probe=7e6463f517) | Feb 05, 2021 |
| ASUSTek       | X505BA                      | Notebook    | [8059f98337](https://linux-hardware.org/?probe=8059f98337) | Feb 03, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| HP            | Presario CQ43               | Notebook    | [13eb02bc61](https://linux-hardware.org/?probe=13eb02bc61) | Feb 02, 2021 |
| HP            | Presario CQ43               | Notebook    | [a6d1b8df1e](https://linux-hardware.org/?probe=a6d1b8df1e) | Feb 02, 2021 |
| Notebook      | N150CU                      | Notebook    | [7753afd04f](https://linux-hardware.org/?probe=7753afd04f) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | Notebook    | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ab91702ac3](https://linux-hardware.org/?probe=ab91702ac3) | Jan 26, 2021 |
| GreatWall     | K41                         | Notebook    | [ddf99d904e](https://linux-hardware.org/?probe=ddf99d904e) | Jan 25, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | X555LN                      | Notebook    | [e649cc1304](https://linux-hardware.org/?probe=e649cc1304) | Jan 24, 2021 |
| ASUSTek       | X441UVK                     | Notebook    | [c73eaa8a8f](https://linux-hardware.org/?probe=c73eaa8a8f) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0ca25f14fb](https://linux-hardware.org/?probe=0ca25f14fb) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [419800f72d](https://linux-hardware.org/?probe=419800f72d) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [844d185dae](https://linux-hardware.org/?probe=844d185dae) | Jan 21, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [91a85ad436](https://linux-hardware.org/?probe=91a85ad436) | Jan 20, 2021 |
| Supermicro    | X9DRD-iF                    | Server      | [afe42b7e58](https://linux-hardware.org/?probe=afe42b7e58) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [62de1cd91f](https://linux-hardware.org/?probe=62de1cd91f) | Jan 16, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [edcaecc674](https://linux-hardware.org/?probe=edcaecc674) | Jan 14, 2021 |
| ASUSTek       | K46CM                       | Notebook    | [e5d77ec648](https://linux-hardware.org/?probe=e5d77ec648) | Jan 14, 2021 |
| Dell          | Precision 3551              | Notebook    | [c6524a92a4](https://linux-hardware.org/?probe=c6524a92a4) | Jan 13, 2021 |
| Intel         | H61                         | Desktop     | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6d637febe2](https://linux-hardware.org/?probe=6d637febe2) | Jan 10, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [05b3190864](https://linux-hardware.org/?probe=05b3190864) | Jan 08, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [0d58fd33df](https://linux-hardware.org/?probe=0d58fd33df) | Jan 07, 2021 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [d1947d8c18](https://linux-hardware.org/?probe=d1947d8c18) | Jan 07, 2021 |
| Dell          | System XPS L502X            | Notebook    | [6548d3214b](https://linux-hardware.org/?probe=6548d3214b) | Jan 06, 2021 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4e9f49422a](https://linux-hardware.org/?probe=4e9f49422a) | Jan 04, 2021 |
| BAKED         | P7xxDM2(-G)                 | Notebook    | [c4206ecc26](https://linux-hardware.org/?probe=c4206ecc26) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | Notebook    | [f995163ff4](https://linux-hardware.org/?probe=f995163ff4) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | Notebook    | [2758658d90](https://linux-hardware.org/?probe=2758658d90) | Jan 04, 2021 |
| Biostar       | H61MHV                      | Desktop     | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6b7c6db0c5](https://linux-hardware.org/?probe=6b7c6db0c5) | Dec 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [10b0b04256](https://linux-hardware.org/?probe=10b0b04256) | Dec 30, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [10d64eecc5](https://linux-hardware.org/?probe=10d64eecc5) | Dec 30, 2020 |
| Gigabyte      | 970A-UD3                    | Desktop     | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | Desktop     | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [e850bec31a](https://linux-hardware.org/?probe=e850bec31a) | Dec 29, 2020 |
| PCSMART       | Unknown                     | Desktop     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4ea54770](https://linux-hardware.org/?probe=3c4ea54770) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d61f2aa238](https://linux-hardware.org/?probe=d61f2aa238) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [bca2708dcd](https://linux-hardware.org/?probe=bca2708dcd) | Dec 25, 2020 |
| ASUSTek       | X450CP                      | Notebook    | [1d2d82e5ee](https://linux-hardware.org/?probe=1d2d82e5ee) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [e395d72cbb](https://linux-hardware.org/?probe=e395d72cbb) | Dec 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [0f86ea7cab](https://linux-hardware.org/?probe=0f86ea7cab) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [c23ae5c475](https://linux-hardware.org/?probe=c23ae5c475) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | Notebook    | [2475252354](https://linux-hardware.org/?probe=2475252354) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | Notebook    | [a08f4cf4e5](https://linux-hardware.org/?probe=a08f4cf4e5) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [dd0d449586](https://linux-hardware.org/?probe=dd0d449586) | Dec 14, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [246d659f60](https://linux-hardware.org/?probe=246d659f60) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [1a353b9226](https://linux-hardware.org/?probe=1a353b9226) | Dec 08, 2020 |
| ECS           | G31T-M7                     | Desktop     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3962cbfb58](https://linux-hardware.org/?probe=3962cbfb58) | Dec 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3d5a1c07e6](https://linux-hardware.org/?probe=3d5a1c07e6) | Dec 05, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [02fb63a36f](https://linux-hardware.org/?probe=02fb63a36f) | Dec 04, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [490bae951e](https://linux-hardware.org/?probe=490bae951e) | Dec 01, 2020 |
| Lenovo        | G470 20078                  | Notebook    | [b0564c0e50](https://linux-hardware.org/?probe=b0564c0e50) | Dec 01, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | IdeaPad U510 20191          | Notebook    | [895b641220](https://linux-hardware.org/?probe=895b641220) | Nov 30, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [0a4b399149](https://linux-hardware.org/?probe=0a4b399149) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [0c9f7ea289](https://linux-hardware.org/?probe=0c9f7ea289) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [a5f5b59788](https://linux-hardware.org/?probe=a5f5b59788) | Nov 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [503b8f9701](https://linux-hardware.org/?probe=503b8f9701) | Nov 25, 2020 |
| ASUSTek       | X441NA                      | Notebook    | [61a5d6947b](https://linux-hardware.org/?probe=61a5d6947b) | Nov 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [73dc6959d6](https://linux-hardware.org/?probe=73dc6959d6) | Nov 23, 2020 |
| Unknown       | Unknown                     | Notebook    | [b0c0ef90cd](https://linux-hardware.org/?probe=b0c0ef90cd) | Nov 23, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a997f8c186](https://linux-hardware.org/?probe=a997f8c186) | Nov 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e24dba10a2](https://linux-hardware.org/?probe=e24dba10a2) | Nov 22, 2020 |
| ASUSTek       | X441NA                      | Notebook    | [e301cabf95](https://linux-hardware.org/?probe=e301cabf95) | Nov 21, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [5021095fd1](https://linux-hardware.org/?probe=5021095fd1) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [e5e8cfd574](https://linux-hardware.org/?probe=e5e8cfd574) | Nov 19, 2020 |
| ASRock        | AB350M-HDV                  | Desktop     | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [026fdce11f](https://linux-hardware.org/?probe=026fdce11f) | Nov 13, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [b3752255e5](https://linux-hardware.org/?probe=b3752255e5) | Nov 13, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| HP            | ProBook 6450b               | Notebook    | [74c2b345b8](https://linux-hardware.org/?probe=74c2b345b8) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [5efbf0cf43](https://linux-hardware.org/?probe=5efbf0cf43) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3f9b54f16c](https://linux-hardware.org/?probe=3f9b54f16c) | Nov 05, 2020 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| Lenovo        | G450 2949                   | Notebook    | [f9bb66b7a2](https://linux-hardware.org/?probe=f9bb66b7a2) | Nov 03, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | Desktop     | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [f3e110826b](https://linux-hardware.org/?probe=f3e110826b) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [9786cce501](https://linux-hardware.org/?probe=9786cce501) | Nov 01, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [dcd8f2aa99](https://linux-hardware.org/?probe=dcd8f2aa99) | Oct 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cafb41376f](https://linux-hardware.org/?probe=cafb41376f) | Oct 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [fa89c085cf](https://linux-hardware.org/?probe=fa89c085cf) | Oct 25, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [7157a6069b](https://linux-hardware.org/?probe=7157a6069b) | Oct 21, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [fb18c13ac7](https://linux-hardware.org/?probe=fb18c13ac7) | Oct 21, 2020 |
| MSI           | H81M-E33                    | Desktop     | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | Desktop     | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [89c3fe76c0](https://linux-hardware.org/?probe=89c3fe76c0) | Oct 18, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [0a4d06561e](https://linux-hardware.org/?probe=0a4d06561e) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [8fb2a0621d](https://linux-hardware.org/?probe=8fb2a0621d) | Oct 12, 2020 |
| Lenovo        | G40-45 80E1                 | Notebook    | [eefc7c92b2](https://linux-hardware.org/?probe=eefc7c92b2) | Oct 11, 2020 |
| Dell          | Latitude E7270              | Notebook    | [cff6ba0c00](https://linux-hardware.org/?probe=cff6ba0c00) | Oct 11, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [e04a055ab8](https://linux-hardware.org/?probe=e04a055ab8) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [c376c39381](https://linux-hardware.org/?probe=c376c39381) | Oct 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [4e2c32a972](https://linux-hardware.org/?probe=4e2c32a972) | Oct 07, 2020 |
| Dell          | Inspiron 3480               | Notebook    | [243905bcf2](https://linux-hardware.org/?probe=243905bcf2) | Oct 06, 2020 |
| Dell          | 0CXTWJ A00                  | All in one  | [d90e79c0b2](https://linux-hardware.org/?probe=d90e79c0b2) | Oct 05, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | Desktop     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [eaeba54519](https://linux-hardware.org/?probe=eaeba54519) | Oct 05, 2020 |
| MPS Mayori... | COIN ST800EDU               | Notebook    | [11e4ae4bfe](https://linux-hardware.org/?probe=11e4ae4bfe) | Oct 03, 2020 |
| MPS Mayori... | COIN ST800EDU               | Notebook    | [38a7d9f974](https://linux-hardware.org/?probe=38a7d9f974) | Oct 03, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [eb0e17a039](https://linux-hardware.org/?probe=eb0e17a039) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e0afc29d83](https://linux-hardware.org/?probe=e0afc29d83) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [4ff7a5528c](https://linux-hardware.org/?probe=4ff7a5528c) | Sep 29, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [21ecdf1804](https://linux-hardware.org/?probe=21ecdf1804) | Sep 28, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [393e09d070](https://linux-hardware.org/?probe=393e09d070) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7ec7b7dbb0](https://linux-hardware.org/?probe=7ec7b7dbb0) | Sep 27, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [be76b68bff](https://linux-hardware.org/?probe=be76b68bff) | Sep 25, 2020 |
| HP            | Notebook                    | Notebook    | [97099ba5b3](https://linux-hardware.org/?probe=97099ba5b3) | Sep 23, 2020 |
| Dell          | 0MM599                      | Desktop     | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [4b3f7c31cc](https://linux-hardware.org/?probe=4b3f7c31cc) | Sep 21, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [bf2a498d90](https://linux-hardware.org/?probe=bf2a498d90) | Sep 21, 2020 |
| ASUSTek       | X441UVK                     | Notebook    | [4be17c95ab](https://linux-hardware.org/?probe=4be17c95ab) | Sep 18, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| Dell          | Latitude E7270              | Notebook    | [76c31048e9](https://linux-hardware.org/?probe=76c31048e9) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | Notebook    | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| TYAN Compu... | S4885 Thunder K8SQ S4885    | Server      | [64251b3f2a](https://linux-hardware.org/?probe=64251b3f2a) | Sep 12, 2020 |
| Dell          | Studio 1558                 | Notebook    | [bfa6ee72ad](https://linux-hardware.org/?probe=bfa6ee72ad) | Sep 11, 2020 |
| Dell          | Studio 1558                 | Notebook    | [09283ede94](https://linux-hardware.org/?probe=09283ede94) | Sep 11, 2020 |
| Acer          | TravelMate 5744             | Notebook    | [cd7e3646ff](https://linux-hardware.org/?probe=cd7e3646ff) | Sep 09, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Dell          | Inspiron N5040              | Notebook    | [7d81a97615](https://linux-hardware.org/?probe=7d81a97615) | Sep 07, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [c184b08cc3](https://linux-hardware.org/?probe=c184b08cc3) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51936947d5](https://linux-hardware.org/?probe=51936947d5) | Sep 05, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [11adb16243](https://linux-hardware.org/?probe=11adb16243) | Sep 03, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | X442UA                      | Notebook    | [cad592ae29](https://linux-hardware.org/?probe=cad592ae29) | Aug 31, 2020 |
| ASUSTek       | X442UA                      | Notebook    | [7697815bb5](https://linux-hardware.org/?probe=7697815bb5) | Aug 31, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Samsung       | R430/R480/R440              | Notebook    | [c37003dbfc](https://linux-hardware.org/?probe=c37003dbfc) | Aug 30, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [c1fe24f51b](https://linux-hardware.org/?probe=c1fe24f51b) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [eb0990afbe](https://linux-hardware.org/?probe=eb0990afbe) | Aug 23, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [f43e5244bc](https://linux-hardware.org/?probe=f43e5244bc) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Dell          | 0D6H9T A01                  | Desktop     | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | Desktop     | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [27987ebfb1](https://linux-hardware.org/?probe=27987ebfb1) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2151fb7ccb](https://linux-hardware.org/?probe=2151fb7ccb) | Aug 15, 2020 |
| MSI           | A68HM-E33                   | Desktop     | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | Desktop     | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| Acer          | AOD255                      | Notebook    | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2a6b9c2763](https://linux-hardware.org/?probe=2a6b9c2763) | Aug 11, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c958c50dad](https://linux-hardware.org/?probe=c958c50dad) | Aug 07, 2020 |
| HP            | ENVY 15                     | Notebook    | [d2fab519a5](https://linux-hardware.org/?probe=d2fab519a5) | Aug 04, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Toshiba       | Satellite L645              | Notebook    | [2f81e753a6](https://linux-hardware.org/?probe=2f81e753a6) | Jul 31, 2020 |
| HP            | 245 G6                      | Notebook    | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [1b4b43f382](https://linux-hardware.org/?probe=1b4b43f382) | Jul 29, 2020 |
| HP            | G42                         | Notebook    | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0928c9c524](https://linux-hardware.org/?probe=0928c9c524) | Jul 27, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [26022f582b](https://linux-hardware.org/?probe=26022f582b) | Jul 26, 2020 |
| HP            | Compaq CQ45                 | Notebook    | [74cad2f13e](https://linux-hardware.org/?probe=74cad2f13e) | Jul 26, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [75928e5332](https://linux-hardware.org/?probe=75928e5332) | Jul 25, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b4f52ba1be](https://linux-hardware.org/?probe=b4f52ba1be) | Jul 25, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [17ecc94bc0](https://linux-hardware.org/?probe=17ecc94bc0) | Jul 24, 2020 |
| Toshiba       | Satellite M505              | Notebook    | [518faca568](https://linux-hardware.org/?probe=518faca568) | Jul 21, 2020 |
| Toshiba       | Satellite S75-A             | Notebook    | [a2fc5378af](https://linux-hardware.org/?probe=a2fc5378af) | Jul 21, 2020 |
| Toshiba       | Satellite M505              | Notebook    | [64f79b1c45](https://linux-hardware.org/?probe=64f79b1c45) | Jul 21, 2020 |
| Dell          | Latitude E7270              | Notebook    | [3240f0ae94](https://linux-hardware.org/?probe=3240f0ae94) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1839ba41d3](https://linux-hardware.org/?probe=1839ba41d3) | Jul 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f179e69271](https://linux-hardware.org/?probe=f179e69271) | Jul 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [543185b30a](https://linux-hardware.org/?probe=543185b30a) | Jul 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e66cd74e47](https://linux-hardware.org/?probe=e66cd74e47) | Jul 18, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| ASUSTek       | X456UA                      | Notebook    | [0bc503ae0b](https://linux-hardware.org/?probe=0bc503ae0b) | Jul 16, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8a858d88d0](https://linux-hardware.org/?probe=8a858d88d0) | Jul 15, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [260563b336](https://linux-hardware.org/?probe=260563b336) | Jul 15, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| ASUSTek       | X456UA                      | Notebook    | [6b61996456](https://linux-hardware.org/?probe=6b61996456) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [858cd73913](https://linux-hardware.org/?probe=858cd73913) | Jul 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [fc5d45e94a](https://linux-hardware.org/?probe=fc5d45e94a) | Jul 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | Desktop     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | Desktop     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| HP            | Compaq 6730s                | Notebook    | [e128a9542c](https://linux-hardware.org/?probe=e128a9542c) | Jul 04, 2020 |
| Sony          | VAIO                        | All in one  | [f52b60725c](https://linux-hardware.org/?probe=f52b60725c) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [dd5e302721](https://linux-hardware.org/?probe=dd5e302721) | Jul 03, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [5260584205](https://linux-hardware.org/?probe=5260584205) | Jun 30, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [0999108dfb](https://linux-hardware.org/?probe=0999108dfb) | Jun 29, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a54dfa2b8b](https://linux-hardware.org/?probe=a54dfa2b8b) | Jun 27, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [fae71e18b2](https://linux-hardware.org/?probe=fae71e18b2) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [7e4c8ea12c](https://linux-hardware.org/?probe=7e4c8ea12c) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [5e921d68ff](https://linux-hardware.org/?probe=5e921d68ff) | Jun 25, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7e8026e797](https://linux-hardware.org/?probe=7e8026e797) | Jun 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [29f9ac42d8](https://linux-hardware.org/?probe=29f9ac42d8) | Jun 21, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [9a14812888](https://linux-hardware.org/?probe=9a14812888) | Jun 20, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3b75e28c9d](https://linux-hardware.org/?probe=3b75e28c9d) | Jun 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [73cda410f2](https://linux-hardware.org/?probe=73cda410f2) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a7d7f2f4f3](https://linux-hardware.org/?probe=a7d7f2f4f3) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d194146ff8](https://linux-hardware.org/?probe=d194146ff8) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b4fdab686](https://linux-hardware.org/?probe=5b4fdab686) | Jun 18, 2020 |
| Biostar       | N68S3+                      | Desktop     | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| HP            | 8245 001                    | All in one  | [b348bc9186](https://linux-hardware.org/?probe=b348bc9186) | Jun 13, 2020 |
| HP            | 8245 001                    | All in one  | [3d2e0b5d1e](https://linux-hardware.org/?probe=3d2e0b5d1e) | Jun 13, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [a1ae232e58](https://linux-hardware.org/?probe=a1ae232e58) | Jun 13, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Dell          | 054KM3 A00                  | Desktop     | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [2212090ff2](https://linux-hardware.org/?probe=2212090ff2) | Jun 10, 2020 |
| Gateway       | M-6319                      | Notebook    | [5b3e8b9ef1](https://linux-hardware.org/?probe=5b3e8b9ef1) | Jun 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [52c8b6876e](https://linux-hardware.org/?probe=52c8b6876e) | Jun 08, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [aad1de590c](https://linux-hardware.org/?probe=aad1de590c) | Jun 07, 2020 |
| Acer          | Aspire E1-421               | Notebook    | [81073e838e](https://linux-hardware.org/?probe=81073e838e) | Jun 05, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [e7901f9d16](https://linux-hardware.org/?probe=e7901f9d16) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [9585e46a59](https://linux-hardware.org/?probe=9585e46a59) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430u 86143HU      | Notebook    | [5a3bf0a8f5](https://linux-hardware.org/?probe=5a3bf0a8f5) | Jun 03, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [d45d40decd](https://linux-hardware.org/?probe=d45d40decd) | Jun 03, 2020 |
| ASUSTek       | K46CM                       | Notebook    | [994e39c619](https://linux-hardware.org/?probe=994e39c619) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| Acer          | Aspire E1-421               | Notebook    | [618908f152](https://linux-hardware.org/?probe=618908f152) | May 27, 2020 |
| ASUSTek       | X411UQ                      | Notebook    | [a3e9e016a6](https://linux-hardware.org/?probe=a3e9e016a6) | May 27, 2020 |
| Lenovo        | ThinkPad A475 20KMS0NG00    | Notebook    | [4572fa1657](https://linux-hardware.org/?probe=4572fa1657) | May 27, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [169492fdd8](https://linux-hardware.org/?probe=169492fdd8) | May 26, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [871784f430](https://linux-hardware.org/?probe=871784f430) | May 26, 2020 |
| HP            | 430                         | Notebook    | [54ba3df0c8](https://linux-hardware.org/?probe=54ba3df0c8) | May 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c4c76cecbd](https://linux-hardware.org/?probe=c4c76cecbd) | May 23, 2020 |
| Lenovo        | 36DC SDK0J40679 WIN 3273... | All in one  | [a4afd5181f](https://linux-hardware.org/?probe=a4afd5181f) | May 23, 2020 |
| Lenovo        | 36DC SDK0J40679 WIN 3273... | All in one  | [3a811fe4cb](https://linux-hardware.org/?probe=3a811fe4cb) | May 23, 2020 |
| MSI           | A55M-P35                    | Desktop     | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| HP            | Laptop 14-bw0xx             | Notebook    | [c9c485db32](https://linux-hardware.org/?probe=c9c485db32) | May 22, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| Sony          | SVF14A15CLB                 | Notebook    | [7fb2e1bda0](https://linux-hardware.org/?probe=7fb2e1bda0) | May 20, 2020 |
| Samsung       | 535U3C                      | Notebook    | [b3983a1b17](https://linux-hardware.org/?probe=b3983a1b17) | May 20, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| Lenovo        | Larne CRB 31900059 STD      | All in one  | [92b26540f0](https://linux-hardware.org/?probe=92b26540f0) | May 18, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [fe9c89b85a](https://linux-hardware.org/?probe=fe9c89b85a) | May 17, 2020 |
| Lenovo        | Larne CRB 31900059 STD      | All in one  | [6da745bc99](https://linux-hardware.org/?probe=6da745bc99) | May 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| Lenovo        | G40-80 80E4                 | Notebook    | [70a6d29aa3](https://linux-hardware.org/?probe=70a6d29aa3) | May 15, 2020 |
| Samsung       | 535U3C                      | Notebook    | [fe2d93033d](https://linux-hardware.org/?probe=fe2d93033d) | May 13, 2020 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5ed9a929ec](https://linux-hardware.org/?probe=5ed9a929ec) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| Sony          | SVE14121CLP                 | Notebook    | [df7e4c2b9f](https://linux-hardware.org/?probe=df7e4c2b9f) | May 09, 2020 |
| ASRock        | G965M-S                     | Desktop     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | Desktop     | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| HP            | 8381 1000                   | All in one  | [abf977e38b](https://linux-hardware.org/?probe=abf977e38b) | May 03, 2020 |
| ECS           | H81H3-M4                    | Desktop     | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [69942e79bd](https://linux-hardware.org/?probe=69942e79bd) | May 02, 2020 |
| Lenovo        | Larne CRB 31900059 WIN 2... | All in one  | [a7430e2754](https://linux-hardware.org/?probe=a7430e2754) | May 01, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | Desktop     | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| HP            | 8381 1000                   | All in one  | [97a3637eb5](https://linux-hardware.org/?probe=97a3637eb5) | Apr 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [91627f8ac4](https://linux-hardware.org/?probe=91627f8ac4) | Apr 29, 2020 |
| Toshiba       | Satellite L515              | Notebook    | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Inspur        | M11JB R2.0/R1.1             | Notebook    | [7f92b47ef4](https://linux-hardware.org/?probe=7f92b47ef4) | Apr 27, 2020 |
| HP            | Pavilion dv6                | Notebook    | [163dac19b3](https://linux-hardware.org/?probe=163dac19b3) | Apr 26, 2020 |
| HP            | Pavilion dv6                | Notebook    | [13cb9e8a90](https://linux-hardware.org/?probe=13cb9e8a90) | Apr 26, 2020 |
| MSI           | 970A-G43 PLUS               | Desktop     | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Dell          | G5 5587                     | Notebook    | [dd4521b554](https://linux-hardware.org/?probe=dd4521b554) | Apr 21, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e5243ea838](https://linux-hardware.org/?probe=e5243ea838) | Apr 21, 2020 |
| HP            | Pavilion g4                 | Notebook    | [7e9785b653](https://linux-hardware.org/?probe=7e9785b653) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | Notebook    | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| HP            | Pavilion g4                 | Notebook    | [3c6a4199c7](https://linux-hardware.org/?probe=3c6a4199c7) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Acer          | Aspire V5-471               | Notebook    | [6540209d65](https://linux-hardware.org/?probe=6540209d65) | Apr 16, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [010fdcb7ab](https://linux-hardware.org/?probe=010fdcb7ab) | Apr 16, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8eae2753ce](https://linux-hardware.org/?probe=8eae2753ce) | Apr 16, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6ec2d663e5](https://linux-hardware.org/?probe=6ec2d663e5) | Apr 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a4b76d231e](https://linux-hardware.org/?probe=a4b76d231e) | Apr 15, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [cb760929c4](https://linux-hardware.org/?probe=cb760929c4) | Apr 14, 2020 |
| MSI           | MS-7309                     | Desktop     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [25e23d0bf7](https://linux-hardware.org/?probe=25e23d0bf7) | Apr 13, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | Notebook    | [823afb58b0](https://linux-hardware.org/?probe=823afb58b0) | Apr 12, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | Notebook    | [90b23eb96e](https://linux-hardware.org/?probe=90b23eb96e) | Apr 12, 2020 |
| Dell          | System Inspiron 5420        | Notebook    | [f74d698b46](https://linux-hardware.org/?probe=f74d698b46) | Apr 11, 2020 |
| Toshiba       | Satellite A505              | Notebook    | [f7f3c03ad9](https://linux-hardware.org/?probe=f7f3c03ad9) | Apr 10, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4c866db0d](https://linux-hardware.org/?probe=c4c866db0d) | Apr 04, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0bb263546b](https://linux-hardware.org/?probe=0bb263546b) | Apr 04, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f9921167fc](https://linux-hardware.org/?probe=f9921167fc) | Apr 02, 2020 |
| HP            | Mini 311-1100               | Notebook    | [d4918f7f3c](https://linux-hardware.org/?probe=d4918f7f3c) | Mar 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| ASUSTek       | X455LD                      | Notebook    | [ec6c4486ca](https://linux-hardware.org/?probe=ec6c4486ca) | Mar 26, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [60f3879e96](https://linux-hardware.org/?probe=60f3879e96) | Mar 25, 2020 |
| Acer          | Aspire 4750                 | Notebook    | [4757577c86](https://linux-hardware.org/?probe=4757577c86) | Mar 23, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [38330a61d2](https://linux-hardware.org/?probe=38330a61d2) | Mar 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S0VE00    | Notebook    | [4d090cecde](https://linux-hardware.org/?probe=4d090cecde) | Mar 22, 2020 |
| HP            | 3048h                       | Desktop     | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [38d4ca1005](https://linux-hardware.org/?probe=38d4ca1005) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [d42c9c08ee](https://linux-hardware.org/?probe=d42c9c08ee) | Mar 19, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [1279383fb8](https://linux-hardware.org/?probe=1279383fb8) | Mar 17, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| ASUSTek       | X505BP                      | Notebook    | [11da78a649](https://linux-hardware.org/?probe=11da78a649) | Mar 16, 2020 |
| Google        | Pantheon                    | Notebook    | [20acb09771](https://linux-hardware.org/?probe=20acb09771) | Mar 09, 2020 |
| Sony          | VGN-SR51MF_S                | Notebook    | [8783bf4fe5](https://linux-hardware.org/?probe=8783bf4fe5) | Mar 09, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [def3aa7871](https://linux-hardware.org/?probe=def3aa7871) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [6dccf0159e](https://linux-hardware.org/?probe=6dccf0159e) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [6ec6d9847c](https://linux-hardware.org/?probe=6ec6d9847c) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [e5c1b0bdce](https://linux-hardware.org/?probe=e5c1b0bdce) | Mar 07, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [20a4bdc803](https://linux-hardware.org/?probe=20a4bdc803) | Mar 05, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b4898d9e36](https://linux-hardware.org/?probe=b4898d9e36) | Mar 05, 2020 |
| ASUSTek       | X505BP                      | Notebook    | [88ec1bf424](https://linux-hardware.org/?probe=88ec1bf424) | Feb 29, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [fd8dfe766e](https://linux-hardware.org/?probe=fd8dfe766e) | Feb 24, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [96c28903af](https://linux-hardware.org/?probe=96c28903af) | Feb 24, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [1ee504b68f](https://linux-hardware.org/?probe=1ee504b68f) | Feb 24, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [c74cb1d856](https://linux-hardware.org/?probe=c74cb1d856) | Feb 22, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [303f2ada85](https://linux-hardware.org/?probe=303f2ada85) | Feb 19, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | Notebook    | [968045d52d](https://linux-hardware.org/?probe=968045d52d) | Feb 19, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [ed95aa0537](https://linux-hardware.org/?probe=ed95aa0537) | Feb 16, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84c6ace757](https://linux-hardware.org/?probe=84c6ace757) | Feb 15, 2020 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [d0276ea845](https://linux-hardware.org/?probe=d0276ea845) | Feb 14, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [1d69448de6](https://linux-hardware.org/?probe=1d69448de6) | Feb 09, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [6d4ecdb510](https://linux-hardware.org/?probe=6d4ecdb510) | Feb 09, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | Notebook    | [30b395a14f](https://linux-hardware.org/?probe=30b395a14f) | Feb 08, 2020 |
| Dell          | Vostro 3400                 | Notebook    | [7ad384214e](https://linux-hardware.org/?probe=7ad384214e) | Feb 06, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [b3a11d5f5d](https://linux-hardware.org/?probe=b3a11d5f5d) | Jan 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [25f6d11655](https://linux-hardware.org/?probe=25f6d11655) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| ASUSTek       | X550ZE                      | Notebook    | [e06f76becf](https://linux-hardware.org/?probe=e06f76becf) | Jan 08, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [30389049c2](https://linux-hardware.org/?probe=30389049c2) | Jan 07, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [06421a5c44](https://linux-hardware.org/?probe=06421a5c44) | Jan 05, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [db9c0c83ce](https://linux-hardware.org/?probe=db9c0c83ce) | Jan 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [854604bdad](https://linux-hardware.org/?probe=854604bdad) | Dec 31, 2019 |
| ASRock        | G41M-VS3                    | Desktop     | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | Notebook    | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b6846dfd95](https://linux-hardware.org/?probe=b6846dfd95) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [75a94cfe2f](https://linux-hardware.org/?probe=75a94cfe2f) | Dec 28, 2019 |
| Unknown       | GSUO H61V10C                | Desktop     | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [17ed1f4194](https://linux-hardware.org/?probe=17ed1f4194) | Dec 22, 2019 |
| HP            | Laptop 14-bp0xx             | Notebook    | [c99b71d804](https://linux-hardware.org/?probe=c99b71d804) | Dec 18, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| Lenovo        | 36DA SDK0J40679 WIN 3273... | All in one  | [de2a851c8f](https://linux-hardware.org/?probe=de2a851c8f) | Dec 12, 2019 |
| Lenovo        | 36DA SDK0J40679 WIN 3273... | All in one  | [427c0eea33](https://linux-hardware.org/?probe=427c0eea33) | Dec 12, 2019 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b1f6e07d2b](https://linux-hardware.org/?probe=b1f6e07d2b) | Dec 09, 2019 |
| HP            | Pavilion 10 TS              | Notebook    | [fbe754b72c](https://linux-hardware.org/?probe=fbe754b72c) | Nov 29, 2019 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d78bbdfa2a](https://linux-hardware.org/?probe=d78bbdfa2a) | Nov 18, 2019 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [7e957006e4](https://linux-hardware.org/?probe=7e957006e4) | Nov 18, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb6e592c0d](https://linux-hardware.org/?probe=cb6e592c0d) | Nov 18, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [9515caaefa](https://linux-hardware.org/?probe=9515caaefa) | Nov 17, 2019 |
| ASRock        | H55M                        | Desktop     | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [4e2ba6330f](https://linux-hardware.org/?probe=4e2ba6330f) | Nov 09, 2019 |
| Lenovo        | ThinkPad E460 20EUA00900    | Notebook    | [a549aed5b4](https://linux-hardware.org/?probe=a549aed5b4) | Nov 08, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [36570780b5](https://linux-hardware.org/?probe=36570780b5) | Oct 30, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [5d4e6e95f1](https://linux-hardware.org/?probe=5d4e6e95f1) | Oct 30, 2019 |
| Dell          | XPS 15 9550                 | Notebook    | [7323abf391](https://linux-hardware.org/?probe=7323abf391) | Oct 29, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [4270a9638b](https://linux-hardware.org/?probe=4270a9638b) | Oct 29, 2019 |
| Dell          | XPS 15 9550                 | Notebook    | [c70f66f439](https://linux-hardware.org/?probe=c70f66f439) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [666b6342e0](https://linux-hardware.org/?probe=666b6342e0) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [36c76546e9](https://linux-hardware.org/?probe=36c76546e9) | Oct 29, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [3469bcd886](https://linux-hardware.org/?probe=3469bcd886) | Oct 28, 2019 |
| HP            | Laptop 14-bp0xx             | Notebook    | [2e6a129f3e](https://linux-hardware.org/?probe=2e6a129f3e) | Oct 24, 2019 |
| VIT           | P2412                       | Notebook    | [2604d0b890](https://linux-hardware.org/?probe=2604d0b890) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6206eb1a2f](https://linux-hardware.org/?probe=6206eb1a2f) | Oct 11, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9a54660b4f](https://linux-hardware.org/?probe=9a54660b4f) | Oct 11, 2019 |
| MSI           | MS-7309                     | Desktop     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| Toshiba       | NB 105                      | Notebook    | [07f2ac3953](https://linux-hardware.org/?probe=07f2ac3953) | Oct 08, 2019 |
| Toshiba       | NB 105                      | Notebook    | [56d1fb0551](https://linux-hardware.org/?probe=56d1fb0551) | Oct 08, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [147a0012a9](https://linux-hardware.org/?probe=147a0012a9) | Oct 08, 2019 |
| HP            | Pavilion 10 TS              | Notebook    | [f1d915aa56](https://linux-hardware.org/?probe=f1d915aa56) | Oct 06, 2019 |
| Acer          | Aspire E3-111               | Notebook    | [cb12dc0dcd](https://linux-hardware.org/?probe=cb12dc0dcd) | Sep 18, 2019 |
| Chuwi         | LapBook Plus                | Notebook    | [2cc2dc7812](https://linux-hardware.org/?probe=2cc2dc7812) | Sep 15, 2019 |
| Samsung       | 535U3C                      | Notebook    | [3605b4bcc2](https://linux-hardware.org/?probe=3605b4bcc2) | Sep 15, 2019 |
| Fujitsu       | LIFEBOOK T734               | Notebook    | [38a59cafac](https://linux-hardware.org/?probe=38a59cafac) | Sep 07, 2019 |
| Acer          | Aspire E1-571               | Notebook    | [f7809cd921](https://linux-hardware.org/?probe=f7809cd921) | Sep 06, 2019 |
| HP            | 240 G4 Notebook PC          | Notebook    | [c29c743021](https://linux-hardware.org/?probe=c29c743021) | Sep 06, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [47661b90c1](https://linux-hardware.org/?probe=47661b90c1) | Aug 31, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e4ca853a88](https://linux-hardware.org/?probe=e4ca853a88) | Aug 30, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ebb5e97cc6](https://linux-hardware.org/?probe=ebb5e97cc6) | Aug 30, 2019 |
| Samsung       | 535U3C                      | Notebook    | [05752face4](https://linux-hardware.org/?probe=05752face4) | Aug 29, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| Lenovo        | G40-80 80E4                 | Notebook    | [386e041ee1](https://linux-hardware.org/?probe=386e041ee1) | Aug 27, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [934edb8a8d](https://linux-hardware.org/?probe=934edb8a8d) | Aug 19, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [d9d655f7eb](https://linux-hardware.org/?probe=d9d655f7eb) | Aug 19, 2019 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c3f8c454d5](https://linux-hardware.org/?probe=c3f8c454d5) | Aug 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [60d6ad276f](https://linux-hardware.org/?probe=60d6ad276f) | Aug 16, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9b10892d1f](https://linux-hardware.org/?probe=9b10892d1f) | Aug 12, 2019 |
| HP            | 81B9 1000                   | All in one  | [15c46542b5](https://linux-hardware.org/?probe=15c46542b5) | Aug 11, 2019 |
| HP            | 81B9 1000                   | All in one  | [c1e56da320](https://linux-hardware.org/?probe=c1e56da320) | Aug 11, 2019 |
| HP            | 240 G4 Notebook PC          | Notebook    | [8abebd7b2f](https://linux-hardware.org/?probe=8abebd7b2f) | Jul 31, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 115       | 13.86%  |
| Ubuntu 18.04       | 101       | 12.17%  |
| OpenMandriva 4.3   | 30        | 3.61%   |
| Ubuntu 22.04       | 21        | 2.53%   |
| KDE neon 20.04     | 18        | 2.17%   |
| OpenMandriva 4.2   | 17        | 2.05%   |
| Zorin 15           | 16        | 1.93%   |
| Ubuntu 19.04       | 15        | 1.81%   |
| Debian 11          | 15        | 1.81%   |
| Linux Mint 20.3    | 13        | 1.57%   |
| Linux Mint 19.3    | 13        | 1.57%   |
| Arch Rolling       | 13        | 1.57%   |
| Arch               | 13        | 1.57%   |
| Linux Mint 20.2    | 12        | 1.45%   |
| Ubuntu 19.10       | 10        | 1.2%    |
| Linux Mint 20.1    | 10        | 1.2%    |
| Fedora 35          | 10        | 1.2%    |
| Fedora 34          | 10        | 1.2%    |
| Zorin 16           | 9         | 1.08%   |
| ROSA R10           | 9         | 1.08%   |
| Manjaro            | 9         | 1.08%   |
| Kubuntu 20.04      | 9         | 1.08%   |
| Fedora 36          | 9         | 1.08%   |
| Ubuntu 20.10       | 8         | 0.96%   |
| Fedora 33          | 8         | 0.96%   |
| Debian 10          | 8         | 0.96%   |
| Xubuntu 20.04      | 7         | 0.84%   |
| Ubuntu 16.04       | 7         | 0.84%   |
| Pop!_OS 22.04      | 7         | 0.84%   |
| Pop!_OS 20.04      | 7         | 0.84%   |
| Linux Mint 20      | 7         | 0.84%   |
| Fedora 32          | 7         | 0.84%   |
| ArcoLinux Rolling  | 7         | 0.84%   |
| Ubuntu 21.04       | 6         | 0.72%   |
| Ubuntu Unity 16.04 | 5         | 0.6%    |
| Ubuntu 21.10       | 5         | 0.6%    |
| Ubuntu 18.10       | 5         | 0.6%    |
| ROSA R11           | 5         | 0.6%    |
| ROSA 12.2          | 5         | 0.6%    |
| Fedora 31          | 5         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 283       | 35.91%  |
| Endless       | 66        | 8.38%   |
| Linux Mint    | 65        | 8.25%   |
| OpenMandriva  | 49        | 6.22%   |
| Fedora        | 43        | 5.46%   |
| Zorin         | 28        | 3.55%   |
| Debian        | 26        | 3.3%    |
| Arch          | 26        | 3.3%    |
| Manjaro       | 25        | 3.17%   |
| Pop!_OS       | 24        | 3.05%   |
| ROSA          | 23        | 2.92%   |
| KDE neon      | 21        | 2.66%   |
| Kubuntu       | 14        | 1.78%   |
| Xubuntu       | 13        | 1.65%   |
| ArcoLinux     | 9         | 1.14%   |
| Ubuntu Unity  | 8         | 1.02%   |
| Kali          | 8         | 1.02%   |
| Elementary    | 8         | 1.02%   |
| Lubuntu       | 6         | 0.76%   |
| openSUSE      | 5         | 0.63%   |
| Ubuntu Budgie | 4         | 0.51%   |
| MX            | 3         | 0.38%   |
| Deepin        | 3         | 0.38%   |
| Clear Linux   | 3         | 0.38%   |
| Nobara        | 2         | 0.25%   |
| Garuda Linux  | 2         | 0.25%   |
| EndeavourOS   | 2         | 0.25%   |
| CentOS        | 2         | 0.25%   |
| BlackPanther  | 2         | 0.25%   |
| Xero          | 1         | 0.13%   |
| UbuntuDDE     | 1         | 0.13%   |
| Ubuntu MATE   | 1         | 0.13%   |
| Rocky Linux   | 1         | 0.13%   |
| RHEL          | 1         | 0.13%   |
| Reborn OS     | 1         | 0.13%   |
| Parrot        | 1         | 0.13%   |
| NixOS         | 1         | 0.13%   |
| Mageia        | 1         | 0.13%   |
| LMDE          | 1         | 0.13%   |
| LinuxFX       | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 30        | 3.4%    |
| 5.4.0-42-generic                   | 28        | 3.17%   |
| 5.10.14-desktop-1omv4002           | 17        | 1.93%   |
| 5.8.0-14-generic                   | 16        | 1.81%   |
| 5.4.0-58-generic                   | 14        | 1.59%   |
| 5.4.0-19-generic                   | 12        | 1.36%   |
| 5.3.0-46-generic                   | 9         | 1.02%   |
| 4.18.0-15-generic                  | 9         | 1.02%   |
| 5.4.0-48-generic                   | 8         | 0.91%   |
| 5.15.0-48-generic                  | 8         | 0.91%   |
| 4.18.0-25-generic                  | 8         | 0.91%   |
| 5.8.0-43-generic                   | 7         | 0.79%   |
| 5.4.0-37-generic                   | 7         | 0.79%   |
| 5.4.0-31-generic                   | 7         | 0.79%   |
| 5.3.0-28-generic                   | 7         | 0.79%   |
| 5.15.0-46-generic                  | 7         | 0.79%   |
| 5.0.0-37-generic                   | 7         | 0.79%   |
| 5.13.0-40-generic                  | 6         | 0.68%   |
| 5.13.0-30-generic                  | 6         | 0.68%   |
| 5.11.0-34-generic                  | 6         | 0.68%   |
| 5.11.0-27-generic                  | 6         | 0.68%   |
| 5.0.0-32-generic                   | 6         | 0.68%   |
| 5.0.0-25-generic                   | 6         | 0.68%   |
| 5.0.0-15-generic                   | 6         | 0.68%   |
| 5.4.0-72-generic                   | 5         | 0.57%   |
| 5.4.0-70-generic                   | 5         | 0.57%   |
| 5.4.0-65-generic                   | 5         | 0.57%   |
| 5.4.0-54-generic                   | 5         | 0.57%   |
| 5.4.0-47-generic                   | 5         | 0.57%   |
| 5.4.0-107-generic                  | 5         | 0.57%   |
| 5.3.0-40-generic                   | 5         | 0.57%   |
| 5.15.0-50-generic                  | 5         | 0.57%   |
| 5.15.0-47-generic                  | 5         | 0.57%   |
| 5.11.0-40-generic                  | 5         | 0.57%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 0.57%   |
| 5.0.0-23-generic                   | 5         | 0.57%   |
| 5.0.0-13-generic                   | 5         | 0.57%   |
| 4.15.0-47-generic                  | 5         | 0.57%   |
| 5.8.0-59-generic                   | 4         | 0.45%   |
| 5.8.0-48-generic                   | 4         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 182       | 21.46%  |
| 4.15.0  | 61        | 7.19%   |
| 5.8.0   | 53        | 6.25%   |
| 5.3.0   | 51        | 6.01%   |
| 5.0.0   | 48        | 5.66%   |
| 4.18.0  | 40        | 4.72%   |
| 5.15.0  | 39        | 4.6%    |
| 5.13.0  | 39        | 4.6%    |
| 5.11.0  | 38        | 4.48%   |
| 5.16.7  | 30        | 3.54%   |
| 5.10.14 | 17        | 2%      |
| 5.10.0  | 15        | 1.77%   |
| 4.19.0  | 7         | 0.83%   |
| 5.10.74 | 5         | 0.59%   |
| 4.9.60  | 5         | 0.59%   |
| 4.4.0   | 5         | 0.59%   |
| 5.8.5   | 4         | 0.47%   |
| 5.8.18  | 4         | 0.47%   |
| 4.13.0  | 4         | 0.47%   |
| 5.9.16  | 3         | 0.35%   |
| 5.6.0   | 3         | 0.35%   |
| 5.18.10 | 3         | 0.35%   |
| 5.17.5  | 3         | 0.35%   |
| 5.17.15 | 3         | 0.35%   |
| 5.15.12 | 3         | 0.35%   |
| 5.14.0  | 3         | 0.35%   |
| 5.13.19 | 3         | 0.35%   |
| 5.12.4  | 3         | 0.35%   |
| 5.1.0   | 3         | 0.35%   |
| 4.9.20  | 3         | 0.35%   |
| 4.9.0   | 3         | 0.35%   |
| 5.9.1   | 2         | 0.24%   |
| 5.7.19  | 2         | 0.24%   |
| 5.6.19  | 2         | 0.24%   |
| 5.6.15  | 2         | 0.24%   |
| 5.4.32  | 2         | 0.24%   |
| 5.3.12  | 2         | 0.24%   |
| 5.19.9  | 2         | 0.24%   |
| 5.19.4  | 2         | 0.24%   |
| 5.19.0  | 2         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 190       | 22.65%  |
| 5.8     | 64        | 7.63%   |
| 4.15    | 61        | 7.27%   |
| 5.3     | 56        | 6.67%   |
| 5.10    | 55        | 6.56%   |
| 5.15    | 52        | 6.2%    |
| 5.13    | 50        | 5.96%   |
| 5.0     | 49        | 5.84%   |
| 5.11    | 44        | 5.24%   |
| 4.18    | 43        | 5.13%   |
| 5.16    | 36        | 4.29%   |
| 4.9     | 17        | 2.03%   |
| 5.6     | 15        | 1.79%   |
| 5.17    | 13        | 1.55%   |
| 5.14    | 12        | 1.43%   |
| 5.18    | 11        | 1.31%   |
| 5.9     | 10        | 1.19%   |
| 5.12    | 9         | 1.07%   |
| 5.7     | 8         | 0.95%   |
| 4.19    | 8         | 0.95%   |
| 5.19    | 7         | 0.83%   |
| 4.4     | 5         | 0.6%    |
| 5.5     | 4         | 0.48%   |
| 4.13    | 4         | 0.48%   |
| 5.1     | 3         | 0.36%   |
| 4.12    | 3         | 0.36%   |
| 6.0     | 2         | 0.24%   |
| 5.2     | 2         | 0.24%   |
| 4.10    | 2         | 0.24%   |
| 4.1     | 2         | 0.24%   |
| 4.20    | 1         | 0.12%   |
| 4.14    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 747       | 97.14%  |
| i686    | 19        | 2.47%   |
| aarch64 | 3         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 361       | 45.58%  |
| Unknown    | 131       | 16.54%  |
| KDE5       | 107       | 13.51%  |
| XFCE       | 55        | 6.94%   |
| X-Cinnamon | 39        | 4.92%   |
| KDE        | 26        | 3.28%   |
| KDE4       | 12        | 1.52%   |
| MATE       | 11        | 1.39%   |
| Unity      | 8         | 1.01%   |
| Pantheon   | 8         | 1.01%   |
| Cinnamon   | 8         | 1.01%   |
| Budgie     | 6         | 0.76%   |
| Deepin     | 5         | 0.63%   |
| LXQt       | 4         | 0.51%   |
| LXDE       | 4         | 0.51%   |
| i3         | 2         | 0.25%   |
| bspwm      | 2         | 0.25%   |
| awesome    | 2         | 0.25%   |
| ICEWM      | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 616       | 78.47%  |
| Unknown | 86        | 10.96%  |
| Wayland | 75        | 9.55%   |
| Tty     | 8         | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 476       | 60.18%  |
| SDDM    | 91        | 11.5%   |
| GDM     | 82        | 10.37%  |
| LightDM | 60        | 7.59%   |
| GDM3    | 47        | 5.94%   |
| TDM     | 21        | 2.65%   |
| KDM     | 12        | 1.52%   |
| SLiM    | 1         | 0.13%   |
| LXDM    | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_CO   | 368       | 46.46%  |
| en_US   | 195       | 24.62%  |
| Unknown | 145       | 18.31%  |
| es_ES   | 49        | 6.19%   |
| es_MX   | 12        | 1.52%   |
| en_GB   | 4         | 0.51%   |
| es_PE   | 3         | 0.38%   |
| C       | 3         | 0.38%   |
| pt_BR   | 2         | 0.25%   |
| es_EC   | 2         | 0.25%   |
| pt_PT   | 1         | 0.13%   |
| pl_PL   | 1         | 0.13%   |
| it_IT   | 1         | 0.13%   |
| fr_FR   | 1         | 0.13%   |
| es_VE   | 1         | 0.13%   |
| es_CL   | 1         | 0.13%   |
| es_AR   | 1         | 0.13%   |
| en      | 1         | 0.13%   |
| de_DE   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 393       | 50.32%  |
| BIOS | 388       | 49.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 629       | 80.03%  |
| Overlay | 52        | 6.62%   |
| Unknown | 47        | 5.98%   |
| Btrfs   | 39        | 4.96%   |
| Xfs     | 11        | 1.4%    |
| Zfs     | 2         | 0.25%   |
| Tmpfs   | 2         | 0.25%   |
| Ext2    | 2         | 0.25%   |
| F2fs    | 1         | 0.13%   |
| Ext3    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 511       | 65.77%  |
| GPT     | 189       | 24.32%  |
| MBR     | 77        | 9.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 685       | 86.93%  |
| Yes       | 103       | 13.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 501       | 64.23%  |
| Yes       | 279       | 35.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 179       | 23.28%  |
| Hewlett-Packard              | 154       | 20.03%  |
| Lenovo                       | 103       | 13.39%  |
| Dell                         | 62        | 8.06%   |
| Acer                         | 46        | 5.98%   |
| MSI                          | 33        | 4.29%   |
| Gigabyte Technology          | 33        | 4.29%   |
| ASRock                       | 26        | 3.38%   |
| Toshiba                      | 21        | 2.73%   |
| Apple                        | 14        | 1.82%   |
| Samsung Electronics          | 12        | 1.56%   |
| Intel                        | 12        | 1.56%   |
| Sony                         | 10        | 1.3%    |
| Unknown                      | 8         | 1.04%   |
| HUAWEI                       | 6         | 0.78%   |
| ECS                          | 6         | 0.78%   |
| Pegatron                     | 5         | 0.65%   |
| Biostar                      | 5         | 0.65%   |
| Foxconn                      | 4         | 0.52%   |
| PCSMART                      | 3         | 0.39%   |
| Supermicro                   | 2         | 0.26%   |
| Raspberry Pi Foundation      | 2         | 0.26%   |
| Notebook                     | 2         | 0.26%   |
| Gateway                      | 2         | 0.26%   |
| VIT                          | 1         | 0.13%   |
| TYAN Computer                | 1         | 0.13%   |
| Timi                         | 1         | 0.13%   |
| PCChips                      | 1         | 0.13%   |
| ONDA                         | 1         | 0.13%   |
| Nvidia                       | 1         | 0.13%   |
| MPS Mayorista de Colombia SA | 1         | 0.13%   |
| Lanix                        | 1         | 0.13%   |
| Inspur                       | 1         | 0.13%   |
| Hardkernel                   | 1         | 0.13%   |
| GreatWall                    | 1         | 0.13%   |
| Google                       | 1         | 0.13%   |
| Fujitsu Siemens              | 1         | 0.13%   |
| Fujitsu                      | 1         | 0.13%   |
| Framework                    | 1         | 0.13%   |
| Compumax Computer            | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-db0xxx                        | 11        | 1.43%   |
| Unknown                                    | 10        | 1.3%    |
| Samsung 300E4C/300E5C/300E7C               | 5         | 0.65%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 5         | 0.65%   |
| HP Notebook                                | 5         | 0.65%   |
| HP Laptop 14-bs0xx                         | 5         | 0.65%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 5         | 0.65%   |
| MSI MS-7309                                | 4         | 0.52%   |
| HP Laptop 14-cm1xxx                        | 4         | 0.52%   |
| HP 245 G6                                  | 4         | 0.52%   |
| HP 14                                      | 4         | 0.52%   |
| Dell XPS 15 9550                           | 4         | 0.52%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.52%   |
| ASUS X455LJ                                | 4         | 0.52%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB     | 4         | 0.52%   |
| ASUS All Series                            | 4         | 0.52%   |
| MSI MS-7817                                | 3         | 0.39%   |
| Lenovo IdeaPad S340-14API 81NB             | 3         | 0.39%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 3         | 0.39%   |
| Lenovo G40-80 80E4                         | 3         | 0.39%   |
| Lenovo G40-45 80E1                         | 3         | 0.39%   |
| HP ProBook 450 G1                          | 3         | 0.39%   |
| HP Pavilion x360 Convertible 14-cd0xxx     | 3         | 0.39%   |
| HP Laptop 15-da0xxx                        | 3         | 0.39%   |
| HP ENVY 15                                 | 3         | 0.39%   |
| Gigabyte H81M-H                            | 3         | 0.39%   |
| Gigabyte GA-78LMT-USB3                     | 3         | 0.39%   |
| Gigabyte G31M-ES2C                         | 3         | 0.39%   |
| Gigabyte B450M DS3H                        | 3         | 0.39%   |
| ECS G31T-M7                                | 3         | 0.39%   |
| Dell Vostro 3400                           | 3         | 0.39%   |
| ASUS X555QG                                | 3         | 0.39%   |
| ASUS X505BP                                | 3         | 0.39%   |
| ASUS X455LD                                | 3         | 0.39%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA     | 3         | 0.39%   |
| ASUS VivoBook_ASUSLaptop X409DA_M409DA     | 3         | 0.39%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 3         | 0.39%   |
| ASUS T101HA                                | 3         | 0.39%   |
| ASUS M5A78L-M/USB3                         | 3         | 0.39%   |
| ASRock Wolfdale1333-D667                   | 3         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 52        | 6.76%   |
| Lenovo IdeaPad         | 35        | 4.55%   |
| HP Laptop              | 33        | 4.29%   |
| Acer Aspire            | 33        | 4.29%   |
| Lenovo ThinkPad        | 30        | 3.9%    |
| HP Pavilion            | 30        | 3.9%    |
| Dell Inspiron          | 20        | 2.6%    |
| Toshiba Satellite      | 18        | 2.34%   |
| HP ProBook             | 16        | 2.08%   |
| HP Compaq              | 14        | 1.82%   |
| ASUS PRIME             | 14        | 1.82%   |
| Dell Latitude          | 11        | 1.43%   |
| Unknown                | 10        | 1.3%    |
| Dell Vostro            | 9         | 1.17%   |
| ASUS TUF               | 9         | 1.17%   |
| ASUS ROG               | 9         | 1.17%   |
| HP 245                 | 8         | 1.04%   |
| Dell OptiPlex          | 7         | 0.91%   |
| Dell XPS               | 6         | 0.78%   |
| ASUS ZenBook           | 6         | 0.78%   |
| Samsung 300E4C         | 5         | 0.65%   |
| HP Notebook            | 5         | 0.65%   |
| HP ENVY                | 5         | 0.65%   |
| HP EliteBook           | 5         | 0.65%   |
| MSI MS-7309            | 4         | 0.52%   |
| Lenovo Yoga            | 4         | 0.52%   |
| HP ProLiant            | 4         | 0.52%   |
| HP 240                 | 4         | 0.52%   |
| HP 14                  | 4         | 0.52%   |
| ASUS X455LJ            | 4         | 0.52%   |
| ASUS All               | 4         | 0.52%   |
| MSI MS-7817            | 3         | 0.39%   |
| Lenovo G40-80          | 3         | 0.39%   |
| Lenovo G40-45          | 3         | 0.39%   |
| HP Presario            | 3         | 0.39%   |
| HP All-in-One          | 3         | 0.39%   |
| Gigabyte X399          | 3         | 0.39%   |
| Gigabyte H81M-H        | 3         | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 3         | 0.39%   |
| Gigabyte G31M-ES2C     | 3         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 86        | 11.18%  |
| 2019    | 82        | 10.66%  |
| 2017    | 76        | 9.88%   |
| 2012    | 58        | 7.54%   |
| 2010    | 58        | 7.54%   |
| 2011    | 55        | 7.15%   |
| 2020    | 53        | 6.89%   |
| 2013    | 50        | 6.5%    |
| 2015    | 49        | 6.37%   |
| 2014    | 44        | 5.72%   |
| 2009    | 33        | 4.29%   |
| 2021    | 32        | 4.16%   |
| 2016    | 30        | 3.9%    |
| 2008    | 24        | 3.12%   |
| 2007    | 17        | 2.21%   |
| 2006    | 12        | 1.56%   |
| 2022    | 4         | 0.52%   |
| Unknown | 3         | 0.39%   |
| 2005    | 2         | 0.26%   |
| 2003    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 523       | 68.01%  |
| Desktop        | 200       | 26.01%  |
| All in one     | 20        | 2.6%    |
| Convertible    | 13        | 1.69%   |
| Tablet         | 6         | 0.78%   |
| System on chip | 3         | 0.39%   |
| Server         | 3         | 0.39%   |
| Mini pc        | 1         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 697       | 90.17%  |
| Enabled  | 76        | 9.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 768       | 99.87%  |
| Yes  | 1         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 235       | 30.24%  |
| 3.01-4.0    | 205       | 26.38%  |
| 8.01-16.0   | 141       | 18.15%  |
| 16.01-24.0  | 86        | 11.07%  |
| 1.01-2.0    | 45        | 5.79%   |
| 32.01-64.0  | 25        | 3.22%   |
| 2.01-3.0    | 20        | 2.57%   |
| 24.01-32.0  | 9         | 1.16%   |
| 0.51-1.0    | 7         | 0.9%    |
| 64.01-256.0 | 4         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 310       | 36.9%   |
| 2.01-3.0  | 239       | 28.45%  |
| 3.01-4.0  | 119       | 14.17%  |
| 4.01-8.0  | 88        | 10.48%  |
| 0.51-1.0  | 54        | 6.43%   |
| 8.01-16.0 | 26        | 3.1%    |
| 0.01-0.5  | 4         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 567       | 72.6%   |
| 2      | 164       | 21%     |
| 3      | 31        | 3.97%   |
| 4      | 12        | 1.54%   |
| 5      | 3         | 0.38%   |
| 6      | 2         | 0.26%   |
| 8      | 1         | 0.13%   |
| 0      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 489       | 63.26%  |
| Yes       | 284       | 36.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 661       | 85.73%  |
| No        | 110       | 14.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 631       | 81.74%  |
| No        | 141       | 18.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 487       | 63.16%  |
| No        | 284       | 36.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Colombia | 769       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Bogotá          | 312       | 39.05%  |
| Medellín        | 111       | 13.89%  |
| Santiago de Cali | 72        | 9.01%   |
| Bucaramanga      | 37        | 4.63%   |
| Barranquilla     | 35        | 4.38%   |
| Pereira          | 20        | 2.5%    |
| Cartagena        | 18        | 2.25%   |
| Manizales        | 15        | 1.88%   |
| Envigado         | 11        | 1.38%   |
| Villavicencio    | 9         | 1.13%   |
| Cúcuta          | 9         | 1.13%   |
| Popayán         | 8         | 1%      |
| Ibague           | 8         | 1%      |
| Santa Marta      | 6         | 0.75%   |
| Montería        | 6         | 0.75%   |
| Fusagasuga       | 6         | 0.75%   |
| Armenia          | 6         | 0.75%   |
| Chia             | 5         | 0.63%   |
| Bello            | 5         | 0.63%   |
| Tunja            | 4         | 0.5%    |
| Valledupar       | 3         | 0.38%   |
| Sincelejo        | 3         | 0.38%   |
| Rionegro         | 3         | 0.38%   |
| Pasto            | 3         | 0.38%   |
| Palmira          | 3         | 0.38%   |
| Neiva            | 3         | 0.38%   |
| Los Patios       | 3         | 0.38%   |
| Ipiales          | 3         | 0.38%   |
| Yopal            | 2         | 0.25%   |
| Tuluá           | 2         | 0.25%   |
| Soledad          | 2         | 0.25%   |
| Soacha           | 2         | 0.25%   |
| Sabaneta         | 2         | 0.25%   |
| La Estrella      | 2         | 0.25%   |
| Itaguei          | 2         | 0.25%   |
| Floridablanca    | 2         | 0.25%   |
| Facatativá      | 2         | 0.25%   |
| Cota             | 2         | 0.25%   |
| Chiquinquira     | 2         | 0.25%   |
| Calarcá         | 2         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 183       | 232    | 18.14%  |
| WDC                   | 152       | 191    | 15.06%  |
| Toshiba               | 140       | 166    | 13.88%  |
| Samsung Electronics   | 68        | 80     | 6.74%   |
| Kingston              | 66        | 86     | 6.54%   |
| Hitachi               | 63        | 76     | 6.24%   |
| SanDisk               | 49        | 59     | 4.86%   |
| Crucial               | 36        | 41     | 3.57%   |
| Unknown               | 34        | 37     | 3.37%   |
| A-DATA Technology     | 34        | 41     | 3.37%   |
| HGST                  | 33        | 42     | 3.27%   |
| Intel                 | 16        | 18     | 1.59%   |
| Maxtor                | 14        | 15     | 1.39%   |
| SK hynix              | 13        | 19     | 1.29%   |
| Micron Technology     | 9         | 9      | 0.89%   |
| China                 | 8         | 8      | 0.79%   |
| Apple                 | 8         | 8      | 0.79%   |
| Realtek Semiconductor | 7         | 8      | 0.69%   |
| Phison                | 7         | 9      | 0.69%   |
| Fujitsu               | 6         | 6      | 0.59%   |
| XPG                   | 5         | 6      | 0.5%    |
| Silicon Motion        | 5         | 5      | 0.5%    |
| JMicron Technology    | 5         | 5      | 0.5%    |
| Gigabyte Technology   | 5         | 6      | 0.5%    |
| PNY                   | 3         | 3      | 0.3%    |
| LITEONIT              | 3         | 3      | 0.3%    |
| KingDian              | 3         | 3      | 0.3%    |
| Hewlett-Packard       | 3         | 3      | 0.3%    |
| Transcend             | 2         | 3      | 0.2%    |
| Team                  | 2         | 2      | 0.2%    |
| Netac                 | 2         | 2      | 0.2%    |
| LITEON                | 2         | 3      | 0.2%    |
| Lexar                 | 2         | 2      | 0.2%    |
| KingSpec              | 2         | 2      | 0.2%    |
| Corsair               | 2         | 2      | 0.2%    |
| Zheino                | 1         | 1      | 0.1%    |
| XrayDisk              | 1         | 1      | 0.1%    |
| Union Memory          | 1         | 1      | 0.1%    |
| SUPERSONIC            | 1         | 1      | 0.1%    |
| SSSTC                 | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 37        | 3.55%   |
| Toshiba MQ04ABF100 1TB                 | 30        | 2.88%   |
| Toshiba MQ01ABF050 500GB               | 21        | 2.02%   |
| Toshiba DT01ACA100 1TB                 | 18        | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 18        | 1.73%   |
| Toshiba MQ01ABD100 1TB                 | 17        | 1.63%   |
| Kingston SA400S37240G 240GB SSD        | 14        | 1.34%   |
| Seagate ST500LT012-1DG142 500GB        | 13        | 1.25%   |
| Crucial CT240BX500SSD1 240GB           | 13        | 1.25%   |
| Kingston SA400S37120G 120GB SSD        | 12        | 1.15%   |
| Kingston SA400S37480G 480GB SSD        | 9         | 0.86%   |
| SanDisk NVMe SSD Drive 256GB           | 8         | 0.77%   |
| HGST HTS541010B7E610 1TB               | 8         | 0.77%   |
| HGST HTS541010A9E680 1TB               | 8         | 0.77%   |
| Unknown MMC Card  64GB                 | 7         | 0.67%   |
| SanDisk NVMe SSD Drive 512GB           | 7         | 0.67%   |
| Hitachi HDS721050CLA362 500GB          | 7         | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB               | 6         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                 | 6         | 0.58%   |
| Unknown MMC Card  32GB                 | 6         | 0.58%   |
| Toshiba HDWD110 1TB                    | 6         | 0.58%   |
| Toshiba DT01ACA200 2TB                 | 6         | 0.58%   |
| Toshiba DT01ACA050 500GB               | 6         | 0.58%   |
| Seagate ST500LT012-9WS142 500GB        | 6         | 0.58%   |
| Kingston SV300S37A120G 120GB SSD       | 6         | 0.58%   |
| HGST HTS545050A7E680 500GB             | 6         | 0.58%   |
| Crucial CT1000BX500SSD1 1TB            | 6         | 0.58%   |
| Unknown SD/MMC/MS PRO 1TB              | 5         | 0.48%   |
| Seagate ST500LM030-1RK17D 500GB        | 5         | 0.48%   |
| Seagate ST500DM002-1BD142 500GB        | 5         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB             | 5         | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 5         | 0.48%   |
| Intel NVMe SSD Drive 512GB             | 5         | 0.48%   |
| Hitachi HDS721616PLA380 160GB          | 5         | 0.48%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.48%   |
| Crucial CT480BX500SSD1 480GB           | 5         | 0.48%   |
| A-DATA SU650 120GB SSD                 | 5         | 0.48%   |
| A-DATA SU630 480GB SSD                 | 5         | 0.48%   |
| A-DATA SU630 240GB SSD                 | 5         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB               | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 183       | 231    | 30.7%   |
| Toshiba             | 136       | 160    | 22.82%  |
| WDC                 | 133       | 168    | 22.32%  |
| Hitachi             | 63        | 76     | 10.57%  |
| HGST                | 33        | 42     | 5.54%   |
| Samsung Electronics | 17        | 19     | 2.85%   |
| Maxtor              | 14        | 15     | 2.35%   |
| Fujitsu             | 6         | 6      | 1.01%   |
| Unknown             | 5         | 6      | 0.84%   |
| Apple               | 3         | 3      | 0.5%    |
| SATAFIRM            | 1         | 1      | 0.17%   |
| Phison              | 1         | 2      | 0.17%   |
| ExcelStor           | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 55        | 73     | 23.71%  |
| Crucial             | 33        | 38     | 14.22%  |
| A-DATA Technology   | 31        | 38     | 13.36%  |
| Samsung Electronics | 23        | 24     | 9.91%   |
| SanDisk             | 20        | 23     | 8.62%   |
| WDC                 | 12        | 13     | 5.17%   |
| China               | 8         | 8      | 3.45%   |
| Toshiba             | 5         | 6      | 2.16%   |
| Intel               | 4         | 5      | 1.72%   |
| Gigabyte Technology | 4         | 5      | 1.72%   |
| Apple               | 4         | 4      | 1.72%   |
| SK hynix            | 3         | 7      | 1.29%   |
| Micron Technology   | 3         | 3      | 1.29%   |
| LITEONIT            | 3         | 3      | 1.29%   |
| KingDian            | 3         | 3      | 1.29%   |
| Transcend           | 2         | 3      | 0.86%   |
| Team                | 2         | 2      | 0.86%   |
| PNY                 | 2         | 2      | 0.86%   |
| LITEON              | 2         | 3      | 0.86%   |
| Lexar               | 2         | 2      | 0.86%   |
| KingSpec            | 2         | 2      | 0.86%   |
| Zheino              | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |
| Seagate             | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| HS-SSD-C100         | 1         | 1      | 0.43%   |
| Hewlett-Packard     | 1         | 1      | 0.43%   |
| Corsair             | 1         | 1      | 0.43%   |
| Argon               | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 523       | 730    | 56.72%  |
| SSD     | 221       | 276    | 23.97%  |
| NVMe    | 143       | 175    | 15.51%  |
| MMC     | 26        | 29     | 2.82%   |
| Unknown | 9         | 10     | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 654       | 994    | 77.49%  |
| NVMe | 141       | 172    | 16.71%  |
| MMC  | 26        | 29     | 3.08%   |
| SAS  | 23        | 25     | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 426       | 584    | 56.65%  |
| 0.51-1.0   | 281       | 357    | 37.37%  |
| 1.01-2.0   | 31        | 43     | 4.12%   |
| 4.01-10.0  | 5         | 6      | 0.66%   |
| 3.01-4.0   | 4         | 10     | 0.53%   |
| 2.01-3.0   | 4         | 4      | 0.53%   |
| 0          | 1         | 2      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 206       | 25.46%  |
| 251-500        | 199       | 24.6%   |
| 501-1000       | 160       | 19.78%  |
| 51-100         | 66        | 8.16%   |
| 1-20           | 61        | 7.54%   |
| 1001-2000      | 46        | 5.69%   |
| 21-50          | 35        | 4.33%   |
| More than 3000 | 13        | 1.61%   |
| Unknown        | 13        | 1.61%   |
| 2001-3000      | 10        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 349       | 41.65%  |
| 21-50          | 161       | 19.21%  |
| 101-250        | 113       | 13.48%  |
| 51-100         | 97        | 11.58%  |
| 251-500        | 53        | 6.32%   |
| 501-1000       | 38        | 4.53%   |
| Unknown        | 13        | 1.55%   |
| 1001-2000      | 7         | 0.84%   |
| More than 3000 | 4         | 0.48%   |
| 2001-3000      | 3         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 4      | 4.21%   |
| Seagate ST9500420AS 500GB            | 2         | 2      | 2.11%   |
| Seagate ST9320423AS 320GB            | 2         | 2      | 2.11%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 2         | 2      | 2.11%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2      | 2.11%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 2.11%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 2      | 2.11%   |
| Hitachi HDS721050CLA362 500GB        | 2         | 2      | 2.11%   |
| A-DATA Technology SU630 480GB SSD    | 2         | 2      | 2.11%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 1      | 1.05%   |
| WDC WD800BD-22MRA1 80GB              | 1         | 1      | 1.05%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 1      | 1.05%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-08V0A0 500GB          | 1         | 1      | 1.05%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 1      | 1.05%   |
| WDC WD3200BEKT-60F3T1 320GB          | 1         | 1      | 1.05%   |
| WDC WD3200AVJS-63B6A0 320GB          | 1         | 1      | 1.05%   |
| WDC WD3200AAJS-60Z0A0 320GB          | 1         | 1      | 1.05%   |
| WDC WD3200AAJS-56M0A0 320GB          | 1         | 1      | 1.05%   |
| WDC WD20EZRX-00DC0B0 2TB             | 1         | 1      | 1.05%   |
| WDC WD2003FYPS-27W9B0 2TB            | 1         | 1      | 1.05%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 1      | 1.05%   |
| WDC WD1600BEKT-60V5T1 160GB          | 1         | 1      | 1.05%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1      | 1.05%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 1      | 1.05%   |
| WDC WD10EURX-73FH1Y0 1TB             | 1         | 1      | 1.05%   |
| WDC WD10EACS-00D6B1 1TB              | 1         | 1      | 1.05%   |
| WDC WD1001FAES-75W7A0 1TB            | 1         | 1      | 1.05%   |
| Toshiba MQ04ABF100 1TB               | 1         | 2      | 1.05%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.05%   |
| Toshiba MK7559GSXP 752GB             | 1         | 1      | 1.05%   |
| Toshiba MK5076GSX 500GB              | 1         | 1      | 1.05%   |
| Toshiba MK5065GSXN 500GB             | 1         | 1      | 1.05%   |
| Toshiba MK3263GSX 320GB              | 1         | 1      | 1.05%   |
| Toshiba HDWD110 1TB                  | 1         | 1      | 1.05%   |
| Toshiba DT01ABA200V 2TB              | 1         | 1      | 1.05%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.05%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.05%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 1.05%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 36     | 32.95%  |
| WDC                 | 16        | 19     | 18.18%  |
| Hitachi             | 15        | 21     | 17.05%  |
| Toshiba             | 8         | 9      | 9.09%   |
| Samsung Electronics | 5         | 5      | 5.68%   |
| Maxtor              | 4         | 4      | 4.55%   |
| HGST                | 2         | 2      | 2.27%   |
| Crucial             | 2         | 2      | 2.27%   |
| A-DATA Technology   | 2         | 2      | 2.27%   |
| Micron Technology   | 1         | 1      | 1.14%   |
| Kingston            | 1         | 1      | 1.14%   |
| Intel               | 1         | 2      | 1.14%   |
| Fujitsu             | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 36     | 36.71%  |
| WDC                 | 16        | 19     | 20.25%  |
| Hitachi             | 15        | 21     | 18.99%  |
| Toshiba             | 8         | 9      | 10.13%  |
| Maxtor              | 4         | 4      | 5.06%   |
| Samsung Electronics | 3         | 3      | 3.8%    |
| HGST                | 2         | 2      | 2.53%   |
| Fujitsu             | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 96     | 89.16%  |
| SSD  | 8         | 9      | 9.64%   |
| NVMe | 1         | 1      | 1.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Maxtor STM380211AS 80GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Maxtor | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 535       | 833    | 65.48%  |
| Works    | 198       | 280    | 24.24%  |
| Malfunc  | 83        | 106    | 10.16%  |
| Failed   | 1         | 1      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 493       | 56.41%  |
| AMD                                  | 205       | 23.46%  |
| SanDisk                              | 36        | 4.12%   |
| Samsung Electronics                  | 29        | 3.32%   |
| Nvidia                               | 20        | 2.29%   |
| Realtek Semiconductor                | 11        | 1.26%   |
| SK hynix                             | 10        | 1.14%   |
| Kingston Technology Company          | 10        | 1.14%   |
| Phison Electronics                   | 9         | 1.03%   |
| Micron Technology                    | 8         | 0.92%   |
| ASMedia Technology                   | 8         | 0.92%   |
| Silicon Motion                       | 7         | 0.8%    |
| VIA Technologies                     | 6         | 0.69%   |
| ADATA Technology                     | 4         | 0.46%   |
| Marvell Technology Group             | 3         | 0.34%   |
| JMicron Technology                   | 3         | 0.34%   |
| Union Memory (Shenzhen)              | 2         | 0.23%   |
| Micron/Crucial Technology            | 2         | 0.23%   |
| Unknown                              | 1         | 0.11%   |
| Solid State Storage Technology       | 1         | 0.11%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.11%   |
| LSI Logic / Symbios Logic            | 1         | 0.11%   |
| KIOXIA                               | 1         | 0.11%   |
| Hewlett-Packard                      | 1         | 0.11%   |
| Biwin Storage Technology             | 1         | 0.11%   |
| Apple                                | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 156       | 15.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 59        | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 39        | 3.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 38        | 3.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 29        | 2.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 27        | 2.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 22        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18        | 1.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 17        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17        | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 11        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 10        | 1%      |
| Realtek Realtek Non-Volatile memory controller                                          | 10        | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 10        | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1%      |
| AMD 500 Series Chipset SATA Controller                                                  | 10        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 0.9%    |
| Nvidia MCP61 SATA Controller                                                            | 8         | 0.8%    |
| Micron Non-Volatile memory controller                                                   | 8         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 0.8%    |
| Samsung NVMe SSD Controller 980                                                         | 7         | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 7         | 0.7%    |
| Intel SATA Controller [RAID mode]                                                       | 7         | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 590       | 65.41%  |
| NVMe | 140       | 15.52%  |
| IDE  | 112       | 12.42%  |
| RAID | 59        | 6.54%   |
| SAS  | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 527       | 68.53%  |
| AMD    | 239       | 31.08%  |
| ARM    | 3         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 25        | 3.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 13        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 12        | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 11        | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 1.17%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 9         | 1.17%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 9         | 1.17%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 8         | 1.04%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 8         | 1.04%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 8         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 7         | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 7         | 0.91%   |
| AMD Ryzen 5 3600 6-Core Processor               | 7         | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 6         | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 6         | 0.78%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 6         | 0.78%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 0.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 6         | 0.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 6         | 0.78%   |
| AMD FX-8320 Eight-Core Processor                | 6         | 0.78%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 6         | 0.78%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 5         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 5         | 0.65%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 5         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 5         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 5         | 0.65%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 5         | 0.65%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 5         | 0.65%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 5         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 4         | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 4         | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.52%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 4         | 0.52%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 4         | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 0.52%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.52%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 4         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 153       | 19.84%  |
| Intel Core i7           | 121       | 15.69%  |
| Intel Core i3           | 83        | 10.77%  |
| AMD Ryzen 5             | 64        | 8.3%    |
| Intel Celeron           | 46        | 5.97%   |
| Other                   | 43        | 5.58%   |
| Intel Core 2 Duo        | 23        | 2.98%   |
| Intel Atom              | 23        | 2.98%   |
| AMD Ryzen 7             | 17        | 2.2%    |
| AMD Ryzen 3             | 17        | 2.2%    |
| Intel Pentium Dual-Core | 15        | 1.95%   |
| AMD FX                  | 14        | 1.82%   |
| Intel Pentium Dual      | 11        | 1.43%   |
| Intel Pentium           | 11        | 1.43%   |
| AMD A10                 | 11        | 1.43%   |
| AMD A4                  | 9         | 1.17%   |
| AMD A12                 | 9         | 1.17%   |
| Intel Xeon              | 8         | 1.04%   |
| AMD E1                  | 8         | 1.04%   |
| AMD A8                  | 7         | 0.91%   |
| AMD A6                  | 7         | 0.91%   |
| AMD Ryzen 7 PRO         | 6         | 0.78%   |
| AMD Athlon 64 X2        | 5         | 0.65%   |
| AMD Athlon              | 5         | 0.65%   |
| Intel Core 2            | 4         | 0.52%   |
| AMD Ryzen 9             | 4         | 0.52%   |
| AMD Phenom II X6        | 4         | 0.52%   |
| AMD E2                  | 4         | 0.52%   |
| AMD E                   | 4         | 0.52%   |
| AMD Athlon II X2        | 4         | 0.52%   |
| AMD Turion 64 X2 Mobile | 3         | 0.39%   |
| AMD Ryzen Threadripper  | 3         | 0.39%   |
| Intel Pentium 4         | 2         | 0.26%   |
| Intel Core m5           | 2         | 0.26%   |
| Intel Celeron M         | 2         | 0.26%   |
| AMD Sempron             | 2         | 0.26%   |
| AMD Phenom              | 2         | 0.26%   |
| Intel Pentium D         | 1         | 0.13%   |
| Intel Genuine           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 402       | 52.21%  |
| 4       | 245       | 31.82%  |
| 6       | 48        | 6.23%   |
| 1       | 32        | 4.16%   |
| 8       | 26        | 3.38%   |
| 3       | 5         | 0.65%   |
| 16      | 4         | 0.52%   |
| 12      | 4         | 0.52%   |
| 14      | 2         | 0.26%   |
| 10      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 762       | 99.09%  |
| 2      | 7         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 503       | 65.16%  |
| 1       | 266       | 34.46%  |
| 8       | 2         | 0.26%   |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 724       | 93.54%  |
| Unknown        | 39        | 5.04%   |
| 64-bit         | 7         | 0.9%    |
| 32-bit         | 4         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 16.33%  |
| 0x306a9    | 46        | 5.87%   |
| 0x206a7    | 46        | 5.87%   |
| 0x806ea    | 29        | 3.7%    |
| 0x306c3    | 27        | 3.44%   |
| 0x08108109 | 25        | 3.19%   |
| 0x406e3    | 22        | 2.81%   |
| 0x1067a    | 22        | 2.81%   |
| 0x06006705 | 21        | 2.68%   |
| 0x40651    | 18        | 2.3%    |
| 0x306d4    | 18        | 2.3%    |
| 0x6fd      | 17        | 2.17%   |
| 0x906ea    | 15        | 1.91%   |
| 0x806ec    | 15        | 1.91%   |
| 0x20655    | 15        | 1.91%   |
| 0x806e9    | 14        | 1.79%   |
| 0x406c4    | 14        | 1.79%   |
| 0x08108102 | 13        | 1.66%   |
| 0x806c1    | 11        | 1.4%    |
| 0x706e5    | 10        | 1.28%   |
| 0x506e3    | 10        | 1.28%   |
| 0x08701021 | 10        | 1.28%   |
| 0x06000852 | 10        | 1.28%   |
| 0x706a1    | 9         | 1.15%   |
| 0x806eb    | 8         | 1.02%   |
| 0x10676    | 8         | 1.02%   |
| 0x906e9    | 7         | 0.89%   |
| 0x20652    | 7         | 0.89%   |
| 0x106e5    | 7         | 0.89%   |
| 0x06006118 | 7         | 0.89%   |
| 0x05000119 | 7         | 0.89%   |
| 0x30678    | 6         | 0.77%   |
| 0x106ca    | 6         | 0.77%   |
| 0x0a50000c | 6         | 0.77%   |
| 0x08608103 | 6         | 0.77%   |
| 0x08600106 | 6         | 0.77%   |
| 0x08101007 | 6         | 0.77%   |
| 0x06006704 | 6         | 0.77%   |
| 0x0600611a | 6         | 0.77%   |
| 0xa0653    | 5         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 108       | 14.03%  |
| SandyBridge      | 58        | 7.53%   |
| Zen+             | 52        | 6.75%   |
| Haswell          | 52        | 6.75%   |
| IvyBridge        | 50        | 6.49%   |
| Excavator        | 42        | 5.45%   |
| Skylake          | 36        | 4.68%   |
| Penryn           | 34        | 4.42%   |
| Core             | 29        | 3.77%   |
| Westmere         | 28        | 3.64%   |
| Zen 2            | 27        | 3.51%   |
| Silvermont       | 27        | 3.51%   |
| Broadwell        | 20        | 2.6%    |
| Zen              | 19        | 2.47%   |
| Piledriver       | 18        | 2.34%   |
| K8 Hammer        | 15        | 1.95%   |
| IceLake          | 15        | 1.95%   |
| K10              | 14        | 1.82%   |
| TigerLake        | 13        | 1.69%   |
| Goldmont plus    | 13        | 1.69%   |
| CometLake        | 12        | 1.56%   |
| Bonnell          | 12        | 1.56%   |
| Puma             | 11        | 1.43%   |
| Unknown          | 11        | 1.43%   |
| Zen 3            | 9         | 1.17%   |
| Nehalem          | 8         | 1.04%   |
| Bobcat           | 8         | 1.04%   |
| Jaguar           | 7         | 0.91%   |
| NetBurst         | 6         | 0.78%   |
| Steamroller      | 4         | 0.52%   |
| Goldmont         | 4         | 0.52%   |
| K10 Llano        | 3         | 0.39%   |
| Bulldozer        | 2         | 0.26%   |
| Alderlake Hybrid | 2         | 0.26%   |
| K8 & K10 hybrid  | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 459       | 51.23%  |
| AMD                        | 242       | 27.01%  |
| Nvidia                     | 185       | 20.65%  |
| Matrox Electronics Systems | 6         | 0.67%   |
| VIA Technologies           | 4         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 47        | 4.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 4.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 3.72%   |
| Intel UHD Graphics 620                                                                   | 28        | 2.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 2.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 2.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 2.02%   |
| Intel HD Graphics 620                                                                    | 19        | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.91%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.38%   |
| AMD Renoir                                                                               | 13        | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.27%   |
| Intel HD Graphics 530                                                                    | 11        | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 0.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8         | 0.85%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 8         | 0.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 8         | 0.85%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 7         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.74%   |
| AMD Lucienne                                                                             | 7         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.64%   |
| Nvidia GM108M [GeForce MX110]                                                            | 6         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 344       | 44.56%  |
| 1 x AMD         | 186       | 24.09%  |
| Intel + Nvidia  | 98        | 12.69%  |
| 1 x Nvidia      | 76        | 9.84%   |
| 2 x AMD         | 32        | 4.15%   |
| Intel + AMD     | 14        | 1.81%   |
| AMD + Nvidia    | 9         | 1.17%   |
| 1 x Matrox      | 5         | 0.65%   |
| 1 x VIA         | 4         | 0.52%   |
| Other           | 3         | 0.39%   |
| Nvidia + Matrox | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 649       | 83.63%  |
| Proprietary | 88        | 11.34%  |
| Unknown     | 39        | 5.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 423       | 54.09%  |
| 1.01-2.0   | 126       | 16.11%  |
| 0.01-0.5   | 119       | 15.22%  |
| 0.51-1.0   | 56        | 7.16%   |
| 3.01-4.0   | 39        | 4.99%   |
| 5.01-6.0   | 8         | 1.02%   |
| 7.01-8.0   | 6         | 0.77%   |
| 8.01-16.0  | 3         | 0.38%   |
| 2.01-3.0   | 2         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 135       | 16.58%  |
| Samsung Electronics     | 132       | 16.22%  |
| AU Optronics            | 110       | 13.51%  |
| BOE                     | 89        | 10.93%  |
| LG Display              | 67        | 8.23%   |
| Goldstar                | 55        | 6.76%   |
| Hewlett-Packard         | 38        | 4.67%   |
| Dell                    | 24        | 2.95%   |
| Apple                   | 15        | 1.84%   |
| Acer                    | 15        | 1.84%   |
| PANDA                   | 14        | 1.72%   |
| Chi Mei Optoelectronics | 13        | 1.6%    |
| AOC                     | 13        | 1.6%    |
| Sharp                   | 8         | 0.98%   |
| Lenovo                  | 8         | 0.98%   |
| ViewSonic               | 6         | 0.74%   |
| Sony                    | 5         | 0.61%   |
| LG Philips              | 5         | 0.61%   |
| InnoLux Display         | 5         | 0.61%   |
| Unknown                 | 4         | 0.49%   |
| InfoVision              | 4         | 0.49%   |
| BenQ                    | 4         | 0.49%   |
| ASUSTek Computer        | 4         | 0.49%   |
| SAC                     | 3         | 0.37%   |
| LG Electronics          | 3         | 0.37%   |
| HannStar                | 3         | 0.37%   |
| CSO                     | 3         | 0.37%   |
| Sceptre Tech            | 2         | 0.25%   |
| SANYO                   | 2         | 0.25%   |
| MSI                     | 2         | 0.25%   |
| KTC                     | 2         | 0.25%   |
| Ancor Communications    | 2         | 0.25%   |
| AGO                     | 2         | 0.25%   |
| Westinghouse            | 1         | 0.12%   |
| Unknown (XXX)           | 1         | 0.12%   |
| SMC                     | 1         | 0.12%   |
| SKG                     | 1         | 0.12%   |
| PEGA                    | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |
| MStar                   | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 17        | 2.06%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 12        | 1.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 9         | 1.09%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 8         | 0.97%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 8         | 0.97%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 8         | 0.97%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 7         | 0.85%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 7         | 0.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 6         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 6         | 0.73%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.73%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 5         | 0.61%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 5         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 5         | 0.61%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 5         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 5         | 0.61%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                  | 5         | 0.61%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 5         | 0.61%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.48%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 4         | 0.48%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 0.48%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 4         | 0.48%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                  | 4         | 0.48%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.48%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 3         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 3         | 0.36%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 3         | 0.36%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 3         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch | 3         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 356       | 45.7%   |
| 1920x1080 (FHD)    | 215       | 27.6%   |
| 1600x900 (HD+)     | 41        | 5.26%   |
| 3840x2160 (4K)     | 30        | 3.85%   |
| 1440x900 (WXGA+)   | 26        | 3.34%   |
| 1280x1024 (SXGA)   | 23        | 2.95%   |
| 1280x800 (WXGA)    | 19        | 2.44%   |
| 2560x1440 (QHD)    | 9         | 1.16%   |
| 1360x768           | 9         | 1.16%   |
| 1920x1200 (WUXGA)  | 7         | 0.9%    |
| 1024x600           | 7         | 0.9%    |
| 2560x1080          | 5         | 0.64%   |
| 1680x1050 (WSXGA+) | 5         | 0.64%   |
| Unknown            | 4         | 0.51%   |
| 3840x1080          | 3         | 0.39%   |
| 2560x1600          | 3         | 0.39%   |
| 1024x768 (XGA)     | 3         | 0.39%   |
| 3456x2160          | 2         | 0.26%   |
| 3440x1440          | 2         | 0.26%   |
| 2160x1440          | 2         | 0.26%   |
| 1280x720 (HD)      | 2         | 0.26%   |
| 3200x1080          | 1         | 0.13%   |
| 2880x1800          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1536x2048          | 1         | 0.13%   |
| 1152x864           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 200       | 24.39%  |
| 13      | 147       | 17.93%  |
| 14      | 112       | 13.66%  |
| 21      | 52        | 6.34%   |
| 23      | 40        | 4.88%   |
| 18      | 37        | 4.51%   |
| 19      | 36        | 4.39%   |
| 17      | 36        | 4.39%   |
| Unknown | 18        | 2.2%    |
| 27      | 17        | 2.07%   |
| 24      | 16        | 1.95%   |
| 20      | 16        | 1.95%   |
| 12      | 12        | 1.46%   |
| 11      | 11        | 1.34%   |
| 31      | 10        | 1.22%   |
| 10      | 8         | 0.98%   |
| 84      | 6         | 0.73%   |
| 47      | 6         | 0.73%   |
| 22      | 6         | 0.73%   |
| 72      | 5         | 0.61%   |
| 34      | 5         | 0.61%   |
| 16      | 4         | 0.49%   |
| 48      | 3         | 0.37%   |
| 54      | 2         | 0.24%   |
| 40      | 2         | 0.24%   |
| 26      | 2         | 0.24%   |
| 8       | 2         | 0.24%   |
| 63      | 1         | 0.12%   |
| 61      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 44      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 28      | 1         | 0.12%   |
| 9       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 442       | 54.57%  |
| 401-500     | 140       | 17.28%  |
| 501-600     | 66        | 8.15%   |
| 201-300     | 56        | 6.91%   |
| 351-400     | 31        | 3.83%   |
| 601-700     | 18        | 2.22%   |
| Unknown     | 18        | 2.22%   |
| 1001-1500   | 16        | 1.98%   |
| 1501-2000   | 11        | 1.36%   |
| 701-800     | 5         | 0.62%   |
| 101-200     | 3         | 0.37%   |
| 801-900     | 2         | 0.25%   |
| 901-1000    | 2         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 616       | 83.58%  |
| 16/10   | 65        | 8.82%   |
| 5/4     | 21        | 2.85%   |
| Unknown | 15        | 2.04%   |
| 4/3     | 6         | 0.81%   |
| 21/9    | 6         | 0.81%   |
| 3/2     | 4         | 0.54%   |
| 32/9    | 3         | 0.41%   |
| 0.75    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 240       | 29.41%  |
| 101-110        | 200       | 24.51%  |
| 201-250        | 96        | 11.76%  |
| 151-200        | 62        | 7.6%    |
| 141-150        | 51        | 6.25%   |
| 71-80          | 19        | 2.33%   |
| 301-350        | 19        | 2.33%   |
| More than 1000 | 18        | 2.21%   |
| Unknown        | 18        | 2.21%   |
| 351-500        | 15        | 1.84%   |
| 121-130        | 15        | 1.84%   |
| 501-1000       | 13        | 1.59%   |
| 51-60          | 11        | 1.35%   |
| 61-70          | 10        | 1.23%   |
| 41-50          | 9         | 1.1%    |
| 251-300        | 9         | 1.1%    |
| 131-140        | 6         | 0.74%   |
| 111-120        | 3         | 0.37%   |
| 1-40           | 2         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 370       | 46.25%  |
| 51-100        | 215       | 26.88%  |
| 121-160       | 137       | 17.13%  |
| 1-50          | 25        | 3.13%   |
| 161-240       | 22        | 2.75%   |
| Unknown       | 18        | 2.25%   |
| More than 240 | 13        | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 632       | 80%     |
| 2     | 112       | 14.18%  |
| 0     | 41        | 5.19%   |
| 3     | 4         | 0.51%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 502       | 42.58%  |
| Intel                             | 225       | 19.08%  |
| Qualcomm Atheros                  | 185       | 15.69%  |
| Broadcom                          | 72        | 6.11%   |
| Broadcom Limited                  | 30        | 2.54%   |
| Ralink Technology                 | 28        | 2.37%   |
| TP-Link                           | 19        | 1.61%   |
| Ralink                            | 17        | 1.44%   |
| Nvidia                            | 17        | 1.44%   |
| Samsung Electronics               | 10        | 0.85%   |
| Marvell Technology Group          | 10        | 0.85%   |
| Qualcomm Atheros Communications   | 7         | 0.59%   |
| ICS Advent                        | 6         | 0.51%   |
| MediaTek                          | 5         | 0.42%   |
| Huawei Technologies               | 5         | 0.42%   |
| Xiaomi                            | 4         | 0.34%   |
| VIA Technologies                  | 4         | 0.34%   |
| ASIX Electronics                  | 4         | 0.34%   |
| Motorola PCS                      | 3         | 0.25%   |
| Mercucys                          | 3         | 0.25%   |
| D-Link System                     | 3         | 0.25%   |
| T & A Mobile Phones               | 2         | 0.17%   |
| Qualcomm                          | 2         | 0.17%   |
| DisplayLink                       | 2         | 0.17%   |
| Wistron NeWeb                     | 1         | 0.08%   |
| Sundance Technology Inc / IC Plus | 1         | 0.08%   |
| STMicroelectronics                | 1         | 0.08%   |
| Quanta                            | 1         | 0.08%   |
| Prolific Technology               | 1         | 0.08%   |
| OPPO Electronics                  | 1         | 0.08%   |
| Mellanox Technologies             | 1         | 0.08%   |
| Lenovo                            | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| Google                            | 1         | 0.08%   |
| Encore Electronics                | 1         | 0.08%   |
| Dell                              | 1         | 0.08%   |
| Aquantia                          | 1         | 0.08%   |
| 3Com                              | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 322       | 23.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 88        | 6.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.98%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 38        | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 2.62%   |
| Intel Wireless 8265 / 8275                                              | 31        | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 28        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 1.67%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 16        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 14        | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 13        | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.8%    |
| Intel Wireless 7260                                                     | 11        | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                       | 9         | 0.66%   |
| Intel Wireless 8260                                                     | 9         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 8         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.58%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 0.58%   |
| Intel I211 Gigabit Network Connection                                   | 8         | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.51%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 185       | 27.65%  |
| Intel                           | 185       | 27.65%  |
| Qualcomm Atheros                | 150       | 22.42%  |
| Broadcom                        | 43        | 6.43%   |
| Ralink Technology               | 28        | 4.19%   |
| Broadcom Limited                | 20        | 2.99%   |
| TP-Link                         | 19        | 2.84%   |
| Ralink                          | 17        | 2.54%   |
| Qualcomm Atheros Communications | 7         | 1.05%   |
| MediaTek                        | 4         | 0.6%    |
| Mercucys                        | 3         | 0.45%   |
| D-Link System                   | 2         | 0.3%    |
| Wistron NeWeb                   | 1         | 0.15%   |
| Qualcomm                        | 1         | 0.15%   |
| Marvell Technology Group        | 1         | 0.15%   |
| Encore Electronics              | 1         | 0.15%   |
| Dell                            | 1         | 0.15%   |
| 3Com                            | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 6.1%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 38        | 5.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 5.36%   |
| Intel Wireless 8265 / 8275                                              | 31        | 4.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 28        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 2.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 17        | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 13        | 1.93%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.64%   |
| Intel Wireless 7260                                                     | 11        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.49%   |
| Intel Wireless 8260                                                     | 9         | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 8         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.89%   |
| Intel Wireless 7265                                                     | 6         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.89%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 6         | 0.89%   |
| Intel Wireless 3160                                                     | 5         | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.74%   |
| TP-Link 802.11n WLAN Adapter                                            | 4         | 0.6%    |
| Realtek 802.11ac NIC                                                    | 4         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 442       | 63.69%  |
| Intel                             | 81        | 11.67%  |
| Qualcomm Atheros                  | 52        | 7.49%   |
| Broadcom                          | 34        | 4.9%    |
| Nvidia                            | 17        | 2.45%   |
| Samsung Electronics               | 10        | 1.44%   |
| Broadcom Limited                  | 10        | 1.44%   |
| Marvell Technology Group          | 9         | 1.3%    |
| ICS Advent                        | 6         | 0.86%   |
| Huawei Technologies               | 5         | 0.72%   |
| Xiaomi                            | 4         | 0.58%   |
| VIA Technologies                  | 4         | 0.58%   |
| ASIX Electronics                  | 4         | 0.58%   |
| T & A Mobile Phones               | 2         | 0.29%   |
| DisplayLink                       | 2         | 0.29%   |
| Sundance Technology Inc / IC Plus | 1         | 0.14%   |
| Quanta                            | 1         | 0.14%   |
| Qualcomm                          | 1         | 0.14%   |
| Prolific Technology               | 1         | 0.14%   |
| OPPO Electronics                  | 1         | 0.14%   |
| Motorola PCS                      | 1         | 0.14%   |
| Mellanox Technologies             | 1         | 0.14%   |
| MediaTek                          | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 322       | 46.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 12.61%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.15%   |
| Nvidia MCP61 Ethernet                                             | 8         | 1.15%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 7         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.72%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 5         | 0.72%   |
| Huawei LYA-L09                                                    | 5         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.43%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.43%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.43%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 660       | 50.97%  |
| WiFi     | 631       | 48.73%  |
| Unknown  | 3         | 0.23%   |
| Modem    | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 483       | 59.34%  |
| Ethernet | 330       | 40.54%  |
| Unknown  | 1         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 457       | 59.35%  |
| 1     | 294       | 38.18%  |
| 0     | 11        | 1.43%   |
| 3     | 5         | 0.65%   |
| 7     | 1         | 0.13%   |
| 6     | 1         | 0.13%   |
| 4     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 716       | 92.15%  |
| Yes  | 61        | 7.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 31.57%  |
| Realtek Semiconductor           | 95        | 19.35%  |
| IMC Networks                    | 57        | 11.61%  |
| Qualcomm Atheros Communications | 48        | 9.78%   |
| Lite-On Technology              | 29        | 5.91%   |
| Cambridge Silicon Radio         | 28        | 5.7%    |
| Broadcom                        | 18        | 3.67%   |
| Foxconn / Hon Hai               | 13        | 2.65%   |
| Apple                           | 13        | 2.65%   |
| Ralink                          | 8         | 1.63%   |
| Hewlett-Packard                 | 6         | 1.22%   |
| Toshiba                         | 5         | 1.02%   |
| Dell                            | 4         | 0.81%   |
| Realtek                         | 3         | 0.61%   |
| Foxconn International           | 3         | 0.61%   |
| Alps Electric                   | 3         | 0.61%   |
| MediaTek                        | 2         | 0.41%   |
| ASUSTek Computer                | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 69        | 14.05%  |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 10.39%  |
| Realtek Bluetooth Radio                             | 34        | 6.92%   |
| IMC Networks Bluetooth Radio                        | 32        | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 5.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 4.28%   |
| Intel AX201 Bluetooth                               | 19        | 3.87%   |
| Intel AX200 Bluetooth                               | 19        | 3.87%   |
| IMC Networks Bluetooth Device                       | 18        | 3.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 2.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.83%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 7         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.02%   |
| Lite-On Bluetooth Device                            | 5         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.02%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.81%   |
| Apple Bluetooth Host Controller                     | 4         | 0.81%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.61%   |
| Realtek Bluetooth Radio                             | 3         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.61%   |
| Broadcom BCM20702A0                                 | 3         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.61%   |
| Alps Electric BCM2046 Bluetooth Device              | 3         | 0.61%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.41%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.41%   |
| MediaTek Wireless_Device                            | 2         | 0.41%   |
| Lite-On Bluetooth Radio                             | 2         | 0.41%   |
| IMC Networks Wireless_Device                        | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 500       | 54.05%  |
| AMD                         | 252       | 27.24%  |
| Nvidia                      | 118       | 12.76%  |
| C-Media Electronics         | 8         | 0.86%   |
| VIA Technologies            | 6         | 0.65%   |
| Logitech                    | 5         | 0.54%   |
| JMTek                       | 4         | 0.43%   |
| Realtek Semiconductor       | 3         | 0.32%   |
| Generalplus Technology      | 3         | 0.32%   |
| Creative Labs               | 3         | 0.32%   |
| Texas Instruments           | 2         | 0.22%   |
| Plantronics                 | 2         | 0.22%   |
| M-Audio                     | 2         | 0.22%   |
| Kingston Technology         | 2         | 0.22%   |
| Turtle Beach                | 1         | 0.11%   |
| SteelSeries ApS             | 1         | 0.11%   |
| Sennheiser Communications   | 1         | 0.11%   |
| Microsoft                   | 1         | 0.11%   |
| Earth Computer Technologies | 1         | 0.11%   |
| Drop                        | 1         | 0.11%   |
| DCMT Technology             | 1         | 0.11%   |
| Creative Technology         | 1         | 0.11%   |
| Corsair                     | 1         | 0.11%   |
| Cirrus Logic                | 1         | 0.11%   |
| Blue Microphones            | 1         | 0.11%   |
| BEHRINGER International     | 1         | 0.11%   |
| Avid Technology             | 1         | 0.11%   |
| Astro Gaming                | 1         | 0.11%   |
| Apple                       | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 86        | 7.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 74        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 56        | 4.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 56        | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 48        | 4.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 42        | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 35        | 2.97%   |
| AMD FCH Azalia Controller                                                                         | 35        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 32        | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 31        | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 2.55%   |
| AMD High Definition Audio Controller                                                              | 27        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 1.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 1.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 9         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 9         | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 8         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 102       | 24.34%  |
| SK hynix            | 72        | 17.18%  |
| Micron Technology   | 49        | 11.69%  |
| Unknown             | 36        | 8.59%   |
| Kingston            | 32        | 7.64%   |
| A-DATA Technology   | 28        | 6.68%   |
| Crucial             | 15        | 3.58%   |
| Corsair             | 15        | 3.58%   |
| Ramaxel Technology  | 12        | 2.86%   |
| Elpida              | 6         | 1.43%   |
| Nanya Technology    | 5         | 1.19%   |
| G.Skill             | 5         | 1.19%   |
| Avant               | 5         | 1.19%   |
| Team                | 3         | 0.72%   |
| Super Talent        | 3         | 0.72%   |
| GeIL                | 3         | 0.72%   |
| Apacer              | 3         | 0.72%   |
| Unknown             | 3         | 0.72%   |
| PNY                 | 2         | 0.48%   |
| Patriot             | 2         | 0.48%   |
| Kreton              | 2         | 0.48%   |
| Kllisre             | 2         | 0.48%   |
| Hewlett-Packard     | 2         | 0.48%   |
| Unknown (ABCD)      | 1         | 0.24%   |
| Unknown (08AE)      | 1         | 0.24%   |
| Unigen              | 1         | 0.24%   |
| Transcend           | 1         | 0.24%   |
| Sesame              | 1         | 0.24%   |
| Qimonda             | 1         | 0.24%   |
| PUSKILL             | 1         | 0.24%   |
| Hikvision           | 1         | 0.24%   |
| Goldkey             | 1         | 0.24%   |
| ChangXin Memory     | 1         | 0.24%   |
| Centon              | 1         | 0.24%   |
| ASint Technology    | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 9         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 1.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 7         | 1.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 7         | 1.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 1.13%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 4         | 0.9%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 4         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 4         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.9%    |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s        | 3         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 0.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.68%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                   | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 3         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.68%   |
| Unknown                                                      | 3         | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 2         | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2         | 0.45%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.45%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.45%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.45%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 2         | 0.45%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 2         | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.45%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 151       | 46.04%  |
| DDR3    | 119       | 36.28%  |
| DDR2    | 17        | 5.18%   |
| SDRAM   | 15        | 4.57%   |
| LPDDR4  | 12        | 3.66%   |
| Unknown | 6         | 1.83%   |
| LPDDR3  | 4         | 1.22%   |
| DRAM    | 2         | 0.61%   |
| DDR5    | 1         | 0.3%    |
| DDR     | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 215       | 66.98%  |
| DIMM         | 93        | 28.97%  |
| Row Of Chips | 13        | 4.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 144       | 37.89%  |
| 8192  | 122       | 32.11%  |
| 2048  | 55        | 14.47%  |
| 16384 | 33        | 8.68%   |
| 1024  | 15        | 3.95%   |
| 32768 | 8         | 2.11%   |
| 512   | 2         | 0.53%   |
| 128   | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 81        | 22.38%  |
| 2667    | 68        | 18.78%  |
| 3200    | 41        | 11.33%  |
| 2400    | 25        | 6.91%   |
| 1333    | 25        | 6.91%   |
| 2133    | 16        | 4.42%   |
| 1334    | 14        | 3.87%   |
| Unknown | 13        | 3.59%   |
| 3266    | 8         | 2.21%   |
| 3600    | 7         | 1.93%   |
| 800     | 7         | 1.93%   |
| 3000    | 6         | 1.66%   |
| 1067    | 6         | 1.66%   |
| 667     | 5         | 1.38%   |
| 4267    | 4         | 1.1%    |
| 4199    | 4         | 1.1%    |
| 1867    | 4         | 1.1%    |
| 533     | 3         | 0.83%   |
| 3800    | 2         | 0.55%   |
| 3400    | 2         | 0.55%   |
| 2666    | 2         | 0.55%   |
| 1866    | 2         | 0.55%   |
| 1776    | 2         | 0.55%   |
| 1066    | 2         | 0.55%   |
| 333     | 2         | 0.55%   |
| 8400    | 1         | 0.28%   |
| 4800    | 1         | 0.28%   |
| 4266    | 1         | 0.28%   |
| 3733    | 1         | 0.28%   |
| 3500    | 1         | 0.28%   |
| 3100    | 1         | 0.28%   |
| 3066    | 1         | 0.28%   |
| 2800    | 1         | 0.28%   |
| 2176    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |
| 200     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 35.29%  |
| Seiko Epson         | 4         | 23.53%  |
| Samsung Electronics | 3         | 17.65%  |
| SAT                 | 1         | 5.88%   |
| Prolific Technology | 1         | 5.88%   |
| Canon               | 1         | 5.88%   |
| Brother Industries  | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Seiko Epson L120 Series                                | 2         | 11.76%  |
| HP LaserJet Professional P 1102w                       | 2         | 11.76%  |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 5.88%   |
| Seiko Epson L210 Series                                | 1         | 5.88%   |
| SAT SAT38TUSE                                          | 1         | 5.88%   |
| Samsung ML-2010P Mono Laser Printer                    | 1         | 5.88%   |
| Samsung M2020 Series                                   | 1         | 5.88%   |
| Samsung Composite Device                               | 1         | 5.88%   |
| Prolific PL2305 Parallel Port                          | 1         | 5.88%   |
| HP LaserJet CP 1025                                    | 1         | 5.88%   |
| HP LaserJet 1020                                       | 1         | 5.88%   |
| HP Laser 107w                                          | 1         | 5.88%   |
| HP Deskjet 2540 series                                 | 1         | 5.88%   |
| Canon G3000 series                                     | 1         | 5.88%   |
| Brother DCP-T710W                                      | 1         | 5.88%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 113       | 20.04%  |
| IMC Networks                           | 102       | 18.09%  |
| Realtek Semiconductor                  | 42        | 7.45%   |
| Acer                                   | 39        | 6.91%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 6.74%   |
| Microdia                               | 33        | 5.85%   |
| Quanta                                 | 27        | 4.79%   |
| Sunplus Innovation Technology          | 23        | 4.08%   |
| Lite-On Technology                     | 21        | 3.72%   |
| Syntek                                 | 15        | 2.66%   |
| Logitech                               | 15        | 2.66%   |
| Silicon Motion                         | 14        | 2.48%   |
| Suyin                                  | 12        | 2.13%   |
| Apple                                  | 9         | 1.6%    |
| KYE Systems (Mouse Systems)            | 8         | 1.42%   |
| Ricoh                                  | 6         | 1.06%   |
| Alcor Micro                            | 6         | 1.06%   |
| Microsoft                              | 4         | 0.71%   |
| Importek                               | 4         | 0.71%   |
| Cubeternet                             | 4         | 0.71%   |
| ALi                                    | 4         | 0.71%   |
| Z-Star Microelectronics                | 3         | 0.53%   |
| Huawei Technologies                    | 3         | 0.53%   |
| Arkmicro Technologies                  | 3         | 0.53%   |
| Samsung Electronics                    | 2         | 0.35%   |
| Pixart Imaging                         | 2         | 0.35%   |
| OmniVision Technologies                | 2         | 0.35%   |
| Lenovo                                 | 2         | 0.35%   |
| Y Media                                | 1         | 0.18%   |
| Unknown                                | 1         | 0.18%   |
| Sunplus Technology                     | 1         | 0.18%   |
| Sonix Technology                       | 1         | 0.18%   |
| Hewlett-Packard                        | 1         | 0.18%   |
| Genesys Logic                          | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |
| Alcorlink                              | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 45        | 7.98%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 26        | 4.61%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 17        | 3.01%   |
| Microdia Integrated_Webcam_HD                                  | 12        | 2.13%   |
| Chicony Integrated Camera                                      | 12        | 2.13%   |
| Chicony HP TrueVision HD Camera                                | 11        | 1.95%   |
| Acer Integrated Camera                                         | 9         | 1.6%    |
| IMC Networks Integrated Camera                                 | 8         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 8         | 1.42%   |
| Syntek Integrated Camera                                       | 7         | 1.24%   |
| Realtek USB Camera                                             | 7         | 1.24%   |
| Lite-On HP Webcam                                              | 7         | 1.24%   |
| Chicony Lenovo EasyCamera                                      | 7         | 1.24%   |
| Chicony HP Webcam                                              | 7         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 7         | 1.24%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 1.06%   |
| Chicony HD WebCam                                              | 6         | 1.06%   |
| Quanta HP Webcam                                               | 5         | 0.89%   |
| Lite-On HP Wide Vision HD Camera                               | 5         | 0.89%   |
| IMC Networks VGA UVC WebCam                                    | 5         | 0.89%   |
| Acer Lenovo EasyCamera                                         | 5         | 0.89%   |
| Syntek Lenovo EasyCamera                                       | 4         | 0.71%   |
| Syntek EasyCamera                                              | 4         | 0.71%   |
| Suyin 1.3M HD WebCam                                           | 4         | 0.71%   |
| Sunplus HD WebCam                                              | 4         | 0.71%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.71%   |
| Realtek HP Truevision HD                                       | 4         | 0.71%   |
| Realtek HD WebCam                                              | 4         | 0.71%   |
| Quanta HP Wide Vision HD Camera                                | 4         | 0.71%   |
| Lite-On HP HD Camera                                           | 4         | 0.71%   |
| IMC Networks EasyCamera                                        | 4         | 0.71%   |
| Chicony HP Wide Vision HD Camera                               | 4         | 0.71%   |
| Chicony HP High Definition 1MP Webcam                          | 4         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 4         | 0.71%   |
| Acer HD Webcam                                                 | 4         | 0.71%   |
| Acer EasyCamera                                                | 4         | 0.71%   |
| Sunplus ASUS Webcam                                            | 3         | 0.53%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.53%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.53%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 35.14%  |
| Synaptics                  | 18        | 24.32%  |
| Elan Microelectronics      | 12        | 16.22%  |
| Shenzhen Goodix Technology | 9         | 12.16%  |
| Upek                       | 4         | 5.41%   |
| LighTuning Technology      | 2         | 2.7%    |
| AuthenTec                  | 2         | 2.7%    |
| STMicroelectronics         | 1         | 1.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 11        | 14.86%  |
| Unknown                                                                    | 8         | 10.81%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 6.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 6.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.7%    |
| Synaptics  WBDI                                                            | 2         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.35%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.35%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.35%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.35%   |
| Synaptics WBDI Device                                                      | 1         | 1.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.35%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.35%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.35%   |
| AuthenTec AES2810                                                          | 1         | 1.35%   |
| AuthenTec AES1600                                                          | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 40%     |
| Upek                  | 2         | 13.33%  |
| O2 Micro              | 2         | 13.33%  |
| Lenovo                | 2         | 13.33%  |
| Alcor Micro           | 2         | 13.33%  |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 13.33%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 13.33%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 6.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 526       | 67.18%  |
| 1     | 218       | 27.84%  |
| 2     | 36        | 4.6%    |
| 7     | 1         | 0.13%   |
| 4     | 1         | 0.13%   |
| 3     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 74        | 25.34%  |
| Net/wireless             | 70        | 23.97%  |
| Graphics card            | 61        | 20.89%  |
| Multimedia controller    | 26        | 8.9%    |
| Chipcard                 | 15        | 5.14%   |
| Bluetooth                | 14        | 4.79%   |
| Communication controller | 8         | 2.74%   |
| Sound                    | 5         | 1.71%   |
| Camera                   | 5         | 1.71%   |
| Storage                  | 3         | 1.03%   |
| Card reader              | 3         | 1.03%   |
| Storage/raid             | 2         | 0.68%   |
| Net/ethernet             | 2         | 0.68%   |
| Unassigned class         | 1         | 0.34%   |
| Network                  | 1         | 0.34%   |
| Flash memory             | 1         | 0.34%   |
| Firewire controller      | 1         | 0.34%   |

