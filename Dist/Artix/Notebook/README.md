Artix - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Artix.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | B570e HuronRiver Platfor... | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell     | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell     | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek  | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo   | ThinkBook 15 G2 ITL 20VE    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi     | RedmiBook 14 II             | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| Lenovo   | ThinkPad 11e 5th Gen 20L... | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| Lenovo   | ThinkPad T480s 20L8S3D40... | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo   | ThinkPad T480s 20L8S3D40... | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP       | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi     | RedmiBook 14 II             | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi     | RedmiBook 14 II             | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Acer     | Swift SF314-59              | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer     | Swift SF314-59              | [0107549144](https://linux-hardware.org/?probe=0107549144) | Sep 23, 2021 |
| Acer     | Swift SF314-59              | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer     | Aspire E5-575               | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP       | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell     | Precision M6600             | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| ASUSTek  | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek  | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| GPD      | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD      | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| GPD      | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP       | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Dell     | Inspiron 3442               | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo   | LaVie Z 20FF0012US          | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP       | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| Apple    | MacBookAir7,2               | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP       | 250 G7 Notebook PC          | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP       | 250 G7 Notebook PC          | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell     | Precision 7550              | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Lenovo   | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell     | Precision 7550              | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| Dell     | Precision 7550              | [e7ccee4869](https://linux-hardware.org/?probe=e7ccee4869) | May 23, 2021 |
| UNOWHY   | Y13G010S4EI                 | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| HP       | Laptop 17z-ca300            | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| Acer     | Aspire V3-572PG             | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Apple    | MacBookAir7,2               | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple    | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Apple    | MacBookPro11,1              | [cc467b4015](https://linux-hardware.org/?probe=cc467b4015) | Mar 27, 2021 |
| Apple    | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI      | GP72 7RDX                   | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta   | SWH                         | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell     | Precision 7550              | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Acer     | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [dd81f9c015](https://linux-hardware.org/?probe=dd81f9c015) | Jan 23, 2021 |
| ASUSTek  | K53SC                       | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek  | K53SC                       | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| HP       | ProBook 450 G6              | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell     | Precision 5520              | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASUSTek  | E402NA                      | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple    | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Acer     | Aspire A315-53              | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Dell     | Precision 7550              | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte | B450M DS3H-CF               | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Dell     | Latitude E6530              | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte | B450M DS3H-CF               | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP       | 250 G4 Notebook PC          | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD      | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Sony     | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer     | Aspire A315-53              | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Lenovo   | IdeaPad L340-17IRH Gamin... | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP       | OMEN Laptop 15-en0xxx       | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek  | VivoBook_ASUS Laptop X50... | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek  | VivoBook_ASUS Laptop X50... | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell     | Inspiron 5570               | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo   | IdeaPad 5 15IIL05 81YK      | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| HP       | 255 G7 Notebook PC          | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Dell     | Precision 7550              | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| Dell     | Precision 7550              | [4b12417b4c](https://linux-hardware.org/?probe=4b12417b4c) | Sep 15, 2020 |
| Dell     | Precision 7550              | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell     | Precision 7550              | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| Dell     | Precision 7550              | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| Acer     | Nitro AN515-51              | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo   | IdeaPad 5 15IIL05 81YK      | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo   | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook | N130BU                      | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte | AERO 15-X9                  | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Gigabyte | AERO 15-X9                  | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| Gigabyte | AERO 15-X9                  | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| Acer     | Aspire E5-575G              | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| Dell     | Precision 3540              | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell     | Precision 3540              | [6b57174c98](https://linux-hardware.org/?probe=6b57174c98) | Mar 21, 2020 |
| Dell     | Precision 3540              | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Lenovo   | B590 20206                  | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 7.89%   |
| 5.7.6-artix1-1                  | 3         | 3.95%   |
| 5.7.12-artix1-1                 | 2         | 2.63%   |
| 5.14.16-artix1-1                | 2         | 2.63%   |
| 5.13.8-artix1-1                 | 2         | 2.63%   |
| 5.12.8-artix1-1                 | 2         | 2.63%   |
| 5.12.12-zen1-1-zen              | 2         | 2.63%   |
| 5.12.12-artix1-1                | 2         | 2.63%   |
| 5.11.6-artix1-1                 | 2         | 2.63%   |
| 5.10.6-artix1-1                 | 2         | 2.63%   |
| 5.10.4-artix2-1                 | 2         | 2.63%   |
| 5.10.16-artix1-1                | 2         | 2.63%   |
| 5.9.6-artix1-1                  | 1         | 1.32%   |
| 5.9.14-zen1-1-zen               | 1         | 1.32%   |
| 5.9.12-artix1-1                 | 1         | 1.32%   |
| 5.9.1-artix1-1                  | 1         | 1.32%   |
| 5.9.0-zen1-1-zen                | 1         | 1.32%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 1.32%   |
| 5.8.8-artix1-1                  | 1         | 1.32%   |
| 5.8.4-artix1-1                  | 1         | 1.32%   |
| 5.8.14-zen1-1-zen               | 1         | 1.32%   |
| 5.8.14-artix1-1                 | 1         | 1.32%   |
| 5.8.12-artix1-1                 | 1         | 1.32%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 1.32%   |
| 5.7.8-artix1-1                  | 1         | 1.32%   |
| 5.7.2-artix1-1                  | 1         | 1.32%   |
| 5.6.7-x86_64                    | 1         | 1.32%   |
| 5.5.3-artix1-1                  | 1         | 1.32%   |
| 5.5.10-artix1-1                 | 1         | 1.32%   |
| 5.4.74-1-lts                    | 1         | 1.32%   |
| 5.15.8-artix1-1                 | 1         | 1.32%   |
| 5.15.7-zen1-1-zen               | 1         | 1.32%   |
| 5.15.5-zen1-1-zen               | 1         | 1.32%   |
| 5.15.4-artix1-1                 | 1         | 1.32%   |
| 5.15.3-zen1-1-zen               | 1         | 1.32%   |
| 5.14.7-zen1-1-zen               | 1         | 1.32%   |
| 5.14.14-artix1-1                | 1         | 1.32%   |
| 5.13.13-xanmod1-1               | 1         | 1.32%   |
| 5.13.12-artix1-1                | 1         | 1.32%   |
| 5.12.8-zen1-1-zen               | 1         | 1.32%   |
| 5.12.6-artix1-1                 | 1         | 1.32%   |
| 5.12.5-artix1-1                 | 1         | 1.32%   |
| 5.12.4-artix1-1                 | 1         | 1.32%   |
| 5.12.14-zen1-1-zen              | 1         | 1.32%   |
| 5.12.14-artix1-1                | 1         | 1.32%   |
| 5.12.0-rc8                      | 1         | 1.32%   |
| 5.11.8-artix1-1                 | 1         | 1.32%   |
| 5.11.7-zen1-1-zen               | 1         | 1.32%   |
| 5.11.2-zen1-1-zen               | 1         | 1.32%   |
| 5.11.16-zen1-1-zen              | 1         | 1.32%   |
| 5.11.12-artix1-1                | 1         | 1.32%   |
| 5.11.1-artix1-1                 | 1         | 1.32%   |
| 5.10.82-1-lts                   | 1         | 1.32%   |
| 5.10.8-artix1-1                 | 1         | 1.32%   |
| 5.10.64-1-lts                   | 1         | 1.32%   |
| 5.10.5-zen1-1-zen               | 1         | 1.32%   |
| 5.10.15-artix1-1                | 1         | 1.32%   |
| 5.10.0-pf0-nicer-rt-22+         | 1         | 1.32%   |
| 4.19.0-1-MANJARO                | 1         | 1.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 9.21%   |
| 5.12.12 | 4         | 5.26%   |
| 5.7.6   | 3         | 3.95%   |
| 5.12.8  | 3         | 3.95%   |
| 5.9.0   | 2         | 2.63%   |
| 5.8.14  | 2         | 2.63%   |
| 5.7.12  | 2         | 2.63%   |
| 5.14.16 | 2         | 2.63%   |
| 5.13.8  | 2         | 2.63%   |
| 5.12.14 | 2         | 2.63%   |
| 5.11.6  | 2         | 2.63%   |
| 5.10.6  | 2         | 2.63%   |
| 5.10.4  | 2         | 2.63%   |
| 5.10.16 | 2         | 2.63%   |
| 5.9.6   | 1         | 1.32%   |
| 5.9.12  | 1         | 1.32%   |
| 5.9.1   | 1         | 1.32%   |
| 5.8.8   | 1         | 1.32%   |
| 5.8.4   | 1         | 1.32%   |
| 5.8.12  | 1         | 1.32%   |
| 5.8.0   | 1         | 1.32%   |
| 5.7.8   | 1         | 1.32%   |
| 5.7.2   | 1         | 1.32%   |
| 5.6.7   | 1         | 1.32%   |
| 5.5.3   | 1         | 1.32%   |
| 5.5.10  | 1         | 1.32%   |
| 5.4.74  | 1         | 1.32%   |
| 5.15.8  | 1         | 1.32%   |
| 5.15.7  | 1         | 1.32%   |
| 5.15.5  | 1         | 1.32%   |
| 5.15.4  | 1         | 1.32%   |
| 5.15.3  | 1         | 1.32%   |
| 5.14.7  | 1         | 1.32%   |
| 5.14.14 | 1         | 1.32%   |
| 5.13.13 | 1         | 1.32%   |
| 5.13.12 | 1         | 1.32%   |
| 5.12.6  | 1         | 1.32%   |
| 5.12.5  | 1         | 1.32%   |
| 5.12.4  | 1         | 1.32%   |
| 5.12.0  | 1         | 1.32%   |
| 5.11.8  | 1         | 1.32%   |
| 5.11.7  | 1         | 1.32%   |
| 5.11.2  | 1         | 1.32%   |
| 5.11.16 | 1         | 1.32%   |
| 5.11.12 | 1         | 1.32%   |
| 5.11.1  | 1         | 1.32%   |
| 5.10.82 | 1         | 1.32%   |
| 5.10.8  | 1         | 1.32%   |
| 5.10.64 | 1         | 1.32%   |
| 5.10.5  | 1         | 1.32%   |
| 5.10.15 | 1         | 1.32%   |
| 5.10.0  | 1         | 1.32%   |
| 4.19.0  | 1         | 1.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.12    | 12        | 17.14%  |
| 5.9     | 11        | 15.71%  |
| 5.10    | 11        | 15.71%  |
| 5.11    | 8         | 11.43%  |
| 5.7     | 6         | 8.57%   |
| 5.8     | 5         | 7.14%   |
| 5.15    | 5         | 7.14%   |
| 5.14    | 4         | 5.71%   |
| 5.13    | 4         | 5.71%   |
| 5.6     | 1         | 1.43%   |
| 5.5     | 1         | 1.43%   |
| 5.4     | 1         | 1.43%   |
| 4.19    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 60        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| XFCE       | 12        | 18.46%  |
| KDE5       | 12        | 18.46%  |
| Unknown    | 11        | 16.92%  |
| GNOME      | 10        | 15.38%  |
| X-Cinnamon | 4         | 6.15%   |
| KDE        | 4         | 6.15%   |
| LXQt       | 3         | 4.62%   |
| Cinnamon   | 3         | 4.62%   |
| MATE       | 2         | 3.08%   |
| xmonad     | 1         | 1.54%   |
| nxde       | 1         | 1.54%   |
| LXDE       | 1         | 1.54%   |
| bspwm      | 1         | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 42        | 66.67%  |
| Tty     | 11        | 17.46%  |
| Wayland | 6         | 9.52%   |
| Unknown | 4         | 6.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 37.7%   |
| LightDM | 20        | 32.79%  |
| SDDM    | 16        | 26.23%  |
| SLiM    | 1         | 1.64%   |
| GDM     | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 33        | 53.23%  |
| Unknown | 9         | 14.52%  |
| ru_RU   | 6         | 9.68%   |
| en_GB   | 4         | 6.45%   |
| fr_FR   | 2         | 3.23%   |
| pt_PT   | 1         | 1.61%   |
| pt_BR   | 1         | 1.61%   |
| pl_PL   | 1         | 1.61%   |
| it_IT   | 1         | 1.61%   |
| en_CA   | 1         | 1.61%   |
| el_GR   | 1         | 1.61%   |
| de_DE   | 1         | 1.61%   |
| C       | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 45        | 73.77%  |
| BIOS | 16        | 26.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 71.67%  |
| Btrfs   | 13        | 21.67%  |
| Xfs     | 2         | 3.33%   |
| Overlay | 1         | 1.67%   |
| F2fs    | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 44        | 72.13%  |
| Unknown | 10        | 16.39%  |
| MBR     | 7         | 11.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 80.33%  |
| Yes       | 12        | 19.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 73.33%  |
| Yes       | 16        | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 28.33%  |
| Hewlett-Packard     | 9         | 15%     |
| Dell                | 9         | 15%     |
| Acer                | 7         | 11.67%  |
| ASUSTek Computer    | 5         | 8.33%   |
| Apple               | 3         | 5%      |
| Timi                | 2         | 3.33%   |
| GPD                 | 2         | 3.33%   |
| Gigabyte Technology | 2         | 3.33%   |
| UNOWHY              | 1         | 1.67%   |
| Quanta              | 1         | 1.67%   |
| Notebook            | 1         | 1.67%   |
| MSI                 | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                    | 2         | 3.33%   |
| Lenovo IdeaPad 5 15IIL05 81YK           | 2         | 3.33%   |
| GPD P2 MAX                              | 2         | 3.33%   |
| Dell Precision 7550                     | 2         | 3.33%   |
| Apple MacBookAir7,2                     | 2         | 3.33%   |
| UNOWHY Y13G010S4EI                      | 1         | 1.67%   |
| Quanta SWH                              | 1         | 1.67%   |
| Notebook N130BU                         | 1         | 1.67%   |
| MSI GP72 7RDX                           | 1         | 1.67%   |
| Lenovo ThinkPad W500 4063CJ5            | 1         | 1.67%   |
| Lenovo ThinkPad T480s 20L8S3D400        | 1         | 1.67%   |
| Lenovo ThinkPad T420 4236H45            | 1         | 1.67%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00    | 1         | 1.67%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800    | 1         | 1.67%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH     | 1         | 1.67%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500  | 1         | 1.67%   |
| Lenovo ThinkBook 15 G2 ITL 20VE         | 1         | 1.67%   |
| Lenovo LaVie Z 20FF0012US               | 1         | 1.67%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL   | 1         | 1.67%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG    | 1         | 1.67%   |
| Lenovo IdeaPad 510-15IKB 80SV           | 1         | 1.67%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 1.67%   |
| Lenovo B590 20206                       | 1         | 1.67%   |
| Lenovo B570e HuronRiver Platform        | 1         | 1.67%   |
| HP ProBook 450 G6                       | 1         | 1.67%   |
| HP OMEN Laptop 15-en0xxx                | 1         | 1.67%   |
| HP Laptop 17z-ca300                     | 1         | 1.67%   |
| HP Laptop 14s-cf3xxx                    | 1         | 1.67%   |
| HP 255 G7 Notebook PC                   | 1         | 1.67%   |
| HP 250 G7 Notebook PC                   | 1         | 1.67%   |
| HP 250 G4 Notebook PC                   | 1         | 1.67%   |
| HP 250 G3                               | 1         | 1.67%   |
| HP 15                                   | 1         | 1.67%   |
| Gigabyte B450M DS3H                     | 1         | 1.67%   |
| Gigabyte AERO 15-X9                     | 1         | 1.67%   |
| Dell Precision M6600                    | 1         | 1.67%   |
| Dell Precision 5520                     | 1         | 1.67%   |
| Dell Precision 3540                     | 1         | 1.67%   |
| Dell Latitude E6530                     | 1         | 1.67%   |
| Dell Latitude E6440                     | 1         | 1.67%   |
| Dell Inspiron 5570                      | 1         | 1.67%   |
| Dell Inspiron 3442                      | 1         | 1.67%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 1         | 1.67%   |
| ASUS K53SC                              | 1         | 1.67%   |
| ASUS K50IE                              | 1         | 1.67%   |
| ASUS GL702ZC                            | 1         | 1.67%   |
| ASUS E402NA                             | 1         | 1.67%   |
| Apple MacBookPro11,1                    | 1         | 1.67%   |
| Acer Swift SF314-59                     | 1         | 1.67%   |
| Acer Nitro AN515-51                     | 1         | 1.67%   |
| Acer Aspire V3-572PG                    | 1         | 1.67%   |
| Acer Aspire E5-575G                     | 1         | 1.67%   |
| Acer Aspire E5-575                      | 1         | 1.67%   |
| Acer Aspire A315-53                     | 1         | 1.67%   |
| Acer Aspire 5733Z                       | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 11.67%  |
| Lenovo IdeaPad     | 6         | 10%     |
| Dell Precision     | 5         | 8.33%   |
| Acer Aspire        | 5         | 8.33%   |
| HP 250             | 3         | 5%      |
| Timi RedmiBook     | 2         | 3.33%   |
| HP Laptop          | 2         | 3.33%   |
| GPD P2             | 2         | 3.33%   |
| Dell Latitude      | 2         | 3.33%   |
| Dell Inspiron      | 2         | 3.33%   |
| Apple MacBookAir7  | 2         | 3.33%   |
| UNOWHY Y13G010S4EI | 1         | 1.67%   |
| Quanta SWH         | 1         | 1.67%   |
| Notebook N130BU    | 1         | 1.67%   |
| MSI GP72           | 1         | 1.67%   |
| Lenovo ThinkBook   | 1         | 1.67%   |
| Lenovo LaVie       | 1         | 1.67%   |
| Lenovo B590        | 1         | 1.67%   |
| Lenovo B570e       | 1         | 1.67%   |
| HP ProBook         | 1         | 1.67%   |
| HP OMEN            | 1         | 1.67%   |
| HP 255             | 1         | 1.67%   |
| HP 15              | 1         | 1.67%   |
| Gigabyte B450M     | 1         | 1.67%   |
| Gigabyte AERO      | 1         | 1.67%   |
| ASUS VivoBook      | 1         | 1.67%   |
| ASUS K53SC         | 1         | 1.67%   |
| ASUS K50IE         | 1         | 1.67%   |
| ASUS GL702ZC       | 1         | 1.67%   |
| ASUS E402NA        | 1         | 1.67%   |
| Apple MacBookPro11 | 1         | 1.67%   |
| Acer Swift         | 1         | 1.67%   |
| Acer Nitro         | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 33.33%  |
| 2019 | 14        | 23.33%  |
| 2018 | 6         | 10%     |
| 2021 | 4         | 6.67%   |
| 2017 | 4         | 6.67%   |
| 2011 | 4         | 6.67%   |
| 2014 | 3         | 5%      |
| 2012 | 3         | 5%      |
| 2016 | 1         | 1.67%   |
| 2015 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 98.33%  |
| Enabled  | 1         | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 27.87%  |
| 8.01-16.0   | 17        | 27.87%  |
| 16.01-24.0  | 11        | 18.03%  |
| 3.01-4.0    | 9         | 14.75%  |
| 32.01-64.0  | 3         | 4.92%   |
| 64.01-256.0 | 3         | 4.92%   |
| 1.01-2.0    | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 19        | 27.54%  |
| 2.01-3.0   | 17        | 24.64%  |
| 4.01-8.0   | 11        | 15.94%  |
| 3.01-4.0   | 9         | 13.04%  |
| 0.51-1.0   | 7         | 10.14%  |
| 8.01-16.0  | 4         | 5.8%    |
| 16.01-24.0 | 1         | 1.45%   |
| 0.01-0.5   | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 72.13%  |
| 2      | 16        | 26.23%  |
| 3      | 1         | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 70%     |
| Yes       | 18        | 30%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 78.33%  |
| No        | 13        | 21.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 98.33%  |
| No        | 1         | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 80.65%  |
| No        | 12        | 19.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 20%     |
| Russia      | 6         | 10%     |
| Germany     | 4         | 6.67%   |
| Ukraine     | 3         | 5%      |
| UK          | 3         | 5%      |
| Turkey      | 3         | 5%      |
| France      | 3         | 5%      |
| Canada      | 3         | 5%      |
| Brazil      | 3         | 5%      |
| Switzerland | 2         | 3.33%   |
| Poland      | 2         | 3.33%   |
| Netherlands | 2         | 3.33%   |
| Uzbekistan  | 1         | 1.67%   |
| Sweden      | 1         | 1.67%   |
| Lithuania   | 1         | 1.67%   |
| Italy       | 1         | 1.67%   |
| Indonesia   | 1         | 1.67%   |
| India       | 1         | 1.67%   |
| Greece      | 1         | 1.67%   |
| China       | 1         | 1.67%   |
| Chile       | 1         | 1.67%   |
| Bulgaria    | 1         | 1.67%   |
| Bangladesh  | 1         | 1.67%   |
| Azerbaijan  | 1         | 1.67%   |
| Argentina   | 1         | 1.67%   |
| Algeria     | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| St Petersburg     | 2         | 3.13%   |
| San Ramon         | 2         | 3.13%   |
| Paris             | 2         | 3.13%   |
| Neuchatel         | 2         | 3.13%   |
| Los Angeles       | 2         | 3.13%   |
| Kyiv              | 2         | 3.13%   |
| Frankfurt am Main | 2         | 3.13%   |
| Amsterdam         | 2         | 3.13%   |
| Çorum            | 1         | 1.56%   |
| Zaporizhzhya      | 1         | 1.56%   |
| York              | 1         | 1.56%   |
| Yekaterinburg     | 1         | 1.56%   |
| Xirdalan          | 1         | 1.56%   |
| Wigan             | 1         | 1.56%   |
| Vilnius           | 1         | 1.56%   |
| Vancouver         | 1         | 1.56%   |
| Toronto           | 1         | 1.56%   |
| Thassos           | 1         | 1.56%   |
| Syeverodonets'k   | 1         | 1.56%   |
| Surgut            | 1         | 1.56%   |
| Stuttgart         | 1         | 1.56%   |
| Stockholm         | 1         | 1.56%   |
| Srednyaya Akhtuba | 1         | 1.56%   |
| Sofia             | 1         | 1.56%   |
| Seattle           | 1         | 1.56%   |
| Santiago          | 1         | 1.56%   |
| Santa Fe          | 1         | 1.56%   |
| Sainte-Severe     | 1         | 1.56%   |
| Roseburg          | 1         | 1.56%   |
| Quincy            | 1         | 1.56%   |
| Ordu              | 1         | 1.56%   |
| Omsk              | 1         | 1.56%   |
| Nottingham        | 1         | 1.56%   |
| Nantes            | 1         | 1.56%   |
| Mount Pearl       | 1         | 1.56%   |
| Milton            | 1         | 1.56%   |
| Mestre            | 1         | 1.56%   |
| Mesquite          | 1         | 1.56%   |
| Malda             | 1         | 1.56%   |
| Lexington         | 1         | 1.56%   |
| Leander           | 1         | 1.56%   |
| Lavras            | 1         | 1.56%   |
| Laurel            | 1         | 1.56%   |
| Klobuck           | 1         | 1.56%   |
| K?�odzko          | 1         | 1.56%   |
| Jakarta           | 1         | 1.56%   |
| Hinsdale          | 1         | 1.56%   |
| Guacui            | 1         | 1.56%   |
| Dhaka             | 1         | 1.56%   |
| Castanhal         | 1         | 1.56%   |
| Boysun            | 1         | 1.56%   |
| Berlin            | 1         | 1.56%   |
| Beijing           | 1         | 1.56%   |
| Bedford           | 1         | 1.56%   |
| Antalya           | 1         | 1.56%   |
| Annaba            | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 22.37%  |
| Seagate             | 10        | 10     | 13.16%  |
| WDC                 | 8         | 11     | 10.53%  |
| Toshiba             | 7         | 7      | 9.21%   |
| SK Hynix            | 4         | 11     | 5.26%   |
| Sandisk             | 3         | 3      | 3.95%   |
| Kingston            | 3         | 4      | 3.95%   |
| Intel               | 3         | 5      | 3.95%   |
| Hitachi             | 3         | 4      | 3.95%   |
| HGST                | 3         | 3      | 3.95%   |
| Apple               | 3         | 4      | 3.95%   |
| Unknown             | 2         | 2      | 2.63%   |
| Phison Electronics  | 2         | 3      | 2.63%   |
| China               | 2         | 2      | 2.63%   |
| Solid State Storage | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Linux               | 1         | 1      | 1.32%   |
| LDLC                | 1         | 6      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| Crucial             | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 3.7%    |
| Sandisk NVMe SSD Drive 512GB              | 3         | 3.7%    |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 2.47%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.47%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 2.47%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 2         | 2.47%   |
| Phison PCIe SSD 512GB                     | 2         | 2.47%   |
| HGST HTS545050A7E680 500GB                | 2         | 2.47%   |
| China SATA SSD 960GB                      | 2         | 2.47%   |
| Apple SSD SM0256G 256GB                   | 2         | 2.47%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 1.23%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.23%   |
| WDC WD5000BPVT-22HXZT3 500GB              | 1         | 1.23%   |
| WDC WD3200LPVT-00FMCT0 320GB              | 1         | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.23%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 1.23%   |
| Unknown SD/MMC/MS PRO 7GB                 | 1         | 1.23%   |
| Unknown DA4064  64GB                      | 1         | 1.23%   |
| Toshiba THNSNH128GMCT 128GB SSD           | 1         | 1.23%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.23%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1.23%   |
| Toshiba MK5065GSX 500GB                   | 1         | 1.23%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 1.23%   |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 1.23%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 1.23%   |
| SK Hynix SC311 SATA 256GB SSD             | 1         | 1.23%   |
| SK Hynix NVMe SSD Drive 1TB               | 1         | 1.23%   |
| SK Hynix NVMe SSD Drive 1024GB            | 1         | 1.23%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 1.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.23%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.23%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.23%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.23%   |
| Seagate BUP Portable 4TB                  | 1         | 1.23%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.23%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 1.23%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.23%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB    | 1         | 1.23%   |
| Samsung SM961 NVMe 512GB                  | 1         | 1.23%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.23%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 1         | 1.23%   |
| Samsung MZVPW256HEGL-000L7 256GB          | 1         | 1.23%   |
| Samsung MZVLQ512HALU-00000 512GB          | 1         | 1.23%   |
| Samsung MZVLB512HBJQ-000H1 512GB          | 1         | 1.23%   |
| Samsung MZVLB256HBHQ-00000 256GB          | 1         | 1.23%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 1         | 1.23%   |
| Samsung MZNTE256HMHP-000L1 256GB SSD      | 1         | 1.23%   |
| Samsung MZALQ512HALU-000L2 512GB          | 1         | 1.23%   |
| PNY CS900 240GB SSD                       | 1         | 1.23%   |
| Linux scsi_debug 8.3MB                    | 1         | 1.23%   |
| LDLC SSD 120GB                            | 1         | 1.23%   |
| Kingston SM2280S3G2120G 120GB SSD         | 1         | 1.23%   |
| Kingston SA400S37240G 240GB SSD           | 1         | 1.23%   |
| Kingston OM8PCP3512F-AA 512GB             | 1         | 1.23%   |
| Kingston NVMe SSD Drive 512GB             | 1         | 1.23%   |
| Intenso SSD SATAIII 128GB                 | 1         | 1.23%   |
| Intel SSDPEKKW128G8 128GB                 | 1         | 1.23%   |
| Intel NVMe SSD Drive 512GB                | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 34.48%  |
| WDC     | 7         | 9      | 24.14%  |
| Toshiba | 5         | 5      | 17.24%  |
| Hitachi | 3         | 4      | 10.34%  |
| HGST    | 3         | 3      | 10.34%  |
| Unknown | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 25%     |
| Apple               | 3         | 4      | 15%     |
| Kingston            | 2         | 2      | 10%     |
| China               | 2         | 2      | 10%     |
| WDC                 | 1         | 2      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| Linux               | 1         | 1      | 5%      |
| LDLC                | 1         | 6      | 5%      |
| Intenso             | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 32     | 39.44%  |
| NVMe | 23        | 40     | 32.39%  |
| SSD  | 19        | 27     | 26.76%  |
| MMC  | 1         | 1      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 57     | 62.86%  |
| NVMe | 23        | 40     | 32.86%  |
| SAS  | 2         | 2      | 2.86%   |
| MMC  | 1         | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 34     | 55.32%  |
| 0.51-1.0   | 17        | 20     | 36.17%  |
| 1.01-2.0   | 3         | 4      | 6.38%   |
| 3.01-4.0   | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 27.87%  |
| 251-500        | 13        | 21.31%  |
| 501-1000       | 10        | 16.39%  |
| 1001-2000      | 6         | 9.84%   |
| 51-100         | 5         | 8.2%    |
| Unknown        | 5         | 8.2%    |
| More than 3000 | 2         | 3.28%   |
| 1-20           | 2         | 3.28%   |
| 2001-3000      | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 24.24%  |
| 51-100    | 13        | 19.7%   |
| 21-50     | 11        | 16.67%  |
| 101-250   | 8         | 12.12%  |
| 501-1000  | 8         | 12.12%  |
| Unknown   | 5         | 7.58%   |
| 1001-2000 | 3         | 4.55%   |
| 251-500   | 2         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB     | 2         | 2      | 22.22%  |
| WDC WD3200LPVT-00FMCT0 320GB   | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 11.11%  |
| Toshiba MK5065GSX 500GB        | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 11.11%  |
| LDLC SSD 120GB                 | 1         | 3      | 11.11%  |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 11.11%  |
| Hitachi HTS542516K9SA00 160GB  | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 22.22%  |
| Hitachi | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Seagate | 1         | 1      | 11.11%  |
| LDLC    | 1         | 3      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Seagate | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 88.89%  |
| SSD  | 1         | 3      | 11.11%  |

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
| Works    | 33        | 43     | 51.56%  |
| Detected | 22        | 46     | 34.38%  |
| Malfunc  | 9         | 11     | 14.06%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 40        | 52.63%  |
| Samsung Electronics            | 14        | 18.42%  |
| AMD                            | 8         | 10.53%  |
| SK Hynix                       | 3         | 3.95%   |
| Sandisk                        | 3         | 3.95%   |
| Phison Electronics             | 2         | 2.63%   |
| Union Memory (Shenzhen)        | 1         | 1.32%   |
| Toshiba America Info Systems   | 1         | 1.32%   |
| Solid State Storage Technology | 1         | 1.32%   |
| Nvidia                         | 1         | 1.32%   |
| Marvell Technology Group       | 1         | 1.32%   |
| Kingston Technology Company    | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 8.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 8.75%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 8.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 5%      |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3.75%   |
| SK Hynix Non-Volatile memory controller                                        | 2         | 2.5%    |
| Sandisk Non-Volatile memory controller                                         | 2         | 2.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.5%    |
| Samsung Electronics SATA controller                                            | 2         | 2.5%    |
| Phison E12 NVMe Controller                                                     | 2         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.5%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 2.5%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.5%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1.25%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.25%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.25%   |
| SK Hynix BC511                                                                 | 1         | 1.25%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.25%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.25%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.25%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.25%   |
| Intel SSD 660P Series                                                          | 1         | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.25%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 59.21%  |
| NVMe | 24        | 31.58%  |
| RAID | 7         | 9.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 85%     |
| AMD    | 9         | 15%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 4.92%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 3.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.28%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 3.28%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 3.28%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 3.28%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 1.64%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.64%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.64%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.64%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.64%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 1.64%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 1.64%   |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 1.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.64%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 1.64%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.64%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.64%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.64%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 1.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.64%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.64%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.64%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.64%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.64%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.64%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz          | 1         | 1.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.64%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.64%   |
| Intel Celeron CPU B800 @ 1.50GHz              | 1         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.64%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.64%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 1         | 1.64%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 1         | 1.64%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.64%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 26.67%  |
| Intel Core i7           | 11        | 18.33%  |
| Intel Core i3           | 8         | 13.33%  |
| AMD Ryzen 7             | 5         | 8.33%   |
| Intel Celeron           | 4         | 6.67%   |
| Other                   | 2         | 3.33%   |
| Intel Pentium           | 2         | 3.33%   |
| Intel Core m3           | 2         | 3.33%   |
| Intel Core i9           | 2         | 3.33%   |
| Intel Xeon              | 1         | 1.67%   |
| Intel Pentium Silver    | 1         | 1.67%   |
| Intel Pentium Dual-Core | 1         | 1.67%   |
| Intel Core 2 Duo        | 1         | 1.67%   |
| AMD Ryzen 9             | 1         | 1.67%   |
| AMD Ryzen 5 PRO         | 1         | 1.67%   |
| AMD Ryzen 5             | 1         | 1.67%   |
| AMD Ryzen 3             | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 51.67%  |
| 4      | 16        | 26.67%  |
| 8      | 7         | 11.67%  |
| 6      | 5         | 8.33%   |
| 12     | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 76.67%  |
| 1      | 14        | 23.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 60        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 14.52%  |
| 0x806e9    | 5         | 8.06%   |
| 0x206a7    | 5         | 8.06%   |
| 0x306d4    | 4         | 6.45%   |
| 0xa0652    | 3         | 4.84%   |
| 0x906e9    | 3         | 4.84%   |
| 0x806ec    | 3         | 4.84%   |
| 0x706e5    | 3         | 4.84%   |
| 0x08600106 | 3         | 4.84%   |
| 0x806ea    | 2         | 3.23%   |
| 0x806c1    | 2         | 3.23%   |
| 0x706a1    | 2         | 3.23%   |
| 0x40651    | 2         | 3.23%   |
| 0x306a9    | 2         | 3.23%   |
| 0x1067a    | 2         | 3.23%   |
| 0x906ed    | 1         | 1.61%   |
| 0x906ea    | 1         | 1.61%   |
| 0x506c9    | 1         | 1.61%   |
| 0x406e3    | 1         | 1.61%   |
| 0x306c3    | 1         | 1.61%   |
| 0x30678    | 1         | 1.61%   |
| 0x20655    | 1         | 1.61%   |
| 0x08701013 | 1         | 1.61%   |
| 0x08600103 | 1         | 1.61%   |
| 0x0810100b | 1         | 1.61%   |
| 0x08101007 | 1         | 1.61%   |
| 0x08001137 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 30%     |
| Zen 2         | 6         | 10%     |
| SandyBridge   | 5         | 8.33%   |
| Broadwell     | 5         | 8.33%   |
| Haswell       | 4         | 6.67%   |
| CometLake     | 4         | 6.67%   |
| Zen           | 3         | 5%      |
| IceLake       | 3         | 5%      |
| TigerLake     | 2         | 3.33%   |
| Penryn        | 2         | 3.33%   |
| IvyBridge     | 2         | 3.33%   |
| Goldmont plus | 2         | 3.33%   |
| Westmere      | 1         | 1.67%   |
| Skylake       | 1         | 1.67%   |
| Silvermont    | 1         | 1.67%   |
| Goldmont      | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 61.04%  |
| Nvidia | 17        | 22.08%  |
| AMD    | 13        | 16.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                         | 6         | 7.79%   |
| AMD Renoir                                                                    | 5         | 6.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 5.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 5.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 3.9%    |
| Intel HD Graphics 5500                                                        | 3         | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 3.9%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 2         | 2.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.6%    |
| Intel UHD Graphics 620                                                        | 2         | 2.6%    |
| Intel UHD Graphics 615                                                        | 2         | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.6%    |
| Intel HD Graphics 630                                                         | 2         | 2.6%    |
| Intel HD Graphics 6000                                                        | 2         | 2.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.3%    |
| Nvidia TU117M                                                                 | 1         | 1.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.3%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 1         | 1.3%    |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 1.3%    |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 1.3%    |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.3%    |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 1.3%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 1.3%    |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.3%    |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 1.3%    |
| Nvidia GF108M [GeForce GT 520M]                                               | 1         | 1.3%    |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.3%    |
| Intel HD Graphics P630                                                        | 1         | 1.3%    |
| Intel HD Graphics 500                                                         | 1         | 1.3%    |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.3%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.3%    |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 1         | 1.3%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.3%    |
| AMD Saturn XT [FirePro M6100]                                                 | 1         | 1.3%    |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 1.3%    |
| AMD Lexa XT [Radeon PRO WX 3100]                                              | 1         | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 50.82%  |
| Intel + Nvidia | 13        | 21.31%  |
| 1 x AMD        | 10        | 16.39%  |
| 1 x Nvidia     | 3         | 4.92%   |
| Intel + AMD    | 3         | 4.92%   |
| AMD + Nvidia   | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 50        | 83.33%  |
| Proprietary | 10        | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 67.21%  |
| 0.01-0.5   | 6         | 9.84%   |
| 1.01-2.0   | 5         | 8.2%    |
| 0.51-1.0   | 4         | 6.56%   |
| 3.01-4.0   | 3         | 4.92%   |
| 7.01-8.0   | 1         | 1.64%   |
| 2.01-3.0   | 1         | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 13        | 19.4%   |
| LG Display              | 10        | 14.93%  |
| Chimei Innolux          | 10        | 14.93%  |
| AU Optronics            | 8         | 11.94%  |
| Samsung Electronics     | 6         | 8.96%   |
| Apple                   | 3         | 4.48%   |
| Sharp                   | 2         | 2.99%   |
| Dell                    | 2         | 2.99%   |
| Chi Mei Optoelectronics | 2         | 2.99%   |
| ASUSTek Computer        | 2         | 2.99%   |
| Philips                 | 1         | 1.49%   |
| PANDA                   | 1         | 1.49%   |
| MSI                     | 1         | 1.49%   |
| LGD                     | 1         | 1.49%   |
| Lenovo                  | 1         | 1.49%   |
| InfoVision              | 1         | 1.49%   |
| Hewlett-Packard         | 1         | 1.49%   |
| Goldstar                | 1         | 1.49%   |
| Ancor Communications    | 1         | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 4.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 2.99%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 2.99%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 2.99%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 2.99%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 2.99%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 2.99%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 1.49%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 1.49%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 1.49%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 1.49%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 1.49%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                   | 1         | 1.49%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 1.49%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 1.49%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch               | 1         | 1.49%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 1.49%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                  | 1         | 1.49%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 1         | 1.49%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 1         | 1.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.49%   |
| Dell P2720DC DELD0FB 2560x1440 597x336mm 27.0-inch                        | 1         | 1.49%   |
| Dell E2310H DELD033 1920x1080 510x287mm 23.0-inch                         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 340x190mm 15.3-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.49%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                      | 1         | 1.49%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE0754 1366x768 256x144mm 11.6-inch                      | 1         | 1.49%   |
| BOE LCD Monitor BOE0618 1366x768 277x156mm 12.5-inch                      | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch             | 1         | 1.49%   |
| ASUSTek Computer VZ279HE AUS27C0 1920x1080 598x336mm 27.0-inch            | 1         | 1.49%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch              | 1         | 1.49%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                     | 1         | 1.49%   |
| Ancor Communications ASUS VS208 ACI20D9 1600x900 443x249mm 20.0-inch      | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 45.45%  |
| 1366x768 (WXGA)    | 21        | 31.82%  |
| 3840x2160 (4K)     | 3         | 4.55%   |
| 2560x1440 (QHD)    | 3         | 4.55%   |
| 1440x900 (WXGA+)   | 3         | 4.55%   |
| 1600x900 (HD+)     | 2         | 3.03%   |
| 3440x1440          | 1         | 1.52%   |
| 2560x1600          | 1         | 1.52%   |
| 1920x1200 (WUXGA)  | 1         | 1.52%   |
| 1680x1050 (WSXGA+) | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 32        | 48.48%  |
| 13      | 11        | 16.67%  |
| 14      | 6         | 9.09%   |
| 17      | 5         | 7.58%   |
| 27      | 3         | 4.55%   |
| 24      | 2         | 3.03%   |
| 34      | 1         | 1.52%   |
| 23      | 1         | 1.52%   |
| 21      | 1         | 1.52%   |
| 20      | 1         | 1.52%   |
| 12      | 1         | 1.52%   |
| 11      | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 63.64%  |
| 351-400     | 7         | 10.61%  |
| 201-300     | 7         | 10.61%  |
| 501-600     | 5         | 7.58%   |
| 401-500     | 2         | 3.03%   |
| 701-800     | 1         | 1.52%   |
| 601-700     | 1         | 1.52%   |
| Unknown     | 1         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 86.44%  |
| 16/10   | 6         | 10.17%  |
| 21/9    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 48.48%  |
| 81-90          | 12        | 18.18%  |
| 71-80          | 5         | 7.58%   |
| 121-130        | 4         | 6.06%   |
| 301-350        | 3         | 4.55%   |
| 201-250        | 3         | 4.55%   |
| 61-70          | 1         | 1.52%   |
| 51-60          | 1         | 1.52%   |
| 351-500        | 1         | 1.52%   |
| 251-300        | 1         | 1.52%   |
| 151-200        | 1         | 1.52%   |
| 131-140        | 1         | 1.52%   |
| Unknown        | 1         | 1.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 50%     |
| 101-120       | 19        | 29.69%  |
| 51-100        | 8         | 12.5%   |
| 161-240       | 3         | 4.69%   |
| More than 240 | 1         | 1.56%   |
| Unknown       | 1         | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 86.89%  |
| 2     | 8         | 13.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 39.58%  |
| Intel                 | 31        | 32.29%  |
| Qualcomm Atheros      | 12        | 12.5%   |
| Broadcom              | 6         | 6.25%   |
| Broadcom Limited      | 3         | 3.13%   |
| Ralink                | 2         | 2.08%   |
| Sierra Wireless       | 1         | 1.04%   |
| Ralink Technology     | 1         | 1.04%   |
| Linksys               | 1         | 1.04%   |
| Huawei Technologies   | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 23.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 4.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.54%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.54%   |
| Intel Wireless 7265                                               | 4         | 3.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 3.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.65%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.77%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.77%   |
| Sierra Wireless MC7700                                            | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.88%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.88%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.88%   |
| Intel Wireless-AC 9260                                            | 1         | 0.88%   |
| Intel Wireless 3165                                               | 1         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.88%   |
| Huawei E353/E3131                                                 | 1         | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 46.03%  |
| Realtek Semiconductor | 12        | 19.05%  |
| Qualcomm Atheros      | 10        | 15.87%  |
| Broadcom              | 5         | 7.94%   |
| Broadcom Limited      | 3         | 4.76%   |
| Ralink                | 2         | 3.17%   |
| Sierra Wireless       | 1         | 1.59%   |
| Ralink Technology     | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 7.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.35%   |
| Intel Wireless 8265 / 8275                                     | 4         | 6.35%   |
| Intel Wireless 7265                                            | 4         | 6.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 6.35%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 4.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.17%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.17%   |
| Sierra Wireless MC7700                                         | 1         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.59%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.59%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.59%   |
| Intel Wireless-AC 9260                                         | 1         | 1.59%   |
| Intel Wireless 3165                                            | 1         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.59%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 70%     |
| Intel                 | 10        | 20%     |
| Qualcomm Atheros      | 2         | 4%      |
| Linksys               | 1         | 2%      |
| Huawei Technologies   | 1         | 2%      |
| Broadcom              | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 52%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 12%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6%      |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 4%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2%      |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Huawei E353/E3131                                                 | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 55.66%  |
| Ethernet | 47        | 44.34%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 71.64%  |
| Ethernet | 19        | 28.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 70.49%  |
| 1     | 16        | 26.23%  |
| 3     | 2         | 3.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 87.1%   |
| Yes  | 8         | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 50%     |
| Realtek Semiconductor           | 8         | 16%     |
| Lite-On Technology              | 3         | 6%      |
| Broadcom                        | 3         | 6%      |
| Apple                           | 3         | 6%      |
| Realtek                         | 2         | 4%      |
| Qualcomm Atheros Communications | 2         | 4%      |
| Ralink                          | 1         | 2%      |
| IMC Networks                    | 1         | 2%      |
| Foxconn / Hon Hai               | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 18%     |
| Intel AX201 Bluetooth                               | 8         | 16%     |
| Realtek Bluetooth Radio                             | 4         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Intel AX200 Bluetooth                               | 3         | 6%      |
| Realtek Bluetooth Radio                             | 2         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4%      |
| Apple Bluetooth USB Host Controller                 | 2         | 4%      |
| Realtek RTL8821A Bluetooth                          | 1         | 2%      |
| Ralink RT3290 Bluetooth                             | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2%      |
| IMC Networks Bluetooth Device                       | 1         | 2%      |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2%      |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2%      |
| Apple Bluetooth Host Controller                     | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 65.79%  |
| Nvidia                | 10        | 13.16%  |
| AMD                   | 10        | 13.16%  |
| Realtek Semiconductor | 2         | 2.63%   |
| C-Media Electronics   | 2         | 2.63%   |
| Plantronics           | 1         | 1.32%   |
| Corsair               | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 11.58%  |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 7         | 7.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 5.26%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 5.26%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 4.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.16%   |
| Intel CM238 HD Audio Controller                                            | 3         | 3.16%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.16%   |
| Realtek Semiconductor USB Audio                                            | 2         | 2.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.11%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.11%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.05%   |
| Intel USB PnP Sound Device                                                 | 1         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.05%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1         | 1.05%   |
| C-Media Electronics USB Audio Device                                       | 1         | 1.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.05%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1         | 1.05%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 1.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 36.67%  |
| SK Hynix            | 13        | 21.67%  |
| Micron Technology   | 6         | 10%     |
| Kingston            | 5         | 8.33%   |
| A-DATA Technology   | 3         | 5%      |
| Unknown             | 2         | 3.33%   |
| Ramaxel Technology  | 2         | 3.33%   |
| Unknown (ABCD)      | 1         | 1.67%   |
| Team                | 1         | 1.67%   |
| Smart Brazil        | 1         | 1.67%   |
| Silicon Power       | 1         | 1.67%   |
| Nanya Technology    | 1         | 1.67%   |
| Corsair             | 1         | 1.67%   |
| ASint Technology    | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 3.28%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 2         | 3.28%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 3.28%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 3.28%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 3.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.28%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.28%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.64%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 1.64%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 1.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.64%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK Hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.64%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.64%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                      | 1         | 1.64%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 1.64%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.64%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                       | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 1.64%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16384MB SODIMM DDR4 2400MT/s        | 1         | 1.64%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 1.64%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Kingston RAM 9905469-157.A01LF 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Kingston RAM 9905469-024.A00LF 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.64%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 1         | 1.64%   |
| ASint RAM C1RE5SR4HN1 2GB SODIMM SDRAM 4199MT/s                  | 1         | 1.64%   |
| A-DATA RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.64%   |
| A-DATA RAM AO1P21FC4R1-B2MS 4GB SODIMM DDR4 2133MT/s             | 1         | 1.64%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 54.9%   |
| DDR3    | 15        | 29.41%  |
| LPDDR4  | 3         | 5.88%   |
| SDRAM   | 2         | 3.92%   |
| LPDDR3  | 2         | 3.92%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 84.31%  |
| Row Of Chips | 6         | 11.76%  |
| DIMM         | 1         | 1.96%   |
| Unknown      | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 43.4%   |
| 8192  | 15        | 28.3%   |
| 16384 | 7         | 13.21%  |
| 2048  | 5         | 9.43%   |
| 32768 | 2         | 3.77%   |
| 1024  | 1         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 16        | 29.63%  |
| 3200  | 10        | 18.52%  |
| 2667  | 9         | 16.67%  |
| 2400  | 7         | 12.96%  |
| 4199  | 2         | 3.7%    |
| 2133  | 2         | 3.7%    |
| 1333  | 2         | 3.7%    |
| 4267  | 1         | 1.85%   |
| 3400  | 1         | 1.85%   |
| 3266  | 1         | 1.85%   |
| 2933  | 1         | 1.85%   |
| 1334  | 1         | 1.85%   |
| 1066  | 1         | 1.85%   |

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
| Chicony Electronics                    | 9         | 17.31%  |
| Realtek Semiconductor                  | 7         | 13.46%  |
| Quanta                                 | 6         | 11.54%  |
| Acer                                   | 5         | 9.62%   |
| Suyin                                  | 4         | 7.69%   |
| IMC Networks                           | 4         | 7.69%   |
| Syntek                                 | 3         | 5.77%   |
| Alcor Micro                            | 3         | 5.77%   |
| Silicon Motion                         | 2         | 3.85%   |
| Microdia                               | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 1.92%   |
| Luxvisions Innotech Limited            | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| LG Electronics                         | 1         | 1.92%   |
| Lenovo                                 | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 4         | 7.69%   |
| IMC Networks Integrated Camera                                 | 3         | 5.77%   |
| Chicony Integrated Camera                                      | 3         | 5.77%   |
| Chicony HD WebCam                                              | 3         | 5.77%   |
| Syntek EasyCamera                                              | 2         | 3.85%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 3.85%   |
| Quanta HP Webcam                                               | 2         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 3.85%   |
| Syntek Integrated Camera                                       | 1         | 1.92%   |
| Suyin USB Webcam                                               | 1         | 1.92%   |
| Suyin NEC HD WebCam                                            | 1         | 1.92%   |
| Suyin HP Webcam                                                | 1         | 1.92%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.92%   |
| Sunplus HD WebCam                                              | 1         | 1.92%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.92%   |
| Realtek Integrated Webcam                                      | 1         | 1.92%   |
| Realtek HD WebCam                                              | 1         | 1.92%   |
| Quanta VGA WebCam                                              | 1         | 1.92%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.92%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.92%   |
| Quanta HD User Facing                                          | 1         | 1.92%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.92%   |
| Microdia Integrated Webcam                                     | 1         | 1.92%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.92%   |
| Lite-On HP HD Camera                                           | 1         | 1.92%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.92%   |
| Lenovo UVC Camera                                              | 1         | 1.92%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.92%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.92%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.92%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.92%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.92%   |
| Acer Integrated Camera                                         | 1         | 1.92%   |
| Acer Integrated 5M Camera                                      | 1         | 1.92%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.92%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 50%     |
| Shenzhen Goodix Technology | 2         | 33.33%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 50%     |
| Shenzhen Goodix  FingerPrint Device               | 2         | 33.33%  |
| AuthenTec AES2810                                 | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 33.33%  |
| Broadcom 58200                                                               | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 42        | 67.74%  |
| 1     | 16        | 25.81%  |
| 2     | 4         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 24%     |
| Multimedia controller | 4         | 16%     |
| Graphics card         | 4         | 16%     |
| Net/wireless          | 3         | 12%     |
| Camera                | 3         | 12%     |
| Chipcard              | 2         | 8%      |
| Storage               | 1         | 4%      |
| Dvb card              | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

