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

Total: 169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | Notebook    | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
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
| Void Linux Rolling | 79        | 60.31%  |
| Void Linux         | 52        | 39.69%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 128       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 7         | 5.11%   |
| 5.8.18_1    | 5         | 3.65%   |
| 5.3.9_1     | 4         | 2.92%   |
| 5.16.20_1   | 4         | 2.92%   |
| 5.10.17_1   | 4         | 2.92%   |
| 5.8.12_1    | 3         | 2.19%   |
| 5.19.17_1   | 3         | 2.19%   |
| 5.18.19_1   | 3         | 2.19%   |
| 5.18.14_1   | 3         | 2.19%   |
| 5.15.32_1   | 3         | 2.19%   |
| 5.13.13_1   | 3         | 2.19%   |
| 5.12.10_1   | 3         | 2.19%   |
| 5.9.14_1    | 2         | 1.46%   |
| 5.4.24_1    | 2         | 1.46%   |
| 5.4.13_2    | 2         | 1.46%   |
| 5.19.16_1   | 2         | 1.46%   |
| 5.18.9_1    | 2         | 1.46%   |
| 5.15.41_1   | 2         | 1.46%   |
| 5.15.34_1   | 2         | 1.46%   |
| 5.15.22_1   | 2         | 1.46%   |
| 5.15.16_1   | 2         | 1.46%   |
| 5.13.15_1   | 2         | 1.46%   |
| 5.13.10_1   | 2         | 1.46%   |
| 5.12.14_1   | 2         | 1.46%   |
| 5.11.9_1    | 2         | 1.46%   |
| 5.10.14_1   | 2         | 1.46%   |
| 6.0.9_1     | 1         | 0.73%   |
| 5.9.16_1    | 1         | 0.73%   |
| 5.9.0-rc8_2 | 1         | 0.73%   |
| 5.8.9_1     | 1         | 0.73%   |
| 5.8.8_1     | 1         | 0.73%   |
| 5.8.7_1     | 1         | 0.73%   |
| 5.8.6_1     | 1         | 0.73%   |
| 5.8.5_1     | 1         | 0.73%   |
| 5.8.16_1    | 1         | 0.73%   |
| 5.8.14_1    | 1         | 0.73%   |
| 5.8.12_2    | 1         | 0.73%   |
| 5.8.11_1    | 1         | 0.73%   |
| 5.8.10_1    | 1         | 0.73%   |
| 5.7.16_1    | 1         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 5.11%   |
| 5.8.18  | 5         | 3.65%   |
| 5.8.12  | 4         | 2.92%   |
| 5.3.9   | 4         | 2.92%   |
| 5.16.20 | 4         | 2.92%   |
| 5.10.17 | 4         | 2.92%   |
| 5.19.17 | 3         | 2.19%   |
| 5.18.19 | 3         | 2.19%   |
| 5.18.14 | 3         | 2.19%   |
| 5.15.32 | 3         | 2.19%   |
| 5.13.13 | 3         | 2.19%   |
| 5.12.10 | 3         | 2.19%   |
| 5.9.14  | 2         | 1.46%   |
| 5.4.24  | 2         | 1.46%   |
| 5.4.13  | 2         | 1.46%   |
| 5.19.16 | 2         | 1.46%   |
| 5.18.9  | 2         | 1.46%   |
| 5.15.41 | 2         | 1.46%   |
| 5.15.34 | 2         | 1.46%   |
| 5.15.22 | 2         | 1.46%   |
| 5.15.16 | 2         | 1.46%   |
| 5.13.15 | 2         | 1.46%   |
| 5.13.10 | 2         | 1.46%   |
| 5.12.14 | 2         | 1.46%   |
| 5.11.9  | 2         | 1.46%   |
| 5.10.14 | 2         | 1.46%   |
| 6.0.9   | 1         | 0.73%   |
| 5.9.16  | 1         | 0.73%   |
| 5.9.0   | 1         | 0.73%   |
| 5.8.9   | 1         | 0.73%   |
| 5.8.8   | 1         | 0.73%   |
| 5.8.7   | 1         | 0.73%   |
| 5.8.6   | 1         | 0.73%   |
| 5.8.5   | 1         | 0.73%   |
| 5.8.16  | 1         | 0.73%   |
| 5.8.14  | 1         | 0.73%   |
| 5.8.11  | 1         | 0.73%   |
| 5.8.10  | 1         | 0.73%   |
| 5.7.16  | 1         | 0.73%   |
| 5.6.14  | 1         | 0.73%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 17.65%  |
| 5.8     | 18        | 13.24%  |
| 5.13    | 16        | 11.76%  |
| 5.10    | 15        | 11.03%  |
| 5.18    | 11        | 8.09%   |
| 5.12    | 9         | 6.62%   |
| 5.4     | 7         | 5.15%   |
| 5.3     | 5         | 3.68%   |
| 5.19    | 5         | 3.68%   |
| 5.11    | 5         | 3.68%   |
| 5.9     | 4         | 2.94%   |
| 5.16    | 4         | 2.94%   |
| 4.19    | 4         | 2.94%   |
| 6.0     | 1         | 0.74%   |
| 5.7     | 1         | 0.74%   |
| 5.6     | 1         | 0.74%   |
| 5.2     | 1         | 0.74%   |
| 5.17    | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |
| 5.1     | 1         | 0.74%   |
| 4.4     | 1         | 0.74%   |
| 4.14    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 117       | 91.41%  |
| i686    | 5         | 3.91%   |
| aarch64 | 3         | 2.34%   |
| ppc64le | 1         | 0.78%   |
| ppc64   | 1         | 0.78%   |
| armv7l  | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 50.38%  |
| XFCE       | 15        | 11.28%  |
| KDE        | 10        | 7.52%   |
| MATE       | 7         | 5.26%   |
| KDE5       | 7         | 5.26%   |
| GNOME      | 6         | 4.51%   |
| i3         | 5         | 3.76%   |
| X-Cinnamon | 3         | 2.26%   |
| openbox    | 3         | 2.26%   |
| bspwm      | 3         | 2.26%   |
| awesome    | 3         | 2.26%   |
| Lumina     | 2         | 1.5%    |
| sway       | 1         | 0.75%   |
| river      | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 90        | 69.23%  |
| Tty     | 16        | 12.31%  |
| Wayland | 12        | 9.23%   |
| Unknown | 12        | 9.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 113       | 86.92%  |
| SDDM    | 5         | 3.85%   |
| LXDM    | 5         | 3.85%   |
| LightDM | 5         | 3.85%   |
| LDM     | 1         | 0.77%   |
| GDM     | 1         | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 67        | 50.38%  |
| Unknown | 20        | 15.04%  |
| en_GB   | 7         | 5.26%   |
| en_DK   | 6         | 4.51%   |
| ru_RU   | 5         | 3.76%   |
| it_IT   | 3         | 2.26%   |
| fr_FR   | 3         | 2.26%   |
| de_DE   | 3         | 2.26%   |
| pt_BR   | 2         | 1.5%    |
| pl_PL   | 2         | 1.5%    |
| en_AU   | 2         | 1.5%    |
| cs_CZ   | 2         | 1.5%    |
| tr_TR   | 1         | 0.75%   |
| ru_UA   | 1         | 0.75%   |
| nb_NO   | 1         | 0.75%   |
| es_HN   | 1         | 0.75%   |
| es_ES   | 1         | 0.75%   |
| es_DO   | 1         | 0.75%   |
| en_NZ   | 1         | 0.75%   |
| en_IE   | 1         | 0.75%   |
| en_CA   | 1         | 0.75%   |
| el_GR   | 1         | 0.75%   |
| bg_BG   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 68        | 51.91%  |
| BIOS | 63        | 48.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 63.08%  |
| Btrfs   | 27        | 20.77%  |
| Xfs     | 8         | 6.15%   |
| Zfs     | 6         | 4.62%   |
| Unknown | 5         | 3.85%   |
| F2fs    | 1         | 0.77%   |
| Ext3    | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 73        | 55.73%  |
| Unknown | 38        | 29.01%  |
| MBR     | 20        | 15.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 86.72%  |
| Yes       | 17        | 13.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 79.84%  |
| Yes       | 26        | 20.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 28        | 21.88%  |
| Lenovo                  | 20        | 15.63%  |
| Hewlett-Packard         | 13        | 10.16%  |
| Dell                    | 13        | 10.16%  |
| Acer                    | 12        | 9.38%   |
| MSI                     | 9         | 7.03%   |
| ASRock                  | 8         | 6.25%   |
| Unknown                 | 5         | 3.91%   |
| Gigabyte Technology     | 4         | 3.13%   |
| HUAWEI                  | 2         | 1.56%   |
| Samsung Electronics     | 1         | 0.78%   |
| Raspberry Pi Foundation | 1         | 0.78%   |
| Positivo                | 1         | 0.78%   |
| Pine Microsystems       | 1         | 0.78%   |
| Notebook                | 1         | 0.78%   |
| Nokia                   | 1         | 0.78%   |
| Microsoft               | 1         | 0.78%   |
| Getac                   | 1         | 0.78%   |
| Framework               | 1         | 0.78%   |
| Exo                     | 1         | 0.78%   |
| Digibras                | 1         | 0.78%   |
| Cisco Systems           | 1         | 0.78%   |
| Chuwi                   | 1         | 0.78%   |
| Apple                   | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 5         | 3.91%   |
| HP Laptop 15-bw0xx                     | 2         | 1.56%   |
| Dell OptiPlex 7010                     | 2         | 1.56%   |
| ASUS PRIME Z390-P                      | 2         | 1.56%   |
| Acer Swift SF314-42                    | 2         | 1.56%   |
| Samsung 275E4E/275E5E                  | 1         | 0.78%   |
| RPi Raspberry Pi                       | 1         | 0.78%   |
| Positivo Mobile                        | 1         | 0.78%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.78%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.78%   |
| Nokia Booklet 3G                       | 1         | 0.78%   |
| MSI MS-7D14                            | 1         | 0.78%   |
| MSI MS-7C92                            | 1         | 0.78%   |
| MSI MS-7C52                            | 1         | 0.78%   |
| MSI MS-7C02                            | 1         | 0.78%   |
| MSI MS-7A68                            | 1         | 0.78%   |
| MSI MS-7A39                            | 1         | 0.78%   |
| MSI MS-7816                            | 1         | 0.78%   |
| MSI GV72 7RE                           | 1         | 0.78%   |
| MSI Bravo 15 A4DDR                     | 1         | 0.78%   |
| Microsoft Surface with Windows RT      | 1         | 0.78%   |
| Lenovo Yoga 720-15IKB 80X7             | 1         | 0.78%   |
| Lenovo Y520-15IKB 80YY                 | 1         | 0.78%   |
| Lenovo ThinkPad X260 20F5S08Q00        | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMA34HMN        | 1         | 0.78%   |
| Lenovo ThinkPad X201 3680BR4           | 1         | 0.78%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS | 1         | 0.78%   |
| Lenovo ThinkPad T490 20N20046US        | 1         | 0.78%   |
| Lenovo ThinkPad T480 20L6SA5Q00        | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS0WN00        | 1         | 0.78%   |
| Lenovo ThinkPad T430 2349PS3           | 1         | 0.78%   |
| Lenovo ThinkPad T420 4236PG6           | 1         | 0.78%   |
| Lenovo ThinkPad T420 4180A21           | 1         | 0.78%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW  | 1         | 0.78%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00  | 1         | 0.78%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200   | 1         | 0.78%   |
| Lenovo ThinkPad E595 20NFCTO1WW        | 1         | 0.78%   |
| Lenovo IdeaPad Z570 10246ZG            | 1         | 0.78%   |
| Lenovo IdeaPad S145-14IIL 81W6         | 1         | 0.78%   |
| Lenovo IdeaPad 710S-13IKB 80VQ         | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 14        | 10.94%  |
| Acer Aspire              | 7         | 5.47%   |
| ASUS PRIME               | 6         | 4.69%   |
| HP Laptop                | 5         | 3.91%   |
| Unknown                  | 5         | 3.91%   |
| Dell OptiPlex            | 4         | 3.13%   |
| Dell Inspiron            | 4         | 3.13%   |
| ASUS VivoBook            | 4         | 3.13%   |
| Lenovo IdeaPad           | 3         | 2.34%   |
| HP Pavilion              | 2         | 1.56%   |
| Dell Latitude            | 2         | 1.56%   |
| ASUS TUF                 | 2         | 1.56%   |
| ASUS ROG                 | 2         | 1.56%   |
| Acer Swift               | 2         | 1.56%   |
| Samsung 275E4E           | 1         | 0.78%   |
| RPi Raspberry            | 1         | 0.78%   |
| Positivo Mobile          | 1         | 0.78%   |
| Pine Microsystems Pine64 | 1         | 0.78%   |
| Notebook NV4XMB          | 1         | 0.78%   |
| Nokia Booklet            | 1         | 0.78%   |
| MSI MS-7D14              | 1         | 0.78%   |
| MSI MS-7C92              | 1         | 0.78%   |
| MSI MS-7C52              | 1         | 0.78%   |
| MSI MS-7C02              | 1         | 0.78%   |
| MSI MS-7A68              | 1         | 0.78%   |
| MSI MS-7A39              | 1         | 0.78%   |
| MSI MS-7816              | 1         | 0.78%   |
| MSI GV72                 | 1         | 0.78%   |
| MSI Bravo                | 1         | 0.78%   |
| Microsoft Surface        | 1         | 0.78%   |
| Lenovo Yoga              | 1         | 0.78%   |
| Lenovo Y520-15IKB        | 1         | 0.78%   |
| Lenovo G50-45            | 1         | 0.78%   |
| HUAWEI KLVL-WXXW         | 1         | 0.78%   |
| HUAWEI HN-WX9X           | 1         | 0.78%   |
| HP Z2                    | 1         | 0.78%   |
| HP Stream                | 1         | 0.78%   |
| HP Notebook              | 1         | 0.78%   |
| HP ENVY                  | 1         | 0.78%   |
| HP Compaq                | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 19        | 14.84%  |
| 2020    | 16        | 12.5%   |
| 2018    | 16        | 12.5%   |
| 2017    | 11        | 8.59%   |
| 2016    | 9         | 7.03%   |
| 2013    | 9         | 7.03%   |
| 2014    | 8         | 6.25%   |
| 2012    | 8         | 6.25%   |
| 2011    | 6         | 4.69%   |
| 2015    | 5         | 3.91%   |
| 2010    | 5         | 3.91%   |
| Unknown | 5         | 3.91%   |
| 2021    | 4         | 3.13%   |
| 2009    | 2         | 1.56%   |
| 2008    | 2         | 1.56%   |
| 2022    | 1         | 0.78%   |
| 2006    | 1         | 0.78%   |
| 2005    | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 77        | 60.16%  |
| Desktop        | 43        | 33.59%  |
| Convertible    | 3         | 2.34%   |
| Tablet         | 2         | 1.56%   |
| System on chip | 1         | 0.78%   |
| Mini pc        | 1         | 0.78%   |
| Server         | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 128       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 29        | 22.31%  |
| 16.01-24.0      | 28        | 21.54%  |
| 8.01-16.0       | 25        | 19.23%  |
| 3.01-4.0        | 21        | 16.15%  |
| 32.01-64.0      | 12        | 9.23%   |
| 1.01-2.0        | 6         | 4.62%   |
| 0.51-1.0        | 4         | 3.08%   |
| 64.01-256.0     | 2         | 1.54%   |
| More than 256.0 | 1         | 0.77%   |
| 24.01-32.0      | 1         | 0.77%   |
| 2.01-3.0        | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 37        | 27.01%  |
| 2.01-3.0    | 32        | 23.36%  |
| 0.51-1.0    | 22        | 16.06%  |
| 4.01-8.0    | 15        | 10.95%  |
| 3.01-4.0    | 14        | 10.22%  |
| 8.01-16.0   | 7         | 5.11%   |
| 0.01-0.5    | 6         | 4.38%   |
| 16.01-24.0  | 3         | 2.19%   |
| 64.01-256.0 | 1         | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 59.69%  |
| 2      | 30        | 23.26%  |
| 3      | 16        | 12.4%   |
| 5      | 2         | 1.55%   |
| 4      | 2         | 1.55%   |
| 9      | 1         | 0.78%   |
| 0      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 78.13%  |
| Yes       | 28        | 21.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 82.81%  |
| No        | 22        | 17.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 70.31%  |
| No        | 38        | 29.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 58.14%  |
| No        | 54        | 41.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 25        | 19.53%  |
| Russia             | 12        | 9.38%   |
| Germany            | 10        | 7.81%   |
| India              | 9         | 7.03%   |
| Brazil             | 7         | 5.47%   |
| Czechia            | 6         | 4.69%   |
| Denmark            | 5         | 3.91%   |
| Ukraine            | 4         | 3.13%   |
| UK                 | 4         | 3.13%   |
| Poland             | 4         | 3.13%   |
| France             | 4         | 3.13%   |
| Turkey             | 3         | 2.34%   |
| Switzerland        | 3         | 2.34%   |
| Netherlands        | 3         | 2.34%   |
| Bulgaria           | 3         | 2.34%   |
| Spain              | 2         | 1.56%   |
| Morocco            | 2         | 1.56%   |
| Italy              | 2         | 1.56%   |
| Greece             | 2         | 1.56%   |
| Australia          | 2         | 1.56%   |
| Argentina          | 2         | 1.56%   |
| Vietnam            | 1         | 0.78%   |
| Sweden             | 1         | 0.78%   |
| Peru               | 1         | 0.78%   |
| Norway             | 1         | 0.78%   |
| New Zealand        | 1         | 0.78%   |
| Mexico             | 1         | 0.78%   |
| Latvia             | 1         | 0.78%   |
| Indonesia          | 1         | 0.78%   |
| Honduras           | 1         | 0.78%   |
| Ecuador            | 1         | 0.78%   |
| Dominican Republic | 1         | 0.78%   |
| Canada             | 1         | 0.78%   |
| Belgium            | 1         | 0.78%   |
| Bangladesh         | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 5         | 3.82%   |
| Moscow             | 3         | 2.29%   |
| Denver             | 3         | 2.29%   |
| Amsterdam          | 3         | 2.29%   |
| St Petersburg      | 2         | 1.53%   |
| Sofia              | 2         | 1.53%   |
| Rome               | 2         | 1.53%   |
| Orlando            | 2         | 1.53%   |
| Munich             | 2         | 1.53%   |
| Meknes             | 2         | 1.53%   |
| Lublin             | 2         | 1.53%   |
| Hyderabad          | 2         | 1.53%   |
| Geneva             | 2         | 1.53%   |
| Zagnansk           | 1         | 0.76%   |
| Yekaterinburg      | 1         | 0.76%   |
| Yambol             | 1         | 0.76%   |
| Weatherford        | 1         | 0.76%   |
| Volgograd          | 1         | 0.76%   |
| Vlaardingen        | 1         | 0.76%   |
| Viby J             | 1         | 0.76%   |
| Varna              | 1         | 0.76%   |
| Trujillo           | 1         | 0.76%   |
| Toulouse           | 1         | 0.76%   |
| Toms River         | 1         | 0.76%   |
| Tegucigalpa        | 1         | 0.76%   |
| Syktyvkar          | 1         | 0.76%   |
| Surabaya           | 1         | 0.76%   |
| Stratford          | 1         | 0.76%   |
| South Shields      | 1         | 0.76%   |
| Solone             | 1         | 0.76%   |
| Sistranda          | 1         | 0.76%   |
| Saxtons River      | 1         | 0.76%   |
| Sao Paulo          | 1         | 0.76%   |
| Santo Domingo      | 1         | 0.76%   |
| Saint-Paul-les-Dax | 1         | 0.76%   |
| Saint Paul         | 1         | 0.76%   |
| Rostock            | 1         | 0.76%   |
| Rosenheim          | 1         | 0.76%   |
| Rosario            | 1         | 0.76%   |
| Rio de Janeiro     | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 54     | 21.39%  |
| WDC                 | 32        | 39     | 17.11%  |
| Seagate             | 31        | 36     | 16.58%  |
| Kingston            | 12        | 12     | 6.42%   |
| Unknown             | 9         | 14     | 4.81%   |
| Toshiba             | 9         | 10     | 4.81%   |
| SanDisk             | 8         | 9      | 4.28%   |
| Intel               | 7         | 9      | 3.74%   |
| HGST                | 7         | 8      | 3.74%   |
| Crucial             | 5         | 6      | 2.67%   |
| Hitachi             | 4         | 4      | 2.14%   |
| SK hynix            | 2         | 2      | 1.07%   |
| Phison              | 2         | 2      | 1.07%   |
| Patriot             | 2         | 2      | 1.07%   |
| Corsair             | 2         | 2      | 1.07%   |
| A-DATA Technology   | 2         | 3      | 1.07%   |
| XPG                 | 1         | 4      | 0.53%   |
| Transcend           | 1         | 1      | 0.53%   |
| SPCC                | 1         | 1      | 0.53%   |
| Phison Electronics  | 1         | 1      | 0.53%   |
| OCZ                 | 1         | 1      | 0.53%   |
| Maxtor              | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| Lenovo              | 1         | 1      | 0.53%   |
| KIOXIA              | 1         | 1      | 0.53%   |
| Gigabyte Technology | 1         | 2      | 0.53%   |
| China               | 1         | 1      | 0.53%   |
| BHT                 | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 5         | 2.43%   |
| Unknown MMC Card  32GB                  | 4         | 1.94%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.94%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 1.46%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 1.46%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 1.46%   |
| Samsung SSD 870 EVO 500GB               | 3         | 1.46%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 1.46%   |
| Kingston SHFS37A120G 120GB SSD          | 3         | 1.46%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.97%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 0.97%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 0.97%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 0.97%   |
| Samsung SSD 980 PRO 500GB               | 2         | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.97%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.97%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.97%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 0.97%   |
| Patriot Burst 120GB SSD                 | 2         | 0.97%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 0.97%   |
| HGST HTS545050A7E680 500GB              | 2         | 0.97%   |
| HGST HTS541010B7E610 1TB                | 2         | 0.97%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.97%   |
| XPG NVMe SSD Drive 2TB                  | 1         | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.49%   |
| WDC WD7500AYYS-01RCA0 752GB             | 1         | 0.49%   |
| WDC WD60 EFRX-68L0BN1 6TB               | 1         | 0.49%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 0.49%   |
| WDC WD5000AADS-00S9B0 500GB             | 1         | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.49%   |
| WDC WD3200AAKS-22SBA0 320GB             | 1         | 0.49%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.49%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 0.49%   |
| WDC WD20EZBX-00AYRA0 2TB                | 1         | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB                | 1         | 0.49%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 36     | 37.35%  |
| WDC                 | 27        | 33     | 32.53%  |
| Toshiba             | 8         | 9      | 9.64%   |
| HGST                | 7         | 8      | 8.43%   |
| Samsung Electronics | 5         | 5      | 6.02%   |
| Hitachi             | 4         | 4      | 4.82%   |
| Maxtor              | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 32.08%  |
| Kingston            | 11        | 11     | 20.75%  |
| SanDisk             | 5         | 5      | 9.43%   |
| Crucial             | 3         | 4      | 5.66%   |
| WDC                 | 2         | 2      | 3.77%   |
| Patriot             | 2         | 2      | 3.77%   |
| Intel               | 2         | 2      | 3.77%   |
| Transcend           | 1         | 1      | 1.89%   |
| SPCC                | 1         | 1      | 1.89%   |
| OCZ                 | 1         | 1      | 1.89%   |
| LITEONIT            | 1         | 1      | 1.89%   |
| Lenovo              | 1         | 1      | 1.89%   |
| Gigabyte Technology | 1         | 2      | 1.89%   |
| Corsair             | 1         | 1      | 1.89%   |
| China               | 1         | 1      | 1.89%   |
| BHT                 | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |
| A-DATA Technology   | 1         | 2      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 69        | 96     | 41.07%  |
| SSD     | 48        | 59     | 28.57%  |
| NVMe    | 41        | 59     | 24.4%   |
| MMC     | 8         | 12     | 4.76%   |
| Unknown | 2         | 3      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 153    | 64.19%  |
| NVMe | 41        | 59     | 27.7%   |
| MMC  | 8         | 12     | 5.41%   |
| SAS  | 4         | 5      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 84     | 52.8%   |
| 0.51-1.0   | 42        | 49     | 33.6%   |
| 1.01-2.0   | 13        | 17     | 10.4%   |
| 4.01-10.0  | 3         | 3      | 2.4%    |
| 3.01-4.0   | 1         | 2      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 24.43%  |
| 501-1000       | 26        | 19.85%  |
| 101-250        | 25        | 19.08%  |
| Unknown        | 12        | 9.16%   |
| 1001-2000      | 11        | 8.4%    |
| 1-20           | 7         | 5.34%   |
| More than 3000 | 6         | 4.58%   |
| 2001-3000      | 5         | 3.82%   |
| 21-50          | 4         | 3.05%   |
| 51-100         | 3         | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 25.19%  |
| 101-250        | 31        | 22.96%  |
| 21-50          | 17        | 12.59%  |
| 51-100         | 14        | 10.37%  |
| 251-500        | 13        | 9.63%   |
| Unknown        | 12        | 8.89%   |
| 1001-2000      | 7         | 5.19%   |
| 501-1000       | 4         | 2.96%   |
| More than 3000 | 2         | 1.48%   |
| 2001-3000      | 1         | 0.74%   |

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
| Works    | 78        | 119    | 52%     |
| Detected | 48        | 81     | 32%     |
| Malfunc  | 24        | 29     | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 69        | 44.52%  |
| AMD                              | 38        | 24.52%  |
| Samsung Electronics              | 23        | 14.84%  |
| SanDisk                          | 5         | 3.23%   |
| Phison Electronics               | 4         | 2.58%   |
| SK hynix                         | 2         | 1.29%   |
| Micron/Crucial Technology        | 2         | 1.29%   |
| ADATA Technology                 | 2         | 1.29%   |
| Toshiba America Info Systems     | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| Marvell Technology Group         | 1         | 0.65%   |
| LSI Logic / Symbios Logic        | 1         | 0.65%   |
| KIOXIA                           | 1         | 0.65%   |
| Kingston Technology Company      | 1         | 0.65%   |
| JMicron Technology               | 1         | 0.65%   |
| Broadcom                         | 1         | 0.65%   |
| ASMedia Technology               | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 27        | 15.52%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 13        | 7.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 10        | 5.75%   |
| AMD 400 Series Chipset SATA Controller                                        | 8         | 4.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 7         | 4.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 5         | 2.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 4         | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 4         | 2.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                | 3         | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 1.72%   |
| Intel SSD 660P Series                                                         | 3         | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 3         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3         | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 1.72%   |
| SK hynix Non-Volatile memory controller                                       | 2         | 1.15%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 1.15%   |
| Phison E12 NVMe Controller                                                    | 2         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 2         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2         | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                        | 2         | 1.15%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 2         | 1.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                   | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 1         | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 0.57%   |
| Samsung Apple PCIe SSD                                                        | 1         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.57%   |
| Nvidia MCP61 SATA Controller                                                  | 1         | 0.57%   |
| Nvidia MCP61 IDE                                                              | 1         | 0.57%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 94        | 59.87%  |
| NVMe | 42        | 26.75%  |
| IDE  | 13        | 8.28%   |
| RAID | 8         | 5.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 78        | 60.94%  |
| AMD                      | 44        | 34.38%  |
| ARM                      | 4         | 3.13%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.78%   |
| PowerMac11,2             | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 3.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 2.34%   |
| ARM Processor                                      | 3         | 2.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.56%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 1.56%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 2         | 1.56%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.56%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 2         | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.56%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.56%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.56%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.78%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.78%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.78%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.78%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.78%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.78%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.78%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.78%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 1         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz                  | 1         | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz                  | 1         | 0.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz                   | 1         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz                  | 1         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz                  | 1         | 0.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                 | 1         | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz                 | 1         | 0.78%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 1         | 0.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 1         | 0.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz                  | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 19.53%  |
| Intel Core i7           | 18        | 14.06%  |
| AMD Ryzen 5             | 15        | 11.72%  |
| Other                   | 13        | 10.16%  |
| Intel Core i3           | 12        | 9.38%   |
| AMD Ryzen 7             | 9         | 7.03%   |
| Intel Atom              | 6         | 4.69%   |
| Intel Celeron           | 4         | 3.13%   |
| Intel Pentium           | 2         | 1.56%   |
| Intel Core 2 Duo        | 2         | 1.56%   |
| AMD Ryzen 7 PRO         | 2         | 1.56%   |
| AMD Ryzen 3             | 2         | 1.56%   |
| AMD FX                  | 2         | 1.56%   |
| AMD A8                  | 2         | 1.56%   |
| Intel Xeon              | 1         | 0.78%   |
| Intel Pentium Gold      | 1         | 0.78%   |
| Intel Pentium 4         | 1         | 0.78%   |
| Intel Genuine           | 1         | 0.78%   |
| Intel Core i9           | 1         | 0.78%   |
| AMD Turion 64 X2 Mobile | 1         | 0.78%   |
| AMD Ryzen Threadripper  | 1         | 0.78%   |
| AMD Phenom II X4        | 1         | 0.78%   |
| AMD E2                  | 1         | 0.78%   |
| AMD E1                  | 1         | 0.78%   |
| AMD C-60                | 1         | 0.78%   |
| AMD Athlon II X3        | 1         | 0.78%   |
| AMD Athlon II X2        | 1         | 0.78%   |
| AMD A4                  | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 45        | 35.16%  |
| 2       | 45        | 35.16%  |
| 6       | 17        | 13.28%  |
| 8       | 12        | 9.38%   |
| 1       | 5         | 3.91%   |
| 64      | 1         | 0.78%   |
| 12      | 1         | 0.78%   |
| 3       | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 125       | 97.66%  |
| 2       | 2         | 1.56%   |
| Unknown | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 84        | 65.63%  |
| 1       | 42        | 32.81%  |
| 4       | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 114       | 89.06%  |
| Unknown        | 8         | 6.25%   |
| 64-bit         | 3         | 2.34%   |
| 32-bit         | 3         | 2.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 30.53%  |
| 0x306a9    | 7         | 5.34%   |
| 0x40651    | 6         | 4.58%   |
| 0x906e9    | 5         | 3.82%   |
| 0x906ea    | 4         | 3.05%   |
| 0x806ec    | 3         | 2.29%   |
| 0x806ea    | 3         | 2.29%   |
| 0x806e9    | 3         | 2.29%   |
| 0x406e3    | 3         | 2.29%   |
| 0x206a7    | 3         | 2.29%   |
| 0x08600104 | 3         | 2.29%   |
| 0x08108102 | 3         | 2.29%   |
| 0x30678    | 2         | 1.53%   |
| 0x106c2    | 2         | 1.53%   |
| 0x0a201009 | 2         | 1.53%   |
| 0x08701021 | 2         | 1.53%   |
| 0x0800820d | 2         | 1.53%   |
| 0x07030105 | 2         | 1.53%   |
| 0x06006705 | 2         | 1.53%   |
| 0x06000852 | 2         | 1.53%   |
| 0x05000119 | 2         | 1.53%   |
| 0x010000c8 | 2         | 1.53%   |
| 0xa0671    | 1         | 0.76%   |
| 0xa0652    | 1         | 0.76%   |
| 0x906ed    | 1         | 0.76%   |
| 0x90672    | 1         | 0.76%   |
| 0x806eb    | 1         | 0.76%   |
| 0x706e5    | 1         | 0.76%   |
| 0x706a1    | 1         | 0.76%   |
| 0x506e3    | 1         | 0.76%   |
| 0x406c4    | 1         | 0.76%   |
| 0x306d4    | 1         | 0.76%   |
| 0x306c3    | 1         | 0.76%   |
| 0x20652    | 1         | 0.76%   |
| 0x106ca    | 1         | 0.76%   |
| 0x106a5    | 1         | 0.76%   |
| 0x1067a    | 1         | 0.76%   |
| 0x0a50000c | 1         | 0.76%   |
| 0x0a201205 | 1         | 0.76%   |
| 0x08701013 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 26        | 20.31%  |
| Zen 2            | 10        | 7.81%   |
| IvyBridge        | 10        | 7.81%   |
| Haswell          | 9         | 7.03%   |
| Unknown          | 8         | 6.25%   |
| Zen+             | 7         | 5.47%   |
| Zen 3            | 6         | 4.69%   |
| Skylake          | 6         | 4.69%   |
| Zen              | 4         | 3.13%   |
| Silvermont       | 4         | 3.13%   |
| SandyBridge      | 4         | 3.13%   |
| Excavator        | 4         | 3.13%   |
| Puma             | 3         | 2.34%   |
| K10              | 3         | 2.34%   |
| IceLake          | 3         | 2.34%   |
| Bonnell          | 3         | 2.34%   |
| TigerLake        | 2         | 1.56%   |
| Piledriver       | 2         | 1.56%   |
| Penryn           | 2         | 1.56%   |
| Goldmont plus    | 2         | 1.56%   |
| Bobcat           | 2         | 1.56%   |
| Westmere         | 1         | 0.78%   |
| NetBurst         | 1         | 0.78%   |
| Nehalem          | 1         | 0.78%   |
| K8 Hammer        | 1         | 0.78%   |
| Core             | 1         | 0.78%   |
| CometLake        | 1         | 0.78%   |
| Broadwell        | 1         | 0.78%   |
| Alderlake Hybrid | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 62        | 41.06%  |
| Nvidia                           | 45        | 29.8%   |
| AMD                              | 41        | 27.15%  |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Matrox Electronics Systems       | 1         | 0.66%   |
| ASPEED Technology                | 1         | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 5.16%   |
| AMD Renoir                                                                | 6         | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 5         | 3.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 4         | 2.58%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.58%   |
| Intel UHD Graphics 620                                                    | 4         | 2.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.58%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.94%   |
| Intel HD Graphics 630                                                     | 3         | 1.94%   |
| Intel HD Graphics 620                                                     | 3         | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 1.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 1.29%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.29%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 2         | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                            | 2         | 1.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.29%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.29%   |
| AMD Lucienne                                                              | 2         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2         | 1.29%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                        | 2         | 1.29%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 1         | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                     | 1         | 0.65%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                 | 1         | 0.65%   |
| Nvidia NV43 [GeForce 6600]                                                | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 30.77%  |
| 1 x AMD        | 35        | 26.92%  |
| 1 x Nvidia     | 22        | 16.92%  |
| Intel + Nvidia | 20        | 15.38%  |
| Other          | 4         | 3.08%   |
| 2 x AMD        | 2         | 1.54%   |
| AMD + Nvidia   | 2         | 1.54%   |
| 2 x Nvidia     | 1         | 0.77%   |
| 1 x SiS        | 1         | 0.77%   |
| 1 x Matrox     | 1         | 0.77%   |
| Intel + AMD    | 1         | 0.77%   |
| AMD + ASPEED   | 1         | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 89        | 68.46%  |
| Proprietary | 36        | 27.69%  |
| Unknown     | 5         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 54.89%  |
| 1.01-2.0   | 17        | 12.78%  |
| 0.01-0.5   | 14        | 10.53%  |
| 3.01-4.0   | 11        | 8.27%   |
| 0.51-1.0   | 7         | 5.26%   |
| 5.01-6.0   | 4         | 3.01%   |
| 7.01-8.0   | 2         | 1.5%    |
| 2.01-3.0   | 2         | 1.5%    |
| 8.01-16.0  | 2         | 1.5%    |
| 16.01-24.0 | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 20        | 14.81%  |
| Chimei Innolux       | 17        | 12.59%  |
| LG Display           | 13        | 9.63%   |
| BOE                  | 13        | 9.63%   |
| Samsung Electronics  | 10        | 7.41%   |
| Hewlett-Packard      | 8         | 5.93%   |
| Dell                 | 8         | 5.93%   |
| Acer                 | 5         | 3.7%    |
| Philips              | 4         | 2.96%   |
| Iiyama               | 4         | 2.96%   |
| Lenovo               | 3         | 2.22%   |
| Goldstar             | 3         | 2.22%   |
| BenQ                 | 3         | 2.22%   |
| PANDA                | 2         | 1.48%   |
| Fujitsu Siemens      | 2         | 1.48%   |
| ASUSTek Computer     | 2         | 1.48%   |
| Apple                | 2         | 1.48%   |
| AOC                  | 2         | 1.48%   |
| Ancor Communications | 2         | 1.48%   |
| Unknown              | 1         | 0.74%   |
| STD                  | 1         | 0.74%   |
| Sharp                | 1         | 0.74%   |
| Sceptre Tech         | 1         | 0.74%   |
| Sceptre              | 1         | 0.74%   |
| Panasonic            | 1         | 0.74%   |
| ONN                  | 1         | 0.74%   |
| MSI                  | 1         | 0.74%   |
| LG Philips           | 1         | 0.74%   |
| InnoLux Display      | 1         | 0.74%   |
| FUN                  | 1         | 0.74%   |
| CHR                  | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.13%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.13%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2         | 1.42%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.42%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.42%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.71%   |
| STD LCD Monitor STD0001 1920x1080                                     | 1         | 0.71%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.71%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 0.71%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.71%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.71%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.71%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 0.71%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.71%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.71%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.71%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.71%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.71%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.71%   |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 0.71%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.71%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                   | 1         | 0.71%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                 | 1         | 0.71%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.71%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05A7 2560x1440 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 44.36%  |
| 1366x768 (WXGA)    | 26        | 19.55%  |
| 1920x1200 (WUXGA)  | 6         | 4.51%   |
| 3840x2160 (4K)     | 5         | 3.76%   |
| 2560x1440 (QHD)    | 5         | 3.76%   |
| 1680x1050 (WSXGA+) | 4         | 3.01%   |
| 1600x900 (HD+)     | 4         | 3.01%   |
| 3440x1440          | 3         | 2.26%   |
| 2160x1440          | 3         | 2.26%   |
| 1280x800 (WXGA)    | 3         | 2.26%   |
| Unknown            | 3         | 2.26%   |
| 1280x1024 (SXGA)   | 2         | 1.5%    |
| 1024x600           | 2         | 1.5%    |
| 7680x1080          | 1         | 0.75%   |
| 3840x1600          | 1         | 0.75%   |
| 3840x1080          | 1         | 0.75%   |
| 2560x1600          | 1         | 0.75%   |
| 2560x1080          | 1         | 0.75%   |
| 2256x1504          | 1         | 0.75%   |
| 1360x768           | 1         | 0.75%   |
| 1280x720 (HD)      | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 25.55%  |
| 24      | 15        | 10.95%  |
| 14      | 14        | 10.22%  |
| 13      | 13        | 9.49%   |
| Unknown | 11        | 8.03%   |
| 23      | 7         | 5.11%   |
| 27      | 6         | 4.38%   |
| 21      | 6         | 4.38%   |
| 22      | 4         | 2.92%   |
| 12      | 4         | 2.92%   |
| 34      | 3         | 2.19%   |
| 17      | 3         | 2.19%   |
| 11      | 2         | 1.46%   |
| 10      | 2         | 1.46%   |
| 84      | 1         | 0.73%   |
| 40      | 1         | 0.73%   |
| 39      | 1         | 0.73%   |
| 37      | 1         | 0.73%   |
| 33      | 1         | 0.73%   |
| 31      | 1         | 0.73%   |
| 28      | 1         | 0.73%   |
| 25      | 1         | 0.73%   |
| 20      | 1         | 0.73%   |
| 19      | 1         | 0.73%   |
| 18      | 1         | 0.73%   |
| 8       | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 39.71%  |
| 501-600     | 27        | 19.85%  |
| 201-300     | 17        | 12.5%   |
| 401-500     | 12        | 8.82%   |
| Unknown     | 11        | 8.09%   |
| 701-800     | 4         | 2.94%   |
| 801-900     | 3         | 2.21%   |
| 601-700     | 3         | 2.21%   |
| 351-400     | 3         | 2.21%   |
| 1501-2000   | 1         | 0.74%   |
| 101-200     | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 92        | 71.88%  |
| 16/10   | 14        | 10.94%  |
| Unknown | 10        | 7.81%   |
| 3/2     | 5         | 3.91%   |
| 21/9    | 5         | 3.91%   |
| 5/4     | 2         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 25.93%  |
| 201-250        | 22        | 16.3%   |
| 81-90          | 21        | 15.56%  |
| Unknown        | 11        | 8.15%   |
| 251-300        | 10        | 7.41%   |
| 71-80          | 6         | 4.44%   |
| 301-350        | 6         | 4.44%   |
| 351-500        | 5         | 3.7%    |
| 61-70          | 4         | 2.96%   |
| 501-1000       | 3         | 2.22%   |
| 51-60          | 2         | 1.48%   |
| 41-50          | 2         | 1.48%   |
| 151-200        | 2         | 1.48%   |
| 141-150        | 2         | 1.48%   |
| More than 1000 | 1         | 0.74%   |
| 1-40           | 1         | 0.74%   |
| 131-140        | 1         | 0.74%   |
| 121-130        | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 30.66%  |
| 121-160       | 37        | 27.01%  |
| 101-120       | 34        | 24.82%  |
| 161-240       | 12        | 8.76%   |
| Unknown       | 11        | 8.03%   |
| More than 240 | 1         | 0.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 104       | 80.62%  |
| 2     | 22        | 17.05%  |
| 0     | 3         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 69        | 38.55%  |
| Intel                            | 52        | 29.05%  |
| Qualcomm Atheros                 | 19        | 10.61%  |
| Broadcom                         | 10        | 5.59%   |
| TP-Link                          | 3         | 1.68%   |
| Sierra Wireless                  | 3         | 1.68%   |
| Ralink Technology                | 3         | 1.68%   |
| Broadcom Limited                 | 3         | 1.68%   |
| Xiaomi                           | 2         | 1.12%   |
| Qualcomm Atheros Communications  | 2         | 1.12%   |
| Cypress Semiconductor            | 2         | 1.12%   |
| Tenda                            | 1         | 0.56%   |
| Standard Microsystems            | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Ralink                           | 1         | 0.56%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.56%   |
| Nvidia                           | 1         | 0.56%   |
| MediaTek                         | 1         | 0.56%   |
| DisplayLink                      | 1         | 0.56%   |
| ASIX Electronics                 | 1         | 0.56%   |
| Arduino SA                       | 1         | 0.56%   |
| Apple                            | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 21.9%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.29%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.43%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.43%   |
| Intel Wireless 8260                                               | 3         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.95%   |
| Intel Wireless 7260                                               | 2         | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.95%   |
| Cypress K38231_03                                                 | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.48%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.48%   |
| Tenda U12                                                         | 1         | 0.48%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.48%   |
| Sierra Wireless EM7455                                            | 1         | 0.48%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.48%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 41.49%  |
| Realtek Semiconductor           | 20        | 21.28%  |
| Qualcomm Atheros                | 16        | 17.02%  |
| Broadcom                        | 4         | 4.26%   |
| Sierra Wireless                 | 3         | 3.19%   |
| Ralink Technology               | 3         | 3.19%   |
| Broadcom Limited                | 3         | 3.19%   |
| TP-Link                         | 2         | 2.13%   |
| Qualcomm Atheros Communications | 2         | 2.13%   |
| Tenda                           | 1         | 1.06%   |
| Ralink                          | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 10.64%  |
| Intel Wireless 8265 / 8275                                              | 6         | 6.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 4.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 3.19%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.19%   |
| Intel Wireless 8260                                                     | 3         | 3.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 3.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 2.13%   |
| Intel Wireless 7260                                                     | 2         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.06%   |
| Tenda U12                                                               | 1         | 1.06%   |
| Sierra Wireless EM7455                                                  | 1         | 1.06%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.06%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.06%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.06%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.06%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.06%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.06%   |
| Intel WiFi Link 5100                                                    | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 63        | 55.26%  |
| Intel                            | 28        | 24.56%  |
| Broadcom                         | 7         | 6.14%   |
| Qualcomm Atheros                 | 4         | 3.51%   |
| Xiaomi                           | 2         | 1.75%   |
| Cypress Semiconductor            | 2         | 1.75%   |
| TP-Link                          | 1         | 0.88%   |
| Standard Microsystems            | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| Nvidia                           | 1         | 0.88%   |
| MediaTek                         | 1         | 0.88%   |
| DisplayLink                      | 1         | 0.88%   |
| ASIX Electronics                 | 1         | 0.88%   |
| Apple                            | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 40.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 7.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.39%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.39%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.75%   |
| Cypress K38231_03                                                 | 2         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.88%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.88%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.88%   |
| MediaTek N152DL                                                   | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.88%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.88%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.88%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.88%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 53.54%  |
| WiFi     | 90        | 45.45%  |
| Modem    | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 60.32%  |
| Ethernet | 50        | 39.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 46.09%  |
| 2     | 57        | 44.53%  |
| 0     | 7         | 5.47%   |
| 3     | 4         | 3.13%   |
| 4     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 89.23%  |
| Yes  | 14        | 10.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 42.86%  |
| Realtek Semiconductor           | 12        | 15.58%  |
| Cambridge Silicon Radio         | 7         | 9.09%   |
| Lite-On Technology              | 6         | 7.79%   |
| Broadcom                        | 6         | 7.79%   |
| Qualcomm Atheros Communications | 4         | 5.19%   |
| IMC Networks                    | 3         | 3.9%    |
| Realtek                         | 2         | 2.6%    |
| Foxconn / Hon Hai               | 2         | 2.6%    |
| Dell                            | 1         | 1.3%    |
| Apple                           | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 14.29%  |
| Intel AX200 Bluetooth                               | 10        | 12.99%  |
| Realtek Bluetooth Radio                             | 8         | 10.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.9%    |
| Intel AX201 Bluetooth                               | 3         | 3.9%    |
| Realtek Bluetooth Radio                             | 2         | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.6%    |
| Intel AX210 Bluetooth                               | 2         | 2.6%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.3%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.3%    |
| IMC Networks Bluetooth Device                       | 1         | 1.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.3%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.3%    |
| Dell Wireless 365 Bluetooth                         | 1         | 1.3%    |
| Broadcom HP Portable Valentine                      | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.3%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.3%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.3%    |
| Apple Bluetooth Host Controller                     | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 41.71%  |
| AMD                              | 47        | 26.86%  |
| Nvidia                           | 29        | 16.57%  |
| C-Media Electronics              | 5         | 2.86%   |
| Logitech                         | 4         | 2.29%   |
| JMTek                            | 4         | 2.29%   |
| Texas Instruments                | 2         | 1.14%   |
| Creative Technology              | 2         | 1.14%   |
| VIA Technologies                 | 1         | 0.57%   |
| Unknown                          | 1         | 0.57%   |
| SteelSeries ApS                  | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| SAVITECH                         | 1         | 0.57%   |
| Focusrite-Novation               | 1         | 0.57%   |
| Elgato Systems                   | 1         | 0.57%   |
| Corsair                          | 1         | 0.57%   |
| Cambridge Audio                  | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 5.99%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 4.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 3.69%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.3%    |
| JMTek USB PnP Audio Device                                                 | 4         | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.84%   |
| AMD High Definition Audio Controller                                       | 4         | 1.84%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.38%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.38%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.38%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.92%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.92%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 25        | 24.75%  |
| Samsung Electronics | 24        | 23.76%  |
| Kingston            | 11        | 10.89%  |
| Micron Technology   | 8         | 7.92%   |
| Unknown             | 7         | 6.93%   |
| G.Skill             | 6         | 5.94%   |
| Corsair             | 5         | 4.95%   |
| A-DATA Technology   | 5         | 4.95%   |
| Crucial             | 3         | 2.97%   |
| Ramaxel Technology  | 2         | 1.98%   |
| Transcend           | 1         | 0.99%   |
| Patriot             | 1         | 0.99%   |
| Elpida              | 1         | 0.99%   |
| Avant               | 1         | 0.99%   |
| 48spaces            | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 3         | 2.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 1.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 1.79%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 1.79%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 2         | 1.79%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                 | 1         | 0.89%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s          | 1         | 0.89%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1         | 0.89%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1         | 0.89%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s            | 1         | 0.89%   |
| Unknown RAM Module 1GB SODIMM DDR2                        | 1         | 0.89%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s      | 1         | 0.89%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 0.89%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.89%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 0.89%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s | 1         | 0.89%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.89%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s         | 1         | 0.89%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s      | 1         | 0.89%   |
| SK hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s      | 1         | 0.89%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 0.89%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 0.89%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.89%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 49.45%  |
| DDR3    | 35        | 38.46%  |
| LPDDR4  | 3         | 3.3%    |
| LPDDR3  | 3         | 3.3%    |
| DDR2    | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| DDR5    | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 62.22%  |
| DIMM         | 30        | 33.33%  |
| Row Of Chips | 4         | 4.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 44.9%   |
| 4096  | 32        | 32.65%  |
| 16384 | 11        | 11.22%  |
| 2048  | 7         | 7.14%   |
| 1024  | 3         | 3.06%   |
| 512   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 23.23%  |
| 2667    | 17        | 17.17%  |
| 3200    | 12        | 12.12%  |
| 2400    | 9         | 9.09%   |
| 1333    | 9         | 9.09%   |
| 1334    | 5         | 5.05%   |
| 3600    | 4         | 4.04%   |
| 2133    | 4         | 4.04%   |
| 3000    | 2         | 2.02%   |
| 1867    | 2         | 2.02%   |
| 4800    | 1         | 1.01%   |
| 4266    | 1         | 1.01%   |
| 3866    | 1         | 1.01%   |
| 3733    | 1         | 1.01%   |
| 3333    | 1         | 1.01%   |
| 2933    | 1         | 1.01%   |
| 2800    | 1         | 1.01%   |
| 2666    | 1         | 1.01%   |
| 1067    | 1         | 1.01%   |
| 667     | 1         | 1.01%   |
| 533     | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

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
| Chicony Electronics                    | 26        | 30.23%  |
| IMC Networks                           | 13        | 15.12%  |
| Microdia                               | 10        | 11.63%  |
| Realtek Semiconductor                  | 7         | 8.14%   |
| Logitech                               | 7         | 8.14%   |
| Acer                                   | 6         | 6.98%   |
| Quanta                                 | 5         | 5.81%   |
| Sunplus Innovation Technology          | 3         | 3.49%   |
| Suyin                                  | 2         | 2.33%   |
| MacroSilicon                           | 2         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.33%   |
| Silicon Motion                         | 1         | 1.16%   |
| Microsoft                              | 1         | 1.16%   |
| GEMBIRD                                | 1         | 1.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 7         | 7.95%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 4.55%   |
| Realtek USB Camera                            | 3         | 3.41%   |
| Quanta HD User Facing                         | 3         | 3.41%   |
| Logitech Webcam C270                          | 3         | 3.41%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 3.41%   |
| Suyin HP TrueVision HD                        | 2         | 2.27%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.27%   |
| Microdia Integrated_Webcam_HD                 | 2         | 2.27%   |
| Microdia HP Integrated Webcam                 | 2         | 2.27%   |
| IMC Networks HD Camera                        | 2         | 2.27%   |
| Chicony USB 2.0 Camera                        | 2         | 2.27%   |
| Chicony HP TrueVision HD Camera               | 2         | 2.27%   |
| Chicony HD WebCam                             | 2         | 2.27%   |
| Chicony EasyCamera                            | 2         | 2.27%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.14%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.14%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.14%   |
| Realtek Laptop Camera                         | 1         | 1.14%   |
| Realtek Integrated Webcam HD                  | 1         | 1.14%   |
| Realtek HD WebCam                             | 1         | 1.14%   |
| Quanta VGA WebCam                             | 1         | 1.14%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.14%   |
| Microsoft LifeCam HD-3000                     | 1         | 1.14%   |
| Microdia Webcam Vitade AF                     | 1         | 1.14%   |
| Microdia Webcam                               | 1         | 1.14%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.14%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.14%   |
| Microdia Hy-HD-Camera                         | 1         | 1.14%   |
| Microdia Camera                               | 1         | 1.14%   |
| MacroSilicon USB Video                        | 1         | 1.14%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1         | 1.14%   |
| Logitech Webcam C930e                         | 1         | 1.14%   |
| Logitech HD Webcam C615                       | 1         | 1.14%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.14%   |
| Logitech C505 HD Webcam                       | 1         | 1.14%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.14%   |
| IMC Networks Integrated Camera                | 1         | 1.14%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.14%   |
| IMC Networks EasyCamera                       | 1         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 54.55%  |
| Validity Sensors           | 3         | 27.27%  |
| Upek                       | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 36.36%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 27.27%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics  WBDI                                        | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Lenovo      | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| Lenovo Integrated Smart Card Reader            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 101       | 78.29%  |
| 1     | 20        | 15.5%   |
| 2     | 6         | 4.65%   |
| 3     | 2         | 1.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 29.73%  |
| Net/wireless             | 5         | 13.51%  |
| Graphics card            | 5         | 13.51%  |
| Chipcard                 | 5         | 13.51%  |
| Camera                   | 4         | 10.81%  |
| Sound                    | 3         | 8.11%   |
| Multimedia controller    | 2         | 5.41%   |
| Net/ethernet             | 1         | 2.7%    |
| Communication controller | 1         | 2.7%    |

