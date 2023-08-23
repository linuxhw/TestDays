Linux in New Zealand - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

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

Total: 550

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Alienware     | 15                          | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| HP            | Beats 15                    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Acer          | E1-510                      | [2a83ad14c0](https://linux-hardware.org/?probe=2a83ad14c0) | Jul 27, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [823eca937c](https://linux-hardware.org/?probe=823eca937c) | Jul 24, 2023 |
| HP            | Notebook                    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [0e18492205](https://linux-hardware.org/?probe=0e18492205) | Jul 20, 2023 |
| Toshiba       | TECRA Z50-A                 | [d2b1eef8ac](https://linux-hardware.org/?probe=d2b1eef8ac) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Dell          | System XPS L502X            | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| HP            | ProBook 470 G5              | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Toshiba       | Satellite C50D-C            | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| HP            | Laptop 15-bw0xx             | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| ASUSTek       | N750JV                      | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| HP            | EliteBook 840 G5            | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| HP            | EliteBook 830 G5            | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| HP            | EliteBook 850 G5            | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| HP            | EliteBook 830 G5            | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| HP            | Pavilion 15                 | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| HP            | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| Apple         | MacBookPro11,3              | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| Acer          | Aspire E1-521               | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| HP            | EliteBook 840 G6            | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [c7308f11ce](https://linux-hardware.org/?probe=c7308f11ce) | May 06, 2023 |
| Google        | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [69d95c7c30](https://linux-hardware.org/?probe=69d95c7c30) | May 02, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [864b1a4325](https://linux-hardware.org/?probe=864b1a4325) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | Pavilion 15                 | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Lenovo        | N22 80S6                    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| HP            | ProBook 6550b               | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Dell          | Latitude E5570              | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX431FN             | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| HP            | Notebook                    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Valve         | Jupiter                     | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| Acer          | Aspire F5-573G              | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| HP            | EliteBook 840 14 inch G9... | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| ASUSTek       | UX430UNR                    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Unknown       | Unknown                     | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| Acer          | E1-510                      | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| MSI           | Stealth GS77 12UHS          | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| HP            | ProBook 430 G3              | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| Toshiba       | Satellite C660              | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Google        | Swanky                      | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Latitude E7440              | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| Toshiba       | Satellite C660              | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Google        | Snappy                      | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| The Wareho... | E2037                       | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Dell          | Latitude E6430s             | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| Alienware     | x17 R2                      | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Toshiba       | Satellite C660              | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Toshiba       | Satellite C660              | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Dell          | XPS 13 9360                 | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Dell          | Latitude 7480               | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| HP            | Laptop 15-bs0xx             | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| HP            | EliteBook 8460p             | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| Toshiba       | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Dell          | Inspiron 5415               | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Acer          | Aspire A715-42G             | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| HP            | ProBook 450 G2              | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| ASUSTek       | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Google        | Kip                         | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| Dell          | Vostro 14 5410              | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| HP            | Spectre x2 Detachable       | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| HP            | Pavilion tx2500             | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Dell          | Latitude 7285               | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| Acer          | Aspire VN7-593G             | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| HP            | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| MSI           | GE66 Raider 10SF            | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| Acer          | TravelMate 5760             | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |
| HP            | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| Dell          | System XPS L702X            | [e0ff0245fb](https://linux-hardware.org/?probe=e0ff0245fb) | Sep 10, 2021 |
| Toshiba       | Satellite C50D-C            | [af1933f8ad](https://linux-hardware.org/?probe=af1933f8ad) | Sep 09, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [35c6eb0703](https://linux-hardware.org/?probe=35c6eb0703) | Aug 31, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Medion        | P6815                       | [e3e586bafe](https://linux-hardware.org/?probe=e3e586bafe) | Aug 29, 2021 |
| Medion        | P6815                       | [46b6aaf8c5](https://linux-hardware.org/?probe=46b6aaf8c5) | Aug 29, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| HP            | Pavilion dv6                | [c1ad958c3f](https://linux-hardware.org/?probe=c1ad958c3f) | Aug 28, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Sony          | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [efeb81eaea](https://linux-hardware.org/?probe=efeb81eaea) | Aug 21, 2021 |
| Dell          | XPS 15 9500                 | [1216df6214](https://linux-hardware.org/?probe=1216df6214) | Aug 19, 2021 |
| TWG           | E2017                       | [3f335e736c](https://linux-hardware.org/?probe=3f335e736c) | Aug 18, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Toshiba       | Satellite C50D-C            | [dda3acac30](https://linux-hardware.org/?probe=dda3acac30) | Aug 08, 2021 |
| Samsung       | RC410/RC510/RC710           | [4e03a59c3f](https://linux-hardware.org/?probe=4e03a59c3f) | Aug 03, 2021 |
| Samsung       | RC410/RC510/RC710           | [37550654db](https://linux-hardware.org/?probe=37550654db) | Aug 03, 2021 |
| Lenovo        | V15-IIL 82C5                | [20007580cb](https://linux-hardware.org/?probe=20007580cb) | Aug 01, 2021 |
| Lenovo        | V15-IIL 82C5                | [359e3c40ca](https://linux-hardware.org/?probe=359e3c40ca) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [812ba32a31](https://linux-hardware.org/?probe=812ba32a31) | Aug 01, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [cc238ca2aa](https://linux-hardware.org/?probe=cc238ca2aa) | Jul 30, 2021 |
| HP            | Spectre x2 Detachable       | [7b96d53aa9](https://linux-hardware.org/?probe=7b96d53aa9) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [2a54318c46](https://linux-hardware.org/?probe=2a54318c46) | Jul 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| HP            | Laptop 14s-dk0xxx           | [0acaedd30c](https://linux-hardware.org/?probe=0acaedd30c) | Jul 13, 2021 |
| HP            | Laptop 14s-dk0xxx           | [f655e1ca50](https://linux-hardware.org/?probe=f655e1ca50) | Jul 12, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [331968a8d9](https://linux-hardware.org/?probe=331968a8d9) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [59e9a66bff](https://linux-hardware.org/?probe=59e9a66bff) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490 20N2S04200    | [e20b747527](https://linux-hardware.org/?probe=e20b747527) | Jul 03, 2021 |
| Sony          | SVE14A15FGS                 | [adb8d0cc94](https://linux-hardware.org/?probe=adb8d0cc94) | Jun 14, 2021 |
| Acer          | Aspire A715-71G             | [cb59081351](https://linux-hardware.org/?probe=cb59081351) | Jun 14, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [e82b7b36f2](https://linux-hardware.org/?probe=e82b7b36f2) | Jun 12, 2021 |
| ASUSTek       | K52Jc                       | [4b93dc4ee8](https://linux-hardware.org/?probe=4b93dc4ee8) | Jun 07, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| HP            | EliteBook 8560p             | [ea1bd5e314](https://linux-hardware.org/?probe=ea1bd5e314) | May 30, 2021 |
| Sony          | SVE11126CGB                 | [b7ee22588d](https://linux-hardware.org/?probe=b7ee22588d) | May 29, 2021 |
| Toshiba       | Satellite S70t-B            | [33d64c7a69](https://linux-hardware.org/?probe=33d64c7a69) | May 26, 2021 |
| Toshiba       | Satellite S70t-B            | [60c1bab5d9](https://linux-hardware.org/?probe=60c1bab5d9) | May 26, 2021 |
| HP            | Pavilion Notebook           | [37695077ba](https://linux-hardware.org/?probe=37695077ba) | May 21, 2021 |
| HP            | ENVY 15                     | [2a23609955](https://linux-hardware.org/?probe=2a23609955) | May 15, 2021 |
| Acer          | E5-571-551U                 | [152105400d](https://linux-hardware.org/?probe=152105400d) | May 05, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Lenovo        | V110-15IAP 80TG             | [76ac42ca9c](https://linux-hardware.org/?probe=76ac42ca9c) | Apr 30, 2021 |
| MSI           | GS63VR 7RF                  | [4a7125aec0](https://linux-hardware.org/?probe=4a7125aec0) | Apr 18, 2021 |
| MSI           | GS63VR 7RF                  | [76126cd5fd](https://linux-hardware.org/?probe=76126cd5fd) | Apr 18, 2021 |
| Toshiba       | PORTEGE M930                | [aac37423e5](https://linux-hardware.org/?probe=aac37423e5) | Apr 13, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d65bc55ad0](https://linux-hardware.org/?probe=d65bc55ad0) | Apr 11, 2021 |
| Apple         | MacBook7,1                  | [9b4e89202e](https://linux-hardware.org/?probe=9b4e89202e) | Apr 09, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | EliteBook 2560p             | [ecdecf72ec](https://linux-hardware.org/?probe=ecdecf72ec) | Mar 30, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0653cc5343](https://linux-hardware.org/?probe=0653cc5343) | Mar 29, 2021 |
| Metabox       | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| HP            | ProBook 4540s               | [4fe9e650c2](https://linux-hardware.org/?probe=4fe9e650c2) | Mar 13, 2021 |
| HP            | ProBook 4540s               | [d2c0c69a0d](https://linux-hardware.org/?probe=d2c0c69a0d) | Mar 13, 2021 |
| Acer          | Aspire 5750                 | [6aaf201a58](https://linux-hardware.org/?probe=6aaf201a58) | Mar 10, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [b1088bed99](https://linux-hardware.org/?probe=b1088bed99) | Feb 26, 2021 |
| Dell          | XPS 13 9360                 | [7de34c9abe](https://linux-hardware.org/?probe=7de34c9abe) | Feb 26, 2021 |
| HP            | ZBook 14                    | [042b4b4a48](https://linux-hardware.org/?probe=042b4b4a48) | Feb 26, 2021 |
| Dell          | Latitude E6430s             | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| Dell          | Latitude 7285               | [844392cd2c](https://linux-hardware.org/?probe=844392cd2c) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [d20e5c1f85](https://linux-hardware.org/?probe=d20e5c1f85) | Feb 15, 2021 |
| HP            | EliteBook 820 G3            | [e1a72b607e](https://linux-hardware.org/?probe=e1a72b607e) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [a09ca20174](https://linux-hardware.org/?probe=a09ca20174) | Feb 14, 2021 |
| HP            | Notebook                    | [e5bc3a0317](https://linux-hardware.org/?probe=e5bc3a0317) | Feb 12, 2021 |
| MSI           | GE66 Raider 10SF            | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| HP            | 355 G2                      | [ac856a41b8](https://linux-hardware.org/?probe=ac856a41b8) | Feb 03, 2021 |
| Acer          | ES1-512-P8NA                | [c393cb6ad4](https://linux-hardware.org/?probe=c393cb6ad4) | Jan 24, 2021 |
| HP            | ProBook 450 G3              | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [ecc872dc4a](https://linux-hardware.org/?probe=ecc872dc4a) | Jan 16, 2021 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [3c308a7199](https://linux-hardware.org/?probe=3c308a7199) | Jan 15, 2021 |
| Acer          | ConceptD CN315-71P          | [7d1c394d7a](https://linux-hardware.org/?probe=7d1c394d7a) | Dec 26, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| Lenovo        | ThinkPad P52 20M9000KUS     | [ed51fc90e5](https://linux-hardware.org/?probe=ed51fc90e5) | Dec 19, 2020 |
| HP            | ZBook Studio G5             | [af0417cef5](https://linux-hardware.org/?probe=af0417cef5) | Dec 10, 2020 |
| Dell          | Precision 7530              | [c82b4c0f51](https://linux-hardware.org/?probe=c82b4c0f51) | Dec 03, 2020 |
| HP            | Pavilion dv6                | [2c1cf2da53](https://linux-hardware.org/?probe=2c1cf2da53) | Nov 30, 2020 |
| eMachines     | eM350                       | [0ba740f085](https://linux-hardware.org/?probe=0ba740f085) | Nov 28, 2020 |
| Dell          | XPS 15 9560                 | [463c0c961e](https://linux-hardware.org/?probe=463c0c961e) | Nov 15, 2020 |
| Dell          | Latitude D630               | [4b5f3f19ae](https://linux-hardware.org/?probe=4b5f3f19ae) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [3ffb0e062e](https://linux-hardware.org/?probe=3ffb0e062e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [7e7b6fe785](https://linux-hardware.org/?probe=7e7b6fe785) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [0001b76ceb](https://linux-hardware.org/?probe=0001b76ceb) | Nov 10, 2020 |
| Acer          | Aspire ES1-511              | [13485ce10c](https://linux-hardware.org/?probe=13485ce10c) | Nov 08, 2020 |
| Acer          | Aspire ES1-511              | [903c4d5729](https://linux-hardware.org/?probe=903c4d5729) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [c4d3f6f37d](https://linux-hardware.org/?probe=c4d3f6f37d) | Nov 07, 2020 |
| Lenovo        | ThinkPad T460p 20FWA023C... | [841d75822e](https://linux-hardware.org/?probe=841d75822e) | Nov 04, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [41c93bb503](https://linux-hardware.org/?probe=41c93bb503) | Oct 29, 2020 |
| Lenovo        | ThinkPad T510 4349P91       | [7678291690](https://linux-hardware.org/?probe=7678291690) | Oct 28, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [bacac44e9d](https://linux-hardware.org/?probe=bacac44e9d) | Oct 26, 2020 |
| HP            | ProBook 6550b               | [d93b3bfeac](https://linux-hardware.org/?probe=d93b3bfeac) | Oct 22, 2020 |
| Toshiba       | Satellite C660              | [d8ac831c61](https://linux-hardware.org/?probe=d8ac831c61) | Oct 20, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [8720432e33](https://linux-hardware.org/?probe=8720432e33) | Oct 16, 2020 |
| ASUSTek       | X550EP                      | [f13a8d8d9b](https://linux-hardware.org/?probe=f13a8d8d9b) | Oct 15, 2020 |
| Dell          | XPS 13 9360                 | [8cf28e044c](https://linux-hardware.org/?probe=8cf28e044c) | Oct 11, 2020 |
| HP            | Compaq Presario A900        | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| HP            | Laptop 15s-fq1xxx           | [b3ae2a4d2c](https://linux-hardware.org/?probe=b3ae2a4d2c) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | Swift SF314-41              | [26350d0806](https://linux-hardware.org/?probe=26350d0806) | Oct 04, 2020 |
| HP            | Compaq CQ45                 | [ea61076771](https://linux-hardware.org/?probe=ea61076771) | Sep 30, 2020 |
| MSI           | GP75 Leopard 9SD            | [9c152a1117](https://linux-hardware.org/?probe=9c152a1117) | Sep 30, 2020 |
| HP            | Compaq CQ45                 | [f62190e31d](https://linux-hardware.org/?probe=f62190e31d) | Sep 29, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Apple         | MacBook5,1                  | [fb2f9dd279](https://linux-hardware.org/?probe=fb2f9dd279) | Sep 24, 2020 |
| HP            | EliteBook Folio 1040 G1     | [0848bad0d4](https://linux-hardware.org/?probe=0848bad0d4) | Sep 23, 2020 |
| Apple         | MacBook5,1                  | [ad39052e7a](https://linux-hardware.org/?probe=ad39052e7a) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [616e26ca49](https://linux-hardware.org/?probe=616e26ca49) | Sep 20, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| HP            | ProBook 6560b               | [109cd57459](https://linux-hardware.org/?probe=109cd57459) | Sep 12, 2020 |
| Dell          | Latitude E6430s             | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [b673064c0f](https://linux-hardware.org/?probe=b673064c0f) | Sep 08, 2020 |
| Acer          | Aspire 5750                 | [b65a1db938](https://linux-hardware.org/?probe=b65a1db938) | Sep 07, 2020 |
| Toshiba       | Satellite C50-B             | [167e9daeb7](https://linux-hardware.org/?probe=167e9daeb7) | Sep 05, 2020 |
| HP            | Pavilion dv6                | [4c2298d7bb](https://linux-hardware.org/?probe=4c2298d7bb) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| HP            | Laptop 15-db0xxx            | [3949b5f183](https://linux-hardware.org/?probe=3949b5f183) | Sep 04, 2020 |
| Dell          | Inspiron 5567               | [ab299d27a4](https://linux-hardware.org/?probe=ab299d27a4) | Sep 04, 2020 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [9c1bd6b943](https://linux-hardware.org/?probe=9c1bd6b943) | Sep 03, 2020 |
| MSI           | GT80S 6QD                   | [e14f86e038](https://linux-hardware.org/?probe=e14f86e038) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [c9cf3aef22](https://linux-hardware.org/?probe=c9cf3aef22) | Sep 03, 2020 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | [65612b9b8f](https://linux-hardware.org/?probe=65612b9b8f) | Sep 03, 2020 |
| Toshiba       | Satellite C660              | [e7791768a3](https://linux-hardware.org/?probe=e7791768a3) | Sep 02, 2020 |
| Toshiba       | Satellite C50-B             | [186e22ea8c](https://linux-hardware.org/?probe=186e22ea8c) | Sep 01, 2020 |
| Dell          | XPS 15 9570                 | [cb17688de8](https://linux-hardware.org/?probe=cb17688de8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T460p 20FW0044A... | [4d92725c5a](https://linux-hardware.org/?probe=4d92725c5a) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [1707834024](https://linux-hardware.org/?probe=1707834024) | Aug 26, 2020 |
| Lenovo        | ThinkPad T460 20FMS2FR00    | [db76b91e62](https://linux-hardware.org/?probe=db76b91e62) | Aug 21, 2020 |
| HP            | Pavilion dv6                | [65033f4392](https://linux-hardware.org/?probe=65033f4392) | Aug 19, 2020 |
| MSI           | GE66 Raider 10SF            | [3bcf471b04](https://linux-hardware.org/?probe=3bcf471b04) | Aug 15, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| System76      | Lemur Pro                   | [c2619f1014](https://linux-hardware.org/?probe=c2619f1014) | Aug 14, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [fb69c1f324](https://linux-hardware.org/?probe=fb69c1f324) | Aug 10, 2020 |
| Apple         | MacBookPro5,5               | [37d32b3bac](https://linux-hardware.org/?probe=37d32b3bac) | Aug 03, 2020 |
| Apple         | MacBookPro5,5               | [6aee03b649](https://linux-hardware.org/?probe=6aee03b649) | Jul 31, 2020 |
| HP            | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| MSI           | GE66 Raider 10SF            | [3dcde22239](https://linux-hardware.org/?probe=3dcde22239) | Jul 25, 2020 |
| HP            | Laptop 15-dy0xxx            | [cad2dbb88f](https://linux-hardware.org/?probe=cad2dbb88f) | Jul 25, 2020 |
| HP            | ProBook 450 G5              | [a8dfd5a806](https://linux-hardware.org/?probe=a8dfd5a806) | Jul 21, 2020 |
| HP            | Laptop 15-dy0xxx            | [e471bc69b2](https://linux-hardware.org/?probe=e471bc69b2) | Jul 21, 2020 |
| Dell          | Latitude E5570              | [6408e82f4f](https://linux-hardware.org/?probe=6408e82f4f) | Jul 20, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| HP            | EliteBook 8560p             | [e83d7e33f2](https://linux-hardware.org/?probe=e83d7e33f2) | Jun 29, 2020 |
| HP            | EliteBook 840 G6            | [9fccdcc42f](https://linux-hardware.org/?probe=9fccdcc42f) | Jun 25, 2020 |
| HP            | ProBook 650 G1              | [d8e10f56ec](https://linux-hardware.org/?probe=d8e10f56ec) | Jun 24, 2020 |
| MSI           | GE66 Raider 10SF            | [ca5d80f8f9](https://linux-hardware.org/?probe=ca5d80f8f9) | Jun 16, 2020 |
| MSI           | GE66 Raider 10SF            | [220b2a94c8](https://linux-hardware.org/?probe=220b2a94c8) | Jun 10, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| MSI           | GE66 Raider 10SF            | [8c0b76c629](https://linux-hardware.org/?probe=8c0b76c629) | Jun 01, 2020 |
| Acer          | Aspire E1-571               | [25ca966875](https://linux-hardware.org/?probe=25ca966875) | Jun 01, 2020 |
| MSI           | GE66 Raider 10SF            | [1cb7bb7ad9](https://linux-hardware.org/?probe=1cb7bb7ad9) | May 23, 2020 |
| MSI           | GE66 Raider 10SF            | [afec91ff4d](https://linux-hardware.org/?probe=afec91ff4d) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [72f3e05699](https://linux-hardware.org/?probe=72f3e05699) | May 22, 2020 |
| HP            | EliteBook 8560p             | [5439d2f06b](https://linux-hardware.org/?probe=5439d2f06b) | May 22, 2020 |
| Dell          | Latitude E6430s             | [891fd84ed1](https://linux-hardware.org/?probe=891fd84ed1) | May 21, 2020 |
| Dell          | Latitude E6430s             | [b2f67f2744](https://linux-hardware.org/?probe=b2f67f2744) | May 20, 2020 |
| Sony          | VPCEH28FG                   | [f241603946](https://linux-hardware.org/?probe=f241603946) | May 17, 2020 |
| Lenovo        | ThinkPad E590 20NBS0SC00    | [50ca962181](https://linux-hardware.org/?probe=50ca962181) | May 14, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| HP            | EliteBook 8560p             | [605660fceb](https://linux-hardware.org/?probe=605660fceb) | May 11, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [d1258905c6](https://linux-hardware.org/?probe=d1258905c6) | May 10, 2020 |
| Lenovo        | ThinkPad E520 1143CTO       | [51adfc765c](https://linux-hardware.org/?probe=51adfc765c) | May 10, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [8ca322cd11](https://linux-hardware.org/?probe=8ca322cd11) | May 06, 2020 |
| Lenovo        | ThinkPad T520 42406BG       | [e0d0592e34](https://linux-hardware.org/?probe=e0d0592e34) | May 05, 2020 |
| HP            | ProBook 650 G1              | [ed42eb842d](https://linux-hardware.org/?probe=ed42eb842d) | May 04, 2020 |
| HP            | ProBook 650 G1              | [d29d76cb5c](https://linux-hardware.org/?probe=d29d76cb5c) | May 04, 2020 |
| HP            | Presario CQ57               | [df09ee9161](https://linux-hardware.org/?probe=df09ee9161) | Apr 26, 2020 |
| Toshiba       | TECRA Z50-A                 | [ff5b768627](https://linux-hardware.org/?probe=ff5b768627) | Apr 21, 2020 |
| Acer          | Aspire A315-21G             | [7f9e52f0dd](https://linux-hardware.org/?probe=7f9e52f0dd) | Apr 20, 2020 |
| Acer          | Aspire A315-21G             | [4409c8dae5](https://linux-hardware.org/?probe=4409c8dae5) | Apr 20, 2020 |
| HP            | Pavilion g6                 | [15ad84ee0f](https://linux-hardware.org/?probe=15ad84ee0f) | Apr 15, 2020 |
| Dell          | XPS 13 9360                 | [89cce1b8b6](https://linux-hardware.org/?probe=89cce1b8b6) | Apr 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e4ed30a655](https://linux-hardware.org/?probe=e4ed30a655) | Apr 04, 2020 |
| Toshiba       | Satellite L750              | [391a50ded4](https://linux-hardware.org/?probe=391a50ded4) | Apr 03, 2020 |
| ASUSTek       | N56VZ                       | [04666ab26e](https://linux-hardware.org/?probe=04666ab26e) | Apr 01, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0c505fcd69](https://linux-hardware.org/?probe=0c505fcd69) | Mar 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fc12fa3a4d](https://linux-hardware.org/?probe=fc12fa3a4d) | Mar 25, 2020 |
| Dell          | Precision M6800             | [adb3b768f7](https://linux-hardware.org/?probe=adb3b768f7) | Mar 24, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| HP            | EliteBook 840 G6            | [a26150e202](https://linux-hardware.org/?probe=a26150e202) | Mar 07, 2020 |
| HP            | EliteBook 840 G6            | [0d6d26562c](https://linux-hardware.org/?probe=0d6d26562c) | Mar 07, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [f49a66ef1e](https://linux-hardware.org/?probe=f49a66ef1e) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [72784962fe](https://linux-hardware.org/?probe=72784962fe) | Feb 25, 2020 |
| HP            | Pavilion 15                 | [a1e89aa309](https://linux-hardware.org/?probe=a1e89aa309) | Feb 25, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| HP            | EliteBook x360 1040 G6      | [a838427772](https://linux-hardware.org/?probe=a838427772) | Feb 12, 2020 |
| Lenovo        | ThinkPad T520 424229U       | [5f61d3d553](https://linux-hardware.org/?probe=5f61d3d553) | Feb 09, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| HP            | ProBook 650 G1              | [b5d441afe1](https://linux-hardware.org/?probe=b5d441afe1) | Feb 01, 2020 |
| Lenovo        | V110-14IAP 80TF             | [85b3202273](https://linux-hardware.org/?probe=85b3202273) | Jan 30, 2020 |
| Dell          | XPS 13 9360                 | [c770de6326](https://linux-hardware.org/?probe=c770de6326) | Jan 25, 2020 |
| Lenovo        | ThinkPad X131e 33691A4      | [a30712cd7d](https://linux-hardware.org/?probe=a30712cd7d) | Jan 22, 2020 |
| HP            | Notebook                    | [8f2fc8e2ec](https://linux-hardware.org/?probe=8f2fc8e2ec) | Jan 09, 2020 |
| ASUSTek       | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek       | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| HP            | ProBook 650 G1              | [0763c1c109](https://linux-hardware.org/?probe=0763c1c109) | Jan 02, 2020 |
| HP            | ProBook 650 G1              | [023556890d](https://linux-hardware.org/?probe=023556890d) | Jan 02, 2020 |
| Acer          | Aspire F5-573G              | [ead658852a](https://linux-hardware.org/?probe=ead658852a) | Jan 01, 2020 |
| Acer          | Aspire F5-573G              | [e19db7603d](https://linux-hardware.org/?probe=e19db7603d) | Jan 01, 2020 |
| HP            | ProBook 6550b               | [65a8d66fb9](https://linux-hardware.org/?probe=65a8d66fb9) | Dec 31, 2019 |
| HP            | ProBook 650 G1              | [0085227124](https://linux-hardware.org/?probe=0085227124) | Dec 30, 2019 |
| HP            | EliteBook 850 G5            | [65b1eb0ca1](https://linux-hardware.org/?probe=65b1eb0ca1) | Dec 26, 2019 |
| Lenovo        | ThinkPad T420 4180AQ3       | [4da7aff7a2](https://linux-hardware.org/?probe=4da7aff7a2) | Dec 23, 2019 |
| ASUSTek       | UL50Ag                      | [ba1e7f648c](https://linux-hardware.org/?probe=ba1e7f648c) | Dec 19, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| HP            | Pavilion g6                 | [3acb153d5d](https://linux-hardware.org/?probe=3acb153d5d) | Dec 06, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| HP            | Pavilion g6                 | [034500d792](https://linux-hardware.org/?probe=034500d792) | Nov 26, 2019 |
| Dell          | Latitude 7285               | [87a44ef029](https://linux-hardware.org/?probe=87a44ef029) | Nov 22, 2019 |
| Dell          | Latitude 7285               | [34937530ea](https://linux-hardware.org/?probe=34937530ea) | Nov 21, 2019 |
| HP            | Notebook                    | [31d1bef6c1](https://linux-hardware.org/?probe=31d1bef6c1) | Nov 11, 2019 |
| HP            | ProBook 4540s               | [5cc8316a85](https://linux-hardware.org/?probe=5cc8316a85) | Nov 08, 2019 |
| HP            | ProBook 4730s               | [ed03fd8077](https://linux-hardware.org/?probe=ed03fd8077) | Oct 29, 2019 |
| HP            | ProBook 4730s               | [cd284908ca](https://linux-hardware.org/?probe=cd284908ca) | Oct 28, 2019 |
| HP            | Notebook                    | [1bccff3cda](https://linux-hardware.org/?probe=1bccff3cda) | Sep 25, 2019 |
| Toshiba       | PORTEGE M780                | [64824e5a04](https://linux-hardware.org/?probe=64824e5a04) | Sep 21, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [8e78a0ebf5](https://linux-hardware.org/?probe=8e78a0ebf5) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [fd27e8c70f](https://linux-hardware.org/?probe=fd27e8c70f) | Sep 11, 2019 |
| HP            | Notebook                    | [776ffefbc2](https://linux-hardware.org/?probe=776ffefbc2) | Sep 11, 2019 |
| MSI           | GE60 0NC/GE60 0ND           | [f5b3521c55](https://linux-hardware.org/?probe=f5b3521c55) | Sep 11, 2019 |
| HP            | Notebook                    | [cf646ad1f2](https://linux-hardware.org/?probe=cf646ad1f2) | Sep 11, 2019 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [873e28fce7](https://linux-hardware.org/?probe=873e28fce7) | Sep 02, 2019 |
| HP            | Compaq 6910p (GM903PA#AB... | [2724623348](https://linux-hardware.org/?probe=2724623348) | Aug 12, 2019 |
| ASUSTek       | X542UQ                      | [7a4797b166](https://linux-hardware.org/?probe=7a4797b166) | Aug 11, 2019 |
| HP            | ProBook 6570b               | [4f80f9ba3c](https://linux-hardware.org/?probe=4f80f9ba3c) | Aug 04, 2019 |
| Lenovo        | ThinkPad T440p 20AWS1J00... | [31bcd5a103](https://linux-hardware.org/?probe=31bcd5a103) | Jul 31, 2019 |
| HP            | ProBook 450 G3              | [b9e21a89da](https://linux-hardware.org/?probe=b9e21a89da) | Jul 23, 2019 |
| HP            | ProBook 650 G1              | [6d584d5dab](https://linux-hardware.org/?probe=6d584d5dab) | Jul 22, 2019 |
| HP            | ProBook 450 G3              | [10b8987b19](https://linux-hardware.org/?probe=10b8987b19) | Jul 17, 2019 |
| HP            | ProBook 6550b               | [801f83247c](https://linux-hardware.org/?probe=801f83247c) | Jul 06, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Acer          | Aspire 5100                 | [a28f7b2623](https://linux-hardware.org/?probe=a28f7b2623) | Jun 27, 2019 |
| Acer          | Aspire 5100                 | [aa61fb2b9c](https://linux-hardware.org/?probe=aa61fb2b9c) | Jun 11, 2019 |
| YJKC          | vBOOK Plus                  | [80eae9ed5f](https://linux-hardware.org/?probe=80eae9ed5f) | Jun 09, 2019 |
| HP            | Unknown                     | [ef6ea82cf5](https://linux-hardware.org/?probe=ef6ea82cf5) | May 20, 2019 |
| ASUSTek       | K84L                        | [231a7d9bc6](https://linux-hardware.org/?probe=231a7d9bc6) | Apr 18, 2019 |
| HP            | ProBook 6570b               | [42129ed417](https://linux-hardware.org/?probe=42129ed417) | Mar 23, 2019 |
| HP            | ProBook 6570b               | [25a7d4cca8](https://linux-hardware.org/?probe=25a7d4cca8) | Mar 03, 2019 |
| Acer          | Aspire E5-721               | [e6dca4d6fd](https://linux-hardware.org/?probe=e6dca4d6fd) | Feb 28, 2019 |
| HP            | Mini 110-1100               | [1ba5e0d0b2](https://linux-hardware.org/?probe=1ba5e0d0b2) | Feb 23, 2019 |
| HP            | ProBook 6570b               | [82e153050f](https://linux-hardware.org/?probe=82e153050f) | Jan 28, 2019 |
| HP            | ProBook 650 G1              | [2756a314e5](https://linux-hardware.org/?probe=2756a314e5) | Jan 14, 2019 |
| HP            | ProBook 650 G1              | [f81c16faea](https://linux-hardware.org/?probe=f81c16faea) | Jan 14, 2019 |
| Lenovo        | B590 20208                  | [7c06278f98](https://linux-hardware.org/?probe=7c06278f98) | Dec 28, 2018 |
| Lenovo        | B590 20208                  | [d4897cc9d7](https://linux-hardware.org/?probe=d4897cc9d7) | Dec 28, 2018 |
| HP            | Pavilion 15                 | [5407e9ab05](https://linux-hardware.org/?probe=5407e9ab05) | Dec 22, 2018 |
| HP            | Pavilion 15                 | [a47a651328](https://linux-hardware.org/?probe=a47a651328) | Dec 22, 2018 |
| HP            | 14                          | [553085d233](https://linux-hardware.org/?probe=553085d233) | Jul 06, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 37        | 9.34%   |
| Ubuntu 22.04                 | 21        | 5.3%    |
| Pop!_OS 22.04                | 17        | 4.29%   |
| Ubuntu 18.04                 | 15        | 3.79%   |
| Arch Rolling                 | 13        | 3.28%   |
| OpenMandriva 4.3             | 12        | 3.03%   |
| Zorin 16                     | 10        | 2.53%   |
| Zorin 15                     | 10        | 2.53%   |
| Arch                         | 10        | 2.53%   |
| Pop!_OS 20.04                | 8         | 2.02%   |
| OpenMandriva 4.2             | 8         | 2.02%   |
| Debian 11                    | 8         | 2.02%   |
| OpenMandriva 23.01           | 7         | 1.77%   |
| Ubuntu 21.10                 | 6         | 1.52%   |
| Ubuntu 20.10                 | 6         | 1.52%   |
| Linux Mint 21.1              | 6         | 1.52%   |
| Linux Mint 21                | 6         | 1.52%   |
| Linux Mint 20.3              | 6         | 1.52%   |
| Linux Mint 20.2              | 6         | 1.52%   |
| Fedora 31                    | 6         | 1.52%   |
| Debian 10                    | 6         | 1.52%   |
| Pop!_OS 20.10                | 5         | 1.26%   |
| Manjaro                      | 5         | 1.26%   |
| Fedora 35                    | 5         | 1.26%   |
| EndeavourOS Rolling          | 5         | 1.26%   |
| Ubuntu 21.04                 | 4         | 1.01%   |
| Pop!_OS 21.04                | 4         | 1.01%   |
| OpenMandriva 23.03           | 4         | 1.01%   |
| MX 21                        | 4         | 1.01%   |
| Linux Mint 19.2              | 4         | 1.01%   |
| Kubuntu 22.04                | 4         | 1.01%   |
| Kubuntu 20.04                | 4         | 1.01%   |
| Fedora 34                    | 4         | 1.01%   |
| Fedora 33                    | 4         | 1.01%   |
| Ubuntu 19.10                 | 3         | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.76%   |
| Nobara 36                    | 3         | 0.76%   |
| Linux Mint 20                | 3         | 0.76%   |
| Linux Mint 19.3              | 3         | 0.76%   |
| Linux Mint 19.1              | 3         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 93        | 24.73%  |
| Linux Mint       | 37        | 9.84%   |
| Pop!_OS          | 35        | 9.31%   |
| OpenMandriva     | 30        | 7.98%   |
| Fedora           | 29        | 7.71%   |
| Arch             | 23        | 6.12%   |
| Zorin            | 20        | 5.32%   |
| Debian           | 20        | 5.32%   |
| Manjaro          | 11        | 2.93%   |
| Kubuntu          | 10        | 2.66%   |
| EndeavourOS      | 6         | 1.6%    |
| Nobara           | 5         | 1.33%   |
| Endless          | 5         | 1.33%   |
| Elementary       | 5         | 1.33%   |
| MX               | 4         | 1.06%   |
| Gentoo           | 4         | 1.06%   |
| Xubuntu          | 3         | 0.8%    |
| Ubuntu Unity     | 3         | 0.8%    |
| openSUSE         | 3         | 0.8%    |
| LMDE             | 3         | 0.8%    |
| KDE neon         | 3         | 0.8%    |
| Kali             | 3         | 0.8%    |
| Ubuntu MATE      | 2         | 0.53%   |
| SteamOS          | 2         | 0.53%   |
| Solus            | 2         | 0.53%   |
| ROSA             | 2         | 0.53%   |
| Peppermint       | 2         | 0.53%   |
| Lubuntu          | 2         | 0.53%   |
| ArcoLinux        | 2         | 0.53%   |
| Void Linux       | 1         | 0.27%   |
| Sparky           | 1         | 0.27%   |
| Parrot           | 1         | 0.27%   |
| org.kde.Platform | 1         | 0.27%   |
| BlackPanther     | 1         | 0.27%   |
| Archman          | 1         | 0.27%   |
| antiX            | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 2.75%   |
| 5.16.7-desktop-1omv4003  | 10        | 2.29%   |
| 5.15.0-46-generic        | 8         | 1.83%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.83%   |
| 6.1.1-desktop-1omv2290   | 7         | 1.61%   |
| 6.0.12-76060006-generic  | 7         | 1.61%   |
| 5.4.0-48-generic         | 5         | 1.15%   |
| 5.3.0-28-generic         | 5         | 1.15%   |
| 5.3.16-300.fc31.x86_64   | 4         | 0.92%   |
| 5.17.5-76051705-generic  | 4         | 0.92%   |
| 5.15.0-58-generic        | 4         | 0.92%   |
| 5.15.0-56-generic        | 4         | 0.92%   |
| 5.11.0-7620-generic      | 4         | 0.92%   |
| 5.11.0-27-generic        | 4         | 0.92%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.69%   |
| 5.8.0-53-generic         | 3         | 0.69%   |
| 5.4.0-81-generic         | 3         | 0.69%   |
| 5.4.0-7642-generic       | 3         | 0.69%   |
| 5.4.0-74-generic         | 3         | 0.69%   |
| 5.4.0-65-generic         | 3         | 0.69%   |
| 5.4.0-45-generic         | 3         | 0.69%   |
| 5.4.0-26-generic         | 3         | 0.69%   |
| 5.19.0-46-generic        | 3         | 0.69%   |
| 5.15.0-60-generic        | 3         | 0.69%   |
| 5.15.0-57-generic        | 3         | 0.69%   |
| 5.15.0-53-generic        | 3         | 0.69%   |
| 5.13.0-37-generic        | 3         | 0.69%   |
| 5.10.0-18-amd64          | 3         | 0.69%   |
| 5.10.0-16-amd64          | 3         | 0.69%   |
| 5.0.0-37-generic         | 3         | 0.69%   |
| 4.19.0-9-amd64           | 3         | 0.69%   |
| 6.3.1-1-default          | 2         | 0.46%   |
| 6.2.6-76060206-generic   | 2         | 0.46%   |
| 6.2.0-20-generic         | 2         | 0.46%   |
| 6.1.1-arch1-1            | 2         | 0.46%   |
| 5.8.11-1-MANJARO         | 2         | 0.46%   |
| 5.8.0-7630-generic       | 2         | 0.46%   |
| 5.8.0-48-generic         | 2         | 0.46%   |
| 5.8.0-43-generic         | 2         | 0.46%   |
| 5.4.0-91-generic         | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 59        | 14.25%  |
| 5.15.0  | 39        | 9.42%   |
| 5.13.0  | 22        | 5.31%   |
| 5.11.0  | 17        | 4.11%   |
| 5.3.0   | 16        | 3.86%   |
| 5.8.0   | 15        | 3.62%   |
| 4.15.0  | 14        | 3.38%   |
| 5.10.0  | 13        | 3.14%   |
| 5.0.0   | 12        | 2.9%    |
| 5.19.0  | 10        | 2.42%   |
| 5.16.7  | 10        | 2.42%   |
| 6.1.1   | 9         | 2.17%   |
| 5.10.14 | 9         | 2.17%   |
| 6.0.12  | 7         | 1.69%   |
| 4.19.0  | 7         | 1.69%   |
| 4.18.0  | 6         | 1.45%   |
| 6.2.6   | 5         | 1.21%   |
| 6.1.0   | 4         | 0.97%   |
| 5.3.16  | 4         | 0.97%   |
| 5.17.5  | 4         | 0.97%   |
| 6.2.12  | 3         | 0.72%   |
| 5.15.4  | 3         | 0.72%   |
| 6.3.1   | 2         | 0.48%   |
| 6.2.8   | 2         | 0.48%   |
| 6.2.0   | 2         | 0.48%   |
| 6.0.10  | 2         | 0.48%   |
| 6.0.0   | 2         | 0.48%   |
| 5.8.11  | 2         | 0.48%   |
| 5.7.0   | 2         | 0.48%   |
| 5.6.8   | 2         | 0.48%   |
| 5.6.19  | 2         | 0.48%   |
| 5.3.8   | 2         | 0.48%   |
| 5.19.7  | 2         | 0.48%   |
| 5.18.6  | 2         | 0.48%   |
| 5.18.10 | 2         | 0.48%   |
| 5.18.0  | 2         | 0.48%   |
| 5.17.15 | 2         | 0.48%   |
| 5.16.13 | 2         | 0.48%   |
| 5.16.11 | 2         | 0.48%   |
| 5.15.15 | 2         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 64        | 15.76%  |
| 5.15    | 51        | 12.56%  |
| 5.10    | 28        | 6.9%    |
| 5.13    | 25        | 6.16%   |
| 5.11    | 22        | 5.42%   |
| 5.8     | 21        | 5.17%   |
| 5.3     | 21        | 5.17%   |
| 5.16    | 19        | 4.68%   |
| 6.1     | 17        | 4.19%   |
| 6.0     | 15        | 3.69%   |
| 4.15    | 14        | 3.45%   |
| 6.2     | 13        | 3.2%    |
| 5.19    | 13        | 3.2%    |
| 5.0     | 12        | 2.96%   |
| 5.18    | 9         | 2.22%   |
| 5.17    | 8         | 1.97%   |
| 6.3     | 7         | 1.72%   |
| 4.19    | 7         | 1.72%   |
| 4.18    | 7         | 1.72%   |
| 5.6     | 6         | 1.48%   |
| 5.14    | 6         | 1.48%   |
| 5.7     | 5         | 1.23%   |
| 5.9     | 4         | 0.99%   |
| 4.9     | 3         | 0.74%   |
| 6.4     | 2         | 0.49%   |
| 5.5     | 2         | 0.49%   |
| 4.20    | 2         | 0.49%   |
| 5.2     | 1         | 0.25%   |
| 4.13    | 1         | 0.25%   |
| 4.11    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 347       | 97.47%  |
| i686   | 9         | 2.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 176       | 47.06%  |
| KDE5             | 58        | 15.51%  |
| Unknown          | 34        | 9.09%   |
| X-Cinnamon       | 27        | 7.22%   |
| XFCE             | 25        | 6.68%   |
| MATE             | 11        | 2.94%   |
| KDE              | 10        | 2.67%   |
| Pantheon         | 5         | 1.34%   |
| i3               | 5         | 1.34%   |
| Cinnamon         | 4         | 1.07%   |
| Unity            | 3         | 0.8%    |
| LXDE             | 3         | 0.8%    |
| Hyprland         | 3         | 0.8%    |
| LXQt             | 2         | 0.53%   |
| Budgie           | 2         | 0.53%   |
| lightdm-xsession | 1         | 0.27%   |
| KDE4             | 1         | 0.27%   |
| icewm            | 1         | 0.27%   |
| i3-with-shmlog   | 1         | 0.27%   |
| fluxbox          | 1         | 0.27%   |
| Deepin           | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 275       | 74.53%  |
| Wayland | 75        | 20.33%  |
| Unknown | 16        | 4.34%   |
| Tty     | 3         | 0.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 190       | 50.4%   |
| SDDM    | 53        | 14.06%  |
| GDM     | 42        | 11.14%  |
| GDM3    | 38        | 10.08%  |
| LightDM | 37        | 9.81%   |
| TDM     | 11        | 2.92%   |
| Ly      | 2         | 0.53%   |
| LXDM    | 2         | 0.53%   |
| XDM     | 1         | 0.27%   |
| KDM     | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_NZ   | 226       | 60.59%  |
| en_US   | 75        | 20.11%  |
| Unknown | 29        | 7.77%   |
| en_GB   | 18        | 4.83%   |
| C       | 12        | 3.22%   |
| en_AU   | 7         | 1.88%   |
| zh_CN   | 2         | 0.54%   |
| mi_NZ   | 2         | 0.54%   |
| pt_BR   | 1         | 0.27%   |
| de_DE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 195       | 53.87%  |
| BIOS | 167       | 46.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 280       | 75.27%  |
| Btrfs   | 35        | 9.41%   |
| Overlay | 32        | 8.6%    |
| Unknown | 14        | 3.76%   |
| Tmpfs   | 3         | 0.81%   |
| Ext2    | 3         | 0.81%   |
| Zfs     | 2         | 0.54%   |
| Xfs     | 2         | 0.54%   |
| Ext3    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 193       | 52.45%  |
| GPT     | 133       | 36.14%  |
| MBR     | 42        | 11.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 320       | 87.43%  |
| Yes       | 46        | 12.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 278       | 76.37%  |
| Yes       | 86        | 23.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 112       | 31.46%  |
| Lenovo              | 54        | 15.17%  |
| Dell                | 49        | 13.76%  |
| ASUSTek Computer    | 36        | 10.11%  |
| Acer                | 30        | 8.43%   |
| Toshiba             | 19        | 5.34%   |
| MSI                 | 10        | 2.81%   |
| Apple               | 10        | 2.81%   |
| Sony                | 6         | 1.69%   |
| Google              | 6         | 1.69%   |
| Samsung Electronics | 4         | 1.12%   |
| Valve               | 2         | 0.56%   |
| System76            | 2         | 0.56%   |
| HUAWEI              | 2         | 0.56%   |
| Alienware           | 2         | 0.56%   |
| YJKC                | 1         | 0.28%   |
| TWG                 | 1         | 0.28%   |
| Timi                | 1         | 0.28%   |
| The Warehouse Group | 1         | 0.28%   |
| Star Labs           | 1         | 0.28%   |
| Metabox             | 1         | 0.28%   |
| Medion              | 1         | 0.28%   |
| Kogan               | 1         | 0.28%   |
| IBM                 | 1         | 0.28%   |
| Gigabyte Technology | 1         | 0.28%   |
| eMachines           | 1         | 0.28%   |
| Unknown             | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP Notebook                               | 5         | 1.4%    |
| Dell XPS 13 9360                          | 5         | 1.4%    |
| HP ProBook 6550b                          | 4         | 1.12%   |
| HP Pavilion dv6                           | 4         | 1.12%   |
| HP Pavilion 15                            | 4         | 1.12%   |
| HP ProBook 4540s                          | 3         | 0.84%   |
| HP EliteBook 8560p                        | 3         | 0.84%   |
| ASUS ASUS EXPERTBOOK P2451FA_P2451FA      | 3         | 0.84%   |
| Acer Aspire F5-573G                       | 3         | 0.84%   |
| Valve Jupiter                             | 2         | 0.56%   |
| Toshiba TECRA Z50-A                       | 2         | 0.56%   |
| Toshiba Satellite L750                    | 2         | 0.56%   |
| MSI GE66 Raider 10SF                      | 2         | 0.56%   |
| Lenovo ThinkPad T460 20FMS2FR00           | 2         | 0.56%   |
| Lenovo ThinkPad T420 4180AQ3              | 2         | 0.56%   |
| HUAWEI BOHK-WAX9X                         | 2         | 0.56%   |
| HP ZBook Firefly 15 G7 Mobile Workstation | 2         | 0.56%   |
| HP ProBook 6570b                          | 2         | 0.56%   |
| HP ProBook 470 G5                         | 2         | 0.56%   |
| HP ProBook 450 G5                         | 2         | 0.56%   |
| HP ProBook 450 G3                         | 2         | 0.56%   |
| HP EliteBook 8570p                        | 2         | 0.56%   |
| HP EliteBook 850 G5                       | 2         | 0.56%   |
| HP EliteBook 840 G6                       | 2         | 0.56%   |
| HP EliteBook 840 G5                       | 2         | 0.56%   |
| HP EliteBook 830 G5                       | 2         | 0.56%   |
| Dell XPS 15 9500                          | 2         | 0.56%   |
| Dell System XPS L702X                     | 2         | 0.56%   |
| Dell Latitude E7440                       | 2         | 0.56%   |
| Dell Latitude E6430s                      | 2         | 0.56%   |
| Dell Latitude E5570                       | 2         | 0.56%   |
| Dell Latitude E4300                       | 2         | 0.56%   |
| Dell Latitude 7490                        | 2         | 0.56%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR     | 2         | 0.56%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 0.56%   |
| ASUS K52Jc                                | 2         | 0.56%   |
| ASUS ASUS TUF Dash F15 FX516PM_FX516PM    | 2         | 0.56%   |
| Apple MacBookAir7,2                       | 2         | 0.56%   |
| Acer Swift SF314-41                       | 2         | 0.56%   |
| Unknown                                   | 2         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 37        | 10.39%  |
| HP EliteBook      | 28        | 7.87%   |
| HP ProBook        | 25        | 7.02%   |
| HP Pavilion       | 20        | 5.62%   |
| Acer Aspire       | 19        | 5.34%   |
| Dell Latitude     | 18        | 5.06%   |
| Toshiba Satellite | 13        | 3.65%   |
| Dell XPS          | 11        | 3.09%   |
| HP ZBook          | 8         | 2.25%   |
| HP Laptop         | 7         | 1.97%   |
| Dell Inspiron     | 7         | 1.97%   |
| ASUS ROG          | 6         | 1.69%   |
| ASUS ASUS         | 6         | 1.69%   |
| HP Notebook       | 5         | 1.4%    |
| Dell Precision    | 5         | 1.4%    |
| Toshiba PORTEGE   | 4         | 1.12%   |
| Acer TravelMate   | 4         | 1.12%   |
| Lenovo IdeaPad    | 3         | 0.84%   |
| HP Compaq         | 3         | 0.84%   |
| Dell System       | 3         | 0.84%   |
| ASUS VivoBook     | 3         | 0.84%   |
| Apple MacBookPro5 | 3         | 0.84%   |
| Valve Jupiter     | 2         | 0.56%   |
| Toshiba TECRA     | 2         | 0.56%   |
| MSI GE66          | 2         | 0.56%   |
| Lenovo Yoga       | 2         | 0.56%   |
| HUAWEI BOHK-WAX9X | 2         | 0.56%   |
| HP Presario       | 2         | 0.56%   |
| HP OMEN           | 2         | 0.56%   |
| HP ENVY           | 2         | 0.56%   |
| Dell Vostro       | 2         | 0.56%   |
| ASUS ZenBook      | 2         | 0.56%   |
| ASUS K52Jc        | 2         | 0.56%   |
| Apple MacBookAir7 | 2         | 0.56%   |
| Apple MacBook5    | 2         | 0.56%   |
| Acer Swift        | 2         | 0.56%   |
| Unknown           | 2         | 0.56%   |
| YJKC vBOOK        | 1         | 0.28%   |
| TWG E2017         | 1         | 0.28%   |
| Timi A30          | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 39        | 10.96%  |
| 2011 | 36        | 10.11%  |
| 2018 | 31        | 8.71%   |
| 2020 | 29        | 8.15%   |
| 2019 | 28        | 7.87%   |
| 2021 | 26        | 7.3%    |
| 2017 | 22        | 6.18%   |
| 2016 | 22        | 6.18%   |
| 2013 | 22        | 6.18%   |
| 2022 | 20        | 5.62%   |
| 2015 | 18        | 5.06%   |
| 2014 | 18        | 5.06%   |
| 2008 | 16        | 4.49%   |
| 2010 | 14        | 3.93%   |
| 2009 | 9         | 2.53%   |
| 2007 | 2         | 0.56%   |
| 2006 | 2         | 0.56%   |
| 2023 | 1         | 0.28%   |
| 2005 | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 356       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 316       | 88.27%  |
| Enabled  | 42        | 11.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 348       | 97.75%  |
| Yes  | 8         | 2.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 104       | 28.49%  |
| 16.01-24.0  | 71        | 19.45%  |
| 3.01-4.0    | 64        | 17.53%  |
| 8.01-16.0   | 63        | 17.26%  |
| 32.01-64.0  | 34        | 9.32%   |
| 1.01-2.0    | 9         | 2.47%   |
| 64.01-256.0 | 8         | 2.19%   |
| 24.01-32.0  | 5         | 1.37%   |
| 2.01-3.0    | 4         | 1.1%    |
| 0.51-1.0    | 3         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 131       | 33%     |
| 2.01-3.0   | 106       | 26.7%   |
| 3.01-4.0   | 61        | 15.37%  |
| 4.01-8.0   | 56        | 14.11%  |
| 0.51-1.0   | 22        | 5.54%   |
| 8.01-16.0  | 12        | 3.02%   |
| 16.01-24.0 | 5         | 1.26%   |
| 24.01-32.0 | 2         | 0.5%    |
| 0.01-0.5   | 2         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 278       | 75.54%  |
| 2      | 74        | 20.11%  |
| 3      | 14        | 3.8%    |
| 0      | 2         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 214       | 59.78%  |
| Yes       | 144       | 40.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 81.89%  |
| No        | 65        | 18.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 353       | 99.16%  |
| No        | 3         | 0.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 80.49%  |
| No        | 71        | 19.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| New Zealand | 356       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Auckland         | 174       | 46.9%   |
| Wellington       | 40        | 10.78%  |
| Christchurch     | 37        | 9.97%   |
| Hamilton         | 24        | 6.47%   |
| Tauranga         | 13        | 3.5%    |
| Dunedin          | 10        | 2.7%    |
| Whangarei        | 8         | 2.16%   |
| Cambridge        | 7         | 1.89%   |
| New Plymouth     | 6         | 1.62%   |
| Lower Hutt       | 6         | 1.62%   |
| Palmerston North | 5         | 1.35%   |
| Nelson           | 5         | 1.35%   |
| Napier City      | 5         | 1.35%   |
| Invercargill     | 5         | 1.35%   |
| Hastings         | 4         | 1.08%   |
| Whanganui        | 3         | 0.81%   |
| Otaki            | 2         | 0.54%   |
| Levin            | 2         | 0.54%   |
| Grafton          | 2         | 0.54%   |
| Whatawhata       | 1         | 0.27%   |
| Tutukaka         | 1         | 0.27%   |
| Saint Andrews    | 1         | 0.27%   |
| Rotorua          | 1         | 0.27%   |
| Paraparaumu      | 1         | 0.27%   |
| Pakuranga        | 1         | 0.27%   |
| Masterton        | 1         | 0.27%   |
| Kerikeri         | 1         | 0.27%   |
| Katikati         | 1         | 0.27%   |
| Gordonton        | 1         | 0.27%   |
| Edgecumbe        | 1         | 0.27%   |
| Bulls            | 1         | 0.27%   |
| Ashburton        | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 87        | 117    | 20.14%  |
| Seagate                     | 52        | 57     | 12.04%  |
| WDC                         | 45        | 66     | 10.42%  |
| Toshiba                     | 40        | 48     | 9.26%   |
| Crucial                     | 25        | 43     | 5.79%   |
| SanDisk                     | 22        | 24     | 5.09%   |
| Unknown                     | 21        | 30     | 4.86%   |
| SK hynix                    | 19        | 21     | 4.4%    |
| Intel                       | 17        | 21     | 3.94%   |
| Kingston                    | 12        | 15     | 2.78%   |
| Hitachi                     | 12        | 14     | 2.78%   |
| HGST                        | 12        | 12     | 2.78%   |
| Micron Technology           | 10        | 14     | 2.31%   |
| LITEON                      | 4         | 4      | 0.93%   |
| KingSpec                    | 4         | 4      | 0.93%   |
| China                       | 4         | 4      | 0.93%   |
| Apple                       | 4         | 5      | 0.93%   |
| A-DATA Technology           | 4         | 4      | 0.93%   |
| Team                        | 3         | 3      | 0.69%   |
| ASMT                        | 3         | 3      | 0.69%   |
| Transcend                   | 2         | 2      | 0.46%   |
| TO Exter                    | 2         | 2      | 0.46%   |
| Silicon Motion              | 2         | 3      | 0.46%   |
| ROG                         | 2         | 2      | 0.46%   |
| O2 Micro                    | 2         | 2      | 0.46%   |
| Micron/Crucial Technology   | 2         | 2      | 0.46%   |
| KIOXIA                      | 2         | 3      | 0.46%   |
| JMicron Technology          | 2         | 2      | 0.46%   |
| Hewlett-Packard             | 2         | 4      | 0.46%   |
| XPG                         | 1         | 1      | 0.23%   |
| Star Drive                  | 1         | 1      | 0.23%   |
| ShiJi                       | 1         | 1      | 0.23%   |
| Phison Electronics          | 1         | 2      | 0.23%   |
| Phison                      | 1         | 1      | 0.23%   |
| OCZ                         | 1         | 1      | 0.23%   |
| Netac                       | 1         | 1      | 0.23%   |
| LITEONIT                    | 1         | 3      | 0.23%   |
| Kingston Technology Company | 1         | 1      | 0.23%   |
| KINGBANK                    | 1         | 1      | 0.23%   |
| HGST HTS                    | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB       | 7         | 1.55%   |
| Intel NVMe SSD Drive 512GB            | 7         | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 1.33%   |
| Samsung SSD 860 EVO 500GB             | 6         | 1.33%   |
| Samsung NVMe SSD Drive 512GB          | 6         | 1.33%   |
| Seagate Expansion 1TB                 | 5         | 1.11%   |
| Samsung SSD 850 EVO 500GB             | 5         | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 4         | 0.88%   |
| WDC WD10JPVX-60JC3T0 1TB              | 4         | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB              | 4         | 0.88%   |
| Toshiba MQ01ABF050 500GB              | 4         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 0.88%   |
| SanDisk NVMe SSD Drive 512GB          | 4         | 0.88%   |
| Samsung NVMe SSD Drive 256GB          | 4         | 0.88%   |
| Crucial CT500MX500SSD1 500GB          | 4         | 0.88%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 3         | 0.66%   |
| Unknown MMC Card  64GB                | 3         | 0.66%   |
| Unknown MMC Card  32GB                | 3         | 0.66%   |
| Unknown MMC Card  2GB                 | 3         | 0.66%   |
| Toshiba XG6 NVMe SSD Controller 512GB | 3         | 0.66%   |
| Toshiba NVMe SSD Drive 512GB          | 3         | 0.66%   |
| Seagate ST9500420AS 500GB             | 3         | 0.66%   |
| Samsung SSD 980 1TB                   | 3         | 0.66%   |
| Samsung SSD 870 EVO 1TB               | 3         | 0.66%   |
| Samsung SSD 850 EVO 1TB               | 3         | 0.66%   |
| Samsung MZVL21T0HCLR-00B00 1TB        | 3         | 0.66%   |
| Kingston SV300S37A240G 240GB SSD      | 3         | 0.66%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 0.66%   |
| Intel SSDPEKNU512GZ 512GB             | 3         | 0.66%   |
| HGST HTS721010A9E630 1TB              | 3         | 0.66%   |
| Crucial CT240BX200SSD1 240GB          | 3         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB           | 3         | 0.66%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 2         | 0.44%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 2         | 0.44%   |
| WDC WD10SPZX-22Z10T1 1TB              | 2         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB              | 2         | 0.44%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB  | 2         | 0.44%   |
| Unknown MMC Card  128GB               | 2         | 0.44%   |
| Toshiba MQ01ACF050 500GB              | 2         | 0.44%   |
| Toshiba MQ01ABD100 1TB                | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 54     | 36.03%  |
| WDC                 | 34        | 45     | 25%     |
| Toshiba             | 20        | 25     | 14.71%  |
| Hitachi             | 12        | 14     | 8.82%   |
| HGST                | 12        | 12     | 8.82%   |
| Samsung Electronics | 2         | 2      | 1.47%   |
| JMicron Technology  | 2         | 2      | 1.47%   |
| Unknown             | 1         | 3      | 0.74%   |
| HGST HTS            | 1         | 1      | 0.74%   |
| Fujitsu             | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 47     | 26.32%  |
| Crucial             | 21        | 39     | 15.79%  |
| SanDisk             | 13        | 13     | 9.77%   |
| Kingston            | 9         | 12     | 6.77%   |
| Micron Technology   | 7         | 10     | 5.26%   |
| WDC                 | 4         | 11     | 3.01%   |
| KingSpec            | 4         | 4      | 3.01%   |
| Intel               | 4         | 7      | 3.01%   |
| China               | 4         | 4      | 3.01%   |
| A-DATA Technology   | 4         | 4      | 3.01%   |
| Toshiba             | 3         | 4      | 2.26%   |
| Team                | 3         | 3      | 2.26%   |
| SK hynix            | 3         | 3      | 2.26%   |
| LITEON              | 3         | 3      | 2.26%   |
| Apple               | 3         | 4      | 2.26%   |
| Transcend           | 2         | 2      | 1.5%    |
| TO Exter            | 2         | 2      | 1.5%    |
| Seagate             | 2         | 2      | 1.5%    |
| OCZ                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 3      | 0.75%   |
| Hewlett-Packard     | 1         | 3      | 0.75%   |
| Dell                | 1         | 1      | 0.75%   |
| ASMT                | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 130       | 169    | 31.71%  |
| HDD     | 129       | 161    | 31.46%  |
| SSD     | 125       | 185    | 30.49%  |
| MMC     | 21        | 28     | 5.12%   |
| Unknown | 5         | 5      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 229       | 327    | 57.25%  |
| NVMe | 130       | 168    | 32.5%   |
| MMC  | 21        | 28     | 5.25%   |
| SAS  | 20        | 25     | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 164       | 230    | 63.81%  |
| 0.51-1.0   | 83        | 106    | 32.3%   |
| 1.01-2.0   | 8         | 8      | 3.11%   |
| 3.01-4.0   | 1         | 1      | 0.39%   |
| 4.01-10.0  | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 103       | 27.61%  |
| 101-250        | 95        | 25.47%  |
| 501-1000       | 57        | 15.28%  |
| 1-20           | 33        | 8.85%   |
| 1001-2000      | 25        | 6.7%    |
| 51-100         | 23        | 6.17%   |
| More than 3000 | 11        | 2.95%   |
| 21-50          | 11        | 2.95%   |
| Unknown        | 8         | 2.14%   |
| 2001-3000      | 7         | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 155       | 39.54%  |
| 21-50          | 77        | 19.64%  |
| 101-250        | 49        | 12.5%   |
| 51-100         | 43        | 10.97%  |
| 251-500        | 26        | 6.63%   |
| 501-1000       | 26        | 6.63%   |
| Unknown        | 8         | 2.04%   |
| 1001-2000      | 4         | 1.02%   |
| More than 3000 | 2         | 0.51%   |
| 2001-3000      | 2         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 6.25%   |
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 3.13%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.13%   |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 3.13%   |
| Toshiba MK3256GSY 320GB                             | 1         | 1      | 3.13%   |
| SK hynix SC308 SATA 128GB SSD                       | 1         | 1      | 3.13%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 2      | 3.13%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB             | 1         | 1      | 3.13%   |
| ShiJi 512GB M.2-NVMe                                | 1         | 1      | 3.13%   |
| Seagate ST9500420ASG 500GB                          | 1         | 1      | 3.13%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 3.13%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.13%   |
| Intel SSDSCKKW240H6 240GB                           | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9SA00 320GB                       | 1         | 1      | 3.13%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.13%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 3.13%   |
| HGST HTS 541075A9E680 752GB                         | 1         | 1      | 3.13%   |
| HGST HCC545050A7E380 500GB                          | 1         | 1      | 3.13%   |
| Crucial CT275MX300SSD1 275GB                        | 1         | 1      | 3.13%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 3.13%   |
| ASMT ASM105x 500GB                                  | 1         | 1      | 3.13%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 16.13%  |
| HGST                | 5         | 5      | 16.13%  |
| Toshiba             | 4         | 4      | 12.9%   |
| WDC                 | 2         | 2      | 6.45%   |
| SK hynix            | 2         | 4      | 6.45%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Micron Technology   | 2         | 2      | 6.45%   |
| Hitachi             | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| ShiJi               | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| HGST HTS            | 1         | 1      | 3.23%   |
| ASMT                | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 25%     |
| HGST     | 5         | 5      | 25%     |
| Toshiba  | 4         | 4      | 20%     |
| WDC      | 2         | 2      | 10%     |
| Hitachi  | 2         | 2      | 10%     |
| HGST HTS | 1         | 1      | 5%      |
| Apple    | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 64.52%  |
| SSD  | 8         | 8      | 25.81%  |
| NVMe | 3         | 5      | 9.68%   |

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
| Detected | 216       | 340    | 56.54%  |
| Works    | 136       | 175    | 35.6%   |
| Malfunc  | 30        | 33     | 7.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 240       | 58.25%  |
| Samsung Electronics          | 55        | 13.35%  |
| AMD                          | 38        | 9.22%   |
| Toshiba America Info Systems | 18        | 4.37%   |
| SK hynix                     | 16        | 3.88%   |
| SanDisk                      | 15        | 3.64%   |
| Nvidia                       | 6         | 1.46%   |
| Micron/Crucial Technology    | 6         | 1.46%   |
| Kingston Technology Company  | 4         | 0.97%   |
| Phison Electronics           | 3         | 0.73%   |
| Micron Technology            | 3         | 0.73%   |
| Silicon Motion               | 2         | 0.49%   |
| O2 Micro                     | 2         | 0.49%   |
| KIOXIA                       | 2         | 0.49%   |
| Lite-On Technology           | 1         | 0.24%   |
| ADATA Technology             | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 35        | 8.03%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 29        | 6.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 6.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 5.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 2.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 2.75%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 2.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 2.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 2.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 2.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 6         | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.38%   |
| Intel SSD 660P Series                                                          | 6         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 4         | 0.92%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.69%   |
| SK hynix BC511 NVMe SSD                                                        | 3         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.69%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 3         | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.69%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 0.46%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.46%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 2         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 247       | 58.95%  |
| NVMe | 131       | 31.26%  |
| RAID | 26        | 6.21%   |
| IDE  | 15        | 3.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 297       | 83.43%  |
| AMD    | 59        | 16.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.4%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.4%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.4%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 1.4%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.12%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.12%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 1.12%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.84%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.84%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.84%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 3         | 0.84%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.84%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.84%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 0.84%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.84%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.84%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.56%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 104       | 29.21%  |
| Intel Core i7                  | 95        | 26.69%  |
| Other                          | 29        | 8.15%   |
| Intel Core 2 Duo               | 22        | 6.18%   |
| Intel Celeron                  | 20        | 5.62%   |
| Intel Core i3                  | 16        | 4.49%   |
| AMD A6                         | 9         | 2.53%   |
| AMD Ryzen 7                    | 8         | 2.25%   |
| AMD Ryzen 5                    | 8         | 2.25%   |
| AMD Ryzen 9                    | 5         | 1.4%    |
| AMD E2                         | 5         | 1.4%    |
| AMD A8                         | 4         | 1.12%   |
| Intel Pentium                  | 3         | 0.84%   |
| Intel Core i9                  | 3         | 0.84%   |
| Intel Atom                     | 3         | 0.84%   |
| AMD Ryzen 5 PRO                | 3         | 0.84%   |
| Intel Pentium M                | 2         | 0.56%   |
| AMD Ryzen 3                    | 2         | 0.56%   |
| AMD E1                         | 2         | 0.56%   |
| AMD E                          | 2         | 0.56%   |
| AMD A4                         | 2         | 0.56%   |
| Intel Xeon                     | 1         | 0.28%   |
| Intel Pentium Silver           | 1         | 0.28%   |
| Intel Genuine                  | 1         | 0.28%   |
| Intel Core m7                  | 1         | 0.28%   |
| Intel Celeron Dual-Core        | 1         | 0.28%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.28%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.28%   |
| AMD Ryzen 7 PRO                | 1         | 0.28%   |
| AMD A10                        | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 181       | 50.7%   |
| 4      | 112       | 31.37%  |
| 6      | 24        | 6.72%   |
| 8      | 21        | 5.88%   |
| 1      | 7         | 1.96%   |
| 14     | 6         | 1.68%   |
| 10     | 6         | 1.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 356       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 272       | 76.19%  |
| 1      | 84        | 23.53%  |
| 8      | 1         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 348       | 96.4%   |
| Unknown        | 10        | 2.77%   |
| 32-bit         | 3         | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 26.63%  |
| 0x206a7    | 31        | 8.42%   |
| 0x306a9    | 25        | 6.79%   |
| 0x806ea    | 16        | 4.35%   |
| 0x806ec    | 13        | 3.53%   |
| 0x406e3    | 11        | 2.99%   |
| 0x1067a    | 10        | 2.72%   |
| 0x806e9    | 9         | 2.45%   |
| 0x20655    | 9         | 2.45%   |
| 0x30678    | 8         | 2.17%   |
| 0xa0652    | 7         | 1.9%    |
| 0x40651    | 7         | 1.9%    |
| 0x306c3    | 7         | 1.9%    |
| 0x10676    | 7         | 1.9%    |
| 0x306d4    | 6         | 1.63%   |
| 0x07030105 | 6         | 1.63%   |
| 0x906e9    | 5         | 1.36%   |
| 0x906a4    | 5         | 1.36%   |
| 0x906ea    | 4         | 1.09%   |
| 0x906a3    | 4         | 1.09%   |
| 0x806c1    | 4         | 1.09%   |
| 0x506e3    | 4         | 1.09%   |
| 0x506c9    | 4         | 1.09%   |
| 0x0a50000d | 4         | 1.09%   |
| 0x0a50000c | 4         | 1.09%   |
| 0x08108109 | 4         | 1.09%   |
| 0x06006705 | 4         | 1.09%   |
| 0x806d1    | 3         | 0.82%   |
| 0x706a8    | 3         | 0.82%   |
| 0x6fd      | 3         | 0.82%   |
| 0x08600106 | 3         | 0.82%   |
| 0x08108102 | 3         | 0.82%   |
| 0x06001119 | 3         | 0.82%   |
| 0xa0660    | 2         | 0.54%   |
| 0x806eb    | 2         | 0.54%   |
| 0x6d8      | 2         | 0.54%   |
| 0x106e5    | 2         | 0.54%   |
| 0x106ca    | 2         | 0.54%   |
| 0x08608103 | 2         | 0.54%   |
| 0x0700010f | 2         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 71        | 19.94%  |
| SandyBridge      | 38        | 10.67%  |
| IvyBridge        | 33        | 9.27%   |
| Haswell          | 23        | 6.46%   |
| Skylake          | 22        | 6.18%   |
| Penryn           | 20        | 5.62%   |
| Silvermont       | 12        | 3.37%   |
| CometLake        | 12        | 3.37%   |
| Zen 3            | 11        | 3.09%   |
| Westmere         | 11        | 3.09%   |
| Puma             | 10        | 2.81%   |
| Unknown          | 10        | 2.81%   |
| Excavator        | 9         | 2.53%   |
| Alderlake Hybrid | 9         | 2.53%   |
| Zen+             | 8         | 2.25%   |
| TigerLake        | 8         | 2.25%   |
| Broadwell        | 8         | 2.25%   |
| Icelake          | 6         | 1.69%   |
| Goldmont plus    | 4         | 1.12%   |
| Goldmont         | 4         | 1.12%   |
| Core             | 4         | 1.12%   |
| Zen 2            | 3         | 0.84%   |
| Piledriver       | 3         | 0.84%   |
| Nehalem          | 3         | 0.84%   |
| Jaguar           | 3         | 0.84%   |
| Bonnell          | 3         | 0.84%   |
| Bobcat           | 3         | 0.84%   |
| P6               | 2         | 0.56%   |
| Tremont          | 1         | 0.28%   |
| K8 Hammer        | 1         | 0.28%   |
| K8 & K10 hybrid  | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 262       | 57.96%  |
| AMD    | 97        | 21.46%  |
| Nvidia | 93        | 20.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 33        | 7.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 28        | 5.94%   |
| Intel UHD Graphics 620                                                                | 20        | 4.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 2.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 13        | 2.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                   | 10        | 2.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 10        | 2.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 2.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 8         | 1.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 1.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 8         | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 1.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 1.49%   |
| Intel HD Graphics 630                                                                 | 7         | 1.49%   |
| Intel HD Graphics 620                                                                 | 7         | 1.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 6         | 1.27%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 6         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 6         | 1.27%   |
| Intel HD Graphics 5500                                                                | 5         | 1.06%   |
| Intel HD Graphics 530                                                                 | 5         | 1.06%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 5         | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.85%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 4         | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 4         | 0.85%   |
| Nvidia C79 [GeForce 9400M]                                                            | 4         | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 0.85%   |
| Intel HD Graphics 500                                                                 | 4         | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 4         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 47.75%  |
| Intel + Nvidia | 67        | 18.82%  |
| 1 x AMD        | 56        | 15.73%  |
| Intel + AMD    | 23        | 6.46%   |
| 1 x Nvidia     | 18        | 5.06%   |
| 2 x AMD        | 12        | 3.37%   |
| AMD + Nvidia   | 6         | 1.69%   |
| 2 x Nvidia     | 2         | 0.56%   |
| Other          | 1         | 0.28%   |
| 2 x Intel      | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 301       | 84.08%  |
| Proprietary | 48        | 13.41%  |
| Unknown     | 9         | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 235       | 64.56%  |
| 0.01-0.5   | 39        | 10.71%  |
| 1.01-2.0   | 32        | 8.79%   |
| 0.51-1.0   | 28        | 7.69%   |
| 3.01-4.0   | 16        | 4.4%    |
| 5.01-6.0   | 6         | 1.65%   |
| 7.01-8.0   | 5         | 1.37%   |
| 2.01-3.0   | 2         | 0.55%   |
| 8.01-16.0  | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 71        | 16.78%  |
| LG Display              | 60        | 14.18%  |
| Chimei Innolux          | 58        | 13.71%  |
| Samsung Electronics     | 51        | 12.06%  |
| BOE                     | 38        | 8.98%   |
| Goldstar                | 17        | 4.02%   |
| Dell                    | 17        | 4.02%   |
| Chi Mei Optoelectronics | 16        | 3.78%   |
| Sharp                   | 15        | 3.55%   |
| AOC                     | 12        | 2.84%   |
| Apple                   | 9         | 2.13%   |
| InfoVision              | 6         | 1.42%   |
| Philips                 | 5         | 1.18%   |
| PANDA                   | 5         | 1.18%   |
| Lenovo                  | 4         | 0.95%   |
| ViewSonic               | 3         | 0.71%   |
| Sony                    | 3         | 0.71%   |
| Hewlett-Packard         | 3         | 0.71%   |
| Valve                   | 2         | 0.47%   |
| Quanta Display          | 2         | 0.47%   |
| Panasonic               | 2         | 0.47%   |
| InnoLux Display         | 2         | 0.47%   |
| HannStar                | 2         | 0.47%   |
| Denver                  | 2         | 0.47%   |
| Ancor Communications    | 2         | 0.47%   |
| Acer                    | 2         | 0.47%   |
| Yamaha                  | 1         | 0.24%   |
| Wacom                   | 1         | 0.24%   |
| TMX                     | 1         | 0.24%   |
| SANYO                   | 1         | 0.24%   |
| PRISM+                  | 1         | 0.24%   |
| MStar                   | 1         | 0.24%   |
| MiTAC                   | 1         | 0.24%   |
| Mi                      | 1         | 0.24%   |
| LG Philips              | 1         | 0.24%   |
| Kogan                   | 1         | 0.24%   |
| IBM                     | 1         | 0.24%   |
| HYD                     | 1         | 0.24%   |
| HKC                     | 1         | 0.24%   |
| CPT                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 1.38%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 4         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.92%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 3         | 0.69%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.69%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.69%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.46%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.46%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.46%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 2         | 0.46%   |
| Panasonic TV MEIA0A6 1920x1080 698x392mm 31.5-inch                       | 2         | 0.46%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD041E 1920x1080 345x194mm 15.6-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.46%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch                 | 2         | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.46%   |
| Goldstar 23EN43 GSM59DC 1920x1080 510x290mm 23.1-inch                    | 2         | 0.46%   |
| Dell U3818DW DELA0F3 3840x1600 880x370mm 37.6-inch                       | 2         | 0.46%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.46%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.46%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 158       | 39.4%   |
| 1366x768 (WXGA)    | 114       | 28.43%  |
| 1600x900 (HD+)     | 27        | 6.73%   |
| 3840x2160 (4K)     | 18        | 4.49%   |
| 2560x1440 (QHD)    | 16        | 3.99%   |
| 1280x800 (WXGA)    | 15        | 3.74%   |
| 3440x1440          | 8         | 2%      |
| 1920x1200 (WUXGA)  | 8         | 2%      |
| 1440x900 (WXGA+)   | 7         | 1.75%   |
| 3200x1800 (QHD+)   | 4         | 1%      |
| 2880x1800          | 4         | 1%      |
| 1280x1024 (SXGA)   | 3         | 0.75%   |
| 1024x600           | 3         | 0.75%   |
| 800x1280           | 2         | 0.5%    |
| 3840x1600          | 2         | 0.5%    |
| 3456x2160          | 2         | 0.5%    |
| 2560x1600          | 2         | 0.5%    |
| 1680x1050 (WSXGA+) | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 2880x1920          | 1         | 0.25%   |
| 2560x1080          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1920x1280          | 1         | 0.25%   |
| 1360x768           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 167       | 39.11%  |
| 13      | 55        | 12.88%  |
| 14      | 52        | 12.18%  |
| 17      | 34        | 7.96%   |
| 27      | 23        | 5.39%   |
| 23      | 11        | 2.58%   |
| 24      | 9         | 2.11%   |
| 21      | 9         | 2.11%   |
| 31      | 8         | 1.87%   |
| 11      | 7         | 1.64%   |
| 34      | 5         | 1.17%   |
| 12      | 5         | 1.17%   |
| 10      | 5         | 1.17%   |
| 16      | 4         | 0.94%   |
| Unknown | 4         | 0.94%   |
| 37      | 3         | 0.7%    |
| 20      | 3         | 0.7%    |
| 18      | 3         | 0.7%    |
| 72      | 2         | 0.47%   |
| 46      | 2         | 0.47%   |
| 35      | 2         | 0.47%   |
| 22      | 2         | 0.47%   |
| 19      | 2         | 0.47%   |
| 7       | 2         | 0.47%   |
| 84      | 1         | 0.23%   |
| 60      | 1         | 0.23%   |
| 52      | 1         | 0.23%   |
| 40      | 1         | 0.23%   |
| 33      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |
| 28      | 1         | 0.23%   |
| 25      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 251       | 59.34%  |
| 501-600     | 40        | 9.46%   |
| 351-400     | 39        | 9.22%   |
| 201-300     | 39        | 9.22%   |
| 401-500     | 17        | 4.02%   |
| 601-700     | 12        | 2.84%   |
| 801-900     | 6         | 1.42%   |
| 701-800     | 6         | 1.42%   |
| 1001-1500   | 4         | 0.95%   |
| Unknown     | 4         | 0.95%   |
| 1501-2000   | 3         | 0.71%   |
| 1-100       | 2         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 300       | 82.64%  |
| 16/10   | 40        | 11.02%  |
| 21/9    | 11        | 3.03%   |
| 5/4     | 3         | 0.83%   |
| 3/2     | 3         | 0.83%   |
| 0.67    | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 4/3     | 1         | 0.28%   |
| 32/9    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 164       | 38.41%  |
| 81-90          | 89        | 20.84%  |
| 121-130        | 31        | 7.26%   |
| 201-250        | 28        | 6.56%   |
| 301-350        | 23        | 5.39%   |
| 71-80          | 18        | 4.22%   |
| 351-500        | 17        | 3.98%   |
| 51-60          | 7         | 1.64%   |
| 151-200        | 7         | 1.64%   |
| 111-120        | 6         | 1.41%   |
| 501-1000       | 6         | 1.41%   |
| More than 1000 | 5         | 1.17%   |
| 61-70          | 5         | 1.17%   |
| 41-50          | 5         | 1.17%   |
| 141-150        | 4         | 0.94%   |
| Unknown        | 4         | 0.94%   |
| 251-300        | 3         | 0.7%    |
| 1-40           | 2         | 0.47%   |
| 131-140        | 2         | 0.47%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 151       | 36.3%   |
| 101-120       | 145       | 34.86%  |
| 51-100        | 70        | 16.83%  |
| 161-240       | 25        | 6.01%   |
| More than 240 | 15        | 3.61%   |
| 1-50          | 6         | 1.44%   |
| Unknown       | 4         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 275       | 74.73%  |
| 2     | 69        | 18.75%  |
| 3     | 12        | 3.26%   |
| 0     | 10        | 2.72%   |
| 4     | 2         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 210       | 37.1%   |
| Realtek Semiconductor             | 176       | 31.1%   |
| Qualcomm Atheros                  | 71        | 12.54%  |
| Broadcom                          | 35        | 6.18%   |
| MediaTek                          | 9         | 1.59%   |
| TP-Link                           | 8         | 1.41%   |
| Ralink                            | 8         | 1.41%   |
| Broadcom Limited                  | 8         | 1.41%   |
| Nvidia                            | 6         | 1.06%   |
| Hewlett-Packard                   | 6         | 1.06%   |
| DisplayLink                       | 4         | 0.71%   |
| Sierra Wireless                   | 3         | 0.53%   |
| Lenovo                            | 3         | 0.53%   |
| Marvell Technology Group          | 2         | 0.35%   |
| JMicron Technology                | 2         | 0.35%   |
| Dell                              | 2         | 0.35%   |
| ASIX Electronics                  | 2         | 0.35%   |
| STMicroelectronics                | 1         | 0.18%   |
| Samsung Electronics               | 1         | 0.18%   |
| Qualcomm                          | 1         | 0.18%   |
| OPPO Electronics                  | 1         | 0.18%   |
| NetGear                           | 1         | 0.18%   |
| Lite-On Technology                | 1         | 0.18%   |
| ICS Advent                        | 1         | 0.18%   |
| Fujitsu                           | 1         | 0.18%   |
| Espressi                          | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| Attansic Technology               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 102       | 14.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 4.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 3.17%   |
| Intel Wireless 8265 / 8275                                        | 20        | 2.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.59%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 2.31%   |
| Intel Wireless 7260                                               | 15        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.87%   |
| Intel Wireless 8260                                               | 13        | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.15%   |
| Intel Wireless 7265                                               | 8         | 1.15%   |
| Intel Wireless 3165                                               | 8         | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 1.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.15%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.86%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.72%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.72%   |
| Intel WiFi Link 5100                                              | 5         | 0.72%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.72%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 201       | 53.74%  |
| Qualcomm Atheros      | 63        | 16.84%  |
| Realtek Semiconductor | 38        | 10.16%  |
| Broadcom              | 28        | 7.49%   |
| MediaTek              | 9         | 2.41%   |
| TP-Link               | 8         | 2.14%   |
| Ralink                | 8         | 2.14%   |
| Broadcom Limited      | 8         | 2.14%   |
| Sierra Wireless       | 3         | 0.8%    |
| Hewlett-Packard       | 3         | 0.8%    |
| Dell                  | 2         | 0.53%   |
| Qualcomm              | 1         | 0.27%   |
| NetGear               | 1         | 0.27%   |
| Lite-On Technology    | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 20        | 5.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 4.79%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 4.26%   |
| Intel Wireless 7260                                            | 15        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 3.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 3.46%   |
| Intel Wireless 8260                                            | 13        | 3.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 3.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 2.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.66%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 2.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.13%   |
| Intel Wireless 7265                                            | 8         | 2.13%   |
| Intel Wireless 3165                                            | 8         | 2.13%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 2.13%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 1.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.6%    |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.6%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.33%   |
| Intel WiFi Link 5100                                           | 5         | 1.33%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.33%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 1.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.8%    |
| Intel Wireless-AC 9260                                         | 3         | 0.8%    |
| Intel Wireless 3160                                            | 3         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.8%    |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 162       | 52.6%   |
| Intel                    | 92        | 29.87%  |
| Qualcomm Atheros         | 21        | 6.82%   |
| Broadcom                 | 10        | 3.25%   |
| Nvidia                   | 6         | 1.95%   |
| DisplayLink              | 4         | 1.3%    |
| Lenovo                   | 3         | 0.97%   |
| Marvell Technology Group | 2         | 0.65%   |
| JMicron Technology       | 2         | 0.65%   |
| ASIX Electronics         | 2         | 0.65%   |
| Samsung Electronics      | 1         | 0.32%   |
| OPPO Electronics         | 1         | 0.32%   |
| ICS Advent               | 1         | 0.32%   |
| Attansic Technology      | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 102       | 32.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 9.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 7.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 5.81%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 2.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 2.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.94%   |
| Nvidia MCP79 Ethernet                                             | 5         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.61%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 1.61%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.61%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.29%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.29%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.29%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.97%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.97%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.65%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.65%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.65%   |
| Intel Killer E3100 2.5 Gigabit Ethernet Controller                | 2         | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.65%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 352       | 53.82%  |
| Ethernet | 294       | 44.95%  |
| Modem    | 8         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 307       | 78.72%  |
| Ethernet | 83        | 21.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 266       | 74.72%  |
| 1     | 85        | 23.88%  |
| 3     | 3         | 0.84%   |
| 0     | 2         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 306       | 84.76%  |
| Yes  | 55        | 15.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 152       | 51.7%   |
| Qualcomm Atheros Communications | 25        | 8.5%    |
| Broadcom                        | 18        | 6.12%   |
| Realtek Semiconductor           | 17        | 5.78%   |
| Lite-On Technology              | 14        | 4.76%   |
| IMC Networks                    | 14        | 4.76%   |
| Foxconn / Hon Hai               | 13        | 4.42%   |
| Hewlett-Packard                 | 12        | 4.08%   |
| Apple                           | 9         | 3.06%   |
| Toshiba                         | 5         | 1.7%    |
| Ralink Technology               | 3         | 1.02%   |
| Dell                            | 3         | 1.02%   |
| Realtek                         | 2         | 0.68%   |
| Ralink                          | 2         | 0.68%   |
| ASUSTek Computer                | 2         | 0.68%   |
| Alps Electric                   | 2         | 0.68%   |
| Edimax Technology               | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 62        | 21.09%  |
| Intel AX201 Bluetooth                            | 24        | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 18        | 6.12%   |
| Intel AX200 Bluetooth                            | 16        | 5.44%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 12        | 4.08%   |
| Realtek Bluetooth Radio                          | 10        | 3.4%    |
| Qualcomm Atheros  Bluetooth Device               | 9         | 3.06%   |
| HP Broadcom 2070 Bluetooth Combo                 | 8         | 2.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 7         | 2.38%   |
| IMC Networks Wireless_Device                     | 7         | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                   | 6         | 2.04%   |
| Intel Bluetooth Device                           | 6         | 2.04%   |
| Apple Bluetooth Host Controller                  | 6         | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                 | 5         | 1.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 5         | 1.7%    |
| IMC Networks Bluetooth Radio                     | 5         | 1.7%    |
| Foxconn / Hon Hai Bluetooth Device               | 5         | 1.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 4         | 1.36%   |
| Lite-On Bluetooth Device                         | 4         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                 | 4         | 1.36%   |
| Broadcom BCM2045B (BDC-2.1)                      | 4         | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                | 3         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 3         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 3         | 1.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 3         | 1.02%   |
| Foxconn / Hon Hai Acer Module                    | 3         | 1.02%   |
| Broadcom HP Portable SoftSailing                 | 3         | 1.02%   |
| Broadcom BCM20702A0                              | 3         | 1.02%   |
| Toshiba Bluetooth USB Host Controller            | 2         | 0.68%   |
| Toshiba Bluetooth Radio                          | 2         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                    | 2         | 0.68%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter     | 2         | 0.68%   |
| Ralink RT3290 Bluetooth                          | 2         | 0.68%   |
| Intel AX210 Bluetooth                            | 2         | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 2         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 0.68%   |
| Apple Bluetooth USB Host Controller              | 2         | 0.68%   |
| Alps Electric BCM2046 Bluetooth Device           | 2         | 0.68%   |
| Toshiba BRCM Bluetooth Controller BCM2070        | 1         | 0.34%   |
| Realtek RTL8821A Bluetooth                       | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 291       | 63.26%  |
| AMD                       | 75        | 16.3%   |
| Nvidia                    | 57        | 12.39%  |
| Hewlett-Packard           | 8         | 1.74%   |
| Realtek Semiconductor     | 5         | 1.09%   |
| Logitech                  | 4         | 0.87%   |
| Lenovo                    | 3         | 0.65%   |
| Plantronics               | 2         | 0.43%   |
| Generalplus Technology    | 2         | 0.43%   |
| Texas Instruments         | 1         | 0.22%   |
| SteelSeries ApS           | 1         | 0.22%   |
| Sennheiser Communications | 1         | 0.22%   |
| Microsoft                 | 1         | 0.22%   |
| Micro Star International  | 1         | 0.22%   |
| Harman                    | 1         | 0.22%   |
| GYROCOM C&C               | 1         | 0.22%   |
| Google                    | 1         | 0.22%   |
| Conexant Systems          | 1         | 0.22%   |
| CMX Systems               | 1         | 0.22%   |
| ClearOne Communications   | 1         | 0.22%   |
| Belkin Components         | 1         | 0.22%   |
| AST Research              | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 45        | 8.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 7.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 5.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 4.95%   |
| AMD FCH Azalia Controller                                                  | 18        | 3.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 14        | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 2.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 2.39%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 2.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 2.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 1.83%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.47%   |
| Intel CM238 HD Audio Controller                                            | 8         | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.47%   |
| Hewlett-Packard USB Audio                                                  | 8         | 1.47%   |
| AMD High Definition Audio Controller                                       | 8         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.1%    |
| Realtek Semiconductor USB Audio                                            | 5         | 0.92%   |
| Nvidia MCP79 High Definition Audio                                         | 5         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 29.34%  |
| SK hynix            | 60        | 24.79%  |
| Micron Technology   | 38        | 15.7%   |
| Kingston            | 21        | 8.68%   |
| Crucial             | 19        | 7.85%   |
| Unknown             | 6         | 2.48%   |
| A-DATA Technology   | 6         | 2.48%   |
| Elpida              | 5         | 2.07%   |
| Team                | 2         | 0.83%   |
| Strontium           | 2         | 0.83%   |
| Shenzhen Mic        | 2         | 0.83%   |
| Ramaxel Technology  | 2         | 0.83%   |
| Unknown (ABCD)      | 1         | 0.41%   |
| Transcend           | 1         | 0.41%   |
| Neo Forza           | 1         | 0.41%   |
| Nanya Technology    | 1         | 0.41%   |
| G.Skill             | 1         | 0.41%   |
| fef5                | 1         | 0.41%   |
| Corsair             | 1         | 0.41%   |
| Apacer              | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 2.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 6         | 2.37%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s       | 4         | 1.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 1.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 4         | 1.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 4         | 1.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 4         | 1.58%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 3         | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 3         | 1.19%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                   | 3         | 1.19%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                  | 3         | 1.19%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.19%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s        | 3         | 1.19%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 3         | 1.19%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s       | 3         | 1.19%   |
| Unknown RAM Module 4096MB SODIMM DDR3                         | 2         | 0.79%   |
| SK hynix RAM Module 16GB SODIMM DDR5 4800MT/s                 | 2         | 0.79%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s         | 2         | 0.79%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s          | 2         | 0.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 2         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 2         | 0.79%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s   | 2         | 0.79%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                  | 2         | 0.79%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s      | 2         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s      | 2         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.79%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 2         | 0.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 2         | 0.79%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 0.79%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.79%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.79%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM 1334MT/s              | 2         | 0.79%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 2         | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.79%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s        | 2         | 0.79%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.79%   |
| Kingston RAM ACR16D3LS1NGG/4G 4096MB SODIMM DDR3 1600MT/s     | 2         | 0.79%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 43.3%   |
| DDR3    | 74        | 38.14%  |
| DDR2    | 8         | 4.12%   |
| LPDDR3  | 7         | 3.61%   |
| DDR5    | 7         | 3.61%   |
| SDRAM   | 6         | 3.09%   |
| LPDDR4  | 5         | 2.58%   |
| Unknown | 2         | 1.03%   |
| LPDDR5  | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 91.24%  |
| Row Of Chips | 11        | 5.67%   |
| Chip         | 3         | 1.55%   |
| Unknown      | 3         | 1.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 80        | 39.02%  |
| 4096  | 56        | 27.32%  |
| 16384 | 37        | 18.05%  |
| 2048  | 24        | 11.71%  |
| 32768 | 7         | 3.41%   |
| 1024  | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 25.24%  |
| 3200    | 38        | 18.1%   |
| 2667    | 30        | 14.29%  |
| 2400    | 15        | 7.14%   |
| 1334    | 15        | 7.14%   |
| 2133    | 9         | 4.29%   |
| 4800    | 7         | 3.33%   |
| 1333    | 7         | 3.33%   |
| 1067    | 7         | 3.33%   |
| 667     | 5         | 2.38%   |
| 1867    | 4         | 1.9%    |
| Unknown | 4         | 1.9%    |
| 8400    | 3         | 1.43%   |
| 4199    | 3         | 1.43%   |
| 3733    | 2         | 0.95%   |
| 2048    | 2         | 0.95%   |
| 975     | 2         | 0.95%   |
| 800     | 2         | 0.95%   |
| 6400    | 1         | 0.48%   |
| 4267    | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 33.33%  |
| HP DeskJet 2300 series        | 1         | 33.33%  |
| Canon G3010 series            | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 91        | 28.35%  |
| IMC Networks                           | 30        | 9.35%   |
| Sunplus Innovation Technology          | 24        | 7.48%   |
| Microdia                               | 24        | 7.48%   |
| Realtek Semiconductor                  | 23        | 7.17%   |
| Quanta                                 | 20        | 6.23%   |
| Bison Electronics                      | 16        | 4.98%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.36%   |
| Suyin                                  | 11        | 3.43%   |
| Lite-On Technology                     | 10        | 3.12%   |
| Apple                                  | 8         | 2.49%   |
| Luxvisions Innotech Limited            | 7         | 2.18%   |
| Logitech                               | 7         | 2.18%   |
| Syntek                                 | 5         | 1.56%   |
| Acer                                   | 5         | 1.56%   |
| Ricoh                                  | 4         | 1.25%   |
| Primax Electronics                     | 4         | 1.25%   |
| Alcor Micro                            | 4         | 1.25%   |
| Silicon Motion                         | 3         | 0.93%   |
| Samsung Electronics                    | 2         | 0.62%   |
| Importek                               | 2         | 0.62%   |
| Z-Star Microelectronics                | 1         | 0.31%   |
| Yealink Network Technology             | 1         | 0.31%   |
| Sonix Technology                       | 1         | 0.31%   |
| Intel                                  | 1         | 0.31%   |
| DigiTech                               | 1         | 0.31%   |
| AVer Information                       | 1         | 0.31%   |
| ALi                                    | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 15        | 4.66%   |
| Chicony integrated camera                     | 15        | 4.66%   |
| Chicony HP HD Camera                          | 12        | 3.73%   |
| Chicony HD WebCam                             | 11        | 3.42%   |
| Realtek Integrated_Webcam_HD                  | 8         | 2.48%   |
| Sunplus Integrated_Webcam_HD                  | 7         | 2.17%   |
| Sunplus HP HD Webcam [Fixed]                  | 7         | 2.17%   |
| IMC Networks Integrated Camera                | 7         | 2.17%   |
| Microdia Integrated_Webcam_HD                 | 6         | 1.86%   |
| Microdia Integrated Webcam HD                 | 6         | 1.86%   |
| Chicony HP HD Webcam                          | 6         | 1.86%   |
| Bison Integrated Camera                       | 6         | 1.86%   |
| Realtek HP Truevision HD                      | 5         | 1.55%   |
| Chicony TOSHIBA Web Camera - HD               | 5         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 5         | 1.55%   |
| Apple Built-in iSight                         | 5         | 1.55%   |
| Quanta HP TrueVision HD Camera                | 4         | 1.24%   |
| Quanta HP HD Camera                           | 4         | 1.24%   |
| Quanta Laptop_Integrated_Webcam_2HDM          | 3         | 0.93%   |
| Luxvisions Innotech Limited HP HD Camera      | 3         | 0.93%   |
| Lite-On Integrated Camera                     | 3         | 0.93%   |
| Lite-On HP HD Camera                          | 3         | 0.93%   |
| Chicony VGA Webcam                            | 3         | 0.93%   |
| Chicony USB2.0 Camera                         | 3         | 0.93%   |
| Chicony Integrated HP HD Webcam               | 3         | 0.93%   |
| Chicony HP Wide Vision HD Camera              | 3         | 0.93%   |
| Bison SunplusIT Integrated Camera             | 3         | 0.93%   |
| Syntek Integrated Camera                      | 2         | 0.62%   |
| Syntek EasyCamera                             | 2         | 0.62%   |
| Suyin HP Webcam                               | 2         | 0.62%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 0.62%   |
| Suyin HP Truevision HD                        | 2         | 0.62%   |
| Suyin 1.3M HD WebCam                          | 2         | 0.62%   |
| Sunplus HP TrueVision HD Camera               | 2         | 0.62%   |
| Sunplus HD WebCam                             | 2         | 0.62%   |
| Sunplus ASUS Webcam                           | 2         | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)       | 2         | 0.62%   |
| Realtek USB Camera                            | 2         | 0.62%   |
| Realtek Integrated Webcam_HD                  | 2         | 0.62%   |
| Realtek HP "Truevision HD" laptop camera      | 2         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 52%     |
| Synaptics                  | 25        | 25%     |
| Shenzhen Goodix Technology | 6         | 6%      |
| Upek                       | 5         | 5%      |
| AuthenTec                  | 5         | 5%      |
| Elan Microelectronics      | 4         | 4%      |
| LighTuning Technology      | 2         | 2%      |
| STMicroelectronics         | 1         | 1%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 13%     |
| Validity Sensors VFS491                                                    | 7         | 7%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 6%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 6%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 4%      |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3%      |
| Elan ELAN:Fingerprint                                                      | 3         | 3%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 2%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2%      |
| Shenzhen Goodix FingerPrint                                                | 2         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2%      |
| AuthenTec Fingerprint Sensor                                               | 2         | 2%      |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1%      |
| Elan ELAN:ARM-M4                                                           | 1         | 1%      |
| AuthenTec AES2810                                                          | 1         | 1%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1%      |
| AuthenTec AES1600                                                          | 1         | 1%      |
| Unknown                                                                    | 1         | 1%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 63.64%  |
| Lenovo      | 3         | 13.64%  |
| Alcor Micro | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |
| O2 Micro    | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 7         | 31.82%  |
| Broadcom 58200                                             | 4         | 18.18%  |
| Lenovo Integrated Smart Card Reader                        | 3         | 13.64%  |
| Broadcom 5880                                              | 3         | 13.64%  |
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 197       | 53.24%  |
| 1     | 137       | 37.03%  |
| 2     | 30        | 8.11%   |
| 3     | 3         | 0.81%   |
| 6     | 2         | 0.54%   |
| 5     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 98        | 46.45%  |
| Graphics card            | 35        | 16.59%  |
| Net/wireless             | 23        | 10.9%   |
| Chipcard                 | 20        | 9.48%   |
| Multimedia controller    | 10        | 4.74%   |
| Camera                   | 5         | 2.37%   |
| Net/ethernet             | 4         | 1.9%    |
| Sound                    | 3         | 1.42%   |
| Communication controller | 3         | 1.42%   |
| Bluetooth                | 3         | 1.42%   |
| Network                  | 2         | 0.95%   |
| Card reader              | 2         | 0.95%   |
| Storage                  | 1         | 0.47%   |
| Modem                    | 1         | 0.47%   |
| Flash memory             | 1         | 0.47%   |

