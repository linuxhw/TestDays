Void - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Void.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void/Desktop/README.md) and [notebooks](/Dist/Void/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| ASRock        | J4005B-ITX                  | Desktop     | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [32c0e61ea7](https://linux-hardware.org/?probe=32c0e61ea7) | May 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Dell          | Inspiron 11 - 3148          | Notebook    | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Acer          | AO722                       | Notebook    | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| HP            | 82C0                        | Mini pc     | [44430304d3](https://linux-hardware.org/?probe=44430304d3) | Oct 19, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | Notebook    | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| Acer          | Nitro AN715-51              | Notebook    | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | Notebook    | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | Notebook    | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| ASUSTek       | P8H67-V                     | Desktop     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Acer          | AO722                       | Notebook    | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | Notebook    | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | Notebook    | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | Notebook    | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| Dell          | 0H8052                      | Desktop     | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek       | X555UJ                      | Notebook    | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Google        | Chell                       | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| ASRock        | AB350M                      | Desktop     | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| MSI           | B350M GAMING PRO            | Desktop     | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| Positivo      | Mobile                      | Notebook    | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.13.19_1           | 6         | 6.74%   |
| 5.8.18_1            | 4         | 4.49%   |
| 5.3.9_1             | 4         | 4.49%   |
| 5.10.17_1           | 4         | 4.49%   |
| 5.8.12_1            | 3         | 3.37%   |
| 5.13.13_1           | 3         | 3.37%   |
| 5.12.10_1           | 3         | 3.37%   |
| 5.9.14_1            | 2         | 2.25%   |
| 5.4.24_1            | 2         | 2.25%   |
| 5.4.13_2            | 2         | 2.25%   |
| 5.13.15_1           | 2         | 2.25%   |
| 5.13.10_1           | 2         | 2.25%   |
| 5.12.14_1           | 2         | 2.25%   |
| 5.11.9_1            | 2         | 2.25%   |
| 5.10.14_1           | 2         | 2.25%   |
| 5.9.16_1            | 1         | 1.12%   |
| 5.9.0-rc8_2         | 1         | 1.12%   |
| 5.8.9_1             | 1         | 1.12%   |
| 5.8.8_1             | 1         | 1.12%   |
| 5.8.7_1             | 1         | 1.12%   |
| 5.8.6_1             | 1         | 1.12%   |
| 5.8.5_1             | 1         | 1.12%   |
| 5.8.16_1            | 1         | 1.12%   |
| 5.8.14_1            | 1         | 1.12%   |
| 5.8.12_2            | 1         | 1.12%   |
| 5.8.11_1            | 1         | 1.12%   |
| 5.8.10_1            | 1         | 1.12%   |
| 5.7.16_1            | 1         | 1.12%   |
| 5.6.14_1            | 1         | 1.12%   |
| 5.4.35_1            | 1         | 1.12%   |
| 5.4.21_1            | 1         | 1.12%   |
| 5.4.15_1            | 1         | 1.12%   |
| 5.3.16_1            | 1         | 1.12%   |
| 5.2.13_1            | 1         | 1.12%   |
| 5.14.0_1            | 1         | 1.12%   |
| 5.13.18_1           | 1         | 1.12%   |
| 5.13.12_1           | 1         | 1.12%   |
| 5.12.7_1            | 1         | 1.12%   |
| 5.12.6              | 1         | 1.12%   |
| 5.12.3-tkg-MuQSS_22 | 1         | 1.12%   |
| 5.12.19_1           | 1         | 1.12%   |
| 5.11.18_1           | 1         | 1.12%   |
| 5.11.16_1           | 1         | 1.12%   |
| 5.11.11_1           | 1         | 1.12%   |
| 5.10.9_1            | 1         | 1.12%   |
| 5.10.8_1            | 1         | 1.12%   |
| 5.10.88_1           | 1         | 1.12%   |
| 5.10.80_1           | 1         | 1.12%   |
| 5.10.7_1            | 1         | 1.12%   |
| 5.10.67_1           | 1         | 1.12%   |
| 5.10.46_1           | 1         | 1.12%   |
| 5.10.3_1            | 1         | 1.12%   |
| 5.10.23_1           | 1         | 1.12%   |
| 5.1.17_1            | 1         | 1.12%   |
| 5.1.10_1            | 1         | 1.12%   |
| 4.4.177_1           | 1         | 1.12%   |
| 4.19.67_1           | 1         | 1.12%   |
| 4.19.66_1           | 1         | 1.12%   |
| 4.19.34_1           | 1         | 1.12%   |
| 4.19.31_1           | 1         | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.13.19  | 6         | 6.74%   |
| 5.8.18   | 4         | 4.49%   |
| 5.8.12   | 4         | 4.49%   |
| 5.3.9    | 4         | 4.49%   |
| 5.10.17  | 4         | 4.49%   |
| 5.13.13  | 3         | 3.37%   |
| 5.12.10  | 3         | 3.37%   |
| 5.9.14   | 2         | 2.25%   |
| 5.4.24   | 2         | 2.25%   |
| 5.4.13   | 2         | 2.25%   |
| 5.13.15  | 2         | 2.25%   |
| 5.13.10  | 2         | 2.25%   |
| 5.12.14  | 2         | 2.25%   |
| 5.11.9   | 2         | 2.25%   |
| 5.10.14  | 2         | 2.25%   |
| 5.9.16   | 1         | 1.12%   |
| 5.9.0    | 1         | 1.12%   |
| 5.8.9    | 1         | 1.12%   |
| 5.8.8    | 1         | 1.12%   |
| 5.8.7    | 1         | 1.12%   |
| 5.8.6    | 1         | 1.12%   |
| 5.8.5    | 1         | 1.12%   |
| 5.8.16   | 1         | 1.12%   |
| 5.8.14   | 1         | 1.12%   |
| 5.8.11   | 1         | 1.12%   |
| 5.8.10   | 1         | 1.12%   |
| 5.7.16   | 1         | 1.12%   |
| 5.6.14   | 1         | 1.12%   |
| 5.4.35   | 1         | 1.12%   |
| 5.4.21   | 1         | 1.12%   |
| 5.4.15   | 1         | 1.12%   |
| 5.3.16   | 1         | 1.12%   |
| 5.2.13   | 1         | 1.12%   |
| 5.14.0   | 1         | 1.12%   |
| 5.13.18  | 1         | 1.12%   |
| 5.13.12  | 1         | 1.12%   |
| 5.12.7   | 1         | 1.12%   |
| 5.12.6   | 1         | 1.12%   |
| 5.12.3   | 1         | 1.12%   |
| 5.12.19  | 1         | 1.12%   |
| 5.11.18  | 1         | 1.12%   |
| 5.11.16  | 1         | 1.12%   |
| 5.11.11  | 1         | 1.12%   |
| 5.10.9   | 1         | 1.12%   |
| 5.10.88  | 1         | 1.12%   |
| 5.10.80  | 1         | 1.12%   |
| 5.10.8   | 1         | 1.12%   |
| 5.10.7   | 1         | 1.12%   |
| 5.10.67  | 1         | 1.12%   |
| 5.10.46  | 1         | 1.12%   |
| 5.10.3   | 1         | 1.12%   |
| 5.10.23  | 1         | 1.12%   |
| 5.1.17   | 1         | 1.12%   |
| 5.1.10   | 1         | 1.12%   |
| 4.4.177  | 1         | 1.12%   |
| 4.19.67  | 1         | 1.12%   |
| 4.19.66  | 1         | 1.12%   |
| 4.19.34  | 1         | 1.12%   |
| 4.19.31  | 1         | 1.12%   |
| 4.14.163 | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 17        | 19.32%  |
| 5.13    | 15        | 17.05%  |
| 5.10    | 15        | 17.05%  |
| 5.12    | 9         | 10.23%  |
| 5.4     | 7         | 7.95%   |
| 5.3     | 5         | 5.68%   |
| 5.11    | 5         | 5.68%   |
| 5.9     | 4         | 4.55%   |
| 4.19    | 4         | 4.55%   |
| 5.7     | 1         | 1.14%   |
| 5.6     | 1         | 1.14%   |
| 5.2     | 1         | 1.14%   |
| 5.14    | 1         | 1.14%   |
| 5.1     | 1         | 1.14%   |
| 4.4     | 1         | 1.14%   |
| 4.14    | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 75        | 91.46%  |
| i686    | 4         | 4.88%   |
| aarch64 | 2         | 2.44%   |
| ppc64le | 1         | 1.22%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 51.16%  |
| XFCE       | 9         | 10.47%  |
| KDE        | 7         | 8.14%   |
| MATE       | 6         | 6.98%   |
| i3         | 5         | 5.81%   |
| GNOME      | 5         | 5.81%   |
| X-Cinnamon | 3         | 3.49%   |
| bspwm      | 3         | 3.49%   |
| Lumina     | 2         | 2.33%   |
| KDE5       | 1         | 1.16%   |
| awesome    | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 61        | 73.49%  |
| Tty     | 11        | 13.25%  |
| Wayland | 8         | 9.64%   |
| Unknown | 3         | 3.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 97.59%  |
| SDDM    | 1         | 1.2%    |
| LXDM    | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 43        | 50%     |
| Unknown | 15        | 17.44%  |
| en_GB   | 6         | 6.98%   |
| ru_RU   | 3         | 3.49%   |
| en_DK   | 3         | 3.49%   |
| de_DE   | 3         | 3.49%   |
| pt_BR   | 2         | 2.33%   |
| en_AU   | 2         | 2.33%   |
| ru_UA   | 1         | 1.16%   |
| nb_NO   | 1         | 1.16%   |
| fr_FR   | 1         | 1.16%   |
| es_DO   | 1         | 1.16%   |
| en_NZ   | 1         | 1.16%   |
| en_CA   | 1         | 1.16%   |
| el_GR   | 1         | 1.16%   |
| cs_CZ   | 1         | 1.16%   |
| bg_BG   | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 53.01%  |
| EFI  | 39        | 46.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 50        | 60.24%  |
| Btrfs   | 16        | 19.28%  |
| Zfs     | 5         | 6.02%   |
| Xfs     | 5         | 6.02%   |
| Unknown | 5         | 6.02%   |
| F2fs    | 1         | 1.2%    |
| Ext3    | 1         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 43        | 51.19%  |
| Unknown | 29        | 34.52%  |
| MBR     | 12        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 87.8%   |
| Yes       | 10        | 12.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 80.49%  |
| Yes       | 16        | 19.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 24.39%  |
| Lenovo              | 11        | 13.41%  |
| Acer                | 11        | 13.41%  |
| Dell                | 8         | 9.76%   |
| Hewlett-Packard     | 7         | 8.54%   |
| MSI                 | 6         | 7.32%   |
| ASRock              | 6         | 7.32%   |
| Gigabyte Technology | 3         | 3.66%   |
| Unknown             | 3         | 3.66%   |
| Samsung Electronics | 1         | 1.22%   |
| Positivo            | 1         | 1.22%   |
| Pine Microsystems   | 1         | 1.22%   |
| Google              | 1         | 1.22%   |
| Getac               | 1         | 1.22%   |
| Digibras            | 1         | 1.22%   |
| Chuwi               | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 3         | 3.66%   |
| ASUS PRIME Z390-P                       | 2         | 2.44%   |
| Samsung 275E4E/275E5E                   | 1         | 1.22%   |
| Positivo Mobile                         | 1         | 1.22%   |
| Pine Microsystems Pine64 Pinebook Pro   | 1         | 1.22%   |
| MSI MS-7C92                             | 1         | 1.22%   |
| MSI MS-7C52                             | 1         | 1.22%   |
| MSI MS-7C02                             | 1         | 1.22%   |
| MSI MS-7A68                             | 1         | 1.22%   |
| MSI MS-7A39                             | 1         | 1.22%   |
| MSI Bravo 15 A4DDR                      | 1         | 1.22%   |
| Lenovo Yoga 720-15IKB 80X7              | 1         | 1.22%   |
| Lenovo ThinkPad X260 20F5S08Q00         | 1         | 1.22%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS  | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L6SA5Q00         | 1         | 1.22%   |
| Lenovo ThinkPad T430 2349PS3            | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW   | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00   | 1         | 1.22%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200    | 1         | 1.22%   |
| Lenovo IdeaPad Z570 10246ZG             | 1         | 1.22%   |
| Lenovo IdeaPad 710S-13IKB 80VQ          | 1         | 1.22%   |
| Lenovo G50-45 80E3                      | 1         | 1.22%   |
| HP Z2 Mini G3 Workstation               | 1         | 1.22%   |
| HP Stream 7 Tablet                      | 1         | 1.22%   |
| HP Pavilion Notebook                    | 1         | 1.22%   |
| HP Laptop 15-bw0xx                      | 1         | 1.22%   |
| HP Laptop 14-dk0xxx                     | 1         | 1.22%   |
| HP Laptop 14-bs0xx                      | 1         | 1.22%   |
| HP 15                                   | 1         | 1.22%   |
| Google Chell                            | 1         | 1.22%   |
| Gigabyte H310M M.2 2.0                  | 1         | 1.22%   |
| Gigabyte GA-78LMT-S2                    | 1         | 1.22%   |
| Gigabyte B450M DS3H                     | 1         | 1.22%   |
| Getac V110                              | 1         | 1.22%   |
| Digibras NH4CU03                        | 1         | 1.22%   |
| Dell Precision 3530                     | 1         | 1.22%   |
| Dell OptiPlex GX520                     | 1         | 1.22%   |
| Dell OptiPlex 780                       | 1         | 1.22%   |
| Dell Latitude E4300                     | 1         | 1.22%   |
| Dell Inspiron 5555                      | 1         | 1.22%   |
| Dell Inspiron 1501                      | 1         | 1.22%   |
| Dell Inspiron 11 - 3148                 | 1         | 1.22%   |
| Dell G3 3579                            | 1         | 1.22%   |
| Chuwi GemiBook Pro                      | 1         | 1.22%   |
| ASUS X751LD                             | 1         | 1.22%   |
| ASUS X555UJ                             | 1         | 1.22%   |
| ASUS X510UAR                            | 1         | 1.22%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL  | 1         | 1.22%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA  | 1         | 1.22%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 1         | 1.22%   |
| ASUS VivoBook 15_ASUS Laptop X540UB     | 1         | 1.22%   |
| ASUS TUF Gaming FX505DT_FX505DT         | 1         | 1.22%   |
| ASUS ROG CROSSHAIR VII HERO             | 1         | 1.22%   |
| ASUS PRIME Z270-AR                      | 1         | 1.22%   |
| ASUS PRIME A320M-K/BR                   | 1         | 1.22%   |
| ASUS P8Z77-V LX2                        | 1         | 1.22%   |
| ASUS P8H67-V                            | 1         | 1.22%   |
| ASUS M5A78L-M LX                        | 1         | 1.22%   |
| ASUS M4A89GTD-PRO/USB3                  | 1         | 1.22%   |
| ASUS H110M-PLUS                         | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 7         | 8.54%   |
| Acer Aspire              | 7         | 8.54%   |
| ASUS VivoBook            | 4         | 4.88%   |
| ASUS PRIME               | 4         | 4.88%   |
| HP Laptop                | 3         | 3.66%   |
| Dell Inspiron            | 3         | 3.66%   |
| Unknown                  | 3         | 3.66%   |
| Lenovo IdeaPad           | 2         | 2.44%   |
| Dell OptiPlex            | 2         | 2.44%   |
| Samsung 275E4E           | 1         | 1.22%   |
| Positivo Mobile          | 1         | 1.22%   |
| Pine Microsystems Pine64 | 1         | 1.22%   |
| MSI MS-7C92              | 1         | 1.22%   |
| MSI MS-7C52              | 1         | 1.22%   |
| MSI MS-7C02              | 1         | 1.22%   |
| MSI MS-7A68              | 1         | 1.22%   |
| MSI MS-7A39              | 1         | 1.22%   |
| MSI Bravo                | 1         | 1.22%   |
| Lenovo Yoga              | 1         | 1.22%   |
| Lenovo G50-45            | 1         | 1.22%   |
| HP Z2                    | 1         | 1.22%   |
| HP Stream                | 1         | 1.22%   |
| HP Pavilion              | 1         | 1.22%   |
| HP 15                    | 1         | 1.22%   |
| Google Chell             | 1         | 1.22%   |
| Gigabyte H310M           | 1         | 1.22%   |
| Gigabyte GA-78LMT-S2     | 1         | 1.22%   |
| Gigabyte B450M           | 1         | 1.22%   |
| Getac V110               | 1         | 1.22%   |
| Digibras NH4CU03         | 1         | 1.22%   |
| Dell Precision           | 1         | 1.22%   |
| Dell Latitude            | 1         | 1.22%   |
| Dell G3                  | 1         | 1.22%   |
| Chuwi GemiBook           | 1         | 1.22%   |
| ASUS X751LD              | 1         | 1.22%   |
| ASUS X555UJ              | 1         | 1.22%   |
| ASUS X510UAR             | 1         | 1.22%   |
| ASUS TUF                 | 1         | 1.22%   |
| ASUS ROG                 | 1         | 1.22%   |
| ASUS P8Z77-V             | 1         | 1.22%   |
| ASUS P8H67-V             | 1         | 1.22%   |
| ASUS M5A78L-M            | 1         | 1.22%   |
| ASUS M4A89GTD-PRO        | 1         | 1.22%   |
| ASUS H110M-PLUS          | 1         | 1.22%   |
| ASUS B150M               | 1         | 1.22%   |
| ASUS ASUS                | 1         | 1.22%   |
| ASRock N68-S3            | 1         | 1.22%   |
| ASRock J4005B-ITX        | 1         | 1.22%   |
| ASRock H61M-VG4          | 1         | 1.22%   |
| ASRock B450              | 1         | 1.22%   |
| ASRock AB350M            | 1         | 1.22%   |
| ASRock 970               | 1         | 1.22%   |
| Acer Swift               | 1         | 1.22%   |
| Acer Nitro               | 1         | 1.22%   |
| Acer AOA150              | 1         | 1.22%   |
| Acer AO722               | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 20        | 24.39%  |
| 2018    | 12        | 14.63%  |
| 2019    | 9         | 10.98%  |
| 2013    | 7         | 8.54%   |
| 2014    | 6         | 7.32%   |
| 2016    | 5         | 6.1%    |
| 2015    | 5         | 6.1%    |
| 2012    | 4         | 4.88%   |
| 2021    | 3         | 3.66%   |
| 2011    | 3         | 3.66%   |
| Unknown | 3         | 3.66%   |
| 2017    | 1         | 1.22%   |
| 2009    | 1         | 1.22%   |
| 2008    | 1         | 1.22%   |
| 2007    | 1         | 1.22%   |
| 2006    | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 49        | 59.76%  |
| Desktop     | 29        | 35.37%  |
| Convertible | 2         | 2.44%   |
| Tablet      | 1         | 1.22%   |
| Mini pc     | 1         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 24.1%   |
| 8.01-16.0   | 18        | 21.69%  |
| 3.01-4.0    | 16        | 19.28%  |
| 16.01-24.0  | 15        | 18.07%  |
| 32.01-64.0  | 7         | 8.43%   |
| 1.01-2.0    | 4         | 4.82%   |
| 2.01-3.0    | 1         | 1.2%    |
| 64.01-256.0 | 1         | 1.2%    |
| 0.51-1.0    | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 25        | 28.09%  |
| 2.01-3.0   | 22        | 24.72%  |
| 0.51-1.0   | 16        | 17.98%  |
| 4.01-8.0   | 9         | 10.11%  |
| 3.01-4.0   | 9         | 10.11%  |
| 8.01-16.0  | 4         | 4.49%   |
| 16.01-24.0 | 2         | 2.25%   |
| 0.01-0.5   | 2         | 2.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 62.2%   |
| 2      | 19        | 23.17%  |
| 3      | 11        | 13.41%  |
| 4      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 70.73%  |
| Yes       | 24        | 29.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 87.8%   |
| No        | 10        | 12.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 69.51%  |
| No        | 25        | 30.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 57.83%  |
| No        | 35        | 42.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 17        | 20.73%  |
| Germany            | 8         | 9.76%   |
| Brazil             | 7         | 8.54%   |
| India              | 6         | 7.32%   |
| Russia             | 5         | 6.1%    |
| Ukraine            | 4         | 4.88%   |
| UK                 | 4         | 4.88%   |
| Czechia            | 3         | 3.66%   |
| Bulgaria           | 3         | 3.66%   |
| Turkey             | 2         | 2.44%   |
| Switzerland        | 2         | 2.44%   |
| Greece             | 2         | 2.44%   |
| France             | 2         | 2.44%   |
| Denmark            | 2         | 2.44%   |
| Australia          | 2         | 2.44%   |
| Vietnam            | 1         | 1.22%   |
| Sweden             | 1         | 1.22%   |
| Spain              | 1         | 1.22%   |
| Poland             | 1         | 1.22%   |
| Peru               | 1         | 1.22%   |
| Norway             | 1         | 1.22%   |
| New Zealand        | 1         | 1.22%   |
| Netherlands        | 1         | 1.22%   |
| Ecuador            | 1         | 1.22%   |
| Dominican Republic | 1         | 1.22%   |
| Canada             | 1         | 1.22%   |
| Bangladesh         | 1         | 1.22%   |
| Argentina          | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Munich           | 3         | 3.57%   |
| Denver           | 3         | 3.57%   |
| Varna            | 2         | 2.38%   |
| Prague           | 2         | 2.38%   |
| Zurich           | 1         | 1.19%   |
| Yekaterinburg    | 1         | 1.19%   |
| Yambol           | 1         | 1.19%   |
| Vlaardingen      | 1         | 1.19%   |
| Viby             | 1         | 1.19%   |
| Uzhhorod         | 1         | 1.19%   |
| Trujillo         | 1         | 1.19%   |
| Toulouse         | 1         | 1.19%   |
| Toms River       | 1         | 1.19%   |
| Syktyvkar        | 1         | 1.19%   |
| Sydney           | 1         | 1.19%   |
| St Petersburg    | 1         | 1.19%   |
| South Shields    | 1         | 1.19%   |
| Schwabhausen     | 1         | 1.19%   |
| Saxtons River    | 1         | 1.19%   |
| Rostock          | 1         | 1.19%   |
| Rosario          | 1         | 1.19%   |
| Rio de Janeiro   | 1         | 1.19%   |
| Richmond         | 1         | 1.19%   |
| Regensburg       | 1         | 1.19%   |
| Pune             | 1         | 1.19%   |
| Porto Alegre     | 1         | 1.19%   |
| Phoenix          | 1         | 1.19%   |
| Peckham          | 1         | 1.19%   |
| Paris            | 1         | 1.19%   |
| New York         | 1         | 1.19%   |
| Nagua            | 1         | 1.19%   |
| Mossoro          | 1         | 1.19%   |
| Moscow           | 1         | 1.19%   |
| Miedziana Gora   | 1         | 1.19%   |
| Mesa             | 1         | 1.19%   |
| Matos Costa      | 1         | 1.19%   |
| Malvern          | 1         | 1.19%   |
| Los Angeles      | 1         | 1.19%   |
| London           | 1         | 1.19%   |
| Lakewood         | 1         | 1.19%   |
| Krynychky        | 1         | 1.19%   |
| Kremenchug       | 1         | 1.19%   |
| Kotlas           | 1         | 1.19%   |
| Kolkata          | 1         | 1.19%   |
| Izmir            | 1         | 1.19%   |
| Itanhaem         | 1         | 1.19%   |
| Ioannina         | 1         | 1.19%   |
| Horsens          | 1         | 1.19%   |
| Horice           | 1         | 1.19%   |
| Ho Chi Minh City | 1         | 1.19%   |
| Guayaquil        | 1         | 1.19%   |
| Gothenburg       | 1         | 1.19%   |
| Geneva           | 1         | 1.19%   |
| Ernakulam        | 1         | 1.19%   |
| Erlangen         | 1         | 1.19%   |
| Elgin            | 1         | 1.19%   |
| Dublin           | 1         | 1.19%   |
| Drammen          | 1         | 1.19%   |
| Dnipropetrovsk   | 1         | 1.19%   |
| Dhaka            | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 30     | 20%     |
| Samsung Electronics | 22        | 29     | 19.13%  |
| Seagate             | 18        | 20     | 15.65%  |
| Toshiba             | 7         | 7      | 6.09%   |
| Kingston            | 7         | 7      | 6.09%   |
| Intel               | 6         | 8      | 5.22%   |
| Unknown             | 5         | 9      | 4.35%   |
| Sandisk             | 4         | 5      | 3.48%   |
| HGST                | 4         | 5      | 3.48%   |
| SK Hynix            | 2         | 2      | 1.74%   |
| Patriot             | 2         | 2      | 1.74%   |
| Crucial             | 2         | 3      | 1.74%   |
| Corsair             | 2         | 2      | 1.74%   |
| Transcend           | 1         | 1      | 0.87%   |
| SPCC                | 1         | 1      | 0.87%   |
| Phison              | 1         | 1      | 0.87%   |
| OCZ                 | 1         | 1      | 0.87%   |
| MAXTOR              | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| Hitachi             | 1         | 1      | 0.87%   |
| Gigabyte Technology | 1         | 1      | 0.87%   |
| China               | 1         | 1      | 0.87%   |
| BHT                 | 1         | 1      | 0.87%   |
| A-DATA Technology   | 1         | 2      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 4         | 3.15%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 2.36%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.57%   |
| Toshiba MQ01ABF050 500GB                | 2         | 1.57%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 1.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.57%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.57%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.57%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.57%   |
| Patriot Burst 120GB SSD                 | 2         | 1.57%   |
| Kingston SHFS37A120G 120GB SSD          | 2         | 1.57%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.57%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 1.57%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.57%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.79%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.79%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.79%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.79%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.79%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.79%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.79%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 0.79%   |
| WDC WD15EARS-00MVWB0 1TB                | 1         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.79%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.79%   |
| WDC WD10JPVX-08JC3T6 1TB                | 1         | 0.79%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.79%   |
| WDC WD10EZRX-00L4HB0 1TB                | 1         | 0.79%   |
| WDC WD10EFRX-68PJCN0 1TB                | 1         | 0.79%   |
| WDC WD10EFRX-68FYTN0 1TB                | 1         | 0.79%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 0.79%   |
| WDC WD1001FALS-00K1B0 1TB               | 1         | 0.79%   |
| WDC WD Elements 500GB                   | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 0.79%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.79%   |
| Unknown SD512  512MB                    | 1         | 0.79%   |
| Unknown SD16G  16GB                     | 1         | 0.79%   |
| Unknown MMC Card  8GB                   | 1         | 0.79%   |
| Unknown MMC Card  7GB                   | 1         | 0.79%   |
| Unknown MMC Card  32GB                  | 1         | 0.79%   |
| Unknown MMC Card  128GB                 | 1         | 0.79%   |
| Unknown MMC Card                        | 1         | 0.79%   |
| Unknown CWBC3R  64GB                    | 1         | 0.79%   |
| Transcend TS128GMTS800 128GB SSD        | 1         | 0.79%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 0.79%   |
| Toshiba HDWD110 1TB                     | 1         | 0.79%   |
| Toshiba DT01ACA200 2TB                  | 1         | 0.79%   |
| SPCC Solid State Disk 128GB             | 1         | 0.79%   |
| Seagate ST98823AS 80GB                  | 1         | 0.79%   |
| Seagate ST9750420AS 752GB               | 1         | 0.79%   |
| Seagate ST9500325AS 500GB               | 1         | 0.79%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 0.79%   |
| Seagate ST3500413AS 500GB               | 1         | 0.79%   |
| Seagate ST3360320AS 360GB               | 1         | 0.79%   |
| Seagate ST2000LM015-2E81 2TB            | 1         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB          | 1         | 0.79%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 26     | 38.46%  |
| Seagate             | 18        | 20     | 34.62%  |
| Toshiba             | 6         | 6      | 11.54%  |
| HGST                | 4         | 5      | 7.69%   |
| Samsung Electronics | 2         | 2      | 3.85%   |
| MAXTOR              | 1         | 1      | 1.92%   |
| Hitachi             | 1         | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 28.13%  |
| Kingston            | 6         | 6      | 18.75%  |
| SanDisk             | 2         | 2      | 6.25%   |
| Patriot             | 2         | 2      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| Crucial             | 2         | 3      | 6.25%   |
| Transcend           | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| Gigabyte Technology | 1         | 1      | 3.13%   |
| Corsair             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| BHT                 | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 2      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 46        | 61     | 43.4%   |
| SSD     | 30        | 34     | 28.3%   |
| NVMe    | 24        | 36     | 22.64%  |
| MMC     | 5         | 9      | 4.72%   |
| Unknown | 1         | 1      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 93     | 65.96%  |
| NVMe | 24        | 36     | 25.53%  |
| MMC  | 5         | 9      | 5.32%   |
| SAS  | 3         | 3      | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 51     | 53.16%  |
| 0.51-1.0   | 28        | 33     | 35.44%  |
| 1.01-2.0   | 7         | 9      | 8.86%   |
| 4.01-10.0  | 2         | 2      | 2.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 23.81%  |
| 501-1000       | 19        | 22.62%  |
| 101-250        | 15        | 17.86%  |
| Unknown        | 9         | 10.71%  |
| More than 3000 | 5         | 5.95%   |
| 1001-2000      | 5         | 5.95%   |
| 21-50          | 3         | 3.57%   |
| 1-20           | 3         | 3.57%   |
| 51-100         | 3         | 3.57%   |
| 2001-3000      | 2         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 27.59%  |
| 1-20           | 19        | 21.84%  |
| 21-50          | 11        | 12.64%  |
| Unknown        | 9         | 10.34%  |
| 251-500        | 8         | 9.2%    |
| 51-100         | 8         | 9.2%    |
| 1001-2000      | 3         | 3.45%   |
| 501-1000       | 3         | 3.45%   |
| More than 3000 | 2         | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB         | 1         | 2      | 6.67%   |
| WDC WD1600BEVS-60VAT0 160GB         | 1         | 1      | 6.67%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 1      | 6.67%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 6.67%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 6.67%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 6.67%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 6.67%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 6.67%   |
| A-DATA Technology SU700 120GB SSD   | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| WDC                 | 3         | 4      | 20%     |
| HGST                | 2         | 2      | 13.33%  |
| Toshiba             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| WDC                 | 3         | 4      | 21.43%  |
| HGST                | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 48        | 69     | 49.48%  |
| Detected | 36        | 56     | 37.11%  |
| Malfunc  | 13        | 16     | 13.4%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 44%     |
| AMD                              | 28        | 28%     |
| Samsung Electronics              | 13        | 13%     |
| Sandisk                          | 4         | 4%      |
| SK Hynix                         | 2         | 2%      |
| Phison Electronics               | 2         | 2%      |
| Toshiba America Info Systems     | 1         | 1%      |
| Silicon Integrated Systems [SiS] | 1         | 1%      |
| Nvidia                           | 1         | 1%      |
| Marvell Technology Group         | 1         | 1%      |
| Kingston Technology Company      | 1         | 1%      |
| JMicron Technology               | 1         | 1%      |
| ASMedia Technology               | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 16.67%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 8.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 7.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.39%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 4.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 3.51%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.63%   |
| Intel SSD 660P Series                                                            | 3         | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.63%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.75%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.75%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.88%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.88%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.88%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.88%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.88%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.88%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.88%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.88%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.88%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 0.88%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 1         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.88%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.88%   |
| AMD SB600 IDE                                                                    | 1         | 0.88%   |
| AMD FCH SATA Controller D                                                        | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 64        | 62.75%  |
| NVMe | 25        | 24.51%  |
| IDE  | 9         | 8.82%   |
| RAID | 4         | 3.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 48        | 58.54%  |
| AMD                      | 31        | 37.8%   |
| ARM                      | 2         | 2.44%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 1.22%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 2.44%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 2.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 2.44%   |
| ARM Processor                                      | 2         | 2.44%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 2.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 2.44%   |
| AMD Ryzen 5 5600X 6-Core Processor                 | 2         | 2.44%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 2.44%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 1.22%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 1.22%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 1.22%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 1.22%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 1         | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1         | 1.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 1.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 1         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz                  | 1         | 1.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1         | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 1         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz                  | 1         | 1.22%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1         | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 1         | 1.22%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1         | 1.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz                  | 1         | 1.22%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1         | 1.22%   |
| Intel Core i3-7100U CPU @ 2.40GHz                  | 1         | 1.22%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1         | 1.22%   |
| Intel Core i3-6006U CPU @ 2.00GHz                  | 1         | 1.22%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 1         | 1.22%   |
| Intel Core i3-4005U CPU @ 1.70GHz                  | 1         | 1.22%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1         | 1.22%   |
| Intel Core i3-3217U CPU @ 1.80GHz                  | 1         | 1.22%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz               | 1         | 1.22%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1         | 1.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz                  | 1         | 1.22%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1         | 1.22%   |
| Intel Celeron CPU 847 @ 1.10GHz                    | 1         | 1.22%   |
| Intel Celeron CPU 1005M @ 1.90GHz                  | 1         | 1.22%   |
| Intel Atom CPU Z3735G @ 1.33GHz                    | 1         | 1.22%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 1         | 1.22%   |
| Intel Atom CPU N270 @ 1.60GHz                      | 1         | 1.22%   |
| AMD Turion 64 X2 Mobile Technology TL-50           | 1         | 1.22%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 1         | 1.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 1         | 1.22%   |
| AMD Ryzen 7 1700 Eight-Core Processor              | 1         | 1.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics             | 1         | 1.22%   |
| AMD Ryzen 5 4500U with Radeon Graphics             | 1         | 1.22%   |
| AMD Ryzen 5 3600 6-Core Processor                  | 1         | 1.22%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx      | 1         | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 20.73%  |
| Intel Core i7           | 10        | 12.2%   |
| AMD Ryzen 5             | 9         | 10.98%  |
| Intel Core i3           | 8         | 9.76%   |
| Other                   | 5         | 6.1%    |
| AMD Ryzen 7             | 5         | 6.1%    |
| Intel Celeron           | 4         | 4.88%   |
| Intel Atom              | 3         | 3.66%   |
| Intel Core 2 Duo        | 2         | 2.44%   |
| AMD Ryzen 7 PRO         | 2         | 2.44%   |
| AMD FX                  | 2         | 2.44%   |
| AMD A8                  | 2         | 2.44%   |
| Intel Pentium Gold      | 1         | 1.22%   |
| Intel Pentium 4         | 1         | 1.22%   |
| Intel Genuine           | 1         | 1.22%   |
| Intel Core i9           | 1         | 1.22%   |
| AMD Turion 64 X2 Mobile | 1         | 1.22%   |
| AMD Ryzen 3             | 1         | 1.22%   |
| AMD Phenom II X4        | 1         | 1.22%   |
| AMD E2                  | 1         | 1.22%   |
| AMD E1                  | 1         | 1.22%   |
| AMD C-60                | 1         | 1.22%   |
| AMD Athlon II X3        | 1         | 1.22%   |
| AMD Athlon II X2        | 1         | 1.22%   |
| AMD A4                  | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 37.8%   |
| 4      | 30        | 36.59%  |
| 6      | 9         | 10.98%  |
| 8      | 8         | 9.76%   |
| 1      | 3         | 3.66%   |
| 3      | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 81        | 98.78%  |
| 2      | 1         | 1.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 59.76%  |
| 1      | 32        | 39.02%  |
| 4      | 1         | 1.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 86.59%  |
| Unknown        | 7         | 8.54%   |
| 64-bit         | 2         | 2.44%   |
| 32-bit         | 2         | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 34.52%  |
| 0x40651    | 4         | 4.76%   |
| 0x306a9    | 4         | 4.76%   |
| 0x906ea    | 3         | 3.57%   |
| 0x906e9    | 3         | 3.57%   |
| 0x806e9    | 3         | 3.57%   |
| 0x806ec    | 2         | 2.38%   |
| 0x806ea    | 2         | 2.38%   |
| 0x406e3    | 2         | 2.38%   |
| 0x08600104 | 2         | 2.38%   |
| 0x08108102 | 2         | 2.38%   |
| 0x07030105 | 2         | 2.38%   |
| 0x06000852 | 2         | 2.38%   |
| 0x05000119 | 2         | 2.38%   |
| 0x010000c8 | 2         | 2.38%   |
| 0x906ed    | 1         | 1.19%   |
| 0x806eb    | 1         | 1.19%   |
| 0x706a1    | 1         | 1.19%   |
| 0x506e3    | 1         | 1.19%   |
| 0x30678    | 1         | 1.19%   |
| 0x206a7    | 1         | 1.19%   |
| 0x106c2    | 1         | 1.19%   |
| 0x1067a    | 1         | 1.19%   |
| 0x0a50000c | 1         | 1.19%   |
| 0x0a201009 | 1         | 1.19%   |
| 0x08701021 | 1         | 1.19%   |
| 0x08701013 | 1         | 1.19%   |
| 0x08600106 | 1         | 1.19%   |
| 0x08600102 | 1         | 1.19%   |
| 0x08101007 | 1         | 1.19%   |
| 0x0800820d | 1         | 1.19%   |
| 0x08001136 | 1         | 1.19%   |
| 0x08001129 | 1         | 1.19%   |
| 0x07030104 | 1         | 1.19%   |
| 0x06006705 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 25.61%  |
| Zen 2         | 7         | 8.54%   |
| IvyBridge     | 6         | 7.32%   |
| Skylake       | 5         | 6.1%    |
| Haswell       | 5         | 6.1%    |
| Zen+          | 4         | 4.88%   |
| Zen 3         | 3         | 3.66%   |
| Zen           | 3         | 3.66%   |
| Puma          | 3         | 3.66%   |
| K10           | 3         | 3.66%   |
| Excavator     | 3         | 3.66%   |
| Unknown       | 3         | 3.66%   |
| Silvermont    | 2         | 2.44%   |
| SandyBridge   | 2         | 2.44%   |
| Piledriver    | 2         | 2.44%   |
| Penryn        | 2         | 2.44%   |
| Goldmont plus | 2         | 2.44%   |
| Bobcat        | 2         | 2.44%   |
| NetBurst      | 1         | 1.22%   |
| K8 Hammer     | 1         | 1.22%   |
| Core          | 1         | 1.22%   |
| Bonnell       | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 37        | 37.37%  |
| Nvidia                           | 31        | 31.31%  |
| AMD                              | 29        | 29.29%  |
| Silicon Integrated Systems [SiS] | 1         | 1.01%   |
| ASPEED Technology                | 1         | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 4.85%   |
| AMD Renoir                                                                    | 5         | 4.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 2.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 2.91%   |
| Intel UHD Graphics 620                                                        | 3         | 2.91%   |
| Intel HD Graphics 620                                                         | 3         | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 2.91%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 2.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 3         | 2.91%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.94%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 2         | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2         | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.94%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 2         | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 1.94%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.97%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.97%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                         | 1         | 0.97%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                     | 1         | 0.97%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.97%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                          | 1         | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 1         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 0.97%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.97%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                          | 1         | 0.97%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.97%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1         | 0.97%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.97%   |
| Nvidia GF108 [GeForce GT 420]                                                 | 1         | 0.97%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1         | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 0.97%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.97%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.97%   |
| Intel HD Graphics 630                                                         | 1         | 0.97%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 0.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 1         | 0.97%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 0.97%   |
| AMD Wrestler [Radeon HD 6290]                                                 | 1         | 0.97%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 1         | 0.97%   |
| AMD Tonga PRO [Radeon R9 285/380]                                             | 1         | 0.97%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 1         | 0.97%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                        | 1         | 0.97%   |
| AMD RS880 [Radeon HD 4290]                                                    | 1         | 0.97%   |
| AMD RS780L [Radeon 3000]                                                      | 1         | 0.97%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                       | 1         | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 0.97%   |
| AMD Oland PRO [Radeon R7 240/340]                                             | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 24        | 28.92%  |
| 1 x Intel      | 22        | 26.51%  |
| 1 x Nvidia     | 14        | 16.87%  |
| Intel + Nvidia | 14        | 16.87%  |
| Other          | 2         | 2.41%   |
| 2 x AMD        | 2         | 2.41%   |
| AMD + Nvidia   | 2         | 2.41%   |
| 2 x Nvidia     | 1         | 1.2%    |
| 1 x SiS        | 1         | 1.2%    |
| AMD + ASPEED   | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 66.27%  |
| Proprietary | 25        | 30.12%  |
| Unknown     | 3         | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 52.33%  |
| 1.01-2.0   | 11        | 12.79%  |
| 0.01-0.5   | 9         | 10.47%  |
| 3.01-4.0   | 8         | 9.3%    |
| 0.51-1.0   | 6         | 6.98%   |
| 5.01-6.0   | 2         | 2.33%   |
| 2.01-3.0   | 2         | 2.33%   |
| 8.01-16.0  | 2         | 2.33%   |
| 7.01-8.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 12        | 13.64%  |
| LG Display           | 10        | 11.36%  |
| Chimei Innolux       | 10        | 11.36%  |
| Samsung Electronics  | 9         | 10.23%  |
| BOE                  | 7         | 7.95%   |
| Hewlett-Packard      | 5         | 5.68%   |
| Dell                 | 5         | 5.68%   |
| Philips              | 4         | 4.55%   |
| Acer                 | 3         | 3.41%   |
| PANDA                | 2         | 2.27%   |
| Lenovo               | 2         | 2.27%   |
| Goldstar             | 2         | 2.27%   |
| BenQ                 | 2         | 2.27%   |
| AOC                  | 2         | 2.27%   |
| Ancor Communications | 2         | 2.27%   |
| Unknown              | 1         | 1.14%   |
| STD                  | 1         | 1.14%   |
| Sceptre Tech         | 1         | 1.14%   |
| Sceptre              | 1         | 1.14%   |
| ONN                  | 1         | 1.14%   |
| MSI                  | 1         | 1.14%   |
| LG Philips           | 1         | 1.14%   |
| FUN                  | 1         | 1.14%   |
| Fujitsu Siemens      | 1         | 1.14%   |
| CHR                  | 1         | 1.14%   |
| Apple                | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 3.23%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 2.15%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 1.08%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                         | 1         | 1.08%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 1         | 1.08%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 1.08%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 1.08%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 480x270mm 21.7-inch  | 1         | 1.08%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch  | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 1.08%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 1.08%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 1.08%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 1.08%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1.08%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 1.08%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 1.08%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 1.08%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 1.08%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.08%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 1.08%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 1.08%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 1.08%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 1.08%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch           | 1         | 1.08%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 1.08%   |
| Lenovo LEN-V510Z-B LEN1201 1920x1080 509x286mm 23.0-inch              | 1         | 1.08%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 1.08%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1         | 1.08%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1         | 1.08%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 1.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.08%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1         | 1.08%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1         | 1.08%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1         | 1.08%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1         | 1.08%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1         | 1.08%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1         | 1.08%   |
| Dell U2415 DELA0B8 1920x1080 520x320mm 24.0-inch                      | 1         | 1.08%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 1.08%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 1.08%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                 | 1         | 1.08%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 340x190mm 15.3-inch       | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 44.83%  |
| 1366x768 (WXGA)    | 19        | 21.84%  |
| 2560x1440 (QHD)    | 4         | 4.6%    |
| 1920x1200 (WUXGA)  | 4         | 4.6%    |
| 1680x1050 (WSXGA+) | 4         | 4.6%    |
| 3840x2160 (4K)     | 3         | 3.45%   |
| 1600x900 (HD+)     | 2         | 2.3%    |
| 1280x800 (WXGA)    | 2         | 2.3%    |
| Unknown            | 2         | 2.3%    |
| 7680x1080          | 1         | 1.15%   |
| 3840x1600          | 1         | 1.15%   |
| 3840x1080          | 1         | 1.15%   |
| 3440x1440          | 1         | 1.15%   |
| 2160x1440          | 1         | 1.15%   |
| 1360x768           | 1         | 1.15%   |
| 1280x1024 (SXGA)   | 1         | 1.15%   |
| 1024x600           | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 28.09%  |
| Unknown | 10        | 11.24%  |
| 24      | 8         | 8.99%   |
| 14      | 7         | 7.87%   |
| 13      | 7         | 7.87%   |
| 21      | 5         | 5.62%   |
| 27      | 4         | 4.49%   |
| 23      | 4         | 4.49%   |
| 22      | 4         | 4.49%   |
| 17      | 2         | 2.25%   |
| 12      | 2         | 2.25%   |
| 11      | 2         | 2.25%   |
| 40      | 1         | 1.12%   |
| 39      | 1         | 1.12%   |
| 37      | 1         | 1.12%   |
| 34      | 1         | 1.12%   |
| 33      | 1         | 1.12%   |
| 31      | 1         | 1.12%   |
| 25      | 1         | 1.12%   |
| 18      | 1         | 1.12%   |
| 8       | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 40.91%  |
| 501-600     | 16        | 18.18%  |
| 401-500     | 10        | 11.36%  |
| Unknown     | 10        | 11.36%  |
| 201-300     | 8         | 9.09%   |
| 801-900     | 3         | 3.41%   |
| 701-800     | 2         | 2.27%   |
| 601-700     | 1         | 1.14%   |
| 351-400     | 1         | 1.14%   |
| 101-200     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 72.29%  |
| 16/10   | 10        | 12.05%  |
| Unknown | 9         | 10.84%  |
| 21/9    | 2         | 2.41%   |
| 5/4     | 1         | 1.2%    |
| 3/2     | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 28.09%  |
| 201-250        | 15        | 16.85%  |
| 81-90          | 12        | 13.48%  |
| Unknown        | 10        | 11.24%  |
| 251-300        | 5         | 5.62%   |
| 301-350        | 4         | 4.49%   |
| 71-80          | 3         | 3.37%   |
| 351-500        | 3         | 3.37%   |
| 501-1000       | 3         | 3.37%   |
| 61-70          | 2         | 2.25%   |
| 51-60          | 2         | 2.25%   |
| 141-150        | 2         | 2.25%   |
| 1-40           | 1         | 1.12%   |
| 151-200        | 1         | 1.12%   |
| 131-140        | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 27        | 30.34%  |
| 101-120       | 23        | 25.84%  |
| 121-160       | 22        | 24.72%  |
| Unknown       | 10        | 11.24%  |
| 161-240       | 6         | 6.74%   |
| More than 240 | 1         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 78.31%  |
| 2     | 16        | 19.28%  |
| 0     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 39.47%  |
| Intel                            | 30        | 26.32%  |
| Qualcomm Atheros                 | 14        | 12.28%  |
| Broadcom                         | 7         | 6.14%   |
| TP-Link                          | 2         | 1.75%   |
| Ralink Technology                | 2         | 1.75%   |
| Qualcomm Atheros Communications  | 2         | 1.75%   |
| Cypress Semiconductor            | 2         | 1.75%   |
| Tenda                            | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| Sierra Wireless                  | 1         | 0.88%   |
| Ralink                           | 1         | 0.88%   |
| Nvidia                           | 1         | 0.88%   |
| MediaTek                         | 1         | 0.88%   |
| DisplayLink                      | 1         | 0.88%   |
| Broadcom Limited                 | 1         | 0.88%   |
| ASIX Electronics                 | 1         | 0.88%   |
| Apple                            | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 26.12%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 4.48%   |
| Intel Wireless 8265 / 8275                                        | 6         | 4.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.49%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.49%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.49%   |
| Cypress K38231_03                                                 | 2         | 1.49%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.75%   |
| Tenda U12                                                         | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.75%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.75%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.75%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.75%   |
| MediaTek WP5 Pro                                                  | 1         | 0.75%   |
| Intel Wireless-AC 9260                                            | 1         | 0.75%   |
| Intel Wireless 8260                                               | 1         | 0.75%   |
| Intel Wireless 7260                                               | 1         | 0.75%   |
| Intel WiFi Link 5100                                              | 1         | 0.75%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.75%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.75%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.75%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.75%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 0.75%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 38.98%  |
| Realtek Semiconductor           | 12        | 20.34%  |
| Qualcomm Atheros                | 12        | 20.34%  |
| Broadcom                        | 3         | 5.08%   |
| Ralink Technology               | 2         | 3.39%   |
| Qualcomm Atheros Communications | 2         | 3.39%   |
| TP-Link                         | 1         | 1.69%   |
| Tenda                           | 1         | 1.69%   |
| Sierra Wireless                 | 1         | 1.69%   |
| Ralink                          | 1         | 1.69%   |
| Broadcom Limited                | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 8         | 13.56%  |
| Intel Wireless 8265 / 8275                                 | 6         | 10.17%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 6.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 6.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 3         | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 3         | 5.08%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 3         | 5.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 3.39%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 3.39%   |
| Ralink MT7601U Wireless Adapter                            | 2         | 3.39%   |
| Qualcomm Atheros AR9271 802.11n                            | 2         | 3.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.69%   |
| Tenda U12                                                  | 1         | 1.69%   |
| Sierra Wireless EM7305 Modem                               | 1         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 1.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter   | 1         | 1.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.69%   |
| Intel Wireless-AC 9260                                     | 1         | 1.69%   |
| Intel Wireless 8260                                        | 1         | 1.69%   |
| Intel Wireless 7260                                        | 1         | 1.69%   |
| Intel WiFi Link 5100                                       | 1         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 1.69%   |
| Broadcom BCM4311 802.11b/g WLAN                            | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 43        | 57.33%  |
| Intel                            | 15        | 20%     |
| Broadcom                         | 5         | 6.67%   |
| Qualcomm Atheros                 | 3         | 4%      |
| Cypress Semiconductor            | 2         | 2.67%   |
| TP-Link                          | 1         | 1.33%   |
| Silicon Integrated Systems [SiS] | 1         | 1.33%   |
| Nvidia                           | 1         | 1.33%   |
| MediaTek                         | 1         | 1.33%   |
| DisplayLink                      | 1         | 1.33%   |
| ASIX Electronics                 | 1         | 1.33%   |
| Apple                            | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 46.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 8%      |
| Intel Ethernet Connection (2) I219-V                              | 3         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.67%   |
| Cypress K38231_03                                                 | 2         | 2.67%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 1.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.33%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.33%   |
| MediaTek WP5 Pro                                                  | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.33%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 1.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.33%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.33%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.33%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.33%   |
| Apple iPad 4/Mini1                                                | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 72        | 55.81%  |
| WiFi     | 57        | 44.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 60        | 52.63%  |
| WiFi     | 54        | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 46.34%  |
| 1     | 38        | 46.34%  |
| 0     | 4         | 4.88%   |
| 3     | 2         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 89.29%  |
| Yes  | 9         | 10.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 42%     |
| Realtek Semiconductor           | 7         | 14%     |
| Lite-On Technology              | 5         | 10%     |
| Cambridge Silicon Radio         | 5         | 10%     |
| Qualcomm Atheros Communications | 3         | 6%      |
| IMC Networks                    | 3         | 6%      |
| Broadcom                        | 3         | 6%      |
| Foxconn / Hon Hai               | 2         | 4%      |
| Dell                            | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 16%     |
| Intel AX200 Bluetooth                               | 8         | 16%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 10%     |
| Realtek Bluetooth Radio                             | 4         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 4%      |
| IMC Networks Bluetooth Radio                        | 2         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2%      |
| Intel AX201 Bluetooth                               | 1         | 2%      |
| IMC Networks Bluetooth Device                       | 1         | 2%      |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2%      |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2%      |
| Dell Wireless 365 Bluetooth                         | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 38.94%  |
| AMD                              | 33        | 29.2%   |
| Nvidia                           | 20        | 17.7%   |
| Logitech                         | 3         | 2.65%   |
| C-Media Electronics              | 3         | 2.65%   |
| Texas Instruments                | 2         | 1.77%   |
| JMTek                            | 2         | 1.77%   |
| VIA Technologies                 | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| SAVITECH                         | 1         | 0.88%   |
| Elgato Systems                   | 1         | 0.88%   |
| Creative Technology              | 1         | 0.88%   |
| Cambridge Audio                  | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 7.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 9         | 6.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 4.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 3.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.52%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 2.82%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.11%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.11%   |
| AMD High Definition Audio Controller                                       | 3         | 2.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.11%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 1.41%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.41%   |
| JMTek USB PnP Audio Device                                                 | 2         | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.41%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.41%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.7%    |
| SAVITECH SA9023 audio controller                                           | 1         | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.7%    |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.7%    |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.7%    |
| Logitech G633 Gaming Headset                                               | 1         | 0.7%    |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.7%    |
| Logitech Blue Snowball                                                     | 1         | 0.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 1         | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.7%    |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1         | 0.7%    |
| Elgato Systems Elgato Wave:3                                               | 1         | 0.7%    |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 0.7%    |
| Cambridge Audio USB Audio 2.0                                              | 1         | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 0.7%    |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 0.7%    |
| C-Media Electronics Antlion USB adapter                                    | 1         | 0.7%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1         | 0.7%    |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1         | 0.7%    |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1         | 0.7%    |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 22.73%  |
| Samsung Electronics | 14        | 21.21%  |
| Micron Technology   | 7         | 10.61%  |
| Kingston            | 5         | 7.58%   |
| G.Skill             | 5         | 7.58%   |
| Corsair             | 5         | 7.58%   |
| A-DATA Technology   | 5         | 7.58%   |
| Unknown             | 4         | 6.06%   |
| Crucial             | 2         | 3.03%   |
| Transcend           | 1         | 1.52%   |
| Ramaxel Technology  | 1         | 1.52%   |
| Patriot             | 1         | 1.52%   |
| Elpida              | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 2.7%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.7%    |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.35%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.35%   |
| Transcend RAM TS512MSK64W6H 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.35%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.35%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.35%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.35%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.35%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.35%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s              | 1         | 1.35%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s           | 1         | 1.35%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.35%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.35%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s                | 1         | 1.35%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s         | 1         | 1.35%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.35%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.35%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s             | 1         | 1.35%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.35%   |
| Kingston RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 1.35%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 1.35%   |
| Kingston RAM ACR26D4S9S1KA-4 4GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Kingston RAM 99U5474-016.A00LF 4096MB DIMM DDR3 1333MT/s         | 1         | 1.35%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 1.35%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 1         | 1.35%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 1         | 1.35%   |
| G.Skill RAM F4-2800C17-8GIS 8192MB DIMM DDR4 2800MT/s            | 1         | 1.35%   |
| G.Skill RAM F4-2666C18-4GRS 4096MB SODIMM DDR4 2400MT/s          | 1         | 1.35%   |
| G.Skill RAM F3-10666CL7-2GBRH 2048MB DIMM DDR3 1333MT/s          | 1         | 1.35%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 1.35%   |
| Elpida RAM BA92-09550A 2GB SODIMM DDR3 1600MT/s                  | 1         | 1.35%   |
| Crucial RAM CT8G4DFS824A.M8FE 8192MB DIMM DDR4 2933MT/s          | 1         | 1.35%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s             | 1         | 1.35%   |
| Crucial RAM CT16G4DFD824A.M16FJ 16384MB DIMM DDR4 2400MT/s       | 1         | 1.35%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s          | 1         | 1.35%   |
| Crucial RAM BL25664TN1608.16FF 2048MB DIMM DDR3 1333MT/s         | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 30        | 52.63%  |
| DDR3    | 20        | 35.09%  |
| LPDDR4  | 2         | 3.51%   |
| LPDDR3  | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| DDR2    | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 62.5%   |
| DIMM         | 19        | 33.93%  |
| Row Of Chips | 2         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 42.62%  |
| 4096  | 21        | 34.43%  |
| 16384 | 6         | 9.84%   |
| 2048  | 5         | 8.2%    |
| 1024  | 2         | 3.28%   |
| 512   | 1         | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 13        | 20.63%  |
| 2667  | 10        | 15.87%  |
| 3200  | 8         | 12.7%   |
| 2400  | 8         | 12.7%   |
| 1333  | 6         | 9.52%   |
| 3600  | 3         | 4.76%   |
| 2133  | 3         | 4.76%   |
| 1334  | 3         | 4.76%   |
| 3000  | 2         | 3.17%   |
| 1867  | 2         | 3.17%   |
| 3733  | 1         | 1.59%   |
| 2933  | 1         | 1.59%   |
| 2800  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |
| 533   | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 15        | 25.86%  |
| IMC Networks                           | 9         | 15.52%  |
| Microdia                               | 8         | 13.79%  |
| Realtek Semiconductor                  | 5         | 8.62%   |
| Logitech                               | 5         | 8.62%   |
| Quanta                                 | 4         | 6.9%    |
| Acer                                   | 4         | 6.9%    |
| Sunplus Innovation Technology          | 3         | 5.17%   |
| Silicon Motion                         | 1         | 1.72%   |
| Microsoft                              | 1         | 1.72%   |
| MacroSilicon                           | 1         | 1.72%   |
| MACROSIL                               | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 6.67%   |
| Chicony Integrated Camera                     | 3         | 5%      |
| Sunplus Integrated_Webcam_HD                  | 2         | 3.33%   |
| Quanta HD User Facing                         | 2         | 3.33%   |
| Microdia HP Integrated Webcam                 | 2         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 3.33%   |
| Chicony HD WebCam                             | 2         | 3.33%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.67%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.67%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.67%   |
| Realtek USB Camera                            | 1         | 1.67%   |
| Realtek Integrated Webcam HD                  | 1         | 1.67%   |
| Realtek HD WebCam                             | 1         | 1.67%   |
| Realtek FULL HD 1080P Webcam                  | 1         | 1.67%   |
| Quanta VGA WebCam                             | 1         | 1.67%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.67%   |
| Microsoft LifeCam HD-3000                     | 1         | 1.67%   |
| Microdia USB Live camera                      | 1         | 1.67%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.67%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.67%   |
| Microdia HD Webcam USB                        | 1         | 1.67%   |
| Microdia Camera                               | 1         | 1.67%   |
| MacroSilicon USB Video                        | 1         | 1.67%   |
| MACROSIL AV TO USB2.0                         | 1         | 1.67%   |
| Logitech Webcam C930e                         | 1         | 1.67%   |
| Logitech Webcam C270                          | 1         | 1.67%   |
| Logitech HD Webcam C615                       | 1         | 1.67%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.67%   |
| Logitech C505 HD Webcam                       | 1         | 1.67%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.67%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.67%   |
| IMC Networks EasyCamera                       | 1         | 1.67%   |
| Chicony WebCam                                | 1         | 1.67%   |
| Chicony USB 5M WebCam                         | 1         | 1.67%   |
| Chicony USB 2.0 Camera                        | 1         | 1.67%   |
| Chicony thinkpad t430s camera                 | 1         | 1.67%   |
| Chicony Lenovo EasyCamera                     | 1         | 1.67%   |
| Chicony Integrated IR Camera                  | 1         | 1.67%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 1.67%   |
| Chicony HP TrueVision HD Camera               | 1         | 1.67%   |
| Chicony HP 720p HD Monitor Webcam             | 1         | 1.67%   |
| Chicony HD WebCam (Acer)                      | 1         | 1.67%   |
| Chicony HD User Facing                        | 1         | 1.67%   |
| Chicony EasyCamera                            | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 1.67%   |
| Acer ThinkPad P50 Integrated Camera           | 1         | 1.67%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.67%   |
| Acer OrbiCam                                  | 1         | 1.67%   |
| Acer Lenovo EasyCamera                        | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 5         | 83.33%  |
| Validity Sensors | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Synaptics  WBDI                                   | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 79.52%  |
| 1     | 11        | 13.25%  |
| 2     | 4         | 4.82%   |
| 3     | 2         | 2.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 25%     |
| Graphics card         | 5         | 20.83%  |
| Net/wireless          | 4         | 16.67%  |
| Chipcard              | 3         | 12.5%   |
| Sound                 | 2         | 8.33%   |
| Camera                | 2         | 8.33%   |
| Net/ethernet          | 1         | 4.17%   |
| Multimedia controller | 1         | 4.17%   |

