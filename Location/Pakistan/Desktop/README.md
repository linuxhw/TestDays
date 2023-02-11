Linux in Pakistan - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

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

Total: 118

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | 0KRC95 A00                  | [bf9e573abf](https://linux-hardware.org/?probe=bf9e573abf) | Jan 25, 2023 |
| MSI      | Z590-A PRO                  | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| MSI      | Z590-A PRO                  | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| HP       | 304Ah                       | [6106d55390](https://linux-hardware.org/?probe=6106d55390) | Dec 26, 2022 |
| Gigabyte | Q87M-D2H                    | [0b6bf86b5e](https://linux-hardware.org/?probe=0b6bf86b5e) | Dec 10, 2022 |
| HP       | 198E                        | [9d22530b3c](https://linux-hardware.org/?probe=9d22530b3c) | Nov 25, 2022 |
| Dell     | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| Gigabyte | Q87M-D2H                    | [e7c7b6c8a7](https://linux-hardware.org/?probe=e7c7b6c8a7) | Nov 14, 2022 |
| Gigabyte | Q87M-D2H                    | [8224e059c6](https://linux-hardware.org/?probe=8224e059c6) | Nov 14, 2022 |
| Gigabyte | Q87M-D2H                    | [543c3778c3](https://linux-hardware.org/?probe=543c3778c3) | Nov 12, 2022 |
| Gigabyte | Q87M-D2H                    | [f73ba4186b](https://linux-hardware.org/?probe=f73ba4186b) | Nov 11, 2022 |
| Gigabyte | Q87M-D2H                    | [143dc1e811](https://linux-hardware.org/?probe=143dc1e811) | Nov 05, 2022 |
| ASUSTek  | Q87M-E                      | [79f94ede46](https://linux-hardware.org/?probe=79f94ede46) | Oct 11, 2022 |
| HP       | 18E7                        | [797aa81ce0](https://linux-hardware.org/?probe=797aa81ce0) | Oct 02, 2022 |
| HP       | 18E7                        | [69e4bb94f3](https://linux-hardware.org/?probe=69e4bb94f3) | Oct 02, 2022 |
| Lenovo   | ThinkStation D30 4223CC9    | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo   | ThinkStation D30 4223CC9    | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| Quanta   | 2ABB 101                    | [3d241d58b9](https://linux-hardware.org/?probe=3d241d58b9) | Jul 13, 2022 |
| Gigabyte | A520M S2H                   | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| ASUSTek  | TUF Gaming B550-PLUS WIF... | [44db6036ce](https://linux-hardware.org/?probe=44db6036ce) | Jul 08, 2022 |
| Gigabyte | A520M S2H                   | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| HP       | 339A                        | [a20191b759](https://linux-hardware.org/?probe=a20191b759) | Jun 23, 2022 |
| HP       | 18E7                        | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| ASUSTek  | STRIX B250H GAMING          | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| HP       | 1495                        | [9ec1730693](https://linux-hardware.org/?probe=9ec1730693) | May 11, 2022 |
| Lenovo   | SDK0E50510 WIN              | [07526b3b20](https://linux-hardware.org/?probe=07526b3b20) | May 10, 2022 |
| HP       | 3396                        | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP       | 3396                        | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| HP       | 3396                        | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| HP       | 87D6 SMVB                   | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| HP       | 87D6 SMVB                   | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Dell     | 0HR330                      | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Gigabyte | A520M S2H                   | [06db14c491](https://linux-hardware.org/?probe=06db14c491) | Mar 01, 2022 |
| Dell     | 0HR330                      | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| Dell     | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell     | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP       | 8717                        | [d5d2ee0ab5](https://linux-hardware.org/?probe=d5d2ee0ab5) | Feb 18, 2022 |
| HP       | 8061                        | [f721051d60](https://linux-hardware.org/?probe=f721051d60) | Feb 11, 2022 |
| HP       | 8717                        | [97d99714a1](https://linux-hardware.org/?probe=97d99714a1) | Feb 10, 2022 |
| Dell     | 0DR845                      | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| HP       | 0B3Ch HP P/N                | [2805378159](https://linux-hardware.org/?probe=2805378159) | Dec 10, 2021 |
| Lenovo   | ThinkStation D30 4223CC9    | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| Dell     | 0VHRW1 A03                  | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo   | ThinkStation D30 4223CC9    | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Dell     | 0VHRW1 A03                  | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Lenovo   | ThinkStation D30 4223CC9    | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell     | 0VHRW1 A03                  | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Dell     | 06FW8P A02                  | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Shuttle  | FS81                        | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| Shuttle  | FS81                        | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| HP       | 0AECh D                     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| Dell     | 06FW8P A02                  | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Dell     | 06FW8P A02                  | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| ASUSTek  | PRIME B550-PLUS             | [98ddca21d9](https://linux-hardware.org/?probe=98ddca21d9) | Nov 06, 2021 |
| HP       | 0AECh D                     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Dell     | 06FW8P A02                  | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| Dell     | 0XPDFK A01                  | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| HP       | 0AECh D                     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Dell     | 06FW8P A02                  | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Dell     | 06FW8P A02                  | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| HP       | 0AECh D                     | [202ada3fc3](https://linux-hardware.org/?probe=202ada3fc3) | Sep 23, 2021 |
| HP       | 3047h                       | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| HP       | 1587h                       | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Unknown  | Unknown                     | [321a93dff9](https://linux-hardware.org/?probe=321a93dff9) | Sep 07, 2021 |
| Shuttle  | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Dell     | 09KPNV A01                  | [7e939d9f5f](https://linux-hardware.org/?probe=7e939d9f5f) | Aug 20, 2021 |
| Lenovo   | MAHOBAY NOK                 | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| Gigabyte | Z590 UD AC                  | [7e8e35538a](https://linux-hardware.org/?probe=7e8e35538a) | Jul 26, 2021 |
| Lenovo   | MAHOBAY NOK                 | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo   | MAHOBAY NOK                 | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Gigabyte | Z590 UD AC                  | [4fc5079d7e](https://linux-hardware.org/?probe=4fc5079d7e) | Jul 20, 2021 |
| Lenovo   | ThinkCentre M70e 0830F2U    | [8dad962f2f](https://linux-hardware.org/?probe=8dad962f2f) | Jul 09, 2021 |
| HP       | 158A                        | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| Dell     | 042P49 A00                  | [2d9b300bd3](https://linux-hardware.org/?probe=2d9b300bd3) | May 13, 2021 |
| Lenovo   | MAHOBAY NOK                 | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell     | 06FW8P A01                  | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| Lenovo   | MAHOBAY NOK                 | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| Dell     | 0VHRW1 A03                  | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo   | ThinkStation D30 4223CC9    | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell     | 06FW8P A02                  | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell     | 06FW8P A01                  | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle  | FS81                        | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Dell     | 0GU083 A00                  | [03e87a4ada](https://linux-hardware.org/?probe=03e87a4ada) | Mar 20, 2021 |
| Dell     | 0C27VV A01                  | [2ab353f0c6](https://linux-hardware.org/?probe=2ab353f0c6) | Mar 06, 2021 |
| Lenovo   | MAHOBAY NOK                 | [67ea005277](https://linux-hardware.org/?probe=67ea005277) | Feb 24, 2021 |
| Lenovo   | MAHOBAY 31900003 STD        | [845f5a30c2](https://linux-hardware.org/?probe=845f5a30c2) | Feb 13, 2021 |
| Lenovo   | ThinkCentre M58 7373C51     | [3e79476403](https://linux-hardware.org/?probe=3e79476403) | Jan 27, 2021 |
| HP       | 3047h                       | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| HP       | 3047h                       | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Dell     | 07N90W A01                  | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| HP       | 8433 11                     | [1d000792d8](https://linux-hardware.org/?probe=1d000792d8) | Sep 03, 2020 |
| Dell     | 0D6H9T A01                  | [1f914ddd57](https://linux-hardware.org/?probe=1f914ddd57) | Aug 31, 2020 |
| Dell     | 0HY9JP A02                  | [19795140c8](https://linux-hardware.org/?probe=19795140c8) | Aug 22, 2020 |
| Dell     | 0HY9JP A02                  | [b739a3410a](https://linux-hardware.org/?probe=b739a3410a) | Aug 22, 2020 |
| Dell     | 0PP150 A00                  | [a990cf0ce7](https://linux-hardware.org/?probe=a990cf0ce7) | Aug 21, 2020 |
| HP       | 0B4Ch D                     | [4053256264](https://linux-hardware.org/?probe=4053256264) | Aug 10, 2020 |
| Dell     | 0DR845                      | [e4ff6acb83](https://linux-hardware.org/?probe=e4ff6acb83) | Aug 01, 2020 |
| Dell     | 0DR845                      | [4b9fbd7a8f](https://linux-hardware.org/?probe=4b9fbd7a8f) | Aug 01, 2020 |
| HP       | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Gigabyte | B450M S2H                   | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| Gigabyte | B250M-D3H-CF                | [f74cf1545a](https://linux-hardware.org/?probe=f74cf1545a) | May 21, 2020 |
| Dell     | 0GU083 A00                  | [a31c9c5f4f](https://linux-hardware.org/?probe=a31c9c5f4f) | May 05, 2020 |
| Gigabyte | Z170X-Gaming 7              | [e3400fb2b7](https://linux-hardware.org/?probe=e3400fb2b7) | May 04, 2020 |
| Dell     | 0PP150 A00                  | [51f69f1430](https://linux-hardware.org/?probe=51f69f1430) | May 02, 2020 |
| Lenovo   | ThinkCentre M57 6072W2A     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Lenovo   | ThinkCentre M57 6072W2A     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| Dell     | 0PP150 A00                  | [f224ee60e5](https://linux-hardware.org/?probe=f224ee60e5) | Apr 30, 2020 |
| Dell     | 0XPDFK A01                  | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| Dell     | 0XPDFK A01                  | [4a53b5e634](https://linux-hardware.org/?probe=4a53b5e634) | Mar 11, 2020 |
| Dell     | 054KM3 A01                  | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP       | 1497                        | [fe24ec7591](https://linux-hardware.org/?probe=fe24ec7591) | Jan 28, 2020 |
| Dell     | 054KM3 A01                  | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| Acer     | Veriton X6620G v1.0         | [e921d3af77](https://linux-hardware.org/?probe=e921d3af77) | Dec 13, 2019 |
| ASUSTek  | Q87M-E                      | [01f990ea56](https://linux-hardware.org/?probe=01f990ea56) | Oct 19, 2019 |
| HP       | 304Ah                       | [4f72bfd1f5](https://linux-hardware.org/?probe=4f72bfd1f5) | May 13, 2019 |
| Dell     | 054KM3 A01                  | [144815a4e9](https://linux-hardware.org/?probe=144815a4e9) | Jan 15, 2019 |
| Dell     | 054KM3 A01                  | [f83bcddf2e](https://linux-hardware.org/?probe=f83bcddf2e) | Jan 08, 2019 |
| Dell     | 054KM3 A01                  | [404e699144](https://linux-hardware.org/?probe=404e699144) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 12       | 14.81%  |
| Ubuntu 22.04       | 6        | 7.41%   |
| Debian 11          | 6        | 7.41%   |
| Debian 10          | 6        | 7.41%   |
| Ubuntu 18.04       | 4        | 4.94%   |
| OpenMandriva 4.3   | 4        | 4.94%   |
| Zorin 15           | 3        | 3.7%    |
| Ubuntu 21.04       | 3        | 3.7%    |
| Arch               | 3        | 3.7%    |
| Ubuntu 20.10       | 2        | 2.47%   |
| Pop!_OS 20.04      | 2        | 2.47%   |
| OpenMandriva 4.2   | 2        | 2.47%   |
| Manjaro            | 2        | 2.47%   |
| Linux Mint 19.3    | 2        | 2.47%   |
| Fedora 34          | 2        | 2.47%   |
| ArcoLinux Rolling  | 2        | 2.47%   |
| Zorin 16           | 1        | 1.23%   |
| Ubuntu MATE 18.04  | 1        | 1.23%   |
| ROSA 12.2          | 1        | 1.23%   |
| Pop!_OS 21.04      | 1        | 1.23%   |
| Parrot 4.10        | 1        | 1.23%   |
| OpenMandriva 23.01 | 1        | 1.23%   |
| LMDE 4             | 1        | 1.23%   |
| Linux Mint 20.3    | 1        | 1.23%   |
| Linux Mint 20.2    | 1        | 1.23%   |
| Linux Mint 19.2    | 1        | 1.23%   |
| Kubuntu 21.10      | 1        | 1.23%   |
| Kubuntu 20.04      | 1        | 1.23%   |
| KDE neon 20.04     | 1        | 1.23%   |
| Kali 2022.2        | 1        | 1.23%   |
| Kali 2022.1        | 1        | 1.23%   |
| Fedora 36          | 1        | 1.23%   |
| Fedora 32          | 1        | 1.23%   |
| CentOS 7           | 1        | 1.23%   |
| BlackPanther 18.1  | 1        | 1.23%   |
| Alpine 3.11.2      | 1        | 1.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 26       | 33.77%  |
| Debian       | 9        | 11.69%  |
| OpenMandriva | 7        | 9.09%   |
| Linux Mint   | 5        | 6.49%   |
| Zorin        | 4        | 5.19%   |
| Fedora       | 4        | 5.19%   |
| Pop!_OS      | 3        | 3.9%    |
| Arch         | 3        | 3.9%    |
| Manjaro      | 2        | 2.6%    |
| Kubuntu      | 2        | 2.6%    |
| Kali         | 2        | 2.6%    |
| ArcoLinux    | 2        | 2.6%    |
| Ubuntu MATE  | 1        | 1.3%    |
| ROSA         | 1        | 1.3%    |
| Parrot       | 1        | 1.3%    |
| LMDE         | 1        | 1.3%    |
| KDE neon     | 1        | 1.3%    |
| CentOS       | 1        | 1.3%    |
| BlackPanther | 1        | 1.3%    |
| Alpine       | 1        | 1.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.106-1-pve            | 5        | 5.95%   |
| 5.16.7-desktop-1omv4003  | 4        | 4.76%   |
| 5.15.0-53-generic        | 3        | 3.57%   |
| 5.8.0-44-generic         | 2        | 2.38%   |
| 5.4.0-7642-generic       | 2        | 2.38%   |
| 5.4.0-28-generic         | 2        | 2.38%   |
| 5.13.19-1-pve            | 2        | 2.38%   |
| 5.13.0-40-generic        | 2        | 2.38%   |
| 5.10.14-desktop-1omv4002 | 2        | 2.38%   |
| 5.0.0-32-generic         | 2        | 2.38%   |
| 6.1.1-desktop-1omv2290   | 1        | 1.19%   |
| 6.1.1-arch1-1            | 1        | 1.19%   |
| 5.8.3-2-MANJARO          | 1        | 1.19%   |
| 5.8.0-63-generic         | 1        | 1.19%   |
| 5.8.0-59-generic         | 1        | 1.19%   |
| 5.8.0-43-generic         | 1        | 1.19%   |
| 5.8.0-40-generic         | 1        | 1.19%   |
| 5.7.10-201.fc32.x86_64   | 1        | 1.19%   |
| 5.7.0-2parrot2-amd64     | 1        | 1.19%   |
| 5.4.41-1-pve             | 1        | 1.19%   |
| 5.4.36-1-MANJARO         | 1        | 1.19%   |
| 5.4.0-88-generic         | 1        | 1.19%   |
| 5.4.0-52-generic         | 1        | 1.19%   |
| 5.4.0-42-generic         | 1        | 1.19%   |
| 5.4.0-26-generic         | 1        | 1.19%   |
| 5.4.0-109-generic        | 1        | 1.19%   |
| 5.4.0-100-generic        | 1        | 1.19%   |
| 5.3.7-arch1-1-ARCH       | 1        | 1.19%   |
| 5.19.13-arch1-1          | 1        | 1.19%   |
| 5.18.9-200.fc36.x86_64   | 1        | 1.19%   |
| 5.18.0-kali2-amd64       | 1        | 1.19%   |
| 5.16.15-arch1-1          | 1        | 1.19%   |
| 5.15.39-4-pve            | 1        | 1.19%   |
| 5.15.0-kali3-amd64       | 1        | 1.19%   |
| 5.15.0-56-generic        | 1        | 1.19%   |
| 5.15.0-52-generic        | 1        | 1.19%   |
| 5.15.0-48-generic        | 1        | 1.19%   |
| 5.15.0-41-generic        | 1        | 1.19%   |
| 5.15.0-39-generic        | 1        | 1.19%   |
| 5.15.0-33-generic        | 1        | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 10       | 12.2%   |
| 5.15.0   | 9        | 10.98%  |
| 5.11.0   | 7        | 8.54%   |
| 5.8.0    | 6        | 7.32%   |
| 5.4.106  | 5        | 6.1%    |
| 5.16.7   | 4        | 4.88%   |
| 5.11.22  | 4        | 4.88%   |
| 5.0.0    | 4        | 4.88%   |
| 5.13.0   | 3        | 3.66%   |
| 4.15.0   | 3        | 3.66%   |
| 6.1.1    | 2        | 2.44%   |
| 5.13.19  | 2        | 2.44%   |
| 5.10.14  | 2        | 2.44%   |
| 4.18.0   | 2        | 2.44%   |
| 5.8.3    | 1        | 1.22%   |
| 5.7.10   | 1        | 1.22%   |
| 5.7.0    | 1        | 1.22%   |
| 5.4.41   | 1        | 1.22%   |
| 5.4.36   | 1        | 1.22%   |
| 5.3.7    | 1        | 1.22%   |
| 5.19.13  | 1        | 1.22%   |
| 5.18.9   | 1        | 1.22%   |
| 5.18.0   | 1        | 1.22%   |
| 5.16.15  | 1        | 1.22%   |
| 5.15.39  | 1        | 1.22%   |
| 5.13.4   | 1        | 1.22%   |
| 5.13.14  | 1        | 1.22%   |
| 5.10.74  | 1        | 1.22%   |
| 5.10.61  | 1        | 1.22%   |
| 4.19.0   | 1        | 1.22%   |
| 4.18.16  | 1        | 1.22%   |
| 3.10.105 | 1        | 1.22%   |
| 3.10.0   | 1        | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 17       | 20.73%  |
| 5.11    | 11       | 13.41%  |
| 5.15    | 10       | 12.2%   |
| 5.8     | 7        | 8.54%   |
| 5.13    | 7        | 8.54%   |
| 5.16    | 5        | 6.1%    |
| 5.10    | 4        | 4.88%   |
| 5.0     | 4        | 4.88%   |
| 4.18    | 3        | 3.66%   |
| 4.15    | 3        | 3.66%   |
| 6.1     | 2        | 2.44%   |
| 5.7     | 2        | 2.44%   |
| 5.18    | 2        | 2.44%   |
| 3.10    | 2        | 2.44%   |
| 5.3     | 1        | 1.22%   |
| 5.19    | 1        | 1.22%   |
| 4.19    | 1        | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 72       | 98.63%  |
| i686   | 1        | 1.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 37       | 48.68%  |
| Unknown    | 15       | 19.74%  |
| KDE5       | 11       | 14.47%  |
| X-Cinnamon | 4        | 5.26%   |
| MATE       | 4        | 5.26%   |
| KDE        | 2        | 2.63%   |
| i3         | 2        | 2.63%   |
| KDE4       | 1        | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 53       | 70.67%  |
| Wayland | 9        | 12%     |
| Tty     | 7        | 9.33%   |
| Unknown | 6        | 8%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 42       | 56.76%  |
| SDDM    | 12       | 16.22%  |
| GDM3    | 12       | 16.22%  |
| GDM     | 5        | 6.76%   |
| LightDM | 2        | 2.7%    |
| TDM     | 1        | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 62       | 83.78%  |
| en_GB   | 6        | 8.11%   |
| Unknown | 5        | 6.76%   |
| en_PK   | 1        | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 54       | 71.05%  |
| EFI  | 22       | 28.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 59       | 74.68%  |
| Overlay | 7        | 8.86%   |
| Zfs     | 6        | 7.59%   |
| Btrfs   | 5        | 6.33%   |
| Xfs     | 1        | 1.27%   |
| Unknown | 1        | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 54.05%  |
| GPT     | 26       | 35.14%  |
| MBR     | 8        | 10.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 80.52%  |
| Yes       | 15       | 19.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 60.53%  |
| Yes       | 30       | 39.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 24       | 32.88%  |
| Hewlett-Packard     | 22       | 30.14%  |
| Gigabyte Technology | 9        | 12.33%  |
| Lenovo              | 7        | 9.59%   |
| ASUSTek Computer    | 5        | 6.85%   |
| Shuttle             | 2        | 2.74%   |
| Quanta              | 1        | 1.37%   |
| MSI                 | 1        | 1.37%   |
| Acer                | 1        | 1.37%   |
| Unknown             | 1        | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell Precision WorkStation T7500           | 4        | 5.48%   |
| Dell Precision WorkStation T3500           | 3        | 4.11%   |
| Shuttle DS81D                              | 2        | 2.74%   |
| HP ProDesk 600 G1 SFF                      | 2        | 2.74%   |
| HP ProDesk 400 G7 Microtower PC            | 2        | 2.74%   |
| HP Compaq 8100 Elite SFF PC                | 2        | 2.74%   |
| Gigabyte Z590 UD AC                        | 2        | 2.74%   |
| Gigabyte Q87M-D2H                          | 2        | 2.74%   |
| Gigabyte A520M S2H                         | 2        | 2.74%   |
| Dell XPS 630i                              | 2        | 2.74%   |
| Dell Vostro 430                            | 2        | 2.74%   |
| Dell Precision WorkStation 490             | 2        | 2.74%   |
| Dell OptiPlex 755                          | 2        | 2.74%   |
| Quanta TouchSmart 9300 Elite All-in-One PC | 1        | 1.37%   |
| MSI MS-7D09                                | 1        | 1.37%   |
| Lenovo ThinkStation D30 4223CC9            | 1        | 1.37%   |
| Lenovo ThinkCentre M93z 10ACS12B00         | 1        | 1.37%   |
| Lenovo ThinkCentre M82 27423K1             | 1        | 1.37%   |
| Lenovo ThinkCentre M70e 0830F2U            | 1        | 1.37%   |
| Lenovo ThinkCentre M58 7373C51             | 1        | 1.37%   |
| Lenovo ThinkCentre M57 6072W2A             | 1        | 1.37%   |
| Lenovo H520 10094                          | 1        | 1.37%   |
| HP Z800 Workstation                        | 1        | 1.37%   |
| HP Z620 Workstation                        | 1        | 1.37%   |
| HP Z420 Workstation                        | 1        | 1.37%   |
| HP Z400 Workstation                        | 1        | 1.37%   |
| HP Z210 Workstation                        | 1        | 1.37%   |
| HP ProDesk 400 G3 MT                       | 1        | 1.37%   |
| HP ProDesk 400 G2 MT (TPM DP)              | 1        | 1.37%   |
| HP Pavilion Gaming Desktop TG01-1xxx       | 1        | 1.37%   |
| HP Pavilion Desktop 590-p0xxx              | 1        | 1.37%   |
| HP Compaq Pro 6300 SFF                     | 1        | 1.37%   |
| HP Compaq Elite 8300 CMT                   | 1        | 1.37%   |
| HP Compaq dx7510 MT                        | 1        | 1.37%   |
| HP Compaq 8200 Elite MT PC                 | 1        | 1.37%   |
| HP Compaq 6200 Pro MT PC                   | 1        | 1.37%   |
| HP Compaq 6005 Pro SFF PC                  | 1        | 1.37%   |
| HP Compaq 6005 Pro MT PC                   | 1        | 1.37%   |
| Gigabyte Z170X-Gaming 7                    | 1        | 1.37%   |
| Gigabyte B450M S2H                         | 1        | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell Precision        | 10       | 13.7%   |
| HP Compaq             | 9        | 12.33%  |
| Dell OptiPlex         | 9        | 12.33%  |
| HP ProDesk            | 6        | 8.22%   |
| Lenovo ThinkCentre    | 5        | 6.85%   |
| Dell Vostro           | 3        | 4.11%   |
| Shuttle DS81D         | 2        | 2.74%   |
| HP Pavilion           | 2        | 2.74%   |
| Gigabyte Z590         | 2        | 2.74%   |
| Gigabyte Q87M-D2H     | 2        | 2.74%   |
| Gigabyte A520M        | 2        | 2.74%   |
| Dell XPS              | 2        | 2.74%   |
| Quanta TouchSmart     | 1        | 1.37%   |
| MSI MS-7D09           | 1        | 1.37%   |
| Lenovo ThinkStation   | 1        | 1.37%   |
| Lenovo H520           | 1        | 1.37%   |
| HP Z800               | 1        | 1.37%   |
| HP Z620               | 1        | 1.37%   |
| HP Z420               | 1        | 1.37%   |
| HP Z400               | 1        | 1.37%   |
| HP Z210               | 1        | 1.37%   |
| Gigabyte Z170X-Gaming | 1        | 1.37%   |
| Gigabyte B450M        | 1        | 1.37%   |
| Gigabyte B250M-D3H    | 1        | 1.37%   |
| ASUS TUF              | 1        | 1.37%   |
| ASUS STRIX            | 1        | 1.37%   |
| ASUS Q87M-XA          | 1        | 1.37%   |
| ASUS PRIME            | 1        | 1.37%   |
| ASUS All              | 1        | 1.37%   |
| Acer Veriton          | 1        | 1.37%   |
| Unknown               | 1        | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2011    | 10       | 13.7%   |
| 2012    | 9        | 12.33%  |
| 2009    | 8        | 10.96%  |
| 2013    | 7        | 9.59%   |
| 2010    | 7        | 9.59%   |
| 2021    | 6        | 8.22%   |
| 2020    | 4        | 5.48%   |
| 2014    | 4        | 5.48%   |
| 2007    | 4        | 5.48%   |
| 2018    | 3        | 4.11%   |
| 2008    | 3        | 4.11%   |
| 2017    | 2        | 2.74%   |
| 2016    | 2        | 2.74%   |
| 2006    | 2        | 2.74%   |
| 2015    | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 73       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 73       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 15       | 20.27%  |
| 16.01-24.0      | 15       | 20.27%  |
| 4.01-8.0        | 14       | 18.92%  |
| 8.01-16.0       | 13       | 17.57%  |
| 32.01-64.0      | 7        | 9.46%   |
| 64.01-256.0     | 7        | 9.46%   |
| More than 256.0 | 1        | 1.35%   |
| 24.01-32.0      | 1        | 1.35%   |
| 1.01-2.0        | 1        | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 30       | 36.14%  |
| 2.01-3.0    | 23       | 27.71%  |
| 3.01-4.0    | 9        | 10.84%  |
| 4.01-8.0    | 8        | 9.64%   |
| 8.01-16.0   | 7        | 8.43%   |
| 16.01-24.0  | 2        | 2.41%   |
| 32.01-64.0  | 1        | 1.2%    |
| 64.01-256.0 | 1        | 1.2%    |
| 0.51-1.0    | 1        | 1.2%    |
| Unknown     | 1        | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 33.33%  |
| 2      | 25       | 30.86%  |
| 3      | 13       | 16.05%  |
| 6      | 5        | 6.17%   |
| 5      | 3        | 3.7%    |
| 4      | 3        | 3.7%    |
| 13     | 1        | 1.23%   |
| 11     | 1        | 1.23%   |
| 10     | 1        | 1.23%   |
| 9      | 1        | 1.23%   |
| 8      | 1        | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 54.79%  |
| Yes       | 33       | 45.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 73       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 52%     |
| No        | 36       | 48%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 72.73%  |
| Yes       | 21       | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Pakistan | 73       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Lahore         | 25       | 32.89%  |
| Karachi        | 16       | 21.05%  |
| Islamabad      | 13       | 17.11%  |
| Rawalpindi     | 3        | 3.95%   |
| Peshawar       | 2        | 2.63%   |
| Multan         | 2        | 2.63%   |
| Kamoke         | 2        | 2.63%   |
| Tando Allahyar | 1        | 1.32%   |
| Sialkot        | 1        | 1.32%   |
| Sheikhupura    | 1        | 1.32%   |
| Sargodha       | 1        | 1.32%   |
| Sahiwal        | 1        | 1.32%   |
| Mardan         | 1        | 1.32%   |
| Larkana        | 1        | 1.32%   |
| Jhelum         | 1        | 1.32%   |
| Hyderabad      | 1        | 1.32%   |
| Gujranwala     | 1        | 1.32%   |
| Faisalabad     | 1        | 1.32%   |
| Burewala       | 1        | 1.32%   |
| Abbottabad     | 1        | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 76     | 25.17%  |
| WDC                 | 28       | 44     | 18.54%  |
| Samsung Electronics | 18       | 22     | 11.92%  |
| Hitachi             | 11       | 16     | 7.28%   |
| Hewlett-Packard     | 6        | 17     | 3.97%   |
| Hajaan              | 6        | 9      | 3.97%   |
| LITEONIT            | 4        | 7      | 2.65%   |
| LITEON              | 4        | 5      | 2.65%   |
| Toshiba             | 3        | 3      | 1.99%   |
| SK hynix            | 3        | 3      | 1.99%   |
| Maxtor              | 3        | 3      | 1.99%   |
| Lexar               | 3        | 5      | 1.99%   |
| LaCie               | 3        | 3      | 1.99%   |
| HS-SSD-E100         | 3        | 3      | 1.99%   |
| Crucial             | 3        | 3      | 1.99%   |
| Intel               | 2        | 2      | 1.32%   |
| A-DATA Technology   | 2        | 2      | 1.32%   |
| ZTE                 | 1        | 1      | 0.66%   |
| Transcend           | 1        | 1      | 0.66%   |
| Silicon Motion      | 1        | 1      | 0.66%   |
| SanDisk             | 1        | 1      | 0.66%   |
| Micron Technology   | 1        | 2      | 0.66%   |
| MARSHAL             | 1        | 1      | 0.66%   |
| Kingston            | 1        | 1      | 0.66%   |
| KingFast            | 1        | 2      | 0.66%   |
| IBM-ESXS            | 1        | 3      | 0.66%   |
| HGST                | 1        | 1      | 0.66%   |
| Gigabyte Technology | 1        | 2      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seagate ST3000NXCLAR3000 3TB          | 7        | 3.8%    |
| HP MB2000EBZQC 2TB                    | 6        | 3.26%   |
| Hajaan SSD 256G                       | 6        | 3.26%   |
| Samsung SSD PM830 2.5 7mm 256GB       | 4        | 2.17%   |
| Seagate ST8000DM004-2CX188 8TB        | 3        | 1.63%   |
| Seagate ST6000NM0024 6TB              | 3        | 1.63%   |
| Seagate ST500DM002-1BD142 500GB       | 3        | 1.63%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 3        | 1.63%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB     | 3        | 1.63%   |
| Lexar 256GB SSD                       | 3        | 1.63%   |
| LaCie Rugged USB-C 1TB                | 3        | 1.63%   |
| HS-SSD-E100 128G                      | 3        | 1.63%   |
| WDC WD5002ABYS-02B1B0 500GB           | 2        | 1.09%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2        | 1.09%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 1.09%   |
| SK hynix SC300 M.2 2280 256GB SSD     | 2        | 1.09%   |
| Seagate ST3500414CS 500GB             | 2        | 1.09%   |
| Seagate ST3250318AS 249GB             | 2        | 1.09%   |
| Seagate ST2000VM003-1ET164 2TB        | 2        | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 1.09%   |
| Seagate ST2000DM008-2FR1              | 2        | 1.09%   |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 1.09%   |
| Samsung NVMe SSD Drive 500GB          | 2        | 1.09%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD  | 2        | 1.09%   |
| Maxtor STM380215AS 80GB               | 2        | 1.09%   |
| Hitachi HUA723020ALA640 2TB           | 2        | 1.09%   |
| HP MB2000GCWDA 2TB                    | 2        | 1.09%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 1.09%   |
| ZTE MMC Storage 942MB                 | 1        | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1        | 0.54%   |
| WDC WD800JD-60LUA0 80GB               | 1        | 0.54%   |
| WDC WD800JD-00LSA0 80GB               | 1        | 0.54%   |
| WDC WD800ADFS-75SLR2 80GB             | 1        | 0.54%   |
| WDC WD800AAJS-75M0A0 80GB             | 1        | 0.54%   |
| WDC WD800AAJS-60M0A0 80GB             | 1        | 0.54%   |
| WDC WD7500AACS-00D6B0 752GB           | 1        | 0.54%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 0.54%   |
| WDC WD5000AACS-61M6B2 500GB           | 1        | 0.54%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 76     | 41.3%   |
| WDC                 | 27       | 41     | 29.35%  |
| Hitachi             | 11       | 16     | 11.96%  |
| Hewlett-Packard     | 6        | 17     | 6.52%   |
| Samsung Electronics | 3        | 3      | 3.26%   |
| Maxtor              | 3        | 3      | 3.26%   |
| Toshiba             | 2        | 2      | 2.17%   |
| MARSHAL             | 1        | 1      | 1.09%   |
| HGST                | 1        | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 14     | 23.91%  |
| Hajaan              | 6        | 9      | 13.04%  |
| LITEONIT            | 4        | 7      | 8.7%    |
| LITEON              | 4        | 5      | 8.7%    |
| SK hynix            | 3        | 3      | 6.52%   |
| Lexar               | 3        | 5      | 6.52%   |
| Crucial             | 3        | 3      | 6.52%   |
| WDC                 | 2        | 3      | 4.35%   |
| Intel               | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| Transcend           | 1        | 1      | 2.17%   |
| Toshiba             | 1        | 1      | 2.17%   |
| SanDisk             | 1        | 1      | 2.17%   |
| Micron Technology   | 1        | 2      | 2.17%   |
| Kingston            | 1        | 1      | 2.17%   |
| Gigabyte Technology | 1        | 2      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 62       | 160    | 60.78%  |
| SSD     | 26       | 61     | 25.49%  |
| Unknown | 8        | 12     | 7.84%   |
| NVMe    | 6        | 6      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 69       | 209    | 81.18%  |
| SAS  | 10       | 24     | 11.76%  |
| NVMe | 6        | 6      | 7.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 59       | 130    | 57.28%  |
| 0.51-1.0   | 19       | 21     | 18.45%  |
| 1.01-2.0   | 12       | 36     | 11.65%  |
| 2.01-3.0   | 7        | 15     | 6.8%    |
| 4.01-10.0  | 4        | 17     | 3.88%   |
| 3.01-4.0   | 2        | 2      | 1.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 22.5%   |
| 51-100         | 14       | 17.5%   |
| 251-500        | 11       | 13.75%  |
| 21-50          | 7        | 8.75%   |
| 1001-2000      | 7        | 8.75%   |
| 1-20           | 7        | 8.75%   |
| 501-1000       | 7        | 8.75%   |
| Unknown        | 7        | 8.75%   |
| More than 3000 | 1        | 1.25%   |
| 2001-3000      | 1        | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 33       | 41.25%  |
| 21-50     | 12       | 15%     |
| 101-250   | 8        | 10%     |
| 251-500   | 7        | 8.75%   |
| 51-100    | 7        | 8.75%   |
| Unknown   | 7        | 8.75%   |
| 501-1000  | 5        | 6.25%   |
| 1001-2000 | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST2000DM008-2FR1          | 2        | 2      | 9.52%   |
| Hewlett-Packard MB2000EBZQC 2TB   | 2        | 3      | 9.52%   |
| Crucial CT525MX300SSD1 528GB      | 2        | 2      | 9.52%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1        | 1      | 4.76%   |
| WDC WD2500HHTZ-04N21V0 250GB      | 1        | 1      | 4.76%   |
| WDC WD2500AAKS-00F0A0 250GB       | 1        | 1      | 4.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 1      | 4.76%   |
| WDC WD1600AAJS-22L7A0 160GB       | 1        | 1      | 4.76%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 4.76%   |
| Seagate ST3160215AS 160GB         | 1        | 1      | 4.76%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 2      | 4.76%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 4.76%   |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 4.76%   |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 4.76%   |
| Intel SSDSA2M080G2GN 80GB         | 1        | 1      | 4.76%   |
| Hitachi HUA723020ALA640 2TB       | 1        | 2      | 4.76%   |
| Hitachi HDS721680PLA380 80GB      | 1        | 1      | 4.76%   |
| Hitachi HDS721050CLA660 500GB     | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 25%     |
| Seagate             | 5        | 7      | 25%     |
| Hitachi             | 3        | 4      | 15%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Hewlett-Packard     | 2        | 3      | 10%     |
| Crucial             | 2        | 2      | 10%     |
| Intel               | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 29.41%  |
| Seagate             | 5        | 7      | 29.41%  |
| Hitachi             | 3        | 4      | 17.65%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Hewlett-Packard     | 2        | 3      | 11.76%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 21     | 76.92%  |
| SSD  | 3        | 3      | 23.08%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 52       | 121    | 59.09%  |
| Works    | 24       | 94     | 27.27%  |
| Malfunc  | 12       | 24     | 13.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 62       | 68.89%  |
| AMD                       | 9        | 10%     |
| LSI Logic / Symbios Logic | 8        | 8.89%   |
| Samsung Electronics       | 5        | 5.56%   |
| Nvidia                    | 2        | 2.22%   |
| Silicon Motion            | 1        | 1.11%   |
| Broadcom / LSI            | 1        | 1.11%   |
| ASMedia Technology        | 1        | 1.11%   |
| Adaptec                   | 1        | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 7.75%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 8        | 6.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 5.43%   |
| Intel SATA Controller [RAID mode]                                              | 5        | 3.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5        | 3.88%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4        | 3.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 3.1%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 3.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 3.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 2.33%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 2.33%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 2.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 1.55%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2        | 1.55%   |
| Nvidia MCP51 IDE                                                               | 2        | 1.55%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 2        | 1.55%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                           | 2        | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.55%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 1.55%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2        | 1.55%   |
| Intel 82Q35 Express PT IDER Controller                                         | 2        | 1.55%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.55%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.55%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.55%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 2        | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.55%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                         | 2        | 1.55%   |
| Intel 631xESB/632xESB IDE Controller                                           | 2        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2        | 1.55%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.78%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.78%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                        | 1        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 54       | 50%     |
| IDE  | 21       | 19.44%  |
| RAID | 12       | 11.11%  |
| SCSI | 9        | 8.33%   |
| SAS  | 6        | 5.56%   |
| NVMe | 6        | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 87.67%  |
| AMD    | 9        | 12.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Xeon CPU X5650 @ 2.67GHz          | 5        | 6.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4        | 5.48%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 3        | 4.11%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3        | 4.11%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 2        | 2.74%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 2        | 2.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2        | 2.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 2.74%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2        | 2.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2        | 2.74%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 2        | 2.74%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 2.74%   |
| Intel Xeon CPU X5660 @ 2.80GHz          | 1        | 1.37%   |
| Intel Xeon CPU X5560 @ 2.80GHz          | 1        | 1.37%   |
| Intel Xeon CPU W3680 @ 3.33GHz          | 1        | 1.37%   |
| Intel Xeon CPU W3565 @ 3.20GHz          | 1        | 1.37%   |
| Intel Xeon CPU W3520 @ 2.67GHz          | 1        | 1.37%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 1.37%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz      | 1        | 1.37%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 1        | 1.37%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1        | 1.37%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz  | 1        | 1.37%   |
| Intel Pentium CPU G870 @ 3.10GHz        | 1        | 1.37%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 1.37%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1        | 1.37%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1        | 1.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 1.37%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 1.37%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1        | 1.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 1.37%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 1.37%   |
| Intel Core i5-4590S CPU @ 3.00GHz       | 1        | 1.37%   |
| Intel Core i5-4570T CPU @ 2.90GHz       | 1        | 1.37%   |
| Intel Core i5-2500S CPU @ 2.70GHz       | 1        | 1.37%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 1        | 1.37%   |
| Intel Core i5 CPU 760 @ 2.80GHz         | 1        | 1.37%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1        | 1.37%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 1        | 1.37%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 1        | 1.37%   |
| Intel Core i3 CPU 550 @ 3.20GHz         | 1        | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 19       | 26.03%  |
| Intel Xeon         | 16       | 21.92%  |
| Intel Core i7      | 8        | 10.96%  |
| Intel Core 2 Duo   | 8        | 10.96%  |
| Intel Core i3      | 4        | 5.48%   |
| AMD Ryzen 7        | 3        | 4.11%   |
| AMD Ryzen 5        | 3        | 4.11%   |
| Other              | 2        | 2.74%   |
| Intel Core 2 Quad  | 2        | 2.74%   |
| Intel Celeron      | 2        | 2.74%   |
| AMD Athlon II X2   | 2        | 2.74%   |
| Intel Pentium Dual | 1        | 1.37%   |
| Intel Pentium      | 1        | 1.37%   |
| Intel Core 2       | 1        | 1.37%   |
| AMD Ryzen 3        | 1        | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 28       | 37.84%  |
| 2      | 22       | 29.73%  |
| 8      | 10       | 13.51%  |
| 6      | 9        | 12.16%  |
| 16     | 2        | 2.7%    |
| 12     | 2        | 2.7%    |
| 1      | 1        | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 67       | 90.54%  |
| 2      | 7        | 9.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 56.16%  |
| 2      | 32       | 43.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 72       | 98.63%  |
| Unknown        | 1        | 1.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 28.57%  |
| 0x306c3    | 7        | 9.09%   |
| 0x206a7    | 7        | 9.09%   |
| 0x1067a    | 7        | 9.09%   |
| 0x206c2    | 6        | 7.79%   |
| 0x306a9    | 5        | 6.49%   |
| 0xa0655    | 3        | 3.9%    |
| 0x6f6      | 3        | 3.9%    |
| 0x206d7    | 3        | 3.9%    |
| 0x506e3    | 2        | 2.6%    |
| 0x106a5    | 2        | 2.6%    |
| 0x08701021 | 2        | 2.6%    |
| 0xa0671    | 1        | 1.3%    |
| 0x6fd      | 1        | 1.3%    |
| 0x6fb      | 1        | 1.3%    |
| 0x20655    | 1        | 1.3%    |
| 0x20652    | 1        | 1.3%    |
| 0x10676    | 1        | 1.3%    |
| 0x0800820d | 1        | 1.3%    |
| 0x010000b6 | 1        | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 11       | 15.07%  |
| Westmere    | 10       | 13.7%   |
| Haswell     | 10       | 13.7%   |
| Penryn      | 9        | 12.33%  |
| IvyBridge   | 6        | 8.22%   |
| Core        | 5        | 6.85%   |
| Zen 2       | 4        | 5.48%   |
| Skylake     | 4        | 5.48%   |
| Nehalem     | 4        | 5.48%   |
| CometLake   | 3        | 4.11%   |
| Zen+        | 2        | 2.74%   |
| K10         | 2        | 2.74%   |
| Unknown     | 2        | 2.74%   |
| Zen         | 1        | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 38.96%  |
| Nvidia | 28       | 36.36%  |
| AMD    | 19       | 24.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 8.43%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 7.23%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 6.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 4.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.61%   |
| Nvidia GT218 [GeForce 310]                                                  | 2        | 2.41%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.41%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.41%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 2.41%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 2.41%   |
| Intel HD Graphics 530                                                       | 2        | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 2.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.41%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 2.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.41%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 2.41%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.2%    |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.2%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.2%    |
| Nvidia GK104 [GeForce GTX 690]                                              | 1        | 1.2%    |
| Nvidia GF119 [NVS 315]                                                      | 1        | 1.2%    |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.2%    |
| Nvidia GF108M [GeForce GT 425M]                                             | 1        | 1.2%    |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.2%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.2%    |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.2%    |
| Nvidia G71GL [Quadro FX 1500]                                               | 1        | 1.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.2%    |
| AMD Turks PRO [Radeon HD 7570]                                              | 1        | 1.2%    |
| AMD RV730 GL [FirePro V3750]                                                | 1        | 1.2%    |
| AMD RV710 [Radeon HD 4550]                                                  | 1        | 1.2%    |
| AMD RV670 [Radeon HD 3870]                                                  | 1        | 1.2%    |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 1.2%    |
| AMD RV370 [Radeon X300]                                                     | 1        | 1.2%    |
| AMD RV370 [Radeon X300 SE]                                                  | 1        | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 28       | 36.84%  |
| 1 x Nvidia     | 25       | 32.89%  |
| 1 x AMD        | 16       | 21.05%  |
| Other          | 2        | 2.63%   |
| 2 x AMD        | 2        | 2.63%   |
| 2 x Nvidia     | 1        | 1.32%   |
| Intel + Nvidia | 1        | 1.32%   |
| AMD + Nvidia   | 1        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 68.35%  |
| Proprietary | 15       | 18.99%  |
| Unknown     | 10       | 12.66%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 62.34%  |
| 1.01-2.0   | 10       | 12.99%  |
| 0.01-0.5   | 8        | 10.39%  |
| 0.51-1.0   | 4        | 5.19%   |
| 3.01-4.0   | 3        | 3.9%    |
| 8.01-16.0  | 2        | 2.6%    |
| 5.01-6.0   | 1        | 1.3%    |
| 2.01-3.0   | 1        | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 16       | 30.19%  |
| Dell                | 11       | 20.75%  |
| Samsung Electronics | 5        | 9.43%   |
| Unknown             | 4        | 7.55%   |
| Acer                | 4        | 7.55%   |
| Lenovo              | 3        | 5.66%   |
| NEC Computers       | 2        | 3.77%   |
| Hitachi             | 2        | 3.77%   |
| ViewSonic           | 1        | 1.89%   |
| Philips             | 1        | 1.89%   |
| LED                 | 1        | 1.89%   |
| HannStar            | 1        | 1.89%   |
| Goldstar            | 1        | 1.89%   |
| DENON               | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 2        | 3.51%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch    | 2        | 3.51%   |
| ViewSonic LCD Monitor VA2451 SERIES 1920x1080                        | 1        | 1.75%   |
| Unknown LCD Monitor ITE DP2VGA V221 1680x1050                        | 1        | 1.75%   |
| Unknown LCD Monitor DellSP2008WFP 1680x1050                          | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM0586 1920x1200 518x324mm 24.1-inch | 1        | 1.75%   |
| Samsung Electronics SMBX2240 SAM0684 1920x1080 477x268mm 21.5-inch   | 1        | 1.75%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 1.75%   |
| Philips 150P PHL0814 1024x768 307x230mm 15.1-inch                    | 1        | 1.75%   |
| NEC Computers LCD1770NX NEC6665 1280x1024 338x270mm 17.0-inch        | 1        | 1.75%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch         | 1        | 1.75%   |
| Lenovo LEN-M93z-B LEN0093 1920x1080 510x290mm 23.1-inch              | 1        | 1.75%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 476x268mm 21.5-inch             | 1        | 1.75%   |
| Lenovo LEN P24q-20 LEN61F5 2560x1440 527x296mm 23.8-inch             | 1        | 1.75%   |
| LED TV LED2968 1366x768 575x323mm 26.0-inch                          | 1        | 1.75%   |
| Hitachi PC-DTA15AXGS HTCB88C 1024x768 304x228mm 15.0-inch            | 1        | 1.75%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.75%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch        | 1        | 1.75%   |
| Hewlett-Packard Z22i HWP308E 1920x1080 477x268mm 21.5-inch           | 1        | 1.75%   |
| Hewlett-Packard TouchSmart HWP4204 1920x1080 510x287mm 23.0-inch     | 1        | 1.75%   |
| Hewlett-Packard M27fw FHD HPN370F 1920x1080 597x336mm 27.0-inch      | 1        | 1.75%   |
| Hewlett-Packard M27fw FHD HPN370E 1920x1080 597x336mm 27.0-inch      | 1        | 1.75%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 470x300mm 22.0-inch        | 1        | 1.75%   |
| Hewlett-Packard LE1901w HWP284E 1440x900 410x256mm 19.0-inch         | 1        | 1.75%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor ZR2740w                                  | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor LA2206                                   | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor L2245w 1680x1050                         | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor 2009 3520x1080                           | 1        | 1.75%   |
| Hewlett-Packard LA2206 HWP2946 1920x1080 477x268mm 21.5-inch         | 1        | 1.75%   |
| Hewlett-Packard LA1956x HWP3021 1280x1024 376x301mm 19.0-inch        | 1        | 1.75%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch          | 1        | 1.75%   |
| Hewlett-Packard E221c HWP3092 1920x1080 497x292mm 22.7-inch          | 1        | 1.75%   |
| Hewlett-Packard E221 HWP3060 1920x1080 496x292mm 22.7-inch           | 1        | 1.75%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch           | 1        | 1.75%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch            | 1        | 1.75%   |
| HannStar HP205DJB HSD3FB9 1600x900 432x240mm 19.5-inch               | 1        | 1.75%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch             | 1        | 1.75%   |
| DENON AVR DON0063 3840x2160 1420x800mm 64.2-inch                     | 1        | 1.75%   |
| Dell U2413 DELF048 1920x1200 518x324mm 24.1-inch                     | 1        | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 39.62%  |
| 1280x1024 (SXGA)   | 7        | 13.21%  |
| 1680x1050 (WSXGA+) | 6        | 11.32%  |
| 1920x1200 (WUXGA)  | 3        | 5.66%   |
| 3840x2160 (4K)     | 2        | 3.77%   |
| 3440x1440          | 2        | 3.77%   |
| 2288x1287          | 2        | 3.77%   |
| 1024x768 (XGA)     | 2        | 3.77%   |
| Unknown            | 2        | 3.77%   |
| 3640x1920          | 1        | 1.89%   |
| 3520x1080          | 1        | 1.89%   |
| 2560x1440 (QHD)    | 1        | 1.89%   |
| 1600x900 (HD+)     | 1        | 1.89%   |
| 1440x900 (WXGA+)   | 1        | 1.89%   |
| 1366x768 (WXGA)    | 1        | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 9        | 17.31%  |
| Unknown | 8        | 15.38%  |
| 24      | 6        | 11.54%  |
| 19      | 6        | 11.54%  |
| 27      | 4        | 7.69%   |
| 23      | 4        | 7.69%   |
| 22      | 3        | 5.77%   |
| 17      | 3        | 5.77%   |
| 142     | 2        | 3.85%   |
| 15      | 2        | 3.85%   |
| 84      | 1        | 1.92%   |
| 72      | 1        | 1.92%   |
| 40      | 1        | 1.92%   |
| 26      | 1        | 1.92%   |
| 18      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 15       | 28.85%  |
| 401-500        | 15       | 28.85%  |
| Unknown        | 8        | 15.38%  |
| 301-350        | 5        | 9.62%   |
| 351-400        | 4        | 7.69%   |
| More than 2000 | 2        | 3.85%   |
| 1501-2000      | 2        | 3.85%   |
| 801-900        | 1        | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 49.02%  |
| Unknown | 8        | 15.69%  |
| 5/4     | 7        | 13.73%  |
| 16/10   | 7        | 13.73%  |
| 4/3     | 2        | 3.92%   |
| 1.00    | 2        | 3.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 32.69%  |
| 151-200        | 8        | 15.38%  |
| Unknown        | 8        | 15.38%  |
| More than 1000 | 4        | 7.69%   |
| 301-350        | 4        | 7.69%   |
| 251-300        | 4        | 7.69%   |
| 141-150        | 4        | 7.69%   |
| 101-110        | 2        | 3.85%   |
| 501-1000       | 1        | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 32       | 62.75%  |
| Unknown | 8        | 15.69%  |
| 101-120 | 7        | 13.73%  |
| 1-50    | 3        | 5.88%   |
| 121-160 | 1        | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 69.74%  |
| 0     | 16       | 21.05%  |
| 2     | 7        | 9.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 31.3%   |
| Realtek Semiconductor           | 31       | 23.66%  |
| Broadcom                        | 25       | 19.08%  |
| Ralink Technology               | 8        | 6.11%   |
| Samsung Electronics             | 3        | 2.29%   |
| Qualcomm Atheros Communications | 3        | 2.29%   |
| MediaTek                        | 3        | 2.29%   |
| D-Link                          | 3        | 2.29%   |
| Qualcomm Atheros                | 2        | 1.53%   |
| Nvidia                          | 2        | 1.53%   |
| Marvell Technology Group        | 2        | 1.53%   |
| Huawei Technologies             | 2        | 1.53%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.76%   |
| VIA Technologies                | 1        | 0.76%   |
| Sierra Wireless                 | 1        | 0.76%   |
| Broadcom Limited                | 1        | 0.76%   |
| ASIX Electronics                | 1        | 0.76%   |
| 3Com                            | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 14       | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 14       | 10%     |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 9        | 6.43%   |
| Ralink MT7601U Wireless Adapter                                      | 8        | 5.71%   |
| Intel Ethernet Connection I217-LM                                    | 7        | 5%      |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 6        | 4.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4        | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 2.86%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 3        | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3        | 2.14%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 2.14%   |
| Intel Ethernet Connection (2) I219-V                                 | 3        | 2.14%   |
| Intel 82574L Gigabit Network Connection                              | 3        | 2.14%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 3        | 2.14%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 3        | 2.14%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 3        | 2.14%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 3        | 2.14%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3        | 2.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.43%   |
| Nvidia MCP51 Ethernet Controller                                     | 2        | 1.43%   |
| MediaTek File-CD Gadget                                              | 2        | 1.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 1.43%   |
| Intel Ethernet Connection (11) I219-LM                               | 2        | 1.43%   |
| Intel 82578DM Gigabit Network Connection                             | 2        | 1.43%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 2        | 1.43%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express              | 2        | 1.43%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                        | 1        | 0.71%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 1        | 0.71%   |
| Sierra Wireless MC7700                                               | 1        | 0.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.71%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 0.71%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                 | 1        | 0.71%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 0.71%   |
| Realtek 802.11ac NIC                                                 | 1        | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1        | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 0.71%   |
| Marvell Group 88W8361 [TopDog] 802.11n Wireless                      | 1        | 0.71%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 1        | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 38.1%   |
| Ralink Technology               | 8        | 19.05%  |
| Broadcom                        | 5        | 11.9%   |
| Qualcomm Atheros Communications | 3        | 7.14%   |
| Intel                           | 3        | 7.14%   |
| D-Link                          | 3        | 7.14%   |
| Sierra Wireless                 | 1        | 2.38%   |
| Qualcomm Atheros                | 1        | 2.38%   |
| MediaTek                        | 1        | 2.38%   |
| Marvell Technology Group        | 1        | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 8        | 18.6%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 4        | 9.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 9.3%    |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 6.98%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 3        | 6.98%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller  | 3        | 6.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 4.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2        | 4.65%   |
| Sierra Wireless MC7700                                               | 1        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 2.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 2.33%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                 | 1        | 2.33%   |
| Realtek RTL8187 Wireless Adapter                                     | 1        | 2.33%   |
| Realtek 802.11ac NIC                                                 | 1        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1        | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 2.33%   |
| Marvell Group 88W8361 [TopDog] 802.11n Wireless                      | 1        | 2.33%   |
| Intel Wireless 7260                                                  | 1        | 2.33%   |
| Broadcom BCM43227 802.11b/g/n                                        | 1        | 2.33%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 39       | 42.39%  |
| Broadcom                   | 20       | 21.74%  |
| Realtek Semiconductor      | 17       | 18.48%  |
| Samsung Electronics        | 3        | 3.26%   |
| Nvidia                     | 2        | 2.17%   |
| MediaTek                   | 2        | 2.17%   |
| Huawei Technologies        | 2        | 2.17%   |
| ZTE WCDMA Technologies MSM | 1        | 1.09%   |
| VIA Technologies           | 1        | 1.09%   |
| Qualcomm Atheros           | 1        | 1.09%   |
| Marvell Technology Group   | 1        | 1.09%   |
| Broadcom Limited           | 1        | 1.09%   |
| ASIX Electronics           | 1        | 1.09%   |
| 3Com                       | 1        | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 14.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14       | 14.43%  |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9        | 9.28%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 7.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 6        | 6.19%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 3.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.09%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 3.09%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 3.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 3.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 3.09%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 2.06%   |
| MediaTek File-CD Gadget                                           | 2        | 2.06%   |
| Intel Ethernet Connection (11) I219-LM                            | 2        | 2.06%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.06%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 2.06%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 1.03%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 1.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.03%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.03%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.03%   |
| Huawei Ideos (tethering mode)                                     | 1        | 1.03%   |
| Huawei E353/E3131                                                 | 1        | 1.03%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.03%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                       | 1        | 1.03%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 1.03%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.03%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 65.18%  |
| WiFi     | 39       | 34.82%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 71.64%  |
| WiFi     | 19       | 28.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 58.11%  |
| 2     | 22       | 29.73%  |
| 3     | 5        | 6.76%   |
| 4     | 4        | 5.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 94.67%  |
| Yes  | 4        | 5.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 12       | 52.17%  |
| Realtek Semiconductor   | 5        | 21.74%  |
| Intel                   | 3        | 13.04%  |
| Broadcom                | 2        | 8.7%    |
| AboCom Systems          | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 52.17%  |
| Realtek Bluetooth Radio                             | 4        | 17.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.35%   |
| Intel Bluetooth wireless interface                  | 1        | 4.35%   |
| Broadcom HP Bluethunder                             | 1        | 4.35%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 4.35%   |
| AboCom Systems AboCom Bluetooth Device              | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 61       | 53.04%  |
| Nvidia                 | 27       | 23.48%  |
| AMD                    | 19       | 16.52%  |
| Generalplus Technology | 3        | 2.61%   |
| C-Media Electronics    | 2        | 1.74%   |
| Texas Instruments      | 1        | 0.87%   |
| FIFINE 683 Microphone  | 1        | 0.87%   |
| Creative Labs          | 1        | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 6.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 6.15%   |
| Nvidia High Definition Audio Controller                                    | 7        | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 3.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 3.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.31%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 2.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 2.31%   |
| Generalplus Technology USB Audio Device                                    | 3        | 2.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.31%   |
| Nvidia MCP51 High Definition Audio                                         | 2        | 1.54%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.54%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.54%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2        | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.54%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.77%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.77%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.77%   |
| FIFINE 683 Microphone FIFINE 683 Microphone                                | 1        | 0.77%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 0.77%   |
| C-Media Electronics USB Audio Device                                       | 1        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 17       | 33.33%  |
| SK hynix            | 15       | 29.41%  |
| Kingston            | 5        | 9.8%    |
| Micron Technology   | 4        | 7.84%   |
| Unknown (2C0B)      | 2        | 3.92%   |
| Elpida              | 2        | 3.92%   |
| Unknown             | 1        | 1.96%   |
| Transcend           | 1        | 1.96%   |
| Toshiba-0098        | 1        | 1.96%   |
| Team                | 1        | 1.96%   |
| Ramaxel Technology  | 1        | 1.96%   |
| A-DATA Technology   | 1        | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM 1333MT/s              | 3        | 4.62%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s         | 3        | 4.62%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s            | 2        | 3.08%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s        | 2        | 3.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2        | 3.08%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s                   | 1        | 1.54%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                   | 1        | 1.54%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s          | 1        | 1.54%   |
| Toshiba-0098 RAM 9965516-069.A00LF 8192MB DIMM DDR3 1067MT/s | 1        | 1.54%   |
| Toshiba-0098 RAM 9965516-057.A00LF 8192MB DIMM DDR3 1067MT/s | 1        | 1.54%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 1.54%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 1        | 1.54%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                | 1        | 1.54%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.54%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.54%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1067MT/s        | 1        | 1.54%   |
| SK hynix RAM HMT42GR7AFR4A 16GB DIMM DDR3 1600MT/s           | 1        | 1.54%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s      | 1        | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1333MT/s         | 1        | 1.54%   |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1.54%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 1        | 1.54%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1.54%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s        | 1        | 1.54%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 1.54%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1        | 1.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 1        | 1.54%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1        | 1.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1        | 1.54%   |
| Samsung RAM M393B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 1.54%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s         | 1        | 1.54%   |
| Samsung RAM M393B2G70QH0-YH9 16384MB DIMM DDR3 1333MT/s      | 1        | 1.54%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1067MT/s         | 1        | 1.54%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s             | 1        | 1.54%   |
| Samsung RAM M393B1K70DH0-YK0 8192MB DIMM DDR3 1600MT/s       | 1        | 1.54%   |
| Samsung RAM M393B1K70DH0-CK0 8GB DIMM DDR3 1600MT/s          | 1        | 1.54%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1067MT/s       | 1        | 1.54%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 1        | 1.54%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s          | 1        | 1.54%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s          | 1        | 1.54%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 23       | 69.7%   |
| DDR4  | 6        | 18.18%  |
| SDRAM | 3        | 9.09%   |
| DDR2  | 1        | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 29       | 90.63%  |
| SODIMM | 3        | 9.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 10       | 26.32%  |
| 2048  | 10       | 26.32%  |
| 4096  | 9        | 23.68%  |
| 8192  | 8        | 21.05%  |
| 32768 | 1        | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 34.15%  |
| 1333  | 9        | 21.95%  |
| 2667  | 5        | 12.2%   |
| 1866  | 3        | 7.32%   |
| 4199  | 1        | 2.44%   |
| 3733  | 1        | 2.44%   |
| 2666  | 1        | 2.44%   |
| 2200  | 1        | 2.44%   |
| 2133  | 1        | 2.44%   |
| 2000  | 1        | 2.44%   |
| 1867  | 1        | 2.44%   |
| 1067  | 1        | 2.44%   |
| 1066  | 1        | 2.44%   |
| 800   | 1        | 2.44%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 2        | 25%     |
| Samsung Electronics     | 1        | 12.5%   |
| OmniVision Technologies | 1        | 12.5%   |
| MacroSilicon            | 1        | 12.5%   |
| Asuscom Network         | 1        | 12.5%   |
| Apple                   | 1        | 12.5%   |
| Acer                    | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera           | 2        | 25%     |
| Samsung Galaxy A5 (MTP)              | 1        | 12.5%   |
| OmniVision Monitor Integrated Webcam | 1        | 12.5%   |
| MacroSilicon USB Video               | 1        | 12.5%   |
| Asuscom Network Depstech webcam      | 1        | 12.5%   |
| Apple iPhone 5/5C/5S/6/SE            | 1        | 12.5%   |
| Acer Integrated Camera               | 1        | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 55       | 70.51%  |
| 1     | 13       | 16.67%  |
| 2     | 6        | 7.69%   |
| 3     | 2        | 2.56%   |
| 5     | 1        | 1.28%   |
| 4     | 1        | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 35.29%  |
| Net/wireless             | 10       | 29.41%  |
| Sound                    | 7        | 20.59%  |
| Communication controller | 3        | 8.82%   |
| Network                  | 1        | 2.94%   |
| Net/ethernet             | 1        | 2.94%   |

