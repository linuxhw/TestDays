Linux in Egypt - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Egypt/Desktop/README.md) and [notebooks](/Location/Egypt/Notebook/README.md).

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

Total: 488

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 0A80h                       | Desktop     | [7e5c6cf61e](https://linux-hardware.org/?probe=7e5c6cf61e) | May 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [4058369652](https://linux-hardware.org/?probe=4058369652) | May 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bd33528d52](https://linux-hardware.org/?probe=bd33528d52) | May 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Dell          | 03NVJ6 A04                  | Desktop     | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Fujitsu       | FMVA06004                   | Notebook    | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [e6ef37e2a0](https://linux-hardware.org/?probe=e6ef37e2a0) | Apr 24, 2022 |
| Dell          | Latitude 3440               | Notebook    | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| HP            | 8053                        | Desktop     | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| HP            | 15                          | Notebook    | [3253e0fc56](https://linux-hardware.org/?probe=3253e0fc56) | Apr 21, 2022 |
| Sony          | SVT1121B2EW                 | Notebook    | [dd43f45353](https://linux-hardware.org/?probe=dd43f45353) | Apr 21, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| HP            | 8265                        | Desktop     | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| Alienware     | 17                          | Notebook    | [b9b420077c](https://linux-hardware.org/?probe=b9b420077c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Dell          | 0WK833                      | Desktop     | [efee7c0ec6](https://linux-hardware.org/?probe=efee7c0ec6) | Apr 02, 2022 |
| Dell          | 0WK833                      | Desktop     | [a8703c7598](https://linux-hardware.org/?probe=a8703c7598) | Apr 02, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f93e8f46c2](https://linux-hardware.org/?probe=f93e8f46c2) | Apr 01, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [2da8f96ad8](https://linux-hardware.org/?probe=2da8f96ad8) | Mar 29, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [55a2911462](https://linux-hardware.org/?probe=55a2911462) | Mar 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Notebook                    | Notebook    | [4cc8a23994](https://linux-hardware.org/?probe=4cc8a23994) | Mar 22, 2022 |
| HP            | Notebook                    | Notebook    | [cb2c910f05](https://linux-hardware.org/?probe=cb2c910f05) | Mar 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| HP            | Pavilion 15                 | Notebook    | [0f3cb22c3d](https://linux-hardware.org/?probe=0f3cb22c3d) | Mar 20, 2022 |
| HP            | G62                         | Notebook    | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| Dell          | 0804P1 A05                  | Server      | [97777b0db4](https://linux-hardware.org/?probe=97777b0db4) | Mar 17, 2022 |
| HP            | ENVY dv6                    | Notebook    | [39ff0aa86d](https://linux-hardware.org/?probe=39ff0aa86d) | Mar 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b3ba67d085](https://linux-hardware.org/?probe=b3ba67d085) | Mar 08, 2022 |
| Intel         | DQ965MT AAD36265-505        | Desktop     | [93758c64fa](https://linux-hardware.org/?probe=93758c64fa) | Mar 07, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| Dell          | 0XG309                      | Desktop     | [535c8e4e2e](https://linux-hardware.org/?probe=535c8e4e2e) | Feb 28, 2022 |
| Dell          | 0XG309                      | Desktop     | [d9f753df89](https://linux-hardware.org/?probe=d9f753df89) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| Dell          | Venue 10 Pro 5056           | Notebook    | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| HP            | 3397                        | Desktop     | [de499e61b9](https://linux-hardware.org/?probe=de499e61b9) | Feb 22, 2022 |
| HP            | ENVY dv6                    | Notebook    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2ddf4948c9](https://linux-hardware.org/?probe=2ddf4948c9) | Feb 19, 2022 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [d799c9b2f2](https://linux-hardware.org/?probe=d799c9b2f2) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5760b6c177](https://linux-hardware.org/?probe=5760b6c177) | Feb 14, 2022 |
| HP            | 3397                        | Desktop     | [06f2eef752](https://linux-hardware.org/?probe=06f2eef752) | Feb 13, 2022 |
| Dell          | G3 3500                     | Notebook    | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| HP            | 1906                        | Desktop     | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | Desktop     | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9129341c42](https://linux-hardware.org/?probe=9129341c42) | Jan 24, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| Sony          | SVF15328CXB                 | Notebook    | [d55d8f394d](https://linux-hardware.org/?probe=d55d8f394d) | Jan 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [4edc707b67](https://linux-hardware.org/?probe=4edc707b67) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [71a9fb4409](https://linux-hardware.org/?probe=71a9fb4409) | Jan 13, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [9087ece92b](https://linux-hardware.org/?probe=9087ece92b) | Jan 13, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Lenovo        | BRASWELL NOK                | Desktop     | [0b12f54345](https://linux-hardware.org/?probe=0b12f54345) | Dec 26, 2021 |
| HP            | 3047h                       | Desktop     | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Dell          | G15 5510                    | Notebook    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Dell          | G15 5510                    | Notebook    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7326d20e8a](https://linux-hardware.org/?probe=7326d20e8a) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [357bfe0849](https://linux-hardware.org/?probe=357bfe0849) | Dec 11, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [f8dc028352](https://linux-hardware.org/?probe=f8dc028352) | Dec 08, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| HP            | 83DD                        | Mini pc     | [9ec6f2e5fe](https://linux-hardware.org/?probe=9ec6f2e5fe) | Nov 16, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [49f973804a](https://linux-hardware.org/?probe=49f973804a) | Nov 13, 2021 |
| Dell          | Latitude 5420               | Notebook    | [973018da2b](https://linux-hardware.org/?probe=973018da2b) | Nov 08, 2021 |
| Dell          | Precision WorkStation 49... | Desktop     | [b40b65db05](https://linux-hardware.org/?probe=b40b65db05) | Nov 07, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [eacb69d71e](https://linux-hardware.org/?probe=eacb69d71e) | Nov 05, 2021 |
| Lenovo        | ThinkPad E14 20RAS0CM00     | Notebook    | [a35aaaeb6d](https://linux-hardware.org/?probe=a35aaaeb6d) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e8781db5ab](https://linux-hardware.org/?probe=e8781db5ab) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e1978d5164](https://linux-hardware.org/?probe=e1978d5164) | Oct 31, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [08d287d2e2](https://linux-hardware.org/?probe=08d287d2e2) | Oct 30, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [ff796824d2](https://linux-hardware.org/?probe=ff796824d2) | Oct 30, 2021 |
| HP            | 1850                        | Desktop     | [b155e888a5](https://linux-hardware.org/?probe=b155e888a5) | Oct 24, 2021 |
| HP            | ProBook 6460b               | Notebook    | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [e66a1ae149](https://linux-hardware.org/?probe=e66a1ae149) | Oct 21, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [7339dc6e79](https://linux-hardware.org/?probe=7339dc6e79) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d69772c626](https://linux-hardware.org/?probe=d69772c626) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0086ED     | Notebook    | [2db7f4be45](https://linux-hardware.org/?probe=2db7f4be45) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e8ae6d00a2](https://linux-hardware.org/?probe=e8ae6d00a2) | Oct 12, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [bc2b8a4fa5](https://linux-hardware.org/?probe=bc2b8a4fa5) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [879496302d](https://linux-hardware.org/?probe=879496302d) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [bbe7dc3f56](https://linux-hardware.org/?probe=bbe7dc3f56) | Oct 11, 2021 |
| HP            | ProBook 645 G1              | Notebook    | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [51d51a675d](https://linux-hardware.org/?probe=51d51a675d) | Oct 10, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6df5eb55f0](https://linux-hardware.org/?probe=6df5eb55f0) | Oct 03, 2021 |
| ASUSTek       | N501JW                      | Notebook    | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| HP            | 1632                        | Desktop     | [269b4ad58e](https://linux-hardware.org/?probe=269b4ad58e) | Aug 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [26cae4bb7a](https://linux-hardware.org/?probe=26cae4bb7a) | Aug 16, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| HP            | Compaq 2510p                | Notebook    | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | Notebook    | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Packard Be... | EasyNote LX                 | Notebook    | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [9bda168dc6](https://linux-hardware.org/?probe=9bda168dc6) | Aug 04, 2021 |
| Dell          | 0DR845                      | Desktop     | [1714388038](https://linux-hardware.org/?probe=1714388038) | Aug 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [4f7539c771](https://linux-hardware.org/?probe=4f7539c771) | Jul 30, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [08fc5f3b99](https://linux-hardware.org/?probe=08fc5f3b99) | Jul 27, 2021 |
| HP            | 3047h                       | Desktop     | [58b480757e](https://linux-hardware.org/?probe=58b480757e) | Jul 18, 2021 |
| HP            | 3047h                       | Desktop     | [40a25f223c](https://linux-hardware.org/?probe=40a25f223c) | Jul 18, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b8b861a13d](https://linux-hardware.org/?probe=b8b861a13d) | Jul 13, 2021 |
| MSI           | MS-7507                     | Desktop     | [ede4b6fc34](https://linux-hardware.org/?probe=ede4b6fc34) | Jul 11, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [428dcd6503](https://linux-hardware.org/?probe=428dcd6503) | Jul 07, 2021 |
| Dell          | G3 3579                     | Notebook    | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| HP            | 0A54h                       | Desktop     | [c8d8757784](https://linux-hardware.org/?probe=c8d8757784) | Jul 02, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [8c7ef2bc15](https://linux-hardware.org/?probe=8c7ef2bc15) | Jun 20, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [4c397b8b70](https://linux-hardware.org/?probe=4c397b8b70) | Jun 20, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [c432c046f1](https://linux-hardware.org/?probe=c432c046f1) | Jun 04, 2021 |
| HP            | 158B                        | Desktop     | [cc2472f216](https://linux-hardware.org/?probe=cc2472f216) | Jun 03, 2021 |
| HP            | 83E1                        | Desktop     | [a10433a3cb](https://linux-hardware.org/?probe=a10433a3cb) | Jun 03, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [ace51e66cb](https://linux-hardware.org/?probe=ace51e66cb) | May 31, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | ProBook 645 G1              | Notebook    | [a92458c2db](https://linux-hardware.org/?probe=a92458c2db) | May 26, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [6ae217a5a8](https://linux-hardware.org/?probe=6ae217a5a8) | May 21, 2021 |
| Dell          | G5 5587                     | Notebook    | [fae808ae7d](https://linux-hardware.org/?probe=fae808ae7d) | May 02, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [b902c359da](https://linux-hardware.org/?probe=b902c359da) | Apr 30, 2021 |
| Unknown       | Unknown                     | Phone       | [da645fe697](https://linux-hardware.org/?probe=da645fe697) | Apr 25, 2021 |
| Gigabyte      | H55M-S2V                    | Desktop     | [9170ec8194](https://linux-hardware.org/?probe=9170ec8194) | Apr 20, 2021 |
| HP            | Notebook                    | Notebook    | [872a5f9112](https://linux-hardware.org/?probe=872a5f9112) | Apr 18, 2021 |
| HP            | 3397                        | Desktop     | [bb31fb43b4](https://linux-hardware.org/?probe=bb31fb43b4) | Apr 17, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [b7fe68e060](https://linux-hardware.org/?probe=b7fe68e060) | Apr 17, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [101c47c9a2](https://linux-hardware.org/?probe=101c47c9a2) | Apr 17, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [3200f41cf0](https://linux-hardware.org/?probe=3200f41cf0) | Apr 13, 2021 |
| HP            | 3397                        | Desktop     | [aa5cc70dda](https://linux-hardware.org/?probe=aa5cc70dda) | Apr 12, 2021 |
| HP            | 15                          | Notebook    | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [820db16b30](https://linux-hardware.org/?probe=820db16b30) | Apr 08, 2021 |
| Dell          | Inspiron 3580               | Notebook    | [fcb5ccbc6c](https://linux-hardware.org/?probe=fcb5ccbc6c) | Apr 08, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [a3ecba2a79](https://linux-hardware.org/?probe=a3ecba2a79) | Apr 06, 2021 |
| Dell          | 0F5C5X A00                  | Desktop     | [7eda600c97](https://linux-hardware.org/?probe=7eda600c97) | Apr 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [bb1ef328b0](https://linux-hardware.org/?probe=bb1ef328b0) | Mar 30, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [10aaa9110b](https://linux-hardware.org/?probe=10aaa9110b) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | Desktop     | [280d47279c](https://linux-hardware.org/?probe=280d47279c) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | Desktop     | [a33947d95c](https://linux-hardware.org/?probe=a33947d95c) | Mar 23, 2021 |
| HP            | 2215                        | Desktop     | [baefda0ada](https://linux-hardware.org/?probe=baefda0ada) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ecb76b364b](https://linux-hardware.org/?probe=ecb76b364b) | Mar 20, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [d48c515893](https://linux-hardware.org/?probe=d48c515893) | Mar 20, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [ca4e78877a](https://linux-hardware.org/?probe=ca4e78877a) | Mar 12, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [9dbe8f6250](https://linux-hardware.org/?probe=9dbe8f6250) | Mar 12, 2021 |
| TECNO         | WinPad 10A                  | Notebook    | [e96bf0a4fa](https://linux-hardware.org/?probe=e96bf0a4fa) | Mar 08, 2021 |
| Lenovo        | AILZx                       | Notebook    | [b0c93e5b27](https://linux-hardware.org/?probe=b0c93e5b27) | Mar 07, 2021 |
| Lenovo        | AILZx                       | Notebook    | [d06410a1dd](https://linux-hardware.org/?probe=d06410a1dd) | Mar 04, 2021 |
| Lenovo        | AILZx                       | Notebook    | [cf1bc93ffd](https://linux-hardware.org/?probe=cf1bc93ffd) | Mar 04, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba97fc0d2](https://linux-hardware.org/?probe=5ba97fc0d2) | Mar 03, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [586d9baf41](https://linux-hardware.org/?probe=586d9baf41) | Feb 25, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [f22c5da52d](https://linux-hardware.org/?probe=f22c5da52d) | Feb 25, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [8f9a642417](https://linux-hardware.org/?probe=8f9a642417) | Feb 22, 2021 |
| HP            | 3397                        | Desktop     | [d20792e0ea](https://linux-hardware.org/?probe=d20792e0ea) | Feb 17, 2021 |
| Dell          | Latitude XT3                | Notebook    | [2335b761fb](https://linux-hardware.org/?probe=2335b761fb) | Feb 16, 2021 |
| Gigabyte      | H61M-S2P                    | Desktop     | [93bf0c5ca7](https://linux-hardware.org/?probe=93bf0c5ca7) | Feb 16, 2021 |
| HP            | 250 G3                      | Notebook    | [67cb272c8e](https://linux-hardware.org/?probe=67cb272c8e) | Feb 14, 2021 |
| Dell          | Latitude XT3                | Notebook    | [94f5a1f396](https://linux-hardware.org/?probe=94f5a1f396) | Feb 13, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [6472781079](https://linux-hardware.org/?probe=6472781079) | Feb 09, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [80ffaa3d5b](https://linux-hardware.org/?probe=80ffaa3d5b) | Feb 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ab3be4f904](https://linux-hardware.org/?probe=ab3be4f904) | Feb 07, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [ed032a4225](https://linux-hardware.org/?probe=ed032a4225) | Feb 07, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [fdfa43b360](https://linux-hardware.org/?probe=fdfa43b360) | Feb 01, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [7e3a962336](https://linux-hardware.org/?probe=7e3a962336) | Jan 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9072c5e554](https://linux-hardware.org/?probe=9072c5e554) | Jan 29, 2021 |
| HP            | Pavilion dv6                | Notebook    | [55752483ef](https://linux-hardware.org/?probe=55752483ef) | Jan 25, 2021 |
| Lenovo        | ThinkPad T580 20LAS09100    | Notebook    | [92d071729f](https://linux-hardware.org/?probe=92d071729f) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [e596928019](https://linux-hardware.org/?probe=e596928019) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8b2119a584](https://linux-hardware.org/?probe=8b2119a584) | Jan 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [835511d4d7](https://linux-hardware.org/?probe=835511d4d7) | Jan 21, 2021 |
| Dell          | G3 3590                     | Notebook    | [27fb9a0695](https://linux-hardware.org/?probe=27fb9a0695) | Jan 12, 2021 |
| HP            | 18E7                        | Desktop     | [627983aa9a](https://linux-hardware.org/?probe=627983aa9a) | Jan 08, 2021 |
| HP            | 18E7                        | Desktop     | [84402293e1](https://linux-hardware.org/?probe=84402293e1) | Jan 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dbf279a62e](https://linux-hardware.org/?probe=dbf279a62e) | Jan 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [f14ce7c7c0](https://linux-hardware.org/?probe=f14ce7c7c0) | Jan 07, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [a8f7f002a3](https://linux-hardware.org/?probe=a8f7f002a3) | Jan 06, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [09ee69f73b](https://linux-hardware.org/?probe=09ee69f73b) | Jan 05, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| Acer          | Veriton ES2735G V:2.0       | Desktop     | [c7f3ccb243](https://linux-hardware.org/?probe=c7f3ccb243) | Jan 03, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d18c93f636](https://linux-hardware.org/?probe=d18c93f636) | Dec 31, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0a288440a6](https://linux-hardware.org/?probe=0a288440a6) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [1262d56db8](https://linux-hardware.org/?probe=1262d56db8) | Dec 30, 2020 |
| Dell          | Latitude E6400              | Notebook    | [9f5ac2d658](https://linux-hardware.org/?probe=9f5ac2d658) | Dec 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7b24857e8f](https://linux-hardware.org/?probe=7b24857e8f) | Dec 28, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [91e7e7c14e](https://linux-hardware.org/?probe=91e7e7c14e) | Dec 27, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [3f73a22244](https://linux-hardware.org/?probe=3f73a22244) | Dec 27, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [054d224782](https://linux-hardware.org/?probe=054d224782) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Apple         | MacBookPro5,3               | Notebook    | [29542ce3fc](https://linux-hardware.org/?probe=29542ce3fc) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RD001HAD     | Notebook    | [4f6e684aa1](https://linux-hardware.org/?probe=4f6e684aa1) | Dec 22, 2020 |
| HP            | Pavilion g6                 | Notebook    | [172d4abbd7](https://linux-hardware.org/?probe=172d4abbd7) | Dec 19, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [9d4e1e6361](https://linux-hardware.org/?probe=9d4e1e6361) | Dec 17, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ed8e771bf5](https://linux-hardware.org/?probe=ed8e771bf5) | Dec 15, 2020 |
| HP            | ProBook 4540s               | Notebook    | [a35b479f53](https://linux-hardware.org/?probe=a35b479f53) | Dec 09, 2020 |
| HP            | ZBook 15                    | Notebook    | [f7f246578a](https://linux-hardware.org/?probe=f7f246578a) | Dec 07, 2020 |
| ASUSTek       | X455LD                      | Notebook    | [9e5d7995ce](https://linux-hardware.org/?probe=9e5d7995ce) | Dec 03, 2020 |
| Lenovo        | ThinkPad T580 20LAS09100    | Notebook    | [d5a8abcbc5](https://linux-hardware.org/?probe=d5a8abcbc5) | Dec 01, 2020 |
| Dell          | Inspiron 7786               | Convertible | [d4082453c1](https://linux-hardware.org/?probe=d4082453c1) | Nov 24, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c9204a3c7d](https://linux-hardware.org/?probe=c9204a3c7d) | Nov 22, 2020 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [db7eb29112](https://linux-hardware.org/?probe=db7eb29112) | Nov 22, 2020 |
| I-Life Dig... | ZED AIR 2                   | Notebook    | [74f5e7c221](https://linux-hardware.org/?probe=74f5e7c221) | Nov 20, 2020 |
| I-Life Dig... | ZED AIR 2                   | Notebook    | [04802ac1cb](https://linux-hardware.org/?probe=04802ac1cb) | Nov 20, 2020 |
| HP            | ZBook 15                    | Notebook    | [9adafc3a81](https://linux-hardware.org/?probe=9adafc3a81) | Nov 19, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [c09f7df61e](https://linux-hardware.org/?probe=c09f7df61e) | Nov 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [630b92e4d0](https://linux-hardware.org/?probe=630b92e4d0) | Nov 18, 2020 |
| Dell          | 0WWJRX A00                  | Desktop     | [79bddf0f48](https://linux-hardware.org/?probe=79bddf0f48) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [907aebb56a](https://linux-hardware.org/?probe=907aebb56a) | Nov 16, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [ec87278338](https://linux-hardware.org/?probe=ec87278338) | Nov 14, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [0b7205d523](https://linux-hardware.org/?probe=0b7205d523) | Nov 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [cee12c5d76](https://linux-hardware.org/?probe=cee12c5d76) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b5aff9926a](https://linux-hardware.org/?probe=b5aff9926a) | Nov 09, 2020 |
| HP            | Pavilion g6                 | Notebook    | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Dell          | Latitude 3590               | Notebook    | [6a285d94b7](https://linux-hardware.org/?probe=6a285d94b7) | Nov 02, 2020 |
| Dell          | Latitude E5570              | Notebook    | [ba5361df9e](https://linux-hardware.org/?probe=ba5361df9e) | Oct 29, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [59b28e7f27](https://linux-hardware.org/?probe=59b28e7f27) | Oct 29, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [812301310e](https://linux-hardware.org/?probe=812301310e) | Oct 29, 2020 |
| Dell          | G5 5587                     | Notebook    | [14789ef506](https://linux-hardware.org/?probe=14789ef506) | Oct 27, 2020 |
| Dell          | G5 5587                     | Notebook    | [414f6ca570](https://linux-hardware.org/?probe=414f6ca570) | Oct 27, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [3810f22dfc](https://linux-hardware.org/?probe=3810f22dfc) | Oct 23, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [183944533e](https://linux-hardware.org/?probe=183944533e) | Oct 19, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [b7c7ae8b8b](https://linux-hardware.org/?probe=b7c7ae8b8b) | Oct 17, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e58300f1c](https://linux-hardware.org/?probe=8e58300f1c) | Oct 17, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [e6c4e6ff27](https://linux-hardware.org/?probe=e6c4e6ff27) | Oct 15, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| HP            | 304Ah                       | Desktop     | [a304d64545](https://linux-hardware.org/?probe=a304d64545) | Oct 14, 2020 |
| HP            | 304Ah                       | Desktop     | [539e24cc37](https://linux-hardware.org/?probe=539e24cc37) | Oct 13, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [1722d6f45f](https://linux-hardware.org/?probe=1722d6f45f) | Oct 13, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [9a361154cb](https://linux-hardware.org/?probe=9a361154cb) | Oct 11, 2020 |
| ASUSTek       | P6T                         | Desktop     | [3dd96c341e](https://linux-hardware.org/?probe=3dd96c341e) | Oct 08, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [8d775d0fba](https://linux-hardware.org/?probe=8d775d0fba) | Oct 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [0f22425e10](https://linux-hardware.org/?probe=0f22425e10) | Oct 07, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [68e8da08fa](https://linux-hardware.org/?probe=68e8da08fa) | Oct 06, 2020 |
| HP            | 304Ah                       | Desktop     | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [6a95a69346](https://linux-hardware.org/?probe=6a95a69346) | Oct 04, 2020 |
| HP            | 304Ah                       | Desktop     | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [fc81852ffb](https://linux-hardware.org/?probe=fc81852ffb) | Oct 04, 2020 |
| ASUSTek       | G53SW                       | Notebook    | [cb9eb22047](https://linux-hardware.org/?probe=cb9eb22047) | Oct 02, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [cfddb029a9](https://linux-hardware.org/?probe=cfddb029a9) | Oct 01, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [6e17f92f25](https://linux-hardware.org/?probe=6e17f92f25) | Sep 30, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [839f278908](https://linux-hardware.org/?probe=839f278908) | Sep 30, 2020 |
| Gigabyte      | P61-DS3-B3                  | Desktop     | [3e2d37b04f](https://linux-hardware.org/?probe=3e2d37b04f) | Sep 30, 2020 |
| Gigabyte      | P61-DS3-B3                  | Desktop     | [a8eb27996e](https://linux-hardware.org/?probe=a8eb27996e) | Sep 30, 2020 |
| HP            | 304Ah                       | Desktop     | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| HP            | 2215                        | Desktop     | [4251c60f57](https://linux-hardware.org/?probe=4251c60f57) | Sep 28, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e22e757c8c](https://linux-hardware.org/?probe=e22e757c8c) | Sep 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [105d229822](https://linux-hardware.org/?probe=105d229822) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [4d46200fc3](https://linux-hardware.org/?probe=4d46200fc3) | Sep 17, 2020 |
| ASUSTek       | X580VN                      | Notebook    | [cdd3998e5d](https://linux-hardware.org/?probe=cdd3998e5d) | Sep 12, 2020 |
| ASUSTek       | X580VN                      | Notebook    | [02de9a38ac](https://linux-hardware.org/?probe=02de9a38ac) | Sep 12, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [0a888dfc64](https://linux-hardware.org/?probe=0a888dfc64) | Sep 12, 2020 |
| Dell          | 0C27VV A00                  | Desktop     | [63ac37dbe0](https://linux-hardware.org/?probe=63ac37dbe0) | Sep 09, 2020 |
| HP            | 1850                        | Desktop     | [b4067f01b9](https://linux-hardware.org/?probe=b4067f01b9) | Aug 28, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [29083832b1](https://linux-hardware.org/?probe=29083832b1) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| HP            | 0AA8h                       | Desktop     | [1d5b0d8069](https://linux-hardware.org/?probe=1d5b0d8069) | Aug 18, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2c424580ec](https://linux-hardware.org/?probe=2c424580ec) | Aug 15, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8b2bb78e5e](https://linux-hardware.org/?probe=8b2bb78e5e) | Aug 15, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [82f88ee681](https://linux-hardware.org/?probe=82f88ee681) | Aug 09, 2020 |
| Dell          | G5 5587                     | Notebook    | [ff9bde0012](https://linux-hardware.org/?probe=ff9bde0012) | Aug 06, 2020 |
| Gigabyte      | H55M-S2V                    | Desktop     | [07f217e703](https://linux-hardware.org/?probe=07f217e703) | Aug 03, 2020 |
| Gigabyte      | H55M-S2V                    | Desktop     | [ed1664a437](https://linux-hardware.org/?probe=ed1664a437) | Aug 03, 2020 |
| Dell          | G5 5587                     | Notebook    | [0f1718b1a5](https://linux-hardware.org/?probe=0f1718b1a5) | Aug 03, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [0107343e87](https://linux-hardware.org/?probe=0107343e87) | Aug 02, 2020 |
| Dell          | Latitude 7400               | Notebook    | [bb45d9a55f](https://linux-hardware.org/?probe=bb45d9a55f) | Jul 31, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [3ed23397a7](https://linux-hardware.org/?probe=3ed23397a7) | Jul 30, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [5bd1b54d12](https://linux-hardware.org/?probe=5bd1b54d12) | Jul 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [51ed8b0103](https://linux-hardware.org/?probe=51ed8b0103) | Jul 28, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | Notebook    | [f599cd92cd](https://linux-hardware.org/?probe=f599cd92cd) | Jul 27, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [81dd1b462b](https://linux-hardware.org/?probe=81dd1b462b) | Jul 26, 2020 |
| Lenovo        | ThinkPad E580 20KS0008AD    | Notebook    | [5e0f6c1dce](https://linux-hardware.org/?probe=5e0f6c1dce) | Jul 26, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | Notebook    | [f24dee8f72](https://linux-hardware.org/?probe=f24dee8f72) | Jul 24, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [56cf19c251](https://linux-hardware.org/?probe=56cf19c251) | Jul 18, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [3d66bcb580](https://linux-hardware.org/?probe=3d66bcb580) | Jul 15, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | Desktop     | [0aea737b4e](https://linux-hardware.org/?probe=0aea737b4e) | Jul 14, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Lenovo        | G555 0873                   | Notebook    | [6a79c9f57b](https://linux-hardware.org/?probe=6a79c9f57b) | Jun 26, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3b7aa38697](https://linux-hardware.org/?probe=3b7aa38697) | Jun 24, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [bf6cda0ab3](https://linux-hardware.org/?probe=bf6cda0ab3) | Jun 24, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [f9ef75ee84](https://linux-hardware.org/?probe=f9ef75ee84) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [bd3ec8d031](https://linux-hardware.org/?probe=bd3ec8d031) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [bb181efab0](https://linux-hardware.org/?probe=bb181efab0) | Jun 22, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [5cad704188](https://linux-hardware.org/?probe=5cad704188) | Jun 22, 2020 |
| ECS           | G41T-M6                     | Desktop     | [c053fd66c4](https://linux-hardware.org/?probe=c053fd66c4) | Jun 20, 2020 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [c0a0033c02](https://linux-hardware.org/?probe=c0a0033c02) | Jun 19, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [1785e9c758](https://linux-hardware.org/?probe=1785e9c758) | Jun 09, 2020 |
| Lenovo        | ThinkPad E480 20KN0082AD    | Notebook    | [f8743f8e7c](https://linux-hardware.org/?probe=f8743f8e7c) | Jun 03, 2020 |
| Acer          | Aspire 5253                 | Notebook    | [7951613e3c](https://linux-hardware.org/?probe=7951613e3c) | Jun 02, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [7bc753da45](https://linux-hardware.org/?probe=7bc753da45) | Jun 01, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [cad337153c](https://linux-hardware.org/?probe=cad337153c) | May 30, 2020 |
| HP            | G60                         | Notebook    | [36393e3df7](https://linux-hardware.org/?probe=36393e3df7) | May 30, 2020 |
| Dell          | Latitude E5570              | Notebook    | [52fe4fa81d](https://linux-hardware.org/?probe=52fe4fa81d) | May 27, 2020 |
| HP            | 0A64h                       | Desktop     | [2bd2c492f2](https://linux-hardware.org/?probe=2bd2c492f2) | May 19, 2020 |
| Packard Be... | EasyNote TJ75               | Notebook    | [3e4f50b818](https://linux-hardware.org/?probe=3e4f50b818) | May 18, 2020 |
| Lenovo        | G555 0873                   | Notebook    | [80cd03a651](https://linux-hardware.org/?probe=80cd03a651) | May 17, 2020 |
| Lenovo        | G555 0873                   | Notebook    | [0c8aa224f6](https://linux-hardware.org/?probe=0c8aa224f6) | May 17, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [49f0886269](https://linux-hardware.org/?probe=49f0886269) | May 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [261ecd7cd3](https://linux-hardware.org/?probe=261ecd7cd3) | May 15, 2020 |
| HP            | Pavilion g4                 | Notebook    | [d72a853f70](https://linux-hardware.org/?probe=d72a853f70) | May 15, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [567c197788](https://linux-hardware.org/?probe=567c197788) | May 14, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [d2f086da96](https://linux-hardware.org/?probe=d2f086da96) | May 13, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [143dc371cc](https://linux-hardware.org/?probe=143dc371cc) | May 13, 2020 |
| Dell          | G3 3579                     | Notebook    | [1391477c00](https://linux-hardware.org/?probe=1391477c00) | May 11, 2020 |
| Dell          | 0F5C5X A00                  | Desktop     | [7249cfd353](https://linux-hardware.org/?probe=7249cfd353) | May 11, 2020 |
| Dell          | 0M863N A01                  | Desktop     | [9d837a84d6](https://linux-hardware.org/?probe=9d837a84d6) | May 06, 2020 |
| Dell          | G3 3779                     | Notebook    | [8adf43a503](https://linux-hardware.org/?probe=8adf43a503) | May 05, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [bdb886a73d](https://linux-hardware.org/?probe=bdb886a73d) | May 05, 2020 |
| HP            | Pavilion g4                 | Notebook    | [8dec145194](https://linux-hardware.org/?probe=8dec145194) | May 05, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [3cc9bc0ca6](https://linux-hardware.org/?probe=3cc9bc0ca6) | May 02, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [ca61693f79](https://linux-hardware.org/?probe=ca61693f79) | May 02, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [aa0e93d8ea](https://linux-hardware.org/?probe=aa0e93d8ea) | May 01, 2020 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [ec80a4e6c4](https://linux-hardware.org/?probe=ec80a4e6c4) | May 01, 2020 |
| HP            | 0A64h                       | Desktop     | [33c495a402](https://linux-hardware.org/?probe=33c495a402) | Apr 29, 2020 |
| HP            | 0A64h                       | Desktop     | [fa43db5ed0](https://linux-hardware.org/?probe=fa43db5ed0) | Apr 29, 2020 |
| Toshiba       | Satellite L850-A894         | Notebook    | [4cff22692a](https://linux-hardware.org/?probe=4cff22692a) | Apr 26, 2020 |
| Toshiba       | Satellite L850-A894         | Notebook    | [c6bd4ae874](https://linux-hardware.org/?probe=c6bd4ae874) | Apr 26, 2020 |
| Dell          | Inspiron 5583               | Notebook    | [73ad84a03c](https://linux-hardware.org/?probe=73ad84a03c) | Apr 22, 2020 |
| Dell          | G5 5587                     | Notebook    | [56485e9db4](https://linux-hardware.org/?probe=56485e9db4) | Apr 22, 2020 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [518f5df11e](https://linux-hardware.org/?probe=518f5df11e) | Apr 19, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [cb33489db5](https://linux-hardware.org/?probe=cb33489db5) | Apr 18, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [e39b380b81](https://linux-hardware.org/?probe=e39b380b81) | Apr 18, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [165bdbdf8b](https://linux-hardware.org/?probe=165bdbdf8b) | Apr 09, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [a8a037650e](https://linux-hardware.org/?probe=a8a037650e) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | Notebook    | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | Notebook    | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5a16417e7b](https://linux-hardware.org/?probe=5a16417e7b) | Apr 04, 2020 |
| HP            | 3029h                       | Desktop     | [79951d69d3](https://linux-hardware.org/?probe=79951d69d3) | Apr 03, 2020 |
| HP            | 0B54h D                     | Desktop     | [90835f49e4](https://linux-hardware.org/?probe=90835f49e4) | Apr 01, 2020 |
| HP            | 0B54h D                     | Desktop     | [ccfbb22390](https://linux-hardware.org/?probe=ccfbb22390) | Apr 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c6657af4bd](https://linux-hardware.org/?probe=c6657af4bd) | Mar 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2645325565](https://linux-hardware.org/?probe=2645325565) | Mar 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [b90d909930](https://linux-hardware.org/?probe=b90d909930) | Mar 28, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [3aa7a0e126](https://linux-hardware.org/?probe=3aa7a0e126) | Mar 27, 2020 |
| HP            | Pavilion dv7                | Notebook    | [6f801c5209](https://linux-hardware.org/?probe=6f801c5209) | Mar 20, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [f7f247e8c5](https://linux-hardware.org/?probe=f7f247e8c5) | Mar 19, 2020 |
| Lenovo        | ThinkPad SL410 0616A44      | Notebook    | [2c3f83610d](https://linux-hardware.org/?probe=2c3f83610d) | Mar 04, 2020 |
| HP            | 304Ah                       | Desktop     | [6b3da5e7b3](https://linux-hardware.org/?probe=6b3da5e7b3) | Mar 02, 2020 |
| ASUSTek       | P8B75-M                     | Desktop     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [d4389ea7a1](https://linux-hardware.org/?probe=d4389ea7a1) | Feb 23, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [d9e2a26971](https://linux-hardware.org/?probe=d9e2a26971) | Feb 11, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [3b89d35524](https://linux-hardware.org/?probe=3b89d35524) | Feb 11, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [9808803a9a](https://linux-hardware.org/?probe=9808803a9a) | Feb 07, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [bd16699d67](https://linux-hardware.org/?probe=bd16699d67) | Feb 07, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [101d794bd2](https://linux-hardware.org/?probe=101d794bd2) | Jan 30, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [975cffd2a7](https://linux-hardware.org/?probe=975cffd2a7) | Jan 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d08a0ed65d](https://linux-hardware.org/?probe=d08a0ed65d) | Jan 16, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | Desktop     | [ad3e13542c](https://linux-hardware.org/?probe=ad3e13542c) | Jan 15, 2020 |
| Lenovo        | ThinkCentre M55p 8811Y4U    | Desktop     | [9658459b91](https://linux-hardware.org/?probe=9658459b91) | Jan 14, 2020 |
| Lenovo        | ThinkPad E590 20NB0002AD    | Notebook    | [0fc61e3795](https://linux-hardware.org/?probe=0fc61e3795) | Jan 13, 2020 |
| HP            | EliteBook 745 G4            | Notebook    | [99937a33e7](https://linux-hardware.org/?probe=99937a33e7) | Jan 05, 2020 |
| IBM           | 81713FG                     | Desktop     | [53dead81c6](https://linux-hardware.org/?probe=53dead81c6) | Jan 03, 2020 |
| IBM           | 81713FG                     | Desktop     | [d8e454de5c](https://linux-hardware.org/?probe=d8e454de5c) | Jan 03, 2020 |
| ASUSTek       | X540UA                      | Notebook    | [714b86d8a5](https://linux-hardware.org/?probe=714b86d8a5) | Dec 31, 2019 |
| Dell          | Inspiron 5570               | Notebook    | [92a06ce5da](https://linux-hardware.org/?probe=92a06ce5da) | Dec 31, 2019 |
| HP            | Pavilion dv7                | Notebook    | [9091bfdcb2](https://linux-hardware.org/?probe=9091bfdcb2) | Dec 13, 2019 |
| ASUSTek       | T103HAF                     | Tablet      | [5fcf1662db](https://linux-hardware.org/?probe=5fcf1662db) | Dec 08, 2019 |
| Dell          | Inspiron 15-3567            | Notebook    | [ddc251a8e0](https://linux-hardware.org/?probe=ddc251a8e0) | Dec 07, 2019 |
| Dell          | Inspiron 3542               | Notebook    | [38da710325](https://linux-hardware.org/?probe=38da710325) | Dec 01, 2019 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [19294a1943](https://linux-hardware.org/?probe=19294a1943) | Nov 29, 2019 |
| ASUSTek       | H61M-K                      | Desktop     | [60762839f9](https://linux-hardware.org/?probe=60762839f9) | Nov 28, 2019 |
| Dell          | Inspiron 15-3567            | Notebook    | [ba36a0ae04](https://linux-hardware.org/?probe=ba36a0ae04) | Nov 27, 2019 |
| Dell          | Inspiron 15-3567            | Notebook    | [a93aff23bf](https://linux-hardware.org/?probe=a93aff23bf) | Nov 24, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8f75febf6c](https://linux-hardware.org/?probe=8f75febf6c) | Nov 23, 2019 |
| HP            | Pavilion dv7                | Notebook    | [0261873b10](https://linux-hardware.org/?probe=0261873b10) | Nov 22, 2019 |
| ASUSTek       | H61M-K                      | Desktop     | [7ab32a09a5](https://linux-hardware.org/?probe=7ab32a09a5) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [3054eabefb](https://linux-hardware.org/?probe=3054eabefb) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [62081db5d0](https://linux-hardware.org/?probe=62081db5d0) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [6ed324d188](https://linux-hardware.org/?probe=6ed324d188) | Nov 20, 2019 |
| HP            | Pavilion dv7                | Notebook    | [ab5fc8d0ac](https://linux-hardware.org/?probe=ab5fc8d0ac) | Nov 15, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [5d228450e9](https://linux-hardware.org/?probe=5d228450e9) | Nov 11, 2019 |
| HP            | Pavilion dv7                | Notebook    | [41305d675a](https://linux-hardware.org/?probe=41305d675a) | Nov 09, 2019 |
| HP            | Pavilion dv7                | Notebook    | [6031485dd2](https://linux-hardware.org/?probe=6031485dd2) | Nov 08, 2019 |
| Lenovo        | ThinkPad T420 4178CXG       | Notebook    | [70105ff0ab](https://linux-hardware.org/?probe=70105ff0ab) | Nov 03, 2019 |
| Lenovo        | ThinkPad L460 20FVS0ER00    | Notebook    | [713a72e731](https://linux-hardware.org/?probe=713a72e731) | Oct 31, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [e11bd3882e](https://linux-hardware.org/?probe=e11bd3882e) | Oct 22, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [677874b570](https://linux-hardware.org/?probe=677874b570) | Oct 18, 2019 |
| Dell          | 0G214D A00                  | Desktop     | [9ed0af6e0a](https://linux-hardware.org/?probe=9ed0af6e0a) | Oct 11, 2019 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [63cd905908](https://linux-hardware.org/?probe=63cd905908) | Oct 10, 2019 |
| HP            | 2820h                       | Desktop     | [11ccf345fc](https://linux-hardware.org/?probe=11ccf345fc) | Oct 06, 2019 |
| Gigabyte      | 8I848P-G                    | Desktop     | [dc8d0265cd](https://linux-hardware.org/?probe=dc8d0265cd) | Sep 29, 2019 |
| Gigabyte      | 8I848P-G                    | Desktop     | [ab92c43036](https://linux-hardware.org/?probe=ab92c43036) | Sep 28, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [d8532c559a](https://linux-hardware.org/?probe=d8532c559a) | Sep 18, 2019 |
| Dell          | 0G214D A00                  | Desktop     | [e8c153f59c](https://linux-hardware.org/?probe=e8c153f59c) | Sep 09, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [fb490db7bf](https://linux-hardware.org/?probe=fb490db7bf) | Sep 09, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [993460ba08](https://linux-hardware.org/?probe=993460ba08) | Sep 09, 2019 |
| MSI           | GL62 7QF                    | Notebook    | [4d0dbc5874](https://linux-hardware.org/?probe=4d0dbc5874) | Aug 30, 2019 |
| MSI           | GL62 7QF                    | Notebook    | [e508053ff2](https://linux-hardware.org/?probe=e508053ff2) | Aug 29, 2019 |
| Dell          | G3 3579                     | Notebook    | [ddcae43a95](https://linux-hardware.org/?probe=ddcae43a95) | Aug 24, 2019 |
| Dell          | Latitude E6440              | Notebook    | [c9fc484b61](https://linux-hardware.org/?probe=c9fc484b61) | Aug 20, 2019 |
| Dell          | Latitude E6440              | Notebook    | [f153be7930](https://linux-hardware.org/?probe=f153be7930) | Aug 20, 2019 |
| Dell          | 0G214D A00                  | Desktop     | [16230f6527](https://linux-hardware.org/?probe=16230f6527) | Aug 10, 2019 |
| HP            | 0AA8h                       | Desktop     | [590f9d42ea](https://linux-hardware.org/?probe=590f9d42ea) | Aug 09, 2019 |
| HP            | 0AA8h                       | Desktop     | [822e83d86b](https://linux-hardware.org/?probe=822e83d86b) | Aug 09, 2019 |
| Dell          | 0RW199                      | Desktop     | [dfb1809733](https://linux-hardware.org/?probe=dfb1809733) | Aug 05, 2019 |
| HP            | 0AA8h                       | Desktop     | [e4137ad45b](https://linux-hardware.org/?probe=e4137ad45b) | Jul 31, 2019 |
| HP            | 0AA8h                       | Desktop     | [22921b3801](https://linux-hardware.org/?probe=22921b3801) | Jul 31, 2019 |
| HP            | Pavilion dv7                | Notebook    | [d2006e7a87](https://linux-hardware.org/?probe=d2006e7a87) | Jul 27, 2019 |
| Toshiba       | Satellite C850-B341         | Notebook    | [acd80fad4b](https://linux-hardware.org/?probe=acd80fad4b) | Jul 20, 2019 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [0beb4b51ba](https://linux-hardware.org/?probe=0beb4b51ba) | Jul 12, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [ea1580c609](https://linux-hardware.org/?probe=ea1580c609) | Jul 01, 2019 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [8a7237435e](https://linux-hardware.org/?probe=8a7237435e) | Jun 28, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [4cbf20a7cf](https://linux-hardware.org/?probe=4cbf20a7cf) | Jun 18, 2019 |
| Lenovo        | ThinkPad T410 2522N18       | Notebook    | [9ab11256e2](https://linux-hardware.org/?probe=9ab11256e2) | Jun 16, 2019 |
| Acer          | Aspire E5-576G              | Notebook    | [119e4e5705](https://linux-hardware.org/?probe=119e4e5705) | Jun 06, 2019 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [0d944086c2](https://linux-hardware.org/?probe=0d944086c2) | Jun 04, 2019 |
| HP            | Laptop 15-bs1xx             | Notebook    | [47b56cee05](https://linux-hardware.org/?probe=47b56cee05) | May 25, 2019 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [ada1dd6ed6](https://linux-hardware.org/?probe=ada1dd6ed6) | May 25, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [fb72c7a17e](https://linux-hardware.org/?probe=fb72c7a17e) | May 22, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [8cc7613eb4](https://linux-hardware.org/?probe=8cc7613eb4) | May 22, 2019 |
| HP            | 339A                        | Desktop     | [5b75c30305](https://linux-hardware.org/?probe=5b75c30305) | May 07, 2019 |
| HP            | 339A                        | Desktop     | [8d28878fde](https://linux-hardware.org/?probe=8d28878fde) | Apr 24, 2019 |
| Acer          | RS880M05                    | Desktop     | [17c0c75b39](https://linux-hardware.org/?probe=17c0c75b39) | Apr 23, 2019 |
| Dell          | Inspiron 3576               | Notebook    | [e86a5c4340](https://linux-hardware.org/?probe=e86a5c4340) | Apr 12, 2019 |
| HP            | 158A                        | Desktop     | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [7a92794877](https://linux-hardware.org/?probe=7a92794877) | Apr 01, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [ed27c8b4b2](https://linux-hardware.org/?probe=ed27c8b4b2) | Feb 23, 2019 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [db8cfde0fc](https://linux-hardware.org/?probe=db8cfde0fc) | Feb 15, 2019 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [2c4a8b9bfc](https://linux-hardware.org/?probe=2c4a8b9bfc) | Feb 14, 2019 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [4bd60c5d00](https://linux-hardware.org/?probe=4bd60c5d00) | Feb 13, 2019 |
| Dell          | 0W0CHX A00                  | Desktop     | [84777ce1be](https://linux-hardware.org/?probe=84777ce1be) | Feb 05, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d1e0440b23](https://linux-hardware.org/?probe=d1e0440b23) | Jan 30, 2019 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [4ea628d244](https://linux-hardware.org/?probe=4ea628d244) | Nov 27, 2018 |
| Dell          | Inspiron 7520               | Notebook    | [4362c41db3](https://linux-hardware.org/?probe=4362c41db3) | Nov 17, 2018 |
| Dell          | Inspiron 7520               | Notebook    | [461541bb3a](https://linux-hardware.org/?probe=461541bb3a) | Nov 17, 2018 |
| MSI           | MS-7309                     | Desktop     | [dcfb685544](https://linux-hardware.org/?probe=dcfb685544) | Nov 16, 2018 |
| Dell          | Latitude E5470              | Notebook    | [f54e62ab63](https://linux-hardware.org/?probe=f54e62ab63) | Nov 11, 2018 |
| Dell          | Latitude E5470              | Notebook    | [496335b114](https://linux-hardware.org/?probe=496335b114) | Nov 10, 2018 |
| Dell          | Latitude E5470              | Notebook    | [3c869c46e5](https://linux-hardware.org/?probe=3c869c46e5) | Nov 08, 2018 |
| Gigabyte      | P31-DS3L                    | Desktop     | [5e5236f775](https://linux-hardware.org/?probe=5e5236f775) | May 31, 2018 |
| Gigabyte      | P31-DS3L                    | Desktop     | [cb1a0d9cdd](https://linux-hardware.org/?probe=cb1a0d9cdd) | Jan 30, 2018 |
| Gigabyte      | P31-DS3L                    | Desktop     | [a3bd2e39bb](https://linux-hardware.org/?probe=a3bd2e39bb) | Jan 05, 2018 |
| MSI           | MS-7309                     | Desktop     | [bfa74baa2d](https://linux-hardware.org/?probe=bfa74baa2d) | Oct 30, 2017 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [d033ac1daf](https://linux-hardware.org/?probe=d033ac1daf) | Jun 18, 2017 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [89a443e757](https://linux-hardware.org/?probe=89a443e757) | Jun 15, 2017 |
| Toshiba       | Satellite L50-A661          | Notebook    | [fad34d33ee](https://linux-hardware.org/?probe=fad34d33ee) | Apr 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 74        | 21.45%  |
| Ubuntu 18.04        | 45        | 13.04%  |
| Ubuntu 19.10        | 9         | 2.61%   |
| OpenMandriva 4.3    | 9         | 2.61%   |
| OpenMandriva 4.2    | 9         | 2.61%   |
| Ubuntu 20.10        | 8         | 2.32%   |
| Zorin 15            | 7         | 2.03%   |
| Pop!_OS 20.10       | 7         | 2.03%   |
| Ubuntu 21.10        | 6         | 1.74%   |
| Arch                | 6         | 1.74%   |
| Zorin 16            | 5         | 1.45%   |
| Linux Mint 19.3     | 5         | 1.45%   |
| KDE neon 20.04      | 5         | 1.45%   |
| Fedora 35           | 5         | 1.45%   |
| Fedora 34           | 5         | 1.45%   |
| Ubuntu 19.04        | 4         | 1.16%   |
| Pop!_OS 21.04       | 4         | 1.16%   |
| Pop!_OS 20.04       | 4         | 1.16%   |
| Manjaro             | 4         | 1.16%   |
| Linux Mint 20.1     | 4         | 1.16%   |
| Linux Mint 20       | 4         | 1.16%   |
| Kali 2022.1         | 4         | 1.16%   |
| Fedora 32           | 4         | 1.16%   |
| BlackPanther 18.1   | 4         | 1.16%   |
| ArcoLinux Rolling   | 4         | 1.16%   |
| Ubuntu 22.04        | 3         | 0.87%   |
| Ubuntu 21.04        | 3         | 0.87%   |
| Ubuntu 16.04        | 3         | 0.87%   |
| ROSA R9             | 3         | 0.87%   |
| ROSA R10            | 3         | 0.87%   |
| Kubuntu 20.04       | 3         | 0.87%   |
| Kali 2021.1         | 3         | 0.87%   |
| Fedora 33           | 3         | 0.87%   |
| Ubuntu 18.10        | 2         | 0.58%   |
| ROSA R11.1          | 2         | 0.58%   |
| ROSA R11            | 2         | 0.58%   |
| ROSA 12.2           | 2         | 0.58%   |
| RHEL 8              | 2         | 0.58%   |
| Manjaro 21.2.0      | 2         | 0.58%   |
| Manjaro 20.2.1      | 2         | 0.58%   |
| LMDE 4              | 2         | 0.58%   |
| Linux Mint 20.3     | 2         | 0.58%   |
| Linux Mint 20.2     | 2         | 0.58%   |
| Linux Mint 19.2     | 2         | 0.58%   |
| Linux Mint 19       | 2         | 0.58%   |
| Fedora 31           | 2         | 0.58%   |
| Fedora 30           | 2         | 0.58%   |
| Elementary 5.1.2    | 2         | 0.58%   |
| Debian 10           | 2         | 0.58%   |
| Xubuntu 20.04       | 1         | 0.29%   |
| Xubuntu 18.04       | 1         | 0.29%   |
| Xubuntu 16.04       | 1         | 0.29%   |
| Ubuntu Budgie 19.10 | 1         | 0.29%   |
| Reborn OS Rolling   | 1         | 0.29%   |
| Pop!_OS 22.04       | 1         | 0.29%   |
| Parrot 5.0          | 1         | 0.29%   |
| Manjaro 21.2.6      | 1         | 0.29%   |
| Manjaro 21.2.5      | 1         | 0.29%   |
| Manjaro 21.2.1      | 1         | 0.29%   |
| Manjaro 20.1.1      | 1         | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 154       | 46.39%  |
| Linux Mint    | 22        | 6.63%   |
| Fedora        | 20        | 6.02%   |
| OpenMandriva  | 18        | 5.42%   |
| Pop!_OS       | 15        | 4.52%   |
| Manjaro       | 13        | 3.92%   |
| Zorin         | 12        | 3.61%   |
| ROSA          | 10        | 3.01%   |
| Kali          | 9         | 2.71%   |
| Endless       | 8         | 2.41%   |
| Arch          | 7         | 2.11%   |
| KDE neon      | 5         | 1.51%   |
| Elementary    | 5         | 1.51%   |
| ArcoLinux     | 5         | 1.51%   |
| BlackPanther  | 4         | 1.2%    |
| Xubuntu       | 3         | 0.9%    |
| Kubuntu       | 3         | 0.9%    |
| Debian        | 3         | 0.9%    |
| RHEL          | 2         | 0.6%    |
| LMDE          | 2         | 0.6%    |
| Clear Linux   | 2         | 0.6%    |
| Ubuntu Budgie | 1         | 0.3%    |
| Reborn OS     | 1         | 0.3%    |
| Parrot        | 1         | 0.3%    |
| Lubuntu       | 1         | 0.3%    |
| Gentoo        | 1         | 0.3%    |
| EndeavourOS   | 1         | 0.3%    |
| CentOS        | 1         | 0.3%    |
| Android       | 1         | 0.3%    |
| ALT Linux     | 1         | 0.3%    |
| Alpine        | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 17        | 4.62%   |
| 5.10.14-desktop-1omv4002           | 9         | 2.45%   |
| 5.4.0-58-generic                   | 8         | 2.17%   |
| 5.16.7-desktop-1omv4003            | 8         | 2.17%   |
| 5.4.0-48-generic                   | 6         | 1.63%   |
| 5.11.0-37-generic                  | 6         | 1.63%   |
| 5.8.0-7630-generic                 | 5         | 1.36%   |
| 5.3.0-51-generic                   | 5         | 1.36%   |
| 5.13.0-30-generic                  | 5         | 1.36%   |
| 5.8.0-48-generic                   | 4         | 1.09%   |
| 5.4.0-29-generic                   | 4         | 1.09%   |
| 5.11.0-38-generic                  | 4         | 1.09%   |
| 5.0.0-32-generic                   | 4         | 1.09%   |
| 5.9.1-arch1-1                      | 3         | 0.82%   |
| 5.8.0-43-generic                   | 3         | 0.82%   |
| 5.8.0-41-generic                   | 3         | 0.82%   |
| 5.4.0-59-generic                   | 3         | 0.82%   |
| 5.4.0-56-generic                   | 3         | 0.82%   |
| 5.4.0-54-generic                   | 3         | 0.82%   |
| 5.4.0-37-generic                   | 3         | 0.82%   |
| 5.4.0-26-generic                   | 3         | 0.82%   |
| 5.3.0-45-generic                   | 3         | 0.82%   |
| 5.3.0-26-generic                   | 3         | 0.82%   |
| 5.3.0-18-generic                   | 3         | 0.82%   |
| 4.18.16-desktop-1bP                | 3         | 0.82%   |
| 4.15.0-55-generic                  | 3         | 0.82%   |
| 4.15.0-54-generic                  | 3         | 0.82%   |
| 5.4.0-89-generic                   | 2         | 0.54%   |
| 5.4.0-80-generic                   | 2         | 0.54%   |
| 5.4.0-64-generic                   | 2         | 0.54%   |
| 5.4.0-53-generic                   | 2         | 0.54%   |
| 5.4.0-52-generic                   | 2         | 0.54%   |
| 5.4.0-40-generic                   | 2         | 0.54%   |
| 5.4.0-33-generic                   | 2         | 0.54%   |
| 5.4.0-100-generic                  | 2         | 0.54%   |
| 5.3.0-46-generic                   | 2         | 0.54%   |
| 5.3.0-42-generic                   | 2         | 0.54%   |
| 5.3.0-40-generic                   | 2         | 0.54%   |
| 5.3.0-28-generic                   | 2         | 0.54%   |
| 5.3.0-23-generic                   | 2         | 0.54%   |
| 5.15.0-kali3-amd64                 | 2         | 0.54%   |
| 5.15.0-25-generic                  | 2         | 0.54%   |
| 5.13.0-7620-generic                | 2         | 0.54%   |
| 5.13.0-39-generic                  | 2         | 0.54%   |
| 5.13.0-28-generic                  | 2         | 0.54%   |
| 5.11.0-7620-generic                | 2         | 0.54%   |
| 5.11.0-35-generic                  | 2         | 0.54%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.54%   |
| 5.10.19-200.fc33.x86_64            | 2         | 0.54%   |
| 5.10.0-kali7-amd64                 | 2         | 0.54%   |
| 5.10.0-kali3-amd64                 | 2         | 0.54%   |
| 5.0.0-37-generic                   | 2         | 0.54%   |
| 5.0.0-25-generic                   | 2         | 0.54%   |
| 5.0.0-23-generic                   | 2         | 0.54%   |
| 4.18.0-15-generic                  | 2         | 0.54%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 0.54%   |
| 4.15.0-99-generic                  | 2         | 0.54%   |
| 4.15.0-46-generic                  | 2         | 0.54%   |
| 4.15.0-20-generic                  | 2         | 0.54%   |
| 5.9.0-kali5-amd64                  | 1         | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 79        | 22.51%  |
| 5.3.0   | 30        | 8.55%   |
| 5.8.0   | 27        | 7.69%   |
| 4.15.0  | 27        | 7.69%   |
| 5.11.0  | 20        | 5.7%    |
| 5.13.0  | 19        | 5.41%   |
| 5.0.0   | 18        | 5.13%   |
| 4.18.0  | 10        | 2.85%   |
| 5.10.14 | 9         | 2.56%   |
| 5.16.7  | 8         | 2.28%   |
| 5.15.0  | 6         | 1.71%   |
| 5.10.0  | 5         | 1.42%   |
| 4.19.0  | 4         | 1.14%   |
| 5.9.1   | 3         | 0.85%   |
| 5.16.0  | 3         | 0.85%   |
| 4.18.16 | 3         | 0.85%   |
| 5.5.13  | 2         | 0.57%   |
| 5.17.1  | 2         | 0.57%   |
| 5.10.74 | 2         | 0.57%   |
| 5.10.19 | 2         | 0.57%   |
| 4.9.60  | 2         | 0.57%   |
| 4.9.20  | 2         | 0.57%   |
| 5.9.0   | 1         | 0.28%   |
| 5.8.7   | 1         | 0.28%   |
| 5.8.15  | 1         | 0.28%   |
| 5.8.14  | 1         | 0.28%   |
| 5.8.11  | 1         | 0.28%   |
| 5.8.10  | 1         | 0.28%   |
| 5.7.7   | 1         | 0.28%   |
| 5.7.1   | 1         | 0.28%   |
| 5.6.8   | 1         | 0.28%   |
| 5.6.15  | 1         | 0.28%   |
| 5.6.14  | 1         | 0.28%   |
| 5.6.10  | 1         | 0.28%   |
| 5.4.83  | 1         | 0.28%   |
| 5.4.8   | 1         | 0.28%   |
| 5.4.70  | 1         | 0.28%   |
| 5.4.67  | 1         | 0.28%   |
| 5.4.40  | 1         | 0.28%   |
| 5.4.13  | 1         | 0.28%   |
| 5.4.101 | 1         | 0.28%   |
| 5.3.8   | 1         | 0.28%   |
| 5.3.7   | 1         | 0.28%   |
| 5.3.3   | 1         | 0.28%   |
| 5.2.11  | 1         | 0.28%   |
| 5.17.9  | 1         | 0.28%   |
| 5.17.5  | 1         | 0.28%   |
| 5.17.4  | 1         | 0.28%   |
| 5.16.9  | 1         | 0.28%   |
| 5.16.20 | 1         | 0.28%   |
| 5.16.19 | 1         | 0.28%   |
| 5.16.18 | 1         | 0.28%   |
| 5.16.13 | 1         | 0.28%   |
| 5.16.12 | 1         | 0.28%   |
| 5.16.11 | 1         | 0.28%   |
| 5.16.1  | 1         | 0.28%   |
| 5.15.7  | 1         | 0.28%   |
| 5.15.5  | 1         | 0.28%   |
| 5.15.28 | 1         | 0.28%   |
| 5.15.23 | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 86        | 24.93%  |
| 5.3     | 33        | 9.57%   |
| 5.8     | 31        | 8.99%   |
| 4.15    | 27        | 7.83%   |
| 5.10    | 26        | 7.54%   |
| 5.11    | 23        | 6.67%   |
| 5.13    | 21        | 6.09%   |
| 5.16    | 19        | 5.51%   |
| 5.0     | 18        | 5.22%   |
| 4.18    | 13        | 3.77%   |
| 5.15    | 11        | 3.19%   |
| 4.9     | 7         | 2.03%   |
| 5.17    | 5         | 1.45%   |
| 5.9     | 4         | 1.16%   |
| 5.6     | 4         | 1.16%   |
| 4.19    | 4         | 1.16%   |
| 5.12    | 3         | 0.87%   |
| 5.7     | 2         | 0.58%   |
| 5.5     | 2         | 0.58%   |
| 5.14    | 2         | 0.58%   |
| 5.2     | 1         | 0.29%   |
| 4.4     | 1         | 0.29%   |
| 4.16    | 1         | 0.29%   |
| 4.13    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 313       | 96.9%   |
| i686    | 7         | 2.17%   |
| aarch64 | 3         | 0.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 178       | 54.1%   |
| Unknown         | 46        | 13.98%  |
| KDE5            | 40        | 12.16%  |
| XFCE            | 22        | 6.69%   |
| X-Cinnamon      | 15        | 4.56%   |
| KDE4            | 6         | 1.82%   |
| MATE            | 5         | 1.52%   |
| Pantheon        | 3         | 0.91%   |
| Cinnamon        | 3         | 0.91%   |
| Unity           | 2         | 0.61%   |
| KDE             | 2         | 0.61%   |
| qtile           | 1         | 0.3%    |
| LXQt            | 1         | 0.3%    |
| LXDE            | 1         | 0.3%    |
| i3              | 1         | 0.3%    |
| GNOME Flashback | 1         | 0.3%    |
| GNOME Classic   | 1         | 0.3%    |
| Budgie          | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 273       | 82.23%  |
| Unknown | 28        | 8.43%   |
| Wayland | 27        | 8.13%   |
| Tty     | 4         | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 197       | 60.43%  |
| GDM     | 44        | 13.5%   |
| SDDM    | 35        | 10.74%  |
| LightDM | 17        | 5.21%   |
| GDM3    | 15        | 4.6%    |
| TDM     | 12        | 3.68%   |
| KDM     | 6         | 1.84%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 244       | 74.16%  |
| Unknown | 55        | 16.72%  |
| en_GB   | 11        | 3.34%   |
| ar_EG   | 10        | 3.04%   |
| C       | 5         | 1.52%   |
| ru_RU   | 2         | 0.61%   |
| en_ZA   | 1         | 0.3%    |
| de_DE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 196       | 60.49%  |
| EFI  | 128       | 39.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 267       | 81.16%  |
| Overlay | 22        | 6.69%   |
| Unknown | 18        | 5.47%   |
| Btrfs   | 11        | 3.34%   |
| Xfs     | 7         | 2.13%   |
| Zfs     | 2         | 0.61%   |
| Ext3    | 2         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 210       | 64.62%  |
| GPT     | 71        | 21.85%  |
| MBR     | 44        | 13.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 282       | 85.71%  |
| Yes       | 47        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 50.91%  |
| Yes       | 162       | 49.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 97        | 30.12%  |
| Dell                        | 80        | 24.84%  |
| Lenovo                      | 55        | 17.08%  |
| Gigabyte Technology         | 27        | 8.39%   |
| ASUSTek Computer            | 20        | 6.21%   |
| Acer                        | 7         | 2.17%   |
| Toshiba                     | 6         | 1.86%   |
| MSI                         | 6         | 1.86%   |
| Hampoo                      | 3         | 0.93%   |
| Alienware                   | 3         | 0.93%   |
| Sony                        | 2         | 0.62%   |
| Raspberry Pi Foundation     | 2         | 0.62%   |
| Packard Bell                | 2         | 0.62%   |
| Intel                       | 2         | 0.62%   |
| Fujitsu                     | 2         | 0.62%   |
| TECNO                       | 1         | 0.31%   |
| Samsung Electronics         | 1         | 0.31%   |
| IBM                         | 1         | 0.31%   |
| I-Life Digital Technologies | 1         | 0.31%   |
| Fujitsu Siemens             | 1         | 0.31%   |
| ECS                         | 1         | 0.31%   |
| Apple                       | 1         | 0.31%   |
| Unknown                     | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Gigabyte G41MT-S2PT                     | 7         | 2.17%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 5         | 1.55%   |
| Dell Inspiron 5570                      | 5         | 1.55%   |
| HP ProBook 450 G7                       | 4         | 1.24%   |
| Dell Inspiron 7577                      | 4         | 1.24%   |
| Dell G3 3579                            | 4         | 1.24%   |
| HP Pavilion dv6                         | 3         | 0.93%   |
| HP Laptop 15-da1xxx                     | 3         | 0.93%   |
| Dell OptiPlex 780                       | 3         | 0.93%   |
| Dell OptiPlex 760                       | 3         | 0.93%   |
| Dell OptiPlex 7020                      | 3         | 0.93%   |
| Dell G5 5587                            | 3         | 0.93%   |
| Lenovo Y50-70 20378                     | 2         | 0.62%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 2         | 0.62%   |
| Lenovo IdeaPad 310-15IKB 80TV           | 2         | 0.62%   |
| Lenovo G555 0873                        | 2         | 0.62%   |
| HP ZBook 15 G2                          | 2         | 0.62%   |
| HP Z600 Workstation                     | 2         | 0.62%   |
| HP ProBook 645 G1                       | 2         | 0.62%   |
| HP ProBook 450 G2                       | 2         | 0.62%   |
| HP Pavilion g6                          | 2         | 0.62%   |
| HP Pavilion g4                          | 2         | 0.62%   |
| HP Pavilion dv7                         | 2         | 0.62%   |
| HP Pavilion 15                          | 2         | 0.62%   |
| HP Notebook                             | 2         | 0.62%   |
| HP Laptop 15-bs0xx                      | 2         | 0.62%   |
| HP EliteBook 840 G1                     | 2         | 0.62%   |
| HP EliteBook 745 G3                     | 2         | 0.62%   |
| HP Compaq Elite 8300 SFF                | 2         | 0.62%   |
| HP Compaq dc7800                        | 2         | 0.62%   |
| HP 15                                   | 2         | 0.62%   |
| Hampoo Cherry Trail CR                  | 2         | 0.62%   |
| Gigabyte H61M-S2V-B3                    | 2         | 0.62%   |
| Gigabyte H61M-S2P                       | 2         | 0.62%   |
| Gigabyte G41MT-S2P                      | 2         | 0.62%   |
| Dell Latitude E5570                     | 2         | 0.62%   |
| Dell Inspiron N5110                     | 2         | 0.62%   |
| Dell Inspiron N5010                     | 2         | 0.62%   |
| Dell Inspiron N4050                     | 2         | 0.62%   |
| Dell Inspiron 5559                      | 2         | 0.62%   |
| Dell Inspiron 3593                      | 2         | 0.62%   |
| Dell Inspiron 3543                      | 2         | 0.62%   |
| Dell Inspiron 3521                      | 2         | 0.62%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR    | 2         | 0.62%   |
| ASUS B250 MINING EXPERT                 | 2         | 0.62%   |
| Alienware Aurora R12                    | 2         | 0.62%   |
| Unknown                                 | 2         | 0.62%   |
| Toshiba Satellite L850-A894             | 1         | 0.31%   |
| Toshiba Satellite L50-A661              | 1         | 0.31%   |
| Toshiba Satellite C850D-B810            | 1         | 0.31%   |
| Toshiba Satellite C850-B341             | 1         | 0.31%   |
| Toshiba Satellite C660                  | 1         | 0.31%   |
| Toshiba Satellite A300                  | 1         | 0.31%   |
| TECNO WinPad 10A                        | 1         | 0.31%   |
| Sony SVT1121B2EW                        | 1         | 0.31%   |
| Sony SVF15328CXB                        | 1         | 0.31%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.4      | 1         | 0.31%   |
| RPi Raspberry Pi                        | 1         | 0.31%   |
| Packard Bell EasyNote TJ75              | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 36        | 11.18%  |
| Lenovo IdeaPad        | 19        | 5.9%    |
| HP Compaq             | 17        | 5.28%   |
| Lenovo ThinkPad       | 15        | 4.66%   |
| Dell OptiPlex         | 15        | 4.66%   |
| HP ProBook            | 14        | 4.35%   |
| HP Pavilion           | 14        | 4.35%   |
| HP EliteBook          | 12        | 3.73%   |
| Dell Latitude         | 12        | 3.73%   |
| HP Laptop             | 7         | 2.17%   |
| Gigabyte G41MT-S2PT   | 7         | 2.17%   |
| Dell G3               | 7         | 2.17%   |
| Toshiba Satellite     | 6         | 1.86%   |
| HP EliteDesk          | 5         | 1.55%   |
| Dell Precision        | 5         | 1.55%   |
| Acer Aspire           | 5         | 1.55%   |
| Lenovo ThinkCentre    | 4         | 1.24%   |
| Lenovo Legion         | 4         | 1.24%   |
| HP ZBook              | 4         | 1.24%   |
| ASUS VivoBook         | 4         | 1.24%   |
| Dell G5               | 3         | 0.93%   |
| RPi Raspberry         | 2         | 0.62%   |
| Packard Bell EasyNote | 2         | 0.62%   |
| Lenovo Yoga           | 2         | 0.62%   |
| Lenovo Y50-70         | 2         | 0.62%   |
| Lenovo G555           | 2         | 0.62%   |
| HP Z600               | 2         | 0.62%   |
| HP ProDesk            | 2         | 0.62%   |
| HP Notebook           | 2         | 0.62%   |
| HP 250                | 2         | 0.62%   |
| HP 15                 | 2         | 0.62%   |
| Hampoo Cherry         | 2         | 0.62%   |
| Gigabyte H61M-S2V-B3  | 2         | 0.62%   |
| Gigabyte H61M-S2P     | 2         | 0.62%   |
| Gigabyte G41MT-S2P    | 2         | 0.62%   |
| ASUS TUF              | 2         | 0.62%   |
| ASUS B250             | 2         | 0.62%   |
| Alienware Aurora      | 2         | 0.62%   |
| Acer Veriton          | 2         | 0.62%   |
| Unknown               | 2         | 0.62%   |
| TECNO WinPad          | 1         | 0.31%   |
| Sony SVT1121B2EW      | 1         | 0.31%   |
| Sony SVF15328CXB      | 1         | 0.31%   |
| Samsung 300E5EV       | 1         | 0.31%   |
| MSI MS-7C84           | 1         | 0.31%   |
| MSI MS-7C02           | 1         | 0.31%   |
| MSI MS-7507           | 1         | 0.31%   |
| MSI MS-7309           | 1         | 0.31%   |
| MSI GS65              | 1         | 0.31%   |
| MSI GL62              | 1         | 0.31%   |
| Lenovo Z50-70         | 1         | 0.31%   |
| Lenovo ThinkStation   | 1         | 0.31%   |
| Lenovo G510           | 1         | 0.31%   |
| Lenovo G50-80         | 1         | 0.31%   |
| Lenovo G50-70         | 1         | 0.31%   |
| Lenovo Flex           | 1         | 0.31%   |
| Lenovo AILZx          | 1         | 0.31%   |
| Intel E4610           | 1         | 0.31%   |
| Intel DG31PR          | 1         | 0.31%   |
| IBM 81713FG           | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 37        | 11.49%  |
| 2017    | 34        | 10.56%  |
| 2011    | 30        | 9.32%   |
| 2013    | 27        | 8.39%   |
| 2014    | 26        | 8.07%   |
| 2019    | 23        | 7.14%   |
| 2016    | 22        | 6.83%   |
| 2012    | 21        | 6.52%   |
| 2008    | 20        | 6.21%   |
| 2010    | 17        | 5.28%   |
| 2015    | 15        | 4.66%   |
| 2009    | 14        | 4.35%   |
| 2020    | 10        | 3.11%   |
| 2007    | 10        | 3.11%   |
| 2021    | 8         | 2.48%   |
| 2005    | 3         | 0.93%   |
| Unknown | 3         | 0.93%   |
| 2006    | 2         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 211       | 65.53%  |
| Desktop        | 100       | 31.06%  |
| Convertible    | 3         | 0.93%   |
| System on chip | 2         | 0.62%   |
| Tablet         | 2         | 0.62%   |
| Mini pc        | 2         | 0.62%   |
| Phone          | 1         | 0.31%   |
| Server         | 1         | 0.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 309       | 95.96%  |
| Enabled  | 13        | 4.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 322       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 26.54%  |
| 3.01-4.0    | 81        | 25%     |
| 16.01-24.0  | 72        | 22.22%  |
| 8.01-16.0   | 46        | 14.2%   |
| 2.01-3.0    | 13        | 4.01%   |
| 1.01-2.0    | 12        | 3.7%    |
| 32.01-64.0  | 7         | 2.16%   |
| 64.01-256.0 | 3         | 0.93%   |
| 24.01-32.0  | 2         | 0.62%   |
| 0.51-1.0    | 1         | 0.31%   |
| 0.01-0.5    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 113       | 32.1%   |
| 2.01-3.0    | 111       | 31.53%  |
| 4.01-8.0    | 48        | 13.64%  |
| 3.01-4.0    | 47        | 13.35%  |
| 0.51-1.0    | 16        | 4.55%   |
| 0.01-0.5    | 8         | 2.27%   |
| 8.01-16.0   | 7         | 1.99%   |
| 32.01-64.0  | 1         | 0.28%   |
| 64.01-256.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 185       | 55.22%  |
| 2       | 126       | 37.61%  |
| 3       | 17        | 5.07%   |
| 4       | 4         | 1.19%   |
| 9       | 1         | 0.3%    |
| 5       | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 52.47%  |
| Yes       | 154       | 47.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 92.24%  |
| No        | 25        | 7.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 78.09%  |
| No        | 71        | 21.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 57.67%  |
| No        | 138       | 42.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Egypt   | 322       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Cairo               | 190       | 55.56%  |
| Alexandria          | 35        | 10.23%  |
| Giza                | 24        | 7.02%   |
| Al Mansurah         | 11        | 3.22%   |
| Tanta               | 10        | 2.92%   |
| Assiut              | 5         | 1.46%   |
| Suez                | 4         | 1.17%   |
| Minya               | 4         | 1.17%   |
| Helwan              | 4         | 1.17%   |
| Awsim               | 4         | 1.17%   |
| Aswan               | 4         | 1.17%   |
| New Cairo           | 3         | 0.88%   |
| Hurghada            | 3         | 0.88%   |
| Zefta               | 2         | 0.58%   |
| Zagazig             | 2         | 0.58%   |
| Port Said           | 2         | 0.58%   |
| Mohandessin         | 2         | 0.58%   |
| Madinat as Sadat    | 2         | 0.58%   |
| Luxor               | 2         | 0.58%   |
| Ismailia            | 2         | 0.58%   |
| Edfu                | 2         | 0.58%   |
| Damietta            | 2         | 0.58%   |
| Damanhur            | 2         | 0.58%   |
| Al Ma`adi           | 2         | 0.58%   |
| 6th of October City | 2         | 0.58%   |
| Talkha              | 1         | 0.29%   |
| Monufia             | 1         | 0.29%   |
| Mashtul as Suq      | 1         | 0.29%   |
| Mallawi             | 1         | 0.29%   |
| Heliopolis          | 1         | 0.29%   |
| Fāraskūr          | 1         | 0.29%   |
| Faiyum              | 1         | 0.29%   |
| Diyarb Najm         | 1         | 0.29%   |
| Bilbeis             | 1         | 0.29%   |
| Bani Suwayf         | 1         | 0.29%   |
| Banha               | 1         | 0.29%   |
| Badr                | 1         | 0.29%   |
| Ashmun              | 1         | 0.29%   |
| Al Qalyubiyah       | 1         | 0.29%   |
| Al Fayyum           | 1         | 0.29%   |
| Akhmim              | 1         | 0.29%   |
| Aga                 | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 118       | 161    | 25.93%  |
| Seagate                   | 100       | 120    | 21.98%  |
| Toshiba                   | 52        | 64     | 11.43%  |
| Samsung Electronics       | 38        | 52     | 8.35%   |
| Kingston                  | 25        | 32     | 5.49%   |
| Crucial                   | 19        | 21     | 4.18%   |
| Unknown                   | 18        | 23     | 3.96%   |
| Hitachi                   | 12        | 15     | 2.64%   |
| SK Hynix                  | 10        | 10     | 2.2%    |
| Sandisk                   | 9         | 10     | 1.98%   |
| Micron Technology         | 6         | 6      | 1.32%   |
| Intel                     | 5         | 5      | 1.1%    |
| HS-SSD-C100               | 5         | 6      | 1.1%    |
| LITEONIT                  | 4         | 5      | 0.88%   |
| HGST                      | 4         | 4      | 0.88%   |
| TwinMOS                   | 3         | 3      | 0.66%   |
| Transcend                 | 3         | 3      | 0.66%   |
| LITEON                    | 3         | 5      | 0.66%   |
| KingSpec                  | 3         | 3      | 0.66%   |
| KIOXIA                    | 2         | 2      | 0.44%   |
| Hewlett-Packard           | 2         | 2      | 0.44%   |
| ZOTAC                     | 1         | 1      | 0.22%   |
| Verbatim                  | 1         | 1      | 0.22%   |
| UMIS                      | 1         | 1      | 0.22%   |
| Team                      | 1         | 1      | 0.22%   |
| Silicon Motion            | 1         | 1      | 0.22%   |
| Micron/Crucial Technology | 1         | 1      | 0.22%   |
| MAXTOR                    | 1         | 2      | 0.22%   |
| Lexar                     | 1         | 1      | 0.22%   |
| JMicron                   | 1         | 1      | 0.22%   |
| HUAWEI                    | 1         | 1      | 0.22%   |
| HS-SSD-E100               | 1         | 1      | 0.22%   |
| Hikvision                 | 1         | 1      | 0.22%   |
| ADATA Technology          | 1         | 1      | 0.22%   |
| A-DATA Technology         | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 30        | 6.25%   |
| Toshiba MQ04ABF100 1TB               | 11        | 2.29%   |
| Seagate ST2000LM007-1R8174 2TB       | 9         | 1.88%   |
| Kingston SA400S37480G 480GB SSD      | 8         | 1.67%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 1.67%   |
| Seagate ST3500414CS 500GB            | 7         | 1.46%   |
| Toshiba MQ01ABD100 1TB               | 6         | 1.25%   |
| Unknown MMC Card  64GB               | 5         | 1.04%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 1.04%   |
| Crucial CT480BX500SSD1 480GB         | 5         | 1.04%   |
| WDC WD10SPZX-60Z10T0 1TB             | 4         | 0.83%   |
| WDC WD10JPVX-60JC3T1 1TB             | 4         | 0.83%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.83%   |
| Seagate ST500DM002-1BD142 500GB      | 4         | 0.83%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.83%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.83%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.63%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 3         | 0.63%   |
| WDC WD1600AABS-00PRA0 160GB          | 3         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 0.63%   |
| WDC WD10JPCX-24UE4T0 1TB             | 3         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB             | 3         | 0.63%   |
| WDC WD10EARS-00Y5B1 1TB              | 3         | 0.63%   |
| Unknown SD/MMC/MS PRO 999GB          | 3         | 0.63%   |
| Unknown MMC Card  32GB               | 3         | 0.63%   |
| TwinMOS SSD 128GB                    | 3         | 0.63%   |
| Toshiba MK3276GSX 320GB              | 3         | 0.63%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 3         | 0.63%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.63%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 3         | 0.63%   |
| Seagate ST3500413AS 500GB            | 3         | 0.63%   |
| Seagate ST3500312CS 500GB            | 3         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.63%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 0.63%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.42%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.42%   |
| WDC WD5000AVVS-63H0B1 500GB          | 2         | 0.42%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 2         | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 0.42%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 0.42%   |
| WDC WD3200BPVT-75JJ5T0 320GB         | 2         | 0.42%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 0.42%   |
| WDC WD2500AAKX-75U6AA0 250GB         | 2         | 0.42%   |
| WDC WD1600BEVT-24A23T0 160GB         | 2         | 0.42%   |
| WDC WD1600AABS-00H4A0 160GB          | 2         | 0.42%   |
| WDC WD10SPZX-75Z10T1 1TB             | 2         | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.42%   |
| WDC WD10SPZX-00Z10T0 1TB             | 2         | 0.42%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.42%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.42%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 2         | 0.42%   |
| Unknown MMC Card  128GB              | 2         | 0.42%   |
| Toshiba MQ01ACF032 320GB             | 2         | 0.42%   |
| Toshiba MK3275GSX 320GB              | 2         | 0.42%   |
| Toshiba MK3256GSY 320GB              | 2         | 0.42%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 109       | 151    | 38.79%  |
| Seagate             | 100       | 119    | 35.59%  |
| Toshiba             | 46        | 56     | 16.37%  |
| Hitachi             | 12        | 15     | 4.27%   |
| Samsung Electronics | 5         | 9      | 1.78%   |
| HGST                | 4         | 4      | 1.42%   |
| Unknown             | 3         | 3      | 1.07%   |
| MAXTOR              | 1         | 2      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 25        | 32     | 21.37%  |
| Samsung Electronics | 18        | 19     | 15.38%  |
| Crucial             | 18        | 20     | 15.38%  |
| WDC                 | 8         | 8      | 6.84%   |
| SanDisk             | 7         | 8      | 5.98%   |
| Micron Technology   | 5         | 5      | 4.27%   |
| Intel               | 5         | 5      | 4.27%   |
| SK Hynix            | 4         | 4      | 3.42%   |
| LITEONIT            | 4         | 5      | 3.42%   |
| TwinMOS             | 3         | 3      | 2.56%   |
| Transcend           | 3         | 3      | 2.56%   |
| Toshiba             | 3         | 4      | 2.56%   |
| LITEON              | 3         | 5      | 2.56%   |
| KingSpec            | 3         | 3      | 2.56%   |
| ZOTAC               | 1         | 1      | 0.85%   |
| Verbatim            | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| Lexar               | 1         | 1      | 0.85%   |
| JMicron             | 1         | 1      | 0.85%   |
| HS-SSD-C100         | 1         | 2      | 0.85%   |
| Hikvision           | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 260       | 360    | 60.61%  |
| SSD     | 107       | 133    | 24.94%  |
| NVMe    | 42        | 50     | 9.79%   |
| MMC     | 14        | 18     | 3.26%   |
| Unknown | 6         | 6      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 300       | 494    | 83.1%   |
| NVMe | 42        | 50     | 11.63%  |
| MMC  | 14        | 18     | 3.88%   |
| SAS  | 5         | 5      | 1.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 299    | 57.38%  |
| 0.51-1.0   | 131       | 163    | 36.49%  |
| 1.01-2.0   | 19        | 21     | 5.29%   |
| 3.01-4.0   | 2         | 4      | 0.56%   |
| 4.01-10.0  | 1         | 6      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 25.51%  |
| 251-500        | 73        | 21.41%  |
| 501-1000       | 48        | 14.08%  |
| 51-100         | 45        | 13.2%   |
| 1001-2000      | 26        | 7.62%   |
| 1-20           | 26        | 7.62%   |
| 21-50          | 23        | 6.74%   |
| Unknown        | 7         | 2.05%   |
| More than 3000 | 3         | 0.88%   |
| 2001-3000      | 3         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 37.97%  |
| 21-50          | 60        | 17.39%  |
| 101-250        | 60        | 17.39%  |
| 51-100         | 38        | 11.01%  |
| 251-500        | 24        | 6.96%   |
| 501-1000       | 20        | 5.8%    |
| Unknown        | 7         | 2.03%   |
| More than 3000 | 2         | 0.58%   |
| 1001-2000      | 2         | 0.58%   |
| 2001-3000      | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 3      | 5.88%   |
| WDC WD5000AVVS-63H0B1 500GB                         | 2         | 2      | 3.92%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2         | 3      | 3.92%   |
| WDC WD1600AABS-00H4A0 160GB                         | 2         | 2      | 3.92%   |
| Seagate ST380815AS 80GB                             | 2         | 2      | 3.92%   |
| WDC WD800JD-60LSA5 80GB                             | 1         | 1      | 1.96%   |
| WDC WD800BD-22MRA1 80GB                             | 1         | 1      | 1.96%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 1.96%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 1.96%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 1.96%   |
| WDC WD5000AAVS-22G9B1 500GB                         | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-009FA0 500GB                         | 1         | 1      | 1.96%   |
| WDC WD5000AAKS-00V6A0 500GB                         | 1         | 1      | 1.96%   |
| WDC WD5000AADS-00M2B0 500GB                         | 1         | 1      | 1.96%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 1.96%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1         | 1      | 1.96%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 1         | 1      | 1.96%   |
| WDC WD3200A 320GB                                   | 1         | 1      | 1.96%   |
| WDC WD2500AAJS-00VTA0 250GB                         | 1         | 1      | 1.96%   |
| WDC WD1600AVVS-63L2B0 160GB                         | 1         | 1      | 1.96%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 1         | 1      | 1.96%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1      | 1.96%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 1.96%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 1.96%   |
| Seagate ST95005620AS 500GB                          | 1         | 2      | 1.96%   |
| Seagate ST9320328CS 320GB                           | 1         | 2      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 3      | 1.96%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 1.96%   |
| Seagate ST3500312CS 500GB                           | 1         | 1      | 1.96%   |
| Seagate ST3320613AS 320GB                           | 1         | 1      | 1.96%   |
| Seagate ST3160211AS 160GB                           | 1         | 2      | 1.96%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 1.96%   |
| Samsung Electronics HD256GJ 250GB                   | 1         | 1      | 1.96%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 1.96%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 1.96%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 2      | 1.96%   |
| Intel SSDSC2BW120H6 120GB                           | 1         | 1      | 1.96%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 1.96%   |
| Hewlett-Packard VB0250EAVER 250GB                   | 1         | 1      | 1.96%   |
| A-DATA Technology IM2P33F3 NVMe 256GB               | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 27     | 46.81%  |
| Seagate             | 14        | 19     | 29.79%  |
| Samsung Electronics | 2         | 2      | 4.26%   |
| Micron Technology   | 2         | 2      | 4.26%   |
| Intel               | 2         | 2      | 4.26%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SK Hynix            | 1         | 1      | 2.13%   |
| Kingston            | 1         | 2      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 27     | 56.41%  |
| Seagate             | 14        | 19     | 35.9%   |
| Toshiba             | 1         | 1      | 2.56%   |
| Samsung Electronics | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 49     | 82.22%  |
| SSD  | 7         | 8      | 15.56%  |
| NVMe | 1         | 1      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 213       | 345    | 61.03%  |
| Works    | 90        | 162    | 25.79%  |
| Malfunc  | 45        | 58     | 12.89%  |
| Failed   | 1         | 2      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 264       | 74.37%  |
| AMD                          | 38        | 10.7%   |
| Samsung Electronics          | 18        | 5.07%   |
| SK Hynix                     | 6         | 1.69%   |
| Toshiba America Info Systems | 5         | 1.41%   |
| Sandisk                      | 4         | 1.13%   |
| Nvidia                       | 2         | 0.56%   |
| Micron/Crucial Technology    | 2         | 0.56%   |
| Marvell Technology Group     | 2         | 0.56%   |
| KIOXIA                       | 2         | 0.56%   |
| Broadcom / LSI               | 2         | 0.56%   |
| ADATA Technology             | 2         | 0.56%   |
| VIA Technologies             | 1         | 0.28%   |
| Union Memory (Shenzhen)      | 1         | 0.28%   |
| Silicon Motion               | 1         | 0.28%   |
| Shenzhen Longsys Electronics | 1         | 0.28%   |
| Seagate Technology           | 1         | 0.28%   |
| Micron Technology            | 1         | 0.28%   |
| LSI Logic / Symbios Logic    | 1         | 0.28%   |
| JMicron Technology           | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 37        | 8.98%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 25        | 6.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 4.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15        | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 3.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 14        | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 2.67%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 2.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.18%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 1.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 7         | 1.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.21%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 0.97%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 0.97%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 0.97%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4         | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 0.97%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.73%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 0.73%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.73%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3         | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3         | 0.73%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3         | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.73%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 0.73%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 0.73%   |
| SK Hynix Gold P31 SSD                                                                   | 2         | 0.49%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.49%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.49%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile              | 2         | 0.49%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2         | 0.49%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2         | 0.49%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2         | 0.49%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 237       | 64.4%   |
| IDE  | 60        | 16.3%   |
| NVMe | 44        | 11.96%  |
| RAID | 22        | 5.98%   |
| SAS  | 4         | 1.09%   |
| SCSI | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 279       | 86.65%  |
| AMD    | 40        | 12.42%  |
| ARM    | 3         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz            | 13        | 4.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 10        | 3.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz            | 8         | 2.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 7         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 6         | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 5         | 1.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 4         | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 4         | 1.24%   |
| Intel Core i5-4590 CPU @ 3.30GHz             | 4         | 1.24%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 4         | 1.24%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz         | 4         | 1.24%   |
| Intel Pentium D CPU 3.00GHz                  | 3         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 3         | 0.93%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz           | 3         | 0.93%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 3         | 0.93%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 3         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 3         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 3         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 3         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 3         | 0.93%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 3         | 0.93%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 3         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 0.93%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 3         | 0.93%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz         | 3         | 0.93%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 3         | 0.93%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz         | 3         | 0.93%   |
| Intel Pentium 4 CPU 3.20GHz                  | 2         | 0.62%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 2         | 0.62%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 0.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz             | 2         | 0.62%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 2         | 0.62%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 2         | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 2         | 0.62%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 2         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 2         | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 2         | 0.62%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 0.62%   |
| Intel Core i3-7020U CPU @ 2.30GHz            | 2         | 0.62%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.62%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 2         | 0.62%   |
| Intel Core i3-2120 CPU @ 3.30GHz             | 2         | 0.62%   |
| Intel Core i3-2100 CPU @ 3.10GHz             | 2         | 0.62%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 0.62%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 0.62%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz         | 2         | 0.62%   |
| Intel Core 2 Duo CPU E4400 @ 2.00GHz         | 2         | 0.62%   |
| Intel Core 2 CPU 6600 @ 2.40GHz              | 2         | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 2         | 0.62%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 2         | 0.62%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 2         | 0.62%   |
| ARM Processor                                | 2         | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor          | 2         | 0.62%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G | 2         | 0.62%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 100       | 30.96%  |
| Intel Core i5           | 74        | 22.91%  |
| Intel Core i3           | 27        | 8.36%   |
| Intel Core 2 Duo        | 26        | 8.05%   |
| Intel Xeon              | 11        | 3.41%   |
| Other                   | 8         | 2.48%   |
| Intel Pentium           | 6         | 1.86%   |
| Intel Celeron           | 6         | 1.86%   |
| Intel Atom              | 6         | 1.86%   |
| AMD Ryzen 5             | 5         | 1.55%   |
| Intel Pentium Dual-Core | 4         | 1.24%   |
| Intel Core 2            | 4         | 1.24%   |
| AMD PRO A10             | 4         | 1.24%   |
| Intel Pentium D         | 3         | 0.93%   |
| Intel Pentium 4         | 3         | 0.93%   |
| AMD Ryzen 7             | 3         | 0.93%   |
| AMD A8                  | 3         | 0.93%   |
| AMD A6                  | 3         | 0.93%   |
| AMD A4                  | 3         | 0.93%   |
| Intel Core 2 Quad       | 2         | 0.62%   |
| AMD Phenom              | 2         | 0.62%   |
| AMD E2                  | 2         | 0.62%   |
| AMD E1                  | 2         | 0.62%   |
| AMD Athlon II Dual-Core | 2         | 0.62%   |
| Intel Xeon Silver       | 1         | 0.31%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| ARM AArch64             | 1         | 0.31%   |
| AMD Sempron             | 1         | 0.31%   |
| AMD Ryzen 9             | 1         | 0.31%   |
| AMD Ryzen 3 PRO         | 1         | 0.31%   |
| AMD Phenom II X4        | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD Athlon II X3        | 1         | 0.31%   |
| AMD Athlon II X2        | 1         | 0.31%   |
| AMD Athlon 64 X2        | 1         | 0.31%   |
| AMD Athlon 64           | 1         | 0.31%   |
| AMD A10                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 159       | 49.23%  |
| 4      | 113       | 34.98%  |
| 6      | 22        | 6.81%   |
| 8      | 11        | 3.41%   |
| 1      | 9         | 2.79%   |
| 16     | 3         | 0.93%   |
| 3      | 3         | 0.93%   |
| 24     | 1         | 0.31%   |
| 12     | 1         | 0.31%   |
| 10     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 314       | 97.52%  |
| 2      | 8         | 2.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 218       | 67.28%  |
| 1      | 106       | 32.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 311       | 95.99%  |
| Unknown        | 10        | 3.09%   |
| 32-bit         | 3         | 0.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 21.39%  |
| 0x206a7    | 24        | 7.23%   |
| 0x306c3    | 21        | 6.33%   |
| 0x306a9    | 17        | 5.12%   |
| 0x1067a    | 17        | 5.12%   |
| 0x906ea    | 15        | 4.52%   |
| 0x806ea    | 13        | 3.92%   |
| 0x40651    | 13        | 3.92%   |
| 0x806e9    | 12        | 3.61%   |
| 0x806ec    | 10        | 3.01%   |
| 0x406e3    | 8         | 2.41%   |
| 0x306d4    | 8         | 2.41%   |
| 0x906e9    | 7         | 2.11%   |
| 0x6fd      | 6         | 1.81%   |
| 0x706e5    | 4         | 1.2%    |
| 0x6fb      | 4         | 1.2%    |
| 0x506e3    | 4         | 1.2%    |
| 0x20655    | 4         | 1.2%    |
| 0x20652    | 4         | 1.2%    |
| 0xa0652    | 3         | 0.9%    |
| 0x806eb    | 3         | 0.9%    |
| 0x406c3    | 3         | 0.9%    |
| 0x30678    | 3         | 0.9%    |
| 0x206c2    | 3         | 0.9%    |
| 0x10676    | 3         | 0.9%    |
| 0x0800820d | 3         | 0.9%    |
| 0x06006705 | 3         | 0.9%    |
| 0xf65      | 2         | 0.6%    |
| 0xf41      | 2         | 0.6%    |
| 0xa0671    | 2         | 0.6%    |
| 0x6f6      | 2         | 0.6%    |
| 0x406c4    | 2         | 0.6%    |
| 0x306e4    | 2         | 0.6%    |
| 0x106a5    | 2         | 0.6%    |
| 0x06006704 | 2         | 0.6%    |
| 0x06001119 | 2         | 0.6%    |
| 0x010000c8 | 2         | 0.6%    |
| 0x01000095 | 2         | 0.6%    |
| 0xf64      | 1         | 0.3%    |
| 0xf43      | 1         | 0.3%    |
| 0x906ed    | 1         | 0.3%    |
| 0x806c1    | 1         | 0.3%    |
| 0x6f2      | 1         | 0.3%    |
| 0x6e8      | 1         | 0.3%    |
| 0x506c9    | 1         | 0.3%    |
| 0x306f2    | 1         | 0.3%    |
| 0x206d7    | 1         | 0.3%    |
| 0x106e5    | 1         | 0.3%    |
| 0x0a50000c | 1         | 0.3%    |
| 0x0a201009 | 1         | 0.3%    |
| 0x08701013 | 1         | 0.3%    |
| 0x08600106 | 1         | 0.3%    |
| 0x08108102 | 1         | 0.3%    |
| 0x08101016 | 1         | 0.3%    |
| 0x07030106 | 1         | 0.3%    |
| 0x0600611a | 1         | 0.3%    |
| 0x06006110 | 1         | 0.3%    |
| 0x06003109 | 1         | 0.3%    |
| 0x0600111f | 1         | 0.3%    |
| 0x05000119 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 78        | 24.15%  |
| Haswell     | 42        | 13%     |
| SandyBridge | 28        | 8.67%   |
| Penryn      | 22        | 6.81%   |
| IvyBridge   | 21        | 6.5%    |
| Skylake     | 16        | 4.95%   |
| Core        | 15        | 4.64%   |
| Westmere    | 14        | 4.33%   |
| Silvermont  | 10        | 3.1%    |
| Excavator   | 9         | 2.79%   |
| Broadwell   | 9         | 2.79%   |
| NetBurst    | 8         | 2.48%   |
| K10         | 8         | 2.48%   |
| IceLake     | 6         | 1.86%   |
| Zen+        | 4         | 1.24%   |
| Piledriver  | 4         | 1.24%   |
| CometLake   | 4         | 1.24%   |
| Unknown     | 4         | 1.24%   |
| Zen 2       | 3         | 0.93%   |
| Steamroller | 3         | 0.93%   |
| Nehalem     | 3         | 0.93%   |
| Zen 3       | 2         | 0.62%   |
| Puma        | 2         | 0.62%   |
| K8 Hammer   | 2         | 0.62%   |
| Bobcat      | 2         | 0.62%   |
| Zen         | 1         | 0.31%   |
| TigerLake   | 1         | 0.31%   |
| P6          | 1         | 0.31%   |
| Goldmont    | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 231       | 52.26%  |
| Nvidia           | 111       | 25.11%  |
| AMD              | 99        | 22.4%   |
| VIA Technologies | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 4.48%   |
| Intel UHD Graphics 620                                                                   | 19        | 4.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 3.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 3.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 2.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 2.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 2.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.24%   |
| Intel HD Graphics 620                                                                    | 10        | 2.24%   |
| Nvidia GM108M [GeForce MX130]                                                            | 9         | 2.02%   |
| Intel HD Graphics 630                                                                    | 9         | 2.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.79%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.35%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 1.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.12%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.9%    |
| Intel HD Graphics 530                                                                    | 4         | 0.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.9%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.9%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.67%   |
| Nvidia GF108GL [Quadro 600]                                                              | 3         | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 3         | 0.67%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.67%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 3         | 0.67%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.67%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.45%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.45%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.45%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.45%   |
| Nvidia GF119 [NVS 315]                                                                   | 2         | 0.45%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 2         | 0.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.45%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 2         | 0.45%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 0.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 112       | 34.67%  |
| Intel + Nvidia | 70        | 21.67%  |
| Intel + AMD    | 48        | 14.86%  |
| 1 x AMD        | 45        | 13.93%  |
| 1 x Nvidia     | 38        | 11.76%  |
| Other          | 3         | 0.93%   |
| AMD + Nvidia   | 3         | 0.93%   |
| 2 x AMD        | 2         | 0.62%   |
| 3 x AMD        | 1         | 0.31%   |
| 1 x VIA        | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 258       | 78.42%  |
| Proprietary | 54        | 16.41%  |
| Unknown     | 17        | 5.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 50.61%  |
| 1.01-2.0   | 55        | 16.67%  |
| 3.01-4.0   | 40        | 12.12%  |
| 0.01-0.5   | 31        | 9.39%   |
| 0.51-1.0   | 24        | 7.27%   |
| 7.01-8.0   | 8         | 2.42%   |
| 5.01-6.0   | 3         | 0.91%   |
| 8.01-16.0  | 2         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 52        | 17.05%  |
| LG Display              | 45        | 14.75%  |
| BOE                     | 45        | 14.75%  |
| Chimei Innolux          | 36        | 11.8%   |
| AU Optronics            | 35        | 11.48%  |
| Dell                    | 19        | 6.23%   |
| Hewlett-Packard         | 17        | 5.57%   |
| Lenovo                  | 11        | 3.61%   |
| Chi Mei Optoelectronics | 11        | 3.61%   |
| Philips                 | 4         | 1.31%   |
| InfoVision              | 3         | 0.98%   |
| Goldstar                | 3         | 0.98%   |
| PANDA                   | 2         | 0.66%   |
| Panasonic               | 2         | 0.66%   |
| Fujitsu Siemens         | 2         | 0.66%   |
| Eizo                    | 2         | 0.66%   |
| Sun                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| Planar                  | 1         | 0.33%   |
| NEC Computers           | 1         | 0.33%   |
| MStar                   | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| JWY                     | 1         | 0.33%   |
| Gigabyte Technology     | 1         | 0.33%   |
| eMachines               | 1         | 0.33%   |
| CPT                     | 1         | 0.33%   |
| BenQ                    | 1         | 0.33%   |
| AUS                     | 1         | 0.33%   |
| ASUSTek Computer        | 1         | 0.33%   |
| Apple                   | 1         | 0.33%   |
| AOC                     | 1         | 0.33%   |
| Ancor Communications    | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 2.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 1.94%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 4         | 1.29%   |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                    | 4         | 1.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.29%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 3         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.97%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.97%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 3         | 0.97%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch              | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.97%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 3         | 0.97%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 2         | 0.65%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch      | 2         | 0.65%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 2         | 0.65%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 2         | 0.65%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.65%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.65%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 2         | 0.65%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 2         | 0.65%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch             | 2         | 0.65%   |
| Dell P2210 DEL404E 1680x1050 474x296mm 22.0-inch                         | 2         | 0.65%   |
| Dell E2014H DELD03B 1600x900 432x240mm 19.5-inch                         | 2         | 0.65%   |
| Dell E170S DELA04A 1280x1024 338x270mm 17.0-inch                         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| BOE LCD Monitor BOE0826 1920x1080 344x193mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.65%   |
| Sun PN17JO SUN0589 1280x1024 295x236mm 14.9-inch                         | 1         | 0.32%   |
| Sony KDL-23S2000 SNY9900 1360x768                                        | 1         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch        | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0590 1600x900 443x249mm 20.0-inch      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch     | 1         | 0.32%   |
| Samsung Electronics SMBX2031 SAM076A 1600x900 443x249mm 20.0-inch        | 1         | 0.32%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 477x268mm 21.5-inch        | 1         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 1         | 0.32%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1         | 0.32%   |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch        | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 115       | 38.33%  |
| 1920x1080 (FHD)    | 111       | 37%     |
| 1280x1024 (SXGA)   | 17        | 5.67%   |
| 1600x900 (HD+)     | 12        | 4%      |
| 1440x900 (WXGA+)   | 11        | 3.67%   |
| 3840x2160 (4K)     | 8         | 2.67%   |
| 1680x1050 (WSXGA+) | 7         | 2.33%   |
| 1280x800 (WXGA)    | 6         | 2%      |
| 2560x1440 (QHD)    | 2         | 0.67%   |
| 3440x1440          | 1         | 0.33%   |
| 3200x1800 (QHD+)   | 1         | 0.33%   |
| 2560x1600          | 1         | 0.33%   |
| 2160x1440          | 1         | 0.33%   |
| 1920x540           | 1         | 0.33%   |
| 1920x1200 (WUXGA)  | 1         | 0.33%   |
| 1600x1200          | 1         | 0.33%   |
| 1400x1050          | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1280x720 (HD)      | 1         | 0.33%   |
| 1024x768 (XGA)     | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 150       | 49.18%  |
| 14      | 30        | 9.84%   |
| 17      | 20        | 6.56%   |
| 19      | 14        | 4.59%   |
| 13      | 14        | 4.59%   |
| 18      | 11        | 3.61%   |
| Unknown | 11        | 3.61%   |
| 24      | 9         | 2.95%   |
| 21      | 8         | 2.62%   |
| 27      | 7         | 2.3%    |
| 22      | 7         | 2.3%    |
| 12      | 6         | 1.97%   |
| 23      | 5         | 1.64%   |
| 20      | 5         | 1.64%   |
| 11      | 2         | 0.66%   |
| 34      | 1         | 0.33%   |
| 32      | 1         | 0.33%   |
| 31      | 1         | 0.33%   |
| 29      | 1         | 0.33%   |
| 25      | 1         | 0.33%   |
| 16      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 195       | 64.57%  |
| 401-500     | 37        | 12.25%  |
| 351-400     | 21        | 6.95%   |
| 501-600     | 19        | 6.29%   |
| 201-300     | 13        | 4.3%    |
| Unknown     | 11        | 3.64%   |
| 601-700     | 4         | 1.32%   |
| 701-800     | 2         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 235       | 80.48%  |
| 16/10   | 26        | 8.9%    |
| 5/4     | 14        | 4.79%   |
| Unknown | 10        | 3.42%   |
| 4/3     | 6         | 2.05%   |
| 21/9    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 146       | 48.18%  |
| 81-90          | 38        | 12.54%  |
| 151-200        | 25        | 8.25%   |
| 201-250        | 19        | 6.27%   |
| 141-150        | 17        | 5.61%   |
| Unknown        | 11        | 3.63%   |
| 121-130        | 9         | 2.97%   |
| 301-350        | 7         | 2.31%   |
| 61-70          | 6         | 1.98%   |
| 251-300        | 6         | 1.98%   |
| 71-80          | 4         | 1.32%   |
| 351-500        | 4         | 1.32%   |
| 131-140        | 4         | 1.32%   |
| 91-100         | 3         | 0.99%   |
| 51-60          | 2         | 0.66%   |
| 111-120        | 2         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 110       | 37.04%  |
| 121-160       | 91        | 30.64%  |
| 51-100        | 80        | 26.94%  |
| Unknown       | 11        | 3.7%    |
| More than 240 | 3         | 1.01%   |
| 161-240       | 2         | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 289       | 87.31%  |
| 2     | 23        | 6.95%   |
| 0     | 18        | 5.44%   |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 194       | 37.82%  |
| Intel                             | 147       | 28.65%  |
| Qualcomm Atheros                  | 70        | 13.65%  |
| Broadcom                          | 40        | 7.8%    |
| Ralink Technology                 | 14        | 2.73%   |
| Broadcom Limited                  | 10        | 1.95%   |
| Ralink                            | 8         | 1.56%   |
| Samsung Electronics               | 4         | 0.78%   |
| Huawei Technologies               | 4         | 0.78%   |
| TP-Link                           | 3         | 0.58%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| Nvidia                            | 2         | 0.39%   |
| MediaTek                          | 2         | 0.39%   |
| Marvell Technology Group          | 2         | 0.39%   |
| Edimax Technology                 | 2         | 0.39%   |
| VIA Technologies                  | 1         | 0.19%   |
| Sundance Technology Inc / IC Plus | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| Motorola                          | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| D-Link                            | 1         | 0.19%   |
| ASIX Electronics                  | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 117       | 20.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 56        | 9.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 25        | 4.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 12        | 2.08%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 1.9%    |
| Ralink RT5370 Wireless Adapter                                                | 10        | 1.73%   |
| Intel Wireless 8265 / 8275                                                    | 10        | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 1.56%   |
| Intel Wireless 7260                                                           | 9         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8         | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8         | 1.38%   |
| Intel Wireless 8260                                                           | 8         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 8         | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 8         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 8         | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 1.21%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7         | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 1.21%   |
| Intel Wireless 7265                                                           | 7         | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 7         | 1.21%   |
| Intel Wireless 3160                                                           | 6         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 5         | 0.87%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 5         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                               | 4         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 0.69%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 0.69%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4         | 0.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 4         | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 3         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3         | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 3         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.52%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 0.52%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 3         | 0.52%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 0.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 0.52%   |
| Intel 82566DM Gigabit Network Connection                                      | 3         | 0.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2         | 0.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.35%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.35%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 2         | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 2         | 0.35%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 0.35%   |
| Intel PRODUCT_MODEM                                                           | 2         | 0.35%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 39.23%  |
| Qualcomm Atheros                | 52        | 20%     |
| Realtek Semiconductor           | 45        | 17.31%  |
| Broadcom                        | 23        | 8.85%   |
| Ralink Technology               | 14        | 5.38%   |
| Ralink                          | 8         | 3.08%   |
| Broadcom Limited                | 6         | 2.31%   |
| TP-Link                         | 3         | 1.15%   |
| Qualcomm Atheros Communications | 2         | 0.77%   |
| Edimax Technology               | 2         | 0.77%   |
| MEDIATEK                        | 1         | 0.38%   |
| Dell                            | 1         | 0.38%   |
| D-Link                          | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 25        | 9.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 12        | 4.58%   |
| Ralink RT5370 Wireless Adapter                                                | 10        | 3.82%   |
| Intel Wireless 8265 / 8275                                                    | 10        | 3.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 3.44%   |
| Intel Wireless 7260                                                           | 9         | 3.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8         | 3.05%   |
| Intel Wireless 8260                                                           | 8         | 3.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 8         | 3.05%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 8         | 3.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 8         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 2.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 7         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 2.67%   |
| Intel Wireless 7265                                                           | 7         | 2.67%   |
| Intel Wireless 3160                                                           | 6         | 2.29%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 2.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5         | 1.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 1.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 5         | 1.91%   |
| Ralink MT7601U Wireless Adapter                                               | 4         | 1.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 1.53%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 1.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.15%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 3         | 1.15%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 1.15%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.76%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 2         | 0.76%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 2         | 0.76%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 0.76%   |
| Intel PRODUCT_MODEM                                                           | 2         | 0.76%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.76%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.76%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 2         | 0.76%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 2         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 2         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.38%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 0.38%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 177       | 57.28%  |
| Intel                             | 72        | 23.3%   |
| Qualcomm Atheros                  | 23        | 7.44%   |
| Broadcom                          | 17        | 5.5%    |
| Samsung Electronics               | 4         | 1.29%   |
| Broadcom Limited                  | 4         | 1.29%   |
| Nvidia                            | 2         | 0.65%   |
| Marvell Technology Group          | 2         | 0.65%   |
| Huawei Technologies               | 2         | 0.65%   |
| VIA Technologies                  | 1         | 0.32%   |
| Sundance Technology Inc / IC Plus | 1         | 0.32%   |
| Qualcomm                          | 1         | 0.32%   |
| MediaTek                          | 1         | 0.32%   |
| Lenovo                            | 1         | 0.32%   |
| ASIX Electronics                  | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 117       | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 56        | 17.95%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 13        | 4.17%   |
| Intel Ethernet Connection I217-LM                                          | 11        | 3.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8         | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 7         | 2.24%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 5         | 1.6%    |
| Intel Ethernet Connection I218-LM                                          | 4         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                      | 4         | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4         | 1.28%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 4         | 1.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 3         | 0.96%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 3         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 3         | 0.96%   |
| Intel Ethernet Connection I219-LM                                          | 3         | 0.96%   |
| Intel 82566DM Gigabit Network Connection                                   | 3         | 0.96%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 2         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 2         | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.64%   |
| Intel I211 Gigabit Network Connection                                      | 2         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                      | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                       | 2         | 0.64%   |
| Intel 82579V Gigabit Network Connection                                    | 2         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                                   | 2         | 0.64%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2         | 0.64%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 2         | 0.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1         | 0.32%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                          | 1         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.32%   |
| Qualcomm Redmi Note 9S                                                     | 1         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                     | 1         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.32%   |
| Nvidia MCP79 Ethernet                                                      | 1         | 0.32%   |
| Nvidia MCP61 Ethernet                                                      | 1         | 0.32%   |
| MediaTek Vodafone Smart N10                                                | 1         | 0.32%   |
| Lenovo Lenovo                                                              | 1         | 0.32%   |
| Intel I210 Gigabit Network Connection                                      | 1         | 0.32%   |
| Intel Ethernet Connection I217-V                                           | 1         | 0.32%   |
| Intel Ethernet Connection (7) I219-V                                       | 1         | 0.32%   |
| Intel Ethernet Connection (5) I219-V                                       | 1         | 0.32%   |
| Intel Ethernet Connection (4) I219-V                                       | 1         | 0.32%   |
| Intel Ethernet Connection (4) I219-LM                                      | 1         | 0.32%   |
| Intel Ethernet Connection (3) I219-LM                                      | 1         | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1         | 0.32%   |
| Intel Ethernet Connection (13) I219-V                                      | 1         | 0.32%   |
| Intel 82578DM Gigabit Network Connection                                   | 1         | 0.32%   |
| Intel 82567LM Gigabit Network Connection                                   | 1         | 0.32%   |
| Intel 82566MM Gigabit Network Connection                                   | 1         | 0.32%   |
| Huawei MAR-LX1A                                                            | 1         | 0.32%   |
| Huawei E353/E3131                                                          | 1         | 0.32%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1         | 0.32%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 1         | 0.32%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                              | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 297       | 53.71%  |
| WiFi     | 252       | 45.57%  |
| Modem    | 4         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 204       | 63.35%  |
| Ethernet | 118       | 36.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 206       | 63.98%  |
| 1     | 104       | 32.3%   |
| 0     | 10        | 3.11%   |
| 3     | 2         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 322       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 44.97%  |
| Qualcomm Atheros Communications | 30        | 15.87%  |
| Realtek Semiconductor           | 22        | 11.64%  |
| Broadcom                        | 15        | 7.94%   |
| Cambridge Silicon Radio         | 8         | 4.23%   |
| Foxconn / Hon Hai               | 6         | 3.17%   |
| Toshiba                         | 5         | 2.65%   |
| Ralink                          | 4         | 2.12%   |
| Lite-On Technology              | 4         | 2.12%   |
| IMC Networks                    | 4         | 2.12%   |
| Dell                            | 3         | 1.59%   |
| MediaTek                        | 1         | 0.53%   |
| Hewlett-Packard                 | 1         | 0.53%   |
| Apple                           | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 43        | 22.75%  |
| Qualcomm Atheros  Bluetooth Device                     | 25        | 13.23%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 16        | 8.47%   |
| Intel AX201 Bluetooth                                  | 14        | 7.41%   |
| Realtek Bluetooth Radio                                | 12        | 6.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 8         | 4.23%   |
| Realtek  Bluetooth 4.2 Adapter                         | 5         | 2.65%   |
| Ralink RT3290 Bluetooth                                | 4         | 2.12%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 4         | 2.12%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 4         | 2.12%   |
| Realtek RTL8723B Bluetooth                             | 3         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 3         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth             | 3         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3         | 1.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 3         | 1.59%   |
| Dell Wireless 365 Bluetooth                            | 3         | 1.59%   |
| Intel AX200 Bluetooth                                  | 2         | 1.06%   |
| IMC Networks Bluetooth Radio                           | 2         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                     | 2         | 1.06%   |
| Foxconn / Hon Hai BCM20702A0                           | 2         | 1.06%   |
| Broadcom HP Portable SoftSailing                       | 2         | 1.06%   |
| Broadcom HP Portable Bumble Bee                        | 2         | 1.06%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 2         | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                            | 2         | 1.06%   |
| Toshiba RT Bluetooth Radio                             | 1         | 0.53%   |
| Toshiba Integrated Bluetooth HCI                       | 1         | 0.53%   |
| Toshiba Bluetooth USB Host Controller                  | 1         | 0.53%   |
| Toshiba Bluetooth Device                               | 1         | 0.53%   |
| Toshiba Askey Bluetooth Module                         | 1         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 0.53%   |
| Realtek 802.11ac WLAN Adapter                          | 1         | 0.53%   |
| Qualcomm Atheros Bluetooth USB Host Controller         | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 0.53%   |
| MediaTek MT7630e Bluetooth Adapter                     | 1         | 0.53%   |
| Lite-On Bluetooth Device                               | 1         | 0.53%   |
| IMC Networks Bluetooth Device                          | 1         | 0.53%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 0.53%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 0.53%   |
| Foxconn / Hon Hai BCM43142A0                           | 1         | 0.53%   |
| Foxconn / Hon Hai Acer Bluetooth module                | 1         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth Device                   | 1         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                      | 1         | 0.53%   |
| Broadcom BCM20702A0                                    | 1         | 0.53%   |
| Apple Bluetooth Host Controller                        | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 269       | 68.45%  |
| AMD                    | 59        | 15.01%  |
| Nvidia                 | 56        | 14.25%  |
| Logitech               | 2         | 0.51%   |
| JMTek                  | 2         | 0.51%   |
| VIA Technologies       | 1         | 0.25%   |
| Thermaltake            | 1         | 0.25%   |
| Tenx Technology        | 1         | 0.25%   |
| Generalplus Technology | 1         | 0.25%   |
| C-Media Electronics    | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 8.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 4.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 3.87%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 3.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 3.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 1.72%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 7         | 1.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.29%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.29%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.65%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.65%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.43%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.43%   |
| Intel Audio device                                                                                | 2         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.43%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 2         | 0.43%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.43%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.43%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK Hynix                     | 55        | 26.96%  |
| Samsung Electronics          | 48        | 23.53%  |
| Unknown                      | 24        | 11.76%  |
| Kingston                     | 19        | 9.31%   |
| Micron Technology            | 16        | 7.84%   |
| Ramaxel Technology           | 12        | 5.88%   |
| Crucial                      | 10        | 4.9%    |
| Nanya Technology             | 6         | 2.94%   |
| Corsair                      | 3         | 1.47%   |
| MINPO                        | 2         | 0.98%   |
| M                            | 2         | 0.98%   |
| ELPIDA                       | 2         | 0.98%   |
| Unknown (E)                  | 1         | 0.49%   |
| Unknown (ABCD)               | 1         | 0.49%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.49%   |
| G.Skill                      | 1         | 0.49%   |
| AXIOM                        | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 7         | 3.24%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 5         | 2.31%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s        | 3         | 1.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 3         | 1.39%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s          | 3         | 1.39%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s            | 3         | 1.39%   |
| Unknown RAM Module 4GB DIMM 400MT/s                             | 2         | 0.93%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                          | 2         | 0.93%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 2         | 0.93%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 2         | 0.93%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                          | 2         | 0.93%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s              | 2         | 0.93%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 0.93%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s          | 2         | 0.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 0.93%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 0.93%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 2         | 0.93%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 2         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.93%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.93%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s       | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 0.93%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s             | 2         | 0.93%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 2         | 0.93%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s       | 2         | 0.93%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s            | 2         | 0.93%   |
| M RAM Module 2048MB DIMM DDR3 667MT/s                           | 2         | 0.93%   |
| Kingston RAM XK2M26-MIE 16384MB DIMM DDR4 3467MT/s              | 2         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3                              | 1         | 0.46%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 512MB DIMM DDR 667MT/s                       | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                     | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR2                             | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                             | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 667MT/s                     | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2                             | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 1         | 0.46%   |
| Unknown RAM Module 1GB DIMM SDRAM                               | 1         | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 1         | 0.46%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                          | 1         | 0.46%   |
| Unknown (E) RAM Module 4096MB DIMM DDR3 667MT/s                 | 1         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s  | 1         | 0.46%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 512MB DIMM DDR2 533MT/s | 1         | 0.46%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.46%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.46%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 1         | 0.46%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.46%   |
| SK Hynix RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.46%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 0.46%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 0.46%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                   | 1         | 0.46%   |
| SK Hynix RAM Module 1GB DIMM DDR2 533MT/s                       | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 67        | 42.14%  |
| DDR3    | 56        | 35.22%  |
| Unknown | 13        | 8.18%   |
| SDRAM   | 9         | 5.66%   |
| DDR2    | 9         | 5.66%   |
| DDR     | 3         | 1.89%   |
| LPDDR4  | 2         | 1.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 92        | 61.33%  |
| DIMM   | 58        | 38.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 52        | 29.55%  |
| 4096  | 50        | 28.41%  |
| 2048  | 36        | 20.45%  |
| 16384 | 26        | 14.77%  |
| 1024  | 9         | 5.11%   |
| 512   | 3         | 1.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 45        | 25.28%  |
| 1600    | 40        | 22.47%  |
| 2400    | 13        | 7.3%    |
| 1333    | 12        | 6.74%   |
| 3200    | 10        | 5.62%   |
| 667     | 9         | 5.06%   |
| 800     | 8         | 4.49%   |
| 1334    | 7         | 3.93%   |
| 400     | 7         | 3.93%   |
| 2133    | 5         | 2.81%   |
| Unknown | 4         | 2.25%   |
| 1066    | 3         | 1.69%   |
| 3467    | 2         | 1.12%   |
| 1866    | 2         | 1.12%   |
| 533     | 2         | 1.12%   |
| 49926   | 1         | 0.56%   |
| 4199    | 1         | 0.56%   |
| 3600    | 1         | 0.56%   |
| 3000    | 1         | 0.56%   |
| 2666    | 1         | 0.56%   |
| 2048    | 1         | 0.56%   |
| 2000    | 1         | 0.56%   |
| 1867    | 1         | 0.56%   |
| 1800    | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 75%     |
| Seiko Epson     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson Printer | 1         | 25%     |
| HP LaserJet P3005   | 1         | 25%     |
| HP LaserJet 1018    | 1         | 25%     |
| HP Deskjet 1510     | 1         | 25%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 48        | 23.3%   |
| Microdia                               | 26        | 12.62%  |
| Realtek Semiconductor                  | 24        | 11.65%  |
| Cheng Uei Precision Industry (Foxlink) | 23        | 11.17%  |
| Acer                                   | 16        | 7.77%   |
| Sunplus Innovation Technology          | 14        | 6.8%    |
| IMC Networks                           | 12        | 5.83%   |
| Lite-On Technology                     | 8         | 3.88%   |
| Suyin                                  | 6         | 2.91%   |
| Quanta                                 | 6         | 2.91%   |
| Silicon Motion                         | 3         | 1.46%   |
| Samsung Electronics                    | 3         | 1.46%   |
| Apple                                  | 3         | 1.46%   |
| Syntek                                 | 2         | 0.97%   |
| Logitech                               | 2         | 0.97%   |
| Cubeternet                             | 2         | 0.97%   |
| Z-Star Microelectronics                | 1         | 0.49%   |
| Sonix Technology                       | 1         | 0.49%   |
| OmniVision Technologies                | 1         | 0.49%   |
| MacroSilicon                           | 1         | 0.49%   |
| Lenovo                                 | 1         | 0.49%   |
| Intel                                  | 1         | 0.49%   |
| eMPIA Technology                       | 1         | 0.49%   |
| ALi                                    | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 14        | 6.76%   |
| Microdia Integrated_Webcam_HD                                              | 13        | 6.28%   |
| Chicony EasyCamera                                                         | 8         | 3.86%   |
| Chicony Integrated Camera                                                  | 7         | 3.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3.38%   |
| Acer Lenovo EasyCamera                                                     | 6         | 2.9%    |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 2.42%   |
| IMC Networks Integrated Camera                                             | 5         | 2.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 4         | 1.93%   |
| Acer HP TrueVision HD Webcam                                               | 4         | 1.93%   |
| Samsung Galaxy A5 (MTP)                                                    | 3         | 1.45%   |
| Realtek Integrated Webcam                                                  | 3         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 1.45%   |
| Lite-On HP HD Camera                                                       | 3         | 1.45%   |
| Chicony HP Truevision HD camera                                            | 3         | 1.45%   |
| Chicony HP HD Webcam                                                       | 3         | 1.45%   |
| Chicony HP HD Camera                                                       | 3         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 3         | 1.45%   |
| Suyin HP Truevision HD                                                     | 2         | 0.97%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.97%   |
| Sunplus Dell HD Webcam                                                     | 2         | 0.97%   |
| Realtek Integrated Webcam HD                                               | 2         | 0.97%   |
| Quanta HP Webcam                                                           | 2         | 0.97%   |
| Microdia Laptop_Integrated_Webcam_1.3M                                     | 2         | 0.97%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 0.97%   |
| Microdia 1.3 MPixel Integrated Webcam                                      | 2         | 0.97%   |
| Logitech Webcam C270                                                       | 2         | 0.97%   |
| Lite-On Integrated Camera                                                  | 2         | 0.97%   |
| Lite-On HP HD Webcam                                                       | 2         | 0.97%   |
| Chicony HP Integrated Webcam                                               | 2         | 0.97%   |
| Chicony HD WebCam                                                          | 2         | 0.97%   |
| Chicony Front Camera                                                       | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 0.97%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 0.97%   |
| Acer EasyCamera                                                            | 2         | 0.97%   |
| Z-Star Vimicro USB Camera (Altair)                                         | 1         | 0.48%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.48%   |
| Syntek Integrated Camera                                                   | 1         | 0.48%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.48%   |
| Suyin HP Webcam-50                                                         | 1         | 0.48%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.48%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.48%   |
| Sunplus Lenovo EasyCamera                                                  | 1         | 0.48%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.48%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.48%   |
| Sunplus HP Universal Camera                                                | 1         | 0.48%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 0.48%   |
| Sonix HP Webcam-101                                                        | 1         | 0.48%   |
| Silicon Motion WebCam SC-03M12736N                                         | 1         | 0.48%   |
| Silicon Motion Lenovo EasyCamera                                           | 1         | 0.48%   |
| Silicon Motion HP Webcam-101                                               | 1         | 0.48%   |
| Realtek USB Camera                                                         | 1         | 0.48%   |
| Realtek Rear Camera                                                        | 1         | 0.48%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 0.48%   |
| Realtek EasyCamera                                                         | 1         | 0.48%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 0.48%   |
| Quanta VGA WebCam                                                          | 1         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 51.16%  |
| Synaptics                  | 11        | 25.58%  |
| Shenzhen Goodix Technology | 6         | 13.95%  |
| Upek                       | 3         | 6.98%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 23.26%  |
| Validity Sensors Fingerprint scanner                                       | 5         | 11.63%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 11.63%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.98%   |
| Synaptics  WBDI                                                            | 3         | 6.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6.98%   |
| Validity Sensors VFS491                                                    | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.33%   |
| Unknown                                                                    | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Broadcom        | 6         | 50%     |
| Alcor Micro     | 3         | 25%     |
| O2 Micro        | 1         | 8.33%   |
| Lenovo          | 1         | 8.33%   |
| Hewlett-Packard | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 16.67%  |
| Broadcom 5880                                                                | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 224       | 67.88%  |
| 1     | 90        | 27.27%  |
| 2     | 14        | 4.24%   |
| 5     | 1         | 0.3%    |
| 4     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 42        | 35%     |
| Graphics card            | 32        | 26.67%  |
| Net/wireless             | 17        | 14.17%  |
| Chipcard                 | 11        | 9.17%   |
| Bluetooth                | 5         | 4.17%   |
| Multimedia controller    | 4         | 3.33%   |
| Unassigned class         | 2         | 1.67%   |
| Storage/ide              | 1         | 0.83%   |
| Sound                    | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |
| Modem                    | 1         | 0.83%   |
| Communication controller | 1         | 0.83%   |
| Card reader              | 1         | 0.83%   |
| Camera                   | 1         | 0.83%   |

