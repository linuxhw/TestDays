Linux in Slovakia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Slovakia/Desktop/README.md) and [notebooks](/Location/Slovakia/Notebook/README.md).

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

Total: 1264

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H61M-S1                     | Desktop     | [b92a6f8a9e](https://linux-hardware.org/?probe=b92a6f8a9e) | Aug 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [031ed1d4e7](https://linux-hardware.org/?probe=031ed1d4e7) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | Notebook    | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| ASUSTek       | F3L                         | Notebook    | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| Dell          | 0RN474                      | Desktop     | [61153fe575](https://linux-hardware.org/?probe=61153fe575) | Aug 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [c160e44518](https://linux-hardware.org/?probe=c160e44518) | Aug 08, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [b4326c3c45](https://linux-hardware.org/?probe=b4326c3c45) | Aug 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [14114ca4aa](https://linux-hardware.org/?probe=14114ca4aa) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [946d81eb9d](https://linux-hardware.org/?probe=946d81eb9d) | Aug 07, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [64803a4cd7](https://linux-hardware.org/?probe=64803a4cd7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Dell          | Latitude 3510               | Notebook    | [8bfe0fe5fb](https://linux-hardware.org/?probe=8bfe0fe5fb) | Jul 30, 2023 |
| Dell          | Latitude E5570              | Notebook    | [1f9be76313](https://linux-hardware.org/?probe=1f9be76313) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ec84069efb](https://linux-hardware.org/?probe=ec84069efb) | Jul 28, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [89557d5880](https://linux-hardware.org/?probe=89557d5880) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [aad0018c0e](https://linux-hardware.org/?probe=aad0018c0e) | Jul 20, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [37a65534a3](https://linux-hardware.org/?probe=37a65534a3) | Jul 18, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | Notebook    | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f60ead06fd](https://linux-hardware.org/?probe=f60ead06fd) | Jun 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [7fbf9c4e53](https://linux-hardware.org/?probe=7fbf9c4e53) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | Desktop     | [dc2911bfae](https://linux-hardware.org/?probe=dc2911bfae) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | Desktop     | [273bec93a4](https://linux-hardware.org/?probe=273bec93a4) | Jun 25, 2023 |
| ASUSTek       | P5K                         | Desktop     | [c33ff02489](https://linux-hardware.org/?probe=c33ff02489) | Jun 24, 2023 |
| ASUSTek       | P5K                         | Desktop     | [c87e87b883](https://linux-hardware.org/?probe=c87e87b883) | Jun 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| Acer          | Aspire VN7-792G             | Notebook    | [ab55f9b492](https://linux-hardware.org/?probe=ab55f9b492) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5141d5dd1a](https://linux-hardware.org/?probe=5141d5dd1a) | Jun 15, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5732495ae1](https://linux-hardware.org/?probe=5732495ae1) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [edbcec7f32](https://linux-hardware.org/?probe=edbcec7f32) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c0d6d68272](https://linux-hardware.org/?probe=c0d6d68272) | Jun 12, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [f5a1226b72](https://linux-hardware.org/?probe=f5a1226b72) | Jun 12, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9d9872a84a](https://linux-hardware.org/?probe=9d9872a84a) | Jun 10, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [012e8255f3](https://linux-hardware.org/?probe=012e8255f3) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [bd22edfae7](https://linux-hardware.org/?probe=bd22edfae7) | Jun 09, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [a6c222681d](https://linux-hardware.org/?probe=a6c222681d) | Jun 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [3063c26aca](https://linux-hardware.org/?probe=3063c26aca) | Jun 08, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| MSI           | MS-7513                     | Desktop     | [ed69341f3c](https://linux-hardware.org/?probe=ed69341f3c) | Jun 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [ed3b6abc56](https://linux-hardware.org/?probe=ed3b6abc56) | Jun 05, 2023 |
| Dell          | Latitude E4300              | Notebook    | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [d8f9165fec](https://linux-hardware.org/?probe=d8f9165fec) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7b513e678c](https://linux-hardware.org/?probe=7b513e678c) | Jun 03, 2023 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | Notebook    | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d33af1d5a](https://linux-hardware.org/?probe=5d33af1d5a) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [6872b07bb6](https://linux-hardware.org/?probe=6872b07bb6) | May 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [7284c23b76](https://linux-hardware.org/?probe=7284c23b76) | May 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | Notebook    | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ada9095c92](https://linux-hardware.org/?probe=ada9095c92) | May 19, 2023 |
| UMAX          | VisionBook 13Wg Flex        | Convertible | [170db25383](https://linux-hardware.org/?probe=170db25383) | May 17, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [97a221407d](https://linux-hardware.org/?probe=97a221407d) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [9f619133b7](https://linux-hardware.org/?probe=9f619133b7) | May 15, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [032080c4ef](https://linux-hardware.org/?probe=032080c4ef) | May 13, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a11f5f3f98](https://linux-hardware.org/?probe=a11f5f3f98) | May 13, 2023 |
| HP            | 1589                        | Desktop     | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| MSI           | MS-7513                     | Desktop     | [1e14e5d3e6](https://linux-hardware.org/?probe=1e14e5d3e6) | May 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [733703c761](https://linux-hardware.org/?probe=733703c761) | May 09, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [4ab42c06ea](https://linux-hardware.org/?probe=4ab42c06ea) | May 09, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [0952e2922b](https://linux-hardware.org/?probe=0952e2922b) | May 09, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [fca1201c9f](https://linux-hardware.org/?probe=fca1201c9f) | May 07, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d6e340501e](https://linux-hardware.org/?probe=d6e340501e) | May 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ae040331e6](https://linux-hardware.org/?probe=ae040331e6) | May 06, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [eb774628af](https://linux-hardware.org/?probe=eb774628af) | May 06, 2023 |
| Unknown       | Unknown                     | Soc         | [2fedff1d10](https://linux-hardware.org/?probe=2fedff1d10) | May 06, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [c78f20f332](https://linux-hardware.org/?probe=c78f20f332) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6c8f0f4521](https://linux-hardware.org/?probe=6c8f0f4521) | May 06, 2023 |
| MSI           | A75A-G55                    | Desktop     | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [8754e79840](https://linux-hardware.org/?probe=8754e79840) | May 04, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a2b832afa2](https://linux-hardware.org/?probe=a2b832afa2) | Apr 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| HP            | 802F                        | Desktop     | [b314d41043](https://linux-hardware.org/?probe=b314d41043) | Apr 28, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [a8e7de2e0b](https://linux-hardware.org/?probe=a8e7de2e0b) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e0f4a4d0f4](https://linux-hardware.org/?probe=e0f4a4d0f4) | Apr 26, 2023 |
| Dell          | 0RCGCR A04                  | Server      | [8ef63cb2de](https://linux-hardware.org/?probe=8ef63cb2de) | Apr 26, 2023 |
| Dell          | Latitude E5570              | Notebook    | [1a6b35e077](https://linux-hardware.org/?probe=1a6b35e077) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [bb520ff82e](https://linux-hardware.org/?probe=bb520ff82e) | Apr 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [2a389c9c58](https://linux-hardware.org/?probe=2a389c9c58) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [af0678336d](https://linux-hardware.org/?probe=af0678336d) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [76db4c685b](https://linux-hardware.org/?probe=76db4c685b) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [9f1a2edf3b](https://linux-hardware.org/?probe=9f1a2edf3b) | Apr 15, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [e9b6076df4](https://linux-hardware.org/?probe=e9b6076df4) | Apr 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a470a3b5a](https://linux-hardware.org/?probe=1a470a3b5a) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [f7435e4d65](https://linux-hardware.org/?probe=f7435e4d65) | Apr 09, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [53ed0bc068](https://linux-hardware.org/?probe=53ed0bc068) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Dell          | Latitude E5570              | Notebook    | [7d6ff0e0d8](https://linux-hardware.org/?probe=7d6ff0e0d8) | Apr 07, 2023 |
| Dell          | 03GP4T A01                  | Server      | [621a5675e8](https://linux-hardware.org/?probe=621a5675e8) | Apr 06, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7c95c976a9](https://linux-hardware.org/?probe=7c95c976a9) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e45ad193f8](https://linux-hardware.org/?probe=e45ad193f8) | Apr 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [e9fe5cb307](https://linux-hardware.org/?probe=e9fe5cb307) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [59c335754f](https://linux-hardware.org/?probe=59c335754f) | Apr 01, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [6c70ac23df](https://linux-hardware.org/?probe=6c70ac23df) | Mar 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fcb8359930](https://linux-hardware.org/?probe=fcb8359930) | Mar 28, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2558605a4b](https://linux-hardware.org/?probe=2558605a4b) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [43dbfddd1b](https://linux-hardware.org/?probe=43dbfddd1b) | Mar 28, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [ac8e41d993](https://linux-hardware.org/?probe=ac8e41d993) | Mar 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad7937aaf](https://linux-hardware.org/?probe=3ad7937aaf) | Mar 26, 2023 |
| Dell          | 0RN474                      | Desktop     | [1fb7cf06d1](https://linux-hardware.org/?probe=1fb7cf06d1) | Mar 25, 2023 |
| Dell          | 0RN474                      | Desktop     | [88b56f0530](https://linux-hardware.org/?probe=88b56f0530) | Mar 24, 2023 |
| HP            | 0AACh                       | Desktop     | [2a1f96ca8d](https://linux-hardware.org/?probe=2a1f96ca8d) | Mar 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [789ca3dc74](https://linux-hardware.org/?probe=789ca3dc74) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| HP            | ProBook 6470b               | Notebook    | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | Notebook    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | Notebook    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| MSI           | CR500                       | Notebook    | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| Dell          | Latitude 5580               | Notebook    | [819b5d8dc2](https://linux-hardware.org/?probe=819b5d8dc2) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [ca10594901](https://linux-hardware.org/?probe=ca10594901) | Mar 12, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [0b55f12ab3](https://linux-hardware.org/?probe=0b55f12ab3) | Mar 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [8e02302d63](https://linux-hardware.org/?probe=8e02302d63) | Mar 09, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| Acer          | Aspire VN7-792G             | Notebook    | [3b4a3b74a1](https://linux-hardware.org/?probe=3b4a3b74a1) | Mar 07, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c76255503](https://linux-hardware.org/?probe=0c76255503) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc28c47011](https://linux-hardware.org/?probe=fc28c47011) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [dda5eec4b9](https://linux-hardware.org/?probe=dda5eec4b9) | Feb 28, 2023 |
| Gigabyte      | X58A-UD5                    | Desktop     | [4cff35f888](https://linux-hardware.org/?probe=4cff35f888) | Feb 27, 2023 |
| Google        | Voxel                       | Notebook    | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [faeee1c46c](https://linux-hardware.org/?probe=faeee1c46c) | Feb 24, 2023 |
| HP            | 3397                        | Desktop     | [e714a7b19d](https://linux-hardware.org/?probe=e714a7b19d) | Feb 23, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| HP            | 829A                        | Mini pc     | [8791cd83c7](https://linux-hardware.org/?probe=8791cd83c7) | Feb 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [f1082dcffa](https://linux-hardware.org/?probe=f1082dcffa) | Feb 17, 2023 |
| Medion        | P651x series                | Notebook    | [23b3fb7ce5](https://linux-hardware.org/?probe=23b3fb7ce5) | Feb 16, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [8689383fea](https://linux-hardware.org/?probe=8689383fea) | Feb 15, 2023 |
| HP            | ProBook 4340s               | Notebook    | [caed0e9f2d](https://linux-hardware.org/?probe=caed0e9f2d) | Feb 13, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [aef266643c](https://linux-hardware.org/?probe=aef266643c) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a4791d2bc4](https://linux-hardware.org/?probe=a4791d2bc4) | Feb 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e6c7ea049a](https://linux-hardware.org/?probe=e6c7ea049a) | Feb 10, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [9cbe5cf2b6](https://linux-hardware.org/?probe=9cbe5cf2b6) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [f396fdb21f](https://linux-hardware.org/?probe=f396fdb21f) | Feb 05, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [bac184b151](https://linux-hardware.org/?probe=bac184b151) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | Notebook    | [3f3e5b3a1e](https://linux-hardware.org/?probe=3f3e5b3a1e) | Feb 03, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1cfa73407d](https://linux-hardware.org/?probe=1cfa73407d) | Jan 31, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [221c45eb1b](https://linux-hardware.org/?probe=221c45eb1b) | Jan 29, 2023 |
| MSI           | MS-7513                     | Desktop     | [3953f1b447](https://linux-hardware.org/?probe=3953f1b447) | Jan 28, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d8e161e2b0](https://linux-hardware.org/?probe=d8e161e2b0) | Jan 25, 2023 |
| Gigabyte      | Z490M                       | Desktop     | [a53147a5e7](https://linux-hardware.org/?probe=a53147a5e7) | Jan 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [e589b4bd78](https://linux-hardware.org/?probe=e589b4bd78) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7a3b58d6a7](https://linux-hardware.org/?probe=7a3b58d6a7) | Jan 24, 2023 |
| Acer          | Aspire C24-1650             | All in one  | [3731b0f907](https://linux-hardware.org/?probe=3731b0f907) | Jan 22, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| HP            | 3397                        | Desktop     | [03c53827b5](https://linux-hardware.org/?probe=03c53827b5) | Jan 17, 2023 |
| PC Special... | Recoil II RTX               | Notebook    | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Dell          | Precision 7520              | Notebook    | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [8d5796c907](https://linux-hardware.org/?probe=8d5796c907) | Jan 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b10c786457](https://linux-hardware.org/?probe=b10c786457) | Jan 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cfa8ec5fcb](https://linux-hardware.org/?probe=cfa8ec5fcb) | Jan 13, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [22d0c82134](https://linux-hardware.org/?probe=22d0c82134) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ProBook 6450b               | Notebook    | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [5bf59df74c](https://linux-hardware.org/?probe=5bf59df74c) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| Acer          | H57M01                      | Desktop     | [41ee28ae4b](https://linux-hardware.org/?probe=41ee28ae4b) | Jan 09, 2023 |
| MSI           | MS-7513                     | Desktop     | [6e63c2139f](https://linux-hardware.org/?probe=6e63c2139f) | Jan 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Google        | Voxel                       | Notebook    | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [28cac9b262](https://linux-hardware.org/?probe=28cac9b262) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | Latitude 3510               | Notebook    | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | Notebook    | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [dc13c122ed](https://linux-hardware.org/?probe=dc13c122ed) | Dec 26, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [30c3f8d777](https://linux-hardware.org/?probe=30c3f8d777) | Dec 21, 2022 |
| MSI           | G41M4                       | Desktop     | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [0d273375d6](https://linux-hardware.org/?probe=0d273375d6) | Dec 18, 2022 |
| MSI           | 790GX-G65                   | Desktop     | [7ad3c8f807](https://linux-hardware.org/?probe=7ad3c8f807) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [b779cd6c2f](https://linux-hardware.org/?probe=b779cd6c2f) | Dec 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [fa46f1d34a](https://linux-hardware.org/?probe=fa46f1d34a) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [cd75a3e13f](https://linux-hardware.org/?probe=cd75a3e13f) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Google        | Voxel                       | Notebook    | [b64ebf7db7](https://linux-hardware.org/?probe=b64ebf7db7) | Dec 03, 2022 |
| HP            | 620                         | Notebook    | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | Notebook    | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | Notebook    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| MSI           | A78-G41 PC Mate             | Desktop     | [8487f5d19c](https://linux-hardware.org/?probe=8487f5d19c) | Nov 08, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [3dac8315d4](https://linux-hardware.org/?probe=3dac8315d4) | Nov 04, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [adab8dea39](https://linux-hardware.org/?probe=adab8dea39) | Nov 03, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [82e35bc925](https://linux-hardware.org/?probe=82e35bc925) | Oct 24, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [b110eca1a8](https://linux-hardware.org/?probe=b110eca1a8) | Oct 23, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [241e42fa0a](https://linux-hardware.org/?probe=241e42fa0a) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b0cc9bee74](https://linux-hardware.org/?probe=b0cc9bee74) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [45d676584c](https://linux-hardware.org/?probe=45d676584c) | Oct 02, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [996d72bd1e](https://linux-hardware.org/?probe=996d72bd1e) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [8394fca38a](https://linux-hardware.org/?probe=8394fca38a) | Sep 30, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e35b86c3b7](https://linux-hardware.org/?probe=e35b86c3b7) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f9e71e7e05](https://linux-hardware.org/?probe=f9e71e7e05) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [345959e0ed](https://linux-hardware.org/?probe=345959e0ed) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [3cdcc8b18d](https://linux-hardware.org/?probe=3cdcc8b18d) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d166d32749](https://linux-hardware.org/?probe=d166d32749) | Sep 26, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [bce9addcca](https://linux-hardware.org/?probe=bce9addcca) | Sep 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| Lenovo        | G780                        | Notebook    | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [9de0254ab0](https://linux-hardware.org/?probe=9de0254ab0) | Sep 13, 2022 |
| ASRock        | Z170 Gaming K6+             | Desktop     | [39027cdb44](https://linux-hardware.org/?probe=39027cdb44) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [bec58f880f](https://linux-hardware.org/?probe=bec58f880f) | Sep 13, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [182bb36928](https://linux-hardware.org/?probe=182bb36928) | Sep 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | Notebook    | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [dff587f11e](https://linux-hardware.org/?probe=dff587f11e) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [f5f3761418](https://linux-hardware.org/?probe=f5f3761418) | Aug 19, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | 3098 0B98401 WIN            | Desktop     | [769802c689](https://linux-hardware.org/?probe=769802c689) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [af03bf80b5](https://linux-hardware.org/?probe=af03bf80b5) | Aug 10, 2022 |
| Packard Be... | P5N-E SLI                   | Desktop     | [6f2bf70c0b](https://linux-hardware.org/?probe=6f2bf70c0b) | Aug 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Packard Be... | P5N-E SLI                   | Desktop     | [cdc88569bc](https://linux-hardware.org/?probe=cdc88569bc) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [98ff02ebde](https://linux-hardware.org/?probe=98ff02ebde) | Aug 05, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | Notebook    | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [5d4a26735e](https://linux-hardware.org/?probe=5d4a26735e) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4a3b630b27](https://linux-hardware.org/?probe=4a3b630b27) | Jul 26, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [793c5e80d4](https://linux-hardware.org/?probe=793c5e80d4) | Jul 26, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [ac78b76a30](https://linux-hardware.org/?probe=ac78b76a30) | Jul 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [210b75c48e](https://linux-hardware.org/?probe=210b75c48e) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [17befc2dd5](https://linux-hardware.org/?probe=17befc2dd5) | Jul 20, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [11ddd8feab](https://linux-hardware.org/?probe=11ddd8feab) | Jul 11, 2022 |
| Acer          | Aspire C22-865              | All in one  | [2e0a195007](https://linux-hardware.org/?probe=2e0a195007) | Jul 09, 2022 |
| HP            | 8455                        | Desktop     | [9954a77308](https://linux-hardware.org/?probe=9954a77308) | Jul 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [779bc20f77](https://linux-hardware.org/?probe=779bc20f77) | Jul 05, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| MSI           | EX705                       | Notebook    | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | Notebook    | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | Notebook    | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | Notebook    | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| Shuttle       | FH61V                       | Desktop     | [465dc41fdb](https://linux-hardware.org/?probe=465dc41fdb) | Jun 08, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | Notebook    | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Intel         | DG41KR AAE62839-304         | Desktop     | [d6fa39e82f](https://linux-hardware.org/?probe=d6fa39e82f) | May 16, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [215ded6566](https://linux-hardware.org/?probe=215ded6566) | May 16, 2022 |
| Acer          | H57M01                      | Desktop     | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| Acer          | H57M01                      | Desktop     | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [0b3c6ab0f7](https://linux-hardware.org/?probe=0b3c6ab0f7) | May 14, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | Notebook    | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| Acer          | Extensa 5635G               | Notebook    | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| HP            | ProBook 4540s               | Notebook    | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Unknown       | RS780-SB700                 | Desktop     | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| Dell          | G3 3579                     | Notebook    | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Gigabyte      | Z490M                       | Desktop     | [2138ce9310](https://linux-hardware.org/?probe=2138ce9310) | Apr 18, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [64a66e1b61](https://linux-hardware.org/?probe=64a66e1b61) | Apr 12, 2022 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Acer          | Revo RL80                   | Desktop     | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| HP            | 15                          | Notebook    | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | Notebook    | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| AMI           | Intel                       | Convertible | [b349c1e550](https://linux-hardware.org/?probe=b349c1e550) | Mar 29, 2022 |
| HP            | 18E5                        | Desktop     | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| HP            | ProBook 4340s               | Notebook    | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| HP            | 18E5                        | Desktop     | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Intel         | S3210SH FRU Ver             | Server      | [d608f51576](https://linux-hardware.org/?probe=d608f51576) | Mar 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| VIA Techno... | KM266-8235                  | Desktop     | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| Dell          | Latitude 3510               | Notebook    | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | Notebook    | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 339A                        | Desktop     | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [d24a3aebe9](https://linux-hardware.org/?probe=d24a3aebe9) | Feb 23, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | Notebook    | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [e667cfc4cf](https://linux-hardware.org/?probe=e667cfc4cf) | Feb 20, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [3031d8a880](https://linux-hardware.org/?probe=3031d8a880) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6cbb067e83](https://linux-hardware.org/?probe=6cbb067e83) | Feb 19, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [781ef18260](https://linux-hardware.org/?probe=781ef18260) | Feb 18, 2022 |
| HP            | 339A                        | Desktop     | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| HP            | 339A                        | Desktop     | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| Gigabyte      | Z77-HD3                     | Desktop     | [c72849033f](https://linux-hardware.org/?probe=c72849033f) | Feb 15, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [5306cc74cf](https://linux-hardware.org/?probe=5306cc74cf) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [bfeed2f132](https://linux-hardware.org/?probe=bfeed2f132) | Feb 14, 2022 |
| Lenovo        | 36ED SDK0J40700 WIN 3258... | All in one  | [b5d4b3357a](https://linux-hardware.org/?probe=b5d4b3357a) | Feb 13, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [b6851e2e2d](https://linux-hardware.org/?probe=b6851e2e2d) | Feb 13, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5084dfc411](https://linux-hardware.org/?probe=5084dfc411) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [4a136af33b](https://linux-hardware.org/?probe=4a136af33b) | Feb 12, 2022 |
| Dell          | Latitude E6500              | Notebook    | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | Notebook    | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| ASUSTek       | P6T                         | Desktop     | [10a6e04458](https://linux-hardware.org/?probe=10a6e04458) | Feb 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [ff4d3f33c9](https://linux-hardware.org/?probe=ff4d3f33c9) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| Lenovo        | 3176 NOK                    | Desktop     | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| MSI           | VR201                       | Notebook    | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | Notebook    | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | Notebook    | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | Notebook    | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | Notebook    | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| Dell          | Latitude 3510               | Notebook    | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| MSI           | EX705                       | Notebook    | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [0a01195a57](https://linux-hardware.org/?probe=0a01195a57) | Jan 16, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | Notebook    | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [56a6e6c9eb](https://linux-hardware.org/?probe=56a6e6c9eb) | Dec 29, 2021 |
| ASUSTek       | G751JY                      | Notebook    | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [3edd9950f9](https://linux-hardware.org/?probe=3edd9950f9) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | Notebook    | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [a9eceeac28](https://linux-hardware.org/?probe=a9eceeac28) | Dec 14, 2021 |
| Shuttle       | FH61V                       | Desktop     | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [182ef61d4c](https://linux-hardware.org/?probe=182ef61d4c) | Dec 13, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [75755e4033](https://linux-hardware.org/?probe=75755e4033) | Dec 12, 2021 |
| Gigabyte      | Z77-HD3                     | Desktop     | [7d3626d44d](https://linux-hardware.org/?probe=7d3626d44d) | Dec 12, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [be9daabc79](https://linux-hardware.org/?probe=be9daabc79) | Dec 10, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [eb723f5cb0](https://linux-hardware.org/?probe=eb723f5cb0) | Dec 09, 2021 |
| Dell          | Latitude 3510               | Notebook    | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [67393b8c68](https://linux-hardware.org/?probe=67393b8c68) | Dec 03, 2021 |
| Dell          | Latitude 5401               | Notebook    | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Gigabyte      | H410M S2H                   | Desktop     | [8b917483ef](https://linux-hardware.org/?probe=8b917483ef) | Nov 30, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | Latitude D630               | Notebook    | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | Notebook    | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Dell          | Latitude 7389               | Convertible | [4364726d94](https://linux-hardware.org/?probe=4364726d94) | Nov 21, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | Notebook    | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [cc38af1147](https://linux-hardware.org/?probe=cc38af1147) | Nov 20, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [bf7d34f5c1](https://linux-hardware.org/?probe=bf7d34f5c1) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1386180677](https://linux-hardware.org/?probe=1386180677) | Nov 12, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [92517a0772](https://linux-hardware.org/?probe=92517a0772) | Nov 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eb16aedbc3](https://linux-hardware.org/?probe=eb16aedbc3) | Nov 11, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [d6285c81a2](https://linux-hardware.org/?probe=d6285c81a2) | Nov 05, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [ef8b1adb4b](https://linux-hardware.org/?probe=ef8b1adb4b) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [992b4af8d4](https://linux-hardware.org/?probe=992b4af8d4) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d4ee4ba59f](https://linux-hardware.org/?probe=d4ee4ba59f) | Nov 01, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [17d03d73f7](https://linux-hardware.org/?probe=17d03d73f7) | Oct 30, 2021 |
| HP            | Presario CQ57               | Notebook    | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | Notebook    | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [c74421666a](https://linux-hardware.org/?probe=c74421666a) | Oct 20, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [cdc6d847a7](https://linux-hardware.org/?probe=cdc6d847a7) | Oct 18, 2021 |
| ASUSTek       | K50C                        | Notebook    | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | Notebook    | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bdf9cbc98c](https://linux-hardware.org/?probe=bdf9cbc98c) | Oct 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | Notebook    | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | Notebook    | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | Notebook    | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | Notebook    | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [57894a62f6](https://linux-hardware.org/?probe=57894a62f6) | Sep 21, 2021 |
| Lenovo        | G580                        | Notebook    | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | Notebook    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [6207dd28b2](https://linux-hardware.org/?probe=6207dd28b2) | Sep 09, 2021 |
| UMAX          | VisionBook 11Wi-64G         | Tablet      | [6dcd6a1bf7](https://linux-hardware.org/?probe=6dcd6a1bf7) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bef580a58c](https://linux-hardware.org/?probe=bef580a58c) | Sep 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e0b66566ad](https://linux-hardware.org/?probe=e0b66566ad) | Sep 04, 2021 |
| Dell          | Latitude 3510               | Notebook    | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | Notebook    | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | Notebook    | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [268813fbf4](https://linux-hardware.org/?probe=268813fbf4) | Aug 28, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| ASUSTek       | X51R                        | Notebook    | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [d827460e02](https://linux-hardware.org/?probe=d827460e02) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| Teclast       | F15S                        | Notebook    | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| ASUSTek       | N551JM                      | Notebook    | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [756bb76029](https://linux-hardware.org/?probe=756bb76029) | Jul 25, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f548a06642](https://linux-hardware.org/?probe=f548a06642) | Jul 23, 2021 |
| Timi          | TM1701                      | Notebook    | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| HP            | Presario CQ57               | Notebook    | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | Notebook    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [2acfd9617b](https://linux-hardware.org/?probe=2acfd9617b) | Jul 10, 2021 |
| HP            | 843C                        | Desktop     | [01dc34eeb4](https://linux-hardware.org/?probe=01dc34eeb4) | Jul 07, 2021 |
| HP            | 0A54h                       | Desktop     | [10aa52cef5](https://linux-hardware.org/?probe=10aa52cef5) | Jul 06, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e649a4f85c](https://linux-hardware.org/?probe=e649a4f85c) | Jun 30, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | Desktop     | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| Intel         | X99                         | Desktop     | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | Notebook    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | Desktop     | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | Desktop     | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| Dell          | Precision 7530              | Notebook    | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| HP            | 3397                        | Desktop     | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [74201da57b](https://linux-hardware.org/?probe=74201da57b) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [297ef6b999](https://linux-hardware.org/?probe=297ef6b999) | Jun 06, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [7c519c91ca](https://linux-hardware.org/?probe=7c519c91ca) | Jun 02, 2021 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [7950140465](https://linux-hardware.org/?probe=7950140465) | Jun 02, 2021 |
| ASUSTek       | K54C                        | Notebook    | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | Notebook    | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | Desktop     | [500976e7d1](https://linux-hardware.org/?probe=500976e7d1) | May 30, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| Lenovo        | 0.1                         | Desktop     | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| ASUSTek       | F3M                         | Notebook    | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| Lenovo        | 0.1                         | Desktop     | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0b27475327](https://linux-hardware.org/?probe=0b27475327) | May 26, 2021 |
| eMachines     | E725                        | Notebook    | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [794531a511](https://linux-hardware.org/?probe=794531a511) | May 25, 2021 |
| Lenovo        | Tiger Hill                  | Desktop     | [3f61f1be35](https://linux-hardware.org/?probe=3f61f1be35) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ZOTAC         | ZBOXNANO-AQ02               | Mini pc     | [eb76ff1c3f](https://linux-hardware.org/?probe=eb76ff1c3f) | May 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | Notebook    | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| HP            | 3047h                       | Desktop     | [4fce80ed03](https://linux-hardware.org/?probe=4fce80ed03) | May 20, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| MSI           | A75A-G55                    | Desktop     | [f9773bff22](https://linux-hardware.org/?probe=f9773bff22) | May 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Acer          | Aspire C22-865              | All in one  | [0ef1f4f50d](https://linux-hardware.org/?probe=0ef1f4f50d) | May 16, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| Acer          | Aspire C22-865              | All in one  | [fdc38a2185](https://linux-hardware.org/?probe=fdc38a2185) | May 16, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| Toshiba       | Satellite L735              | Notebook    | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | 843C                        | Desktop     | [e69ec57276](https://linux-hardware.org/?probe=e69ec57276) | May 10, 2021 |
| HP            | Pavilion dv6                | Notebook    | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | Notebook    | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | Notebook    | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [6f0e0fcc43](https://linux-hardware.org/?probe=6f0e0fcc43) | May 03, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [6f147cab82](https://linux-hardware.org/?probe=6f147cab82) | May 03, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | Notebook    | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| HP            | 3048h                       | Desktop     | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [b4ef2db7c1](https://linux-hardware.org/?probe=b4ef2db7c1) | May 01, 2021 |
| Dell          | Latitude 5520               | Notebook    | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | Notebook    | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [995ec93eb1](https://linux-hardware.org/?probe=995ec93eb1) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [228ac8147b](https://linux-hardware.org/?probe=228ac8147b) | Apr 24, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [19b23587fa](https://linux-hardware.org/?probe=19b23587fa) | Apr 20, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [80fac11897](https://linux-hardware.org/?probe=80fac11897) | Apr 20, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [c6ed3bc2f4](https://linux-hardware.org/?probe=c6ed3bc2f4) | Apr 18, 2021 |
| Dell          | System XPS L702X            | Notebook    | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | Notebook    | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [8648cefc80](https://linux-hardware.org/?probe=8648cefc80) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | Notebook    | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | Notebook    | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | 872E                        | Mini pc     | [7791a24770](https://linux-hardware.org/?probe=7791a24770) | Apr 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | Notebook    | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [79c0025946](https://linux-hardware.org/?probe=79c0025946) | Apr 04, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [0b11aa525b](https://linux-hardware.org/?probe=0b11aa525b) | Apr 04, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [aef62f4f18](https://linux-hardware.org/?probe=aef62f4f18) | Apr 02, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [b4b60c7e29](https://linux-hardware.org/?probe=b4b60c7e29) | Apr 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | Notebook    | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | Desktop     | [19aaa9b56e](https://linux-hardware.org/?probe=19aaa9b56e) | Mar 30, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [b72dc7a1c6](https://linux-hardware.org/?probe=b72dc7a1c6) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [0ee0070622](https://linux-hardware.org/?probe=0ee0070622) | Mar 27, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [d68e01744f](https://linux-hardware.org/?probe=d68e01744f) | Mar 26, 2021 |
| ASUSTek       | P5Q SE2                     | Desktop     | [bcc4de28fb](https://linux-hardware.org/?probe=bcc4de28fb) | Mar 26, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [c3909a14fe](https://linux-hardware.org/?probe=c3909a14fe) | Mar 22, 2021 |
| Toshiba       | Satellite C850-13Z          | Notebook    | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | Notebook    | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| Dell          | Latitude 3510               | Notebook    | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| Shuttle       | FH61V                       | Desktop     | [3e811ec55d](https://linux-hardware.org/?probe=3e811ec55d) | Mar 13, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |
| Acer          | One S1003                   | Tablet      | [2a028c4ed4](https://linux-hardware.org/?probe=2a028c4ed4) | Mar 10, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3d4aacd619](https://linux-hardware.org/?probe=3d4aacd619) | Mar 05, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a9a3d7da6f](https://linux-hardware.org/?probe=a9a3d7da6f) | Mar 05, 2021 |
| HP            | Pavilion dv6                | Notebook    | [c26d9748f4](https://linux-hardware.org/?probe=c26d9748f4) | Mar 05, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [aedc60a146](https://linux-hardware.org/?probe=aedc60a146) | Mar 04, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| Lenovo        | ThinkPad SL 2746AEG         | Notebook    | [4591f5d5af](https://linux-hardware.org/?probe=4591f5d5af) | Mar 03, 2021 |
| Shuttle       | FH61V                       | Desktop     | [70d3424aad](https://linux-hardware.org/?probe=70d3424aad) | Mar 02, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [02ec8d4fff](https://linux-hardware.org/?probe=02ec8d4fff) | Mar 01, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | Notebook    | [5f75eafa25](https://linux-hardware.org/?probe=5f75eafa25) | Feb 28, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [323b7be7ea](https://linux-hardware.org/?probe=323b7be7ea) | Feb 27, 2021 |
| Acer          | Aspire C24-860              | All in one  | [e470b33078](https://linux-hardware.org/?probe=e470b33078) | Feb 26, 2021 |
| Acer          | Aspire C24-860              | All in one  | [ee48661ced](https://linux-hardware.org/?probe=ee48661ced) | Feb 26, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [3c402e56a5](https://linux-hardware.org/?probe=3c402e56a5) | Feb 26, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| Dell          | Latitude 3510               | Notebook    | [8a6676e538](https://linux-hardware.org/?probe=8a6676e538) | Feb 25, 2021 |
| Dell          | 0F8096                      | Desktop     | [307334b9d5](https://linux-hardware.org/?probe=307334b9d5) | Feb 24, 2021 |
| Acer          | Extensa 5235                | Notebook    | [48868a0c5e](https://linux-hardware.org/?probe=48868a0c5e) | Feb 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4861f2acca](https://linux-hardware.org/?probe=4861f2acca) | Feb 24, 2021 |
| ASUSTek       | K52F                        | Notebook    | [1492b277a3](https://linux-hardware.org/?probe=1492b277a3) | Feb 24, 2021 |
| Shuttle       | FH61V                       | Desktop     | [f4fe921fe3](https://linux-hardware.org/?probe=f4fe921fe3) | Feb 24, 2021 |
| ASUSTek       | K52F                        | Notebook    | [0369d16c88](https://linux-hardware.org/?probe=0369d16c88) | Feb 24, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | Notebook    | [3103f52c54](https://linux-hardware.org/?probe=3103f52c54) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [4a3e3cd4ee](https://linux-hardware.org/?probe=4a3e3cd4ee) | Feb 23, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Dell          | 02P9X9 A00                  | Server      | [e014b80891](https://linux-hardware.org/?probe=e014b80891) | Feb 23, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e33b6a55d2](https://linux-hardware.org/?probe=e33b6a55d2) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [b8e8be8f5e](https://linux-hardware.org/?probe=b8e8be8f5e) | Feb 20, 2021 |
| eMachines     | eM350                       | Notebook    | [7826551972](https://linux-hardware.org/?probe=7826551972) | Feb 20, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [bfbf37268c](https://linux-hardware.org/?probe=bfbf37268c) | Feb 17, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [f16fabf13a](https://linux-hardware.org/?probe=f16fabf13a) | Feb 16, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [b0b1eb3196](https://linux-hardware.org/?probe=b0b1eb3196) | Feb 14, 2021 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [68fdda8114](https://linux-hardware.org/?probe=68fdda8114) | Feb 14, 2021 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [9f04601c65](https://linux-hardware.org/?probe=9f04601c65) | Feb 14, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [abdd5f9208](https://linux-hardware.org/?probe=abdd5f9208) | Feb 14, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [b664ab9762](https://linux-hardware.org/?probe=b664ab9762) | Feb 11, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aa7f6024cf](https://linux-hardware.org/?probe=aa7f6024cf) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [715d706afe](https://linux-hardware.org/?probe=715d706afe) | Feb 10, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [64c5568456](https://linux-hardware.org/?probe=64c5568456) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9d9da95c79](https://linux-hardware.org/?probe=9d9da95c79) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [4b6ec0748c](https://linux-hardware.org/?probe=4b6ec0748c) | Feb 10, 2021 |
| Dell          | 0PU052                      | Desktop     | [8e0d1be6bf](https://linux-hardware.org/?probe=8e0d1be6bf) | Feb 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [83be789e3c](https://linux-hardware.org/?probe=83be789e3c) | Feb 07, 2021 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [ca67f71815](https://linux-hardware.org/?probe=ca67f71815) | Feb 06, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [bef7d62361](https://linux-hardware.org/?probe=bef7d62361) | Feb 03, 2021 |
| Dell          | 0PU052                      | Desktop     | [cc4b4c54d6](https://linux-hardware.org/?probe=cc4b4c54d6) | Feb 01, 2021 |
| Dell          | Latitude D620               | Notebook    | [8f4c2819b9](https://linux-hardware.org/?probe=8f4c2819b9) | Feb 01, 2021 |
| MSI           | MS-7388                     | Desktop     | [6fc9a5690d](https://linux-hardware.org/?probe=6fc9a5690d) | Feb 01, 2021 |
| Gigabyte      | B360M H 2019-01-02          | Desktop     | [6b2b3ee651](https://linux-hardware.org/?probe=6b2b3ee651) | Jan 28, 2021 |
| HP            | ProBook 4545s               | Notebook    | [9c55ad844b](https://linux-hardware.org/?probe=9c55ad844b) | Jan 28, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b38aa1a092](https://linux-hardware.org/?probe=b38aa1a092) | Jan 25, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [7a321f0327](https://linux-hardware.org/?probe=7a321f0327) | Jan 25, 2021 |
| HP            | Presario CQ57               | Notebook    | [7dcbdb9d0d](https://linux-hardware.org/?probe=7dcbdb9d0d) | Jan 25, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [845de5bee0](https://linux-hardware.org/?probe=845de5bee0) | Jan 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a875950ed5](https://linux-hardware.org/?probe=a875950ed5) | Jan 22, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | Notebook    | [1469bc5f96](https://linux-hardware.org/?probe=1469bc5f96) | Jan 21, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b28f7278cd](https://linux-hardware.org/?probe=b28f7278cd) | Jan 21, 2021 |
| Dell          | 0F8096                      | Desktop     | [27186bb8eb](https://linux-hardware.org/?probe=27186bb8eb) | Jan 18, 2021 |
| Toshiba       | Satellite L850-1HP          | Notebook    | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | Notebook    | [ce71ff03d7](https://linux-hardware.org/?probe=ce71ff03d7) | Jan 16, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [926473c2ac](https://linux-hardware.org/?probe=926473c2ac) | Jan 16, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [8508696f16](https://linux-hardware.org/?probe=8508696f16) | Jan 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Google        | Gnawty                      | Notebook    | [b110360fd0](https://linux-hardware.org/?probe=b110360fd0) | Jan 15, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [e751bd8090](https://linux-hardware.org/?probe=e751bd8090) | Jan 14, 2021 |
| MSI           | CR500                       | Notebook    | [ff982a100f](https://linux-hardware.org/?probe=ff982a100f) | Jan 14, 2021 |
| MSI           | CR500                       | Notebook    | [509fd7cfd1](https://linux-hardware.org/?probe=509fd7cfd1) | Jan 14, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [cac53c0d21](https://linux-hardware.org/?probe=cac53c0d21) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [dcbc8e3b20](https://linux-hardware.org/?probe=dcbc8e3b20) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [4877506709](https://linux-hardware.org/?probe=4877506709) | Jan 14, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [f70c845b60](https://linux-hardware.org/?probe=f70c845b60) | Jan 13, 2021 |
| MSI           | E3M WORKSTATION V5          | Desktop     | [67805433c0](https://linux-hardware.org/?probe=67805433c0) | Jan 13, 2021 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [5e67f36f68](https://linux-hardware.org/?probe=5e67f36f68) | Jan 12, 2021 |
| HP            | ProBook 455 G6              | Notebook    | [da3110fdce](https://linux-hardware.org/?probe=da3110fdce) | Jan 11, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [95a034c1f0](https://linux-hardware.org/?probe=95a034c1f0) | Jan 10, 2021 |
| HP            | 1495                        | Desktop     | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [5e66fb7f43](https://linux-hardware.org/?probe=5e66fb7f43) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [e7c1c02ce7](https://linux-hardware.org/?probe=e7c1c02ce7) | Jan 07, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| HP            | EliteBook 8730w (VQ683EA... | Notebook    | [9650848634](https://linux-hardware.org/?probe=9650848634) | Jan 05, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [70b6c077a6](https://linux-hardware.org/?probe=70b6c077a6) | Jan 05, 2021 |
| Acer          | Swift sf514-54t             | Notebook    | [f56b772338](https://linux-hardware.org/?probe=f56b772338) | Jan 05, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa54fc6400](https://linux-hardware.org/?probe=fa54fc6400) | Jan 05, 2021 |
| HP            | 843C                        | Desktop     | [e6c805f9dd](https://linux-hardware.org/?probe=e6c805f9dd) | Jan 04, 2021 |
| HP            | ProBook 4540s               | Notebook    | [03c94ff635](https://linux-hardware.org/?probe=03c94ff635) | Jan 04, 2021 |
| HP            | ProBook 4540s               | Notebook    | [eb99a077b0](https://linux-hardware.org/?probe=eb99a077b0) | Jan 04, 2021 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [3523a7845f](https://linux-hardware.org/?probe=3523a7845f) | Jan 04, 2021 |
| Gigabyte      | P35-DS3R                    | Desktop     | [af4f72e797](https://linux-hardware.org/?probe=af4f72e797) | Jan 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [caa3d1d91f](https://linux-hardware.org/?probe=caa3d1d91f) | Jan 03, 2021 |
| MSI           | MS-163B Ver                 | Notebook    | [2406d3e9a2](https://linux-hardware.org/?probe=2406d3e9a2) | Jan 02, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [0440c76ce6](https://linux-hardware.org/?probe=0440c76ce6) | Jan 01, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [1cdae8bcc1](https://linux-hardware.org/?probe=1cdae8bcc1) | Jan 01, 2021 |
| MSI           | MS-163B Ver                 | Notebook    | [d3f6e8b5b6](https://linux-hardware.org/?probe=d3f6e8b5b6) | Dec 30, 2020 |
| Acer          | Extensa 5635G               | Notebook    | [a089e8fb2a](https://linux-hardware.org/?probe=a089e8fb2a) | Dec 27, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [192fd63a7c](https://linux-hardware.org/?probe=192fd63a7c) | Dec 27, 2020 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0baf4b3ee](https://linux-hardware.org/?probe=b0baf4b3ee) | Dec 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [e9db8f5ca6](https://linux-hardware.org/?probe=e9db8f5ca6) | Dec 23, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | Desktop     | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [bab0eb442f](https://linux-hardware.org/?probe=bab0eb442f) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e59a36ff39](https://linux-hardware.org/?probe=e59a36ff39) | Dec 22, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [d239275c54](https://linux-hardware.org/?probe=d239275c54) | Dec 21, 2020 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [403bd739c6](https://linux-hardware.org/?probe=403bd739c6) | Dec 21, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [7a5a80d939](https://linux-hardware.org/?probe=7a5a80d939) | Dec 20, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [915d83d090](https://linux-hardware.org/?probe=915d83d090) | Dec 19, 2020 |
| Lenovo        | IdeaPad U260 20067          | Notebook    | [f8b68b1481](https://linux-hardware.org/?probe=f8b68b1481) | Dec 19, 2020 |
| ASUSTek       | X200MA                      | Notebook    | [662934e08a](https://linux-hardware.org/?probe=662934e08a) | Dec 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [5147c1b78e](https://linux-hardware.org/?probe=5147c1b78e) | Dec 17, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a30ab2cb96](https://linux-hardware.org/?probe=a30ab2cb96) | Dec 16, 2020 |
| Fujitsu       | CELSIUS H760                | Notebook    | [bf6b408b8a](https://linux-hardware.org/?probe=bf6b408b8a) | Dec 15, 2020 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [7746ff0cda](https://linux-hardware.org/?probe=7746ff0cda) | Dec 15, 2020 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0719c37bbd](https://linux-hardware.org/?probe=0719c37bbd) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [207e6367f2](https://linux-hardware.org/?probe=207e6367f2) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [3c0a54f9df](https://linux-hardware.org/?probe=3c0a54f9df) | Dec 11, 2020 |
| HP            | ProBook 4330s               | Notebook    | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| Dell          | Precision 7530              | Notebook    | [0d9da6571f](https://linux-hardware.org/?probe=0d9da6571f) | Dec 04, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [b74c06cc19](https://linux-hardware.org/?probe=b74c06cc19) | Dec 03, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [c3770ada06](https://linux-hardware.org/?probe=c3770ada06) | Dec 03, 2020 |
| HP            | ProBook 4330s               | Notebook    | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| Dell          | Precision 7530              | Notebook    | [2ea7f280b2](https://linux-hardware.org/?probe=2ea7f280b2) | Dec 02, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [c17b4a5c87](https://linux-hardware.org/?probe=c17b4a5c87) | Nov 29, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | Notebook    | [f0b41bab99](https://linux-hardware.org/?probe=f0b41bab99) | Nov 28, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | Notebook    | [e89b91cab1](https://linux-hardware.org/?probe=e89b91cab1) | Nov 25, 2020 |
| Dell          | Vostro 5370                 | Notebook    | [653a970a7e](https://linux-hardware.org/?probe=653a970a7e) | Nov 22, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [0d8cea2372](https://linux-hardware.org/?probe=0d8cea2372) | Nov 21, 2020 |
| HP            | Presario CQ57               | Notebook    | [43ffcec233](https://linux-hardware.org/?probe=43ffcec233) | Nov 18, 2020 |
| ASUSTek       | Rampage II GENE             | Desktop     | [53d482a443](https://linux-hardware.org/?probe=53d482a443) | Nov 17, 2020 |
| HP            | Presario CQ57               | Notebook    | [ff87b0c6d6](https://linux-hardware.org/?probe=ff87b0c6d6) | Nov 16, 2020 |
| ASUSTek       | Rampage II GENE             | Desktop     | [1ab17cdc86](https://linux-hardware.org/?probe=1ab17cdc86) | Nov 15, 2020 |
| HP            | ProBook 4330s               | Notebook    | [c9597f3a0d](https://linux-hardware.org/?probe=c9597f3a0d) | Nov 15, 2020 |
| HP            | 3646h                       | Desktop     | [747ede17e0](https://linux-hardware.org/?probe=747ede17e0) | Nov 12, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [33d4c9409a](https://linux-hardware.org/?probe=33d4c9409a) | Nov 11, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8a6ca29d49](https://linux-hardware.org/?probe=8a6ca29d49) | Nov 08, 2020 |
| Lenovo        | G780                        | Notebook    | [145d3ccb54](https://linux-hardware.org/?probe=145d3ccb54) | Nov 08, 2020 |
| Lenovo        | G780                        | Notebook    | [56faed1607](https://linux-hardware.org/?probe=56faed1607) | Nov 06, 2020 |
| Dell          | Latitude 5411               | Notebook    | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | K75VJ                       | Notebook    | [aa4d1aabd8](https://linux-hardware.org/?probe=aa4d1aabd8) | Nov 03, 2020 |
| MSI           | EX705                       | Notebook    | [4307aff155](https://linux-hardware.org/?probe=4307aff155) | Nov 02, 2020 |
| MSI           | EX705                       | Notebook    | [c93a29a4ec](https://linux-hardware.org/?probe=c93a29a4ec) | Nov 02, 2020 |
| ASUSTek       | P5LD2-X/1333                | Desktop     | [fec864df41](https://linux-hardware.org/?probe=fec864df41) | Nov 01, 2020 |
| HP            | 15                          | Notebook    | [8d582da744](https://linux-hardware.org/?probe=8d582da744) | Nov 01, 2020 |
| HP            | 15                          | Notebook    | [0f0be86a64](https://linux-hardware.org/?probe=0f0be86a64) | Nov 01, 2020 |
| ASUSTek       | F5GL                        | Notebook    | [03675a2262](https://linux-hardware.org/?probe=03675a2262) | Oct 31, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [544a018464](https://linux-hardware.org/?probe=544a018464) | Oct 30, 2020 |
| Dell          | G7 7790                     | Notebook    | [7dd8ac2676](https://linux-hardware.org/?probe=7dd8ac2676) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | Notebook    | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| HP            | 3396                        | Desktop     | [73bbba4a08](https://linux-hardware.org/?probe=73bbba4a08) | Oct 29, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b4ce37aee1](https://linux-hardware.org/?probe=b4ce37aee1) | Oct 29, 2020 |
| HP            | 0AA8h                       | Desktop     | [49ed8250dd](https://linux-hardware.org/?probe=49ed8250dd) | Oct 27, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [0d1db60c39](https://linux-hardware.org/?probe=0d1db60c39) | Oct 24, 2020 |
| Gigabyte      | P67X-UD3-B3                 | Desktop     | [67dbb5a0d2](https://linux-hardware.org/?probe=67dbb5a0d2) | Oct 18, 2020 |
| Gigabyte      | P67X-UD3-B3                 | Desktop     | [9f49d2fb4f](https://linux-hardware.org/?probe=9f49d2fb4f) | Oct 18, 2020 |
| Dell          | 0RN474                      | Desktop     | [766ce09345](https://linux-hardware.org/?probe=766ce09345) | Oct 17, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | Notebook    | [782fe456b2](https://linux-hardware.org/?probe=782fe456b2) | Oct 16, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | Notebook    | [51a31505c0](https://linux-hardware.org/?probe=51a31505c0) | Oct 16, 2020 |
| HP            | Presario CQ57               | Notebook    | [d2883f7a48](https://linux-hardware.org/?probe=d2883f7a48) | Oct 14, 2020 |
| HP            | Presario CQ57               | Notebook    | [3646e51370](https://linux-hardware.org/?probe=3646e51370) | Oct 13, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [1457975a9b](https://linux-hardware.org/?probe=1457975a9b) | Oct 12, 2020 |
| HP            | ProBook 4540s               | Notebook    | [095196f795](https://linux-hardware.org/?probe=095196f795) | Oct 09, 2020 |
| HP            | ProBook 4540s               | Notebook    | [0272418c87](https://linux-hardware.org/?probe=0272418c87) | Oct 09, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dd1a01df40](https://linux-hardware.org/?probe=dd1a01df40) | Oct 09, 2020 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [152291e032](https://linux-hardware.org/?probe=152291e032) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [51aeeb5a22](https://linux-hardware.org/?probe=51aeeb5a22) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [6bd0eacb71](https://linux-hardware.org/?probe=6bd0eacb71) | Oct 07, 2020 |
| Toshiba       | Satellite P770              | Notebook    | [9a6b14ab65](https://linux-hardware.org/?probe=9a6b14ab65) | Oct 07, 2020 |
| MSI           | B360 GAMING PLUS            | Desktop     | [a75b777bc2](https://linux-hardware.org/?probe=a75b777bc2) | Oct 04, 2020 |
| Insyde        | SugarBay                    | Desktop     | [ec1ec65380](https://linux-hardware.org/?probe=ec1ec65380) | Oct 01, 2020 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [cea718db3d](https://linux-hardware.org/?probe=cea718db3d) | Sep 30, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1bcd88fae1](https://linux-hardware.org/?probe=1bcd88fae1) | Sep 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e77ec16bac](https://linux-hardware.org/?probe=e77ec16bac) | Sep 29, 2020 |
| HP            | ProBook 6570b               | Notebook    | [c36d7a3815](https://linux-hardware.org/?probe=c36d7a3815) | Sep 27, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [f3f7d7fa86](https://linux-hardware.org/?probe=f3f7d7fa86) | Sep 24, 2020 |
| Lenovo        | ThinkPad T460s 20F9003SG... | Notebook    | [5ee1f4ba42](https://linux-hardware.org/?probe=5ee1f4ba42) | Sep 21, 2020 |
| Dell          | 0T10XW A00                  | Desktop     | [78018fdd06](https://linux-hardware.org/?probe=78018fdd06) | Sep 20, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| Lenovo        | IdeaPad U260 20067          | Notebook    | [c7ee126272](https://linux-hardware.org/?probe=c7ee126272) | Sep 18, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [bda90e6285](https://linux-hardware.org/?probe=bda90e6285) | Sep 16, 2020 |
| HP            | 86FB MVB A                  | Desktop     | [71e7c31b65](https://linux-hardware.org/?probe=71e7c31b65) | Sep 15, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [f9c109d38a](https://linux-hardware.org/?probe=f9c109d38a) | Sep 14, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [241a96fabe](https://linux-hardware.org/?probe=241a96fabe) | Sep 13, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [68c8013cac](https://linux-hardware.org/?probe=68c8013cac) | Sep 13, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [c28899f07f](https://linux-hardware.org/?probe=c28899f07f) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [3a6d68dfe1](https://linux-hardware.org/?probe=3a6d68dfe1) | Sep 10, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [439a065b35](https://linux-hardware.org/?probe=439a065b35) | Sep 07, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cad15a6d4c](https://linux-hardware.org/?probe=cad15a6d4c) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d968666b2d](https://linux-hardware.org/?probe=d968666b2d) | Sep 03, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [654281ba17](https://linux-hardware.org/?probe=654281ba17) | Sep 02, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [afc3f83ad0](https://linux-hardware.org/?probe=afc3f83ad0) | Sep 02, 2020 |
| Lenovo        | 36DD SDK0J40700 WIN 3258... | All in one  | [7ebbf6aad0](https://linux-hardware.org/?probe=7ebbf6aad0) | Sep 01, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [b2fd45876a](https://linux-hardware.org/?probe=b2fd45876a) | Aug 30, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [9243047fd5](https://linux-hardware.org/?probe=9243047fd5) | Aug 30, 2020 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [566417bef1](https://linux-hardware.org/?probe=566417bef1) | Aug 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [92266759e0](https://linux-hardware.org/?probe=92266759e0) | Aug 29, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [93baa51bda](https://linux-hardware.org/?probe=93baa51bda) | Aug 29, 2020 |
| Acer          | Swift SF314-58              | Notebook    | [3aa1021468](https://linux-hardware.org/?probe=3aa1021468) | Aug 28, 2020 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [7a5dc01f13](https://linux-hardware.org/?probe=7a5dc01f13) | Aug 22, 2020 |
| Toshiba       | Satellite C855-1TT          | Notebook    | [98b59c7ddf](https://linux-hardware.org/?probe=98b59c7ddf) | Aug 21, 2020 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [2fbe460b8a](https://linux-hardware.org/?probe=2fbe460b8a) | Aug 16, 2020 |
| Lenovo        | G580                        | Notebook    | [e6435f1530](https://linux-hardware.org/?probe=e6435f1530) | Aug 13, 2020 |
| Sony          | VPCEH1S1E                   | Notebook    | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| MSI           | CR500                       | Notebook    | [6b04b72ba8](https://linux-hardware.org/?probe=6b04b72ba8) | Aug 06, 2020 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [5ffffc7647](https://linux-hardware.org/?probe=5ffffc7647) | Aug 06, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [371a42eb7e](https://linux-hardware.org/?probe=371a42eb7e) | Jul 26, 2020 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c0beab131f](https://linux-hardware.org/?probe=c0beab131f) | Jul 25, 2020 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [153c0aab66](https://linux-hardware.org/?probe=153c0aab66) | Jul 25, 2020 |
| Gigabyte      | GC330UD                     | Desktop     | [bdfbe25730](https://linux-hardware.org/?probe=bdfbe25730) | Jul 25, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [c570792811](https://linux-hardware.org/?probe=c570792811) | Jul 24, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [ef6922214a](https://linux-hardware.org/?probe=ef6922214a) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | Presario CQ57               | Notebook    | [680685ed32](https://linux-hardware.org/?probe=680685ed32) | Jul 19, 2020 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [332ddc42d4](https://linux-hardware.org/?probe=332ddc42d4) | Jul 16, 2020 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dc205c9f7e](https://linux-hardware.org/?probe=dc205c9f7e) | Jul 13, 2020 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b02e3bb9e8](https://linux-hardware.org/?probe=b02e3bb9e8) | Jul 13, 2020 |
| Dell          | Vostro 5370                 | Notebook    | [f8487e0c66](https://linux-hardware.org/?probe=f8487e0c66) | Jul 13, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [08f2adba8a](https://linux-hardware.org/?probe=08f2adba8a) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [c6ed1cd30d](https://linux-hardware.org/?probe=c6ed1cd30d) | Jul 11, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [51d0966405](https://linux-hardware.org/?probe=51d0966405) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | Notebook    | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [57ca2c447b](https://linux-hardware.org/?probe=57ca2c447b) | Jul 06, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [6ab55c2cfa](https://linux-hardware.org/?probe=6ab55c2cfa) | Jul 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [a4b6a8dfb6](https://linux-hardware.org/?probe=a4b6a8dfb6) | Jul 02, 2020 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| UMAX          | VisionBook 14Wg Pro         | Notebook    | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | ProBook 6570b               | Notebook    | [f2370339d5](https://linux-hardware.org/?probe=f2370339d5) | Jun 21, 2020 |
| HP            | ProBook 6570b               | Notebook    | [c477dc5d5b](https://linux-hardware.org/?probe=c477dc5d5b) | Jun 18, 2020 |
| HP            | ProBook 6570b               | Notebook    | [d1f562df2f](https://linux-hardware.org/?probe=d1f562df2f) | Jun 18, 2020 |
| ASUSTek       | M4N78-AM V2                 | Desktop     | [ce2c44ec00](https://linux-hardware.org/?probe=ce2c44ec00) | Jun 16, 2020 |
| Sony          | VPCEH1L8E                   | Notebook    | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Acer          | Aspire 5100                 | Notebook    | [481320cdb6](https://linux-hardware.org/?probe=481320cdb6) | Jun 09, 2020 |
| Acer          | Aspire 5100                 | Notebook    | [0e89938085](https://linux-hardware.org/?probe=0e89938085) | Jun 09, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [eeef655b1c](https://linux-hardware.org/?probe=eeef655b1c) | Jun 07, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [d832045294](https://linux-hardware.org/?probe=d832045294) | Jun 06, 2020 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [bdafad0c82](https://linux-hardware.org/?probe=bdafad0c82) | Jun 06, 2020 |
| Lenovo        | ThinkPad Edge E220s 5038... | Notebook    | [e37f8c0d24](https://linux-hardware.org/?probe=e37f8c0d24) | Jun 05, 2020 |
| MSI           | B150M MORTAR                | Desktop     | [7cdf6f047d](https://linux-hardware.org/?probe=7cdf6f047d) | Jun 01, 2020 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [a570720ce6](https://linux-hardware.org/?probe=a570720ce6) | May 26, 2020 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [38acad164f](https://linux-hardware.org/?probe=38acad164f) | May 25, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [82c8b62b02](https://linux-hardware.org/?probe=82c8b62b02) | May 24, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 99        | 11.86%  |
| Ubuntu 18.04       | 58        | 6.95%   |
| BlackPanther 18.1  | 46        | 5.51%   |
| Ubuntu 22.04       | 32        | 3.83%   |
| OpenMandriva 4.3   | 31        | 3.71%   |
| OpenMandriva 4.2   | 26        | 3.11%   |
| Debian 11          | 19        | 2.28%   |
| Linux Mint 21.1    | 16        | 1.92%   |
| ROSA R10           | 14        | 1.68%   |
| Linux Mint 20.2    | 14        | 1.68%   |
| Linux Mint 20.1    | 14        | 1.68%   |
| Linux Mint 20.3    | 13        | 1.56%   |
| MX 19              | 12        | 1.44%   |
| Linux Mint 21      | 12        | 1.44%   |
| Linux Mint 19.3    | 12        | 1.44%   |
| Arch Rolling       | 12        | 1.44%   |
| OpenMandriva 23.01 | 11        | 1.32%   |
| Fedora 34          | 11        | 1.32%   |
| Pop!_OS 22.04      | 10        | 1.2%    |
| OpenMandriva 23.03 | 10        | 1.2%    |
| Zorin 16           | 9         | 1.08%   |
| Xubuntu 18.04      | 9         | 1.08%   |
| Ubuntu 20.10       | 9         | 1.08%   |
| Ubuntu 19.04       | 8         | 0.96%   |
| Fedora 33          | 8         | 0.96%   |
| Fedora 31          | 8         | 0.96%   |
| Ubuntu 19.10       | 7         | 0.84%   |
| Pop!_OS 21.10      | 7         | 0.84%   |
| Pop!_OS 20.10      | 7         | 0.84%   |
| MX 18              | 7         | 0.84%   |
| Manjaro            | 7         | 0.84%   |
| Linux Mint 20      | 7         | 0.84%   |
| Fedora 37          | 7         | 0.84%   |
| Debian 10          | 7         | 0.84%   |
| Arch               | 7         | 0.84%   |
| Zorin 15           | 6         | 0.72%   |
| ROSA R9            | 6         | 0.72%   |
| Linux Mint 19.1    | 6         | 0.72%   |
| KDE neon 20.04     | 6         | 0.72%   |
| ArcoLinux Rolling  | 6         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 222       | 28.43%  |
| OpenMandriva  | 87        | 11.14%  |
| Linux Mint    | 87        | 11.14%  |
| Fedora        | 50        | 6.4%    |
| BlackPanther  | 49        | 6.27%   |
| Debian        | 32        | 4.1%    |
| ROSA          | 31        | 3.97%   |
| Pop!_OS       | 30        | 3.84%   |
| Xubuntu       | 19        | 2.43%   |
| Arch          | 19        | 2.43%   |
| Zorin         | 18        | 2.3%    |
| Manjaro       | 18        | 2.3%    |
| MX            | 17        | 2.18%   |
| Kubuntu       | 16        | 2.05%   |
| Endless       | 8         | 1.02%   |
| KDE neon      | 7         | 0.9%    |
| Gentoo        | 7         | 0.9%    |
| ArcoLinux     | 7         | 0.9%    |
| Ubuntu Unity  | 5         | 0.64%   |
| openSUSE      | 5         | 0.64%   |
| Devuan        | 5         | 0.64%   |
| Raspbian      | 4         | 0.51%   |
| Lubuntu       | 4         | 0.51%   |
| SteamOS       | 3         | 0.38%   |
| CentOS        | 3         | 0.38%   |
| Ubuntu MATE   | 2         | 0.26%   |
| LMDE          | 2         | 0.26%   |
| Garuda Linux  | 2         | 0.26%   |
| EndeavourOS   | 2         | 0.26%   |
| Elementary    | 2         | 0.26%   |
| antiX         | 2         | 0.26%   |
| Ubuntu Studio | 1         | 0.13%   |
| Ubuntu Budgie | 1         | 0.13%   |
| Rocky Linux   | 1         | 0.13%   |
| Q4OS          | 1         | 0.13%   |
| Parrot        | 1         | 0.13%   |
| Oracle Linux  | 1         | 0.13%   |
| Nobara        | 1         | 0.13%   |
| Mageia        | 1         | 0.13%   |
| Linux Lite    | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP              | 38        | 4.07%   |
| 5.16.7-desktop-1omv4003          | 27        | 2.89%   |
| 5.10.14-desktop-1omv4002         | 25        | 2.68%   |
| 5.4.0-58-generic                 | 14        | 1.5%    |
| 5.6.14-desktop-2bP               | 13        | 1.39%   |
| 5.15.0-56-generic                | 13        | 1.39%   |
| 6.1.1-desktop-1omv2290           | 11        | 1.18%   |
| 6.2.6-desktop-1omv2390           | 10        | 1.07%   |
| 5.4.0-42-generic                 | 10        | 1.07%   |
| 5.4.0-52-generic                 | 8         | 0.86%   |
| 5.15.0-58-generic                | 8         | 0.86%   |
| 4.19.0-13-amd64                  | 8         | 0.86%   |
| 5.8.0-43-generic                 | 7         | 0.75%   |
| 5.19.0-38-generic                | 7         | 0.75%   |
| 5.15.0-43-generic                | 7         | 0.75%   |
| 5.11.0-27-generic                | 7         | 0.75%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 7         | 0.75%   |
| 4.15.0-66-generic                | 7         | 0.75%   |
| 5.4.0-90-generic                 | 6         | 0.64%   |
| 5.4.0-73-generic                 | 6         | 0.64%   |
| 5.3.0-40-generic                 | 6         | 0.64%   |
| 4.19.0-14-amd64                  | 6         | 0.64%   |
| 5.8.0-50-generic                 | 5         | 0.54%   |
| 5.8.0-44-generic                 | 5         | 0.54%   |
| 5.4.0-65-generic                 | 5         | 0.54%   |
| 5.4.0-47-generic                 | 5         | 0.54%   |
| 5.4.0-26-generic                 | 5         | 0.54%   |
| 5.3.0-26-generic                 | 5         | 0.54%   |
| 5.15.0-67-generic                | 5         | 0.54%   |
| 5.15.0-48-generic                | 5         | 0.54%   |
| 5.13.0-22-generic                | 5         | 0.54%   |
| 5.10.0-23-amd64                  | 5         | 0.54%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 5         | 0.54%   |
| 4.19.0-6-amd64                   | 5         | 0.54%   |
| 5.4.0-88-generic                 | 4         | 0.43%   |
| 5.3.0-42-generic                 | 4         | 0.43%   |
| 5.3.0-24-generic                 | 4         | 0.43%   |
| 5.19.0-35-generic                | 4         | 0.43%   |
| 5.19.0-32-generic                | 4         | 0.43%   |
| 5.16.13-desktop-1omv4003         | 4         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 121       | 13.99%  |
| 5.15.0  | 66        | 7.63%   |
| 4.15.0  | 59        | 6.82%   |
| 5.8.0   | 45        | 5.2%    |
| 4.18.16 | 39        | 4.51%   |
| 5.13.0  | 33        | 3.82%   |
| 5.3.0   | 31        | 3.58%   |
| 5.11.0  | 29        | 3.35%   |
| 5.16.7  | 27        | 3.12%   |
| 5.19.0  | 26        | 3.01%   |
| 5.10.14 | 25        | 2.89%   |
| 5.10.0  | 22        | 2.54%   |
| 5.0.0   | 18        | 2.08%   |
| 4.18.0  | 16        | 1.85%   |
| 4.19.0  | 15        | 1.73%   |
| 6.2.6   | 13        | 1.5%    |
| 5.6.14  | 13        | 1.5%    |
| 6.1.1   | 11        | 1.27%   |
| 4.9.60  | 7         | 0.81%   |
| 6.2.0   | 5         | 0.58%   |
| 6.1.0   | 5         | 0.58%   |
| 5.9.16  | 5         | 0.58%   |
| 4.9.20  | 5         | 0.58%   |
| 4.9.124 | 5         | 0.58%   |
| 6.0.10  | 4         | 0.46%   |
| 5.16.13 | 4         | 0.46%   |
| 4.4.0   | 4         | 0.46%   |
| 5.4.83  | 3         | 0.35%   |
| 5.18.12 | 3         | 0.35%   |
| 5.17.5  | 3         | 0.35%   |
| 5.16.11 | 3         | 0.35%   |
| 5.13.4  | 3         | 0.35%   |
| 5.11.3  | 3         | 0.35%   |
| 5.11.12 | 3         | 0.35%   |
| 5.11.11 | 3         | 0.35%   |
| 5.10.17 | 3         | 0.35%   |
| 4.9.0   | 3         | 0.35%   |
| 6.4.8   | 2         | 0.23%   |
| 6.4.0   | 2         | 0.23%   |
| 6.3.8   | 2         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 129       | 15.16%  |
| 5.15    | 91        | 10.69%  |
| 5.10    | 63        | 7.4%    |
| 4.15    | 59        | 6.93%   |
| 4.18    | 55        | 6.46%   |
| 5.8     | 50        | 5.88%   |
| 5.11    | 41        | 4.82%   |
| 5.13    | 39        | 4.58%   |
| 5.16    | 38        | 4.47%   |
| 5.3     | 36        | 4.23%   |
| 5.19    | 31        | 3.64%   |
| 6.1     | 27        | 3.17%   |
| 4.9     | 25        | 2.94%   |
| 6.2     | 22        | 2.59%   |
| 5.0     | 20        | 2.35%   |
| 4.19    | 20        | 2.35%   |
| 5.6     | 17        | 2%      |
| 6.0     | 11        | 1.29%   |
| 5.9     | 10        | 1.18%   |
| 5.12    | 9         | 1.06%   |
| 5.7     | 8         | 0.94%   |
| 5.5     | 7         | 0.82%   |
| 5.18    | 7         | 0.82%   |
| 5.17    | 7         | 0.82%   |
| 6.3     | 6         | 0.71%   |
| 6.4     | 5         | 0.59%   |
| 4.4     | 4         | 0.47%   |
| 5.14    | 3         | 0.35%   |
| 4.1     | 3         | 0.35%   |
| 5.2     | 2         | 0.24%   |
| 5.1     | 1         | 0.12%   |
| 4.7     | 1         | 0.12%   |
| 4.17    | 1         | 0.12%   |
| 4.16    | 1         | 0.12%   |
| 4.12    | 1         | 0.12%   |
| 4.11    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 694       | 91.68%  |
| i686    | 49        | 6.47%   |
| aarch64 | 8         | 1.06%   |
| armv7l  | 6         | 0.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 281       | 36.07%  |
| KDE5            | 195       | 25.03%  |
| Unknown         | 87        | 11.17%  |
| XFCE            | 75        | 9.63%   |
| X-Cinnamon      | 64        | 8.22%   |
| MATE            | 21        | 2.7%    |
| KDE4            | 14        | 1.8%    |
| KDE             | 11        | 1.41%   |
| Cinnamon        | 8         | 1.03%   |
| Unity           | 5         | 0.64%   |
| LXQt            | 5         | 0.64%   |
| LXDE            | 5         | 0.64%   |
| Pantheon        | 2         | 0.26%   |
| Trinity         | 1         | 0.13%   |
| Openbox         | 1         | 0.13%   |
| GNOME Flashback | 1         | 0.13%   |
| Budgie          | 1         | 0.13%   |
| bspwm           | 1         | 0.13%   |
| awesome         | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 617       | 80.03%  |
| Wayland     | 98        | 12.71%  |
| Unknown     | 41        | 5.32%   |
| Tty         | 14        | 1.82%   |
| Unspecified | 1         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 344       | 44.27%  |
| SDDM    | 183       | 23.55%  |
| LightDM | 73        | 9.4%    |
| GDM     | 69        | 8.88%   |
| GDM3    | 65        | 8.37%   |
| TDM     | 21        | 2.7%    |
| KDM     | 14        | 1.8%    |
| SLiM    | 5         | 0.64%   |
| XDM     | 2         | 0.26%   |
| LXDM    | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 298       | 38.01%  |
| sk_SK       | 247       | 31.51%  |
| Unknown     | 159       | 20.28%  |
| cs_CZ       | 27        | 3.44%   |
| C           | 18        | 2.3%    |
| en_GB       | 16        | 2.04%   |
| hu_HU       | 9         | 1.15%   |
| sr_RS@latin | 2         | 0.26%   |
| ru_UA       | 1         | 0.13%   |
| ru_RU       | 1         | 0.13%   |
| POSIX       | 1         | 0.13%   |
| pl_PL       | 1         | 0.13%   |
| it_IT       | 1         | 0.13%   |
| en_US      | 1         | 0.13%   |
| en_AU       | 1         | 0.13%   |
| C.UTF8      | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 473       | 61.51%  |
| EFI  | 296       | 38.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 540       | 69.05%  |
| Overlay | 127       | 16.24%  |
| Btrfs   | 62        | 7.93%   |
| Unknown | 27        | 3.45%   |
| Xfs     | 8         | 1.02%   |
| Zfs     | 7         | 0.9%    |
| Tmpfs   | 6         | 0.77%   |
| Ext2    | 3         | 0.38%   |
| Ext3    | 2         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 376       | 48.52%  |
| GPT     | 224       | 28.9%   |
| MBR     | 175       | 22.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 644       | 82.35%  |
| Yes       | 138       | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 514       | 67.01%  |
| Yes       | 253       | 32.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 162       | 21.54%  |
| Lenovo                  | 130       | 17.29%  |
| Hewlett-Packard         | 107       | 14.23%  |
| Dell                    | 78        | 10.37%  |
| Gigabyte Technology     | 47        | 6.25%   |
| MSI                     | 42        | 5.59%   |
| Acer                    | 38        | 5.05%   |
| ASRock                  | 23        | 3.06%   |
| Toshiba                 | 18        | 2.39%   |
| Intel                   | 13        | 1.73%   |
| Sony                    | 8         | 1.06%   |
| Apple                   | 7         | 0.93%   |
| UMAX                    | 6         | 0.8%    |
| Samsung Electronics     | 5         | 0.66%   |
| Raspberry Pi Foundation | 5         | 0.66%   |
| Fujitsu Siemens         | 5         | 0.66%   |
| Foxconn                 | 5         | 0.66%   |
| Unknown                 | 5         | 0.66%   |
| Fujitsu                 | 4         | 0.53%   |
| ZOTAC                   | 3         | 0.4%    |
| Valve                   | 3         | 0.4%    |
| Timi                    | 3         | 0.4%    |
| Packard Bell            | 3         | 0.4%    |
| HUAWEI                  | 3         | 0.4%    |
| Hardkernel              | 3         | 0.4%    |
| eMachines               | 3         | 0.4%    |
| Techvision              | 2         | 0.27%   |
| Shuttle                 | 2         | 0.27%   |
| Pegatron                | 2         | 0.27%   |
| Medion                  | 2         | 0.27%   |
| Google                  | 2         | 0.27%   |
| Xunlong                 | 1         | 0.13%   |
| VIA Technologies        | 1         | 0.13%   |
| TYAN Computer           | 1         | 0.13%   |
| Teclast                 | 1         | 0.13%   |
| sunxi                   | 1         | 0.13%   |
| Rockchip                | 1         | 0.13%   |
| Radiant Systems         | 1         | 0.13%   |
| Quanta                  | 1         | 0.13%   |
| PC Specialist           | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ASUS All Series                         | 11        | 1.46%   |
| Unknown                                 | 6         | 0.8%    |
| HP Pavilion dv6                         | 4         | 0.53%   |
| ASUS X550CC                             | 4         | 0.53%   |
| ASUS TUF Gaming B550M-PLUS              | 4         | 0.53%   |
| Valve Jupiter                           | 3         | 0.4%    |
| RPi Raspberry Pi 4 Model B Rev 1.4      | 3         | 0.4%    |
| Lenovo IdeaPadFlex 5 15IIL05 81X3       | 3         | 0.4%    |
| HP ProBook 4540s                        | 3         | 0.4%    |
| HP ProBook 4330s                        | 3         | 0.4%    |
| HP Pavilion g6                          | 3         | 0.4%    |
| Hardkernel ODROID-M1                    | 3         | 0.4%    |
| Gigabyte F2A68HM-DS2                    | 3         | 0.4%    |
| Acer Swift SF314-43                     | 3         | 0.4%    |
| UMAX VisionBook 14Wr Plus               | 2         | 0.27%   |
| Toshiba Satellite P300                  | 2         | 0.27%   |
| Timi Redmi Book Pro 15 2022             | 2         | 0.27%   |
| Techvision TVI7309X                     | 2         | 0.27%   |
| MSI VR610                               | 2         | 0.27%   |
| MSI MS-7D25                             | 2         | 0.27%   |
| MSI MS-7C02                             | 2         | 0.27%   |
| MSI MS-7592                             | 2         | 0.27%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX      | 2         | 0.27%   |
| Lenovo IdeaPad Z500 20202               | 2         | 0.27%   |
| Lenovo IdeaPad U260 20067               | 2         | 0.27%   |
| Lenovo IdeaPad S145-14AST 81ST          | 2         | 0.27%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2     | 2         | 0.27%   |
| Lenovo IdeaCentre Q180 10087&3110       | 2         | 0.27%   |
| Lenovo G580                             | 2         | 0.27%   |
| HUAWEI KLVL-WXX9                        | 2         | 0.27%   |
| HP ProBook 6570b                        | 2         | 0.27%   |
| HP ProBook 650 G1                       | 2         | 0.27%   |
| HP ProBook 4545s                        | 2         | 0.27%   |
| HP ProBook 450 G5                       | 2         | 0.27%   |
| HP ProBook 4340s                        | 2         | 0.27%   |
| HP Pavilion 11 x360 PC                  | 2         | 0.27%   |
| HP EliteBook 8470p                      | 2         | 0.27%   |
| HP EliteBook 2570p                      | 2         | 0.27%   |
| HP Compaq Elite 8300 SFF                | 2         | 0.27%   |
| HP Compaq dc7800p Convertible Minitower | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 49        | 6.52%   |
| Lenovo IdeaPad       | 33        | 4.39%   |
| Dell Latitude        | 29        | 3.86%   |
| HP ProBook           | 26        | 3.46%   |
| Acer Aspire          | 22        | 2.93%   |
| Toshiba Satellite    | 16        | 2.13%   |
| HP Compaq            | 16        | 2.13%   |
| HP Pavilion          | 15        | 1.99%   |
| HP EliteBook         | 14        | 1.86%   |
| ASUS ROG             | 12        | 1.6%    |
| ASUS All             | 11        | 1.46%   |
| ASUS PRIME           | 10        | 1.33%   |
| Dell XPS             | 9         | 1.2%    |
| Dell Vostro          | 9         | 1.2%    |
| Dell OptiPlex        | 9         | 1.2%    |
| Lenovo Yoga          | 8         | 1.06%   |
| Dell Inspiron        | 8         | 1.06%   |
| ASUS TUF             | 7         | 0.93%   |
| Acer Swift           | 7         | 0.93%   |
| Dell Precision       | 6         | 0.8%    |
| ASUS VivoBook        | 6         | 0.8%    |
| Unknown              | 6         | 0.8%    |
| UMAX VisionBook      | 5         | 0.66%   |
| RPi Raspberry        | 5         | 0.66%   |
| Lenovo IdeaCentre    | 5         | 0.66%   |
| Lenovo ThinkCentre   | 4         | 0.53%   |
| Lenovo IdeaPadFlex   | 4         | 0.53%   |
| HP ProLiant          | 4         | 0.53%   |
| ASUS X550CC          | 4         | 0.53%   |
| Acer Extensa         | 4         | 0.53%   |
| Valve Jupiter        | 3         | 0.4%    |
| Lenovo Legion        | 3         | 0.4%    |
| HP ZBook             | 3         | 0.4%    |
| HP Spectre           | 3         | 0.4%    |
| HP Laptop            | 3         | 0.4%    |
| Hardkernel ODROID-M1 | 3         | 0.4%    |
| Gigabyte F2A68HM-DS2 | 3         | 0.4%    |
| Fujitsu LIFEBOOK     | 3         | 0.4%    |
| Dell PowerEdge       | 3         | 0.4%    |
| ASUS ZenBook         | 3         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 78        | 10.37%  |
| 2013    | 64        | 8.51%   |
| 2019    | 56        | 7.45%   |
| 2020    | 53        | 7.05%   |
| 2008    | 51        | 6.78%   |
| 2011    | 49        | 6.52%   |
| 2009    | 48        | 6.38%   |
| 2018    | 46        | 6.12%   |
| 2010    | 41        | 5.45%   |
| 2014    | 40        | 5.32%   |
| 2007    | 39        | 5.19%   |
| 2021    | 38        | 5.05%   |
| 2017    | 36        | 4.79%   |
| 2016    | 31        | 4.12%   |
| 2015    | 25        | 3.32%   |
| 2006    | 21        | 2.79%   |
| 2022    | 17        | 2.26%   |
| Unknown | 11        | 1.46%   |
| 2005    | 3         | 0.4%    |
| 2023    | 2         | 0.27%   |
| 2002    | 1         | 0.13%   |
| 2001    | 1         | 0.13%   |
| 2000    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 414       | 55.05%  |
| Desktop        | 273       | 36.3%   |
| Convertible    | 20        | 2.66%   |
| All in one     | 14        | 1.86%   |
| System on chip | 12        | 1.6%    |
| Mini pc        | 9         | 1.2%    |
| Server         | 6         | 0.8%    |
| Tablet         | 4         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 700       | 92.59%  |
| Enabled  | 56        | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 750       | 99.73%  |
| Yes  | 2         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 193       | 24.97%  |
| 4.01-8.0        | 176       | 22.77%  |
| 8.01-16.0       | 136       | 17.59%  |
| 16.01-24.0      | 117       | 15.14%  |
| 1.01-2.0        | 46        | 5.95%   |
| 32.01-64.0      | 45        | 5.82%   |
| 2.01-3.0        | 20        | 2.59%   |
| 64.01-256.0     | 16        | 2.07%   |
| 0.51-1.0        | 12        | 1.55%   |
| 24.01-32.0      | 7         | 0.91%   |
| 0.01-0.5        | 3         | 0.39%   |
| More than 256.0 | 2         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 317       | 37.51%  |
| 2.01-3.0   | 179       | 21.18%  |
| 0.51-1.0   | 106       | 12.54%  |
| 3.01-4.0   | 88        | 10.41%  |
| 4.01-8.0   | 75        | 8.88%   |
| 0.01-0.5   | 42        | 4.97%   |
| 8.01-16.0  | 35        | 4.14%   |
| 16.01-24.0 | 2         | 0.24%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 477       | 59.77%  |
| 2      | 209       | 26.19%  |
| 3      | 57        | 7.14%   |
| 4      | 18        | 2.26%   |
| 5      | 15        | 1.88%   |
| 0      | 14        | 1.75%   |
| 6      | 5         | 0.63%   |
| 17     | 1         | 0.13%   |
| 8      | 1         | 0.13%   |
| 7      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 415       | 54.46%  |
| Yes       | 347       | 45.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 654       | 86.74%  |
| No        | 100       | 13.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 529       | 69.79%  |
| No        | 229       | 30.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 391       | 51.31%  |
| No        | 371       | 48.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovakia | 752       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Bratislava             | 271       | 32.73%  |
| Košice                | 56        | 6.76%   |
| Nitra                  | 34        | 4.11%   |
| Banská Bystrica       | 32        | 3.86%   |
| Žilina                | 17        | 2.05%   |
| Trnava                 | 12        | 1.45%   |
| Prešov                | 12        | 1.45%   |
| Nové Zámky           | 12        | 1.45%   |
| Humenné               | 12        | 1.45%   |
| Poprad                 | 11        | 1.33%   |
| Martin                 | 10        | 1.21%   |
| Dolny Ohaj             | 10        | 1.21%   |
| Zvolen                 | 9         | 1.09%   |
| Levice                 | 8         | 0.97%   |
| Bardejov               | 8         | 0.97%   |
| Trenčín              | 7         | 0.85%   |
| Brezno                 | 7         | 0.85%   |
| Tornaľa               | 6         | 0.72%   |
| Soblahov               | 6         | 0.72%   |
| Cechynce               | 6         | 0.72%   |
| Ružomberok            | 5         | 0.6%    |
| Pezinok                | 5         | 0.6%    |
| Lučenec               | 5         | 0.6%    |
| Liptovský Mikuláš   | 5         | 0.6%    |
| Kysucké Nové Mesto   | 5         | 0.6%    |
| Topoľčany            | 4         | 0.48%   |
| Skalica                | 4         | 0.48%   |
| Senec                  | 4         | 0.48%   |
| Rožňava              | 4         | 0.48%   |
| Rimavská Sobota       | 4         | 0.48%   |
| Modra                  | 4         | 0.48%   |
| Galanta                | 4         | 0.48%   |
| Dunajská Streda       | 4         | 0.48%   |
| Velky Krtis            | 3         | 0.36%   |
| Štúrovo              | 3         | 0.36%   |
| Šaľa                 | 3         | 0.36%   |
| PetrЕѕalka           | 3         | 0.36%   |
| Nové Mesto nad Váhom | 3         | 0.36%   |
| Nitrianske Hrnciarovce | 3         | 0.36%   |
| Námestovo             | 3         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 198       | 354    | 18.28%  |
| Seagate                     | 172       | 251    | 15.88%  |
| Samsung Electronics         | 150       | 225    | 13.85%  |
| Toshiba                     | 59        | 83     | 5.45%   |
| Kingston                    | 58        | 73     | 5.36%   |
| Unknown                     | 46        | 69     | 4.25%   |
| Sandisk                     | 42        | 51     | 3.88%   |
| Hitachi                     | 42        | 53     | 3.88%   |
| Intel                       | 38        | 54     | 3.51%   |
| A-DATA Technology           | 36        | 54     | 3.32%   |
| Patriot                     | 33        | 54     | 3.05%   |
| SK hynix                    | 22        | 26     | 2.03%   |
| Crucial                     | 21        | 26     | 1.94%   |
| HGST                        | 19        | 26     | 1.75%   |
| Micron Technology           | 17        | 23     | 1.57%   |
| Apacer                      | 12        | 16     | 1.11%   |
| Phison                      | 8         | 10     | 0.74%   |
| Maxtor                      | 7         | 12     | 0.65%   |
| Fujitsu                     | 6         | 7      | 0.55%   |
| Verbatim                    | 5         | 6      | 0.46%   |
| OCZ                         | 5         | 5      | 0.46%   |
| KIOXIA                      | 5         | 16     | 0.46%   |
| KingDian                    | 5         | 7      | 0.46%   |
| HS-SSD-E100                 | 4         | 4      | 0.37%   |
| Gigabyte Technology         | 4         | 6      | 0.37%   |
| China                       | 4         | 7      | 0.37%   |
| Unknown                     | 4         | 4      | 0.37%   |
| Union Memory                | 3         | 3      | 0.28%   |
| LITEONIT                    | 3         | 3      | 0.28%   |
| LITEON                      | 3         | 3      | 0.28%   |
| Intenso                     | 3         | 6      | 0.28%   |
| IBM/Hitachi                 | 3         | 3      | 0.28%   |
| XPG                         | 2         | 5      | 0.18%   |
| Transcend                   | 2         | 2      | 0.18%   |
| Silicon Motion              | 2         | 3      | 0.18%   |
| Realtek Semiconductor       | 2         | 2      | 0.18%   |
| Phison Electronics          | 2         | 2      | 0.18%   |
| Kingston Technology Company | 2         | 5      | 0.18%   |
| Hewlett-Packard             | 2         | 4      | 0.18%   |
| GOODRAM                     | 2         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Patriot Burst 240GB SSD            | 14        | 1.16%   |
| Samsung SSD 860 EVO 500GB          | 13        | 1.08%   |
| Kingston SV300S37A120G 120GB SSD   | 12        | 1%      |
| Samsung SSD 860 EVO 250GB          | 9         | 0.75%   |
| Samsung SSD 850 EVO 500GB          | 9         | 0.75%   |
| Samsung SSD 850 EVO 250GB          | 9         | 0.75%   |
| Unknown MMC Card  64GB             | 8         | 0.66%   |
| Seagate ST9500325AS 500GB          | 8         | 0.66%   |
| Kingston SA400S37120G 120GB SSD    | 8         | 0.66%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 7         | 0.58%   |
| Patriot Burst 480GB SSD            | 7         | 0.58%   |
| Patriot Burst 120GB SSD            | 7         | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB           | 6         | 0.5%    |
| Seagate ST9500420AS 500GB          | 6         | 0.5%    |
| Seagate ST3500418AS 500GB          | 6         | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB     | 6         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.5%    |
| SanDisk NVMe SSD Drive 1024GB      | 6         | 0.5%    |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 5         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 5         | 0.42%   |
| Toshiba NVMe SSD Drive 512GB       | 5         | 0.42%   |
| Samsung SSD 870 EVO 500GB          | 5         | 0.42%   |
| Samsung NVMe SSD Drive 500GB       | 5         | 0.42%   |
| Hitachi HTS543232A7A384 320GB      | 5         | 0.42%   |
| HGST HTS725050A7E630 500GB         | 5         | 0.42%   |
| HGST HTS721010A9E630 1TB           | 5         | 0.42%   |
| Apacer AS350 512GB SSD             | 5         | 0.42%   |
| A-DATA SU650 120GB SSD             | 5         | 0.42%   |
| A-DATA SP600 32GB SSD              | 5         | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 4         | 0.33%   |
| Unknown MMC Card  32GB             | 4         | 0.33%   |
| Unknown MMC Card  1GB              | 4         | 0.33%   |
| Toshiba MQ01ABD100 1TB             | 4         | 0.33%   |
| Toshiba DT01ACA100 1TB             | 4         | 0.33%   |
| Seagate ST9250315AS 250GB          | 4         | 0.33%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 0.33%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.33%   |
| Seagate ST3320311CS 320GB          | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 170       | 312    | 34.98%  |
| Seagate             | 170       | 248    | 34.98%  |
| Hitachi             | 42        | 53     | 8.64%   |
| Toshiba             | 41        | 63     | 8.44%   |
| Samsung Electronics | 22        | 35     | 4.53%   |
| HGST                | 19        | 26     | 3.91%   |
| Maxtor              | 7         | 12     | 1.44%   |
| Fujitsu             | 6         | 7      | 1.23%   |
| IBM/Hitachi         | 3         | 3      | 0.62%   |
| USB3.0              | 1         | 2      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |
| StoreJet            | 1         | 1      | 0.21%   |
| HGST HTS            | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 3      | 0.21%   |
| ExcelStor           | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 81        | 105    | 22.95%  |
| Kingston            | 45        | 60     | 12.75%  |
| Patriot             | 31        | 52     | 8.78%   |
| A-DATA Technology   | 30        | 48     | 8.5%    |
| Intel               | 23        | 35     | 6.52%   |
| SanDisk             | 22        | 26     | 6.23%   |
| WDC                 | 21        | 25     | 5.95%   |
| Crucial             | 21        | 26     | 5.95%   |
| Apacer              | 9         | 13     | 2.55%   |
| Micron Technology   | 8         | 12     | 2.27%   |
| Toshiba             | 7         | 7      | 1.98%   |
| SK hynix            | 6         | 6      | 1.7%    |
| OCZ                 | 5         | 5      | 1.42%   |
| Verbatim            | 4         | 5      | 1.13%   |
| China               | 4         | 7      | 1.13%   |
| LITEONIT            | 3         | 3      | 0.85%   |
| LITEON              | 3         | 3      | 0.85%   |
| KingDian            | 3         | 5      | 0.85%   |
| Intenso             | 3         | 6      | 0.85%   |
| Gigabyte Technology | 3         | 5      | 0.85%   |
| Union Memory        | 2         | 2      | 0.57%   |
| Transcend           | 2         | 2      | 0.57%   |
| GOODRAM             | 2         | 4      | 0.57%   |
| FORESEE             | 2         | 3      | 0.57%   |
| WDC WDS2            | 1         | 1      | 0.28%   |
| ULTIMATE            | 1         | 2      | 0.28%   |
| PNY                 | 1         | 2      | 0.28%   |
| KingSpec            | 1         | 1      | 0.28%   |
| IM3D                | 1         | 1      | 0.28%   |
| HS-SSD-E100         | 1         | 1      | 0.28%   |
| HS-SSD-C100         | 1         | 3      | 0.28%   |
| Hewlett-Packard     | 1         | 1      | 0.28%   |
| Faspeed             | 1         | 1      | 0.28%   |
| Emtec               | 1         | 1      | 0.28%   |
| Corsair             | 1         | 1      | 0.28%   |
| AMD                 | 1         | 1      | 0.28%   |
| 2.5                 | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 400       | 768    | 41.71%  |
| SSD     | 313       | 482    | 32.64%  |
| NVMe    | 184       | 272    | 19.19%  |
| MMC     | 48        | 70     | 5.01%   |
| Unknown | 14        | 15     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 585       | 1230   | 69.07%  |
| NVMe | 184       | 271    | 21.72%  |
| MMC  | 48        | 70     | 5.67%   |
| SAS  | 30        | 36     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 486       | 842    | 66.58%  |
| 0.51-1.0   | 164       | 275    | 22.47%  |
| 1.01-2.0   | 49        | 74     | 6.71%   |
| 3.01-4.0   | 14        | 25     | 1.92%   |
| 2.01-3.0   | 11        | 22     | 1.51%   |
| 4.01-10.0  | 5         | 11     | 0.68%   |
| 10.01-20.0 | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 203       | 24.49%  |
| 251-500        | 164       | 19.78%  |
| 501-1000       | 115       | 13.87%  |
| 1-20           | 102       | 12.3%   |
| Unknown        | 62        | 7.48%   |
| 51-100         | 59        | 7.12%   |
| 21-50          | 46        | 5.55%   |
| 1001-2000      | 45        | 5.43%   |
| More than 3000 | 18        | 2.17%   |
| 2001-3000      | 15        | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 347       | 41.26%  |
| 21-50          | 132       | 15.7%   |
| 101-250        | 92        | 10.94%  |
| 51-100         | 87        | 10.34%  |
| Unknown        | 62        | 7.37%   |
| 251-500        | 54        | 6.42%   |
| 501-1000       | 40        | 4.76%   |
| 1001-2000      | 17        | 2.02%   |
| More than 3000 | 7         | 0.83%   |
| 2001-3000      | 3         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB                 | 3         | 5      | 2.83%   |
| Seagate ST9500325AS 500GB               | 3         | 4      | 2.83%   |
| WDC WD10EZEX-75WN4A0 1TB                | 2         | 3      | 1.89%   |
| Seagate ST980811AS 80GB                 | 2         | 2      | 1.89%   |
| Seagate ST9250315AS 250GB               | 2         | 2      | 1.89%   |
| Seagate ST3320413CS 320GB               | 2         | 2      | 1.89%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 2      | 1.89%   |
| Kingston SV300S37A60G 64GB SSD          | 2         | 3      | 1.89%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 2      | 1.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 0.94%   |
| WDC WD800JD-60LSA0 80GB                 | 1         | 1      | 0.94%   |
| WDC WD7500BPVT-80HXZT3 752GB            | 1         | 1      | 0.94%   |
| WDC WD7500BPVT-24HXZT3 752GB            | 1         | 1      | 0.94%   |
| WDC WD7500AAVS-00D7B1 752GB             | 1         | 1      | 0.94%   |
| WDC WD5000LPVT-24G33T1 500GB            | 1         | 1      | 0.94%   |
| WDC WD5000BPVT-00HXZT1 500GB            | 1         | 1      | 0.94%   |
| WDC WD5000AAVS-22G9B1 500GB             | 1         | 2      | 0.94%   |
| WDC WD5000AAKX-603CA0 500GB             | 1         | 1      | 0.94%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 1      | 0.94%   |
| WDC WD3200AAKS-22L6A0 320GB             | 1         | 1      | 0.94%   |
| WDC WD3200AAJS-56B4A0 320GB             | 1         | 2      | 0.94%   |
| WDC WD2500AAKX-753CA1 250GB             | 1         | 2      | 0.94%   |
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 1      | 0.94%   |
| WDC WD20EURS-63S48Y0 2TB                | 1         | 1      | 0.94%   |
| WDC WD1600JS-61MHB1 160GB               | 1         | 1      | 0.94%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 4      | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                | 1         | 1      | 0.94%   |
| WDC WD10EZEX-00RKKA0 1TB                | 1         | 1      | 0.94%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1         | 1      | 0.94%   |
| WDC WD10EALX-009BA0 1TB                 | 1         | 1      | 0.94%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 0.94%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 0.94%   |
| Toshiba MK5056GSY 500GB                 | 1         | 1      | 0.94%   |
| Toshiba MK3252GSX 320GB                 | 1         | 1      | 0.94%   |
| Toshiba MK1646GSX 160GB                 | 1         | 2      | 0.94%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 0.94%   |
| SK hynix SC210 2.5 7MM 256GB SSD        | 1         | 1      | 0.94%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 0.94%   |
| Seagate ST9500423AS 500GB               | 1         | 1      | 0.94%   |
| Seagate ST9500420AS 500GB               | 1         | 1      | 0.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 35     | 28.57%  |
| WDC                 | 22        | 30     | 20.95%  |
| Hitachi             | 10        | 10     | 9.52%   |
| Toshiba             | 9         | 12     | 8.57%   |
| Samsung Electronics | 6         | 10     | 5.71%   |
| Kingston            | 5         | 6      | 4.76%   |
| Maxtor              | 3         | 3      | 2.86%   |
| Intel               | 3         | 3      | 2.86%   |
| SK hynix            | 2         | 2      | 1.9%    |
| SanDisk             | 2         | 3      | 1.9%    |
| OCZ                 | 2         | 2      | 1.9%    |
| Micron Technology   | 2         | 2      | 1.9%    |
| HGST                | 2         | 4      | 1.9%    |
| Lenovo              | 1         | 1      | 0.95%   |
| IM3D                | 1         | 1      | 0.95%   |
| IBM/Hitachi         | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 2      | 0.95%   |
| ExcelStor           | 1         | 1      | 0.95%   |
| Crucial             | 1         | 1      | 0.95%   |
| A-DATA Technology   | 1         | 1      | 0.95%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 35     | 36.59%  |
| WDC                 | 21        | 29     | 25.61%  |
| Hitachi             | 10        | 10     | 12.2%   |
| Toshiba             | 9         | 12     | 10.98%  |
| Samsung Electronics | 4         | 8      | 4.88%   |
| Maxtor              | 3         | 3      | 3.66%   |
| HGST                | 2         | 4      | 2.44%   |
| IBM/Hitachi         | 1         | 1      | 1.22%   |
| Fujitsu             | 1         | 2      | 1.22%   |
| ExcelStor           | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 78        | 105    | 77.23%  |
| SSD  | 19        | 21     | 18.81%  |
| NVMe | 4         | 4      | 3.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB           | 2         | 2      | 33.33%  |
| Seagate ST9320325AS 320GB         | 1         | 1      | 16.67%  |
| Seagate ST3500418AS 500GB         | 1         | 2      | 16.67%  |
| Seagate ST2000DM001-1CH164 2TB    | 1         | 1      | 16.67%  |
| Samsung Electronics HD321HJ 320GB | 1         | 2      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 50%     |
| Toshiba             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 422       | 802    | 50.48%  |
| Works    | 310       | 667    | 37.08%  |
| Malfunc  | 98        | 130    | 11.72%  |
| Failed   | 6         | 8      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 488       | 54.28%  |
| AMD                              | 148       | 16.46%  |
| Samsung Electronics              | 60        | 6.67%   |
| SanDisk                          | 33        | 3.67%   |
| Nvidia                           | 24        | 2.67%   |
| JMicron Technology               | 20        | 2.22%   |
| SK hynix                         | 16        | 1.78%   |
| Kingston Technology Company      | 16        | 1.78%   |
| Phison Electronics               | 15        | 1.67%   |
| Toshiba America Info Systems     | 11        | 1.22%   |
| ASMedia Technology               | 11        | 1.22%   |
| Micron Technology                | 9         | 1%      |
| ADATA Technology                 | 8         | 0.89%   |
| VIA Technologies                 | 6         | 0.67%   |
| Marvell Technology Group         | 6         | 0.67%   |
| KIOXIA                           | 5         | 0.56%   |
| Silicon Integrated Systems [SiS] | 3         | 0.33%   |
| LSI Logic / Symbios Logic        | 3         | 0.33%   |
| Hewlett-Packard                  | 3         | 0.33%   |
| Silicon Motion                   | 2         | 0.22%   |
| Realtek Semiconductor            | 2         | 0.22%   |
| Promise Technology               | 2         | 0.22%   |
| Union Memory (Shenzhen)          | 1         | 0.11%   |
| ULi Electronics                  | 1         | 0.11%   |
| Solid State Storage Technology   | 1         | 0.11%   |
| Silicon Image                    | 1         | 0.11%   |
| Micron/Crucial Technology        | 1         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 84        | 7.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 35        | 3.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 30        | 2.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 29        | 2.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 27        | 2.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 22        | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 21        | 1.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 14        | 1.28%   |
| JMicron JMB363 SATA/IDE Controller                                             | 13        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 1.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 12        | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11        | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 0.91%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 10        | 0.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 0.91%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 9         | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 9         | 0.82%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 0.73%   |
| Nvidia MCP61 SATA Controller                                                   | 8         | 0.73%   |
| Nvidia MCP61 IDE                                                               | 8         | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 8         | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 8         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 509       | 54.67%  |
| IDE  | 187       | 20.09%  |
| NVMe | 185       | 19.87%  |
| RAID | 47        | 5.05%   |
| SAS  | 2         | 0.21%   |
| SCSI | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 544       | 72.34%  |
| AMD          | 195       | 25.93%  |
| ARM          | 12        | 1.6%    |
| CentaurHauls | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 8         | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 8         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 0.92%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 7         | 0.92%   |
| ARM Processor                           | 7         | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 6         | 0.79%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz   | 6         | 0.79%   |
| Intel Core i3-5010U CPU @ 2.10GHz       | 5         | 0.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 0.66%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz  | 4         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.53%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 0.53%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 4         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 4         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 0.53%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 4         | 0.53%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 4         | 0.53%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 4         | 0.53%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 4         | 0.53%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz    | 4         | 0.53%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 4         | 0.53%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 4         | 0.53%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz  | 3         | 0.4%    |
| Intel Pentium CPU P6100 @ 2.00GHz       | 3         | 0.4%    |
| Intel Pentium CPU N4200 @ 1.10GHz       | 3         | 0.4%    |
| Intel Pentium CPU N3540 @ 2.16GHz       | 3         | 0.4%    |
| Intel Pentium CPU B960 @ 2.20GHz        | 3         | 0.4%    |
| Intel Pentium CPU 2117U @ 1.80GHz       | 3         | 0.4%    |
| Intel Core i7-9850H CPU @ 2.60GHz       | 3         | 0.4%    |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.4%    |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 3         | 0.4%    |
| Intel Core i5-9300H CPU @ 2.40GHz       | 3         | 0.4%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 137       | 18.1%   |
| Intel Core i7           | 98        | 12.95%  |
| Intel Core i3           | 69        | 9.11%   |
| Intel Core 2 Duo        | 52        | 6.87%   |
| Intel Celeron           | 38        | 5.02%   |
| Other                   | 36        | 4.76%   |
| Intel Pentium           | 36        | 4.76%   |
| AMD Ryzen 5             | 34        | 4.49%   |
| AMD Ryzen 7             | 24        | 3.17%   |
| Intel Core 2 Quad       | 18        | 2.38%   |
| Intel Xeon              | 15        | 1.98%   |
| Intel Atom              | 15        | 1.98%   |
| AMD Ryzen 9             | 12        | 1.59%   |
| Intel Pentium Dual      | 11        | 1.45%   |
| AMD Athlon 64 X2        | 10        | 1.32%   |
| AMD Ryzen 3             | 8         | 1.06%   |
| AMD A8                  | 8         | 1.06%   |
| Intel Pentium Dual-Core | 7         | 0.92%   |
| AMD FX                  | 7         | 0.92%   |
| AMD Athlon II X2        | 7         | 0.92%   |
| AMD A6                  | 7         | 0.92%   |
| Intel Core 2            | 6         | 0.79%   |
| AMD Sempron             | 6         | 0.79%   |
| AMD A10                 | 6         | 0.79%   |
| Intel Celeron M         | 5         | 0.66%   |
| AMD Ryzen 5 PRO         | 5         | 0.66%   |
| AMD A4                  | 5         | 0.66%   |
| Intel Genuine           | 4         | 0.53%   |
| Intel Celeron Dual-Core | 4         | 0.53%   |
| ARM BCM                 | 4         | 0.53%   |
| AMD Ryzen 7 PRO         | 4         | 0.53%   |
| AMD Phenom II X4        | 4         | 0.53%   |
| AMD Phenom              | 4         | 0.53%   |
| AMD E                   | 4         | 0.53%   |
| AMD Athlon X4           | 4         | 0.53%   |
| AMD Athlon 64           | 4         | 0.53%   |
| AMD Athlon              | 4         | 0.53%   |
| Intel Pentium 4         | 3         | 0.4%    |
| Intel Pentium M         | 2         | 0.26%   |
| ARM Allwinner           | 2         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 349       | 46.1%   |
| 4       | 254       | 33.55%  |
| 6       | 53        | 7%      |
| 1       | 39        | 5.15%   |
| 8       | 35        | 4.62%   |
| 12      | 7         | 0.92%   |
| 16      | 5         | 0.66%   |
| 10      | 4         | 0.53%   |
| 3       | 4         | 0.53%   |
| Unknown | 3         | 0.4%    |
| 20      | 2         | 0.26%   |
| 32      | 1         | 0.13%   |
| 24      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 746       | 99.2%   |
| 2      | 5         | 0.66%   |
| 8      | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 405       | 53.71%  |
| 1       | 345       | 45.76%  |
| Unknown | 3         | 0.4%    |
| 4       | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 727       | 96.04%  |
| Unknown        | 16        | 2.11%   |
| 32-bit         | 12        | 1.59%   |
| 64-bit         | 2         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 22.25%  |
| 0x306a9    | 63        | 8.06%   |
| 0x1067a    | 41        | 5.24%   |
| 0x206a7    | 39        | 4.99%   |
| 0x306c3    | 34        | 4.35%   |
| 0x6fb      | 19        | 2.43%   |
| 0x6fd      | 17        | 2.17%   |
| 0x806ea    | 16        | 2.05%   |
| 0x506e3    | 16        | 2.05%   |
| 0x906ea    | 14        | 1.79%   |
| 0x806e9    | 12        | 1.53%   |
| 0x806c1    | 12        | 1.53%   |
| 0x20655    | 12        | 1.53%   |
| 0x906e9    | 11        | 1.41%   |
| 0x406e3    | 11        | 1.41%   |
| 0x10676    | 11        | 1.41%   |
| 0x806ec    | 10        | 1.28%   |
| 0x06001119 | 10        | 1.28%   |
| 0x40651    | 9         | 1.15%   |
| 0x20652    | 9         | 1.15%   |
| 0x010000c8 | 9         | 1.15%   |
| 0x0a50000c | 8         | 1.02%   |
| 0x30678    | 7         | 0.9%    |
| 0x08608103 | 7         | 0.9%    |
| 0x08108109 | 7         | 0.9%    |
| 0x706e5    | 6         | 0.77%   |
| 0x706a1    | 6         | 0.77%   |
| 0x6f2      | 6         | 0.77%   |
| 0x406c3    | 6         | 0.77%   |
| 0x08600106 | 6         | 0.77%   |
| 0x06006705 | 6         | 0.77%   |
| 0x306d4    | 5         | 0.64%   |
| 0x08701021 | 5         | 0.64%   |
| 0x08108102 | 5         | 0.64%   |
| 0x906ed    | 4         | 0.51%   |
| 0x906eb    | 4         | 0.51%   |
| 0x6d8      | 4         | 0.51%   |
| 0x506c9    | 4         | 0.51%   |
| 0x106ca    | 4         | 0.51%   |
| 0x0800820d | 4         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 90        | 11.94%  |
| IvyBridge        | 74        | 9.81%   |
| Penryn           | 57        | 7.56%   |
| Haswell          | 55        | 7.29%   |
| Core             | 53        | 7.03%   |
| SandyBridge      | 47        | 6.23%   |
| Unknown          | 37        | 4.91%   |
| Skylake          | 31        | 4.11%   |
| K10              | 27        | 3.58%   |
| Westmere         | 26        | 3.45%   |
| K8 Hammer        | 25        | 3.32%   |
| Zen 3            | 24        | 3.18%   |
| Zen 2            | 24        | 3.18%   |
| Silvermont       | 21        | 2.79%   |
| Zen+             | 18        | 2.39%   |
| Piledriver       | 17        | 2.25%   |
| TigerLake        | 14        | 1.86%   |
| Excavator        | 11        | 1.46%   |
| Goldmont plus    | 10        | 1.33%   |
| P6               | 9         | 1.19%   |
| Bonnell          | 9         | 1.19%   |
| Icelake          | 8         | 1.06%   |
| Broadwell        | 8         | 1.06%   |
| Zen              | 7         | 0.93%   |
| Nehalem          | 7         | 0.93%   |
| CometLake        | 7         | 0.93%   |
| Steamroller      | 6         | 0.8%    |
| Puma             | 4         | 0.53%   |
| NetBurst         | 4         | 0.53%   |
| Goldmont         | 4         | 0.53%   |
| Bobcat           | 4         | 0.53%   |
| K8 & K10 hybrid  | 3         | 0.4%    |
| Jaguar           | 3         | 0.4%    |
| Bulldozer        | 3         | 0.4%    |
| Tremont          | 2         | 0.27%   |
| K10 Llano        | 2         | 0.27%   |
| Alderlake Hybrid | 2         | 0.27%   |
| K6               | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 403       | 45.85%  |
| Nvidia                                       | 239       | 27.19%  |
| AMD                                          | 225       | 25.6%   |
| Matrox Electronics Systems                   | 6         | 0.68%   |
| VIA Technologies                             | 2         | 0.23%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.23%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.11%   |
| S3 Graphics                                  | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 4.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 40        | 4.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 2.05%   |
| Intel UHD Graphics 620                                                                   | 17        | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.61%   |
| Intel HD Graphics 530                                                                    | 14        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.4%    |
| Intel HD Graphics 620                                                                    | 13        | 1.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.29%   |
| AMD Renoir                                                                               | 12        | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.29%   |
| AMD Lucienne                                                                             | 12        | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.75%   |
| Intel HD Graphics 630                                                                    | 7         | 0.75%   |
| Intel HD Graphics 5500                                                                   | 7         | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.65%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.65%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.65%   |
| AMD RS780L [Radeon 3000]                                                                 | 6         | 0.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 288       | 37.65%  |
| 1 x AMD         | 172       | 22.48%  |
| 1 x Nvidia      | 134       | 17.52%  |
| Intel + Nvidia  | 88        | 11.5%   |
| 2 x AMD         | 20        | 2.61%   |
| Intel + AMD     | 20        | 2.61%   |
| AMD + Nvidia    | 13        | 1.7%    |
| Other           | 12        | 1.57%   |
| 1 x Matrox      | 5         | 0.65%   |
| 2 x Intel       | 3         | 0.39%   |
| 2 x Nvidia      | 2         | 0.26%   |
| 1 x VIA         | 2         | 0.26%   |
| 1 x SiS         | 2         | 0.26%   |
| 3 x AMD         | 1         | 0.13%   |
| 1 x S3 Graphics | 1         | 0.13%   |
| Nvidia + XGI    | 1         | 0.13%   |
| AMD + Matrox    | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 628       | 81.66%  |
| Proprietary | 97        | 12.61%  |
| Unknown     | 44        | 5.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 377       | 48.09%  |
| 0.01-0.5   | 140       | 17.86%  |
| 1.01-2.0   | 107       | 13.65%  |
| 0.51-1.0   | 81        | 10.33%  |
| 3.01-4.0   | 40        | 5.1%    |
| 7.01-8.0   | 14        | 1.79%   |
| 5.01-6.0   | 12        | 1.53%   |
| 2.01-3.0   | 7         | 0.89%   |
| 8.01-16.0  | 4         | 0.51%   |
| 16.01-24.0 | 2         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 111       | 13.79%  |
| AU Optronics            | 87        | 10.81%  |
| LG Display              | 73        | 9.07%   |
| Chimei Innolux          | 57        | 7.08%   |
| BOE                     | 52        | 6.46%   |
| Dell                    | 42        | 5.22%   |
| Philips                 | 37        | 4.6%    |
| Goldstar                | 37        | 4.6%    |
| Hewlett-Packard         | 32        | 3.98%   |
| Chi Mei Optoelectronics | 29        | 3.6%    |
| BenQ                    | 29        | 3.6%    |
| Lenovo                  | 23        | 2.86%   |
| Acer                    | 20        | 2.48%   |
| Ancor Communications    | 18        | 2.24%   |
| AOC                     | 15        | 1.86%   |
| Sharp                   | 14        | 1.74%   |
| NEC Computers           | 11        | 1.37%   |
| Apple                   | 10        | 1.24%   |
| PANDA                   | 8         | 0.99%   |
| LG Philips              | 7         | 0.87%   |
| Iiyama                  | 7         | 0.87%   |
| Fujitsu Siemens         | 7         | 0.87%   |
| Eizo                    | 6         | 0.75%   |
| LG Electronics          | 5         | 0.62%   |
| Unknown                 | 4         | 0.5%    |
| CSO                     | 4         | 0.5%    |
| ASUSTek Computer        | 4         | 0.5%    |
| TMX                     | 3         | 0.37%   |
| Sony                    | 3         | 0.37%   |
| InfoVision              | 3         | 0.37%   |
| HannStar                | 3         | 0.37%   |
| Valve                   | 2         | 0.25%   |
| Toshiba                 | 2         | 0.25%   |
| RTD                     | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| MSI                     | 2         | 0.25%   |
| MiTAC                   | 2         | 0.25%   |
| FUS                     | 2         | 0.25%   |
| CVT                     | 2         | 0.25%   |
| CPT                     | 2         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 0.96%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 7         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.84%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.72%   |
| NEC Computers LCD19WV NEC671C 1440x900 410x256mm 19.0-inch               | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 5         | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.48%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch        | 3         | 0.36%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch        | 3         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch    | 3         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.36%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 3         | 0.36%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.36%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.36%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 3         | 0.36%   |
| Acer LCD Monitor ACR40B0 1920x1080 527x296mm 23.8-inch                   | 3         | 0.36%   |
| Unknown 1780 07E7 1280x1024 337x270mm 17.0-inch                          | 2         | 0.24%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 2         | 0.24%   |
| Sharp HDMI SHP1008 1280x720 820x460mm 37.0-inch                          | 2         | 0.24%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch     | 2         | 0.24%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 304       | 39.43%  |
| 1366x768 (WXGA)    | 149       | 19.33%  |
| 2560x1440 (QHD)    | 35        | 4.54%   |
| 1280x800 (WXGA)    | 35        | 4.54%   |
| 1280x1024 (SXGA)   | 35        | 4.54%   |
| 3840x2160 (4K)     | 34        | 4.41%   |
| 1600x900 (HD+)     | 32        | 4.15%   |
| 1440x900 (WXGA+)   | 31        | 4.02%   |
| 1920x1200 (WUXGA)  | 29        | 3.76%   |
| 1680x1050 (WSXGA+) | 29        | 3.76%   |
| 1600x1200          | 9         | 1.17%   |
| 3440x1440          | 6         | 0.78%   |
| 1360x768           | 6         | 0.78%   |
| 1024x600           | 5         | 0.65%   |
| 1280x720 (HD)      | 4         | 0.52%   |
| 2880x1800          | 3         | 0.39%   |
| 1920x540           | 3         | 0.39%   |
| 1024x768 (XGA)     | 3         | 0.39%   |
| 3840x2400          | 2         | 0.26%   |
| 3200x2000          | 2         | 0.26%   |
| 2560x1600          | 2         | 0.26%   |
| 2160x1440          | 2         | 0.26%   |
| Unknown            | 2         | 0.26%   |
| 800x1280           | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3200x1080          | 1         | 0.13%   |
| 2560x1080          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1280x960           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 221       | 27.15%  |
| 24      | 75        | 9.21%   |
| 13      | 63        | 7.74%   |
| 23      | 56        | 6.88%   |
| 14      | 56        | 6.88%   |
| 21      | 44        | 5.41%   |
| 27      | 42        | 5.16%   |
| 17      | 42        | 5.16%   |
| 19      | 33        | 4.05%   |
| Unknown | 31        | 3.81%   |
| 18      | 20        | 2.46%   |
| 22      | 18        | 2.21%   |
| 20      | 14        | 1.72%   |
| 12      | 14        | 1.72%   |
| 11      | 13        | 1.6%    |
| 25      | 11        | 1.35%   |
| 31      | 8         | 0.98%   |
| 34      | 6         | 0.74%   |
| 84      | 5         | 0.61%   |
| 26      | 5         | 0.61%   |
| 10      | 5         | 0.61%   |
| 32      | 4         | 0.49%   |
| 72      | 3         | 0.37%   |
| 54      | 3         | 0.37%   |
| 46      | 3         | 0.37%   |
| 39      | 3         | 0.37%   |
| 65      | 2         | 0.25%   |
| 48      | 2         | 0.25%   |
| 40      | 2         | 0.25%   |
| 37      | 2         | 0.25%   |
| 16      | 2         | 0.25%   |
| 58      | 1         | 0.12%   |
| 50      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 35      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 7       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 319       | 40.03%  |
| 501-600     | 165       | 20.7%   |
| 401-500     | 118       | 14.81%  |
| 201-300     | 68        | 8.53%   |
| 351-400     | 44        | 5.52%   |
| Unknown     | 31        | 3.89%   |
| 1001-1500   | 12        | 1.51%   |
| 701-800     | 11        | 1.38%   |
| 601-700     | 11        | 1.38%   |
| 801-900     | 8         | 1%      |
| 1501-2000   | 8         | 1%      |
| 901-1000    | 1         | 0.13%   |
| 1-100       | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 519       | 69.85%  |
| 16/10   | 132       | 17.77%  |
| 5/4     | 32        | 4.31%   |
| Unknown | 24        | 3.23%   |
| 4/3     | 16        | 2.15%   |
| 3/2     | 10        | 1.35%   |
| 21/9    | 7         | 0.94%   |
| 6/5     | 1         | 0.13%   |
| 32/9    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 218       | 27.08%  |
| 201-250        | 152       | 18.88%  |
| 81-90          | 89        | 11.06%  |
| 151-200        | 60        | 7.45%   |
| 301-350        | 43        | 5.34%   |
| 141-150        | 38        | 4.72%   |
| 251-300        | 37        | 4.6%    |
| Unknown        | 31        | 3.85%   |
| 71-80          | 30        | 3.73%   |
| 351-500        | 20        | 2.48%   |
| More than 1000 | 16        | 1.99%   |
| 121-130        | 15        | 1.86%   |
| 61-70          | 13        | 1.61%   |
| 51-60          | 13        | 1.61%   |
| 501-1000       | 11        | 1.37%   |
| 131-140        | 7         | 0.87%   |
| 41-50          | 5         | 0.62%   |
| 111-120        | 4         | 0.5%    |
| 91-100         | 2         | 0.25%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 317       | 40.59%  |
| 101-120       | 187       | 23.94%  |
| 121-160       | 181       | 23.18%  |
| 161-240       | 32        | 4.1%    |
| Unknown       | 31        | 3.97%   |
| 1-50          | 17        | 2.18%   |
| More than 240 | 16        | 2.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 609       | 78.99%  |
| 2     | 114       | 14.79%  |
| 0     | 39        | 5.06%   |
| 3     | 9         | 1.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 392       | 35.35%  |
| Intel                                  | 310       | 27.95%  |
| Qualcomm Atheros                       | 152       | 13.71%  |
| Broadcom                               | 65        | 5.86%   |
| Marvell Technology Group               | 21        | 1.89%   |
| Ralink Technology                      | 19        | 1.71%   |
| Nvidia                                 | 19        | 1.71%   |
| TP-Link                                | 17        | 1.53%   |
| Broadcom Limited                       | 16        | 1.44%   |
| Ralink                                 | 14        | 1.26%   |
| Qualcomm Atheros Communications        | 12        | 1.08%   |
| MediaTek                               | 8         | 0.72%   |
| Hewlett-Packard                        | 5         | 0.45%   |
| Xiaomi                                 | 4         | 0.36%   |
| Sierra Wireless                        | 3         | 0.27%   |
| Samsung Electronics                    | 3         | 0.27%   |
| Lenovo                                 | 3         | 0.27%   |
| JMicron Technology                     | 3         | 0.27%   |
| Huawei Technologies                    | 3         | 0.27%   |
| Ericsson Business Mobile Networks      | 3         | 0.27%   |
| DisplayLink                            | 3         | 0.27%   |
| Dell                                   | 3         | 0.27%   |
| VIA Technologies                       | 2         | 0.18%   |
| Fibocom                                | 2         | 0.18%   |
| Edimax Technology                      | 2         | 0.18%   |
| D-Link                                 | 2         | 0.18%   |
| ASUSTek Computer                       | 2         | 0.18%   |
| ASIX Electronics                       | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.09%   |
| WiseGroup                              | 1         | 0.09%   |
| ULi Electronics                        | 1         | 0.09%   |
| Texas Instruments                      | 1         | 0.09%   |
| T & A Mobile Phones                    | 1         | 0.09%   |
| Spreadtrum Communications              | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.09%   |
| Sigma Sport                            | 1         | 0.09%   |
| Pulse-Eight                            | 1         | 0.09%   |
| Prestigio                              | 1         | 0.09%   |
| Nokia Mobile Phones                    | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 269       | 21.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 47        | 3.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 28        | 2.19%   |
| Intel Wireless 8265 / 8275                                              | 24        | 1.88%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 19        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 17        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                       | 12        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 12        | 0.94%   |
| Intel Wireless 8260                                                     | 12        | 0.94%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.86%   |
| Intel Wireless 7260                                                     | 11        | 0.86%   |
| Intel I211 Gigabit Network Connection                                   | 11        | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 10        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.71%   |
| Intel Wireless 7265                                                     | 9         | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.63%   |
| Intel Wireless 3165                                                     | 8         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.63%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.63%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 7         | 0.55%   |
| Nvidia MCP61 Ethernet                                                   | 7         | 0.55%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.55%   |
| Intel WiFi Link 5100                                                    | 7         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.55%   |
| Intel Ethernet Connection (2) I219-V                                    | 7         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 232       | 42.11%  |
| Qualcomm Atheros                | 116       | 21.05%  |
| Realtek Semiconductor           | 70        | 12.7%   |
| Broadcom                        | 36        | 6.53%   |
| Ralink Technology               | 19        | 3.45%   |
| TP-Link                         | 17        | 3.09%   |
| Ralink                          | 14        | 2.54%   |
| Qualcomm Atheros Communications | 12        | 2.18%   |
| Broadcom Limited                | 10        | 1.81%   |
| MediaTek                        | 8         | 1.45%   |
| Sierra Wireless                 | 3         | 0.54%   |
| Fibocom                         | 2         | 0.36%   |
| Edimax Technology               | 2         | 0.36%   |
| Dell                            | 2         | 0.36%   |
| D-Link                          | 2         | 0.36%   |
| ASUSTek Computer                | 2         | 0.36%   |
| Texas Instruments               | 1         | 0.18%   |
| Microsoft                       | 1         | 0.18%   |
| Micro Star International        | 1         | 0.18%   |
| Accton Technology               | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 6.13%   |
| Intel Wireless 8265 / 8275                                              | 24        | 4.32%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 2.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 2.16%   |
| Qualcomm Atheros AR9271 802.11n                                         | 12        | 2.16%   |
| Intel Wireless 8260                                                     | 12        | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 2.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 1.98%   |
| Intel Wireless 7260                                                     | 11        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 1.62%   |
| Intel Wireless 7265                                                     | 9         | 1.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.44%   |
| Intel Wireless 3165                                                     | 8         | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.44%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.26%   |
| Intel Wireless-AC 9260                                                  | 7         | 1.26%   |
| Intel WiFi Link 5100                                                    | 7         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 6         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 6         | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 367       | 53.58%  |
| Intel                                  | 161       | 23.5%   |
| Qualcomm Atheros                       | 49        | 7.15%   |
| Broadcom                               | 31        | 4.53%   |
| Marvell Technology Group               | 21        | 3.07%   |
| Nvidia                                 | 19        | 2.77%   |
| Broadcom Limited                       | 6         | 0.88%   |
| Xiaomi                                 | 4         | 0.58%   |
| Samsung Electronics                    | 3         | 0.44%   |
| Lenovo                                 | 3         | 0.44%   |
| JMicron Technology                     | 3         | 0.44%   |
| DisplayLink                            | 3         | 0.44%   |
| VIA Technologies                       | 2         | 0.29%   |
| Huawei Technologies                    | 2         | 0.29%   |
| ASIX Electronics                       | 2         | 0.29%   |
| T & A Mobile Phones                    | 1         | 0.15%   |
| Spreadtrum Communications              | 1         | 0.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| Prestigio                              | 1         | 0.15%   |
| Nokia Mobile Phones                    | 1         | 0.15%   |
| National Semiconductor                 | 1         | 0.15%   |
| Mellanox Technologies                  | 1         | 0.15%   |
| ICS Advent                             | 1         | 0.15%   |
| Attansic Technology                    | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 269       | 38.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 6.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 3.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 2.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 11        | 1.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 10        | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1%      |
| Nvidia MCP61 Ethernet                                             | 7         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1%      |
| Intel 82579V Gigabit Network Connection                           | 7         | 1%      |
| Intel Ethernet Controller I225-V                                  | 6         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.71%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.57%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 4         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 654       | 54.41%  |
| WiFi     | 529       | 44.01%  |
| Modem    | 18        | 1.5%    |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 411       | 53.73%  |
| Ethernet | 354       | 46.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 402       | 53.17%  |
| 1     | 309       | 40.87%  |
| 0     | 29        | 3.84%   |
| 3     | 10        | 1.32%   |
| 4     | 5         | 0.66%   |
| 5     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 715       | 94.7%   |
| Yes  | 40        | 5.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 159       | 40.15%  |
| Realtek Semiconductor           | 34        | 8.59%   |
| Qualcomm Atheros Communications | 33        | 8.33%   |
| IMC Networks                    | 28        | 7.07%   |
| Broadcom                        | 26        | 6.57%   |
| Lite-On Technology              | 18        | 4.55%   |
| Cambridge Silicon Radio         | 15        | 3.79%   |
| ASUSTek Computer                | 14        | 3.54%   |
| Foxconn / Hon Hai               | 11        | 2.78%   |
| Ralink                          | 9         | 2.27%   |
| Hewlett-Packard                 | 9         | 2.27%   |
| Dell                            | 9         | 2.27%   |
| Apple                           | 8         | 2.02%   |
| Toshiba                         | 6         | 1.52%   |
| Micro Star International        | 3         | 0.76%   |
| Foxconn International           | 3         | 0.76%   |
| Taiyo Yuden                     | 2         | 0.51%   |
| Realtek                         | 2         | 0.51%   |
| HTC (High Tech Computer)        | 2         | 0.51%   |
| TP-Link                         | 1         | 0.25%   |
| Integrated System Solution      | 1         | 0.25%   |
| Fujitsu                         | 1         | 0.25%   |
| Belkin Components               | 1         | 0.25%   |
| Alps Electric                   | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 65        | 16.41%  |
| Intel AX201 Bluetooth                               | 29        | 7.32%   |
| Realtek Bluetooth Radio                             | 21        | 5.3%    |
| Intel AX200 Bluetooth                               | 20        | 5.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 4.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 4.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 3.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 2.78%   |
| Ralink RT3290 Bluetooth                             | 9         | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.27%   |
| IMC Networks Bluetooth Device                       | 9         | 2.27%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.02%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 1.77%   |
| Lite-On Bluetooth Device                            | 6         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.52%   |
| Intel AX210 Bluetooth                               | 6         | 1.52%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.52%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 6         | 1.52%   |
| Realtek RTL8821A Bluetooth                          | 5         | 1.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.01%   |
| Lite-On Wireless_Device                             | 3         | 0.76%   |
| IMC Networks Wireless_Device                        | 3         | 0.76%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.76%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.76%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.76%   |
| Apple Bluetooth HCI                                 | 3         | 0.76%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.51%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.51%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 2         | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.51%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 516       | 52.28%  |
| AMD                                          | 227       | 23%     |
| Nvidia                                       | 160       | 16.21%  |
| C-Media Electronics                          | 17        | 1.72%   |
| Creative Labs                                | 8         | 0.81%   |
| VIA Technologies                             | 6         | 0.61%   |
| Lenovo                                       | 6         | 0.61%   |
| GN Netcom                                    | 6         | 0.61%   |
| Creative Technology                          | 6         | 0.61%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.3%    |
| Yamaha                                       | 2         | 0.2%    |
| Samson Technologies                          | 2         | 0.2%    |
| Logitech                                     | 2         | 0.2%    |
| JMTek                                        | 2         | 0.2%    |
| Blue Microphones                             | 2         | 0.2%    |
| ASUSTek Computer                             | 2         | 0.2%    |
| AKAI Professional M.I.                       | 2         | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.1%    |
| Valve Software                               | 1         | 0.1%    |
| ULi Electronics                              | 1         | 0.1%    |
| Trust                                        | 1         | 0.1%    |
| Textech International                        | 1         | 0.1%    |
| Texas Instruments                            | 1         | 0.1%    |
| SteelSeries ApS                              | 1         | 0.1%    |
| Realtek Semiconductor                        | 1         | 0.1%    |
| Plantronics                                  | 1         | 0.1%    |
| Nordic Semiconductor ASA                     | 1         | 0.1%    |
| Micro Star International                     | 1         | 0.1%    |
| Hewlett-Packard                              | 1         | 0.1%    |
| FUXIN                                        | 1         | 0.1%    |
| Fortemedia                                   | 1         | 0.1%    |
| Focusrite-Novation                           | 1         | 0.1%    |
| Behringer.......                             | 1         | 0.1%    |
| Barco Display Systems                        | 1         | 0.1%    |
| A4Tech                                       | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 73        | 6.28%   |
| AMD Family 17h/19h HD Audio Controller                                     | 54        | 4.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 45        | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 41        | 3.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 40        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 39        | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 38        | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 37        | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 36        | 3.1%    |
| AMD FCH Azalia Controller                                                  | 29        | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 28        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 27        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 1.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 1.98%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18        | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18        | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                              | 14        | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 12        | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 0.95%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 0.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 0.86%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.77%   |
| AMD High Definition Audio Controller                                       | 9         | 0.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9         | 0.77%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 9         | 0.77%   |
| Nvidia MCP61 High Definition Audio                                         | 8         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8         | 0.69%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 8         | 0.69%   |
| AMD Trinity HDMI Audio Controller                                          | 8         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 89        | 18.16%  |
| Samsung Electronics | 86        | 17.55%  |
| SK hynix            | 85        | 17.35%  |
| Unknown             | 81        | 16.53%  |
| Micron Technology   | 40        | 8.16%   |
| Crucial             | 25        | 5.1%    |
| Elpida              | 14        | 2.86%   |
| Corsair             | 13        | 2.65%   |
| Patriot             | 10        | 2.04%   |
| Ramaxel Technology  | 8         | 1.63%   |
| G.Skill             | 7         | 1.43%   |
| A-DATA Technology   | 6         | 1.22%   |
| Unknown (ABCD)      | 5         | 1.02%   |
| Unknown             | 5         | 1.02%   |
| Nanya Technology    | 3         | 0.61%   |
| Transcend           | 2         | 0.41%   |
| Hewlett-Packard     | 2         | 0.41%   |
| Apacer              | 2         | 0.41%   |
| Unknown (8AC8)      | 1         | 0.2%    |
| Unknown (130B)      | 1         | 0.2%    |
| Unigen              | 1         | 0.2%    |
| SHARETRONIC         | 1         | 0.2%    |
| Atermiter           | 1         | 0.2%    |
| ASint Technology    | 1         | 0.2%    |
| 48spaces            | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.28%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.09%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.91%   |
| Unknown                                                          | 5         | 0.91%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.73%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.73%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.73%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.73%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 0.73%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.73%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 4         | 0.73%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 4         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.55%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 3         | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.55%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 3         | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.55%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 0.55%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 3         | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 3         | 0.55%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 3         | 0.55%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 0.55%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 3         | 0.55%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 3         | 0.55%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 0.55%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.36%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 2         | 0.36%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 148       | 35.66%  |
| DDR4    | 141       | 33.98%  |
| DDR2    | 46        | 11.08%  |
| SDRAM   | 24        | 5.78%   |
| Unknown | 22        | 5.3%    |
| LPDDR4  | 16        | 3.86%   |
| DDR     | 8         | 1.93%   |
| LPDDR3  | 6         | 1.45%   |
| DRAM    | 2         | 0.48%   |
| DDR5    | 2         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 238       | 58.05%  |
| DIMM         | 146       | 35.61%  |
| Row Of Chips | 21        | 5.12%   |
| Chip         | 4         | 0.98%   |
| FB-DIMM      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 140       | 29.66%  |
| 4096  | 130       | 27.54%  |
| 2048  | 96        | 20.34%  |
| 16384 | 46        | 9.75%   |
| 1024  | 37        | 7.84%   |
| 32768 | 10        | 2.12%   |
| 512   | 9         | 1.91%   |
| 256   | 2         | 0.42%   |
| 128   | 1         | 0.21%   |
| 64    | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 100       | 21.46%  |
| 2667    | 48        | 10.3%   |
| 3200    | 44        | 9.44%   |
| 667     | 32        | 6.87%   |
| 1333    | 28        | 6.01%   |
| 2400    | 26        | 5.58%   |
| 2133    | 23        | 4.94%   |
| 800     | 23        | 4.94%   |
| 1334    | 18        | 3.86%   |
| 3600    | 12        | 2.58%   |
| Unknown | 12        | 2.58%   |
| 1867    | 9         | 1.93%   |
| 4199    | 7         | 1.5%    |
| 1067    | 7         | 1.5%    |
| 533     | 6         | 1.29%   |
| 333     | 6         | 1.29%   |
| 4266    | 5         | 1.07%   |
| 3266    | 5         | 1.07%   |
| 2048    | 5         | 1.07%   |
| 1866    | 5         | 1.07%   |
| 4267    | 4         | 0.86%   |
| 400     | 4         | 0.86%   |
| 3733    | 3         | 0.64%   |
| 3466    | 3         | 0.64%   |
| 1800    | 3         | 0.64%   |
| 1066    | 3         | 0.64%   |
| 8400    | 2         | 0.43%   |
| 4800    | 2         | 0.43%   |
| 3800    | 2         | 0.43%   |
| 3000    | 2         | 0.43%   |
| 1639    | 2         | 0.43%   |
| 975     | 2         | 0.43%   |
| 57535   | 1         | 0.21%   |
| 6400    | 1         | 0.21%   |
| 4400    | 1         | 0.21%   |
| 4000    | 1         | 0.21%   |
| 3933    | 1         | 0.21%   |
| 3666    | 1         | 0.21%   |
| 3533    | 1         | 0.21%   |
| 3400    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 72.22%  |
| Samsung Electronics   | 2         | 11.11%  |
| Star Micronics        | 1         | 5.56%   |
| Lexmark International | 1         | 5.56%   |
| Canon                 | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                | 4         | 22.22%  |
| HP Deskjet 1050 J410                            | 2         | 11.11%  |
| Star Micronics IP1000 Printer USB001            | 1         | 5.56%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5.56%   |
| Samsung M2070 Series                            | 1         | 5.56%   |
| Lexmark International 2600 Series               | 1         | 5.56%   |
| HP OfficeJet 6950                               | 1         | 5.56%   |
| HP LaserJet M14-M17                             | 1         | 5.56%   |
| HP LaserJet M101-M106                           | 1         | 5.56%   |
| HP LaserJet CP 1025nw                           | 1         | 5.56%   |
| HP LaserJet 1150                                | 1         | 5.56%   |
| HP DeskJet 2700 series                          | 1         | 5.56%   |
| HP Deskjet 1510                                 | 1         | 5.56%   |
| Canon PIXMA MP230                               | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Minolta         | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Minolta Dimage Scan Dual III AF-2840 (2889) | 1         | 20%     |
| HP ScanJet 3800c                            | 1         | 20%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 110                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 120       | 28.5%   |
| IMC Networks                           | 39        | 9.26%   |
| Microdia                               | 35        | 8.31%   |
| Realtek Semiconductor                  | 30        | 7.13%   |
| Syntek                                 | 21        | 4.99%   |
| Bison Electronics                      | 21        | 4.99%   |
| Sunplus Innovation Technology          | 20        | 4.75%   |
| Suyin                                  | 16        | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.09%   |
| Acer                                   | 12        | 2.85%   |
| Quanta                                 | 11        | 2.61%   |
| Logitech                               | 11        | 2.61%   |
| Lite-On Technology                     | 8         | 1.9%    |
| Microsoft                              | 7         | 1.66%   |
| Apple                                  | 7         | 1.66%   |
| Alcor Micro                            | 5         | 1.19%   |
| Z-Star Microelectronics                | 4         | 0.95%   |
| GEMBIRD                                | 4         | 0.95%   |
| Silicon Motion                         | 3         | 0.71%   |
| Ricoh                                  | 3         | 0.71%   |
| Creative Technology                    | 3         | 0.71%   |
| SunplusIT                              | 2         | 0.48%   |
| Samsung Electronics                    | 2         | 0.48%   |
| Luxvisions Innotech Limited            | 2         | 0.48%   |
| LG Electronics                         | 2         | 0.48%   |
| Lenovo                                 | 2         | 0.48%   |
| Importek                               | 2         | 0.48%   |
| Valve Software                         | 1         | 0.24%   |
| Unknown                                | 1         | 0.24%   |
| Tripath Technology                     | 1         | 0.24%   |
| SN0002                                 | 1         | 0.24%   |
| Primax Electronics                     | 1         | 0.24%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.24%   |
| OmniVision Technologies                | 1         | 0.24%   |
| MacroSilicon                           | 1         | 0.24%   |
| KYE Systems (Mouse Systems)            | 1         | 0.24%   |
| icSpring                               | 1         | 0.24%   |
| GenesysLogic Technology                | 1         | 0.24%   |
| Generalplus Technology                 | 1         | 0.24%   |
| Elecom                                 | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 26        | 6.12%   |
| Microdia Integrated_Webcam_HD                       | 13        | 3.06%   |
| Syntek Integrated Camera                            | 12        | 2.82%   |
| IMC Networks Integrated Camera                      | 11        | 2.59%   |
| Chicony HP HD Webcam [Fixed]                        | 9         | 2.12%   |
| Chicony HD WebCam                                   | 9         | 2.12%   |
| Realtek Integrated_Webcam_HD                        | 7         | 1.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 1.65%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 1.41%   |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 1.41%   |
| Bison Integrated Camera                             | 6         | 1.41%   |
| Quanta HP HD Camera                                 | 5         | 1.18%   |
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 1.18%   |
| Syntek Lenovo EasyCamera                            | 4         | 0.94%   |
| Suyin HP Webcam                                     | 4         | 0.94%   |
| Sunplus HP HD Webcam [Fixed]                        | 4         | 0.94%   |
| Microdia Webcam Vitade AF                           | 4         | 0.94%   |
| Microdia Integrated Webcam                          | 4         | 0.94%   |
| Lite-On HP HD Camera                                | 4         | 0.94%   |
| IMC Networks Integrated Webcam                      | 4         | 0.94%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 4         | 0.94%   |
| Chicony USB 2.0 Camera                              | 4         | 0.94%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.94%   |
| Chicony HD User Facing                              | 4         | 0.94%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.71%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.71%   |
| Chicony USB2.0 0.3M UVC WebCam                      | 3         | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 0.71%   |
| Chicony Thinkpad T430 camera                        | 3         | 0.71%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.71%   |
| Chicony HP TrueVision HD Camera                     | 3         | 0.71%   |
| Chicony HP HD Camera                                | 3         | 0.71%   |
| Chicony CNF9055 Toshiba Webcam                      | 3         | 0.71%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 3         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.71%   |
| Bison Lenovo EasyCamera                             | 3         | 0.71%   |
| Bison EasyCamera                                    | 3         | 0.71%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 41.41%  |
| Synaptics                  | 30        | 30.3%   |
| Shenzhen Goodix Technology | 8         | 8.08%   |
| AuthenTec                  | 8         | 8.08%   |
| LighTuning Technology      | 4         | 4.04%   |
| Upek                       | 3         | 3.03%   |
| STMicroelectronics         | 3         | 3.03%   |
| Elan Microelectronics      | 2         | 2.02%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 10.1%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 8.08%   |
| Validity Sensors VFS491                                                    | 6         | 6.06%   |
| Synaptics WBDI                                                             | 6         | 6.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 5.05%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.04%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 4.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 4.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 4.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.03%   |
| Synaptics  WBDI                                                            | 3         | 3.03%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.03%   |
| AuthenTec AES2810                                                          | 3         | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.02%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.02%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.02%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.02%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.01%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.01%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.01%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.01%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 1.01%   |
| Synaptics UWP WBDI                                                         | 1         | 1.01%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.01%   |
| AuthenTec AES1600                                                          | 1         | 1.01%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 17        | 37.78%  |
| Alcor Micro           | 15        | 33.33%  |
| O2 Micro              | 5         | 11.11%  |
| BIT4ID                | 3         | 6.67%   |
| Lenovo                | 2         | 4.44%   |
| Gemalto (was Gemplus) | 2         | 4.44%   |
| OmniKey               | 1         | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.33%  |
| Broadcom 5880                                                                | 6         | 13.33%  |
| Broadcom 58200                                                               | 4         | 8.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.67%   |
| BIT4ID miniLector EVO                                                        | 3         | 6.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.44%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.44%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 4.44%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 2.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 516       | 66.58%  |
| 1     | 212       | 27.35%  |
| 2     | 38        | 4.9%    |
| 3     | 7         | 0.9%    |
| 4     | 2         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 99        | 32.67%  |
| Graphics card            | 71        | 23.43%  |
| Chipcard                 | 36        | 11.88%  |
| Net/wireless             | 23        | 7.59%   |
| Multimedia controller    | 14        | 4.62%   |
| Bluetooth                | 13        | 4.29%   |
| Communication controller | 9         | 2.97%   |
| Storage                  | 8         | 2.64%   |
| Modem                    | 6         | 1.98%   |
| Card reader              | 6         | 1.98%   |
| Camera                   | 5         | 1.65%   |
| Sound                    | 4         | 1.32%   |
| Network                  | 3         | 0.99%   |
| Unassigned class         | 2         | 0.66%   |
| Flash memory             | 2         | 0.66%   |
| Storage/ide              | 1         | 0.33%   |
| Net/ethernet             | 1         | 0.33%   |

