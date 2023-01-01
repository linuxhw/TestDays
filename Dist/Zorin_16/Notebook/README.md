Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 1910

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Lenovo        | G500 20236                  | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Dell          | Latitude 7490               | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Gateway       | NV59C                       | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | Studio 1558                 | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| HP            | Notebook                    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Dell          | Latitude E6500              | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Dell          | Latitude E6520              | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Alienware     | 18                          | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| Ematic        | EWT118                      | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| AZW           | Z83-V                       | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| Toshiba       | Satellite P200              | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| HP            | 15                          | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Pavilion g7                 | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| Apple         | MacBookAir7,2               | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude E5440              | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| HP            | EliteBook 6930p             | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| Google        | Kasumi                      | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Ematic        | EWT118                      | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Medion        | E7419 MD60990               | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| Acer          | Peppy                       | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| Dell          | G15 5510                    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | ThinkPad T420 4236VTQ       | [1ea6046182](https://linux-hardware.org/?probe=1ea6046182) | Aug 02, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [b4bee86632](https://linux-hardware.org/?probe=b4bee86632) | Aug 02, 2022 |
| HP            | Laptop 14-dq4xxx            | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | Latitude E7450              | [894a489a03](https://linux-hardware.org/?probe=894a489a03) | Jul 30, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Dell          | Latitude E7450              | [4a277d4cee](https://linux-hardware.org/?probe=4a277d4cee) | Jul 27, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| HP            | Unknown                     | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| HP            | ProBook 4540s               | [a2d1e2fd68](https://linux-hardware.org/?probe=a2d1e2fd68) | Jul 22, 2022 |
| HP            | Compaq 420                  | [913795a620](https://linux-hardware.org/?probe=913795a620) | Jul 21, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Dell          | Inspiron 3541               | [cb0f9c95d2](https://linux-hardware.org/?probe=cb0f9c95d2) | Jul 20, 2022 |
| Toshiba       | Satellite L655              | [e332607406](https://linux-hardware.org/?probe=e332607406) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Google        | Butterfly                   | [ed6aa75ba5](https://linux-hardware.org/?probe=ed6aa75ba5) | Jul 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| Apple         | MacBookPro12,1              | [4a5f294565](https://linux-hardware.org/?probe=4a5f294565) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| Acer          | NC-A315-41G-R88F            | [8ffe1077fd](https://linux-hardware.org/?probe=8ffe1077fd) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| ASUSTek       | X751MA                      | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| Toshiba       | TECRA S11                   | [26ed071525](https://linux-hardware.org/?probe=26ed071525) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| AMI           | Unknown                     | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Alienware     | x15 R1                      | [95ee5b34a7](https://linux-hardware.org/?probe=95ee5b34a7) | Jul 14, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HP            | Unknown                     | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | ProBook 455 G1              | [a0dd163643](https://linux-hardware.org/?probe=a0dd163643) | Jul 14, 2022 |
| HP            | Laptop 15-dw3xxx            | [09e66aef7e](https://linux-hardware.org/?probe=09e66aef7e) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | Laptop 15-dw3xxx            | [e974774285](https://linux-hardware.org/?probe=e974774285) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| HP            | ProBook 640 G1              | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| MSI           | Creator 15 A10SET           | [d90f2aec1b](https://linux-hardware.org/?probe=d90f2aec1b) | Jul 10, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8a02619147](https://linux-hardware.org/?probe=8a02619147) | Jul 10, 2022 |
| eMachines     | E720 V1.06                  | [ec23637bd5](https://linux-hardware.org/?probe=ec23637bd5) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [1fbb699502](https://linux-hardware.org/?probe=1fbb699502) | Jul 09, 2022 |
| Dell          | Latitude 5400               | [46ce7cf7fe](https://linux-hardware.org/?probe=46ce7cf7fe) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [c74f3711f3](https://linux-hardware.org/?probe=c74f3711f3) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T400 2768GB4       | [498bb4a509](https://linux-hardware.org/?probe=498bb4a509) | Jul 08, 2022 |
| Acer          | Aspire 5755G                | [37aff6bb24](https://linux-hardware.org/?probe=37aff6bb24) | Jul 08, 2022 |
| HP            | EliteBook 745 G6            | [159ebeaa5e](https://linux-hardware.org/?probe=159ebeaa5e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| HP            | Mini 110-3100               | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Samsung       | 550XDA                      | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| Acer          | Aspire 5755G                | [0dcb64ed5f](https://linux-hardware.org/?probe=0dcb64ed5f) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [167fe0c2d1](https://linux-hardware.org/?probe=167fe0c2d1) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [59923a9781](https://linux-hardware.org/?probe=59923a9781) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [b8e2b7b6bd](https://linux-hardware.org/?probe=b8e2b7b6bd) | Jul 05, 2022 |
| Lenovo        | S21e-20 80M4                | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| Packard Be... | H17HV                       | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Dell          | Inspiron 5520               | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Google        | Candy                       | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| HP            | Laptop 15-db0xxx            | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Toshiba       | Satellite C870-1C2          | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| Global Dis... | W11651                      | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| Dell          | Latitude E6540              | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Dell          | Precision M4700             | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Positivo      | Q464C                       | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Positivo      | Q464C                       | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | Pavilion 17                 | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Samsung       | 600B4B/600B5B               | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| Dell          | Inspiron 15-5578            | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| HP            | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| ASUSTek       | X450LD                      | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| Dell          | Latitude E6510              | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| Dell          | Latitude D630               | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Dell          | Inspiron 5423               | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| HP            | ZBook 15 G2                 | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| HP            | Pavilion g4                 | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |
| HP            | EliteBook 2570p             | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Unknown       | Unknown                     | [bb968f8b83](https://linux-hardware.org/?probe=bb968f8b83) | May 16, 2022 |
| Dell          | Vostro 3500                 | [b95339f19d](https://linux-hardware.org/?probe=b95339f19d) | May 15, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| HP            | ProBook 450 G1              | [c9da66f0e8](https://linux-hardware.org/?probe=c9da66f0e8) | May 15, 2022 |
| Thomson       | NEO14SBK                    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| ASUSTek       | N80Vb                       | [74cb7e076b](https://linux-hardware.org/?probe=74cb7e076b) | May 13, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| HP            | OMEN by Laptop              | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| Lenovo        | ThinkPad T61 7661V72        | [3d40fb11e8](https://linux-hardware.org/?probe=3d40fb11e8) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [048951833f](https://linux-hardware.org/?probe=048951833f) | May 13, 2022 |
| Dell          | Vostro 3500                 | [3824ac02d2](https://linux-hardware.org/?probe=3824ac02d2) | May 12, 2022 |
| Dell          | Latitude E6540              | [422c7a9209](https://linux-hardware.org/?probe=422c7a9209) | May 11, 2022 |
| Acer          | Aspire E1-571               | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| ASUSTek       | X200CA                      | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| HP            | Laptop 15-db0xxx            | [42f2a531b5](https://linux-hardware.org/?probe=42f2a531b5) | May 09, 2022 |
| HP            | Pavilion Notebook           | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| HP            | Pavilion dv7                | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| ASUSTek       | G74Sx                       | [0ed6635d41](https://linux-hardware.org/?probe=0ed6635d41) | May 09, 2022 |
| ASUSTek       | U43F                        | [ad1a88d120](https://linux-hardware.org/?probe=ad1a88d120) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | X200CA                      | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| ASUSTek       | G74Sx                       | [44f45ca8ea](https://linux-hardware.org/?probe=44f45ca8ea) | May 07, 2022 |
| Toshiba       | TECRA A50-E                 | [29935ac4c6](https://linux-hardware.org/?probe=29935ac4c6) | May 06, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Notebook                    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Google        | Candy                       | [2c41b3e736](https://linux-hardware.org/?probe=2c41b3e736) | May 04, 2022 |
| ASUSTek       | E200HA                      | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| ASUSTek       | X550CL                      | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| HP            | Pavilion dv6                | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [4e21e1d28e](https://linux-hardware.org/?probe=4e21e1d28e) | May 02, 2022 |
| ASUSTek       | X550CL                      | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Lenovo        | Yoga 2 13 20344             | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Acer          | Aspire 5741                 | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Acer          | V5-171                      | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| Acer          | V5-171                      | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| ASUSTek       | X411UN                      | [c864c65ec1](https://linux-hardware.org/?probe=c864c65ec1) | Apr 29, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [c4021bd208](https://linux-hardware.org/?probe=c4021bd208) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| HP            | 15                          | [63e5782bc3](https://linux-hardware.org/?probe=63e5782bc3) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| HP            | Compaq Presario CQ70        | [ebfb06702f](https://linux-hardware.org/?probe=ebfb06702f) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [f940bea00c](https://linux-hardware.org/?probe=f940bea00c) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [b1594df62f](https://linux-hardware.org/?probe=b1594df62f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [e1731ce27f](https://linux-hardware.org/?probe=e1731ce27f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [a681022e30](https://linux-hardware.org/?probe=a681022e30) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | [127dd69ddf](https://linux-hardware.org/?probe=127dd69ddf) | Apr 25, 2022 |
| HP            | Notebook                    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Samsung       | 550XCJ/550XCR               | [4f5bd4cb03](https://linux-hardware.org/?probe=4f5bd4cb03) | Apr 23, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [f57f07921b](https://linux-hardware.org/?probe=f57f07921b) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [883c933519](https://linux-hardware.org/?probe=883c933519) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [9b960298ef](https://linux-hardware.org/?probe=9b960298ef) | Apr 23, 2022 |
| Dell          | Latitude E5440              | [91744e20c7](https://linux-hardware.org/?probe=91744e20c7) | Apr 22, 2022 |
| Google        | Candy                       | [5a31bd1da8](https://linux-hardware.org/?probe=5a31bd1da8) | Apr 22, 2022 |
| Gateway       | NV59C                       | [c7f652c9f8](https://linux-hardware.org/?probe=c7f652c9f8) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| HP            | Laptop 15s-du2xxx           | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Acer          | Nitro AN515-44              | [5549666ce7](https://linux-hardware.org/?probe=5549666ce7) | Apr 20, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| HP            | Notebook                    | [f6d84934cd](https://linux-hardware.org/?probe=f6d84934cd) | Apr 19, 2022 |
| Dell          | Inspiron M5010              | [eff0448051](https://linux-hardware.org/?probe=eff0448051) | Apr 19, 2022 |
| Acer          | Aspire A515-54              | [c1a060dd90](https://linux-hardware.org/?probe=c1a060dd90) | Apr 19, 2022 |
| Toshiba       | Satellite C870-1C2          | [c8917c947b](https://linux-hardware.org/?probe=c8917c947b) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab4247484f](https://linux-hardware.org/?probe=ab4247484f) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [3bf424720c](https://linux-hardware.org/?probe=3bf424720c) | Apr 18, 2022 |
| ASUSTek       | K73BR                       | [596b3b2df6](https://linux-hardware.org/?probe=596b3b2df6) | Apr 18, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| Lenovo        | G40-80 80JE                 | [28c58e21e0](https://linux-hardware.org/?probe=28c58e21e0) | Apr 16, 2022 |
| Lenovo        | ThinkPad E520 11433BU       | [eb10b5f739](https://linux-hardware.org/?probe=eb10b5f739) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| Dell          | Inspiron N5110              | [5ae4706be7](https://linux-hardware.org/?probe=5ae4706be7) | Apr 15, 2022 |
| Insignia      | NS-P89W6100 V1.0            | [dabc8a93a8](https://linux-hardware.org/?probe=dabc8a93a8) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c1273dfd07](https://linux-hardware.org/?probe=c1273dfd07) | Apr 15, 2022 |
| Toshiba       | Satellite P50t-A            | [f2eef93c50](https://linux-hardware.org/?probe=f2eef93c50) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Fujitsu       | LIFEBOOK S760               | [6cb98b4c28](https://linux-hardware.org/?probe=6cb98b4c28) | Apr 12, 2022 |
| Toshiba       | Satellite E55-A             | [dc9e2fd729](https://linux-hardware.org/?probe=dc9e2fd729) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [9a6b2ad9f9](https://linux-hardware.org/?probe=9a6b2ad9f9) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [574edf3e3b](https://linux-hardware.org/?probe=574edf3e3b) | Apr 11, 2022 |
| Framework     | Laptop                      | [14cf383f81](https://linux-hardware.org/?probe=14cf383f81) | Apr 09, 2022 |
| Lenovo        | Flex 2-15 20405             | [b7d6ae3171](https://linux-hardware.org/?probe=b7d6ae3171) | Apr 08, 2022 |
| HP            | Pavilion Notebook           | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [46bbc49e43](https://linux-hardware.org/?probe=46bbc49e43) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Toshiba       | Satellite L755              | [be86a2f36e](https://linux-hardware.org/?probe=be86a2f36e) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [0f8f2d9229](https://linux-hardware.org/?probe=0f8f2d9229) | Apr 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [5cc1a973d7](https://linux-hardware.org/?probe=5cc1a973d7) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| Dell          | Inspiron 1545               | [af6989215e](https://linux-hardware.org/?probe=af6989215e) | Apr 06, 2022 |
| Multilaser    | PC121                       | [f93e89718f](https://linux-hardware.org/?probe=f93e89718f) | Apr 05, 2022 |
| Multilaser    | PC121                       | [31f2c02434](https://linux-hardware.org/?probe=31f2c02434) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Medion        | S6417 MD99651               | [2911120bc0](https://linux-hardware.org/?probe=2911120bc0) | Apr 04, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| Dell          | Inspiron 1545               | [8e5b3df957](https://linux-hardware.org/?probe=8e5b3df957) | Apr 03, 2022 |
| Dell          | Inspiron 3185               | [17c6187b71](https://linux-hardware.org/?probe=17c6187b71) | Apr 03, 2022 |
| Lenovo        | ThinkPad T430 23473B2       | [aa0ad3f513](https://linux-hardware.org/?probe=aa0ad3f513) | Apr 03, 2022 |
| Toshiba       | BDB                         | [985b6a2865](https://linux-hardware.org/?probe=985b6a2865) | Apr 03, 2022 |
| HP            | Notebook                    | [e1af57dc16](https://linux-hardware.org/?probe=e1af57dc16) | Apr 02, 2022 |
| Apple         | MacBookAir5,1               | [d8657defc8](https://linux-hardware.org/?probe=d8657defc8) | Apr 02, 2022 |
| HP            | 240 G3                      | [3e6387008c](https://linux-hardware.org/?probe=3e6387008c) | Apr 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [4f09568c52](https://linux-hardware.org/?probe=4f09568c52) | Apr 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [e81da10444](https://linux-hardware.org/?probe=e81da10444) | Apr 01, 2022 |
| HP            | 255 G8 Notebook PC          | [1b1917729b](https://linux-hardware.org/?probe=1b1917729b) | Apr 01, 2022 |
| HP            | Pavilion dv6000 (GA443UA... | [b9a90b57c8](https://linux-hardware.org/?probe=b9a90b57c8) | Apr 01, 2022 |
| ASUSTek       | K55A                        | [71137b6a1e](https://linux-hardware.org/?probe=71137b6a1e) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [19aa2cf50d](https://linux-hardware.org/?probe=19aa2cf50d) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Acer          | Aspire ES1-572              | [bf6df72edf](https://linux-hardware.org/?probe=bf6df72edf) | Mar 29, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [a6218b029c](https://linux-hardware.org/?probe=a6218b029c) | Mar 29, 2022 |
| HP            | Pavilion dv3                | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| Acer          | Nitro AN515-44              | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Dell          | Precision M4800             | [1eacfc1ab5](https://linux-hardware.org/?probe=1eacfc1ab5) | Mar 27, 2022 |
| Acer          | Predator G9-792             | [4720698441](https://linux-hardware.org/?probe=4720698441) | Mar 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [09cccd4869](https://linux-hardware.org/?probe=09cccd4869) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [7bc7e689a4](https://linux-hardware.org/?probe=7bc7e689a4) | Mar 26, 2022 |
| Insyde        | GeminiLake                  | [44967ed898](https://linux-hardware.org/?probe=44967ed898) | Mar 26, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Toshiba       | Satellite S55t-C            | [0bebc02627](https://linux-hardware.org/?probe=0bebc02627) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Lenovo        | ThinkPad SL500 274677G      | [1fcd4e44f1](https://linux-hardware.org/?probe=1fcd4e44f1) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Positivo      | C14CU51                     | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| ASUSTek       | X405UA                      | [1895364071](https://linux-hardware.org/?probe=1895364071) | Mar 22, 2022 |
| Apple         | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Gateway       | NV59C                       | [ce722c3cc0](https://linux-hardware.org/?probe=ce722c3cc0) | Mar 22, 2022 |
| MSI           | CR643                       | [24e9c1fe40](https://linux-hardware.org/?probe=24e9c1fe40) | Mar 22, 2022 |
| ASUSTek       | G75VW                       | [202d109eb5](https://linux-hardware.org/?probe=202d109eb5) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [15a215fc17](https://linux-hardware.org/?probe=15a215fc17) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [f0915a2702](https://linux-hardware.org/?probe=f0915a2702) | Mar 22, 2022 |
| HP            | Laptop 15-db0xxx            | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| HP            | ENVY dv7                    | [b15a265c66](https://linux-hardware.org/?probe=b15a265c66) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a3859ab679](https://linux-hardware.org/?probe=a3859ab679) | Mar 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9323d5d425](https://linux-hardware.org/?probe=9323d5d425) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a2f09086d6](https://linux-hardware.org/?probe=a2f09086d6) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| HP            | Pavilion dv3                | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Apple         | MacBookPro10,1              | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3603330b59](https://linux-hardware.org/?probe=3603330b59) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [b2d732d46b](https://linux-hardware.org/?probe=b2d732d46b) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [6dbcdd388c](https://linux-hardware.org/?probe=6dbcdd388c) | Mar 18, 2022 |
| Dell          | Inspiron 7737               | [99852ed093](https://linux-hardware.org/?probe=99852ed093) | Mar 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [662aed3d5d](https://linux-hardware.org/?probe=662aed3d5d) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b3fc1a1d0f](https://linux-hardware.org/?probe=b3fc1a1d0f) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Toshiba       | Satellite C855              | [71d2d562d7](https://linux-hardware.org/?probe=71d2d562d7) | Mar 16, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [9aa148dba8](https://linux-hardware.org/?probe=9aa148dba8) | Mar 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [116bb6c003](https://linux-hardware.org/?probe=116bb6c003) | Mar 15, 2022 |
| Sony          | VGN-FW21E                   | [1dbc74cf43](https://linux-hardware.org/?probe=1dbc74cf43) | Mar 15, 2022 |
| Insyde        | i101c                       | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| Gigabyte      | P64V7                       | [13f2e44186](https://linux-hardware.org/?probe=13f2e44186) | Mar 15, 2022 |
| Toshiba       | Satellite C55-C             | [8fade33706](https://linux-hardware.org/?probe=8fade33706) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0755c3c4a6](https://linux-hardware.org/?probe=0755c3c4a6) | Mar 14, 2022 |
| Acer          | Aspire E5-571P              | [dd68b81b43](https://linux-hardware.org/?probe=dd68b81b43) | Mar 14, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| ASUSTek       | X550LC                      | [cb90a1c509](https://linux-hardware.org/?probe=cb90a1c509) | Mar 13, 2022 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [088d2bf23b](https://linux-hardware.org/?probe=088d2bf23b) | Mar 13, 2022 |
| HP            | Notebook                    | [2a7e60663b](https://linux-hardware.org/?probe=2a7e60663b) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| HP            | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 1000                        | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Lenovo        | V110-15IAP 80TG             | [5989c71041](https://linux-hardware.org/?probe=5989c71041) | Mar 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.11.0-38-generic       | 97        | 6.65%   |
| 5.11.0-27-generic       | 92        | 6.31%   |
| 5.15.0-46-generic       | 88        | 6.03%   |
| 5.15.0-52-generic       | 87        | 5.96%   |
| 5.15.0-56-generic       | 73        | 5%      |
| 5.13.0-30-generic       | 73        | 5%      |
| 5.11.0-37-generic       | 67        | 4.59%   |
| 5.11.0-40-generic       | 65        | 4.46%   |
| 5.11.0-41-generic       | 62        | 4.25%   |
| 5.13.0-39-generic       | 60        | 4.11%   |
| 5.11.0-34-generic       | 57        | 3.91%   |
| 5.11.0-43-generic       | 56        | 3.84%   |
| 5.15.0-48-generic       | 51        | 3.5%    |
| 5.13.0-44-generic       | 48        | 3.29%   |
| 5.13.0-40-generic       | 45        | 3.08%   |
| 5.15.0-53-generic       | 40        | 2.74%   |
| 5.13.0-35-generic       | 40        | 2.74%   |
| 5.13.0-28-generic       | 36        | 2.47%   |
| 5.15.0-41-generic       | 32        | 2.19%   |
| 5.13.0-52-generic       | 31        | 2.12%   |
| 5.13.0-27-generic       | 28        | 1.92%   |
| 5.11.0-46-generic       | 26        | 1.78%   |
| 5.13.0-41-generic       | 25        | 1.71%   |
| 5.11.0-36-generic       | 22        | 1.51%   |
| 5.15.0-43-generic       | 21        | 1.44%   |
| 5.13.0-51-generic       | 19        | 1.3%    |
| 5.11.0-44-generic       | 18        | 1.23%   |
| 5.13.0-37-generic       | 15        | 1.03%   |
| 5.13.0-48-generic       | 13        | 0.89%   |
| 5.15.0-50-generic       | 11        | 0.75%   |
| 5.11.0-25-generic       | 9         | 0.62%   |
| 5.8.0-53-generic        | 6         | 0.41%   |
| 5.8.0-59-generic        | 5         | 0.34%   |
| 5.8.0-55-generic        | 5         | 0.34%   |
| 5.8.0-50-generic        | 4         | 0.27%   |
| 5.14.0-1052-oem         | 2         | 0.14%   |
| 6.0.0-060000-generic    | 1         | 0.07%   |
| 5.8.0-63-generic        | 1         | 0.07%   |
| 5.8.0-49-generic        | 1         | 0.07%   |
| 5.4.180-0504180-generic | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 544       | 39.88%  |
| 5.13.0  | 404       | 29.62%  |
| 5.15.0  | 371       | 27.2%   |
| 5.8.0   | 22        | 1.61%   |
| 5.14.0  | 6         | 0.44%   |
| 5.16.0  | 2         | 0.15%   |
| 5.10.0  | 2         | 0.15%   |
| 6.0.0   | 1         | 0.07%   |
| 5.4.180 | 1         | 0.07%   |
| 5.19.9  | 1         | 0.07%   |
| 5.19.14 | 1         | 0.07%   |
| 5.19.12 | 1         | 0.07%   |
| 5.19.1  | 1         | 0.07%   |
| 5.19.0  | 1         | 0.07%   |
| 5.18.6  | 1         | 0.07%   |
| 5.18.15 | 1         | 0.07%   |
| 5.16.12 | 1         | 0.07%   |
| 5.15.49 | 1         | 0.07%   |
| 5.15.24 | 1         | 0.07%   |
| 5.13.18 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 544       | 39.88%  |
| 5.13    | 405       | 29.69%  |
| 5.15    | 373       | 27.35%  |
| 5.8     | 22        | 1.61%   |
| 5.14    | 6         | 0.44%   |
| 5.19    | 5         | 0.37%   |
| 5.16    | 3         | 0.22%   |
| 5.18    | 2         | 0.15%   |
| 5.10    | 2         | 0.15%   |
| 6.0     | 1         | 0.07%   |
| 5.4     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1300      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1140      | 87.09%  |
| XFCE       | 151       | 11.54%  |
| Unknown    | 10        | 0.76%   |
| X-Cinnamon | 2         | 0.15%   |
| LXDE       | 1         | 0.08%   |
| KDE5       | 1         | 0.08%   |
| KDE        | 1         | 0.08%   |
| i3         | 1         | 0.08%   |
| Cinnamon   | 1         | 0.08%   |
| Budgie     | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1277      | 97.63%  |
| Wayland | 27        | 2.06%   |
| Unknown | 4         | 0.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 993       | 75.4%   |
| GDM     | 156       | 11.85%  |
| GDM3    | 129       | 9.79%   |
| LightDM | 36        | 2.73%   |
| SDDM    | 2         | 0.15%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 498       | 38.13%  |
| de_DE | 117       | 8.96%   |
| en_GB | 95        | 7.27%   |
| pt_BR | 78        | 5.97%   |
| fr_FR | 48        | 3.68%   |
| it_IT | 42        | 3.22%   |
| es_ES | 42        | 3.22%   |
| en_IN | 42        | 3.22%   |
| en_CA | 37        | 2.83%   |
| pl_PL | 30        | 2.3%    |
| en_AU | 25        | 1.91%   |
| es_MX | 22        | 1.68%   |
| nl_NL | 20        | 1.53%   |
| ru_RU | 18        | 1.38%   |
| en_ZA | 15        | 1.15%   |
| pt_PT | 14        | 1.07%   |
| cs_CZ | 13        | 1%      |
| fr_BE | 12        | 0.92%   |
| sv_SE | 10        | 0.77%   |
| tr_TR | 9         | 0.69%   |
| es_CL | 8         | 0.61%   |
| en_NZ | 8         | 0.61%   |
| nl_BE | 7         | 0.54%   |
| de_AT | 7         | 0.54%   |
| es_AR | 6         | 0.46%   |
| hu_HU | 5         | 0.38%   |
| es_CO | 5         | 0.38%   |
| ja_JP | 4         | 0.31%   |
| es_CR | 4         | 0.31%   |
| el_GR | 4         | 0.31%   |
| de_CH | 4         | 0.31%   |
| sr_RS | 3         | 0.23%   |
| ru_UA | 3         | 0.23%   |
| nb_NO | 3         | 0.23%   |
| fi_FI | 3         | 0.23%   |
| en_PH | 3         | 0.23%   |
| en_IE | 3         | 0.23%   |
| bg_BG | 3         | 0.23%   |
| ar_EG | 3         | 0.23%   |
| lt_LT | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 779       | 59.33%  |
| BIOS | 534       | 40.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1238      | 94.87%  |
| Zfs     | 24        | 1.84%   |
| Overlay | 22        | 1.69%   |
| Btrfs   | 16        | 1.23%   |
| Xfs     | 3         | 0.23%   |
| Ext3    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1103      | 83.94%  |
| GPT     | 172       | 13.09%  |
| MBR     | 39        | 2.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1278      | 98.08%  |
| Yes       | 25        | 1.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1182      | 90.51%  |
| Yes       | 124       | 9.49%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 279       | 21.46%  |
| Lenovo              | 215       | 16.54%  |
| Dell                | 205       | 15.77%  |
| ASUSTek Computer    | 149       | 11.46%  |
| Acer                | 98        | 7.54%   |
| Toshiba             | 61        | 4.69%   |
| Apple               | 35        | 2.69%   |
| MSI                 | 26        | 2%      |
| Samsung Electronics | 24        | 1.85%   |
| Sony                | 19        | 1.46%   |
| Packard Bell        | 14        | 1.08%   |
| Unknown             | 14        | 1.08%   |
| Google              | 12        | 0.92%   |
| HUAWEI              | 11        | 0.85%   |
| Chuwi               | 8         | 0.62%   |
| Notebook            | 7         | 0.54%   |
| Positivo            | 6         | 0.46%   |
| Fujitsu             | 6         | 0.46%   |
| Alienware           | 6         | 0.46%   |
| Medion              | 5         | 0.38%   |
| GPU Company         | 5         | 0.38%   |
| Razer               | 4         | 0.31%   |
| LG Electronics      | 4         | 0.31%   |
| Jumper              | 4         | 0.31%   |
| Fujitsu Siemens     | 4         | 0.31%   |
| Thomson             | 3         | 0.23%   |
| Multilaser          | 3         | 0.23%   |
| Insyde              | 3         | 0.23%   |
| Gateway             | 3         | 0.23%   |
| Framework           | 3         | 0.23%   |
| AMI                 | 3         | 0.23%   |
| TUXEDO              | 2         | 0.15%   |
| Star Labs           | 2         | 0.15%   |
| Panasonic           | 2         | 0.15%   |
| Microtech           | 2         | 0.15%   |
| Kogan               | 2         | 0.15%   |
| Hampoo              | 2         | 0.15%   |
| Gigabyte Technology | 2         | 0.15%   |
| Fusion5             | 2         | 0.15%   |
| Ematic              | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 21        | 1.62%   |
| HP Notebook                    | 15        | 1.15%   |
| HP Pavilion Notebook           | 12        | 0.92%   |
| HP 15                          | 7         | 0.54%   |
| Apple MacBookPro8,1            | 7         | 0.54%   |
| Dell Latitude E6540            | 6         | 0.46%   |
| HP ProBook 640 G1              | 5         | 0.38%   |
| HP Pavilion dv7                | 5         | 0.38%   |
| HP Pavilion 15                 | 5         | 0.38%   |
| Toshiba Satellite C660         | 4         | 0.31%   |
| Toshiba Satellite C55-C        | 4         | 0.31%   |
| HP Pavilion g6                 | 4         | 0.31%   |
| HP Laptop 15-bw0xx             | 4         | 0.31%   |
| GPU Company GWTC116-2          | 4         | 0.31%   |
| Dell Studio 1558               | 4         | 0.31%   |
| Dell Latitude E7440            | 4         | 0.31%   |
| Dell Latitude E5500            | 4         | 0.31%   |
| Dell Inspiron 3542             | 4         | 0.31%   |
| Dell Inspiron 3521             | 4         | 0.31%   |
| Dell Inspiron 15-3567          | 4         | 0.31%   |
| Chuwi HeroBook Air             | 4         | 0.31%   |
| Packard Bell EasyNote TK85     | 3         | 0.23%   |
| Lenovo Yoga 3 Pro-1370 80HE    | 3         | 0.23%   |
| Lenovo IdeaPad S340-14API 81NB | 3         | 0.23%   |
| Lenovo IdeaPad S145-15API 81V7 | 3         | 0.23%   |
| Lenovo IdeaPad Flex-14API 81SS | 3         | 0.23%   |
| Lenovo IdeaPad 3 15IIL05 81WE  | 3         | 0.23%   |
| Lenovo G500 20236              | 3         | 0.23%   |
| Lenovo G50-70 20351            | 3         | 0.23%   |
| Lenovo G50-30 80G0             | 3         | 0.23%   |
| Jumper EZbook                  | 3         | 0.23%   |
| HUAWEI NBLK-WAX9X              | 3         | 0.23%   |
| HP Pavilion g7                 | 3         | 0.23%   |
| HP Pavilion dv6                | 3         | 0.23%   |
| HP OMEN by Laptop 15-dc1xxx    | 3         | 0.23%   |
| HP Laptop 15-db0xxx            | 3         | 0.23%   |
| HP EliteBook 840 G6            | 3         | 0.23%   |
| HP EliteBook 840 G1            | 3         | 0.23%   |
| HP EliteBook 2570p             | 3         | 0.23%   |
| Framework Laptop               | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 81        | 6.23%   |
| Dell Latitude         | 80        | 6.15%   |
| Dell Inspiron         | 73        | 5.62%   |
| Lenovo IdeaPad        | 70        | 5.38%   |
| Acer Aspire           | 70        | 5.38%   |
| HP Pavilion           | 68        | 5.23%   |
| Toshiba Satellite     | 49        | 3.77%   |
| HP EliteBook          | 37        | 2.85%   |
| HP ProBook            | 34        | 2.62%   |
| HP Laptop             | 27        | 2.08%   |
| ASUS VivoBook         | 27        | 2.08%   |
| Unknown               | 21        | 1.62%   |
| HP Notebook           | 15        | 1.15%   |
| Dell XPS              | 14        | 1.08%   |
| Dell Vostro           | 13        | 1%      |
| Packard Bell EasyNote | 12        | 0.92%   |
| HP Stream             | 12        | 0.92%   |
| HP ENVY               | 12        | 0.92%   |
| HP Compaq             | 12        | 0.92%   |
| HP OMEN               | 10        | 0.77%   |
| HP 15                 | 9         | 0.69%   |
| ASUS ZenBook          | 9         | 0.69%   |
| Apple MacBookPro8     | 9         | 0.69%   |
| Lenovo Yoga           | 8         | 0.62%   |
| Dell Studio           | 8         | 0.62%   |
| Dell Precision        | 8         | 0.62%   |
| ASUS ASUS             | 8         | 0.62%   |
| ASUS ROG              | 7         | 0.54%   |
| HP 255                | 6         | 0.46%   |
| Acer Swift            | 6         | 0.46%   |
| Toshiba PORTEGE       | 5         | 0.38%   |
| Fujitsu LIFEBOOK      | 5         | 0.38%   |
| Chuwi HeroBook        | 5         | 0.38%   |
| ASUS TUF              | 5         | 0.38%   |
| Apple MacBookPro11    | 5         | 0.38%   |
| Toshiba TECRA         | 4         | 0.31%   |
| Lenovo ThinkBook      | 4         | 0.31%   |
| Lenovo Legion         | 4         | 0.31%   |
| HP ZBook              | 4         | 0.31%   |
| HP 250                | 4         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 128       | 9.85%   |
| 2012 | 121       | 9.31%   |
| 2013 | 118       | 9.08%   |
| 2021 | 117       | 9%      |
| 2019 | 101       | 7.77%   |
| 2020 | 100       | 7.69%   |
| 2014 | 88        | 6.77%   |
| 2010 | 84        | 6.46%   |
| 2018 | 79        | 6.08%   |
| 2017 | 77        | 5.92%   |
| 2015 | 75        | 5.77%   |
| 2016 | 68        | 5.23%   |
| 2008 | 59        | 4.54%   |
| 2009 | 37        | 2.85%   |
| 2007 | 27        | 2.08%   |
| 2022 | 15        | 1.15%   |
| 2006 | 6         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1300      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1112      | 84.63%  |
| Enabled  | 202       | 15.37%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1285      | 98.85%  |
| Yes  | 15        | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 443       | 34.02%  |
| 3.01-4.0    | 373       | 28.65%  |
| 8.01-16.0   | 185       | 14.21%  |
| 16.01-24.0  | 138       | 10.6%   |
| 1.01-2.0    | 78        | 5.99%   |
| 32.01-64.0  | 53        | 4.07%   |
| 2.01-3.0    | 16        | 1.23%   |
| 64.01-256.0 | 9         | 0.69%   |
| 24.01-32.0  | 5         | 0.38%   |
| 0.51-1.0    | 2         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 584       | 41.8%   |
| 2.01-3.0   | 454       | 32.5%   |
| 3.01-4.0   | 187       | 13.39%  |
| 4.01-8.0   | 122       | 8.73%   |
| 0.51-1.0   | 27        | 1.93%   |
| 8.01-16.0  | 20        | 1.43%   |
| 24.01-32.0 | 2         | 0.14%   |
| 16.01-24.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 988       | 74.91%  |
| 2      | 287       | 21.76%  |
| 3      | 30        | 2.27%   |
| 4      | 7         | 0.53%   |
| 0      | 5         | 0.38%   |
| 8      | 1         | 0.08%   |
| 5      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 733       | 56.21%  |
| Yes       | 571       | 43.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1025      | 78.66%  |
| No        | 278       | 21.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1254      | 96.46%  |
| No        | 46        | 3.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 936       | 71.4%   |
| No        | 375       | 28.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 282       | 21.64%  |
| Germany      | 130       | 9.98%   |
| Brazil       | 89        | 6.83%   |
| UK           | 82        | 6.29%   |
| Spain        | 51        | 3.91%   |
| Canada       | 45        | 3.45%   |
| Italy        | 44        | 3.38%   |
| India        | 44        | 3.38%   |
| France       | 42        | 3.22%   |
| Mexico       | 32        | 2.46%   |
| Netherlands  | 28        | 2.15%   |
| Poland       | 26        | 2%      |
| Australia    | 24        | 1.84%   |
| Belgium      | 23        | 1.77%   |
| Russia       | 21        | 1.61%   |
| South Africa | 19        | 1.46%   |
| Austria      | 18        | 1.38%   |
| Sweden       | 16        | 1.23%   |
| Portugal     | 16        | 1.23%   |
| Turkey       | 14        | 1.07%   |
| Czechia      | 14        | 1.07%   |
| Switzerland  | 11        | 0.84%   |
| Romania      | 10        | 0.77%   |
| Greece       | 10        | 0.77%   |
| Norway       | 9         | 0.69%   |
| Japan        | 9         | 0.69%   |
| Indonesia    | 9         | 0.69%   |
| Chile        | 9         | 0.69%   |
| Argentina    | 9         | 0.69%   |
| New Zealand  | 8         | 0.61%   |
| Colombia     | 8         | 0.61%   |
| Hungary      | 7         | 0.54%   |
| Bulgaria     | 7         | 0.54%   |
| Kenya        | 6         | 0.46%   |
| Ireland      | 6         | 0.46%   |
| Finland      | 6         | 0.46%   |
| Egypt        | 6         | 0.46%   |
| Ukraine      | 4         | 0.31%   |
| Slovenia     | 4         | 0.31%   |
| Philippines  | 4         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Madrid            | 10        | 0.74%   |
| Berlin            | 10        | 0.74%   |
| Sydney            | 9         | 0.67%   |
| New York          | 9         | 0.67%   |
| Athens            | 9         | 0.67%   |
| Vienna            | 8         | 0.59%   |
| Munich            | 8         | 0.59%   |
| Hamburg           | 8         | 0.59%   |
| Sao Paulo         | 7         | 0.52%   |
| Rome              | 7         | 0.52%   |
| Glasgow           | 7         | 0.52%   |
| Toronto           | 6         | 0.44%   |
| Rio de Janeiro    | 6         | 0.44%   |
| Paris             | 6         | 0.44%   |
| Moscow            | 6         | 0.44%   |
| Montreal          | 6         | 0.44%   |
| Johannesburg      | 6         | 0.44%   |
| Amsterdam         | 6         | 0.44%   |
| Stockholm         | 5         | 0.37%   |
| Seattle           | 5         | 0.37%   |
| Nairobi           | 5         | 0.37%   |
| Mexico City       | 5         | 0.37%   |
| London            | 5         | 0.37%   |
| Jakarta           | 5         | 0.37%   |
| Frankfurt am Main | 5         | 0.37%   |
| Delhi             | 5         | 0.37%   |
| Dallas            | 5         | 0.37%   |
| Chicago           | 5         | 0.37%   |
| Bogotá           | 5         | 0.37%   |
| Barcelona         | 5         | 0.37%   |
| Austin            | 5         | 0.37%   |
| Auckland          | 5         | 0.37%   |
| Valencia          | 4         | 0.3%    |
| Salt Lake City    | 4         | 0.3%    |
| Minneapolis       | 4         | 0.3%    |
| Krakow            | 4         | 0.3%    |
| Istanbul          | 4         | 0.3%    |
| Cairo             | 4         | 0.3%    |
| Birmingham        | 4         | 0.3%    |
| Bernissart        | 4         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 198       | 243    | 12.79%  |
| Samsung Electronics         | 196       | 264    | 12.66%  |
| WDC                         | 168       | 197    | 10.85%  |
| Toshiba                     | 149       | 164    | 9.63%   |
| Unknown                     | 134       | 180    | 8.66%   |
| SanDisk                     | 106       | 120    | 6.85%   |
| Kingston                    | 74        | 88     | 4.78%   |
| Crucial                     | 57        | 71     | 3.68%   |
| Intel                       | 43        | 54     | 2.78%   |
| Hitachi                     | 42        | 48     | 2.71%   |
| SK hynix                    | 41        | 48     | 2.65%   |
| HGST                        | 39        | 45     | 2.52%   |
| Micron Technology           | 31        | 37     | 2%      |
| A-DATA Technology           | 24        | 26     | 1.55%   |
| China                       | 15        | 19     | 0.97%   |
| Netac                       | 13        | 13     | 0.84%   |
| KIOXIA                      | 13        | 13     | 0.84%   |
| Intenso                     | 13        | 14     | 0.84%   |
| Apple                       | 13        | 14     | 0.84%   |
| SPCC                        | 12        | 14     | 0.78%   |
| PNY                         | 11        | 12     | 0.71%   |
| LITEON                      | 10        | 12     | 0.65%   |
| LITEONIT                    | 9         | 10     | 0.58%   |
| Unknown                     | 9         | 11     | 0.58%   |
| Transcend                   | 7         | 9      | 0.45%   |
| Phison                      | 7         | 8      | 0.45%   |
| Fujitsu                     | 7         | 8      | 0.45%   |
| Team                        | 6         | 7      | 0.39%   |
| JMicron Technology          | 6         | 7      | 0.39%   |
| GOODRAM                     | 6         | 7      | 0.39%   |
| SABRENT                     | 5         | 6      | 0.32%   |
| Patriot                     | 5         | 6      | 0.32%   |
| Lite-On                     | 5         | 7      | 0.32%   |
| OCZ                         | 4         | 5      | 0.26%   |
| Lexar                       | 4         | 4      | 0.26%   |
| ASMT                        | 4         | 4      | 0.26%   |
| Micron/Crucial Technology   | 3         | 3      | 0.19%   |
| Yangtze Memory Technologies | 2         | 2      | 0.13%   |
| Union Memory                | 2         | 2      | 0.13%   |
| Silicon Motion              | 2         | 2      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 44        | 2.7%    |
| Unknown MMC Card  64GB                 | 39        | 2.39%   |
| Seagate ST1000LM035-1RK172 1TB         | 27        | 1.66%   |
| Toshiba MQ01ABF050 500GB               | 22        | 1.35%   |
| Toshiba MQ01ABD100 1TB                 | 21        | 1.29%   |
| SanDisk NVMe SSD Drive 256GB           | 19        | 1.17%   |
| Unknown MMC Card  128GB                | 18        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 18        | 1.1%    |
| Samsung NVMe SSD Drive 512GB           | 18        | 1.1%    |
| Seagate ST500LT012-1DG142 500GB        | 16        | 0.98%   |
| Toshiba MQ04ABF100 1TB                 | 15        | 0.92%   |
| Kingston SA400S37240G 240GB SSD        | 15        | 0.92%   |
| Kingston SA400S37480G 480GB SSD        | 14        | 0.86%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 12        | 0.74%   |
| Intel NVMe SSD Drive 512GB             | 12        | 0.74%   |
| Unknown MMC Card  16GB                 | 11        | 0.68%   |
| Seagate ST9500325AS 500GB              | 11        | 0.68%   |
| Seagate Expansion 4TB                  | 11        | 0.68%   |
| SanDisk NVMe SSD Drive 512GB           | 11        | 0.68%   |
| Kingston SA400S37120G 120GB SSD        | 11        | 0.68%   |
| HGST HTS721010A9E630 1TB               | 10        | 0.61%   |
| Crucial CT500MX500SSD1 500GB           | 10        | 0.61%   |
| Crucial CT240BX500SSD1 240GB           | 10        | 0.61%   |
| Unknown SD/MMC/MS PRO 64GB             | 9         | 0.55%   |
| Samsung SSD 860 EVO 500GB              | 9         | 0.55%   |
| Samsung SSD 850 EVO 500GB              | 9         | 0.55%   |
| Unknown                                | 9         | 0.55%   |
| SK hynix NVMe SSD Drive 256GB          | 8         | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 8         | 0.49%   |
| Samsung SSD 870 EVO 1TB                | 8         | 0.49%   |
| Samsung SSD 860 EVO 250GB              | 7         | 0.43%   |
| Hitachi HTS545032B9A300 320GB          | 7         | 0.43%   |
| HGST HTS725050A7E630 500GB             | 7         | 0.43%   |
| HGST HTS541010A9E680 1TB               | 7         | 0.43%   |
| WDC WD10SPZX-24Z10 1TB                 | 6         | 0.37%   |
| Toshiba NVMe SSD Drive 256GB           | 6         | 0.37%   |
| SK hynix NVMe SSD Drive 512GB          | 6         | 0.37%   |
| Seagate ST9500420AS 500GB              | 6         | 0.37%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 6         | 0.37%   |
| Seagate ST500LM021-1KJ152 500GB        | 6         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 197       | 241    | 34.93%  |
| WDC                 | 134       | 154    | 23.76%  |
| Toshiba             | 115       | 124    | 20.39%  |
| Hitachi             | 42        | 48     | 7.45%   |
| HGST                | 39        | 45     | 6.91%   |
| Unknown             | 9         | 10     | 1.6%    |
| Samsung Electronics | 9         | 9      | 1.6%    |
| Fujitsu             | 7         | 8      | 1.24%   |
| ASMT                | 4         | 4      | 0.71%   |
| JMicron Technology  | 2         | 2      | 0.35%   |
| Apple               | 2         | 2      | 0.35%   |
| USB3.0              | 1         | 1      | 0.18%   |
| SABRENT             | 1         | 1      | 0.18%   |
| KESU                | 1         | 1      | 0.18%   |
| Intenso             | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 114       | 148    | 20.77%  |
| Kingston            | 62        | 76     | 11.29%  |
| SanDisk             | 55        | 65     | 10.02%  |
| Crucial             | 55        | 67     | 10.02%  |
| WDC                 | 22        | 28     | 4.01%   |
| Toshiba             | 22        | 25     | 4.01%   |
| A-DATA Technology   | 20        | 22     | 3.64%   |
| Intel               | 15        | 18     | 2.73%   |
| China               | 14        | 18     | 2.55%   |
| SK hynix            | 13        | 13     | 2.37%   |
| Netac               | 13        | 13     | 2.37%   |
| Micron Technology   | 13        | 15     | 2.37%   |
| SPCC                | 11        | 13     | 2%      |
| PNY                 | 11        | 12     | 2%      |
| LITEON              | 10        | 12     | 1.82%   |
| Apple               | 10        | 10     | 1.82%   |
| LITEONIT            | 9         | 10     | 1.64%   |
| Intenso             | 9         | 9      | 1.64%   |
| Transcend           | 7         | 9      | 1.28%   |
| Team                | 6         | 7      | 1.09%   |
| GOODRAM             | 6         | 7      | 1.09%   |
| Patriot             | 5         | 6      | 0.91%   |
| OCZ                 | 4         | 5      | 0.73%   |
| Unknown             | 4         | 6      | 0.73%   |
| Lexar               | 3         | 3      | 0.55%   |
| JMicron Technology  | 3         | 4      | 0.55%   |
| Mushkin             | 2         | 2      | 0.36%   |
| KingSpec            | 2         | 2      | 0.36%   |
| HS-SSD-E100         | 2         | 2      | 0.36%   |
| Hewlett-Packard     | 2         | 2      | 0.36%   |
| BHT                 | 2         | 3      | 0.36%   |
| ZOTAC               | 1         | 1      | 0.18%   |
| Verbatim            | 1         | 1      | 0.18%   |
| Vaseky              | 1         | 2      | 0.18%   |
| TO Exter            | 1         | 1      | 0.18%   |
| Teclast             | 1         | 1      | 0.18%   |
| T-CREATE            | 1         | 1      | 0.18%   |
| Star                | 1         | 1      | 0.18%   |
| SAM                 | 1         | 1      | 0.18%   |
| S3+                 | 1         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 551       | 651    | 36.78%  |
| SSD     | 522       | 658    | 34.85%  |
| NVMe    | 274       | 356    | 18.29%  |
| MMC     | 136       | 179    | 9.08%   |
| Unknown | 15        | 17     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 985       | 1259   | 68.21%  |
| NVMe | 272       | 351    | 18.84%  |
| MMC  | 136       | 179    | 9.42%   |
| SAS  | 51        | 72     | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 739       | 908    | 69.52%  |
| 0.51-1.0   | 282       | 342    | 26.53%  |
| 1.01-2.0   | 25        | 34     | 2.35%   |
| 3.01-4.0   | 14        | 20     | 1.32%   |
| 4.01-10.0  | 3         | 5      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 452       | 33.98%  |
| 251-500        | 354       | 26.62%  |
| 501-1000       | 191       | 14.36%  |
| 51-100         | 133       | 10%     |
| 21-50          | 87        | 6.54%   |
| 1001-2000      | 42        | 3.16%   |
| 1-20           | 27        | 2.03%   |
| Unknown        | 18        | 1.35%   |
| More than 3000 | 15        | 1.13%   |
| 2001-3000      | 11        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 592       | 42.96%  |
| 21-50          | 392       | 28.45%  |
| 51-100         | 149       | 10.81%  |
| 101-250        | 131       | 9.51%   |
| 251-500        | 59        | 4.28%   |
| 501-1000       | 27        | 1.96%   |
| Unknown        | 18        | 1.31%   |
| More than 3000 | 6         | 0.44%   |
| 2001-3000      | 2         | 0.15%   |
| 1001-2000      | 2         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 5.88%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 5.88%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 2.94%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 2.94%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 2.94%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 2.94%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 2.94%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 2.94%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 2.94%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.94%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.94%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 2.94%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.94%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 2.94%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 2.94%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD            | 1         | 1      | 2.94%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 2.94%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD           | 1         | 1      | 2.94%   |
| Hitachi HTS725032A9A364 320GB                    | 1         | 1      | 2.94%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.94%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 2.94%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 2.94%   |
| Hewlett-Packard SSD S600 240GB                   | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 26.47%  |
| Toshiba             | 7         | 7      | 20.59%  |
| WDC                 | 5         | 5      | 14.71%  |
| HGST                | 4         | 4      | 11.76%  |
| Samsung Electronics | 2         | 2      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| Hitachi             | 2         | 2      | 5.88%   |
| SK hynix            | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 34.62%  |
| Toshiba | 6         | 6      | 23.08%  |
| WDC     | 5         | 5      | 19.23%  |
| HGST    | 4         | 4      | 15.38%  |
| Hitachi | 2         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 26     | 76.47%  |
| SSD  | 7         | 7      | 20.59%  |
| NVMe | 1         | 1      | 2.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1137      | 1631   | 85.36%  |
| Works    | 160       | 194    | 12.01%  |
| Malfunc  | 33        | 34     | 2.48%   |
| Failed   | 2         | 2      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 949       | 66.97%  |
| AMD                              | 172       | 12.14%  |
| Samsung Electronics              | 91        | 6.42%   |
| SanDisk                          | 56        | 3.95%   |
| SK hynix                         | 27        | 1.91%   |
| Micron Technology                | 19        | 1.34%   |
| Toshiba America Info Systems     | 13        | 0.92%   |
| KIOXIA                           | 13        | 0.92%   |
| Kingston Technology Company      | 13        | 0.92%   |
| Phison Electronics               | 10        | 0.71%   |
| Nvidia                           | 10        | 0.71%   |
| Micron/Crucial Technology        | 6         | 0.42%   |
| ADATA Technology                 | 6         | 0.42%   |
| Lite-On Technology               | 5         | 0.35%   |
| Marvell Technology Group         | 4         | 0.28%   |
| ASMedia Technology               | 4         | 0.28%   |
| Union Memory (Shenzhen)          | 3         | 0.21%   |
| Silicon Motion                   | 3         | 0.21%   |
| Yangtze Memory Technologies      | 2         | 0.14%   |
| VIA Technologies                 | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.14%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Silicon Image                    | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 150       | 9.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 125       | 8.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 90        | 5.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 89        | 5.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 87        | 5.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 62        | 4.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 55        | 3.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 50        | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 39        | 2.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 38        | 2.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 36        | 2.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 33        | 2.16%   |
| Intel Volume Management Device NVMe RAID Controller                              | 32        | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 31        | 2.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 28        | 1.83%   |
| Samsung NVMe SSD Controller 980                                                  | 27        | 1.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 27        | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 22        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 21        | 1.38%   |
| Micron Non-Volatile memory controller                                            | 19        | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 18        | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 18        | 1.18%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 16        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 15        | 0.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 15        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14        | 0.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 13        | 0.85%   |
| Intel Non-Volatile memory controller                                             | 13        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 13        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 12        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 0.79%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 11        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 0.72%   |
| Intel SSD 660P Series                                                            | 10        | 0.65%   |
| SanDisk Non-Volatile memory controller                                           | 9         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 8         | 0.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 8         | 0.52%   |
| SK hynix BC511                                                                   | 7         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 981       | 66.64%  |
| NVMe | 275       | 18.68%  |
| RAID | 125       | 8.49%   |
| IDE  | 91        | 6.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1087      | 83.62%  |
| AMD    | 213       | 16.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 1.38%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 18        | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 1.31%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 14        | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 1%      |
| Intel Celeron CPU N2840 @ 2.16GHz             | 13        | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 0.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 11        | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 11        | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 0.85%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.77%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 10        | 0.77%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 10        | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.77%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 9         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.69%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 9         | 0.69%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 9         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.62%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 8         | 0.62%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 8         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 321       | 24.69%  |
| Intel Core i7                        | 223       | 17.15%  |
| Intel Core i3                        | 143       | 11%     |
| Intel Celeron                        | 113       | 8.69%   |
| Intel Core 2 Duo                     | 81        | 6.23%   |
| Other                                | 67        | 5.15%   |
| Intel Pentium                        | 53        | 4.08%   |
| Intel Atom                           | 47        | 3.62%   |
| AMD Ryzen 5                          | 43        | 3.31%   |
| AMD Ryzen 7                          | 30        | 2.31%   |
| AMD A6                               | 23        | 1.77%   |
| AMD A4                               | 19        | 1.46%   |
| AMD A10                              | 15        | 1.15%   |
| AMD A8                               | 12        | 0.92%   |
| AMD E1                               | 11        | 0.85%   |
| Intel Pentium Dual-Core              | 10        | 0.77%   |
| Intel Pentium Dual                   | 8         | 0.62%   |
| AMD Ryzen 3                          | 8         | 0.62%   |
| AMD E                                | 7         | 0.54%   |
| Intel Pentium Silver                 | 5         | 0.38%   |
| Intel Core M                         | 5         | 0.38%   |
| Intel Core 2                         | 5         | 0.38%   |
| AMD Turion 64 X2 Mobile              | 5         | 0.38%   |
| Intel Core m5                        | 4         | 0.31%   |
| AMD Ryzen 9                          | 4         | 0.31%   |
| AMD Ryzen 7 PRO                      | 4         | 0.31%   |
| AMD E2                               | 3         | 0.23%   |
| AMD Athlon II                        | 3         | 0.23%   |
| Intel Pentium Gold                   | 2         | 0.15%   |
| Intel Genuine                        | 2         | 0.15%   |
| Intel Core i9                        | 2         | 0.15%   |
| Intel Celeron Dual-Core              | 2         | 0.15%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.15%   |
| AMD FX                               | 2         | 0.15%   |
| AMD Athlon                           | 2         | 0.15%   |
| Intel Xeon                           | 1         | 0.08%   |
| Intel Core 2 Extreme                 | 1         | 0.08%   |
| Intel Celeron M                      | 1         | 0.08%   |
| AMD Z                                | 1         | 0.08%   |
| AMD V120                             | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 797       | 61.31%  |
| 4      | 388       | 29.85%  |
| 6      | 53        | 4.08%   |
| 8      | 44        | 3.38%   |
| 1      | 13        | 1%      |
| 14     | 2         | 0.15%   |
| 16     | 1         | 0.08%   |
| 10     | 1         | 0.08%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1300      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 861       | 66.23%  |
| 1      | 439       | 33.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1300      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 121       | 9.17%   |
| 0x306a9    | 113       | 8.57%   |
| Unknown    | 92        | 6.97%   |
| 0x40651    | 70        | 5.31%   |
| 0x20655    | 53        | 4.02%   |
| 0x1067a    | 49        | 3.71%   |
| 0x306d4    | 44        | 3.34%   |
| 0x30678    | 43        | 3.26%   |
| 0x406e3    | 41        | 3.11%   |
| 0x806c1    | 39        | 2.96%   |
| 0x306c3    | 38        | 2.88%   |
| 0x806ea    | 35        | 2.65%   |
| 0x806e9    | 35        | 2.65%   |
| 0x806ec    | 31        | 2.35%   |
| 0x406c4    | 29        | 2.2%    |
| 0x706a8    | 26        | 1.97%   |
| 0x906ea    | 25        | 1.9%    |
| 0x706e5    | 25        | 1.9%    |
| 0x6fd      | 22        | 1.67%   |
| 0x20652    | 22        | 1.67%   |
| 0x506c9    | 20        | 1.52%   |
| 0x10676    | 20        | 1.52%   |
| 0x406c3    | 18        | 1.36%   |
| 0x906e9    | 17        | 1.29%   |
| 0x08108109 | 16        | 1.21%   |
| 0x07030105 | 16        | 1.21%   |
| 0xa0652    | 15        | 1.14%   |
| 0x08108102 | 15        | 1.14%   |
| 0x06006705 | 13        | 0.99%   |
| 0x0a50000c | 12        | 0.91%   |
| 0x0700010f | 12        | 0.91%   |
| 0x08608103 | 11        | 0.83%   |
| 0x08600106 | 11        | 0.83%   |
| 0x06006704 | 11        | 0.83%   |
| 0x6fb      | 10        | 0.76%   |
| 0x05000119 | 10        | 0.76%   |
| 0x806d1    | 9         | 0.68%   |
| 0x706a1    | 9         | 0.68%   |
| 0x06001119 | 8         | 0.61%   |
| 0x806eb    | 7         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 167       | 12.85%  |
| SandyBridge      | 126       | 9.69%   |
| IvyBridge        | 117       | 9%      |
| Haswell          | 116       | 8.92%   |
| Silvermont       | 96        | 7.38%   |
| Westmere         | 77        | 5.92%   |
| Penryn           | 69        | 5.31%   |
| Skylake          | 51        | 3.92%   |
| TigerLake        | 47        | 3.62%   |
| Broadwell        | 44        | 3.38%   |
| Core             | 43        | 3.31%   |
| Goldmont plus    | 36        | 2.77%   |
| IceLake          | 35        | 2.69%   |
| Zen+             | 33        | 2.54%   |
| Excavator        | 33        | 2.54%   |
| Zen 2            | 23        | 1.77%   |
| Puma             | 22        | 1.69%   |
| Goldmont         | 22        | 1.69%   |
| CometLake        | 19        | 1.46%   |
| Unknown          | 18        | 1.38%   |
| Zen 3            | 16        | 1.23%   |
| Jaguar           | 14        | 1.08%   |
| Bobcat           | 12        | 0.92%   |
| Piledriver       | 10        | 0.77%   |
| Nehalem          | 9         | 0.69%   |
| K10 Llano        | 9         | 0.69%   |
| K10              | 7         | 0.54%   |
| K8 Hammer        | 6         | 0.46%   |
| Bonnell          | 6         | 0.46%   |
| Zen              | 5         | 0.38%   |
| K8 & K10 hybrid  | 4         | 0.31%   |
| Tremont          | 3         | 0.23%   |
| Steamroller      | 3         | 0.23%   |
| Alderlake Hybrid | 2         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 984       | 62.64%  |
| AMD                              | 296       | 18.84%  |
| Nvidia                           | 288       | 18.33%  |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| VIA Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 113       | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 112       | 6.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 72        | 4.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 57        | 3.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 49        | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 2.72%   |
| Intel HD Graphics 620                                                                    | 39        | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 2.22%   |
| Intel UHD Graphics 620                                                                   | 35        | 2.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 2.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 2.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 32        | 1.98%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 25        | 1.55%   |
| AMD Renoir                                                                               | 23        | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 21        | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 1.05%   |
| Intel HD Graphics 630                                                                    | 17        | 1.05%   |
| Intel HD Graphics 500                                                                    | 17        | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 15        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.87%   |
| AMD Lucienne                                                                             | 14        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.62%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 10        | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 10        | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.56%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.49%   |
| Intel HD Graphics 530                                                                    | 8         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 735       | 56.45%  |
| 1 x AMD        | 203       | 15.59%  |
| Intel + Nvidia | 196       | 15.05%  |
| 1 x Nvidia     | 69        | 5.3%    |
| Intel + AMD    | 52        | 3.99%   |
| AMD + Nvidia   | 22        | 1.69%   |
| 2 x AMD        | 20        | 1.54%   |
| 1 x SiS        | 2         | 0.15%   |
| Other          | 1         | 0.08%   |
| 2 x Nvidia     | 1         | 0.08%   |
| 1 x VIA        | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1121      | 85.97%  |
| Proprietary | 165       | 12.65%  |
| Unknown     | 18        | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 880       | 66.62%  |
| 0.01-0.5   | 158       | 11.96%  |
| 1.01-2.0   | 113       | 8.55%   |
| 0.51-1.0   | 93        | 7.04%   |
| 3.01-4.0   | 39        | 2.95%   |
| 5.01-6.0   | 16        | 1.21%   |
| 7.01-8.0   | 13        | 0.98%   |
| 2.01-3.0   | 8         | 0.61%   |
| 8.01-16.0  | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 265       | 19.09%  |
| Chimei Innolux          | 209       | 15.06%  |
| LG Display              | 203       | 14.63%  |
| BOE                     | 178       | 12.82%  |
| Samsung Electronics     | 171       | 12.32%  |
| Chi Mei Optoelectronics | 46        | 3.31%   |
| Apple                   | 34        | 2.45%   |
| Dell                    | 28        | 2.02%   |
| Sharp                   | 24        | 1.73%   |
| Lenovo                  | 24        | 1.73%   |
| Goldstar                | 24        | 1.73%   |
| PANDA                   | 19        | 1.37%   |
| LG Philips              | 18        | 1.3%    |
| Hewlett-Packard         | 12        | 0.86%   |
| CPT                     | 8         | 0.58%   |
| Acer                    | 8         | 0.58%   |
| Vizio                   | 7         | 0.5%    |
| Philips                 | 7         | 0.5%    |
| InfoVision              | 7         | 0.5%    |
| Sony                    | 6         | 0.43%   |
| LGD                     | 6         | 0.43%   |
| BenQ                    | 6         | 0.43%   |
| AOC                     | 5         | 0.36%   |
| Ancor Communications    | 5         | 0.36%   |
| Toshiba                 | 4         | 0.29%   |
| KDC                     | 4         | 0.29%   |
| HannStar                | 4         | 0.29%   |
| ASUSTek Computer        | 4         | 0.29%   |
| InnoLux Display         | 3         | 0.22%   |
| Iiyama                  | 3         | 0.22%   |
| BOE Technology Group    | 3         | 0.22%   |
| SANYO                   | 2         | 0.14%   |
| Quanta Display          | 2         | 0.14%   |
| Panasonic               | 2         | 0.14%   |
| JDI                     | 2         | 0.14%   |
| ITE                     | 2         | 0.14%   |
| Eizo                    | 2         | 0.14%   |
| VIE                     | 1         | 0.07%   |
| Unknown (XXX)           | 1         | 0.07%   |
| Unknown                 | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 15        | 1.07%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 1%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.72%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 7         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 7         | 0.5%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 6         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 6         | 0.43%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 5         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 5         | 0.36%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 5         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 5         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.36%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 4         | 0.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 4         | 0.29%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 4         | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 570       | 42.54%  |
| 1920x1080 (FHD)    | 425       | 31.72%  |
| 1600x900 (HD+)     | 87        | 6.49%   |
| 1280x800 (WXGA)    | 69        | 5.15%   |
| 3840x2160 (4K)     | 32        | 2.39%   |
| 1440x900 (WXGA+)   | 31        | 2.31%   |
| 2560x1440 (QHD)    | 15        | 1.12%   |
| 2560x1600          | 13        | 0.97%   |
| 1680x1050 (WSXGA+) | 11        | 0.82%   |
| 1920x1200 (WUXGA)  | 9         | 0.67%   |
| 1280x1024 (SXGA)   | 9         | 0.67%   |
| 1360x768           | 8         | 0.6%    |
| Unknown            | 7         | 0.52%   |
| 2256x1504          | 6         | 0.45%   |
| 2160x1440          | 6         | 0.45%   |
| 3200x1800 (QHD+)   | 5         | 0.37%   |
| 2560x1080          | 5         | 0.37%   |
| 3840x2400          | 4         | 0.3%    |
| 2880x1800          | 4         | 0.3%    |
| 1920x540           | 3         | 0.22%   |
| 1024x600           | 3         | 0.22%   |
| 5760x1080          | 2         | 0.15%   |
| 3840x1080          | 2         | 0.15%   |
| 3440x1440          | 2         | 0.15%   |
| 1920x515           | 2         | 0.15%   |
| 4480x1600          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 612       | 44.32%  |
| 13      | 191       | 13.83%  |
| 14      | 147       | 10.64%  |
| 17      | 118       | 8.54%   |
| 11      | 55        | 3.98%   |
| 12      | 35        | 2.53%   |
| Unknown | 29        | 2.1%    |
| 27      | 27        | 1.96%   |
| 24      | 24        | 1.74%   |
| 23      | 21        | 1.52%   |
| 18      | 17        | 1.23%   |
| 21      | 14        | 1.01%   |
| 16      | 12        | 0.87%   |
| 34      | 9         | 0.65%   |
| 31      | 9         | 0.65%   |
| 19      | 8         | 0.58%   |
| 10      | 7         | 0.51%   |
| 20      | 6         | 0.43%   |
| 22      | 5         | 0.36%   |
| 40      | 4         | 0.29%   |
| 84      | 3         | 0.22%   |
| 72      | 3         | 0.22%   |
| 54      | 3         | 0.22%   |
| 32      | 3         | 0.22%   |
| 25      | 3         | 0.22%   |
| 49      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 26      | 2         | 0.14%   |
| 74      | 1         | 0.07%   |
| 65      | 1         | 0.07%   |
| 64      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 29      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 846       | 61.62%  |
| 201-300     | 190       | 13.84%  |
| 351-400     | 140       | 10.2%   |
| 501-600     | 67        | 4.88%   |
| 401-500     | 49        | 3.57%   |
| Unknown     | 29        | 2.11%   |
| 601-700     | 14        | 1.02%   |
| 701-800     | 12        | 0.87%   |
| 1001-1500   | 11        | 0.8%    |
| 1501-2000   | 7         | 0.51%   |
| 801-900     | 6         | 0.44%   |
| 101-200     | 1         | 0.07%   |
| 901-1000    | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1069      | 84.51%  |
| 16/10   | 135       | 10.67%  |
| Unknown | 21        | 1.66%   |
| 3/2     | 16        | 1.26%   |
| 21/9    | 9         | 0.71%   |
| 5/4     | 7         | 0.55%   |
| 4/3     | 4         | 0.32%   |
| 3.73    | 2         | 0.16%   |
| 32/9    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 614       | 44.53%  |
| 81-90          | 272       | 19.72%  |
| 121-130        | 97        | 7.03%   |
| 71-80          | 64        | 4.64%   |
| 201-250        | 57        | 4.13%   |
| 51-60          | 55        | 3.99%   |
| 61-70          | 34        | 2.47%   |
| Unknown        | 29        | 2.1%    |
| 301-350        | 28        | 2.03%   |
| 351-500        | 22        | 1.6%    |
| 151-200        | 20        | 1.45%   |
| 141-150        | 20        | 1.45%   |
| More than 1000 | 17        | 1.23%   |
| 131-140        | 15        | 1.09%   |
| 111-120        | 8         | 0.58%   |
| 501-1000       | 8         | 0.58%   |
| 41-50          | 7         | 0.51%   |
| 251-300        | 6         | 0.44%   |
| 91-100         | 5         | 0.36%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 568       | 41.86%  |
| 121-160       | 443       | 32.65%  |
| 51-100        | 209       | 15.4%   |
| 161-240       | 62        | 4.57%   |
| Unknown       | 29        | 2.14%   |
| More than 240 | 26        | 1.92%   |
| 1-50          | 20        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1135      | 86.05%  |
| 2     | 155       | 11.75%  |
| 0     | 16        | 1.21%   |
| 3     | 11        | 0.83%   |
| 5     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 675       | 32.75%  |
| Intel                             | 557       | 27.03%  |
| Qualcomm Atheros                  | 354       | 17.18%  |
| Broadcom                          | 179       | 8.69%   |
| Broadcom Limited                  | 60        | 2.91%   |
| Ralink                            | 26        | 1.26%   |
| Marvell Technology Group          | 22        | 1.07%   |
| TP-Link                           | 16        | 0.78%   |
| MediaTek                          | 15        | 0.73%   |
| ASIX Electronics                  | 15        | 0.73%   |
| Samsung Electronics               | 13        | 0.63%   |
| Ralink Technology                 | 12        | 0.58%   |
| Dell                              | 12        | 0.58%   |
| Nvidia                            | 9         | 0.44%   |
| DisplayLink                       | 9         | 0.44%   |
| Xiaomi                            | 8         | 0.39%   |
| Hewlett-Packard                   | 7         | 0.34%   |
| Sierra Wireless                   | 6         | 0.29%   |
| JMicron Technology                | 6         | 0.29%   |
| Qualcomm                          | 5         | 0.24%   |
| Huawei Technologies               | 5         | 0.24%   |
| Ericsson Business Mobile Networks | 5         | 0.24%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.19%   |
| Edimax Technology                 | 4         | 0.19%   |
| Qualcomm Atheros Communications   | 3         | 0.15%   |
| OPPO Electronics                  | 3         | 0.15%   |
| D-Link System                     | 3         | 0.15%   |
| T & A Mobile Phones               | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.1%    |
| NetGear                           | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| ASUSTek Computer                  | 2         | 0.1%    |
| ZyXEL Communications              | 1         | 0.05%   |
| ZyDAS                             | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |
| Shenzhen Goodix Technology        | 1         | 0.05%   |
| Novatel Wireless                  | 1         | 0.05%   |
| Motorola PCS                      | 1         | 0.05%   |
| Motorola BCS                      | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362       | 14.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 171       | 7.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 84        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 55        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 53        | 2.17%   |
| Intel Wireless 7260                                               | 50        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 46        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 39        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.4%    |
| Intel Wi-Fi 6 AX200                                               | 34        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 32        | 1.31%   |
| Intel Wireless 7265                                               | 31        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 28        | 1.15%   |
| Intel Wireless 8260                                               | 28        | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.15%   |
| Intel Wireless 3165                                               | 26        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 23        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 20        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 0.82%   |
| Intel WiFi Link 5100                                              | 19        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                    | 19        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 18        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 0.74%   |
| Realtek 802.11n WLAN Adapter                                      | 17        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 17        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.62%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 15        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 13        | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 13        | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 531       | 39.92%  |
| Qualcomm Atheros                | 299       | 22.48%  |
| Realtek Semiconductor           | 224       | 16.84%  |
| Broadcom                        | 142       | 10.68%  |
| Broadcom Limited                | 38        | 2.86%   |
| Ralink                          | 26        | 1.95%   |
| MediaTek                        | 13        | 0.98%   |
| Ralink Technology               | 12        | 0.9%    |
| TP-Link                         | 11        | 0.83%   |
| Sierra Wireless                 | 6         | 0.45%   |
| Dell                            | 6         | 0.45%   |
| Edimax Technology               | 4         | 0.3%    |
| Qualcomm Atheros Communications | 3         | 0.23%   |
| D-Link System                   | 3         | 0.23%   |
| NetGear                         | 2         | 0.15%   |
| Linksys                         | 2         | 0.15%   |
| ZyXEL Communications            | 1         | 0.08%   |
| ZyDAS                           | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| Fibocom                         | 1         | 0.08%   |
| ASUSTek Computer                | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 84        | 6.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 55        | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 53        | 3.95%   |
| Intel Wireless 7260                                            | 50        | 3.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 46        | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 2.98%   |
| Broadcom BCM43142 802.11b/g/n                                  | 39        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.53%   |
| Intel Wi-Fi 6 AX200                                            | 34        | 2.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 2.53%   |
| Intel Wireless 8265 / 8275                                     | 32        | 2.38%   |
| Intel Wireless 7265                                            | 31        | 2.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 28        | 2.09%   |
| Intel Wireless 8260                                            | 28        | 2.09%   |
| Intel Wi-Fi 6 AX201                                            | 28        | 2.09%   |
| Intel Wireless 3165                                            | 26        | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 23        | 1.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 20        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20        | 1.49%   |
| Intel WiFi Link 5100                                           | 19        | 1.42%   |
| Intel Centrino Ultimate-N 6300                                 | 19        | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 18        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 1.34%   |
| Realtek 802.11n WLAN Adapter                                   | 17        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 15        | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 13        | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 13        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 0.97%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 12        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 12        | 0.89%   |
| Realtek 802.11ac NIC                                           | 11        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 11        | 0.82%   |
| Intel Wireless 3160                                            | 11        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 571       | 53.56%  |
| Intel                            | 204       | 19.14%  |
| Qualcomm Atheros                 | 92        | 8.63%   |
| Broadcom                         | 59        | 5.53%   |
| Broadcom Limited                 | 24        | 2.25%   |
| Marvell Technology Group         | 22        | 2.06%   |
| ASIX Electronics                 | 15        | 1.41%   |
| Samsung Electronics              | 13        | 1.22%   |
| Nvidia                           | 9         | 0.84%   |
| DisplayLink                      | 9         | 0.84%   |
| Xiaomi                           | 8         | 0.75%   |
| JMicron Technology               | 6         | 0.56%   |
| TP-Link                          | 5         | 0.47%   |
| Qualcomm                         | 4         | 0.38%   |
| OPPO Electronics                 | 3         | 0.28%   |
| Huawei Technologies              | 3         | 0.28%   |
| Hewlett-Packard                  | 3         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.19%   |
| MediaTek                         | 2         | 0.19%   |
| VIA Technologies                 | 1         | 0.09%   |
| Novatel Wireless                 | 1         | 0.09%   |
| Motorola PCS                     | 1         | 0.09%   |
| Motorola BCS                     | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| ICS Advent                       | 1         | 0.09%   |
| HMD Global                       | 1         | 0.09%   |
| GoPro                            | 1         | 0.09%   |
| Google                           | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362       | 33.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 171       | 15.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 5.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 2.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.59%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 1.49%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 1.4%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 1.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 1.12%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 8         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.75%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 7         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 5         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.47%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 5         | 0.47%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 5         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.37%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1254      | 54.52%  |
| Ethernet | 1022      | 44.43%  |
| Modem    | 19        | 0.83%   |
| Unknown  | 5         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1063      | 78.39%  |
| Ethernet | 292       | 21.53%  |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 939       | 72.23%  |
| 1     | 296       | 22.77%  |
| 0     | 60        | 4.62%   |
| 3     | 5         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 909       | 68.92%  |
| Yes  | 410       | 31.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 369       | 38.92%  |
| Qualcomm Atheros Communications | 124       | 13.08%  |
| Realtek Semiconductor           | 113       | 11.92%  |
| Broadcom                        | 62        | 6.54%   |
| IMC Networks                    | 57        | 6.01%   |
| Lite-On Technology              | 36        | 3.8%    |
| Apple                           | 33        | 3.48%   |
| Foxconn / Hon Hai               | 31        | 3.27%   |
| Dell                            | 26        | 2.74%   |
| Hewlett-Packard                 | 20        | 2.11%   |
| Toshiba                         | 19        | 2%      |
| Cambridge Silicon Radio         | 16        | 1.69%   |
| Ralink                          | 12        | 1.27%   |
| ASUSTek Computer                | 8         | 0.84%   |
| Foxconn International           | 5         | 0.53%   |
| Realtek                         | 4         | 0.42%   |
| Alps Electric                   | 4         | 0.42%   |
| Integrated System Solution      | 2         | 0.21%   |
| Askey Computer                  | 2         | 0.21%   |
| Qcom                            | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |
| Unknown                         | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 171       | 18.02%  |
| Realtek Bluetooth Radio                             | 73        | 7.69%   |
| Intel AX201 Bluetooth                               | 55        | 5.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 5.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 51        | 5.37%   |
| Intel AX200 Bluetooth                               | 34        | 3.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 3.16%   |
| IMC Networks Bluetooth Device                       | 23        | 2.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 2.21%   |
| Apple Bluetooth Host Controller                     | 21        | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 1.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 1.69%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 1.48%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.37%   |
| Ralink RT3290 Bluetooth                             | 12        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.26%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 1.26%   |
| Intel AX210 Bluetooth                               | 12        | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.05%   |
| Dell DW375 Bluetooth Module                         | 10        | 1.05%   |
| IMC Networks Wireless_Device                        | 9         | 0.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.74%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 6         | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 6         | 0.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.63%   |
| Toshiba Bluetooth Device                            | 5         | 0.53%   |
| Toshiba BCM43142A0                                  | 5         | 0.53%   |
| Lite-On Bluetooth Device                            | 5         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1038      | 68.92%  |
| AMD                                  | 252       | 16.73%  |
| Nvidia                               | 176       | 11.69%  |
| Realtek Semiconductor                | 4         | 0.27%   |
| SteelSeries ApS                      | 3         | 0.2%    |
| Generalplus Technology               | 3         | 0.2%    |
| C-Media Electronics                  | 3         | 0.2%    |
| Silicon Integrated Systems [SiS]     | 2         | 0.13%   |
| Logitech                             | 2         | 0.13%   |
| Lenovo                               | 2         | 0.13%   |
| KTMicro                              | 2         | 0.13%   |
| Focusrite-Novation                   | 2         | 0.13%   |
| DSEA A/S                             | 2         | 0.13%   |
| VIA Technologies                     | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.07%   |
| Texas Instruments                    | 1         | 0.07%   |
| Tenx Technology                      | 1         | 0.07%   |
| Sony                                 | 1         | 0.07%   |
| Roland                               | 1         | 0.07%   |
| Razer USA                            | 1         | 0.07%   |
| PreSonus Audio Electronics           | 1         | 0.07%   |
| JMTek                                | 1         | 0.07%   |
| GN Netcom                            | 1         | 0.07%   |
| Creative Technology                  | 1         | 0.07%   |
| Corsair                              | 1         | 0.07%   |
| Conexant Systems                     | 1         | 0.07%   |
| CMX Systems                          | 1         | 0.07%   |
| ASUSTek Computer                     | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 143       | 7.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 120       | 6.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 100       | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 91        | 4.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 86        | 4.67%   |
| Intel 8 Series HD Audio Controller                                                                | 73        | 3.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 69        | 3.74%   |
| AMD FCH Azalia Controller                                                                         | 64        | 3.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 59        | 3.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 47        | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 44        | 2.39%   |
| Intel Broadwell-U Audio Controller                                                                | 44        | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 2.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 44        | 2.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 43        | 2.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 36        | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 36        | 1.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 36        | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 33        | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 1.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 31        | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 26        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 25        | 1.36%   |
| AMD High Definition Audio Controller                                                              | 25        | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 22        | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 21        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 1.03%   |
| Intel CM238 HD Audio Controller                                                                   | 19        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 18        | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 0.71%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 12        | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 10        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 92        | 28.93%  |
| SK hynix            | 73        | 22.96%  |
| Micron Technology   | 43        | 13.52%  |
| Kingston            | 19        | 5.97%   |
| Unknown (ABCD)      | 16        | 5.03%   |
| Unknown             | 15        | 4.72%   |
| Crucial             | 13        | 4.09%   |
| A-DATA Technology   | 11        | 3.46%   |
| Elpida              | 5         | 1.57%   |
| Nanya Technology    | 4         | 1.26%   |
| Ramaxel Technology  | 3         | 0.94%   |
| Timetec             | 2         | 0.63%   |
| Teikon              | 2         | 0.63%   |
| Patriot             | 2         | 0.63%   |
| Unknown (08B5)      | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| Team                | 1         | 0.31%   |
| Strontium           | 1         | 0.31%   |
| Smart               | 1         | 0.31%   |
| Qimonda             | 1         | 0.31%   |
| PUSKILL             | 1         | 0.31%   |
| Netlist             | 1         | 0.31%   |
| Kingmax             | 1         | 0.31%   |
| GSkill              | 1         | 0.31%   |
| G.Skill             | 1         | 0.31%   |
| ff                  | 1         | 0.31%   |
| Essencore           | 1         | 0.31%   |
| CSX                 | 1         | 0.31%   |
| Axiom               | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| 4ea5                | 1         | 0.31%   |
| Unknown             | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 4.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.19%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.19%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.9%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.9%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.9%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.9%    |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.9%    |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.6%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.6%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.6%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.6%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 112       | 42.42%  |
| DDR3    | 97        | 36.74%  |
| LPDDR4  | 27        | 10.23%  |
| LPDDR3  | 11        | 4.17%   |
| DDR2    | 10        | 3.79%   |
| SDRAM   | 5         | 1.89%   |
| LPDDR5  | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 227       | 85.02%  |
| Row Of Chips | 31        | 11.61%  |
| DIMM         | 5         | 1.87%   |
| Chip         | 2         | 0.75%   |
| Unknown      | 2         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 112       | 38.36%  |
| 4096  | 105       | 35.96%  |
| 2048  | 39        | 13.36%  |
| 16384 | 24        | 8.22%   |
| 1024  | 8         | 2.74%   |
| 32768 | 4         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 67        | 22.87%  |
| 2667    | 50        | 17.06%  |
| 3200    | 47        | 16.04%  |
| 2400    | 35        | 11.95%  |
| 1334    | 18        | 6.14%   |
| 1333    | 12        | 4.1%    |
| 2133    | 10        | 3.41%   |
| 4267    | 8         | 2.73%   |
| 667     | 8         | 2.73%   |
| 3266    | 6         | 2.05%   |
| 1066    | 5         | 1.71%   |
| Unknown | 5         | 1.71%   |
| 8400    | 3         | 1.02%   |
| 2048    | 3         | 1.02%   |
| 1867    | 3         | 1.02%   |
| 800     | 3         | 1.02%   |
| 4199    | 2         | 0.68%   |
| 1067    | 2         | 0.68%   |
| 975     | 2         | 0.68%   |
| 6400    | 1         | 0.34%   |
| 4800    | 1         | 0.34%   |
| 4266    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 50%     |
| Canon                 | 2         | 16.67%  |
| Zebra                 | 1         | 8.33%   |
| Seiko Epson           | 1         | 8.33%   |
| Samsung Electronics   | 1         | 8.33%   |
| Lexmark International | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP ENVY Photo 6200 series         | 2         | 16.67%  |
| Zebra ZP 450 Printer              | 1         | 8.33%   |
| Seiko Epson L3110 Series          | 1         | 8.33%   |
| Samsung M2020 Series              | 1         | 8.33%   |
| Lexmark International 2400 series | 1         | 8.33%   |
| HP LaserJet 1200                  | 1         | 8.33%   |
| HP LaserJet 1000                  | 1         | 8.33%   |
| HP DeskJet 2300 series            | 1         | 8.33%   |
| HP DeskJet 1110 series            | 1         | 8.33%   |
| Canon TS3100 series               | 1         | 8.33%   |
| Canon PIXMA MG3000 series         | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 25%     |
| Canon CanoScan LIDE 25                      | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 269       | 23.93%  |
| Microdia                               | 110       | 9.79%   |
| Realtek Semiconductor                  | 104       | 9.25%   |
| IMC Networks                           | 103       | 9.16%   |
| Acer                                   | 71        | 6.32%   |
| Sunplus Innovation Technology          | 66        | 5.87%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 5.34%   |
| Quanta                                 | 49        | 4.36%   |
| Suyin                                  | 47        | 4.18%   |
| Syntek                                 | 32        | 2.85%   |
| Apple                                  | 31        | 2.76%   |
| Silicon Motion                         | 23        | 2.05%   |
| Lite-On Technology                     | 18        | 1.6%    |
| Ricoh                                  | 17        | 1.51%   |
| Alcor Micro                            | 17        | 1.51%   |
| Luxvisions Innotech Limited            | 12        | 1.07%   |
| USB Camera                             | 11        | 0.98%   |
| Primax Electronics                     | 11        | 0.98%   |
| ALi                                    | 7         | 0.62%   |
| Sonix Technology                       | 6         | 0.53%   |
| Samsung Electronics                    | 6         | 0.53%   |
| SunplusIT                              | 5         | 0.44%   |
| Lenovo                                 | 5         | 0.44%   |
| Importek                               | 5         | 0.44%   |
| Logitech                               | 4         | 0.36%   |
| GEMBIRD                                | 4         | 0.36%   |
| Sunplus Technology                     | 3         | 0.27%   |
| ARC International                      | 3         | 0.27%   |
| Z-Star Microelectronics                | 2         | 0.18%   |
| OmniVision Technologies                | 2         | 0.18%   |
| Genesys Logic                          | 2         | 0.18%   |
| Generalplus Technology                 | 2         | 0.18%   |
| YGTek                                  | 1         | 0.09%   |
| Y Media                                | 1         | 0.09%   |
| Unknown                                | 1         | 0.09%   |
| Tripath Technology                     | 1         | 0.09%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| Panasonic (Matsushita)                 | 1         | 0.09%   |
| Nebraska Furniture Mart                | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 37        | 3.28%   |
| Microdia Integrated_Webcam_HD                           | 29        | 2.57%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 27        | 2.4%    |
| Microdia Integrated Webcam                              | 24        | 2.13%   |
| Realtek Integrated_Webcam_HD                            | 22        | 1.95%   |
| Syntek Integrated Camera                                | 20        | 1.77%   |
| Chicony HD WebCam                                       | 20        | 1.77%   |
| Acer Integrated Camera                                  | 20        | 1.77%   |
| Chicony HP TrueVision HD                                | 19        | 1.69%   |
| Chicony TOSHIBA Web Camera - HD                         | 17        | 1.51%   |
| Realtek USB Camera                                      | 16        | 1.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 15        | 1.33%   |
| IMC Networks Integrated Camera                          | 14        | 1.24%   |
| Sunplus HD WebCam                                       | 13        | 1.15%   |
| Acer Lenovo EasyCamera                                  | 13        | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 12        | 1.06%   |
| USB Camera USB Camera                                   | 11        | 0.98%   |
| Apple FaceTime HD Camera                                | 11        | 0.98%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 0.89%   |
| Chicony USB2.0 VGA UVC WebCam                           | 10        | 0.89%   |
| Chicony HP TrueVision HD Camera                         | 10        | 0.89%   |
| Chicony HP HD Webcam                                    | 10        | 0.89%   |
| Apple iPhone5/5C/5S/6                                   | 10        | 0.89%   |
| Realtek Lenovo EasyCamera                               | 9         | 0.8%    |
| Chicony Lenovo EasyCamera                               | 9         | 0.8%    |
| Realtek Integrated Webcam                               | 8         | 0.71%   |
| Quanta HP Wide Vision HD Camera                         | 8         | 0.71%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.71%   |
| Microdia Webcam Vitade AF                               | 8         | 0.71%   |
| Chicony VGA Webcam                                      | 8         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                            | 8         | 0.71%   |
| Chicony USB 2.0 Camera                                  | 8         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 8         | 0.71%   |
| Alcor Micro USB 2.0 Camera                              | 8         | 0.71%   |
| Sunplus ASUS Webcam                                     | 7         | 0.62%   |
| Quanta HD User Facing                                   | 7         | 0.62%   |
| Lite-On HP HD Camera                                    | 7         | 0.62%   |
| Chicony HP HD Camera                                    | 7         | 0.62%   |
| Chicony EasyCamera                                      | 7         | 0.62%   |
| Chicony CNF9055 Toshiba Webcam                          | 7         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 43.78%  |
| AuthenTec                  | 23        | 12.43%  |
| Shenzhen Goodix Technology | 22        | 11.89%  |
| Upek                       | 19        | 10.27%  |
| Synaptics                  | 17        | 9.19%   |
| Elan Microelectronics      | 10        | 5.41%   |
| LighTuning Technology      | 6         | 3.24%   |
| STMicroelectronics         | 5         | 2.7%    |
| Samsung Electronics        | 1         | 0.54%   |
| Focal-systems.Corp         | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 9.73%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 9.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 8.65%   |
| AuthenTec AES2810                                                          | 10        | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 4.86%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 4.32%   |
| Validity Sensors VFS491                                                    | 7         | 3.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.78%   |
| Elan ELAN:ARM-M4                                                           | 7         | 3.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.7%    |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.7%    |
| Unknown                                                                    | 5         | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.16%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.16%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 2.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.16%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.62%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.62%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.62%   |
| AuthenTec AES1600                                                          | 3         | 1.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.08%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.08%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.08%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.08%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.54%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.54%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.54%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 45        | 56.25%  |
| Alcor Micro                       | 11        | 13.75%  |
| O2 Micro                          | 7         | 8.75%   |
| Lenovo                            | 6         | 7.5%    |
| Upek                              | 5         | 6.25%   |
| Yubico.com                        | 2         | 2.5%    |
| VASCO Data Security International | 1         | 1.25%   |
| SCM Microsystems                  | 1         | 1.25%   |
| Realtek Semiconductor             | 1         | 1.25%   |
| OmniKey                           | 1         | 1.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 22.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 18.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 13.75%  |
| Broadcom 5880                                                                | 9         | 11.25%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 8.75%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 6.25%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 2.5%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.25%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.25%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.25%   |
| Broadcom 58200                                                               | 1         | 1.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 904       | 68.48%  |
| 1     | 328       | 24.85%  |
| 2     | 81        | 6.14%   |
| 3     | 7         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 180       | 36.36%  |
| Graphics card            | 81        | 16.36%  |
| Chipcard                 | 73        | 14.75%  |
| Net/wireless             | 51        | 10.3%   |
| Multimedia controller    | 51        | 10.3%   |
| Bluetooth                | 16        | 3.23%   |
| Storage                  | 15        | 3.03%   |
| Sound                    | 5         | 1.01%   |
| Net/ethernet             | 3         | 0.61%   |
| Communication controller | 3         | 0.61%   |
| Card reader              | 3         | 0.61%   |
| Camera                   | 3         | 0.61%   |
| Storage/nvme             | 2         | 0.4%    |
| Network                  | 2         | 0.4%    |
| Modem                    | 2         | 0.4%    |
| Flash memory             | 2         | 0.4%    |
| Unclassified device      | 1         | 0.2%    |
| Storage/ide              | 1         | 0.2%    |
| Dvb card                 | 1         | 0.2%    |

