ArcoLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

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

Total: 868

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| System76      | Oryx Pro                    | [b55d1a9fe5](https://linux-hardware.org/?probe=b55d1a9fe5) | Jul 25, 2022 |
| System76      | Oryx Pro                    | [3b91037c6f](https://linux-hardware.org/?probe=3b91037c6f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| Dell          | Inspiron 14 5401            | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| HP            | Unknown                     | [01622a24ef](https://linux-hardware.org/?probe=01622a24ef) | Jul 17, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [3cc4a578df](https://linux-hardware.org/?probe=3cc4a578df) | Jul 17, 2022 |
| HP            | Notebook                    | [e5a1df8ba8](https://linux-hardware.org/?probe=e5a1df8ba8) | Jul 17, 2022 |
| System76      | Oryx Pro                    | [5cac9c78e6](https://linux-hardware.org/?probe=5cac9c78e6) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [383c62eca2](https://linux-hardware.org/?probe=383c62eca2) | Jul 14, 2022 |
| System76      | Oryx Pro                    | [7cb7b3fd6a](https://linux-hardware.org/?probe=7cb7b3fd6a) | Jul 14, 2022 |
| Dell          | XPS 17 9710                 | [2438f42e95](https://linux-hardware.org/?probe=2438f42e95) | Jul 13, 2022 |
| Dell          | Vostro 15 3510              | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| Dell          | Inspiron N5050              | [8002a8ec0f](https://linux-hardware.org/?probe=8002a8ec0f) | Jul 10, 2022 |
| HP            | Laptop 15-da1xxx            | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [019c2b1194](https://linux-hardware.org/?probe=019c2b1194) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | [1f47ada680](https://linux-hardware.org/?probe=1f47ada680) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [8476e2e1c3](https://linux-hardware.org/?probe=8476e2e1c3) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | [add34d1f6a](https://linux-hardware.org/?probe=add34d1f6a) | Jul 05, 2022 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [1773a0941f](https://linux-hardware.org/?probe=1773a0941f) | Jul 05, 2022 |
| Acer          | Aspire E5-576G              | [74f6e010da](https://linux-hardware.org/?probe=74f6e010da) | Jul 04, 2022 |
| MSI           | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| System76      | Oryx Pro                    | [7fa7a1ca82](https://linux-hardware.org/?probe=7fa7a1ca82) | Jun 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Toshiba       | Satellite Pro S300          | [09f9ef25cd](https://linux-hardware.org/?probe=09f9ef25cd) | Jun 27, 2022 |
| HP            | EliteBook 840 G3            | [0d16a3f2ce](https://linux-hardware.org/?probe=0d16a3f2ce) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| ASUSTek       | All Series                  | [19dde83002](https://linux-hardware.org/?probe=19dde83002) | Jun 26, 2022 |
| Acer          | Aspire E1-572G              | [c2fceb2c81](https://linux-hardware.org/?probe=c2fceb2c81) | Jun 24, 2022 |
| Dell          | Inspiron 5459               | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| Acer          | Aspire ES1-571              | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| System76      | Oryx Pro                    | [c623d50d29](https://linux-hardware.org/?probe=c623d50d29) | Jun 20, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [bf292ae80a](https://linux-hardware.org/?probe=bf292ae80a) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1cf9eae6e5](https://linux-hardware.org/?probe=1cf9eae6e5) | Jun 20, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [07821abe14](https://linux-hardware.org/?probe=07821abe14) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Notebook      | PA70ES                      | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| System76      | Oryx Pro                    | [8488dcacf9](https://linux-hardware.org/?probe=8488dcacf9) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [5d49ce7763](https://linux-hardware.org/?probe=5d49ce7763) | Jun 10, 2022 |
| Razer         | Blade                       | [2d8524dc81](https://linux-hardware.org/?probe=2d8524dc81) | Jun 10, 2022 |
| HP            | Laptop 14-dk1xxx            | [f895a113f9](https://linux-hardware.org/?probe=f895a113f9) | Jun 09, 2022 |
| HP            | Laptop 14-dk1xxx            | [e29eb57530](https://linux-hardware.org/?probe=e29eb57530) | Jun 09, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | [0b67cbecfc](https://linux-hardware.org/?probe=0b67cbecfc) | Jun 07, 2022 |
| HP            | Laptop 15-da1xxx            | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| ASUSTek       | GL703VD                     | [3a9d836e5e](https://linux-hardware.org/?probe=3a9d836e5e) | Jun 03, 2022 |
| ASUSTek       | GL703VD                     | [531d7297d9](https://linux-hardware.org/?probe=531d7297d9) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| System76      | Oryx Pro                    | [5f84134f5d](https://linux-hardware.org/?probe=5f84134f5d) | May 29, 2022 |
| Toshiba       | Satellite C675              | [72daf96a34](https://linux-hardware.org/?probe=72daf96a34) | May 28, 2022 |
| Unknown       | Unknown                     | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| System76      | Oryx Pro                    | [2652ac64a4](https://linux-hardware.org/?probe=2652ac64a4) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AV0031GE    | [13f326fc7d](https://linux-hardware.org/?probe=13f326fc7d) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| Toshiba       | PORTEGE R30-A               | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| MSI           | GF75 Thin 9SC               | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| LG Electro... | C500                        | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| HP            | Pavilion Notebook           | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Sony          | SVE1712C1EW                 | [9410df7433](https://linux-hardware.org/?probe=9410df7433) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [75ec4a948b](https://linux-hardware.org/?probe=75ec4a948b) | May 18, 2022 |
| Lenovo        | ThinkPad T400 276521G       | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| HP            | Folio 13                    | [9c9cd2aa91](https://linux-hardware.org/?probe=9c9cd2aa91) | May 15, 2022 |
| System76      | Oryx Pro                    | [d740686b5e](https://linux-hardware.org/?probe=d740686b5e) | May 14, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3780dc0fe5](https://linux-hardware.org/?probe=3780dc0fe5) | May 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [09d0c5a57c](https://linux-hardware.org/?probe=09d0c5a57c) | May 10, 2022 |
| Samsung       | 550XDA                      | [d3d7a64817](https://linux-hardware.org/?probe=d3d7a64817) | May 08, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| HP            | 250 G5 Notebook PC          | [a21e01fec5](https://linux-hardware.org/?probe=a21e01fec5) | May 07, 2022 |
| HP            | Laptop 17-cn0xxx            | [eab46c9089](https://linux-hardware.org/?probe=eab46c9089) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| ASUSTek       | G752VT                      | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | Latitude E6230              | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| Dell          | Latitude E6230              | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| Dell          | Latitude E6430              | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Dell          | Latitude 5421               | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| System76      | Oryx Pro                    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| System76      | Oryx Pro                    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| Apple         | MacBookPro11,2              | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| ASUSTek       | K53E                        | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | 255 G7 Notebook PC          | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| HP            | 255 G7 Notebook PC          | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| HP            | 255 G7 Notebook PC          | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Dell          | Precision 5550              | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Notebook      | PA70ES                      | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Dell          | XPS 17 9710                 | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| Acer          | Extensa 5620                | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| Monster       | ABRA A5 V11.1               | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Dell          | XPS 17 9710                 | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Monster       | ABRA A5 V11.1               | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Dell          | Latitude 3410               | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Acer          | Aspire F5-573G              | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [b7b09dcc5e](https://linux-hardware.org/?probe=b7b09dcc5e) | Dec 15, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Precision M4800             | [90109636fe](https://linux-hardware.org/?probe=90109636fe) | Dec 15, 2021 |
| Dell          | Precision M4800             | [0d1cfc9a0e](https://linux-hardware.org/?probe=0d1cfc9a0e) | Dec 15, 2021 |
| Notebook      | NH5xAx                      | [62f88112f1](https://linux-hardware.org/?probe=62f88112f1) | Dec 14, 2021 |
| Alienware     | 15 R3                       | [6394aa965a](https://linux-hardware.org/?probe=6394aa965a) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5faef7686a](https://linux-hardware.org/?probe=5faef7686a) | Dec 14, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| Acer          | Extensa 5635ZG              | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [91eeb42bcb](https://linux-hardware.org/?probe=91eeb42bcb) | Dec 13, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | Precision 5550              | [9e88f6034f](https://linux-hardware.org/?probe=9e88f6034f) | Dec 12, 2021 |
| System76      | Galago Pro                  | [9fe1e9175f](https://linux-hardware.org/?probe=9fe1e9175f) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | [64958365b3](https://linux-hardware.org/?probe=64958365b3) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| System76      | Darter Pro                  | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| Dell          | Inspiron 5468               | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [cf8576527d](https://linux-hardware.org/?probe=cf8576527d) | Dec 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| HP            | ENVY Notebook               | [179bd0eae8](https://linux-hardware.org/?probe=179bd0eae8) | Dec 05, 2021 |
| HP            | ENVY Notebook               | [58488b0351](https://linux-hardware.org/?probe=58488b0351) | Dec 05, 2021 |
| Razer         | Blade Stealth               | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| HP            | Notebook                    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| Apple         | MacBookPro11,2              | [681845a2e3](https://linux-hardware.org/?probe=681845a2e3) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [b022b376ee](https://linux-hardware.org/?probe=b022b376ee) | Nov 28, 2021 |
| Dell          | Inspiron 3505               | [d3cfe93dc6](https://linux-hardware.org/?probe=d3cfe93dc6) | Nov 28, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | V14-ADA 82C6                | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| ASUSTek       | X556UQK                     | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| HP            | Laptop 15-bw0xx             | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| Dell          | Latitude E5450              | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| HP            | EliteBook 840 G1            | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| HUAWEI        | WRT-WX9                     | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| Dell          | Inspiron 5579               | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| Apple         | MacBook5,1                  | [6ddb5fdd76](https://linux-hardware.org/?probe=6ddb5fdd76) | Nov 12, 2021 |
| HUAWEI        | KPL-W0X                     | [bffba05735](https://linux-hardware.org/?probe=bffba05735) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HUAWEI        | KPL-W0X                     | [4a189c2903](https://linux-hardware.org/?probe=4a189c2903) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Latitude E6440              | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| HP            | 630                         | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Razer         | Blade                       | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| Dell          | Latitude E6540              | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| ASUSTek       | X555LD                      | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Acer          | Aspire E5-523               | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | Latitude E7440              | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| Acer          | Aspire SW5-173              | [38872d1422](https://linux-hardware.org/?probe=38872d1422) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| ASUSTek       | N53Jq                       | [3cd3bb5eae](https://linux-hardware.org/?probe=3cd3bb5eae) | Oct 16, 2021 |
| Dell          | Inspiron 3520               | [56fe4ab8a1](https://linux-hardware.org/?probe=56fe4ab8a1) | Oct 16, 2021 |
| Acer          | Nitro AN515-55              | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8fbafb0d7e](https://linux-hardware.org/?probe=8fbafb0d7e) | Oct 16, 2021 |
| System76      | Pangolin                    | [e4fb2b6b8a](https://linux-hardware.org/?probe=e4fb2b6b8a) | Oct 16, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [eed2a8b965](https://linux-hardware.org/?probe=eed2a8b965) | Oct 15, 2021 |
| Lenovo        | G50-30 80G0                 | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| Razer         | Blade Stealth               | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| MSI           | GS66 Stealth 10SFS          | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| HP            | Pavilion dv6                | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Monster       | ABRA A5 V11.1               | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Chuwi         | GemiBook Pro                | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | UX303LN                     | [9c8bb62a98](https://linux-hardware.org/?probe=9c8bb62a98) | Sep 17, 2021 |
| MSI           | GP76 Leopard 10UE           | [547ee4e1ea](https://linux-hardware.org/?probe=547ee4e1ea) | Sep 16, 2021 |
| MSI           | GP76 Leopard 10UE           | [90168ebbeb](https://linux-hardware.org/?probe=90168ebbeb) | Sep 16, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Fujitsu       | LIFEBOOK A357               | [efc14ead6c](https://linux-hardware.org/?probe=efc14ead6c) | Sep 13, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [a19eee5494](https://linux-hardware.org/?probe=a19eee5494) | Sep 11, 2021 |
| Fujitsu       | LIFEBOOK A357               | [6a38389900](https://linux-hardware.org/?probe=6a38389900) | Sep 11, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| HP            | ZBook Studio G3             | [d239ae254a](https://linux-hardware.org/?probe=d239ae254a) | Sep 09, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Lenovo        | ThinkPad T450s 20BWS04K0... | [3c7ed2f9b7](https://linux-hardware.org/?probe=3c7ed2f9b7) | Sep 06, 2021 |
| Acer          | Aspire 7750G                | [2b645d2c16](https://linux-hardware.org/?probe=2b645d2c16) | Sep 05, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| Acer          | Swift SF114-32              | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| Dell          | XPS 15 9560                 | [4b8701a2b3](https://linux-hardware.org/?probe=4b8701a2b3) | Sep 05, 2021 |
| Dell          | Inspiron 5570               | [ffa40a366f](https://linux-hardware.org/?probe=ffa40a366f) | Sep 05, 2021 |
| HP            | Laptop 15q-bu0xx            | [bc433a2411](https://linux-hardware.org/?probe=bc433a2411) | Sep 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0LA00    | [d5b967eeee](https://linux-hardware.org/?probe=d5b967eeee) | Sep 04, 2021 |
| Dell          | Latitude E6420              | [0d79becf85](https://linux-hardware.org/?probe=0d79becf85) | Sep 03, 2021 |
| Dell          | XPS 13 9300                 | [9b10289848](https://linux-hardware.org/?probe=9b10289848) | Sep 02, 2021 |
| ASUSTek       | X555QG                      | [14d10602c8](https://linux-hardware.org/?probe=14d10602c8) | Sep 02, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [1fd99ca58d](https://linux-hardware.org/?probe=1fd99ca58d) | Sep 02, 2021 |
| Acer          | Aspire 5750                 | [c3ae9f4793](https://linux-hardware.org/?probe=c3ae9f4793) | Sep 01, 2021 |
| Acer          | Nitro AN517-52              | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| ASUSTek       | G750JX                      | [53da9f0547](https://linux-hardware.org/?probe=53da9f0547) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| HP            | ENVY Laptop 17-cg0xxx       | [14f5f8a179](https://linux-hardware.org/?probe=14f5f8a179) | Aug 28, 2021 |
| Dell          | Inspiron 15-5568            | [81b3e142a3](https://linux-hardware.org/?probe=81b3e142a3) | Aug 28, 2021 |
| Dell          | Inspiron 5579               | [11d1c6d073](https://linux-hardware.org/?probe=11d1c6d073) | Aug 28, 2021 |
| Apple         | MacBookPro11,1              | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| Eluktronic... | MAG-15 2070                 | [28b869ed18](https://linux-hardware.org/?probe=28b869ed18) | Aug 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f6fa665265](https://linux-hardware.org/?probe=f6fa665265) | Aug 27, 2021 |
| Dell          | XPS 15 9500                 | [62f508237e](https://linux-hardware.org/?probe=62f508237e) | Aug 25, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6ab2831848](https://linux-hardware.org/?probe=6ab2831848) | Aug 25, 2021 |
| HP            | Laptop 15-bw0xx             | [e6c79ed475](https://linux-hardware.org/?probe=e6c79ed475) | Aug 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0016FR     | [94091b0705](https://linux-hardware.org/?probe=94091b0705) | Aug 24, 2021 |
| System76      | Gazelle                     | [b1f5d2f5db](https://linux-hardware.org/?probe=b1f5d2f5db) | Aug 24, 2021 |
| System76      | Gazelle                     | [be7855ec0c](https://linux-hardware.org/?probe=be7855ec0c) | Aug 24, 2021 |
| Fujitsu       | LIFEBOOK E756               | [ad2bc5b140](https://linux-hardware.org/?probe=ad2bc5b140) | Aug 23, 2021 |
| HP            | Laptop 15-da0xxx            | [2aafbc0a72](https://linux-hardware.org/?probe=2aafbc0a72) | Aug 23, 2021 |
| Dell          | Inspiron 5579               | [4e844d3321](https://linux-hardware.org/?probe=4e844d3321) | Aug 22, 2021 |
| HP            | Laptop 15-db0xxx            | [83c1674e38](https://linux-hardware.org/?probe=83c1674e38) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | [6dbfd72cd8](https://linux-hardware.org/?probe=6dbfd72cd8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [24bbd4d06f](https://linux-hardware.org/?probe=24bbd4d06f) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e7fd668005](https://linux-hardware.org/?probe=e7fd668005) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| Dell          | Inspiron 15-5568            | [7fec9a3a5b](https://linux-hardware.org/?probe=7fec9a3a5b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T440 20B70048US    | [14e8d60953](https://linux-hardware.org/?probe=14e8d60953) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| ASUSTek       | X556UA                      | [04710b290b](https://linux-hardware.org/?probe=04710b290b) | Aug 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| ASUSTek       | X580VD                      | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e42d32bf2a](https://linux-hardware.org/?probe=e42d32bf2a) | Aug 12, 2021 |
| Acer          | Aspire 7741                 | [9d26562113](https://linux-hardware.org/?probe=9d26562113) | Aug 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| HP            | Laptop 15q-bu1xx            | [5aced87a3f](https://linux-hardware.org/?probe=5aced87a3f) | Aug 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [e9d2ccb049](https://linux-hardware.org/?probe=e9d2ccb049) | Aug 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [5f24fa8f98](https://linux-hardware.org/?probe=5f24fa8f98) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [51115b9f9f](https://linux-hardware.org/?probe=51115b9f9f) | Aug 08, 2021 |
| Lenovo        | ThinkPad W541 20EF0000US    | [6150ef8ebc](https://linux-hardware.org/?probe=6150ef8ebc) | Aug 07, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| Acer          | Nitro AN515-53              | [baf0ccecb1](https://linux-hardware.org/?probe=baf0ccecb1) | Aug 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [c434457251](https://linux-hardware.org/?probe=c434457251) | Aug 03, 2021 |
| AZW           | SEi                         | [de596531ae](https://linux-hardware.org/?probe=de596531ae) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [2b732e43eb](https://linux-hardware.org/?probe=2b732e43eb) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [68b431bc45](https://linux-hardware.org/?probe=68b431bc45) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [a8e52318c8](https://linux-hardware.org/?probe=a8e52318c8) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [949e4af6a7](https://linux-hardware.org/?probe=949e4af6a7) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [65d9b956bc](https://linux-hardware.org/?probe=65d9b956bc) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e84e4c3d4c](https://linux-hardware.org/?probe=e84e4c3d4c) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Dell          | Precision 7520              | [bb1844c704](https://linux-hardware.org/?probe=bb1844c704) | Jul 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| Dell          | Latitude 5410               | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| HP            | Stream Notebook PC 13       | [6631c46029](https://linux-hardware.org/?probe=6631c46029) | Jul 22, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| HP            | Laptop 15-da0xxx            | [4cb2daf424](https://linux-hardware.org/?probe=4cb2daf424) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [be2edf1657](https://linux-hardware.org/?probe=be2edf1657) | Jul 14, 2021 |
| Acer          | Aspire E5-575G              | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | Notebook                    | [021a011da8](https://linux-hardware.org/?probe=021a011da8) | Jul 13, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [9779eaca87](https://linux-hardware.org/?probe=9779eaca87) | Jul 11, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [329bbc8c40](https://linux-hardware.org/?probe=329bbc8c40) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [2114ad4f9e](https://linux-hardware.org/?probe=2114ad4f9e) | Jul 10, 2021 |
| MSI           | GP63 Leopard 8RE            | [a469d525e3](https://linux-hardware.org/?probe=a469d525e3) | Jul 10, 2021 |
| Fujitsu       | LIFEBOOK S751               | [fc7d66f096](https://linux-hardware.org/?probe=fc7d66f096) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [252e038506](https://linux-hardware.org/?probe=252e038506) | Jul 08, 2021 |
| Dell          | XPS 13 9360                 | [bb7d68bae6](https://linux-hardware.org/?probe=bb7d68bae6) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4ed05b4d7b](https://linux-hardware.org/?probe=4ed05b4d7b) | Jul 07, 2021 |
| Acer          | Aspire E5-573G              | [f1f413aced](https://linux-hardware.org/?probe=f1f413aced) | Jul 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6f489566ae](https://linux-hardware.org/?probe=6f489566ae) | Jul 06, 2021 |
| Fujitsu       | LIFEBOOK T902               | [4fb535811d](https://linux-hardware.org/?probe=4fb535811d) | Jul 05, 2021 |
| ASUSTek       | Q550LF                      | [3aafd6f8a6](https://linux-hardware.org/?probe=3aafd6f8a6) | Jul 05, 2021 |
| Dell          | Latitude 7480               | [827e1b8a21](https://linux-hardware.org/?probe=827e1b8a21) | Jul 04, 2021 |
| Fujitsu       | LIFEBOOK T902               | [7e6ee2f561](https://linux-hardware.org/?probe=7e6ee2f561) | Jul 04, 2021 |
| ASUSTek       | X510UNR                     | [3c8630ec48](https://linux-hardware.org/?probe=3c8630ec48) | Jul 04, 2021 |
| Notebook      | P95_HP                      | [8aa8037e16](https://linux-hardware.org/?probe=8aa8037e16) | Jul 03, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [e08d79f016](https://linux-hardware.org/?probe=e08d79f016) | Jul 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWX5140... | [06e8c86830](https://linux-hardware.org/?probe=06e8c86830) | Jul 02, 2021 |
| HP            | 250 G1                      | [bc56e9fe6f](https://linux-hardware.org/?probe=bc56e9fe6f) | Jul 02, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c0ed3a3c09](https://linux-hardware.org/?probe=c0ed3a3c09) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | [ea85c0f143](https://linux-hardware.org/?probe=ea85c0f143) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Apple         | MacBookPro12,1              | [0a8dac703d](https://linux-hardware.org/?probe=0a8dac703d) | Jun 29, 2021 |
| Apple         | MacBookPro8,1               | [aac1bf4737](https://linux-hardware.org/?probe=aac1bf4737) | Jun 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [127874b25b](https://linux-hardware.org/?probe=127874b25b) | Jun 28, 2021 |
| ASUSTek       | K53E                        | [3ad8363a7d](https://linux-hardware.org/?probe=3ad8363a7d) | Jun 28, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [ceab39c39a](https://linux-hardware.org/?probe=ceab39c39a) | Jun 28, 2021 |
| Acer          | Predator G3-572             | [982137c856](https://linux-hardware.org/?probe=982137c856) | Jun 28, 2021 |
| Lenovo        | ThinkPad X240 20AM001RGE    | [5e80a2492e](https://linux-hardware.org/?probe=5e80a2492e) | Jun 28, 2021 |
| Apple         | MacBookPro11,5              | [29dedcc0c7](https://linux-hardware.org/?probe=29dedcc0c7) | Jun 28, 2021 |
| AZW           | GT-R                        | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | [5fd8e985e9](https://linux-hardware.org/?probe=5fd8e985e9) | Jun 28, 2021 |
| Dell          | XPS 17 9700                 | [cbf1953567](https://linux-hardware.org/?probe=cbf1953567) | Jun 27, 2021 |
| Alienware     | m15 Ryzen Ed. R5            | [d48faf5072](https://linux-hardware.org/?probe=d48faf5072) | Jun 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Toshiba       | Satellite C600              | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| MSI           | Modern 14 A10M              | [a07552d987](https://linux-hardware.org/?probe=a07552d987) | Jun 24, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| HP            | EliteBook 840 G4            | [1155abf435](https://linux-hardware.org/?probe=1155abf435) | Jun 22, 2021 |
| HUAWEI        | MACH-WX9                    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Dell          | Inspiron 13-5378            | [5246eabc5f](https://linux-hardware.org/?probe=5246eabc5f) | Jun 17, 2021 |
| Dell          | Inspiron 3593               | [ba202e6f1e](https://linux-hardware.org/?probe=ba202e6f1e) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [22aabc71ef](https://linux-hardware.org/?probe=22aabc71ef) | Jun 17, 2021 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [99a0a332ec](https://linux-hardware.org/?probe=99a0a332ec) | Jun 17, 2021 |
| HP            | Pavilion Notebook           | [b81aa5226f](https://linux-hardware.org/?probe=b81aa5226f) | Jun 17, 2021 |
| Alienware     | 17                          | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ac8e80e0cc](https://linux-hardware.org/?probe=ac8e80e0cc) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | [a6cf581d50](https://linux-hardware.org/?probe=a6cf581d50) | Jun 14, 2021 |
| Apple         | MacBookAir1,1               | [48c28ecda7](https://linux-hardware.org/?probe=48c28ecda7) | Jun 14, 2021 |
| Dell          | Inspiron 5485 2n1           | [cda45b1f3c](https://linux-hardware.org/?probe=cda45b1f3c) | Jun 14, 2021 |
| Dell          | Latitude E6440              | [908df2d475](https://linux-hardware.org/?probe=908df2d475) | Jun 13, 2021 |
| Medion        | Erazer X7841 MD99556        | [a15e0c5ae0](https://linux-hardware.org/?probe=a15e0c5ae0) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | [f6b6b11c24](https://linux-hardware.org/?probe=f6b6b11c24) | Jun 12, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Fujitsu       | LIFEBOOK S751               | [20ff390b75](https://linux-hardware.org/?probe=20ff390b75) | Jun 11, 2021 |
| Acer          | Aspire A715-71G             | [64db1224d0](https://linux-hardware.org/?probe=64db1224d0) | Jun 10, 2021 |
| HP            | Laptop 15q-bu0xx            | [758cd92d87](https://linux-hardware.org/?probe=758cd92d87) | Jun 10, 2021 |
| Razer         | Blade                       | [e6ee630e9b](https://linux-hardware.org/?probe=e6ee630e9b) | Jun 06, 2021 |
| Apple         | MacBookPro11,1              | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| Lenovo        | ThinkPad X220 4290LD4       | [22bbadb3dd](https://linux-hardware.org/?probe=22bbadb3dd) | Jun 03, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [fa237f560a](https://linux-hardware.org/?probe=fa237f560a) | Jun 02, 2021 |
| Lenovo        | ThinkPad X230 2306CTO       | [4d799b19db](https://linux-hardware.org/?probe=4d799b19db) | Jun 02, 2021 |
| Toshiba       | Satellite L635              | [c5883a9da8](https://linux-hardware.org/?probe=c5883a9da8) | Jun 01, 2021 |
| Toshiba       | Satellite L635              | [634bc5add8](https://linux-hardware.org/?probe=634bc5add8) | May 30, 2021 |
| System76      | Oryx Pro                    | [e18b16565f](https://linux-hardware.org/?probe=e18b16565f) | May 29, 2021 |
| Toshiba       | Satellite R630              | [0c557895be](https://linux-hardware.org/?probe=0c557895be) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [302b62a5c7](https://linux-hardware.org/?probe=302b62a5c7) | May 20, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [0d44d30be1](https://linux-hardware.org/?probe=0d44d30be1) | May 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [00aa4c11f4](https://linux-hardware.org/?probe=00aa4c11f4) | May 13, 2021 |
| Sony          | SVE14125CXP                 | [23d5e048cb](https://linux-hardware.org/?probe=23d5e048cb) | May 13, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| Toshiba       | Satellite L50-A-19N         | [988020930b](https://linux-hardware.org/?probe=988020930b) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| HP            | Pavilion Notebook           | [da82b1b43f](https://linux-hardware.org/?probe=da82b1b43f) | May 09, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [ab871dcbe2](https://linux-hardware.org/?probe=ab871dcbe2) | May 01, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [f8bbdfd850](https://linux-hardware.org/?probe=f8bbdfd850) | Apr 30, 2021 |
| Lenovo        | ThinkPad Helix 36986RU      | [2df93a93d1](https://linux-hardware.org/?probe=2df93a93d1) | Apr 30, 2021 |
| HP            | 250 G1                      | [0810673d99](https://linux-hardware.org/?probe=0810673d99) | Apr 29, 2021 |
| Dell          | Latitude E6440              | [535815022c](https://linux-hardware.org/?probe=535815022c) | Apr 23, 2021 |
| HP            | 255 G2                      | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [f707b24713](https://linux-hardware.org/?probe=f707b24713) | Apr 22, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [16ab380d72](https://linux-hardware.org/?probe=16ab380d72) | Apr 21, 2021 |
| Dell          | Vostro 3550                 | [2b122eb7e6](https://linux-hardware.org/?probe=2b122eb7e6) | Apr 21, 2021 |
| ASUSTek       | UX430UAR                    | [a071188f1c](https://linux-hardware.org/?probe=a071188f1c) | Apr 21, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| HP            | EliteBook 8460p             | [dc1e0bf320](https://linux-hardware.org/?probe=dc1e0bf320) | Apr 19, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [eeee3c8078](https://linux-hardware.org/?probe=eeee3c8078) | Apr 18, 2021 |
| HP            | 255 G7 Notebook PC          | [ba1e3ed32e](https://linux-hardware.org/?probe=ba1e3ed32e) | Apr 15, 2021 |
| Dell          | XPS 15 9570                 | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Lenovo        | G50-45 80E3                 | [7633456df0](https://linux-hardware.org/?probe=7633456df0) | Apr 15, 2021 |
| ASUSTek       | N550JV                      | [61b2baa2d1](https://linux-hardware.org/?probe=61b2baa2d1) | Apr 13, 2021 |
| Chuwi         | GemiBook Pro                | [9909625298](https://linux-hardware.org/?probe=9909625298) | Apr 12, 2021 |
| Acer          | Predator PH315-52           | [97c81f4b56](https://linux-hardware.org/?probe=97c81f4b56) | Apr 11, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| Toshiba       | PORTEGE Z30t-C              | [39dd5ca43b](https://linux-hardware.org/?probe=39dd5ca43b) | Apr 11, 2021 |
| Dell          | XPS 13 9380                 | [8ceda587e7](https://linux-hardware.org/?probe=8ceda587e7) | Apr 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [337a0c3723](https://linux-hardware.org/?probe=337a0c3723) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| HP            | EliteBook 840 G3            | [5a663fff6e](https://linux-hardware.org/?probe=5a663fff6e) | Apr 05, 2021 |
| Lenovo        | ThinkPad X220 4291WF5       | [7cf8cfd8f8](https://linux-hardware.org/?probe=7cf8cfd8f8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T480 20L6S27S0P    | [6fc0f5a4b6](https://linux-hardware.org/?probe=6fc0f5a4b6) | Apr 03, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [53fe8e1c6c](https://linux-hardware.org/?probe=53fe8e1c6c) | Mar 31, 2021 |
| Dell          | Latitude E7440              | [e0c5eda63a](https://linux-hardware.org/?probe=e0c5eda63a) | Mar 31, 2021 |
| Dell          | Inspiron 5520               | [151b34a749](https://linux-hardware.org/?probe=151b34a749) | Mar 29, 2021 |
| Dell          | Latitude E7440              | [1c004faf2a](https://linux-hardware.org/?probe=1c004faf2a) | Mar 28, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LR... | [440edfbe7e](https://linux-hardware.org/?probe=440edfbe7e) | Mar 26, 2021 |
| Dell          | Latitude 3580               | [0de8d9cd4c](https://linux-hardware.org/?probe=0de8d9cd4c) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad 11e 20D90020US     | [e5948a4e4c](https://linux-hardware.org/?probe=e5948a4e4c) | Mar 24, 2021 |
| Dell          | Inspiron 5593               | [0348f8af6b](https://linux-hardware.org/?probe=0348f8af6b) | Mar 23, 2021 |
| Dell          | Latitude E4310              | [16025a8970](https://linux-hardware.org/?probe=16025a8970) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Dell          | Inspiron 5575               | [4b72276133](https://linux-hardware.org/?probe=4b72276133) | Mar 17, 2021 |
| Dell          | Latitude E6440              | [8eb5c8aaa9](https://linux-hardware.org/?probe=8eb5c8aaa9) | Mar 17, 2021 |
| Dell          | Inspiron 5555               | [4b3ec85962](https://linux-hardware.org/?probe=4b3ec85962) | Mar 16, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| HP            | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2347GU8       | [1c74d63cc4](https://linux-hardware.org/?probe=1c74d63cc4) | Mar 10, 2021 |
| Apple         | MacBookPro11,3              | [06f7468dab](https://linux-hardware.org/?probe=06f7468dab) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| Lenovo        | ThinkPad T570 20H90002GE    | [ce32634171](https://linux-hardware.org/?probe=ce32634171) | Mar 09, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Dell          | Latitude E6530              | [15b1567c06](https://linux-hardware.org/?probe=15b1567c06) | Feb 27, 2021 |
| Dell          | Latitude E6530              | [519e2218aa](https://linux-hardware.org/?probe=519e2218aa) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | [602223a1ab](https://linux-hardware.org/?probe=602223a1ab) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| Toshiba       | Satellite L775              | [670f2c264f](https://linux-hardware.org/?probe=670f2c264f) | Feb 24, 2021 |
| Acer          | Aspire E5-573G              | [55a00ca46d](https://linux-hardware.org/?probe=55a00ca46d) | Feb 24, 2021 |
| Bluechip C... | BUSINESSline                | [740e39daaa](https://linux-hardware.org/?probe=740e39daaa) | Feb 23, 2021 |
| Dell          | XPS 15 9570                 | [084be10f62](https://linux-hardware.org/?probe=084be10f62) | Feb 19, 2021 |
| Dell          | Latitude 5480               | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| Apple         | MacBookPro5,1               | [238564a9fc](https://linux-hardware.org/?probe=238564a9fc) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [b27e52570f](https://linux-hardware.org/?probe=b27e52570f) | Feb 17, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Apple         | MacBookPro11,1              | [e121595694](https://linux-hardware.org/?probe=e121595694) | Feb 16, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| Lenovo        | ThinkPad L520 785958G       | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| Apple         | MacBookPro5,5               | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| Notebook      | N2x0WU                      | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [874d0c0e0e](https://linux-hardware.org/?probe=874d0c0e0e) | Feb 05, 2021 |
| Sony          | VPCF11J1E                   | [a4c36618e9](https://linux-hardware.org/?probe=a4c36618e9) | Feb 03, 2021 |
| HP            | ENVY 17                     | [7b09b4c5b4](https://linux-hardware.org/?probe=7b09b4c5b4) | Feb 02, 2021 |
| Dell          | XPS 13 9300                 | [ec70bba0fc](https://linux-hardware.org/?probe=ec70bba0fc) | Feb 01, 2021 |
| Google        | Swanky                      | [c4dd59ca8a](https://linux-hardware.org/?probe=c4dd59ca8a) | Jan 29, 2021 |
| Dell          | Latitude D820               | [c4b9edad97](https://linux-hardware.org/?probe=c4b9edad97) | Jan 24, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | [6bb7d90da6](https://linux-hardware.org/?probe=6bb7d90da6) | Jan 23, 2021 |
| Lenovo        | ThinkPad T61 64659TU        | [b302c2489e](https://linux-hardware.org/?probe=b302c2489e) | Jan 23, 2021 |
| ASUSTek       | K56CM                       | [e1da558e84](https://linux-hardware.org/?probe=e1da558e84) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Lenovo        | B50-10 80QR                 | [136f6c27fb](https://linux-hardware.org/?probe=136f6c27fb) | Jan 22, 2021 |
| Medion        | E7222                       | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| HP            | Pavilion Notebook           | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [fc5afc1dc2](https://linux-hardware.org/?probe=fc5afc1dc2) | Jan 18, 2021 |
| Lenovo        | ThinkPad T440S 20AQ005NU... | [356ab4974a](https://linux-hardware.org/?probe=356ab4974a) | Jan 18, 2021 |
| HP            | ENVY Notebook               | [e75216ca48](https://linux-hardware.org/?probe=e75216ca48) | Jan 17, 2021 |
| Dell          | Latitude E6530              | [da4602f931](https://linux-hardware.org/?probe=da4602f931) | Jan 16, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [325809a72d](https://linux-hardware.org/?probe=325809a72d) | Jan 16, 2021 |
| Dell          | Inspiron 7558               | [272d237def](https://linux-hardware.org/?probe=272d237def) | Jan 15, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | Yoga 900-13ISK 80UE         | [7b790852bf](https://linux-hardware.org/?probe=7b790852bf) | Jan 13, 2021 |
| Acer          | Aspire VN7-792G             | [0b1c2de104](https://linux-hardware.org/?probe=0b1c2de104) | Jan 13, 2021 |
| Lenovo        | Yoga 900-13ISK 80MK         | [8956e9185a](https://linux-hardware.org/?probe=8956e9185a) | Jan 13, 2021 |
| Lenovo        | V155-15API 81V5             | [a3143c0638](https://linux-hardware.org/?probe=a3143c0638) | Jan 13, 2021 |
| Acer          | NU-A515-44-R68D             | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| Dell          | Latitude E6540              | [c6ab95a062](https://linux-hardware.org/?probe=c6ab95a062) | Jan 11, 2021 |
| Dell          | Latitude E6540              | [565853d023](https://linux-hardware.org/?probe=565853d023) | Jan 10, 2021 |
| HP            | 250 G7 Notebook PC          | [0d0aa5182b](https://linux-hardware.org/?probe=0d0aa5182b) | Jan 10, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| HP            | 15                          | [7559b865f0](https://linux-hardware.org/?probe=7559b865f0) | Jan 06, 2021 |
| Apple         | MacBookPro9,2               | [62f0ab94ac](https://linux-hardware.org/?probe=62f0ab94ac) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| Dell          | XPS L501X                   | [4ced160372](https://linux-hardware.org/?probe=4ced160372) | Dec 31, 2020 |
| SLIMBOOK      | PROX15-AMD                  | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [ca0a06995e](https://linux-hardware.org/?probe=ca0a06995e) | Dec 28, 2020 |
| HP            | ENVY m6                     | [50e8b7f0f6](https://linux-hardware.org/?probe=50e8b7f0f6) | Dec 28, 2020 |
| Dell          | XPS 13 9370                 | [d96119f05d](https://linux-hardware.org/?probe=d96119f05d) | Dec 26, 2020 |
| Dell          | Inspiron 3476               | [c269f527ed](https://linux-hardware.org/?probe=c269f527ed) | Dec 25, 2020 |
| Lenovo        | V155-15API 81V5             | [afd1dcfbae](https://linux-hardware.org/?probe=afd1dcfbae) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| ASUSTek       | X540SAA                     | [fafdaae4cb](https://linux-hardware.org/?probe=fafdaae4cb) | Dec 23, 2020 |
| HP            | EliteBook 6930p             | [ddde2864e6](https://linux-hardware.org/?probe=ddde2864e6) | Dec 22, 2020 |
| Lenovo        | V155-15API 81V5             | [45526695b8](https://linux-hardware.org/?probe=45526695b8) | Dec 21, 2020 |
| Lenovo        | ThinkPad T480s 20L8S8540... | [12fb9652a7](https://linux-hardware.org/?probe=12fb9652a7) | Dec 21, 2020 |
| Dell          | XPS 15 9560                 | [47fb295e32](https://linux-hardware.org/?probe=47fb295e32) | Dec 21, 2020 |
| Samsung       | NC210/NC110                 | [98057a3a7a](https://linux-hardware.org/?probe=98057a3a7a) | Dec 19, 2020 |
| Samsung       | NC210/NC110                 | [4f3402c9dc](https://linux-hardware.org/?probe=4f3402c9dc) | Dec 19, 2020 |
| Timi          | TM1709                      | [089615b43f](https://linux-hardware.org/?probe=089615b43f) | Dec 16, 2020 |
| HP            | EliteBook 8760w             | [5e2ff51ade](https://linux-hardware.org/?probe=5e2ff51ade) | Dec 15, 2020 |
| Lenovo        | Flex 2-14 20404             | [8c7c33ba8b](https://linux-hardware.org/?probe=8c7c33ba8b) | Dec 14, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| HP            | EliteBook Folio 9480m       | [7d51a3bee8](https://linux-hardware.org/?probe=7d51a3bee8) | Dec 14, 2020 |
| HP            | Notebook                    | [a770f1e52d](https://linux-hardware.org/?probe=a770f1e52d) | Dec 13, 2020 |
| TUXEDO        | Polaris 15 AMD Gen1         | [602a601769](https://linux-hardware.org/?probe=602a601769) | Dec 11, 2020 |
| HP            | OMEN by Laptop              | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| Acer          | Swift SF314-41              | [5155111cfa](https://linux-hardware.org/?probe=5155111cfa) | Dec 10, 2020 |
| Acer          | AOD260                      | [635a9139e1](https://linux-hardware.org/?probe=635a9139e1) | Dec 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [baf10417f7](https://linux-hardware.org/?probe=baf10417f7) | Dec 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| Dell          | Latitude 5480               | [02680953ae](https://linux-hardware.org/?probe=02680953ae) | Dec 04, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [e6ee8ad4bb](https://linux-hardware.org/?probe=e6ee8ad4bb) | Dec 03, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [153a43bcc6](https://linux-hardware.org/?probe=153a43bcc6) | Dec 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [52cf6d4786](https://linux-hardware.org/?probe=52cf6d4786) | Dec 02, 2020 |
| Fujitsu       | LIFEBOOK AH562              | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Timi          | TM1709                      | [bcccdee6ec](https://linux-hardware.org/?probe=bcccdee6ec) | Nov 29, 2020 |
| System76      | Galago Pro                  | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | System Inspiron N4110       | [8d8bd09d64](https://linux-hardware.org/?probe=8d8bd09d64) | Nov 27, 2020 |
| Toshiba       | Satellite S70-B             | [d9925a0d93](https://linux-hardware.org/?probe=d9925a0d93) | Nov 26, 2020 |
| Dell          | Latitude 5310               | [b941f2a157](https://linux-hardware.org/?probe=b941f2a157) | Nov 25, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ce492b1a92](https://linux-hardware.org/?probe=ce492b1a92) | Nov 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3cfe7597e](https://linux-hardware.org/?probe=e3cfe7597e) | Nov 25, 2020 |
| Dell          | Inspiron 3558               | [2beee5183a](https://linux-hardware.org/?probe=2beee5183a) | Nov 24, 2020 |
| Lenovo        | G580                        | [bbca803600](https://linux-hardware.org/?probe=bbca803600) | Nov 23, 2020 |
| Dell          | Latitude 5480               | [30bffef4fc](https://linux-hardware.org/?probe=30bffef4fc) | Nov 22, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| HP            | EliteBook 8540p             | [d9ca357ad7](https://linux-hardware.org/?probe=d9ca357ad7) | Nov 20, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Lenovo        | ThinkPad T430 2347AQ9       | [6fa209f1de](https://linux-hardware.org/?probe=6fa209f1de) | Nov 19, 2020 |
| Entroware     | Apollo                      | [6d7a020174](https://linux-hardware.org/?probe=6d7a020174) | Nov 19, 2020 |
| Dell          | XPS L421X                   | [4efcda4ace](https://linux-hardware.org/?probe=4efcda4ace) | Nov 18, 2020 |
| Dell          | Inspiron 5770               | [6abb25b1de](https://linux-hardware.org/?probe=6abb25b1de) | Nov 18, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [75d38974bc](https://linux-hardware.org/?probe=75d38974bc) | Nov 15, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [299e10281f](https://linux-hardware.org/?probe=299e10281f) | Nov 15, 2020 |
| Timi          | TM1709                      | [522d6ab484](https://linux-hardware.org/?probe=522d6ab484) | Nov 15, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| Acer          | Aspire E5-532               | [79948d67b4](https://linux-hardware.org/?probe=79948d67b4) | Nov 15, 2020 |
| ASUSTek       | K52JT                       | [be614c012f](https://linux-hardware.org/?probe=be614c012f) | Nov 15, 2020 |
| Timi          | TM1607                      | [db600ca49e](https://linux-hardware.org/?probe=db600ca49e) | Nov 14, 2020 |
| Acer          | Aspire E5-523               | [316dc021cb](https://linux-hardware.org/?probe=316dc021cb) | Nov 14, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [867148b244](https://linux-hardware.org/?probe=867148b244) | Nov 14, 2020 |
| HP            | EliteBook 8540p             | [1df463aa08](https://linux-hardware.org/?probe=1df463aa08) | Nov 13, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [addf2ac7fa](https://linux-hardware.org/?probe=addf2ac7fa) | Nov 12, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [9ebd194a93](https://linux-hardware.org/?probe=9ebd194a93) | Nov 12, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [49eef48191](https://linux-hardware.org/?probe=49eef48191) | Nov 12, 2020 |
| HP            | EliteBook 8760w             | [27ecc71233](https://linux-hardware.org/?probe=27ecc71233) | Nov 11, 2020 |
| Lenovo        | ThinkPad X201 3680KC5       | [2f03701216](https://linux-hardware.org/?probe=2f03701216) | Nov 11, 2020 |
| HP            | EliteBook 8540p             | [6a0b95782d](https://linux-hardware.org/?probe=6a0b95782d) | Nov 11, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [f2fc35bc80](https://linux-hardware.org/?probe=f2fc35bc80) | Nov 10, 2020 |
| HP            | EliteBook 8540p             | [a3264597e8](https://linux-hardware.org/?probe=a3264597e8) | Nov 10, 2020 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [e6ae7e8546](https://linux-hardware.org/?probe=e6ae7e8546) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [1dbe42216a](https://linux-hardware.org/?probe=1dbe42216a) | Nov 10, 2020 |
| Lenovo        | G560 0679                   | [35c00cb9bd](https://linux-hardware.org/?probe=35c00cb9bd) | Nov 09, 2020 |
| Medion        | E7212                       | [8979d90ea2](https://linux-hardware.org/?probe=8979d90ea2) | Nov 09, 2020 |
| Medion        | E7212                       | [3650f725ba](https://linux-hardware.org/?probe=3650f725ba) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | [c84684fab0](https://linux-hardware.org/?probe=c84684fab0) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | [57911ec356](https://linux-hardware.org/?probe=57911ec356) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| ASUSTek       | E403NA                      | [c18d0128e0](https://linux-hardware.org/?probe=c18d0128e0) | Nov 09, 2020 |
| ASUSTek       | K501UX                      | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| Lenovo        | ThinkPad T420 423662U       | [f8954d3570](https://linux-hardware.org/?probe=f8954d3570) | Nov 02, 2020 |
| Apple         | MacBookPro7,1               | [b57fd68ea6](https://linux-hardware.org/?probe=b57fd68ea6) | Nov 01, 2020 |
| Acer          | Aspire F5-572               | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| ASUSTek       | U36SG                       | [77de00a544](https://linux-hardware.org/?probe=77de00a544) | Oct 29, 2020 |
| HP            | Folio 13                    | [0687b076f8](https://linux-hardware.org/?probe=0687b076f8) | Oct 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [03f33fb1bf](https://linux-hardware.org/?probe=03f33fb1bf) | Oct 28, 2020 |
| HP            | ENVY 15                     | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| HP            | EliteBook 8460p             | [83d1965847](https://linux-hardware.org/?probe=83d1965847) | Oct 25, 2020 |
| HP            | ProBook 450 G5              | [e726afbb3a](https://linux-hardware.org/?probe=e726afbb3a) | Oct 22, 2020 |
| Lenovo        | ThinkPad T440p 20AWS21V0... | [d38362dbe3](https://linux-hardware.org/?probe=d38362dbe3) | Oct 20, 2020 |
| Fujitsu       | LIFEBOOK P770               | [255c63f72d](https://linux-hardware.org/?probe=255c63f72d) | Oct 17, 2020 |
| eMachines     | eME640G                     | [a5176c2926](https://linux-hardware.org/?probe=a5176c2926) | Oct 15, 2020 |
| HP            | EliteBook 8460p             | [efc5e42972](https://linux-hardware.org/?probe=efc5e42972) | Oct 15, 2020 |
| Sony          | VPCEB1E1E                   | [cbd4fefba6](https://linux-hardware.org/?probe=cbd4fefba6) | Oct 14, 2020 |
| HP            | ProBook 450 G1              | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Toshiba       | Satellite S70-B             | [7732c2c6d9](https://linux-hardware.org/?probe=7732c2c6d9) | Oct 14, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| MSI           | GE62VR 6RF                  | [d6186120ce](https://linux-hardware.org/?probe=d6186120ce) | Oct 11, 2020 |
| Timi          | TM1709                      | [0d3a90e1de](https://linux-hardware.org/?probe=0d3a90e1de) | Oct 11, 2020 |
| MSI           | GE62VR 6RF                  | [cbdaf7b97a](https://linux-hardware.org/?probe=cbdaf7b97a) | Oct 10, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d8bdfa0313](https://linux-hardware.org/?probe=d8bdfa0313) | Oct 06, 2020 |
| HP            | ENVY 15                     | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Medion        | P7624                       | [a4216be7a9](https://linux-hardware.org/?probe=a4216be7a9) | Oct 05, 2020 |
| Dell          | Inspiron 5520               | [aa7011d06b](https://linux-hardware.org/?probe=aa7011d06b) | Sep 10, 2020 |
| Dell          | Inspiron 5520               | [cc20cdc047](https://linux-hardware.org/?probe=cc20cdc047) | Sep 09, 2020 |
| Acer          | Aspire F5-573G              | [ec3d93d07c](https://linux-hardware.org/?probe=ec3d93d07c) | Jul 24, 2020 |
| Acer          | Aspire F5-573G              | [a24a914659](https://linux-hardware.org/?probe=a24a914659) | Jul 24, 2020 |
| Apple         | MacBookPro14,2              | [0388e1560c](https://linux-hardware.org/?probe=0388e1560c) | Jul 19, 2020 |
| Apple         | MacBookPro14,2              | [e6c8216292](https://linux-hardware.org/?probe=e6c8216292) | Jul 18, 2020 |
| Apple         | MacBookPro14,2              | [98f781c69d](https://linux-hardware.org/?probe=98f781c69d) | Jul 18, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [3b43913f4f](https://linux-hardware.org/?probe=3b43913f4f) | Jul 07, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Teclast       | Cherry Trail Tablet         | [f975838f9a](https://linux-hardware.org/?probe=f975838f9a) | Jun 26, 2020 |
| HP            | 255 G7 Notebook PC          | [23d10923e3](https://linux-hardware.org/?probe=23d10923e3) | Jun 23, 2020 |
| Dell          | Latitude E6320              | [ddd1262c4d](https://linux-hardware.org/?probe=ddd1262c4d) | Apr 14, 2020 |
| HP            | Notebook                    | [a711b56cd0](https://linux-hardware.org/?probe=a711b56cd0) | Apr 13, 2020 |
| HP            | Notebook                    | [3e6181305b](https://linux-hardware.org/?probe=3e6181305b) | Apr 13, 2020 |
| Dell          | Latitude E6320              | [d1ffc53a12](https://linux-hardware.org/?probe=d1ffc53a12) | Apr 12, 2020 |
| ASUSTek       | X540LA                      | [64daf31a22](https://linux-hardware.org/?probe=64daf31a22) | Apr 05, 2020 |
| Toshiba       | Satellite C660              | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Acer          | Aspire VN7-791G             | [cd10eea9ff](https://linux-hardware.org/?probe=cd10eea9ff) | Apr 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f09c3dfb9f](https://linux-hardware.org/?probe=f09c3dfb9f) | Jan 31, 2020 |
| HP            | Pavilion dv7                | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| Acer          | Nitro AN515-42              | [f592750747](https://linux-hardware.org/?probe=f592750747) | Aug 16, 2019 |
| HP            | Laptop 15-bw0xx             | [09a098a5aa](https://linux-hardware.org/?probe=09a098a5aa) | Jul 25, 2019 |
| HP            | Laptop 15-bw0xx             | [024cf11765](https://linux-hardware.org/?probe=024cf11765) | Jul 20, 2019 |
| HP            | Laptop 15-bw0xx             | [4b6d3033d0](https://linux-hardware.org/?probe=4b6d3033d0) | Jul 09, 2019 |
| HP            | Laptop 17-ak0xx             | [b53e43fc3c](https://linux-hardware.org/?probe=b53e43fc3c) | May 06, 2019 |
| ASUSTek       | UX31A                       | [2a30d224cf](https://linux-hardware.org/?probe=2a30d224cf) | Feb 24, 2019 |
| Lenovo        | ThinkPad E420 11417NA       | [9d5fad95db](https://linux-hardware.org/?probe=9d5fad95db) | Aug 22, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 570       | 86.76%  |
| ArcoLinux             | 66        | 10.05%  |
| ArcoLinux 20.6.5      | 7         | 1.07%   |
| ArcoLinux 20.7.5      | 4         | 0.61%   |
| ArcoLinux 20.3.4      | 2         | 0.3%    |
| ArcoLinux 20.3.3      | 2         | 0.3%    |
| ArcoLinux I3-v19.02.4 | 1         | 0.15%   |
| ArcoLinux 6.9.2       | 1         | 0.15%   |
| ArcoLinux 20.2.12     | 1         | 0.15%   |
| ArcoLinux 20.1.4      | 1         | 0.15%   |
| ArcoLinux 19.07.11    | 1         | 0.15%   |
| ArcoLinux 19.02.4     | 1         | 0.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ArcoLinux | 653       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 20        | 2.77%   |
| 5.15.10-arch1-1   | 19        | 2.63%   |
| 5.13.13-arch1-1   | 18        | 2.49%   |
| 5.14.14-arch1-1   | 14        | 1.94%   |
| 5.13.12-arch1-1   | 13        | 1.8%    |
| 5.14.12-arch1-1   | 12        | 1.66%   |
| 5.17.1-arch1-1    | 11        | 1.52%   |
| 5.12.13-arch1-2   | 10        | 1.38%   |
| 5.15.11-arch2-1   | 9         | 1.24%   |
| 5.9.8-arch1-1     | 8         | 1.11%   |
| 5.9.1-arch1-1     | 8         | 1.11%   |
| 5.16.10-arch1-1   | 8         | 1.11%   |
| 5.15.5-arch1-1    | 8         | 1.11%   |
| 5.12.15-arch1-1   | 8         | 1.11%   |
| 5.12.14-arch1-1   | 8         | 1.11%   |
| 5.17.4-arch1-1    | 7         | 0.97%   |
| 5.16.2-arch1-1    | 7         | 0.97%   |
| 5.15.13-arch1-1   | 7         | 0.97%   |
| 5.12.10-arch1-1   | 7         | 0.97%   |
| 5.9.10-arch1-1    | 6         | 0.83%   |
| 5.17.5-arch1-1    | 6         | 0.83%   |
| 5.16.16-arch1-1   | 6         | 0.83%   |
| 5.16.12-arch1-1   | 6         | 0.83%   |
| 5.14.9-arch2-1    | 6         | 0.83%   |
| 5.13.8-arch1-1    | 6         | 0.83%   |
| 5.12.12-arch1-1   | 6         | 0.83%   |
| 5.10.84-1-lts     | 6         | 0.83%   |
| 5.4.70-1-lts      | 5         | 0.69%   |
| 5.18.3-arch1-1    | 5         | 0.69%   |
| 5.16.11-arch1-1   | 5         | 0.69%   |
| 5.15.4-arch1-1    | 5         | 0.69%   |
| 5.15.12-arch1-1   | 5         | 0.69%   |
| 5.10.88-2-lts     | 5         | 0.69%   |
| 5.10.6-arch1-1    | 5         | 0.69%   |
| 5.10.56-1-lts     | 5         | 0.69%   |
| 5.10.16-arch1-1   | 5         | 0.69%   |
| 5.9.6-arch1-1     | 4         | 0.55%   |
| 5.9.14-zen1-1-zen | 4         | 0.55%   |
| 5.9.14-arch1-1    | 4         | 0.55%   |
| 5.9.13-arch1-1    | 4         | 0.55%   |
| 5.18.1-arch1-1    | 4         | 0.55%   |
| 5.17.9-arch1-1    | 4         | 0.55%   |
| 5.16.8-arch1-1    | 4         | 0.55%   |
| 5.16.5-arch1-1    | 4         | 0.55%   |
| 5.16.4-arch1-1    | 4         | 0.55%   |
| 5.16.15-arch1-1   | 4         | 0.55%   |
| 5.15.6-arch2-1    | 4         | 0.55%   |
| 5.15.2-arch1-1    | 4         | 0.55%   |
| 5.14.7-arch1-1    | 4         | 0.55%   |
| 5.14.15-arch1-1   | 4         | 0.55%   |
| 5.13.9-arch1-1    | 4         | 0.55%   |
| 5.13.6-arch1-1    | 4         | 0.55%   |
| 5.13.10-arch1-1   | 4         | 0.55%   |
| 5.11.12-arch1-1   | 4         | 0.55%   |
| 5.10.85-1-lts     | 4         | 0.55%   |
| 5.10.7-arch1-1    | 4         | 0.55%   |
| 5.10.60-1-lts     | 4         | 0.55%   |
| 5.10.11-arch1-1   | 4         | 0.55%   |
| 5.9.6-zen1-1-zen  | 3         | 0.41%   |
| 5.9.11-arch2-1    | 3         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.7  | 24        | 3.32%   |
| 5.15.10 | 19        | 2.63%   |
| 5.13.13 | 18        | 2.49%   |
| 5.17.1  | 14        | 1.94%   |
| 5.14.14 | 14        | 1.94%   |
| 5.14.12 | 13        | 1.8%    |
| 5.13.12 | 13        | 1.8%    |
| 5.9.8   | 12        | 1.66%   |
| 5.9.1   | 10        | 1.38%   |
| 5.12.13 | 10        | 1.38%   |
| 5.16.2  | 9         | 1.24%   |
| 5.16.10 | 9         | 1.24%   |
| 5.15.5  | 9         | 1.24%   |
| 5.15.11 | 9         | 1.24%   |
| 5.12.15 | 9         | 1.24%   |
| 5.9.14  | 8         | 1.11%   |
| 5.14.9  | 8         | 1.11%   |
| 5.12.14 | 8         | 1.11%   |
| 5.10.16 | 8         | 1.11%   |
| 5.9.6   | 7         | 0.97%   |
| 5.9.10  | 7         | 0.97%   |
| 5.17.5  | 7         | 0.97%   |
| 5.17.4  | 7         | 0.97%   |
| 5.15.13 | 7         | 0.97%   |
| 5.12.10 | 7         | 0.97%   |
| 5.18.3  | 6         | 0.83%   |
| 5.16.16 | 6         | 0.83%   |
| 5.16.12 | 6         | 0.83%   |
| 5.16.11 | 6         | 0.83%   |
| 5.15.4  | 6         | 0.83%   |
| 5.13.8  | 6         | 0.83%   |
| 5.12.12 | 6         | 0.83%   |
| 5.10.84 | 6         | 0.83%   |
| 5.9.13  | 5         | 0.69%   |
| 5.9.11  | 5         | 0.69%   |
| 5.4.70  | 5         | 0.69%   |
| 5.16.8  | 5         | 0.69%   |
| 5.16.5  | 5         | 0.69%   |
| 5.15.6  | 5         | 0.69%   |
| 5.15.2  | 5         | 0.69%   |
| 5.15.12 | 5         | 0.69%   |
| 5.14.15 | 5         | 0.69%   |
| 5.13.9  | 5         | 0.69%   |
| 5.13.6  | 5         | 0.69%   |
| 5.11.12 | 5         | 0.69%   |
| 5.11.11 | 5         | 0.69%   |
| 5.10.88 | 5         | 0.69%   |
| 5.10.7  | 5         | 0.69%   |
| 5.10.6  | 5         | 0.69%   |
| 5.10.56 | 5         | 0.69%   |
| 5.10.11 | 5         | 0.69%   |
| 5.18.7  | 4         | 0.55%   |
| 5.18.5  | 4         | 0.55%   |
| 5.18.1  | 4         | 0.55%   |
| 5.17.9  | 4         | 0.55%   |
| 5.17.3  | 4         | 0.55%   |
| 5.16.4  | 4         | 0.55%   |
| 5.16.15 | 4         | 0.55%   |
| 5.14.7  | 4         | 0.55%   |
| 5.14.6  | 4         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 123       | 17.55%  |
| 5.15    | 120       | 17.12%  |
| 5.16    | 63        | 8.99%   |
| 5.14    | 61        | 8.7%    |
| 5.13    | 59        | 8.42%   |
| 5.9     | 57        | 8.13%   |
| 5.12    | 54        | 7.7%    |
| 5.17    | 46        | 6.56%   |
| 5.11    | 35        | 4.99%   |
| 5.4     | 33        | 4.71%   |
| 5.18    | 31        | 4.42%   |
| 5.8     | 6         | 0.86%   |
| 5.7     | 4         | 0.57%   |
| 5.5     | 3         | 0.43%   |
| 5.6     | 2         | 0.29%   |
| 5.2     | 1         | 0.14%   |
| 5.0     | 1         | 0.14%   |
| 4.20    | 1         | 0.14%   |
| 4.18    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 653       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| XFCE           | 210       | 31.11%  |
| KDE5           | 107       | 15.85%  |
| i3             | 59        | 8.74%   |
| GNOME          | 45        | 6.67%   |
| awesome        | 38        | 5.63%   |
| qtile          | 35        | 5.19%   |
| bspwm          | 29        | 4.3%    |
| DWM            | 25        | 3.7%    |
| xmonad         | 23        | 3.41%   |
| X-Cinnamon     | 23        | 3.41%   |
| KDE            | 12        | 1.78%   |
| Unknown        | 10        | 1.48%   |
| LeftWM         | 8         | 1.19%   |
| Deepin         | 8         | 1.19%   |
| Budgie         | 7         | 1.04%   |
| MATE           | 6         | 0.89%   |
| i3-with-shmlog | 6         | 0.89%   |
| herbstluftwm   | 5         | 0.74%   |
| spectrwm       | 3         | 0.44%   |
| LXQt           | 3         | 0.44%   |
| Cinnamon       | 3         | 0.44%   |
| Unity          | 2         | 0.3%    |
| cwm            | 2         | 0.3%    |
| sway           | 1         | 0.15%   |
| openbox        | 1         | 0.15%   |
| jwm            | 1         | 0.15%   |
| dwm-sc         | 1         | 0.15%   |
| dusk           | 1         | 0.15%   |
| Cutefish       | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 616       | 93.9%   |
| Tty     | 24        | 3.66%   |
| Wayland | 13        | 1.98%   |
| Unknown | 3         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 323       | 47.22%  |
| TDM     | 149       | 21.78%  |
| LightDM | 115       | 16.81%  |
| Unknown | 82        | 11.99%  |
| GDM     | 11        | 1.61%   |
| XDM     | 1         | 0.15%   |
| SLiM    | 1         | 0.15%   |
| Ly      | 1         | 0.15%   |
| LXDM    | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 385       | 58.33%  |
| en_GB   | 45        | 6.82%   |
| de_DE   | 37        | 5.61%   |
| en_CA   | 23        | 3.48%   |
| en_IN   | 22        | 3.33%   |
| fr_FR   | 18        | 2.73%   |
| en_AU   | 11        | 1.67%   |
| ru_RU   | 9         | 1.36%   |
| pl_PL   | 8         | 1.21%   |
| pt_BR   | 7         | 1.06%   |
| Unknown | 7         | 1.06%   |
| hu_HU   | 6         | 0.91%   |
| es_ES   | 6         | 0.91%   |
| ru_UA   | 4         | 0.61%   |
| it_IT   | 4         | 0.61%   |
| es_AR   | 4         | 0.61%   |
| en_IE   | 4         | 0.61%   |
| tr_TR   | 3         | 0.45%   |
| nl_BE   | 3         | 0.45%   |
| es_CL   | 3         | 0.45%   |
| en_ZA   | 3         | 0.45%   |
| en_SG   | 3         | 0.45%   |
| en_IL   | 3         | 0.45%   |
| en_DK   | 3         | 0.45%   |
| el_GR   | 3         | 0.45%   |
| sv_SE   | 2         | 0.3%    |
| ro_RO   | 2         | 0.3%    |
| nl_NL   | 2         | 0.3%    |
| ja_JP   | 2         | 0.3%    |
| fr_CA   | 2         | 0.3%    |
| fr_BE   | 2         | 0.3%    |
| fi_FI   | 2         | 0.3%    |
| es_MX   | 2         | 0.3%    |
| en_PH   | 2         | 0.3%    |
| zh_CN   | 1         | 0.15%   |
| pt_PT   | 1         | 0.15%   |
| nb_NO   | 1         | 0.15%   |
| lv_LV   | 1         | 0.15%   |
| fr_CH   | 1         | 0.15%   |
| es_VE   | 1         | 0.15%   |
| es_US   | 1         | 0.15%   |
| es_PY   | 1         | 0.15%   |
| es_EC   | 1         | 0.15%   |
| es_CO   | 1         | 0.15%   |
| en_NZ   | 1         | 0.15%   |
| en_HK   | 1         | 0.15%   |
| de_ch   | 1         | 0.15%   |
| de_AT   | 1         | 0.15%   |
| da_DK   | 1         | 0.15%   |
| cs_CZ   | 1         | 0.15%   |
| ca_ES   | 1         | 0.15%   |
| C       | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 455       | 69.25%  |
| BIOS | 202       | 30.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 510       | 77.27%  |
| Btrfs   | 104       | 15.76%  |
| Overlay | 31        | 4.7%    |
| Xfs     | 10        | 1.52%   |
| F2fs    | 3         | 0.45%   |
| Jfs     | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 463       | 70.36%  |
| MBR     | 121       | 18.39%  |
| Unknown | 74        | 11.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 549       | 82.68%  |
| Yes       | 115       | 17.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 445       | 67.84%  |
| Yes       | 211       | 32.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 195       | 29.86%  |
| Dell                 | 102       | 15.62%  |
| Hewlett-Packard      | 87        | 13.32%  |
| ASUSTek Computer     | 75        | 11.49%  |
| Acer                 | 50        | 7.66%   |
| Apple                | 24        | 3.68%   |
| Toshiba              | 15        | 2.3%    |
| MSI                  | 11        | 1.68%   |
| Samsung Electronics  | 8         | 1.23%   |
| System76             | 7         | 1.07%   |
| Sony                 | 7         | 1.07%   |
| Razer                | 7         | 1.07%   |
| Notebook             | 6         | 0.92%   |
| Medion               | 6         | 0.92%   |
| HUAWEI               | 6         | 0.92%   |
| Fujitsu              | 6         | 0.92%   |
| Timi                 | 5         | 0.77%   |
| TUXEDO               | 4         | 0.61%   |
| Alienware            | 4         | 0.61%   |
| Teclast              | 2         | 0.31%   |
| Schenker             | 2         | 0.31%   |
| LG Electronics       | 2         | 0.31%   |
| Chuwi                | 2         | 0.31%   |
| Casper               | 2         | 0.31%   |
| AZW                  | 2         | 0.31%   |
| Unknown              | 2         | 0.31%   |
| UNITCOM              | 1         | 0.15%   |
| Standard             | 1         | 0.15%   |
| SLIMBOOK             | 1         | 0.15%   |
| Semp Toshiba         | 1         | 0.15%   |
| Pegatron             | 1         | 0.15%   |
| Monster              | 1         | 0.15%   |
| Intel Client Systems | 1         | 0.15%   |
| Google               | 1         | 0.15%   |
| Entroware            | 1         | 0.15%   |
| eMachines            | 1         | 0.15%   |
| Eluktronics          | 1         | 0.15%   |
| Daten Tecnologia     | 1         | 0.15%   |
| Compal               | 1         | 0.15%   |
| Bluechip Computer    | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion Notebook                   | 6         | 0.92%   |
| HP Notebook                            | 5         | 0.77%   |
| Razer Blade                            | 4         | 0.61%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 4         | 0.61%   |
| HP EliteBook 840 G3                    | 4         | 0.61%   |
| Unknown                                | 4         | 0.61%   |
| Timi TM1607                            | 3         | 0.46%   |
| Lenovo Legion Y540-15IRH 81SX          | 3         | 0.46%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 3         | 0.46%   |
| HP Laptop 15s-eq2xxx                   | 3         | 0.46%   |
| HP EliteBook 8460p                     | 3         | 0.46%   |
| HP 255 G7 Notebook PC                  | 3         | 0.46%   |
| Dell XPS 15 9570                       | 3         | 0.46%   |
| Dell Precision M4800                   | 3         | 0.46%   |
| Dell Latitude E6530                    | 3         | 0.46%   |
| Dell Inspiron 15 7000 Gaming           | 3         | 0.46%   |
| Apple MacBookPro8,1                    | 3         | 0.46%   |
| Apple MacBookPro11,2                   | 3         | 0.46%   |
| Apple MacBookPro11,1                   | 3         | 0.46%   |
| Acer Swift SF314-41                    | 3         | 0.46%   |
| System76 Oryx Pro                      | 2         | 0.31%   |
| System76 Galago Pro                    | 2         | 0.31%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 2         | 0.31%   |
| Razer Blade Stealth                    | 2         | 0.31%   |
| Lenovo Yoga 900-13ISK 80MK             | 2         | 0.31%   |
| Lenovo V14-ADA 82C6                    | 2         | 0.31%   |
| Lenovo ThinkPad T410 2522AC1           | 2         | 0.31%   |
| Lenovo ThinkPad T14 Gen 2a 20XKCTO1WW  | 2         | 0.31%   |
| Lenovo Legion 5 15ARH05 82B5           | 2         | 0.31%   |
| Lenovo IdeaPad S145-15AST 81N3         | 2         | 0.31%   |
| Lenovo IdeaPad Flex-14API 81SS         | 2         | 0.31%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 2         | 0.31%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.31%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 2         | 0.31%   |
| Lenovo G50-30 80G0                     | 2         | 0.31%   |
| HUAWEI WRT-WX9                         | 2         | 0.31%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.31%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 2         | 0.31%   |
| HP OMEN by Laptop                      | 2         | 0.31%   |
| HP Laptop 15-da0xxx                    | 2         | 0.31%   |
| HP Laptop 15-bw0xx                     | 2         | 0.31%   |
| HP ENVY Notebook                       | 2         | 0.31%   |
| HP EliteBook 8760w                     | 2         | 0.31%   |
| HP 250 G7 Notebook PC                  | 2         | 0.31%   |
| Dell XPS 15 9560                       | 2         | 0.31%   |
| Dell XPS 15 9500                       | 2         | 0.31%   |
| Dell XPS 13 9370                       | 2         | 0.31%   |
| Dell XPS 13 9300                       | 2         | 0.31%   |
| Dell Precision 5550                    | 2         | 0.31%   |
| Dell Latitude E7440                    | 2         | 0.31%   |
| Dell Latitude E6540                    | 2         | 0.31%   |
| Dell Latitude E5430 non-vPro           | 2         | 0.31%   |
| Dell Latitude E4310                    | 2         | 0.31%   |
| Dell Latitude 7480                     | 2         | 0.31%   |
| Dell Latitude 5480                     | 2         | 0.31%   |
| Dell Latitude 5410                     | 2         | 0.31%   |
| Dell Inspiron 5570                     | 2         | 0.31%   |
| Chuwi GemiBook Pro                     | 2         | 0.31%   |
| ASUS X580VD                            | 2         | 0.31%   |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 110       | 16.85%  |
| Lenovo IdeaPad      | 44        | 6.74%   |
| Dell Latitude       | 35        | 5.36%   |
| Dell Inspiron       | 33        | 5.05%   |
| Acer Aspire         | 32        | 4.9%    |
| Dell XPS            | 21        | 3.22%   |
| HP Laptop           | 19        | 2.91%   |
| ASUS VivoBook       | 18        | 2.76%   |
| Lenovo Legion       | 16        | 2.45%   |
| HP Pavilion         | 15        | 2.3%    |
| HP EliteBook        | 15        | 2.3%    |
| Toshiba Satellite   | 12        | 1.84%   |
| Dell Precision      | 8         | 1.23%   |
| Apple MacBookPro11  | 8         | 1.23%   |
| Acer Nitro          | 8         | 1.23%   |
| Razer Blade         | 7         | 1.07%   |
| HP ProBook          | 6         | 0.92%   |
| HP ENVY             | 6         | 0.92%   |
| Fujitsu LIFEBOOK    | 6         | 0.92%   |
| ASUS TUF            | 6         | 0.92%   |
| ASUS ROG            | 6         | 0.92%   |
| HP Notebook         | 5         | 0.77%   |
| HP 250              | 5         | 0.77%   |
| Acer Swift          | 5         | 0.77%   |
| Lenovo Yoga         | 4         | 0.61%   |
| HP 255              | 4         | 0.61%   |
| Dell Vostro         | 4         | 0.61%   |
| Unknown             | 4         | 0.61%   |
| Timi TM1607         | 3         | 0.46%   |
| HP ZBook            | 3         | 0.46%   |
| Apple MacBookPro8   | 3         | 0.46%   |
| Apple MacBookPro5   | 3         | 0.46%   |
| Toshiba PORTEGE     | 2         | 0.31%   |
| System76 Oryx       | 2         | 0.31%   |
| System76 Galago     | 2         | 0.31%   |
| Samsung 350V5C      | 2         | 0.31%   |
| MSI Modern          | 2         | 0.31%   |
| MSI GS66            | 2         | 0.31%   |
| Lenovo V14-ADA      | 2         | 0.31%   |
| Lenovo ThinkBook    | 2         | 0.31%   |
| Lenovo G50-30       | 2         | 0.31%   |
| HUAWEI WRT-WX9      | 2         | 0.31%   |
| HUAWEI KLVL-WXX9    | 2         | 0.31%   |
| HP OMEN             | 2         | 0.31%   |
| Chuwi GemiBook      | 2         | 0.31%   |
| ASUS Zephyrus       | 2         | 0.31%   |
| ASUS X580VD         | 2         | 0.31%   |
| Apple MacBookPro9   | 2         | 0.31%   |
| Apple MacBookPro14  | 2         | 0.31%   |
| Alienware m15       | 2         | 0.31%   |
| Acer Predator       | 2         | 0.31%   |
| UNITCOM W55xEU      | 1         | 0.15%   |
| TUXEDO Polaris      | 1         | 0.15%   |
| TUXEDO InfinityBook | 1         | 0.15%   |
| TUXEDO BC1510       | 1         | 0.15%   |
| Toshiba QOSMIO      | 1         | 0.15%   |
| Timi TM1709         | 1         | 0.15%   |
| Timi TM1701         | 1         | 0.15%   |
| Teclast X98Pro      | 1         | 0.15%   |
| Teclast F15S        | 1         | 0.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 81        | 12.4%   |
| 2019 | 76        | 11.64%  |
| 2018 | 70        | 10.72%  |
| 2017 | 70        | 10.72%  |
| 2016 | 57        | 8.73%   |
| 2011 | 53        | 8.12%   |
| 2021 | 38        | 5.82%   |
| 2013 | 38        | 5.82%   |
| 2012 | 38        | 5.82%   |
| 2014 | 36        | 5.51%   |
| 2015 | 35        | 5.36%   |
| 2010 | 32        | 4.9%    |
| 2009 | 12        | 1.84%   |
| 2008 | 11        | 1.68%   |
| 2007 | 3         | 0.46%   |
| 2022 | 2         | 0.31%   |
| 2006 | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 653       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 653       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 648       | 99.23%  |
| Yes  | 5         | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 214       | 32.62%  |
| 16.01-24.0  | 158       | 24.09%  |
| 8.01-16.0   | 116       | 17.68%  |
| 3.01-4.0    | 96        | 14.63%  |
| 32.01-64.0  | 39        | 5.95%   |
| 1.01-2.0    | 11        | 1.68%   |
| 24.01-32.0  | 10        | 1.52%   |
| 64.01-256.0 | 7         | 1.07%   |
| 2.01-3.0    | 5         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 239       | 34.09%  |
| 2.01-3.0   | 182       | 25.96%  |
| 3.01-4.0   | 90        | 12.84%  |
| 4.01-8.0   | 76        | 10.84%  |
| 0.51-1.0   | 75        | 10.7%   |
| 8.01-16.0  | 24        | 3.42%   |
| 0.01-0.5   | 12        | 1.71%   |
| 16.01-24.0 | 2         | 0.29%   |
| 24.01-32.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 441       | 66.92%  |
| 2      | 190       | 28.83%  |
| 3      | 20        | 3.03%   |
| 4      | 4         | 0.61%   |
| 0      | 3         | 0.46%   |
| 6      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 466       | 71.15%  |
| Yes       | 189       | 28.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 539       | 82.29%  |
| No        | 116       | 17.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 647       | 99.08%  |
| No        | 6         | 0.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 556       | 84.37%  |
| No        | 103       | 15.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 115       | 17.53%  |
| Germany            | 55        | 8.38%   |
| India              | 36        | 5.49%   |
| UK                 | 34        | 5.18%   |
| Canada             | 30        | 4.57%   |
| France             | 24        | 3.66%   |
| Italy              | 17        | 2.59%   |
| Belgium            | 16        | 2.44%   |
| Poland             | 15        | 2.29%   |
| Russia             | 14        | 2.13%   |
| Netherlands        | 14        | 2.13%   |
| Brazil             | 14        | 2.13%   |
| Turkey             | 13        | 1.98%   |
| Hungary            | 13        | 1.98%   |
| Ukraine            | 12        | 1.83%   |
| Australia          | 12        | 1.83%   |
| Switzerland        | 11        | 1.68%   |
| Sweden             | 11        | 1.68%   |
| Spain              | 10        | 1.52%   |
| Indonesia          | 8         | 1.22%   |
| Argentina          | 8         | 1.22%   |
| Romania            | 7         | 1.07%   |
| Norway             | 7         | 1.07%   |
| Greece             | 7         | 1.07%   |
| Finland            | 7         | 1.07%   |
| Bangladesh         | 7         | 1.07%   |
| Czechia            | 6         | 0.91%   |
| China              | 6         | 0.91%   |
| Bulgaria           | 6         | 0.91%   |
| Portugal           | 5         | 0.76%   |
| Estonia            | 5         | 0.76%   |
| South Africa       | 4         | 0.61%   |
| Slovenia           | 4         | 0.61%   |
| Mexico             | 4         | 0.61%   |
| Ireland            | 4         | 0.61%   |
| Egypt              | 4         | 0.61%   |
| Denmark            | 4         | 0.61%   |
| Chile              | 4         | 0.61%   |
| Vietnam            | 3         | 0.46%   |
| Serbia             | 3         | 0.46%   |
| Morocco            | 3         | 0.46%   |
| Malaysia           | 3         | 0.46%   |
| Lithuania          | 3         | 0.46%   |
| Latvia             | 3         | 0.46%   |
| Japan              | 3         | 0.46%   |
| Hong Kong          | 3         | 0.46%   |
| Colombia           | 3         | 0.46%   |
| Algeria            | 3         | 0.46%   |
| UAE                | 2         | 0.3%    |
| Slovakia           | 2         | 0.3%    |
| Singapore          | 2         | 0.3%    |
| Philippines        | 2         | 0.3%    |
| Paraguay           | 2         | 0.3%    |
| Libya              | 2         | 0.3%    |
| Lebanon            | 2         | 0.3%    |
| Israel             | 2         | 0.3%    |
| Iran               | 2         | 0.3%    |
| Guatemala          | 2         | 0.3%    |
| Dominican Republic | 2         | 0.3%    |
| Croatia            | 2         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Berlin             | 7         | 1.03%   |
| Pune               | 6         | 0.88%   |
| Paris              | 6         | 0.88%   |
| Tallinn            | 5         | 0.74%   |
| Sydney             | 5         | 0.74%   |
| Budapest           | 5         | 0.74%   |
| Warsaw             | 4         | 0.59%   |
| Stockholm          | 4         | 0.59%   |
| Kolkata            | 4         | 0.59%   |
| Helsinki           | 4         | 0.59%   |
| Brooklyn           | 4         | 0.59%   |
| Bergheim           | 4         | 0.59%   |
| Athens             | 4         | 0.59%   |
| Ankara             | 4         | 0.59%   |
| Zurich             | 3         | 0.44%   |
| Spokane            | 3         | 0.44%   |
| Sofia              | 3         | 0.44%   |
| Seville            | 3         | 0.44%   |
| Scottsdale         | 3         | 0.44%   |
| Rio de Janeiro     | 3         | 0.44%   |
| Ochten             | 3         | 0.44%   |
| Mumbai             | 3         | 0.44%   |
| Moscow             | 3         | 0.44%   |
| Milan              | 3         | 0.44%   |
| Madrid             | 3         | 0.44%   |
| Lisbon             | 3         | 0.44%   |
| Lier               | 3         | 0.44%   |
| Kyiv               | 3         | 0.44%   |
| Izmir              | 3         | 0.44%   |
| Houston            | 3         | 0.44%   |
| Hamburg            | 3         | 0.44%   |
| Frankfurt am Main  | 3         | 0.44%   |
| Dhaka              | 3         | 0.44%   |
| Dagenham           | 3         | 0.44%   |
| Chicago            | 3         | 0.44%   |
| Central            | 3         | 0.44%   |
| Cairo              | 3         | 0.44%   |
| Bengaluru          | 3         | 0.44%   |
| Belgrade           | 3         | 0.44%   |
| Zagreb             | 2         | 0.29%   |
| Wiesbaden          | 2         | 0.29%   |
| Washington         | 2         | 0.29%   |
| Ufa                | 2         | 0.29%   |
| Tver               | 2         | 0.29%   |
| Toronto            | 2         | 0.29%   |
| Tongi              | 2         | 0.29%   |
| Tokyo              | 2         | 0.29%   |
| Thessaloniki       | 2         | 0.29%   |
| Tel Aviv           | 2         | 0.29%   |
| Tehran             | 2         | 0.29%   |
| St Petersburg      | 2         | 0.29%   |
| Singapore          | 2         | 0.29%   |
| Sao Paulo          | 2         | 0.29%   |
| Santo Domingo Este | 2         | 0.29%   |
| Santiago           | 2         | 0.29%   |
| Prague             | 2         | 0.29%   |
| Plano              | 2         | 0.29%   |
| Phnom Penh         | 2         | 0.29%   |
| Perth              | 2         | 0.29%   |
| Oslo               | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 162       | 201    | 19.06%  |
| WDC                 | 125       | 147    | 14.71%  |
| Seagate             | 99        | 111    | 11.65%  |
| Toshiba             | 72        | 84     | 8.47%   |
| Kingston            | 48        | 55     | 5.65%   |
| SK hynix            | 40        | 44     | 4.71%   |
| SanDisk             | 39        | 44     | 4.59%   |
| Crucial             | 27        | 32     | 3.18%   |
| Intel               | 26        | 32     | 3.06%   |
| HGST                | 24        | 27     | 2.82%   |
| Unknown             | 18        | 26     | 2.12%   |
| Micron Technology   | 18        | 18     | 2.12%   |
| Apple               | 14        | 18     | 1.65%   |
| Hitachi             | 13        | 14     | 1.53%   |
| A-DATA Technology   | 13        | 14     | 1.53%   |
| KIOXIA              | 11        | 14     | 1.29%   |
| PNY                 | 9         | 11     | 1.06%   |
| LITEON              | 9         | 10     | 1.06%   |
| Phison              | 7         | 9      | 0.82%   |
| LITEONIT            | 6         | 6      | 0.71%   |
| JMicron Technology  | 6         | 6      | 0.71%   |
| SPCC                | 5         | 5      | 0.59%   |
| Mushkin             | 4         | 4      | 0.47%   |
| Corsair             | 4         | 4      | 0.47%   |
| China               | 4         | 4      | 0.47%   |
| Transcend           | 3         | 3      | 0.35%   |
| Lenovo              | 3         | 4      | 0.35%   |
| KingSpec            | 3         | 3      | 0.35%   |
| Intenso             | 3         | 3      | 0.35%   |
| SSSTC               | 2         | 2      | 0.24%   |
| Silicon Motion      | 2         | 3      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Patriot             | 2         | 5      | 0.24%   |
| Lexar               | 2         | 2      | 0.24%   |
| GOODRAM             | 2         | 4      | 0.24%   |
| Gigabyte Technology | 2         | 3      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| XrayDisk            | 1         | 1      | 0.12%   |
| XPG                 | 1         | 1      | 0.12%   |
| W800S               | 1         | 2      | 0.12%   |
| Union Memory        | 1         | 1      | 0.12%   |
| UMIS                | 1         | 1      | 0.12%   |
| Team                | 1         | 1      | 0.12%   |
| SABRENT             | 1         | 1      | 0.12%   |
| OSCOO               | 1         | 2      | 0.12%   |
| OCZ                 | 1         | 1      | 0.12%   |
| NGFF                | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.12%   |
| KingFast            | 1         | 1      | 0.12%   |
| KESU                | 1         | 1      | 0.12%   |
| HUAWEI              | 1         | 1      | 0.12%   |
| HS-SSD-C100         | 1         | 2      | 0.12%   |
| HPE                 | 1         | 2      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |
| Dogfish             | 1         | 1      | 0.12%   |
| addlink             | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 28        | 3.15%   |
| Samsung SSD 860 EVO 500GB             | 16        | 1.8%    |
| Toshiba MQ01ABD100 1TB                | 14        | 1.57%   |
| Toshiba MQ04ABF100 1TB                | 13        | 1.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 1.24%   |
| Kingston SA400S37240G 240GB SSD       | 11        | 1.24%   |
| Samsung SSD 970 EVO Plus 1TB          | 8         | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB        | 7         | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB        | 6         | 0.67%   |
| Kingston SA400S37480G 480GB SSD       | 6         | 0.67%   |
| HGST HTS721010A9E630 1TB              | 6         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 5         | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 5         | 0.56%   |
| SanDisk SSD PLUS 480GB                | 5         | 0.56%   |
| Samsung SSD 850 EVO 500GB             | 5         | 0.56%   |
| Samsung MZVLB512HBJQ-000L7 512GB      | 5         | 0.56%   |
| JMicron Generic 2TB                   | 5         | 0.56%   |
| HGST HTS545050A7E680 500GB            | 5         | 0.56%   |
| Crucial CT1000MX500SSD1 1TB           | 5         | 0.56%   |
| Apple SSD SM0256F 256GB               | 5         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 4         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB              | 4         | 0.45%   |
| WDC WD10SPZX-08Z10 1TB                | 4         | 0.45%   |
| WDC WD10JPCX-24UE4T0 1TB              | 4         | 0.45%   |
| Toshiba MQ01ABF050 500GB              | 4         | 0.45%   |
| SK hynix HFM512GDJTNG-8310A 512GB     | 4         | 0.45%   |
| Samsung SSD 850 EVO 250GB             | 4         | 0.45%   |
| Samsung MZVLB1T0HBLR-000L2 1TB        | 4         | 0.45%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 4         | 0.45%   |
| HGST HTS545050A7E380 500GB            | 4         | 0.45%   |
| Crucial CT500MX500SSD1 500GB          | 4         | 0.45%   |
| Crucial CT480BX500SSD1 480GB          | 4         | 0.45%   |
| A-DATA SX8200PNP 1TB                  | 4         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 3         | 0.34%   |
| WDC WDBNCE5000PNC 500GB SSD           | 3         | 0.34%   |
| WDC WD10SPZX-80Z10T2 1TB              | 3         | 0.34%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 3         | 0.34%   |
| Toshiba MK7575GSX 752GB               | 3         | 0.34%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 3         | 0.34%   |
| Seagate ST9500325AS 500GB             | 3         | 0.34%   |
| Seagate ST9320325AS 320GB             | 3         | 0.34%   |
| Seagate ST9250315AS 250GB             | 3         | 0.34%   |
| Seagate Expansion 1TB                 | 3         | 0.34%   |
| SanDisk SSD U110 16GB                 | 3         | 0.34%   |
| SanDisk Extreme 55AE 2TB SSD          | 3         | 0.34%   |
| Samsung SSD 970 PRO 512GB             | 3         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB        | 3         | 0.34%   |
| Samsung SSD 970 EVO Plus 250GB        | 3         | 0.34%   |
| Samsung SSD 970 EVO 1TB               | 3         | 0.34%   |
| Samsung SSD 860 QVO 1TB               | 3         | 0.34%   |
| Samsung SSD 860 EVO 1TB               | 3         | 0.34%   |
| Samsung MZVLW256HEHP-000L7 256GB      | 3         | 0.34%   |
| Samsung MZNTY128HDHP-00000 128GB SSD  | 3         | 0.34%   |
| Samsung MZNLF128HCHP-00000 128GB SSD  | 3         | 0.34%   |
| Samsung MZALQ512HALU-000L2 512GB      | 3         | 0.34%   |
| PNY CS900 240GB SSD                   | 3         | 0.34%   |
| KIOXIA KBG40ZNS512G NVMe 512GB        | 3         | 0.34%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 0.34%   |
| Kingston RBUSNS8154P3256GJ3 256GB     | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 107    | 37.94%  |
| WDC                 | 60        | 72     | 23.72%  |
| Toshiba             | 50        | 57     | 19.76%  |
| HGST                | 24        | 27     | 9.49%   |
| Hitachi             | 13        | 14     | 5.14%   |
| Samsung Electronics | 3         | 3      | 1.19%   |
| Unknown             | 2         | 2      | 0.79%   |
| SABRENT             | 1         | 1      | 0.4%    |
| KESU                | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 2      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 90        | 115    | 27.36%  |
| Kingston            | 37        | 41     | 11.25%  |
| SanDisk             | 35        | 39     | 10.64%  |
| WDC                 | 29        | 32     | 8.81%   |
| Crucial             | 23        | 24     | 6.99%   |
| Apple               | 10        | 12     | 3.04%   |
| SK hynix            | 9         | 10     | 2.74%   |
| PNY                 | 9         | 11     | 2.74%   |
| Micron Technology   | 9         | 9      | 2.74%   |
| Intel               | 9         | 12     | 2.74%   |
| A-DATA Technology   | 8         | 9      | 2.43%   |
| Toshiba             | 7         | 9      | 2.13%   |
| LITEON              | 7         | 8      | 2.13%   |
| LITEONIT            | 6         | 6      | 1.82%   |
| SPCC                | 5         | 5      | 1.52%   |
| China               | 4         | 4      | 1.22%   |
| Transcend           | 3         | 3      | 0.91%   |
| KingSpec            | 3         | 3      | 0.91%   |
| Seagate             | 2         | 2      | 0.61%   |
| Plextor             | 2         | 2      | 0.61%   |
| Patriot             | 2         | 5      | 0.61%   |
| Mushkin             | 2         | 2      | 0.61%   |
| Lexar               | 2         | 2      | 0.61%   |
| Intenso             | 2         | 2      | 0.61%   |
| Goodram             | 2         | 4      | 0.61%   |
| XrayDisk            | 1         | 1      | 0.3%    |
| W800S               | 1         | 2      | 0.3%    |
| Unknown             | 1         | 1      | 0.3%    |
| Team                | 1         | 1      | 0.3%    |
| SSSTC               | 1         | 1      | 0.3%    |
| OCZ                 | 1         | 1      | 0.3%    |
| NGFF                | 1         | 1      | 0.3%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.3%    |
| KingFast            | 1         | 1      | 0.3%    |
| HS-SSD-C100         | 1         | 2      | 0.3%    |
| Dogfish             | 1         | 1      | 0.3%    |
| Corsair             | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 299       | 385    | 37%     |
| HDD     | 247       | 288    | 30.57%  |
| NVMe    | 240       | 296    | 29.7%   |
| MMC     | 17        | 25     | 2.1%    |
| Unknown | 5         | 6      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 469       | 636    | 61.71%  |
| NVMe | 236       | 291    | 31.05%  |
| SAS  | 38        | 48     | 5%      |
| MMC  | 17        | 25     | 2.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 325       | 413    | 59.41%  |
| 0.51-1.0   | 203       | 237    | 37.11%  |
| 1.01-2.0   | 14        | 18     | 2.56%   |
| 3.01-4.0   | 5         | 5      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 183       | 27.27%  |
| 251-500        | 160       | 23.85%  |
| 501-1000       | 105       | 15.65%  |
| 1001-2000      | 67        | 9.99%   |
| 51-100         | 40        | 5.96%   |
| Unknown        | 38        | 5.66%   |
| 1-20           | 30        | 4.47%   |
| More than 3000 | 27        | 4.02%   |
| 2001-3000      | 11        | 1.64%   |
| 21-50          | 10        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 207       | 29.87%  |
| 21-50          | 150       | 21.65%  |
| 101-250        | 110       | 15.87%  |
| 51-100         | 86        | 12.41%  |
| 251-500        | 50        | 7.22%   |
| Unknown        | 38        | 5.48%   |
| 501-1000       | 30        | 4.33%   |
| 1001-2000      | 11        | 1.59%   |
| More than 3000 | 10        | 1.44%   |
| 0              | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 5         | 5      | 5.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 5.21%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 3.13%   |
| Toshiba MQ01ABF050 500GB                       | 2         | 2      | 2.08%   |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 2.08%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 2.08%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 2.08%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 2.08%   |
| Seagate ST1000LX015-1U7172 1TB                 | 2         | 2      | 2.08%   |
| Seagate ST1000LM049-2GH172 1TB                 | 2         | 2      | 2.08%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 2.08%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 2.08%   |
| HGST HTS545050A7E680 500GB                     | 2         | 2      | 2.08%   |
| HGST HTS545050A7E380 500GB                     | 2         | 3      | 2.08%   |
| HGST HTS541010A9E680 1TB                       | 2         | 3      | 2.08%   |
| WDC WD6400BEVT-60A0RT0 640GB                   | 1         | 2      | 1.04%   |
| WDC WD5000L 500GB                              | 1         | 1      | 1.04%   |
| WDC WD5000BPVT-22HXZT1 500GB                   | 1         | 1      | 1.04%   |
| WDC WD5000BPKX-22HPJT0 500GB                   | 1         | 1      | 1.04%   |
| WDC WD3200BPVT-00JJ5T0 320GB                   | 1         | 1      | 1.04%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1         | 1      | 1.04%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 1.04%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.04%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 1.04%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 1.04%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 1.04%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD           | 1         | 1      | 1.04%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 1.04%   |
| Toshiba MQ01ACF050 500GB                       | 1         | 1      | 1.04%   |
| Toshiba MK7575GSX 752GB                        | 1         | 1      | 1.04%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 1.04%   |
| Toshiba MK5061GSYN 500GB                       | 1         | 1      | 1.04%   |
| Toshiba MK3261GSYN 320GB                       | 1         | 1      | 1.04%   |
| Toshiba MK1237GSX 120GB                        | 1         | 1      | 1.04%   |
| SSSTC CVB-8D128-HP 128GB SSD                   | 1         | 1      | 1.04%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 1.04%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 1.04%   |
| Seagate ST9500420AS 500GB                      | 1         | 2      | 1.04%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 1.04%   |
| Seagate ST9160314AS 160GB                      | 1         | 1      | 1.04%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 1.04%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 1.04%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.04%   |
| SanDisk SSD PLUS 1000GB                        | 1         | 1      | 1.04%   |
| SanDisk SSD i100 24GB                          | 1         | 1      | 1.04%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB    | 1         | 1      | 1.04%   |
| Samsung Electronics SSD 860 EVO 1TB            | 1         | 1      | 1.04%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB   | 1         | 1      | 1.04%   |
| Plextor PX-128M6S 128GB SSD                    | 1         | 1      | 1.04%   |
| Mushkin MKNSSDCR250GB-7-OEM                    | 1         | 1      | 1.04%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 1.04%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.04%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 1.04%   |
| LITEONIT LCT-512M3S 512GB SSD                  | 1         | 1      | 1.04%   |
| LITEONIT LAT-256M3S 256GB SSD                  | 1         | 1      | 1.04%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB           | 1         | 1      | 1.04%   |
| Kingston SUV500M8960G 960GB SSD                | 1         | 1      | 1.04%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 32     | 31.58%  |
| Toshiba             | 13        | 14     | 13.68%  |
| WDC                 | 12        | 13     | 12.63%  |
| HGST                | 10        | 12     | 10.53%  |
| Intel               | 4         | 5      | 4.21%   |
| SanDisk             | 3         | 3      | 3.16%   |
| Samsung Electronics | 3         | 3      | 3.16%   |
| Micron Technology   | 3         | 3      | 3.16%   |
| Hitachi             | 3         | 3      | 3.16%   |
| LITEONIT            | 2         | 2      | 2.11%   |
| Kingston            | 2         | 2      | 2.11%   |
| Crucial             | 2         | 2      | 2.11%   |
| SSSTC               | 1         | 1      | 1.05%   |
| SK hynix            | 1         | 1      | 1.05%   |
| Plextor             | 1         | 1      | 1.05%   |
| Mushkin             | 1         | 1      | 1.05%   |
| Lenovo              | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |
| A-DATA Technology   | 1         | 1      | 1.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 30        | 32     | 44.12%  |
| WDC     | 12        | 13     | 17.65%  |
| Toshiba | 12        | 13     | 17.65%  |
| HGST    | 10        | 12     | 14.71%  |
| Hitachi | 3         | 3      | 4.41%   |
| Apple   | 1         | 1      | 1.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 68        | 74     | 72.34%  |
| SSD  | 23        | 25     | 24.47%  |
| NVMe | 3         | 3      | 3.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB   | 1         | 1      | 25%     |
| Seagate ST9320325AS 320GB  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB   | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 507       | 723    | 69.74%  |
| Detected | 124       | 171    | 17.06%  |
| Malfunc  | 92        | 102    | 12.65%  |
| Failed   | 4         | 4      | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 469       | 58.99%  |
| Samsung Electronics            | 82        | 10.31%  |
| AMD                            | 75        | 9.43%   |
| SanDisk                        | 41        | 5.16%   |
| SK hynix                       | 31        | 3.9%    |
| KIOXIA                         | 16        | 2.01%   |
| Phison Electronics             | 13        | 1.64%   |
| Toshiba America Info Systems   | 12        | 1.51%   |
| Kingston Technology Company    | 12        | 1.51%   |
| Micron Technology              | 9         | 1.13%   |
| Silicon Motion                 | 5         | 0.63%   |
| Nvidia                         | 5         | 0.63%   |
| Micron/Crucial Technology      | 5         | 0.63%   |
| ADATA Technology               | 5         | 0.63%   |
| Union Memory (Shenzhen)        | 3         | 0.38%   |
| Lenovo                         | 3         | 0.38%   |
| Apple                          | 3         | 0.38%   |
| Lite-On Technology             | 2         | 0.25%   |
| Unknown                        | 1         | 0.13%   |
| Solid State Storage Technology | 1         | 0.13%   |
| Marvell Technology Group       | 1         | 0.13%   |
| ASMedia Technology             | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 82        | 10.02%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 74        | 9.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 50        | 6.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 49        | 5.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 44        | 5.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 37        | 4.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 37        | 4.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26        | 3.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 20        | 2.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 2.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 2.08%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 14        | 1.71%   |
| SK hynix Gold P31 SSD                                                            | 13        | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 13        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 1.59%   |
| Samsung NVMe SSD Controller 980                                                  | 12        | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 1.22%   |
| Micron Non-Volatile memory controller                                            | 9         | 1.1%    |
| Intel SSD 660P Series                                                            | 9         | 1.1%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 8         | 0.98%   |
| Phison E12 NVMe Controller                                                       | 8         | 0.98%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 8         | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.73%   |
| Samsung Apple PCIe SSD                                                           | 6         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 0.73%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.61%   |
| SK hynix BC511                                                                   | 5         | 0.61%   |
| SanDisk Non-Volatile memory controller                                           | 5         | 0.61%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 0.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.49%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.49%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.49%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.49%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.49%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.37%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.37%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 3         | 0.37%   |
| Micron/Crucial Non-Volatile memory controller                                    | 3         | 0.37%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.37%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.37%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.24%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.24%   |
| Samsung Electronics SATA controller                                              | 2         | 0.24%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.24%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 488       | 61.54%  |
| NVMe | 237       | 29.89%  |
| RAID | 54        | 6.81%   |
| IDE  | 14        | 1.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 542       | 83%     |
| AMD    | 111       | 17%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 20        | 3.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 19        | 2.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 17        | 2.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 17        | 2.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 17        | 2.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz               | 14        | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 13        | 1.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 11        | 1.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 10        | 1.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 9         | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 9         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 8         | 1.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 8         | 1.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 8         | 1.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 7         | 1.07%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 7         | 1.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 7         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 7         | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 7         | 1.07%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 7         | 1.07%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 6         | 0.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 6         | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 6         | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 6         | 0.92%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 6         | 0.92%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 6         | 0.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 5         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 5         | 0.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 5         | 0.77%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 5         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 5         | 0.77%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 5         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 5         | 0.77%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 5         | 0.77%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 4         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 4         | 0.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 4         | 0.61%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 4         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 0.61%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 4         | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.61%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 0.61%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 4         | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 4         | 0.61%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 4         | 0.61%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 4         | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 4         | 0.61%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 4         | 0.61%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz                | 3         | 0.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 3         | 0.46%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 3         | 0.46%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 3         | 0.46%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 3         | 0.46%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 3         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 3         | 0.46%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 3         | 0.46%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 3         | 0.46%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 202       | 30.93%  |
| Intel Core i5           | 201       | 30.78%  |
| Intel Core i3           | 43        | 6.58%   |
| AMD Ryzen 5             | 31        | 4.75%   |
| AMD Ryzen 7             | 29        | 4.44%   |
| Other                   | 24        | 3.68%   |
| Intel Pentium           | 18        | 2.76%   |
| Intel Core 2 Duo        | 18        | 2.76%   |
| Intel Celeron           | 16        | 2.45%   |
| AMD Ryzen 3             | 11        | 1.68%   |
| AMD A6                  | 8         | 1.23%   |
| AMD Ryzen 7 PRO         | 7         | 1.07%   |
| Intel Atom              | 5         | 0.77%   |
| AMD A12                 | 5         | 0.77%   |
| AMD A10                 | 5         | 0.77%   |
| Intel Pentium Dual-Core | 4         | 0.61%   |
| AMD Ryzen 9             | 4         | 0.61%   |
| Intel Pentium Silver    | 3         | 0.46%   |
| Intel Core m3           | 3         | 0.46%   |
| AMD A8                  | 3         | 0.46%   |
| AMD A4                  | 3         | 0.46%   |
| Intel Xeon              | 2         | 0.31%   |
| Intel Core i9           | 2         | 0.31%   |
| Intel Core 2            | 2         | 0.31%   |
| Intel Core m7           | 1         | 0.15%   |
| Intel Core M            | 1         | 0.15%   |
| AMD E2                  | 1         | 0.15%   |
| AMD Athlon II           | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 320       | 49%     |
| 4      | 227       | 34.76%  |
| 6      | 59        | 9.04%   |
| 8      | 42        | 6.43%   |
| 1      | 3         | 0.46%   |
| 14     | 1         | 0.15%   |
| 12     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 653       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 555       | 84.99%  |
| 1      | 98        | 15.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 652       | 99.85%  |
| Unknown        | 1         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 13.62%  |
| 0x206a7    | 47        | 7.11%   |
| 0x906ea    | 38        | 5.75%   |
| 0x806ea    | 37        | 5.6%    |
| 0x806e9    | 35        | 5.3%    |
| 0x406e3    | 35        | 5.3%    |
| 0x306c3    | 30        | 4.54%   |
| 0x306a9    | 30        | 4.54%   |
| 0x40651    | 24        | 3.63%   |
| 0x906e9    | 20        | 3.03%   |
| 0x806ec    | 19        | 2.87%   |
| 0x306d4    | 19        | 2.87%   |
| 0x20655    | 18        | 2.72%   |
| 0x08600106 | 16        | 2.42%   |
| 0xa0652    | 15        | 2.27%   |
| 0x806c1    | 14        | 2.12%   |
| 0x08108102 | 14        | 2.12%   |
| 0x706e5    | 11        | 1.66%   |
| 0x08108109 | 11        | 1.66%   |
| 0x30678    | 9         | 1.36%   |
| 0x1067a    | 9         | 1.36%   |
| 0x506e3    | 7         | 1.06%   |
| 0x10676    | 7         | 1.06%   |
| 0x08600103 | 7         | 1.06%   |
| 0x806eb    | 6         | 0.91%   |
| 0x0a50000c | 6         | 0.91%   |
| 0x0810100b | 6         | 0.91%   |
| 0x06006705 | 6         | 0.91%   |
| 0x806d1    | 5         | 0.76%   |
| 0x706a8    | 5         | 0.76%   |
| 0x20652    | 5         | 0.76%   |
| 0x106e5    | 5         | 0.76%   |
| 0x08600104 | 5         | 0.76%   |
| 0x406c4    | 4         | 0.61%   |
| 0x40661    | 4         | 0.61%   |
| 0x0a50000b | 4         | 0.61%   |
| 0x0600611a | 4         | 0.61%   |
| 0x406c3    | 3         | 0.45%   |
| 0x106ca    | 3         | 0.45%   |
| 0x08608103 | 3         | 0.45%   |
| 0x06006118 | 3         | 0.45%   |
| 0x906ed    | 2         | 0.3%    |
| 0x706a1    | 2         | 0.3%    |
| 0x506c9    | 2         | 0.3%    |
| 0x07030105 | 2         | 0.3%    |
| 0x06006704 | 2         | 0.3%    |
| 0x906c0    | 1         | 0.15%   |
| 0x906a3    | 1         | 0.15%   |
| 0x6fd      | 1         | 0.15%   |
| 0x6fb      | 1         | 0.15%   |
| 0x6f6      | 1         | 0.15%   |
| 0x08701013 | 1         | 0.15%   |
| 0x08101007 | 1         | 0.15%   |
| 0x08101004 | 1         | 0.15%   |
| 0x06006110 | 1         | 0.15%   |
| 0x06001119 | 1         | 0.15%   |
| 0x06001116 | 1         | 0.15%   |
| 0x010000b6 | 1         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 180       | 27.52%  |
| Haswell          | 63        | 9.63%   |
| SandyBridge      | 53        | 8.1%    |
| Skylake          | 49        | 7.49%   |
| IvyBridge        | 39        | 5.96%   |
| Zen 2            | 30        | 4.59%   |
| Zen+             | 28        | 4.28%   |
| Westmere         | 28        | 4.28%   |
| Broadwell        | 22        | 3.36%   |
| Excavator        | 21        | 3.21%   |
| Penryn           | 19        | 2.91%   |
| Silvermont       | 17        | 2.6%    |
| CometLake        | 17        | 2.6%    |
| IceLake          | 16        | 2.45%   |
| TigerLake        | 15        | 2.29%   |
| Zen 3            | 13        | 1.99%   |
| Zen              | 8         | 1.22%   |
| Goldmont plus    | 7         | 1.07%   |
| Nehalem          | 5         | 0.76%   |
| Core             | 5         | 0.76%   |
| Unknown          | 4         | 0.61%   |
| Puma             | 3         | 0.46%   |
| Piledriver       | 3         | 0.46%   |
| Bonnell          | 3         | 0.46%   |
| Goldmont         | 2         | 0.31%   |
| Tremont          | 1         | 0.15%   |
| K10              | 1         | 0.15%   |
| Jaguar           | 1         | 0.15%   |
| Alderlake Hybrid | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 500       | 56.82%  |
| Nvidia | 239       | 27.16%  |
| AMD    | 141       | 16.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 5.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 4.89%   |
| Intel UHD Graphics 620                                                                   | 37        | 4.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 4.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 4%      |
| Intel HD Graphics 620                                                                    | 34        | 3.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 3.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 3.11%   |
| AMD Renoir                                                                               | 26        | 2.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 2.78%   |
| Intel HD Graphics 630                                                                    | 22        | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 2.44%   |
| Intel HD Graphics 5500                                                                   | 19        | 2.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 12        | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.22%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 1.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.11%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 1.11%   |
| AMD Cezanne                                                                              | 10        | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1%      |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.78%   |
| Intel HD Graphics 530                                                                    | 7         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.67%   |
| Nvidia GM108M [GeForce MX110]                                                            | 6         | 0.67%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 6         | 0.67%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 5         | 0.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.56%   |
| Nvidia TU117M                                                                            | 4         | 0.44%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.44%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.44%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.44%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.44%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 4         | 0.44%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 3         | 0.33%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.33%   |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.33%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.33%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.33%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 292       | 44.65%  |
| Intel + Nvidia | 178       | 27.22%  |
| 1 x AMD        | 81        | 12.39%  |
| 1 x Nvidia     | 41        | 6.27%   |
| Intel + AMD    | 28        | 4.28%   |
| AMD + Nvidia   | 19        | 2.91%   |
| 2 x AMD        | 13        | 1.99%   |
| 2 x Nvidia     | 1         | 0.15%   |
| 2 x Intel      | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 520       | 79.15%  |
| Proprietary | 128       | 19.48%  |
| Unknown     | 9         | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 68.93%  |
| 1.01-2.0   | 64        | 9.65%   |
| 0.01-0.5   | 62        | 9.35%   |
| 0.51-1.0   | 33        | 4.98%   |
| 3.01-4.0   | 26        | 3.92%   |
| 5.01-6.0   | 13        | 1.96%   |
| 7.01-8.0   | 4         | 0.6%    |
| 2.01-3.0   | 3         | 0.45%   |
| 8.01-16.0  | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 142       | 18.39%  |
| AU Optronics            | 131       | 16.97%  |
| Chimei Innolux          | 113       | 14.64%  |
| BOE                     | 99        | 12.82%  |
| Samsung Electronics     | 52        | 6.74%   |
| Sharp                   | 26        | 3.37%   |
| Dell                    | 25        | 3.24%   |
| Goldstar                | 22        | 2.85%   |
| Apple                   | 22        | 2.85%   |
| Lenovo                  | 19        | 2.46%   |
| PANDA                   | 11        | 1.42%   |
| Hewlett-Packard         | 10        | 1.3%    |
| BenQ                    | 9         | 1.17%   |
| Chi Mei Optoelectronics | 8         | 1.04%   |
| AOC                     | 7         | 0.91%   |
| Philips                 | 6         | 0.78%   |
| CSO                     | 6         | 0.78%   |
| Sony                    | 5         | 0.65%   |
| Panasonic               | 5         | 0.65%   |
| Acer                    | 5         | 0.65%   |
| InfoVision              | 4         | 0.52%   |
| Ancor Communications    | 4         | 0.52%   |
| ASUSTek Computer        | 3         | 0.39%   |
| ViewSonic               | 2         | 0.26%   |
| Sceptre Tech            | 2         | 0.26%   |
| Medion                  | 2         | 0.26%   |
| LG Philips              | 2         | 0.26%   |
| InnoLux Display         | 2         | 0.26%   |
| Iiyama                  | 2         | 0.26%   |
| Eizo                    | 2         | 0.26%   |
| CPT                     | 2         | 0.26%   |
| Westinghouse            | 1         | 0.13%   |
| VIE                     | 1         | 0.13%   |
| Seiki                   | 1         | 0.13%   |
| RGT                     | 1         | 0.13%   |
| PRO                     | 1         | 0.13%   |
| Philco                  | 1         | 0.13%   |
| Packard Bell            | 1         | 0.13%   |
| NCS                     | 1         | 0.13%   |
| MStar                   | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| Mi                      | 1         | 0.13%   |
| LPL                     | 1         | 0.13%   |
| LGD                     | 1         | 0.13%   |
| JRY                     | 1         | 0.13%   |
| JDI                     | 1         | 0.13%   |
| Insignia                | 1         | 0.13%   |
| Hyundai ImageQuest      | 1         | 0.13%   |
| Hitachi                 | 1         | 0.13%   |
| HannStar                | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| Daewoo                  | 1         | 0.13%   |
| Belinea                 | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 1.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 10        | 1.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 8         | 1.03%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.91%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 6         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 6         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 5         | 0.65%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 5         | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 5         | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 5         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 5         | 0.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 5         | 0.65%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 4         | 0.52%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch     | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 4         | 0.52%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 4         | 0.52%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 4         | 0.52%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 4         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 3         | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.39%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 3         | 0.39%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 3         | 0.39%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 3         | 0.39%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch         | 3         | 0.39%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 3         | 0.39%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 3         | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 3         | 0.39%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 3         | 0.39%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 3         | 0.39%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 3         | 0.39%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                | 3         | 0.39%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch               | 2         | 0.26%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch              | 2         | 0.26%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch              | 2         | 0.26%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch    | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 357       | 50.07%  |
| 1366x768 (WXGA)    | 176       | 24.68%  |
| 1600x900 (HD+)     | 37        | 5.19%   |
| 3840x2160 (4K)     | 24        | 3.37%   |
| 1280x800 (WXGA)    | 21        | 2.95%   |
| 2560x1440 (QHD)    | 19        | 2.66%   |
| 2880x1800          | 10        | 1.4%    |
| 1920x1200 (WUXGA)  | 10        | 1.4%    |
| 1440x900 (WXGA+)   | 9         | 1.26%   |
| 2560x1600          | 7         | 0.98%   |
| 2560x1080          | 7         | 0.98%   |
| 2160x1440          | 6         | 0.84%   |
| 1280x1024 (SXGA)   | 6         | 0.84%   |
| 3200x1800 (QHD+)   | 5         | 0.7%    |
| 1680x1050 (WSXGA+) | 4         | 0.56%   |
| 3840x2400          | 3         | 0.42%   |
| 3440x1440          | 3         | 0.42%   |
| 1920x540           | 2         | 0.28%   |
| 1360x768           | 2         | 0.28%   |
| 1024x600           | 2         | 0.28%   |
| 3840x1600          | 1         | 0.14%   |
| 3000x2000          | 1         | 0.14%   |
| 2160x1350          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 321       | 41.8%   |
| 14      | 103       | 13.41%  |
| 13      | 99        | 12.89%  |
| 17      | 69        | 8.98%   |
| 24      | 25        | 3.26%   |
| 23      | 25        | 3.26%   |
| 12      | 25        | 3.26%   |
| 27      | 24        | 3.13%   |
| 21      | 19        | 2.47%   |
| 34      | 9         | 1.17%   |
| 19      | 6         | 0.78%   |
| 11      | 6         | 0.78%   |
| 18      | 5         | 0.65%   |
| Unknown | 5         | 0.65%   |
| 31      | 4         | 0.52%   |
| 22      | 4         | 0.52%   |
| 54      | 3         | 0.39%   |
| 16      | 3         | 0.39%   |
| 84      | 2         | 0.26%   |
| 10      | 2         | 0.26%   |
| 72      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 47      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 35      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 466       | 61.24%  |
| 201-300     | 87        | 11.43%  |
| 351-400     | 74        | 9.72%   |
| 501-600     | 70        | 9.2%    |
| 401-500     | 31        | 4.07%   |
| 701-800     | 10        | 1.31%   |
| 1001-1500   | 7         | 0.92%   |
| 601-700     | 5         | 0.66%   |
| Unknown     | 5         | 0.66%   |
| 801-900     | 3         | 0.39%   |
| 1501-2000   | 3         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 579       | 85.65%  |
| 16/10   | 64        | 9.47%   |
| 3/2     | 12        | 1.78%   |
| 21/9    | 11        | 1.63%   |
| 5/4     | 4         | 0.59%   |
| Unknown | 3         | 0.44%   |
| 6/5     | 2         | 0.3%    |
| 4/3     | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 315       | 41.12%  |
| 81-90          | 159       | 20.76%  |
| 121-130        | 64        | 8.36%   |
| 201-250        | 62        | 8.09%   |
| 71-80          | 44        | 5.74%   |
| 301-350        | 24        | 3.13%   |
| 61-70          | 21        | 2.74%   |
| 351-500        | 16        | 2.09%   |
| More than 1000 | 9         | 1.17%   |
| 151-200        | 8         | 1.04%   |
| 141-150        | 8         | 1.04%   |
| 251-300        | 7         | 0.91%   |
| 91-100         | 7         | 0.91%   |
| 51-60          | 6         | 0.78%   |
| Unknown        | 5         | 0.65%   |
| 131-140        | 4         | 0.52%   |
| 111-120        | 3         | 0.39%   |
| 41-50          | 2         | 0.26%   |
| 501-1000       | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 354       | 46.89%  |
| 101-120       | 203       | 26.89%  |
| 51-100        | 105       | 13.91%  |
| 161-240       | 58        | 7.68%   |
| More than 240 | 22        | 2.91%   |
| 1-50          | 8         | 1.06%   |
| Unknown       | 5         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 530       | 79.58%  |
| 2     | 112       | 16.82%  |
| 3     | 13        | 1.95%   |
| 0     | 11        | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 383       | 38.11%  |
| Realtek Semiconductor             | 349       | 34.73%  |
| Qualcomm Atheros                  | 147       | 14.63%  |
| Broadcom                          | 47        | 4.68%   |
| Broadcom Limited                  | 12        | 1.19%   |
| Dell                              | 7         | 0.7%    |
| Sierra Wireless                   | 6         | 0.6%    |
| TP-Link                           | 5         | 0.5%    |
| MediaTek                          | 5         | 0.5%    |
| Marvell Technology Group          | 5         | 0.5%    |
| Ralink                            | 4         | 0.4%    |
| Nvidia                            | 4         | 0.4%    |
| ASIX Electronics                  | 4         | 0.4%    |
| Samsung Electronics               | 3         | 0.3%    |
| Lenovo                            | 3         | 0.3%    |
| Ericsson Business Mobile Networks | 3         | 0.3%    |
| Ralink Technology                 | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| Hewlett-Packard                   | 2         | 0.2%    |
| Xiaomi                            | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| NetGear                           | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Microsoft                         | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| Google                            | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| ASUSTek Computer                  | 1         | 0.1%    |
| Apple                             | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 248       | 19.92%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 50        | 4.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49        | 3.94%   |
| Intel Wireless 8265 / 8275                                        | 40        | 3.21%   |
| Intel Wi-Fi 6 AX200                                               | 38        | 3.05%   |
| Intel Wireless 7260                                               | 31        | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31        | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 2.01%   |
| Intel Wireless 8260                                               | 25        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 1.77%   |
| Intel Wireless 7265                                               | 18        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.2%    |
| Intel Wireless 3165                                               | 15        | 1.2%    |
| Intel Centrino Ultimate-N 6300                                    | 15        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 9         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.72%   |
| Intel Wireless-AC 9260                                            | 9         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 9         | 0.72%   |
| Intel Centrino Advanced-N 6200                                    | 9         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 7         | 0.56%   |
| Intel Wireless 3160                                               | 7         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.4%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 5         | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.32%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.32%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.32%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.32%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.32%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.32%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 372       | 55.52%  |
| Qualcomm Atheros                | 126       | 18.81%  |
| Realtek Semiconductor           | 98        | 14.63%  |
| Broadcom                        | 36        | 5.37%   |
| Broadcom Limited                | 9         | 1.34%   |
| Sierra Wireless                 | 6         | 0.9%    |
| MediaTek                        | 5         | 0.75%   |
| TP-Link                         | 4         | 0.6%    |
| Ralink                          | 4         | 0.6%    |
| Dell                            | 3         | 0.45%   |
| Ralink Technology               | 2         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.15%   |
| NetGear                         | 1         | 0.15%   |
| Microsoft                       | 1         | 0.15%   |
| Fibocom                         | 1         | 0.15%   |
| ASUSTek Computer                | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 50        | 7.44%   |
| Intel Wireless 8265 / 8275                                     | 40        | 5.95%   |
| Intel Wi-Fi 6 AX200                                            | 38        | 5.65%   |
| Intel Wireless 7260                                            | 31        | 4.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31        | 4.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 3.87%   |
| Intel Wireless 8260                                            | 25        | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 3.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 3.27%   |
| Intel Wireless 7265                                            | 18        | 2.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.23%   |
| Intel Wireless 3165                                            | 15        | 2.23%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 2.08%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.49%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 9         | 1.34%   |
| Intel Wireless-AC 9260                                         | 9         | 1.34%   |
| Intel Centrino Advanced-N 6235                                 | 9         | 1.34%   |
| Intel Centrino Advanced-N 6200                                 | 9         | 1.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 1.04%   |
| Intel Wireless 3160                                            | 7         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.6%    |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.6%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.6%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 0.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 0.6%    |
| Sierra Wireless EM7455                                         | 3         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.45%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 0.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.45%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.3%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 2         | 0.3%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.3%    |
| Intel WiFi Link 5100                                           | 2         | 0.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.3%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.3%    |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]           | 2         | 0.3%    |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 2         | 0.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 322       | 58.33%  |
| Intel                    | 146       | 26.45%  |
| Qualcomm Atheros         | 36        | 6.52%   |
| Broadcom                 | 17        | 3.08%   |
| Marvell Technology Group | 5         | 0.91%   |
| Nvidia                   | 4         | 0.72%   |
| ASIX Electronics         | 4         | 0.72%   |
| Samsung Electronics      | 3         | 0.54%   |
| Lenovo                   | 3         | 0.54%   |
| Broadcom Limited         | 3         | 0.54%   |
| Xiaomi                   | 1         | 0.18%   |
| TP-Link                  | 1         | 0.18%   |
| Qualcomm                 | 1         | 0.18%   |
| Motorola PCS             | 1         | 0.18%   |
| MediaTek                 | 1         | 0.18%   |
| JMicron Technology       | 1         | 0.18%   |
| Google                   | 1         | 0.18%   |
| DisplayLink              | 1         | 0.18%   |
| Apple                    | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 248       | 44.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 49        | 8.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 31        | 5.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 25        | 4.45%   |
| Intel Ethernet Connection I217-LM                                              | 17        | 3.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 2.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 1.6%    |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.6%    |
| Intel Ethernet Connection I218-LM                                              | 9         | 1.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 9         | 1.6%    |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                                          | 7         | 1.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 1.07%   |
| Intel Ethernet Connection I219-V                                               | 6         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.71%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.71%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.53%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.36%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.36%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.36%   |
| Intel Ethernet controller                                                      | 2         | 0.36%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.36%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.36%   |
| Intel Ethernet Connection (5) I219-V                                           | 2         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.36%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.36%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.36%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.36%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.18%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.18%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.18%   |
| Qualcomm Android                                                               | 1         | 0.18%   |
| Motorola PCS moto g(9) play                                                    | 1         | 0.18%   |
| MediaTek moto e(6) plus                                                        | 1         | 0.18%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.18%   |
| Lenovo VIBEUI                                                                  | 1         | 0.18%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.18%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 648       | 54.23%  |
| Ethernet | 536       | 44.85%  |
| Modem    | 11        | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 552       | 80.47%  |
| Ethernet | 134       | 19.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 498       | 76.15%  |
| 1     | 145       | 22.17%  |
| 3     | 9         | 1.38%   |
| 0     | 2         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 524       | 79.27%  |
| Yes  | 137       | 20.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 286       | 51.25%  |
| Realtek Semiconductor           | 65        | 11.65%  |
| Qualcomm Atheros Communications | 52        | 9.32%   |
| IMC Networks                    | 30        | 5.38%   |
| Lite-On Technology              | 29        | 5.2%    |
| Broadcom                        | 29        | 5.2%    |
| Apple                           | 21        | 3.76%   |
| Foxconn / Hon Hai               | 17        | 3.05%   |
| Dell                            | 9         | 1.61%   |
| Cambridge Silicon Radio         | 6         | 1.08%   |
| Toshiba                         | 3         | 0.54%   |
| ASUSTek Computer                | 3         | 0.54%   |
| Realtek                         | 2         | 0.36%   |
| Hewlett-Packard                 | 2         | 0.36%   |
| Ralink Technology               | 1         | 0.18%   |
| Ralink                          | 1         | 0.18%   |
| Dynex                           | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 130       | 23.3%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 46        | 8.24%   |
| Intel AX201 Bluetooth                                                               | 41        | 7.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 40        | 7.17%   |
| Intel AX200 Bluetooth                                                               | 36        | 6.45%   |
| Realtek Bluetooth Radio                                                             | 34        | 6.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 3.58%   |
| Apple Bluetooth Host Controller                                                     | 17        | 3.05%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 15        | 2.69%   |
| Intel Bluetooth Device                                                              | 14        | 2.51%   |
| Lite-On Bluetooth Device                                                            | 13        | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 2.15%   |
| IMC Networks Bluetooth Device                                                       | 12        | 2.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.79%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.08%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 1.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.08%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.72%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.54%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.54%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.54%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.54%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.36%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.36%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.36%   |
| IMC Networks BCM20702A0                                                             | 2         | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.36%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.36%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.36%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.36%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.36%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.36%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.18%   |
| Realtek CSR BS8510                                                                  | 1         | 0.18%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.18%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.18%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.18%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.18%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.18%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.18%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.18%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.18%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.18%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.18%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.18%   |
| Broadcom Bluetooth                                                                  | 1         | 0.18%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.18%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.18%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.18%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 1         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 535       | 63.46%  |
| Nvidia                    | 142       | 16.84%  |
| AMD                       | 120       | 14.23%  |
| Realtek Semiconductor     | 5         | 0.59%   |
| Logitech                  | 5         | 0.59%   |
| Lenovo                    | 3         | 0.36%   |
| Kingston Technology       | 3         | 0.36%   |
| GN Netcom                 | 3         | 0.36%   |
| C-Media Electronics       | 3         | 0.36%   |
| BEHRINGER International   | 3         | 0.36%   |
| Generalplus Technology    | 2         | 0.24%   |
| Focusrite-Novation        | 2         | 0.24%   |
| VIA Technologies          | 1         | 0.12%   |
| USB-MIC                   | 1         | 0.12%   |
| Texas Instruments         | 1         | 0.12%   |
| SteelSeries ApS           | 1         | 0.12%   |
| Sony                      | 1         | 0.12%   |
| Sennheiser Communications | 1         | 0.12%   |
| Samsung Electronics       | 1         | 0.12%   |
| Samson Technologies       | 1         | 0.12%   |
| No brand                  | 1         | 0.12%   |
| Microchip Technology      | 1         | 0.12%   |
| Mark of the Unicorn       | 1         | 0.12%   |
| LG Electronics            | 1         | 0.12%   |
| JMTek                     | 1         | 0.12%   |
| Dell                      | 1         | 0.12%   |
| Corsair                   | 1         | 0.12%   |
| Barco Display Systems     | 1         | 0.12%   |
| Asahi Kasei Microsystems  | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 118       | 11.67%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 80        | 7.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 49        | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 46        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 46        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 37        | 3.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 33        | 3.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 3.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 31        | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 2.47%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 2.47%   |
| Intel CM238 HD Audio Controller                                                                   | 24        | 2.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 2.18%   |
| Intel Broadwell-U Audio Controller                                                                | 22        | 2.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 1.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 1.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.09%   |
| AMD High Definition Audio Controller                                                              | 11        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.69%   |
| AMD FCH Azalia Controller                                                                         | 7         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.49%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.49%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.4%    |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.3%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.3%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.3%    |
| Intel Crystal Well HD Audio Controller                                                            | 3         | 0.3%    |
| BEHRINGER International UMC404HD 192k                                                             | 3         | 0.3%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.3%    |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 2         | 0.2%    |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.2%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.2%    |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.2%    |
| Nvidia Audio device                                                                               | 2         | 0.2%    |
| Logitech 960 Headset                                                                              | 2         | 0.2%    |
| Kingston Technology HyperX 7.1 Audio                                                              | 2         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 228       | 32.29%  |
| SK hynix            | 167       | 23.65%  |
| Micron Technology   | 81        | 11.47%  |
| Kingston            | 64        | 9.07%   |
| Crucial             | 37        | 5.24%   |
| Unknown             | 30        | 4.25%   |
| Ramaxel Technology  | 15        | 2.12%   |
| Elpida              | 12        | 1.7%    |
| Nanya Technology    | 11        | 1.56%   |
| A-DATA Technology   | 10        | 1.42%   |
| Corsair             | 6         | 0.85%   |
| Team                | 4         | 0.57%   |
| Patriot             | 4         | 0.57%   |
| Avant               | 3         | 0.42%   |
| Apacer              | 3         | 0.42%   |
| Unknown             | 3         | 0.42%   |
| Unknown (ABCD)      | 2         | 0.28%   |
| Transcend           | 2         | 0.28%   |
| Silicon Power       | 2         | 0.28%   |
| Neo Forza           | 2         | 0.28%   |
| Goodram             | 2         | 0.28%   |
| Goldkey             | 2         | 0.28%   |
| G.Skill             | 2         | 0.28%   |
| ASint Technology    | 2         | 0.28%   |
| Unknown (898F)      | 1         | 0.14%   |
| Unknown (0x8634)    | 1         | 0.14%   |
| Unknown (0x8319)    | 1         | 0.14%   |
| Unknown (09D5)      | 1         | 0.14%   |
| Sesame              | 1         | 0.14%   |
| Saikano             | 1         | 0.14%   |
| PNY                 | 1         | 0.14%   |
| EUDAR               | 1         | 0.14%   |
| DSL                 | 1         | 0.14%   |
| CSX                 | 1         | 0.14%   |
| AMD                 | 1         | 0.14%   |
| 48spaces            | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 17        | 2.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 15        | 1.99%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 15        | 1.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 12        | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 11        | 1.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 11        | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 9         | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 9         | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 9         | 1.19%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 8         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 8         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 8         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 8         | 1.06%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 8         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 7         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 7         | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 7         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 6         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 6         | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 6         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 5         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 5         | 0.66%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 5         | 0.66%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 5         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 4         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 4         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.53%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 4         | 0.53%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s   | 4         | 0.53%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 4         | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s    | 4         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 4         | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 0.53%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 4         | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s    | 4         | 0.53%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.53%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                   | 4         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.53%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 4         | 0.53%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 4         | 0.53%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 4         | 0.53%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 4         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 3         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 3         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 3         | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.4%    |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s    | 3         | 0.4%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 3         | 0.4%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 3         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 0.4%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 3         | 0.4%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s         | 3         | 0.4%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 0.4%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 3         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 307       | 52.75%  |
| DDR3    | 215       | 36.94%  |
| LPDDR3  | 26        | 4.47%   |
| LPDDR4  | 16        | 2.75%   |
| DDR2    | 8         | 1.37%   |
| SDRAM   | 7         | 1.2%    |
| Unknown | 3         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 538       | 91.65%  |
| Row Of Chips | 40        | 6.81%   |
| Chip         | 8         | 1.36%   |
| DIMM         | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 259       | 40.79%  |
| 4096  | 230       | 36.22%  |
| 16384 | 70        | 11.02%  |
| 2048  | 57        | 8.98%   |
| 32768 | 12        | 1.89%   |
| 1024  | 6         | 0.94%   |
| 64    | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 164       | 25.23%  |
| 1600    | 162       | 24.92%  |
| 3200    | 90        | 13.85%  |
| 2400    | 66        | 10.15%  |
| 2133    | 38        | 5.85%   |
| 1334    | 30        | 4.62%   |
| 1333    | 20        | 3.08%   |
| 3266    | 15        | 2.31%   |
| 1067    | 14        | 2.15%   |
| 1867    | 12        | 1.85%   |
| Unknown | 7         | 1.08%   |
| 4267    | 6         | 0.92%   |
| 667     | 5         | 0.77%   |
| 4199    | 4         | 0.62%   |
| 8400    | 3         | 0.46%   |
| 975     | 3         | 0.46%   |
| 800     | 3         | 0.46%   |
| 2048    | 2         | 0.31%   |
| 4800    | 1         | 0.15%   |
| 3733    | 1         | 0.15%   |
| 3000    | 1         | 0.15%   |
| 1776    | 1         | 0.15%   |
| 1639    | 1         | 0.15%   |
| 1066    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MIIIW              | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini  | 1         | 33.33%  |
| Canon G2000 series          | 1         | 33.33%  |
| Brother MFC-L3770CDW series | 1         | 33.33%  |

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
| Chicony Electronics                    | 170       | 28.19%  |
| IMC Networks                           | 78        | 12.94%  |
| Acer                                   | 60        | 9.95%   |
| Realtek Semiconductor                  | 56        | 9.29%   |
| Microdia                               | 48        | 7.96%   |
| Sunplus Innovation Technology          | 29        | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 4.31%   |
| Quanta                                 | 24        | 3.98%   |
| Apple                                  | 18        | 2.99%   |
| Syntek                                 | 14        | 2.32%   |
| Lite-On Technology                     | 13        | 2.16%   |
| Suyin                                  | 12        | 1.99%   |
| Logitech                               | 10        | 1.66%   |
| Lenovo                                 | 9         | 1.49%   |
| Silicon Motion                         | 7         | 1.16%   |
| Primax Electronics                     | 5         | 0.83%   |
| Luxvisions Innotech Limited            | 5         | 0.83%   |
| Samsung Electronics                    | 4         | 0.66%   |
| Importek                               | 3         | 0.5%    |
| Sunplus Technology                     | 2         | 0.33%   |
| Generalplus Technology                 | 2         | 0.33%   |
| Alcor Micro                            | 2         | 0.33%   |
| WaveRider Communications               | 1         | 0.17%   |
| Sonix Technology                       | 1         | 0.17%   |
| Ricoh                                  | 1         | 0.17%   |
| Microsoft                              | 1         | 0.17%   |
| Creative Technology                    | 1         | 0.17%   |
| ARC International                      | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 48        | 7.91%   |
| Realtek Integrated_Webcam_HD                                   | 23        | 3.79%   |
| Microdia Integrated_Webcam_HD                                  | 22        | 3.62%   |
| IMC Networks Integrated Camera                                 | 22        | 3.62%   |
| Chicony HD WebCam                                              | 21        | 3.46%   |
| Acer Integrated Camera                                         | 18        | 2.97%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 16        | 2.64%   |
| Lite-On Integrated Camera                                      | 10        | 1.65%   |
| Chicony USB2.0 Camera                                          | 10        | 1.65%   |
| Sunplus Integrated_Webcam_HD                                   | 9         | 1.48%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 9         | 1.48%   |
| Acer EasyCamera                                                | 9         | 1.48%   |
| Syntek Integrated Camera                                       | 8         | 1.32%   |
| Microdia Integrated Webcam                                     | 8         | 1.32%   |
| Chicony HP Truevision HD                                       | 8         | 1.32%   |
| Quanta HD Webcam                                               | 7         | 1.15%   |
| Lenovo Integrated Webcam [R5U877]                              | 6         | 0.99%   |
| IMC Networks Lenovo EasyCamera                                 | 6         | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 6         | 0.99%   |
| Apple Built-in iSight                                          | 6         | 0.99%   |
| Acer BisonCam,NB Pro                                           | 6         | 0.99%   |
| Quanta HD User Facing                                          | 5         | 0.82%   |
| IMC Networks VGA UVC WebCam                                    | 5         | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 0.82%   |
| Chicony HP TrueVision HD Camera                                | 5         | 0.82%   |
| Chicony HP HD Camera                                           | 5         | 0.82%   |
| Chicony EasyCamera                                             | 5         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 5         | 0.82%   |
| Apple FaceTime HD Camera                                       | 5         | 0.82%   |
| Acer SunplusIT Integrated Camera                               | 5         | 0.82%   |
| Acer HD Webcam                                                 | 5         | 0.82%   |
| Samsung Galaxy A5 (MTP)                                        | 4         | 0.66%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 4         | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 4         | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 0.66%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 4         | 0.66%   |
| Chicony HP HD Webcam                                           | 4         | 0.66%   |
| Chicony FJ Camera                                              | 4         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.66%   |
| Acer Lenovo EasyCamera                                         | 4         | 0.66%   |
| Syntek EasyCamera                                              | 3         | 0.49%   |
| Sunplus Laptop Integrated Webcam HD                            | 3         | 0.49%   |
| Sunplus HD Webcam                                              | 3         | 0.49%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.49%   |
| Realtek Integrated Webcam_HD                                   | 3         | 0.49%   |
| Realtek Integrated Webcam HD                                   | 3         | 0.49%   |
| Realtek Integrated Webcam                                      | 3         | 0.49%   |
| Realtek HD WebCam                                              | 3         | 0.49%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 0.49%   |
| Primax HP HD Webcam [Fixed]                                    | 3         | 0.49%   |
| Microdia Dell Integrated HD Webcam                             | 3         | 0.49%   |
| Logitech HD Pro Webcam C920                                    | 3         | 0.49%   |
| Lenovo Integrated Webcam                                       | 3         | 0.49%   |
| IMC Networks USB Camera                                        | 3         | 0.49%   |
| IMC Networks EasyCamera                                        | 3         | 0.49%   |
| Chicony USB 2.0 Camera                                         | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 44.07%  |
| Synaptics                  | 21        | 17.8%   |
| Shenzhen Goodix Technology | 17        | 14.41%  |
| Upek                       | 8         | 6.78%   |
| Elan Microelectronics      | 7         | 5.93%   |
| LighTuning Technology      | 6         | 5.08%   |
| AuthenTec                  | 6         | 5.08%   |
| STMicroelectronics         | 1         | 0.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 12.71%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 8.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 7.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.78%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 6.78%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 5.93%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 5.93%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.24%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.24%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.39%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.54%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.69%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.69%   |
| Synaptics WBDI Device                                                      | 2         | 1.69%   |
| Synaptics  WBDI                                                            | 2         | 1.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.69%   |
| AuthenTec AES1600                                                          | 2         | 1.69%   |
| Validity Sensors VFS491                                                    | 1         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.85%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.85%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.85%   |
| AuthenTec AES2810                                                          | 1         | 0.85%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.85%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.85%   |
| Unknown                                                                    | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 43.4%   |
| Alcor Micro | 19        | 35.85%  |
| O2 Micro    | 5         | 9.43%   |
| Lenovo      | 4         | 7.55%   |
| Upek        | 2         | 3.77%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 35.85%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 11.32%  |
| Broadcom 5880                                                                | 5         | 9.43%   |
| Broadcom 58200                                                               | 5         | 9.43%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.77%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 417       | 62.61%  |
| 1     | 193       | 28.98%  |
| 2     | 53        | 7.96%   |
| 3     | 3         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 117       | 39%     |
| Graphics card         | 66        | 22%     |
| Chipcard              | 53        | 17.67%  |
| Net/wireless          | 23        | 7.67%   |
| Multimedia controller | 17        | 5.67%   |
| Camera                | 15        | 5%      |
| Network               | 2         | 0.67%   |
| Card reader           | 2         | 0.67%   |
| Bluetooth             | 2         | 0.67%   |
| Storage               | 1         | 0.33%   |
| Net/ethernet          | 1         | 0.33%   |
| Dvb card              | 1         | 0.33%   |

