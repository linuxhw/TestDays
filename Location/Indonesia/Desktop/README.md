Linux in Indonesia - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 730

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H110                        | [329a7cfb8a](https://linux-hardware.org/?probe=329a7cfb8a) | Dec 30, 2025 |
| ASRock        | H310CM-HDV                  | [25f0a879bb](https://linux-hardware.org/?probe=25f0a879bb) | Dec 29, 2025 |
| Gigabyte      | B550M DS3H                  | [58bb579875](https://linux-hardware.org/?probe=58bb579875) | Dec 28, 2025 |
| HP            | 3397                        | [d21a114362](https://linux-hardware.org/?probe=d21a114362) | Dec 28, 2025 |
| Intel         | H81                         | [514c6a7933](https://linux-hardware.org/?probe=514c6a7933) | Dec 25, 2025 |
| Intel         | H61                         | [a996c59bd4](https://linux-hardware.org/?probe=a996c59bd4) | Dec 25, 2025 |
| Gigabyte      | H81M-DS2                    | [48f1ce3c05](https://linux-hardware.org/?probe=48f1ce3c05) | Dec 24, 2025 |
| HP            | 1495                        | [672633acf3](https://linux-hardware.org/?probe=672633acf3) | Dec 24, 2025 |
| ASRock        | B460M Steel Legend          | [176f88f86e](https://linux-hardware.org/?probe=176f88f86e) | Dec 20, 2025 |
| ASUSTek       | H61M-C                      | [44829ff4b8](https://linux-hardware.org/?probe=44829ff4b8) | Dec 19, 2025 |
| Gigabyte      | H61M-D2P-B3                 | [cafc2c974d](https://linux-hardware.org/?probe=cafc2c974d) | Dec 16, 2025 |
| AISURIX       | H81 Motherboard V2.0        | [3bcae0d33b](https://linux-hardware.org/?probe=3bcae0d33b) | Dec 14, 2025 |
| Gigabyte      | 965P-DS3                    | [3ed3880244](https://linux-hardware.org/?probe=3ed3880244) | Dec 13, 2025 |
| Gigabyte      | G41M-Combo                  | [b6daa2fff5](https://linux-hardware.org/?probe=b6daa2fff5) | Dec 11, 2025 |
| ASUSTek       | H81M-C                      | [dcdc41b589](https://linux-hardware.org/?probe=dcdc41b589) | Dec 09, 2025 |
| HP            | 8597                        | [d52f1722fd](https://linux-hardware.org/?probe=d52f1722fd) | Dec 08, 2025 |
| HP            | 8597                        | [30ed22e915](https://linux-hardware.org/?probe=30ed22e915) | Dec 08, 2025 |
| Gigabyte      | GA-H110M-H-CF               | [4c446050d7](https://linux-hardware.org/?probe=4c446050d7) | Dec 08, 2025 |
| MSI           | B250M PRO-VDH               | [1ae1dc130c](https://linux-hardware.org/?probe=1ae1dc130c) | Dec 06, 2025 |
| ASRock        | FM2A68M-HD+                 | [0c1c1825e3](https://linux-hardware.org/?probe=0c1c1825e3) | Dec 06, 2025 |
| ASRock        | B550M Pro4                  | [233048ee4b](https://linux-hardware.org/?probe=233048ee4b) | Dec 05, 2025 |
| ASRock        | B550M Pro4                  | [b206dfea93](https://linux-hardware.org/?probe=b206dfea93) | Dec 05, 2025 |
| ASUSTek       | P5G41T-M LX                 | [6e26cc8f0b](https://linux-hardware.org/?probe=6e26cc8f0b) | Dec 05, 2025 |
| Intel         | H55                         | [64547cb270](https://linux-hardware.org/?probe=64547cb270) | Nov 24, 2025 |
| Intel         | H55                         | [03919b1a0c](https://linux-hardware.org/?probe=03919b1a0c) | Nov 22, 2025 |
| ASRock        | FM2A68M-DG3+                | [b3cefcb6a7](https://linux-hardware.org/?probe=b3cefcb6a7) | Nov 20, 2025 |
| Lenovo        | ThinkCentre Edge 71z 756... | [f53fa15a0e](https://linux-hardware.org/?probe=f53fa15a0e) | Nov 17, 2025 |
| ASUSTek       | Z97-A                       | [f6694986c9](https://linux-hardware.org/?probe=f6694986c9) | Nov 13, 2025 |
| venomRX       | H110 Ver:2.3                | [2348395742](https://linux-hardware.org/?probe=2348395742) | Nov 10, 2025 |
| Gigabyte      | H610M K DDR4                | [bff6aa9159](https://linux-hardware.org/?probe=bff6aa9159) | Nov 04, 2025 |
| Biostar       | H61MLV2                     | [0734a3ade7](https://linux-hardware.org/?probe=0734a3ade7) | Oct 30, 2025 |
| ASRock        | AB350 Pro4                  | [682ad03729](https://linux-hardware.org/?probe=682ad03729) | Oct 30, 2025 |
| ASUSTek       | P8H61-M LX R2.0             | [c5faaa4ca3](https://linux-hardware.org/?probe=c5faaa4ca3) | Oct 29, 2025 |
| wolfNfox c... | H55MXV-LE                   | [135c10fb45](https://linux-hardware.org/?probe=135c10fb45) | Oct 29, 2025 |
| MSI           | H310M PRO-VD                | [5cef1d2379](https://linux-hardware.org/?probe=5cef1d2379) | Oct 21, 2025 |
| Intel         | H55                         | [595a9670e0](https://linux-hardware.org/?probe=595a9670e0) | Oct 20, 2025 |
| ASRock        | A320M-HDV R4.0              | [3fef4bd4f3](https://linux-hardware.org/?probe=3fef4bd4f3) | Oct 17, 2025 |
| Acer          | Veriton X2610               | [09c0b8ea84](https://linux-hardware.org/?probe=09c0b8ea84) | Oct 09, 2025 |
| ASUSTek       | P8Z77-V DELUXE              | [14fdc78a7b](https://linux-hardware.org/?probe=14fdc78a7b) | Oct 07, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [5aa5cce5cd](https://linux-hardware.org/?probe=5aa5cce5cd) | Oct 02, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [1d16dda120](https://linux-hardware.org/?probe=1d16dda120) | Oct 01, 2025 |
| ASUSTek       | PRIME H510M-K R2.0          | [cb9b82619e](https://linux-hardware.org/?probe=cb9b82619e) | Sep 30, 2025 |
| ASRock        | X300M-STX                   | [9e206fc7cd](https://linux-hardware.org/?probe=9e206fc7cd) | Sep 30, 2025 |
| Dell          | 0JP3NX A01                  | [e9b36eaceb](https://linux-hardware.org/?probe=e9b36eaceb) | Sep 28, 2025 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [34d252367d](https://linux-hardware.org/?probe=34d252367d) | Sep 26, 2025 |
| ASUSTek       | M5A78L-M LE/USB3            | [213bfbf41e](https://linux-hardware.org/?probe=213bfbf41e) | Sep 26, 2025 |
| ASUSTek       | M5A78L-M LE/USB3            | [c666c6e75e](https://linux-hardware.org/?probe=c666c6e75e) | Sep 26, 2025 |
| ASRock        | FM2A68M-DG3+                | [a00b5767de](https://linux-hardware.org/?probe=a00b5767de) | Sep 25, 2025 |
| Gigabyte      | G31M-S2L                    | [62cd36d091](https://linux-hardware.org/?probe=62cd36d091) | Sep 24, 2025 |
| Gigabyte      | G31M-S2L                    | [8c8c16ac10](https://linux-hardware.org/?probe=8c8c16ac10) | Sep 24, 2025 |
| Gigabyte      | H61M-S2P-B3                 | [66f28131b4](https://linux-hardware.org/?probe=66f28131b4) | Sep 14, 2025 |
| Huanan        | X79 V2.5 249PC              | [8cd7c91d90](https://linux-hardware.org/?probe=8cd7c91d90) | Sep 14, 2025 |
| Huanan        | X79 V2.5 249PC              | [ecfd63e31b](https://linux-hardware.org/?probe=ecfd63e31b) | Sep 08, 2025 |
| OEM           | X79G                        | [5958169308](https://linux-hardware.org/?probe=5958169308) | Sep 04, 2025 |
| Gigabyte      | GA-880GM-UD2H               | [8e741cb158](https://linux-hardware.org/?probe=8e741cb158) | Sep 01, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [74c9a329e3](https://linux-hardware.org/?probe=74c9a329e3) | Aug 26, 2025 |
| Gigabyte      | EG45M-UD2H                  | [fe37eae13a](https://linux-hardware.org/?probe=fe37eae13a) | Aug 25, 2025 |
| ECS           | H81H3-M4                    | [68017db36d](https://linux-hardware.org/?probe=68017db36d) | Aug 20, 2025 |
| Biostar       | H110MH PRO D4               | [17ec26f1c3](https://linux-hardware.org/?probe=17ec26f1c3) | Aug 18, 2025 |
| ASRock        | X600-ITX                    | [ded4cdf036](https://linux-hardware.org/?probe=ded4cdf036) | Aug 16, 2025 |
| Biostar       | G41D3+                      | [0fa7f0d0df](https://linux-hardware.org/?probe=0fa7f0d0df) | Aug 15, 2025 |
| ASRock        | H97M-ITX/ac                 | [d040318175](https://linux-hardware.org/?probe=d040318175) | Aug 15, 2025 |
| HP            | 1589                        | [a8b28baa8a](https://linux-hardware.org/?probe=a8b28baa8a) | Aug 12, 2025 |
| Biostar       | NM70I-1037U                 | [371ec96c61](https://linux-hardware.org/?probe=371ec96c61) | Aug 07, 2025 |
| ASRock        | X570 PG Velocita            | [7877442c7b](https://linux-hardware.org/?probe=7877442c7b) | Aug 07, 2025 |
| AZW           | GK55                        | [f01ba6fff6](https://linux-hardware.org/?probe=f01ba6fff6) | Aug 02, 2025 |
| ECS           | H81H3-M4                    | [a4ea413b68](https://linux-hardware.org/?probe=a4ea413b68) | Jul 31, 2025 |
| Intel         | H81                         | [e273068f88](https://linux-hardware.org/?probe=e273068f88) | Jul 20, 2025 |
| Lenovo        | ThinkCentre M80 7493CTO     | [95d8736416](https://linux-hardware.org/?probe=95d8736416) | Jul 05, 2025 |
| Lenovo        | ThinkCentre M80 7493CTO     | [a3122f28fe](https://linux-hardware.org/?probe=a3122f28fe) | Jul 05, 2025 |
| Unknown       | G41 Series                  | [d1ececac79](https://linux-hardware.org/?probe=d1ececac79) | Jul 04, 2025 |
| ASRock        | B450M-HDV R4.0              | [cf996d03fd](https://linux-hardware.org/?probe=cf996d03fd) | Jul 04, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [243d96316d](https://linux-hardware.org/?probe=243d96316d) | Jun 27, 2025 |
| Dell          | 0M9KCM A02                  | [78f99f574d](https://linux-hardware.org/?probe=78f99f574d) | Jun 22, 2025 |
| Unknown       | Unknown                     | [cc3ce164fd](https://linux-hardware.org/?probe=cc3ce164fd) | Jun 22, 2025 |
| Unknown       | Unknown                     | [7fe3380ec2](https://linux-hardware.org/?probe=7fe3380ec2) | Jun 19, 2025 |
| Minix         | H61M-USB3 V1.2              | [088e1ba23e](https://linux-hardware.org/?probe=088e1ba23e) | Jun 18, 2025 |
| MSI           | MAG B550M MORTAR WIFI       | [24cf734da2](https://linux-hardware.org/?probe=24cf734da2) | Jun 17, 2025 |
| ASRock        | A320M-HDV                   | [bae2e7d24c](https://linux-hardware.org/?probe=bae2e7d24c) | Jun 17, 2025 |
| Dell          | 0GY6Y8 A00                  | [6ac5a9b0a1](https://linux-hardware.org/?probe=6ac5a9b0a1) | Jun 16, 2025 |
| ASUSTek       | P5G41T-M LX                 | [f4ded16ac9](https://linux-hardware.org/?probe=f4ded16ac9) | Jun 16, 2025 |
| ASRock        | A55M-DGS                    | [aa8d71e629](https://linux-hardware.org/?probe=aa8d71e629) | Jun 15, 2025 |
| ASRock        | A55M-DGS                    | [a05e676e6b](https://linux-hardware.org/?probe=a05e676e6b) | Jun 15, 2025 |
| ASRock        | X600M-STX                   | [6c8adb7e17](https://linux-hardware.org/?probe=6c8adb7e17) | Jun 14, 2025 |
| HP            | 2B12                        | [9db1d09a0c](https://linux-hardware.org/?probe=9db1d09a0c) | Jun 14, 2025 |
| Intel         | H81                         | [52fc48d200](https://linux-hardware.org/?probe=52fc48d200) | Jun 14, 2025 |
| Intel         | H81                         | [3ceefa5484](https://linux-hardware.org/?probe=3ceefa5484) | Jun 14, 2025 |
| HP            | 2B12                        | [9104ec5154](https://linux-hardware.org/?probe=9104ec5154) | Jun 13, 2025 |
| MSI           | H61M-P20                    | [7f9cdd1a0a](https://linux-hardware.org/?probe=7f9cdd1a0a) | Jun 12, 2025 |
| Gigabyte      | B550M DS3H                  | [0f94470fba](https://linux-hardware.org/?probe=0f94470fba) | Jun 11, 2025 |
| Gigabyte      | H81M-DS2                    | [5d2dd59bb6](https://linux-hardware.org/?probe=5d2dd59bb6) | Jun 11, 2025 |
| MSI           | A520M PRO                   | [f0ae8405e4](https://linux-hardware.org/?probe=f0ae8405e4) | Jun 09, 2025 |
| MSI           | A520M PRO                   | [0c51e08e21](https://linux-hardware.org/?probe=0c51e08e21) | Jun 08, 2025 |
| ASUSTek       | P8Z68-M PRO                 | [e69221ece9](https://linux-hardware.org/?probe=e69221ece9) | Jun 07, 2025 |
| MSI           | A520M-A PRO                 | [466c464e29](https://linux-hardware.org/?probe=466c464e29) | Jun 05, 2025 |
| MSI           | A520M-A PRO                 | [78c1647ec6](https://linux-hardware.org/?probe=78c1647ec6) | Jun 05, 2025 |
| Gigabyte      | H81M-DS2                    | [62a89f4408](https://linux-hardware.org/?probe=62a89f4408) | Jun 04, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [96452e46ed](https://linux-hardware.org/?probe=96452e46ed) | May 25, 2025 |
| Gigabyte      | Z68XP-UD3                   | [aa2f9c861b](https://linux-hardware.org/?probe=aa2f9c861b) | May 24, 2025 |
| Gigabyte      | EP31-DS3L                   | [34c1816abc](https://linux-hardware.org/?probe=34c1816abc) | May 20, 2025 |
| ASRock        | B650M Pro RS                | [432d2c28eb](https://linux-hardware.org/?probe=432d2c28eb) | May 17, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c35990d0ed](https://linux-hardware.org/?probe=c35990d0ed) | May 15, 2025 |
| MSI           | H81M-E35                    | [decb9c4ffb](https://linux-hardware.org/?probe=decb9c4ffb) | May 10, 2025 |
| ASRock        | X300-ITX                    | [c65077f42d](https://linux-hardware.org/?probe=c65077f42d) | May 07, 2025 |
| ECS           | A58F2P-M4                   | [f4d07adc5f](https://linux-hardware.org/?probe=f4d07adc5f) | May 07, 2025 |
| HP            | 2AF9                        | [01139226eb](https://linux-hardware.org/?probe=01139226eb) | May 07, 2025 |
| Dell          | 05XGC8 A01                  | [cf61f96f20](https://linux-hardware.org/?probe=cf61f96f20) | May 05, 2025 |
| Dell          | 05XGC8 A01                  | [728bd664c9](https://linux-hardware.org/?probe=728bd664c9) | Apr 26, 2025 |
| ASUSTek       | H61M-E                      | [008f988fee](https://linux-hardware.org/?probe=008f988fee) | Apr 26, 2025 |
| ASRock        | B650M PG Lightning WiFi     | [10e2bb695d](https://linux-hardware.org/?probe=10e2bb695d) | Apr 20, 2025 |
| Intel         | H81                         | [bff4b4a5f0](https://linux-hardware.org/?probe=bff4b4a5f0) | Apr 19, 2025 |
| MSI           | PRO H410M-B                 | [6381e79779](https://linux-hardware.org/?probe=6381e79779) | Apr 19, 2025 |
| HP            | 2B12                        | [18bd7cffd2](https://linux-hardware.org/?probe=18bd7cffd2) | Apr 01, 2025 |
| HP            | 2B12                        | [d414420da7](https://linux-hardware.org/?probe=d414420da7) | Apr 01, 2025 |
| ASRock        | B850 Pro-A                  | [e00a642b77](https://linux-hardware.org/?probe=e00a642b77) | Mar 27, 2025 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [c9407cf6b9](https://linux-hardware.org/?probe=c9407cf6b9) | Mar 27, 2025 |
| ASUSTek       | P5KPL-AM                    | [95b3e4a4d2](https://linux-hardware.org/?probe=95b3e4a4d2) | Mar 19, 2025 |
| Biostar       | NM70I-1037U                 | [977c3a6e1c](https://linux-hardware.org/?probe=977c3a6e1c) | Mar 15, 2025 |
| MSI           | B350M GAMING PRO            | [c535df19f9](https://linux-hardware.org/?probe=c535df19f9) | Mar 14, 2025 |
| MSI           | B350M GAMING PRO            | [9c52154899](https://linux-hardware.org/?probe=9c52154899) | Mar 13, 2025 |
| ASRock        | H97M-ITX/ac                 | [db2721c3d7](https://linux-hardware.org/?probe=db2721c3d7) | Mar 08, 2025 |
| ASRock        | B550M Pro4                  | [e81dd45b5b](https://linux-hardware.org/?probe=e81dd45b5b) | Mar 07, 2025 |
| Dell          | 0Y2MRG A00                  | [3ac332cfad](https://linux-hardware.org/?probe=3ac332cfad) | Mar 04, 2025 |
| Gigabyte      | EG45M-UD2H                  | [d5a11f8862](https://linux-hardware.org/?probe=d5a11f8862) | Mar 03, 2025 |
| ASRock        | H410M-HVS R2.0              | [24a8d830bb](https://linux-hardware.org/?probe=24a8d830bb) | Mar 01, 2025 |
| ASRock        | H410M-HVS R2.0              | [48a3900cf6](https://linux-hardware.org/?probe=48a3900cf6) | Mar 01, 2025 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [ff834a6c4e](https://linux-hardware.org/?probe=ff834a6c4e) | Feb 28, 2025 |
| ECS           | A320AM4-M3D/3.x/5.x         | [0bfd20edd7](https://linux-hardware.org/?probe=0bfd20edd7) | Feb 27, 2025 |
| MSI           | B450M-A PRO MAX             | [cc0ca34cd1](https://linux-hardware.org/?probe=cc0ca34cd1) | Feb 23, 2025 |
| PC Partner... | A236 0A                     | [fd354b0204](https://linux-hardware.org/?probe=fd354b0204) | Feb 17, 2025 |
| PC Partner... | A236 0A                     | [f55a5da9f6](https://linux-hardware.org/?probe=f55a5da9f6) | Feb 15, 2025 |
| Intel         | B75                         | [18389eb77f](https://linux-hardware.org/?probe=18389eb77f) | Feb 15, 2025 |
| HP            | 212B                        | [6ba5de0521](https://linux-hardware.org/?probe=6ba5de0521) | Feb 15, 2025 |
| HP            | 212B                        | [5145984b7f](https://linux-hardware.org/?probe=5145984b7f) | Feb 15, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [3ece699435](https://linux-hardware.org/?probe=3ece699435) | Feb 13, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [282e5df271](https://linux-hardware.org/?probe=282e5df271) | Feb 13, 2025 |
| Dell          | 033FF6 A00                  | [c9ac06d36b](https://linux-hardware.org/?probe=c9ac06d36b) | Feb 13, 2025 |
| Dell          | 033FF6 A00                  | [5be9faa359](https://linux-hardware.org/?probe=5be9faa359) | Feb 12, 2025 |
| HP            | 8704                        | [186e33f12e](https://linux-hardware.org/?probe=186e33f12e) | Feb 12, 2025 |
| Biostar       | B75MU3B                     | [8c0f562af1](https://linux-hardware.org/?probe=8c0f562af1) | Feb 11, 2025 |
| Dell          | 0WR7PY A00                  | [e3ae928c48](https://linux-hardware.org/?probe=e3ae928c48) | Feb 10, 2025 |
| ASRock        | FM2A68M-DG3+                | [6cb7638c01](https://linux-hardware.org/?probe=6cb7638c01) | Feb 02, 2025 |
| Dell          | 0D6H9T A02                  | [44dfc0cb6d](https://linux-hardware.org/?probe=44dfc0cb6d) | Jan 27, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [beb78f3767](https://linux-hardware.org/?probe=beb78f3767) | Jan 24, 2025 |
| ASRock        | B560M Pro4                  | [63f219119d](https://linux-hardware.org/?probe=63f219119d) | Jan 24, 2025 |
| ASRock        | X370M-HDV                   | [59b8497c91](https://linux-hardware.org/?probe=59b8497c91) | Jan 23, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [382e28b5a0](https://linux-hardware.org/?probe=382e28b5a0) | Jan 22, 2025 |
| Biostar       | NM70I-1037U                 | [3e7d70c21f](https://linux-hardware.org/?probe=3e7d70c21f) | Jan 22, 2025 |
| Gigabyte      | 965P-DS3                    | [7489046d93](https://linux-hardware.org/?probe=7489046d93) | Jan 20, 2025 |
| MSI           | B550M PRO-VDH               | [88ef98a9a7](https://linux-hardware.org/?probe=88ef98a9a7) | Jan 19, 2025 |
| MSI           | B450M-A PRO MAX             | [67ad350eda](https://linux-hardware.org/?probe=67ad350eda) | Jan 19, 2025 |
| ASRock        | H97M-ITX/ac                 | [7862031e44](https://linux-hardware.org/?probe=7862031e44) | Jan 17, 2025 |
| HP            | 2B12                        | [f9594ff416](https://linux-hardware.org/?probe=f9594ff416) | Jan 05, 2025 |
| ASUSTek       | H110M-E/M.2                 | [3b654f1020](https://linux-hardware.org/?probe=3b654f1020) | Jan 05, 2025 |
| ASUSTek       | H110M-E/M.2                 | [d36b787d21](https://linux-hardware.org/?probe=d36b787d21) | Jan 04, 2025 |
| Dell          | 033FF6 A00                  | [621ced80c1](https://linux-hardware.org/?probe=621ced80c1) | Jan 03, 2025 |
| Dell          | 033FF6 A00                  | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| Lenovo        | No DPK                      | [0a59c75def](https://linux-hardware.org/?probe=0a59c75def) | Dec 28, 2024 |
| MSI           | Z97-G43 GAMING              | [28be42de72](https://linux-hardware.org/?probe=28be42de72) | Dec 28, 2024 |
| Dell          | 07HXY6 A01                  | [05efb343fe](https://linux-hardware.org/?probe=05efb343fe) | Dec 28, 2024 |
| ASRock        | A320M-HDV R4.0              | [283f8d39eb](https://linux-hardware.org/?probe=283f8d39eb) | Dec 27, 2024 |
| ASRock        | B550M Pro4                  | [15ca1a3986](https://linux-hardware.org/?probe=15ca1a3986) | Dec 25, 2024 |
| Dell          | 0YF8P5 A00                  | [fab3c1d036](https://linux-hardware.org/?probe=fab3c1d036) | Dec 25, 2024 |
| MSI           | B450M-A PRO MAX             | [b5f8afb7e9](https://linux-hardware.org/?probe=b5f8afb7e9) | Dec 24, 2024 |
| Lenovo        | ThinkCentre A70 7099S3A     | [1ed214159d](https://linux-hardware.org/?probe=1ed214159d) | Dec 24, 2024 |
| Biostar       | IH61MF-Q5                   | [4ff0b038b3](https://linux-hardware.org/?probe=4ff0b038b3) | Dec 15, 2024 |
| ASRock        | X600-ITX                    | [00b43dd980](https://linux-hardware.org/?probe=00b43dd980) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | [e42cce2813](https://linux-hardware.org/?probe=e42cce2813) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | [e872037135](https://linux-hardware.org/?probe=e872037135) | Nov 14, 2024 |
| MSI           | ZH77A-G43                   | [6e7a02926e](https://linux-hardware.org/?probe=6e7a02926e) | Nov 12, 2024 |
| Unknown       | G41 A01                     | [b2d92f4da8](https://linux-hardware.org/?probe=b2d92f4da8) | Nov 05, 2024 |
| Intel         | H61                         | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| ASRock        | B450M Steel Legend          | [1e81679f39](https://linux-hardware.org/?probe=1e81679f39) | Oct 22, 2024 |
| HP            | 89B3 A                      | [95660e69d1](https://linux-hardware.org/?probe=95660e69d1) | Oct 12, 2024 |
| HP            | 2B12                        | [dc89c52ca5](https://linux-hardware.org/?probe=dc89c52ca5) | Oct 10, 2024 |
| HP            | 2B12                        | [af8c8f5046](https://linux-hardware.org/?probe=af8c8f5046) | Oct 09, 2024 |
| ASRock        | H170 Performance            | [333e0c72e5](https://linux-hardware.org/?probe=333e0c72e5) | Oct 09, 2024 |
| Intel         | H81                         | [9792775b83](https://linux-hardware.org/?probe=9792775b83) | Oct 05, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [2b9c6f05fe](https://linux-hardware.org/?probe=2b9c6f05fe) | Sep 28, 2024 |
| Intel         | B75                         | [17dd91b6f2](https://linux-hardware.org/?probe=17dd91b6f2) | Sep 24, 2024 |
| Gigabyte      | G31M-S2C                    | [29671c0af6](https://linux-hardware.org/?probe=29671c0af6) | Sep 02, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | [b0e323ae58](https://linux-hardware.org/?probe=b0e323ae58) | Aug 31, 2024 |
| Gigabyte      | P55-UD3P                    | [80da5ed3a8](https://linux-hardware.org/?probe=80da5ed3a8) | Aug 29, 2024 |
| ASUSTek       | K30AM-J                     | [912c2ae503](https://linux-hardware.org/?probe=912c2ae503) | Aug 29, 2024 |
| Gigabyte      | B550M AORUS PRO             | [7dfa339f21](https://linux-hardware.org/?probe=7dfa339f21) | Aug 29, 2024 |
| GEEKOM        | Mini IT12                   | [6ce7717ab8](https://linux-hardware.org/?probe=6ce7717ab8) | Aug 20, 2024 |
| ASUSTek       | A88X-GAMER                  | [dd86f2e3f4](https://linux-hardware.org/?probe=dd86f2e3f4) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | [571b1e7cf5](https://linux-hardware.org/?probe=571b1e7cf5) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | [ca11b9e447](https://linux-hardware.org/?probe=ca11b9e447) | Aug 20, 2024 |
| ASRock        | X300M-STX                   | [39611ab403](https://linux-hardware.org/?probe=39611ab403) | Aug 16, 2024 |
| GEEKOM        | Mini IT12                   | [54b3658243](https://linux-hardware.org/?probe=54b3658243) | Aug 15, 2024 |
| ASUSTek       | P5G41T-M LX                 | [fe32237e3a](https://linux-hardware.org/?probe=fe32237e3a) | Aug 12, 2024 |
| Gigabyte      | B75M-HD3                    | [39efa072bc](https://linux-hardware.org/?probe=39efa072bc) | Aug 12, 2024 |
| ASUSTek       | H61M-E                      | [c18e02345c](https://linux-hardware.org/?probe=c18e02345c) | Aug 12, 2024 |
| HP            | 198E                        | [21d03f44b1](https://linux-hardware.org/?probe=21d03f44b1) | Aug 11, 2024 |
| Intel         | H110 Series                 | [ba2023d022](https://linux-hardware.org/?probe=ba2023d022) | Aug 03, 2024 |
| Intel         | DH61WW AAG23116-303         | [f46309dc1c](https://linux-hardware.org/?probe=f46309dc1c) | Aug 03, 2024 |
| ASUSTek       | H61M-E                      | [368a1a7088](https://linux-hardware.org/?probe=368a1a7088) | Jul 30, 2024 |
| ASRock        | H510M-HDV/M.2               | [2e993c4215](https://linux-hardware.org/?probe=2e993c4215) | Jul 27, 2024 |
| ASRock        | H510M-HDV/M.2               | [a9d457cbfe](https://linux-hardware.org/?probe=a9d457cbfe) | Jul 27, 2024 |
| MSI           | B550M PRO-VDH               | [e20f83dc61](https://linux-hardware.org/?probe=e20f83dc61) | Jul 23, 2024 |
| Intel         | H61                         | [79cbc35474](https://linux-hardware.org/?probe=79cbc35474) | Jul 20, 2024 |
| ASUSTek       | H81M-K                      | [a87baa98b1](https://linux-hardware.org/?probe=a87baa98b1) | Jul 11, 2024 |
| ASRock        | B650M PG Lightning          | [94eff09933](https://linux-hardware.org/?probe=94eff09933) | Jul 09, 2024 |
| ASRock        | FM2A68M-DG3+                | [c5062c2b4e](https://linux-hardware.org/?probe=c5062c2b4e) | Jul 07, 2024 |
| ECS           | H61H2-M12                   | [7bcab0a14c](https://linux-hardware.org/?probe=7bcab0a14c) | Jul 07, 2024 |
| ASRock        | B550M-HDV                   | [9d7278dbe4](https://linux-hardware.org/?probe=9d7278dbe4) | Jul 06, 2024 |
| ASRock        | B550M-HDV                   | [54e71c6699](https://linux-hardware.org/?probe=54e71c6699) | Jul 06, 2024 |
| Gigabyte      | 970A-D3P                    | [1aba817d5d](https://linux-hardware.org/?probe=1aba817d5d) | Jul 05, 2024 |
| HP            | 8169                        | [c45572c08d](https://linux-hardware.org/?probe=c45572c08d) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | [a12c62a640](https://linux-hardware.org/?probe=a12c62a640) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | [9f0a26445e](https://linux-hardware.org/?probe=9f0a26445e) | Jul 04, 2024 |
| ASRock        | B450M Steel Legend          | [16545a1d8f](https://linux-hardware.org/?probe=16545a1d8f) | Jul 02, 2024 |
| Dell          | 0Y2MRG A00                  | [cab50448b9](https://linux-hardware.org/?probe=cab50448b9) | Jun 30, 2024 |
| ASRock        | X370M Pro4                  | [65e29ff944](https://linux-hardware.org/?probe=65e29ff944) | Jun 29, 2024 |
| ASUSTek       | PRIME H510M-E               | [4d278d12d7](https://linux-hardware.org/?probe=4d278d12d7) | Jun 25, 2024 |
| Acer          | Aspire MC605 v1.0           | [412057df6b](https://linux-hardware.org/?probe=412057df6b) | Jun 23, 2024 |
| Gigabyte      | G41MT-S2PT                  | [347663d539](https://linux-hardware.org/?probe=347663d539) | Jun 23, 2024 |
| Dell          | 0D24M8 A01                  | [2cdf2b71a1](https://linux-hardware.org/?probe=2cdf2b71a1) | Jun 20, 2024 |
| TriGem Com... | H61H2-TM7                   | [7deb9d1c5a](https://linux-hardware.org/?probe=7deb9d1c5a) | Jun 11, 2024 |
| Unknown       | G41 Series                  | [f9b4dbc607](https://linux-hardware.org/?probe=f9b4dbc607) | Jun 05, 2024 |
| Acer          | Veriton L4620G v1.0         | [24db2893da](https://linux-hardware.org/?probe=24db2893da) | Jun 04, 2024 |
| Gigabyte      | B450M DS3H V2               | [0941f7e44b](https://linux-hardware.org/?probe=0941f7e44b) | Jun 03, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [0c62b9f67c](https://linux-hardware.org/?probe=0c62b9f67c) | May 20, 2024 |
| Unknown       | G41 A01                     | [537cc137bd](https://linux-hardware.org/?probe=537cc137bd) | May 04, 2024 |
| HP            | 0B4Ch D                     | [29d73efd4a](https://linux-hardware.org/?probe=29d73efd4a) | Apr 30, 2024 |
| ASUSTek       | PRIME A320M-K               | [97e9e0c7a1](https://linux-hardware.org/?probe=97e9e0c7a1) | Apr 13, 2024 |
| Intel         | H81                         | [e734609a4c](https://linux-hardware.org/?probe=e734609a4c) | Mar 26, 2024 |
| ASRock        | H610M-HVS/M.2 R2.0          | [208a49a1cc](https://linux-hardware.org/?probe=208a49a1cc) | Mar 24, 2024 |
| ECS           | H61H2-MV                    | [2ab5b82fb2](https://linux-hardware.org/?probe=2ab5b82fb2) | Mar 21, 2024 |
| ASRock        | B550M Steel Legend          | [a1762528fb](https://linux-hardware.org/?probe=a1762528fb) | Mar 17, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | [d9770af085](https://linux-hardware.org/?probe=d9770af085) | Mar 06, 2024 |
| Intel         | H61                         | [2577e168b3](https://linux-hardware.org/?probe=2577e168b3) | Mar 05, 2024 |
| Intel         | H81                         | [4f0a4894dc](https://linux-hardware.org/?probe=4f0a4894dc) | Mar 03, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [223fbfa988](https://linux-hardware.org/?probe=223fbfa988) | Feb 29, 2024 |
| Lenovo        | 3102 NOK                    | [b343ea038a](https://linux-hardware.org/?probe=b343ea038a) | Feb 27, 2024 |
| HP            | 1998                        | [ea2b04fb8f](https://linux-hardware.org/?probe=ea2b04fb8f) | Feb 20, 2024 |
| ASRock        | X99 Taichi                  | [98640d2d16](https://linux-hardware.org/?probe=98640d2d16) | Feb 19, 2024 |
| ASRock        | FM2A58M-VG3+ R2.0           | [5c7e2b278a](https://linux-hardware.org/?probe=5c7e2b278a) | Feb 17, 2024 |
| ASRock        | FM2A58M-VG3+ R2.0           | [a44e202559](https://linux-hardware.org/?probe=a44e202559) | Feb 17, 2024 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [1809bea252](https://linux-hardware.org/?probe=1809bea252) | Feb 14, 2024 |
| Intel         | H81                         | [fac0a305d4](https://linux-hardware.org/?probe=fac0a305d4) | Jan 29, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [fe98e7026e](https://linux-hardware.org/?probe=fe98e7026e) | Jan 25, 2024 |
| Gigabyte      | F2A58M-DS2                  | [b8fc987633](https://linux-hardware.org/?probe=b8fc987633) | Jan 24, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [8edec841f0](https://linux-hardware.org/?probe=8edec841f0) | Jan 22, 2024 |
| Gigabyte      | F2A58M-DS2                  | [2b604752a0](https://linux-hardware.org/?probe=2b604752a0) | Jan 21, 2024 |
| ECS           | H61H2-MV                    | [09c20c7740](https://linux-hardware.org/?probe=09c20c7740) | Jan 15, 2024 |
| HP            | 81B4 01                     | [2a8624aed6](https://linux-hardware.org/?probe=2a8624aed6) | Jan 15, 2024 |
| MSI           | H310M PRO-VH PLUS           | [7b76b0de4f](https://linux-hardware.org/?probe=7b76b0de4f) | Jan 13, 2024 |
| MSI           | H310M PRO-VH PLUS           | [8431e0e3d7](https://linux-hardware.org/?probe=8431e0e3d7) | Jan 10, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| Dell          | 033FF6 A00                  | [f54cfd23ee](https://linux-hardware.org/?probe=f54cfd23ee) | Dec 28, 2023 |
| Dell          | 033FF6 A00                  | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| AZW           | MINI S 10                   | [fbeeeb79f5](https://linux-hardware.org/?probe=fbeeeb79f5) | Dec 25, 2023 |
| Intel         | B75                         | [65bfc8c4cf](https://linux-hardware.org/?probe=65bfc8c4cf) | Dec 24, 2023 |
| Dell          | 033FF6 A00                  | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| MSI           | Z77A-G43                    | [9afc3e4d49](https://linux-hardware.org/?probe=9afc3e4d49) | Dec 16, 2023 |
| MSI           | Z77A-G43                    | [25c5c9bb33](https://linux-hardware.org/?probe=25c5c9bb33) | Dec 16, 2023 |
| ASUSTek       | Crosshair V Formula         | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| Intel         | H61                         | [9951d7579f](https://linux-hardware.org/?probe=9951d7579f) | Dec 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Intel         | H61                         | [a0a26787ca](https://linux-hardware.org/?probe=a0a26787ca) | Nov 30, 2023 |
| Minix         | H61M-USB3 V1.2              | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [dbfedd49f8](https://linux-hardware.org/?probe=dbfedd49f8) | Nov 21, 2023 |
| Dell          | 0HH807                      | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| ASRock        | B550M Pro4                  | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| Gigabyte      | A520I AC                    | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| Dell          | 0HH807                      | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Acer          | EG31M R01-C3                | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| Gigabyte      | B550M DS3H                  | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| HP            | 198E                        | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| MSI           | 770T-C45                    | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| ASRock        | B550M Pro4                  | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| ASRock        | FM2A68M-DG3+                | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASRock        | A88M-G                      | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| ZOTAC         | NM10                        | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| Acer          | Aspire M5910                | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| MSI           | 2A9C                        | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| MSI           | MS-B9091                    | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| MSI           | MS-B9091                    | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| MSI           | H310M PRO-VH PLUS           | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Acer          | Veriton M480                | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Foxconn       | G31MX Series                | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| ASRock        | H61M-HVGS                   | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| Intel         | H81                         | [70d2da2312](https://linux-hardware.org/?probe=70d2da2312) | Aug 20, 2023 |
| MSI           | 3666h                       | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Gigabyte      | B365M DS3H                  | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASRock        | B550M Pro4                  | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| ASRock        | H61M-HVGS                   | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| ASUSTek       | P5QD TURBO                  | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| MSI           | H81M-E35 V2                 | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| Dell          | 0GTK4K A10                  | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Gigabyte      | H61M-DS2                    | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| HP            | 2187 A01                    | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Gigabyte      | H81M-S2PV                   | [c1c039384c](https://linux-hardware.org/?probe=c1c039384c) | Jul 11, 2023 |
| Gigabyte      | P55-USB3L                   | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| Intel         | Unknown                     | [3c85a0c7b9](https://linux-hardware.org/?probe=3c85a0c7b9) | Jun 28, 2023 |
| Intel         | Unknown                     | [dbfbe4b6aa](https://linux-hardware.org/?probe=dbfbe4b6aa) | Jun 27, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| MSI           | B350M MORTAR                | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Unknown       | Unknown                     | [76c1fcc4e5](https://linux-hardware.org/?probe=76c1fcc4e5) | Jun 14, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| MSI           | 2A9C                        | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| Unknown       | Unknown                     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| MSI           | 2A9C                        | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASRock        | B560M Pro4                  | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | X300-ITX                    | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| Acer          | EG31M R01-C3                | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Gigabyte      | P41T-D3                     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| Gigabyte      | H81M-S2PV                   | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| GALAX         | B550M                       | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Foxconn       | G31MX Series                | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | Z97-G43 GAMING              | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASRock        | 970A-G                      | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASRock        | A88M-G                      | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Unknown       | Unknown                     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ECS           | H81H3-MV                    | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| HP            | 198E                        | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Dell          | 0VRWRC A00                  | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | B550M Pro4                  | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | 3102 NO DPK                 | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Intel         | Unknown                     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Gigabyte      | B550M AORUS PRO             | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| HP            | ProLiant ML110 G7           | [7b4b133211](https://linux-hardware.org/?probe=7b4b133211) | Dec 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| MSI           | H61M-P20                    | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| Gigabyte      | 970A-D3P                    | [d09b578699](https://linux-hardware.org/?probe=d09b578699) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| ASUSTek       | Z8NA-D6                     | [1cd6da46f3](https://linux-hardware.org/?probe=1cd6da46f3) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-F               | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| Intel         | DH55PJ AAE93812-302         | [de105b99e4](https://linux-hardware.org/?probe=de105b99e4) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| MSI           | H510M PRO                   | [182b91241d](https://linux-hardware.org/?probe=182b91241d) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| MSI           | 2A9C                        | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| MSI           | 2A9C                        | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| ASRock        | B550M-ITX/ac                | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| HP            | 198E                        | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| ECS           | A55F2-M4                    | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Gigabyte      | H81M-S2PV                   | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Gigabyte      | H170-D3H-CF                 | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Gigabyte      | B365M H                     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| MSI           | 2A9C                        | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | H110M-A/DP                  | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Biostar       | A68N-5600E                  | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | P5GC-MX/1333                | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| MSI           | 2A9C                        | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| Wearnes       | T1550-A1                    | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| ASRock        | A88M-G                      | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASRock        | A88M-G                      | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| Unknown       | Unknown                     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Unknown       | Unknown                     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| HP            | 3641h                       | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Koloe         | X58                         | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Intel         | H55                         | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| ZYREX COMP... | TACTICAL                    | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| MSI           | 2A9C                        | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| Dell          | 02YYK5 A01                  | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Dell          | 0VRWRC A00                  | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Biostar       | H81MHV3                     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| ASUSTek       | Z97-C                       | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| ECS           | H61H2-MV                    | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Foxconn       | 17A0                        | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| Foxconn       | 17A0                        | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [6d67037961](https://linux-hardware.org/?probe=6d67037961) | Nov 16, 2021 |
| Foxconn       | 17A0                        | [ed1128211e](https://linux-hardware.org/?probe=ed1128211e) | Nov 14, 2021 |
| Foxconn       | 17A0                        | [17ff85bc35](https://linux-hardware.org/?probe=17ff85bc35) | Nov 09, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| ASUSTek       | PRIME H310M-K               | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| MSI           | B350M MORTAR                | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [4fa9117126](https://linux-hardware.org/?probe=4fa9117126) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [e4fc3665f7](https://linux-hardware.org/?probe=e4fc3665f7) | Oct 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [93b56b7543](https://linux-hardware.org/?probe=93b56b7543) | Oct 29, 2021 |
| MSI           | B350M MORTAR                | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| Pegatron      | 2AD4                        | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| Gigabyte      | EP45-UD3R                   | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| Dell          | 0773VG A01                  | [84fc704eaa](https://linux-hardware.org/?probe=84fc704eaa) | Oct 09, 2021 |
| Lenovo        | H310                        | [ce491df5a4](https://linux-hardware.org/?probe=ce491df5a4) | Oct 06, 2021 |
| ASRock        | AB350 Pro4                  | [4038d4a0a6](https://linux-hardware.org/?probe=4038d4a0a6) | Sep 29, 2021 |
| ASRock        | AB350 Pro4                  | [5854a1e114](https://linux-hardware.org/?probe=5854a1e114) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| ASUSTek       | PRIME H510M-D               | [f8fd88bca1](https://linux-hardware.org/?probe=f8fd88bca1) | Sep 26, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| Gigabyte      | P31-ES3G                    | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| ASUSTek       | H61M-K                      | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [9ab0b9612a](https://linux-hardware.org/?probe=9ab0b9612a) | Aug 30, 2021 |
| ASUSTek       | Z97-C                       | [924e556648](https://linux-hardware.org/?probe=924e556648) | Aug 28, 2021 |
| ASRock        | X300M-STX                   | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | H81M-C                      | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| Gigabyte      | EP45-DS3                    | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| ECS           | A960M-MV                    | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| ASRock        | AB350 Pro4                  | [2da83ae7b5](https://linux-hardware.org/?probe=2da83ae7b5) | Aug 12, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| ASRock        | A320M-HDV                   | [20dc9f0df4](https://linux-hardware.org/?probe=20dc9f0df4) | Jul 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Acer          | Veriton L4630G V:1.0        | [c486fbf03f](https://linux-hardware.org/?probe=c486fbf03f) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| ECS           | G41T-M12                    | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | H110M-E/M.2                 | [7f0ce9114c](https://linux-hardware.org/?probe=7f0ce9114c) | Jul 21, 2021 |
| Dell          | 0YXT71 A03                  | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [533da05156](https://linux-hardware.org/?probe=533da05156) | Jul 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [064817cd28](https://linux-hardware.org/?probe=064817cd28) | Jul 05, 2021 |
| MSI           | 870A-G54                    | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Biostar       | TA870+                      | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| Lenovo        | SHARKBAY NOK                | [a3cef73da9](https://linux-hardware.org/?probe=a3cef73da9) | Jun 09, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [414008f0a3](https://linux-hardware.org/?probe=414008f0a3) | Jun 08, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [744392b18f](https://linux-hardware.org/?probe=744392b18f) | Jun 08, 2021 |
| MSI           | Z97-G43 GAMING              | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| HP            | 1906                        | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| ECS           | G41T-M12                    | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| ECS           | A55F2-M4                    | [b08197df02](https://linux-hardware.org/?probe=b08197df02) | May 29, 2021 |
| Gigabyte      | P85-D3                      | [a85613d8a6](https://linux-hardware.org/?probe=a85613d8a6) | May 24, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| Dell          | 0GDG8Y A00                  | [c75161deac](https://linux-hardware.org/?probe=c75161deac) | May 20, 2021 |
| Gigabyte      | B450M DS3H V2               | [8f39af876c](https://linux-hardware.org/?probe=8f39af876c) | May 19, 2021 |
| ASRock        | H81M-VG4 R2.0               | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [f900105a8a](https://linux-hardware.org/?probe=f900105a8a) | May 09, 2021 |
| Acer          | Veriton M2611 v1.0          | [82b2ea1868](https://linux-hardware.org/?probe=82b2ea1868) | May 06, 2021 |
| Acer          | Veriton M2611 v1.0          | [218de62b27](https://linux-hardware.org/?probe=218de62b27) | May 06, 2021 |
| Unknown       | Unknown                     | [327d214403](https://linux-hardware.org/?probe=327d214403) | May 04, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| ECS           | 945GCT-M2                   | [3f73514b16](https://linux-hardware.org/?probe=3f73514b16) | Apr 26, 2021 |
| ECS           | 945GCT-M2                   | [289b6cba53](https://linux-hardware.org/?probe=289b6cba53) | Apr 25, 2021 |
| MSI           | Z97-G43 GAMING              | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7099S3A     | [2fd4915fe8](https://linux-hardware.org/?probe=2fd4915fe8) | Apr 16, 2021 |
| ASRock        | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASRock        | B450 Pro4                   | [e83e7312c9](https://linux-hardware.org/?probe=e83e7312c9) | Apr 08, 2021 |
| MSI           | B85M GAMING                 | [bf0490433a](https://linux-hardware.org/?probe=bf0490433a) | Apr 07, 2021 |
| MSI           | B550-A PRO                  | [f7ddac6f83](https://linux-hardware.org/?probe=f7ddac6f83) | Apr 02, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [a5d5c057c0](https://linux-hardware.org/?probe=a5d5c057c0) | Mar 24, 2021 |
| MSI           | B460M PRO                   | [3a26303ce0](https://linux-hardware.org/?probe=3a26303ce0) | Mar 21, 2021 |
| MSI           | B460M PRO                   | [82bf6fd41b](https://linux-hardware.org/?probe=82bf6fd41b) | Mar 21, 2021 |
| ASRock        | B450 Pro4                   | [ed1a952ed3](https://linux-hardware.org/?probe=ed1a952ed3) | Mar 17, 2021 |
| Unknown       | Unknown                     | [b4b92701a0](https://linux-hardware.org/?probe=b4b92701a0) | Mar 05, 2021 |
| Biostar       | H61MGV3                     | [85e0a1cacc](https://linux-hardware.org/?probe=85e0a1cacc) | Mar 01, 2021 |
| ASUSTek       | H61M-K                      | [b59c5fdb8a](https://linux-hardware.org/?probe=b59c5fdb8a) | Feb 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [95c5fe898a](https://linux-hardware.org/?probe=95c5fe898a) | Feb 27, 2021 |
| Lenovo        | Unknown                     | [0ca27a0ce2](https://linux-hardware.org/?probe=0ca27a0ce2) | Feb 24, 2021 |
| Gigabyte      | B460M DS3H                  | [fe95f7aef8](https://linux-hardware.org/?probe=fe95f7aef8) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [b1edb9db86](https://linux-hardware.org/?probe=b1edb9db86) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [abc0ef8bc7](https://linux-hardware.org/?probe=abc0ef8bc7) | Feb 19, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [502bc7eb2a](https://linux-hardware.org/?probe=502bc7eb2a) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [8d369a84ce](https://linux-hardware.org/?probe=8d369a84ce) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [95883e3fff](https://linux-hardware.org/?probe=95883e3fff) | Feb 04, 2021 |
| HP            | 834F                        | [c849bbc95a](https://linux-hardware.org/?probe=c849bbc95a) | Jan 14, 2021 |
| Lenovo        | 36EB SDK0Q55726 WIN 3273... | [ace52f974e](https://linux-hardware.org/?probe=ace52f974e) | Jan 13, 2021 |
| Gigabyte      | A320M-DS2-CF                | [414638f163](https://linux-hardware.org/?probe=414638f163) | Jan 07, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [9fe6d5b992](https://linux-hardware.org/?probe=9fe6d5b992) | Jan 02, 2021 |
| MSI           | G41M-P26                    | [8d7a10a828](https://linux-hardware.org/?probe=8d7a10a828) | Dec 31, 2020 |
| MSI           | 760GM-P23                   | [9ea9c09319](https://linux-hardware.org/?probe=9ea9c09319) | Dec 27, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [405b8ef206](https://linux-hardware.org/?probe=405b8ef206) | Dec 25, 2020 |
| MSI           | 870A-G54                    | [479ee62f9f](https://linux-hardware.org/?probe=479ee62f9f) | Dec 21, 2020 |
| HP            | 1497                        | [1bfa453ea4](https://linux-hardware.org/?probe=1bfa453ea4) | Dec 19, 2020 |
| HP            | 1497                        | [9b292e4071](https://linux-hardware.org/?probe=9b292e4071) | Dec 19, 2020 |
| MSI           | B360 GAMING PLUS            | [7a77cc7ec2](https://linux-hardware.org/?probe=7a77cc7ec2) | Dec 12, 2020 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [3e44b38d7f](https://linux-hardware.org/?probe=3e44b38d7f) | Dec 03, 2020 |
| ASRock        | H67M                        | [11ccd3281d](https://linux-hardware.org/?probe=11ccd3281d) | Nov 28, 2020 |
| Acer          | Aspire M3970                | [7350b05e56](https://linux-hardware.org/?probe=7350b05e56) | Nov 25, 2020 |
| Acer          | Aspire M3970                | [f380a566c2](https://linux-hardware.org/?probe=f380a566c2) | Nov 25, 2020 |
| Acer          | Veriton X4610G              | [e9ace7d042](https://linux-hardware.org/?probe=e9ace7d042) | Nov 24, 2020 |
| Dell          | 08HPGT A01                  | [d5ae57d261](https://linux-hardware.org/?probe=d5ae57d261) | Nov 20, 2020 |
| ASRock        | B450 Pro4                   | [f24f7ba17e](https://linux-hardware.org/?probe=f24f7ba17e) | Nov 13, 2020 |
| Dell          | 0GY6Y8 A00                  | [613e036e8d](https://linux-hardware.org/?probe=613e036e8d) | Nov 11, 2020 |
| MSI           | H410M PRO-VH                | [e5603638aa](https://linux-hardware.org/?probe=e5603638aa) | Nov 10, 2020 |
| MSI           | 870A-G54                    | [d14df17124](https://linux-hardware.org/?probe=d14df17124) | Nov 08, 2020 |
| HP            | 304Ah                       | [530cc628fb](https://linux-hardware.org/?probe=530cc628fb) | Nov 07, 2020 |
| HP            | 304Ah                       | [0ed06ad934](https://linux-hardware.org/?probe=0ed06ad934) | Nov 04, 2020 |
| Gigabyte      | H81M-Gaming 3               | [8d7b38dbf3](https://linux-hardware.org/?probe=8d7b38dbf3) | Nov 03, 2020 |
| Gigabyte      | H81M-Gaming 3               | [0c6140c86e](https://linux-hardware.org/?probe=0c6140c86e) | Nov 03, 2020 |
| MSI           | B85M GAMING                 | [b2b720adf7](https://linux-hardware.org/?probe=b2b720adf7) | Oct 28, 2020 |
| HP            | 1493                        | [cf9c3c195a](https://linux-hardware.org/?probe=cf9c3c195a) | Oct 24, 2020 |
| Quanta        | 2B03 110                    | [afa8ef9dda](https://linux-hardware.org/?probe=afa8ef9dda) | Oct 20, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| Lenovo        | SKYBAY NOK                  | [f02492e188](https://linux-hardware.org/?probe=f02492e188) | Oct 08, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [805323645e](https://linux-hardware.org/?probe=805323645e) | Oct 04, 2020 |
| ASUSTek       | H110M-E/M.2                 | [e937cdfcbc](https://linux-hardware.org/?probe=e937cdfcbc) | Sep 28, 2020 |
| MSI           | B360 GAMING PLUS            | [6b3915fc77](https://linux-hardware.org/?probe=6b3915fc77) | Sep 28, 2020 |
| ASRock        | B365M Phantom Gaming 4      | [9f213e1442](https://linux-hardware.org/?probe=9f213e1442) | Sep 25, 2020 |
| Lenovo        | ThinkCentre M57p 9193A11    | [4d8a70073f](https://linux-hardware.org/?probe=4d8a70073f) | Sep 25, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [8be0a34480](https://linux-hardware.org/?probe=8be0a34480) | Sep 16, 2020 |
| Gigabyte      | H81M-S2PH                   | [b5438c62fc](https://linux-hardware.org/?probe=b5438c62fc) | Sep 16, 2020 |
| ECS           | Z97M-PK                     | [888e740324](https://linux-hardware.org/?probe=888e740324) | Sep 13, 2020 |
| MSI           | B360 GAMING PLUS            | [6c5d768e02](https://linux-hardware.org/?probe=6c5d768e02) | Sep 10, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [c363153de4](https://linux-hardware.org/?probe=c363153de4) | Sep 08, 2020 |
| MSI           | B350M MORTAR                | [ebcd809d62](https://linux-hardware.org/?probe=ebcd809d62) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6d06e18252](https://linux-hardware.org/?probe=6d06e18252) | Aug 30, 2020 |
| MSI           | B75MA-P33                   | [05483ed2c3](https://linux-hardware.org/?probe=05483ed2c3) | Aug 28, 2020 |
| MSI           | 870A-G54                    | [727980a18d](https://linux-hardware.org/?probe=727980a18d) | Aug 23, 2020 |
| SPECTRUM U... | VA 880G                     | [ef0b289382](https://linux-hardware.org/?probe=ef0b289382) | Aug 21, 2020 |
| ASRock        | A300M-STX                   | [0aeef3e18b](https://linux-hardware.org/?probe=0aeef3e18b) | Aug 19, 2020 |
| Lenovo        | SHARKBAY NOK                | [f205ba371e](https://linux-hardware.org/?probe=f205ba371e) | Aug 19, 2020 |
| MSI           | 870A-G54                    | [292a02f724](https://linux-hardware.org/?probe=292a02f724) | Aug 17, 2020 |
| Biostar       | H310MHC                     | [4331ff5e27](https://linux-hardware.org/?probe=4331ff5e27) | Aug 14, 2020 |
| Dell          | 0D28YY A01                  | [6740e51a94](https://linux-hardware.org/?probe=6740e51a94) | Aug 14, 2020 |
| NEC Comput... | MS-7264LW                   | [63f1552717](https://linux-hardware.org/?probe=63f1552717) | Aug 09, 2020 |
| NEC Comput... | MS-7264LW                   | [bc4eab7fa3](https://linux-hardware.org/?probe=bc4eab7fa3) | Aug 09, 2020 |
| MSI           | B85M GAMING                 | [984c0ed0a7](https://linux-hardware.org/?probe=984c0ed0a7) | Aug 07, 2020 |
| ASRock        | A320M-HDV R4.0              | [87a26416b1](https://linux-hardware.org/?probe=87a26416b1) | Aug 06, 2020 |
| MSI           | H81M-P33                    | [f9cb52c02a](https://linux-hardware.org/?probe=f9cb52c02a) | Aug 05, 2020 |
| ASUSTek       | PRIME H410M-E               | [ecd5a9cdd0](https://linux-hardware.org/?probe=ecd5a9cdd0) | Aug 01, 2020 |
| ASUSTek       | PRIME H410M-E               | [f95e229d75](https://linux-hardware.org/?probe=f95e229d75) | Aug 01, 2020 |
| MSI           | B85M GAMING                 | [ca027f475e](https://linux-hardware.org/?probe=ca027f475e) | Jul 28, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [5a271f15c2](https://linux-hardware.org/?probe=5a271f15c2) | Jul 28, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f34a4c062d](https://linux-hardware.org/?probe=f34a4c062d) | Jul 26, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [1d18d6d402](https://linux-hardware.org/?probe=1d18d6d402) | Jul 25, 2020 |
| MSI           | B85M GAMING                 | [29191c1b1e](https://linux-hardware.org/?probe=29191c1b1e) | Jul 24, 2020 |
| OEM           | G41 775 ICH7 8712           | [bdbd588c54](https://linux-hardware.org/?probe=bdbd588c54) | Jul 24, 2020 |
| MSI           | 870A-G54                    | [74d1532bd8](https://linux-hardware.org/?probe=74d1532bd8) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [9110e601b2](https://linux-hardware.org/?probe=9110e601b2) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [ce919dba00](https://linux-hardware.org/?probe=ce919dba00) | Jul 09, 2020 |
| Intel         | Unknown                     | [9224b78dd5](https://linux-hardware.org/?probe=9224b78dd5) | Jul 07, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| Nvidia        | NF-MCP68                    | [6b42b5244e](https://linux-hardware.org/?probe=6b42b5244e) | Jun 23, 2020 |
| Unknown       | G41 Series                  | [5f2347032e](https://linux-hardware.org/?probe=5f2347032e) | Jun 16, 2020 |
| MSI           | 870A-G54                    | [4c34d33e03](https://linux-hardware.org/?probe=4c34d33e03) | Jun 15, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [5bb6af2e45](https://linux-hardware.org/?probe=5bb6af2e45) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [c06f108477](https://linux-hardware.org/?probe=c06f108477) | Jun 14, 2020 |
| MSI           | 870A-G54                    | [8f14b79b6a](https://linux-hardware.org/?probe=8f14b79b6a) | Jun 14, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [ab1f7a9baa](https://linux-hardware.org/?probe=ab1f7a9baa) | Jun 11, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [e30aeca065](https://linux-hardware.org/?probe=e30aeca065) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8918ed5ee1](https://linux-hardware.org/?probe=8918ed5ee1) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [34ec73be33](https://linux-hardware.org/?probe=34ec73be33) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [f56d577ca6](https://linux-hardware.org/?probe=f56d577ca6) | May 29, 2020 |
| Gigabyte      | EP45-DS3LR                  | [1aa541af52](https://linux-hardware.org/?probe=1aa541af52) | May 29, 2020 |
| ECS           | P43G                        | [61bbe10085](https://linux-hardware.org/?probe=61bbe10085) | May 28, 2020 |
| ECS           | P43G                        | [13a37c39ae](https://linux-hardware.org/?probe=13a37c39ae) | May 28, 2020 |
| MSI           | B85M GAMING                 | [ce4c6b31d7](https://linux-hardware.org/?probe=ce4c6b31d7) | May 24, 2020 |
| ASRock        | G41M-VS3                    | [b8573ae92c](https://linux-hardware.org/?probe=b8573ae92c) | May 23, 2020 |
| MSI           | B85M GAMING                 | [aba32f928c](https://linux-hardware.org/?probe=aba32f928c) | May 17, 2020 |
| Gigabyte      | H61M-DS2                    | [16bcd5ac39](https://linux-hardware.org/?probe=16bcd5ac39) | May 02, 2020 |
| MSI           | P55-CD53                    | [afb112f2e5](https://linux-hardware.org/?probe=afb112f2e5) | May 02, 2020 |
| Gigabyte      | H61M-DS2                    | [e16a4f321c](https://linux-hardware.org/?probe=e16a4f321c) | Apr 29, 2020 |
| MSI           | 970A-G45                    | [6ac0a4fa90](https://linux-hardware.org/?probe=6ac0a4fa90) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [6adbd75b76](https://linux-hardware.org/?probe=6adbd75b76) | Apr 24, 2020 |
| Biostar       | H310MHC                     | [49ba466f80](https://linux-hardware.org/?probe=49ba466f80) | Apr 17, 2020 |
| Biostar       | H310MHC                     | [b7a62e3806](https://linux-hardware.org/?probe=b7a62e3806) | Apr 17, 2020 |
| ECS           | H61H2-M12                   | [ae9b0e4fc7](https://linux-hardware.org/?probe=ae9b0e4fc7) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [de706540bb](https://linux-hardware.org/?probe=de706540bb) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [e7b1567091](https://linux-hardware.org/?probe=e7b1567091) | Apr 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [de7c9abd9e](https://linux-hardware.org/?probe=de7c9abd9e) | Apr 14, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [39347abd01](https://linux-hardware.org/?probe=39347abd01) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [8b47d0dec9](https://linux-hardware.org/?probe=8b47d0dec9) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [de75fa5904](https://linux-hardware.org/?probe=de75fa5904) | Apr 06, 2020 |
| ASRock        | X570 Steel Legend           | [9ebe70290a](https://linux-hardware.org/?probe=9ebe70290a) | Apr 05, 2020 |
| Biostar       | X370GT3                     | [1eba7843c7](https://linux-hardware.org/?probe=1eba7843c7) | Apr 03, 2020 |
| Biostar       | X370GT3                     | [4a91b87778](https://linux-hardware.org/?probe=4a91b87778) | Apr 03, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASUSTek       | CG8580                      | [a2755006be](https://linux-hardware.org/?probe=a2755006be) | Feb 22, 2020 |
| ASUSTek       | CG8580                      | [ca764ea79e](https://linux-hardware.org/?probe=ca764ea79e) | Feb 22, 2020 |
| ASUSTek       | H81M-E                      | [d4fc5bee1a](https://linux-hardware.org/?probe=d4fc5bee1a) | Feb 21, 2020 |
| ASUSTek       | H81M-E                      | [ee2cf3834b](https://linux-hardware.org/?probe=ee2cf3834b) | Feb 21, 2020 |
| ASUSTek       | H97M-E                      | [583ff222dc](https://linux-hardware.org/?probe=583ff222dc) | Feb 20, 2020 |
| Intel         | Unknown                     | [ed1af52d9b](https://linux-hardware.org/?probe=ed1af52d9b) | Feb 14, 2020 |
| Dell          | 09KPNV A00                  | [a242b5b90b](https://linux-hardware.org/?probe=a242b5b90b) | Feb 07, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [ef5e60b804](https://linux-hardware.org/?probe=ef5e60b804) | Feb 06, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [e2ad5e1470](https://linux-hardware.org/?probe=e2ad5e1470) | Feb 06, 2020 |
| Biostar       | B45M2                       | [d5e8a2ad7a](https://linux-hardware.org/?probe=d5e8a2ad7a) | Jan 18, 2020 |
| Biostar       | B45M2                       | [8fde9c57e5](https://linux-hardware.org/?probe=8fde9c57e5) | Jan 18, 2020 |
| MSI           | 2A78h                       | [275a99a2fe](https://linux-hardware.org/?probe=275a99a2fe) | Jan 06, 2020 |
| Intel         | DG31PR AAD97573-306         | [7f477da95d](https://linux-hardware.org/?probe=7f477da95d) | Dec 12, 2019 |
| Biostar       | H310MHC                     | [a2ad758a5a](https://linux-hardware.org/?probe=a2ad758a5a) | Oct 29, 2019 |
| Biostar       | H310MHC                     | [3b6265a2aa](https://linux-hardware.org/?probe=3b6265a2aa) | Oct 29, 2019 |
| Dell          | 0T656F A01                  | [7a0f0d92a8](https://linux-hardware.org/?probe=7a0f0d92a8) | Oct 18, 2019 |
| ECS           | A785GM-AD3                  | [69dee2c465](https://linux-hardware.org/?probe=69dee2c465) | Oct 10, 2019 |
| ASUSTek       | M4A785TD-V EVO              | [85e109926e](https://linux-hardware.org/?probe=85e109926e) | Sep 20, 2019 |
| Intel         | DX58SO AAE29331-703         | [8a2de6109c](https://linux-hardware.org/?probe=8a2de6109c) | Sep 17, 2019 |
| Intel         | DG31PR AAD97573-306         | [1b36a15fbc](https://linux-hardware.org/?probe=1b36a15fbc) | Sep 17, 2019 |
| Intel         | DX58SO AAE29331-703         | [bc3adc24d0](https://linux-hardware.org/?probe=bc3adc24d0) | Sep 12, 2019 |
| ASUSTek       | P5KPL-AM                    | [7da787439e](https://linux-hardware.org/?probe=7da787439e) | Sep 11, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| Intel         | D525MW AAE93082-400         | [89a1e0ba41](https://linux-hardware.org/?probe=89a1e0ba41) | Sep 01, 2019 |
| ASUSTek       | P5KPL-AM                    | [11025c5412](https://linux-hardware.org/?probe=11025c5412) | Aug 27, 2019 |
| MSI           | 0AB8                        | [1728939e55](https://linux-hardware.org/?probe=1728939e55) | Aug 22, 2019 |
| ASUSTek       | P5KPL-AM EPU                | [4272d3a201](https://linux-hardware.org/?probe=4272d3a201) | Aug 22, 2019 |
| ASRock        | A320M-HDV R4.0              | [cce7f9292d](https://linux-hardware.org/?probe=cce7f9292d) | Jul 23, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f664fb0c42](https://linux-hardware.org/?probe=f664fb0c42) | Jul 22, 2019 |
| MSI           | H110M PRO-VH PLUS           | [cdce9b48f0](https://linux-hardware.org/?probe=cdce9b48f0) | Jul 20, 2019 |
| Dell          | 02YRK5 A02                  | [18212fdd56](https://linux-hardware.org/?probe=18212fdd56) | Jul 11, 2019 |
| Dell          | 02YRK5 A02                  | [9fa1b2681a](https://linux-hardware.org/?probe=9fa1b2681a) | Jul 10, 2019 |
| Jetway        | TA55MG2-OC                  | [f2e67158f7](https://linux-hardware.org/?probe=f2e67158f7) | Jul 06, 2019 |
| Jetway        | TA55MG2-OC                  | [7ac413972b](https://linux-hardware.org/?probe=7ac413972b) | Jul 06, 2019 |
| Biostar       | R690A-M2T                   | [6c00967a8c](https://linux-hardware.org/?probe=6c00967a8c) | Jul 03, 2019 |
| ASRock        | H61M-VS3                    | [1192feeead](https://linux-hardware.org/?probe=1192feeead) | Jun 20, 2019 |
| HP            | 2B60 MVB                    | [931efec797](https://linux-hardware.org/?probe=931efec797) | Jun 11, 2019 |
| Biostar       | TB250-BTC PRO               | [56d589996a](https://linux-hardware.org/?probe=56d589996a) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [41c5a400a2](https://linux-hardware.org/?probe=41c5a400a2) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [e5699ad7bf](https://linux-hardware.org/?probe=e5699ad7bf) | May 23, 2019 |
| Biostar       | G31M+                       | [ee05f6ce67](https://linux-hardware.org/?probe=ee05f6ce67) | May 20, 2019 |
| Gigabyte      | H310M DS2                   | [229e72bc4f](https://linux-hardware.org/?probe=229e72bc4f) | May 20, 2019 |
| Lenovo        | MAHOBAY NOK                 | [2e7abfe281](https://linux-hardware.org/?probe=2e7abfe281) | May 18, 2019 |
| Dell          | 0WR7PY A02                  | [6e00c71124](https://linux-hardware.org/?probe=6e00c71124) | May 14, 2019 |
| ASUSTek       | P8H67-V                     | [f39c397507](https://linux-hardware.org/?probe=f39c397507) | May 09, 2019 |
| Intel         | Unknown                     | [a467374ecd](https://linux-hardware.org/?probe=a467374ecd) | Apr 25, 2019 |
| ASUSTek       | P5G41C-M LX                 | [e4433722a7](https://linux-hardware.org/?probe=e4433722a7) | Feb 24, 2019 |
| ASUSTek       | P5G41C-M LX                 | [7e4001ef6e](https://linux-hardware.org/?probe=7e4001ef6e) | Feb 24, 2019 |
| MSI           | 785GM-E51                   | [06046973d6](https://linux-hardware.org/?probe=06046973d6) | Jan 08, 2019 |
| ASRock        | Z77 Professional            | [8bc3d31d80](https://linux-hardware.org/?probe=8bc3d31d80) | Dec 03, 2018 |
| ASRock        | Z77 Professional            | [243ff79ac2](https://linux-hardware.org/?probe=243ff79ac2) | Nov 30, 2018 |
| Dell          | 0J3C2F A02                  | [3b377580ad](https://linux-hardware.org/?probe=3b377580ad) | Nov 07, 2018 |
| Dell          | 0J3C2F A02                  | [17cec4b4ca](https://linux-hardware.org/?probe=17cec4b4ca) | Nov 06, 2018 |
| Intel         | DG31PR AAD97573-306         | [cf36e3e24d](https://linux-hardware.org/?probe=cf36e3e24d) | Oct 20, 2018 |
| ASRock        | G41M-VS3                    | [7bb4fff693](https://linux-hardware.org/?probe=7bb4fff693) | Sep 25, 2018 |
| ASUSTek       | P5QPL-VM EPU                | [6c4195dd46](https://linux-hardware.org/?probe=6c4195dd46) | Jul 30, 2018 |
| ASUSTek       | F1A55-M LX PLUS             | [bd4bad9fd4](https://linux-hardware.org/?probe=bd4bad9fd4) | Apr 23, 2017 |
| ASUSTek       | P5KPL-AM SE                 | [5128fdeca3](https://linux-hardware.org/?probe=5128fdeca3) | Dec 07, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 44       | 8.01%   |
| Ubuntu 18.04                 | 32       | 5.83%   |
| Ubuntu 22.04                 | 20       | 3.64%   |
| OpenMandriva 4.3             | 20       | 3.64%   |
| Debian 12                    | 14       | 2.55%   |
| Pop!_OS 22.04                | 12       | 2.19%   |
| Ubuntu 24.04                 | 11       | 2%      |
| Zorin 15                     | 10       | 1.82%   |
| Fedora 42                    | 10       | 1.82%   |
| Arch Rolling                 | 10       | 1.82%   |
| OpenMandriva 25.90           | 9        | 1.64%   |
| OpenMandriva 24.12           | 9        | 1.64%   |
| ArcoLinux Rolling            | 9        | 1.64%   |
| OpenMandriva 4.2             | 8        | 1.46%   |
| Linux Mint 22.1              | 7        | 1.28%   |
| KDE neon 20.04               | 7        | 1.28%   |
| Zorin 17                     | 6        | 1.09%   |
| Zorin 16                     | 6        | 1.09%   |
| OpenMandriva 5.0             | 6        | 1.09%   |
| OpenMandriva 23.03           | 6        | 1.09%   |
| Elementary 6.1               | 6        | 1.09%   |
| OpenMandriva 6.0             | 5        | 0.91%   |
| OpenMandriva 25.06           | 5        | 0.91%   |
| OpenMandriva 25.01           | 5        | 0.91%   |
| OpenMandriva 23.08           | 5        | 0.91%   |
| OpenMandriva 23.01           | 5        | 0.91%   |
| Linux Mint 19.3              | 5        | 0.91%   |
| Fedora 38                    | 5        | 0.91%   |
| EndeavourOS Rolling          | 5        | 0.91%   |
| CachyOS                      | 5        | 0.91%   |
| Xubuntu 20.04                | 4        | 0.73%   |
| Ubuntu Unity 20.04           | 4        | 0.73%   |
| Pop!_OS 20.04                | 4        | 0.73%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 0.73%   |
| OpenMandriva 24.07           | 4        | 0.73%   |
| Linux Mint 22.2              | 4        | 0.73%   |
| Fedora 41                    | 4        | 0.73%   |
| Fedora 35                    | 4        | 0.73%   |
| Fedora 33                    | 4        | 0.73%   |
| Fedora 32                    | 4        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 121      | 23.5%   |
| OpenMandriva  | 90       | 17.48%  |
| Linux Mint    | 40       | 7.77%   |
| Fedora        | 37       | 7.18%   |
| Zorin         | 26       | 5.05%   |
| Debian        | 19       | 3.69%   |
| Pop!_OS       | 18       | 3.5%    |
| Arch          | 14       | 2.72%   |
| Kali          | 13       | 2.52%   |
| Elementary    | 13       | 2.52%   |
| Kubuntu       | 10       | 1.94%   |
| KDE neon      | 10       | 1.94%   |
| Endless       | 9        | 1.75%   |
| ArcoLinux     | 9        | 1.75%   |
| Manjaro       | 8        | 1.55%   |
| Xubuntu       | 6        | 1.17%   |
| MX            | 6        | 1.17%   |
| ROSA          | 5        | 0.97%   |
| openSUSE      | 5        | 0.97%   |
| Lubuntu       | 5        | 0.97%   |
| EndeavourOS   | 5        | 0.97%   |
| CachyOS       | 5        | 0.97%   |
| Bazzite       | 5        | 0.97%   |
| Ubuntu Unity  | 4        | 0.78%   |
| Clear Linux   | 3        | 0.58%   |
| Ubuntu MATE   | 2        | 0.39%   |
| SteamOS       | 2        | 0.39%   |
| Sparky        | 2        | 0.39%   |
| Rocky Linux   | 2        | 0.39%   |
| Nobara        | 2        | 0.39%   |
| LMDE          | 2        | 0.39%   |
| CentOS        | 2        | 0.39%   |
| UbuntuDDE     | 1        | 0.19%   |
| Ubuntu Studio | 1        | 0.19%   |
| RHEL          | 1        | 0.19%   |
| Pikaos        | 1        | 0.19%   |
| Peux OS       | 1        | 0.19%   |
| Parrot        | 1        | 0.19%   |
| Lilidog       | 1        | 0.19%   |
| Gentoo        | 1        | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.14.2-desktop-3omv2590  | 20       | 3.37%   |
| 5.16.7-desktop-1omv4003  | 19       | 3.2%    |
| 5.4.0-42-generic         | 11       | 1.85%   |
| 6.12.1-desktop-1omv2490  | 8        | 1.35%   |
| 5.15.0-56-generic        | 8        | 1.35%   |
| 5.4.0-52-generic         | 7        | 1.18%   |
| 6.8.0-51-generic         | 6        | 1.01%   |
| 6.6.2-desktop-1omv2390   | 6        | 1.01%   |
| 6.2.6-desktop-1omv2390   | 6        | 1.01%   |
| 6.12.9-desktop-1omv2490  | 6        | 1.01%   |
| 5.4.0-26-generic         | 6        | 1.01%   |
| 6.4.11-desktop-1omv2390  | 5        | 0.84%   |
| 5.4.0-58-generic         | 5        | 0.84%   |
| 5.10.14-desktop-1omv4002 | 5        | 0.84%   |
| 6.14.0-36-generic        | 4        | 0.67%   |
| 5.8.0-14-generic         | 4        | 0.67%   |
| 5.4.0-80-generic         | 4        | 0.67%   |
| 5.3.0-28-generic         | 4        | 0.67%   |
| 6.9.3-76060903-generic   | 3        | 0.51%   |
| 6.8.0-40-generic         | 3        | 0.51%   |
| 6.5.0-14-generic         | 3        | 0.51%   |
| 6.16.3-76061603-generic  | 3        | 0.51%   |
| 6.14.0-63.fc42.x86_64    | 3        | 0.51%   |
| 6.12.25-amd64            | 3        | 0.51%   |
| 6.10.0-desktop-1omv2490  | 3        | 0.51%   |
| 6.1.1-desktop-1omv2290   | 3        | 0.51%   |
| 5.4.0-81-generic         | 3        | 0.51%   |
| 5.15.0-43-generic        | 3        | 0.51%   |
| 5.13.0-41-generic        | 3        | 0.51%   |
| 5.11.12-desktop-1omv4002 | 3        | 0.51%   |
| 5.11.0-43-generic        | 3        | 0.51%   |
| 6.8.0-60-generic         | 2        | 0.34%   |
| 6.8.0-59-generic         | 2        | 0.34%   |
| 6.8.0-55-generic         | 2        | 0.34%   |
| 6.8.0-54-generic         | 2        | 0.34%   |
| 6.8.0-41-generic         | 2        | 0.34%   |
| 6.6.9-200.fc39.x86_64    | 2        | 0.34%   |
| 6.5.6-76060506-generic   | 2        | 0.34%   |
| 6.5.5-desktop-1omv2390   | 2        | 0.34%   |
| 6.3.8-200.fc38.x86_64    | 2        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 66       | 11.58%  |
| 5.15.0  | 29       | 5.09%   |
| 6.8.0   | 27       | 4.74%   |
| 6.14.2  | 21       | 3.68%   |
| 5.16.7  | 20       | 3.51%   |
| 6.14.0  | 17       | 2.98%   |
| 4.15.0  | 17       | 2.98%   |
| 5.8.0   | 16       | 2.81%   |
| 5.11.0  | 15       | 2.63%   |
| 5.3.0   | 14       | 2.46%   |
| 5.13.0  | 13       | 2.28%   |
| 4.18.0  | 13       | 2.28%   |
| 6.5.0   | 12       | 2.11%   |
| 6.1.0   | 12       | 2.11%   |
| 5.0.0   | 9        | 1.58%   |
| 6.12.1  | 8        | 1.4%    |
| 5.10.0  | 8        | 1.4%    |
| 6.2.6   | 7        | 1.23%   |
| 6.6.2   | 6        | 1.05%   |
| 6.12.9  | 6        | 1.05%   |
| 6.1.1   | 6        | 1.05%   |
| 5.19.0  | 6        | 1.05%   |
| 6.4.11  | 5        | 0.88%   |
| 6.2.0   | 5        | 0.88%   |
| 5.10.14 | 5        | 0.88%   |
| 6.5.5   | 4        | 0.7%    |
| 6.11.0  | 4        | 0.7%    |
| 6.9.7   | 3        | 0.53%   |
| 6.9.3   | 3        | 0.53%   |
| 6.6.9   | 3        | 0.53%   |
| 6.5.6   | 3        | 0.53%   |
| 6.16.3  | 3        | 0.53%   |
| 6.12.25 | 3        | 0.53%   |
| 6.10.0  | 3        | 0.53%   |
| 5.9.16  | 3        | 0.53%   |
| 5.14.0  | 3        | 0.53%   |
| 5.11.12 | 3        | 0.53%   |
| 6.7.9   | 2        | 0.35%   |
| 6.6.34  | 2        | 0.35%   |
| 6.5.4   | 2        | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 67       | 11.92%  |
| 6.14    | 43       | 7.65%   |
| 5.15    | 32       | 5.69%   |
| 6.12    | 30       | 5.34%   |
| 6.8     | 29       | 5.16%   |
| 6.5     | 24       | 4.27%   |
| 6.1     | 24       | 4.27%   |
| 5.10    | 24       | 4.27%   |
| 5.16    | 23       | 4.09%   |
| 5.11    | 20       | 3.56%   |
| 5.8     | 19       | 3.38%   |
| 6.6     | 17       | 3.02%   |
| 6.2     | 17       | 3.02%   |
| 4.15    | 17       | 3.02%   |
| 5.13    | 16       | 2.85%   |
| 5.3     | 14       | 2.49%   |
| 4.18    | 13       | 2.31%   |
| 6.4     | 12       | 2.14%   |
| 6.16    | 11       | 1.96%   |
| 6.9     | 10       | 1.78%   |
| 6.0     | 9        | 1.6%    |
| 5.0     | 9        | 1.6%    |
| 6.11    | 8        | 1.42%   |
| 5.19    | 8        | 1.42%   |
| 6.3     | 7        | 1.25%   |
| 6.10    | 7        | 1.25%   |
| 6.13    | 5        | 0.89%   |
| 5.14    | 5        | 0.89%   |
| 6.7     | 4        | 0.71%   |
| 6.17    | 4        | 0.71%   |
| 5.17    | 4        | 0.71%   |
| 5.12    | 4        | 0.71%   |
| 6.15    | 3        | 0.53%   |
| 5.9     | 3        | 0.53%   |
| 5.7     | 3        | 0.53%   |
| 5.6     | 3        | 0.53%   |
| 5.18    | 3        | 0.53%   |
| 4.9     | 3        | 0.53%   |
| 4.19    | 2        | 0.36%   |
| 6.18    | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 492      | 98.2%   |
| i686   | 9        | 1.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 196      | 37.48%  |
| KDE5              | 83       | 15.87%  |
| KDE6              | 54       | 10.33%  |
| Unknown           | 49       | 9.37%   |
| XFCE              | 40       | 7.65%   |
| X-Cinnamon        | 33       | 6.31%   |
| LXQt              | 15       | 2.87%   |
| Pantheon          | 12       | 2.29%   |
| MATE              | 8        | 1.53%   |
| Unity             | 4        | 0.76%   |
| KDE               | 4        | 0.76%   |
| lightdm-xsession  | 3        | 0.57%   |
| i3                | 3        | 0.57%   |
| Deepin            | 3        | 0.57%   |
| Cinnamon          | 3        | 0.57%   |
| Yaru:ubuntu:GNOME | 2        | 0.38%   |
| KDE4              | 2        | 0.38%   |
| Peux Gnome        | 1        | 0.19%   |
| LXDE              | 1        | 0.19%   |
| ICEWM             | 1        | 0.19%   |
| GNOME Flashback   | 1        | 0.19%   |
| DWM               | 1        | 0.19%   |
| Cutefish          | 1        | 0.19%   |
| COSMIC            | 1        | 0.19%   |
| Budgie            | 1        | 0.19%   |
| Bspwm             | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 346      | 66.8%   |
| Wayland | 132      | 25.48%  |
| Unknown | 31       | 5.98%   |
| Tty     | 9        | 1.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 242      | 46.18%  |
| SDDM           | 122      | 23.28%  |
| LightDM        | 53       | 10.11%  |
| GDM3           | 52       | 9.92%   |
| GDM            | 46       | 8.78%   |
| TDM            | 6        | 1.15%   |
| KDM            | 2        | 0.38%   |
| COSMIC-GREETER | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 406      | 79.92%  |
| id_ID   | 42       | 8.27%   |
| Unknown | 36       | 7.09%   |
| C       | 11       | 2.17%   |
| en_GB   | 5        | 0.98%   |
| it_IT   | 1        | 0.2%    |
| en_SG   | 1        | 0.2%    |
| en_IN   | 1        | 0.2%    |
| en_CA   | 1        | 0.2%    |
| en_AU   | 1        | 0.2%    |
| en_AG   | 1        | 0.2%    |
| de_DE   | 1        | 0.2%    |
| Default | 1        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 318      | 61.75%  |
| EFI  | 197      | 38.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 356      | 69.26%  |
| Btrfs   | 58       | 11.28%  |
| Overlay | 56       | 10.89%  |
| Tmpfs   | 23       | 4.47%   |
| Unknown | 11       | 2.14%   |
| Xfs     | 9        | 1.75%   |
| Zfs     | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 240      | 46.42%  |
| GPT     | 204      | 39.46%  |
| MBR     | 73       | 14.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 429      | 83.46%  |
| Yes       | 85       | 16.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 300      | 57.92%  |
| Yes       | 218      | 42.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 77       | 15.37%  |
| ASRock                               | 77       | 15.37%  |
| Gigabyte Technology                  | 74       | 14.77%  |
| MSI                                  | 58       | 11.58%  |
| Dell                                 | 34       | 6.79%   |
| Intel                                | 29       | 5.79%   |
| Hewlett-Packard                      | 28       | 5.59%   |
| Biostar                              | 24       | 4.79%   |
| Lenovo                               | 22       | 4.39%   |
| ECS                                  | 22       | 4.39%   |
| Acer                                 | 11       | 2.2%    |
| Unknown                              | 10       | 2%      |
| AZW                                  | 4        | 0.8%    |
| Foxconn                              | 3        | 0.6%    |
| Pegatron                             | 2        | 0.4%    |
| OEM                                  | 2        | 0.4%    |
| LORD ELECTRONICS                     | 2        | 0.4%    |
| ZYREX COMPUTER SYSTEMS               | 1        | 0.2%    |
| ZOTAC                                | 1        | 0.2%    |
| wolfNfox computer                    | 1        | 0.2%    |
| Wearnes                              | 1        | 0.2%    |
| venomRX                              | 1        | 0.2%    |
| TriGem Computer                      | 1        | 0.2%    |
| SPECTRUM UTAMA                       | 1        | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 1        | 0.2%    |
| Samsung Electronics                  | 1        | 0.2%    |
| Quanta                               | 1        | 0.2%    |
| PC Partner Limited                   | 1        | 0.2%    |
| Nvidia                               | 1        | 0.2%    |
| NEC Computers                        | 1        | 0.2%    |
| Minix                                | 1        | 0.2%    |
| Koloe                                | 1        | 0.2%    |
| Jetway                               | 1        | 0.2%    |
| Inventec                             | 1        | 0.2%    |
| Huanan                               | 1        | 0.2%    |
| GEEKOM                               | 1        | 0.2%    |
| GALAX                                | 1        | 0.2%    |
| Colorful Technology                  | 1        | 0.2%    |
| AISURIX                              | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 13       | 2.59%   |
| Intel H61                                         | 11       | 2.2%    |
| ASUS All Series                                   | 8        | 1.6%    |
| Dell OptiPlex 7010                                | 6        | 1.2%    |
| ASRock A320M-HDV R4.0                             | 6        | 1.2%    |
| Gigabyte H81M-DS2                                 | 4        | 0.8%    |
| Gigabyte H61M-DS2                                 | 4        | 0.8%    |
| ASRock FM2A68M-DG3+                               | 4        | 0.8%    |
| ASRock B550M Pro4                                 | 4        | 0.8%    |
| MSI MS-7C52                                       | 3        | 0.6%    |
| MSI MS-7A37                                       | 3        | 0.6%    |
| Intel H55                                         | 3        | 0.6%    |
| Intel B75                                         | 3        | 0.6%    |
| ECS H61H2-MV                                      | 3        | 0.6%    |
| Dell Inspiron 580                                 | 3        | 0.6%    |
| ASUS P5KPL-AM SE                                  | 3        | 0.6%    |
| ASUS P5G41T-M LX                                  | 3        | 0.6%    |
| ASUS H110M-E/M.2                                  | 3        | 0.6%    |
| ASRock X300M-STX                                  | 3        | 0.6%    |
| ASRock B560M Pro4                                 | 3        | 0.6%    |
| ASRock B450 Pro4                                  | 3        | 0.6%    |
| ASRock AB350 Pro4                                 | 3        | 0.6%    |
| ASRock A88M-G                                     | 3        | 0.6%    |
| ASRock A320M-HDV                                  | 3        | 0.6%    |
| MSI MS-7D43                                       | 2        | 0.4%    |
| MSI MS-7C96                                       | 2        | 0.4%    |
| MSI MS-7C02                                       | 2        | 0.4%    |
| MSI MS-7B22                                       | 2        | 0.4%    |
| MSI MS-7823                                       | 2        | 0.4%    |
| MSI MS-7817                                       | 2        | 0.4%    |
| MSI MS-7788                                       | 2        | 0.4%    |
| MSI MS-7758                                       | 2        | 0.4%    |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 2        | 0.4%    |
| Lenovo ThinkCentre A70 7099S3A                    | 2        | 0.4%    |
| HP ProDesk 400 G2 MT (TPM DP)                     | 2        | 0.4%    |
| Gigabyte GA-78LMT-USB3 6.0                        | 2        | 0.4%    |
| Gigabyte G31M-ES2L                                | 2        | 0.4%    |
| Gigabyte B550M DS3H                               | 2        | 0.4%    |
| Gigabyte B550M AORUS PRO                          | 2        | 0.4%    |
| Gigabyte B460MDS3H                                | 2        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 22       | 4.39%   |
| Lenovo ThinkCentre     | 13       | 2.59%   |
| Unknown                | 13       | 2.59%   |
| Intel H61              | 11       | 2.2%    |
| ASUS PRIME             | 11       | 2.2%    |
| ASUS ROG               | 9        | 1.8%    |
| ASRock A320M-HDV       | 9        | 1.8%    |
| ASUS All               | 8        | 1.6%    |
| Acer Veriton           | 7        | 1.4%    |
| HP ProDesk             | 6        | 1.2%    |
| Dell Inspiron          | 6        | 1.2%    |
| ASUS TUF               | 6        | 1.2%    |
| ASUS P5KPL-AM          | 6        | 1.2%    |
| HP Compaq              | 5        | 1%      |
| Gigabyte H61M-DS2      | 5        | 1%      |
| Gigabyte B550M         | 5        | 1%      |
| ASRock B550M           | 5        | 1%      |
| Gigabyte H81M-DS2      | 4        | 0.8%    |
| ASUS P5G41T-M          | 4        | 0.8%    |
| ASRock FM2A68M-DG3+    | 4        | 0.8%    |
| Acer Aspire            | 4        | 0.8%    |
| MSI MS-7C52            | 3        | 0.6%    |
| MSI MS-7A37            | 3        | 0.6%    |
| Lenovo IdeaCentre      | 3        | 0.6%    |
| Intel H55              | 3        | 0.6%    |
| Intel B75              | 3        | 0.6%    |
| Gigabyte GA-78LMT-USB3 | 3        | 0.6%    |
| ECS H61H2-MV           | 3        | 0.6%    |
| Dell Vostro            | 3        | 0.6%    |
| ASUS P8H61-M           | 3        | 0.6%    |
| ASUS H110M-E           | 3        | 0.6%    |
| ASRock X300M-STX       | 3        | 0.6%    |
| ASRock B650M           | 3        | 0.6%    |
| ASRock B560M           | 3        | 0.6%    |
| ASRock B450            | 3        | 0.6%    |
| ASRock AB350           | 3        | 0.6%    |
| ASRock A88M-G          | 3        | 0.6%    |
| MSI MS-7D43            | 2        | 0.4%    |
| MSI MS-7C96            | 2        | 0.4%    |
| MSI MS-7C02            | 2        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 51       | 10.18%  |
| 2012 | 48       | 9.58%   |
| 2020 | 46       | 9.18%   |
| 2014 | 42       | 8.38%   |
| 2011 | 39       | 7.78%   |
| 2010 | 38       | 7.58%   |
| 2018 | 34       | 6.79%   |
| 2009 | 31       | 6.19%   |
| 2017 | 30       | 5.99%   |
| 2019 | 26       | 5.19%   |
| 2021 | 24       | 4.79%   |
| 2016 | 20       | 3.99%   |
| 2008 | 19       | 3.79%   |
| 2015 | 18       | 3.59%   |
| 2023 | 10       | 2%      |
| 2022 | 8        | 1.6%    |
| 2007 | 8        | 1.6%    |
| 2024 | 5        | 1%      |
| 2025 | 2        | 0.4%    |
| 2006 | 2        | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 501      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 491      | 98%     |
| Enabled  | 10       | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 501      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 110      | 21.57%  |
| 3.01-4.0    | 107      | 20.98%  |
| 16.01-24.0  | 103      | 20.2%   |
| 4.01-8.0    | 98       | 19.22%  |
| 32.01-64.0  | 47       | 9.22%   |
| 1.01-2.0    | 15       | 2.94%   |
| 24.01-32.0  | 13       | 2.55%   |
| 64.01-256.0 | 11       | 2.16%   |
| 2.01-3.0    | 6        | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 190      | 33.51%  |
| 2.01-3.0   | 156      | 27.51%  |
| 4.01-8.0   | 85       | 14.99%  |
| 3.01-4.0   | 75       | 13.23%  |
| 0.51-1.0   | 34       | 6%      |
| 8.01-16.0  | 15       | 2.65%   |
| 16.01-24.0 | 5        | 0.88%   |
| 0.01-0.5   | 4        | 0.71%   |
| 32.01-64.0 | 2        | 0.35%   |
| 24.01-32.0 | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 241      | 46.17%  |
| 2      | 160      | 30.65%  |
| 3      | 67       | 12.84%  |
| 4      | 30       | 5.75%   |
| 5      | 13       | 2.49%   |
| 7      | 3        | 0.57%   |
| 6      | 3        | 0.57%   |
| 0      | 2        | 0.38%   |
| 15     | 1        | 0.19%   |
| 12     | 1        | 0.19%   |
| 8      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 376      | 73.73%  |
| Yes       | 134      | 26.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 494      | 98.6%   |
| No        | 7        | 1.4%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 279      | 54.92%  |
| No        | 229      | 45.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 367      | 72.39%  |
| Yes       | 140      | 27.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Indonesia | 501      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Jakarta         | 125      | 23.02%  |
| Bandung         | 54       | 9.94%   |
| Surabaya        | 32       | 5.89%   |
| Yogyakarta      | 28       | 5.16%   |
| Semarang        | 19       | 3.5%    |
| Bekasi          | 19       | 3.5%    |
| Malang          | 18       | 3.31%   |
| Medan           | 17       | 3.13%   |
| Tangerang       | 15       | 2.76%   |
| South Tangerang | 13       | 2.39%   |
| Bogor           | 11       | 2.03%   |
| Palembang       | 10       | 1.84%   |
| Depok           | 9        | 1.66%   |
| Denpasar        | 8        | 1.47%   |
| Banjarmasin     | 8        | 1.47%   |
| Surakarta       | 7        | 1.29%   |
| Pasuruan        | 6        | 1.1%    |
| Sleman          | 5        | 0.92%   |
| Kediri          | 5        | 0.92%   |
| Batam           | 5        | 0.92%   |
| Srengseng Sawah | 4        | 0.74%   |
| Pekalongan      | 4        | 0.74%   |
| Makassar        | 4        | 0.74%   |
| Magelang        | 4        | 0.74%   |
| Sidoarjo        | 3        | 0.55%   |
| Salatiga        | 3        | 0.55%   |
| Pekanbaru       | 3        | 0.55%   |
| Gresik          | 3        | 0.55%   |
| Cirebon         | 3        | 0.55%   |
| Tinjomoyo       | 2        | 0.37%   |
| Tasikmalaya     | 2        | 0.37%   |
| Tanjung Pinang  | 2        | 0.37%   |
| Sukabumi        | 2        | 0.37%   |
| Purwokerto      | 2        | 0.37%   |
| Pontianak       | 2        | 0.37%   |
| Palu            | 2        | 0.37%   |
| Mataram         | 2        | 0.37%   |
| Klaten          | 2        | 0.37%   |
| Karawang        | 2        | 0.37%   |
| Jember          | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 229      | 326    | 26.32%  |
| WDC                         | 151      | 228    | 17.36%  |
| Samsung Electronics         | 58       | 81     | 6.67%   |
| Toshiba                     | 39       | 48     | 4.48%   |
| A-DATA Technology           | 31       | 38     | 3.56%   |
| Hitachi                     | 28       | 40     | 3.22%   |
| V-GeN                       | 21       | 25     | 2.41%   |
| SanDisk                     | 21       | 26     | 2.41%   |
| ADATA Technology            | 21       | 35     | 2.41%   |
| China                       | 18       | 21     | 2.07%   |
| Silicon Motion              | 16       | 19     | 1.84%   |
| Kingston                    | 15       | 20     | 1.72%   |
| MidasForce                  | 13       | 16     | 1.49%   |
| Unknown                     | 13       | 15     | 1.49%   |
| Unknown                     | 11       | 18     | 1.26%   |
| HGST                        | 11       | 17     | 1.26%   |
| Team                        | 9        | 11     | 1.03%   |
| RX7                         | 8        | 10     | 0.92%   |
| RESCUE                      | 8        | 14     | 0.92%   |
| Patriot                     | 8        | 19     | 0.92%   |
| Apacer                      | 8        | 11     | 0.92%   |
| XPG                         | 6        | 9      | 0.69%   |
| Transcend                   | 6        | 9      | 0.69%   |
| Phison Electronics          | 6        | 6      | 0.69%   |
| Pioneer                     | 5        | 6      | 0.57%   |
| Intel                       | 5        | 5      | 0.57%   |
| T-FORCE                     | 4        | 4      | 0.46%   |
| Realtek Semiconductor       | 4        | 4      | 0.46%   |
| PNY                         | 4        | 6      | 0.46%   |
| Maxtor                      | 4        | 4      | 0.46%   |
| MAXIO Technology (Hangzhou) | 4        | 4      | 0.46%   |
| Varro                       | 3        | 3      | 0.34%   |
| SK hynix                    | 3        | 4      | 0.34%   |
| OCZ                         | 3        | 3      | 0.34%   |
| JMicron Technology          | 3        | 3      | 0.34%   |
| Hewlett-Packard             | 3        | 3      | 0.34%   |
| EYOTA                       | 3        | 3      | 0.34%   |
| Colorful                    | 3        | 3      | 0.34%   |
| Biostar                     | 3        | 4      | 0.34%   |
| XSTAR                       | 2        | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                                    | 33       | 3.38%   |
| Seagate ST3500312CS 500GB                                          | 26       | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 16       | 1.64%   |
| Unknown                                                            | 13       | 1.33%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 12       | 1.23%   |
| A-DATA SU650 120GB SSD                                             | 11       | 1.13%   |
| Seagate ST3250318AS 250GB                                          | 10       | 1.03%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB              | 9        | 0.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 9        | 0.92%   |
| Toshiba DT01ACA200 2TB                                             | 8        | 0.82%   |
| Seagate ST3500418AS 500GB                                          | 8        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 7        | 0.72%   |
| Kingston SA400S37120G 120GB SSD                                    | 7        | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 6        | 0.62%   |
| Seagate ST9320325AS 320GB                                          | 6        | 0.62%   |
| Seagate ST250DM000-1BD141 250GB                                    | 6        | 0.62%   |
| Samsung SSD 860 EVO 250GB                                          | 6        | 0.62%   |
| WDC WD5000AAKX-75U6AA0 500GB                                       | 5        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB                                           | 5        | 0.51%   |
| Toshiba HDWD110 1TB                                                | 5        | 0.51%   |
| Toshiba DT01ACA100 1TB                                             | 5        | 0.51%   |
| Seagate ST3500413AS 500GB                                          | 5        | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB                                     | 5        | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                                     | 5        | 0.51%   |
| MidasForce SSD 120GB                                               | 5        | 0.51%   |
| HGST HTS545050A7E380 500GB                                         | 5        | 0.51%   |
| Apacer AS340 240GB SSD                                             | 5        | 0.51%   |
| A-DATA SU650 240GB SSD                                             | 5        | 0.51%   |
| WDC WD20EZBX-00AYRA0 2TB                                           | 4        | 0.41%   |
| WDC WD10EZEX-00WN4A0 1TB                                           | 4        | 0.41%   |
| Toshiba DT01ACA050 500GB                                           | 4        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB                                    | 4        | 0.41%   |
| Seagate ST380215AS 80GB                                            | 4        | 0.41%   |
| Seagate ST3160815AS 160GB                                          | 4        | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB                                     | 4        | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB                                     | 4        | 0.41%   |
| SanDisk SSD PLUS 240GB                                             | 4        | 0.41%   |
| Samsung SSD 850 120GB                                              | 4        | 0.41%   |
| Phison PS5013 E13 NVMe Controller 500GB                            | 4        | 0.41%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB                   | 4        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 227      | 320    | 47.99%  |
| WDC                 | 137      | 208    | 28.96%  |
| Toshiba             | 38       | 47     | 8.03%   |
| Hitachi             | 28       | 40     | 5.92%   |
| HGST                | 11       | 17     | 2.33%   |
| Samsung Electronics | 9        | 9      | 1.9%    |
| Unknown             | 4        | 5      | 0.85%   |
| Maxtor              | 4        | 4      | 0.85%   |
| JMicron Technology  | 2        | 2      | 0.42%   |
| Hewlett-Packard     | 2        | 2      | 0.42%   |
| Fujitsu             | 2        | 2      | 0.42%   |
| External            | 2        | 2      | 0.42%   |
| Unknown             | 2        | 2      | 0.42%   |
| TO Exter            | 1        | 1      | 0.21%   |
| SATAFIRM            | 1        | 1      | 0.21%   |
| ExcelStor           | 1        | 1      | 0.21%   |
| CLOVER              | 1        | 1      | 0.21%   |
| Apple               | 1        | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 35       | 50     | 13.78%  |
| A-DATA Technology   | 23       | 28     | 9.06%   |
| China               | 17       | 20     | 6.69%   |
| WDC                 | 15       | 16     | 5.91%   |
| V-GeN               | 15       | 19     | 5.91%   |
| Kingston            | 14       | 19     | 5.51%   |
| MidasForce          | 13       | 16     | 5.12%   |
| SanDisk             | 12       | 15     | 4.72%   |
| Patriot             | 8        | 19     | 3.15%   |
| Apacer              | 8        | 11     | 3.15%   |
| RESCUE              | 7        | 13     | 2.76%   |
| Unknown             | 7        | 9      | 2.76%   |
| RX7                 | 6        | 6      | 2.36%   |
| Transcend           | 5        | 8      | 1.97%   |
| Pioneer             | 5        | 6      | 1.97%   |
| Team                | 4        | 6      | 1.57%   |
| T-FORCE             | 4        | 4      | 1.57%   |
| Unknown             | 3        | 4      | 1.18%   |
| Seagate             | 3        | 6      | 1.18%   |
| OCZ                 | 3        | 3      | 1.18%   |
| Colorful            | 3        | 3      | 1.18%   |
| XSTAR               | 2        | 2      | 0.79%   |
| Varro               | 2        | 2      | 0.79%   |
| Ramos Technology    | 2        | 2      | 0.79%   |
| PNY                 | 2        | 2      | 0.79%   |
| KYO                 | 2        | 2      | 0.79%   |
| JOINT               | 2        | 3      | 0.79%   |
| Intel               | 2        | 2      | 0.79%   |
| Biostar             | 2        | 3      | 0.79%   |
| ADATA SU            | 2        | 2      | 0.79%   |
| Wellcomm            | 1        | 1      | 0.39%   |
| VISIPRO             | 1        | 1      | 0.39%   |
| Verbatim            | 1        | 1      | 0.39%   |
| Toshiba             | 1        | 1      | 0.39%   |
| SS-200              | 1        | 1      | 0.39%   |
| SPCC                | 1        | 1      | 0.39%   |
| SK hynix            | 1        | 2      | 0.39%   |
| OVATION             | 1        | 1      | 0.39%   |
| Netac               | 1        | 1      | 0.39%   |
| Memory              | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 374      | 665    | 52.53%  |
| SSD     | 210      | 334    | 29.49%  |
| NVMe    | 105      | 160    | 14.75%  |
| Unknown | 22       | 28     | 3.09%   |
| MMC     | 1        | 4      | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 461      | 995    | 77.61%  |
| NVMe | 105      | 158    | 17.68%  |
| SAS  | 27       | 34     | 4.55%   |
| MMC  | 1        | 4      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 369      | 668    | 61.81%  |
| 0.51-1.0   | 138      | 211    | 23.12%  |
| 1.01-2.0   | 57       | 79     | 9.55%   |
| 3.01-4.0   | 14       | 20     | 2.35%   |
| 2.01-3.0   | 9        | 9      | 1.51%   |
| 4.01-10.0  | 9        | 11     | 1.51%   |
| 10.01-20.0 | 1        | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 143      | 26.53%  |
| 251-500        | 104      | 19.29%  |
| 501-1000       | 68       | 12.62%  |
| 1-20           | 48       | 8.91%   |
| 1001-2000      | 43       | 7.98%   |
| 51-100         | 41       | 7.61%   |
| More than 3000 | 31       | 5.75%   |
| 21-50          | 29       | 5.38%   |
| 2001-3000      | 18       | 3.34%   |
| Unknown        | 14       | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 212      | 38.55%  |
| 21-50          | 96       | 17.45%  |
| 101-250        | 61       | 11.09%  |
| 51-100         | 55       | 10%     |
| 251-500        | 42       | 7.64%   |
| 501-1000       | 25       | 4.55%   |
| 1001-2000      | 22       | 4%      |
| Unknown        | 14       | 2.55%   |
| More than 3000 | 13       | 2.36%   |
| 2001-3000      | 9        | 1.64%   |
| 0              | 1        | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Desktops | Drives | Percent |
|-------------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 12       | 14     | 9.68%   |
| Seagate ST9320325AS 320GB                             | 3        | 4      | 2.42%   |
| Seagate ST9250410AS 250GB                             | 3        | 5      | 2.42%   |
| Seagate ST250DM000-1BD141 250GB                       | 3        | 3      | 2.42%   |
| Seagate ST1000DM003-1ER162 1TB                        | 3        | 3      | 2.42%   |
| HGST HTS545050A7E380 500GB                            | 3        | 4      | 2.42%   |
| WDC WD800JD-08LSA0 80GB                               | 2        | 2      | 1.61%   |
| WDC WD3200AAKS-61L9A0 320GB                           | 2        | 3      | 1.61%   |
| WDC WD2000FYYZ-01UL1B1 2TB                            | 2        | 3      | 1.61%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 2        | 2      | 1.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2        | 3      | 1.61%   |
| Seagate ST3500418AS 500GB                             | 2        | 2      | 1.61%   |
| Seagate ST3500312CS 500GB                             | 2        | 5      | 1.61%   |
| Seagate ST1000DM010-2EP102 1TB                        | 2        | 2      | 1.61%   |
| Hitachi HDS721680PLA380 80GB                          | 2        | 2      | 1.61%   |
| WDC WD80EZZX-11CSGA0 8TB                              | 1        | 2      | 0.81%   |
| WDC WD7500BPVT-55HXZT4 752GB                          | 1        | 1      | 0.81%   |
| WDC WD6400AADS-00M2B0 640GB                           | 1        | 1      | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 1        | 2      | 0.81%   |
| WDC WD5000AZLX-60K2TA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AZLX-00JKKA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-75U6AA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-22ERMA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-08U6AA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-08ERMA0 500GB                          | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-083CA1 500GB                           | 1        | 1      | 0.81%   |
| WDC WD5000AAKX-001CA0 500GB                           | 1        | 1      | 0.81%   |
| WDC WD5000AADS-00M2B0 500GB                           | 1        | 1      | 0.81%   |
| WDC WD5000AACS-00G8B0 500GB                           | 1        | 1      | 0.81%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 1        | 1      | 0.81%   |
| WDC WD40EFRX-68WT0N0 4TB                              | 1        | 1      | 0.81%   |
| WDC WD3200JS-63PDB1 320GB                             | 1        | 1      | 0.81%   |
| WDC WD3200BPVT-00HXZT1 320GB                          | 1        | 1      | 0.81%   |
| WDC WD3200AVJS-63B6A0 320GB                           | 1        | 1      | 0.81%   |
| WDC WD3200AAKX-001CA0 320GB                           | 1        | 1      | 0.81%   |
| WDC WD3200AAJS-61B4A0 320GB                           | 1        | 1      | 0.81%   |
| WDC WD3200AAJS-08B4A0 320GB                           | 1        | 1      | 0.81%   |
| WDC WD30EZRZ-00Z5HB0 3TB                              | 1        | 1      | 0.81%   |
| WDC WD30EZRX-00MMMB0 3TB                              | 1        | 1      | 0.81%   |
| WDC WD30EFRX-68AX9N0 3TB                              | 1        | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 46       | 61     | 39.66%  |
| WDC                 | 35       | 44     | 30.17%  |
| Hitachi             | 9        | 10     | 7.76%   |
| HGST                | 5        | 6      | 4.31%   |
| Samsung Electronics | 3        | 3      | 2.59%   |
| Kingston            | 3        | 4      | 2.59%   |
| Silicon Motion      | 2        | 3      | 1.72%   |
| SanDisk             | 2        | 2      | 1.72%   |
| Fujitsu             | 2        | 2      | 1.72%   |
| Unknown             | 1        | 1      | 0.86%   |
| Toshiba             | 1        | 1      | 0.86%   |
| T-FORCE             | 1        | 1      | 0.86%   |
| Maxtor              | 1        | 1      | 0.86%   |
| CLOVER              | 1        | 1      | 0.86%   |
| China               | 1        | 1      | 0.86%   |
| Apple               | 1        | 1      | 0.86%   |
| Apacer              | 1        | 2      | 0.86%   |
| Unknown             | 1        | 1      | 0.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 57     | 43.27%  |
| WDC                 | 35       | 44     | 33.65%  |
| Hitachi             | 9        | 10     | 8.65%   |
| HGST                | 5        | 6      | 4.81%   |
| Samsung Electronics | 2        | 2      | 1.92%   |
| Fujitsu             | 2        | 2      | 1.92%   |
| Unknown             | 1        | 1      | 0.96%   |
| Toshiba             | 1        | 1      | 0.96%   |
| Maxtor              | 1        | 1      | 0.96%   |
| CLOVER              | 1        | 1      | 0.96%   |
| Apple               | 1        | 1      | 0.96%   |
| Unknown             | 1        | 1      | 0.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 88       | 127    | 88.89%  |
| SSD  | 9        | 15     | 9.09%   |
| NVMe | 2        | 3      | 2.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 2      | 33.33%  |
| Seagate ST3250318AS 250GB       | 2        | 2      | 33.33%  |
| Toshiba MK6475GSX 640GB         | 1        | 1      | 16.67%  |
| Hitachi HTS545050B9A300 500GB   | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 66.67%  |
| Toshiba | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 283      | 587    | 48.29%  |
| Works    | 201      | 453    | 34.3%   |
| Malfunc  | 97       | 145    | 16.55%  |
| Failed   | 5        | 6      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 352      | 54.07%  |
| AMD                          | 141      | 21.66%  |
| ADATA Technology             | 33       | 5.07%   |
| Silicon Motion               | 21       | 3.23%   |
| Samsung Electronics          | 17       | 2.61%   |
| ASMedia Technology           | 16       | 2.46%   |
| SanDisk                      | 12       | 1.84%   |
| Phison Electronics           | 11       | 1.69%   |
| JMicron Technology           | 10       | 1.54%   |
| Realtek Semiconductor        | 7        | 1.08%   |
| MAXIO Technology (Hangzhou)  | 6        | 0.92%   |
| Marvell Technology Group     | 5        | 0.77%   |
| VIA Technologies             | 4        | 0.61%   |
| Nvidia                       | 3        | 0.46%   |
| Kingston Technology Company  | 3        | 0.46%   |
| SK hynix                     | 2        | 0.31%   |
| Solidigm                     | 1        | 0.15%   |
| Shenzhen Longsys Electronics | 1        | 0.15%   |
| Seagate Technology           | 1        | 0.15%   |
| O2 Micro                     | 1        | 0.15%   |
| INNOGRIT                     | 1        | 0.15%   |
| Hosin Global Electronics     | 1        | 0.15%   |
| Broadcom / LSI               | 1        | 0.15%   |
| Biwin Storage Technology     | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 60       | 7.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 55       | 6.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 40       | 4.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 39       | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 39       | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 32       | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 32       | 3.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 2.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 23       | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21       | 2.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 20       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 2.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17       | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 1.91%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 16       | 1.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 1.67%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 14       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 1.55%   |
| AMD FCH IDE Controller                                                                  | 13       | 1.55%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 1.43%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.43%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 11       | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10       | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 1.07%   |
| AMD 600 Series Chipset SATA Controller                                                  | 9        | 1.07%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 8        | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 6        | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 6        | 0.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.72%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 5        | 0.6%    |
| JMicron JMB368 IDE controller                                                           | 5        | 0.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 370      | 56.66%  |
| IDE  | 161      | 24.66%  |
| NVMe | 105      | 16.08%  |
| RAID | 15       | 2.3%    |
| SAS  | 2        | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 352      | 70.26%  |
| AMD    | 149      | 29.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 12       | 2.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 11       | 2.19%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 1.99%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 1.99%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 9        | 1.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 9        | 1.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 1.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 1.59%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 8        | 1.59%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 7        | 1.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 1.39%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 6        | 1.19%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 6        | 1.19%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 6        | 1.19%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 6        | 1.19%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 6        | 1.19%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.99%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.99%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.99%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 0.99%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4        | 0.8%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 0.8%    |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 0.8%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 4        | 0.8%    |
| Intel Core i3-2130 CPU @ 3.40GHz            | 4        | 0.8%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.8%    |
| AMD Ryzen 5 5600 6-Core Processor           | 4        | 0.8%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.8%    |
| AMD Phenom II X6 1055T Processor            | 4        | 0.8%    |
| AMD FX-6300 Six-Core Processor              | 4        | 0.8%    |
| AMD Athlon 3000G with Radeon Vega Graphics  | 4        | 0.8%    |
| AMD A6-6400K APU with Radeon HD Graphics    | 4        | 0.8%    |
| Intel Pentium CPU G3240 @ 3.10GHz           | 3        | 0.6%    |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.6%    |
| Intel Core i7-10700F CPU @ 2.90GHz          | 3        | 0.6%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 92       | 18.29%  |
| Intel Core i3           | 72       | 14.31%  |
| Intel Core i7           | 58       | 11.53%  |
| AMD Ryzen 5             | 49       | 9.74%   |
| Intel Core 2 Duo        | 31       | 6.16%   |
| Intel Pentium           | 19       | 3.78%   |
| Other                   | 16       | 3.18%   |
| Intel Xeon              | 16       | 3.18%   |
| AMD Ryzen 7             | 16       | 3.18%   |
| Intel Core 2 Quad       | 14       | 2.78%   |
| AMD Ryzen 3             | 14       | 2.78%   |
| Intel Pentium Dual-Core | 12       | 2.39%   |
| AMD FX                  | 10       | 1.99%   |
| Intel Celeron           | 7        | 1.39%   |
| AMD Ryzen 9             | 7        | 1.39%   |
| AMD A8                  | 7        | 1.39%   |
| AMD A6                  | 7        | 1.39%   |
| AMD Athlon II X2        | 6        | 1.19%   |
| AMD Athlon              | 5        | 0.99%   |
| Intel Core 2            | 4        | 0.8%    |
| Intel Atom              | 4        | 0.8%    |
| AMD Phenom II X6        | 4        | 0.8%    |
| AMD Athlon X4           | 4        | 0.8%    |
| AMD A4                  | 4        | 0.8%    |
| Intel Pentium Gold      | 3        | 0.6%    |
| AMD Phenom II X4        | 3        | 0.6%    |
| AMD A10                 | 3        | 0.6%    |
| Intel Pentium Dual      | 2        | 0.4%    |
| Intel Pentium D         | 2        | 0.4%    |
| Intel Genuine           | 2        | 0.4%    |
| AMD Ryzen 3 PRO         | 2        | 0.4%    |
| AMD GX                  | 2        | 0.4%    |
| AMD Athlon 64 X2        | 2        | 0.4%    |
| Intel Core 2 Extreme    | 1        | 0.2%    |
| AMD Ryzen 5 PRO         | 1        | 0.2%    |
| AMD PRO A8              | 1        | 0.2%    |
| AMD Phenom              | 1        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 197      | 39.09%  |
| 2      | 181      | 35.91%  |
| 6      | 71       | 14.09%  |
| 8      | 31       | 6.15%   |
| 1      | 8        | 1.59%   |
| 12     | 5        | 0.99%   |
| 10     | 4        | 0.79%   |
| 3      | 4        | 0.79%   |
| 16     | 3        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 500      | 99.8%   |
| 2      | 1        | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 279      | 55.58%  |
| 1      | 223      | 44.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 495      | 98.8%   |
| Unknown        | 5        | 1%      |
| 32-bit         | 1        | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 242      | 46.36%  |
| 0x306c3    | 33       | 6.32%   |
| 0x1067a    | 30       | 5.75%   |
| 0x306a9    | 29       | 5.56%   |
| 0x206a7    | 23       | 4.41%   |
| 0x906e9    | 11       | 2.11%   |
| 0x906ea    | 8        | 1.53%   |
| 0x08701021 | 6        | 1.15%   |
| 0xa0655    | 5        | 0.96%   |
| 0x6fd      | 5        | 0.96%   |
| 0x6fb      | 5        | 0.96%   |
| 0x506e3    | 5        | 0.96%   |
| 0x20652    | 5        | 0.96%   |
| 0x06003106 | 5        | 0.96%   |
| 0x06001119 | 5        | 0.96%   |
| 0x010000c8 | 5        | 0.96%   |
| 0x0a50000c | 4        | 0.77%   |
| 0x0a201016 | 4        | 0.77%   |
| 0x08001137 | 4        | 0.77%   |
| 0x010000dc | 4        | 0.77%   |
| 0xa0671    | 3        | 0.57%   |
| 0xa0653    | 3        | 0.57%   |
| 0x906ed    | 3        | 0.57%   |
| 0x106e5    | 3        | 0.57%   |
| 0x106a5    | 3        | 0.57%   |
| 0x10676    | 3        | 0.57%   |
| 0x08108109 | 3        | 0.57%   |
| 0x08101016 | 3        | 0.57%   |
| 0x08101007 | 3        | 0.57%   |
| 0x0800820d | 3        | 0.57%   |
| 0x010000c7 | 3        | 0.57%   |
| 0xf62      | 2        | 0.38%   |
| 0x906eb    | 2        | 0.38%   |
| 0x90675    | 2        | 0.38%   |
| 0x90672    | 2        | 0.38%   |
| 0x6f6      | 2        | 0.38%   |
| 0x206d7    | 2        | 0.38%   |
| 0x106ca    | 2        | 0.38%   |
| 0x0a50000d | 2        | 0.38%   |
| 0x0a20120a | 2        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 58       | 11.58%  |
| Haswell          | 53       | 10.58%  |
| SandyBridge      | 51       | 10.18%  |
| Penryn           | 49       | 9.78%   |
| KabyLake         | 40       | 7.98%   |
| Zen 3            | 30       | 5.99%   |
| Zen              | 21       | 4.19%   |
| Piledriver       | 21       | 4.19%   |
| CometLake        | 18       | 3.59%   |
| Unknown          | 18       | 3.59%   |
| Zen 2            | 17       | 3.39%   |
| Core             | 16       | 3.19%   |
| Skylake          | 15       | 2.99%   |
| Zen+             | 14       | 2.79%   |
| Westmere         | 14       | 2.79%   |
| K10              | 14       | 2.79%   |
| Nehalem          | 10       | 2%      |
| Steamroller      | 6        | 1.2%    |
| Alderlake Hybrid | 6        | 1.2%    |
| Excavator        | 4        | 0.8%    |
| Bonnell          | 4        | 0.8%    |
| K10 Llano        | 3        | 0.6%    |
| Goldmont plus    | 3        | 0.6%    |
| Tremont          | 2        | 0.4%    |
| NetBurst         | 2        | 0.4%    |
| K8 Hammer        | 2        | 0.4%    |
| Jaguar           | 2        | 0.4%    |
| Icelake          | 2        | 0.4%    |
| Bulldozer        | 2        | 0.4%    |
| Silvermont       | 1        | 0.2%    |
| Puma             | 1        | 0.2%    |
| Gracemont        | 1        | 0.2%    |
| Broadwell        | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 204      | 37.71%  |
| AMD                        | 179      | 33.09%  |
| Nvidia                     | 156      | 28.84%  |
| Matrox Electronics Systems | 1        | 0.18%   |
| 3Com                       | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 29       | 5.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 28       | 5.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 26       | 4.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 19       | 3.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19       | 3.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 17       | 3.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13       | 2.36%   |
| Nvidia GK208B [GeForce GT 730]                                              | 11       | 1.99%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 11       | 1.99%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 11       | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11       | 1.99%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 10       | 1.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 1.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 9        | 1.63%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 9        | 1.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 1.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 1.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 1.45%   |
| Nvidia GF108 [GeForce GT 730]                                               | 8        | 1.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 1.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 7        | 1.27%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 7        | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.09%   |
| AMD Richland [Radeon HD 8470D]                                              | 5        | 0.91%   |
| AMD Phoenix1                                                                | 5        | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.72%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 4        | 0.72%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 4        | 0.72%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 0.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 3        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 0.54%   |
| Nvidia GK208B [GeForce GT 720]                                              | 3        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 174      | 34.32%  |
| 1 x AMD                | 160      | 31.56%  |
| 1 x Nvidia             | 140      | 27.61%  |
| Intel + AMD            | 8        | 1.58%   |
| Intel + Nvidia         | 7        | 1.38%   |
| AMD + Nvidia           | 6        | 1.18%   |
| 2 x AMD                | 5        | 0.99%   |
| 2 x Intel              | 3        | 0.59%   |
| 2 x Nvidia             | 1        | 0.2%    |
| 1 x Matrox             | 1        | 0.2%    |
| 1 x Intel + 4 x Nvidia | 1        | 0.2%    |
| Intel + 3Com           | 1        | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 423      | 82.62%  |
| Proprietary | 70       | 13.67%  |
| Unknown     | 19       | 3.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 275      | 53.29%  |
| 1.01-2.0   | 68       | 13.18%  |
| 0.51-1.0   | 51       | 9.88%   |
| 0.01-0.5   | 44       | 8.53%   |
| 3.01-4.0   | 33       | 6.4%    |
| 7.01-8.0   | 21       | 4.07%   |
| 5.01-6.0   | 11       | 2.13%   |
| 8.01-16.0  | 11       | 2.13%   |
| 2.01-3.0   | 2        | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 109      | 23.29%  |
| Samsung Electronics  | 65       | 13.89%  |
| Dell                 | 48       | 10.26%  |
| Lenovo               | 32       | 6.84%   |
| Hewlett-Packard      | 32       | 6.84%   |
| AOC                  | 25       | 5.34%   |
| Acer                 | 19       | 4.06%   |
| ViewSonic            | 14       | 2.99%   |
| Philips              | 12       | 2.56%   |
| Mi                   | 10       | 2.14%   |
| BenQ                 | 10       | 2.14%   |
| LG Electronics       | 9        | 1.92%   |
| Ancor Communications | 8        | 1.71%   |
| MSI                  | 7        | 1.5%    |
| Sharp                | 6        | 1.28%   |
| Toshiba              | 5        | 1.07%   |
| Unknown              | 4        | 0.85%   |
| RTK                  | 4        | 0.85%   |
| SAS                  | 3        | 0.64%   |
| Panasonic            | 3        | 0.64%   |
| Unknown (XXX)        | 2        | 0.43%   |
| Skyworth             | 2        | 0.43%   |
| JRY                  | 2        | 0.43%   |
| HKC                  | 2        | 0.43%   |
| GDH                  | 2        | 0.43%   |
| Denver               | 2        | 0.43%   |
| ASUSTek Computer     | 2        | 0.43%   |
| Xiaomi               | 1        | 0.21%   |
| Unknown (BBC)        | 1        | 0.21%   |
| Tech Concepts        | 1        | 0.21%   |
| TCL                  | 1        | 0.21%   |
| Sunplus              | 1        | 0.21%   |
| SPC                  | 1        | 0.21%   |
| Sony                 | 1        | 0.21%   |
| SKY                  | 1        | 0.21%   |
| S2-Tek               | 1        | 0.21%   |
| RGT                  | 1        | 0.21%   |
| Polaroid             | 1        | 0.21%   |
| PiLot                | 1        | 0.21%   |
| ODH                  | 1        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 19       | 3.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 14       | 2.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8        | 1.64%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 8        | 1.64%   |
| Acer X163WL ACR022E 1366x768 344x193mm 15.5-inch                     | 7        | 1.43%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch              | 6        | 1.23%   |
| Lenovo LEN D186wA LEN0A14 1366x768 410x230mm 18.5-inch               | 5        | 1.02%   |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                  | 5        | 1.02%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 5        | 1.02%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                   | 5        | 1.02%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch              | 4        | 0.82%   |
| Lenovo L24i-30 LEN66BD 1920x1080 527x296mm 23.8-inch                 | 4        | 0.82%   |
| Hewlett-Packard LE1902x HWP2965 1366x768 410x230mm 18.5-inch         | 4        | 0.82%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 3        | 0.61%   |
| Toshiba LX600B LCD1560 1360x768 340x190mm 15.3-inch                  | 3        | 0.61%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                      | 3        | 0.61%   |
| SAS VGA SAS2000 1440x900 409x255mm 19.0-inch                         | 3        | 0.61%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch   | 3        | 0.61%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 3        | 0.61%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 3        | 0.61%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 3        | 0.61%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                     | 3        | 0.61%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch               | 3        | 0.61%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 3        | 0.61%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 3        | 0.61%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 0.61%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                     | 3        | 0.61%   |
| Dell E1912H DELF03E 1366x768 410x230mm 18.5-inch                     | 3        | 0.61%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                     | 3        | 0.61%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 3        | 0.61%   |
| Unknown LCD Monitor AcerMFMAV 1440x900                               | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 2        | 0.41%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 2        | 0.41%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 0.41%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch    | 2        | 0.41%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch     | 2        | 0.41%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 2        | 0.41%   |
| Samsung Electronics LCD Monitor S19D300 1366x768                     | 2        | 0.41%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 0.41%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 173      | 37.61%  |
| 1366x768 (WXGA)    | 120      | 26.09%  |
| 3840x2160 (4K)     | 43       | 9.35%   |
| 1440x900 (WXGA+)   | 29       | 6.3%    |
| 2560x1440 (QHD)    | 19       | 4.13%   |
| 1600x900 (HD+)     | 18       | 3.91%   |
| 1360x768           | 14       | 3.04%   |
| 1280x1024 (SXGA)   | 13       | 2.83%   |
| 2560x1080          | 7        | 1.52%   |
| 3440x1440          | 5        | 1.09%   |
| 1680x1050 (WSXGA+) | 4        | 0.87%   |
| 1280x720 (HD)      | 3        | 0.65%   |
| 1024x768 (XGA)     | 3        | 0.65%   |
| 3840x1080          | 2        | 0.43%   |
| 1280x960           | 2        | 0.43%   |
| Unknown            | 2        | 0.43%   |
| 640x480            | 1        | 0.22%   |
| 5760x2160          | 1        | 0.22%   |
| 2288x1287          | 1        | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 89       | 19.02%  |
| 21      | 56       | 11.97%  |
| 23      | 53       | 11.32%  |
| 24      | 40       | 8.55%   |
| 27      | 38       | 8.12%   |
| 19      | 38       | 8.12%   |
| 15      | 32       | 6.84%   |
| Unknown | 26       | 5.56%   |
| 31      | 24       | 5.13%   |
| 17      | 11       | 2.35%   |
| 34      | 7        | 1.5%    |
| 20      | 6        | 1.28%   |
| 84      | 5        | 1.07%   |
| 40      | 5        | 1.07%   |
| 22      | 4        | 0.85%   |
| 63      | 3        | 0.64%   |
| 42      | 3        | 0.64%   |
| 37      | 3        | 0.64%   |
| 52      | 2        | 0.43%   |
| 49      | 2        | 0.43%   |
| 48      | 2        | 0.43%   |
| 16      | 2        | 0.43%   |
| 13      | 2        | 0.43%   |
| 142     | 1        | 0.21%   |
| 72      | 1        | 0.21%   |
| 65      | 1        | 0.21%   |
| 60      | 1        | 0.21%   |
| 57      | 1        | 0.21%   |
| 54      | 1        | 0.21%   |
| 46      | 1        | 0.21%   |
| 43      | 1        | 0.21%   |
| 39      | 1        | 0.21%   |
| 36      | 1        | 0.21%   |
| 35      | 1        | 0.21%   |
| 32      | 1        | 0.21%   |
| 29      | 1        | 0.21%   |
| 28      | 1        | 0.21%   |
| 12      | 1        | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 182      | 39.57%  |
| 501-600        | 123      | 26.74%  |
| 301-350        | 38       | 8.26%   |
| 601-700        | 30       | 6.52%   |
| Unknown        | 26       | 5.65%   |
| 351-400        | 14       | 3.04%   |
| 1001-1500      | 13       | 2.83%   |
| 801-900        | 10       | 2.17%   |
| 701-800        | 10       | 2.17%   |
| 1501-2000      | 6        | 1.3%    |
| 901-1000       | 4        | 0.87%   |
| 201-300        | 3        | 0.65%   |
| More than 2000 | 1        | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 357      | 80.04%  |
| 16/10   | 32       | 7.17%   |
| Unknown | 25       | 5.61%   |
| 5/4     | 13       | 2.91%   |
| 21/9    | 10       | 2.24%   |
| 4/3     | 5        | 1.12%   |
| 32/9    | 2        | 0.45%   |
| 1.00    | 1        | 0.22%   |
| 0.56    | 1        | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 117      | 25.27%  |
| 141-150        | 93       | 20.09%  |
| 151-200        | 67       | 14.47%  |
| 301-350        | 38       | 8.21%   |
| 351-500        | 32       | 6.91%   |
| 101-110        | 29       | 6.26%   |
| Unknown        | 26       | 5.62%   |
| More than 1000 | 18       | 3.89%   |
| 501-1000       | 17       | 3.67%   |
| 251-300        | 13       | 2.81%   |
| 131-140        | 5        | 1.08%   |
| 91-100         | 3        | 0.65%   |
| 81-90          | 2        | 0.43%   |
| 111-120        | 2        | 0.43%   |
| 71-80          | 1        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 298      | 65.21%  |
| 101-120 | 101      | 22.1%   |
| Unknown | 26       | 5.69%   |
| 1-50    | 23       | 5.03%   |
| 121-160 | 5        | 1.09%   |
| 161-240 | 4        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 431      | 84.68%  |
| 2     | 38       | 7.47%   |
| 0     | 38       | 7.47%   |
| 4     | 1        | 0.2%    |
| 3     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 391      | 50.13%  |
| Intel                           | 132      | 16.92%  |
| Qualcomm Atheros                | 47       | 6.03%   |
| TP-Link                         | 44       | 5.64%   |
| Ralink Technology               | 44       | 5.64%   |
| Broadcom                        | 18       | 2.31%   |
| Xiaomi                          | 15       | 1.92%   |
| Qualcomm Atheros Communications | 10       | 1.28%   |
| MediaTek                        | 10       | 1.28%   |
| Samsung Electronics             | 8        | 1.03%   |
| Ralink                          | 7        | 0.9%    |
| Qualcomm                        | 5        | 0.64%   |
| D-Link System                   | 5        | 0.64%   |
| D-Link                          | 5        | 0.64%   |
| ASIX Electronics                | 5        | 0.64%   |
| ZTopInc                         | 3        | 0.38%   |
| OPPO Electronics                | 3        | 0.38%   |
| Marvell Technology Group        | 3        | 0.38%   |
| QinHeng Electronics             | 2        | 0.26%   |
| Nvidia                          | 2        | 0.26%   |
| Huawei Technologies             | 2        | 0.26%   |
| HMD Global                      | 2        | 0.26%   |
| Broadcom Limited                | 2        | 0.26%   |
| AboCom Systems                  | 2        | 0.26%   |
| 3Com                            | 2        | 0.26%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.13%   |
| vivo                            | 1        | 0.13%   |
| VIA Technologies                | 1        | 0.13%   |
| T & A Mobile Phones             | 1        | 0.13%   |
| Spreadtrum Communications       | 1        | 0.13%   |
| Microsoft                       | 1        | 0.13%   |
| Linux Foundation                | 1        | 0.13%   |
| ICS Advent                      | 1        | 0.13%   |
| Foxconn / Hon Hai               | 1        | 0.13%   |
| Belkin Components               | 1        | 0.13%   |
| ASUSTek Computer                | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 289      | 32.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 5.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 35       | 3.98%   |
| Ralink MT7601U Wireless Adapter                                        | 31       | 3.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 22       | 2.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 21       | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18       | 2.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 12       | 1.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 12       | 1.36%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 10       | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10       | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10       | 1.14%   |
| Intel I211 Gigabit Network Connection                                  | 10       | 1.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9        | 1.02%   |
| Intel Wi-Fi 6 AX200                                                    | 9        | 1.02%   |
| Realtek 802.11ac NIC                                                   | 8        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 0.91%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                | 7        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                   | 7        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7        | 0.8%    |
| TP-Link 802.11n NIC                                                    | 6        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 6        | 0.68%   |
| Qualcomm Nokia X30 5G                                                  | 5        | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.57%   |
| Intel Ethernet Controller I225-V                                       | 5        | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.57%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 4        | 0.45%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 0.45%   |
| Intel Wireless 3165                                                    | 4        | 0.45%   |
| Intel Ethernet Connection I217-V                                       | 4        | 0.45%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 0.45%   |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4        | 0.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 4        | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4        | 0.45%   |
| ZTopInc 802.11n NIC                                                    | 3        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 92       | 30.98%  |
| Intel                           | 55       | 18.52%  |
| Ralink Technology               | 44       | 14.81%  |
| TP-Link                         | 42       | 14.14%  |
| Qualcomm Atheros                | 17       | 5.72%   |
| Qualcomm Atheros Communications | 10       | 3.37%   |
| Ralink                          | 7        | 2.36%   |
| Broadcom                        | 7        | 2.36%   |
| MediaTek                        | 6        | 2.02%   |
| D-Link                          | 5        | 1.68%   |
| ZTopInc                         | 3        | 1.01%   |
| D-Link System                   | 3        | 1.01%   |
| AboCom Systems                  | 2        | 0.67%   |
| Microsoft                       | 1        | 0.34%   |
| Broadcom Limited                | 1        | 0.34%   |
| Belkin Components               | 1        | 0.34%   |
| ASUSTek Computer                | 1        | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 35       | 11.63%  |
| Ralink MT7601U Wireless Adapter                               | 31       | 10.3%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 22       | 7.31%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 12       | 3.99%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 10       | 3.32%   |
| Qualcomm Atheros AR9271 802.11n                               | 10       | 3.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 10       | 3.32%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 9        | 2.99%   |
| Intel Wi-Fi 6 AX200                                           | 9        | 2.99%   |
| Realtek 802.11ac NIC                                          | 8        | 2.66%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter       | 7        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 7        | 2.33%   |
| TP-Link 802.11n NIC                                           | 6        | 1.99%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 6        | 1.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 4        | 1.33%   |
| Ralink RT5370 Wireless Adapter                                | 4        | 1.33%   |
| Intel Wireless 3165                                           | 4        | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4        | 1.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 4        | 1.33%   |
| ZTopInc 802.11n NIC                                           | 3        | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3        | 1%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 3        | 1%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 3        | 1%      |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)     | 3        | 1%      |
| Intel Wireless 7265                                           | 3        | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2        | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 2        | 0.66%   |
| Ralink RT2501/RT2573 Wireless Adapter                         | 2        | 0.66%   |
| Ralink RT5392 PCIe Wireless Network Adapter                   | 2        | 0.66%   |
| Ralink RT2561/RT61 802.11g PCI                                | 2        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2        | 0.66%   |
| Intel Wireless 7260                                           | 2        | 0.66%   |
| Intel Wireless 3160                                           | 2        | 0.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 2        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2        | 0.66%   |
| D-Link WLAN controller                                        | 2        | 0.66%   |
| D-Link 802.11 n WLAN                                          | 2        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 368      | 64.9%   |
| Intel                      | 93       | 16.4%   |
| Qualcomm Atheros           | 31       | 5.47%   |
| Xiaomi                     | 15       | 2.65%   |
| Broadcom                   | 11       | 1.94%   |
| Samsung Electronics        | 8        | 1.41%   |
| Qualcomm                   | 5        | 0.88%   |
| ASIX Electronics           | 5        | 0.88%   |
| MediaTek                   | 4        | 0.71%   |
| OPPO Electronics           | 3        | 0.53%   |
| Marvell Technology Group   | 3        | 0.53%   |
| TP-Link                    | 2        | 0.35%   |
| Nvidia                     | 2        | 0.35%   |
| Huawei Technologies        | 2        | 0.35%   |
| HMD Global                 | 2        | 0.35%   |
| D-Link System              | 2        | 0.35%   |
| 3Com                       | 2        | 0.35%   |
| ZTE WCDMA Technologies MSM | 1        | 0.18%   |
| vivo                       | 1        | 0.18%   |
| VIA Technologies           | 1        | 0.18%   |
| T & A Mobile Phones        | 1        | 0.18%   |
| Spreadtrum Communications  | 1        | 0.18%   |
| QinHeng Electronics        | 1        | 0.18%   |
| ICS Advent                 | 1        | 0.18%   |
| Foxconn / Hon Hai          | 1        | 0.18%   |
| Broadcom Limited           | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 289      | 50.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 50       | 8.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 21       | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18       | 3.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 12       | 2.08%   |
| Intel I211 Gigabit Network Connection                                  | 10       | 1.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                   | 7        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6        | 1.04%   |
| Qualcomm Nokia X30 5G                                                  | 5        | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.87%   |
| Intel Ethernet Controller I225-V                                       | 5        | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.87%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.87%   |
| Intel Ethernet Connection I217-V                                       | 4        | 0.69%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3        | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 3        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3        | 0.52%   |
| MediaTek Infinix HOT 50i                                               | 3        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                  | 3        | 0.52%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 3        | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2        | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2        | 0.35%   |
| OPPO Ace 3V                                                            | 2        | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2        | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 494      | 63.82%  |
| WiFi     | 279      | 36.05%  |
| Modem    | 1        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 314      | 62.3%   |
| WiFi     | 190      | 37.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 355      | 70.3%   |
| 2     | 123      | 24.36%  |
| 3     | 16       | 3.17%   |
| 0     | 6        | 1.19%   |
| 5     | 2        | 0.4%    |
| 4     | 2        | 0.4%    |
| 27    | 1        | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 469      | 93.06%  |
| Yes  | 35       | 6.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 35.86%  |
| Cambridge Silicon Radio         | 52       | 35.86%  |
| Realtek Semiconductor           | 14       | 9.66%   |
| TP-Link                         | 4        | 2.76%   |
| Qualcomm Atheros Communications | 4        | 2.76%   |
| Broadcom                        | 4        | 2.76%   |
| MediaTek                        | 3        | 2.07%   |
| IMC Networks                    | 3        | 2.07%   |
| Actions                         | 3        | 2.07%   |
| Unknown                         | 3        | 2.07%   |
| Lite-On Technology              | 1        | 0.69%   |
| Foxconn / Hon Hai               | 1        | 0.69%   |
| Apple                           | 1        | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 52       | 35.86%  |
| Intel Bluetooth wireless interface                  | 15       | 10.34%  |
| Realtek Bluetooth Radio                             | 11       | 7.59%   |
| Intel AX210 Bluetooth                               | 9        | 6.21%   |
| Intel AX200 Bluetooth                               | 9        | 6.21%   |
| Intel AX201 Bluetooth                               | 8        | 5.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7        | 4.83%   |
| TP-Link TP-T@- UB500 Adapter                        | 4        | 2.76%   |
| MediaTek Wireless_Device                            | 3        | 2.07%   |
| Actions general adapter                             | 3        | 2.07%   |
| Unknown                                             | 3        | 2.07%   |
| Realtek RTL8821A Bluetooth                          | 2        | 1.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 1.38%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2        | 1.38%   |
| Realtek RTL8723B Bluetooth                          | 1        | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.69%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.69%   |
| Qualcomm Atheros Bluetooth                          | 1        | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 0.69%   |
| Lite-On Wireless_Device                             | 1        | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 0.69%   |
| Intel Bluetooth Device                              | 1        | 0.69%   |
| IMC Networks Wireless_Device                        | 1        | 0.69%   |
| IMC Networks Bluetooth Radio                        | 1        | 0.69%   |
| IMC Networks Bluetooth Device                       | 1        | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 0.69%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 0.69%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 0.69%   |
| Apple Bluetooth Host Controller                     | 1        | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 349      | 45.86%  |
| AMD                                  | 201      | 26.41%  |
| Nvidia                               | 143      | 18.79%  |
| C-Media Electronics                  | 15       | 1.97%   |
| Generalplus Technology               | 8        | 1.05%   |
| Texas Instruments                    | 5        | 0.66%   |
| Creative Labs                        | 4        | 0.53%   |
| Weltrend Semiconductor               | 2        | 0.26%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.26%   |
| SteelSeries ApS                      | 2        | 0.26%   |
| Sony                                 | 2        | 0.26%   |
| Razer USA                            | 2        | 0.26%   |
| Logitech                             | 2        | 0.26%   |
| KTMicro                              | 2        | 0.26%   |
| Kingston Technology                  | 2        | 0.26%   |
| JMTek                                | 2        | 0.26%   |
| Barco Display Systems                | 2        | 0.26%   |
| ASUSTek Computer                     | 2        | 0.26%   |
| Yamaha                               | 1        | 0.13%   |
| STMicroelectronics                   | 1        | 0.13%   |
| Soundprese                           | 1        | 0.13%   |
| Solid State Logic                    | 1        | 0.13%   |
| Samson Technologies                  | 1        | 0.13%   |
| Micro Star International             | 1        | 0.13%   |
| Jieli Technology                     | 1        | 0.13%   |
| JBL                                  | 1        | 0.13%   |
| Hewlett-Packard                      | 1        | 0.13%   |
| GYROCOM C&C                          | 1        | 0.13%   |
| Giga-Byte Technology                 | 1        | 0.13%   |
| Creative Technology                  | 1        | 0.13%   |
| Cooler Master                        | 1        | 0.13%   |
| Comtrue                              | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 73       | 8%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 54       | 5.92%   |
| AMD Ryzen HD Audio Controller                                              | 53       | 5.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44       | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31       | 3.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 30       | 3.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29       | 3.18%   |
| AMD FCH Azalia Controller                                                  | 29       | 3.18%   |
| Nvidia High Definition Audio Controller                                    | 23       | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23       | 2.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22       | 2.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 21       | 2.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 2.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19       | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18       | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18       | 1.97%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 1.86%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 17       | 1.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 17       | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 1.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.21%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 11       | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10       | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 1.1%    |
| AMD Trinity HDMI Audio Controller                                          | 9        | 0.99%   |
| AMD Radeon High Definition Audio Controller                                | 9        | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 9        | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                              | 8        | 0.88%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 0.88%   |
| Generalplus Technology USB Audio Device                                    | 8        | 0.88%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 7        | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 58       | 18.07%  |
| Kingston            | 46       | 14.33%  |
| SK hynix            | 40       | 12.46%  |
| Samsung Electronics | 40       | 12.46%  |
| Corsair             | 28       | 8.72%   |
| Team                | 27       | 8.41%   |
| V-GeN               | 14       | 4.36%   |
| Unknown             | 13       | 4.05%   |
| Micron Technology   | 12       | 3.74%   |
| G.Skill             | 10       | 3.12%   |
| Elpida              | 5        | 1.56%   |
| Crucial             | 4        | 1.25%   |
| Patriot             | 3        | 0.93%   |
| KLEVV               | 3        | 0.93%   |
| A-DATA Technology   | 3        | 0.93%   |
| Unknown (0x0DD5)    | 2        | 0.62%   |
| Transcend           | 2        | 0.62%   |
| Ramaxel Technology  | 2        | 0.62%   |
| Visipro             | 1        | 0.31%   |
| Unknown (8AA1)      | 1        | 0.31%   |
| Super Talent        | 1        | 0.31%   |
| Nanya Technology    | 1        | 0.31%   |
| Lexar Co Limited    | 1        | 0.31%   |
| Lexar               | 1        | 0.31%   |
| Kingmax             | 1        | 0.31%   |
| Essencore           | 1        | 0.31%   |
| 04?@                | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown                                                     | 13       | 3.78%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s          | 9        | 2.62%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 6        | 1.74%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 5        | 1.45%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 4        | 1.16%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3000MT/s          | 4        | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 4        | 1.16%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s         | 4        | 1.16%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s         | 4        | 1.16%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s        | 4        | 1.16%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 3        | 0.87%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 3        | 0.87%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 3        | 0.87%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                        | 3        | 0.87%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 3        | 0.87%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 3        | 0.87%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s          | 3        | 0.87%   |
| SK hynix RAM HMT351U6EFR8C-PBA 8GB DIMM DDR3 1600MT/s       | 3        | 0.87%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s         | 3        | 0.87%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                  | 3        | 0.87%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 3        | 0.87%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s       | 3        | 0.87%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM SDRAM 1800MT/s        | 3        | 0.87%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s       | 3        | 0.87%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 3        | 0.87%   |
| V-GEN RAM D4H8GL26A8TS6 8GB DIMM DDR4 2666MT/s              | 2        | 0.58%   |
| V-GeN RAM D3R4GL16B8R 4GB DIMM DDR3 1600MT/s                | 2        | 0.58%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 2        | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                   | 2        | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                    | 2        | 0.58%   |
| Unknown RAM Module 2GB DIMM 667MT/s                         | 2        | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 2        | 0.58%   |
| Unknown (0x0DD5) RAM AZ8G4SW266-8G 8GB SODIMM DDR4 2667MT/s | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 4000MT/s         | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s          | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s         | 2        | 0.58%   |
| SK hynix RAM Module 8GB DIMM DDR3                           | 2        | 0.58%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 107      | 39.19%  |
| DDR4    | 102      | 37.36%  |
| SDRAM   | 22       | 8.06%   |
| Unknown | 18       | 6.59%   |
| DDR2    | 14       | 5.13%   |
| DDR5    | 8        | 2.93%   |
| DDR     | 2        | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 240      | 90.57%  |
| SODIMM | 25       | 9.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 94       | 31.02%  |
| 4096  | 83       | 27.39%  |
| 2048  | 61       | 20.13%  |
| 16384 | 29       | 9.57%   |
| 32768 | 27       | 8.91%   |
| 1024  | 8        | 2.64%   |
| 512   | 1        | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 63       | 20.79%  |
| 1333    | 42       | 13.86%  |
| 3600    | 17       | 5.61%   |
| 3200    | 17       | 5.61%   |
| 2400    | 14       | 4.62%   |
| 800     | 14       | 4.62%   |
| 2667    | 13       | 4.29%   |
| Unknown | 12       | 3.96%   |
| 3800    | 11       | 3.63%   |
| 1800    | 10       | 3.3%    |
| 3733    | 9        | 2.97%   |
| 2133    | 7        | 2.31%   |
| 667     | 7        | 2.31%   |
| 2666    | 6        | 1.98%   |
| 3000    | 5        | 1.65%   |
| 1867    | 5        | 1.65%   |
| 1866    | 5        | 1.65%   |
| 3400    | 4        | 1.32%   |
| 1067    | 4        | 1.32%   |
| 4000    | 3        | 0.99%   |
| 1066    | 3        | 0.99%   |
| 6000    | 2        | 0.66%   |
| 5600    | 2        | 0.66%   |
| 5400    | 2        | 0.66%   |
| 4800    | 2        | 0.66%   |
| 3866    | 2        | 0.66%   |
| 3151    | 2        | 0.66%   |
| 400     | 2        | 0.66%   |
| 333     | 2        | 0.66%   |
| 50410   | 1        | 0.33%   |
| 8400    | 1        | 0.33%   |
| 4040    | 1        | 0.33%   |
| 3466    | 1        | 0.33%   |
| 3333    | 1        | 0.33%   |
| 3066    | 1        | 0.33%   |
| 2934    | 1        | 0.33%   |
| 2933    | 1        | 0.33%   |
| 2734    | 1        | 0.33%   |
| 2733    | 1        | 0.33%   |
| 2465    | 1        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 17       | 65.38%  |
| Hewlett-Packard    | 5        | 19.23%  |
| STMicroelectronics | 1        | 3.85%   |
| Fuji Xerox         | 1        | 3.85%   |
| Canon              | 1        | 3.85%   |
| Brother Industries | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seiko Epson L120 Series                 | 5        | 19.23%  |
| Seiko Epson EPSON L220 Series           | 4        | 15.38%  |
| Seiko Epson L3110 Series                | 2        | 7.69%   |
| Seiko Epson EPSON L300 Series           | 2        | 7.69%   |
| STMicroelectronics ICOD_Thermal_Printer | 1        | 3.85%   |
| Seiko Epson L3210 Series                | 1        | 3.85%   |
| Seiko Epson L312 Series                 | 1        | 3.85%   |
| Seiko Epson L1300 Series                | 1        | 3.85%   |
| Seiko Epson L1110 Series                | 1        | 3.85%   |
| HP LaserJet P1102                       | 1        | 3.85%   |
| HP LaserJet P1006                       | 1        | 3.85%   |
| HP Ink Tank 310 series                  | 1        | 3.85%   |
| HP DeskJet 5820 series                  | 1        | 3.85%   |
| HP DeskJet 2130 series                  | 1        | 3.85%   |
| Fuji Xerox DocuPrint M205 b             | 1        | 3.85%   |
| Canon PIXMA MP250                       | 1        | 3.85%   |
| Brother DCP-T310                        | 1        | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 33.33%  |
| Canon CanoScan LIDE 25             | 1        | 33.33%  |
| Canon CanoScan LiDE 110            | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 20.55%  |
| Microdia                      | 7        | 9.59%   |
| Chicony Electronics           | 7        | 9.59%   |
| Jieli Technology              | 5        | 6.85%   |
| ANYKA                         | 5        | 6.85%   |
| Z-Star Microelectronics       | 4        | 5.48%   |
| IMC Networks                  | 3        | 4.11%   |
| Generalplus Technology        | 3        | 4.11%   |
| Sunplus Innovation Technology | 2        | 2.74%   |
| SN0002                        | 2        | 2.74%   |
| Realtek Semiconductor         | 2        | 2.74%   |
| MacroSilicon                  | 2        | 2.74%   |
| GEMBIRD                       | 2        | 2.74%   |
| Cubeternet                    | 2        | 2.74%   |
| Apple                         | 2        | 2.74%   |
| WCM_USB                       | 1        | 1.37%   |
| Sonix Technology              | 1        | 1.37%   |
| SiGma Micro                   | 1        | 1.37%   |
| Samsung Electronics           | 1        | 1.37%   |
| Razer USA                     | 1        | 1.37%   |
| OPPO Electronics              | 1        | 1.37%   |
| KYE Systems (Mouse Systems)   | 1        | 1.37%   |
| Huawei Technologies           | 1        | 1.37%   |
| Arkmicro Technologies         | 1        | 1.37%   |
| A4Tech                        | 1        | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Microdia Integrated Camera                            | 5        | 6.76%   |
| ANYKA V380 FHD Camera                                 | 5        | 6.76%   |
| Logitech Webcam C270                                  | 3        | 4.05%   |
| Jieli USB Composite Device                            | 3        | 4.05%   |
| Chicony HP High Definition 1MP Webcam                 | 3        | 4.05%   |
| SN0002 1080P Web Camera                               | 2        | 2.7%    |
| Realtek Thronmax Stream Go Pro Webcam                 | 2        | 2.7%    |
| MacroSilicon USB Video                                | 2        | 2.7%    |
| Logitech Webcam C310                                  | 2        | 2.7%    |
| Logitech HD Webcam C615                               | 2        | 2.7%    |
| Logitech C922 Pro Stream Webcam                       | 2        | 2.7%    |
| Logitech Brio 100                                     | 2        | 2.7%    |
| Jieli USB PHY 2.0                                     | 2        | 2.7%    |
| IMC Networks XHC Camera                               | 2        | 2.7%    |
| Generalplus GENERAL WEBCAM                            | 2        | 2.7%    |
| Chicony HP Integrated Webcam                          | 2        | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 2        | 2.7%    |
| Z-Star Venus USB2.0 Camera                            | 1        | 1.35%   |
| Z-Star USB 2.0 Web Camera                             | 1        | 1.35%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 1.35%   |
| Z-Star Integrated Camera                              | 1        | 1.35%   |
| WCM_USB WEB CAM                                       | 1        | 1.35%   |
| Sunplus SPCA2281 Web Camera                           | 1        | 1.35%   |
| Sunplus Full HD webcam                                | 1        | 1.35%   |
| Sonix GENERAL WEBCAM                                  | 1        | 1.35%   |
| SiGma Micro WebCam SiGma Micro                        | 1        | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 1.35%   |
| Razer USA Razer Kiyo Pro                              | 1        | 1.35%   |
| OPPO OnePlus 13R                                      | 1        | 1.35%   |
| Microdia USB camera                                   | 1        | 1.35%   |
| Microdia Integrated_Webcam_HD                         | 1        | 1.35%   |
| Logitech Webcam C170                                  | 1        | 1.35%   |
| Logitech Webcam C110                                  | 1        | 1.35%   |
| Logitech Logitech Webcam C160                         | 1        | 1.35%   |
| Logitech HD Webcam C525                               | 1        | 1.35%   |
| KYE Systems (Mouse Systems) USB 2.0 HD1080P PC Camera | 1        | 1.35%   |
| IMC Networks USB2.0 UVC HD Webcam                     | 1        | 1.35%   |
| Huawei HiCamera                                       | 1        | 1.35%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 1        | 1.35%   |
| GEMBIRD USB2.0 PC CAMERA                              | 1        | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| STMicroelectronics         | 1        | 50%     |
| Shenzhen Goodix Technology | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 50%     |
| Shenzhen Goodix Fingerprint Reader    | 1        | 50%     |

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
| 0     | 444      | 87.57%  |
| 1     | 56       | 11.05%  |
| 2     | 6        | 1.18%   |
| 3     | 1        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 25       | 36.76%  |
| Net/wireless             | 24       | 35.29%  |
| Unassigned class         | 3        | 4.41%   |
| Net/ethernet             | 3        | 4.41%   |
| Communication controller | 3        | 4.41%   |
| Storage/ide              | 2        | 2.94%   |
| Fingerprint reader       | 2        | 2.94%   |
| Camera                   | 2        | 2.94%   |
| Wireless                 | 1        | 1.47%   |
| Sound                    | 1        | 1.47%   |
| Multimedia controller    | 1        | 1.47%   |
| Bluetooth                | 1        | 1.47%   |

