Slackware 15.0 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 82

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad T60 8744HDG        | [397feea269](https://linux-hardware.org/?probe=397feea269) | Aug 03, 2025 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [6d7c7e541d](https://linux-hardware.org/?probe=6d7c7e541d) | May 07, 2025 |
| Acer      | Nitro ANV15-41              | [103ad43d8e](https://linux-hardware.org/?probe=103ad43d8e) | Jan 13, 2025 |
| HP        | Laptop 14-fq0xxx            | [2e065da895](https://linux-hardware.org/?probe=2e065da895) | Dec 26, 2024 |
| HP        | Victus by Gaming Laptop ... | [ba32f5b55e](https://linux-hardware.org/?probe=ba32f5b55e) | Aug 26, 2024 |
| HP        | Pavilion g6                 | [8d4cd1cce3](https://linux-hardware.org/?probe=8d4cd1cce3) | Jul 25, 2024 |
| Lenovo    | IdeaPad 5 15ALC05 82LN      | [f7b2ff4d05](https://linux-hardware.org/?probe=f7b2ff4d05) | Jul 17, 2024 |
| HP        | OMEN by Laptop 16-b1xxx     | [63bafff3a1](https://linux-hardware.org/?probe=63bafff3a1) | May 25, 2024 |
| Dynabook  | PORTEGE X50-G               | [995067b4e8](https://linux-hardware.org/?probe=995067b4e8) | May 22, 2024 |
| Lenovo    | ThinkPad X201 3626F7U       | [40e1a8f2e0](https://linux-hardware.org/?probe=40e1a8f2e0) | May 10, 2024 |
| Lenovo    | ThinkPad X201 3626F7U       | [44b7fec8f8](https://linux-hardware.org/?probe=44b7fec8f8) | May 10, 2024 |
| Lenovo    | ThinkPad T430s 2355CL4      | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Lenovo    | ThinkPad T16 Gen 2 21K7C... | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| Dell      | Precision 7510              | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| Lenovo    | ThinkPad T430s 2355CL4      | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| MSI       | Modern 14 B5M               | [585c473256](https://linux-hardware.org/?probe=585c473256) | Mar 08, 2024 |
| Dell      | XPS 13 9370                 | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Notebook  | NL5xNU                      | [e83f0b4085](https://linux-hardware.org/?probe=e83f0b4085) | Feb 18, 2024 |
| Dell      | XPS 13 9370                 | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| HP        | Laptop 14s-fq0xxx           | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| Acer      | Aspire SW5-012              | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| Lenovo    | V330-14ARR 81B1             | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Toshiba   | Satellite C660              | [483998d7de](https://linux-hardware.org/?probe=483998d7de) | Oct 20, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [aafdab7043](https://linux-hardware.org/?probe=aafdab7043) | Oct 13, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [a1a64b6621](https://linux-hardware.org/?probe=a1a64b6621) | Oct 05, 2023 |
| Notebook  | P7xxTM                      | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook  | P7xxTM                      | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo    | ThinkPad E16 Gen 1 21JT0... | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| Dell      | Vostro 3405                 | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
| Valve     | Jupiter                     | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo    | IdeaPad 5 15ALC05 82LN      | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| HP        | Laptop 14s-fq0xxx           | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Acer      | Swift SF114-34              | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| Apple     | MacBookAir7,2               | [941aa94750](https://linux-hardware.org/?probe=941aa94750) | Apr 13, 2023 |
| Valve     | Jupiter                     | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [fde666c0ea](https://linux-hardware.org/?probe=fde666c0ea) | Feb 17, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [5ce5272a93](https://linux-hardware.org/?probe=5ce5272a93) | Feb 17, 2023 |
| Lenovo    | ThinkPad X140e 20BMS03E0... | [fb4c4aebf9](https://linux-hardware.org/?probe=fb4c4aebf9) | Jan 31, 2023 |
| Lenovo    | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HP        | EliteBook 8440p             | [9edc837033](https://linux-hardware.org/?probe=9edc837033) | Jan 13, 2023 |
| HP        | OMEN by Laptop 17-ck0xxx    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Acer      | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo    | ThinkPad T470 20JNS01R01    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo    | ThinkPad T410 2518C3U       | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| Fujitsu   | LIFEBOOK A544               | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI       | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Sony      | SVE1713A1EW                 | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| MSI       | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI       | GE76 Raider 11UE            | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook  | X170KM-G                    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Dell      | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP        | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo    | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell      | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 13        | 19.12%  |
| 5.15.145                    | 4         | 5.88%   |
| 5.15.117                    | 4         | 5.88%   |
| 5.19.17                     | 3         | 4.41%   |
| 6.1.44                      | 2         | 2.94%   |
| 5.17.1                      | 2         | 2.94%   |
| 5.15.80                     | 2         | 2.94%   |
| 5.15.38                     | 2         | 2.94%   |
| 5.15.161                    | 2         | 2.94%   |
| 5.13.8                      | 2         | 2.94%   |
| 6.8.8                       | 1         | 1.47%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 1.47%   |
| 6.6.8                       | 1         | 1.47%   |
| 6.6.28                      | 1         | 1.47%   |
| 6.6.26                      | 1         | 1.47%   |
| 6.5.5                       | 1         | 1.47%   |
| 6.12.9                      | 1         | 1.47%   |
| 6.12.6                      | 1         | 1.47%   |
| 6.10.3                      | 1         | 1.47%   |
| 6.1.51                      | 1         | 1.47%   |
| 6.1.12                      | 1         | 1.47%   |
| 6.1.1                       | 1         | 1.47%   |
| 5.17.5                      | 1         | 1.47%   |
| 5.17.2                      | 1         | 1.47%   |
| 5.16.9-joe1                 | 1         | 1.47%   |
| 5.16.12                     | 1         | 1.47%   |
| 5.15.78.a                   | 1         | 1.47%   |
| 5.15.63                     | 1         | 1.47%   |
| 5.15.37.a                   | 1         | 1.47%   |
| 5.15.33.kjh                 | 1         | 1.47%   |
| 5.15.27                     | 1         | 1.47%   |
| 5.15.188                    | 1         | 1.47%   |
| 5.15.159.a                  | 1         | 1.47%   |
| 5.15.118                    | 1         | 1.47%   |
| 5.15.1                      | 1         | 1.47%   |
| 5.14.9                      | 1         | 1.47%   |
| 5.14.8                      | 1         | 1.47%   |
| 5.14.10                     | 1         | 1.47%   |
| 5.14.0                      | 1         | 1.47%   |
| 5.13.5                      | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 13        | 19.12%  |
| 5.15.145 | 4         | 5.88%   |
| 5.15.117 | 4         | 5.88%   |
| 5.19.17  | 3         | 4.41%   |
| 6.1.44   | 2         | 2.94%   |
| 5.17.1   | 2         | 2.94%   |
| 5.15.80  | 2         | 2.94%   |
| 5.15.38  | 2         | 2.94%   |
| 5.15.161 | 2         | 2.94%   |
| 5.13.8   | 2         | 2.94%   |
| 6.8.8    | 1         | 1.47%   |
| 6.7.5    | 1         | 1.47%   |
| 6.6.8    | 1         | 1.47%   |
| 6.6.28   | 1         | 1.47%   |
| 6.6.26   | 1         | 1.47%   |
| 6.5.5    | 1         | 1.47%   |
| 6.12.9   | 1         | 1.47%   |
| 6.12.6   | 1         | 1.47%   |
| 6.10.3   | 1         | 1.47%   |
| 6.1.51   | 1         | 1.47%   |
| 6.1.12   | 1         | 1.47%   |
| 6.1.1    | 1         | 1.47%   |
| 5.17.5   | 1         | 1.47%   |
| 5.17.2   | 1         | 1.47%   |
| 5.16.9   | 1         | 1.47%   |
| 5.16.12  | 1         | 1.47%   |
| 5.15.78  | 1         | 1.47%   |
| 5.15.63  | 1         | 1.47%   |
| 5.15.37  | 1         | 1.47%   |
| 5.15.33  | 1         | 1.47%   |
| 5.15.27  | 1         | 1.47%   |
| 5.15.188 | 1         | 1.47%   |
| 5.15.159 | 1         | 1.47%   |
| 5.15.118 | 1         | 1.47%   |
| 5.15.1   | 1         | 1.47%   |
| 5.14.9   | 1         | 1.47%   |
| 5.14.8   | 1         | 1.47%   |
| 5.14.10  | 1         | 1.47%   |
| 5.14.0   | 1         | 1.47%   |
| 5.13.5   | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 36        | 53.73%  |
| 6.1     | 5         | 7.46%   |
| 5.17    | 4         | 5.97%   |
| 5.13    | 4         | 5.97%   |
| 6.6     | 3         | 4.48%   |
| 5.19    | 3         | 4.48%   |
| 5.14    | 3         | 4.48%   |
| 6.12    | 2         | 2.99%   |
| 5.16    | 2         | 2.99%   |
| 6.8     | 1         | 1.49%   |
| 6.7     | 1         | 1.49%   |
| 6.5     | 1         | 1.49%   |
| 6.10    | 1         | 1.49%   |
| 5.10    | 1         | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 31        | 48.44%  |
| XFCE      | 20        | 31.25%  |
| Unknown   | 6         | 9.38%   |
| MATE      | 2         | 3.13%   |
| xwmconfig | 1         | 1.56%   |
| KDE       | 1         | 1.56%   |
| GNOME     | 1         | 1.56%   |
| awesome   | 1         | 1.56%   |
| 2bwm      | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 35        | 53.03%  |
| Tty     | 28        | 42.42%  |
| Wayland | 3         | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 38        | 57.58%  |
| XDM     | 13        | 19.7%   |
| Unknown | 13        | 19.7%   |
| LightDM | 1         | 1.52%   |
| GDM     | 1         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 47        | 74.6%   |
| it_IT   | 3         | 4.76%   |
| de_DE   | 3         | 4.76%   |
| pt_BR   | 2         | 3.17%   |
| fr_FR   | 2         | 3.17%   |
| cs_CZ   | 2         | 3.17%   |
| zh_TW   | 1         | 1.59%   |
| ru_RU   | 1         | 1.59%   |
| en_SE   | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 62.5%   |
| BIOS | 24        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 86.15%  |
| Btrfs   | 4         | 6.15%   |
| Overlay | 3         | 4.62%   |
| Xfs     | 1         | 1.54%   |
| Jfs     | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 42        | 65.63%  |
| MBR     | 12        | 18.75%  |
| Unknown | 10        | 15.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 79.69%  |
| Yes       | 13        | 20.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 64.06%  |
| Yes       | 23        | 35.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 18        | 28.57%  |
| Hewlett-Packard  | 14        | 22.22%  |
| Dell             | 7         | 11.11%  |
| MSI              | 5         | 7.94%   |
| ASUSTek Computer | 4         | 6.35%   |
| Acer             | 4         | 6.35%   |
| Notebook         | 3         | 4.76%   |
| Dynabook         | 2         | 3.17%   |
| Valve            | 1         | 1.59%   |
| Toshiba          | 1         | 1.59%   |
| System76         | 1         | 1.59%   |
| Sony             | 1         | 1.59%   |
| Fujitsu          | 1         | 1.59%   |
| Framework        | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 3.17%   |
| Valve Jupiter                            | 1         | 1.59%   |
| Toshiba Satellite C660                   | 1         | 1.59%   |
| System76 Oryx Pro                        | 1         | 1.59%   |
| Sony SVE1713A1EW                         | 1         | 1.59%   |
| Notebook X170KM-G                        | 1         | 1.59%   |
| Notebook P7xxTM                          | 1         | 1.59%   |
| Notebook NL5xNU                          | 1         | 1.59%   |
| MSI Modern 14 B5M                        | 1         | 1.59%   |
| MSI Modern 14 B11MO                      | 1         | 1.59%   |
| MSI Modern 14 B10MW                      | 1         | 1.59%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.59%   |
| MSI GE76 Raider 11UE                     | 1         | 1.59%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.59%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.59%   |
| Lenovo ThinkPad X201 3626F7U             | 1         | 1.59%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 1.59%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.59%   |
| Lenovo ThinkPad T60 8744HDG              | 1         | 1.59%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.59%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.59%   |
| Lenovo ThinkPad T430s 2355CL4            | 1         | 1.59%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.59%   |
| Lenovo ThinkPad T16 Gen 2 21K7CTO1WW     | 1         | 1.59%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.59%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 1.59%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 1.59%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.59%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.59%   |
| HP Victus by Gaming Laptop 15-fb0xxx     | 1         | 1.59%   |
| HP ProBook 6570b                         | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.59%   |
| HP Pavilion g6                           | 1         | 1.59%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 1.59%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.59%   |
| HP Laptop 15-bs1xx                       | 1         | 1.59%   |
| HP Laptop 14s-fq0xxx                     | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 14        | 22.22%  |
| MSI Modern          | 3         | 4.76%   |
| Lenovo IdeaPad      | 3         | 4.76%   |
| HP Pavilion         | 3         | 4.76%   |
| HP Laptop           | 3         | 4.76%   |
| HP OMEN             | 2         | 3.17%   |
| HP EliteBook        | 2         | 3.17%   |
| Dell Vostro         | 2         | 3.17%   |
| Dell Precision      | 2         | 3.17%   |
| ASUS VivoBook       | 2         | 3.17%   |
| Acer Nitro          | 2         | 3.17%   |
| Valve Jupiter       | 1         | 1.59%   |
| Toshiba Satellite   | 1         | 1.59%   |
| System76 Oryx       | 1         | 1.59%   |
| Sony SVE1713A1EW    | 1         | 1.59%   |
| Notebook X170KM-G   | 1         | 1.59%   |
| Notebook P7xxTM     | 1         | 1.59%   |
| Notebook NL5xNU     | 1         | 1.59%   |
| MSI GP76            | 1         | 1.59%   |
| MSI GE76            | 1         | 1.59%   |
| Lenovo V330-14ARR   | 1         | 1.59%   |
| HP Victus           | 1         | 1.59%   |
| HP ProBook          | 1         | 1.59%   |
| HP ENVY             | 1         | 1.59%   |
| HP 245              | 1         | 1.59%   |
| Fujitsu LIFEBOOK    | 1         | 1.59%   |
| Framework Laptop    | 1         | 1.59%   |
| Dynabook PORTEGE    | 1         | 1.59%   |
| Dynabook P1-C7MP-BL | 1         | 1.59%   |
| Dell XPS            | 1         | 1.59%   |
| Dell Latitude       | 1         | 1.59%   |
| Dell Inspiron       | 1         | 1.59%   |
| ASUS ROG            | 1         | 1.59%   |
| ASUS ASUS           | 1         | 1.59%   |
| Acer Swift          | 1         | 1.59%   |
| Acer Aspire         | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 12        | 19.05%  |
| 2021 | 9         | 14.29%  |
| 2022 | 7         | 11.11%  |
| 2012 | 5         | 7.94%   |
| 2018 | 4         | 6.35%   |
| 2017 | 4         | 6.35%   |
| 2019 | 3         | 4.76%   |
| 2010 | 3         | 4.76%   |
| 2023 | 2         | 3.17%   |
| 2016 | 2         | 3.17%   |
| 2015 | 2         | 3.17%   |
| 2013 | 2         | 3.17%   |
| 2009 | 2         | 3.17%   |
| 2024 | 1         | 1.59%   |
| 2014 | 1         | 1.59%   |
| 2011 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |
| 2007 | 1         | 1.59%   |
| 2006 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 96.83%  |
| Yes  | 2         | 3.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 26.56%  |
| 4.01-8.0    | 14        | 21.88%  |
| 16.01-24.0  | 11        | 17.19%  |
| 3.01-4.0    | 8         | 12.5%   |
| 32.01-64.0  | 5         | 7.81%   |
| 64.01-256.0 | 4         | 6.25%   |
| 24.01-32.0  | 3         | 4.69%   |
| 2.01-3.0    | 1         | 1.56%   |
| 1.01-2.0    | 1         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 23        | 32.86%  |
| 1.01-2.0   | 17        | 24.29%  |
| 4.01-8.0   | 14        | 20%     |
| 0.51-1.0   | 8         | 11.43%  |
| 3.01-4.0   | 4         | 5.71%   |
| 16.01-24.0 | 2         | 2.86%   |
| 0.01-0.5   | 2         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 68.75%  |
| 2      | 17        | 26.56%  |
| 4      | 2         | 3.13%   |
| 3      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 80.95%  |
| Yes       | 12        | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 86.15%  |
| No        | 9         | 13.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 92.06%  |
| No        | 5         | 7.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 87.3%   |
| No        | 8         | 12.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 15        | 23.81%  |
| Portugal     | 4         | 6.35%   |
| Japan        | 4         | 6.35%   |
| Italy        | 4         | 6.35%   |
| Kazakhstan   | 3         | 4.76%   |
| Germany      | 3         | 4.76%   |
| France       | 3         | 4.76%   |
| Spain        | 2         | 3.17%   |
| South Africa | 2         | 3.17%   |
| Romania      | 2         | 3.17%   |
| India        | 2         | 3.17%   |
| Czechia      | 2         | 3.17%   |
| Brazil       | 2         | 3.17%   |
| Argentina    | 2         | 3.17%   |
| UK           | 1         | 1.59%   |
| Taiwan       | 1         | 1.59%   |
| Sweden       | 1         | 1.59%   |
| Serbia       | 1         | 1.59%   |
| Russia       | 1         | 1.59%   |
| Mexico       | 1         | 1.59%   |
| Lithuania    | 1         | 1.59%   |
| Iran         | 1         | 1.59%   |
| Greece       | 1         | 1.59%   |
| China        | 1         | 1.59%   |
| Chile        | 1         | 1.59%   |
| Canada       | 1         | 1.59%   |
| Belgium      | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tsukuba            | 3         | 4.62%   |
| Lisbon             | 3         | 4.62%   |
| Ust-Kamenogorsk    | 2         | 3.08%   |
| Sun Prairie        | 2         | 3.08%   |
| Greater Noida      | 2         | 3.08%   |
| Frignano           | 2         | 3.08%   |
| Bucharest          | 2         | 3.08%   |
| Worpswede          | 1         | 1.54%   |
| Vilnius            | 1         | 1.54%   |
| Villaputzu         | 1         | 1.54%   |
| Villa Carlos Paz   | 1         | 1.54%   |
| Tehran             | 1         | 1.54%   |
| Taichung           | 1         | 1.54%   |
| Skövde            | 1         | 1.54%   |
| Seattle            | 1         | 1.54%   |
| Sao Paulo          | 1         | 1.54%   |
| Santiago           | 1         | 1.54%   |
| Santander          | 1         | 1.54%   |
| Round Rock         | 1         | 1.54%   |
| Roudnice nad Labem | 1         | 1.54%   |
| Reno               | 1         | 1.54%   |
| Renazzo            | 1         | 1.54%   |
| Punxsutawney       | 1         | 1.54%   |
| Plainwell          | 1         | 1.54%   |
| Ōtsu              | 1         | 1.54%   |
| Oberstreit         | 1         | 1.54%   |
| Novy Jicin         | 1         | 1.54%   |
| New Delhi          | 1         | 1.54%   |
| Moscow             | 1         | 1.54%   |
| Montreal           | 1         | 1.54%   |
| Mexico City        | 1         | 1.54%   |
| Meuselwitz         | 1         | 1.54%   |
| McKinney           | 1         | 1.54%   |
| Lynden             | 1         | 1.54%   |
| Luxeuil-les-Bains  | 1         | 1.54%   |
| League City        | 1         | 1.54%   |
| Kent               | 1         | 1.54%   |
| Karaganda          | 1         | 1.54%   |
| Johannesburg       | 1         | 1.54%   |
| Hayward            | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 16        | 22     | 19.75%  |
| WDC                         | 9         | 11     | 11.11%  |
| Kingston                    | 8         | 9      | 9.88%   |
| Seagate                     | 5         | 5      | 6.17%   |
| SanDisk                     | 5         | 8      | 6.17%   |
| Intel                       | 5         | 6      | 6.17%   |
| Toshiba                     | 3         | 3      | 3.7%    |
| SK hynix                    | 3         | 3      | 3.7%    |
| Micron Technology           | 3         | 3      | 3.7%    |
| HGST                        | 3         | 3      | 3.7%    |
| Unknown                     | 2         | 4      | 2.47%   |
| Micron/Crucial Technology   | 2         | 2      | 2.47%   |
| LITEON                      | 2         | 2      | 2.47%   |
| Crucial                     | 2         | 2      | 2.47%   |
| Verbatim                    | 1         | 2      | 1.23%   |
| Transcend                   | 1         | 1      | 1.23%   |
| SSSTC                       | 1         | 1      | 1.23%   |
| Silicon Motion              | 1         | 1      | 1.23%   |
| Plextor                     | 1         | 1      | 1.23%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.23%   |
| KIOXIA                      | 1         | 1      | 1.23%   |
| Kingston Technology Company | 1         | 1      | 1.23%   |
| KingSpec                    | 1         | 1      | 1.23%   |
| JMicron Technology          | 1         | 1      | 1.23%   |
| Hewlett-Packard             | 1         | 2      | 1.23%   |
| Gigabyte Technology         | 1         | 1      | 1.23%   |
| External                    | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 4         | 4.49%   |
| Seagate ST1000LM048-2E7172 1TB                        | 3         | 3.37%   |
| Intel SSD 660P Series 512GB                           | 3         | 3.37%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 2.25%   |
| HGST HTS725050A7E630 500GB                            | 2         | 2.25%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 1.12%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 1.12%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 1         | 1.12%   |
| WDC WD10JPVT-08A1YT2 1TB                              | 1         | 1.12%   |
| WDC WD Green 2.5 240GB                                | 1         | 1.12%   |
| WDC WD Blue SA510 2.5 2TB                             | 1         | 1.12%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                    | 1         | 1.12%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 1.12%   |
| Verbatim Vi550 S3 SSD 512GB                           | 1         | 1.12%   |
| Unknown MMC Card  64GB                                | 1         | 1.12%   |
| Unknown MMC Card  512GB                               | 1         | 1.12%   |
| Unknown MMC Card  32GB                                | 1         | 1.12%   |
| Transcend TS256GMTE352T-VLV 256GB                     | 1         | 1.12%   |
| Toshiba MQ04ABF100 1TB                                | 1         | 1.12%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 1.12%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 1.12%   |
| SSSTC CVB-8D128-HP 128GB                              | 1         | 1.12%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 1.12%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB               | 1         | 1.12%   |
| SK hynix BC511 512GB                                  | 1         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 1         | 1.12%   |
| Seagate ST2000LX001-1RG174 2TB                        | 1         | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 1.12%   |
| Sandisk WDC PC SN540 SDDPNPF-512G-1032 512GB          | 1         | 1.12%   |
| Sandisk WD PC SN740 SDDQNQD-1T00-1201 1TB             | 1         | 1.12%   |
| Sandisk WD Black SN850 1TB                            | 1         | 1.12%   |
| SanDisk Ultra II 960GB SSD                            | 1         | 1.12%   |
| SanDisk SDSSDA240G 240GB                              | 1         | 1.12%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.12%   |
| Samsung SSD PM830 2.5 7mm 128GB                       | 1         | 1.12%   |
| Samsung SSD 980 PRO 500GB                             | 1         | 1.12%   |
| Samsung SSD 980 PRO 2TB                               | 1         | 1.12%   |
| Samsung SSD 980 PRO 1TB                               | 1         | 1.12%   |
| Samsung SSD 970 EVO Plus 500GB                        | 1         | 1.12%   |
| Samsung SSD 970 EVO Plus 2TB                          | 1         | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 5         | 5      | 29.41%  |
| WDC                | 4         | 4      | 23.53%  |
| Toshiba            | 3         | 3      | 17.65%  |
| HGST               | 3         | 3      | 17.65%  |
| JMicron Technology | 1         | 1      | 5.88%   |
| External           | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 8      | 29.17%  |
| Samsung Electronics | 4         | 6      | 16.67%  |
| WDC                 | 3         | 4      | 12.5%   |
| SanDisk             | 2         | 2      | 8.33%   |
| Verbatim            | 1         | 2      | 4.17%   |
| SSSTC               | 1         | 1      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| KingSpec            | 1         | 1      | 4.17%   |
| Gigabyte Technology | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 48     | 46.84%  |
| SSD  | 24        | 29     | 30.38%  |
| HDD  | 16        | 17     | 20.25%  |
| MMC  | 2         | 4      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 48     | 49.33%  |
| SATA | 32        | 41     | 42.67%  |
| SAS  | 4         | 5      | 5.33%   |
| MMC  | 2         | 4      | 2.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 60%     |
| 0.51-1.0   | 14        | 16     | 35%     |
| 1.01-2.0   | 2         | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 22        | 33.85%  |
| 101-250        | 16        | 24.62%  |
| 251-500        | 11        | 16.92%  |
| 1001-2000      | 8         | 12.31%  |
| 21-50          | 2         | 3.08%   |
| 1-20           | 2         | 3.08%   |
| 51-100         | 2         | 3.08%   |
| More than 3000 | 1         | 1.54%   |
| 2001-3000      | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 251-500   | 16        | 23.88%  |
| 101-250   | 16        | 23.88%  |
| 21-50     | 11        | 16.42%  |
| 1-20      | 10        | 14.93%  |
| 51-100    | 6         | 8.96%   |
| 501-1000  | 5         | 7.46%   |
| 1001-2000 | 3         | 4.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SSSTC CVB-8D128-HP 128GB            | 1         | 1      | 20%     |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 20%     |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 20%     |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 20%     |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 2         | 2      | 40%     |
| SSSTC               | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Plextor             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 60%     |
| HDD  | 2         | 2      | 40%     |

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
| Works    | 51        | 69     | 72.86%  |
| Detected | 14        | 24     | 20%     |
| Malfunc  | 5         | 5      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 35        | 46.67%  |
| Samsung Electronics         | 12        | 16%     |
| AMD                         | 8         | 10.67%  |
| SanDisk                     | 5         | 6.67%   |
| SK hynix                    | 3         | 4%      |
| Micron/Crucial Technology   | 3         | 4%      |
| Micron Technology           | 2         | 2.67%   |
| Kingston Technology Company | 2         | 2.67%   |
| Silicon Motion              | 1         | 1.33%   |
| MAXIO Technology (Hangzhou) | 1         | 1.33%   |
| Lite-On Technology          | 1         | 1.33%   |
| KIOXIA                      | 1         | 1.33%   |
| Biwin Storage Technology    | 1         | 1.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 8.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 6.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 6.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 6.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 4.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 3.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 3.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.7%    |
| Intel SSD 660P Series                                                            | 3         | 3.7%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.47%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.47%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.23%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 1         | 1.23%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.23%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                      | 1         | 1.23%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 1.23%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.23%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.23%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 1.23%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 1.23%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 1.23%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                         | 1         | 1.23%   |
| Lite-On CL1-3D256, CL1-8D512 NVMe SSD (DRAM-less)                                | 1         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.23%   |
| Kingston Company OM8SEP4 Design-In PCIe 4 NVMe SSD (TLC) (DRAM-less)             | 1         | 1.23%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 1.23%   |
| Intel SSD 600P Series                                                            | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 37        | 46.84%  |
| SATA | 32        | 40.51%  |
| RAID | 8         | 10.13%  |
| IDE  | 2         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 74.6%   |
| AMD    | 16        | 25.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 6.35%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 3.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 3.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 3.17%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 3.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.17%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.59%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.59%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.59%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.59%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.59%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.59%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.59%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.59%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.59%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 1         | 1.59%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.59%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.59%   |
| Intel 12th Gen Core i7-12650H                 | 1         | 1.59%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 1.59%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.59%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 1.59%   |
| AMD Ryzen 7 PRO 7840U w/ Radeon 780M Graphics | 1         | 1.59%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 1         | 1.59%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 14        | 22.22%  |
| Intel Core i5        | 14        | 22.22%  |
| Intel Core i7        | 12        | 19.05%  |
| AMD Ryzen 5          | 7         | 11.11%  |
| AMD Ryzen 7          | 4         | 6.35%   |
| Intel Core i3        | 2         | 3.17%   |
| Intel Pentium Silver | 1         | 1.59%   |
| Intel Pentium        | 1         | 1.59%   |
| Intel Core 2 Duo     | 1         | 1.59%   |
| Intel Core 2         | 1         | 1.59%   |
| Intel Celeron        | 1         | 1.59%   |
| Intel Atom           | 1         | 1.59%   |
| AMD Ryzen 9          | 1         | 1.59%   |
| AMD Ryzen 7 PRO      | 1         | 1.59%   |
| AMD Ryzen 3          | 1         | 1.59%   |
| AMD E1               | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 34.92%  |
| 4      | 18        | 28.57%  |
| 8      | 12        | 19.05%  |
| 6      | 6         | 9.52%   |
| 14     | 3         | 4.76%   |
| 10     | 2         | 3.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 55        | 87.3%   |
| 1      | 8         | 12.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 32.31%  |
| 0x306a9    | 5         | 7.69%   |
| 0x906a3    | 4         | 6.15%   |
| 0x806d1    | 4         | 6.15%   |
| 0x806c1    | 3         | 4.62%   |
| 0x20655    | 3         | 4.62%   |
| 0x806ea    | 2         | 3.08%   |
| 0x406e3    | 2         | 3.08%   |
| 0x08600106 | 2         | 3.08%   |
| 0x08108109 | 2         | 3.08%   |
| 0xa0671    | 1         | 1.54%   |
| 0xa0652    | 1         | 1.54%   |
| 0x906ed    | 1         | 1.54%   |
| 0x906ea    | 1         | 1.54%   |
| 0x906c0    | 1         | 1.54%   |
| 0x906a4    | 1         | 1.54%   |
| 0x806ec    | 1         | 1.54%   |
| 0x6f6      | 1         | 1.54%   |
| 0x406c4    | 1         | 1.54%   |
| 0x306d4    | 1         | 1.54%   |
| 0x306c3    | 1         | 1.54%   |
| 0x30678    | 1         | 1.54%   |
| 0x206a7    | 1         | 1.54%   |
| 0x08900201 | 1         | 1.54%   |
| 0x08608103 | 1         | 1.54%   |
| 0x08608102 | 1         | 1.54%   |
| 0x07000106 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 15.63%  |
| IvyBridge        | 6         | 9.38%   |
| Unknown          | 6         | 9.38%   |
| Westmere         | 5         | 7.81%   |
| Icelake          | 5         | 7.81%   |
| Alderlake Hybrid | 5         | 7.81%   |
| Skylake          | 4         | 6.25%   |
| Zen+             | 3         | 4.69%   |
| Zen 3            | 3         | 4.69%   |
| Zen 2            | 3         | 4.69%   |
| TigerLake        | 3         | 4.69%   |
| Silvermont       | 2         | 3.13%   |
| Core             | 2         | 3.13%   |
| Zen              | 1         | 1.56%   |
| Tremont          | 1         | 1.56%   |
| SandyBridge      | 1         | 1.56%   |
| Jaguar           | 1         | 1.56%   |
| Haswell          | 1         | 1.56%   |
| CometLake        | 1         | 1.56%   |
| Broadwell        | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 45%     |
| Nvidia | 22        | 27.5%   |
| AMD    | 22        | 27.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 4.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 3.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.7%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 3.7%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 3.7%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.47%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 2.47%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 2.47%   |
| AMD Lucienne                                                                             | 2         | 2.47%   |
| AMD Barcelo                                                                              | 2         | 2.47%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.23%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 1.23%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.23%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.23%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.23%   |
| Nvidia GA107 [GeForce RTX 2050]                                                          | 1         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.23%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 1         | 1.23%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 1         | 1.23%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.23%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.23%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.23%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 36.51%  |
| 1 x AMD        | 18        | 28.57%  |
| Intel + Nvidia | 11        | 17.46%  |
| 1 x Nvidia     | 7         | 11.11%  |
| AMD + Nvidia   | 3         | 4.76%   |
| Intel + AMD    | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 84.38%  |
| Proprietary | 10        | 15.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 55.38%  |
| 0.01-0.5   | 9         | 13.85%  |
| 0.51-1.0   | 6         | 9.23%   |
| 7.01-8.0   | 4         | 6.15%   |
| 3.01-4.0   | 4         | 6.15%   |
| 1.01-2.0   | 4         | 6.15%   |
| 5.01-6.0   | 2         | 3.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 15        | 20.27%  |
| AU Optronics        | 11        | 14.86%  |
| Chimei Innolux      | 9         | 12.16%  |
| LG Display          | 8         | 10.81%  |
| Samsung Electronics | 7         | 9.46%   |
| Sharp               | 4         | 5.41%   |
| Hewlett-Packard     | 4         | 5.41%   |
| Lenovo              | 3         | 4.05%   |
| Goldstar            | 2         | 2.7%    |
| Dell                | 2         | 2.7%    |
| BenQ                | 2         | 2.7%    |
| Valve               | 1         | 1.35%   |
| Sony                | 1         | 1.35%   |
| PANDA               | 1         | 1.35%   |
| IBM                 | 1         | 1.35%   |
| Hyundai ImageQuest  | 1         | 1.35%   |
| HKC                 | 1         | 1.35%   |
| AOC                 | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 2.7%    |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 2.7%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 2.7%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.35%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.35%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.35%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.35%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch               | 1         | 1.35%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.35%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 1.35%   |
| Samsung Electronics S23B350 SAM08D6 1920x1080 510x287mm 23.0-inch     | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.35%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.35%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.35%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 1.35%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 1.35%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 1         | 1.35%   |
| Hyundai ImageQuest B70A HIQ5004 1280x1024 337x270mm 17.0-inch         | 1         | 1.35%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 1.35%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.35%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.35%   |
| Hewlett-Packard 22vc HWP330E 1920x1080 480x270mm 21.7-inch            | 1         | 1.35%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.35%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.35%   |
| Dell S2721H DEL41F5 1920x1080 598x336mm 27.0-inch                     | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch      | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1538 1920x1080 344x193mm 15.5-inch      | 1         | 1.35%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 52.94%  |
| 1366x768 (WXGA)    | 11        | 16.18%  |
| 3840x2160 (4K)     | 3         | 4.41%   |
| 1600x900 (HD+)     | 3         | 4.41%   |
| 1280x800 (WXGA)    | 3         | 4.41%   |
| 2880x1620          | 2         | 2.94%   |
| 2560x1440 (QHD)    | 2         | 2.94%   |
| 1920x1200 (WUXGA)  | 2         | 2.94%   |
| 1680x1050 (WSXGA+) | 2         | 2.94%   |
| 800x1280           | 1         | 1.47%   |
| 2256x1504          | 1         | 1.47%   |
| 1360x768           | 1         | 1.47%   |
| 1280x1024 (SXGA)   | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 35.62%  |
| 14     | 10        | 13.7%   |
| 13     | 9         | 12.33%  |
| 17     | 6         | 8.22%   |
| 16     | 4         | 5.48%   |
| 31     | 3         | 4.11%   |
| 27     | 3         | 4.11%   |
| 21     | 3         | 4.11%   |
| 23     | 2         | 2.74%   |
| 12     | 2         | 2.74%   |
| 72     | 1         | 1.37%   |
| 24     | 1         | 1.37%   |
| 22     | 1         | 1.37%   |
| 11     | 1         | 1.37%   |
| 7      | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 61.64%  |
| 351-400     | 8         | 10.96%  |
| 501-600     | 5         | 6.85%   |
| 401-500     | 5         | 6.85%   |
| 201-300     | 5         | 6.85%   |
| 601-700     | 3         | 4.11%   |
| 1501-2000   | 1         | 1.37%   |
| 1-100       | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 52        | 82.54%  |
| 16/10 | 7         | 11.11%  |
| 3/2   | 2         | 3.17%   |
| 5/4   | 1         | 1.59%   |
| 0.67  | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 38.36%  |
| 81-90          | 18        | 24.66%  |
| 201-250        | 5         | 6.85%   |
| 121-130        | 5         | 6.85%   |
| 351-500        | 3         | 4.11%   |
| 301-350        | 3         | 4.11%   |
| 61-70          | 2         | 2.74%   |
| 111-120        | 2         | 2.74%   |
| More than 1000 | 1         | 1.37%   |
| 71-80          | 1         | 1.37%   |
| 51-60          | 1         | 1.37%   |
| 1-40           | 1         | 1.37%   |
| 251-300        | 1         | 1.37%   |
| 151-200        | 1         | 1.37%   |
| 141-150        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 38        | 55.07%  |
| 101-120       | 14        | 20.29%  |
| 51-100        | 10        | 14.49%  |
| 161-240       | 5         | 7.25%   |
| More than 240 | 1         | 1.45%   |
| 1-50          | 1         | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 80.95%  |
| 2     | 12        | 19.05%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 39.18%  |
| Realtek Semiconductor      | 35        | 36.08%  |
| MediaTek                   | 6         | 6.19%   |
| Qualcomm Atheros           | 4         | 4.12%   |
| ASIX Electronics           | 4         | 4.12%   |
| Broadcom Limited           | 3         | 3.09%   |
| Sitecom Europe             | 1         | 1.03%   |
| Shenzhen Goodix Technology | 1         | 1.03%   |
| Ralink Technology          | 1         | 1.03%   |
| Qualcomm                   | 1         | 1.03%   |
| Huawei Technologies        | 1         | 1.03%   |
| Hewlett-Packard            | 1         | 1.03%   |
| Broadcom                   | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 19.17%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 3.33%   |
| Intel Wireless 8265 / 8275                                             | 4         | 3.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 3.33%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 2.5%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 3         | 2.5%    |
| Intel Wireless 8260                                                    | 3         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                               | 3         | 2.5%    |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.5%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.67%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 1.67%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.67%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                | 2         | 1.67%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter               | 1         | 0.83%   |
| Shenzhen Goodix Fingerprint Reader                                     | 1         | 0.83%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.83%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.83%   |
| Intel Wireless 7260                                                    | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 60.34%  |
| Realtek Semiconductor | 9         | 15.52%  |
| MediaTek              | 4         | 6.9%    |
| Qualcomm Atheros      | 3         | 5.17%   |
| Broadcom Limited      | 3         | 5.17%   |
| Sitecom Europe        | 1         | 1.72%   |
| Ralink Technology     | 1         | 1.72%   |
| Qualcomm              | 1         | 1.72%   |
| Broadcom              | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 4         | 6.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 6.78%   |
| Intel Wi-Fi 6 AX200                                                  | 4         | 6.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 5.08%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 3         | 5.08%   |
| Intel Wireless 8260                                                  | 3         | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 5.08%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 3.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 3.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 3.39%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 3.39%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                              | 2         | 3.39%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter             | 1         | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 1.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.69%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 1         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 1.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 1.69%   |
| Intel Wireless 7260                                                  | 1         | 1.69%   |
| Intel Wireless 3165                                                  | 1         | 1.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.69%   |
| Intel Jasper Lake PCH CNVi WiFi                                      | 1         | 1.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 1         | 1.69%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                              | 1         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 57.14%  |
| Intel                 | 16        | 28.57%  |
| ASIX Electronics      | 4         | 7.14%   |
| MediaTek              | 2         | 3.57%   |
| Qualcomm Atheros      | 1         | 1.79%   |
| Huawei Technologies   | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 38.98%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 6.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 6.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 5.08%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 5.08%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 5.08%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 3.39%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 3.39%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 3.39%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 3.39%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.69%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.69%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 1.69%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.69%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.69%   |
| Huawei E353/E3131                                                      | 1         | 1.69%   |
| ASIX AX88772A Fast Ethernet                                            | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 50%     |
| Ethernet | 56        | 48.28%  |
| Modem    | 2         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 69.12%  |
| Ethernet | 21        | 30.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 71.43%  |
| 1     | 16        | 25.4%   |
| 0     | 2         | 3.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 82.54%  |
| Yes  | 11        | 17.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 52.73%  |
| Broadcom                        | 9         | 16.36%  |
| Realtek Semiconductor           | 6         | 10.91%  |
| IMC Networks                    | 6         | 10.91%  |
| Foxconn / Hon Hai               | 2         | 3.64%   |
| USI                             | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| MediaTek                        | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 10        | 18.18%  |
| Intel AX201 Bluetooth                            | 8         | 14.55%  |
| IMC Networks Wireless_Device                     | 5         | 9.09%   |
| Intel AX210 Bluetooth                            | 4         | 7.27%   |
| Intel AX200 Bluetooth                            | 4         | 7.27%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 5.45%   |
| Realtek Bluetooth Radio                          | 3         | 5.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 3.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 3.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 2         | 3.64%   |
| USI Bluetooth Device                             | 1         | 1.82%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 1.82%   |
| MediaTek Wireless_Device                         | 1         | 1.82%   |
| Intel Bluetooth Device                           | 1         | 1.82%   |
| IMC Networks Bluetooth Radio                     | 1         | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 1.82%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 1.82%   |
| Broadcom HP Portable Valentine                   | 1         | 1.82%   |
| Broadcom HP Portable SoftSailing                 | 1         | 1.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 1.82%   |
| Broadcom BCM20702A0                              | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                      | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 46        | 52.27%  |
| Nvidia                 | 20        | 22.73%  |
| AMD                    | 19        | 21.59%  |
| C-Media Electronics    | 1         | 1.14%   |
| ASUSTek Computer       | 1         | 1.14%   |
| AlfaPlus Semiconductor | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 14        | 13.46%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 7         | 6.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 5.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 5.77%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 5         | 4.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 4.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 4.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 3.85%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.88%   |
| AMD Radeon High Definition Audio Controller                                                       | 3         | 2.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.92%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.92%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.92%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.96%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.96%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 0.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.96%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 0.96%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.96%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.96%   |
| AlfaPlus Semiconductor MPOW Wireless Gaming Headset                                               | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 30.65%  |
| SK hynix            | 11        | 17.74%  |
| Kingston            | 9         | 14.52%  |
| Micron Technology   | 8         | 12.9%   |
| Crucial             | 5         | 8.06%   |
| Unknown             | 2         | 3.23%   |
| Corsair             | 2         | 3.23%   |
| Neo Forza           | 1         | 1.61%   |
| Nanya Technology    | 1         | 1.61%   |
| Innodisk            | 1         | 1.61%   |
| Essencore Limited   | 1         | 1.61%   |
| Elpida              | 1         | 1.61%   |
| A-DATA Technology   | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 3         | 4.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.55%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 3.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 3.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 3.03%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 3.03%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s           | 2         | 3.03%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 3.03%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.52%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.52%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.52%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.52%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Samsung RAM K3LK7K70BM-BGCP000 4GiB SODIMM LPDDR5 4266MT/s       | 1         | 1.52%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s          | 1         | 1.52%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.52%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.52%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.52%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.52%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s           | 1         | 1.52%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.52%   |
| Micron RAM 16ATF2G64HZ-2G1B1 16GB SODIMM DDR4 2133MT/s           | 1         | 1.52%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 28        | 51.85%  |
| DDR3   | 15        | 27.78%  |
| LPDDR5 | 3         | 5.56%   |
| LPDDR3 | 3         | 5.56%   |
| DDR5   | 3         | 5.56%   |
| LPDDR4 | 1         | 1.85%   |
| DDR2   | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 87.27%  |
| Row Of Chips | 6         | 10.91%  |
| Chip         | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 47.54%  |
| 4096  | 16        | 26.23%  |
| 16384 | 11        | 18.03%  |
| 2048  | 3         | 4.92%   |
| 32768 | 2         | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 18        | 31.58%  |
| 1600    | 11        | 19.3%   |
| 2667    | 8         | 14.04%  |
| 2133    | 3         | 5.26%   |
| 6400    | 2         | 3.51%   |
| 4800    | 2         | 3.51%   |
| 2400    | 2         | 3.51%   |
| 1867    | 2         | 3.51%   |
| 1334    | 2         | 3.51%   |
| 1333    | 2         | 3.51%   |
| 5600    | 1         | 1.75%   |
| 4267    | 1         | 1.75%   |
| 4266    | 1         | 1.75%   |
| 701     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| QinHeng CH340S | 1         | 100%    |

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
| Chicony Electronics                    | 16        | 28.57%  |
| Bison Electronics                      | 11        | 19.64%  |
| Realtek Semiconductor                  | 5         | 8.93%   |
| Microdia                               | 4         | 7.14%   |
| Luxvisions Innotech Limited            | 4         | 7.14%   |
| Syntek                                 | 3         | 5.36%   |
| Sonix Technology                       | 3         | 5.36%   |
| Quanta                                 | 3         | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 1.79%   |
| Samsung Electronics                    | 1         | 1.79%   |
| Logitech                               | 1         | 1.79%   |
| Lite-On Technology                     | 1         | 1.79%   |
| Lenovo                                 | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Bison HD Webcam                                                | 4         | 7.14%   |
| Chicony Integrated Camera                                      | 3         | 5.36%   |
| Bison Integrated Camera                                        | 3         | 5.36%   |
| Bison BisonCam,NB Pro                                          | 3         | 5.36%   |
| Syntek Integrated Camera                                       | 2         | 3.57%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 3.57%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 2         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 3.57%   |
| Chicony HP TrueVision HD Camera                                | 2         | 3.57%   |
| Chicony HD User Facing                                         | 2         | 3.57%   |
| Syntek USB2.0 Camera                                           | 1         | 1.79%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 1.79%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 1.79%   |
| Realtek Laptop Camera                                          | 1         | 1.79%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.79%   |
| Realtek Integrated Camera                                      | 1         | 1.79%   |
| Realtek EasyCamera                                             | 1         | 1.79%   |
| Realtek Bluetooth Radio                                        | 1         | 1.79%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 1.79%   |
| Quanta HP Webcam                                               | 1         | 1.79%   |
| Quanta ACER HD User Facing                                     | 1         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 1.79%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.79%   |
| Microdia Integrated Webcam                                     | 1         | 1.79%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.79%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 1.79%   |
| Lite-On Integrated Camera                                      | 1         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 1.79%   |
| Chicony Web Camera - FHD                                       | 1         | 1.79%   |
| Chicony USB 2.0 Camera                                         | 1         | 1.79%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.79%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 1.79%   |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 1.79%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 1.79%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.79%   |
| Chicony HP HD Camera                                           | 1         | 1.79%   |
| Chicony FJ Camera                                              | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 6         | 37.5%   |
| Synaptics                          | 3         | 18.75%  |
| STMicroelectronics                 | 2         | 12.5%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 12.5%   |
| Upek                               | 1         | 6.25%   |
| Shenzhen Goodix Technology         | 1         | 6.25%   |
| Elan Microelectronics              | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 18.75%  |
| STMicroelectronics Fingerprint Reader                           | 2         | 12.5%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 6.25%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 1         | 6.25%   |
| Synaptics WBDI Device                                           | 1         | 6.25%   |
| Synaptics TouchPad                                              | 1         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                                | 1         | 6.25%   |
| Unknown                                                         | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 25%     |
| Lenovo      | 1         | 25%     |
| Broadcom    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 25%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 25%     |
| Broadcom 5880                                              | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 58.46%  |
| 1     | 21        | 32.31%  |
| 2     | 5         | 7.69%   |
| 3     | 1         | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 16        | 47.06%  |
| Graphics card         | 5         | 14.71%  |
| Net/wireless          | 4         | 11.76%  |
| Multimedia controller | 3         | 8.82%   |
| Chipcard              | 3         | 8.82%   |
| Card reader           | 1         | 2.94%   |
| Camera                | 1         | 2.94%   |
| Bluetooth             | 1         | 2.94%   |

