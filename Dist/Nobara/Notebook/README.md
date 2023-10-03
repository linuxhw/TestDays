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

Total: 325

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Nobara 36 | 113       | 44.66%  |
| Nobara 37 | 105       | 41.5%   |
| Nobara 38 | 35        | 13.83%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 249       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 19        | 7.31%   |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 6.15%   |
| 6.1.11-201.fsync.fc37.x86_64  | 12        | 4.62%   |
| 6.0.14-201.fsync.fc36.x86_64  | 11        | 4.23%   |
| 6.1.4-203.fsync.fc37.x86_64   | 10        | 3.85%   |
| 6.3.12-204.fsync.fc38.x86_64  | 9         | 3.46%   |
| 6.2.14-300.fsync.fc37.x86_64  | 9         | 3.46%   |
| 6.1.14-201.fsync.fc37.x86_64  | 9         | 3.46%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 2.69%   |
| 6.0.16-301.fsync.fc37.x86_64  | 7         | 2.69%   |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 2.69%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 2.69%   |
| 6.3.5-201.fsync.fc37.x86_64   | 6         | 2.31%   |
| 6.2.11-201.fsync.fc37.x86_64  | 6         | 2.31%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 2.31%   |
| 6.3.7-200.fsync.fc37.x86_64   | 5         | 1.92%   |
| 6.3.10-200.fsync.fc38.x86_64  | 5         | 1.92%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 1.92%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 1.92%   |
| 6.4.10-202.fsync.fc38.x86_64  | 4         | 1.54%   |
| 6.2.6-201.fsync.fc37.x86_64   | 4         | 1.54%   |
| 6.2.12-200.fsync.fc37.x86_64  | 4         | 1.54%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4         | 1.54%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 1.54%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 1.54%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 1.54%   |
| 6.5.3-200.fsync.fc38.x86_64   | 3         | 1.15%   |
| 6.3.12-205.fsync.fc38.x86_64  | 3         | 1.15%   |
| 6.3.10-200.fsync.fc37.x86_64  | 3         | 1.15%   |
| 6.2.8-200.fsync.fc37.x86_64   | 3         | 1.15%   |
| 6.2.10-200.fsync.fc37.x86_64  | 3         | 1.15%   |
| 6.1.6-203.fsync.fc37.x86_64   | 3         | 1.15%   |
| 6.0.9-202.fc36.x86_64         | 3         | 1.15%   |
| 6.0.9-201.fc36.x86_64         | 3         | 1.15%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 1.15%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 1.15%   |
| 6.5.5-200.fsync.fc38.x86_64   | 2         | 0.77%   |
| 6.3.12-204.fsync.fc37.x86_64  | 2         | 0.77%   |
| 6.3.12-203.fsync.fc38.x86_64  | 2         | 0.77%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 19        | 7.31%   |
| 6.3.12  | 16        | 6.15%   |
| 5.19.14 | 16        | 6.15%   |
| 6.1.11  | 12        | 4.62%   |
| 6.0.14  | 11        | 4.23%   |
| 6.1.4   | 10        | 3.85%   |
| 6.3.10  | 9         | 3.46%   |
| 6.2.14  | 9         | 3.46%   |
| 6.1.14  | 9         | 3.46%   |
| 5.19.7  | 8         | 3.08%   |
| 6.4.10  | 7         | 2.69%   |
| 6.2.11  | 7         | 2.69%   |
| 6.1.9   | 7         | 2.69%   |
| 6.1.6   | 7         | 2.69%   |
| 6.0.7   | 7         | 2.69%   |
| 6.0.16  | 7         | 2.69%   |
| 5.19.9  | 7         | 2.69%   |
| 6.3.5   | 6         | 2.31%   |
| 6.1.8   | 6         | 2.31%   |
| 6.0.9   | 6         | 2.31%   |
| 6.3.7   | 5         | 1.92%   |
| 6.0.5   | 5         | 1.92%   |
| 5.19.12 | 5         | 1.92%   |
| 6.5.3   | 4         | 1.54%   |
| 6.2.6   | 4         | 1.54%   |
| 6.2.12  | 4         | 1.54%   |
| 5.19.8  | 4         | 1.54%   |
| 5.19.16 | 4         | 1.54%   |
| 5.19.11 | 4         | 1.54%   |
| 6.2.8   | 3         | 1.15%   |
| 6.2.10  | 3         | 1.15%   |
| 5.18.16 | 3         | 1.15%   |
| 5.18.13 | 3         | 1.15%   |
| 6.5.5   | 2         | 0.77%   |
| 6.3.9   | 2         | 0.77%   |
| 6.0.8   | 2         | 0.77%   |
| 5.19.4  | 2         | 0.77%   |
| 5.19.15 | 2         | 0.77%   |
| 5.18.17 | 2         | 0.77%   |
| 6.5.4   | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 59        | 23.05%  |
| 5.19    | 54        | 21.09%  |
| 6.1     | 51        | 19.92%  |
| 6.3     | 38        | 14.84%  |
| 6.2     | 29        | 11.33%  |
| 5.18    | 10        | 3.91%   |
| 6.4     | 8         | 3.13%   |
| 6.5     | 7         | 2.73%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 249       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 183       | 72.91%  |
| KDE5    | 61        | 24.3%   |
| Unknown | 7         | 2.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 198       | 78.88%  |
| X11     | 48        | 19.12%  |
| Unknown | 4         | 1.59%   |
| Tty     | 1         | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 193       | 76.28%  |
| GDM     | 40        | 15.81%  |
| SDDM    | 18        | 7.11%   |
| LightDM | 2         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 133       | 53.2%   |
| en_GB   | 13        | 5.2%    |
| es_ES   | 11        | 4.4%    |
| de_DE   | 10        | 4%      |
| pt_BR   | 8         | 3.2%    |
| pl_PL   | 8         | 3.2%    |
| ru_RU   | 7         | 2.8%    |
| it_IT   | 7         | 2.8%    |
| es_MX   | 5         | 2%      |
| en_NZ   | 5         | 2%      |
| en_IN   | 5         | 2%      |
| es_AR   | 4         | 1.6%    |
| en_CA   | 4         | 1.6%    |
| tr_TR   | 3         | 1.2%    |
| pt_PT   | 3         | 1.2%    |
| en_AU   | 3         | 1.2%    |
| Unknown | 3         | 1.2%    |
| zh_TW   | 2         | 0.8%    |
| fr_FR   | 2         | 0.8%    |
| sv_SE   | 1         | 0.4%    |
| ro_RO   | 1         | 0.4%    |
| nb_NO   | 1         | 0.4%    |
| hu_HU   | 1         | 0.4%    |
| hr_HR   | 1         | 0.4%    |
| fi_FI   | 1         | 0.4%    |
| es_US   | 1         | 0.4%    |
| es_CR   | 1         | 0.4%    |
| es_CO   | 1         | 0.4%    |
| es_CL   | 1         | 0.4%    |
| en_ZA   | 1         | 0.4%    |
| en_PH   | 1         | 0.4%    |
| en_IE   | 1         | 0.4%    |
| de_AT   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 210       | 83.67%  |
| BIOS | 41        | 16.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 184       | 73.31%  |
| Ext4  | 66        | 26.29%  |
| Xfs   | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 188       | 74.02%  |
| GPT     | 63        | 24.8%   |
| MBR     | 3         | 1.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 230       | 91.63%  |
| Yes       | 21        | 8.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 215       | 86.35%  |
| Yes       | 34        | 13.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 60        | 24.1%   |
| ASUSTek Computer                 | 43        | 17.27%  |
| Hewlett-Packard                  | 38        | 15.26%  |
| Dell                             | 26        | 10.44%  |
| Acer                             | 18        | 7.23%   |
| MSI                              | 11        | 4.42%   |
| Apple                            | 11        | 4.42%   |
| Toshiba                          | 4         | 1.61%   |
| Samsung Electronics              | 3         | 1.2%    |
| Gigabyte Technology              | 3         | 1.2%    |
| Positivo                         | 2         | 0.8%    |
| Notebook                         | 2         | 0.8%    |
| Infinix                          | 2         | 0.8%    |
| Alienware                        | 2         | 0.8%    |
| Valve                            | 1         | 0.4%    |
| Timi                             | 1         | 0.4%    |
| Sony                             | 1         | 0.4%    |
| Schenker                         | 1         | 0.4%    |
| Razer                            | 1         | 0.4%    |
| Packard Bell                     | 1         | 0.4%    |
| ONE-NETBOOK                      | 1         | 0.4%    |
| Monster                          | 1         | 0.4%    |
| Micro Electronics                | 1         | 0.4%    |
| Micro Computer (HK) Tech Limited | 1         | 0.4%    |
| Medion                           | 1         | 0.4%    |
| Intel                            | 1         | 0.4%    |
| HUAWEI                           | 1         | 0.4%    |
| GPU Company                      | 1         | 0.4%    |
| Google                           | 1         | 0.4%    |
| GEO                              | 1         | 0.4%    |
| Gateway                          | 1         | 0.4%    |
| Fujitsu                          | 1         | 0.4%    |
| EVOO                             | 1         | 0.4%    |
| Dynabook                         | 1         | 0.4%    |
| Coradir                          | 1         | 0.4%    |
| Casper                           | 1         | 0.4%    |
| ASRock                           | 1         | 0.4%    |
| Unknown                          | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 2.01%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 1.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx | 3         | 1.2%    |
| Lenovo Legion 5 15ARH05H 82B1       | 2         | 0.8%    |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.8%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 2         | 0.8%    |
| Lenovo IdeaPad C340-14API 81N6      | 2         | 0.8%    |
| Lenovo IdeaPad 5 15ITL05 82FG       | 2         | 0.8%    |
| HP ZBook 15u G3                     | 2         | 0.8%    |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.8%    |
| HP Pavilion 15                      | 2         | 0.8%    |
| Dell Vostro 3400                    | 2         | 0.8%    |
| Dell Inspiron 3542                  | 2         | 0.8%    |
| Dell Inspiron 15 3520               | 2         | 0.8%    |
| Dell G5 5505                        | 2         | 0.8%    |
| ASUS ROG Strix G512LW_G512LW        | 2         | 0.8%    |
| Apple MacBookPro8,3                 | 2         | 0.8%    |
| Apple MacBookPro8,1                 | 2         | 0.8%    |
| Acer Nitro AN515-52                 | 2         | 0.8%    |
| Acer Nitro AN515-42                 | 2         | 0.8%    |
| Acer Aspire VX5-591G                | 2         | 0.8%    |
| Valve Jupiter                       | 1         | 0.4%    |
| Toshiba TECRA A50-A                 | 1         | 0.4%    |
| Toshiba Satellite S55t-C            | 1         | 0.4%    |
| Toshiba Satellite L850              | 1         | 0.4%    |
| Toshiba Satellite L650              | 1         | 0.4%    |
| Timi A30                            | 1         | 0.4%    |
| Sony SVF1521N6EW                    | 1         | 0.4%    |
| Schenker XMG NEO (M19, RTX 2070)    | 1         | 0.4%    |
| Samsung R520/R522/R620              | 1         | 0.4%    |
| Samsung 535U3C                      | 1         | 0.4%    |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.4%    |
| Razer Blade                         | 1         | 0.4%    |
| Positivo N1250                      | 1         | 0.4%    |
| Positivo N1240                      | 1         | 0.4%    |
| Packard Bell EasyNote LS11HR        | 1         | 0.4%    |
| ONE-NETBOOK ONEXPLAYER 2 ARP23      | 1         | 0.4%    |
| Notebook P7xxDM2(-G)                | 1         | 0.4%    |
| Notebook NP5x_NP6x_NP7xHP           | 1         | 0.4%    |
| MSI Summit E14Evo A12M              | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 21        | 8.43%   |
| Lenovo ThinkPad   | 15        | 6.02%   |
| ASUS ROG          | 14        | 5.62%   |
| Lenovo Legion     | 12        | 4.82%   |
| HP Pavilion       | 10        | 4.02%   |
| ASUS VivoBook     | 10        | 4.02%   |
| Acer Nitro        | 7         | 2.81%   |
| HP EliteBook      | 6         | 2.41%   |
| Dell Inspiron     | 6         | 2.41%   |
| Acer Aspire       | 6         | 2.41%   |
| HP ZBook          | 5         | 2.01%   |
| Unknown           | 5         | 2.01%   |
| Dell Vostro       | 4         | 1.61%   |
| Dell Precision    | 4         | 1.61%   |
| ASUS ASUS         | 4         | 1.61%   |
| Apple MacBookPro8 | 4         | 1.61%   |
| Toshiba Satellite | 3         | 1.2%    |
| HP Laptop         | 3         | 1.2%    |
| HP ENVY           | 3         | 1.2%    |
| Dell Latitude     | 3         | 1.2%    |
| ASUS TUF          | 3         | 1.2%    |
| MSI GT70          | 2         | 0.8%    |
| Lenovo G580       | 2         | 0.8%    |
| Infinix INBook    | 2         | 0.8%    |
| HP ProBook        | 2         | 0.8%    |
| HP OMEN           | 2         | 0.8%    |
| Gigabyte AERO     | 2         | 0.8%    |
| Dell G5           | 2         | 0.8%    |
| Dell G3           | 2         | 0.8%    |
| Dell G15          | 2         | 0.8%    |
| Apple MacBookPro5 | 2         | 0.8%    |
| Acer Swift        | 2         | 0.8%    |
| Valve Jupiter     | 1         | 0.4%    |
| Toshiba TECRA     | 1         | 0.4%    |
| Timi A30          | 1         | 0.4%    |
| Sony SVF1521N6EW  | 1         | 0.4%    |
| Schenker XMG      | 1         | 0.4%    |
| Samsung R520      | 1         | 0.4%    |
| Samsung 535U3C    | 1         | 0.4%    |
| Samsung 340XAA    | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 39        | 15.66%  |
| 2020 | 32        | 12.85%  |
| 2018 | 27        | 10.84%  |
| 2022 | 25        | 10.04%  |
| 2019 | 23        | 9.24%   |
| 2014 | 18        | 7.23%   |
| 2013 | 17        | 6.83%   |
| 2015 | 12        | 4.82%   |
| 2017 | 11        | 4.42%   |
| 2012 | 11        | 4.42%   |
| 2016 | 10        | 4.02%   |
| 2023 | 8         | 3.21%   |
| 2011 | 5         | 2.01%   |
| 2010 | 5         | 2.01%   |
| 2009 | 5         | 2.01%   |
| 2008 | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 249       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 249       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 248       | 99.6%   |
| Yes  | 1         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 25.6%   |
| 16.01-24.0  | 58        | 23.2%   |
| 8.01-16.0   | 57        | 22.8%   |
| 32.01-64.0  | 30        | 12%     |
| 3.01-4.0    | 28        | 11.2%   |
| 24.01-32.0  | 9         | 3.6%    |
| 64.01-256.0 | 2         | 0.8%    |
| 1.01-2.0    | 2         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 112       | 43.92%  |
| 2.01-3.0  | 59        | 23.14%  |
| 3.01-4.0  | 54        | 21.18%  |
| 8.01-16.0 | 22        | 8.63%   |
| 1.01-2.0  | 8         | 3.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 170       | 68%     |
| 2      | 66        | 26.4%   |
| 3      | 12        | 4.8%    |
| 5      | 1         | 0.4%    |
| 4      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 80.32%  |
| Yes       | 49        | 19.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 78.8%   |
| No        | 53        | 21.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 98.8%   |
| No        | 3         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 90.36%  |
| No        | 24        | 9.64%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 75        | 30.12%  |
| Germany             | 15        | 6.02%   |
| Spain               | 13        | 5.22%   |
| Poland              | 13        | 5.22%   |
| Brazil              | 10        | 4.02%   |
| UK                  | 8         | 3.21%   |
| Italy               | 8         | 3.21%   |
| Russia              | 7         | 2.81%   |
| Mexico              | 7         | 2.81%   |
| India               | 7         | 2.81%   |
| Portugal            | 5         | 2.01%   |
| New Zealand         | 5         | 2.01%   |
| Canada              | 5         | 2.01%   |
| Turkey              | 4         | 1.61%   |
| Romania             | 4         | 1.61%   |
| Indonesia           | 4         | 1.61%   |
| Australia           | 4         | 1.61%   |
| Argentina           | 4         | 1.61%   |
| Sweden              | 3         | 1.2%    |
| Philippines         | 3         | 1.2%    |
| Malaysia            | 3         | 1.2%    |
| Colombia            | 3         | 1.2%    |
| Chile               | 3         | 1.2%    |
| Vietnam             | 2         | 0.8%    |
| France              | 2         | 0.8%    |
| Finland             | 2         | 0.8%    |
| Egypt               | 2         | 0.8%    |
| Croatia             | 2         | 0.8%    |
| Austria             | 2         | 0.8%    |
| Venezuela           | 1         | 0.4%    |
| Tunisia             | 1         | 0.4%    |
| Trinidad and Tobago | 1         | 0.4%    |
| Taiwan              | 1         | 0.4%    |
| Sri Lanka           | 1         | 0.4%    |
| South Africa        | 1         | 0.4%    |
| Slovenia            | 1         | 0.4%    |
| Serbia              | 1         | 0.4%    |
| Panama              | 1         | 0.4%    |
| Pakistan            | 1         | 0.4%    |
| Norway              | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Wroclaw        | 3         | 1.16%   |
| San Francisco  | 3         | 1.16%   |
| Madrid         | 3         | 1.16%   |
| Kuala Lumpur   | 3         | 1.16%   |
| Auckland       | 3         | 1.16%   |
| Wasilla        | 2         | 0.77%   |
| Warsaw         | 2         | 0.77%   |
| Stockholm      | 2         | 0.77%   |
| Schmalkalden   | 2         | 0.77%   |
| San Jose       | 2         | 0.77%   |
| Salem          | 2         | 0.77%   |
| Poznan         | 2         | 0.77%   |
| Perm           | 2         | 0.77%   |
| Panama City    | 2         | 0.77%   |
| Ochsenfurt     | 2         | 0.77%   |
| Mumbai         | 2         | 0.77%   |
| Milano         | 2         | 0.77%   |
| Milan          | 2         | 0.77%   |
| Lisbon         | 2         | 0.77%   |
| Houston        | 2         | 0.77%   |
| Hamburg        | 2         | 0.77%   |
| Guadalajara    | 2         | 0.77%   |
| Fortaleza      | 2         | 0.77%   |
| Bucharest      | 2         | 0.77%   |
| Berlin         | 2         | 0.77%   |
| Atlanta        | 2         | 0.77%   |
| Zamora         | 1         | 0.39%   |
| Zadar          | 1         | 0.39%   |
| Wesley Chapel  | 1         | 0.39%   |
| Wellington     | 1         | 0.39%   |
| Wayne          | 1         | 0.39%   |
| Wabrzezno      | 1         | 0.39%   |
| Vladivostok    | 1         | 0.39%   |
| Virginia Beach | 1         | 0.39%   |
| Villarrica     | 1         | 0.39%   |
| Villa Nueva    | 1         | 0.39%   |
| Vienna         | 1         | 0.39%   |
| Veszprém      | 1         | 0.39%   |
| Varaždin      | 1         | 0.39%   |
| Valladolid     | 1         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 71        | 84     | 21.39%  |
| Sandisk                      | 25        | 26     | 7.53%   |
| WDC                          | 23        | 25     | 6.93%   |
| SK hynix                     | 21        | 21     | 6.33%   |
| Seagate                      | 21        | 21     | 6.33%   |
| Kingston                     | 20        | 20     | 6.02%   |
| Intel                        | 19        | 21     | 5.72%   |
| Toshiba                      | 18        | 23     | 5.42%   |
| Crucial                      | 13        | 14     | 3.92%   |
| Micron Technology            | 12        | 12     | 3.61%   |
| Unknown                      | 8         | 8      | 2.41%   |
| Phison Electronics           | 8         | 8      | 2.41%   |
| Micron/Crucial Technology    | 8         | 8      | 2.41%   |
| KIOXIA                       | 7         | 7      | 2.11%   |
| HGST                         | 7         | 7      | 2.11%   |
| Hitachi                      | 4         | 5      | 1.2%    |
| China                        | 4         | 4      | 1.2%    |
| Apple                        | 4         | 5      | 1.2%    |
| A-DATA Technology            | 4         | 4      | 1.2%    |
| Team                         | 3         | 3      | 0.9%    |
| Kingston Technology Company  | 3         | 3      | 0.9%    |
| Shenzhen Longsys Electronics | 2         | 2      | 0.6%    |
| LITEON                       | 2         | 2      | 0.6%    |
| HS-SSD-C100                  | 2         | 2      | 0.6%    |
| Unknown                      | 2         | 2      | 0.6%    |
| Wibtek                       | 1         | 1      | 0.3%    |
| Union Memory                 | 1         | 2      | 0.3%    |
| T-FORCE                      | 1         | 1      | 0.3%    |
| SPCC                         | 1         | 1      | 0.3%    |
| Solid State Storage          | 1         | 1      | 0.3%    |
| Silicon Motion               | 1         | 1      | 0.3%    |
| SABRENT                      | 1         | 1      | 0.3%    |
| Realtek                      | 1         | 1      | 0.3%    |
| Ramsta                       | 1         | 1      | 0.3%    |
| PNY                          | 1         | 1      | 0.3%    |
| Plextor                      | 1         | 1      | 0.3%    |
| Mushkin                      | 1         | 1      | 0.3%    |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.3%    |
| Lexar                        | 1         | 1      | 0.3%    |
| Intenso                      | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 13        | 3.77%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 2.32%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 7         | 2.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 7         | 2.03%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 1.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 5         | 1.45%   |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 1.45%   |
| SK hynix BC511 512GB                                | 4         | 1.16%   |
| Samsung SSD 980 1TB                                 | 4         | 1.16%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 4         | 1.16%   |
| Intel SSD 660P Series 1024GB                        | 4         | 1.16%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 3         | 0.87%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.87%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 3         | 0.87%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB       | 3         | 0.87%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 0.87%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 3         | 0.87%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.58%   |
| WDC WD10SPCX-24HWST1 1TB                            | 2         | 0.58%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 2         | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.58%   |
| Unknown MMC Card  64GB                              | 2         | 0.58%   |
| Unknown MMC Card  32GB                              | 2         | 0.58%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.58%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.58%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 0.58%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.58%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.58%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 0.58%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB     | 2         | 0.58%   |
| Sandisk PC SN740 NVMe WD 512GB                      | 2         | 0.58%   |
| Samsung SSD 870 EVO 2TB                             | 2         | 0.58%   |
| Samsung SSD 860 EVO M.2 1TB                         | 2         | 0.58%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.58%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.58%   |
| Samsung MZVLQ1T0HBLB-00B00 1TB                      | 2         | 0.58%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 2         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 21        | 21     | 31.82%  |
| WDC      | 15        | 16     | 22.73%  |
| Toshiba  | 13        | 16     | 19.7%   |
| HGST     | 7         | 7      | 10.61%  |
| Hitachi  | 4         | 5      | 6.06%   |
| Unknown  | 2         | 2      | 3.03%   |
| SABRENT  | 1         | 1      | 1.52%   |
| HGST HTS | 1         | 1      | 1.52%   |
| Fujitsu  | 1         | 1      | 1.52%   |
| Apple    | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 27     | 25.81%  |
| Kingston            | 13        | 13     | 13.98%  |
| Crucial             | 12        | 13     | 12.9%   |
| SanDisk             | 6         | 6      | 6.45%   |
| SK hynix            | 4         | 4      | 4.3%    |
| China               | 4         | 4      | 4.3%    |
| A-DATA Technology   | 4         | 4      | 4.3%    |
| Team                | 3         | 3      | 3.23%   |
| Intel               | 3         | 3      | 3.23%   |
| WDC                 | 2         | 3      | 2.15%   |
| Toshiba             | 2         | 3      | 2.15%   |
| Micron Technology   | 2         | 2      | 2.15%   |
| LITEON              | 2         | 2      | 2.15%   |
| Apple               | 2         | 2      | 2.15%   |
| Wibtek              | 1         | 1      | 1.08%   |
| SPCC                | 1         | 1      | 1.08%   |
| Ramsta              | 1         | 1      | 1.08%   |
| PNY                 | 1         | 1      | 1.08%   |
| Plextor             | 1         | 1      | 1.08%   |
| Mushkin             | 1         | 1      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| Emtec               | 1         | 1      | 1.08%   |
| Dell                | 1         | 1      | 1.08%   |
| Apacer              | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 145       | 177    | 47.23%  |
| SSD     | 85        | 99     | 27.69%  |
| HDD     | 65        | 71     | 21.17%  |
| MMC     | 6         | 6      | 1.95%   |
| Unknown | 6         | 6      | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 144       | 176    | 48.98%  |
| SATA | 131       | 162    | 44.56%  |
| SAS  | 13        | 15     | 4.42%   |
| MMC  | 6         | 6      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 94     | 54.9%   |
| 0.51-1.0   | 57        | 63     | 37.25%  |
| 1.01-2.0   | 10        | 11     | 6.54%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |
| 4.01-10.0  | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 68        | 26.67%  |
| 251-500        | 56        | 21.96%  |
| 101-250        | 45        | 17.65%  |
| 1001-2000      | 31        | 12.16%  |
| Unknown        | 15        | 5.88%   |
| More than 3000 | 14        | 5.49%   |
| 21-50          | 9         | 3.53%   |
| 2001-3000      | 8         | 3.14%   |
| 51-100         | 8         | 3.14%   |
| 1-20           | 1         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 71        | 27.63%  |
| 1-20           | 53        | 20.62%  |
| 101-250        | 37        | 14.4%   |
| 251-500        | 28        | 10.89%  |
| 51-100         | 25        | 9.73%   |
| 501-1000       | 15        | 5.84%   |
| Unknown        | 15        | 5.84%   |
| 1001-2000      | 9         | 3.5%    |
| More than 3000 | 2         | 0.78%   |
| 2001-3000      | 2         | 0.78%   |

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
| Detected | 193       | 269    | 73.38%  |
| Works    | 65        | 84     | 24.71%  |
| Malfunc  | 5         | 6      | 1.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 152       | 43.55%  |
| Samsung Electronics            | 50        | 14.33%  |
| AMD                            | 47        | 13.47%  |
| SanDisk                        | 24        | 6.88%   |
| SK hynix                       | 17        | 4.87%   |
| Micron Technology              | 10        | 2.87%   |
| Kingston Technology Company    | 10        | 2.87%   |
| Micron/Crucial Technology      | 9         | 2.58%   |
| Phison Electronics             | 8         | 2.29%   |
| KIOXIA                         | 7         | 2.01%   |
| Toshiba America Info Systems   | 3         | 0.86%   |
| Nvidia                         | 3         | 0.86%   |
| Shenzhen Longsys Electronics   | 2         | 0.57%   |
| Union Memory (Shenzhen)        | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Silicon Motion                 | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.29%   |
| Marvell Technology Group       | 1         | 0.29%   |
| Apple                          | 1         | 0.29%   |
| ADATA Technology               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 12.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 4.9%    |
| Samsung NVMe SSD Controller 980                                                | 16        | 4.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 15        | 4.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 3.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 11        | 3%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 2.72%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 8         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.18%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 7         | 1.91%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 1.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.63%   |
| Intel SSD 660P Series                                                          | 6         | 1.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 1.36%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 1.09%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 4         | 1.09%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.09%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 3         | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 0.82%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 3         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.82%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 3         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.82%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.54%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.54%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 2         | 0.54%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                          | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 171       | 49.71%  |
| NVMe | 143       | 41.57%  |
| RAID | 29        | 8.43%   |
| IDE  | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 70.68%  |
| AMD    | 73        | 29.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 3.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 2.8%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 2.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 2.4%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 2.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 2%      |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 2%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2%      |
| Intel Core i3-4030U CPU @ 1.90GHz             | 4         | 1.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.6%    |
| Intel 12th Gen Core i7-12700H                 | 4         | 1.6%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.2%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 3         | 1.2%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.2%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.2%    |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 1.2%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.2%    |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 1.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.2%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.2%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.8%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.8%    |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 2         | 0.8%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.8%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.8%    |
| Intel 13th Gen Core i7-13700H                 | 2         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 65        | 26.1%   |
| Intel Core i5           | 44        | 17.67%  |
| Other                   | 34        | 13.65%  |
| AMD Ryzen 5             | 31        | 12.45%  |
| AMD Ryzen 7             | 23        | 9.24%   |
| Intel Core i3           | 14        | 5.62%   |
| Intel Celeron           | 9         | 3.61%   |
| AMD Ryzen 9             | 8         | 3.21%   |
| Intel Pentium           | 4         | 1.61%   |
| Intel Core 2 Duo        | 4         | 1.61%   |
| AMD A6                  | 3         | 1.2%    |
| AMD A10                 | 2         | 0.8%    |
| Intel Pentium Dual-Core | 1         | 0.4%    |
| Intel Core 2 Extreme    | 1         | 0.4%    |
| Intel Atom              | 1         | 0.4%    |
| AMD Ryzen 5 PRO         | 1         | 0.4%    |
| AMD Ryzen 3             | 1         | 0.4%    |
| AMD FX                  | 1         | 0.4%    |
| AMD E                   | 1         | 0.4%    |
| AMD A4                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 87        | 34.8%   |
| 2      | 74        | 29.6%   |
| 6      | 40        | 16%     |
| 8      | 35        | 14%     |
| 14     | 8         | 3.2%    |
| 12     | 3         | 1.2%    |
| 10     | 2         | 0.8%    |
| 1      | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 249       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 224       | 89.96%  |
| 1      | 25        | 10.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 249       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 27.17%  |
| 0x0a50000c | 17        | 6.69%   |
| 0xa0652    | 12        | 4.72%   |
| 0x40651    | 11        | 4.33%   |
| 0x906ea    | 8         | 3.15%   |
| 0x906a3    | 8         | 3.15%   |
| 0x306a9    | 8         | 3.15%   |
| 0x206a7    | 8         | 3.15%   |
| 0x906e9    | 7         | 2.76%   |
| 0x806c1    | 7         | 2.76%   |
| 0x08600104 | 7         | 2.76%   |
| 0x08108109 | 7         | 2.76%   |
| 0x08608103 | 6         | 2.36%   |
| 0x08600106 | 6         | 2.36%   |
| 0x806d1    | 5         | 1.97%   |
| 0x506e3    | 5         | 1.97%   |
| 0x306c3    | 5         | 1.97%   |
| 0x806e9    | 4         | 1.57%   |
| 0x406e3    | 4         | 1.57%   |
| 0x0a50000d | 4         | 1.57%   |
| 0x0a404102 | 4         | 1.57%   |
| 0x806ea    | 3         | 1.18%   |
| 0x10676    | 3         | 1.18%   |
| 0x806ec    | 2         | 0.79%   |
| 0x706e5    | 2         | 0.79%   |
| 0x306d4    | 2         | 0.79%   |
| 0x30678    | 2         | 0.79%   |
| 0x1067a    | 2         | 0.79%   |
| 0x0a404101 | 2         | 0.79%   |
| 0x08108102 | 2         | 0.79%   |
| 0x0810100b | 2         | 0.79%   |
| 0x08101007 | 2         | 0.79%   |
| 0x06006110 | 2         | 0.79%   |
| 0xa0655    | 1         | 0.39%   |
| 0x906ed    | 1         | 0.39%   |
| 0x706a1    | 1         | 0.39%   |
| 0x506c9    | 1         | 0.39%   |
| 0x30661    | 1         | 0.39%   |
| 0x20655    | 1         | 0.39%   |
| 0x20652    | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 16.47%  |
| Haswell          | 29        | 11.65%  |
| Zen 3            | 21        | 8.43%   |
| CometLake        | 16        | 6.43%   |
| Zen 2            | 15        | 6.02%   |
| Unknown          | 15        | 6.02%   |
| TigerLake        | 14        | 5.62%   |
| Skylake          | 14        | 5.62%   |
| Alderlake Hybrid | 12        | 4.82%   |
| SandyBridge      | 11        | 4.42%   |
| Zen+             | 9         | 3.61%   |
| Icelake          | 9         | 3.61%   |
| IvyBridge        | 8         | 3.21%   |
| Zen              | 6         | 2.41%   |
| Penryn           | 6         | 2.41%   |
| Silvermont       | 4         | 1.61%   |
| Goldmont plus    | 4         | 1.61%   |
| Excavator        | 3         | 1.2%    |
| Broadwell        | 3         | 1.2%    |
| Westmere         | 2         | 0.8%    |
| Steamroller      | 1         | 0.4%    |
| Puma             | 1         | 0.4%    |
| Piledriver       | 1         | 0.4%    |
| Jaguar           | 1         | 0.4%    |
| Goldmont         | 1         | 0.4%    |
| Bonnell          | 1         | 0.4%    |
| Bobcat           | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 159       | 42.4%   |
| Nvidia | 129       | 34.4%   |
| AMD    | 87        | 23.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 19        | 4.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 18        | 4.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 16        | 4.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 13        | 3.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 13        | 3.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 12        | 3.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 11        | 2.85%   |
| AMD Renoir                                                                    | 11        | 2.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 10        | 2.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 9         | 2.33%   |
| Intel HD Graphics 530                                                         | 8         | 2.07%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 8         | 2.07%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 7         | 1.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 7         | 1.81%   |
| Nvidia TU117M                                                                 | 7         | 1.81%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 7         | 1.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 6         | 1.55%   |
| Intel UHD Graphics 620                                                        | 6         | 1.55%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 1.55%   |
| AMD Rembrandt [Radeon 680M]                                                   | 6         | 1.55%   |
| AMD Lucienne                                                                  | 6         | 1.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 1.3%    |
| Intel HD Graphics 630                                                         | 5         | 1.3%    |
| Intel HD Graphics 620                                                         | 5         | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 1.3%    |
| Nvidia GM107M [GeForce GTX 960M]                                              | 4         | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 4         | 1.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 1.04%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 0.78%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 0.78%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 0.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 3         | 0.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 3         | 0.78%   |
| Intel HD Graphics 5500                                                        | 3         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.78%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                       | 3         | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 3         | 0.78%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 3         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 86        | 34.54%  |
| 1 x Intel          | 58        | 23.29%  |
| 1 x AMD            | 41        | 16.47%  |
| AMD + Nvidia       | 25        | 10.04%  |
| 1 x Nvidia         | 16        | 6.43%   |
| Intel + AMD        | 12        | 4.82%   |
| 2 x AMD            | 9         | 3.61%   |
| Other              | 1         | 0.4%    |
| Intel + 2 x Nvidia | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 145       | 58%     |
| Proprietary | 103       | 41.2%   |
| Unknown     | 2         | 0.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 57.94%  |
| 0.01-0.5   | 40        | 15.87%  |
| 1.01-2.0   | 24        | 9.52%   |
| 0.51-1.0   | 17        | 6.75%   |
| 3.01-4.0   | 9         | 3.57%   |
| 5.01-6.0   | 7         | 2.78%   |
| 7.01-8.0   | 6         | 2.38%   |
| 8.01-16.0  | 3         | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 57        | 19.26%  |
| BOE                     | 42        | 14.19%  |
| Chimei Innolux          | 39        | 13.18%  |
| LG Display              | 38        | 12.84%  |
| Samsung Electronics     | 26        | 8.78%   |
| PANDA                   | 15        | 5.07%   |
| Apple                   | 9         | 3.04%   |
| Sharp                   | 8         | 2.7%    |
| Hewlett-Packard         | 6         | 2.03%   |
| Goldstar                | 6         | 2.03%   |
| MSI                     | 5         | 1.69%   |
| Dell                    | 5         | 1.69%   |
| Chi Mei Optoelectronics | 4         | 1.35%   |
| ViewSonic               | 3         | 1.01%   |
| InfoVision              | 3         | 1.01%   |
| Acer                    | 3         | 1.01%   |
| Vizio                   | 2         | 0.68%   |
| TMX                     | 2         | 0.68%   |
| Philips                 | 2         | 0.68%   |
| Eizo                    | 2         | 0.68%   |
| CSO                     | 2         | 0.68%   |
| AOC                     | 2         | 0.68%   |
| ___                     | 1         | 0.34%   |
| XUE                     | 1         | 0.34%   |
| VIE                     | 1         | 0.34%   |
| Valve                   | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| Ruijiang                | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| MLT                     | 1         | 0.34%   |
| Lenovo                  | 1         | 0.34%   |
| HKC                     | 1         | 0.34%   |
| GAOMON                  | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |
| Ancor Communications    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 5         | 1.69%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 4         | 1.35%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch     | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 3         | 1.01%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 2         | 0.68%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                   | 2         | 0.68%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                   | 2         | 0.68%   |
| LG Display LCD Monitor LGD0738 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 2         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 2         | 0.68%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                        | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch           | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 2         | 0.68%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                     | 2         | 0.68%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.68%   |
| ___ LCDTV16 ___9000 1360x768                                              | 1         | 0.34%   |
| XUE HDMI XUE1600 1920x1200 360x190mm 16.0-inch                            | 1         | 0.34%   |
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                       | 1         | 0.34%   |
| Vizio E320fi-B2 VIZ1005 1920x1080 477x268mm 21.5-inch                     | 1         | 0.34%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch                | 1         | 0.34%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch             | 1         | 0.34%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch             | 1         | 0.34%   |
| VIE C78 VIEE003 1920x1080 600x330mm 27.0-inch                             | 1         | 0.34%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.34%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                          | 1         | 0.34%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                   | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 148       | 55.02%  |
| 1366x768 (WXGA)    | 52        | 19.33%  |
| 3840x2160 (4K)     | 12        | 4.46%   |
| 2560x1440 (QHD)    | 8         | 2.97%   |
| 1920x1200 (WUXGA)  | 8         | 2.97%   |
| 2560x1600          | 7         | 2.6%    |
| 2880x1800          | 4         | 1.49%   |
| 1440x900 (WXGA+)   | 4         | 1.49%   |
| 1280x800 (WXGA)    | 4         | 1.49%   |
| 3840x2400          | 2         | 0.74%   |
| 2560x1080          | 2         | 0.74%   |
| 2240x1400          | 2         | 0.74%   |
| 1680x1050 (WSXGA+) | 2         | 0.74%   |
| 1600x900 (HD+)     | 2         | 0.74%   |
| 1360x768           | 2         | 0.74%   |
| 800x1280           | 1         | 0.37%   |
| 3456x2160          | 1         | 0.37%   |
| 3440x1440          | 1         | 0.37%   |
| 3200x2000          | 1         | 0.37%   |
| 3200x1800 (QHD+)   | 1         | 0.37%   |
| 2520x1680          | 1         | 0.37%   |
| 1600x2560          | 1         | 0.37%   |
| 1280x960           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 142       | 48.14%  |
| 17      | 30        | 10.17%  |
| 13      | 28        | 9.49%   |
| 14      | 21        | 7.12%   |
| 23      | 12        | 4.07%   |
| 16      | 11        | 3.73%   |
| 27      | 10        | 3.39%   |
| 31      | 8         | 2.71%   |
| 24      | 7         | 2.37%   |
| 34      | 3         | 1.02%   |
| 18      | 3         | 1.02%   |
| 72      | 2         | 0.68%   |
| 21      | 2         | 0.68%   |
| 11      | 2         | 0.68%   |
| Unknown | 2         | 0.68%   |
| 86      | 1         | 0.34%   |
| 84      | 1         | 0.34%   |
| 69      | 1         | 0.34%   |
| 48      | 1         | 0.34%   |
| 43      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 20      | 1         | 0.34%   |
| 19      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |
| 8       | 1         | 0.34%   |
| 7       | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 190       | 64.85%  |
| 351-400     | 33        | 11.26%  |
| 501-600     | 28        | 9.56%   |
| 201-300     | 14        | 4.78%   |
| 601-700     | 9         | 3.07%   |
| 401-500     | 6         | 2.05%   |
| 1501-2000   | 4         | 1.37%   |
| 701-800     | 2         | 0.68%   |
| Unknown     | 2         | 0.68%   |
| 801-900     | 1         | 0.34%   |
| 101-200     | 1         | 0.34%   |
| 1001-1500   | 1         | 0.34%   |
| 901-1000    | 1         | 0.34%   |
| 1-100       | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 212       | 83.14%  |
| 16/10 | 35        | 13.73%  |
| 21/9  | 3         | 1.18%   |
| 5/4   | 2         | 0.78%   |
| 3/2   | 1         | 0.39%   |
| 0.67  | 1         | 0.39%   |
| 0.62  | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 144       | 48.98%  |
| 81-90          | 45        | 15.31%  |
| 121-130        | 27        | 9.18%   |
| 201-250        | 14        | 4.76%   |
| 351-500        | 11        | 3.74%   |
| 301-350        | 10        | 3.4%    |
| 111-120        | 9         | 3.06%   |
| 251-300        | 6         | 2.04%   |
| More than 1000 | 5         | 1.7%    |
| 71-80          | 4         | 1.36%   |
| 141-150        | 4         | 1.36%   |
| 151-200        | 3         | 1.02%   |
| 131-140        | 3         | 1.02%   |
| 51-60          | 2         | 0.68%   |
| 1-40           | 2         | 0.68%   |
| Unknown        | 2         | 0.68%   |
| 61-70          | 1         | 0.34%   |
| 41-50          | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 149       | 51.74%  |
| 101-120       | 56        | 19.44%  |
| 51-100        | 42        | 14.58%  |
| 161-240       | 21        | 7.29%   |
| More than 240 | 13        | 4.51%   |
| 1-50          | 5         | 1.74%   |
| Unknown       | 2         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 193       | 76.89%  |
| 2     | 48        | 19.12%  |
| 0     | 6         | 2.39%   |
| 3     | 4         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 151       | 37.19%  |
| Intel                           | 136       | 33.5%   |
| Qualcomm Atheros                | 39        | 9.61%   |
| Broadcom                        | 25        | 6.16%   |
| MediaTek                        | 16        | 3.94%   |
| Samsung Electronics             | 4         | 0.99%   |
| Broadcom Limited                | 4         | 0.99%   |
| ASIX Electronics                | 4         | 0.99%   |
| Xiaomi                          | 3         | 0.74%   |
| Nvidia                          | 3         | 0.74%   |
| Sierra Wireless                 | 2         | 0.49%   |
| Ralink                          | 2         | 0.49%   |
| Qualcomm Atheros Communications | 2         | 0.49%   |
| Qualcomm                        | 2         | 0.49%   |
| Lenovo                          | 2         | 0.49%   |
| TP-Link                         | 1         | 0.25%   |
| Ralink Technology               | 1         | 0.25%   |
| Panasonic (Matsushita)          | 1         | 0.25%   |
| OPPO Electronics                | 1         | 0.25%   |
| Motorola PCS                    | 1         | 0.25%   |
| Microsoft                       | 1         | 0.25%   |
| Marvell Technology Group        | 1         | 0.25%   |
| JMicron Technology              | 1         | 0.25%   |
| Google                          | 1         | 0.25%   |
| ASUSTek Computer                | 1         | 0.25%   |
| Afatech                         | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106       | 22.8%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 4.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 3.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.58%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 2.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 2.37%   |
| Intel Wireless 7260                                               | 9         | 1.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 1.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.72%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.72%   |
| Intel Wireless 8260                                               | 8         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.29%   |
| Intel Wireless 7265                                               | 6         | 1.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.65%   |
| Intel Wireless-AC 9260                                            | 3         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 51.97%  |
| Realtek Semiconductor           | 40        | 15.75%  |
| Qualcomm Atheros                | 30        | 11.81%  |
| Broadcom                        | 22        | 8.66%   |
| MediaTek                        | 16        | 6.3%    |
| Broadcom Limited                | 3         | 1.18%   |
| Sierra Wireless                 | 2         | 0.79%   |
| Ralink                          | 2         | 0.79%   |
| Qualcomm Atheros Communications | 2         | 0.79%   |
| TP-Link                         | 1         | 0.39%   |
| Ralink Technology               | 1         | 0.39%   |
| Panasonic (Matsushita)          | 1         | 0.39%   |
| Microsoft                       | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 19        | 7.48%   |
| Intel Comet Lake PCH CNVi WiFi                                | 15        | 5.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 13        | 5.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 12        | 4.72%   |
| Intel Wi-Fi 6 AX201                                           | 12        | 4.72%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 11        | 4.33%   |
| Intel Wireless 7260                                           | 9         | 3.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 3.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 8         | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 3.15%   |
| Intel Wireless 8265 / 8275                                    | 8         | 3.15%   |
| Intel Wireless 8260                                           | 8         | 3.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 8         | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7         | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 7         | 2.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6         | 2.36%   |
| Intel Wireless 7265                                           | 6         | 2.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 6         | 2.36%   |
| Broadcom BCM43142 802.11b/g/n                                 | 6         | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 4         | 1.57%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 4         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.18%   |
| Intel Wireless-AC 9260                                        | 3         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.18%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 3         | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 2         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                  | 2         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 2         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 0.79%   |
| Intel Wireless 3160                                           | 2         | 0.79%   |
| Intel WiFi Link 5100                                          | 2         | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 2         | 0.79%   |
| Intel Centrino Advanced-N 6235                                | 2         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 2         | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.39%   |
| Sierra Wireless EM7455                                        | 1         | 0.39%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 134       | 64.42%  |
| Intel                    | 31        | 14.9%   |
| Qualcomm Atheros         | 13        | 6.25%   |
| Broadcom                 | 7         | 3.37%   |
| ASIX Electronics         | 4         | 1.92%   |
| Xiaomi                   | 3         | 1.44%   |
| Samsung Electronics      | 3         | 1.44%   |
| Nvidia                   | 3         | 1.44%   |
| Qualcomm                 | 2         | 0.96%   |
| Lenovo                   | 2         | 0.96%   |
| OPPO Electronics         | 1         | 0.48%   |
| Motorola PCS             | 1         | 0.48%   |
| Marvell Technology Group | 1         | 0.48%   |
| JMicron Technology       | 1         | 0.48%   |
| Google                   | 1         | 0.48%   |
| Broadcom Limited         | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106       | 50.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.91%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.44%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.44%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.96%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.96%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.48%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.48%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.48%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.48%   |
| Qualcomm MDM9207-MTP _SN:F0A6D599                                 | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.48%   |
| OPPO 8                                                            | 1         | 0.48%   |
| Motorola PCS moto g51 5G                                          | 1         | 0.48%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 55.16%  |
| Ethernet | 198       | 44.39%  |
| Modem    | 1         | 0.22%   |
| Unknown  | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 74.44%  |
| Ethernet | 68        | 25.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 179       | 71.89%  |
| 1     | 66        | 26.51%  |
| 0     | 3         | 1.2%    |
| 3     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 72.8%   |
| Yes  | 68        | 27.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 56.19%  |
| Realtek Semiconductor           | 27        | 11.95%  |
| Qualcomm Atheros Communications | 13        | 5.75%   |
| Lite-On Technology              | 12        | 5.31%   |
| IMC Networks                    | 12        | 5.31%   |
| Foxconn / Hon Hai               | 10        | 4.42%   |
| Broadcom                        | 9         | 3.98%   |
| Apple                           | 9         | 3.98%   |
| Ralink                          | 2         | 0.88%   |
| Toshiba                         | 1         | 0.44%   |
| Realtek                         | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |
| Foxconn International           | 1         | 0.44%   |
| Cambridge Silicon Radio         | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 39        | 17.26%  |
| Intel AX201 Bluetooth                             | 29        | 12.83%  |
| Realtek Bluetooth Radio                           | 21        | 9.29%   |
| Intel AX200 Bluetooth                             | 19        | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 16        | 7.08%   |
| Intel Bluetooth Device                            | 9         | 3.98%   |
| Intel AX210 Bluetooth                             | 8         | 3.54%   |
| Apple Bluetooth Host Controller                   | 8         | 3.54%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 2.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 5         | 2.21%   |
| IMC Networks Wireless_Device                      | 5         | 2.21%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 5         | 2.21%   |
| IMC Networks Bluetooth Radio                      | 4         | 1.77%   |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 1.33%   |
| Lite-On Bluetooth Device                          | 3         | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 3         | 1.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 2         | 0.88%   |
| Ralink RT3290 Bluetooth                           | 2         | 0.88%   |
| Lite-On Wireless_Device                           | 2         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 0.88%   |
| Lite-On Bluetooth Radio                           | 2         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 0.88%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 0.88%   |
| IMC Networks Bluetooth Device                     | 2         | 0.88%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 2         | 0.88%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth Device              | 2         | 0.88%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.44%   |
| Realtek Bluetooth Radio                           | 1         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth (AR3011)               | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.44%   |
| MediaTek Wireless_Device                          | 1         | 0.44%   |
| Lite-On BCM43142A0                                | 1         | 0.44%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.44%   |
| IMC Networks BCM20702A0                           | 1         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.44%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth       | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 173       | 47.4%   |
| Nvidia                 | 85        | 23.29%  |
| AMD                    | 82        | 22.47%  |
| C-Media Electronics    | 3         | 0.82%   |
| TTGK Technology        | 2         | 0.55%   |
| Sony                   | 2         | 0.55%   |
| Razer USA              | 2         | 0.55%   |
| Logitech               | 2         | 0.55%   |
| Lenovo                 | 2         | 0.55%   |
| Creative Technology    | 2         | 0.55%   |
| Tenx Technology        | 1         | 0.27%   |
| SteelSeries ApS        | 1         | 0.27%   |
| Samsung Electronics    | 1         | 0.27%   |
| Native Instruments     | 1         | 0.27%   |
| Hewlett-Packard        | 1         | 0.27%   |
| GN Netcom              | 1         | 0.27%   |
| Generalplus Technology | 1         | 0.27%   |
| Corsair                | 1         | 0.27%   |
| Blue Microphones       | 1         | 0.27%   |
| ASUSTek Computer       | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 62        | 13.78%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 27        | 6%      |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 4.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 3.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 3.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 3.56%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 3.56%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 3.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 2.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 2.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 1.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.56%   |
| Nvidia Audio device                                                        | 7         | 1.56%   |
| Intel CM238 HD Audio Controller                                            | 7         | 1.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 1.11%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.89%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.67%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.67%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.67%   |
| TTGK Technology Audio                                                      | 2         | 0.44%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 34.48%  |
| SK hynix            | 18        | 20.69%  |
| Micron Technology   | 15        | 17.24%  |
| Kingston            | 5         | 5.75%   |
| Crucial             | 3         | 3.45%   |
| Unknown (ABCD)      | 2         | 2.3%    |
| Team                | 2         | 2.3%    |
| G.Skill             | 2         | 2.3%    |
| Corsair             | 2         | 2.3%    |
| A-DATA Technology   | 2         | 2.3%    |
| Unknown             | 1         | 1.15%   |
| Transcend           | 1         | 1.15%   |
| Nanya Technology    | 1         | 1.15%   |
| Elpida              | 1         | 1.15%   |
| AMD                 | 1         | 1.15%   |
| Unknown             | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 5.43%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 2.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.17%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 2.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.17%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 2         | 2.17%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 2.17%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 2.17%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 2.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 2.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.09%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.09%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 1.09%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.09%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.09%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.09%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 1.09%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.09%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.09%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 43        | 61.43%  |
| DDR3    | 10        | 14.29%  |
| DDR5    | 8         | 11.43%  |
| LPDDR4  | 7         | 10%     |
| DDR2    | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 88.73%  |
| Row Of Chips | 8         | 11.27%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 38        | 49.35%  |
| 4096  | 16        | 20.78%  |
| 16384 | 14        | 18.18%  |
| 32768 | 5         | 6.49%   |
| 2048  | 4         | 5.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 25        | 34.25%  |
| 2667  | 16        | 21.92%  |
| 1600  | 8         | 10.96%  |
| 4800  | 5         | 6.85%   |
| 2400  | 4         | 5.48%   |
| 5600  | 3         | 4.11%   |
| 4267  | 2         | 2.74%   |
| 3266  | 2         | 2.74%   |
| 1333  | 2         | 2.74%   |
| 6400  | 1         | 1.37%   |
| 4266  | 1         | 1.37%   |
| 3333  | 1         | 1.37%   |
| 2133  | 1         | 1.37%   |
| 1334  | 1         | 1.37%   |
| 975   | 1         | 1.37%   |

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
| Chicony Electronics                    | 51        | 22.77%  |
| IMC Networks                           | 31        | 13.84%  |
| Realtek Semiconductor                  | 16        | 7.14%   |
| Sunplus Innovation Technology          | 13        | 5.8%    |
| Bison Electronics                      | 13        | 5.8%    |
| Quanta                                 | 12        | 5.36%   |
| Syntek                                 | 11        | 4.91%   |
| Microdia                               | 11        | 4.91%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.46%   |
| Apple                                  | 10        | 4.46%   |
| Luxvisions Innotech Limited            | 6         | 2.68%   |
| Logitech                               | 6         | 2.68%   |
| Lite-On Technology                     | 6         | 2.68%   |
| Suyin                                  | 5         | 2.23%   |
| Sonix Technology                       | 5         | 2.23%   |
| Silicon Motion                         | 3         | 1.34%   |
| SunplusIT                              | 2         | 0.89%   |
| Samsung Electronics                    | 2         | 0.89%   |
| Intel                                  | 2         | 0.89%   |
| Acer                                   | 2         | 0.89%   |
| Z-Star Microelectronics                | 1         | 0.45%   |
| Tobii Technology AB                    | 1         | 0.45%   |
| Shine-optics                           | 1         | 0.45%   |
| Importek                               | 1         | 0.45%   |
| HRY                                    | 1         | 0.45%   |
| Google                                 | 1         | 0.45%   |
| Goodong Industry                       | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 6.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 13        | 5.78%   |
| Syntek Integrated Camera                            | 8         | 3.56%   |
| Realtek Integrated_Webcam_HD                        | 8         | 3.56%   |
| IMC Networks Integrated Camera                      | 8         | 3.56%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 3.11%   |
| Chicony HD WebCam                                   | 6         | 2.67%   |
| Microdia Integrated_Webcam_HD                       | 5         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 2.22%   |
| Bison Integrated Camera                             | 4         | 1.78%   |
| Bison HD Webcam                                     | 4         | 1.78%   |
| Apple FaceTime HD Camera                            | 4         | 1.78%   |
| Sunplus HD WebCam                                   | 3         | 1.33%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.33%   |
| Realtek USB Camera                                  | 3         | 1.33%   |
| Quanta HD User Facing                               | 3         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.33%   |
| Lite-On HP HD Webcam                                | 3         | 1.33%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.33%   |
| Chicony USB 2.0 Camera                              | 3         | 1.33%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.33%   |
| Chicony HP Truevision HD                            | 3         | 1.33%   |
| Chicony HD User Facing                              | 3         | 1.33%   |
| Apple Built-in iSight                               | 3         | 1.33%   |
| Syntek EasyCamera                                   | 2         | 0.89%   |
| SunplusIT MTD camera                                | 2         | 0.89%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.89%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 0.89%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.89%   |
| Quanta HD Webcam                                    | 2         | 0.89%   |
| Microdia USB 2.0 Camera                             | 2         | 0.89%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.89%   |
| Logitech HD Pro Webcam C920                         | 2         | 0.89%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 0.89%   |
| Lite-On HP HD Camera                                | 2         | 0.89%   |
| Intel RealSense 3D Camera (Front F200)              | 2         | 0.89%   |
| Chicony USB2.0 Camera                               | 2         | 0.89%   |
| Chicony EasyCamera                                  | 2         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 13        | 37.14%  |
| Synaptics                          | 8         | 22.86%  |
| Shenzhen Goodix Technology         | 7         | 20%     |
| Elan Microelectronics              | 4         | 11.43%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 5.71%   |
| Focal-systems.Corp                 | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 22.86%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 5.71%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 5.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 5.71%   |
| Elan ELAN:Fingerprint                                           | 2         | 5.71%   |
| Elan ELAN:ARM-M4                                                | 2         | 5.71%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 2.86%   |
| Synaptics WBDI Device                                           | 1         | 2.86%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.86%   |
| Synaptics  WBDI                                                 | 1         | 2.86%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 2.86%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 167       | 66.01%  |
| 1     | 69        | 27.27%  |
| 2     | 15        | 5.93%   |
| 3     | 2         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 32.08%  |
| Graphics card            | 27        | 25.47%  |
| Multimedia controller    | 24        | 22.64%  |
| Net/wireless             | 14        | 13.21%  |
| Bluetooth                | 3         | 2.83%   |
| Modem                    | 1         | 0.94%   |
| Communication controller | 1         | 0.94%   |
| Chipcard                 | 1         | 0.94%   |
| Camera                   | 1         | 0.94%   |

