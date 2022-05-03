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

Total: 852

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| System76      | Oryx Pro                    | [7f83049cd5](https://linux-hardware.org/?probe=7f83049cd5) | Apr 19, 2022 |
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
| System76      | Oryx Pro                    | [0e42cf4c00](https://linux-hardware.org/?probe=0e42cf4c00) | Apr 01, 2022 |
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
| ASUSTek       | ROG Strix G513IC_G513IC     | [45e459af5a](https://linux-hardware.org/?probe=45e459af5a) | Mar 01, 2022 |
| Apple         | MacBookPro11,2              | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [9bac80064d](https://linux-hardware.org/?probe=9bac80064d) | Feb 26, 2022 |
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
| HUAWEI        | KLVL-WXX9                   | [b9dfe5b842](https://linux-hardware.org/?probe=b9dfe5b842) | Jan 21, 2022 |
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
| ASUSTek       | K53E                        | [ed3993d878](https://linux-hardware.org/?probe=ed3993d878) | Jan 08, 2022 |
| ASUSTek       | K53E                        | [f0be64df73](https://linux-hardware.org/?probe=f0be64df73) | Jan 08, 2022 |
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
| Acer          | Aspire E5-575G              | [e453f3473f](https://linux-hardware.org/?probe=e453f3473f) | Dec 27, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | [9ba8148878](https://linux-hardware.org/?probe=9ba8148878) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | [e110e5c127](https://linux-hardware.org/?probe=e110e5c127) | Dec 25, 2021 |
| ASUSTek       | K53E                        | [0915144999](https://linux-hardware.org/?probe=0915144999) | Dec 25, 2021 |
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
| Acer          | Aspire E5-575G              | [7a34a2de3b](https://linux-hardware.org/?probe=7a34a2de3b) | Dec 13, 2021 |
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
| Monster       | ABRA A5 V11.1               | [80e68beff0](https://linux-hardware.org/?probe=80e68beff0) | Dec 12, 2021 |
| Fujitsu       | LIFEBOOK E756               | [539ebca696](https://linux-hardware.org/?probe=539ebca696) | Dec 12, 2021 |
| System76      | Darter Pro                  | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| ASUSTek       | K53E                        | [86e5e5850b](https://linux-hardware.org/?probe=86e5e5850b) | Dec 09, 2021 |
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
| ASUSTek       | K53E                        | [7213694058](https://linux-hardware.org/?probe=7213694058) | Dec 04, 2021 |
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
| ASUSTek       | K53E                        | [e0191cc961](https://linux-hardware.org/?probe=e0191cc961) | Nov 26, 2021 |
| HP            | Laptop 15-bw0xx             | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e102635d3d](https://linux-hardware.org/?probe=e102635d3d) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| Dell          | Latitude E5450              | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| HP            | EliteBook 840 G1            | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek       | K53E                        | [de7dd823ec](https://linux-hardware.org/?probe=de7dd823ec) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| HUAWEI        | WRT-WX9                     | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| Dell          | Inspiron 3581               | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| Dell          | Inspiron 5579               | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| ASUSTek       | K53E                        | [11aec68b43](https://linux-hardware.org/?probe=11aec68b43) | Nov 13, 2021 |
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
| Lenovo        | ThinkPad T550 20CJS0S800    | [f7630e472c](https://linux-hardware.org/?probe=f7630e472c) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| ASUSTek       | K53E                        | [a51c252738](https://linux-hardware.org/?probe=a51c252738) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Razer         | Blade                       | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| Dell          | Latitude E6540              | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| Acer          | Aspire E5-575G              | [7046d52a8d](https://linux-hardware.org/?probe=7046d52a8d) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | K53E                        | [e7be61df28](https://linux-hardware.org/?probe=e7be61df28) | Oct 21, 2021 |
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
| ASUSTek       | K53E                        | [9f59e9fe10](https://linux-hardware.org/?probe=9f59e9fe10) | Oct 14, 2021 |
| Lenovo        | G50-30 80G0                 | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| HP            | EliteBook 840 G3            | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [bbb5cfe8b9](https://linux-hardware.org/?probe=bbb5cfe8b9) | Oct 10, 2021 |
| Razer         | Blade Stealth               | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| MSI           | GS66 Stealth 10SFS          | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| ASUSTek       | K53E                        | [b71c09ae16](https://linux-hardware.org/?probe=b71c09ae16) | Oct 04, 2021 |
| ASUSTek       | K53E                        | [6ccfe2739d](https://linux-hardware.org/?probe=6ccfe2739d) | Oct 04, 2021 |
| Alienware     | 17                          | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Monster       | ABRA A5 V11.1               | [1e67c40ae2](https://linux-hardware.org/?probe=1e67c40ae2) | Oct 02, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| HP            | Pavilion dv6                | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Monster       | ABRA A5 V11.1               | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| ASUSTek       | K53E                        | [2e166e4316](https://linux-hardware.org/?probe=2e166e4316) | Sep 27, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | X580VD                      | [baec321ff8](https://linux-hardware.org/?probe=baec321ff8) | Sep 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| ASUSTek       | K53E                        | [32ee9b304e](https://linux-hardware.org/?probe=32ee9b304e) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Chuwi         | GemiBook Pro                | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| ASUSTek       | K53E                        | [9b95329be6](https://linux-hardware.org/?probe=9b95329be6) | Sep 20, 2021 |
| Chuwi         | GemiBook Pro                | [5703e45a96](https://linux-hardware.org/?probe=5703e45a96) | Sep 19, 2021 |
| Chuwi         | GemiBook Pro                | [c42c7d1ccc](https://linux-hardware.org/?probe=c42c7d1ccc) | Sep 19, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | UX303LN                     | [9c8bb62a98](https://linux-hardware.org/?probe=9c8bb62a98) | Sep 17, 2021 |
| MSI           | GP76 Leopard 10UE           | [547ee4e1ea](https://linux-hardware.org/?probe=547ee4e1ea) | Sep 16, 2021 |
| MSI           | GP76 Leopard 10UE           | [90168ebbeb](https://linux-hardware.org/?probe=90168ebbeb) | Sep 16, 2021 |
| ASUSTek       | K53E                        | [c36494f62f](https://linux-hardware.org/?probe=c36494f62f) | Sep 16, 2021 |
| ASUSTek       | K53E                        | [88c9dd1a13](https://linux-hardware.org/?probe=88c9dd1a13) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Fujitsu       | LIFEBOOK A357               | [efc14ead6c](https://linux-hardware.org/?probe=efc14ead6c) | Sep 13, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| Lenovo        | ThinkPad T490 20N3S19L00    | [a19eee5494](https://linux-hardware.org/?probe=a19eee5494) | Sep 11, 2021 |
| Fujitsu       | LIFEBOOK A357               | [6a38389900](https://linux-hardware.org/?probe=6a38389900) | Sep 11, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | K53E                        | [17cf695269](https://linux-hardware.org/?probe=17cf695269) | Sep 10, 2021 |
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
| Acer          | Aspire E5-575G              | [be98863a94](https://linux-hardware.org/?probe=be98863a94) | Sep 02, 2021 |
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
| ASUSTek       | K53E                        | [c9705b65ba](https://linux-hardware.org/?probe=c9705b65ba) | Aug 28, 2021 |
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
| ASUSTek       | X580VD                      | [7af8fc72d4](https://linux-hardware.org/?probe=7af8fc72d4) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | [83c1674e38](https://linux-hardware.org/?probe=83c1674e38) | Aug 21, 2021 |
| HP            | Laptop 15-db0xxx            | [6dbfd72cd8](https://linux-hardware.org/?probe=6dbfd72cd8) | Aug 21, 2021 |
| ASUSTek       | X580VD                      | [5df36dba53](https://linux-hardware.org/?probe=5df36dba53) | Aug 21, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [24bbd4d06f](https://linux-hardware.org/?probe=24bbd4d06f) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [e7fd668005](https://linux-hardware.org/?probe=e7fd668005) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [e17fcec0b4](https://linux-hardware.org/?probe=e17fcec0b4) | Aug 21, 2021 |
| Dell          | Inspiron 15-5568            | [7fec9a3a5b](https://linux-hardware.org/?probe=7fec9a3a5b) | Aug 21, 2021 |
| Lenovo        | ThinkPad T440 20B70048US    | [14e8d60953](https://linux-hardware.org/?probe=14e8d60953) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| ASUSTek       | K53E                        | [a0381bb99a](https://linux-hardware.org/?probe=a0381bb99a) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 7661ZLF        | [d28b77f82f](https://linux-hardware.org/?probe=d28b77f82f) | Aug 19, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC1K    | [d693db633c](https://linux-hardware.org/?probe=d693db633c) | Aug 18, 2021 |
| Dell          | XPS 15 7590                 | [3d348a9d2a](https://linux-hardware.org/?probe=3d348a9d2a) | Aug 18, 2021 |
| ASUSTek       | X556UA                      | [04710b290b](https://linux-hardware.org/?probe=04710b290b) | Aug 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cfe1daabe](https://linux-hardware.org/?probe=4cfe1daabe) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ffa5f6a0e](https://linux-hardware.org/?probe=1ffa5f6a0e) | Aug 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d00e9f1724](https://linux-hardware.org/?probe=d00e9f1724) | Aug 14, 2021 |
| ASUSTek       | X441SA                      | [157096a598](https://linux-hardware.org/?probe=157096a598) | Aug 14, 2021 |
| ASUSTek       | K53E                        | [0b6bf691c0](https://linux-hardware.org/?probe=0b6bf691c0) | Aug 14, 2021 |
| ASUSTek       | X580VD                      | [4a86f48291](https://linux-hardware.org/?probe=4a86f48291) | Aug 14, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| ASUSTek       | X580VD                      | [7a8a93a361](https://linux-hardware.org/?probe=7a8a93a361) | Aug 12, 2021 |
| ASUSTek       | X580VD                      | [aeae754f0f](https://linux-hardware.org/?probe=aeae754f0f) | Aug 12, 2021 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e42d32bf2a](https://linux-hardware.org/?probe=e42d32bf2a) | Aug 12, 2021 |
| Acer          | Aspire 7741                 | [9d26562113](https://linux-hardware.org/?probe=9d26562113) | Aug 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| HP            | Laptop 15q-bu1xx            | [5aced87a3f](https://linux-hardware.org/?probe=5aced87a3f) | Aug 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [e9d2ccb049](https://linux-hardware.org/?probe=e9d2ccb049) | Aug 09, 2021 |
| ASUSTek       | K53E                        | [e8fff6624c](https://linux-hardware.org/?probe=e8fff6624c) | Aug 09, 2021 |
| ASUSTek       | X441SA                      | [7b26cd5c2b](https://linux-hardware.org/?probe=7b26cd5c2b) | Aug 08, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [5f24fa8f98](https://linux-hardware.org/?probe=5f24fa8f98) | Aug 08, 2021 |
| Dell          | Vostro 3500                 | [51115b9f9f](https://linux-hardware.org/?probe=51115b9f9f) | Aug 08, 2021 |
| ASUSTek       | K53E                        | [5469077205](https://linux-hardware.org/?probe=5469077205) | Aug 07, 2021 |
| Lenovo        | ThinkPad W541 20EF0000US    | [6150ef8ebc](https://linux-hardware.org/?probe=6150ef8ebc) | Aug 07, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | K53E                        | [abf75647a9](https://linux-hardware.org/?probe=abf75647a9) | Aug 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [268e93bc48](https://linux-hardware.org/?probe=268e93bc48) | Aug 05, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| Acer          | Nitro AN515-53              | [baf0ccecb1](https://linux-hardware.org/?probe=baf0ccecb1) | Aug 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [c434457251](https://linux-hardware.org/?probe=c434457251) | Aug 03, 2021 |
| AZW           | SEi                         | [de596531ae](https://linux-hardware.org/?probe=de596531ae) | Aug 02, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Lenovo        | ThinkPad X201 3626GWG       | [3709f5744a](https://linux-hardware.org/?probe=3709f5744a) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| ASUSTek       | K53E                        | [2868347889](https://linux-hardware.org/?probe=2868347889) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [2b732e43eb](https://linux-hardware.org/?probe=2b732e43eb) | Aug 01, 2021 |
| ASUSTek       | E200HA                      | [68b431bc45](https://linux-hardware.org/?probe=68b431bc45) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [a8e52318c8](https://linux-hardware.org/?probe=a8e52318c8) | Aug 01, 2021 |
| Apple         | MacBookPro9,2               | [949e4af6a7](https://linux-hardware.org/?probe=949e4af6a7) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| ASUSTek       | K53E                        | [bc4f2fef5c](https://linux-hardware.org/?probe=bc4f2fef5c) | Jul 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [65d9b956bc](https://linux-hardware.org/?probe=65d9b956bc) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e84e4c3d4c](https://linux-hardware.org/?probe=e84e4c3d4c) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e9fd822a6](https://linux-hardware.org/?probe=0e9fd822a6) | Jul 29, 2021 |
| Dell          | Precision 7520              | [bb1844c704](https://linux-hardware.org/?probe=bb1844c704) | Jul 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| ASUSTek       | K53E                        | [45f958be8e](https://linux-hardware.org/?probe=45f958be8e) | Jul 26, 2021 |
| ASUSTek       | K53E                        | [906c44e1dd](https://linux-hardware.org/?probe=906c44e1dd) | Jul 26, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| ASUSTek       | K53E                        | [0e4c994a10](https://linux-hardware.org/?probe=0e4c994a10) | Jul 25, 2021 |
| ASUSTek       | K53E                        | [6246986bb2](https://linux-hardware.org/?probe=6246986bb2) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| Dell          | Latitude 5410               | [cb463b1fc3](https://linux-hardware.org/?probe=cb463b1fc3) | Jul 22, 2021 |
| HP            | Stream Notebook PC 13       | [6631c46029](https://linux-hardware.org/?probe=6631c46029) | Jul 22, 2021 |
| ASUSTek       | K53E                        | [b61f2b460f](https://linux-hardware.org/?probe=b61f2b460f) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| HP            | Laptop 15-da0xxx            | [4cb2daf424](https://linux-hardware.org/?probe=4cb2daf424) | Jul 16, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [be2edf1657](https://linux-hardware.org/?probe=be2edf1657) | Jul 14, 2021 |
| Acer          | Aspire E5-575G              | [672a2b3117](https://linux-hardware.org/?probe=672a2b3117) | Jul 14, 2021 |
| HP            | Notebook                    | [021a011da8](https://linux-hardware.org/?probe=021a011da8) | Jul 13, 2021 |
| ASUSTek       | K53E                        | [8e034623d9](https://linux-hardware.org/?probe=8e034623d9) | Jul 12, 2021 |
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
| Apple         | MacBookPro11,5              | [beb6e31fa9](https://linux-hardware.org/?probe=beb6e31fa9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Apple         | MacBookPro12,1              | [0a8dac703d](https://linux-hardware.org/?probe=0a8dac703d) | Jun 29, 2021 |
| Apple         | MacBookPro11,5              | [924bb2e204](https://linux-hardware.org/?probe=924bb2e204) | Jun 28, 2021 |
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
| Chuwi         | GemiBook Pro                | [021617b9a0](https://linux-hardware.org/?probe=021617b9a0) | May 31, 2021 |
| Toshiba       | Satellite L635              | [634bc5add8](https://linux-hardware.org/?probe=634bc5add8) | May 30, 2021 |
| System76      | Oryx Pro                    | [e18b16565f](https://linux-hardware.org/?probe=e18b16565f) | May 29, 2021 |
| Toshiba       | Satellite R630              | [0c557895be](https://linux-hardware.org/?probe=0c557895be) | May 29, 2021 |
| Daten Tecn... | ESTELAR                     | [f19e7920ca](https://linux-hardware.org/?probe=f19e7920ca) | May 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1daf88898e](https://linux-hardware.org/?probe=1daf88898e) | May 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [302b62a5c7](https://linux-hardware.org/?probe=302b62a5c7) | May 20, 2021 |
| Chuwi         | GemiBook Pro                | [7af662cb94](https://linux-hardware.org/?probe=7af662cb94) | May 18, 2021 |
| Chuwi         | GemiBook Pro                | [c188ca866f](https://linux-hardware.org/?probe=c188ca866f) | May 18, 2021 |
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
| Chuwi         | GemiBook Pro                | [753d42a4a5](https://linux-hardware.org/?probe=753d42a4a5) | Apr 28, 2021 |
| Dell          | Latitude E6440              | [535815022c](https://linux-hardware.org/?probe=535815022c) | Apr 23, 2021 |
| Dell          | Latitude E6440              | [a079078493](https://linux-hardware.org/?probe=a079078493) | Apr 23, 2021 |
| HP            | 255 G2                      | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [f707b24713](https://linux-hardware.org/?probe=f707b24713) | Apr 22, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [16ab380d72](https://linux-hardware.org/?probe=16ab380d72) | Apr 21, 2021 |
| Dell          | Vostro 3550                 | [2b122eb7e6](https://linux-hardware.org/?probe=2b122eb7e6) | Apr 21, 2021 |
| ASUSTek       | UX430UAR                    | [a071188f1c](https://linux-hardware.org/?probe=a071188f1c) | Apr 21, 2021 |
| Lenovo        | G50-70 20351                | [44e6cc36ce](https://linux-hardware.org/?probe=44e6cc36ce) | Apr 20, 2021 |
| HP            | EliteBook 8460p             | [dc1e0bf320](https://linux-hardware.org/?probe=dc1e0bf320) | Apr 19, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [eeee3c8078](https://linux-hardware.org/?probe=eeee3c8078) | Apr 18, 2021 |
| Chuwi         | GemiBook Pro                | [24b652099d](https://linux-hardware.org/?probe=24b652099d) | Apr 16, 2021 |
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
| Toshiba       | Satellite C55-A-1N0         | [d316794d0c](https://linux-hardware.org/?probe=d316794d0c) | Mar 27, 2021 |
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
| ASUSTek       | K501UX                      | [0a3c9ff078](https://linux-hardware.org/?probe=0a3c9ff078) | Mar 17, 2021 |
| Dell          | Inspiron 5555               | [4b3ec85962](https://linux-hardware.org/?probe=4b3ec85962) | Mar 16, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| HP            | OMEN by HP Laptop           | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
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
| Lenovo        | ThinkPad L520 785958G       | [4ec2149aa3](https://linux-hardware.org/?probe=4ec2149aa3) | Feb 11, 2021 |
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
| Lenovo        | ThinkPad X201 3680KC5       | [d91cbb0784](https://linux-hardware.org/?probe=d91cbb0784) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Lenovo        | B50-10 80QR                 | [136f6c27fb](https://linux-hardware.org/?probe=136f6c27fb) | Jan 22, 2021 |
| Medion        | E7222                       | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| Acer          | NU-A515-44-R68D             | [69612ffeb2](https://linux-hardware.org/?probe=69612ffeb2) | Jan 20, 2021 |
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
| Lenovo        | V155-15API 81V5             | [64ec8663fc](https://linux-hardware.org/?probe=64ec8663fc) | Dec 23, 2020 |
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
| HP            | OMEN by HP Laptop           | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| Acer          | Swift SF314-41              | [5155111cfa](https://linux-hardware.org/?probe=5155111cfa) | Dec 10, 2020 |
| Acer          | AOD260                      | [635a9139e1](https://linux-hardware.org/?probe=635a9139e1) | Dec 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [baf10417f7](https://linux-hardware.org/?probe=baf10417f7) | Dec 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| ASUSTek       | K501UX                      | [4838a6e14f](https://linux-hardware.org/?probe=4838a6e14f) | Dec 05, 2020 |
| Dell          | Latitude 5480               | [02680953ae](https://linux-hardware.org/?probe=02680953ae) | Dec 04, 2020 |
| ASUSTek       | TUF GAMING FX504GE_FX80G... | [e6ee8ad4bb](https://linux-hardware.org/?probe=e6ee8ad4bb) | Dec 03, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [153a43bcc6](https://linux-hardware.org/?probe=153a43bcc6) | Dec 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [52cf6d4786](https://linux-hardware.org/?probe=52cf6d4786) | Dec 02, 2020 |
| Fujitsu       | LIFEBOOK AH562              | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Timi          | TM1709                      | [bcccdee6ec](https://linux-hardware.org/?probe=bcccdee6ec) | Nov 29, 2020 |
| System76      | Galago Pro                  | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | Inspiron N4110              | [8d8bd09d64](https://linux-hardware.org/?probe=8d8bd09d64) | Nov 27, 2020 |
| Timi          | TM1709                      | [01d2a19918](https://linux-hardware.org/?probe=01d2a19918) | Nov 27, 2020 |
| Toshiba       | Satellite S70-B             | [d9925a0d93](https://linux-hardware.org/?probe=d9925a0d93) | Nov 26, 2020 |
| Dell          | Latitude 5310               | [b941f2a157](https://linux-hardware.org/?probe=b941f2a157) | Nov 25, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ce492b1a92](https://linux-hardware.org/?probe=ce492b1a92) | Nov 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3cfe7597e](https://linux-hardware.org/?probe=e3cfe7597e) | Nov 25, 2020 |
| Dell          | Inspiron 3558               | [2beee5183a](https://linux-hardware.org/?probe=2beee5183a) | Nov 24, 2020 |
| Timi          | TM1709                      | [cf290a19fb](https://linux-hardware.org/?probe=cf290a19fb) | Nov 24, 2020 |
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
| Acer          | Aspire E5-523               | [ae9800cc49](https://linux-hardware.org/?probe=ae9800cc49) | Nov 14, 2020 |
| Timi          | TM1607                      | [db600ca49e](https://linux-hardware.org/?probe=db600ca49e) | Nov 14, 2020 |
| Acer          | Aspire E5-523               | [316dc021cb](https://linux-hardware.org/?probe=316dc021cb) | Nov 14, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [867148b244](https://linux-hardware.org/?probe=867148b244) | Nov 14, 2020 |
| HP            | EliteBook 8540p             | [10121917da](https://linux-hardware.org/?probe=10121917da) | Nov 13, 2020 |
| HP            | EliteBook 8540p             | [1df463aa08](https://linux-hardware.org/?probe=1df463aa08) | Nov 13, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [addf2ac7fa](https://linux-hardware.org/?probe=addf2ac7fa) | Nov 12, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [9ebd194a93](https://linux-hardware.org/?probe=9ebd194a93) | Nov 12, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [49eef48191](https://linux-hardware.org/?probe=49eef48191) | Nov 12, 2020 |
| Timi          | TM1709                      | [d7a940b8e0](https://linux-hardware.org/?probe=d7a940b8e0) | Nov 12, 2020 |
| HP            | EliteBook 8760w             | [27ecc71233](https://linux-hardware.org/?probe=27ecc71233) | Nov 11, 2020 |
| Lenovo        | ThinkPad X201 3680KC5       | [2f03701216](https://linux-hardware.org/?probe=2f03701216) | Nov 11, 2020 |
| HP            | EliteBook 8540p             | [6a0b95782d](https://linux-hardware.org/?probe=6a0b95782d) | Nov 11, 2020 |
| Timi          | TM1709                      | [b89916b8c1](https://linux-hardware.org/?probe=b89916b8c1) | Nov 10, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [f2fc35bc80](https://linux-hardware.org/?probe=f2fc35bc80) | Nov 10, 2020 |
| HP            | EliteBook 8540p             | [a3264597e8](https://linux-hardware.org/?probe=a3264597e8) | Nov 10, 2020 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [e6ae7e8546](https://linux-hardware.org/?probe=e6ae7e8546) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [1dbe42216a](https://linux-hardware.org/?probe=1dbe42216a) | Nov 10, 2020 |
| Lenovo        | G560 0679                   | [35c00cb9bd](https://linux-hardware.org/?probe=35c00cb9bd) | Nov 09, 2020 |
| Medion        | E7212                       | [8979d90ea2](https://linux-hardware.org/?probe=8979d90ea2) | Nov 09, 2020 |
| Medion        | E7212                       | [3650f725ba](https://linux-hardware.org/?probe=3650f725ba) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [5c6c0ac3fa](https://linux-hardware.org/?probe=5c6c0ac3fa) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | [c84684fab0](https://linux-hardware.org/?probe=c84684fab0) | Nov 09, 2020 |
| Sony          | SVS1511Q9EB                 | [57911ec356](https://linux-hardware.org/?probe=57911ec356) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| ASUSTek       | E403NA                      | [c18d0128e0](https://linux-hardware.org/?probe=c18d0128e0) | Nov 09, 2020 |
| ASUSTek       | K501UX                      | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| Timi          | TM1709                      | [97dbbf75d8](https://linux-hardware.org/?probe=97dbbf75d8) | Nov 08, 2020 |
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
| HP            | Notebook                    | [c93227aec0](https://linux-hardware.org/?probe=c93227aec0) | Apr 13, 2020 |
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
| ArcoLinux Rolling     | 510       | 85.86%  |
| ArcoLinux             | 63        | 10.61%  |
| ArcoLinux 20.6.5      | 7         | 1.18%   |
| ArcoLinux 20.7.5      | 4         | 0.67%   |
| ArcoLinux 20.3.4      | 2         | 0.34%   |
| ArcoLinux 20.3.3      | 2         | 0.34%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.17%   |
| ArcoLinux 6.9.2       | 1         | 0.17%   |
| ArcoLinux 20.2.12     | 1         | 0.17%   |
| ArcoLinux 20.1.4      | 1         | 0.17%   |
| ArcoLinux 19.07.11    | 1         | 0.17%   |
| ArcoLinux 19.02.4     | 1         | 0.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ArcoLinux | 591       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 21        | 3.14%   |
| 5.13.13-arch1-1   | 19        | 2.84%   |
| 5.15.10-arch1-1   | 16        | 2.4%    |
| 5.14.14-arch1-1   | 14        | 2.1%    |
| 5.13.12-arch1-1   | 13        | 1.95%   |
| 5.17.1-arch1-1    | 12        | 1.8%    |
| 5.14.12-arch1-1   | 12        | 1.8%    |
| 5.12.13-arch1-2   | 10        | 1.5%    |
| 5.15.11-arch2-1   | 9         | 1.35%   |
| 5.12.15-arch1-1   | 9         | 1.35%   |
| 5.9.1-arch1-1     | 8         | 1.2%    |
| 5.15.5-arch1-1    | 8         | 1.2%    |
| 5.15.13-arch1-1   | 8         | 1.2%    |
| 5.12.14-arch1-1   | 8         | 1.2%    |
| 5.10.84-1-lts     | 8         | 1.2%    |
| 5.9.8-arch1-1     | 7         | 1.05%   |
| 5.16.2-arch1-1    | 7         | 1.05%   |
| 5.16.10-arch1-1   | 7         | 1.05%   |
| 5.13.8-arch1-1    | 7         | 1.05%   |
| 5.12.10-arch1-1   | 7         | 1.05%   |
| 5.9.10-arch1-1    | 6         | 0.9%    |
| 5.16.12-arch1-1   | 6         | 0.9%    |
| 5.15.4-arch1-1    | 6         | 0.9%    |
| 5.14.9-arch2-1    | 6         | 0.9%    |
| 5.12.12-arch1-1   | 6         | 0.9%    |
| 5.10.6-arch1-1    | 6         | 0.9%    |
| 5.9.6-arch1-1     | 5         | 0.75%   |
| 5.4.70-1-lts      | 5         | 0.75%   |
| 5.16.16-arch1-1   | 5         | 0.75%   |
| 5.15.6-arch2-1    | 5         | 0.75%   |
| 5.14.7-arch1-1    | 5         | 0.75%   |
| 5.14.15-arch1-1   | 5         | 0.75%   |
| 5.10.88-2-lts     | 5         | 0.75%   |
| 5.10.56-1-lts     | 5         | 0.75%   |
| 5.10.16-arch1-1   | 5         | 0.75%   |
| 5.9.14-zen1-1-zen | 4         | 0.6%    |
| 5.9.14-arch1-1    | 4         | 0.6%    |
| 5.9.13-arch1-1    | 4         | 0.6%    |
| 5.9.11-arch2-1    | 4         | 0.6%    |
| 5.17.4-arch1-1    | 4         | 0.6%    |
| 5.16.8-arch1-1    | 4         | 0.6%    |
| 5.16.5-arch1-1    | 4         | 0.6%    |
| 5.16.4-arch1-1    | 4         | 0.6%    |
| 5.16.15-arch1-1   | 4         | 0.6%    |
| 5.16.11-arch1-1   | 4         | 0.6%    |
| 5.15.2-arch1-1    | 4         | 0.6%    |
| 5.15.12-arch1-1   | 4         | 0.6%    |
| 5.14.5-arch1-1    | 4         | 0.6%    |
| 5.13.9-arch1-1    | 4         | 0.6%    |
| 5.13.6-arch1-1    | 4         | 0.6%    |
| 5.13.10-arch1-1   | 4         | 0.6%    |
| 5.11.6-arch1-1    | 4         | 0.6%    |
| 5.11.12-arch1-1   | 4         | 0.6%    |
| 5.10.85-1-lts     | 4         | 0.6%    |
| 5.10.7-arch1-1    | 4         | 0.6%    |
| 5.10.60-1-lts     | 4         | 0.6%    |
| 5.9.6-zen1-1-zen  | 3         | 0.45%   |
| 5.8.13-arch1-1    | 3         | 0.45%   |
| 5.4.72-1-lts      | 3         | 0.45%   |
| 5.16.9-arch1-1    | 3         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.7  | 25        | 3.74%   |
| 5.13.13 | 19        | 2.84%   |
| 5.15.10 | 16        | 2.4%    |
| 5.17.1  | 15        | 2.25%   |
| 5.14.14 | 14        | 2.1%    |
| 5.14.12 | 13        | 1.95%   |
| 5.13.12 | 13        | 1.95%   |
| 5.9.8   | 11        | 1.65%   |
| 5.9.1   | 10        | 1.5%    |
| 5.12.15 | 10        | 1.5%    |
| 5.12.13 | 10        | 1.5%    |
| 5.16.2  | 9         | 1.35%   |
| 5.15.5  | 9         | 1.35%   |
| 5.15.11 | 9         | 1.35%   |
| 5.9.6   | 8         | 1.2%    |
| 5.9.14  | 8         | 1.2%    |
| 5.16.10 | 8         | 1.2%    |
| 5.15.13 | 8         | 1.2%    |
| 5.14.9  | 8         | 1.2%    |
| 5.12.14 | 8         | 1.2%    |
| 5.10.84 | 8         | 1.2%    |
| 5.10.16 | 8         | 1.2%    |
| 5.9.10  | 7         | 1.05%   |
| 5.15.4  | 7         | 1.05%   |
| 5.13.8  | 7         | 1.05%   |
| 5.12.10 | 7         | 1.05%   |
| 5.9.11  | 6         | 0.9%    |
| 5.16.12 | 6         | 0.9%    |
| 5.15.6  | 6         | 0.9%    |
| 5.14.15 | 6         | 0.9%    |
| 5.12.12 | 6         | 0.9%    |
| 5.10.6  | 6         | 0.9%    |
| 5.9.13  | 5         | 0.75%   |
| 5.4.70  | 5         | 0.75%   |
| 5.16.8  | 5         | 0.75%   |
| 5.16.5  | 5         | 0.75%   |
| 5.16.16 | 5         | 0.75%   |
| 5.16.11 | 5         | 0.75%   |
| 5.15.2  | 5         | 0.75%   |
| 5.14.7  | 5         | 0.75%   |
| 5.14.5  | 5         | 0.75%   |
| 5.13.9  | 5         | 0.75%   |
| 5.13.6  | 5         | 0.75%   |
| 5.11.6  | 5         | 0.75%   |
| 5.11.12 | 5         | 0.75%   |
| 5.11.11 | 5         | 0.75%   |
| 5.10.88 | 5         | 0.75%   |
| 5.10.7  | 5         | 0.75%   |
| 5.10.56 | 5         | 0.75%   |
| 5.17.4  | 4         | 0.6%    |
| 5.17.3  | 4         | 0.6%    |
| 5.16.4  | 4         | 0.6%    |
| 5.16.15 | 4         | 0.6%    |
| 5.15.12 | 4         | 0.6%    |
| 5.13.5  | 4         | 0.6%    |
| 5.13.10 | 4         | 0.6%    |
| 5.12.9  | 4         | 0.6%    |
| 5.11.4  | 4         | 0.6%    |
| 5.10.9  | 4         | 0.6%    |
| 5.10.85 | 4         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 123       | 19.28%  |
| 5.15    | 105       | 16.46%  |
| 5.14    | 62        | 9.72%   |
| 5.13    | 62        | 9.72%   |
| 5.16    | 60        | 9.4%    |
| 5.9     | 57        | 8.93%   |
| 5.12    | 55        | 8.62%   |
| 5.11    | 36        | 5.64%   |
| 5.4     | 33        | 5.17%   |
| 5.17    | 26        | 4.08%   |
| 5.8     | 6         | 0.94%   |
| 5.7     | 4         | 0.63%   |
| 5.5     | 3         | 0.47%   |
| 5.6     | 2         | 0.31%   |
| 5.2     | 1         | 0.16%   |
| 5.0     | 1         | 0.16%   |
| 4.20    | 1         | 0.16%   |
| 4.18    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 591       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| XFCE           | 184       | 30.21%  |
| KDE5           | 94        | 15.44%  |
| i3             | 56        | 9.2%    |
| GNOME          | 42        | 6.9%    |
| qtile          | 33        | 5.42%   |
| awesome        | 33        | 5.42%   |
| bspwm          | 28        | 4.6%    |
| dwm            | 24        | 3.94%   |
| xmonad         | 22        | 3.61%   |
| X-Cinnamon     | 20        | 3.28%   |
| KDE            | 11        | 1.81%   |
| Unknown        | 9         | 1.48%   |
| Deepin         | 7         | 1.15%   |
| Budgie         | 7         | 1.15%   |
| MATE           | 6         | 0.99%   |
| LeftWM         | 6         | 0.99%   |
| i3-with-shmlog | 6         | 0.99%   |
| herbstluftwm   | 5         | 0.82%   |
| LXQt           | 3         | 0.49%   |
| Cinnamon       | 3         | 0.49%   |
| spectrwm       | 2         | 0.33%   |
| Unity          | 1         | 0.16%   |
| sway           | 1         | 0.16%   |
| openbox        | 1         | 0.16%   |
| jwm            | 1         | 0.16%   |
| dwm-sc         | 1         | 0.16%   |
| dusk           | 1         | 0.16%   |
| cwm            | 1         | 0.16%   |
| Cutefish       | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 557       | 93.77%  |
| Tty     | 23        | 3.87%   |
| Wayland | 13        | 2.19%   |
| Unknown | 1         | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 283       | 45.94%  |
| TDM     | 147       | 23.86%  |
| LightDM | 94        | 15.26%  |
| Unknown | 78        | 12.66%  |
| GDM     | 10        | 1.62%   |
| XDM     | 1         | 0.16%   |
| SLiM    | 1         | 0.16%   |
| Ly      | 1         | 0.16%   |
| LXDM    | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 346       | 57.86%  |
| en_GB   | 43        | 7.19%   |
| de_DE   | 35        | 5.85%   |
| en_IN   | 20        | 3.34%   |
| en_CA   | 20        | 3.34%   |
| fr_FR   | 17        | 2.84%   |
| en_AU   | 10        | 1.67%   |
| ru_RU   | 9         | 1.51%   |
| pl_PL   | 8         | 1.34%   |
| Unknown | 7         | 1.17%   |
| pt_BR   | 6         | 1%      |
| hu_HU   | 6         | 1%      |
| es_ES   | 5         | 0.84%   |
| ru_UA   | 4         | 0.67%   |
| es_AR   | 4         | 0.67%   |
| en_IE   | 4         | 0.67%   |
| nl_BE   | 3         | 0.5%    |
| it_IT   | 3         | 0.5%    |
| es_CL   | 3         | 0.5%    |
| en_SG   | 3         | 0.5%    |
| en_DK   | 3         | 0.5%    |
| el_GR   | 3         | 0.5%    |
| tr_TR   | 2         | 0.33%   |
| sv_SE   | 2         | 0.33%   |
| ro_RO   | 2         | 0.33%   |
| nl_NL   | 2         | 0.33%   |
| fr_CA   | 2         | 0.33%   |
| fr_BE   | 2         | 0.33%   |
| es_MX   | 2         | 0.33%   |
| en_IL   | 2         | 0.33%   |
| zh_CN   | 1         | 0.17%   |
| pt_PT   | 1         | 0.17%   |
| nb_NO   | 1         | 0.17%   |
| lv_LV   | 1         | 0.17%   |
| ja_JP   | 1         | 0.17%   |
| fr_CH   | 1         | 0.17%   |
| es_VE   | 1         | 0.17%   |
| es_US   | 1         | 0.17%   |
| es_PY   | 1         | 0.17%   |
| es_EC   | 1         | 0.17%   |
| es_CO   | 1         | 0.17%   |
| en_ZA   | 1         | 0.17%   |
| en_PH   | 1         | 0.17%   |
| en_NZ   | 1         | 0.17%   |
| en_HK   | 1         | 0.17%   |
| de_ch   | 1         | 0.17%   |
| da_DK   | 1         | 0.17%   |
| cs_CZ   | 1         | 0.17%   |
| ca_ES   | 1         | 0.17%   |
| C       | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 410       | 68.79%  |
| BIOS | 186       | 31.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 464       | 77.72%  |
| Btrfs   | 92        | 15.41%  |
| Overlay | 27        | 4.52%   |
| Xfs     | 10        | 1.68%   |
| F2fs    | 2         | 0.34%   |
| Jfs     | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 417       | 70.2%   |
| MBR     | 106       | 17.85%  |
| Unknown | 71        | 11.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 507       | 84.22%  |
| Yes       | 95        | 15.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 408       | 68.8%   |
| Yes       | 185       | 31.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 178       | 30.12%  |
| Dell                | 97        | 16.41%  |
| Hewlett-Packard     | 75        | 12.69%  |
| ASUSTek Computer    | 66        | 11.17%  |
| Acer                | 46        | 7.78%   |
| Apple               | 23        | 3.89%   |
| Toshiba             | 12        | 2.03%   |
| MSI                 | 9         | 1.52%   |
| System76            | 7         | 1.18%   |
| Sony                | 7         | 1.18%   |
| Samsung Electronics | 7         | 1.18%   |
| Razer               | 6         | 1.02%   |
| Notebook            | 6         | 1.02%   |
| HUAWEI              | 6         | 1.02%   |
| Fujitsu             | 6         | 1.02%   |
| Timi                | 5         | 0.85%   |
| Medion              | 5         | 0.85%   |
| TUXEDO              | 4         | 0.68%   |
| Alienware           | 3         | 0.51%   |
| Teclast             | 2         | 0.34%   |
| Casper              | 2         | 0.34%   |
| AZW                 | 2         | 0.34%   |
| UNITCOM             | 1         | 0.17%   |
| Standard            | 1         | 0.17%   |
| SLIMBOOK            | 1         | 0.17%   |
| Semp Toshiba        | 1         | 0.17%   |
| Schenker            | 1         | 0.17%   |
| Pegatron            | 1         | 0.17%   |
| Monster             | 1         | 0.17%   |
| LG Electronics      | 1         | 0.17%   |
| Google              | 1         | 0.17%   |
| Entroware           | 1         | 0.17%   |
| eMachines           | 1         | 0.17%   |
| Eluktronics         | 1         | 0.17%   |
| Daten Tecnologia    | 1         | 0.17%   |
| Compal              | 1         | 0.17%   |
| Chuwi               | 1         | 0.17%   |
| Bluechip Computer   | 1         | 0.17%   |
| Unknown             | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 4         | 0.68%   |
| HP Pavilion Notebook                   | 4         | 0.68%   |
| HP Notebook                            | 4         | 0.68%   |
| Timi TM1607                            | 3         | 0.51%   |
| Razer Blade                            | 3         | 0.51%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 3         | 0.51%   |
| HP Laptop 15s-eq2xxx                   | 3         | 0.51%   |
| HP EliteBook 8460p                     | 3         | 0.51%   |
| HP 255 G7 Notebook PC                  | 3         | 0.51%   |
| Dell XPS 15 9570                       | 3         | 0.51%   |
| Dell Precision M4800                   | 3         | 0.51%   |
| Dell Latitude E6530                    | 3         | 0.51%   |
| Dell Inspiron 15 7000 Gaming           | 3         | 0.51%   |
| Apple MacBookPro8,1                    | 3         | 0.51%   |
| Apple MacBookPro11,2                   | 3         | 0.51%   |
| Apple MacBookPro11,1                   | 3         | 0.51%   |
| Acer Swift SF314-41                    | 3         | 0.51%   |
| System76 Oryx Pro                      | 2         | 0.34%   |
| System76 Galago Pro                    | 2         | 0.34%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 2         | 0.34%   |
| Razer Blade Stealth                    | 2         | 0.34%   |
| Lenovo Yoga 900-13ISK 80MK             | 2         | 0.34%   |
| Lenovo V14-ADA 82C6                    | 2         | 0.34%   |
| Lenovo ThinkPad T410 2522AC1           | 2         | 0.34%   |
| Lenovo Legion Y540-15IRH 81SX          | 2         | 0.34%   |
| Lenovo Legion 5 15ARH05 82B5           | 2         | 0.34%   |
| Lenovo IdeaPad S145-15AST 81N3         | 2         | 0.34%   |
| Lenovo IdeaPad Flex-14API 81SS         | 2         | 0.34%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.34%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 2         | 0.34%   |
| Lenovo G50-30 80G0                     | 2         | 0.34%   |
| HUAWEI WRT-WX9                         | 2         | 0.34%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.34%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 2         | 0.34%   |
| HP OMEN by HP Laptop                   | 2         | 0.34%   |
| HP Laptop 15-da0xxx                    | 2         | 0.34%   |
| HP Laptop 15-bw0xx                     | 2         | 0.34%   |
| HP ENVY Notebook                       | 2         | 0.34%   |
| HP EliteBook 8760w                     | 2         | 0.34%   |
| HP EliteBook 840 G3                    | 2         | 0.34%   |
| HP 250 G7 Notebook PC                  | 2         | 0.34%   |
| Dell XPS 15 9560                       | 2         | 0.34%   |
| Dell XPS 15 9500                       | 2         | 0.34%   |
| Dell XPS 13 9370                       | 2         | 0.34%   |
| Dell XPS 13 9300                       | 2         | 0.34%   |
| Dell Precision 5550                    | 2         | 0.34%   |
| Dell Latitude E7440                    | 2         | 0.34%   |
| Dell Latitude E6540                    | 2         | 0.34%   |
| Dell Latitude E5430 non-vPro           | 2         | 0.34%   |
| Dell Latitude E4310                    | 2         | 0.34%   |
| Dell Latitude 7480                     | 2         | 0.34%   |
| Dell Latitude 5480                     | 2         | 0.34%   |
| Dell Latitude 5410                     | 2         | 0.34%   |
| Dell Inspiron 5570                     | 2         | 0.34%   |
| ASUS X580VD                            | 2         | 0.34%   |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD | 2         | 0.34%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL | 2         | 0.34%   |
| Apple MacBookPro9,2                    | 2         | 0.34%   |
| Apple MacBookPro14,2                   | 2         | 0.34%   |
| Acer Nitro AN515-54                    | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 99        | 16.75%  |
| Lenovo IdeaPad      | 40        | 6.77%   |
| Dell Latitude       | 35        | 5.92%   |
| Dell Inspiron       | 30        | 5.08%   |
| Acer Aspire         | 28        | 4.74%   |
| Dell XPS            | 21        | 3.55%   |
| ASUS VivoBook       | 16        | 2.71%   |
| Lenovo Legion       | 15        | 2.54%   |
| HP Laptop           | 15        | 2.54%   |
| HP EliteBook        | 13        | 2.2%    |
| HP Pavilion         | 12        | 2.03%   |
| Toshiba Satellite   | 10        | 1.69%   |
| Dell Precision      | 8         | 1.35%   |
| Apple MacBookPro11  | 8         | 1.35%   |
| Acer Nitro          | 8         | 1.35%   |
| Razer Blade         | 6         | 1.02%   |
| HP ProBook          | 6         | 1.02%   |
| HP ENVY             | 6         | 1.02%   |
| Fujitsu LIFEBOOK    | 6         | 1.02%   |
| ASUS TUF            | 5         | 0.85%   |
| ASUS ROG            | 5         | 0.85%   |
| Acer Swift          | 5         | 0.85%   |
| Lenovo Yoga         | 4         | 0.68%   |
| HP Notebook         | 4         | 0.68%   |
| HP 255              | 4         | 0.68%   |
| HP 250              | 4         | 0.68%   |
| Timi TM1607         | 3         | 0.51%   |
| HP ZBook            | 3         | 0.51%   |
| Dell Vostro         | 3         | 0.51%   |
| Apple MacBookPro8   | 3         | 0.51%   |
| System76 Oryx       | 2         | 0.34%   |
| System76 Galago     | 2         | 0.34%   |
| Samsung 350V5C      | 2         | 0.34%   |
| MSI Modern          | 2         | 0.34%   |
| MSI GS66            | 2         | 0.34%   |
| Lenovo V14-ADA      | 2         | 0.34%   |
| Lenovo ThinkBook    | 2         | 0.34%   |
| Lenovo G50-30       | 2         | 0.34%   |
| HUAWEI WRT-WX9      | 2         | 0.34%   |
| HUAWEI KLVL-WXX9    | 2         | 0.34%   |
| HP OMEN             | 2         | 0.34%   |
| ASUS X580VD         | 2         | 0.34%   |
| Apple MacBookPro9   | 2         | 0.34%   |
| Apple MacBookPro5   | 2         | 0.34%   |
| Apple MacBookPro14  | 2         | 0.34%   |
| Acer Predator       | 2         | 0.34%   |
| Unknown             | 2         | 0.34%   |
| UNITCOM W55xEU      | 1         | 0.17%   |
| TUXEDO Polaris      | 1         | 0.17%   |
| TUXEDO InfinityBook | 1         | 0.17%   |
| TUXEDO BC1510       | 1         | 0.17%   |
| Toshiba QOSMIO      | 1         | 0.17%   |
| Toshiba PORTEGE     | 1         | 0.17%   |
| Timi TM1709         | 1         | 0.17%   |
| Timi TM1701         | 1         | 0.17%   |
| Teclast X98Pro      | 1         | 0.17%   |
| Teclast F15S        | 1         | 0.17%   |
| System76 Pangolin   | 1         | 0.17%   |
| System76 Gazelle    | 1         | 0.17%   |
| System76 Darter     | 1         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 74        | 12.52%  |
| 2019 | 70        | 11.84%  |
| 2017 | 67        | 11.34%  |
| 2018 | 66        | 11.17%  |
| 2011 | 50        | 8.46%   |
| 2016 | 46        | 7.78%   |
| 2012 | 35        | 5.92%   |
| 2015 | 34        | 5.75%   |
| 2014 | 34        | 5.75%   |
| 2013 | 33        | 5.58%   |
| 2010 | 30        | 5.08%   |
| 2021 | 29        | 4.91%   |
| 2009 | 11        | 1.86%   |
| 2008 | 8         | 1.35%   |
| 2007 | 4         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 591       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 591       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 587       | 99.32%  |
| Yes  | 4         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 197       | 33.16%  |
| 16.01-24.0  | 144       | 24.24%  |
| 8.01-16.0   | 104       | 17.51%  |
| 3.01-4.0    | 85        | 14.31%  |
| 32.01-64.0  | 34        | 5.72%   |
| 24.01-32.0  | 10        | 1.68%   |
| 1.01-2.0    | 10        | 1.68%   |
| 64.01-256.0 | 7         | 1.18%   |
| 2.01-3.0    | 3         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 224       | 35.28%  |
| 2.01-3.0   | 169       | 26.61%  |
| 3.01-4.0   | 81        | 12.76%  |
| 0.51-1.0   | 66        | 10.39%  |
| 4.01-8.0   | 62        | 9.76%   |
| 8.01-16.0  | 19        | 2.99%   |
| 0.01-0.5   | 11        | 1.73%   |
| 16.01-24.0 | 2         | 0.31%   |
| 24.01-32.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 401       | 67.17%  |
| 2      | 172       | 28.81%  |
| 3      | 18        | 3.02%   |
| 0      | 3         | 0.5%    |
| 4      | 2         | 0.34%   |
| 6      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 421       | 70.99%  |
| Yes       | 172       | 29.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 486       | 81.96%  |
| No        | 107       | 18.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 586       | 99.15%  |
| No        | 5         | 0.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 502       | 84.37%  |
| No        | 93        | 15.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 105       | 17.65%  |
| Germany                | 51        | 8.57%   |
| India                  | 33        | 5.55%   |
| UK                     | 32        | 5.38%   |
| Canada                 | 26        | 4.37%   |
| France                 | 22        | 3.7%    |
| Poland                 | 14        | 2.35%   |
| Italy                  | 14        | 2.35%   |
| Belgium                | 14        | 2.35%   |
| Hungary                | 13        | 2.18%   |
| Netherlands            | 12        | 2.02%   |
| Brazil                 | 12        | 2.02%   |
| Ukraine                | 11        | 1.85%   |
| Sweden                 | 11        | 1.85%   |
| Russia                 | 11        | 1.85%   |
| Australia              | 11        | 1.85%   |
| Turkey                 | 10        | 1.68%   |
| Switzerland            | 10        | 1.68%   |
| Spain                  | 9         | 1.51%   |
| Indonesia              | 8         | 1.34%   |
| Argentina              | 8         | 1.34%   |
| Greece                 | 7         | 1.18%   |
| Bangladesh             | 7         | 1.18%   |
| Romania                | 6         | 1.01%   |
| Norway                 | 6         | 1.01%   |
| China                  | 6         | 1.01%   |
| Bulgaria               | 6         | 1.01%   |
| Portugal               | 5         | 0.84%   |
| Finland                | 5         | 0.84%   |
| Estonia                | 5         | 0.84%   |
| Czechia                | 5         | 0.84%   |
| Vietnam                | 4         | 0.67%   |
| Slovenia               | 4         | 0.67%   |
| Mexico                 | 4         | 0.67%   |
| Ireland                | 4         | 0.67%   |
| Egypt                  | 4         | 0.67%   |
| Denmark                | 4         | 0.67%   |
| Chile                  | 4         | 0.67%   |
| Serbia                 | 3         | 0.5%    |
| Morocco                | 3         | 0.5%    |
| Malaysia               | 3         | 0.5%    |
| Lithuania              | 3         | 0.5%    |
| Latvia                 | 3         | 0.5%    |
| Colombia               | 3         | 0.5%    |
| Algeria                | 3         | 0.5%    |
| UAE                    | 2         | 0.34%   |
| South Africa           | 2         | 0.34%   |
| Singapore              | 2         | 0.34%   |
| Paraguay               | 2         | 0.34%   |
| Lebanon                | 2         | 0.34%   |
| Japan                  | 2         | 0.34%   |
| Iran                   | 2         | 0.34%   |
| Hong Kong              | 2         | 0.34%   |
| Guatemala              | 2         | 0.34%   |
| Dominican Republic     | 2         | 0.34%   |
| Croatia                | 2         | 0.34%   |
| Cambodia               | 2         | 0.34%   |
| Bosnia and Herzegovina | 2         | 0.34%   |
| Venezuela              | 1         | 0.17%   |
| Uruguay                | 1         | 0.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Paris              | 7         | 1.14%   |
| Berlin             | 7         | 1.14%   |
| Tallinn            | 5         | 0.81%   |
| Pune               | 5         | 0.81%   |
| Budapest           | 5         | 0.81%   |
| Sydney             | 4         | 0.65%   |
| Moscow             | 4         | 0.65%   |
| Kolkata            | 4         | 0.65%   |
| Dhaka              | 4         | 0.65%   |
| Bergheim           | 4         | 0.65%   |
| Athens             | 4         | 0.65%   |
| Ankara             | 4         | 0.65%   |
| Zurich             | 3         | 0.49%   |
| Warsaw             | 3         | 0.49%   |
| Stockholm          | 3         | 0.49%   |
| Spokane            | 3         | 0.49%   |
| Sofia              | 3         | 0.49%   |
| Rio de Janeiro     | 3         | 0.49%   |
| Milan              | 3         | 0.49%   |
| Madrid             | 3         | 0.49%   |
| Lisbon             | 3         | 0.49%   |
| Kyiv               | 3         | 0.49%   |
| Kuala Lumpur       | 3         | 0.49%   |
| Jakarta            | 3         | 0.49%   |
| Houston            | 3         | 0.49%   |
| Hanoi              | 3         | 0.49%   |
| Frankfurt am Main  | 3         | 0.49%   |
| Denver             | 3         | 0.49%   |
| Dagenham           | 3         | 0.49%   |
| Chicago            | 3         | 0.49%   |
| Cairo              | 3         | 0.49%   |
| Brooklyn           | 3         | 0.49%   |
| Bengaluru          | 3         | 0.49%   |
| Zagreb             | 2         | 0.32%   |
| Wroclaw            | 2         | 0.32%   |
| Wiesbaden          | 2         | 0.32%   |
| Tongi              | 2         | 0.32%   |
| Thessaloniki       | 2         | 0.32%   |
| Tehran             | 2         | 0.32%   |
| Stuttgart          | 2         | 0.32%   |
| St Petersburg      | 2         | 0.32%   |
| Singapore          | 2         | 0.32%   |
| Seville            | 2         | 0.32%   |
| Scottsdale         | 2         | 0.32%   |
| Santo Domingo Este | 2         | 0.32%   |
| Santiago           | 2         | 0.32%   |
| Plano              | 2         | 0.32%   |
| Phnom Penh         | 2         | 0.32%   |
| Oslo               | 2         | 0.32%   |
| Mumbai             | 2         | 0.32%   |
| Melbourne          | 2         | 0.32%   |
| London             | 2         | 0.32%   |
| Lokeren            | 2         | 0.32%   |
| Ljubljana          | 2         | 0.32%   |
| Lancaster          | 2         | 0.32%   |
| Kollow             | 2         | 0.32%   |
| Istanbul           | 2         | 0.32%   |
| Hamburg            | 2         | 0.32%   |
| Half Moon Bay      | 2         | 0.32%   |
| Guatemala City     | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 153       | 192    | 19.95%  |
| WDC                 | 111       | 138    | 14.47%  |
| Seagate             | 88        | 100    | 11.47%  |
| Toshiba             | 65        | 80     | 8.47%   |
| Kingston            | 42        | 48     | 5.48%   |
| SK Hynix            | 37        | 41     | 4.82%   |
| SanDisk             | 36        | 40     | 4.69%   |
| Intel               | 24        | 36     | 3.13%   |
| Crucial             | 23        | 25     | 3%      |
| HGST                | 19        | 24     | 2.48%   |
| Unknown             | 18        | 23     | 2.35%   |
| Micron Technology   | 16        | 16     | 2.09%   |
| Apple               | 14        | 18     | 1.83%   |
| A-DATA Technology   | 13        | 13     | 1.69%   |
| Hitachi             | 10        | 11     | 1.3%    |
| LITEON              | 9         | 10     | 1.17%   |
| PNY                 | 8         | 10     | 1.04%   |
| KIOXIA              | 8         | 10     | 1.04%   |
| Phison              | 6         | 7      | 0.78%   |
| JMicron             | 6         | 6      | 0.78%   |
| SPCC                | 5         | 5      | 0.65%   |
| LITEONIT            | 5         | 5      | 0.65%   |
| Mushkin             | 4         | 4      | 0.52%   |
| Corsair             | 4         | 4      | 0.52%   |
| China               | 4         | 4      | 0.52%   |
| Transcend           | 3         | 3      | 0.39%   |
| Lenovo              | 3         | 4      | 0.39%   |
| KingSpec            | 3         | 3      | 0.39%   |
| Intenso             | 3         | 3      | 0.39%   |
| Union Memory        | 2         | 2      | 0.26%   |
| Silicon Motion      | 2         | 3      | 0.26%   |
| PLEXTOR             | 2         | 2      | 0.26%   |
| Lexar               | 2         | 2      | 0.26%   |
| GOODRAM             | 2         | 6      | 0.26%   |
| Unknown             | 2         | 2      | 0.26%   |
| XPG                 | 1         | 1      | 0.13%   |
| W800S               | 1         | 3      | 0.13%   |
| Team                | 1         | 1      | 0.13%   |
| SSSTC               | 1         | 1      | 0.13%   |
| SABRENT             | 1         | 1      | 0.13%   |
| Patriot             | 1         | 4      | 0.13%   |
| OSCOO               | 1         | 2      | 0.13%   |
| NGFF                | 1         | 1      | 0.13%   |
| KingFast            | 1         | 1      | 0.13%   |
| KESU                | 1         | 1      | 0.13%   |
| HS-SSD-C100         | 1         | 2      | 0.13%   |
| Hewlett-Packard     | 1         | 2      | 0.13%   |
| Gigabyte Technology | 1         | 1      | 0.13%   |
| DOGFISH             | 1         | 1      | 0.13%   |
| addlink             | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 25        | 3.11%   |
| Samsung SSD 860 EVO 500GB             | 16        | 1.99%   |
| Toshiba MQ04ABF100 1TB                | 13        | 1.62%   |
| Toshiba MQ01ABD100 1TB                | 12        | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 10        | 1.24%   |
| Kingston SA400S37240G 240GB SSD       | 9         | 1.12%   |
| Samsung SSD 970 EVO Plus 1TB          | 8         | 1%      |
| Seagate ST1000LM048-2E7172 1TB        | 7         | 0.87%   |
| Seagate ST1000LM049-2GH172 1TB        | 6         | 0.75%   |
| Kingston SA400S37480G 480GB SSD       | 6         | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 5         | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 5         | 0.62%   |
| SanDisk SSD PLUS 480GB                | 5         | 0.62%   |
| Samsung SSD 850 EVO 500GB             | 5         | 0.62%   |
| JMicron Generic 240GB                 | 5         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB           | 5         | 0.62%   |
| Apple SSD SM0256F 256GB               | 5         | 0.62%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 4         | 0.5%    |
| WDC WD10SPZX-08Z10 1TB                | 4         | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB              | 4         | 0.5%    |
| SK Hynix HFM512GDJTNG-8310A 512GB     | 4         | 0.5%    |
| Samsung SSD 850 EVO 250GB             | 4         | 0.5%    |
| Samsung MZVLB512HBJQ-000L7 512GB      | 4         | 0.5%    |
| Samsung MZVLB1T0HBLR-000L2 1TB        | 4         | 0.5%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 4         | 0.5%    |
| HGST HTS721010A9E630 1TB              | 4         | 0.5%    |
| Crucial CT480BX500SSD1 480GB          | 4         | 0.5%    |
| A-DATA SX8200PNP 1TB                  | 4         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 3         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB              | 3         | 0.37%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 3         | 0.37%   |
| Toshiba MQ01ABF050 500GB              | 3         | 0.37%   |
| Toshiba MK7575GSX 752GB               | 3         | 0.37%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 3         | 0.37%   |
| Seagate ST9320325AS 320GB             | 3         | 0.37%   |
| Seagate ST9250315AS 250GB             | 3         | 0.37%   |
| SanDisk SSD U110 16GB                 | 3         | 0.37%   |
| SanDisk Extreme 55AE 500GB SSD        | 3         | 0.37%   |
| Samsung SSD 970 PRO 512GB             | 3         | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB        | 3         | 0.37%   |
| Samsung SSD 970 EVO Plus 250GB        | 3         | 0.37%   |
| Samsung SSD 860 QVO 1TB               | 3         | 0.37%   |
| Samsung SSD 860 EVO 1TB               | 3         | 0.37%   |
| Samsung MZNTY128HDHP-00000 128GB SSD  | 3         | 0.37%   |
| Samsung MZNLF128HCHP-00000 128GB SSD  | 3         | 0.37%   |
| Samsung MZALQ512HALU-000L2 512GB      | 3         | 0.37%   |
| PNY CS900 240GB SSD                   | 3         | 0.37%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 0.37%   |
| Kingston RBUSNS8154P3256GJ3 256GB     | 3         | 0.37%   |
| Intel SSDPEKNW010T8 1TB               | 3         | 0.37%   |
| HGST HTS545050A7E680 500GB            | 3         | 0.37%   |
| HGST HTS545050A7E380 500GB            | 3         | 0.37%   |
| Crucial CT500MX500SSD1 500GB          | 3         | 0.37%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 0.25%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 2         | 0.25%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 2         | 0.25%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 0.25%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 2         | 0.25%   |
| WDC WD20SPZX-22UA7T0 2TB              | 2         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 96     | 37.78%  |
| WDC                 | 55        | 74     | 24.44%  |
| Toshiba             | 46        | 55     | 20.44%  |
| HGST                | 19        | 24     | 8.44%   |
| Hitachi             | 10        | 11     | 4.44%   |
| Samsung Electronics | 3         | 3      | 1.33%   |
| Unknown             | 2         | 2      | 0.89%   |
| SABRENT             | 1         | 1      | 0.44%   |
| KESU                | 1         | 1      | 0.44%   |
| Intenso             | 1         | 1      | 0.44%   |
| Hewlett-Packard     | 1         | 2      | 0.44%   |
| Apple               | 1         | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 85        | 111    | 27.87%  |
| SanDisk             | 32        | 35     | 10.49%  |
| Kingston            | 32        | 36     | 10.49%  |
| WDC                 | 23        | 24     | 7.54%   |
| Crucial             | 20        | 20     | 6.56%   |
| Apple               | 10        | 12     | 3.28%   |
| SK Hynix            | 9         | 10     | 2.95%   |
| Micron Technology   | 9         | 9      | 2.95%   |
| Intel               | 9         | 19     | 2.95%   |
| PNY                 | 8         | 10     | 2.62%   |
| A-DATA Technology   | 8         | 8      | 2.62%   |
| LITEON              | 7         | 8      | 2.3%    |
| Toshiba             | 6         | 8      | 1.97%   |
| SPCC                | 5         | 5      | 1.64%   |
| LITEONIT            | 5         | 5      | 1.64%   |
| JMicron             | 5         | 5      | 1.64%   |
| China               | 4         | 4      | 1.31%   |
| Transcend           | 3         | 3      | 0.98%   |
| KingSpec            | 3         | 3      | 0.98%   |
| Seagate             | 2         | 2      | 0.66%   |
| PLEXTOR             | 2         | 2      | 0.66%   |
| Mushkin             | 2         | 2      | 0.66%   |
| Lexar               | 2         | 2      | 0.66%   |
| Intenso             | 2         | 2      | 0.66%   |
| GOODRAM             | 2         | 6      | 0.66%   |
| W800S               | 1         | 3      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |
| Team                | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| Patriot             | 1         | 4      | 0.33%   |
| NGFF                | 1         | 1      | 0.33%   |
| KingFast            | 1         | 1      | 0.33%   |
| HS-SSD-C100         | 1         | 2      | 0.33%   |
| DOGFISH             | 1         | 1      | 0.33%   |
| Corsair             | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 274       | 367    | 37.79%  |
| HDD     | 220       | 271    | 30.34%  |
| NVMe    | 211       | 260    | 29.1%   |
| MMC     | 17        | 22     | 2.34%   |
| Unknown | 3         | 3      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 428       | 598    | 62.03%  |
| NVMe | 211       | 260    | 30.58%  |
| SAS  | 34        | 43     | 4.93%   |
| MMC  | 17        | 22     | 2.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 300       | 389    | 59.88%  |
| 0.51-1.0   | 183       | 230    | 36.53%  |
| 1.01-2.0   | 12        | 13     | 2.4%    |
| 3.01-4.0   | 5         | 5      | 1%      |
| 2.01-3.0   | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 164       | 27.06%  |
| 251-500        | 144       | 23.76%  |
| 501-1000       | 101       | 16.67%  |
| 1001-2000      | 60        | 9.9%    |
| 51-100         | 37        | 6.11%   |
| Unknown        | 33        | 5.45%   |
| 1-20           | 25        | 4.13%   |
| More than 3000 | 22        | 3.63%   |
| 21-50          | 10        | 1.65%   |
| 2001-3000      | 10        | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 189       | 30.19%  |
| 21-50          | 135       | 21.57%  |
| 101-250        | 100       | 15.97%  |
| 51-100         | 79        | 12.62%  |
| 251-500        | 45        | 7.19%   |
| Unknown        | 33        | 5.27%   |
| 501-1000       | 25        | 3.99%   |
| More than 3000 | 10        | 1.6%    |
| 1001-2000      | 9         | 1.44%   |
| 0              | 1         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 5         | 5      | 5.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 5.95%   |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 2.38%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 2.38%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 2.38%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 2.38%   |
| Seagate ST1000LM049-2GH172 1TB                 | 2         | 2      | 2.38%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 2.38%   |
| HGST HTS541010A9E680 1TB                       | 2         | 3      | 2.38%   |
| WDC WD6400BEVT-60A0RT0 640GB                   | 1         | 9      | 1.19%   |
| WDC WD5000L 500GB                              | 1         | 1      | 1.19%   |
| WDC WD5000BPVT-22HXZT1 500GB                   | 1         | 1      | 1.19%   |
| WDC WD3200BPVT-00JJ5T0 320GB                   | 1         | 1      | 1.19%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1         | 1      | 1.19%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 1.19%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.19%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 1.19%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 1.19%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 1.19%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 1.19%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD           | 1         | 1      | 1.19%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 1.19%   |
| Toshiba MQ01ACF050 500GB                       | 1         | 1      | 1.19%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.19%   |
| Toshiba MK7575GSX 752GB                        | 1         | 1      | 1.19%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 1.19%   |
| Toshiba MK5061GSYN 500GB                       | 1         | 1      | 1.19%   |
| Toshiba MK3261GSYN 320GB                       | 1         | 1      | 1.19%   |
| Toshiba MK1237GSX 120GB                        | 1         | 1      | 1.19%   |
| SSSTC CVB-8D128-HP 128GB SSD                   | 1         | 1      | 1.19%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 1.19%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 1.19%   |
| Seagate ST9500420AS 500GB                      | 1         | 2      | 1.19%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 1.19%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 1.19%   |
| Seagate ST9160314AS 160GB                      | 1         | 1      | 1.19%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 1.19%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 1.19%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 1         | 1      | 1.19%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.19%   |
| SanDisk SSD PLUS 1000GB                        | 1         | 2      | 1.19%   |
| SanDisk SSD i100 24GB                          | 1         | 1      | 1.19%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB    | 1         | 1      | 1.19%   |
| Samsung Electronics SSD 860 EVO 1TB            | 1         | 1      | 1.19%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB   | 1         | 1      | 1.19%   |
| PLEXTOR PX-128M6S 128GB SSD                    | 1         | 1      | 1.19%   |
| Mushkin MKNSSDCR250GB-7-OEM                    | 1         | 1      | 1.19%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 1.19%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.19%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 1.19%   |
| LITEONIT LCT-512M3S 512GB SSD                  | 1         | 1      | 1.19%   |
| LITEONIT LAT-256M3S 256GB SSD                  | 1         | 1      | 1.19%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB           | 1         | 1      | 1.19%   |
| Kingston SUV500M8960G 960GB SSD                | 1         | 1      | 1.19%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 1.19%   |
| Intel SSDSC2CT120A3 120GB                      | 1         | 1      | 1.19%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 1.19%   |
| Intel SSDSA2M160G2GC 160GB                     | 1         | 9      | 1.19%   |
| Intel SSDPEKKW256G7 256GB                      | 1         | 1      | 1.19%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 1.19%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 30.12%  |
| WDC                 | 11        | 19     | 13.25%  |
| Toshiba             | 11        | 12     | 13.25%  |
| HGST                | 7         | 9      | 8.43%   |
| Intel               | 4         | 12     | 4.82%   |
| SanDisk             | 3         | 4      | 3.61%   |
| Samsung Electronics | 3         | 3      | 3.61%   |
| Micron Technology   | 3         | 3      | 3.61%   |
| LITEONIT            | 2         | 2      | 2.41%   |
| Kingston            | 2         | 2      | 2.41%   |
| Hitachi             | 2         | 2      | 2.41%   |
| Crucial             | 2         | 2      | 2.41%   |
| SSSTC               | 1         | 1      | 1.2%    |
| SK Hynix            | 1         | 1      | 1.2%    |
| PLEXTOR             | 1         | 1      | 1.2%    |
| Mushkin             | 1         | 1      | 1.2%    |
| Lenovo              | 1         | 1      | 1.2%    |
| Corsair             | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |
| A-DATA Technology   | 1         | 1      | 1.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 27     | 44.64%  |
| WDC     | 11        | 19     | 19.64%  |
| Toshiba | 10        | 11     | 17.86%  |
| HGST    | 7         | 9      | 12.5%   |
| Hitachi | 2         | 2      | 3.57%   |
| Apple   | 1         | 1      | 1.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 69     | 68.29%  |
| SSD  | 23        | 33     | 28.05%  |
| NVMe | 3         | 3      | 3.66%   |

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
| Works    | 453       | 656    | 69.16%  |
| Detected | 118       | 158    | 18.02%  |
| Malfunc  | 80        | 105    | 12.21%  |
| Failed   | 4         | 4      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 423       | 58.83%  |
| Samsung Electronics          | 77        | 10.71%  |
| AMD                          | 71        | 9.87%   |
| Sandisk                      | 38        | 5.29%   |
| SK Hynix                     | 28        | 3.89%   |
| KIOXIA                       | 13        | 1.81%   |
| Phison Electronics           | 11        | 1.53%   |
| Toshiba America Info Systems | 10        | 1.39%   |
| Kingston Technology Company  | 10        | 1.39%   |
| Micron Technology            | 7         | 0.97%   |
| Silicon Motion               | 5         | 0.7%    |
| ADATA Technology             | 5         | 0.7%    |
| Nvidia                       | 4         | 0.56%   |
| Micron/Crucial Technology    | 4         | 0.56%   |
| Lenovo                       | 3         | 0.42%   |
| Apple                        | 3         | 0.42%   |
| Union Memory (Shenzhen)      | 2         | 0.28%   |
| Lite-On Technology           | 2         | 0.28%   |
| Unknown                      | 1         | 0.14%   |
| Marvell Technology Group     | 1         | 0.14%   |
| ASMedia Technology           | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 73        | 9.85%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 70        | 9.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 47        | 6.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 47        | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 41        | 5.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 34        | 4.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 34        | 4.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 3.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 2.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 1.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 12        | 1.62%   |
| KIOXIA Non-Volatile memory controller                                            | 12        | 1.62%   |
| SK Hynix Gold P31 SSD                                                            | 11        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 10        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                  | 10        | 1.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.21%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 8         | 1.08%   |
| Intel SSD 660P Series                                                            | 8         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 1.08%   |
| Phison E12 NVMe Controller                                                       | 7         | 0.94%   |
| Micron Non-Volatile memory controller                                            | 7         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 0.94%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 6         | 0.81%   |
| Samsung Apple PCIe SSD                                                           | 6         | 0.81%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 6         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.81%   |
| SK Hynix Non-Volatile memory controller                                          | 5         | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.54%   |
| SK Hynix BC511                                                                   | 4         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.54%   |
| Sandisk Non-Volatile memory controller                                           | 4         | 0.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.54%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.54%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.4%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.4%    |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.4%    |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.4%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.27%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.27%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.27%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.27%   |
| Samsung Electronics SATA controller                                              | 2         | 0.27%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.27%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.27%   |
| Micron/Crucial Non-Volatile memory controller                                    | 2         | 0.27%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 443       | 61.79%  |
| NVMe | 211       | 29.43%  |
| RAID | 49        | 6.83%   |
| IDE  | 14        | 1.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 489       | 82.74%  |
| AMD    | 102       | 17.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 20        | 3.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 19        | 3.21%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 15        | 2.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 15        | 2.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 14        | 2.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 13        | 2.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz               | 13        | 2.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 8         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 8         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 8         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 8         | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 8         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 8         | 1.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 8         | 1.35%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 7         | 1.18%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 7         | 1.18%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 6         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 6         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 6         | 1.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 6         | 1.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 6         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 5         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 5         | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 5         | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 5         | 0.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 5         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 5         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 5         | 0.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 5         | 0.85%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 5         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 4         | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 4         | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 0.68%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 4         | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.68%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.68%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 4         | 0.68%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 4         | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 0.68%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 4         | 0.68%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 4         | 0.68%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 4         | 0.68%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 4         | 0.68%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz                | 3         | 0.51%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 3         | 0.51%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 3         | 0.51%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 3         | 0.51%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 3         | 0.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 3         | 0.51%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 3         | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 3         | 0.51%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 3         | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 3         | 0.51%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 3         | 0.51%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 3         | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 0.51%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 3         | 0.51%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 3         | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 3         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 189       | 31.98%  |
| Intel Core i7           | 184       | 31.13%  |
| Intel Core i3           | 35        | 5.92%   |
| AMD Ryzen 5             | 31        | 5.25%   |
| AMD Ryzen 7             | 27        | 4.57%   |
| Other                   | 17        | 2.88%   |
| Intel Pentium           | 17        | 2.88%   |
| Intel Core 2 Duo        | 15        | 2.54%   |
| Intel Celeron           | 14        | 2.37%   |
| AMD Ryzen 3             | 9         | 1.52%   |
| AMD A6                  | 7         | 1.18%   |
| Intel Atom              | 5         | 0.85%   |
| AMD A10                 | 5         | 0.85%   |
| Intel Pentium Dual-Core | 4         | 0.68%   |
| AMD Ryzen 9             | 4         | 0.68%   |
| AMD Ryzen 7 PRO         | 4         | 0.68%   |
| AMD A12                 | 4         | 0.68%   |
| Intel Core m3           | 3         | 0.51%   |
| AMD A8                  | 3         | 0.51%   |
| AMD A4                  | 3         | 0.51%   |
| Intel Xeon              | 2         | 0.34%   |
| Intel Pentium Silver    | 2         | 0.34%   |
| Intel Core i9           | 2         | 0.34%   |
| Intel Core m7           | 1         | 0.17%   |
| Intel Core M            | 1         | 0.17%   |
| Intel Core 2            | 1         | 0.17%   |
| AMD E2                  | 1         | 0.17%   |
| AMD Athlon II           | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 286       | 48.39%  |
| 4      | 212       | 35.87%  |
| 6      | 53        | 8.97%   |
| 8      | 36        | 6.09%   |
| 1      | 3         | 0.51%   |
| 12     | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 591       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 504       | 85.28%  |
| 1      | 87        | 14.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 590       | 99.83%  |
| Unknown        | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 13.71%  |
| 0x206a7    | 43        | 7.19%   |
| 0x806ea    | 37        | 6.19%   |
| 0x906ea    | 34        | 5.69%   |
| 0x806e9    | 32        | 5.35%   |
| 0x406e3    | 29        | 4.85%   |
| 0x306a9    | 28        | 4.68%   |
| 0x306c3    | 27        | 4.52%   |
| 0x40651    | 21        | 3.51%   |
| 0x906e9    | 19        | 3.18%   |
| 0x806ec    | 18        | 3.01%   |
| 0x306d4    | 17        | 2.84%   |
| 0x20655    | 17        | 2.84%   |
| 0xa0652    | 14        | 2.34%   |
| 0x08108102 | 14        | 2.34%   |
| 0x08600106 | 13        | 2.17%   |
| 0x706e5    | 10        | 1.67%   |
| 0x08108109 | 10        | 1.67%   |
| 0x806c1    | 9         | 1.51%   |
| 0x30678    | 9         | 1.51%   |
| 0x1067a    | 8         | 1.34%   |
| 0x806eb    | 6         | 1%      |
| 0x506e3    | 6         | 1%      |
| 0x08600103 | 6         | 1%      |
| 0x0810100b | 6         | 1%      |
| 0x06006705 | 6         | 1%      |
| 0x106e5    | 5         | 0.84%   |
| 0x10676    | 5         | 0.84%   |
| 0x0a50000c | 5         | 0.84%   |
| 0x08600104 | 5         | 0.84%   |
| 0x806d1    | 4         | 0.67%   |
| 0x706a8    | 4         | 0.67%   |
| 0x406c4    | 4         | 0.67%   |
| 0x40661    | 4         | 0.67%   |
| 0x20652    | 4         | 0.67%   |
| 0x0a50000b | 4         | 0.67%   |
| 0x406c3    | 3         | 0.5%    |
| 0x106ca    | 3         | 0.5%    |
| 0x08608103 | 3         | 0.5%    |
| 0x0600611a | 3         | 0.5%    |
| 0x06006118 | 3         | 0.5%    |
| 0x706a1    | 2         | 0.33%   |
| 0x506c9    | 2         | 0.33%   |
| 0x06006704 | 2         | 0.33%   |
| 0x906ed    | 1         | 0.17%   |
| 0x6fd      | 1         | 0.17%   |
| 0x6fb      | 1         | 0.17%   |
| 0x6f6      | 1         | 0.17%   |
| 0x08701013 | 1         | 0.17%   |
| 0x08101007 | 1         | 0.17%   |
| 0x08101004 | 1         | 0.17%   |
| 0x07030105 | 1         | 0.17%   |
| 0x06006110 | 1         | 0.17%   |
| 0x06001119 | 1         | 0.17%   |
| 0x06001116 | 1         | 0.17%   |
| 0x010000b6 | 1         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 168       | 28.38%  |
| Haswell       | 56        | 9.46%   |
| SandyBridge   | 49        | 8.28%   |
| Skylake       | 40        | 6.76%   |
| IvyBridge     | 37        | 6.25%   |
| Zen+          | 27        | 4.56%   |
| Zen 2         | 26        | 4.39%   |
| Westmere      | 26        | 4.39%   |
| Excavator     | 20        | 3.38%   |
| Broadwell     | 20        | 3.38%   |
| Silvermont    | 17        | 2.87%   |
| CometLake     | 16        | 2.7%    |
| Penryn        | 15        | 2.53%   |
| IceLake       | 14        | 2.36%   |
| Zen 3         | 11        | 1.86%   |
| TigerLake     | 10        | 1.69%   |
| Zen           | 8         | 1.35%   |
| Goldmont plus | 6         | 1.01%   |
| Nehalem       | 5         | 0.84%   |
| Core          | 5         | 0.84%   |
| Unknown       | 4         | 0.68%   |
| Piledriver    | 3         | 0.51%   |
| Bonnell       | 3         | 0.51%   |
| Puma          | 2         | 0.34%   |
| Goldmont      | 2         | 0.34%   |
| K10           | 1         | 0.17%   |
| Jaguar        | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 451       | 56.66%  |
| Nvidia | 217       | 27.26%  |
| AMD    | 128       | 16.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 43        | 5.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 4.79%   |
| Intel UHD Graphics 620                                                                   | 37        | 4.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 4.29%   |
| Intel HD Graphics 620                                                                    | 31        | 3.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 3.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 3.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 3.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 2.7%    |
| AMD Renoir                                                                               | 22        | 2.7%    |
| Intel HD Graphics 630                                                                    | 20        | 2.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 2.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 17        | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.23%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 1.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.23%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.1%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 1.1%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.98%   |
| AMD Cezanne                                                                              | 8         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.86%   |
| Intel HD Graphics 530                                                                    | 7         | 0.86%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.74%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 6         | 0.74%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 5         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.61%   |
| Nvidia TU117M                                                                            | 4         | 0.49%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.49%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.49%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 0.49%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.49%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.49%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 4         | 0.49%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.37%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.37%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.37%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.37%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.37%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.37%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 3         | 0.37%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 3         | 0.37%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 265       | 44.84%  |
| Intel + Nvidia | 161       | 27.24%  |
| 1 x AMD        | 73        | 12.35%  |
| 1 x Nvidia     | 36        | 6.09%   |
| Intel + AMD    | 24        | 4.06%   |
| AMD + Nvidia   | 18        | 3.05%   |
| 2 x AMD        | 13        | 2.2%    |
| 2 x Nvidia     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 469       | 78.96%  |
| Proprietary | 116       | 19.53%  |
| Unknown     | 9         | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 416       | 69.33%  |
| 1.01-2.0   | 61        | 10.17%  |
| 0.01-0.5   | 54        | 9%      |
| 0.51-1.0   | 30        | 5%      |
| 3.01-4.0   | 24        | 4%      |
| 5.01-6.0   | 9         | 1.5%    |
| 7.01-8.0   | 4         | 0.67%   |
| 2.01-3.0   | 2         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 126       | 18.05%  |
| AU Optronics            | 114       | 16.33%  |
| Chimei Innolux          | 103       | 14.76%  |
| BOE                     | 89        | 12.75%  |
| Samsung Electronics     | 49        | 7.02%   |
| Sharp                   | 26        | 3.72%   |
| Dell                    | 23        | 3.3%    |
| Apple                   | 21        | 3.01%   |
| Goldstar                | 20        | 2.87%   |
| Lenovo                  | 17        | 2.44%   |
| PANDA                   | 10        | 1.43%   |
| Hewlett-Packard         | 9         | 1.29%   |
| BenQ                    | 9         | 1.29%   |
| Chi Mei Optoelectronics | 8         | 1.15%   |
| CSO                     | 6         | 0.86%   |
| AOC                     | 6         | 0.86%   |
| Sony                    | 5         | 0.72%   |
| Philips                 | 5         | 0.72%   |
| Acer                    | 5         | 0.72%   |
| Panasonic               | 4         | 0.57%   |
| InfoVision              | 4         | 0.57%   |
| Ancor Communications    | 4         | 0.57%   |
| ASUSTek Computer        | 3         | 0.43%   |
| ViewSonic               | 2         | 0.29%   |
| Sceptre Tech            | 2         | 0.29%   |
| LG Philips              | 2         | 0.29%   |
| InnoLux Display         | 2         | 0.29%   |
| Iiyama                  | 2         | 0.29%   |
| Eizo                    | 2         | 0.29%   |
| CPT                     | 2         | 0.29%   |
| Westinghouse            | 1         | 0.14%   |
| VIE                     | 1         | 0.14%   |
| Seiki                   | 1         | 0.14%   |
| Philco                  | 1         | 0.14%   |
| Packard Bell            | 1         | 0.14%   |
| NCS                     | 1         | 0.14%   |
| MStar                   | 1         | 0.14%   |
| MSI                     | 1         | 0.14%   |
| Mi                      | 1         | 0.14%   |
| Medion                  | 1         | 0.14%   |
| LPL                     | 1         | 0.14%   |
| LGD                     | 1         | 0.14%   |
| JDI                     | 1         | 0.14%   |
| Hyundai ImageQuest      | 1         | 0.14%   |
| Hitachi                 | 1         | 0.14%   |
| HannStar                | 1         | 0.14%   |
| Fujitsu Siemens         | 1         | 0.14%   |
| Daewoo                  | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 1.14%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 1%      |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 5         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 5         | 0.72%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.57%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.57%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 4         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 4         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.57%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.57%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.57%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 4         | 0.57%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.57%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 4         | 0.57%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.43%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 3         | 0.43%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 3         | 0.43%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 3         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.43%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.43%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 3         | 0.43%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.43%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x174mm 14.0-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 3         | 0.43%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                 | 3         | 0.43%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch | 2         | 0.29%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch               | 2         | 0.29%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC454A 3200x1800 293x165mm 13.2-inch | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch | 2         | 0.29%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 2         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 2         | 0.29%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD065A 1920x1080 340x190mm 15.3-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD0615 1920x1080 382x215mm 17.3-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 326       | 50.62%  |
| 1366x768 (WXGA)    | 157       | 24.38%  |
| 1600x900 (HD+)     | 33        | 5.12%   |
| 1280x800 (WXGA)    | 20        | 3.11%   |
| 3840x2160 (4K)     | 19        | 2.95%   |
| 2560x1440 (QHD)    | 15        | 2.33%   |
| 2880x1800          | 10        | 1.55%   |
| 1920x1200 (WUXGA)  | 9         | 1.4%    |
| 2560x1600          | 7         | 1.09%   |
| 2560x1080          | 7         | 1.09%   |
| 3200x1800 (QHD+)   | 6         | 0.93%   |
| 1440x900 (WXGA+)   | 6         | 0.93%   |
| 1280x1024 (SXGA)   | 6         | 0.93%   |
| 2160x1440          | 5         | 0.78%   |
| 1680x1050 (WSXGA+) | 4         | 0.62%   |
| 3440x1440          | 3         | 0.47%   |
| 3840x2400          | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1360x768           | 2         | 0.31%   |
| 1024x600           | 2         | 0.31%   |
| 3840x1600          | 1         | 0.16%   |
| 3000x2000          | 1         | 0.16%   |
| 2160x1350          | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 286       | 41.21%  |
| 14      | 93        | 13.4%   |
| 13      | 93        | 13.4%   |
| 17      | 59        | 8.5%    |
| 12      | 24        | 3.46%   |
| 27      | 23        | 3.31%   |
| 23      | 23        | 3.31%   |
| 24      | 22        | 3.17%   |
| 21      | 16        | 2.31%   |
| 34      | 9         | 1.3%    |
| 11      | 6         | 0.86%   |
| 19      | 5         | 0.72%   |
| 18      | 5         | 0.72%   |
| Unknown | 5         | 0.72%   |
| 16      | 4         | 0.58%   |
| 54      | 3         | 0.43%   |
| 31      | 3         | 0.43%   |
| 22      | 3         | 0.43%   |
| 10      | 3         | 0.43%   |
| 84      | 2         | 0.29%   |
| 72      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 47      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 37      | 1         | 0.14%   |
| 35      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 417       | 60.7%   |
| 201-300     | 85        | 12.37%  |
| 351-400     | 65        | 9.46%   |
| 501-600     | 64        | 9.32%   |
| 401-500     | 26        | 3.78%   |
| 701-800     | 10        | 1.46%   |
| 1001-1500   | 5         | 0.73%   |
| Unknown     | 5         | 0.73%   |
| 601-700     | 4         | 0.58%   |
| 801-900     | 3         | 0.44%   |
| 1501-2000   | 3         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 523       | 85.6%   |
| 16/10   | 56        | 9.17%   |
| 3/2     | 11        | 1.8%    |
| 21/9    | 11        | 1.8%    |
| 5/4     | 4         | 0.65%   |
| Unknown | 3         | 0.49%   |
| 6/5     | 2         | 0.33%   |
| 4/3     | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 280       | 40.46%  |
| 81-90          | 144       | 20.81%  |
| 201-250        | 56        | 8.09%   |
| 121-130        | 54        | 7.8%    |
| 71-80          | 43        | 6.21%   |
| 301-350        | 23        | 3.32%   |
| 61-70          | 20        | 2.89%   |
| 351-500        | 15        | 2.17%   |
| 141-150        | 8         | 1.16%   |
| More than 1000 | 7         | 1.01%   |
| 91-100         | 7         | 1.01%   |
| 51-60          | 6         | 0.87%   |
| 151-200        | 6         | 0.87%   |
| 251-300        | 5         | 0.72%   |
| Unknown        | 5         | 0.72%   |
| 131-140        | 4         | 0.58%   |
| 111-120        | 4         | 0.58%   |
| 41-50          | 3         | 0.43%   |
| 501-1000       | 2         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 323       | 47.29%  |
| 101-120       | 179       | 26.21%  |
| 51-100        | 97        | 14.2%   |
| 161-240       | 52        | 7.61%   |
| More than 240 | 21        | 3.07%   |
| 1-50          | 6         | 0.88%   |
| Unknown       | 5         | 0.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 477       | 79.63%  |
| 2     | 99        | 16.53%  |
| 3     | 13        | 2.17%   |
| 0     | 10        | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 343       | 37.9%   |
| Realtek Semiconductor             | 311       | 34.36%  |
| Qualcomm Atheros                  | 137       | 15.14%  |
| Broadcom                          | 44        | 4.86%   |
| Broadcom Limited                  | 11        | 1.22%   |
| Dell                              | 7         | 0.77%   |
| Marvell Technology Group          | 5         | 0.55%   |
| TP-Link                           | 4         | 0.44%   |
| Sierra Wireless                   | 4         | 0.44%   |
| MEDIATEK                          | 4         | 0.44%   |
| ASIX Electronics                  | 4         | 0.44%   |
| Samsung Electronics               | 3         | 0.33%   |
| Ralink                            | 3         | 0.33%   |
| Nvidia                            | 3         | 0.33%   |
| Lenovo                            | 3         | 0.33%   |
| Ericsson Business Mobile Networks | 3         | 0.33%   |
| Ralink Technology                 | 2         | 0.22%   |
| Hewlett-Packard                   | 2         | 0.22%   |
| Xiaomi                            | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| Qualcomm                          | 1         | 0.11%   |
| NetGear                           | 1         | 0.11%   |
| Motorola PCS                      | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| Google                            | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |
| DisplayLink                       | 1         | 0.11%   |
| ASUSTek Computer                  | 1         | 0.11%   |
| Apple                             | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 225       | 20%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 48        | 4.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 3.73%   |
| Intel Wireless 8265 / 8275                                        | 37        | 3.29%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 2.67%   |
| Intel Wireless 7260                                               | 28        | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 24        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.96%   |
| Intel Wireless 8260                                               | 22        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 19        | 1.69%   |
| Intel Wireless 7265                                               | 17        | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.16%   |
| Intel Wireless 3165                                               | 12        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.89%   |
| Intel Wireless-AC 9260                                            | 9         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.8%    |
| Intel Centrino Advanced-N 6200                                    | 9         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 8         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.71%   |
| Intel Centrino Advanced-N 6235                                    | 8         | 0.71%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 6         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.44%   |
| Intel Wireless 3160                                               | 5         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.44%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 5         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.36%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.36%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.36%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 333       | 55.04%  |
| Qualcomm Atheros                | 120       | 19.83%  |
| Realtek Semiconductor           | 86        | 14.21%  |
| Broadcom                        | 34        | 5.62%   |
| Broadcom Limited                | 8         | 1.32%   |
| Sierra Wireless                 | 4         | 0.66%   |
| MEDIATEK                        | 4         | 0.66%   |
| TP-Link                         | 3         | 0.5%    |
| Ralink                          | 3         | 0.5%    |
| Dell                            | 3         | 0.5%    |
| Ralink Technology               | 2         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.17%   |
| NetGear                         | 1         | 0.17%   |
| Microsoft                       | 1         | 0.17%   |
| Fibocom                         | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 48        | 7.91%   |
| Intel Wireless 8265 / 8275                                     | 37        | 6.1%    |
| Intel Wi-Fi 6 AX200                                            | 34        | 5.6%    |
| Intel Wireless 7260                                            | 28        | 4.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 4.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 24        | 3.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22        | 3.62%   |
| Intel Wireless 8260                                            | 22        | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 19        | 3.13%   |
| Intel Wireless 7265                                            | 17        | 2.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.47%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 2.14%   |
| Intel Wireless 3165                                            | 12        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.65%   |
| Intel Wireless-AC 9260                                         | 9         | 1.48%   |
| Intel Centrino Advanced-N 6200                                 | 9         | 1.48%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 8         | 1.32%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 1.32%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.82%   |
| Intel Wireless 3160                                            | 5         | 0.82%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.66%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.66%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.66%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.33%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.33%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]           | 2         | 0.33%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 2         | 0.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 0.33%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 0.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 0.33%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.16%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.16%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 0.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 290       | 58.12%  |
| Intel                    | 133       | 26.65%  |
| Qualcomm Atheros         | 31        | 6.21%   |
| Broadcom                 | 16        | 3.21%   |
| Marvell Technology Group | 5         | 1%      |
| ASIX Electronics         | 4         | 0.8%    |
| Samsung Electronics      | 3         | 0.6%    |
| Nvidia                   | 3         | 0.6%    |
| Lenovo                   | 3         | 0.6%    |
| Broadcom Limited         | 3         | 0.6%    |
| Xiaomi                   | 1         | 0.2%    |
| TP-Link                  | 1         | 0.2%    |
| Qualcomm                 | 1         | 0.2%    |
| Motorola PCS             | 1         | 0.2%    |
| MediaTek                 | 1         | 0.2%    |
| JMicron Technology       | 1         | 0.2%    |
| DisplayLink              | 1         | 0.2%    |
| Apple                    | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 225       | 44.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 42        | 8.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 30        | 5.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 4.72%   |
| Intel Ethernet Connection I217-LM                                              | 17        | 3.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 13        | 2.56%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 1.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 9         | 1.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 1.57%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.98%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.59%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.59%   |
| Intel Ethernet Connection (10) I219-LM                                         | 3         | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.39%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.39%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.39%   |
| Intel Ethernet controller                                                      | 2         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.39%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.39%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.39%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.39%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.2%    |
| TP-Link USB 10/100/1000 LAN                                                    | 1         | 0.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.2%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.2%    |
| Qualcomm Mi A1                                                                 | 1         | 0.2%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.2%    |
| Motorola PCS moto g(30)                                                        | 1         | 0.2%    |
| MediaTek NOA N2                                                                | 1         | 0.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.2%    |
| Lenovo VIBEUI                                                                  | 1         | 0.2%    |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.2%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.2%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.2%    |
| Intel Ethernet Controller I225-V                                               | 1         | 0.2%    |
| Intel Ethernet Connection I218-V                                               | 1         | 0.2%    |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 587       | 54.35%  |
| Ethernet | 483       | 44.72%  |
| Modem    | 10        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 510       | 74.78%  |
| Ethernet | 172       | 25.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 448       | 75.68%  |
| 1     | 134       | 22.64%  |
| 3     | 8         | 1.35%   |
| 0     | 2         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 477       | 79.77%  |
| Yes  | 121       | 20.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 50.2%   |
| Realtek Semiconductor           | 59        | 11.71%  |
| Qualcomm Atheros Communications | 51        | 10.12%  |
| IMC Networks                    | 27        | 5.36%   |
| Lite-On Technology              | 26        | 5.16%   |
| Broadcom                        | 26        | 5.16%   |
| Apple                           | 20        | 3.97%   |
| Foxconn / Hon Hai               | 15        | 2.98%   |
| Dell                            | 9         | 1.79%   |
| Cambridge Silicon Radio         | 4         | 0.79%   |
| Toshiba                         | 3         | 0.6%    |
| ASUSTek Computer                | 3         | 0.6%    |
| Realtek                         | 2         | 0.4%    |
| Hewlett-Packard                 | 2         | 0.4%    |
| Ralink Technology               | 1         | 0.2%    |
| Ralink                          | 1         | 0.2%    |
| Dynex                           | 1         | 0.2%    |
| Chicony Electronics             | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 117       | 23.21%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 39        | 7.74%   |
| Intel Bluetooth Device                                                              | 37        | 7.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 37        | 7.34%   |
| Intel AX200 Bluetooth                                                               | 32        | 6.35%   |
| Realtek Bluetooth Radio                                                             | 31        | 6.15%   |
| Lite-On Bluetooth Device                                                            | 22        | 4.37%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 2.38%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 2.18%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.79%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.79%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.19%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 1.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.6%    |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.6%    |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.6%    |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.6%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.6%    |
| Toshiba Bluetooth Device                                                            | 2         | 0.4%    |
| Realtek Bluetooth Radio                                                             | 2         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.4%    |
| IMC Networks Wireless_Device                                                        | 2         | 0.4%    |
| IMC Networks BCM20702A0                                                             | 2         | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.4%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.4%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.4%    |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.2%    |
| Realtek CSR BS8510                                                                  | 1         | 0.2%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.2%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.2%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.2%    |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.2%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.2%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.2%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.2%    |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.2%    |
| Broadcom Bluetooth                                                                  | 1         | 0.2%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.2%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.2%    |
| Broadcom BCM2046 Bluetooth Device                                                   | 1         | 0.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.2%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.2%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 483       | 63.05%  |
| Nvidia                    | 131       | 17.1%   |
| AMD                       | 111       | 14.49%  |
| Logitech                  | 5         | 0.65%   |
| Realtek Semiconductor     | 4         | 0.52%   |
| Lenovo                    | 3         | 0.39%   |
| Kingston Technology       | 3         | 0.39%   |
| GN Netcom                 | 3         | 0.39%   |
| C-Media Electronics       | 3         | 0.39%   |
| BEHRINGER International   | 3         | 0.39%   |
| VIA Technologies          | 1         | 0.13%   |
| USB-MIC                   | 1         | 0.13%   |
| Texas Instruments         | 1         | 0.13%   |
| SteelSeries ApS           | 1         | 0.13%   |
| Sennheiser Communications | 1         | 0.13%   |
| Samsung Electronics       | 1         | 0.13%   |
| Samson Technologies       | 1         | 0.13%   |
| No brand                  | 1         | 0.13%   |
| Mark of the Unicorn       | 1         | 0.13%   |
| LG Electronics            | 1         | 0.13%   |
| JMTek                     | 1         | 0.13%   |
| Generalplus Technology    | 1         | 0.13%   |
| Focusrite-Novation        | 1         | 0.13%   |
| Dell                      | 1         | 0.13%   |
| Corsair                   | 1         | 0.13%   |
| Barco Display Systems     | 1         | 0.13%   |
| Asahi Kasei Microsystems  | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 107       | 11.64%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 73        | 7.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 4.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 43        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 43        | 4.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 34        | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 31        | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 31        | 3.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 2.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 2.39%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 2.39%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 2.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 2.18%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 2.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 20        | 2.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 1.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 16        | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 1.31%   |
| Nvidia Audio device                                                                               | 12        | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 1.2%    |
| AMD High Definition Audio Controller                                                              | 11        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.65%   |
| AMD FCH Azalia Controller                                                                         | 6         | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.54%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.44%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.33%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.33%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.33%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.33%   |
| Intel Crystal Well HD Audio Controller                                                            | 3         | 0.33%   |
| BEHRINGER International UMC404HD 192k                                                             | 3         | 0.33%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.33%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.22%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.22%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.22%   |
| Logitech 960 Headset                                                                              | 2         | 0.22%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 2         | 0.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.22%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 203       | 32.07%  |
| SK Hynix            | 148       | 23.38%  |
| Micron Technology   | 69        | 10.9%   |
| Kingston            | 56        | 8.85%   |
| Crucial             | 36        | 5.69%   |
| Unknown             | 28        | 4.42%   |
| Ramaxel Technology  | 13        | 2.05%   |
| Elpida              | 12        | 1.9%    |
| Nanya Technology    | 11        | 1.74%   |
| A-DATA Technology   | 10        | 1.58%   |
| Corsair             | 6         | 0.95%   |
| Patriot             | 4         | 0.63%   |
| Team                | 3         | 0.47%   |
| Avant               | 3         | 0.47%   |
| Apacer              | 3         | 0.47%   |
| Unknown (ABCD)      | 2         | 0.32%   |
| Transcend           | 2         | 0.32%   |
| Silicon Power       | 2         | 0.32%   |
| Neo Forza           | 2         | 0.32%   |
| GOODRAM             | 2         | 0.32%   |
| Goldkey             | 2         | 0.32%   |
| ASint Technology    | 2         | 0.32%   |
| Unknown             | 2         | 0.32%   |
| Unknown (898F)      | 1         | 0.16%   |
| Unknown (0x8634)    | 1         | 0.16%   |
| Unknown (0x8319)    | 1         | 0.16%   |
| Unknown (09D5)      | 1         | 0.16%   |
| Sesame              | 1         | 0.16%   |
| Saikano             | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| G.Skill             | 1         | 0.16%   |
| EUDAR               | 1         | 0.16%   |
| DSL                 | 1         | 0.16%   |
| CSX                 | 1         | 0.16%   |
| 48spaces            | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 2.52%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 15        | 2.23%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 2.08%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 10        | 1.48%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 9         | 1.34%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 1.19%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 8         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 1.19%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 8         | 1.19%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 1.04%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.04%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 1.04%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 6         | 0.89%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.89%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.89%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.89%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 6         | 0.89%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.74%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.74%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 5         | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.74%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.59%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.59%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.59%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 4         | 0.59%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.59%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.59%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s            | 4         | 0.59%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 3         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 3         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.45%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.45%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.45%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.45%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.45%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.45%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 3         | 0.45%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 3         | 0.45%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 0.45%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 0.45%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.45%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 3         | 0.45%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 3         | 0.45%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.3%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.3%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.3%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 2         | 0.3%    |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 276       | 52.87%  |
| DDR3    | 192       | 36.78%  |
| LPDDR3  | 25        | 4.79%   |
| LPDDR4  | 13        | 2.49%   |
| DDR2    | 8         | 1.53%   |
| SDRAM   | 6         | 1.15%   |
| Unknown | 2         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 482       | 91.63%  |
| Row Of Chips | 37        | 7.03%   |
| Chip         | 7         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 231       | 40.81%  |
| 4096  | 206       | 36.4%   |
| 16384 | 64        | 11.31%  |
| 2048  | 49        | 8.66%   |
| 32768 | 11        | 1.94%   |
| 1024  | 4         | 0.71%   |
| 64    | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 152       | 25.98%  |
| 1600    | 144       | 24.62%  |
| 3200    | 76        | 12.99%  |
| 2400    | 63        | 10.77%  |
| 2133    | 34        | 5.81%   |
| 1334    | 29        | 4.96%   |
| 1333    | 18        | 3.08%   |
| 3266    | 15        | 2.56%   |
| 1067    | 11        | 1.88%   |
| 1867    | 10        | 1.71%   |
| Unknown | 7         | 1.2%    |
| 4267    | 5         | 0.85%   |
| 667     | 5         | 0.85%   |
| 4199    | 4         | 0.68%   |
| 975     | 3         | 0.51%   |
| 800     | 3         | 0.51%   |
| 8400    | 1         | 0.17%   |
| 3733    | 1         | 0.17%   |
| 3000    | 1         | 0.17%   |
| 2048    | 1         | 0.17%   |
| 1776    | 1         | 0.17%   |
| 1639    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MIIIW              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini | 1         | 50%     |
| Brother MFC-L3770CDW       | 1         | 50%     |

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
| Chicony Electronics                    | 150       | 27.52%  |
| IMC Networks                           | 69        | 12.66%  |
| Acer                                   | 54        | 9.91%   |
| Realtek Semiconductor                  | 53        | 9.72%   |
| Microdia                               | 43        | 7.89%   |
| Sunplus Innovation Technology          | 29        | 5.32%   |
| Quanta                                 | 24        | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.85%   |
| Apple                                  | 17        | 3.12%   |
| Syntek                                 | 14        | 2.57%   |
| Lite-On Technology                     | 13        | 2.39%   |
| Suyin                                  | 10        | 1.83%   |
| Lenovo                                 | 9         | 1.65%   |
| Silicon Motion                         | 7         | 1.28%   |
| Logitech                               | 7         | 1.28%   |
| Primax Electronics                     | 5         | 0.92%   |
| Samsung Electronics                    | 4         | 0.73%   |
| Luxvisions Innotech Limited            | 3         | 0.55%   |
| Sunplus Technology                     | 2         | 0.37%   |
| Importek                               | 2         | 0.37%   |
| Generalplus Technology                 | 2         | 0.37%   |
| Alcor Micro                            | 2         | 0.37%   |
| Sonix Technology                       | 1         | 0.18%   |
| Ricoh                                  | 1         | 0.18%   |
| Microsoft                              | 1         | 0.18%   |
| Creative Technology                    | 1         | 0.18%   |
| ARC International                      | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 44        | 8.01%   |
| Realtek Integrated_Webcam_HD                                               | 22        | 4.01%   |
| Microdia Integrated_Webcam_HD                                              | 20        | 3.64%   |
| IMC Networks Integrated Camera                                             | 17        | 3.1%    |
| Chicony HD WebCam                                                          | 17        | 3.1%    |
| Acer Integrated Camera                                                     | 17        | 3.1%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 2.55%   |
| Lite-On Integrated Camera                                                  | 10        | 1.82%   |
| Chicony USB2.0 Camera                                                      | 10        | 1.82%   |
| Sunplus Integrated_Webcam_HD                                               | 9         | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 9         | 1.64%   |
| Syntek Integrated Camera                                                   | 8         | 1.46%   |
| Microdia Integrated Webcam                                                 | 8         | 1.46%   |
| Chicony HP Truevision HD                                                   | 8         | 1.46%   |
| Quanta HD WebCam                                                           | 7         | 1.28%   |
| Acer EasyCamera                                                            | 7         | 1.28%   |
| Lenovo Integrated Webcam [R5U877]                                          | 6         | 1.09%   |
| IMC Networks Lenovo EasyCamera                                             | 6         | 1.09%   |
| Acer BisonCam,NB Pro                                                       | 6         | 1.09%   |
| Quanta HD User Facing                                                      | 5         | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 5         | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)                                    | 5         | 0.91%   |
| Chicony EasyCamera                                                         | 5         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 5         | 0.91%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 5         | 0.91%   |
| Apple FaceTime HD Camera                                                   | 5         | 0.91%   |
| Apple Built-in iSight                                                      | 5         | 0.91%   |
| Acer SunplusIT Integrated Camera                                           | 5         | 0.91%   |
| Samsung Galaxy A5 (MTP)                                                    | 4         | 0.73%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 4         | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 4         | 0.73%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 0.73%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.73%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 0.73%   |
| Chicony HP HD Webcam                                                       | 4         | 0.73%   |
| Chicony FJ Camera                                                          | 4         | 0.73%   |
| Acer Lenovo EasyCamera                                                     | 4         | 0.73%   |
| Acer HD Webcam                                                             | 4         | 0.73%   |
| Syntek EasyCamera                                                          | 3         | 0.55%   |
| Sunplus Laptop Integrated Webcam HD                                        | 3         | 0.55%   |
| Sunplus HD WebCam                                                          | 3         | 0.55%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 3         | 0.55%   |
| Realtek Integrated Webcam_HD                                               | 3         | 0.55%   |
| Realtek Integrated Webcam HD                                               | 3         | 0.55%   |
| Realtek Integrated Webcam                                                  | 3         | 0.55%   |
| Realtek HD WebCam                                                          | 3         | 0.55%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 0.55%   |
| Primax HP HD Webcam [Fixed]                                                | 3         | 0.55%   |
| Microdia Dell Integrated HD Webcam                                         | 3         | 0.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 3         | 0.55%   |
| Lenovo Integrated Webcam                                                   | 3         | 0.55%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 0.55%   |
| IMC Networks USB Camera                                                    | 3         | 0.55%   |
| IMC Networks EasyCamera                                                    | 3         | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 0.55%   |
| Chicony USB 2.0 Camera                                                     | 3         | 0.55%   |
| Chicony HP HD Camera                                                       | 3         | 0.55%   |
| Chicony HD User Facing                                                     | 3         | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 49        | 44.95%  |
| Synaptics                  | 19        | 17.43%  |
| Shenzhen Goodix Technology | 17        | 15.6%   |
| Upek                       | 8         | 7.34%   |
| LighTuning Technology      | 6         | 5.5%    |
| Elan Microelectronics      | 5         | 4.59%   |
| AuthenTec                  | 4         | 3.67%   |
| STMicroelectronics         | 1         | 0.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 13.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 7.34%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 7.34%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 7.34%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 7.34%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 6.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.59%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.67%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.83%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.83%   |
| Synaptics WBDI Device                                                      | 2         | 1.83%   |
| Synaptics  WBDI                                                            | 2         | 1.83%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.83%   |
| Validity Sensors VFS491                                                    | 1         | 0.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.92%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.92%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.92%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.92%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.92%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.92%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.92%   |
| AuthenTec AES1600                                                          | 1         | 0.92%   |
| Unknown                                                                    | 1         | 0.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 45.1%   |
| Alcor Micro | 18        | 35.29%  |
| O2 Micro    | 4         | 7.84%   |
| Lenovo      | 4         | 7.84%   |
| Upek        | 2         | 3.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 35.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 11.76%  |
| Broadcom 5880                                                                | 5         | 9.8%    |
| Broadcom 58200                                                               | 5         | 9.8%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.84%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.92%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 373       | 61.86%  |
| 1     | 180       | 29.85%  |
| 2     | 47        | 7.79%   |
| 3     | 3         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 108       | 38.85%  |
| Graphics card         | 61        | 21.94%  |
| Chipcard              | 51        | 18.35%  |
| Net/wireless          | 22        | 7.91%   |
| Multimedia controller | 16        | 5.76%   |
| Camera                | 12        | 4.32%   |
| Network               | 2         | 0.72%   |
| Card reader           | 2         | 0.72%   |
| Storage               | 1         | 0.36%   |
| Net/ethernet          | 1         | 0.36%   |
| Dvb card              | 1         | 0.36%   |
| Bluetooth             | 1         | 0.36%   |

