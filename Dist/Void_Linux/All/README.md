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

Total: 157

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7e7f71a3c0](https://linux-hardware.org/?probe=7e7f71a3c0) | Jul 23, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [761dd08497](https://linux-hardware.org/?probe=761dd08497) | Jul 23, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP            | 3397                        | Desktop     | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 71        | 58.68%  |
| Void Linux         | 50        | 41.32%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 117       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.13.19_1                              | 7         | 5.56%   |
| 5.8.18_1                               | 5         | 3.97%   |
| 5.3.9_1                                | 4         | 3.17%   |
| 5.16.20_1                              | 4         | 3.17%   |
| 5.10.17_1                              | 4         | 3.17%   |
| 5.8.12_1                               | 3         | 2.38%   |
| 5.18.14_1                              | 3         | 2.38%   |
| 5.15.32_1                              | 3         | 2.38%   |
| 5.13.13_1                              | 3         | 2.38%   |
| 5.12.10_1                              | 3         | 2.38%   |
| 5.9.14_1                               | 2         | 1.59%   |
| 5.4.24_1                               | 2         | 1.59%   |
| 5.4.13_2                               | 2         | 1.59%   |
| 5.18.9_1                               | 2         | 1.59%   |
| 5.15.34_1                              | 2         | 1.59%   |
| 5.15.22_1                              | 2         | 1.59%   |
| 5.15.16_1                              | 2         | 1.59%   |
| 5.13.15_1                              | 2         | 1.59%   |
| 5.13.10_1                              | 2         | 1.59%   |
| 5.12.14_1                              | 2         | 1.59%   |
| 5.11.9_1                               | 2         | 1.59%   |
| 5.10.14_1                              | 2         | 1.59%   |
| 5.9.16_1                               | 1         | 0.79%   |
| 5.9.0-rc8_2                            | 1         | 0.79%   |
| 5.8.9_1                                | 1         | 0.79%   |
| 5.8.8_1                                | 1         | 0.79%   |
| 5.8.7_1                                | 1         | 0.79%   |
| 5.8.6_1                                | 1         | 0.79%   |
| 5.8.5_1                                | 1         | 0.79%   |
| 5.8.16_1                               | 1         | 0.79%   |
| 5.8.14_1                               | 1         | 0.79%   |
| 5.8.12_2                               | 1         | 0.79%   |
| 5.8.11_1                               | 1         | 0.79%   |
| 5.8.10_1                               | 1         | 0.79%   |
| 5.7.16_1                               | 1         | 0.79%   |
| 5.6.14_1                               | 1         | 0.79%   |
| 5.4.35_1                               | 1         | 0.79%   |
| 5.4.21_1                               | 1         | 0.79%   |
| 5.4.15_1                               | 1         | 0.79%   |
| 5.3.16_1                               | 1         | 0.79%   |
| 5.2.13_1                               | 1         | 0.79%   |
| 5.18.7_1                               | 1         | 0.79%   |
| 5.18.1_1                               | 1         | 0.79%   |
| 5.18.16_1                              | 1         | 0.79%   |
| 5.17.0-rc3-next-20220207-g5bd2d473f01f | 1         | 0.79%   |
| 5.15.6_1                               | 1         | 0.79%   |
| 5.15.50_1                              | 1         | 0.79%   |
| 5.15.45_1                              | 1         | 0.79%   |
| 5.15.41_1                              | 1         | 0.79%   |
| 5.15.30_1                              | 1         | 0.79%   |
| 5.15.28_1                              | 1         | 0.79%   |
| 5.15.26_1                              | 1         | 0.79%   |
| 5.15.24_1                              | 1         | 0.79%   |
| 5.15.19_1                              | 1         | 0.79%   |
| 5.15.17_1                              | 1         | 0.79%   |
| 5.15.14_1                              | 1         | 0.79%   |
| 5.15.12_1                              | 1         | 0.79%   |
| 5.15.11_1                              | 1         | 0.79%   |
| 5.14.0_1                               | 1         | 0.79%   |
| 5.13.18_1                              | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 5.56%   |
| 5.8.18  | 5         | 3.97%   |
| 5.8.12  | 4         | 3.17%   |
| 5.3.9   | 4         | 3.17%   |
| 5.16.20 | 4         | 3.17%   |
| 5.10.17 | 4         | 3.17%   |
| 5.18.14 | 3         | 2.38%   |
| 5.15.32 | 3         | 2.38%   |
| 5.13.13 | 3         | 2.38%   |
| 5.12.10 | 3         | 2.38%   |
| 5.9.14  | 2         | 1.59%   |
| 5.4.24  | 2         | 1.59%   |
| 5.4.13  | 2         | 1.59%   |
| 5.18.9  | 2         | 1.59%   |
| 5.15.34 | 2         | 1.59%   |
| 5.15.22 | 2         | 1.59%   |
| 5.15.16 | 2         | 1.59%   |
| 5.13.15 | 2         | 1.59%   |
| 5.13.10 | 2         | 1.59%   |
| 5.12.14 | 2         | 1.59%   |
| 5.11.9  | 2         | 1.59%   |
| 5.10.14 | 2         | 1.59%   |
| 5.9.16  | 1         | 0.79%   |
| 5.9.0   | 1         | 0.79%   |
| 5.8.9   | 1         | 0.79%   |
| 5.8.8   | 1         | 0.79%   |
| 5.8.7   | 1         | 0.79%   |
| 5.8.6   | 1         | 0.79%   |
| 5.8.5   | 1         | 0.79%   |
| 5.8.16  | 1         | 0.79%   |
| 5.8.14  | 1         | 0.79%   |
| 5.8.11  | 1         | 0.79%   |
| 5.8.10  | 1         | 0.79%   |
| 5.7.16  | 1         | 0.79%   |
| 5.6.14  | 1         | 0.79%   |
| 5.4.35  | 1         | 0.79%   |
| 5.4.21  | 1         | 0.79%   |
| 5.4.15  | 1         | 0.79%   |
| 5.3.16  | 1         | 0.79%   |
| 5.2.13  | 1         | 0.79%   |
| 5.18.7  | 1         | 0.79%   |
| 5.18.16 | 1         | 0.79%   |
| 5.18.1  | 1         | 0.79%   |
| 5.17.0  | 1         | 0.79%   |
| 5.15.6  | 1         | 0.79%   |
| 5.15.50 | 1         | 0.79%   |
| 5.15.45 | 1         | 0.79%   |
| 5.15.41 | 1         | 0.79%   |
| 5.15.30 | 1         | 0.79%   |
| 5.15.28 | 1         | 0.79%   |
| 5.15.26 | 1         | 0.79%   |
| 5.15.24 | 1         | 0.79%   |
| 5.15.19 | 1         | 0.79%   |
| 5.15.17 | 1         | 0.79%   |
| 5.15.14 | 1         | 0.79%   |
| 5.15.12 | 1         | 0.79%   |
| 5.15.11 | 1         | 0.79%   |
| 5.14.0  | 1         | 0.79%   |
| 5.13.18 | 1         | 0.79%   |
| 5.13.12 | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 22        | 17.6%   |
| 5.8     | 18        | 14.4%   |
| 5.13    | 16        | 12.8%   |
| 5.10    | 15        | 12%     |
| 5.12    | 9         | 7.2%    |
| 5.18    | 8         | 6.4%    |
| 5.4     | 7         | 5.6%    |
| 5.3     | 5         | 4%      |
| 5.11    | 5         | 4%      |
| 5.9     | 4         | 3.2%    |
| 5.16    | 4         | 3.2%    |
| 4.19    | 4         | 3.2%    |
| 5.7     | 1         | 0.8%    |
| 5.6     | 1         | 0.8%    |
| 5.2     | 1         | 0.8%    |
| 5.17    | 1         | 0.8%    |
| 5.14    | 1         | 0.8%    |
| 5.1     | 1         | 0.8%    |
| 4.4     | 1         | 0.8%    |
| 4.14    | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 107       | 91.45%  |
| i686    | 5         | 4.27%   |
| aarch64 | 2         | 1.71%   |
| ppc64le | 1         | 0.85%   |
| ppc64   | 1         | 0.85%   |
| armv7l  | 1         | 0.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 48.36%  |
| XFCE       | 15        | 12.3%   |
| KDE        | 10        | 8.2%    |
| MATE       | 6         | 4.92%   |
| GNOME      | 6         | 4.92%   |
| KDE5       | 5         | 4.1%    |
| i3         | 5         | 4.1%    |
| X-Cinnamon | 3         | 2.46%   |
| openbox    | 3         | 2.46%   |
| bspwm      | 3         | 2.46%   |
| awesome    | 3         | 2.46%   |
| Lumina     | 2         | 1.64%   |
| sway       | 1         | 0.82%   |
| river      | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 84        | 70.59%  |
| Wayland | 12        | 10.08%  |
| Tty     | 12        | 10.08%  |
| Unknown | 11        | 9.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 89.08%  |
| LightDM | 5         | 4.2%    |
| LXDM    | 4         | 3.36%   |
| SDDM    | 3         | 2.52%   |
| GDM     | 1         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 60        | 49.18%  |
| Unknown | 19        | 15.57%  |
| en_GB   | 7         | 5.74%   |
| en_DK   | 6         | 4.92%   |
| ru_RU   | 5         | 4.1%    |
| fr_FR   | 3         | 2.46%   |
| de_DE   | 3         | 2.46%   |
| pt_BR   | 2         | 1.64%   |
| pl_PL   | 2         | 1.64%   |
| en_AU   | 2         | 1.64%   |
| cs_CZ   | 2         | 1.64%   |
| tr_TR   | 1         | 0.82%   |
| ru_UA   | 1         | 0.82%   |
| nb_NO   | 1         | 0.82%   |
| es_HN   | 1         | 0.82%   |
| es_ES   | 1         | 0.82%   |
| es_DO   | 1         | 0.82%   |
| en_NZ   | 1         | 0.82%   |
| en_IE   | 1         | 0.82%   |
| en_CA   | 1         | 0.82%   |
| el_GR   | 1         | 0.82%   |
| bg_BG   | 1         | 0.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 61        | 50.83%  |
| BIOS | 59        | 49.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 75        | 63.03%  |
| Btrfs   | 24        | 20.17%  |
| Xfs     | 7         | 5.88%   |
| Zfs     | 6         | 5.04%   |
| Unknown | 5         | 4.2%    |
| F2fs    | 1         | 0.84%   |
| Ext3    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 65        | 54.17%  |
| Unknown | 36        | 30%     |
| MBR     | 19        | 15.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 87.18%  |
| Yes       | 15        | 12.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 80.51%  |
| Yes       | 23        | 19.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 27        | 23.08%  |
| Lenovo              | 16        | 13.68%  |
| Hewlett-Packard     | 12        | 10.26%  |
| Acer                | 12        | 10.26%  |
| Dell                | 11        | 9.4%    |
| MSI                 | 8         | 6.84%   |
| ASRock              | 8         | 6.84%   |
| Gigabyte Technology | 4         | 3.42%   |
| Unknown             | 4         | 3.42%   |
| HUAWEI              | 2         | 1.71%   |
| Samsung Electronics | 1         | 0.85%   |
| Positivo            | 1         | 0.85%   |
| Pine Microsystems   | 1         | 0.85%   |
| Notebook            | 1         | 0.85%   |
| Nokia               | 1         | 0.85%   |
| Microsoft           | 1         | 0.85%   |
| Getac               | 1         | 0.85%   |
| Framework           | 1         | 0.85%   |
| Exo                 | 1         | 0.85%   |
| Digibras            | 1         | 0.85%   |
| Cisco Systems       | 1         | 0.85%   |
| Chuwi               | 1         | 0.85%   |
| Apple               | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 4         | 3.42%   |
| Dell OptiPlex 7010                     | 2         | 1.71%   |
| ASUS PRIME Z390-P                      | 2         | 1.71%   |
| Acer Swift SF314-42                    | 2         | 1.71%   |
| Samsung 275E4E/275E5E                  | 1         | 0.85%   |
| Positivo Mobile                        | 1         | 0.85%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.85%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.85%   |
| Nokia Booklet 3G                       | 1         | 0.85%   |
| MSI MS-7D14                            | 1         | 0.85%   |
| MSI MS-7C92                            | 1         | 0.85%   |
| MSI MS-7C52                            | 1         | 0.85%   |
| MSI MS-7C02                            | 1         | 0.85%   |
| MSI MS-7A68                            | 1         | 0.85%   |
| MSI MS-7A39                            | 1         | 0.85%   |
| MSI MS-7816                            | 1         | 0.85%   |
| MSI Bravo 15 A4DDR                     | 1         | 0.85%   |
| Microsoft Surface with Windows RT      | 1         | 0.85%   |
| Lenovo Yoga 720-15IKB 80X7             | 1         | 0.85%   |
| Lenovo ThinkPad X260 20F5S08Q00        | 1         | 0.85%   |
| Lenovo ThinkPad X240 20AMA34HMN        | 1         | 0.85%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS | 1         | 0.85%   |
| Lenovo ThinkPad T480 20L6SA5Q00        | 1         | 0.85%   |
| Lenovo ThinkPad T460 20FMS0WN00        | 1         | 0.85%   |
| Lenovo ThinkPad T430 2349PS3           | 1         | 0.85%   |
| Lenovo ThinkPad T420 4180A21           | 1         | 0.85%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW  | 1         | 0.85%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00  | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200   | 1         | 0.85%   |
| Lenovo ThinkPad E595 20NFCTO1WW        | 1         | 0.85%   |
| Lenovo IdeaPad Z570 10246ZG            | 1         | 0.85%   |
| Lenovo IdeaPad S145-14IIL 81W6         | 1         | 0.85%   |
| Lenovo IdeaPad 710S-13IKB 80VQ         | 1         | 0.85%   |
| Lenovo G50-45 80E3                     | 1         | 0.85%   |
| HUAWEI KLVL-WXXW                       | 1         | 0.85%   |
| HUAWEI HN-WX9X                         | 1         | 0.85%   |
| HP Z2 Mini G3 Workstation              | 1         | 0.85%   |
| HP Stream 7 Tablet                     | 1         | 0.85%   |
| HP Pavilion Notebook                   | 1         | 0.85%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.85%   |
| HP Notebook                            | 1         | 0.85%   |
| HP Laptop 15s-eq2xxx                   | 1         | 0.85%   |
| HP Laptop 15-bw0xx                     | 1         | 0.85%   |
| HP Laptop 14-dk0xxx                    | 1         | 0.85%   |
| HP Laptop 14-bs0xx                     | 1         | 0.85%   |
| HP ENVY 6                              | 1         | 0.85%   |
| HP Compaq Elite 8300 SFF               | 1         | 0.85%   |
| HP 15                                  | 1         | 0.85%   |
| Gigabyte H310M M.2 2.0                 | 1         | 0.85%   |
| Gigabyte GA-78LMT-S2                   | 1         | 0.85%   |
| Gigabyte B550M AORUS PRO-P             | 1         | 0.85%   |
| Gigabyte B450M DS3H                    | 1         | 0.85%   |
| Getac V110                             | 1         | 0.85%   |
| Framework Laptop                       | 1         | 0.85%   |
| Exo Exomate X352                       | 1         | 0.85%   |
| Digibras NH4CU03                       | 1         | 0.85%   |
| Dell Precision 3530                    | 1         | 0.85%   |
| Dell OptiPlex GX520                    | 1         | 0.85%   |
| Dell OptiPlex 780                      | 1         | 0.85%   |
| Dell Latitude E4300                    | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 9.4%    |
| Acer Aspire              | 7         | 5.98%   |
| ASUS PRIME               | 6         | 5.13%   |
| HP Laptop                | 4         | 3.42%   |
| Dell OptiPlex            | 4         | 3.42%   |
| ASUS VivoBook            | 4         | 3.42%   |
| Unknown                  | 4         | 3.42%   |
| Lenovo IdeaPad           | 3         | 2.56%   |
| Dell Inspiron            | 3         | 2.56%   |
| HP Pavilion              | 2         | 1.71%   |
| Dell Latitude            | 2         | 1.71%   |
| ASUS TUF                 | 2         | 1.71%   |
| ASUS ROG                 | 2         | 1.71%   |
| Acer Swift               | 2         | 1.71%   |
| Samsung 275E4E           | 1         | 0.85%   |
| Positivo Mobile          | 1         | 0.85%   |
| Pine Microsystems Pine64 | 1         | 0.85%   |
| Notebook NV4XMB          | 1         | 0.85%   |
| Nokia Booklet            | 1         | 0.85%   |
| MSI MS-7D14              | 1         | 0.85%   |
| MSI MS-7C92              | 1         | 0.85%   |
| MSI MS-7C52              | 1         | 0.85%   |
| MSI MS-7C02              | 1         | 0.85%   |
| MSI MS-7A68              | 1         | 0.85%   |
| MSI MS-7A39              | 1         | 0.85%   |
| MSI MS-7816              | 1         | 0.85%   |
| MSI Bravo                | 1         | 0.85%   |
| Microsoft Surface        | 1         | 0.85%   |
| Lenovo Yoga              | 1         | 0.85%   |
| Lenovo G50-45            | 1         | 0.85%   |
| HUAWEI KLVL-WXXW         | 1         | 0.85%   |
| HUAWEI HN-WX9X           | 1         | 0.85%   |
| HP Z2                    | 1         | 0.85%   |
| HP Stream                | 1         | 0.85%   |
| HP Notebook              | 1         | 0.85%   |
| HP ENVY                  | 1         | 0.85%   |
| HP Compaq                | 1         | 0.85%   |
| HP 15                    | 1         | 0.85%   |
| Gigabyte H310M           | 1         | 0.85%   |
| Gigabyte GA-78LMT-S2     | 1         | 0.85%   |
| Gigabyte B550M           | 1         | 0.85%   |
| Gigabyte B450M           | 1         | 0.85%   |
| Getac V110               | 1         | 0.85%   |
| Framework Laptop         | 1         | 0.85%   |
| Exo Exomate              | 1         | 0.85%   |
| Digibras NH4CU03         | 1         | 0.85%   |
| Dell Precision           | 1         | 0.85%   |
| Dell G3                  | 1         | 0.85%   |
| Cisco Systems PowerEdge  | 1         | 0.85%   |
| Chuwi GemiBook           | 1         | 0.85%   |
| ASUS X751LD              | 1         | 0.85%   |
| ASUS X555UJ              | 1         | 0.85%   |
| ASUS X510UAR             | 1         | 0.85%   |
| ASUS X455LF              | 1         | 0.85%   |
| ASUS Q325UAR             | 1         | 0.85%   |
| ASUS P8Z77-V             | 1         | 0.85%   |
| ASUS P8H67-V             | 1         | 0.85%   |
| ASUS M5A78L-M            | 1         | 0.85%   |
| ASUS M4A89GTD-PRO        | 1         | 0.85%   |
| ASUS H110M-PLUS          | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 18        | 15.38%  |
| 2020    | 14        | 11.97%  |
| 2018    | 14        | 11.97%  |
| 2017    | 10        | 8.55%   |
| 2016    | 9         | 7.69%   |
| 2013    | 9         | 7.69%   |
| 2012    | 8         | 6.84%   |
| 2014    | 7         | 5.98%   |
| 2011    | 5         | 4.27%   |
| 2021    | 4         | 3.42%   |
| 2015    | 4         | 3.42%   |
| 2010    | 4         | 3.42%   |
| Unknown | 4         | 3.42%   |
| 2009    | 2         | 1.71%   |
| 2008    | 2         | 1.71%   |
| 2006    | 2         | 1.71%   |
| 2022    | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 67        | 57.26%  |
| Desktop     | 43        | 36.75%  |
| Convertible | 3         | 2.56%   |
| Tablet      | 2         | 1.71%   |
| Mini pc     | 1         | 0.85%   |
| Server      | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 26        | 21.85%  |
| 16.01-24.0      | 26        | 21.85%  |
| 8.01-16.0       | 23        | 19.33%  |
| 3.01-4.0        | 20        | 16.81%  |
| 32.01-64.0      | 11        | 9.24%   |
| 1.01-2.0        | 5         | 4.2%    |
| 0.51-1.0        | 3         | 2.52%   |
| 64.01-256.0     | 2         | 1.68%   |
| More than 256.0 | 1         | 0.84%   |
| 24.01-32.0      | 1         | 0.84%   |
| 2.01-3.0        | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 33        | 26.19%  |
| 2.01-3.0    | 30        | 23.81%  |
| 0.51-1.0    | 21        | 16.67%  |
| 4.01-8.0    | 13        | 10.32%  |
| 3.01-4.0    | 13        | 10.32%  |
| 8.01-16.0   | 7         | 5.56%   |
| 0.01-0.5    | 5         | 3.97%   |
| 16.01-24.0  | 3         | 2.38%   |
| 64.01-256.0 | 1         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 58.47%  |
| 2      | 28        | 23.73%  |
| 3      | 15        | 12.71%  |
| 5      | 2         | 1.69%   |
| 4      | 2         | 1.69%   |
| 9      | 1         | 0.85%   |
| 0      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 75.21%  |
| Yes       | 29        | 24.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 82.91%  |
| No        | 20        | 17.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 69.23%  |
| No        | 36        | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 57.63%  |
| No        | 50        | 42.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 24        | 20.51%  |
| Russia             | 9         | 7.69%   |
| India              | 9         | 7.69%   |
| Germany            | 9         | 7.69%   |
| Brazil             | 7         | 5.98%   |
| Czechia            | 6         | 5.13%   |
| Denmark            | 5         | 4.27%   |
| Ukraine            | 4         | 3.42%   |
| UK                 | 4         | 3.42%   |
| Poland             | 4         | 3.42%   |
| France             | 4         | 3.42%   |
| Turkey             | 3         | 2.56%   |
| Switzerland        | 3         | 2.56%   |
| Netherlands        | 3         | 2.56%   |
| Bulgaria           | 3         | 2.56%   |
| Spain              | 2         | 1.71%   |
| Greece             | 2         | 1.71%   |
| Australia          | 2         | 1.71%   |
| Argentina          | 2         | 1.71%   |
| Vietnam            | 1         | 0.85%   |
| Sweden             | 1         | 0.85%   |
| Peru               | 1         | 0.85%   |
| Norway             | 1         | 0.85%   |
| New Zealand        | 1         | 0.85%   |
| Indonesia          | 1         | 0.85%   |
| Honduras           | 1         | 0.85%   |
| Ecuador            | 1         | 0.85%   |
| Dominican Republic | 1         | 0.85%   |
| Canada             | 1         | 0.85%   |
| Belgium            | 1         | 0.85%   |
| Bangladesh         | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 5         | 4.17%   |
| Denver             | 3         | 2.5%    |
| Amsterdam          | 3         | 2.5%    |
| St Petersburg      | 2         | 1.67%   |
| Sofia              | 2         | 1.67%   |
| Orlando            | 2         | 1.67%   |
| Munich             | 2         | 1.67%   |
| Moscow             | 2         | 1.67%   |
| Lublin             | 2         | 1.67%   |
| Hyderabad          | 2         | 1.67%   |
| Geneva             | 2         | 1.67%   |
| Zagnansk           | 1         | 0.83%   |
| Yekaterinburg      | 1         | 0.83%   |
| Yambol             | 1         | 0.83%   |
| Weatherford        | 1         | 0.83%   |
| Vlaardingen        | 1         | 0.83%   |
| Viby J             | 1         | 0.83%   |
| Varna              | 1         | 0.83%   |
| Trujillo           | 1         | 0.83%   |
| Toulouse           | 1         | 0.83%   |
| Toms River         | 1         | 0.83%   |
| Tegucigalpa        | 1         | 0.83%   |
| Syktyvkar          | 1         | 0.83%   |
| Surabaya           | 1         | 0.83%   |
| Stratford          | 1         | 0.83%   |
| South Shields      | 1         | 0.83%   |
| Solone             | 1         | 0.83%   |
| Sistranda          | 1         | 0.83%   |
| Saxtons River      | 1         | 0.83%   |
| Sao Paulo          | 1         | 0.83%   |
| Santo Domingo      | 1         | 0.83%   |
| Saint-Paul-les-Dax | 1         | 0.83%   |
| Saint Paul         | 1         | 0.83%   |
| Rostock            | 1         | 0.83%   |
| Rosenheim          | 1         | 0.83%   |
| Rosario            | 1         | 0.83%   |
| Rio de Janeiro     | 1         | 0.83%   |
| Richmond           | 1         | 0.83%   |
| Regensburg         | 1         | 0.83%   |
| Pyatigorsk         | 1         | 0.83%   |
| Pune               | 1         | 0.83%   |
| Porto Alegre       | 1         | 0.83%   |
| Pliening           | 1         | 0.83%   |
| Phoenix            | 1         | 0.83%   |
| Pelabravo          | 1         | 0.83%   |
| Paris              | 1         | 0.83%   |
| Pardubice          | 1         | 0.83%   |
| Odense             | 1         | 0.83%   |
| Nizhniy Novgorod   | 1         | 0.83%   |
| New York           | 1         | 0.83%   |
| New Delhi          | 1         | 0.83%   |
| Mossoro            | 1         | 0.83%   |
| Monaca             | 1         | 0.83%   |
| Milford            | 1         | 0.83%   |
| Miedziana Gora     | 1         | 0.83%   |
| Mer                | 1         | 0.83%   |
| Melbourne          | 1         | 0.83%   |
| Matos Costa        | 1         | 0.83%   |
| Los Angeles        | 1         | 0.83%   |
| Lakewood           | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 51     | 21.51%  |
| WDC                 | 32        | 39     | 18.6%   |
| Seagate             | 28        | 33     | 16.28%  |
| Kingston            | 11        | 11     | 6.4%    |
| Toshiba             | 9         | 10     | 5.23%   |
| Unknown             | 7         | 12     | 4.07%   |
| SanDisk             | 7         | 8      | 4.07%   |
| Intel               | 7         | 9      | 4.07%   |
| HGST                | 6         | 7      | 3.49%   |
| Hitachi             | 4         | 4      | 2.33%   |
| Crucial             | 4         | 5      | 2.33%   |
| SK hynix            | 2         | 2      | 1.16%   |
| Phison              | 2         | 2      | 1.16%   |
| Patriot             | 2         | 2      | 1.16%   |
| Corsair             | 2         | 2      | 1.16%   |
| A-DATA Technology   | 2         | 3      | 1.16%   |
| XPG                 | 1         | 4      | 0.58%   |
| Transcend           | 1         | 1      | 0.58%   |
| SPCC                | 1         | 1      | 0.58%   |
| OCZ                 | 1         | 1      | 0.58%   |
| Maxtor              | 1         | 1      | 0.58%   |
| LITEONIT            | 1         | 1      | 0.58%   |
| Gigabyte Technology | 1         | 2      | 0.58%   |
| China               | 1         | 1      | 0.58%   |
| BHT                 | 1         | 1      | 0.58%   |
| Apple               | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 5         | 2.62%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 2.09%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.57%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.57%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 1.57%   |
| Samsung SSD 870 EVO 500GB               | 3         | 1.57%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 1.57%   |
| Kingston SHFS37A120G 120GB SSD          | 3         | 1.57%   |
| Unknown MMC Card  32GB                  | 2         | 1.05%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.05%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 1.05%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.05%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 1.05%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 1.05%   |
| Samsung SSD 980 PRO 500GB               | 2         | 1.05%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.05%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.05%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.05%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.05%   |
| Patriot Burst 120GB SSD                 | 2         | 1.05%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 1.05%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.05%   |
| XPG NVMe SSD Drive 2TB                  | 1         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.52%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.52%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.52%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.52%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.52%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.52%   |
| WDC WD3200AAKS-22SBA0 320GB             | 1         | 0.52%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.52%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.52%   |
| WDC WD20EZBX-00AYRA0 2TB                | 1         | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.52%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.52%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 0.52%   |
| WDC WD1600AAJS-60PSA0 160GB             | 1         | 0.52%   |
| WDC WD15EARS-00MVWB0 1TB                | 1         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.52%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.52%   |
| WDC WD10JPVX-08JC3T6 1TB                | 1         | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.52%   |
| WDC WD10EZRX-00L4HB0 1TB                | 1         | 0.52%   |
| WDC WD10EZEX-00BBHA0 1TB                | 1         | 0.52%   |
| WDC WD10EFRX-68PJCN0 1TB                | 1         | 0.52%   |
| WDC WD10EFRX-68FYTN0 1TB                | 1         | 0.52%   |
| WDC WD10EARX-00PASB0 1TB                | 1         | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 1         | 0.52%   |
| WDC WD1001FALS-00K1B0 1TB               | 1         | 0.52%   |
| WDC WD Elements 500GB                   | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.52%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.52%   |
| Unknown SD512  512MB                    | 1         | 0.52%   |
| Unknown SD16G  16GB                     | 1         | 0.52%   |
| Unknown MMC Card  8GB                   | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 33     | 35.44%  |
| WDC                 | 27        | 33     | 34.18%  |
| Toshiba             | 8         | 9      | 10.13%  |
| HGST                | 6         | 7      | 7.59%   |
| Samsung Electronics | 5         | 5      | 6.33%   |
| Hitachi             | 4         | 4      | 5.06%   |
| Maxtor              | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 32.65%  |
| Kingston            | 10        | 10     | 20.41%  |
| SanDisk             | 5         | 5      | 10.2%   |
| WDC                 | 2         | 2      | 4.08%   |
| Patriot             | 2         | 2      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| Crucial             | 2         | 3      | 4.08%   |
| Transcend           | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| OCZ                 | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| Gigabyte Technology | 1         | 2      | 2.04%   |
| Corsair             | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 2      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 65        | 92     | 42.21%  |
| SSD     | 45        | 55     | 29.22%  |
| NVMe    | 36        | 54     | 23.38%  |
| MMC     | 6         | 10     | 3.9%    |
| Unknown | 2         | 3      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 145    | 65.93%  |
| NVMe | 36        | 54     | 26.67%  |
| MMC  | 6         | 10     | 4.44%   |
| SAS  | 4         | 5      | 2.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 79     | 52.94%  |
| 0.51-1.0   | 39        | 46     | 32.77%  |
| 1.01-2.0   | 13        | 17     | 10.92%  |
| 3.01-4.0   | 2         | 3      | 1.68%   |
| 4.01-10.0  | 2         | 2      | 1.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 30        | 25%     |
| 501-1000       | 24        | 20%     |
| 101-250        | 22        | 18.33%  |
| Unknown        | 12        | 10%     |
| 1001-2000      | 10        | 8.33%   |
| More than 3000 | 6         | 5%      |
| 1-20           | 6         | 5%      |
| 2001-3000      | 4         | 3.33%   |
| 21-50          | 3         | 2.5%    |
| 51-100         | 3         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 26.61%  |
| 101-250        | 28        | 22.58%  |
| 21-50          | 16        | 12.9%   |
| 251-500        | 12        | 9.68%   |
| Unknown        | 12        | 9.68%   |
| 51-100         | 11        | 8.87%   |
| 1001-2000      | 5         | 4.03%   |
| 501-1000       | 4         | 3.23%   |
| More than 3000 | 2         | 1.61%   |
| 2001-3000      | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 7.41%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 3.7%    |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 3.7%    |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 3.7%    |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 3.7%    |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 3.7%    |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.7%    |
| Seagate ST9750420AS 752GB             | 1         | 1      | 3.7%    |
| Seagate ST9500325AS 500GB             | 1         | 1      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 3.7%    |
| Seagate ST3750330AS 752GB             | 1         | 1      | 3.7%    |
| Seagate ST3160318AS 160GB             | 1         | 1      | 3.7%    |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 1      | 3.7%    |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 3.7%    |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 3.7%    |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 3.7%    |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 3.7%    |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 3.7%    |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 3.7%    |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.7%    |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 3.7%    |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.7%    |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 3.7%    |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 38.46%  |
| WDC                 | 4         | 5      | 15.38%  |
| Samsung Electronics | 4         | 4      | 15.38%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 3      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 41.67%  |
| WDC                 | 4         | 5      | 16.67%  |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 3      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 92%     |
| SSD  | 2         | 2      | 8%      |

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
| Works    | 70        | 107    | 50.36%  |
| Detected | 45        | 78     | 32.37%  |
| Malfunc  | 24        | 29     | 17.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 63        | 44.06%  |
| AMD                              | 37        | 25.87%  |
| Samsung Electronics              | 21        | 14.69%  |
| SanDisk                          | 4         | 2.8%    |
| Phison Electronics               | 3         | 2.1%    |
| SK hynix                         | 2         | 1.4%    |
| Micron/Crucial Technology        | 2         | 1.4%    |
| ADATA Technology                 | 2         | 1.4%    |
| Toshiba America Info Systems     | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Nvidia                           | 1         | 0.7%    |
| Marvell Technology Group         | 1         | 0.7%    |
| LSI Logic / Symbios Logic        | 1         | 0.7%    |
| Kingston Technology Company      | 1         | 0.7%    |
| JMicron Technology               | 1         | 0.7%    |
| Broadcom                         | 1         | 0.7%    |
| ASMedia Technology               | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 16.05%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.17%   |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 4.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 2.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.85%   |
| Intel SSD 660P Series                                                            | 3         | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 1.85%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.23%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 1.23%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.62%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.62%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.62%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.62%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 0.62%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.62%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                      | 1         | 0.62%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.62%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.62%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.62%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.62%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.62%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.62%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 0.62%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1         | 0.62%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1         | 0.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 88        | 60.69%  |
| NVMe | 37        | 25.52%  |
| IDE  | 13        | 8.97%   |
| RAID | 7         | 4.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 69        | 58.97%  |
| AMD                      | 43        | 36.75%  |
| ARM                      | 3         | 2.56%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.85%   |
| PowerMac11,2             | 1         | 0.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 3.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.71%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.71%   |
| ARM Processor                                      | 2         | 1.71%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 2         | 1.71%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.71%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.71%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.85%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.85%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.85%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.85%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.85%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.85%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.85%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz                  | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 1         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz                  | 1         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 0.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 1         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz                  | 1         | 0.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1         | 0.85%   |
| Intel Core i5-4670 CPU @ 3.40GHz                   | 1         | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz                  | 1         | 0.85%   |
| Intel Core i5-4278U CPU @ 2.60GHz                  | 1         | 0.85%   |
| Intel Core i5-4250U CPU @ 1.30GHz                  | 1         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 1         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz                   | 1         | 0.85%   |
| Intel Core i5-3350P CPU @ 3.10GHz                  | 1         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz                  | 1         | 0.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz                  | 1         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 1         | 0.85%   |
| Intel Core i3-9100F CPU @ 3.60GHz                  | 1         | 0.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz                  | 1         | 0.85%   |
| Intel Core i3-7100 CPU @ 3.90GHz                   | 1         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz                  | 1         | 0.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 1         | 0.85%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 1         | 0.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz                  | 1         | 0.85%   |
| Intel Core i3-3240 CPU @ 3.40GHz                   | 1         | 0.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz                  | 1         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 1         | 0.85%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz               | 1         | 0.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz               | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 19.66%  |
| AMD Ryzen 5             | 15        | 12.82%  |
| Intel Core i7           | 14        | 11.97%  |
| Other                   | 11        | 9.4%    |
| Intel Core i3           | 10        | 8.55%   |
| AMD Ryzen 7             | 9         | 7.69%   |
| Intel Atom              | 5         | 4.27%   |
| Intel Celeron           | 4         | 3.42%   |
| Intel Pentium           | 2         | 1.71%   |
| Intel Core 2 Duo        | 2         | 1.71%   |
| AMD Ryzen 7 PRO         | 2         | 1.71%   |
| AMD Ryzen 3             | 2         | 1.71%   |
| AMD FX                  | 2         | 1.71%   |
| AMD A8                  | 2         | 1.71%   |
| Intel Xeon              | 1         | 0.85%   |
| Intel Pentium Gold      | 1         | 0.85%   |
| Intel Pentium 4         | 1         | 0.85%   |
| Intel Genuine           | 1         | 0.85%   |
| Intel Core i9           | 1         | 0.85%   |
| AMD Turion 64 X2 Mobile | 1         | 0.85%   |
| AMD Ryzen Threadripper  | 1         | 0.85%   |
| AMD Phenom II X4        | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD E1                  | 1         | 0.85%   |
| AMD C-60                | 1         | 0.85%   |
| AMD Athlon II X3        | 1         | 0.85%   |
| AMD Athlon II X2        | 1         | 0.85%   |
| AMD A4                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 41        | 35.04%  |
| 2      | 40        | 34.19%  |
| 6      | 16        | 13.68%  |
| 8      | 12        | 10.26%  |
| 1      | 5         | 4.27%   |
| 64     | 1         | 0.85%   |
| 12     | 1         | 0.85%   |
| 3      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 115       | 98.29%  |
| 2      | 2         | 1.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 64.96%  |
| 1      | 40        | 34.19%  |
| 4      | 1         | 0.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 88.89%  |
| Unknown        | 8         | 6.84%   |
| 32-bit         | 3         | 2.56%   |
| 64-bit         | 2         | 1.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 31.67%  |
| 0x306a9    | 7         | 5.83%   |
| 0x40651    | 6         | 5%      |
| 0x906ea    | 4         | 3.33%   |
| 0x906e9    | 3         | 2.5%    |
| 0x806ea    | 3         | 2.5%    |
| 0x806e9    | 3         | 2.5%    |
| 0x406e3    | 3         | 2.5%    |
| 0x08600104 | 3         | 2.5%    |
| 0x08108102 | 3         | 2.5%    |
| 0x806ec    | 2         | 1.67%   |
| 0x206a7    | 2         | 1.67%   |
| 0x106c2    | 2         | 1.67%   |
| 0x0a201009 | 2         | 1.67%   |
| 0x08701021 | 2         | 1.67%   |
| 0x0800820d | 2         | 1.67%   |
| 0x07030105 | 2         | 1.67%   |
| 0x06000852 | 2         | 1.67%   |
| 0x05000119 | 2         | 1.67%   |
| 0x010000c8 | 2         | 1.67%   |
| 0xa0671    | 1         | 0.83%   |
| 0x906ed    | 1         | 0.83%   |
| 0x90672    | 1         | 0.83%   |
| 0x806eb    | 1         | 0.83%   |
| 0x706a1    | 1         | 0.83%   |
| 0x506e3    | 1         | 0.83%   |
| 0x406c4    | 1         | 0.83%   |
| 0x306d4    | 1         | 0.83%   |
| 0x306c3    | 1         | 0.83%   |
| 0x30678    | 1         | 0.83%   |
| 0x106ca    | 1         | 0.83%   |
| 0x106a5    | 1         | 0.83%   |
| 0x1067a    | 1         | 0.83%   |
| 0x0a50000c | 1         | 0.83%   |
| 0x0a201205 | 1         | 0.83%   |
| 0x08701013 | 1         | 0.83%   |
| 0x08608103 | 1         | 0.83%   |
| 0x08608102 | 1         | 0.83%   |
| 0x08600106 | 1         | 0.83%   |
| 0x08600102 | 1         | 0.83%   |
| 0x08108109 | 1         | 0.83%   |
| 0x08101007 | 1         | 0.83%   |
| 0x08001138 | 1         | 0.83%   |
| 0x08001136 | 1         | 0.83%   |
| 0x08001129 | 1         | 0.83%   |
| 0x07030104 | 1         | 0.83%   |
| 0x06006705 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 19.66%  |
| Zen 2            | 10        | 8.55%   |
| IvyBridge        | 10        | 8.55%   |
| Haswell          | 8         | 6.84%   |
| Zen+             | 7         | 5.98%   |
| Unknown          | 7         | 5.98%   |
| Zen 3            | 6         | 5.13%   |
| Skylake          | 6         | 5.13%   |
| Zen              | 4         | 3.42%   |
| Silvermont       | 3         | 2.56%   |
| SandyBridge      | 3         | 2.56%   |
| Puma             | 3         | 2.56%   |
| K10              | 3         | 2.56%   |
| Excavator        | 3         | 2.56%   |
| Bonnell          | 3         | 2.56%   |
| TigerLake        | 2         | 1.71%   |
| Piledriver       | 2         | 1.71%   |
| Penryn           | 2         | 1.71%   |
| Icelake          | 2         | 1.71%   |
| Goldmont plus    | 2         | 1.71%   |
| Bobcat           | 2         | 1.71%   |
| NetBurst         | 1         | 0.85%   |
| Nehalem          | 1         | 0.85%   |
| K8 Hammer        | 1         | 0.85%   |
| Core             | 1         | 0.85%   |
| Broadwell        | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 38.69%  |
| Nvidia                           | 41        | 29.93%  |
| AMD                              | 40        | 29.2%   |
| Silicon Integrated Systems [SiS] | 1         | 0.73%   |
| Matrox Electronics Systems       | 1         | 0.73%   |
| ASPEED Technology                | 1         | 0.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 4.96%   |
| AMD Renoir                                                                    | 6         | 4.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 3.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 2.84%   |
| Intel UHD Graphics 620                                                        | 4         | 2.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 2.84%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 2.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 2.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 2.13%   |
| Intel HD Graphics 620                                                         | 3         | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 3         | 2.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 3         | 2.13%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 2         | 1.42%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.42%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 2         | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.42%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 2         | 1.42%   |
| AMD Lucienne                                                                  | 2         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 1.42%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                            | 2         | 1.42%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.71%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1         | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 1         | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                         | 1         | 0.71%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                     | 1         | 0.71%   |
| Nvidia NV43 [GeForce 6600]                                                    | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.71%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                          | 1         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 1         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.71%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 0.71%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                          | 1         | 0.71%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 0.71%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.71%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1         | 0.71%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.71%   |
| Nvidia GF108 [GeForce GT 420]                                                 | 1         | 0.71%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 0.71%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1         | 0.71%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 0.71%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 0.71%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1         | 0.71%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.71%   |
| Intel HD Graphics 630                                                         | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 29.41%  |
| 1 x AMD        | 34        | 28.57%  |
| 1 x Nvidia     | 22        | 18.49%  |
| Intel + Nvidia | 16        | 13.45%  |
| Other          | 3         | 2.52%   |
| 2 x AMD        | 2         | 1.68%   |
| AMD + Nvidia   | 2         | 1.68%   |
| 2 x Nvidia     | 1         | 0.84%   |
| 1 x SiS        | 1         | 0.84%   |
| 1 x Matrox     | 1         | 0.84%   |
| Intel + AMD    | 1         | 0.84%   |
| AMD + ASPEED   | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 82        | 68.91%  |
| Proprietary | 33        | 27.73%  |
| Unknown     | 4         | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 52.46%  |
| 1.01-2.0   | 17        | 13.93%  |
| 0.01-0.5   | 13        | 10.66%  |
| 3.01-4.0   | 10        | 8.2%    |
| 0.51-1.0   | 7         | 5.74%   |
| 5.01-6.0   | 4         | 3.28%   |
| 7.01-8.0   | 2         | 1.64%   |
| 2.01-3.0   | 2         | 1.64%   |
| 8.01-16.0  | 2         | 1.64%   |
| 16.01-24.0 | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 18        | 14.29%  |
| Chimei Innolux       | 14        | 11.11%  |
| LG Display           | 12        | 9.52%   |
| BOE                  | 12        | 9.52%   |
| Samsung Electronics  | 10        | 7.94%   |
| Hewlett-Packard      | 8         | 6.35%   |
| Dell                 | 8         | 6.35%   |
| Acer                 | 5         | 3.97%   |
| Philips              | 4         | 3.17%   |
| Iiyama               | 4         | 3.17%   |
| Goldstar             | 3         | 2.38%   |
| BenQ                 | 3         | 2.38%   |
| PANDA                | 2         | 1.59%   |
| Lenovo               | 2         | 1.59%   |
| Fujitsu Siemens      | 2         | 1.59%   |
| ASUSTek Computer     | 2         | 1.59%   |
| Apple                | 2         | 1.59%   |
| AOC                  | 2         | 1.59%   |
| Ancor Communications | 2         | 1.59%   |
| Unknown              | 1         | 0.79%   |
| STD                  | 1         | 0.79%   |
| Sceptre Tech         | 1         | 0.79%   |
| Sceptre              | 1         | 0.79%   |
| Panasonic            | 1         | 0.79%   |
| ONN                  | 1         | 0.79%   |
| MSI                  | 1         | 0.79%   |
| LG Philips           | 1         | 0.79%   |
| InnoLux Display      | 1         | 0.79%   |
| FUN                  | 1         | 0.79%   |
| CHR                  | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.26%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2         | 1.5%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.5%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.5%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.5%    |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.75%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1         | 0.75%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.75%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.75%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.75%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.75%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 0.75%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.75%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.75%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.75%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.75%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.75%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.75%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.75%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.75%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.75%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                | 1         | 0.75%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 1         | 0.75%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.75%   |
| Lenovo LEN-22ICB-C LEN1201 1920x1080 476x268mm 21.5-inch              | 1         | 0.75%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 0.75%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch      | 1         | 0.75%   |
| Iiyama PL2530H IVM6132 1920x1080 540x300mm 24.3-inch                  | 1         | 0.75%   |
| Hewlett-Packard Z24i G2 HPN3481 1920x1200 518x324mm 24.1-inch         | 1         | 0.75%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 1         | 0.75%   |
| Hewlett-Packard LCD Monitor Compaq W185q 1366x768                     | 1         | 0.75%   |
| Hewlett-Packard E221c HWP3094 1920x1080 497x292mm 22.7-inch           | 1         | 0.75%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 1         | 0.75%   |
| Hewlett-Packard 21kd HWP3329 1920x1080 458x258mm 20.7-inch            | 1         | 0.75%   |
| Goldstar LG 32 FHD GSM7701 1920x1080 600x340mm 27.2-inch              | 1         | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.75%   |
| Goldstar 23MB35 GSM5A3E 1920x1080 510x290mm 23.1-inch                 | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 44.35%  |
| 1366x768 (WXGA)    | 24        | 19.35%  |
| 3840x2160 (4K)     | 5         | 4.03%   |
| 2560x1440 (QHD)    | 5         | 4.03%   |
| 1920x1200 (WUXGA)  | 5         | 4.03%   |
| 1680x1050 (WSXGA+) | 4         | 3.23%   |
| 3440x1440          | 3         | 2.42%   |
| 2160x1440          | 3         | 2.42%   |
| 1600x900 (HD+)     | 3         | 2.42%   |
| Unknown            | 3         | 2.42%   |
| 1280x800 (WXGA)    | 2         | 1.61%   |
| 1280x1024 (SXGA)   | 2         | 1.61%   |
| 1024x600           | 2         | 1.61%   |
| 7680x1080          | 1         | 0.81%   |
| 3840x1600          | 1         | 0.81%   |
| 3840x1080          | 1         | 0.81%   |
| 2560x1600          | 1         | 0.81%   |
| 2560x1080          | 1         | 0.81%   |
| 2256x1504          | 1         | 0.81%   |
| 1360x768           | 1         | 0.81%   |
| 1280x720 (HD)      | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 23.44%  |
| 24      | 15        | 11.72%  |
| 13      | 13        | 10.16%  |
| 14      | 12        | 9.38%   |
| Unknown | 11        | 8.59%   |
| 23      | 7         | 5.47%   |
| 27      | 6         | 4.69%   |
| 21      | 6         | 4.69%   |
| 22      | 4         | 3.13%   |
| 34      | 3         | 2.34%   |
| 12      | 3         | 2.34%   |
| 17      | 2         | 1.56%   |
| 11      | 2         | 1.56%   |
| 10      | 2         | 1.56%   |
| 84      | 1         | 0.78%   |
| 40      | 1         | 0.78%   |
| 39      | 1         | 0.78%   |
| 37      | 1         | 0.78%   |
| 33      | 1         | 0.78%   |
| 31      | 1         | 0.78%   |
| 28      | 1         | 0.78%   |
| 25      | 1         | 0.78%   |
| 20      | 1         | 0.78%   |
| 19      | 1         | 0.78%   |
| 18      | 1         | 0.78%   |
| 8       | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 37.01%  |
| 501-600     | 27        | 21.26%  |
| 201-300     | 16        | 12.6%   |
| 401-500     | 12        | 9.45%   |
| Unknown     | 11        | 8.66%   |
| 701-800     | 4         | 3.15%   |
| 801-900     | 3         | 2.36%   |
| 601-700     | 3         | 2.36%   |
| 351-400     | 2         | 1.57%   |
| 1501-2000   | 1         | 0.79%   |
| 101-200     | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 71.43%  |
| 16/10   | 13        | 10.92%  |
| Unknown | 10        | 8.4%    |
| 21/9    | 5         | 4.2%    |
| 3/2     | 4         | 3.36%   |
| 5/4     | 2         | 1.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 23.62%  |
| 201-250        | 22        | 17.32%  |
| 81-90          | 20        | 15.75%  |
| Unknown        | 11        | 8.66%   |
| 251-300        | 10        | 7.87%   |
| 71-80          | 6         | 4.72%   |
| 301-350        | 6         | 4.72%   |
| 351-500        | 5         | 3.94%   |
| 61-70          | 3         | 2.36%   |
| 501-1000       | 3         | 2.36%   |
| 51-60          | 2         | 1.57%   |
| 41-50          | 2         | 1.57%   |
| 151-200        | 2         | 1.57%   |
| 141-150        | 2         | 1.57%   |
| More than 1000 | 1         | 0.79%   |
| 1-40           | 1         | 0.79%   |
| 131-140        | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 41        | 32.03%  |
| 101-120       | 33        | 25.78%  |
| 121-160       | 30        | 23.44%  |
| 161-240       | 12        | 9.38%   |
| Unknown       | 11        | 8.59%   |
| More than 240 | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 79.66%  |
| 2     | 22        | 18.64%  |
| 0     | 2         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 65        | 39.39%  |
| Intel                            | 46        | 27.88%  |
| Qualcomm Atheros                 | 17        | 10.3%   |
| Broadcom                         | 10        | 6.06%   |
| TP-Link                          | 3         | 1.82%   |
| Sierra Wireless                  | 3         | 1.82%   |
| Ralink Technology                | 3         | 1.82%   |
| Xiaomi                           | 2         | 1.21%   |
| Qualcomm Atheros Communications  | 2         | 1.21%   |
| Cypress Semiconductor            | 2         | 1.21%   |
| Broadcom Limited                 | 2         | 1.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |
| Realtek                          | 1         | 0.61%   |
| Ralink                           | 1         | 0.61%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.61%   |
| Nvidia                           | 1         | 0.61%   |
| MediaTek                         | 1         | 0.61%   |
| DisplayLink                      | 1         | 0.61%   |
| ASIX Electronics                 | 1         | 0.61%   |
| Arduino SA                       | 1         | 0.61%   |
| Apple                            | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 43        | 22.4%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.6%    |
| Intel I211 Gigabit Network Connection                                   | 5         | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 2.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.56%   |
| Intel Wireless 8260                                                     | 3         | 1.56%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.04%   |
| Intel Wireless 7260                                                     | 2         | 1.04%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.04%   |
| Cypress K38231_03                                                       | 2         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.52%   |
| TP-Link TL-WN722N v2                                                    | 1         | 0.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.52%   |
| Sierra Wireless EM7455                                                  | 1         | 0.52%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.52%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.52%   |
| Realtek 802.11n NIC                                                     | 1         | 0.52%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.52%   |
| OnePlus (Shenzhen) OnePlus                                              | 1         | 0.52%   |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.52%   |
| MediaTek moto e6s                                                       | 1         | 0.52%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.52%   |
| Intel WiFi Link 5100                                                    | 1         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 39.29%  |
| Realtek Semiconductor           | 19        | 22.62%  |
| Qualcomm Atheros                | 15        | 17.86%  |
| Broadcom                        | 4         | 4.76%   |
| Ralink Technology               | 3         | 3.57%   |
| TP-Link                         | 2         | 2.38%   |
| Sierra Wireless                 | 2         | 2.38%   |
| Qualcomm Atheros Communications | 2         | 2.38%   |
| Broadcom Limited                | 2         | 2.38%   |
| Realtek                         | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 11.9%   |
| Intel Wireless 8265 / 8275                                              | 6         | 7.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.57%   |
| Intel Wireless 8260                                                     | 3         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.38%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.38%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 2.38%   |
| Intel Wireless 7260                                                     | 2         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.38%   |
| TP-Link TL-WN722N v2                                                    | 1         | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.19%   |
| Sierra Wireless EM7455                                                  | 1         | 1.19%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.19%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.19%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.19%   |
| Realtek 802.11n NIC                                                     | 1         | 1.19%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.19%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.19%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.19%   |
| Intel WiFi Link 5100                                                    | 1         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.19%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.19%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 55.66%  |
| Intel                            | 25        | 23.58%  |
| Broadcom                         | 7         | 6.6%    |
| Qualcomm Atheros                 | 3         | 2.83%   |
| Xiaomi                           | 2         | 1.89%   |
| Cypress Semiconductor            | 2         | 1.89%   |
| TP-Link                          | 1         | 0.94%   |
| Silicon Integrated Systems [SiS] | 1         | 0.94%   |
| Sierra Wireless                  | 1         | 0.94%   |
| Nvidia                           | 1         | 0.94%   |
| MediaTek                         | 1         | 0.94%   |
| DisplayLink                      | 1         | 0.94%   |
| ASIX Electronics                 | 1         | 0.94%   |
| Apple                            | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 40.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.72%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.72%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.89%   |
| Cypress K38231_03                                                 | 2         | 1.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.94%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.94%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.94%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.94%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.94%   |
| MediaTek moto e6s                                                 | 1         | 0.94%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.94%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.94%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.94%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.94%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.94%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.94%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.94%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.94%   |
| Apple iPad 4/Mini1                                                | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 53.89%  |
| WiFi     | 81        | 45%     |
| Modem    | 1         | 0.56%   |
| Unknown  | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 58.12%  |
| Ethernet | 49        | 41.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 49.57%  |
| 2     | 49        | 41.88%  |
| 0     | 5         | 4.27%   |
| 3     | 4         | 3.42%   |
| 4     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 105       | 88.24%  |
| Yes  | 14        | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 42.86%  |
| Realtek Semiconductor           | 11        | 15.71%  |
| Cambridge Silicon Radio         | 7         | 10%     |
| Lite-On Technology              | 5         | 7.14%   |
| Broadcom                        | 5         | 7.14%   |
| Qualcomm Atheros Communications | 3         | 4.29%   |
| IMC Networks                    | 3         | 4.29%   |
| Realtek                         | 2         | 2.86%   |
| Foxconn / Hon Hai               | 2         | 2.86%   |
| Dell                            | 1         | 1.43%   |
| Apple                           | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.71%  |
| Intel AX200 Bluetooth                               | 10        | 14.29%  |
| Realtek Bluetooth Radio                             | 7         | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 10%     |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.29%   |
| Intel AX201 Bluetooth                               | 3         | 4.29%   |
| Realtek Bluetooth Radio                             | 2         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.86%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.43%   |
| Intel AX210 Bluetooth                               | 1         | 1.43%   |
| IMC Networks Bluetooth Device                       | 1         | 1.43%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.43%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.43%   |
| Broadcom HP Portable Valentine                      | 1         | 1.43%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.43%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.43%   |
| Apple Bluetooth Host Controller                     | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 39.02%  |
| AMD                              | 46        | 28.05%  |
| Nvidia                           | 28        | 17.07%  |
| C-Media Electronics              | 5         | 3.05%   |
| Logitech                         | 4         | 2.44%   |
| JMTek                            | 4         | 2.44%   |
| Texas Instruments                | 2         | 1.22%   |
| Creative Technology              | 2         | 1.22%   |
| VIA Technologies                 | 1         | 0.61%   |
| Unknown                          | 1         | 0.61%   |
| SteelSeries ApS                  | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |
| SAVITECH                         | 1         | 0.61%   |
| Focusrite-Novation               | 1         | 0.61%   |
| Elgato Systems                   | 1         | 0.61%   |
| Corsair                          | 1         | 0.61%   |
| Cambridge Audio                  | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 3.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 3.43%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 3.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.94%   |
| JMTek USB PnP Audio Device                                                 | 4         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.96%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.47%   |
| AMD High Definition Audio Controller                                       | 3         | 1.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.47%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.98%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.98%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.98%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.98%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1         | 0.49%   |
| Unknown USB Audio                                                          | 1         | 0.49%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.49%   |
| SAVITECH SA9023 audio controller                                           | 1         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.49%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.49%   |
| Logitech PRO X                                                             | 1         | 0.49%   |
| Logitech G633 Gaming Headset                                               | 1         | 0.49%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.49%   |
| Logitech Blue Snowball                                                     | 1         | 0.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.49%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.49%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.49%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 22.83%  |
| Samsung Electronics | 21        | 22.83%  |
| Kingston            | 11        | 11.96%  |
| Micron Technology   | 8         | 8.7%    |
| Unknown             | 6         | 6.52%   |
| G.Skill             | 6         | 6.52%   |
| Corsair             | 5         | 5.43%   |
| A-DATA Technology   | 5         | 5.43%   |
| Crucial             | 3         | 3.26%   |
| Transcend           | 1         | 1.09%   |
| Ramaxel Technology  | 1         | 1.09%   |
| Patriot             | 1         | 1.09%   |
| Elpida              | 1         | 1.09%   |
| Avant               | 1         | 1.09%   |
| 48spaces            | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.96%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.98%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.98%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.98%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.98%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.98%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.98%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                      | 1         | 0.98%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.98%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.98%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.98%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.98%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s              | 1         | 0.98%   |
| Samsung RAM M378B2873EH1-CF8 1GB DIMM DDR3 1067MT/s              | 1         | 0.98%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4096MB SODIMM LPDDR4 3733MT/s        | 1         | 0.98%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.98%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 0.98%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 0.98%   |
| Patriot RAM PSD48G24002 8192MB DIMM DDR4 2400MT/s                | 1         | 0.98%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 1         | 0.98%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 0.98%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 1         | 0.98%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 1         | 0.98%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| Kingston RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 0.98%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s              | 1         | 0.98%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 1         | 0.98%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s          | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 40        | 48.19%  |
| DDR3    | 32        | 38.55%  |
| LPDDR4  | 3         | 3.61%   |
| LPDDR3  | 3         | 3.61%   |
| DDR2    | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| DDR5    | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 59.76%  |
| DIMM         | 29        | 35.37%  |
| Row Of Chips | 4         | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 39        | 44.32%  |
| 4096  | 29        | 32.95%  |
| 16384 | 10        | 11.36%  |
| 2048  | 6         | 6.82%   |
| 1024  | 3         | 3.41%   |
| 512   | 1         | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 25.56%  |
| 2667    | 13        | 14.44%  |
| 3200    | 11        | 12.22%  |
| 2400    | 9         | 10%     |
| 1333    | 7         | 7.78%   |
| 3600    | 4         | 4.44%   |
| 2133    | 4         | 4.44%   |
| 1334    | 3         | 3.33%   |
| 3000    | 2         | 2.22%   |
| 1867    | 2         | 2.22%   |
| 4800    | 1         | 1.11%   |
| 4266    | 1         | 1.11%   |
| 3866    | 1         | 1.11%   |
| 3733    | 1         | 1.11%   |
| 3333    | 1         | 1.11%   |
| 2933    | 1         | 1.11%   |
| 2800    | 1         | 1.11%   |
| 2666    | 1         | 1.11%   |
| 1067    | 1         | 1.11%   |
| 667     | 1         | 1.11%   |
| 533     | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

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
| Chicony Electronics                    | 23        | 29.11%  |
| IMC Networks                           | 13        | 16.46%  |
| Microdia                               | 9         | 11.39%  |
| Logitech                               | 7         | 8.86%   |
| Realtek Semiconductor                  | 6         | 7.59%   |
| Quanta                                 | 5         | 6.33%   |
| Acer                                   | 5         | 6.33%   |
| Sunplus Innovation Technology          | 3         | 3.8%    |
| Suyin                                  | 2         | 2.53%   |
| MacroSilicon                           | 2         | 2.53%   |
| Silicon Motion                         | 1         | 1.27%   |
| Microsoft                              | 1         | 1.27%   |
| GEMBIRD                                | 1         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony integrated camera                         | 6         | 7.41%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 4.94%   |
| Quanta HD User Facing                             | 3         | 3.7%    |
| Logitech Webcam C270                              | 3         | 3.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                | 3         | 3.7%    |
| Suyin HP TrueVision HD                            | 2         | 2.47%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 2.47%   |
| Microdia HP Integrated Webcam                     | 2         | 2.47%   |
| IMC Networks HD Camera                            | 2         | 2.47%   |
| Chicony USB 2.0 Camera                            | 2         | 2.47%   |
| Chicony HP TrueVision HD Camera                   | 2         | 2.47%   |
| Chicony HD WebCam                                 | 2         | 2.47%   |
| Sunplus HP Wide Vision HD                         | 1         | 1.23%   |
| Silicon Motion WebCam SC-10HDD12636N              | 1         | 1.23%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 1.23%   |
| Realtek USB Camera                                | 1         | 1.23%   |
| Realtek Streaming Webcam                          | 1         | 1.23%   |
| Realtek Laptop Camera                             | 1         | 1.23%   |
| Realtek Integrated Webcam HD                      | 1         | 1.23%   |
| Realtek HD WebCam                                 | 1         | 1.23%   |
| Quanta VGA WebCam                                 | 1         | 1.23%   |
| Quanta HP TrueVision HD Camera                    | 1         | 1.23%   |
| Microsoft LifeCam HD-3000                         | 1         | 1.23%   |
| Microdia Webcam Vitade AF                         | 1         | 1.23%   |
| Microdia Webcam                                   | 1         | 1.23%   |
| Microdia USB 2.0 Camera                           | 1         | 1.23%   |
| Microdia Sonix USB 2.0 Camera                     | 1         | 1.23%   |
| Microdia Integrated_Webcam_HD                     | 1         | 1.23%   |
| Microdia Integrated_Webcam_2M                     | 1         | 1.23%   |
| Microdia Camera                                   | 1         | 1.23%   |
| MacroSilicon USB Video                            | 1         | 1.23%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]     | 1         | 1.23%   |
| Logitech Webcam C930e                             | 1         | 1.23%   |
| Logitech HD Webcam C615                           | 1         | 1.23%   |
| Logitech C922 Pro Stream Webcam                   | 1         | 1.23%   |
| Logitech C505 HD Webcam                           | 1         | 1.23%   |
| IMC Networks VGA UVC WebCam                       | 1         | 1.23%   |
| IMC Networks Integrated Camera                    | 1         | 1.23%   |
| IMC Networks HP TrueVision HD Camera              | 1         | 1.23%   |
| IMC Networks EasyCamera                           | 1         | 1.23%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1         | 1.23%   |
| Chicony WebCam                                    | 1         | 1.23%   |
| Chicony USB2.0 VGA UVC WebCam                     | 1         | 1.23%   |
| Chicony USB2.0 Camera                             | 1         | 1.23%   |
| Chicony USB 5M WebCam                             | 1         | 1.23%   |
| Chicony thinkpad t430s camera                     | 1         | 1.23%   |
| Chicony Lenovo EasyCamera                         | 1         | 1.23%   |
| Chicony Integrated IR Camera                      | 1         | 1.23%   |
| Chicony Integrated Camera (1280x720@30)           | 1         | 1.23%   |
| Chicony HP Wide Vision HD Camera                  | 1         | 1.23%   |
| Chicony HP 720p HD Monitor Webcam                 | 1         | 1.23%   |
| Chicony HD WebCam (Acer)                          | 1         | 1.23%   |
| Chicony HD User Facing                            | 1         | 1.23%   |
| Chicony EasyCamera                                | 1         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam     | 1         | 1.23%   |
| Acer ThinkPad P50 Integrated Camera               | 1         | 1.23%   |
| Acer SunplusIT Integrated Camera                  | 1         | 1.23%   |
| Acer SunplusIT INC. Integrated Camera             | 1         | 1.23%   |
| Acer OrbiCam                                      | 1         | 1.23%   |
| Acer Lenovo EasyCamera                            | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 55.56%  |
| Validity Sensors           | 3         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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
| 0     | 96        | 81.36%  |
| 1     | 14        | 11.86%  |
| 2     | 6         | 5.08%   |
| 3     | 2         | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


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

