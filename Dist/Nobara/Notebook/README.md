Nobara - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 351

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| Dell          | Precision 7740              | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| System76      | Gazelle                     | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| HP            | Notebook                    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| Dell          | Latitude E5470              | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E5470              | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| ASUSTek       | GL502VSK                    | [5f455e693f](https://linux-hardware.org/?probe=5f455e693f) | Oct 24, 2023 |
| Dell          | Inspiron 7375               | [451317bd25](https://linux-hardware.org/?probe=451317bd25) | Oct 22, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [fa46708f8f](https://linux-hardware.org/?probe=fa46708f8f) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| MSI           | GT72S 6QE                   | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Toshiba       | Satellite C55D-C            | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| Acer          | Aspire A315-42              | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| Acer          | Aspire A315-41              | [85d999063f](https://linux-hardware.org/?probe=85d999063f) | Oct 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| MSI           | Modern 14 B5M               | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Acer          | Nitro AN515-42              | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| Dell          | G5 5505                     | [787ccf4559](https://linux-hardware.org/?probe=787ccf4559) | Sep 25, 2023 |
| GPU Compan... | GWNR71517                   | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| HP            | Victus by Gaming Laptop ... | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| Dell          | G3 3579                     | [eff563e086](https://linux-hardware.org/?probe=eff563e086) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [4c854cc233](https://linux-hardware.org/?probe=4c854cc233) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [cd2fb41835](https://linux-hardware.org/?probe=cd2fb41835) | Sep 15, 2023 |
| Dell          | Latitude E6440              | [591c479a8d](https://linux-hardware.org/?probe=591c479a8d) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| ASUSTek       | G751JM                      | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| Acer          | Nitro AN515-56              | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| Acer          | Nitro AN515-56              | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| Infinix       | INBOOK X2 GEN11             | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | [9c5e7cc1fb](https://linux-hardware.org/?probe=9c5e7cc1fb) | Aug 16, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f9d07e4f97](https://linux-hardware.org/?probe=f9d07e4f97) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ecbc3827d1](https://linux-hardware.org/?probe=ecbc3827d1) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | [101c521941](https://linux-hardware.org/?probe=101c521941) | Aug 08, 2023 |
| Micro Comp... | NUCXI7                      | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| Dell          | Inspiron 15 3520            | [49cbe32874](https://linux-hardware.org/?probe=49cbe32874) | Jul 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 15 3520            | [319cb6659d](https://linux-hardware.org/?probe=319cb6659d) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| Toshiba       | Satellite S55t-C            | [be8777b248](https://linux-hardware.org/?probe=be8777b248) | Jul 17, 2023 |
| Acer          | Predator PH315-52           | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| Acer          | Nitro AN515-54              | [ac55f32c4e](https://linux-hardware.org/?probe=ac55f32c4e) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| MSI           | GT70 2PE                    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| Dell          | G7 7790                     | [a6dd0d72f7](https://linux-hardware.org/?probe=a6dd0d72f7) | Jul 06, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [afa2978397](https://linux-hardware.org/?probe=afa2978397) | Jul 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9472db0bf4](https://linux-hardware.org/?probe=9472db0bf4) | Jul 04, 2023 |
| Dell          | Latitude E5440              | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| ASUSTek       | X541SA                      | [be7a8d9ce0](https://linux-hardware.org/?probe=be7a8d9ce0) | Jul 02, 2023 |
| Dell          | G7 7790                     | [6345fbbe32](https://linux-hardware.org/?probe=6345fbbe32) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [bbd5ba331d](https://linux-hardware.org/?probe=bbd5ba331d) | Jun 30, 2023 |
| Lenovo        | G50-80 80L0                 | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| Apple         | MacBookPro8,3               | [4846eae54f](https://linux-hardware.org/?probe=4846eae54f) | Jun 28, 2023 |
| Apple         | MacBookPro8,3               | [f5c922b6d3](https://linux-hardware.org/?probe=f5c922b6d3) | Jun 28, 2023 |
| Dell          | Inspiron 15 3520            | [c77b479e22](https://linux-hardware.org/?probe=c77b479e22) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [5e67041129](https://linux-hardware.org/?probe=5e67041129) | Jun 26, 2023 |
| Google        | Blooglet                    | [88fae074d1](https://linux-hardware.org/?probe=88fae074d1) | Jun 25, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [305e202fd3](https://linux-hardware.org/?probe=305e202fd3) | Jun 22, 2023 |
| MSI           | GT70 2OC/2OD                | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | [f7a3caaef1](https://linux-hardware.org/?probe=f7a3caaef1) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | [f11d231c6a](https://linux-hardware.org/?probe=f11d231c6a) | Jun 20, 2023 |
| Timi          | A30                         | [34d77f385a](https://linux-hardware.org/?probe=34d77f385a) | Jun 19, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | [10cf405f89](https://linux-hardware.org/?probe=10cf405f89) | Jun 17, 2023 |
| Dell          | Precision 7510              | [cbbfdafd46](https://linux-hardware.org/?probe=cbbfdafd46) | Jun 17, 2023 |
| Google        | Blooglet                    | [80ce635393](https://linux-hardware.org/?probe=80ce635393) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Infinix       | INBook X1 Pro               | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASUSTek       | X550JK                      | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| Alienware     | m17 R5 AMD                  | [f5eeb72c4d](https://linux-hardware.org/?probe=f5eeb72c4d) | May 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0cb4af5367](https://linux-hardware.org/?probe=0cb4af5367) | May 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S06Q0... | [e54e204b28](https://linux-hardware.org/?probe=e54e204b28) | May 29, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | [9496942a44](https://linux-hardware.org/?probe=9496942a44) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| Packard Be... | EasyNote LS11HR             | [a5df8ea9d7](https://linux-hardware.org/?probe=a5df8ea9d7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [1e648e8f50](https://linux-hardware.org/?probe=1e648e8f50) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| HP            | Pavilion 15                 | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| HP            | Laptop 17-ca1xxx            | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Samsung       | 535U3C                      | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| HP            | Unknown                     | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| Unknown       | ACB20                       | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Lenovo        | Unknown                     | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Acer          | Nitro AN515-52              | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Dell          | Vostro 3400                 | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| Dell          | Vostro 3400                 | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | ZBook 17                    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| HP            | EliteBook Revolve 810 G1    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | Katana GF76 11UD            | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Medion        | GUARDIAN X10                | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | EliteBook 8570p             | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dynabook      | PORTEGE X30L-K              | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASUSTek       | GL753VD                     | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | 2000                        | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Apple         | MacBookPro5,5               | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| HP            | 2000                        | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Dell          | Inspiron 3542               | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| Gateway       | NE56R                       | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Alienware     | Area-51m R2 A00             | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | TP500LA                     | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| Dell          | G15 5511                    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| Notebook      | P7xxDM2(-G)                 | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Apple         | MacBookPro14,2              | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Razer         | Blade                       | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Nobara 36 | 113       | 41.09%  |
| Nobara 37 | 105       | 38.18%  |
| Nobara 38 | 57        | 20.73%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 270       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 19        | 6.71%   |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 5.65%   |
| 6.1.11-201.fsync.fc37.x86_64  | 12        | 4.24%   |
| 6.0.14-201.fsync.fc36.x86_64  | 11        | 3.89%   |
| 6.1.4-203.fsync.fc37.x86_64   | 10        | 3.53%   |
| 6.3.12-204.fsync.fc38.x86_64  | 9         | 3.18%   |
| 6.2.14-300.fsync.fc37.x86_64  | 9         | 3.18%   |
| 6.1.14-201.fsync.fc37.x86_64  | 9         | 3.18%   |
| 6.5.6-200.fsync.fc38.x86_64   | 7         | 2.47%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 2.47%   |
| 6.0.16-301.fsync.fc37.x86_64  | 7         | 2.47%   |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 2.47%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 2.47%   |
| 6.4.10-202.fsync.fc38.x86_64  | 6         | 2.12%   |
| 6.3.5-201.fsync.fc37.x86_64   | 6         | 2.12%   |
| 6.2.11-201.fsync.fc37.x86_64  | 6         | 2.12%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 2.12%   |
| 6.3.7-200.fsync.fc37.x86_64   | 5         | 1.77%   |
| 6.3.10-200.fsync.fc38.x86_64  | 5         | 1.77%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 1.77%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 1.77%   |
| 6.5.5-202.fsync.fc38.x86_64   | 4         | 1.41%   |
| 6.5.5-200.fsync.fc38.x86_64   | 4         | 1.41%   |
| 6.2.6-201.fsync.fc37.x86_64   | 4         | 1.41%   |
| 6.2.12-200.fsync.fc37.x86_64  | 4         | 1.41%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4         | 1.41%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 1.41%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 1.41%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 1.41%   |
| 6.5.9-201.fsync.fc38.x86_64   | 3         | 1.06%   |
| 6.5.9-200.fsync.fc38.x86_64   | 3         | 1.06%   |
| 6.5.3-200.fsync.fc38.x86_64   | 3         | 1.06%   |
| 6.3.12-205.fsync.fc38.x86_64  | 3         | 1.06%   |
| 6.3.10-200.fsync.fc37.x86_64  | 3         | 1.06%   |
| 6.2.8-200.fsync.fc37.x86_64   | 3         | 1.06%   |
| 6.2.10-200.fsync.fc37.x86_64  | 3         | 1.06%   |
| 6.1.6-203.fsync.fc37.x86_64   | 3         | 1.06%   |
| 6.0.9-202.fc36.x86_64         | 3         | 1.06%   |
| 6.0.9-201.fc36.x86_64         | 3         | 1.06%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 19        | 6.71%   |
| 6.3.12  | 16        | 5.65%   |
| 5.19.14 | 16        | 5.65%   |
| 6.1.11  | 12        | 4.24%   |
| 6.0.14  | 11        | 3.89%   |
| 6.1.4   | 10        | 3.53%   |
| 6.4.10  | 9         | 3.18%   |
| 6.3.10  | 9         | 3.18%   |
| 6.2.14  | 9         | 3.18%   |
| 6.1.14  | 9         | 3.18%   |
| 6.5.5   | 8         | 2.83%   |
| 5.19.7  | 8         | 2.83%   |
| 6.5.6   | 7         | 2.47%   |
| 6.2.11  | 7         | 2.47%   |
| 6.1.9   | 7         | 2.47%   |
| 6.1.6   | 7         | 2.47%   |
| 6.0.7   | 7         | 2.47%   |
| 6.0.16  | 7         | 2.47%   |
| 5.19.9  | 7         | 2.47%   |
| 6.5.9   | 6         | 2.12%   |
| 6.3.5   | 6         | 2.12%   |
| 6.1.8   | 6         | 2.12%   |
| 6.0.9   | 6         | 2.12%   |
| 6.3.7   | 5         | 1.77%   |
| 6.0.5   | 5         | 1.77%   |
| 5.19.12 | 5         | 1.77%   |
| 6.5.3   | 4         | 1.41%   |
| 6.2.6   | 4         | 1.41%   |
| 6.2.12  | 4         | 1.41%   |
| 5.19.8  | 4         | 1.41%   |
| 5.19.16 | 4         | 1.41%   |
| 5.19.11 | 4         | 1.41%   |
| 6.2.8   | 3         | 1.06%   |
| 6.2.10  | 3         | 1.06%   |
| 5.18.16 | 3         | 1.06%   |
| 5.18.13 | 3         | 1.06%   |
| 6.5.8   | 2         | 0.71%   |
| 6.3.9   | 2         | 0.71%   |
| 6.0.8   | 2         | 0.71%   |
| 5.19.4  | 2         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 59        | 21.15%  |
| 5.19    | 54        | 19.35%  |
| 6.1     | 51        | 18.28%  |
| 6.3     | 38        | 13.62%  |
| 6.2     | 29        | 10.39%  |
| 6.5     | 28        | 10.04%  |
| 6.4     | 10        | 3.58%   |
| 5.18    | 10        | 3.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 270       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GNOME    | 195       | 71.69%  |
| KDE5     | 69        | 25.37%  |
| Unknown  | 7         | 2.57%   |
| Hyprland | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 219       | 80.51%  |
| X11     | 48        | 17.65%  |
| Unknown | 4         | 1.47%   |
| Tty     | 1         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 210       | 76.64%  |
| GDM     | 44        | 16.06%  |
| SDDM    | 18        | 6.57%   |
| LightDM | 2         | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 144       | 53.14%  |
| en_GB   | 15        | 5.54%   |
| es_ES   | 12        | 4.43%   |
| de_DE   | 10        | 3.69%   |
| ru_RU   | 8         | 2.95%   |
| pt_BR   | 8         | 2.95%   |
| pl_PL   | 8         | 2.95%   |
| it_IT   | 8         | 2.95%   |
| es_MX   | 7         | 2.58%   |
| en_NZ   | 5         | 1.85%   |
| en_IN   | 5         | 1.85%   |
| en_CA   | 5         | 1.85%   |
| es_AR   | 4         | 1.48%   |
| tr_TR   | 3         | 1.11%   |
| pt_PT   | 3         | 1.11%   |
| fr_FR   | 3         | 1.11%   |
| en_AU   | 3         | 1.11%   |
| Unknown | 3         | 1.11%   |
| zh_TW   | 2         | 0.74%   |
| uk_UA   | 1         | 0.37%   |
| sv_SE   | 1         | 0.37%   |
| ro_RO   | 1         | 0.37%   |
| nb_NO   | 1         | 0.37%   |
| hu_HU   | 1         | 0.37%   |
| hr_HR   | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| es_US   | 1         | 0.37%   |
| es_CR   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| es_CL   | 1         | 0.37%   |
| en_ZA   | 1         | 0.37%   |
| en_PH   | 1         | 0.37%   |
| en_IE   | 1         | 0.37%   |
| de_AT   | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 230       | 84.25%  |
| BIOS | 43        | 15.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 205       | 75.37%  |
| Ext4  | 66        | 24.26%  |
| Xfs   | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 205       | 74.55%  |
| GPT     | 67        | 24.36%  |
| MBR     | 3         | 1.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 251       | 92.28%  |
| Yes       | 21        | 7.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 235       | 87.04%  |
| Yes       | 35        | 12.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 63        | 23.33%  |
| ASUSTek Computer                 | 49        | 18.15%  |
| Hewlett-Packard                  | 40        | 14.81%  |
| Dell                             | 29        | 10.74%  |
| Acer                             | 20        | 7.41%   |
| MSI                              | 13        | 4.81%   |
| Apple                            | 11        | 4.07%   |
| Toshiba                          | 5         | 1.85%   |
| Samsung Electronics              | 3         | 1.11%   |
| Gigabyte Technology              | 3         | 1.11%   |
| Positivo                         | 2         | 0.74%   |
| Notebook                         | 2         | 0.74%   |
| Infinix                          | 2         | 0.74%   |
| Alienware                        | 2         | 0.74%   |
| Valve                            | 1         | 0.37%   |
| Timi                             | 1         | 0.37%   |
| System76                         | 1         | 0.37%   |
| Sony                             | 1         | 0.37%   |
| Schenker                         | 1         | 0.37%   |
| Razer                            | 1         | 0.37%   |
| Packard Bell                     | 1         | 0.37%   |
| ONE-NETBOOK TECHNOLOGY           | 1         | 0.37%   |
| ONE-NETBOOK                      | 1         | 0.37%   |
| Monster                          | 1         | 0.37%   |
| Micro Electronics                | 1         | 0.37%   |
| Micro Computer (HK) Tech Limited | 1         | 0.37%   |
| Medion                           | 1         | 0.37%   |
| Intel                            | 1         | 0.37%   |
| HUAWEI                           | 1         | 0.37%   |
| GPU Company                      | 1         | 0.37%   |
| Google                           | 1         | 0.37%   |
| GEO                              | 1         | 0.37%   |
| Gateway                          | 1         | 0.37%   |
| Fujitsu                          | 1         | 0.37%   |
| EVOO                             | 1         | 0.37%   |
| Dynabook                         | 1         | 0.37%   |
| Coradir                          | 1         | 0.37%   |
| Casper                           | 1         | 0.37%   |
| ASRock                           | 1         | 0.37%   |
| Unknown                          | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 1.85%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 1.11%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 3         | 1.11%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 3         | 1.11%   |
| Lenovo Legion 5 15ARH05H 82B1       | 2         | 0.74%   |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.74%   |
| Lenovo Legion 5 15ACH6H 82JU        | 2         | 0.74%   |
| Lenovo IdeaPad C340-14API 81N6      | 2         | 0.74%   |
| Lenovo IdeaPad 5 15ITL05 82FG       | 2         | 0.74%   |
| HP ZBook 15u G3                     | 2         | 0.74%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.74%   |
| HP Pavilion 15                      | 2         | 0.74%   |
| Dell Vostro 3400                    | 2         | 0.74%   |
| Dell Inspiron 3542                  | 2         | 0.74%   |
| Dell Inspiron 15 3520               | 2         | 0.74%   |
| Dell G5 5505                        | 2         | 0.74%   |
| ASUS ROG Strix G713RM_G713RM        | 2         | 0.74%   |
| ASUS ROG Strix G512LW_G512LW        | 2         | 0.74%   |
| Apple MacBookPro8,3                 | 2         | 0.74%   |
| Apple MacBookPro8,1                 | 2         | 0.74%   |
| Acer Nitro AN515-52                 | 2         | 0.74%   |
| Acer Nitro AN515-42                 | 2         | 0.74%   |
| Acer Aspire VX5-591G                | 2         | 0.74%   |
| Acer Aspire A315-42                 | 2         | 0.74%   |
| Valve Jupiter                       | 1         | 0.37%   |
| Toshiba TECRA A50-A                 | 1         | 0.37%   |
| Toshiba Satellite S55t-C            | 1         | 0.37%   |
| Toshiba Satellite L850              | 1         | 0.37%   |
| Toshiba Satellite L650              | 1         | 0.37%   |
| Toshiba Satellite C55D-C            | 1         | 0.37%   |
| Timi A30                            | 1         | 0.37%   |
| System76 Gazelle                    | 1         | 0.37%   |
| Sony SVF1521N6EW                    | 1         | 0.37%   |
| Schenker XMG NEO (M19, RTX 2070)    | 1         | 0.37%   |
| Samsung R520/R522/R620              | 1         | 0.37%   |
| Samsung 535U3C                      | 1         | 0.37%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.37%   |
| Razer Blade                         | 1         | 0.37%   |
| Positivo N1250                      | 1         | 0.37%   |
| Positivo N1240                      | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 22        | 8.15%   |
| Lenovo ThinkPad   | 16        | 5.93%   |
| ASUS ROG          | 16        | 5.93%   |
| Lenovo Legion     | 13        | 4.81%   |
| HP Pavilion       | 11        | 4.07%   |
| ASUS VivoBook     | 11        | 4.07%   |
| Acer Aspire       | 8         | 2.96%   |
| Dell Inspiron     | 7         | 2.59%   |
| Acer Nitro        | 7         | 2.59%   |
| HP EliteBook      | 6         | 2.22%   |
| HP ZBook          | 5         | 1.85%   |
| Dell Precision    | 5         | 1.85%   |
| Unknown           | 5         | 1.85%   |
| Toshiba Satellite | 4         | 1.48%   |
| Dell Vostro       | 4         | 1.48%   |
| Dell Latitude     | 4         | 1.48%   |
| ASUS ASUS         | 4         | 1.48%   |
| Apple MacBookPro8 | 4         | 1.48%   |
| HP Laptop         | 3         | 1.11%   |
| HP ENVY           | 3         | 1.11%   |
| ASUS TUF          | 3         | 1.11%   |
| MSI GT70          | 2         | 0.74%   |
| Lenovo G580       | 2         | 0.74%   |
| Infinix INBook    | 2         | 0.74%   |
| HP ProBook        | 2         | 0.74%   |
| HP OMEN           | 2         | 0.74%   |
| Gigabyte AERO     | 2         | 0.74%   |
| Dell G5           | 2         | 0.74%   |
| Dell G3           | 2         | 0.74%   |
| Dell G15          | 2         | 0.74%   |
| Apple MacBookPro5 | 2         | 0.74%   |
| Acer Swift        | 2         | 0.74%   |
| Valve Jupiter     | 1         | 0.37%   |
| Toshiba TECRA     | 1         | 0.37%   |
| Timi A30          | 1         | 0.37%   |
| System76 Gazelle  | 1         | 0.37%   |
| Sony SVF1521N6EW  | 1         | 0.37%   |
| Schenker XMG      | 1         | 0.37%   |
| Samsung R520      | 1         | 0.37%   |
| Samsung 535U3C    | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 44        | 16.3%   |
| 2020 | 32        | 11.85%  |
| 2018 | 29        | 10.74%  |
| 2022 | 28        | 10.37%  |
| 2019 | 26        | 9.63%   |
| 2014 | 19        | 7.04%   |
| 2013 | 17        | 6.3%    |
| 2016 | 14        | 5.19%   |
| 2015 | 13        | 4.81%   |
| 2017 | 12        | 4.44%   |
| 2012 | 11        | 4.07%   |
| 2023 | 9         | 3.33%   |
| 2011 | 5         | 1.85%   |
| 2010 | 5         | 1.85%   |
| 2009 | 5         | 1.85%   |
| 2008 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 270       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 270       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 268       | 99.26%  |
| Yes  | 2         | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 68        | 25%     |
| 8.01-16.0   | 66        | 24.26%  |
| 16.01-24.0  | 63        | 23.16%  |
| 32.01-64.0  | 31        | 11.4%   |
| 3.01-4.0    | 30        | 11.03%  |
| 24.01-32.0  | 10        | 3.68%   |
| 64.01-256.0 | 2         | 0.74%   |
| 1.01-2.0    | 2         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 123       | 44.24%  |
| 2.01-3.0   | 65        | 23.38%  |
| 3.01-4.0   | 56        | 20.14%  |
| 8.01-16.0  | 23        | 8.27%   |
| 1.01-2.0   | 10        | 3.6%    |
| 16.01-24.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 187       | 68.5%   |
| 2      | 72        | 26.37%  |
| 3      | 12        | 4.4%    |
| 5      | 1         | 0.37%   |
| 4      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 218       | 80.74%  |
| Yes       | 52        | 19.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 78.97%  |
| No        | 57        | 21.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 98.52%  |
| No        | 4         | 1.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 90.37%  |
| No        | 26        | 9.63%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 77        | 28.52%  |
| Germany             | 16        | 5.93%   |
| Spain               | 14        | 5.19%   |
| Poland              | 13        | 4.81%   |
| Italy               | 10        | 3.7%    |
| Brazil              | 10        | 3.7%    |
| UK                  | 9         | 3.33%   |
| Russia              | 9         | 3.33%   |
| Mexico              | 9         | 3.33%   |
| India               | 8         | 2.96%   |
| Indonesia           | 6         | 2.22%   |
| Canada              | 6         | 2.22%   |
| Portugal            | 5         | 1.85%   |
| New Zealand         | 5         | 1.85%   |
| Turkey              | 4         | 1.48%   |
| Romania             | 4         | 1.48%   |
| Australia           | 4         | 1.48%   |
| Argentina           | 4         | 1.48%   |
| Vietnam             | 3         | 1.11%   |
| Sweden              | 3         | 1.11%   |
| Philippines         | 3         | 1.11%   |
| Malaysia            | 3         | 1.11%   |
| France              | 3         | 1.11%   |
| Colombia            | 3         | 1.11%   |
| Chile               | 3         | 1.11%   |
| Pakistan            | 2         | 0.74%   |
| Morocco             | 2         | 0.74%   |
| Finland             | 2         | 0.74%   |
| Egypt               | 2         | 0.74%   |
| Croatia             | 2         | 0.74%   |
| Austria             | 2         | 0.74%   |
| Venezuela           | 1         | 0.37%   |
| Ukraine             | 1         | 0.37%   |
| Tunisia             | 1         | 0.37%   |
| Trinidad and Tobago | 1         | 0.37%   |
| Taiwan              | 1         | 0.37%   |
| Sri Lanka           | 1         | 0.37%   |
| South Africa        | 1         | 0.37%   |
| Slovenia            | 1         | 0.37%   |
| Serbia              | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Wroclaw                 | 3         | 1.07%   |
| San Francisco           | 3         | 1.07%   |
| Madrid                  | 3         | 1.07%   |
| Kuala Lumpur            | 3         | 1.07%   |
| Auckland                | 3         | 1.07%   |
| Wasilla                 | 2         | 0.71%   |
| Warsaw                  | 2         | 0.71%   |
| Stockholm               | 2         | 0.71%   |
| Schmalkalden            | 2         | 0.71%   |
| San Jose                | 2         | 0.71%   |
| Salem                   | 2         | 0.71%   |
| Poznan                  | 2         | 0.71%   |
| Perm                    | 2         | 0.71%   |
| Panama City             | 2         | 0.71%   |
| Ochsenfurt              | 2         | 0.71%   |
| Mumbai                  | 2         | 0.71%   |
| Milano                  | 2         | 0.71%   |
| Milan                   | 2         | 0.71%   |
| Lisbon                  | 2         | 0.71%   |
| Jakarta                 | 2         | 0.71%   |
| Houston                 | 2         | 0.71%   |
| Hamburg                 | 2         | 0.71%   |
| Guadalajara             | 2         | 0.71%   |
| Fortaleza               | 2         | 0.71%   |
| Casablanca              | 2         | 0.71%   |
| Bucharest               | 2         | 0.71%   |
| Berlin                  | 2         | 0.71%   |
| Atlanta                 | 2         | 0.71%   |
| Zaragoza                | 1         | 0.36%   |
| Zamora                  | 1         | 0.36%   |
| Zadar                   | 1         | 0.36%   |
| Xalapa                  | 1         | 0.36%   |
| Wesley Chapel           | 1         | 0.36%   |
| Wellington              | 1         | 0.36%   |
| Wayne                   | 1         | 0.36%   |
| Wabrzezno               | 1         | 0.36%   |
| Vladivostok             | 1         | 0.36%   |
| Virginia Beach          | 1         | 0.36%   |
| Villefranche-sur-Saône | 1         | 0.36%   |
| Villarrica              | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 72        | 85     | 20.06%  |
| Sandisk                      | 27        | 28     | 7.52%   |
| WDC                          | 25        | 27     | 6.96%   |
| SK hynix                     | 25        | 25     | 6.96%   |
| Toshiba                      | 21        | 26     | 5.85%   |
| Seagate                      | 21        | 21     | 5.85%   |
| Kingston                     | 21        | 21     | 5.85%   |
| Intel                        | 20        | 23     | 5.57%   |
| Micron Technology            | 15        | 16     | 4.18%   |
| Crucial                      | 14        | 15     | 3.9%    |
| Unknown                      | 10        | 10     | 2.79%   |
| Phison Electronics           | 9         | 9      | 2.51%   |
| Micron/Crucial Technology    | 8         | 8      | 2.23%   |
| HGST                         | 8         | 8      | 2.23%   |
| KIOXIA                       | 7         | 7      | 1.95%   |
| China                        | 5         | 5      | 1.39%   |
| A-DATA Technology            | 5         | 5      | 1.39%   |
| Team                         | 4         | 4      | 1.11%   |
| Hitachi                      | 4         | 5      | 1.11%   |
| Apple                        | 4         | 5      | 1.11%   |
| Kingston Technology Company  | 3         | 3      | 0.84%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.56%   |
| LITEON                       | 2         | 2      | 0.56%   |
| Intenso                      | 2         | 2      | 0.56%   |
| HS-SSD-C100                  | 2         | 2      | 0.56%   |
| Unknown                      | 2         | 2      | 0.56%   |
| Wibtek                       | 1         | 1      | 0.28%   |
| V-GeN                        | 1         | 1      | 0.28%   |
| Union Memory                 | 1         | 2      | 0.28%   |
| T-FORCE                      | 1         | 1      | 0.28%   |
| SPCC                         | 1         | 1      | 0.28%   |
| Solid State Storage          | 1         | 1      | 0.28%   |
| Silicon Motion               | 1         | 1      | 0.28%   |
| SABRENT                      | 1         | 1      | 0.28%   |
| Realtek                      | 1         | 1      | 0.28%   |
| Ramsta                       | 1         | 1      | 0.28%   |
| PNY                          | 1         | 1      | 0.28%   |
| Plextor                      | 1         | 1      | 0.28%   |
| Mushkin                      | 1         | 1      | 0.28%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 13        | 3.49%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 2.15%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 7         | 1.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 7         | 1.88%   |
| Intel SSDPEKNU512GZ 512GB                           | 6         | 1.61%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 1.34%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 5         | 1.34%   |
| SK hynix BC511 512GB                                | 4         | 1.08%   |
| Samsung SSD 980 1TB                                 | 4         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 4         | 1.08%   |
| Phison PS5013 E13 NVMe Controller 256GB             | 4         | 1.08%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 4         | 1.08%   |
| Intel SSD 660P Series 1024GB                        | 4         | 1.08%   |
| Unknown MMC Card  64GB                              | 3         | 0.81%   |
| Unknown MMC Card  32GB                              | 3         | 0.81%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.81%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 3         | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB       | 3         | 0.81%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 0.81%   |
| Phison E12 NVMe Controller 1TB                      | 3         | 0.81%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 3         | 0.81%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.81%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.81%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.54%   |
| WDC WD10SPCX-24HWST1 1TB                            | 2         | 0.54%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 2         | 0.54%   |
| Unknown SD/MMC/MS PRO 16GB                          | 2         | 0.54%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 0.54%   |
| Team T253X2512G 512GB SSD                           | 2         | 0.54%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.54%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.54%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.54%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 0.54%   |
| Sandisk WD Green SN350 2TB                          | 2         | 0.54%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 21        | 21     | 30.88%  |
| WDC      | 15        | 16     | 22.06%  |
| Toshiba  | 15        | 18     | 22.06%  |
| HGST     | 8         | 8      | 11.76%  |
| Hitachi  | 4         | 5      | 5.88%   |
| Unknown  | 2         | 2      | 2.94%   |
| HGST HTS | 1         | 1      | 1.47%   |
| Fujitsu  | 1         | 1      | 1.47%   |
| Apple    | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 26     | 22.77%  |
| Kingston            | 13        | 13     | 12.87%  |
| Crucial             | 13        | 14     | 12.87%  |
| SanDisk             | 6         | 6      | 5.94%   |
| China               | 5         | 5      | 4.95%   |
| A-DATA Technology   | 5         | 5      | 4.95%   |
| WDC                 | 4         | 5      | 3.96%   |
| Team                | 4         | 4      | 3.96%   |
| SK hynix            | 4         | 4      | 3.96%   |
| Intel               | 3         | 3      | 2.97%   |
| Toshiba             | 2         | 3      | 1.98%   |
| Micron Technology   | 2         | 2      | 1.98%   |
| LITEON              | 2         | 2      | 1.98%   |
| Intenso             | 2         | 2      | 1.98%   |
| Apple               | 2         | 2      | 1.98%   |
| Wibtek              | 1         | 1      | 0.99%   |
| V-GeN               | 1         | 1      | 0.99%   |
| SPCC                | 1         | 1      | 0.99%   |
| SABRENT             | 1         | 1      | 0.99%   |
| Ramsta              | 1         | 1      | 0.99%   |
| PNY                 | 1         | 1      | 0.99%   |
| Plextor             | 1         | 1      | 0.99%   |
| Mushkin             | 1         | 1      | 0.99%   |
| Emtec               | 1         | 1      | 0.99%   |
| Dell                | 1         | 1      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 159       | 194    | 48.04%  |
| SSD     | 91        | 107    | 27.49%  |
| HDD     | 67        | 73     | 20.24%  |
| MMC     | 8         | 8      | 2.42%   |
| Unknown | 6         | 6      | 1.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 158       | 192    | 49.38%  |
| SATA | 140       | 172    | 43.75%  |
| SAS  | 14        | 16     | 4.38%   |
| MMC  | 8         | 8      | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 100    | 54.88%  |
| 0.51-1.0   | 62        | 67     | 37.8%   |
| 1.01-2.0   | 10        | 11     | 6.1%    |
| 3.01-4.0   | 2         | 2      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 76        | 27.54%  |
| 251-500        | 61        | 22.1%   |
| 101-250        | 46        | 16.67%  |
| 1001-2000      | 33        | 11.96%  |
| More than 3000 | 15        | 5.43%   |
| Unknown        | 15        | 5.43%   |
| 51-100         | 10        | 3.62%   |
| 21-50          | 9         | 3.26%   |
| 2001-3000      | 8         | 2.9%    |
| 1-20           | 3         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 76        | 27.14%  |
| 1-20           | 55        | 19.64%  |
| 101-250        | 43        | 15.36%  |
| 251-500        | 32        | 11.43%  |
| 51-100         | 28        | 10%     |
| 501-1000       | 18        | 6.43%   |
| Unknown        | 15        | 5.36%   |
| 1001-2000      | 9         | 3.21%   |
| More than 3000 | 2         | 0.71%   |
| 2001-3000      | 2         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 16.67%  |
| Ramsta SSD S800 240GB                 | 1         | 1      | 16.67%  |
| Hitachi HTS54323 320GB                | 1         | 1      | 16.67%  |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 16.67%  |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 2         | 2      | 33.33%  |
| SK hynix            | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Ramsta              | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 66.67%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 50%     |
| SSD  | 2         | 2      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Detected | 210       | 294    | 73.94%  |
| Works    | 69        | 88     | 24.3%   |
| Malfunc  | 5         | 6      | 1.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 160       | 42.55%  |
| AMD                            | 53        | 14.1%   |
| Samsung Electronics            | 51        | 13.56%  |
| Sandisk                        | 26        | 6.91%   |
| SK hynix                       | 21        | 5.59%   |
| Micron Technology              | 13        | 3.46%   |
| Kingston Technology Company    | 11        | 2.93%   |
| Phison Electronics             | 9         | 2.39%   |
| Micron/Crucial Technology      | 9         | 2.39%   |
| KIOXIA                         | 7         | 1.86%   |
| Toshiba America Info Systems   | 4         | 1.06%   |
| Nvidia                         | 3         | 0.8%    |
| Shenzhen Longsys Electronics   | 2         | 0.53%   |
| Union Memory (Shenzhen)        | 1         | 0.27%   |
| Solid State Storage Technology | 1         | 0.27%   |
| Silicon Motion                 | 1         | 0.27%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.27%   |
| Marvell Technology Group       | 1         | 0.27%   |
| Apple                          | 1         | 0.27%   |
| ADATA Technology               | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 53        | 13.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 4.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 16        | 4.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 15        | 3.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 3.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 3.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.54%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 2.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 2.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 8         | 2.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 8         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 1.78%   |
| Intel SSD 660P Series                                                          | 6         | 1.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 1.27%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 5         | 1.27%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 5         | 1.27%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.02%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.02%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 3         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 0.76%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.76%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 0.76%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 3         | 0.76%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 3         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.76%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.51%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 184       | 49.6%   |
| NVMe | 157       | 42.32%  |
| RAID | 29        | 7.82%   |
| IDE  | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 68.52%  |
| AMD    | 85        | 31.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 3.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 2.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 2.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 2.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 2.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 2.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 1.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.85%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 1.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 1.85%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 4         | 1.48%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.48%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.48%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.48%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.11%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 3         | 1.11%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.11%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 1.11%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.11%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 3         | 1.11%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 1.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.11%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.11%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.74%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.74%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.74%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 2         | 0.74%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 68        | 25.19%  |
| Intel Core i5           | 47        | 17.41%  |
| Other                   | 36        | 13.33%  |
| AMD Ryzen 5             | 35        | 12.96%  |
| AMD Ryzen 7             | 27        | 10%     |
| Intel Core i3           | 14        | 5.19%   |
| Intel Celeron           | 10        | 3.7%    |
| AMD Ryzen 9             | 9         | 3.33%   |
| Intel Pentium           | 4         | 1.48%   |
| Intel Core 2 Duo        | 4         | 1.48%   |
| AMD Ryzen 3             | 3         | 1.11%   |
| AMD A6                  | 3         | 1.11%   |
| AMD A4                  | 2         | 0.74%   |
| AMD A10                 | 2         | 0.74%   |
| Intel Pentium Dual-Core | 1         | 0.37%   |
| Intel Core 2 Extreme    | 1         | 0.37%   |
| Intel Atom              | 1         | 0.37%   |
| AMD Ryzen 5 PRO         | 1         | 0.37%   |
| AMD FX                  | 1         | 0.37%   |
| AMD E                   | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 93        | 34.32%  |
| 2      | 80        | 29.52%  |
| 6      | 43        | 15.87%  |
| 8      | 40        | 14.76%  |
| 14     | 9         | 3.32%   |
| 12     | 3         | 1.11%   |
| 10     | 2         | 0.74%   |
| 1      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 270       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 243       | 90%     |
| 1      | 27        | 10%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 270       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 28.62%  |
| 0x0a50000c | 20        | 7.25%   |
| 0xa0652    | 12        | 4.35%   |
| 0x40651    | 11        | 3.99%   |
| 0x906ea    | 8         | 2.9%    |
| 0x906a3    | 8         | 2.9%    |
| 0x306a9    | 8         | 2.9%    |
| 0x206a7    | 8         | 2.9%    |
| 0x08108109 | 8         | 2.9%    |
| 0x906e9    | 7         | 2.54%   |
| 0x806c1    | 7         | 2.54%   |
| 0x0a404102 | 7         | 2.54%   |
| 0x08608103 | 7         | 2.54%   |
| 0x08600104 | 7         | 2.54%   |
| 0x08600106 | 6         | 2.17%   |
| 0x806d1    | 5         | 1.81%   |
| 0x506e3    | 5         | 1.81%   |
| 0x306c3    | 5         | 1.81%   |
| 0x806e9    | 4         | 1.45%   |
| 0x406e3    | 4         | 1.45%   |
| 0x0a50000d | 4         | 1.45%   |
| 0x806ea    | 3         | 1.09%   |
| 0x10676    | 3         | 1.09%   |
| 0x08108102 | 3         | 1.09%   |
| 0x0810100b | 3         | 1.09%   |
| 0x08101007 | 3         | 1.09%   |
| 0x806ec    | 2         | 0.72%   |
| 0x706e5    | 2         | 0.72%   |
| 0x306d4    | 2         | 0.72%   |
| 0x30678    | 2         | 0.72%   |
| 0x1067a    | 2         | 0.72%   |
| 0x0a404101 | 2         | 0.72%   |
| 0x06006110 | 2         | 0.72%   |
| 0xa0655    | 1         | 0.36%   |
| 0x906ed    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x506c9    | 1         | 0.36%   |
| 0x30661    | 1         | 0.36%   |
| 0x20655    | 1         | 0.36%   |
| 0x20652    | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 15.93%  |
| Haswell          | 29        | 10.74%  |
| Zen 3            | 24        | 8.89%   |
| Unknown          | 19        | 7.04%   |
| Skylake          | 17        | 6.3%    |
| CometLake        | 16        | 5.93%   |
| Zen 2            | 15        | 5.56%   |
| TigerLake        | 15        | 5.56%   |
| Alderlake Hybrid | 13        | 4.81%   |
| Zen+             | 11        | 4.07%   |
| SandyBridge      | 11        | 4.07%   |
| Icelake          | 9         | 3.33%   |
| Zen              | 8         | 2.96%   |
| IvyBridge        | 8         | 2.96%   |
| Penryn           | 6         | 2.22%   |
| Silvermont       | 5         | 1.85%   |
| Goldmont plus    | 4         | 1.48%   |
| Broadwell        | 4         | 1.48%   |
| Excavator        | 3         | 1.11%   |
| Westmere         | 2         | 0.74%   |
| Puma             | 2         | 0.74%   |
| Steamroller      | 1         | 0.37%   |
| Piledriver       | 1         | 0.37%   |
| Jaguar           | 1         | 0.37%   |
| Goldmont         | 1         | 0.37%   |
| Bonnell          | 1         | 0.37%   |
| Bobcat           | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 166       | 41.19%  |
| Nvidia | 138       | 34.24%  |
| AMD    | 99        | 24.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 4.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 3.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 3.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 3.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 3.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 3.14%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 2.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 2.42%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 9         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.17%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 2.17%   |
| Intel HD Graphics 530                                                                    | 8         | 1.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 1.93%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 1.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.69%   |
| AMD Lucienne                                                                             | 7         | 1.69%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 1.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 1.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.21%   |
| Intel HD Graphics 630                                                                    | 5         | 1.21%   |
| Intel HD Graphics 620                                                                    | 5         | 1.21%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.97%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 0.97%   |
| Intel HD Graphics 5500                                                                   | 4         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 3         | 0.72%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.72%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.72%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 3         | 0.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3         | 0.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 88        | 32.59%  |
| 1 x Intel          | 62        | 22.96%  |
| 1 x AMD            | 48        | 17.78%  |
| AMD + Nvidia       | 29        | 10.74%  |
| 1 x Nvidia         | 19        | 7.04%   |
| Intel + AMD        | 13        | 4.81%   |
| 2 x AMD            | 9         | 3.33%   |
| Other              | 1         | 0.37%   |
| Intel + 2 x Nvidia | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 157       | 57.93%  |
| Proprietary | 112       | 41.33%  |
| Unknown     | 2         | 0.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 56.93%  |
| 0.01-0.5   | 47        | 17.15%  |
| 1.01-2.0   | 27        | 9.85%   |
| 0.51-1.0   | 18        | 6.57%   |
| 3.01-4.0   | 9         | 3.28%   |
| 7.01-8.0   | 7         | 2.55%   |
| 5.01-6.0   | 7         | 2.55%   |
| 8.01-16.0  | 3         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 19.02%  |
| BOE                     | 48        | 14.72%  |
| Chimei Innolux          | 44        | 13.5%   |
| LG Display              | 41        | 12.58%  |
| Samsung Electronics     | 28        | 8.59%   |
| PANDA                   | 15        | 4.6%    |
| Hewlett-Packard         | 9         | 2.76%   |
| Apple                   | 9         | 2.76%   |
| Sharp                   | 8         | 2.45%   |
| MSI                     | 6         | 1.84%   |
| Goldstar                | 6         | 1.84%   |
| Dell                    | 5         | 1.53%   |
| Chi Mei Optoelectronics | 4         | 1.23%   |
| ViewSonic               | 3         | 0.92%   |
| InfoVision              | 3         | 0.92%   |
| Acer                    | 3         | 0.92%   |
| Vizio                   | 2         | 0.61%   |
| TMX                     | 2         | 0.61%   |
| Sony                    | 2         | 0.61%   |
| Philips                 | 2         | 0.61%   |
| Lenovo                  | 2         | 0.61%   |
| HKC                     | 2         | 0.61%   |
| Eizo                    | 2         | 0.61%   |
| CSO                     | 2         | 0.61%   |
| AOC                     | 2         | 0.61%   |
| ___                     | 1         | 0.31%   |
| XUE                     | 1         | 0.31%   |
| VIE                     | 1         | 0.31%   |
| Valve                   | 1         | 0.31%   |
| Unknown                 | 1         | 0.31%   |
| SNC                     | 1         | 0.31%   |
| Ruijiang                | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| MLT                     | 1         | 0.31%   |
| GAOMON                  | 1         | 0.31%   |
| CPT                     | 1         | 0.31%   |
| BenQ                    | 1         | 0.31%   |
| ASUSTek Computer        | 1         | 0.31%   |
| Ancor Communications    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 5         | 1.53%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 4         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.23%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch     | 3         | 0.92%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 3         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 3         | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.92%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 2         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                   | 2         | 0.61%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                   | 2         | 0.61%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                           | 2         | 0.61%   |
| LG Display LCD Monitor LGD0738 1920x1080 344x194mm 15.5-inch              | 2         | 0.61%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 2         | 0.61%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                        | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch           | 2         | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.61%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                     | 2         | 0.61%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                     | 2         | 0.61%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 2         | 0.61%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 2         | 0.61%   |
| ___ LCD TV ___9000 1360x768                                               | 1         | 0.31%   |
| XUE HDMI XUE1600 1920x1200 360x190mm 16.0-inch                            | 1         | 0.31%   |
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                      | 1         | 0.31%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                      | 1         | 0.31%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch                | 1         | 0.31%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch             | 1         | 0.31%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 520x290mm 23.4-inch             | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 163       | 55.44%  |
| 1366x768 (WXGA)    | 57        | 19.39%  |
| 3840x2160 (4K)     | 13        | 4.42%   |
| 2560x1440 (QHD)    | 10        | 3.4%    |
| 2560x1600          | 9         | 3.06%   |
| 1920x1200 (WUXGA)  | 8         | 2.72%   |
| 2880x1800          | 4         | 1.36%   |
| 1440x900 (WXGA+)   | 4         | 1.36%   |
| 1280x800 (WXGA)    | 4         | 1.36%   |
| 3840x2400          | 2         | 0.68%   |
| 2560x1080          | 2         | 0.68%   |
| 2240x1400          | 2         | 0.68%   |
| 1680x1050 (WSXGA+) | 2         | 0.68%   |
| 1600x900 (HD+)     | 2         | 0.68%   |
| 1360x768           | 2         | 0.68%   |
| 800x1280           | 1         | 0.34%   |
| 3456x2160          | 1         | 0.34%   |
| 3440x1440          | 1         | 0.34%   |
| 3200x2000          | 1         | 0.34%   |
| 3200x1800 (QHD+)   | 1         | 0.34%   |
| 2520x1680          | 1         | 0.34%   |
| 1600x2560          | 1         | 0.34%   |
| 1280x960           | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |
| 1280x1024 (SXGA)   | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 153       | 47.08%  |
| 17      | 33        | 10.15%  |
| 13      | 31        | 9.54%   |
| 14      | 24        | 7.38%   |
| 23      | 14        | 4.31%   |
| 27      | 12        | 3.69%   |
| 16      | 11        | 3.38%   |
| 31      | 10        | 3.08%   |
| 24      | 9         | 2.77%   |
| 34      | 3         | 0.92%   |
| 18      | 3         | 0.92%   |
| 72      | 2         | 0.62%   |
| 21      | 2         | 0.62%   |
| 11      | 2         | 0.62%   |
| 8       | 2         | 0.62%   |
| Unknown | 2         | 0.62%   |
| 86      | 1         | 0.31%   |
| 84      | 1         | 0.31%   |
| 69      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 43      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 26      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 19      | 1         | 0.31%   |
| 12      | 1         | 0.31%   |
| 10      | 1         | 0.31%   |
| 7       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 205       | 63.47%  |
| 351-400     | 36        | 11.15%  |
| 501-600     | 34        | 10.53%  |
| 201-300     | 16        | 4.95%   |
| 601-700     | 11        | 3.41%   |
| 401-500     | 6         | 1.86%   |
| 1501-2000   | 4         | 1.24%   |
| 701-800     | 3         | 0.93%   |
| 101-200     | 2         | 0.62%   |
| Unknown     | 2         | 0.62%   |
| 801-900     | 1         | 0.31%   |
| 1001-1500   | 1         | 0.31%   |
| 901-1000    | 1         | 0.31%   |
| 1-100       | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 232       | 83.75%  |
| 16/10 | 36        | 13%     |
| 21/9  | 3         | 1.08%   |
| 5/4   | 2         | 0.72%   |
| 0.62  | 2         | 0.72%   |
| 3/2   | 1         | 0.36%   |
| 0.67  | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 155       | 47.84%  |
| 81-90          | 49        | 15.12%  |
| 121-130        | 30        | 9.26%   |
| 201-250        | 17        | 5.25%   |
| 351-500        | 14        | 4.32%   |
| 301-350        | 12        | 3.7%    |
| 111-120        | 9         | 2.78%   |
| 251-300        | 7         | 2.16%   |
| 71-80          | 6         | 1.85%   |
| More than 1000 | 5         | 1.54%   |
| 141-150        | 4         | 1.23%   |
| 1-40           | 3         | 0.93%   |
| 151-200        | 3         | 0.93%   |
| 131-140        | 3         | 0.93%   |
| 51-60          | 2         | 0.62%   |
| Unknown        | 2         | 0.62%   |
| 61-70          | 1         | 0.31%   |
| 41-50          | 1         | 0.31%   |
| 501-1000       | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 163       | 51.26%  |
| 101-120       | 62        | 19.5%   |
| 51-100        | 49        | 15.41%  |
| 161-240       | 23        | 7.23%   |
| More than 240 | 14        | 4.4%    |
| 1-50          | 5         | 1.57%   |
| Unknown       | 2         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 207       | 75.82%  |
| 2     | 56        | 20.51%  |
| 0     | 6         | 2.2%    |
| 3     | 4         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 165       | 37.5%   |
| Intel                           | 143       | 32.5%   |
| Qualcomm Atheros                | 42        | 9.55%   |
| Broadcom                        | 26        | 5.91%   |
| MediaTek                        | 22        | 5%      |
| Xiaomi                          | 4         | 0.91%   |
| Samsung Electronics             | 4         | 0.91%   |
| Broadcom Limited                | 4         | 0.91%   |
| ASIX Electronics                | 4         | 0.91%   |
| Qualcomm                        | 3         | 0.68%   |
| Nvidia                          | 3         | 0.68%   |
| Sierra Wireless                 | 2         | 0.45%   |
| Ralink Technology               | 2         | 0.45%   |
| Ralink                          | 2         | 0.45%   |
| Qualcomm Atheros Communications | 2         | 0.45%   |
| Lenovo                          | 2         | 0.45%   |
| TP-Link                         | 1         | 0.23%   |
| Panasonic (Matsushita)          | 1         | 0.23%   |
| OPPO Electronics                | 1         | 0.23%   |
| Motorola PCS                    | 1         | 0.23%   |
| Microsoft                       | 1         | 0.23%   |
| Marvell Technology Group        | 1         | 0.23%   |
| JMicron Technology              | 1         | 0.23%   |
| Google                          | 1         | 0.23%   |
| ASUSTek Computer                | 1         | 0.23%   |
| Afatech                         | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 22.18%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 3.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.77%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 2.18%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.98%   |
| Intel Wireless 8260                                               | 10        | 1.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 1.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.78%   |
| Intel Wireless 7260                                               | 9         | 1.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 1.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.39%   |
| Intel Wireless 7265                                               | 7         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.99%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.79%   |
| Intel Wireless-AC 9260                                            | 4         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 50.55%  |
| Realtek Semiconductor           | 43        | 15.64%  |
| Qualcomm Atheros                | 33        | 12%     |
| Broadcom                        | 23        | 8.36%   |
| MediaTek                        | 22        | 8%      |
| Broadcom Limited                | 3         | 1.09%   |
| Sierra Wireless                 | 2         | 0.73%   |
| Ralink Technology               | 2         | 0.73%   |
| Ralink                          | 2         | 0.73%   |
| Qualcomm Atheros Communications | 2         | 0.73%   |
| TP-Link                         | 1         | 0.36%   |
| Panasonic (Matsushita)          | 1         | 0.36%   |
| Microsoft                       | 1         | 0.36%   |
| ASUSTek Computer                | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 19        | 6.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 15        | 5.45%   |
| Intel Comet Lake PCH CNVi WiFi                                | 15        | 5.45%   |
| Intel Wi-Fi 6 AX201                                           | 13        | 4.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 12        | 4.36%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 11        | 4%      |
| Intel Wireless 8265 / 8275                                    | 10        | 3.64%   |
| Intel Wireless 8260                                           | 10        | 3.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 9         | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 9         | 3.27%   |
| Intel Wireless 7260                                           | 9         | 3.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 2.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 8         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7         | 2.55%   |
| Intel Wireless 7265                                           | 7         | 2.55%   |
| Broadcom BCM43142 802.11b/g/n                                 | 7         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6         | 2.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 6         | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 5         | 1.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4         | 1.45%   |
| Intel Wireless-AC 9260                                        | 4         | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 4         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 2         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 2         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 0.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 0.73%   |
| Intel Wireless 3160                                           | 2         | 0.73%   |
| Intel WiFi Link 5100                                          | 2         | 0.73%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 2         | 0.73%   |
| Intel Centrino Advanced-N 6235                                | 2         | 0.73%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 0.73%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 2         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 147       | 64.76%  |
| Intel                    | 34        | 14.98%  |
| Qualcomm Atheros         | 14        | 6.17%   |
| Broadcom                 | 7         | 3.08%   |
| Xiaomi                   | 4         | 1.76%   |
| ASIX Electronics         | 4         | 1.76%   |
| Samsung Electronics      | 3         | 1.32%   |
| Qualcomm                 | 3         | 1.32%   |
| Nvidia                   | 3         | 1.32%   |
| Lenovo                   | 2         | 0.88%   |
| OPPO Electronics         | 1         | 0.44%   |
| Motorola PCS             | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Google                   | 1         | 0.44%   |
| Broadcom Limited         | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 49.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 3.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.32%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.88%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 2         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.88%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.88%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.44%   |
| Qualcomm MDM9207-MTP _SN:F0A6D599                                 | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.44%   |
| OPPO RMX2027                                                      | 1         | 0.44%   |
| Motorola PCS motorola one macro                                   | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 266       | 55.07%  |
| Ethernet | 215       | 44.51%  |
| Modem    | 1         | 0.21%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 73.96%  |
| Ethernet | 75        | 26.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 194       | 71.85%  |
| 1     | 72        | 26.67%  |
| 0     | 3         | 1.11%   |
| 3     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 200       | 73.8%   |
| Yes  | 71        | 26.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 54.07%  |
| Realtek Semiconductor           | 29        | 11.79%  |
| Qualcomm Atheros Communications | 14        | 5.69%   |
| Lite-On Technology              | 14        | 5.69%   |
| Foxconn / Hon Hai               | 14        | 5.69%   |
| IMC Networks                    | 13        | 5.28%   |
| Broadcom                        | 10        | 4.07%   |
| Apple                           | 9         | 3.66%   |
| Toshiba                         | 2         | 0.81%   |
| Ralink                          | 2         | 0.81%   |
| MediaTek                        | 2         | 0.81%   |
| Cambridge Silicon Radio         | 2         | 0.81%   |
| Realtek                         | 1         | 0.41%   |
| Foxconn International           | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 44        | 17.89%  |
| Intel AX201 Bluetooth                               | 30        | 12.2%   |
| Realtek Bluetooth Radio                             | 23        | 9.35%   |
| Intel AX200 Bluetooth                               | 19        | 7.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 6.5%    |
| Intel Bluetooth Device                              | 10        | 4.07%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 3.66%   |
| Intel AX210 Bluetooth                               | 8         | 3.25%   |
| Apple Bluetooth Host Controller                     | 8         | 3.25%   |
| IMC Networks Wireless_Device                        | 6         | 2.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 2.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.63%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.22%   |
| Lite-On Bluetooth Device                            | 3         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.81%   |
| MediaTek Wireless_Device                            | 2         | 0.81%   |
| Lite-On Wireless_Device                             | 2         | 0.81%   |
| Lite-On Bluetooth Radio                             | 2         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.81%   |
| IMC Networks Bluetooth Device                       | 2         | 0.81%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 2         | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.81%   |
| Toshiba Bluetooth Radio                             | 1         | 0.41%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.41%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.41%   |
| Realtek Bluetooth Radio                             | 1         | 0.41%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.41%   |
| Lite-On BCM43142A0                                  | 1         | 0.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.41%   |
| IMC Networks BCM20702A0                             | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 182       | 45.84%  |
| AMD                        | 95        | 23.93%  |
| Nvidia                     | 91        | 22.92%  |
| Razer USA                  | 3         | 0.76%   |
| Lenovo                     | 3         | 0.76%   |
| C-Media Electronics        | 3         | 0.76%   |
| TTGK Technology            | 2         | 0.5%    |
| Sony                       | 2         | 0.5%    |
| Logitech                   | 2         | 0.5%    |
| Creative Technology        | 2         | 0.5%    |
| Tenx Technology            | 1         | 0.25%   |
| SteelSeries ApS            | 1         | 0.25%   |
| Samsung Electronics        | 1         | 0.25%   |
| Realtek Semiconductor      | 1         | 0.25%   |
| PreSonus Audio Electronics | 1         | 0.25%   |
| Native Instruments         | 1         | 0.25%   |
| Hewlett-Packard            | 1         | 0.25%   |
| GN Netcom                  | 1         | 0.25%   |
| Generalplus Technology     | 1         | 0.25%   |
| Corsair                    | 1         | 0.25%   |
| Blue Microphones           | 1         | 0.25%   |
| ASUSTek Computer           | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 73        | 14.84%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 30        | 6.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 4.07%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 3.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 3.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 3.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 16        | 3.25%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 3.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 3.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 3.05%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 2.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 2.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 10        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.83%   |
| Nvidia Audio device                                                                               | 8         | 1.63%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.42%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 1.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 1.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 6         | 1.22%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.81%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 0.81%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 0.81%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.61%   |
| TTGK Technology Audio                                                                             | 2         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 33.7%   |
| SK hynix            | 19        | 20.65%  |
| Micron Technology   | 17        | 18.48%  |
| Kingston            | 5         | 5.43%   |
| Crucial             | 3         | 3.26%   |
| Unknown (ABCD)      | 2         | 2.17%   |
| Unknown             | 2         | 2.17%   |
| Team                | 2         | 2.17%   |
| G.Skill             | 2         | 2.17%   |
| Corsair             | 2         | 2.17%   |
| A-DATA Technology   | 2         | 2.17%   |
| Transcend           | 1         | 1.09%   |
| Nanya Technology    | 1         | 1.09%   |
| Elpida              | 1         | 1.09%   |
| AMD                 | 1         | 1.09%   |
| Unknown             | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 5.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 3.09%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.06%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.06%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.06%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 2         | 2.06%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 2.06%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 2.06%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 2.06%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 2.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.06%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.03%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 1.03%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.03%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 1.03%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 1.03%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.03%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.03%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.03%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.03%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.03%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.03%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.03%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.03%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 1.03%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.03%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.03%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 60.81%  |
| DDR5    | 10        | 13.51%  |
| DDR3    | 10        | 13.51%  |
| LPDDR4  | 7         | 9.46%   |
| DDR2    | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 89.33%  |
| Row Of Chips | 8         | 10.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 49.4%   |
| 4096  | 17        | 20.48%  |
| 16384 | 14        | 16.87%  |
| 32768 | 7         | 8.43%   |
| 2048  | 4         | 4.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 26        | 33.33%  |
| 2667  | 16        | 20.51%  |
| 1600  | 8         | 10.26%  |
| 4800  | 7         | 8.97%   |
| 2400  | 5         | 6.41%   |
| 5600  | 3         | 3.85%   |
| 4267  | 2         | 2.56%   |
| 3266  | 2         | 2.56%   |
| 2133  | 2         | 2.56%   |
| 1333  | 2         | 2.56%   |
| 6400  | 1         | 1.28%   |
| 4266  | 1         | 1.28%   |
| 3333  | 1         | 1.28%   |
| 1334  | 1         | 1.28%   |
| 975   | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung Composite Device | 1         | 100%    |

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
| Chicony Electronics                    | 54        | 22.5%   |
| IMC Networks                           | 33        | 13.75%  |
| Realtek Semiconductor                  | 18        | 7.5%    |
| Bison Electronics                      | 17        | 7.08%   |
| Sunplus Innovation Technology          | 14        | 5.83%   |
| Quanta                                 | 14        | 5.83%   |
| Syntek                                 | 11        | 4.58%   |
| Microdia                               | 11        | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.58%   |
| Apple                                  | 10        | 4.17%   |
| Sonix Technology                       | 6         | 2.5%    |
| Luxvisions Innotech Limited            | 6         | 2.5%    |
| Logitech                               | 6         | 2.5%    |
| Lite-On Technology                     | 6         | 2.5%    |
| Suyin                                  | 5         | 2.08%   |
| Silicon Motion                         | 3         | 1.25%   |
| SunplusIT                              | 2         | 0.83%   |
| Samsung Electronics                    | 2         | 0.83%   |
| Intel                                  | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.42%   |
| Tobii Technology AB                    | 1         | 0.42%   |
| Shine-optics                           | 1         | 0.42%   |
| Ruision                                | 1         | 0.42%   |
| Importek                               | 1         | 0.42%   |
| HRY                                    | 1         | 0.42%   |
| Google                                 | 1         | 0.42%   |
| Goodong Industry                       | 1         | 0.42%   |
| Acer                                   | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 5.81%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 13        | 5.39%   |
| Realtek Integrated_Webcam_HD                        | 9         | 3.73%   |
| IMC Networks Integrated Camera                      | 9         | 3.73%   |
| Syntek Integrated Camera                            | 8         | 3.32%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 2.9%    |
| Chicony HD WebCam                                   | 6         | 2.49%   |
| Microdia Integrated_Webcam_HD                       | 5         | 2.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 2.07%   |
| Bison Integrated Camera                             | 5         | 2.07%   |
| Bison HD Webcam                                     | 5         | 2.07%   |
| Chicony HP TrueVision HD                            | 4         | 1.66%   |
| Apple FaceTime HD Camera                            | 4         | 1.66%   |
| Sunplus HD WebCam                                   | 3         | 1.24%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.24%   |
| Sonix USB2.0 FHD UVC WebCam                         | 3         | 1.24%   |
| Realtek USB Camera                                  | 3         | 1.24%   |
| Quanta VGA WebCam                                   | 3         | 1.24%   |
| Quanta HD User Facing                               | 3         | 1.24%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.24%   |
| Lite-On HP HD Webcam                                | 3         | 1.24%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.24%   |
| Chicony HD User Facing                              | 3         | 1.24%   |
| Bison Lenovo Integrated Webcam                      | 3         | 1.24%   |
| Apple Built-in iSight                               | 3         | 1.24%   |
| Syntek EasyCamera                                   | 2         | 0.83%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.83%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 0.83%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.83%   |
| Quanta HD Webcam                                    | 2         | 0.83%   |
| Microdia USB 2.0 Camera                             | 2         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.83%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 0.83%   |
| Lite-On HP HD Camera                                | 2         | 0.83%   |
| Intel RealSense 3D Camera (Front F200)              | 2         | 0.83%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.83%   |
| Chicony USB2.0 Camera                               | 2         | 0.83%   |
| Chicony USB 2.0 Camera                              | 2         | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 13        | 35.14%  |
| Synaptics                          | 8         | 21.62%  |
| Shenzhen Goodix Technology         | 7         | 18.92%  |
| Elan Microelectronics              | 5         | 13.51%  |
| Realtek USB2.0 Finger Print Bridge | 3         | 8.11%   |
| Focal-systems.Corp                 | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 21.62%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 13.51%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 8.11%   |
| Elan ELAN:ARM-M4                                                | 3         | 8.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 5.41%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 5.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5.41%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 5.41%   |
| Elan ELAN:Fingerprint                                           | 2         | 5.41%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 2.7%    |
| Synaptics WBDI Device                                           | 1         | 2.7%    |
| Synaptics UWP WBDI Device                                       | 1         | 2.7%    |
| Synaptics  WBDI                                                 | 1         | 2.7%    |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 2.7%    |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 181       | 66.06%  |
| 1     | 76        | 27.74%  |
| 2     | 15        | 5.47%   |
| 3     | 2         | 0.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 32.14%  |
| Graphics card            | 29        | 25.89%  |
| Multimedia controller    | 25        | 22.32%  |
| Net/wireless             | 14        | 12.5%   |
| Bluetooth                | 3         | 2.68%   |
| Storage/nvme             | 1         | 0.89%   |
| Modem                    | 1         | 0.89%   |
| Communication controller | 1         | 0.89%   |
| Chipcard                 | 1         | 0.89%   |
| Camera                   | 1         | 0.89%   |

