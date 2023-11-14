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

Total: 131

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 81        | 74.31%  |
| Void Linux         | 28        | 25.69%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 6.3.13_1    | 7         | 6.25%   |
| 5.13.19_1   | 5         | 4.46%   |
| 5.18.19_1   | 4         | 3.57%   |
| 6.1.4_1     | 3         | 2.68%   |
| 5.8.18_1    | 3         | 2.68%   |
| 5.8.12_1    | 3         | 2.68%   |
| 5.3.9_1     | 3         | 2.68%   |
| 5.19.17_1   | 3         | 2.68%   |
| 5.10.17_1   | 3         | 2.68%   |
| 6.3.12_1    | 2         | 1.79%   |
| 6.1.31_1    | 2         | 1.79%   |
| 6.1.21_1    | 2         | 1.79%   |
| 6.1.10_1    | 2         | 1.79%   |
| 5.4.24_1    | 2         | 1.79%   |
| 5.19.16_1   | 2         | 1.79%   |
| 5.18.14_1   | 2         | 1.79%   |
| 5.16.20_1   | 2         | 1.79%   |
| 5.15.32_1   | 2         | 1.79%   |
| 5.13.13_1   | 2         | 1.79%   |
| 5.12.10_1   | 2         | 1.79%   |
| 6.5.5_2     | 1         | 0.89%   |
| 6.5.10_1    | 1         | 0.89%   |
| 6.4.8_1     | 1         | 0.89%   |
| 6.2.8_1     | 1         | 0.89%   |
| 6.2.11_1    | 1         | 0.89%   |
| 6.1.3_1     | 1         | 0.89%   |
| 6.1.29_1    | 1         | 0.89%   |
| 6.1.18_1    | 1         | 0.89%   |
| 6.1.14_1    | 1         | 0.89%   |
| 6.1.13_1    | 1         | 0.89%   |
| 6.0.9_1     | 1         | 0.89%   |
| 6.0.15_1    | 1         | 0.89%   |
| 6.0.10_1    | 1         | 0.89%   |
| 5.9.16_1    | 1         | 0.89%   |
| 5.9.14_1    | 1         | 0.89%   |
| 5.9.0-rc8_2 | 1         | 0.89%   |
| 5.8.9_1     | 1         | 0.89%   |
| 5.8.8_1     | 1         | 0.89%   |
| 5.8.7_1     | 1         | 0.89%   |
| 5.8.6_1     | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.13  | 7         | 6.25%   |
| 5.13.19 | 5         | 4.46%   |
| 5.8.12  | 4         | 3.57%   |
| 5.18.19 | 4         | 3.57%   |
| 6.1.4   | 3         | 2.68%   |
| 5.8.18  | 3         | 2.68%   |
| 5.3.9   | 3         | 2.68%   |
| 5.19.17 | 3         | 2.68%   |
| 5.10.17 | 3         | 2.68%   |
| 6.3.12  | 2         | 1.79%   |
| 6.1.31  | 2         | 1.79%   |
| 6.1.21  | 2         | 1.79%   |
| 6.1.10  | 2         | 1.79%   |
| 5.4.24  | 2         | 1.79%   |
| 5.19.16 | 2         | 1.79%   |
| 5.18.14 | 2         | 1.79%   |
| 5.16.20 | 2         | 1.79%   |
| 5.15.32 | 2         | 1.79%   |
| 5.13.13 | 2         | 1.79%   |
| 5.12.10 | 2         | 1.79%   |
| 6.5.5   | 1         | 0.89%   |
| 6.5.10  | 1         | 0.89%   |
| 6.4.8   | 1         | 0.89%   |
| 6.2.8   | 1         | 0.89%   |
| 6.2.11  | 1         | 0.89%   |
| 6.1.3   | 1         | 0.89%   |
| 6.1.29  | 1         | 0.89%   |
| 6.1.18  | 1         | 0.89%   |
| 6.1.14  | 1         | 0.89%   |
| 6.1.13  | 1         | 0.89%   |
| 6.0.9   | 1         | 0.89%   |
| 6.0.15  | 1         | 0.89%   |
| 6.0.10  | 1         | 0.89%   |
| 5.9.16  | 1         | 0.89%   |
| 5.9.14  | 1         | 0.89%   |
| 5.9.0   | 1         | 0.89%   |
| 5.8.9   | 1         | 0.89%   |
| 5.8.8   | 1         | 0.89%   |
| 5.8.7   | 1         | 0.89%   |
| 5.8.6   | 1         | 0.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 14        | 12.61%  |
| 5.15    | 12        | 10.81%  |
| 5.8     | 11        | 9.91%   |
| 5.13    | 11        | 9.91%   |
| 6.3     | 9         | 8.11%   |
| 5.18    | 7         | 6.31%   |
| 5.12    | 7         | 6.31%   |
| 5.10    | 7         | 6.31%   |
| 5.4     | 5         | 4.5%    |
| 5.19    | 5         | 4.5%    |
| 6.0     | 3         | 2.7%    |
| 5.9     | 3         | 2.7%    |
| 5.3     | 3         | 2.7%    |
| 6.5     | 2         | 1.8%    |
| 6.2     | 2         | 1.8%    |
| 5.16    | 2         | 1.8%    |
| 6.4     | 1         | 0.9%    |
| 5.7     | 1         | 0.9%    |
| 5.2     | 1         | 0.9%    |
| 5.14    | 1         | 0.9%    |
| 5.11    | 1         | 0.9%    |
| 5.1     | 1         | 0.9%    |
| 4.4     | 1         | 0.9%    |
| 4.14    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 102       | 94.44%  |
| i686    | 4         | 3.7%    |
| aarch64 | 2         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 44        | 39.64%  |
| XFCE         | 15        | 13.51%  |
| MATE         | 9         | 8.11%   |
| KDE          | 9         | 8.11%   |
| KDE5         | 8         | 7.21%   |
| GNOME        | 6         | 5.41%   |
| i3           | 5         | 4.5%    |
| X-Cinnamon   | 2         | 1.8%    |
| sway         | 2         | 1.8%    |
| bspwm        | 2         | 1.8%    |
| awesome      | 2         | 1.8%    |
| river        | 1         | 0.9%    |
| openbox      | 1         | 0.9%    |
| LXQt         | 1         | 0.9%    |
| LXDE         | 1         | 0.9%    |
| Lumina       | 1         | 0.9%    |
| dwm          | 1         | 0.9%    |
| dot-xsession | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 76        | 69.72%  |
| Wayland | 14        | 12.84%  |
| Tty     | 12        | 11.01%  |
| Unknown | 7         | 6.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 74.31%  |
| LightDM | 12        | 11.01%  |
| SDDM    | 7         | 6.42%   |
| LXDM    | 6         | 5.5%    |
| SLiM    | 1         | 0.92%   |
| LDM     | 1         | 0.92%   |
| GDM     | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 59        | 53.64%  |
| Unknown | 11        | 10%     |
| en_GB   | 8         | 7.27%   |
| it_IT   | 4         | 3.64%   |
| es_ES   | 4         | 3.64%   |
| en_DK   | 4         | 3.64%   |
| de_DE   | 4         | 3.64%   |
| en_CA   | 2         | 1.82%   |
| tr_TR   | 1         | 0.91%   |
| ru_UA   | 1         | 0.91%   |
| ru_RU   | 1         | 0.91%   |
| pt_BR   | 1         | 0.91%   |
| nb_NO   | 1         | 0.91%   |
| fr_FR   | 1         | 0.91%   |
| es_HN   | 1         | 0.91%   |
| es_DO   | 1         | 0.91%   |
| es_AR   | 1         | 0.91%   |
| en_NZ   | 1         | 0.91%   |
| en_AU   | 1         | 0.91%   |
| el_GR   | 1         | 0.91%   |
| ca_ES   | 1         | 0.91%   |
| C       | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 66        | 60.55%  |
| BIOS | 43        | 39.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 68        | 62.39%  |
| Btrfs   | 27        | 24.77%  |
| Unknown | 5         | 4.59%   |
| Xfs     | 4         | 3.67%   |
| Zfs     | 3         | 2.75%   |
| F2fs    | 1         | 0.92%   |
| Ext3    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 68        | 61.82%  |
| Unknown | 28        | 25.45%  |
| MBR     | 14        | 12.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 89.81%  |
| Yes       | 11        | 10.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 78.7%   |
| Yes       | 23        | 21.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 25%     |
| Hewlett-Packard     | 17        | 15.74%  |
| ASUSTek Computer    | 15        | 13.89%  |
| Acer                | 15        | 13.89%  |
| Dell                | 11        | 10.19%  |
| MSI                 | 4         | 3.7%    |
| Unknown             | 3         | 2.78%   |
| Notebook            | 2         | 1.85%   |
| HUAWEI              | 2         | 1.85%   |
| Timi                | 1         | 0.93%   |
| Samsung Electronics | 1         | 0.93%   |
| Positivo            | 1         | 0.93%   |
| Pine Microsystems   | 1         | 0.93%   |
| Nokia               | 1         | 0.93%   |
| Google              | 1         | 0.93%   |
| Getac               | 1         | 0.93%   |
| Framework           | 1         | 0.93%   |
| Exo                 | 1         | 0.93%   |
| Digibras            | 1         | 0.93%   |
| Chuwi               | 1         | 0.93%   |
| Apple               | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.78%   |
| HP Pavilion Notebook                      | 2         | 1.85%   |
| HP Laptop 15-bw0xx                        | 2         | 1.85%   |
| HP 15                                     | 2         | 1.85%   |
| ASUS X751LD                               | 2         | 1.85%   |
| Acer Swift SF314-42                       | 2         | 1.85%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.93%   |
| Samsung 275E4E/275E5E                     | 1         | 0.93%   |
| Positivo Mobile                           | 1         | 0.93%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.93%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.93%   |
| Notebook NH50_70RA                        | 1         | 0.93%   |
| Nokia Booklet 3G                          | 1         | 0.93%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.93%   |
| MSI GV72 7RE                              | 1         | 0.93%   |
| MSI GF63 Thin 10SCXR                      | 1         | 0.93%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.93%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.93%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.93%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.93%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.93%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.93%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 0.93%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 2a 20XLS02500     | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 0.93%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 1         | 0.93%   |
| Lenovo ThinkPad E595 20NFCTO1WW           | 1         | 0.93%   |
| Lenovo Legion Y540-15IRH-PG0 81SY         | 1         | 0.93%   |
| Lenovo IdeaPad Z570 10246ZG               | 1         | 0.93%   |
| Lenovo IdeaPad S145-15IWL 81MV            | 1         | 0.93%   |
| Lenovo IdeaPad S145-14IIL 81W6            | 1         | 0.93%   |
| Lenovo IdeaPad 710S-13IKB 80VQ            | 1         | 0.93%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 16        | 14.81%  |
| Acer Aspire              | 9         | 8.33%   |
| Lenovo IdeaPad           | 7         | 6.48%   |
| ASUS VivoBook            | 7         | 6.48%   |
| HP Laptop                | 5         | 4.63%   |
| HP Pavilion              | 4         | 3.7%    |
| Dell Latitude            | 4         | 3.7%    |
| Dell Inspiron            | 4         | 3.7%    |
| Unknown                  | 3         | 2.78%   |
| HP ENVY                  | 2         | 1.85%   |
| HP 255                   | 2         | 1.85%   |
| HP 15                    | 2         | 1.85%   |
| ASUS X751LD              | 2         | 1.85%   |
| Acer Swift               | 2         | 1.85%   |
| Timi Redmi               | 1         | 0.93%   |
| Samsung 275E4E           | 1         | 0.93%   |
| Positivo Mobile          | 1         | 0.93%   |
| Pine Microsystems Pine64 | 1         | 0.93%   |
| Notebook NV4XMB          | 1         | 0.93%   |
| Notebook NH50            | 1         | 0.93%   |
| Nokia Booklet            | 1         | 0.93%   |
| MSI Summit               | 1         | 0.93%   |
| MSI GV72                 | 1         | 0.93%   |
| MSI GF63                 | 1         | 0.93%   |
| MSI Bravo                | 1         | 0.93%   |
| Lenovo Y520-15IKB        | 1         | 0.93%   |
| Lenovo Legion            | 1         | 0.93%   |
| Lenovo G50-70            | 1         | 0.93%   |
| Lenovo G50-45            | 1         | 0.93%   |
| HUAWEI KLVL-WXXW         | 1         | 0.93%   |
| HUAWEI HN-WX9X           | 1         | 0.93%   |
| HP Stream                | 1         | 0.93%   |
| HP Notebook              | 1         | 0.93%   |
| Google Phaser360         | 1         | 0.93%   |
| Getac V110               | 1         | 0.93%   |
| Framework Laptop         | 1         | 0.93%   |
| Exo Exomate              | 1         | 0.93%   |
| Digibras NH4CU03         | 1         | 0.93%   |
| Dell XPS                 | 1         | 0.93%   |
| Dell Precision           | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 18        | 16.67%  |
| 2020    | 14        | 12.96%  |
| 2013    | 9         | 8.33%   |
| 2022    | 8         | 7.41%   |
| 2018    | 8         | 7.41%   |
| 2015    | 8         | 7.41%   |
| 2014    | 8         | 7.41%   |
| 2016    | 7         | 6.48%   |
| 2021    | 5         | 4.63%   |
| 2017    | 5         | 4.63%   |
| 2011    | 4         | 3.7%    |
| 2012    | 3         | 2.78%   |
| 2010    | 2         | 1.85%   |
| 2009    | 2         | 1.85%   |
| 2008    | 2         | 1.85%   |
| Unknown | 2         | 1.85%   |
| 2007    | 1         | 0.93%   |
| 2006    | 1         | 0.93%   |
| 2005    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 25.69%  |
| 3.01-4.0    | 25        | 22.94%  |
| 8.01-16.0   | 19        | 17.43%  |
| 16.01-24.0  | 17        | 15.6%   |
| 1.01-2.0    | 7         | 6.42%   |
| 32.01-64.0  | 6         | 5.5%    |
| 24.01-32.0  | 3         | 2.75%   |
| 0.51-1.0    | 2         | 1.83%   |
| 64.01-256.0 | 1         | 0.92%   |
| 0.01-0.5    | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 43        | 38.39%  |
| 2.01-3.0   | 23        | 20.54%  |
| 0.51-1.0   | 16        | 14.29%  |
| 4.01-8.0   | 13        | 11.61%  |
| 3.01-4.0   | 9         | 8.04%   |
| 0.01-0.5   | 5         | 4.46%   |
| 8.01-16.0  | 2         | 1.79%   |
| 16.01-24.0 | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 78.7%   |
| 2      | 20        | 18.52%  |
| 3      | 2         | 1.85%   |
| 0      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 75%     |
| Yes       | 27        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 72.22%  |
| No        | 30        | 27.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 96.3%   |
| No        | 4         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 82.41%  |
| No        | 19        | 17.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 18        | 16.67%  |
| Germany            | 11        | 10.19%  |
| Russia             | 10        | 9.26%   |
| India              | 9         | 8.33%   |
| Ukraine            | 4         | 3.7%    |
| Switzerland        | 4         | 3.7%    |
| Denmark            | 4         | 3.7%    |
| Brazil             | 4         | 3.7%    |
| Italy              | 3         | 2.78%   |
| UK                 | 2         | 1.85%   |
| Turkey             | 2         | 1.85%   |
| Spain              | 2         | 1.85%   |
| Netherlands        | 2         | 1.85%   |
| Morocco            | 2         | 1.85%   |
| Greece             | 2         | 1.85%   |
| France             | 2         | 1.85%   |
| Canada             | 2         | 1.85%   |
| Bulgaria           | 2         | 1.85%   |
| Australia          | 2         | 1.85%   |
| Argentina          | 2         | 1.85%   |
| Vietnam            | 1         | 0.93%   |
| Uruguay            | 1         | 0.93%   |
| Thailand           | 1         | 0.93%   |
| Serbia             | 1         | 0.93%   |
| Portugal           | 1         | 0.93%   |
| Peru               | 1         | 0.93%   |
| Norway             | 1         | 0.93%   |
| New Zealand        | 1         | 0.93%   |
| Mexico             | 1         | 0.93%   |
| Latvia             | 1         | 0.93%   |
| Indonesia          | 1         | 0.93%   |
| Honduras           | 1         | 0.93%   |
| Guatemala          | 1         | 0.93%   |
| Grenada            | 1         | 0.93%   |
| Ecuador            | 1         | 0.93%   |
| Dominican Republic | 1         | 0.93%   |
| Czechia            | 1         | 0.93%   |
| Colombia           | 1         | 0.93%   |
| Austria            | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 5         | 4.59%   |
| St Petersburg          | 3         | 2.75%   |
| Spring Hill            | 2         | 1.83%   |
| Rome                   | 2         | 1.83%   |
| Meknes                 | 2         | 1.83%   |
| Hyderabad              | 2         | 1.83%   |
| Geneva                 | 2         | 1.83%   |
| Yambol                 | 1         | 0.92%   |
| Wilen bei Wollerau     | 1         | 0.92%   |
| Weatherford            | 1         | 0.92%   |
| Volgograd              | 1         | 0.92%   |
| Vlaardingen            | 1         | 0.92%   |
| Vienna                 | 1         | 0.92%   |
| Viby J                 | 1         | 0.92%   |
| Trujillo               | 1         | 0.92%   |
| Toulouse               | 1         | 0.92%   |
| Touget                 | 1         | 0.92%   |
| Toms River             | 1         | 0.92%   |
| Tegucigalpa            | 1         | 0.92%   |
| Syktyvkar              | 1         | 0.92%   |
| Sydney                 | 1         | 0.92%   |
| Surabaya               | 1         | 0.92%   |
| Sun Prairie            | 1         | 0.92%   |
| Stratford              | 1         | 0.92%   |
| Solone                 | 1         | 0.92%   |
| Sohren                 | 1         | 0.92%   |
| Sofia                  | 1         | 0.92%   |
| Sistranda              | 1         | 0.92%   |
| Saxtons River          | 1         | 0.92%   |
| Sao Paulo              | 1         | 0.92%   |
| Santo Domingo          | 1         | 0.92%   |
| San Miguel de Tucumán | 1         | 0.92%   |
| Saint George's         | 1         | 0.92%   |
| Rostock                | 1         | 0.92%   |
| Rosenheim              | 1         | 0.92%   |
| River Grove            | 1         | 0.92%   |
| Riga                   | 1         | 0.92%   |
| Reutlingen             | 1         | 0.92%   |
| Regensburg             | 1         | 0.92%   |
| Ragusa                 | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 22        | 23     | 17.46%  |
| Seagate                     | 18        | 19     | 14.29%  |
| WDC                         | 13        | 14     | 10.32%  |
| Unknown                     | 10        | 16     | 7.94%   |
| SanDisk                     | 8         | 9      | 6.35%   |
| SK hynix                    | 7         | 7      | 5.56%   |
| HGST                        | 7         | 8      | 5.56%   |
| Intel                       | 6         | 7      | 4.76%   |
| Toshiba                     | 5         | 5      | 3.97%   |
| Kingston                    | 5         | 5      | 3.97%   |
| Crucial                     | 5         | 5      | 3.97%   |
| Phison                      | 2         | 2      | 1.59%   |
| Micron Technology           | 2         | 2      | 1.59%   |
| Hitachi                     | 2         | 2      | 1.59%   |
| Transcend                   | 1         | 1      | 0.79%   |
| PNY                         | 1         | 1      | 0.79%   |
| Phison Electronics          | 1         | 1      | 0.79%   |
| Patriot                     | 1         | 1      | 0.79%   |
| ORIGIN                      | 1         | 1      | 0.79%   |
| Micron/Crucial Technology   | 1         | 1      | 0.79%   |
| Lenovo                      | 1         | 1      | 0.79%   |
| KIOXIA                      | 1         | 1      | 0.79%   |
| Kingston Technology Company | 1         | 1      | 0.79%   |
| INNOVATION IT               | 1         | 1      | 0.79%   |
| IBM/Hitachi                 | 1         | 1      | 0.79%   |
| China                       | 1         | 1      | 0.79%   |
| BHT                         | 1         | 1      | 0.79%   |
| Apple                       | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 4         | 3.05%   |
| Unknown MMC Card  32GB                            | 3         | 2.29%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 2.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 3         | 2.29%   |
| HGST HTS545050A7E680 500GB                        | 3         | 2.29%   |
| Crucial CT500MX500SSD1 500GB                      | 3         | 2.29%   |
| Unknown MMC Card  128GB                           | 2         | 1.53%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1024GB        | 2         | 1.53%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 2         | 1.53%   |
| Samsung SSD 870 EVO 500GB                         | 2         | 1.53%   |
| Intel SSDPEKNW512G8 512GB                         | 2         | 1.53%   |
| HGST HTS541010B7E610 1TB                          | 2         | 1.53%   |
| HGST HTS541010A9E680 1TB                          | 2         | 1.53%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 0.76%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.76%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 0.76%   |
| WDC WD2500BEVT-22A23T0 250GB                      | 1         | 0.76%   |
| WDC WD1600BEVS-60VAT0 160GB                       | 1         | 0.76%   |
| WDC WD10SPZX-24Z10 1TB                            | 1         | 0.76%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 0.76%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.76%   |
| WDC WD Elements 320GB                             | 1         | 0.76%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB                | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB              | 1         | 0.76%   |
| Unknown USB DISK 3.2 1TB                          | 1         | 0.76%   |
| Unknown SD512  512MB                              | 1         | 0.76%   |
| Unknown SD16G  16GB                               | 1         | 0.76%   |
| Unknown SD/MMC/MS PRO 16GB                        | 1         | 0.76%   |
| Unknown MMC Card  8GB                             | 1         | 0.76%   |
| Unknown MMC Card  64GB                            | 1         | 0.76%   |
| Unknown MMC Card  2GB                             | 1         | 0.76%   |
| Unknown MMC Card                                  | 1         | 0.76%   |
| Unknown CWBC3R  64GB                              | 1         | 0.76%   |
| Transcend TS128GMTS800 128GB SSD                  | 1         | 0.76%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 0.76%   |
| Toshiba KXG50ZNV512G NVMe 512GB                   | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 40.91%  |
| WDC                 | 10        | 10     | 22.73%  |
| HGST                | 7         | 8      | 15.91%  |
| Toshiba             | 4         | 4      | 9.09%   |
| Hitachi             | 2         | 2      | 4.55%   |
| Unknown             | 1         | 1      | 2.27%   |
| Samsung Electronics | 1         | 1      | 2.27%   |
| IBM/Hitachi         | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 25%     |
| Crucial             | 5         | 5      | 15.63%  |
| SanDisk             | 4         | 4      | 12.5%   |
| Kingston            | 4         | 4      | 12.5%   |
| Transcend           | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Patriot             | 1         | 1      | 3.13%   |
| ORIGIN              | 1         | 1      | 3.13%   |
| Lenovo              | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| INNOVATION IT       | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| BHT                 | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 43        | 46     | 34.96%  |
| NVMe    | 39        | 44     | 31.71%  |
| SSD     | 30        | 32     | 24.39%  |
| MMC     | 9         | 13     | 7.32%   |
| Unknown | 2         | 3      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 75     | 55.83%  |
| NVMe | 39        | 44     | 32.5%   |
| MMC  | 9         | 13     | 7.5%    |
| SAS  | 5         | 6      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 48     | 58.9%   |
| 0.51-1.0   | 29        | 29     | 39.73%  |
| 2.01-3.0   | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 33        | 30%     |
| 501-1000       | 27        | 24.55%  |
| 101-250        | 21        | 19.09%  |
| Unknown        | 7         | 6.36%   |
| 1-20           | 6         | 5.45%   |
| 21-50          | 5         | 4.55%   |
| 51-100         | 5         | 4.55%   |
| 1001-2000      | 4         | 3.64%   |
| More than 3000 | 1         | 0.91%   |
| 2001-3000      | 1         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 28.18%  |
| 101-250        | 26        | 23.64%  |
| 21-50          | 19        | 17.27%  |
| 51-100         | 13        | 11.82%  |
| 251-500        | 9         | 8.18%   |
| Unknown        | 7         | 6.36%   |
| 1001-2000      | 3         | 2.73%   |
| More than 3000 | 1         | 0.91%   |
| 501-1000       | 1         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB              | 2         | 2      | 12.5%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 6.25%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 6.25%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 6.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 6.25%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 6.25%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 6.25%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| HGST                | 3         | 3      | 18.75%  |
| Hitachi             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| IBM/Hitachi         | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 6      | 42.86%  |
| HGST        | 3         | 3      | 21.43%  |
| Hitachi     | 2         | 2      | 14.29%  |
| WDC         | 1         | 1      | 7.14%   |
| Toshiba     | 1         | 1      | 7.14%   |
| IBM/Hitachi | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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
| Works    | 61        | 72     | 52.59%  |
| Detected | 39        | 50     | 33.62%  |
| Malfunc  | 16        | 16     | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 52.03%  |
| AMD                              | 22        | 17.89%  |
| Samsung Electronics              | 14        | 11.38%  |
| SK hynix                         | 6         | 4.88%   |
| SanDisk                          | 6         | 4.88%   |
| Phison Electronics               | 3         | 2.44%   |
| Micron Technology                | 2         | 1.63%   |
| Kingston Technology Company      | 2         | 1.63%   |
| Toshiba America Info Systems     | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Micron/Crucial Technology        | 1         | 0.81%   |
| KIOXIA                           | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 20        | 15.75%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 8.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 7.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 3.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 4         | 3.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 3.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 3         | 2.36%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 3         | 2.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 3         | 2.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.36%   |
| Intel SSD 660P Series                                                        | 3         | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.36%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 2         | 1.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 2         | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.57%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.57%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 2         | 1.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.57%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 0.79%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.79%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 0.79%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 0.79%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.79%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.79%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.79%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 0.79%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                               | 1         | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.79%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 73        | 58.87%  |
| NVMe | 39        | 31.45%  |
| RAID | 6         | 4.84%   |
| IDE  | 6         | 4.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 68.52%  |
| AMD    | 32        | 29.63%  |
| ARM    | 2         | 1.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 2.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.85%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.85%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 1.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.85%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.85%   |
| ARM Processor                                 | 2         | 1.85%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.85%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.85%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.85%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.93%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.93%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 0.93%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.93%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.93%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 19.44%  |
| Intel Core i7           | 17        | 15.74%  |
| Intel Core i3           | 13        | 12.04%  |
| Other                   | 11        | 10.19%  |
| AMD Ryzen 5             | 9         | 8.33%   |
| Intel Celeron           | 7         | 6.48%   |
| AMD Ryzen 7             | 7         | 6.48%   |
| Intel Atom              | 5         | 4.63%   |
| AMD Ryzen 7 PRO         | 3         | 2.78%   |
| Intel Pentium           | 2         | 1.85%   |
| AMD A8                  | 2         | 1.85%   |
| Intel Pentium M         | 1         | 0.93%   |
| Intel Genuine           | 1         | 0.93%   |
| Intel Core 2 Duo        | 1         | 0.93%   |
| AMD Turion 64 X2 Mobile | 1         | 0.93%   |
| AMD Ryzen 5 PRO         | 1         | 0.93%   |
| AMD Ryzen 3             | 1         | 0.93%   |
| AMD E2                  | 1         | 0.93%   |
| AMD E1                  | 1         | 0.93%   |
| AMD C-60                | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A4                  | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 40.74%  |
| 4      | 35        | 32.41%  |
| 6      | 13        | 12.04%  |
| 8      | 7         | 6.48%   |
| 1      | 6         | 5.56%   |
| 14     | 2         | 1.85%   |
| 10     | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 99.07%  |
| 2      | 1         | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 72.22%  |
| 1      | 30        | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 91.67%  |
| Unknown        | 4         | 3.7%    |
| 32-bit         | 3         | 2.78%   |
| 64-bit         | 2         | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 33.64%  |
| 0x40651    | 8         | 7.27%   |
| 0x406e3    | 4         | 3.64%   |
| 0x306a9    | 4         | 3.64%   |
| 0x08108102 | 4         | 3.64%   |
| 0x906ea    | 3         | 2.73%   |
| 0x806ec    | 3         | 2.73%   |
| 0x806e9    | 3         | 2.73%   |
| 0x30678    | 3         | 2.73%   |
| 0x206a7    | 3         | 2.73%   |
| 0x08600104 | 3         | 2.73%   |
| 0x906e9    | 2         | 1.82%   |
| 0x906a3    | 2         | 1.82%   |
| 0x106c2    | 2         | 1.82%   |
| 0x0a50000c | 2         | 1.82%   |
| 0x07030105 | 2         | 1.82%   |
| 0x06006705 | 2         | 1.82%   |
| 0x05000119 | 2         | 1.82%   |
| 0xa0652    | 1         | 0.91%   |
| 0x806eb    | 1         | 0.91%   |
| 0x806ea    | 1         | 0.91%   |
| 0x806c1    | 1         | 0.91%   |
| 0x706e5    | 1         | 0.91%   |
| 0x406c4    | 1         | 0.91%   |
| 0x306d4    | 1         | 0.91%   |
| 0x30673    | 1         | 0.91%   |
| 0x20652    | 1         | 0.91%   |
| 0x106ca    | 1         | 0.91%   |
| 0x10661    | 1         | 0.91%   |
| 0x0a404102 | 1         | 0.91%   |
| 0x0a404101 | 1         | 0.91%   |
| 0x08608103 | 1         | 0.91%   |
| 0x08608102 | 1         | 0.91%   |
| 0x08600106 | 1         | 0.91%   |
| 0x08600102 | 1         | 0.91%   |
| 0x08108109 | 1         | 0.91%   |
| 0x0810100b | 1         | 0.91%   |
| 0x08101007 | 1         | 0.91%   |
| 0x07030104 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 19.44%  |
| Haswell          | 10        | 9.26%   |
| Zen 2            | 6         | 5.56%   |
| Skylake          | 6         | 5.56%   |
| Unknown          | 6         | 5.56%   |
| Zen+             | 5         | 4.63%   |
| Silvermont       | 5         | 4.63%   |
| Zen 3            | 4         | 3.7%    |
| SandyBridge      | 4         | 3.7%    |
| IvyBridge        | 4         | 3.7%    |
| Excavator        | 4         | 3.7%    |
| TigerLake        | 3         | 2.78%   |
| Puma             | 3         | 2.78%   |
| Broadwell        | 3         | 2.78%   |
| Bonnell          | 3         | 2.78%   |
| Alderlake Hybrid | 3         | 2.78%   |
| Zen              | 2         | 1.85%   |
| IceLake          | 2         | 1.85%   |
| Goldmont plus    | 2         | 1.85%   |
| Core             | 2         | 1.85%   |
| CometLake        | 2         | 1.85%   |
| Bobcat           | 2         | 1.85%   |
| Westmere         | 1         | 0.93%   |
| Penryn           | 1         | 0.93%   |
| P6               | 1         | 0.93%   |
| K8 Hammer        | 1         | 0.93%   |
| Jaguar           | 1         | 0.93%   |
| Goldmont         | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 72        | 53.33%  |
| AMD                              | 33        | 24.44%  |
| Nvidia                           | 29        | 21.48%  |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 7.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 4.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 4.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 3.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 3.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 2.88%   |
| Intel UHD Graphics 620                                                    | 3         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.16%   |
| Intel HD Graphics 620                                                     | 3         | 2.16%   |
| Intel HD Graphics 5500                                                    | 3         | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.16%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.44%   |
| Intel HD Graphics 630                                                     | 2         | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.44%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 1.44%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.44%   |
| AMD Lucienne                                                              | 2         | 1.44%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.72%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 40.74%  |
| 1 x AMD        | 27        | 25%     |
| Intel + Nvidia | 25        | 23.15%  |
| Other          | 3         | 2.78%   |
| AMD + Nvidia   | 3         | 2.78%   |
| 2 x AMD        | 2         | 1.85%   |
| 2 x Intel      | 1         | 0.93%   |
| 1 x SiS        | 1         | 0.93%   |
| 1 x Nvidia     | 1         | 0.93%   |
| Intel + AMD    | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 84        | 77.78%  |
| Proprietary | 21        | 19.44%  |
| Unknown     | 3         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 67.57%  |
| 0.01-0.5   | 13        | 11.71%  |
| 1.01-2.0   | 9         | 8.11%   |
| 0.51-1.0   | 7         | 6.31%   |
| 3.01-4.0   | 6         | 5.41%   |
| 5.01-6.0   | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 26        | 23.21%  |
| AU Optronics         | 24        | 21.43%  |
| BOE                  | 17        | 15.18%  |
| LG Display           | 15        | 13.39%  |
| Samsung Electronics  | 5         | 4.46%   |
| PANDA                | 3         | 2.68%   |
| Sharp                | 2         | 1.79%   |
| LG Philips           | 2         | 1.79%   |
| Lenovo               | 2         | 1.79%   |
| Hewlett-Packard      | 2         | 1.79%   |
| Apple                | 2         | 1.79%   |
| AOC                  | 2         | 1.79%   |
| TMX                  | 1         | 0.89%   |
| STD                  | 1         | 0.89%   |
| Quanta Display       | 1         | 0.89%   |
| Philips              | 1         | 0.89%   |
| Panasonic            | 1         | 0.89%   |
| InnoLux Display      | 1         | 0.89%   |
| Iiyama               | 1         | 0.89%   |
| Goldstar             | 1         | 0.89%   |
| CHR                  | 1         | 0.89%   |
| BOE Technology Group | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.68%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.68%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.79%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.79%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 1.79%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.89%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.89%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.89%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.89%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.89%   |
| Quanta Display LCD Monitor QDS0015 1024x768 285x214mm 14.0-inch       | 1         | 0.89%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.89%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.89%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.89%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.89%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.89%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.89%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch               | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 39.09%  |
| 1366x768 (WXGA)   | 34        | 30.91%  |
| 1920x1200 (WUXGA) | 6         | 5.45%   |
| 1600x900 (HD+)    | 5         | 4.55%   |
| 2160x1440         | 3         | 2.73%   |
| 1280x800 (WXGA)   | 3         | 2.73%   |
| 3840x2160 (4K)    | 2         | 1.82%   |
| 2560x1600         | 2         | 1.82%   |
| 2560x1440 (QHD)   | 2         | 1.82%   |
| 1024x600          | 2         | 1.82%   |
| 3440x1440         | 1         | 0.91%   |
| 3200x2000         | 1         | 0.91%   |
| 2880x1800         | 1         | 0.91%   |
| 2288x1287         | 1         | 0.91%   |
| 2256x1504         | 1         | 0.91%   |
| 1360x768          | 1         | 0.91%   |
| 1280x720 (HD)     | 1         | 0.91%   |
| 1024x768 (XGA)    | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 47        | 41.96%  |
| 14      | 20        | 17.86%  |
| 13      | 13        | 11.61%  |
| 17      | 5         | 4.46%   |
| 11      | 5         | 4.46%   |
| 12      | 4         | 3.57%   |
| 23      | 3         | 2.68%   |
| 24      | 2         | 1.79%   |
| 16      | 2         | 1.79%   |
| 10      | 2         | 1.79%   |
| Unknown | 2         | 1.79%   |
| 84      | 1         | 0.89%   |
| 39      | 1         | 0.89%   |
| 34      | 1         | 0.89%   |
| 33      | 1         | 0.89%   |
| 21      | 1         | 0.89%   |
| 18      | 1         | 0.89%   |
| 8       | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 64.29%  |
| 201-300     | 21        | 18.75%  |
| 501-600     | 5         | 4.46%   |
| 351-400     | 5         | 4.46%   |
| 701-800     | 2         | 1.79%   |
| 401-500     | 2         | 1.79%   |
| Unknown     | 2         | 1.79%   |
| 801-900     | 1         | 0.89%   |
| 1501-2000   | 1         | 0.89%   |
| 101-200     | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 83        | 79.05%  |
| 16/10   | 14        | 13.33%  |
| 3/2     | 5         | 4.76%   |
| 4/3     | 1         | 0.95%   |
| 21/9    | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 41.07%  |
| 81-90          | 25        | 22.32%  |
| 71-80          | 6         | 5.36%   |
| 51-60          | 5         | 4.46%   |
| 61-70          | 4         | 3.57%   |
| 201-250        | 4         | 3.57%   |
| 121-130        | 3         | 2.68%   |
| 111-120        | 3         | 2.68%   |
| 351-500        | 2         | 1.79%   |
| 41-50          | 2         | 1.79%   |
| 251-300        | 2         | 1.79%   |
| 131-140        | 2         | 1.79%   |
| 91-100         | 2         | 1.79%   |
| Unknown        | 2         | 1.79%   |
| More than 1000 | 1         | 0.89%   |
| 1-40           | 1         | 0.89%   |
| 141-150        | 1         | 0.89%   |
| 501-1000       | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 49        | 44.14%  |
| 101-120       | 30        | 27.03%  |
| 51-100        | 15        | 13.51%  |
| 161-240       | 13        | 11.71%  |
| More than 240 | 2         | 1.8%    |
| Unknown       | 2         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 93        | 86.11%  |
| 2     | 13        | 12.04%  |
| 0     | 2         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 59        | 37.82%  |
| Intel                            | 45        | 28.85%  |
| Qualcomm Atheros                 | 19        | 12.18%  |
| Broadcom                         | 11        | 7.05%   |
| Broadcom Limited                 | 4         | 2.56%   |
| Sierra Wireless                  | 3         | 1.92%   |
| Ralink Technology                | 3         | 1.92%   |
| MediaTek                         | 3         | 1.92%   |
| Cypress Semiconductor            | 2         | 1.28%   |
| Xiaomi                           | 1         | 0.64%   |
| TP-Link                          | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| Ralink                           | 1         | 0.64%   |
| Qualcomm                         | 1         | 0.64%   |
| Marvell Technology Group         | 1         | 0.64%   |
| Huawei Technologies              | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 18.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.84%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 4.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 3.68%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.11%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.05%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.05%   |
| Intel Wireless 8260                                               | 2         | 1.05%   |
| Intel Wireless 7260                                               | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.05%   |
| Cypress K38231_03                                                 | 2         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.05%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.53%   |
| Sierra Wireless EM7455                                            | 1         | 0.53%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.53%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 40.91%  |
| Realtek Semiconductor | 25        | 22.73%  |
| Qualcomm Atheros      | 17        | 15.45%  |
| Broadcom              | 9         | 8.18%   |
| Sierra Wireless       | 3         | 2.73%   |
| Ralink Technology     | 3         | 2.73%   |
| MediaTek              | 3         | 2.73%   |
| Broadcom Limited      | 3         | 2.73%   |
| Ralink                | 1         | 0.91%   |
| Qualcomm              | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 8.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 6.36%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.64%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 2.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.82%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.82%   |
| Intel Wireless 8260                                            | 2         | 1.82%   |
| Intel Wireless 7260                                            | 2         | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.82%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.82%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.82%   |
| Sierra Wireless EM7455                                         | 1         | 0.91%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.91%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.91%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.91%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.91%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.91%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.91%   |
| Intel Wireless-AC 9260                                         | 1         | 0.91%   |
| Intel Wireless 7265                                            | 1         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 51        | 64.56%  |
| Intel                            | 14        | 17.72%  |
| Qualcomm Atheros                 | 3         | 3.8%    |
| Broadcom                         | 3         | 3.8%    |
| Cypress Semiconductor            | 2         | 2.53%   |
| Xiaomi                           | 1         | 1.27%   |
| TP-Link                          | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.27%   |
| Marvell Technology Group         | 1         | 1.27%   |
| Huawei Technologies              | 1         | 1.27%   |
| Broadcom Limited                 | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 45.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 16.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.8%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.53%   |
| Cypress K38231_03                                                 | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.27%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.27%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.27%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.27%   |
| Huawei ALP-AL00                                                   | 1         | 1.27%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.27%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 1.27%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 56.83%  |
| Ethernet | 78        | 42.62%  |
| Modem    | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 84.4%   |
| Ethernet | 17        | 15.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 62.96%  |
| 1     | 33        | 30.56%  |
| 0     | 5         | 4.63%   |
| 3     | 2         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 85.45%  |
| Yes  | 16        | 14.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 41.76%  |
| Realtek Semiconductor           | 16        | 17.58%  |
| Lite-On Technology              | 7         | 7.69%   |
| Broadcom                        | 7         | 7.69%   |
| IMC Networks                    | 5         | 5.49%   |
| Qualcomm Atheros Communications | 4         | 4.4%    |
| Foxconn / Hon Hai               | 4         | 4.4%    |
| Realtek                         | 2         | 2.2%    |
| Cambridge Silicon Radio         | 2         | 2.2%    |
| USI                             | 1         | 1.1%    |
| SIN                             | 1         | 1.1%    |
| Opticis                         | 1         | 1.1%    |
| Foxconn International           | 1         | 1.1%    |
| Dell                            | 1         | 1.1%    |
| Apple                           | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 13.19%  |
| Realtek Bluetooth Radio                             | 9         | 9.89%   |
| Intel AX200 Bluetooth                               | 9         | 9.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.49%   |
| Intel AX201 Bluetooth                               | 5         | 5.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 3.3%    |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 3.3%    |
| Realtek Bluetooth Radio                             | 2         | 2.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.2%    |
| Intel Bluetooth Device                              | 2         | 2.2%    |
| Intel AX210 Bluetooth                               | 2         | 2.2%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.2%    |
| IMC Networks Bluetooth Device                       | 2         | 2.2%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.2%    |
| USI Bluetooth Device                                | 1         | 1.1%    |
| SIN Bluetooth Keyboard                              | 1         | 1.1%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.1%    |
| Realtek RTL8723B Bluetooth                          | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.1%    |
| Opticis Bluetooth Radio                             | 1         | 1.1%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.1%    |
| IMC Networks Wireless_Device                        | 1         | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.1%    |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.1%    |
| Dell Wireless 365 Bluetooth                         | 1         | 1.1%    |
| Broadcom HP Portable Valentine                      | 1         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.1%    |
| Apple Bluetooth Host Controller                     | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 72        | 60%     |
| AMD                              | 32        | 26.67%  |
| Nvidia                           | 10        | 8.33%   |
| Texas Instruments                | 2         | 1.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Logitech                         | 1         | 0.83%   |
| JMTek                            | 1         | 0.83%   |
| Creative Technology              | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 12.35%  |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 7.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 6.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 6.17%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 6.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 4.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.09%   |
| AMD FCH Azalia Controller                                                  | 5         | 3.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.47%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.47%   |
| AMD High Definition Audio Controller                                       | 4         | 2.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.85%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.85%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.23%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.23%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.62%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.62%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.62%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 29        | 30.21%  |
| Samsung Electronics | 28        | 29.17%  |
| Micron Technology   | 13        | 13.54%  |
| Kingston            | 6         | 6.25%   |
| Unknown             | 5         | 5.21%   |
| A-DATA Technology   | 4         | 4.17%   |
| Ramaxel Technology  | 2         | 2.08%   |
| Corsair             | 2         | 2.08%   |
| Unknown (ABCD)      | 1         | 1.04%   |
| Transcend           | 1         | 1.04%   |
| Team                | 1         | 1.04%   |
| Elpida              | 1         | 1.04%   |
| Crucial             | 1         | 1.04%   |
| 4ea5                | 1         | 1.04%   |
| 48spaces            | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.96%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.96%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.98%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.98%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.98%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.98%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.98%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.98%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.98%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.98%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 43.75%  |
| DDR3   | 32        | 40%     |
| LPDDR4 | 5         | 6.25%   |
| LPDDR5 | 3         | 3.75%   |
| DDR2   | 3         | 3.75%   |
| LPDDR3 | 1         | 1.25%   |
| DDR    | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 89.87%  |
| Row Of Chips | 6         | 7.59%   |
| DIMM         | 1         | 1.27%   |
| Unknown      | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 37        | 39.78%  |
| 4096  | 34        | 36.56%  |
| 2048  | 8         | 8.6%    |
| 16384 | 7         | 7.53%   |
| 1024  | 3         | 3.23%   |
| 512   | 3         | 3.23%   |
| 32768 | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 27.91%  |
| 2667    | 18        | 20.93%  |
| 3200    | 15        | 17.44%  |
| 2400    | 5         | 5.81%   |
| 1334    | 5         | 5.81%   |
| 1333    | 4         | 4.65%   |
| 6400    | 3         | 3.49%   |
| 533     | 3         | 3.49%   |
| 3733    | 2         | 2.33%   |
| 2133    | 2         | 2.33%   |
| 667     | 2         | 2.33%   |
| 4266    | 1         | 1.16%   |
| 1867    | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

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
| Chicony Electronics                    | 30        | 31.25%  |
| IMC Networks                           | 16        | 16.67%  |
| Microdia                               | 9         | 9.38%   |
| Realtek Semiconductor                  | 7         | 7.29%   |
| Quanta                                 | 7         | 7.29%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.21%   |
| Bison Electronics                      | 5         | 5.21%   |
| Suyin                                  | 3         | 3.13%   |
| Sunplus Innovation Technology          | 3         | 3.13%   |
| Acer                                   | 3         | 3.13%   |
| Syntek                                 | 2         | 2.08%   |
| SunplusIT                              | 1         | 1.04%   |
| Silicon Motion                         | 1         | 1.04%   |
| Luxvisions Innotech Limited            | 1         | 1.04%   |
| Logitech                               | 1         | 1.04%   |
| Intel                                  | 1         | 1.04%   |
| Alcor Micro                            | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 10        | 10.31%  |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 7.22%   |
| Suyin HP Truevision HD                        | 3         | 3.09%   |
| Realtek USB Camera                            | 3         | 3.09%   |
| Quanta HD User Facing                         | 3         | 3.09%   |
| Microdia Integrated_Webcam_HD                 | 3         | 3.09%   |
| Chicony HP TrueVision HD Camera               | 3         | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 3.09%   |
| Syntek Integrated Camera                      | 2         | 2.06%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.06%   |
| Microdia HP Webcam-101                        | 2         | 2.06%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.06%   |
| IMC Networks Integrated Camera                | 2         | 2.06%   |
| IMC Networks HD Camera                        | 2         | 2.06%   |
| Chicony USB2.0 Camera                         | 2         | 2.06%   |
| Chicony USB 2.0 Camera                        | 2         | 2.06%   |
| Chicony Lenovo EasyCamera                     | 2         | 2.06%   |
| Chicony HD WebCam (Acer)                      | 2         | 2.06%   |
| Chicony HD WebCam                             | 2         | 2.06%   |
| Bison SunplusIT Integrated Camera             | 2         | 2.06%   |
| Bison Lenovo EasyCamera                       | 2         | 2.06%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 1.03%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.03%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.03%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.03%   |
| Realtek Laptop Camera                         | 1         | 1.03%   |
| Realtek Integrated Webcam HD                  | 1         | 1.03%   |
| Realtek HD WebCam                             | 1         | 1.03%   |
| Quanta VGA WebCam                             | 1         | 1.03%   |
| Quanta HP Webcam                              | 1         | 1.03%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.03%   |
| Quanta ACER HD User Facing                    | 1         | 1.03%   |
| Microdia Webcam Vitade AF                     | 1         | 1.03%   |
| Microdia Webcam                               | 1         | 1.03%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.03%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.03%   |
| Luxvisions Innotech Limited EasyCamera 1M     | 1         | 1.03%   |
| Logitech C505 HD Webcam                       | 1         | 1.03%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 1.03%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 42.86%  |
| Validity Sensors           | 3         | 21.43%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| Elan Microelectronics      | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 35.71%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 21.43%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                       | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Lenovo      | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 79        | 72.48%  |
| 1     | 24        | 22.02%  |
| 2     | 5         | 4.59%   |
| 3     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 38.89%  |
| Net/wireless             | 5         | 13.89%  |
| Chipcard                 | 5         | 13.89%  |
| Graphics card            | 4         | 11.11%  |
| Multimedia controller    | 2         | 5.56%   |
| Communication controller | 2         | 5.56%   |
| Camera                   | 2         | 5.56%   |
| Sound                    | 1         | 2.78%   |
| Net/ethernet             | 1         | 2.78%   |

