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

Total: 218

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Acer          | One S1003                   | Tablet      | [dd8e16ad67](https://linux-hardware.org/?probe=dd8e16ad67) | Sep 25, 2023 |
| Acer          | One S1003                   | Tablet      | [02c8574cb0](https://linux-hardware.org/?probe=02c8574cb0) | Sep 25, 2023 |
| HP            | 15                          | Notebook    | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 116       | 69.05%  |
| Void Linux         | 52        | 30.95%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 165       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 8         | 4.47%   |
| 5.13.19_1 | 7         | 3.91%   |
| 6.3.12_1  | 5         | 2.79%   |
| 5.8.18_1  | 5         | 2.79%   |
| 6.1.4_1   | 4         | 2.23%   |
| 6.1.31_1  | 4         | 2.23%   |
| 5.3.9_1   | 4         | 2.23%   |
| 5.18.19_1 | 4         | 2.23%   |
| 5.16.20_1 | 4         | 2.23%   |
| 5.10.17_1 | 4         | 2.23%   |
| 5.8.12_1  | 3         | 1.68%   |
| 5.19.17_1 | 3         | 1.68%   |
| 5.18.14_1 | 3         | 1.68%   |
| 5.15.32_1 | 3         | 1.68%   |
| 5.13.13_1 | 3         | 1.68%   |
| 5.12.10_1 | 3         | 1.68%   |
| 6.1.21_1  | 2         | 1.12%   |
| 6.1.10_1  | 2         | 1.12%   |
| 6.0.15_1  | 2         | 1.12%   |
| 6.0.13_1  | 2         | 1.12%   |
| 5.9.14_1  | 2         | 1.12%   |
| 5.4.24_1  | 2         | 1.12%   |
| 5.4.13_2  | 2         | 1.12%   |
| 5.19.16_1 | 2         | 1.12%   |
| 5.18.9_1  | 2         | 1.12%   |
| 5.15.41_1 | 2         | 1.12%   |
| 5.15.34_1 | 2         | 1.12%   |
| 5.15.22_1 | 2         | 1.12%   |
| 5.15.16_1 | 2         | 1.12%   |
| 5.13.15_1 | 2         | 1.12%   |
| 5.13.10_1 | 2         | 1.12%   |
| 5.12.14_1 | 2         | 1.12%   |
| 5.11.9_1  | 2         | 1.12%   |
| 5.10.14_1 | 2         | 1.12%   |
| 6.4.8_1   | 1         | 0.56%   |
| 6.2.8_1   | 1         | 0.56%   |
| 6.2.11_1  | 1         | 0.56%   |
| 6.1.9_1   | 1         | 0.56%   |
| 6.1.7_1   | 1         | 0.56%   |
| 6.1.3_1   | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 8         | 4.47%   |
| 5.13.19 | 7         | 3.91%   |
| 6.3.12  | 5         | 2.79%   |
| 5.8.18  | 5         | 2.79%   |
| 6.1.4   | 4         | 2.23%   |
| 6.1.31  | 4         | 2.23%   |
| 5.8.12  | 4         | 2.23%   |
| 5.3.9   | 4         | 2.23%   |
| 5.18.19 | 4         | 2.23%   |
| 5.16.20 | 4         | 2.23%   |
| 5.10.17 | 4         | 2.23%   |
| 5.19.17 | 3         | 1.68%   |
| 5.18.14 | 3         | 1.68%   |
| 5.15.32 | 3         | 1.68%   |
| 5.13.13 | 3         | 1.68%   |
| 5.12.10 | 3         | 1.68%   |
| 6.1.21  | 2         | 1.12%   |
| 6.1.10  | 2         | 1.12%   |
| 6.0.15  | 2         | 1.12%   |
| 6.0.13  | 2         | 1.12%   |
| 5.9.14  | 2         | 1.12%   |
| 5.4.24  | 2         | 1.12%   |
| 5.4.13  | 2         | 1.12%   |
| 5.19.16 | 2         | 1.12%   |
| 5.18.9  | 2         | 1.12%   |
| 5.15.41 | 2         | 1.12%   |
| 5.15.34 | 2         | 1.12%   |
| 5.15.22 | 2         | 1.12%   |
| 5.15.16 | 2         | 1.12%   |
| 5.13.15 | 2         | 1.12%   |
| 5.13.10 | 2         | 1.12%   |
| 5.12.14 | 2         | 1.12%   |
| 5.11.9  | 2         | 1.12%   |
| 5.10.14 | 2         | 1.12%   |
| 6.4.8   | 1         | 0.56%   |
| 6.2.8   | 1         | 0.56%   |
| 6.2.11  | 1         | 0.56%   |
| 6.1.9   | 1         | 0.56%   |
| 6.1.7   | 1         | 0.56%   |
| 6.1.3   | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 13.56%  |
| 6.1     | 19        | 10.73%  |
| 5.8     | 18        | 10.17%  |
| 5.13    | 16        | 9.04%   |
| 5.10    | 15        | 8.47%   |
| 6.3     | 13        | 7.34%   |
| 5.18    | 12        | 6.78%   |
| 5.12    | 9         | 5.08%   |
| 5.4     | 7         | 3.95%   |
| 6.0     | 6         | 3.39%   |
| 5.3     | 5         | 2.82%   |
| 5.19    | 5         | 2.82%   |
| 5.11    | 5         | 2.82%   |
| 5.9     | 4         | 2.26%   |
| 5.16    | 4         | 2.26%   |
| 4.19    | 4         | 2.26%   |
| 6.2     | 2         | 1.13%   |
| 6.4     | 1         | 0.56%   |
| 5.7     | 1         | 0.56%   |
| 5.6     | 1         | 0.56%   |
| 5.2     | 1         | 0.56%   |
| 5.17    | 1         | 0.56%   |
| 5.14    | 1         | 0.56%   |
| 5.1     | 1         | 0.56%   |
| 4.4     | 1         | 0.56%   |
| 4.14    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 154       | 93.33%  |
| i686    | 5         | 3.03%   |
| aarch64 | 3         | 1.82%   |
| ppc64le | 1         | 0.61%   |
| ppc64   | 1         | 0.61%   |
| armv7l  | 1         | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 72        | 42.11%  |
| XFCE         | 23        | 13.45%  |
| KDE          | 12        | 7.02%   |
| KDE5         | 11        | 6.43%   |
| GNOME        | 10        | 5.85%   |
| MATE         | 9         | 5.26%   |
| X-Cinnamon   | 6         | 3.51%   |
| i3           | 6         | 3.51%   |
| sway         | 4         | 2.34%   |
| bspwm        | 4         | 2.34%   |
| awesome      | 4         | 2.34%   |
| openbox      | 3         | 1.75%   |
| Lumina       | 2         | 1.17%   |
| river        | 1         | 0.58%   |
| LXQt         | 1         | 0.58%   |
| LXDE         | 1         | 0.58%   |
| dwm          | 1         | 0.58%   |
| dot-xsession | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 119       | 70.41%  |
| Wayland | 20        | 11.83%  |
| Tty     | 17        | 10.06%  |
| Unknown | 13        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 131       | 77.51%  |
| LightDM | 16        | 9.47%   |
| SDDM    | 9         | 5.33%   |
| LXDM    | 8         | 4.73%   |
| GDM     | 3         | 1.78%   |
| SLiM    | 1         | 0.59%   |
| LDM     | 1         | 0.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 86        | 50.29%  |
| Unknown | 22        | 12.87%  |
| en_GB   | 11        | 6.43%   |
| en_DK   | 6         | 3.51%   |
| ru_RU   | 5         | 2.92%   |
| de_DE   | 5         | 2.92%   |
| it_IT   | 4         | 2.34%   |
| fr_FR   | 4         | 2.34%   |
| es_ES   | 4         | 2.34%   |
| cs_CZ   | 3         | 1.75%   |
| pt_BR   | 2         | 1.17%   |
| pl_PL   | 2         | 1.17%   |
| en_CA   | 2         | 1.17%   |
| en_AU   | 2         | 1.17%   |
| el_GR   | 2         | 1.17%   |
| tr_TR   | 1         | 0.58%   |
| ru_UA   | 1         | 0.58%   |
| nb_NO   | 1         | 0.58%   |
| es_HN   | 1         | 0.58%   |
| es_DO   | 1         | 0.58%   |
| es_AR   | 1         | 0.58%   |
| en_NZ   | 1         | 0.58%   |
| en_IE   | 1         | 0.58%   |
| ca_ES   | 1         | 0.58%   |
| C       | 1         | 0.58%   |
| bg_BG   | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 91        | 53.85%  |
| BIOS | 78        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 105       | 62.13%  |
| Btrfs   | 37        | 21.89%  |
| Zfs     | 9         | 5.33%   |
| Xfs     | 9         | 5.33%   |
| Unknown | 6         | 3.55%   |
| F2fs    | 2         | 1.18%   |
| Ext3    | 1         | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 98        | 57.99%  |
| Unknown | 50        | 29.59%  |
| MBR     | 21        | 12.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 87.27%  |
| Yes       | 21        | 12.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 130       | 77.38%  |
| Yes       | 38        | 22.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 35        | 21.21%  |
| Lenovo                  | 30        | 18.18%  |
| Hewlett-Packard         | 20        | 12.12%  |
| Acer                    | 16        | 9.7%    |
| Dell                    | 14        | 8.48%   |
| MSI                     | 12        | 7.27%   |
| ASRock                  | 8         | 4.85%   |
| Gigabyte Technology     | 6         | 3.64%   |
| Unknown                 | 5         | 3.03%   |
| Notebook                | 2         | 1.21%   |
| Microsoft               | 2         | 1.21%   |
| HUAWEI                  | 2         | 1.21%   |
| Timi                    | 1         | 0.61%   |
| Samsung Electronics     | 1         | 0.61%   |
| Raspberry Pi Foundation | 1         | 0.61%   |
| Positivo                | 1         | 0.61%   |
| Pine Microsystems       | 1         | 0.61%   |
| Nokia                   | 1         | 0.61%   |
| Getac                   | 1         | 0.61%   |
| Framework               | 1         | 0.61%   |
| Exo                     | 1         | 0.61%   |
| Digibras                | 1         | 0.61%   |
| Cisco Systems           | 1         | 0.61%   |
| Chuwi                   | 1         | 0.61%   |
| Apple                   | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 5         | 3.03%   |
| HP Laptop 15-bw0xx                        | 2         | 1.21%   |
| HP 15                                     | 2         | 1.21%   |
| Dell OptiPlex 7010                        | 2         | 1.21%   |
| ASUS X751LD                               | 2         | 1.21%   |
| ASUS PRIME Z390-P                         | 2         | 1.21%   |
| Acer Swift SF314-42                       | 2         | 1.21%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.61%   |
| Samsung 275E4E/275E5E                     | 1         | 0.61%   |
| RPi Raspberry Pi                          | 1         | 0.61%   |
| Positivo Mobile                           | 1         | 0.61%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.61%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.61%   |
| Notebook NH50_70RA                        | 1         | 0.61%   |
| Nokia Booklet 3G                          | 1         | 0.61%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.61%   |
| MSI MS-7D14                               | 1         | 0.61%   |
| MSI MS-7C92                               | 1         | 0.61%   |
| MSI MS-7C52                               | 1         | 0.61%   |
| MSI MS-7C35                               | 1         | 0.61%   |
| MSI MS-7C02                               | 1         | 0.61%   |
| MSI MS-7B86                               | 1         | 0.61%   |
| MSI MS-7A68                               | 1         | 0.61%   |
| MSI MS-7A39                               | 1         | 0.61%   |
| MSI MS-7816                               | 1         | 0.61%   |
| MSI GV72 7RE                              | 1         | 0.61%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.61%   |
| Microsoft Surface with Windows RT         | 1         | 0.61%   |
| Microsoft Surface Go 2                    | 1         | 0.61%   |
| Lenovo Yoga 720-15IKB 80X7                | 1         | 0.61%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.61%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.61%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.61%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS    | 1         | 0.61%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.61%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.61%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.61%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 17        | 10.3%   |
| Acer Aspire              | 9         | 5.45%   |
| Lenovo IdeaPad           | 8         | 4.85%   |
| ASUS VivoBook            | 7         | 4.24%   |
| ASUS PRIME               | 7         | 4.24%   |
| HP Laptop                | 5         | 3.03%   |
| Unknown                  | 5         | 3.03%   |
| Dell OptiPlex            | 4         | 2.42%   |
| Dell Inspiron            | 4         | 2.42%   |
| HP Pavilion              | 3         | 1.82%   |
| Dell Latitude            | 3         | 1.82%   |
| Microsoft Surface        | 2         | 1.21%   |
| HP Stream                | 2         | 1.21%   |
| HP ENVY                  | 2         | 1.21%   |
| HP 255                   | 2         | 1.21%   |
| HP 15                    | 2         | 1.21%   |
| ASUS X751LD              | 2         | 1.21%   |
| ASUS TUF                 | 2         | 1.21%   |
| ASUS ROG                 | 2         | 1.21%   |
| Acer Swift               | 2         | 1.21%   |
| Timi Redmi               | 1         | 0.61%   |
| Samsung 275E4E           | 1         | 0.61%   |
| RPi Raspberry            | 1         | 0.61%   |
| Positivo Mobile          | 1         | 0.61%   |
| Pine Microsystems Pine64 | 1         | 0.61%   |
| Notebook NV4XMB          | 1         | 0.61%   |
| Notebook NH50            | 1         | 0.61%   |
| Nokia Booklet            | 1         | 0.61%   |
| MSI Summit               | 1         | 0.61%   |
| MSI MS-7D14              | 1         | 0.61%   |
| MSI MS-7C92              | 1         | 0.61%   |
| MSI MS-7C52              | 1         | 0.61%   |
| MSI MS-7C35              | 1         | 0.61%   |
| MSI MS-7C02              | 1         | 0.61%   |
| MSI MS-7B86              | 1         | 0.61%   |
| MSI MS-7A68              | 1         | 0.61%   |
| MSI MS-7A39              | 1         | 0.61%   |
| MSI MS-7816              | 1         | 0.61%   |
| MSI GV72                 | 1         | 0.61%   |
| MSI Bravo                | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 26        | 15.76%  |
| 2018    | 19        | 11.52%  |
| 2020    | 18        | 10.91%  |
| 2013    | 14        | 8.48%   |
| 2017    | 13        | 7.88%   |
| 2016    | 10        | 6.06%   |
| 2014    | 10        | 6.06%   |
| 2012    | 9         | 5.45%   |
| 2022    | 8         | 4.85%   |
| 2021    | 8         | 4.85%   |
| 2015    | 7         | 4.24%   |
| 2011    | 6         | 3.64%   |
| 2010    | 5         | 3.03%   |
| Unknown | 5         | 3.03%   |
| 2009    | 2         | 1.21%   |
| 2008    | 2         | 1.21%   |
| 2007    | 1         | 0.61%   |
| 2006    | 1         | 0.61%   |
| 2005    | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 103       | 62.42%  |
| Desktop        | 51        | 30.91%  |
| Tablet         | 4         | 2.42%   |
| Convertible    | 4         | 2.42%   |
| System on chip | 1         | 0.61%   |
| Mini pc        | 1         | 0.61%   |
| Server         | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 165       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 165       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 38        | 22.75%  |
| 4.01-8.0        | 35        | 20.96%  |
| 8.01-16.0       | 29        | 17.37%  |
| 3.01-4.0        | 27        | 16.17%  |
| 32.01-64.0      | 17        | 10.18%  |
| 1.01-2.0        | 8         | 4.79%   |
| 24.01-32.0      | 4         | 2.4%    |
| 0.51-1.0        | 4         | 2.4%    |
| 64.01-256.0     | 2         | 1.2%    |
| More than 256.0 | 1         | 0.6%    |
| 2.01-3.0        | 1         | 0.6%    |
| 0.01-0.5        | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 53        | 30.11%  |
| 2.01-3.0    | 39        | 22.16%  |
| 0.51-1.0    | 24        | 13.64%  |
| 4.01-8.0    | 20        | 11.36%  |
| 3.01-4.0    | 19        | 10.8%   |
| 8.01-16.0   | 10        | 5.68%   |
| 0.01-0.5    | 7         | 3.98%   |
| 16.01-24.0  | 3         | 1.7%    |
| 64.01-256.0 | 1         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 61.68%  |
| 2      | 37        | 22.16%  |
| 3      | 18        | 10.78%  |
| 4      | 4         | 2.4%    |
| 5      | 3         | 1.8%    |
| 9      | 1         | 0.6%    |
| 0      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 79.39%  |
| Yes       | 34        | 20.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 79.52%  |
| No        | 34        | 20.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 72.89%  |
| No        | 45        | 27.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 63.25%  |
| No        | 61        | 36.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 30        | 18.18%  |
| Russia             | 15        | 9.09%   |
| Germany            | 15        | 9.09%   |
| India              | 10        | 6.06%   |
| Brazil             | 7         | 4.24%   |
| Czechia            | 6         | 3.64%   |
| UK                 | 5         | 3.03%   |
| Poland             | 5         | 3.03%   |
| France             | 5         | 3.03%   |
| Denmark            | 5         | 3.03%   |
| Ukraine            | 4         | 2.42%   |
| Switzerland        | 4         | 2.42%   |
| Netherlands        | 4         | 2.42%   |
| Greece             | 4         | 2.42%   |
| Turkey             | 3         | 1.82%   |
| Spain              | 3         | 1.82%   |
| Italy              | 3         | 1.82%   |
| Bulgaria           | 3         | 1.82%   |
| Australia          | 3         | 1.82%   |
| Argentina          | 3         | 1.82%   |
| Serbia             | 2         | 1.21%   |
| Morocco            | 2         | 1.21%   |
| Finland            | 2         | 1.21%   |
| Canada             | 2         | 1.21%   |
| Vietnam            | 1         | 0.61%   |
| Uruguay            | 1         | 0.61%   |
| Sweden             | 1         | 0.61%   |
| Portugal           | 1         | 0.61%   |
| Peru               | 1         | 0.61%   |
| Norway             | 1         | 0.61%   |
| Nigeria            | 1         | 0.61%   |
| New Zealand        | 1         | 0.61%   |
| Mexico             | 1         | 0.61%   |
| Latvia             | 1         | 0.61%   |
| Indonesia          | 1         | 0.61%   |
| Honduras           | 1         | 0.61%   |
| Guatemala          | 1         | 0.61%   |
| Grenada            | 1         | 0.61%   |
| Ecuador            | 1         | 0.61%   |
| Dominican Republic | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 5         | 2.94%   |
| Moscow             | 5         | 2.94%   |
| St Petersburg      | 3         | 1.76%   |
| Denver             | 3         | 1.76%   |
| Amsterdam          | 3         | 1.76%   |
| Spring Hill        | 2         | 1.18%   |
| Sofia              | 2         | 1.18%   |
| Rome               | 2         | 1.18%   |
| Orlando            | 2         | 1.18%   |
| Munich             | 2         | 1.18%   |
| Meknes             | 2         | 1.18%   |
| Lublin             | 2         | 1.18%   |
| Ioannina           | 2         | 1.18%   |
| Hyderabad          | 2         | 1.18%   |
| Geneva             | 2         | 1.18%   |
| Zagnansk           | 1         | 0.59%   |
| Yekaterinburg      | 1         | 0.59%   |
| Yambol             | 1         | 0.59%   |
| Worthing           | 1         | 0.59%   |
| Wilen bei Wollerau | 1         | 0.59%   |
| Weatherford        | 1         | 0.59%   |
| Warsaw             | 1         | 0.59%   |
| Volgograd          | 1         | 0.59%   |
| Vlaardingen        | 1         | 0.59%   |
| Vienna             | 1         | 0.59%   |
| Viby J             | 1         | 0.59%   |
| Varna              | 1         | 0.59%   |
| Trujillo           | 1         | 0.59%   |
| Toulouse           | 1         | 0.59%   |
| Touget             | 1         | 0.59%   |
| Toms River         | 1         | 0.59%   |
| Tegucigalpa        | 1         | 0.59%   |
| Syktyvkar          | 1         | 0.59%   |
| Sydney             | 1         | 0.59%   |
| Surabaya           | 1         | 0.59%   |
| Sun Prairie        | 1         | 0.59%   |
| Stratford          | 1         | 0.59%   |
| South Shields      | 1         | 0.59%   |
| Solone             | 1         | 0.59%   |
| Sohren             | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 48        | 64     | 19.92%  |
| Seagate                     | 38        | 47     | 15.77%  |
| WDC                         | 36        | 45     | 14.94%  |
| Kingston                    | 16        | 17     | 6.64%   |
| Unknown                     | 13        | 19     | 5.39%   |
| SanDisk                     | 13        | 16     | 5.39%   |
| Toshiba                     | 9         | 10     | 3.73%   |
| HGST                        | 9         | 10     | 3.73%   |
| Intel                       | 8         | 10     | 3.32%   |
| Crucial                     | 8         | 9      | 3.32%   |
| SK hynix                    | 7         | 7      | 2.9%    |
| Hitachi                     | 5         | 5      | 2.07%   |
| Phison                      | 3         | 3      | 1.24%   |
| Micron Technology           | 3         | 4      | 1.24%   |
| Patriot                     | 2         | 2      | 0.83%   |
| Micron/Crucial Technology   | 2         | 2      | 0.83%   |
| Corsair                     | 2         | 2      | 0.83%   |
| A-DATA Technology           | 2         | 3      | 0.83%   |
| XPG                         | 1         | 4      | 0.41%   |
| Transcend                   | 1         | 1      | 0.41%   |
| SPCC                        | 1         | 1      | 0.41%   |
| PNY                         | 1         | 1      | 0.41%   |
| Phison Electronics          | 1         | 1      | 0.41%   |
| ORIGIN                      | 1         | 1      | 0.41%   |
| OCZ                         | 1         | 1      | 0.41%   |
| Maxtor                      | 1         | 1      | 0.41%   |
| LITEONIT                    | 1         | 1      | 0.41%   |
| Lenovo                      | 1         | 1      | 0.41%   |
| KIOXIA                      | 1         | 1      | 0.41%   |
| Kingston Technology Company | 1         | 2      | 0.41%   |
| INNOVATION IT               | 1         | 1      | 0.41%   |
| Gigabyte Technology         | 1         | 2      | 0.41%   |
| China                       | 1         | 1      | 0.41%   |
| BHT                         | 1         | 1      | 0.41%   |
| Apple                       | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 5         | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 1.89%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 1.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 4         | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB                      | 4         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4         | 1.52%   |
| Samsung SSD 870 EVO 500GB                           | 4         | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 1.14%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.14%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 1.14%   |
| Kingston SHFS37A120G 120GB SSD                      | 3         | 1.14%   |
| HGST HTS545050A7E680 500GB                          | 3         | 1.14%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 1.14%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 0.76%   |
| Unknown MMC Card  64GB                              | 2         | 0.76%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.76%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB             | 2         | 0.76%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.76%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.76%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 2         | 0.76%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 2         | 0.76%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.76%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.76%   |
| Samsung NVMe SSD Drive 500GB                        | 2         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 0.76%   |
| Patriot Burst 120GB SSD                             | 2         | 0.76%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.76%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 0.76%   |
| HGST HTS541010B7E610 1TB                            | 2         | 0.76%   |
| HGST HTS541010A9E680 1TB                            | 2         | 0.76%   |
| XPG NVMe SSD Drive 2TB                              | 1         | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.38%   |
| WDC WD7500AYYS-01RCA0 752GB                         | 1         | 0.38%   |
| WDC WD60 EFRX-68L0BN1 6TB                           | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 47     | 38.78%  |
| WDC                 | 30        | 37     | 30.61%  |
| HGST                | 9         | 10     | 9.18%   |
| Toshiba             | 8         | 9      | 8.16%   |
| Samsung Electronics | 6         | 7      | 6.12%   |
| Hitachi             | 5         | 5      | 5.1%    |
| Unknown             | 1         | 1      | 1.02%   |
| Maxtor              | 1         | 1      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 23     | 28.57%  |
| Kingston            | 15        | 16     | 21.43%  |
| SanDisk             | 6         | 7      | 8.57%   |
| Crucial             | 6         | 7      | 8.57%   |
| WDC                 | 4         | 4      | 5.71%   |
| Patriot             | 2         | 2      | 2.86%   |
| Intel               | 2         | 2      | 2.86%   |
| Transcend           | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| ORIGIN              | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| Lenovo              | 1         | 1      | 1.43%   |
| INNOVATION IT       | 1         | 1      | 1.43%   |
| Gigabyte Technology | 1         | 2      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| BHT                 | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 2      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 82        | 117    | 37.27%  |
| SSD     | 63        | 78     | 28.64%  |
| NVMe    | 61        | 83     | 27.73%  |
| MMC     | 12        | 16     | 5.45%   |
| Unknown | 2         | 3      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 191    | 59.69%  |
| NVMe | 61        | 83     | 31.12%  |
| MMC  | 12        | 16     | 6.12%   |
| SAS  | 6         | 7      | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 103    | 52.98%  |
| 0.51-1.0   | 53        | 66     | 35.1%   |
| 1.01-2.0   | 14        | 21     | 9.27%   |
| 4.01-10.0  | 3         | 3      | 1.99%   |
| 3.01-4.0   | 1         | 2      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 46        | 27.22%  |
| 501-1000       | 36        | 21.3%   |
| 101-250        | 29        | 17.16%  |
| Unknown        | 12        | 7.1%    |
| 1001-2000      | 11        | 6.51%   |
| 1-20           | 10        | 5.92%   |
| More than 3000 | 9         | 5.33%   |
| 51-100         | 7         | 4.14%   |
| 2001-3000      | 5         | 2.96%   |
| 21-50          | 4         | 2.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 48        | 27.27%  |
| 101-250        | 39        | 22.16%  |
| 21-50          | 22        | 12.5%   |
| 251-500        | 18        | 10.23%  |
| 51-100         | 18        | 10.23%  |
| Unknown        | 12        | 6.82%   |
| 1001-2000      | 9         | 5.11%   |
| 501-1000       | 5         | 2.84%   |
| More than 3000 | 4         | 2.27%   |
| 2001-3000      | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 6.25%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 6.25%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 3.13%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 3.13%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 3.13%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 3.13%   |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 3.13%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.13%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 3.13%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.13%   |
| Seagate ST3750330AS 752GB             | 1         | 1      | 3.13%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 3.13%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 2      | 3.13%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 3.13%   |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 3.13%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 3.13%   |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 3.13%   |
| Hitachi HUA722010CLA330 1TB           | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.13%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.13%   |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 41.94%  |
| WDC                 | 4         | 5      | 12.9%   |
| Samsung Electronics | 4         | 4      | 12.9%   |
| Hitachi             | 4         | 4      | 12.9%   |
| HGST                | 3         | 3      | 9.68%   |
| Toshiba             | 2         | 3      | 6.45%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 44.83%  |
| WDC                 | 4         | 5      | 13.79%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| HGST                | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 3      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 33     | 93.33%  |
| SSD  | 2         | 2      | 6.67%   |

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
| Works    | 98        | 149    | 51.04%  |
| Detected | 65        | 113    | 33.85%  |
| Malfunc  | 29        | 35     | 15.1%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 89        | 43.63%  |
| AMD                              | 46        | 22.55%  |
| Samsung Electronics              | 28        | 13.73%  |
| SanDisk                          | 9         | 4.41%   |
| SK hynix                         | 6         | 2.94%   |
| Phison Electronics               | 5         | 2.45%   |
| Micron/Crucial Technology        | 3         | 1.47%   |
| Micron Technology                | 3         | 1.47%   |
| ASMedia Technology               | 3         | 1.47%   |
| Kingston Technology Company      | 2         | 0.98%   |
| ADATA Technology                 | 2         | 0.98%   |
| Toshiba America Info Systems     | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Nvidia                           | 1         | 0.49%   |
| Marvell Technology Group         | 1         | 0.49%   |
| LSI Logic / Symbios Logic        | 1         | 0.49%   |
| KIOXIA                           | 1         | 0.49%   |
| JMicron Technology               | 1         | 0.49%   |
| Broadcom                         | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 14.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 6.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 5.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 4.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 3.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.76%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.32%   |
| Intel SSD 660P Series                                                          | 3         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.32%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.88%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.88%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.88%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.88%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 120       | 58.25%  |
| NVMe | 62        | 30.1%   |
| IDE  | 14        | 6.8%    |
| RAID | 10        | 4.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 102       | 61.82%  |
| AMD                      | 57        | 34.55%  |
| ARM                      | 4         | 2.42%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.61%   |
| PowerMac11,2             | 1         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 4         | 2.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 3         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 1.82%   |
| ARM Processor                                      | 3         | 1.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 3         | 1.82%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 2         | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.21%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 2         | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 2         | 1.21%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.21%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 2         | 1.21%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 1.21%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 2         | 1.21%   |
| Intel Core i3-4030U CPU @ 1.90GHz                  | 2         | 1.21%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 2         | 1.21%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 2         | 1.21%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 2         | 1.21%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.21%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.21%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2         | 1.21%   |
| AMD Ryzen 5 5600H with Radeon Graphics             | 2         | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.21%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx      | 2         | 1.21%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.21%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.21%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.61%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.61%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.61%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.61%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.61%   |
| Intel Pentium CPU N3520 @ 2.16GHz                  | 1         | 0.61%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.61%   |
| Intel Pentium CPU 4425Y @ 1.70GHz                  | 1         | 0.61%   |
| Intel Pentium 4 CPU 2.80GHz                        | 1         | 0.61%   |
| Intel Genuine CPU 585 @ 2.16GHz                    | 1         | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz                  | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 17.58%  |
| Intel Core i7           | 24        | 14.55%  |
| AMD Ryzen 5             | 19        | 11.52%  |
| Other                   | 18        | 10.91%  |
| Intel Core i3           | 16        | 9.7%    |
| AMD Ryzen 7             | 13        | 7.88%   |
| Intel Atom              | 7         | 4.24%   |
| Intel Celeron           | 6         | 3.64%   |
| Intel Pentium           | 4         | 2.42%   |
| AMD Ryzen 7 PRO         | 3         | 1.82%   |
| AMD FX                  | 3         | 1.82%   |
| Intel Core 2 Duo        | 2         | 1.21%   |
| AMD Ryzen 3             | 2         | 1.21%   |
| AMD A8                  | 2         | 1.21%   |
| Intel Xeon              | 1         | 0.61%   |
| Intel Pentium Gold      | 1         | 0.61%   |
| Intel Pentium 4         | 1         | 0.61%   |
| Intel Genuine           | 1         | 0.61%   |
| Intel Core i9           | 1         | 0.61%   |
| AMD Turion 64 X2 Mobile | 1         | 0.61%   |
| AMD Ryzen Threadripper  | 1         | 0.61%   |
| AMD Ryzen 9             | 1         | 0.61%   |
| AMD Ryzen 5 PRO         | 1         | 0.61%   |
| AMD Phenom II X4        | 1         | 0.61%   |
| AMD E2                  | 1         | 0.61%   |
| AMD E1                  | 1         | 0.61%   |
| AMD C-60                | 1         | 0.61%   |
| AMD Athlon II X3        | 1         | 0.61%   |
| AMD Athlon II X2        | 1         | 0.61%   |
| AMD A6                  | 1         | 0.61%   |
| AMD A4                  | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 58        | 35.15%  |
| 2       | 53        | 32.12%  |
| 6       | 24        | 14.55%  |
| 8       | 16        | 9.7%    |
| 1       | 6         | 3.64%   |
| 14      | 2         | 1.21%   |
| 12      | 2         | 1.21%   |
| 64      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |
| 3       | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 162       | 98.18%  |
| 2       | 2         | 1.21%   |
| Unknown | 1         | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 115       | 69.7%   |
| 1       | 48        | 29.09%  |
| 4       | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 151       | 91.52%  |
| Unknown        | 8         | 4.85%   |
| 64-bit         | 3         | 1.82%   |
| 32-bit         | 3         | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 34.12%  |
| 0x40651    | 8         | 4.71%   |
| 0x306a9    | 7         | 4.12%   |
| 0x906e9    | 5         | 2.94%   |
| 0x906ea    | 4         | 2.35%   |
| 0x806ec    | 4         | 2.35%   |
| 0x806e9    | 4         | 2.35%   |
| 0x406e3    | 4         | 2.35%   |
| 0x08108102 | 4         | 2.35%   |
| 0x806ea    | 3         | 1.76%   |
| 0x30678    | 3         | 1.76%   |
| 0x206a7    | 3         | 1.76%   |
| 0x0a50000c | 3         | 1.76%   |
| 0x08600104 | 3         | 1.76%   |
| 0x906a3    | 2         | 1.18%   |
| 0x506e3    | 2         | 1.18%   |
| 0x106c2    | 2         | 1.18%   |
| 0x0a201009 | 2         | 1.18%   |
| 0x08701021 | 2         | 1.18%   |
| 0x0800820d | 2         | 1.18%   |
| 0x07030105 | 2         | 1.18%   |
| 0x06006705 | 2         | 1.18%   |
| 0x06000852 | 2         | 1.18%   |
| 0x05000119 | 2         | 1.18%   |
| 0x010000c8 | 2         | 1.18%   |
| 0xa0671    | 1         | 0.59%   |
| 0xa0652    | 1         | 0.59%   |
| 0x906ed    | 1         | 0.59%   |
| 0x90675    | 1         | 0.59%   |
| 0x90672    | 1         | 0.59%   |
| 0x806eb    | 1         | 0.59%   |
| 0x806c1    | 1         | 0.59%   |
| 0x706e5    | 1         | 0.59%   |
| 0x706a1    | 1         | 0.59%   |
| 0x406c4    | 1         | 0.59%   |
| 0x306d4    | 1         | 0.59%   |
| 0x306c3    | 1         | 0.59%   |
| 0x30673    | 1         | 0.59%   |
| 0x20652    | 1         | 0.59%   |
| 0x106ca    | 1         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 34        | 20.61%  |
| Haswell          | 13        | 7.88%   |
| Zen 3            | 11        | 6.67%   |
| Zen 2            | 11        | 6.67%   |
| IvyBridge        | 10        | 6.06%   |
| Unknown          | 10        | 6.06%   |
| Zen+             | 9         | 5.45%   |
| Skylake          | 8         | 4.85%   |
| Silvermont       | 7         | 4.24%   |
| Zen              | 5         | 3.03%   |
| Alderlake Hybrid | 5         | 3.03%   |
| SandyBridge      | 4         | 2.42%   |
| Excavator        | 4         | 2.42%   |
| TigerLake        | 3         | 1.82%   |
| Puma             | 3         | 1.82%   |
| Piledriver       | 3         | 1.82%   |
| K10              | 3         | 1.82%   |
| IceLake          | 3         | 1.82%   |
| Bonnell          | 3         | 1.82%   |
| Penryn           | 2         | 1.21%   |
| Goldmont plus    | 2         | 1.21%   |
| Core             | 2         | 1.21%   |
| Broadwell        | 2         | 1.21%   |
| Bobcat           | 2         | 1.21%   |
| Westmere         | 1         | 0.61%   |
| NetBurst         | 1         | 0.61%   |
| Nehalem          | 1         | 0.61%   |
| K8 Hammer        | 1         | 0.61%   |
| Jaguar           | 1         | 0.61%   |
| CometLake        | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 82        | 42.05%  |
| Nvidia                           | 56        | 28.72%  |
| AMD                              | 54        | 27.69%  |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Matrox Electronics Systems       | 1         | 0.51%   |
| ASPEED Technology                | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.97%   |
| AMD Renoir                                                                               | 6         | 2.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 2.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.48%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.49%   |
| Intel HD Graphics 630                                                                    | 3         | 1.49%   |
| Intel HD Graphics 620                                                                    | 3         | 1.49%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.49%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3         | 1.49%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.99%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.99%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.99%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.99%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 0.99%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.99%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.99%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.99%   |
| AMD Lucienne                                                                             | 2         | 0.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 32.74%  |
| 1 x AMD        | 47        | 27.98%  |
| 1 x Nvidia     | 26        | 15.48%  |
| Intel + Nvidia | 25        | 14.88%  |
| Other          | 4         | 2.38%   |
| AMD + Nvidia   | 3         | 1.79%   |
| 2 x Nvidia     | 2         | 1.19%   |
| 2 x AMD        | 2         | 1.19%   |
| 1 x SiS        | 1         | 0.6%    |
| 1 x Matrox     | 1         | 0.6%    |
| Intel + AMD    | 1         | 0.6%    |
| AMD + ASPEED   | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 118       | 70.24%  |
| Proprietary | 45        | 26.79%  |
| Unknown     | 5         | 2.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 56.98%  |
| 1.01-2.0   | 19        | 11.05%  |
| 3.01-4.0   | 17        | 9.88%   |
| 0.01-0.5   | 15        | 8.72%   |
| 0.51-1.0   | 8         | 4.65%   |
| 7.01-8.0   | 5         | 2.91%   |
| 5.01-6.0   | 4         | 2.33%   |
| 8.01-16.0  | 3         | 1.74%   |
| 2.01-3.0   | 2         | 1.16%   |
| 16.01-24.0 | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 25        | 14.29%  |
| AU Optronics         | 23        | 13.14%  |
| BOE                  | 19        | 10.86%  |
| Samsung Electronics  | 16        | 9.14%   |
| LG Display           | 16        | 9.14%   |
| Hewlett-Packard      | 9         | 5.14%   |
| Dell                 | 8         | 4.57%   |
| Iiyama               | 5         | 2.86%   |
| Acer                 | 5         | 2.86%   |
| Philips              | 4         | 2.29%   |
| Goldstar             | 4         | 2.29%   |
| BenQ                 | 4         | 2.29%   |
| PANDA                | 3         | 1.71%   |
| Lenovo               | 3         | 1.71%   |
| ASUSTek Computer     | 3         | 1.71%   |
| AOC                  | 3         | 1.71%   |
| Sharp                | 2         | 1.14%   |
| LG Philips           | 2         | 1.14%   |
| Fujitsu Siemens      | 2         | 1.14%   |
| Apple                | 2         | 1.14%   |
| Ancor Communications | 2         | 1.14%   |
| Unknown              | 1         | 0.57%   |
| TMX                  | 1         | 0.57%   |
| STD                  | 1         | 0.57%   |
| Sceptre Tech         | 1         | 0.57%   |
| Sceptre              | 1         | 0.57%   |
| Panasonic            | 1         | 0.57%   |
| ONN                  | 1         | 0.57%   |
| MSI                  | 1         | 0.57%   |
| InnoLux Display      | 1         | 0.57%   |
| Idek Iiyama          | 1         | 0.57%   |
| Huion                | 1         | 0.57%   |
| Gigabyte Technology  | 1         | 0.57%   |
| FUN                  | 1         | 0.57%   |
| CHR                  | 1         | 0.57%   |
| BOE Technology Group | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.65%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.1%    |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 2         | 1.1%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.1%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.1%    |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.55%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.55%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.55%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.55%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.55%   |
| Sceptre Tech E24 SPT099D 1920x1080 530x300mm 24.0-inch                | 1         | 0.55%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.55%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.55%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.55%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.55%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.55%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.55%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.55%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.55%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch    | 1         | 0.55%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.55%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1         | 0.55%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.55%   |
| Philips LCD Monitor 227E4LH 1920x1080                                 | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 43.2%   |
| 1366x768 (WXGA)    | 33        | 19.53%  |
| 3840x2160 (4K)     | 8         | 4.73%   |
| 2560x1440 (QHD)    | 8         | 4.73%   |
| 1920x1200 (WUXGA)  | 8         | 4.73%   |
| 1600x900 (HD+)     | 5         | 2.96%   |
| 3440x1440          | 4         | 2.37%   |
| 1680x1050 (WSXGA+) | 4         | 2.37%   |
| 2160x1440          | 3         | 1.78%   |
| 1280x800 (WXGA)    | 3         | 1.78%   |
| Unknown            | 3         | 1.78%   |
| 2560x1600          | 2         | 1.18%   |
| 1280x1024 (SXGA)   | 2         | 1.18%   |
| 1024x600           | 2         | 1.18%   |
| 7680x1080          | 1         | 0.59%   |
| 3840x1600          | 1         | 0.59%   |
| 3840x1080          | 1         | 0.59%   |
| 3200x2000          | 1         | 0.59%   |
| 2880x1800          | 1         | 0.59%   |
| 2560x1080          | 1         | 0.59%   |
| 2288x1287          | 1         | 0.59%   |
| 2256x1504          | 1         | 0.59%   |
| 1920x1280          | 1         | 0.59%   |
| 1360x768           | 1         | 0.59%   |
| 1280x720 (HD)      | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 26.29%  |
| 14      | 20        | 11.43%  |
| 24      | 16        | 9.14%   |
| 13      | 15        | 8.57%   |
| Unknown | 14        | 8%      |
| 27      | 8         | 4.57%   |
| 23      | 8         | 4.57%   |
| 21      | 8         | 4.57%   |
| 17      | 6         | 3.43%   |
| 34      | 4         | 2.29%   |
| 22      | 4         | 2.29%   |
| 12      | 4         | 2.29%   |
| 11      | 3         | 1.71%   |
| 10      | 3         | 1.71%   |
| 28      | 2         | 1.14%   |
| 19      | 2         | 1.14%   |
| 16      | 2         | 1.14%   |
| 84      | 1         | 0.57%   |
| 40      | 1         | 0.57%   |
| 39      | 1         | 0.57%   |
| 37      | 1         | 0.57%   |
| 33      | 1         | 0.57%   |
| 31      | 1         | 0.57%   |
| 25      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |
| 18      | 1         | 0.57%   |
| 8       | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 42.53%  |
| 501-600     | 31        | 17.82%  |
| 201-300     | 20        | 11.49%  |
| 401-500     | 15        | 8.62%   |
| Unknown     | 14        | 8.05%   |
| 351-400     | 6         | 3.45%   |
| 701-800     | 5         | 2.87%   |
| 601-700     | 4         | 2.3%    |
| 801-900     | 3         | 1.72%   |
| 1501-2000   | 1         | 0.57%   |
| 101-200     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 115       | 70.99%  |
| 16/10   | 20        | 12.35%  |
| Unknown | 13        | 8.02%   |
| 3/2     | 6         | 3.7%    |
| 21/9    | 6         | 3.7%    |
| 5/4     | 2         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 25.86%  |
| 81-90          | 27        | 15.52%  |
| 201-250        | 26        | 14.94%  |
| Unknown        | 14        | 8.05%   |
| 251-300        | 11        | 6.32%   |
| 301-350        | 8         | 4.6%    |
| 71-80          | 7         | 4.02%   |
| 351-500        | 7         | 4.02%   |
| 61-70          | 4         | 2.3%    |
| 51-60          | 4         | 2.3%    |
| 151-200        | 3         | 1.72%   |
| 121-130        | 3         | 1.72%   |
| 111-120        | 3         | 1.72%   |
| 501-1000       | 3         | 1.72%   |
| 41-50          | 2         | 1.15%   |
| 141-150        | 2         | 1.15%   |
| 131-140        | 2         | 1.15%   |
| More than 1000 | 1         | 0.57%   |
| 1-40           | 1         | 0.57%   |
| 91-100         | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 49        | 28%     |
| 51-100        | 47        | 26.86%  |
| 101-120       | 45        | 25.71%  |
| 161-240       | 17        | 9.71%   |
| Unknown       | 14        | 8%      |
| More than 240 | 3         | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 135       | 80.84%  |
| 2     | 29        | 17.37%  |
| 0     | 3         | 1.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 91        | 38.24%  |
| Intel                            | 68        | 28.57%  |
| Qualcomm Atheros                 | 23        | 9.66%   |
| Broadcom                         | 15        | 6.3%    |
| Ralink Technology                | 5         | 2.1%    |
| TP-Link                          | 4         | 1.68%   |
| MediaTek                         | 4         | 1.68%   |
| Xiaomi                           | 3         | 1.26%   |
| Sierra Wireless                  | 3         | 1.26%   |
| Broadcom Limited                 | 3         | 1.26%   |
| Qualcomm Atheros Communications  | 2         | 0.84%   |
| Cypress Semiconductor            | 2         | 0.84%   |
| Tenda                            | 1         | 0.42%   |
| STMicroelectronics               | 1         | 0.42%   |
| Standard Microsystems            | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Ralink                           | 1         | 0.42%   |
| Qualcomm                         | 1         | 0.42%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.42%   |
| Nvidia                           | 1         | 0.42%   |
| Marvell Technology Group         | 1         | 0.42%   |
| Huawei Technologies              | 1         | 0.42%   |
| DisplayLink                      | 1         | 0.42%   |
| ASUSTek Computer                 | 1         | 0.42%   |
| ASIX Electronics                 | 1         | 0.42%   |
| Arduino SA                       | 1         | 0.42%   |
| Apple                            | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 21.53%  |
| Intel Wi-Fi 6 AX200                                               | 14        | 5.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.38%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.46%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.09%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.09%   |
| Intel Wireless 8260                                               | 3         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.73%   |
| Intel Wireless 7265                                               | 2         | 0.73%   |
| Intel Wireless 7260                                               | 2         | 0.73%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.73%   |
| Cypress K38231_03                                                 | 2         | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.73%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 41.54%  |
| Realtek Semiconductor           | 25        | 19.23%  |
| Qualcomm Atheros                | 19        | 14.62%  |
| Broadcom                        | 9         | 6.92%   |
| Ralink Technology               | 5         | 3.85%   |
| TP-Link                         | 3         | 2.31%   |
| Sierra Wireless                 | 3         | 2.31%   |
| MediaTek                        | 3         | 2.31%   |
| Broadcom Limited                | 3         | 2.31%   |
| Qualcomm Atheros Communications | 2         | 1.54%   |
| Tenda                           | 1         | 0.77%   |
| Ralink                          | 1         | 0.77%   |
| Qualcomm                        | 1         | 0.77%   |
| ASUSTek Computer                | 1         | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 14        | 10.77%  |
| Intel Wireless 8265 / 8275                                    | 8         | 6.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 5.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 3.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 2.31%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 3         | 2.31%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 2.31%   |
| Intel Wireless 8260                                           | 3         | 2.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 2.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 1.54%   |
| Intel Wireless 7265                                           | 2         | 1.54%   |
| Intel Wireless 7260                                           | 2         | 1.54%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.54%   |
| Broadcom BCM4311 802.11b/g WLAN                               | 2         | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1         | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.77%   |
| TP-Link 802.11n NIC                                           | 1         | 0.77%   |
| Tenda U12                                                     | 1         | 0.77%   |
| Sierra Wireless EM7455                                        | 1         | 0.77%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.77%   |
| Sierra Wireless EM7305 Modem                                  | 1         | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.77%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 1         | 0.77%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 83        | 58.87%  |
| Intel                            | 31        | 21.99%  |
| Broadcom                         | 7         | 4.96%   |
| Qualcomm Atheros                 | 5         | 3.55%   |
| Xiaomi                           | 3         | 2.13%   |
| Cypress Semiconductor            | 2         | 1.42%   |
| TP-Link                          | 1         | 0.71%   |
| Standard Microsystems            | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |
| Nvidia                           | 1         | 0.71%   |
| MediaTek                         | 1         | 0.71%   |
| Marvell Technology Group         | 1         | 0.71%   |
| Huawei Technologies              | 1         | 0.71%   |
| DisplayLink                      | 1         | 0.71%   |
| ASIX Electronics                 | 1         | 0.71%   |
| Apple                            | 1         | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 41.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 8.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.84%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.42%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.42%   |
| Cypress K38231_03                                                 | 2         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.71%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.71%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 0.71%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.71%   |
| Huawei JKM-LX1                                                    | 1         | 0.71%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.71%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.71%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.71%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 132       | 51.56%  |
| WiFi     | 121       | 47.27%  |
| Modem    | 2         | 0.78%   |
| Unknown  | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 60.37%  |
| Ethernet | 65        | 39.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 78        | 47.27%  |
| 2     | 72        | 43.64%  |
| 0     | 8         | 4.85%   |
| 3     | 6         | 3.64%   |
| 4     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 84.43%  |
| Yes  | 26        | 15.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 43.52%  |
| Realtek Semiconductor           | 16        | 14.81%  |
| Broadcom                        | 9         | 8.33%   |
| Lite-On Technology              | 7         | 6.48%   |
| Cambridge Silicon Radio         | 7         | 6.48%   |
| IMC Networks                    | 5         | 4.63%   |
| Qualcomm Atheros Communications | 4         | 3.7%    |
| Foxconn / Hon Hai               | 4         | 3.7%    |
| Realtek                         | 2         | 1.85%   |
| USI                             | 1         | 0.93%   |
| Opticis                         | 1         | 0.93%   |
| Foxconn International           | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |
| ASUSTek Computer                | 1         | 0.93%   |
| Apple                           | 1         | 0.93%   |
| Actions                         | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 12.96%  |
| Intel AX200 Bluetooth                               | 14        | 12.96%  |
| Realtek Bluetooth Radio                             | 9         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 6.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 4.63%   |
| Intel AX201 Bluetooth                               | 5         | 4.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2.78%   |
| Intel AX210 Bluetooth                               | 3         | 2.78%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2.78%   |
| Realtek Bluetooth Radio                             | 2         | 1.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.85%   |
| Intel Bluetooth Device                              | 2         | 1.85%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.85%   |
| IMC Networks Bluetooth Device                       | 2         | 1.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.85%   |
| USI Bluetooth Device                                | 1         | 0.93%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.93%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.93%   |
| Opticis Bluetooth Radio                             | 1         | 0.93%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.93%   |
| IMC Networks Wireless_Device                        | 1         | 0.93%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.93%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.93%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.93%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.93%   |
| Broadcom HP Portable Valentine                      | 1         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.93%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.93%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.93%   |
| Apple Bluetooth Host Controller                     | 1         | 0.93%   |
| Actions general adapter                             | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96        | 42.48%  |
| AMD                              | 60        | 26.55%  |
| Nvidia                           | 36        | 15.93%  |
| Logitech                         | 6         | 2.65%   |
| JMTek                            | 5         | 2.21%   |
| C-Media Electronics              | 5         | 2.21%   |
| Texas Instruments                | 2         | 0.88%   |
| Creative Technology              | 2         | 0.88%   |
| VIA Technologies                 | 1         | 0.44%   |
| SteelSeries ApS                  | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| SAVITECH                         | 1         | 0.44%   |
| Fry's Electronics                | 1         | 0.44%   |
| Focusrite-Novation               | 1         | 0.44%   |
| Elgato Systems                   | 1         | 0.44%   |
| EDFIER                           | 1         | 0.44%   |
| DCMT Technology                  | 1         | 0.44%   |
| Corsair                          | 1         | 0.44%   |
| Cambridge Audio                  | 1         | 0.44%   |
| Blue Microphones                 | 1         | 0.44%   |
| BEHRINGER International          | 1         | 0.44%   |
| ASRock                           | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 7.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 5.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 4.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.82%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 3.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 2.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.08%   |
| JMTek USB PnP Audio Device                                                 | 5         | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.74%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.39%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 1.39%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.39%   |
| AMD High Definition Audio Controller                                       | 4         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.04%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.04%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.69%   |
| Logitech PRO X                                                             | 2         | 0.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 32        | 24.81%  |
| Samsung Electronics | 31        | 24.03%  |
| Micron Technology   | 12        | 9.3%    |
| Kingston            | 11        | 8.53%   |
| Unknown             | 9         | 6.98%   |
| G.Skill             | 8         | 6.2%    |
| Corsair             | 8         | 6.2%    |
| A-DATA Technology   | 6         | 4.65%   |
| Crucial             | 4         | 3.1%    |
| Ramaxel Technology  | 3         | 2.33%   |
| Transcend           | 1         | 0.78%   |
| Patriot             | 1         | 0.78%   |
| Elpida              | 1         | 0.78%   |
| Avant               | 1         | 0.78%   |
| 48spaces            | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.41%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 2         | 1.41%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 2         | 1.41%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                   | 1         | 0.7%    |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s            | 1         | 0.7%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1         | 0.7%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s              | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2                          | 1         | 0.7%    |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 0.7%    |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 0.7%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.7%    |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.7%    |
| SK hynix RAM HMT31GR7BFR4C-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 50%     |
| DDR3    | 42        | 36.21%  |
| LPDDR3  | 4         | 3.45%   |
| LPDDR5  | 3         | 2.59%   |
| LPDDR4  | 3         | 2.59%   |
| DDR2    | 3         | 2.59%   |
| Unknown | 2         | 1.72%   |
| DDR5    | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 61.74%  |
| DIMM         | 35        | 30.43%  |
| Row Of Chips | 9         | 7.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 55        | 43.65%  |
| 4096  | 41        | 32.54%  |
| 16384 | 14        | 11.11%  |
| 2048  | 11        | 8.73%   |
| 1024  | 3         | 2.38%   |
| 512   | 2         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 23.81%  |
| 2667    | 20        | 15.87%  |
| 3200    | 19        | 15.08%  |
| 2400    | 10        | 7.94%   |
| 1333    | 9         | 7.14%   |
| 3600    | 6         | 4.76%   |
| 1334    | 5         | 3.97%   |
| 2133    | 4         | 3.17%   |
| 6400    | 3         | 2.38%   |
| 1867    | 3         | 2.38%   |
| 3866    | 2         | 1.59%   |
| 3000    | 2         | 1.59%   |
| 533     | 2         | 1.59%   |
| 4800    | 1         | 0.79%   |
| 4266    | 1         | 0.79%   |
| 3733    | 1         | 0.79%   |
| 3534    | 1         | 0.79%   |
| 3333    | 1         | 0.79%   |
| 3266    | 1         | 0.79%   |
| 2933    | 1         | 0.79%   |
| 2800    | 1         | 0.79%   |
| 1067    | 1         | 0.79%   |
| 667     | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

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
| Chicony Electronics                    | 34        | 30.09%  |
| IMC Networks                           | 17        | 15.04%  |
| Microdia                               | 11        | 9.73%   |
| Realtek Semiconductor                  | 8         | 7.08%   |
| Quanta                                 | 7         | 6.19%   |
| Logitech                               | 7         | 6.19%   |
| Bison Electronics                      | 7         | 6.19%   |
| Sunplus Innovation Technology          | 4         | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.54%   |
| Suyin                                  | 3         | 2.65%   |
| Syntek                                 | 2         | 1.77%   |
| MacroSilicon                           | 2         | 1.77%   |
| SunplusIT                              | 1         | 0.88%   |
| Silicon Motion                         | 1         | 0.88%   |
| Microsoft                              | 1         | 0.88%   |
| Intel                                  | 1         | 0.88%   |
| GEMBIRD                                | 1         | 0.88%   |
| Asuscom Network                        | 1         | 0.88%   |
| Acer                                   | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 11        | 9.57%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 6.09%   |
| Suyin HP Truevision HD                        | 3         | 2.61%   |
| Realtek USB Camera                            | 3         | 2.61%   |
| Quanta HD User Facing                         | 3         | 2.61%   |
| Microdia Integrated_Webcam_HD                 | 3         | 2.61%   |
| Logitech Webcam C270                          | 3         | 2.61%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 2.61%   |
| Chicony HP TrueVision HD Camera               | 3         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.61%   |
| Syntek Integrated Camera                      | 2         | 1.74%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.74%   |
| Microdia HP Integrated Webcam                 | 2         | 1.74%   |
| IMC Networks Integrated Camera                | 2         | 1.74%   |
| IMC Networks HD Camera                        | 2         | 1.74%   |
| Chicony USB2.0 Camera                         | 2         | 1.74%   |
| Chicony USB 2.0 Camera                        | 2         | 1.74%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.74%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.74%   |
| Chicony HD WebCam                             | 2         | 1.74%   |
| Chicony EasyCamera                            | 2         | 1.74%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.74%   |
| Bison Lenovo EasyCamera                       | 2         | 1.74%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.87%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.87%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.87%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.87%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.87%   |
| Realtek Laptop Camera                         | 1         | 0.87%   |
| Realtek Integrated Webcam HD                  | 1         | 0.87%   |
| Realtek HD WebCam                             | 1         | 0.87%   |
| Realtek FULL HD 1080P Webcam                  | 1         | 0.87%   |
| Quanta VGA WebCam                             | 1         | 0.87%   |
| Quanta HP Webcam                              | 1         | 0.87%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.87%   |
| Quanta ACER HD User Facing                    | 1         | 0.87%   |
| Microsoft LifeCam HD-3000                     | 1         | 0.87%   |
| Microdia Webcam Vitade AF                     | 1         | 0.87%   |
| Microdia Webcam                               | 1         | 0.87%   |
| Microdia USB 2.0 Camera                       | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 43.75%  |
| Validity Sensors           | 3         | 18.75%  |
| Shenzhen Goodix Technology | 3         | 18.75%  |
| Elan Microelectronics      | 2         | 12.5%   |
| Upek                       | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 31.25%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 18.75%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics  WBDI                                        | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                       | 1         | 6.25%   |

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
| 0     | 127       | 76.51%  |
| 1     | 30        | 18.07%  |
| 2     | 7         | 4.22%   |
| 3     | 2         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 33.33%  |
| Net/wireless             | 7         | 14.58%  |
| Graphics card            | 7         | 14.58%  |
| Chipcard                 | 5         | 10.42%  |
| Multimedia controller    | 4         | 8.33%   |
| Camera                   | 4         | 8.33%   |
| Sound                    | 3         | 6.25%   |
| Net/ethernet             | 1         | 2.08%   |
| Communication controller | 1         | 2.08%   |

