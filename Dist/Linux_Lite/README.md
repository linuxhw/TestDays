Linux Lite - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Linux Lite.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Linux_Lite/Desktop/README.md) and [notebooks](/Dist/Linux_Lite/Notebook/README.md).

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

Total: 286

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-942B5BF58194151B        | All in one  | [60d8cda1ee](https://linux-hardware.org/?probe=60d8cda1ee) | Jan 02, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0bc7f79026](https://linux-hardware.org/?probe=0bc7f79026) | Dec 16, 2024 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [1193f44f20](https://linux-hardware.org/?probe=1193f44f20) | Dec 08, 2024 |
| Acer          | TravelMate 8372             | Notebook    | [fb1751719f](https://linux-hardware.org/?probe=fb1751719f) | Nov 30, 2024 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8b9610f096](https://linux-hardware.org/?probe=8b9610f096) | Nov 23, 2024 |
| ASUSTek       | 1008P                       | Notebook    | [6484520857](https://linux-hardware.org/?probe=6484520857) | Oct 31, 2024 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [3c2cfc5412](https://linux-hardware.org/?probe=3c2cfc5412) | Oct 28, 2024 |
| Google        | Droid                       | Notebook    | [4879fa61ce](https://linux-hardware.org/?probe=4879fa61ce) | Oct 23, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [61f9e31812](https://linux-hardware.org/?probe=61f9e31812) | Sep 30, 2024 |
| CSL-Comput... | C15 5500U                   | Notebook    | [98b09fe8bb](https://linux-hardware.org/?probe=98b09fe8bb) | Sep 30, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d7efba0bf](https://linux-hardware.org/?probe=6d7efba0bf) | Sep 29, 2024 |
| CSL-Comput... | C15 5500U                   | Notebook    | [008e0d5421](https://linux-hardware.org/?probe=008e0d5421) | Sep 16, 2024 |
| Dell          | Latitude 5400               | Notebook    | [ee7fe19f16](https://linux-hardware.org/?probe=ee7fe19f16) | Aug 26, 2024 |
| HP            | Notebook                    | Notebook    | [8330d22ee5](https://linux-hardware.org/?probe=8330d22ee5) | Aug 23, 2024 |
| ASRock        | 970A-G                      | Desktop     | [6d383b267d](https://linux-hardware.org/?probe=6d383b267d) | Aug 08, 2024 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [49665d68a3](https://linux-hardware.org/?probe=49665d68a3) | Aug 05, 2024 |
| Acer          | Aspire A315-53              | Notebook    | [c20748d891](https://linux-hardware.org/?probe=c20748d891) | Jul 29, 2024 |
| Acer          | ERC410M                     | Desktop     | [cdc03ce164](https://linux-hardware.org/?probe=cdc03ce164) | Jul 18, 2024 |
| HP            | 2B34                        | Desktop     | [9ee5932126](https://linux-hardware.org/?probe=9ee5932126) | Jul 13, 2024 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [4833f5a1a9](https://linux-hardware.org/?probe=4833f5a1a9) | Jul 12, 2024 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d707b04e42](https://linux-hardware.org/?probe=d707b04e42) | Jul 12, 2024 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [3ada57e9c6](https://linux-hardware.org/?probe=3ada57e9c6) | Jul 12, 2024 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cd1e4598f1](https://linux-hardware.org/?probe=cd1e4598f1) | Jul 05, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [81a22d43ad](https://linux-hardware.org/?probe=81a22d43ad) | Jun 09, 2024 |
| HP            | 18E7                        | Desktop     | [b1e0cff114](https://linux-hardware.org/?probe=b1e0cff114) | Jun 02, 2024 |
| Acer          | Aspire C22-963              | All in one  | [db7dfe3ac4](https://linux-hardware.org/?probe=db7dfe3ac4) | May 21, 2024 |
| Compal        | JHL90 REFERENCE             | Notebook    | [c477434d4e](https://linux-hardware.org/?probe=c477434d4e) | May 09, 2024 |
| ASUSTek       | M4A88T-I DELUXE             | Desktop     | [98c3cc204a](https://linux-hardware.org/?probe=98c3cc204a) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [99f91f2965](https://linux-hardware.org/?probe=99f91f2965) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [519d12ee29](https://linux-hardware.org/?probe=519d12ee29) | May 04, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| Dell          | Latitude D630               | Notebook    | [c9ae85eecc](https://linux-hardware.org/?probe=c9ae85eecc) | Apr 30, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Dell          | Latitude D630               | Notebook    | [f59eb192f4](https://linux-hardware.org/?probe=f59eb192f4) | Apr 03, 2024 |
| Google        | Celes                       | Notebook    | [996befe940](https://linux-hardware.org/?probe=996befe940) | Mar 13, 2024 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [37172a9059](https://linux-hardware.org/?probe=37172a9059) | Mar 02, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [df12996678](https://linux-hardware.org/?probe=df12996678) | Feb 25, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [eaca048668](https://linux-hardware.org/?probe=eaca048668) | Feb 24, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [9925fee177](https://linux-hardware.org/?probe=9925fee177) | Feb 23, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [b76bdbcd5d](https://linux-hardware.org/?probe=b76bdbcd5d) | Feb 18, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [4abd6b79ce](https://linux-hardware.org/?probe=4abd6b79ce) | Feb 17, 2024 |
| ASUSTek       | Berkeley                    | Desktop     | [0192b193c3](https://linux-hardware.org/?probe=0192b193c3) | Feb 14, 2024 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [7ee978c5e1](https://linux-hardware.org/?probe=7ee978c5e1) | Feb 08, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [becc9c140b](https://linux-hardware.org/?probe=becc9c140b) | Jan 21, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| ASRock        | J4125B-ITX                  | Desktop     | [663e605574](https://linux-hardware.org/?probe=663e605574) | Jan 17, 2024 |
| ASRock        | J4105M                      | Desktop     | [2e5352f371](https://linux-hardware.org/?probe=2e5352f371) | Jan 16, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [54e52154d1](https://linux-hardware.org/?probe=54e52154d1) | Dec 07, 2023 |
| HP            | 81BB                        | All in one  | [38a445e315](https://linux-hardware.org/?probe=38a445e315) | Dec 04, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4949cf710](https://linux-hardware.org/?probe=c4949cf710) | Nov 28, 2023 |
| Medion        | E3223                       | Convertible | [7fd5d80169](https://linux-hardware.org/?probe=7fd5d80169) | Nov 20, 2023 |
| HP            | 81BB                        | All in one  | [a79e0b8d25](https://linux-hardware.org/?probe=a79e0b8d25) | Nov 15, 2023 |
| ASRock        | J3455M                      | Desktop     | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| Sony          | VGN-SZ750N                  | Notebook    | [aa0a3e3559](https://linux-hardware.org/?probe=aa0a3e3559) | Nov 13, 2023 |
| HP            | 3646h                       | Desktop     | [1cfad160f4](https://linux-hardware.org/?probe=1cfad160f4) | Nov 12, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [75a2534386](https://linux-hardware.org/?probe=75a2534386) | Nov 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e7d16a3fc2](https://linux-hardware.org/?probe=e7d16a3fc2) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| Compaq(Int... | Michelangelo(LT1504)        | Notebook    | [678614e123](https://linux-hardware.org/?probe=678614e123) | Oct 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [97e8dc04f5](https://linux-hardware.org/?probe=97e8dc04f5) | Oct 13, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [12331db1c1](https://linux-hardware.org/?probe=12331db1c1) | Oct 03, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [5f99185bbb](https://linux-hardware.org/?probe=5f99185bbb) | Sep 17, 2023 |
| Toshiba       | Satellite P305              | Notebook    | [d5ac020866](https://linux-hardware.org/?probe=d5ac020866) | Sep 15, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [eaaac22962](https://linux-hardware.org/?probe=eaaac22962) | Sep 15, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
| Toshiba       | Satellite C850-C1S          | Notebook    | [ce5643add2](https://linux-hardware.org/?probe=ce5643add2) | Sep 09, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [26c288c533](https://linux-hardware.org/?probe=26c288c533) | Aug 30, 2023 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [d623d73283](https://linux-hardware.org/?probe=d623d73283) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [41ad8c7fc0](https://linux-hardware.org/?probe=41ad8c7fc0) | Jul 26, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [a2f77869ad](https://linux-hardware.org/?probe=a2f77869ad) | Jul 14, 2023 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [7416e91f77](https://linux-hardware.org/?probe=7416e91f77) | Jul 14, 2023 |
| Dell          | 0GN4PW A00                  | Desktop     | [8380b94e4f](https://linux-hardware.org/?probe=8380b94e4f) | Jul 06, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8a66b6d6b6](https://linux-hardware.org/?probe=8a66b6d6b6) | Jul 03, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | Notebook    | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | Notebook    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| American M... | IPPBT-RO                    | All in one  | [ea620e0681](https://linux-hardware.org/?probe=ea620e0681) | May 04, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| Lenovo        | Yoga C740 81TC              | Convertible | [087e19943f](https://linux-hardware.org/?probe=087e19943f) | Apr 11, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| HP            | 0AE4h C                     | Desktop     | [fe2502088a](https://linux-hardware.org/?probe=fe2502088a) | Mar 21, 2023 |
| HP            | 0AE4h C                     | Desktop     | [71bdbbb36f](https://linux-hardware.org/?probe=71bdbbb36f) | Mar 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [b42df5cbe0](https://linux-hardware.org/?probe=b42df5cbe0) | Mar 11, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [17a3030488](https://linux-hardware.org/?probe=17a3030488) | Mar 11, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [b9f775b14e](https://linux-hardware.org/?probe=b9f775b14e) | Feb 28, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [6def275f9b](https://linux-hardware.org/?probe=6def275f9b) | Feb 26, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| HP            | 240 G3                      | Notebook    | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | Notebook    | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b0289f0ef8](https://linux-hardware.org/?probe=b0289f0ef8) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Pegatron      | H36FF                       | Notebook    | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Braview       | BRW-BSWI-D2                 | Desktop     | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [9224597686](https://linux-hardware.org/?probe=9224597686) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MS-N014                     | Notebook    | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI           | MS-N014                     | Notebook    | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP            | Presario V6000 (RG289UA#... | Notebook    | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [1a999b09ae](https://linux-hardware.org/?probe=1a999b09ae) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| Samsung       | X420/X520                   | Notebook    | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu       | FMVNQ8P6                    | Notebook    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| Sony          | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Samsung       | 530XBB                      | Notebook    | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP            | 3047h                       | Desktop     | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell          | MXG061                      | Notebook    | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T400 6475E13       | Notebook    | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| HP            | 2820h                       | Desktop     | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | MXG071                      | Notebook    | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| ABIT          | IP35-E                      | Desktop     | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | Notebook    | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Gigabyte      | GA-E350N                    | Desktop     | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [64eba568a1](https://linux-hardware.org/?probe=64eba568a1) | Nov 25, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell          | MXG061                      | Notebook    | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Dell          | Vostro1710                  | Notebook    | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell          | Inspiron 5452               | Notebook    | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek       | X541SA                      | Notebook    | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP            | 0A98h                       | Desktop     | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| MSI           | Boston                      | Desktop     | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [b9140b8786](https://linux-hardware.org/?probe=b9140b8786) | Mar 29, 2021 |
| ASUSTek       | K54LY                       | Notebook    | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer          | Aspire V5-552               | Notebook    | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP            | Compaq 6735b                | Notebook    | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer          | Predator PH317-52           | Notebook    | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| HP            | 655                         | Notebook    | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP            | 655                         | Notebook    | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek       | 1001PX                      | Notebook    | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| HP            | 0ACCh                       | Desktop     | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | Desktop     | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | Desktop     | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo        | ThinkCentre A55 9265BL7     | Desktop     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP            | 2AA6 PVT                    | Desktop     | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| Dell          | Latitude D530               | Notebook    | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| MSI           | Z77A-G43                    | Desktop     | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [2a6ae45bc4](https://linux-hardware.org/?probe=2a6ae45bc4) | Aug 20, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway        | I61MG4                      | Desktop     | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway        | I61MG4                      | Desktop     | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [cf8c7c6ae6](https://linux-hardware.org/?probe=cf8c7c6ae6) | Jul 29, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google        | Chell                       | Notebook    | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo        | 3000 V200 0764A11           | Notebook    | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR            | ST Pro-KN                   | Notebook    | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| Acer          | EQ35M                       | Desktop     | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | Desktop     | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 6.6 | 30        | 14.35%  |
| Linux Lite 5.8 | 26        | 12.44%  |
| Linux Lite 6.4 | 23        | 11%     |
| Linux Lite 6.0 | 19        | 9.09%   |
| Linux Lite 5.4 | 19        | 9.09%   |
| Linux Lite 5.0 | 18        | 8.61%   |
| Linux Lite 5.2 | 17        | 8.13%   |
| Linux Lite 6.2 | 16        | 7.66%   |
| Linux Lite 5.6 | 16        | 7.66%   |
| Linux Lite 7.0 | 10        | 4.78%   |
| Linux Lite 3.8 | 6         | 2.87%   |
| Linux Lite 7.2 | 4         | 1.91%   |
| Linux Lite 4.8 | 2         | 0.96%   |
| Linux Lite 4.6 | 1         | 0.48%   |
| Linux Lite 4.4 | 1         | 0.48%   |
| Linux Lite 4.2 | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 205       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-69-generic | 9         | 4.09%   |
| 5.15.0-82-generic | 7         | 3.18%   |
| 5.4.0-42-generic  | 6         | 2.73%   |
| 5.15.0-91-generic | 6         | 2.73%   |
| 5.4.0-91-generic  | 5         | 2.27%   |
| 5.4.0-70-generic  | 5         | 2.27%   |
| 5.15.0-76-generic | 5         | 2.27%   |
| 5.4.0-96-generic  | 4         | 1.82%   |
| 5.4.0-52-generic  | 4         | 1.82%   |
| 5.4.0-40-generic  | 4         | 1.82%   |
| 5.4.0-109-generic | 4         | 1.82%   |
| 5.4.0-104-generic | 4         | 1.82%   |
| 5.15.0-88-generic | 4         | 1.82%   |
| 5.15.0-71-generic | 4         | 1.82%   |
| 5.15.0-33-generic | 4         | 1.82%   |
| 6.8.0-47-generic  | 3         | 1.36%   |
| 6.8.0-38-generic  | 3         | 1.36%   |
| 5.4.0-81-generic  | 3         | 1.36%   |
| 5.4.0-58-generic  | 3         | 1.36%   |
| 5.4.0-48-generic  | 3         | 1.36%   |
| 5.4.0-113-generic | 3         | 1.36%   |
| 5.4.0-107-generic | 3         | 1.36%   |
| 5.15.0-83-generic | 3         | 1.36%   |
| 5.15.0-75-generic | 3         | 1.36%   |
| 5.15.0-58-generic | 3         | 1.36%   |
| 5.15.0-52-generic | 3         | 1.36%   |
| 5.15.0-47-generic | 3         | 1.36%   |
| 5.15.0-46-generic | 3         | 1.36%   |
| 4.4.0-112-generic | 3         | 1.36%   |
| 6.8.0-39-generic  | 2         | 0.91%   |
| 5.4.0-90-generic  | 2         | 0.91%   |
| 5.4.0-88-generic  | 2         | 0.91%   |
| 5.4.0-80-generic  | 2         | 0.91%   |
| 5.4.0-74-generic  | 2         | 0.91%   |
| 5.4.0-54-generic  | 2         | 0.91%   |
| 5.4.0-33-generic  | 2         | 0.91%   |
| 5.4.0-110-generic | 2         | 0.91%   |
| 5.4.0-105-generic | 2         | 0.91%   |
| 5.15.0-97-generic | 2         | 0.91%   |
| 5.15.0-89-generic | 2         | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 88        | 41.9%   |
| 5.15.0  | 86        | 40.95%  |
| 6.8.0   | 14        | 6.67%   |
| 4.4.0   | 5         | 2.38%   |
| 4.15.0  | 5         | 2.38%   |
| 5.13.0  | 3         | 1.43%   |
| 6.0.0   | 2         | 0.95%   |
| 6.5.0   | 1         | 0.48%   |
| 6.1.0   | 1         | 0.48%   |
| 5.9.0   | 1         | 0.48%   |
| 5.19.0  | 1         | 0.48%   |
| 5.16.9  | 1         | 0.48%   |
| 5.16.0  | 1         | 0.48%   |
| 5.10.0  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 88        | 41.9%   |
| 5.15    | 86        | 40.95%  |
| 6.8     | 14        | 6.67%   |
| 4.4     | 5         | 2.38%   |
| 4.15    | 5         | 2.38%   |
| 5.13    | 3         | 1.43%   |
| 6.0     | 2         | 0.95%   |
| 5.16    | 2         | 0.95%   |
| 6.5     | 1         | 0.48%   |
| 6.1     | 1         | 0.48%   |
| 5.9     | 1         | 0.48%   |
| 5.19    | 1         | 0.48%   |
| 5.10    | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 200       | 97.56%  |
| i686   | 5         | 2.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 172       | 83.9%   |
| GNOME   | 29        | 14.15%  |
| Unknown | 2         | 0.98%   |
| Deepin  | 1         | 0.49%   |
| Budgie  | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 201       | 98.05%  |
| Tty     | 2         | 0.98%   |
| Wayland | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 144       | 69.57%  |
| Unknown | 33        | 15.94%  |
| TDM     | 28        | 13.53%  |
| GDM3    | 1         | 0.48%   |
| GDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 104       | 50.73%  |
| de_DE | 14        | 6.83%   |
| pt_BR | 10        | 4.88%   |
| en_GB | 10        | 4.88%   |
| pl_PL | 8         | 3.9%    |
| fr_FR | 8         | 3.9%    |
| es_ES | 6         | 2.93%   |
| it_IT | 5         | 2.44%   |
| es_MX | 5         | 2.44%   |
| en_CA | 5         | 2.44%   |
| ru_UA | 3         | 1.46%   |
| ru_RU | 3         | 1.46%   |
| pt_PT | 2         | 0.98%   |
| nl_NL | 2         | 0.98%   |
| en_IE | 2         | 0.98%   |
| zh_CN | 1         | 0.49%   |
| tr_TR | 1         | 0.49%   |
| id_ID | 1         | 0.49%   |
| hu_HU | 1         | 0.49%   |
| fr_CA | 1         | 0.49%   |
| es_CO | 1         | 0.49%   |
| es_CL | 1         | 0.49%   |
| es_AR | 1         | 0.49%   |
| en_SG | 1         | 0.49%   |
| en_PH | 1         | 0.49%   |
| en_NZ | 1         | 0.49%   |
| en_IN | 1         | 0.49%   |
| en_AU | 1         | 0.49%   |
| el_GR | 1         | 0.49%   |
| da_DK | 1         | 0.49%   |
| C     | 1         | 0.49%   |
| bg_BG | 1         | 0.49%   |
| ar_SA | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 114       | 55.34%  |
| EFI  | 92        | 44.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 173       | 84.39%  |
| Tmpfs   | 15        | 7.32%   |
| Overlay | 13        | 6.34%   |
| Btrfs   | 2         | 0.98%   |
| Zfs     | 1         | 0.49%   |
| Ext3    | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 109       | 53.17%  |
| Unknown | 50        | 24.39%  |
| MBR     | 46        | 22.44%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 83.5%   |
| Yes       | 34        | 16.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 72.46%  |
| Yes       | 57        | 27.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 34        | 16.59%  |
| ASUSTek Computer    | 28        | 13.66%  |
| Lenovo              | 27        | 13.17%  |
| Acer                | 18        | 8.78%   |
| Dell                | 14        | 6.83%   |
| Gigabyte Technology | 10        | 4.88%   |
| ASRock              | 9         | 4.39%   |
| Apple               | 8         | 3.9%    |
| MSI                 | 6         | 2.93%   |
| Toshiba             | 4         | 1.95%   |
| Samsung Electronics | 4         | 1.95%   |
| Fujitsu             | 4         | 1.95%   |
| Pegatron            | 3         | 1.46%   |
| Intel               | 3         | 1.46%   |
| Google              | 3         | 1.46%   |
| Sony                | 2         | 0.98%   |
| Minix               | 2         | 0.98%   |
| Medion              | 2         | 0.98%   |
| Inventec            | 2         | 0.98%   |
| Fujitsu Siemens     | 2         | 0.98%   |
| Foxconn             | 2         | 0.98%   |
| UNOWHY              | 1         | 0.49%   |
| UMAX                | 1         | 0.49%   |
| TR                  | 1         | 0.49%   |
| Thomson             | 1         | 0.49%   |
| Packard Bell        | 1         | 0.49%   |
| Jetway              | 1         | 0.49%   |
| Insignia            | 1         | 0.49%   |
| Gateway             | 1         | 0.49%   |
| EVGA                | 1         | 0.49%   |
| CSL-Computer        | 1         | 0.49%   |
| Compaq(Intel)       | 1         | 0.49%   |
| Compal              | 1         | 0.49%   |
| Braview             | 1         | 0.49%   |
| Biostar             | 1         | 0.49%   |
| AWOW                | 1         | 0.49%   |
| AMI                 | 1         | 0.49%   |
| American Megatrends | 1         | 0.49%   |
| ABIT                | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| MSI MS-7758                                 | 2         | 0.98%   |
| UNOWHY Y13G010S4EI                          | 1         | 0.49%   |
| UMAX VisionBook 12Wi 64G                    | 1         | 0.49%   |
| TR ST Pro-KN                                | 1         | 0.49%   |
| Toshiba Satellite T215D                     | 1         | 0.49%   |
| Toshiba Satellite P305                      | 1         | 0.49%   |
| Toshiba Satellite C850-C1S                  | 1         | 0.49%   |
| Toshiba QOSMIO X70-B                        | 1         | 0.49%   |
| Thomson PT-NEO14A.2WH32                     | 1         | 0.49%   |
| Sony VGN-SZ750N                             | 1         | 0.49%   |
| Sony VGC-JS54FB_W                           | 1         | 0.49%   |
| Samsung X420/X520                           | 1         | 0.49%   |
| Samsung NC110P/NC108P/NC111P                | 1         | 0.49%   |
| Samsung 905S3G/906S3G/915S3G/9305SG         | 1         | 0.49%   |
| Samsung 530XBB                              | 1         | 0.49%   |
| Pegatron H36FF                              | 1         | 0.49%   |
| Pegatron 520-1135la                         | 1         | 0.49%   |
| Pegatron 520-1030a                          | 1         | 0.49%   |
| Packard Bell ISTART D2314                   | 1         | 0.49%   |
| MSI MS-N014                                 | 1         | 0.49%   |
| MSI MS-7C95                                 | 1         | 0.49%   |
| MSI MS-7996                                 | 1         | 0.49%   |
| MSI FZ079AA-ABF a6625fr                     | 1         | 0.49%   |
| Minix Z83-4                                 | 1         | 0.49%   |
| Minix Z64                                   | 1         | 0.49%   |
| Medion E3223                                | 1         | 0.49%   |
| Medion Akoya E6418 MD99620                  | 1         | 0.49%   |
| Lenovo Yoga C740 81TC                       | 1         | 0.49%   |
| Lenovo V530S-07ICR 11BM0028MZ               | 1         | 0.49%   |
| Lenovo ThinkStation P320 30BH000BFR         | 1         | 0.49%   |
| Lenovo ThinkPad X240 20AMS1J100             | 1         | 0.49%   |
| Lenovo ThinkPad T430s 2356H83               | 1         | 0.49%   |
| Lenovo ThinkPad T400 6475E13                | 1         | 0.49%   |
| Lenovo ThinkPad L480 20LS001AMC             | 1         | 0.49%   |
| Lenovo ThinkPad A475 20KMS08300             | 1         | 0.49%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE00A7AX | 1         | 0.49%   |
| Lenovo ThinkCentre M91p 4524RS6             | 1         | 0.49%   |
| Lenovo ThinkCentre M91p 4518E2M             | 1         | 0.49%   |
| Lenovo ThinkCentre A55 9265BL7              | 1         | 0.49%   |
| Lenovo MIIX 300-10IBY 80NR                  | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 12        | 5.85%   |
| Lenovo IdeaPad          | 10        | 4.88%   |
| HP Compaq               | 9         | 4.39%   |
| Lenovo ThinkPad         | 5         | 2.44%   |
| HP Laptop               | 5         | 2.44%   |
| Dell Latitude           | 5         | 2.44%   |
| Dell Inspiron           | 5         | 2.44%   |
| Lenovo ThinkCentre      | 4         | 1.95%   |
| ASUS VivoBook           | 4         | 1.95%   |
| Toshiba Satellite       | 3         | 1.46%   |
| HP EliteBook            | 3         | 1.46%   |
| MSI MS-7758             | 2         | 0.98%   |
| Inventec Dell           | 2         | 0.98%   |
| HP Pavilion             | 2         | 0.98%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.98%   |
| Fujitsu LIFEBOOK        | 2         | 0.98%   |
| UNOWHY Y13G010S4EI      | 1         | 0.49%   |
| UMAX VisionBook         | 1         | 0.49%   |
| TR ST                   | 1         | 0.49%   |
| Toshiba QOSMIO          | 1         | 0.49%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.49%   |
| Sony VGN-SZ750N         | 1         | 0.49%   |
| Sony VGC-JS54FB         | 1         | 0.49%   |
| Samsung X420            | 1         | 0.49%   |
| Samsung NC110P          | 1         | 0.49%   |
| Samsung 905S3G          | 1         | 0.49%   |
| Samsung 530XBB          | 1         | 0.49%   |
| Pegatron H36FF          | 1         | 0.49%   |
| Pegatron 520-1135la     | 1         | 0.49%   |
| Pegatron 520-1030a      | 1         | 0.49%   |
| Packard Bell ISTART     | 1         | 0.49%   |
| MSI MS-N014             | 1         | 0.49%   |
| MSI MS-7C95             | 1         | 0.49%   |
| MSI MS-7996             | 1         | 0.49%   |
| MSI FZ079AA-ABF         | 1         | 0.49%   |
| Minix Z83-4             | 1         | 0.49%   |
| Minix Z64               | 1         | 0.49%   |
| Medion E3223            | 1         | 0.49%   |
| Medion Akoya            | 1         | 0.49%   |
| Lenovo Yoga             | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 19        | 9.27%   |
| 2010 | 19        | 9.27%   |
| 2008 | 19        | 9.27%   |
| 2011 | 17        | 8.29%   |
| 2012 | 16        | 7.8%    |
| 2007 | 15        | 7.32%   |
| 2020 | 14        | 6.83%   |
| 2015 | 12        | 5.85%   |
| 2014 | 12        | 5.85%   |
| 2017 | 10        | 4.88%   |
| 2016 | 10        | 4.88%   |
| 2013 | 9         | 4.39%   |
| 2022 | 6         | 2.93%   |
| 2021 | 6         | 2.93%   |
| 2019 | 6         | 2.93%   |
| 2009 | 6         | 2.93%   |
| 2023 | 3         | 1.46%   |
| 2006 | 2         | 0.98%   |
| 2005 | 2         | 0.98%   |
| 2024 | 1         | 0.49%   |
| 2004 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 115       | 56.1%   |
| Desktop     | 73        | 35.61%  |
| All in one  | 8         | 3.9%    |
| Mini pc     | 4         | 1.95%   |
| Convertible | 3         | 1.46%   |
| Tablet      | 2         | 0.98%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 193       | 94.15%  |
| Enabled  | 12        | 5.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 202       | 98.54%  |
| Yes  | 3         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 68        | 33.17%  |
| 4.01-8.0    | 45        | 21.95%  |
| 1.01-2.0    | 34        | 16.59%  |
| 8.01-16.0   | 22        | 10.73%  |
| 16.01-24.0  | 18        | 8.78%   |
| 32.01-64.0  | 7         | 3.41%   |
| 2.01-3.0    | 4         | 1.95%   |
| 0.51-1.0    | 4         | 1.95%   |
| 64.01-256.0 | 2         | 0.98%   |
| 24.01-32.0  | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 103       | 49.52%  |
| 2.01-3.0  | 45        | 21.63%  |
| 0.51-1.0  | 29        | 13.94%  |
| 3.01-4.0  | 15        | 7.21%   |
| 4.01-8.0  | 10        | 4.81%   |
| 8.01-16.0 | 3         | 1.44%   |
| 0.01-0.5  | 3         | 1.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 70.39%  |
| 2      | 48        | 23.3%   |
| 3      | 9         | 4.37%   |
| 5      | 2         | 0.97%   |
| 0      | 2         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 58.54%  |
| Yes       | 85        | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 86.83%  |
| No        | 27        | 13.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 79.51%  |
| No        | 42        | 20.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 54.37%  |
| No        | 94        | 45.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 38        | 18.54%  |
| Germany         | 17        | 8.29%   |
| Brazil          | 16        | 7.8%    |
| UK              | 13        | 6.34%   |
| France          | 11        | 5.37%   |
| Poland          | 8         | 3.9%    |
| Mexico          | 7         | 3.41%   |
| Italy           | 7         | 3.41%   |
| Canada          | 7         | 3.41%   |
| Romania         | 6         | 2.93%   |
| Ukraine         | 5         | 2.44%   |
| Spain           | 5         | 2.44%   |
| Russia          | 5         | 2.44%   |
| Netherlands     | 5         | 2.44%   |
| Turkey          | 3         | 1.46%   |
| Peru            | 3         | 1.46%   |
| Indonesia       | 3         | 1.46%   |
| Australia       | 3         | 1.46%   |
| Thailand        | 2         | 0.98%   |
| Switzerland     | 2         | 0.98%   |
| Portugal        | 2         | 0.98%   |
| Philippines     | 2         | 0.98%   |
| Ireland         | 2         | 0.98%   |
| India           | 2         | 0.98%   |
| Greece          | 2         | 0.98%   |
| Colombia        | 2         | 0.98%   |
| Chile           | 2         | 0.98%   |
| Argentina       | 2         | 0.98%   |
| Venezuela       | 1         | 0.49%   |
| Sweden          | 1         | 0.49%   |
| South Africa    | 1         | 0.49%   |
| Slovakia        | 1         | 0.49%   |
| Singapore       | 1         | 0.49%   |
| Serbia          | 1         | 0.49%   |
| Saudi Arabia    | 1         | 0.49%   |
| Qatar           | 1         | 0.49%   |
| Pakistan        | 1         | 0.49%   |
| North Macedonia | 1         | 0.49%   |
| New Zealand     | 1         | 0.49%   |
| Myanmar         | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Pabianice              | 3         | 1.43%   |
| Moscow                 | 3         | 1.43%   |
| Würzburg              | 2         | 0.95%   |
| Warsaw                 | 2         | 0.95%   |
| Valencia               | 2         | 0.95%   |
| Toronto                | 2         | 0.95%   |
| The Hague              | 2         | 0.95%   |
| Tamm                   | 2         | 0.95%   |
| Sydney                 | 2         | 0.95%   |
| Sao Paulo              | 2         | 0.95%   |
| Paris                  | 2         | 0.95%   |
| Ottawa                 | 2         | 0.95%   |
| Odessa                 | 2         | 0.95%   |
| Mexico City            | 2         | 0.95%   |
| Madrid                 | 2         | 0.95%   |
| Lublin                 | 2         | 0.95%   |
| Lima                   | 2         | 0.95%   |
| Kyiv                   | 2         | 0.95%   |
| Frankfurt am Main      | 2         | 0.95%   |
| Estacada               | 2         | 0.95%   |
| East Sussex            | 2         | 0.95%   |
| Dublin                 | 2         | 0.95%   |
| Delhi                  | 2         | 0.95%   |
| Bogotá                | 2         | 0.95%   |
| Berlin                 | 2         | 0.95%   |
| Bangkok                | 2         | 0.95%   |
| Żywiec                | 1         | 0.48%   |
| Zurich                 | 1         | 0.48%   |
| Yangon                 | 1         | 0.48%   |
| Winterthur             | 1         | 0.48%   |
| Wiesbaden              | 1         | 0.48%   |
| Wellington             | 1         | 0.48%   |
| Waterbury              | 1         | 0.48%   |
| Washington             | 1         | 0.48%   |
| Wahroonga              | 1         | 0.48%   |
| Voluntari              | 1         | 0.48%   |
| Virginia Beach         | 1         | 0.48%   |
| Vinnytsia              | 1         | 0.48%   |
| Villingen-Schwenningen | 1         | 0.48%   |
| Varennes-les-Narcy     | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 52     | 18.25%  |
| WDC                 | 37        | 48     | 14.68%  |
| Samsung Electronics | 26        | 29     | 10.32%  |
| Toshiba             | 18        | 20     | 7.14%   |
| Kingston            | 17        | 20     | 6.75%   |
| Unknown             | 15        | 20     | 5.95%   |
| Hitachi             | 11        | 12     | 4.37%   |
| SanDisk             | 9         | 9      | 3.57%   |
| Micron Technology   | 6         | 8      | 2.38%   |
| HGST                | 6         | 6      | 2.38%   |
| SK hynix            | 5         | 7      | 1.98%   |
| Crucial             | 5         | 5      | 1.98%   |
| China               | 5         | 5      | 1.98%   |
| Maxtor              | 4         | 8      | 1.59%   |
| Apple               | 4         | 4      | 1.59%   |
| Phison              | 3         | 3      | 1.19%   |
| GOODRAM             | 3         | 3      | 1.19%   |
| A-DATA Technology   | 3         | 3      | 1.19%   |
| MSI                 | 2         | 2      | 0.79%   |
| Intenso             | 2         | 2      | 0.79%   |
| Intel               | 2         | 2      | 0.79%   |
| Hewlett-Packard     | 2         | 2      | 0.79%   |
| Fujitsu             | 2         | 2      | 0.79%   |
| Team                | 1         | 1      | 0.4%    |
| SPCC                | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| Mass                | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| Lexar               | 1         | 1      | 0.4%    |
| KIOXIA              | 1         | 1      | 0.4%    |
| JMicron Technology  | 1         | 1      | 0.4%    |
| HS-SSD-E100         | 1         | 1      | 0.4%    |
| HPE                 | 1         | 1      | 0.4%    |
| Gigabyte Technology | 1         | 1      | 0.4%    |
| FORESEE             | 1         | 1      | 0.4%    |
| Fanxiang            | 1         | 2      | 0.4%    |
| Dogfish             | 1         | 1      | 0.4%    |
| ASUS-PHISON         | 1         | 2      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 2.24%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 2.24%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.49%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.12%   |
| Samsung SSD 860 EVO 500GB           | 3         | 1.12%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 1.12%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 0.75%   |
| WDC WD10JPVX-75JC3T0 1TB            | 2         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.75%   |
| Unknown DA4064  64GB                | 2         | 0.75%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.75%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.75%   |
| Toshiba DT01ACA100 1TB              | 2         | 0.75%   |
| Seagate ST9500325AS 500GB           | 2         | 0.75%   |
| Seagate ST9320325AS 320GB           | 2         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.75%   |
| Seagate ST3500418AS 500GB           | 2         | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.75%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.75%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.75%   |
| Samsung MZVLB256HAHQ-000L7 256GB    | 2         | 0.75%   |
| Samsung HM500JI 500GB               | 2         | 0.75%   |
| MSI S270 240GB                      | 2         | 0.75%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD | 2         | 0.75%   |
| Maxtor Z1 SSD 240GB                 | 2         | 0.75%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 0.75%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.75%   |
| Apple HDD HTS541010A9E632 1TB       | 2         | 0.75%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 0.37%   |
| WDC WDS250G2B0A 250GB SSD           | 1         | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1         | 0.37%   |
| WDC WD800JD-60LSA0 80GB             | 1         | 0.37%   |
| WDC WD800JD-00MSA1 80GB             | 1         | 0.37%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.37%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 0.37%   |
| WDC WD5000AAKX-003CA0 500GB         | 1         | 0.37%   |
| WDC WD5000AAKS-60WWPA0 500GB        | 1         | 0.37%   |
| WDC WD5000AADS-56S9B0 500GB         | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 50     | 36.97%  |
| WDC                 | 29        | 36     | 24.37%  |
| Toshiba             | 17        | 19     | 14.29%  |
| Hitachi             | 11        | 12     | 9.24%   |
| HGST                | 6         | 6      | 5.04%   |
| Samsung Electronics | 4         | 5      | 3.36%   |
| Maxtor              | 2         | 6      | 1.68%   |
| Fujitsu             | 2         | 2      | 1.68%   |
| Apple               | 2         | 2      | 1.68%   |
| Unknown             | 1         | 2      | 0.84%   |
| HPE                 | 1         | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 15     | 17.05%  |
| Kingston            | 14        | 16     | 15.91%  |
| SanDisk             | 7         | 7      | 7.95%   |
| WDC                 | 6         | 7      | 6.82%   |
| Crucial             | 5         | 5      | 5.68%   |
| China               | 5         | 5      | 5.68%   |
| Micron Technology   | 4         | 6      | 4.55%   |
| GOODRAM             | 3         | 3      | 3.41%   |
| A-DATA Technology   | 3         | 3      | 3.41%   |
| Phison              | 2         | 2      | 2.27%   |
| MSI                 | 2         | 2      | 2.27%   |
| Maxtor              | 2         | 2      | 2.27%   |
| Hewlett-Packard     | 2         | 2      | 2.27%   |
| Apple               | 2         | 2      | 2.27%   |
| Toshiba             | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| SK hynix            | 1         | 3      | 1.14%   |
| Seagate             | 1         | 1      | 1.14%   |
| PNY                 | 1         | 1      | 1.14%   |
| OCZ                 | 1         | 1      | 1.14%   |
| LITEON              | 1         | 1      | 1.14%   |
| Lexar               | 1         | 1      | 1.14%   |
| Intenso             | 1         | 1      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |
| Gigabyte Technology | 1         | 1      | 1.14%   |
| Fanxiang            | 1         | 2      | 1.14%   |
| Dogfish             | 1         | 1      | 1.14%   |
| ASUS-PHISON         | 1         | 2      | 1.14%   |
| ASMT                | 1         | 1      | 1.14%   |
| Apacer              | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 141    | 45.83%  |
| SSD     | 86        | 97     | 35.83%  |
| NVMe    | 22        | 29     | 9.17%   |
| MMC     | 17        | 21     | 7.08%   |
| Unknown | 5         | 5      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 172       | 232    | 77.83%  |
| NVMe | 22        | 29     | 9.95%   |
| MMC  | 17        | 21     | 7.69%   |
| SAS  | 10        | 11     | 4.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 176    | 70.62%  |
| 0.51-1.0   | 51        | 55     | 26.29%  |
| 1.01-2.0   | 4         | 5      | 2.06%   |
| 3.01-4.0   | 1         | 1      | 0.52%   |
| 2.01-3.0   | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 35.41%  |
| 251-500        | 44        | 21.05%  |
| 51-100         | 27        | 12.92%  |
| 501-1000       | 24        | 11.48%  |
| 1-20           | 14        | 6.7%    |
| 21-50          | 12        | 5.74%   |
| 1001-2000      | 7         | 3.35%   |
| More than 3000 | 6         | 2.87%   |
| 2001-3000      | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 93        | 44.08%  |
| 21-50     | 54        | 25.59%  |
| 101-250   | 23        | 10.9%   |
| 51-100    | 23        | 10.9%   |
| 251-500   | 8         | 3.79%   |
| 501-1000  | 4         | 1.9%    |
| 2001-3000 | 3         | 1.42%   |
| 1001-2000 | 3         | 1.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 2.63%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 2.63%   |
| WDC WD800JD-00MSA1 80GB                        | 1         | 1      | 2.63%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 2.63%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 2.63%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 2.63%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 2.63%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 2.63%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 2.63%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 2.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 2.63%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 2.63%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.63%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 2.63%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 2.63%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 2.63%   |
| Seagate ST3750528AS 752GB                      | 1         | 1      | 2.63%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 1      | 2.63%   |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 2.63%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 2.63%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 2.63%   |
| Maxtor 6Y250M0 256GB                           | 1         | 1      | 2.63%   |
| Maxtor 6V300F0 304GB                           | 1         | 3      | 2.63%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.63%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 2.63%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 2.63%   |
| Hitachi HDP725032GLA360 320GB                  | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 2.63%   |
| Apple SSD SM128C 121GB                         | 1         | 1      | 2.63%   |
| Apacer 16GB SATA Flash Drive SSD               | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 35.14%  |
| WDC                 | 7         | 7      | 18.92%  |
| Hitachi             | 5         | 5      | 13.51%  |
| Toshiba             | 4         | 4      | 10.81%  |
| SK hynix            | 1         | 1      | 2.7%    |
| SanDisk             | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 4      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 41.94%  |
| WDC                 | 6         | 6      | 19.35%  |
| Hitachi             | 5         | 5      | 16.13%  |
| Toshiba             | 4         | 4      | 12.9%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Maxtor              | 1         | 4      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 34     | 82.86%  |
| SSD  | 6         | 6      | 17.14%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intenso | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 100       | 128    | 45.66%  |
| Detected | 84        | 124    | 38.36%  |
| Malfunc  | 34        | 40     | 15.53%  |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 146       | 66.06%  |
| AMD                          | 36        | 16.29%  |
| Samsung Electronics          | 7         | 3.17%   |
| Nvidia                       | 7         | 3.17%   |
| SanDisk                      | 4         | 1.81%   |
| SK hynix                     | 3         | 1.36%   |
| Marvell Technology Group     | 3         | 1.36%   |
| Kingston Technology Company  | 3         | 1.36%   |
| Micron Technology            | 2         | 0.9%    |
| VIA Technologies             | 1         | 0.45%   |
| ULi Electronics              | 1         | 0.45%   |
| Silicon Image                | 1         | 0.45%   |
| Shenzhen Longsys Electronics | 1         | 0.45%   |
| Phison Electronics           | 1         | 0.45%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.45%   |
| LSI Logic / Symbios Logic    | 1         | 0.45%   |
| KIOXIA                       | 1         | 0.45%   |
| JMicron Technology           | 1         | 0.45%   |
| Broadcom / LSI               | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 8.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 4%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 2.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 2.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 1.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 5         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.45%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 4         | 1.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 4         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3         | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.09%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3         | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 0.73%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 0.73%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.73%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 149       | 62.34%  |
| IDE  | 56        | 23.43%  |
| NVMe | 22        | 9.21%   |
| RAID | 11        | 4.6%    |
| SCSI | 1         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 163       | 79.51%  |
| AMD    | 42        | 20.49%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 1.95%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 3         | 1.46%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 1.46%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 3         | 1.46%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.98%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 2         | 0.98%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.98%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.98%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.98%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 0.98%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.98%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 2         | 0.98%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.98%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.98%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 0.98%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.49%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.49%   |
| Intel Xeon CPU E5410 @ 2.33GHz                | 1         | 0.49%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 1         | 0.49%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz   | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.49%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.49%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.49%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.49%   |
| Intel Pentium D CPU 3.00GHz                   | 1         | 0.49%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.49%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.49%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.49%   |
| Intel Pentium CPU J2850 @ 2.41GHz             | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 17.56%  |
| Intel Celeron           | 25        | 12.2%   |
| Intel Core i3           | 19        | 9.27%   |
| Intel Core 2 Duo        | 19        | 9.27%   |
| Intel Core i7           | 11        | 5.37%   |
| Intel Atom              | 11        | 5.37%   |
| Other                   | 8         | 3.9%    |
| Intel Pentium           | 8         | 3.9%    |
| Intel Pentium Dual-Core | 6         | 2.93%   |
| AMD Ryzen 5             | 6         | 2.93%   |
| Intel Xeon              | 4         | 1.95%   |
| Intel Core 2            | 4         | 1.95%   |
| AMD Ryzen 3             | 4         | 1.95%   |
| AMD FX                  | 3         | 1.46%   |
| AMD E2                  | 3         | 1.46%   |
| AMD A8                  | 3         | 1.46%   |
| AMD A6                  | 3         | 1.46%   |
| Intel Pentium Silver    | 2         | 0.98%   |
| Intel Pentium Dual      | 2         | 0.98%   |
| Intel Pentium D         | 2         | 0.98%   |
| Intel Genuine           | 2         | 0.98%   |
| Intel Core 2 Quad       | 2         | 0.98%   |
| AMD Turion 64 X2 Mobile | 2         | 0.98%   |
| AMD E                   | 2         | 0.98%   |
| AMD Athlon II X2        | 2         | 0.98%   |
| Intel Core m7           | 1         | 0.49%   |
| Intel Core 2 Extreme    | 1         | 0.49%   |
| Intel Celeron M         | 1         | 0.49%   |
| Intel Celeron Dual-Core | 1         | 0.49%   |
| AMD Turion Dual-Core    | 1         | 0.49%   |
| AMD Sempron             | 1         | 0.49%   |
| AMD Ryzen 9             | 1         | 0.49%   |
| AMD Quad-Core           | 1         | 0.49%   |
| AMD Phenom II X4        | 1         | 0.49%   |
| AMD Phenom II X2        | 1         | 0.49%   |
| AMD GX                  | 1         | 0.49%   |
| AMD E1                  | 1         | 0.49%   |
| AMD Athlon II Neo       | 1         | 0.49%   |
| AMD Athlon 64 X2        | 1         | 0.49%   |
| AMD A12                 | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 116       | 56.59%  |
| 4      | 65        | 31.71%  |
| 6      | 10        | 4.88%   |
| 1      | 8         | 3.9%    |
| 12     | 2         | 0.98%   |
| 14     | 1         | 0.49%   |
| 10     | 1         | 0.49%   |
| 8      | 1         | 0.49%   |
| 3      | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 99.02%  |
| 2      | 2         | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 122       | 59.51%  |
| 2      | 83        | 40.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 99.02%  |
| 32-bit         | 2         | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 22.01%  |
| 0x206a7    | 16        | 7.66%   |
| 0x1067a    | 16        | 7.66%   |
| 0x30678    | 9         | 4.31%   |
| 0x306a9    | 7         | 3.35%   |
| 0x706a1    | 5         | 2.39%   |
| 0x6fd      | 5         | 2.39%   |
| 0x406c4    | 5         | 2.39%   |
| 0x40651    | 5         | 2.39%   |
| 0x20655    | 5         | 2.39%   |
| 0x6fb      | 4         | 1.91%   |
| 0x506c9    | 4         | 1.91%   |
| 0x306c3    | 4         | 1.91%   |
| 0x10676    | 4         | 1.91%   |
| 0x010000c8 | 4         | 1.91%   |
| 0x806ec    | 3         | 1.44%   |
| 0x6f6      | 3         | 1.44%   |
| 0x06006705 | 3         | 1.44%   |
| 0x906e9    | 2         | 0.96%   |
| 0x906c0    | 2         | 0.96%   |
| 0x806ea    | 2         | 0.96%   |
| 0x806e9    | 2         | 0.96%   |
| 0x806c1    | 2         | 0.96%   |
| 0x706a8    | 2         | 0.96%   |
| 0x506e3    | 2         | 0.96%   |
| 0x406e3    | 2         | 0.96%   |
| 0x406c3    | 2         | 0.96%   |
| 0x206c2    | 2         | 0.96%   |
| 0x106ca    | 2         | 0.96%   |
| 0x07030105 | 2         | 0.96%   |
| 0x06000852 | 2         | 0.96%   |
| 0x05000119 | 2         | 0.96%   |
| 0xf64      | 1         | 0.48%   |
| 0xf44      | 1         | 0.48%   |
| 0xa0653    | 1         | 0.48%   |
| 0x906eb    | 1         | 0.48%   |
| 0x906ea    | 1         | 0.48%   |
| 0x906a4    | 1         | 0.48%   |
| 0x906a3    | 1         | 0.48%   |
| 0x90672    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 25        | 12.2%   |
| Silvermont       | 21        | 10.24%  |
| SandyBridge      | 16        | 7.8%    |
| Core             | 16        | 7.8%    |
| KabyLake         | 15        | 7.32%   |
| Haswell          | 11        | 5.37%   |
| Westmere         | 9         | 4.39%   |
| IvyBridge        | 9         | 4.39%   |
| Goldmont plus    | 9         | 4.39%   |
| Skylake          | 7         | 3.41%   |
| K10              | 6         | 2.93%   |
| Excavator        | 6         | 2.93%   |
| Puma             | 5         | 2.44%   |
| Zen              | 4         | 1.95%   |
| Piledriver       | 4         | 1.95%   |
| Goldmont         | 4         | 1.95%   |
| Bonnell          | 4         | 1.95%   |
| K8 Hammer        | 3         | 1.46%   |
| Bobcat           | 3         | 1.46%   |
| Alderlake Hybrid | 3         | 1.46%   |
| Unknown          | 3         | 1.46%   |
| Zen+             | 2         | 0.98%   |
| Zen 3            | 2         | 0.98%   |
| Tremont          | 2         | 0.98%   |
| TigerLake        | 2         | 0.98%   |
| P6               | 2         | 0.98%   |
| NetBurst         | 2         | 0.98%   |
| K10 Llano        | 2         | 0.98%   |
| CometLake        | 2         | 0.98%   |
| Zen 2            | 1         | 0.49%   |
| Nehalem          | 1         | 0.49%   |
| K8 & K10 hybrid  | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| IceLake          | 1         | 0.49%   |
| Broadwell        | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 124       | 56.11%  |
| AMD    | 50        | 22.62%  |
| Nvidia | 47        | 21.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 4.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 3.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 2.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 2.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.59%   |
| Intel HD Graphics 500                                                                    | 4         | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.29%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.29%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.86%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.86%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.86%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.86%   |
| Intel HD Graphics 630                                                                    | 2         | 0.86%   |
| Intel HD Graphics 620                                                                    | 2         | 0.86%   |
| Intel HD Graphics 530                                                                    | 2         | 0.86%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.86%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.86%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.86%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.86%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.86%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 2         | 0.86%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 106       | 51.71%  |
| 1 x AMD        | 45        | 21.95%  |
| 1 x Nvidia     | 33        | 16.1%   |
| Intel + Nvidia | 14        | 6.83%   |
| 2 x AMD        | 4         | 1.95%   |
| Other          | 1         | 0.49%   |
| 2 x Intel      | 1         | 0.49%   |
| Intel + AMD    | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 178       | 86.41%  |
| Proprietary | 23        | 11.17%  |
| Unknown     | 5         | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 63.46%  |
| 0.01-0.5   | 39        | 18.75%  |
| 1.01-2.0   | 14        | 6.73%   |
| 0.51-1.0   | 13        | 6.25%   |
| 3.01-4.0   | 6         | 2.88%   |
| 5.01-6.0   | 3         | 1.44%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 13.59%  |
| AU Optronics            | 20        | 9.71%   |
| BOE                     | 19        | 9.22%   |
| Chimei Innolux          | 17        | 8.25%   |
| LG Display              | 14        | 6.8%    |
| Hewlett-Packard         | 14        | 6.8%    |
| Goldstar                | 11        | 5.34%   |
| Chi Mei Optoelectronics | 9         | 4.37%   |
| Acer                    | 9         | 4.37%   |
| Apple                   | 6         | 2.91%   |
| Ancor Communications    | 6         | 2.91%   |
| Sony                    | 5         | 2.43%   |
| Dell                    | 4         | 1.94%   |
| CPT                     | 4         | 1.94%   |
| ViewSonic               | 3         | 1.46%   |
| NEC Computers           | 3         | 1.46%   |
| LG Philips              | 3         | 1.46%   |
| Lenovo                  | 3         | 1.46%   |
| Vestel Elektronik       | 2         | 0.97%   |
| Philips                 | 2         | 0.97%   |
| PANDA                   | 2         | 0.97%   |
| InfoVision              | 2         | 0.97%   |
| HannStar                | 2         | 0.97%   |
| AOC                     | 2         | 0.97%   |
| Unknown                 | 2         | 0.97%   |
| TSL                     | 1         | 0.49%   |
| Toshiba                 | 1         | 0.49%   |
| TCL                     | 1         | 0.49%   |
| Sharp                   | 1         | 0.49%   |
| Seiko/Epson             | 1         | 0.49%   |
| SANYO                   | 1         | 0.49%   |
| OEM                     | 1         | 0.49%   |
| NCS                     | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| Hitachi                 | 1         | 0.49%   |
| eMachines               | 1         | 0.49%   |
| cPATH                   | 1         | 0.49%   |
| BenQ                    | 1         | 0.49%   |
| Belinea                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.42%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 3         | 1.42%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 2         | 0.94%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 0.94%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 0.94%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.94%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 2         | 0.94%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.94%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                      | 2         | 0.94%   |
| Acer X193HQ ACR0069 1366x768 410x230mm 18.5-inch                      | 2         | 0.94%   |
| Unknown                                                               | 2         | 0.94%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.47%   |
| ViewSonic VA2026w VSC5020 1680x1050 433x271mm 20.1-inch               | 1         | 0.47%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.47%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.47%   |
| TSL 24MT600BF TSL0758 1920x1080 530x299mm 24.0-inch                   | 1         | 0.47%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.47%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.47%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.47%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.47%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                         | 1         | 0.47%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                         | 1         | 0.47%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1         | 0.47%   |
| Sharp HDMI SHP4192 1920x1080 708x398mm 32.0-inch                      | 1         | 0.47%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.47%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 520x320mm 24.0-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.47%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch     | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.47%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1         | 0.47%   |
| Samsung Electronics S24C31x SAM7311 1920x1080 527x296mm 23.8-inch     | 1         | 0.47%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.47%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch      | 1         | 0.47%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 630x360mm 28.6-inch     | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 67        | 32.52%  |
| 1366x768 (WXGA)    | 62        | 30.1%   |
| 3840x2160 (4K)     | 12        | 5.83%   |
| 1920x1200 (WUXGA)  | 12        | 5.83%   |
| 1280x800 (WXGA)    | 12        | 5.83%   |
| 1680x1050 (WSXGA+) | 8         | 3.88%   |
| 1280x1024 (SXGA)   | 7         | 3.4%    |
| 1600x900 (HD+)     | 6         | 2.91%   |
| 1440x900 (WXGA+)   | 5         | 2.43%   |
| 1360x768           | 3         | 1.46%   |
| 1024x600           | 3         | 1.46%   |
| 2560x1440 (QHD)    | 2         | 0.97%   |
| Unknown            | 2         | 0.97%   |
| 5280x1080          | 1         | 0.49%   |
| 3840x2400          | 1         | 0.49%   |
| 1920x540           | 1         | 0.49%   |
| 1280x720 (HD)      | 1         | 0.49%   |
| 1024x768 (XGA)     | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 21.26%  |
| 13      | 19        | 9.18%   |
| 24      | 17        | 8.21%   |
| 14      | 17        | 8.21%   |
| 17      | 16        | 7.73%   |
| 23      | 13        | 6.28%   |
| Unknown | 10        | 4.83%   |
| 21      | 9         | 4.35%   |
| 11      | 7         | 3.38%   |
| 27      | 6         | 2.9%    |
| 18      | 6         | 2.9%    |
| 12      | 6         | 2.9%    |
| 20      | 5         | 2.42%   |
| 19      | 5         | 2.42%   |
| 31      | 4         | 1.93%   |
| 22      | 4         | 1.93%   |
| 10      | 4         | 1.93%   |
| 16      | 3         | 1.45%   |
| 84      | 2         | 0.97%   |
| 72      | 2         | 0.97%   |
| 46      | 2         | 0.97%   |
| 32      | 2         | 0.97%   |
| 65      | 1         | 0.48%   |
| 60      | 1         | 0.48%   |
| 28      | 1         | 0.48%   |
| 26      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 80        | 38.83%  |
| 501-600     | 34        | 16.5%   |
| 401-500     | 29        | 14.08%  |
| 201-300     | 23        | 11.17%  |
| 351-400     | 14        | 6.8%    |
| Unknown     | 10        | 4.85%   |
| 601-700     | 6         | 2.91%   |
| 1501-2000   | 4         | 1.94%   |
| 1001-1500   | 4         | 1.94%   |
| 701-800     | 2         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 145       | 73.6%   |
| 16/10   | 34        | 17.26%  |
| 5/4     | 7         | 3.55%   |
| Unknown | 7         | 3.55%   |
| 4/3     | 2         | 1.02%   |
| 6/5     | 1         | 0.51%   |
| 3/2     | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 21.26%  |
| 201-250        | 33        | 15.94%  |
| 81-90          | 30        | 14.49%  |
| 151-200        | 16        | 7.73%   |
| 141-150        | 10        | 4.83%   |
| Unknown        | 10        | 4.83%   |
| 71-80          | 7         | 3.38%   |
| 51-60          | 7         | 3.38%   |
| 351-500        | 7         | 3.38%   |
| 301-350        | 7         | 3.38%   |
| 121-130        | 7         | 3.38%   |
| More than 1000 | 6         | 2.9%    |
| 131-140        | 6         | 2.9%    |
| 61-70          | 5         | 2.42%   |
| 251-300        | 5         | 2.42%   |
| 41-50          | 4         | 1.93%   |
| 501-1000       | 2         | 0.97%   |
| 111-120        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 72        | 36%     |
| 101-120       | 61        | 30.5%   |
| 121-160       | 43        | 21.5%   |
| Unknown       | 10        | 5%      |
| 161-240       | 7         | 3.5%    |
| 1-50          | 5         | 2.5%    |
| More than 240 | 2         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 183       | 88.83%  |
| 2     | 19        | 9.22%   |
| 0     | 3         | 1.46%   |
| 3     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 112       | 36.01%  |
| Intel                                 | 68        | 21.86%  |
| Qualcomm Atheros                      | 46        | 14.79%  |
| Broadcom                              | 24        | 7.72%   |
| Broadcom Limited                      | 7         | 2.25%   |
| Ralink                                | 6         | 1.93%   |
| Ralink Technology                     | 5         | 1.61%   |
| Nvidia                                | 5         | 1.61%   |
| Marvell Technology Group              | 5         | 1.61%   |
| TP-Link                               | 4         | 1.29%   |
| Sierra Wireless                       | 3         | 0.96%   |
| MediaTek                              | 3         | 0.96%   |
| ASUSTek Computer                      | 3         | 0.96%   |
| Qualcomm Atheros Communications       | 2         | 0.64%   |
| ASIX Electronics                      | 2         | 0.64%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.32%   |
| Xiaomi                                | 1         | 0.32%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.32%   |
| Sitecom Europe                        | 1         | 0.32%   |
| Samsung Electronics                   | 1         | 0.32%   |
| OPPO Electronics                      | 1         | 0.32%   |
| Microsoft                             | 1         | 0.32%   |
| Linksys                               | 1         | 0.32%   |
| JMicron Technology                    | 1         | 0.32%   |
| Gemtek                                | 1         | 0.32%   |
| Ericsson Business Mobile Networks     | 1         | 0.32%   |
| Dell                                  | 1         | 0.32%   |
| D-Link                                | 1         | 0.32%   |
| Belkin Components                     | 1         | 0.32%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.32%   |
| 3Com                                  | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 77        | 20.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 22        | 5.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 10        | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 9         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 9         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 8         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 1.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 1.63%   |
| Intel Wireless 3165                                                                           | 5         | 1.36%   |
| Realtek 802.11ac NIC                                                                          | 4         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 4         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 0.81%   |
| Intel Wireless 7260                                                                           | 3         | 0.81%   |
| Intel Wireless 3160                                                                           | 3         | 0.81%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 0.54%   |
| Sierra Wireless EM7305 Modem                                                                  | 2         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.54%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 2         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 2         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 0.54%   |
| Nvidia MCP77 Ethernet                                                                         | 2         | 0.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2         | 0.54%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.54%   |
| Intel Wireless 7265                                                                           | 2         | 0.54%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 0.54%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 49        | 27.84%  |
| Qualcomm Atheros                      | 41        | 23.3%   |
| Realtek Semiconductor                 | 38        | 21.59%  |
| Broadcom                              | 10        | 5.68%   |
| Ralink                                | 6         | 3.41%   |
| Ralink Technology                     | 5         | 2.84%   |
| Broadcom Limited                      | 5         | 2.84%   |
| TP-Link                               | 4         | 2.27%   |
| Sierra Wireless                       | 3         | 1.7%    |
| ASUSTek Computer                      | 3         | 1.7%    |
| Qualcomm Atheros Communications       | 2         | 1.14%   |
| MediaTek                              | 2         | 1.14%   |
| Sitecom Europe                        | 1         | 0.57%   |
| Microsoft                             | 1         | 0.57%   |
| Linksys                               | 1         | 0.57%   |
| Gemtek                                | 1         | 0.57%   |
| Dell                                  | 1         | 0.57%   |
| D-Link                                | 1         | 0.57%   |
| Belkin Components                     | 1         | 0.57%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 10        | 5.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 9         | 5.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 9         | 5.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 5.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 6         | 3.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 3.39%   |
| Intel Wireless 3165                                                                           | 5         | 2.82%   |
| Realtek 802.11ac NIC                                                                          | 4         | 2.26%   |
| Ralink MT7601U Wireless Adapter                                                               | 4         | 2.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4         | 2.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 2.26%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 4         | 2.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3         | 1.69%   |
| Intel Wireless 7260                                                                           | 3         | 1.69%   |
| Intel Wireless 3160                                                                           | 3         | 1.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 1.13%   |
| Sierra Wireless EM7305 Modem                                                                  | 2         | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 1.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 1.13%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 1.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2         | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 1.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2         | 1.13%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.13%   |
| Intel Wireless 7265                                                                           | 2         | 1.13%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 2         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 2         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 2         | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.56%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1         | 0.56%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1         | 0.56%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 103       | 55.38%  |
| Intel                             | 33        | 17.74%  |
| Broadcom                          | 16        | 8.6%    |
| Qualcomm Atheros                  | 12        | 6.45%   |
| Nvidia                            | 5         | 2.69%   |
| Marvell Technology Group          | 5         | 2.69%   |
| Broadcom Limited                  | 2         | 1.08%   |
| ASIX Electronics                  | 2         | 1.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.54%   |
| Xiaomi                            | 1         | 0.54%   |
| Sundance Technology Inc / IC Plus | 1         | 0.54%   |
| Samsung Electronics               | 1         | 0.54%   |
| OPPO Electronics                  | 1         | 0.54%   |
| MediaTek                          | 1         | 0.54%   |
| JMicron Technology                | 1         | 0.54%   |
| 3Com                              | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 77        | 40.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 22        | 11.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 8         | 4.21%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 3         | 1.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2         | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 1.05%   |
| Nvidia MCP77 Ethernet                                                      | 2         | 1.05%   |
| Intel Ethernet Connection I218-LM                                          | 2         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                                   | 2         | 1.05%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                          | 2         | 1.05%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 1.05%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                     | 2         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2         | 1.05%   |
| ZTE WCDMA MSM Unisoc Phone                                                 | 1         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1         | 0.53%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.53%   |
| Realtek USB 10/100 LAN                                                     | 1         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                          | 1         | 0.53%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.53%   |
| Realtek Killer E2600 GbE Controller                                        | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.53%   |
| OPPO OnePlus Nord 4                                                        | 1         | 0.53%   |
| Nvidia MCP61 Ethernet                                                      | 1         | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                           | 1         | 0.53%   |
| Nvidia CK804 Ethernet Controller                                           | 1         | 0.53%   |
| MediaTek Infinix SMART 5                                                   | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                    | 1         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 1         | 0.53%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                      | 1         | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 178       | 51.9%   |
| WiFi     | 163       | 47.52%  |
| Modem    | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 62.62%  |
| Ethernet | 80        | 37.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 120       | 58.54%  |
| 1     | 77        | 37.56%  |
| 0     | 4         | 1.95%   |
| 3     | 3         | 1.46%   |
| 4     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 153       | 74.27%  |
| Yes  | 53        | 25.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 28.32%  |
| Realtek Semiconductor           | 20        | 17.7%   |
| Cambridge Silicon Radio         | 9         | 7.96%   |
| Lite-On Technology              | 8         | 7.08%   |
| Qualcomm Atheros Communications | 7         | 6.19%   |
| IMC Networks                    | 7         | 6.19%   |
| Broadcom                        | 7         | 6.19%   |
| Apple                           | 6         | 5.31%   |
| Hewlett-Packard                 | 5         | 4.42%   |
| Dell                            | 3         | 2.65%   |
| Chicony Electronics             | 2         | 1.77%   |
| ASUSTek Computer                | 2         | 1.77%   |
| Toshiba                         | 1         | 0.88%   |
| Smart Modular Technologies      | 1         | 0.88%   |
| Ralink                          | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |
| Foxconn / Hon Hai               | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 14.16%  |
| Realtek Bluetooth Radio                             | 10        | 8.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 7.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 7.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 4.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 3.54%   |
| IMC Networks Bluetooth Device                       | 4         | 3.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 2.65%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.77%   |
| Lite-On Bluetooth Device                            | 2         | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.77%   |
| Intel AX201 Bluetooth                               | 2         | 1.77%   |
| Intel AX200 Bluetooth                               | 2         | 1.77%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.77%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.77%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.77%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 1.77%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.77%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.77%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.77%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.77%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.88%   |
| Smart Modular Bluetooth Device                      | 1         | 0.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.88%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.88%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.88%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.88%   |
| MediaTek Wireless_Device                            | 1         | 0.88%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.88%   |
| Intel AX211 Bluetooth                               | 1         | 0.88%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.88%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.88%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.88%   |
| Broadcom HP Portable Valentine                      | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 153       | 60.24%  |
| AMD                     | 52        | 20.47%  |
| Nvidia                  | 29        | 11.42%  |
| C-Media Electronics     | 4         | 1.57%   |
| JMTek                   | 3         | 1.18%   |
| Logitech                | 2         | 0.79%   |
| Creative Labs           | 2         | 0.79%   |
| ULi Electronics         | 1         | 0.39%   |
| Texas Instruments       | 1         | 0.39%   |
| Realtek Semiconductor   | 1         | 0.39%   |
| GN Netcom               | 1         | 0.39%   |
| Giga-Byte Technology    | 1         | 0.39%   |
| Ensoniq                 | 1         | 0.39%   |
| Blue Microphones        | 1         | 0.39%   |
| BEHRINGER International | 1         | 0.39%   |
| ATI Technologies        | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 3.73%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 3.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 3.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 3.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 3.05%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 9         | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 2.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.36%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.36%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.02%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.02%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.68%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.68%   |
| JMTek USB Speaker                                                                                 | 2         | 0.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.68%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 19.55%  |
| Unknown             | 33        | 18.44%  |
| SK hynix            | 28        | 15.64%  |
| Kingston            | 23        | 12.85%  |
| Micron Technology   | 16        | 8.94%   |
| Unknown             | 6         | 3.35%   |
| Unknown (ABCD)      | 5         | 2.79%   |
| Corsair             | 5         | 2.79%   |
| Elpida              | 4         | 2.23%   |
| Nanya Technology    | 3         | 1.68%   |
| A-DATA Technology   | 3         | 1.68%   |
| Ramaxel Technology  | 2         | 1.12%   |
| Unknown (0x7F61)    | 1         | 0.56%   |
| Transcend           | 1         | 0.56%   |
| Smart               | 1         | 0.56%   |
| Qumo                | 1         | 0.56%   |
| Qimonda             | 1         | 0.56%   |
| Patriot             | 1         | 0.56%   |
| GOODRAM             | 1         | 0.56%   |
| GeIL                | 1         | 0.56%   |
| G.Skill             | 1         | 0.56%   |
| G Skil              | 1         | 0.56%   |
| Crucial             | 1         | 0.56%   |
| Avant               | 1         | 0.56%   |
| 2C0C1121390963FE    | 1         | 0.56%   |
| 2C0C1121390963FD    | 1         | 0.56%   |
| 2C0C1121390963F9    | 1         | 0.56%   |
| 2C0C1121390963F8    | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 3.19%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 1.6%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 3         | 1.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.06%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.06%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 1.06%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1333MT/s         | 2         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR                               | 1         | 0.53%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.53%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.53%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                       | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 57        | 36.31%  |
| DDR4    | 38        | 24.2%   |
| DDR2    | 25        | 15.92%  |
| SDRAM   | 13        | 8.28%   |
| LPDDR4  | 10        | 6.37%   |
| Unknown | 7         | 4.46%   |
| DDR     | 5         | 3.18%   |
| LPDDR5  | 1         | 0.64%   |
| DRAM    | 1         | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 63.4%   |
| DIMM         | 52        | 33.99%  |
| Row Of Chips | 2         | 1.31%   |
| FB-DIMM      | 2         | 1.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 53        | 31.36%  |
| 4096  | 49        | 28.99%  |
| 8192  | 33        | 19.53%  |
| 1024  | 19        | 11.24%  |
| 16384 | 10        | 5.92%   |
| 32768 | 3         | 1.78%   |
| 6144  | 1         | 0.59%   |
| 512   | 1         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 41        | 24.85%  |
| 2667    | 16        | 9.7%    |
| 3200    | 15        | 9.09%   |
| 667     | 14        | 8.48%   |
| 1333    | 12        | 7.27%   |
| Unknown | 10        | 6.06%   |
| 2400    | 8         | 4.85%   |
| 800     | 7         | 4.24%   |
| 3266    | 4         | 2.42%   |
| 4199    | 3         | 1.82%   |
| 3400    | 3         | 1.82%   |
| 2133    | 3         | 1.82%   |
| 2048    | 3         | 1.82%   |
| 1334    | 3         | 1.82%   |
| 975     | 3         | 1.82%   |
| 400     | 3         | 1.82%   |
| 1066    | 2         | 1.21%   |
| 49926   | 1         | 0.61%   |
| 19791   | 1         | 0.61%   |
| 6400    | 1         | 0.61%   |
| 4267    | 1         | 0.61%   |
| 3933    | 1         | 0.61%   |
| 3800    | 1         | 0.61%   |
| 3733    | 1         | 0.61%   |
| 3500    | 1         | 0.61%   |
| 2734    | 1         | 0.61%   |
| 1866    | 1         | 0.61%   |
| 1800    | 1         | 0.61%   |
| 1639    | 1         | 0.61%   |
| 1067    | 1         | 0.61%   |
| 1033    | 1         | 0.61%   |
| 133     | 1         | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Canon LBP2900      | 1         | 50%     |
| Canon G1020 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Mustek Systems  | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 25%     |
| HP ScanJet 5200c                   | 1         | 25%     |
| Canon CanoScan LiDE 120            | 1         | 25%     |
| Canon CanoScan LiDE 110            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 26.02%  |
| Apple                                  | 9         | 7.32%   |
| Realtek Semiconductor                  | 8         | 6.5%    |
| IMC Networks                           | 8         | 6.5%    |
| Suyin                                  | 7         | 5.69%   |
| Quanta                                 | 7         | 5.69%   |
| Microdia                               | 6         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.88%   |
| Syntek                                 | 5         | 4.07%   |
| Silicon Motion                         | 5         | 4.07%   |
| Alcor Micro                            | 5         | 4.07%   |
| Sunplus Innovation Technology          | 3         | 2.44%   |
| Lite-On Technology                     | 3         | 2.44%   |
| Bison Electronics                      | 3         | 2.44%   |
| Z-Star Microelectronics                | 2         | 1.63%   |
| Ricoh                                  | 2         | 1.63%   |
| Logitech                               | 2         | 1.63%   |
| Sunplus IT                             | 1         | 0.81%   |
| Samsung Electronics                    | 1         | 0.81%   |
| Pixart Imaging                         | 1         | 0.81%   |
| OmniVision Technologies                | 1         | 0.81%   |
| Microsoft                              | 1         | 0.81%   |
| Jieli Technology                       | 1         | 0.81%   |
| Hewlett-Packard                        | 1         | 0.81%   |
| Generalplus Technology                 | 1         | 0.81%   |
| Aveo Technology                        | 1         | 0.81%   |
| ALi                                    | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                       | 6         | 4.88%   |
| Chicony Integrated Camera                           | 4         | 3.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 4         | 3.25%   |
| Chicony USB 2.0 Camera                              | 3         | 2.44%   |
| Syntek USB Video Device                             | 2         | 1.63%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.63%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.63%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.63%   |
| Lite-On HP Webcam                                   | 2         | 1.63%   |
| IMC Networks EasyCamera                             | 2         | 1.63%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 1.63%   |
| Chicony FJ Camera                                   | 2         | 1.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.63%   |
| Bison Lenovo EasyCamera                             | 2         | 1.63%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.63%   |
| Apple Built-in iSight                               | 2         | 1.63%   |
| Alcor Micro Acer Integrated Webcam                  | 2         | 1.63%   |
| Z-Star Webcam                                       | 1         | 0.81%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.81%   |
| Syntek Integrated Camera                            | 1         | 0.81%   |
| Suyin USB 2.0 Camera                                | 1         | 0.81%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.81%   |
| Suyin HP Truevision HD                              | 1         | 0.81%   |
| Suyin HP Integrated Webcam                          | 1         | 0.81%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 0.81%   |
| Sunplus IT PC Camera                                | 1         | 0.81%   |
| Sunplus MTD camera                                  | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.81%   |
| Sunplus HD WebCam                                   | 1         | 0.81%   |
| Silicon Motion WebCam SC-10HDD13335N                | 1         | 0.81%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.81%   |
| Silicon Motion Web Camera                           | 1         | 0.81%   |
| Silicon Motion Real HD WebCam                       | 1         | 0.81%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.81%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.81%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.81%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.81%   |
| Realtek USB2.0 camera                               | 1         | 0.81%   |
| Realtek USB Camera                                  | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 26.67%  |
| Validity Sensors      | 3         | 20%     |
| Upek                  | 2         | 13.33%  |
| Synaptics             | 2         | 13.33%  |
| LighTuning Technology | 2         | 13.33%  |
| Samsung Electronics   | 1         | 6.67%   |
| Focal-systems.Corp    | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 13.33%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 13.33%  |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 6.67%   |
| Synaptics WBDI                                         | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 6.67%   |
| Samsung Fingerprint Device                             | 1         | 6.67%   |
| LighTuning Fingerprint Reader                          | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.67%   |
| AuthenTec AES1600                                      | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| O2 Micro    | 2         | 33.33%  |
| Broadcom    | 2         | 33.33%  |
| Upek        | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 150       | 72.46%  |
| 1     | 47        | 22.71%  |
| 2     | 10        | 4.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 22        | 32.84%  |
| Fingerprint reader       | 15        | 22.39%  |
| Net/wireless             | 8         | 11.94%  |
| Chipcard                 | 6         | 8.96%   |
| Storage                  | 3         | 4.48%   |
| Sound                    | 2         | 2.99%   |
| Network                  | 2         | 2.99%   |
| Multimedia controller    | 2         | 2.99%   |
| Bluetooth                | 2         | 2.99%   |
| Unassigned class         | 1         | 1.49%   |
| Net/ethernet             | 1         | 1.49%   |
| Dvb card                 | 1         | 1.49%   |
| Communication controller | 1         | 1.49%   |
| Camera                   | 1         | 1.49%   |

