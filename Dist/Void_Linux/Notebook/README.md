Void Linux - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

Total: 146

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Acer          | Aspire A515-44              | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| ASUSTek       | G750JX                      | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| HP            | Pavilion 11 x360 PC         | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| Lenovo        | Ducati 5 82ES               | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| Google        | Phaser360                   | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | Latitude D610               | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| Unknown       | Unknown                     | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| HP            | 15                          | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| Acer          | Aspire A515-57              | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| Notebook      | NH50_70RA                   | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| ASUSTek       | X751LD                      | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| HP            | 255 G7 Notebook PC          | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Lenovo        | B50-80 80EW                 | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| MSI           | GV72 7RE                    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Exo           | Exomate X352                | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Nokia         | Booklet 3G                  | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| ASUSTek       | X751LD                      | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Acer          | Aspire E1-531               | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Acer          | Aspire E1-531               | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| Samsung       | 275E4E/275E5E               | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| Lenovo        | G50-45 80E3                 | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| HP            | Laptop 14-dk0xxx            | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| Acer          | Aspire SW5-015              | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| Dell          | Inspiron 11 - 3148          | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| Acer          | AO722                       | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| Acer          | Nitro AN715-51              | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| Acer          | AO722                       | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| Dell          | Inspiron 1501               | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| Digibras      | NH4CU03                     | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| Positivo      | Mobile                      | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 92        | 76.67%  |
| Void Linux         | 28        | 23.33%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 119       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Notebooks | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 7         | 5.69%   |
| 5.13.19_1 | 5         | 4.07%   |
| 6.3.12_1  | 4         | 3.25%   |
| 5.18.19_1 | 4         | 3.25%   |
| 6.1.4_1   | 3         | 2.44%   |
| 5.8.18_1  | 3         | 2.44%   |
| 5.8.12_1  | 3         | 2.44%   |
| 5.3.9_1   | 3         | 2.44%   |
| 5.19.17_1 | 3         | 2.44%   |
| 5.10.17_1 | 3         | 2.44%   |
| 6.6.9_1   | 2         | 1.63%   |
| 6.5.13_1  | 2         | 1.63%   |
| 6.5.11_1  | 2         | 1.63%   |
| 6.5.10_1  | 2         | 1.63%   |
| 6.1.31_1  | 2         | 1.63%   |
| 6.1.21_1  | 2         | 1.63%   |
| 6.1.10_1  | 2         | 1.63%   |
| 5.4.24_1  | 2         | 1.63%   |
| 5.19.16_1 | 2         | 1.63%   |
| 5.18.14_1 | 2         | 1.63%   |
| 5.16.20_1 | 2         | 1.63%   |
| 5.15.32_1 | 2         | 1.63%   |
| 5.13.13_1 | 2         | 1.63%   |
| 5.12.10_1 | 2         | 1.63%   |
| 6.6.1_1   | 1         | 0.81%   |
| 6.5.5_2   | 1         | 0.81%   |
| 6.5.12_1  | 1         | 0.81%   |
| 6.4.8_1   | 1         | 0.81%   |
| 6.2.8_1   | 1         | 0.81%   |
| 6.2.11_1  | 1         | 0.81%   |
| 6.1.3_1   | 1         | 0.81%   |
| 6.1.29_1  | 1         | 0.81%   |
| 6.1.18_1  | 1         | 0.81%   |
| 6.1.14_1  | 1         | 0.81%   |
| 6.1.13_1  | 1         | 0.81%   |
| 6.0.9_1   | 1         | 0.81%   |
| 6.0.15_1  | 1         | 0.81%   |
| 6.0.10_1  | 1         | 0.81%   |
| 5.9.16_1  | 1         | 0.81%   |
| 5.9.14_1  | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.13  | 7         | 5.69%   |
| 5.13.19 | 5         | 4.07%   |
| 6.3.12  | 4         | 3.25%   |
| 5.8.12  | 4         | 3.25%   |
| 5.18.19 | 4         | 3.25%   |
| 6.1.4   | 3         | 2.44%   |
| 5.8.18  | 3         | 2.44%   |
| 5.3.9   | 3         | 2.44%   |
| 5.19.17 | 3         | 2.44%   |
| 5.10.17 | 3         | 2.44%   |
| 6.6.9   | 2         | 1.63%   |
| 6.5.13  | 2         | 1.63%   |
| 6.5.11  | 2         | 1.63%   |
| 6.5.10  | 2         | 1.63%   |
| 6.1.31  | 2         | 1.63%   |
| 6.1.21  | 2         | 1.63%   |
| 6.1.10  | 2         | 1.63%   |
| 5.4.24  | 2         | 1.63%   |
| 5.19.16 | 2         | 1.63%   |
| 5.18.14 | 2         | 1.63%   |
| 5.16.20 | 2         | 1.63%   |
| 5.15.32 | 2         | 1.63%   |
| 5.13.13 | 2         | 1.63%   |
| 5.12.10 | 2         | 1.63%   |
| 6.6.1   | 1         | 0.81%   |
| 6.5.5   | 1         | 0.81%   |
| 6.5.12  | 1         | 0.81%   |
| 6.4.8   | 1         | 0.81%   |
| 6.2.8   | 1         | 0.81%   |
| 6.2.11  | 1         | 0.81%   |
| 6.1.3   | 1         | 0.81%   |
| 6.1.29  | 1         | 0.81%   |
| 6.1.18  | 1         | 0.81%   |
| 6.1.14  | 1         | 0.81%   |
| 6.1.13  | 1         | 0.81%   |
| 6.0.9   | 1         | 0.81%   |
| 6.0.15  | 1         | 0.81%   |
| 6.0.10  | 1         | 0.81%   |
| 5.9.16  | 1         | 0.81%   |
| 5.9.14  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 14        | 11.48%  |
| 5.15    | 12        | 9.84%   |
| 6.3     | 11        | 9.02%   |
| 5.8     | 11        | 9.02%   |
| 5.13    | 11        | 9.02%   |
| 6.5     | 8         | 6.56%   |
| 5.18    | 7         | 5.74%   |
| 5.12    | 7         | 5.74%   |
| 5.10    | 7         | 5.74%   |
| 5.4     | 5         | 4.1%    |
| 5.19    | 5         | 4.1%    |
| 6.6     | 3         | 2.46%   |
| 6.0     | 3         | 2.46%   |
| 5.9     | 3         | 2.46%   |
| 5.3     | 3         | 2.46%   |
| 6.2     | 2         | 1.64%   |
| 5.16    | 2         | 1.64%   |
| 6.4     | 1         | 0.82%   |
| 5.7     | 1         | 0.82%   |
| 5.2     | 1         | 0.82%   |
| 5.14    | 1         | 0.82%   |
| 5.11    | 1         | 0.82%   |
| 5.1     | 1         | 0.82%   |
| 4.4     | 1         | 0.82%   |
| 4.14    | 1         | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 113       | 94.96%  |
| i686    | 4         | 3.36%   |
| aarch64 | 2         | 1.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 48        | 39.34%  |
| XFCE         | 19        | 15.57%  |
| KDE          | 10        | 8.2%    |
| MATE         | 9         | 7.38%   |
| KDE5         | 9         | 7.38%   |
| i3           | 6         | 4.92%   |
| GNOME        | 6         | 4.92%   |
| X-Cinnamon   | 2         | 1.64%   |
| sway         | 2         | 1.64%   |
| bspwm        | 2         | 1.64%   |
| awesome      | 2         | 1.64%   |
| river        | 1         | 0.82%   |
| openbox      | 1         | 0.82%   |
| LXQt         | 1         | 0.82%   |
| LXDE         | 1         | 0.82%   |
| Lumina       | 1         | 0.82%   |
| dwm          | 1         | 0.82%   |
| dot-xsession | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 82        | 68.33%  |
| Wayland | 17        | 14.17%  |
| Tty     | 13        | 10.83%  |
| Unknown | 8         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 72.5%   |
| LightDM | 15        | 12.5%   |
| SDDM    | 9         | 7.5%    |
| LXDM    | 6         | 5%      |
| SLiM    | 1         | 0.83%   |
| LDM     | 1         | 0.83%   |
| GDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 52.89%  |
| Unknown | 11        | 9.09%   |
| en_GB   | 9         | 7.44%   |
| it_IT   | 5         | 4.13%   |
| es_ES   | 4         | 3.31%   |
| en_DK   | 4         | 3.31%   |
| de_DE   | 4         | 3.31%   |
| C       | 4         | 3.31%   |
| fr_FR   | 2         | 1.65%   |
| en_CA   | 2         | 1.65%   |
| tr_TR   | 1         | 0.83%   |
| ru_UA   | 1         | 0.83%   |
| ru_RU   | 1         | 0.83%   |
| pt_BR   | 1         | 0.83%   |
| nb_NO   | 1         | 0.83%   |
| es_HN   | 1         | 0.83%   |
| es_DO   | 1         | 0.83%   |
| es_AR   | 1         | 0.83%   |
| en_NZ   | 1         | 0.83%   |
| en_AU   | 1         | 0.83%   |
| el_GR   | 1         | 0.83%   |
| ca_ES   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 61.67%  |
| BIOS | 46        | 38.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 74        | 61.67%  |
| Btrfs   | 29        | 24.17%  |
| Unknown | 5         | 4.17%   |
| Xfs     | 4         | 3.33%   |
| Zfs     | 3         | 2.5%    |
| Overlay | 2         | 1.67%   |
| F2fs    | 2         | 1.67%   |
| Ext3    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 77        | 63.64%  |
| Unknown | 30        | 24.79%  |
| MBR     | 14        | 11.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 89.92%  |
| Yes       | 12        | 10.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 78.15%  |
| Yes       | 26        | 21.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 26.89%  |
| Hewlett-Packard     | 18        | 15.13%  |
| Acer                | 16        | 13.45%  |
| ASUSTek Computer    | 15        | 12.61%  |
| Dell                | 11        | 9.24%   |
| MSI                 | 6         | 5.04%   |
| Unknown             | 3         | 2.52%   |
| Notebook            | 2         | 1.68%   |
| HUAWEI              | 2         | 1.68%   |
| Toshiba             | 1         | 0.84%   |
| Timi                | 1         | 0.84%   |
| Samsung Electronics | 1         | 0.84%   |
| Razer               | 1         | 0.84%   |
| Positivo            | 1         | 0.84%   |
| Pine Microsystems   | 1         | 0.84%   |
| Nokia               | 1         | 0.84%   |
| Google              | 1         | 0.84%   |
| Getac               | 1         | 0.84%   |
| Framework           | 1         | 0.84%   |
| Exo                 | 1         | 0.84%   |
| Digibras            | 1         | 0.84%   |
| Chuwi               | 1         | 0.84%   |
| Apple               | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.52%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 2         | 1.68%   |
| HP Pavilion Notebook                      | 2         | 1.68%   |
| HP Laptop 15-bw0xx                        | 2         | 1.68%   |
| HP 15                                     | 2         | 1.68%   |
| ASUS X751LD                               | 2         | 1.68%   |
| Acer Swift SF314-42                       | 2         | 1.68%   |
| Toshiba Satellite A200                    | 1         | 0.84%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.84%   |
| Samsung 275E4E/275E5E                     | 1         | 0.84%   |
| Razer Blade 14 (2022) - RZ09-0427         | 1         | 0.84%   |
| Positivo Mobile                           | 1         | 0.84%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.84%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.84%   |
| Notebook NH50_70RA                        | 1         | 0.84%   |
| Nokia Booklet 3G                          | 1         | 0.84%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.84%   |
| MSI Prestige 15 A10SC                     | 1         | 0.84%   |
| MSI GV72 7RE                              | 1         | 0.84%   |
| MSI GF63 Thin 10SCXR                      | 1         | 0.84%   |
| MSI GE60 2OC\2OD\2OE                      | 1         | 0.84%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.84%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.84%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.84%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.84%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.84%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.84%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.84%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.84%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.84%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.84%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 0.84%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 0.84%   |
| Lenovo ThinkPad T16 Gen 1 21CHCTO1WW      | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 2a 20XLS02500     | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 0.84%   |
| Lenovo ThinkPad E595 20NFCTO1WW           | 1         | 0.84%   |
| Lenovo ThinkBook 14 G5+ ARP 21HY          | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 18        | 15.13%  |
| Acer Aspire              | 10        | 8.4%    |
| Lenovo IdeaPad           | 7         | 5.88%   |
| ASUS VivoBook            | 7         | 5.88%   |
| HP Pavilion              | 5         | 4.2%    |
| HP Laptop                | 5         | 4.2%    |
| Dell Latitude            | 4         | 3.36%   |
| Dell Inspiron            | 4         | 3.36%   |
| Unknown                  | 3         | 2.52%   |
| Lenovo ThinkBook         | 2         | 1.68%   |
| HP ENVY                  | 2         | 1.68%   |
| HP 255                   | 2         | 1.68%   |
| HP 15                    | 2         | 1.68%   |
| ASUS X751LD              | 2         | 1.68%   |
| Acer Swift               | 2         | 1.68%   |
| Toshiba Satellite        | 1         | 0.84%   |
| Timi Redmi               | 1         | 0.84%   |
| Samsung 275E4E           | 1         | 0.84%   |
| Razer Blade              | 1         | 0.84%   |
| Positivo Mobile          | 1         | 0.84%   |
| Pine Microsystems Pine64 | 1         | 0.84%   |
| Notebook NV4XMB          | 1         | 0.84%   |
| Notebook NH50            | 1         | 0.84%   |
| Nokia Booklet            | 1         | 0.84%   |
| MSI Summit               | 1         | 0.84%   |
| MSI Prestige             | 1         | 0.84%   |
| MSI GV72                 | 1         | 0.84%   |
| MSI GF63                 | 1         | 0.84%   |
| MSI GE60                 | 1         | 0.84%   |
| MSI Bravo                | 1         | 0.84%   |
| Lenovo Y520-15IKB        | 1         | 0.84%   |
| Lenovo Legion            | 1         | 0.84%   |
| Lenovo G50-70            | 1         | 0.84%   |
| Lenovo G50-45            | 1         | 0.84%   |
| Lenovo Ducati            | 1         | 0.84%   |
| HUAWEI KLVL-WXXW         | 1         | 0.84%   |
| HUAWEI HN-WX9X           | 1         | 0.84%   |
| HP Stream                | 1         | 0.84%   |
| HP Notebook              | 1         | 0.84%   |
| Google Phaser360         | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 19        | 15.97%  |
| 2020    | 16        | 13.45%  |
| 2022    | 11        | 9.24%   |
| 2013    | 10        | 8.4%    |
| 2014    | 9         | 7.56%   |
| 2018    | 8         | 6.72%   |
| 2015    | 8         | 6.72%   |
| 2016    | 7         | 5.88%   |
| 2021    | 6         | 5.04%   |
| 2017    | 5         | 4.2%    |
| 2011    | 4         | 3.36%   |
| 2012    | 3         | 2.52%   |
| 2010    | 2         | 1.68%   |
| 2009    | 2         | 1.68%   |
| 2008    | 2         | 1.68%   |
| 2007    | 2         | 1.68%   |
| Unknown | 2         | 1.68%   |
| 2023    | 1         | 0.84%   |
| 2006    | 1         | 0.84%   |
| 2005    | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 119       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 119       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 99.16%  |
| Yes  | 1         | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 25.83%  |
| 3.01-4.0    | 27        | 22.5%   |
| 8.01-16.0   | 21        | 17.5%   |
| 16.01-24.0  | 19        | 15.83%  |
| 1.01-2.0    | 7         | 5.83%   |
| 32.01-64.0  | 6         | 5%      |
| 24.01-32.0  | 5         | 4.17%   |
| 0.51-1.0    | 2         | 1.67%   |
| 64.01-256.0 | 1         | 0.83%   |
| 0.01-0.5    | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 45        | 36.59%  |
| 2.01-3.0   | 29        | 23.58%  |
| 0.51-1.0   | 17        | 13.82%  |
| 4.01-8.0   | 14        | 11.38%  |
| 3.01-4.0   | 10        | 8.13%   |
| 0.01-0.5   | 5         | 4.07%   |
| 8.01-16.0  | 2         | 1.63%   |
| 16.01-24.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 78.15%  |
| 2      | 23        | 19.33%  |
| 3      | 2         | 1.68%   |
| 0      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 75.63%  |
| Yes       | 29        | 24.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 72.27%  |
| No        | 33        | 27.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 96.64%  |
| No        | 4         | 3.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 84.03%  |
| No        | 19        | 15.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 19        | 15.97%  |
| Russia             | 12        | 10.08%  |
| Germany            | 11        | 9.24%   |
| India              | 9         | 7.56%   |
| Italy              | 5         | 4.2%    |
| Brazil             | 5         | 4.2%    |
| Ukraine            | 4         | 3.36%   |
| Switzerland        | 4         | 3.36%   |
| Denmark            | 4         | 3.36%   |
| UK                 | 3         | 2.52%   |
| France             | 3         | 2.52%   |
| Vietnam            | 2         | 1.68%   |
| Turkey             | 2         | 1.68%   |
| Spain              | 2         | 1.68%   |
| Netherlands        | 2         | 1.68%   |
| Morocco            | 2         | 1.68%   |
| Greece             | 2         | 1.68%   |
| Canada             | 2         | 1.68%   |
| Bulgaria           | 2         | 1.68%   |
| Australia          | 2         | 1.68%   |
| Argentina          | 2         | 1.68%   |
| Uruguay            | 1         | 0.84%   |
| Thailand           | 1         | 0.84%   |
| Serbia             | 1         | 0.84%   |
| Portugal           | 1         | 0.84%   |
| Poland             | 1         | 0.84%   |
| Peru               | 1         | 0.84%   |
| Norway             | 1         | 0.84%   |
| New Zealand        | 1         | 0.84%   |
| Mexico             | 1         | 0.84%   |
| Latvia             | 1         | 0.84%   |
| Jordan             | 1         | 0.84%   |
| Indonesia          | 1         | 0.84%   |
| Honduras           | 1         | 0.84%   |
| Guatemala          | 1         | 0.84%   |
| Grenada            | 1         | 0.84%   |
| Ecuador            | 1         | 0.84%   |
| Dominican Republic | 1         | 0.84%   |
| Czechia            | 1         | 0.84%   |
| Colombia           | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 6         | 5%      |
| St Petersburg          | 3         | 2.5%    |
| Spring Hill            | 2         | 1.67%   |
| Sao Paulo              | 2         | 1.67%   |
| Rome                   | 2         | 1.67%   |
| Meknes                 | 2         | 1.67%   |
| Hyderabad              | 2         | 1.67%   |
| Geneva                 | 2         | 1.67%   |
| Zarqa                  | 1         | 0.83%   |
| Yambol                 | 1         | 0.83%   |
| Wilen bei Wollerau     | 1         | 0.83%   |
| Weatherford            | 1         | 0.83%   |
| Volgograd              | 1         | 0.83%   |
| Vlaardingen            | 1         | 0.83%   |
| Vienna                 | 1         | 0.83%   |
| Viby J                 | 1         | 0.83%   |
| Verkhnyaya Pyshma      | 1         | 0.83%   |
| Trujillo               | 1         | 0.83%   |
| Toulouse               | 1         | 0.83%   |
| Touget                 | 1         | 0.83%   |
| Toms River             | 1         | 0.83%   |
| Tegucigalpa            | 1         | 0.83%   |
| Syktyvkar              | 1         | 0.83%   |
| Sydney                 | 1         | 0.83%   |
| Surabaya               | 1         | 0.83%   |
| Sun Prairie            | 1         | 0.83%   |
| Stratford              | 1         | 0.83%   |
| Stezzano               | 1         | 0.83%   |
| Solone                 | 1         | 0.83%   |
| Sohren                 | 1         | 0.83%   |
| Sofia                  | 1         | 0.83%   |
| Sistranda              | 1         | 0.83%   |
| Saxtons River          | 1         | 0.83%   |
| Santo Domingo          | 1         | 0.83%   |
| San Miguel de Tucumán | 1         | 0.83%   |
| Saint George's         | 1         | 0.83%   |
| Rostock                | 1         | 0.83%   |
| Rosenheim              | 1         | 0.83%   |
| River Grove            | 1         | 0.83%   |
| Riga                   | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 27        | 28     | 19.29%  |
| Seagate                     | 18        | 19     | 12.86%  |
| WDC                         | 13        | 14     | 9.29%   |
| Unknown                     | 11        | 17     | 7.86%   |
| SanDisk                     | 10        | 11     | 7.14%   |
| SK hynix                    | 9         | 9      | 6.43%   |
| HGST                        | 7         | 8      | 5%      |
| Intel                       | 6         | 7      | 4.29%   |
| Toshiba                     | 5         | 5      | 3.57%   |
| Kingston                    | 5         | 5      | 3.57%   |
| Crucial                     | 5         | 5      | 3.57%   |
| Hitachi                     | 3         | 3      | 2.14%   |
| Phison                      | 2         | 2      | 1.43%   |
| Micron Technology           | 2         | 2      | 1.43%   |
| Kingston Technology Company | 2         | 2      | 1.43%   |
| XrayDisk                    | 1         | 1      | 0.71%   |
| Transcend                   | 1         | 1      | 0.71%   |
| PNY                         | 1         | 1      | 0.71%   |
| Phison Electronics          | 1         | 1      | 0.71%   |
| Patriot                     | 1         | 1      | 0.71%   |
| ORIGIN                      | 1         | 1      | 0.71%   |
| Micron/Crucial Technology   | 1         | 1      | 0.71%   |
| Lenovo                      | 1         | 1      | 0.71%   |
| KIOXIA                      | 1         | 1      | 0.71%   |
| INNOVATION IT               | 1         | 1      | 0.71%   |
| IBM/Hitachi                 | 1         | 1      | 0.71%   |
| China                       | 1         | 1      | 0.71%   |
| BHT                         | 1         | 1      | 0.71%   |
| Apple                       | 1         | 1      | 0.71%   |
| A-DATA Technology           | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 2.76%   |
| Unknown MMC Card  32GB                             | 3         | 2.07%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 2.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 3         | 2.07%   |
| HGST HTS545050A7E680 500GB                         | 3         | 2.07%   |
| Crucial CT500MX500SSD1 500GB                       | 3         | 2.07%   |
| Unknown MMC Card  64GB                             | 2         | 1.38%   |
| Unknown MMC Card  128GB                            | 2         | 1.38%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB            | 2         | 1.38%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 1.38%   |
| Samsung SSD 870 EVO 500GB                          | 2         | 1.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 1.38%   |
| Intel SSDPEKNW512G8 512GB                          | 2         | 1.38%   |
| HGST HTS541010B7E610 1TB                           | 2         | 1.38%   |
| HGST HTS541010A9E680 1TB                           | 2         | 1.38%   |
| XrayDisk 128GB                                     | 1         | 0.69%   |
| WDC WD5000LPCX-22VHAT0 500GB                       | 1         | 0.69%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 0.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 0.69%   |
| WDC WD2500BEVT-22A23T0 250GB                       | 1         | 0.69%   |
| WDC WD1600BEVS-60VAT0 160GB                        | 1         | 0.69%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.69%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.69%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.69%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.69%   |
| WDC WD Elements 320GB                              | 1         | 0.69%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB                 | 1         | 0.69%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB               | 1         | 0.69%   |
| Unknown USB DISK 3.2 1TB                           | 1         | 0.69%   |
| Unknown SD512  512MB                               | 1         | 0.69%   |
| Unknown SD16G  16GB                                | 1         | 0.69%   |
| Unknown SD/MMC/MS PRO 256GB                        | 1         | 0.69%   |
| Unknown MMC Card  8GB                              | 1         | 0.69%   |
| Unknown MMC Card  2GB                              | 1         | 0.69%   |
| Unknown MMC Card                                   | 1         | 0.69%   |
| Unknown CWBC3R  64GB                               | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 39.13%  |
| WDC                 | 10        | 10     | 21.74%  |
| HGST                | 7         | 8      | 15.22%  |
| Toshiba             | 4         | 4      | 8.7%    |
| Hitachi             | 3         | 3      | 6.52%   |
| XrayDisk            | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| IBM/Hitachi         | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 23.53%  |
| SanDisk             | 5         | 5      | 14.71%  |
| Crucial             | 5         | 5      | 14.71%  |
| Kingston            | 4         | 4      | 11.76%  |
| Transcend           | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| ORIGIN              | 1         | 1      | 2.94%   |
| Lenovo              | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| INNOVATION IT       | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| BHT                 | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 47        | 53     | 34.56%  |
| HDD     | 45        | 48     | 33.09%  |
| SSD     | 32        | 34     | 23.53%  |
| MMC     | 10        | 14     | 7.35%   |
| Unknown | 2         | 3      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 78     | 52.63%  |
| NVMe | 47        | 53     | 35.34%  |
| MMC  | 10        | 14     | 7.52%   |
| SAS  | 6         | 7      | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 50     | 58.44%  |
| 0.51-1.0   | 31        | 31     | 40.26%  |
| 4.01-10.0  | 1         | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 37        | 30.58%  |
| 501-1000       | 28        | 23.14%  |
| 101-250        | 26        | 21.49%  |
| Unknown        | 7         | 5.79%   |
| 1-20           | 6         | 4.96%   |
| 51-100         | 6         | 4.96%   |
| 21-50          | 5         | 4.13%   |
| 1001-2000      | 4         | 3.31%   |
| More than 3000 | 1         | 0.83%   |
| 2001-3000      | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 28.1%   |
| 101-250        | 27        | 22.31%  |
| 21-50          | 23        | 19.01%  |
| 51-100         | 14        | 11.57%  |
| 251-500        | 10        | 8.26%   |
| Unknown        | 7         | 5.79%   |
| 1001-2000      | 3         | 2.48%   |
| 501-1000       | 2         | 1.65%   |
| More than 3000 | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB              | 2         | 2      | 11.76%  |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 5.88%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 5.88%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 5.88%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 5.88%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5.88%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5.88%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 5.88%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 35.29%  |
| Hitachi             | 3         | 3      | 17.65%  |
| HGST                | 3         | 3      | 17.65%  |
| WDC                 | 1         | 1      | 5.88%   |
| Toshiba             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| IBM/Hitachi         | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 6      | 40%     |
| Hitachi     | 3         | 3      | 20%     |
| HGST        | 3         | 3      | 20%     |
| WDC         | 1         | 1      | 6.67%   |
| Toshiba     | 1         | 1      | 6.67%   |
| IBM/Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

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
| Works    | 68        | 80     | 53.13%  |
| Detected | 43        | 55     | 33.59%  |
| Malfunc  | 17        | 17     | 13.28%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 67        | 48.91%  |
| AMD                              | 24        | 17.52%  |
| Samsung Electronics              | 19        | 13.87%  |
| SK hynix                         | 8         | 5.84%   |
| SanDisk                          | 7         | 5.11%   |
| Phison Electronics               | 3         | 2.19%   |
| Kingston Technology Company      | 3         | 2.19%   |
| Micron Technology                | 2         | 1.46%   |
| Toshiba America Info Systems     | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] | 1         | 0.73%   |
| Micron/Crucial Technology        | 1         | 0.73%   |
| KIOXIA                           | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 22        | 15.49%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 7.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 6.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 8         | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 3.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 4         | 2.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 4         | 2.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 2.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 3         | 2.11%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 3         | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 3         | 2.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 3         | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.11%   |
| Intel SSD 660P Series                                                        | 3         | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.11%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 2         | 1.41%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 2         | 1.41%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 2         | 1.41%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.41%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                               | 2         | 1.41%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 2         | 1.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.41%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.7%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                           | 1         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.7%    |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.7%    |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 0.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.7%    |
| Phison E12 NVMe Controller                                                   | 1         | 0.7%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 56.52%  |
| NVMe | 47        | 34.06%  |
| IDE  | 7         | 5.07%   |
| RAID | 6         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 66.39%  |
| AMD    | 38        | 31.93%  |
| ARM    | 2         | 1.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.52%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 2.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.68%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.68%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.68%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 1.68%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.68%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.68%   |
| ARM Processor                                 | 2         | 1.68%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 1.68%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.68%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.68%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.68%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.68%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.68%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.84%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.84%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 0.84%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.84%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.84%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.84%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.84%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.84%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 18.49%  |
| Intel Core i7           | 19        | 15.97%  |
| Intel Core i3           | 13        | 10.92%  |
| Other                   | 11        | 9.24%   |
| AMD Ryzen 5             | 10        | 8.4%    |
| Intel Celeron           | 8         | 6.72%   |
| AMD Ryzen 7             | 8         | 6.72%   |
| Intel Atom              | 5         | 4.2%    |
| AMD Ryzen 7 PRO         | 5         | 4.2%    |
| Intel Pentium           | 2         | 1.68%   |
| Intel Core 2 Duo        | 2         | 1.68%   |
| AMD Ryzen 3             | 2         | 1.68%   |
| AMD A8                  | 2         | 1.68%   |
| Intel Pentium M         | 1         | 0.84%   |
| Intel Genuine           | 1         | 0.84%   |
| AMD Turion 64 X2 Mobile | 1         | 0.84%   |
| AMD Ryzen 9             | 1         | 0.84%   |
| AMD Ryzen 5 PRO         | 1         | 0.84%   |
| AMD E2                  | 1         | 0.84%   |
| AMD E1                  | 1         | 0.84%   |
| AMD C-60                | 1         | 0.84%   |
| AMD A6                  | 1         | 0.84%   |
| AMD A4                  | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 38.66%  |
| 4      | 38        | 31.93%  |
| 6      | 15        | 12.61%  |
| 8      | 11        | 9.24%   |
| 1      | 6         | 5.04%   |
| 14     | 2         | 1.68%   |
| 10     | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 99.16%  |
| 2      | 1         | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 72.27%  |
| 1      | 33        | 27.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 92.44%  |
| Unknown        | 4         | 3.36%   |
| 32-bit         | 3         | 2.52%   |
| 64-bit         | 2         | 1.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 34.71%  |
| 0x40651    | 8         | 6.61%   |
| 0x0a404102 | 5         | 4.13%   |
| 0x406e3    | 4         | 3.31%   |
| 0x306a9    | 4         | 3.31%   |
| 0x08108102 | 4         | 3.31%   |
| 0x906ea    | 3         | 2.48%   |
| 0x806ec    | 3         | 2.48%   |
| 0x806e9    | 3         | 2.48%   |
| 0x30678    | 3         | 2.48%   |
| 0x206a7    | 3         | 2.48%   |
| 0x08600104 | 3         | 2.48%   |
| 0x906e9    | 2         | 1.65%   |
| 0x906a3    | 2         | 1.65%   |
| 0x106c2    | 2         | 1.65%   |
| 0x0a50000c | 2         | 1.65%   |
| 0x08608103 | 2         | 1.65%   |
| 0x07030105 | 2         | 1.65%   |
| 0x06006705 | 2         | 1.65%   |
| 0x05000119 | 2         | 1.65%   |
| 0xa0652    | 1         | 0.83%   |
| 0x806eb    | 1         | 0.83%   |
| 0x806ea    | 1         | 0.83%   |
| 0x806c1    | 1         | 0.83%   |
| 0x706e5    | 1         | 0.83%   |
| 0x406c4    | 1         | 0.83%   |
| 0x306d4    | 1         | 0.83%   |
| 0x30673    | 1         | 0.83%   |
| 0x20652    | 1         | 0.83%   |
| 0x106ca    | 1         | 0.83%   |
| 0x10661    | 1         | 0.83%   |
| 0x0a404101 | 1         | 0.83%   |
| 0x08608102 | 1         | 0.83%   |
| 0x08600106 | 1         | 0.83%   |
| 0x08600103 | 1         | 0.83%   |
| 0x08600102 | 1         | 0.83%   |
| 0x08108109 | 1         | 0.83%   |
| 0x0810100b | 1         | 0.83%   |
| 0x08101007 | 1         | 0.83%   |
| 0x07030104 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 17.65%  |
| Haswell          | 11        | 9.24%   |
| Unknown          | 11        | 9.24%   |
| Zen 2            | 7         | 5.88%   |
| Skylake          | 6         | 5.04%   |
| Silvermont       | 6         | 5.04%   |
| Zen+             | 5         | 4.2%    |
| Zen 3            | 4         | 3.36%   |
| SandyBridge      | 4         | 3.36%   |
| IvyBridge        | 4         | 3.36%   |
| Excavator        | 4         | 3.36%   |
| TigerLake        | 3         | 2.52%   |
| Puma             | 3         | 2.52%   |
| IceLake          | 3         | 2.52%   |
| Core             | 3         | 2.52%   |
| CometLake        | 3         | 2.52%   |
| Broadwell        | 3         | 2.52%   |
| Bonnell          | 3         | 2.52%   |
| Alderlake Hybrid | 3         | 2.52%   |
| Zen              | 2         | 1.68%   |
| Goldmont plus    | 2         | 1.68%   |
| Bobcat           | 2         | 1.68%   |
| Westmere         | 1         | 0.84%   |
| Penryn           | 1         | 0.84%   |
| P6               | 1         | 0.84%   |
| K8 Hammer        | 1         | 0.84%   |
| Jaguar           | 1         | 0.84%   |
| Goldmont         | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 51.01%  |
| AMD                              | 40        | 26.85%  |
| Nvidia                           | 32        | 21.48%  |
| Silicon Integrated Systems [SiS] | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 6.54%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 6         | 3.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 3.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.92%   |
| AMD Rembrandt [Radeon 680M]                                               | 6         | 3.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 5         | 3.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.61%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.61%   |
| Intel UHD Graphics 620                                                    | 3         | 1.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 1.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.96%   |
| Intel HD Graphics 620                                                     | 3         | 1.96%   |
| Intel HD Graphics 5500                                                    | 3         | 1.96%   |
| AMD Lucienne                                                              | 3         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.96%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.31%   |
| Intel HD Graphics 630                                                     | 2         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.31%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 1.31%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.31%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.31%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.65%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.65%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 38.66%  |
| 1 x AMD        | 33        | 27.73%  |
| Intel + Nvidia | 27        | 22.69%  |
| AMD + Nvidia   | 4         | 3.36%   |
| Other          | 3         | 2.52%   |
| 2 x AMD        | 2         | 1.68%   |
| 2 x Intel      | 1         | 0.84%   |
| 1 x SiS        | 1         | 0.84%   |
| 1 x Nvidia     | 1         | 0.84%   |
| Intel + AMD    | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 93        | 78.15%  |
| Proprietary | 22        | 18.49%  |
| Unknown     | 4         | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 65.57%  |
| 0.01-0.5   | 14        | 11.48%  |
| 1.01-2.0   | 10        | 8.2%    |
| 3.01-4.0   | 8         | 6.56%   |
| 0.51-1.0   | 7         | 5.74%   |
| 7.01-8.0   | 2         | 1.64%   |
| 5.01-6.0   | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 29        | 23.2%   |
| AU Optronics         | 25        | 20%     |
| BOE                  | 19        | 15.2%   |
| LG Display           | 16        | 12.8%   |
| Samsung Electronics  | 5         | 4%      |
| PANDA                | 4         | 3.2%    |
| LG Philips           | 3         | 2.4%    |
| TMX                  | 2         | 1.6%    |
| Sharp                | 2         | 1.6%    |
| Philips              | 2         | 1.6%    |
| Lenovo               | 2         | 1.6%    |
| Hewlett-Packard      | 2         | 1.6%    |
| Apple                | 2         | 1.6%    |
| AOC                  | 2         | 1.6%    |
| STD                  | 1         | 0.8%    |
| Quanta Display       | 1         | 0.8%    |
| Panasonic            | 1         | 0.8%    |
| InnoLux Display      | 1         | 0.8%    |
| Iiyama               | 1         | 0.8%    |
| Goldstar             | 1         | 0.8%    |
| CSO                  | 1         | 0.8%    |
| CHR                  | 1         | 0.8%    |
| BOE Technology Group | 1         | 0.8%    |
| Unknown              | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.4%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.6%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.6%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 1.6%    |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.8%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.8%    |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.8%    |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.8%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.8%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.8%    |
| Quanta Display LCD Monitor QDS0015 1024x768 285x214mm 14.0-inch       | 1         | 0.8%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.8%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.8%    |
| PANDA LCD Monitor NCP003D 1920x1080 344x194mm 15.5-inch               | 1         | 0.8%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.8%    |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.8%    |
| LG Philips LCD Monitor LPLDC00 1280x800 331x207mm 15.4-inch           | 1         | 0.8%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.8%    |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.8%    |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.8%    |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.8%    |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.8%    |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.8%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 49        | 40.16%  |
| 1366x768 (WXGA)   | 35        | 28.69%  |
| 1920x1200 (WUXGA) | 7         | 5.74%   |
| 1600x900 (HD+)    | 5         | 4.1%    |
| 1280x800 (WXGA)   | 4         | 3.28%   |
| 2560x1600         | 3         | 2.46%   |
| 2560x1440 (QHD)   | 3         | 2.46%   |
| 2160x1440         | 3         | 2.46%   |
| 3840x2160 (4K)    | 2         | 1.64%   |
| 2880x1800         | 2         | 1.64%   |
| 1024x600          | 2         | 1.64%   |
| 3440x1440         | 1         | 0.82%   |
| 3200x2000         | 1         | 0.82%   |
| 2288x1287         | 1         | 0.82%   |
| 2256x1504         | 1         | 0.82%   |
| 1360x768          | 1         | 0.82%   |
| 1280x720 (HD)     | 1         | 0.82%   |
| 1024x768 (XGA)    | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 51        | 40.8%   |
| 14      | 23        | 18.4%   |
| 13      | 14        | 11.2%   |
| 11      | 6         | 4.8%    |
| 17      | 5         | 4%      |
| 16      | 4         | 3.2%    |
| 12      | 4         | 3.2%    |
| 24      | 3         | 2.4%    |
| 23      | 3         | 2.4%    |
| 10      | 2         | 1.6%    |
| Unknown | 2         | 1.6%    |
| 84      | 1         | 0.8%    |
| 39      | 1         | 0.8%    |
| 34      | 1         | 0.8%    |
| 33      | 1         | 0.8%    |
| 32      | 1         | 0.8%    |
| 21      | 1         | 0.8%    |
| 18      | 1         | 0.8%    |
| 8       | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 65.6%   |
| 201-300     | 22        | 17.6%   |
| 501-600     | 6         | 4.8%    |
| 351-400     | 5         | 4%      |
| 701-800     | 3         | 2.4%    |
| 401-500     | 2         | 1.6%    |
| Unknown     | 2         | 1.6%    |
| 801-900     | 1         | 0.8%    |
| 1501-2000   | 1         | 0.8%    |
| 101-200     | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 77.59%  |
| 16/10   | 18        | 15.52%  |
| 3/2     | 5         | 4.31%   |
| 4/3     | 1         | 0.86%   |
| 21/9    | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 40%     |
| 81-90          | 29        | 23.2%   |
| 71-80          | 6         | 4.8%    |
| 51-60          | 6         | 4.8%    |
| 201-250        | 5         | 4%      |
| 111-120        | 5         | 4%      |
| 61-70          | 4         | 3.2%    |
| 351-500        | 3         | 2.4%    |
| 121-130        | 3         | 2.4%    |
| 41-50          | 2         | 1.6%    |
| 251-300        | 2         | 1.6%    |
| 131-140        | 2         | 1.6%    |
| 91-100         | 2         | 1.6%    |
| Unknown        | 2         | 1.6%    |
| More than 1000 | 1         | 0.8%    |
| 1-40           | 1         | 0.8%    |
| 141-150        | 1         | 0.8%    |
| 501-1000       | 1         | 0.8%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 45.16%  |
| 101-120       | 30        | 24.19%  |
| 51-100        | 18        | 14.52%  |
| 161-240       | 15        | 12.1%   |
| More than 240 | 3         | 2.42%   |
| Unknown       | 2         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 102       | 85.71%  |
| 2     | 15        | 12.61%  |
| 0     | 2         | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 67        | 38.29%  |
| Intel                            | 48        | 27.43%  |
| Qualcomm Atheros                 | 21        | 12%     |
| Broadcom                         | 11        | 6.29%   |
| MediaTek                         | 5         | 2.86%   |
| Qualcomm                         | 4         | 2.29%   |
| Broadcom Limited                 | 4         | 2.29%   |
| Sierra Wireless                  | 3         | 1.71%   |
| Ralink Technology                | 3         | 1.71%   |
| Ralink                           | 2         | 1.14%   |
| Cypress Semiconductor            | 2         | 1.14%   |
| Xiaomi                           | 1         | 0.57%   |
| TP-Link                          | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Marvell Technology Group         | 1         | 0.57%   |
| Huawei Technologies              | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 41        | 19.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 7.18%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 4.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 3.35%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 2.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 2.39%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 1.91%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.96%   |
| Intel Wireless 8260                                                    | 2         | 0.96%   |
| Intel Wireless 7260                                                    | 2         | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.96%   |
| Cypress K38231_03                                                      | 2         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                        | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.48%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.48%   |
| Sierra Wireless EM7455                                                 | 1         | 0.48%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.48%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 0.48%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 39.67%  |
| Realtek Semiconductor | 26        | 21.49%  |
| Qualcomm Atheros      | 18        | 14.88%  |
| Broadcom              | 9         | 7.44%   |
| MediaTek              | 5         | 4.13%   |
| Qualcomm              | 4         | 3.31%   |
| Sierra Wireless       | 3         | 2.48%   |
| Ralink Technology     | 3         | 2.48%   |
| Broadcom Limited      | 3         | 2.48%   |
| Ralink                | 2         | 1.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 9         | 7.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 5.79%   |
| Intel Wireless 8265 / 8275                                    | 6         | 4.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 4.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 4.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 4.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 4.13%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 3.31%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 4         | 3.31%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 3         | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 2.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.65%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.65%   |
| Intel Wireless 8260                                           | 2         | 1.65%   |
| Intel Wireless 7260                                           | 2         | 1.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 2         | 1.65%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.65%   |
| Broadcom BCM4311 802.11b/g WLAN                               | 2         | 1.65%   |
| Sierra Wireless EM7455                                        | 1         | 0.83%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.83%   |
| Sierra Wireless EM7305 Modem                                  | 1         | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.83%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 58        | 66.67%  |
| Intel                            | 14        | 16.09%  |
| Qualcomm Atheros                 | 4         | 4.6%    |
| Broadcom                         | 3         | 3.45%   |
| Cypress Semiconductor            | 2         | 2.3%    |
| Xiaomi                           | 1         | 1.15%   |
| TP-Link                          | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |
| Marvell Technology Group         | 1         | 1.15%   |
| Huawei Technologies              | 1         | 1.15%   |
| Broadcom Limited                 | 1         | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 41        | 47.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 17.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.45%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.3%    |
| Cypress K38231_03                                                      | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 1.15%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.15%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 1.15%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.15%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.15%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.15%   |
| Huawei STG-LX1                                                         | 1         | 1.15%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.15%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1         | 1.15%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 56.93%  |
| Ethernet | 86        | 42.57%  |
| Modem    | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 83.47%  |
| Ethernet | 20        | 16.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 63.87%  |
| 1     | 36        | 30.25%  |
| 0     | 5         | 4.2%    |
| 3     | 2         | 1.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 82.64%  |
| Yes  | 21        | 17.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 39.22%  |
| Realtek Semiconductor           | 16        | 15.69%  |
| Lite-On Technology              | 9         | 8.82%   |
| Broadcom                        | 7         | 6.86%   |
| IMC Networks                    | 6         | 5.88%   |
| Foxconn / Hon Hai               | 6         | 5.88%   |
| Qualcomm Atheros Communications | 4         | 3.92%   |
| USI                             | 3         | 2.94%   |
| Realtek                         | 2         | 1.96%   |
| Cambridge Silicon Radio         | 2         | 1.96%   |
| Toshiba                         | 1         | 0.98%   |
| SIN                             | 1         | 0.98%   |
| Ralink                          | 1         | 0.98%   |
| Opticis                         | 1         | 0.98%   |
| Foxconn International           | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |
| Apple                           | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 11.76%  |
| Realtek Bluetooth Radio                             | 9         | 8.82%   |
| Intel AX200 Bluetooth                               | 9         | 8.82%   |
| Intel AX201 Bluetooth                               | 7         | 6.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 4.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 3.92%   |
| USI Bluetooth Device                                | 3         | 2.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2.94%   |
| Realtek Bluetooth Radio                             | 2         | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.96%   |
| Lite-On Bluetooth Device                            | 2         | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.96%   |
| Intel Bluetooth Device                              | 2         | 1.96%   |
| Intel AX210 Bluetooth                               | 2         | 1.96%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.96%   |
| IMC Networks Bluetooth Device                       | 2         | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.96%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.98%   |
| SIN Bluetooth Keyboard                              | 1         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.98%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.98%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.98%   |
| Opticis Bluetooth Radio                             | 1         | 0.98%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.98%   |
| IMC Networks Wireless_Device                        | 1         | 0.98%   |
| IMC Networks Bluetooth                              | 1         | 0.98%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.98%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.98%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.98%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.98%   |
| Broadcom HP Portable Valentine                      | 1         | 0.98%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.98%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 57.46%  |
| AMD                              | 39        | 29.1%   |
| Nvidia                           | 11        | 8.21%   |
| Texas Instruments                | 2         | 1.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Logitech                         | 1         | 0.75%   |
| JMTek                            | 1         | 0.75%   |
| Creative Technology              | 1         | 0.75%   |
| Corsair                          | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 26        | 14.21%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 7.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 6.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 5.46%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 5.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 2.73%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.19%   |
| AMD High Definition Audio Controller                                       | 4         | 2.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.64%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.09%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.09%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.09%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.55%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.55%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 31        | 28.97%  |
| Samsung Electronics | 30        | 28.04%  |
| Micron Technology   | 18        | 16.82%  |
| Kingston            | 7         | 6.54%   |
| Unknown             | 5         | 4.67%   |
| A-DATA Technology   | 4         | 3.74%   |
| Ramaxel Technology  | 2         | 1.87%   |
| Corsair             | 2         | 1.87%   |
| Unknown (ABCD)      | 1         | 0.93%   |
| Transcend           | 1         | 0.93%   |
| Team                | 1         | 0.93%   |
| Nanya Technology    | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Crucial             | 1         | 0.93%   |
| 4ea5                | 1         | 0.93%   |
| 48spaces            | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.77%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.77%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 1.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 1.77%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s          | 2         | 1.77%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.77%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                    | 1         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                        | 1         | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 1         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.88%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.88%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 1         | 0.88%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                       | 1         | 0.88%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.88%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                          | 1         | 0.88%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.88%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 38        | 43.18%  |
| DDR3   | 33        | 37.5%   |
| LPDDR5 | 6         | 6.82%   |
| LPDDR4 | 5         | 5.68%   |
| DDR2   | 3         | 3.41%   |
| LPDDR3 | 1         | 1.14%   |
| DDR5   | 1         | 1.14%   |
| DDR    | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 87.5%   |
| Row Of Chips | 9         | 10.23%  |
| DIMM         | 1         | 1.14%   |
| Unknown      | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 43        | 42.57%  |
| 4096  | 35        | 34.65%  |
| 16384 | 8         | 7.92%   |
| 2048  | 8         | 7.92%   |
| 1024  | 3         | 2.97%   |
| 512   | 3         | 2.97%   |
| 32768 | 1         | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 26.6%   |
| 2667    | 19        | 20.21%  |
| 3200    | 16        | 17.02%  |
| 6400    | 6         | 6.38%   |
| 2400    | 5         | 5.32%   |
| 1334    | 5         | 5.32%   |
| 1333    | 4         | 4.26%   |
| 533     | 3         | 3.19%   |
| 3733    | 2         | 2.13%   |
| 2133    | 2         | 2.13%   |
| 667     | 2         | 2.13%   |
| 8400    | 1         | 1.06%   |
| 4800    | 1         | 1.06%   |
| 4266    | 1         | 1.06%   |
| 1867    | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 31.78%  |
| IMC Networks                           | 17        | 15.89%  |
| Microdia                               | 9         | 8.41%   |
| Bison Electronics                      | 8         | 7.48%   |
| Realtek Semiconductor                  | 7         | 6.54%   |
| Quanta                                 | 7         | 6.54%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.67%   |
| Acer                                   | 4         | 3.74%   |
| Syntek                                 | 3         | 2.8%    |
| Suyin                                  | 3         | 2.8%    |
| Sunplus Innovation Technology          | 3         | 2.8%    |
| Luxvisions Innotech Limited            | 2         | 1.87%   |
| SunplusIT                              | 1         | 0.93%   |
| Silicon Motion                         | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Intel                                  | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 10        | 9.26%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 7         | 6.48%   |
| Chicony HP Truevision HD camera                   | 4         | 3.7%    |
| Syntek Integrated Camera                          | 3         | 2.78%   |
| Suyin HP Truevision HD                            | 3         | 2.78%   |
| Realtek USB Camera                                | 3         | 2.78%   |
| Quanta HD User Facing                             | 3         | 2.78%   |
| Microdia Integrated_Webcam_HD                     | 3         | 2.78%   |
| Chicony USB 2.0 Camera                            | 3         | 2.78%   |
| Chicony HD Webcam                                 | 3         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam     | 3         | 2.78%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.85%   |
| Microdia HP Integrated Webcam                     | 2         | 1.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 2         | 1.85%   |
| IMC Networks Integrated Camera                    | 2         | 1.85%   |
| IMC Networks HD Camera                            | 2         | 1.85%   |
| Chicony USB2.0 Camera                             | 2         | 1.85%   |
| Chicony Lenovo EasyCamera                         | 2         | 1.85%   |
| Chicony HD WebCam (Acer)                          | 2         | 1.85%   |
| Chicony HD User Facing                            | 2         | 1.85%   |
| Bison Lenovo EasyCamera                           | 2         | 1.85%   |
| Bison Integrated RGB Camera                       | 2         | 1.85%   |
| Acer SunplusIT Integrated Camera                  | 2         | 1.85%   |
| SunplusIT XiaoMi USB 2.0 Webcam                   | 1         | 0.93%   |
| Sunplus HP Wide Vision HD                         | 1         | 0.93%   |
| Silicon Motion WebCam SC-10HDD12636N              | 1         | 0.93%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.93%   |
| Realtek Laptop Camera                             | 1         | 0.93%   |
| Realtek Integrated Webcam HD                      | 1         | 0.93%   |
| Realtek HD WebCam                                 | 1         | 0.93%   |
| Quanta VGA WebCam                                 | 1         | 0.93%   |
| Quanta HP Webcam                                  | 1         | 0.93%   |
| Quanta HP TrueVision HD Camera                    | 1         | 0.93%   |
| Quanta ACER HD User Facing                        | 1         | 0.93%   |
| Microdia Webcam Vitade AF                         | 1         | 0.93%   |
| Microdia Webcam                                   | 1         | 0.93%   |
| Microdia Sonix USB 2.0 Camera                     | 1         | 0.93%   |
| Microdia Integrated_Webcam_2M                     | 1         | 0.93%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.93%   |
| Luxvisions Innotech Limited EasyCamera 1M         | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 47.06%  |
| Validity Sensors           | 3         | 17.65%  |
| Shenzhen Goodix Technology | 3         | 17.65%  |
| Elan Microelectronics      | 2         | 11.76%  |
| Upek                       | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 29.41%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 17.65%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 17.65%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.88%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 5.88%   |
| Synaptics UWP WBDI Device                              | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.88%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.88%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 66.67%  |
| Lenovo      | 1         | 16.67%  |
| Broadcom    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 66.67%  |
| Lenovo Integrated Smart Card Reader            | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 84        | 70%     |
| 1     | 28        | 23.33%  |
| 2     | 7         | 5.83%   |
| 3     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 38.64%  |
| Graphics card            | 7         | 15.91%  |
| Chipcard                 | 6         | 13.64%  |
| Net/wireless             | 5         | 11.36%  |
| Multimedia controller    | 2         | 4.55%   |
| Communication controller | 2         | 4.55%   |
| Camera                   | 2         | 4.55%   |
| Sound                    | 1         | 2.27%   |
| Net/ethernet             | 1         | 2.27%   |
| Bluetooth                | 1         | 2.27%   |

