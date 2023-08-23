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

Total: 121

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Void Linux Rolling | 71        | 71.72%  |
| Void Linux         | 28        | 28.28%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.13.19_1   | 5         | 4.9%    |
| 5.18.19_1   | 4         | 3.92%   |
| 6.1.4_1     | 3         | 2.94%   |
| 5.8.18_1    | 3         | 2.94%   |
| 5.8.12_1    | 3         | 2.94%   |
| 5.3.9_1     | 3         | 2.94%   |
| 5.19.17_1   | 3         | 2.94%   |
| 5.10.17_1   | 3         | 2.94%   |
| 6.1.31_1    | 2         | 1.96%   |
| 6.1.21_1    | 2         | 1.96%   |
| 6.1.10_1    | 2         | 1.96%   |
| 5.4.24_1    | 2         | 1.96%   |
| 5.19.16_1   | 2         | 1.96%   |
| 5.18.14_1   | 2         | 1.96%   |
| 5.16.20_1   | 2         | 1.96%   |
| 5.15.32_1   | 2         | 1.96%   |
| 5.13.13_1   | 2         | 1.96%   |
| 5.12.10_1   | 2         | 1.96%   |
| 6.4.8_1     | 1         | 0.98%   |
| 6.3.12_1    | 1         | 0.98%   |
| 6.2.8_1     | 1         | 0.98%   |
| 6.2.11_1    | 1         | 0.98%   |
| 6.1.3_1     | 1         | 0.98%   |
| 6.1.29_1    | 1         | 0.98%   |
| 6.1.18_1    | 1         | 0.98%   |
| 6.1.14_1    | 1         | 0.98%   |
| 6.1.13_1    | 1         | 0.98%   |
| 6.0.9_1     | 1         | 0.98%   |
| 6.0.15_1    | 1         | 0.98%   |
| 6.0.10_1    | 1         | 0.98%   |
| 5.9.16_1    | 1         | 0.98%   |
| 5.9.14_1    | 1         | 0.98%   |
| 5.9.0-rc8_2 | 1         | 0.98%   |
| 5.8.9_1     | 1         | 0.98%   |
| 5.8.8_1     | 1         | 0.98%   |
| 5.8.7_1     | 1         | 0.98%   |
| 5.8.6_1     | 1         | 0.98%   |
| 5.8.12_2    | 1         | 0.98%   |
| 5.7.16_1    | 1         | 0.98%   |
| 5.4.35_1    | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.19 | 5         | 4.9%    |
| 5.8.12  | 4         | 3.92%   |
| 5.18.19 | 4         | 3.92%   |
| 6.1.4   | 3         | 2.94%   |
| 5.8.18  | 3         | 2.94%   |
| 5.3.9   | 3         | 2.94%   |
| 5.19.17 | 3         | 2.94%   |
| 5.10.17 | 3         | 2.94%   |
| 6.1.31  | 2         | 1.96%   |
| 6.1.21  | 2         | 1.96%   |
| 6.1.10  | 2         | 1.96%   |
| 5.4.24  | 2         | 1.96%   |
| 5.19.16 | 2         | 1.96%   |
| 5.18.14 | 2         | 1.96%   |
| 5.16.20 | 2         | 1.96%   |
| 5.15.32 | 2         | 1.96%   |
| 5.13.13 | 2         | 1.96%   |
| 5.12.10 | 2         | 1.96%   |
| 6.4.8   | 1         | 0.98%   |
| 6.3.12  | 1         | 0.98%   |
| 6.2.8   | 1         | 0.98%   |
| 6.2.11  | 1         | 0.98%   |
| 6.1.3   | 1         | 0.98%   |
| 6.1.29  | 1         | 0.98%   |
| 6.1.18  | 1         | 0.98%   |
| 6.1.14  | 1         | 0.98%   |
| 6.1.13  | 1         | 0.98%   |
| 6.0.9   | 1         | 0.98%   |
| 6.0.15  | 1         | 0.98%   |
| 6.0.10  | 1         | 0.98%   |
| 5.9.16  | 1         | 0.98%   |
| 5.9.14  | 1         | 0.98%   |
| 5.9.0   | 1         | 0.98%   |
| 5.8.9   | 1         | 0.98%   |
| 5.8.8   | 1         | 0.98%   |
| 5.8.7   | 1         | 0.98%   |
| 5.8.6   | 1         | 0.98%   |
| 5.7.16  | 1         | 0.98%   |
| 5.4.35  | 1         | 0.98%   |
| 5.4.21  | 1         | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 14        | 13.86%  |
| 5.15    | 12        | 11.88%  |
| 5.8     | 11        | 10.89%  |
| 5.13    | 11        | 10.89%  |
| 5.18    | 7         | 6.93%   |
| 5.12    | 7         | 6.93%   |
| 5.10    | 7         | 6.93%   |
| 5.4     | 5         | 4.95%   |
| 5.19    | 5         | 4.95%   |
| 6.0     | 3         | 2.97%   |
| 5.9     | 3         | 2.97%   |
| 5.3     | 3         | 2.97%   |
| 6.2     | 2         | 1.98%   |
| 5.16    | 2         | 1.98%   |
| 6.4     | 1         | 0.99%   |
| 6.3     | 1         | 0.99%   |
| 5.7     | 1         | 0.99%   |
| 5.2     | 1         | 0.99%   |
| 5.14    | 1         | 0.99%   |
| 5.11    | 1         | 0.99%   |
| 5.1     | 1         | 0.99%   |
| 4.4     | 1         | 0.99%   |
| 4.14    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 93        | 94.9%   |
| i686    | 3         | 3.06%   |
| aarch64 | 2         | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 41        | 40.59%  |
| XFCE         | 11        | 10.89%  |
| MATE         | 9         | 8.91%   |
| KDE          | 9         | 8.91%   |
| KDE5         | 7         | 6.93%   |
| i3           | 5         | 4.95%   |
| GNOME        | 5         | 4.95%   |
| X-Cinnamon   | 2         | 1.98%   |
| sway         | 2         | 1.98%   |
| bspwm        | 2         | 1.98%   |
| river        | 1         | 0.99%   |
| openbox      | 1         | 0.99%   |
| LXQt         | 1         | 0.99%   |
| LXDE         | 1         | 0.99%   |
| Lumina       | 1         | 0.99%   |
| dwm          | 1         | 0.99%   |
| dot-xsession | 1         | 0.99%   |
| awesome      | 1         | 0.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 67        | 67.68%  |
| Wayland | 13        | 13.13%  |
| Tty     | 12        | 12.12%  |
| Unknown | 7         | 7.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 77.78%  |
| LightDM | 8         | 8.08%   |
| SDDM    | 6         | 6.06%   |
| LXDM    | 6         | 6.06%   |
| SLiM    | 1         | 1.01%   |
| LDM     | 1         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 54        | 54%     |
| Unknown | 10        | 10%     |
| en_GB   | 7         | 7%      |
| es_ES   | 4         | 4%      |
| en_DK   | 4         | 4%      |
| de_DE   | 4         | 4%      |
| it_IT   | 3         | 3%      |
| en_CA   | 2         | 2%      |
| tr_TR   | 1         | 1%      |
| ru_UA   | 1         | 1%      |
| ru_RU   | 1         | 1%      |
| pt_BR   | 1         | 1%      |
| nb_NO   | 1         | 1%      |
| fr_FR   | 1         | 1%      |
| es_HN   | 1         | 1%      |
| es_DO   | 1         | 1%      |
| es_AR   | 1         | 1%      |
| en_NZ   | 1         | 1%      |
| en_AU   | 1         | 1%      |
| ca_ES   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 61.62%  |
| BIOS | 38        | 38.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 64.65%  |
| Btrfs   | 22        | 22.22%  |
| Unknown | 5         | 5.05%   |
| Xfs     | 4         | 4.04%   |
| Zfs     | 2         | 2.02%   |
| F2fs    | 1         | 1.01%   |
| Ext3    | 1         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 62        | 62%     |
| Unknown | 25        | 25%     |
| MBR     | 13        | 13%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 88.78%  |
| Yes       | 11        | 11.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 77.55%  |
| Yes       | 22        | 22.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 26.53%  |
| Hewlett-Packard     | 14        | 14.29%  |
| ASUSTek Computer    | 14        | 14.29%  |
| Acer                | 14        | 14.29%  |
| Dell                | 10        | 10.2%   |
| MSI                 | 3         | 3.06%   |
| Notebook            | 2         | 2.04%   |
| HUAWEI              | 2         | 2.04%   |
| Unknown             | 2         | 2.04%   |
| Timi                | 1         | 1.02%   |
| Samsung Electronics | 1         | 1.02%   |
| Positivo            | 1         | 1.02%   |
| Pine Microsystems   | 1         | 1.02%   |
| Nokia               | 1         | 1.02%   |
| Getac               | 1         | 1.02%   |
| Framework           | 1         | 1.02%   |
| Exo                 | 1         | 1.02%   |
| Digibras            | 1         | 1.02%   |
| Chuwi               | 1         | 1.02%   |
| Apple               | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP Laptop 15-bw0xx                        | 2         | 2.04%   |
| ASUS X751LD                               | 2         | 2.04%   |
| Acer Swift SF314-42                       | 2         | 2.04%   |
| Unknown                                   | 2         | 2.04%   |
| Timi Redmi Book Pro 15 2022               | 1         | 1.02%   |
| Samsung 275E4E/275E5E                     | 1         | 1.02%   |
| Positivo Mobile                           | 1         | 1.02%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 1.02%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 1.02%   |
| Notebook NH50_70RA                        | 1         | 1.02%   |
| Nokia Booklet 3G                          | 1         | 1.02%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 1.02%   |
| MSI GV72 7RE                              | 1         | 1.02%   |
| MSI Bravo 15 A4DDR                        | 1         | 1.02%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 1.02%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 1.02%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 1.02%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 1.02%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 1.02%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 1.02%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 1.02%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 1.02%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 1.02%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 1.02%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 1.02%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 1.02%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 1.02%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 1.02%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 1         | 1.02%   |
| Lenovo ThinkPad E595 20NFCTO1WW           | 1         | 1.02%   |
| Lenovo Legion Y540-15IRH-PG0 81SY         | 1         | 1.02%   |
| Lenovo IdeaPad Z570 10246ZG               | 1         | 1.02%   |
| Lenovo IdeaPad S145-15IWL 81MV            | 1         | 1.02%   |
| Lenovo IdeaPad S145-14IIL 81W6            | 1         | 1.02%   |
| Lenovo IdeaPad 710S-13IKB 80VQ            | 1         | 1.02%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5          | 1         | 1.02%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 1         | 1.02%   |
| Lenovo IdeaPad 100-14IBD 80RK             | 1         | 1.02%   |
| Lenovo G50-70 20351                       | 1         | 1.02%   |
| Lenovo G50-45 80E3                        | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 15        | 15.31%  |
| Acer Aspire              | 8         | 8.16%   |
| Lenovo IdeaPad           | 7         | 7.14%   |
| ASUS VivoBook            | 6         | 6.12%   |
| HP Laptop                | 5         | 5.1%    |
| Dell Inspiron            | 4         | 4.08%   |
| HP Pavilion              | 3         | 3.06%   |
| Dell Latitude            | 3         | 3.06%   |
| HP ENVY                  | 2         | 2.04%   |
| ASUS X751LD              | 2         | 2.04%   |
| Acer Swift               | 2         | 2.04%   |
| Unknown                  | 2         | 2.04%   |
| Timi Redmi               | 1         | 1.02%   |
| Samsung 275E4E           | 1         | 1.02%   |
| Positivo Mobile          | 1         | 1.02%   |
| Pine Microsystems Pine64 | 1         | 1.02%   |
| Notebook NV4XMB          | 1         | 1.02%   |
| Notebook NH50            | 1         | 1.02%   |
| Nokia Booklet            | 1         | 1.02%   |
| MSI Summit               | 1         | 1.02%   |
| MSI GV72                 | 1         | 1.02%   |
| MSI Bravo                | 1         | 1.02%   |
| Lenovo Y520-15IKB        | 1         | 1.02%   |
| Lenovo Legion            | 1         | 1.02%   |
| Lenovo G50-70            | 1         | 1.02%   |
| Lenovo G50-45            | 1         | 1.02%   |
| HUAWEI KLVL-WXXW         | 1         | 1.02%   |
| HUAWEI HN-WX9X           | 1         | 1.02%   |
| HP Stream                | 1         | 1.02%   |
| HP Notebook              | 1         | 1.02%   |
| HP 255                   | 1         | 1.02%   |
| HP 15                    | 1         | 1.02%   |
| Getac V110               | 1         | 1.02%   |
| Framework Laptop         | 1         | 1.02%   |
| Exo Exomate              | 1         | 1.02%   |
| Digibras NH4CU03         | 1         | 1.02%   |
| Dell XPS                 | 1         | 1.02%   |
| Dell Precision           | 1         | 1.02%   |
| Dell G3                  | 1         | 1.02%   |
| Chuwi GemiBook           | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 18        | 18.37%  |
| 2020    | 12        | 12.24%  |
| 2018    | 8         | 8.16%   |
| 2016    | 8         | 8.16%   |
| 2014    | 8         | 8.16%   |
| 2013    | 8         | 8.16%   |
| 2015    | 6         | 6.12%   |
| 2017    | 5         | 5.1%    |
| 2022    | 4         | 4.08%   |
| 2021    | 4         | 4.08%   |
| 2011    | 4         | 4.08%   |
| 2012    | 3         | 3.06%   |
| 2010    | 2         | 2.04%   |
| 2009    | 2         | 2.04%   |
| 2008    | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| 2007    | 1         | 1.02%   |
| 2006    | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 27        | 27.27%  |
| 3.01-4.0    | 22        | 22.22%  |
| 8.01-16.0   | 17        | 17.17%  |
| 16.01-24.0  | 16        | 16.16%  |
| 1.01-2.0    | 6         | 6.06%   |
| 32.01-64.0  | 5         | 5.05%   |
| 24.01-32.0  | 2         | 2.02%   |
| 0.51-1.0    | 2         | 2.02%   |
| 64.01-256.0 | 1         | 1.01%   |
| 0.01-0.5    | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 37        | 36.27%  |
| 2.01-3.0   | 23        | 22.55%  |
| 0.51-1.0   | 16        | 15.69%  |
| 4.01-8.0   | 10        | 9.8%    |
| 3.01-4.0   | 9         | 8.82%   |
| 0.01-0.5   | 4         | 3.92%   |
| 8.01-16.0  | 2         | 1.96%   |
| 16.01-24.0 | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 77.55%  |
| 2      | 19        | 19.39%  |
| 3      | 2         | 2.04%   |
| 0      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 75.51%  |
| Yes       | 24        | 24.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 71.43%  |
| No        | 28        | 28.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 95.92%  |
| No        | 4         | 4.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 82.65%  |
| No        | 17        | 17.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 14        | 14.29%  |
| Germany            | 11        | 11.22%  |
| Russia             | 9         | 9.18%   |
| India              | 9         | 9.18%   |
| Ukraine            | 4         | 4.08%   |
| Denmark            | 4         | 4.08%   |
| Brazil             | 4         | 4.08%   |
| Switzerland        | 3         | 3.06%   |
| UK                 | 2         | 2.04%   |
| Turkey             | 2         | 2.04%   |
| Spain              | 2         | 2.04%   |
| Netherlands        | 2         | 2.04%   |
| Morocco            | 2         | 2.04%   |
| Italy              | 2         | 2.04%   |
| France             | 2         | 2.04%   |
| Canada             | 2         | 2.04%   |
| Bulgaria           | 2         | 2.04%   |
| Australia          | 2         | 2.04%   |
| Argentina          | 2         | 2.04%   |
| Vietnam            | 1         | 1.02%   |
| Uruguay            | 1         | 1.02%   |
| Serbia             | 1         | 1.02%   |
| Peru               | 1         | 1.02%   |
| Norway             | 1         | 1.02%   |
| New Zealand        | 1         | 1.02%   |
| Mexico             | 1         | 1.02%   |
| Latvia             | 1         | 1.02%   |
| Indonesia          | 1         | 1.02%   |
| Honduras           | 1         | 1.02%   |
| Guatemala          | 1         | 1.02%   |
| Grenada            | 1         | 1.02%   |
| Greece             | 1         | 1.02%   |
| Ecuador            | 1         | 1.02%   |
| Dominican Republic | 1         | 1.02%   |
| Czechia            | 1         | 1.02%   |
| Colombia           | 1         | 1.02%   |
| Austria            | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 4         | 4.04%   |
| St Petersburg          | 3         | 3.03%   |
| Spring Hill            | 2         | 2.02%   |
| Rome                   | 2         | 2.02%   |
| Meknes                 | 2         | 2.02%   |
| Hyderabad              | 2         | 2.02%   |
| Geneva                 | 2         | 2.02%   |
| Yambol                 | 1         | 1.01%   |
| Weatherford            | 1         | 1.01%   |
| Volgograd              | 1         | 1.01%   |
| Vlaardingen            | 1         | 1.01%   |
| Vienna                 | 1         | 1.01%   |
| Viby J                 | 1         | 1.01%   |
| Trujillo               | 1         | 1.01%   |
| Toulouse               | 1         | 1.01%   |
| Touget                 | 1         | 1.01%   |
| Toms River             | 1         | 1.01%   |
| Tegucigalpa            | 1         | 1.01%   |
| Syktyvkar              | 1         | 1.01%   |
| Sydney                 | 1         | 1.01%   |
| Surabaya               | 1         | 1.01%   |
| Sun Prairie            | 1         | 1.01%   |
| Stratford              | 1         | 1.01%   |
| Solone                 | 1         | 1.01%   |
| Sohren                 | 1         | 1.01%   |
| Sofia                  | 1         | 1.01%   |
| Sistranda              | 1         | 1.01%   |
| Saxtons River          | 1         | 1.01%   |
| Sao Paulo              | 1         | 1.01%   |
| Santo Domingo          | 1         | 1.01%   |
| San Miguel de Tucumán | 1         | 1.01%   |
| Saint George's         | 1         | 1.01%   |
| Rostock                | 1         | 1.01%   |
| Rosenheim              | 1         | 1.01%   |
| Riga                   | 1         | 1.01%   |
| Reutlingen             | 1         | 1.01%   |
| Regensburg             | 1         | 1.01%   |
| Pune                   | 1         | 1.01%   |
| Prague                 | 1         | 1.01%   |
| Porto Alegre           | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 21        | 22     | 18.1%   |
| Seagate                   | 18        | 19     | 15.52%  |
| WDC                       | 13        | 14     | 11.21%  |
| Unknown                   | 8         | 13     | 6.9%    |
| Sandisk                   | 7         | 8      | 6.03%   |
| SK hynix                  | 6         | 6      | 5.17%   |
| HGST                      | 6         | 7      | 5.17%   |
| Toshiba                   | 5         | 5      | 4.31%   |
| Kingston                  | 5         | 5      | 4.31%   |
| Intel                     | 5         | 6      | 4.31%   |
| Crucial                   | 4         | 4      | 3.45%   |
| Phison                    | 2         | 2      | 1.72%   |
| Micron Technology         | 2         | 2      | 1.72%   |
| Hitachi                   | 2         | 2      | 1.72%   |
| Transcend                 | 1         | 1      | 0.86%   |
| PNY                       | 1         | 1      | 0.86%   |
| Phison Electronics        | 1         | 1      | 0.86%   |
| Patriot                   | 1         | 1      | 0.86%   |
| ORIGIN                    | 1         | 1      | 0.86%   |
| Micron/Crucial Technology | 1         | 1      | 0.86%   |
| Lenovo                    | 1         | 1      | 0.86%   |
| KIOXIA                    | 1         | 1      | 0.86%   |
| INNOVATION IT             | 1         | 1      | 0.86%   |
| China                     | 1         | 1      | 0.86%   |
| BHT                       | 1         | 1      | 0.86%   |
| Apple                     | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 4         | 3.33%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 2.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB               | 3         | 2.5%    |
| Crucial CT500MX500SSD1 500GB                      | 3         | 2.5%    |
| Unknown MMC Card  32GB                            | 2         | 1.67%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB           | 2         | 1.67%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 2         | 1.67%   |
| Samsung SSD 870 EVO 500GB                         | 2         | 1.67%   |
| Intel SSDPEKNW512G8 512GB                         | 2         | 1.67%   |
| HGST HTS545050A7E680 500GB                        | 2         | 1.67%   |
| HGST HTS541010B7E610 1TB                          | 2         | 1.67%   |
| HGST HTS541010A9E680 1TB                          | 2         | 1.67%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 0.83%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 0.83%   |
| WDC WD2500BEVT-22A23T0 250GB                      | 1         | 0.83%   |
| WDC WD1600BEVS-60VAT0 160GB                       | 1         | 0.83%   |
| WDC WD10SPZX-24Z10 1TB                            | 1         | 0.83%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 0.83%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 0.83%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.83%   |
| WDC WD Elements 320GB                             | 1         | 0.83%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB                | 1         | 0.83%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB              | 1         | 0.83%   |
| Unknown USB DISK 3.2 2TB                          | 1         | 0.83%   |
| Unknown SD512  512MB                              | 1         | 0.83%   |
| Unknown SD16G  16GB                               | 1         | 0.83%   |
| Unknown SD/MMC/MS PRO 128GB                       | 1         | 0.83%   |
| Unknown MMC Card  8GB                             | 1         | 0.83%   |
| Unknown MMC Card  2GB                             | 1         | 0.83%   |
| Unknown MMC Card  128GB                           | 1         | 0.83%   |
| Unknown MMC Card                                  | 1         | 0.83%   |
| Unknown CWBC3R  64GB                              | 1         | 0.83%   |
| Transcend TS128GMTS800 128GB SSD                  | 1         | 0.83%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 0.83%   |
| Toshiba KXG50ZNV512G NVMe 512GB                   | 1         | 0.83%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB            | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 19     | 42.86%  |
| WDC                 | 10        | 10     | 23.81%  |
| HGST                | 6         | 7      | 14.29%  |
| Toshiba             | 4         | 4      | 9.52%   |
| Hitachi             | 2         | 2      | 4.76%   |
| Unknown             | 1         | 1      | 2.38%   |
| Samsung Electronics | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 25.81%  |
| SanDisk             | 4         | 4      | 12.9%   |
| Kingston            | 4         | 4      | 12.9%   |
| Crucial             | 4         | 4      | 12.9%   |
| Transcend           | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| PNY                 | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| ORIGIN              | 1         | 1      | 3.23%   |
| Lenovo              | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| INNOVATION IT       | 1         | 1      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| BHT                 | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 41        | 44     | 36.28%  |
| NVMe    | 34        | 39     | 30.09%  |
| SSD     | 29        | 31     | 25.66%  |
| MMC     | 7         | 10     | 6.19%   |
| Unknown | 2         | 3      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 72     | 58.18%  |
| NVMe | 34        | 39     | 30.91%  |
| MMC  | 7         | 10     | 6.36%   |
| SAS  | 5         | 6      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 44     | 55.71%  |
| 0.51-1.0   | 29        | 29     | 41.43%  |
| 3.01-4.0   | 1         | 1      | 1.43%   |
| 4.01-10.0  | 1         | 1      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 32%     |
| 501-1000       | 24        | 24%     |
| 101-250        | 18        | 18%     |
| Unknown        | 7         | 7%      |
| 1-20           | 5         | 5%      |
| 51-100         | 5         | 5%      |
| 1001-2000      | 4         | 4%      |
| 21-50          | 3         | 3%      |
| More than 3000 | 1         | 1%      |
| 2001-3000      | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 26%     |
| 101-250        | 24        | 24%     |
| 21-50          | 18        | 18%     |
| 51-100         | 11        | 11%     |
| 251-500        | 9         | 9%      |
| Unknown        | 7         | 7%      |
| 1001-2000      | 3         | 3%      |
| More than 3000 | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB              | 2         | 2      | 14.29%  |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 7.14%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 7.14%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 7.14%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 7.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 7.14%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 7.14%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| HGST                | 3         | 3      | 21.43%  |
| Hitachi             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 46.15%  |
| HGST    | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| WDC     | 1         | 1      | 7.69%   |
| Toshiba | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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
| Works    | 58        | 69     | 54.72%  |
| Detected | 34        | 44     | 32.08%  |
| Malfunc  | 14        | 14     | 13.21%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 58        | 51.79%  |
| AMD                              | 21        | 18.75%  |
| Samsung Electronics              | 13        | 11.61%  |
| SK hynix                         | 5         | 4.46%   |
| SanDisk                          | 5         | 4.46%   |
| Phison Electronics               | 3         | 2.68%   |
| Micron Technology                | 2         | 1.79%   |
| Toshiba America Info Systems     | 1         | 0.89%   |
| Silicon Integrated Systems [SiS] | 1         | 0.89%   |
| Micron/Crucial Technology        | 1         | 0.89%   |
| KIOXIA                           | 1         | 0.89%   |
| Kingston Technology Company      | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 19        | 16.38%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 9.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 7.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 4.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 4         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 3.45%   |
| Samsung NVMe SSD Controller 980                                              | 3         | 2.59%   |
| Intel SSD 660P Series                                                        | 3         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.59%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 2         | 1.72%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 1.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 1.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.72%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 0.86%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.86%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                           | 1         | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.86%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                          | 1         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 0.86%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.86%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.86%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.86%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 0.86%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 1         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 69        | 61.06%  |
| NVMe | 34        | 30.09%  |
| RAID | 5         | 4.42%   |
| IDE  | 5         | 4.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 69.39%  |
| AMD    | 28        | 28.57%  |
| ARM    | 2         | 2.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 3.06%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 3.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.04%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.04%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 2.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 2.04%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 2.04%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.04%   |
| ARM Processor                                 | 2         | 2.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 2.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 2.04%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 2.04%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.02%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 1.02%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.02%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.02%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.02%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.02%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 1         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 20.41%  |
| Intel Core i7           | 16        | 16.33%  |
| Intel Core i3           | 13        | 13.27%  |
| Other                   | 10        | 10.2%   |
| AMD Ryzen 7             | 7         | 7.14%   |
| AMD Ryzen 5             | 7         | 7.14%   |
| Intel Celeron           | 5         | 5.1%    |
| Intel Atom              | 5         | 5.1%    |
| Intel Pentium           | 2         | 2.04%   |
| AMD Ryzen 7 PRO         | 2         | 2.04%   |
| AMD A8                  | 2         | 2.04%   |
| Intel Genuine           | 1         | 1.02%   |
| Intel Core 2 Duo        | 1         | 1.02%   |
| AMD Turion 64 X2 Mobile | 1         | 1.02%   |
| AMD Ryzen 5 PRO         | 1         | 1.02%   |
| AMD Ryzen 3             | 1         | 1.02%   |
| AMD E2                  | 1         | 1.02%   |
| AMD E1                  | 1         | 1.02%   |
| AMD C-60                | 1         | 1.02%   |
| AMD A4                  | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 42        | 42.86%  |
| 4      | 33        | 33.67%  |
| 6      | 10        | 10.2%   |
| 8      | 6         | 6.12%   |
| 1      | 5         | 5.1%    |
| 14     | 2         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 98.98%  |
| 2      | 1         | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 73.47%  |
| 1      | 26        | 26.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 90        | 91.84%  |
| Unknown        | 4         | 4.08%   |
| 64-bit         | 2         | 2.04%   |
| 32-bit         | 2         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 28%     |
| 0x40651    | 8         | 8%      |
| 0x406e3    | 4         | 4%      |
| 0x306a9    | 4         | 4%      |
| 0x08108102 | 4         | 4%      |
| 0x906ea    | 3         | 3%      |
| 0x806ec    | 3         | 3%      |
| 0x806e9    | 3         | 3%      |
| 0x30678    | 3         | 3%      |
| 0x206a7    | 3         | 3%      |
| 0x08600104 | 3         | 3%      |
| 0x906e9    | 2         | 2%      |
| 0x906a3    | 2         | 2%      |
| 0x106c2    | 2         | 2%      |
| 0x07030105 | 2         | 2%      |
| 0x06006705 | 2         | 2%      |
| 0x05000119 | 2         | 2%      |
| 0xa0652    | 1         | 1%      |
| 0x806eb    | 1         | 1%      |
| 0x806ea    | 1         | 1%      |
| 0x806c1    | 1         | 1%      |
| 0x706e5    | 1         | 1%      |
| 0x406c4    | 1         | 1%      |
| 0x306d4    | 1         | 1%      |
| 0x30673    | 1         | 1%      |
| 0x20652    | 1         | 1%      |
| 0x106ca    | 1         | 1%      |
| 0x10661    | 1         | 1%      |
| 0x0a50000c | 1         | 1%      |
| 0x0a404102 | 1         | 1%      |
| 0x0a404101 | 1         | 1%      |
| 0x08608103 | 1         | 1%      |
| 0x08608102 | 1         | 1%      |
| 0x08600106 | 1         | 1%      |
| 0x08600102 | 1         | 1%      |
| 0x08108109 | 1         | 1%      |
| 0x0810100b | 1         | 1%      |
| 0x08101007 | 1         | 1%      |
| 0x07030104 | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 21.43%  |
| Haswell          | 10        | 10.2%   |
| Zen 2            | 6         | 6.12%   |
| Skylake          | 6         | 6.12%   |
| Unknown          | 6         | 6.12%   |
| Zen+             | 5         | 5.1%    |
| Silvermont       | 5         | 5.1%    |
| SandyBridge      | 4         | 4.08%   |
| IvyBridge        | 4         | 4.08%   |
| Excavator        | 4         | 4.08%   |
| TigerLake        | 3         | 3.06%   |
| Puma             | 3         | 3.06%   |
| Bonnell          | 3         | 3.06%   |
| Zen              | 2         | 2.04%   |
| IceLake          | 2         | 2.04%   |
| Core             | 2         | 2.04%   |
| Broadwell        | 2         | 2.04%   |
| Bobcat           | 2         | 2.04%   |
| Alderlake Hybrid | 2         | 2.04%   |
| Zen 3            | 1         | 1.02%   |
| Westmere         | 1         | 1.02%   |
| Penryn           | 1         | 1.02%   |
| K8 Hammer        | 1         | 1.02%   |
| Goldmont plus    | 1         | 1.02%   |
| CometLake        | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 53.23%  |
| AMD                              | 29        | 23.39%  |
| Nvidia                           | 28        | 22.58%  |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 7.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 4.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.69%   |
| AMD Renoir                                                                | 6         | 4.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 3.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 4         | 3.13%   |
| Intel UHD Graphics 620                                                    | 3         | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.34%   |
| Intel HD Graphics 620                                                     | 3         | 2.34%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.56%   |
| Intel HD Graphics 630                                                     | 2         | 1.56%   |
| Intel HD Graphics 5500                                                    | 2         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.56%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.56%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.56%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.56%   |
| AMD Lucienne                                                              | 2         | 1.56%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.78%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.78%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.78%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.78%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 0.78%   |
| Nvidia GM108M [GeForce 830M]                                              | 1         | 0.78%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 41.84%  |
| Intel + Nvidia | 24        | 24.49%  |
| 1 x AMD        | 23        | 23.47%  |
| AMD + Nvidia   | 3         | 3.06%   |
| Other          | 2         | 2.04%   |
| 2 x AMD        | 2         | 2.04%   |
| 1 x SiS        | 1         | 1.02%   |
| 1 x Nvidia     | 1         | 1.02%   |
| Intel + AMD    | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 75        | 76.53%  |
| Proprietary | 20        | 20.41%  |
| Unknown     | 3         | 3.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 65.35%  |
| 0.01-0.5   | 12        | 11.88%  |
| 1.01-2.0   | 9         | 8.91%   |
| 0.51-1.0   | 7         | 6.93%   |
| 3.01-4.0   | 6         | 5.94%   |
| 5.01-6.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 22        | 21.57%  |
| AU Optronics         | 21        | 20.59%  |
| BOE                  | 16        | 15.69%  |
| LG Display           | 15        | 14.71%  |
| Samsung Electronics  | 4         | 3.92%   |
| PANDA                | 3         | 2.94%   |
| Sharp                | 2         | 1.96%   |
| LG Philips           | 2         | 1.96%   |
| Lenovo               | 2         | 1.96%   |
| Hewlett-Packard      | 2         | 1.96%   |
| Apple                | 2         | 1.96%   |
| AOC                  | 2         | 1.96%   |
| TMX                  | 1         | 0.98%   |
| STD                  | 1         | 0.98%   |
| Philips              | 1         | 0.98%   |
| Panasonic            | 1         | 0.98%   |
| InnoLux Display      | 1         | 0.98%   |
| Iiyama               | 1         | 0.98%   |
| Goldstar             | 1         | 0.98%   |
| CHR                  | 1         | 0.98%   |
| BOE Technology Group | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.94%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.94%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.96%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.96%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.98%   |
| STD LED STD0001 1024x768 300x230mm 14.9-inch                          | 1         | 0.98%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.98%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.98%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.98%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.98%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 0.98%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.98%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.98%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.98%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 222x125mm 10.0-inch      | 1         | 0.98%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                 | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 40        | 40%     |
| 1366x768 (WXGA)   | 30        | 30%     |
| 1920x1200 (WUXGA) | 5         | 5%      |
| 1600x900 (HD+)    | 5         | 5%      |
| 2160x1440         | 3         | 3%      |
| 1280x800 (WXGA)   | 3         | 3%      |
| 2560x1600         | 2         | 2%      |
| 2560x1440 (QHD)   | 2         | 2%      |
| 1024x600          | 2         | 2%      |
| 3840x2160 (4K)    | 1         | 1%      |
| 3440x1440         | 1         | 1%      |
| 3200x2000         | 1         | 1%      |
| 2880x1800         | 1         | 1%      |
| 2288x1287         | 1         | 1%      |
| 2256x1504         | 1         | 1%      |
| 1360x768          | 1         | 1%      |
| 1280x720 (HD)     | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 41.18%  |
| 14      | 17        | 16.67%  |
| 13      | 13        | 12.75%  |
| 17      | 5         | 4.9%    |
| 12      | 4         | 3.92%   |
| 23      | 3         | 2.94%   |
| 11      | 3         | 2.94%   |
| 24      | 2         | 1.96%   |
| 16      | 2         | 1.96%   |
| 10      | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 84      | 1         | 0.98%   |
| 39      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 33      | 1         | 0.98%   |
| 21      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 8       | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 63.73%  |
| 201-300     | 18        | 17.65%  |
| 501-600     | 5         | 4.9%    |
| 351-400     | 5         | 4.9%    |
| 701-800     | 2         | 1.96%   |
| 401-500     | 2         | 1.96%   |
| Unknown     | 2         | 1.96%   |
| 801-900     | 1         | 0.98%   |
| 1501-2000   | 1         | 0.98%   |
| 101-200     | 1         | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 78.95%  |
| 16/10   | 13        | 13.68%  |
| 3/2     | 5         | 5.26%   |
| 21/9    | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 40.2%   |
| 81-90          | 23        | 22.55%  |
| 71-80          | 6         | 5.88%   |
| 61-70          | 4         | 3.92%   |
| 201-250        | 4         | 3.92%   |
| 51-60          | 3         | 2.94%   |
| 121-130        | 3         | 2.94%   |
| 111-120        | 3         | 2.94%   |
| 351-500        | 2         | 1.96%   |
| 41-50          | 2         | 1.96%   |
| 251-300        | 2         | 1.96%   |
| 131-140        | 2         | 1.96%   |
| Unknown        | 2         | 1.96%   |
| More than 1000 | 1         | 0.98%   |
| 1-40           | 1         | 0.98%   |
| 141-150        | 1         | 0.98%   |
| 501-1000       | 1         | 0.98%   |
| 91-100         | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 43.56%  |
| 101-120       | 28        | 27.72%  |
| 51-100        | 14        | 13.86%  |
| 161-240       | 12        | 11.88%  |
| Unknown       | 2         | 1.98%   |
| More than 240 | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 84.69%  |
| 2     | 13        | 13.27%  |
| 0     | 2         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 52        | 37.68%  |
| Intel                            | 40        | 28.99%  |
| Qualcomm Atheros                 | 19        | 13.77%  |
| Broadcom                         | 10        | 7.25%   |
| Sierra Wireless                  | 3         | 2.17%   |
| Broadcom Limited                 | 3         | 2.17%   |
| Ralink Technology                | 2         | 1.45%   |
| Cypress Semiconductor            | 2         | 1.45%   |
| Xiaomi                           | 1         | 0.72%   |
| TP-Link                          | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |
| Ralink                           | 1         | 0.72%   |
| Qualcomm                         | 1         | 0.72%   |
| MediaTek                         | 1         | 0.72%   |
| Marvell Technology Group         | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 18.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 6.47%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 5.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 4.12%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 2.35%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.18%   |
| Intel Wireless 8260                                               | 2         | 1.18%   |
| Intel Wireless 7260                                               | 2         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.18%   |
| Cypress USB-C Dock ETH                                            | 2         | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.18%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.59%   |
| Sierra Wireless EM7455                                            | 1         | 0.59%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.59%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 40.4%   |
| Realtek Semiconductor | 23        | 23.23%  |
| Qualcomm Atheros      | 17        | 17.17%  |
| Broadcom              | 8         | 8.08%   |
| Sierra Wireless       | 3         | 3.03%   |
| Broadcom Limited      | 3         | 3.03%   |
| Ralink Technology     | 2         | 2.02%   |
| Ralink                | 1         | 1.01%   |
| Qualcomm              | 1         | 1.01%   |
| MediaTek              | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 7.07%   |
| Intel Wireless 8265 / 8275                                     | 6         | 6.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 5.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 5.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.04%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 4.04%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.02%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 2.02%   |
| Intel Wireless 8260                                            | 2         | 2.02%   |
| Intel Wireless 7260                                            | 2         | 2.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.02%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.02%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 2.02%   |
| Sierra Wireless EM7455                                         | 1         | 1.01%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.01%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.01%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.01%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 1.01%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.01%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.01%   |
| Intel Wireless-AC 9260                                         | 1         | 1.01%   |
| Intel Wireless 7265                                            | 1         | 1.01%   |
| Intel WiFi Link 5100                                           | 1         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 45        | 63.38%  |
| Intel                            | 14        | 19.72%  |
| Qualcomm Atheros                 | 3         | 4.23%   |
| Broadcom                         | 3         | 4.23%   |
| Cypress Semiconductor            | 2         | 2.82%   |
| Xiaomi                           | 1         | 1.41%   |
| TP-Link                          | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] | 1         | 1.41%   |
| Marvell Technology Group         | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 45.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 15.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.23%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.82%   |
| Cypress USB-C Dock ETH                                            | 2         | 2.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.41%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.41%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 57.32%  |
| Ethernet | 70        | 42.68%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 82.83%  |
| Ethernet | 17        | 17.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 63.27%  |
| 1     | 31        | 31.63%  |
| 0     | 4         | 4.08%   |
| 3     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 87%     |
| Yes  | 13        | 13%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 41.46%  |
| Realtek Semiconductor           | 15        | 18.29%  |
| Lite-On Technology              | 7         | 8.54%   |
| Broadcom                        | 6         | 7.32%   |
| Qualcomm Atheros Communications | 4         | 4.88%   |
| IMC Networks                    | 4         | 4.88%   |
| Foxconn / Hon Hai               | 3         | 3.66%   |
| Realtek                         | 2         | 2.44%   |
| Cambridge Silicon Radio         | 2         | 2.44%   |
| USI                             | 1         | 1.22%   |
| Opticis                         | 1         | 1.22%   |
| Foxconn International           | 1         | 1.22%   |
| Dell                            | 1         | 1.22%   |
| Apple                           | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 13.41%  |
| Intel AX200 Bluetooth                               | 9         | 10.98%  |
| Realtek Bluetooth Radio                             | 8         | 9.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 3.66%   |
| Intel AX201 Bluetooth                               | 3         | 3.66%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 2.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.44%   |
| Intel Bluetooth Device                              | 2         | 2.44%   |
| Intel AX210 Bluetooth                               | 2         | 2.44%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.44%   |
| IMC Networks Bluetooth Device                       | 2         | 2.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.44%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 2.44%   |
| USI Bluetooth Device                                | 1         | 1.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.22%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.22%   |
| Opticis Bluetooth Radio                             | 1         | 1.22%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.22%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.22%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.22%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.22%   |
| Broadcom HP Portable Valentine                      | 1         | 1.22%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 1.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.22%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.22%   |
| Apple Bluetooth Host Controller                     | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 60%     |
| AMD                              | 28        | 25.45%  |
| Nvidia                           | 10        | 9.09%   |
| Texas Instruments                | 2         | 1.82%   |
| Silicon Integrated Systems [SiS] | 1         | 0.91%   |
| Logitech                         | 1         | 0.91%   |
| JMTek                            | 1         | 0.91%   |
| Creative Technology              | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 11.56%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 6.8%    |
| Intel 8 Series HD Audio Controller                                                                | 10        | 6.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 4.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.72%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.72%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.04%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.36%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.36%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.36%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.36%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 1.36%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Logitech G432 Gaming Headset                                                                      | 1         | 0.68%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.68%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 26        | 30.95%  |
| Samsung Electronics | 25        | 29.76%  |
| Micron Technology   | 11        | 13.1%   |
| Unknown             | 5         | 5.95%   |
| Kingston            | 5         | 5.95%   |
| A-DATA Technology   | 4         | 4.76%   |
| Ramaxel Technology  | 2         | 2.38%   |
| Corsair             | 2         | 2.38%   |
| Transcend           | 1         | 1.19%   |
| Elpida              | 1         | 1.19%   |
| Crucial             | 1         | 1.19%   |
| 48spaces            | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 3.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 2.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 2         | 2.22%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 2.22%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 2.22%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 2.22%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s             | 1         | 1.11%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                 | 1         | 1.11%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 1.11%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 1         | 1.11%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 1.11%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 1.11%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.11%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.11%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.11%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s            | 1         | 1.11%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.11%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.11%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 1.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.11%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.11%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.11%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s    | 1         | 1.11%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 32        | 43.84%  |
| DDR3   | 31        | 42.47%  |
| LPDDR5 | 3         | 4.11%   |
| LPDDR4 | 3         | 4.11%   |
| DDR2   | 3         | 4.11%   |
| LPDDR3 | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 90.28%  |
| Row Of Chips | 6         | 8.33%   |
| DIMM         | 1         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 32        | 39.02%  |
| 4096  | 32        | 39.02%  |
| 16384 | 7         | 8.54%   |
| 2048  | 7         | 8.54%   |
| 1024  | 2         | 2.44%   |
| 512   | 2         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 29.87%  |
| 2667    | 18        | 23.38%  |
| 3200    | 12        | 15.58%  |
| 1334    | 5         | 6.49%   |
| 1333    | 4         | 5.19%   |
| 6400    | 3         | 3.9%    |
| 2400    | 3         | 3.9%    |
| 2133    | 2         | 2.6%    |
| 533     | 2         | 2.6%    |
| 4266    | 1         | 1.3%    |
| 3733    | 1         | 1.3%    |
| 1867    | 1         | 1.3%    |
| 667     | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

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
| Chicony Electronics                    | 28        | 31.82%  |
| IMC Networks                           | 15        | 17.05%  |
| Microdia                               | 9         | 10.23%  |
| Realtek Semiconductor                  | 7         | 7.95%   |
| Bison Electronics                      | 7         | 7.95%   |
| Quanta                                 | 6         | 6.82%   |
| Suyin                                  | 3         | 3.41%   |
| Sunplus Innovation Technology          | 3         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.41%   |
| Syntek                                 | 2         | 2.27%   |
| SunplusIT                              | 1         | 1.14%   |
| Silicon Motion                         | 1         | 1.14%   |
| Logitech                               | 1         | 1.14%   |
| Intel                                  | 1         | 1.14%   |
| Acer                                   | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 9         | 10.11%  |
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 6.74%   |
| Suyin HP Truevision HD                        | 3         | 3.37%   |
| Realtek USB Camera                            | 3         | 3.37%   |
| Quanta HD User Facing                         | 3         | 3.37%   |
| Microdia Integrated_Webcam_HD                 | 3         | 3.37%   |
| Syntek Integrated Camera                      | 2         | 2.25%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.25%   |
| Microdia HP Integrated Webcam                 | 2         | 2.25%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 2.25%   |
| IMC Networks Integrated Camera                | 2         | 2.25%   |
| IMC Networks HD Camera                        | 2         | 2.25%   |
| Chicony USB2.0 Camera                         | 2         | 2.25%   |
| Chicony USB 2.0 Camera                        | 2         | 2.25%   |
| Chicony Lenovo EasyCamera                     | 2         | 2.25%   |
| Chicony HP TrueVision HD Camera               | 2         | 2.25%   |
| Chicony HD WebCam (Acer)                      | 2         | 2.25%   |
| Chicony HD WebCam                             | 2         | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 2.25%   |
| Bison SunplusIT Integrated Camera             | 2         | 2.25%   |
| Bison Lenovo EasyCamera                       | 2         | 2.25%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 1.12%   |
| Sunplus HP Wide Vision HD                     | 1         | 1.12%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 1.12%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 1.12%   |
| Realtek Laptop Camera                         | 1         | 1.12%   |
| Realtek Integrated Webcam HD                  | 1         | 1.12%   |
| Realtek HD WebCam                             | 1         | 1.12%   |
| Quanta VGA WebCam                             | 1         | 1.12%   |
| Quanta HP Webcam                              | 1         | 1.12%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.12%   |
| Microdia Webcam Vitade AF                     | 1         | 1.12%   |
| Microdia Webcam                               | 1         | 1.12%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.12%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.12%   |
| Logitech C505 HD Webcam                       | 1         | 1.12%   |
| Intel RealSense 3D Camera (Front F200)        | 1         | 1.12%   |
| IMC Networks VGA UVC WebCam                   | 1         | 1.12%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 1.12%   |
| IMC Networks EasyCamera                       | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 45.45%  |
| Validity Sensors           | 3         | 27.27%  |
| Shenzhen Goodix Technology | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 36.36%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 27.27%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |

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
| 0     | 74        | 74.75%  |
| 1     | 19        | 19.19%  |
| 2     | 5         | 5.05%   |
| 3     | 1         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 35.48%  |
| Chipcard                 | 5         | 16.13%  |
| Net/wireless             | 4         | 12.9%   |
| Graphics card            | 4         | 12.9%   |
| Multimedia controller    | 2         | 6.45%   |
| Camera                   | 2         | 6.45%   |
| Sound                    | 1         | 3.23%   |
| Net/ethernet             | 1         | 3.23%   |
| Communication controller | 1         | 3.23%   |

