Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 130

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| ASUSTek       | Q325UAR                     | Convertible | [fc83e5d0b3](https://linux-hardware.org/?probe=fc83e5d0b3) | Feb 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | Notebook    | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | Notebook    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 55        | 55.56%  |
| Void Linux         | 44        | 44.44%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 96        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.13.19_1           | 7         | 6.73%   |
| 5.8.18_1            | 5         | 4.81%   |
| 5.3.9_1             | 4         | 3.85%   |
| 5.10.17_1           | 4         | 3.85%   |
| 5.8.12_1            | 3         | 2.88%   |
| 5.13.13_1           | 3         | 2.88%   |
| 5.12.10_1           | 3         | 2.88%   |
| 5.9.14_1            | 2         | 1.92%   |
| 5.4.24_1            | 2         | 1.92%   |
| 5.4.13_2            | 2         | 1.92%   |
| 5.15.22_1           | 2         | 1.92%   |
| 5.15.16_1           | 2         | 1.92%   |
| 5.13.15_1           | 2         | 1.92%   |
| 5.13.10_1           | 2         | 1.92%   |
| 5.12.14_1           | 2         | 1.92%   |
| 5.11.9_1            | 2         | 1.92%   |
| 5.10.14_1           | 2         | 1.92%   |
| 5.9.16_1            | 1         | 0.96%   |
| 5.9.0-rc8_2         | 1         | 0.96%   |
| 5.8.9_1             | 1         | 0.96%   |
| 5.8.8_1             | 1         | 0.96%   |
| 5.8.7_1             | 1         | 0.96%   |
| 5.8.6_1             | 1         | 0.96%   |
| 5.8.5_1             | 1         | 0.96%   |
| 5.8.16_1            | 1         | 0.96%   |
| 5.8.14_1            | 1         | 0.96%   |
| 5.8.12_2            | 1         | 0.96%   |
| 5.8.11_1            | 1         | 0.96%   |
| 5.8.10_1            | 1         | 0.96%   |
| 5.7.16_1            | 1         | 0.96%   |
| 5.6.14_1            | 1         | 0.96%   |
| 5.4.35_1            | 1         | 0.96%   |
| 5.4.21_1            | 1         | 0.96%   |
| 5.4.15_1            | 1         | 0.96%   |
| 5.3.16_1            | 1         | 0.96%   |
| 5.2.13_1            | 1         | 0.96%   |
| 5.15.6_1            | 1         | 0.96%   |
| 5.15.30_1           | 1         | 0.96%   |
| 5.15.28_1           | 1         | 0.96%   |
| 5.15.26_1           | 1         | 0.96%   |
| 5.15.24_1           | 1         | 0.96%   |
| 5.15.17_1           | 1         | 0.96%   |
| 5.15.14_1           | 1         | 0.96%   |
| 5.15.12_1           | 1         | 0.96%   |
| 5.15.11_1           | 1         | 0.96%   |
| 5.14.0_1            | 1         | 0.96%   |
| 5.13.18_1           | 1         | 0.96%   |
| 5.13.12_1           | 1         | 0.96%   |
| 5.12.7_1            | 1         | 0.96%   |
| 5.12.6              | 1         | 0.96%   |
| 5.12.3-tkg-MuQSS_22 | 1         | 0.96%   |
| 5.12.19_1           | 1         | 0.96%   |
| 5.11.18_1           | 1         | 0.96%   |
| 5.11.16_1           | 1         | 0.96%   |
| 5.11.11_1           | 1         | 0.96%   |
| 5.10.9_1            | 1         | 0.96%   |
| 5.10.8_1            | 1         | 0.96%   |
| 5.10.88_1           | 1         | 0.96%   |
| 5.10.80_1           | 1         | 0.96%   |
| 5.10.7_1            | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 6.73%   |
| 5.8.18  | 5         | 4.81%   |
| 5.8.12  | 4         | 3.85%   |
| 5.3.9   | 4         | 3.85%   |
| 5.10.17 | 4         | 3.85%   |
| 5.13.13 | 3         | 2.88%   |
| 5.12.10 | 3         | 2.88%   |
| 5.9.14  | 2         | 1.92%   |
| 5.4.24  | 2         | 1.92%   |
| 5.4.13  | 2         | 1.92%   |
| 5.15.22 | 2         | 1.92%   |
| 5.15.16 | 2         | 1.92%   |
| 5.13.15 | 2         | 1.92%   |
| 5.13.10 | 2         | 1.92%   |
| 5.12.14 | 2         | 1.92%   |
| 5.11.9  | 2         | 1.92%   |
| 5.10.14 | 2         | 1.92%   |
| 5.9.16  | 1         | 0.96%   |
| 5.9.0   | 1         | 0.96%   |
| 5.8.9   | 1         | 0.96%   |
| 5.8.8   | 1         | 0.96%   |
| 5.8.7   | 1         | 0.96%   |
| 5.8.6   | 1         | 0.96%   |
| 5.8.5   | 1         | 0.96%   |
| 5.8.16  | 1         | 0.96%   |
| 5.8.14  | 1         | 0.96%   |
| 5.8.11  | 1         | 0.96%   |
| 5.8.10  | 1         | 0.96%   |
| 5.7.16  | 1         | 0.96%   |
| 5.6.14  | 1         | 0.96%   |
| 5.4.35  | 1         | 0.96%   |
| 5.4.21  | 1         | 0.96%   |
| 5.4.15  | 1         | 0.96%   |
| 5.3.16  | 1         | 0.96%   |
| 5.2.13  | 1         | 0.96%   |
| 5.15.6  | 1         | 0.96%   |
| 5.15.30 | 1         | 0.96%   |
| 5.15.28 | 1         | 0.96%   |
| 5.15.26 | 1         | 0.96%   |
| 5.15.24 | 1         | 0.96%   |
| 5.15.17 | 1         | 0.96%   |
| 5.15.14 | 1         | 0.96%   |
| 5.15.12 | 1         | 0.96%   |
| 5.15.11 | 1         | 0.96%   |
| 5.14.0  | 1         | 0.96%   |
| 5.13.18 | 1         | 0.96%   |
| 5.13.12 | 1         | 0.96%   |
| 5.12.7  | 1         | 0.96%   |
| 5.12.6  | 1         | 0.96%   |
| 5.12.3  | 1         | 0.96%   |
| 5.12.19 | 1         | 0.96%   |
| 5.11.18 | 1         | 0.96%   |
| 5.11.16 | 1         | 0.96%   |
| 5.11.11 | 1         | 0.96%   |
| 5.10.9  | 1         | 0.96%   |
| 5.10.88 | 1         | 0.96%   |
| 5.10.80 | 1         | 0.96%   |
| 5.10.8  | 1         | 0.96%   |
| 5.10.7  | 1         | 0.96%   |
| 5.10.67 | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 18        | 17.48%  |
| 5.13    | 16        | 15.53%  |
| 5.10    | 15        | 14.56%  |
| 5.15    | 13        | 12.62%  |
| 5.12    | 9         | 8.74%   |
| 5.4     | 7         | 6.8%    |
| 5.3     | 5         | 4.85%   |
| 5.11    | 5         | 4.85%   |
| 5.9     | 4         | 3.88%   |
| 4.19    | 4         | 3.88%   |
| 5.7     | 1         | 0.97%   |
| 5.6     | 1         | 0.97%   |
| 5.2     | 1         | 0.97%   |
| 5.14    | 1         | 0.97%   |
| 5.1     | 1         | 0.97%   |
| 4.4     | 1         | 0.97%   |
| 4.14    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 89        | 92.71%  |
| i686    | 4         | 4.17%   |
| aarch64 | 2         | 2.08%   |
| ppc64le | 1         | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 48%     |
| XFCE       | 11        | 11%     |
| KDE        | 10        | 10%     |
| MATE       | 6         | 6%      |
| i3         | 5         | 5%      |
| GNOME      | 5         | 5%      |
| X-Cinnamon | 3         | 3%      |
| KDE5       | 3         | 3%      |
| bspwm      | 3         | 3%      |
| Lumina     | 2         | 2%      |
| awesome    | 2         | 2%      |
| sway       | 1         | 1%      |
| river      | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 67        | 69.07%  |
| Wayland | 12        | 12.37%  |
| Tty     | 12        | 12.37%  |
| Unknown | 6         | 6.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 97.94%  |
| SDDM    | 1         | 1.03%   |
| LXDM    | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 50        | 50%     |
| Unknown | 16        | 16%     |
| en_GB   | 7         | 7%      |
| en_DK   | 6         | 6%      |
| ru_RU   | 3         | 3%      |
| de_DE   | 3         | 3%      |
| pt_BR   | 2         | 2%      |
| fr_FR   | 2         | 2%      |
| en_AU   | 2         | 2%      |
| ru_UA   | 1         | 1%      |
| nb_NO   | 1         | 1%      |
| es_ES   | 1         | 1%      |
| es_DO   | 1         | 1%      |
| en_NZ   | 1         | 1%      |
| en_CA   | 1         | 1%      |
| el_GR   | 1         | 1%      |
| cs_CZ   | 1         | 1%      |
| bg_BG   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 49        | 50%     |
| EFI  | 49        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 63.92%  |
| Btrfs   | 19        | 19.59%  |
| Zfs     | 5         | 5.15%   |
| Xfs     | 5         | 5.15%   |
| Unknown | 4         | 4.12%   |
| F2fs    | 1         | 1.03%   |
| Ext3    | 1         | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 52        | 53.06%  |
| Unknown | 32        | 32.65%  |
| MBR     | 14        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 89.58%  |
| Yes       | 10        | 10.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 81.25%  |
| Yes       | 18        | 18.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 22        | 22.92%  |
| Lenovo              | 14        | 14.58%  |
| Acer                | 12        | 12.5%   |
| Hewlett-Packard     | 9         | 9.38%   |
| Dell                | 8         | 8.33%   |
| MSI                 | 7         | 7.29%   |
| ASRock              | 6         | 6.25%   |
| Gigabyte Technology | 4         | 4.17%   |
| Unknown             | 3         | 3.13%   |
| Samsung Electronics | 1         | 1.04%   |
| Positivo            | 1         | 1.04%   |
| Pine Microsystems   | 1         | 1.04%   |
| Notebook            | 1         | 1.04%   |
| HUAWEI              | 1         | 1.04%   |
| Google              | 1         | 1.04%   |
| Getac               | 1         | 1.04%   |
| Framework           | 1         | 1.04%   |
| Digibras            | 1         | 1.04%   |
| Chuwi               | 1         | 1.04%   |
| Apple               | 1         | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 3.13%   |
| ASUS PRIME Z390-P                      | 2         | 2.08%   |
| Acer Swift SF314-42                    | 2         | 2.08%   |
| Samsung 275E4E/275E5E                  | 1         | 1.04%   |
| Positivo Mobile                        | 1         | 1.04%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 1.04%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 1.04%   |
| MSI MS-7D14                            | 1         | 1.04%   |
| MSI MS-7C92                            | 1         | 1.04%   |
| MSI MS-7C52                            | 1         | 1.04%   |
| MSI MS-7C02                            | 1         | 1.04%   |
| MSI MS-7A68                            | 1         | 1.04%   |
| MSI MS-7A39                            | 1         | 1.04%   |
| MSI Bravo 15 A4DDR                     | 1         | 1.04%   |
| Lenovo Yoga 720-15IKB 80X7             | 1         | 1.04%   |
| Lenovo ThinkPad X260 20F5S08Q00        | 1         | 1.04%   |
| Lenovo ThinkPad X240 20AMA34HMN        | 1         | 1.04%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS | 1         | 1.04%   |
| Lenovo ThinkPad T480 20L6SA5Q00        | 1         | 1.04%   |
| Lenovo ThinkPad T460 20FMS0WN00        | 1         | 1.04%   |
| Lenovo ThinkPad T430 2349PS3           | 1         | 1.04%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW  | 1         | 1.04%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00  | 1         | 1.04%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200   | 1         | 1.04%   |
| Lenovo ThinkPad E595 20NFCTO1WW        | 1         | 1.04%   |
| Lenovo IdeaPad Z570 10246ZG            | 1         | 1.04%   |
| Lenovo IdeaPad 710S-13IKB 80VQ         | 1         | 1.04%   |
| Lenovo G50-45 80E3                     | 1         | 1.04%   |
| HUAWEI HN-WX9X                         | 1         | 1.04%   |
| HP Z2 Mini G3 Workstation              | 1         | 1.04%   |
| HP Stream 7 Tablet                     | 1         | 1.04%   |
| HP Pavilion Notebook                   | 1         | 1.04%   |
| HP Notebook                            | 1         | 1.04%   |
| HP Laptop 15-bw0xx                     | 1         | 1.04%   |
| HP Laptop 14-dk0xxx                    | 1         | 1.04%   |
| HP Laptop 14-bs0xx                     | 1         | 1.04%   |
| HP ENVY 6                              | 1         | 1.04%   |
| HP 15                                  | 1         | 1.04%   |
| Google Chell                           | 1         | 1.04%   |
| Gigabyte H310M M.2 2.0                 | 1         | 1.04%   |
| Gigabyte GA-78LMT-S2                   | 1         | 1.04%   |
| Gigabyte B550M AORUS PRO-P             | 1         | 1.04%   |
| Gigabyte B450M DS3H                    | 1         | 1.04%   |
| Getac V110                             | 1         | 1.04%   |
| Framework Laptop                       | 1         | 1.04%   |
| Digibras NH4CU03                       | 1         | 1.04%   |
| Dell Precision 3530                    | 1         | 1.04%   |
| Dell OptiPlex GX520                    | 1         | 1.04%   |
| Dell OptiPlex 780                      | 1         | 1.04%   |
| Dell Latitude E4300                    | 1         | 1.04%   |
| Dell Inspiron 5555                     | 1         | 1.04%   |
| Dell Inspiron 1501                     | 1         | 1.04%   |
| Dell Inspiron 11 - 3148                | 1         | 1.04%   |
| Dell G3 3579                           | 1         | 1.04%   |
| Chuwi GemiBook Pro                     | 1         | 1.04%   |
| ASUS X751LD                            | 1         | 1.04%   |
| ASUS X555UJ                            | 1         | 1.04%   |
| ASUS X510UAR                           | 1         | 1.04%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL | 1         | 1.04%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 1         | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 10        | 10.42%  |
| Acer Aspire              | 7         | 7.29%   |
| ASUS PRIME               | 5         | 5.21%   |
| ASUS VivoBook            | 4         | 4.17%   |
| HP Laptop                | 3         | 3.13%   |
| Dell Inspiron            | 3         | 3.13%   |
| Unknown                  | 3         | 3.13%   |
| Lenovo IdeaPad           | 2         | 2.08%   |
| Dell OptiPlex            | 2         | 2.08%   |
| Acer Swift               | 2         | 2.08%   |
| Samsung 275E4E           | 1         | 1.04%   |
| Positivo Mobile          | 1         | 1.04%   |
| Pine Microsystems Pine64 | 1         | 1.04%   |
| Notebook NV4XMB          | 1         | 1.04%   |
| MSI MS-7D14              | 1         | 1.04%   |
| MSI MS-7C92              | 1         | 1.04%   |
| MSI MS-7C52              | 1         | 1.04%   |
| MSI MS-7C02              | 1         | 1.04%   |
| MSI MS-7A68              | 1         | 1.04%   |
| MSI MS-7A39              | 1         | 1.04%   |
| MSI Bravo                | 1         | 1.04%   |
| Lenovo Yoga              | 1         | 1.04%   |
| Lenovo G50-45            | 1         | 1.04%   |
| HUAWEI HN-WX9X           | 1         | 1.04%   |
| HP Z2                    | 1         | 1.04%   |
| HP Stream                | 1         | 1.04%   |
| HP Pavilion              | 1         | 1.04%   |
| HP Notebook              | 1         | 1.04%   |
| HP ENVY                  | 1         | 1.04%   |
| HP 15                    | 1         | 1.04%   |
| Google Chell             | 1         | 1.04%   |
| Gigabyte H310M           | 1         | 1.04%   |
| Gigabyte GA-78LMT-S2     | 1         | 1.04%   |
| Gigabyte B550M           | 1         | 1.04%   |
| Gigabyte B450M           | 1         | 1.04%   |
| Getac V110               | 1         | 1.04%   |
| Framework Laptop         | 1         | 1.04%   |
| Digibras NH4CU03         | 1         | 1.04%   |
| Dell Precision           | 1         | 1.04%   |
| Dell Latitude            | 1         | 1.04%   |
| Dell G3                  | 1         | 1.04%   |
| Chuwi GemiBook           | 1         | 1.04%   |
| ASUS X751LD              | 1         | 1.04%   |
| ASUS X555UJ              | 1         | 1.04%   |
| ASUS X510UAR             | 1         | 1.04%   |
| ASUS TUF                 | 1         | 1.04%   |
| ASUS ROG                 | 1         | 1.04%   |
| ASUS Q325UAR             | 1         | 1.04%   |
| ASUS P8Z77-V             | 1         | 1.04%   |
| ASUS P8H67-V             | 1         | 1.04%   |
| ASUS M5A78L-M            | 1         | 1.04%   |
| ASUS M4A89GTD-PRO        | 1         | 1.04%   |
| ASUS H110M-PLUS          | 1         | 1.04%   |
| ASUS B150M               | 1         | 1.04%   |
| ASUS ASUS                | 1         | 1.04%   |
| ASRock N68-S3            | 1         | 1.04%   |
| ASRock J4005B-ITX        | 1         | 1.04%   |
| ASRock H61M-VG4          | 1         | 1.04%   |
| ASRock B450              | 1         | 1.04%   |
| ASRock AB350M            | 1         | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 14        | 14.58%  |
| 2020    | 13        | 13.54%  |
| 2018    | 13        | 13.54%  |
| 2017    | 10        | 10.42%  |
| 2016    | 9         | 9.38%   |
| 2014    | 6         | 6.25%   |
| 2013    | 6         | 6.25%   |
| 2012    | 6         | 6.25%   |
| 2011    | 5         | 5.21%   |
| 2015    | 3         | 3.13%   |
| Unknown | 3         | 3.13%   |
| 2010    | 2         | 2.08%   |
| 2008    | 2         | 2.08%   |
| 2006    | 2         | 2.08%   |
| 2021    | 1         | 1.04%   |
| 2009    | 1         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 59        | 61.46%  |
| Desktop     | 32        | 33.33%  |
| Convertible | 3         | 3.13%   |
| Tablet      | 1         | 1.04%   |
| Mini pc     | 1         | 1.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 96        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 23.71%  |
| 8.01-16.0   | 20        | 20.62%  |
| 16.01-24.0  | 19        | 19.59%  |
| 3.01-4.0    | 18        | 18.56%  |
| 32.01-64.0  | 8         | 8.25%   |
| 1.01-2.0    | 4         | 4.12%   |
| 64.01-256.0 | 2         | 2.06%   |
| 24.01-32.0  | 1         | 1.03%   |
| 2.01-3.0    | 1         | 1.03%   |
| 0.51-1.0    | 1         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 30        | 28.85%  |
| 2.01-3.0   | 26        | 25%     |
| 0.51-1.0   | 17        | 16.35%  |
| 4.01-8.0   | 11        | 10.58%  |
| 3.01-4.0   | 9         | 8.65%   |
| 8.01-16.0  | 6         | 5.77%   |
| 16.01-24.0 | 3         | 2.88%   |
| 0.01-0.5   | 2         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 63.54%  |
| 2      | 21        | 21.88%  |
| 3      | 13        | 13.54%  |
| 4      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 73.96%  |
| Yes       | 25        | 26.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 84.38%  |
| No        | 15        | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 72.92%  |
| No        | 26        | 27.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 61.86%  |
| No        | 37        | 38.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 21        | 21.88%  |
| Germany            | 9         | 9.38%   |
| India              | 8         | 8.33%   |
| Brazil             | 7         | 7.29%   |
| Russia             | 6         | 6.25%   |
| Denmark            | 5         | 5.21%   |
| Ukraine            | 4         | 4.17%   |
| UK                 | 4         | 4.17%   |
| Switzerland        | 3         | 3.13%   |
| France             | 3         | 3.13%   |
| Czechia            | 3         | 3.13%   |
| Bulgaria           | 3         | 3.13%   |
| Turkey             | 2         | 2.08%   |
| Spain              | 2         | 2.08%   |
| Greece             | 2         | 2.08%   |
| Australia          | 2         | 2.08%   |
| Vietnam            | 1         | 1.04%   |
| Sweden             | 1         | 1.04%   |
| Poland             | 1         | 1.04%   |
| Peru               | 1         | 1.04%   |
| Norway             | 1         | 1.04%   |
| New Zealand        | 1         | 1.04%   |
| Netherlands        | 1         | 1.04%   |
| Ecuador            | 1         | 1.04%   |
| Dominican Republic | 1         | 1.04%   |
| Canada             | 1         | 1.04%   |
| Bangladesh         | 1         | 1.04%   |
| Argentina          | 1         | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Munich              | 3         | 3.03%   |
| Denver              | 3         | 3.03%   |
| Viby                | 2         | 2.02%   |
| Varna               | 2         | 2.02%   |
| St Petersburg       | 2         | 2.02%   |
| Prague              | 2         | 2.02%   |
| Hyderabad           | 2         | 2.02%   |
| Geneva              | 2         | 2.02%   |
| Amsterdam           | 2         | 2.02%   |
| Zurich              | 1         | 1.01%   |
| Zagnansk            | 1         | 1.01%   |
| Yekaterinburg       | 1         | 1.01%   |
| Yambol              | 1         | 1.01%   |
| Vlaardingen         | 1         | 1.01%   |
| Uzhhorod            | 1         | 1.01%   |
| Trujillo            | 1         | 1.01%   |
| Toulouse            | 1         | 1.01%   |
| Toms River          | 1         | 1.01%   |
| Syktyvkar           | 1         | 1.01%   |
| Sydney              | 1         | 1.01%   |
| South Shields       | 1         | 1.01%   |
| Schwabhausen        | 1         | 1.01%   |
| Saxtons River       | 1         | 1.01%   |
| Saint Paul          | 1         | 1.01%   |
| Rostock             | 1         | 1.01%   |
| Rosario             | 1         | 1.01%   |
| Rio de Janeiro      | 1         | 1.01%   |
| Richmond            | 1         | 1.01%   |
| Regensburg          | 1         | 1.01%   |
| Pune                | 1         | 1.01%   |
| Porto Alegre        | 1         | 1.01%   |
| Phoenix             | 1         | 1.01%   |
| Peckham             | 1         | 1.01%   |
| Paris               | 1         | 1.01%   |
| Orlando             | 1         | 1.01%   |
| Odense              | 1         | 1.01%   |
| New York            | 1         | 1.01%   |
| Nagua               | 1         | 1.01%   |
| Mossoro             | 1         | 1.01%   |
| Moscow              | 1         | 1.01%   |
| Milford             | 1         | 1.01%   |
| Miedziana Gora      | 1         | 1.01%   |
| Matos Costa         | 1         | 1.01%   |
| Malvern             | 1         | 1.01%   |
| Los Angeles         | 1         | 1.01%   |
| London              | 1         | 1.01%   |
| Lakewood            | 1         | 1.01%   |
| Krynychky           | 1         | 1.01%   |
| Kremenchug          | 1         | 1.01%   |
| Kotlas              | 1         | 1.01%   |
| Kolkata             | 1         | 1.01%   |
| Izmir               | 1         | 1.01%   |
| Itanhaem            | 1         | 1.01%   |
| Ioannina            | 1         | 1.01%   |
| Huisseau-sur-Cosson | 1         | 1.01%   |
| Horsens             | 1         | 1.01%   |
| Horice              | 1         | 1.01%   |
| Ho Chi Minh City    | 1         | 1.01%   |
| Guayaquil           | 1         | 1.01%   |
| Gothenburg          | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 37     | 21.48%  |
| WDC                 | 26        | 33     | 19.26%  |
| Seagate             | 21        | 23     | 15.56%  |
| Toshiba             | 8         | 9      | 5.93%   |
| Kingston            | 7         | 7      | 5.19%   |
| Unknown             | 6         | 11     | 4.44%   |
| Intel               | 6         | 8      | 4.44%   |
| SanDisk             | 5         | 6      | 3.7%    |
| HGST                | 5         | 6      | 3.7%    |
| Hitachi             | 3         | 3      | 2.22%   |
| SK Hynix            | 2         | 2      | 1.48%   |
| Patriot             | 2         | 2      | 1.48%   |
| Crucial             | 2         | 3      | 1.48%   |
| Corsair             | 2         | 2      | 1.48%   |
| Transcend           | 1         | 1      | 0.74%   |
| SPCC                | 1         | 1      | 0.74%   |
| Phison              | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| MAXTOR              | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Gigabyte Technology | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| BHT                 | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |
| A-DATA Technology   | 1         | 2      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 4         | 2.72%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 2.04%   |
| Toshiba MQ01ABF050 500GB                | 3         | 2.04%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 2.04%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.36%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 1.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.36%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 1.36%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.36%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.36%   |
| Patriot Burst 120GB SSD                 | 2         | 1.36%   |
| Kingston SHFS37A120G 120GB SSD          | 2         | 1.36%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.36%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 1.36%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.68%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.68%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.68%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.68%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.68%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.68%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.68%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.68%   |
| WDC WD20EZBX-00AYRA0 2TB                | 1         | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.68%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 0.68%   |
| WDC WD15EARS-00MVWB0 1TB                | 1         | 0.68%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.68%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.68%   |
| WDC WD10JPVX-08JC3T6 1TB                | 1         | 0.68%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.68%   |
| WDC WD10EZRX-00L4HB0 1TB                | 1         | 0.68%   |
| WDC WD10EFRX-68PJCN0 1TB                | 1         | 0.68%   |
| WDC WD10EFRX-68FYTN0 1TB                | 1         | 0.68%   |
| WDC WD10EARX-00PASB0 1TB                | 1         | 0.68%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 0.68%   |
| WDC WD1001FALS-00K1B0 1TB               | 1         | 0.68%   |
| WDC WD Elements 500GB                   | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 0.68%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.68%   |
| Unknown USB DISK 3.2 500GB              | 1         | 0.68%   |
| Unknown SD512  512MB                    | 1         | 0.68%   |
| Unknown SD16G  16GB                     | 1         | 0.68%   |
| Unknown MMC Card  8GB                   | 1         | 0.68%   |
| Unknown MMC Card  7GB                   | 1         | 0.68%   |
| Unknown MMC Card  32GB                  | 1         | 0.68%   |
| Unknown MMC Card  128GB                 | 1         | 0.68%   |
| Unknown MMC Card                        | 1         | 0.68%   |
| Unknown CWBC3R  64GB                    | 1         | 0.68%   |
| Transcend TS128GMTS800 128GB SSD        | 1         | 0.68%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 0.68%   |
| Toshiba HDWD110 1TB                     | 1         | 0.68%   |
| Toshiba DT01ACA200 2TB                  | 1         | 0.68%   |
| SPCC Solid State Disk 128GB             | 1         | 0.68%   |
| Seagate ST98823AS 80GB                  | 1         | 0.68%   |
| Seagate ST9750420AS 752GB               | 1         | 0.68%   |
| Seagate ST9500325AS 500GB               | 1         | 0.68%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 0.68%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 28     | 36.07%  |
| Seagate             | 21        | 23     | 34.43%  |
| Toshiba             | 7         | 8      | 11.48%  |
| HGST                | 5         | 6      | 8.2%    |
| Hitachi             | 3         | 3      | 4.92%   |
| Samsung Electronics | 2         | 2      | 3.28%   |
| MAXTOR              | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 29.73%  |
| Kingston            | 6         | 6      | 16.22%  |
| SanDisk             | 3         | 3      | 8.11%   |
| Patriot             | 2         | 2      | 5.41%   |
| Intel               | 2         | 2      | 5.41%   |
| Crucial             | 2         | 3      | 5.41%   |
| WDC                 | 1         | 1      | 2.7%    |
| Transcend           | 1         | 1      | 2.7%    |
| SPCC                | 1         | 1      | 2.7%    |
| OCZ                 | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Gigabyte Technology | 1         | 1      | 2.7%    |
| Corsair             | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| BHT                 | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 71     | 41.8%   |
| SSD     | 35        | 40     | 28.69%  |
| NVMe    | 29        | 41     | 23.77%  |
| MMC     | 5         | 9      | 4.1%    |
| Unknown | 2         | 3      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 109    | 65.45%  |
| NVMe | 29        | 41     | 26.36%  |
| MMC  | 5         | 9      | 4.55%   |
| SAS  | 4         | 5      | 3.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 60     | 54.95%  |
| 0.51-1.0   | 30        | 37     | 32.97%  |
| 1.01-2.0   | 9         | 12     | 9.89%   |
| 3.01-4.0   | 1         | 1      | 1.1%    |
| 4.01-10.0  | 1         | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 25.25%  |
| 501-1000       | 21        | 21.21%  |
| 101-250        | 18        | 18.18%  |
| Unknown        | 10        | 10.1%   |
| 1001-2000      | 7         | 7.07%   |
| More than 3000 | 5         | 5.05%   |
| 1-20           | 4         | 4.04%   |
| 21-50          | 3         | 3.03%   |
| 2001-3000      | 3         | 3.03%   |
| 51-100         | 3         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 25.49%  |
| 101-250        | 25        | 24.51%  |
| 21-50          | 14        | 13.73%  |
| Unknown        | 10        | 9.8%    |
| 251-500        | 9         | 8.82%   |
| 51-100         | 8         | 7.84%   |
| 1001-2000      | 5         | 4.9%    |
| 501-1000       | 3         | 2.94%   |
| More than 3000 | 2         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB         | 1         | 2      | 5.56%   |
| WDC WD1600BEVS-60VAT0 160GB         | 1         | 1      | 5.56%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 1      | 5.56%   |
| Toshiba MQ04ABF100 1TB              | 1         | 2      | 5.56%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 5.56%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 5.56%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 5.56%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 5.56%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 5.56%   |
| A-DATA Technology SU700 120GB SSD   | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 33.33%  |
| WDC                 | 3         | 4      | 16.67%  |
| Hitachi             | 3         | 3      | 16.67%  |
| Toshiba             | 2         | 3      | 11.11%  |
| HGST                | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 35.29%  |
| WDC                 | 3         | 4      | 17.65%  |
| Hitachi             | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 3      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 94.12%  |
| SSD  | 1         | 1      | 5.88%   |

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
| Works    | 57        | 83     | 50.89%  |
| Detected | 39        | 61     | 34.82%  |
| Malfunc  | 16        | 20     | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 42.24%  |
| AMD                              | 33        | 28.45%  |
| Samsung Electronics              | 19        | 16.38%  |
| Sandisk                          | 4         | 3.45%   |
| SK Hynix                         | 2         | 1.72%   |
| Phison Electronics               | 2         | 1.72%   |
| Toshiba America Info Systems     | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] | 1         | 0.86%   |
| Nvidia                           | 1         | 0.86%   |
| Marvell Technology Group         | 1         | 0.86%   |
| Kingston Technology Company      | 1         | 0.86%   |
| JMicron Technology               | 1         | 0.86%   |
| ASMedia Technology               | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 16.79%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 9.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 7.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 4.58%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 4.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 3.05%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.29%   |
| Intel SSD 660P Series                                                            | 3         | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.29%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 2.29%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.53%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.53%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.76%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.76%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.76%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.76%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.76%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.76%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.76%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.76%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.76%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.76%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 0.76%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.76%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.76%   |
| AMD SB600 IDE                                                                    | 1         | 0.76%   |
| AMD FCH SATA Controller D                                                        | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 64.1%   |
| NVMe | 30        | 25.64%  |
| IDE  | 8         | 6.84%   |
| RAID | 4         | 3.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 56        | 58.33%  |
| AMD                      | 37        | 38.54%  |
| ARM                      | 2         | 2.08%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 1.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 4.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 2.08%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 2.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 2.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 2.08%   |
| ARM Processor                                      | 2         | 2.08%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 2.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 2.08%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 2         | 2.08%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 2.08%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 1.04%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 1.04%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 1.04%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 1.04%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 1.04%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 1.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz                  | 1         | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 1         | 1.04%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 1.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz                  | 1         | 1.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1         | 1.04%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 1.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 1.04%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 1.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 1         | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz                  | 1         | 1.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1         | 1.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz                  | 1         | 1.04%   |
| Intel Core i5-4278U CPU @ 2.60GHz                  | 1         | 1.04%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 1         | 1.04%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz                  | 1         | 1.04%   |
| Intel Core i5-3317U CPU @ 1.70GHz                  | 1         | 1.04%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1         | 1.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz                  | 1         | 1.04%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1         | 1.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz                  | 1         | 1.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 1         | 1.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz                  | 1         | 1.04%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1         | 1.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz                  | 1         | 1.04%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz               | 1         | 1.04%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1         | 1.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz                  | 1         | 1.04%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1         | 1.04%   |
| Intel Celeron CPU 847 @ 1.10GHz                    | 1         | 1.04%   |
| Intel Celeron CPU 1005M @ 1.90GHz                  | 1         | 1.04%   |
| Intel Atom CPU Z3735G @ 1.33GHz                    | 1         | 1.04%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 1         | 1.04%   |
| Intel Atom CPU N270 @ 1.60GHz                      | 1         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 1         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz            | 1         | 1.04%   |
| AMD Turion 64 X2 Mobile Technology TL-50           | 1         | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 20.83%  |
| Intel Core i7           | 12        | 12.5%   |
| AMD Ryzen 5             | 12        | 12.5%   |
| Intel Core i3           | 8         | 8.33%   |
| AMD Ryzen 7             | 8         | 8.33%   |
| Other                   | 7         | 7.29%   |
| Intel Celeron           | 4         | 4.17%   |
| Intel Atom              | 3         | 3.13%   |
| Intel Core 2 Duo        | 2         | 2.08%   |
| AMD Ryzen 7 PRO         | 2         | 2.08%   |
| AMD FX                  | 2         | 2.08%   |
| AMD A8                  | 2         | 2.08%   |
| Intel Pentium Gold      | 1         | 1.04%   |
| Intel Pentium 4         | 1         | 1.04%   |
| Intel Pentium           | 1         | 1.04%   |
| Intel Genuine           | 1         | 1.04%   |
| Intel Core i9           | 1         | 1.04%   |
| AMD Turion 64 X2 Mobile | 1         | 1.04%   |
| AMD Ryzen 3             | 1         | 1.04%   |
| AMD Phenom II X4        | 1         | 1.04%   |
| AMD E2                  | 1         | 1.04%   |
| AMD E1                  | 1         | 1.04%   |
| AMD C-60                | 1         | 1.04%   |
| AMD Athlon II X3        | 1         | 1.04%   |
| AMD Athlon II X2        | 1         | 1.04%   |
| AMD A4                  | 1         | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 37.5%   |
| 2      | 35        | 36.46%  |
| 6      | 11        | 11.46%  |
| 8      | 10        | 10.42%  |
| 1      | 3         | 3.13%   |
| 3      | 1         | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 98.96%  |
| 2      | 1         | 1.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 63.54%  |
| 1      | 34        | 35.42%  |
| 4      | 1         | 1.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 88.54%  |
| Unknown        | 7         | 7.29%   |
| 64-bit         | 2         | 2.08%   |
| 32-bit         | 2         | 2.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 32.32%  |
| 0x40651    | 6         | 6.06%   |
| 0x306a9    | 5         | 5.05%   |
| 0x906ea    | 3         | 3.03%   |
| 0x906e9    | 3         | 3.03%   |
| 0x806ea    | 3         | 3.03%   |
| 0x806e9    | 3         | 3.03%   |
| 0x406e3    | 3         | 3.03%   |
| 0x08600104 | 3         | 3.03%   |
| 0x08108102 | 3         | 3.03%   |
| 0x806ec    | 2         | 2.02%   |
| 0x08701021 | 2         | 2.02%   |
| 0x07030105 | 2         | 2.02%   |
| 0x06000852 | 2         | 2.02%   |
| 0x05000119 | 2         | 2.02%   |
| 0x010000c8 | 2         | 2.02%   |
| 0x906ed    | 1         | 1.01%   |
| 0x806eb    | 1         | 1.01%   |
| 0x706a1    | 1         | 1.01%   |
| 0x506e3    | 1         | 1.01%   |
| 0x406c4    | 1         | 1.01%   |
| 0x30678    | 1         | 1.01%   |
| 0x206a7    | 1         | 1.01%   |
| 0x106c2    | 1         | 1.01%   |
| 0x1067a    | 1         | 1.01%   |
| 0x0a50000c | 1         | 1.01%   |
| 0x0a201205 | 1         | 1.01%   |
| 0x0a201009 | 1         | 1.01%   |
| 0x08701013 | 1         | 1.01%   |
| 0x08600106 | 1         | 1.01%   |
| 0x08600102 | 1         | 1.01%   |
| 0x08108109 | 1         | 1.01%   |
| 0x08101007 | 1         | 1.01%   |
| 0x0800820d | 1         | 1.01%   |
| 0x08001138 | 1         | 1.01%   |
| 0x08001136 | 1         | 1.01%   |
| 0x08001129 | 1         | 1.01%   |
| 0x07030104 | 1         | 1.01%   |
| 0x06006705 | 1         | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 22        | 22.92%  |
| Zen 2         | 8         | 8.33%   |
| IvyBridge     | 7         | 7.29%   |
| Haswell       | 7         | 7.29%   |
| Zen+          | 6         | 6.25%   |
| Skylake       | 6         | 6.25%   |
| Zen 3         | 5         | 5.21%   |
| Zen           | 4         | 4.17%   |
| Silvermont    | 3         | 3.13%   |
| Puma          | 3         | 3.13%   |
| K10           | 3         | 3.13%   |
| Excavator     | 3         | 3.13%   |
| Unknown       | 3         | 3.13%   |
| TigerLake     | 2         | 2.08%   |
| SandyBridge   | 2         | 2.08%   |
| Piledriver    | 2         | 2.08%   |
| Penryn        | 2         | 2.08%   |
| Goldmont plus | 2         | 2.08%   |
| Bobcat        | 2         | 2.08%   |
| NetBurst      | 1         | 1.04%   |
| K8 Hammer     | 1         | 1.04%   |
| Core          | 1         | 1.04%   |
| Bonnell       | 1         | 1.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 39.47%  |
| AMD                              | 35        | 30.7%   |
| Nvidia                           | 32        | 28.07%  |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| ASPEED Technology                | 1         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 5.93%   |
| AMD Renoir                                                                               | 6         | 5.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.24%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 2.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.54%   |
| Intel HD Graphics 620                                                                    | 3         | 2.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.54%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.69%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.69%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.85%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.85%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.85%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.85%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.85%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                                     | 1         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.85%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.85%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                                     | 1         | 0.85%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.85%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 0.85%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.85%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1         | 0.85%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.85%   |
| Intel HD Graphics 630                                                                    | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.85%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 0.85%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.85%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.85%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 0.85%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 0.85%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.85%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 1         | 0.85%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.85%   |
| AMD RS880 [Radeon HD 4290]                                                               | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 29.9%   |
| 1 x AMD        | 29        | 29.9%   |
| 1 x Nvidia     | 15        | 15.46%  |
| Intel + Nvidia | 14        | 14.43%  |
| Other          | 2         | 2.06%   |
| 2 x AMD        | 2         | 2.06%   |
| AMD + Nvidia   | 2         | 2.06%   |
| 2 x Nvidia     | 1         | 1.03%   |
| 1 x SiS        | 1         | 1.03%   |
| Intel + AMD    | 1         | 1.03%   |
| AMD + ASPEED   | 1         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 68        | 70.1%   |
| Proprietary | 26        | 26.8%   |
| Unknown     | 3         | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 53%     |
| 1.01-2.0   | 14        | 14%     |
| 0.01-0.5   | 10        | 10%     |
| 3.01-4.0   | 8         | 8%      |
| 0.51-1.0   | 7         | 7%      |
| 7.01-8.0   | 2         | 2%      |
| 5.01-6.0   | 2         | 2%      |
| 2.01-3.0   | 2         | 2%      |
| 8.01-16.0  | 2         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 14        | 13.46%  |
| AU Optronics         | 13        | 12.5%   |
| LG Display           | 11        | 10.58%  |
| BOE                  | 11        | 10.58%  |
| Samsung Electronics  | 9         | 8.65%   |
| Hewlett-Packard      | 7         | 6.73%   |
| Dell                 | 5         | 4.81%   |
| Philips              | 4         | 3.85%   |
| Acer                 | 4         | 3.85%   |
| PANDA                | 2         | 1.92%   |
| Lenovo               | 2         | 1.92%   |
| Goldstar             | 2         | 1.92%   |
| BenQ                 | 2         | 1.92%   |
| Apple                | 2         | 1.92%   |
| AOC                  | 2         | 1.92%   |
| Ancor Communications | 2         | 1.92%   |
| Unknown              | 1         | 0.96%   |
| STD                  | 1         | 0.96%   |
| Sceptre Tech         | 1         | 0.96%   |
| Sceptre              | 1         | 0.96%   |
| Panasonic            | 1         | 0.96%   |
| ONN                  | 1         | 0.96%   |
| MSI                  | 1         | 0.96%   |
| LG Philips           | 1         | 0.96%   |
| Iiyama               | 1         | 0.96%   |
| FUN                  | 1         | 0.96%   |
| Fujitsu Siemens      | 1         | 0.96%   |
| CHR                  | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.75%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 520x320mm 24.0-inch          | 2         | 1.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.83%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.83%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.92%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.92%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.92%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.92%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.92%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.92%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 0.92%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.92%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.92%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.92%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.92%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.92%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.92%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.92%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.92%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 0.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.92%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.92%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 1         | 0.92%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.92%   |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1         | 0.92%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 0.92%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1         | 0.92%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1         | 0.92%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1         | 0.92%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1         | 0.92%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 0.92%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1         | 0.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.92%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1         | 0.92%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1         | 0.92%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1         | 0.92%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1         | 0.92%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 1         | 0.92%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 1         | 0.92%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 1         | 0.92%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 1         | 0.92%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 45.1%   |
| 1366x768 (WXGA)    | 22        | 21.57%  |
| 1920x1200 (WUXGA)  | 5         | 4.9%    |
| 3840x2160 (4K)     | 4         | 3.92%   |
| 2560x1440 (QHD)    | 4         | 3.92%   |
| 1680x1050 (WSXGA+) | 4         | 3.92%   |
| 2160x1440          | 2         | 1.96%   |
| 1600x900 (HD+)     | 2         | 1.96%   |
| 1280x800 (WXGA)    | 2         | 1.96%   |
| Unknown            | 2         | 1.96%   |
| 7680x1080          | 1         | 0.98%   |
| 3840x1600          | 1         | 0.98%   |
| 3840x1080          | 1         | 0.98%   |
| 3440x1440          | 1         | 0.98%   |
| 2560x1600          | 1         | 0.98%   |
| 2256x1504          | 1         | 0.98%   |
| 1360x768           | 1         | 0.98%   |
| 1280x1024 (SXGA)   | 1         | 0.98%   |
| 1024x600           | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 26.67%  |
| 13      | 13        | 12.38%  |
| 24      | 11        | 10.48%  |
| Unknown | 10        | 9.52%   |
| 14      | 8         | 7.62%   |
| 21      | 5         | 4.76%   |
| 27      | 4         | 3.81%   |
| 23      | 4         | 3.81%   |
| 22      | 4         | 3.81%   |
| 12      | 3         | 2.86%   |
| 17      | 2         | 1.9%    |
| 11      | 2         | 1.9%    |
| 84      | 1         | 0.95%   |
| 40      | 1         | 0.95%   |
| 39      | 1         | 0.95%   |
| 37      | 1         | 0.95%   |
| 34      | 1         | 0.95%   |
| 33      | 1         | 0.95%   |
| 31      | 1         | 0.95%   |
| 25      | 1         | 0.95%   |
| 20      | 1         | 0.95%   |
| 18      | 1         | 0.95%   |
| 8       | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 40.38%  |
| 501-600     | 19        | 18.27%  |
| 201-300     | 13        | 12.5%   |
| 401-500     | 11        | 10.58%  |
| Unknown     | 10        | 9.62%   |
| 801-900     | 3         | 2.88%   |
| 701-800     | 2         | 1.92%   |
| 601-700     | 1         | 0.96%   |
| 351-400     | 1         | 0.96%   |
| 1501-2000   | 1         | 0.96%   |
| 101-200     | 1         | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 70        | 72.16%  |
| 16/10   | 12        | 12.37%  |
| Unknown | 9         | 9.28%   |
| 3/2     | 3         | 3.09%   |
| 21/9    | 2         | 2.06%   |
| 5/4     | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 26.67%  |
| 81-90          | 16        | 15.24%  |
| 201-250        | 16        | 15.24%  |
| Unknown        | 10        | 9.52%   |
| 251-300        | 8         | 7.62%   |
| 71-80          | 6         | 5.71%   |
| 301-350        | 4         | 3.81%   |
| 61-70          | 3         | 2.86%   |
| 351-500        | 3         | 2.86%   |
| 501-1000       | 3         | 2.86%   |
| 51-60          | 2         | 1.9%    |
| 141-150        | 2         | 1.9%    |
| More than 1000 | 1         | 0.95%   |
| 1-40           | 1         | 0.95%   |
| 151-200        | 1         | 0.95%   |
| 131-140        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 31        | 29.52%  |
| 101-120       | 27        | 25.71%  |
| 121-160       | 25        | 23.81%  |
| 161-240       | 11        | 10.48%  |
| Unknown       | 10        | 9.52%   |
| More than 240 | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 79.38%  |
| 2     | 18        | 18.56%  |
| 0     | 2         | 2.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 52        | 38.52%  |
| Intel                            | 37        | 27.41%  |
| Qualcomm Atheros                 | 14        | 10.37%  |
| Broadcom                         | 8         | 5.93%   |
| TP-Link                          | 3         | 2.22%   |
| Sierra Wireless                  | 3         | 2.22%   |
| Ralink Technology                | 3         | 2.22%   |
| Qualcomm Atheros Communications  | 2         | 1.48%   |
| Cypress Semiconductor            | 2         | 1.48%   |
| Broadcom Limited                 | 2         | 1.48%   |
| Xiaomi                           | 1         | 0.74%   |
| Tenda                            | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Ralink                           | 1         | 0.74%   |
| Nvidia                           | 1         | 0.74%   |
| MediaTek                         | 1         | 0.74%   |
| DisplayLink                      | 1         | 0.74%   |
| ASIX Electronics                 | 1         | 0.74%   |
| Apple                            | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 24.53%  |
| Intel Wi-Fi 6 AX200                                               | 9         | 5.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.4%    |
| Intel Wireless 8265 / 8275                                        | 6         | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.89%   |
| Intel Wireless 8260                                               | 3         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.26%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.26%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.26%   |
| Intel Wireless 7260                                               | 2         | 1.26%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Cypress K38231_03                                                 | 2         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.63%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.63%   |
| Tenda U12                                                         | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.63%   |
| Sierra Wireless EM7455                                            | 1         | 0.63%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.63%   |
| Sierra Wireless EM7305                                            | 1         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.63%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.63%   |
| MediaTek U FEEL                                                   | 1         | 0.63%   |
| Intel Wireless-AC 9260                                            | 1         | 0.63%   |
| Intel WiFi Link 5100                                              | 1         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.63%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 39.19%  |
| Realtek Semiconductor           | 15        | 20.27%  |
| Qualcomm Atheros                | 12        | 16.22%  |
| Broadcom                        | 4         | 5.41%   |
| Sierra Wireless                 | 3         | 4.05%   |
| Ralink Technology               | 3         | 4.05%   |
| TP-Link                         | 2         | 2.7%    |
| Qualcomm Atheros Communications | 2         | 2.7%    |
| Broadcom Limited                | 2         | 2.7%    |
| Tenda                           | 1         | 1.35%   |
| Ralink                          | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 9         | 12.16%  |
| Intel Wireless 8265 / 8275                                 | 6         | 8.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 4         | 5.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 5.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3         | 4.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 3         | 4.05%   |
| Intel Wireless 8260                                        | 3         | 4.05%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 3         | 4.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2         | 2.7%    |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 2.7%    |
| Ralink MT7601U Wireless Adapter                            | 2         | 2.7%    |
| Qualcomm Atheros AR9271 802.11n                            | 2         | 2.7%    |
| Intel Wireless 7260                                        | 2         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 1.35%   |
| Tenda U12                                                  | 1         | 1.35%   |
| Sierra Wireless EM7455                                     | 1         | 1.35%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 1.35%   |
| Sierra Wireless EM7305                                     | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 1.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter   | 1         | 1.35%   |
| Ralink RT5572 Wireless Adapter                             | 1         | 1.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.35%   |
| Intel Wireless-AC 9260                                     | 1         | 1.35%   |
| Intel WiFi Link 5100                                       | 1         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 1.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 1.35%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 1.35%   |
| Broadcom BCM4311 802.11b/g WLAN                            | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 49        | 57.65%  |
| Intel                            | 18        | 21.18%  |
| Broadcom                         | 5         | 5.88%   |
| Qualcomm Atheros                 | 3         | 3.53%   |
| Cypress Semiconductor            | 2         | 2.35%   |
| Xiaomi                           | 1         | 1.18%   |
| TP-Link                          | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] | 1         | 1.18%   |
| Nvidia                           | 1         | 1.18%   |
| MediaTek                         | 1         | 1.18%   |
| DisplayLink                      | 1         | 1.18%   |
| ASIX Electronics                 | 1         | 1.18%   |
| Apple                            | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 45.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 8.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 3.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.35%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.35%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.35%   |
| Cypress K38231_03                                                 | 2         | 2.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.18%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.18%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.18%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.18%   |
| MediaTek U FEEL                                                   | 1         | 1.18%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.18%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 1.18%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.18%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.18%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.18%   |
| Apple iPad 4/Mini1                                                | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 81        | 53.64%  |
| WiFi     | 70        | 46.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 50%     |
| Ethernet | 66        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 46        | 47.92%  |
| 2     | 44        | 45.83%  |
| 0     | 4         | 4.17%   |
| 3     | 2         | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 88.78%  |
| Yes  | 11        | 11.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 43.55%  |
| Realtek Semiconductor           | 9         | 14.52%  |
| Lite-On Technology              | 5         | 8.06%   |
| Cambridge Silicon Radio         | 5         | 8.06%   |
| Broadcom                        | 5         | 8.06%   |
| Qualcomm Atheros Communications | 3         | 4.84%   |
| IMC Networks                    | 3         | 4.84%   |
| Foxconn / Hon Hai               | 2         | 3.23%   |
| Realtek                         | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |
| Apple                           | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 17.74%  |
| Intel AX200 Bluetooth                               | 9         | 14.52%  |
| Realtek Bluetooth Radio                             | 5         | 8.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 8.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.23%   |
| Intel AX201 Bluetooth                               | 2         | 3.23%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.61%   |
| Realtek Bluetooth Radio                             | 1         | 1.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.61%   |
| Intel Bluetooth Device                              | 1         | 1.61%   |
| Intel AX210 Bluetooth                               | 1         | 1.61%   |
| IMC Networks Bluetooth Device                       | 1         | 1.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.61%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.61%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.61%   |
| Broadcom HP Portable Valentine                      | 1         | 1.61%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.61%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.61%   |
| Apple Bluetooth Host Controller                     | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 40.31%  |
| AMD                              | 39        | 30.23%  |
| Nvidia                           | 21        | 16.28%  |
| Logitech                         | 3         | 2.33%   |
| JMTek                            | 3         | 2.33%   |
| C-Media Electronics              | 3         | 2.33%   |
| Texas Instruments                | 2         | 1.55%   |
| VIA Technologies                 | 1         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| SAVITECH                         | 1         | 0.78%   |
| Elgato Systems                   | 1         | 0.78%   |
| Creative Technology              | 1         | 0.78%   |
| Cambridge Audio                  | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 7.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 7.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 4.24%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 4.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 3.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 3.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.42%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 1.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.82%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.82%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.21%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.21%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.21%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.21%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                                | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.61%   |
| SAVITECH SA9023 audio controller                                                                  | 1         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.61%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.61%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.61%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Logitech G633 Gaming Headset                                                                      | 1         | 0.61%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.61%   |
| Logitech Blue Snowball                                                                            | 1         | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.61%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.61%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                                 | 1         | 0.61%   |
| Elgato Systems Elgato Wave:3                                                                      | 1         | 0.61%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.61%   |
| Cambridge Audio USB Audio 2.0                                                                     | 1         | 0.61%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 0.61%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 0.61%   |
| C-Media Electronics Antlion USB adapter                                                           | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 18        | 23.38%  |
| Samsung Electronics | 17        | 22.08%  |
| Micron Technology   | 8         | 10.39%  |
| Kingston            | 7         | 9.09%   |
| Unknown             | 5         | 6.49%   |
| G.Skill             | 5         | 6.49%   |
| Corsair             | 5         | 6.49%   |
| A-DATA Technology   | 5         | 6.49%   |
| Crucial             | 2         | 2.6%    |
| Transcend           | 1         | 1.3%    |
| Ramaxel Technology  | 1         | 1.3%    |
| Patriot             | 1         | 1.3%    |
| Elpida              | 1         | 1.3%    |
| Avant               | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.35%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 2.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 2.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 2         | 2.35%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.18%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 1.18%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.18%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 4096MB SODIMM DDR4 3200MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.18%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s              | 1         | 1.18%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s           | 1         | 1.18%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.18%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.18%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s                | 1         | 1.18%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.18%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.18%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Kingston RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 1.18%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 1.18%   |
| Kingston RAM HP16D3LS1KBGH/4G 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| Kingston RAM ACR26D4S9S1KA-4 4GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 1.18%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s            | 1         | 1.18%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Kingston RAM 9905701-017.A00G 16384MB DIMM DDR4 2666MT/s         | 1         | 1.18%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 1         | 1.18%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 50%     |
| DDR3    | 25        | 36.76%  |
| LPDDR4  | 3         | 4.41%   |
| LPDDR3  | 3         | 4.41%   |
| Unknown | 2         | 2.94%   |
| DDR2    | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 64.18%  |
| DIMM         | 21        | 31.34%  |
| Row Of Chips | 3         | 4.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 43.06%  |
| 4096  | 25        | 34.72%  |
| 16384 | 8         | 11.11%  |
| 2048  | 5         | 6.94%   |
| 1024  | 2         | 2.78%   |
| 512   | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 22.97%  |
| 2667  | 12        | 16.22%  |
| 3200  | 9         | 12.16%  |
| 2400  | 9         | 12.16%  |
| 1333  | 6         | 8.11%   |
| 2133  | 4         | 5.41%   |
| 3600  | 3         | 4.05%   |
| 1334  | 3         | 4.05%   |
| 3000  | 2         | 2.7%    |
| 1867  | 2         | 2.7%    |
| 4266  | 1         | 1.35%   |
| 3733  | 1         | 1.35%   |
| 2933  | 1         | 1.35%   |
| 2800  | 1         | 1.35%   |
| 2666  | 1         | 1.35%   |
| 1067  | 1         | 1.35%   |
| 533   | 1         | 1.35%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 25.71%  |
| IMC Networks                           | 11        | 15.71%  |
| Microdia                               | 8         | 11.43%  |
| Realtek Semiconductor                  | 6         | 8.57%   |
| Logitech                               | 6         | 8.57%   |
| Quanta                                 | 5         | 7.14%   |
| Acer                                   | 5         | 7.14%   |
| Sunplus Innovation Technology          | 3         | 4.29%   |
| Suyin                                  | 2         | 2.86%   |
| MacroSilicon                           | 2         | 2.86%   |
| Silicon Motion                         | 1         | 1.43%   |
| Microsoft                              | 1         | 1.43%   |
| GEMBIRD                                | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 5         | 6.94%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 5.56%   |
| Quanta HD User Facing                             | 3         | 4.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 3         | 4.17%   |
| Suyin HP TrueVision HD                            | 2         | 2.78%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 2.78%   |
| Microdia HP Integrated Webcam                     | 2         | 2.78%   |
| Logitech Webcam C270                              | 2         | 2.78%   |
| Chicony HD WebCam                                 | 2         | 2.78%   |
| Sunplus HP Wide Vision HD                         | 1         | 1.39%   |
| Silicon Motion WebCam SC-10HDD12636N              | 1         | 1.39%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 1.39%   |
| Realtek USB Camera                                | 1         | 1.39%   |
| Realtek Laptop Camera                             | 1         | 1.39%   |
| Realtek Integrated Webcam HD                      | 1         | 1.39%   |
| Realtek HD WebCam                                 | 1         | 1.39%   |
| Realtek FULL HD 1080P Webcam                      | 1         | 1.39%   |
| Quanta VGA WebCam                                 | 1         | 1.39%   |
| Quanta HP TrueVision HD Camera                    | 1         | 1.39%   |
| Microsoft LifeCam HD-3000                         | 1         | 1.39%   |
| Microdia Webcam Vitade AF                         | 1         | 1.39%   |
| Microdia Sonix USB 2.0 Camera                     | 1         | 1.39%   |
| Microdia Integrated_Webcam_HD                     | 1         | 1.39%   |
| Microdia Integrated_Webcam_2M                     | 1         | 1.39%   |
| Microdia Hy-HD-Camera                             | 1         | 1.39%   |
| Microdia Camera                                   | 1         | 1.39%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1         | 1.39%   |
| MacroSilicon MiraBox Capture                      | 1         | 1.39%   |
| Logitech Webcam C930e                             | 1         | 1.39%   |
| Logitech HD Webcam C615                           | 1         | 1.39%   |
| Logitech C922 Pro Stream Webcam                   | 1         | 1.39%   |
| Logitech C505 HD Webcam                           | 1         | 1.39%   |
| IMC Networks VGA UVC WebCam                       | 1         | 1.39%   |
| IMC Networks HP TrueVision HD Camera              | 1         | 1.39%   |
| IMC Networks HD Camera                            | 1         | 1.39%   |
| IMC Networks EasyCamera                           | 1         | 1.39%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1         | 1.39%   |
| Chicony WebCam                                    | 1         | 1.39%   |
| Chicony USB2.0 Camera                             | 1         | 1.39%   |
| Chicony USB 5M WebCam                             | 1         | 1.39%   |
| Chicony USB 2.0 Camera                            | 1         | 1.39%   |
| Chicony thinkpad t430s camera                     | 1         | 1.39%   |
| Chicony Lenovo EasyCamera                         | 1         | 1.39%   |
| Chicony Integrated IR Camera                      | 1         | 1.39%   |
| Chicony Integrated Camera (1280x720@30)           | 1         | 1.39%   |
| Chicony HP TrueVision HD Camera                   | 1         | 1.39%   |
| Chicony HP 720p HD Monitor Webcam                 | 1         | 1.39%   |
| Chicony HD WebCam (Acer)                          | 1         | 1.39%   |
| Chicony HD User Facing                            | 1         | 1.39%   |
| Chicony EasyCamera                                | 1         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) Webcam     | 1         | 1.39%   |
| Acer SunplusIT Integrated Camera                  | 1         | 1.39%   |
| Acer SunplusIT INC. Integrated Camera             | 1         | 1.39%   |
| Acer OrbiCam                                      | 1         | 1.39%   |
| Acer Lenovo EasyCamera                            | 1         | 1.39%   |
| Acer Integrated Camera                            | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 5         | 62.5%   |
| Validity Sensors | 3         | 37.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 3         | 37.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 37.5%   |
| Synaptics  WBDI                                   | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 75%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 75%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 78.35%  |
| 1     | 14        | 14.43%  |
| 2     | 5         | 5.15%   |
| 3     | 2         | 2.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 27.59%  |
| Net/wireless          | 5         | 17.24%  |
| Graphics card         | 5         | 17.24%  |
| Chipcard              | 4         | 13.79%  |
| Sound                 | 2         | 6.9%    |
| Multimedia controller | 2         | 6.9%    |
| Camera                | 2         | 6.9%    |
| Net/ethernet          | 1         | 3.45%   |

