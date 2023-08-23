Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 759

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [f016fa3756](https://linux-hardware.org/?probe=f016fa3756) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [d490bb32ec](https://linux-hardware.org/?probe=d490bb32ec) | Aug 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [fffee60e72](https://linux-hardware.org/?probe=fffee60e72) | Aug 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [101c521941](https://linux-hardware.org/?probe=101c521941) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [f7c7290847](https://linux-hardware.org/?probe=f7c7290847) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [9a0fa703d7](https://linux-hardware.org/?probe=9a0fa703d7) | Aug 07, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2cb4df0aab](https://linux-hardware.org/?probe=2cb4df0aab) | Aug 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | Notebook    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [18dad15a33](https://linux-hardware.org/?probe=18dad15a33) | Aug 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [ceb7e754a1](https://linux-hardware.org/?probe=ceb7e754a1) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [38e481c3d5](https://linux-hardware.org/?probe=38e481c3d5) | Jul 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [513ac15990](https://linux-hardware.org/?probe=513ac15990) | Jul 28, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [f37cf89f5f](https://linux-hardware.org/?probe=f37cf89f5f) | Jul 28, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [23c1f6fa05](https://linux-hardware.org/?probe=23c1f6fa05) | Jul 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [49cbe32874](https://linux-hardware.org/?probe=49cbe32874) | Jul 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [c9c42e4857](https://linux-hardware.org/?probe=c9c42e4857) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [319cb6659d](https://linux-hardware.org/?probe=319cb6659d) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [228ded2955](https://linux-hardware.org/?probe=228ded2955) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [2109b6ace6](https://linux-hardware.org/?probe=2109b6ace6) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [25311760a9](https://linux-hardware.org/?probe=25311760a9) | Jul 21, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0ba223e9ae](https://linux-hardware.org/?probe=0ba223e9ae) | Jul 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [26313914e4](https://linux-hardware.org/?probe=26313914e4) | Jul 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| Toshiba       | Satellite S55t-C            | Notebook    | [be8777b248](https://linux-hardware.org/?probe=be8777b248) | Jul 17, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [70b7e2a7f5](https://linux-hardware.org/?probe=70b7e2a7f5) | Jul 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ac55f32c4e](https://linux-hardware.org/?probe=ac55f32c4e) | Jul 16, 2023 |
| ASRock        | H370 Performance            | Desktop     | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| HP            | 3396                        | Desktop     | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d8550d27e3](https://linux-hardware.org/?probe=d8550d27e3) | Jul 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c27ff02a84](https://linux-hardware.org/?probe=c27ff02a84) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [7026c5b007](https://linux-hardware.org/?probe=7026c5b007) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8e3cc576fd](https://linux-hardware.org/?probe=8e3cc576fd) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | Desktop     | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| Acer          | Nitro N50-620               | Desktop     | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Dell          | G7 7790                     | Notebook    | [a6dd0d72f7](https://linux-hardware.org/?probe=a6dd0d72f7) | Jul 06, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [afa2978397](https://linux-hardware.org/?probe=afa2978397) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9472db0bf4](https://linux-hardware.org/?probe=9472db0bf4) | Jul 04, 2023 |
| GPD           | G1618-03                    | Desktop     | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| Dell          | Latitude E5440              | Notebook    | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| Samsung       | 730QED                      | Convertible | [5bcec42625](https://linux-hardware.org/?probe=5bcec42625) | Jul 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [626416c230](https://linux-hardware.org/?probe=626416c230) | Jul 03, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [be7a8d9ce0](https://linux-hardware.org/?probe=be7a8d9ce0) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| Dell          | G7 7790                     | Notebook    | [6345fbbe32](https://linux-hardware.org/?probe=6345fbbe32) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [ff1f31ff36](https://linux-hardware.org/?probe=ff1f31ff36) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [d4362fb3ca](https://linux-hardware.org/?probe=d4362fb3ca) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c93f4f0d0b](https://linux-hardware.org/?probe=c93f4f0d0b) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [bbd5ba331d](https://linux-hardware.org/?probe=bbd5ba331d) | Jun 30, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4846eae54f](https://linux-hardware.org/?probe=4846eae54f) | Jun 28, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [f5c922b6d3](https://linux-hardware.org/?probe=f5c922b6d3) | Jun 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [c77b479e22](https://linux-hardware.org/?probe=c77b479e22) | Jun 27, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [c243b40ffb](https://linux-hardware.org/?probe=c243b40ffb) | Jun 26, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [5e67041129](https://linux-hardware.org/?probe=5e67041129) | Jun 26, 2023 |
| Google        | Blooglet                    | Notebook    | [88fae074d1](https://linux-hardware.org/?probe=88fae074d1) | Jun 25, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [279f2cedcc](https://linux-hardware.org/?probe=279f2cedcc) | Jun 24, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [f83de9c7b9](https://linux-hardware.org/?probe=f83de9c7b9) | Jun 24, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [305e202fd3](https://linux-hardware.org/?probe=305e202fd3) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [379c36642b](https://linux-hardware.org/?probe=379c36642b) | Jun 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [2656caf6b8](https://linux-hardware.org/?probe=2656caf6b8) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [2805733dcd](https://linux-hardware.org/?probe=2805733dcd) | Jun 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [370e948985](https://linux-hardware.org/?probe=370e948985) | Jun 21, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f7a3caaef1](https://linux-hardware.org/?probe=f7a3caaef1) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f11d231c6a](https://linux-hardware.org/?probe=f11d231c6a) | Jun 20, 2023 |
| Timi          | A30                         | Notebook    | [34d77f385a](https://linux-hardware.org/?probe=34d77f385a) | Jun 19, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [10cf405f89](https://linux-hardware.org/?probe=10cf405f89) | Jun 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [cbbfdafd46](https://linux-hardware.org/?probe=cbbfdafd46) | Jun 17, 2023 |
| ASRock        | Z370 Gaming-ITX/ac          | Desktop     | [e05a90c6c5](https://linux-hardware.org/?probe=e05a90c6c5) | Jun 16, 2023 |
| HP            | 8054                        | Desktop     | [97a4b34236](https://linux-hardware.org/?probe=97a4b34236) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [3edca35793](https://linux-hardware.org/?probe=3edca35793) | Jun 14, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| Google        | Blooglet                    | Notebook    | [80ce635393](https://linux-hardware.org/?probe=80ce635393) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [386f19f4f1](https://linux-hardware.org/?probe=386f19f4f1) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [f5eeb72c4d](https://linux-hardware.org/?probe=f5eeb72c4d) | May 31, 2023 |
| Samsung       | 730QED                      | Convertible | [8b5ecbd84f](https://linux-hardware.org/?probe=8b5ecbd84f) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0cb4af5367](https://linux-hardware.org/?probe=0cb4af5367) | May 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S06Q0... | Notebook    | [e54e204b28](https://linux-hardware.org/?probe=e54e204b28) | May 29, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [9496942a44](https://linux-hardware.org/?probe=9496942a44) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [447bbfbd40](https://linux-hardware.org/?probe=447bbfbd40) | May 27, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [c2640c22ff](https://linux-hardware.org/?probe=c2640c22ff) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6bf848e58f](https://linux-hardware.org/?probe=6bf848e58f) | May 25, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [cc674d2878](https://linux-hardware.org/?probe=cc674d2878) | May 25, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [c43cfd04ad](https://linux-hardware.org/?probe=c43cfd04ad) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [a5df8ea9d7](https://linux-hardware.org/?probe=a5df8ea9d7) | May 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [1e648e8f50](https://linux-hardware.org/?probe=1e648e8f50) | May 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [b034244bec](https://linux-hardware.org/?probe=b034244bec) | May 20, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [758f0dbd4b](https://linux-hardware.org/?probe=758f0dbd4b) | May 19, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Samsung       | 730QED                      | Convertible | [7440f51d53](https://linux-hardware.org/?probe=7440f51d53) | May 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fee6b2f55b](https://linux-hardware.org/?probe=fee6b2f55b) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [40d1bba9e2](https://linux-hardware.org/?probe=40d1bba9e2) | May 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [e2ce1c3d6c](https://linux-hardware.org/?probe=e2ce1c3d6c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [b0a2a0b536](https://linux-hardware.org/?probe=b0a2a0b536) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [d7c37a25de](https://linux-hardware.org/?probe=d7c37a25de) | May 05, 2023 |
| Samsung       | 535U3C                      | Notebook    | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [352e8b2616](https://linux-hardware.org/?probe=352e8b2616) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Supermicro    | X10SAE                      | Server      | [4b0cfec9a7](https://linux-hardware.org/?probe=4b0cfec9a7) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f29d1d7b8](https://linux-hardware.org/?probe=2f29d1d7b8) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [222d699e31](https://linux-hardware.org/?probe=222d699e31) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | Notebook    | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Unknown       | ACB20                       | Notebook    | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | Desktop     | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [eba8868f8b](https://linux-hardware.org/?probe=eba8868f8b) | Mar 20, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [ab9d7b857f](https://linux-hardware.org/?probe=ab9d7b857f) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [7659c07b7c](https://linux-hardware.org/?probe=7659c07b7c) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | Notebook    | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | Notebook    | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 36 | 255       | 44.43%  |
| Nobara 37 | 252       | 43.9%   |
| Nobara 38 | 67        | 11.67%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 561       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.0.14-201.fsync.fc36.x86_64  | 37        | 6.11%   |
| 6.0.10-201.fc36.x86_64        | 37        | 6.11%   |
| 6.2.14-300.fsync.fc37.x86_64  | 32        | 5.28%   |
| 6.3.12-204.fsync.fc38.x86_64  | 27        | 4.46%   |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 4.13%   |
| 5.19.14-201.fsync.fc36.x86_64 | 25        | 4.13%   |
| 6.1.11-201.fsync.fc37.x86_64  | 19        | 3.14%   |
| 6.2.12-200.fsync.fc37.x86_64  | 18        | 2.97%   |
| 6.2.6-201.fsync.fc37.x86_64   | 17        | 2.81%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 2.81%   |
| 6.1.4-203.fsync.fc37.x86_64   | 17        | 2.81%   |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 2.64%   |
| 5.19.7-204.fsync.fc36.x86_64  | 16        | 2.64%   |
| 6.3.10-200.fsync.fc38.x86_64  | 14        | 2.31%   |
| 6.3.7-200.fsync.fc37.x86_64   | 13        | 2.15%   |
| 6.2.10-200.fsync.fc37.x86_64  | 13        | 2.15%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 1.98%   |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 1.98%   |
| 6.2.8-200.fsync.fc37.x86_64   | 11        | 1.82%   |
| 6.0.5-201.fsync.fc36.x86_64   | 11        | 1.82%   |
| 6.0.16-301.fsync.fc37.x86_64  | 11        | 1.82%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 1.82%   |
| 6.3.5-201.fsync.fc37.x86_64   | 10        | 1.65%   |
| 6.3.12-205.fsync.fc38.x86_64  | 10        | 1.65%   |
| 6.1.6-203.fsync.fc37.x86_64   | 10        | 1.65%   |
| 6.2.11-201.fsync.fc37.x86_64  | 9         | 1.49%   |
| 6.1.8-202.fsync.fc37.x86_64   | 9         | 1.49%   |
| 6.0.9-201.fc36.x86_64         | 9         | 1.49%   |
| 5.19.12-201.fsync.fc36.x86_64 | 8         | 1.32%   |
| 5.19.10-201.fsync.fc36.x86_64 | 8         | 1.32%   |
| 6.3.12-203.fsync.fc38.x86_64  | 7         | 1.16%   |
| 6.2.11-202.fsync.fc37.x86_64  | 7         | 1.16%   |
| 5.19.4-201.fsync.fc36.x86_64  | 7         | 1.16%   |
| 5.18.16-201.fsync.fc36.x86_64 | 7         | 1.16%   |
| 5.19.15-202.fsync.fc36.x86_64 | 6         | 0.99%   |
| 5.19.11-201.fsync.fc36.x86_64 | 6         | 0.99%   |
| 5.18.17-201.fsync.fc36.x86_64 | 6         | 0.99%   |
| 6.3.12-204.fsync.fc37.x86_64  | 4         | 0.66%   |
| 6.3.10-200.fsync.fc37.x86_64  | 4         | 0.66%   |
| 6.1.6-201.fsync.fc37.x86_64   | 4         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.12  | 49        | 8.1%    |
| 6.0.14  | 37        | 6.12%   |
| 6.0.10  | 37        | 6.12%   |
| 6.2.14  | 33        | 5.45%   |
| 6.1.14  | 25        | 4.13%   |
| 5.19.14 | 25        | 4.13%   |
| 6.3.10  | 20        | 3.31%   |
| 6.1.11  | 19        | 3.14%   |
| 6.2.12  | 18        | 2.98%   |
| 5.19.7  | 18        | 2.98%   |
| 6.2.6   | 17        | 2.81%   |
| 6.1.9   | 17        | 2.81%   |
| 6.1.4   | 17        | 2.81%   |
| 6.2.11  | 16        | 2.64%   |
| 6.1.6   | 16        | 2.64%   |
| 6.0.7   | 16        | 2.64%   |
| 5.19.9  | 16        | 2.64%   |
| 6.3.7   | 14        | 2.31%   |
| 6.2.10  | 13        | 2.15%   |
| 6.1.8   | 13        | 2.15%   |
| 6.0.9   | 13        | 2.15%   |
| 5.19.16 | 12        | 1.98%   |
| 6.3.5   | 11        | 1.82%   |
| 6.2.8   | 11        | 1.82%   |
| 6.0.5   | 11        | 1.82%   |
| 6.0.16  | 11        | 1.82%   |
| 5.18.13 | 11        | 1.82%   |
| 5.19.12 | 8         | 1.32%   |
| 5.19.10 | 8         | 1.32%   |
| 5.19.4  | 7         | 1.16%   |
| 5.18.16 | 7         | 1.16%   |
| 5.19.15 | 6         | 0.99%   |
| 5.19.11 | 6         | 0.99%   |
| 5.18.17 | 6         | 0.99%   |
| 6.3.9   | 4         | 0.66%   |
| 6.0.8   | 4         | 0.66%   |
| 5.19.8  | 4         | 0.66%   |
| 5.18.19 | 4         | 0.66%   |
| 6.3.4   | 3         | 0.5%    |
| 5.19.13 | 3         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 130       | 21.92%  |
| 5.19    | 114       | 19.22%  |
| 6.1     | 107       | 18.04%  |
| 6.2     | 105       | 17.71%  |
| 6.3     | 99        | 16.69%  |
| 5.18    | 34        | 5.73%   |
| 6.4     | 4         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 561       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 407       | 72.04%  |
| KDE5          | 146       | 25.84%  |
| Unknown       | 8         | 1.42%   |
| GNOME Classic | 2         | 0.35%   |
| X-Cinnamon    | 1         | 0.18%   |
| sway          | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 432       | 75.66%  |
| X11     | 132       | 23.12%  |
| Unknown | 5         | 0.88%   |
| Tty     | 2         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 454       | 80.07%  |
| GDM     | 74        | 13.05%  |
| SDDM    | 35        | 6.17%   |
| LightDM | 4         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 303       | 53.72%  |
| en_GB   | 48        | 8.51%   |
| de_DE   | 28        | 4.96%   |
| es_ES   | 20        | 3.55%   |
| es_MX   | 15        | 2.66%   |
| pl_PL   | 13        | 2.3%    |
| pt_BR   | 12        | 2.13%   |
| en_CA   | 12        | 2.13%   |
| ru_RU   | 11        | 1.95%   |
| es_AR   | 10        | 1.77%   |
| it_IT   | 9         | 1.6%    |
| fr_FR   | 9         | 1.6%    |
| en_NZ   | 8         | 1.42%   |
| de_AT   | 6         | 1.06%   |
| en_IN   | 5         | 0.89%   |
| Unknown | 5         | 0.89%   |
| pt_PT   | 4         | 0.71%   |
| nl_NL   | 4         | 0.71%   |
| es_CO   | 4         | 0.71%   |
| en_AU   | 4         | 0.71%   |
| en_PH   | 3         | 0.53%   |
| zh_TW   | 2         | 0.35%   |
| tr_TR   | 2         | 0.35%   |
| sv_SE   | 2         | 0.35%   |
| fi_FI   | 2         | 0.35%   |
| es_CL   | 2         | 0.35%   |
| ar_SA   | 2         | 0.35%   |
| sk_SK   | 1         | 0.18%   |
| ro_RO   | 1         | 0.18%   |
| nl_BE   | 1         | 0.18%   |
| nb_NO   | 1         | 0.18%   |
| hu_HU   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| fr_BE   | 1         | 0.18%   |
| es_US   | 1         | 0.18%   |
| es_GT   | 1         | 0.18%   |
| es_EC   | 1         | 0.18%   |
| es_CR   | 1         | 0.18%   |
| en_ZA   | 1         | 0.18%   |
| en_SG   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 459       | 81.1%   |
| BIOS | 107       | 18.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 418       | 74.11%  |
| Ext4  | 144       | 25.53%  |
| Xfs   | 2         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 447       | 78.7%   |
| GPT     | 113       | 19.89%  |
| MBR     | 8         | 1.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 528       | 93.78%  |
| Yes       | 35        | 6.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 504       | 89.68%  |
| Yes       | 58        | 10.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 131       | 23.35%  |
| MSI                                  | 77        | 13.73%  |
| Lenovo                               | 67        | 11.94%  |
| Hewlett-Packard                      | 58        | 10.34%  |
| Gigabyte Technology                  | 51        | 9.09%   |
| Dell                                 | 37        | 6.6%    |
| ASRock                               | 35        | 6.24%   |
| Acer                                 | 18        | 3.21%   |
| Apple                                | 17        | 3.03%   |
| Intel                                | 7         | 1.25%   |
| Samsung Electronics                  | 5         | 0.89%   |
| Toshiba                              | 4         | 0.71%   |
| Alienware                            | 4         | 0.71%   |
| Unknown                              | 3         | 0.53%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.36%   |
| Positivo                             | 2         | 0.36%   |
| Notebook                             | 2         | 0.36%   |
| Microsoft                            | 2         | 0.36%   |
| Fujitsu                              | 2         | 0.36%   |
| Biostar                              | 2         | 0.36%   |
| AZW                                  | 2         | 0.36%   |
| Acidanthera                          | 2         | 0.36%   |
| ZOTAC                                | 1         | 0.18%   |
| Valve                                | 1         | 0.18%   |
| Timi                                 | 1         | 0.18%   |
| Supermicro                           | 1         | 0.18%   |
| Sony                                 | 1         | 0.18%   |
| Schenker                             | 1         | 0.18%   |
| Razer                                | 1         | 0.18%   |
| Protectli                            | 1         | 0.18%   |
| Packard Bell                         | 1         | 0.18%   |
| ONE-NETBOOK                          | 1         | 0.18%   |
| OEM                                  | 1         | 0.18%   |
| NZXT                                 | 1         | 0.18%   |
| Monster                              | 1         | 0.18%   |
| Micro Electronics                    | 1         | 0.18%   |
| Micro Computer (HK) Tech Limited     | 1         | 0.18%   |
| Medion                               | 1         | 0.18%   |
| langchao                             | 1         | 0.18%   |
| Infinix                              | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7B86                         | 8         | 1.43%   |
| Unknown                             | 7         | 1.25%   |
| MSI MS-7D25                         | 5         | 0.89%   |
| MSI MS-7C91                         | 5         | 0.89%   |
| MSI MS-7C37                         | 5         | 0.89%   |
| ASUS All Series                     | 5         | 0.89%   |
| MSI MS-7C02                         | 4         | 0.71%   |
| MSI MS-7B79                         | 4         | 0.71%   |
| ASUS ROG STRIX B550-F GAMING        | 4         | 0.71%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 0.53%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 3         | 0.53%   |
| Gigabyte B550 AORUS ELITE V2        | 3         | 0.53%   |
| Dell XPS 8700                       | 3         | 0.53%   |
| ASUS PRIME A320M-K                  | 3         | 0.53%   |
| Samsung 730QED                      | 2         | 0.36%   |
| MSI MS-7C87                         | 2         | 0.36%   |
| MSI MS-7C56                         | 2         | 0.36%   |
| MSI MS-7B85                         | 2         | 0.36%   |
| MSI MS-7721                         | 2         | 0.36%   |
| MSI MS-7693                         | 2         | 0.36%   |
| Lenovo Legion 5 15ARH05H 82B1       | 2         | 0.36%   |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.36%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 2         | 0.36%   |
| Lenovo IdeaPad C340-14API 81N6      | 2         | 0.36%   |
| Lenovo IdeaPad 5 15ITL05 82FG       | 2         | 0.36%   |
| Intel X79                           | 2         | 0.36%   |
| HP ZBook 15u G3                     | 2         | 0.36%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.36%   |
| HP Pavilion 15                      | 2         | 0.36%   |
| HP EliteBook x360 1030 G2           | 2         | 0.36%   |
| Gigabyte Z590I VISION D             | 2         | 0.36%   |
| Gigabyte X570 AORUS ELITE WIFI      | 2         | 0.36%   |
| Gigabyte X570 AORUS ELITE           | 2         | 0.36%   |
| Gigabyte B450M DS3H                 | 2         | 0.36%   |
| Dell Vostro 3400                    | 2         | 0.36%   |
| Dell OptiPlex 390                   | 2         | 0.36%   |
| Dell Inspiron 3542                  | 2         | 0.36%   |
| Dell Inspiron 15 3520               | 2         | 0.36%   |
| ASUS TUF Gaming B550M-PLUS          | 2         | 0.36%   |
| ASUS TUF Gaming B550-PLUS           | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 38        | 6.77%   |
| ASUS TUF           | 21        | 3.74%   |
| ASUS PRIME         | 21        | 3.74%   |
| Lenovo IdeaPad     | 19        | 3.39%   |
| Lenovo ThinkPad    | 16        | 2.85%   |
| HP Pavilion        | 14        | 2.5%    |
| Lenovo Legion      | 12        | 2.14%   |
| ASUS VivoBook      | 10        | 1.78%   |
| MSI MS-7B86        | 8         | 1.43%   |
| HP EliteBook       | 8         | 1.43%   |
| Dell Inspiron      | 8         | 1.43%   |
| Gigabyte X570      | 7         | 1.25%   |
| Acer Aspire        | 7         | 1.25%   |
| Unknown            | 7         | 1.25%   |
| HP ENVY            | 6         | 1.07%   |
| Dell Precision     | 6         | 1.07%   |
| Dell OptiPlex      | 6         | 1.07%   |
| Acer Nitro         | 6         | 1.07%   |
| MSI MS-7D25        | 5         | 0.89%   |
| MSI MS-7C91        | 5         | 0.89%   |
| MSI MS-7C37        | 5         | 0.89%   |
| Lenovo ThinkCentre | 5         | 0.89%   |
| HP ZBook           | 5         | 0.89%   |
| ASUS All           | 5         | 0.89%   |
| MSI MS-7C02        | 4         | 0.71%   |
| MSI MS-7B79        | 4         | 0.71%   |
| Gigabyte B550      | 4         | 0.71%   |
| Dell Vostro        | 4         | 0.71%   |
| ASUS ASUS          | 4         | 0.71%   |
| Apple MacBookPro8  | 4         | 0.71%   |
| Toshiba Satellite  | 3         | 0.53%   |
| Lenovo Yoga        | 3         | 0.53%   |
| HP Laptop          | 3         | 0.53%   |
| HP EliteDesk       | 3         | 0.53%   |
| HP Compaq          | 3         | 0.53%   |
| Gigabyte B550M     | 3         | 0.53%   |
| Dell XPS           | 3         | 0.53%   |
| Dell Latitude      | 3         | 0.53%   |
| ASRock B550        | 3         | 0.53%   |
| Samsung 730QED     | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 77        | 13.73%  |
| 2021 | 75        | 13.37%  |
| 2019 | 70        | 12.48%  |
| 2022 | 60        | 10.7%   |
| 2018 | 57        | 10.16%  |
| 2013 | 40        | 7.13%   |
| 2014 | 32        | 5.7%    |
| 2017 | 31        | 5.53%   |
| 2012 | 29        | 5.17%   |
| 2016 | 26        | 4.63%   |
| 2015 | 18        | 3.21%   |
| 2011 | 17        | 3.03%   |
| 2023 | 9         | 1.6%    |
| 2010 | 8         | 1.43%   |
| 2009 | 7         | 1.25%   |
| 2008 | 4         | 0.71%   |
| 2007 | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 291       | 51.87%  |
| Notebook    | 234       | 41.71%  |
| Convertible | 14        | 2.5%    |
| Mini pc     | 9         | 1.6%    |
| All in one  | 6         | 1.07%   |
| Tablet      | 5         | 0.89%   |
| Other       | 1         | 0.18%   |
| Server      | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 561       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 560       | 99.82%  |
| Yes  | 1         | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 165       | 29.36%  |
| 32.01-64.0      | 120       | 21.35%  |
| 4.01-8.0        | 93        | 16.55%  |
| 8.01-16.0       | 88        | 15.66%  |
| 3.01-4.0        | 42        | 7.47%   |
| 24.01-32.0      | 29        | 5.16%   |
| 64.01-256.0     | 21        | 3.74%   |
| 1.01-2.0        | 3         | 0.53%   |
| More than 256.0 | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 265       | 45.07%  |
| 3.01-4.0   | 131       | 22.28%  |
| 2.01-3.0   | 102       | 17.35%  |
| 8.01-16.0  | 60        | 10.2%   |
| 1.01-2.0   | 18        | 3.06%   |
| 16.01-24.0 | 8         | 1.36%   |
| 24.01-32.0 | 3         | 0.51%   |
| 32.01-64.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 259       | 45.44%  |
| 2      | 159       | 27.89%  |
| 3      | 79        | 13.86%  |
| 4      | 29        | 5.09%   |
| 5      | 26        | 4.56%   |
| 6      | 7         | 1.23%   |
| 7      | 4         | 0.7%    |
| 8      | 3         | 0.53%   |
| 10     | 2         | 0.35%   |
| 9      | 2         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 457       | 81.03%  |
| Yes       | 107       | 18.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 498       | 88.45%  |
| No        | 65        | 11.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 437       | 77.48%  |
| No        | 127       | 22.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 401       | 71.35%  |
| No        | 161       | 28.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 179       | 31.91%  |
| Germany      | 39        | 6.95%   |
| UK           | 31        | 5.53%   |
| Spain        | 21        | 3.74%   |
| Poland       | 19        | 3.39%   |
| Brazil       | 17        | 3.03%   |
| France       | 16        | 2.85%   |
| Canada       | 16        | 2.85%   |
| Argentina    | 15        | 2.67%   |
| Russia       | 14        | 2.5%    |
| Mexico       | 13        | 2.32%   |
| Italy        | 13        | 2.32%   |
| Netherlands  | 11        | 1.96%   |
| Sweden       | 8         | 1.43%   |
| New Zealand  | 8         | 1.43%   |
| Austria      | 8         | 1.43%   |
| Australia    | 8         | 1.43%   |
| Portugal     | 7         | 1.25%   |
| India        | 7         | 1.25%   |
| Philippines  | 6         | 1.07%   |
| Finland      | 6         | 1.07%   |
| Colombia     | 6         | 1.07%   |
| Chile        | 6         | 1.07%   |
| Turkey       | 5         | 0.89%   |
| Saudi Arabia | 5         | 0.89%   |
| Romania      | 4         | 0.71%   |
| Indonesia    | 4         | 0.71%   |
| Hungary      | 4         | 0.71%   |
| Belgium      | 4         | 0.71%   |
| Venezuela    | 3         | 0.53%   |
| Serbia       | 3         | 0.53%   |
| Norway       | 3         | 0.53%   |
| Malaysia     | 3         | 0.53%   |
| Estonia      | 3         | 0.53%   |
| Czechia      | 3         | 0.53%   |
| Croatia      | 3         | 0.53%   |
| Vietnam      | 2         | 0.36%   |
| South Africa | 2         | 0.36%   |
| Singapore    | 2         | 0.36%   |
| Japan        | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Guadalajara   | 5         | 0.86%   |
| Atlanta       | 5         | 0.86%   |
| Stockholm     | 4         | 0.69%   |
| San Francisco | 4         | 0.69%   |
| Buenos Aires  | 4         | 0.69%   |
| Berlin        | 4         | 0.69%   |
| Auckland      | 4         | 0.69%   |
| Wroclaw       | 3         | 0.52%   |
| Wellington    | 3         | 0.52%   |
| Warsaw        | 3         | 0.52%   |
| Vienna        | 3         | 0.52%   |
| San Jose      | 3         | 0.52%   |
| Rotterdam     | 3         | 0.52%   |
| Rome          | 3         | 0.52%   |
| Poznan        | 3         | 0.52%   |
| Philadelphia  | 3         | 0.52%   |
| Perm          | 3         | 0.52%   |
| Nuremberg     | 3         | 0.52%   |
| Melbourne     | 3         | 0.52%   |
| Madrid        | 3         | 0.52%   |
| Kuala Lumpur  | 3         | 0.52%   |
| Denver        | 3         | 0.52%   |
| Boynton Beach | 3         | 0.52%   |
| Wasilla       | 2         | 0.34%   |
| Villa Nueva   | 2         | 0.34%   |
| Victoria      | 2         | 0.34%   |
| Valladolid    | 2         | 0.34%   |
| Tucson        | 2         | 0.34%   |
| Toulouse      | 2         | 0.34%   |
| Sydney        | 2         | 0.34%   |
| Springfield   | 2         | 0.34%   |
| Singapore     | 2         | 0.34%   |
| Seattle       | 2         | 0.34%   |
| Schmalkalden  | 2         | 0.34%   |
| Sao Paulo     | 2         | 0.34%   |
| San Diego     | 2         | 0.34%   |
| San Antonio   | 2         | 0.34%   |
| Samara        | 2         | 0.34%   |
| Salem         | 2         | 0.34%   |
| Riyadh        | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 182       | 283    | 17.98%  |
| WDC                         | 121       | 169    | 11.96%  |
| Seagate                     | 101       | 135    | 9.98%   |
| Sandisk                     | 72        | 86     | 7.11%   |
| Kingston                    | 71        | 78     | 7.02%   |
| Toshiba                     | 57        | 67     | 5.63%   |
| Crucial                     | 53        | 72     | 5.24%   |
| Intel                       | 31        | 39     | 3.06%   |
| Phison Electronics          | 28        | 32     | 2.77%   |
| Micron/Crucial Technology   | 28        | 36     | 2.77%   |
| SK hynix                    | 23        | 24     | 2.27%   |
| Micron Technology           | 20        | 21     | 1.98%   |
| Unknown                     | 18        | 23     | 1.78%   |
| Hitachi                     | 14        | 19     | 1.38%   |
| Kingston Technology Company | 12        | 12     | 1.19%   |
| HGST                        | 12        | 15     | 1.19%   |
| PNY                         | 11        | 18     | 1.09%   |
| China                       | 10        | 10     | 0.99%   |
| SPCC                        | 9         | 11     | 0.89%   |
| KIOXIA                      | 9         | 10     | 0.89%   |
| Apple                       | 9         | 10     | 0.89%   |
| Team                        | 8         | 8      | 0.79%   |
| Silicon Motion              | 8         | 8      | 0.79%   |
| Phison                      | 8         | 9      | 0.79%   |
| A-DATA Technology           | 7         | 7      | 0.69%   |
| ADATA Technology            | 6         | 6      | 0.59%   |
| Realtek Semiconductor       | 5         | 5      | 0.49%   |
| KIOXIA-EXCERIA              | 3         | 3      | 0.3%    |
| Intenso                     | 3         | 4      | 0.3%    |
| HS-SSD-C100                 | 3         | 3      | 0.3%    |
| Apacer                      | 3         | 3      | 0.3%    |
| Unknown                     | 3         | 4      | 0.3%    |
| Verbatim                    | 2         | 2      | 0.2%    |
| USB3.0                      | 2         | 2      | 0.2%    |
| Union Memory                | 2         | 3      | 0.2%    |
| Transcend                   | 2         | 2      | 0.2%    |
| Realtek                     | 2         | 2      | 0.2%    |
| OCZ                         | 2         | 2      | 0.2%    |
| Mushkin                     | 2         | 2      | 0.2%    |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 36        | 3.15%   |
| Kingston SA400S37240G 240GB SSD                       | 24        | 2.1%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 20        | 1.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 18        | 1.57%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 15        | 1.31%   |
| Phison E12 NVMe Controller 2TB                        | 15        | 1.31%   |
| Samsung SSD 850 EVO 500GB                             | 12        | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB                        | 10        | 0.87%   |
| Samsung SSD 860 EVO 500GB                             | 10        | 0.87%   |
| Intel SSD 660P Series 1024GB                          | 10        | 0.87%   |
| Crucial CT1000MX500SSD1 1TB                           | 10        | 0.87%   |
| Samsung SSD 860 EVO 1TB                               | 9         | 0.79%   |
| Samsung SSD 850 EVO 250GB                             | 9         | 0.79%   |
| Samsung SSD 980 1TB                                   | 8         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 8         | 0.7%    |
| Toshiba DT01ACA100 1TB                                | 7         | 0.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 7         | 0.61%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 7         | 0.61%   |
| Crucial CT1000BX500SSD1 1TB                           | 7         | 0.61%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 6         | 0.52%   |
| Unknown MMC Card  64GB                                | 6         | 0.52%   |
| Toshiba MQ04ABF100 1TB                                | 6         | 0.52%   |
| Toshiba DT01ACA200 2TB                                | 6         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 6         | 0.52%   |
| Kingston SA400S37480G 480GB SSD                       | 6         | 0.52%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 5         | 0.44%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 5         | 0.44%   |
| Toshiba HDWD110 1TB                                   | 5         | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                        | 5         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 0.44%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB         | 5         | 0.44%   |
| Intel SSDPEKNU512GZ 512GB                             | 5         | 0.44%   |
| Crucial CT500MX500SSD1 500GB                          | 5         | 0.44%   |
| Crucial CT240BX500SSD1 240GB                          | 5         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 4         | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 4         | 0.35%   |
| SK hynix BC511 512GB                                  | 4         | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                        | 4         | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                        | 4         | 0.35%   |
| Sandisk WD Black SN850 1TB                            | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 130    | 34.02%  |
| WDC                 | 93        | 129    | 31.96%  |
| Toshiba             | 46        | 54     | 15.81%  |
| Hitachi             | 14        | 19     | 4.81%   |
| Samsung Electronics | 12        | 21     | 4.12%   |
| HGST                | 12        | 15     | 4.12%   |
| Apple               | 6         | 6      | 2.06%   |
| USB3.0              | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |
| SSK                 | 1         | 1      | 0.34%   |
| SABRENT             | 1         | 2      | 0.34%   |
| Maxtor              | 1         | 1      | 0.34%   |
| JMicron Technology  | 1         | 1      | 0.34%   |
| HGST HTS            | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| Fujitsu             | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 89        | 117    | 24.86%  |
| Kingston            | 52        | 58     | 14.53%  |
| Crucial             | 51        | 70     | 14.25%  |
| WDC                 | 27        | 31     | 7.54%   |
| SanDisk             | 22        | 25     | 6.15%   |
| PNY                 | 11        | 18     | 3.07%   |
| China               | 10        | 10     | 2.79%   |
| SPCC                | 9         | 11     | 2.51%   |
| Team                | 7         | 7      | 1.96%   |
| Micron Technology   | 7         | 8      | 1.96%   |
| A-DATA Technology   | 7         | 7      | 1.96%   |
| Intel               | 6         | 6      | 1.68%   |
| Toshiba             | 5         | 6      | 1.4%    |
| SK hynix            | 4         | 4      | 1.12%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.84%   |
| Apacer              | 3         | 3      | 0.84%   |
| Verbatim            | 2         | 2      | 0.56%   |
| Transcend           | 2         | 2      | 0.56%   |
| Seagate             | 2         | 2      | 0.56%   |
| OCZ                 | 2         | 2      | 0.56%   |
| Mushkin             | 2         | 2      | 0.56%   |
| LITEON              | 2         | 2      | 0.56%   |
| KingFast            | 2         | 2      | 0.56%   |
| Intenso             | 2         | 2      | 0.56%   |
| Drevo               | 2         | 2      | 0.56%   |
| Apple               | 2         | 2      | 0.56%   |
| XSTAR               | 1         | 1      | 0.28%   |
| WDC WDS             | 1         | 1      | 0.28%   |
| USB3.0              | 1         | 1      | 0.28%   |
| SuperSSpeed         | 1         | 1      | 0.28%   |
| SD                  | 1         | 1      | 0.28%   |
| SCY                 | 1         | 1      | 0.28%   |
| Ramsta              | 1         | 1      | 0.28%   |
| Ramaxel Technology  | 1         | 1      | 0.28%   |
| PNY CS90            | 1         | 1      | 0.28%   |
| Plextor             | 1         | 1      | 0.28%   |
| Patriot             | 1         | 1      | 0.28%   |
| ORTIAL              | 1         | 1      | 0.28%   |
| Neo                 | 1         | 1      | 0.28%   |
| MyDigitalSSD        | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 316       | 449    | 36.07%  |
| SSD     | 289       | 430    | 32.99%  |
| HDD     | 242       | 384    | 27.63%  |
| Unknown | 17        | 20     | 1.94%   |
| MMC     | 12        | 14     | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 387       | 784    | 51.46%  |
| NVMe | 314       | 447    | 41.76%  |
| SAS  | 39        | 52     | 5.19%   |
| MMC  | 12        | 14     | 1.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 260       | 381    | 44.91%  |
| 0.51-1.0   | 191       | 258    | 32.99%  |
| 1.01-2.0   | 77        | 109    | 13.3%   |
| 3.01-4.0   | 22        | 28     | 3.8%    |
| 4.01-10.0  | 16        | 22     | 2.76%   |
| 2.01-3.0   | 9         | 11     | 1.55%   |
| 10.01-20.0 | 4         | 5      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 119       | 20.8%   |
| 251-500        | 106       | 18.53%  |
| 101-250        | 102       | 17.83%  |
| 1001-2000      | 101       | 17.66%  |
| More than 3000 | 64        | 11.19%  |
| 2001-3000      | 29        | 5.07%   |
| 21-50          | 17        | 2.97%   |
| Unknown        | 17        | 2.97%   |
| 51-100         | 14        | 2.45%   |
| 1-20           | 3         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 147       | 25%     |
| 1-20           | 110       | 18.71%  |
| 101-250        | 81        | 13.78%  |
| 51-100         | 70        | 11.9%   |
| 251-500        | 64        | 10.88%  |
| 501-1000       | 45        | 7.65%   |
| 1001-2000      | 25        | 4.25%   |
| Unknown        | 17        | 2.89%   |
| More than 3000 | 16        | 2.72%   |
| 2001-3000      | 13        | 2.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 11.76%  |
| WDC WD30EZRX-00DC0B0 3TB                       | 1         | 1      | 5.88%   |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 5.88%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 5.88%   |
| WDC WD10EACS-00D6B0 1TB                        | 1         | 1      | 5.88%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 5.88%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 5.88%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.88%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 5.88%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5.88%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 35.29%  |
| Seagate             | 3         | 3      | 17.65%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Ramsta              | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 46.15%  |
| Seagate             | 3         | 3      | 23.08%  |
| HGST                | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 76.47%  |
| SSD  | 3         | 3      | 17.65%  |
| NVMe | 1         | 1      | 5.88%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 461       | 1053   | 77.87%  |
| Works    | 115       | 226    | 19.43%  |
| Malfunc  | 15        | 17     | 2.53%   |
| Limited  | 1         | 1      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 293       | 33.07%  |
| AMD                            | 206       | 23.25%  |
| Samsung Electronics            | 109       | 12.3%   |
| SanDisk                        | 58        | 6.55%   |
| Phison Electronics             | 36        | 4.06%   |
| Kingston Technology Company    | 32        | 3.61%   |
| Micron/Crucial Technology      | 30        | 3.39%   |
| ASMedia Technology             | 26        | 2.93%   |
| SK hynix                       | 19        | 2.14%   |
| Micron Technology              | 13        | 1.47%   |
| KIOXIA                         | 9         | 1.02%   |
| Silicon Motion                 | 8         | 0.9%    |
| Nvidia                         | 7         | 0.79%   |
| Realtek Semiconductor          | 6         | 0.68%   |
| ADATA Technology               | 6         | 0.68%   |
| Toshiba America Info Systems   | 5         | 0.56%   |
| Marvell Technology Group       | 5         | 0.56%   |
| Union Memory (Shenzhen)        | 2         | 0.23%   |
| Solidigm                       | 2         | 0.23%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.23%   |
| JMicron Technology             | 2         | 0.23%   |
| Broadcom / LSI                 | 2         | 0.23%   |
| Solid State Storage Technology | 1         | 0.11%   |
| Silicon Image                  | 1         | 0.11%   |
| Shenzhen Longsys Electronics   | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |
| Netac Technology               | 1         | 0.11%   |
| LSI Logic / Symbios Logic      | 1         | 0.11%   |
| Biwin Storage Technology       | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 139       | 14.15%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 48        | 4.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 41        | 4.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 34        | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 27        | 2.75%   |
| Samsung NVMe SSD Controller 980                                                | 25        | 2.55%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 25        | 2.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 24        | 2.44%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 20        | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 1.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 16        | 1.63%   |
| Phison E12 NVMe Controller                                                     | 16        | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14        | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 14        | 1.43%   |
| Intel SSD 660P Series                                                          | 12        | 1.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 1.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 11        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 1.12%   |
| Kingston Company A2000 NVMe SSD                                                | 10        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 10        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10        | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 0.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                              | 7         | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 7         | 0.71%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 7         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 448       | 53.59%  |
| NVMe | 314       | 37.56%  |
| RAID | 45        | 5.38%   |
| IDE  | 25        | 2.99%   |
| SAS  | 4         | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 322       | 57.4%   |
| AMD    | 239       | 42.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 13        | 2.31%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 12        | 2.13%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 11        | 1.95%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 10        | 1.78%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 8         | 1.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 8         | 1.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 1.24%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 7         | 1.24%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 7         | 1.24%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 6         | 1.07%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 6         | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 6         | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 5         | 0.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 5         | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 5         | 0.89%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 5         | 0.89%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.89%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 5         | 0.89%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 5         | 0.89%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 5         | 0.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 5         | 0.89%   |
| AMD FX-8350 Eight-Core Processor        | 5         | 0.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 4         | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 4         | 0.71%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 4         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 0.71%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 4         | 0.71%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 4         | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 4         | 0.71%   |
| Intel 12th Gen Core i7-12700H           | 4         | 0.71%   |
| Intel 12th Gen Core i5-12600K           | 4         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 0.71%   |
| AMD Ryzen 9 7900X 12-Core Processor     | 4         | 0.71%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 4         | 0.71%   |
| AMD Ryzen 5 7600X 6-Core Processor      | 4         | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 4         | 0.71%   |
| AMD Ryzen 5 5500                        | 4         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 97        | 17.26%  |
| AMD Ryzen 5             | 96        | 17.08%  |
| Intel Core i5           | 95        | 16.9%   |
| AMD Ryzen 7             | 61        | 10.85%  |
| Other                   | 58        | 10.32%  |
| AMD Ryzen 9             | 36        | 6.41%   |
| Intel Core i3           | 27        | 4.8%    |
| AMD FX                  | 12        | 2.14%   |
| Intel Celeron           | 11        | 1.96%   |
| Intel Xeon              | 10        | 1.78%   |
| Intel Core 2 Duo        | 7         | 1.25%   |
| Intel Pentium           | 6         | 1.07%   |
| AMD Ryzen 3             | 6         | 1.07%   |
| Intel Core i9           | 5         | 0.89%   |
| Intel Atom              | 4         | 0.71%   |
| AMD A6                  | 4         | 0.71%   |
| AMD A10                 | 4         | 0.71%   |
| AMD Phenom II X6        | 3         | 0.53%   |
| AMD A4                  | 3         | 0.53%   |
| Intel Pentium Dual-Core | 2         | 0.36%   |
| AMD Ryzen Threadripper  | 2         | 0.36%   |
| Intel Core m7           | 1         | 0.18%   |
| Intel Core 2 Extreme    | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD Ryzen 3 PRO         | 1         | 0.18%   |
| AMD PRO A10             | 1         | 0.18%   |
| AMD Phenom II X4        | 1         | 0.18%   |
| AMD Phenom              | 1         | 0.18%   |
| AMD G                   | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD Athlon X4           | 1         | 0.18%   |
| AMD Athlon II X2        | 1         | 0.18%   |
| AMD Athlon Dual Core    | 1         | 0.18%   |
| AMD A8                  | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 165       | 29.36%  |
| 6      | 135       | 24.02%  |
| 2      | 110       | 19.57%  |
| 8      | 84        | 14.95%  |
| 12     | 22        | 3.91%   |
| 16     | 17        | 3.02%   |
| 10     | 11        | 1.96%   |
| 14     | 8         | 1.42%   |
| 3      | 4         | 0.71%   |
| 1      | 4         | 0.71%   |
| 24     | 2         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 560       | 99.82%  |
| 2      | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 467       | 83.1%   |
| 1      | 95        | 16.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 561       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 22.55%  |
| 0x08701021 | 28        | 4.9%    |
| 0x0a50000c | 21        | 3.67%   |
| 0x306c3    | 20        | 3.5%    |
| 0x306a9    | 20        | 3.5%    |
| 0x0a601203 | 17        | 2.97%   |
| 0x206a7    | 16        | 2.8%    |
| 0x906ea    | 15        | 2.62%   |
| 0x0a201016 | 14        | 2.45%   |
| 0x08108109 | 14        | 2.45%   |
| 0x906e9    | 13        | 2.27%   |
| 0x40651    | 13        | 2.27%   |
| 0x0a50000d | 13        | 2.27%   |
| 0xa0652    | 12        | 2.1%    |
| 0x0800820d | 12        | 2.1%    |
| 0x506e3    | 9         | 1.57%   |
| 0x0a20120a | 9         | 1.57%   |
| 0x906a3    | 8         | 1.4%    |
| 0x806c1    | 8         | 1.4%    |
| 0x08608103 | 8         | 1.4%    |
| 0x06000822 | 8         | 1.4%    |
| 0x806e9    | 7         | 1.22%   |
| 0xa0655    | 6         | 1.05%   |
| 0x90672    | 6         | 1.05%   |
| 0x0a201205 | 6         | 1.05%   |
| 0x08600104 | 6         | 1.05%   |
| 0x906ed    | 5         | 0.87%   |
| 0x806d1    | 5         | 0.87%   |
| 0x406e3    | 5         | 0.87%   |
| 0x0a404102 | 5         | 0.87%   |
| 0x0a201204 | 5         | 0.87%   |
| 0x08600106 | 5         | 0.87%   |
| 0x08001138 | 5         | 0.87%   |
| 0xa0653    | 4         | 0.7%    |
| 0x906ec    | 4         | 0.7%    |
| 0x206d7    | 4         | 0.7%    |
| 0x1067a    | 4         | 0.7%    |
| 0x06003106 | 4         | 0.7%    |
| 0x806ea    | 3         | 0.52%   |
| 0x30678    | 3         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 77        | 13.7%   |
| KabyLake         | 70        | 12.46%  |
| Haswell          | 56        | 9.96%   |
| Zen 2            | 47        | 8.36%   |
| Unknown          | 39        | 6.94%   |
| Zen+             | 33        | 5.87%   |
| Alderlake Hybrid | 29        | 5.16%   |
| CometLake        | 27        | 4.8%    |
| SandyBridge      | 26        | 4.63%   |
| Skylake          | 25        | 4.45%   |
| IvyBridge        | 25        | 4.45%   |
| Icelake          | 15        | 2.67%   |
| TigerLake        | 14        | 2.49%   |
| Piledriver       | 14        | 2.49%   |
| Zen              | 11        | 1.96%   |
| Penryn           | 10        | 1.78%   |
| Silvermont       | 8         | 1.42%   |
| K10              | 6         | 1.07%   |
| Excavator        | 5         | 0.89%   |
| Broadwell        | 5         | 0.89%   |
| Steamroller      | 4         | 0.71%   |
| Goldmont plus    | 4         | 0.71%   |
| Westmere         | 2         | 0.36%   |
| Bobcat           | 2         | 0.36%   |
| Puma             | 1         | 0.18%   |
| Nehalem          | 1         | 0.18%   |
| K8 Hammer        | 1         | 0.18%   |
| Jaguar           | 1         | 0.18%   |
| Goldmont         | 1         | 0.18%   |
| Core             | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |
| Bonnell          | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 258       | 35.98%  |
| AMD    | 240       | 33.47%  |
| Intel  | 219       | 30.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 31        | 4.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 23        | 3.1%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 22        | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 18        | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 17        | 2.29%   |
| AMD Raphael                                                                 | 17        | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 16        | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 13        | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 13        | 1.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13        | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 13        | 1.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13        | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 11        | 1.48%   |
| Intel HD Graphics 530                                                       | 11        | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 11        | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 10        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10        | 1.35%   |
| Intel HD Graphics 620                                                       | 10        | 1.35%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10        | 1.35%   |
| AMD Renoir                                                                  | 9         | 1.21%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 8         | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 8         | 1.08%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 1.08%   |
| AMD Rembrandt [Radeon 680M]                                                 | 8         | 1.08%   |
| AMD Lucienne                                                                | 8         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 7         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 7         | 0.94%   |
| Nvidia TU117M                                                               | 7         | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7         | 0.94%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 7         | 0.94%   |
| Intel HD Graphics 630                                                       | 6         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5         | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5         | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5         | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 0.67%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5         | 0.67%   |
| Intel UHD Graphics 620                                                      | 5         | 0.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 5         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 170       | 30.25%  |
| 1 x Nvidia         | 135       | 24.02%  |
| 1 x Intel          | 100       | 17.79%  |
| Intel + Nvidia     | 86        | 15.3%   |
| AMD + Nvidia       | 33        | 5.87%   |
| 2 x AMD            | 20        | 3.56%   |
| Intel + AMD        | 14        | 2.49%   |
| 2 x Nvidia         | 2         | 0.36%   |
| Other              | 1         | 0.18%   |
| Intel + 2 x Nvidia | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 353       | 62.48%  |
| Proprietary | 201       | 35.58%  |
| Unknown     | 11        | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 250       | 43.94%  |
| 7.01-8.0   | 74        | 13.01%  |
| 0.01-0.5   | 57        | 10.02%  |
| 1.01-2.0   | 52        | 9.14%   |
| 8.01-16.0  | 46        | 8.08%   |
| 3.01-4.0   | 37        | 6.5%    |
| 0.51-1.0   | 28        | 4.92%   |
| 5.01-6.0   | 13        | 2.28%   |
| 16.01-24.0 | 8         | 1.41%   |
| 2.01-3.0   | 4         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 93        | 14.2%   |
| AU Optronics            | 60        | 9.16%   |
| Goldstar                | 46        | 7.02%   |
| BOE                     | 42        | 6.41%   |
| Chimei Innolux          | 37        | 5.65%   |
| LG Display              | 35        | 5.34%   |
| Dell                    | 33        | 5.04%   |
| Acer                    | 31        | 4.73%   |
| Ancor Communications    | 23        | 3.51%   |
| BenQ                    | 21        | 3.21%   |
| Hewlett-Packard         | 19        | 2.9%    |
| AOC                     | 19        | 2.9%    |
| ASUSTek Computer        | 18        | 2.75%   |
| MSI                     | 15        | 2.29%   |
| Apple                   | 15        | 2.29%   |
| PANDA                   | 13        | 1.98%   |
| ViewSonic               | 12        | 1.83%   |
| Sony                    | 10        | 1.53%   |
| Sharp                   | 10        | 1.53%   |
| Vizio                   | 9         | 1.37%   |
| Lenovo                  | 9         | 1.37%   |
| Philips                 | 8         | 1.22%   |
| Gigabyte Technology     | 8         | 1.22%   |
| InfoVision              | 6         | 0.92%   |
| Toshiba                 | 4         | 0.61%   |
| Sceptre Tech            | 4         | 0.61%   |
| Chi Mei Optoelectronics | 4         | 0.61%   |
| Unknown                 | 3         | 0.46%   |
| Iiyama                  | 3         | 0.46%   |
| Eizo                    | 3         | 0.46%   |
| Valve                   | 2         | 0.31%   |
| Panasonic               | 2         | 0.31%   |
| NEC Computers           | 2         | 0.31%   |
| Insignia                | 2         | 0.31%   |
| HUAWEI                  | 2         | 0.31%   |
| CSO                     | 2         | 0.31%   |
| Corsair                 | 2         | 0.31%   |
| ___                     | 1         | 0.15%   |
| Yeyian                  | 1         | 0.15%   |
| XUE                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 5         | 0.74%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 5         | 0.74%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 4         | 0.59%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 3         | 0.44%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 3         | 0.44%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch           | 3         | 0.44%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 3         | 0.44%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 0.44%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 3         | 0.44%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 600x340mm 27.2-inch         | 3         | 0.44%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                     | 3         | 0.44%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                     | 3         | 0.44%   |
| Vizio M50Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 2         | 0.29%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 2         | 0.29%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 2         | 0.29%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.29%   |
| Toshiba TV TSB0108 1360x768 930x523mm 42.0-inch                        | 2         | 0.29%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.29%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 2         | 0.29%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 2         | 0.29%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                        | 2         | 0.29%   |
| LG Display LCD Monitor LGD0738 1920x1080 344x194mm 15.5-inch           | 2         | 0.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 2         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 0.29%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2         | 0.29%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch           | 2         | 0.29%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch               | 2         | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.29%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                     | 2         | 0.29%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 0.29%   |
| Dell U2715H DELD067 2560x1440 600x340mm 27.2-inch                      | 2         | 0.29%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 284       | 45.88%  |
| 2560x1440 (QHD)    | 77        | 12.44%  |
| 3840x2160 (4K)     | 65        | 10.5%   |
| 1366x768 (WXGA)    | 56        | 9.05%   |
| 1680x1050 (WSXGA+) | 16        | 2.58%   |
| 3440x1440          | 14        | 2.26%   |
| 1920x1200 (WUXGA)  | 14        | 2.26%   |
| 1440x900 (WXGA+)   | 12        | 1.94%   |
| 2560x1600          | 10        | 1.62%   |
| 1360x768           | 9         | 1.45%   |
| 2560x1080          | 8         | 1.29%   |
| 1600x900 (HD+)     | 8         | 1.29%   |
| 1280x1024 (SXGA)   | 8         | 1.29%   |
| 2880x1800          | 5         | 0.81%   |
| 1920x540           | 5         | 0.81%   |
| 1280x800 (WXGA)    | 4         | 0.65%   |
| 2240x1400          | 3         | 0.48%   |
| 3840x1600          | 2         | 0.32%   |
| 3840x1080          | 2         | 0.32%   |
| 2736x1824          | 2         | 0.32%   |
| 2288x1287          | 2         | 0.32%   |
| Unknown            | 2         | 0.32%   |
| 800x1280           | 1         | 0.16%   |
| 5760x1080          | 1         | 0.16%   |
| 3840x2560          | 1         | 0.16%   |
| 3840x2400          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2520x1680          | 1         | 0.16%   |
| 2048x1152          | 1         | 0.16%   |
| 1600x2560          | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 137       | 20.92%  |
| 27      | 90        | 13.74%  |
| 24      | 45        | 6.87%   |
| 31      | 44        | 6.72%   |
| 23      | 44        | 6.72%   |
| 13      | 36        | 5.5%    |
| 17      | 33        | 5.04%   |
| 21      | 30        | 4.58%   |
| 14      | 23        | 3.51%   |
| 34      | 17        | 2.6%    |
| 84      | 12        | 1.83%   |
| Unknown | 12        | 1.83%   |
| 20      | 11        | 1.68%   |
| 22      | 10        | 1.53%   |
| 18      | 10        | 1.53%   |
| 19      | 9         | 1.37%   |
| 16      | 9         | 1.37%   |
| 72      | 8         | 1.22%   |
| 48      | 7         | 1.07%   |
| 32      | 6         | 0.92%   |
| 26      | 6         | 0.92%   |
| 29      | 5         | 0.76%   |
| 42      | 4         | 0.61%   |
| 12      | 4         | 0.61%   |
| 52      | 3         | 0.46%   |
| 49      | 3         | 0.46%   |
| 40      | 3         | 0.46%   |
| 142     | 2         | 0.31%   |
| 69      | 2         | 0.31%   |
| 60      | 2         | 0.31%   |
| 55      | 2         | 0.31%   |
| 38      | 2         | 0.31%   |
| 37      | 2         | 0.31%   |
| 35      | 2         | 0.31%   |
| 33      | 2         | 0.31%   |
| 28      | 2         | 0.31%   |
| 25      | 2         | 0.31%   |
| 11      | 2         | 0.31%   |
| 86      | 1         | 0.15%   |
| 85      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 190       | 29.73%  |
| 501-600        | 164       | 25.67%  |
| 401-500        | 69        | 10.8%   |
| 601-700        | 58        | 9.08%   |
| 351-400        | 31        | 4.85%   |
| 201-300        | 26        | 4.07%   |
| 701-800        | 24        | 3.76%   |
| 1501-2000      | 24        | 3.76%   |
| 1001-1500      | 22        | 3.44%   |
| Unknown        | 12        | 1.88%   |
| 801-900        | 10        | 1.56%   |
| 901-1000       | 5         | 0.78%   |
| More than 2000 | 2         | 0.31%   |
| 101-200        | 1         | 0.16%   |
| 1-100          | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 439       | 78.82%  |
| 16/10   | 66        | 11.85%  |
| 21/9    | 23        | 4.13%   |
| 5/4     | 8         | 1.44%   |
| 3/2     | 5         | 0.9%    |
| 4/3     | 4         | 0.72%   |
| 32/9    | 4         | 0.72%   |
| Unknown | 3         | 0.54%   |
| 1.00    | 2         | 0.36%   |
| 1.96    | 1         | 0.18%   |
| 0.67    | 1         | 0.18%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 138       | 21.43%  |
| 201-250        | 105       | 16.3%   |
| 301-350        | 96        | 14.91%  |
| 351-500        | 71        | 11.02%  |
| 81-90          | 46        | 7.14%   |
| More than 1000 | 42        | 6.52%   |
| 151-200        | 32        | 4.97%   |
| 121-130        | 25        | 3.88%   |
| 501-1000       | 18        | 2.8%    |
| 251-300        | 15        | 2.33%   |
| 71-80          | 13        | 2.02%   |
| Unknown        | 12        | 1.86%   |
| 141-150        | 11        | 1.71%   |
| 111-120        | 8         | 1.24%   |
| 61-70          | 3         | 0.47%   |
| 131-140        | 3         | 0.47%   |
| 51-60          | 2         | 0.31%   |
| 1-40           | 2         | 0.31%   |
| 41-50          | 1         | 0.16%   |
| 91-100         | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 221       | 35.53%  |
| 121-160       | 155       | 24.92%  |
| 101-120       | 140       | 22.51%  |
| 161-240       | 43        | 6.91%   |
| 1-50          | 36        | 5.79%   |
| More than 240 | 15        | 2.41%   |
| Unknown       | 12        | 1.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 411       | 72.49%  |
| 2     | 114       | 20.11%  |
| 3     | 21        | 3.7%    |
| 0     | 19        | 3.35%   |
| 4     | 2         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 332       | 38.16%  |
| Intel                           | 295       | 33.91%  |
| Qualcomm Atheros                | 54        | 6.21%   |
| Broadcom                        | 40        | 4.6%    |
| MediaTek                        | 37        | 4.25%   |
| TP-Link                         | 18        | 2.07%   |
| Microsoft                       | 10        | 1.15%   |
| Ralink Technology               | 8         | 0.92%   |
| Broadcom Limited                | 7         | 0.8%    |
| Xiaomi                          | 5         | 0.57%   |
| ASIX Electronics                | 5         | 0.57%   |
| Samsung Electronics             | 4         | 0.46%   |
| Ralink                          | 4         | 0.46%   |
| Qualcomm                        | 4         | 0.46%   |
| Nvidia                          | 4         | 0.46%   |
| Qualcomm Atheros Communications | 3         | 0.34%   |
| Motorola PCS                    | 3         | 0.34%   |
| Marvell Technology Group        | 3         | 0.34%   |
| ASUSTek Computer                | 3         | 0.34%   |
| Aquantia                        | 3         | 0.34%   |
| Sierra Wireless                 | 2         | 0.23%   |
| Oculus VR                       | 2         | 0.23%   |
| NetGear                         | 2         | 0.23%   |
| Lenovo                          | 2         | 0.23%   |
| Hewlett-Packard                 | 2         | 0.23%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.11%   |
| Wacom                           | 1         | 0.11%   |
| T & A Mobile Phones             | 1         | 0.11%   |
| Panasonic (Matsushita)          | 1         | 0.11%   |
| Padix (Rockfire)                | 1         | 0.11%   |
| OPPO Electronics                | 1         | 0.11%   |
| Microchip Technology            | 1         | 0.11%   |
| Mellanox Technologies           | 1         | 0.11%   |
| Loupedeck                       | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| JMicron Technology              | 1         | 0.11%   |
| ICS Advent                      | 1         | 0.11%   |
| Holtek Semiconductor            | 1         | 0.11%   |
| Google                          | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 237       | 23.42%  |
| Realtek RTL8125 2.5GbE Controller                                 | 51        | 5.04%   |
| Intel Wi-Fi 6 AX200                                               | 46        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 33        | 3.26%   |
| Intel I211 Gigabit Network Connection                             | 29        | 2.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 21        | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 13        | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 1.28%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 1.09%   |
| Intel Wireless 8260                                               | 11        | 1.09%   |
| Intel Wireless 7265                                               | 11        | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10        | 0.99%   |
| Intel Wireless 7260                                               | 10        | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.79%   |
| Intel Wireless-AC 9260                                            | 8         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 8         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.59%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 6         | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 220       | 47.93%  |
| Realtek Semiconductor           | 73        | 15.9%   |
| MediaTek                        | 37        | 8.06%   |
| Qualcomm Atheros                | 35        | 7.63%   |
| Broadcom                        | 34        | 7.41%   |
| TP-Link                         | 17        | 3.7%    |
| Microsoft                       | 10        | 2.18%   |
| Ralink Technology               | 8         | 1.74%   |
| Broadcom Limited                | 5         | 1.09%   |
| Ralink                          | 4         | 0.87%   |
| Qualcomm Atheros Communications | 3         | 0.65%   |
| ASUSTek Computer                | 3         | 0.65%   |
| Sierra Wireless                 | 2         | 0.44%   |
| NetGear                         | 2         | 0.44%   |
| Wacom                           | 1         | 0.22%   |
| Panasonic (Matsushita)          | 1         | 0.22%   |
| Marvell Technology Group        | 1         | 0.22%   |
| Linksys                         | 1         | 0.22%   |
| D-Link System                   | 1         | 0.22%   |
| D-Link                          | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 46        | 10%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 21        | 4.57%   |
| Intel Comet Lake PCH CNVi WiFi                                | 15        | 3.26%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 15        | 3.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 13        | 2.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 13        | 2.83%   |
| Intel Wireless 8265 / 8275                                    | 13        | 2.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 13        | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 12        | 2.61%   |
| Intel Wireless 8260                                           | 11        | 2.39%   |
| Intel Wireless 7265                                           | 11        | 2.39%   |
| Intel Wi-Fi 6 AX201                                           | 11        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 10        | 2.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 10        | 2.17%   |
| Intel Wireless 7260                                           | 10        | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 9         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 9         | 1.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 1.74%   |
| Intel Wireless-AC 9260                                        | 8         | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 8         | 1.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 8         | 1.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 7         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 7         | 1.52%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 6         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                 | 6         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 5         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 5         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 5         | 1.09%   |
| TP-Link 802.11ac NIC                                          | 4         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4         | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 4         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 4         | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                           | 4         | 0.87%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 4         | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3         | 0.65%   |
| Realtek 802.11ac NIC                                          | 3         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 304       | 57.25%  |
| Intel                      | 146       | 27.5%   |
| Qualcomm Atheros           | 23        | 4.33%   |
| Broadcom                   | 14        | 2.64%   |
| Xiaomi                     | 5         | 0.94%   |
| ASIX Electronics           | 5         | 0.94%   |
| Qualcomm                   | 4         | 0.75%   |
| Nvidia                     | 4         | 0.75%   |
| Motorola PCS               | 3         | 0.56%   |
| Aquantia                   | 3         | 0.56%   |
| Samsung Electronics        | 2         | 0.38%   |
| Marvell Technology Group   | 2         | 0.38%   |
| Lenovo                     | 2         | 0.38%   |
| Hewlett-Packard            | 2         | 0.38%   |
| Broadcom Limited           | 2         | 0.38%   |
| ZTE WCDMA Technologies MSM | 1         | 0.19%   |
| TP-Link                    | 1         | 0.19%   |
| T & A Mobile Phones        | 1         | 0.19%   |
| OPPO Electronics           | 1         | 0.19%   |
| Mellanox Technologies      | 1         | 0.19%   |
| MediaTek                   | 1         | 0.19%   |
| JMicron Technology         | 1         | 0.19%   |
| ICS Advent                 | 1         | 0.19%   |
| Google                     | 1         | 0.19%   |
| American Megatrends        | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 237       | 43.65%  |
| Realtek RTL8125 2.5GbE Controller                                   | 51        | 9.39%   |
| Intel Ethernet Controller I225-V                                    | 33        | 6.08%   |
| Intel I211 Gigabit Network Connection                               | 29        | 5.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 11        | 2.03%   |
| Intel Ethernet Connection (7) I219-V                                | 11        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 1.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 8         | 1.47%   |
| Intel Ethernet Connection (2) I219-V                                | 7         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 6         | 1.1%    |
| Intel Ethernet Connection I217-V                                    | 6         | 1.1%    |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.1%    |
| Intel Ethernet Connection (2) I218-V                                | 5         | 0.92%   |
| Intel 82579V Gigabit Network Connection                             | 5         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 5         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 4         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 4         | 0.74%   |
| Intel Ethernet Connection I218-LM                                   | 4         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                               | 4         | 0.74%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 4         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                       | 4         | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 3         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 3         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3         | 0.55%   |
| Nvidia MCP79 Ethernet                                               | 3         | 0.55%   |
| Motorola PCS XT1032                                                 | 3         | 0.55%   |
| Intel I210 Gigabit Network Connection                               | 3         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                               | 3         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                               | 3         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                               | 3         | 0.55%   |
| Intel Ethernet Connection (14) I219-V                               | 3         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                               | 2         | 0.37%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 2         | 0.37%   |
| Intel Ethernet Connection (17) I219-V                               | 2         | 0.37%   |
| Intel Ethernet Connection (12) I219-V                               | 2         | 0.37%   |
| HP lt4120 Snapdragon X5 LTE                                         | 2         | 0.37%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.37%   |
| ZTE WCDMA MSM Android                                               | 1         | 0.18%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 499       | 53.03%  |
| WiFi     | 433       | 46.01%  |
| Modem    | 6         | 0.64%   |
| Unknown  | 3         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 308       | 51.59%  |
| WiFi     | 289       | 48.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 305       | 54.27%  |
| 1     | 233       | 41.46%  |
| 3     | 16        | 2.85%   |
| 0     | 6         | 1.07%   |
| 6     | 1         | 0.18%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 388       | 68.67%  |
| Yes  | 177       | 31.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 211       | 51.84%  |
| Realtek Semiconductor           | 36        | 8.85%   |
| Cambridge Silicon Radio         | 32        | 7.86%   |
| Qualcomm Atheros Communications | 17        | 4.18%   |
| MediaTek                        | 16        | 3.93%   |
| Foxconn / Hon Hai               | 15        | 3.69%   |
| Broadcom                        | 15        | 3.69%   |
| Apple                           | 15        | 3.69%   |
| IMC Networks                    | 12        | 2.95%   |
| Lite-On Technology              | 11        | 2.7%    |
| TP-Link                         | 6         | 1.47%   |
| ASUSTek Computer                | 6         | 1.47%   |
| Edimax Technology               | 3         | 0.74%   |
| Ralink                          | 2         | 0.49%   |
| Actions                         | 2         | 0.49%   |
| Toshiba                         | 1         | 0.25%   |
| Realtek                         | 1         | 0.25%   |
| Marvell Semiconductor           | 1         | 0.25%   |
| Integrated System Solution      | 1         | 0.25%   |
| Foxconn International           | 1         | 0.25%   |
| Dynex                           | 1         | 0.25%   |
| Dell                            | 1         | 0.25%   |
| Unknown                         | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 54        | 13.27%  |
| Intel AX200 Bluetooth                                   | 47        | 11.55%  |
| Intel AX201 Bluetooth                                   | 35        | 8.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 32        | 7.86%   |
| Realtek Bluetooth Radio                                 | 28        | 6.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 21        | 5.16%   |
| Intel AX210 Bluetooth                                   | 20        | 4.91%   |
| Intel Bluetooth Device                                  | 17        | 4.18%   |
| MediaTek Wireless_Device                                | 16        | 3.93%   |
| Intel Wireless-AC 3168 Bluetooth                        | 8         | 1.97%   |
| Apple Bluetooth Host Controller                         | 8         | 1.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 7         | 1.72%   |
| TP-Link UB500 Adapter                                   | 6         | 1.47%   |
| Realtek  Bluetooth 4.2 Adapter                          | 5         | 1.23%   |
| Qualcomm Atheros  Bluetooth Device                      | 5         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 5         | 1.23%   |
| IMC Networks Wireless_Device                            | 5         | 1.23%   |
| IMC Networks Bluetooth Radio                            | 5         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter            | 5         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                       | 4         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 4         | 0.98%   |
| ASUS ASUS USB-BT500                                     | 4         | 0.98%   |
| Apple Bluetooth USB Host Controller                     | 4         | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 3         | 0.74%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 3         | 0.74%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 2         | 0.49%   |
| Ralink RT3290 Bluetooth                                 | 2         | 0.49%   |
| Lite-On Wireless_Device                                 | 2         | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 2         | 0.49%   |
| Lite-On Bluetooth Radio                                 | 2         | 0.49%   |
| Lite-On Bluetooth Device                                | 2         | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.49%   |
| IMC Networks Bluetooth Device                           | 2         | 0.49%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.49%   |
| Broadcom HP Portable Bumble Bee                         | 2         | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                    | 2         | 0.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 2         | 0.49%   |
| Actions general adapter                                 | 2         | 0.49%   |
| Toshiba Askey Bluetooth Module                          | 1         | 0.25%   |
| Realtek RTL8821A Bluetooth                              | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 314       | 31.56%  |
| AMD                        | 289       | 29.05%  |
| Nvidia                     | 215       | 21.61%  |
| C-Media Electronics        | 26        | 2.61%   |
| Logitech                   | 20        | 2.01%   |
| ASUSTek Computer           | 12        | 1.21%   |
| Razer USA                  | 10        | 1.01%   |
| Kingston Technology        | 9         | 0.9%    |
| SteelSeries ApS            | 7         | 0.7%    |
| Creative Labs              | 6         | 0.6%    |
| Texas Instruments          | 5         | 0.5%    |
| Plantronics                | 5         | 0.5%    |
| Creative Technology        | 5         | 0.5%    |
| Samson Technologies        | 4         | 0.4%    |
| Realtek Semiconductor      | 4         | 0.4%    |
| JMTek                      | 4         | 0.4%    |
| Corsair                    | 4         | 0.4%    |
| Blue Microphones           | 4         | 0.4%    |
| Sony                       | 3         | 0.3%    |
| Micro Star International   | 3         | 0.3%    |
| GN Netcom                  | 3         | 0.3%    |
| Audio-Technica             | 3         | 0.3%    |
| TTGK Technology            | 2         | 0.2%    |
| Tenx Technology            | 2         | 0.2%    |
| SAVITECH                   | 2         | 0.2%    |
| Native Instruments         | 2         | 0.2%    |
| Lenovo                     | 2         | 0.2%    |
| Hewlett-Packard            | 2         | 0.2%    |
| Generalplus Technology     | 2         | 0.2%    |
| Focusrite-Novation         | 2         | 0.2%    |
| Asahi Kasei Microsystems   | 2         | 0.2%    |
| VIA Technologies           | 1         | 0.1%    |
| Turtle Beach               | 1         | 0.1%    |
| Trust                      | 1         | 0.1%    |
| Scarlett                   | 1         | 0.1%    |
| Samsung Electronics        | 1         | 0.1%    |
| ROCCAT                     | 1         | 0.1%    |
| PreSonus Audio Electronics | 1         | 0.1%    |
| Positive Grid              | 1         | 0.1%    |
| Ploopy                     | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 95        | 7.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 72        | 5.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 57        | 4.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 41        | 3.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 2.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 2.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 24        | 1.99%   |
| Nvidia GA104 High Definition Audio Controller                              | 23        | 1.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 23        | 1.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 23        | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 1.66%   |
| Nvidia GA106 High Definition Audio Controller                              | 19        | 1.57%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 15        | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 14        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 13        | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                              | 13        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 12        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 0.99%   |
| AMD Navi 10 HDMI Audio                                                     | 12        | 0.99%   |
| AMD FCH Azalia Controller                                                  | 12        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.91%   |
| ASUSTek Computer USB Audio                                                 | 11        | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11        | 0.91%   |
| Intel 200 Series PCH HD Audio                                              | 9         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8         | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 23.42%  |
| SK hynix            | 22        | 13.92%  |
| Micron Technology   | 20        | 12.66%  |
| Kingston            | 16        | 10.13%  |
| Corsair             | 15        | 9.49%   |
| G.Skill             | 14        | 8.86%   |
| Crucial             | 8         | 5.06%   |
| Team                | 7         | 4.43%   |
| Unknown             | 6         | 3.8%    |
| A-DATA Technology   | 3         | 1.9%    |
| Unknown (ABCD)      | 2         | 1.27%   |
| Transcend           | 1         | 0.63%   |
| Ramaxel Technology  | 1         | 0.63%   |
| Nanya Technology    | 1         | 0.63%   |
| Hewlett-Packard     | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| Asgard              | 1         | 0.63%   |
| AMD                 | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.8%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 2         | 1.2%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.2%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1.2%    |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 1.2%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.2%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 1.2%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 2         | 1.2%    |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 2         | 1.2%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 1.2%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 2         | 1.2%    |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s             | 2         | 1.2%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.2%    |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.6%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.6%    |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 0.6%    |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 0.6%    |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s                 | 1         | 0.6%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.6%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.6%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.6%    |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.6%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 82        | 62.12%  |
| DDR3    | 26        | 19.7%   |
| DDR5    | 10        | 7.58%   |
| LPDDR4  | 9         | 6.82%   |
| Unknown | 2         | 1.52%   |
| SDRAM   | 1         | 0.76%   |
| LPDDR5  | 1         | 0.76%   |
| DDR2    | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 47.37%  |
| DIMM         | 59        | 44.36%  |
| Row Of Chips | 11        | 8.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 47.18%  |
| 16384 | 28        | 19.72%  |
| 4096  | 23        | 16.2%   |
| 32768 | 13        | 9.15%   |
| 2048  | 10        | 7.04%   |
| 1024  | 1         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 34        | 24.11%  |
| 1600  | 18        | 12.77%  |
| 2667  | 16        | 11.35%  |
| 2400  | 10        | 7.09%   |
| 3600  | 9         | 6.38%   |
| 1333  | 6         | 4.26%   |
| 4800  | 5         | 3.55%   |
| 4267  | 4         | 2.84%   |
| 5600  | 3         | 2.13%   |
| 3800  | 3         | 2.13%   |
| 3733  | 3         | 2.13%   |
| 3266  | 3         | 2.13%   |
| 6400  | 2         | 1.42%   |
| 3866  | 2         | 1.42%   |
| 3466  | 2         | 1.42%   |
| 2933  | 2         | 1.42%   |
| 2133  | 2         | 1.42%   |
| 1066  | 2         | 1.42%   |
| 6000  | 1         | 0.71%   |
| 5200  | 1         | 0.71%   |
| 4266  | 1         | 0.71%   |
| 3933  | 1         | 0.71%   |
| 3534  | 1         | 0.71%   |
| 3533  | 1         | 0.71%   |
| 3400  | 1         | 0.71%   |
| 3334  | 1         | 0.71%   |
| 3333  | 1         | 0.71%   |
| 3100  | 1         | 0.71%   |
| 3000  | 1         | 0.71%   |
| 2800  | 1         | 0.71%   |
| 1334  | 1         | 0.71%   |
| 975   | 1         | 0.71%   |
| 800   | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 36.36%  |
| Canon               | 3         | 27.27%  |
| STMicroelectronics  | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Hewlett-Packard     | 1         | 9.09%   |
| Dell                | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 9.09%   |
| Samsung Composite Device                                  | 1         | 9.09%   |
| HP DeskJet Plus 4100 series                               | 1         | 9.09%   |
| Dell 1130 Laser Printer                                   | 1         | 9.09%   |
| Canon TS700 series                                        | 1         | 9.09%   |
| Canon TR4500 series                                       | 1         | 9.09%   |
| Canon PIXMA MX370 Series                                  | 1         | 9.09%   |
| Brother MFC-L2710DN series                                | 1         | 9.09%   |
| Brother MFC-J460DW                                        | 1         | 9.09%   |
| Brother HL-L2370DW series                                 | 1         | 9.09%   |
| Brother DCP-1510                                          | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 2400c              | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 51        | 17.47%  |
| IMC Networks                           | 31        | 10.62%  |
| Logitech                               | 25        | 8.56%   |
| Apple                                  | 23        | 7.88%   |
| Realtek Semiconductor                  | 16        | 5.48%   |
| Sunplus Innovation Technology          | 15        | 5.14%   |
| Microdia                               | 13        | 4.45%   |
| Quanta                                 | 12        | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.11%   |
| Syntek                                 | 11        | 3.77%   |
| Bison Electronics                      | 11        | 3.77%   |
| Microsoft                              | 7         | 2.4%    |
| Luxvisions Innotech Limited            | 7         | 2.4%    |
| Lite-On Technology                     | 7         | 2.4%    |
| Suyin                                  | 5         | 1.71%   |
| SunplusIT                              | 5         | 1.71%   |
| Sonix Technology                       | 5         | 1.71%   |
| Acer                                   | 5         | 1.71%   |
| Silicon Motion                         | 3         | 1.03%   |
| Samsung Electronics                    | 3         | 1.03%   |
| MacroSilicon                           | 2         | 0.68%   |
| Intel                                  | 2         | 0.68%   |
| Hewlett-Packard                        | 2         | 0.68%   |
| ARC International                      | 2         | 0.68%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| YGTek                                  | 1         | 0.34%   |
| WCM_USB                                | 1         | 0.34%   |
| Tobii Technology AB                    | 1         | 0.34%   |
| Shine-optics                           | 1         | 0.34%   |
| Razer USA                              | 1         | 0.34%   |
| Owon                                   | 1         | 0.34%   |
| lihappe8                               | 1         | 0.34%   |
| Lenovo                                 | 1         | 0.34%   |
| KYE Systems (Mouse Systems)            | 1         | 0.34%   |
| Importek                               | 1         | 0.34%   |
| Goodong Industry                       | 1         | 0.34%   |
| Generalplus Technology                 | 1         | 0.34%   |
| EVGA                                   | 1         | 0.34%   |
| Cubeternet                             | 1         | 0.34%   |
| ANYKA                                  | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 14        | 4.75%   |
| Chicony Integrated Camera                           | 14        | 4.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 10        | 3.39%   |
| Syntek Integrated Camera                            | 8         | 2.71%   |
| Realtek Integrated_Webcam_HD                        | 8         | 2.71%   |
| Logitech C922 Pro Stream Webcam                     | 8         | 2.71%   |
| IMC Networks Integrated Camera                      | 7         | 2.37%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 2.03%   |
| Chicony HD WebCam                                   | 6         | 2.03%   |
| Logitech HD Pro Webcam C920                         | 5         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.69%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.36%   |
| Logitech Webcam C270                                | 4         | 1.36%   |
| Bison Integrated Camera                             | 4         | 1.36%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 1.36%   |
| Apple FaceTime HD Camera                            | 4         | 1.36%   |
| Apple Built-in iSight                               | 4         | 1.36%   |
| Sunplus HD WebCam                                   | 3         | 1.02%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 1.02%   |
| Realtek USB Camera                                  | 3         | 1.02%   |
| Quanta HD User Facing                               | 3         | 1.02%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.02%   |
| Lite-On HP HD Webcam                                | 3         | 1.02%   |
| Chicony USB 2.0 Camera                              | 3         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.02%   |
| Chicony HP Truevision HD                            | 3         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.02%   |
| Syntek EasyCamera                                   | 2         | 0.68%   |
| SunplusIT 720p HD Camera                            | 2         | 0.68%   |
| Sunplus FULL HD webcam                              | 2         | 0.68%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.68%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 0.68%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.68%   |
| Quanta HD Webcam                                    | 2         | 0.68%   |
| Microsoft LifeCam Cinema                            | 2         | 0.68%   |
| Microdia Integrated Camera                          | 2         | 0.68%   |
| MacroSilicon USB Video                              | 2         | 0.68%   |
| Logitech StreamCam                                  | 2         | 0.68%   |
| Logitech QuickCam Pro 9000                          | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 16        | 39.02%  |
| Synaptics                          | 10        | 24.39%  |
| Shenzhen Goodix Technology         | 8         | 19.51%  |
| Elan Microelectronics              | 5         | 12.2%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 4.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 19.51%  |
| Shenzhen Goodix  FingerPrint Device                             | 4         | 9.76%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 9.76%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 7.32%   |
| Elan ELAN:Fingerprint                                           | 3         | 7.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 4.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 4.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 4.88%   |
| Elan ELAN:ARM-M4                                                | 2         | 4.88%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 2.44%   |
| Synaptics WBDI Device                                           | 1         | 2.44%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.44%   |
| Synaptics UWP WBDI                                              | 1         | 2.44%   |
| Synaptics  WBDI                                                 | 1         | 2.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.44%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 50%     |
| Broadcom              | 3         | 37.5%   |
| Realtek Semiconductor | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 50%     |
| Broadcom 5880                                                                | 2         | 25%     |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 428       | 75.22%  |
| 1     | 118       | 20.74%  |
| 2     | 20        | 3.51%   |
| 3     | 3         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 46        | 27.71%  |
| Net/wireless             | 41        | 24.7%   |
| Fingerprint reader       | 40        | 24.1%   |
| Multimedia controller    | 26        | 15.66%  |
| Unassigned class         | 3         | 1.81%   |
| Bluetooth                | 3         | 1.81%   |
| Communication controller | 2         | 1.2%    |
| Camera                   | 2         | 1.2%    |
| Sound                    | 1         | 0.6%    |
| Modem                    | 1         | 0.6%    |
| Chipcard                 | 1         | 0.6%    |

