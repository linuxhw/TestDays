Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

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

Total: 143

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
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
| Dell          | Latitude 3379               | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 63        | 57.27%  |
| Void Linux         | 47        | 42.73%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 106       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.13.19_1           | 7         | 6.09%   |
| 5.8.18_1            | 5         | 4.35%   |
| 5.3.9_1             | 4         | 3.48%   |
| 5.16.20_1           | 4         | 3.48%   |
| 5.10.17_1           | 4         | 3.48%   |
| 5.8.12_1            | 3         | 2.61%   |
| 5.15.32_1           | 3         | 2.61%   |
| 5.13.13_1           | 3         | 2.61%   |
| 5.12.10_1           | 3         | 2.61%   |
| 5.9.14_1            | 2         | 1.74%   |
| 5.4.24_1            | 2         | 1.74%   |
| 5.4.13_2            | 2         | 1.74%   |
| 5.15.34_1           | 2         | 1.74%   |
| 5.15.22_1           | 2         | 1.74%   |
| 5.15.16_1           | 2         | 1.74%   |
| 5.13.15_1           | 2         | 1.74%   |
| 5.13.10_1           | 2         | 1.74%   |
| 5.12.14_1           | 2         | 1.74%   |
| 5.11.9_1            | 2         | 1.74%   |
| 5.10.14_1           | 2         | 1.74%   |
| 5.9.16_1            | 1         | 0.87%   |
| 5.9.0-rc8_2         | 1         | 0.87%   |
| 5.8.9_1             | 1         | 0.87%   |
| 5.8.8_1             | 1         | 0.87%   |
| 5.8.7_1             | 1         | 0.87%   |
| 5.8.6_1             | 1         | 0.87%   |
| 5.8.5_1             | 1         | 0.87%   |
| 5.8.16_1            | 1         | 0.87%   |
| 5.8.14_1            | 1         | 0.87%   |
| 5.8.12_2            | 1         | 0.87%   |
| 5.8.11_1            | 1         | 0.87%   |
| 5.8.10_1            | 1         | 0.87%   |
| 5.7.16_1            | 1         | 0.87%   |
| 5.6.14_1            | 1         | 0.87%   |
| 5.4.35_1            | 1         | 0.87%   |
| 5.4.21_1            | 1         | 0.87%   |
| 5.4.15_1            | 1         | 0.87%   |
| 5.3.16_1            | 1         | 0.87%   |
| 5.2.13_1            | 1         | 0.87%   |
| 5.15.6_1            | 1         | 0.87%   |
| 5.15.41_1           | 1         | 0.87%   |
| 5.15.30_1           | 1         | 0.87%   |
| 5.15.28_1           | 1         | 0.87%   |
| 5.15.26_1           | 1         | 0.87%   |
| 5.15.24_1           | 1         | 0.87%   |
| 5.15.19_1           | 1         | 0.87%   |
| 5.15.17_1           | 1         | 0.87%   |
| 5.15.14_1           | 1         | 0.87%   |
| 5.15.12_1           | 1         | 0.87%   |
| 5.15.11_1           | 1         | 0.87%   |
| 5.14.0_1            | 1         | 0.87%   |
| 5.13.18_1           | 1         | 0.87%   |
| 5.13.12_1           | 1         | 0.87%   |
| 5.12.7_1            | 1         | 0.87%   |
| 5.12.6              | 1         | 0.87%   |
| 5.12.3-tkg-MuQSS_22 | 1         | 0.87%   |
| 5.12.19_1           | 1         | 0.87%   |
| 5.11.18_1           | 1         | 0.87%   |
| 5.11.16_1           | 1         | 0.87%   |
| 5.11.11_1           | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 6.09%   |
| 5.8.18  | 5         | 4.35%   |
| 5.8.12  | 4         | 3.48%   |
| 5.3.9   | 4         | 3.48%   |
| 5.16.20 | 4         | 3.48%   |
| 5.10.17 | 4         | 3.48%   |
| 5.15.32 | 3         | 2.61%   |
| 5.13.13 | 3         | 2.61%   |
| 5.12.10 | 3         | 2.61%   |
| 5.9.14  | 2         | 1.74%   |
| 5.4.24  | 2         | 1.74%   |
| 5.4.13  | 2         | 1.74%   |
| 5.15.34 | 2         | 1.74%   |
| 5.15.22 | 2         | 1.74%   |
| 5.15.16 | 2         | 1.74%   |
| 5.13.15 | 2         | 1.74%   |
| 5.13.10 | 2         | 1.74%   |
| 5.12.14 | 2         | 1.74%   |
| 5.11.9  | 2         | 1.74%   |
| 5.10.14 | 2         | 1.74%   |
| 5.9.16  | 1         | 0.87%   |
| 5.9.0   | 1         | 0.87%   |
| 5.8.9   | 1         | 0.87%   |
| 5.8.8   | 1         | 0.87%   |
| 5.8.7   | 1         | 0.87%   |
| 5.8.6   | 1         | 0.87%   |
| 5.8.5   | 1         | 0.87%   |
| 5.8.16  | 1         | 0.87%   |
| 5.8.14  | 1         | 0.87%   |
| 5.8.11  | 1         | 0.87%   |
| 5.8.10  | 1         | 0.87%   |
| 5.7.16  | 1         | 0.87%   |
| 5.6.14  | 1         | 0.87%   |
| 5.4.35  | 1         | 0.87%   |
| 5.4.21  | 1         | 0.87%   |
| 5.4.15  | 1         | 0.87%   |
| 5.3.16  | 1         | 0.87%   |
| 5.2.13  | 1         | 0.87%   |
| 5.15.6  | 1         | 0.87%   |
| 5.15.41 | 1         | 0.87%   |
| 5.15.30 | 1         | 0.87%   |
| 5.15.28 | 1         | 0.87%   |
| 5.15.26 | 1         | 0.87%   |
| 5.15.24 | 1         | 0.87%   |
| 5.15.19 | 1         | 0.87%   |
| 5.15.17 | 1         | 0.87%   |
| 5.15.14 | 1         | 0.87%   |
| 5.15.12 | 1         | 0.87%   |
| 5.15.11 | 1         | 0.87%   |
| 5.14.0  | 1         | 0.87%   |
| 5.13.18 | 1         | 0.87%   |
| 5.13.12 | 1         | 0.87%   |
| 5.12.7  | 1         | 0.87%   |
| 5.12.6  | 1         | 0.87%   |
| 5.12.3  | 1         | 0.87%   |
| 5.12.19 | 1         | 0.87%   |
| 5.11.18 | 1         | 0.87%   |
| 5.11.16 | 1         | 0.87%   |
| 5.11.11 | 1         | 0.87%   |
| 5.10.9  | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 20        | 17.54%  |
| 5.8     | 18        | 15.79%  |
| 5.13    | 16        | 14.04%  |
| 5.10    | 15        | 13.16%  |
| 5.12    | 9         | 7.89%   |
| 5.4     | 7         | 6.14%   |
| 5.3     | 5         | 4.39%   |
| 5.11    | 5         | 4.39%   |
| 5.9     | 4         | 3.51%   |
| 5.16    | 4         | 3.51%   |
| 4.19    | 4         | 3.51%   |
| 5.7     | 1         | 0.88%   |
| 5.6     | 1         | 0.88%   |
| 5.2     | 1         | 0.88%   |
| 5.14    | 1         | 0.88%   |
| 5.1     | 1         | 0.88%   |
| 4.4     | 1         | 0.88%   |
| 4.14    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 99        | 93.4%   |
| i686    | 4         | 3.77%   |
| aarch64 | 2         | 1.89%   |
| ppc64le | 1         | 0.94%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 47.75%  |
| XFCE       | 12        | 10.81%  |
| KDE        | 10        | 9.01%   |
| MATE       | 6         | 5.41%   |
| GNOME      | 6         | 5.41%   |
| i3         | 5         | 4.5%    |
| KDE5       | 4         | 3.6%    |
| X-Cinnamon | 3         | 2.7%    |
| openbox    | 3         | 2.7%    |
| bspwm      | 3         | 2.7%    |
| Lumina     | 2         | 1.8%    |
| awesome    | 2         | 1.8%    |
| sway       | 1         | 0.9%    |
| river      | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 75        | 69.44%  |
| Wayland | 12        | 11.11%  |
| Tty     | 12        | 11.11%  |
| Unknown | 9         | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 100       | 92.59%  |
| LightDM | 4         | 3.7%    |
| SDDM    | 2         | 1.85%   |
| LXDM    | 1         | 0.93%   |
| GDM     | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 54        | 48.65%  |
| Unknown | 18        | 16.22%  |
| en_GB   | 7         | 6.31%   |
| en_DK   | 6         | 5.41%   |
| ru_RU   | 4         | 3.6%    |
| de_DE   | 3         | 2.7%    |
| pt_BR   | 2         | 1.8%    |
| fr_FR   | 2         | 1.8%    |
| en_AU   | 2         | 1.8%    |
| cs_CZ   | 2         | 1.8%    |
| ru_UA   | 1         | 0.9%    |
| pl_PL   | 1         | 0.9%    |
| nb_NO   | 1         | 0.9%    |
| es_HN   | 1         | 0.9%    |
| es_ES   | 1         | 0.9%    |
| es_DO   | 1         | 0.9%    |
| en_NZ   | 1         | 0.9%    |
| en_IE   | 1         | 0.9%    |
| en_CA   | 1         | 0.9%    |
| el_GR   | 1         | 0.9%    |
| bg_BG   | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 56        | 51.38%  |
| BIOS | 53        | 48.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 61.11%  |
| Btrfs   | 23        | 21.3%   |
| Zfs     | 6         | 5.56%   |
| Xfs     | 6         | 5.56%   |
| Unknown | 5         | 4.63%   |
| F2fs    | 1         | 0.93%   |
| Ext3    | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 60        | 55.05%  |
| Unknown | 34        | 31.19%  |
| MBR     | 15        | 13.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 87.74%  |
| Yes       | 13        | 12.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 80.37%  |
| Yes       | 21        | 19.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 23        | 21.7%   |
| Lenovo              | 16        | 15.09%  |
| Acer                | 12        | 11.32%  |
| Hewlett-Packard     | 10        | 9.43%   |
| Dell                | 10        | 9.43%   |
| MSI                 | 8         | 7.55%   |
| ASRock              | 8         | 7.55%   |
| Gigabyte Technology | 4         | 3.77%   |
| Unknown             | 3         | 2.83%   |
| HUAWEI              | 2         | 1.89%   |
| Samsung Electronics | 1         | 0.94%   |
| Positivo            | 1         | 0.94%   |
| Pine Microsystems   | 1         | 0.94%   |
| Notebook            | 1         | 0.94%   |
| Getac               | 1         | 0.94%   |
| Framework           | 1         | 0.94%   |
| Digibras            | 1         | 0.94%   |
| Cisco Systems       | 1         | 0.94%   |
| Chuwi               | 1         | 0.94%   |
| Apple               | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 3         | 2.83%   |
| ASUS PRIME Z390-P                      | 2         | 1.89%   |
| Acer Swift SF314-42                    | 2         | 1.89%   |
| Samsung 275E4E/275E5E                  | 1         | 0.94%   |
| Positivo Mobile                        | 1         | 0.94%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.94%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.94%   |
| MSI MS-7D14                            | 1         | 0.94%   |
| MSI MS-7C92                            | 1         | 0.94%   |
| MSI MS-7C52                            | 1         | 0.94%   |
| MSI MS-7C02                            | 1         | 0.94%   |
| MSI MS-7A68                            | 1         | 0.94%   |
| MSI MS-7A39                            | 1         | 0.94%   |
| MSI MS-7816                            | 1         | 0.94%   |
| MSI Bravo 15 A4DDR                     | 1         | 0.94%   |
| Lenovo Yoga 720-15IKB 80X7             | 1         | 0.94%   |
| Lenovo ThinkPad X260 20F5S08Q00        | 1         | 0.94%   |
| Lenovo ThinkPad X240 20AMA34HMN        | 1         | 0.94%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS | 1         | 0.94%   |
| Lenovo ThinkPad T480 20L6SA5Q00        | 1         | 0.94%   |
| Lenovo ThinkPad T460 20FMS0WN00        | 1         | 0.94%   |
| Lenovo ThinkPad T430 2349PS3           | 1         | 0.94%   |
| Lenovo ThinkPad T420 4180A21           | 1         | 0.94%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW  | 1         | 0.94%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00  | 1         | 0.94%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200   | 1         | 0.94%   |
| Lenovo ThinkPad E595 20NFCTO1WW        | 1         | 0.94%   |
| Lenovo IdeaPad Z570 10246ZG            | 1         | 0.94%   |
| Lenovo IdeaPad S145-14IIL 81W6         | 1         | 0.94%   |
| Lenovo IdeaPad 710S-13IKB 80VQ         | 1         | 0.94%   |
| Lenovo G50-45 80E3                     | 1         | 0.94%   |
| HUAWEI KLVL-WXXW                       | 1         | 0.94%   |
| HUAWEI HN-WX9X                         | 1         | 0.94%   |
| HP Z2 Mini G3 Workstation              | 1         | 0.94%   |
| HP Stream 7 Tablet                     | 1         | 0.94%   |
| HP Pavilion Notebook                   | 1         | 0.94%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.94%   |
| HP Notebook                            | 1         | 0.94%   |
| HP Laptop 15-bw0xx                     | 1         | 0.94%   |
| HP Laptop 14-dk0xxx                    | 1         | 0.94%   |
| HP Laptop 14-bs0xx                     | 1         | 0.94%   |
| HP ENVY 6                              | 1         | 0.94%   |
| HP 15                                  | 1         | 0.94%   |
| Gigabyte H310M M.2 2.0                 | 1         | 0.94%   |
| Gigabyte GA-78LMT-S2                   | 1         | 0.94%   |
| Gigabyte B550M AORUS PRO-P             | 1         | 0.94%   |
| Gigabyte B450M DS3H                    | 1         | 0.94%   |
| Getac V110                             | 1         | 0.94%   |
| Framework Laptop                       | 1         | 0.94%   |
| Digibras NH4CU03                       | 1         | 0.94%   |
| Dell Precision 3530                    | 1         | 0.94%   |
| Dell OptiPlex GX520                    | 1         | 0.94%   |
| Dell OptiPlex 780                      | 1         | 0.94%   |
| Dell OptiPlex 7010                     | 1         | 0.94%   |
| Dell Latitude E4300                    | 1         | 0.94%   |
| Dell Latitude 3379                     | 1         | 0.94%   |
| Dell Inspiron 5555                     | 1         | 0.94%   |
| Dell Inspiron 1501                     | 1         | 0.94%   |
| Dell Inspiron 11 - 3148                | 1         | 0.94%   |
| Dell G3 3579                           | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 10.38%  |
| Acer Aspire              | 7         | 6.6%    |
| ASUS PRIME               | 5         | 4.72%   |
| ASUS VivoBook            | 4         | 3.77%   |
| Lenovo IdeaPad           | 3         | 2.83%   |
| HP Laptop                | 3         | 2.83%   |
| Dell OptiPlex            | 3         | 2.83%   |
| Dell Inspiron            | 3         | 2.83%   |
| Unknown                  | 3         | 2.83%   |
| HP Pavilion              | 2         | 1.89%   |
| Dell Latitude            | 2         | 1.89%   |
| ASUS ROG                 | 2         | 1.89%   |
| Acer Swift               | 2         | 1.89%   |
| Samsung 275E4E           | 1         | 0.94%   |
| Positivo Mobile          | 1         | 0.94%   |
| Pine Microsystems Pine64 | 1         | 0.94%   |
| Notebook NV4XMB          | 1         | 0.94%   |
| MSI MS-7D14              | 1         | 0.94%   |
| MSI MS-7C92              | 1         | 0.94%   |
| MSI MS-7C52              | 1         | 0.94%   |
| MSI MS-7C02              | 1         | 0.94%   |
| MSI MS-7A68              | 1         | 0.94%   |
| MSI MS-7A39              | 1         | 0.94%   |
| MSI MS-7816              | 1         | 0.94%   |
| MSI Bravo                | 1         | 0.94%   |
| Lenovo Yoga              | 1         | 0.94%   |
| Lenovo G50-45            | 1         | 0.94%   |
| HUAWEI KLVL-WXXW         | 1         | 0.94%   |
| HUAWEI HN-WX9X           | 1         | 0.94%   |
| HP Z2                    | 1         | 0.94%   |
| HP Stream                | 1         | 0.94%   |
| HP Notebook              | 1         | 0.94%   |
| HP ENVY                  | 1         | 0.94%   |
| HP 15                    | 1         | 0.94%   |
| Gigabyte H310M           | 1         | 0.94%   |
| Gigabyte GA-78LMT-S2     | 1         | 0.94%   |
| Gigabyte B550M           | 1         | 0.94%   |
| Gigabyte B450M           | 1         | 0.94%   |
| Getac V110               | 1         | 0.94%   |
| Framework Laptop         | 1         | 0.94%   |
| Digibras NH4CU03         | 1         | 0.94%   |
| Dell Precision           | 1         | 0.94%   |
| Dell G3                  | 1         | 0.94%   |
| Cisco Systems PowerEdge  | 1         | 0.94%   |
| Chuwi GemiBook           | 1         | 0.94%   |
| ASUS X751LD              | 1         | 0.94%   |
| ASUS X555UJ              | 1         | 0.94%   |
| ASUS X510UAR             | 1         | 0.94%   |
| ASUS TUF                 | 1         | 0.94%   |
| ASUS Q325UAR             | 1         | 0.94%   |
| ASUS P8Z77-V             | 1         | 0.94%   |
| ASUS P8H67-V             | 1         | 0.94%   |
| ASUS M5A78L-M            | 1         | 0.94%   |
| ASUS M4A89GTD-PRO        | 1         | 0.94%   |
| ASUS H110M-PLUS          | 1         | 0.94%   |
| ASUS B150M               | 1         | 0.94%   |
| ASUS ASUS                | 1         | 0.94%   |
| ASRock X570              | 1         | 0.94%   |
| ASRock TRX40             | 1         | 0.94%   |
| ASRock N68-S3            | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 17        | 16.04%  |
| 2020    | 14        | 13.21%  |
| 2018    | 14        | 13.21%  |
| 2017    | 10        | 9.43%   |
| 2016    | 9         | 8.49%   |
| 2013    | 8         | 7.55%   |
| 2012    | 7         | 6.6%    |
| 2014    | 6         | 5.66%   |
| 2011    | 5         | 4.72%   |
| 2015    | 3         | 2.83%   |
| 2010    | 3         | 2.83%   |
| Unknown | 3         | 2.83%   |
| 2021    | 2         | 1.89%   |
| 2008    | 2         | 1.89%   |
| 2006    | 2         | 1.89%   |
| 2009    | 1         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 63        | 59.43%  |
| Desktop     | 37        | 34.91%  |
| Convertible | 3         | 2.83%   |
| Tablet      | 1         | 0.94%   |
| Mini pc     | 1         | 0.94%   |
| Server      | 1         | 0.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 106       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 24        | 22.22%  |
| 16.01-24.0      | 23        | 21.3%   |
| 8.01-16.0       | 21        | 19.44%  |
| 3.01-4.0        | 20        | 18.52%  |
| 32.01-64.0      | 10        | 9.26%   |
| 1.01-2.0        | 4         | 3.7%    |
| 64.01-256.0     | 2         | 1.85%   |
| More than 256.0 | 1         | 0.93%   |
| 24.01-32.0      | 1         | 0.93%   |
| 2.01-3.0        | 1         | 0.93%   |
| 0.51-1.0        | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 32        | 27.83%  |
| 2.01-3.0    | 28        | 24.35%  |
| 0.51-1.0    | 19        | 16.52%  |
| 4.01-8.0    | 13        | 11.3%   |
| 3.01-4.0    | 10        | 8.7%    |
| 8.01-16.0   | 7         | 6.09%   |
| 16.01-24.0  | 3         | 2.61%   |
| 0.01-0.5    | 2         | 1.74%   |
| 64.01-256.0 | 1         | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 60.75%  |
| 2      | 24        | 22.43%  |
| 3      | 15        | 14.02%  |
| 9      | 1         | 0.93%   |
| 5      | 1         | 0.93%   |
| 4      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 75.47%  |
| Yes       | 26        | 24.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 83.96%  |
| No        | 17        | 16.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 70.75%  |
| No        | 31        | 29.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 59.81%  |
| No        | 43        | 40.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 21        | 19.81%  |
| Germany            | 9         | 8.49%   |
| Russia             | 8         | 7.55%   |
| India              | 8         | 7.55%   |
| Brazil             | 7         | 6.6%    |
| Czechia            | 6         | 5.66%   |
| Denmark            | 5         | 4.72%   |
| Ukraine            | 4         | 3.77%   |
| UK                 | 4         | 3.77%   |
| Switzerland        | 3         | 2.83%   |
| Poland             | 3         | 2.83%   |
| France             | 3         | 2.83%   |
| Bulgaria           | 3         | 2.83%   |
| Turkey             | 2         | 1.89%   |
| Spain              | 2         | 1.89%   |
| Netherlands        | 2         | 1.89%   |
| Greece             | 2         | 1.89%   |
| Australia          | 2         | 1.89%   |
| Vietnam            | 1         | 0.94%   |
| Sweden             | 1         | 0.94%   |
| Peru               | 1         | 0.94%   |
| Norway             | 1         | 0.94%   |
| New Zealand        | 1         | 0.94%   |
| Honduras           | 1         | 0.94%   |
| Ecuador            | 1         | 0.94%   |
| Dominican Republic | 1         | 0.94%   |
| Canada             | 1         | 0.94%   |
| Belgium            | 1         | 0.94%   |
| Bangladesh         | 1         | 0.94%   |
| Argentina          | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Prague         | 5         | 4.59%   |
| Denver         | 3         | 2.75%   |
| St Petersburg  | 2         | 1.83%   |
| Sofia          | 2         | 1.83%   |
| Munich         | 2         | 1.83%   |
| Moscow         | 2         | 1.83%   |
| Lublin         | 2         | 1.83%   |
| Hyderabad      | 2         | 1.83%   |
| Geneva         | 2         | 1.83%   |
| Amsterdam      | 2         | 1.83%   |
| Zagnansk       | 1         | 0.92%   |
| Yekaterinburg  | 1         | 0.92%   |
| Yambol         | 1         | 0.92%   |
| Weatherford    | 1         | 0.92%   |
| Vlaardingen    | 1         | 0.92%   |
| Viby J         | 1         | 0.92%   |
| Varna          | 1         | 0.92%   |
| Trujillo       | 1         | 0.92%   |
| Toulouse       | 1         | 0.92%   |
| Toms River     | 1         | 0.92%   |
| Tegucigalpa    | 1         | 0.92%   |
| Syktyvkar      | 1         | 0.92%   |
| Stratford      | 1         | 0.92%   |
| South Shields  | 1         | 0.92%   |
| Solone         | 1         | 0.92%   |
| Sistranda      | 1         | 0.92%   |
| Saxtons River  | 1         | 0.92%   |
| Sao Paulo      | 1         | 0.92%   |
| Santo Domingo  | 1         | 0.92%   |
| Saint Paul     | 1         | 0.92%   |
| Rostock        | 1         | 0.92%   |
| Rosenheim      | 1         | 0.92%   |
| Rosario        | 1         | 0.92%   |
| Rio de Janeiro | 1         | 0.92%   |
| Richmond       | 1         | 0.92%   |
| Regensburg     | 1         | 0.92%   |
| Pyatigorsk     | 1         | 0.92%   |
| Pune           | 1         | 0.92%   |
| Porto Alegre   | 1         | 0.92%   |
| Pliening       | 1         | 0.92%   |
| Phoenix        | 1         | 0.92%   |
| Pelabravo      | 1         | 0.92%   |
| Paris          | 1         | 0.92%   |
| Pardubice      | 1         | 0.92%   |
| Orlando        | 1         | 0.92%   |
| Odense         | 1         | 0.92%   |
| New York       | 1         | 0.92%   |
| New Delhi      | 1         | 0.92%   |
| Mossoro        | 1         | 0.92%   |
| Monaca         | 1         | 0.92%   |
| Milford        | 1         | 0.92%   |
| Miedziana Gora | 1         | 0.92%   |
| Mer            | 1         | 0.92%   |
| Melbourne      | 1         | 0.92%   |
| Matos Costa    | 1         | 0.92%   |
| Los Angeles    | 1         | 0.92%   |
| Lakewood       | 1         | 0.92%   |
| Kremenchug     | 1         | 0.92%   |
| Kolkata        | 1         | 0.92%   |
| Izmir          | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 44     | 21.29%  |
| WDC                 | 29        | 36     | 18.71%  |
| Seagate             | 26        | 30     | 16.77%  |
| Toshiba             | 9         | 10     | 5.81%   |
| Kingston            | 8         | 8      | 5.16%   |
| SanDisk             | 7         | 8      | 4.52%   |
| Unknown             | 6         | 11     | 3.87%   |
| Intel               | 6         | 8      | 3.87%   |
| HGST                | 5         | 6      | 3.23%   |
| Hitachi             | 3         | 3      | 1.94%   |
| Crucial             | 3         | 4      | 1.94%   |
| SK Hynix            | 2         | 2      | 1.29%   |
| Phison              | 2         | 2      | 1.29%   |
| Patriot             | 2         | 2      | 1.29%   |
| Corsair             | 2         | 2      | 1.29%   |
| A-DATA Technology   | 2         | 3      | 1.29%   |
| XPG                 | 1         | 4      | 0.65%   |
| Transcend           | 1         | 1      | 0.65%   |
| SPCC                | 1         | 1      | 0.65%   |
| OCZ                 | 1         | 1      | 0.65%   |
| MAXTOR              | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Gigabyte Technology | 1         | 2      | 0.65%   |
| China               | 1         | 1      | 0.65%   |
| BHT                 | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 5         | 2.94%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.76%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.76%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 1.76%   |
| Kingston SHFS37A120G 120GB SSD          | 3         | 1.76%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.18%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 1.18%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.18%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 1.18%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 1.18%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.18%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.18%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.18%   |
| Patriot Burst 120GB SSD                 | 2         | 1.18%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.18%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 1.18%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.18%   |
| XPG NVMe SSD Drive 2TB                  | 1         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.59%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.59%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.59%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.59%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.59%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.59%   |
| WDC WD3200AAKS-22SBA0 320GB             | 1         | 0.59%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.59%   |
| WDC WD20EZBX-00AYRA0 2TB                | 1         | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.59%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.59%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 0.59%   |
| WDC WD15EARS-00MVWB0 1TB                | 1         | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.59%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.59%   |
| WDC WD10JPVX-08JC3T6 1TB                | 1         | 0.59%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.59%   |
| WDC WD10EZRX-00L4HB0 1TB                | 1         | 0.59%   |
| WDC WD10EFRX-68PJCN0 1TB                | 1         | 0.59%   |
| WDC WD10EFRX-68FYTN0 1TB                | 1         | 0.59%   |
| WDC WD10EARX-00PASB0 1TB                | 1         | 0.59%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 0.59%   |
| WDC WD1001FALS-00K1B0 1TB               | 1         | 0.59%   |
| WDC WD Elements 500GB                   | 1         | 0.59%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 0.59%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.59%   |
| Unknown USB DISK 3.2 250GB              | 1         | 0.59%   |
| Unknown SD512  512MB                    | 1         | 0.59%   |
| Unknown SD16G  16GB                     | 1         | 0.59%   |
| Unknown MMC Card  8GB                   | 1         | 0.59%   |
| Unknown MMC Card  7GB                   | 1         | 0.59%   |
| Unknown MMC Card  32GB                  | 1         | 0.59%   |
| Unknown MMC Card  128GB                 | 1         | 0.59%   |
| Unknown MMC Card                        | 1         | 0.59%   |
| Unknown CWBC3R  64GB                    | 1         | 0.59%   |
| Transcend TS128GMTS800 128GB SSD        | 1         | 0.59%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 36.11%  |
| WDC                 | 24        | 30     | 33.33%  |
| Toshiba             | 8         | 9      | 11.11%  |
| Samsung Electronics | 5         | 5      | 6.94%   |
| HGST                | 5         | 6      | 6.94%   |
| Hitachi             | 3         | 3      | 4.17%   |
| MAXTOR              | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 28.57%  |
| Kingston            | 7         | 7      | 16.67%  |
| SanDisk             | 5         | 5      | 11.9%   |
| WDC                 | 2         | 2      | 4.76%   |
| Patriot             | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| Crucial             | 2         | 3      | 4.76%   |
| Transcend           | 1         | 1      | 2.38%   |
| SPCC                | 1         | 1      | 2.38%   |
| OCZ                 | 1         | 1      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| Gigabyte Technology | 1         | 2      | 2.38%   |
| Corsair             | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| BHT                 | 1         | 1      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 2      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 59        | 84     | 42.75%  |
| SSD     | 39        | 47     | 28.26%  |
| NVMe    | 33        | 50     | 23.91%  |
| MMC     | 5         | 9      | 3.62%   |
| Unknown | 2         | 3      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 129    | 65.85%  |
| NVMe | 33        | 50     | 26.83%  |
| MMC  | 5         | 9      | 4.07%   |
| SAS  | 4         | 5      | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 71     | 52.88%  |
| 0.51-1.0   | 35        | 42     | 33.65%  |
| 1.01-2.0   | 11        | 14     | 10.58%  |
| 4.01-10.0  | 2         | 2      | 1.92%   |
| 3.01-4.0   | 1         | 2      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 27        | 24.77%  |
| 501-1000       | 22        | 20.18%  |
| 101-250        | 20        | 18.35%  |
| Unknown        | 11        | 10.09%  |
| 1001-2000      | 10        | 9.17%   |
| More than 3000 | 6         | 5.5%    |
| 1-20           | 4         | 3.67%   |
| 21-50          | 3         | 2.75%   |
| 2001-3000      | 3         | 2.75%   |
| 51-100         | 3         | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 23.89%  |
| 1-20           | 27        | 23.89%  |
| 21-50          | 15        | 13.27%  |
| 251-500        | 11        | 9.73%   |
| Unknown        | 11        | 9.73%   |
| 51-100         | 10        | 8.85%   |
| 1001-2000      | 5         | 4.42%   |
| 501-1000       | 4         | 3.54%   |
| More than 3000 | 2         | 1.77%   |
| 2001-3000      | 1         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 8%      |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 2      | 4%      |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1         | 1      | 4%      |
| WDC WD1600BEVS-60VAT0 160GB         | 1         | 1      | 4%      |
| WDC WD10EZEX-08WN4A0 1TB            | 1         | 1      | 4%      |
| Toshiba MQ04ABF100 1TB              | 1         | 2      | 4%      |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 4%      |
| Seagate ST9750420AS 752GB           | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB           | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 4%      |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 4%      |
| Seagate ST3750330AS 752GB           | 1         | 1      | 4%      |
| Seagate ST3160318AS 160GB           | 1         | 1      | 4%      |
| Seagate ST2000VX000-1CU164 2TB      | 1         | 1      | 4%      |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 4%      |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 4%      |
| Samsung Electronics HD502HJ 500GB   | 1         | 1      | 4%      |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 4%      |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 4%      |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 4%      |
| A-DATA Technology SU700 120GB SSD   | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 37.5%   |
| WDC                 | 4         | 5      | 16.67%  |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 3      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 39.13%  |
| WDC                 | 4         | 5      | 17.39%  |
| Samsung Electronics | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 3      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 26     | 95.65%  |
| SSD  | 1         | 1      | 4.35%   |

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
| Works    | 65        | 95     | 50.78%  |
| Detected | 41        | 71     | 32.03%  |
| Malfunc  | 22        | 27     | 17.19%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 41.98%  |
| AMD                              | 36        | 27.48%  |
| Samsung Electronics              | 20        | 15.27%  |
| Sandisk                          | 4         | 3.05%   |
| Phison Electronics               | 3         | 2.29%   |
| SK Hynix                         | 2         | 1.53%   |
| ADATA Technology                 | 2         | 1.53%   |
| Toshiba America Info Systems     | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] | 1         | 0.76%   |
| Nvidia                           | 1         | 0.76%   |
| Micron/Crucial Technology        | 1         | 0.76%   |
| Marvell Technology Group         | 1         | 0.76%   |
| LSI Logic / Symbios Logic        | 1         | 0.76%   |
| Kingston Technology Company      | 1         | 0.76%   |
| JMicron Technology               | 1         | 0.76%   |
| ASMedia Technology               | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 17.01%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 8.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.8%    |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 2.72%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.04%   |
| Intel SSD 660P Series                                                            | 3         | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 2.04%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.36%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.36%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.36%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 1.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.68%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.68%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.68%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.68%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.68%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.68%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                      | 1         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.68%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.68%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.68%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.68%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1         | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 0.68%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.68%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.68%   |
| AMD SB600 IDE                                                                    | 1         | 0.68%   |
| AMD FCH SATA Controller D                                                        | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 81        | 61.83%  |
| NVMe | 34        | 25.95%  |
| IDE  | 9         | 6.87%   |
| RAID | 7         | 5.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 62        | 58.49%  |
| AMD                      | 41        | 38.68%  |
| ARM                      | 2         | 1.89%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.94%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 3.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.89%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.89%   |
| ARM Processor                                      | 2         | 1.89%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.89%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.89%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 2         | 1.89%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.89%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.89%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.94%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.94%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.94%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.94%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.94%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.94%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.94%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 1         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 0.94%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz                  | 1         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 1         | 0.94%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 0.94%   |
| Intel Core i7-4600U CPU @ 2.10GHz                  | 1         | 0.94%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 1         | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 0.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 0.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 1         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz                  | 1         | 0.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1         | 0.94%   |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz                  | 1         | 0.94%   |
| Intel Core i5-4278U CPU @ 2.60GHz                  | 1         | 0.94%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 1         | 0.94%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz                  | 1         | 0.94%   |
| Intel Core i5-3317U CPU @ 1.70GHz                  | 1         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 1         | 0.94%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1         | 0.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz                  | 1         | 0.94%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz                  | 1         | 0.94%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 1         | 0.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz                  | 1         | 0.94%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1         | 0.94%   |
| Intel Core i3-3217U CPU @ 1.80GHz                  | 1         | 0.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 1         | 0.94%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz               | 1         | 0.94%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1         | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz                  | 1         | 0.94%   |
| Intel Celeron J4005 CPU @ 2.00GHz                  | 1         | 0.94%   |
| Intel Celeron CPU 847 @ 1.10GHz                    | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 20.75%  |
| AMD Ryzen 5             | 14        | 13.21%  |
| Intel Core i7           | 13        | 12.26%  |
| Intel Core i3           | 9         | 8.49%   |
| AMD Ryzen 7             | 9         | 8.49%   |
| Other                   | 7         | 6.6%    |
| Intel Celeron           | 4         | 3.77%   |
| Intel Atom              | 3         | 2.83%   |
| Intel Pentium           | 2         | 1.89%   |
| Intel Core 2 Duo        | 2         | 1.89%   |
| AMD Ryzen 7 PRO         | 2         | 1.89%   |
| AMD FX                  | 2         | 1.89%   |
| AMD A8                  | 2         | 1.89%   |
| Intel Xeon              | 1         | 0.94%   |
| Intel Pentium Gold      | 1         | 0.94%   |
| Intel Pentium 4         | 1         | 0.94%   |
| Intel Genuine           | 1         | 0.94%   |
| Intel Core i9           | 1         | 0.94%   |
| AMD Turion 64 X2 Mobile | 1         | 0.94%   |
| AMD Ryzen Threadripper  | 1         | 0.94%   |
| AMD Ryzen 3             | 1         | 0.94%   |
| AMD Phenom II X4        | 1         | 0.94%   |
| AMD E2                  | 1         | 0.94%   |
| AMD E1                  | 1         | 0.94%   |
| AMD C-60                | 1         | 0.94%   |
| AMD Athlon II X3        | 1         | 0.94%   |
| AMD Athlon II X2        | 1         | 0.94%   |
| AMD A4                  | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 35.85%  |
| 4      | 37        | 34.91%  |
| 6      | 14        | 13.21%  |
| 8      | 12        | 11.32%  |
| 1      | 3         | 2.83%   |
| 64     | 1         | 0.94%   |
| 3      | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 98.11%  |
| 2      | 2         | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 68        | 64.15%  |
| 1      | 37        | 34.91%  |
| 4      | 1         | 0.94%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 89.62%  |
| Unknown        | 7         | 6.6%    |
| 64-bit         | 2         | 1.89%   |
| 32-bit         | 2         | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 32.11%  |
| 0x40651    | 6         | 5.5%    |
| 0x306a9    | 5         | 4.59%   |
| 0x906ea    | 4         | 3.67%   |
| 0x906e9    | 3         | 2.75%   |
| 0x806ea    | 3         | 2.75%   |
| 0x806e9    | 3         | 2.75%   |
| 0x406e3    | 3         | 2.75%   |
| 0x08600104 | 3         | 2.75%   |
| 0x08108102 | 3         | 2.75%   |
| 0x806ec    | 2         | 1.83%   |
| 0x206a7    | 2         | 1.83%   |
| 0x0a201009 | 2         | 1.83%   |
| 0x08701021 | 2         | 1.83%   |
| 0x0800820d | 2         | 1.83%   |
| 0x07030105 | 2         | 1.83%   |
| 0x06000852 | 2         | 1.83%   |
| 0x05000119 | 2         | 1.83%   |
| 0x010000c8 | 2         | 1.83%   |
| 0x906ed    | 1         | 0.92%   |
| 0x806eb    | 1         | 0.92%   |
| 0x706a1    | 1         | 0.92%   |
| 0x506e3    | 1         | 0.92%   |
| 0x406c4    | 1         | 0.92%   |
| 0x306c3    | 1         | 0.92%   |
| 0x30678    | 1         | 0.92%   |
| 0x106c2    | 1         | 0.92%   |
| 0x106a5    | 1         | 0.92%   |
| 0x1067a    | 1         | 0.92%   |
| 0x0a50000c | 1         | 0.92%   |
| 0x0a201205 | 1         | 0.92%   |
| 0x08701013 | 1         | 0.92%   |
| 0x08608102 | 1         | 0.92%   |
| 0x08600106 | 1         | 0.92%   |
| 0x08600102 | 1         | 0.92%   |
| 0x08108109 | 1         | 0.92%   |
| 0x08101007 | 1         | 0.92%   |
| 0x08001138 | 1         | 0.92%   |
| 0x08001136 | 1         | 0.92%   |
| 0x08001129 | 1         | 0.92%   |
| 0x07030104 | 1         | 0.92%   |
| 0x06006705 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 21.7%   |
| Zen 2         | 9         | 8.49%   |
| IvyBridge     | 8         | 7.55%   |
| Haswell       | 8         | 7.55%   |
| Zen+          | 7         | 6.6%    |
| Zen 3         | 6         | 5.66%   |
| Skylake       | 6         | 5.66%   |
| Zen           | 4         | 3.77%   |
| Unknown       | 4         | 3.77%   |
| Silvermont    | 3         | 2.83%   |
| SandyBridge   | 3         | 2.83%   |
| Puma          | 3         | 2.83%   |
| K10           | 3         | 2.83%   |
| Excavator     | 3         | 2.83%   |
| TigerLake     | 2         | 1.89%   |
| Piledriver    | 2         | 1.89%   |
| Penryn        | 2         | 1.89%   |
| Goldmont plus | 2         | 1.89%   |
| Bobcat        | 2         | 1.89%   |
| NetBurst      | 1         | 0.94%   |
| Nehalem       | 1         | 0.94%   |
| K8 Hammer     | 1         | 0.94%   |
| IceLake       | 1         | 0.94%   |
| Core          | 1         | 0.94%   |
| Bonnell       | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 38.89%  |
| Nvidia                           | 37        | 29.37%  |
| AMD                              | 37        | 29.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |
| Matrox Electronics Systems       | 1         | 0.79%   |
| ASPEED Technology                | 1         | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 5.38%   |
| AMD Renoir                                                                               | 6         | 4.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 3.08%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.31%   |
| Intel HD Graphics 620                                                                    | 3         | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.31%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.31%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.54%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.54%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.54%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.77%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.77%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.77%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.77%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.77%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                                     | 1         | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.77%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.77%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                                     | 1         | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.77%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.77%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1         | 0.77%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.77%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1         | 0.77%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 1         | 0.77%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.77%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.77%   |
| Intel HD Graphics 630                                                                    | 1         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 0.77%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1         | 0.77%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.77%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.77%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 29.63%  |
| 1 x AMD        | 31        | 28.7%   |
| 1 x Nvidia     | 19        | 17.59%  |
| Intel + Nvidia | 15        | 13.89%  |
| Other          | 2         | 1.85%   |
| 2 x AMD        | 2         | 1.85%   |
| AMD + Nvidia   | 2         | 1.85%   |
| 2 x Nvidia     | 1         | 0.93%   |
| 1 x SiS        | 1         | 0.93%   |
| 1 x Matrox     | 1         | 0.93%   |
| Intel + AMD    | 1         | 0.93%   |
| AMD + ASPEED   | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 68.52%  |
| Proprietary | 31        | 28.7%   |
| Unknown     | 3         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 52.25%  |
| 1.01-2.0   | 15        | 13.51%  |
| 0.01-0.5   | 11        | 9.91%   |
| 3.01-4.0   | 9         | 8.11%   |
| 0.51-1.0   | 7         | 6.31%   |
| 5.01-6.0   | 4         | 3.6%    |
| 7.01-8.0   | 2         | 1.8%    |
| 2.01-3.0   | 2         | 1.8%    |
| 8.01-16.0  | 2         | 1.8%    |
| 16.01-24.0 | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 16        | 13.91%  |
| Chimei Innolux       | 14        | 12.17%  |
| BOE                  | 12        | 10.43%  |
| LG Display           | 11        | 9.57%   |
| Samsung Electronics  | 9         | 7.83%   |
| Hewlett-Packard      | 8         | 6.96%   |
| Dell                 | 6         | 5.22%   |
| Philips              | 4         | 3.48%   |
| Iiyama               | 4         | 3.48%   |
| Acer                 | 4         | 3.48%   |
| BenQ                 | 3         | 2.61%   |
| PANDA                | 2         | 1.74%   |
| Lenovo               | 2         | 1.74%   |
| Goldstar             | 2         | 1.74%   |
| Fujitsu Siemens      | 2         | 1.74%   |
| Apple                | 2         | 1.74%   |
| AOC                  | 2         | 1.74%   |
| Ancor Communications | 2         | 1.74%   |
| Unknown              | 1         | 0.87%   |
| STD                  | 1         | 0.87%   |
| Sceptre Tech         | 1         | 0.87%   |
| Sceptre              | 1         | 0.87%   |
| Panasonic            | 1         | 0.87%   |
| ONN                  | 1         | 0.87%   |
| MSI                  | 1         | 0.87%   |
| LG Philips           | 1         | 0.87%   |
| FUN                  | 1         | 0.87%   |
| CHR                  | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.48%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2         | 1.65%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.65%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.65%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.83%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.83%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.83%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.83%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.83%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 0.83%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.83%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.83%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.83%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.83%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.83%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.83%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 0.83%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| Panasonic TV MEIA296 1360x768                                         | 1         | 0.83%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.83%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.83%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.83%   |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1         | 0.83%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch               | 1         | 0.83%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 1         | 0.83%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1         | 0.83%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1         | 0.83%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1         | 0.83%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1         | 0.83%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 0.83%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1         | 0.83%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.83%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1         | 0.83%   |
| FUN HDMI Monitor FUN9D31 3840x2160 480x270mm 21.7-inch                | 1         | 0.83%   |
| Fujitsu Siemens SL27T-1 LED FUS07E4 1920x1080 598x336mm 27.0-inch     | 1         | 0.83%   |
| Fujitsu Siemens E19-06SA FUS0742 1280x1024 376x301mm 19.0-inch        | 1         | 0.83%   |
| Dell U3818DW DELA0F4 3840x1600 880x367mm 37.5-inch                    | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 44.74%  |
| 1366x768 (WXGA)    | 23        | 20.18%  |
| 1920x1200 (WUXGA)  | 5         | 4.39%   |
| 3840x2160 (4K)     | 4         | 3.51%   |
| 2560x1440 (QHD)    | 4         | 3.51%   |
| 1680x1050 (WSXGA+) | 4         | 3.51%   |
| 3440x1440          | 3         | 2.63%   |
| 2160x1440          | 3         | 2.63%   |
| 1600x900 (HD+)     | 3         | 2.63%   |
| Unknown            | 3         | 2.63%   |
| 1280x800 (WXGA)    | 2         | 1.75%   |
| 1280x1024 (SXGA)   | 2         | 1.75%   |
| 7680x1080          | 1         | 0.88%   |
| 3840x1600          | 1         | 0.88%   |
| 3840x1080          | 1         | 0.88%   |
| 2560x1600          | 1         | 0.88%   |
| 2256x1504          | 1         | 0.88%   |
| 1360x768           | 1         | 0.88%   |
| 1024x600           | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 24.79%  |
| 24      | 13        | 11.11%  |
| 13      | 13        | 11.11%  |
| 14      | 11        | 9.4%    |
| Unknown | 11        | 9.4%    |
| 23      | 6         | 5.13%   |
| 21      | 5         | 4.27%   |
| 27      | 4         | 3.42%   |
| 22      | 4         | 3.42%   |
| 34      | 3         | 2.56%   |
| 12      | 3         | 2.56%   |
| 17      | 2         | 1.71%   |
| 11      | 2         | 1.71%   |
| 84      | 1         | 0.85%   |
| 40      | 1         | 0.85%   |
| 39      | 1         | 0.85%   |
| 37      | 1         | 0.85%   |
| 33      | 1         | 0.85%   |
| 31      | 1         | 0.85%   |
| 25      | 1         | 0.85%   |
| 20      | 1         | 0.85%   |
| 19      | 1         | 0.85%   |
| 18      | 1         | 0.85%   |
| 8       | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 38.79%  |
| 501-600     | 23        | 19.83%  |
| 201-300     | 14        | 12.07%  |
| 401-500     | 11        | 9.48%   |
| Unknown     | 11        | 9.48%   |
| 701-800     | 4         | 3.45%   |
| 801-900     | 3         | 2.59%   |
| 351-400     | 2         | 1.72%   |
| 601-700     | 1         | 0.86%   |
| 1501-2000   | 1         | 0.86%   |
| 101-200     | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 69.72%  |
| 16/10   | 13        | 11.93%  |
| Unknown | 10        | 9.17%   |
| 3/2     | 4         | 3.67%   |
| 21/9    | 4         | 3.67%   |
| 5/4     | 2         | 1.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 24.79%  |
| 81-90          | 19        | 16.24%  |
| 201-250        | 19        | 16.24%  |
| Unknown        | 11        | 9.4%    |
| 251-300        | 9         | 7.69%   |
| 71-80          | 6         | 5.13%   |
| 351-500        | 5         | 4.27%   |
| 301-350        | 4         | 3.42%   |
| 61-70          | 3         | 2.56%   |
| 501-1000       | 3         | 2.56%   |
| 51-60          | 2         | 1.71%   |
| 151-200        | 2         | 1.71%   |
| 141-150        | 2         | 1.71%   |
| More than 1000 | 1         | 0.85%   |
| 1-40           | 1         | 0.85%   |
| 131-140        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 36        | 30.77%  |
| 101-120       | 30        | 25.64%  |
| 121-160       | 27        | 23.08%  |
| 161-240       | 12        | 10.26%  |
| Unknown       | 11        | 9.4%    |
| More than 240 | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 85        | 79.44%  |
| 2     | 20        | 18.69%  |
| 0     | 2         | 1.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 58        | 38.93%  |
| Intel                            | 43        | 28.86%  |
| Qualcomm Atheros                 | 14        | 9.4%    |
| Broadcom                         | 9         | 6.04%   |
| TP-Link                          | 3         | 2.01%   |
| Sierra Wireless                  | 3         | 2.01%   |
| Ralink Technology                | 3         | 2.01%   |
| Qualcomm Atheros Communications  | 2         | 1.34%   |
| Cypress Semiconductor            | 2         | 1.34%   |
| Broadcom Limited                 | 2         | 1.34%   |
| Xiaomi                           | 1         | 0.67%   |
| Tenda                            | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.67%   |
| Ralink                           | 1         | 0.67%   |
| Nvidia                           | 1         | 0.67%   |
| MediaTek                         | 1         | 0.67%   |
| DisplayLink                      | 1         | 0.67%   |
| ASIX Electronics                 | 1         | 0.67%   |
| Arduino SA                       | 1         | 0.67%   |
| Apple                            | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 23.43%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4%      |
| Intel Wireless 8265 / 8275                                        | 6         | 3.43%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.71%   |
| Intel Wireless 8260                                               | 3         | 1.71%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.71%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.14%   |
| Intel Wireless 7260                                               | 2         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.14%   |
| Cypress K38231_03                                                 | 2         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.57%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.57%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.57%   |
| Tenda U12                                                         | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.57%   |
| Sierra Wireless EM7455                                            | 1         | 0.57%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.57%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.57%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 0.57%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.57%   |
| MediaTek Vodafone Smart N10                                       | 1         | 0.57%   |
| Intel Wireless-AC 9260                                            | 1         | 0.57%   |
| Intel WiFi Link 5100                                              | 1         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.57%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.57%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 40.51%  |
| Realtek Semiconductor           | 17        | 21.52%  |
| Qualcomm Atheros                | 12        | 15.19%  |
| Broadcom                        | 4         | 5.06%   |
| Sierra Wireless                 | 3         | 3.8%    |
| Ralink Technology               | 3         | 3.8%    |
| TP-Link                         | 2         | 2.53%   |
| Qualcomm Atheros Communications | 2         | 2.53%   |
| Broadcom Limited                | 2         | 2.53%   |
| Tenda                           | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 10        | 12.66%  |
| Intel Wireless 8265 / 8275                                 | 6         | 7.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 4         | 5.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 4         | 5.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 5.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 5.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3         | 3.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 3         | 3.8%    |
| Intel Wireless 8260                                        | 3         | 3.8%    |
| Intel Cannon Lake PCH CNVi WiFi                            | 3         | 3.8%    |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 2.53%   |
| Ralink MT7601U Wireless Adapter                            | 2         | 2.53%   |
| Qualcomm Atheros AR9271 802.11n                            | 2         | 2.53%   |
| Intel Wireless 7260                                        | 2         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 2.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 2         | 2.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1         | 1.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 1.27%   |
| Tenda U12                                                  | 1         | 1.27%   |
| Sierra Wireless EM7455                                     | 1         | 1.27%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 1.27%   |
| Sierra Wireless EM7305 Modem                               | 1         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 1.27%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter   | 1         | 1.27%   |
| Ralink RT5572 Wireless Adapter                             | 1         | 1.27%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.27%   |
| Intel Wireless-AC 9260                                     | 1         | 1.27%   |
| Intel WiFi Link 5100                                       | 1         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.27%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 1.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 1.27%   |
| Broadcom BCM4311 802.11b/g WLAN                            | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 53        | 55.79%  |
| Intel                            | 23        | 24.21%  |
| Broadcom                         | 6         | 6.32%   |
| Qualcomm Atheros                 | 3         | 3.16%   |
| Cypress Semiconductor            | 2         | 2.11%   |
| Xiaomi                           | 1         | 1.05%   |
| TP-Link                          | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 1.05%   |
| Nvidia                           | 1         | 1.05%   |
| MediaTek                         | 1         | 1.05%   |
| DisplayLink                      | 1         | 1.05%   |
| ASIX Electronics                 | 1         | 1.05%   |
| Apple                            | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 43.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.37%   |
| Intel I211 Gigabit Network Connection                             | 5         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.16%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.16%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.11%   |
| Cypress K38231_03                                                 | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.05%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.05%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.05%   |
| MediaTek Vodafone Smart N10                                       | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.05%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 1.05%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.05%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.05%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.05%   |
| Apple iPad 4/Mini1                                                | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 53.94%  |
| WiFi     | 75        | 45.45%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 58.88%  |
| Ethernet | 44        | 41.12%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 49.06%  |
| 2     | 46        | 43.4%   |
| 0     | 4         | 3.77%   |
| 3     | 3         | 2.83%   |
| 4     | 1         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 96        | 88.89%  |
| Yes  | 12        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 43.94%  |
| Realtek Semiconductor           | 10        | 15.15%  |
| Lite-On Technology              | 5         | 7.58%   |
| Cambridge Silicon Radio         | 5         | 7.58%   |
| Broadcom                        | 5         | 7.58%   |
| Qualcomm Atheros Communications | 3         | 4.55%   |
| IMC Networks                    | 3         | 4.55%   |
| Realtek                         | 2         | 3.03%   |
| Foxconn / Hon Hai               | 2         | 3.03%   |
| Dell                            | 1         | 1.52%   |
| Apple                           | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 16.67%  |
| Intel AX200 Bluetooth                               | 10        | 15.15%  |
| Realtek Bluetooth Radio                             | 6         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 7.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.55%   |
| Realtek Bluetooth Radio                             | 2         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.03%   |
| Intel AX201 Bluetooth                               | 2         | 3.03%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.03%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.52%   |
| Intel AX210 Bluetooth                               | 1         | 1.52%   |
| IMC Networks Bluetooth Device                       | 1         | 1.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.52%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.52%   |
| Broadcom HP Portable Valentine                      | 1         | 1.52%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.52%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.52%   |
| Apple Bluetooth Host Controller                     | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 57        | 39.04%  |
| AMD                              | 43        | 29.45%  |
| Nvidia                           | 26        | 17.81%  |
| Logitech                         | 3         | 2.05%   |
| JMTek                            | 3         | 2.05%   |
| C-Media Electronics              | 3         | 2.05%   |
| Texas Instruments                | 2         | 1.37%   |
| VIA Technologies                 | 1         | 0.68%   |
| Unknown                          | 1         | 0.68%   |
| SteelSeries ApS                  | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| SAVITECH                         | 1         | 0.68%   |
| Focusrite-Novation               | 1         | 0.68%   |
| Elgato Systems                   | 1         | 0.68%   |
| Creative Technology              | 1         | 0.68%   |
| Cambridge Audio                  | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 6.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 6.56%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 4.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 3.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.83%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.19%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.19%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.64%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 1.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.64%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.64%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.09%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.09%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.09%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                                | 1         | 0.55%   |
| Unknown USB Audio                                                                                 | 1         | 0.55%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.55%   |
| SAVITECH SA9023 audio controller                                                                  | 1         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.55%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.55%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.55%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Logitech G633 Gaming Headset                                                                      | 1         | 0.55%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.55%   |
| Logitech Blue Snowball                                                                            | 1         | 0.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.55%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.55%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                                 | 1         | 0.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 20        | 23.53%  |
| Samsung Electronics | 20        | 23.53%  |
| Kingston            | 9         | 10.59%  |
| Micron Technology   | 8         | 9.41%   |
| G.Skill             | 6         | 7.06%   |
| Unknown             | 5         | 5.88%   |
| Corsair             | 5         | 5.88%   |
| A-DATA Technology   | 5         | 5.88%   |
| Crucial             | 2         | 2.35%   |
| Transcend           | 1         | 1.18%   |
| Ramaxel Technology  | 1         | 1.18%   |
| Patriot             | 1         | 1.18%   |
| Elpida              | 1         | 1.18%   |
| Avant               | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.13%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 2.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.13%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.13%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.06%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.06%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.06%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.06%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 4096MB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.06%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.06%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 1.06%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s              | 1         | 1.06%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4096MB SODIMM LPDDR4 3733MT/s        | 1         | 1.06%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.06%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.06%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.06%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s                | 1         | 1.06%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.06%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| Kingston RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 1.06%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s              | 1         | 1.06%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s             | 1         | 1.06%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| Kingston RAM HP16D3LS1KBGH/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Kingston RAM ACR26D4S9S1KA-4 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 38        | 50%     |
| DDR3    | 29        | 38.16%  |
| LPDDR4  | 3         | 3.95%   |
| LPDDR3  | 3         | 3.95%   |
| Unknown | 2         | 2.63%   |
| DDR2    | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 60%     |
| DIMM         | 26        | 34.67%  |
| Row Of Chips | 4         | 5.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 45%     |
| 4096  | 27        | 33.75%  |
| 16384 | 9         | 11.25%  |
| 2048  | 5         | 6.25%   |
| 1024  | 2         | 2.5%    |
| 512   | 1         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 20        | 24.39%  |
| 2667  | 13        | 15.85%  |
| 3200  | 10        | 12.2%   |
| 2400  | 9         | 10.98%  |
| 1333  | 7         | 8.54%   |
| 2133  | 4         | 4.88%   |
| 3600  | 3         | 3.66%   |
| 1334  | 3         | 3.66%   |
| 3000  | 2         | 2.44%   |
| 1867  | 2         | 2.44%   |
| 4266  | 1         | 1.22%   |
| 3866  | 1         | 1.22%   |
| 3733  | 1         | 1.22%   |
| 3333  | 1         | 1.22%   |
| 2933  | 1         | 1.22%   |
| 2800  | 1         | 1.22%   |
| 2666  | 1         | 1.22%   |
| 1067  | 1         | 1.22%   |
| 533   | 1         | 1.22%   |

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
| Chicony Electronics                    | 20        | 27.03%  |
| IMC Networks                           | 13        | 17.57%  |
| Microdia                               | 8         | 10.81%  |
| Realtek Semiconductor                  | 6         | 8.11%   |
| Logitech                               | 6         | 8.11%   |
| Quanta                                 | 5         | 6.76%   |
| Acer                                   | 5         | 6.76%   |
| Sunplus Innovation Technology          | 3         | 4.05%   |
| Suyin                                  | 2         | 2.7%    |
| MacroSilicon                           | 2         | 2.7%    |
| Silicon Motion                         | 1         | 1.35%   |
| Microsoft                              | 1         | 1.35%   |
| GEMBIRD                                | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony integrated camera                         | 6         | 7.89%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 5.26%   |
| Quanta HD User Facing                             | 3         | 3.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 3         | 3.95%   |
| Suyin HP TrueVision HD                            | 2         | 2.63%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 2.63%   |
| Microdia HP Webcam-101                            | 2         | 2.63%   |
| Logitech Webcam C270                              | 2         | 2.63%   |
| IMC Networks HD Camera                            | 2         | 2.63%   |
| Chicony HD WebCam                                 | 2         | 2.63%   |
| Sunplus HP Wide Vision HD                         | 1         | 1.32%   |
| Silicon Motion WebCam SC-10HDD12636N              | 1         | 1.32%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 1.32%   |
| Realtek USB Camera                                | 1         | 1.32%   |
| Realtek Laptop Camera                             | 1         | 1.32%   |
| Realtek Integrated Webcam HD                      | 1         | 1.32%   |
| Realtek HD WebCam                                 | 1         | 1.32%   |
| Realtek FULL HD 1080P Webcam                      | 1         | 1.32%   |
| Quanta VGA WebCam                                 | 1         | 1.32%   |
| Quanta HP TrueVision HD Camera                    | 1         | 1.32%   |
| Microsoft LifeCam HD-3000                         | 1         | 1.32%   |
| Microdia Webcam Vitade AF                         | 1         | 1.32%   |
| Microdia USB Camera                               | 1         | 1.32%   |
| Microdia Sonix USB 2.0 Camera                     | 1         | 1.32%   |
| Microdia Integrated_Webcam_HD                     | 1         | 1.32%   |
| Microdia Integrated_Webcam_2M                     | 1         | 1.32%   |
| Microdia Camera                                   | 1         | 1.32%   |
| MacroSilicon USB Video                            | 1         | 1.32%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1         | 1.32%   |
| Logitech Webcam C930e                             | 1         | 1.32%   |
| Logitech HD Webcam C615                           | 1         | 1.32%   |
| Logitech C922 Pro Stream Webcam                   | 1         | 1.32%   |
| Logitech C505 HD Webcam                           | 1         | 1.32%   |
| IMC Networks VGA UVC WebCam                       | 1         | 1.32%   |
| IMC Networks Integrated Camera                    | 1         | 1.32%   |
| IMC Networks HP TrueVision HD Camera              | 1         | 1.32%   |
| IMC Networks EasyCamera                           | 1         | 1.32%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1         | 1.32%   |
| Chicony WebCam                                    | 1         | 1.32%   |
| Chicony USB2.0 Camera                             | 1         | 1.32%   |
| Chicony USB 5M WebCam                             | 1         | 1.32%   |
| Chicony USB 2.0 Camera                            | 1         | 1.32%   |
| Chicony thinkpad t430s camera                     | 1         | 1.32%   |
| Chicony Lenovo EasyCamera                         | 1         | 1.32%   |
| Chicony Integrated IR Camera                      | 1         | 1.32%   |
| Chicony Integrated Camera (1280x720@30)           | 1         | 1.32%   |
| Chicony HP Wide Vision HD Camera                  | 1         | 1.32%   |
| Chicony HP TrueVision HD Camera                   | 1         | 1.32%   |
| Chicony HP 720p HD Monitor Webcam                 | 1         | 1.32%   |
| Chicony HD WebCam (Acer)                          | 1         | 1.32%   |
| Chicony HD User Facing                            | 1         | 1.32%   |
| Chicony EasyCamera                                | 1         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) Webcam     | 1         | 1.32%   |
| Acer ThinkPad P50 Integrated Camera               | 1         | 1.32%   |
| Acer SunplusIT Integrated Camera                  | 1         | 1.32%   |
| Acer SunplusIT INC. Integrated Camera             | 1         | 1.32%   |
| Acer OrbiCam                                      | 1         | 1.32%   |
| Acer Lenovo EasyCamera                            | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 55.56%  |
| Validity Sensors           | 3         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 3         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 33.33%  |
| Synaptics  WBDI                                   | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device               | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 75%     |
| Broadcom    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 75%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 85        | 79.44%  |
| 1     | 14        | 13.08%  |
| 2     | 6         | 5.61%   |
| 3     | 2         | 1.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 29.03%  |
| Net/wireless          | 5         | 16.13%  |
| Graphics card         | 5         | 16.13%  |
| Chipcard              | 4         | 12.9%   |
| Camera                | 3         | 9.68%   |
| Sound                 | 2         | 6.45%   |
| Multimedia controller | 2         | 6.45%   |
| Net/ethernet          | 1         | 3.23%   |

