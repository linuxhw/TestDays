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

Total: 202

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | Notebook    | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| ASUSTek       | Q325UAR                     | Convertible | [b95d2d4e30](https://linux-hardware.org/?probe=b95d2d4e30) | Feb 02, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [43ba50f36c](https://linux-hardware.org/?probe=43ba50f36c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| MSI           | B550M PRO                   | Desktop     | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| MSI           | B550M PRO                   | Desktop     | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 103       | 66.45%  |
| Void Linux         | 52        | 33.55%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 152       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 5.13.19_1 | 7         | 4.24%   |
| 5.8.18_1  | 5         | 3.03%   |
| 6.1.4_1   | 4         | 2.42%   |
| 6.1.31_1  | 4         | 2.42%   |
| 5.3.9_1   | 4         | 2.42%   |
| 5.18.19_1 | 4         | 2.42%   |
| 5.16.20_1 | 4         | 2.42%   |
| 5.10.17_1 | 4         | 2.42%   |
| 5.8.12_1  | 3         | 1.82%   |
| 5.19.17_1 | 3         | 1.82%   |
| 5.18.14_1 | 3         | 1.82%   |
| 5.15.32_1 | 3         | 1.82%   |
| 5.13.13_1 | 3         | 1.82%   |
| 5.12.10_1 | 3         | 1.82%   |
| 6.1.21_1  | 2         | 1.21%   |
| 6.1.10_1  | 2         | 1.21%   |
| 6.0.15_1  | 2         | 1.21%   |
| 6.0.13_1  | 2         | 1.21%   |
| 5.9.14_1  | 2         | 1.21%   |
| 5.4.24_1  | 2         | 1.21%   |
| 5.4.13_2  | 2         | 1.21%   |
| 5.19.16_1 | 2         | 1.21%   |
| 5.18.9_1  | 2         | 1.21%   |
| 5.15.41_1 | 2         | 1.21%   |
| 5.15.34_1 | 2         | 1.21%   |
| 5.15.22_1 | 2         | 1.21%   |
| 5.15.16_1 | 2         | 1.21%   |
| 5.13.15_1 | 2         | 1.21%   |
| 5.13.10_1 | 2         | 1.21%   |
| 5.12.14_1 | 2         | 1.21%   |
| 5.11.9_1  | 2         | 1.21%   |
| 5.10.14_1 | 2         | 1.21%   |
| 6.2.8_1   | 1         | 0.61%   |
| 6.2.11_1  | 1         | 0.61%   |
| 6.1.9_1   | 1         | 0.61%   |
| 6.1.7_1   | 1         | 0.61%   |
| 6.1.3_1   | 1         | 0.61%   |
| 6.1.29_1  | 1         | 0.61%   |
| 6.1.18_1  | 1         | 0.61%   |
| 6.1.14_1  | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.19 | 7         | 4.24%   |
| 5.8.18  | 5         | 3.03%   |
| 6.1.4   | 4         | 2.42%   |
| 6.1.31  | 4         | 2.42%   |
| 5.8.12  | 4         | 2.42%   |
| 5.3.9   | 4         | 2.42%   |
| 5.18.19 | 4         | 2.42%   |
| 5.16.20 | 4         | 2.42%   |
| 5.10.17 | 4         | 2.42%   |
| 5.19.17 | 3         | 1.82%   |
| 5.18.14 | 3         | 1.82%   |
| 5.15.32 | 3         | 1.82%   |
| 5.13.13 | 3         | 1.82%   |
| 5.12.10 | 3         | 1.82%   |
| 6.1.21  | 2         | 1.21%   |
| 6.1.10  | 2         | 1.21%   |
| 6.0.15  | 2         | 1.21%   |
| 6.0.13  | 2         | 1.21%   |
| 5.9.14  | 2         | 1.21%   |
| 5.4.24  | 2         | 1.21%   |
| 5.4.13  | 2         | 1.21%   |
| 5.19.16 | 2         | 1.21%   |
| 5.18.9  | 2         | 1.21%   |
| 5.15.41 | 2         | 1.21%   |
| 5.15.34 | 2         | 1.21%   |
| 5.15.22 | 2         | 1.21%   |
| 5.15.16 | 2         | 1.21%   |
| 5.13.15 | 2         | 1.21%   |
| 5.13.10 | 2         | 1.21%   |
| 5.12.14 | 2         | 1.21%   |
| 5.11.9  | 2         | 1.21%   |
| 5.10.14 | 2         | 1.21%   |
| 6.2.8   | 1         | 0.61%   |
| 6.2.11  | 1         | 0.61%   |
| 6.1.9   | 1         | 0.61%   |
| 6.1.7   | 1         | 0.61%   |
| 6.1.3   | 1         | 0.61%   |
| 6.1.29  | 1         | 0.61%   |
| 6.1.18  | 1         | 0.61%   |
| 6.1.14  | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 14.72%  |
| 6.1     | 19        | 11.66%  |
| 5.8     | 18        | 11.04%  |
| 5.13    | 16        | 9.82%   |
| 5.10    | 15        | 9.2%    |
| 5.18    | 12        | 7.36%   |
| 5.12    | 9         | 5.52%   |
| 5.4     | 7         | 4.29%   |
| 6.0     | 6         | 3.68%   |
| 5.3     | 5         | 3.07%   |
| 5.19    | 5         | 3.07%   |
| 5.11    | 5         | 3.07%   |
| 5.9     | 4         | 2.45%   |
| 5.16    | 4         | 2.45%   |
| 4.19    | 4         | 2.45%   |
| 6.2     | 2         | 1.23%   |
| 5.7     | 1         | 0.61%   |
| 5.6     | 1         | 0.61%   |
| 5.2     | 1         | 0.61%   |
| 5.17    | 1         | 0.61%   |
| 5.14    | 1         | 0.61%   |
| 5.1     | 1         | 0.61%   |
| 4.4     | 1         | 0.61%   |
| 4.14    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 141       | 92.76%  |
| i686    | 5         | 3.29%   |
| aarch64 | 3         | 1.97%   |
| ppc64le | 1         | 0.66%   |
| ppc64   | 1         | 0.66%   |
| armv7l  | 1         | 0.66%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 70        | 44.3%   |
| XFCE         | 19        | 12.03%  |
| KDE5         | 11        | 6.96%   |
| KDE          | 11        | 6.96%   |
| MATE         | 9         | 5.7%    |
| GNOME        | 8         | 5.06%   |
| i3           | 6         | 3.8%    |
| X-Cinnamon   | 5         | 3.16%   |
| sway         | 3         | 1.9%    |
| openbox      | 3         | 1.9%    |
| bspwm        | 3         | 1.9%    |
| awesome      | 3         | 1.9%    |
| Lumina       | 2         | 1.27%   |
| river        | 1         | 0.63%   |
| LXQt         | 1         | 0.63%   |
| LXDE         | 1         | 0.63%   |
| dwm          | 1         | 0.63%   |
| dot-xsession | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 69.03%  |
| Wayland | 18        | 11.61%  |
| Tty     | 17        | 10.97%  |
| Unknown | 13        | 8.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 125       | 80.13%  |
| LightDM | 12        | 7.69%   |
| SDDM    | 8         | 5.13%   |
| LXDM    | 8         | 5.13%   |
| SLiM    | 1         | 0.64%   |
| LDM     | 1         | 0.64%   |
| GDM     | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 81        | 51.27%  |
| Unknown | 20        | 12.66%  |
| en_GB   | 8         | 5.06%   |
| en_DK   | 6         | 3.8%    |
| ru_RU   | 5         | 3.16%   |
| de_DE   | 5         | 3.16%   |
| fr_FR   | 4         | 2.53%   |
| es_ES   | 4         | 2.53%   |
| it_IT   | 3         | 1.9%    |
| cs_CZ   | 3         | 1.9%    |
| pt_BR   | 2         | 1.27%   |
| pl_PL   | 2         | 1.27%   |
| en_CA   | 2         | 1.27%   |
| en_AU   | 2         | 1.27%   |
| tr_TR   | 1         | 0.63%   |
| ru_UA   | 1         | 0.63%   |
| nb_NO   | 1         | 0.63%   |
| es_HN   | 1         | 0.63%   |
| es_DO   | 1         | 0.63%   |
| es_AR   | 1         | 0.63%   |
| en_NZ   | 1         | 0.63%   |
| en_IE   | 1         | 0.63%   |
| el_GR   | 1         | 0.63%   |
| ca_ES   | 1         | 0.63%   |
| bg_BG   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 84        | 53.85%  |
| BIOS | 72        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 63.46%  |
| Btrfs   | 32        | 20.51%  |
| Xfs     | 9         | 5.77%   |
| Zfs     | 8         | 5.13%   |
| Unknown | 6         | 3.85%   |
| F2fs    | 1         | 0.64%   |
| Ext3    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 90        | 57.69%  |
| Unknown | 45        | 28.85%  |
| MBR     | 21        | 13.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 87.5%   |
| Yes       | 19        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 77.92%  |
| Yes       | 34        | 22.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 33        | 21.71%  |
| Lenovo                  | 29        | 19.08%  |
| Hewlett-Packard         | 17        | 11.18%  |
| Dell                    | 14        | 9.21%   |
| Acer                    | 14        | 9.21%   |
| MSI                     | 10        | 6.58%   |
| ASRock                  | 8         | 5.26%   |
| Unknown                 | 5         | 3.29%   |
| Gigabyte Technology     | 4         | 2.63%   |
| Microsoft               | 2         | 1.32%   |
| HUAWEI                  | 2         | 1.32%   |
| Timi                    | 1         | 0.66%   |
| Samsung Electronics     | 1         | 0.66%   |
| Raspberry Pi Foundation | 1         | 0.66%   |
| Positivo                | 1         | 0.66%   |
| Pine Microsystems       | 1         | 0.66%   |
| Notebook                | 1         | 0.66%   |
| Nokia                   | 1         | 0.66%   |
| Getac                   | 1         | 0.66%   |
| Framework               | 1         | 0.66%   |
| Exo                     | 1         | 0.66%   |
| Digibras                | 1         | 0.66%   |
| Cisco Systems           | 1         | 0.66%   |
| Chuwi                   | 1         | 0.66%   |
| Apple                   | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 5         | 3.29%   |
| HP Laptop 15-bw0xx                        | 2         | 1.32%   |
| Dell OptiPlex 7010                        | 2         | 1.32%   |
| ASUS PRIME Z390-P                         | 2         | 1.32%   |
| Acer Swift SF314-42                       | 2         | 1.32%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.66%   |
| Samsung 275E4E/275E5E                     | 1         | 0.66%   |
| RPi Raspberry Pi                          | 1         | 0.66%   |
| Positivo Mobile                           | 1         | 0.66%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.66%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.66%   |
| Nokia Booklet 3G                          | 1         | 0.66%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.66%   |
| MSI MS-7D14                               | 1         | 0.66%   |
| MSI MS-7C92                               | 1         | 0.66%   |
| MSI MS-7C52                               | 1         | 0.66%   |
| MSI MS-7C02                               | 1         | 0.66%   |
| MSI MS-7A68                               | 1         | 0.66%   |
| MSI MS-7A39                               | 1         | 0.66%   |
| MSI MS-7816                               | 1         | 0.66%   |
| MSI GV72 7RE                              | 1         | 0.66%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.66%   |
| Microsoft Surface with Windows RT         | 1         | 0.66%   |
| Microsoft Surface Go 2                    | 1         | 0.66%   |
| Lenovo Yoga 720-15IKB 80X7                | 1         | 0.66%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.66%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.66%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.66%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.66%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS    | 1         | 0.66%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.66%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.66%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.66%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.66%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.66%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 0.66%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 0.66%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 0.66%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 0.66%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 16        | 10.53%  |
| Lenovo IdeaPad           | 8         | 5.26%   |
| Acer Aspire              | 8         | 5.26%   |
| ASUS PRIME               | 7         | 4.61%   |
| ASUS VivoBook            | 6         | 3.95%   |
| HP Laptop                | 5         | 3.29%   |
| Unknown                  | 5         | 3.29%   |
| Dell OptiPlex            | 4         | 2.63%   |
| Dell Inspiron            | 4         | 2.63%   |
| HP Pavilion              | 3         | 1.97%   |
| Dell Latitude            | 3         | 1.97%   |
| Microsoft Surface        | 2         | 1.32%   |
| HP Stream                | 2         | 1.32%   |
| HP ENVY                  | 2         | 1.32%   |
| ASUS TUF                 | 2         | 1.32%   |
| ASUS ROG                 | 2         | 1.32%   |
| Acer Swift               | 2         | 1.32%   |
| Timi Redmi               | 1         | 0.66%   |
| Samsung 275E4E           | 1         | 0.66%   |
| RPi Raspberry            | 1         | 0.66%   |
| Positivo Mobile          | 1         | 0.66%   |
| Pine Microsystems Pine64 | 1         | 0.66%   |
| Notebook NV4XMB          | 1         | 0.66%   |
| Nokia Booklet            | 1         | 0.66%   |
| MSI Summit               | 1         | 0.66%   |
| MSI MS-7D14              | 1         | 0.66%   |
| MSI MS-7C92              | 1         | 0.66%   |
| MSI MS-7C52              | 1         | 0.66%   |
| MSI MS-7C02              | 1         | 0.66%   |
| MSI MS-7A68              | 1         | 0.66%   |
| MSI MS-7A39              | 1         | 0.66%   |
| MSI MS-7816              | 1         | 0.66%   |
| MSI GV72                 | 1         | 0.66%   |
| MSI Bravo                | 1         | 0.66%   |
| Lenovo Yoga              | 1         | 0.66%   |
| Lenovo Y520-15IKB        | 1         | 0.66%   |
| Lenovo Legion            | 1         | 0.66%   |
| Lenovo G50-70            | 1         | 0.66%   |
| Lenovo G50-45            | 1         | 0.66%   |
| HUAWEI KLVL-WXXW         | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 23        | 15.13%  |
| 2018    | 19        | 12.5%   |
| 2020    | 18        | 11.84%  |
| 2017    | 12        | 7.89%   |
| 2013    | 12        | 7.89%   |
| 2016    | 10        | 6.58%   |
| 2014    | 9         | 5.92%   |
| 2012    | 9         | 5.92%   |
| 2021    | 6         | 3.95%   |
| 2015    | 6         | 3.95%   |
| 2011    | 6         | 3.95%   |
| 2022    | 5         | 3.29%   |
| 2010    | 5         | 3.29%   |
| Unknown | 5         | 3.29%   |
| 2009    | 2         | 1.32%   |
| 2008    | 2         | 1.32%   |
| 2007    | 1         | 0.66%   |
| 2006    | 1         | 0.66%   |
| 2005    | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 96        | 63.16%  |
| Desktop        | 46        | 30.26%  |
| Convertible    | 4         | 2.63%   |
| Tablet         | 3         | 1.97%   |
| System on chip | 1         | 0.66%   |
| Mini pc        | 1         | 0.66%   |
| Server         | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 152       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 35        | 22.73%  |
| 4.01-8.0        | 32        | 20.78%  |
| 8.01-16.0       | 28        | 18.18%  |
| 3.01-4.0        | 26        | 16.88%  |
| 32.01-64.0      | 14        | 9.09%   |
| 1.01-2.0        | 7         | 4.55%   |
| 0.51-1.0        | 4         | 2.6%    |
| 24.01-32.0      | 3         | 1.95%   |
| 64.01-256.0     | 2         | 1.3%    |
| More than 256.0 | 1         | 0.65%   |
| 2.01-3.0        | 1         | 0.65%   |
| 0.01-0.5        | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 46        | 28.4%   |
| 2.01-3.0    | 36        | 22.22%  |
| 0.51-1.0    | 24        | 14.81%  |
| 3.01-4.0    | 19        | 11.73%  |
| 4.01-8.0    | 17        | 10.49%  |
| 8.01-16.0   | 9         | 5.56%   |
| 0.01-0.5    | 7         | 4.32%   |
| 16.01-24.0  | 3         | 1.85%   |
| 64.01-256.0 | 1         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 61.04%  |
| 2      | 36        | 23.38%  |
| 3      | 17        | 11.04%  |
| 4      | 3         | 1.95%   |
| 5      | 2         | 1.3%    |
| 9      | 1         | 0.65%   |
| 0      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 78.95%  |
| Yes       | 32        | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 79.61%  |
| No        | 31        | 20.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 73.86%  |
| No        | 40        | 26.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 63.4%   |
| No        | 56        | 36.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 30        | 19.74%  |
| Germany            | 14        | 9.21%   |
| Russia             | 13        | 8.55%   |
| India              | 10        | 6.58%   |
| Brazil             | 7         | 4.61%   |
| Czechia            | 6         | 3.95%   |
| France             | 5         | 3.29%   |
| Denmark            | 5         | 3.29%   |
| Ukraine            | 4         | 2.63%   |
| UK                 | 4         | 2.63%   |
| Poland             | 4         | 2.63%   |
| Turkey             | 3         | 1.97%   |
| Switzerland        | 3         | 1.97%   |
| Spain              | 3         | 1.97%   |
| Netherlands        | 3         | 1.97%   |
| Greece             | 3         | 1.97%   |
| Bulgaria           | 3         | 1.97%   |
| Australia          | 3         | 1.97%   |
| Argentina          | 3         | 1.97%   |
| Serbia             | 2         | 1.32%   |
| Morocco            | 2         | 1.32%   |
| Italy              | 2         | 1.32%   |
| Canada             | 2         | 1.32%   |
| Vietnam            | 1         | 0.66%   |
| Uruguay            | 1         | 0.66%   |
| Sweden             | 1         | 0.66%   |
| Peru               | 1         | 0.66%   |
| Norway             | 1         | 0.66%   |
| New Zealand        | 1         | 0.66%   |
| Mexico             | 1         | 0.66%   |
| Latvia             | 1         | 0.66%   |
| Indonesia          | 1         | 0.66%   |
| Honduras           | 1         | 0.66%   |
| Guatemala          | 1         | 0.66%   |
| Finland            | 1         | 0.66%   |
| Ecuador            | 1         | 0.66%   |
| Dominican Republic | 1         | 0.66%   |
| Colombia           | 1         | 0.66%   |
| Belgium            | 1         | 0.66%   |
| Bangladesh         | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Prague        | 5         | 3.21%   |
| St Petersburg | 3         | 1.92%   |
| Moscow        | 3         | 1.92%   |
| Denver        | 3         | 1.92%   |
| Amsterdam     | 3         | 1.92%   |
| Spring Hill   | 2         | 1.28%   |
| Sofia         | 2         | 1.28%   |
| Rome          | 2         | 1.28%   |
| Orlando       | 2         | 1.28%   |
| Munich        | 2         | 1.28%   |
| Meknes        | 2         | 1.28%   |
| Lublin        | 2         | 1.28%   |
| Hyderabad     | 2         | 1.28%   |
| Geneva        | 2         | 1.28%   |
| Zagnansk      | 1         | 0.64%   |
| Yekaterinburg | 1         | 0.64%   |
| Yambol        | 1         | 0.64%   |
| Weatherford   | 1         | 0.64%   |
| Volgograd     | 1         | 0.64%   |
| Vlaardingen   | 1         | 0.64%   |
| Vienna        | 1         | 0.64%   |
| Viby J        | 1         | 0.64%   |
| Varna         | 1         | 0.64%   |
| Trujillo      | 1         | 0.64%   |
| Toulouse      | 1         | 0.64%   |
| Touget        | 1         | 0.64%   |
| Toms River    | 1         | 0.64%   |
| Tegucigalpa   | 1         | 0.64%   |
| Syktyvkar     | 1         | 0.64%   |
| Sydney        | 1         | 0.64%   |
| Surabaya      | 1         | 0.64%   |
| Sun Prairie   | 1         | 0.64%   |
| Stratford     | 1         | 0.64%   |
| South Shields | 1         | 0.64%   |
| Solone        | 1         | 0.64%   |
| Sohren        | 1         | 0.64%   |
| Sistranda     | 1         | 0.64%   |
| Saxtons River | 1         | 0.64%   |
| Savannah      | 1         | 0.64%   |
| Sao Paulo     | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 45        | 60     | 20.27%  |
| WDC                       | 35        | 43     | 15.77%  |
| Seagate                   | 34        | 43     | 15.32%  |
| Kingston                  | 15        | 16     | 6.76%   |
| Unknown                   | 12        | 18     | 5.41%   |
| SanDisk                   | 11        | 13     | 4.95%   |
| Toshiba                   | 9         | 10     | 4.05%   |
| HGST                      | 8         | 9      | 3.6%    |
| Intel                     | 7         | 9      | 3.15%   |
| Crucial                   | 7         | 8      | 3.15%   |
| SK hynix                  | 6         | 6      | 2.7%    |
| Hitachi                   | 4         | 4      | 1.8%    |
| Phison                    | 3         | 3      | 1.35%   |
| Micron Technology         | 3         | 3      | 1.35%   |
| Patriot                   | 2         | 2      | 0.9%    |
| Micron/Crucial Technology | 2         | 2      | 0.9%    |
| Corsair                   | 2         | 2      | 0.9%    |
| A-DATA Technology         | 2         | 3      | 0.9%    |
| XPG                       | 1         | 4      | 0.45%   |
| Transcend                 | 1         | 1      | 0.45%   |
| SPCC                      | 1         | 1      | 0.45%   |
| PNY                       | 1         | 1      | 0.45%   |
| Phison Electronics        | 1         | 1      | 0.45%   |
| OCZ                       | 1         | 1      | 0.45%   |
| Maxtor                    | 1         | 1      | 0.45%   |
| LITEONIT                  | 1         | 1      | 0.45%   |
| Lenovo                    | 1         | 1      | 0.45%   |
| KIOXIA                    | 1         | 1      | 0.45%   |
| INNOVATION IT             | 1         | 1      | 0.45%   |
| Gigabyte Technology       | 1         | 2      | 0.45%   |
| China                     | 1         | 1      | 0.45%   |
| BHT                       | 1         | 1      | 0.45%   |
| Apple                     | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                           | 5         | 2.07%   |
| Seagate ST1000LM035-1RK172 1TB                   | 5         | 2.07%   |
| Kingston SA400S37240G 240GB SSD                  | 5         | 2.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 4         | 1.65%   |
| WDC WD10EZEX-08WN4A0 1TB                         | 3         | 1.24%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 1.24%   |
| Seagate ST2000DM008-2FR102 2TB                   | 3         | 1.24%   |
| Samsung SSD 870 EVO 500GB                        | 3         | 1.24%   |
| Samsung NVMe SSD Drive 1TB                       | 3         | 1.24%   |
| Kingston SHFS37A120G 120GB SSD                   | 3         | 1.24%   |
| Crucial CT500MX500SSD1 500GB                     | 3         | 1.24%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                 | 2         | 0.83%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 0.83%   |
| Toshiba MQ04ABF100 1TB                           | 2         | 0.83%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB          | 2         | 0.83%   |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 0.83%   |
| Seagate ST1000LM049-2GH172 1TB                   | 2         | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB                   | 2         | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB | 2         | 0.83%   |
| Samsung SSD 980 PRO 500GB                        | 2         | 0.83%   |
| Samsung SSD 970 EVO Plus 1TB                     | 2         | 0.83%   |
| Samsung SSD 860 EVO 500GB                        | 2         | 0.83%   |
| Samsung SSD 850 EVO 500GB                        | 2         | 0.83%   |
| Samsung NVMe SSD Drive 500GB                     | 2         | 0.83%   |
| Patriot Burst 120GB SSD                          | 2         | 0.83%   |
| Kingston SA400S37120G 120GB SSD                  | 2         | 0.83%   |
| Intel SSDPEKNW512G8 512GB                        | 2         | 0.83%   |
| HGST HTS545050A7E680 500GB                       | 2         | 0.83%   |
| HGST HTS541010B7E610 1TB                         | 2         | 0.83%   |
| HGST HTS541010A9E680 1TB                         | 2         | 0.83%   |
| XPG NVMe SSD Drive 2TB                           | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                 | 1         | 0.41%   |
| WDC WD7500AYYS-01RCA0 752GB                      | 1         | 0.41%   |
| WDC WD60 EFRX-68L0BN1 6TB                        | 1         | 0.41%   |
| WDC WD5000LPCX-22VHAT0 500GB                     | 1         | 0.41%   |
| WDC WD5000LPCX-21VHAT0 500GB                     | 1         | 0.41%   |
| WDC WD5000AADS-00S9B0 500GB                      | 1         | 0.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 0.41%   |
| WDC WD3200AAKS-22SBA0 320GB                      | 1         | 0.41%   |
| WDC WD2500BEVT-22A23T0 250GB                     | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 43     | 37.36%  |
| WDC                 | 29        | 36     | 31.87%  |
| Toshiba             | 8         | 9      | 8.79%   |
| HGST                | 8         | 9      | 8.79%   |
| Samsung Electronics | 6         | 7      | 6.59%   |
| Hitachi             | 4         | 4      | 4.4%    |
| Unknown             | 1         | 1      | 1.1%    |
| Maxtor              | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 21     | 28.13%  |
| Kingston            | 14        | 15     | 21.88%  |
| SanDisk             | 6         | 7      | 9.38%   |
| Crucial             | 5         | 6      | 7.81%   |
| WDC                 | 3         | 3      | 4.69%   |
| Patriot             | 2         | 2      | 3.13%   |
| Intel               | 2         | 2      | 3.13%   |
| Transcend           | 1         | 1      | 1.56%   |
| SPCC                | 1         | 1      | 1.56%   |
| SK hynix            | 1         | 1      | 1.56%   |
| PNY                 | 1         | 1      | 1.56%   |
| OCZ                 | 1         | 1      | 1.56%   |
| LITEONIT            | 1         | 1      | 1.56%   |
| Lenovo              | 1         | 1      | 1.56%   |
| INNOVATION IT       | 1         | 1      | 1.56%   |
| Gigabyte Technology | 1         | 2      | 1.56%   |
| Corsair             | 1         | 1      | 1.56%   |
| China               | 1         | 1      | 1.56%   |
| BHT                 | 1         | 1      | 1.56%   |
| Apple               | 1         | 1      | 1.56%   |
| A-DATA Technology   | 1         | 2      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 76        | 110    | 37.81%  |
| SSD     | 58        | 72     | 28.86%  |
| NVMe    | 54        | 73     | 26.87%  |
| MMC     | 11        | 15     | 5.47%   |
| Unknown | 2         | 3      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 178    | 60.56%  |
| NVMe | 54        | 73     | 30%     |
| MMC  | 11        | 15     | 6.11%   |
| SAS  | 6         | 7      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 98     | 53.19%  |
| 0.51-1.0   | 48        | 58     | 34.04%  |
| 1.01-2.0   | 14        | 21     | 9.93%   |
| 4.01-10.0  | 3         | 3      | 2.13%   |
| 3.01-4.0   | 1         | 2      | 0.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 45        | 28.85%  |
| 501-1000       | 31        | 19.87%  |
| 101-250        | 28        | 17.95%  |
| Unknown        | 12        | 7.69%   |
| 1001-2000      | 11        | 7.05%   |
| 1-20           | 8         | 5.13%   |
| More than 3000 | 6         | 3.85%   |
| 51-100         | 6         | 3.85%   |
| 2001-3000      | 5         | 3.21%   |
| 21-50          | 4         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 43        | 26.54%  |
| 101-250        | 37        | 22.84%  |
| 21-50          | 21        | 12.96%  |
| 251-500        | 17        | 10.49%  |
| 51-100         | 16        | 9.88%   |
| Unknown        | 12        | 7.41%   |
| 1001-2000      | 7         | 4.32%   |
| 501-1000       | 5         | 3.09%   |
| More than 3000 | 3         | 1.85%   |
| 2001-3000      | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 6.67%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 6.67%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 3.33%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 3.33%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 3.33%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 3.33%   |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 3.33%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.33%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 3.33%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.33%   |
| Seagate ST3750330AS 752GB             | 1         | 1      | 3.33%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 3.33%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 2      | 3.33%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 3.33%   |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 3.33%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 3.33%   |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 3.33%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.33%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.33%   |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 14     | 41.38%  |
| WDC                 | 4         | 5      | 13.79%  |
| Samsung Electronics | 4         | 4      | 13.79%  |
| Hitachi             | 3         | 3      | 10.34%  |
| HGST                | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 3      | 6.9%    |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 14     | 44.44%  |
| WDC                 | 4         | 5      | 14.81%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| Hitachi             | 3         | 3      | 11.11%  |
| HGST                | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 31     | 92.86%  |
| SSD  | 2         | 2      | 7.14%   |

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
| Works    | 92        | 138    | 51.69%  |
| Detected | 59        | 102    | 33.15%  |
| Malfunc  | 27        | 33     | 15.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 83        | 44.15%  |
| AMD                              | 42        | 22.34%  |
| Samsung Electronics              | 26        | 13.83%  |
| SanDisk                          | 7         | 3.72%   |
| SK hynix                         | 5         | 2.66%   |
| Phison Electronics               | 5         | 2.66%   |
| Micron/Crucial Technology        | 3         | 1.6%    |
| Micron Technology                | 3         | 1.6%    |
| ASMedia Technology               | 3         | 1.6%    |
| ADATA Technology                 | 2         | 1.06%   |
| Toshiba America Info Systems     | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| Marvell Technology Group         | 1         | 0.53%   |
| LSI Logic / Symbios Logic        | 1         | 0.53%   |
| KIOXIA                           | 1         | 0.53%   |
| Kingston Technology Company      | 1         | 0.53%   |
| JMicron Technology               | 1         | 0.53%   |
| Broadcom                         | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 30        | 14.35%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 14        | 6.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 12        | 5.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 9         | 4.31%   |
| AMD 400 Series Chipset SATA Controller                                        | 8         | 3.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 5         | 2.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 5         | 2.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 4         | 1.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 4         | 1.91%   |
| Samsung NVMe SSD Controller 980                                               | 4         | 1.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 1.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 1.44%   |
| Intel SSD 660P Series                                                         | 3         | 1.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 3         | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 3         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3         | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3         | 1.44%   |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 1.44%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 2         | 0.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2         | 0.96%   |
| Phison E12 NVMe Controller                                                    | 2         | 0.96%   |
| Micron 2450 NVMe SSD (DRAM-less)                                              | 2         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 0.96%   |
| Intel SATA Controller [RAID mode]                                             | 2         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 0.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 2         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 2         | 0.96%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                        | 2         | 0.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 2         | 0.96%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 110       | 57.89%  |
| NVMe | 55        | 28.95%  |
| IDE  | 14        | 7.37%   |
| RAID | 11        | 5.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 63.16%  |
| AMD                      | 50        | 32.89%  |
| ARM                      | 4         | 2.63%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.66%   |
| PowerMac11,2             | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 2.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 1.97%   |
| ARM Processor                                      | 3         | 1.97%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 3         | 1.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 2         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 2         | 1.32%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.32%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 2         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 2         | 1.32%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 2         | 1.32%   |
| Intel Core i3-4030U CPU @ 1.90GHz                  | 2         | 1.32%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 2         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 2         | 1.32%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 2         | 1.32%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.32%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx      | 2         | 1.32%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.32%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.32%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.66%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.66%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.66%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.66%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.66%   |
| Intel Pentium CPU N3520 @ 2.16GHz                  | 1         | 0.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.66%   |
| Intel Pentium CPU 4425Y @ 1.70GHz                  | 1         | 0.66%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.66%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.66%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz                  | 1         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz                  | 1         | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz                  | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 17.76%  |
| Intel Core i7           | 22        | 14.47%  |
| Other                   | 17        | 11.18%  |
| AMD Ryzen 5             | 17        | 11.18%  |
| Intel Core i3           | 16        | 10.53%  |
| AMD Ryzen 7             | 11        | 7.24%   |
| Intel Celeron           | 6         | 3.95%   |
| Intel Atom              | 6         | 3.95%   |
| Intel Pentium           | 4         | 2.63%   |
| AMD FX                  | 3         | 1.97%   |
| Intel Core 2 Duo        | 2         | 1.32%   |
| AMD Ryzen 7 PRO         | 2         | 1.32%   |
| AMD Ryzen 3             | 2         | 1.32%   |
| AMD A8                  | 2         | 1.32%   |
| Intel Xeon              | 1         | 0.66%   |
| Intel Pentium Gold      | 1         | 0.66%   |
| Intel Pentium 4         | 1         | 0.66%   |
| Intel Genuine           | 1         | 0.66%   |
| Intel Core i9           | 1         | 0.66%   |
| AMD Turion 64 X2 Mobile | 1         | 0.66%   |
| AMD Ryzen Threadripper  | 1         | 0.66%   |
| AMD Ryzen 5 PRO         | 1         | 0.66%   |
| AMD Phenom II X4        | 1         | 0.66%   |
| AMD E2                  | 1         | 0.66%   |
| AMD E1                  | 1         | 0.66%   |
| AMD C-60                | 1         | 0.66%   |
| AMD Athlon II X3        | 1         | 0.66%   |
| AMD Athlon II X2        | 1         | 0.66%   |
| AMD A4                  | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 55        | 36.18%  |
| 2       | 52        | 34.21%  |
| 6       | 20        | 13.16%  |
| 8       | 13        | 8.55%   |
| 1       | 6         | 3.95%   |
| 14      | 2         | 1.32%   |
| 64      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |
| 3       | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 149       | 98.03%  |
| 2       | 2         | 1.32%   |
| Unknown | 1         | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 105       | 69.08%  |
| 1       | 45        | 29.61%  |
| 4       | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 90.79%  |
| Unknown        | 8         | 5.26%   |
| 64-bit         | 3         | 1.97%   |
| 32-bit         | 3         | 1.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 30.13%  |
| 0x40651    | 8         | 5.13%   |
| 0x306a9    | 7         | 4.49%   |
| 0x906e9    | 5         | 3.21%   |
| 0x906ea    | 4         | 2.56%   |
| 0x806ec    | 4         | 2.56%   |
| 0x806e9    | 4         | 2.56%   |
| 0x406e3    | 4         | 2.56%   |
| 0x08108102 | 4         | 2.56%   |
| 0x806ea    | 3         | 1.92%   |
| 0x30678    | 3         | 1.92%   |
| 0x206a7    | 3         | 1.92%   |
| 0x08600104 | 3         | 1.92%   |
| 0x906a3    | 2         | 1.28%   |
| 0x506e3    | 2         | 1.28%   |
| 0x106c2    | 2         | 1.28%   |
| 0x0a50000c | 2         | 1.28%   |
| 0x0a201009 | 2         | 1.28%   |
| 0x08701021 | 2         | 1.28%   |
| 0x0800820d | 2         | 1.28%   |
| 0x07030105 | 2         | 1.28%   |
| 0x06006705 | 2         | 1.28%   |
| 0x06000852 | 2         | 1.28%   |
| 0x05000119 | 2         | 1.28%   |
| 0x010000c8 | 2         | 1.28%   |
| 0xa0671    | 1         | 0.64%   |
| 0xa0652    | 1         | 0.64%   |
| 0x906ed    | 1         | 0.64%   |
| 0x90675    | 1         | 0.64%   |
| 0x90672    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x806c1    | 1         | 0.64%   |
| 0x706e5    | 1         | 0.64%   |
| 0x706a1    | 1         | 0.64%   |
| 0x406c4    | 1         | 0.64%   |
| 0x306d4    | 1         | 0.64%   |
| 0x306c3    | 1         | 0.64%   |
| 0x30673    | 1         | 0.64%   |
| 0x20652    | 1         | 0.64%   |
| 0x106ca    | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 21.05%  |
| Haswell          | 11        | 7.24%   |
| Zen 2            | 10        | 6.58%   |
| IvyBridge        | 10        | 6.58%   |
| Unknown          | 10        | 6.58%   |
| Zen+             | 8         | 5.26%   |
| Skylake          | 8         | 5.26%   |
| Zen 3            | 7         | 4.61%   |
| Silvermont       | 6         | 3.95%   |
| Zen              | 5         | 3.29%   |
| SandyBridge      | 4         | 2.63%   |
| Excavator        | 4         | 2.63%   |
| Alderlake Hybrid | 4         | 2.63%   |
| TigerLake        | 3         | 1.97%   |
| Puma             | 3         | 1.97%   |
| Piledriver       | 3         | 1.97%   |
| K10              | 3         | 1.97%   |
| IceLake          | 3         | 1.97%   |
| Bonnell          | 3         | 1.97%   |
| Penryn           | 2         | 1.32%   |
| Goldmont plus    | 2         | 1.32%   |
| Core             | 2         | 1.32%   |
| Broadwell        | 2         | 1.32%   |
| Bobcat           | 2         | 1.32%   |
| Westmere         | 1         | 0.66%   |
| NetBurst         | 1         | 0.66%   |
| Nehalem          | 1         | 0.66%   |
| K8 Hammer        | 1         | 0.66%   |
| CometLake        | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 42.78%  |
| Nvidia                           | 52        | 28.89%  |
| AMD                              | 48        | 26.67%  |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Matrox Electronics Systems       | 1         | 0.56%   |
| ASPEED Technology                | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 5.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 3.23%   |
| AMD Renoir                                                                | 6         | 3.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 5         | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 2.69%   |
| Intel UHD Graphics 620                                                    | 5         | 2.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 2.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 5         | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 2.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 4         | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 1.61%   |
| Intel HD Graphics 630                                                     | 3         | 1.61%   |
| Intel HD Graphics 620                                                     | 3         | 1.61%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                        | 3         | 1.61%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 1.08%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.08%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 2         | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                            | 2         | 1.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.08%   |
| Intel HD Graphics 5500                                                    | 2         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.08%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 1.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.08%   |
| AMD Lucienne                                                              | 2         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2         | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 33.55%  |
| 1 x AMD        | 41        | 26.45%  |
| 1 x Nvidia     | 25        | 16.13%  |
| Intel + Nvidia | 23        | 14.84%  |
| Other          | 4         | 2.58%   |
| AMD + Nvidia   | 3         | 1.94%   |
| 2 x AMD        | 2         | 1.29%   |
| 2 x Nvidia     | 1         | 0.65%   |
| 1 x SiS        | 1         | 0.65%   |
| 1 x Matrox     | 1         | 0.65%   |
| Intel + AMD    | 1         | 0.65%   |
| AMD + ASPEED   | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 69.68%  |
| Proprietary | 42        | 27.1%   |
| Unknown     | 5         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 56.6%   |
| 1.01-2.0   | 19        | 11.95%  |
| 3.01-4.0   | 15        | 9.43%   |
| 0.01-0.5   | 14        | 8.81%   |
| 0.51-1.0   | 8         | 5.03%   |
| 5.01-6.0   | 4         | 2.52%   |
| 7.01-8.0   | 3         | 1.89%   |
| 8.01-16.0  | 3         | 1.89%   |
| 2.01-3.0   | 2         | 1.26%   |
| 16.01-24.0 | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 22        | 13.75%  |
| AU Optronics         | 22        | 13.75%  |
| BOE                  | 18        | 11.25%  |
| LG Display           | 16        | 10%     |
| Samsung Electronics  | 13        | 8.13%   |
| Hewlett-Packard      | 9         | 5.63%   |
| Dell                 | 8         | 5%      |
| Acer                 | 5         | 3.13%   |
| Philips              | 4         | 2.5%    |
| Iiyama               | 4         | 2.5%    |
| Lenovo               | 3         | 1.88%   |
| Goldstar             | 3         | 1.88%   |
| BenQ                 | 3         | 1.88%   |
| AOC                  | 3         | 1.88%   |
| Sharp                | 2         | 1.25%   |
| PANDA                | 2         | 1.25%   |
| LG Philips           | 2         | 1.25%   |
| Fujitsu Siemens      | 2         | 1.25%   |
| ASUSTek Computer     | 2         | 1.25%   |
| Apple                | 2         | 1.25%   |
| Ancor Communications | 2         | 1.25%   |
| Unknown              | 1         | 0.63%   |
| TMX                  | 1         | 0.63%   |
| STD                  | 1         | 0.63%   |
| Sceptre Tech         | 1         | 0.63%   |
| Sceptre              | 1         | 0.63%   |
| Panasonic            | 1         | 0.63%   |
| ONN                  | 1         | 0.63%   |
| MSI                  | 1         | 0.63%   |
| InnoLux Display      | 1         | 0.63%   |
| Gigabyte Technology  | 1         | 0.63%   |
| FUN                  | 1         | 0.63%   |
| CHR                  | 1         | 0.63%   |
| BOE Technology Group | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.81%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.81%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 2         | 1.2%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.2%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.2%    |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.6%    |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.6%    |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                         | 1         | 0.6%    |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.6%    |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.6%    |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.6%    |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.6%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.6%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM029D 1360x768                      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.6%    |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.6%    |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.6%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 0.6%    |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.6%    |
| Philips 220CW PHLC024 1680x1050 474x296mm 22.0-inch                   | 1         | 0.6%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.6%    |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                | 1         | 0.6%    |
| MSI Optix MAG24C MSI1462 1920x1080 521x293mm 23.5-inch                | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 67        | 42.95%  |
| 1366x768 (WXGA)    | 32        | 20.51%  |
| 2560x1440 (QHD)    | 7         | 4.49%   |
| 1920x1200 (WUXGA)  | 7         | 4.49%   |
| 3840x2160 (4K)     | 6         | 3.85%   |
| 1680x1050 (WSXGA+) | 4         | 2.56%   |
| 1600x900 (HD+)     | 4         | 2.56%   |
| 3440x1440          | 3         | 1.92%   |
| 2160x1440          | 3         | 1.92%   |
| 1280x800 (WXGA)    | 3         | 1.92%   |
| Unknown            | 3         | 1.92%   |
| 2560x1600          | 2         | 1.28%   |
| 1280x1024 (SXGA)   | 2         | 1.28%   |
| 1024x600           | 2         | 1.28%   |
| 7680x1080          | 1         | 0.64%   |
| 3840x1600          | 1         | 0.64%   |
| 3840x1080          | 1         | 0.64%   |
| 3200x2000          | 1         | 0.64%   |
| 2880x1800          | 1         | 0.64%   |
| 2560x1080          | 1         | 0.64%   |
| 2288x1287          | 1         | 0.64%   |
| 2256x1504          | 1         | 0.64%   |
| 1920x1280          | 1         | 0.64%   |
| 1360x768           | 1         | 0.64%   |
| 1280x720 (HD)      | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 42        | 26.09%  |
| 14      | 18        | 11.18%  |
| 24      | 15        | 9.32%   |
| 13      | 15        | 9.32%   |
| Unknown | 13        | 8.07%   |
| 27      | 8         | 4.97%   |
| 23      | 7         | 4.35%   |
| 21      | 7         | 4.35%   |
| 17      | 5         | 3.11%   |
| 22      | 4         | 2.48%   |
| 12      | 4         | 2.48%   |
| 34      | 3         | 1.86%   |
| 11      | 3         | 1.86%   |
| 10      | 3         | 1.86%   |
| 16      | 2         | 1.24%   |
| 84      | 1         | 0.62%   |
| 40      | 1         | 0.62%   |
| 39      | 1         | 0.62%   |
| 37      | 1         | 0.62%   |
| 33      | 1         | 0.62%   |
| 31      | 1         | 0.62%   |
| 28      | 1         | 0.62%   |
| 25      | 1         | 0.62%   |
| 20      | 1         | 0.62%   |
| 19      | 1         | 0.62%   |
| 18      | 1         | 0.62%   |
| 8       | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 42.5%   |
| 501-600     | 29        | 18.13%  |
| 201-300     | 20        | 12.5%   |
| 401-500     | 13        | 8.13%   |
| Unknown     | 13        | 8.13%   |
| 351-400     | 5         | 3.13%   |
| 701-800     | 4         | 2.5%    |
| 801-900     | 3         | 1.88%   |
| 601-700     | 3         | 1.88%   |
| 1501-2000   | 1         | 0.63%   |
| 101-200     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 106       | 70.67%  |
| 16/10   | 19        | 12.67%  |
| Unknown | 12        | 8%      |
| 3/2     | 6         | 4%      |
| 21/9    | 5         | 3.33%   |
| 5/4     | 2         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 25.63%  |
| 81-90          | 25        | 15.63%  |
| 201-250        | 24        | 15%     |
| Unknown        | 13        | 8.13%   |
| 251-300        | 10        | 6.25%   |
| 301-350        | 8         | 5%      |
| 71-80          | 7         | 4.38%   |
| 351-500        | 5         | 3.13%   |
| 61-70          | 4         | 2.5%    |
| 51-60          | 4         | 2.5%    |
| 121-130        | 3         | 1.88%   |
| 111-120        | 3         | 1.88%   |
| 501-1000       | 3         | 1.88%   |
| 41-50          | 2         | 1.25%   |
| 151-200        | 2         | 1.25%   |
| 141-150        | 2         | 1.25%   |
| More than 1000 | 1         | 0.63%   |
| 1-40           | 1         | 0.63%   |
| 131-140        | 1         | 0.63%   |
| 91-100         | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 27.78%  |
| 51-100        | 45        | 27.78%  |
| 101-120       | 41        | 25.31%  |
| 161-240       | 16        | 9.88%   |
| Unknown       | 13        | 8.02%   |
| More than 240 | 2         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 126       | 81.82%  |
| 2     | 25        | 16.23%  |
| 0     | 3         | 1.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 83        | 38.07%  |
| Intel                            | 64        | 29.36%  |
| Qualcomm Atheros                 | 21        | 9.63%   |
| Broadcom                         | 14        | 6.42%   |
| Ralink Technology                | 4         | 1.83%   |
| Xiaomi                           | 3         | 1.38%   |
| TP-Link                          | 3         | 1.38%   |
| Sierra Wireless                  | 3         | 1.38%   |
| Broadcom Limited                 | 3         | 1.38%   |
| Qualcomm Atheros Communications  | 2         | 0.92%   |
| MediaTek                         | 2         | 0.92%   |
| Cypress Semiconductor            | 2         | 0.92%   |
| STMicroelectronics               | 1         | 0.46%   |
| Standard Microsystems            | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Realtek                          | 1         | 0.46%   |
| Ralink                           | 1         | 0.46%   |
| Qualcomm                         | 1         | 0.46%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.46%   |
| Nvidia                           | 1         | 0.46%   |
| Marvell Technology Group         | 1         | 0.46%   |
| DisplayLink                      | 1         | 0.46%   |
| ASUSTek Computer                 | 1         | 0.46%   |
| ASIX Electronics                 | 1         | 0.46%   |
| Arduino SA                       | 1         | 0.46%   |
| Apple                            | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 21.34%  |
| Intel Wi-Fi 6 AX200                                               | 12        | 4.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.35%   |
| Intel Wireless 8265 / 8275                                        | 8         | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.98%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.58%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.19%   |
| Intel Wireless 8260                                               | 3         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.79%   |
| Intel Wireless 7265                                               | 2         | 0.79%   |
| Intel Wireless 7260                                               | 2         | 0.79%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.79%   |
| Cypress K38231_03                                                 | 2         | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.79%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 42.5%   |
| Realtek Semiconductor           | 24        | 20%     |
| Qualcomm Atheros                | 18        | 15%     |
| Broadcom                        | 8         | 6.67%   |
| Ralink Technology               | 4         | 3.33%   |
| Sierra Wireless                 | 3         | 2.5%    |
| Broadcom Limited                | 3         | 2.5%    |
| TP-Link                         | 2         | 1.67%   |
| Qualcomm Atheros Communications | 2         | 1.67%   |
| Realtek                         | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Qualcomm                        | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| ASUSTek Computer                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                         | 12        | 10%     |
| Intel Wireless 8265 / 8275                                  | 8         | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 6         | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 5         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 5         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 4         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 4         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 4         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                               | 4         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 3         | 2.5%    |
| Realtek RTL8723DE Wireless Network Adapter                  | 3         | 2.5%    |
| Ralink MT7601U Wireless Adapter                             | 3         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 3         | 2.5%    |
| Intel Wireless 8260                                         | 3         | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 3         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 2         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                             | 2         | 1.67%   |
| Intel Wireless 7265                                         | 2         | 1.67%   |
| Intel Wireless 7260                                         | 2         | 1.67%   |
| Intel Wi-Fi 6 AX201                                         | 2         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 2         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 2         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                    | 2         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                            | 2         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 2         | 1.67%   |
| Broadcom BCM4311 802.11b/g WLAN                             | 2         | 1.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                | 1         | 0.83%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1         | 0.83%   |
| Sierra Wireless EM7455                                      | 1         | 0.83%   |
| Sierra Wireless EM7345 4G LTE                               | 1         | 0.83%   |
| Sierra Wireless EM7305 Modem                                | 1         | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                  | 1         | 0.83%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter    | 1         | 0.83%   |
| Realtek 802.11n NIC                                         | 1         | 0.83%   |
| Ralink RT5572 Wireless Adapter                              | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                   | 1         | 0.83%   |
| Qualcomm QCNFA765 Wireless Network Adapter                  | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 75        | 57.69%  |
| Intel                            | 30        | 23.08%  |
| Broadcom                         | 7         | 5.38%   |
| Qualcomm Atheros                 | 4         | 3.08%   |
| Xiaomi                           | 3         | 2.31%   |
| Cypress Semiconductor            | 2         | 1.54%   |
| TP-Link                          | 1         | 0.77%   |
| Standard Microsystems            | 1         | 0.77%   |
| Silicon Integrated Systems [SiS] | 1         | 0.77%   |
| Nvidia                           | 1         | 0.77%   |
| MediaTek                         | 1         | 0.77%   |
| Marvell Technology Group         | 1         | 0.77%   |
| DisplayLink                      | 1         | 0.77%   |
| ASIX Electronics                 | 1         | 0.77%   |
| Apple                            | 1         | 0.77%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 41.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 8.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.08%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 3.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.54%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.54%   |
| Cypress K38231_03                                                 | 2         | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.77%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.77%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.77%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.77%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.77%   |
| MediaTek Armor X10 Pro                                            | 1         | 0.77%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.77%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.77%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.77%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.77%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.77%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 1         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 51.05%  |
| WiFi     | 113       | 47.68%  |
| Modem    | 2         | 0.84%   |
| Unknown  | 1         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 60.93%  |
| Ethernet | 59        | 39.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 47.37%  |
| 2     | 67        | 44.08%  |
| 0     | 7         | 4.61%   |
| 3     | 5         | 3.29%   |
| 4     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 85.71%  |
| Yes  | 22        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 44%     |
| Realtek Semiconductor           | 15        | 15%     |
| Broadcom                        | 8         | 8%      |
| Lite-On Technology              | 7         | 7%      |
| Cambridge Silicon Radio         | 7         | 7%      |
| Qualcomm Atheros Communications | 4         | 4%      |
| IMC Networks                    | 3         | 3%      |
| Foxconn / Hon Hai               | 3         | 3%      |
| Realtek                         | 2         | 2%      |
| USI                             | 1         | 1%      |
| Opticis                         | 1         | 1%      |
| Foxconn International           | 1         | 1%      |
| Dell                            | 1         | 1%      |
| ASUSTek Computer                | 1         | 1%      |
| Apple                           | 1         | 1%      |
| Actions                         | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 14%     |
| Intel AX200 Bluetooth                               | 12        | 12%     |
| Realtek Bluetooth Radio                             | 8         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 7%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6%      |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5%      |
| Intel AX201 Bluetooth                               | 4         | 4%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3%      |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 3%      |
| Intel AX210 Bluetooth                               | 3         | 3%      |
| Realtek Bluetooth Radio                             | 2         | 2%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2%      |
| Intel Bluetooth Device                              | 2         | 2%      |
| IMC Networks Bluetooth Radio                        | 2         | 2%      |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 2%      |
| USI Bluetooth Device                                | 1         | 1%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1%      |
| Realtek RTL8723B Bluetooth                          | 1         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1%      |
| Opticis Bluetooth Radio                             | 1         | 1%      |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1%      |
| IMC Networks Bluetooth Device                       | 1         | 1%      |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1%      |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1%      |
| Dell Wireless 365 Bluetooth                         | 1         | 1%      |
| Broadcom HP Portable Valentine                      | 1         | 1%      |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1%      |
| Broadcom BCM2045 Bluetooth                          | 1         | 1%      |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1%      |
| Apple Bluetooth Host Controller                     | 1         | 1%      |
| Actions general adapter                             | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 44.39%  |
| AMD                              | 53        | 25.85%  |
| Nvidia                           | 33        | 16.1%   |
| C-Media Electronics              | 5         | 2.44%   |
| Logitech                         | 4         | 1.95%   |
| JMTek                            | 4         | 1.95%   |
| Texas Instruments                | 2         | 0.98%   |
| Creative Technology              | 2         | 0.98%   |
| VIA Technologies                 | 1         | 0.49%   |
| SteelSeries ApS                  | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| SAVITECH                         | 1         | 0.49%   |
| Fry's Electronics                | 1         | 0.49%   |
| Focusrite-Novation               | 1         | 0.49%   |
| Elgato Systems                   | 1         | 0.49%   |
| EDFIER                           | 1         | 0.49%   |
| Corsair                          | 1         | 0.49%   |
| Cambridge Audio                  | 1         | 0.49%   |
| ASRock                           | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 6.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 5.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.88%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 3.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.94%   |
| JMTek USB PnP Audio Device                                                 | 4         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 1.55%   |
| AMD High Definition Audio Controller                                       | 4         | 1.55%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.16%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.78%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 30        | 25.21%  |
| Samsung Electronics | 28        | 23.53%  |
| Micron Technology   | 11        | 9.24%   |
| Kingston            | 11        | 9.24%   |
| Unknown             | 8         | 6.72%   |
| G.Skill             | 7         | 5.88%   |
| Corsair             | 6         | 5.04%   |
| A-DATA Technology   | 6         | 5.04%   |
| Crucial             | 4         | 3.36%   |
| Ramaxel Technology  | 3         | 2.52%   |
| Transcend           | 1         | 0.84%   |
| Patriot             | 1         | 0.84%   |
| Elpida              | 1         | 0.84%   |
| Avant               | 1         | 0.84%   |
| 48spaces            | 1         | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.53%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.53%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 2         | 1.53%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 2         | 1.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s    | 2         | 1.53%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                   | 1         | 0.76%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s            | 1         | 0.76%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 0.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1         | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s              | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2                          | 1         | 0.76%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 0.76%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 0.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 0.76%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1         | 0.76%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.76%   |
| SK hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.76%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 0.76%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 53        | 49.07%  |
| DDR3    | 39        | 36.11%  |
| LPDDR3  | 4         | 3.7%    |
| LPDDR5  | 3         | 2.78%   |
| LPDDR4  | 3         | 2.78%   |
| DDR2    | 3         | 2.78%   |
| Unknown | 2         | 1.85%   |
| DDR5    | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 61.68%  |
| DIMM         | 32        | 29.91%  |
| Row Of Chips | 9         | 8.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 51        | 43.59%  |
| 4096  | 39        | 33.33%  |
| 16384 | 13        | 11.11%  |
| 2048  | 9         | 7.69%   |
| 1024  | 3         | 2.56%   |
| 512   | 2         | 1.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 23.08%  |
| 2667    | 20        | 17.09%  |
| 3200    | 16        | 13.68%  |
| 2400    | 9         | 7.69%   |
| 1333    | 9         | 7.69%   |
| 1334    | 5         | 4.27%   |
| 3600    | 4         | 3.42%   |
| 2133    | 4         | 3.42%   |
| 6400    | 3         | 2.56%   |
| 1867    | 3         | 2.56%   |
| 3866    | 2         | 1.71%   |
| 3000    | 2         | 1.71%   |
| 533     | 2         | 1.71%   |
| 4800    | 1         | 0.85%   |
| 4266    | 1         | 0.85%   |
| 3733    | 1         | 0.85%   |
| 3534    | 1         | 0.85%   |
| 3333    | 1         | 0.85%   |
| 3266    | 1         | 0.85%   |
| 2933    | 1         | 0.85%   |
| 2800    | 1         | 0.85%   |
| 1067    | 1         | 0.85%   |
| 667     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

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
| Chicony Electronics                    | 31        | 29.52%  |
| IMC Networks                           | 16        | 15.24%  |
| Microdia                               | 11        | 10.48%  |
| Bison Electronics                      | 8         | 7.62%   |
| Realtek Semiconductor                  | 7         | 6.67%   |
| Logitech                               | 7         | 6.67%   |
| Quanta                                 | 6         | 5.71%   |
| Sunplus Innovation Technology          | 4         | 3.81%   |
| Suyin                                  | 3         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.86%   |
| Syntek                                 | 2         | 1.9%    |
| MacroSilicon                           | 2         | 1.9%    |
| SunplusIT                              | 1         | 0.95%   |
| Silicon Motion                         | 1         | 0.95%   |
| Microsoft                              | 1         | 0.95%   |
| Intel                                  | 1         | 0.95%   |
| GEMBIRD                                | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 10        | 9.35%   |
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 5.61%   |
| Suyin HP Truevision HD                        | 3         | 2.8%    |
| Quanta HD User Facing                         | 3         | 2.8%    |
| Microdia Integrated_Webcam_HD                 | 3         | 2.8%    |
| Logitech Webcam C270                          | 3         | 2.8%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 2.8%    |
| Syntek Integrated Camera                      | 2         | 1.87%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.87%   |
| Realtek USB Camera                            | 2         | 1.87%   |
| Microdia HP Integrated Webcam                 | 2         | 1.87%   |
| IMC Networks Integrated Camera                | 2         | 1.87%   |
| IMC Networks HD Camera                        | 2         | 1.87%   |
| Chicony USB 2.0 Camera                        | 2         | 1.87%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.87%   |
| Chicony HP TrueVision HD Camera               | 2         | 1.87%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.87%   |
| Chicony HD WebCam                             | 2         | 1.87%   |
| Chicony EasyCamera                            | 2         | 1.87%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.87%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.87%   |
| Bison Lenovo EasyCamera                       | 2         | 1.87%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.93%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.93%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.93%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.93%   |
| Realtek Laptop Camera                         | 1         | 0.93%   |
| Realtek Integrated Webcam HD                  | 1         | 0.93%   |
| Realtek HD WebCam                             | 1         | 0.93%   |
| Realtek FULL HD 1080P Webcam                  | 1         | 0.93%   |
| Quanta VGA WebCam                             | 1         | 0.93%   |
| Quanta HP Webcam                              | 1         | 0.93%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.93%   |
| Microsoft LifeCam HD-3000                     | 1         | 0.93%   |
| Microdia Webcam Vitade AF                     | 1         | 0.93%   |
| Microdia Webcam                               | 1         | 0.93%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 0.93%   |
| Microdia REDRAGON Live Camera Audio           | 1         | 0.93%   |
| Microdia Integrated_Webcam_2M                 | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 46.15%  |
| Validity Sensors           | 3         | 23.08%  |
| Shenzhen Goodix Technology | 3         | 23.08%  |
| Upek                       | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 30.77%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 23.08%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 15.38%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics  WBDI                                        | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Lenovo      | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 120       | 78.43%  |
| 1     | 24        | 15.69%  |
| 2     | 7         | 4.58%   |
| 3     | 2         | 1.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 30.95%  |
| Net/wireless             | 6         | 14.29%  |
| Graphics card            | 6         | 14.29%  |
| Chipcard                 | 5         | 11.9%   |
| Camera                   | 4         | 9.52%   |
| Sound                    | 3         | 7.14%   |
| Multimedia controller    | 3         | 7.14%   |
| Net/ethernet             | 1         | 2.38%   |
| Communication controller | 1         | 2.38%   |

