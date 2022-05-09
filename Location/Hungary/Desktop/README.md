Linux in Hungary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 3768

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | X79 V2.72B                  | [87dd767f71](https://linux-hardware.org/?probe=87dd767f71) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| ASUSTek       | PRIME B365M-A               | [8214f55ca5](https://linux-hardware.org/?probe=8214f55ca5) | May 03, 2022 |
| ASUSTek       | PRIME B365M-A               | [f9e7349f8b](https://linux-hardware.org/?probe=f9e7349f8b) | May 03, 2022 |
| ASUSTek       | PRIME B365M-A               | [e723525ebd](https://linux-hardware.org/?probe=e723525ebd) | May 02, 2022 |
| HP            | 1850                        | [1a2271c939](https://linux-hardware.org/?probe=1a2271c939) | May 01, 2022 |
| ASUSTek       | PRIME B365M-A               | [f55f993229](https://linux-hardware.org/?probe=f55f993229) | May 01, 2022 |
| Dell          | 0TY915                      | [7de07e1186](https://linux-hardware.org/?probe=7de07e1186) | May 01, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [bb192229b3](https://linux-hardware.org/?probe=bb192229b3) | Apr 30, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [a5ce52429c](https://linux-hardware.org/?probe=a5ce52429c) | Apr 30, 2022 |
| Dell          | 0TY915                      | [ef4cf49069](https://linux-hardware.org/?probe=ef4cf49069) | Apr 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [af2b0de49b](https://linux-hardware.org/?probe=af2b0de49b) | Apr 29, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASUSTek       | B85M-E                      | [05896f4d55](https://linux-hardware.org/?probe=05896f4d55) | Apr 27, 2022 |
| ASUSTek       | B85M-E                      | [c4ccc166be](https://linux-hardware.org/?probe=c4ccc166be) | Apr 27, 2022 |
| ASRock        | FM2A75M Pro4+               | [0fc510a45a](https://linux-hardware.org/?probe=0fc510a45a) | Apr 26, 2022 |
| ASRock        | FM2A75M Pro4+               | [e8cef8d7a9](https://linux-hardware.org/?probe=e8cef8d7a9) | Apr 26, 2022 |
| ASRock        | FM2A75M Pro4+               | [2ccbcae022](https://linux-hardware.org/?probe=2ccbcae022) | Apr 23, 2022 |
| ASRock        | FM2A75M Pro4+               | [ec77795911](https://linux-hardware.org/?probe=ec77795911) | Apr 23, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| HP            | 339A                        | [229032eb98](https://linux-hardware.org/?probe=229032eb98) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | [d624a31b69](https://linux-hardware.org/?probe=d624a31b69) | Apr 18, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [44e20e1af0](https://linux-hardware.org/?probe=44e20e1af0) | Apr 17, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [1959eab901](https://linux-hardware.org/?probe=1959eab901) | Apr 16, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [0a7ccf21d6](https://linux-hardware.org/?probe=0a7ccf21d6) | Apr 16, 2022 |
| ASRock        | ConRoe1333-D667             | [d2bba273a0](https://linux-hardware.org/?probe=d2bba273a0) | Apr 15, 2022 |
| ASRock        | ConRoe1333-D667             | [24ba95b6ea](https://linux-hardware.org/?probe=24ba95b6ea) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| ASUSTek       | M4A78 PRO                   | [9ed3f59682](https://linux-hardware.org/?probe=9ed3f59682) | Apr 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [5e30e0e56d](https://linux-hardware.org/?probe=5e30e0e56d) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [67175f0019](https://linux-hardware.org/?probe=67175f0019) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [a6d685f9c7](https://linux-hardware.org/?probe=a6d685f9c7) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [c11ab04912](https://linux-hardware.org/?probe=c11ab04912) | Apr 12, 2022 |
| Dell          | 055H3G A01                  | [a41b7fbf00](https://linux-hardware.org/?probe=a41b7fbf00) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3d91f855bc](https://linux-hardware.org/?probe=3d91f855bc) | Apr 09, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [b48b65867f](https://linux-hardware.org/?probe=b48b65867f) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [6130d7e1e6](https://linux-hardware.org/?probe=6130d7e1e6) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [cb4cca0ed4](https://linux-hardware.org/?probe=cb4cca0ed4) | Apr 09, 2022 |
| Gigabyte      | G41MT-S2PT                  | [7dde5fefd1](https://linux-hardware.org/?probe=7dde5fefd1) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0840dd295](https://linux-hardware.org/?probe=b0840dd295) | Apr 09, 2022 |
| ASUSTek       | B85M-G                      | [c58e24cff5](https://linux-hardware.org/?probe=c58e24cff5) | Apr 07, 2022 |
| Gigabyte      | G41MT-S2PT                  | [d0a71a4c13](https://linux-hardware.org/?probe=d0a71a4c13) | Apr 06, 2022 |
| Gigabyte      | G41MT-S2PT                  | [17f2b9f011](https://linux-hardware.org/?probe=17f2b9f011) | Apr 06, 2022 |
| Gigabyte      | H87M-HD3                    | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Gigabyte      | G41MT-S2PT                  | [1a54aa07e3](https://linux-hardware.org/?probe=1a54aa07e3) | Apr 04, 2022 |
| ASRock        | B85M                        | [5e03e9532d](https://linux-hardware.org/?probe=5e03e9532d) | Apr 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | [9d1398934f](https://linux-hardware.org/?probe=9d1398934f) | Apr 04, 2022 |
| Gigabyte      | H61M-DS2                    | [10ccb633ee](https://linux-hardware.org/?probe=10ccb633ee) | Apr 04, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [66db4f71eb](https://linux-hardware.org/?probe=66db4f71eb) | Apr 01, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [66fd90660b](https://linux-hardware.org/?probe=66fd90660b) | Apr 01, 2022 |
| ASRock        | B75 Pro3                    | [01c8b92976](https://linux-hardware.org/?probe=01c8b92976) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [c338f4ffd4](https://linux-hardware.org/?probe=c338f4ffd4) | Mar 31, 2022 |
| HP            | 18E7                        | [4503b657fe](https://linux-hardware.org/?probe=4503b657fe) | Mar 30, 2022 |
| Gigabyte      | B450M GAMING                | [6cff18109b](https://linux-hardware.org/?probe=6cff18109b) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | [b650c90413](https://linux-hardware.org/?probe=b650c90413) | Mar 28, 2022 |
| ASUSTek       | AM1M-A                      | [2f7bece339](https://linux-hardware.org/?probe=2f7bece339) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5d62943116](https://linux-hardware.org/?probe=5d62943116) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [68bf78ae9d](https://linux-hardware.org/?probe=68bf78ae9d) | Mar 27, 2022 |
| Lenovo        | ThinkServer TS440           | [a356a33d0a](https://linux-hardware.org/?probe=a356a33d0a) | Mar 27, 2022 |
| Gigabyte      | H61M-D2-B3                  | [e807733708](https://linux-hardware.org/?probe=e807733708) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | [59df12dc12](https://linux-hardware.org/?probe=59df12dc12) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [7e1b536f6b](https://linux-hardware.org/?probe=7e1b536f6b) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [fd041828d0](https://linux-hardware.org/?probe=fd041828d0) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d2e30b1d8b](https://linux-hardware.org/?probe=d2e30b1d8b) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [72e8662f26](https://linux-hardware.org/?probe=72e8662f26) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2c7a4a9552](https://linux-hardware.org/?probe=2c7a4a9552) | Mar 22, 2022 |
| ASRock        | FM2A75 Pro4+                | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| ASUSTek       | P5B                         | [0ec5966c98](https://linux-hardware.org/?probe=0ec5966c98) | Mar 21, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3bd6a87950](https://linux-hardware.org/?probe=3bd6a87950) | Mar 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [399ab158b9](https://linux-hardware.org/?probe=399ab158b9) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [661d9fcffa](https://linux-hardware.org/?probe=661d9fcffa) | Mar 18, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [46af9af40c](https://linux-hardware.org/?probe=46af9af40c) | Mar 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [1b697ade27](https://linux-hardware.org/?probe=1b697ade27) | Mar 17, 2022 |
| ASUSTek       | Rampage III Extreme         | [6533ff3270](https://linux-hardware.org/?probe=6533ff3270) | Mar 16, 2022 |
| ASUSTek       | Rampage III Extreme         | [1e13431147](https://linux-hardware.org/?probe=1e13431147) | Mar 16, 2022 |
| HP            | 1589                        | [41622b6b2d](https://linux-hardware.org/?probe=41622b6b2d) | Mar 14, 2022 |
| HP            | 1589                        | [95af16db2e](https://linux-hardware.org/?probe=95af16db2e) | Mar 13, 2022 |
| Dell          | 0GM819                      | [e06d400f29](https://linux-hardware.org/?probe=e06d400f29) | Mar 13, 2022 |
| Dell          | 0GM819                      | [252abde91b](https://linux-hardware.org/?probe=252abde91b) | Mar 13, 2022 |
| ASRock        | FM2A75M Pro4+               | [912b670e0f](https://linux-hardware.org/?probe=912b670e0f) | Mar 12, 2022 |
| ASRock        | FM2A75M Pro4+               | [64f83fa328](https://linux-hardware.org/?probe=64f83fa328) | Mar 12, 2022 |
| Acer          | Veriton M4610G              | [ec980460ed](https://linux-hardware.org/?probe=ec980460ed) | Mar 12, 2022 |
| Lenovo        | ThinkServer TS440           | [ec0e6e5114](https://linux-hardware.org/?probe=ec0e6e5114) | Mar 11, 2022 |
| Gigabyte      | B450M GAMING                | [69364aac12](https://linux-hardware.org/?probe=69364aac12) | Mar 09, 2022 |
| Gigabyte      | B450M GAMING                | [f53002a620](https://linux-hardware.org/?probe=f53002a620) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | [71e8b113b4](https://linux-hardware.org/?probe=71e8b113b4) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | [0148e15f51](https://linux-hardware.org/?probe=0148e15f51) | Mar 09, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [5b31db42d4](https://linux-hardware.org/?probe=5b31db42d4) | Mar 08, 2022 |
| HP            | 1589                        | [eceb34c7fa](https://linux-hardware.org/?probe=eceb34c7fa) | Mar 08, 2022 |
| Lenovo        | Dory CRB                    | [e8cfaeca24](https://linux-hardware.org/?probe=e8cfaeca24) | Mar 08, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [8dcdbb2b22](https://linux-hardware.org/?probe=8dcdbb2b22) | Mar 07, 2022 |
| ASUSTek       | PRIME B365M-A               | [1400ed0b8d](https://linux-hardware.org/?probe=1400ed0b8d) | Mar 07, 2022 |
| ASUSTek       | PRIME B365M-A               | [0d6e2bca43](https://linux-hardware.org/?probe=0d6e2bca43) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [378234e501](https://linux-hardware.org/?probe=378234e501) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [110256cccd](https://linux-hardware.org/?probe=110256cccd) | Mar 07, 2022 |
| Gigabyte      | B450M GAMING                | [bab5789d49](https://linux-hardware.org/?probe=bab5789d49) | Mar 06, 2022 |
| Lenovo        | Dory CRB                    | [7f2b3fffd8](https://linux-hardware.org/?probe=7f2b3fffd8) | Mar 05, 2022 |
| Lenovo        | Dory CRB                    | [36400000a9](https://linux-hardware.org/?probe=36400000a9) | Mar 05, 2022 |
| Gigabyte      | G41MT-S2PT                  | [ff8d475418](https://linux-hardware.org/?probe=ff8d475418) | Mar 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | [41a0c8cabb](https://linux-hardware.org/?probe=41a0c8cabb) | Mar 04, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [3cb51f5689](https://linux-hardware.org/?probe=3cb51f5689) | Mar 04, 2022 |
| Gigabyte      | B450M S2H V2                | [000ae29fb1](https://linux-hardware.org/?probe=000ae29fb1) | Mar 03, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3d54b5db38](https://linux-hardware.org/?probe=3d54b5db38) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| Gigabyte      | H61M-D2-B3                  | [ad003c1394](https://linux-hardware.org/?probe=ad003c1394) | Mar 02, 2022 |
| Gigabyte      | H61M-D2-B3                  | [8225572009](https://linux-hardware.org/?probe=8225572009) | Mar 02, 2022 |
| ASRock        | B450M Pro4                  | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| HP            | 339A                        | [59d197fac4](https://linux-hardware.org/?probe=59d197fac4) | Mar 01, 2022 |
| HP            | 339A                        | [6695de0556](https://linux-hardware.org/?probe=6695de0556) | Mar 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a94729eaf7](https://linux-hardware.org/?probe=a94729eaf7) | Mar 01, 2022 |
| ASUSTek       | B75M-PLUS                   | [e479ffd9d5](https://linux-hardware.org/?probe=e479ffd9d5) | Feb 27, 2022 |
| ASUSTek       | B75M-PLUS                   | [96e4cf1606](https://linux-hardware.org/?probe=96e4cf1606) | Feb 27, 2022 |
| ASUSTek       | P5QC                        | [8d2d104db6](https://linux-hardware.org/?probe=8d2d104db6) | Feb 26, 2022 |
| HP            | 3396                        | [c9cce866c4](https://linux-hardware.org/?probe=c9cce866c4) | Feb 25, 2022 |
| Gigabyte      | B450M H                     | [fbed153592](https://linux-hardware.org/?probe=fbed153592) | Feb 25, 2022 |
| Gigabyte      | MCMLUCB-00                  | [d2bce2bda0](https://linux-hardware.org/?probe=d2bce2bda0) | Feb 25, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [e1284695f2](https://linux-hardware.org/?probe=e1284695f2) | Feb 24, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [c7c60ad7ac](https://linux-hardware.org/?probe=c7c60ad7ac) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [4b90c1398d](https://linux-hardware.org/?probe=4b90c1398d) | Feb 23, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e1a5782fbe](https://linux-hardware.org/?probe=e1a5782fbe) | Feb 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0b42d37bf1](https://linux-hardware.org/?probe=0b42d37bf1) | Feb 22, 2022 |
| Gigabyte      | B450M GAMING                | [fe810701b4](https://linux-hardware.org/?probe=fe810701b4) | Feb 22, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [ee84460851](https://linux-hardware.org/?probe=ee84460851) | Feb 20, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [158e5bd3bb](https://linux-hardware.org/?probe=158e5bd3bb) | Feb 20, 2022 |
| Gigabyte      | H61M-S2PV                   | [f5b8bcccb2](https://linux-hardware.org/?probe=f5b8bcccb2) | Feb 19, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1ddb502787](https://linux-hardware.org/?probe=1ddb502787) | Feb 19, 2022 |
| ASRock        | 970 Pro3 R2.0               | [fde5d3aa86](https://linux-hardware.org/?probe=fde5d3aa86) | Feb 19, 2022 |
| Gigabyte      | B450M GAMING                | [b629210922](https://linux-hardware.org/?probe=b629210922) | Feb 19, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7ecf132718](https://linux-hardware.org/?probe=7ecf132718) | Feb 19, 2022 |
| Gigabyte      | Z68MX-UD2H-B3               | [4ee5a962df](https://linux-hardware.org/?probe=4ee5a962df) | Feb 18, 2022 |
| Gigabyte      | B85M-D3H                    | [7b5e16621e](https://linux-hardware.org/?probe=7b5e16621e) | Feb 18, 2022 |
| Gigabyte      | B85M-D3H                    | [85a5aca2eb](https://linux-hardware.org/?probe=85a5aca2eb) | Feb 18, 2022 |
| Medion        | MS-7748                     | [0f9283e5e9](https://linux-hardware.org/?probe=0f9283e5e9) | Feb 17, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [8b373bbfec](https://linux-hardware.org/?probe=8b373bbfec) | Feb 17, 2022 |
| Medion        | MS-7748                     | [72e17bd510](https://linux-hardware.org/?probe=72e17bd510) | Feb 17, 2022 |
| HP            | 2820h                       | [ecf8b8bc60](https://linux-hardware.org/?probe=ecf8b8bc60) | Feb 17, 2022 |
| HP            | 2820h                       | [89f7abcbf4](https://linux-hardware.org/?probe=89f7abcbf4) | Feb 17, 2022 |
| Medion        | MS-7748                     | [7459c164c1](https://linux-hardware.org/?probe=7459c164c1) | Feb 16, 2022 |
| MSI           | B85M-P32                    | [e0a962d224](https://linux-hardware.org/?probe=e0a962d224) | Feb 15, 2022 |
| MSI           | B85M-P32                    | [35c370815c](https://linux-hardware.org/?probe=35c370815c) | Feb 15, 2022 |
| ASRock        | B550M Pro4                  | [5897907111](https://linux-hardware.org/?probe=5897907111) | Feb 15, 2022 |
| ASUSTek       | Crosshair IV Formula        | [f33f7c184e](https://linux-hardware.org/?probe=f33f7c184e) | Feb 14, 2022 |
| MSI           | H61M-P20                    | [63dbb68d31](https://linux-hardware.org/?probe=63dbb68d31) | Feb 14, 2022 |
| ASUSTek       | Crosshair IV Formula        | [e86ee5018c](https://linux-hardware.org/?probe=e86ee5018c) | Feb 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3d320cc4d6](https://linux-hardware.org/?probe=3d320cc4d6) | Feb 13, 2022 |
| MSI           | H61M-P20                    | [d0996e1c65](https://linux-hardware.org/?probe=d0996e1c65) | Feb 13, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [7968062d45](https://linux-hardware.org/?probe=7968062d45) | Feb 13, 2022 |
| Intel         | DG45ID AAE27729-308         | [91f90c2997](https://linux-hardware.org/?probe=91f90c2997) | Feb 12, 2022 |
| ASRock        | B550M Pro4                  | [18b9c160a9](https://linux-hardware.org/?probe=18b9c160a9) | Feb 12, 2022 |
| Gigabyte      | AB350M-D3H-CF               | [406bd79f86](https://linux-hardware.org/?probe=406bd79f86) | Feb 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [4a05dcdd20](https://linux-hardware.org/?probe=4a05dcdd20) | Feb 11, 2022 |
| ASUSTek       | Crosshair IV Formula        | [18f47c9736](https://linux-hardware.org/?probe=18f47c9736) | Feb 10, 2022 |
| ASUSTek       | Crosshair IV Formula        | [2957e7ab9b](https://linux-hardware.org/?probe=2957e7ab9b) | Feb 10, 2022 |
| MSI           | MS-7253                     | [c6d4e8933e](https://linux-hardware.org/?probe=c6d4e8933e) | Feb 10, 2022 |
| MSI           | MS-7253                     | [ee60e146a7](https://linux-hardware.org/?probe=ee60e146a7) | Feb 10, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [b56694aaf5](https://linux-hardware.org/?probe=b56694aaf5) | Feb 09, 2022 |
| Gigabyte      | H310M H x.x                 | [1ca3e5ad44](https://linux-hardware.org/?probe=1ca3e5ad44) | Feb 08, 2022 |
| Dell          | 0GM819                      | [473d90da33](https://linux-hardware.org/?probe=473d90da33) | Feb 08, 2022 |
| Gigabyte      | H110M-S2V-CF                | [f424a1b3be](https://linux-hardware.org/?probe=f424a1b3be) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [a76a47a11f](https://linux-hardware.org/?probe=a76a47a11f) | Feb 07, 2022 |
| HP            | 0A64h                       | [98ed15aae2](https://linux-hardware.org/?probe=98ed15aae2) | Feb 07, 2022 |
| HP            | 0A64h                       | [668921361e](https://linux-hardware.org/?probe=668921361e) | Feb 07, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [071fcc6209](https://linux-hardware.org/?probe=071fcc6209) | Feb 07, 2022 |
| HP            | 805D                        | [c60a6bdbbe](https://linux-hardware.org/?probe=c60a6bdbbe) | Feb 07, 2022 |
| HP            | 805D                        | [c744f9c342](https://linux-hardware.org/?probe=c744f9c342) | Feb 07, 2022 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [43f1fc6098](https://linux-hardware.org/?probe=43f1fc6098) | Feb 06, 2022 |
| HP            | 843C                        | [65121c676e](https://linux-hardware.org/?probe=65121c676e) | Feb 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [e2b08e55fa](https://linux-hardware.org/?probe=e2b08e55fa) | Feb 06, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [f45c4ae60c](https://linux-hardware.org/?probe=f45c4ae60c) | Feb 05, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [da100d08f5](https://linux-hardware.org/?probe=da100d08f5) | Feb 05, 2022 |
| ASRock        | G31M-S                      | [2b4d2d640f](https://linux-hardware.org/?probe=2b4d2d640f) | Feb 05, 2022 |
| Gigabyte      | H81M-S                      | [2f6399fd27](https://linux-hardware.org/?probe=2f6399fd27) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Unknown       | Unknown                     | [f9a64bf682](https://linux-hardware.org/?probe=f9a64bf682) | Feb 04, 2022 |
| HP            | 805D                        | [a1c655471b](https://linux-hardware.org/?probe=a1c655471b) | Feb 04, 2022 |
| HP            | 805D                        | [1d5437358e](https://linux-hardware.org/?probe=1d5437358e) | Feb 04, 2022 |
| Unknown       | Unknown                     | [e4e8e488a2](https://linux-hardware.org/?probe=e4e8e488a2) | Feb 04, 2022 |
| HP            | 2820h                       | [29ca2cd67e](https://linux-hardware.org/?probe=29ca2cd67e) | Feb 04, 2022 |
| HP            | 2820h                       | [81782756a3](https://linux-hardware.org/?probe=81782756a3) | Feb 04, 2022 |
| ASUSTek       | VM40B                       | [81ae77ad68](https://linux-hardware.org/?probe=81ae77ad68) | Feb 03, 2022 |
| ASUSTek       | VM40B                       | [3f29251c4f](https://linux-hardware.org/?probe=3f29251c4f) | Feb 03, 2022 |
| Gigabyte      | H81M-S                      | [fcfbc53f05](https://linux-hardware.org/?probe=fcfbc53f05) | Feb 03, 2022 |
| Gigabyte      | P67A-D3-B3                  | [e490dd8875](https://linux-hardware.org/?probe=e490dd8875) | Feb 02, 2022 |
| Gigabyte      | P67A-D3-B3                  | [4cafc7be87](https://linux-hardware.org/?probe=4cafc7be87) | Feb 02, 2022 |
| ASUSTek       | AM1M-A                      | [7967848128](https://linux-hardware.org/?probe=7967848128) | Feb 01, 2022 |
| Lenovo        | NOK                         | [fbc8b16f78](https://linux-hardware.org/?probe=fbc8b16f78) | Feb 01, 2022 |
| ASUSTek       | AM1M-A                      | [d0714efedc](https://linux-hardware.org/?probe=d0714efedc) | Feb 01, 2022 |
| Gigabyte      | B450M GAMING                | [992ff16705](https://linux-hardware.org/?probe=992ff16705) | Jan 31, 2022 |
| Gigabyte      | B450M GAMING                | [6937ccfd65](https://linux-hardware.org/?probe=6937ccfd65) | Jan 31, 2022 |
| ASRock        | H170M Pro4S                 | [efb4e3254e](https://linux-hardware.org/?probe=efb4e3254e) | Jan 31, 2022 |
| HP            | 18E7                        | [fb9b13b49b](https://linux-hardware.org/?probe=fb9b13b49b) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fc9ddc34b0](https://linux-hardware.org/?probe=fc9ddc34b0) | Jan 30, 2022 |
| Gigabyte      | P35-S3G                     | [21f5490cc5](https://linux-hardware.org/?probe=21f5490cc5) | Jan 30, 2022 |
| Gigabyte      | B150M-D3H-CF                | [ab6c348741](https://linux-hardware.org/?probe=ab6c348741) | Jan 30, 2022 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [88218319a7](https://linux-hardware.org/?probe=88218319a7) | Jan 30, 2022 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [1ddd377c2c](https://linux-hardware.org/?probe=1ddd377c2c) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [c2ae5ac235](https://linux-hardware.org/?probe=c2ae5ac235) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2ef8833ffb](https://linux-hardware.org/?probe=2ef8833ffb) | Jan 30, 2022 |
| Lenovo        | Dory CRB                    | [6c48175227](https://linux-hardware.org/?probe=6c48175227) | Jan 30, 2022 |
| Gigabyte      | H61M-D2-B3                  | [19f3d984b0](https://linux-hardware.org/?probe=19f3d984b0) | Jan 30, 2022 |
| Lenovo        | Dory CRB                    | [068f1c2225](https://linux-hardware.org/?probe=068f1c2225) | Jan 30, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [c5e9f1b68c](https://linux-hardware.org/?probe=c5e9f1b68c) | Jan 29, 2022 |
| Lenovo        | ThinkServer TS440           | [eaef3cbdab](https://linux-hardware.org/?probe=eaef3cbdab) | Jan 29, 2022 |
| Gigabyte      | B450M GAMING                | [cb3cf28ad7](https://linux-hardware.org/?probe=cb3cf28ad7) | Jan 27, 2022 |
| Gigabyte      | B450M GAMING                | [44fce2ca83](https://linux-hardware.org/?probe=44fce2ca83) | Jan 27, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| Dell          | 02YYK5 A00                  | [af828f5f84](https://linux-hardware.org/?probe=af828f5f84) | Jan 26, 2022 |
| MSI           | B85M-P32                    | [19c56cc4fc](https://linux-hardware.org/?probe=19c56cc4fc) | Jan 26, 2022 |
| ASRock        | H170M Pro4S                 | [0c900f67d0](https://linux-hardware.org/?probe=0c900f67d0) | Jan 26, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [781a92f9a4](https://linux-hardware.org/?probe=781a92f9a4) | Jan 26, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [205214c3d2](https://linux-hardware.org/?probe=205214c3d2) | Jan 26, 2022 |
| Dell          | 02YYK5 A00                  | [d357a59431](https://linux-hardware.org/?probe=d357a59431) | Jan 26, 2022 |
| MSI           | B85M-P32                    | [80f9f5c800](https://linux-hardware.org/?probe=80f9f5c800) | Jan 25, 2022 |
| Unknown       | Unknown                     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| Medion        | MS-7748                     | [8ca8cf015e](https://linux-hardware.org/?probe=8ca8cf015e) | Jan 24, 2022 |
| Medion        | MS-7748                     | [859e4baa04](https://linux-hardware.org/?probe=859e4baa04) | Jan 24, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [b1cfd38100](https://linux-hardware.org/?probe=b1cfd38100) | Jan 23, 2022 |
| ASUSTek       | P8B75-M LX                  | [dc2c32aac2](https://linux-hardware.org/?probe=dc2c32aac2) | Jan 23, 2022 |
| ASUSTek       | VM40B                       | [35ab4cf978](https://linux-hardware.org/?probe=35ab4cf978) | Jan 22, 2022 |
| MSI           | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| Lenovo        | ThinkServer TS440           | [b736a56c19](https://linux-hardware.org/?probe=b736a56c19) | Jan 21, 2022 |
| Lenovo        | ThinkServer TS440           | [1f5146de0a](https://linux-hardware.org/?probe=1f5146de0a) | Jan 21, 2022 |
| HP            | 3647h                       | [8c83ed4e1a](https://linux-hardware.org/?probe=8c83ed4e1a) | Jan 21, 2022 |
| ASUSTek       | VM40B                       | [64aa40b399](https://linux-hardware.org/?probe=64aa40b399) | Jan 21, 2022 |
| Gigabyte      | P35-S3G                     | [64049e547a](https://linux-hardware.org/?probe=64049e547a) | Jan 21, 2022 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [918378014c](https://linux-hardware.org/?probe=918378014c) | Jan 21, 2022 |
| Gigabyte      | B450M GAMING                | [651a2a77cd](https://linux-hardware.org/?probe=651a2a77cd) | Jan 20, 2022 |
| Gigabyte      | B450M GAMING                | [7bb4428003](https://linux-hardware.org/?probe=7bb4428003) | Jan 20, 2022 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [d258269f4e](https://linux-hardware.org/?probe=d258269f4e) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| HP            | 3647h                       | [b393fe2f3a](https://linux-hardware.org/?probe=b393fe2f3a) | Jan 19, 2022 |
| HP            | 3029h                       | [21048ac4b2](https://linux-hardware.org/?probe=21048ac4b2) | Jan 19, 2022 |
| Medion        | MS-7748                     | [9909705c2a](https://linux-hardware.org/?probe=9909705c2a) | Jan 18, 2022 |
| Gigabyte      | H61M-S2PV                   | [330f414282](https://linux-hardware.org/?probe=330f414282) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | [a28c50c71f](https://linux-hardware.org/?probe=a28c50c71f) | Jan 17, 2022 |
| Lenovo        | Dory CRB                    | [e58b3748b5](https://linux-hardware.org/?probe=e58b3748b5) | Jan 17, 2022 |
| Lenovo        | Dory CRB                    | [cb5e5f4ca1](https://linux-hardware.org/?probe=cb5e5f4ca1) | Jan 16, 2022 |
| MSI           | 890GXM-G65                  | [62c8eab51c](https://linux-hardware.org/?probe=62c8eab51c) | Jan 16, 2022 |
| MSI           | X570-A PRO                  | [acd5f363d7](https://linux-hardware.org/?probe=acd5f363d7) | Jan 16, 2022 |
| MSI           | 890GXM-G65                  | [e59fd1ba13](https://linux-hardware.org/?probe=e59fd1ba13) | Jan 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [fe9b500730](https://linux-hardware.org/?probe=fe9b500730) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [a3711dfcf9](https://linux-hardware.org/?probe=a3711dfcf9) | Jan 15, 2022 |
| Gigabyte      | G41MT-S2PT                  | [e9a758a742](https://linux-hardware.org/?probe=e9a758a742) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [c973a9bc0d](https://linux-hardware.org/?probe=c973a9bc0d) | Jan 15, 2022 |
| Lenovo        | ThinkServer TS440           | [bae7c1cd50](https://linux-hardware.org/?probe=bae7c1cd50) | Jan 15, 2022 |
| Gigabyte      | G41MT-S2PT                  | [de5494084f](https://linux-hardware.org/?probe=de5494084f) | Jan 14, 2022 |
| Gigabyte      | G41MT-S2PT                  | [e78a40c6c9](https://linux-hardware.org/?probe=e78a40c6c9) | Jan 14, 2022 |
| ASRock        | G31M-VS                     | [016c34dc7a](https://linux-hardware.org/?probe=016c34dc7a) | Jan 13, 2022 |
| ASRock        | G31M-VS                     | [c9d6ddaddc](https://linux-hardware.org/?probe=c9d6ddaddc) | Jan 13, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| Medion        | MS-7748                     | [a5a11345ba](https://linux-hardware.org/?probe=a5a11345ba) | Jan 12, 2022 |
| ASRock        | G41M-VS3                    | [8709398c0f](https://linux-hardware.org/?probe=8709398c0f) | Jan 11, 2022 |
| ASRock        | G41M-VS3                    | [9915e534b9](https://linux-hardware.org/?probe=9915e534b9) | Jan 11, 2022 |
| ASRock        | G31M-VS                     | [60f1b2fe4e](https://linux-hardware.org/?probe=60f1b2fe4e) | Jan 11, 2022 |
| ASRock        | G31M-VS                     | [cbf7421335](https://linux-hardware.org/?probe=cbf7421335) | Jan 11, 2022 |
| Medion        | MS-7646                     | [9bc224fcf4](https://linux-hardware.org/?probe=9bc224fcf4) | Jan 10, 2022 |
| Medion        | MS-7646                     | [95646f2380](https://linux-hardware.org/?probe=95646f2380) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c2c5bfd879](https://linux-hardware.org/?probe=c2c5bfd879) | Jan 10, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [d3117e8b94](https://linux-hardware.org/?probe=d3117e8b94) | Jan 10, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [2a515d8620](https://linux-hardware.org/?probe=2a515d8620) | Jan 10, 2022 |
| ASRock        | B550M Pro4                  | [3081352cdd](https://linux-hardware.org/?probe=3081352cdd) | Jan 10, 2022 |
| ASRock        | B550M Pro4                  | [f9848222b6](https://linux-hardware.org/?probe=f9848222b6) | Jan 10, 2022 |
| Gigabyte      | B450M GAMING                | [a3caf6b1cc](https://linux-hardware.org/?probe=a3caf6b1cc) | Jan 09, 2022 |
| Gigabyte      | B450M GAMING                | [301d2eefee](https://linux-hardware.org/?probe=301d2eefee) | Jan 09, 2022 |
| ASUSTek       | PRIME B460M-A               | [34fad0ad77](https://linux-hardware.org/?probe=34fad0ad77) | Jan 09, 2022 |
| ASRock        | B450 Pro4                   | [56ebb4b643](https://linux-hardware.org/?probe=56ebb4b643) | Jan 09, 2022 |
| ASUSTek       | Crosshair IV Formula        | [2a704b5f0c](https://linux-hardware.org/?probe=2a704b5f0c) | Jan 07, 2022 |
| ASUSTek       | Crosshair IV Formula        | [56cd684b9a](https://linux-hardware.org/?probe=56cd684b9a) | Jan 07, 2022 |
| Unknown       | NF-MCP78                    | [b1cca5c515](https://linux-hardware.org/?probe=b1cca5c515) | Jan 06, 2022 |
| Gigabyte      | H81M-S                      | [8d1726befc](https://linux-hardware.org/?probe=8d1726befc) | Jan 06, 2022 |
| Gigabyte      | H81M-S                      | [2b09721dea](https://linux-hardware.org/?probe=2b09721dea) | Jan 06, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [4af527ae61](https://linux-hardware.org/?probe=4af527ae61) | Jan 05, 2022 |
| Lenovo        | Dory CRB                    | [aec293344d](https://linux-hardware.org/?probe=aec293344d) | Jan 05, 2022 |
| Gigabyte      | B450M GAMING                | [87efa65bb9](https://linux-hardware.org/?probe=87efa65bb9) | Jan 04, 2022 |
| Gigabyte      | B450M GAMING                | [0c8a502a11](https://linux-hardware.org/?probe=0c8a502a11) | Jan 04, 2022 |
| Intel         | HURONRIVER                  | [85b441d7cb](https://linux-hardware.org/?probe=85b441d7cb) | Jan 04, 2022 |
| Lenovo        | Dory CRB                    | [7bb3586aed](https://linux-hardware.org/?probe=7bb3586aed) | Jan 04, 2022 |
| Lenovo        | Dory CRB                    | [ba5b413a3b](https://linux-hardware.org/?probe=ba5b413a3b) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | [6ef9b69e18](https://linux-hardware.org/?probe=6ef9b69e18) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | [c2d49cd216](https://linux-hardware.org/?probe=c2d49cd216) | Jan 04, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [50551cf5c6](https://linux-hardware.org/?probe=50551cf5c6) | Jan 03, 2022 |
| Gigabyte      | H310M H x.x                 | [45f7689f8d](https://linux-hardware.org/?probe=45f7689f8d) | Jan 03, 2022 |
| Gigabyte      | H310M H x.x                 | [846475d938](https://linux-hardware.org/?probe=846475d938) | Jan 02, 2022 |
| HP            | 2215                        | [e3e3c6590f](https://linux-hardware.org/?probe=e3e3c6590f) | Jan 02, 2022 |
| Acer          | RS880M05                    | [6d398453c9](https://linux-hardware.org/?probe=6d398453c9) | Jan 02, 2022 |
| Gigabyte      | H61M-S2PV                   | [f527f05637](https://linux-hardware.org/?probe=f527f05637) | Jan 02, 2022 |
| HP            | 3029h                       | [94547ef9f8](https://linux-hardware.org/?probe=94547ef9f8) | Jan 01, 2022 |
| MSI           | H61M-P31/W8                 | [4c7df047c4](https://linux-hardware.org/?probe=4c7df047c4) | Jan 01, 2022 |
| Gigabyte      | H87-HD3                     | [f25dd3b960](https://linux-hardware.org/?probe=f25dd3b960) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | [667da7e2b7](https://linux-hardware.org/?probe=667da7e2b7) | Dec 31, 2021 |
| Gigabyte      | H61M-S2PV                   | [b9920140c4](https://linux-hardware.org/?probe=b9920140c4) | Dec 31, 2021 |
| Gigabyte      | B450M GAMING                | [725c5c0359](https://linux-hardware.org/?probe=725c5c0359) | Dec 30, 2021 |
| Gigabyte      | B450M GAMING                | [8c7efedc51](https://linux-hardware.org/?probe=8c7efedc51) | Dec 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | [8d180dcd18](https://linux-hardware.org/?probe=8d180dcd18) | Dec 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | [9c9af63993](https://linux-hardware.org/?probe=9c9af63993) | Dec 30, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [649d41e3f8](https://linux-hardware.org/?probe=649d41e3f8) | Dec 29, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [4d94e6a36c](https://linux-hardware.org/?probe=4d94e6a36c) | Dec 29, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [3b7ee11eda](https://linux-hardware.org/?probe=3b7ee11eda) | Dec 29, 2021 |
| Lenovo        | Dory CRB                    | [b5d2b24d12](https://linux-hardware.org/?probe=b5d2b24d12) | Dec 29, 2021 |
| ASRock        | H170M Pro4S                 | [a84965705f](https://linux-hardware.org/?probe=a84965705f) | Dec 29, 2021 |
| ASRock        | H170M Pro4S                 | [aba35e9f28](https://linux-hardware.org/?probe=aba35e9f28) | Dec 29, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [01bfccb835](https://linux-hardware.org/?probe=01bfccb835) | Dec 29, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [a3af4e5057](https://linux-hardware.org/?probe=a3af4e5057) | Dec 28, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [bae2ef5b28](https://linux-hardware.org/?probe=bae2ef5b28) | Dec 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [51c6d31670](https://linux-hardware.org/?probe=51c6d31670) | Dec 27, 2021 |
| Medion        | MS-7646                     | [ab5dc2c634](https://linux-hardware.org/?probe=ab5dc2c634) | Dec 27, 2021 |
| ASRock        | FM2A75M Pro4+               | [f0ab5056ee](https://linux-hardware.org/?probe=f0ab5056ee) | Dec 27, 2021 |
| Medion        | MS-7646                     | [87887fba71](https://linux-hardware.org/?probe=87887fba71) | Dec 27, 2021 |
| Lenovo        | No DPK                      | [373571fe93](https://linux-hardware.org/?probe=373571fe93) | Dec 27, 2021 |
| Lenovo        | No DPK                      | [393b6187f9](https://linux-hardware.org/?probe=393b6187f9) | Dec 27, 2021 |
| ASRock        | FM2A75M Pro4+               | [6bf81bce62](https://linux-hardware.org/?probe=6bf81bce62) | Dec 27, 2021 |
| ASRock        | FM2A75M Pro4+               | [103437bdab](https://linux-hardware.org/?probe=103437bdab) | Dec 27, 2021 |
| Gigabyte      | H61M-S2PV                   | [c674a99c77](https://linux-hardware.org/?probe=c674a99c77) | Dec 27, 2021 |
| Gigabyte      | Z97-HD3                     | [8768948189](https://linux-hardware.org/?probe=8768948189) | Dec 26, 2021 |
| Gigabyte      | EG41MF-US2H                 | [82d9c23e0a](https://linux-hardware.org/?probe=82d9c23e0a) | Dec 25, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a55ea9de9c](https://linux-hardware.org/?probe=a55ea9de9c) | Dec 25, 2021 |
| Gigabyte      | EG41MF-US2H                 | [2f2c91abc6](https://linux-hardware.org/?probe=2f2c91abc6) | Dec 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [c62bd7f367](https://linux-hardware.org/?probe=c62bd7f367) | Dec 25, 2021 |
| Gigabyte      | G31M-S2L                    | [4c00491c87](https://linux-hardware.org/?probe=4c00491c87) | Dec 25, 2021 |
| Dell          | 0M858N A01                  | [ecc633d588](https://linux-hardware.org/?probe=ecc633d588) | Dec 24, 2021 |
| Dell          | 0M858N A01                  | [cbbd6d5d9c](https://linux-hardware.org/?probe=cbbd6d5d9c) | Dec 24, 2021 |
| Gigabyte      | H61M-D2-B3                  | [90a846a6ad](https://linux-hardware.org/?probe=90a846a6ad) | Dec 24, 2021 |
| Gigabyte      | H61M-D2-B3                  | [8c5ca7053a](https://linux-hardware.org/?probe=8c5ca7053a) | Dec 24, 2021 |
| Dell          | 0M858N A01                  | [3889da20c0](https://linux-hardware.org/?probe=3889da20c0) | Dec 23, 2021 |
| Dell          | 0M858N A01                  | [5f084eff7c](https://linux-hardware.org/?probe=5f084eff7c) | Dec 23, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [db48e82f65](https://linux-hardware.org/?probe=db48e82f65) | Dec 23, 2021 |
| Gigabyte      | H61M-D2-B3                  | [19f6e9f3cb](https://linux-hardware.org/?probe=19f6e9f3cb) | Dec 23, 2021 |
| ASUSTek       | PRIME A320M-K               | [9820c373d7](https://linux-hardware.org/?probe=9820c373d7) | Dec 23, 2021 |
| Gigabyte      | P67A-D3-B3                  | [8d4aef89ae](https://linux-hardware.org/?probe=8d4aef89ae) | Dec 22, 2021 |
| Gigabyte      | B450M GAMING                | [de82af195d](https://linux-hardware.org/?probe=de82af195d) | Dec 22, 2021 |
| Gigabyte      | B450M GAMING                | [f4b1c233ae](https://linux-hardware.org/?probe=f4b1c233ae) | Dec 22, 2021 |
| Gigabyte      | H61M-D2-B3                  | [837643e24a](https://linux-hardware.org/?probe=837643e24a) | Dec 22, 2021 |
| ASUSTek       | PRIME A320M-K               | [c09ffa2786](https://linux-hardware.org/?probe=c09ffa2786) | Dec 22, 2021 |
| Dell          | 0XPDFK A00                  | [5c8f9aee8c](https://linux-hardware.org/?probe=5c8f9aee8c) | Dec 21, 2021 |
| Dell          | 0XPDFK A00                  | [1ed5e7631a](https://linux-hardware.org/?probe=1ed5e7631a) | Dec 21, 2021 |
| Unknown       | NF-MCP78                    | [9c5e9cb548](https://linux-hardware.org/?probe=9c5e9cb548) | Dec 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [e6d6c1a347](https://linux-hardware.org/?probe=e6d6c1a347) | Dec 21, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [02ccd7fb7d](https://linux-hardware.org/?probe=02ccd7fb7d) | Dec 21, 2021 |
| ASRock        | B365M Pro4                  | [96a31c2b3c](https://linux-hardware.org/?probe=96a31c2b3c) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [75bff2c415](https://linux-hardware.org/?probe=75bff2c415) | Dec 20, 2021 |
| ASRock        | H170M Pro4S                 | [bcd4acf346](https://linux-hardware.org/?probe=bcd4acf346) | Dec 20, 2021 |
| HP            | 1905                        | [e153d159bf](https://linux-hardware.org/?probe=e153d159bf) | Dec 20, 2021 |
| Gigabyte      | H81M-S1                     | [389e039b0e](https://linux-hardware.org/?probe=389e039b0e) | Dec 19, 2021 |
| ASRock        | G31M-VS                     | [af2a2e4db9](https://linux-hardware.org/?probe=af2a2e4db9) | Dec 19, 2021 |
| ASUSTek       | PRIME B460M-A               | [c2f0152b2b](https://linux-hardware.org/?probe=c2f0152b2b) | Dec 19, 2021 |
| Gigabyte      | H87M-HD3                    | [906e50ad1d](https://linux-hardware.org/?probe=906e50ad1d) | Dec 19, 2021 |
| Acer          | Veriton M4630G V:1.0        | [e17d64b34b](https://linux-hardware.org/?probe=e17d64b34b) | Dec 18, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | [97a556a1b1](https://linux-hardware.org/?probe=97a556a1b1) | Dec 18, 2021 |
| Acer          | Veriton M4630G V:1.0        | [e91c344097](https://linux-hardware.org/?probe=e91c344097) | Dec 18, 2021 |
| ASRock        | AM1B-ITX                    | [e66952c0c4](https://linux-hardware.org/?probe=e66952c0c4) | Dec 18, 2021 |
| Lenovo        | Dory CRB                    | [b4cb543288](https://linux-hardware.org/?probe=b4cb543288) | Dec 17, 2021 |
| Lenovo        | Dory CRB                    | [a6f93a8b7f](https://linux-hardware.org/?probe=a6f93a8b7f) | Dec 17, 2021 |
| Gigabyte      | A520M S2H                   | [c266bd78d7](https://linux-hardware.org/?probe=c266bd78d7) | Dec 17, 2021 |
| Gigabyte      | A520M S2H                   | [b23ba421f5](https://linux-hardware.org/?probe=b23ba421f5) | Dec 17, 2021 |
| Foxconn       | 2ABF                        | [a27e441ee7](https://linux-hardware.org/?probe=a27e441ee7) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Foxconn       | 2ABF                        | [eb78990a42](https://linux-hardware.org/?probe=eb78990a42) | Dec 17, 2021 |
| MSI           | B460M-A PRO                 | [5cd26fcd62](https://linux-hardware.org/?probe=5cd26fcd62) | Dec 15, 2021 |
| MSI           | B460M-A PRO                 | [eb08e1c888](https://linux-hardware.org/?probe=eb08e1c888) | Dec 15, 2021 |
| ASUSTek       | PRIME H370-PLUS             | [8de4e9193a](https://linux-hardware.org/?probe=8de4e9193a) | Dec 15, 2021 |
| ASRock        | FM2A75M Pro4+               | [88d54712f5](https://linux-hardware.org/?probe=88d54712f5) | Dec 15, 2021 |
| ASRock        | B450M Pro4                  | [83f2efe2b5](https://linux-hardware.org/?probe=83f2efe2b5) | Dec 15, 2021 |
| ASRock        | AM1B-ITX                    | [7b567d7211](https://linux-hardware.org/?probe=7b567d7211) | Dec 14, 2021 |
| Gigabyte      | P67A-D3-B3                  | [481ac9664e](https://linux-hardware.org/?probe=481ac9664e) | Dec 14, 2021 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [3760c1b2c2](https://linux-hardware.org/?probe=3760c1b2c2) | Dec 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [f03b1893e9](https://linux-hardware.org/?probe=f03b1893e9) | Dec 14, 2021 |
| Dell          | 0KP561                      | [a39e88c6a1](https://linux-hardware.org/?probe=a39e88c6a1) | Dec 14, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [79238447b1](https://linux-hardware.org/?probe=79238447b1) | Dec 14, 2021 |
| ASRock        | B450M Pro4-F                | [ffca94642e](https://linux-hardware.org/?probe=ffca94642e) | Dec 13, 2021 |
| ASRock        | FM2A75M Pro4+               | [78234730e8](https://linux-hardware.org/?probe=78234730e8) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASRock        | FM2A75M Pro4+               | [bb9e6067a6](https://linux-hardware.org/?probe=bb9e6067a6) | Dec 12, 2021 |
| ASRock        | FM2A75M Pro4+               | [06bcf3473b](https://linux-hardware.org/?probe=06bcf3473b) | Dec 12, 2021 |
| Dell          | 0KP561                      | [f43f20d81b](https://linux-hardware.org/?probe=f43f20d81b) | Dec 11, 2021 |
| Dell          | 0KP561                      | [30626b7d94](https://linux-hardware.org/?probe=30626b7d94) | Dec 11, 2021 |
| Medion        | MS-7748                     | [03560eec95](https://linux-hardware.org/?probe=03560eec95) | Dec 10, 2021 |
| Medion        | MS-7748                     | [839b7ba122](https://linux-hardware.org/?probe=839b7ba122) | Dec 10, 2021 |
| Medion        | MS-7748                     | [ec5ca4da92](https://linux-hardware.org/?probe=ec5ca4da92) | Dec 09, 2021 |
| Medion        | MS-7748                     | [7f2cd5277c](https://linux-hardware.org/?probe=7f2cd5277c) | Dec 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [e66d9be700](https://linux-hardware.org/?probe=e66d9be700) | Dec 09, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [de13fff449](https://linux-hardware.org/?probe=de13fff449) | Dec 08, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [db48ed625a](https://linux-hardware.org/?probe=db48ed625a) | Dec 08, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [85f6ec3796](https://linux-hardware.org/?probe=85f6ec3796) | Dec 08, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [782e5be1e8](https://linux-hardware.org/?probe=782e5be1e8) | Dec 08, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [d2a080ee3c](https://linux-hardware.org/?probe=d2a080ee3c) | Dec 08, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [82e5fa3606](https://linux-hardware.org/?probe=82e5fa3606) | Dec 08, 2021 |
| Lenovo        | ThinkCentre M57 6081A86     | [74828f0e8c](https://linux-hardware.org/?probe=74828f0e8c) | Dec 06, 2021 |
| ASUSTek       | P5QL PRO                    | [fb041fdb69](https://linux-hardware.org/?probe=fb041fdb69) | Dec 05, 2021 |
| Foxconn       | 2ABF                        | [6f668098a9](https://linux-hardware.org/?probe=6f668098a9) | Dec 05, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [d9f0e2da32](https://linux-hardware.org/?probe=d9f0e2da32) | Dec 05, 2021 |
| Foxconn       | 2ABF                        | [a81be0771a](https://linux-hardware.org/?probe=a81be0771a) | Dec 03, 2021 |
| Fujitsu       | D3313-S6 S26361-D3313-S6    | [40d466140f](https://linux-hardware.org/?probe=40d466140f) | Dec 03, 2021 |
| Foxconn       | 2ABF                        | [6e3d35fb3a](https://linux-hardware.org/?probe=6e3d35fb3a) | Dec 02, 2021 |
| Gigabyte      | H87M-HD3                    | [4624f9164d](https://linux-hardware.org/?probe=4624f9164d) | Dec 02, 2021 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [a9ef047f21](https://linux-hardware.org/?probe=a9ef047f21) | Dec 02, 2021 |
| Gigabyte      | G41MT-S2PT                  | [77e63c266d](https://linux-hardware.org/?probe=77e63c266d) | Dec 02, 2021 |
| Foxconn       | 2ABF                        | [f194eb6d68](https://linux-hardware.org/?probe=f194eb6d68) | Dec 01, 2021 |
| ASRock        | FM2A75M Pro4+               | [ca55fa2fac](https://linux-hardware.org/?probe=ca55fa2fac) | Nov 30, 2021 |
| ASUSTek       | P5B-PLUS Series             | [ab546ec9e3](https://linux-hardware.org/?probe=ab546ec9e3) | Nov 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [e065a179a8](https://linux-hardware.org/?probe=e065a179a8) | Nov 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [fd4ce799f3](https://linux-hardware.org/?probe=fd4ce799f3) | Nov 30, 2021 |
| ASUSTek       | P5B-PLUS Series             | [7ac4ce7fff](https://linux-hardware.org/?probe=7ac4ce7fff) | Nov 30, 2021 |
| Medion        | MS-7646                     | [44d5c45bcb](https://linux-hardware.org/?probe=44d5c45bcb) | Nov 29, 2021 |
| Medion        | MS-7646                     | [08b1cd6ab1](https://linux-hardware.org/?probe=08b1cd6ab1) | Nov 29, 2021 |
| Dell          | 0KP561                      | [712ece82db](https://linux-hardware.org/?probe=712ece82db) | Nov 29, 2021 |
| Dell          | 0KP561                      | [56f619dcfa](https://linux-hardware.org/?probe=56f619dcfa) | Nov 29, 2021 |
| ASRock        | G31M-VS                     | [b042297ea5](https://linux-hardware.org/?probe=b042297ea5) | Nov 29, 2021 |
| Dell          | 0KP561                      | [ba6014e10d](https://linux-hardware.org/?probe=ba6014e10d) | Nov 29, 2021 |
| ASUSTek       | H81M-D                      | [b08d192653](https://linux-hardware.org/?probe=b08d192653) | Nov 28, 2021 |
| ASUSTek       | H81M-D                      | [822d1d4f8c](https://linux-hardware.org/?probe=822d1d4f8c) | Nov 28, 2021 |
| Gigabyte      | H87-HD3                     | [82c0604f4c](https://linux-hardware.org/?probe=82c0604f4c) | Nov 28, 2021 |
| Minix         | D2700-HD V1.0               | [53f8729986](https://linux-hardware.org/?probe=53f8729986) | Nov 28, 2021 |
| Dell          | 0K240Y A01                  | [db19440955](https://linux-hardware.org/?probe=db19440955) | Nov 27, 2021 |
| HP            | 339A                        | [e12ad89244](https://linux-hardware.org/?probe=e12ad89244) | Nov 27, 2021 |
| HP            | 339A                        | [94bb470b5e](https://linux-hardware.org/?probe=94bb470b5e) | Nov 27, 2021 |
| Gigabyte      | P67A-D3-B3                  | [eea03b7b52](https://linux-hardware.org/?probe=eea03b7b52) | Nov 26, 2021 |
| ASRock        | A75M-ITX                    | [4b8d23a09d](https://linux-hardware.org/?probe=4b8d23a09d) | Nov 24, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [29efd53713](https://linux-hardware.org/?probe=29efd53713) | Nov 23, 2021 |
| HP            | 805D                        | [38636001e3](https://linux-hardware.org/?probe=38636001e3) | Nov 22, 2021 |
| Gigabyte      | H510M H                     | [0c1d0d8398](https://linux-hardware.org/?probe=0c1d0d8398) | Nov 22, 2021 |
| Medion        | MS-7748                     | [76cc89176e](https://linux-hardware.org/?probe=76cc89176e) | Nov 22, 2021 |
| Medion        | MS-7748                     | [acf3d75c25](https://linux-hardware.org/?probe=acf3d75c25) | Nov 22, 2021 |
| ASRock        | ION3D-HT                    | [915f7c5918](https://linux-hardware.org/?probe=915f7c5918) | Nov 21, 2021 |
| ASRock        | ION3D-HT                    | [2ca36fa3fc](https://linux-hardware.org/?probe=2ca36fa3fc) | Nov 21, 2021 |
| Dell          | 0GY6Y8 A01                  | [341c878a77](https://linux-hardware.org/?probe=341c878a77) | Nov 21, 2021 |
| ASRock        | B85M Pro4                   | [b628dc0d86](https://linux-hardware.org/?probe=b628dc0d86) | Nov 21, 2021 |
| ASRock        | B85M Pro4                   | [0000384b9e](https://linux-hardware.org/?probe=0000384b9e) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | [00ec0123c5](https://linux-hardware.org/?probe=00ec0123c5) | Nov 20, 2021 |
| ASUSTek       | M2N                         | [cc4cf29780](https://linux-hardware.org/?probe=cc4cf29780) | Nov 20, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ad117f68b3](https://linux-hardware.org/?probe=ad117f68b3) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | [12db2d9ccc](https://linux-hardware.org/?probe=12db2d9ccc) | Nov 19, 2021 |
| Unknown       | NF-MCP78                    | [5475574f89](https://linux-hardware.org/?probe=5475574f89) | Nov 19, 2021 |
| Gigabyte      | B450M S2H                   | [7781307d3c](https://linux-hardware.org/?probe=7781307d3c) | Nov 18, 2021 |
| Gigabyte      | B450M GAMING                | [e25b3caecd](https://linux-hardware.org/?probe=e25b3caecd) | Nov 17, 2021 |
| Gigabyte      | B450M GAMING                | [efde1f8b24](https://linux-hardware.org/?probe=efde1f8b24) | Nov 17, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [050f65927b](https://linux-hardware.org/?probe=050f65927b) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [a809aa1e3c](https://linux-hardware.org/?probe=a809aa1e3c) | Nov 17, 2021 |
| HP            | 304Bh                       | [0983c3daf2](https://linux-hardware.org/?probe=0983c3daf2) | Nov 16, 2021 |
| ASUSTek       | PRIME A320M-R               | [2932e00969](https://linux-hardware.org/?probe=2932e00969) | Nov 15, 2021 |
| HP            | 3047h                       | [13eea6a00c](https://linux-hardware.org/?probe=13eea6a00c) | Nov 15, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| ASRock        | FM2A88X Extreme4+           | [fed47693de](https://linux-hardware.org/?probe=fed47693de) | Nov 14, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | [8bbf7045eb](https://linux-hardware.org/?probe=8bbf7045eb) | Nov 13, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [57d648d573](https://linux-hardware.org/?probe=57d648d573) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9234274a5e](https://linux-hardware.org/?probe=9234274a5e) | Nov 11, 2021 |
| ASUSTek       | H110-PLUS                   | [a6bfcee068](https://linux-hardware.org/?probe=a6bfcee068) | Nov 11, 2021 |
| ASUSTek       | H110-PLUS                   | [e50d021703](https://linux-hardware.org/?probe=e50d021703) | Nov 11, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [ffb993e97f](https://linux-hardware.org/?probe=ffb993e97f) | Nov 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | [a180319758](https://linux-hardware.org/?probe=a180319758) | Nov 08, 2021 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [051bbe02b9](https://linux-hardware.org/?probe=051bbe02b9) | Nov 08, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [6f5959b193](https://linux-hardware.org/?probe=6f5959b193) | Nov 08, 2021 |
| ASRock        | B365M Pro4                  | [ed60292a3d](https://linux-hardware.org/?probe=ed60292a3d) | Nov 08, 2021 |
| Medion        | MS-7646                     | [910677196c](https://linux-hardware.org/?probe=910677196c) | Nov 07, 2021 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [fd49440f09](https://linux-hardware.org/?probe=fd49440f09) | Nov 06, 2021 |
| Dell          | 0HH807                      | [60b8032ffc](https://linux-hardware.org/?probe=60b8032ffc) | Nov 05, 2021 |
| Dell          | 09KPNV A00                  | [2ccec65f9c](https://linux-hardware.org/?probe=2ccec65f9c) | Nov 05, 2021 |
| Dell          | 0HH807                      | [4b5694433e](https://linux-hardware.org/?probe=4b5694433e) | Nov 05, 2021 |
| Gigabyte      | GA-E350N                    | [7a1569cd1b](https://linux-hardware.org/?probe=7a1569cd1b) | Nov 04, 2021 |
| Gigabyte      | GA-E350N                    | [636653cd60](https://linux-hardware.org/?probe=636653cd60) | Nov 04, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [d18017b0ab](https://linux-hardware.org/?probe=d18017b0ab) | Nov 04, 2021 |
| ASRock        | G31M-GS                     | [4c527af865](https://linux-hardware.org/?probe=4c527af865) | Nov 04, 2021 |
| ASRock        | G31M-GS                     | [f58c37adfc](https://linux-hardware.org/?probe=f58c37adfc) | Nov 04, 2021 |
| Dell          | 09KPNV A00                  | [36cb1f25d5](https://linux-hardware.org/?probe=36cb1f25d5) | Nov 03, 2021 |
| ASRock        | FM2A75M Pro4+               | [ad724814ff](https://linux-hardware.org/?probe=ad724814ff) | Nov 02, 2021 |
| ASRock        | FM2A75M Pro4+               | [38ebe2b83c](https://linux-hardware.org/?probe=38ebe2b83c) | Nov 02, 2021 |
| Dell          | 0XCR8D A02                  | [cb9a694f6a](https://linux-hardware.org/?probe=cb9a694f6a) | Nov 02, 2021 |
| Medion        | MS-7646                     | [e2efd76c5a](https://linux-hardware.org/?probe=e2efd76c5a) | Nov 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [1453bd6a7f](https://linux-hardware.org/?probe=1453bd6a7f) | Nov 02, 2021 |
| MSI           | B150M MORTAR                | [cc32b13112](https://linux-hardware.org/?probe=cc32b13112) | Nov 02, 2021 |
| ASUSTek       | PRIME A320M-R               | [f47dd27f3d](https://linux-hardware.org/?probe=f47dd27f3d) | Nov 02, 2021 |
| Gigabyte      | B450M GAMING                | [5e684892e2](https://linux-hardware.org/?probe=5e684892e2) | Nov 01, 2021 |
| Gigabyte      | B450M GAMING                | [f9f8705a44](https://linux-hardware.org/?probe=f9f8705a44) | Nov 01, 2021 |
| Gigabyte      | J4005ND2P-CF                | [9f1fa5a3cf](https://linux-hardware.org/?probe=9f1fa5a3cf) | Nov 01, 2021 |
| Gigabyte      | J4005ND2P-CF                | [29a98234db](https://linux-hardware.org/?probe=29a98234db) | Nov 01, 2021 |
| ASRock        | A75M-ITX                    | [9d3864e6ee](https://linux-hardware.org/?probe=9d3864e6ee) | Nov 01, 2021 |
| Dell          | 051FJ8 A00                  | [304737ad06](https://linux-hardware.org/?probe=304737ad06) | Nov 01, 2021 |
| Gigabyte      | G41MT-S2PT                  | [b6304370d1](https://linux-hardware.org/?probe=b6304370d1) | Nov 01, 2021 |
| Gigabyte      | G41MT-S2PT                  | [13862d400e](https://linux-hardware.org/?probe=13862d400e) | Nov 01, 2021 |
| Dell          | 051FJ8 A00                  | [ee0915d7d7](https://linux-hardware.org/?probe=ee0915d7d7) | Nov 01, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [183f547eb4](https://linux-hardware.org/?probe=183f547eb4) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [29f9ae21ee](https://linux-hardware.org/?probe=29f9ae21ee) | Nov 01, 2021 |
| Lenovo        | 7052-A9G                    | [40df1b0b1a](https://linux-hardware.org/?probe=40df1b0b1a) | Nov 01, 2021 |
| Lenovo        | 7052-A9G                    | [af48c29603](https://linux-hardware.org/?probe=af48c29603) | Nov 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e52e9002d0](https://linux-hardware.org/?probe=e52e9002d0) | Oct 31, 2021 |
| Gigabyte      | G41MT-S2PT                  | [5af4fee0ba](https://linux-hardware.org/?probe=5af4fee0ba) | Oct 31, 2021 |
| ASUSTek       | PRIME A320M-R               | [d3a9f1ce6e](https://linux-hardware.org/?probe=d3a9f1ce6e) | Oct 31, 2021 |
| ASRock        | A75M-ITX                    | [42a154c334](https://linux-hardware.org/?probe=42a154c334) | Oct 30, 2021 |
| Medion        | B75MA-P45                   | [c483a48272](https://linux-hardware.org/?probe=c483a48272) | Oct 30, 2021 |
| Gigabyte      | EX58-UD3R                   | [45661425ff](https://linux-hardware.org/?probe=45661425ff) | Oct 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [79a9123be0](https://linux-hardware.org/?probe=79a9123be0) | Oct 29, 2021 |
| Gigabyte      | B560M H                     | [be8b71d264](https://linux-hardware.org/?probe=be8b71d264) | Oct 29, 2021 |
| Gigabyte      | B450M GAMING                | [af6ff66ee8](https://linux-hardware.org/?probe=af6ff66ee8) | Oct 29, 2021 |
| Gigabyte      | G41MT-S2PT                  | [7f06ff456a](https://linux-hardware.org/?probe=7f06ff456a) | Oct 28, 2021 |
| AOpen         | D1009 A1A4                  | [af51adb4bb](https://linux-hardware.org/?probe=af51adb4bb) | Oct 28, 2021 |
| ASUSTek       | H81M-C                      | [67b9ea1699](https://linux-hardware.org/?probe=67b9ea1699) | Oct 28, 2021 |
| Intel         | D945GCCR AAD78647-300       | [d41d75c998](https://linux-hardware.org/?probe=d41d75c998) | Oct 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [7b85c81082](https://linux-hardware.org/?probe=7b85c81082) | Oct 27, 2021 |
| ASRock        | FM2A75M Pro4+               | [5e6e002dd7](https://linux-hardware.org/?probe=5e6e002dd7) | Oct 27, 2021 |
| ASRock        | FM2A68M-DG3+                | [0564545bcd](https://linux-hardware.org/?probe=0564545bcd) | Oct 27, 2021 |
| ASRock        | FM2A68M-DG3+                | [59e7bb5715](https://linux-hardware.org/?probe=59e7bb5715) | Oct 27, 2021 |
| HP            | ProLiant MicroServer        | [e1358c7c92](https://linux-hardware.org/?probe=e1358c7c92) | Oct 26, 2021 |
| Gigabyte      | EP41-UD3L                   | [77c4005bd9](https://linux-hardware.org/?probe=77c4005bd9) | Oct 26, 2021 |
| ASUSTek       | PRIME A320M-R               | [729dbc7651](https://linux-hardware.org/?probe=729dbc7651) | Oct 26, 2021 |
| Gigabyte      | B450M GAMING                | [16297cef95](https://linux-hardware.org/?probe=16297cef95) | Oct 26, 2021 |
| ASUSTek       | PRIME A320M-R               | [b03b8e1aef](https://linux-hardware.org/?probe=b03b8e1aef) | Oct 25, 2021 |
| ASUSTek       | PRIME A320M-R               | [88b714c91c](https://linux-hardware.org/?probe=88b714c91c) | Oct 25, 2021 |
| ASRock        | FM2A75M Pro4+               | [2575618c9d](https://linux-hardware.org/?probe=2575618c9d) | Oct 24, 2021 |
| ASRock        | FM2A75M Pro4+               | [219c9e69dd](https://linux-hardware.org/?probe=219c9e69dd) | Oct 24, 2021 |
| Acer          | Aspire X1935                | [b4ed3c0529](https://linux-hardware.org/?probe=b4ed3c0529) | Oct 24, 2021 |
| Acer          | Aspire X1935                | [6e0109a230](https://linux-hardware.org/?probe=6e0109a230) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| Acer          | Aspire X1935                | [f0b8fff129](https://linux-hardware.org/?probe=f0b8fff129) | Oct 23, 2021 |
| ASRock        | A75M-ITX                    | [c2ea35ef30](https://linux-hardware.org/?probe=c2ea35ef30) | Oct 22, 2021 |
| ASRock        | G31M-GS                     | [28e9f5e95f](https://linux-hardware.org/?probe=28e9f5e95f) | Oct 22, 2021 |
| ASRock        | FM2A75M Pro4+               | [6ec597bc1f](https://linux-hardware.org/?probe=6ec597bc1f) | Oct 21, 2021 |
| ASRock        | G31M-GS                     | [94acb8fa87](https://linux-hardware.org/?probe=94acb8fa87) | Oct 21, 2021 |
| Dell          | 040DDP A01                  | [c401dcdeb5](https://linux-hardware.org/?probe=c401dcdeb5) | Oct 21, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [f094a159cc](https://linux-hardware.org/?probe=f094a159cc) | Oct 21, 2021 |
| Gigabyte      | A320M-H-CF                  | [1ee663a97d](https://linux-hardware.org/?probe=1ee663a97d) | Oct 20, 2021 |
| ASRock        | AB350M-HDV R3.0             | [ac305398b3](https://linux-hardware.org/?probe=ac305398b3) | Oct 20, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [ef4fe075d9](https://linux-hardware.org/?probe=ef4fe075d9) | Oct 19, 2021 |
| ASRock        | AB350M-HDV R3.0             | [1566e28e13](https://linux-hardware.org/?probe=1566e28e13) | Oct 19, 2021 |
| Dell          | 042P49 A00                  | [534a66a78e](https://linux-hardware.org/?probe=534a66a78e) | Oct 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a33e68304f](https://linux-hardware.org/?probe=a33e68304f) | Oct 17, 2021 |
| ASRock        | M3A785GXH/128M              | [9268bda6a2](https://linux-hardware.org/?probe=9268bda6a2) | Oct 17, 2021 |
| Dell          | 0HH807                      | [79fdffe8ec](https://linux-hardware.org/?probe=79fdffe8ec) | Oct 17, 2021 |
| ASRock        | A320M-HDV R3.0              | [e5f58b5d76](https://linux-hardware.org/?probe=e5f58b5d76) | Oct 17, 2021 |
| ASRock        | A320M-HDV R3.0              | [4bf3c6eea6](https://linux-hardware.org/?probe=4bf3c6eea6) | Oct 17, 2021 |
| HP            | 3048h                       | [66aba742a1](https://linux-hardware.org/?probe=66aba742a1) | Oct 16, 2021 |
| HP            | 3048h                       | [e10815e28b](https://linux-hardware.org/?probe=e10815e28b) | Oct 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [2dc6a1d295](https://linux-hardware.org/?probe=2dc6a1d295) | Oct 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [1112150233](https://linux-hardware.org/?probe=1112150233) | Oct 16, 2021 |
| ASRock        | FM2A75M Pro4+               | [ed2c8818b1](https://linux-hardware.org/?probe=ed2c8818b1) | Oct 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [82c18a5c4f](https://linux-hardware.org/?probe=82c18a5c4f) | Oct 16, 2021 |
| ASRock        | P67 Extreme4                | [fb4d76caab](https://linux-hardware.org/?probe=fb4d76caab) | Oct 16, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [4c78e0cb2b](https://linux-hardware.org/?probe=4c78e0cb2b) | Oct 15, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [efe1f6696f](https://linux-hardware.org/?probe=efe1f6696f) | Oct 15, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [de914bf781](https://linux-hardware.org/?probe=de914bf781) | Oct 15, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [8fe0fccc66](https://linux-hardware.org/?probe=8fe0fccc66) | Oct 15, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [42d90aa70b](https://linux-hardware.org/?probe=42d90aa70b) | Oct 15, 2021 |
| ASRock        | Z370 Pro4                   | [4603126532](https://linux-hardware.org/?probe=4603126532) | Oct 15, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [5c680571ad](https://linux-hardware.org/?probe=5c680571ad) | Oct 15, 2021 |
| ASUSTek       | Crosshair IV Formula        | [65a6fc76f7](https://linux-hardware.org/?probe=65a6fc76f7) | Oct 15, 2021 |
| HP            | 3047h                       | [f66ec61e22](https://linux-hardware.org/?probe=f66ec61e22) | Oct 14, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [dba1f5388d](https://linux-hardware.org/?probe=dba1f5388d) | Oct 14, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [8cb5f6619c](https://linux-hardware.org/?probe=8cb5f6619c) | Oct 14, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | [467c3682c1](https://linux-hardware.org/?probe=467c3682c1) | Oct 13, 2021 |
| MSI           | A320M BAZOOKA               | [acfde1543b](https://linux-hardware.org/?probe=acfde1543b) | Oct 13, 2021 |
| Gigabyte      | H61M-D2-B3                  | [1005ec2531](https://linux-hardware.org/?probe=1005ec2531) | Oct 13, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [297e015743](https://linux-hardware.org/?probe=297e015743) | Oct 13, 2021 |
| ASRock        | FM2A75M Pro4+               | [5ada5c50fa](https://linux-hardware.org/?probe=5ada5c50fa) | Oct 12, 2021 |
| ASRock        | FM2A75M Pro4+               | [fd728a94c7](https://linux-hardware.org/?probe=fd728a94c7) | Oct 12, 2021 |
| Gigabyte      | Z590 UD AC                  | [ec7ba8e11a](https://linux-hardware.org/?probe=ec7ba8e11a) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4342f43c87](https://linux-hardware.org/?probe=4342f43c87) | Oct 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [848ca6ba47](https://linux-hardware.org/?probe=848ca6ba47) | Oct 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [38dfedc3d4](https://linux-hardware.org/?probe=38dfedc3d4) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [da72dae510](https://linux-hardware.org/?probe=da72dae510) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |
| Gigabyte      | X99-UD3-CF                  | [347d6df600](https://linux-hardware.org/?probe=347d6df600) | Oct 12, 2021 |
| ASRock        | AB350M-HDV R3.0             | [a214b95fb1](https://linux-hardware.org/?probe=a214b95fb1) | Oct 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | [3d26775340](https://linux-hardware.org/?probe=3d26775340) | Oct 11, 2021 |
| Gigabyte      | B450M GAMING                | [f3a72daeb2](https://linux-hardware.org/?probe=f3a72daeb2) | Oct 11, 2021 |
| Gigabyte      | B450M GAMING                | [437d5a964e](https://linux-hardware.org/?probe=437d5a964e) | Oct 11, 2021 |
| ASRock        | FM2A75M Pro4+               | [0c02d64f86](https://linux-hardware.org/?probe=0c02d64f86) | Oct 10, 2021 |
| ASRock        | FM2A75M Pro4+               | [e47408eeae](https://linux-hardware.org/?probe=e47408eeae) | Oct 10, 2021 |
| Dell          | 0HH807                      | [692c125ea1](https://linux-hardware.org/?probe=692c125ea1) | Oct 10, 2021 |
| Gigabyte      | H61M-S1                     | [d7a1eaa74f](https://linux-hardware.org/?probe=d7a1eaa74f) | Oct 10, 2021 |
| Gigabyte      | H61M-S1                     | [e7294698d5](https://linux-hardware.org/?probe=e7294698d5) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [34bd8d1731](https://linux-hardware.org/?probe=34bd8d1731) | Oct 08, 2021 |
| HP            | 1850                        | [f015e1d723](https://linux-hardware.org/?probe=f015e1d723) | Oct 08, 2021 |
| HP            | 1850                        | [ca826dc2a8](https://linux-hardware.org/?probe=ca826dc2a8) | Oct 08, 2021 |
| ASUSTek       | PRIME B450M-A               | [cede000cfe](https://linux-hardware.org/?probe=cede000cfe) | Oct 08, 2021 |
| ASRock        | H110 Pro BTC+               | [e099edf338](https://linux-hardware.org/?probe=e099edf338) | Oct 08, 2021 |
| Gigabyte      | P67A-D3-B3                  | [679674342a](https://linux-hardware.org/?probe=679674342a) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [08bd5ce8ba](https://linux-hardware.org/?probe=08bd5ce8ba) | Oct 07, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [b4f0a3ac81](https://linux-hardware.org/?probe=b4f0a3ac81) | Oct 07, 2021 |
| Dell          | 042P49 A00                  | [ae38db7950](https://linux-hardware.org/?probe=ae38db7950) | Oct 07, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [5fb2c09c5a](https://linux-hardware.org/?probe=5fb2c09c5a) | Oct 07, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [62d65c6dbd](https://linux-hardware.org/?probe=62d65c6dbd) | Oct 07, 2021 |
| Dell          | 042P49 A00                  | [fed6853ecf](https://linux-hardware.org/?probe=fed6853ecf) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [96f0badb1a](https://linux-hardware.org/?probe=96f0badb1a) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [c78f82b137](https://linux-hardware.org/?probe=c78f82b137) | Oct 07, 2021 |
| Unknown       | NF-MCP78                    | [89eef3c1a9](https://linux-hardware.org/?probe=89eef3c1a9) | Oct 06, 2021 |
| Dell          | 04YP6J A02                  | [8c5232840e](https://linux-hardware.org/?probe=8c5232840e) | Oct 06, 2021 |
| ASUSTek       | PRIME B365M-A               | [c0bcda2558](https://linux-hardware.org/?probe=c0bcda2558) | Oct 05, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [620cf43d8c](https://linux-hardware.org/?probe=620cf43d8c) | Oct 05, 2021 |
| ASUSTek       | PRIME B365M-A               | [1d781d0515](https://linux-hardware.org/?probe=1d781d0515) | Oct 05, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [930f24205c](https://linux-hardware.org/?probe=930f24205c) | Oct 05, 2021 |
| Gigabyte      | H81M-S                      | [c5c52cc683](https://linux-hardware.org/?probe=c5c52cc683) | Oct 05, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [87e02ffa04](https://linux-hardware.org/?probe=87e02ffa04) | Oct 04, 2021 |
| ASRock        | FM2A78M-ITX+                | [ac327f6ccd](https://linux-hardware.org/?probe=ac327f6ccd) | Oct 03, 2021 |
| ASUSTek       | P5K-E                       | [047ba385fb](https://linux-hardware.org/?probe=047ba385fb) | Oct 03, 2021 |
| Unknown       | NF-MCP78                    | [acd7f5af32](https://linux-hardware.org/?probe=acd7f5af32) | Oct 03, 2021 |
| HP            | 3648h                       | [a21990541e](https://linux-hardware.org/?probe=a21990541e) | Oct 02, 2021 |
| ASUSTek       | Crosshair IV Formula        | [37ab8645f2](https://linux-hardware.org/?probe=37ab8645f2) | Oct 02, 2021 |
| ASUSTek       | Crosshair IV Formula        | [bc5b837be9](https://linux-hardware.org/?probe=bc5b837be9) | Oct 02, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b3820e4c5b](https://linux-hardware.org/?probe=b3820e4c5b) | Oct 01, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [6325e87df9](https://linux-hardware.org/?probe=6325e87df9) | Sep 30, 2021 |
| HP            | 339A                        | [b5af0617de](https://linux-hardware.org/?probe=b5af0617de) | Sep 30, 2021 |
| HP            | 339A                        | [40f2319534](https://linux-hardware.org/?probe=40f2319534) | Sep 30, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [4609c2f8e7](https://linux-hardware.org/?probe=4609c2f8e7) | Sep 30, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [4ec386d3fe](https://linux-hardware.org/?probe=4ec386d3fe) | Sep 30, 2021 |
| MSI           | G31M3-L V2                  | [2c6743db1a](https://linux-hardware.org/?probe=2c6743db1a) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | [ea770dbf08](https://linux-hardware.org/?probe=ea770dbf08) | Sep 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [117bf7a43d](https://linux-hardware.org/?probe=117bf7a43d) | Sep 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9ea3df1de](https://linux-hardware.org/?probe=a9ea3df1de) | Sep 28, 2021 |
| ASUSTek       | PRIME B365M-A               | [4180f07858](https://linux-hardware.org/?probe=4180f07858) | Sep 27, 2021 |
| ASUSTek       | PRIME B365M-A               | [c0387b0c6e](https://linux-hardware.org/?probe=c0387b0c6e) | Sep 27, 2021 |
| HP            | ProLiant MicroServer        | [531a56dc7a](https://linux-hardware.org/?probe=531a56dc7a) | Sep 26, 2021 |
| Lenovo        | SDK0E50510 WIN              | [f8502b5c83](https://linux-hardware.org/?probe=f8502b5c83) | Sep 25, 2021 |
| Lenovo        | SDK0E50510 WIN              | [159d56e485](https://linux-hardware.org/?probe=159d56e485) | Sep 25, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [08d8affc67](https://linux-hardware.org/?probe=08d8affc67) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [d2e3e42411](https://linux-hardware.org/?probe=d2e3e42411) | Sep 25, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [e051a4f0a5](https://linux-hardware.org/?probe=e051a4f0a5) | Sep 25, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [1b3c9892fe](https://linux-hardware.org/?probe=1b3c9892fe) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [5c9a5f607c](https://linux-hardware.org/?probe=5c9a5f607c) | Sep 24, 2021 |
| Gigabyte      | P67A-D3-B3                  | [b0fc31da96](https://linux-hardware.org/?probe=b0fc31da96) | Sep 22, 2021 |
| ASUSTek       | Crosshair IV Formula        | [9476202052](https://linux-hardware.org/?probe=9476202052) | Sep 22, 2021 |
| ASUSTek       | Crosshair IV Formula        | [4ae8e54658](https://linux-hardware.org/?probe=4ae8e54658) | Sep 22, 2021 |
| ASUSTek       | PRIME B365M-A               | [8d522eb6f9](https://linux-hardware.org/?probe=8d522eb6f9) | Sep 22, 2021 |
| ASUSTek       | PRIME B365M-A               | [6b38686790](https://linux-hardware.org/?probe=6b38686790) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| Gigabyte      | P67A-D3-B3                  | [5abd4b5b41](https://linux-hardware.org/?probe=5abd4b5b41) | Sep 21, 2021 |
| Gigabyte      | H61M-DS2                    | [0d52c3d318](https://linux-hardware.org/?probe=0d52c3d318) | Sep 20, 2021 |
| Lenovo        | SDK0E50510 WIN              | [d2f00a48eb](https://linux-hardware.org/?probe=d2f00a48eb) | Sep 20, 2021 |
| Lenovo        | SDK0E50510 WIN              | [3c1735b674](https://linux-hardware.org/?probe=3c1735b674) | Sep 20, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a2a2fb4a37](https://linux-hardware.org/?probe=a2a2fb4a37) | Sep 19, 2021 |
| Lenovo        | SDK0E50510 WIN              | [59da5f6189](https://linux-hardware.org/?probe=59da5f6189) | Sep 19, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [9a1cd7ff88](https://linux-hardware.org/?probe=9a1cd7ff88) | Sep 19, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [36d1365bf4](https://linux-hardware.org/?probe=36d1365bf4) | Sep 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [88d81ffc0a](https://linux-hardware.org/?probe=88d81ffc0a) | Sep 18, 2021 |
| Dell          | 042P49 A00                  | [aac5ee2d08](https://linux-hardware.org/?probe=aac5ee2d08) | Sep 18, 2021 |
| Dell          | 042P49 A00                  | [19767a5ca3](https://linux-hardware.org/?probe=19767a5ca3) | Sep 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | [cfbaf14ee1](https://linux-hardware.org/?probe=cfbaf14ee1) | Sep 18, 2021 |
| Intel         | DG41RQ AAE54511-205         | [8830ef3d59](https://linux-hardware.org/?probe=8830ef3d59) | Sep 17, 2021 |
| Gigabyte      | G41MT-S2PT                  | [9487f0833d](https://linux-hardware.org/?probe=9487f0833d) | Sep 17, 2021 |
| Intel         | DG41RQ AAE54511-205         | [c6d04492c3](https://linux-hardware.org/?probe=c6d04492c3) | Sep 17, 2021 |
| Gigabyte      | G41MT-S2PT                  | [b016defc57](https://linux-hardware.org/?probe=b016defc57) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASUSTek       | P7P55D                      | [9b2fccd56c](https://linux-hardware.org/?probe=9b2fccd56c) | Sep 17, 2021 |
| ASUSTek       | P7P55D                      | [f140b7f9da](https://linux-hardware.org/?probe=f140b7f9da) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASRock        | B365M Pro4                  | [220ff38d46](https://linux-hardware.org/?probe=220ff38d46) | Sep 16, 2021 |
| Gigabyte      | P67A-D3-B3                  | [26c3981f46](https://linux-hardware.org/?probe=26c3981f46) | Sep 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [4e7df6d137](https://linux-hardware.org/?probe=4e7df6d137) | Sep 15, 2021 |
| ASUSTek       | PRIME B365M-A               | [37e0e1e105](https://linux-hardware.org/?probe=37e0e1e105) | Sep 15, 2021 |
| ASUSTek       | PRIME B365M-A               | [0cfa735943](https://linux-hardware.org/?probe=0cfa735943) | Sep 14, 2021 |
| ASUSTek       | PRIME B365M-A               | [d3ed44b359](https://linux-hardware.org/?probe=d3ed44b359) | Sep 14, 2021 |
| ASUSTek       | H81M-C                      | [535e1cd490](https://linux-hardware.org/?probe=535e1cd490) | Sep 14, 2021 |
| Gigabyte      | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| ASRock        | 945GCM-S                    | [03499bb636](https://linux-hardware.org/?probe=03499bb636) | Sep 13, 2021 |
| Gigabyte      | G41MT-S2PT                  | [97dd712d6b](https://linux-hardware.org/?probe=97dd712d6b) | Sep 12, 2021 |
| Gigabyte      | H81M-S1                     | [9776910346](https://linux-hardware.org/?probe=9776910346) | Sep 12, 2021 |
| Gigabyte      | H81M-S1                     | [2ff1e76c4c](https://linux-hardware.org/?probe=2ff1e76c4c) | Sep 12, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9127bc0d0a](https://linux-hardware.org/?probe=9127bc0d0a) | Sep 12, 2021 |
| Gigabyte      | H110M-S2HP-CF               | [88b4dd396f](https://linux-hardware.org/?probe=88b4dd396f) | Sep 12, 2021 |
| Gigabyte      | M57SLI-S4                   | [e55af94449](https://linux-hardware.org/?probe=e55af94449) | Sep 12, 2021 |
| ASUSTek       | V-M3N8200                   | [4ee51bb086](https://linux-hardware.org/?probe=4ee51bb086) | Sep 11, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [ff4265647a](https://linux-hardware.org/?probe=ff4265647a) | Sep 11, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [ab1d855978](https://linux-hardware.org/?probe=ab1d855978) | Sep 11, 2021 |
| Gigabyte      | M57SLI-S4                   | [146ac97e70](https://linux-hardware.org/?probe=146ac97e70) | Sep 11, 2021 |
| Dell          | 042P49 A00                  | [58329f197b](https://linux-hardware.org/?probe=58329f197b) | Sep 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3a4a448af4](https://linux-hardware.org/?probe=3a4a448af4) | Sep 10, 2021 |
| ASUSTek       | PRIME B365M-A               | [871521108c](https://linux-hardware.org/?probe=871521108c) | Sep 09, 2021 |
| Dell          | 0WMJ54 A01                  | [fb3d977ed2](https://linux-hardware.org/?probe=fb3d977ed2) | Sep 09, 2021 |
| ASRock        | FM2A75M Pro4+               | [f9a6db318b](https://linux-hardware.org/?probe=f9a6db318b) | Sep 08, 2021 |
| ASRock        | FM2A75M Pro4+               | [0c82df3a06](https://linux-hardware.org/?probe=0c82df3a06) | Sep 08, 2021 |
| HP            | 1850                        | [411bf15eca](https://linux-hardware.org/?probe=411bf15eca) | Sep 08, 2021 |
| HP            | 1850                        | [6e9c48c5d6](https://linux-hardware.org/?probe=6e9c48c5d6) | Sep 08, 2021 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [a3ecb14c0c](https://linux-hardware.org/?probe=a3ecb14c0c) | Sep 07, 2021 |
| ASUSTek       | PRIME B365M-A               | [62dc94bf03](https://linux-hardware.org/?probe=62dc94bf03) | Sep 07, 2021 |
| Gigabyte      | G41MT-S2PT                  | [98f43bc075](https://linux-hardware.org/?probe=98f43bc075) | Sep 06, 2021 |
| Gigabyte      | G41MT-S2PT                  | [19f7501dc0](https://linux-hardware.org/?probe=19f7501dc0) | Sep 06, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [e72963a1b5](https://linux-hardware.org/?probe=e72963a1b5) | Sep 06, 2021 |
| Intel         | DG35EC AAE29266-206         | [ea929e2d7e](https://linux-hardware.org/?probe=ea929e2d7e) | Sep 06, 2021 |
| Gigabyte      | G41MT-S2PT                  | [049f33e3a1](https://linux-hardware.org/?probe=049f33e3a1) | Sep 05, 2021 |
| ASUSTek       | F1A75-M PRO                 | [a3e8627869](https://linux-hardware.org/?probe=a3e8627869) | Sep 04, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [c0df973810](https://linux-hardware.org/?probe=c0df973810) | Sep 04, 2021 |
| ASRock        | 4CoreDual-SATA2             | [cad3b9b0f1](https://linux-hardware.org/?probe=cad3b9b0f1) | Sep 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c6d512b026](https://linux-hardware.org/?probe=c6d512b026) | Sep 03, 2021 |
| ASUSTek       | H110M-A                     | [ccec98ba3b](https://linux-hardware.org/?probe=ccec98ba3b) | Sep 03, 2021 |
| ASUSTek       | H110M-A                     | [ba85622bd9](https://linux-hardware.org/?probe=ba85622bd9) | Sep 03, 2021 |
| Dell          | 0C27VV A01                  | [4954befff2](https://linux-hardware.org/?probe=4954befff2) | Sep 03, 2021 |
| HP            | 1497                        | [b0391f5e3b](https://linux-hardware.org/?probe=b0391f5e3b) | Sep 03, 2021 |
| ASUSTek       | PRIME A320M-R               | [6c6942f44c](https://linux-hardware.org/?probe=6c6942f44c) | Sep 03, 2021 |
| ASUSTek       | PRIME A320M-R               | [7eddf184b0](https://linux-hardware.org/?probe=7eddf184b0) | Sep 02, 2021 |
| Gigabyte      | G41MT-S2PT                  | [9a5ff9dfeb](https://linux-hardware.org/?probe=9a5ff9dfeb) | Sep 02, 2021 |
| Gigabyte      | B450 AORUS M                | [03bcbe2a20](https://linux-hardware.org/?probe=03bcbe2a20) | Sep 02, 2021 |
| Gigabyte      | P67A-D3-B3                  | [f196983180](https://linux-hardware.org/?probe=f196983180) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [ff69ae3970](https://linux-hardware.org/?probe=ff69ae3970) | Sep 01, 2021 |
| ASUSTek       | F1A75-M PRO                 | [7462e7862f](https://linux-hardware.org/?probe=7462e7862f) | Sep 01, 2021 |
| Gigabyte      | B450 AORUS M                | [b599686ac3](https://linux-hardware.org/?probe=b599686ac3) | Sep 01, 2021 |
| Gigabyte      | B450 AORUS M                | [22d55b215b](https://linux-hardware.org/?probe=22d55b215b) | Sep 01, 2021 |
| Gigabyte      | B85-HD3                     | [3692a01aed](https://linux-hardware.org/?probe=3692a01aed) | Aug 31, 2021 |
| ASRock        | FM2A68M-DG3+                | [1c39c6a6a7](https://linux-hardware.org/?probe=1c39c6a6a7) | Aug 31, 2021 |
| ASRock        | FM2A75M Pro4+               | [fd885351b2](https://linux-hardware.org/?probe=fd885351b2) | Aug 31, 2021 |
| ASRock        | FM2A75M Pro4+               | [7abf2da5d9](https://linux-hardware.org/?probe=7abf2da5d9) | Aug 31, 2021 |
| ASRock        | FM2A55M-DGS                 | [4e5483f8ac](https://linux-hardware.org/?probe=4e5483f8ac) | Aug 30, 2021 |
| HP            | 339A                        | [4d0ba425d3](https://linux-hardware.org/?probe=4d0ba425d3) | Aug 30, 2021 |
| ASUSTek       | PRIME B365M-A               | [386205cb7a](https://linux-hardware.org/?probe=386205cb7a) | Aug 30, 2021 |
| HP            | 339A                        | [6572008aa8](https://linux-hardware.org/?probe=6572008aa8) | Aug 30, 2021 |
| HP            | 339A                        | [65bbc55e85](https://linux-hardware.org/?probe=65bbc55e85) | Aug 30, 2021 |
| HP            | 339A                        | [fbe8527e27](https://linux-hardware.org/?probe=fbe8527e27) | Aug 30, 2021 |
| Gigabyte      | P67A-D3-B3                  | [c3bb5024c6](https://linux-hardware.org/?probe=c3bb5024c6) | Aug 30, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [01068c79df](https://linux-hardware.org/?probe=01068c79df) | Aug 29, 2021 |
| ASRock        | FM2A55M-DGS                 | [67a8c1ef5b](https://linux-hardware.org/?probe=67a8c1ef5b) | Aug 29, 2021 |
| ASRock        | FM2A55M-DGS                 | [fc76c90854](https://linux-hardware.org/?probe=fc76c90854) | Aug 29, 2021 |
| Gigabyte      | H170-D3HP-CF                | [64087c4ed2](https://linux-hardware.org/?probe=64087c4ed2) | Aug 29, 2021 |
| ASRock        | G31M-GS                     | [64c987e31f](https://linux-hardware.org/?probe=64c987e31f) | Aug 28, 2021 |
| Unknown       | T3 MRD V1.1                 | [9acb786639](https://linux-hardware.org/?probe=9acb786639) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| Gigabyte      | G41MT-S2PT                  | [d9b8d68a27](https://linux-hardware.org/?probe=d9b8d68a27) | Aug 27, 2021 |
| Dell          | 0HN7XN A01                  | [af8a3aac02](https://linux-hardware.org/?probe=af8a3aac02) | Aug 27, 2021 |
| Gigabyte      | A320M-H-CF                  | [5cee16a454](https://linux-hardware.org/?probe=5cee16a454) | Aug 27, 2021 |
| ASUSTek       | A8N-SLI                     | [f43dbdd84f](https://linux-hardware.org/?probe=f43dbdd84f) | Aug 27, 2021 |
| Dell          | 0KP561                      | [aaae00b03c](https://linux-hardware.org/?probe=aaae00b03c) | Aug 27, 2021 |
| Dell          | 0KP561                      | [945a17243f](https://linux-hardware.org/?probe=945a17243f) | Aug 27, 2021 |
| Gigabyte      | G41MT-S2PT                  | [195d08a54c](https://linux-hardware.org/?probe=195d08a54c) | Aug 26, 2021 |
| ASRock        | FM2A55M-DGS                 | [22aef16302](https://linux-hardware.org/?probe=22aef16302) | Aug 26, 2021 |
| ASRock        | FM2A55M-DGS                 | [9521da307e](https://linux-hardware.org/?probe=9521da307e) | Aug 26, 2021 |
| ASRock        | AB350 Gaming K4             | [f25ecb1f4d](https://linux-hardware.org/?probe=f25ecb1f4d) | Aug 25, 2021 |
| ASUSTek       | PRIME A320M-R               | [743bb647e8](https://linux-hardware.org/?probe=743bb647e8) | Aug 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [4ca08670f9](https://linux-hardware.org/?probe=4ca08670f9) | Aug 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [c2083e6b60](https://linux-hardware.org/?probe=c2083e6b60) | Aug 24, 2021 |
| ASUSTek       | PRIME B365M-A               | [dbf504b6a5](https://linux-hardware.org/?probe=dbf504b6a5) | Aug 24, 2021 |
| ASUSTek       | PRIME B365M-A               | [a94b2db164](https://linux-hardware.org/?probe=a94b2db164) | Aug 24, 2021 |
| Foxconn       | 2ABF                        | [0ea76af952](https://linux-hardware.org/?probe=0ea76af952) | Aug 24, 2021 |
| Foxconn       | 2ABF                        | [c276a9ab0a](https://linux-hardware.org/?probe=c276a9ab0a) | Aug 24, 2021 |
| ASRock        | FM2A75M Pro4+               | [36fc620223](https://linux-hardware.org/?probe=36fc620223) | Aug 23, 2021 |
| ASRock        | FM2A75M Pro4+               | [5a0c624731](https://linux-hardware.org/?probe=5a0c624731) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-R               | [aa83132d79](https://linux-hardware.org/?probe=aa83132d79) | Aug 23, 2021 |
| Gigabyte      | G41MT-S2PT                  | [2fca41e052](https://linux-hardware.org/?probe=2fca41e052) | Aug 22, 2021 |
| Gigabyte      | G41MT-S2PT                  | [9b7bc61611](https://linux-hardware.org/?probe=9b7bc61611) | Aug 22, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [4951e3a5e3](https://linux-hardware.org/?probe=4951e3a5e3) | Aug 22, 2021 |
| Dell          | 0KP561                      | [b136ea3e88](https://linux-hardware.org/?probe=b136ea3e88) | Aug 21, 2021 |
| Dell          | 0KP561                      | [52425b1ce2](https://linux-hardware.org/?probe=52425b1ce2) | Aug 21, 2021 |
| Fujitsu       | D3118-A2 S26361-D3118-A2    | [8e8715b0cd](https://linux-hardware.org/?probe=8e8715b0cd) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [46614b6e2e](https://linux-hardware.org/?probe=46614b6e2e) | Aug 18, 2021 |
| Wistron       | ProLiant ML110 G6           | [a43f59c4ab](https://linux-hardware.org/?probe=a43f59c4ab) | Aug 18, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [097ad1f8b1](https://linux-hardware.org/?probe=097ad1f8b1) | Aug 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | [0cebce03bb](https://linux-hardware.org/?probe=0cebce03bb) | Aug 17, 2021 |
| ASUSTek       | PRIME B365M-A               | [5e62791576](https://linux-hardware.org/?probe=5e62791576) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [5a5a31dc0b](https://linux-hardware.org/?probe=5a5a31dc0b) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [322b65b02a](https://linux-hardware.org/?probe=322b65b02a) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [eb8a66e986](https://linux-hardware.org/?probe=eb8a66e986) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [0c67b898b6](https://linux-hardware.org/?probe=0c67b898b6) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [6ddc03d1e7](https://linux-hardware.org/?probe=6ddc03d1e7) | Aug 16, 2021 |
| Dell          | 0C27VV A01                  | [c811f7984e](https://linux-hardware.org/?probe=c811f7984e) | Aug 15, 2021 |
| Dell          | 0C27VV A01                  | [6c7f7a7f72](https://linux-hardware.org/?probe=6c7f7a7f72) | Aug 15, 2021 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [337dd88949](https://linux-hardware.org/?probe=337dd88949) | Aug 14, 2021 |
| ASRock        | FM2A75M Pro4+               | [3d8aee6409](https://linux-hardware.org/?probe=3d8aee6409) | Aug 14, 2021 |
| ASUSTek       | AM1M-A                      | [c5e4927f76](https://linux-hardware.org/?probe=c5e4927f76) | Aug 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [45c59105c4](https://linux-hardware.org/?probe=45c59105c4) | Aug 12, 2021 |
| Lenovo        | Board                       | [8841f4eb25](https://linux-hardware.org/?probe=8841f4eb25) | Aug 11, 2021 |
| ASRock        | J3160-ITX                   | [682890974b](https://linux-hardware.org/?probe=682890974b) | Aug 11, 2021 |
| HP            | ProLiant MicroServer        | [f7472b1017](https://linux-hardware.org/?probe=f7472b1017) | Aug 11, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [77f7e27f04](https://linux-hardware.org/?probe=77f7e27f04) | Aug 11, 2021 |
| ASUSTek       | H110M-K                     | [4746c16098](https://linux-hardware.org/?probe=4746c16098) | Aug 10, 2021 |
| Gigabyte      | P67A-D3-B3                  | [9e6ce28012](https://linux-hardware.org/?probe=9e6ce28012) | Aug 08, 2021 |
| ASRock        | B75 Pro3                    | [c32fcf3e07](https://linux-hardware.org/?probe=c32fcf3e07) | Aug 08, 2021 |
| ASRock        | B75 Pro3                    | [b6fb908c5e](https://linux-hardware.org/?probe=b6fb908c5e) | Aug 08, 2021 |
| ASUSTek       | M2A-MX                      | [9aa2ff4ca2](https://linux-hardware.org/?probe=9aa2ff4ca2) | Aug 07, 2021 |
| Lenovo        | Board                       | [f3a8efacf0](https://linux-hardware.org/?probe=f3a8efacf0) | Aug 07, 2021 |
| Lenovo        | Board                       | [1aef7ded95](https://linux-hardware.org/?probe=1aef7ded95) | Aug 07, 2021 |
| ASRock        | B85M                        | [a3363aaf61](https://linux-hardware.org/?probe=a3363aaf61) | Aug 06, 2021 |
| ASRock        | B85M                        | [d2667fd78f](https://linux-hardware.org/?probe=d2667fd78f) | Aug 06, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [6c7c2e63a6](https://linux-hardware.org/?probe=6c7c2e63a6) | Aug 05, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [ab79a32cc2](https://linux-hardware.org/?probe=ab79a32cc2) | Aug 05, 2021 |
| Gigabyte      | H310M S2H x.x               | [5324364e30](https://linux-hardware.org/?probe=5324364e30) | Aug 05, 2021 |
| Gigabyte      | H310M S2H x.x               | [3464207bf9](https://linux-hardware.org/?probe=3464207bf9) | Aug 05, 2021 |
| Dell          | 0GM819                      | [0dcf2d06c1](https://linux-hardware.org/?probe=0dcf2d06c1) | Aug 05, 2021 |
| Dell          | 0GM819                      | [6dd45e20cc](https://linux-hardware.org/?probe=6dd45e20cc) | Aug 05, 2021 |
| Gigabyte      | G41MT-S2                    | [88dc4d9a30](https://linux-hardware.org/?probe=88dc4d9a30) | Aug 02, 2021 |
| Gigabyte      | G41MT-S2                    | [bebba22bf9](https://linux-hardware.org/?probe=bebba22bf9) | Aug 02, 2021 |
| ASUSTek       | B75M-A                      | [a5019e4b32](https://linux-hardware.org/?probe=a5019e4b32) | Aug 01, 2021 |
| ASUSTek       | H81M-C                      | [1bddfe5a64](https://linux-hardware.org/?probe=1bddfe5a64) | Aug 01, 2021 |
| Gigabyte      | EP45-UD3                    | [c2ed86e850](https://linux-hardware.org/?probe=c2ed86e850) | Aug 01, 2021 |
| ASRock        | 4CoreDual-SATA2             | [5b17caa94d](https://linux-hardware.org/?probe=5b17caa94d) | Aug 01, 2021 |
| ASRock        | 4CoreDual-SATA2             | [feb2c5c340](https://linux-hardware.org/?probe=feb2c5c340) | Aug 01, 2021 |
| Gigabyte      | EP45-UD3                    | [6775219be1](https://linux-hardware.org/?probe=6775219be1) | Aug 01, 2021 |
| ASUSTek       | B75M-A                      | [314c09e02e](https://linux-hardware.org/?probe=314c09e02e) | Aug 01, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f656370ab1](https://linux-hardware.org/?probe=f656370ab1) | Jul 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [a282d834c3](https://linux-hardware.org/?probe=a282d834c3) | Jul 31, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [bbc2a8730c](https://linux-hardware.org/?probe=bbc2a8730c) | Jul 31, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [2fcda4fa72](https://linux-hardware.org/?probe=2fcda4fa72) | Jul 31, 2021 |
| MSI           | B450I GAMING PLUS AC        | [cacd4b91a5](https://linux-hardware.org/?probe=cacd4b91a5) | Jul 31, 2021 |
| MSI           | B450I GAMING PLUS AC        | [1caefe66d6](https://linux-hardware.org/?probe=1caefe66d6) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [5ba8f24eda](https://linux-hardware.org/?probe=5ba8f24eda) | Jul 30, 2021 |
| Lenovo        | Board                       | [171501e566](https://linux-hardware.org/?probe=171501e566) | Jul 30, 2021 |
| ASUSTek       | PRIME B365M-A               | [25f6033200](https://linux-hardware.org/?probe=25f6033200) | Jul 29, 2021 |
| ASUSTek       | PRIME B365M-A               | [b72fa42ea7](https://linux-hardware.org/?probe=b72fa42ea7) | Jul 29, 2021 |
| ASUSTek       | PRIME B365M-A               | [3904c32fbc](https://linux-hardware.org/?probe=3904c32fbc) | Jul 29, 2021 |
| Gigabyte      | 970A-DS3P                   | [a8abc9f29f](https://linux-hardware.org/?probe=a8abc9f29f) | Jul 29, 2021 |
| Dell          | 0VD5HY A00                  | [f4115403fe](https://linux-hardware.org/?probe=f4115403fe) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [fde3c4fa9f](https://linux-hardware.org/?probe=fde3c4fa9f) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [451f5ecbcf](https://linux-hardware.org/?probe=451f5ecbcf) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [2428ba9d17](https://linux-hardware.org/?probe=2428ba9d17) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [f3daafb698](https://linux-hardware.org/?probe=f3daafb698) | Jul 27, 2021 |
| ASUSTek       | PRIME B365M-A               | [89e15e668b](https://linux-hardware.org/?probe=89e15e668b) | Jul 27, 2021 |
| ASUSTek       | PRIME B365M-A               | [91d27803e4](https://linux-hardware.org/?probe=91d27803e4) | Jul 27, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [da264c335c](https://linux-hardware.org/?probe=da264c335c) | Jul 27, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [4279830fce](https://linux-hardware.org/?probe=4279830fce) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| ASUSTek       | P7P55D                      | [1895c9117e](https://linux-hardware.org/?probe=1895c9117e) | Jul 26, 2021 |
| ASUSTek       | P7P55D                      | [ae216dec22](https://linux-hardware.org/?probe=ae216dec22) | Jul 26, 2021 |
| Gigabyte      | G41MT-S2PT                  | [044559bb88](https://linux-hardware.org/?probe=044559bb88) | Jul 26, 2021 |
| Gigabyte      | G41MT-S2PT                  | [2cc580a560](https://linux-hardware.org/?probe=2cc580a560) | Jul 26, 2021 |
| ASRock        | B250M Pro4                  | [5b604a949d](https://linux-hardware.org/?probe=5b604a949d) | Jul 26, 2021 |
| ASRock        | B250M Pro4                  | [d8f05d9acc](https://linux-hardware.org/?probe=d8f05d9acc) | Jul 26, 2021 |
| MSI           | 2A9Ch                       | [93ee78c8d1](https://linux-hardware.org/?probe=93ee78c8d1) | Jul 25, 2021 |
| MSI           | 2A9Ch                       | [49f73287c8](https://linux-hardware.org/?probe=49f73287c8) | Jul 25, 2021 |
| ASUSTek       | H110M-A                     | [b186699a65](https://linux-hardware.org/?probe=b186699a65) | Jul 25, 2021 |
| ASUSTek       | H110M-A                     | [550dc3327b](https://linux-hardware.org/?probe=550dc3327b) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| ASUSTek       | P5QC                        | [1964e96f5b](https://linux-hardware.org/?probe=1964e96f5b) | Jul 25, 2021 |
| ASUSTek       | P5QC                        | [f17cd722d8](https://linux-hardware.org/?probe=f17cd722d8) | Jul 25, 2021 |
| ASUSTek       | P5QC                        | [850e5c5f2a](https://linux-hardware.org/?probe=850e5c5f2a) | Jul 25, 2021 |
| ASRock        | B250M Pro4                  | [a85901b6d4](https://linux-hardware.org/?probe=a85901b6d4) | Jul 24, 2021 |
| ASRock        | B250M Pro4                  | [c2e8f0fec8](https://linux-hardware.org/?probe=c2e8f0fec8) | Jul 24, 2021 |
| Unknown       | 775i65G                     | [b92a942f9e](https://linux-hardware.org/?probe=b92a942f9e) | Jul 23, 2021 |
| HP            | 8055                        | [1b9ebeb8fa](https://linux-hardware.org/?probe=1b9ebeb8fa) | Jul 23, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [54a35ebdd2](https://linux-hardware.org/?probe=54a35ebdd2) | Jul 22, 2021 |
| ASRock        | B250M Pro4                  | [272875ccfb](https://linux-hardware.org/?probe=272875ccfb) | Jul 22, 2021 |
| Gigabyte      | H81M-HD3                    | [c3ddc34552](https://linux-hardware.org/?probe=c3ddc34552) | Jul 22, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [9edb803c32](https://linux-hardware.org/?probe=9edb803c32) | Jul 22, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [7cbc302447](https://linux-hardware.org/?probe=7cbc302447) | Jul 22, 2021 |
| ASUSTek       | H81M-E                      | [4c55d81b47](https://linux-hardware.org/?probe=4c55d81b47) | Jul 22, 2021 |
| ASRock        | B250M Pro4                  | [ca9889003b](https://linux-hardware.org/?probe=ca9889003b) | Jul 22, 2021 |
| ASUSTek       | H81M-E                      | [df85b3a98b](https://linux-hardware.org/?probe=df85b3a98b) | Jul 22, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [33d0133c6f](https://linux-hardware.org/?probe=33d0133c6f) | Jul 22, 2021 |
| ASRock        | B550M Pro4                  | [9d070c09ac](https://linux-hardware.org/?probe=9d070c09ac) | Jul 21, 2021 |
| ASUSTek       | PRIME B365M-A               | [f257dde72a](https://linux-hardware.org/?probe=f257dde72a) | Jul 21, 2021 |
| ASRock        | B550M Pro4                  | [9d5b7e363b](https://linux-hardware.org/?probe=9d5b7e363b) | Jul 21, 2021 |
| ASUSTek       | PRIME B365M-A               | [68b7c3ed61](https://linux-hardware.org/?probe=68b7c3ed61) | Jul 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [83c0a37711](https://linux-hardware.org/?probe=83c0a37711) | Jul 18, 2021 |
| Gigabyte      | H61M-DS2                    | [51928c8c9b](https://linux-hardware.org/?probe=51928c8c9b) | Jul 18, 2021 |
| Gigabyte      | H61M-DS2                    | [9bec640779](https://linux-hardware.org/?probe=9bec640779) | Jul 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [d079295fab](https://linux-hardware.org/?probe=d079295fab) | Jul 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [b623dba68b](https://linux-hardware.org/?probe=b623dba68b) | Jul 18, 2021 |
| HP            | 0A68h                       | [0d65da8218](https://linux-hardware.org/?probe=0d65da8218) | Jul 18, 2021 |
| HP            | 0A68h                       | [5abf71b3b5](https://linux-hardware.org/?probe=5abf71b3b5) | Jul 18, 2021 |
| ASUSTek       | H110M-A                     | [58d78b8e65](https://linux-hardware.org/?probe=58d78b8e65) | Jul 17, 2021 |
| MSI           | G41M-P28                    | [3ee9259ce1](https://linux-hardware.org/?probe=3ee9259ce1) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [f03b137212](https://linux-hardware.org/?probe=f03b137212) | Jul 17, 2021 |
| HP            | 1850                        | [7a7e737a89](https://linux-hardware.org/?probe=7a7e737a89) | Jul 17, 2021 |
| HP            | 1850                        | [f8fce9677b](https://linux-hardware.org/?probe=f8fce9677b) | Jul 17, 2021 |
| ASUSTek       | H110M-A                     | [da611f3a89](https://linux-hardware.org/?probe=da611f3a89) | Jul 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [0a56fa942f](https://linux-hardware.org/?probe=0a56fa942f) | Jul 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [5291ceb2e8](https://linux-hardware.org/?probe=5291ceb2e8) | Jul 17, 2021 |
| HP            | 3029h                       | [cdd0072823](https://linux-hardware.org/?probe=cdd0072823) | Jul 17, 2021 |
| ASUSTek       | P7P55D                      | [1fdccf0b8c](https://linux-hardware.org/?probe=1fdccf0b8c) | Jul 16, 2021 |
| ASUSTek       | P7P55D                      | [732e6e2b14](https://linux-hardware.org/?probe=732e6e2b14) | Jul 16, 2021 |
| ASUSTek       | P7P55D                      | [764653dba1](https://linux-hardware.org/?probe=764653dba1) | Jul 16, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| ASUSTek       | M2N68-AM Plus               | [0369488ec1](https://linux-hardware.org/?probe=0369488ec1) | Jul 15, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [fded86e377](https://linux-hardware.org/?probe=fded86e377) | Jul 14, 2021 |
| Acer          | Veriton X4630G              | [080363027e](https://linux-hardware.org/?probe=080363027e) | Jul 14, 2021 |
| Acer          | Veriton X4630G              | [5fa2645a1f](https://linux-hardware.org/?probe=5fa2645a1f) | Jul 14, 2021 |
| ASUSTek       | P7P55D                      | [384f2488c8](https://linux-hardware.org/?probe=384f2488c8) | Jul 13, 2021 |
| ASUSTek       | P7P55D                      | [ee84d97e60](https://linux-hardware.org/?probe=ee84d97e60) | Jul 13, 2021 |
| Gigabyte      | H81M-HD3                    | [0d72e1d70d](https://linux-hardware.org/?probe=0d72e1d70d) | Jul 12, 2021 |
| Lenovo        | Tilapia CRB                 | [da1f0d65ec](https://linux-hardware.org/?probe=da1f0d65ec) | Jul 12, 2021 |
| ASRock        | B450M Pro4-F                | [b8a9b28642](https://linux-hardware.org/?probe=b8a9b28642) | Jul 11, 2021 |
| ASUSTek       | VC65R                       | [790c5f73db](https://linux-hardware.org/?probe=790c5f73db) | Jul 09, 2021 |
| ASUSTek       | H110M-A                     | [bb21071b06](https://linux-hardware.org/?probe=bb21071b06) | Jul 08, 2021 |
| ASUSTek       | M2N68-AM Plus               | [222c467b30](https://linux-hardware.org/?probe=222c467b30) | Jul 08, 2021 |
| ASUSTek       | P7P55D                      | [5a6fd99a3e](https://linux-hardware.org/?probe=5a6fd99a3e) | Jul 08, 2021 |
| HP            | 3047h                       | [e78150909f](https://linux-hardware.org/?probe=e78150909f) | Jul 08, 2021 |
| ASUSTek       | P7P55D                      | [ff168e6f91](https://linux-hardware.org/?probe=ff168e6f91) | Jul 08, 2021 |
| ASUSTek       | H110M-A                     | [d77e374c3f](https://linux-hardware.org/?probe=d77e374c3f) | Jul 07, 2021 |
| MSI           | B150M ECO                   | [c97e6af0f2](https://linux-hardware.org/?probe=c97e6af0f2) | Jul 07, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [33b70fad34](https://linux-hardware.org/?probe=33b70fad34) | Jul 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | [500b07927d](https://linux-hardware.org/?probe=500b07927d) | Jul 06, 2021 |
| ASUSTek       | P7P55-M                     | [3248d46b49](https://linux-hardware.org/?probe=3248d46b49) | Jul 06, 2021 |
| ASUSTek       | P7P55-M                     | [c4e2ad4152](https://linux-hardware.org/?probe=c4e2ad4152) | Jul 06, 2021 |
| ASRock        | 970M Pro3                   | [afcf713572](https://linux-hardware.org/?probe=afcf713572) | Jul 05, 2021 |
| ASUSTek       | H110M-A                     | [468912e900](https://linux-hardware.org/?probe=468912e900) | Jul 05, 2021 |
| Gigabyte      | EP45-UD3                    | [0bb7172bae](https://linux-hardware.org/?probe=0bb7172bae) | Jul 05, 2021 |
| ASRock        | 970M Pro3                   | [0601bffa1e](https://linux-hardware.org/?probe=0601bffa1e) | Jul 04, 2021 |
| Gigabyte      | G41MT-S2PT                  | [0058d5166f](https://linux-hardware.org/?probe=0058d5166f) | Jul 04, 2021 |
| ASUSTek       | P7P55D                      | [7a537952d2](https://linux-hardware.org/?probe=7a537952d2) | Jul 04, 2021 |
| ASRock        | B450 Pro4                   | [cddc04f9bf](https://linux-hardware.org/?probe=cddc04f9bf) | Jul 04, 2021 |
| Dell          | 0KP561                      | [7f73e68ddf](https://linux-hardware.org/?probe=7f73e68ddf) | Jul 03, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [0ec93378c3](https://linux-hardware.org/?probe=0ec93378c3) | Jul 03, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [b32ea99708](https://linux-hardware.org/?probe=b32ea99708) | Jul 03, 2021 |
| ASUSTek       | P7P55D                      | [fd6c20bc63](https://linux-hardware.org/?probe=fd6c20bc63) | Jul 03, 2021 |
| ASUSTek       | H110M-A                     | [7f5ac19a94](https://linux-hardware.org/?probe=7f5ac19a94) | Jul 01, 2021 |
| Dell          | 055H3G A01                  | [15d111f1ae](https://linux-hardware.org/?probe=15d111f1ae) | Jul 01, 2021 |
| ASRock        | B450 Pro4                   | [1164a5f913](https://linux-hardware.org/?probe=1164a5f913) | Jul 01, 2021 |
| ASRock        | FM2A55M-DGS                 | [33478fad16](https://linux-hardware.org/?probe=33478fad16) | Jul 01, 2021 |
| ASRock        | FM2A55M-DGS                 | [c9875dfb4a](https://linux-hardware.org/?probe=c9875dfb4a) | Jul 01, 2021 |
| ASRock        | AB350M-HDV R3.0             | [03fe042535](https://linux-hardware.org/?probe=03fe042535) | Jul 01, 2021 |
| ASUSTek       | H110M-R                     | [3f18260d1c](https://linux-hardware.org/?probe=3f18260d1c) | Jun 30, 2021 |
| ASUSTek       | H110M-A                     | [ebb24ecfca](https://linux-hardware.org/?probe=ebb24ecfca) | Jun 29, 2021 |
| ASUSTek       | PRIME A320M-R               | [78c94a5398](https://linux-hardware.org/?probe=78c94a5398) | Jun 29, 2021 |
| Gigabyte      | GA-MA770-UD3                | [34d2885e24](https://linux-hardware.org/?probe=34d2885e24) | Jun 28, 2021 |
| Lenovo        | 7052-A9G                    | [596f502ebb](https://linux-hardware.org/?probe=596f502ebb) | Jun 27, 2021 |
| Lenovo        | 7052-A9G                    | [619feb575b](https://linux-hardware.org/?probe=619feb575b) | Jun 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [602f35c3ff](https://linux-hardware.org/?probe=602f35c3ff) | Jun 27, 2021 |
| ASUSTek       | P7P55-M                     | [349fbd07ac](https://linux-hardware.org/?probe=349fbd07ac) | Jun 27, 2021 |
| ASUSTek       | P7P55-M                     | [53556ddcf3](https://linux-hardware.org/?probe=53556ddcf3) | Jun 27, 2021 |
| Pegatron      | Benicia                     | [2e2484cb24](https://linux-hardware.org/?probe=2e2484cb24) | Jun 26, 2021 |
| Pegatron      | Benicia                     | [38f8d52df2](https://linux-hardware.org/?probe=38f8d52df2) | Jun 26, 2021 |
| Gigabyte      | 945GCM-S2L                  | [770971c70a](https://linux-hardware.org/?probe=770971c70a) | Jun 26, 2021 |
| Gigabyte      | B450M GAMING                | [437db234e1](https://linux-hardware.org/?probe=437db234e1) | Jun 26, 2021 |
| Gigabyte      | B450M GAMING                | [fefedaa32d](https://linux-hardware.org/?probe=fefedaa32d) | Jun 26, 2021 |
| ASUSTek       | H110M-A                     | [b281ce9131](https://linux-hardware.org/?probe=b281ce9131) | Jun 26, 2021 |
| Pegatron      | 2A73                        | [45e9b6e0ca](https://linux-hardware.org/?probe=45e9b6e0ca) | Jun 26, 2021 |
| Pegatron      | 2A73                        | [af6808a93c](https://linux-hardware.org/?probe=af6808a93c) | Jun 26, 2021 |
| ASUSTek       | PRIME A320M-R               | [9b6d40dbd1](https://linux-hardware.org/?probe=9b6d40dbd1) | Jun 25, 2021 |
| Lenovo        | Board                       | [1e44038d9f](https://linux-hardware.org/?probe=1e44038d9f) | Jun 25, 2021 |
| ASUSTek       | AM1M-A                      | [7926f5f9ec](https://linux-hardware.org/?probe=7926f5f9ec) | Jun 25, 2021 |
| Lenovo        | Board                       | [c7b597d184](https://linux-hardware.org/?probe=c7b597d184) | Jun 25, 2021 |
| Gigabyte      | G41MT-S2PT                  | [d65e7a989b](https://linux-hardware.org/?probe=d65e7a989b) | Jun 23, 2021 |
| ASRock        | FM2A68M-HD+                 | [1e37b435ea](https://linux-hardware.org/?probe=1e37b435ea) | Jun 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f3de105f7c](https://linux-hardware.org/?probe=f3de105f7c) | Jun 23, 2021 |
| ASUSTek       | AM1M-A                      | [fd4a23127d](https://linux-hardware.org/?probe=fd4a23127d) | Jun 22, 2021 |
| ASUSTek       | P7P55D-E                    | [e2e01634fe](https://linux-hardware.org/?probe=e2e01634fe) | Jun 21, 2021 |
| Gigabyte      | G41MT-S2PT                  | [def1925097](https://linux-hardware.org/?probe=def1925097) | Jun 20, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [29be4d18e9](https://linux-hardware.org/?probe=29be4d18e9) | Jun 20, 2021 |
| ASUSTek       | P7P55D-E                    | [c9bfcd2d0e](https://linux-hardware.org/?probe=c9bfcd2d0e) | Jun 20, 2021 |
| ASUSTek       | H110M-A                     | [b74294bfd1](https://linux-hardware.org/?probe=b74294bfd1) | Jun 19, 2021 |
| ASUSTek       | H110M-A                     | [ba4e6cbd0f](https://linux-hardware.org/?probe=ba4e6cbd0f) | Jun 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [ff0470d418](https://linux-hardware.org/?probe=ff0470d418) | Jun 19, 2021 |
| Gigabyte      | EP45-UD3                    | [7390744979](https://linux-hardware.org/?probe=7390744979) | Jun 19, 2021 |
| ASUSTek       | P7P55D-E                    | [bf94cf4f0c](https://linux-hardware.org/?probe=bf94cf4f0c) | Jun 19, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [c13134fc57](https://linux-hardware.org/?probe=c13134fc57) | Jun 19, 2021 |
| ASUSTek       | P7P55D-E                    | [69dba0a341](https://linux-hardware.org/?probe=69dba0a341) | Jun 19, 2021 |
| ASRock        | G41M-VS3                    | [761cc9a0fd](https://linux-hardware.org/?probe=761cc9a0fd) | Jun 18, 2021 |
| ASRock        | G41M-VS3                    | [b10e83a964](https://linux-hardware.org/?probe=b10e83a964) | Jun 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | [ae41cc836d](https://linux-hardware.org/?probe=ae41cc836d) | Jun 17, 2021 |
| ASRock        | G41M-VS3                    | [a4cae20589](https://linux-hardware.org/?probe=a4cae20589) | Jun 17, 2021 |
| HP            | 0A68h                       | [93c9241e3a](https://linux-hardware.org/?probe=93c9241e3a) | Jun 17, 2021 |
| Lenovo        | NOK                         | [7cd1c48ff7](https://linux-hardware.org/?probe=7cd1c48ff7) | Jun 17, 2021 |
| Lenovo        | NOK                         | [4a5ca01289](https://linux-hardware.org/?probe=4a5ca01289) | Jun 17, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [07a7bd0dcf](https://linux-hardware.org/?probe=07a7bd0dcf) | Jun 17, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [430e051485](https://linux-hardware.org/?probe=430e051485) | Jun 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | [ffa931b206](https://linux-hardware.org/?probe=ffa931b206) | Jun 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4f3b7ea314](https://linux-hardware.org/?probe=4f3b7ea314) | Jun 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [3ffaaf7165](https://linux-hardware.org/?probe=3ffaaf7165) | Jun 17, 2021 |
| HP            | 0A68h                       | [272ea77ebc](https://linux-hardware.org/?probe=272ea77ebc) | Jun 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | [b2637aa748](https://linux-hardware.org/?probe=b2637aa748) | Jun 16, 2021 |
| Gigabyte      | 945GCM-S2L                  | [342ae79c5a](https://linux-hardware.org/?probe=342ae79c5a) | Jun 16, 2021 |
| ASUSTek       | M5A97 PLUS                  | [987ef5946e](https://linux-hardware.org/?probe=987ef5946e) | Jun 16, 2021 |
| ASUSTek       | M5A97 PLUS                  | [d6831d4bd5](https://linux-hardware.org/?probe=d6831d4bd5) | Jun 16, 2021 |
| ASUSTek       | H110M-A                     | [64936a9519](https://linux-hardware.org/?probe=64936a9519) | Jun 15, 2021 |
| ASUSTek       | H110M-A                     | [b3bca3adb3](https://linux-hardware.org/?probe=b3bca3adb3) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E                    | [fd58a1c56f](https://linux-hardware.org/?probe=fd58a1c56f) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E                    | [3c474c8754](https://linux-hardware.org/?probe=3c474c8754) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [96353190ff](https://linux-hardware.org/?probe=96353190ff) | Jun 15, 2021 |
| Gigabyte      | 945GCM-S2L                  | [1098eea9c3](https://linux-hardware.org/?probe=1098eea9c3) | Jun 14, 2021 |
| Gigabyte      | 945GCM-S2C                  | [c7e324e6c2](https://linux-hardware.org/?probe=c7e324e6c2) | Jun 14, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6fa1ce0161](https://linux-hardware.org/?probe=6fa1ce0161) | Jun 14, 2021 |
| Gigabyte      | 945GCM-S2C                  | [be08e30ca5](https://linux-hardware.org/?probe=be08e30ca5) | Jun 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | [3f3b75a76d](https://linux-hardware.org/?probe=3f3b75a76d) | Jun 13, 2021 |
| Lenovo        | MAHOBAY NOK                 | [34f6b01cd3](https://linux-hardware.org/?probe=34f6b01cd3) | Jun 13, 2021 |
| Gigabyte      | P67A-D3-B3                  | [bd1fa618b2](https://linux-hardware.org/?probe=bd1fa618b2) | Jun 13, 2021 |
| Gigabyte      | P67A-D3-B3                  | [f1960822c0](https://linux-hardware.org/?probe=f1960822c0) | Jun 13, 2021 |
| ASRock        | B550M Pro4                  | [a18d8c2f61](https://linux-hardware.org/?probe=a18d8c2f61) | Jun 12, 2021 |
| Lenovo        | Board                       | [41310d3373](https://linux-hardware.org/?probe=41310d3373) | Jun 12, 2021 |
| ASRock        | B550M Pro4                  | [63c75ffb59](https://linux-hardware.org/?probe=63c75ffb59) | Jun 11, 2021 |
| ASRock        | B550M Pro4                  | [fb7eb180bc](https://linux-hardware.org/?probe=fb7eb180bc) | Jun 11, 2021 |
| HP            | 1850                        | [beb3fc0199](https://linux-hardware.org/?probe=beb3fc0199) | Jun 11, 2021 |
| HP            | 1850                        | [3439ad1e64](https://linux-hardware.org/?probe=3439ad1e64) | Jun 11, 2021 |
| Pegatron      | Benicia                     | [63b3d6c67e](https://linux-hardware.org/?probe=63b3d6c67e) | Jun 10, 2021 |
| Pegatron      | Benicia                     | [5233f7f85c](https://linux-hardware.org/?probe=5233f7f85c) | Jun 10, 2021 |
| ASRock        | G41M-VS3                    | [6b978deb9d](https://linux-hardware.org/?probe=6b978deb9d) | Jun 09, 2021 |
| ASRock        | G41M-VS3                    | [efc4cbb7b3](https://linux-hardware.org/?probe=efc4cbb7b3) | Jun 09, 2021 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [2e1cf6ba65](https://linux-hardware.org/?probe=2e1cf6ba65) | Jun 09, 2021 |
| Gigabyte      | EP45-UD3                    | [0e24e807e1](https://linux-hardware.org/?probe=0e24e807e1) | Jun 08, 2021 |
| HP            | 8054                        | [ec649716ce](https://linux-hardware.org/?probe=ec649716ce) | Jun 08, 2021 |
| Gigabyte      | P55-US3L                    | [46186d595e](https://linux-hardware.org/?probe=46186d595e) | Jun 08, 2021 |
| Gigabyte      | P55-US3L                    | [e04be7a5d4](https://linux-hardware.org/?probe=e04be7a5d4) | Jun 08, 2021 |
| HP            | 8054                        | [132b21848b](https://linux-hardware.org/?probe=132b21848b) | Jun 08, 2021 |
| ASRock        | B550M Pro4                  | [b69db7738f](https://linux-hardware.org/?probe=b69db7738f) | Jun 07, 2021 |
| Gigabyte      | B450M GAMING                | [d776eae12d](https://linux-hardware.org/?probe=d776eae12d) | Jun 07, 2021 |
| Gigabyte      | B450M GAMING                | [eeca67c1ce](https://linux-hardware.org/?probe=eeca67c1ce) | Jun 07, 2021 |
| HP            | 3029h                       | [fd1c85e8a0](https://linux-hardware.org/?probe=fd1c85e8a0) | Jun 07, 2021 |
| Gigabyte      | G41MT-S2PT                  | [07da8f58a5](https://linux-hardware.org/?probe=07da8f58a5) | Jun 07, 2021 |
| Gigabyte      | G41MT-S2PT                  | [e46c003681](https://linux-hardware.org/?probe=e46c003681) | Jun 07, 2021 |
| HP            | 1998                        | [ced90ab9e8](https://linux-hardware.org/?probe=ced90ab9e8) | Jun 06, 2021 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [f35d5a648d](https://linux-hardware.org/?probe=f35d5a648d) | Jun 06, 2021 |
| Lenovo        | SDK0E50510 WIN              | [b3a96627e7](https://linux-hardware.org/?probe=b3a96627e7) | Jun 06, 2021 |
| Lenovo        | SDK0E50510 WIN              | [b6a203b46c](https://linux-hardware.org/?probe=b6a203b46c) | Jun 06, 2021 |
| Dell          | 0M5DCD A00                  | [0fe7ee6fef](https://linux-hardware.org/?probe=0fe7ee6fef) | Jun 06, 2021 |
| Dell          | 0M5DCD A00                  | [9eb9a008db](https://linux-hardware.org/?probe=9eb9a008db) | Jun 06, 2021 |
| Medion        | MS-7646                     | [3bd37e342e](https://linux-hardware.org/?probe=3bd37e342e) | Jun 05, 2021 |
| Medion        | MS-7646                     | [28a12de5d3](https://linux-hardware.org/?probe=28a12de5d3) | Jun 05, 2021 |
| ASUSTek       | AM1M-A                      | [aae694a17b](https://linux-hardware.org/?probe=aae694a17b) | Jun 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [e7e821c4a7](https://linux-hardware.org/?probe=e7e821c4a7) | Jun 04, 2021 |
| HP            | 8054                        | [8ee390f293](https://linux-hardware.org/?probe=8ee390f293) | Jun 04, 2021 |
| HP            | 8054                        | [e11f83223c](https://linux-hardware.org/?probe=e11f83223c) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [a2ea29b46d](https://linux-hardware.org/?probe=a2ea29b46d) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [e094ed6000](https://linux-hardware.org/?probe=e094ed6000) | Jun 04, 2021 |
| ASRock        | G41M-GS                     | [32c5a6d38f](https://linux-hardware.org/?probe=32c5a6d38f) | Jun 03, 2021 |
| ASRock        | G41M-GS                     | [dde78b5387](https://linux-hardware.org/?probe=dde78b5387) | Jun 03, 2021 |
| ASRock        | ConRoe1333-D667             | [6a899d4598](https://linux-hardware.org/?probe=6a899d4598) | Jun 02, 2021 |
| ASRock        | ConRoe1333-D667             | [0d922a9503](https://linux-hardware.org/?probe=0d922a9503) | Jun 02, 2021 |
| Gigabyte      | G41MT-S2PT                  | [fcc8895289](https://linux-hardware.org/?probe=fcc8895289) | Jun 01, 2021 |
| Gigabyte      | G41MT-S2PT                  | [46c72b92c4](https://linux-hardware.org/?probe=46c72b92c4) | Jun 01, 2021 |
| ASRock        | FM2A75 Pro4-M               | [a42b9e9b4c](https://linux-hardware.org/?probe=a42b9e9b4c) | Jun 01, 2021 |
| ASRock        | G41M-GS                     | [87c40fcd51](https://linux-hardware.org/?probe=87c40fcd51) | May 31, 2021 |
| ASRock        | FM2A75 Pro4-M               | [3d65247771](https://linux-hardware.org/?probe=3d65247771) | May 31, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [441067c1c2](https://linux-hardware.org/?probe=441067c1c2) | May 31, 2021 |
| Gigabyte      | F2A55M-DS2                  | [14f43dc84d](https://linux-hardware.org/?probe=14f43dc84d) | May 31, 2021 |
| Gigabyte      | F2A55M-DS2                  | [04ecf95ef8](https://linux-hardware.org/?probe=04ecf95ef8) | May 31, 2021 |
| HP            | 0A68h                       | [0959557733](https://linux-hardware.org/?probe=0959557733) | May 30, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [e9fc8eb1f1](https://linux-hardware.org/?probe=e9fc8eb1f1) | May 30, 2021 |
| ASRock        | FM2A58M-DG3+                | [9d17b2ff73](https://linux-hardware.org/?probe=9d17b2ff73) | May 30, 2021 |
| ASUSTek       | H110M-A                     | [e72091c45b](https://linux-hardware.org/?probe=e72091c45b) | May 29, 2021 |
| ASUSTek       | H110M-A                     | [34366ca0cc](https://linux-hardware.org/?probe=34366ca0cc) | May 29, 2021 |
| ASUSTek       | M5A78L-M LX3                | [08ed9af2b9](https://linux-hardware.org/?probe=08ed9af2b9) | May 29, 2021 |
| MSI           | B150M MORTAR                | [20c36e7f2a](https://linux-hardware.org/?probe=20c36e7f2a) | May 29, 2021 |
| MSI           | B150M MORTAR                | [bcc715ad42](https://linux-hardware.org/?probe=bcc715ad42) | May 29, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [4999ecd668](https://linux-hardware.org/?probe=4999ecd668) | May 28, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f04a4bb553](https://linux-hardware.org/?probe=f04a4bb553) | May 28, 2021 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [fa7e68c037](https://linux-hardware.org/?probe=fa7e68c037) | May 28, 2021 |
| Gigabyte      | H81M-S                      | [f5747f7378](https://linux-hardware.org/?probe=f5747f7378) | May 28, 2021 |
| Gigabyte      | H81M-S                      | [09333861d3](https://linux-hardware.org/?probe=09333861d3) | May 28, 2021 |
| Gigabyte      | EP31-DS3L                   | [f39bcb5de8](https://linux-hardware.org/?probe=f39bcb5de8) | May 28, 2021 |
| Gigabyte      | EP31-DS3L                   | [044dc05ba7](https://linux-hardware.org/?probe=044dc05ba7) | May 28, 2021 |
| ASRock        | G41M-VS3                    | [b9b144530e](https://linux-hardware.org/?probe=b9b144530e) | May 27, 2021 |
| Gigabyte      | P67A-D3-B3                  | [2ab2dabd84](https://linux-hardware.org/?probe=2ab2dabd84) | May 26, 2021 |
| HP            | 1850                        | [bc5ddfc411](https://linux-hardware.org/?probe=bc5ddfc411) | May 26, 2021 |
| HP            | 1850                        | [d21ff3f29a](https://linux-hardware.org/?probe=d21ff3f29a) | May 26, 2021 |
| ASUSTek       | M3A-H/HDMI                  | [7165a5413a](https://linux-hardware.org/?probe=7165a5413a) | May 25, 2021 |
| MSI           | A320M PRO-E                 | [dfa36657a7](https://linux-hardware.org/?probe=dfa36657a7) | May 25, 2021 |
| MSI           | A320M PRO-E                 | [052e68d307](https://linux-hardware.org/?probe=052e68d307) | May 25, 2021 |
| ASRock        | Z170M Extreme4              | [f850d90312](https://linux-hardware.org/?probe=f850d90312) | May 24, 2021 |
| ASRock        | Z170M Extreme4              | [6b18cfc1f9](https://linux-hardware.org/?probe=6b18cfc1f9) | May 24, 2021 |
| Gigabyte      | G31M-S2L                    | [17db6d39fe](https://linux-hardware.org/?probe=17db6d39fe) | May 24, 2021 |
| Gigabyte      | G31M-S2L                    | [69341df289](https://linux-hardware.org/?probe=69341df289) | May 24, 2021 |
| Gigabyte      | EP31-DS3L                   | [2c13fab5f4](https://linux-hardware.org/?probe=2c13fab5f4) | May 24, 2021 |
| Gigabyte      | EP31-DS3L                   | [0b8b4983ad](https://linux-hardware.org/?probe=0b8b4983ad) | May 24, 2021 |
| ASUSTek       | H110M-A                     | [d756796120](https://linux-hardware.org/?probe=d756796120) | May 23, 2021 |
| HP            | 0AA8h                       | [c0e9143e13](https://linux-hardware.org/?probe=c0e9143e13) | May 23, 2021 |
| Lenovo        | SDK0E50510 WIN              | [2432ec433f](https://linux-hardware.org/?probe=2432ec433f) | May 23, 2021 |
| Lenovo        | SDK0E50510 WIN              | [786b8f1681](https://linux-hardware.org/?probe=786b8f1681) | May 23, 2021 |
| Gigabyte      | P67A-D3-B3                  | [848e169731](https://linux-hardware.org/?probe=848e169731) | May 23, 2021 |
| ASUSTek       | H110M-A                     | [7cc377194f](https://linux-hardware.org/?probe=7cc377194f) | May 22, 2021 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [a9b9eb3480](https://linux-hardware.org/?probe=a9b9eb3480) | May 22, 2021 |
| Gigabyte      | G41MT-S2PT                  | [a367e3c6bf](https://linux-hardware.org/?probe=a367e3c6bf) | May 22, 2021 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [79ca888dc3](https://linux-hardware.org/?probe=79ca888dc3) | May 22, 2021 |
| HP            | 1850                        | [aba46fa730](https://linux-hardware.org/?probe=aba46fa730) | May 22, 2021 |
| HP            | 1850                        | [85ec59cbc0](https://linux-hardware.org/?probe=85ec59cbc0) | May 22, 2021 |
| Gigabyte      | H170-D3HP-CF                | [6ceb83052e](https://linux-hardware.org/?probe=6ceb83052e) | May 20, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1b80ac0e66](https://linux-hardware.org/?probe=1b80ac0e66) | May 20, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0f9bda5ad3](https://linux-hardware.org/?probe=0f9bda5ad3) | May 20, 2021 |
| Gigabyte      | P67A-D3-B3                  | [5ce99f9c6f](https://linux-hardware.org/?probe=5ce99f9c6f) | May 20, 2021 |
| Dell          | 0GM819                      | [027f78ee12](https://linux-hardware.org/?probe=027f78ee12) | May 20, 2021 |
| Dell          | 0GM819                      | [bb967fb5bb](https://linux-hardware.org/?probe=bb967fb5bb) | May 20, 2021 |
| Gigabyte      | G41MT-S2PT                  | [58d9c32719](https://linux-hardware.org/?probe=58d9c32719) | May 19, 2021 |
| ASRock        | ConRoe1333-D667             | [604edea965](https://linux-hardware.org/?probe=604edea965) | May 18, 2021 |
| Gigabyte      | H61M-S1                     | [1237be5bd5](https://linux-hardware.org/?probe=1237be5bd5) | May 18, 2021 |
| ASUSTek       | M2N68-AM Plus               | [e77c8b3902](https://linux-hardware.org/?probe=e77c8b3902) | May 18, 2021 |
| ASUSTek       | M2N68-AM Plus               | [a74749d6f3](https://linux-hardware.org/?probe=a74749d6f3) | May 18, 2021 |
| Gigabyte      | M57SLI-S4                   | [deea9868fb](https://linux-hardware.org/?probe=deea9868fb) | May 17, 2021 |
| Gigabyte      | M57SLI-S4                   | [d08e69b682](https://linux-hardware.org/?probe=d08e69b682) | May 17, 2021 |
| ASRock        | ConRoe1333-D667             | [ed9780b501](https://linux-hardware.org/?probe=ed9780b501) | May 17, 2021 |
| Dell          | 08NPPY A00                  | [d6f702a0ce](https://linux-hardware.org/?probe=d6f702a0ce) | May 17, 2021 |
| ASUSTek       | H110M-R                     | [936833e558](https://linux-hardware.org/?probe=936833e558) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | 1850                        | [d6ecc0af75](https://linux-hardware.org/?probe=d6ecc0af75) | May 16, 2021 |
| HP            | 1850                        | [d5cc157212](https://linux-hardware.org/?probe=d5cc157212) | May 16, 2021 |
| MSI           | MS-7312                     | [46a65e835d](https://linux-hardware.org/?probe=46a65e835d) | May 16, 2021 |
| ASUSTek       | P9X79 WS                    | [71e296f6e0](https://linux-hardware.org/?probe=71e296f6e0) | May 15, 2021 |
| ASRock        | FM2A58M-DG3+                | [576cdc7dd6](https://linux-hardware.org/?probe=576cdc7dd6) | May 15, 2021 |
| ASRock        | FM2A58M-DG3+                | [2ab0d87daf](https://linux-hardware.org/?probe=2ab0d87daf) | May 15, 2021 |
| ASUSTek       | M2N-E                       | [5eb35e54f9](https://linux-hardware.org/?probe=5eb35e54f9) | May 14, 2021 |
| ASUSTek       | M2N-E                       | [6d079f811a](https://linux-hardware.org/?probe=6d079f811a) | May 14, 2021 |
| Dell          | 0KP561                      | [274ab22f81](https://linux-hardware.org/?probe=274ab22f81) | May 14, 2021 |
| Gigabyte      | P67A-D3-B3                  | [ef349fed80](https://linux-hardware.org/?probe=ef349fed80) | May 14, 2021 |
| HP            | 1850                        | [f9e407a1d9](https://linux-hardware.org/?probe=f9e407a1d9) | May 13, 2021 |
| ASUSTek       | H110M-A                     | [2321e20fe0](https://linux-hardware.org/?probe=2321e20fe0) | May 13, 2021 |
| ASUSTek       | H110M-A                     | [3802abcba6](https://linux-hardware.org/?probe=3802abcba6) | May 13, 2021 |
| HP            | 1850                        | [0a8a96f0b0](https://linux-hardware.org/?probe=0a8a96f0b0) | May 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | [3719049bcb](https://linux-hardware.org/?probe=3719049bcb) | May 13, 2021 |
| ASUSTek       | P5W DH Deluxe               | [7b73e4a20f](https://linux-hardware.org/?probe=7b73e4a20f) | May 11, 2021 |
| ASUSTek       | P5W DH Deluxe               | [e840ee6854](https://linux-hardware.org/?probe=e840ee6854) | May 11, 2021 |
| Lenovo        | NOK                         | [749127a8a5](https://linux-hardware.org/?probe=749127a8a5) | May 11, 2021 |
| HP            | 3029h                       | [4561c2b0c0](https://linux-hardware.org/?probe=4561c2b0c0) | May 11, 2021 |
| ASUSTek       | H110M-R                     | [6838dc41d6](https://linux-hardware.org/?probe=6838dc41d6) | May 09, 2021 |
| ASUSTek       | H110M-R                     | [e160ab52a1](https://linux-hardware.org/?probe=e160ab52a1) | May 09, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [aed3f5dadf](https://linux-hardware.org/?probe=aed3f5dadf) | May 09, 2021 |
| Acer          | Predator G3610              | [a32f68c5fd](https://linux-hardware.org/?probe=a32f68c5fd) | May 08, 2021 |
| Acer          | Predator G3610              | [e824f3cdd4](https://linux-hardware.org/?probe=e824f3cdd4) | May 08, 2021 |
| Acer          | RS880M05                    | [fb8f612ec3](https://linux-hardware.org/?probe=fb8f612ec3) | May 08, 2021 |
| Acer          | RS880M05                    | [089679ad9f](https://linux-hardware.org/?probe=089679ad9f) | May 08, 2021 |
| Intel         | DH55TC AAE70932-302         | [15ff525efc](https://linux-hardware.org/?probe=15ff525efc) | May 07, 2021 |
| ASRock        | G31M-GS                     | [6e383b2696](https://linux-hardware.org/?probe=6e383b2696) | May 07, 2021 |
| Gigabyte      | MZAPLBP-00                  | [7741641346](https://linux-hardware.org/?probe=7741641346) | May 07, 2021 |
| Intel         | DH55TC AAE70932-302         | [5ad81d36fd](https://linux-hardware.org/?probe=5ad81d36fd) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Dell          | 06D7TR A00                  | [9db6c930c1](https://linux-hardware.org/?probe=9db6c930c1) | May 06, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [4b74fbc44d](https://linux-hardware.org/?probe=4b74fbc44d) | May 06, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [63a05aa6f3](https://linux-hardware.org/?probe=63a05aa6f3) | May 06, 2021 |
| HP            | 3029h                       | [5e8b1106bc](https://linux-hardware.org/?probe=5e8b1106bc) | May 06, 2021 |
| ASUSTek       | A88X-PLUS                   | [b233d9d079](https://linux-hardware.org/?probe=b233d9d079) | May 05, 2021 |
| ASUSTek       | A88X-PLUS                   | [a8bfe32403](https://linux-hardware.org/?probe=a8bfe32403) | May 05, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [03938b1fb9](https://linux-hardware.org/?probe=03938b1fb9) | May 05, 2021 |
| ASUSTek       | A88X-PLUS                   | [ebe95650e8](https://linux-hardware.org/?probe=ebe95650e8) | May 05, 2021 |
| HP            | 3029h                       | [24e70a4120](https://linux-hardware.org/?probe=24e70a4120) | May 05, 2021 |
| Gigabyte      | GA-MA770-UD3                | [2f2e4e3ccc](https://linux-hardware.org/?probe=2f2e4e3ccc) | May 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | [5d43e628f4](https://linux-hardware.org/?probe=5d43e628f4) | May 04, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e9a6af506f](https://linux-hardware.org/?probe=e9a6af506f) | May 04, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [bbde3f1f35](https://linux-hardware.org/?probe=bbde3f1f35) | May 03, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [1235d21db0](https://linux-hardware.org/?probe=1235d21db0) | May 03, 2021 |
| Gigabyte      | G41MT-S2PT                  | [c2c5452b86](https://linux-hardware.org/?probe=c2c5452b86) | May 02, 2021 |
| Gigabyte      | H61M-D2-B3                  | [576f39167b](https://linux-hardware.org/?probe=576f39167b) | May 02, 2021 |
| ASRock        | FM2A68M-DG3+                | [56d18e1b25](https://linux-hardware.org/?probe=56d18e1b25) | May 02, 2021 |
| Gigabyte      | H61M-D2-B3                  | [db37873820](https://linux-hardware.org/?probe=db37873820) | May 02, 2021 |
| ASUSTek       | Maximus VII HERO            | [f91f457178](https://linux-hardware.org/?probe=f91f457178) | Apr 30, 2021 |
| ASUSTek       | Maximus VII HERO            | [9d47f4035f](https://linux-hardware.org/?probe=9d47f4035f) | Apr 30, 2021 |
| Gigabyte      | B450M GAMING                | [ec0806feff](https://linux-hardware.org/?probe=ec0806feff) | Apr 29, 2021 |
| Gigabyte      | B450M GAMING                | [d7bdd00101](https://linux-hardware.org/?probe=d7bdd00101) | Apr 29, 2021 |
| Gigabyte      | H310M S2H x.x               | [4260340e8d](https://linux-hardware.org/?probe=4260340e8d) | Apr 29, 2021 |
| HP            | 1494                        | [a79136c0eb](https://linux-hardware.org/?probe=a79136c0eb) | Apr 29, 2021 |
| Lenovo        | NO DPK                      | [d6273dfd6c](https://linux-hardware.org/?probe=d6273dfd6c) | Apr 28, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d4a67740c8](https://linux-hardware.org/?probe=d4a67740c8) | Apr 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [ce8423f26b](https://linux-hardware.org/?probe=ce8423f26b) | Apr 26, 2021 |
| Gigabyte      | P67A-D3-B3                  | [b1082ac003](https://linux-hardware.org/?probe=b1082ac003) | Apr 26, 2021 |
| ASRock        | FM2A75M Pro4+               | [d3c1bab446](https://linux-hardware.org/?probe=d3c1bab446) | Apr 25, 2021 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [59d1a825fd](https://linux-hardware.org/?probe=59d1a825fd) | Apr 25, 2021 |
| Dell          | 0HY9JP A02                  | [15562c77d6](https://linux-hardware.org/?probe=15562c77d6) | Apr 25, 2021 |
| Dell          | 0HY9JP A02                  | [dea97d53d2](https://linux-hardware.org/?probe=dea97d53d2) | Apr 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [8a607b7d4e](https://linux-hardware.org/?probe=8a607b7d4e) | Apr 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [5116c82924](https://linux-hardware.org/?probe=5116c82924) | Apr 25, 2021 |
| ASUSTek       | PRIME H410M-R               | [8bdbfb46b1](https://linux-hardware.org/?probe=8bdbfb46b1) | Apr 25, 2021 |
| ASUSTek       | H81M-D                      | [6eecc39763](https://linux-hardware.org/?probe=6eecc39763) | Apr 25, 2021 |
| ASUSTek       | H81M-D                      | [a4d0fd5ce8](https://linux-hardware.org/?probe=a4d0fd5ce8) | Apr 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8afd041673](https://linux-hardware.org/?probe=8afd041673) | Apr 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [c3df47b276](https://linux-hardware.org/?probe=c3df47b276) | Apr 25, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [f6e266a897](https://linux-hardware.org/?probe=f6e266a897) | Apr 25, 2021 |
| Gigabyte      | G41MT-S2PT                  | [79c635f579](https://linux-hardware.org/?probe=79c635f579) | Apr 24, 2021 |
| Gigabyte      | P67A-D3-B3                  | [b40232d837](https://linux-hardware.org/?probe=b40232d837) | Apr 23, 2021 |
| Gigabyte      | G41M-ES2L                   | [d388bb85a4](https://linux-hardware.org/?probe=d388bb85a4) | Apr 23, 2021 |
| Gigabyte      | G41M-ES2L                   | [3cb9983956](https://linux-hardware.org/?probe=3cb9983956) | Apr 23, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [fb58321498](https://linux-hardware.org/?probe=fb58321498) | Apr 23, 2021 |
| ASUSTek       | H110M-A                     | [73a64cf6c3](https://linux-hardware.org/?probe=73a64cf6c3) | Apr 22, 2021 |
| ASRock        | FM2A75M Pro4+               | [07e689fbd8](https://linux-hardware.org/?probe=07e689fbd8) | Apr 22, 2021 |
| ASUSTek       | H110M-A                     | [50e5360b19](https://linux-hardware.org/?probe=50e5360b19) | Apr 21, 2021 |
| Gigabyte      | H170-D3HP-CF                | [c970ef4e84](https://linux-hardware.org/?probe=c970ef4e84) | Apr 21, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0329d04e62](https://linux-hardware.org/?probe=0329d04e62) | Apr 20, 2021 |
| ASRock        | H87M                        | [1155908299](https://linux-hardware.org/?probe=1155908299) | Apr 20, 2021 |
| ASRock        | H87M                        | [fc2678ea38](https://linux-hardware.org/?probe=fc2678ea38) | Apr 20, 2021 |
| Dell          | 06D7TR A00                  | [907d14ed71](https://linux-hardware.org/?probe=907d14ed71) | Apr 20, 2021 |
| ASRock        | A320M-HDV R3.0              | [b4ca18e121](https://linux-hardware.org/?probe=b4ca18e121) | Apr 20, 2021 |
| ECS           | GLKM-MINI                   | [11d8fcf22b](https://linux-hardware.org/?probe=11d8fcf22b) | Apr 19, 2021 |
| ASRock        | FM2A75M Pro4+               | [41234fe11d](https://linux-hardware.org/?probe=41234fe11d) | Apr 19, 2021 |
| ASRock        | FM2A75M Pro4+               | [63c88adcb4](https://linux-hardware.org/?probe=63c88adcb4) | Apr 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [d1ab6c5ca5](https://linux-hardware.org/?probe=d1ab6c5ca5) | Apr 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [5addce194b](https://linux-hardware.org/?probe=5addce194b) | Apr 19, 2021 |
| MSI           | B75MA-P33                   | [5db26fac48](https://linux-hardware.org/?probe=5db26fac48) | Apr 18, 2021 |
| Gigabyte      | H61M-S1                     | [fbf399c3f2](https://linux-hardware.org/?probe=fbf399c3f2) | Apr 18, 2021 |
| Gigabyte      | H61M-S1                     | [aebada7ba5](https://linux-hardware.org/?probe=aebada7ba5) | Apr 18, 2021 |
| Acer          | Aspire X1935                | [95f1a36a27](https://linux-hardware.org/?probe=95f1a36a27) | Apr 18, 2021 |
| Acer          | Aspire X1935                | [7b73b9a448](https://linux-hardware.org/?probe=7b73b9a448) | Apr 18, 2021 |
| MSI           | Z97 GAMING 5                | [254c55fa75](https://linux-hardware.org/?probe=254c55fa75) | Apr 18, 2021 |
| Lenovo        | NOK                         | [c88ecfeb5c](https://linux-hardware.org/?probe=c88ecfeb5c) | Apr 18, 2021 |
| ASUSTek       | P7P55D-E                    | [11cbb7255a](https://linux-hardware.org/?probe=11cbb7255a) | Apr 18, 2021 |
| ASUSTek       | H110M-A                     | [b0851fa73e](https://linux-hardware.org/?probe=b0851fa73e) | Apr 18, 2021 |
| ASUSTek       | H110M-A                     | [974505179e](https://linux-hardware.org/?probe=974505179e) | Apr 17, 2021 |
| Gigabyte      | B450M S2H                   | [5777c5cd05](https://linux-hardware.org/?probe=5777c5cd05) | Apr 17, 2021 |
| Pegatron      | 2AB6                        | [24bc39e404](https://linux-hardware.org/?probe=24bc39e404) | Apr 15, 2021 |
| ASRock        | FM2A88M Extreme4+           | [4d012c7f4f](https://linux-hardware.org/?probe=4d012c7f4f) | Apr 15, 2021 |
| ASRock        | FM2A88M Extreme4+           | [ef36b6826b](https://linux-hardware.org/?probe=ef36b6826b) | Apr 15, 2021 |
| Dell          | 00V62H A01                  | [57eda985a5](https://linux-hardware.org/?probe=57eda985a5) | Apr 15, 2021 |
| Dell          | 00V62H A01                  | [421e94fefc](https://linux-hardware.org/?probe=421e94fefc) | Apr 15, 2021 |
| ASRock        | FM2A58M-HD+ R2.0            | [9166558a28](https://linux-hardware.org/?probe=9166558a28) | Apr 15, 2021 |
| ASUSTek       | P7P55D-E                    | [de55e1fa15](https://linux-hardware.org/?probe=de55e1fa15) | Apr 15, 2021 |
| ASUSTek       | P7P55D-E                    | [f098e54295](https://linux-hardware.org/?probe=f098e54295) | Apr 15, 2021 |
| Gigabyte      | B360M D3H-CF                | [cb623f42c8](https://linux-hardware.org/?probe=cb623f42c8) | Apr 14, 2021 |
| ASUSTek       | P5QL-E                      | [8c2bad9def](https://linux-hardware.org/?probe=8c2bad9def) | Apr 14, 2021 |
| Gigabyte      | G41MT-S2PT                  | [36e85f5028](https://linux-hardware.org/?probe=36e85f5028) | Apr 14, 2021 |
| Fujitsu Si... | D2679-A1 S26361-D2679-Ax... | [7b01144675](https://linux-hardware.org/?probe=7b01144675) | Apr 14, 2021 |
| ASRock        | FM2A88M Extreme4+           | [208222668f](https://linux-hardware.org/?probe=208222668f) | Apr 13, 2021 |
| ASRock        | FM2A88M Extreme4+           | [4fb060e44b](https://linux-hardware.org/?probe=4fb060e44b) | Apr 13, 2021 |
| Dell          | 0M863N A00                  | [886b00db8f](https://linux-hardware.org/?probe=886b00db8f) | Apr 13, 2021 |
| Dell          | 0M863N A00                  | [c6e44b31d8](https://linux-hardware.org/?probe=c6e44b31d8) | Apr 13, 2021 |
| HP            | 3029h                       | [99d4aeee25](https://linux-hardware.org/?probe=99d4aeee25) | Apr 13, 2021 |
| ASUSTek       | P8P67 LE                    | [77a21fd6d4](https://linux-hardware.org/?probe=77a21fd6d4) | Apr 12, 2021 |
| Gigabyte      | B450M GAMING                | [486ccccca8](https://linux-hardware.org/?probe=486ccccca8) | Apr 12, 2021 |
| Gigabyte      | B450M GAMING                | [f422751dcb](https://linux-hardware.org/?probe=f422751dcb) | Apr 12, 2021 |
| ASRock        | FM2A58M-DG3+                | [5a0e980c67](https://linux-hardware.org/?probe=5a0e980c67) | Apr 12, 2021 |
| ASRock        | FM2A58M-DG3+                | [77c3105590](https://linux-hardware.org/?probe=77c3105590) | Apr 12, 2021 |
| Medion        | B75MA-P45                   | [1def72a934](https://linux-hardware.org/?probe=1def72a934) | Apr 12, 2021 |
| Gigabyte      | G41MT-S2PT                  | [234051e81a](https://linux-hardware.org/?probe=234051e81a) | Apr 11, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [42111c7f31](https://linux-hardware.org/?probe=42111c7f31) | Apr 11, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [8f18113228](https://linux-hardware.org/?probe=8f18113228) | Apr 11, 2021 |
| HP            | 3029h                       | [dc37ffe8c1](https://linux-hardware.org/?probe=dc37ffe8c1) | Apr 11, 2021 |
| HP            | 3029h                       | [d5ccc89bde](https://linux-hardware.org/?probe=d5ccc89bde) | Apr 11, 2021 |
| HP            | 3029h                       | [fb9eb25a60](https://linux-hardware.org/?probe=fb9eb25a60) | Apr 10, 2021 |
| ASUSTek       | P7P55D                      | [6dcd3425df](https://linux-hardware.org/?probe=6dcd3425df) | Apr 10, 2021 |
| ASUSTek       | P7P55D                      | [88195af133](https://linux-hardware.org/?probe=88195af133) | Apr 10, 2021 |
| Gigabyte      | EG41MFT-US2H                | [d65c720c55](https://linux-hardware.org/?probe=d65c720c55) | Apr 10, 2021 |
| Gigabyte      | EG41MFT-US2H                | [a195ef1fc9](https://linux-hardware.org/?probe=a195ef1fc9) | Apr 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b89d1f443a](https://linux-hardware.org/?probe=b89d1f443a) | Apr 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [406e2c08d2](https://linux-hardware.org/?probe=406e2c08d2) | Apr 10, 2021 |
| Gigabyte      | P35-S3G                     | [05eea3dc23](https://linux-hardware.org/?probe=05eea3dc23) | Apr 09, 2021 |
| Gigabyte      | P35-S3G                     | [3275d12a5b](https://linux-hardware.org/?probe=3275d12a5b) | Apr 09, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [17192d4f10](https://linux-hardware.org/?probe=17192d4f10) | Apr 09, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [7b26933952](https://linux-hardware.org/?probe=7b26933952) | Apr 09, 2021 |
| Gigabyte      | H81M-S1                     | [2c5c543960](https://linux-hardware.org/?probe=2c5c543960) | Apr 08, 2021 |
| ASUSTek       | A8V-VM SE                   | [d58077c2d7](https://linux-hardware.org/?probe=d58077c2d7) | Apr 08, 2021 |
| ASUSTek       | A8V-VM SE                   | [02c4f1df7c](https://linux-hardware.org/?probe=02c4f1df7c) | Apr 08, 2021 |
| Gigabyte      | H81M-S1                     | [317db0318e](https://linux-hardware.org/?probe=317db0318e) | Apr 08, 2021 |
| Dell          | 0PU052                      | [a9116acf5f](https://linux-hardware.org/?probe=a9116acf5f) | Apr 07, 2021 |
| Dell          | 0PU052                      | [26560b13ed](https://linux-hardware.org/?probe=26560b13ed) | Apr 07, 2021 |
| Dell          | 0TY915                      | [e7c2c731b4](https://linux-hardware.org/?probe=e7c2c731b4) | Apr 06, 2021 |
| Dell          | 0782GW A00                  | [e06d5efa51](https://linux-hardware.org/?probe=e06d5efa51) | Apr 06, 2021 |
| Dell          | 0TY915                      | [0cf451f67e](https://linux-hardware.org/?probe=0cf451f67e) | Apr 06, 2021 |
| Dell          | 0782GW A00                  | [46ef14cb8c](https://linux-hardware.org/?probe=46ef14cb8c) | Apr 06, 2021 |
| Gigabyte      | P35-S3G                     | [7b63b052fa](https://linux-hardware.org/?probe=7b63b052fa) | Apr 05, 2021 |
| Lenovo        | NOK                         | [44bc5dede4](https://linux-hardware.org/?probe=44bc5dede4) | Apr 05, 2021 |
| ASRock        | H61M-VG4                    | [be17bb94cd](https://linux-hardware.org/?probe=be17bb94cd) | Apr 05, 2021 |
| ASRock        | H61M-VG4                    | [2953886a5e](https://linux-hardware.org/?probe=2953886a5e) | Apr 05, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b3258924a5](https://linux-hardware.org/?probe=b3258924a5) | Apr 05, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [45e695016d](https://linux-hardware.org/?probe=45e695016d) | Apr 05, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [cfaa22a0a1](https://linux-hardware.org/?probe=cfaa22a0a1) | Apr 05, 2021 |
| ASUSTek       | P5G41-M SI/DVI              | [9f40039537](https://linux-hardware.org/?probe=9f40039537) | Apr 05, 2021 |
| ASRock        | FM2A88M Extreme4+           | [e016cdbbd0](https://linux-hardware.org/?probe=e016cdbbd0) | Apr 04, 2021 |
| ASRock        | G31M-GS                     | [27466fa593](https://linux-hardware.org/?probe=27466fa593) | Apr 04, 2021 |
| Fujitsu Si... | P5GD1-FM                    | [d82ece259f](https://linux-hardware.org/?probe=d82ece259f) | Apr 04, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [2bf102b13f](https://linux-hardware.org/?probe=2bf102b13f) | Apr 04, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [2d7543cf2f](https://linux-hardware.org/?probe=2d7543cf2f) | Apr 04, 2021 |
| ASUSTek       | P7P55D-E                    | [e023fc9987](https://linux-hardware.org/?probe=e023fc9987) | Apr 04, 2021 |
| MSI           | MS-7267                     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [4360090c45](https://linux-hardware.org/?probe=4360090c45) | Apr 02, 2021 |
| Dell          | 0782GW A00                  | [de98ed0c81](https://linux-hardware.org/?probe=de98ed0c81) | Apr 02, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [56863bbca2](https://linux-hardware.org/?probe=56863bbca2) | Apr 02, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [3585968a8e](https://linux-hardware.org/?probe=3585968a8e) | Apr 02, 2021 |
| Dell          | 0782GW A00                  | [4095cea800](https://linux-hardware.org/?probe=4095cea800) | Apr 02, 2021 |
| HP            | 0A68h                       | [c0e4be6882](https://linux-hardware.org/?probe=c0e4be6882) | Apr 02, 2021 |
| ASRock        | FM2A68M-DG3+                | [866d3a499f](https://linux-hardware.org/?probe=866d3a499f) | Apr 02, 2021 |
| ASRock        | FM2A68M-DG3+                | [65a6eb9037](https://linux-hardware.org/?probe=65a6eb9037) | Apr 02, 2021 |
| ASUSTek       | P7P55D-E                    | [b304fab7e4](https://linux-hardware.org/?probe=b304fab7e4) | Apr 02, 2021 |
| HP            | 0A68h                       | [ff7a007a64](https://linux-hardware.org/?probe=ff7a007a64) | Apr 01, 2021 |
| ASUSTek       | H110M-K                     | [b87f9e09e8](https://linux-hardware.org/?probe=b87f9e09e8) | Apr 01, 2021 |
| MSI           | MS-1672 Ver                 | [c630018fea](https://linux-hardware.org/?probe=c630018fea) | Mar 31, 2021 |
| MSI           | MS-1672 Ver                 | [d72651aaf4](https://linux-hardware.org/?probe=d72651aaf4) | Mar 31, 2021 |
| HP            | 3646h                       | [833b887480](https://linux-hardware.org/?probe=833b887480) | Mar 30, 2021 |
| HP            | 3646h                       | [e01de4d7fb](https://linux-hardware.org/?probe=e01de4d7fb) | Mar 30, 2021 |
| Lenovo        | Board                       | [83ecde57ce](https://linux-hardware.org/?probe=83ecde57ce) | Mar 29, 2021 |
| ASRock        | FM2A68M-DG3+                | [34e4e7b02f](https://linux-hardware.org/?probe=34e4e7b02f) | Mar 29, 2021 |
| Lenovo        | Board                       | [f1d87d3603](https://linux-hardware.org/?probe=f1d87d3603) | Mar 29, 2021 |
| ASUSTek       | Z170-K                      | [48b797e6b3](https://linux-hardware.org/?probe=48b797e6b3) | Mar 29, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [fa7f30a3be](https://linux-hardware.org/?probe=fa7f30a3be) | Mar 29, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [001ac1cd06](https://linux-hardware.org/?probe=001ac1cd06) | Mar 29, 2021 |
| MSI           | H61M-P22                    | [c37830a039](https://linux-hardware.org/?probe=c37830a039) | Mar 28, 2021 |
| MSI           | H61M-P22                    | [be1952aa88](https://linux-hardware.org/?probe=be1952aa88) | Mar 28, 2021 |
| MSI           | H61M-P22                    | [a2e0ed316a](https://linux-hardware.org/?probe=a2e0ed316a) | Mar 28, 2021 |
| ASRock        | FM2A68M-DG3+                | [aea274cf47](https://linux-hardware.org/?probe=aea274cf47) | Mar 28, 2021 |
| HP            | 1497                        | [9372e381c6](https://linux-hardware.org/?probe=9372e381c6) | Mar 28, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [e38d164fe9](https://linux-hardware.org/?probe=e38d164fe9) | Mar 28, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [10dba5a903](https://linux-hardware.org/?probe=10dba5a903) | Mar 28, 2021 |
| MSI           | H61M-P22                    | [9b8a067f4c](https://linux-hardware.org/?probe=9b8a067f4c) | Mar 28, 2021 |
| HP            | 1850                        | [0740682409](https://linux-hardware.org/?probe=0740682409) | Mar 28, 2021 |
| HP            | 1850                        | [500206d11d](https://linux-hardware.org/?probe=500206d11d) | Mar 28, 2021 |
| HP            | 1850                        | [2551c21895](https://linux-hardware.org/?probe=2551c21895) | Mar 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0faec227c9](https://linux-hardware.org/?probe=0faec227c9) | Mar 27, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [add6a586b3](https://linux-hardware.org/?probe=add6a586b3) | Mar 27, 2021 |
| ASUSTek       | H61M-K                      | [766fff8092](https://linux-hardware.org/?probe=766fff8092) | Mar 27, 2021 |
| ASUSTek       | H61M-K                      | [72e7d5ad88](https://linux-hardware.org/?probe=72e7d5ad88) | Mar 27, 2021 |
| ASUSTek       | P7P55D-E                    | [3128c1e8f5](https://linux-hardware.org/?probe=3128c1e8f5) | Mar 27, 2021 |
| Dell          | 042P49 A02                  | [d48888aa81](https://linux-hardware.org/?probe=d48888aa81) | Mar 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | [beb277f702](https://linux-hardware.org/?probe=beb277f702) | Mar 26, 2021 |
| HP            | 0A68h                       | [c2fe41a3be](https://linux-hardware.org/?probe=c2fe41a3be) | Mar 26, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [6c084e841c](https://linux-hardware.org/?probe=6c084e841c) | Mar 26, 2021 |
| ASUSTek       | P7P55D-E                    | [ff00d307f8](https://linux-hardware.org/?probe=ff00d307f8) | Mar 26, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [fc7a17a532](https://linux-hardware.org/?probe=fc7a17a532) | Mar 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | [6c94eca4d8](https://linux-hardware.org/?probe=6c94eca4d8) | Mar 26, 2021 |
| HP            | 0A68h                       | [dcbdfe3c5a](https://linux-hardware.org/?probe=dcbdfe3c5a) | Mar 26, 2021 |
| Medion        | B75MA-P45                   | [983d186655](https://linux-hardware.org/?probe=983d186655) | Mar 25, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f433b76235](https://linux-hardware.org/?probe=f433b76235) | Mar 24, 2021 |
| MSI           | A320M PRO-VD/S              | [ec282075ee](https://linux-hardware.org/?probe=ec282075ee) | Mar 23, 2021 |
| Dell          | 0PU052                      | [ba513ddcba](https://linux-hardware.org/?probe=ba513ddcba) | Mar 22, 2021 |
| Dell          | 0PU052                      | [78fe8701c5](https://linux-hardware.org/?probe=78fe8701c5) | Mar 22, 2021 |
| Medion        | B75MA-P45                   | [f912bc6023](https://linux-hardware.org/?probe=f912bc6023) | Mar 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [121278ea8f](https://linux-hardware.org/?probe=121278ea8f) | Mar 22, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [fe7b25a75f](https://linux-hardware.org/?probe=fe7b25a75f) | Mar 21, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [dd3488f2d2](https://linux-hardware.org/?probe=dd3488f2d2) | Mar 21, 2021 |
| Dell          | 0TY915                      | [d34cf6173e](https://linux-hardware.org/?probe=d34cf6173e) | Mar 20, 2021 |
| ASRock        | H110 Pro BTC+               | [a2f1801155](https://linux-hardware.org/?probe=a2f1801155) | Mar 20, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [6ee42938bc](https://linux-hardware.org/?probe=6ee42938bc) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E                    | [f55ed3635d](https://linux-hardware.org/?probe=f55ed3635d) | Mar 20, 2021 |
| ASRock        | FM2A55M-HD+                 | [6388310990](https://linux-hardware.org/?probe=6388310990) | Mar 20, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f813e5a50c](https://linux-hardware.org/?probe=f813e5a50c) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E                    | [9be22e85c5](https://linux-hardware.org/?probe=9be22e85c5) | Mar 19, 2021 |
| Lenovo        | Board                       | [25d3957f6d](https://linux-hardware.org/?probe=25d3957f6d) | Mar 19, 2021 |
| Lenovo        | Board                       | [a0b02b6653](https://linux-hardware.org/?probe=a0b02b6653) | Mar 19, 2021 |
| Dell          | 0KP561                      | [e4cb77ed6f](https://linux-hardware.org/?probe=e4cb77ed6f) | Mar 19, 2021 |
| HP            | 339A                        | [12cb32a420](https://linux-hardware.org/?probe=12cb32a420) | Mar 19, 2021 |
| MSI           | B85M-P32                    | [f8c9f3c56e](https://linux-hardware.org/?probe=f8c9f3c56e) | Mar 19, 2021 |
| MSI           | B85M-P32                    | [4caa328712](https://linux-hardware.org/?probe=4caa328712) | Mar 19, 2021 |
| Gigabyte      | B450M GAMING                | [6ff25934f6](https://linux-hardware.org/?probe=6ff25934f6) | Mar 18, 2021 |
| Gigabyte      | B450M GAMING                | [44fa4dbc87](https://linux-hardware.org/?probe=44fa4dbc87) | Mar 18, 2021 |
| MSI           | 2A9Ch                       | [f1c12e8608](https://linux-hardware.org/?probe=f1c12e8608) | Mar 18, 2021 |
| MSI           | 2A9Ch                       | [2a341c1c24](https://linux-hardware.org/?probe=2a341c1c24) | Mar 18, 2021 |
| Dell          | 0M5DCD A00                  | [3002b8f729](https://linux-hardware.org/?probe=3002b8f729) | Mar 18, 2021 |
| Dell          | 0M5DCD A00                  | [ade377ef77](https://linux-hardware.org/?probe=ade377ef77) | Mar 18, 2021 |
| MSI           | B85M-P32                    | [1f44fd70b7](https://linux-hardware.org/?probe=1f44fd70b7) | Mar 18, 2021 |
| MSI           | B85M-P32                    | [99bdc6f9ba](https://linux-hardware.org/?probe=99bdc6f9ba) | Mar 18, 2021 |
| ASRock        | H61M-VG3                    | [d64d38cec9](https://linux-hardware.org/?probe=d64d38cec9) | Mar 17, 2021 |
| ASRock        | H61M-VG3                    | [a38af98605](https://linux-hardware.org/?probe=a38af98605) | Mar 17, 2021 |
| ASUSTek       | AM1M-A                      | [232097c5c8](https://linux-hardware.org/?probe=232097c5c8) | Mar 17, 2021 |
| ASUSTek       | P7P55D-E                    | [8d0393f186](https://linux-hardware.org/?probe=8d0393f186) | Mar 17, 2021 |
| ASUSTek       | P7P55D-E                    | [3937d6a2c4](https://linux-hardware.org/?probe=3937d6a2c4) | Mar 17, 2021 |
| HP            | 3031h                       | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASRock        | G31M-VS                     | [ccfde471fd](https://linux-hardware.org/?probe=ccfde471fd) | Mar 16, 2021 |
| ASUSTek       | P7P55D-E                    | [4d140e1fc4](https://linux-hardware.org/?probe=4d140e1fc4) | Mar 16, 2021 |
| ASUSTek       | P7P55D-E                    | [4e9a574f95](https://linux-hardware.org/?probe=4e9a574f95) | Mar 16, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [23ff636844](https://linux-hardware.org/?probe=23ff636844) | Mar 16, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2623d35ade](https://linux-hardware.org/?probe=2623d35ade) | Mar 15, 2021 |
| Dell          | 0R230R A00                  | [0d46e69761](https://linux-hardware.org/?probe=0d46e69761) | Mar 15, 2021 |
| Dell          | 0R230R A00                  | [9e4df7146e](https://linux-hardware.org/?probe=9e4df7146e) | Mar 15, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [c55a1dd601](https://linux-hardware.org/?probe=c55a1dd601) | Mar 15, 2021 |
| ASUSTek       | P7P55D-E                    | [d3d6f2124c](https://linux-hardware.org/?probe=d3d6f2124c) | Mar 15, 2021 |
| Dell          | 0R230R A00                  | [c9ed22f4eb](https://linux-hardware.org/?probe=c9ed22f4eb) | Mar 15, 2021 |
| Dell          | 0R230R A00                  | [6c49839368](https://linux-hardware.org/?probe=6c49839368) | Mar 15, 2021 |
| ASUSTek       | P7P55D-E                    | [4a94e043ee](https://linux-hardware.org/?probe=4a94e043ee) | Mar 15, 2021 |
| Gigabyte      | G31M-ES2L                   | [486007a1f1](https://linux-hardware.org/?probe=486007a1f1) | Mar 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [c2283c8b91](https://linux-hardware.org/?probe=c2283c8b91) | Mar 14, 2021 |
| ASUSTek       | P5G41-M SI/DVI              | [842365a9e6](https://linux-hardware.org/?probe=842365a9e6) | Mar 14, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [53069dd8e1](https://linux-hardware.org/?probe=53069dd8e1) | Mar 14, 2021 |
| Gigabyte      | B450M GAMING                | [3c3b4f92c5](https://linux-hardware.org/?probe=3c3b4f92c5) | Mar 14, 2021 |
| Gigabyte      | B450M GAMING                | [0c1f29fbb3](https://linux-hardware.org/?probe=0c1f29fbb3) | Mar 14, 2021 |
| Dell          | 0HN7XN A00                  | [23ea37daa8](https://linux-hardware.org/?probe=23ea37daa8) | Mar 14, 2021 |
| Dell          | 0HN7XN A00                  | [e39b2292a9](https://linux-hardware.org/?probe=e39b2292a9) | Mar 14, 2021 |
| Medion        | B75MA-P45                   | [52718d996a](https://linux-hardware.org/?probe=52718d996a) | Mar 14, 2021 |
| Medion        | B75MA-P45                   | [12b5da8990](https://linux-hardware.org/?probe=12b5da8990) | Mar 14, 2021 |
| Gigabyte      | H61M-S1                     | [099abf0789](https://linux-hardware.org/?probe=099abf0789) | Mar 13, 2021 |
| ASUSTek       | TUF GAMING B450M-PRO II     | [531005b30b](https://linux-hardware.org/?probe=531005b30b) | Mar 13, 2021 |
| MSI           | B450I GAMING PLUS AC        | [118b74b50e](https://linux-hardware.org/?probe=118b74b50e) | Mar 13, 2021 |
| Dell          | 0XPDFK A00                  | [7f05c0b214](https://linux-hardware.org/?probe=7f05c0b214) | Mar 12, 2021 |
| ASUSTek       | P-P5G41                     | [ff6aa83006](https://linux-hardware.org/?probe=ff6aa83006) | Mar 12, 2021 |
| HP            | 8299                        | [9963fbf8ca](https://linux-hardware.org/?probe=9963fbf8ca) | Mar 12, 2021 |
| ASRock        | G31M-S                      | [2b7f8c8404](https://linux-hardware.org/?probe=2b7f8c8404) | Mar 12, 2021 |
| Dell          | 04YP6J A02                  | [c8792cd53b](https://linux-hardware.org/?probe=c8792cd53b) | Mar 11, 2021 |
| ASUSTek       | P-P5G41                     | [a5c166847a](https://linux-hardware.org/?probe=a5c166847a) | Mar 11, 2021 |
| Lenovo        | Board                       | [b18ebb71d3](https://linux-hardware.org/?probe=b18ebb71d3) | Mar 11, 2021 |
| Lenovo        | Board                       | [53c9925296](https://linux-hardware.org/?probe=53c9925296) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [5d4a9de827](https://linux-hardware.org/?probe=5d4a9de827) | Mar 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [b17e775d08](https://linux-hardware.org/?probe=b17e775d08) | Mar 10, 2021 |
| Gigabyte      | H61M-S1                     | [f183028883](https://linux-hardware.org/?probe=f183028883) | Mar 10, 2021 |
| Dell          | 0XPDFK A00                  | [f3530946b9](https://linux-hardware.org/?probe=f3530946b9) | Mar 10, 2021 |
| Medion        | B75MA-P45                   | [1def29e83d](https://linux-hardware.org/?probe=1def29e83d) | Mar 10, 2021 |
| Dell          | 0GY6Y8 A01                  | [146e780e40](https://linux-hardware.org/?probe=146e780e40) | Mar 09, 2021 |
| ASRock        | FM2A88X Extreme4+           | [043ee03fa9](https://linux-hardware.org/?probe=043ee03fa9) | Mar 09, 2021 |
| Gigabyte      | H61M-S1                     | [1b3ab8cd56](https://linux-hardware.org/?probe=1b3ab8cd56) | Mar 09, 2021 |
| ASUSTek       | P7P55D-E                    | [2016a58d64](https://linux-hardware.org/?probe=2016a58d64) | Mar 09, 2021 |
| Unknown       | 775i915P-SATA2              | [1ea5a05d39](https://linux-hardware.org/?probe=1ea5a05d39) | Mar 09, 2021 |
| ASUSTek       | P7P55D-E                    | [1fee7762fb](https://linux-hardware.org/?probe=1fee7762fb) | Mar 09, 2021 |
| Medion        | B75MA-P45                   | [c57fee9bfa](https://linux-hardware.org/?probe=c57fee9bfa) | Mar 09, 2021 |
| ASRock        | FM2A75M Pro4+               | [abdb93f81d](https://linux-hardware.org/?probe=abdb93f81d) | Mar 09, 2021 |
| ASRock        | FM2A75M Pro4+               | [3033b2cec8](https://linux-hardware.org/?probe=3033b2cec8) | Mar 08, 2021 |
| Gigabyte      | H61M-S1                     | [3a07fa5f91](https://linux-hardware.org/?probe=3a07fa5f91) | Mar 08, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [18208ab02a](https://linux-hardware.org/?probe=18208ab02a) | Mar 08, 2021 |
| ASUSTek       | P8H77-V LE                  | [6a540a3e0a](https://linux-hardware.org/?probe=6a540a3e0a) | Mar 08, 2021 |
| ASUSTek       | P8H77-V LE                  | [48b282d4c6](https://linux-hardware.org/?probe=48b282d4c6) | Mar 08, 2021 |
| Gigabyte      | Z370 HD3P-CF                | [987afdd30b](https://linux-hardware.org/?probe=987afdd30b) | Mar 08, 2021 |
| Gigabyte      | P67A-D3-B3                  | [26c93a46fd](https://linux-hardware.org/?probe=26c93a46fd) | Mar 08, 2021 |
| Dell          | 0R64DJ A00                  | [fd717d72f0](https://linux-hardware.org/?probe=fd717d72f0) | Mar 07, 2021 |
| Dell          | 0R64DJ A00                  | [d8fce99678](https://linux-hardware.org/?probe=d8fce99678) | Mar 07, 2021 |
| ASRock        | 960GM-VGS3 FX               | [a9e44e7341](https://linux-hardware.org/?probe=a9e44e7341) | Mar 07, 2021 |
| ASRock        | 960GM-VGS3 FX               | [60f46c5a79](https://linux-hardware.org/?probe=60f46c5a79) | Mar 07, 2021 |
| Gigabyte      | P61-USB3-B3                 | [ba1ff74c2f](https://linux-hardware.org/?probe=ba1ff74c2f) | Mar 07, 2021 |
| Gigabyte      | P67A-D3-B3                  | [bccb1818c0](https://linux-hardware.org/?probe=bccb1818c0) | Mar 07, 2021 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [2dc8e6ca3c](https://linux-hardware.org/?probe=2dc8e6ca3c) | Mar 07, 2021 |
| Gigabyte      | P61-USB3-B3                 | [6edd9b32e5](https://linux-hardware.org/?probe=6edd9b32e5) | Mar 07, 2021 |
| Gigabyte      | P61-USB3-B3                 | [3b2bc457d4](https://linux-hardware.org/?probe=3b2bc457d4) | Mar 06, 2021 |
| Gigabyte      | B75-D3V                     | [f9b9af98d9](https://linux-hardware.org/?probe=f9b9af98d9) | Mar 06, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [bfed440ce0](https://linux-hardware.org/?probe=bfed440ce0) | Mar 06, 2021 |
| Lenovo        | Board                       | [96cb8ca55d](https://linux-hardware.org/?probe=96cb8ca55d) | Mar 06, 2021 |
| HP            | 3029h                       | [fce9f4d879](https://linux-hardware.org/?probe=fce9f4d879) | Mar 05, 2021 |
| HP            | 3029h                       | [bb440e1164](https://linux-hardware.org/?probe=bb440e1164) | Mar 05, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [e14e02e2c4](https://linux-hardware.org/?probe=e14e02e2c4) | Mar 05, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [f5e8a2f432](https://linux-hardware.org/?probe=f5e8a2f432) | Mar 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | [5b8d2aedbf](https://linux-hardware.org/?probe=5b8d2aedbf) | Mar 05, 2021 |
| HP            | 1495                        | [224a2e7834](https://linux-hardware.org/?probe=224a2e7834) | Mar 05, 2021 |
| HP            | 1495                        | [e532c3854a](https://linux-hardware.org/?probe=e532c3854a) | Mar 05, 2021 |
| HP            | 3029h                       | [8ee3ab9d3e](https://linux-hardware.org/?probe=8ee3ab9d3e) | Mar 05, 2021 |
| Gigabyte      | P61-USB3-B3                 | [01cad6c748](https://linux-hardware.org/?probe=01cad6c748) | Mar 05, 2021 |
| ASRock        | AB350M-HDV R3.0             | [36d6c1f0ed](https://linux-hardware.org/?probe=36d6c1f0ed) | Mar 04, 2021 |
| Gigabyte      | B360N WIFI-CF               | [a85b058510](https://linux-hardware.org/?probe=a85b058510) | Mar 04, 2021 |
| ASUSTek       | P7P55D-E                    | [c3ace4f3b5](https://linux-hardware.org/?probe=c3ace4f3b5) | Mar 04, 2021 |
| ASUSTek       | P7P55D-E                    | [2865207935](https://linux-hardware.org/?probe=2865207935) | Mar 04, 2021 |
| Acer          | RS880M05                    | [fcf184d823](https://linux-hardware.org/?probe=fcf184d823) | Mar 04, 2021 |
| Dell          | 0KP561                      | [dc46e34af6](https://linux-hardware.org/?probe=dc46e34af6) | Mar 04, 2021 |
| MSI           | FM2-A55M-E33                | [11cc209d6b](https://linux-hardware.org/?probe=11cc209d6b) | Mar 03, 2021 |
| MSI           | FM2-A55M-E33                | [757512c5d1](https://linux-hardware.org/?probe=757512c5d1) | Mar 03, 2021 |
| Unknown       | Unknown                     | [745c41cc7d](https://linux-hardware.org/?probe=745c41cc7d) | Mar 03, 2021 |
| Gigabyte      | EG41MFT-US2H                | [1a3d1161ba](https://linux-hardware.org/?probe=1a3d1161ba) | Mar 03, 2021 |
| Gigabyte      | EG41MFT-US2H                | [10887ea451](https://linux-hardware.org/?probe=10887ea451) | Mar 03, 2021 |
| Unknown       | Unknown                     | [1ceaa0fb18](https://linux-hardware.org/?probe=1ceaa0fb18) | Mar 02, 2021 |
| Dell          | 0XPDFK A00                  | [2c6ea47b06](https://linux-hardware.org/?probe=2c6ea47b06) | Mar 02, 2021 |
| ASRock        | H81M-VG4                    | [76c8a31a08](https://linux-hardware.org/?probe=76c8a31a08) | Mar 02, 2021 |
| ASRock        | H81M-VG4                    | [8b4dc2b910](https://linux-hardware.org/?probe=8b4dc2b910) | Mar 02, 2021 |
| Lenovo        | Board                       | [59fe924fb7](https://linux-hardware.org/?probe=59fe924fb7) | Mar 02, 2021 |
| Dell          | 0XPDFK A00                  | [7a9a146dc3](https://linux-hardware.org/?probe=7a9a146dc3) | Mar 02, 2021 |
| Lenovo        | Board                       | [a1922faf5b](https://linux-hardware.org/?probe=a1922faf5b) | Mar 02, 2021 |
| Gigabyte      | P61-USB3-B3                 | [282c9c1167](https://linux-hardware.org/?probe=282c9c1167) | Mar 02, 2021 |
| Dell          | 0KP561                      | [62f706dbb4](https://linux-hardware.org/?probe=62f706dbb4) | Mar 02, 2021 |
| Medion        | B75MA-P45                   | [97b85b51e6](https://linux-hardware.org/?probe=97b85b51e6) | Mar 02, 2021 |
| Gigabyte      | B450M S2H                   | [8a019a55e9](https://linux-hardware.org/?probe=8a019a55e9) | Mar 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c119c000a6](https://linux-hardware.org/?probe=c119c000a6) | Mar 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [989b1b3819](https://linux-hardware.org/?probe=989b1b3819) | Mar 01, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2aca5e4fe3](https://linux-hardware.org/?probe=2aca5e4fe3) | Mar 01, 2021 |
| Dell          | 0KP561                      | [aff6f50d60](https://linux-hardware.org/?probe=aff6f50d60) | Mar 01, 2021 |
| ASUSTek       | H110M-K                     | [7733a70583](https://linux-hardware.org/?probe=7733a70583) | Mar 01, 2021 |
| Dell          | 0KP561                      | [dc209c9f24](https://linux-hardware.org/?probe=dc209c9f24) | Mar 01, 2021 |
| HP            | 3029h                       | [ad816c7052](https://linux-hardware.org/?probe=ad816c7052) | Feb 28, 2021 |
| HP            | 3029h                       | [1a227f4b02](https://linux-hardware.org/?probe=1a227f4b02) | Feb 28, 2021 |
| Dell          | 0M5DCD A00                  | [71c6e1995d](https://linux-hardware.org/?probe=71c6e1995d) | Feb 28, 2021 |
| Dell          | 0M5DCD A00                  | [714a850479](https://linux-hardware.org/?probe=714a850479) | Feb 28, 2021 |
| ASUSTek       | P5G41-M SI/DVI              | [89e3b99068](https://linux-hardware.org/?probe=89e3b99068) | Feb 28, 2021 |
| ASUSTek       | P5G41-M SI/DVI              | [c7d29cab2b](https://linux-hardware.org/?probe=c7d29cab2b) | Feb 28, 2021 |
| ASRock        | H370M-ITX/ac                | [abc233d3dd](https://linux-hardware.org/?probe=abc233d3dd) | Feb 28, 2021 |
| ASUSTek       | P5K SE                      | [31e7b7fb77](https://linux-hardware.org/?probe=31e7b7fb77) | Feb 28, 2021 |
| ASUSTek       | P5K SE                      | [586e5e8728](https://linux-hardware.org/?probe=586e5e8728) | Feb 28, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [bbb98caaae](https://linux-hardware.org/?probe=bbb98caaae) | Feb 27, 2021 |
| MSI           | 2A9Ch                       | [b3cc0e05ef](https://linux-hardware.org/?probe=b3cc0e05ef) | Feb 27, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [d83f5f230c](https://linux-hardware.org/?probe=d83f5f230c) | Feb 27, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [6006210374](https://linux-hardware.org/?probe=6006210374) | Feb 27, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [5a4701e6ab](https://linux-hardware.org/?probe=5a4701e6ab) | Feb 27, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [465cf49a51](https://linux-hardware.org/?probe=465cf49a51) | Feb 27, 2021 |
| Medion        | B75MA-P45                   | [91642cec8f](https://linux-hardware.org/?probe=91642cec8f) | Feb 27, 2021 |
| Gigabyte      | H55M-UD2H                   | [86dbe382d6](https://linux-hardware.org/?probe=86dbe382d6) | Feb 27, 2021 |
| ASRock        | H370M-ITX/ac                | [2079831e86](https://linux-hardware.org/?probe=2079831e86) | Feb 27, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [570849b72e](https://linux-hardware.org/?probe=570849b72e) | Feb 27, 2021 |
| MSI           | G41M-P26                    | [f663f69a03](https://linux-hardware.org/?probe=f663f69a03) | Feb 27, 2021 |
| MSI           | G41M-P26                    | [a23b0d2e71](https://linux-hardware.org/?probe=a23b0d2e71) | Feb 27, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [b7a99185d6](https://linux-hardware.org/?probe=b7a99185d6) | Feb 27, 2021 |
| Gigabyte      | EG41MFT-US2H                | [430f1faa87](https://linux-hardware.org/?probe=430f1faa87) | Feb 27, 2021 |
| Gigabyte      | EG41MFT-US2H                | [70ff19df1f](https://linux-hardware.org/?probe=70ff19df1f) | Feb 27, 2021 |
| Gigabyte      | M61PME-S2P                  | [576b644b34](https://linux-hardware.org/?probe=576b644b34) | Feb 27, 2021 |
| Lenovo        | Board                       | [08ec409a9e](https://linux-hardware.org/?probe=08ec409a9e) | Feb 26, 2021 |
| ASUSTek       | SABERTOOTH X79              | [21a3be2645](https://linux-hardware.org/?probe=21a3be2645) | Feb 26, 2021 |
| ASUSTek       | SABERTOOTH X79              | [7132f8a064](https://linux-hardware.org/?probe=7132f8a064) | Feb 26, 2021 |
| Lenovo        | Board                       | [01f7d196db](https://linux-hardware.org/?probe=01f7d196db) | Feb 26, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [806fd8c5d9](https://linux-hardware.org/?probe=806fd8c5d9) | Feb 26, 2021 |
| Acer          | RS880M05                    | [52bbc50495](https://linux-hardware.org/?probe=52bbc50495) | Feb 26, 2021 |
| Acer          | RS880M05                    | [eef2ec526a](https://linux-hardware.org/?probe=eef2ec526a) | Feb 26, 2021 |
| Gigabyte      | M61PME-S2P                  | [d65ef501a1](https://linux-hardware.org/?probe=d65ef501a1) | Feb 26, 2021 |
| HP            | 1495                        | [18cb54ab11](https://linux-hardware.org/?probe=18cb54ab11) | Feb 26, 2021 |
| ASUSTek       | M5A78L/USB3                 | [415bedf3b2](https://linux-hardware.org/?probe=415bedf3b2) | Feb 26, 2021 |
| ASRock        | 4Core1600-D800              | [f75f8a5709](https://linux-hardware.org/?probe=f75f8a5709) | Feb 26, 2021 |
| HP            | 1495                        | [c90fb7a486](https://linux-hardware.org/?probe=c90fb7a486) | Feb 26, 2021 |
| ASRock        | 4Core1600-D800              | [0bea1c97eb](https://linux-hardware.org/?probe=0bea1c97eb) | Feb 25, 2021 |
| Dell          | 03NVJ6 A03                  | [02d8ea1b99](https://linux-hardware.org/?probe=02d8ea1b99) | Feb 25, 2021 |
| ASRock        | Z77 Extreme4-M              | [468703701c](https://linux-hardware.org/?probe=468703701c) | Feb 25, 2021 |
| Gigabyte      | B450M GAMING                | [b16c91f4db](https://linux-hardware.org/?probe=b16c91f4db) | Feb 24, 2021 |
| ASRock        | X570 Phantom Gaming 4S      | [a7136fe7bb](https://linux-hardware.org/?probe=a7136fe7bb) | Feb 24, 2021 |
| ASUSTek       | B5LD2-TVM                   | [7312cef556](https://linux-hardware.org/?probe=7312cef556) | Feb 23, 2021 |
| ASUSTek       | B5LD2-TVM                   | [cc9bca4618](https://linux-hardware.org/?probe=cc9bca4618) | Feb 23, 2021 |
| ASRock        | Z77 Extreme4-M              | [d56bbf29fc](https://linux-hardware.org/?probe=d56bbf29fc) | Feb 23, 2021 |
| Dell          | 0KP561                      | [27f2ecdcdc](https://linux-hardware.org/?probe=27f2ecdcdc) | Feb 22, 2021 |
| ASUSTek       | A88XM-A                     | [25e8d7e6e1](https://linux-hardware.org/?probe=25e8d7e6e1) | Feb 22, 2021 |
| ASUSTek       | M5A78L/USB3                 | [16a51e99f7](https://linux-hardware.org/?probe=16a51e99f7) | Feb 22, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [fb3c4db722](https://linux-hardware.org/?probe=fb3c4db722) | Feb 21, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [b9ea2d372c](https://linux-hardware.org/?probe=b9ea2d372c) | Feb 21, 2021 |
| ASUSTek       | P5K                         | [eabf755eaf](https://linux-hardware.org/?probe=eabf755eaf) | Feb 21, 2021 |
| MSI           | 2A9Ch                       | [f81b02b989](https://linux-hardware.org/?probe=f81b02b989) | Feb 20, 2021 |
| NEC Comput... | GA-8I945PM                  | [e462d670d4](https://linux-hardware.org/?probe=e462d670d4) | Feb 20, 2021 |
| ASUSTek       | P5K                         | [74d025dcbd](https://linux-hardware.org/?probe=74d025dcbd) | Feb 19, 2021 |
| Lenovo        | Board                       | [1261170f27](https://linux-hardware.org/?probe=1261170f27) | Feb 19, 2021 |
| Lenovo        | Board                       | [cface29ae3](https://linux-hardware.org/?probe=cface29ae3) | Feb 19, 2021 |
| Gigabyte      | 945GCM-S2L                  | [ffd1c6e248](https://linux-hardware.org/?probe=ffd1c6e248) | Feb 19, 2021 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [6138f9b79a](https://linux-hardware.org/?probe=6138f9b79a) | Feb 18, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [a5c687c788](https://linux-hardware.org/?probe=a5c687c788) | Feb 18, 2021 |
| Gigabyte      | 945GCM-S2L                  | [d1fc0d621c](https://linux-hardware.org/?probe=d1fc0d621c) | Feb 17, 2021 |
| MSI           | B460M-A PRO                 | [e692ace041](https://linux-hardware.org/?probe=e692ace041) | Feb 17, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [9da48b0891](https://linux-hardware.org/?probe=9da48b0891) | Feb 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [ab98b73d62](https://linux-hardware.org/?probe=ab98b73d62) | Feb 17, 2021 |
| Lenovo        | Board                       | [87b071c681](https://linux-hardware.org/?probe=87b071c681) | Feb 17, 2021 |
| MSI           | FM2-A55M-E33                | [5bb3a105ef](https://linux-hardware.org/?probe=5bb3a105ef) | Feb 15, 2021 |
| MSI           | FM2-A55M-E33                | [114e38fd23](https://linux-hardware.org/?probe=114e38fd23) | Feb 15, 2021 |
| ASRock        | FM2A68M-DG3+                | [508d752d8f](https://linux-hardware.org/?probe=508d752d8f) | Feb 15, 2021 |
| ASUSTek       | PRIME X470-PRO              | [72064cec12](https://linux-hardware.org/?probe=72064cec12) | Feb 15, 2021 |
| MSI           | MS-7267                     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7b3433431b](https://linux-hardware.org/?probe=7b3433431b) | Feb 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a1757ad8fe](https://linux-hardware.org/?probe=a1757ad8fe) | Feb 15, 2021 |
| ASRock        | H81M-HDS                    | [6dfb511cfa](https://linux-hardware.org/?probe=6dfb511cfa) | Feb 15, 2021 |
| ASRock        | H81M-HDS                    | [f6eea0cc62](https://linux-hardware.org/?probe=f6eea0cc62) | Feb 15, 2021 |
| Lenovo        | Board                       | [f0a0447e54](https://linux-hardware.org/?probe=f0a0447e54) | Feb 15, 2021 |
| Medion        | B75MA-P45                   | [0e14bd9cc9](https://linux-hardware.org/?probe=0e14bd9cc9) | Feb 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [a73d476102](https://linux-hardware.org/?probe=a73d476102) | Feb 15, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [d23e0ad00f](https://linux-hardware.org/?probe=d23e0ad00f) | Feb 14, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [47639fc60d](https://linux-hardware.org/?probe=47639fc60d) | Feb 14, 2021 |
| ASRock        | H81M-VG4                    | [d2b5b2fa58](https://linux-hardware.org/?probe=d2b5b2fa58) | Feb 14, 2021 |
| ASUSTek       | VM62                        | [fd5d5343f1](https://linux-hardware.org/?probe=fd5d5343f1) | Feb 14, 2021 |
| ASRock        | Z77 Extreme4                | [22fb4249a8](https://linux-hardware.org/?probe=22fb4249a8) | Feb 14, 2021 |
| Dell          | Board                       | [1ffb2345d9](https://linux-hardware.org/?probe=1ffb2345d9) | Feb 14, 2021 |
| ASRock        | 970 Extreme3                | [3b74077a5b](https://linux-hardware.org/?probe=3b74077a5b) | Feb 14, 2021 |
| HP            | 339A                        | [16640d2961](https://linux-hardware.org/?probe=16640d2961) | Feb 14, 2021 |
| Pegatron      | 2A99h                       | [b4908fab8a](https://linux-hardware.org/?probe=b4908fab8a) | Feb 14, 2021 |
| Pegatron      | 2A99h                       | [9773881e45](https://linux-hardware.org/?probe=9773881e45) | Feb 14, 2021 |
| ASRock        | B85 Pro4                    | [e5b190431d](https://linux-hardware.org/?probe=e5b190431d) | Feb 13, 2021 |
| HP            | 0AA8h                       | [435f709db3](https://linux-hardware.org/?probe=435f709db3) | Feb 13, 2021 |
| ASUSTek       | P5KPL-CM                    | [902e9db778](https://linux-hardware.org/?probe=902e9db778) | Feb 13, 2021 |
| ASUSTek       | P5KPL-CM                    | [0c6358a507](https://linux-hardware.org/?probe=0c6358a507) | Feb 13, 2021 |
| ASRock        | 980DE3/U3S3 R2.0            | [6b7fa11ae0](https://linux-hardware.org/?probe=6b7fa11ae0) | Feb 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [7f7899209a](https://linux-hardware.org/?probe=7f7899209a) | Feb 13, 2021 |
| ASRock        | B85 Pro4                    | [dfeef3ee66](https://linux-hardware.org/?probe=dfeef3ee66) | Feb 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1d15b94110](https://linux-hardware.org/?probe=1d15b94110) | Feb 13, 2021 |
| Dell          | 0GDG8Y A00                  | [8cea9c9afe](https://linux-hardware.org/?probe=8cea9c9afe) | Feb 12, 2021 |
| MSI           | B450M BAZOOKA V2            | [0d6e169e25](https://linux-hardware.org/?probe=0d6e169e25) | Feb 12, 2021 |
| Dell          | Board                       | [900a495a17](https://linux-hardware.org/?probe=900a495a17) | Feb 12, 2021 |
| Gigabyte      | B85M-DS3H                   | [6024201ea8](https://linux-hardware.org/?probe=6024201ea8) | Feb 11, 2021 |
| Gigabyte      | B450M GAMING                | [82ccfec58a](https://linux-hardware.org/?probe=82ccfec58a) | Feb 10, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [20636627b0](https://linux-hardware.org/?probe=20636627b0) | Feb 10, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [756d1c4d39](https://linux-hardware.org/?probe=756d1c4d39) | Feb 10, 2021 |
| Gigabyte      | G31M-ES2L                   | [556d565291](https://linux-hardware.org/?probe=556d565291) | Feb 10, 2021 |
| ASRock        | ConRoe1333-D667             | [cd69633569](https://linux-hardware.org/?probe=cd69633569) | Feb 10, 2021 |
| ASRock        | ConRoe1333-D667             | [2a0bd07cfa](https://linux-hardware.org/?probe=2a0bd07cfa) | Feb 10, 2021 |
| Gigabyte      | MZBSWMP-00                  | [98d8eb9dd2](https://linux-hardware.org/?probe=98d8eb9dd2) | Feb 10, 2021 |
| Medion        | B75MA-P45                   | [26e5bf9f08](https://linux-hardware.org/?probe=26e5bf9f08) | Feb 10, 2021 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [aadc2b1f61](https://linux-hardware.org/?probe=aadc2b1f61) | Feb 09, 2021 |
| ASRock        | H110 Pro BTC+               | [fa5aaee132](https://linux-hardware.org/?probe=fa5aaee132) | Feb 09, 2021 |
| ASUSTek       | PRIME B250M-A               | [f532d2f8ee](https://linux-hardware.org/?probe=f532d2f8ee) | Feb 09, 2021 |
| ASUSTek       | PRIME B250M-A               | [f31f4a1c74](https://linux-hardware.org/?probe=f31f4a1c74) | Feb 09, 2021 |
| Dell          | 0C27VV A01                  | [6b2fa68118](https://linux-hardware.org/?probe=6b2fa68118) | Feb 09, 2021 |
| Dell          | 0C27VV A01                  | [cfa454b962](https://linux-hardware.org/?probe=cfa454b962) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | P67A-D3-B3                  | [f0d87db846](https://linux-hardware.org/?probe=f0d87db846) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| ASUSTek       | P5K-VM                      | [7bdf714af6](https://linux-hardware.org/?probe=7bdf714af6) | Feb 08, 2021 |
| Dell          | 06D7TR A00                  | [c4f7207a30](https://linux-hardware.org/?probe=c4f7207a30) | Feb 08, 2021 |
| Dell          | 06D7TR A00                  | [f53eee2b3b](https://linux-hardware.org/?probe=f53eee2b3b) | Feb 08, 2021 |
| ASUSTek       | P5K-VM                      | [d05dc6ce57](https://linux-hardware.org/?probe=d05dc6ce57) | Feb 08, 2021 |
| Dell          | Board                       | [f7b73ad2c2](https://linux-hardware.org/?probe=f7b73ad2c2) | Feb 08, 2021 |
| Dell          | Board                       | [27a0185983](https://linux-hardware.org/?probe=27a0185983) | Feb 08, 2021 |
| ASRock        | G41M-VS3                    | [d672c0276f](https://linux-hardware.org/?probe=d672c0276f) | Feb 07, 2021 |
| ASRock        | G41M-VS3                    | [b543686e92](https://linux-hardware.org/?probe=b543686e92) | Feb 07, 2021 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4a97f0b328](https://linux-hardware.org/?probe=4a97f0b328) | Feb 06, 2021 |
| ASUSTek       | H81-PLUS                    | [5e5a94b1a6](https://linux-hardware.org/?probe=5e5a94b1a6) | Feb 06, 2021 |
| Dell          | 0PP150 A00                  | [662ec4f699](https://linux-hardware.org/?probe=662ec4f699) | Feb 06, 2021 |
| Dell          | 0PP150 A00                  | [0409cf039e](https://linux-hardware.org/?probe=0409cf039e) | Feb 06, 2021 |
| MSI           | FM2-A55M-E33                | [894976a7d1](https://linux-hardware.org/?probe=894976a7d1) | Feb 06, 2021 |
| Dell          | 0Y5DDC A00                  | [16a1be9e84](https://linux-hardware.org/?probe=16a1be9e84) | Feb 05, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f6c718cae1](https://linux-hardware.org/?probe=f6c718cae1) | Feb 05, 2021 |
| ASRock        | H55M/USB3                   | [ee39675a0e](https://linux-hardware.org/?probe=ee39675a0e) | Feb 05, 2021 |
| Dell          | 0HN7XN A00                  | [f00b8013f0](https://linux-hardware.org/?probe=f00b8013f0) | Feb 05, 2021 |
| Gigabyte      | P35-DS3R                    | [330e6f5ed7](https://linux-hardware.org/?probe=330e6f5ed7) | Feb 05, 2021 |
| ASUSTek       | H81-PLUS                    | [614c109865](https://linux-hardware.org/?probe=614c109865) | Feb 05, 2021 |
| HP            | 1850                        | [4bf8d67f93](https://linux-hardware.org/?probe=4bf8d67f93) | Feb 05, 2021 |
| HP            | 1850                        | [bf3842b1b0](https://linux-hardware.org/?probe=bf3842b1b0) | Feb 05, 2021 |
| Gigabyte      | B450M GAMING                | [f259451f69](https://linux-hardware.org/?probe=f259451f69) | Feb 05, 2021 |
| Gigabyte      | B450M GAMING                | [30fbe6ac06](https://linux-hardware.org/?probe=30fbe6ac06) | Feb 05, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d2e3564d72](https://linux-hardware.org/?probe=d2e3564d72) | Feb 05, 2021 |
| Dell          | 0Y5DDC A00                  | [47e9e7d806](https://linux-hardware.org/?probe=47e9e7d806) | Feb 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | [df4338099c](https://linux-hardware.org/?probe=df4338099c) | Feb 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | [e11b65b8f1](https://linux-hardware.org/?probe=e11b65b8f1) | Feb 04, 2021 |
| Gigabyte      | P35-DS3R                    | [8b1e721389](https://linux-hardware.org/?probe=8b1e721389) | Feb 04, 2021 |
| ASUSTek       | PRIME A320M-R               | [2fa040a2a1](https://linux-hardware.org/?probe=2fa040a2a1) | Feb 04, 2021 |
| ASRock        | N68C-S UCC                  | [6bd3837896](https://linux-hardware.org/?probe=6bd3837896) | Feb 03, 2021 |
| ASUSTek       | H110M-A                     | [becf5103d5](https://linux-hardware.org/?probe=becf5103d5) | Feb 03, 2021 |
| Dell          | 0GY6Y8 A01                  | [fb2ea268a1](https://linux-hardware.org/?probe=fb2ea268a1) | Feb 03, 2021 |
| Dell          | 0GY6Y8 A01                  | [bc87273065](https://linux-hardware.org/?probe=bc87273065) | Feb 03, 2021 |
| Dell          | 0TY915                      | [40ba7ea7f9](https://linux-hardware.org/?probe=40ba7ea7f9) | Feb 02, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [dbcd9e47bc](https://linux-hardware.org/?probe=dbcd9e47bc) | Feb 01, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [240526ca39](https://linux-hardware.org/?probe=240526ca39) | Feb 01, 2021 |
| MSI           | FM2-A55M-E33                | [96d39edd7b](https://linux-hardware.org/?probe=96d39edd7b) | Feb 01, 2021 |
| ASUSTek       | PRIME A320M-R               | [57a6024905](https://linux-hardware.org/?probe=57a6024905) | Feb 01, 2021 |
| Foxconn       | 2ABF                        | [06084ca03e](https://linux-hardware.org/?probe=06084ca03e) | Feb 01, 2021 |
| Foxconn       | 2ABF                        | [4a9ddb54e6](https://linux-hardware.org/?probe=4a9ddb54e6) | Feb 01, 2021 |
| ASRock        | FM2A75M Pro4+               | [d828125a68](https://linux-hardware.org/?probe=d828125a68) | Feb 01, 2021 |
| ASRock        | FM2A75M Pro4+               | [220b35d884](https://linux-hardware.org/?probe=220b35d884) | Feb 01, 2021 |
| Dell          | 0R64DJ A00                  | [436e9715fe](https://linux-hardware.org/?probe=436e9715fe) | Jan 31, 2021 |
| Dell          | 0R64DJ A00                  | [5fdb14e4db](https://linux-hardware.org/?probe=5fdb14e4db) | Jan 31, 2021 |
| HP            | 3032h                       | [0dea1c4a74](https://linux-hardware.org/?probe=0dea1c4a74) | Jan 31, 2021 |
| HP            | 3032h                       | [a720153d5b](https://linux-hardware.org/?probe=a720153d5b) | Jan 31, 2021 |
| ASUSTek       | H110M-A                     | [6810d211c0](https://linux-hardware.org/?probe=6810d211c0) | Jan 31, 2021 |
| ASUSTek       | H110M-A                     | [c4a25b7501](https://linux-hardware.org/?probe=c4a25b7501) | Jan 31, 2021 |
| ViewSonic     | VPC221 C                    | [a890f1fe70](https://linux-hardware.org/?probe=a890f1fe70) | Jan 30, 2021 |
| ViewSonic     | VPC221 C                    | [8b0fb63937](https://linux-hardware.org/?probe=8b0fb63937) | Jan 30, 2021 |
| MSI           | FM2-A55M-E33                | [c0f8d3f8e2](https://linux-hardware.org/?probe=c0f8d3f8e2) | Jan 30, 2021 |
| ASUSTek       | PRIME A320M-R               | [df3848fb87](https://linux-hardware.org/?probe=df3848fb87) | Jan 30, 2021 |
| HP            | 1850                        | [19288ca451](https://linux-hardware.org/?probe=19288ca451) | Jan 29, 2021 |
| MSI           | FM2-A55M-E33                | [5bc93141c0](https://linux-hardware.org/?probe=5bc93141c0) | Jan 29, 2021 |
| HP            | 1850                        | [74b801f4a8](https://linux-hardware.org/?probe=74b801f4a8) | Jan 29, 2021 |
| HP            | 1850                        | [eb466d53dd](https://linux-hardware.org/?probe=eb466d53dd) | Jan 29, 2021 |
| HP            | 1850                        | [7c1c3572a6](https://linux-hardware.org/?probe=7c1c3572a6) | Jan 28, 2021 |
| HP            | 1850                        | [1147ad6b96](https://linux-hardware.org/?probe=1147ad6b96) | Jan 28, 2021 |
| ASRock        | Z87 Extreme4                | [552f932229](https://linux-hardware.org/?probe=552f932229) | Jan 28, 2021 |
| Foxconn       | 2ABF                        | [01b0846bd6](https://linux-hardware.org/?probe=01b0846bd6) | Jan 28, 2021 |
| Foxconn       | 2ABF                        | [bdd918fa48](https://linux-hardware.org/?probe=bdd918fa48) | Jan 28, 2021 |
| HP            | 1850                        | [5a7aa9c583](https://linux-hardware.org/?probe=5a7aa9c583) | Jan 28, 2021 |
| HP            | 1850                        | [786dfaf821](https://linux-hardware.org/?probe=786dfaf821) | Jan 28, 2021 |
| ASRock        | Q1900-ITX                   | [4e81062adc](https://linux-hardware.org/?probe=4e81062adc) | Jan 28, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [edfc992892](https://linux-hardware.org/?probe=edfc992892) | Jan 28, 2021 |
| MSI           | H81M-P33                    | [f2892bac62](https://linux-hardware.org/?probe=f2892bac62) | Jan 27, 2021 |
| MSI           | H81M-P33                    | [b6c9f371aa](https://linux-hardware.org/?probe=b6c9f371aa) | Jan 27, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [596c0f4645](https://linux-hardware.org/?probe=596c0f4645) | Jan 27, 2021 |
| Lenovo        | Board                       | [c84ecfd3b0](https://linux-hardware.org/?probe=c84ecfd3b0) | Jan 27, 2021 |
| Lenovo        | Board                       | [8cd11b427e](https://linux-hardware.org/?probe=8cd11b427e) | Jan 27, 2021 |
| ASUSTek       | M2N                         | [ae1c6a9ac7](https://linux-hardware.org/?probe=ae1c6a9ac7) | Jan 27, 2021 |
| ASRock        | Q1900-ITX                   | [13b812eb69](https://linux-hardware.org/?probe=13b812eb69) | Jan 27, 2021 |
| ASUSTek       | M2N                         | [1af963ba22](https://linux-hardware.org/?probe=1af963ba22) | Jan 27, 2021 |
| Gigabyte      | B450M GAMING                | [47e995f3ba](https://linux-hardware.org/?probe=47e995f3ba) | Jan 27, 2021 |
| Gigabyte      | B450M GAMING                | [566d845d7c](https://linux-hardware.org/?probe=566d845d7c) | Jan 27, 2021 |
| Gigabyte      | B450M GAMING                | [fd487cdc73](https://linux-hardware.org/?probe=fd487cdc73) | Jan 27, 2021 |
| ASUSTek       | M2N                         | [219619a6e4](https://linux-hardware.org/?probe=219619a6e4) | Jan 26, 2021 |
| ASRock        | B85 Pro4                    | [b57b870224](https://linux-hardware.org/?probe=b57b870224) | Jan 26, 2021 |
| ASRock        | B85 Pro4                    | [c962805f83](https://linux-hardware.org/?probe=c962805f83) | Jan 26, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [4cd6af7910](https://linux-hardware.org/?probe=4cd6af7910) | Jan 26, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2ec86ab02a](https://linux-hardware.org/?probe=2ec86ab02a) | Jan 26, 2021 |
| HP            | 3031h                       | [efd65d2c43](https://linux-hardware.org/?probe=efd65d2c43) | Jan 26, 2021 |
| ASUSTek       | M2N                         | [00c312592e](https://linux-hardware.org/?probe=00c312592e) | Jan 26, 2021 |
| ASRock        | Q1900-ITX                   | [c3d236c0ba](https://linux-hardware.org/?probe=c3d236c0ba) | Jan 26, 2021 |
| ASRock        | H55M/USB3                   | [a99ca54fea](https://linux-hardware.org/?probe=a99ca54fea) | Jan 26, 2021 |
| HP            | 2AFA                        | [b134df65e0](https://linux-hardware.org/?probe=b134df65e0) | Jan 26, 2021 |
| Dell          | 0YH299                      | [6f463264fc](https://linux-hardware.org/?probe=6f463264fc) | Jan 25, 2021 |
| HP            | 2AFA                        | [b45e107e10](https://linux-hardware.org/?probe=b45e107e10) | Jan 25, 2021 |
| ASUSTek       | P5QL PRO                    | [a056713353](https://linux-hardware.org/?probe=a056713353) | Jan 25, 2021 |
| Dell          | 0VD5HY A07                  | [be8d192dd2](https://linux-hardware.org/?probe=be8d192dd2) | Jan 25, 2021 |
| Gigabyte      | P67A-D3-B3                  | [a4e0cb9b40](https://linux-hardware.org/?probe=a4e0cb9b40) | Jan 25, 2021 |
| ASUSTek       | Maximus VIII HERO           | [546d5ef86a](https://linux-hardware.org/?probe=546d5ef86a) | Jan 25, 2021 |
| Gigabyte      | B450 AORUS M                | [71f658769f](https://linux-hardware.org/?probe=71f658769f) | Jan 24, 2021 |
| Gigabyte      | B450 AORUS M                | [f5efd6a111](https://linux-hardware.org/?probe=f5efd6a111) | Jan 24, 2021 |
| ASRock        | FM2A75M Pro4+               | [61d1630aaa](https://linux-hardware.org/?probe=61d1630aaa) | Jan 24, 2021 |
| Dell          | 0R64DJ A00                  | [808d8559fa](https://linux-hardware.org/?probe=808d8559fa) | Jan 24, 2021 |
| Gigabyte      | 965P-DS3                    | [ac7fd78ab8](https://linux-hardware.org/?probe=ac7fd78ab8) | Jan 24, 2021 |
| Dell          | 0R64DJ A00                  | [53bf8f540e](https://linux-hardware.org/?probe=53bf8f540e) | Jan 24, 2021 |
| Gigabyte      | 965P-DS3                    | [1cc1a3144c](https://linux-hardware.org/?probe=1cc1a3144c) | Jan 24, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [deef1cb537](https://linux-hardware.org/?probe=deef1cb537) | Jan 24, 2021 |
| Lenovo        | Board                       | [c71d2ac4f2](https://linux-hardware.org/?probe=c71d2ac4f2) | Jan 23, 2021 |
| Lenovo        | Board                       | [e46f368705](https://linux-hardware.org/?probe=e46f368705) | Jan 23, 2021 |
| HP            | 3646h                       | [06924779f4](https://linux-hardware.org/?probe=06924779f4) | Jan 23, 2021 |
| HP            | 3646h                       | [6acdcfbb99](https://linux-hardware.org/?probe=6acdcfbb99) | Jan 23, 2021 |
| ASUSTek       | H81M2                       | [4ebe4d7827](https://linux-hardware.org/?probe=4ebe4d7827) | Jan 23, 2021 |
| ASRock        | FM2A55M-HD+                 | [00d97593a6](https://linux-hardware.org/?probe=00d97593a6) | Jan 23, 2021 |
| Dell          | 0YH299                      | [2894a5398e](https://linux-hardware.org/?probe=2894a5398e) | Jan 23, 2021 |
| ASUSTek       | H81M2                       | [a5bda7d920](https://linux-hardware.org/?probe=a5bda7d920) | Jan 22, 2021 |
| Lenovo        | Board                       | [113f6c70f7](https://linux-hardware.org/?probe=113f6c70f7) | Jan 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c90492d2c4](https://linux-hardware.org/?probe=c90492d2c4) | Jan 22, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [636411207e](https://linux-hardware.org/?probe=636411207e) | Jan 22, 2021 |
| Lenovo        | Board                       | [a19d7886a6](https://linux-hardware.org/?probe=a19d7886a6) | Jan 22, 2021 |
| Lenovo        | Board                       | [ab50d516f2](https://linux-hardware.org/?probe=ab50d516f2) | Jan 22, 2021 |
| Lenovo        | Board                       | [7adbe4d9d2](https://linux-hardware.org/?probe=7adbe4d9d2) | Jan 22, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [c84870c8a2](https://linux-hardware.org/?probe=c84870c8a2) | Jan 22, 2021 |
| Lenovo        | 0.1                         | [38203d0c6f](https://linux-hardware.org/?probe=38203d0c6f) | Jan 21, 2021 |
| Gigabyte      | B450 AORUS M                | [10786f1d06](https://linux-hardware.org/?probe=10786f1d06) | Jan 21, 2021 |
| ASRock        | B85 Pro4                    | [969ee304a4](https://linux-hardware.org/?probe=969ee304a4) | Jan 21, 2021 |
| HP            | 0A64h                       | [30e56a9643](https://linux-hardware.org/?probe=30e56a9643) | Jan 21, 2021 |
| HP            | 0A64h                       | [754b765201](https://linux-hardware.org/?probe=754b765201) | Jan 21, 2021 |
| Shuttle       | FS35V4                      | [d8027f8f42](https://linux-hardware.org/?probe=d8027f8f42) | Jan 20, 2021 |
| ASRock        | FM2A55M-DGS                 | [af3cf02634](https://linux-hardware.org/?probe=af3cf02634) | Jan 20, 2021 |
| ASRock        | FM2A55M-DGS                 | [c3d3dd157c](https://linux-hardware.org/?probe=c3d3dd157c) | Jan 20, 2021 |
| Dell          | 0KP561                      | [c3a9c228e7](https://linux-hardware.org/?probe=c3a9c228e7) | Jan 20, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [28c8065636](https://linux-hardware.org/?probe=28c8065636) | Jan 20, 2021 |
| Dell          | 0M5DCD A00                  | [e986b15bc6](https://linux-hardware.org/?probe=e986b15bc6) | Jan 19, 2021 |
| Dell          | 0M5DCD A00                  | [877e021737](https://linux-hardware.org/?probe=877e021737) | Jan 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [99f9ed7641](https://linux-hardware.org/?probe=99f9ed7641) | Jan 19, 2021 |
| ASRock        | Q1900-ITX                   | [3668d5e9e0](https://linux-hardware.org/?probe=3668d5e9e0) | Jan 19, 2021 |
| ASRock        | FM2A78 Pro4+                | [5537b1b40a](https://linux-hardware.org/?probe=5537b1b40a) | Jan 19, 2021 |
| ASRock        | Q1900-ITX                   | [f611f6333b](https://linux-hardware.org/?probe=f611f6333b) | Jan 19, 2021 |
| HP            | 3031h                       | [dd4dd72cd8](https://linux-hardware.org/?probe=dd4dd72cd8) | Jan 19, 2021 |
| HP            | 3031h                       | [6db051f28e](https://linux-hardware.org/?probe=6db051f28e) | Jan 19, 2021 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [c83f82ee0d](https://linux-hardware.org/?probe=c83f82ee0d) | Jan 18, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a69186697c](https://linux-hardware.org/?probe=a69186697c) | Jan 18, 2021 |
| ASRock        | FM2A78 Pro4+                | [e56bf3dac2](https://linux-hardware.org/?probe=e56bf3dac2) | Jan 18, 2021 |
| Gigabyte      | H81M-S1                     | [9665ed4b60](https://linux-hardware.org/?probe=9665ed4b60) | Jan 18, 2021 |
| Gigabyte      | H81M-S1                     | [0db96934e8](https://linux-hardware.org/?probe=0db96934e8) | Jan 18, 2021 |
| ASRock        | 939A790GMH                  | [2636b5d0d7](https://linux-hardware.org/?probe=2636b5d0d7) | Jan 18, 2021 |
| Dell          | 06D7TR A00                  | [bd37cb022c](https://linux-hardware.org/?probe=bd37cb022c) | Jan 18, 2021 |
| Gigabyte      | B450M GAMING                | [80de107d7f](https://linux-hardware.org/?probe=80de107d7f) | Jan 18, 2021 |
| Gigabyte      | B450M GAMING                | [d7a2e6dc51](https://linux-hardware.org/?probe=d7a2e6dc51) | Jan 18, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [a7e58a7caf](https://linux-hardware.org/?probe=a7e58a7caf) | Jan 17, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [a19c18392e](https://linux-hardware.org/?probe=a19c18392e) | Jan 17, 2021 |
| ASUSTek       | P5QLD PRO                   | [08cb968ea2](https://linux-hardware.org/?probe=08cb968ea2) | Jan 17, 2021 |
| ASUSTek       | H110M-A/M.2                 | [7fa3d653a2](https://linux-hardware.org/?probe=7fa3d653a2) | Jan 17, 2021 |
| ASUSTek       | H110M-A/M.2                 | [2f37ed2d23](https://linux-hardware.org/?probe=2f37ed2d23) | Jan 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | [32d47af9b0](https://linux-hardware.org/?probe=32d47af9b0) | Jan 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | [19a653ac56](https://linux-hardware.org/?probe=19a653ac56) | Jan 17, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [570b255237](https://linux-hardware.org/?probe=570b255237) | Jan 17, 2021 |
| ASRock        | B75 Pro3-M                  | [17cf91c718](https://linux-hardware.org/?probe=17cf91c718) | Jan 16, 2021 |
| ASRock        | B75 Pro3-M                  | [7f45e62dec](https://linux-hardware.org/?probe=7f45e62dec) | Jan 16, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [6be4ed44b2](https://linux-hardware.org/?probe=6be4ed44b2) | Jan 16, 2021 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [e8ac36243b](https://linux-hardware.org/?probe=e8ac36243b) | Jan 16, 2021 |
| ASUSTek       | H81M-E                      | [36dbdc1b25](https://linux-hardware.org/?probe=36dbdc1b25) | Jan 16, 2021 |
| ASUSTek       | H81M-E                      | [38f45f70f7](https://linux-hardware.org/?probe=38f45f70f7) | Jan 16, 2021 |
| Acer          | RS880M05                    | [b83d095629](https://linux-hardware.org/?probe=b83d095629) | Jan 16, 2021 |
| Acer          | RS880M05                    | [a7ed75d39d](https://linux-hardware.org/?probe=a7ed75d39d) | Jan 16, 2021 |
| ASUSTek       | PRIME X370-PRO              | [80843cdff7](https://linux-hardware.org/?probe=80843cdff7) | Jan 16, 2021 |
| HP            | 2820h                       | [8e0cabde28](https://linux-hardware.org/?probe=8e0cabde28) | Jan 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [9b86ad6bb7](https://linux-hardware.org/?probe=9b86ad6bb7) | Jan 15, 2021 |
| ASRock        | H61M-VG4                    | [4259ad370e](https://linux-hardware.org/?probe=4259ad370e) | Jan 14, 2021 |
| ASRock        | H61M-VG4                    | [21f8a1b100](https://linux-hardware.org/?probe=21f8a1b100) | Jan 14, 2021 |
| Lenovo        | SDK0E50510 WIN              | [0f497cfd1b](https://linux-hardware.org/?probe=0f497cfd1b) | Jan 14, 2021 |
| Lenovo        | SDK0E50510 WIN              | [8d2816e9b4](https://linux-hardware.org/?probe=8d2816e9b4) | Jan 14, 2021 |
| ASRock        | AB350M Pro4                 | [953ed48735](https://linux-hardware.org/?probe=953ed48735) | Jan 14, 2021 |
| Intel         | DQ67SW AAG12527-310         | [bf6619209b](https://linux-hardware.org/?probe=bf6619209b) | Jan 14, 2021 |
| Intel         | DQ67SW AAG12527-310         | [708c294716](https://linux-hardware.org/?probe=708c294716) | Jan 14, 2021 |
| Intel         | DQ67SW AAG12527-310         | [c768ad1f5b](https://linux-hardware.org/?probe=c768ad1f5b) | Jan 14, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [ca60008f75](https://linux-hardware.org/?probe=ca60008f75) | Jan 14, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [f2c924e3b4](https://linux-hardware.org/?probe=f2c924e3b4) | Jan 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | [39d22905d9](https://linux-hardware.org/?probe=39d22905d9) | Jan 13, 2021 |
| Gigabyte      | P35-S3G                     | [fed9162d5b](https://linux-hardware.org/?probe=fed9162d5b) | Jan 13, 2021 |
| Gigabyte      | P35-S3G                     | [e25427cb4d](https://linux-hardware.org/?probe=e25427cb4d) | Jan 13, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [3c2569f07f](https://linux-hardware.org/?probe=3c2569f07f) | Jan 13, 2021 |
| ASUSTek       | F1A75-M                     | [97ea2f8be4](https://linux-hardware.org/?probe=97ea2f8be4) | Jan 13, 2021 |
| ASUSTek       | F1A75-M                     | [42ac05cbac](https://linux-hardware.org/?probe=42ac05cbac) | Jan 13, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [23df31b0d6](https://linux-hardware.org/?probe=23df31b0d6) | Jan 13, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [42e40779e2](https://linux-hardware.org/?probe=42e40779e2) | Jan 13, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | [5213efd9a2](https://linux-hardware.org/?probe=5213efd9a2) | Jan 12, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | [4b601239a6](https://linux-hardware.org/?probe=4b601239a6) | Jan 12, 2021 |
| Dell          | 0WMJ54 A01                  | [8860210ffa](https://linux-hardware.org/?probe=8860210ffa) | Jan 12, 2021 |
| Dell          | 0WMJ54 A01                  | [841d3a3805](https://linux-hardware.org/?probe=841d3a3805) | Jan 12, 2021 |
| ASRock        | A320M-DVS R4.0              | [087c4ba756](https://linux-hardware.org/?probe=087c4ba756) | Jan 11, 2021 |
| ASRock        | A320M-DVS R4.0              | [a774ba83a9](https://linux-hardware.org/?probe=a774ba83a9) | Jan 11, 2021 |
| Dell          | 0KP561                      | [ce575abe57](https://linux-hardware.org/?probe=ce575abe57) | Jan 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [29c6000cca](https://linux-hardware.org/?probe=29c6000cca) | Jan 10, 2021 |
| IBM           | Board                       | [23e77f7d28](https://linux-hardware.org/?probe=23e77f7d28) | Jan 10, 2021 |
| IBM           | Board                       | [58741328a6](https://linux-hardware.org/?probe=58741328a6) | Jan 10, 2021 |
| Gigabyte      | M57SLI-S4                   | [9d8998369e](https://linux-hardware.org/?probe=9d8998369e) | Jan 10, 2021 |
| Gigabyte      | M57SLI-S4                   | [08fbe2f45c](https://linux-hardware.org/?probe=08fbe2f45c) | Jan 10, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [6babd7a19e](https://linux-hardware.org/?probe=6babd7a19e) | Jan 10, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [8f8a87705b](https://linux-hardware.org/?probe=8f8a87705b) | Jan 10, 2021 |
| HP            | 1850                        | [ec1ee7414f](https://linux-hardware.org/?probe=ec1ee7414f) | Jan 10, 2021 |
| ASRock        | A320M-DVS R4.0              | [3b5368065e](https://linux-hardware.org/?probe=3b5368065e) | Jan 10, 2021 |
| ASRock        | A320M-DVS R4.0              | [d354a98884](https://linux-hardware.org/?probe=d354a98884) | Jan 10, 2021 |
| Unknown       | X79                         | [a895be79c6](https://linux-hardware.org/?probe=a895be79c6) | Jan 10, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [911fcd5ab5](https://linux-hardware.org/?probe=911fcd5ab5) | Jan 09, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [e238dc5c94](https://linux-hardware.org/?probe=e238dc5c94) | Jan 09, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [838f96068d](https://linux-hardware.org/?probe=838f96068d) | Jan 09, 2021 |
| HP            | 0A58h                       | [a3d6c49a3c](https://linux-hardware.org/?probe=a3d6c49a3c) | Jan 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19eebbcd7f](https://linux-hardware.org/?probe=19eebbcd7f) | Jan 09, 2021 |
| MSI           | MS-7418 100                 | [6f28d27a3d](https://linux-hardware.org/?probe=6f28d27a3d) | Jan 09, 2021 |
| MSI           | MS-7418 100                 | [c2e9c19171](https://linux-hardware.org/?probe=c2e9c19171) | Jan 09, 2021 |
| HP            | 1850                        | [674b080b47](https://linux-hardware.org/?probe=674b080b47) | Jan 09, 2021 |
| HP            | 1850                        | [016a2c1e76](https://linux-hardware.org/?probe=016a2c1e76) | Jan 09, 2021 |
| Lenovo        | Board                       | [62fa506663](https://linux-hardware.org/?probe=62fa506663) | Jan 08, 2021 |
| HP            | 0A58h                       | [96ef1be072](https://linux-hardware.org/?probe=96ef1be072) | Jan 08, 2021 |
| Dell          | 0KP561                      | [11c64df4ed](https://linux-hardware.org/?probe=11c64df4ed) | Jan 08, 2021 |
| Gigabyte      | P35-S3G                     | [22fecd3fdb](https://linux-hardware.org/?probe=22fecd3fdb) | Jan 08, 2021 |
| Gigabyte      | P35-S3G                     | [63e4c2e3c3](https://linux-hardware.org/?probe=63e4c2e3c3) | Jan 08, 2021 |
| Acer          | Veriton X2631G V:1.0        | [2d2bc2f5ef](https://linux-hardware.org/?probe=2d2bc2f5ef) | Jan 08, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [e4a31891a7](https://linux-hardware.org/?probe=e4a31891a7) | Jan 08, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [50b15ad122](https://linux-hardware.org/?probe=50b15ad122) | Jan 08, 2021 |
| IBM           | Board                       | [50d01bdac4](https://linux-hardware.org/?probe=50d01bdac4) | Jan 07, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [447e8976ed](https://linux-hardware.org/?probe=447e8976ed) | Jan 07, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [d319371243](https://linux-hardware.org/?probe=d319371243) | Jan 07, 2021 |
| HP            | 2820h                       | [a25f5f2706](https://linux-hardware.org/?probe=a25f5f2706) | Jan 06, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [860d7e3d8d](https://linux-hardware.org/?probe=860d7e3d8d) | Jan 06, 2021 |
| ASRock        | H55M/USB3                   | [abf76c1388](https://linux-hardware.org/?probe=abf76c1388) | Jan 06, 2021 |
| HP            | 3029h                       | [4b898f3196](https://linux-hardware.org/?probe=4b898f3196) | Jan 06, 2021 |
| HP            | 3029h                       | [3506371338](https://linux-hardware.org/?probe=3506371338) | Jan 06, 2021 |
| Shuttle       | FS35V4                      | [df13cdfbaa](https://linux-hardware.org/?probe=df13cdfbaa) | Jan 06, 2021 |
| ASRock        | FM2A68M-HD+                 | [526feae278](https://linux-hardware.org/?probe=526feae278) | Jan 06, 2021 |
| ASRock        | FM2A68M-HD+                 | [154717ed6b](https://linux-hardware.org/?probe=154717ed6b) | Jan 06, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [97755e07c8](https://linux-hardware.org/?probe=97755e07c8) | Jan 06, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [690aaca54b](https://linux-hardware.org/?probe=690aaca54b) | Jan 06, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [412c32c92a](https://linux-hardware.org/?probe=412c32c92a) | Jan 05, 2021 |
| ASUSTek       | P5K-VM                      | [b325d00460](https://linux-hardware.org/?probe=b325d00460) | Jan 05, 2021 |
| ASUSTek       | P5K-VM                      | [c9b1d6d121](https://linux-hardware.org/?probe=c9b1d6d121) | Jan 05, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [2a3e6f5a0b](https://linux-hardware.org/?probe=2a3e6f5a0b) | Jan 05, 2021 |
| Gigabyte      | H81M-HD3                    | [9c0917a9e4](https://linux-hardware.org/?probe=9c0917a9e4) | Jan 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | [37caae90dc](https://linux-hardware.org/?probe=37caae90dc) | Jan 05, 2021 |
| ASRock        | FM2A75M Pro4+               | [65369daa03](https://linux-hardware.org/?probe=65369daa03) | Jan 04, 2021 |
| ASRock        | FM2A75M Pro4+               | [7f432fd488](https://linux-hardware.org/?probe=7f432fd488) | Jan 04, 2021 |
| ASRock        | FM2A75M Pro4+               | [7645785386](https://linux-hardware.org/?probe=7645785386) | Jan 04, 2021 |
| Lex           | CedarView                   | [0eeef2ac7e](https://linux-hardware.org/?probe=0eeef2ac7e) | Jan 04, 2021 |
| Lex           | CedarView                   | [f76577566d](https://linux-hardware.org/?probe=f76577566d) | Jan 04, 2021 |
| ASRock        | FM2A58M-DG3+                | [3fd8e12b4e](https://linux-hardware.org/?probe=3fd8e12b4e) | Jan 04, 2021 |
| ASUSTek       | P5K-VM                      | [28bf627172](https://linux-hardware.org/?probe=28bf627172) | Jan 04, 2021 |
| ASUSTek       | P5K-VM                      | [9e51629e0b](https://linux-hardware.org/?probe=9e51629e0b) | Jan 04, 2021 |
| Gigabyte      | B450M GAMING                | [bfae2bdc52](https://linux-hardware.org/?probe=bfae2bdc52) | Jan 04, 2021 |
| Gigabyte      | B450M GAMING                | [63d3c6a6b8](https://linux-hardware.org/?probe=63d3c6a6b8) | Jan 04, 2021 |
| Lenovo        | Board                       | [5e655f151e](https://linux-hardware.org/?probe=5e655f151e) | Jan 03, 2021 |
| ASRock        | FM2A58M-DG3+                | [1afae7873e](https://linux-hardware.org/?probe=1afae7873e) | Jan 03, 2021 |
| Lenovo        | Board                       | [608905b30a](https://linux-hardware.org/?probe=608905b30a) | Jan 03, 2021 |
| Gigabyte      | P35-DS3                     | [9606024510](https://linux-hardware.org/?probe=9606024510) | Jan 03, 2021 |
| Gigabyte      | P35-DS3                     | [eb5351b6ae](https://linux-hardware.org/?probe=eb5351b6ae) | Jan 03, 2021 |
| Gigabyte      | P67A-D3-B3                  | [5f0f9f8e65](https://linux-hardware.org/?probe=5f0f9f8e65) | Jan 03, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [9b1538062c](https://linux-hardware.org/?probe=9b1538062c) | Jan 03, 2021 |
| ASRock        | FM2A75M Pro4+               | [5285d9e26f](https://linux-hardware.org/?probe=5285d9e26f) | Jan 03, 2021 |
| ASRock        | FM2A75M Pro4+               | [2ce60fe502](https://linux-hardware.org/?probe=2ce60fe502) | Jan 03, 2021 |
| Dell          | 0TY915                      | [e852279ad8](https://linux-hardware.org/?probe=e852279ad8) | Jan 03, 2021 |
| Lenovo        | Tilapia CRB                 | [e63b9efb47](https://linux-hardware.org/?probe=e63b9efb47) | Jan 03, 2021 |
| Gigabyte      | H61MS                       | [709fe094a6](https://linux-hardware.org/?probe=709fe094a6) | Jan 02, 2021 |
| MSI           | B150M ECO                   | [87a4d6defb](https://linux-hardware.org/?probe=87a4d6defb) | Jan 02, 2021 |
| Gigabyte      | H61MS                       | [0e32fc1c20](https://linux-hardware.org/?probe=0e32fc1c20) | Jan 02, 2021 |
| HP            | 09CCh                       | [f7c09f2e29](https://linux-hardware.org/?probe=f7c09f2e29) | Jan 02, 2021 |
| HP            | 09CCh                       | [1a330114f0](https://linux-hardware.org/?probe=1a330114f0) | Jan 02, 2021 |
| Gigabyte      | F2A88XM-HD3P                | [3a98ccdd53](https://linux-hardware.org/?probe=3a98ccdd53) | Jan 01, 2021 |
| HP            | 3029h                       | [80b8e8bec6](https://linux-hardware.org/?probe=80b8e8bec6) | Jan 01, 2021 |
| HP            | 1850                        | [8fffd39166](https://linux-hardware.org/?probe=8fffd39166) | Jan 01, 2021 |
| ASRock        | H81M-VG4 R2.0               | [5f0927d93c](https://linux-hardware.org/?probe=5f0927d93c) | Jan 01, 2021 |
| ASRock        | H81M-VG4 R2.0               | [9cca0ad607](https://linux-hardware.org/?probe=9cca0ad607) | Jan 01, 2021 |
| HP            | 1850                        | [1103503dbc](https://linux-hardware.org/?probe=1103503dbc) | Jan 01, 2021 |
| HP            | 1850                        | [334d1b1b9d](https://linux-hardware.org/?probe=334d1b1b9d) | Dec 31, 2020 |
| Dell          | 0GM819                      | [5a8eb2cb67](https://linux-hardware.org/?probe=5a8eb2cb67) | Dec 31, 2020 |
| Dell          | 0GM819                      | [0026329cf2](https://linux-hardware.org/?probe=0026329cf2) | Dec 31, 2020 |
| HP            | 1850                        | [a95d3690ef](https://linux-hardware.org/?probe=a95d3690ef) | Dec 31, 2020 |
| ASRock        | 760GM-GS3                   | [f295d578c1](https://linux-hardware.org/?probe=f295d578c1) | Dec 31, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [cbcfbb7998](https://linux-hardware.org/?probe=cbcfbb7998) | Dec 31, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [7fea7d117e](https://linux-hardware.org/?probe=7fea7d117e) | Dec 31, 2020 |
| HP            | 2820h                       | [7f5e2fdcfb](https://linux-hardware.org/?probe=7f5e2fdcfb) | Dec 30, 2020 |
| WINCOR NIX... | G1-CPU-IMP Motherboard_G... | [135e652baa](https://linux-hardware.org/?probe=135e652baa) | Dec 30, 2020 |
| ASUSTek       | AM1M-A                      | [95a55bc85e](https://linux-hardware.org/?probe=95a55bc85e) | Dec 30, 2020 |
| Dell          | 0HY9JP A02                  | [a562ab51c9](https://linux-hardware.org/?probe=a562ab51c9) | Dec 30, 2020 |
| Dell          | 0HY9JP A02                  | [dbecbfc1de](https://linux-hardware.org/?probe=dbecbfc1de) | Dec 30, 2020 |
| HP            | 1850                        | [e40683c01b](https://linux-hardware.org/?probe=e40683c01b) | Dec 30, 2020 |
| HP            | 1850                        | [5c2d6fa3ca](https://linux-hardware.org/?probe=5c2d6fa3ca) | Dec 29, 2020 |
| HP            | 3029h                       | [edc69be8eb](https://linux-hardware.org/?probe=edc69be8eb) | Dec 29, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [a18a514dfb](https://linux-hardware.org/?probe=a18a514dfb) | Dec 29, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [5d201b140d](https://linux-hardware.org/?probe=5d201b140d) | Dec 29, 2020 |
| Fujitsu Si... | MS-7504VP-PV                | [fd352757f9](https://linux-hardware.org/?probe=fd352757f9) | Dec 29, 2020 |
| Gigabyte      | X48-DS5                     | [3d4b7464c7](https://linux-hardware.org/?probe=3d4b7464c7) | Dec 29, 2020 |
| Gigabyte      | HA65M-UD3H-B3               | [b04db0446c](https://linux-hardware.org/?probe=b04db0446c) | Dec 29, 2020 |
| Gigabyte      | HA65M-UD3H-B3               | [07d2cddba0](https://linux-hardware.org/?probe=07d2cddba0) | Dec 29, 2020 |
| Gigabyte      | EP45-UD3LR                  | [60caf837f2](https://linux-hardware.org/?probe=60caf837f2) | Dec 28, 2020 |
| Gigabyte      | EP45-UD3LR                  | [39c0b5fe1c](https://linux-hardware.org/?probe=39c0b5fe1c) | Dec 28, 2020 |
| ASRock        | ConRoe1333-D667             | [9468e68748](https://linux-hardware.org/?probe=9468e68748) | Dec 28, 2020 |
| ASRock        | ConRoe1333-D667             | [6e52c728b3](https://linux-hardware.org/?probe=6e52c728b3) | Dec 28, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1d07c3c3ed](https://linux-hardware.org/?probe=1d07c3c3ed) | Dec 28, 2020 |
| ASUSTek       | V-P5G41E                    | [94141a3c2f](https://linux-hardware.org/?probe=94141a3c2f) | Dec 28, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [4967060223](https://linux-hardware.org/?probe=4967060223) | Dec 28, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [addfe94ec1](https://linux-hardware.org/?probe=addfe94ec1) | Dec 28, 2020 |
| Gigabyte      | H61MS                       | [1c4b7571a1](https://linux-hardware.org/?probe=1c4b7571a1) | Dec 27, 2020 |
| Gigabyte      | H61MS                       | [7e17e98eed](https://linux-hardware.org/?probe=7e17e98eed) | Dec 27, 2020 |
| ASRock        | ConRoe1333-D667             | [95a65d63de](https://linux-hardware.org/?probe=95a65d63de) | Dec 27, 2020 |
| ASRock        | ConRoe1333-D667             | [cd5cff6f1e](https://linux-hardware.org/?probe=cd5cff6f1e) | Dec 27, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f18a7d122d](https://linux-hardware.org/?probe=f18a7d122d) | Dec 27, 2020 |
| Dell          | Board                       | [4a185c6694](https://linux-hardware.org/?probe=4a185c6694) | Dec 27, 2020 |
| Dell          | 0HY9JP A02                  | [881605eefe](https://linux-hardware.org/?probe=881605eefe) | Dec 27, 2020 |
| Gigabyte      | P67A-D3-B3                  | [8a78cc974c](https://linux-hardware.org/?probe=8a78cc974c) | Dec 27, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [55440b9bde](https://linux-hardware.org/?probe=55440b9bde) | Dec 27, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [c9a505cc39](https://linux-hardware.org/?probe=c9a505cc39) | Dec 27, 2020 |
| Gigabyte      | B85-HD3                     | [ca74c75c06](https://linux-hardware.org/?probe=ca74c75c06) | Dec 27, 2020 |
| ASRock        | FM2A55M-HD+                 | [f4229d1074](https://linux-hardware.org/?probe=f4229d1074) | Dec 27, 2020 |
| Gigabyte      | B85-HD3                     | [99a2dbb10a](https://linux-hardware.org/?probe=99a2dbb10a) | Dec 27, 2020 |
| ASRock        | FM2A75M Pro4+               | [f243799579](https://linux-hardware.org/?probe=f243799579) | Dec 26, 2020 |
| ASRock        | FM2A75M Pro4+               | [8d58203bed](https://linux-hardware.org/?probe=8d58203bed) | Dec 26, 2020 |
| Gigabyte      | H81M-S2H                    | [d20c51ce8a](https://linux-hardware.org/?probe=d20c51ce8a) | Dec 26, 2020 |
| Dell          | Board                       | [5cc4b4c291](https://linux-hardware.org/?probe=5cc4b4c291) | Dec 26, 2020 |
| Gigabyte      | H81M-S2H                    | [654af4d3ee](https://linux-hardware.org/?probe=654af4d3ee) | Dec 26, 2020 |
| Lenovo        | Board                       | [f13ef96e9d](https://linux-hardware.org/?probe=f13ef96e9d) | Dec 26, 2020 |
| ASUSTek       | P5ND2 SE                    | [d8af790f9c](https://linux-hardware.org/?probe=d8af790f9c) | Dec 26, 2020 |
| ASUSTek       | P5ND2 SE                    | [55e2b6554b](https://linux-hardware.org/?probe=55e2b6554b) | Dec 26, 2020 |
| MSI           | G41M-P28                    | [3fa9d8ebcb](https://linux-hardware.org/?probe=3fa9d8ebcb) | Dec 26, 2020 |
| MSI           | G41M-P28                    | [8d6231fc5a](https://linux-hardware.org/?probe=8d6231fc5a) | Dec 26, 2020 |
| Lenovo        | Board                       | [54db40ec86](https://linux-hardware.org/?probe=54db40ec86) | Dec 25, 2020 |
| MSI           | B450M PRO-M2 MAX            | [98ffb21eb5](https://linux-hardware.org/?probe=98ffb21eb5) | Dec 25, 2020 |
| HP            | 2820h                       | [83e16dfb59](https://linux-hardware.org/?probe=83e16dfb59) | Dec 25, 2020 |
| ASRock        | AB350M Pro4                 | [1ca5d8ddec](https://linux-hardware.org/?probe=1ca5d8ddec) | Dec 25, 2020 |
| Gigabyte      | H81M-S1                     | [86db0ee050](https://linux-hardware.org/?probe=86db0ee050) | Dec 25, 2020 |
| Gigabyte      | H81M-S1                     | [d7908bdaa7](https://linux-hardware.org/?probe=d7908bdaa7) | Dec 25, 2020 |
| ASRock        | A55M-HVS                    | [42f3b7e695](https://linux-hardware.org/?probe=42f3b7e695) | Dec 25, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [ba2362a179](https://linux-hardware.org/?probe=ba2362a179) | Dec 24, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [592b9305d3](https://linux-hardware.org/?probe=592b9305d3) | Dec 24, 2020 |
| ASRock        | AB350M Pro4                 | [60ffc8a1c6](https://linux-hardware.org/?probe=60ffc8a1c6) | Dec 24, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [d1697d43e3](https://linux-hardware.org/?probe=d1697d43e3) | Dec 24, 2020 |
| Fujitsu Si... | D2841-A1 S26361-D2841-A1    | [b89aab997a](https://linux-hardware.org/?probe=b89aab997a) | Dec 24, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [21a9ef2f43](https://linux-hardware.org/?probe=21a9ef2f43) | Dec 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [8d470b59c5](https://linux-hardware.org/?probe=8d470b59c5) | Dec 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [00f5a648f8](https://linux-hardware.org/?probe=00f5a648f8) | Dec 24, 2020 |
| Gigabyte      | B450M GAMING                | [5f18d8d576](https://linux-hardware.org/?probe=5f18d8d576) | Dec 24, 2020 |
| Gigabyte      | B450M GAMING                | [f08485d373](https://linux-hardware.org/?probe=f08485d373) | Dec 24, 2020 |
| ASUSTek       | P8B75-M LX                  | [483ec6044f](https://linux-hardware.org/?probe=483ec6044f) | Dec 24, 2020 |
| Gigabyte      | GA-880GMA-UD2H              | [34d999ce70](https://linux-hardware.org/?probe=34d999ce70) | Dec 24, 2020 |
| Gigabyte      | H81M-S1                     | [b36252595f](https://linux-hardware.org/?probe=b36252595f) | Dec 23, 2020 |
| ASRock        | AB350M Pro4                 | [8df4648e03](https://linux-hardware.org/?probe=8df4648e03) | Dec 23, 2020 |
| Dell          | 040DDP A01                  | [03f4bfc5af](https://linux-hardware.org/?probe=03f4bfc5af) | Dec 23, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [193a344ef5](https://linux-hardware.org/?probe=193a344ef5) | Dec 23, 2020 |
| Gigabyte      | P67A-D3-B3                  | [7a1485381d](https://linux-hardware.org/?probe=7a1485381d) | Dec 23, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [cb95e84cd3](https://linux-hardware.org/?probe=cb95e84cd3) | Dec 23, 2020 |
| ASUSTek       | Rampage Formula             | [582082294f](https://linux-hardware.org/?probe=582082294f) | Dec 23, 2020 |
| ASUSTek       | Rampage Formula             | [b7d28c4ce9](https://linux-hardware.org/?probe=b7d28c4ce9) | Dec 23, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [ad12d1e2b9](https://linux-hardware.org/?probe=ad12d1e2b9) | Dec 23, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [8685c5ed9a](https://linux-hardware.org/?probe=8685c5ed9a) | Dec 23, 2020 |
| ASRock        | AB350M Pro4                 | [dfca37dfa1](https://linux-hardware.org/?probe=dfca37dfa1) | Dec 23, 2020 |
| ASRock        | 970M Pro3                   | [8902b96f21](https://linux-hardware.org/?probe=8902b96f21) | Dec 23, 2020 |
| ASRock        | 970M Pro3                   | [2546df2412](https://linux-hardware.org/?probe=2546df2412) | Dec 23, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [191e84568a](https://linux-hardware.org/?probe=191e84568a) | Dec 22, 2020 |
| ASRock        | A75 Extreme6                | [d47e328ee9](https://linux-hardware.org/?probe=d47e328ee9) | Dec 22, 2020 |
| Supermicro    | X7SPA-HF                    | [ef90389802](https://linux-hardware.org/?probe=ef90389802) | Dec 22, 2020 |
| Supermicro    | X7SPA-HF                    | [5ae94ea120](https://linux-hardware.org/?probe=5ae94ea120) | Dec 22, 2020 |
| ASUSTek       | PRIME H310M-K R2.0          | [6ad4a89b27](https://linux-hardware.org/?probe=6ad4a89b27) | Dec 22, 2020 |
| Gigabyte      | G31M-S2C                    | [f2fb2391a2](https://linux-hardware.org/?probe=f2fb2391a2) | Dec 22, 2020 |
| Gigabyte      | G31M-S2C                    | [67cdbb722b](https://linux-hardware.org/?probe=67cdbb722b) | Dec 22, 2020 |
| MSI           | H81M-P33                    | [2b59929656](https://linux-hardware.org/?probe=2b59929656) | Dec 22, 2020 |
| MSI           | H81M-P33                    | [abae1fac44](https://linux-hardware.org/?probe=abae1fac44) | Dec 22, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [509903e2d2](https://linux-hardware.org/?probe=509903e2d2) | Dec 21, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [9fb8257a3f](https://linux-hardware.org/?probe=9fb8257a3f) | Dec 21, 2020 |
| HP            | 1850                        | [b249bd74d9](https://linux-hardware.org/?probe=b249bd74d9) | Dec 21, 2020 |
| HP            | 1850                        | [b8f61f6551](https://linux-hardware.org/?probe=b8f61f6551) | Dec 21, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [bbc08c233a](https://linux-hardware.org/?probe=bbc08c233a) | Dec 21, 2020 |
| Lenovo        | Board                       | [860f59d66d](https://linux-hardware.org/?probe=860f59d66d) | Dec 20, 2020 |
| ASRock        | AB350M Pro4                 | [e402c2335d](https://linux-hardware.org/?probe=e402c2335d) | Dec 20, 2020 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [a076ad4a22](https://linux-hardware.org/?probe=a076ad4a22) | Dec 20, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [6441c899aa](https://linux-hardware.org/?probe=6441c899aa) | Dec 20, 2020 |
| ASUSTek       | F1A75-M                     | [06d970e484](https://linux-hardware.org/?probe=06d970e484) | Dec 20, 2020 |
| ASUSTek       | F1A75-M                     | [cd5ea8ef5e](https://linux-hardware.org/?probe=cd5ea8ef5e) | Dec 20, 2020 |
| ASUSTek       | H81M-K                      | [b24c86c61a](https://linux-hardware.org/?probe=b24c86c61a) | Dec 19, 2020 |
| ASUSTek       | P5KPL-SE                    | [e57035bfc4](https://linux-hardware.org/?probe=e57035bfc4) | Dec 19, 2020 |
| ASUSTek       | P5KPL-SE                    | [953f707801](https://linux-hardware.org/?probe=953f707801) | Dec 19, 2020 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [25895fd0a9](https://linux-hardware.org/?probe=25895fd0a9) | Dec 19, 2020 |
| Gigabyte      | 8I945P-G                    | [a6cfd98040](https://linux-hardware.org/?probe=a6cfd98040) | Dec 19, 2020 |
| ASUSTek       | P5K PRO                     | [5445b6993c](https://linux-hardware.org/?probe=5445b6993c) | Dec 19, 2020 |
| Gigabyte      | 8I945P-G                    | [59903503d8](https://linux-hardware.org/?probe=59903503d8) | Dec 19, 2020 |
| ASUSTek       | P5K PRO                     | [293e72d003](https://linux-hardware.org/?probe=293e72d003) | Dec 19, 2020 |
| ASRock        | AB350M Pro4                 | [3417e6c6f9](https://linux-hardware.org/?probe=3417e6c6f9) | Dec 19, 2020 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [29c8d5d253](https://linux-hardware.org/?probe=29c8d5d253) | Dec 19, 2020 |
| ASRock        | 970M Pro3                   | [b34c4eb0f0](https://linux-hardware.org/?probe=b34c4eb0f0) | Dec 19, 2020 |
| HP            | 18E4                        | [9f8e7c186f](https://linux-hardware.org/?probe=9f8e7c186f) | Dec 19, 2020 |
| ASUSTek       | H110M-A/M.2                 | [c55caa2036](https://linux-hardware.org/?probe=c55caa2036) | Dec 19, 2020 |
| ASRock        | 970M Pro3                   | [ac7801360e](https://linux-hardware.org/?probe=ac7801360e) | Dec 18, 2020 |
| ASRock        | 970M Pro3                   | [806cc99d6a](https://linux-hardware.org/?probe=806cc99d6a) | Dec 18, 2020 |
| Gigabyte      | H310M H x.x                 | [0c17b07f2d](https://linux-hardware.org/?probe=0c17b07f2d) | Dec 18, 2020 |
| Gigabyte      | G31M-ES2L                   | [5ce8cc8f4e](https://linux-hardware.org/?probe=5ce8cc8f4e) | Dec 18, 2020 |
| MSI           | MAG Z390M MORTAR            | [7ae12c1a68](https://linux-hardware.org/?probe=7ae12c1a68) | Dec 16, 2020 |
| Lenovo        | Board                       | [9d4cd21808](https://linux-hardware.org/?probe=9d4cd21808) | Dec 16, 2020 |
| Gigabyte      | EP45-UD3LR                  | [4470cf02b9](https://linux-hardware.org/?probe=4470cf02b9) | Dec 16, 2020 |
| Gigabyte      | EP45-UD3LR                  | [89ae739892](https://linux-hardware.org/?probe=89ae739892) | Dec 16, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [25b160a081](https://linux-hardware.org/?probe=25b160a081) | Dec 16, 2020 |
| HP            | 3398                        | [1a769f8caa](https://linux-hardware.org/?probe=1a769f8caa) | Dec 16, 2020 |
| HP            | 3398                        | [67a39608da](https://linux-hardware.org/?probe=67a39608da) | Dec 16, 2020 |
| Gigabyte      | B550M AORUS PRO             | [9a8f1a8636](https://linux-hardware.org/?probe=9a8f1a8636) | Dec 15, 2020 |
| Lenovo        | Board                       | [b0592cba0d](https://linux-hardware.org/?probe=b0592cba0d) | Dec 15, 2020 |
| ASRock        | ConRoe1333-D667             | [875b32c93a](https://linux-hardware.org/?probe=875b32c93a) | Dec 15, 2020 |
| ASRock        | B450 Gaming K4              | [260c01ec7c](https://linux-hardware.org/?probe=260c01ec7c) | Dec 15, 2020 |
| Gigabyte      | G31M-ES2L                   | [69171f27d3](https://linux-hardware.org/?probe=69171f27d3) | Dec 13, 2020 |
| Gigabyte      | G31M-ES2L                   | [dd397330cd](https://linux-hardware.org/?probe=dd397330cd) | Dec 13, 2020 |
| ASRock        | N68C-S UCC                  | [4f394cdaa8](https://linux-hardware.org/?probe=4f394cdaa8) | Dec 13, 2020 |
| ASRock        | N68C-S UCC                  | [ed2c6b06d4](https://linux-hardware.org/?probe=ed2c6b06d4) | Dec 13, 2020 |
| ASRock        | FM2A75M Pro4+               | [af403633ab](https://linux-hardware.org/?probe=af403633ab) | Dec 13, 2020 |
| ASRock        | FM2A75M Pro4+               | [89044de0b9](https://linux-hardware.org/?probe=89044de0b9) | Dec 13, 2020 |
| HP            | 1850                        | [521f158a22](https://linux-hardware.org/?probe=521f158a22) | Dec 12, 2020 |
| HP            | 1850                        | [5da06619c6](https://linux-hardware.org/?probe=5da06619c6) | Dec 12, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [564f2a08cf](https://linux-hardware.org/?probe=564f2a08cf) | Dec 12, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [589154d42c](https://linux-hardware.org/?probe=589154d42c) | Dec 12, 2020 |
| ASRock        | G31M-GS                     | [f51f75944e](https://linux-hardware.org/?probe=f51f75944e) | Dec 12, 2020 |
| Gigabyte      | B450M GAMING                | [4f0f3a1eda](https://linux-hardware.org/?probe=4f0f3a1eda) | Dec 11, 2020 |
| Gigabyte      | B450M GAMING                | [b418913a85](https://linux-hardware.org/?probe=b418913a85) | Dec 11, 2020 |
| ASUSTek       | P5L13L-X                    | [408a0a1460](https://linux-hardware.org/?probe=408a0a1460) | Dec 11, 2020 |
| MSI           | A320M BAZOOKA               | [9298e5fb24](https://linux-hardware.org/?probe=9298e5fb24) | Dec 10, 2020 |
| ASRock        | N68C-S UCC                  | [7ee78dc05c](https://linux-hardware.org/?probe=7ee78dc05c) | Dec 10, 2020 |
| ASRock        | N68C-S UCC                  | [2ec488274c](https://linux-hardware.org/?probe=2ec488274c) | Dec 10, 2020 |
| Gigabyte      | B450M GAMING                | [b20b153aad](https://linux-hardware.org/?probe=b20b153aad) | Dec 09, 2020 |
| Gigabyte      | H61M-S2PV                   | [8a2b334be0](https://linux-hardware.org/?probe=8a2b334be0) | Dec 09, 2020 |
| Gigabyte      | B450M GAMING                | [c6b360de0b](https://linux-hardware.org/?probe=c6b360de0b) | Dec 08, 2020 |
| Lenovo        | Board                       | [b275827ec8](https://linux-hardware.org/?probe=b275827ec8) | Dec 08, 2020 |
| Lenovo        | Board                       | [c65f9f1ab3](https://linux-hardware.org/?probe=c65f9f1ab3) | Dec 08, 2020 |
| ASUSTek       | P8Z77-V                     | [f6b281bfe8](https://linux-hardware.org/?probe=f6b281bfe8) | Dec 08, 2020 |
| HP            | 2820h                       | [c318a3bef2](https://linux-hardware.org/?probe=c318a3bef2) | Dec 08, 2020 |
| HP            | 2820h                       | [a37424c811](https://linux-hardware.org/?probe=a37424c811) | Dec 08, 2020 |
| ASRock        | AB350M Pro4                 | [c036117925](https://linux-hardware.org/?probe=c036117925) | Dec 08, 2020 |
| ASRock        | 970 Pro3 R2.0               | [dd07e49e09](https://linux-hardware.org/?probe=dd07e49e09) | Dec 08, 2020 |
| ASRock        | 970 Pro3 R2.0               | [8ade4bcf0b](https://linux-hardware.org/?probe=8ade4bcf0b) | Dec 08, 2020 |
| ASRock        | J4105M                      | [a11d8e59e0](https://linux-hardware.org/?probe=a11d8e59e0) | Dec 08, 2020 |
| ASRock        | J4105M                      | [ebd8ad3f41](https://linux-hardware.org/?probe=ebd8ad3f41) | Dec 08, 2020 |
| ASRock        | J4105-ITX                   | [0fe9076bf2](https://linux-hardware.org/?probe=0fe9076bf2) | Dec 08, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [997274b093](https://linux-hardware.org/?probe=997274b093) | Dec 07, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [d3349741ea](https://linux-hardware.org/?probe=d3349741ea) | Dec 07, 2020 |
| MSI           | 2A9C                        | [b486a6b9d7](https://linux-hardware.org/?probe=b486a6b9d7) | Dec 07, 2020 |
| ASRock        | N68C-S UCC                  | [d2fb6ff92c](https://linux-hardware.org/?probe=d2fb6ff92c) | Dec 07, 2020 |
| ASRock        | N68C-S UCC                  | [e95ac52242](https://linux-hardware.org/?probe=e95ac52242) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [1bec700189](https://linux-hardware.org/?probe=1bec700189) | Dec 07, 2020 |
| MSI           | 970A SLI Krait Edition      | [8d56de5850](https://linux-hardware.org/?probe=8d56de5850) | Dec 07, 2020 |
| Gigabyte      | X570 AORUS PRO              | [14e81e9a29](https://linux-hardware.org/?probe=14e81e9a29) | Dec 06, 2020 |
| ASRock        | N68-VS3 UCC                 | [0bce949e82](https://linux-hardware.org/?probe=0bce949e82) | Dec 06, 2020 |
| Gigabyte      | B450M GAMING                | [3cc56f7b47](https://linux-hardware.org/?probe=3cc56f7b47) | Dec 06, 2020 |
| ASRock        | N68-VS3 UCC                 | [23b6389bb5](https://linux-hardware.org/?probe=23b6389bb5) | Dec 06, 2020 |
| MSI           | K9A2 Platinum               | [45cb99f887](https://linux-hardware.org/?probe=45cb99f887) | Dec 06, 2020 |
| HP            | 3048h                       | [828def5c74](https://linux-hardware.org/?probe=828def5c74) | Dec 06, 2020 |
| HP            | 2820h                       | [52d0a3c8f2](https://linux-hardware.org/?probe=52d0a3c8f2) | Dec 06, 2020 |
| MSI           | K9A2 Platinum               | [6cbb89a067](https://linux-hardware.org/?probe=6cbb89a067) | Dec 06, 2020 |
| HP            | 1850                        | [a35698a6d3](https://linux-hardware.org/?probe=a35698a6d3) | Dec 06, 2020 |
| HP            | 1850                        | [6698a60c2b](https://linux-hardware.org/?probe=6698a60c2b) | Dec 06, 2020 |
| Lenovo        | Board                       | [53d51fe945](https://linux-hardware.org/?probe=53d51fe945) | Dec 06, 2020 |
| Gigabyte      | P35-S3G                     | [692adc3a2f](https://linux-hardware.org/?probe=692adc3a2f) | Dec 06, 2020 |
| Gigabyte      | P35-S3G                     | [70a929f8db](https://linux-hardware.org/?probe=70a929f8db) | Dec 05, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [d593f66ed0](https://linux-hardware.org/?probe=d593f66ed0) | Dec 04, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [f81e7f05bd](https://linux-hardware.org/?probe=f81e7f05bd) | Dec 04, 2020 |
| ASUSTek       | P7P55D-E                    | [e80bdbc2e1](https://linux-hardware.org/?probe=e80bdbc2e1) | Dec 04, 2020 |
| ASUSTek       | PRIME X570-PRO              | [e431f31b9d](https://linux-hardware.org/?probe=e431f31b9d) | Dec 04, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [601a149d94](https://linux-hardware.org/?probe=601a149d94) | Dec 03, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [b628800e8b](https://linux-hardware.org/?probe=b628800e8b) | Dec 03, 2020 |
| ASUSTek       | M2N68-AM SE2                | [5d85b9810b](https://linux-hardware.org/?probe=5d85b9810b) | Dec 03, 2020 |
| HP            | 3048h                       | [4ac8c18e85](https://linux-hardware.org/?probe=4ac8c18e85) | Dec 03, 2020 |
| ASUSTek       | PRIME X570-PRO              | [c585ad0e8f](https://linux-hardware.org/?probe=c585ad0e8f) | Dec 03, 2020 |
| ASUSTek       | M2N68-AM SE2                | [4ff7dc1309](https://linux-hardware.org/?probe=4ff7dc1309) | Dec 02, 2020 |
| ASUSTek       | PRIME B460M-A               | [6303ca2690](https://linux-hardware.org/?probe=6303ca2690) | Dec 02, 2020 |
| Dell          | 0YP693 A02                  | [01238c1850](https://linux-hardware.org/?probe=01238c1850) | Dec 02, 2020 |
| Dell          | 0YP693 A02                  | [5314a8b4a8](https://linux-hardware.org/?probe=5314a8b4a8) | Dec 02, 2020 |
| HP            | 2820h                       | [2b81fdbd35](https://linux-hardware.org/?probe=2b81fdbd35) | Dec 02, 2020 |
| MSI           | B150M ECO                   | [e04d48b463](https://linux-hardware.org/?probe=e04d48b463) | Dec 01, 2020 |
| ASRock        | J4105-ITX                   | [54f377b79c](https://linux-hardware.org/?probe=54f377b79c) | Dec 01, 2020 |
| ASRock        | 775i65G                     | [f2f798e7d5](https://linux-hardware.org/?probe=f2f798e7d5) | Nov 30, 2020 |
| Gigabyte      | B85M-D2V                    | [3c79523685](https://linux-hardware.org/?probe=3c79523685) | Nov 30, 2020 |
| ASRock        | FM2A75M-DGS                 | [186d46eaef](https://linux-hardware.org/?probe=186d46eaef) | Nov 29, 2020 |
| ASRock        | FM2A75M-DGS                 | [6f5ffb97dd](https://linux-hardware.org/?probe=6f5ffb97dd) | Nov 29, 2020 |
| ASRock        | A55M-HVS                    | [7f4b731977](https://linux-hardware.org/?probe=7f4b731977) | Nov 29, 2020 |
| ASRock        | A55M-HVS                    | [5eb57e13e0](https://linux-hardware.org/?probe=5eb57e13e0) | Nov 29, 2020 |
| ASRock        | 775i65G                     | [77df379fa4](https://linux-hardware.org/?probe=77df379fa4) | Nov 29, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fb7b61efeb](https://linux-hardware.org/?probe=fb7b61efeb) | Nov 29, 2020 |
| Gigabyte      | B450M GAMING                | [4ce7508555](https://linux-hardware.org/?probe=4ce7508555) | Nov 29, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [83385d4cb2](https://linux-hardware.org/?probe=83385d4cb2) | Nov 29, 2020 |
| Lenovo        | Board                       | [faaa54a9f3](https://linux-hardware.org/?probe=faaa54a9f3) | Nov 29, 2020 |
| Lenovo        | Board                       | [ae788ee4c2](https://linux-hardware.org/?probe=ae788ee4c2) | Nov 29, 2020 |
| Dell          | 040DDP A01                  | [0f1fa15267](https://linux-hardware.org/?probe=0f1fa15267) | Nov 29, 2020 |
| ASUSTek       | H81M-C                      | [7cd37a74d2](https://linux-hardware.org/?probe=7cd37a74d2) | Nov 29, 2020 |
| ASUSTek       | H81M-C                      | [70c9816d91](https://linux-hardware.org/?probe=70c9816d91) | Nov 29, 2020 |
| Gigabyte      | P55-USB3                    | [531929a157](https://linux-hardware.org/?probe=531929a157) | Nov 29, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7ce1e4cda5](https://linux-hardware.org/?probe=7ce1e4cda5) | Nov 29, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [94bcc82bc9](https://linux-hardware.org/?probe=94bcc82bc9) | Nov 29, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [8f9e9726bc](https://linux-hardware.org/?probe=8f9e9726bc) | Nov 29, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [b30068320f](https://linux-hardware.org/?probe=b30068320f) | Nov 29, 2020 |
| ASRock        | 775i65G                     | [ef10bba67d](https://linux-hardware.org/?probe=ef10bba67d) | Nov 28, 2020 |
| ASRock        | H61M/U3S3                   | [47db146daa](https://linux-hardware.org/?probe=47db146daa) | Nov 28, 2020 |
| ASRock        | 4CoreDual-SATA2             | [97ff570a12](https://linux-hardware.org/?probe=97ff570a12) | Nov 28, 2020 |
| Lenovo        | ThinkCentre A57 98517HG     | [ea82055cdf](https://linux-hardware.org/?probe=ea82055cdf) | Nov 28, 2020 |
| Lenovo        | ThinkCentre A57 98517HG     | [202a9c807d](https://linux-hardware.org/?probe=202a9c807d) | Nov 27, 2020 |
| ASRock        | AB350M Pro4                 | [5e8b16d0dd](https://linux-hardware.org/?probe=5e8b16d0dd) | Nov 27, 2020 |
| Gigabyte      | B450M GAMING                | [375183f973](https://linux-hardware.org/?probe=375183f973) | Nov 27, 2020 |
| ASRock        | AB350M Pro4                 | [bbfaa9146b](https://linux-hardware.org/?probe=bbfaa9146b) | Nov 27, 2020 |
| Gigabyte      | B250M-DS3H-CF               | [7dc891b5da](https://linux-hardware.org/?probe=7dc891b5da) | Nov 27, 2020 |
| Gigabyte      | B450M GAMING                | [25790e5a29](https://linux-hardware.org/?probe=25790e5a29) | Nov 26, 2020 |
| ASUSTek       | P8Z68-V                     | [fe834e29f3](https://linux-hardware.org/?probe=fe834e29f3) | Nov 26, 2020 |
| Gigabyte      | B450M GAMING                | [8345c8cc86](https://linux-hardware.org/?probe=8345c8cc86) | Nov 26, 2020 |
| HP            | 1850                        | [e7394ed897](https://linux-hardware.org/?probe=e7394ed897) | Nov 26, 2020 |
| HP            | 2820h                       | [7437a44e85](https://linux-hardware.org/?probe=7437a44e85) | Nov 26, 2020 |
| HP            | 1850                        | [5138e94b2e](https://linux-hardware.org/?probe=5138e94b2e) | Nov 26, 2020 |
| ASRock        | H61M/U3S3                   | [03fd0c20fb](https://linux-hardware.org/?probe=03fd0c20fb) | Nov 26, 2020 |
| ASRock        | AB350M Pro4                 | [15d2718517](https://linux-hardware.org/?probe=15d2718517) | Nov 26, 2020 |
| ASRock        | AB350M Pro4                 | [bdcd04f257](https://linux-hardware.org/?probe=bdcd04f257) | Nov 26, 2020 |
| HP            | 3647h                       | [b9665168e4](https://linux-hardware.org/?probe=b9665168e4) | Nov 25, 2020 |
| HP            | 3647h                       | [de930bc482](https://linux-hardware.org/?probe=de930bc482) | Nov 25, 2020 |
| Gigabyte      | H81M-S2PV                   | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Acer          | EQ45M                       | [57e49b49b9](https://linux-hardware.org/?probe=57e49b49b9) | Nov 25, 2020 |
| ASRock        | FM2A88M Extreme4+           | [ae3944c6d4](https://linux-hardware.org/?probe=ae3944c6d4) | Nov 24, 2020 |
| ASRock        | FM2A88M Extreme4+           | [66c233e21b](https://linux-hardware.org/?probe=66c233e21b) | Nov 24, 2020 |
| Lenovo        | Board                       | [484aa0168c](https://linux-hardware.org/?probe=484aa0168c) | Nov 24, 2020 |
| Lenovo        | Board                       | [aaa3f0a8f1](https://linux-hardware.org/?probe=aaa3f0a8f1) | Nov 24, 2020 |
| Lenovo        | MAHOBAY NOK                 | [206565ab57](https://linux-hardware.org/?probe=206565ab57) | Nov 22, 2020 |
| ASRock        | A320M-DVS R4.0              | [08ecc9bd0a](https://linux-hardware.org/?probe=08ecc9bd0a) | Nov 22, 2020 |
| Lenovo        | Board                       | [82dc8dedbc](https://linux-hardware.org/?probe=82dc8dedbc) | Nov 21, 2020 |
| ASRock        | FM2A75M Pro4+               | [31bfb892a1](https://linux-hardware.org/?probe=31bfb892a1) | Nov 21, 2020 |
| ASRock        | FM2A75M Pro4+               | [0f143d2ec2](https://linux-hardware.org/?probe=0f143d2ec2) | Nov 21, 2020 |
| Gigabyte      | H61M-D2-B3                  | [da106bcda3](https://linux-hardware.org/?probe=da106bcda3) | Nov 21, 2020 |
| Gigabyte      | H61M-D2-B3                  | [686b5cf363](https://linux-hardware.org/?probe=686b5cf363) | Nov 21, 2020 |
| HP            | 18E4                        | [a43f795819](https://linux-hardware.org/?probe=a43f795819) | Nov 20, 2020 |
| Gigabyte      | B450M GAMING                | [18600e2f3e](https://linux-hardware.org/?probe=18600e2f3e) | Nov 20, 2020 |
| Gigabyte      | B450M GAMING                | [4b28b992f1](https://linux-hardware.org/?probe=4b28b992f1) | Nov 20, 2020 |
| Lenovo        | NOK                         | [d8fba0824b](https://linux-hardware.org/?probe=d8fba0824b) | Nov 20, 2020 |
| ASRock        | FM2A88M Extreme4+           | [a12e6aaf98](https://linux-hardware.org/?probe=a12e6aaf98) | Nov 20, 2020 |
| Lenovo        | NOK                         | [0b42e69a5c](https://linux-hardware.org/?probe=0b42e69a5c) | Nov 20, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [3636b69934](https://linux-hardware.org/?probe=3636b69934) | Nov 20, 2020 |
| ASRock        | FM2A88M Extreme4+           | [f40627e8ff](https://linux-hardware.org/?probe=f40627e8ff) | Nov 20, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [ad913e1253](https://linux-hardware.org/?probe=ad913e1253) | Nov 20, 2020 |
| ASUSTek       | P8Z77-V LX                  | [5917ab5ae7](https://linux-hardware.org/?probe=5917ab5ae7) | Nov 20, 2020 |
| ASRock        | 4CoreDual-SATA2             | [867e0317c1](https://linux-hardware.org/?probe=867e0317c1) | Nov 20, 2020 |
| Lenovo        | NOK                         | [e7a6ae23f1](https://linux-hardware.org/?probe=e7a6ae23f1) | Nov 19, 2020 |
| Gigabyte      | B450M GAMING                | [b8be21afb6](https://linux-hardware.org/?probe=b8be21afb6) | Nov 19, 2020 |
| Lenovo        | NOK                         | [426eb39a37](https://linux-hardware.org/?probe=426eb39a37) | Nov 19, 2020 |
| Gigabyte      | B450M GAMING                | [1e905e5ffa](https://linux-hardware.org/?probe=1e905e5ffa) | Nov 19, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7afe275380](https://linux-hardware.org/?probe=7afe275380) | Nov 19, 2020 |
| Dell          | 0WMJ54 A01                  | [efab8f12f3](https://linux-hardware.org/?probe=efab8f12f3) | Nov 19, 2020 |
| ASUSTek       | VM40B                       | [ba4edb0b7e](https://linux-hardware.org/?probe=ba4edb0b7e) | Nov 19, 2020 |
| ASUSTek       | M2V-TVM                     | [de37d829be](https://linux-hardware.org/?probe=de37d829be) | Nov 19, 2020 |
| ASUSTek       | M2V-TVM                     | [b1d691d00b](https://linux-hardware.org/?probe=b1d691d00b) | Nov 19, 2020 |
| ASRock        | AB350M Pro4                 | [a021c2be0d](https://linux-hardware.org/?probe=a021c2be0d) | Nov 19, 2020 |
| ASUSTek       | VM40B                       | [f3463dfdbf](https://linux-hardware.org/?probe=f3463dfdbf) | Nov 18, 2020 |
| ASRock        | 4CoreDual-SATA2             | [655b4a64a7](https://linux-hardware.org/?probe=655b4a64a7) | Nov 18, 2020 |
| Pegatron      | 2A84h                       | [dcb3db3dc7](https://linux-hardware.org/?probe=dcb3db3dc7) | Nov 17, 2020 |
| ASRock        | AB350M Pro4                 | [065818c456](https://linux-hardware.org/?probe=065818c456) | Nov 17, 2020 |
| Pegatron      | 2A84h                       | [ad6ad53e39](https://linux-hardware.org/?probe=ad6ad53e39) | Nov 17, 2020 |
| ASRock        | FM2A75M Pro4+               | [e88edcd3e7](https://linux-hardware.org/?probe=e88edcd3e7) | Nov 16, 2020 |
| Gigabyte      | X570 AORUS PRO              | [794ed64b65](https://linux-hardware.org/?probe=794ed64b65) | Nov 16, 2020 |
| ASUSTek       | AM1M-A                      | [57613716c1](https://linux-hardware.org/?probe=57613716c1) | Nov 16, 2020 |
| ASUSTek       | AM1M-A                      | [3baec79995](https://linux-hardware.org/?probe=3baec79995) | Nov 16, 2020 |
| HP            | 1850                        | [eaf273a1d3](https://linux-hardware.org/?probe=eaf273a1d3) | Nov 16, 2020 |
| HP            | 1850                        | [06c1f0a421](https://linux-hardware.org/?probe=06c1f0a421) | Nov 16, 2020 |
| HP            | 1850                        | [a751347068](https://linux-hardware.org/?probe=a751347068) | Nov 16, 2020 |
| Lenovo        | Board                       | [e8751c86aa](https://linux-hardware.org/?probe=e8751c86aa) | Nov 15, 2020 |
| MSI           | B150M ECO                   | [2821e604de](https://linux-hardware.org/?probe=2821e604de) | Nov 15, 2020 |
| Lenovo        | Board                       | [2f0f1c4470](https://linux-hardware.org/?probe=2f0f1c4470) | Nov 15, 2020 |
| ASUSTek       | AM1M-A                      | [8df0350466](https://linux-hardware.org/?probe=8df0350466) | Nov 15, 2020 |
| Dell          | Board                       | [5b3eb2a1f2](https://linux-hardware.org/?probe=5b3eb2a1f2) | Nov 15, 2020 |
| ASUSTek       | AM1M-A                      | [cd094b38e6](https://linux-hardware.org/?probe=cd094b38e6) | Nov 15, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [093d9bea59](https://linux-hardware.org/?probe=093d9bea59) | Nov 15, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [873fb8f927](https://linux-hardware.org/?probe=873fb8f927) | Nov 15, 2020 |
| Gigabyte      | H61M-D2-B3                  | [61fab0e504](https://linux-hardware.org/?probe=61fab0e504) | Nov 15, 2020 |
| Gigabyte      | H61M-D2-B3                  | [a56da4ea39](https://linux-hardware.org/?probe=a56da4ea39) | Nov 15, 2020 |
| Dell          | Board                       | [3154803abe](https://linux-hardware.org/?probe=3154803abe) | Nov 15, 2020 |
| ASUSTek       | VM62                        | [d597cf70fc](https://linux-hardware.org/?probe=d597cf70fc) | Nov 14, 2020 |
| ASUSTek       | VM62                        | [68bd9a369f](https://linux-hardware.org/?probe=68bd9a369f) | Nov 14, 2020 |
| MSI           | Z170A-G43 PLUS              | [3700ff2dd4](https://linux-hardware.org/?probe=3700ff2dd4) | Nov 14, 2020 |
| HP            | 1850                        | [0eebfd79c5](https://linux-hardware.org/?probe=0eebfd79c5) | Nov 13, 2020 |
| Gigabyte      | B450M GAMING                | [1174092214](https://linux-hardware.org/?probe=1174092214) | Nov 13, 2020 |
| ASRock        | 4CoreDual-SATA2             | [a2e4e18a4b](https://linux-hardware.org/?probe=a2e4e18a4b) | Nov 12, 2020 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [89cc43bdfa](https://linux-hardware.org/?probe=89cc43bdfa) | Nov 12, 2020 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [a0b8d783c9](https://linux-hardware.org/?probe=a0b8d783c9) | Nov 12, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b960ef9994](https://linux-hardware.org/?probe=b960ef9994) | Nov 12, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9c66fe791e](https://linux-hardware.org/?probe=9c66fe791e) | Nov 12, 2020 |
| ASUSTek       | Crosshair IV Formula        | [ce647b8826](https://linux-hardware.org/?probe=ce647b8826) | Nov 12, 2020 |
| ASUSTek       | Crosshair IV Formula        | [c0190c4a27](https://linux-hardware.org/?probe=c0190c4a27) | Nov 12, 2020 |
| ASRock        | 4CoreDual-SATA2             | [e7b19bc625](https://linux-hardware.org/?probe=e7b19bc625) | Nov 11, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e723d5875](https://linux-hardware.org/?probe=0e723d5875) | Nov 11, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e1662dabb7](https://linux-hardware.org/?probe=e1662dabb7) | Nov 11, 2020 |
| Gigabyte      | B450M GAMING                | [42a87b7ace](https://linux-hardware.org/?probe=42a87b7ace) | Nov 11, 2020 |
| Lenovo        | Board                       | [e42b5aadad](https://linux-hardware.org/?probe=e42b5aadad) | Nov 11, 2020 |
| Lenovo        | Board                       | [08d09b1584](https://linux-hardware.org/?probe=08d09b1584) | Nov 11, 2020 |
| ASUSTek       | VC65R                       | [c65085ae62](https://linux-hardware.org/?probe=c65085ae62) | Nov 10, 2020 |
| ASRock        | 4CoreDual-SATA2             | [9b48aa4296](https://linux-hardware.org/?probe=9b48aa4296) | Nov 10, 2020 |
| ASUSTek       | VC65R                       | [09bb14a278](https://linux-hardware.org/?probe=09bb14a278) | Nov 10, 2020 |
| ASRock        | 4CoreDual-SATA2             | [1a79f83bf2](https://linux-hardware.org/?probe=1a79f83bf2) | Nov 10, 2020 |
| HP            | 0A58h                       | [c295262448](https://linux-hardware.org/?probe=c295262448) | Nov 10, 2020 |
| ASRock        | B250M Pro4                  | [325bd2152e](https://linux-hardware.org/?probe=325bd2152e) | Nov 10, 2020 |
| ASUSTek       | AM1M-A                      | [69d69060fd](https://linux-hardware.org/?probe=69d69060fd) | Nov 10, 2020 |
| Lenovo        | Board                       | [1b15cef693](https://linux-hardware.org/?probe=1b15cef693) | Nov 10, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [399fbbd031](https://linux-hardware.org/?probe=399fbbd031) | Nov 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [6ed83dd8a2](https://linux-hardware.org/?probe=6ed83dd8a2) | Nov 09, 2020 |
| Gigabyte      | H170-D3HP-CF                | [5b499e2547](https://linux-hardware.org/?probe=5b499e2547) | Nov 09, 2020 |
| Gigabyte      | B450M GAMING                | [b74f006f02](https://linux-hardware.org/?probe=b74f006f02) | Nov 08, 2020 |
| ASUSTek       | PRIME H310M-K R2.0          | [c3c9e9f176](https://linux-hardware.org/?probe=c3c9e9f176) | Nov 08, 2020 |
| ASUSTek       | P5W DH Deluxe               | [b93553445c](https://linux-hardware.org/?probe=b93553445c) | Nov 08, 2020 |
| Lenovo        | Board                       | [1f42ec099a](https://linux-hardware.org/?probe=1f42ec099a) | Nov 08, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [0792d87f2a](https://linux-hardware.org/?probe=0792d87f2a) | Nov 08, 2020 |
| Lenovo        | Board                       | [932fca82c4](https://linux-hardware.org/?probe=932fca82c4) | Nov 08, 2020 |
| ASUSTek       | P5W DH Deluxe               | [6ec5e8572f](https://linux-hardware.org/?probe=6ec5e8572f) | Nov 08, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [1142236102](https://linux-hardware.org/?probe=1142236102) | Nov 08, 2020 |
| MSI           | Z170A-G43 PLUS              | [53e9351edb](https://linux-hardware.org/?probe=53e9351edb) | Nov 07, 2020 |
| HP            | 0A58h                       | [d6c33285c6](https://linux-hardware.org/?probe=d6c33285c6) | Nov 07, 2020 |
| ASUSTek       | PRIME H310M-K R2.0          | [0b2427d3d0](https://linux-hardware.org/?probe=0b2427d3d0) | Nov 07, 2020 |
| ASRock        | FM2A88M Extreme4+           | [10435e9fb1](https://linux-hardware.org/?probe=10435e9fb1) | Nov 07, 2020 |
| ASRock        | FM2A88M Extreme4+           | [1a16a58f4e](https://linux-hardware.org/?probe=1a16a58f4e) | Nov 07, 2020 |
| ASRock        | H61M-DGS                    | [2e846e0119](https://linux-hardware.org/?probe=2e846e0119) | Nov 07, 2020 |
| MSI           | Z170A-G43 PLUS              | [0a68be2f37](https://linux-hardware.org/?probe=0a68be2f37) | Nov 07, 2020 |
| ASRock        | 4Core1600Twins-P35          | [e9a72adf4e](https://linux-hardware.org/?probe=e9a72adf4e) | Nov 07, 2020 |
| Lenovo        | Board                       | [fd1a79cc6c](https://linux-hardware.org/?probe=fd1a79cc6c) | Nov 06, 2020 |
| ASUSTek       | VM40B                       | [2c71096a81](https://linux-hardware.org/?probe=2c71096a81) | Nov 06, 2020 |
| ASUSTek       | H97M-PLUS                   | [8c3349a881](https://linux-hardware.org/?probe=8c3349a881) | Nov 06, 2020 |
| ASUSTek       | H97M-PLUS                   | [6e89444357](https://linux-hardware.org/?probe=6e89444357) | Nov 06, 2020 |
| ASUSTek       | AM1M-A                      | [5569efe134](https://linux-hardware.org/?probe=5569efe134) | Nov 06, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3bb2713b4d](https://linux-hardware.org/?probe=3bb2713b4d) | Nov 05, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [ee558cceb8](https://linux-hardware.org/?probe=ee558cceb8) | Nov 05, 2020 |
| ASRock        | 4Core1600Twins-P35          | [77158b3210](https://linux-hardware.org/?probe=77158b3210) | Nov 05, 2020 |
| Lenovo        | Board                       | [035746d927](https://linux-hardware.org/?probe=035746d927) | Nov 05, 2020 |
| ASUSTek       | P8P67-M PRO                 | [45a8acd5b2](https://linux-hardware.org/?probe=45a8acd5b2) | Nov 05, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [6793a49002](https://linux-hardware.org/?probe=6793a49002) | Nov 04, 2020 |
| Lenovo        | Board                       | [09801b9d4b](https://linux-hardware.org/?probe=09801b9d4b) | Nov 04, 2020 |
| HP            | 1850                        | [5cf9ab1f9c](https://linux-hardware.org/?probe=5cf9ab1f9c) | Nov 04, 2020 |
| HP            | 1850                        | [a583892ca2](https://linux-hardware.org/?probe=a583892ca2) | Nov 04, 2020 |
| Gigabyte      | B450M GAMING                | [96a73f11e6](https://linux-hardware.org/?probe=96a73f11e6) | Nov 04, 2020 |
| Gigabyte      | EP43-S3L                    | [741039b069](https://linux-hardware.org/?probe=741039b069) | Nov 04, 2020 |
| Gigabyte      | EP43-S3L                    | [a28d76592e](https://linux-hardware.org/?probe=a28d76592e) | Nov 04, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [76e0a7fa89](https://linux-hardware.org/?probe=76e0a7fa89) | Nov 03, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [89aec2503c](https://linux-hardware.org/?probe=89aec2503c) | Nov 03, 2020 |
| ASRock        | 4Core1600Twins-P35          | [529b4b1366](https://linux-hardware.org/?probe=529b4b1366) | Nov 03, 2020 |
| ASRock        | 4Core1600Twins-P35          | [2f1791e919](https://linux-hardware.org/?probe=2f1791e919) | Nov 03, 2020 |
| ASRock        | FM2A88M Extreme4+           | [ebe686719c](https://linux-hardware.org/?probe=ebe686719c) | Nov 03, 2020 |
| ASUSTek       | PRIME B550M-K               | [1347703b51](https://linux-hardware.org/?probe=1347703b51) | Nov 02, 2020 |
| ASUSTek       | PRIME H310-PLUS             | [135dbee973](https://linux-hardware.org/?probe=135dbee973) | Nov 02, 2020 |
| ASUSTek       | VM40B                       | [aa00557aee](https://linux-hardware.org/?probe=aa00557aee) | Nov 02, 2020 |
| MSI           | MS-7358 Fab D               | [2d8f396a9b](https://linux-hardware.org/?probe=2d8f396a9b) | Nov 02, 2020 |
| MSI           | MS-7358 Fab D               | [0cb5a24b6f](https://linux-hardware.org/?probe=0cb5a24b6f) | Nov 02, 2020 |
| HP            | 1850                        | [c088174b36](https://linux-hardware.org/?probe=c088174b36) | Nov 02, 2020 |
| HP            | 1850                        | [ddcf770635](https://linux-hardware.org/?probe=ddcf770635) | Nov 02, 2020 |
| ASUSTek       | VM40B                       | [2b3cd0c708](https://linux-hardware.org/?probe=2b3cd0c708) | Nov 01, 2020 |
| Gigabyte      | B450M GAMING                | [1f965a2cf7](https://linux-hardware.org/?probe=1f965a2cf7) | Nov 01, 2020 |
| HP            | 1850                        | [a733ac9274](https://linux-hardware.org/?probe=a733ac9274) | Nov 01, 2020 |
| HP            | 0AA8h                       | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | VM40B                       | [0dfacca211](https://linux-hardware.org/?probe=0dfacca211) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| ASUSTek       | VM40B                       | [c4488353c4](https://linux-hardware.org/?probe=c4488353c4) | Oct 31, 2020 |
| ASUSTek       | VM40B                       | [96feed82d0](https://linux-hardware.org/?probe=96feed82d0) | Oct 31, 2020 |
| ASUSTek       | VC65R                       | [978bd5311c](https://linux-hardware.org/?probe=978bd5311c) | Oct 31, 2020 |
| HP            | 304Ah                       | [ebc4ca37d5](https://linux-hardware.org/?probe=ebc4ca37d5) | Oct 30, 2020 |
| Gigabyte      | F2A88XM-HD3P                | [d150084b1b](https://linux-hardware.org/?probe=d150084b1b) | Oct 30, 2020 |
| ASUSTek       | VM40B                       | [e9a355f409](https://linux-hardware.org/?probe=e9a355f409) | Oct 30, 2020 |
| ASRock        | Z270 Professional Gaming... | [fb6756a6e4](https://linux-hardware.org/?probe=fb6756a6e4) | Oct 30, 2020 |
| ASRock        | Z270 Professional Gaming... | [2d03558d03](https://linux-hardware.org/?probe=2d03558d03) | Oct 30, 2020 |
| ASRock        | 4CoreDual-SATA2             | [6a8e917dde](https://linux-hardware.org/?probe=6a8e917dde) | Oct 29, 2020 |
| ASUSTek       | P8H77-M                     | [80331aea58](https://linux-hardware.org/?probe=80331aea58) | Oct 29, 2020 |
| ASRock        | AB350M Pro4                 | [4bd76c1240](https://linux-hardware.org/?probe=4bd76c1240) | Oct 29, 2020 |
| ASUSTek       | P5QPL-AM                    | [1338af8cf4](https://linux-hardware.org/?probe=1338af8cf4) | Oct 29, 2020 |
| ASUSTek       | P5QPL-AM                    | [0bb9ff50db](https://linux-hardware.org/?probe=0bb9ff50db) | Oct 29, 2020 |
| ASUSTek       | P8Z77-V                     | [e851b325f3](https://linux-hardware.org/?probe=e851b325f3) | Oct 28, 2020 |
| Hampoo        | Cherry Trail CR             | [e5e14eef33](https://linux-hardware.org/?probe=e5e14eef33) | Oct 28, 2020 |
| ASRock        | H61M/U3S3                   | [0c5bda9187](https://linux-hardware.org/?probe=0c5bda9187) | Oct 28, 2020 |
| HP            | 1850                        | [2f3a6428a6](https://linux-hardware.org/?probe=2f3a6428a6) | Oct 27, 2020 |
| ASRock        | 4CoreDual-SATA2             | [aae93f28df](https://linux-hardware.org/?probe=aae93f28df) | Oct 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [d33892be33](https://linux-hardware.org/?probe=d33892be33) | Oct 27, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cf4c710c0e](https://linux-hardware.org/?probe=cf4c710c0e) | Oct 27, 2020 |
| Gigabyte      | B450M GAMING                | [97ae6aa1c1](https://linux-hardware.org/?probe=97ae6aa1c1) | Oct 27, 2020 |
| Gigabyte      | B450M GAMING                | [12ae1addf9](https://linux-hardware.org/?probe=12ae1addf9) | Oct 27, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b2de97057f](https://linux-hardware.org/?probe=b2de97057f) | Oct 27, 2020 |
| HP            | 1850                        | [80edf9a6a1](https://linux-hardware.org/?probe=80edf9a6a1) | Oct 26, 2020 |
| Hampoo        | Cherry Trail CR             | [ecdb435452](https://linux-hardware.org/?probe=ecdb435452) | Oct 26, 2020 |
| Hampoo        | Cherry Trail CR             | [38ef76b4bc](https://linux-hardware.org/?probe=38ef76b4bc) | Oct 26, 2020 |
| ASUSTek       | H81M-K                      | [b19f7bc600](https://linux-hardware.org/?probe=b19f7bc600) | Oct 26, 2020 |
| ASUSTek       | VM40B                       | [6a7f838a83](https://linux-hardware.org/?probe=6a7f838a83) | Oct 26, 2020 |
| Dell          | 042P49 A01                  | [6c22e31a94](https://linux-hardware.org/?probe=6c22e31a94) | Oct 26, 2020 |
| HP            | 1850                        | [03bbec6e98](https://linux-hardware.org/?probe=03bbec6e98) | Oct 25, 2020 |
| ASRock        | 4CoreDual-SATA2             | [9a903b3efe](https://linux-hardware.org/?probe=9a903b3efe) | Oct 25, 2020 |
| HP            | 1850                        | [2aeb379dc8](https://linux-hardware.org/?probe=2aeb379dc8) | Oct 25, 2020 |
| ASRock        | 4CoreDual-SATA2             | [271db90fcb](https://linux-hardware.org/?probe=271db90fcb) | Oct 25, 2020 |
| ASUSTek       | P5L8L-SE                    | [3b4678fabb](https://linux-hardware.org/?probe=3b4678fabb) | Oct 25, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [097f3426dc](https://linux-hardware.org/?probe=097f3426dc) | Oct 25, 2020 |
| ASRock        | FM2A75M Pro4+               | [9cd65590fd](https://linux-hardware.org/?probe=9cd65590fd) | Oct 25, 2020 |
| ASRock        | FM2A75M Pro4+               | [98860e5701](https://linux-hardware.org/?probe=98860e5701) | Oct 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [1a48c92b18](https://linux-hardware.org/?probe=1a48c92b18) | Oct 25, 2020 |
| HP            | 3398                        | [20aaa59537](https://linux-hardware.org/?probe=20aaa59537) | Oct 25, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [5713d10c6d](https://linux-hardware.org/?probe=5713d10c6d) | Oct 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [a451765aaf](https://linux-hardware.org/?probe=a451765aaf) | Oct 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [7e79877cab](https://linux-hardware.org/?probe=7e79877cab) | Oct 24, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [e22bdb9189](https://linux-hardware.org/?probe=e22bdb9189) | Oct 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [8b318d3ea9](https://linux-hardware.org/?probe=8b318d3ea9) | Oct 23, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [db20da9b6a](https://linux-hardware.org/?probe=db20da9b6a) | Oct 23, 2020 |
| ASRock        | H61M/U3S3                   | [d130da1e76](https://linux-hardware.org/?probe=d130da1e76) | Oct 23, 2020 |
| Lenovo        | Board                       | [0ce03e9b17](https://linux-hardware.org/?probe=0ce03e9b17) | Oct 23, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [cea7ae0f95](https://linux-hardware.org/?probe=cea7ae0f95) | Oct 22, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [cf184ea849](https://linux-hardware.org/?probe=cf184ea849) | Oct 22, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [8f174384cf](https://linux-hardware.org/?probe=8f174384cf) | Oct 22, 2020 |
| ASUSTek       | PRIME B450M-K               | [695daa9c8f](https://linux-hardware.org/?probe=695daa9c8f) | Oct 22, 2020 |
| ASUSTek       | PRIME B450M-K               | [ab1f8208ae](https://linux-hardware.org/?probe=ab1f8208ae) | Oct 22, 2020 |
| ASUSTek       | P5K-VM                      | [af305d00a3](https://linux-hardware.org/?probe=af305d00a3) | Oct 22, 2020 |
| ASUSTek       | P5K-VM                      | [5f9c7c3490](https://linux-hardware.org/?probe=5f9c7c3490) | Oct 22, 2020 |
| ASRock        | N68C-S UCC                  | [5fdd86a28f](https://linux-hardware.org/?probe=5fdd86a28f) | Oct 21, 2020 |
| Lenovo        | Board                       | [da9e80b6db](https://linux-hardware.org/?probe=da9e80b6db) | Oct 21, 2020 |
| ASUSTek       | H110M-A/M.2                 | [f68bc7f1e4](https://linux-hardware.org/?probe=f68bc7f1e4) | Oct 21, 2020 |
| ASUSTek       | H110M-A/M.2                 | [be6cd5ce34](https://linux-hardware.org/?probe=be6cd5ce34) | Oct 21, 2020 |
| Lenovo        | Board                       | [0f0d908d63](https://linux-hardware.org/?probe=0f0d908d63) | Oct 21, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [97f024a85d](https://linux-hardware.org/?probe=97f024a85d) | Oct 21, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [63bda189a2](https://linux-hardware.org/?probe=63bda189a2) | Oct 21, 2020 |
| ASRock        | FM2A75M Pro4+               | [5bdec309ad](https://linux-hardware.org/?probe=5bdec309ad) | Oct 20, 2020 |
| ASRock        | Z77 Pro4-M                  | [d883f12b7e](https://linux-hardware.org/?probe=d883f12b7e) | Oct 20, 2020 |
| ASRock        | Z77 Pro4-M                  | [0fbe8cd0b8](https://linux-hardware.org/?probe=0fbe8cd0b8) | Oct 20, 2020 |
| ASRock        | FM2A75M Pro4+               | [98e1d9c192](https://linux-hardware.org/?probe=98e1d9c192) | Oct 20, 2020 |
| Hampoo        | Cherry Trail CR             | [0cf6bf3f67](https://linux-hardware.org/?probe=0cf6bf3f67) | Oct 20, 2020 |
| ASUSTek       | EX-B250-V7                  | [302be75641](https://linux-hardware.org/?probe=302be75641) | Oct 20, 2020 |
| ASUSTek       | EX-B250-V7                  | [6af893ce44](https://linux-hardware.org/?probe=6af893ce44) | Oct 20, 2020 |
| ASRock        | N68-GS3 UCC                 | [a44f119468](https://linux-hardware.org/?probe=a44f119468) | Oct 19, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [57a0adb007](https://linux-hardware.org/?probe=57a0adb007) | Oct 19, 2020 |
| Lenovo        | Board                       | [d6f6242f68](https://linux-hardware.org/?probe=d6f6242f68) | Oct 19, 2020 |
| ASUSTek       | EX-B250-V7                  | [cbea1841d3](https://linux-hardware.org/?probe=cbea1841d3) | Oct 19, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7761e09b82](https://linux-hardware.org/?probe=7761e09b82) | Oct 19, 2020 |
| Dell          | 02YYK5 A01                  | [9d97541a4b](https://linux-hardware.org/?probe=9d97541a4b) | Oct 19, 2020 |
| HP            | 3033h                       | [efeb6a6d6e](https://linux-hardware.org/?probe=efeb6a6d6e) | Oct 19, 2020 |
| HP            | 3033h                       | [0755c4ed5e](https://linux-hardware.org/?probe=0755c4ed5e) | Oct 19, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [8dacc3f9c1](https://linux-hardware.org/?probe=8dacc3f9c1) | Oct 19, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [59d703367c](https://linux-hardware.org/?probe=59d703367c) | Oct 19, 2020 |
| AMD           | 970A-DS3                    | [7315358808](https://linux-hardware.org/?probe=7315358808) | Oct 19, 2020 |
| AMD           | 970A-DS3                    | [96a5977301](https://linux-hardware.org/?probe=96a5977301) | Oct 19, 2020 |
| AMD           | 970A-DS3                    | [4dedfea6de](https://linux-hardware.org/?probe=4dedfea6de) | Oct 19, 2020 |
| Dell          | 0T656F A02                  | [81efabe78a](https://linux-hardware.org/?probe=81efabe78a) | Oct 18, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [e06544fb7b](https://linux-hardware.org/?probe=e06544fb7b) | Oct 18, 2020 |
| Dell          | 0T656F A02                  | [b5bd0c76ec](https://linux-hardware.org/?probe=b5bd0c76ec) | Oct 18, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [ee4e10cff8](https://linux-hardware.org/?probe=ee4e10cff8) | Oct 18, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [24639202a2](https://linux-hardware.org/?probe=24639202a2) | Oct 18, 2020 |
| ASUSTek       | H110M-A/M.2                 | [37204f15e5](https://linux-hardware.org/?probe=37204f15e5) | Oct 18, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [56c8beb1d7](https://linux-hardware.org/?probe=56c8beb1d7) | Oct 18, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [efd0679aac](https://linux-hardware.org/?probe=efd0679aac) | Oct 18, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [088a4c0dec](https://linux-hardware.org/?probe=088a4c0dec) | Oct 18, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [99e302698a](https://linux-hardware.org/?probe=99e302698a) | Oct 18, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [3aff1bcf8d](https://linux-hardware.org/?probe=3aff1bcf8d) | Oct 18, 2020 |
| ASUSTek       | H110M-A                     | [627d514d22](https://linux-hardware.org/?probe=627d514d22) | Oct 18, 2020 |
| Lenovo        | Board                       | [6f1ad004f6](https://linux-hardware.org/?probe=6f1ad004f6) | Oct 18, 2020 |
| Dell          | 0T656F A02                  | [62d710469f](https://linux-hardware.org/?probe=62d710469f) | Oct 17, 2020 |
| ASRock        | N68C-S UCC                  | [5978ac778c](https://linux-hardware.org/?probe=5978ac778c) | Oct 17, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [e5b14268e0](https://linux-hardware.org/?probe=e5b14268e0) | Oct 17, 2020 |
| ASRock        | N68C-S UCC                  | [bce5cc2728](https://linux-hardware.org/?probe=bce5cc2728) | Oct 17, 2020 |
| MSI           | B75MA-P45                   | [d7314e8823](https://linux-hardware.org/?probe=d7314e8823) | Oct 17, 2020 |
| MSI           | B75MA-P45                   | [62a8f140da](https://linux-hardware.org/?probe=62a8f140da) | Oct 17, 2020 |
| ASUSTek       | H110M-A/M.2                 | [176c5feb75](https://linux-hardware.org/?probe=176c5feb75) | Oct 17, 2020 |
| ASRock        | N68-GS3 UCC                 | [fc6b8552e4](https://linux-hardware.org/?probe=fc6b8552e4) | Oct 17, 2020 |
| ASUSTek       | H110M-A/M.2                 | [d7a8f2a1d0](https://linux-hardware.org/?probe=d7a8f2a1d0) | Oct 17, 2020 |
| Gigabyte      | B85M-DS3H                   | [7e46e0df2f](https://linux-hardware.org/?probe=7e46e0df2f) | Oct 17, 2020 |
| Gigabyte      | B85M-DS3H                   | [4b3164145a](https://linux-hardware.org/?probe=4b3164145a) | Oct 17, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [ae1a94776e](https://linux-hardware.org/?probe=ae1a94776e) | Oct 16, 2020 |
| ASRock        | FM2A75M Pro4+               | [90bb3b1ca5](https://linux-hardware.org/?probe=90bb3b1ca5) | Oct 16, 2020 |
| HP            | 339A                        | [ba855d32f3](https://linux-hardware.org/?probe=ba855d32f3) | Oct 16, 2020 |
| HP            | 1850                        | [e869e99f03](https://linux-hardware.org/?probe=e869e99f03) | Oct 16, 2020 |
| HP            | 1850                        | [11ffd478f3](https://linux-hardware.org/?probe=11ffd478f3) | Oct 16, 2020 |
| Intel         | DQ67SW AAG12527-309         | [1c0439405a](https://linux-hardware.org/?probe=1c0439405a) | Oct 16, 2020 |
| Intel         | DQ67SW AAG12527-309         | [fb513b8e84](https://linux-hardware.org/?probe=fb513b8e84) | Oct 16, 2020 |
| ASRock        | FM2A75M Pro4+               | [e79c942be9](https://linux-hardware.org/?probe=e79c942be9) | Oct 16, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [6a4fc6c458](https://linux-hardware.org/?probe=6a4fc6c458) | Oct 16, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [c642cb82a1](https://linux-hardware.org/?probe=c642cb82a1) | Oct 16, 2020 |
| Intel         | DH67CL AAG10212-208         | [d46d33e509](https://linux-hardware.org/?probe=d46d33e509) | Oct 16, 2020 |
| ASRock        | 960GM-GS3 FX                | [bd68438511](https://linux-hardware.org/?probe=bd68438511) | Oct 15, 2020 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f0a945a01d](https://linux-hardware.org/?probe=f0a945a01d) | Oct 15, 2020 |
| ASRock        | 960GM-GS3 FX                | [e76b366e33](https://linux-hardware.org/?probe=e76b366e33) | Oct 15, 2020 |
| ASRock        | FM2A75M Pro4+               | [89b27d00da](https://linux-hardware.org/?probe=89b27d00da) | Oct 13, 2020 |
| Lenovo        | Board                       | [505cd9e4f6](https://linux-hardware.org/?probe=505cd9e4f6) | Oct 13, 2020 |
| Dell          | 0DR845                      | [b2c55a7204](https://linux-hardware.org/?probe=b2c55a7204) | Oct 13, 2020 |
| Dell          | 0DR845                      | [b7b41da521](https://linux-hardware.org/?probe=b7b41da521) | Oct 13, 2020 |
| ASRock        | FM2A88M Extreme4+           | [748c9f73cb](https://linux-hardware.org/?probe=748c9f73cb) | Oct 12, 2020 |
| HP            | 3397                        | [ad8f96cd61](https://linux-hardware.org/?probe=ad8f96cd61) | Oct 12, 2020 |
| Gigabyte      | MZBSWAP-00                  | [5b56790b14](https://linux-hardware.org/?probe=5b56790b14) | Oct 12, 2020 |
| MSI           | A320M BAZOOKA               | [aa0a4ef80c](https://linux-hardware.org/?probe=aa0a4ef80c) | Oct 12, 2020 |
| MSI           | A320M BAZOOKA               | [63db09b0f0](https://linux-hardware.org/?probe=63db09b0f0) | Oct 12, 2020 |
| ASRock        | FM2A88M Extreme4+           | [d8c9b9ba28](https://linux-hardware.org/?probe=d8c9b9ba28) | Oct 12, 2020 |
| ASRock        | FM2A88M Extreme4+           | [eefe731cc7](https://linux-hardware.org/?probe=eefe731cc7) | Oct 11, 2020 |
| Lenovo        | Board                       | [cfff58ee6e](https://linux-hardware.org/?probe=cfff58ee6e) | Oct 11, 2020 |
| Unknown       | Unknown                     | [da81950abc](https://linux-hardware.org/?probe=da81950abc) | Oct 11, 2020 |
| ASUSTek       | H110M-K                     | [720a976b7c](https://linux-hardware.org/?probe=720a976b7c) | Oct 11, 2020 |
| ASRock        | FM2A88M Extreme4+           | [cee27ab5a4](https://linux-hardware.org/?probe=cee27ab5a4) | Oct 11, 2020 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4e795089dc](https://linux-hardware.org/?probe=4e795089dc) | Oct 11, 2020 |
| HP            | 09F0h                       | [0d992692e6](https://linux-hardware.org/?probe=0d992692e6) | Oct 11, 2020 |
| ASRock        | FM2A75M Pro4+               | [4277540b39](https://linux-hardware.org/?probe=4277540b39) | Oct 10, 2020 |
| Gigabyte      | GA-MA770-UD3                | [ab193a9671](https://linux-hardware.org/?probe=ab193a9671) | Oct 10, 2020 |
| ASRock        | FM2A75M Pro4+               | [90ca07ab0e](https://linux-hardware.org/?probe=90ca07ab0e) | Oct 10, 2020 |
| HP            | 0AACh                       | [d806cc10c8](https://linux-hardware.org/?probe=d806cc10c8) | Oct 10, 2020 |
| ASRock        | FM2A75M Pro4+               | [cadc2ee814](https://linux-hardware.org/?probe=cadc2ee814) | Oct 10, 2020 |
| Gigabyte      | GA-MA770-UD3                | [dd2b4b9f86](https://linux-hardware.org/?probe=dd2b4b9f86) | Oct 10, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [7163ab6805](https://linux-hardware.org/?probe=7163ab6805) | Oct 10, 2020 |
| Lenovo        | Board                       | [b7197342d9](https://linux-hardware.org/?probe=b7197342d9) | Oct 09, 2020 |
| HP            | 0AACh                       | [07494ff085](https://linux-hardware.org/?probe=07494ff085) | Oct 09, 2020 |
| ASRock        | FM2A75M Pro4+               | [68700c4bad](https://linux-hardware.org/?probe=68700c4bad) | Oct 09, 2020 |
| ASRock        | FM2A75M Pro4+               | [f3bff6b04c](https://linux-hardware.org/?probe=f3bff6b04c) | Oct 09, 2020 |
| Gateway       | DT55                        | [e6fabe6d7f](https://linux-hardware.org/?probe=e6fabe6d7f) | Oct 09, 2020 |
| ASUSTek       | M2N                         | [0356749684](https://linux-hardware.org/?probe=0356749684) | Oct 09, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [2bffdc3022](https://linux-hardware.org/?probe=2bffdc3022) | Oct 08, 2020 |
| HP            | 3646h                       | [241750bbc1](https://linux-hardware.org/?probe=241750bbc1) | Oct 08, 2020 |
| HP            | 3646h                       | [91c3f015df](https://linux-hardware.org/?probe=91c3f015df) | Oct 08, 2020 |
| MSI           | MS-7309                     | [7082e7cd50](https://linux-hardware.org/?probe=7082e7cd50) | Oct 08, 2020 |
| MSI           | MS-7309                     | [7a145a6308](https://linux-hardware.org/?probe=7a145a6308) | Oct 08, 2020 |
| MSI           | MS-7309                     | [19f5a1e96e](https://linux-hardware.org/?probe=19f5a1e96e) | Oct 08, 2020 |
| Intel         | DQ67EP AAG12529-309         | [5ccd8517ea](https://linux-hardware.org/?probe=5ccd8517ea) | Oct 07, 2020 |
| Intel         | DQ67EP AAG12529-309         | [9dda3c79bf](https://linux-hardware.org/?probe=9dda3c79bf) | Oct 07, 2020 |
| ASUSTek       | AM1M-A                      | [8867e28736](https://linux-hardware.org/?probe=8867e28736) | Oct 07, 2020 |
| ASUSTek       | PRIME B450M-K               | [e6ac1d6473](https://linux-hardware.org/?probe=e6ac1d6473) | Oct 07, 2020 |
| ASUSTek       | PRIME B450M-K               | [56a7b50799](https://linux-hardware.org/?probe=56a7b50799) | Oct 07, 2020 |
| ASUSTek       | AM1M-A                      | [34716fb410](https://linux-hardware.org/?probe=34716fb410) | Oct 07, 2020 |
| ASRock        | AB350M Pro4                 | [42e9e05b02](https://linux-hardware.org/?probe=42e9e05b02) | Oct 07, 2020 |
| MSI           | 2A9C                        | [f052f2dd77](https://linux-hardware.org/?probe=f052f2dd77) | Oct 07, 2020 |
| Dell          | 0DR845                      | [64c26b457b](https://linux-hardware.org/?probe=64c26b457b) | Oct 07, 2020 |
| Dell          | 0DR845                      | [21cea91d8f](https://linux-hardware.org/?probe=21cea91d8f) | Oct 07, 2020 |
| Lenovo        | ThinkCentre M57 6087AG9     | [03389daf9a](https://linux-hardware.org/?probe=03389daf9a) | Oct 07, 2020 |
| Lenovo        | ThinkCentre M57 6087AG9     | [100710e855](https://linux-hardware.org/?probe=100710e855) | Oct 06, 2020 |
| ASUSTek       | PRIME B450M-K               | [3404170963](https://linux-hardware.org/?probe=3404170963) | Oct 06, 2020 |
| MSI           | K9A2 Platinum               | [d0cdd4c83e](https://linux-hardware.org/?probe=d0cdd4c83e) | Oct 06, 2020 |
| ASUSTek       | PRIME B450M-K               | [c8dbdd6f45](https://linux-hardware.org/?probe=c8dbdd6f45) | Oct 06, 2020 |
| MSI           | K9A2 Platinum               | [410dc6ff65](https://linux-hardware.org/?probe=410dc6ff65) | Oct 06, 2020 |
| Dell          | 0GM819                      | [141783f41a](https://linux-hardware.org/?probe=141783f41a) | Oct 06, 2020 |
| Dell          | 0GM819                      | [4ab2acd036](https://linux-hardware.org/?probe=4ab2acd036) | Oct 06, 2020 |
| ASUSTek       | AM1M-A                      | [1c1cbdecfc](https://linux-hardware.org/?probe=1c1cbdecfc) | Oct 06, 2020 |
| HP            | 1850                        | [e9ffc6b960](https://linux-hardware.org/?probe=e9ffc6b960) | Oct 06, 2020 |
| HP            | 1850                        | [92ddb057ce](https://linux-hardware.org/?probe=92ddb057ce) | Oct 06, 2020 |
| ASRock        | FM2A88M Extreme4+           | [21bfc55bfc](https://linux-hardware.org/?probe=21bfc55bfc) | Oct 05, 2020 |
| ASRock        | AB350M Pro4                 | [320e96586c](https://linux-hardware.org/?probe=320e96586c) | Oct 05, 2020 |
| ASRock        | FM2A88M Extreme4+           | [cb2badc130](https://linux-hardware.org/?probe=cb2badc130) | Oct 05, 2020 |
| ASRock        | FM2A88M Extreme4+           | [adb2979117](https://linux-hardware.org/?probe=adb2979117) | Oct 05, 2020 |
| ASUSTek       | AM1M-A                      | [b2afcb034c](https://linux-hardware.org/?probe=b2afcb034c) | Oct 05, 2020 |
| ASUSTek       | PRIME B450M-K               | [6dcaddbbd7](https://linux-hardware.org/?probe=6dcaddbbd7) | Oct 05, 2020 |
| ASRock        | M3N78D                      | [0842908af8](https://linux-hardware.org/?probe=0842908af8) | Oct 04, 2020 |
| ASUSTek       | PRIME B450M-K               | [b0ba40bed7](https://linux-hardware.org/?probe=b0ba40bed7) | Oct 04, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [7a30a89148](https://linux-hardware.org/?probe=7a30a89148) | Oct 04, 2020 |
| Gigabyte      | H81M-S2H                    | [6838480a4d](https://linux-hardware.org/?probe=6838480a4d) | Oct 04, 2020 |
| Lenovo        | Board                       | [0de8f2dc44](https://linux-hardware.org/?probe=0de8f2dc44) | Oct 04, 2020 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [447ee5f200](https://linux-hardware.org/?probe=447ee5f200) | Oct 04, 2020 |
| Gigabyte      | H81M-S2H                    | [ed961e56ad](https://linux-hardware.org/?probe=ed961e56ad) | Oct 04, 2020 |
| Acer          | Revo RL80                   | [e1335e8e27](https://linux-hardware.org/?probe=e1335e8e27) | Oct 04, 2020 |
| ASRock        | M3N78D                      | [870d5f8ace](https://linux-hardware.org/?probe=870d5f8ace) | Oct 03, 2020 |
| Gigabyte      | B250M-D2V-CF                | [2599615935](https://linux-hardware.org/?probe=2599615935) | Oct 03, 2020 |
| Gigabyte      | B250M-D2V-CF                | [270f4b417a](https://linux-hardware.org/?probe=270f4b417a) | Oct 03, 2020 |
| ASUSTek       | PRIME Z370-A                | [953ba0670d](https://linux-hardware.org/?probe=953ba0670d) | Oct 02, 2020 |
| Gigabyte      | X48-DS5                     | [56eb410dfe](https://linux-hardware.org/?probe=56eb410dfe) | Oct 02, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | [2a8db862cf](https://linux-hardware.org/?probe=2a8db862cf) | Oct 02, 2020 |
| HP            | 3646h                       | [9cc081cfa5](https://linux-hardware.org/?probe=9cc081cfa5) | Oct 02, 2020 |
| HP            | 3646h                       | [5f5e5645b6](https://linux-hardware.org/?probe=5f5e5645b6) | Oct 01, 2020 |
| HP            | 3646h                       | [bbcf01caf1](https://linux-hardware.org/?probe=bbcf01caf1) | Oct 01, 2020 |
| Dell          | 0JP3NX A01                  | [7393134ea6](https://linux-hardware.org/?probe=7393134ea6) | Oct 01, 2020 |
| Gigabyte      | H61MA-D3V                   | [42e242b122](https://linux-hardware.org/?probe=42e242b122) | Oct 01, 2020 |
| Gigabyte      | H55M-S2H                    | [3df13a6547](https://linux-hardware.org/?probe=3df13a6547) | Oct 01, 2020 |
| Gigabyte      | H55M-S2H                    | [f3d91b4dec](https://linux-hardware.org/?probe=f3d91b4dec) | Oct 01, 2020 |
| MSI           | H67MA-E35                   | [92f2cb0a50](https://linux-hardware.org/?probe=92f2cb0a50) | Sep 30, 2020 |
| MSI           | H67MA-E35                   | [4ef940269c](https://linux-hardware.org/?probe=4ef940269c) | Sep 30, 2020 |
| Lenovo        | Board                       | [ad25d6db51](https://linux-hardware.org/?probe=ad25d6db51) | Sep 30, 2020 |
| Lenovo        | Board                       | [44df3afdab](https://linux-hardware.org/?probe=44df3afdab) | Sep 30, 2020 |
| ASRock        | AB350M Pro4                 | [4b982813e2](https://linux-hardware.org/?probe=4b982813e2) | Sep 30, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | [9f128c321d](https://linux-hardware.org/?probe=9f128c321d) | Sep 30, 2020 |
| Dell          | 0GM819                      | [9295632bd9](https://linux-hardware.org/?probe=9295632bd9) | Sep 30, 2020 |
| HP            | 2B4B                        | [9b275b5130](https://linux-hardware.org/?probe=9b275b5130) | Sep 30, 2020 |
| ASRock        | AB350M Pro4                 | [f8e37e9054](https://linux-hardware.org/?probe=f8e37e9054) | Sep 30, 2020 |
| ASUSTek       | P5G-MX                      | [e2d8583e4f](https://linux-hardware.org/?probe=e2d8583e4f) | Sep 29, 2020 |
| Dell          | 0GM819                      | [f6078f8321](https://linux-hardware.org/?probe=f6078f8321) | Sep 29, 2020 |
| Gigabyte      | H61MA-D3V                   | [d81b396a54](https://linux-hardware.org/?probe=d81b396a54) | Sep 29, 2020 |
| Lenovo        | Board                       | [747a5a6f20](https://linux-hardware.org/?probe=747a5a6f20) | Sep 29, 2020 |
| Lenovo        | Board                       | [301da504ec](https://linux-hardware.org/?probe=301da504ec) | Sep 29, 2020 |
| Dell          | 0GM819                      | [100e15914b](https://linux-hardware.org/?probe=100e15914b) | Sep 29, 2020 |
| Dell          | 0GM819                      | [2905f47997](https://linux-hardware.org/?probe=2905f47997) | Sep 28, 2020 |
| ASRock        | AM2NF3-VSTA                 | [c71633fd43](https://linux-hardware.org/?probe=c71633fd43) | Sep 28, 2020 |
| Gigabyte      | 970A-DS3P                   | [8dc871b0cb](https://linux-hardware.org/?probe=8dc871b0cb) | Sep 28, 2020 |
| ASRock        | FM2A75M Pro4+               | [1d3a043f51](https://linux-hardware.org/?probe=1d3a043f51) | Sep 28, 2020 |
| ABIT          | IL8                         | [008e2c39d0](https://linux-hardware.org/?probe=008e2c39d0) | Sep 28, 2020 |
| ABIT          | IL8                         | [aa685c4b87](https://linux-hardware.org/?probe=aa685c4b87) | Sep 28, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [09acee1d64](https://linux-hardware.org/?probe=09acee1d64) | Sep 28, 2020 |
| Lenovo        | Board                       | [cc35539abf](https://linux-hardware.org/?probe=cc35539abf) | Sep 28, 2020 |
| ASRock        | FM2A55M-DGS                 | [0937bb5379](https://linux-hardware.org/?probe=0937bb5379) | Sep 28, 2020 |
| Dell          | 0GM819                      | [e8fc7174ff](https://linux-hardware.org/?probe=e8fc7174ff) | Sep 27, 2020 |
| Gigabyte      | MZGLKDP-00                  | [07b81a2502](https://linux-hardware.org/?probe=07b81a2502) | Sep 27, 2020 |
| ASRock        | FM2A88M Extreme4+           | [4ab391459c](https://linux-hardware.org/?probe=4ab391459c) | Sep 27, 2020 |
| ASRock        | FM2A88M Extreme4+           | [9ef7141d27](https://linux-hardware.org/?probe=9ef7141d27) | Sep 27, 2020 |
| Gigabyte      | MZGLKDP-00                  | [ae2969ad3e](https://linux-hardware.org/?probe=ae2969ad3e) | Sep 27, 2020 |
| ABIT          | IL8                         | [c6da31310e](https://linux-hardware.org/?probe=c6da31310e) | Sep 27, 2020 |
| Lenovo        | Board                       | [7bb30f6161](https://linux-hardware.org/?probe=7bb30f6161) | Sep 27, 2020 |
| HP            | 0AACh                       | [f2f91e8a9d](https://linux-hardware.org/?probe=f2f91e8a9d) | Sep 26, 2020 |
| Dell          | 0Y2MRG A00                  | [fe94a4bb83](https://linux-hardware.org/?probe=fe94a4bb83) | Sep 26, 2020 |
| Dell          | 048DY8 A00                  | [e3347c4b5a](https://linux-hardware.org/?probe=e3347c4b5a) | Sep 26, 2020 |
| Lenovo        | Board                       | [fa4b6aaa05](https://linux-hardware.org/?probe=fa4b6aaa05) | Sep 25, 2020 |
| ASRock        | AB350M Pro4                 | [779cedd17c](https://linux-hardware.org/?probe=779cedd17c) | Sep 25, 2020 |
| ASRock        | AB350M Pro4                 | [f7de7f1a55](https://linux-hardware.org/?probe=f7de7f1a55) | Sep 25, 2020 |
| Dell          | 0R230R A00                  | [6a40372c8f](https://linux-hardware.org/?probe=6a40372c8f) | Sep 25, 2020 |
| HP            | 3646h                       | [ac5417728a](https://linux-hardware.org/?probe=ac5417728a) | Sep 24, 2020 |
| HP            | 3646h                       | [3adc6344b9](https://linux-hardware.org/?probe=3adc6344b9) | Sep 24, 2020 |
| HP            | 1850                        | [3226e7e957](https://linux-hardware.org/?probe=3226e7e957) | Sep 23, 2020 |
| HP            | 1850                        | [bacab11ff1](https://linux-hardware.org/?probe=bacab11ff1) | Sep 23, 2020 |
| Lenovo        | Board                       | [c4bdb49b7c](https://linux-hardware.org/?probe=c4bdb49b7c) | Sep 23, 2020 |
| Lenovo        | Board                       | [86e707d095](https://linux-hardware.org/?probe=86e707d095) | Sep 23, 2020 |
| ASRock        | FM2A88M Extreme4+           | [bd0c22ad1a](https://linux-hardware.org/?probe=bd0c22ad1a) | Sep 23, 2020 |
| ASRock        | FM2A88M Extreme4+           | [0caef57ae5](https://linux-hardware.org/?probe=0caef57ae5) | Sep 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [1e029e2ae3](https://linux-hardware.org/?probe=1e029e2ae3) | Sep 23, 2020 |
| Foxconn       | H55M-S                      | [debe3aa457](https://linux-hardware.org/?probe=debe3aa457) | Sep 23, 2020 |
| Foxconn       | H55M-S                      | [4d3a138b55](https://linux-hardware.org/?probe=4d3a138b55) | Sep 23, 2020 |
| Lenovo        | ThinkServer TS140           | [bb4d8abbcb](https://linux-hardware.org/?probe=bb4d8abbcb) | Sep 23, 2020 |
| ASUSTek       | PRIME A320M-R               | [9f1815040c](https://linux-hardware.org/?probe=9f1815040c) | Sep 22, 2020 |
| ASUSTek       | PRIME A320M-R               | [e582010822](https://linux-hardware.org/?probe=e582010822) | Sep 22, 2020 |
| Gigabyte      | F2A88XM-HD3P                | [b21765acb6](https://linux-hardware.org/?probe=b21765acb6) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [d0fa77ca5c](https://linux-hardware.org/?probe=d0fa77ca5c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [cd1338eddd](https://linux-hardware.org/?probe=cd1338eddd) | Sep 21, 2020 |
| HP            | 1850                        | [b5835a9092](https://linux-hardware.org/?probe=b5835a9092) | Sep 21, 2020 |
| HP            | 1850                        | [11d1652e76](https://linux-hardware.org/?probe=11d1652e76) | Sep 21, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [f7dcf9f65c](https://linux-hardware.org/?probe=f7dcf9f65c) | Sep 20, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [cdc2868bf5](https://linux-hardware.org/?probe=cdc2868bf5) | Sep 20, 2020 |
| Dell          | 0TY915                      | [a0af838736](https://linux-hardware.org/?probe=a0af838736) | Sep 20, 2020 |
| Dell          | 0TY915                      | [7bcbdfafb1](https://linux-hardware.org/?probe=7bcbdfafb1) | Sep 20, 2020 |
| Foxconn       | H55M-S                      | [d347990d6a](https://linux-hardware.org/?probe=d347990d6a) | Sep 20, 2020 |
| ASUSTek       | P5QL PRO                    | [f720340d6c](https://linux-hardware.org/?probe=f720340d6c) | Sep 20, 2020 |
| ASUSTek       | P5QL PRO                    | [b4d28ace5e](https://linux-hardware.org/?probe=b4d28ace5e) | Sep 20, 2020 |
| MSI           | B450M MORTAR MAX            | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| HP            | 2ADE                        | [5540608873](https://linux-hardware.org/?probe=5540608873) | Sep 20, 2020 |
| HP            | 2ADE                        | [716f0b0ff8](https://linux-hardware.org/?probe=716f0b0ff8) | Sep 20, 2020 |
| ASRock        | A55M-HVS                    | [7eb86b51bb](https://linux-hardware.org/?probe=7eb86b51bb) | Sep 20, 2020 |
| Lenovo        | Board                       | [ee2acaef87](https://linux-hardware.org/?probe=ee2acaef87) | Sep 20, 2020 |
| ASRock        | B450M Pro4-F                | [3338df304f](https://linux-hardware.org/?probe=3338df304f) | Sep 19, 2020 |
| Foxconn       | H55M-S                      | [6badece895](https://linux-hardware.org/?probe=6badece895) | Sep 19, 2020 |
| ASRock        | H81M-VG4                    | [6088fc2394](https://linux-hardware.org/?probe=6088fc2394) | Sep 18, 2020 |
| ASRock        | Z270 Professional Gaming... | [6f7ec72603](https://linux-hardware.org/?probe=6f7ec72603) | Sep 18, 2020 |
| ASUSTek       | P5PL2-E                     | [034f119364](https://linux-hardware.org/?probe=034f119364) | Sep 17, 2020 |
| ASRock        | AM2NF3-VSTA                 | [7de59c54e2](https://linux-hardware.org/?probe=7de59c54e2) | Sep 17, 2020 |
| ASRock        | Z270 Professional Gaming... | [d580ac535d](https://linux-hardware.org/?probe=d580ac535d) | Sep 17, 2020 |
| ASRock        | H81M-VG4                    | [630e9d6c96](https://linux-hardware.org/?probe=630e9d6c96) | Sep 17, 2020 |
| ASUSTek       | P8Z77-V                     | [8115d3bd72](https://linux-hardware.org/?probe=8115d3bd72) | Sep 17, 2020 |
| ASUSTek       | P5PL2-E                     | [de75e16eb4](https://linux-hardware.org/?probe=de75e16eb4) | Sep 16, 2020 |
| Lenovo        | Board                       | [19fbf440bd](https://linux-hardware.org/?probe=19fbf440bd) | Sep 16, 2020 |
| Lenovo        | Board                       | [13d7b99190](https://linux-hardware.org/?probe=13d7b99190) | Sep 15, 2020 |
| Lenovo        | Board                       | [d2fec42b60](https://linux-hardware.org/?probe=d2fec42b60) | Sep 15, 2020 |
| ABIT          | F-I90HD                     | [3b4fba4f76](https://linux-hardware.org/?probe=3b4fba4f76) | Sep 15, 2020 |
| ABIT          | F-I90HD                     | [fa3222f6f2](https://linux-hardware.org/?probe=fa3222f6f2) | Sep 15, 2020 |
| HP            | 1850                        | [969552600c](https://linux-hardware.org/?probe=969552600c) | Sep 14, 2020 |
| HP            | 1850                        | [1d870fa36e](https://linux-hardware.org/?probe=1d870fa36e) | Sep 14, 2020 |
| ASUSTek       | H97-PLUS                    | [2728213546](https://linux-hardware.org/?probe=2728213546) | Sep 14, 2020 |
| ASUSTek       | H97-PLUS                    | [c84c3d3653](https://linux-hardware.org/?probe=c84c3d3653) | Sep 14, 2020 |
| Dell          | 0T656F A02                  | [8b713057f0](https://linux-hardware.org/?probe=8b713057f0) | Sep 14, 2020 |
| Dell          | 0T656F A02                  | [e571934792](https://linux-hardware.org/?probe=e571934792) | Sep 14, 2020 |
| ASRock        | N68-VS3 UCC                 | [3db1c50f81](https://linux-hardware.org/?probe=3db1c50f81) | Sep 13, 2020 |
| HP            | 2820h                       | [e846a8fdc1](https://linux-hardware.org/?probe=e846a8fdc1) | Sep 13, 2020 |
| HP            | 2820h                       | [c256ac5b2d](https://linux-hardware.org/?probe=c256ac5b2d) | Sep 13, 2020 |
| Dell          | 0KP561                      | [02690907c0](https://linux-hardware.org/?probe=02690907c0) | Sep 12, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [6732035bdb](https://linux-hardware.org/?probe=6732035bdb) | Sep 12, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [1d3b0acf1b](https://linux-hardware.org/?probe=1d3b0acf1b) | Sep 12, 2020 |
| ASRock        | Z270 Professional Gaming... | [396be1ec3c](https://linux-hardware.org/?probe=396be1ec3c) | Sep 12, 2020 |
| ASRock        | Z270 Professional Gaming... | [143a7cbca8](https://linux-hardware.org/?probe=143a7cbca8) | Sep 12, 2020 |
| Gigabyte      | X570 GAMING X               | [3fa9b2d5a3](https://linux-hardware.org/?probe=3fa9b2d5a3) | Sep 11, 2020 |
| Gigabyte      | X570 GAMING X               | [a6aa94288b](https://linux-hardware.org/?probe=a6aa94288b) | Sep 11, 2020 |
| ASRock        | 945GCM-S                    | [ea20683c56](https://linux-hardware.org/?probe=ea20683c56) | Sep 10, 2020 |
| Lenovo        | ThinkServer TS140           | [00e9c00fc4](https://linux-hardware.org/?probe=00e9c00fc4) | Sep 10, 2020 |
| Lenovo        | ThinkServer TS140           | [aa9d119ef8](https://linux-hardware.org/?probe=aa9d119ef8) | Sep 10, 2020 |
| Dell          | 0HH807                      | [7d7ee67969](https://linux-hardware.org/?probe=7d7ee67969) | Sep 10, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [290a511ed4](https://linux-hardware.org/?probe=290a511ed4) | Sep 09, 2020 |
| ASRock        | AM2NF3-VSTA                 | [90e5f3867a](https://linux-hardware.org/?probe=90e5f3867a) | Sep 09, 2020 |
| ASUSTek       | P5Q                         | [f67a33edb0](https://linux-hardware.org/?probe=f67a33edb0) | Sep 09, 2020 |
| ASRock        | N68-S3 UCC                  | [93c7826f5a](https://linux-hardware.org/?probe=93c7826f5a) | Sep 08, 2020 |
| ASRock        | N68-S3 UCC                  | [d2b4e2eee2](https://linux-hardware.org/?probe=d2b4e2eee2) | Sep 08, 2020 |
| ASRock        | 945GCM-S                    | [ea976442ff](https://linux-hardware.org/?probe=ea976442ff) | Sep 08, 2020 |
| ASRock        | 945GCM-S                    | [45fa5763dc](https://linux-hardware.org/?probe=45fa5763dc) | Sep 08, 2020 |
| ASRock        | Z270 Professional Gaming... | [a70c79f6dc](https://linux-hardware.org/?probe=a70c79f6dc) | Sep 08, 2020 |
| ASRock        | Z270 Professional Gaming... | [9dee0c84fd](https://linux-hardware.org/?probe=9dee0c84fd) | Sep 08, 2020 |
| ASUSTek       | P5Q                         | [68a53d1511](https://linux-hardware.org/?probe=68a53d1511) | Sep 08, 2020 |
| HP            | 1850                        | [317e774f45](https://linux-hardware.org/?probe=317e774f45) | Sep 07, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [6803b5780c](https://linux-hardware.org/?probe=6803b5780c) | Sep 07, 2020 |
| Gigabyte      | B360N WIFI-CF               | [35cfdd6e2f](https://linux-hardware.org/?probe=35cfdd6e2f) | Sep 07, 2020 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [71689e8e33](https://linux-hardware.org/?probe=71689e8e33) | Sep 07, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [a37c1863f7](https://linux-hardware.org/?probe=a37c1863f7) | Sep 07, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [93307c26cd](https://linux-hardware.org/?probe=93307c26cd) | Sep 07, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [a72ed6239a](https://linux-hardware.org/?probe=a72ed6239a) | Sep 06, 2020 |
| HP            | 2820h                       | [94ee523a7f](https://linux-hardware.org/?probe=94ee523a7f) | Sep 06, 2020 |
| Gigabyte      | F2A88XM-DS2                 | [9893916a95](https://linux-hardware.org/?probe=9893916a95) | Sep 06, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [3d2f901492](https://linux-hardware.org/?probe=3d2f901492) | Sep 06, 2020 |
| ASRock        | AB350M Pro4                 | [a8f43c7358](https://linux-hardware.org/?probe=a8f43c7358) | Sep 05, 2020 |
| ASRock        | AB350M Pro4                 | [e29615ab54](https://linux-hardware.org/?probe=e29615ab54) | Sep 05, 2020 |
| HP            | 1850                        | [3796bb6da6](https://linux-hardware.org/?probe=3796bb6da6) | Sep 05, 2020 |
| HP            | 2820h                       | [7cf6703210](https://linux-hardware.org/?probe=7cf6703210) | Sep 05, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [bccec91b12](https://linux-hardware.org/?probe=bccec91b12) | Sep 05, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [e1ea43d910](https://linux-hardware.org/?probe=e1ea43d910) | Sep 05, 2020 |
| ASUSTek       | AM1M-A                      | [8861d72b80](https://linux-hardware.org/?probe=8861d72b80) | Sep 04, 2020 |
| MSI           | G31M3-F V2                  | [f7201af112](https://linux-hardware.org/?probe=f7201af112) | Sep 04, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [c278fa5bfe](https://linux-hardware.org/?probe=c278fa5bfe) | Sep 04, 2020 |
| ASUSTek       | AM1M-A                      | [110f93b52c](https://linux-hardware.org/?probe=110f93b52c) | Sep 04, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [81072b442a](https://linux-hardware.org/?probe=81072b442a) | Sep 04, 2020 |
| HP            | 2820h                       | [5b50a9d615](https://linux-hardware.org/?probe=5b50a9d615) | Sep 04, 2020 |
| HP            | 2820h                       | [78352d40e0](https://linux-hardware.org/?probe=78352d40e0) | Sep 04, 2020 |
| ASRock        | AB350M Pro4                 | [a6d168e482](https://linux-hardware.org/?probe=a6d168e482) | Sep 03, 2020 |
| MSI           | G31M3-F V2                  | [26cb4879e9](https://linux-hardware.org/?probe=26cb4879e9) | Sep 03, 2020 |
| ASRock        | Z270 Professional Gaming... | [e0b65c9150](https://linux-hardware.org/?probe=e0b65c9150) | Sep 03, 2020 |
| ASRock        | Z270 Professional Gaming... | [05aff16c45](https://linux-hardware.org/?probe=05aff16c45) | Sep 03, 2020 |
| MSI           | G31M3-F V2                  | [e29a7853b6](https://linux-hardware.org/?probe=e29a7853b6) | Sep 02, 2020 |
| Gigabyte      | H61M-S1                     | [bace7e0044](https://linux-hardware.org/?probe=bace7e0044) | Sep 02, 2020 |
| Gigabyte      | H61M-S1                     | [5fecaf10f7](https://linux-hardware.org/?probe=5fecaf10f7) | Sep 02, 2020 |
| ASRock        | H61M-VG4                    | [a829cc528e](https://linux-hardware.org/?probe=a829cc528e) | Sep 01, 2020 |
| ASRock        | H61M-VG4                    | [898f88c7e1](https://linux-hardware.org/?probe=898f88c7e1) | Sep 01, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [d62134bc38](https://linux-hardware.org/?probe=d62134bc38) | Sep 01, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [d7efcacb33](https://linux-hardware.org/?probe=d7efcacb33) | Sep 01, 2020 |
| HP            | 3031h                       | [c2edafaa68](https://linux-hardware.org/?probe=c2edafaa68) | Sep 01, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [aa076e6629](https://linux-hardware.org/?probe=aa076e6629) | Aug 31, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [693ca5075d](https://linux-hardware.org/?probe=693ca5075d) | Aug 30, 2020 |
| HP            | 09F0h                       | [3b29ee3fd4](https://linux-hardware.org/?probe=3b29ee3fd4) | Aug 30, 2020 |
| HP            | 09F0h                       | [09d010b9ae](https://linux-hardware.org/?probe=09d010b9ae) | Aug 30, 2020 |
| Dell          | 0C27VV A01                  | [91433a9c70](https://linux-hardware.org/?probe=91433a9c70) | Aug 30, 2020 |
| Dell          | 0C27VV A01                  | [a379b0fa9c](https://linux-hardware.org/?probe=a379b0fa9c) | Aug 30, 2020 |
| Dell          | 0C27VV A01                  | [52dff95cda](https://linux-hardware.org/?probe=52dff95cda) | Aug 30, 2020 |
| HP            | 3047h                       | [57656e7ba8](https://linux-hardware.org/?probe=57656e7ba8) | Aug 29, 2020 |
| ASRock        | Z370 Killer SLI             | [1244135ba6](https://linux-hardware.org/?probe=1244135ba6) | Aug 29, 2020 |
| ASRock        | H81M-VG4                    | [87458c1f63](https://linux-hardware.org/?probe=87458c1f63) | Aug 29, 2020 |
| ASRock        | H81M-VG4                    | [585584fb38](https://linux-hardware.org/?probe=585584fb38) | Aug 29, 2020 |
| Gigabyte      | B85M-D3H                    | [434541db06](https://linux-hardware.org/?probe=434541db06) | Aug 29, 2020 |
| Gigabyte      | B85M-D3H                    | [9a1504121e](https://linux-hardware.org/?probe=9a1504121e) | Aug 29, 2020 |
| Dell          | 0782GW A00                  | [03bfdc1a33](https://linux-hardware.org/?probe=03bfdc1a33) | Aug 28, 2020 |
| ASRock        | FM2A75M Pro4+               | [ff6551cb4e](https://linux-hardware.org/?probe=ff6551cb4e) | Aug 28, 2020 |
| ASRock        | FM2A75M Pro4+               | [a36530f996](https://linux-hardware.org/?probe=a36530f996) | Aug 28, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0fe5bfbee7](https://linux-hardware.org/?probe=0fe5bfbee7) | Aug 28, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [016eeb0f51](https://linux-hardware.org/?probe=016eeb0f51) | Aug 28, 2020 |
| ASRock        | FM2A75M Pro4+               | [86560d42d8](https://linux-hardware.org/?probe=86560d42d8) | Aug 28, 2020 |
| ASRock        | FM2A75M Pro4+               | [39d36638c9](https://linux-hardware.org/?probe=39d36638c9) | Aug 28, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [aa73ecf76d](https://linux-hardware.org/?probe=aa73ecf76d) | Aug 28, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ee393f4f96](https://linux-hardware.org/?probe=ee393f4f96) | Aug 28, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f06fab9291](https://linux-hardware.org/?probe=f06fab9291) | Aug 28, 2020 |
| ASRock        | 970 Pro3 R2.0               | [232460fae7](https://linux-hardware.org/?probe=232460fae7) | Aug 27, 2020 |
| ASRock        | 970 Pro3 R2.0               | [d55dbedba0](https://linux-hardware.org/?probe=d55dbedba0) | Aug 27, 2020 |
| MSI           | 2A9C                        | [ca309cbde1](https://linux-hardware.org/?probe=ca309cbde1) | Aug 27, 2020 |
| Gigabyte      | B85M-D3H                    | [60981af61b](https://linux-hardware.org/?probe=60981af61b) | Aug 27, 2020 |
| Gigabyte      | B85M-D3H                    | [d2d7bda036](https://linux-hardware.org/?probe=d2d7bda036) | Aug 27, 2020 |
| Lenovo        | Board                       | [7927886a68](https://linux-hardware.org/?probe=7927886a68) | Aug 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [92580a13f5](https://linux-hardware.org/?probe=92580a13f5) | Aug 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [c2a9a69b1c](https://linux-hardware.org/?probe=c2a9a69b1c) | Aug 26, 2020 |
| ASRock        | A320M-DVS R4.0              | [22467d7e8b](https://linux-hardware.org/?probe=22467d7e8b) | Aug 26, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [9c29b00911](https://linux-hardware.org/?probe=9c29b00911) | Aug 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [78592df384](https://linux-hardware.org/?probe=78592df384) | Aug 26, 2020 |
| MSI           | 2A9C                        | [ca92098ba7](https://linux-hardware.org/?probe=ca92098ba7) | Aug 26, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [01eaf76eca](https://linux-hardware.org/?probe=01eaf76eca) | Aug 25, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [31ff878740](https://linux-hardware.org/?probe=31ff878740) | Aug 25, 2020 |
| ASRock        | A320M-DVS R4.0              | [fb41b369a3](https://linux-hardware.org/?probe=fb41b369a3) | Aug 25, 2020 |
| Gigabyte      | X570 AORUS PRO              | [0faed02af4](https://linux-hardware.org/?probe=0faed02af4) | Aug 25, 2020 |
| Gigabyte      | X570 AORUS PRO              | [28479b61d1](https://linux-hardware.org/?probe=28479b61d1) | Aug 25, 2020 |
| HP            | 3031h                       | [8d684e591f](https://linux-hardware.org/?probe=8d684e591f) | Aug 25, 2020 |
| Lenovo        | SHARKBAY NOK                | [877f4bd195](https://linux-hardware.org/?probe=877f4bd195) | Aug 25, 2020 |
| Lenovo        | SHARKBAY NOK                | [acae2f1c50](https://linux-hardware.org/?probe=acae2f1c50) | Aug 25, 2020 |
| Gigabyte      | X570 AORUS PRO              | [765ff1a786](https://linux-hardware.org/?probe=765ff1a786) | Aug 25, 2020 |
| Dell          | 0KP561                      | [82b6295c53](https://linux-hardware.org/?probe=82b6295c53) | Aug 24, 2020 |
| Gigabyte      | P61-USB3-B3                 | [9ecd34fe2e](https://linux-hardware.org/?probe=9ecd34fe2e) | Aug 24, 2020 |
| Gigabyte      | B85M-D3H                    | [9e7655fff6](https://linux-hardware.org/?probe=9e7655fff6) | Aug 23, 2020 |
| Gigabyte      | B85M-D3H                    | [a000d8825a](https://linux-hardware.org/?probe=a000d8825a) | Aug 23, 2020 |
| Lenovo        | Board                       | [5c00a0d413](https://linux-hardware.org/?probe=5c00a0d413) | Aug 23, 2020 |
| Lenovo        | Board                       | [0b4aa4ca34](https://linux-hardware.org/?probe=0b4aa4ca34) | Aug 23, 2020 |
| Gigabyte      | X570 AORUS PRO              | [466173dd1f](https://linux-hardware.org/?probe=466173dd1f) | Aug 23, 2020 |
| Gigabyte      | X570 AORUS PRO              | [e28cf8bc3f](https://linux-hardware.org/?probe=e28cf8bc3f) | Aug 23, 2020 |
| Gigabyte      | X570 AORUS PRO              | [e21e088473](https://linux-hardware.org/?probe=e21e088473) | Aug 23, 2020 |
| Gigabyte      | B450 AORUS M                | [662336896f](https://linux-hardware.org/?probe=662336896f) | Aug 23, 2020 |
| Gigabyte      | H61M-D2-B3                  | [0383089f76](https://linux-hardware.org/?probe=0383089f76) | Aug 23, 2020 |
| Gigabyte      | B85M-D3H                    | [a55cc31e1d](https://linux-hardware.org/?probe=a55cc31e1d) | Aug 23, 2020 |
| Gigabyte      | B85M-D3H                    | [a0a9d60a96](https://linux-hardware.org/?probe=a0a9d60a96) | Aug 23, 2020 |
| Gigabyte      | B85M-DS3H                   | [4d190a0b79](https://linux-hardware.org/?probe=4d190a0b79) | Aug 22, 2020 |
| Gigabyte      | B85M-DS3H                   | [2fe644816e](https://linux-hardware.org/?probe=2fe644816e) | Aug 22, 2020 |
| Dell          | 0782GW A00                  | [a9576f5520](https://linux-hardware.org/?probe=a9576f5520) | Aug 22, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [2f2cd90fee](https://linux-hardware.org/?probe=2f2cd90fee) | Aug 22, 2020 |
| HP            | 1850                        | [01b14e6c6a](https://linux-hardware.org/?probe=01b14e6c6a) | Aug 21, 2020 |
| HP            | 1850                        | [5aae864176](https://linux-hardware.org/?probe=5aae864176) | Aug 21, 2020 |
| ASRock        | Z370 Killer SLI             | [b44ea23a59](https://linux-hardware.org/?probe=b44ea23a59) | Aug 21, 2020 |
| ASRock        | Z370 Killer SLI             | [376d430471](https://linux-hardware.org/?probe=376d430471) | Aug 21, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [ff5ba50b6a](https://linux-hardware.org/?probe=ff5ba50b6a) | Aug 21, 2020 |
| Lenovo        | Board                       | [dd8a86d862](https://linux-hardware.org/?probe=dd8a86d862) | Aug 20, 2020 |
| Dell          | 0782GW A00                  | [19ee874e3e](https://linux-hardware.org/?probe=19ee874e3e) | Aug 20, 2020 |
| Gigabyte      | B450 AORUS M                | [87be7d55ee](https://linux-hardware.org/?probe=87be7d55ee) | Aug 20, 2020 |
| Gigabyte      | B450 AORUS M                | [a0364553f5](https://linux-hardware.org/?probe=a0364553f5) | Aug 20, 2020 |
| MSI           | 2A9C                        | [afaebe81a7](https://linux-hardware.org/?probe=afaebe81a7) | Aug 20, 2020 |
| MSI           | 2A9C                        | [a3ef9588ad](https://linux-hardware.org/?probe=a3ef9588ad) | Aug 20, 2020 |
| Gigabyte      | B85M-DS3H                   | [9b84f5c56d](https://linux-hardware.org/?probe=9b84f5c56d) | Aug 20, 2020 |
| HP            | 0A64h                       | [09736ec014](https://linux-hardware.org/?probe=09736ec014) | Aug 20, 2020 |
| ASRock        | AM2NF3-VSTA                 | [58ea95e8ac](https://linux-hardware.org/?probe=58ea95e8ac) | Aug 20, 2020 |
| MSI           | H67MA-E35                   | [3147984b92](https://linux-hardware.org/?probe=3147984b92) | Aug 20, 2020 |
| ASUSTek       | M5A97 R2.0                  | [216727a6bd](https://linux-hardware.org/?probe=216727a6bd) | Aug 19, 2020 |
| HP            | 21EF                        | [bc9d42df4a](https://linux-hardware.org/?probe=bc9d42df4a) | Aug 19, 2020 |
| HP            | 21EF                        | [64e7df4bb9](https://linux-hardware.org/?probe=64e7df4bb9) | Aug 19, 2020 |
| MSI           | H67MA-E35                   | [4b8b630472](https://linux-hardware.org/?probe=4b8b630472) | Aug 19, 2020 |
| ASRock        | H110M-HDV R3.0              | [b3d54f6eae](https://linux-hardware.org/?probe=b3d54f6eae) | Aug 18, 2020 |
| Dell          | 0M5DCD A00                  | [529d3be359](https://linux-hardware.org/?probe=529d3be359) | Aug 18, 2020 |
| Dell          | 0M5DCD A00                  | [0f39a82fcf](https://linux-hardware.org/?probe=0f39a82fcf) | Aug 18, 2020 |
| Dell          | 0TY565                      | [3c1f0efe58](https://linux-hardware.org/?probe=3c1f0efe58) | Aug 18, 2020 |
| Dell          | 0TY565                      | [24460fa374](https://linux-hardware.org/?probe=24460fa374) | Aug 18, 2020 |
| Gigabyte      | B450 GAMING X               | [cc5c0b0ef3](https://linux-hardware.org/?probe=cc5c0b0ef3) | Aug 18, 2020 |
| Gigabyte      | B450 GAMING X               | [7a88c254fb](https://linux-hardware.org/?probe=7a88c254fb) | Aug 18, 2020 |
| Gigabyte      | M68M-S2P                    | [d81b12825f](https://linux-hardware.org/?probe=d81b12825f) | Aug 18, 2020 |
| Gigabyte      | M68M-S2P                    | [e5e453d4ee](https://linux-hardware.org/?probe=e5e453d4ee) | Aug 18, 2020 |
| MSI           | 870A-G54                    | [fe52fdc14e](https://linux-hardware.org/?probe=fe52fdc14e) | Aug 18, 2020 |
| Gigabyte      | H81M-S2H                    | [5ee1a0c476](https://linux-hardware.org/?probe=5ee1a0c476) | Aug 18, 2020 |
| ASUSTek       | A88X-PRO                    | [5b93129aff](https://linux-hardware.org/?probe=5b93129aff) | Aug 18, 2020 |
| Lenovo        | Board                       | [e331ccf06e](https://linux-hardware.org/?probe=e331ccf06e) | Aug 18, 2020 |
| Lenovo        | Board                       | [7976b1e1a5](https://linux-hardware.org/?probe=7976b1e1a5) | Aug 18, 2020 |
| HP            | 1494                        | [2a4871f0b1](https://linux-hardware.org/?probe=2a4871f0b1) | Aug 18, 2020 |
| Gigabyte      | EP31-DS3L                   | [fa34875d1f](https://linux-hardware.org/?probe=fa34875d1f) | Aug 18, 2020 |
| Gigabyte      | H81M-S2H                    | [ebcb51fd6a](https://linux-hardware.org/?probe=ebcb51fd6a) | Aug 18, 2020 |
| Gigabyte      | B85M-DS3H                   | [187d7f9d43](https://linux-hardware.org/?probe=187d7f9d43) | Aug 18, 2020 |
| MSI           | 870A-G54                    | [db045621cd](https://linux-hardware.org/?probe=db045621cd) | Aug 18, 2020 |
| ASRock        | FM2A75M Pro4+               | [a689aaa0b0](https://linux-hardware.org/?probe=a689aaa0b0) | Aug 17, 2020 |
| ASRock        | H110M-HDV R3.0              | [bc32d2c642](https://linux-hardware.org/?probe=bc32d2c642) | Aug 17, 2020 |
| ASRock        | FM2A75M Pro4+               | [9f99a6d0a2](https://linux-hardware.org/?probe=9f99a6d0a2) | Aug 17, 2020 |
| MSI           | 870A-G54                    | [2ebcd87834](https://linux-hardware.org/?probe=2ebcd87834) | Aug 17, 2020 |
| MSI           | 870A-G54                    | [4e6da88fcf](https://linux-hardware.org/?probe=4e6da88fcf) | Aug 17, 2020 |
| MSI           | 870A-G54                    | [9fb9dc5056](https://linux-hardware.org/?probe=9fb9dc5056) | Aug 17, 2020 |
| Gigabyte      | EP31-DS3L                   | [1b99508676](https://linux-hardware.org/?probe=1b99508676) | Aug 17, 2020 |
| Gigabyte      | EP31-DS3L                   | [758cb6cf5b](https://linux-hardware.org/?probe=758cb6cf5b) | Aug 17, 2020 |
| Gigabyte      | B85M-DS3H                   | [85022d2f23](https://linux-hardware.org/?probe=85022d2f23) | Aug 17, 2020 |
| MSI           | 760GM -E51                  | [3f37580f3f](https://linux-hardware.org/?probe=3f37580f3f) | Aug 17, 2020 |
| MSI           | 760GM -E51                  | [5f9062b119](https://linux-hardware.org/?probe=5f9062b119) | Aug 17, 2020 |
| HP            | 3032h                       | [a51111cef5](https://linux-hardware.org/?probe=a51111cef5) | Aug 17, 2020 |
| HP            | 3032h                       | [30cbc45362](https://linux-hardware.org/?probe=30cbc45362) | Aug 17, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [3d8c960f2b](https://linux-hardware.org/?probe=3d8c960f2b) | Aug 17, 2020 |
| ASUSTek       | P5PL2-E                     | [ce31f485a9](https://linux-hardware.org/?probe=ce31f485a9) | Aug 16, 2020 |
| Lenovo        | Board                       | [3c9b7dcc49](https://linux-hardware.org/?probe=3c9b7dcc49) | Aug 16, 2020 |
| ASUSTek       | P5PL2-E                     | [8092432213](https://linux-hardware.org/?probe=8092432213) | Aug 16, 2020 |
| Lenovo        | Board                       | [f689b34cc9](https://linux-hardware.org/?probe=f689b34cc9) | Aug 16, 2020 |
| ASRock        | FM2A75M Pro4+               | [1dc2ae1f3d](https://linux-hardware.org/?probe=1dc2ae1f3d) | Aug 15, 2020 |
| Lenovo        | Board                       | [42ff4aec83](https://linux-hardware.org/?probe=42ff4aec83) | Aug 15, 2020 |
| ABIT          | IL8                         | [612d7f845d](https://linux-hardware.org/?probe=612d7f845d) | Aug 15, 2020 |
| Gigabyte      | G41M-ES2L                   | [de26560b15](https://linux-hardware.org/?probe=de26560b15) | Aug 15, 2020 |
| ABIT          | IL8                         | [4f59d75b3e](https://linux-hardware.org/?probe=4f59d75b3e) | Aug 15, 2020 |
| Gigabyte      | G41M-ES2L                   | [880bd2a7de](https://linux-hardware.org/?probe=880bd2a7de) | Aug 15, 2020 |
| ASRock        | H81 Pro BTC R2.0            | [79cff83ed2](https://linux-hardware.org/?probe=79cff83ed2) | Aug 15, 2020 |
| ASUSTek       | P5K                         | [f5f7c64a4b](https://linux-hardware.org/?probe=f5f7c64a4b) | Aug 15, 2020 |
| ASUSTek       | P5K                         | [e75a7ecc71](https://linux-hardware.org/?probe=e75a7ecc71) | Aug 15, 2020 |
| ASRock        | FM2A85X Extreme4            | [01908c3d01](https://linux-hardware.org/?probe=01908c3d01) | Aug 15, 2020 |
| ASRock        | FM2A85X Extreme4            | [0643f403ff](https://linux-hardware.org/?probe=0643f403ff) | Aug 15, 2020 |
| ASRock        | 945GCM-S                    | [70fdd7aaa7](https://linux-hardware.org/?probe=70fdd7aaa7) | Aug 15, 2020 |
| Gigabyte      | B85M-DS3H                   | [a4bd744fb3](https://linux-hardware.org/?probe=a4bd744fb3) | Aug 15, 2020 |
| ASRock        | Z77 Extreme4-M              | [e8127d929e](https://linux-hardware.org/?probe=e8127d929e) | Aug 15, 2020 |
| ASRock        | Z77 Extreme4-M              | [d50ee79f61](https://linux-hardware.org/?probe=d50ee79f61) | Aug 15, 2020 |
| MSI           | 870A-G54                    | [3e2cbc53f7](https://linux-hardware.org/?probe=3e2cbc53f7) | Aug 15, 2020 |
| Lenovo        | Board                       | [5c854c4ec2](https://linux-hardware.org/?probe=5c854c4ec2) | Aug 15, 2020 |
| MSI           | 2A9C                        | [23a6bd0572](https://linux-hardware.org/?probe=23a6bd0572) | Aug 14, 2020 |
| MSI           | 2A9C                        | [e227591817](https://linux-hardware.org/?probe=e227591817) | Aug 14, 2020 |
| ASRock        | 945GCM-S                    | [c4119749d3](https://linux-hardware.org/?probe=c4119749d3) | Aug 14, 2020 |
| ASUSTek       | M2N-MX SE                   | [718c95f99d](https://linux-hardware.org/?probe=718c95f99d) | Aug 13, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [aa3690c11e](https://linux-hardware.org/?probe=aa3690c11e) | Aug 13, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [3f64fad650](https://linux-hardware.org/?probe=3f64fad650) | Aug 13, 2020 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [fa2d57b6e1](https://linux-hardware.org/?probe=fa2d57b6e1) | Aug 13, 2020 |
| Dell          | 0MN1TX A03                  | [b86f5e25b6](https://linux-hardware.org/?probe=b86f5e25b6) | Aug 12, 2020 |
| ASUSTek       | P5LD2-VM                    | [b7a6e48dfd](https://linux-hardware.org/?probe=b7a6e48dfd) | Aug 12, 2020 |
| ASRock        | 945GCM-S                    | [1b4999d718](https://linux-hardware.org/?probe=1b4999d718) | Aug 12, 2020 |
| ASRock        | 945GCM-S                    | [d26fb201c6](https://linux-hardware.org/?probe=d26fb201c6) | Aug 12, 2020 |
| Gigabyte      | G41M-ES2L                   | [fdb3226f5a](https://linux-hardware.org/?probe=fdb3226f5a) | Aug 12, 2020 |
| Gigabyte      | G41M-ES2L                   | [391c86924b](https://linux-hardware.org/?probe=391c86924b) | Aug 11, 2020 |
| Gigabyte      | G41M-ES2L                   | [dd68ede03f](https://linux-hardware.org/?probe=dd68ede03f) | Aug 11, 2020 |
| MSI           | 2A9C                        | [2e19cc35fe](https://linux-hardware.org/?probe=2e19cc35fe) | Aug 11, 2020 |
| Foxconn       | 2A8C                        | [f0593b10e6](https://linux-hardware.org/?probe=f0593b10e6) | Aug 11, 2020 |
| HP            | 1850                        | [f9c8eb714f](https://linux-hardware.org/?probe=f9c8eb714f) | Aug 11, 2020 |
| Foxconn       | 2A8C                        | [174e5da334](https://linux-hardware.org/?probe=174e5da334) | Aug 11, 2020 |
| HP            | 1850                        | [c62feba028](https://linux-hardware.org/?probe=c62feba028) | Aug 11, 2020 |
| Lenovo        | Board                       | [38e662cd9f](https://linux-hardware.org/?probe=38e662cd9f) | Aug 10, 2020 |
| Gigabyte      | B360N WIFI-CF               | [d71b2e9af6](https://linux-hardware.org/?probe=d71b2e9af6) | Aug 10, 2020 |
| Lenovo        | Board                       | [bf7f7f7bf8](https://linux-hardware.org/?probe=bf7f7f7bf8) | Aug 10, 2020 |
| Lenovo        | Board                       | [431d7d667c](https://linux-hardware.org/?probe=431d7d667c) | Aug 10, 2020 |
| Gigabyte      | P55-USB3                    | [c9a09717f5](https://linux-hardware.org/?probe=c9a09717f5) | Aug 09, 2020 |
| Lenovo        | Board                       | [d60cc6078f](https://linux-hardware.org/?probe=d60cc6078f) | Aug 09, 2020 |
| Unknown       | Unknown                     | [cac38ad57b](https://linux-hardware.org/?probe=cac38ad57b) | Aug 08, 2020 |
| Gigabyte      | P55-USB3                    | [7b2575cd8b](https://linux-hardware.org/?probe=7b2575cd8b) | Aug 08, 2020 |
| Gigabyte      | PH67-DS3-B3                 | [d3f8ea2959](https://linux-hardware.org/?probe=d3f8ea2959) | Aug 08, 2020 |
| Gigabyte      | PH67-DS3-B3                 | [37cde24e51](https://linux-hardware.org/?probe=37cde24e51) | Aug 08, 2020 |
| ASUSTek       | A88XM-PLUS                  | [5ce36fc195](https://linux-hardware.org/?probe=5ce36fc195) | Aug 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [f72b099883](https://linux-hardware.org/?probe=f72b099883) | Aug 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2cd5ca5dc8](https://linux-hardware.org/?probe=2cd5ca5dc8) | Aug 07, 2020 |
| ASRock        | FM2A88M Extreme4+           | [011f90431a](https://linux-hardware.org/?probe=011f90431a) | Aug 06, 2020 |
| Dell          | 0C27VV A01                  | [c5d97db12a](https://linux-hardware.org/?probe=c5d97db12a) | Aug 06, 2020 |
| ASRock        | FM2A88M Extreme4+           | [97f7bf23f9](https://linux-hardware.org/?probe=97f7bf23f9) | Aug 06, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | [b2f8fb00d2](https://linux-hardware.org/?probe=b2f8fb00d2) | Aug 06, 2020 |
| ASRock        | 880GM-LE                    | [889e3debf5](https://linux-hardware.org/?probe=889e3debf5) | Aug 06, 2020 |
| Unknown       | 4Core1333-eSATA2            | [6c98b08f20](https://linux-hardware.org/?probe=6c98b08f20) | Aug 06, 2020 |
| Unknown       | 4Core1333-eSATA2            | [2e45ebe11b](https://linux-hardware.org/?probe=2e45ebe11b) | Aug 06, 2020 |
| HP            | ProLiant MicroServer        | [ff52284235](https://linux-hardware.org/?probe=ff52284235) | Aug 05, 2020 |
| HP            | ProLiant MicroServer        | [e4d516d280](https://linux-hardware.org/?probe=e4d516d280) | Aug 05, 2020 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [393f2687a1](https://linux-hardware.org/?probe=393f2687a1) | Aug 05, 2020 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [0582a3bfb5](https://linux-hardware.org/?probe=0582a3bfb5) | Aug 05, 2020 |
| Dell          | 0C27VV A01                  | [1dcafe483a](https://linux-hardware.org/?probe=1dcafe483a) | Aug 04, 2020 |
| MSI           | 2A9C                        | [4c1f2ac9e7](https://linux-hardware.org/?probe=4c1f2ac9e7) | Aug 04, 2020 |
| MSI           | 2A9C                        | [380a2e06c0](https://linux-hardware.org/?probe=380a2e06c0) | Aug 04, 2020 |
| MSI           | 2A9C                        | [207500f8cb](https://linux-hardware.org/?probe=207500f8cb) | Aug 03, 2020 |
| ASUSTek       | STRIX H270I GAMING          | [3172951074](https://linux-hardware.org/?probe=3172951074) | Aug 03, 2020 |
| MSI           | A320M PRO-E                 | [2f6073428b](https://linux-hardware.org/?probe=2f6073428b) | Aug 03, 2020 |
| MSI           | A320M PRO-E                 | [b417f503ca](https://linux-hardware.org/?probe=b417f503ca) | Aug 03, 2020 |
| HP            | 3032h                       | [ae7a96563e](https://linux-hardware.org/?probe=ae7a96563e) | Aug 03, 2020 |
| Gigabyte      | 8I915GMF                    | [1640fa1306](https://linux-hardware.org/?probe=1640fa1306) | Aug 02, 2020 |
| ASRock        | 970M Pro3                   | [852e2a5211](https://linux-hardware.org/?probe=852e2a5211) | Aug 02, 2020 |
| Gigabyte      | B360N WIFI-CF               | [199424d4a0](https://linux-hardware.org/?probe=199424d4a0) | Aug 02, 2020 |
| ASRock        | 970M Pro3                   | [b1224f87ef](https://linux-hardware.org/?probe=b1224f87ef) | Aug 01, 2020 |
| Dell          | 0YP693 A02                  | [87c804f90a](https://linux-hardware.org/?probe=87c804f90a) | Aug 01, 2020 |
| Dell          | 0YP693 A02                  | [1b9e67c6ac](https://linux-hardware.org/?probe=1b9e67c6ac) | Aug 01, 2020 |
| Gigabyte      | H170-D3HP-CF                | [25353149f4](https://linux-hardware.org/?probe=25353149f4) | Aug 01, 2020 |
| Gigabyte      | H170-D3HP-CF                | [4f3a95ebc2](https://linux-hardware.org/?probe=4f3a95ebc2) | Aug 01, 2020 |
| MSI           | 2A9C                        | [dc0f85769a](https://linux-hardware.org/?probe=dc0f85769a) | Aug 01, 2020 |
| MSI           | 2A9C                        | [03b5ba79ce](https://linux-hardware.org/?probe=03b5ba79ce) | Jul 31, 2020 |
| ASRock        | H110M-HDV R3.0              | [1bfb1a21e2](https://linux-hardware.org/?probe=1bfb1a21e2) | Jul 31, 2020 |
| HP            | 0A64h                       | [4840f60304](https://linux-hardware.org/?probe=4840f60304) | Jul 31, 2020 |
| Gigabyte      | X570 GAMING X               | [e0d443cd9f](https://linux-hardware.org/?probe=e0d443cd9f) | Jul 30, 2020 |
| HP            | 3397                        | [d0075e1c66](https://linux-hardware.org/?probe=d0075e1c66) | Jul 29, 2020 |
| ASRock        | Z370 Gaming K6              | [d2b117ce8f](https://linux-hardware.org/?probe=d2b117ce8f) | Jul 29, 2020 |
| HP            | 3397                        | [b1758cd724](https://linux-hardware.org/?probe=b1758cd724) | Jul 29, 2020 |
| ASUSTek       | P8Z77-V LX2                 | [9fcf6bec59](https://linux-hardware.org/?probe=9fcf6bec59) | Jul 29, 2020 |
| MSI           | 2A9C                        | [244196ee5e](https://linux-hardware.org/?probe=244196ee5e) | Jul 28, 2020 |
| MSI           | 2A9C                        | [cd1f47d4ed](https://linux-hardware.org/?probe=cd1f47d4ed) | Jul 28, 2020 |
| MSI           | 2A9C                        | [011795706b](https://linux-hardware.org/?probe=011795706b) | Jul 28, 2020 |
| MSI           | H110M PRO-VD                | [9c61fc1174](https://linux-hardware.org/?probe=9c61fc1174) | Jul 27, 2020 |
| HP            | 3397                        | [ff77bd35fc](https://linux-hardware.org/?probe=ff77bd35fc) | Jul 27, 2020 |
| Dell          | 0GY6Y8 A02                  | [1c101ad7ed](https://linux-hardware.org/?probe=1c101ad7ed) | Jul 27, 2020 |
| Medion        | B75MA-P45                   | [76ebe37688](https://linux-hardware.org/?probe=76ebe37688) | Jul 26, 2020 |
| Gigabyte      | P55-USB3                    | [57c5ff20d8](https://linux-hardware.org/?probe=57c5ff20d8) | Jul 25, 2020 |
| ASUSTek       | PRIME B550M-K               | [af74715e7f](https://linux-hardware.org/?probe=af74715e7f) | Jul 25, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [18441ff5a8](https://linux-hardware.org/?probe=18441ff5a8) | Jul 24, 2020 |
| ASUSTek       | PRIME B550M-K               | [38d7ad1ec6](https://linux-hardware.org/?probe=38d7ad1ec6) | Jul 24, 2020 |
| Gigabyte      | P55-USB3                    | [d82eabf22d](https://linux-hardware.org/?probe=d82eabf22d) | Jul 24, 2020 |
| Acer          | Revo 70                     | [2165f3ed5a](https://linux-hardware.org/?probe=2165f3ed5a) | Jul 24, 2020 |
| Acer          | Revo 70                     | [7f227506b2](https://linux-hardware.org/?probe=7f227506b2) | Jul 24, 2020 |
| Gigabyte      | H61M-D2-B3                  | [ea87f767dc](https://linux-hardware.org/?probe=ea87f767dc) | Jul 23, 2020 |
| Gigabyte      | H61M-D2-B3                  | [251b1af376](https://linux-hardware.org/?probe=251b1af376) | Jul 23, 2020 |
| Dell          | 08WKV3 A00                  | [05a9a07ee6](https://linux-hardware.org/?probe=05a9a07ee6) | Jul 23, 2020 |
| MSI           | H110M PRO-VD                | [810ca72a0b](https://linux-hardware.org/?probe=810ca72a0b) | Jul 23, 2020 |
| ASUSTek       | PRIME A320M-R               | [e5e81d86f8](https://linux-hardware.org/?probe=e5e81d86f8) | Jul 22, 2020 |
| ASUSTek       | PRIME A320M-R               | [ef328ad6f5](https://linux-hardware.org/?probe=ef328ad6f5) | Jul 22, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [33edc05ea1](https://linux-hardware.org/?probe=33edc05ea1) | Jul 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [58fd584cac](https://linux-hardware.org/?probe=58fd584cac) | Jul 22, 2020 |
| ASUSTek       | M5A97 R2.0                  | [57076d5dea](https://linux-hardware.org/?probe=57076d5dea) | Jul 21, 2020 |
| Unknown       | SKYBAY                      | [eae408aac8](https://linux-hardware.org/?probe=eae408aac8) | Jul 21, 2020 |
| MSI           | H81M-P33                    | [b3d4f0e7de](https://linux-hardware.org/?probe=b3d4f0e7de) | Jul 21, 2020 |
| MSI           | H81M-P33                    | [921cf0840a](https://linux-hardware.org/?probe=921cf0840a) | Jul 21, 2020 |
| Gigabyte      | B85M-DS3H                   | [be165d3b32](https://linux-hardware.org/?probe=be165d3b32) | Jul 21, 2020 |
| Gigabyte      | B85M-DS3H                   | [333267bd9d](https://linux-hardware.org/?probe=333267bd9d) | Jul 21, 2020 |
| Gigabyte      | H61M-D2-B3                  | [f60aa20ad8](https://linux-hardware.org/?probe=f60aa20ad8) | Jul 20, 2020 |
| ASRock        | H61M-VG4                    | [8f3bdd22c9](https://linux-hardware.org/?probe=8f3bdd22c9) | Jul 19, 2020 |
| ASRock        | H61M-VG4                    | [a758f7e594](https://linux-hardware.org/?probe=a758f7e594) | Jul 19, 2020 |
| Gigabyte      | H61M-D2-B3                  | [da4d7d66bf](https://linux-hardware.org/?probe=da4d7d66bf) | Jul 19, 2020 |
| Acer          | RS880M05                    | [558840528d](https://linux-hardware.org/?probe=558840528d) | Jul 19, 2020 |
| ASUSTek       | M5A97 R2.0                  | [9153b65349](https://linux-hardware.org/?probe=9153b65349) | Jul 19, 2020 |
| MSI           | H110M PRO-VD                | [c2160c6bbd](https://linux-hardware.org/?probe=c2160c6bbd) | Jul 19, 2020 |
| Gigabyte      | B85M-DS3H                   | [162bc3487e](https://linux-hardware.org/?probe=162bc3487e) | Jul 19, 2020 |
| Gigabyte      | B85M-DS3H                   | [fe3aa70a35](https://linux-hardware.org/?probe=fe3aa70a35) | Jul 19, 2020 |
| Dell          | 0WG864                      | [57017d9751](https://linux-hardware.org/?probe=57017d9751) | Jul 19, 2020 |
| ASUSTek       | M5A97 R2.0                  | [9d69493a63](https://linux-hardware.org/?probe=9d69493a63) | Jul 18, 2020 |
| ASUSTek       | VM40B                       | [8a1e26281e](https://linux-hardware.org/?probe=8a1e26281e) | Jul 18, 2020 |
| ASUSTek       | VM40B                       | [b4e37ad8d4](https://linux-hardware.org/?probe=b4e37ad8d4) | Jul 18, 2020 |
| ASUSTek       | PRIME B550M-K               | [1bc84f716e](https://linux-hardware.org/?probe=1bc84f716e) | Jul 18, 2020 |
| Gigabyte      | H61M-D2-B3                  | [d05475e162](https://linux-hardware.org/?probe=d05475e162) | Jul 18, 2020 |
| ASRock        | FM2A58M-VG3+ R2.0           | [18294281b8](https://linux-hardware.org/?probe=18294281b8) | Jul 17, 2020 |
| ASRock        | H61M-VG4                    | [9774abb0c8](https://linux-hardware.org/?probe=9774abb0c8) | Jul 17, 2020 |
| ASRock        | H61M-VG4                    | [326fe38162](https://linux-hardware.org/?probe=326fe38162) | Jul 17, 2020 |
| ASUSTek       | PRIME B550M-K               | [c5e6addebb](https://linux-hardware.org/?probe=c5e6addebb) | Jul 17, 2020 |
| Gigabyte      | H61M-D2-B3                  | [669dfc19ac](https://linux-hardware.org/?probe=669dfc19ac) | Jul 17, 2020 |
| ASUSTek       | SABERTOOTH X58              | [683c309aef](https://linux-hardware.org/?probe=683c309aef) | Jul 16, 2020 |
| Gigabyte      | H61M-D2-B3                  | [3eca21386c](https://linux-hardware.org/?probe=3eca21386c) | Jul 16, 2020 |
| ASUSTek       | SABERTOOTH X58              | [fd090d55ee](https://linux-hardware.org/?probe=fd090d55ee) | Jul 16, 2020 |
| Lenovo        | Board                       | [c7d16ba4c1](https://linux-hardware.org/?probe=c7d16ba4c1) | Jul 16, 2020 |
| Lenovo        | Board                       | [b1e51f2e06](https://linux-hardware.org/?probe=b1e51f2e06) | Jul 16, 2020 |
| Gigabyte      | H61M-D2-B3                  | [282e2fbd13](https://linux-hardware.org/?probe=282e2fbd13) | Jul 16, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [14b35fa973](https://linux-hardware.org/?probe=14b35fa973) | Jul 15, 2020 |
| Gigabyte      | Z270-HD3P-CF                | [e73d6b9695](https://linux-hardware.org/?probe=e73d6b9695) | Jul 15, 2020 |
| Gigabyte      | H61M-D2-B3                  | [28b1e9918d](https://linux-hardware.org/?probe=28b1e9918d) | Jul 13, 2020 |
| Gigabyte      | H61M-D2-B3                  | [5070c7cc70](https://linux-hardware.org/?probe=5070c7cc70) | Jul 13, 2020 |
| Dell          | 0WMJ54 A01                  | [d1739b30ff](https://linux-hardware.org/?probe=d1739b30ff) | Jul 13, 2020 |
| Dell          | 0WMJ54 A01                  | [e194a84474](https://linux-hardware.org/?probe=e194a84474) | Jul 13, 2020 |
| Medion        | B75MA-P45                   | [653bfde125](https://linux-hardware.org/?probe=653bfde125) | Jul 12, 2020 |
| HP            | 339A                        | [0f20e771d7](https://linux-hardware.org/?probe=0f20e771d7) | Jul 12, 2020 |
| HP            | 339A                        | [1c989fdd21](https://linux-hardware.org/?probe=1c989fdd21) | Jul 12, 2020 |
| Gigabyte      | X48-DS5                     | [186a5f354f](https://linux-hardware.org/?probe=186a5f354f) | Jul 11, 2020 |
| Dell          | 0Y2MRG A00                  | [18352e9ee5](https://linux-hardware.org/?probe=18352e9ee5) | Jul 11, 2020 |
| Gigabyte      | H61M-S2V-B3                 | [f8cdfb01d3](https://linux-hardware.org/?probe=f8cdfb01d3) | Jul 11, 2020 |
| Gigabyte      | 970A-DS3P                   | [d9e8d336dd](https://linux-hardware.org/?probe=d9e8d336dd) | Jul 10, 2020 |
| ASUSTek       | H110M-R                     | [dc1736982c](https://linux-hardware.org/?probe=dc1736982c) | Jul 10, 2020 |
| ASUSTek       | H110M-R                     | [8994d66047](https://linux-hardware.org/?probe=8994d66047) | Jul 10, 2020 |
| Lenovo        | Board                       | [579ba828e9](https://linux-hardware.org/?probe=579ba828e9) | Jul 10, 2020 |
| ASUSTek       | P5G41T-M LX3                | [9eb845703c](https://linux-hardware.org/?probe=9eb845703c) | Jul 09, 2020 |
| Intel         | DH61BE AAG14062-212         | [304bf0f19e](https://linux-hardware.org/?probe=304bf0f19e) | Jul 08, 2020 |
| ASUSTek       | B150 PRO GAMING             | [f5d3c0e198](https://linux-hardware.org/?probe=f5d3c0e198) | Jul 08, 2020 |
| Lenovo        | Board                       | [37d2645039](https://linux-hardware.org/?probe=37d2645039) | Jul 08, 2020 |
| Gigabyte      | 970A-DS3P                   | [e9154c6e5f](https://linux-hardware.org/?probe=e9154c6e5f) | Jul 08, 2020 |
| HP            | 3646h                       | [c9c22fc2d2](https://linux-hardware.org/?probe=c9c22fc2d2) | Jul 07, 2020 |
| Lenovo        | Board                       | [ffbd208895](https://linux-hardware.org/?probe=ffbd208895) | Jul 07, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [3b83d81575](https://linux-hardware.org/?probe=3b83d81575) | Jul 06, 2020 |
| Foxconn       | H61M/H61M-S                 | [433fa2d995](https://linux-hardware.org/?probe=433fa2d995) | Jul 06, 2020 |
| Foxconn       | H61M/H61M-S                 | [6463942cf1](https://linux-hardware.org/?probe=6463942cf1) | Jul 06, 2020 |
| HP            | 3646h                       | [5bb02ddef7](https://linux-hardware.org/?probe=5bb02ddef7) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [096ded673b](https://linux-hardware.org/?probe=096ded673b) | Jul 06, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [5e05e7ff38](https://linux-hardware.org/?probe=5e05e7ff38) | Jul 06, 2020 |
| HP            | 1850                        | [4589a02a3b](https://linux-hardware.org/?probe=4589a02a3b) | Jul 05, 2020 |
| HP            | 3646h                       | [8a64d62abf](https://linux-hardware.org/?probe=8a64d62abf) | Jul 05, 2020 |
| Lenovo        | Board                       | [fe6a9e33d6](https://linux-hardware.org/?probe=fe6a9e33d6) | Jul 05, 2020 |
| HP            | 1850                        | [198dec280a](https://linux-hardware.org/?probe=198dec280a) | Jul 05, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [f09dae18ba](https://linux-hardware.org/?probe=f09dae18ba) | Jul 05, 2020 |
| Biostar       | X470NH                      | [00f710fa13](https://linux-hardware.org/?probe=00f710fa13) | Jul 05, 2020 |
| HP            | 1850                        | [af4e29ee3b](https://linux-hardware.org/?probe=af4e29ee3b) | Jul 05, 2020 |
| HP            | 1850                        | [cbe091dbc7](https://linux-hardware.org/?probe=cbe091dbc7) | Jul 05, 2020 |
| Lenovo        | Board                       | [672ab0b566](https://linux-hardware.org/?probe=672ab0b566) | Jul 04, 2020 |
| Lenovo        | Board                       | [02738b8fe6](https://linux-hardware.org/?probe=02738b8fe6) | Jul 03, 2020 |
| Lenovo        | Board                       | [52ee6c252f](https://linux-hardware.org/?probe=52ee6c252f) | Jul 03, 2020 |
| Gigabyte      | X570 GAMING X               | [d9da78a524](https://linux-hardware.org/?probe=d9da78a524) | Jul 03, 2020 |
| Lenovo        | Board                       | [4965543d87](https://linux-hardware.org/?probe=4965543d87) | Jul 02, 2020 |
| Dell          | 0Y2MRG A00                  | [e0aa8843f0](https://linux-hardware.org/?probe=e0aa8843f0) | Jul 01, 2020 |
| Foxconn       | CALI                        | [88399e8ee7](https://linux-hardware.org/?probe=88399e8ee7) | Jul 01, 2020 |
| ASRock        | A320M-DVS R4.0              | [003dafed13](https://linux-hardware.org/?probe=003dafed13) | Jun 30, 2020 |
| HP            | 3029h                       | [83bd0d970c](https://linux-hardware.org/?probe=83bd0d970c) | Jun 30, 2020 |
| MSI           | D2415 S26361-D2415-A10      | [cdeb87380b](https://linux-hardware.org/?probe=cdeb87380b) | Jun 30, 2020 |
| ASRock        | Z68 Pro3 Gen3               | [ad6bb0997e](https://linux-hardware.org/?probe=ad6bb0997e) | Jun 29, 2020 |
| MSI           | P67A-C45                    | [0f64b14506](https://linux-hardware.org/?probe=0f64b14506) | Jun 29, 2020 |
| ASRock        | H110 Pro BTC+               | [58cd657886](https://linux-hardware.org/?probe=58cd657886) | Jun 29, 2020 |
| Gigabyte      | EP41T-UD3L                  | [703487796e](https://linux-hardware.org/?probe=703487796e) | Jun 28, 2020 |
| Gigabyte      | EP41T-UD3L                  | [baf075d199](https://linux-hardware.org/?probe=baf075d199) | Jun 28, 2020 |
| ASRock        | Z68 Pro3 Gen3               | [47e0bd55ed](https://linux-hardware.org/?probe=47e0bd55ed) | Jun 27, 2020 |
| Gigabyte      | Z87-HD3                     | [3eff281cc0](https://linux-hardware.org/?probe=3eff281cc0) | Jun 27, 2020 |
| ASRock        | Z68 Pro3 Gen3               | [45ef0e585d](https://linux-hardware.org/?probe=45ef0e585d) | Jun 27, 2020 |
| Nvidia        | NF-MCP68                    | [91542aad5f](https://linux-hardware.org/?probe=91542aad5f) | Jun 27, 2020 |
| Gigabyte      | X48-DS5                     | [a2d6a8c38a](https://linux-hardware.org/?probe=a2d6a8c38a) | Jun 26, 2020 |
| ASRock        | FM2A75M-DGS R2.0            | [80a8998cb8](https://linux-hardware.org/?probe=80a8998cb8) | Jun 26, 2020 |
| ASRock        | FM2A75M-DGS R2.0            | [84df17703a](https://linux-hardware.org/?probe=84df17703a) | Jun 26, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [baf7d23a79](https://linux-hardware.org/?probe=baf7d23a79) | Jun 26, 2020 |
| MSI           | H61M-P21                    | [1753985522](https://linux-hardware.org/?probe=1753985522) | Jun 26, 2020 |
| Gigabyte      | X570 AORUS PRO              | [be903f651a](https://linux-hardware.org/?probe=be903f651a) | Jun 26, 2020 |
| Gigabyte      | H61M-D2-B3                  | [62b0e47d2a](https://linux-hardware.org/?probe=62b0e47d2a) | Jun 25, 2020 |
| Lenovo        | Board                       | [4cfa441478](https://linux-hardware.org/?probe=4cfa441478) | Jun 25, 2020 |
| Gigabyte      | H61M-D2-B3                  | [d01fd584e5](https://linux-hardware.org/?probe=d01fd584e5) | Jun 25, 2020 |
| Gigabyte      | GA-MA78G-DS3H               | [bda2dd72e6](https://linux-hardware.org/?probe=bda2dd72e6) | Jun 25, 2020 |
| Gigabyte      | GA-MA78G-DS3H               | [4eb0e60de1](https://linux-hardware.org/?probe=4eb0e60de1) | Jun 25, 2020 |
| HP            | 1850                        | [e111d92535](https://linux-hardware.org/?probe=e111d92535) | Jun 25, 2020 |
| HP            | 1850                        | [351b79f932](https://linux-hardware.org/?probe=351b79f932) | Jun 24, 2020 |
| Gigabyte      | H61M-D2-B3                  | [0e2f74b34c](https://linux-hardware.org/?probe=0e2f74b34c) | Jun 24, 2020 |
| Gigabyte      | B450 AORUS M                | [a75952edd6](https://linux-hardware.org/?probe=a75952edd6) | Jun 23, 2020 |
| Dell          | 0M863N A01                  | [6fb10808ff](https://linux-hardware.org/?probe=6fb10808ff) | Jun 23, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [05203fd4b0](https://linux-hardware.org/?probe=05203fd4b0) | Jun 23, 2020 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [17ee730f3d](https://linux-hardware.org/?probe=17ee730f3d) | Jun 23, 2020 |
| Gigabyte      | X570 AORUS PRO              | [1bc1f63a04](https://linux-hardware.org/?probe=1bc1f63a04) | Jun 23, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [3f1f0d4ed8](https://linux-hardware.org/?probe=3f1f0d4ed8) | Jun 23, 2020 |
| ASRock        | FM2A88M Extreme4+           | [220f1e42b1](https://linux-hardware.org/?probe=220f1e42b1) | Jun 23, 2020 |
| ASRock        | FM2A88M Extreme4+           | [8fd6e1e576](https://linux-hardware.org/?probe=8fd6e1e576) | Jun 23, 2020 |
| Lenovo        | Board                       | [1139d3a0ed](https://linux-hardware.org/?probe=1139d3a0ed) | Jun 22, 2020 |
| Gigabyte      | X570 AORUS PRO              | [81290d1d4d](https://linux-hardware.org/?probe=81290d1d4d) | Jun 22, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [35447ed97f](https://linux-hardware.org/?probe=35447ed97f) | Jun 22, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [ca88228ba9](https://linux-hardware.org/?probe=ca88228ba9) | Jun 21, 2020 |
| Gigabyte      | PH67A-D3-B3                 | [3e05bb7530](https://linux-hardware.org/?probe=3e05bb7530) | Jun 21, 2020 |
| Dell          | 0GM819                      | [eb0fd36373](https://linux-hardware.org/?probe=eb0fd36373) | Jun 21, 2020 |
| ASRock        | B75 Pro3-M                  | [a39c4402b9](https://linux-hardware.org/?probe=a39c4402b9) | Jun 21, 2020 |
| Lenovo        | Board                       | [40db434882](https://linux-hardware.org/?probe=40db434882) | Jun 21, 2020 |
| Lenovo        | Board                       | [8eb537a6d3](https://linux-hardware.org/?probe=8eb537a6d3) | Jun 21, 2020 |
| Lenovo        | Board                       | [47c887c7d4](https://linux-hardware.org/?probe=47c887c7d4) | Jun 21, 2020 |
| Gigabyte      | H55M-UD2H                   | [e750ad6b0b](https://linux-hardware.org/?probe=e750ad6b0b) | Jun 21, 2020 |
| Gigabyte      | PH67A-D3-B3                 | [be889b4fdc](https://linux-hardware.org/?probe=be889b4fdc) | Jun 20, 2020 |
| ASUSTek       | B85M-G                      | [6788469cfa](https://linux-hardware.org/?probe=6788469cfa) | Jun 20, 2020 |
| ASUSTek       | B150M-A/M.2                 | [c2232bc3f1](https://linux-hardware.org/?probe=c2232bc3f1) | Jun 20, 2020 |
| HP            | 0A58h                       | [1b66a4905e](https://linux-hardware.org/?probe=1b66a4905e) | Jun 20, 2020 |
| Gigabyte      | H61M-D2-B3                  | [b4b5575636](https://linux-hardware.org/?probe=b4b5575636) | Jun 20, 2020 |
| ASUSTek       | P7H55                       | [edf862d7bb](https://linux-hardware.org/?probe=edf862d7bb) | Jun 19, 2020 |
| Gigabyte      | B85M-DS3H                   | [182d2eac44](https://linux-hardware.org/?probe=182d2eac44) | Jun 19, 2020 |
| Gigabyte      | B85M-DS3H                   | [9e737535be](https://linux-hardware.org/?probe=9e737535be) | Jun 19, 2020 |
| ASRock        | FM2A58M-DG3+                | [6ebaa1d0f5](https://linux-hardware.org/?probe=6ebaa1d0f5) | Jun 18, 2020 |
| ASRock        | FM2A58M-DG3+                | [11f017d1e1](https://linux-hardware.org/?probe=11f017d1e1) | Jun 18, 2020 |
| ASUSTek       | P7H55                       | [fa29e65a3c](https://linux-hardware.org/?probe=fa29e65a3c) | Jun 18, 2020 |
| Dell          | 0TY565                      | [988acd56a8](https://linux-hardware.org/?probe=988acd56a8) | Jun 18, 2020 |
| HP            | 0A58h                       | [97c6bb1757](https://linux-hardware.org/?probe=97c6bb1757) | Jun 18, 2020 |
| HP            | 0A58h                       | [068b85afb8](https://linux-hardware.org/?probe=068b85afb8) | Jun 18, 2020 |
| Gigabyte      | H61M-D2-B3                  | [0ecde27264](https://linux-hardware.org/?probe=0ecde27264) | Jun 17, 2020 |
| Gigabyte      | X570 GAMING X               | [2ea2fd9fb1](https://linux-hardware.org/?probe=2ea2fd9fb1) | Jun 17, 2020 |
| Gigabyte      | X570 GAMING X               | [82d130eb39](https://linux-hardware.org/?probe=82d130eb39) | Jun 17, 2020 |
| Dell          | 06D7TR A00                  | [d13b915d47](https://linux-hardware.org/?probe=d13b915d47) | Jun 17, 2020 |
| Gigabyte      | B85M-DS3H                   | [5613e3f490](https://linux-hardware.org/?probe=5613e3f490) | Jun 17, 2020 |
| Gigabyte      | B85M-DS3H                   | [f633c933dc](https://linux-hardware.org/?probe=f633c933dc) | Jun 17, 2020 |
| MSI           | D2415 S26361-D2415-A10      | [047a92b8b5](https://linux-hardware.org/?probe=047a92b8b5) | Jun 17, 2020 |
| Gigabyte      | X570 GAMING X               | [d4ac7faeda](https://linux-hardware.org/?probe=d4ac7faeda) | Jun 17, 2020 |
| Gigabyte      | H61M-D2-B3                  | [1b40279f83](https://linux-hardware.org/?probe=1b40279f83) | Jun 17, 2020 |
| MSI           | MS-7181                     | [d25a89846d](https://linux-hardware.org/?probe=d25a89846d) | Jun 16, 2020 |
| MSI           | MS-7181                     | [97cdb0c04e](https://linux-hardware.org/?probe=97cdb0c04e) | Jun 16, 2020 |
| ASUSTek       | P5VD2-MX                    | [365dba79bc](https://linux-hardware.org/?probe=365dba79bc) | Jun 16, 2020 |
| ASRock        | ConRoe1333-D667             | [48a1f71def](https://linux-hardware.org/?probe=48a1f71def) | Jun 16, 2020 |
| Acer          | Veriton M6610G              | [1a1bd11ada](https://linux-hardware.org/?probe=1a1bd11ada) | Jun 16, 2020 |
| Gigabyte      | X48-DS5                     | [30e353d201](https://linux-hardware.org/?probe=30e353d201) | Jun 15, 2020 |
| Dell          | 0M5DCD A00                  | [0f8b820257](https://linux-hardware.org/?probe=0f8b820257) | Jun 15, 2020 |
| Dell          | 0M5DCD A00                  | [aae825819f](https://linux-hardware.org/?probe=aae825819f) | Jun 15, 2020 |
| Dell          | 0TY915                      | [8640fb5dc7](https://linux-hardware.org/?probe=8640fb5dc7) | Jun 14, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [02a1b5e0f6](https://linux-hardware.org/?probe=02a1b5e0f6) | Jun 14, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [ac49772b1d](https://linux-hardware.org/?probe=ac49772b1d) | Jun 14, 2020 |
| Gigabyte      | H61M-D2-B3                  | [96b7fa4452](https://linux-hardware.org/?probe=96b7fa4452) | Jun 14, 2020 |
| Dell          | 0Y2MRG A00                  | [76265587cd](https://linux-hardware.org/?probe=76265587cd) | Jun 13, 2020 |
| Intel         | D410PT AAE76528-400         | [a064945524](https://linux-hardware.org/?probe=a064945524) | Jun 12, 2020 |
| Gigabyte      | B85M-HD3                    | [6f4faa0e9e](https://linux-hardware.org/?probe=6f4faa0e9e) | Jun 12, 2020 |
| Gigabyte      | B85M-HD3                    | [8004b67232](https://linux-hardware.org/?probe=8004b67232) | Jun 12, 2020 |
| Intel         | D410PT AAE76528-400         | [f8453ed546](https://linux-hardware.org/?probe=f8453ed546) | Jun 11, 2020 |
| Gigabyte      | GA-MA785G-UD3H              | [d2f25e942a](https://linux-hardware.org/?probe=d2f25e942a) | Jun 11, 2020 |
| HP            | 2820h                       | [9d0345b894](https://linux-hardware.org/?probe=9d0345b894) | Jun 11, 2020 |
| Gigabyte      | B85M-DS3H                   | [6766e6d562](https://linux-hardware.org/?probe=6766e6d562) | Jun 11, 2020 |
| Gigabyte      | B85M-DS3H                   | [f798231722](https://linux-hardware.org/?probe=f798231722) | Jun 11, 2020 |
| Gigabyte      | H310M S2V x.x               | [304460088b](https://linux-hardware.org/?probe=304460088b) | Jun 11, 2020 |
| Gigabyte      | H310M S2V x.x               | [8cc6b80fc1](https://linux-hardware.org/?probe=8cc6b80fc1) | Jun 11, 2020 |
| Gigabyte      | P35-DQ6                     | [54fb93fb5d](https://linux-hardware.org/?probe=54fb93fb5d) | Jun 09, 2020 |
| Dell          | 0WG233                      | [089bb652ab](https://linux-hardware.org/?probe=089bb652ab) | Jun 08, 2020 |
| Intel         | D410PT AAE76528-400         | [f01d49010b](https://linux-hardware.org/?probe=f01d49010b) | Jun 07, 2020 |
| ASUSTek       | P7P55 LX                    | [e45f158bd0](https://linux-hardware.org/?probe=e45f158bd0) | Jun 07, 2020 |
| ASUSTek       | P7P55 LX                    | [0717dbbb74](https://linux-hardware.org/?probe=0717dbbb74) | Jun 07, 2020 |
| Intel         | D410PT AAE76528-400         | [f55796e03b](https://linux-hardware.org/?probe=f55796e03b) | Jun 07, 2020 |
| Gigabyte      | B85M-DS3H                   | [f341c781e8](https://linux-hardware.org/?probe=f341c781e8) | Jun 07, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [9e2ad1669c](https://linux-hardware.org/?probe=9e2ad1669c) | Jun 07, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a3fbb6d89b](https://linux-hardware.org/?probe=a3fbb6d89b) | Jun 07, 2020 |
| Dell          | 048DY8 A00                  | [e52110bdf4](https://linux-hardware.org/?probe=e52110bdf4) | Jun 06, 2020 |
| Dell          | 0M5DCD A00                  | [e15a2d0ac4](https://linux-hardware.org/?probe=e15a2d0ac4) | Jun 06, 2020 |
| Dell          | 0M5DCD A00                  | [2a8ab8703b](https://linux-hardware.org/?probe=2a8ab8703b) | Jun 06, 2020 |
| Dell          | Board                       | [d2804b8ec2](https://linux-hardware.org/?probe=d2804b8ec2) | Jun 06, 2020 |
| HP            | 1850                        | [d427e66a14](https://linux-hardware.org/?probe=d427e66a14) | Jun 06, 2020 |
| ASRock        | H81M-HDS R2.0               | [b39e737c91](https://linux-hardware.org/?probe=b39e737c91) | Jun 06, 2020 |
| ASRock        | H81M-HDS R2.0               | [8fcff0197b](https://linux-hardware.org/?probe=8fcff0197b) | Jun 06, 2020 |
| Dell          | Board                       | [2bd9e6fda9](https://linux-hardware.org/?probe=2bd9e6fda9) | Jun 06, 2020 |
| Gigabyte      | EP35-DS3                    | [3196193d8b](https://linux-hardware.org/?probe=3196193d8b) | Jun 06, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [09af92c9ea](https://linux-hardware.org/?probe=09af92c9ea) | Jun 05, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [6b556e3412](https://linux-hardware.org/?probe=6b556e3412) | Jun 05, 2020 |
| HP            | 0A68h                       | [bea8f18224](https://linux-hardware.org/?probe=bea8f18224) | Jun 05, 2020 |
| MSI           | H61M-P21                    | [aa87e3626b](https://linux-hardware.org/?probe=aa87e3626b) | Jun 04, 2020 |
| MSI           | H61M-P21                    | [a9652634ec](https://linux-hardware.org/?probe=a9652634ec) | Jun 04, 2020 |
| Gigabyte      | B85M-DS3H                   | [5e21181b5c](https://linux-hardware.org/?probe=5e21181b5c) | Jun 04, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [10a7069b4e](https://linux-hardware.org/?probe=10a7069b4e) | Jun 04, 2020 |
| HP            | 0A68h                       | [c4739573a3](https://linux-hardware.org/?probe=c4739573a3) | Jun 04, 2020 |
| HP            | 0A68h                       | [9e276af568](https://linux-hardware.org/?probe=9e276af568) | Jun 04, 2020 |
| Unknown       | 4Core1333-eSATA2            | [62bc4d7f7d](https://linux-hardware.org/?probe=62bc4d7f7d) | Jun 03, 2020 |
| ASUSTek       | P5G41T-M LX                 | [397b26ccfe](https://linux-hardware.org/?probe=397b26ccfe) | Jun 03, 2020 |
| ASRock        | FM2A85X Extreme4            | [b48d2a4cd9](https://linux-hardware.org/?probe=b48d2a4cd9) | Jun 03, 2020 |
| Unknown       | 4Core1333-eSATA2            | [cb538cdc54](https://linux-hardware.org/?probe=cb538cdc54) | Jun 02, 2020 |
| Unknown       | 4Core1333-eSATA2            | [0d2380ada7](https://linux-hardware.org/?probe=0d2380ada7) | Jun 02, 2020 |
| HP            | 097Ch                       | [f665df7ad5](https://linux-hardware.org/?probe=f665df7ad5) | Jun 02, 2020 |
| ASUSTek       | PRIME H310M-D               | [6fae6abb2f](https://linux-hardware.org/?probe=6fae6abb2f) | Jun 01, 2020 |
| MSI           | H61M-P20                    | [ec9052e283](https://linux-hardware.org/?probe=ec9052e283) | Jun 01, 2020 |
| MSI           | H61M-P20                    | [b57843f08e](https://linux-hardware.org/?probe=b57843f08e) | Jun 01, 2020 |
| MSI           | H61M-P20                    | [f266b7d2fa](https://linux-hardware.org/?probe=f266b7d2fa) | Jun 01, 2020 |
| MSI           | H61M-P20                    | [6393557f9d](https://linux-hardware.org/?probe=6393557f9d) | Jun 01, 2020 |
| Dell          | 09KPNV A00                  | [b282563e32](https://linux-hardware.org/?probe=b282563e32) | May 31, 2020 |
| Gigabyte      | B450M GAMING                | [6a8f24bad0](https://linux-hardware.org/?probe=6a8f24bad0) | May 31, 2020 |
| Gigabyte      | B450M GAMING                | [23fd764706](https://linux-hardware.org/?probe=23fd764706) | May 31, 2020 |
| Dell          | 09KPNV A00                  | [2752d3dcff](https://linux-hardware.org/?probe=2752d3dcff) | May 31, 2020 |
| Dell          | 09KPNV A00                  | [5bda3f3a4f](https://linux-hardware.org/?probe=5bda3f3a4f) | May 31, 2020 |
| MSI           | H61M-P20                    | [98f90876db](https://linux-hardware.org/?probe=98f90876db) | May 31, 2020 |
| Dell          | 09KPNV A00                  | [499d8fa679](https://linux-hardware.org/?probe=499d8fa679) | May 31, 2020 |
| Intel         | DH55TC AAE70932-302         | [a8f06d0420](https://linux-hardware.org/?probe=a8f06d0420) | May 30, 2020 |
| Intel         | DH55TC AAE70932-302         | [d8ca0e6f6e](https://linux-hardware.org/?probe=d8ca0e6f6e) | May 30, 2020 |
| Intel         | DH55TC AAE70932-302         | [81568885c3](https://linux-hardware.org/?probe=81568885c3) | May 30, 2020 |
| Dell          | 0R230R A00                  | [0584719f13](https://linux-hardware.org/?probe=0584719f13) | May 29, 2020 |
| Gigabyte      | B85M-DS3H                   | [67d21a44a6](https://linux-hardware.org/?probe=67d21a44a6) | May 29, 2020 |
| Gigabyte      | B85M-DS3H                   | [ac816f388a](https://linux-hardware.org/?probe=ac816f388a) | May 29, 2020 |
| Gigabyte      | B450M GAMING                | [d4357635ce](https://linux-hardware.org/?probe=d4357635ce) | May 28, 2020 |
| ASRock        | 945GCM-S                    | [244f0e6d6a](https://linux-hardware.org/?probe=244f0e6d6a) | May 28, 2020 |
| Gigabyte      | B85M-DS3H                   | [42b296ec3e](https://linux-hardware.org/?probe=42b296ec3e) | May 28, 2020 |
| Gigabyte      | B85M-DS3H                   | [9338088e90](https://linux-hardware.org/?probe=9338088e90) | May 28, 2020 |
| Intel         | D2700MUD AAG32419-602       | [4ae3dd9399](https://linux-hardware.org/?probe=4ae3dd9399) | May 28, 2020 |
| Intel         | D2700MUD AAG32419-602       | [78dcc87dfe](https://linux-hardware.org/?probe=78dcc87dfe) | May 27, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [2afab59422](https://linux-hardware.org/?probe=2afab59422) | May 27, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [374deb158c](https://linux-hardware.org/?probe=374deb158c) | May 27, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [9505b023cc](https://linux-hardware.org/?probe=9505b023cc) | May 27, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | [d0fedaae46](https://linux-hardware.org/?probe=d0fedaae46) | May 27, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | [51b969527f](https://linux-hardware.org/?probe=51b969527f) | May 26, 2020 |
| HP            | 0AA8h                       | [70a7e4b65a](https://linux-hardware.org/?probe=70a7e4b65a) | May 26, 2020 |
| Gigabyte      | B450M GAMING                | [d3a1d57b15](https://linux-hardware.org/?probe=d3a1d57b15) | May 26, 2020 |
| ASUSTek       | P8H61/USB3 R2.0             | [c82a52b1cd](https://linux-hardware.org/?probe=c82a52b1cd) | May 26, 2020 |
| ASUSTek       | P8H61/USB3 R2.0             | [0d806b4124](https://linux-hardware.org/?probe=0d806b4124) | May 26, 2020 |
| Nvidia        | MCP68                       | [a63a6a75c5](https://linux-hardware.org/?probe=a63a6a75c5) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| BlackPanther 18.1   | 816      | 59.35%  |
| Ubuntu 20.04        | 91       | 6.62%   |
| BlackPanther 16.2   | 64       | 4.65%   |
| Ubuntu 18.04        | 58       | 4.22%   |
| OpenMandriva 4.2    | 35       | 2.55%   |
| Linux Mint 20.2     | 13       | 0.95%   |
| Debian 11           | 13       | 0.95%   |
| Debian 10           | 12       | 0.87%   |
| Ubuntu 19.10        | 11       | 0.8%    |
| Arch                | 11       | 0.8%    |
| Arch Rolling        | 10       | 0.73%   |
| Zorin 16            | 9        | 0.65%   |
| Xubuntu 20.04       | 9        | 0.65%   |
| Ubuntu 19.04        | 9        | 0.65%   |
| Linux Mint 20       | 9        | 0.65%   |
| Xubuntu 18.04       | 8        | 0.58%   |
| Ubuntu 21.10        | 8        | 0.58%   |
| OpenMandriva 4.3    | 8        | 0.58%   |
| Ubuntu 20.10        | 7        | 0.51%   |
| Zorin 15            | 6        | 0.44%   |
| Ubuntu 21.04        | 6        | 0.44%   |
| OpenMandriva 4.50   | 6        | 0.44%   |
| Linux Mint 20.1     | 6        | 0.44%   |
| Linux Mint 19.3     | 6        | 0.44%   |
| Kubuntu 20.04       | 6        | 0.44%   |
| Ubuntu 16.04        | 5        | 0.36%   |
| Manjaro             | 5        | 0.36%   |
| Lubuntu 20.04       | 5        | 0.36%   |
| Fedora 32           | 5        | 0.36%   |
| Pop!_OS 20.10       | 4        | 0.29%   |
| KDE neon 20.04      | 4        | 0.29%   |
| Fedora 35           | 4        | 0.29%   |
| Ubuntu 18.10        | 3        | 0.22%   |
| ROSA R10            | 3        | 0.22%   |
| Pop!_OS 21.10       | 3        | 0.22%   |
| Pop!_OS 21.04       | 3        | 0.22%   |
| Linux Mint 19       | 3        | 0.22%   |
| Kubuntu 21.10       | 3        | 0.22%   |
| Kubuntu 21.04       | 3        | 0.22%   |
| Kubuntu 18.04       | 3        | 0.22%   |
| Fedora 34           | 3        | 0.22%   |
| Fedora 33           | 3        | 0.22%   |
| Fedora 31           | 3        | 0.22%   |
| Ubuntu MATE 21.04   | 2        | 0.15%   |
| Ubuntu MATE 20.04   | 2        | 0.15%   |
| Ubuntu MATE 18.04   | 2        | 0.15%   |
| ROSA R11.1          | 2        | 0.15%   |
| Manjaro 21.0.7      | 2        | 0.15%   |
| LMDE 4              | 2        | 0.15%   |
| Linux Mint 20.3     | 2        | 0.15%   |
| Linux Mint 19.2     | 2        | 0.15%   |
| Linux Mint 19.1     | 2        | 0.15%   |
| Kubuntu 20.10       | 2        | 0.15%   |
| Gentoo 2.6          | 2        | 0.15%   |
| Endless 3.8.1       | 2        | 0.15%   |
| EndeavourOS Rolling | 2        | 0.15%   |
| Debian 9            | 2        | 0.15%   |
| ArcoLinux Rolling   | 2        | 0.15%   |
| ArcoLinux           | 2        | 0.15%   |
| Xubuntu 21.10       | 1        | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| BlackPanther  | 862      | 64.81%  |
| Ubuntu        | 188      | 14.14%  |
| OpenMandriva  | 48       | 3.61%   |
| Linux Mint    | 42       | 3.16%   |
| Debian        | 28       | 2.11%   |
| Arch          | 21       | 1.58%   |
| Xubuntu       | 19       | 1.43%   |
| Kubuntu       | 17       | 1.28%   |
| Zorin         | 15       | 1.13%   |
| Manjaro       | 15       | 1.13%   |
| Fedora        | 12       | 0.9%    |
| Pop!_OS       | 10       | 0.75%   |
| Lubuntu       | 7        | 0.53%   |
| Ubuntu MATE   | 6        | 0.45%   |
| ROSA          | 6        | 0.45%   |
| KDE neon      | 5        | 0.38%   |
| Endless       | 5        | 0.38%   |
| ArcoLinux     | 4        | 0.3%    |
| openSUSE      | 3        | 0.23%   |
| Gentoo        | 3        | 0.23%   |
| LMDE          | 2        | 0.15%   |
| EndeavourOS   | 2        | 0.15%   |
| Ubuntu Budgie | 1        | 0.08%   |
| Reborn OS     | 1        | 0.08%   |
| NixOS         | 1        | 0.08%   |
| MX            | 1        | 0.08%   |
| Kali          | 1        | 0.08%   |
| Elementary    | 1        | 0.08%   |
| Clear Linux   | 1        | 0.08%   |
| CentOS        | 1        | 0.08%   |
| Archcraft     | 1        | 0.08%   |
| antergos      | 1        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.18.16-desktop-1bP      | 637      | 42.27%  |
| 5.6.14-desktop-2bP       | 229      | 15.2%   |
| 4.9.20-desktop-pae-1bP   | 56       | 3.72%   |
| 5.10.14-desktop-1omv4002 | 33       | 2.19%   |
| 5.1.15-desktop-1bP       | 27       | 1.79%   |
| 5.4.0-42-generic         | 13       | 0.86%   |
| 5.4.0-58-generic         | 12       | 0.8%    |
| 5.4.0-52-generic         | 9        | 0.6%    |
| 5.4.0-48-generic         | 8        | 0.53%   |
| 5.16.7-desktop-1omv4003  | 8        | 0.53%   |
| 5.11.0-27-generic        | 7        | 0.46%   |
| 5.8.0-43-generic         | 6        | 0.4%    |
| 5.4.0-91-generic         | 6        | 0.4%    |
| 5.4.0-47-generic         | 6        | 0.4%    |
| 5.3.0-46-generic         | 6        | 0.4%    |
| 5.11.0-43-generic        | 6        | 0.4%    |
| 4.15.0-43-generic        | 6        | 0.4%    |
| 5.8.0-44-generic         | 5        | 0.33%   |
| 5.12.4-desktop-1omv4050  | 5        | 0.33%   |
| 5.11.0-37-generic        | 5        | 0.33%   |
| 5.0.0-37-generic         | 5        | 0.33%   |
| 5.8.0-7630-generic       | 4        | 0.27%   |
| 5.4.0-88-generic         | 4        | 0.27%   |
| 5.4.0-54-generic         | 4        | 0.27%   |
| 5.4.0-53-generic         | 4        | 0.27%   |
| 5.4.0-40-generic         | 4        | 0.27%   |
| 5.4.0-39-generic         | 4        | 0.27%   |
| 5.4.0-37-generic         | 4        | 0.27%   |
| 5.4.0-31-generic         | 4        | 0.27%   |
| 5.4.0-100-generic        | 4        | 0.27%   |
| 5.13.13-arch1-1          | 4        | 0.27%   |
| 5.13.0-30-generic        | 4        | 0.27%   |
| 5.13.0-27-generic        | 4        | 0.27%   |
| 5.11.0-41-generic        | 4        | 0.27%   |
| 5.11.0-38-generic        | 4        | 0.27%   |
| 5.11.0-34-generic        | 4        | 0.27%   |
| 5.10.0-8-amd64           | 4        | 0.27%   |
| 5.0.0-25-generic         | 4        | 0.27%   |
| 4.15.0-54-generic        | 4        | 0.27%   |
| 5.9.16-1-MANJARO         | 3        | 0.2%    |
| 5.8.0-59-generic         | 3        | 0.2%    |
| 5.8.0-53-generic         | 3        | 0.2%    |
| 5.8.0-50-generic         | 3        | 0.2%    |
| 5.4.0-92-generic         | 3        | 0.2%    |
| 5.4.0-90-generic         | 3        | 0.2%    |
| 5.4.0-73-generic         | 3        | 0.2%    |
| 5.4.0-72-generic         | 3        | 0.2%    |
| 5.4.0-65-generic         | 3        | 0.2%    |
| 5.4.0-56-generic         | 3        | 0.2%    |
| 5.4.0-51-generic         | 3        | 0.2%    |
| 5.4.0-29-generic         | 3        | 0.2%    |
| 5.3.0-40-generic         | 3        | 0.2%    |
| 5.3.0-26-generic         | 3        | 0.2%    |
| 5.13.0-39-generic        | 3        | 0.2%    |
| 5.13.0-22-generic        | 3        | 0.2%    |
| 5.0.0-36-generic         | 3        | 0.2%    |
| 5.0.0-23-generic         | 3        | 0.2%    |
| 4.9.20-desktop-1bP       | 3        | 0.2%    |
| 4.7.0-desktop-1bP        | 3        | 0.2%    |
| 4.18.0-25-generic        | 3        | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.16 | 637      | 43.36%  |
| 5.6.14  | 230      | 15.66%  |
| 5.4.0   | 119      | 8.1%    |
| 4.9.20  | 59       | 4.02%   |
| 5.11.0  | 43       | 2.93%   |
| 4.15.0  | 42       | 2.86%   |
| 5.8.0   | 36       | 2.45%   |
| 5.10.14 | 33       | 2.25%   |
| 5.3.0   | 29       | 1.97%   |
| 5.1.15  | 28       | 1.91%   |
| 5.13.0  | 23       | 1.57%   |
| 5.0.0   | 22       | 1.5%    |
| 4.19.0  | 13       | 0.88%   |
| 5.10.0  | 10       | 0.68%   |
| 5.16.7  | 8        | 0.54%   |
| 4.18.0  | 7        | 0.48%   |
| 5.12.4  | 5        | 0.34%   |
| 5.9.16  | 4        | 0.27%   |
| 5.16.0  | 4        | 0.27%   |
| 5.13.13 | 4        | 0.27%   |
| 5.14.9  | 3        | 0.2%    |
| 5.14.0  | 3        | 0.2%    |
| 4.7.0   | 3        | 0.2%    |
| 5.9.14  | 2        | 0.14%   |
| 5.9.1   | 2        | 0.14%   |
| 5.7.0   | 2        | 0.14%   |
| 5.6.12  | 2        | 0.14%   |
| 5.5.8   | 2        | 0.14%   |
| 5.4.80  | 2        | 0.14%   |
| 5.17.1  | 2        | 0.14%   |
| 5.16.15 | 2        | 0.14%   |
| 5.15.5  | 2        | 0.14%   |
| 5.14.10 | 2        | 0.14%   |
| 5.13.19 | 2        | 0.14%   |
| 4.9.60  | 2        | 0.14%   |
| 4.4.0   | 2        | 0.14%   |
| 5.9.8   | 1        | 0.07%   |
| 5.9.6   | 1        | 0.07%   |
| 5.9.12  | 1        | 0.07%   |
| 5.9.10  | 1        | 0.07%   |
| 5.8.4   | 1        | 0.07%   |
| 5.8.14  | 1        | 0.07%   |
| 5.8.11  | 1        | 0.07%   |
| 5.8.10  | 1        | 0.07%   |
| 5.8.1   | 1        | 0.07%   |
| 5.7.9   | 1        | 0.07%   |
| 5.7.8   | 1        | 0.07%   |
| 5.7.7   | 1        | 0.07%   |
| 5.7.6   | 1        | 0.07%   |
| 5.7.15  | 1        | 0.07%   |
| 5.7.11  | 1        | 0.07%   |
| 5.6.11  | 1        | 0.07%   |
| 5.6.0   | 1        | 0.07%   |
| 5.5.17  | 1        | 0.07%   |
| 5.4.83  | 1        | 0.07%   |
| 5.4.7   | 1        | 0.07%   |
| 5.4.65  | 1        | 0.07%   |
| 5.4.32  | 1        | 0.07%   |
| 5.4.25  | 1        | 0.07%   |
| 5.4.14  | 1        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 644      | 44.05%  |
| 5.6     | 232      | 15.87%  |
| 5.4     | 127      | 8.69%   |
| 4.9     | 64       | 4.38%   |
| 5.10    | 51       | 3.49%   |
| 5.11    | 50       | 3.42%   |
| 4.15    | 42       | 2.87%   |
| 5.8     | 41       | 2.8%    |
| 5.13    | 31       | 2.12%   |
| 5.1     | 31       | 2.12%   |
| 5.3     | 30       | 2.05%   |
| 5.0     | 22       | 1.5%    |
| 5.16    | 17       | 1.16%   |
| 5.15    | 13       | 0.89%   |
| 4.19    | 13       | 0.89%   |
| 5.9     | 11       | 0.75%   |
| 5.14    | 9        | 0.62%   |
| 5.7     | 8        | 0.55%   |
| 5.12    | 8        | 0.55%   |
| 5.5     | 3        | 0.21%   |
| 4.7     | 3        | 0.21%   |
| 5.17    | 2        | 0.14%   |
| 4.4     | 2        | 0.14%   |
| 4.20    | 2        | 0.14%   |
| 4.5     | 1        | 0.07%   |
| 4.14    | 1        | 0.07%   |
| 4.12    | 1        | 0.07%   |
| 4.10    | 1        | 0.07%   |
| 4.1     | 1        | 0.07%   |
| 3.13    | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1230     | 93.82%  |
| i686   | 80       | 6.1%    |
| unknow | 1        | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 929      | 70.22%  |
| GNOME           | 177      | 13.38%  |
| Unknown         | 77       | 5.82%   |
| XFCE            | 42       | 3.17%   |
| X-Cinnamon      | 26       | 1.97%   |
| MATE            | 21       | 1.59%   |
| KDE             | 11       | 0.83%   |
| LXQt            | 8        | 0.6%    |
| Cinnamon        | 8        | 0.6%    |
| Unity           | 7        | 0.53%   |
| KDE4            | 5        | 0.38%   |
| i3              | 4        | 0.3%    |
| Deepin          | 3        | 0.23%   |
| LXDE            | 1        | 0.08%   |
| GNOME Flashback | 1        | 0.08%   |
| GNOME Classic   | 1        | 0.08%   |
| Enlightenment   | 1        | 0.08%   |
| Budgie          | 1        | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1224     | 94.01%  |
| Unknown | 44       | 3.38%   |
| Wayland | 24       | 1.84%   |
| Tty     | 10       | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 928      | 70.25%  |
| Unknown | 268      | 20.29%  |
| LightDM | 35       | 2.65%   |
| GDM     | 32       | 2.42%   |
| GDM3    | 26       | 1.97%   |
| TDM     | 25       | 1.89%   |
| KDM     | 5        | 0.38%   |
| SLiM    | 2        | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 911      | 68.91%  |
| hu_HU   | 262      | 19.82%  |
| en_US   | 125      | 9.46%   |
| en_GB   | 12       | 0.91%   |
| C       | 6        | 0.45%   |
| de_DE   | 4        | 0.3%    |
| POSIX   | 1        | 0.08%   |
| C.UTF8  | 1        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 992      | 73.92%  |
| EFI  | 350      | 26.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Overlay | 678      | 48.71%  |
| Ext4    | 665      | 47.77%  |
| Btrfs   | 20       | 1.44%   |
| Unknown | 15       | 1.08%   |
| Zfs     | 4        | 0.29%   |
| Xfs     | 4        | 0.29%   |
| Ext2    | 3        | 0.22%   |
| Ext3    | 2        | 0.14%   |
| Tmpfs   | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 703      | 51.84%  |
| GPT     | 362      | 26.7%   |
| Unknown | 291      | 21.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 985      | 69.66%  |
| Yes       | 429      | 30.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 732      | 53.12%  |
| No        | 646      | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 259      | 20.03%  |
| ASUSTek Computer    | 252      | 19.49%  |
| ASRock              | 231      | 17.87%  |
| Dell                | 127      | 9.82%   |
| Hewlett-Packard     | 114      | 8.82%   |
| MSI                 | 77       | 5.96%   |
| Lenovo              | 58       | 4.49%   |
| Fujitsu             | 39       | 3.02%   |
| Fujitsu Siemens     | 25       | 1.93%   |
| Intel               | 21       | 1.62%   |
| Acer                | 20       | 1.55%   |
| Foxconn             | 14       | 1.08%   |
| Unknown             | 13       | 1.01%   |
| Medion              | 8        | 0.62%   |
| Pegatron            | 5        | 0.39%   |
| AOpen               | 3        | 0.23%   |
| ABIT                | 3        | 0.23%   |
| Nvidia              | 2        | 0.15%   |
| Gateway             | 2        | 0.15%   |
| Biostar             | 2        | 0.15%   |
| AMD                 | 2        | 0.15%   |
| Wistron             | 1        | 0.08%   |
| WINCOR NIXDORF      | 1        | 0.08%   |
| ViewSonic           | 1        | 0.08%   |
| Supermicro          | 1        | 0.08%   |
| Shuttle             | 1        | 0.08%   |
| SeeedStudio         | 1        | 0.08%   |
| NEC Computers       | 1        | 0.08%   |
| Minix               | 1        | 0.08%   |
| Lex                 | 1        | 0.08%   |
| JW Technology       | 1        | 0.08%   |
| IBM                 | 1        | 0.08%   |
| Hampoo              | 1        | 0.08%   |
| ECS                 | 1        | 0.08%   |
| ASRockRack          | 1        | 0.08%   |
| Apple               | 1        | 0.08%   |
| AMI                 | 1        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASRock FM2A75M Pro4+                   | 32       | 2.47%   |
| ASUS All Series                        | 25       | 1.93%   |
| Dell OptiPlex 3020                     | 17       | 1.31%   |
| Unknown                                | 13       | 1.01%   |
| ASUS P5KPL-AM EPU                      | 12       | 0.93%   |
| Gigabyte G31M-ES2L                     | 10       | 0.77%   |
| Dell OptiPlex 780                      | 10       | 0.77%   |
| Dell OptiPlex 755                      | 10       | 0.77%   |
| Dell OptiPlex 760                      | 9        | 0.7%    |
| Gigabyte H61M-S1                       | 8        | 0.62%   |
| ASRock G41M-VS3                        | 8        | 0.62%   |
| Gigabyte 970A-DS3P                     | 7        | 0.54%   |
| Dell Precision WorkStation T3500       | 7        | 0.54%   |
| Dell OptiPlex 7010                     | 7        | 0.54%   |
| HP ProDesk 600 G2 SFF                  | 6        | 0.46%   |
| HP Compaq 8000 Elite SFF PC            | 6        | 0.46%   |
| Dell OptiPlex 330                      | 6        | 0.46%   |
| ASRock N68C-S UCC                      | 6        | 0.46%   |
| MSI MS-7592                            | 5        | 0.39%   |
| HP Compaq Elite 8300 SFF               | 5        | 0.39%   |
| HP Compaq dc5850 Small Form Factor     | 5        | 0.39%   |
| HP Compaq dc5800 Small Form Factor     | 5        | 0.39%   |
| Gigabyte H81M-S1                       | 5        | 0.39%   |
| Fujitsu Siemens ESPRIMO E5730          | 5        | 0.39%   |
| Foxconn Pro 3500 Series                | 5        | 0.39%   |
| Dell OptiPlex 745                      | 5        | 0.39%   |
| Dell OptiPlex 3010                     | 5        | 0.39%   |
| ASRock FM2A68M-HD+                     | 5        | 0.39%   |
| ASRock 970 Pro3 R2.0                   | 5        | 0.39%   |
| Acer Veriton M430                      | 5        | 0.39%   |
| Medion Pentino G-Series                | 4        | 0.31%   |
| HP Compaq Pro 6305 SFF                 | 4        | 0.31%   |
| HP Compaq dc5850 Microtower            | 4        | 0.31%   |
| Gigabyte X48-DS5                       | 4        | 0.31%   |
| Gigabyte P67A-D3-B3                    | 4        | 0.31%   |
| Gigabyte B85M-DS3H-A                   | 4        | 0.31%   |
| Gigabyte B450 AORUS M                  | 4        | 0.31%   |
| Gigabyte B450 AORUS ELITE              | 4        | 0.31%   |
| Fujitsu ESPRIMO P910                   | 4        | 0.31%   |
| Dell OptiPlex 740 Enhanced             | 4        | 0.31%   |
| ASUS PRIME B365M-A                     | 4        | 0.31%   |
| ASUS P5KPL-AM SE                       | 4        | 0.31%   |
| ASUS H110M-K                           | 4        | 0.31%   |
| ASRock H110 Pro BTC+                   | 4        | 0.31%   |
| ASRock FM2A68M-DG3+                    | 4        | 0.31%   |
| ASRock ConRoe1333-D667                 | 4        | 0.31%   |
| ASRock 970M Pro3                       | 4        | 0.31%   |
| ASRock 945GCM-S                        | 4        | 0.31%   |
| MSI MS-7C02                            | 3        | 0.23%   |
| MSI MS-7817                            | 3        | 0.23%   |
| MSI MS-7788                            | 3        | 0.23%   |
| MSI MS-7680                            | 3        | 0.23%   |
| HP ProLiant MicroServer                | 3        | 0.23%   |
| HP Compaq Pro 6305 MT                  | 3        | 0.23%   |
| HP Compaq Pro 6300 SFF                 | 3        | 0.23%   |
| HP Compaq Pro 6300 MT                  | 3        | 0.23%   |
| HP Compaq Elite 8300 CMT               | 3        | 0.23%   |
| HP Compaq dc7900 Small Form Factor     | 3        | 0.23%   |
| HP Compaq dc7900 Convertible Minitower | 3        | 0.23%   |
| HP Compaq dc5800 Microtower            | 3        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 106      | 8.2%    |
| HP Compaq               | 85       | 6.57%   |
| Lenovo ThinkCentre      | 45       | 3.48%   |
| ASRock FM2A75M          | 32       | 2.47%   |
| ASUS PRIME              | 31       | 2.4%    |
| Fujitsu ESPRIMO         | 28       | 2.17%   |
| ASUS All                | 25       | 1.93%   |
| Fujitsu Siemens ESPRIMO | 19       | 1.47%   |
| ASUS P5KPL-AM           | 17       | 1.31%   |
| Acer Veriton            | 14       | 1.08%   |
| Unknown                 | 13       | 1.01%   |
| Gigabyte B450           | 11       | 0.85%   |
| Dell Precision          | 11       | 0.85%   |
| Gigabyte G31M-ES2L      | 10       | 0.77%   |
| ASUS ROG                | 10       | 0.77%   |
| ASUS TUF                | 9        | 0.7%    |
| ASUS M5A97              | 9        | 0.7%    |
| HP ProDesk              | 8        | 0.62%   |
| Gigabyte H61M-S1        | 8        | 0.62%   |
| Gigabyte B450M          | 8        | 0.62%   |
| Fujitsu CELSIUS         | 8        | 0.62%   |
| ASRock G41M-VS3         | 8        | 0.62%   |
| ASRock 970              | 8        | 0.62%   |
| Gigabyte H310M          | 7        | 0.54%   |
| Gigabyte 970A-DS3P      | 7        | 0.54%   |
| ASRock N68C-S           | 7        | 0.54%   |
| HP EliteDesk            | 6        | 0.46%   |
| ASUS M5A78L-M           | 6        | 0.46%   |
| MSI MS-7592             | 5        | 0.39%   |
| Gigabyte H81M-S1        | 5        | 0.39%   |
| Foxconn Pro             | 5        | 0.39%   |
| ASUS H110M-A            | 5        | 0.39%   |
| ASRock Z77              | 5        | 0.39%   |
| ASRock FM2A68M-HD+      | 5        | 0.39%   |
| ASRock B450M            | 5        | 0.39%   |
| ASRock B450             | 5        | 0.39%   |
| Medion Pentino          | 4        | 0.31%   |
| Lenovo ThinkStation     | 4        | 0.31%   |
| Gigabyte X48-DS5        | 4        | 0.31%   |
| Gigabyte P67A-D3-B3     | 4        | 0.31%   |
| Gigabyte B85M-DS3H-A    | 4        | 0.31%   |
| Dell PowerEdge          | 4        | 0.31%   |
| ASUS P8H61-M            | 4        | 0.31%   |
| ASUS M2N68-AM           | 4        | 0.31%   |
| ASUS H110M-K            | 4        | 0.31%   |
| ASRock Z370             | 4        | 0.31%   |
| ASRock H110             | 4        | 0.31%   |
| ASRock FM2A68M-DG3+     | 4        | 0.31%   |
| ASRock ConRoe1333-D667  | 4        | 0.31%   |
| ASRock B75              | 4        | 0.31%   |
| ASRock 970M             | 4        | 0.31%   |
| ASRock 945GCM-S         | 4        | 0.31%   |
| Pegatron Compaq         | 3        | 0.23%   |
| MSI Pro                 | 3        | 0.23%   |
| MSI MS-7C02             | 3        | 0.23%   |
| MSI MS-7817             | 3        | 0.23%   |
| MSI MS-7788             | 3        | 0.23%   |
| MSI MS-7680             | 3        | 0.23%   |
| HP ProLiant             | 3        | 0.23%   |
| Gigabyte X570           | 3        | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 152      | 11.76%  |
| 2013    | 135      | 10.44%  |
| 2014    | 121      | 9.36%   |
| 2009    | 119      | 9.2%    |
| 2010    | 116      | 8.97%   |
| 2008    | 112      | 8.66%   |
| 2011    | 104      | 8.04%   |
| 2018    | 89       | 6.88%   |
| 2007    | 87       | 6.73%   |
| 2015    | 53       | 4.1%    |
| 2017    | 41       | 3.17%   |
| 2016    | 41       | 3.17%   |
| 2019    | 35       | 2.71%   |
| 2006    | 32       | 2.47%   |
| 2020    | 25       | 1.93%   |
| 2005    | 17       | 1.31%   |
| 2021    | 7        | 0.54%   |
| 2004    | 4        | 0.31%   |
| 2003    | 2        | 0.15%   |
| Unknown | 1        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1293     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1287     | 99.38%  |
| Enabled  | 8        | 0.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1293     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 389      | 29.16%  |
| 8.01-16.0   | 327      | 24.51%  |
| 4.01-8.0    | 215      | 16.12%  |
| 16.01-24.0  | 186      | 13.94%  |
| 1.01-2.0    | 109      | 8.17%   |
| 32.01-64.0  | 50       | 3.75%   |
| 2.01-3.0    | 30       | 2.25%   |
| 24.01-32.0  | 11       | 0.82%   |
| 64.01-256.0 | 10       | 0.75%   |
| 0.51-1.0    | 7        | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 434      | 28.8%   |
| 0.51-1.0    | 423      | 28.07%  |
| 1.01-2.0    | 397      | 26.34%  |
| 2.01-3.0    | 127      | 8.43%   |
| 3.01-4.0    | 57       | 3.78%   |
| 4.01-8.0    | 49       | 3.25%   |
| 8.01-16.0   | 13       | 0.86%   |
| 16.01-24.0  | 5        | 0.33%   |
| 64.01-256.0 | 1        | 0.07%   |
| Unknown     | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 696      | 49.43%  |
| 2       | 370      | 26.28%  |
| 3       | 188      | 13.35%  |
| 4       | 76       | 5.4%    |
| 5       | 34       | 2.41%   |
| 0       | 20       | 1.42%   |
| 6       | 11       | 0.78%   |
| 7       | 5        | 0.36%   |
| 8       | 3        | 0.21%   |
| 9       | 2        | 0.14%   |
| 11      | 1        | 0.07%   |
| 10      | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 787      | 58.82%  |
| No        | 551      | 41.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1279     | 98.92%  |
| No        | 14       | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 993      | 75.23%  |
| Yes       | 327      | 24.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1148     | 87.1%   |
| Yes       | 170      | 12.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Hungary | 1293     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Budapest                | 393      | 26.23%  |
| Szeged                  | 32       | 2.14%   |
| Miskolc                 | 32       | 2.14%   |
| Debrecen                | 28       | 1.87%   |
| Karcag                  | 23       | 1.54%   |
| GyЕ‘r                | 23       | 1.54%   |
| PГ©cs                 | 21       | 1.4%    |
| Jaszbereny              | 20       | 1.34%   |
| Eger                    | 20       | 1.34%   |
| Szombathely             | 19       | 1.27%   |
| SzГ©kesfehГ©rvГЎr | 16       | 1.07%   |
| KecskemГ©t            | 16       | 1.07%   |
| Szigetszentmiklos       | 15       | 1%      |
| Nyiregyhaza             | 15       | 1%      |
| SzekszГЎrd            | 14       | 0.93%   |
| PÃ©cs                 | 13       | 0.87%   |
| Oroshaza                | 13       | 0.87%   |
| GГ¶dГ¶llЕ‘       | 13       | 0.87%   |
| TatabГЎnya            | 12       | 0.8%    |
| Gyomro                  | 12       | 0.8%    |
| Zalaegerszeg            | 11       | 0.73%   |
| MosonmagyarГіvГЎr   | 11       | 0.73%   |
| Hodmezovasarhely        | 11       | 0.73%   |
| Г‰rd                 | 10       | 0.67%   |
| SzekszÃ¡rd            | 9        | 0.6%    |
| BГ©kГ©scsaba        | 9        | 0.6%    |
| Baja                    | 9        | 0.6%    |
| Tiszafured              | 8        | 0.53%   |
| Szolnok                 | 8        | 0.53%   |
| Papa                    | 8        | 0.53%   |
| Gyongyos                | 8        | 0.53%   |
| GyÅ‘r                | 8        | 0.53%   |
| Ajka                    | 8        | 0.53%   |
| Toeroekbalint           | 7        | 0.47%   |
| TatabÃ¡nya            | 7        | 0.47%   |
| SzÃ©kesfehÃ©rvÃ¡r | 7        | 0.47%   |
| MohГЎcs               | 7        | 0.47%   |
| KecskemÃ©t            | 7        | 0.47%   |
| Hatvan                  | 7        | 0.47%   |
| Esztergom               | 7        | 0.47%   |
| DunaГєjvГЎros       | 7        | 0.47%   |
| Szentes                 | 6        | 0.4%    |
| Szentendre              | 6        | 0.4%    |
| Sopron                  | 6        | 0.4%    |
| God                     | 6        | 0.4%    |
| Cegled                  | 6        | 0.4%    |
| Ã‰rd                 | 6        | 0.4%    |
| Veresegyhaz             | 5        | 0.33%   |
| Vecses                  | 5        | 0.33%   |
| SiГіfok               | 5        | 0.33%   |
| Pecel                   | 5        | 0.33%   |
| Nagykoros               | 5        | 0.33%   |
| Nagykanizsa             | 5        | 0.33%   |
| Monor                   | 5        | 0.33%   |
| Mezokovesd              | 5        | 0.33%   |
| Mako                    | 5        | 0.33%   |
| Kistarcsa               | 5        | 0.33%   |
| Dunakeszi               | 5        | 0.33%   |
| Budakeszi               | 5        | 0.33%   |
| VeszprГ©m             | 4        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 477      | 990    | 21.54%  |
| Samsung Electronics | 359      | 625    | 16.21%  |
| Seagate             | 333      | 558    | 15.04%  |
| Kingston            | 289      | 546    | 13.05%  |
| Toshiba             | 180      | 330    | 8.13%   |
| Hitachi             | 97       | 136    | 4.38%   |
| A-DATA Technology   | 71       | 129    | 3.21%   |
| MAXTOR              | 44       | 73     | 1.99%   |
| SanDisk             | 29       | 32     | 1.31%   |
| Crucial             | 25       | 46     | 1.13%   |
| SPCC                | 24       | 39     | 1.08%   |
| OCZ                 | 17       | 22     | 0.77%   |
| HGST                | 16       | 32     | 0.72%   |
| Fujitsu             | 16       | 17     | 0.72%   |
| Intel               | 15       | 31     | 0.68%   |
| China               | 13       | 23     | 0.59%   |
| Hewlett-Packard     | 12       | 19     | 0.54%   |
| Unknown             | 11       | 19     | 0.5%    |
| Patriot             | 10       | 18     | 0.45%   |
| Intenso             | 10       | 12     | 0.45%   |
| Apacer              | 10       | 22     | 0.45%   |
| Transcend           | 9        | 13     | 0.41%   |
| Gigabyte Technology | 9        | 25     | 0.41%   |
| SK Hynix            | 8        | 12     | 0.36%   |
| Kingmax             | 8        | 21     | 0.36%   |
| Zheino              | 6        | 16     | 0.27%   |
| PNY                 | 6        | 22     | 0.27%   |
| Micron Technology   | 6        | 7      | 0.27%   |
| KingSpec            | 6        | 6      | 0.27%   |
| JMicron             | 6        | 7      | 0.27%   |
| Team                | 5        | 7      | 0.23%   |
| Phison              | 5        | 8      | 0.23%   |
| Corsair             | 5        | 7      | 0.23%   |
| Verbatim            | 4        | 9      | 0.18%   |
| Netac               | 4        | 9      | 0.18%   |
| LITEON              | 4        | 4      | 0.18%   |
| USB3.0              | 3        | 4      | 0.14%   |
| Silicon Motion      | 3        | 4      | 0.14%   |
| QUANTUM             | 3        | 3      | 0.14%   |
| ASMT                | 3        | 3      | 0.14%   |
| WD MediaMax         | 2        | 4      | 0.09%   |
| SATAFIRM            | 2        | 2      | 0.09%   |
| Leven               | 2        | 2      | 0.09%   |
| KingDian            | 2        | 2      | 0.09%   |
| Integral            | 2        | 2      | 0.09%   |
| ICY BOX             | 2        | 3      | 0.09%   |
| HGST HTS            | 2        | 2      | 0.09%   |
| GOODRAM             | 2        | 2      | 0.09%   |
| Apple               | 2        | 3      | 0.09%   |
| AMD                 | 2        | 2      | 0.09%   |
| XPG                 | 1        | 1      | 0.05%   |
| WDC WDS             | 1        | 1      | 0.05%   |
| Vaseky              | 1        | 1      | 0.05%   |
| USB2.0              | 1        | 1      | 0.05%   |
| USB                 | 1        | 1      | 0.05%   |
| TO Exter            | 1        | 1      | 0.05%   |
| SSD 120G            | 1        | 1      | 0.05%   |
| sobetter            | 1        | 1      | 0.05%   |
| ROG                 | 1        | 1      | 0.05%   |
| RECADATA            | 1        | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37120G 120GB SSD  | 64       | 2.55%   |
| Kingston SA400S37240G 240GB SSD  | 61       | 2.43%   |
| Kingston SV300S37A120G 120GB SSD | 53       | 2.11%   |
| Toshiba DT01ACA100 1TB           | 49       | 1.95%   |
| Seagate ST500DM002-1BD142 500GB  | 40       | 1.6%    |
| Toshiba DT01ACA050 500GB         | 30       | 1.2%    |
| A-DATA SU630 240GB SSD           | 27       | 1.08%   |
| Seagate ST380815AS 80GB          | 24       | 0.96%   |
| Samsung HD502HJ 500GB            | 21       | 0.84%   |
| Toshiba HDWD110 1TB              | 20       | 0.8%    |
| A-DATA SU700 120GB SSD           | 20       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 19       | 0.76%   |
| Kingston SUV400S37120G 120GB SSD | 19       | 0.76%   |
| Toshiba DT01ACA200 2TB           | 17       | 0.68%   |
| Samsung SSD 860 EVO 250GB        | 17       | 0.68%   |
| Toshiba HDWD130 3TB              | 15       | 0.6%    |
| Samsung SSD 850 EVO 250GB        | 15       | 0.6%    |
| Kingston SHFS37A120G 120GB SSD   | 15       | 0.6%    |
| Kingston SA400S37480G 480GB SSD  | 15       | 0.6%    |
| Seagate ST3160815AS 160GB        | 14       | 0.56%   |
| Samsung HD322HJ 320GB            | 14       | 0.56%   |
| Samsung HD161HJ 160GB            | 14       | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB   | 13       | 0.52%   |
| Samsung HD502IJ 500GB            | 13       | 0.52%   |
| Hitachi HDS721050CLA360 500GB    | 13       | 0.52%   |
| Seagate ST3160318AS 160GB        | 12       | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 11       | 0.44%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 11       | 0.44%   |
| WDC WD10EZRX-00L4HB0 1TB         | 11       | 0.44%   |
| WDC WD10EZEX-22MFCA0 1TB         | 11       | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB   | 11       | 0.44%   |
| Samsung HD103UJ 1TB              | 11       | 0.44%   |
| Kingston SV300S37A240G 240GB SSD | 11       | 0.44%   |
| WDC WD5000AAKX-001CA0 500GB      | 10       | 0.4%    |
| WDC WD10EZRZ-00HTKB0 1TB         | 10       | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB         | 10       | 0.4%    |
| Seagate ST3250318AS 250GB        | 10       | 0.4%    |
| Samsung SSD 840 EVO 120GB        | 10       | 0.4%    |
| Samsung HD501LJ 500GB            | 10       | 0.4%    |
| Samsung HD160JJ 160GB            | 10       | 0.4%    |
| Samsung HD082GJ 80GB             | 10       | 0.4%    |
| Kingston SH103S3120G 120GB SSD   | 10       | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 9        | 0.36%   |
| WDC WD5000AADS-00S9B0 500GB      | 9        | 0.36%   |
| SPCC Solid State Disk 256GB      | 9        | 0.36%   |
| Samsung SSD 850 EVO 500GB        | 9        | 0.36%   |
| Samsung HD154UI 1TB              | 9        | 0.36%   |
| Fujitsu MHZ2160BH G2 160GB       | 9        | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 8        | 0.32%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 8        | 0.32%   |
| Toshiba DT01ACA300 3TB           | 8        | 0.32%   |
| Samsung HD321KJ 320GB            | 8        | 0.32%   |
| Samsung HD103SJ 1TB              | 8        | 0.32%   |
| Kingston SV300S37A60G 64GB SSD   | 8        | 0.32%   |
| Kingston SUV400S37240G 240GB SSD | 8        | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 7        | 0.28%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 7        | 0.28%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 7        | 0.28%   |
| WDC WD20EZRX-00D8PB0 2TB         | 7        | 0.28%   |
| Samsung SSD 860 EVO 500GB        | 7        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 446      | 899    | 32.63%  |
| Seagate             | 327      | 549    | 23.92%  |
| Samsung Electronics | 220      | 362    | 16.09%  |
| Toshiba             | 172      | 321    | 12.58%  |
| Hitachi             | 97       | 136    | 7.1%    |
| MAXTOR              | 44       | 73     | 3.22%   |
| HGST                | 16       | 32     | 1.17%   |
| Fujitsu             | 16       | 17     | 1.17%   |
| Hewlett-Packard     | 7        | 9      | 0.51%   |
| USB3.0              | 3        | 4      | 0.22%   |
| Unknown             | 3        | 6      | 0.22%   |
| QUANTUM             | 3        | 3      | 0.22%   |
| ASMT                | 3        | 3      | 0.22%   |
| WD MediaMax         | 2        | 4      | 0.15%   |
| ICY BOX             | 2        | 3      | 0.15%   |
| Apple               | 2        | 3      | 0.15%   |
| USB                 | 1        | 1      | 0.07%   |
| IBM/Hitachi         | 1        | 1      | 0.07%   |
| ExcelStor           | 1        | 1      | 0.07%   |
| Asmedia             | 1        | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 271      | 501    | 35.61%  |
| Samsung Electronics | 127      | 209    | 16.69%  |
| A-DATA Technology   | 68       | 122    | 8.94%   |
| WDC                 | 44       | 86     | 5.78%   |
| SanDisk             | 27       | 29     | 3.55%   |
| Crucial             | 21       | 39     | 2.76%   |
| SPCC                | 18       | 33     | 2.37%   |
| OCZ                 | 17       | 22     | 2.23%   |
| Intel               | 13       | 24     | 1.71%   |
| China               | 13       | 23     | 1.71%   |
| Intenso             | 10       | 12     | 1.31%   |
| Apacer              | 10       | 22     | 1.31%   |
| Toshiba             | 9        | 9      | 1.18%   |
| Patriot             | 9        | 17     | 1.18%   |
| Transcend           | 8        | 12     | 1.05%   |
| Kingmax             | 8        | 21     | 1.05%   |
| Gigabyte Technology | 7        | 22     | 0.92%   |
| PNY                 | 6        | 22     | 0.79%   |
| KingSpec            | 6        | 6      | 0.79%   |
| Team                | 5        | 7      | 0.66%   |
| SK Hynix            | 5        | 9      | 0.66%   |
| Micron Technology   | 5        | 6      | 0.66%   |
| JMicron             | 5        | 6      | 0.66%   |
| Corsair             | 5        | 7      | 0.66%   |
| Verbatim            | 4        | 9      | 0.53%   |
| Netac               | 4        | 9      | 0.53%   |
| LITEON              | 4        | 4      | 0.53%   |
| Hewlett-Packard     | 3        | 3      | 0.39%   |
| SATAFIRM            | 2        | 2      | 0.26%   |
| KingDian            | 2        | 2      | 0.26%   |
| Integral            | 2        | 2      | 0.26%   |
| GOODRAM             | 2        | 2      | 0.26%   |
| AMD                 | 2        | 2      | 0.26%   |
| WDC WDS             | 1        | 1      | 0.13%   |
| Vaseky              | 1        | 1      | 0.13%   |
| Unknown             | 1        | 2      | 0.13%   |
| TO Exter            | 1        | 1      | 0.13%   |
| Seagate             | 1        | 1      | 0.13%   |
| RECADATA            | 1        | 1      | 0.13%   |
| Platinet            | 1        | 1      | 0.13%   |
| Leven               | 1        | 1      | 0.13%   |
| KODAK               | 1        | 1      | 0.13%   |
| KingFast            | 1        | 1      | 0.13%   |
| HS-SSD-C100         | 1        | 1      | 0.13%   |
| GALAX               | 1        | 2      | 0.13%   |
| External            | 1        | 1      | 0.13%   |
| EMTEC               | 1        | 1      | 0.13%   |
| EAGET S5            | 1        | 1      | 0.13%   |
| DREVO               | 1        | 1      | 0.13%   |
| BIWIN               | 1        | 5      | 0.13%   |
| 2-Power             | 1        | 1      | 0.13%   |
| Unknown             | 1        | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1032     | 2428   | 56.77%  |
| SSD     | 657      | 1326   | 36.14%  |
| NVMe    | 101      | 181    | 5.56%   |
| Unknown | 21       | 25     | 1.16%   |
| MMC     | 7        | 9      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1256     | 3682   | 88.26%  |
| NVMe | 101      | 181    | 7.1%    |
| SAS  | 59       | 97     | 4.15%   |
| MMC  | 7        | 9      | 0.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1149     | 2648   | 68.6%   |
| 0.51-1.0   | 339      | 699    | 20.24%  |
| 1.01-2.0   | 107      | 185    | 6.39%   |
| 2.01-3.0   | 36       | 113    | 2.15%   |
| 3.01-4.0   | 31       | 62     | 1.85%   |
| 4.01-10.0  | 10       | 32     | 0.6%    |
| 10.01-20.0 | 3        | 15     | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 642      | 44.09%  |
| 101-250        | 258      | 17.72%  |
| 251-500        | 153      | 10.51%  |
| 51-100         | 93       | 6.39%   |
| 501-1000       | 76       | 5.22%   |
| 1001-2000      | 65       | 4.46%   |
| 21-50          | 56       | 3.85%   |
| 1-20           | 50       | 3.43%   |
| More than 3000 | 39       | 2.68%   |
| 2001-3000      | 24       | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 642      | 43.82%  |
| 1-20           | 432      | 29.49%  |
| 21-50          | 103      | 7.03%   |
| 51-100         | 77       | 5.26%   |
| 101-250        | 66       | 4.51%   |
| 501-1000       | 52       | 3.55%   |
| 251-500        | 40       | 2.73%   |
| 1001-2000      | 29       | 1.98%   |
| More than 3000 | 15       | 1.02%   |
| 2001-3000      | 9        | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| A-DATA Technology SU630 240GB SSD | 17       | 20     | 3.39%   |
| Seagate ST500DM002-1BD142 500GB   | 14       | 36     | 2.79%   |
| Kingston SV300S37A120G 120GB SSD  | 12       | 12     | 2.4%    |
| Samsung Electronics HD103UJ 1TB   | 10       | 26     | 2%      |
| Toshiba DT01ACA050 500GB          | 8        | 14     | 1.6%    |
| WDC WD5000AAKX-001CA0 500GB       | 6        | 6      | 1.2%    |
| WDC WD5000AADS-00S9B0 500GB       | 6        | 7      | 1.2%    |
| Toshiba DT01ACA100 1TB            | 6        | 13     | 1.2%    |
| Seagate ST3250318AS 250GB         | 5        | 9      | 1%      |
| Samsung Electronics HD502HJ 500GB | 5        | 8      | 1%      |
| Samsung Electronics HD321KJ 320GB | 5        | 5      | 1%      |
| Samsung Electronics HD161HJ 160GB | 5        | 5      | 1%      |
| Samsung Electronics HD103SI 1TB   | 5        | 6      | 1%      |
| WDC WD5000AAKS-00UU3A0 500GB      | 4        | 8      | 0.8%    |
| Seagate ST380815AS 80GB           | 4        | 7      | 0.8%    |
| Seagate ST3160815AS 160GB         | 4        | 4      | 0.8%    |
| Samsung Electronics SP2004C 200GB | 4        | 8      | 0.8%    |
| Samsung Electronics HD161GJ 160GB | 4        | 5      | 0.8%    |
| Samsung Electronics HD082GJ 80GB  | 4        | 4      | 0.8%    |
| MAXTOR 6Y080M0 81GB               | 4        | 5      | 0.8%    |
| MAXTOR 6Y080L0 82GB               | 4        | 7      | 0.8%    |
| MAXTOR 2B020H1 20GB               | 4        | 11     | 0.8%    |
| WDC WD5000AAKX-08U6AA0 500GB      | 3        | 7      | 0.6%    |
| WDC WD5000AAKX-07U6AA0 500GB      | 3        | 6      | 0.6%    |
| WDC WD3200AAKS-00L9A0 320GB       | 3        | 5      | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB          | 3        | 3      | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB           | 3        | 6      | 0.6%    |
| SK Hynix SC210 2.5 7MM 128GB SSD  | 3        | 7      | 0.6%    |
| Seagate ST4000DM000-1F2168 4TB    | 3        | 11     | 0.6%    |
| Seagate ST3500320AS 500GB         | 3        | 4      | 0.6%    |
| Seagate ST3160812AS 160GB         | 3        | 3      | 0.6%    |
| Seagate ST3160318AS 160GB         | 3        | 3      | 0.6%    |
| Samsung Electronics SP2504C 250GB | 3        | 3      | 0.6%    |
| Samsung Electronics SP1203N 120GB | 3        | 3      | 0.6%    |
| Samsung Electronics HD642JJ 640GB | 3        | 7      | 0.6%    |
| Samsung Electronics HD502IJ 500GB | 3        | 4      | 0.6%    |
| Samsung Electronics HD501LJ 500GB | 3        | 4      | 0.6%    |
| Samsung Electronics HD322HJ 320GB | 3        | 3      | 0.6%    |
| Samsung Electronics HD160JJ 160GB | 3        | 3      | 0.6%    |
| Samsung Electronics HD080HJ 80GB  | 3        | 4      | 0.6%    |
| Hitachi HTS545050B9A300 500GB     | 3        | 3      | 0.6%    |
| Hitachi HDP725050GLA360 500GB     | 3        | 3      | 0.6%    |
| WDC WD800AAJS-75M0A0 80GB         | 2        | 3      | 0.4%    |
| WDC WD6400AAVS-00G9B1 640GB       | 2        | 2      | 0.4%    |
| WDC WD5000AZRX-00L4HB0 500GB      | 2        | 2      | 0.4%    |
| WDC WD5000AVCS-632DY1 500GB       | 2        | 4      | 0.4%    |
| WDC WD5000AAKX-22ERMA0 500GB      | 2        | 3      | 0.4%    |
| WDC WD5000AAKX-221CA1 500GB       | 2        | 2      | 0.4%    |
| WDC WD5000AAKX-08ERMA0 500GB      | 2        | 4      | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 2      | 0.4%    |
| WDC WD5000AAKS-22A7B0 500GB       | 2        | 2      | 0.4%    |
| WDC WD3200AAKS-00UU3A0 320GB      | 2        | 3      | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB          | 2        | 3      | 0.4%    |
| WDC WD20EARX-00PASB0 2TB          | 2        | 2      | 0.4%    |
| WDC WD15EARS-00MVWB0 1TB          | 2        | 3      | 0.4%    |
| WDC WD10EZRX-00A8LB0 1TB          | 2        | 6      | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 12     | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 2      | 0.4%    |
| WDC WD10EURS-630AB1 1TB           | 2        | 2      | 0.4%    |
| WDC WD10EALX-009BA0 1TB           | 2        | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 135      | 241    | 28.3%   |
| Seagate             | 91       | 148    | 19.08%  |
| Samsung Electronics | 91       | 143    | 19.08%  |
| Hitachi             | 30       | 46     | 6.29%   |
| Toshiba             | 29       | 47     | 6.08%   |
| Kingston            | 25       | 28     | 5.24%   |
| MAXTOR              | 24       | 50     | 5.03%   |
| A-DATA Technology   | 21       | 30     | 4.4%    |
| HGST                | 6        | 7      | 1.26%   |
| Fujitsu             | 4        | 4      | 0.84%   |
| SK Hynix            | 3        | 7      | 0.63%   |
| WD MediaMax         | 2        | 4      | 0.42%   |
| KingSpec            | 2        | 2      | 0.42%   |
| Hewlett-Packard     | 2        | 2      | 0.42%   |
| SATAFIRM            | 1        | 1      | 0.21%   |
| SanDisk             | 1        | 1      | 0.21%   |
| OCZ                 | 1        | 3      | 0.21%   |
| LITEON              | 1        | 1      | 0.21%   |
| Kingmax             | 1        | 1      | 0.21%   |
| Intenso             | 1        | 1      | 0.21%   |
| Intel               | 1        | 1      | 0.21%   |
| ICY BOX             | 1        | 1      | 0.21%   |
| IBM/Hitachi         | 1        | 1      | 0.21%   |
| ExcelStor           | 1        | 1      | 0.21%   |
| China               | 1        | 1      | 0.21%   |
| ASMT                | 1        | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 134      | 240    | 32.45%  |
| Seagate             | 91       | 148    | 22.03%  |
| Samsung Electronics | 88       | 140    | 21.31%  |
| Hitachi             | 30       | 46     | 7.26%   |
| Toshiba             | 28       | 46     | 6.78%   |
| MAXTOR              | 24       | 50     | 5.81%   |
| HGST                | 6        | 7      | 1.45%   |
| Fujitsu             | 4        | 4      | 0.97%   |
| WD MediaMax         | 2        | 4      | 0.48%   |
| Hewlett-Packard     | 2        | 2      | 0.48%   |
| ICY BOX             | 1        | 1      | 0.24%   |
| IBM/Hitachi         | 1        | 1      | 0.24%   |
| ExcelStor           | 1        | 1      | 0.24%   |
| ASMT                | 1        | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 357      | 691    | 85.2%   |
| SSD  | 62       | 82     | 14.8%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 2        | 2      | 28.57%  |
| Seagate ST380815AS 80GB           | 1        | 3      | 14.29%  |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 14.29%  |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 14.29%  |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 5      | 71.43%  |
| Seagate             | 1        | 3      | 14.29%  |
| Hewlett-Packard     | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 821      | 2309   | 51.57%  |
| Malfunc  | 406      | 773    | 25.5%   |
| Detected | 358      | 878    | 22.49%  |
| Failed   | 7        | 9      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 883      | 55.43%  |
| AMD                              | 342      | 21.47%  |
| JMicron Technology               | 72       | 4.52%   |
| Nvidia                           | 52       | 3.26%   |
| ASMedia Technology               | 51       | 3.2%    |
| Samsung Electronics              | 41       | 2.57%   |
| Marvell Technology Group         | 33       | 2.07%   |
| Kingston Technology Company      | 26       | 1.63%   |
| Phison Electronics               | 15       | 0.94%   |
| VIA Technologies                 | 12       | 0.75%   |
| Silicon Motion                   | 12       | 0.75%   |
| Silicon Image                    | 10       | 0.63%   |
| LSI Logic / Symbios Logic        | 9        | 0.56%   |
| Sandisk                          | 6        | 0.38%   |
| Micron/Crucial Technology        | 4        | 0.25%   |
| Integrated Technology Express    | 4        | 0.25%   |
| ADATA Technology                 | 4        | 0.25%   |
| SK Hynix                         | 3        | 0.19%   |
| Broadcom / LSI                   | 2        | 0.13%   |
| Adaptec                          | 2        | 0.13%   |
| Silicon Integrated Systems [SiS] | 1        | 0.06%   |
| Seagate Technology               | 1        | 0.06%   |
| Realtek Semiconductor            | 1        | 0.06%   |
| Promise Technology               | 1        | 0.06%   |
| OCZ Technology Group             | 1        | 0.06%   |
| Micron Technology                | 1        | 0.06%   |
| Initio                           | 1        | 0.06%   |
| HighPoint Technologies           | 1        | 0.06%   |
| Hewlett-Packard                  | 1        | 0.06%   |
| 3ware                            | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 179      | 7.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 152      | 6.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 120      | 5.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 107      | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 79       | 3.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 79       | 3.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 67       | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 64       | 2.83%   |
| AMD FCH IDE Controller                                                                  | 61       | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 58       | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 58       | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 51       | 2.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 46       | 2.04%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 45       | 1.99%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 45       | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 43       | 1.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 42       | 1.86%   |
| Intel SATA Controller [RAID mode]                                                       | 41       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 1.81%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 33       | 1.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29       | 1.28%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 26       | 1.15%   |
| Nvidia MCP61 SATA Controller                                                            | 25       | 1.11%   |
| JMicron JMB368 IDE controller                                                           | 25       | 1.11%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 21       | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 21       | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 21       | 0.93%   |
| Nvidia MCP61 IDE                                                                        | 20       | 0.89%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 19       | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 18       | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 18       | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                         | 17       | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 17       | 0.75%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 16       | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 15       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 15       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 15       | 0.66%   |
| AMD FCH SATA Controller D                                                               | 15       | 0.66%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 14       | 0.62%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 12       | 0.53%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 12       | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11       | 0.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 0.49%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.44%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 10       | 0.44%   |
| AMD SB600 IDE                                                                           | 10       | 0.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 9        | 0.4%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 9        | 0.4%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 9        | 0.4%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 8        | 0.35%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 8        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.31%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 7        | 0.31%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 7        | 0.31%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 7        | 0.31%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6        | 0.27%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 6        | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 868      | 51.61%  |
| IDE  | 624      | 37.1%   |
| NVMe | 104      | 6.18%   |
| RAID | 73       | 4.34%   |
| SCSI | 8        | 0.48%   |
| SAS  | 5        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 901      | 69.68%  |
| AMD    | 392      | 30.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 38       | 2.93%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 34       | 2.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24       | 1.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 19       | 1.46%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 18       | 1.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 16       | 1.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 16       | 1.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 15       | 1.16%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 15       | 1.16%   |
| AMD FX-8350 Eight-Core Processor              | 15       | 1.16%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 14       | 1.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 14       | 1.08%   |
| AMD FX-6300 Six-Core Processor                | 14       | 1.08%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 13       | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor           | 12       | 0.92%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 11       | 0.85%   |
| Intel Pentium 4 CPU 3.00GHz                   | 11       | 0.85%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 11       | 0.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 10       | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 10       | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9        | 0.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 9        | 0.69%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 9        | 0.69%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 9        | 0.69%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 9        | 0.69%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 8        | 0.62%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 8        | 0.62%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 8        | 0.62%   |
| AMD Ryzen 5 3600 6-Core Processor             | 8        | 0.62%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8        | 0.62%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 7        | 0.54%   |
| Intel Pentium CPU G840 @ 2.80GHz              | 7        | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 7        | 0.54%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 7        | 0.54%   |
| Intel Core i5-2300 CPU @ 2.80GHz              | 7        | 0.54%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 7        | 0.54%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 7        | 0.54%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 7        | 0.54%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz          | 7        | 0.54%   |
| Intel Celeron CPU E3400 @ 2.60GHz             | 7        | 0.54%   |
| AMD Ryzen 3 1200 Quad-Core Processor          | 7        | 0.54%   |
| AMD Athlon X4 860K Quad Core Processor        | 7        | 0.54%   |
| AMD Athlon II X2 260 Processor                | 7        | 0.54%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 7        | 0.54%   |
| AMD A4-5300 APU with Radeon HD Graphics       | 7        | 0.54%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 6        | 0.46%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 6        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6        | 0.46%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 6        | 0.46%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 6        | 0.46%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 6        | 0.46%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 6        | 0.46%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 6        | 0.46%   |
| Intel Core 2 Duo CPU E8200 @ 2.66GHz          | 6        | 0.46%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 6        | 0.46%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 6        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6        | 0.46%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 5        | 0.39%   |
| Intel Pentium D CPU 2.80GHz                   | 5        | 0.39%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 5        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 222      | 17.14%  |
| Intel Core 2 Duo        | 131      | 10.12%  |
| Intel Core i3           | 128      | 9.88%   |
| Intel Pentium           | 61       | 4.71%   |
| Intel Core i7           | 60       | 4.63%   |
| Intel Celeron           | 58       | 4.48%   |
| Intel Pentium Dual-Core | 53       | 4.09%   |
| AMD A8                  | 51       | 3.94%   |
| Intel Xeon              | 48       | 3.71%   |
| Intel Core 2 Quad       | 46       | 3.55%   |
| AMD FX                  | 46       | 3.55%   |
| AMD Ryzen 5             | 44       | 3.4%    |
| AMD Athlon II X2        | 32       | 2.47%   |
| AMD Athlon 64 X2        | 26       | 2.01%   |
| AMD Ryzen 3             | 23       | 1.78%   |
| Intel Core 2            | 20       | 1.54%   |
| AMD A4                  | 20       | 1.54%   |
| AMD Ryzen 7             | 19       | 1.47%   |
| Intel Pentium 4         | 18       | 1.39%   |
| AMD Phenom II X4        | 18       | 1.39%   |
| Intel Pentium Dual      | 16       | 1.24%   |
| Intel Atom              | 15       | 1.16%   |
| Intel Pentium D         | 12       | 0.93%   |
| AMD A6                  | 12       | 0.93%   |
| AMD A10                 | 12       | 0.93%   |
| AMD Sempron             | 10       | 0.77%   |
| AMD Athlon Dual Core    | 10       | 0.77%   |
| AMD Athlon X4           | 9        | 0.69%   |
| AMD Athlon II X4        | 9        | 0.69%   |
| AMD Athlon              | 7        | 0.54%   |
| AMD Athlon 64           | 6        | 0.46%   |
| AMD Phenom II X6        | 5        | 0.39%   |
| Other                   | 4        | 0.31%   |
| AMD Phenom II X2        | 4        | 0.31%   |
| AMD Phenom              | 4        | 0.31%   |
| Intel Pentium Gold      | 3        | 0.23%   |
| Intel Genuine           | 3        | 0.23%   |
| Intel Celeron D         | 3        | 0.23%   |
| AMD Ryzen 9             | 3        | 0.23%   |
| AMD GX                  | 3        | 0.23%   |
| AMD Athlon X2           | 3        | 0.23%   |
| AMD Athlon II X3        | 3        | 0.23%   |
| Intel Core i9           | 2        | 0.15%   |
| AMD Turion II Neo       | 2        | 0.15%   |
| AMD Phenom II X3        | 2        | 0.15%   |
| AMD E                   | 2        | 0.15%   |
| Intel Core 2 Extreme    | 1        | 0.08%   |
| AMD Ryzen 5 PRO         | 1        | 0.08%   |
| AMD PRO A8              | 1        | 0.08%   |
| AMD Opteron             | 1        | 0.08%   |
| AMD E1                  | 1        | 0.08%   |
| AMD Athlon II Neo       | 1        | 0.08%   |
| AMD A12                 | 1        | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 626      | 48.15%  |
| 4      | 441      | 33.92%  |
| 6      | 86       | 6.62%   |
| 1      | 85       | 6.54%   |
| 8      | 29       | 2.23%   |
| 3      | 26       | 2%      |
| 12     | 5        | 0.38%   |
| 28     | 1        | 0.08%   |
| 16     | 1        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1286     | 99.38%  |
| 2      | 8        | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 830      | 63.94%  |
| 2      | 468      | 36.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1283     | 99.15%  |
| 32-bit         | 6        | 0.46%   |
| Unknown        | 5        | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 164      | 12.34%  |
| Unknown    | 140      | 10.53%  |
| 0x306c3    | 118      | 8.88%   |
| 0x206a7    | 103      | 7.75%   |
| 0x306a9    | 87       | 6.55%   |
| 0x06001119 | 72       | 5.42%   |
| 0x506e3    | 45       | 3.39%   |
| 0x010000c8 | 44       | 3.31%   |
| 0x10676    | 38       | 2.86%   |
| 0x906e9    | 31       | 2.33%   |
| 0x6fd      | 28       | 2.11%   |
| 0x6fb      | 26       | 1.96%   |
| 0x06000852 | 25       | 1.88%   |
| 0x906ea    | 23       | 1.73%   |
| 0x0800820d | 22       | 1.66%   |
| 0x106e5    | 15       | 1.13%   |
| 0x6f2      | 14       | 1.05%   |
| 0x08701021 | 14       | 1.05%   |
| 0x06003106 | 13       | 0.98%   |
| 0x206c2    | 12       | 0.9%    |
| 0x906eb    | 11       | 0.83%   |
| 0x20655    | 11       | 0.83%   |
| 0x010000db | 11       | 0.83%   |
| 0x10677    | 10       | 0.75%   |
| 0x03000027 | 10       | 0.75%   |
| 0xf43      | 9        | 0.68%   |
| 0x0810100b | 9        | 0.68%   |
| 0x08001138 | 9        | 0.68%   |
| 0x0600084f | 9        | 0.68%   |
| 0x6f6      | 8        | 0.6%    |
| 0x106a5    | 8        | 0.6%    |
| 0x0600063e | 8        | 0.6%    |
| 0xf41      | 7        | 0.53%   |
| 0xa0653    | 7        | 0.53%   |
| 0x08108109 | 7        | 0.53%   |
| 0x0700010f | 7        | 0.53%   |
| 0xf47      | 6        | 0.45%   |
| 0x20652    | 6        | 0.45%   |
| 0x08701013 | 6        | 0.45%   |
| 0x06003104 | 6        | 0.45%   |
| 0xf65      | 5        | 0.38%   |
| 0x906ec    | 5        | 0.38%   |
| 0x706a1    | 5        | 0.38%   |
| 0x406c4    | 5        | 0.38%   |
| 0x10661    | 5        | 0.38%   |
| 0x010000dc | 5        | 0.38%   |
| 0x010000c7 | 5        | 0.38%   |
| 0x30661    | 4        | 0.3%    |
| 0x106ca    | 4        | 0.3%    |
| 0x08101016 | 4        | 0.3%    |
| 0x01000095 | 4        | 0.3%    |
| 0xf64      | 3        | 0.23%   |
| 0xf49      | 3        | 0.23%   |
| 0xf29      | 3        | 0.23%   |
| 0x30678    | 3        | 0.23%   |
| 0x30673    | 3        | 0.23%   |
| 0x206d7    | 3        | 0.23%   |
| 0x106c2    | 3        | 0.23%   |
| 0x07030106 | 3        | 0.23%   |
| 0x06000822 | 3        | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Penryn          | 215      | 16.63%  |
| Haswell         | 128      | 9.9%    |
| SandyBridge     | 117      | 9.05%   |
| Piledriver      | 111      | 8.58%   |
| IvyBridge       | 93       | 7.19%   |
| K10             | 86       | 6.65%   |
| Core            | 83       | 6.42%   |
| KabyLake        | 77       | 5.96%   |
| Skylake         | 51       | 3.94%   |
| K8 Hammer       | 48       | 3.71%   |
| NetBurst        | 42       | 3.25%   |
| Zen+            | 34       | 2.63%   |
| Westmere        | 29       | 2.24%   |
| Zen 2           | 26       | 2.01%   |
| Zen             | 25       | 1.93%   |
| Nehalem         | 23       | 1.78%   |
| Steamroller     | 21       | 1.62%   |
| Silvermont      | 13       | 1.01%   |
| Bonnell         | 11       | 0.85%   |
| K10 Llano       | 10       | 0.77%   |
| CometLake       | 10       | 0.77%   |
| Bulldozer       | 9        | 0.7%    |
| Jaguar          | 8        | 0.62%   |
| Goldmont plus   | 6        | 0.46%   |
| Zen 3           | 5        | 0.39%   |
| Puma            | 4        | 0.31%   |
| Excavator       | 2        | 0.15%   |
| Bobcat          | 2        | 0.15%   |
| K8 & K10 hybrid | 1        | 0.08%   |
| Icelake         | 1        | 0.08%   |
| Goldmont        | 1        | 0.08%   |
| Unknown         | 1        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 467      | 34.09%  |
| Intel                      | 453      | 33.07%  |
| AMD                        | 441      | 32.19%  |
| VIA Technologies           | 4        | 0.29%   |
| ASPEED Technology          | 3        | 0.22%   |
| Matrox Electronics Systems | 1        | 0.07%   |
| ATI Technologies           | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 70       | 4.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 67       | 4.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 53       | 3.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 51       | 3.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 42       | 2.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 39       | 2.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 39       | 2.73%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 36       | 2.52%   |
| AMD Richland [Radeon HD 8570D]                                                           | 34       | 2.38%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 32       | 2.24%   |
| Intel HD Graphics 530                                                                    | 29       | 2.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26       | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 25       | 1.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 21       | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 19       | 1.33%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 19       | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 18       | 1.26%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 18       | 1.26%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 17       | 1.19%   |
| Intel HD Graphics 630                                                                    | 13       | 0.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12       | 0.84%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 12       | 0.84%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                                | 12       | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 11       | 0.77%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 11       | 0.77%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 11       | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 10       | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 10       | 0.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 10       | 0.7%    |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 10       | 0.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 10       | 0.7%    |
| Nvidia G94 [GeForce 9600 GT]                                                             | 9        | 0.63%   |
| AMD RS880 [Radeon HD 4200]                                                               | 9        | 0.63%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 8        | 0.56%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 8        | 0.56%   |
| AMD RS880 [Radeon HD 4250]                                                               | 8        | 0.56%   |
| AMD RS780C [Radeon 3100]                                                                 | 8        | 0.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8        | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7        | 0.49%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7        | 0.49%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 7        | 0.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7        | 0.49%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 7        | 0.49%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 7        | 0.49%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 6        | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6        | 0.42%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 6        | 0.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6        | 0.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6        | 0.42%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 6        | 0.42%   |
| AMD RS780L [Radeon 3000]                                                                 | 6        | 0.42%   |
| AMD Richland [Radeon HD 8470D]                                                           | 6        | 0.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 0.42%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 6        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 5        | 0.35%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 0.35%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 5        | 0.35%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5        | 0.35%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5        | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 444      | 33.59%  |
| 1 x Intel           | 407      | 30.79%  |
| 1 x AMD             | 392      | 29.65%  |
| 2 x AMD             | 42       | 3.18%   |
| Intel + Nvidia      | 14       | 1.06%   |
| Intel + AMD         | 6        | 0.45%   |
| 1 x VIA             | 4        | 0.3%    |
| AMD + Nvidia        | 4        | 0.3%    |
| 2 x Nvidia          | 3        | 0.23%   |
| 1 x ASPEED          | 2        | 0.15%   |
| 1 x Matrox          | 1        | 0.08%   |
| 1 x Intel + 3 x AMD | 1        | 0.08%   |
| Intel + 2 x Nvidia  | 1        | 0.08%   |
| AMD + ASPEED        | 1        | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1140     | 87.29%  |
| Proprietary | 115      | 8.81%   |
| Unknown     | 51       | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 479      | 35.4%   |
| 0.51-1.0   | 281      | 20.77%  |
| 0.01-0.5   | 239      | 17.66%  |
| 1.01-2.0   | 193      | 14.26%  |
| 3.01-4.0   | 75       | 5.54%   |
| 7.01-8.0   | 39       | 2.88%   |
| 5.01-6.0   | 27       | 2%      |
| 2.01-3.0   | 16       | 1.18%   |
| 16.01-24.0 | 2        | 0.15%   |
| 8.01-16.0  | 2        | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 291      | 22.82%  |
| Goldstar                | 216      | 16.94%  |
| Dell                    | 94       | 7.37%   |
| Philips                 | 71       | 5.57%   |
| BenQ                    | 69       | 5.41%   |
| Ancor Communications    | 69       | 5.41%   |
| Acer                    | 62       | 4.86%   |
| Hewlett-Packard         | 56       | 4.39%   |
| Fujitsu Siemens         | 38       | 2.98%   |
| AOC                     | 22       | 1.73%   |
| Lenovo                  | 20       | 1.57%   |
| Eizo                    | 20       | 1.57%   |
| LG Electronics          | 19       | 1.49%   |
| HannStar                | 17       | 1.33%   |
| Sony                    | 14       | 1.1%    |
| HKC                     | 14       | 1.1%    |
| NEC Computers           | 13       | 1.02%   |
| Vestel Elektronik       | 10       | 0.78%   |
| Belinea                 | 10       | 0.78%   |
| Medion                  | 9        | 0.71%   |
| IBM                     | 9        | 0.71%   |
| ASUSTek Computer        | 9        | 0.71%   |
| ViewSonic               | 8        | 0.63%   |
| Unknown                 | 8        | 0.63%   |
| Toshiba                 | 6        | 0.47%   |
| Panasonic               | 6        | 0.47%   |
| Arnos Instruments       | 6        | 0.47%   |
| Videoseven              | 5        | 0.39%   |
| Plain Tree Systems      | 5        | 0.39%   |
| OEM                     | 5        | 0.39%   |
| MStar                   | 5        | 0.39%   |
| Gericom                 | 5        | 0.39%   |
| FUS                     | 5        | 0.39%   |
| Iiyama                  | 4        | 0.31%   |
| Orion                   | 3        | 0.24%   |
| KTC                     | 3        | 0.24%   |
| Impression              | 3        | 0.24%   |
| Daewoo                  | 3        | 0.24%   |
| Chi Mei Optoelectronics | 3        | 0.24%   |
| ___                     | 2        | 0.16%   |
| ZLS                     | 2        | 0.16%   |
| Onkyo                   | 2        | 0.16%   |
| LLL                     | 2        | 0.16%   |
| InnoLux Display         | 2        | 0.16%   |
| GABA                    | 2        | 0.16%   |
| WYT                     | 1        | 0.08%   |
| Unknown (XXX)           | 1        | 0.08%   |
| Unknown (ADA)           | 1        | 0.08%   |
| UMC                     | 1        | 0.08%   |
| SHI                     | 1        | 0.08%   |
| S2-Tek                  | 1        | 0.08%   |
| RTK                     | 1        | 0.08%   |
| PRI                     | 1        | 0.08%   |
| MiTAC                   | 1        | 0.08%   |
| Marantz                 | 1        | 0.08%   |
| LMV                     | 1        | 0.08%   |
| LG Display              | 1        | 0.08%   |
| KSI                     | 1        | 0.08%   |
| Hitachi                 | 1        | 0.08%   |
| GVT                     | 1        | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                   | 30       | 2.27%   |
| HKC Checksum: 0x8a (valid) HKC1850 1360x768 304x228mm 15.0-inch       | 11       | 0.83%   |
| HannStar Hanns.G HX191 HSD0013 1280x1024 376x301mm 19.0-inch          | 11       | 0.83%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch  | 10       | 0.76%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 10       | 0.76%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 10       | 0.76%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 10       | 0.76%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 9        | 0.68%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 8        | 0.61%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.53%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 7        | 0.53%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 7        | 0.53%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 7        | 0.53%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 7        | 0.53%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 7        | 0.53%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 6        | 0.45%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 6        | 0.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.45%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 6        | 0.45%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.45%   |
| Eizo S2202W ENC1976 1680x1050 474x297mm 22.0-inch                     | 6        | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 5        | 0.38%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 5        | 0.38%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 5        | 0.38%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 5        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 5        | 0.38%   |
| Toshiba TV TSB0108 1920x540                                           | 4        | 0.3%    |
| Samsung Electronics SMB1920NW SAM06A5 1440x900 408x255mm 18.9-inch    | 4        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch     | 4        | 0.3%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.3%    |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                     | 4        | 0.3%    |
| Hewlett-Packard P222va HWP322B 1920x1080 477x268mm 21.5-inch          | 4        | 0.3%    |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch           | 4        | 0.3%    |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch           | 4        | 0.3%    |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch           | 4        | 0.3%    |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch             | 4        | 0.3%    |
| Goldstar E2350 GSM5790 1920x1080 510x290mm 23.1-inch                  | 4        | 0.3%    |
| AOC 2041 AOC2041 1600x900 443x249mm 20.0-inch                         | 4        | 0.3%    |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch       | 4        | 0.3%    |
| Ancor Communications VC279 ACI27C4 1920x1080 598x336mm 27.0-inch      | 4        | 0.3%    |
| Ancor Communications ASUS VW228 ACI22E2 1920x1080 521x293mm 23.5-inch | 4        | 0.3%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 4        | 0.3%    |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                     | 4        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.23%   |
| Sony TV SNY4803 1920x1080 1107x623mm 50.0-inch                        | 3        | 0.23%   |
| Samsung Electronics SyncMaster SAM03E1 1440x900 410x260mm 19.1-inch   | 3        | 0.23%   |
| Samsung Electronics SyncMaster SAM021D 1680x1050 433x271mm 20.1-inch  | 3        | 0.23%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 3        | 0.23%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 3        | 0.23%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch  | 3        | 0.23%   |
| Samsung Electronics S/M 755DF SAM1156 1600x1200 320x240mm 15.7-inch   | 3        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0D49 1920x1080 480x270mm 21.7-inch | 3        | 0.23%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                    | 3        | 0.23%   |
| NEC Computers LCD195VXM+ NEC66C1 1280x1024 376x301mm 19.0-inch        | 3        | 0.23%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 3        | 0.23%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 3        | 0.23%   |
| IBM L171 IBM24C9 1280x1024 337x270mm 17.0-inch                        | 3        | 0.23%   |
| Hewlett-Packard LP1965 HWP2692 1280x1024 380x300mm 19.1-inch          | 3        | 0.23%   |
| Goldstar W2242 GSM4B6F 1680x1050 474x296mm 22.0-inch                  | 3        | 0.23%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 3        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 502      | 40.26%  |
| 1280x1024 (SXGA)   | 234      | 18.77%  |
| 1680x1050 (WSXGA+) | 110      | 8.82%   |
| 1440x900 (WXGA+)   | 92       | 7.38%   |
| 1366x768 (WXGA)    | 55       | 4.41%   |
| 3840x2160 (4K)     | 53       | 4.25%   |
| 1360x768           | 32       | 2.57%   |
| 1920x1200 (WUXGA)  | 22       | 1.76%   |
| 2560x1440 (QHD)    | 21       | 1.68%   |
| 2560x1080          | 20       | 1.6%    |
| 1024x768 (XGA)     | 20       | 1.6%    |
| 1600x900 (HD+)     | 18       | 1.44%   |
| Unknown            | 17       | 1.36%   |
| 1920x540           | 11       | 0.88%   |
| 1600x1200          | 8        | 0.64%   |
| 1280x720 (HD)      | 6        | 0.48%   |
| 3840x1080          | 4        | 0.32%   |
| 3840x1200          | 2        | 0.16%   |
| 3440x1440          | 2        | 0.16%   |
| 3280x1080          | 2        | 0.16%   |
| 2288x1287          | 2        | 0.16%   |
| 2048x1152          | 2        | 0.16%   |
| 1280x960           | 2        | 0.16%   |
| 7680x2160          | 1        | 0.08%   |
| 3840x1920          | 1        | 0.08%   |
| 3600x1200          | 1        | 0.08%   |
| 3200x1080          | 1        | 0.08%   |
| 2880x1024          | 1        | 0.08%   |
| 2304x1024          | 1        | 0.08%   |
| 2048x1536          | 1        | 0.08%   |
| 1400x1050          | 1        | 0.08%   |
| 1280x800 (WXGA)    | 1        | 0.08%   |
| 1152x864           | 1        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 193      | 15.18%  |
| 21      | 179      | 14.08%  |
| 23      | 129      | 10.15%  |
| 17      | 116      | 9.13%   |
| 27      | 97       | 7.63%   |
| 24      | 97       | 7.63%   |
| 22      | 85       | 6.69%   |
| Unknown | 84       | 6.61%   |
| 18      | 76       | 5.98%   |
| 20      | 36       | 2.83%   |
| 15      | 33       | 2.6%    |
| 84      | 21       | 1.65%   |
| 34      | 21       | 1.65%   |
| 40      | 17       | 1.34%   |
| 31      | 17       | 1.34%   |
| 72      | 14       | 1.1%    |
| 32      | 8        | 0.63%   |
| 65      | 6        | 0.47%   |
| 54      | 5        | 0.39%   |
| 52      | 5        | 0.39%   |
| 42      | 5        | 0.39%   |
| 55      | 4        | 0.31%   |
| 64      | 3        | 0.24%   |
| 47      | 3        | 0.24%   |
| 14      | 3        | 0.24%   |
| 12      | 3        | 0.24%   |
| 48      | 2        | 0.16%   |
| 39      | 2        | 0.16%   |
| 26      | 2        | 0.16%   |
| 60      | 1        | 0.08%   |
| 50      | 1        | 0.08%   |
| 46      | 1        | 0.08%   |
| 13      | 1        | 0.08%   |
| 7       | 1        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 440      | 35.17%  |
| 501-600     | 312      | 24.94%  |
| 301-350     | 142      | 11.35%  |
| 351-400     | 125      | 9.99%   |
| Unknown     | 84       | 6.71%   |
| 1501-2000   | 35       | 2.8%    |
| 1001-1500   | 31       | 2.48%   |
| 701-800     | 29       | 2.32%   |
| 601-700     | 21       | 1.68%   |
| 801-900     | 19       | 1.52%   |
| 201-300     | 7        | 0.56%   |
| 901-1000    | 5        | 0.4%    |
| 101-200     | 1        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 647      | 53.56%  |
| 5/4     | 227      | 18.79%  |
| 16/10   | 200      | 16.56%  |
| Unknown | 63       | 5.22%   |
| 4/3     | 43       | 3.56%   |
| 21/9    | 21       | 1.74%   |
| 3/2     | 5        | 0.41%   |
| 6/5     | 2        | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 414      | 32.91%  |
| 151-200        | 280      | 22.26%  |
| 141-150        | 175      | 13.91%  |
| 301-350        | 98       | 7.79%   |
| Unknown        | 84       | 6.68%   |
| More than 1000 | 62       | 4.93%   |
| 351-500        | 46       | 3.66%   |
| 251-300        | 30       | 2.38%   |
| 501-1000       | 28       | 2.23%   |
| 101-110        | 24       | 1.91%   |
| 111-120        | 9        | 0.72%   |
| 91-100         | 3        | 0.24%   |
| 71-80          | 2        | 0.16%   |
| 81-90          | 1        | 0.08%   |
| 61-70          | 1        | 0.08%   |
| 1-40           | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 843      | 70.13%  |
| 101-120 | 206      | 17.14%  |
| Unknown | 84       | 6.99%   |
| 1-50    | 47       | 3.91%   |
| 121-160 | 14       | 1.16%   |
| 161-240 | 8        | 0.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1159     | 87.74%  |
| 2     | 103      | 7.8%    |
| 0     | 49       | 3.71%   |
| 3     | 10       | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 728      | 44.97%  |
| Intel                             | 347      | 21.43%  |
| Qualcomm Atheros                  | 152      | 9.39%   |
| Broadcom                          | 59       | 3.64%   |
| Qualcomm Atheros Communications   | 57       | 3.52%   |
| Broadcom Limited                  | 42       | 2.59%   |
| Ralink Technology                 | 41       | 2.53%   |
| Nvidia                            | 37       | 2.29%   |
| TP-Link                           | 31       | 1.91%   |
| Marvell Technology Group          | 24       | 1.48%   |
| Ralink                            | 14       | 0.86%   |
| VIA Technologies                  | 12       | 0.74%   |
| ASUSTek Computer                  | 10       | 0.62%   |
| Xiaomi                            | 6        | 0.37%   |
| Samsung Electronics               | 6        | 0.37%   |
| IMC Networks                      | 5        | 0.31%   |
| D-Link System                     | 5        | 0.31%   |
| Belkin Components                 | 5        | 0.31%   |
| Huawei Technologies               | 4        | 0.25%   |
| Edimax Technology                 | 3        | 0.19%   |
| Aquantia                          | 3        | 0.19%   |
| Accton Technology                 | 3        | 0.19%   |
| ZyDAS                             | 2        | 0.12%   |
| Microsoft                         | 2        | 0.12%   |
| D-Link                            | 2        | 0.12%   |
| ASIX Electronics                  | 2        | 0.12%   |
| TRENDnet                          | 1        | 0.06%   |
| Texas Instruments                 | 1        | 0.06%   |
| Sundance Technology Inc / IC Plus | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.06%   |
| ShenZhen ShanWan Technology       | 1        | 0.06%   |
| Seeed Technology                  | 1        | 0.06%   |
| Qualcomm                          | 1        | 0.06%   |
| QLogic                            | 1        | 0.06%   |
| NetGear                           | 1        | 0.06%   |
| Mercucys                          | 1        | 0.06%   |
| MediaTek                          | 1        | 0.06%   |
| JMicron Technology                | 1        | 0.06%   |
| HMD Global                        | 1        | 0.06%   |
| Hangzhou Silan Microelectronics   | 1        | 0.06%   |
| DisplayLink                       | 1        | 0.06%   |
| Arduino SA                        | 1        | 0.06%   |
| American Megatrends               | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 607      | 35.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 69       | 4.02%   |
| Qualcomm Atheros AR9271 802.11n                                               | 50       | 2.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 45       | 2.62%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 45       | 2.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 40       | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 34       | 1.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 29       | 1.69%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 29       | 1.69%   |
| Nvidia MCP61 Ethernet                                                         | 25       | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 23       | 1.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 23       | 1.34%   |
| Intel I211 Gigabit Network Connection                                         | 23       | 1.34%   |
| Intel Ethernet Connection I217-LM                                             | 23       | 1.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 21       | 1.22%   |
| Ralink MT7601U Wireless Adapter                                               | 19       | 1.11%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 15       | 0.87%   |
| Intel Ethernet Connection I217-V                                              | 13       | 0.76%   |
| Intel 82579V Gigabit Network Connection                                       | 13       | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 12       | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 12       | 0.7%    |
| Intel 82567LF-3 Gigabit Network Connection                                    | 12       | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 12       | 0.7%    |
| TP-Link TL-WN821N Version 5 RTL8192EU                                         | 10       | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 10       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 10       | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 9        | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 9        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 9        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 9        | 0.52%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express               | 9        | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 8        | 0.47%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 0.47%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 8        | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 7        | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 7        | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 7        | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 7        | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                                      | 7        | 0.41%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express               | 7        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                                | 6        | 0.35%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 6        | 0.35%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 6        | 0.35%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 6        | 0.35%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express                 | 6        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 5        | 0.29%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 5        | 0.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 5        | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 5        | 0.29%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 5        | 0.29%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 5        | 0.29%   |
| Intel Wireless 7260                                                           | 5        | 0.29%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 0.29%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 4        | 0.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 4        | 0.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 4        | 0.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4        | 0.23%   |
| Ralink RT2070 Wireless Adapter                                                | 4        | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 68       | 20%     |
| Qualcomm Atheros Communications | 57       | 16.76%  |
| Qualcomm Atheros                | 44       | 12.94%  |
| Intel                           | 43       | 12.65%  |
| Ralink Technology               | 41       | 12.06%  |
| TP-Link                         | 31       | 9.12%   |
| Ralink                          | 14       | 4.12%   |
| ASUSTek Computer                | 10       | 2.94%   |
| IMC Networks                    | 5        | 1.47%   |
| Belkin Components               | 5        | 1.47%   |
| Broadcom                        | 4        | 1.18%   |
| Edimax Technology               | 3        | 0.88%   |
| ZyDAS                           | 2        | 0.59%   |
| Microsoft                       | 2        | 0.59%   |
| D-Link System                   | 2        | 0.59%   |
| VIA Technologies                | 1        | 0.29%   |
| TRENDnet                        | 1        | 0.29%   |
| Texas Instruments               | 1        | 0.29%   |
| NetGear                         | 1        | 0.29%   |
| Mercucys                        | 1        | 0.29%   |
| Marvell Technology Group        | 1        | 0.29%   |
| D-Link                          | 1        | 0.29%   |
| Broadcom Limited                | 1        | 0.29%   |
| Accton Technology               | 1        | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                   | 50       | 14.58%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 23       | 6.71%   |
| Ralink MT7601U Wireless Adapter                                                   | 19       | 5.54%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                             | 10       | 2.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 10       | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 9        | 2.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 8        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 7        | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 7        | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 7        | 2.04%   |
| Ralink RT5370 Wireless Adapter                                                    | 6        | 1.75%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]     | 6        | 1.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                        | 6        | 1.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 5        | 1.46%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 5        | 1.46%   |
| Intel Wireless 7260                                                               | 5        | 1.46%   |
| Intel Wi-Fi 6 AX200                                                               | 5        | 1.46%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 4        | 1.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 4        | 1.17%   |
| Ralink RT2070 Wireless Adapter                                                    | 4        | 1.17%   |
| Ralink RT2561/RT61 802.11g PCI                                                    | 4        | 1.17%   |
| Intel Wireless-AC 9260                                                            | 4        | 1.17%   |
| Intel Wireless 3165                                                               | 4        | 1.17%   |
| Intel Wireless 3160                                                               | 4        | 1.17%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                              | 4        | 1.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 3        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 3        | 0.87%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                            | 3        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 3        | 0.87%   |
| Realtek 802.11ac NIC                                                              | 3        | 0.87%   |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 3        | 0.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 3        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 3        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                    | 3        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)           | 3        | 0.87%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]     | 3        | 0.87%   |
| Intel Wireless 7265                                                               | 3        | 0.87%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                | 3        | 0.87%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                         | 3        | 0.87%   |
| ZyDAS ZD1211B 802.11g                                                             | 2        | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 2        | 0.58%   |
| TP-Link Archer T4U ver.3                                                          | 2        | 0.58%   |
| Realtek RTL8187 Wireless Adapter                                                  | 2        | 0.58%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                 | 2        | 0.58%   |
| Ralink RT2500 Wireless 802.11bg                                                   | 2        | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 2        | 0.58%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                  | 2        | 0.58%   |
| Intel Wireless 8265 / 8275                                                        | 2        | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 2        | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 2        | 0.58%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]        | 2        | 0.58%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]            | 2        | 0.58%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                   | 2        | 0.58%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                               | 2        | 0.58%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                      | 1        | 0.29%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.29%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 0.29%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                         | 1        | 0.29%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.29%   |
| Texas Instruments ACX 111 54Mbps Wireless Interface                               | 1        | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 698      | 52.09%  |
| Intel                             | 328      | 24.48%  |
| Qualcomm Atheros                  | 112      | 8.36%   |
| Broadcom                          | 55       | 4.1%    |
| Broadcom Limited                  | 41       | 3.06%   |
| Nvidia                            | 37       | 2.76%   |
| Marvell Technology Group          | 23       | 1.72%   |
| VIA Technologies                  | 10       | 0.75%   |
| Xiaomi                            | 6        | 0.45%   |
| Samsung Electronics               | 6        | 0.45%   |
| Huawei Technologies               | 3        | 0.22%   |
| D-Link System                     | 3        | 0.22%   |
| Aquantia                          | 3        | 0.22%   |
| ASIX Electronics                  | 2        | 0.15%   |
| Accton Technology                 | 2        | 0.15%   |
| Sundance Technology Inc / IC Plus | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.07%   |
| Qualcomm                          | 1        | 0.07%   |
| QLogic                            | 1        | 0.07%   |
| MediaTek                          | 1        | 0.07%   |
| JMicron Technology                | 1        | 0.07%   |
| HMD Global                        | 1        | 0.07%   |
| Hangzhou Silan Microelectronics   | 1        | 0.07%   |
| DisplayLink                       | 1        | 0.07%   |
| D-Link                            | 1        | 0.07%   |
| American Megatrends               | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 607      | 44.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69       | 5.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 45       | 3.29%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 45       | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 40       | 2.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34       | 2.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 29       | 2.12%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 29       | 2.12%   |
| Nvidia MCP61 Ethernet                                             | 25       | 1.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 23       | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 23       | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 23       | 1.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 21       | 1.54%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 15       | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 13       | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12       | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 12       | 0.88%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 12       | 0.88%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12       | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 10       | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 0.66%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 9        | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.58%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 8        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7        | 0.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 7        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                          | 7        | 0.51%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 7        | 0.51%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 6        | 0.44%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 6        | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5        | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 5        | 0.37%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 5        | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4        | 0.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.29%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.29%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 4        | 0.29%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 4        | 0.29%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 4        | 0.29%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 4        | 0.29%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 3        | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.22%   |
| Nvidia MCP55 Ethernet                                             | 3        | 0.22%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 3        | 0.22%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 0.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.15%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.15%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.15%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.15%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.15%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.15%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.15%   |
| Intel PRO/100 VE Network Connection                               | 2        | 0.15%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1279     | 79.49%  |
| WiFi     | 325      | 20.2%   |
| Modem    | 4        | 0.25%   |
| Unknown  | 1        | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1165     | 82.1%   |
| WiFi     | 253      | 17.83%  |
| Unknown  | 1        | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1088     | 83.69%  |
| 2     | 179      | 13.77%  |
| 0     | 17       | 1.31%   |
| 3     | 13       | 1%      |
| 4     | 3        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1163     | 87.18%  |
| Yes  | 171      | 12.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 82       | 48.24%  |
| Intel                           | 42       | 24.71%  |
| Broadcom                        | 11       | 6.47%   |
| ASUSTek Computer                | 8        | 4.71%   |
| Conwise Technology              | 5        | 2.94%   |
| Integrated System Solution      | 4        | 2.35%   |
| Realtek Semiconductor           | 3        | 1.76%   |
| Belkin Components               | 3        | 1.76%   |
| Qualcomm Atheros Communications | 2        | 1.18%   |
| Logitech                        | 2        | 1.18%   |
| IMC Networks                    | 2        | 1.18%   |
| Hewlett-Packard                 | 2        | 1.18%   |
| Edimax Technology               | 2        | 1.18%   |
| TP-Link                         | 1        | 0.59%   |
| Lite-On Technology              | 1        | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 82       | 48.24%  |
| Intel Bluetooth wireless interface                      | 18       | 10.59%  |
| Intel Wireless-AC 3168 Bluetooth                        | 7        | 4.12%   |
| Intel AX200 Bluetooth                                   | 5        | 2.94%   |
| Conwise CW6622                                          | 5        | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 4        | 2.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4        | 2.35%   |
| Broadcom Bluetooth dongle                               | 3        | 1.76%   |
| ASUS Bluetooth Radio                                    | 3        | 1.76%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 2        | 1.18%   |
| Intel AX201 Bluetooth                                   | 2        | 1.18%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 2        | 1.18%   |
| Integrated System Solution Bluetooth Device             | 2        | 1.18%   |
| HP Bluetooth Adapter                                    | 2        | 1.18%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 1.18%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 2        | 1.18%   |
| Broadcom BCM2035 Bluetooth dongle                       | 2        | 1.18%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 1.18%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 1.18%   |
| TP-Link TP-TR- UB500 Adapter                           | 1        | 0.59%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.59%   |
| Realtek  Bluetooth 4.2 Adapter                          | 1        | 0.59%   |
| Realtek Bluetooth Radio                                 | 1        | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1        | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.59%   |
| Lite-On Bluetooth Device                                | 1        | 0.59%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1        | 0.59%   |
| Intel AX210 Bluetooth                                   | 1        | 0.59%   |
| IMC Networks Bluetooth Device                           | 1        | 0.59%   |
| IMC Networks BCM20702A0                                 | 1        | 0.59%   |
| Broadcom HP Portable Bumble Bee                         | 1        | 0.59%   |
| Broadcom Bluetooth 3.0 Device                           | 1        | 0.59%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter        | 1        | 0.59%   |
| Broadcom BCM2045 Bluetooth                              | 1        | 0.59%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter   | 1        | 0.59%   |
| Belkin Components F8T013 Bluetooth Adapter              | 1        | 0.59%   |
| Belkin Components Bluetooth Mini Dongle                 | 1        | 0.59%   |
| ASUS Bluetooth Adapter                                  | 1        | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 844      | 43.33%  |
| AMD                                  | 512      | 26.28%  |
| Nvidia                               | 415      | 21.3%   |
| C-Media Electronics                  | 65       | 3.34%   |
| Creative Labs                        | 28       | 1.44%   |
| Logitech                             | 10       | 0.51%   |
| Texas Instruments                    | 8        | 0.41%   |
| VIA Technologies                     | 7        | 0.36%   |
| JMTek                                | 7        | 0.36%   |
| Generalplus Technology               | 5        | 0.26%   |
| Creative Technology                  | 5        | 0.26%   |
| BEHRINGER International              | 5        | 0.26%   |
| ASUSTek Computer                     | 4        | 0.21%   |
| Kingston Technology                  | 3        | 0.15%   |
| GN Netcom                            | 2        | 0.1%    |
| Ensoniq                              | 2        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 1        | 0.05%   |
| Tenx Technology                      | 1        | 0.05%   |
| Syntek                               | 1        | 0.05%   |
| Superlux digit                       | 1        | 0.05%   |
| Sunplus Technology                   | 1        | 0.05%   |
| SteelSeries ApS                      | 1        | 0.05%   |
| SM950T Microphone                    | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]     | 1        | 0.05%   |
| Sennheiser Communications            | 1        | 0.05%   |
| Samson Technologies                  | 1        | 0.05%   |
| ROTEL                                | 1        | 0.05%   |
| Promethean Limited                   | 1        | 0.05%   |
| Plantronics                          | 1        | 0.05%   |
| Nektar                               | 1        | 0.05%   |
| MCS                                  | 1        | 0.05%   |
| KORG                                 | 1        | 0.05%   |
| JBL                                  | 1        | 0.05%   |
| Hewlett-Packard                      | 1        | 0.05%   |
| Focusrite-Novation                   | 1        | 0.05%   |
| Elite Silicon                        | 1        | 0.05%   |
| DigiTech                             | 1        | 0.05%   |
| D&M Holdings (Denon/Marantz)         | 1        | 0.05%   |
| Conexant Systems                     | 1        | 0.05%   |
| Barco Display Systems                | 1        | 0.05%   |
| Avance Logic                         | 1        | 0.05%   |
| ATI Technologies                     | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 150      | 6.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 127      | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 119      | 5.21%   |
| AMD FCH Azalia Controller                                                         | 114      | 4.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 110      | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 77       | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 77       | 3.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 67       | 2.93%   |
| AMD Trinity HDMI Audio Controller                                                 | 60       | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 58       | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 58       | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 54       | 2.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 52       | 2.28%   |
| Nvidia High Definition Audio Controller                                           | 49       | 2.15%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 48       | 2.1%    |
| Intel 200 Series PCH HD Audio                                                     | 47       | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 39       | 1.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 38       | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 37       | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 34       | 1.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 31       | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                     | 29       | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                                     | 28       | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 28       | 1.23%   |
| AMD Starship/Matisse HD Audio Controller                                          | 28       | 1.23%   |
| Nvidia MCP61 High Definition Audio                                                | 24       | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 24       | 1.05%   |
| AMD Family 17h/19h HD Audio Controller                                            | 22       | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                | 20       | 0.88%   |
| Nvidia GP108 High Definition Audio Controller                                     | 19       | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 19       | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 19       | 0.83%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 17       | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17       | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 17       | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                        | 16       | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 15       | 0.66%   |
| C-Media Electronics CM108 Audio Controller                                        | 15       | 0.66%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 14       | 0.61%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 14       | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 13       | 0.57%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 13       | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                                     | 12       | 0.53%   |
| AMD Kabini HDMI/DP Audio                                                          | 12       | 0.53%   |
| Nvidia GK106 HDMI Audio Controller                                                | 10       | 0.44%   |
| Nvidia GF116 High Definition Audio Controller                                     | 9        | 0.39%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 0.39%   |
| Nvidia TU116 High Definition Audio Controller                                     | 8        | 0.35%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 8        | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                                     | 8        | 0.35%   |
| Nvidia GK104 HDMI Audio Controller                                                | 8        | 0.35%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 8        | 0.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 8        | 0.35%   |
| Texas Instruments PCM2902 Audio Codec                                             | 7        | 0.31%   |
| Nvidia MCP51 High Definition Audio                                                | 7        | 0.31%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 7        | 0.31%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 7        | 0.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6        | 0.26%   |
| Nvidia GM204 High Definition Audio Controller                                     | 6        | 0.26%   |
| Nvidia GF104 High Definition Audio Controller                                     | 6        | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 363      | 28.63%  |
| Kingston                   | 281      | 22.16%  |
| SK Hynix                   | 127      | 10.02%  |
| Samsung Electronics        | 117      | 9.23%   |
| Micron Technology          | 68       | 5.36%   |
| Kingmax                    | 50       | 3.94%   |
| Corsair                    | 44       | 3.47%   |
| Nanya Technology           | 42       | 3.31%   |
| Crucial                    | 37       | 2.92%   |
| G.Skill                    | 35       | 2.76%   |
| Elpida                     | 18       | 1.42%   |
| CSX                        | 15       | 1.18%   |
| Ramaxel Technology         | 9        | 0.71%   |
| Team                       | 8        | 0.63%   |
| A-DATA Technology          | 6        | 0.47%   |
| Melco                      | 5        | 0.39%   |
| Transcend                  | 4        | 0.32%   |
| Patriot                    | 4        | 0.32%   |
| Qimonda                    | 3        | 0.24%   |
| OCZ                        | 3        | 0.24%   |
| Kingmax Semiconductor      | 3        | 0.24%   |
| GeIL                       | 3        | 0.24%   |
| Silicon Power              | 2        | 0.16%   |
| Intersil                   | 2        | 0.16%   |
| H                          | 2        | 0.16%   |
| Golden Empire              | 2        | 0.16%   |
| 48spaces                   | 2        | 0.16%   |
| Unknown (ABCD)             | 1        | 0.08%   |
| Unknown (7F7F7F7F7F970000) | 1        | 0.08%   |
| Unknown (09D5)             | 1        | 0.08%   |
| Unigen                     | 1        | 0.08%   |
| Toshiba                    | 1        | 0.08%   |
| Ramos Technology           | 1        | 0.08%   |
| Princeton                  | 1        | 0.08%   |
| Level One Communication    | 1        | 0.08%   |
| Hyundai lnc                | 1        | 0.08%   |
| GOODRAM                    | 1        | 0.08%   |
| Exceleram                  | 1        | 0.08%   |
| AMI                        | 1        | 0.08%   |
| Unknown                    | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s   | 41       | 2.8%    |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 32       | 2.18%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 32       | 2.18%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 19       | 1.3%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 19       | 1.3%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 17       | 1.16%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 16       | 1.09%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 16       | 1.09%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 16       | 1.09%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 15       | 1.02%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 15       | 1.02%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s | 15       | 1.02%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 11       | 0.75%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 11       | 0.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s              | 10       | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 10       | 0.68%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 10       | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s     | 10       | 0.68%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 10       | 0.68%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 8        | 0.55%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 7        | 0.48%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 7        | 0.48%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                   | 7        | 0.48%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 7        | 0.48%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 7        | 0.48%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 7        | 0.48%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s           | 7        | 0.48%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 7        | 0.48%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 7        | 0.48%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 7        | 0.48%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s   | 7        | 0.48%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 6        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 6        | 0.41%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 6        | 0.41%   |
| SK Hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s    | 6        | 0.41%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 6        | 0.41%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 6        | 0.41%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 6        | 0.41%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s     | 6        | 0.41%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s      | 6        | 0.41%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 1639MT/s  | 6        | 0.41%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 6        | 0.41%   |
| Nanya RAM M2Y2G64TU8HD5B-AC 2048MB DIMM DDR2 800MT/s     | 6        | 0.41%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 6        | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s              | 5        | 0.34%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s             | 5        | 0.34%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s              | 5        | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                  | 5        | 0.34%   |
| Unknown RAM Module 1024MB DIMM DDR2                      | 5        | 0.34%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1333MT/s            | 5        | 0.34%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s    | 5        | 0.34%   |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s      | 5        | 0.34%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s       | 5        | 0.34%   |
| Nanya RAM Module 2048MB DIMM DDR3 1333MT/s               | 5        | 0.34%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 5        | 0.34%   |
| Elpida RAM EBJ21UE8BDF0-DJ-F 2048MB DIMM DDR3 1333MT/s   | 5        | 0.34%   |
| Elpida RAM EBE10UE8ACWA-8G-E 1GB DIMM DDR2 800MT/s       | 5        | 0.34%   |
| CSX RAM V01D3LF4GB26826813 4GB DIMM DDR3 1333MT/s        | 5        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 4        | 0.27%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                   | 4        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 439      | 40.02%  |
| DDR4    | 190      | 17.32%  |
| DDR2    | 163      | 14.86%  |
| Unknown | 137      | 12.49%  |
| SDRAM   | 132      | 12.03%  |
| DDR     | 35       | 3.19%   |
| LPDDR4  | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1018     | 97.32%  |
| SODIMM  | 26       | 2.49%   |
| RIMM    | 1        | 0.1%    |
| FB-DIMM | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 389      | 31.76%  |
| 2048  | 375      | 30.61%  |
| 8192  | 218      | 17.8%   |
| 1024  | 163      | 13.31%  |
| 16384 | 38       | 3.1%    |
| 512   | 29       | 2.37%   |
| 32768 | 9        | 0.73%   |
| 256   | 4        | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 225      | 18.23%  |
| 1333    | 199      | 16.13%  |
| 800     | 152      | 12.32%  |
| 667     | 78       | 6.32%   |
| Unknown | 73       | 5.92%   |
| 1866    | 58       | 4.7%    |
| 2400    | 55       | 4.46%   |
| 2133    | 53       | 4.29%   |
| 3200    | 36       | 2.92%   |
| 1867    | 33       | 2.67%   |
| 400     | 25       | 2.03%   |
| 1066    | 24       | 1.94%   |
| 533     | 21       | 1.7%    |
| 3600    | 19       | 1.54%   |
| 2667    | 18       | 1.46%   |
| 3466    | 14       | 1.13%   |
| 1800    | 14       | 1.13%   |
| 2048    | 12       | 0.97%   |
| 3000    | 11       | 0.89%   |
| 1067    | 11       | 0.89%   |
| 3533    | 10       | 0.81%   |
| 2933    | 10       | 0.81%   |
| 2666    | 8        | 0.65%   |
| 1639    | 8        | 0.65%   |
| 49926   | 6        | 0.49%   |
| 3151    | 6        | 0.49%   |
| 2000    | 6        | 0.49%   |
| 3400    | 5        | 0.41%   |
| 1334    | 4        | 0.32%   |
| 333     | 4        | 0.32%   |
| 1400    | 3        | 0.24%   |
| 266     | 3        | 0.24%   |
| 3733    | 2        | 0.16%   |
| 3334    | 2        | 0.16%   |
| 3333    | 2        | 0.16%   |
| 3007    | 2        | 0.16%   |
| 2733    | 2        | 0.16%   |
| 2200    | 2        | 0.16%   |
| 2134    | 2        | 0.16%   |
| 1648    | 2        | 0.16%   |
| 66      | 2        | 0.16%   |
| 50410   | 1        | 0.08%   |
| 4199    | 1        | 0.08%   |
| 3467    | 1        | 0.08%   |
| 3066    | 1        | 0.08%   |
| 2800    | 1        | 0.08%   |
| 2747    | 1        | 0.08%   |
| 2465    | 1        | 0.08%   |
| 2448    | 1        | 0.08%   |
| 1904    | 1        | 0.08%   |
| 880     | 1        | 0.08%   |
| 200     | 1        | 0.08%   |
| 133     | 1        | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 40       | 47.06%  |
| Samsung Electronics   | 18       | 21.18%  |
| Canon                 | 12       | 14.12%  |
| Brother Industries    | 5        | 5.88%   |
| Seiko Epson           | 4        | 4.71%   |
| QinHeng Electronics   | 2        | 2.35%   |
| Xerox                 | 1        | 1.18%   |
| STMicroelectronics    | 1        | 1.18%   |
| Prolific Technology   | 1        | 1.18%   |
| Lexmark International | 1        | 1.18%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2600 series                                    | 8        | 9.3%    |
| Samsung M2020 Series                                      | 5        | 5.81%   |
| HP LaserJet 1020                                          | 4        | 4.65%   |
| Samsung ML-1640 Series Laser Printer                      | 3        | 3.49%   |
| Samsung SCX-3400 Series                                   | 2        | 2.33%   |
| Samsung ML-2010P Mono Laser Printer                       | 2        | 2.33%   |
| QinHeng CH340S                                            | 2        | 2.33%   |
| HP LaserJet P1005                                         | 2        | 2.33%   |
| HP LaserJet 1018                                          | 2        | 2.33%   |
| HP LaserJet 1010                                          | 2        | 2.33%   |
| HP LaserJet 1000                                          | 2        | 2.33%   |
| HP DeskJet F4100 Printer series                           | 2        | 2.33%   |
| HP Deskjet F2280 series                                   | 2        | 2.33%   |
| HP Deskjet 3520 series                                    | 2        | 2.33%   |
| HP DeskJet 2130 series                                    | 2        | 2.33%   |
| HP Deskjet 2050 J510                                      | 2        | 2.33%   |
| Canon TS5100 series                                       | 2        | 2.33%   |
| Canon LiDE 400                                            | 2        | 2.33%   |
| Brother HL-1110 series                                    | 2        | 2.33%   |
| Xerox WorkCentre 3119 Series                              | 1        | 1.16%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.16%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 1.16%   |
| Seiko Epson Printer                                       | 1        | 1.16%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 1.16%   |
| Seiko Epson L395 Series                                   | 1        | 1.16%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 1.16%   |
| Samsung SCX-4623 Series                                   | 1        | 1.16%   |
| Samsung ML-1660 Series                                    | 1        | 1.16%   |
| Samsung ML-1630 Series                                    | 1        | 1.16%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 1.16%   |
| Samsung C48x Series Color Laser Multifunction Printer     | 1        | 1.16%   |
| Prolific PL2305 Parallel Port                             | 1        | 1.16%   |
| Lexmark International InkJet Color Printer                | 1        | 1.16%   |
| HP LaserJet Pro M12a                                      | 1        | 1.16%   |
| HP LaserJet 1022                                          | 1        | 1.16%   |
| HP EWS UPD                                                | 1        | 1.16%   |
| HP DeskJet F2100 Printer series                           | 1        | 1.16%   |
| HP Deskjet D1500 series                                   | 1        | 1.16%   |
| HP DeskJet 959c                                           | 1        | 1.16%   |
| HP DeskJet 840c                                           | 1        | 1.16%   |
| HP DeskJet 5000 series                                    | 1        | 1.16%   |
| HP DeskJet 4530 series                                    | 1        | 1.16%   |
| HP Deskjet 1050 J410                                      | 1        | 1.16%   |
| Canon TS3100 series                                       | 1        | 1.16%   |
| Canon PIXMA MX360                                         | 1        | 1.16%   |
| Canon PIXMA MP280                                         | 1        | 1.16%   |
| Canon PIXMA MG3500 Series                                 | 1        | 1.16%   |
| Canon PIXMA MG2500 Series                                 | 1        | 1.16%   |
| Canon MG5700 series                                       | 1        | 1.16%   |
| Canon CanoScan LiDE 300                                   | 1        | 1.16%   |
| Canon BJC-2110 Color Printer                              | 1        | 1.16%   |
| Brother MFC-L2710DN series                                | 1        | 1.16%   |
| Brother HL-L2370DN series                                 | 1        | 1.16%   |
| Brother HL-L2300D series                                  | 1        | 1.16%   |
| Brother DCP-T510W                                         | 1        | 1.16%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 66.67%  |
| Hewlett-Packard | 3        | 20%     |
| UMAX            | 1        | 6.67%   |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 3        | 20%     |
| HP Scanjet 300                     | 2        | 13.33%  |
| Canon CanoScan LIDE 25             | 2        | 13.33%  |
| Canon CanoScan LiDE 110            | 2        | 13.33%  |
| UMAX Astra 4400/4450               | 1        | 6.67%   |
| Mustek Systems SNAPSCAN e22        | 1        | 6.67%   |
| HP ScanJet 3770                    | 1        | 6.67%   |
| Canon CanoScan N1240U/LiDE 30      | 1        | 6.67%   |
| Canon CanoScan LiDE 120            | 1        | 6.67%   |
| Canon CanoScan LiDE 100            | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 42       | 27.63%  |
| Microdia                    | 26       | 17.11%  |
| Microsoft                   | 11       | 7.24%   |
| KYE Systems (Mouse Systems) | 11       | 7.24%   |
| Z-Star Microelectronics     | 10       | 6.58%   |
| Trust                       | 5        | 3.29%   |
| Arkmicro Technologies       | 5        | 3.29%   |
| GEMBIRD                     | 4        | 2.63%   |
| Samsung Electronics         | 3        | 1.97%   |
| Pixart Imaging              | 3        | 1.97%   |
| LG Electronics              | 3        | 1.97%   |
| Cubeternet                  | 3        | 1.97%   |
| Creative Technology         | 3        | 1.97%   |
| Chicony Electronics         | 3        | 1.97%   |
| Aveo Technology             | 3        | 1.97%   |
| MacroSilicon                | 2        | 1.32%   |
| Jieli Technology            | 2        | 1.32%   |
| Hewlett-Packard             | 2        | 1.32%   |
| Apple                       | 2        | 1.32%   |
| Unknown                     | 1        | 0.66%   |
| Teslong Camera              | 1        | 0.66%   |
| Sonix Technology            | 1        | 0.66%   |
| Silicon Motion              | 1        | 0.66%   |
| Realtek Semiconductor       | 1        | 0.66%   |
| OmniVision Technologies     | 1        | 0.66%   |
| IMC Networks                | 1        | 0.66%   |
| Generalplus Technology      | 1        | 0.66%   |
| Alcor Micro                 | 1        | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 16       | 10.46%  |
| Microdia Camera                                       | 14       | 9.15%   |
| Logitech Webcam C600                                  | 7        | 4.58%   |
| Microdia Sonix USB 2.0 Camera                         | 6        | 3.92%   |
| Microsoft LifeCam HD-3000                             | 5        | 3.27%   |
| Arkmicro USB2.0 PC CAMERA                             | 5        | 3.27%   |
| Z-Star Vimicro USB Camera (Altair)                    | 4        | 2.61%   |
| Z-Star Venus USB2.0 Camera                            | 4        | 2.61%   |
| Logitech Webcam C170                                  | 4        | 2.61%   |
| Logitech HD Webcam C525                               | 4        | 2.61%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 4        | 2.61%   |
| Samsung Galaxy A5 (MTP)                               | 3        | 1.96%   |
| Microsoft LifeCam VX-2000                             | 3        | 1.96%   |
| Microdia USB 2.0 Camera                               | 3        | 1.96%   |
| Trust 17676 Webcam                                    | 2        | 1.31%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 2        | 1.31%   |
| Microsoft LifeCam Studio                              | 2        | 1.31%   |
| Microdia Defender G-Lens 2577 HD720p Camera           | 2        | 1.31%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]         | 2        | 1.31%   |
| Logitech QuickCam Pro 9000                            | 2        | 1.31%   |
| Logitech QuickCam Communicate Deluxe/S7500            | 2        | 1.31%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.31%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 2        | 1.31%   |
| KYE Systems (Mouse Systems) Genius WideCam F100       | 2        | 1.31%   |
| Jieli USB PHY 2.0                                     | 2        | 1.31%   |
| GEMBIRD USB2.0 PC CAMERA                              | 2        | 1.31%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 2        | 1.31%   |
| Cubeternet USB2.0 Camera                              | 2        | 1.31%   |
| Creative Live! Cam Chat HD [VF0700]                   | 2        | 1.31%   |
| Aveo USB2.0 Camera                                    | 2        | 1.31%   |
| Apple iPhone 5/5C/5S/6/SE                             | 2        | 1.31%   |
| Z-Star Saturn USB 2.0 Camera                          | 1        | 0.65%   |
| Z-Star A4 TECH HD PC Camera                           | 1        | 0.65%   |
| Unknown HD camera                                     | 1        | 0.65%   |
| Trust Webcam                                          | 1        | 0.65%   |
| Trust WB-8300X 2MP Webcam                             | 1        | 0.65%   |
| Trust Full HD Webcam                                  | 1        | 0.65%   |
| Teslong Camera Teslong Camera                         | 1        | 0.65%   |
| Sonix USB 2.0 Camera                                  | 1        | 0.65%   |
| Silicon Motion Silicon Motion SM371 Camera            | 1        | 0.65%   |
| Realtek FULL HD 1080P Webcam                          | 1        | 0.65%   |
| Pixart Imaging Webcam Genius iLook 300                | 1        | 0.65%   |
| OmniVision Monitor Webcam                             | 1        | 0.65%   |
| Microsoft LifeCam VX-800                              | 1        | 0.65%   |
| Microdia Webcam Vitade AF                             | 1        | 0.65%   |
| Logitech Webcam C310                                  | 1        | 0.65%   |
| Logitech Webcam C300                                  | 1        | 0.65%   |
| Logitech Webcam C250                                  | 1        | 0.65%   |
| Logitech Webcam C210                                  | 1        | 0.65%   |
| Logitech Webcam C200                                  | 1        | 0.65%   |
| Logitech QuickCam Communicate Deluxe                  | 1        | 0.65%   |
| Logitech Logitech Webcam C100                         | 1        | 0.65%   |
| Logitech BRIO Ultra HD Webcam                         | 1        | 0.65%   |
| LG Mouse Scanner LSM-150 [LG Smart Scan Mouse]        | 1        | 0.65%   |
| KYE Systems (Mouse Systems) iSlim 321R                | 1        | 0.65%   |
| KYE Systems (Mouse Systems) FaceCam 320X              | 1        | 0.65%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 1        | 0.65%   |
| IMC Networks USB 2.0 Camera                           | 1        | 0.65%   |
| HP Webcam HD 2300                                     | 1        | 0.65%   |
| HP Webcam 1300                                        | 1        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Gemalto (was Gemplus)     | 1        | 50%     |
| Aladdin Knowledge Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |
| Aladdin Knowledge Systems Token JC                | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1181     | 89%     |
| 1     | 134      | 10.1%   |
| 2     | 11       | 0.83%   |
| 3     | 1        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 94       | 61.44%  |
| Net/wireless             | 21       | 13.73%  |
| Communication controller | 10       | 6.54%   |
| Unassigned class         | 7        | 4.58%   |
| Multimedia controller    | 6        | 3.92%   |
| Camera                   | 4        | 2.61%   |
| Fingerprint reader       | 2        | 1.31%   |
| Card reader              | 2        | 1.31%   |
| Storage/raid             | 1        | 0.65%   |
| Storage                  | 1        | 0.65%   |
| Sound                    | 1        | 0.65%   |
| Net/ethernet             | 1        | 0.65%   |
| Dvb card                 | 1        | 0.65%   |
| Chipcard                 | 1        | 0.65%   |
| Bluetooth                | 1        | 0.65%   |

