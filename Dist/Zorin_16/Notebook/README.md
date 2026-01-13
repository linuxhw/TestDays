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

Total: 3582

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | U46SM                       | [bd0d38e805](https://linux-hardware.org/?probe=bd0d38e805) | Dec 24, 2025 |
| Gigabyte      | GB-BNi7HG4-950              | [36b5ed19b7](https://linux-hardware.org/?probe=36b5ed19b7) | Dec 18, 2025 |
| HP            | ProBook 6570b               | [d7001cb8ee](https://linux-hardware.org/?probe=d7001cb8ee) | Dec 08, 2025 |
| HP            | EliteBook 840 G6            | [7dc5ad1a57](https://linux-hardware.org/?probe=7dc5ad1a57) | Dec 08, 2025 |
| HP            | 2000                        | [258adeab9d](https://linux-hardware.org/?probe=258adeab9d) | Dec 01, 2025 |
| HP            | ProBook 6570b               | [445f74db55](https://linux-hardware.org/?probe=445f74db55) | Nov 17, 2025 |
| HP            | ProBook 6570b               | [5294c39f37](https://linux-hardware.org/?probe=5294c39f37) | Nov 17, 2025 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [4d492c7379](https://linux-hardware.org/?probe=4d492c7379) | Nov 12, 2025 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [19f27c6a17](https://linux-hardware.org/?probe=19f27c6a17) | Nov 12, 2025 |
| HP            | Laptop 15-db1xxx            | [b494afa7ad](https://linux-hardware.org/?probe=b494afa7ad) | Nov 09, 2025 |
| Samsung       | Q35/Q36                     | [a27441fd37](https://linux-hardware.org/?probe=a27441fd37) | Nov 09, 2025 |
| HP            | Laptop 15-db1xxx            | [675998e2d7](https://linux-hardware.org/?probe=675998e2d7) | Nov 04, 2025 |
| HP            | Laptop 15-db1xxx            | [4e62083a10](https://linux-hardware.org/?probe=4e62083a10) | Nov 02, 2025 |
| Lenovo        | V14-IIL 82C4                | [14172561f0](https://linux-hardware.org/?probe=14172561f0) | Nov 02, 2025 |
| Lenovo        | G50-80 80L0                 | [46a2e403d4](https://linux-hardware.org/?probe=46a2e403d4) | Oct 27, 2025 |
| Toshiba       | Satellite L50-B             | [23657e9fe1](https://linux-hardware.org/?probe=23657e9fe1) | Oct 22, 2025 |
| HP            | Pavilion g6                 | [e698edc08e](https://linux-hardware.org/?probe=e698edc08e) | Oct 21, 2025 |
| Lenovo        | ThinkPad Edge E530c 3366... | [384ac4ede4](https://linux-hardware.org/?probe=384ac4ede4) | Oct 09, 2025 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [ec00f26275](https://linux-hardware.org/?probe=ec00f26275) | Sep 28, 2025 |
| Dell          | Latitude E4200              | [55f2e5f4a6](https://linux-hardware.org/?probe=55f2e5f4a6) | Sep 17, 2025 |
| Acer          | Aspire A315-44P             | [77bf25fcae](https://linux-hardware.org/?probe=77bf25fcae) | Sep 17, 2025 |
| Lenovo        | G70-70 80HW                 | [3dd3d8ca13](https://linux-hardware.org/?probe=3dd3d8ca13) | Sep 12, 2025 |
| Lenovo        | ThinkBook 14 G7 IML 21MR    | [e28d40e2a9](https://linux-hardware.org/?probe=e28d40e2a9) | Sep 11, 2025 |
| Samsung       | Q35/Q36                     | [cfc5c4693c](https://linux-hardware.org/?probe=cfc5c4693c) | Sep 11, 2025 |
| Lenovo        | ThinkPad Edge E530c 3366... | [5c1a9a8f53](https://linux-hardware.org/?probe=5c1a9a8f53) | Sep 06, 2025 |
| Lenovo        | ThinkPad Edge E530c 3366... | [93d48e2eb9](https://linux-hardware.org/?probe=93d48e2eb9) | Sep 05, 2025 |
| Toshiba       | Satellite L775D             | [3a8cc5d45c](https://linux-hardware.org/?probe=3a8cc5d45c) | Aug 31, 2025 |
| HP            | Stream Laptop 14-cb1xxx     | [9ab8634b7d](https://linux-hardware.org/?probe=9ab8634b7d) | Aug 17, 2025 |
| ASUSTek       | K45VD                       | [2d02858be7](https://linux-hardware.org/?probe=2d02858be7) | Jul 31, 2025 |
| HP            | ProBook 4730s               | [c42c3c35fd](https://linux-hardware.org/?probe=c42c3c35fd) | Jul 19, 2025 |
| HP            | ProBook 4730s               | [d3917b5489](https://linux-hardware.org/?probe=d3917b5489) | Jul 19, 2025 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [57b8c9fb76](https://linux-hardware.org/?probe=57b8c9fb76) | Jul 17, 2025 |
| Dell          | Latitude E7450              | [57dc610746](https://linux-hardware.org/?probe=57dc610746) | Jul 10, 2025 |
| Toshiba       | Satellite C660              | [ba1abe69bf](https://linux-hardware.org/?probe=ba1abe69bf) | Jul 08, 2025 |
| Dell          | Inspiron 1564               | [30723ae2c0](https://linux-hardware.org/?probe=30723ae2c0) | Jul 07, 2025 |
| Dell          | Latitude D530               | [0053d61dc3](https://linux-hardware.org/?probe=0053d61dc3) | Jul 05, 2025 |
| Dell          | Latitude D530               | [3eaae2ab74](https://linux-hardware.org/?probe=3eaae2ab74) | Jun 12, 2025 |
| Dell          | Inspiron 1545               | [7e4203164e](https://linux-hardware.org/?probe=7e4203164e) | Jun 09, 2025 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [7cb1e1a974](https://linux-hardware.org/?probe=7cb1e1a974) | Jun 09, 2025 |
| Compal        | Unknown                     | [ac5ec91466](https://linux-hardware.org/?probe=ac5ec91466) | Jun 03, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bdada53092](https://linux-hardware.org/?probe=bdada53092) | May 23, 2025 |
| Lenovo        | ThinkPad E590 20NB001DUS    | [810686a741](https://linux-hardware.org/?probe=810686a741) | May 22, 2025 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b78651468a](https://linux-hardware.org/?probe=b78651468a) | May 17, 2025 |
| Acer          | Aspire 5750                 | [12008603ac](https://linux-hardware.org/?probe=12008603ac) | May 12, 2025 |
| Dell          | Latitude E6510              | [6e8d264b2d](https://linux-hardware.org/?probe=6e8d264b2d) | May 09, 2025 |
| Apple         | MacBookPro10,2              | [eae725d054](https://linux-hardware.org/?probe=eae725d054) | May 02, 2025 |
| Dell          | Latitude D530               | [008aee6053](https://linux-hardware.org/?probe=008aee6053) | Apr 30, 2025 |
| Apple         | MacBookPro10,2              | [5452c915bd](https://linux-hardware.org/?probe=5452c915bd) | Apr 29, 2025 |
| Dell          | Latitude D830               | [41e3d3257b](https://linux-hardware.org/?probe=41e3d3257b) | Apr 27, 2025 |
| Samsung       | Q35/Q36                     | [226aa6a75e](https://linux-hardware.org/?probe=226aa6a75e) | Apr 16, 2025 |
| HP            | Laptop 17-bs0xx             | [f34354deb7](https://linux-hardware.org/?probe=f34354deb7) | Apr 13, 2025 |
| Apple         | MacBook8,1                  | [0c1206faa7](https://linux-hardware.org/?probe=0c1206faa7) | Apr 06, 2025 |
| Lenovo        | ThinkPad T410 2522AF6       | [b7291b991b](https://linux-hardware.org/?probe=b7291b991b) | Mar 28, 2025 |
| Dell          | Vostro 3558                 | [6140b9f9eb](https://linux-hardware.org/?probe=6140b9f9eb) | Mar 26, 2025 |
| Dell          | Precision 3520              | [b321c3a06e](https://linux-hardware.org/?probe=b321c3a06e) | Mar 22, 2025 |
| Toshiba       | Satellite L50-B             | [5a1d23174a](https://linux-hardware.org/?probe=5a1d23174a) | Mar 18, 2025 |
| Dell          | Latitude E4300              | [4b85adb345](https://linux-hardware.org/?probe=4b85adb345) | Mar 16, 2025 |
| HP            | Pavilion 17                 | [86d5e97cd7](https://linux-hardware.org/?probe=86d5e97cd7) | Mar 14, 2025 |
| Lenovo        | ThinkPad W510 4213630       | [adcb6b4414](https://linux-hardware.org/?probe=adcb6b4414) | Mar 09, 2025 |
| HP            | ProBook 6545b               | [0282e61c1d](https://linux-hardware.org/?probe=0282e61c1d) | Mar 06, 2025 |
| Apple         | MacBookAir7,2               | [f19f132b1a](https://linux-hardware.org/?probe=f19f132b1a) | Mar 02, 2025 |
| UMAX          | N14R                        | [ffd9e38b16](https://linux-hardware.org/?probe=ffd9e38b16) | Feb 17, 2025 |
| Lenovo        | ThinkPad E555 20DH000WGE    | [ca6830af49](https://linux-hardware.org/?probe=ca6830af49) | Feb 13, 2025 |
| Dell          | Latitude E4300              | [65d0fb553a](https://linux-hardware.org/?probe=65d0fb553a) | Feb 11, 2025 |
| HP            | ZBook 17 G5                 | [2345c8673c](https://linux-hardware.org/?probe=2345c8673c) | Feb 11, 2025 |
| HP            | 2000                        | [4778c8e731](https://linux-hardware.org/?probe=4778c8e731) | Feb 09, 2025 |
| Dell          | Latitude 5500               | [350828035d](https://linux-hardware.org/?probe=350828035d) | Feb 07, 2025 |
| Dell          | Latitude 5500               | [a00d52df90](https://linux-hardware.org/?probe=a00d52df90) | Feb 07, 2025 |
| MSI           | GL75 9SD                    | [dc97a18785](https://linux-hardware.org/?probe=dc97a18785) | Feb 02, 2025 |
| Acer          | Aspire E1-531               | [f824f69578](https://linux-hardware.org/?probe=f824f69578) | Jan 26, 2025 |
| Acer          | TravelMate 5210             | [379e44855f](https://linux-hardware.org/?probe=379e44855f) | Jan 05, 2025 |
| Dell          | Vostro 1500                 | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [b4a2895025](https://linux-hardware.org/?probe=b4a2895025) | Dec 28, 2024 |
| Lenovo        | ThinkPad T420 418062U       | [f06b701043](https://linux-hardware.org/?probe=f06b701043) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [7aa92e6daf](https://linux-hardware.org/?probe=7aa92e6daf) | Dec 27, 2024 |
| Fujitsu Si... | LIFEBOOK S7220              | [2f65653f5c](https://linux-hardware.org/?probe=2f65653f5c) | Dec 27, 2024 |
| Lenovo        | ThinkPad T520 42424UU       | [5de1acb22e](https://linux-hardware.org/?probe=5de1acb22e) | Dec 27, 2024 |
| Dell          | Latitude E4300              | [cfcc3cbd9f](https://linux-hardware.org/?probe=cfcc3cbd9f) | Dec 23, 2024 |
| Dell          | Latitude E4300              | [e67d828b77](https://linux-hardware.org/?probe=e67d828b77) | Dec 23, 2024 |
| Gateway       | NE56R                       | [cefc202761](https://linux-hardware.org/?probe=cefc202761) | Dec 10, 2024 |
| HP            | Pavilion 17                 | [0ca43719ed](https://linux-hardware.org/?probe=0ca43719ed) | Dec 06, 2024 |
| Toshiba       | Satellite C660D             | [ae20ba1091](https://linux-hardware.org/?probe=ae20ba1091) | Dec 03, 2024 |
| MSI           | MS-N014                     | [8f4f502803](https://linux-hardware.org/?probe=8f4f502803) | Nov 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [066e955a01](https://linux-hardware.org/?probe=066e955a01) | Nov 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [412e0842bc](https://linux-hardware.org/?probe=412e0842bc) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6cd8e82a85](https://linux-hardware.org/?probe=6cd8e82a85) | Nov 21, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [2488665eda](https://linux-hardware.org/?probe=2488665eda) | Nov 15, 2024 |
| HP            | EliteBook 820 G1            | [c4b2bda42d](https://linux-hardware.org/?probe=c4b2bda42d) | Nov 09, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | [06aea2ac21](https://linux-hardware.org/?probe=06aea2ac21) | Nov 05, 2024 |
| Acer          | Aspire SW5-012              | [aed9a62d9a](https://linux-hardware.org/?probe=aed9a62d9a) | Nov 04, 2024 |
| Acer          | Extensa 5635ZG              | [46d4a76e28](https://linux-hardware.org/?probe=46d4a76e28) | Nov 02, 2024 |
| Lenovo        | Z70-80 80FG                 | [36e44b1959](https://linux-hardware.org/?probe=36e44b1959) | Oct 29, 2024 |
| Dell          | Latitude D830               | [9dcccfc8bd](https://linux-hardware.org/?probe=9dcccfc8bd) | Oct 28, 2024 |
| Dell          | Latitude D530               | [c1459031b7](https://linux-hardware.org/?probe=c1459031b7) | Oct 25, 2024 |
| ASUSTek       | K55A                        | [d0eea3c30a](https://linux-hardware.org/?probe=d0eea3c30a) | Oct 25, 2024 |
| Dell          | Latitude E7450              | [49d9a72f4e](https://linux-hardware.org/?probe=49d9a72f4e) | Oct 07, 2024 |
| HP            | ENVY 17 Leap Motion SE N... | [a8c1a124a9](https://linux-hardware.org/?probe=a8c1a124a9) | Oct 06, 2024 |
| Dell          | Inspiron 3543               | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| HP            | 625 (VW697EC)               | [ae4660d758](https://linux-hardware.org/?probe=ae4660d758) | Oct 04, 2024 |
| HP            | 625 (VW697EC)               | [933fa4ee91](https://linux-hardware.org/?probe=933fa4ee91) | Oct 03, 2024 |
| ASUSTek       | X405UA                      | [d9a22e6539](https://linux-hardware.org/?probe=d9a22e6539) | Sep 23, 2024 |
| Acer          | Aspire M5-583P              | [402d480ac7](https://linux-hardware.org/?probe=402d480ac7) | Sep 16, 2024 |
| HP            | ProBook 6570b               | [5b28f08307](https://linux-hardware.org/?probe=5b28f08307) | Sep 15, 2024 |
| Lenovo        | ThinkPad X201 36803D7       | [0951b0296f](https://linux-hardware.org/?probe=0951b0296f) | Sep 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [17b6d58dd6](https://linux-hardware.org/?probe=17b6d58dd6) | Sep 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [2c9b283a47](https://linux-hardware.org/?probe=2c9b283a47) | Sep 01, 2024 |
| Lenovo        | V14-IIL 82C4                | [6cce07e59a](https://linux-hardware.org/?probe=6cce07e59a) | Aug 27, 2024 |
| Lenovo        | G50-80 80R0                 | [fef5f4b6e6](https://linux-hardware.org/?probe=fef5f4b6e6) | Aug 27, 2024 |
| ASUSTek       | K93SV                       | [22b7252c1e](https://linux-hardware.org/?probe=22b7252c1e) | Aug 27, 2024 |
| Lenovo        | G50-80 80R0                 | [e2934da80c](https://linux-hardware.org/?probe=e2934da80c) | Aug 26, 2024 |
| MSI           | GF63 Thin 9RCX              | [6ebcf05841](https://linux-hardware.org/?probe=6ebcf05841) | Aug 21, 2024 |
| HP            | ProBook 6570b               | [742d48f2c5](https://linux-hardware.org/?probe=742d48f2c5) | Aug 18, 2024 |
| Dell          | Inspiron 5447               | [3ca233c313](https://linux-hardware.org/?probe=3ca233c313) | Aug 16, 2024 |
| Toshiba       | Satellite L50-B             | [fe95a4d9d9](https://linux-hardware.org/?probe=fe95a4d9d9) | Aug 16, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [4e79a5dba0](https://linux-hardware.org/?probe=4e79a5dba0) | Aug 12, 2024 |
| HP            | Laptop 15s-du3xxx           | [b08bd4b9be](https://linux-hardware.org/?probe=b08bd4b9be) | Aug 03, 2024 |
| Toshiba       | Satellite L50-B             | [00b4917faf](https://linux-hardware.org/?probe=00b4917faf) | Aug 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ee57a214a5](https://linux-hardware.org/?probe=ee57a214a5) | Jul 31, 2024 |
| Acer          | Aspire M5-583P              | [9b35f780ba](https://linux-hardware.org/?probe=9b35f780ba) | Jul 28, 2024 |
| Medion        | S5610                       | [9f7039a688](https://linux-hardware.org/?probe=9f7039a688) | Jul 28, 2024 |
| Wortmann      | FR1220578_1470116           | [45c3f64216](https://linux-hardware.org/?probe=45c3f64216) | Jul 28, 2024 |
| Lenovo        | IdeaPad U410                | [b8b8a7241d](https://linux-hardware.org/?probe=b8b8a7241d) | Jul 27, 2024 |
| Acer          | Aspire M5-583P              | [5c5abd6cdc](https://linux-hardware.org/?probe=5c5abd6cdc) | Jul 25, 2024 |
| ASUSTek       | K93SV                       | [5d544a09dd](https://linux-hardware.org/?probe=5d544a09dd) | Jul 25, 2024 |
| HP            | 14                          | [6381dc091b](https://linux-hardware.org/?probe=6381dc091b) | Jul 24, 2024 |
| HP            | 14                          | [0c704da202](https://linux-hardware.org/?probe=0c704da202) | Jul 22, 2024 |
| HP            | 2000                        | [08dc7124d2](https://linux-hardware.org/?probe=08dc7124d2) | Jul 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [977e94dbb3](https://linux-hardware.org/?probe=977e94dbb3) | Jul 20, 2024 |
| Dell          | Latitude 7390               | [7fbd8bda9a](https://linux-hardware.org/?probe=7fbd8bda9a) | Jul 20, 2024 |
| ASUSTek       | UL50VT                      | [bc1ff179a3](https://linux-hardware.org/?probe=bc1ff179a3) | Jul 14, 2024 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [037fb75cc0](https://linux-hardware.org/?probe=037fb75cc0) | Jul 14, 2024 |
| Apple         | MacBook7,1                  | [118264dd2e](https://linux-hardware.org/?probe=118264dd2e) | Jul 13, 2024 |
| AMI           | Unknown                     | [bbd263c78b](https://linux-hardware.org/?probe=bbd263c78b) | Jul 10, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Dell          | Latitude E6520              | [4945d904f3](https://linux-hardware.org/?probe=4945d904f3) | Jul 05, 2024 |
| Dell          | Latitude E6520              | [43f678ce52](https://linux-hardware.org/?probe=43f678ce52) | Jul 02, 2024 |
| HP            | Notebook                    | [a093e1b594](https://linux-hardware.org/?probe=a093e1b594) | Jun 28, 2024 |
| HP            | Notebook                    | [6e535b1fd1](https://linux-hardware.org/?probe=6e535b1fd1) | Jun 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [1990e46def](https://linux-hardware.org/?probe=1990e46def) | Jun 23, 2024 |
| Lenovo        | Z51-70 80K6                 | [3aea2776ac](https://linux-hardware.org/?probe=3aea2776ac) | Jun 19, 2024 |
| Dell          | Latitude E5500              | [1264354878](https://linux-hardware.org/?probe=1264354878) | Jun 18, 2024 |
| Unknown       | Unknown                     | [77d1ea732e](https://linux-hardware.org/?probe=77d1ea732e) | Jun 17, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [391a3f4d0f](https://linux-hardware.org/?probe=391a3f4d0f) | Jun 09, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [51ddff7468](https://linux-hardware.org/?probe=51ddff7468) | Jun 08, 2024 |
| Lenovo        | IdeaPad U410                | [6945d0a8b4](https://linux-hardware.org/?probe=6945d0a8b4) | Jun 08, 2024 |
| Acer          | Aspire A515-54              | [4964dddf37](https://linux-hardware.org/?probe=4964dddf37) | Jun 04, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [df8e59b402](https://linux-hardware.org/?probe=df8e59b402) | May 30, 2024 |
| MSI           | GS73VR 7RF                  | [9be3005158](https://linux-hardware.org/?probe=9be3005158) | May 28, 2024 |
| HP            | Pavilion dv6                | [295d1b4150](https://linux-hardware.org/?probe=295d1b4150) | May 26, 2024 |
| Lenovo        | V15-ADA 82C7                | [a12122eb2a](https://linux-hardware.org/?probe=a12122eb2a) | May 25, 2024 |
| Acer          | Aspire V3-572G              | [afbfc24291](https://linux-hardware.org/?probe=afbfc24291) | May 22, 2024 |
| HP            | EliteBook 8470p             | [68781bf67c](https://linux-hardware.org/?probe=68781bf67c) | May 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [b853bbc409](https://linux-hardware.org/?probe=b853bbc409) | May 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [6e282ab8d7](https://linux-hardware.org/?probe=6e282ab8d7) | May 15, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | [bfcdaa0e75](https://linux-hardware.org/?probe=bfcdaa0e75) | May 15, 2024 |
| Samsung       | 305E4A/305E5A/305E7A        | [471865ac80](https://linux-hardware.org/?probe=471865ac80) | May 11, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [34e765cb75](https://linux-hardware.org/?probe=34e765cb75) | May 10, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| SCHNEIDER     | SCL141CTP                   | [ce0a785c29](https://linux-hardware.org/?probe=ce0a785c29) | May 07, 2024 |
| HP            | Pavilion Notebook           | [2fc15c8d5c](https://linux-hardware.org/?probe=2fc15c8d5c) | May 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | [687cc00e33](https://linux-hardware.org/?probe=687cc00e33) | May 01, 2024 |
| Dell          | System Vostro 3450          | [eede1fda8a](https://linux-hardware.org/?probe=eede1fda8a) | Apr 30, 2024 |
| Lenovo        | B50-80 80EW                 | [5f20d3fde3](https://linux-hardware.org/?probe=5f20d3fde3) | Apr 29, 2024 |
| HP            | ProBook 450 G1              | [9c5d161110](https://linux-hardware.org/?probe=9c5d161110) | Apr 28, 2024 |
| Acer          | Aspire E5-575T              | [d91600e2a3](https://linux-hardware.org/?probe=d91600e2a3) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [3d7326b94d](https://linux-hardware.org/?probe=3d7326b94d) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | [d217b8e5ee](https://linux-hardware.org/?probe=d217b8e5ee) | Apr 22, 2024 |
| ASUSTek       | K75VM                       | [c863c3ba6b](https://linux-hardware.org/?probe=c863c3ba6b) | Apr 21, 2024 |
| Mediacom      | SmartBook Pro i5            | [fdc40cdd18](https://linux-hardware.org/?probe=fdc40cdd18) | Apr 19, 2024 |
| Dell          | Latitude E5420              | [f937473451](https://linux-hardware.org/?probe=f937473451) | Apr 19, 2024 |
| Acer          | Aspire A515-43              | [fcd5e8e59d](https://linux-hardware.org/?probe=fcd5e8e59d) | Apr 16, 2024 |
| Dell          | XPS 15 9550                 | [22d857c49c](https://linux-hardware.org/?probe=22d857c49c) | Apr 14, 2024 |
| Dell          | Latitude 3440               | [e334ba82e5](https://linux-hardware.org/?probe=e334ba82e5) | Apr 14, 2024 |
| Dell          | Latitude 3440               | [77e2af784e](https://linux-hardware.org/?probe=77e2af784e) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| ASUSTek       | E402SA                      | [5266b4e65d](https://linux-hardware.org/?probe=5266b4e65d) | Apr 13, 2024 |
| ASUSTek       | N552VW                      | [02c36db055](https://linux-hardware.org/?probe=02c36db055) | Apr 12, 2024 |
| Lenovo        | G550 2958                   | [2cebfc34df](https://linux-hardware.org/?probe=2cebfc34df) | Apr 12, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | [9996ba8710](https://linux-hardware.org/?probe=9996ba8710) | Apr 12, 2024 |
| ASUSTek       | N552VW                      | [981a9ddf63](https://linux-hardware.org/?probe=981a9ddf63) | Apr 11, 2024 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [b87b1a20b9](https://linux-hardware.org/?probe=b87b1a20b9) | Apr 06, 2024 |
| MSI           | GT70 2PE                    | [13f21446e0](https://linux-hardware.org/?probe=13f21446e0) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | [ee4bb4963a](https://linux-hardware.org/?probe=ee4bb4963a) | Apr 04, 2024 |
| Dell          | Latitude E7470              | [ea70b2caa0](https://linux-hardware.org/?probe=ea70b2caa0) | Apr 04, 2024 |
| Apple         | MacBookPro9,2               | [cccef069f7](https://linux-hardware.org/?probe=cccef069f7) | Apr 01, 2024 |
| Dell          | Latitude 7480               | [0ab21a354e](https://linux-hardware.org/?probe=0ab21a354e) | Mar 31, 2024 |
| HP            | 15                          | [e1c7ccf97a](https://linux-hardware.org/?probe=e1c7ccf97a) | Mar 31, 2024 |
| Lenovo        | ThinkPad E470 20H1006KGE    | [494ac5439c](https://linux-hardware.org/?probe=494ac5439c) | Mar 28, 2024 |
| Dell          | Inspiron 5537               | [f081fc7478](https://linux-hardware.org/?probe=f081fc7478) | Mar 26, 2024 |
| Dell          | Inspiron 5537               | [bbe46521b3](https://linux-hardware.org/?probe=bbe46521b3) | Mar 26, 2024 |
| Toshiba       | Satellite L355D             | [fd8ddd8b99](https://linux-hardware.org/?probe=fd8ddd8b99) | Mar 25, 2024 |
| Fujitsu       | LIFEBOOK S760               | [9ef9218d97](https://linux-hardware.org/?probe=9ef9218d97) | Mar 24, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | [399c0cd75c](https://linux-hardware.org/?probe=399c0cd75c) | Mar 23, 2024 |
| HP            | 15                          | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| Positivo      | Q232A                       | [46c3ff72eb](https://linux-hardware.org/?probe=46c3ff72eb) | Mar 23, 2024 |
| Positivo      | Q232A                       | [924bb4b4ee](https://linux-hardware.org/?probe=924bb4b4ee) | Mar 23, 2024 |
| Google        | Magma                       | [8fe3986816](https://linux-hardware.org/?probe=8fe3986816) | Mar 20, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [93f757d8b3](https://linux-hardware.org/?probe=93f757d8b3) | Mar 18, 2024 |
| ASUSTek       | K42F                        | [f36df8e399](https://linux-hardware.org/?probe=f36df8e399) | Mar 18, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| Apple         | MacBook5,2                  | [e482eea403](https://linux-hardware.org/?probe=e482eea403) | Mar 13, 2024 |
| Apple         | MacBook5,2                  | [7e0aa86d1c](https://linux-hardware.org/?probe=7e0aa86d1c) | Mar 13, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [b78e24d0f3](https://linux-hardware.org/?probe=b78e24d0f3) | Mar 11, 2024 |
| HP            | ProBook 650 G2              | [532a823ad7](https://linux-hardware.org/?probe=532a823ad7) | Mar 11, 2024 |
| HP            | ProBook 450 G6              | [6fb4193bc2](https://linux-hardware.org/?probe=6fb4193bc2) | Mar 10, 2024 |
| Acer          | Aspire 9410                 | [3307f5eede](https://linux-hardware.org/?probe=3307f5eede) | Mar 09, 2024 |
| HP            | 1000                        | [12df954c4d](https://linux-hardware.org/?probe=12df954c4d) | Mar 09, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [bd5a3177a0](https://linux-hardware.org/?probe=bd5a3177a0) | Mar 09, 2024 |
| HP            | Laptop 15s-du3xxx           | [d3e9bec32e](https://linux-hardware.org/?probe=d3e9bec32e) | Mar 08, 2024 |
| ASUSTek       | X205TAW                     | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [0111e861f4](https://linux-hardware.org/?probe=0111e861f4) | Mar 07, 2024 |
| Acer          | Aspire M3-581G              | [7ab92d79ee](https://linux-hardware.org/?probe=7ab92d79ee) | Mar 06, 2024 |
| Lenovo        | V15-ADA 82C7                | [06c5a79ab1](https://linux-hardware.org/?probe=06c5a79ab1) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | [632d2a6962](https://linux-hardware.org/?probe=632d2a6962) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | [4282677961](https://linux-hardware.org/?probe=4282677961) | Mar 05, 2024 |
| Acer          | Extensa 5635ZG              | [736943715c](https://linux-hardware.org/?probe=736943715c) | Mar 04, 2024 |
| Acer          | Extensa 5635ZG              | [e32263435e](https://linux-hardware.org/?probe=e32263435e) | Mar 04, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f9efc24735](https://linux-hardware.org/?probe=f9efc24735) | Mar 03, 2024 |
| Apple         | MacBookPro5,3               | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| ASUSTek       | E201NA                      | [39326f3b72](https://linux-hardware.org/?probe=39326f3b72) | Mar 01, 2024 |
| HP            | Laptop 15-ef2xxx            | [aae4ff4009](https://linux-hardware.org/?probe=aae4ff4009) | Feb 29, 2024 |
| HP            | Pavilion Sleekbook 14       | [9727db31ca](https://linux-hardware.org/?probe=9727db31ca) | Feb 28, 2024 |
| Dell          | Latitude E7470              | [d4890f7ed2](https://linux-hardware.org/?probe=d4890f7ed2) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [79b3e2b85f](https://linux-hardware.org/?probe=79b3e2b85f) | Feb 26, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | [a0d0bf0a80](https://linux-hardware.org/?probe=a0d0bf0a80) | Feb 25, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | [c398b93c14](https://linux-hardware.org/?probe=c398b93c14) | Feb 24, 2024 |
| HP            | Pavilion 17                 | [274b953249](https://linux-hardware.org/?probe=274b953249) | Feb 23, 2024 |
| HP            | 240 14 inch G9              | [54ea49a49a](https://linux-hardware.org/?probe=54ea49a49a) | Feb 23, 2024 |
| ASUSTek       | X501U                       | [1ebbe09ae2](https://linux-hardware.org/?probe=1ebbe09ae2) | Feb 21, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d7f17aa5fd](https://linux-hardware.org/?probe=d7f17aa5fd) | Feb 21, 2024 |
| Lenovo        | ThinkPad X230 2325CY4       | [6491a02f07](https://linux-hardware.org/?probe=6491a02f07) | Feb 20, 2024 |
| Medion        | Akoya THE TOUCH 10          | [55af4d803a](https://linux-hardware.org/?probe=55af4d803a) | Feb 19, 2024 |
| Acer          | Swift SF314-54              | [a08666a01c](https://linux-hardware.org/?probe=a08666a01c) | Feb 18, 2024 |
| Dell          | Latitude E6410              | [a074f7ca62](https://linux-hardware.org/?probe=a074f7ca62) | Feb 17, 2024 |
| Notebook      | P95_96_97Ex,Rx              | [b3549ef96d](https://linux-hardware.org/?probe=b3549ef96d) | Feb 16, 2024 |
| Dell          | Studio XPS 1640             | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| MSI           | CR61 3M                     | [6a7b9ef9b5](https://linux-hardware.org/?probe=6a7b9ef9b5) | Feb 15, 2024 |
| Acer          | Aspire VX5-591G             | [ab712b6e6c](https://linux-hardware.org/?probe=ab712b6e6c) | Feb 14, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [85e7855e2c](https://linux-hardware.org/?probe=85e7855e2c) | Feb 13, 2024 |
| Unknown       | W1415A                      | [a0c020f290](https://linux-hardware.org/?probe=a0c020f290) | Feb 13, 2024 |
| Lenovo        | G40-45 80E1                 | [23bd060420](https://linux-hardware.org/?probe=23bd060420) | Feb 12, 2024 |
| HP            | Notebook                    | [bdd85f3367](https://linux-hardware.org/?probe=bdd85f3367) | Feb 12, 2024 |
| HP            | Laptop 14-ck0xxx            | [eb7f318e9b](https://linux-hardware.org/?probe=eb7f318e9b) | Feb 11, 2024 |
| Lenovo        | ThinkPad T410 2537CF3       | [7be1e6e033](https://linux-hardware.org/?probe=7be1e6e033) | Feb 10, 2024 |
| HP            | 250 G7 Notebook PC          | [284bdb6d3c](https://linux-hardware.org/?probe=284bdb6d3c) | Feb 10, 2024 |
| HP            | ProBook 430 G1              | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| Dell          | Latitude D630               | [3de4290e6a](https://linux-hardware.org/?probe=3de4290e6a) | Feb 09, 2024 |
| Dell          | Latitude D630               | [bb2c9bba3c](https://linux-hardware.org/?probe=bb2c9bba3c) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | [1c9674a221](https://linux-hardware.org/?probe=1c9674a221) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [7a2fbcd83a](https://linux-hardware.org/?probe=7a2fbcd83a) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [77995292b4](https://linux-hardware.org/?probe=77995292b4) | Feb 08, 2024 |
| Positivo      | C14CR21                     | [0c5f4aa87b](https://linux-hardware.org/?probe=0c5f4aa87b) | Feb 07, 2024 |
| ASUSTek       | UL50VT                      | [b25f172725](https://linux-hardware.org/?probe=b25f172725) | Feb 07, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [1b1a2efc3f](https://linux-hardware.org/?probe=1b1a2efc3f) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | [a16ea9a89e](https://linux-hardware.org/?probe=a16ea9a89e) | Feb 05, 2024 |
| HP            | 650                         | [1787878b4c](https://linux-hardware.org/?probe=1787878b4c) | Feb 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [facc68443a](https://linux-hardware.org/?probe=facc68443a) | Feb 05, 2024 |
| Dell          | Latitude E7470              | [cb6d054e87](https://linux-hardware.org/?probe=cb6d054e87) | Feb 04, 2024 |
| Acer          | Extensa 5635ZG              | [8b36e2aaa6](https://linux-hardware.org/?probe=8b36e2aaa6) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c4e7517d41](https://linux-hardware.org/?probe=c4e7517d41) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [db0469bd8f](https://linux-hardware.org/?probe=db0469bd8f) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | [d779dcc224](https://linux-hardware.org/?probe=d779dcc224) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | [4be4aaae01](https://linux-hardware.org/?probe=4be4aaae01) | Feb 04, 2024 |
| Dell          | Venue 11 Pro 7140           | [35aa24fc01](https://linux-hardware.org/?probe=35aa24fc01) | Feb 04, 2024 |
| Lenovo        | ThinkPad T430 2349HNU       | [f73b7b76a2](https://linux-hardware.org/?probe=f73b7b76a2) | Feb 03, 2024 |
| Toshiba       | Satellite L55-C             | [747bf6b034](https://linux-hardware.org/?probe=747bf6b034) | Feb 03, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [45207cf034](https://linux-hardware.org/?probe=45207cf034) | Jan 31, 2024 |
| HP            | EliteBook 8460p             | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| HP            | ProBook 6570b               | [20537302e6](https://linux-hardware.org/?probe=20537302e6) | Jan 31, 2024 |
| Acer          | Aspire 9420                 | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| Dell          | Inspiron 1545               | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| Acer          | Aspire M3-581G              | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| Dell          | Latitude E6430              | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Toshiba       | Satellite R630              | [c888a8f4d5](https://linux-hardware.org/?probe=c888a8f4d5) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [214ebad454](https://linux-hardware.org/?probe=214ebad454) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | [f2a415adc9](https://linux-hardware.org/?probe=f2a415adc9) | Jan 24, 2024 |
| HP            | ZBook Studio G5             | [114d79aa75](https://linux-hardware.org/?probe=114d79aa75) | Jan 23, 2024 |
| Dell          | Latitude E5420              | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Pavilion g4                 | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| Google        | Kefka                       | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| HP            | Notebook                    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [8dacf655a4](https://linux-hardware.org/?probe=8dacf655a4) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [c3f3bb78c6](https://linux-hardware.org/?probe=c3f3bb78c6) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [046036e7e3](https://linux-hardware.org/?probe=046036e7e3) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | [262a8552de](https://linux-hardware.org/?probe=262a8552de) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Dell          | Latitude 5490               | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | Notebook                    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Sony          | VGN-NS11Z_S                 | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4257aab3ea](https://linux-hardware.org/?probe=4257aab3ea) | Jan 20, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| HP            | EliteBook 840 G1            | [becbec6f26](https://linux-hardware.org/?probe=becbec6f26) | Jan 20, 2024 |
| Acer          | Aspire E5-551G              | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [66c11ee330](https://linux-hardware.org/?probe=66c11ee330) | Jan 17, 2024 |
| Toshiba       | Satellite C850-B820         | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | [640deb41af](https://linux-hardware.org/?probe=640deb41af) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [0e05a50329](https://linux-hardware.org/?probe=0e05a50329) | Jan 16, 2024 |
| HP            | Pavilion 17                 | [3594afe0d4](https://linux-hardware.org/?probe=3594afe0d4) | Jan 16, 2024 |
| Intel         | Unknown                     | [dfd975eff3](https://linux-hardware.org/?probe=dfd975eff3) | Jan 15, 2024 |
| Sony          | VGN-NS11Z_S                 | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| Dell          | Inspiron 3501               | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Toshiba       | Satellite R630              | [0e83a06873](https://linux-hardware.org/?probe=0e83a06873) | Jan 13, 2024 |
| Acer          | Aspire V5-573G              | [09ddfeab43](https://linux-hardware.org/?probe=09ddfeab43) | Jan 12, 2024 |
| ASUSTek       | N56JR                       | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Medion        | E4251 MD61435               | [6a9251fa94](https://linux-hardware.org/?probe=6a9251fa94) | Jan 11, 2024 |
| HP            | Pavilion Sleekbook 14       | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| Toshiba       | Satellite C850              | [38fb6d3619](https://linux-hardware.org/?probe=38fb6d3619) | Jan 09, 2024 |
| Toshiba       | Satellite C850              | [c6faf796f4](https://linux-hardware.org/?probe=c6faf796f4) | Jan 09, 2024 |
| HONOR         | BBR-WAX9                    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| HP            | EliteBook 8440p             | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| ASUSTek       | UL50VT                      | [428d20a1eb](https://linux-hardware.org/?probe=428d20a1eb) | Jan 07, 2024 |
| Acer          | Swift SF314-511             | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire E1-570G              | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| Dell          | Latitude E5420              | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | [900bfdd9a8](https://linux-hardware.org/?probe=900bfdd9a8) | Jan 06, 2024 |
| HP            | ENVY dv6                    | [12f54bd4e0](https://linux-hardware.org/?probe=12f54bd4e0) | Jan 06, 2024 |
| HP            | Pavilion Power Laptop 15... | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Sony          | VGN-CR21S_W                 | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| HP            | ZBook 14u G6                | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Acer          | Aspire E1-570               | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| HP            | Compaq 2510p                | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [ae928b9cc1](https://linux-hardware.org/?probe=ae928b9cc1) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| Lenovo        | V110-15ISK 80TL             | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| HP            | Victus by 15.6 inch Gami... | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude E7270              | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| HP            | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Toshiba       | Satellite C850              | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| Framework     | Laptop                      | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Irbis         | NB12                        | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| Google        | Phaser360                   | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | Notebook                    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Medion        | P7624                       | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Dell          | Inspiron 15 5510            | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| Acer          | AOD257                      | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| Dell          | Latitude 7490               | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| HP            | Pavilion dv7                | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| HP            | Pavilion dv5                | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Dell          | Latitude D830               | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| Lenovo        | Z710 20250                  | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Samsung       | 530XBB                      | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Apple         | MacBookPro14,3              | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Medion        | E5214                       | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Dell          | Latitude 5490               | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| HP            | ZBook 14u G6                | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| HP            | Presario CQ62               | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Lenovo        | Z40-70 20366                | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| Acer          | Aspire E1-531               | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| Dell          | Latitude E7450              | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| Dell          | Latitude E6520              | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| Acer          | Aspire 5736Z                | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | ENVY 17                     | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| HP            | ENVY 17                     | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| Dell          | Precision 7530              | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| Dell          | Latitude 5490               | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| HP            | Pavilion g7                 | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| HP            | Compaq Presario CQ60        | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Alienware     | M14xR2                      | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Medion        | E4251 MD61435               | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Dell          | G3 3579                     | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Acer          | Aspire ES1-521              | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| HP            | Pavilion dv6                | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| HP            | Notebook                    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Dell          | XPS 13 9360                 | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| Hometech      | Ultra Tab 8W                | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Apple         | MacBook4,1                  | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Itautec       | Infoway                     | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| HP            | Pavilion dv7                | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Lenovo        | V110-14IAP 80TF             | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Dell          | Inspiron 5559               | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Framework     | Laptop                      | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| HP            | Laptop 14-dq1xxx            | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| TERRA         | TERRAPC                     | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| HP            | Notebook                    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Lenovo        | G40-30 80FY                 | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | 15                          | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| AMI           | Unknown                     | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.15.0-56-generic  | 136       | 5.02%   |
| 5.11.0-38-generic  | 103       | 3.8%    |
| 5.11.0-27-generic  | 96        | 3.54%   |
| 5.15.0-52-generic  | 94        | 3.47%   |
| 5.15.0-58-generic  | 91        | 3.36%   |
| 5.15.0-46-generic  | 88        | 3.25%   |
| 5.15.0-91-generic  | 84        | 3.1%    |
| 5.13.0-30-generic  | 76        | 2.81%   |
| 5.15.0-78-generic  | 73        | 2.69%   |
| 5.11.0-37-generic  | 66        | 2.44%   |
| 5.15.0-67-generic  | 64        | 2.36%   |
| 5.11.0-40-generic  | 64        | 2.36%   |
| 5.15.0-69-generic  | 63        | 2.33%   |
| 5.11.0-41-generic  | 63        | 2.33%   |
| 5.15.0-88-generic  | 60        | 2.21%   |
| 5.13.0-39-generic  | 60        | 2.21%   |
| 5.15.0-60-generic  | 58        | 2.14%   |
| 5.15.0-76-generic  | 57        | 2.1%    |
| 5.15.0-71-generic  | 57        | 2.1%    |
| 5.11.0-34-generic  | 57        | 2.1%    |
| 5.11.0-43-generic  | 55        | 2.03%   |
| 5.15.0-48-generic  | 51        | 1.88%   |
| 5.13.0-44-generic  | 48        | 1.77%   |
| 5.13.0-40-generic  | 46        | 1.7%    |
| 5.15.0-86-generic  | 44        | 1.62%   |
| 5.15.0-84-generic  | 43        | 1.59%   |
| 5.15.0-53-generic  | 43        | 1.59%   |
| 5.15.0-89-generic  | 41        | 1.51%   |
| 5.13.0-35-generic  | 40        | 1.48%   |
| 5.13.0-28-generic  | 37        | 1.37%   |
| 5.15.0-73-generic  | 36        | 1.33%   |
| 5.15.0-41-generic  | 35        | 1.29%   |
| 5.15.0-79-generic  | 34        | 1.26%   |
| 5.15.0-72-generic  | 31        | 1.14%   |
| 5.13.0-52-generic  | 31        | 1.14%   |
| 5.15.0-83-generic  | 29        | 1.07%   |
| 5.13.0-27-generic  | 28        | 1.03%   |
| 5.11.0-46-generic  | 27        | 1%      |
| 5.13.0-41-generic  | 25        | 0.92%   |
| 5.15.0-139-generic | 23        | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 1369      | 57.02%  |
| 5.11.0   | 550       | 22.91%  |
| 5.13.0   | 408       | 16.99%  |
| 5.8.0    | 24        | 1%      |
| 5.14.0   | 8         | 0.33%   |
| 6.3.13   | 6         | 0.25%   |
| 6.5.7    | 2         | 0.08%   |
| 6.2.16   | 2         | 0.08%   |
| 5.4.0    | 2         | 0.08%   |
| 5.19.0   | 2         | 0.08%   |
| 5.18.15  | 2         | 0.08%   |
| 5.16.0   | 2         | 0.08%   |
| 5.10.0   | 2         | 0.08%   |
| 6.6.7    | 1         | 0.04%   |
| 6.6.1    | 1         | 0.04%   |
| 6.5.0    | 1         | 0.04%   |
| 6.3.2    | 1         | 0.04%   |
| 6.3.1    | 1         | 0.04%   |
| 6.2.14   | 1         | 0.04%   |
| 6.1.22   | 1         | 0.04%   |
| 6.0.19   | 1         | 0.04%   |
| 6.0.0    | 1         | 0.04%   |
| 5.4.180  | 1         | 0.04%   |
| 5.19.9   | 1         | 0.04%   |
| 5.19.14  | 1         | 0.04%   |
| 5.19.12  | 1         | 0.04%   |
| 5.19.1   | 1         | 0.04%   |
| 5.18.6   | 1         | 0.04%   |
| 5.16.12  | 1         | 0.04%   |
| 5.15.49  | 1         | 0.04%   |
| 5.15.24  | 1         | 0.04%   |
| 5.15.150 | 1         | 0.04%   |
| 5.15.12  | 1         | 0.04%   |
| 5.13.18  | 1         | 0.04%   |
| 5.13.12  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1372      | 57.17%  |
| 5.11    | 550       | 22.92%  |
| 5.13    | 410       | 17.08%  |
| 5.8     | 24        | 1%      |
| 6.3     | 8         | 0.33%   |
| 5.14    | 8         | 0.33%   |
| 5.19    | 6         | 0.25%   |
| 6.5     | 3         | 0.13%   |
| 6.2     | 3         | 0.13%   |
| 5.4     | 3         | 0.13%   |
| 5.18    | 3         | 0.13%   |
| 5.16    | 3         | 0.13%   |
| 6.6     | 2         | 0.08%   |
| 6.0     | 2         | 0.08%   |
| 5.10    | 2         | 0.08%   |
| 6.1     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2308      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1905      | 81.69%  |
| XFCE            | 386       | 16.55%  |
| Unknown         | 19        | 0.81%   |
| KDE5            | 7         | 0.3%    |
| X-Cinnamon      | 4         | 0.17%   |
| Budgie          | 3         | 0.13%   |
| i3              | 2         | 0.09%   |
| Unity           | 1         | 0.04%   |
| LXQt            | 1         | 0.04%   |
| LXDE            | 1         | 0.04%   |
| KDE             | 1         | 0.04%   |
| GNOME Flashback | 1         | 0.04%   |
| Cinnamon        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2265      | 97.34%  |
| Wayland | 52        | 2.23%   |
| Unknown | 9         | 0.39%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1712      | 73.07%  |
| GDM     | 289       | 12.33%  |
| GDM3    | 230       | 9.82%   |
| LightDM | 109       | 4.65%   |
| SDDM    | 2         | 0.09%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 870       | 37.45%  |
| de_DE | 224       | 9.64%   |
| en_GB | 155       | 6.67%   |
| pt_BR | 122       | 5.25%   |
| fr_FR | 100       | 4.3%    |
| es_ES | 86        | 3.7%    |
| it_IT | 85        | 3.66%   |
| en_IN | 69        | 2.97%   |
| pl_PL | 61        | 2.63%   |
| en_CA | 59        | 2.54%   |
| nl_NL | 41        | 1.76%   |
| es_MX | 40        | 1.72%   |
| en_AU | 36        | 1.55%   |
| ru_RU | 26        | 1.12%   |
| pt_PT | 24        | 1.03%   |
| en_ZA | 23        | 0.99%   |
| cs_CZ | 21        | 0.9%    |
| sv_SE | 19        | 0.82%   |
| tr_TR | 17        | 0.73%   |
| en_NZ | 15        | 0.65%   |
| de_CH | 15        | 0.65%   |
| fr_BE | 14        | 0.6%    |
| de_AT | 14        | 0.6%    |
| hu_HU | 13        | 0.56%   |
| es_AR | 13        | 0.56%   |
| es_CL | 12        | 0.52%   |
| nl_BE | 10        | 0.43%   |
| es_CO | 9         | 0.39%   |
| bg_BG | 7         | 0.3%    |
| ja_JP | 6         | 0.26%   |
| es_CR | 6         | 0.26%   |
| en_IE | 6         | 0.26%   |
| el_GR | 6         | 0.26%   |
| da_DK | 6         | 0.26%   |
| ro_RO | 5         | 0.22%   |
| hr_HR | 5         | 0.22%   |
| es_PE | 5         | 0.22%   |
| en_PH | 5         | 0.22%   |
| ar_EG | 5         | 0.22%   |
| sr_RS | 4         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1410      | 60.28%  |
| BIOS | 929       | 39.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2117      | 90.98%  |
| Tmpfs   | 93        | 4%      |
| Overlay | 42        | 1.8%    |
| Zfs     | 40        | 1.72%   |
| Btrfs   | 26        | 1.12%   |
| Xfs     | 4         | 0.17%   |
| Ext2    | 3         | 0.13%   |
| Ext3    | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1820      | 77.65%  |
| GPT     | 408       | 17.41%  |
| MBR     | 116       | 4.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2249      | 97.19%  |
| Yes       | 65        | 2.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2089      | 90.2%   |
| Yes       | 227       | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 494       | 21.4%   |
| Lenovo              | 416       | 18.02%  |
| Dell                | 362       | 15.68%  |
| ASUSTek Computer    | 226       | 9.79%   |
| Acer                | 181       | 7.84%   |
| Toshiba             | 99        | 4.29%   |
| Apple               | 81        | 3.51%   |
| MSI                 | 39        | 1.69%   |
| Samsung Electronics | 36        | 1.56%   |
| Sony                | 34        | 1.47%   |
| Google              | 31        | 1.34%   |
| HUAWEI              | 24        | 1.04%   |
| Unknown             | 22        | 0.95%   |
| Packard Bell        | 17        | 0.74%   |
| Positivo            | 15        | 0.65%   |
| Medion              | 15        | 0.65%   |
| Fujitsu             | 12        | 0.52%   |
| Notebook            | 10        | 0.43%   |
| Chuwi               | 10        | 0.43%   |
| Alienware           | 10        | 0.43%   |
| Multilaser          | 7         | 0.3%    |
| Fujitsu Siemens     | 7         | 0.3%    |
| GPU Company         | 6         | 0.26%   |
| AMI                 | 6         | 0.26%   |
| Thomson             | 5         | 0.22%   |
| LG Electronics      | 5         | 0.22%   |
| Razer               | 4         | 0.17%   |
| Microtech           | 4         | 0.17%   |
| Jumper              | 4         | 0.17%   |
| Itautec             | 4         | 0.17%   |
| Gateway             | 4         | 0.17%   |
| Framework           | 4         | 0.17%   |
| Digibras            | 4         | 0.17%   |
| UMAX                | 3         | 0.13%   |
| TUXEDO              | 3         | 0.13%   |
| Timi                | 3         | 0.13%   |
| Semp Toshiba        | 3         | 0.13%   |
| Mediacom            | 3         | 0.13%   |
| Intel               | 3         | 0.13%   |
| Insyde              | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 35        | 1.52%   |
| HP Notebook                     | 26        | 1.13%   |
| HP Pavilion Notebook            | 15        | 0.65%   |
| HP 15                           | 14        | 0.61%   |
| HP Pavilion dv6                 | 10        | 0.43%   |
| HP Pavilion dv7                 | 9         | 0.39%   |
| HP Pavilion 15                  | 9         | 0.39%   |
| Apple MacBookPro8,1             | 8         | 0.35%   |
| Dell Latitude E6520             | 7         | 0.3%    |
| Apple MacBookPro12,1            | 7         | 0.3%    |
| HP Pavilion g7                  | 6         | 0.26%   |
| HP Pavilion g6                  | 6         | 0.26%   |
| Dell Latitude E6540             | 6         | 0.26%   |
| Dell Latitude E6430             | 6         | 0.26%   |
| Dell Inspiron 1545              | 6         | 0.26%   |
| Dell Inspiron 15-3567           | 6         | 0.26%   |
| Apple MacBookAir7,2             | 6         | 0.26%   |
| Toshiba Satellite C660          | 5         | 0.22%   |
| Lenovo IdeaPad 3 15ALC6 82KU    | 5         | 0.22%   |
| HP ProBook 640 G1               | 5         | 0.22%   |
| HP EliteBook 8460p              | 5         | 0.22%   |
| HP EliteBook 840 G6             | 5         | 0.22%   |
| HP EliteBook 840 G1             | 5         | 0.22%   |
| HP EliteBook 2570p              | 5         | 0.22%   |
| Dell Latitude E7450             | 5         | 0.22%   |
| Dell Latitude E5500             | 5         | 0.22%   |
| Dell Latitude D630              | 5         | 0.22%   |
| Dell Latitude 5490              | 5         | 0.22%   |
| Dell Inspiron 5537              | 5         | 0.22%   |
| Apple MacBookPro11,1            | 5         | 0.22%   |
| Toshiba Satellite C55-C         | 4         | 0.17%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 4         | 0.17%   |
| Lenovo IdeaPad 3 15ADA05 81W1   | 4         | 0.17%   |
| HP Victus by Laptop 16-e0xxx    | 4         | 0.17%   |
| HP Stream Notebook              | 4         | 0.17%   |
| HP Stream Laptop 14-ax0XX       | 4         | 0.17%   |
| HP ProBook 6570b                | 4         | 0.17%   |
| HP Pavilion Laptop 15-eg0xxx    | 4         | 0.17%   |
| HP Laptop 15-db0xxx             | 4         | 0.17%   |
| HP Laptop 15-bw0xx              | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 175       | 7.58%   |
| Dell Latitude         | 144       | 6.24%   |
| Acer Aspire           | 132       | 5.72%   |
| Lenovo IdeaPad        | 126       | 5.46%   |
| Dell Inspiron         | 116       | 5.03%   |
| HP Pavilion           | 114       | 4.94%   |
| Toshiba Satellite     | 82        | 3.55%   |
| HP EliteBook          | 70        | 3.03%   |
| HP ProBook            | 62        | 2.69%   |
| HP Laptop             | 52        | 2.25%   |
| ASUS VivoBook         | 40        | 1.73%   |
| Unknown               | 35        | 1.52%   |
| Dell Vostro           | 28        | 1.21%   |
| HP Notebook           | 26        | 1.13%   |
| Dell XPS              | 24        | 1.04%   |
| HP Compaq             | 22        | 0.95%   |
| Dell Precision        | 20        | 0.87%   |
| HP Stream             | 19        | 0.82%   |
| HP ENVY               | 18        | 0.78%   |
| HP 15                 | 16        | 0.69%   |
| Packard Bell EasyNote | 15        | 0.65%   |
| ASUS ZenBook          | 15        | 0.65%   |
| ASUS ROG              | 15        | 0.65%   |
| ASUS ASUS             | 15        | 0.65%   |
| Lenovo Yoga           | 13        | 0.56%   |
| HP OMEN               | 13        | 0.56%   |
| Lenovo Legion         | 12        | 0.52%   |
| HP ZBook              | 11        | 0.48%   |
| Apple MacBookPro8     | 11        | 0.48%   |
| Fujitsu LIFEBOOK      | 10        | 0.43%   |
| Apple MacBookPro5     | 10        | 0.43%   |
| Apple MacBookPro11    | 10        | 0.43%   |
| Acer Swift            | 10        | 0.43%   |
| Lenovo ThinkBook      | 9         | 0.39%   |
| Dell Studio           | 9         | 0.39%   |
| HP 255                | 8         | 0.35%   |
| HP 250                | 8         | 0.35%   |
| Toshiba TECRA         | 7         | 0.3%    |
| Dell Venue            | 7         | 0.3%    |
| Apple MacBookPro12    | 7         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 205       | 8.88%   |
| 2013 | 195       | 8.45%   |
| 2011 | 194       | 8.41%   |
| 2021 | 191       | 8.28%   |
| 2020 | 165       | 7.15%   |
| 2019 | 156       | 6.76%   |
| 2014 | 146       | 6.33%   |
| 2017 | 145       | 6.28%   |
| 2015 | 142       | 6.15%   |
| 2018 | 141       | 6.11%   |
| 2010 | 131       | 5.68%   |
| 2016 | 126       | 5.46%   |
| 2008 | 110       | 4.77%   |
| 2009 | 83        | 3.6%    |
| 2022 | 64        | 2.77%   |
| 2007 | 56        | 2.43%   |
| 2023 | 37        | 1.6%    |
| 2006 | 20        | 0.87%   |
| 2024 | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2308      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1980      | 84.94%  |
| Enabled  | 351       | 15.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2273      | 98.48%  |
| Yes  | 35        | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 799       | 34.29%  |
| 3.01-4.0    | 621       | 26.65%  |
| 8.01-16.0   | 306       | 13.13%  |
| 16.01-24.0  | 296       | 12.7%   |
| 1.01-2.0    | 137       | 5.88%   |
| 32.01-64.0  | 93        | 3.99%   |
| 2.01-3.0    | 41        | 1.76%   |
| 64.01-256.0 | 17        | 0.73%   |
| 24.01-32.0  | 14        | 0.6%    |
| 0.51-1.0    | 6         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 987       | 38.8%   |
| 2.01-3.0   | 849       | 33.37%  |
| 3.01-4.0   | 343       | 13.48%  |
| 4.01-8.0   | 256       | 10.06%  |
| 0.51-1.0   | 67        | 2.63%   |
| 8.01-16.0  | 36        | 1.42%   |
| 24.01-32.0 | 4         | 0.16%   |
| 16.01-24.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1781      | 75.72%  |
| 2      | 499       | 21.22%  |
| 3      | 51        | 2.17%   |
| 4      | 9         | 0.38%   |
| 0      | 8         | 0.34%   |
| 5      | 3         | 0.13%   |
| 8      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1358      | 58.61%  |
| Yes       | 959       | 41.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1812      | 78.31%  |
| No        | 502       | 21.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2223      | 96.23%  |
| No        | 87        | 3.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1674      | 71.57%  |
| No        | 665       | 28.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 470       | 20.27%  |
| Germany      | 247       | 10.65%  |
| Brazil       | 143       | 6.17%   |
| UK           | 137       | 5.91%   |
| Spain        | 90        | 3.88%   |
| France       | 87        | 3.75%   |
| Italy        | 86        | 3.71%   |
| Canada       | 74        | 3.19%   |
| India        | 72        | 3.1%    |
| Netherlands  | 67        | 2.89%   |
| Mexico       | 56        | 2.41%   |
| Poland       | 53        | 2.29%   |
| Belgium      | 35        | 1.51%   |
| Australia    | 35        | 1.51%   |
| Austria      | 34        | 1.47%   |
| Sweden       | 31        | 1.34%   |
| Russia       | 31        | 1.34%   |
| Portugal     | 30        | 1.29%   |
| Switzerland  | 29        | 1.25%   |
| South Africa | 28        | 1.21%   |
| Turkey       | 27        | 1.16%   |
| Czechia      | 23        | 0.99%   |
| Romania      | 21        | 0.91%   |
| Argentina    | 19        | 0.82%   |
| Norway       | 16        | 0.69%   |
| Hungary      | 16        | 0.69%   |
| New Zealand  | 15        | 0.65%   |
| Greece       | 15        | 0.65%   |
| Colombia     | 15        | 0.65%   |
| Chile        | 15        | 0.65%   |
| Japan        | 14        | 0.6%    |
| Indonesia    | 14        | 0.6%    |
| Ireland      | 11        | 0.47%   |
| Egypt        | 11        | 0.47%   |
| Finland      | 10        | 0.43%   |
| Bulgaria     | 10        | 0.43%   |
| Denmark      | 8         | 0.34%   |
| Croatia      | 8         | 0.34%   |
| Serbia       | 7         | 0.3%    |
| Saudi Arabia | 7         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 20        | 0.82%   |
| Vienna            | 19        | 0.78%   |
| Madrid            | 17        | 0.69%   |
| New York          | 14        | 0.57%   |
| Amsterdam         | 14        | 0.57%   |
| Sao Paulo         | 13        | 0.53%   |
| Hamburg           | 13        | 0.53%   |
| Sydney            | 12        | 0.49%   |
| Rome              | 12        | 0.49%   |
| Paris             | 12        | 0.49%   |
| Munich            | 12        | 0.49%   |
| Bogotá           | 10        | 0.41%   |
| Athens            | 10        | 0.41%   |
| Valencia          | 9         | 0.37%   |
| Rio de Janeiro    | 9         | 0.37%   |
| Milan             | 9         | 0.37%   |
| Mexico City       | 9         | 0.37%   |
| Johannesburg      | 9         | 0.37%   |
| Glasgow           | 9         | 0.37%   |
| Frankfurt am Main | 9         | 0.37%   |
| Denver            | 9         | 0.37%   |
| Delhi             | 9         | 0.37%   |
| Toronto           | 8         | 0.33%   |
| Stockholm         | 8         | 0.33%   |
| Moscow            | 8         | 0.33%   |
| Montreal          | 8         | 0.33%   |
| Melbourne         | 8         | 0.33%   |
| London            | 8         | 0.33%   |
| Dallas            | 8         | 0.33%   |
| Widnau            | 7         | 0.29%   |
| Warsaw            | 7         | 0.29%   |
| Jakarta           | 7         | 0.29%   |
| Istanbul          | 7         | 0.29%   |
| Bengaluru         | 7         | 0.29%   |
| Barcelona         | 7         | 0.29%   |
| Stuttgart         | 6         | 0.24%   |
| Seattle           | 6         | 0.24%   |
| Santiago          | 6         | 0.24%   |
| Nairobi           | 6         | 0.24%   |
| Krakow            | 6         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 349       | 488    | 12.61%  |
| Seagate                     | 307       | 391    | 11.09%  |
| WDC                         | 288       | 362    | 10.4%   |
| Unknown                     | 255       | 345    | 9.21%   |
| Toshiba                     | 239       | 289    | 8.63%   |
| Sandisk                     | 191       | 230    | 6.9%    |
| Kingston                    | 128       | 166    | 4.62%   |
| Crucial                     | 93        | 120    | 3.36%   |
| SK hynix                    | 83        | 94     | 3%      |
| Intel                       | 81        | 100    | 2.93%   |
| HGST                        | 78        | 93     | 2.82%   |
| Micron Technology           | 67        | 85     | 2.42%   |
| Hitachi                     | 64        | 79     | 2.31%   |
| China                       | 39        | 52     | 1.41%   |
| Apple                       | 39        | 46     | 1.41%   |
| A-DATA Technology           | 36        | 43     | 1.3%    |
| KIOXIA                      | 31        | 38     | 1.12%   |
| Intenso                     | 24        | 27     | 0.87%   |
| Unknown                     | 24        | 26     | 0.87%   |
| SPCC                        | 18        | 26     | 0.65%   |
| Netac                       | 18        | 18     | 0.65%   |
| PNY                         | 16        | 19     | 0.58%   |
| LITEONIT                    | 15        | 17     | 0.54%   |
| Fujitsu                     | 14        | 16     | 0.51%   |
| Phison                      | 13        | 17     | 0.47%   |
| Patriot                     | 12        | 14     | 0.43%   |
| LITEON                      | 12        | 14     | 0.43%   |
| Team                        | 11        | 12     | 0.4%    |
| Silicon Motion              | 11        | 12     | 0.4%    |
| Transcend                   | 10        | 13     | 0.36%   |
| Phison Electronics          | 10        | 10     | 0.36%   |
| JMicron Technology          | 10        | 11     | 0.36%   |
| GOODRAM                     | 10        | 11     | 0.36%   |
| MAXIO Technology (Hangzhou) | 7         | 7      | 0.25%   |
| Kingston Technology Company | 7         | 8      | 0.25%   |
| OCZ                         | 6         | 7      | 0.22%   |
| KingSpec                    | 6         | 6      | 0.22%   |
| SABRENT                     | 5         | 6      | 0.18%   |
| Micron/Crucial Technology   | 5         | 7      | 0.18%   |
| Lite-On                     | 5         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                               | 79        | 2.73%   |
| Unknown MMC Card  64GB                               | 72        | 2.49%   |
| Seagate ST1000LM035-1RK172 1TB                       | 42        | 1.45%   |
| Toshiba MQ01ABD100 1TB                               | 38        | 1.31%   |
| Unknown MMC Card  128GB                              | 31        | 1.07%   |
| Toshiba MQ01ABF050 500GB                             | 31        | 1.07%   |
| Kingston SA400S37240G 240GB SSD                      | 30        | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 28        | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                      | 26        | 0.9%    |
| Toshiba MQ04ABF100 1TB                               | 24        | 0.83%   |
| Unknown                                              | 24        | 0.83%   |
| Kingston SA400S37480G 480GB SSD                      | 22        | 0.76%   |
| Unknown MMC Card  16GB                               | 19        | 0.66%   |
| Seagate ST9500325AS 500GB                            | 19        | 0.66%   |
| SanDisk NVMe SSD Drive 256GB                         | 19        | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 19        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                         | 18        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                      | 17        | 0.59%   |
| HGST HTS721010A9E630 1TB                             | 17        | 0.59%   |
| Crucial CT240BX500SSD1 240GB                         | 16        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                         | 15        | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 14        | 0.48%   |
| Unknown SD/MMC/MS PRO 2GB                            | 14        | 0.48%   |
| HGST HTS545050A7E680 500GB                           | 14        | 0.48%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 13        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                         | 13        | 0.45%   |
| Samsung SSD 850 EVO 500GB                            | 13        | 0.45%   |
| HGST HTS541010A9E680 1TB                             | 13        | 0.45%   |
| Seagate Expansion 2TB                                | 12        | 0.42%   |
| Samsung NVMe SSD Drive 256GB                         | 12        | 0.42%   |
| Intel NVMe SSD Drive 512GB                           | 12        | 0.42%   |
| Samsung SSD 860 EVO 500GB                            | 11        | 0.38%   |
| HGST HTS725050A7E630 500GB                           | 11        | 0.38%   |
| Seagate ST9500420AS 500GB                            | 10        | 0.35%   |
| Samsung SSD 850 EVO 250GB                            | 10        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 10        | 0.35%   |
| Crucial CT480BX500SSD1 480GB                         | 10        | 0.35%   |
| China SSD 256GB                                      | 10        | 0.35%   |
| Seagate ST500LM021-1KJ152 500GB                      | 9         | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 9         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 301       | 382    | 32.75%  |
| WDC                 | 223       | 277    | 24.27%  |
| Toshiba             | 185       | 221    | 20.13%  |
| HGST                | 78        | 93     | 8.49%   |
| Hitachi             | 64        | 79     | 6.96%   |
| Samsung Electronics | 19        | 19     | 2.07%   |
| Unknown             | 15        | 16     | 1.63%   |
| Fujitsu             | 14        | 16     | 1.52%   |
| JMicron Technology  | 5         | 6      | 0.54%   |
| Apple               | 5         | 5      | 0.54%   |
| Intenso             | 2         | 2      | 0.22%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| USB3.0              | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| SSK                 | 1         | 1      | 0.11%   |
| Shenzhen            | 1         | 1      | 0.11%   |
| SABRENT             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| KESU                | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 183       | 258    | 18.96%  |
| Kingston            | 111       | 146    | 11.5%   |
| SanDisk             | 97        | 119    | 10.05%  |
| Crucial             | 89        | 114    | 9.22%   |
| WDC                 | 40        | 54     | 4.15%   |
| China               | 38        | 51     | 3.94%   |
| Intel               | 31        | 36     | 3.21%   |
| A-DATA Technology   | 29        | 36     | 3.01%   |
| Toshiba             | 28        | 31     | 2.9%    |
| Apple               | 28        | 33     | 2.9%    |
| Micron Technology   | 26        | 32     | 2.69%   |
| SK hynix            | 22        | 22     | 2.28%   |
| Netac               | 18        | 18     | 1.87%   |
| SPCC                | 17        | 25     | 1.76%   |
| Intenso             | 17        | 18     | 1.76%   |
| PNY                 | 16        | 19     | 1.66%   |
| LITEONIT            | 15        | 17     | 1.55%   |
| Patriot             | 12        | 14     | 1.24%   |
| LITEON              | 12        | 14     | 1.24%   |
| Team                | 11        | 12     | 1.14%   |
| Transcend           | 10        | 13     | 1.04%   |
| GOODRAM             | 9         | 10     | 0.93%   |
| Unknown             | 7         | 9      | 0.73%   |
| OCZ                 | 6         | 7      | 0.62%   |
| KingSpec            | 6         | 6      | 0.62%   |
| ASMT                | 5         | 5      | 0.52%   |
| SABRENT             | 4         | 5      | 0.41%   |
| Phison              | 4         | 7      | 0.41%   |
| Hewlett-Packard     | 4         | 6      | 0.41%   |
| Teclast             | 3         | 3      | 0.31%   |
| Plextor             | 3         | 3      | 0.31%   |
| Mushkin             | 3         | 3      | 0.31%   |
| Lexar               | 3         | 3      | 0.31%   |
| Fanxiang            | 3         | 4      | 0.31%   |
| Apacer              | 3         | 3      | 0.31%   |
| Verbatim            | 2         | 2      | 0.21%   |
| JMicron Technology  | 2         | 2      | 0.21%   |
| HS-SSD-E100         | 2         | 2      | 0.21%   |
| Gigabyte Technology | 2         | 2      | 0.21%   |
| BHT                 | 2         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 918       | 1215   | 34.41%  |
| HDD     | 897       | 1124   | 33.62%  |
| NVMe    | 555       | 743    | 20.8%   |
| MMC     | 257       | 346    | 9.63%   |
| Unknown | 41        | 46     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1676      | 2267   | 65.09%  |
| NVMe | 554       | 739    | 21.51%  |
| MMC  | 257       | 346    | 9.98%   |
| SAS  | 88        | 122    | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1249      | 1632   | 69.43%  |
| 0.51-1.0   | 471       | 598    | 26.18%  |
| 1.01-2.0   | 63        | 84     | 3.5%    |
| 3.01-4.0   | 10        | 16     | 0.56%   |
| 4.01-10.0  | 6         | 9      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 829       | 34.92%  |
| 251-500        | 611       | 25.74%  |
| 501-1000       | 346       | 14.57%  |
| 51-100         | 227       | 9.56%   |
| 21-50          | 149       | 6.28%   |
| 1001-2000      | 76        | 3.2%    |
| 1-20           | 54        | 2.27%   |
| Unknown        | 32        | 1.35%   |
| More than 3000 | 28        | 1.18%   |
| 2001-3000      | 22        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 971       | 38.61%  |
| 21-50          | 752       | 29.9%   |
| 51-100         | 316       | 12.56%  |
| 101-250        | 255       | 10.14%  |
| 251-500        | 111       | 4.41%   |
| 501-1000       | 50        | 1.99%   |
| Unknown        | 32        | 1.27%   |
| 1001-2000      | 14        | 0.56%   |
| More than 3000 | 9         | 0.36%   |
| 2001-3000      | 5         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 3         | 3      | 4.92%   |
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 3.28%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 3.28%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 3.28%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 3.28%   |
| Seagate ST1000LM048-2E7172 1TB                   | 2         | 2      | 3.28%   |
| Seagate ST1000LM035-1RK172 1TB                   | 2         | 2      | 3.28%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 3.28%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 3.28%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.64%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.64%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.64%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.64%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.64%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.64%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.64%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.64%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.64%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.64%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.64%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.64%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.64%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.64%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 1.64%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.64%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.64%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.64%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.64%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.64%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.64%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.64%   |
| POLION SSD 240GB                                 | 1         | 1      | 1.64%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD            | 1         | 1      | 1.64%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 1.64%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 1.64%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD           | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 29.51%  |
| Toshiba             | 9         | 9      | 14.75%  |
| HGST                | 8         | 9      | 13.11%  |
| WDC                 | 7         | 7      | 11.48%  |
| Samsung Electronics | 4         | 4      | 6.56%   |
| Kingston            | 3         | 3      | 4.92%   |
| Hitachi             | 3         | 3      | 4.92%   |
| SK hynix            | 2         | 2      | 3.28%   |
| Teclast             | 1         | 1      | 1.64%   |
| POLION              | 1         | 1      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 1.64%   |
| Drevo               | 1         | 1      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 40%     |
| HGST                | 8         | 9      | 17.78%  |
| WDC                 | 7         | 7      | 15.56%  |
| Toshiba             | 7         | 7      | 15.56%  |
| Hitachi             | 3         | 3      | 6.67%   |
| Samsung Electronics | 2         | 2      | 4.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 46     | 73.77%  |
| SSD  | 14        | 14     | 22.95%  |
| NVMe | 2         | 2      | 3.28%   |

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
| Detected | 2001      | 3027   | 84.29%  |
| Works    | 310       | 382    | 13.06%  |
| Malfunc  | 60        | 62     | 2.53%   |
| Failed   | 2         | 2      | 0.08%   |
| Fixed    | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1652      | 65.09%  |
| AMD                              | 279       | 10.99%  |
| Samsung Electronics              | 179       | 7.05%   |
| SanDisk                          | 107       | 4.22%   |
| SK hynix                         | 59        | 2.32%   |
| Micron Technology                | 42        | 1.65%   |
| KIOXIA                           | 31        | 1.22%   |
| Toshiba America Info Systems     | 27        | 1.06%   |
| Nvidia                           | 26        | 1.02%   |
| Kingston Technology Company      | 24        | 0.95%   |
| Phison Electronics               | 22        | 0.87%   |
| Silicon Motion                   | 14        | 0.55%   |
| ADATA Technology                 | 11        | 0.43%   |
| Micron/Crucial Technology        | 10        | 0.39%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.32%   |
| Marvell Technology Group         | 5         | 0.2%    |
| Lite-On Technology               | 5         | 0.2%    |
| Apple                            | 5         | 0.2%    |
| Union Memory (Shenzhen)          | 4         | 0.16%   |
| Silicon Integrated Systems [SiS] | 4         | 0.16%   |
| ASMedia Technology               | 4         | 0.16%   |
| VIA Technologies                 | 3         | 0.12%   |
| Realtek Semiconductor            | 3         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Solid State Storage Technology   | 2         | 0.08%   |
| Shenzhen Longsys Electronics     | 2         | 0.08%   |
| Seagate Technology               | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Silicon Image                    | 1         | 0.04%   |
| JMicron Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 236       | 8.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 204       | 7.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 174       | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 144       | 5.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 138       | 5.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 101       | 3.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 89        | 3.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 78        | 2.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 73        | 2.66%   |
| Intel Volume Management Device NVMe RAID Controller                              | 67        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 61        | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 61        | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 55        | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 51        | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 51        | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 48        | 1.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 45        | 1.64%   |
| Intel Tiger Lake-LP SATA Controller                                              | 39        | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 37        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 36        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 36        | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 33        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 31        | 1.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 28        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 23        | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 23        | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 23        | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 22        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 20        | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 19        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.69%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 18        | 0.66%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 17        | 0.62%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 17        | 0.62%   |
| Nvidia MCP79 AHCI Controller                                                     | 15        | 0.55%   |
| Intel SSD 660P Series                                                            | 15        | 0.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 14        | 0.51%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 13        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1698      | 64.25%  |
| NVMe | 555       | 21%     |
| RAID | 219       | 8.29%   |
| IDE  | 171       | 6.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1947      | 84.36%  |
| AMD    | 361       | 15.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz             | 35        | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 30        | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.3%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 28        | 1.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 1.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.95%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.91%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.91%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 19        | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.74%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 16        | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 15        | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 15        | 0.65%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 15        | 0.65%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 15        | 0.65%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 14        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 14        | 0.61%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 0.61%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 14        | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 13        | 0.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 13        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 570       | 24.69%  |
| Intel Core i7                        | 385       | 16.67%  |
| Intel Core i3                        | 225       | 9.74%   |
| Intel Celeron                        | 215       | 9.31%   |
| Other                                | 161       | 6.97%   |
| Intel Core 2 Duo                     | 142       | 6.15%   |
| Intel Atom                           | 82        | 3.55%   |
| Intel Pentium                        | 78        | 3.38%   |
| AMD Ryzen 5                          | 76        | 3.29%   |
| AMD Ryzen 7                          | 53        | 2.3%    |
| AMD A6                               | 31        | 1.34%   |
| AMD A4                               | 27        | 1.17%   |
| Intel Pentium Dual-Core              | 26        | 1.13%   |
| AMD A8                               | 23        | 1%      |
| AMD A10                              | 20        | 0.87%   |
| Intel Core 2                         | 16        | 0.69%   |
| AMD Ryzen 3                          | 16        | 0.69%   |
| Intel Pentium Dual                   | 15        | 0.65%   |
| AMD E1                               | 14        | 0.61%   |
| Intel Core M                         | 12        | 0.52%   |
| AMD E                                | 12        | 0.52%   |
| Intel Pentium Silver                 | 10        | 0.43%   |
| AMD Turion 64 X2 Mobile              | 10        | 0.43%   |
| AMD Ryzen 9                          | 10        | 0.43%   |
| AMD Athlon II                        | 6         | 0.26%   |
| Intel Core m5                        | 5         | 0.22%   |
| AMD Ryzen 7 PRO                      | 5         | 0.22%   |
| AMD E2                               | 5         | 0.22%   |
| Intel Pentium Gold                   | 4         | 0.17%   |
| Intel Genuine                        | 4         | 0.17%   |
| Intel Celeron Dual-Core              | 4         | 0.17%   |
| AMD Athlon                           | 4         | 0.17%   |
| Intel Celeron M                      | 3         | 0.13%   |
| AMD Turion II Dual-Core              | 3         | 0.13%   |
| AMD FX                               | 3         | 0.13%   |
| Intel Core i9                        | 2         | 0.09%   |
| AMD V120                             | 2         | 0.09%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile       | 2         | 0.09%   |
| AMD Turion II                        | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1397      | 60.5%   |
| 4      | 674       | 29.19%  |
| 6      | 92        | 3.98%   |
| 8      | 78        | 3.38%   |
| 1      | 29        | 1.26%   |
| 10     | 14        | 0.61%   |
| 12     | 10        | 0.43%   |
| 14     | 9         | 0.39%   |
| 16     | 3         | 0.13%   |
| 24     | 2         | 0.09%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2308      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1514      | 65.6%   |
| 1      | 794       | 34.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2308      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 191       | 8.15%   |
| 0x206a7    | 186       | 7.94%   |
| Unknown    | 161       | 6.87%   |
| 0x40651    | 112       | 4.78%   |
| 0x1067a    | 98        | 4.18%   |
| 0x306d4    | 95        | 4.05%   |
| 0x406e3    | 92        | 3.93%   |
| 0x20655    | 82        | 3.5%    |
| 0x806c1    | 78        | 3.33%   |
| 0x30678    | 73        | 3.12%   |
| 0x806e9    | 67        | 2.86%   |
| 0x806ec    | 63        | 2.69%   |
| 0x806ea    | 60        | 2.56%   |
| 0x306c3    | 60        | 2.56%   |
| 0x706a8    | 52        | 2.22%   |
| 0x406c4    | 51        | 2.18%   |
| 0x6fd      | 42        | 1.79%   |
| 0x906ea    | 39        | 1.66%   |
| 0x706e5    | 39        | 1.66%   |
| 0x506c9    | 37        | 1.58%   |
| 0x10676    | 35        | 1.49%   |
| 0x906e9    | 33        | 1.41%   |
| 0x20652    | 32        | 1.37%   |
| 0x406c3    | 30        | 1.28%   |
| 0x08108109 | 29        | 1.24%   |
| 0x07030105 | 23        | 0.98%   |
| 0x0a50000c | 22        | 0.94%   |
| 0xa0652    | 21        | 0.9%    |
| 0x06006705 | 20        | 0.85%   |
| 0x08108102 | 18        | 0.77%   |
| 0x706a1    | 17        | 0.73%   |
| 0x506e3    | 17        | 0.73%   |
| 0x08608103 | 16        | 0.68%   |
| 0x0700010f | 16        | 0.68%   |
| 0x08600106 | 15        | 0.64%   |
| 0x906a3    | 14        | 0.6%    |
| 0x806d1    | 14        | 0.6%    |
| 0x6f6      | 14        | 0.6%    |
| 0x05000119 | 14        | 0.6%    |
| 0x6fb      | 13        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 301       | 13.04%  |
| IvyBridge        | 199       | 8.62%   |
| SandyBridge      | 192       | 8.32%   |
| Haswell          | 185       | 8.02%   |
| Silvermont       | 167       | 7.24%   |
| Penryn           | 134       | 5.81%   |
| Westmere         | 117       | 5.07%   |
| Skylake          | 114       | 4.94%   |
| Broadwell        | 95        | 4.12%   |
| TigerLake        | 92        | 3.99%   |
| Core             | 83        | 3.6%    |
| Goldmont plus    | 72        | 3.12%   |
| Icelake          | 54        | 2.34%   |
| Unknown          | 54        | 2.34%   |
| Zen+             | 50        | 2.17%   |
| Excavator        | 48        | 2.08%   |
| Zen 3            | 39        | 1.69%   |
| Goldmont         | 39        | 1.69%   |
| Zen 2            | 35        | 1.52%   |
| Puma             | 34        | 1.47%   |
| Alderlake Hybrid | 26        | 1.13%   |
| CometLake        | 25        | 1.08%   |
| Jaguar           | 20        | 0.87%   |
| Bobcat           | 19        | 0.82%   |
| K10              | 17        | 0.74%   |
| Piledriver       | 15        | 0.65%   |
| K8 Hammer        | 14        | 0.61%   |
| Nehalem          | 13        | 0.56%   |
| K10 Llano        | 13        | 0.56%   |
| Tremont          | 10        | 0.43%   |
| Bonnell          | 10        | 0.43%   |
| Zen              | 9         | 0.39%   |
| Steamroller      | 7         | 0.3%    |
| K8 & K10 hybrid  | 6         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1761      | 63.48%  |
| Nvidia                           | 504       | 18.17%  |
| AMD                              | 503       | 18.13%  |
| Silicon Integrated Systems [SiS] | 4         | 0.14%   |
| VIA Technologies                 | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 190       | 6.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 174       | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 116       | 4.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 85        | 2.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 84        | 2.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 82        | 2.86%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 81        | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 77        | 2.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 71        | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 2.27%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 63        | 2.2%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 62        | 2.16%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 61        | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 53        | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 52        | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 39        | 1.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 39        | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.22%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 34        | 1.19%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 33        | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 1.12%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 32        | 1.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 1.08%   |
| AMD Lucienne                                                                             | 25        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 23        | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.8%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 22        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 0.73%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 20        | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 17        | 0.59%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 16        | 0.56%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 16        | 0.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 0.52%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 15        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1330      | 57.53%  |
| 1 x AMD        | 340       | 14.71%  |
| Intel + Nvidia | 337       | 14.58%  |
| 1 x Nvidia     | 123       | 5.32%   |
| Intel + AMD    | 88        | 3.81%   |
| 2 x AMD        | 38        | 1.64%   |
| AMD + Nvidia   | 38        | 1.64%   |
| Other          | 6         | 0.26%   |
| 2 x Nvidia     | 6         | 0.26%   |
| 1 x SiS        | 4         | 0.17%   |
| 1 x VIA        | 2         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2039      | 87.96%  |
| Proprietary | 232       | 10.01%  |
| Unknown     | 47        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1600      | 68.35%  |
| 0.01-0.5   | 305       | 13.03%  |
| 1.01-2.0   | 183       | 7.82%   |
| 0.51-1.0   | 142       | 6.07%   |
| 3.01-4.0   | 60        | 2.56%   |
| 5.01-6.0   | 22        | 0.94%   |
| 7.01-8.0   | 16        | 0.68%   |
| 2.01-3.0   | 11        | 0.47%   |
| 8.01-16.0  | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 483       | 19.85%  |
| Chimei Innolux          | 348       | 14.3%   |
| LG Display              | 342       | 14.06%  |
| BOE                     | 342       | 14.06%  |
| Samsung Electronics     | 268       | 11.02%  |
| Apple                   | 79        | 3.25%   |
| Chi Mei Optoelectronics | 69        | 2.84%   |
| Lenovo                  | 47        | 1.93%   |
| Sharp                   | 45        | 1.85%   |
| Goldstar                | 40        | 1.64%   |
| Dell                    | 37        | 1.52%   |
| LG Philips              | 34        | 1.4%    |
| PANDA                   | 31        | 1.27%   |
| InfoVision              | 23        | 0.95%   |
| Hewlett-Packard         | 20        | 0.82%   |
| CPT                     | 15        | 0.62%   |
| Acer                    | 12        | 0.49%   |
| Vizio                   | 11        | 0.45%   |
| Philips                 | 11        | 0.45%   |
| BenQ                    | 11        | 0.45%   |
| Ancor Communications    | 9         | 0.37%   |
| Sony                    | 8         | 0.33%   |
| ASUSTek Computer        | 7         | 0.29%   |
| AOC                     | 7         | 0.29%   |
| SLD                     | 6         | 0.25%   |
| LGD                     | 6         | 0.25%   |
| HannStar                | 6         | 0.25%   |
| Unknown                 | 6         | 0.25%   |
| Toshiba                 | 5         | 0.21%   |
| InnoLux Display         | 5         | 0.21%   |
| BOE Technology Group    | 5         | 0.21%   |
| ViewSonic               | 4         | 0.16%   |
| Panasonic               | 4         | 0.16%   |
| KDC                     | 4         | 0.16%   |
| CSO                     | 4         | 0.16%   |
| TMX                     | 3         | 0.12%   |
| MSI                     | 3         | 0.12%   |
| Iiyama                  | 3         | 0.12%   |
| Eizo                    | 3         | 0.12%   |
| VIE                     | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 23        | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.73%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 16        | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.57%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 14        | 0.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 14        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.49%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 11        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.45%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 9         | 0.37%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 8         | 0.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 7         | 0.29%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 6         | 0.24%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 6         | 0.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 6         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 933       | 39.67%  |
| 1920x1080 (FHD)    | 798       | 33.93%  |
| 1600x900 (HD+)     | 146       | 6.21%   |
| 1280x800 (WXGA)    | 122       | 5.19%   |
| 1440x900 (WXGA+)   | 56        | 2.38%   |
| 3840x2160 (4K)     | 53        | 2.25%   |
| 1920x1200 (WUXGA)  | 34        | 1.45%   |
| 2560x1600          | 28        | 1.19%   |
| 2560x1440 (QHD)    | 24        | 1.02%   |
| 1680x1050 (WSXGA+) | 17        | 0.72%   |
| 1280x1024 (SXGA)   | 13        | 0.55%   |
| 2880x1800          | 11        | 0.47%   |
| 2560x1080          | 11        | 0.47%   |
| 2160x1440          | 10        | 0.43%   |
| Unknown            | 9         | 0.38%   |
| 3200x1800 (QHD+)   | 8         | 0.34%   |
| 2256x1504          | 8         | 0.34%   |
| 1360x768           | 8         | 0.34%   |
| 1920x540           | 7         | 0.3%    |
| 3840x2400          | 6         | 0.26%   |
| 1024x600           | 6         | 0.26%   |
| 3440x1440          | 5         | 0.21%   |
| 3840x1080          | 4         | 0.17%   |
| 2880x1920          | 4         | 0.17%   |
| 2304x1440          | 3         | 0.13%   |
| 1920x515           | 3         | 0.13%   |
| 5760x1080          | 2         | 0.09%   |
| 2880x1620          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3600x1080          | 1         | 0.04%   |
| 3456x2160          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1031      | 42.55%  |
| 13      | 357       | 14.73%  |
| 14      | 295       | 12.17%  |
| 17      | 195       | 8.05%   |
| 11      | 91        | 3.76%   |
| 12      | 73        | 3.01%   |
| 27      | 44        | 1.82%   |
| 24      | 43        | 1.77%   |
| Unknown | 42        | 1.73%   |
| 16      | 29        | 1.2%    |
| 23      | 28        | 1.16%   |
| 18      | 27        | 1.11%   |
| 31      | 25        | 1.03%   |
| 21      | 24        | 0.99%   |
| 34      | 16        | 0.66%   |
| 10      | 15        | 0.62%   |
| 19      | 13        | 0.54%   |
| 54      | 9         | 0.37%   |
| 40      | 7         | 0.29%   |
| 22      | 6         | 0.25%   |
| 20      | 6         | 0.25%   |
| 84      | 5         | 0.21%   |
| 72      | 4         | 0.17%   |
| 32      | 4         | 0.17%   |
| 25      | 4         | 0.17%   |
| 63      | 3         | 0.12%   |
| 48      | 3         | 0.12%   |
| 37      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 52      | 2         | 0.08%   |
| 49      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 42      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 86      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 69      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1510      | 62.58%  |
| 201-300     | 340       | 14.09%  |
| 351-400     | 233       | 9.66%   |
| 501-600     | 112       | 4.64%   |
| 401-500     | 73        | 3.03%   |
| Unknown     | 42        | 1.74%   |
| 601-700     | 32        | 1.33%   |
| 1001-1500   | 25        | 1.04%   |
| 701-800     | 21        | 0.87%   |
| 1501-2000   | 11        | 0.46%   |
| 801-900     | 10        | 0.41%   |
| 101-200     | 2         | 0.08%   |
| 901-1000    | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1869      | 83.85%  |
| 16/10   | 260       | 11.66%  |
| Unknown | 29        | 1.3%    |
| 3/2     | 28        | 1.26%   |
| 21/9    | 16        | 0.72%   |
| 5/4     | 12        | 0.54%   |
| 4/3     | 6         | 0.27%   |
| 3.73    | 3         | 0.13%   |
| 32/9    | 2         | 0.09%   |
| 0.62    | 2         | 0.09%   |
| 1.96    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1029      | 42.49%  |
| 81-90          | 544       | 22.46%  |
| 121-130        | 160       | 6.61%   |
| 71-80          | 108       | 4.46%   |
| 51-60          | 92        | 3.8%    |
| 201-250        | 90        | 3.72%   |
| 61-70          | 71        | 2.93%   |
| 301-350        | 46        | 1.9%    |
| 351-500        | 45        | 1.86%   |
| Unknown        | 42        | 1.73%   |
| 141-150        | 34        | 1.4%    |
| More than 1000 | 32        | 1.32%   |
| 151-200        | 28        | 1.16%   |
| 131-140        | 28        | 1.16%   |
| 111-120        | 22        | 0.91%   |
| 501-1000       | 18        | 0.74%   |
| 41-50          | 14        | 0.58%   |
| 91-100         | 9         | 0.37%   |
| 251-300        | 8         | 0.33%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 965       | 40.29%  |
| 121-160       | 831       | 34.7%   |
| 51-100        | 335       | 13.99%  |
| 161-240       | 142       | 5.93%   |
| Unknown       | 43        | 1.8%    |
| More than 240 | 40        | 1.67%   |
| 1-50          | 39        | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2020      | 85.92%  |
| 2     | 267       | 11.36%  |
| 0     | 43        | 1.83%   |
| 3     | 18        | 0.77%   |
| 4     | 2         | 0.09%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1180      | 32.33%  |
| Intel                             | 1052      | 28.82%  |
| Qualcomm Atheros                  | 554       | 15.18%  |
| Broadcom                          | 309       | 8.47%   |
| Broadcom Limited                  | 103       | 2.82%   |
| Marvell Technology Group          | 47        | 1.29%   |
| Ralink                            | 46        | 1.26%   |
| MediaTek                          | 39        | 1.07%   |
| TP-Link                           | 29        | 0.79%   |
| Dell                              | 26        | 0.71%   |
| Nvidia                            | 24        | 0.66%   |
| Samsung Electronics               | 22        | 0.6%    |
| ASIX Electronics                  | 22        | 0.6%    |
| Ralink Technology                 | 18        | 0.49%   |
| Sierra Wireless                   | 14        | 0.38%   |
| DisplayLink                       | 14        | 0.38%   |
| JMicron Technology                | 13        | 0.36%   |
| Hewlett-Packard                   | 12        | 0.33%   |
| Shenzhen Goodix Technology        | 11        | 0.3%    |
| Xiaomi                            | 10        | 0.27%   |
| Huawei Technologies               | 10        | 0.27%   |
| Qualcomm                          | 7         | 0.19%   |
| Ericsson Business Mobile Networks | 7         | 0.19%   |
| OPPO Electronics                  | 6         | 0.16%   |
| NetGear                           | 6         | 0.16%   |
| Qualcomm Atheros Communications   | 5         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.11%   |
| Motorola PCS                      | 4         | 0.11%   |
| Edimax Technology                 | 4         | 0.11%   |
| ASUSTek Computer                  | 4         | 0.11%   |
| VIA Technologies                  | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| Google                            | 3         | 0.08%   |
| D-Link System                     | 3         | 0.08%   |
| U-Blox                            | 2         | 0.05%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| Lenovo                            | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |
| ZyXEL Communications              | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 640       | 14.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 278       | 6.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 113       | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 98        | 2.26%   |
| Intel Wireless 7260                                                    | 89        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 86        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 84        | 1.94%   |
| Intel Wireless 7265                                                    | 79        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 76        | 1.75%   |
| Intel Wireless 8265 / 8275                                             | 70        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 63        | 1.45%   |
| Intel Wi-Fi 6 AX201                                                    | 61        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 58        | 1.34%   |
| Intel Wireless 8260                                                    | 56        | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                          | 56        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                    | 52        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 48        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 46        | 1.06%   |
| Intel Wireless 3165                                                    | 46        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 45        | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 44        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 42        | 0.97%   |
| Intel WiFi Link 5100                                                   | 35        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 34        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 33        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 31        | 0.71%   |
| Intel Centrino Ultimate-N 6300                                         | 30        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 29        | 0.67%   |
| Intel Wireless 3160                                                    | 29        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                               | 29        | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 0.65%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 26        | 0.6%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 26        | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 0.6%    |
| Intel Ethernet Connection I217-LM                                      | 25        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 0.58%   |
| Intel Centrino Advanced-N 6200                                         | 22        | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 21        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                               | 21        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1000      | 42.25%  |
| Qualcomm Atheros                  | 472       | 19.94%  |
| Realtek Semiconductor             | 397       | 16.77%  |
| Broadcom                          | 245       | 10.35%  |
| Broadcom Limited                  | 69        | 2.92%   |
| Ralink                            | 46        | 1.94%   |
| MediaTek                          | 32        | 1.35%   |
| TP-Link                           | 21        | 0.89%   |
| Ralink Technology                 | 18        | 0.76%   |
| Dell                              | 15        | 0.63%   |
| Sierra Wireless                   | 14        | 0.59%   |
| NetGear                           | 6         | 0.25%   |
| Qualcomm Atheros Communications   | 5         | 0.21%   |
| Edimax Technology                 | 4         | 0.17%   |
| D-Link System                     | 3         | 0.13%   |
| ASUSTek Computer                  | 3         | 0.13%   |
| Linksys                           | 2         | 0.08%   |
| Hewlett-Packard                   | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| ZyXEL Communications              | 1         | 0.04%   |
| ZyDAS                             | 1         | 0.04%   |
| TRENDnet                          | 1         | 0.04%   |
| Tenda                             | 1         | 0.04%   |
| Qualcomm                          | 1         | 0.04%   |
| Microsoft                         | 1         | 0.04%   |
| Mercucys                          | 1         | 0.04%   |
| Fibocom                           | 1         | 0.04%   |
| Ericsson Business Mobile Networks | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |
| Askey Computer                    | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 4.73%   |
| Intel Wireless 7260                                                     | 89        | 3.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 84        | 3.51%   |
| Intel Wireless 7265                                                     | 79        | 3.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 76        | 3.18%   |
| Intel Wireless 8265 / 8275                                              | 70        | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 2.63%   |
| Intel Wi-Fi 6 AX201                                                     | 61        | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 58        | 2.43%   |
| Intel Wireless 8260                                                     | 56        | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 2.34%   |
| Intel Wi-Fi 6 AX200                                                     | 52        | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.92%   |
| Intel Wireless 3165                                                     | 46        | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 44        | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 42        | 1.76%   |
| Intel WiFi Link 5100                                                    | 35        | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 34        | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 33        | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 1.3%    |
| Intel Centrino Ultimate-N 6300                                          | 30        | 1.25%   |
| Intel Wireless 3160                                                     | 29        | 1.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 26        | 1.09%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 26        | 1.09%   |
| Intel Centrino Advanced-N 6200                                          | 22        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 0.88%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 20        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 20        | 0.84%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 20        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 20        | 0.84%   |
| Intel Centrino Advanced-N 6235                                          | 20        | 0.84%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 20        | 0.84%   |
| Realtek 802.11n WLAN Adapter                                            | 19        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 18        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 18        | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 18        | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 996       | 52.84%  |
| Intel                            | 394       | 20.9%   |
| Qualcomm Atheros                 | 138       | 7.32%   |
| Broadcom                         | 102       | 5.41%   |
| Marvell Technology Group         | 47        | 2.49%   |
| Broadcom Limited                 | 38        | 2.02%   |
| Nvidia                           | 24        | 1.27%   |
| ASIX Electronics                 | 22        | 1.17%   |
| Samsung Electronics              | 21        | 1.11%   |
| DisplayLink                      | 14        | 0.74%   |
| JMicron Technology               | 13        | 0.69%   |
| Xiaomi                           | 10        | 0.53%   |
| TP-Link                          | 8         | 0.42%   |
| Huawei Technologies              | 7         | 0.37%   |
| Qualcomm                         | 6         | 0.32%   |
| OPPO Electronics                 | 6         | 0.32%   |
| MediaTek                         | 6         | 0.32%   |
| Silicon Integrated Systems [SiS] | 4         | 0.21%   |
| Motorola PCS                     | 4         | 0.21%   |
| VIA Technologies                 | 3         | 0.16%   |
| Hewlett-Packard                  | 3         | 0.16%   |
| Google                           | 3         | 0.16%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| vivo                             | 1         | 0.05%   |
| T & A Mobile Phones              | 1         | 0.05%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| Novatel Wireless                 | 1         | 0.05%   |
| Motorola BCS                     | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| GoPro                            | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 640       | 33.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 278       | 14.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 98        | 5.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 45        | 2.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 29        | 1.53%   |
| Intel 82577LM Gigabit Network Connection                               | 29        | 1.53%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 1.48%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 1.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 25        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 1.32%   |
| Intel 82567LM Gigabit Network Connection                               | 21        | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                          | 20        | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 18        | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 17        | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 17        | 0.9%    |
| Intel Ethernet Connection I219-V                                       | 17        | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 16        | 0.84%   |
| Nvidia MCP79 Ethernet                                                  | 15        | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 15        | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 14        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 13        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 12        | 0.63%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 12        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 11        | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 11        | 0.58%   |
| Intel 82566MM Gigabit Network Connection                               | 11        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 10        | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 8         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                  | 8         | 0.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 7         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 7         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2224      | 54.52%  |
| Ethernet | 1804      | 44.23%  |
| Modem    | 47        | 1.15%   |
| Unknown  | 4         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1890      | 79.35%  |
| Ethernet | 491       | 20.61%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1642      | 71.08%  |
| 1     | 558       | 24.16%  |
| 0     | 99        | 4.29%   |
| 3     | 10        | 0.43%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1615      | 68.64%  |
| Yes  | 738       | 31.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 724       | 42.71%  |
| Realtek Semiconductor           | 202       | 11.92%  |
| Qualcomm Atheros Communications | 190       | 11.21%  |
| Broadcom                        | 109       | 6.43%   |
| IMC Networks                    | 83        | 4.9%    |
| Apple                           | 70        | 4.13%   |
| Foxconn / Hon Hai               | 60        | 3.54%   |
| Lite-On Technology              | 55        | 3.24%   |
| Dell                            | 45        | 2.65%   |
| Hewlett-Packard                 | 35        | 2.06%   |
| Toshiba                         | 32        | 1.89%   |
| Cambridge Silicon Radio         | 22        | 1.3%    |
| Ralink                          | 18        | 1.06%   |
| ASUSTek Computer                | 11        | 0.65%   |
| Realtek                         | 9         | 0.53%   |
| Foxconn International           | 7         | 0.41%   |
| Alps Electric                   | 7         | 0.41%   |
| Ralink Technology               | 3         | 0.18%   |
| Askey Computer                  | 3         | 0.18%   |
| Integrated System Solution      | 2         | 0.12%   |
| Unknown                         | 2         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Conwise Technology              | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 350       | 20.62%  |
| Realtek Bluetooth Radio                             | 135       | 7.96%   |
| Intel AX201 Bluetooth                               | 110       | 6.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 101       | 5.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 80        | 4.71%   |
| Intel AX200 Bluetooth                               | 50        | 2.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 46        | 2.71%   |
| Apple Bluetooth Host Controller                     | 43        | 2.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 34        | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 1.71%   |
| IMC Networks Bluetooth Device                       | 28        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 26        | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 21        | 1.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 21        | 1.24%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 1.18%   |
| Intel AX210 Bluetooth                               | 20        | 1.18%   |
| IMC Networks Wireless_Device                        | 20        | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.12%   |
| IMC Networks Bluetooth Radio                        | 19        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.12%   |
| Ralink RT3290 Bluetooth                             | 18        | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 1.06%   |
| Intel Bluetooth Device                              | 17        | 1%      |
| Dell DW375 Bluetooth Module                         | 16        | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.77%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.71%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.65%   |
| Toshiba Bluetooth Device                            | 10        | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.59%   |
| Realtek Bluetooth Radio                             | 9         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 8         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1852      | 69.78%  |
| AMD                                  | 421       | 15.86%  |
| Nvidia                               | 297       | 11.19%  |
| Generalplus Technology               | 6         | 0.23%   |
| C-Media Electronics                  | 6         | 0.23%   |
| Realtek Semiconductor                | 5         | 0.19%   |
| Lenovo                               | 5         | 0.19%   |
| SteelSeries ApS                      | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 4         | 0.15%   |
| Logitech                             | 4         | 0.15%   |
| PreSonus Audio Electronics           | 3         | 0.11%   |
| Plantronics                          | 3         | 0.11%   |
| JMTek                                | 3         | 0.11%   |
| VIA Technologies                     | 2         | 0.08%   |
| Texas Instruments                    | 2         | 0.08%   |
| Tenx Technology                      | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| KTMicro                              | 2         | 0.08%   |
| Focusrite-Novation                   | 2         | 0.08%   |
| DSEA A/S                             | 2         | 0.08%   |
| Creative Technology                  | 2         | 0.08%   |
| Corsair                              | 2         | 0.08%   |
| Apple                                | 2         | 0.08%   |
| XMOS                                 | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Roland                               | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| Nordic Semiconductor ASA             | 1         | 0.04%   |
| M-Audio                              | 1         | 0.04%   |
| Kingston Technology                  | 1         | 0.04%   |
| Huawei Technologies                  | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| GN Netcom                            | 1         | 0.04%   |
| FiiO Electronics Technology          | 1         | 0.04%   |
| EasyPass Industrial                  | 1         | 0.04%   |
| Dell                                 | 1         | 0.04%   |
| Conexant Systems                     | 1         | 0.04%   |
| CMX Systems                          | 1         | 0.04%   |
| BEHRINGER International              | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 236       | 7.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 235       | 7.27%   |
| AMD Ryzen HD Audio Controller                                                                     | 163       | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 155       | 4.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 130       | 4.02%   |
| Intel 8 Series HD Audio Controller                                                                | 117       | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 113       | 3.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 111       | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 97        | 3%      |
| Intel Broadwell-U Audio Controller                                                                | 95        | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 94        | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 92        | 2.85%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 80        | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 72        | 2.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 69        | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 2.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 62        | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 57        | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 54        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 51        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 47        | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 46        | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 41        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 40        | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 40        | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 38        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 38        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 37        | 1.14%   |
| AMD High Definition Audio Controller                                                              | 33        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 31        | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 18        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.53%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 17        | 0.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 176       | 28.39%  |
| SK hynix               | 135       | 21.77%  |
| Micron Technology      | 82        | 13.23%  |
| Kingston               | 44        | 7.1%    |
| Unknown                | 37        | 5.97%   |
| Crucial                | 24        | 3.87%   |
| Unknown (ABCD)         | 22        | 3.55%   |
| A-DATA Technology      | 13        | 2.1%    |
| Elpida                 | 12        | 1.94%   |
| Ramaxel Technology     | 9         | 1.45%   |
| Smart                  | 7         | 1.13%   |
| Nanya Technology       | 5         | 0.81%   |
| Patriot                | 4         | 0.65%   |
| Unknown                | 4         | 0.65%   |
| Transcend              | 3         | 0.48%   |
| Timetec                | 3         | 0.48%   |
| Team                   | 3         | 0.48%   |
| G.Skill                | 3         | 0.48%   |
| Corsair                | 3         | 0.48%   |
| Teikon                 | 2         | 0.32%   |
| ff                     | 2         | 0.32%   |
| fef5                   | 2         | 0.32%   |
| 4ea5                   | 2         | 0.32%   |
| Unknown (08B5)         | 1         | 0.16%   |
| Unknown (07F7)         | 1         | 0.16%   |
| Unknown (000080B30080) | 1         | 0.16%   |
| Strontium              | 1         | 0.16%   |
| Smart Brazil           | 1         | 0.16%   |
| Silicon Power          | 1         | 0.16%   |
| SHARETRONIC            | 1         | 0.16%   |
| Qimonda                | 1         | 0.16%   |
| PUSKILL                | 1         | 0.16%   |
| ProMos/Mosel Vitelic   | 1         | 0.16%   |
| pqi                    | 1         | 0.16%   |
| PNY                    | 1         | 0.16%   |
| Netlist                | 1         | 0.16%   |
| Kllisre                | 1         | 0.16%   |
| Kingmax                | 1         | 0.16%   |
| GSkill                 | 1         | 0.16%   |
| Essencore              | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 2.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.23%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 7         | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 1.08%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 6         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.92%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.92%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 5         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.62%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s             | 4         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.62%   |
| Unknown                                                          | 4         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.46%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.46%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                     | 3         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 3         | 0.46%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 221       | 42.58%  |
| DDR3    | 187       | 36.03%  |
| LPDDR4  | 42        | 8.09%   |
| DDR2    | 23        | 4.43%   |
| LPDDR3  | 20        | 3.85%   |
| SDRAM   | 11        | 2.12%   |
| LPDDR5  | 5         | 0.96%   |
| Unknown | 5         | 0.96%   |
| DDR5    | 4         | 0.77%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 438       | 83.91%  |
| Row Of Chips | 58        | 11.11%  |
| DIMM         | 9         | 1.72%   |
| Chip         | 9         | 1.72%   |
| Unknown      | 8         | 1.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 219       | 37.95%  |
| 4096  | 179       | 31.02%  |
| 2048  | 83        | 14.38%  |
| 16384 | 62        | 10.75%  |
| 1024  | 20        | 3.47%   |
| 32768 | 13        | 2.25%   |
| 512   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 129       | 22.87%  |
| 3200    | 107       | 18.97%  |
| 2667    | 89        | 15.78%  |
| 2400    | 61        | 10.82%  |
| 1334    | 24        | 4.26%   |
| 2133    | 22        | 3.9%    |
| 1333    | 20        | 3.55%   |
| 667     | 12        | 2.13%   |
| 4267    | 11        | 1.95%   |
| Unknown | 10        | 1.77%   |
| 8400    | 9         | 1.6%    |
| 1066    | 9         | 1.6%    |
| 800     | 9         | 1.6%    |
| 3266    | 8         | 1.42%   |
| 2048    | 8         | 1.42%   |
| 1867    | 8         | 1.42%   |
| 6400    | 5         | 0.89%   |
| 4800    | 4         | 0.71%   |
| 1067    | 4         | 0.71%   |
| 975     | 4         | 0.71%   |
| 4199    | 3         | 0.53%   |
| 2933    | 2         | 0.35%   |
| 7467    | 1         | 0.18%   |
| 5600    | 1         | 0.18%   |
| 4266    | 1         | 0.18%   |
| 3733    | 1         | 0.18%   |
| 1866    | 1         | 0.18%   |
| 533     | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 44.44%  |
| Seiko Epson           | 4         | 22.22%  |
| Canon                 | 2         | 11.11%  |
| Zebra                 | 1         | 5.56%   |
| Samsung Electronics   | 1         | 5.56%   |
| Lexmark International | 1         | 5.56%   |
| Brother Industries    | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP ENVY Photo 6200 series         | 2         | 11.11%  |
| Zebra ZP 450 Printer              | 1         | 5.56%   |
| Seiko Epson XP-235 Series         | 1         | 5.56%   |
| Seiko Epson L3110 Series          | 1         | 5.56%   |
| Seiko Epson ET-2810 Series        | 1         | 5.56%   |
| Seiko Epson AcuLaser C1700        | 1         | 5.56%   |
| Samsung M2020 Series              | 1         | 5.56%   |
| Lexmark International 2400 series | 1         | 5.56%   |
| HP LaserJet P1102                 | 1         | 5.56%   |
| HP LaserJet 1200                  | 1         | 5.56%   |
| HP LaserJet 1000                  | 1         | 5.56%   |
| HP DeskJet 2300 series            | 1         | 5.56%   |
| HP Deskjet 1510                   | 1         | 5.56%   |
| HP DeskJet 1110 series            | 1         | 5.56%   |
| Canon TS3100 series               | 1         | 5.56%   |
| Canon PIXMA MG3000 series         | 1         | 5.56%   |
| Brother MFC-J5730DW               | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 62.5%   |
| Seiko Epson | 3         | 37.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 37.5%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 12.5%   |
| Canon CanoScan LiDE 90                      | 1         | 12.5%   |
| Canon CanoScan LiDE 700F                    | 1         | 12.5%   |
| Canon CanoScan LIDE 25                      | 1         | 12.5%   |
| Canon CanoScan LiDE 110                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 465       | 23.37%  |
| Microdia                               | 185       | 9.3%    |
| Realtek Semiconductor                  | 178       | 8.94%   |
| IMC Networks                           | 166       | 8.34%   |
| Bison Electronics                      | 135       | 6.78%   |
| Sunplus Innovation Technology          | 121       | 6.08%   |
| Quanta                                 | 99        | 4.97%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 4.87%   |
| Suyin                                  | 79        | 3.97%   |
| Syntek                                 | 58        | 2.91%   |
| Apple                                  | 57        | 2.86%   |
| Lite-On Technology                     | 44        | 2.21%   |
| Alcor Micro                            | 37        | 1.86%   |
| Silicon Motion                         | 36        | 1.81%   |
| Luxvisions Innotech Limited            | 28        | 1.41%   |
| Ricoh                                  | 22        | 1.11%   |
| Sonix Technology                       | 17        | 0.85%   |
| Logitech                               | 16        | 0.8%    |
| icSpring                               | 14        | 0.7%    |
| Primax Electronics                     | 12        | 0.6%    |
| Acer                                   | 12        | 0.6%    |
| Lenovo                                 | 10        | 0.5%    |
| SunplusIT                              | 9         | 0.45%   |
| Samsung Electronics                    | 9         | 0.45%   |
| ALi                                    | 8         | 0.4%    |
| Importek                               | 7         | 0.35%   |
| Z-Star Microelectronics                | 6         | 0.3%    |
| Y Media                                | 5         | 0.25%   |
| OmniVision Technologies                | 5         | 0.25%   |
| GEMBIRD                                | 5         | 0.25%   |
| Microsoft                              | 4         | 0.2%    |
| Sunplus Technology                     | 3         | 0.15%   |
| Intel                                  | 3         | 0.15%   |
| Genesys Logic                          | 3         | 0.15%   |
| Generalplus Technology                 | 3         | 0.15%   |
| ARC International                      | 3         | 0.15%   |
| Unknown                                | 3         | 0.15%   |
| Tripath Technology                     | 2         | 0.1%    |
| KYE Systems (Mouse Systems)            | 2         | 0.1%    |
| YGTek                                  | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 79        | 3.96%   |
| Microdia Integrated_Webcam_HD                       | 48        | 2.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 42        | 2.1%    |
| Chicony HD WebCam                                   | 41        | 2.05%   |
| Syntek Integrated Camera                            | 35        | 1.75%   |
| Bison Integrated Camera                             | 34        | 1.7%    |
| Realtek Integrated_Webcam_HD                        | 33        | 1.65%   |
| IMC Networks Integrated Camera                      | 32        | 1.6%    |
| Chicony HP Truevision HD                            | 28        | 1.4%    |
| Sunplus Integrated_Webcam_HD                        | 26        | 1.3%    |
| Microdia Integrated Webcam                          | 26        | 1.3%    |
| Chicony TOSHIBA Web Camera - HD                     | 26        | 1.3%    |
| Bison Lenovo EasyCamera                             | 26        | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 22        | 1.1%    |
| Realtek USB Camera                                  | 19        | 0.95%   |
| Alcor Micro USB 2.0 Camera                          | 19        | 0.95%   |
| Lite-On HP HD Camera                                | 18        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 18        | 0.9%    |
| Sunplus HD WebCam                                   | 16        | 0.8%    |
| Quanta HD User Facing                               | 16        | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.8%    |
| Apple Built-in iSight                               | 16        | 0.8%    |
| Realtek Integrated Webcam                           | 15        | 0.75%   |
| Realtek HP Truevision HD                            | 15        | 0.75%   |
| Chicony Lenovo EasyCamera                           | 15        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 15        | 0.75%   |
| Apple FaceTime HD Camera                            | 15        | 0.75%   |
| icSpring camera                                     | 14        | 0.7%    |
| Chicony VGA WebCam                                  | 14        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.7%    |
| Chicony HP Truevision HD camera                     | 14        | 0.7%    |
| Realtek Integrated Webcam HD                        | 13        | 0.65%   |
| Quanta HP Wide Vision HD Camera                     | 13        | 0.65%   |
| Quanta HD Webcam                                    | 13        | 0.65%   |
| Chicony HP HD Camera                                | 13        | 0.65%   |
| Chicony EasyCamera                                  | 13        | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                          | 12        | 0.6%    |
| Chicony HP HD Webcam                                | 12        | 0.6%    |
| Chicony CNF9055 Toshiba Webcam                      | 12        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 12        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 154       | 45.16%  |
| Synaptics                          | 44        | 12.9%   |
| Shenzhen Goodix Technology         | 39        | 11.44%  |
| AuthenTec                          | 38        | 11.14%  |
| Upek                               | 28        | 8.21%   |
| Elan Microelectronics              | 16        | 4.69%   |
| LighTuning Technology              | 9         | 2.64%   |
| STMicroelectronics                 | 7         | 2.05%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.88%   |
| Samsung Electronics                | 2         | 0.59%   |
| Focal-systems.Corp                 | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 9.38%   |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 8.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 7.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 4.99%   |
| Validity Sensors VFS491                                                    | 16        | 4.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.4%    |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.52%   |
| AuthenTec AES2810                                                          | 12        | 3.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 3.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 3.23%   |
| Elan ELAN:ARM-M4                                                           | 11        | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 2.64%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.35%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.47%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.47%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.47%   |
| AuthenTec AES1600                                                          | 5         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.88%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.59%   |
| Synaptics WBDI                                                             | 2         | 0.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.59%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 88        | 57.14%  |
| Alcor Micro                       | 26        | 16.88%  |
| O2 Micro                          | 16        | 10.39%  |
| Upek                              | 7         | 4.55%   |
| Lenovo                            | 7         | 4.55%   |
| Yubico.com                        | 2         | 1.3%    |
| VASCO Data Security International | 2         | 1.3%    |
| SCM Microsystems                  | 2         | 1.3%    |
| Realtek Semiconductor             | 1         | 0.65%   |
| OmniKey                           | 1         | 0.65%   |
| Gemalto (was Gemplus)             | 1         | 0.65%   |
| Fujitsu Siemens Computers         | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 21.43%  |
| Broadcom 5880                                                                | 26        | 16.88%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 16.88%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 9.74%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.55%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.55%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 4         | 2.6%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.3%    |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.3%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.3%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.65%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.65%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.65%   |
| Broadcom 58200                                                               | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1518      | 64.71%  |
| 1     | 635       | 27.07%  |
| 2     | 168       | 7.16%   |
| 3     | 22        | 0.94%   |
| 4     | 3         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 334       | 32.97%  |
| Graphics card            | 194       | 19.15%  |
| Chipcard                 | 146       | 14.41%  |
| Net/wireless             | 118       | 11.65%  |
| Multimedia controller    | 111       | 10.96%  |
| Storage                  | 30        | 2.96%   |
| Bluetooth                | 24        | 2.37%   |
| Sound                    | 11        | 1.09%   |
| Communication controller | 10        | 0.99%   |
| Camera                   | 8         | 0.79%   |
| Net/ethernet             | 6         | 0.59%   |
| Card reader              | 5         | 0.49%   |
| Network                  | 3         | 0.3%    |
| Modem                    | 3         | 0.3%    |
| Flash memory             | 3         | 0.3%    |
| Storage/nvme             | 2         | 0.2%    |
| Storage/ide              | 2         | 0.2%    |
| Dvb card                 | 2         | 0.2%    |
| Unclassified device      | 1         | 0.1%    |

