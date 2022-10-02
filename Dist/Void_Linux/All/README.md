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

Total: 161

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Raspberry ... | Raspberry Pi                | Soc         | [a3485b332a](https://linux-hardware.org/?probe=a3485b332a) | Sep 27, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
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
| Void Linux Rolling | 72        | 57.6%   |
| Void Linux         | 53        | 42.4%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 121       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 7         | 5.38%   |
| 5.8.18_1    | 5         | 3.85%   |
| 5.3.9_1     | 4         | 3.08%   |
| 5.16.20_1   | 4         | 3.08%   |
| 5.10.17_1   | 4         | 3.08%   |
| 5.8.12_1    | 3         | 2.31%   |
| 5.18.19_1   | 3         | 2.31%   |
| 5.18.14_1   | 3         | 2.31%   |
| 5.15.32_1   | 3         | 2.31%   |
| 5.13.13_1   | 3         | 2.31%   |
| 5.12.10_1   | 3         | 2.31%   |
| 5.9.14_1    | 2         | 1.54%   |
| 5.4.24_1    | 2         | 1.54%   |
| 5.4.13_2    | 2         | 1.54%   |
| 5.18.9_1    | 2         | 1.54%   |
| 5.15.34_1   | 2         | 1.54%   |
| 5.15.22_1   | 2         | 1.54%   |
| 5.15.16_1   | 2         | 1.54%   |
| 5.13.15_1   | 2         | 1.54%   |
| 5.13.10_1   | 2         | 1.54%   |
| 5.12.14_1   | 2         | 1.54%   |
| 5.11.9_1    | 2         | 1.54%   |
| 5.10.14_1   | 2         | 1.54%   |
| 5.9.16_1    | 1         | 0.77%   |
| 5.9.0-rc8_2 | 1         | 0.77%   |
| 5.8.9_1     | 1         | 0.77%   |
| 5.8.8_1     | 1         | 0.77%   |
| 5.8.7_1     | 1         | 0.77%   |
| 5.8.6_1     | 1         | 0.77%   |
| 5.8.5_1     | 1         | 0.77%   |
| 5.8.16_1    | 1         | 0.77%   |
| 5.8.14_1    | 1         | 0.77%   |
| 5.8.12_2    | 1         | 0.77%   |
| 5.8.11_1    | 1         | 0.77%   |
| 5.8.10_1    | 1         | 0.77%   |
| 5.7.16_1    | 1         | 0.77%   |
| 5.6.14_1    | 1         | 0.77%   |
| 5.4.35_1    | 1         | 0.77%   |
| 5.4.21_1    | 1         | 0.77%   |
| 5.4.15_1    | 1         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 5.38%   |
| 5.8.18  | 5         | 3.85%   |
| 5.8.12  | 4         | 3.08%   |
| 5.3.9   | 4         | 3.08%   |
| 5.16.20 | 4         | 3.08%   |
| 5.10.17 | 4         | 3.08%   |
| 5.18.19 | 3         | 2.31%   |
| 5.18.14 | 3         | 2.31%   |
| 5.15.32 | 3         | 2.31%   |
| 5.13.13 | 3         | 2.31%   |
| 5.12.10 | 3         | 2.31%   |
| 5.9.14  | 2         | 1.54%   |
| 5.4.24  | 2         | 1.54%   |
| 5.4.13  | 2         | 1.54%   |
| 5.18.9  | 2         | 1.54%   |
| 5.15.34 | 2         | 1.54%   |
| 5.15.22 | 2         | 1.54%   |
| 5.15.16 | 2         | 1.54%   |
| 5.13.15 | 2         | 1.54%   |
| 5.13.10 | 2         | 1.54%   |
| 5.12.14 | 2         | 1.54%   |
| 5.11.9  | 2         | 1.54%   |
| 5.10.14 | 2         | 1.54%   |
| 5.9.16  | 1         | 0.77%   |
| 5.9.0   | 1         | 0.77%   |
| 5.8.9   | 1         | 0.77%   |
| 5.8.8   | 1         | 0.77%   |
| 5.8.7   | 1         | 0.77%   |
| 5.8.6   | 1         | 0.77%   |
| 5.8.5   | 1         | 0.77%   |
| 5.8.16  | 1         | 0.77%   |
| 5.8.14  | 1         | 0.77%   |
| 5.8.11  | 1         | 0.77%   |
| 5.8.10  | 1         | 0.77%   |
| 5.7.16  | 1         | 0.77%   |
| 5.6.14  | 1         | 0.77%   |
| 5.4.35  | 1         | 0.77%   |
| 5.4.21  | 1         | 0.77%   |
| 5.4.15  | 1         | 0.77%   |
| 5.3.16  | 1         | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 23        | 17.83%  |
| 5.8     | 18        | 13.95%  |
| 5.13    | 16        | 12.4%   |
| 5.10    | 15        | 11.63%  |
| 5.18    | 11        | 8.53%   |
| 5.12    | 9         | 6.98%   |
| 5.4     | 7         | 5.43%   |
| 5.3     | 5         | 3.88%   |
| 5.11    | 5         | 3.88%   |
| 5.9     | 4         | 3.1%    |
| 5.16    | 4         | 3.1%    |
| 4.19    | 4         | 3.1%    |
| 5.7     | 1         | 0.78%   |
| 5.6     | 1         | 0.78%   |
| 5.2     | 1         | 0.78%   |
| 5.17    | 1         | 0.78%   |
| 5.14    | 1         | 0.78%   |
| 5.1     | 1         | 0.78%   |
| 4.4     | 1         | 0.78%   |
| 4.14    | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 110       | 90.91%  |
| i686    | 5         | 4.13%   |
| aarch64 | 3         | 2.48%   |
| ppc64le | 1         | 0.83%   |
| ppc64   | 1         | 0.83%   |
| armv7l  | 1         | 0.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 50%     |
| XFCE       | 15        | 11.9%   |
| KDE        | 10        | 7.94%   |
| MATE       | 6         | 4.76%   |
| GNOME      | 6         | 4.76%   |
| KDE5       | 5         | 3.97%   |
| i3         | 5         | 3.97%   |
| X-Cinnamon | 3         | 2.38%   |
| openbox    | 3         | 2.38%   |
| bspwm      | 3         | 2.38%   |
| awesome    | 3         | 2.38%   |
| Lumina     | 2         | 1.59%   |
| sway       | 1         | 0.79%   |
| river      | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 86        | 69.92%  |
| Tty     | 13        | 10.57%  |
| Wayland | 12        | 9.76%   |
| Unknown | 12        | 9.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 110       | 89.43%  |
| LightDM | 5         | 4.07%   |
| LXDM    | 4         | 3.25%   |
| SDDM    | 3         | 2.44%   |
| GDM     | 1         | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 63        | 50%     |
| Unknown | 20        | 15.87%  |
| en_GB   | 7         | 5.56%   |
| en_DK   | 6         | 4.76%   |
| ru_RU   | 5         | 3.97%   |
| fr_FR   | 3         | 2.38%   |
| de_DE   | 3         | 2.38%   |
| pt_BR   | 2         | 1.59%   |
| pl_PL   | 2         | 1.59%   |
| en_AU   | 2         | 1.59%   |
| cs_CZ   | 2         | 1.59%   |
| tr_TR   | 1         | 0.79%   |
| ru_UA   | 1         | 0.79%   |
| nb_NO   | 1         | 0.79%   |
| es_HN   | 1         | 0.79%   |
| es_ES   | 1         | 0.79%   |
| es_DO   | 1         | 0.79%   |
| en_NZ   | 1         | 0.79%   |
| en_IE   | 1         | 0.79%   |
| en_CA   | 1         | 0.79%   |
| el_GR   | 1         | 0.79%   |
| bg_BG   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 63        | 50.81%  |
| BIOS | 61        | 49.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 78        | 63.41%  |
| Btrfs   | 24        | 19.51%  |
| Xfs     | 8         | 6.5%    |
| Zfs     | 6         | 4.88%   |
| Unknown | 5         | 4.07%   |
| F2fs    | 1         | 0.81%   |
| Ext3    | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 67        | 54.03%  |
| Unknown | 38        | 30.65%  |
| MBR     | 19        | 15.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 87.6%   |
| Yes       | 15        | 12.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 81.15%  |
| Yes       | 23        | 18.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 28        | 23.14%  |
| Lenovo                  | 16        | 13.22%  |
| Hewlett-Packard         | 13        | 10.74%  |
| Acer                    | 12        | 9.92%   |
| Dell                    | 11        | 9.09%   |
| MSI                     | 8         | 6.61%   |
| ASRock                  | 8         | 6.61%   |
| Unknown                 | 5         | 4.13%   |
| Gigabyte Technology     | 4         | 3.31%   |
| HUAWEI                  | 2         | 1.65%   |
| Samsung Electronics     | 1         | 0.83%   |
| Raspberry Pi Foundation | 1         | 0.83%   |
| Positivo                | 1         | 0.83%   |
| Pine Microsystems       | 1         | 0.83%   |
| Notebook                | 1         | 0.83%   |
| Nokia                   | 1         | 0.83%   |
| Microsoft               | 1         | 0.83%   |
| Getac                   | 1         | 0.83%   |
| Framework               | 1         | 0.83%   |
| Exo                     | 1         | 0.83%   |
| Digibras                | 1         | 0.83%   |
| Cisco Systems           | 1         | 0.83%   |
| Chuwi                   | 1         | 0.83%   |
| Apple                   | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 5         | 4.13%   |
| HP Laptop 15-bw0xx                     | 2         | 1.65%   |
| Dell OptiPlex 7010                     | 2         | 1.65%   |
| ASUS PRIME Z390-P                      | 2         | 1.65%   |
| Acer Swift SF314-42                    | 2         | 1.65%   |
| Samsung 275E4E/275E5E                  | 1         | 0.83%   |
| RPi Raspberry Pi                       | 1         | 0.83%   |
| Positivo Mobile                        | 1         | 0.83%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.83%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.83%   |
| Nokia Booklet 3G                       | 1         | 0.83%   |
| MSI MS-7D14                            | 1         | 0.83%   |
| MSI MS-7C92                            | 1         | 0.83%   |
| MSI MS-7C52                            | 1         | 0.83%   |
| MSI MS-7C02                            | 1         | 0.83%   |
| MSI MS-7A68                            | 1         | 0.83%   |
| MSI MS-7A39                            | 1         | 0.83%   |
| MSI MS-7816                            | 1         | 0.83%   |
| MSI Bravo 15 A4DDR                     | 1         | 0.83%   |
| Microsoft Surface with Windows RT      | 1         | 0.83%   |
| Lenovo Yoga 720-15IKB 80X7             | 1         | 0.83%   |
| Lenovo ThinkPad X260 20F5S08Q00        | 1         | 0.83%   |
| Lenovo ThinkPad X240 20AMA34HMN        | 1         | 0.83%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L6SA5Q00        | 1         | 0.83%   |
| Lenovo ThinkPad T460 20FMS0WN00        | 1         | 0.83%   |
| Lenovo ThinkPad T430 2349PS3           | 1         | 0.83%   |
| Lenovo ThinkPad T420 4180A21           | 1         | 0.83%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW  | 1         | 0.83%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00  | 1         | 0.83%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200   | 1         | 0.83%   |
| Lenovo ThinkPad E595 20NFCTO1WW        | 1         | 0.83%   |
| Lenovo IdeaPad Z570 10246ZG            | 1         | 0.83%   |
| Lenovo IdeaPad S145-14IIL 81W6         | 1         | 0.83%   |
| Lenovo IdeaPad 710S-13IKB 80VQ         | 1         | 0.83%   |
| Lenovo G50-45 80E3                     | 1         | 0.83%   |
| HUAWEI KLVL-WXXW                       | 1         | 0.83%   |
| HUAWEI HN-WX9X                         | 1         | 0.83%   |
| HP Z2 Mini G3 Workstation              | 1         | 0.83%   |
| HP Stream 7 Tablet                     | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 9.09%   |
| Acer Aspire              | 7         | 5.79%   |
| ASUS PRIME               | 6         | 4.96%   |
| HP Laptop                | 5         | 4.13%   |
| Unknown                  | 5         | 4.13%   |
| Dell OptiPlex            | 4         | 3.31%   |
| ASUS VivoBook            | 4         | 3.31%   |
| Lenovo IdeaPad           | 3         | 2.48%   |
| Dell Inspiron            | 3         | 2.48%   |
| HP Pavilion              | 2         | 1.65%   |
| Dell Latitude            | 2         | 1.65%   |
| ASUS TUF                 | 2         | 1.65%   |
| ASUS ROG                 | 2         | 1.65%   |
| Acer Swift               | 2         | 1.65%   |
| Samsung 275E4E           | 1         | 0.83%   |
| RPi Raspberry            | 1         | 0.83%   |
| Positivo Mobile          | 1         | 0.83%   |
| Pine Microsystems Pine64 | 1         | 0.83%   |
| Notebook NV4XMB          | 1         | 0.83%   |
| Nokia Booklet            | 1         | 0.83%   |
| MSI MS-7D14              | 1         | 0.83%   |
| MSI MS-7C92              | 1         | 0.83%   |
| MSI MS-7C52              | 1         | 0.83%   |
| MSI MS-7C02              | 1         | 0.83%   |
| MSI MS-7A68              | 1         | 0.83%   |
| MSI MS-7A39              | 1         | 0.83%   |
| MSI MS-7816              | 1         | 0.83%   |
| MSI Bravo                | 1         | 0.83%   |
| Microsoft Surface        | 1         | 0.83%   |
| Lenovo Yoga              | 1         | 0.83%   |
| Lenovo G50-45            | 1         | 0.83%   |
| HUAWEI KLVL-WXXW         | 1         | 0.83%   |
| HUAWEI HN-WX9X           | 1         | 0.83%   |
| HP Z2                    | 1         | 0.83%   |
| HP Stream                | 1         | 0.83%   |
| HP Notebook              | 1         | 0.83%   |
| HP ENVY                  | 1         | 0.83%   |
| HP Compaq                | 1         | 0.83%   |
| HP 15                    | 1         | 0.83%   |
| Gigabyte H310M           | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 18        | 14.88%  |
| 2020    | 14        | 11.57%  |
| 2018    | 14        | 11.57%  |
| 2017    | 11        | 9.09%   |
| 2016    | 9         | 7.44%   |
| 2013    | 9         | 7.44%   |
| 2014    | 8         | 6.61%   |
| 2012    | 8         | 6.61%   |
| 2015    | 5         | 4.13%   |
| 2011    | 5         | 4.13%   |
| Unknown | 5         | 4.13%   |
| 2021    | 4         | 3.31%   |
| 2010    | 4         | 3.31%   |
| 2009    | 2         | 1.65%   |
| 2008    | 2         | 1.65%   |
| 2022    | 1         | 0.83%   |
| 2006    | 1         | 0.83%   |
| 2005    | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 70        | 57.85%  |
| Desktop        | 43        | 35.54%  |
| Convertible    | 3         | 2.48%   |
| Tablet         | 2         | 1.65%   |
| System on chip | 1         | 0.83%   |
| Mini pc        | 1         | 0.83%   |
| Server         | 1         | 0.83%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 26        | 21.14%  |
| 16.01-24.0      | 26        | 21.14%  |
| 8.01-16.0       | 24        | 19.51%  |
| 3.01-4.0        | 21        | 17.07%  |
| 32.01-64.0      | 11        | 8.94%   |
| 1.01-2.0        | 6         | 4.88%   |
| 0.51-1.0        | 4         | 3.25%   |
| 64.01-256.0     | 2         | 1.63%   |
| More than 256.0 | 1         | 0.81%   |
| 24.01-32.0      | 1         | 0.81%   |
| 2.01-3.0        | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 35        | 26.92%  |
| 2.01-3.0    | 30        | 23.08%  |
| 0.51-1.0    | 22        | 16.92%  |
| 4.01-8.0    | 13        | 10%     |
| 3.01-4.0    | 13        | 10%     |
| 8.01-16.0   | 7         | 5.38%   |
| 0.01-0.5    | 6         | 4.62%   |
| 16.01-24.0  | 3         | 2.31%   |
| 64.01-256.0 | 1         | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 59.84%  |
| 2      | 28        | 22.95%  |
| 3      | 15        | 12.3%   |
| 5      | 2         | 1.64%   |
| 4      | 2         | 1.64%   |
| 9      | 1         | 0.82%   |
| 0      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 76.86%  |
| Yes       | 28        | 23.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 82.64%  |
| No        | 21        | 17.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 68.6%   |
| No        | 38        | 31.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 57.38%  |
| No        | 52        | 42.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 24        | 19.83%  |
| Russia             | 10        | 8.26%   |
| India              | 9         | 7.44%   |
| Germany            | 9         | 7.44%   |
| Brazil             | 7         | 5.79%   |
| Czechia            | 6         | 4.96%   |
| Denmark            | 5         | 4.13%   |
| Ukraine            | 4         | 3.31%   |
| UK                 | 4         | 3.31%   |
| Poland             | 4         | 3.31%   |
| France             | 4         | 3.31%   |
| Turkey             | 3         | 2.48%   |
| Switzerland        | 3         | 2.48%   |
| Netherlands        | 3         | 2.48%   |
| Bulgaria           | 3         | 2.48%   |
| Spain              | 2         | 1.65%   |
| Morocco            | 2         | 1.65%   |
| Greece             | 2         | 1.65%   |
| Australia          | 2         | 1.65%   |
| Argentina          | 2         | 1.65%   |
| Vietnam            | 1         | 0.83%   |
| Sweden             | 1         | 0.83%   |
| Peru               | 1         | 0.83%   |
| Norway             | 1         | 0.83%   |
| New Zealand        | 1         | 0.83%   |
| Mexico             | 1         | 0.83%   |
| Indonesia          | 1         | 0.83%   |
| Honduras           | 1         | 0.83%   |
| Ecuador            | 1         | 0.83%   |
| Dominican Republic | 1         | 0.83%   |
| Canada             | 1         | 0.83%   |
| Belgium            | 1         | 0.83%   |
| Bangladesh         | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 5         | 4.03%   |
| Denver             | 3         | 2.42%   |
| Amsterdam          | 3         | 2.42%   |
| St Petersburg      | 2         | 1.61%   |
| Sofia              | 2         | 1.61%   |
| Orlando            | 2         | 1.61%   |
| Munich             | 2         | 1.61%   |
| Moscow             | 2         | 1.61%   |
| Meknes             | 2         | 1.61%   |
| Lublin             | 2         | 1.61%   |
| Hyderabad          | 2         | 1.61%   |
| Geneva             | 2         | 1.61%   |
| Zagnansk           | 1         | 0.81%   |
| Yekaterinburg      | 1         | 0.81%   |
| Yambol             | 1         | 0.81%   |
| Weatherford        | 1         | 0.81%   |
| Vlaardingen        | 1         | 0.81%   |
| Viby J             | 1         | 0.81%   |
| Varna              | 1         | 0.81%   |
| Trujillo           | 1         | 0.81%   |
| Toulouse           | 1         | 0.81%   |
| Toms River         | 1         | 0.81%   |
| Tegucigalpa        | 1         | 0.81%   |
| Syktyvkar          | 1         | 0.81%   |
| Surabaya           | 1         | 0.81%   |
| Stratford          | 1         | 0.81%   |
| South Shields      | 1         | 0.81%   |
| Solone             | 1         | 0.81%   |
| Sistranda          | 1         | 0.81%   |
| Saxtons River      | 1         | 0.81%   |
| Sao Paulo          | 1         | 0.81%   |
| Santo Domingo      | 1         | 0.81%   |
| Saint-Paul-les-Dax | 1         | 0.81%   |
| Saint Paul         | 1         | 0.81%   |
| Rostock            | 1         | 0.81%   |
| Rosenheim          | 1         | 0.81%   |
| Rosario            | 1         | 0.81%   |
| Rio de Janeiro     | 1         | 0.81%   |
| Richmond           | 1         | 0.81%   |
| Regensburg         | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 51     | 21.02%  |
| WDC                 | 32        | 39     | 18.18%  |
| Seagate             | 29        | 34     | 16.48%  |
| Kingston            | 11        | 11     | 6.25%   |
| Unknown             | 9         | 14     | 5.11%   |
| Toshiba             | 9         | 10     | 5.11%   |
| SanDisk             | 7         | 8      | 3.98%   |
| Intel               | 7         | 9      | 3.98%   |
| HGST                | 7         | 8      | 3.98%   |
| Hitachi             | 4         | 4      | 2.27%   |
| Crucial             | 4         | 5      | 2.27%   |
| SK hynix            | 2         | 2      | 1.14%   |
| Phison              | 2         | 2      | 1.14%   |
| Patriot             | 2         | 2      | 1.14%   |
| Corsair             | 2         | 2      | 1.14%   |
| A-DATA Technology   | 2         | 3      | 1.14%   |
| XPG                 | 1         | 4      | 0.57%   |
| Transcend           | 1         | 1      | 0.57%   |
| SPCC                | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Maxtor              | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| Gigabyte Technology | 1         | 2      | 0.57%   |
| China               | 1         | 1      | 0.57%   |
| BHT                 | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 5         | 2.56%   |
| Unknown MMC Card  32GB                  | 4         | 2.05%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 2.05%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.54%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 1.54%   |
| Samsung SSD 870 EVO 500GB               | 3         | 1.54%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 1.54%   |
| Kingston SHFS37A120G 120GB SSD          | 3         | 1.54%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.03%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 1.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.03%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 1.03%   |
| Samsung SSD 980 PRO 500GB               | 2         | 1.03%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.03%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.03%   |
| Samsung SSD 850 EVO 500GB               | 2         | 1.03%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 1.03%   |
| Patriot Burst 120GB SSD                 | 2         | 1.03%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 1.03%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.03%   |
| HGST HTS541010B7E610 1TB                | 2         | 1.03%   |
| XPG NVMe SSD Drive 2TB                  | 1         | 0.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.51%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.51%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.51%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.51%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.51%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.51%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.51%   |
| WDC WD3200AAKS-22SBA0 320GB             | 1         | 0.51%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.51%   |
| WDC WD20EZBX-00AYRA0 2TB                | 1         | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.51%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.51%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 34     | 35.8%   |
| WDC                 | 27        | 33     | 33.33%  |
| Toshiba             | 8         | 9      | 9.88%   |
| HGST                | 7         | 8      | 8.64%   |
| Samsung Electronics | 5         | 5      | 6.17%   |
| Hitachi             | 4         | 4      | 4.94%   |
| Maxtor              | 1         | 1      | 1.23%   |

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
| HDD     | 67        | 94     | 42.41%  |
| SSD     | 45        | 55     | 28.48%  |
| NVMe    | 36        | 54     | 22.78%  |
| MMC     | 8         | 12     | 5.06%   |
| Unknown | 2         | 3      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 91        | 147    | 65.47%  |
| NVMe | 36        | 54     | 25.9%   |
| MMC  | 8         | 12     | 5.76%   |
| SAS  | 4         | 5      | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 79     | 52.07%  |
| 0.51-1.0   | 41        | 48     | 33.88%  |
| 1.01-2.0   | 14        | 18     | 11.57%  |
| 4.01-10.0  | 2         | 2      | 1.65%   |
| 3.01-4.0   | 1         | 2      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 25%     |
| 501-1000       | 25        | 20.16%  |
| 101-250        | 22        | 17.74%  |
| Unknown        | 12        | 9.68%   |
| 1001-2000      | 10        | 8.06%   |
| 1-20           | 7         | 5.65%   |
| More than 3000 | 6         | 4.84%   |
| 21-50          | 4         | 3.23%   |
| 2001-3000      | 4         | 3.23%   |
| 51-100         | 3         | 2.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 26.56%  |
| 101-250        | 30        | 23.44%  |
| 21-50          | 17        | 13.28%  |
| 251-500        | 12        | 9.38%   |
| Unknown        | 12        | 9.38%   |
| 51-100         | 11        | 8.59%   |
| 1001-2000      | 5         | 3.91%   |
| 501-1000       | 4         | 3.13%   |
| More than 3000 | 2         | 1.56%   |
| 2001-3000      | 1         | 0.78%   |

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
| Works    | 71        | 108    | 49.65%  |
| Detected | 48        | 81     | 33.57%  |
| Malfunc  | 24        | 29     | 16.78%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 44.14%  |
| AMD                              | 38        | 26.21%  |
| Samsung Electronics              | 21        | 14.48%  |
| SanDisk                          | 4         | 2.76%   |
| Phison Electronics               | 3         | 2.07%   |
| SK hynix                         | 2         | 1.38%   |
| Micron/Crucial Technology        | 2         | 1.38%   |
| ADATA Technology                 | 2         | 1.38%   |
| Toshiba America Info Systems     | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Nvidia                           | 1         | 0.69%   |
| Marvell Technology Group         | 1         | 0.69%   |
| LSI Logic / Symbios Logic        | 1         | 0.69%   |
| Kingston Technology Company      | 1         | 0.69%   |
| JMicron Technology               | 1         | 0.69%   |
| Broadcom                         | 1         | 0.69%   |
| ASMedia Technology               | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 16.46%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 7.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.1%    |
| AMD 400 Series Chipset SATA Controller                                           | 8         | 4.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 4.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 2.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.83%   |
| Intel SSD 660P Series                                                            | 3         | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 1.83%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 1.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.22%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 1.22%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.22%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 1.22%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.61%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.61%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.61%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.61%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.61%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.61%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.61%   |
| Micron/Crucial Non-Volatile memory controller                                    | 1         | 0.61%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.61%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                      | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 89        | 60.54%  |
| NVMe | 37        | 25.17%  |
| IDE  | 13        | 8.84%   |
| RAID | 8         | 5.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 58.68%  |
| AMD                      | 44        | 36.36%  |
| ARM                      | 4         | 3.31%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.83%   |
| PowerMac11,2             | 1         | 0.83%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 3.31%   |
| ARM Processor                                      | 3         | 2.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.65%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.65%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 2         | 1.65%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.65%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.65%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.65%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.83%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.83%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.83%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.83%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.83%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.83%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.83%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.83%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 1         | 0.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 0.83%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz                  | 1         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 1         | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 0.83%   |
| Intel Core i7-4600U CPU @ 2.10GHz                  | 1         | 0.83%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 0.83%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 0.83%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 1         | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz                  | 1         | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz                  | 1         | 0.83%   |
| Intel Core i5-6400 CPU @ 2.70GHz                   | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 19.01%  |
| AMD Ryzen 5             | 15        | 12.4%   |
| Intel Core i7           | 14        | 11.57%  |
| Other                   | 13        | 10.74%  |
| Intel Core i3           | 11        | 9.09%   |
| AMD Ryzen 7             | 9         | 7.44%   |
| Intel Atom              | 6         | 4.96%   |
| Intel Celeron           | 4         | 3.31%   |
| Intel Pentium           | 2         | 1.65%   |
| Intel Core 2 Duo        | 2         | 1.65%   |
| AMD Ryzen 7 PRO         | 2         | 1.65%   |
| AMD Ryzen 3             | 2         | 1.65%   |
| AMD FX                  | 2         | 1.65%   |
| AMD A8                  | 2         | 1.65%   |
| Intel Xeon              | 1         | 0.83%   |
| Intel Pentium Gold      | 1         | 0.83%   |
| Intel Pentium 4         | 1         | 0.83%   |
| Intel Genuine           | 1         | 0.83%   |
| Intel Core i9           | 1         | 0.83%   |
| AMD Turion 64 X2 Mobile | 1         | 0.83%   |
| AMD Ryzen Threadripper  | 1         | 0.83%   |
| AMD Phenom II X4        | 1         | 0.83%   |
| AMD E2                  | 1         | 0.83%   |
| AMD E1                  | 1         | 0.83%   |
| AMD C-60                | 1         | 0.83%   |
| AMD Athlon II X3        | 1         | 0.83%   |
| AMD Athlon II X2        | 1         | 0.83%   |
| AMD A4                  | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 42        | 34.71%  |
| 2       | 42        | 34.71%  |
| 6       | 16        | 13.22%  |
| 8       | 12        | 9.92%   |
| 1       | 5         | 4.13%   |
| 64      | 1         | 0.83%   |
| 12      | 1         | 0.83%   |
| 3       | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 118       | 97.52%  |
| 2       | 2         | 1.65%   |
| Unknown | 1         | 0.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 77        | 63.64%  |
| 1       | 42        | 34.71%  |
| 4       | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 88.43%  |
| Unknown        | 8         | 6.61%   |
| 64-bit         | 3         | 2.48%   |
| 32-bit         | 3         | 2.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 32.26%  |
| 0x306a9    | 7         | 5.65%   |
| 0x40651    | 6         | 4.84%   |
| 0x906ea    | 4         | 3.23%   |
| 0x906e9    | 3         | 2.42%   |
| 0x806ea    | 3         | 2.42%   |
| 0x806e9    | 3         | 2.42%   |
| 0x406e3    | 3         | 2.42%   |
| 0x08600104 | 3         | 2.42%   |
| 0x08108102 | 3         | 2.42%   |
| 0x806ec    | 2         | 1.61%   |
| 0x30678    | 2         | 1.61%   |
| 0x206a7    | 2         | 1.61%   |
| 0x106c2    | 2         | 1.61%   |
| 0x0a201009 | 2         | 1.61%   |
| 0x08701021 | 2         | 1.61%   |
| 0x0800820d | 2         | 1.61%   |
| 0x07030105 | 2         | 1.61%   |
| 0x06006705 | 2         | 1.61%   |
| 0x06000852 | 2         | 1.61%   |
| 0x05000119 | 2         | 1.61%   |
| 0x010000c8 | 2         | 1.61%   |
| 0xa0671    | 1         | 0.81%   |
| 0x906ed    | 1         | 0.81%   |
| 0x90672    | 1         | 0.81%   |
| 0x806eb    | 1         | 0.81%   |
| 0x706a1    | 1         | 0.81%   |
| 0x506e3    | 1         | 0.81%   |
| 0x406c4    | 1         | 0.81%   |
| 0x306d4    | 1         | 0.81%   |
| 0x306c3    | 1         | 0.81%   |
| 0x106ca    | 1         | 0.81%   |
| 0x106a5    | 1         | 0.81%   |
| 0x1067a    | 1         | 0.81%   |
| 0x0a50000c | 1         | 0.81%   |
| 0x0a201205 | 1         | 0.81%   |
| 0x08701013 | 1         | 0.81%   |
| 0x08608103 | 1         | 0.81%   |
| 0x08608102 | 1         | 0.81%   |
| 0x08600106 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 19.01%  |
| Zen 2            | 10        | 8.26%   |
| IvyBridge        | 10        | 8.26%   |
| Haswell          | 9         | 7.44%   |
| Unknown          | 8         | 6.61%   |
| Zen+             | 7         | 5.79%   |
| Zen 3            | 6         | 4.96%   |
| Skylake          | 6         | 4.96%   |
| Zen              | 4         | 3.31%   |
| Silvermont       | 4         | 3.31%   |
| Excavator        | 4         | 3.31%   |
| SandyBridge      | 3         | 2.48%   |
| Puma             | 3         | 2.48%   |
| K10              | 3         | 2.48%   |
| Bonnell          | 3         | 2.48%   |
| TigerLake        | 2         | 1.65%   |
| Piledriver       | 2         | 1.65%   |
| Penryn           | 2         | 1.65%   |
| Icelake          | 2         | 1.65%   |
| Goldmont plus    | 2         | 1.65%   |
| Bobcat           | 2         | 1.65%   |
| NetBurst         | 1         | 0.83%   |
| Nehalem          | 1         | 0.83%   |
| K8 Hammer        | 1         | 0.83%   |
| Core             | 1         | 0.83%   |
| Broadwell        | 1         | 0.83%   |
| Alderlake Hybrid | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 55        | 39.01%  |
| Nvidia                           | 42        | 29.79%  |
| AMD                              | 41        | 29.08%  |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |
| Matrox Electronics Systems       | 1         | 0.71%   |
| ASPEED Technology                | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 5.52%   |
| AMD Renoir                                                                | 6         | 4.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 5         | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 4         | 2.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.76%   |
| Intel UHD Graphics 620                                                    | 4         | 2.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.76%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.07%   |
| Intel HD Graphics 620                                                     | 3         | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 1.38%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.38%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 2         | 1.38%   |
| Nvidia GK208B [GeForce GT 710]                                            | 2         | 1.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.38%   |
| AMD Lucienne                                                              | 2         | 1.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2         | 1.38%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                        | 2         | 1.38%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.69%   |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1         | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 1         | 0.69%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                     | 1         | 0.69%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                 | 1         | 0.69%   |
| Nvidia NV43 [GeForce 6600]                                                | 1         | 0.69%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.69%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 29.27%  |
| 1 x AMD        | 35        | 28.46%  |
| 1 x Nvidia     | 22        | 17.89%  |
| Intel + Nvidia | 17        | 13.82%  |
| Other          | 4         | 3.25%   |
| 2 x AMD        | 2         | 1.63%   |
| AMD + Nvidia   | 2         | 1.63%   |
| 2 x Nvidia     | 1         | 0.81%   |
| 1 x SiS        | 1         | 0.81%   |
| 1 x Matrox     | 1         | 0.81%   |
| Intel + AMD    | 1         | 0.81%   |
| AMD + ASPEED   | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 68.29%  |
| Proprietary | 34        | 27.64%  |
| Unknown     | 5         | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 53.17%  |
| 1.01-2.0   | 17        | 13.49%  |
| 0.01-0.5   | 14        | 11.11%  |
| 3.01-4.0   | 10        | 7.94%   |
| 0.51-1.0   | 7         | 5.56%   |
| 5.01-6.0   | 4         | 3.17%   |
| 7.01-8.0   | 2         | 1.59%   |
| 2.01-3.0   | 2         | 1.59%   |
| 8.01-16.0  | 2         | 1.59%   |
| 16.01-24.0 | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 18        | 14.06%  |
| Chimei Innolux       | 15        | 11.72%  |
| BOE                  | 13        | 10.16%  |
| LG Display           | 12        | 9.38%   |
| Samsung Electronics  | 10        | 7.81%   |
| Hewlett-Packard      | 8         | 6.25%   |
| Dell                 | 8         | 6.25%   |
| Acer                 | 5         | 3.91%   |
| Philips              | 4         | 3.13%   |
| Iiyama               | 4         | 3.13%   |
| Goldstar             | 3         | 2.34%   |
| BenQ                 | 3         | 2.34%   |
| PANDA                | 2         | 1.56%   |
| Lenovo               | 2         | 1.56%   |
| Fujitsu Siemens      | 2         | 1.56%   |
| ASUSTek Computer     | 2         | 1.56%   |
| Apple                | 2         | 1.56%   |
| AOC                  | 2         | 1.56%   |
| Ancor Communications | 2         | 1.56%   |
| Unknown              | 1         | 0.78%   |
| STD                  | 1         | 0.78%   |
| Sceptre Tech         | 1         | 0.78%   |
| Sceptre              | 1         | 0.78%   |
| Panasonic            | 1         | 0.78%   |
| ONN                  | 1         | 0.78%   |
| MSI                  | 1         | 0.78%   |
| LG Philips           | 1         | 0.78%   |
| InnoLux Display      | 1         | 0.78%   |
| FUN                  | 1         | 0.78%   |
| CHR                  | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.24%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2         | 1.49%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.49%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.49%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.75%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                         | 1         | 0.75%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.75%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.75%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.75%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.75%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.75%   |
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
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.75%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.75%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 1         | 0.75%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 43.65%  |
| 1366x768 (WXGA)    | 26        | 20.63%  |
| 3840x2160 (4K)     | 5         | 3.97%   |
| 2560x1440 (QHD)    | 5         | 3.97%   |
| 1920x1200 (WUXGA)  | 5         | 3.97%   |
| 1680x1050 (WSXGA+) | 4         | 3.17%   |
| 3440x1440          | 3         | 2.38%   |
| 2160x1440          | 3         | 2.38%   |
| 1600x900 (HD+)     | 3         | 2.38%   |
| Unknown            | 3         | 2.38%   |
| 1280x800 (WXGA)    | 2         | 1.59%   |
| 1280x1024 (SXGA)   | 2         | 1.59%   |
| 1024x600           | 2         | 1.59%   |
| 7680x1080          | 1         | 0.79%   |
| 3840x1600          | 1         | 0.79%   |
| 3840x1080          | 1         | 0.79%   |
| 2560x1600          | 1         | 0.79%   |
| 2560x1080          | 1         | 0.79%   |
| 2256x1504          | 1         | 0.79%   |
| 1360x768           | 1         | 0.79%   |
| 1280x720 (HD)      | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 24.62%  |
| 24      | 15        | 11.54%  |
| 13      | 13        | 10%     |
| 14      | 12        | 9.23%   |
| Unknown | 11        | 8.46%   |
| 23      | 7         | 5.38%   |
| 27      | 6         | 4.62%   |
| 21      | 6         | 4.62%   |
| 22      | 4         | 3.08%   |
| 34      | 3         | 2.31%   |
| 12      | 3         | 2.31%   |
| 17      | 2         | 1.54%   |
| 11      | 2         | 1.54%   |
| 10      | 2         | 1.54%   |
| 84      | 1         | 0.77%   |
| 40      | 1         | 0.77%   |
| 39      | 1         | 0.77%   |
| 37      | 1         | 0.77%   |
| 33      | 1         | 0.77%   |
| 31      | 1         | 0.77%   |
| 28      | 1         | 0.77%   |
| 25      | 1         | 0.77%   |
| 20      | 1         | 0.77%   |
| 19      | 1         | 0.77%   |
| 18      | 1         | 0.77%   |
| 8       | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 37.98%  |
| 501-600     | 27        | 20.93%  |
| 201-300     | 16        | 12.4%   |
| 401-500     | 12        | 9.3%    |
| Unknown     | 11        | 8.53%   |
| 701-800     | 4         | 3.1%    |
| 801-900     | 3         | 2.33%   |
| 601-700     | 3         | 2.33%   |
| 351-400     | 2         | 1.55%   |
| 1501-2000   | 1         | 0.78%   |
| 101-200     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 71.9%   |
| 16/10   | 13        | 10.74%  |
| Unknown | 10        | 8.26%   |
| 21/9    | 5         | 4.13%   |
| 3/2     | 4         | 3.31%   |
| 5/4     | 2         | 1.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 25%     |
| 201-250        | 22        | 17.19%  |
| 81-90          | 19        | 14.84%  |
| Unknown        | 11        | 8.59%   |
| 251-300        | 10        | 7.81%   |
| 71-80          | 6         | 4.69%   |
| 301-350        | 6         | 4.69%   |
| 351-500        | 5         | 3.91%   |
| 61-70          | 3         | 2.34%   |
| 501-1000       | 3         | 2.34%   |
| 51-60          | 2         | 1.56%   |
| 41-50          | 2         | 1.56%   |
| 151-200        | 2         | 1.56%   |
| 141-150        | 2         | 1.56%   |
| More than 1000 | 1         | 0.78%   |
| 1-40           | 1         | 0.78%   |
| 131-140        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 32.31%  |
| 101-120       | 34        | 26.15%  |
| 121-160       | 30        | 23.08%  |
| 161-240       | 12        | 9.23%   |
| Unknown       | 11        | 8.46%   |
| More than 240 | 1         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 79.51%  |
| 2     | 22        | 18.03%  |
| 0     | 3         | 2.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 67        | 39.64%  |
| Intel                            | 46        | 27.22%  |
| Qualcomm Atheros                 | 17        | 10.06%  |
| Broadcom                         | 10        | 5.92%   |
| TP-Link                          | 3         | 1.78%   |
| Sierra Wireless                  | 3         | 1.78%   |
| Ralink Technology                | 3         | 1.78%   |
| Broadcom Limited                 | 3         | 1.78%   |
| Xiaomi                           | 2         | 1.18%   |
| Qualcomm Atheros Communications  | 2         | 1.18%   |
| Cypress Semiconductor            | 2         | 1.18%   |
| Tenda                            | 1         | 0.59%   |
| Standard Microsystems            | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |
| Ralink                           | 1         | 0.59%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.59%   |
| Nvidia                           | 1         | 0.59%   |
| MediaTek                         | 1         | 0.59%   |
| DisplayLink                      | 1         | 0.59%   |
| ASIX Electronics                 | 1         | 0.59%   |
| Arduino SA                       | 1         | 0.59%   |
| Apple                            | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 22.84%  |
| Intel Wi-Fi 6 AX200                                               | 10        | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 4.06%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.54%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.52%   |
| Intel Wireless 8260                                               | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.02%   |
| Intel Wireless 7260                                               | 2         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.02%   |
| Cypress K38231_03                                                 | 2         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.51%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.51%   |
| Tenda U12                                                         | 1         | 0.51%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.51%   |
| Sierra Wireless EM7455                                            | 1         | 0.51%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.51%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 37.93%  |
| Realtek Semiconductor           | 20        | 22.99%  |
| Qualcomm Atheros                | 15        | 17.24%  |
| Broadcom                        | 4         | 4.6%    |
| Sierra Wireless                 | 3         | 3.45%   |
| Ralink Technology               | 3         | 3.45%   |
| Broadcom Limited                | 3         | 3.45%   |
| TP-Link                         | 2         | 2.3%    |
| Qualcomm Atheros Communications | 2         | 2.3%    |
| Tenda                           | 1         | 1.15%   |
| Ralink                          | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 11.49%  |
| Intel Wireless 8265 / 8275                                              | 6         | 6.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.45%   |
| Intel Wireless 8260                                                     | 3         | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.3%    |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.3%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 2.3%    |
| Intel Wireless 7260                                                     | 2         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.15%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.15%   |
| Tenda U12                                                               | 1         | 1.15%   |
| Sierra Wireless EM7455                                                  | 1         | 1.15%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.15%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.15%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.15%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.15%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.15%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.15%   |
| Intel WiFi Link 5100                                                    | 1         | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.15%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 61        | 56.48%  |
| Intel                            | 25        | 23.15%  |
| Broadcom                         | 7         | 6.48%   |
| Qualcomm Atheros                 | 3         | 2.78%   |
| Xiaomi                           | 2         | 1.85%   |
| Cypress Semiconductor            | 2         | 1.85%   |
| TP-Link                          | 1         | 0.93%   |
| Standard Microsystems            | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| Nvidia                           | 1         | 0.93%   |
| MediaTek                         | 1         | 0.93%   |
| DisplayLink                      | 1         | 0.93%   |
| ASIX Electronics                 | 1         | 0.93%   |
| Apple                            | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 41.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.63%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.63%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.85%   |
| Cypress K38231_03                                                 | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.93%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.93%   |
| MediaTek Nokia 5.1 Plus                                           | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.93%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.93%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.93%   |
| Apple iPad 4/Mini1                                                | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 54.05%  |
| WiFi     | 83        | 44.86%  |
| Modem    | 1         | 0.54%   |
| Unknown  | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 58.82%  |
| Ethernet | 49        | 41.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 47.93%  |
| 2     | 51        | 42.15%  |
| 0     | 7         | 5.79%   |
| 3     | 4         | 3.31%   |
| 4     | 1         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 88.62%  |
| Yes  | 14        | 11.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 41.67%  |
| Realtek Semiconductor           | 12        | 16.67%  |
| Cambridge Silicon Radio         | 7         | 9.72%   |
| Lite-On Technology              | 6         | 8.33%   |
| Broadcom                        | 5         | 6.94%   |
| Qualcomm Atheros Communications | 3         | 4.17%   |
| IMC Networks                    | 3         | 4.17%   |
| Realtek                         | 2         | 2.78%   |
| Foxconn / Hon Hai               | 2         | 2.78%   |
| Dell                            | 1         | 1.39%   |
| Apple                           | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.28%  |
| Intel AX200 Bluetooth                               | 10        | 13.89%  |
| Realtek Bluetooth Radio                             | 7         | 9.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 9.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.17%   |
| Intel AX201 Bluetooth                               | 3         | 4.17%   |
| Realtek Bluetooth Radio                             | 2         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.78%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.39%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.39%   |
| Intel AX210 Bluetooth                               | 1         | 1.39%   |
| IMC Networks Bluetooth Device                       | 1         | 1.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.39%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.39%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.39%   |
| Broadcom HP Portable Valentine                      | 1         | 1.39%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.39%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.39%   |
| Apple Bluetooth Host Controller                     | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 39.52%  |
| AMD                              | 47        | 28.14%  |
| Nvidia                           | 28        | 16.77%  |
| C-Media Electronics              | 5         | 2.99%   |
| Logitech                         | 4         | 2.4%    |
| JMTek                            | 4         | 2.4%    |
| Texas Instruments                | 2         | 1.2%    |
| Creative Technology              | 2         | 1.2%    |
| VIA Technologies                 | 1         | 0.6%    |
| Unknown                          | 1         | 0.6%    |
| SteelSeries ApS                  | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| SAVITECH                         | 1         | 0.6%    |
| Focusrite-Novation               | 1         | 0.6%    |
| Elgato Systems                   | 1         | 0.6%    |
| Corsair                          | 1         | 0.6%    |
| Cambridge Audio                  | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 6.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 4.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 3.83%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 3.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.91%   |
| AMD High Definition Audio Controller                                       | 4         | 1.91%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.44%   |
| JMTek USB PnP Audio Device                                                 | 3         | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.44%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.96%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.96%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.96%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.96%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1         | 0.48%   |
| Unknown USB Audio                                                          | 1         | 0.48%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 22        | 23.4%   |
| Samsung Electronics | 21        | 22.34%  |
| Kingston            | 11        | 11.7%   |
| Micron Technology   | 8         | 8.51%   |
| Unknown             | 7         | 7.45%   |
| G.Skill             | 6         | 6.38%   |
| Corsair             | 5         | 5.32%   |
| A-DATA Technology   | 5         | 5.32%   |
| Crucial             | 3         | 3.19%   |
| Transcend           | 1         | 1.06%   |
| Ramaxel Technology  | 1         | 1.06%   |
| Patriot             | 1         | 1.06%   |
| Elpida              | 1         | 1.06%   |
| Avant               | 1         | 1.06%   |
| 48spaces            | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.9%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.9%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.9%    |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.95%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.95%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.95%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.95%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.95%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.95%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.95%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.95%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.95%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.95%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.95%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 41        | 48.24%  |
| DDR3    | 33        | 38.82%  |
| LPDDR4  | 3         | 3.53%   |
| LPDDR3  | 3         | 3.53%   |
| DDR2    | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| DDR5    | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 59.52%  |
| DIMM         | 30        | 35.71%  |
| Row Of Chips | 4         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 41        | 44.57%  |
| 4096  | 30        | 32.61%  |
| 16384 | 10        | 10.87%  |
| 2048  | 7         | 7.61%   |
| 1024  | 3         | 3.26%   |
| 512   | 1         | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 25%     |
| 2667    | 14        | 15.22%  |
| 3200    | 11        | 11.96%  |
| 2400    | 9         | 9.78%   |
| 1333    | 8         | 8.7%    |
| 3600    | 4         | 4.35%   |
| 2133    | 4         | 4.35%   |
| 1334    | 3         | 3.26%   |
| 3000    | 2         | 2.17%   |
| 1867    | 2         | 2.17%   |
| 4800    | 1         | 1.09%   |
| 4266    | 1         | 1.09%   |
| 3866    | 1         | 1.09%   |
| 3733    | 1         | 1.09%   |
| 3333    | 1         | 1.09%   |
| 2933    | 1         | 1.09%   |
| 2800    | 1         | 1.09%   |
| 2666    | 1         | 1.09%   |
| 1067    | 1         | 1.09%   |
| 667     | 1         | 1.09%   |
| 533     | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

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
| Chicony Electronics                    | 23        | 28.4%   |
| IMC Networks                           | 13        | 16.05%  |
| Microdia                               | 9         | 11.11%  |
| Realtek Semiconductor                  | 7         | 8.64%   |
| Logitech                               | 7         | 8.64%   |
| Quanta                                 | 5         | 6.17%   |
| Acer                                   | 5         | 6.17%   |
| Sunplus Innovation Technology          | 3         | 3.7%    |
| Suyin                                  | 2         | 2.47%   |
| MacroSilicon                           | 2         | 2.47%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.47%   |
| Silicon Motion                         | 1         | 1.23%   |
| Microsoft                              | 1         | 1.23%   |
| GEMBIRD                                | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 6         | 7.23%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 4.82%   |
| Quanta HD User Facing                         | 3         | 3.61%   |
| Logitech Webcam C270                          | 3         | 3.61%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 3.61%   |
| Suyin HP TrueVision HD                        | 2         | 2.41%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.41%   |
| Realtek USB Camera                            | 2         | 2.41%   |
| Microdia HP Integrated Webcam                 | 2         | 2.41%   |
| IMC Networks HD Camera                        | 2         | 2.41%   |
| Chicony USB 2.0 Camera                        | 2         | 2.41%   |
| Chicony HP TrueVision HD Camera               | 2         | 2.41%   |
| Chicony HD WebCam                             | 2         | 2.41%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.2%    |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.2%    |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.2%    |
| Realtek Streaming Webcam                      | 1         | 1.2%    |
| Realtek Laptop Camera                         | 1         | 1.2%    |
| Realtek Integrated Webcam HD                  | 1         | 1.2%    |
| Realtek HD WebCam                             | 1         | 1.2%    |
| Quanta VGA WebCam                             | 1         | 1.2%    |
| Quanta HP TrueVision HD Camera                | 1         | 1.2%    |
| Microsoft LifeCam HD-3000                     | 1         | 1.2%    |
| Microdia Webcam Vitade AF                     | 1         | 1.2%    |
| Microdia Webcam                               | 1         | 1.2%    |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.2%    |
| Microdia Integrated_Webcam_HD                 | 1         | 1.2%    |
| Microdia Integrated_Webcam_2M                 | 1         | 1.2%    |
| Microdia CameraA                              | 1         | 1.2%    |
| Microdia Camera                               | 1         | 1.2%    |
| MacroSilicon USB Video                        | 1         | 1.2%    |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1         | 1.2%    |
| Logitech Webcam C930e                         | 1         | 1.2%    |
| Logitech HD Webcam C615                       | 1         | 1.2%    |
| Logitech C922 Pro Stream Webcam               | 1         | 1.2%    |
| Logitech C505 HD Webcam                       | 1         | 1.2%    |
| IMC Networks VGA UVC WebCam                   | 1         | 1.2%    |
| IMC Networks Integrated Camera                | 1         | 1.2%    |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.2%    |
| IMC Networks EasyCamera                       | 1         | 1.2%    |

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
| 0     | 98        | 80.33%  |
| 1     | 16        | 13.11%  |
| 2     | 6         | 4.92%   |
| 3     | 2         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 27.27%  |
| Net/wireless          | 5         | 15.15%  |
| Graphics card         | 5         | 15.15%  |
| Chipcard              | 4         | 12.12%  |
| Camera                | 4         | 12.12%  |
| Sound                 | 3         | 9.09%   |
| Multimedia controller | 2         | 6.06%   |
| Net/ethernet          | 1         | 3.03%   |

