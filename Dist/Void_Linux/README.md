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

Total: 230

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| Dell          | Latitude D610               | Notebook    | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 127       | 70.95%  |
| Void Linux         | 52        | 29.05%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 176       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 11        | 5.79%   |
| 5.13.19_1 | 7         | 3.68%   |
| 6.3.12_1  | 6         | 3.16%   |
| 5.8.18_1  | 5         | 2.63%   |
| 6.1.4_1   | 4         | 2.11%   |
| 6.1.31_1  | 4         | 2.11%   |
| 5.3.9_1   | 4         | 2.11%   |
| 5.18.19_1 | 4         | 2.11%   |
| 5.16.20_1 | 4         | 2.11%   |
| 5.10.17_1 | 4         | 2.11%   |
| 5.8.12_1  | 3         | 1.58%   |
| 5.19.17_1 | 3         | 1.58%   |
| 5.18.14_1 | 3         | 1.58%   |
| 5.15.32_1 | 3         | 1.58%   |
| 5.13.13_1 | 3         | 1.58%   |
| 5.12.10_1 | 3         | 1.58%   |
| 6.5.9_1   | 2         | 1.05%   |
| 6.5.5_2   | 2         | 1.05%   |
| 6.1.21_1  | 2         | 1.05%   |
| 6.1.10_1  | 2         | 1.05%   |
| 6.0.15_1  | 2         | 1.05%   |
| 6.0.13_1  | 2         | 1.05%   |
| 5.9.14_1  | 2         | 1.05%   |
| 5.4.24_1  | 2         | 1.05%   |
| 5.4.13_2  | 2         | 1.05%   |
| 5.19.16_1 | 2         | 1.05%   |
| 5.18.9_1  | 2         | 1.05%   |
| 5.15.41_1 | 2         | 1.05%   |
| 5.15.34_1 | 2         | 1.05%   |
| 5.15.22_1 | 2         | 1.05%   |
| 5.15.16_1 | 2         | 1.05%   |
| 5.13.15_1 | 2         | 1.05%   |
| 5.13.10_1 | 2         | 1.05%   |
| 5.12.14_1 | 2         | 1.05%   |
| 5.11.9_1  | 2         | 1.05%   |
| 5.10.14_1 | 2         | 1.05%   |
| 6.5.7_1   | 1         | 0.53%   |
| 6.5.6_1   | 1         | 0.53%   |
| 6.5.10_1  | 1         | 0.53%   |
| 6.4.8_1   | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 11        | 5.79%   |
| 5.13.19 | 7         | 3.68%   |
| 6.3.12  | 6         | 3.16%   |
| 5.8.18  | 5         | 2.63%   |
| 6.1.4   | 4         | 2.11%   |
| 6.1.31  | 4         | 2.11%   |
| 5.8.12  | 4         | 2.11%   |
| 5.3.9   | 4         | 2.11%   |
| 5.18.19 | 4         | 2.11%   |
| 5.16.20 | 4         | 2.11%   |
| 5.10.17 | 4         | 2.11%   |
| 5.19.17 | 3         | 1.58%   |
| 5.18.14 | 3         | 1.58%   |
| 5.15.32 | 3         | 1.58%   |
| 5.13.13 | 3         | 1.58%   |
| 5.12.10 | 3         | 1.58%   |
| 6.5.9   | 2         | 1.05%   |
| 6.5.5   | 2         | 1.05%   |
| 6.1.21  | 2         | 1.05%   |
| 6.1.10  | 2         | 1.05%   |
| 6.0.15  | 2         | 1.05%   |
| 6.0.13  | 2         | 1.05%   |
| 5.9.14  | 2         | 1.05%   |
| 5.4.24  | 2         | 1.05%   |
| 5.4.13  | 2         | 1.05%   |
| 5.19.16 | 2         | 1.05%   |
| 5.18.9  | 2         | 1.05%   |
| 5.15.41 | 2         | 1.05%   |
| 5.15.34 | 2         | 1.05%   |
| 5.15.22 | 2         | 1.05%   |
| 5.15.16 | 2         | 1.05%   |
| 5.13.15 | 2         | 1.05%   |
| 5.13.10 | 2         | 1.05%   |
| 5.12.14 | 2         | 1.05%   |
| 5.11.9  | 2         | 1.05%   |
| 5.10.14 | 2         | 1.05%   |
| 6.5.7   | 1         | 0.53%   |
| 6.5.6   | 1         | 0.53%   |
| 6.5.10  | 1         | 0.53%   |
| 6.4.8   | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 12.77%  |
| 6.1     | 19        | 10.11%  |
| 5.8     | 18        | 9.57%   |
| 6.3     | 17        | 9.04%   |
| 5.13    | 16        | 8.51%   |
| 5.10    | 15        | 7.98%   |
| 5.18    | 12        | 6.38%   |
| 5.12    | 9         | 4.79%   |
| 6.5     | 7         | 3.72%   |
| 5.4     | 7         | 3.72%   |
| 6.0     | 6         | 3.19%   |
| 5.3     | 5         | 2.66%   |
| 5.19    | 5         | 2.66%   |
| 5.11    | 5         | 2.66%   |
| 5.9     | 4         | 2.13%   |
| 5.16    | 4         | 2.13%   |
| 4.19    | 4         | 2.13%   |
| 6.2     | 2         | 1.06%   |
| 6.4     | 1         | 0.53%   |
| 5.7     | 1         | 0.53%   |
| 5.6     | 1         | 0.53%   |
| 5.2     | 1         | 0.53%   |
| 5.17    | 1         | 0.53%   |
| 5.14    | 1         | 0.53%   |
| 5.1     | 1         | 0.53%   |
| 4.4     | 1         | 0.53%   |
| 4.14    | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 164       | 93.18%  |
| i686    | 6         | 3.41%   |
| aarch64 | 3         | 1.7%    |
| ppc64le | 1         | 0.57%   |
| ppc64   | 1         | 0.57%   |
| armv7l  | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 76        | 41.76%  |
| XFCE         | 26        | 14.29%  |
| KDE5         | 14        | 7.69%   |
| KDE          | 12        | 6.59%   |
| GNOME        | 10        | 5.49%   |
| MATE         | 9         | 4.95%   |
| X-Cinnamon   | 6         | 3.3%    |
| i3           | 6         | 3.3%    |
| sway         | 5         | 2.75%   |
| bspwm        | 4         | 2.2%    |
| awesome      | 4         | 2.2%    |
| openbox      | 3         | 1.65%   |
| Lumina       | 2         | 1.1%    |
| river        | 1         | 0.55%   |
| LXQt         | 1         | 0.55%   |
| LXDE         | 1         | 0.55%   |
| dwm          | 1         | 0.55%   |
| dot-xsession | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 127       | 70.56%  |
| Wayland | 21        | 11.67%  |
| Tty     | 19        | 10.56%  |
| Unknown | 13        | 7.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 137       | 76.11%  |
| LightDM | 19        | 10.56%  |
| SDDM    | 11        | 6.11%   |
| LXDM    | 8         | 4.44%   |
| GDM     | 3         | 1.67%   |
| SLiM    | 1         | 0.56%   |
| LDM     | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 95        | 52.2%   |
| Unknown | 22        | 12.09%  |
| en_GB   | 11        | 6.04%   |
| en_DK   | 6         | 3.3%    |
| ru_RU   | 5         | 2.75%   |
| de_DE   | 5         | 2.75%   |
| it_IT   | 4         | 2.2%    |
| fr_FR   | 4         | 2.2%    |
| es_ES   | 4         | 2.2%    |
| cs_CZ   | 3         | 1.65%   |
| pt_BR   | 2         | 1.1%    |
| pl_PL   | 2         | 1.1%    |
| en_CA   | 2         | 1.1%    |
| en_AU   | 2         | 1.1%    |
| el_GR   | 2         | 1.1%    |
| C       | 2         | 1.1%    |
| tr_TR   | 1         | 0.55%   |
| ru_UA   | 1         | 0.55%   |
| nb_NO   | 1         | 0.55%   |
| hu_HU   | 1         | 0.55%   |
| es_HN   | 1         | 0.55%   |
| es_DO   | 1         | 0.55%   |
| es_AR   | 1         | 0.55%   |
| en_NZ   | 1         | 0.55%   |
| en_IE   | 1         | 0.55%   |
| ca_ES   | 1         | 0.55%   |
| bg_BG   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 94        | 52.22%  |
| BIOS | 86        | 47.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 61.11%  |
| Btrfs   | 43        | 23.89%  |
| Zfs     | 9         | 5%      |
| Xfs     | 9         | 5%      |
| Unknown | 6         | 3.33%   |
| F2fs    | 2         | 1.11%   |
| Ext3    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 103       | 57.22%  |
| Unknown | 53        | 29.44%  |
| MBR     | 24        | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 154       | 87.5%   |
| Yes       | 22        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 140       | 78.21%  |
| Yes       | 39        | 21.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 36        | 20.45%  |
| Lenovo                  | 30        | 17.05%  |
| Hewlett-Packard         | 21        | 11.93%  |
| Dell                    | 16        | 9.09%   |
| Acer                    | 16        | 9.09%   |
| MSI                     | 14        | 7.95%   |
| ASRock                  | 8         | 4.55%   |
| Gigabyte Technology     | 7         | 3.98%   |
| Unknown                 | 6         | 3.41%   |
| Notebook                | 2         | 1.14%   |
| Microsoft               | 2         | 1.14%   |
| HUAWEI                  | 2         | 1.14%   |
| Timi                    | 1         | 0.57%   |
| Supermicro              | 1         | 0.57%   |
| Samsung Electronics     | 1         | 0.57%   |
| Raspberry Pi Foundation | 1         | 0.57%   |
| Positivo                | 1         | 0.57%   |
| Pine Microsystems       | 1         | 0.57%   |
| Nokia                   | 1         | 0.57%   |
| Google                  | 1         | 0.57%   |
| Getac                   | 1         | 0.57%   |
| Framework               | 1         | 0.57%   |
| Exo                     | 1         | 0.57%   |
| EVGA                    | 1         | 0.57%   |
| Digibras                | 1         | 0.57%   |
| Cisco Systems           | 1         | 0.57%   |
| Chuwi                   | 1         | 0.57%   |
| Apple                   | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 6         | 3.41%   |
| MSI MS-7C02                               | 2         | 1.14%   |
| HP Pavilion Notebook                      | 2         | 1.14%   |
| HP Laptop 15-bw0xx                        | 2         | 1.14%   |
| HP 15                                     | 2         | 1.14%   |
| Dell OptiPlex 780                         | 2         | 1.14%   |
| Dell OptiPlex 7010                        | 2         | 1.14%   |
| ASUS X751LD                               | 2         | 1.14%   |
| ASUS PRIME Z390-P                         | 2         | 1.14%   |
| Acer Swift SF314-42                       | 2         | 1.14%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.57%   |
| Supermicro Super Server                   | 1         | 0.57%   |
| Samsung 275E4E/275E5E                     | 1         | 0.57%   |
| RPi Raspberry Pi                          | 1         | 0.57%   |
| Positivo Mobile                           | 1         | 0.57%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.57%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.57%   |
| Notebook NH50_70RA                        | 1         | 0.57%   |
| Nokia Booklet 3G                          | 1         | 0.57%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.57%   |
| MSI MS-7D14                               | 1         | 0.57%   |
| MSI MS-7C92                               | 1         | 0.57%   |
| MSI MS-7C52                               | 1         | 0.57%   |
| MSI MS-7C35                               | 1         | 0.57%   |
| MSI MS-7B86                               | 1         | 0.57%   |
| MSI MS-7A68                               | 1         | 0.57%   |
| MSI MS-7A39                               | 1         | 0.57%   |
| MSI MS-7816                               | 1         | 0.57%   |
| MSI GV72 7RE                              | 1         | 0.57%   |
| MSI GF63 Thin 10SCXR                      | 1         | 0.57%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.57%   |
| Microsoft Surface with Windows RT         | 1         | 0.57%   |
| Microsoft Surface Go 2                    | 1         | 0.57%   |
| Lenovo Yoga 720-15IKB 80X7                | 1         | 0.57%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.57%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.57%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LD001HUS    | 1         | 0.57%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 17        | 9.66%   |
| Acer Aspire              | 9         | 5.11%   |
| Lenovo IdeaPad           | 8         | 4.55%   |
| ASUS PRIME               | 8         | 4.55%   |
| ASUS VivoBook            | 7         | 3.98%   |
| Unknown                  | 6         | 3.41%   |
| HP Laptop                | 5         | 2.84%   |
| Dell OptiPlex            | 5         | 2.84%   |
| HP Pavilion              | 4         | 2.27%   |
| Dell Latitude            | 4         | 2.27%   |
| Dell Inspiron            | 4         | 2.27%   |
| MSI MS-7C02              | 2         | 1.14%   |
| Microsoft Surface        | 2         | 1.14%   |
| HP Stream                | 2         | 1.14%   |
| HP ENVY                  | 2         | 1.14%   |
| HP 255                   | 2         | 1.14%   |
| HP 15                    | 2         | 1.14%   |
| ASUS X751LD              | 2         | 1.14%   |
| ASUS TUF                 | 2         | 1.14%   |
| ASUS ROG                 | 2         | 1.14%   |
| Acer Swift               | 2         | 1.14%   |
| Timi Redmi               | 1         | 0.57%   |
| Supermicro Super         | 1         | 0.57%   |
| Samsung 275E4E           | 1         | 0.57%   |
| RPi Raspberry            | 1         | 0.57%   |
| Positivo Mobile          | 1         | 0.57%   |
| Pine Microsystems Pine64 | 1         | 0.57%   |
| Notebook NV4XMB          | 1         | 0.57%   |
| Notebook NH50            | 1         | 0.57%   |
| Nokia Booklet            | 1         | 0.57%   |
| MSI Summit               | 1         | 0.57%   |
| MSI MS-7D14              | 1         | 0.57%   |
| MSI MS-7C92              | 1         | 0.57%   |
| MSI MS-7C52              | 1         | 0.57%   |
| MSI MS-7C35              | 1         | 0.57%   |
| MSI MS-7B86              | 1         | 0.57%   |
| MSI MS-7A68              | 1         | 0.57%   |
| MSI MS-7A39              | 1         | 0.57%   |
| MSI MS-7816              | 1         | 0.57%   |
| MSI GV72                 | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 27        | 15.34%  |
| 2020    | 20        | 11.36%  |
| 2018    | 20        | 11.36%  |
| 2013    | 14        | 7.95%   |
| 2017    | 13        | 7.39%   |
| 2016    | 10        | 5.68%   |
| 2014    | 10        | 5.68%   |
| 2022    | 9         | 5.11%   |
| 2021    | 9         | 5.11%   |
| 2012    | 9         | 5.11%   |
| 2015    | 8         | 4.55%   |
| 2011    | 8         | 4.55%   |
| 2010    | 5         | 2.84%   |
| Unknown | 5         | 2.84%   |
| 2009    | 2         | 1.14%   |
| 2008    | 2         | 1.14%   |
| 2005    | 2         | 1.14%   |
| 2023    | 1         | 0.57%   |
| 2007    | 1         | 0.57%   |
| 2006    | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 108       | 61.36%  |
| Desktop        | 56        | 31.82%  |
| Tablet         | 4         | 2.27%   |
| Convertible    | 4         | 2.27%   |
| Server         | 2         | 1.14%   |
| System on chip | 1         | 0.57%   |
| Mini pc        | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 176       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 99.43%  |
| Yes  | 1         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 39        | 21.91%  |
| 4.01-8.0        | 35        | 19.66%  |
| 8.01-16.0       | 31        | 17.42%  |
| 3.01-4.0        | 29        | 16.29%  |
| 32.01-64.0      | 22        | 12.36%  |
| 1.01-2.0        | 9         | 5.06%   |
| 24.01-32.0      | 4         | 2.25%   |
| 0.51-1.0        | 4         | 2.25%   |
| 64.01-256.0     | 2         | 1.12%   |
| More than 256.0 | 1         | 0.56%   |
| 2.01-3.0        | 1         | 0.56%   |
| 0.01-0.5        | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 57        | 30.48%  |
| 2.01-3.0    | 39        | 20.86%  |
| 4.01-8.0    | 24        | 12.83%  |
| 0.51-1.0    | 24        | 12.83%  |
| 3.01-4.0    | 20        | 10.7%   |
| 8.01-16.0   | 11        | 5.88%   |
| 0.01-0.5    | 8         | 4.28%   |
| 16.01-24.0  | 3         | 1.6%    |
| 64.01-256.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 61.24%  |
| 2      | 40        | 22.47%  |
| 3      | 19        | 10.67%  |
| 4      | 5         | 2.81%   |
| 5      | 3         | 1.69%   |
| 9      | 1         | 0.56%   |
| 0      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 78.98%  |
| Yes       | 37        | 21.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 79.66%  |
| No        | 36        | 20.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 72.32%  |
| No        | 49        | 27.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 62.71%  |
| No        | 66        | 37.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 38        | 21.59%  |
| Germany     | 16        | 9.09%   |
| Russia      | 15        | 8.52%   |
| India       | 10        | 5.68%   |
| Brazil      | 7         | 3.98%   |
| Czechia     | 6         | 3.41%   |
| UK          | 5         | 2.84%   |
| Poland      | 5         | 2.84%   |
| France      | 5         | 2.84%   |
| Denmark     | 5         | 2.84%   |
| Ukraine     | 4         | 2.27%   |
| Switzerland | 4         | 2.27%   |
| Netherlands | 4         | 2.27%   |
| Greece      | 4         | 2.27%   |
| Turkey      | 3         | 1.7%    |
| Spain       | 3         | 1.7%    |
| Italy       | 3         | 1.7%    |
| Bulgaria    | 3         | 1.7%    |
| Australia   | 3         | 1.7%    |
| Argentina   | 3         | 1.7%    |
| Serbia      | 2         | 1.14%   |
| Morocco     | 2         | 1.14%   |
| Finland     | 2         | 1.14%   |
| Canada      | 2         | 1.14%   |
| Vietnam     | 1         | 0.57%   |
| Uruguay     | 1         | 0.57%   |
| Thailand    | 1         | 0.57%   |
| Sweden      | 1         | 0.57%   |
| Portugal    | 1         | 0.57%   |
| Peru        | 1         | 0.57%   |
| Norway      | 1         | 0.57%   |
| Nigeria     | 1         | 0.57%   |
| New Zealand | 1         | 0.57%   |
| Mexico      | 1         | 0.57%   |
| Latvia      | 1         | 0.57%   |
| Indonesia   | 1         | 0.57%   |
| Hungary     | 1         | 0.57%   |
| Honduras    | 1         | 0.57%   |
| Guatemala   | 1         | 0.57%   |
| Grenada     | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 5         | 2.76%   |
| Moscow             | 5         | 2.76%   |
| St Petersburg      | 3         | 1.66%   |
| Denver             | 3         | 1.66%   |
| Amsterdam          | 3         | 1.66%   |
| Spring Hill        | 2         | 1.1%    |
| Sofia              | 2         | 1.1%    |
| Rome               | 2         | 1.1%    |
| Orlando            | 2         | 1.1%    |
| Munich             | 2         | 1.1%    |
| Meknes             | 2         | 1.1%    |
| Lublin             | 2         | 1.1%    |
| Ioannina           | 2         | 1.1%    |
| Hyderabad          | 2         | 1.1%    |
| Geneva             | 2         | 1.1%    |
| Zagnansk           | 1         | 0.55%   |
| Yekaterinburg      | 1         | 0.55%   |
| Yambol             | 1         | 0.55%   |
| Worthing           | 1         | 0.55%   |
| Wilen bei Wollerau | 1         | 0.55%   |
| Weatherford        | 1         | 0.55%   |
| Warsaw             | 1         | 0.55%   |
| Volgograd          | 1         | 0.55%   |
| Vlaardingen        | 1         | 0.55%   |
| Vienna             | 1         | 0.55%   |
| Viby J             | 1         | 0.55%   |
| Varna              | 1         | 0.55%   |
| Trujillo           | 1         | 0.55%   |
| Toulouse           | 1         | 0.55%   |
| Touget             | 1         | 0.55%   |
| Toms River         | 1         | 0.55%   |
| Tegucigalpa        | 1         | 0.55%   |
| Syktyvkar          | 1         | 0.55%   |
| Sydney             | 1         | 0.55%   |
| Surabaya           | 1         | 0.55%   |
| Sun Prairie        | 1         | 0.55%   |
| Stratford          | 1         | 0.55%   |
| South Shields      | 1         | 0.55%   |
| Solone             | 1         | 0.55%   |
| Sohren             | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 51        | 68     | 19.84%  |
| Seagate                     | 40        | 49     | 15.56%  |
| WDC                         | 36        | 45     | 14.01%  |
| Kingston                    | 17        | 18     | 6.61%   |
| Unknown                     | 15        | 22     | 5.84%   |
| Sandisk                     | 14        | 17     | 5.45%   |
| Toshiba                     | 9         | 10     | 3.5%    |
| Intel                       | 9         | 11     | 3.5%    |
| HGST                        | 9         | 10     | 3.5%    |
| Crucial                     | 9         | 10     | 3.5%    |
| SK hynix                    | 8         | 9      | 3.11%   |
| Hitachi                     | 7         | 7      | 2.72%   |
| Phison                      | 3         | 3      | 1.17%   |
| Micron Technology           | 3         | 4      | 1.17%   |
| Patriot                     | 2         | 2      | 0.78%   |
| Micron/Crucial Technology   | 2         | 2      | 0.78%   |
| Kingston Technology Company | 2         | 3      | 0.78%   |
| Corsair                     | 2         | 2      | 0.78%   |
| A-DATA Technology           | 2         | 3      | 0.78%   |
| XPG                         | 1         | 4      | 0.39%   |
| Transcend                   | 1         | 1      | 0.39%   |
| SPCC                        | 1         | 1      | 0.39%   |
| PNY                         | 1         | 1      | 0.39%   |
| Phison Electronics          | 1         | 1      | 0.39%   |
| ORIGIN                      | 1         | 1      | 0.39%   |
| OCZ                         | 1         | 1      | 0.39%   |
| Maxtor                      | 1         | 1      | 0.39%   |
| LITEONIT                    | 1         | 1      | 0.39%   |
| Lenovo                      | 1         | 1      | 0.39%   |
| KIOXIA                      | 1         | 1      | 0.39%   |
| INNOVATION IT               | 1         | 1      | 0.39%   |
| IBM/Hitachi                 | 1         | 1      | 0.39%   |
| Gigabyte Technology         | 1         | 2      | 0.39%   |
| China                       | 1         | 1      | 0.39%   |
| BHT                         | 1         | 1      | 0.39%   |
| Apple                       | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                            | 6         | 2.13%   |
| Kingston SA400S37240G 240GB SSD                   | 6         | 2.13%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 1.77%   |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 1.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 4         | 1.42%   |
| Seagate ST1000DM010-2EP102 1TB                    | 4         | 1.42%   |
| Samsung SSD 870 EVO 500GB                         | 4         | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.42%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3         | 1.06%   |
| Unknown MMC Card  64GB                            | 3         | 1.06%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 1.06%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                | 3         | 1.06%   |
| Samsung NVMe SSD Drive 1TB                        | 3         | 1.06%   |
| Kingston SHFS37A120G 120GB SSD                    | 3         | 1.06%   |
| HGST HTS545050A7E680 500GB                        | 3         | 1.06%   |
| Crucial CT500MX500SSD1 500GB                      | 3         | 1.06%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.71%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.71%   |
| Unknown MMC Card  128GB                           | 2         | 0.71%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.71%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1024GB        | 2         | 0.71%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.71%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB                    | 2         | 0.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 2         | 0.71%   |
| Samsung SSD 980 PRO 500GB                         | 2         | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB                      | 2         | 0.71%   |
| Samsung SSD 870 QVO 1TB                           | 2         | 0.71%   |
| Samsung SSD 870 EVO 1TB                           | 2         | 0.71%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.71%   |
| Samsung SSD 860 EVO 4TB                           | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB                         | 2         | 0.71%   |
| Samsung NVMe SSD Drive 500GB                      | 2         | 0.71%   |
| Patriot Burst 120GB SSD                           | 2         | 0.71%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.71%   |
| Intel SSDPEKNW512G8 512GB                         | 2         | 0.71%   |
| HGST HTS541010B7E610 1TB                          | 2         | 0.71%   |
| HGST HTS541010A9E680 1TB                          | 2         | 0.71%   |
| XPG NVMe SSD Drive 2TB                            | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 49     | 38.83%  |
| WDC                 | 30        | 37     | 29.13%  |
| HGST                | 9         | 10     | 8.74%   |
| Toshiba             | 8         | 9      | 7.77%   |
| Hitachi             | 7         | 7      | 6.8%    |
| Samsung Electronics | 6         | 7      | 5.83%   |
| Unknown             | 1         | 1      | 0.97%   |
| Maxtor              | 1         | 1      | 0.97%   |
| IBM/Hitachi         | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 25     | 29.73%  |
| Kingston            | 16        | 17     | 21.62%  |
| Crucial             | 7         | 8      | 9.46%   |
| SanDisk             | 6         | 7      | 8.11%   |
| WDC                 | 4         | 4      | 5.41%   |
| Patriot             | 2         | 2      | 2.7%    |
| Intel               | 2         | 2      | 2.7%    |
| Transcend           | 1         | 1      | 1.35%   |
| SPCC                | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| PNY                 | 1         | 1      | 1.35%   |
| ORIGIN              | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| LITEONIT            | 1         | 1      | 1.35%   |
| Lenovo              | 1         | 1      | 1.35%   |
| INNOVATION IT       | 1         | 1      | 1.35%   |
| Gigabyte Technology | 1         | 2      | 1.35%   |
| Corsair             | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| BHT                 | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 2      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 86        | 122    | 36.75%  |
| NVMe    | 66        | 90     | 28.21%  |
| SSD     | 66        | 82     | 28.21%  |
| MMC     | 14        | 19     | 5.98%   |
| Unknown | 2         | 3      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 124       | 200    | 59.05%  |
| NVMe | 66        | 90     | 31.43%  |
| MMC  | 14        | 19     | 6.67%   |
| SAS  | 6         | 7      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 107    | 52.17%  |
| 0.51-1.0   | 57        | 69     | 35.4%   |
| 1.01-2.0   | 15        | 22     | 9.32%   |
| 3.01-4.0   | 2         | 3      | 1.24%   |
| 4.01-10.0  | 2         | 2      | 1.24%   |
| 2.01-3.0   | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 46        | 25.56%  |
| 501-1000       | 37        | 20.56%  |
| 101-250        | 33        | 18.33%  |
| 1001-2000      | 13        | 7.22%   |
| Unknown        | 12        | 6.67%   |
| More than 3000 | 11        | 6.11%   |
| 1-20           | 10        | 5.56%   |
| 51-100         | 7         | 3.89%   |
| 21-50          | 6         | 3.33%   |
| 2001-3000      | 5         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 53        | 28.34%  |
| 101-250        | 40        | 21.39%  |
| 21-50          | 24        | 12.83%  |
| 251-500        | 18        | 9.63%   |
| 51-100         | 18        | 9.63%   |
| Unknown        | 12        | 6.42%   |
| 1001-2000      | 9         | 4.81%   |
| 501-1000       | 7         | 3.74%   |
| More than 3000 | 4         | 2.14%   |
| 2001-3000      | 2         | 1.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 5.88%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 5.88%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 2.94%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 2.94%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 2.94%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 2.94%   |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 2.94%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.94%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 2.94%   |
| Seagate ST3750330AS 752GB             | 1         | 1      | 2.94%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 2.94%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 2      | 2.94%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 2.94%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 2.94%   |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 2.94%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 2.94%   |
| Hitachi HUA722010CLA330 1TB           | 1         | 1      | 2.94%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 2.94%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.94%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.94%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 2.94%   |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 39.39%  |
| WDC                 | 4         | 5      | 12.12%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| Hitachi             | 4         | 4      | 12.12%  |
| HGST                | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 3      | 6.06%   |
| IBM/Hitachi         | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 43.33%  |
| WDC                 | 4         | 5      | 13.33%  |
| Hitachi             | 4         | 4      | 13.33%  |
| Samsung Electronics | 3         | 3      | 10%     |
| HGST                | 3         | 3      | 10%     |
| Toshiba             | 2         | 3      | 6.67%   |
| IBM/Hitachi         | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 34     | 90.63%  |
| SSD  | 3         | 3      | 9.38%   |

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
| Works    | 101       | 153    | 49.75%  |
| Detected | 71        | 126    | 34.98%  |
| Malfunc  | 31        | 37     | 15.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 43.89%  |
| AMD                              | 48        | 21.72%  |
| Samsung Electronics              | 30        | 13.57%  |
| SanDisk                          | 10        | 4.52%   |
| SK hynix                         | 7         | 3.17%   |
| Phison Electronics               | 5         | 2.26%   |
| ASMedia Technology               | 4         | 1.81%   |
| Micron/Crucial Technology        | 3         | 1.36%   |
| Micron Technology                | 3         | 1.36%   |
| Kingston Technology Company      | 3         | 1.36%   |
| Marvell Technology Group         | 2         | 0.9%    |
| ADATA Technology                 | 2         | 0.9%    |
| Toshiba America Info Systems     | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |
| LSI Logic / Symbios Logic        | 1         | 0.45%   |
| KIOXIA                           | 1         | 0.45%   |
| JMicron Technology               | 1         | 0.45%   |
| Broadcom                         | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 13.77%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 6.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 4.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 4.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 4.05%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 6         | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.21%   |
| Intel SSD 660P Series                                                          | 3         | 1.21%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.21%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.81%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.81%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.81%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 0.81%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 125       | 56.31%  |
| NVMe | 67        | 30.18%  |
| IDE  | 16        | 7.21%   |
| RAID | 14        | 6.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 111       | 63.07%  |
| AMD                      | 59        | 33.52%  |
| ARM                      | 4         | 2.27%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.57%   |
| PowerMac11,2             | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 5         | 2.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 3         | 1.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 1.7%    |
| ARM Processor                                      | 3         | 1.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 3         | 1.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 2         | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.14%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 2         | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 2         | 1.14%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 2         | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 1.14%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 2         | 1.14%   |
| Intel Core i3-4030U CPU @ 1.90GHz                  | 2         | 1.14%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 2         | 1.14%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 2         | 1.14%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 2         | 1.14%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.14%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2         | 1.14%   |
| AMD Ryzen 5 5600H with Radeon Graphics             | 2         | 1.14%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 2         | 1.14%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.14%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx      | 2         | 1.14%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.14%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.14%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.57%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.57%   |
| Intel Xeon E-2146G CPU @ 3.50GHz                   | 1         | 0.57%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.57%   |
| Intel Pentium M processor 2.13GHz                  | 1         | 0.57%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz             | 1         | 0.57%   |
| Intel Pentium CPU N3710 @ 1.60GHz                  | 1         | 0.57%   |
| Intel Pentium CPU N3520 @ 2.16GHz                  | 1         | 0.57%   |
| Intel Pentium CPU G2030 @ 3.00GHz                  | 1         | 0.57%   |
| Intel Pentium CPU 4425Y @ 1.70GHz                  | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 17.61%  |
| Intel Core i7           | 25        | 14.2%   |
| AMD Ryzen 5             | 21        | 11.93%  |
| Other                   | 18        | 10.23%  |
| Intel Core i3           | 16        | 9.09%   |
| AMD Ryzen 7             | 13        | 7.39%   |
| Intel Celeron           | 8         | 4.55%   |
| Intel Atom              | 7         | 3.98%   |
| Intel Pentium           | 4         | 2.27%   |
| AMD Ryzen 7 PRO         | 3         | 1.7%    |
| AMD FX                  | 3         | 1.7%    |
| Intel Xeon              | 2         | 1.14%   |
| Intel Core i9           | 2         | 1.14%   |
| Intel Core 2 Duo        | 2         | 1.14%   |
| AMD Ryzen 3             | 2         | 1.14%   |
| AMD A8                  | 2         | 1.14%   |
| Intel Pentium M         | 1         | 0.57%   |
| Intel Pentium Gold      | 1         | 0.57%   |
| Intel Pentium 4         | 1         | 0.57%   |
| Intel Genuine           | 1         | 0.57%   |
| Intel Core 2 Quad       | 1         | 0.57%   |
| AMD Turion 64 X2 Mobile | 1         | 0.57%   |
| AMD Ryzen Threadripper  | 1         | 0.57%   |
| AMD Ryzen 9             | 1         | 0.57%   |
| AMD Ryzen 5 PRO         | 1         | 0.57%   |
| AMD Phenom II X4        | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E1                  | 1         | 0.57%   |
| AMD C-60                | 1         | 0.57%   |
| AMD Athlon II X3        | 1         | 0.57%   |
| AMD Athlon II X2        | 1         | 0.57%   |
| AMD A6                  | 1         | 0.57%   |
| AMD A4                  | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 61        | 34.66%  |
| 2       | 55        | 31.25%  |
| 6       | 28        | 15.91%  |
| 8       | 16        | 9.09%   |
| 1       | 7         | 3.98%   |
| 14      | 2         | 1.14%   |
| 12      | 2         | 1.14%   |
| 64      | 1         | 0.57%   |
| 24      | 1         | 0.57%   |
| 10      | 1         | 0.57%   |
| 3       | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 173       | 98.3%   |
| 2       | 2         | 1.14%   |
| Unknown | 1         | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 121       | 68.75%  |
| 1       | 53        | 30.11%  |
| 4       | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 161       | 91.48%  |
| Unknown        | 8         | 4.55%   |
| 32-bit         | 4         | 2.27%   |
| 64-bit         | 3         | 1.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 38.12%  |
| 0x40651    | 8         | 4.42%   |
| 0x306a9    | 7         | 3.87%   |
| 0x906e9    | 5         | 2.76%   |
| 0x906ea    | 4         | 2.21%   |
| 0x806ec    | 4         | 2.21%   |
| 0x806e9    | 4         | 2.21%   |
| 0x406e3    | 4         | 2.21%   |
| 0x08108102 | 4         | 2.21%   |
| 0x806ea    | 3         | 1.66%   |
| 0x30678    | 3         | 1.66%   |
| 0x206a7    | 3         | 1.66%   |
| 0x0a50000c | 3         | 1.66%   |
| 0x08600104 | 3         | 1.66%   |
| 0x906a3    | 2         | 1.1%    |
| 0x506e3    | 2         | 1.1%    |
| 0x106c2    | 2         | 1.1%    |
| 0x0a201009 | 2         | 1.1%    |
| 0x08701021 | 2         | 1.1%    |
| 0x0800820d | 2         | 1.1%    |
| 0x07030105 | 2         | 1.1%    |
| 0x06006705 | 2         | 1.1%    |
| 0x06000852 | 2         | 1.1%    |
| 0x05000119 | 2         | 1.1%    |
| 0x010000c8 | 2         | 1.1%    |
| 0xa0671    | 1         | 0.55%   |
| 0xa0652    | 1         | 0.55%   |
| 0x906ed    | 1         | 0.55%   |
| 0x90675    | 1         | 0.55%   |
| 0x90672    | 1         | 0.55%   |
| 0x806eb    | 1         | 0.55%   |
| 0x806c1    | 1         | 0.55%   |
| 0x706e5    | 1         | 0.55%   |
| 0x706a1    | 1         | 0.55%   |
| 0x406c4    | 1         | 0.55%   |
| 0x306d4    | 1         | 0.55%   |
| 0x306c3    | 1         | 0.55%   |
| 0x30673    | 1         | 0.55%   |
| 0x20652    | 1         | 0.55%   |
| 0x106ca    | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 19.89%  |
| Haswell          | 13        | 7.39%   |
| Zen 3            | 12        | 6.82%   |
| Zen 2            | 12        | 6.82%   |
| Unknown          | 11        | 6.25%   |
| IvyBridge        | 10        | 5.68%   |
| Zen+             | 9         | 5.11%   |
| Skylake          | 8         | 4.55%   |
| Silvermont       | 7         | 3.98%   |
| Zen              | 5         | 2.84%   |
| SandyBridge      | 5         | 2.84%   |
| Alderlake Hybrid | 5         | 2.84%   |
| Excavator        | 4         | 2.27%   |
| TigerLake        | 3         | 1.7%    |
| Puma             | 3         | 1.7%    |
| Piledriver       | 3         | 1.7%    |
| Penryn           | 3         | 1.7%    |
| K10              | 3         | 1.7%    |
| IceLake          | 3         | 1.7%    |
| Goldmont plus    | 3         | 1.7%    |
| Broadwell        | 3         | 1.7%    |
| Bonnell          | 3         | 1.7%    |
| Core             | 2         | 1.14%   |
| CometLake        | 2         | 1.14%   |
| Bobcat           | 2         | 1.14%   |
| Westmere         | 1         | 0.57%   |
| P6               | 1         | 0.57%   |
| NetBurst         | 1         | 0.57%   |
| Nehalem          | 1         | 0.57%   |
| K8 Hammer        | 1         | 0.57%   |
| Jaguar           | 1         | 0.57%   |
| Goldmont         | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 88        | 42.11%  |
| Nvidia                           | 60        | 28.71%  |
| AMD                              | 57        | 27.27%  |
| ASPEED Technology                | 2         | 0.96%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Matrox Electronics Systems       | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 2.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 2.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 2.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.31%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.39%   |
| Intel HD Graphics 630                                                                    | 3         | 1.39%   |
| Intel HD Graphics 620                                                                    | 3         | 1.39%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.39%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3         | 1.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.93%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.93%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 31.84%  |
| 1 x AMD        | 49        | 27.37%  |
| 1 x Nvidia     | 29        | 16.2%   |
| Intel + Nvidia | 26        | 14.53%  |
| Other          | 5         | 2.79%   |
| AMD + Nvidia   | 3         | 1.68%   |
| 2 x Nvidia     | 2         | 1.12%   |
| 2 x AMD        | 2         | 1.12%   |
| AMD + ASPEED   | 2         | 1.12%   |
| 2 x Intel      | 1         | 0.56%   |
| 1 x SiS        | 1         | 0.56%   |
| 1 x Matrox     | 1         | 0.56%   |
| Intel + AMD    | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 125       | 69.83%  |
| Proprietary | 49        | 27.37%  |
| Unknown     | 5         | 2.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 56.83%  |
| 1.01-2.0   | 19        | 10.38%  |
| 3.01-4.0   | 17        | 9.29%   |
| 0.01-0.5   | 15        | 8.2%    |
| 0.51-1.0   | 9         | 4.92%   |
| 7.01-8.0   | 7         | 3.83%   |
| 5.01-6.0   | 5         | 2.73%   |
| 8.01-16.0  | 3         | 1.64%   |
| 2.01-3.0   | 2         | 1.09%   |
| 16.01-24.0 | 2         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 27        | 14.44%  |
| AU Optronics         | 25        | 13.37%  |
| BOE                  | 19        | 10.16%  |
| Samsung Electronics  | 17        | 9.09%   |
| LG Display           | 16        | 8.56%   |
| Hewlett-Packard      | 9         | 4.81%   |
| Dell                 | 9         | 4.81%   |
| Goldstar             | 6         | 3.21%   |
| Iiyama               | 5         | 2.67%   |
| Acer                 | 5         | 2.67%   |
| Philips              | 4         | 2.14%   |
| BenQ                 | 4         | 2.14%   |
| PANDA                | 3         | 1.6%    |
| Lenovo               | 3         | 1.6%    |
| ASUSTek Computer     | 3         | 1.6%    |
| Apple                | 3         | 1.6%    |
| AOC                  | 3         | 1.6%    |
| Sharp                | 2         | 1.07%   |
| LG Philips           | 2         | 1.07%   |
| Fujitsu Siemens      | 2         | 1.07%   |
| Ancor Communications | 2         | 1.07%   |
| Vizio                | 1         | 0.53%   |
| Unknown              | 1         | 0.53%   |
| TMX                  | 1         | 0.53%   |
| STD                  | 1         | 0.53%   |
| Sceptre Tech         | 1         | 0.53%   |
| Sceptre              | 1         | 0.53%   |
| Quanta Display       | 1         | 0.53%   |
| Panasonic            | 1         | 0.53%   |
| ONN                  | 1         | 0.53%   |
| MSI                  | 1         | 0.53%   |
| InnoLux Display      | 1         | 0.53%   |
| Idek Iiyama          | 1         | 0.53%   |
| Huion                | 1         | 0.53%   |
| Gigabyte Technology  | 1         | 0.53%   |
| FUN                  | 1         | 0.53%   |
| CHR                  | 1         | 0.53%   |
| BOE Technology Group | 1         | 0.53%   |
| Unknown              | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.55%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.55%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.03%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 2         | 1.03%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 1.03%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.03%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1         | 0.52%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.52%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.52%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.52%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.52%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 0.52%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.52%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 477x268mm 21.5-inch  | 1         | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.52%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.52%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.52%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.52%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor LC49G95T 7040x1440                    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor C49HG9x                               | 1         | 0.52%   |
| Samsung Electronics LCD Monitor C24F390 3840x1080                     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor C24F390                               | 1         | 0.52%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch    | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 41.44%  |
| 1366x768 (WXGA)    | 37        | 20.44%  |
| 3840x2160 (4K)     | 9         | 4.97%   |
| 1920x1200 (WUXGA)  | 9         | 4.97%   |
| 2560x1440 (QHD)    | 8         | 4.42%   |
| 1600x900 (HD+)     | 5         | 2.76%   |
| 3440x1440          | 4         | 2.21%   |
| 1680x1050 (WSXGA+) | 4         | 2.21%   |
| Unknown            | 4         | 2.21%   |
| 2160x1440          | 3         | 1.66%   |
| 1280x800 (WXGA)    | 3         | 1.66%   |
| 2560x1600          | 2         | 1.1%    |
| 2560x1080          | 2         | 1.1%    |
| 1280x1024 (SXGA)   | 2         | 1.1%    |
| 1024x600           | 2         | 1.1%    |
| 7680x1080          | 1         | 0.55%   |
| 7040x1440          | 1         | 0.55%   |
| 3840x1600          | 1         | 0.55%   |
| 3840x1080          | 1         | 0.55%   |
| 3200x2000          | 1         | 0.55%   |
| 2880x1800          | 1         | 0.55%   |
| 2288x1287          | 1         | 0.55%   |
| 2256x1504          | 1         | 0.55%   |
| 1920x1280          | 1         | 0.55%   |
| 1360x768           | 1         | 0.55%   |
| 1280x720 (HD)      | 1         | 0.55%   |
| 1024x768 (XGA)     | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 25.81%  |
| 14      | 21        | 11.29%  |
| 24      | 18        | 9.68%   |
| 13      | 15        | 8.06%   |
| Unknown | 15        | 8.06%   |
| 21      | 9         | 4.84%   |
| 27      | 8         | 4.3%    |
| 23      | 8         | 4.3%    |
| 17      | 6         | 3.23%   |
| 34      | 5         | 2.69%   |
| 11      | 5         | 2.69%   |
| 22      | 4         | 2.15%   |
| 12      | 4         | 2.15%   |
| 10      | 3         | 1.61%   |
| 31      | 2         | 1.08%   |
| 28      | 2         | 1.08%   |
| 19      | 2         | 1.08%   |
| 16      | 2         | 1.08%   |
| 84      | 1         | 0.54%   |
| 40      | 1         | 0.54%   |
| 39      | 1         | 0.54%   |
| 37      | 1         | 0.54%   |
| 33      | 1         | 0.54%   |
| 25      | 1         | 0.54%   |
| 20      | 1         | 0.54%   |
| 18      | 1         | 0.54%   |
| 8       | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 41.08%  |
| 501-600     | 33        | 17.84%  |
| 201-300     | 23        | 12.43%  |
| 401-500     | 16        | 8.65%   |
| Unknown     | 15        | 8.11%   |
| 701-800     | 6         | 3.24%   |
| 351-400     | 6         | 3.24%   |
| 601-700     | 5         | 2.7%    |
| 801-900     | 3         | 1.62%   |
| 1501-2000   | 1         | 0.54%   |
| 101-200     | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 70.52%  |
| 16/10   | 21        | 12.14%  |
| Unknown | 14        | 8.09%   |
| 21/9    | 7         | 4.05%   |
| 3/2     | 6         | 3.47%   |
| 5/4     | 2         | 1.16%   |
| 4/3     | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 25.41%  |
| 201-250        | 28        | 15.14%  |
| 81-90          | 27        | 14.59%  |
| Unknown        | 15        | 8.11%   |
| 251-300        | 12        | 6.49%   |
| 351-500        | 9         | 4.86%   |
| 301-350        | 8         | 4.32%   |
| 71-80          | 7         | 3.78%   |
| 51-60          | 6         | 3.24%   |
| 61-70          | 4         | 2.16%   |
| 151-200        | 3         | 1.62%   |
| 121-130        | 3         | 1.62%   |
| 111-120        | 3         | 1.62%   |
| 501-1000       | 3         | 1.62%   |
| 41-50          | 2         | 1.08%   |
| 141-150        | 2         | 1.08%   |
| 131-140        | 2         | 1.08%   |
| 91-100         | 2         | 1.08%   |
| More than 1000 | 1         | 0.54%   |
| 1-40           | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 52        | 27.96%  |
| 51-100        | 51        | 27.42%  |
| 101-120       | 47        | 25.27%  |
| 161-240       | 17        | 9.14%   |
| Unknown       | 15        | 8.06%   |
| More than 240 | 3         | 1.61%   |
| 1-50          | 1         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 145       | 81.46%  |
| 2     | 30        | 16.85%  |
| 0     | 3         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 97        | 38.34%  |
| Intel                            | 75        | 29.64%  |
| Qualcomm Atheros                 | 23        | 9.09%   |
| Broadcom                         | 15        | 5.93%   |
| Ralink Technology                | 5         | 1.98%   |
| TP-Link                          | 4         | 1.58%   |
| MediaTek                         | 4         | 1.58%   |
| Broadcom Limited                 | 4         | 1.58%   |
| Xiaomi                           | 3         | 1.19%   |
| Sierra Wireless                  | 3         | 1.19%   |
| Qualcomm Atheros Communications  | 2         | 0.79%   |
| Cypress Semiconductor            | 2         | 0.79%   |
| Tenda                            | 1         | 0.4%    |
| STMicroelectronics               | 1         | 0.4%    |
| Standard Microsystems            | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Ralink                           | 1         | 0.4%    |
| Qualcomm                         | 1         | 0.4%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.4%    |
| Nvidia                           | 1         | 0.4%    |
| Marvell Technology Group         | 1         | 0.4%    |
| Huawei Technologies              | 1         | 0.4%    |
| DisplayLink                      | 1         | 0.4%    |
| ASUSTek Computer                 | 1         | 0.4%    |
| ASIX Electronics                 | 1         | 0.4%    |
| Arduino SA                       | 1         | 0.4%    |
| Aquantia                         | 1         | 0.4%    |
| Apple                            | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 21.5%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 4.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.44%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.02%   |
| Intel Wireless 8260                                               | 3         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.68%   |
| Intel Wireless 7265                                               | 2         | 0.68%   |
| Intel Wireless 7260                                               | 2         | 0.68%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.68%   |
| Cypress K38231_03                                                 | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 43.07%  |
| Realtek Semiconductor           | 27        | 19.71%  |
| Qualcomm Atheros                | 19        | 13.87%  |
| Broadcom                        | 9         | 6.57%   |
| Ralink Technology               | 5         | 3.65%   |
| TP-Link                         | 3         | 2.19%   |
| Sierra Wireless                 | 3         | 2.19%   |
| MediaTek                        | 3         | 2.19%   |
| Broadcom Limited                | 3         | 2.19%   |
| Qualcomm Atheros Communications | 2         | 1.46%   |
| Tenda                           | 1         | 0.73%   |
| Ralink                          | 1         | 0.73%   |
| Qualcomm                        | 1         | 0.73%   |
| ASUSTek Computer                | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 14        | 10.22%  |
| Intel Wireless 8265 / 8275                                    | 8         | 5.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 5.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.65%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 3.65%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 2.19%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 3         | 2.19%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 2.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 2.19%   |
| Intel Wireless 8260                                           | 3         | 2.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 2.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.46%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 1.46%   |
| Intel Wireless 7265                                           | 2         | 1.46%   |
| Intel Wireless 7260                                           | 2         | 1.46%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.46%   |
| Broadcom BCM4311 802.11b/g WLAN                               | 2         | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1         | 0.73%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.73%   |
| TP-Link 802.11 NIC                                            | 1         | 0.73%   |
| Tenda U12                                                     | 1         | 0.73%   |
| Sierra Wireless EM7455                                        | 1         | 0.73%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.73%   |
| Sierra Wireless EM7305 Modem                                  | 1         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.73%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 88        | 58.28%  |
| Intel                            | 34        | 22.52%  |
| Broadcom                         | 7         | 4.64%   |
| Qualcomm Atheros                 | 5         | 3.31%   |
| Xiaomi                           | 3         | 1.99%   |
| Cypress Semiconductor            | 2         | 1.32%   |
| TP-Link                          | 1         | 0.66%   |
| Standard Microsystems            | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Nvidia                           | 1         | 0.66%   |
| MediaTek                         | 1         | 0.66%   |
| Marvell Technology Group         | 1         | 0.66%   |
| Huawei Technologies              | 1         | 0.66%   |
| DisplayLink                      | 1         | 0.66%   |
| Broadcom Limited                 | 1         | 0.66%   |
| ASIX Electronics                 | 1         | 0.66%   |
| Aquantia                         | 1         | 0.66%   |
| Apple                            | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 41.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.95%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.32%   |
| Cypress K38231_03                                                 | 2         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.66%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.66%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.66%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.66%   |
| MediaTek Wiko U316AT                                              | 1         | 0.66%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.66%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.66%   |
| Huawei ALP-AL00                                                   | 1         | 0.66%   |
| DisplayLink ThinkPad USB 3.0 Pro Dock                             | 1         | 0.66%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.66%   |
| Broadcom NetXtreme BCM5780 Gigabit Ethernet                       | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 141       | 51.65%  |
| WiFi     | 128       | 46.89%  |
| Modem    | 3         | 1.1%    |
| Unknown  | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 60%     |
| Ethernet | 70        | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 46.59%  |
| 2     | 77        | 43.75%  |
| 0     | 9         | 5.11%   |
| 3     | 7         | 3.98%   |
| 4     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 83.15%  |
| Yes  | 30        | 16.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 44.35%  |
| Realtek Semiconductor           | 16        | 13.91%  |
| Broadcom                        | 9         | 7.83%   |
| Cambridge Silicon Radio         | 8         | 6.96%   |
| Lite-On Technology              | 7         | 6.09%   |
| IMC Networks                    | 6         | 5.22%   |
| Qualcomm Atheros Communications | 4         | 3.48%   |
| Foxconn / Hon Hai               | 4         | 3.48%   |
| Realtek                         | 2         | 1.74%   |
| USI                             | 1         | 0.87%   |
| SIN                             | 1         | 0.87%   |
| Opticis                         | 1         | 0.87%   |
| Foxconn International           | 1         | 0.87%   |
| Dell                            | 1         | 0.87%   |
| ASUSTek Computer                | 1         | 0.87%   |
| Apple                           | 1         | 0.87%   |
| Actions                         | 1         | 0.87%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 13.04%  |
| Intel AX200 Bluetooth                               | 14        | 12.17%  |
| Realtek Bluetooth Radio                             | 9         | 7.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 6.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.09%   |
| Intel AX201 Bluetooth                               | 6         | 5.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2.61%   |
| Intel Bluetooth Device                              | 3         | 2.61%   |
| Intel AX210 Bluetooth                               | 3         | 2.61%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.61%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2.61%   |
| Realtek Bluetooth Radio                             | 2         | 1.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.74%   |
| IMC Networks Bluetooth Device                       | 2         | 1.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.74%   |
| USI Bluetooth Device                                | 1         | 0.87%   |
| SIN Bluetooth Keyboard                              | 1         | 0.87%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.87%   |
| Opticis Bluetooth Radio                             | 1         | 0.87%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.87%   |
| IMC Networks Wireless_Device                        | 1         | 0.87%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.87%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.87%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.87%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.87%   |
| Broadcom HP Portable Valentine                      | 1         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.87%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.87%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.87%   |
| Apple Bluetooth Host Controller                     | 1         | 0.87%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 105       | 42.68%  |
| AMD                                  | 64        | 26.02%  |
| Nvidia                               | 39        | 15.85%  |
| Logitech                             | 6         | 2.44%   |
| C-Media Electronics                  | 6         | 2.44%   |
| JMTek                                | 5         | 2.03%   |
| Texas Instruments                    | 2         | 0.81%   |
| Creative Technology                  | 2         | 0.81%   |
| VIA Technologies                     | 1         | 0.41%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.41%   |
| SteelSeries ApS                      | 1         | 0.41%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.41%   |
| SAVITECH                             | 1         | 0.41%   |
| Fry's Electronics                    | 1         | 0.41%   |
| Focusrite-Novation                   | 1         | 0.41%   |
| Elgato Systems                       | 1         | 0.41%   |
| EDFIER                               | 1         | 0.41%   |
| DCMT Technology                      | 1         | 0.41%   |
| Corsair                              | 1         | 0.41%   |
| Cambridge Audio                      | 1         | 0.41%   |
| Blue Microphones                     | 1         | 0.41%   |
| BEHRINGER International              | 1         | 0.41%   |
| Astro Gaming                         | 1         | 0.41%   |
| ASRock                               | 1         | 0.41%   |
| Apple                                | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 6.77%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 4.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 3.87%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.55%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 2.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 2.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.94%   |
| JMTek USB PnP Audio Device                                                 | 5         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.29%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.29%   |
| AMD High Definition Audio Controller                                       | 4         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.97%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.97%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 35        | 24.65%  |
| Samsung Electronics | 33        | 23.24%  |
| Micron Technology   | 14        | 9.86%   |
| Kingston            | 12        | 8.45%   |
| Unknown             | 10        | 7.04%   |
| G.Skill             | 8         | 5.63%   |
| Corsair             | 8         | 5.63%   |
| A-DATA Technology   | 6         | 4.23%   |
| Crucial             | 5         | 3.52%   |
| Ramaxel Technology  | 3         | 2.11%   |
| Unknown (ABCD)      | 1         | 0.7%    |
| Transcend           | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| Patriot             | 1         | 0.7%    |
| Elpida              | 1         | 0.7%    |
| Avant               | 1         | 0.7%    |
| 4ea5                | 1         | 0.7%    |
| 48spaces            | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 1.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.29%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 1.29%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.29%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.29%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.65%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.65%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.65%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.65%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.65%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 48.39%  |
| DDR3    | 44        | 35.48%  |
| LPDDR4  | 5         | 4.03%   |
| LPDDR3  | 4         | 3.23%   |
| LPDDR5  | 3         | 2.42%   |
| DDR2    | 3         | 2.42%   |
| Unknown | 3         | 2.42%   |
| DDR5    | 1         | 0.81%   |
| DDR     | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 60.98%  |
| DIMM         | 38        | 30.89%  |
| Row Of Chips | 9         | 7.32%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 58        | 42.03%  |
| 4096  | 45        | 32.61%  |
| 16384 | 15        | 10.87%  |
| 2048  | 12        | 8.7%    |
| 1024  | 4         | 2.9%    |
| 512   | 3         | 2.17%   |
| 32768 | 1         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 23.36%  |
| 2667    | 21        | 15.33%  |
| 3200    | 20        | 14.6%   |
| 2400    | 11        | 8.03%   |
| 1333    | 11        | 8.03%   |
| 3600    | 6         | 4.38%   |
| 1334    | 5         | 3.65%   |
| 2133    | 4         | 2.92%   |
| 6400    | 3         | 2.19%   |
| 1867    | 3         | 2.19%   |
| 533     | 3         | 2.19%   |
| 3866    | 2         | 1.46%   |
| 3733    | 2         | 1.46%   |
| 3000    | 2         | 1.46%   |
| 667     | 2         | 1.46%   |
| 4800    | 1         | 0.73%   |
| 4266    | 1         | 0.73%   |
| 3534    | 1         | 0.73%   |
| 3333    | 1         | 0.73%   |
| 3266    | 1         | 0.73%   |
| 2933    | 1         | 0.73%   |
| 2800    | 1         | 0.73%   |
| 2666    | 1         | 0.73%   |
| 1067    | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

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
| Chicony Electronics                    | 34        | 28.57%  |
| IMC Networks                           | 17        | 14.29%  |
| Microdia                               | 11        | 9.24%   |
| Realtek Semiconductor                  | 8         | 6.72%   |
| Quanta                                 | 7         | 5.88%   |
| Logitech                               | 7         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.2%    |
| Bison Electronics                      | 5         | 4.2%    |
| Sunplus Innovation Technology          | 4         | 3.36%   |
| Suyin                                  | 3         | 2.52%   |
| Acer                                   | 3         | 2.52%   |
| Syntek                                 | 2         | 1.68%   |
| MacroSilicon                           | 2         | 1.68%   |
| WaveRider Communications               | 1         | 0.84%   |
| SunplusIT                              | 1         | 0.84%   |
| Sonix Technology                       | 1         | 0.84%   |
| Silicon Motion                         | 1         | 0.84%   |
| Microsoft                              | 1         | 0.84%   |
| Luxvisions Innotech Limited            | 1         | 0.84%   |
| Intel                                  | 1         | 0.84%   |
| GEMBIRD                                | 1         | 0.84%   |
| Asuscom Network                        | 1         | 0.84%   |
| Apple                                  | 1         | 0.84%   |
| Alcor Micro                            | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 11        | 9.09%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 5.79%   |
| Suyin HP Truevision HD                        | 3         | 2.48%   |
| Realtek USB Camera                            | 3         | 2.48%   |
| Quanta HD User Facing                         | 3         | 2.48%   |
| Microdia Integrated_Webcam_HD                 | 3         | 2.48%   |
| Logitech Webcam C270                          | 3         | 2.48%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 2.48%   |
| Chicony HP TrueVision HD Camera               | 3         | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.48%   |
| Syntek Integrated Camera                      | 2         | 1.65%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.65%   |
| Microdia HP Webcam-101                        | 2         | 1.65%   |
| IMC Networks Integrated Camera                | 2         | 1.65%   |
| IMC Networks HD Camera                        | 2         | 1.65%   |
| Chicony USB2.0 Camera                         | 2         | 1.65%   |
| Chicony USB 2.0 Camera                        | 2         | 1.65%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.65%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.65%   |
| Chicony HD WebCam                             | 2         | 1.65%   |
| Chicony EasyCamera                            | 2         | 1.65%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.65%   |
| Bison Lenovo EasyCamera                       | 2         | 1.65%   |
| WaveRider USB Live camera                     | 1         | 0.83%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.83%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.83%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.83%   |
| Sonix NexiGo HD Webcam                        | 1         | 0.83%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.83%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.83%   |
| Realtek Laptop Camera                         | 1         | 0.83%   |
| Realtek Integrated Webcam HD                  | 1         | 0.83%   |
| Realtek HD WebCam                             | 1         | 0.83%   |
| Realtek FULL HD 1080P Webcam                  | 1         | 0.83%   |
| Quanta VGA WebCam                             | 1         | 0.83%   |
| Quanta HP Webcam                              | 1         | 0.83%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.83%   |
| Quanta ACER HD User Facing                    | 1         | 0.83%   |
| Microsoft LifeCam HD-3000                     | 1         | 0.83%   |
| Microdia Webcam Vitade AF                     | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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
| 0     | 135       | 76.27%  |
| 1     | 32        | 18.08%  |
| 2     | 8         | 4.52%   |
| 3     | 2         | 1.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 30.77%  |
| Graphics card            | 9         | 17.31%  |
| Net/wireless             | 7         | 13.46%  |
| Chipcard                 | 5         | 9.62%   |
| Sound                    | 4         | 7.69%   |
| Multimedia controller    | 4         | 7.69%   |
| Camera                   | 4         | 7.69%   |
| Communication controller | 2         | 3.85%   |
| Net/ethernet             | 1         | 1.92%   |

