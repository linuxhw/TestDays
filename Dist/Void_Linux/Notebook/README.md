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

Total: 142

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 89        | 76.07%  |
| Void Linux         | 28        | 23.93%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 116       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 6.3.13_1    | 7         | 5.83%   |
| 5.13.19_1   | 5         | 4.17%   |
| 5.18.19_1   | 4         | 3.33%   |
| 6.3.12_1    | 3         | 2.5%    |
| 6.1.4_1     | 3         | 2.5%    |
| 5.8.18_1    | 3         | 2.5%    |
| 5.8.12_1    | 3         | 2.5%    |
| 5.3.9_1     | 3         | 2.5%    |
| 5.19.17_1   | 3         | 2.5%    |
| 5.10.17_1   | 3         | 2.5%    |
| 6.5.13_1    | 2         | 1.67%   |
| 6.5.11_1    | 2         | 1.67%   |
| 6.5.10_1    | 2         | 1.67%   |
| 6.1.31_1    | 2         | 1.67%   |
| 6.1.21_1    | 2         | 1.67%   |
| 6.1.10_1    | 2         | 1.67%   |
| 5.4.24_1    | 2         | 1.67%   |
| 5.19.16_1   | 2         | 1.67%   |
| 5.18.14_1   | 2         | 1.67%   |
| 5.16.20_1   | 2         | 1.67%   |
| 5.15.32_1   | 2         | 1.67%   |
| 5.13.13_1   | 2         | 1.67%   |
| 5.12.10_1   | 2         | 1.67%   |
| 6.6.1_1     | 1         | 0.83%   |
| 6.5.5_2     | 1         | 0.83%   |
| 6.5.12_1    | 1         | 0.83%   |
| 6.4.8_1     | 1         | 0.83%   |
| 6.2.8_1     | 1         | 0.83%   |
| 6.2.11_1    | 1         | 0.83%   |
| 6.1.3_1     | 1         | 0.83%   |
| 6.1.29_1    | 1         | 0.83%   |
| 6.1.18_1    | 1         | 0.83%   |
| 6.1.14_1    | 1         | 0.83%   |
| 6.1.13_1    | 1         | 0.83%   |
| 6.0.9_1     | 1         | 0.83%   |
| 6.0.15_1    | 1         | 0.83%   |
| 6.0.10_1    | 1         | 0.83%   |
| 5.9.16_1    | 1         | 0.83%   |
| 5.9.14_1    | 1         | 0.83%   |
| 5.9.0-rc8_2 | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.13  | 7         | 5.83%   |
| 5.13.19 | 5         | 4.17%   |
| 5.8.12  | 4         | 3.33%   |
| 5.18.19 | 4         | 3.33%   |
| 6.3.12  | 3         | 2.5%    |
| 6.1.4   | 3         | 2.5%    |
| 5.8.18  | 3         | 2.5%    |
| 5.3.9   | 3         | 2.5%    |
| 5.19.17 | 3         | 2.5%    |
| 5.10.17 | 3         | 2.5%    |
| 6.5.13  | 2         | 1.67%   |
| 6.5.11  | 2         | 1.67%   |
| 6.5.10  | 2         | 1.67%   |
| 6.1.31  | 2         | 1.67%   |
| 6.1.21  | 2         | 1.67%   |
| 6.1.10  | 2         | 1.67%   |
| 5.4.24  | 2         | 1.67%   |
| 5.19.16 | 2         | 1.67%   |
| 5.18.14 | 2         | 1.67%   |
| 5.16.20 | 2         | 1.67%   |
| 5.15.32 | 2         | 1.67%   |
| 5.13.13 | 2         | 1.67%   |
| 5.12.10 | 2         | 1.67%   |
| 6.6.1   | 1         | 0.83%   |
| 6.5.5   | 1         | 0.83%   |
| 6.5.12  | 1         | 0.83%   |
| 6.4.8   | 1         | 0.83%   |
| 6.2.8   | 1         | 0.83%   |
| 6.2.11  | 1         | 0.83%   |
| 6.1.3   | 1         | 0.83%   |
| 6.1.29  | 1         | 0.83%   |
| 6.1.18  | 1         | 0.83%   |
| 6.1.14  | 1         | 0.83%   |
| 6.1.13  | 1         | 0.83%   |
| 6.0.9   | 1         | 0.83%   |
| 6.0.15  | 1         | 0.83%   |
| 6.0.10  | 1         | 0.83%   |
| 5.9.16  | 1         | 0.83%   |
| 5.9.14  | 1         | 0.83%   |
| 5.9.0   | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 14        | 11.76%  |
| 5.15    | 12        | 10.08%  |
| 5.8     | 11        | 9.24%   |
| 5.13    | 11        | 9.24%   |
| 6.3     | 10        | 8.4%    |
| 6.5     | 8         | 6.72%   |
| 5.18    | 7         | 5.88%   |
| 5.12    | 7         | 5.88%   |
| 5.10    | 7         | 5.88%   |
| 5.4     | 5         | 4.2%    |
| 5.19    | 5         | 4.2%    |
| 6.0     | 3         | 2.52%   |
| 5.9     | 3         | 2.52%   |
| 5.3     | 3         | 2.52%   |
| 6.2     | 2         | 1.68%   |
| 5.16    | 2         | 1.68%   |
| 6.6     | 1         | 0.84%   |
| 6.4     | 1         | 0.84%   |
| 5.7     | 1         | 0.84%   |
| 5.2     | 1         | 0.84%   |
| 5.14    | 1         | 0.84%   |
| 5.11    | 1         | 0.84%   |
| 5.1     | 1         | 0.84%   |
| 4.4     | 1         | 0.84%   |
| 4.14    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 110       | 94.83%  |
| i686    | 4         | 3.45%   |
| aarch64 | 2         | 1.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 47        | 39.5%   |
| XFCE         | 18        | 15.13%  |
| KDE          | 10        | 8.4%    |
| MATE         | 9         | 7.56%   |
| KDE5         | 8         | 6.72%   |
| i3           | 6         | 5.04%   |
| GNOME        | 6         | 5.04%   |
| X-Cinnamon   | 2         | 1.68%   |
| sway         | 2         | 1.68%   |
| bspwm        | 2         | 1.68%   |
| awesome      | 2         | 1.68%   |
| river        | 1         | 0.84%   |
| openbox      | 1         | 0.84%   |
| LXQt         | 1         | 0.84%   |
| LXDE         | 1         | 0.84%   |
| Lumina       | 1         | 0.84%   |
| dwm          | 1         | 0.84%   |
| dot-xsession | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 81        | 69.23%  |
| Wayland | 16        | 13.68%  |
| Tty     | 13        | 11.11%  |
| Unknown | 7         | 5.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 85        | 72.65%  |
| LightDM | 15        | 12.82%  |
| SDDM    | 8         | 6.84%   |
| LXDM    | 6         | 5.13%   |
| SLiM    | 1         | 0.85%   |
| LDM     | 1         | 0.85%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 62        | 52.54%  |
| Unknown | 11        | 9.32%   |
| en_GB   | 9         | 7.63%   |
| it_IT   | 5         | 4.24%   |
| es_ES   | 4         | 3.39%   |
| en_DK   | 4         | 3.39%   |
| de_DE   | 4         | 3.39%   |
| C       | 3         | 2.54%   |
| fr_FR   | 2         | 1.69%   |
| en_CA   | 2         | 1.69%   |
| tr_TR   | 1         | 0.85%   |
| ru_UA   | 1         | 0.85%   |
| ru_RU   | 1         | 0.85%   |
| pt_BR   | 1         | 0.85%   |
| nb_NO   | 1         | 0.85%   |
| es_HN   | 1         | 0.85%   |
| es_DO   | 1         | 0.85%   |
| es_AR   | 1         | 0.85%   |
| en_NZ   | 1         | 0.85%   |
| en_AU   | 1         | 0.85%   |
| el_GR   | 1         | 0.85%   |
| ca_ES   | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 61.54%  |
| BIOS | 45        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 72        | 61.54%  |
| Btrfs   | 29        | 24.79%  |
| Unknown | 5         | 4.27%   |
| Xfs     | 4         | 3.42%   |
| Zfs     | 3         | 2.56%   |
| F2fs    | 2         | 1.71%   |
| Overlay | 1         | 0.85%   |
| Ext3    | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 75        | 63.56%  |
| Unknown | 29        | 24.58%  |
| MBR     | 14        | 11.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 89.66%  |
| Yes       | 12        | 10.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 77.59%  |
| Yes       | 26        | 22.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 25.86%  |
| Hewlett-Packard     | 18        | 15.52%  |
| Acer                | 16        | 13.79%  |
| ASUSTek Computer    | 15        | 12.93%  |
| Dell                | 11        | 9.48%   |
| MSI                 | 6         | 5.17%   |
| Unknown             | 3         | 2.59%   |
| Notebook            | 2         | 1.72%   |
| HUAWEI              | 2         | 1.72%   |
| Timi                | 1         | 0.86%   |
| Samsung Electronics | 1         | 0.86%   |
| Razer               | 1         | 0.86%   |
| Positivo            | 1         | 0.86%   |
| Pine Microsystems   | 1         | 0.86%   |
| Nokia               | 1         | 0.86%   |
| Google              | 1         | 0.86%   |
| Getac               | 1         | 0.86%   |
| Framework           | 1         | 0.86%   |
| Exo                 | 1         | 0.86%   |
| Digibras            | 1         | 0.86%   |
| Chuwi               | 1         | 0.86%   |
| Apple               | 1         | 0.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.59%   |
| HP Pavilion Notebook                      | 2         | 1.72%   |
| HP Laptop 15-bw0xx                        | 2         | 1.72%   |
| HP 15                                     | 2         | 1.72%   |
| ASUS X751LD                               | 2         | 1.72%   |
| Acer Swift SF314-42                       | 2         | 1.72%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.86%   |
| Samsung 275E4E/275E5E                     | 1         | 0.86%   |
| Razer Blade 14 (2022) - RZ09-0427         | 1         | 0.86%   |
| Positivo Mobile                           | 1         | 0.86%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.86%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.86%   |
| Notebook NH50_70RA                        | 1         | 0.86%   |
| Nokia Booklet 3G                          | 1         | 0.86%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.86%   |
| MSI Prestige 15 A10SC                     | 1         | 0.86%   |
| MSI GV72 7RE                              | 1         | 0.86%   |
| MSI GF63 Thin 10SCXR                      | 1         | 0.86%   |
| MSI GE60 2OC\2OD\2OE                      | 1         | 0.86%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.86%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.86%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.86%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.86%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.86%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.86%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.86%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.86%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.86%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.86%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 0.86%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 0.86%   |
| Lenovo ThinkPad T16 Gen 1 21CHCTO1WW      | 1         | 0.86%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 0.86%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 0.86%   |
| Lenovo ThinkPad T14 Gen 2a 20XLS02500     | 1         | 0.86%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 0.86%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 1         | 0.86%   |
| Lenovo ThinkPad E595 20NFCTO1WW           | 1         | 0.86%   |
| Lenovo ThinkBook 14 G3 ACL 21A2           | 1         | 0.86%   |
| Lenovo Legion Y540-15IRH-PG0 81SY         | 1         | 0.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 17        | 14.66%  |
| Acer Aspire              | 10        | 8.62%   |
| Lenovo IdeaPad           | 7         | 6.03%   |
| ASUS VivoBook            | 7         | 6.03%   |
| HP Pavilion              | 5         | 4.31%   |
| HP Laptop                | 5         | 4.31%   |
| Dell Latitude            | 4         | 3.45%   |
| Dell Inspiron            | 4         | 3.45%   |
| Unknown                  | 3         | 2.59%   |
| HP ENVY                  | 2         | 1.72%   |
| HP 255                   | 2         | 1.72%   |
| HP 15                    | 2         | 1.72%   |
| ASUS X751LD              | 2         | 1.72%   |
| Acer Swift               | 2         | 1.72%   |
| Timi Redmi               | 1         | 0.86%   |
| Samsung 275E4E           | 1         | 0.86%   |
| Razer Blade              | 1         | 0.86%   |
| Positivo Mobile          | 1         | 0.86%   |
| Pine Microsystems Pine64 | 1         | 0.86%   |
| Notebook NV4XMB          | 1         | 0.86%   |
| Notebook NH50            | 1         | 0.86%   |
| Nokia Booklet            | 1         | 0.86%   |
| MSI Summit               | 1         | 0.86%   |
| MSI Prestige             | 1         | 0.86%   |
| MSI GV72                 | 1         | 0.86%   |
| MSI GF63                 | 1         | 0.86%   |
| MSI GE60                 | 1         | 0.86%   |
| MSI Bravo                | 1         | 0.86%   |
| Lenovo Y520-15IKB        | 1         | 0.86%   |
| Lenovo ThinkBook         | 1         | 0.86%   |
| Lenovo Legion            | 1         | 0.86%   |
| Lenovo G50-70            | 1         | 0.86%   |
| Lenovo G50-45            | 1         | 0.86%   |
| Lenovo Ducati            | 1         | 0.86%   |
| HUAWEI KLVL-WXXW         | 1         | 0.86%   |
| HUAWEI HN-WX9X           | 1         | 0.86%   |
| HP Stream                | 1         | 0.86%   |
| HP Notebook              | 1         | 0.86%   |
| Google Phaser360         | 1         | 0.86%   |
| Getac V110               | 1         | 0.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 19        | 16.38%  |
| 2020    | 16        | 13.79%  |
| 2022    | 10        | 8.62%   |
| 2013    | 10        | 8.62%   |
| 2014    | 9         | 7.76%   |
| 2018    | 8         | 6.9%    |
| 2015    | 8         | 6.9%    |
| 2016    | 7         | 6.03%   |
| 2021    | 6         | 5.17%   |
| 2017    | 5         | 4.31%   |
| 2011    | 4         | 3.45%   |
| 2012    | 3         | 2.59%   |
| 2010    | 2         | 1.72%   |
| 2009    | 2         | 1.72%   |
| 2008    | 2         | 1.72%   |
| Unknown | 2         | 1.72%   |
| 2007    | 1         | 0.86%   |
| 2006    | 1         | 0.86%   |
| 2005    | 1         | 0.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 116       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 116       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 99.14%  |
| Yes  | 1         | 0.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 26.5%   |
| 3.01-4.0    | 26        | 22.22%  |
| 8.01-16.0   | 21        | 17.95%  |
| 16.01-24.0  | 19        | 16.24%  |
| 1.01-2.0    | 7         | 5.98%   |
| 32.01-64.0  | 6         | 5.13%   |
| 24.01-32.0  | 3         | 2.56%   |
| 0.51-1.0    | 2         | 1.71%   |
| 64.01-256.0 | 1         | 0.85%   |
| 0.01-0.5    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 44        | 36.67%  |
| 2.01-3.0   | 29        | 24.17%  |
| 0.51-1.0   | 16        | 13.33%  |
| 4.01-8.0   | 13        | 10.83%  |
| 3.01-4.0   | 10        | 8.33%   |
| 0.01-0.5   | 5         | 4.17%   |
| 8.01-16.0  | 2         | 1.67%   |
| 16.01-24.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 77.59%  |
| 2      | 23        | 19.83%  |
| 3      | 2         | 1.72%   |
| 0      | 1         | 0.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 75.86%  |
| Yes       | 28        | 24.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 71.55%  |
| No        | 33        | 28.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 96.55%  |
| No        | 4         | 3.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 83.62%  |
| No        | 19        | 16.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 18        | 15.52%  |
| Russia             | 12        | 10.34%  |
| Germany            | 11        | 9.48%   |
| India              | 9         | 7.76%   |
| Italy              | 5         | 4.31%   |
| Brazil             | 5         | 4.31%   |
| Ukraine            | 4         | 3.45%   |
| Switzerland        | 4         | 3.45%   |
| Denmark            | 4         | 3.45%   |
| UK                 | 3         | 2.59%   |
| France             | 3         | 2.59%   |
| Turkey             | 2         | 1.72%   |
| Spain              | 2         | 1.72%   |
| Netherlands        | 2         | 1.72%   |
| Morocco            | 2         | 1.72%   |
| Greece             | 2         | 1.72%   |
| Canada             | 2         | 1.72%   |
| Bulgaria           | 2         | 1.72%   |
| Australia          | 2         | 1.72%   |
| Argentina          | 2         | 1.72%   |
| Vietnam            | 1         | 0.86%   |
| Uruguay            | 1         | 0.86%   |
| Thailand           | 1         | 0.86%   |
| Serbia             | 1         | 0.86%   |
| Portugal           | 1         | 0.86%   |
| Peru               | 1         | 0.86%   |
| Norway             | 1         | 0.86%   |
| New Zealand        | 1         | 0.86%   |
| Mexico             | 1         | 0.86%   |
| Latvia             | 1         | 0.86%   |
| Jordan             | 1         | 0.86%   |
| Indonesia          | 1         | 0.86%   |
| Honduras           | 1         | 0.86%   |
| Guatemala          | 1         | 0.86%   |
| Grenada            | 1         | 0.86%   |
| Ecuador            | 1         | 0.86%   |
| Dominican Republic | 1         | 0.86%   |
| Czechia            | 1         | 0.86%   |
| Colombia           | 1         | 0.86%   |
| Austria            | 1         | 0.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 6         | 5.13%   |
| St Petersburg          | 3         | 2.56%   |
| Spring Hill            | 2         | 1.71%   |
| Sao Paulo              | 2         | 1.71%   |
| Rome                   | 2         | 1.71%   |
| Meknes                 | 2         | 1.71%   |
| Hyderabad              | 2         | 1.71%   |
| Geneva                 | 2         | 1.71%   |
| Zarqa                  | 1         | 0.85%   |
| Yambol                 | 1         | 0.85%   |
| Wilen bei Wollerau     | 1         | 0.85%   |
| Weatherford            | 1         | 0.85%   |
| Volgograd              | 1         | 0.85%   |
| Vlaardingen            | 1         | 0.85%   |
| Vienna                 | 1         | 0.85%   |
| Viby J                 | 1         | 0.85%   |
| Verkhnyaya Pyshma      | 1         | 0.85%   |
| Trujillo               | 1         | 0.85%   |
| Toulouse               | 1         | 0.85%   |
| Touget                 | 1         | 0.85%   |
| Toms River             | 1         | 0.85%   |
| Tegucigalpa            | 1         | 0.85%   |
| Syktyvkar              | 1         | 0.85%   |
| Sydney                 | 1         | 0.85%   |
| Surabaya               | 1         | 0.85%   |
| Sun Prairie            | 1         | 0.85%   |
| Stratford              | 1         | 0.85%   |
| Stezzano               | 1         | 0.85%   |
| Solone                 | 1         | 0.85%   |
| Sohren                 | 1         | 0.85%   |
| Sofia                  | 1         | 0.85%   |
| Sistranda              | 1         | 0.85%   |
| Saxtons River          | 1         | 0.85%   |
| Santo Domingo          | 1         | 0.85%   |
| San Miguel de Tucumán | 1         | 0.85%   |
| Saint George's         | 1         | 0.85%   |
| Rostock                | 1         | 0.85%   |
| Rosenheim              | 1         | 0.85%   |
| River Grove            | 1         | 0.85%   |
| Riga                   | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 26        | 27     | 18.98%  |
| Seagate                     | 18        | 19     | 13.14%  |
| WDC                         | 13        | 14     | 9.49%   |
| Unknown                     | 11        | 17     | 8.03%   |
| Sandisk                     | 10        | 11     | 7.3%    |
| SK hynix                    | 8         | 8      | 5.84%   |
| HGST                        | 7         | 8      | 5.11%   |
| Intel                       | 6         | 7      | 4.38%   |
| Toshiba                     | 5         | 5      | 3.65%   |
| Kingston                    | 5         | 5      | 3.65%   |
| Crucial                     | 5         | 5      | 3.65%   |
| Hitachi                     | 3         | 3      | 2.19%   |
| Phison                      | 2         | 2      | 1.46%   |
| Micron Technology           | 2         | 2      | 1.46%   |
| Kingston Technology Company | 2         | 2      | 1.46%   |
| XrayDisk                    | 1         | 1      | 0.73%   |
| Transcend                   | 1         | 1      | 0.73%   |
| PNY                         | 1         | 1      | 0.73%   |
| Phison Electronics          | 1         | 1      | 0.73%   |
| Patriot                     | 1         | 1      | 0.73%   |
| ORIGIN                      | 1         | 1      | 0.73%   |
| Micron/Crucial Technology   | 1         | 1      | 0.73%   |
| Lenovo                      | 1         | 1      | 0.73%   |
| KIOXIA                      | 1         | 1      | 0.73%   |
| INNOVATION IT               | 1         | 1      | 0.73%   |
| IBM/Hitachi                 | 1         | 1      | 0.73%   |
| China                       | 1         | 1      | 0.73%   |
| BHT                         | 1         | 1      | 0.73%   |
| Apple                       | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 2.82%   |
| Unknown MMC Card  32GB                              | 3         | 2.11%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 2.11%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 2.11%   |
| HGST HTS545050A7E680 500GB                          | 3         | 2.11%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 2.11%   |
| Unknown MMC Card  64GB                              | 2         | 1.41%   |
| Unknown MMC Card  128GB                             | 2         | 1.41%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB             | 2         | 1.41%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 2         | 1.41%   |
| Samsung SSD 870 EVO 500GB                           | 2         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 1.41%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 1.41%   |
| HGST HTS541010B7E610 1TB                            | 2         | 1.41%   |
| HGST HTS541010A9E680 1TB                            | 2         | 1.41%   |
| XrayDisk 128GB                                      | 1         | 0.7%    |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 0.7%    |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.7%    |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.7%    |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 0.7%    |
| WDC WD1600BEVS-60VAT0 160GB                         | 1         | 0.7%    |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.7%    |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.7%    |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.7%    |
| WDC WD Elements 320GB                               | 1         | 0.7%    |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB                  | 1         | 0.7%    |
| WDC PC SN520 SDAPNUW-512G-1014 512GB                | 1         | 0.7%    |
| Unknown USB DISK 3.2 1TB                            | 1         | 0.7%    |
| Unknown SD512  512MB                                | 1         | 0.7%    |
| Unknown SD16G  16GB                                 | 1         | 0.7%    |
| Unknown SD/MMC/MS PRO 512GB                         | 1         | 0.7%    |
| Unknown MMC Card  8GB                               | 1         | 0.7%    |
| Unknown MMC Card  2GB                               | 1         | 0.7%    |
| Unknown MMC Card                                    | 1         | 0.7%    |
| Unknown CWBC3R  64GB                                | 1         | 0.7%    |

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
| Samsung Electronics | 8         | 8      | 24.24%  |
| SanDisk             | 5         | 5      | 15.15%  |
| Crucial             | 5         | 5      | 15.15%  |
| Kingston            | 4         | 4      | 12.12%  |
| Transcend           | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| ORIGIN              | 1         | 1      | 3.03%   |
| Lenovo              | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| INNOVATION IT       | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| BHT                 | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 45        | 51     | 33.83%  |
| HDD     | 45        | 48     | 33.83%  |
| SSD     | 31        | 33     | 23.31%  |
| MMC     | 10        | 14     | 7.52%   |
| Unknown | 2         | 3      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 77     | 53.08%  |
| NVMe | 45        | 51     | 34.62%  |
| MMC  | 10        | 14     | 7.69%   |
| SAS  | 6         | 7      | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 48     | 56.58%  |
| 0.51-1.0   | 32        | 32     | 42.11%  |
| 4.01-10.0  | 1         | 1      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 36        | 30.51%  |
| 501-1000       | 28        | 23.73%  |
| 101-250        | 24        | 20.34%  |
| Unknown        | 7         | 5.93%   |
| 1-20           | 6         | 5.08%   |
| 51-100         | 6         | 5.08%   |
| 21-50          | 5         | 4.24%   |
| 1001-2000      | 4         | 3.39%   |
| More than 3000 | 1         | 0.85%   |
| 2001-3000      | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 27.97%  |
| 101-250        | 27        | 22.88%  |
| 21-50          | 22        | 18.64%  |
| 51-100         | 14        | 11.86%  |
| 251-500        | 9         | 7.63%   |
| Unknown        | 7         | 5.93%   |
| 1001-2000      | 3         | 2.54%   |
| 501-1000       | 2         | 1.69%   |
| More than 3000 | 1         | 0.85%   |

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
| Works    | 66        | 78     | 52.8%   |
| Detected | 42        | 54     | 33.6%   |
| Malfunc  | 17        | 17     | 13.6%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 49.25%  |
| AMD                              | 24        | 17.91%  |
| Samsung Electronics              | 18        | 13.43%  |
| SK hynix                         | 7         | 5.22%   |
| SanDisk                          | 7         | 5.22%   |
| Phison Electronics               | 3         | 2.24%   |
| Kingston Technology Company      | 3         | 2.24%   |
| Micron Technology                | 2         | 1.49%   |
| Toshiba America Info Systems     | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Micron/Crucial Technology        | 1         | 0.75%   |
| KIOXIA                           | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 22        | 15.94%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 7.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 6.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 8         | 5.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 3.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 4         | 2.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 4         | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 2.9%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 3         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 3         | 2.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 3         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.17%   |
| Intel SSD 660P Series                                                        | 3         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.17%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 2         | 1.45%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 2         | 1.45%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 2         | 1.45%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 2         | 1.45%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.45%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                               | 2         | 1.45%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 2         | 1.45%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.45%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.72%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.72%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.72%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.72%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.72%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.72%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 77        | 57.46%  |
| NVMe | 45        | 33.58%  |
| RAID | 6         | 4.48%   |
| IDE  | 6         | 4.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 67.24%  |
| AMD    | 36        | 31.03%  |
| ARM    | 2         | 1.72%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.59%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 2.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.72%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.72%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 1.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.72%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.72%   |
| ARM Processor                                 | 2         | 1.72%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.72%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.72%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.72%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.72%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.72%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.86%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.86%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 0.86%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.86%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.86%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.86%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.86%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.86%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.86%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 18.97%  |
| Intel Core i7           | 19        | 16.38%  |
| Intel Core i3           | 13        | 11.21%  |
| Other                   | 11        | 9.48%   |
| AMD Ryzen 5             | 10        | 8.62%   |
| Intel Celeron           | 8         | 6.9%    |
| AMD Ryzen 7             | 7         | 6.03%   |
| Intel Atom              | 5         | 4.31%   |
| AMD Ryzen 7 PRO         | 4         | 3.45%   |
| Intel Pentium           | 2         | 1.72%   |
| AMD Ryzen 3             | 2         | 1.72%   |
| AMD A8                  | 2         | 1.72%   |
| Intel Pentium M         | 1         | 0.86%   |
| Intel Genuine           | 1         | 0.86%   |
| Intel Core 2 Duo        | 1         | 0.86%   |
| AMD Turion 64 X2 Mobile | 1         | 0.86%   |
| AMD Ryzen 9             | 1         | 0.86%   |
| AMD Ryzen 5 PRO         | 1         | 0.86%   |
| AMD E2                  | 1         | 0.86%   |
| AMD E1                  | 1         | 0.86%   |
| AMD C-60                | 1         | 0.86%   |
| AMD A6                  | 1         | 0.86%   |
| AMD A4                  | 1         | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 38.79%  |
| 4      | 38        | 32.76%  |
| 6      | 15        | 12.93%  |
| 8      | 9         | 7.76%   |
| 1      | 6         | 5.17%   |
| 14     | 2         | 1.72%   |
| 10     | 1         | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 99.14%  |
| 2      | 1         | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 84        | 72.41%  |
| 1      | 32        | 27.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 92.24%  |
| Unknown        | 4         | 3.45%   |
| 32-bit         | 3         | 2.59%   |
| 64-bit         | 2         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 34.75%  |
| 0x40651    | 8         | 6.78%   |
| 0x406e3    | 4         | 3.39%   |
| 0x306a9    | 4         | 3.39%   |
| 0x08108102 | 4         | 3.39%   |
| 0x906ea    | 3         | 2.54%   |
| 0x806ec    | 3         | 2.54%   |
| 0x806e9    | 3         | 2.54%   |
| 0x30678    | 3         | 2.54%   |
| 0x206a7    | 3         | 2.54%   |
| 0x0a404102 | 3         | 2.54%   |
| 0x08600104 | 3         | 2.54%   |
| 0x906e9    | 2         | 1.69%   |
| 0x906a3    | 2         | 1.69%   |
| 0x106c2    | 2         | 1.69%   |
| 0x0a50000c | 2         | 1.69%   |
| 0x08608103 | 2         | 1.69%   |
| 0x07030105 | 2         | 1.69%   |
| 0x06006705 | 2         | 1.69%   |
| 0x05000119 | 2         | 1.69%   |
| 0xa0652    | 1         | 0.85%   |
| 0x806eb    | 1         | 0.85%   |
| 0x806ea    | 1         | 0.85%   |
| 0x806c1    | 1         | 0.85%   |
| 0x706e5    | 1         | 0.85%   |
| 0x406c4    | 1         | 0.85%   |
| 0x306d4    | 1         | 0.85%   |
| 0x30673    | 1         | 0.85%   |
| 0x20652    | 1         | 0.85%   |
| 0x106ca    | 1         | 0.85%   |
| 0x10661    | 1         | 0.85%   |
| 0x0a404101 | 1         | 0.85%   |
| 0x08608102 | 1         | 0.85%   |
| 0x08600106 | 1         | 0.85%   |
| 0x08600103 | 1         | 0.85%   |
| 0x08600102 | 1         | 0.85%   |
| 0x08108109 | 1         | 0.85%   |
| 0x0810100b | 1         | 0.85%   |
| 0x08101007 | 1         | 0.85%   |
| 0x07030104 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 18.1%   |
| Haswell          | 11        | 9.48%   |
| Unknown          | 9         | 7.76%   |
| Zen 2            | 7         | 6.03%   |
| Skylake          | 6         | 5.17%   |
| Silvermont       | 6         | 5.17%   |
| Zen+             | 5         | 4.31%   |
| Zen 3            | 4         | 3.45%   |
| SandyBridge      | 4         | 3.45%   |
| IvyBridge        | 4         | 3.45%   |
| Excavator        | 4         | 3.45%   |
| TigerLake        | 3         | 2.59%   |
| Puma             | 3         | 2.59%   |
| IceLake          | 3         | 2.59%   |
| CometLake        | 3         | 2.59%   |
| Broadwell        | 3         | 2.59%   |
| Bonnell          | 3         | 2.59%   |
| Alderlake Hybrid | 3         | 2.59%   |
| Zen              | 2         | 1.72%   |
| Goldmont plus    | 2         | 1.72%   |
| Core             | 2         | 1.72%   |
| Bobcat           | 2         | 1.72%   |
| Westmere         | 1         | 0.86%   |
| Penryn           | 1         | 0.86%   |
| P6               | 1         | 0.86%   |
| K8 Hammer        | 1         | 0.86%   |
| Jaguar           | 1         | 0.86%   |
| Goldmont         | 1         | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 52.05%  |
| AMD                              | 37        | 25.34%  |
| Nvidia                           | 32        | 21.92%  |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 6.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 6         | 4%      |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 4%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 5         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.67%   |
| AMD Rembrandt [Radeon 680M]                                               | 4         | 2.67%   |
| Intel UHD Graphics 620                                                    | 3         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 2%      |
| Intel HD Graphics 620                                                     | 3         | 2%      |
| Intel HD Graphics 5500                                                    | 3         | 2%      |
| AMD Lucienne                                                              | 3         | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2%      |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.33%   |
| Intel HD Graphics 630                                                     | 2         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.33%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.33%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.67%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.67%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.67%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.67%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 39.66%  |
| 1 x AMD        | 30        | 25.86%  |
| Intel + Nvidia | 27        | 23.28%  |
| AMD + Nvidia   | 4         | 3.45%   |
| Other          | 3         | 2.59%   |
| 2 x AMD        | 2         | 1.72%   |
| 2 x Intel      | 1         | 0.86%   |
| 1 x SiS        | 1         | 0.86%   |
| 1 x Nvidia     | 1         | 0.86%   |
| Intel + AMD    | 1         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 78.45%  |
| Proprietary | 22        | 18.97%  |
| Unknown     | 3         | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 66.39%  |
| 0.01-0.5   | 14        | 11.76%  |
| 1.01-2.0   | 10        | 8.4%    |
| 0.51-1.0   | 7         | 5.88%   |
| 3.01-4.0   | 6         | 5.04%   |
| 7.01-8.0   | 2         | 1.68%   |
| 5.01-6.0   | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 29        | 23.77%  |
| AU Optronics         | 24        | 19.67%  |
| BOE                  | 19        | 15.57%  |
| LG Display           | 16        | 13.11%  |
| Samsung Electronics  | 5         | 4.1%    |
| PANDA                | 4         | 3.28%   |
| TMX                  | 2         | 1.64%   |
| Sharp                | 2         | 1.64%   |
| Philips              | 2         | 1.64%   |
| LG Philips           | 2         | 1.64%   |
| Lenovo               | 2         | 1.64%   |
| Hewlett-Packard      | 2         | 1.64%   |
| Apple                | 2         | 1.64%   |
| AOC                  | 2         | 1.64%   |
| STD                  | 1         | 0.82%   |
| Quanta Display       | 1         | 0.82%   |
| Panasonic            | 1         | 0.82%   |
| InnoLux Display      | 1         | 0.82%   |
| Iiyama               | 1         | 0.82%   |
| Goldstar             | 1         | 0.82%   |
| CHR                  | 1         | 0.82%   |
| BOE Technology Group | 1         | 0.82%   |
| Unknown              | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.46%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.64%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.64%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 1.64%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.82%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.82%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.82%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.82%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.82%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.82%   |
| Quanta Display LCD Monitor QDS0015 1024x768 285x214mm 14.0-inch       | 1         | 0.82%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.82%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.82%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.82%   |
| PANDA LCD Monitor NCP003D 1920x1080 344x194mm 15.5-inch               | 1         | 0.82%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.82%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.82%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 49        | 41.18%  |
| 1366x768 (WXGA)   | 35        | 29.41%  |
| 1920x1200 (WUXGA) | 7         | 5.88%   |
| 1600x900 (HD+)    | 5         | 4.2%    |
| 2560x1440 (QHD)   | 3         | 2.52%   |
| 2160x1440         | 3         | 2.52%   |
| 1280x800 (WXGA)   | 3         | 2.52%   |
| 3840x2160 (4K)    | 2         | 1.68%   |
| 2560x1600         | 2         | 1.68%   |
| 1024x600          | 2         | 1.68%   |
| 3440x1440         | 1         | 0.84%   |
| 3200x2000         | 1         | 0.84%   |
| 2880x1800         | 1         | 0.84%   |
| 2288x1287         | 1         | 0.84%   |
| 2256x1504         | 1         | 0.84%   |
| 1360x768          | 1         | 0.84%   |
| 1280x720 (HD)     | 1         | 0.84%   |
| 1024x768 (XGA)    | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 40.98%  |
| 14      | 22        | 18.03%  |
| 13      | 14        | 11.48%  |
| 11      | 6         | 4.92%   |
| 17      | 5         | 4.1%    |
| 12      | 4         | 3.28%   |
| 24      | 3         | 2.46%   |
| 23      | 3         | 2.46%   |
| 16      | 3         | 2.46%   |
| 10      | 2         | 1.64%   |
| Unknown | 2         | 1.64%   |
| 84      | 1         | 0.82%   |
| 39      | 1         | 0.82%   |
| 34      | 1         | 0.82%   |
| 33      | 1         | 0.82%   |
| 32      | 1         | 0.82%   |
| 21      | 1         | 0.82%   |
| 18      | 1         | 0.82%   |
| 8       | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 64.75%  |
| 201-300     | 22        | 18.03%  |
| 501-600     | 6         | 4.92%   |
| 351-400     | 5         | 4.1%    |
| 701-800     | 3         | 2.46%   |
| 401-500     | 2         | 1.64%   |
| Unknown     | 2         | 1.64%   |
| 801-900     | 1         | 0.82%   |
| 1501-2000   | 1         | 0.82%   |
| 101-200     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 79.65%  |
| 16/10   | 15        | 13.27%  |
| 3/2     | 5         | 4.42%   |
| 4/3     | 1         | 0.88%   |
| 21/9    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 40.16%  |
| 81-90          | 28        | 22.95%  |
| 71-80          | 6         | 4.92%   |
| 51-60          | 6         | 4.92%   |
| 201-250        | 5         | 4.1%    |
| 61-70          | 4         | 3.28%   |
| 111-120        | 4         | 3.28%   |
| 351-500        | 3         | 2.46%   |
| 121-130        | 3         | 2.46%   |
| 41-50          | 2         | 1.64%   |
| 251-300        | 2         | 1.64%   |
| 131-140        | 2         | 1.64%   |
| 91-100         | 2         | 1.64%   |
| Unknown        | 2         | 1.64%   |
| More than 1000 | 1         | 0.82%   |
| 1-40           | 1         | 0.82%   |
| 141-150        | 1         | 0.82%   |
| 501-1000       | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 46.28%  |
| 101-120       | 30        | 24.79%  |
| 51-100        | 17        | 14.05%  |
| 161-240       | 14        | 11.57%  |
| More than 240 | 2         | 1.65%   |
| Unknown       | 2         | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 85.34%  |
| 2     | 15        | 12.93%  |
| 0     | 2         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 64        | 37.87%  |
| Intel                            | 47        | 27.81%  |
| Qualcomm Atheros                 | 21        | 12.43%  |
| Broadcom                         | 11        | 6.51%   |
| MediaTek                         | 4         | 2.37%   |
| Broadcom Limited                 | 4         | 2.37%   |
| Sierra Wireless                  | 3         | 1.78%   |
| Ralink Technology                | 3         | 1.78%   |
| Qualcomm                         | 3         | 1.78%   |
| Ralink                           | 2         | 1.18%   |
| Cypress Semiconductor            | 2         | 1.18%   |
| Xiaomi                           | 1         | 0.59%   |
| TP-Link                          | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |
| Marvell Technology Group         | 1         | 0.59%   |
| Huawei Technologies              | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 19.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.9%    |
| Intel Wi-Fi 6 AX200                                               | 9         | 4.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 3.45%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.46%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.97%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.48%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 3         | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.99%   |
| Intel Wireless 8260                                               | 2         | 0.99%   |
| Intel Wireless 7260                                               | 2         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.99%   |
| Cypress USB Type-C Dock                                           | 2         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.49%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.49%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 1         | 0.49%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.49%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 39.83%  |
| Realtek Semiconductor | 26        | 22.03%  |
| Qualcomm Atheros      | 18        | 15.25%  |
| Broadcom              | 9         | 7.63%   |
| MediaTek              | 4         | 3.39%   |
| Sierra Wireless       | 3         | 2.54%   |
| Ralink Technology     | 3         | 2.54%   |
| Qualcomm              | 3         | 2.54%   |
| Broadcom Limited      | 3         | 2.54%   |
| Ralink                | 2         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 9         | 7.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 5.93%   |
| Intel Wireless 8265 / 8275                                    | 6         | 5.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 4.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 4.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 4.24%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 3.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 4         | 3.39%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 3         | 2.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 3         | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 2.54%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 2.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 2.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.69%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.69%   |
| Intel Wireless 8260                                           | 2         | 1.69%   |
| Intel Wireless 7260                                           | 2         | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 1.69%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.69%   |
| Broadcom BCM4311 802.11b/g WLAN                               | 2         | 1.69%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A           | 1         | 0.85%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.85%   |
| Sierra Wireless EM7305 Modem                                  | 1         | 0.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 0.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 1         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 55        | 65.48%  |
| Intel                            | 14        | 16.67%  |
| Qualcomm Atheros                 | 4         | 4.76%   |
| Broadcom                         | 3         | 3.57%   |
| Cypress Semiconductor            | 2         | 2.38%   |
| Xiaomi                           | 1         | 1.19%   |
| TP-Link                          | 1         | 1.19%   |
| Silicon Integrated Systems [SiS] | 1         | 1.19%   |
| Marvell Technology Group         | 1         | 1.19%   |
| Huawei Technologies              | 1         | 1.19%   |
| Broadcom Limited                 | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 46.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.38%   |
| Cypress USB Type-C Dock                                           | 2         | 2.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.19%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.19%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.19%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.19%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.19%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.19%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.19%   |
| Huawei MAR-LX1M                                                   | 1         | 1.19%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.19%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.19%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.19%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 57.14%  |
| Ethernet | 83        | 42.35%  |
| Modem    | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 84.75%  |
| Ethernet | 18        | 15.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 62.93%  |
| 1     | 36        | 31.03%  |
| 0     | 5         | 4.31%   |
| 3     | 2         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 83.9%   |
| Yes  | 19        | 16.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 40.4%   |
| Realtek Semiconductor           | 16        | 16.16%  |
| Lite-On Technology              | 9         | 9.09%   |
| Broadcom                        | 7         | 7.07%   |
| IMC Networks                    | 6         | 6.06%   |
| Foxconn / Hon Hai               | 5         | 5.05%   |
| Qualcomm Atheros Communications | 4         | 4.04%   |
| USI                             | 2         | 2.02%   |
| Realtek                         | 2         | 2.02%   |
| Cambridge Silicon Radio         | 2         | 2.02%   |
| SIN                             | 1         | 1.01%   |
| Ralink                          | 1         | 1.01%   |
| Opticis                         | 1         | 1.01%   |
| Foxconn International           | 1         | 1.01%   |
| Dell                            | 1         | 1.01%   |
| Apple                           | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 12.12%  |
| Realtek Bluetooth Radio                             | 9         | 9.09%   |
| Intel Bluetooth Device                              | 9         | 9.09%   |
| Intel AX200 Bluetooth                               | 9         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 3.03%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 3.03%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 3.03%   |
| USI Bluetooth Device                                | 2         | 2.02%   |
| Realtek Bluetooth Radio                             | 2         | 2.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.02%   |
| Lite-On Bluetooth Device                            | 2         | 2.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.02%   |
| Intel AX210 Bluetooth                               | 2         | 2.02%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.02%   |
| IMC Networks Bluetooth Device                       | 2         | 2.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.02%   |
| SIN Bluetooth Keyboard                              | 1         | 1.01%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.01%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.01%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.01%   |
| Opticis Bluetooth Radio                             | 1         | 1.01%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.01%   |
| IMC Networks Wireless_Device                        | 1         | 1.01%   |
| IMC Networks Bluetooth                              | 1         | 1.01%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.01%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.01%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.01%   |
| Broadcom HP Portable Valentine                      | 1         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.01%   |
| Apple Bluetooth Host Controller                     | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 58.46%  |
| AMD                              | 36        | 27.69%  |
| Nvidia                           | 11        | 8.46%   |
| Texas Instruments                | 2         | 1.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.77%   |
| Logitech                         | 1         | 0.77%   |
| JMTek                            | 1         | 0.77%   |
| Creative Technology              | 1         | 0.77%   |
| Corsair                          | 1         | 0.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 13.56%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 7.34%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 6.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 5.65%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 5.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 2.82%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 2.26%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.26%   |
| AMD High Definition Audio Controller                                       | 4         | 2.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 2.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.69%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.13%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.13%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.13%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.13%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.56%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.56%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 31        | 29.52%  |
| Samsung Electronics | 30        | 28.57%  |
| Micron Technology   | 16        | 15.24%  |
| Kingston            | 7         | 6.67%   |
| Unknown             | 5         | 4.76%   |
| A-DATA Technology   | 4         | 3.81%   |
| Ramaxel Technology  | 2         | 1.9%    |
| Corsair             | 2         | 1.9%    |
| Unknown (ABCD)      | 1         | 0.95%   |
| Transcend           | 1         | 0.95%   |
| Team                | 1         | 0.95%   |
| Nanya Technology    | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |
| Crucial             | 1         | 0.95%   |
| 4ea5                | 1         | 0.95%   |
| 48spaces            | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.8%    |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 1.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.8%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.8%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 1.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.8%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.8%    |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.9%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.9%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.9%    |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.9%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.9%    |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.9%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.9%    |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.9%    |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.9%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 38        | 44.19%  |
| DDR3   | 33        | 38.37%  |
| LPDDR4 | 5         | 5.81%   |
| LPDDR5 | 4         | 4.65%   |
| DDR2   | 3         | 3.49%   |
| LPDDR3 | 1         | 1.16%   |
| DDR5   | 1         | 1.16%   |
| DDR    | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 88.37%  |
| Row Of Chips | 8         | 9.3%    |
| DIMM         | 1         | 1.16%   |
| Unknown      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 41.41%  |
| 4096  | 35        | 35.35%  |
| 16384 | 8         | 8.08%   |
| 2048  | 8         | 8.08%   |
| 1024  | 3         | 3.03%   |
| 512   | 3         | 3.03%   |
| 32768 | 1         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 27.17%  |
| 2667    | 19        | 20.65%  |
| 3200    | 16        | 17.39%  |
| 2400    | 5         | 5.43%   |
| 1334    | 5         | 5.43%   |
| 6400    | 4         | 4.35%   |
| 1333    | 4         | 4.35%   |
| 533     | 3         | 3.26%   |
| 3733    | 2         | 2.17%   |
| 2133    | 2         | 2.17%   |
| 667     | 2         | 2.17%   |
| 8400    | 1         | 1.09%   |
| 4800    | 1         | 1.09%   |
| 4266    | 1         | 1.09%   |
| 1867    | 1         | 1.09%   |
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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 31.73%  |
| IMC Networks                           | 17        | 16.35%  |
| Microdia                               | 9         | 8.65%   |
| Bison Electronics                      | 9         | 8.65%   |
| Realtek Semiconductor                  | 7         | 6.73%   |
| Quanta                                 | 7         | 6.73%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.81%   |
| Syntek                                 | 3         | 2.88%   |
| Suyin                                  | 3         | 2.88%   |
| Sunplus Innovation Technology          | 3         | 2.88%   |
| Acer                                   | 2         | 1.92%   |
| SunplusIT                              | 1         | 0.96%   |
| Silicon Motion                         | 1         | 0.96%   |
| Luxvisions Innotech Limited            | 1         | 0.96%   |
| Logitech                               | 1         | 0.96%   |
| Intel                                  | 1         | 0.96%   |
| Alcor Micro                            | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 10        | 9.52%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 6.67%   |
| Chicony HP Truevision HD camera               | 4         | 3.81%   |
| Syntek Integrated Camera                      | 3         | 2.86%   |
| Suyin HP Truevision HD                        | 3         | 2.86%   |
| Realtek USB Camera                            | 3         | 2.86%   |
| Quanta HD User Facing                         | 3         | 2.86%   |
| Microdia Integrated_Webcam_HD                 | 3         | 2.86%   |
| Chicony HD Webcam                             | 3         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.86%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.9%    |
| Microdia HP Integrated Webcam                 | 2         | 1.9%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.9%    |
| IMC Networks Integrated Camera                | 2         | 1.9%    |
| IMC Networks HD Camera                        | 2         | 1.9%    |
| Chicony USB2.0 Camera                         | 2         | 1.9%    |
| Chicony USB 2.0 Camera                        | 2         | 1.9%    |
| Chicony Lenovo EasyCamera                     | 2         | 1.9%    |
| Chicony HD WebCam (Acer)                      | 2         | 1.9%    |
| Chicony HD User Facing                        | 2         | 1.9%    |
| Bison SunplusIT Integrated Camera             | 2         | 1.9%    |
| Bison Lenovo EasyCamera                       | 2         | 1.9%    |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.95%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.95%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.95%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.95%   |
| Realtek Laptop Camera                         | 1         | 0.95%   |
| Realtek Integrated Webcam HD                  | 1         | 0.95%   |
| Realtek HD WebCam                             | 1         | 0.95%   |
| Quanta VGA WebCam                             | 1         | 0.95%   |
| Quanta HP Webcam                              | 1         | 0.95%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.95%   |
| Quanta ACER HD User Facing                    | 1         | 0.95%   |
| Microdia Webcam Vitade AF                     | 1         | 0.95%   |
| Microdia Webcam                               | 1         | 0.95%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 0.95%   |
| Microdia Integrated_Webcam_2M                 | 1         | 0.95%   |
| Luxvisions Innotech Limited EasyCamera 1M     | 1         | 0.95%   |
| Logitech C505 HD Webcam                       | 1         | 0.95%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 0.95%   |

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
| 0     | 82        | 70.09%  |
| 1     | 27        | 23.08%  |
| 2     | 7         | 5.98%   |
| 3     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 39.53%  |
| Graphics card            | 6         | 13.95%  |
| Chipcard                 | 6         | 13.95%  |
| Net/wireless             | 5         | 11.63%  |
| Multimedia controller    | 2         | 4.65%   |
| Communication controller | 2         | 4.65%   |
| Camera                   | 2         | 4.65%   |
| Sound                    | 1         | 2.33%   |
| Net/ethernet             | 1         | 2.33%   |
| Bluetooth                | 1         | 2.33%   |

