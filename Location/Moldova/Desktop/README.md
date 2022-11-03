Linux in Moldova - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

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

Total: 90

| Vendor   | Model               | Probe                                                      | Date         |
|----------|---------------------|------------------------------------------------------------|--------------|
| Biostar  | TB250-BTC PRO       | [09be95ac2c](https://linux-hardware.org/?probe=09be95ac2c) | Oct 10, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0    | [0f690e6e12](https://linux-hardware.org/?probe=0f690e6e12) | Oct 08, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0    | [e9bc8b1f10](https://linux-hardware.org/?probe=e9bc8b1f10) | Sep 26, 2022 |
| Gigabyte | B550 AORUS ELITE    | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| Foxconn  | nT-330i             | [64504a98ed](https://linux-hardware.org/?probe=64504a98ed) | Aug 04, 2022 |
| Dell     | 0782GW A01          | [20cb4c3e27](https://linux-hardware.org/?probe=20cb4c3e27) | Jul 11, 2022 |
| Gigabyte | B450M S2H V2        | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| ASUSTek  | PRIME A520M-K       | [72dd09a86a](https://linux-hardware.org/?probe=72dd09a86a) | Jun 05, 2022 |
| ASUSTek  | M4A785-M            | [25526ee77d](https://linux-hardware.org/?probe=25526ee77d) | Apr 17, 2022 |
| ASUSTek  | PRIME B550-PLUS     | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Gigabyte | Z690 UD DDR4        | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| HP       | 21F5                | [ce8e06508d](https://linux-hardware.org/?probe=ce8e06508d) | Jan 16, 2022 |
| Biostar  | N68S3+              | [8812de783f](https://linux-hardware.org/?probe=8812de783f) | Dec 16, 2021 |
| ASUSTek  | A_F_K20CE           | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| ASUSTek  | Z97I-PLUS           | [a379cfa431](https://linux-hardware.org/?probe=a379cfa431) | Dec 12, 2021 |
| Gigabyte | H61M-S2-B3          | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| ASRock   | M3A770DE            | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| Gigabyte | H81M-HD3            | [953c3f9284](https://linux-hardware.org/?probe=953c3f9284) | Nov 13, 2021 |
| MSI      | MS-7309             | [0a4d7fb95d](https://linux-hardware.org/?probe=0a4d7fb95d) | Oct 30, 2021 |
| MSI      | A75A-G35            | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| Biostar  | N68S3+              | [1eae78eec0](https://linux-hardware.org/?probe=1eae78eec0) | Aug 04, 2021 |
| Gigabyte | B460M DS3H V2       | [6177f24834](https://linux-hardware.org/?probe=6177f24834) | Aug 02, 2021 |
| Gigabyte | B460M DS3H V2       | [7fa66f2f95](https://linux-hardware.org/?probe=7fa66f2f95) | Aug 02, 2021 |
| Gigabyte | EP43-UD3L           | [3b6839e225](https://linux-hardware.org/?probe=3b6839e225) | Jul 01, 2021 |
| ASUSTek  | F1A75-M LE          | [b453e98364](https://linux-hardware.org/?probe=b453e98364) | May 21, 2021 |
| Biostar  | A58MD               | [3effc9a4ed](https://linux-hardware.org/?probe=3effc9a4ed) | Apr 18, 2021 |
| Biostar  | H110MHC             | [acc13c8156](https://linux-hardware.org/?probe=acc13c8156) | Mar 24, 2021 |
| ASUSTek  | P8Z77-V PRO         | [a3d54dee1b](https://linux-hardware.org/?probe=a3d54dee1b) | Feb 22, 2021 |
| ASUSTek  | P8Z77-V PRO         | [7f75cd3e14](https://linux-hardware.org/?probe=7f75cd3e14) | Feb 22, 2021 |
| ASUSTek  | PRIME B350-PLUS     | [23ddb098d4](https://linux-hardware.org/?probe=23ddb098d4) | Feb 18, 2021 |
| ASRock   | Z87 Extreme4        | [2fc1d961c0](https://linux-hardware.org/?probe=2fc1d961c0) | Feb 14, 2021 |
| ASUSTek  | B85M-E              | [024b12b22d](https://linux-hardware.org/?probe=024b12b22d) | Jan 17, 2021 |
| Gigabyte | GA-970A-DS3         | [f333aed432](https://linux-hardware.org/?probe=f333aed432) | Dec 04, 2020 |
| Gigabyte | X570 AORUS ULTRA    | [bdc9ccf5d5](https://linux-hardware.org/?probe=bdc9ccf5d5) | Nov 23, 2020 |
| Biostar  | A960D+V3            | [86864a3f9a](https://linux-hardware.org/?probe=86864a3f9a) | Oct 01, 2020 |
| Biostar  | A960D+V3            | [781ac4ebab](https://linux-hardware.org/?probe=781ac4ebab) | Sep 30, 2020 |
| Gigabyte | P41-ES3G            | [30feb0323e](https://linux-hardware.org/?probe=30feb0323e) | Sep 29, 2020 |
| Gigabyte | P41-ES3G            | [395e492e72](https://linux-hardware.org/?probe=395e492e72) | Sep 29, 2020 |
| ASUSTek  | P8H61-MX            | [46cff277d4](https://linux-hardware.org/?probe=46cff277d4) | Aug 16, 2020 |
| ASUSTek  | M2N-SLI DELUXE      | [02ab999339](https://linux-hardware.org/?probe=02ab999339) | Aug 04, 2020 |
| ASRock   | A320M-HDV R4.0      | [0320a45205](https://linux-hardware.org/?probe=0320a45205) | Jul 25, 2020 |
| ASUSTek  | M4A785TD-V EVO      | [734d413d2f](https://linux-hardware.org/?probe=734d413d2f) | May 25, 2020 |
| ASUSTek  | M4A785TD-V EVO      | [a5f24237a6](https://linux-hardware.org/?probe=a5f24237a6) | May 22, 2020 |
| ASUSTek  | P8B75-M LE          | [3051982d33](https://linux-hardware.org/?probe=3051982d33) | Apr 28, 2020 |
| ASUSTek  | P8B75-M LE          | [6e3a1017c8](https://linux-hardware.org/?probe=6e3a1017c8) | Apr 28, 2020 |
| ASUSTek  | H110M-K             | [d65e7d1bb6](https://linux-hardware.org/?probe=d65e7d1bb6) | Mar 28, 2020 |
| ASUSTek  | F1A75-M LE          | [3cee091303](https://linux-hardware.org/?probe=3cee091303) | Mar 25, 2020 |
| ASUSTek  | H110M-K             | [c0aa963f37](https://linux-hardware.org/?probe=c0aa963f37) | Mar 21, 2020 |
| MSI      | 2A9C                | [cb1789ae00](https://linux-hardware.org/?probe=cb1789ae00) | Mar 18, 2020 |
| ASUSTek  | M5A78L-M LX         | [90f55c011b](https://linux-hardware.org/?probe=90f55c011b) | Dec 04, 2019 |
| ASUSTek  | P5QL/EPU            | [8f31c009af](https://linux-hardware.org/?probe=8f31c009af) | Oct 20, 2019 |
| ASUSTek  | F1A75-M LE          | [bdb727808f](https://linux-hardware.org/?probe=bdb727808f) | Jul 26, 2019 |
| ASUSTek  | F1A75-M LE          | [961de73328](https://linux-hardware.org/?probe=961de73328) | Jul 26, 2019 |
| Biostar  | GF8100 M2+ SE       | [52b394c153](https://linux-hardware.org/?probe=52b394c153) | May 05, 2019 |
| ASUSTek  | P5P43TD             | [bbfc5c83ed](https://linux-hardware.org/?probe=bbfc5c83ed) | Apr 23, 2019 |
| ASUSTek  | P5P43TD             | [a1df618ae9](https://linux-hardware.org/?probe=a1df618ae9) | Apr 18, 2019 |
| Gigabyte | G41M-ES2L           | [62f911ea35](https://linux-hardware.org/?probe=62f911ea35) | Apr 09, 2019 |
| HP       | 82A1                | [f04f3b1720](https://linux-hardware.org/?probe=f04f3b1720) | Mar 18, 2019 |
| ASRock   | B250M Pro4          | [05dfa7d080](https://linux-hardware.org/?probe=05dfa7d080) | Jan 07, 2019 |
| ASRock   | B250M Pro4          | [4ca432ffe1](https://linux-hardware.org/?probe=4ca432ffe1) | Jan 03, 2019 |
| Biostar  | NF61D-A2            | [8920fb5da2](https://linux-hardware.org/?probe=8920fb5da2) | Nov 24, 2018 |
| Gigabyte | H61M-S1             | [f035a927b4](https://linux-hardware.org/?probe=f035a927b4) | Oct 16, 2018 |
| Gigabyte | H61M-S1             | [0cb176039a](https://linux-hardware.org/?probe=0cb176039a) | Oct 16, 2018 |
| ASUSTek  | H110M-R             | [e8cf4914df](https://linux-hardware.org/?probe=e8cf4914df) | Oct 11, 2018 |
| ASUSTek  | TUF X299 MARK 1     | [4ff6f8b306](https://linux-hardware.org/?probe=4ff6f8b306) | Aug 28, 2018 |
| ASUSTek  | H110M-R             | [856815508e](https://linux-hardware.org/?probe=856815508e) | Jul 20, 2018 |
| ASUSTek  | H110M-R             | [2c6e982e0a](https://linux-hardware.org/?probe=2c6e982e0a) | Jul 20, 2018 |
| ASRock   | H110M-DGS           | [2bf308c36a](https://linux-hardware.org/?probe=2bf308c36a) | Apr 22, 2018 |
| Gigabyte | H81M-S2PV           | [d73e7cdaf7](https://linux-hardware.org/?probe=d73e7cdaf7) | Apr 10, 2018 |
| ASUSTek  | M5A78L LE           | [324ea287af](https://linux-hardware.org/?probe=324ea287af) | Mar 25, 2018 |
| ASUSTek  | M5A78L LE           | [c4796ca0ba](https://linux-hardware.org/?probe=c4796ca0ba) | Mar 25, 2018 |
| MSI      | G31M3-L V2          | [a010b34c1d](https://linux-hardware.org/?probe=a010b34c1d) | Mar 14, 2018 |
| Gigabyte | GA-880GM-USB3       | [488c7af7b3](https://linux-hardware.org/?probe=488c7af7b3) | Feb 13, 2018 |
| Biostar  | H61MGV3             | [601f3981af](https://linux-hardware.org/?probe=601f3981af) | Jan 25, 2018 |
| MSI      | G31M3-L V2          | [cb825d670e](https://linux-hardware.org/?probe=cb825d670e) | Jan 23, 2018 |
| Biostar  | A960G+              | [1ed969e51e](https://linux-hardware.org/?probe=1ed969e51e) | Jan 02, 2018 |
| Gigabyte | H81M-S2PV           | [b4b5168bf0](https://linux-hardware.org/?probe=b4b5168bf0) | Oct 22, 2017 |
| Biostar  | TA790GX 128M        | [13dafc619e](https://linux-hardware.org/?probe=13dafc619e) | Sep 07, 2017 |
| ASUSTek  | P7P55D-E            | [7ead295d4f](https://linux-hardware.org/?probe=7ead295d4f) | May 04, 2017 |
| ASUSTek  | P5GPL               | [dc412a96d7](https://linux-hardware.org/?probe=dc412a96d7) | Mar 11, 2017 |
| ASUSTek  | P5GPL               | [704d76d7f0](https://linux-hardware.org/?probe=704d76d7f0) | Mar 11, 2017 |
| ECS      | GeForce7050M-M      | [dffec0e1ef](https://linux-hardware.org/?probe=dffec0e1ef) | Jan 26, 2017 |
| MSI      | G41M-P26            | [3a93859874](https://linux-hardware.org/?probe=3a93859874) | Jan 21, 2017 |
| Dell     | 0HJ054              | [3a64a2e7cc](https://linux-hardware.org/?probe=3a64a2e7cc) | Jan 14, 2017 |
| ASUSTek  | M5A78L-M LX3        | [de5986b48c](https://linux-hardware.org/?probe=de5986b48c) | Dec 27, 2016 |
| ASUSTek  | P8H61-M LX3         | [51108b9a7b](https://linux-hardware.org/?probe=51108b9a7b) | Nov 26, 2016 |
| ASUSTek  | A88X-PLUS           | [e5165dfe31](https://linux-hardware.org/?probe=e5165dfe31) | Nov 25, 2016 |
| ASUSTek  | A88X-PLUS           | [53f70342b5](https://linux-hardware.org/?probe=53f70342b5) | Nov 23, 2016 |
| ASUSTek  | P5KPL-AM IN/ROEM/SI | [c140d93dd9](https://linux-hardware.org/?probe=c140d93dd9) | Nov 08, 2016 |
| ECS      | GeForce7050M-M      | [3f276c748c](https://linux-hardware.org/?probe=3f276c748c) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ROSA R10         | 12       | 17.14%  |
| ROSA R11         | 8        | 11.43%  |
| ROSA R8          | 7        | 10%     |
| ROSA R8.1        | 6        | 8.57%   |
| ROSA R11.1       | 6        | 8.57%   |
| OpenMandriva 4.2 | 6        | 8.57%   |
| Ubuntu 18.04     | 3        | 4.29%   |
| Ubuntu 20.04     | 2        | 2.86%   |
| ROSA 12.2        | 2        | 2.86%   |
| Manjaro          | 2        | 2.86%   |
| Arch Rolling     | 2        | 2.86%   |
| Ubuntu 21.10     | 1        | 1.43%   |
| Ubuntu 16.04     | 1        | 1.43%   |
| ROSA R9          | 1        | 1.43%   |
| Pop!_OS 21.10    | 1        | 1.43%   |
| Pop!_OS 20.10    | 1        | 1.43%   |
| Pop!_OS 20.04    | 1        | 1.43%   |
| OpenMandriva 4.3 | 1        | 1.43%   |
| Manjaro 21.3.0   | 1        | 1.43%   |
| Linux Mint 20    | 1        | 1.43%   |
| Linux Mint 19.3  | 1        | 1.43%   |
| KDE neon 20.04   | 1        | 1.43%   |
| Kali 2019.3      | 1        | 1.43%   |
| Fedora 35        | 1        | 1.43%   |
| Ctlos 1.4.0      | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 40       | 58.82%  |
| Ubuntu       | 7        | 10.29%  |
| OpenMandriva | 7        | 10.29%  |
| Pop!_OS      | 3        | 4.41%   |
| Manjaro      | 3        | 4.41%   |
| Linux Mint   | 2        | 2.94%   |
| Arch         | 2        | 2.94%   |
| KDE neon     | 1        | 1.47%   |
| Kali         | 1        | 1.47%   |
| Fedora       | 1        | 1.47%   |
| Ctlos        | 1        | 1.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002           | 6        | 8.33%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 6        | 8.33%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 4        | 5.56%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 4        | 5.56%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2        | 2.78%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 2        | 2.78%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2        | 2.78%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2        | 2.78%   |
| 4.15.0-desktop-47.2rosa-x86_64     | 2        | 2.78%   |
| 4.1.34-nrj-desktop-2rosa-i586      | 2        | 2.78%   |
| 5.9.3-050903-generic               | 1        | 1.39%   |
| 5.8.0-7642-generic                 | 1        | 1.39%   |
| 5.8.0-38-generic                   | 1        | 1.39%   |
| 5.5.9-zen1-2-zen                   | 1        | 1.39%   |
| 5.4.83-generic-2rosa-x86_64        | 1        | 1.39%   |
| 5.4.32-generic-2rosa-x86_64        | 1        | 1.39%   |
| 5.4.32-generic-2rosa-i586          | 1        | 1.39%   |
| 5.4.0-90-generic                   | 1        | 1.39%   |
| 5.4.0-7634-generic                 | 1        | 1.39%   |
| 5.4.0-56-generic                   | 1        | 1.39%   |
| 5.4.0-48-generic                   | 1        | 1.39%   |
| 5.2.0-kali2-amd64                  | 1        | 1.39%   |
| 5.17.9-arch1-1                     | 1        | 1.39%   |
| 5.17.11-generic-2rosa2021.1-x86_64 | 1        | 1.39%   |
| 5.16.9-200.fc35.x86_64             | 1        | 1.39%   |
| 5.16.7-desktop-1omv4003            | 1        | 1.39%   |
| 5.15.48-1-MANJARO                  | 1        | 1.39%   |
| 5.15.11-76051511-generic           | 1        | 1.39%   |
| 5.14.14-arch1-1                    | 1        | 1.39%   |
| 5.13.0-52-generic                  | 1        | 1.39%   |
| 5.13.0-39-generic                  | 1        | 1.39%   |
| 5.10.53-1-MANJARO                  | 1        | 1.39%   |
| 5.10.26-1-MANJARO                  | 1        | 1.39%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 1        | 1.39%   |
| 4.9.9-nrj-desktop-1rosa-i586       | 1        | 1.39%   |
| 4.9.87-nrj-desktop-2rosa-x86_64    | 1        | 1.39%   |
| 4.9.76-nrj-desktop-1rosa-x86_64    | 1        | 1.39%   |
| 4.9.76-nrj-desktop-1rosa-i586      | 1        | 1.39%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 1        | 1.39%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 1        | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 11       | 15.49%  |
| 4.9.60  | 7        | 9.86%   |
| 5.10.14 | 6        | 8.45%   |
| 4.1.34  | 6        | 8.45%   |
| 5.4.0   | 4        | 5.63%   |
| 5.8.0   | 2        | 2.82%   |
| 5.4.32  | 2        | 2.82%   |
| 5.13.0  | 2        | 2.82%   |
| 5.10.74 | 2        | 2.82%   |
| 4.9.9   | 2        | 2.82%   |
| 4.9.76  | 2        | 2.82%   |
| 4.9.20  | 2        | 2.82%   |
| 4.9.155 | 2        | 2.82%   |
| 4.9.124 | 2        | 2.82%   |
| 4.1.38  | 2        | 2.82%   |
| 5.9.3   | 1        | 1.41%   |
| 5.5.9   | 1        | 1.41%   |
| 5.4.83  | 1        | 1.41%   |
| 5.2.0   | 1        | 1.41%   |
| 5.17.9  | 1        | 1.41%   |
| 5.17.11 | 1        | 1.41%   |
| 5.16.9  | 1        | 1.41%   |
| 5.16.7  | 1        | 1.41%   |
| 5.15.48 | 1        | 1.41%   |
| 5.15.11 | 1        | 1.41%   |
| 5.14.14 | 1        | 1.41%   |
| 5.10.53 | 1        | 1.41%   |
| 5.10.26 | 1        | 1.41%   |
| 4.9.87  | 1        | 1.41%   |
| 4.18.0  | 1        | 1.41%   |
| 4.10.0  | 1        | 1.41%   |
| 4.1.25  | 1        | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 17       | 24.29%  |
| 4.15    | 11       | 15.71%  |
| 5.10    | 10       | 14.29%  |
| 4.1     | 9        | 12.86%  |
| 5.4     | 7        | 10%     |
| 5.8     | 2        | 2.86%   |
| 5.17    | 2        | 2.86%   |
| 5.16    | 2        | 2.86%   |
| 5.15    | 2        | 2.86%   |
| 5.13    | 2        | 2.86%   |
| 5.9     | 1        | 1.43%   |
| 5.5     | 1        | 1.43%   |
| 5.2     | 1        | 1.43%   |
| 5.14    | 1        | 1.43%   |
| 4.18    | 1        | 1.43%   |
| 4.10    | 1        | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 58       | 85.29%  |
| i686   | 10       | 14.71%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE4            | 27       | 39.13%  |
| KDE5            | 18       | 26.09%  |
| GNOME           | 10       | 14.49%  |
| XFCE            | 3        | 4.35%   |
| X-Cinnamon      | 2        | 2.9%    |
| LXQt            | 2        | 2.9%    |
| KDE             | 2        | 2.9%    |
| xinitrc         | 1        | 1.45%   |
| sway            | 1        | 1.45%   |
| MATE            | 1        | 1.45%   |
| GNOME Flashback | 1        | 1.45%   |
| Unknown         | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 62       | 91.18%  |
| Wayland | 5        | 7.35%   |
| Unknown | 1        | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 27       | 39.13%  |
| SDDM    | 22       | 31.88%  |
| Unknown | 13       | 18.84%  |
| GDM     | 3        | 4.35%   |
| TDM     | 2        | 2.9%    |
| LightDM | 1        | 1.45%   |
| GDM3    | 1        | 1.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 48.57%  |
| ru_RU   | 20       | 28.57%  |
| en_US   | 11       | 15.71%  |
| ro_RO   | 2        | 2.86%   |
| en_GB   | 2        | 2.86%   |
| ru_UA   | 1        | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 57       | 82.61%  |
| EFI  | 12       | 17.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 40       | 58.82%  |
| Unknown | 21       | 30.88%  |
| Overlay | 5        | 7.35%   |
| Btrfs   | 2        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 40       | 56.34%  |
| Unknown | 19       | 26.76%  |
| GPT     | 12       | 16.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 81.16%  |
| Yes       | 13       | 18.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 65.22%  |
| Yes       | 24       | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 28       | 41.18%  |
| Gigabyte Technology | 14       | 20.59%  |
| Biostar             | 10       | 14.71%  |
| MSI                 | 5        | 7.35%   |
| ASRock              | 5        | 7.35%   |
| Hewlett-Packard     | 2        | 2.94%   |
| Dell                | 2        | 2.94%   |
| Foxconn             | 1        | 1.47%   |
| ECS                 | 1        | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS H110M-R               | 2        | 2.94%   |
| ASUS All Series            | 2        | 2.94%   |
| MSI Pro 3130 Microtower PC | 1        | 1.47%   |
| MSI MS-7695                | 1        | 1.47%   |
| MSI MS-7592                | 1        | 1.47%   |
| MSI MS-7529                | 1        | 1.47%   |
| MSI MS-7309                | 1        | 1.47%   |
| HP ProDesk 490 G2 MT       | 1        | 1.47%   |
| HP ProDesk 400 G4 MT       | 1        | 1.47%   |
| Gigabyte Z690 UD DDR4      | 1        | 1.47%   |
| Gigabyte X570 AORUS ULTRA  | 1        | 1.47%   |
| Gigabyte P41-ES3G          | 1        | 1.47%   |
| Gigabyte H81M-S2PV         | 1        | 1.47%   |
| Gigabyte H81M-HD3          | 1        | 1.47%   |
| Gigabyte H61M-S2-B3        | 1        | 1.47%   |
| Gigabyte H61M-S1           | 1        | 1.47%   |
| Gigabyte GA-970A-DS3       | 1        | 1.47%   |
| Gigabyte GA-880GM-USB3     | 1        | 1.47%   |
| Gigabyte G41M-ES2L         | 1        | 1.47%   |
| Gigabyte EP43-UD3L         | 1        | 1.47%   |
| Gigabyte B550 AORUS ELITE  | 1        | 1.47%   |
| Gigabyte B460MDS3HV2       | 1        | 1.47%   |
| Gigabyte B450M S2H V2      | 1        | 1.47%   |
| Foxconn nT-330i            | 1        | 1.47%   |
| ECS GeForce7050M-M         | 1        | 1.47%   |
| Dell OptiPlex 5050         | 1        | 1.47%   |
| Dell DM051                 | 1        | 1.47%   |
| Biostar TB250-BTC PRO      | 1        | 1.47%   |
| Biostar TA790GX 128M       | 1        | 1.47%   |
| Biostar NF61D-A2           | 1        | 1.47%   |
| Biostar N68S3+             | 1        | 1.47%   |
| Biostar H61MGV3            | 1        | 1.47%   |
| Biostar H110MHC            | 1        | 1.47%   |
| Biostar GF8100 M2+ SE      | 1        | 1.47%   |
| Biostar A960G+             | 1        | 1.47%   |
| Biostar A960D+V3           | 1        | 1.47%   |
| Biostar A58MD              | 1        | 1.47%   |
| ASUS TUF X299 MARK 1       | 1        | 1.47%   |
| ASUS PRIME B550-PLUS       | 1        | 1.47%   |
| ASUS PRIME B350-PLUS       | 1        | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 3        | 4.41%   |
| HP ProDesk             | 2        | 2.94%   |
| ASUS P8H61-M           | 2        | 2.94%   |
| ASUS M5A78L-M          | 2        | 2.94%   |
| ASUS H110M-R           | 2        | 2.94%   |
| ASUS All               | 2        | 2.94%   |
| MSI Pro                | 1        | 1.47%   |
| MSI MS-7695            | 1        | 1.47%   |
| MSI MS-7592            | 1        | 1.47%   |
| MSI MS-7529            | 1        | 1.47%   |
| MSI MS-7309            | 1        | 1.47%   |
| Gigabyte Z690          | 1        | 1.47%   |
| Gigabyte X570          | 1        | 1.47%   |
| Gigabyte P41-ES3G      | 1        | 1.47%   |
| Gigabyte H81M-S2PV     | 1        | 1.47%   |
| Gigabyte H81M-HD3      | 1        | 1.47%   |
| Gigabyte H61M-S2-B3    | 1        | 1.47%   |
| Gigabyte H61M-S1       | 1        | 1.47%   |
| Gigabyte GA-970A-DS3   | 1        | 1.47%   |
| Gigabyte GA-880GM-USB3 | 1        | 1.47%   |
| Gigabyte G41M-ES2L     | 1        | 1.47%   |
| Gigabyte EP43-UD3L     | 1        | 1.47%   |
| Gigabyte B550          | 1        | 1.47%   |
| Gigabyte B460MDS3HV2   | 1        | 1.47%   |
| Gigabyte B450M         | 1        | 1.47%   |
| Foxconn nT-330i        | 1        | 1.47%   |
| ECS GeForce7050M-M     | 1        | 1.47%   |
| Dell OptiPlex          | 1        | 1.47%   |
| Dell DM051             | 1        | 1.47%   |
| Biostar TB250-BTC      | 1        | 1.47%   |
| Biostar TA790GX        | 1        | 1.47%   |
| Biostar NF61D-A2       | 1        | 1.47%   |
| Biostar N68S3+         | 1        | 1.47%   |
| Biostar H61MGV3        | 1        | 1.47%   |
| Biostar H110MHC        | 1        | 1.47%   |
| Biostar GF8100         | 1        | 1.47%   |
| Biostar A960G+         | 1        | 1.47%   |
| Biostar A960D+V3       | 1        | 1.47%   |
| Biostar A58MD          | 1        | 1.47%   |
| ASUS TUF               | 1        | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 11       | 16.18%  |
| 2012 | 8        | 11.76%  |
| 2011 | 7        | 10.29%  |
| 2013 | 6        | 8.82%   |
| 2010 | 6        | 8.82%   |
| 2020 | 5        | 7.35%   |
| 2017 | 5        | 7.35%   |
| 2016 | 5        | 7.35%   |
| 2018 | 3        | 4.41%   |
| 2006 | 3        | 4.41%   |
| 2015 | 2        | 2.94%   |
| 2007 | 2        | 2.94%   |
| 2022 | 1        | 1.47%   |
| 2021 | 1        | 1.47%   |
| 2019 | 1        | 1.47%   |
| 2014 | 1        | 1.47%   |
| 2005 | 1        | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 68       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 67       | 98.53%  |
| Enabled  | 1        | 1.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 24       | 34.78%  |
| 8.01-16.0  | 15       | 21.74%  |
| 16.01-24.0 | 9        | 13.04%  |
| 4.01-8.0   | 7        | 10.14%  |
| 1.01-2.0   | 5        | 7.25%   |
| 32.01-64.0 | 4        | 5.8%    |
| 2.01-3.0   | 4        | 5.8%    |
| 0.51-1.0   | 1        | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 28       | 37.84%  |
| 0.51-1.0  | 23       | 31.08%  |
| 2.01-3.0  | 9        | 12.16%  |
| 4.01-8.0  | 6        | 8.11%   |
| 3.01-4.0  | 4        | 5.41%   |
| 0.01-0.5  | 3        | 4.05%   |
| 8.01-16.0 | 1        | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 50.72%  |
| 2      | 19       | 27.54%  |
| 3      | 10       | 14.49%  |
| 4      | 4        | 5.8%    |
| 0      | 1        | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 52.94%  |
| Yes       | 32       | 47.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 76.47%  |
| Yes       | 16       | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 88.24%  |
| Yes       | 8        | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Moldova | 68       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Chisinau  | 27       | 39.71%  |
| Tiraspol  | 24       | 35.29%  |
| Tighina   | 2        | 2.94%   |
| Straseni  | 2        | 2.94%   |
| Bălţi   | 2        | 2.94%   |
| Tintareni | 1        | 1.47%   |
| Singera   | 1        | 1.47%   |
| Rîbniţa | 1        | 1.47%   |
| Rezina    | 1        | 1.47%   |
| Lapusna   | 1        | 1.47%   |
| Ialoveni  | 1        | 1.47%   |
| Hincesti  | 1        | 1.47%   |
| Edineţ   | 1        | 1.47%   |
| Drochia   | 1        | 1.47%   |
| Cazanesti | 1        | 1.47%   |
| Căușeni | 1        | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 29     | 21.93%  |
| Seagate             | 20       | 22     | 17.54%  |
| WDC                 | 19       | 20     | 16.67%  |
| Toshiba             | 11       | 12     | 9.65%   |
| Hitachi             | 6        | 8      | 5.26%   |
| SPCC                | 5        | 6      | 4.39%   |
| Transcend           | 4        | 4      | 3.51%   |
| Kingston            | 4        | 4      | 3.51%   |
| Maxtor              | 3        | 4      | 2.63%   |
| Apacer              | 3        | 3      | 2.63%   |
| XPG                 | 1        | 1      | 0.88%   |
| Team                | 1        | 1      | 0.88%   |
| SK hynix            | 1        | 1      | 0.88%   |
| SanDisk             | 1        | 1      | 0.88%   |
| Phison              | 1        | 1      | 0.88%   |
| Patriot             | 1        | 1      | 0.88%   |
| Leven               | 1        | 1      | 0.88%   |
| Intel               | 1        | 1      | 0.88%   |
| HGST                | 1        | 1      | 0.88%   |
| GOODRAM             | 1        | 1      | 0.88%   |
| Goldkey             | 1        | 1      | 0.88%   |
| Gigabyte Technology | 1        | 2      | 0.88%   |
| Crucial             | 1        | 2      | 0.88%   |
| CHN25SATAS1         | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba DT01ACA050 500GB         | 4        | 3.33%   |
| Toshiba DT01ACA100 1TB           | 3        | 2.5%    |
| Samsung HD502HJ 500GB            | 3        | 2.5%    |
| Kingston SHFS37A120G 120GB SSD   | 3        | 2.5%    |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 1.67%   |
| Transcend TS64GSSD370S 64GB      | 2        | 1.67%   |
| Toshiba HDWD110 1TB              | 2        | 1.67%   |
| SPCC Solid State Disk 128GB      | 2        | 1.67%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.67%   |
| Seagate ST4000VM000-2AF166 4TB   | 2        | 1.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.67%   |
| Seagate ST1000DL002-9TT153 1TB   | 2        | 1.67%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.67%   |
| Samsung HD251HJ 249GB            | 2        | 1.67%   |
| Samsung HD082GJ 80GB             | 2        | 1.67%   |
| XPG NVMe SSD Drive 512GB         | 1        | 0.83%   |
| WDC WD800JD-22LSA0 80GB          | 1        | 0.83%   |
| WDC WD62PURZ-85B3AY0 6TB         | 1        | 0.83%   |
| WDC WD5000AZRZ-00HTKB0 500GB     | 1        | 0.83%   |
| WDC WD5000AUDX-63WNHY0 500GB     | 1        | 0.83%   |
| WDC WD5000AAKX-08ERMA0 500GB     | 1        | 0.83%   |
| WDC WD5000AAKS-75V0A0 500GB      | 1        | 0.83%   |
| WDC WD5000AAKS-00WWPA0 500GB     | 1        | 0.83%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 0.83%   |
| WDC WD5000AADS-56S9B1 500GB      | 1        | 0.83%   |
| WDC WD3200BPVT-24ZEST0 320GB     | 1        | 0.83%   |
| WDC WD3200AVJS-63B6A0 320GB      | 1        | 0.83%   |
| WDC WD2500AAKX-00U6AA0 250GB     | 1        | 0.83%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 1        | 0.83%   |
| WDC WD200EB-00CPF0 20GB          | 1        | 0.83%   |
| WDC WD1600BEVS-60RST0 160GB      | 1        | 0.83%   |
| WDC WD10SPZX-22Z10T1 1TB         | 1        | 0.83%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 0.83%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 0.83%   |
| Transcend TS256GSSD370S 256GB    | 1        | 0.83%   |
| Transcend TS128GSSD230S 128GB    | 1        | 0.83%   |
| Toshiba THNSN5256GPUK NVMe 256GB | 1        | 0.83%   |
| Toshiba MQ01ABD032 320GB         | 1        | 0.83%   |
| Team L5 LITE SSD 240GB           | 1        | 0.83%   |
| SPCC SSD162 56GB                 | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 22     | 25.97%  |
| WDC                 | 19       | 20     | 24.68%  |
| Samsung Electronics | 18       | 21     | 23.38%  |
| Toshiba             | 10       | 11     | 12.99%  |
| Hitachi             | 6        | 8      | 7.79%   |
| Maxtor              | 3        | 4      | 3.9%    |
| HGST                | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SPCC                | 5        | 6      | 17.86%  |
| Transcend           | 4        | 4      | 14.29%  |
| Kingston            | 4        | 4      | 14.29%  |
| Samsung Electronics | 3        | 3      | 10.71%  |
| Apacer              | 3        | 3      | 10.71%  |
| Team                | 1        | 1      | 3.57%   |
| SanDisk             | 1        | 1      | 3.57%   |
| Patriot             | 1        | 1      | 3.57%   |
| Leven               | 1        | 1      | 3.57%   |
| GOODRAM             | 1        | 1      | 3.57%   |
| Goldkey             | 1        | 1      | 3.57%   |
| Gigabyte Technology | 1        | 2      | 3.57%   |
| Crucial             | 1        | 2      | 3.57%   |
| CHN25SATAS1         | 1        | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 57       | 87     | 63.33%  |
| SSD  | 26       | 31     | 28.89%  |
| NVMe | 7        | 10     | 7.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 118    | 90.14%  |
| NVMe | 7        | 10     | 9.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 57       | 89     | 71.25%  |
| 0.51-1.0   | 13       | 19     | 16.25%  |
| 1.01-2.0   | 6        | 6      | 7.5%    |
| 3.01-4.0   | 3        | 3      | 3.75%   |
| 4.01-10.0  | 1        | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 15       | 21.13%  |
| 101-250        | 14       | 19.72%  |
| 51-100         | 13       | 18.31%  |
| 1-20           | 11       | 15.49%  |
| 501-1000       | 6        | 8.45%   |
| 21-50          | 5        | 7.04%   |
| More than 3000 | 2        | 2.82%   |
| 2001-3000      | 2        | 2.82%   |
| 1001-2000      | 2        | 2.82%   |
| Unknown        | 1        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 38       | 54.29%  |
| 21-50          | 10       | 14.29%  |
| 51-100         | 8        | 11.43%  |
| 101-250        | 4        | 5.71%   |
| 251-500        | 3        | 4.29%   |
| 501-1000       | 3        | 4.29%   |
| 1001-2000      | 2        | 2.86%   |
| More than 3000 | 1        | 1.43%   |
| Unknown        | 1        | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD082GJ 80GB  | 2        | 2      | 6.45%   |
| WDC WD800JD-22LSA0 80GB           | 1        | 1      | 3.23%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 3.23%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1        | 1      | 3.23%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1        | 1      | 3.23%   |
| WDC WD5000AADS-56S9B1 500GB       | 1        | 1      | 3.23%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1        | 1      | 3.23%   |
| WDC WD1600BEVS-60RST0 160GB       | 1        | 1      | 3.23%   |
| Toshiba MQ01ABD032 320GB          | 1        | 1      | 3.23%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 3.23%   |
| Team L5 LITE SSD 240GB            | 1        | 1      | 3.23%   |
| SPCC SSD162 120GB                 | 1        | 1      | 3.23%   |
| SPCC Solid State Disk 56GB        | 1        | 2      | 3.23%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 3.23%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1        | 1      | 3.23%   |
| Seagate ST3160023A 160GB          | 1        | 1      | 3.23%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 3.23%   |
| Seagate ST1000DL002-9TT153 1TB    | 1        | 1      | 3.23%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.23%   |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 3.23%   |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 3.23%   |
| Maxtor STM380215AS 80GB           | 1        | 1      | 3.23%   |
| Maxtor STM3160811AS 160GB         | 1        | 1      | 3.23%   |
| Maxtor STM3160211AS 160GB         | 1        | 1      | 3.23%   |
| Maxtor 4R120L0 128GB              | 1        | 1      | 3.23%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 3.23%   |
| Hitachi HTS545025B9A300 250GB     | 1        | 1      | 3.23%   |
| Hitachi HDT721010SLA360 1TB       | 1        | 2      | 3.23%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 3.23%   |
| Hitachi HDP725025GLA380 250GB     | 1        | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 23.33%  |
| Seagate             | 5        | 5      | 16.67%  |
| Samsung Electronics | 5        | 5      | 16.67%  |
| Hitachi             | 4        | 6      | 13.33%  |
| Maxtor              | 3        | 4      | 10%     |
| Toshiba             | 2        | 2      | 6.67%   |
| SPCC                | 2        | 3      | 6.67%   |
| Team                | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 26.92%  |
| Seagate             | 5        | 5      | 19.23%  |
| Samsung Electronics | 5        | 5      | 19.23%  |
| Hitachi             | 4        | 6      | 15.38%  |
| Maxtor              | 3        | 4      | 11.54%  |
| Toshiba             | 2        | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 29     | 84.62%  |
| SSD  | 4        | 5      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 33.33%  |
| Samsung Electronics HD322GJ 320GB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 37       | 60     | 45.12%  |
| Malfunc  | 26       | 34     | 31.71%  |
| Detected | 16       | 30     | 19.51%  |
| Failed   | 3        | 4      | 3.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 39       | 46.43%  |
| AMD                          | 22       | 26.19%  |
| Nvidia                       | 7        | 8.33%   |
| JMicron Technology           | 5        | 5.95%   |
| Samsung Electronics          | 4        | 4.76%   |
| ASMedia Technology           | 2        | 2.38%   |
| Toshiba America Info Systems | 1        | 1.19%   |
| SK hynix                     | 1        | 1.19%   |
| Phison Electronics           | 1        | 1.19%   |
| Marvell Technology Group     | 1        | 1.19%   |
| ADATA Technology             | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 8.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 8.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 4.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 4.07%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 4.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.44%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 2.44%   |
| Nvidia MCP61 IDE                                                                        | 3        | 2.44%   |
| JMicron JMB368 IDE controller                                                           | 3        | 2.44%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 2.44%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.44%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.63%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.63%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.81%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.81%   |
| Nvidia MCP79 SATA Controller                                                            | 1        | 0.81%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.81%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.81%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.81%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.81%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.81%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.81%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 0.81%   |
| Intel SSD 600P Series                                                                   | 1        | 0.81%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 48.35%  |
| IDE  | 38       | 41.76%  |
| NVMe | 7        | 7.69%   |
| RAID | 2        | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 40       | 58.82%  |
| AMD    | 28       | 41.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 2.94%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 2.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.94%   |
| AMD Phenom II X6 1055T Processor            | 2        | 2.94%   |
| AMD Athlon II X2 280 Processor              | 2        | 2.94%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.47%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.47%   |
| Intel Pentium D CPU 2.66GHz                 | 1        | 1.47%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 1.47%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1.47%   |
| Intel Pentium CPU G4620 @ 3.70GHz           | 1        | 1.47%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.47%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.47%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1        | 1.47%   |
| Intel Core i7-7820X CPU @ 3.60GHz           | 1        | 1.47%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1        | 1.47%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.47%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 1.47%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.47%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.47%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 1        | 1.47%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.47%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.47%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.47%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.47%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 1.47%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.47%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 1.47%   |
| Intel Celeron CPU G1630 @ 2.80GHz           | 1        | 1.47%   |
| Intel Celeron CPU E1200 @ 1.60GHz           | 1        | 1.47%   |
| Intel Celeron CPU 2.53GHz                   | 1        | 1.47%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 1.47%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 16.18%  |
| Intel Pentium           | 7        | 10.29%  |
| AMD Athlon II X2        | 6        | 8.82%   |
| Intel Core i3           | 5        | 7.35%   |
| Intel Core i7           | 4        | 5.88%   |
| AMD Athlon 64 X2        | 4        | 5.88%   |
| Intel Celeron           | 3        | 4.41%   |
| Intel Pentium D         | 2        | 2.94%   |
| Intel Core 2 Duo        | 2        | 2.94%   |
| AMD Ryzen 7             | 2        | 2.94%   |
| AMD Ryzen 5             | 2        | 2.94%   |
| AMD Ryzen 3             | 2        | 2.94%   |
| AMD Phenom II X6        | 2        | 2.94%   |
| AMD FX                  | 2        | 2.94%   |
| AMD Athlon II X4        | 2        | 2.94%   |
| AMD A4                  | 2        | 2.94%   |
| Other                   | 1        | 1.47%   |
| Intel Pentium Dual-Core | 1        | 1.47%   |
| Intel Pentium Dual      | 1        | 1.47%   |
| Intel Pentium 4         | 1        | 1.47%   |
| Intel Core 2 Quad       | 1        | 1.47%   |
| Intel Atom              | 1        | 1.47%   |
| AMD Phenom II X4        | 1        | 1.47%   |
| AMD Athlon              | 1        | 1.47%   |
| AMD A8                  | 1        | 1.47%   |
| AMD A10                 | 1        | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 33       | 47.83%  |
| 4       | 22       | 31.88%  |
| 6       | 4        | 5.8%    |
| 8       | 3        | 4.35%   |
| 1       | 3        | 4.35%   |
| Unknown | 3        | 4.35%   |
| 10      | 1        | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 42       | 60.87%  |
| 2       | 24       | 34.78%  |
| Unknown | 3        | 4.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 68       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 14.71%  |
| 0x010000c8 | 6        | 8.82%   |
| 0x906e9    | 4        | 5.88%   |
| 0x506e3    | 4        | 5.88%   |
| 0x306c3    | 4        | 5.88%   |
| 0x306a9    | 4        | 5.88%   |
| 0x206a7    | 4        | 5.88%   |
| 0x1067a    | 3        | 4.41%   |
| 0xf47      | 2        | 2.94%   |
| 0x6fd      | 2        | 2.94%   |
| 0x08701021 | 2        | 2.94%   |
| 0x010000dc | 2        | 2.94%   |
| 0xf49      | 1        | 1.47%   |
| 0xf41      | 1        | 1.47%   |
| 0xa0655    | 1        | 1.47%   |
| 0x90672    | 1        | 1.47%   |
| 0x50654    | 1        | 1.47%   |
| 0x406c3    | 1        | 1.47%   |
| 0x20655    | 1        | 1.47%   |
| 0x106e5    | 1        | 1.47%   |
| 0x106c2    | 1        | 1.47%   |
| 0x10676    | 1        | 1.47%   |
| 0x08600106 | 1        | 1.47%   |
| 0x08108109 | 1        | 1.47%   |
| 0x08101102 | 1        | 1.47%   |
| 0x08001138 | 1        | 1.47%   |
| 0x06003106 | 1        | 1.47%   |
| 0x06000852 | 1        | 1.47%   |
| 0x0600063e | 1        | 1.47%   |
| 0x03000027 | 1        | 1.47%   |
| 0x03000025 | 1        | 1.47%   |
| 0x010000db | 1        | 1.47%   |
| 0x010000b6 | 1        | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| K10              | 11       | 16.18%  |
| Skylake          | 6        | 8.82%   |
| Haswell          | 6        | 8.82%   |
| Zen 2            | 4        | 5.88%   |
| SandyBridge      | 4        | 5.88%   |
| Penryn           | 4        | 5.88%   |
| NetBurst         | 4        | 5.88%   |
| KabyLake         | 4        | 5.88%   |
| K8 Hammer        | 4        | 5.88%   |
| IvyBridge        | 4        | 5.88%   |
| Zen              | 2        | 2.94%   |
| Piledriver       | 2        | 2.94%   |
| K10 Llano        | 2        | 2.94%   |
| Core             | 2        | 2.94%   |
| Zen+             | 1        | 1.47%   |
| Westmere         | 1        | 1.47%   |
| Steamroller      | 1        | 1.47%   |
| Silvermont       | 1        | 1.47%   |
| Nehalem          | 1        | 1.47%   |
| CometLake        | 1        | 1.47%   |
| Bulldozer        | 1        | 1.47%   |
| Bonnell          | 1        | 1.47%   |
| Alderlake Hybrid | 1        | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 30       | 42.86%  |
| AMD    | 23       | 32.86%  |
| Intel  | 17       | 24.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 4.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 4.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 2.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 2.7%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 2.7%    |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 2.7%    |
| Intel HD Graphics 630                                                                    | 2        | 2.7%    |
| Intel HD Graphics 530                                                                    | 2        | 2.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.7%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 2.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.35%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.35%   |
| Nvidia GT200b [GeForce GTX 285]                                                          | 1        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.35%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1        | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.35%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.35%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 1.35%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 1.35%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.35%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.35%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 1.35%   |
| Nvidia C79 [ION]                                                                         | 1        | 1.35%   |
| Nvidia C77 [GeForce 8100 / nForce 720a]                                                  | 1        | 1.35%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.35%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.35%   |
| Intel HD Graphics 510                                                                    | 1        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.35%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.35%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 1.35%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 30       | 42.86%  |
| 1 x AMD    | 19       | 27.14%  |
| 1 x Intel  | 17       | 24.29%  |
| 2 x AMD    | 4        | 5.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 73.61%  |
| Proprietary | 12       | 16.67%  |
| Unknown     | 7        | 9.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 28.77%  |
| 1.01-2.0   | 15       | 20.55%  |
| 0.01-0.5   | 15       | 20.55%  |
| 0.51-1.0   | 10       | 13.7%   |
| 3.01-4.0   | 8        | 10.96%  |
| 5.01-6.0   | 2        | 2.74%   |
| 7.01-8.0   | 1        | 1.37%   |
| 2.01-3.0   | 1        | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 26.87%  |
| Goldstar             | 14       | 20.9%   |
| Philips              | 8        | 11.94%  |
| Acer                 | 7        | 10.45%  |
| Hewlett-Packard      | 4        | 5.97%   |
| Dell                 | 4        | 5.97%   |
| AOC                  | 3        | 4.48%   |
| ViewSonic            | 1        | 1.49%   |
| Toshiba              | 1        | 1.49%   |
| Plain Tree Systems   | 1        | 1.49%   |
| Medion               | 1        | 1.49%   |
| KTC                  | 1        | 1.49%   |
| HannStar             | 1        | 1.49%   |
| BenQ                 | 1        | 1.49%   |
| ASUSTek Computer     | 1        | 1.49%   |
| Ancor Communications | 1        | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch   | 2        | 2.9%    |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 2        | 2.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 2        | 2.9%    |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch                 | 1        | 1.45%   |
| Toshiba TV TSB0108 1920x540 698x393mm 31.5-inch                        | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch   | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 380x300mm 19.1-inch   | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch    | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch   | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch   | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 1.45%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch      | 1        | 1.45%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch       | 1        | 1.45%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch      | 1        | 1.45%   |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch      | 1        | 1.45%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1        | 1.45%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 1.45%   |
| Samsung Electronics S/T 77E/76E STN0005 1280x1024 312x234mm 15.4-inch  | 1        | 1.45%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.45%   |
| Plain Tree Systems XAP-192i PTS03D5 1280x1024 376x301mm 19.0-inch      | 1        | 1.45%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch               | 1        | 1.45%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch                | 1        | 1.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1        | 1.45%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch               | 1        | 1.45%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 1.45%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch                | 1        | 1.45%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 1.45%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                      | 1        | 1.45%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 1        | 1.45%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                 | 1        | 1.45%   |
| KTC 32T72-H-AN KTC3200 1360x768 698x392mm 31.5-inch                    | 1        | 1.45%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1        | 1.45%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.45%   |
| HannStar HW223 HSD5B10 1680x1050 433x271mm 20.1-inch                   | 1        | 1.45%   |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch                   | 1        | 1.45%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                    | 1        | 1.45%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                   | 1        | 1.45%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 37.31%  |
| 1280x1024 (SXGA)   | 11       | 16.42%  |
| 1600x900 (HD+)     | 5        | 7.46%   |
| 1440x900 (WXGA+)   | 5        | 7.46%   |
| 1366x768 (WXGA)    | 5        | 7.46%   |
| 2560x1440 (QHD)    | 4        | 5.97%   |
| 1680x1050 (WSXGA+) | 4        | 5.97%   |
| 2560x1080          | 2        | 2.99%   |
| 1600x1200          | 2        | 2.99%   |
| 1024x768 (XGA)     | 2        | 2.99%   |
| 1920x540           | 1        | 1.49%   |
| 1360x768           | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 10       | 14.71%  |
| 23     | 9        | 13.24%  |
| 24     | 8        | 11.76%  |
| 20     | 8        | 11.76%  |
| 27     | 6        | 8.82%   |
| 21     | 6        | 8.82%   |
| 18     | 6        | 8.82%   |
| 15     | 6        | 8.82%   |
| 17     | 5        | 7.35%   |
| 34     | 2        | 2.94%   |
| 72     | 1        | 1.47%   |
| 32     | 1        | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 25       | 37.31%  |
| 501-600     | 22       | 32.84%  |
| 301-350     | 11       | 16.42%  |
| 351-400     | 5        | 7.46%   |
| 701-800     | 3        | 4.48%   |
| 1501-2000   | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 39       | 60%     |
| 5/4   | 9        | 13.85%  |
| 4/3   | 7        | 10.77%  |
| 16/10 | 7        | 10.77%  |
| 21/9  | 2        | 3.08%   |
| 3/2   | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 32.35%  |
| 151-200        | 20       | 29.41%  |
| 141-150        | 10       | 14.71%  |
| 301-350        | 6        | 8.82%   |
| 111-120        | 4        | 5.88%   |
| 351-500        | 3        | 4.41%   |
| 101-110        | 2        | 2.94%   |
| More than 1000 | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 77.61%  |
| 101-120 | 13       | 19.4%   |
| 1-50    | 1        | 1.49%   |
| 121-160 | 1        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 64       | 94.12%  |
| 2     | 3        | 4.41%   |
| 0     | 1        | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 47       | 58.02%  |
| Intel                    | 10       | 12.35%  |
| Qualcomm Atheros         | 8        | 9.88%   |
| Nvidia                   | 6        | 7.41%   |
| Xiaomi                   | 1        | 1.23%   |
| TP-Link                  | 1        | 1.23%   |
| Ralink                   | 1        | 1.23%   |
| Mercucys                 | 1        | 1.23%   |
| MediaTek                 | 1        | 1.23%   |
| Marvell Technology Group | 1        | 1.23%   |
| D-Link System            | 1        | 1.23%   |
| D-Link                   | 1        | 1.23%   |
| Broadcom                 | 1        | 1.23%   |
| ASIX Electronics         | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 42       | 47.73%  |
| Nvidia MCP61 Ethernet                                                  | 3        | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 2.27%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 2.27%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.14%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.14%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 1.14%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.14%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 1.14%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 1.14%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.14%   |
| Nvidia MCP77 Ethernet                                                  | 1        | 1.14%   |
| Nvidia MCP67 Ethernet                                                  | 1        | 1.14%   |
| Nvidia MCP55 Ethernet                                                  | 1        | 1.14%   |
| Mercucys 802.11n NIC                                                   | 1        | 1.14%   |
| MediaTek TECNO Pouvoir 3 Air                                           | 1        | 1.14%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 1.14%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.14%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.14%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.14%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.14%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.14%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 1.14%   |
| D-Link DWA-137 Wireless N High-Gain Adapter [Ralink RT5372]            | 1        | 1.14%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 25%     |
| Qualcomm Atheros      | 4        | 25%     |
| Intel                 | 2        | 12.5%   |
| TP-Link               | 1        | 6.25%   |
| Ralink                | 1        | 6.25%   |
| Mercucys              | 1        | 6.25%   |
| D-Link System         | 1        | 6.25%   |
| D-Link                | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 2        | 12.5%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 6.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 6.25%   |
| Realtek 802.11ac NIC                                                   | 1        | 6.25%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 6.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 6.25%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 6.25%   |
| Mercucys 802.11n NIC                                                   | 1        | 6.25%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 6.25%   |
| D-Link DWA-137 Wireless N High-Gain Adapter [Ralink RT5372]            | 1        | 6.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 47       | 66.2%   |
| Intel                    | 9        | 12.68%  |
| Nvidia                   | 6        | 8.45%   |
| Qualcomm Atheros         | 5        | 7.04%   |
| Xiaomi                   | 1        | 1.41%   |
| MediaTek                 | 1        | 1.41%   |
| Marvell Technology Group | 1        | 1.41%   |
| ASIX Electronics         | 1        | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42       | 58.33%  |
| Nvidia MCP61 Ethernet                                             | 3        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.39%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.39%   |
| Nvidia MCP67 Ethernet                                             | 1        | 1.39%   |
| Nvidia MCP55 Ethernet                                             | 1        | 1.39%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1        | 1.39%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.39%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.39%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 80.95%  |
| WiFi     | 16       | 19.05%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 89.55%  |
| WiFi     | 7        | 10.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 82.35%  |
| 2     | 12       | 17.65%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 95.59%  |
| Yes  | 3        | 4.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 2        | 25%     |
| Cambridge Silicon Radio    | 2        | 25%     |
| Integrated System Solution | 1        | 12.5%   |
| IMC Networks               | 1        | 12.5%   |
| Broadcom                   | 1        | 12.5%   |
| ASUSTek Computer           | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 25%     |
| Integrated System Solution Bluetooth Device         | 1        | 12.5%   |
| IMC Networks Bluetooth Radio                        | 1        | 12.5%   |
| Broadcom BCM92045B3 ROM                             | 1        | 12.5%   |
| ASUS BCM20702A0                                     | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 38       | 35.85%  |
| AMD                       | 30       | 28.3%   |
| Nvidia                    | 28       | 26.42%  |
| Creative Labs             | 2        | 1.89%   |
| Texas Instruments         | 1        | 0.94%   |
| SteelSeries ApS           | 1        | 0.94%   |
| Shenzhen Rapoo Technology | 1        | 0.94%   |
| Sennheiser Communications | 1        | 0.94%   |
| Plantronics               | 1        | 0.94%   |
| Kingston Technology       | 1        | 0.94%   |
| GN Netcom                 | 1        | 0.94%   |
| C-Media Electronics       | 1        | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 11       | 9.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 5%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 3.33%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 3.33%   |
| AMD FCH Azalia Controller                                                         | 4        | 3.33%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 2.5%    |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.5%    |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 2.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 2.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.67%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.83%   |
| SteelSeries ApS SteelSeries Arctis 7                                              | 1        | 0.83%   |
| Shenzhen Rapoo Technology Wireless Audio                                          | 1        | 0.83%   |
| Sennheiser Communications SC60 for Lync                                           | 1        | 0.83%   |
| Plantronics Audio 628 USB                                                         | 1        | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.83%   |
| Nvidia MCP67 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.83%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 0.83%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 28       | 43.75%  |
| Kingston            | 10       | 15.63%  |
| SK hynix            | 2        | 3.13%   |
| Samsung Electronics | 2        | 3.13%   |
| Patriot             | 2        | 3.13%   |
| Micron Technology   | 2        | 3.13%   |
| GOODRAM             | 2        | 3.13%   |
| G.Skill             | 2        | 3.13%   |
| Transcend           | 1        | 1.56%   |
| Team                | 1        | 1.56%   |
| Silicon Power       | 1        | 1.56%   |
| SGS/Thomson         | 1        | 1.56%   |
| Nanya Technology    | 1        | 1.56%   |
| Hexon               | 1        | 1.56%   |
| Goldkey             | 1        | 1.56%   |
| Elpida              | 1        | 1.56%   |
| Crucial             | 1        | 1.56%   |
| Corsair             | 1        | 1.56%   |
| AVEXIR              | 1        | 1.56%   |
| Apacer              | 1        | 1.56%   |
| A-DATA Technology   | 1        | 1.56%   |
| Unknown             | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s               | 3        | 4%      |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 3        | 4%      |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2        | 2.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 2        | 2.67%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 2        | 2.67%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 2        | 2.67%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s               | 2        | 2.67%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 2        | 2.67%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 1.33%   |
| Unknown RAM Module 512MB DIMM SDRAM                       | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM 667MT/s                       | 1        | 1.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 1.33%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s              | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s               | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM                            | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                | 1        | 1.33%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 1.33%   |
| Unknown RAM ..E-D3U1600M/4G 4096MB DIMM DDR3 800MT/s      | 1        | 1.33%   |
| Transcend RAM JM1333KLH-4G 4GB DIMM DDR3 1333MT/s         | 1        | 1.33%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                | 1        | 1.33%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 400MT/s       | 1        | 1.33%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s       | 1        | 1.33%   |
| SK hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR2 400MT/s    | 1        | 1.33%   |
| Silicon Power RAM DCLT2GN568S 2048MB DIMM DDR3 1600MT/s   | 1        | 1.33%   |
| SGS/Thomson RAM GR800S264L5/2G 2048MB DIMM SDRAM 2048MT/s | 1        | 1.33%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s    | 1        | 1.33%   |
| Samsung RAM M3 78T6553CZ3-CD5 512MB DIMM DDR 533MT/s      | 1        | 1.33%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s           | 1        | 1.33%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 1.33%   |
| Nanya RAM M2F2G64CB88B7N-CG 2048MB DIMM 1333MT/s          | 1        | 1.33%   |
| Micron RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 27.12%  |
| DDR3    | 15       | 25.42%  |
| Unknown | 11       | 18.64%  |
| DDR2    | 8        | 13.56%  |
| SDRAM   | 6        | 10.17%  |
| DDR     | 3        | 5.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 57       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 24       | 34.78%  |
| 4096  | 20       | 28.99%  |
| 8192  | 10       | 14.49%  |
| 1024  | 7        | 10.14%  |
| 16384 | 5        | 7.25%   |
| 512   | 2        | 2.9%    |
| 32768 | 1        | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 13       | 20.31%  |
| 1600    | 11       | 17.19%  |
| 800     | 7        | 10.94%  |
| 2133    | 5        | 7.81%   |
| 2667    | 3        | 4.69%   |
| 667     | 3        | 4.69%   |
| 333     | 3        | 4.69%   |
| Unknown | 3        | 4.69%   |
| 3600    | 2        | 3.13%   |
| 3200    | 2        | 3.13%   |
| 3000    | 2        | 3.13%   |
| 2933    | 2        | 3.13%   |
| 3500    | 1        | 1.56%   |
| 2800    | 1        | 1.56%   |
| 2666    | 1        | 1.56%   |
| 2400    | 1        | 1.56%   |
| 2048    | 1        | 1.56%   |
| 1400    | 1        | 1.56%   |
| 533     | 1        | 1.56%   |
| 400     | 1        | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 50%     |
| Seiko Epson     | 1        | 25%     |
| Canon           | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1        | 25%     |
| HP LaserJet M14-M17                   | 1        | 25%     |
| HP LaserJet 1020                      | 1        | 25%     |
| Canon LaserShot LBP-1120 Printer      | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 700F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 4        | 20%     |
| Microdia                    | 3        | 15%     |
| Z-Star Microelectronics     | 2        | 10%     |
| KYE Systems (Mouse Systems) | 2        | 10%     |
| YGTek                       | 1        | 5%      |
| Trust                       | 1        | 5%      |
| Samsung Electronics         | 1        | 5%      |
| Pixart Imaging              | 1        | 5%      |
| Microsoft                   | 1        | 5%      |
| Genesys Logic               | 1        | 5%      |
| GEMBIRD                     | 1        | 5%      |
| Cubeternet                  | 1        | 5%      |
| Aveo Technology             | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Microdia Camera                           | 3        | 15%     |
| Z-Star Venus USB2.0 Camera                | 2        | 10%     |
| Logitech Webcam C270                      | 2        | 10%     |
| YGTek Webcam                              | 1        | 5%      |
| Trust Full HD Webcam                      | 1        | 5%      |
| Samsung Galaxy (PTP mode)                 | 1        | 5%      |
| Pixart Imaging GE 1.3 MP MiniCam Pro      | 1        | 5%      |
| Microsoft LifeCam VX-700                  | 1        | 5%      |
| Logitech Webcam C170                      | 1        | 5%      |
| Logitech Webcam C110                      | 1        | 5%      |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5%      |
| KYE Systems (Mouse Systems) eFace 2025    | 1        | 5%      |
| Genesys Logic U2 EE Cam                   | 1        | 5%      |
| GEMBIRD USB2.0 PC CAMERA                  | 1        | 5%      |
| Cubeternet USB2.0 Camera                  | 1        | 5%      |
| Aveo Camera                               | 1        | 5%      |

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
| 0     | 61       | 85.92%  |
| 1     | 10       | 14.08%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 8        | 80%     |
| Net/wireless  | 1        | 10%     |
| Camera        | 1        | 10%     |

